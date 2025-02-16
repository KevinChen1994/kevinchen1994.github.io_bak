---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466RQI6RBHX%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250216T152209Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEDQaCXVzLXdlc3QtMiJGMEQCIDSxogITOMYZ7%2FjLv%2F2FVtBveahBlLEjjszNjTZFpvc7AiA\
  PU9HMrDHaMJd9gvY0fppCLMdPeTzhfvoBggl2VHuIqCr%2FAwhdEAAaDDYzNzQyMzE4MzgwNSIMR9\
  wgw5o887g0oz54KtwDG1Xc5j4ef6eZds%2BYTvFrCGIEkBsLhDfbS6oI9%2F6RIfe5w2nbTIiZxJI\
  TLkyVn1BdgFbcxqcHNxpo8gSU0eW1xrH8XGSClzbphLvWo6jYQIF7xYiVqg22hZRFfNt98oMICOj1\
  psBbIchxftnyhC9XXKj9GN3YgbKURkGwIDP8WDcKuNQ1oL5prvw7aB9ebKYXIXrvk1PFeHVzn1MkF\
  aGS9u4QRGa3EphdAzeZdQGFtnkfzntPNQ6BJ9n%2B2rHGaaG0nBKaGtVfSVf2FxiWuvOj8tLfpaaW\
  Jq1ye6TJpoFetHKLaSgAhGIVJJPN9SqoQt%2Bdfmspl2oEOOGND%2FpLyka7wUdQFho%2FK3DcvbS\
  G%2Bkwc9%2FhRq9gSLlPSOGGF5X%2Bu9Q6e9aNTTXJmqZpWSBUgEP4V%2FUuOylEn1GIteJ0F4fME\
  QETCsTUXfNQ%2FUaM5ZE4Xpkk27KLtso3ucw7EqQVMOvW1JuntUPoSmnQncz0%2FRuOaFx%2Bkv1S\
  xx81GLDnU8rP7ztg2uEPqz55cKaxUPLKIT0MdUXqQBRTlkXirW8R%2B2gNsqJic3bl0cmXwBRB39j\
  v46E5SNi0fQKm%2Beq4vi4vw9gL%2FkzYrnAGntBXqohkbX7PxHxIMNPQtUH4myYcK5%2BIwsZ%2F\
  HvQY6pgGYv%2BLpRqEZ5QjKR5wTZhD9xty8bSCxzpNHyu5HnCzzmTi9U1l7KP4B8MPweKqiuuKOts\
  6OOiv1Hz837dYuCxGsvS1vlYUCjnl50Q6ndu8JkVOFWcYZD83c3StsmIre2vv68FICHZKaJEBKmA1\
  x84o7bJaGUtEHe59Jqp%2F7zTmtfCJSmn3DVrxzJEgsVTsWQQiVh8c5tT93VDmxCI%2FF%2FrglXT\
  Jl8Fn7&X-Amz-Signature=37d575af2b11b5cff8181fe265dc86ef1b7735916fddc2bab6cc2b\
  d19b974992&X-Amz-SignedHeaders=host&x-id=GetObject"
series:
  - "Tech"
authors:
  - "陈猛"
tags:
  - "大模型微调"
categories:
  - "LLM"
