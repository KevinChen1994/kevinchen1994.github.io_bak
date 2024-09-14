---
title: "Agent Ⅱ 手搓一个Agent feat. Qwen-Agent"
date: "2024-06-21T09:04:00.000Z"
lastmod: "2024-08-01T04:01:00.000Z"
draft: false
series: []
authors:
  - "陈猛"
tags:
  - "Agent"
categories:
  - "LLM"
NOTION_METADATA:
  object: "page"
  id: "fc43a67a-ce89-4bea-b359-4fd88154859d"
  created_time: "2024-06-21T09:04:00.000Z"
  last_edited_time: "2024-08-01T04:01:00.000Z"
  created_by:
    object: "user"
    id: "cc08a802-cdc1-4040-b261-957206a41bd5"
  last_edited_by:
    object: "user"
    id: "cc08a802-cdc1-4040-b261-957206a41bd5"
  cover: null
  icon: null
  parent:
    type: "database_id"
    database_id: "8d6a6f9d-5a2c-433b-a560-b744eab9db1a"
  archived: false
  in_trash: false
  properties:
    series:
      id: "B%3C%3FS"
      type: "multi_select"
      multi_select: []
    draft:
      id: "JiWU"
      type: "checkbox"
      checkbox: false
    Created time:
      id: "UBQ%7B"
      type: "created_time"
      created_time: "2024-06-21T09:04:00.000Z"
    authors:
      id: "bK%3B%5B"
      type: "people"
      people:
        - object: "user"
          id: "cc08a802-cdc1-4040-b261-957206a41bd5"
          name: "陈猛"
          avatar_url: "https://s3-us-west-2.amazonaws.com/public.notion-static.com/775523\
            b7-57cf-4c98-8ad8-8777d898666f/notion-avatar-1678713535269.png"
          type: "person"
          person:
            email: "346521888@qq.com"
    custom-front-matter:
      id: "c~kA"
      type: "rich_text"
      rich_text: []
    tags:
      id: "jw%7CC"
      type: "multi_select"
      multi_select:
        - id: "4a95f3da-c782-4564-aad4-12c28bae47a6"
          name: "Agent"
          color: "yellow"
    categories:
      id: "nbY%3F"
      type: "multi_select"
      multi_select:
        - id: "e417d9a1-8454-498a-b9de-502d57e26681"
          name: "LLM"
          color: "gray"
    summary:
      id: "x%3AlD"
      type: "rich_text"
      rich_text: []
    Date:
      id: "zYLY"
      type: "date"
      date: null
    Name:
      id: "title"
      type: "title"
      title:
        - type: "text"
          text:
            content: "Agent Ⅱ 手搓一个Agent feat. Qwen-Agent"
            link: null
          annotations:
            bold: false
            italic: false
            strikethrough: false
            underline: false
            code: false
            color: "default"
          plain_text: "Agent Ⅱ 手搓一个Agent feat. Qwen-Agent"
          href: null
  url: "https://www.notion.so/Agent-Agent-feat-Qwen-Agent-fc43a67ace894beab3594fd\
    88154859d"
  public_url: "https://kevinchen1994.notion.site/Agent-Agent-feat-Qwen-Agent-fc43\
    a67ace894beab3594fd88154859d"
UPDATE_TIME: "2024-09-14T18:27:54.663Z"
EXPIRY_TIME: "2024-09-14T19:27:42.778Z"

---
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/katex@0.16.2/dist/katex.min.css" integrity="sha384-bYdxxUwYipFNohQlHt0bjN/LCpueqWz13HufFEV1SUatKs1cm4L6fFgCi1jT643X" crossorigin="anonymous">


## 前言


上一篇文章介绍了关于Agent的一些相关内容，这篇文章来动手实现一个Agent。目前比较流行的Agent开发框架有很多，比如可视化的字节的扣子，还有代码实现的babyagi、AutoGPT，因为我用qwen用的比较多，正好我最近看到qwen也开源了一套框架，qwen-agents，封装了工具、助手和一些规划的方法，使用起来比较方便，那就用这套框架实现一个简单的Agent。


## Agent设计开发


既然是Agent，那就让他做一个LLM不能直接实现的任务，我这边有一个北京的房价表格，我们可以让Agent帮我们分析一下房价，最后生成一个图标来展示每平米的价格。


因为这个任务需要多步骤才能实现，所以我们可以使用上篇文章中将的ReAct的思路，让模型自己规划任务，根据每一次的执行结果来调整任务，并且可以利用代码助手来帮助他实现目标。


先配置LLM，这里可以使用阿里的api，也可以使用第三方的api，只要与openAI库兼容就可以。我这里尝试了付费的qwen-max和免费的Qwen2-7B-Instruct。


```python
llm_cfg = {
        # 使用 DashScope 提供的模型服务：
        # 'model': 'qwen-max',
        # 'model_server': 'dashscope',
        # 'api_key': 'EMPTY',
        # 如果这里没有设置 'api_key'，它将读取 `DASHSCOPE_API_KEY` 环境变量。

        # 使用与 OpenAI API 兼容的模型服务，例如 vLLM 或 Ollama：
        'model': 'alibaba/Qwen2-7B-Instruct',
        'model_server': 'http://localhost:8000/v1',  # base_url，也称为 api_base
        'api_key': 'EMPTY',

        # （可选） LLM 的超参数：
        'generate_cfg': {
            'top_p': 0.8
        }
    }
```


