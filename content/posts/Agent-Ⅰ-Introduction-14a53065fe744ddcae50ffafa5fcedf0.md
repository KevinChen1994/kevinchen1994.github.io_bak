---
title: "Agent Ⅰ Introduction"
date: "2024-06-20T07:07:00.000Z"
lastmod: "2024-06-24T11:50:00.000Z"
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
  id: "14a53065-fe74-4ddc-ae50-ffafa5fcedf0"
  created_time: "2024-06-20T07:07:00.000Z"
  last_edited_time: "2024-06-24T11:50:00.000Z"
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
      created_time: "2024-06-20T07:07:00.000Z"
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
            content: "Agent Ⅰ Introduction"
            link: null
          annotations:
            bold: false
            italic: false
            strikethrough: false
            underline: false
            code: false
            color: "default"
          plain_text: "Agent Ⅰ Introduction"
          href: null
  url: "https://www.notion.so/Agent-Introduction-14a53065fe744ddcae50ffafa5fcedf0"
  public_url: "https://kevinchen1994.notion.site/Agent-Introduction-14a53065fe744\
    ddcae50ffafa5fcedf0"
UPDATE_TIME: "2025-01-08T23:21:04.593Z"
EXPIRY_TIME: "2025-01-09T00:20:57.117Z"

---
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/katex@0.16.2/dist/katex.min.css" integrity="sha384-bYdxxUwYipFNohQlHt0bjN/LCpueqWz13HufFEV1SUatKs1cm4L6fFgCi1jT643X" crossorigin="anonymous">


## Overview


随着ChatGPT的流行，我们似乎觉得LLM能够帮我们解决任何问题，但是长时间使用下来，有一些问题LLM并不能很好的解决，比如我想让LLM基于一次考试后的全班试卷帮我统计某个班级的最高分、最低分、平均分，并且针对考试较差的学生提出针对性的建议。目前所有的LLM都无法直接做到，因为首先全班所有的试卷就已经够长了，LLM的上下文长度可能都不够，再就是LLM并不擅长做关于数字的内容，因为数字对于他来说就是token，他有可能并不清楚数字token之间的关系。


那这个问题怎么解决呢，那就是通过Agent来解决，我们让LLM作为大脑，让其拥有记忆功能来存储试卷内容，还可能让其调用工具，让其学会计算，对于他也不会的知识点，他还可以上网搜索学会了再来辅导学生。这是不是就有人工智能那味儿了。


Agent能够通过构建LLM与规划、记忆、工具和执行来完成复杂的任务，LLM在其中扮演的就是大脑的角色，通过将复杂任务进行拆解，并且通过调用工具和存储来逐一解决小任务，最终完成复杂的任务。Agent能够大大提升LLM的实用性，让其不仅仅是一个只会对话的模型，而是有了规划和思考的能力。


下图为Agent的构成的概要。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/01e26f63-8eec-47b0-99ef-0ddcd7aba4ec/agent-overview.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45FSPPWI6X%2F20250108%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250108T232057Z&X-Amz-Expires=3600&X-Amz-Signature=d302a3dceaaa4417b0e6e956a32e4823c454f9712ae1f55cc7867c3065e2b07e&X-Amz-SignedHeaders=host&x-id=GetObject)


## Memory


人类的大脑中有多种记忆模式，比如短期记忆，用于存储当下的一些信息，例如我们现在与人对话的上下文，还有长期记忆，用于存储我们的知识体系。Agent也是一样，短期记忆用于存储当前会话的上下文，一般通过模型的上下文窗口来解决，长期记忆用于存储知识库和历史行为，一般通过外部存储来解决。


短期记忆受模型上下文窗口限制，所以不会太长，随着上下文长度的增长，对于显存的占用也会同步增加，所以这部分我们尽量控制的短一些，如果是超长的上下文，我们也可以将其转换为长期记忆来存储。


长期记忆其实也就是RAG，我们通过外部向量存储知识库，可以快速检索和访问，因为向量库相对比较便宜，所以我们可以存储大量的知识以供Agent使用，并且向量库的内容我们还可以经常更新，让模型在不调整参数的同时就拥有了比较新的知识。


## Planning


### 无反馈规划


对于复杂的任务将其进行拆解能够帮助Agent更好的进行执行。


对于LLM来说，他并不会主动将任务进行拆解，我们可以通过CoT（Chain of Though）让其进行拆解复杂任务，“let's think step by step”就是一句魔法咒语，在prompt开头添加这句话，能够让模型分步骤解决问题，从而获得更高的准确率。


在CoT的基础上，还有ToT（Tree of Though）的方法，通过在每一步探索多个可能得路径，形成树状结构，再通过DFS或者BSF来评估每个步骤的有效性。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/caad19c9-e75d-4e81-a654-d8b7605df700/tot.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45FSPPWI6X%2F20250108%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250108T232057Z&X-Amz-Expires=3600&X-Amz-Signature=bc152b45b3fdec2bcdbe83954d56661875e79a92a62cc27dd1a47908f2b3a84f&X-Amz-SignedHeaders=host&x-id=GetObject)


还有一种方法是LLM+P，也就是通过外部规划期来进行长期规划，这种方法先将问题转化为PDDL格式，然后利用规划期生成方案，最终将这一方案转换为自然语言。本质上，规划步骤被外包给外部工具，假设特定领域的 PDDL 和合适的规划器可用，这在某些机器人设置中很常见，但在许多其他领域并不常见。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/0687d74d-ec28-4124-984b-192ba7e82461/llmP.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45FSPPWI6X%2F20250108%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250108T232057Z&X-Amz-Expires=3600&X-Amz-Signature=3664ddd1e6d847a328d238c09890bc9a55da8e272558eebb4f3de96c9104798c&X-Amz-SignedHeaders=host&x-id=GetObject)