summary: "对于大模型微调起来不仅需要很多计算资源（GPU），还需要大量的训练时间，PEFT通过高效微调模型，使得我们可以使用单卡去训练比较大的LLM。"
NOTION_METADATA:
  object: "page"
  id: "ef5aece1-aa0f-4934-b3dd-f3f305a7e191"
  created_time: "2023-08-25T08:02:00.000Z"
  last_edited_time: "2023-08-25T08:32:00.000Z"
  created_by:
    object: "user"
    id: "cc08a802-cdc1-4040-b261-957206a41bd5"
  last_edited_by:
    object: "user"
    id: "cc08a802-cdc1-4040-b261-957206a41bd5"
  cover:
    type: "file"
    file:
      url: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-a\
        e1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-Amz-A\
        lgorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-C\
        redential=ASIAZI2LB466YWM2ZG7E%2F20250216%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250216T152043Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJIMEYCIQDxDaPMMdJ9zODTRSxHaDQy8xwmqh1\
        5t4DJhCBKtkAX%2BQIhAJd8d2zYL17X5oy%2BkkRcMVHe6c%2Bj0gD4u%2BsOP8PAWXuiKv\
        8DCF0QABoMNjM3NDIzMTgzODA1IgwhUCS3pXhBy1kmOBEq3AMdq8jDcjz60GkMeoXQGQuSD\
        8QCXzfD3niyV%2F%2BWvws43N8VXa3WshTOzU6QboLT7s%2FW%2BBUZizmVzNTAVKWi8QRZ\
        l3l0%2BbHrVR9Bokt4%2BJRWJB87hRr06PQcKe%2BV%2BwhkLC8%2FFn1vyygkJxkSwVL4o\
        jfufWGNRbtU8VZ7UyPXgPOAPtDBeV6oHSf5XRQhVfcxRLlAq92P%2BSVbrNElI9N0w2SYuN\
        gh22dY8QyYBkS0oB%2BrbtDZpNMTWz9GtEIicfBKLgD%2Bz85YVPPtCvi6046WKXNH2E%2F\
        TAsf2Rlc%2BIOBbOa4NHxo7sVCfmBNMcaWQUky%2Bz0c%2BiYJFpPj4BOxC7OCVGYHXOck8\
        KKJOl261kgp4UTxLHEdlYyDIYY8xMnGsYXBr1k2TSl6RTrNV4PE6lJ3%2F8yv8QBSimNRHo\
        g%2FGHvJLtiWp%2BWpKjCWGfWI88a%2Fp6Z1H2o92fkF6KauaJxAuwBGx5qME9aE3C3xcog\
        KRs4QizxQuzVQhG0FpWv%2B6odnqQnt0w5BrYHkWhnhJf5wY%2FFHhIdZVvzG3pyjLRbLU6\
        eZVmyVwK5aRg19ZyEfgF6ZkoEEGo%2F1h0U%2BFtxym6XCE6mVjEGr27jEEMIrsEqcSe%2B\
        caVJ2vR2GW4l2NCOeLZeeZPjC%2Fn8e9BjqkARR%2FIWa%2FeIiu%2BB4wdQ71zxjoLLj%2\
        BlTeOXweLqNxZK04LKAuedlN6xzKvPF7Cfb8N%2BhkuupiUOZWr8f%2FUiANdRt%2B4NBAn\
        0zMts1a0Q9POqLIHTw%2B0hqDRK9nlv6b4hLFcvJlKcbcPTxTk40WaTTqTwFkLOe%2B4ydD\
        yjFL33xBl70r7O45LNldNS5ixf5w6RglnHe8SwXSW9tnqvTSjBwKY5W7kCYYv&X-Amz-Sig\
        nature=6d98bff4455045d3412dbffd3cdb7c3ff9c4c8a60ef2bfbf934d080c3a92d955\
        &X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-16T16:20:43.890Z"
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
      multi_select:
        - id: "f6345faf-6e79-413e-847a-3fb764a61e06"
          name: "Tech"
          color: "green"
    draft:
      id: "JiWU"
      type: "checkbox"
      checkbox: false
    Created time:
      id: "UBQ%7B"
      type: "created_time"
      created_time: "2023-08-25T08:02:00.000Z"
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
        - id: "1446ca36-aed8-4a52-ac2f-405939fd3168"
          name: "大模型微调"
          color: "red"
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
      rich_text:
        - type: "text"
          text:
            content: "对于大模型微调起来不仅需要很多计算资源（GPU），还需要大量的训练时间，PEFT通过高效微调模型，使得我们可以使用单卡去训练比较大的LLM\
              。"
            link: null
          annotations:
            bold: false
            italic: false
            strikethrough: false
            underline: false
            code: false
            color: "default"
          plain_text: "对于大模型微调起来不仅需要很多计算资源（GPU），还需要大量的训练时间，PEFT通过高效微调模型，使得我们可以使用单卡去训练比较大的\
            LLM。"
          href: null
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
            content: "PEFT"
            link: null
          annotations:
            bold: false
            italic: false
            strikethrough: false
            underline: false
            code: false
            color: "default"
          plain_text: "PEFT"
          href: null
  url: "https://www.notion.so/PEFT-ef5aece1aa0f4934b3ddf3f305a7e191"
  public_url: "https://kevinchen1994.notion.site/PEFT-ef5aece1aa0f4934b3ddf3f305a7e191"
UPDATE_TIME: "2025-02-16T15:22:14.752Z"
EXPIRY_TIME: "2025-02-16T16:22:07.216Z"

---
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/katex@0.16.2/dist/katex.min.css" integrity="sha384-bYdxxUwYipFNohQlHt0bjN/LCpueqWz13HufFEV1SUatKs1cm4L6fFgCi1jT643X" crossorigin="anonymous">


## Fine-Tuning


Pre-training后使用有标注的数据对模型进行微调，需要大量的有监督数据，预训练与微调之间存在gap，效果提升不够明显。代表模型EMLO、BERT、GPT1


## Prompt-Tuning系列


通过添加模版的方式，避免引入额外的参数，从而让语言模型能够在Zero-Shot，或者Few-Shot的场景下达到理想的效果。代表模型GPT3


### Discrete Prompt（离散Prompt）


离散Prompt是指将离散字符与在原始文本进拼接，且在训练中保持不变，这里保持不变是指这些离散字符的词向量（Word Embedding）在训练过程中保持不变。通常情况下，离散法不需要引入任何参数。


### Continuous Prompt（连续Prompt）


连续Prompt是指让模型在训练过程中，根据具体的上下文语义和任务目标对模板参数进行连续可调。因为在离散训练中，模板无法参与模型的训练环境，容易陷入局部最优，而如果将模版变为可以训练的参数，那么不同的样本可以在连续的向量空间中寻找合适的伪标记，同时也可以增强模型的泛化能力。因此，连续法需要引入少量的参数让模型在训练时进行参数更新。


### **Prefix Tuning （2021.01）**


_论文题目：Prefix-Tuning: Optimizing Continuous Prompts for Generation_


