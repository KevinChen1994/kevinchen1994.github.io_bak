---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466WVLYASL4%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250219T232231Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEIf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIBL2HA8%2F1fIrCLZf7\
  FnrZBbSRLkdY4Yc6DrkabGUBjhpAiARJxLBgpz8%2FPmTSJSQsGSiu0T7ZrBoSNzDSZfoClUmjCqI\
  BAiw%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMMyScxu17svihks%2B\
  LKtwDmN0COpAKGU3VyRtqoG%2BepkG3wkPviMIOWCxdnHY75FvYFs6DYQm5CRRQNVIuwQ4h7zavFX\
  PWtGMYzrYzieCD1Ip36BeIik7VA9mu53Q7vA3hG2rD4OUj%2Bj0VZ0YZXXKaGlFdEnXlPhInBC8ga\
  zNcPmdisBc446bqQZQ3WIoV%2FiWp1gOj91oeeMwb5ot%2FeC6ocKbSBvbq8hCwUpziMX1z4dRP5S\
  r0VeKcQXdDxdXp2G40s8bVgVHki%2F7vJWt9gjOt7WqydxYbPsbZJJk3ZXm8JToPTcRP5gxjiQ2fM\
  lVVRx%2BKsIewAFMEPqm90BspeUrX4zfrylL9PkmSbjnEpuupQeLhPBeT%2F7d7iDXjy8UN3dtzCP\
  WX03qtol4UuV%2B6B6MyRu0QMW86t31T7qgcnkLsDMPcD3qu6se9uJ%2BhKU2fNv4uT79mlj%2FOJ\
  VDxAjH38Lt3cPCQX8WR9G%2BRvvT7o5UYzaQ1V9z6ohqcH8Emzeotovt7be0XDQ3yqkwwUghHomm8\
  xPjGoXJDYSNuOXqYEkNhNG30U9Btq%2BwsHK%2BJwyf399OMJTsxns%2F3Bf9z9jwd6DUhQxsXxK5\
  oLkxyjv7cKGXgY8UkLk5o7vGxNKgPN3%2BIQtvSFpe9H%2B8RN1vrCrcwssnZvQY6pgGXSr%2BtBt\
  Vwb6udBMmxlbQ%2BelczjnvwMuuMtzx6ZjlaYu6yIhZvZGzp24xA87Kt8Fy9eV1TmtU%2Bb%2Frju\
  TeGZGrBA9mIMsxip9JKzFFLcWA9r79rB4tSwqTp4I66Hy7MFO08uGVbAP9FIf%2BAbrSveSAI4P5Z\
  Yh7%2FeT9mfQzpJz6kEgzIqcdmw%2FyOf%2B7bPQcIVIrZFHDDObRJOuMXYO3Oita4%2BgOFHe2R&\
  X-Amz-Signature=520d0ca01ebfea118bd881ebdcb4f3a52e559f499aefc212550d346239405\
  dc5&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4666CGY3OMV%2F20250219%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250219T232100Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEIf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIB11Sg3YTviBtLaSCB33G1VpTMz5YIogNl3XXvnuRYqiAiEAtT%2FwjrKYFr8bBkIM07CX\
        I5d8HC%2BGxjfc2opTnV0GqJ8qiAQIsP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2M\
        zc0MjMxODM4MDUiDM4L1qWQDSOTRupiWSrcAyFbWJBDUwt8%2FLPnRP5camAB9sX5quCjE4\
        C7CMCALMJnNd%2F9nhbOGON6a0aqmajCLZvUb%2BozpjfWNCbsWaECIUeVNiXYPy%2B7t1Y\
        DfmbAA%2Fj6S9KE%2BFQiRunv%2FWbKZXwkPdaIKBbpxp9jLT5AYH52vzIdjVkR6nniW8z1\
        hpoMruJv6qllM69tCiYhidWerXXdl%2F4EKBwiKdQUJ59%2FS1wgnaWLHEUAi0UzWXC9cko\
        HTopxz%2FG6QbI3ufmjYxgN9ntwanvKAxabl%2FjsbG9q53OAVCbK%2FCFVSwqGT7e7bdMu\
        %2B1PVUy8coEXnptBmpoOdJxfSno5FYeKJ4WbVfq5o2h31FS4LAyN1IKk4rqzLEcnrk4FSi\
        j1%2F1pSqaTqsQOOPMryTD3RvrHTAofTYuy1%2BHMXgPkrpyo%2BEhk%2FeRwbkvC9LcYQd\
        w4CuPp8iVFWiHGFustdYpTxW435xhSFYCYQXn0RHamtRh24DwFaH40eGofe7Awyg8o6Qw%2\
        FX%2BSQdkJGP4cx1vxBtqgpRuY1BEs94XOobeRDIRsRViFGCWHXlblYtLFbp4XEGp%2BBbe\
        nyCGpkUycSeUF2BLv0k5Zs5RB0G0kYuN0EtmNRhI218PG6FJ%2Fbkavd0X7GetyQudCpIBX\
        zCIMKHK2b0GOqUBq%2Ff2O95hZZercYyx96rO7fcaW2q56KBjOKsKWoUgNzh0TFY07Q4eBS\
        6gmd9exBZ%2B2rWJr8z%2FmlLtY0%2FAyoBIGaFIHbGiuPYejSyVfakwWi%2BNWrNFMGtuI\
        dqmZVaaQIXmj5S8xO90j9PRZRChpVgRuU39E%2B9ftQEn%2BwHL2RinC7cJkAHzuINhhk%2\
        F6EiGnVFN8THWgs5LAljMIA7pZ30FdlJjrWinU&X-Amz-Signature=f5dc2979661ac201\
        c5ef11f0e7f995fa9f3c6278f3d5bd70d858b4dcefe86a47&X-Amz-SignedHeaders=ho\
        st&x-id=GetObject"
      expiry_time: "2025-02-20T00:21:00.508Z"
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
UPDATE_TIME: "2025-02-19T23:22:42.271Z"
EXPIRY_TIME: "2025-02-20T00:22:29.056Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RFNFZ3N2%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T232229Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAEEKHO%2FbkcnWTiIiws3egpYlscES2ykBcINzdGHPcxdAiAYkaYykmBx8dK03nl9TmohxyMJNwnIvDNeISCczW%2FFdiqIBAiw%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMqYeNvP0B%2BYoL5CUfKtwDr%2FGRcJN6iuMD8aSmcmUBW38sEQqXTO2KNheB%2B7tDstoq2buVnPWQXGO1jh8XkTRGulqF8MwqZKRXTnt%2FVliFS5ekqHSsiubyOEGduG3kZrbU3n2lc9MHt9XM%2FhvAdykhRkfCyb0lAWCYV2Jkls7%2FhtVuZPo2kx5LzkN%2Fnd3NYKwBP3MNLCLos10PS7%2FnjHzxC3aZWql9wa2SWVKNzBGdYf1Q8HvohN9RBBf1DgsrEv1sVUvJkb2v6wZeha%2FzPDPGV7VBu%2B2uFkzE3%2FbXIGZM3PnCYHlp4EjVftP68MtwI9aIT24EvvBhgS1pnz9H%2BeEV0N7zKX0lCjgwatA6qPjXihAl1%2B864ggS2v3luV%2BUXZv10nytfNi8LoSK5GBYUPZUD7ZFrd8gcLAa%2BHsVOzAIwtfpNBVDJPiCpcmL394OVGzeNsRuCnYYumBjTcZL3Agora%2FUSOCP5zJ5A833XJtnf17QDLIyWofhO78Vj39t0KW9JkCYuP%2Bikfobsq9meOP2X3EhUfIs5orrweirx4ih%2FWM58O%2FMd%2B4vZUsiRQjdnb1dP6YbxSE0sJqj7UjBlCtWEVwjBuKYoKe%2ByEgLW2PNDO%2BtCrYWWc9ZaBWEnLxUHMctM6ix%2FHdtFpoaQT0wosnZvQY6pgF6Rh%2FRQKdsYb%2F%2F56YSVUVZ1f9nPk4uCgC%2Fv49xC%2FNn6sJ95LRkprvQvrlFiQIGLgKG3tJw%2FKANOy70EAqtjNuJCs%2BlTdwQvbKB9I0wwgHCjsC0g6ahcUEo1efRSqL31WP57EpcGbCEYtQzQ7YUFstBKoSftDsWaH%2BqOrZqW5F2%2B%2FcVJdWoaJP7g3uyEJrkcUTvTNAaJfVnyAuIDZUXklnAJu%2Fbir7T&X-Amz-Signature=f136ff91a3a5044e048c3ab83f6a6fadf222861a7e90d7f13cacf17f71329572&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RFNFZ3N2%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T232229Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAEEKHO%2FbkcnWTiIiws3egpYlscES2ykBcINzdGHPcxdAiAYkaYykmBx8dK03nl9TmohxyMJNwnIvDNeISCczW%2FFdiqIBAiw%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMqYeNvP0B%2BYoL5CUfKtwDr%2FGRcJN6iuMD8aSmcmUBW38sEQqXTO2KNheB%2B7tDstoq2buVnPWQXGO1jh8XkTRGulqF8MwqZKRXTnt%2FVliFS5ekqHSsiubyOEGduG3kZrbU3n2lc9MHt9XM%2FhvAdykhRkfCyb0lAWCYV2Jkls7%2FhtVuZPo2kx5LzkN%2Fnd3NYKwBP3MNLCLos10PS7%2FnjHzxC3aZWql9wa2SWVKNzBGdYf1Q8HvohN9RBBf1DgsrEv1sVUvJkb2v6wZeha%2FzPDPGV7VBu%2B2uFkzE3%2FbXIGZM3PnCYHlp4EjVftP68MtwI9aIT24EvvBhgS1pnz9H%2BeEV0N7zKX0lCjgwatA6qPjXihAl1%2B864ggS2v3luV%2BUXZv10nytfNi8LoSK5GBYUPZUD7ZFrd8gcLAa%2BHsVOzAIwtfpNBVDJPiCpcmL394OVGzeNsRuCnYYumBjTcZL3Agora%2FUSOCP5zJ5A833XJtnf17QDLIyWofhO78Vj39t0KW9JkCYuP%2Bikfobsq9meOP2X3EhUfIs5orrweirx4ih%2FWM58O%2FMd%2B4vZUsiRQjdnb1dP6YbxSE0sJqj7UjBlCtWEVwjBuKYoKe%2ByEgLW2PNDO%2BtCrYWWc9ZaBWEnLxUHMctM6ix%2FHdtFpoaQT0wosnZvQY6pgF6Rh%2FRQKdsYb%2F%2F56YSVUVZ1f9nPk4uCgC%2Fv49xC%2FNn6sJ95LRkprvQvrlFiQIGLgKG3tJw%2FKANOy70EAqtjNuJCs%2BlTdwQvbKB9I0wwgHCjsC0g6ahcUEo1efRSqL31WP57EpcGbCEYtQzQ7YUFstBKoSftDsWaH%2BqOrZqW5F2%2B%2FcVJdWoaJP7g3uyEJrkcUTvTNAaJfVnyAuIDZUXklnAJu%2Fbir7T&X-Amz-Signature=71374a4149c970be280589f7498d9d2e518399c070e0d4ee04b298b9f20ee2d9&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RFNFZ3N2%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T232229Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAEEKHO%2FbkcnWTiIiws3egpYlscES2ykBcINzdGHPcxdAiAYkaYykmBx8dK03nl9TmohxyMJNwnIvDNeISCczW%2FFdiqIBAiw%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMqYeNvP0B%2BYoL5CUfKtwDr%2FGRcJN6iuMD8aSmcmUBW38sEQqXTO2KNheB%2B7tDstoq2buVnPWQXGO1jh8XkTRGulqF8MwqZKRXTnt%2FVliFS5ekqHSsiubyOEGduG3kZrbU3n2lc9MHt9XM%2FhvAdykhRkfCyb0lAWCYV2Jkls7%2FhtVuZPo2kx5LzkN%2Fnd3NYKwBP3MNLCLos10PS7%2FnjHzxC3aZWql9wa2SWVKNzBGdYf1Q8HvohN9RBBf1DgsrEv1sVUvJkb2v6wZeha%2FzPDPGV7VBu%2B2uFkzE3%2FbXIGZM3PnCYHlp4EjVftP68MtwI9aIT24EvvBhgS1pnz9H%2BeEV0N7zKX0lCjgwatA6qPjXihAl1%2B864ggS2v3luV%2BUXZv10nytfNi8LoSK5GBYUPZUD7ZFrd8gcLAa%2BHsVOzAIwtfpNBVDJPiCpcmL394OVGzeNsRuCnYYumBjTcZL3Agora%2FUSOCP5zJ5A833XJtnf17QDLIyWofhO78Vj39t0KW9JkCYuP%2Bikfobsq9meOP2X3EhUfIs5orrweirx4ih%2FWM58O%2FMd%2B4vZUsiRQjdnb1dP6YbxSE0sJqj7UjBlCtWEVwjBuKYoKe%2ByEgLW2PNDO%2BtCrYWWc9ZaBWEnLxUHMctM6ix%2FHdtFpoaQT0wosnZvQY6pgF6Rh%2FRQKdsYb%2F%2F56YSVUVZ1f9nPk4uCgC%2Fv49xC%2FNn6sJ95LRkprvQvrlFiQIGLgKG3tJw%2FKANOy70EAqtjNuJCs%2BlTdwQvbKB9I0wwgHCjsC0g6ahcUEo1efRSqL31WP57EpcGbCEYtQzQ7YUFstBKoSftDsWaH%2BqOrZqW5F2%2B%2FcVJdWoaJP7g3uyEJrkcUTvTNAaJfVnyAuIDZUXklnAJu%2Fbir7T&X-Amz-Signature=da5805a55fba7ec36ddbff809b2d6d3ca79abac369cd6d01dfe9abbc33fe4ff2&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RFNFZ3N2%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T232229Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAEEKHO%2FbkcnWTiIiws3egpYlscES2ykBcINzdGHPcxdAiAYkaYykmBx8dK03nl9TmohxyMJNwnIvDNeISCczW%2FFdiqIBAiw%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMqYeNvP0B%2BYoL5CUfKtwDr%2FGRcJN6iuMD8aSmcmUBW38sEQqXTO2KNheB%2B7tDstoq2buVnPWQXGO1jh8XkTRGulqF8MwqZKRXTnt%2FVliFS5ekqHSsiubyOEGduG3kZrbU3n2lc9MHt9XM%2FhvAdykhRkfCyb0lAWCYV2Jkls7%2FhtVuZPo2kx5LzkN%2Fnd3NYKwBP3MNLCLos10PS7%2FnjHzxC3aZWql9wa2SWVKNzBGdYf1Q8HvohN9RBBf1DgsrEv1sVUvJkb2v6wZeha%2FzPDPGV7VBu%2B2uFkzE3%2FbXIGZM3PnCYHlp4EjVftP68MtwI9aIT24EvvBhgS1pnz9H%2BeEV0N7zKX0lCjgwatA6qPjXihAl1%2B864ggS2v3luV%2BUXZv10nytfNi8LoSK5GBYUPZUD7ZFrd8gcLAa%2BHsVOzAIwtfpNBVDJPiCpcmL394OVGzeNsRuCnYYumBjTcZL3Agora%2FUSOCP5zJ5A833XJtnf17QDLIyWofhO78Vj39t0KW9JkCYuP%2Bikfobsq9meOP2X3EhUfIs5orrweirx4ih%2FWM58O%2FMd%2B4vZUsiRQjdnb1dP6YbxSE0sJqj7UjBlCtWEVwjBuKYoKe%2ByEgLW2PNDO%2BtCrYWWc9ZaBWEnLxUHMctM6ix%2FHdtFpoaQT0wosnZvQY6pgF6Rh%2FRQKdsYb%2F%2F56YSVUVZ1f9nPk4uCgC%2Fv49xC%2FNn6sJ95LRkprvQvrlFiQIGLgKG3tJw%2FKANOy70EAqtjNuJCs%2BlTdwQvbKB9I0wwgHCjsC0g6ahcUEo1efRSqL31WP57EpcGbCEYtQzQ7YUFstBKoSftDsWaH%2BqOrZqW5F2%2B%2FcVJdWoaJP7g3uyEJrkcUTvTNAaJfVnyAuIDZUXklnAJu%2Fbir7T&X-Amz-Signature=2eb4bc4b49772b84a1eca3c4a8ee966d8a41fb0d9d841f1773fe47e248a93192&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RFNFZ3N2%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T232229Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAEEKHO%2FbkcnWTiIiws3egpYlscES2ykBcINzdGHPcxdAiAYkaYykmBx8dK03nl9TmohxyMJNwnIvDNeISCczW%2FFdiqIBAiw%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMqYeNvP0B%2BYoL5CUfKtwDr%2FGRcJN6iuMD8aSmcmUBW38sEQqXTO2KNheB%2B7tDstoq2buVnPWQXGO1jh8XkTRGulqF8MwqZKRXTnt%2FVliFS5ekqHSsiubyOEGduG3kZrbU3n2lc9MHt9XM%2FhvAdykhRkfCyb0lAWCYV2Jkls7%2FhtVuZPo2kx5LzkN%2Fnd3NYKwBP3MNLCLos10PS7%2FnjHzxC3aZWql9wa2SWVKNzBGdYf1Q8HvohN9RBBf1DgsrEv1sVUvJkb2v6wZeha%2FzPDPGV7VBu%2B2uFkzE3%2FbXIGZM3PnCYHlp4EjVftP68MtwI9aIT24EvvBhgS1pnz9H%2BeEV0N7zKX0lCjgwatA6qPjXihAl1%2B864ggS2v3luV%2BUXZv10nytfNi8LoSK5GBYUPZUD7ZFrd8gcLAa%2BHsVOzAIwtfpNBVDJPiCpcmL394OVGzeNsRuCnYYumBjTcZL3Agora%2FUSOCP5zJ5A833XJtnf17QDLIyWofhO78Vj39t0KW9JkCYuP%2Bikfobsq9meOP2X3EhUfIs5orrweirx4ih%2FWM58O%2FMd%2B4vZUsiRQjdnb1dP6YbxSE0sJqj7UjBlCtWEVwjBuKYoKe%2ByEgLW2PNDO%2BtCrYWWc9ZaBWEnLxUHMctM6ix%2FHdtFpoaQT0wosnZvQY6pgF6Rh%2FRQKdsYb%2F%2F56YSVUVZ1f9nPk4uCgC%2Fv49xC%2FNn6sJ95LRkprvQvrlFiQIGLgKG3tJw%2FKANOy70EAqtjNuJCs%2BlTdwQvbKB9I0wwgHCjsC0g6ahcUEo1efRSqL31WP57EpcGbCEYtQzQ7YUFstBKoSftDsWaH%2BqOrZqW5F2%2B%2FcVJdWoaJP7g3uyEJrkcUTvTNAaJfVnyAuIDZUXklnAJu%2Fbir7T&X-Amz-Signature=6e8fef5de9083774b897b1cf6647b920fc2e92b8b8b2c67049b1f399c3654c78&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UCJORFTQ%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T232229Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIED3%2BzHXm2v6DGxJXFFwBTjKSotxErPi%2BSo3up4e%2BpaMAiEAicoXjCWU%2FEo5DXU9zHsR3jR%2FQ%2BK1%2FFP1GqWOjUniwNEqiAQIsP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDAg%2Bmyb6vVzxRB7rpSrcA62av7PkyTb7P%2FcPgqbK%2BhKsRDTQEseEaFDsG%2Fnn1xbd3iqZxUkuJAsgULzO4Xut4QLZ7OBqC1pmSlzNkEBpcTiQSMkRdY7fRFL0vBdQCJ9qdN628Qh9NrXvAs0WN4eymtj32NSHjjGxyJcSH2n16AoCtj0gxNIYQTnq3HXMMHXybXZWTkHfFVr3xoD1jNeLDFRrbQlJM3uqIe9xlSd4vaefYixK6dEj0%2BofUCwvg2ESl%2BmCs78xiEdDUhVH1baYzJyVkMq1ng1XMGQ8Bz0CU2sgNld7IJgiXKi0VITZWnq1vJGNsL5kag0JaPQJaLt3iDhuNTW5Wz%2F8AvDd0sLMBJ71%2BSbsKbw%2BAB3Lo9GYMWdPuk7IxKy6wB9sRYIGeECSa6Wv%2F8A%2BqDLMZUD1EPnlveaJWrHcpXd%2F6lmThb9xvAq3zq4B%2BfE5EPNJqniP%2BgFWkYT91kWnJZYSYp7p6LUyiD3q3NrsT38WxqWwsIYXT5EiPn8W13Vvl%2FyGIp2i%2Bcnwg1DCuNMFpxpmgD3FjGfsFEXZSiOrCWzYWmUi6rQCB32xuDtEZ2LXn57nToj9MTKX92aoCzQw2EqlTqnVyoOBTx1ID4bVF3pgmjBnA7tKiLL%2FtBlxKmvYPxmwe7tjMMbJ2b0GOqUB00HQhgoLqJOQokan1bFM5qH5yPfaW0aCDTM63UY85LKtEpkb16PvIhoVqALw4AIBcMJ9e1US1nPu1yfkp%2BYIF4MlifpHFW1IQytN2m23z7ipWPI6FU1v8Y1XJtFJyP6qCfDs%2B%2B01MFOp02cXg9TP%2BtJRXECIoCGMY2y6tUuz6fiw1yyC4cR5Q%2FM8K6j4duQU6DDLeEFLCs3oyv%2BFU%2F0FWvegQnvR&X-Amz-Signature=5b9724a9602b3731bb28e9a5f26e066fb484ee3dd61f3b977d59e40892d671db&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QHHCUPK3%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T232231Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIEwbwdG1xmoFKKnMBBHc5GJ3HhXTXmp6fRnpbc78bXIoAiEA7peHFS91iu1zDbSe5uL65FmySPaQYc1osonry6dJc7IqiAQIsP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKdd7ijU1pt%2BNp40ECrcA1ntOsD46hcnV5Ki%2F20FEfDbICR2G%2FIuzaJqJ5T63lOYScmHdMJytsOcu1fnzGNODlidCqyXVIqk5QQKiK8z7hj1H08rKhN%2B%2F5WBgkGD4Hm7U4%2BPnojaMdchMndNlDiTx2Lhwcdk3XxvGiCHJ%2F62wJuCc0%2F88Iz%2BcBz5Nuh42SS52MBBq1NRXzoiq2pfAy7L3P5PV8YsVELGybEeLFgXK8sZTY9%2Fg9gSALyK241BUIsLjQFHHhIohyL23rRPW2OQB1lAKzQ8sCfcZBDWkUXvyAJGXG0b%2Fl72JN7dSAyTfm3swzZIJlA%2Bl%2BNCVhwfctNW7FTKDHBLI64keLdHcWAmNeZcaHjhCBT4No2iqKnEiZec%2BE%2BMsaCICoEnwFK5UCkvFqj1ZCPArS50coc5KOY%2FkSeuZhBhGdWQoIosnmuFH2ScTygJAeJeIhlunz0pxg5ygj1DTHOMf5NrKFOEOxTK6PwwhHxd6DZtsavtkzrMUsSs7GB1uDHUdOGmAJ7PES5yL3VzNzv8Y%2Fyh4UGNnmwmAbgMturRgYm64%2BSB%2B6YO%2BgkGluGsZLpPZaUfjMSWB4iKEyu16kggB6cAWfh8w%2FkP7zdt8XtDoMGhR7uu8WjkTeMoRA2pJRd9Apfx7U6%2FMN%2FJ2b0GOqUBRJCzhqS2%2BP4zfNKcd6gtyuu0cOWYrdllZqAksGCYXrk7ZSEN5rhUmy0XZ6iPFwoetMMpV70hGwxuKAtk%2F6gn9BbopBK1T3%2Foss2j0m9vt1iMXY3O1Pg%2Fs1SP4PWiTnJjAo%2BnSnBlPVhYTSYDOgCpSzFSo4htMRGQvY%2Fr9e6JDkaoOAPPsisS0hcUS2no25NUrSJjjp290Jx5x1TJRcZXEjkZzS%2BK&X-Amz-Signature=bbe8ff1bfbcef64ef506fa97b065151f0dfc6081ff9848f3335e81eaa7a8a727&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RFNFZ3N2%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T232229Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAEEKHO%2FbkcnWTiIiws3egpYlscES2ykBcINzdGHPcxdAiAYkaYykmBx8dK03nl9TmohxyMJNwnIvDNeISCczW%2FFdiqIBAiw%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMqYeNvP0B%2BYoL5CUfKtwDr%2FGRcJN6iuMD8aSmcmUBW38sEQqXTO2KNheB%2B7tDstoq2buVnPWQXGO1jh8XkTRGulqF8MwqZKRXTnt%2FVliFS5ekqHSsiubyOEGduG3kZrbU3n2lc9MHt9XM%2FhvAdykhRkfCyb0lAWCYV2Jkls7%2FhtVuZPo2kx5LzkN%2Fnd3NYKwBP3MNLCLos10PS7%2FnjHzxC3aZWql9wa2SWVKNzBGdYf1Q8HvohN9RBBf1DgsrEv1sVUvJkb2v6wZeha%2FzPDPGV7VBu%2B2uFkzE3%2FbXIGZM3PnCYHlp4EjVftP68MtwI9aIT24EvvBhgS1pnz9H%2BeEV0N7zKX0lCjgwatA6qPjXihAl1%2B864ggS2v3luV%2BUXZv10nytfNi8LoSK5GBYUPZUD7ZFrd8gcLAa%2BHsVOzAIwtfpNBVDJPiCpcmL394OVGzeNsRuCnYYumBjTcZL3Agora%2FUSOCP5zJ5A833XJtnf17QDLIyWofhO78Vj39t0KW9JkCYuP%2Bikfobsq9meOP2X3EhUfIs5orrweirx4ih%2FWM58O%2FMd%2B4vZUsiRQjdnb1dP6YbxSE0sJqj7UjBlCtWEVwjBuKYoKe%2ByEgLW2PNDO%2BtCrYWWc9ZaBWEnLxUHMctM6ix%2FHdtFpoaQT0wosnZvQY6pgF6Rh%2FRQKdsYb%2F%2F56YSVUVZ1f9nPk4uCgC%2Fv49xC%2FNn6sJ95LRkprvQvrlFiQIGLgKG3tJw%2FKANOy70EAqtjNuJCs%2BlTdwQvbKB9I0wwgHCjsC0g6ahcUEo1efRSqL31WP57EpcGbCEYtQzQ7YUFstBKoSftDsWaH%2BqOrZqW5F2%2B%2FcVJdWoaJP7g3uyEJrkcUTvTNAaJfVnyAuIDZUXklnAJu%2Fbir7T&X-Amz-Signature=4be8b7fe8ed528c08271fa0ae6c6de08ecba9338b2808802b481e1ae7de00aed&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RFNFZ3N2%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T232229Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAEEKHO%2FbkcnWTiIiws3egpYlscES2ykBcINzdGHPcxdAiAYkaYykmBx8dK03nl9TmohxyMJNwnIvDNeISCczW%2FFdiqIBAiw%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMqYeNvP0B%2BYoL5CUfKtwDr%2FGRcJN6iuMD8aSmcmUBW38sEQqXTO2KNheB%2B7tDstoq2buVnPWQXGO1jh8XkTRGulqF8MwqZKRXTnt%2FVliFS5ekqHSsiubyOEGduG3kZrbU3n2lc9MHt9XM%2FhvAdykhRkfCyb0lAWCYV2Jkls7%2FhtVuZPo2kx5LzkN%2Fnd3NYKwBP3MNLCLos10PS7%2FnjHzxC3aZWql9wa2SWVKNzBGdYf1Q8HvohN9RBBf1DgsrEv1sVUvJkb2v6wZeha%2FzPDPGV7VBu%2B2uFkzE3%2FbXIGZM3PnCYHlp4EjVftP68MtwI9aIT24EvvBhgS1pnz9H%2BeEV0N7zKX0lCjgwatA6qPjXihAl1%2B864ggS2v3luV%2BUXZv10nytfNi8LoSK5GBYUPZUD7ZFrd8gcLAa%2BHsVOzAIwtfpNBVDJPiCpcmL394OVGzeNsRuCnYYumBjTcZL3Agora%2FUSOCP5zJ5A833XJtnf17QDLIyWofhO78Vj39t0KW9JkCYuP%2Bikfobsq9meOP2X3EhUfIs5orrweirx4ih%2FWM58O%2FMd%2B4vZUsiRQjdnb1dP6YbxSE0sJqj7UjBlCtWEVwjBuKYoKe%2ByEgLW2PNDO%2BtCrYWWc9ZaBWEnLxUHMctM6ix%2FHdtFpoaQT0wosnZvQY6pgF6Rh%2FRQKdsYb%2F%2F56YSVUVZ1f9nPk4uCgC%2Fv49xC%2FNn6sJ95LRkprvQvrlFiQIGLgKG3tJw%2FKANOy70EAqtjNuJCs%2BlTdwQvbKB9I0wwgHCjsC0g6ahcUEo1efRSqL31WP57EpcGbCEYtQzQ7YUFstBKoSftDsWaH%2BqOrZqW5F2%2B%2FcVJdWoaJP7g3uyEJrkcUTvTNAaJfVnyAuIDZUXklnAJu%2Fbir7T&X-Amz-Signature=a43a7e1e19791028d937e9ef27beb4ce8bc4e70367d2da71fac154ad35b723b6&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RFNFZ3N2%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T232229Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAEEKHO%2FbkcnWTiIiws3egpYlscES2ykBcINzdGHPcxdAiAYkaYykmBx8dK03nl9TmohxyMJNwnIvDNeISCczW%2FFdiqIBAiw%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMqYeNvP0B%2BYoL5CUfKtwDr%2FGRcJN6iuMD8aSmcmUBW38sEQqXTO2KNheB%2B7tDstoq2buVnPWQXGO1jh8XkTRGulqF8MwqZKRXTnt%2FVliFS5ekqHSsiubyOEGduG3kZrbU3n2lc9MHt9XM%2FhvAdykhRkfCyb0lAWCYV2Jkls7%2FhtVuZPo2kx5LzkN%2Fnd3NYKwBP3MNLCLos10PS7%2FnjHzxC3aZWql9wa2SWVKNzBGdYf1Q8HvohN9RBBf1DgsrEv1sVUvJkb2v6wZeha%2FzPDPGV7VBu%2B2uFkzE3%2FbXIGZM3PnCYHlp4EjVftP68MtwI9aIT24EvvBhgS1pnz9H%2BeEV0N7zKX0lCjgwatA6qPjXihAl1%2B864ggS2v3luV%2BUXZv10nytfNi8LoSK5GBYUPZUD7ZFrd8gcLAa%2BHsVOzAIwtfpNBVDJPiCpcmL394OVGzeNsRuCnYYumBjTcZL3Agora%2FUSOCP5zJ5A833XJtnf17QDLIyWofhO78Vj39t0KW9JkCYuP%2Bikfobsq9meOP2X3EhUfIs5orrweirx4ih%2FWM58O%2FMd%2B4vZUsiRQjdnb1dP6YbxSE0sJqj7UjBlCtWEVwjBuKYoKe%2ByEgLW2PNDO%2BtCrYWWc9ZaBWEnLxUHMctM6ix%2FHdtFpoaQT0wosnZvQY6pgF6Rh%2FRQKdsYb%2F%2F56YSVUVZ1f9nPk4uCgC%2Fv49xC%2FNn6sJ95LRkprvQvrlFiQIGLgKG3tJw%2FKANOy70EAqtjNuJCs%2BlTdwQvbKB9I0wwgHCjsC0g6ahcUEo1efRSqL31WP57EpcGbCEYtQzQ7YUFstBKoSftDsWaH%2BqOrZqW5F2%2B%2FcVJdWoaJP7g3uyEJrkcUTvTNAaJfVnyAuIDZUXklnAJu%2Fbir7T&X-Amz-Signature=8c2f4da2dd8cf4a17a44f53f5686cfdca1593d2832719390992f5ab0a10a980c&X-Amz-SignedHeaders=host&x-id=GetObject)


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