### 有反馈规划


如果模型规划有问题也不能很好的解决复杂的问题，所以我们可以让Agent通过反馈来进行规划，以纠正以前的错误，这对于解决复杂的任务有着至关重要的作用，毕竟人类在解决复杂问题时也会通过复盘来迭代自己的方法。姚顺雨大佬的两篇论文就是解决这个问题。


ReAct通过结合特定任务的离散动作与语言描述，实现了LLM中融合推理和执行的能力。离散动作能够与现实环境进行交互，语言米哦啊哈苏则可能促进LLM产生基于自然语言的推理路径。这种策略不仅提高了LLM处理复杂问题的能力，还通过与外部环境直接交互，增强了模型在真实世界中的适应性和灵活性。


具体的就是通过一下prompt模板，让LLM思考其Though、Action、Observation。


```text
Thought: ...
Action: ...
Observation: ...
... (Repeated many times)
```


下图可以看到使用ReAct后的效果，并且对比了只使用推理（reason）和只使用执行（act）的区别。在使用了推理+执行后，模型可以很好的规划这个任务，并且根据每一步的结果来规划下一步需要做什么，最终得到正确的答案。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/a490c953-a74c-4835-a670-96188bc1f16f/ReAct.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45FSPPWI6X%2F20250108%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250108T232057Z&X-Amz-Expires=3600&X-Amz-Signature=d832b1f11b963dd35c118e5bcdba938c10d8f0f0dc2e696da188264471a6af13&X-Amz-SignedHeaders=host&x-id=GetObject)


传统的强化学习学习大量的训练样本和计算资源来让模型从错误中进行学习，Reflexion提出了一种新的框架，不通过更新模型的权重，而是通过自然语言的反馈来增强模型从错误中学习。


Reflexion有一个标准的RL设置，其中简历模型提供简单的二元奖励，动作空间遵守ReAct中的设置，其中特定于任务的动作空间通过语言进行增强，以实现复杂的推理步骤。每一次执行，执行者（Actor）都会基于观察状态生成文本和动作，执行后，评估者（Evaluator）会对执行者生成的内容计算奖励分数，自我反思模型（Self-reflection）会生成口头自我反思提示以协助执行者进行改进，对于效率低下的规划，因为会存储在长期记忆中，所以会被识别到一直没有完成，这时自我反思模型会考虑将其停止。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/076884f4-ee09-41cf-ae0d-6b39bd7e0f27/reflexion.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45FSPPWI6X%2F20250108%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250108T232057Z&X-Amz-Expires=3600&X-Amz-Signature=eed6e63ef384213214f4fbccb1fcf296e0773a4912305bda167fcc07294c43bb&X-Amz-SignedHeaders=host&x-id=GetObject)


## Tools


曾几何时，人们普遍认为“使用工具”是人和动物最大的区别，虽然现在人们不这么认为了，但是人类文明发展史很大程度上就是一部人类发明工具帮助人类做事情的历史。如果Agent也能像人类一样使用工具就能够大大提升LLM的能力范围。


比如LLM对数字不够敏感，可能很多加减法都会做错，但是如果他能够调用计算器，那多复杂的运算也能够准确的计算出来。还有很多工具，像是网页浏览、写代码、画图、调用API等等，都能够有效的提升LLM的能力。


以下是一些LLM使用工具的方法：


MRKL（Modular Reasoning, Knowledge and Language）包含一组专家模块，LLM作为路由器将查询路由到最合适的专家模块。


TALM（Tool Augmented Language Models）和Toolformer都是对LLM进行微调，让其学会使用外部工具API。


HuggingGPT是一个使用ChatGPT作为任务规划器的框架，根据模型描述选择HuggingFace平台中可用的模型，并根据执行结果总结响应。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/56d6065a-8a9f-4353-b13b-18c5ab114ade/huggingGPT.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45FSPPWI6X%2F20250108%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250108T232057Z&X-Amz-Expires=3600&X-Amz-Signature=79d95cefc9376e50d3d6e55fff669fd79c6529b151c465b79aeac2e11d1f1193&X-Amz-SignedHeaders=host&x-id=GetObject)


## Challenges


Agent虽然可以帮我们解决复杂的任务，但是仍然有很多限制和挑战。

- LLM的上下文长度有限，对于复杂的任务，需要记录很多步骤、指令、工具介绍等情况，很容易把上下文窗口占满从而影响Agent的能力。
- 在planning阶段如果出错，那Agent就很难得到正确的答案，或者走很多弯路，对资源消耗比较大，目前没有完美的解决方案。
- 自然语言的可靠性，当前的Agent都是依赖自然语言作为LLM与其他组件交流的工具，然而自然语言容易有歧义，文本格式错误也可能导致理解错误，所以成功率并不高。

## Summary


从相信LLM无所不能，到高频使用后的去魅，再到Agent解决复杂的问题，让我更加了解了LLM的能力边界，LLM更适合做一个大脑，通过结合不同的模块发挥更大的作用，但是目前来看局限性比较大，很多场景需要人工的设置一些规则才能让Agent有好的表现，所以未来还有很长的路要走，不过我们可以想一想目前哪些任务我们可以交给Agent去做，从而提高我们的效率，让我们更专注于做一些价值更高的事情。


## Citation


[LLM Powered Autonomous Agents](https://lilianweng.github.io/posts/2023-06-23-agent/)


[姚顺雨-从语言模型到语言智能体（From Language Models to Language Agents）](https://www.bilibili.com/video/BV1ju4y1e7Em/?spm_id_from=333.1245.0.0)