_论文地址：_[_https://arxiv.org/pdf/2101.00190.pdf _](https://arxiv.org/pdf/2101.00190.pdf)


_论文源码：_[_https://github.com/XiangLi1999/PrefixTuning_](https://github.com/XiangLi1999/PrefixTuning)


背景：1. 人工设计的离散Prompt模板成本高，并且模型对模板特别敏感，多一个字少一个字都可能造成较大的变化，并且效果可能不是最优的；2. 传统微调需要针对每一个下游任务单独保存一份模型的权重，训练成本太高。


基于此，Prefix Tuning提出了固定LM参数，为LM提供可训练的、特定任务的前缀，这样就可以针对不同的任务使用不同的前缀，并且也可以复用LM的参数了。其次，使用连续的Prompt，相比离散的Prompt效果更好。在实际使用中挑选任务相关的prefix与transformer进行组装，实现热插拔。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663OWRSRYH%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T152207Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJHMEUCIE1ldKKWH6g9gUO6xVTI0RtEjw%2FTbBDDOb%2FcTg1sAjXgAiEA%2Busq1nxRW%2FuXtMXGXAZCS4kB%2Bh2if8QxMVgfykQNdLMq%2FwMIXRAAGgw2Mzc0MjMxODM4MDUiDD9zE231EOhuDS7eMircAwpnR0IGTRyBCn3OqGqEqogrdRD2iDNU3%2BQ8lE3q%2FwEsweoIbsyjt0swKcDiL8OPp%2FhLg7wKVvW5z08ugX9gLA4podbVBSdEPGvCmC1QsNYWq5igtlKt6BkUNtEKI1ApGGuudWAwF3yAb0Ub8QjAAExKY4nimp2coeVdsDbXt%2F1JGIS6gd6iHY1EnnT4UOpjP%2FBXs3FhP14kK7koFjpqtm6pc9dBEsmEAhJ1s21u9tb9xLy5Er7zYfe2DDRPeYZbutGi%2BduX5H8obLGr0%2BeKtfERlZOwXuKRdiZ4poq5KpMgkDK9exjtyPGKrT08gxgh566aLBh1fCcxyGNoWkIZolRnG%2BsdNMTUjQcctvD7SXj9mKsHGyzcUjK1hyW8drsRh%2BQRq%2FX8IQovuG8qZaLBqx7Fc9Bn%2FNX9cMJd5ybVtSVphqpWfIP3jvfwauzHmBxNv3%2FtsPDpsyBqtqAQ7ufoIsb212NkdPg2mN7sRVtl5WOCZkMYzPz0nv4YW4UlmoRMweqVMSq3cPv5nbZRNz9NSAS%2FjnFjl4jx2ver3q%2FZq2riRBT5TSXcBp3obOkNG1su0mQD0%2BPqWsaGhSs8J4qqnRnCsA3SUfTnN6HlsU8kgWzwnzEWozQEV0aU7Ed%2FMJmhx70GOqUBMgl7akSToVaN8hY5jgwT6xvQeiAgs9YF%2BQfB82oKNUrdboAcJVG1nHG9n0KsDV%2BgJ06IcVvYpzkHFTDep7Sti1zitDk1V%2BSbRWvuSXTckLlMsYUxc0KW3WioT3T47xMlfV0tHgITtxlxjFSfFQFgkYkNm8SQUn7ZNoAS193DcRkqwGHFYdgDcgavPELpmHXj5Qkl%2B7nR8n2cadQJQKwBiatWWvwB&X-Amz-Signature=a286a0210f72a067d8e45affcc793f14e4d31e4d039136f427d8e0c841ba0688&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663OWRSRYH%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T152207Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJHMEUCIE1ldKKWH6g9gUO6xVTI0RtEjw%2FTbBDDOb%2FcTg1sAjXgAiEA%2Busq1nxRW%2FuXtMXGXAZCS4kB%2Bh2if8QxMVgfykQNdLMq%2FwMIXRAAGgw2Mzc0MjMxODM4MDUiDD9zE231EOhuDS7eMircAwpnR0IGTRyBCn3OqGqEqogrdRD2iDNU3%2BQ8lE3q%2FwEsweoIbsyjt0swKcDiL8OPp%2FhLg7wKVvW5z08ugX9gLA4podbVBSdEPGvCmC1QsNYWq5igtlKt6BkUNtEKI1ApGGuudWAwF3yAb0Ub8QjAAExKY4nimp2coeVdsDbXt%2F1JGIS6gd6iHY1EnnT4UOpjP%2FBXs3FhP14kK7koFjpqtm6pc9dBEsmEAhJ1s21u9tb9xLy5Er7zYfe2DDRPeYZbutGi%2BduX5H8obLGr0%2BeKtfERlZOwXuKRdiZ4poq5KpMgkDK9exjtyPGKrT08gxgh566aLBh1fCcxyGNoWkIZolRnG%2BsdNMTUjQcctvD7SXj9mKsHGyzcUjK1hyW8drsRh%2BQRq%2FX8IQovuG8qZaLBqx7Fc9Bn%2FNX9cMJd5ybVtSVphqpWfIP3jvfwauzHmBxNv3%2FtsPDpsyBqtqAQ7ufoIsb212NkdPg2mN7sRVtl5WOCZkMYzPz0nv4YW4UlmoRMweqVMSq3cPv5nbZRNz9NSAS%2FjnFjl4jx2ver3q%2FZq2riRBT5TSXcBp3obOkNG1su0mQD0%2BPqWsaGhSs8J4qqnRnCsA3SUfTnN6HlsU8kgWzwnzEWozQEV0aU7Ed%2FMJmhx70GOqUBMgl7akSToVaN8hY5jgwT6xvQeiAgs9YF%2BQfB82oKNUrdboAcJVG1nHG9n0KsDV%2BgJ06IcVvYpzkHFTDep7Sti1zitDk1V%2BSbRWvuSXTckLlMsYUxc0KW3WioT3T47xMlfV0tHgITtxlxjFSfFQFgkYkNm8SQUn7ZNoAS193DcRkqwGHFYdgDcgavPELpmHXj5Qkl%2B7nR8n2cadQJQKwBiatWWvwB&X-Amz-Signature=5c72a47cbefb246543c68fe2e78530b54966d1f5e4531b7a4bc2ff0ce5519555&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663OWRSRYH%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T152207Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJHMEUCIE1ldKKWH6g9gUO6xVTI0RtEjw%2FTbBDDOb%2FcTg1sAjXgAiEA%2Busq1nxRW%2FuXtMXGXAZCS4kB%2Bh2if8QxMVgfykQNdLMq%2FwMIXRAAGgw2Mzc0MjMxODM4MDUiDD9zE231EOhuDS7eMircAwpnR0IGTRyBCn3OqGqEqogrdRD2iDNU3%2BQ8lE3q%2FwEsweoIbsyjt0swKcDiL8OPp%2FhLg7wKVvW5z08ugX9gLA4podbVBSdEPGvCmC1QsNYWq5igtlKt6BkUNtEKI1ApGGuudWAwF3yAb0Ub8QjAAExKY4nimp2coeVdsDbXt%2F1JGIS6gd6iHY1EnnT4UOpjP%2FBXs3FhP14kK7koFjpqtm6pc9dBEsmEAhJ1s21u9tb9xLy5Er7zYfe2DDRPeYZbutGi%2BduX5H8obLGr0%2BeKtfERlZOwXuKRdiZ4poq5KpMgkDK9exjtyPGKrT08gxgh566aLBh1fCcxyGNoWkIZolRnG%2BsdNMTUjQcctvD7SXj9mKsHGyzcUjK1hyW8drsRh%2BQRq%2FX8IQovuG8qZaLBqx7Fc9Bn%2FNX9cMJd5ybVtSVphqpWfIP3jvfwauzHmBxNv3%2FtsPDpsyBqtqAQ7ufoIsb212NkdPg2mN7sRVtl5WOCZkMYzPz0nv4YW4UlmoRMweqVMSq3cPv5nbZRNz9NSAS%2FjnFjl4jx2ver3q%2FZq2riRBT5TSXcBp3obOkNG1su0mQD0%2BPqWsaGhSs8J4qqnRnCsA3SUfTnN6HlsU8kgWzwnzEWozQEV0aU7Ed%2FMJmhx70GOqUBMgl7akSToVaN8hY5jgwT6xvQeiAgs9YF%2BQfB82oKNUrdboAcJVG1nHG9n0KsDV%2BgJ06IcVvYpzkHFTDep7Sti1zitDk1V%2BSbRWvuSXTckLlMsYUxc0KW3WioT3T47xMlfV0tHgITtxlxjFSfFQFgkYkNm8SQUn7ZNoAS193DcRkqwGHFYdgDcgavPELpmHXj5Qkl%2B7nR8n2cadQJQKwBiatWWvwB&X-Amz-Signature=727e1e7724619cf828b0bd25f0faa060cdd4e75500a331456ad915f16a2925a9&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663OWRSRYH%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T152207Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJHMEUCIE1ldKKWH6g9gUO6xVTI0RtEjw%2FTbBDDOb%2FcTg1sAjXgAiEA%2Busq1nxRW%2FuXtMXGXAZCS4kB%2Bh2if8QxMVgfykQNdLMq%2FwMIXRAAGgw2Mzc0MjMxODM4MDUiDD9zE231EOhuDS7eMircAwpnR0IGTRyBCn3OqGqEqogrdRD2iDNU3%2BQ8lE3q%2FwEsweoIbsyjt0swKcDiL8OPp%2FhLg7wKVvW5z08ugX9gLA4podbVBSdEPGvCmC1QsNYWq5igtlKt6BkUNtEKI1ApGGuudWAwF3yAb0Ub8QjAAExKY4nimp2coeVdsDbXt%2F1JGIS6gd6iHY1EnnT4UOpjP%2FBXs3FhP14kK7koFjpqtm6pc9dBEsmEAhJ1s21u9tb9xLy5Er7zYfe2DDRPeYZbutGi%2BduX5H8obLGr0%2BeKtfERlZOwXuKRdiZ4poq5KpMgkDK9exjtyPGKrT08gxgh566aLBh1fCcxyGNoWkIZolRnG%2BsdNMTUjQcctvD7SXj9mKsHGyzcUjK1hyW8drsRh%2BQRq%2FX8IQovuG8qZaLBqx7Fc9Bn%2FNX9cMJd5ybVtSVphqpWfIP3jvfwauzHmBxNv3%2FtsPDpsyBqtqAQ7ufoIsb212NkdPg2mN7sRVtl5WOCZkMYzPz0nv4YW4UlmoRMweqVMSq3cPv5nbZRNz9NSAS%2FjnFjl4jx2ver3q%2FZq2riRBT5TSXcBp3obOkNG1su0mQD0%2BPqWsaGhSs8J4qqnRnCsA3SUfTnN6HlsU8kgWzwnzEWozQEV0aU7Ed%2FMJmhx70GOqUBMgl7akSToVaN8hY5jgwT6xvQeiAgs9YF%2BQfB82oKNUrdboAcJVG1nHG9n0KsDV%2BgJ06IcVvYpzkHFTDep7Sti1zitDk1V%2BSbRWvuSXTckLlMsYUxc0KW3WioT3T47xMlfV0tHgITtxlxjFSfFQFgkYkNm8SQUn7ZNoAS193DcRkqwGHFYdgDcgavPELpmHXj5Qkl%2B7nR8n2cadQJQKwBiatWWvwB&X-Amz-Signature=8b7276d351ec960ca59ded2f4afdaf13116f3ce7a947cb035d30905a6f9cf833&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663OWRSRYH%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T152207Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJHMEUCIE1ldKKWH6g9gUO6xVTI0RtEjw%2FTbBDDOb%2FcTg1sAjXgAiEA%2Busq1nxRW%2FuXtMXGXAZCS4kB%2Bh2if8QxMVgfykQNdLMq%2FwMIXRAAGgw2Mzc0MjMxODM4MDUiDD9zE231EOhuDS7eMircAwpnR0IGTRyBCn3OqGqEqogrdRD2iDNU3%2BQ8lE3q%2FwEsweoIbsyjt0swKcDiL8OPp%2FhLg7wKVvW5z08ugX9gLA4podbVBSdEPGvCmC1QsNYWq5igtlKt6BkUNtEKI1ApGGuudWAwF3yAb0Ub8QjAAExKY4nimp2coeVdsDbXt%2F1JGIS6gd6iHY1EnnT4UOpjP%2FBXs3FhP14kK7koFjpqtm6pc9dBEsmEAhJ1s21u9tb9xLy5Er7zYfe2DDRPeYZbutGi%2BduX5H8obLGr0%2BeKtfERlZOwXuKRdiZ4poq5KpMgkDK9exjtyPGKrT08gxgh566aLBh1fCcxyGNoWkIZolRnG%2BsdNMTUjQcctvD7SXj9mKsHGyzcUjK1hyW8drsRh%2BQRq%2FX8IQovuG8qZaLBqx7Fc9Bn%2FNX9cMJd5ybVtSVphqpWfIP3jvfwauzHmBxNv3%2FtsPDpsyBqtqAQ7ufoIsb212NkdPg2mN7sRVtl5WOCZkMYzPz0nv4YW4UlmoRMweqVMSq3cPv5nbZRNz9NSAS%2FjnFjl4jx2ver3q%2FZq2riRBT5TSXcBp3obOkNG1su0mQD0%2BPqWsaGhSs8J4qqnRnCsA3SUfTnN6HlsU8kgWzwnzEWozQEV0aU7Ed%2FMJmhx70GOqUBMgl7akSToVaN8hY5jgwT6xvQeiAgs9YF%2BQfB82oKNUrdboAcJVG1nHG9n0KsDV%2BgJ06IcVvYpzkHFTDep7Sti1zitDk1V%2BSbRWvuSXTckLlMsYUxc0KW3WioT3T47xMlfV0tHgITtxlxjFSfFQFgkYkNm8SQUn7ZNoAS193DcRkqwGHFYdgDcgavPELpmHXj5Qkl%2B7nR8n2cadQJQKwBiatWWvwB&X-Amz-Signature=ba53175fceca9a97575ba9e62c1689383cefcc00789aba3d34ae2c3f10b0dc20&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RDZ5HVUF%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T152208Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJHMEUCIHmw4WSj%2BC6tYZcRNCMW3bQZc5%2BIveHdN7X5NKlFQwuCAiEAuCnB%2BwMC8aAsG8aH9C9QntbRC54SowwPasXRCeTO0aQq%2FwMIXRAAGgw2Mzc0MjMxODM4MDUiDL%2B%2B1qgOPJ8riZZ0iyrcA3UL7M6Kdq0x1PL9xSEKLCovkURY5dal%2F4%2FtrBfM7BIH5qn5prSh23mOHhBrCsZrTvmENjZHIt52PonOz6jhCQlnt%2F4huIJOkLgiP9U9Ed8K%2BrJhAwql0t0UC8mc3J%2BaQM%2FlhleqI5RP10dC3rYu6jQKttdf4AvN3dYpWL30sN4t33GjoruMS8JnQvJrMUhSQULw0rMKRGsFipZDz%2BPazq13QEvJhLt27tyX3A%2FS%2FsZrXRqxnP1eWgpzOVtjmYvsCbp25iyLr09U76D%2FDMxFW%2F8rxXI3S3D3QHnu%2BRFtUI5Lve7GF2ce3ALbntdX2hCom5qYFtvtTNR9oRsb%2BM6AlKeKXE%2BDnTBuQlfg6UKMOZ45iLlOHKQ3XZfA1j9ORfacsxfwBGF1Z6THaOZqji78fYBP%2FY57zsFf3B%2B7o6Z3o74psTe0LKBzXnbRi4Sc2zeOLo%2FSN%2FdVdv2nf80QpUnZ6oTP%2B1A7zuJKLqL9aW2urgPSRuWoOW7qTe0%2BRvpUshenNecW07yRAqGTI1TYnwlqCxo7XD766PpVLZB34DJSMCOnrdM7EiNC5CdamCrrfoIqgaKXl6prxr3GFS2A3u96VmSPHTIZFT8mKeE6EWKOOnsyWPziRdJ0ca4oevVDMN%2Bjx70GOqUBQI21Y9DbkhhwYJmnDvPw1%2FYedzPqg0%2Bnwknyd9zPyiqCzVdsntCBkOv7dibm2svH834OZR6G84LT5txnilROW5FsSdFwiFvuxGXH7SZBr4S%2FXi0%2BK8Xtourq4JdA%2BvSRYZoljZ7CByN%2F7kIxHRbnPBcQnzV1keQmCYwtDE1OqkBfvagDQpevPrGfBlp0iO4PKB%2BC3MVlk9Yp4P6F0DZcJXfHNzlT&X-Amz-Signature=264b7f893f061bc121bbd72cfd215027bc98043fb6c91944b49308eeb5e152c3&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667LPS2D76%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T152208Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJHMEUCIQCaaNa%2Btcz%2BFblU9M57PaAp5A1OO8XaY08YHp5uLAM8UAIgRAr1PdzDiDDKcckTpMJkDFfvGg3NvTsg1WXZC28yWKUq%2FwMIXRAAGgw2Mzc0MjMxODM4MDUiDH2500YrISsAfVeoUyrcA1R66uuqhXTtWHQglz03BtZC1mXkvFKZJZdx45OP8GR2177eIaOIL%2FHuzzqJ5E6T6HJ8cz53BSS6l44XuEN1vJa0o9t4mnWc7Qn966d%2FFWqFJbcDzoqB9vaXE4NaPTyUm8mCyeYuEkxLUXyC0d63ATntnKC1uOjpNUbKUskGTTERqCsYQgATUtV5qO%2Bj%2BuK%2FZbH2Uvjz%2BLYEM%2BEDQSpoLhGThJXRV7hrGKmmFqZQr%2BgN5VayOIzV2FDRJpMBdsGMqGRTwxZ5VJjLm%2Bqy1f9Unwk1mC9xjxlXKid8fUMDpelGpYaj2mkfdtu0Ugsv6ztk9tD2rcbnlRRh7whxPROBXbWjYwHqworLFHLnSoOKofHXiRq1dNLeiwDXqaUnCkqFYXQYR69FLZOc2o%2FJzCiD%2BTML3i8Ev9A90TtMeJc%2BCVu9621Ey%2B4jn9woId1n6fydC4T0mO7imjAJh7an8M8Th1S%2BFkqrtr1pPrMZ4C3yjQP%2BwTUdyHeQgqgmGszR1%2FoOteRsL15qOMQ8uUu8pxzFixmA5Ikf%2FagK0p2JDE0Ae%2FZMMizUrsOnbvC5oOJtyJbypHDDEul6cZBgD6zwYqfm6Zx5Xp%2BEt1FhL4oOexRSBh2q9ik6SV8oMIBojHFNMLKix70GOqUBc%2B1ROE5NgPclDU7SBQCHJdfT4W9K9%2FEhHjP2TEpXrLPYP2gzlv4BHjkPibdXhjC2M2biJTre0ZPAO2KaAgezpqgUn3LNhZ4C1oLaYP2ceZbA7tKBz0hm%2FfVuV7RgLsP9xsHiVuScfH%2Fwjs5pEdFMVM9%2FzrpCMEPefKXj36Ny569K8T7U89hoSgNcRSgV8%2B%2FHYI4KQYu%2FCQ2iUINGQ8QhcC3ICNN4&X-Amz-Signature=ea89c39b2544e5b0f367aecd3b92413e1dae937c9f471d05cd85ae90a9631172&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663OWRSRYH%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T152207Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJHMEUCIE1ldKKWH6g9gUO6xVTI0RtEjw%2FTbBDDOb%2FcTg1sAjXgAiEA%2Busq1nxRW%2FuXtMXGXAZCS4kB%2Bh2if8QxMVgfykQNdLMq%2FwMIXRAAGgw2Mzc0MjMxODM4MDUiDD9zE231EOhuDS7eMircAwpnR0IGTRyBCn3OqGqEqogrdRD2iDNU3%2BQ8lE3q%2FwEsweoIbsyjt0swKcDiL8OPp%2FhLg7wKVvW5z08ugX9gLA4podbVBSdEPGvCmC1QsNYWq5igtlKt6BkUNtEKI1ApGGuudWAwF3yAb0Ub8QjAAExKY4nimp2coeVdsDbXt%2F1JGIS6gd6iHY1EnnT4UOpjP%2FBXs3FhP14kK7koFjpqtm6pc9dBEsmEAhJ1s21u9tb9xLy5Er7zYfe2DDRPeYZbutGi%2BduX5H8obLGr0%2BeKtfERlZOwXuKRdiZ4poq5KpMgkDK9exjtyPGKrT08gxgh566aLBh1fCcxyGNoWkIZolRnG%2BsdNMTUjQcctvD7SXj9mKsHGyzcUjK1hyW8drsRh%2BQRq%2FX8IQovuG8qZaLBqx7Fc9Bn%2FNX9cMJd5ybVtSVphqpWfIP3jvfwauzHmBxNv3%2FtsPDpsyBqtqAQ7ufoIsb212NkdPg2mN7sRVtl5WOCZkMYzPz0nv4YW4UlmoRMweqVMSq3cPv5nbZRNz9NSAS%2FjnFjl4jx2ver3q%2FZq2riRBT5TSXcBp3obOkNG1su0mQD0%2BPqWsaGhSs8J4qqnRnCsA3SUfTnN6HlsU8kgWzwnzEWozQEV0aU7Ed%2FMJmhx70GOqUBMgl7akSToVaN8hY5jgwT6xvQeiAgs9YF%2BQfB82oKNUrdboAcJVG1nHG9n0KsDV%2BgJ06IcVvYpzkHFTDep7Sti1zitDk1V%2BSbRWvuSXTckLlMsYUxc0KW3WioT3T47xMlfV0tHgITtxlxjFSfFQFgkYkNm8SQUn7ZNoAS193DcRkqwGHFYdgDcgavPELpmHXj5Qkl%2B7nR8n2cadQJQKwBiatWWvwB&X-Amz-Signature=a8c3af6339c155fdad4048d2a8938cb4defececf94dcb252bb1ddd8b7a198df6&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663OWRSRYH%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T152207Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJHMEUCIE1ldKKWH6g9gUO6xVTI0RtEjw%2FTbBDDOb%2FcTg1sAjXgAiEA%2Busq1nxRW%2FuXtMXGXAZCS4kB%2Bh2if8QxMVgfykQNdLMq%2FwMIXRAAGgw2Mzc0MjMxODM4MDUiDD9zE231EOhuDS7eMircAwpnR0IGTRyBCn3OqGqEqogrdRD2iDNU3%2BQ8lE3q%2FwEsweoIbsyjt0swKcDiL8OPp%2FhLg7wKVvW5z08ugX9gLA4podbVBSdEPGvCmC1QsNYWq5igtlKt6BkUNtEKI1ApGGuudWAwF3yAb0Ub8QjAAExKY4nimp2coeVdsDbXt%2F1JGIS6gd6iHY1EnnT4UOpjP%2FBXs3FhP14kK7koFjpqtm6pc9dBEsmEAhJ1s21u9tb9xLy5Er7zYfe2DDRPeYZbutGi%2BduX5H8obLGr0%2BeKtfERlZOwXuKRdiZ4poq5KpMgkDK9exjtyPGKrT08gxgh566aLBh1fCcxyGNoWkIZolRnG%2BsdNMTUjQcctvD7SXj9mKsHGyzcUjK1hyW8drsRh%2BQRq%2FX8IQovuG8qZaLBqx7Fc9Bn%2FNX9cMJd5ybVtSVphqpWfIP3jvfwauzHmBxNv3%2FtsPDpsyBqtqAQ7ufoIsb212NkdPg2mN7sRVtl5WOCZkMYzPz0nv4YW4UlmoRMweqVMSq3cPv5nbZRNz9NSAS%2FjnFjl4jx2ver3q%2FZq2riRBT5TSXcBp3obOkNG1su0mQD0%2BPqWsaGhSs8J4qqnRnCsA3SUfTnN6HlsU8kgWzwnzEWozQEV0aU7Ed%2FMJmhx70GOqUBMgl7akSToVaN8hY5jgwT6xvQeiAgs9YF%2BQfB82oKNUrdboAcJVG1nHG9n0KsDV%2BgJ06IcVvYpzkHFTDep7Sti1zitDk1V%2BSbRWvuSXTckLlMsYUxc0KW3WioT3T47xMlfV0tHgITtxlxjFSfFQFgkYkNm8SQUn7ZNoAS193DcRkqwGHFYdgDcgavPELpmHXj5Qkl%2B7nR8n2cadQJQKwBiatWWvwB&X-Amz-Signature=0953b60a1f7f534b7ef928c47b411c60868f36841ea60386c9b9da02b5561633&X-Amz-SignedHeaders=host&x-id=GetObject)


实验结果证明AdaLoRA效果好于LoRA，但是没好太多，个人认为方法是好方法，提升有限。


### QLoRA（2023.05）


论文题目：QLoRA: Efficient Finetuning of Quantized LLMs


论文源码：[https://github.com/artidoro/qlora](https://github.com/artidoro/qlora)


论文地址：[https://arxiv.org/pdf/2305.14314.pdf](https://arxiv.org/pdf/2305.14314.pdf)


背景：量化方法可以显著减少LLM的内存占用，然而只限于在推理阶段，基于此，QLoRA提出了在不降低性能的前提下，微调量化为4bit的LLM。


具体操作为将预训练模型量化到4bit，并且添加可以学习的低秩适配器权重，这些权重通过量化的反向传播梯度进行优化。QLoRA 有一种低精度存储数据类型（4 bit），还有一种计算数据类型（BFloat16）。实际上，这意味着无论何时使用 QLoRA 权重张量，我们都会将张量反量化为 BFloat16，然后执行 16 位矩阵乘法。QLoRA提出的一些新技术来实现了上述操作，具体为：

- **4bit NormalFloat(NF4)**：对于正态分布权重而言，一种信息理论上最优的新数据类型，该数据类型对正态分布数据产生比 4 bit整数和 4bit 浮点数更好的实证结果。
- **双量化**：对第一次量化后的那些常量再进行一次量化，减少存储空间。
- **分页优化器**：使用NVIDIA统一内存特性，该特性可以在在GPU偶尔OOM的情况下，进行CPU和GPU之间自动分页到分页的传输，以实现无错误的 GPU 处理。该功能的工作方式类似于 CPU 内存和磁盘之间的常规内存分页。使用此功能为优化器状态（Optimizer）分配分页内存，然后在 GPU 内存不足时将其自动卸载到 CPU 内存，并在优化器更新步骤需要时将其加载回 GPU 内存。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663OWRSRYH%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T152207Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJHMEUCIE1ldKKWH6g9gUO6xVTI0RtEjw%2FTbBDDOb%2FcTg1sAjXgAiEA%2Busq1nxRW%2FuXtMXGXAZCS4kB%2Bh2if8QxMVgfykQNdLMq%2FwMIXRAAGgw2Mzc0MjMxODM4MDUiDD9zE231EOhuDS7eMircAwpnR0IGTRyBCn3OqGqEqogrdRD2iDNU3%2BQ8lE3q%2FwEsweoIbsyjt0swKcDiL8OPp%2FhLg7wKVvW5z08ugX9gLA4podbVBSdEPGvCmC1QsNYWq5igtlKt6BkUNtEKI1ApGGuudWAwF3yAb0Ub8QjAAExKY4nimp2coeVdsDbXt%2F1JGIS6gd6iHY1EnnT4UOpjP%2FBXs3FhP14kK7koFjpqtm6pc9dBEsmEAhJ1s21u9tb9xLy5Er7zYfe2DDRPeYZbutGi%2BduX5H8obLGr0%2BeKtfERlZOwXuKRdiZ4poq5KpMgkDK9exjtyPGKrT08gxgh566aLBh1fCcxyGNoWkIZolRnG%2BsdNMTUjQcctvD7SXj9mKsHGyzcUjK1hyW8drsRh%2BQRq%2FX8IQovuG8qZaLBqx7Fc9Bn%2FNX9cMJd5ybVtSVphqpWfIP3jvfwauzHmBxNv3%2FtsPDpsyBqtqAQ7ufoIsb212NkdPg2mN7sRVtl5WOCZkMYzPz0nv4YW4UlmoRMweqVMSq3cPv5nbZRNz9NSAS%2FjnFjl4jx2ver3q%2FZq2riRBT5TSXcBp3obOkNG1su0mQD0%2BPqWsaGhSs8J4qqnRnCsA3SUfTnN6HlsU8kgWzwnzEWozQEV0aU7Ed%2FMJmhx70GOqUBMgl7akSToVaN8hY5jgwT6xvQeiAgs9YF%2BQfB82oKNUrdboAcJVG1nHG9n0KsDV%2BgJ06IcVvYpzkHFTDep7Sti1zitDk1V%2BSbRWvuSXTckLlMsYUxc0KW3WioT3T47xMlfV0tHgITtxlxjFSfFQFgkYkNm8SQUn7ZNoAS193DcRkqwGHFYdgDcgavPELpmHXj5Qkl%2B7nR8n2cadQJQKwBiatWWvwB&X-Amz-Signature=a43cdbb9c0c6fa4c6eaa6ca2ebadca6b26420ee76be77473a032ffa8e3d72fb0&X-Amz-SignedHeaders=host&x-id=GetObject)


## 总结


> 📌 P-tuning v1与Prompt tuning是比较类似的方法


P-tuning v1和Prompt tuning都是在**输入层**添加连续的虚拟token；


P-tuning v1插入虚拟token的位置可以是前缀，也可以插入到中间；


Prompt tuning是针对不同的任务设定不同的prompt，将prompt与特定任务的数据进行拼接作为输入；


P-tuning v1将prompt使用MLP+LSTM的方式对prompt进行embedding处理，这里起到的作用的加速训练，Prompt tuning不需要使用MLP进行向量化；


> 📌 P-tuning v2与Prefix tuning是比较类似的方法


Prefix tuning和P-tuning v2都是在**transformer的每一层**添加虚拟token；


Prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务;


Prefix tuning可以应用在decoder-only模型，也可以应用在encoder-decoder模型，P-tuning v2只能应用在decoder-only模型；


> 📌 LoRA系列


LoRA通过引入低秩的旁路网络（增量矩阵）可获得与全量微调相当的性能，且极大降低训练显存依赖（将GPT-3可调参数减少10000倍，GPU内存需求减少3倍）；LoRA需要预先设置相同增量矩阵的秩，忽略了不同权重参数的重要性差异，AdaLora对这一问题进行改进，通过引入SVD技术，达到对参数矩阵自适应分配秩的效果，从而获得了相较Lora更优的性能；与AdaLoRA思路不同，QLoRA在LoRA基础上，对大模型基座进行4-bit量化，同时引入双量化和分页优化，极大减少训练显存依赖，且效果与16-bit全量微调相当，QLoRA将65B Llama模型的显存需求从大于780G降低到小于48G，AdaLoRA和QLoRA可看作是对LoRA不同的两种改进方式。


## 参考文献


[https://mp.weixin.qq.com/s/E_0-skD3__w5jLGEJlDpoA](https://mp.weixin.qq.com/s/E_0-skD3__w5jLGEJlDpoA)


[https://mp.weixin.qq.com/s/webUB5j8nNQsthTFQNiqpA](https://mp.weixin.qq.com/s/webUB5j8nNQsthTFQNiqpA)


[https://mp.weixin.qq.com/s/8A7aLiknSDCBfMuUKg4eiw](https://mp.weixin.qq.com/s/8A7aLiknSDCBfMuUKg4eiw)


[https://zhuanlan.zhihu.com/p/636215898](https://zhuanlan.zhihu.com/p/636215898)