然后去定义我们的Agent，因为框架封装的很方便了，所以几行代码就可以实现。


可以看到我们只需要配置Agent能够使用的工具，以及Agent的名称，他能做什么就可以了。工具方面我这边只使用了代码解释器，框架还封装了很多其他的工具，比如联网搜索、图片生成（需要api支持）、RAG等。框架也支持自定义工具，可以根据自己的需要实现特定功能的工具。


```python
def init_agent_service():
    llm_cfg = {
    }
    tools = ['code_interpreter']
    bot = agents.ReActChat(llm=llm_cfg,
                           name='house price analyzer',
                           description='You are a house price analyzer, you can run code to analyze house price.',
                           function_list=tools)
    return bot
```


然后就可以配置测试的方法了，可以通过命令行进行测试，也可以通过GUI进行测试，框架基于gradio开发了很方便的GUI方法，我就选择GUI来进行测试。


这里可以提前写好建议的prompt和需要上传的文件，也可以在页面自己手动填写和上传。


```python
def app_gui():
    bot = init_agent_service()
    chatbot_config = {
        'prompt.suggestions': [{
            'text': '先使用pd.head()查看数据，然后帮我分析昌平区两居室的每平米均价，最后帮我画一个关于昌平区两居室房子面积与价格的折线图',
            'files': [os.path.join(ROOT_RESOURCE, 'lianjia.xlsx')]
        }]
    }
    gui.WebUI(bot, chatbot_config=chatbot_config).run()
```


最后运行程序就可以了。


## Agent实际效果


这里可以看到他根据我的指令，进行了思考，他需要先加载文件，然后通过pandas来查看数据，然后根据我的要求进行筛序，最后进行计算和画图。


接着他实现了代码，代码逻辑看上去没有啥问题，有一处小问题，那就是两居室可能不能使用等于2室来表示，而是包含2室，我们看看运行结果怎么样。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/0a5d54ec-a589-4509-b198-1000ca4d87cb/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240914%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240914T182742Z&X-Amz-Expires=3600&X-Amz-Signature=d2fbdc502deacb97b87ffc4d5e82dd30441483102039336b8663c66214361d00&X-Amz-SignedHeaders=host&x-id=GetObject)


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ac8ab89b-633f-4919-bfa6-2d86d28ae82b/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240914%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240914T182742Z&X-Amz-Expires=3600&X-Amz-Signature=15f5bb051e9dc1a0700862443341245213f0df3fa28755f3e397e38433b2d934&X-Amz-SignedHeaders=host&x-id=GetObject)


代码运行出错了，因为数据中并没有区域这一列，实际是Region，也没有居室这样的列名，接着他通过pandas查看了列名来确认具体的列名是什么。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/3b718e77-1946-4ac3-a089-866d3a754068/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240914%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240914T182742Z&X-Amz-Expires=3600&X-Amz-Signature=377875885dffda41c8266b8afb7ef1cec2116f31938ba13dbfde398f8e741af4&X-Amz-SignedHeaders=host&x-id=GetObject)


这次的代码没有问题了，字段使用都是正确的，两居室也是使用contains来表示。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/c090d249-4a2e-42b7-8bb1-b469afd6f8c5/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240914%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240914T182742Z&X-Amz-Expires=3600&X-Amz-Signature=e8e76ed07341d1e0da56868d14182830185b0981c233100540b6c9fdc96ff952&X-Amz-SignedHeaders=host&x-id=GetObject)


每平米房价跟房屋面积的图画出来了，看上去不错。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/356e3fa9-a7a7-4c14-97cc-a1053e50368c/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240914%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240914T182742Z&X-Amz-Expires=3600&X-Amz-Signature=b2f2c1e3ce9ac017d8d7a2a34fa64a2a29325ddda98ffd9afd6bdeb7ece62316&X-Amz-SignedHeaders=host&x-id=GetObject)


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/1cd562c0-28a7-486f-97c3-9f4878b101e2/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240914%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240914T182742Z&X-Amz-Expires=3600&X-Amz-Signature=e041f2525bea2a90e9ad8294bc28f3e2e200f551655ebc750bda49a010c181d1&X-Amz-SignedHeaders=host&x-id=GetObject)


尽管代码报错了，但是最终得到了答案，最后还给出了一些分析，很好的完成了我的任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/95839a71-f818-4faa-83e2-c4d89d13fb1c/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240914%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240914T182742Z&X-Amz-Expires=3600&X-Amz-Signature=100ce2357109a401864e50f21c971094a673e0d558c699012dbc65526ac73f36&X-Amz-SignedHeaders=host&x-id=GetObject)


## 总结


房价分析Agent很好的完成了我的任务，尽管过程中有出现一些错误，但是经过ReAct的这种观测、思考最终还是顺利的完成了。


其实实际运行中，Agent并不是一次性就完成了我的任务，中间运行了好多次都是错误的结果，要么是代码写的有问题，要么就是观测的结果与思考有问题，所以想要Agent完全代替人的工作为时尚早。


Agent相比于LLM来说，确实更加智能，但是其中需要人根据具体的任务去设计Agent，如果是复杂的任务，可能需要多个Agent来协作，这就涉及到了上篇文章讲到的挑战了，复杂的任务通常需要很多步骤才能完成，那LLM的上下文长度就会成为瓶颈。根据这次的经验，LLM通过自然语言作为接口来进行交互难免出错，所以还是需要提升LLM的能力，让其成为一个合格的大脑。

