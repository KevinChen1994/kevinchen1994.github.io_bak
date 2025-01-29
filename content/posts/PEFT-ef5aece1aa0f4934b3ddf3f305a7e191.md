---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4663GPFB7UC%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250129T172041Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDNiyMEOmoDMc7rdsf\
  Ydz6TOwAHtVp1QCRanGIr6JvjDwIhALsQtQsHeeUxmjBwFg6n%2B8E%2FlvKNkpKaNKk8HtGxHruJ\
  KogECJL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igxyy%2B27ll%2Fbg\
  YcIs7gq3AMsgBwy8hukItrGbfaiqI7cP3rZOO0XJMAcnyEuozTcLktG%2Fn9S1jrCfmHFWT%2BeIK\
  Cnye2CONxtNjqoW4HeytPYTt5yRLJ4TsiMrOc4t49bY2AUkn5xFK4Etpv4pbgSzLKXSFdtCrEDPlu\
  6VV8124HDsrvM9cQfwde7HBxECLQaZSqCSRNEdOJA9FkNBojR4051zqEFH24Y37IAE1PI31Aw%2FG\
  q69vUfYr1cOBDZeO6o97bJV1jDy0HGtPJlbaoYWye2nBvo8sHG0NKuwVliRXM%2B4wrDq%2FdHwj9\
  fjg0hg2NiM5sppZZZoyhvJkOvqt8he8xICiomndtwkbUiDAldfybMhnEphhViP0%2FGNHJPHSe%2F\
  KVc3f3S8LR2%2FovtqcUe%2FD4e2lY04t%2FLehFUKPwrT7o6irZXlp6x0zDPExEftQhCtZQ5klap\
  ykVgS1uXA%2BpOsfbl%2BDFDia%2B0ft%2FAgZXRCVhUF4VbDGfFUllwDk%2FJqhjZ7zVfcE0K4AI\
  tCJsMXlju7MTt2eGGzeRB6n7C6iiM1qX5lwUBTCeOndJraF1iJEcciw4L4ZAa9O0LAMjoqee5GOUv\
  hGpx%2FBKE5iib17CDWPpgSlewHMyIUgSxQm7Pozuwu%2BvGGMgsTsbGVeXqaWzD8vem8BjqkAWqh\
  x2xhzsp6ff9NLXtBNQhwC2kPaYUzYXM%2FP0sG3j3TQHwE9dFfcCPX%2FHhv%2BlOv1vH6Y%2B3iW\
  %2F%2BY49faynIZgSikpk5GepX0WCYZCjwXxUNc%2BfTUZpJihZeI93WUTNnRbqW37yBucRGUDQNC\
  VU7m4985%2Fz4pKuUfPqb4wXtb5nut69bNh%2FXBbFF64VZpHMp56Aan8cS877z%2FI9n4HKRmUGS\
  cRyJo&X-Amz-Signature=0a7bece4eb7c444e65f89a3486033b83c97f3129d687f2df27b7ff9\
  9cd5212e1&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466VPXRBNSO%2F20250129%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250129T171941Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIC4aR%2FcJjc%2B27%2BgcgCnqok4Ccu8YU3GEe%2FwVjDQfVlghAiEAqMv%2B9PA4mUah\
        Vh7W8JdABRVyhjpWbT7lY8tiHThuMAYqiAQIkv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARA\
        AGgw2Mzc0MjMxODM4MDUiDN33B2mWQmBkyVeayCrcAy7kTrqHt%2BazIcLxlRCiw21Oz4Xk\
        9i1GJgutBcwgUE6Kc%2B4gPic69ZsREpLyRWT3rhUDgQ93jYecowr8YD2EOIacWXS6AlkIm\
        Hed%2BznUWR%2Fj0gtMLNLTeeTBXweZcHvXbXaalXvR6n5A2ocawPI6dPVYDBdtIIVRtcAX\
        IsoG43FCqBi7oGCuKUK%2FDZoFkDlbiOE8so%2BHF%2FrO2Hcrj%2BvEm9aOAVrfRRpHYh4\
        1Le%2B5upzDLqM%2BxnuB8oJOSyph2lHGX1%2Bi2Ku7UgF9iniPu3FcT%2FiNkWLAWe8ln6\
        I%2BMGZBmQwbKWmfr%2F3brDKvVCqnCl1mTpwLvu7zaiNAfBWEQG9jjT7wlg6%2B83a%2Bn\
        bb0C2qWkqGQwhRdJkJnYluMtTFQUDVoQ6df8xlTZUwsgwRhsI54bLFmC8V1xFGYFM%2Ff8X\
        K%2BM0KY0dN7PPTrrM52xY71PANusYEXlDw8SOoRROb5H%2BFW3LkOYQsrChFpBDse2m88r\
        x9pXy3Q6IQtpdLFFFBHm0VoLe1c8pu3q1nd9rv8q57N3P4qo4XkDEUi7%2FkzrsKr1J0oom\
        glA6VE%2BEZaBRyTr3tkcAja06nCuvN%2BQoqZXRBU3dCSDgetboLTqcY%2F6levasJ6b3M\
        XDDelRjS6fVk0MNu96bwGOqUBgxVpAS26GITFBOB4c6LhjXcbZkdDsX0%2BLHzgBS4bDjzx\
        3zEpt7EpXzT2GV48r1i62OKElGhkaNFhI1iWGOMrsCJPgwknqyIPhV0zEGHYVmRBMIGQj4y\
        X3JVbmLxeZuGVOD3rkDUCOwiC9%2BDLbaYoClbrK%2BWN30c5Nf9sxMSnrHsy4iemjAPJdB\
        KDqpL7LUvW989LB7WgZOtVBP3EZ8mMSbHHNyo1&X-Amz-Signature=0c58f87194f8c4c6\
        f42d7b8d2136916e590331a0d9ff251cc83f5de15beb177b&X-Amz-SignedHeaders=ho\
        st&x-id=GetObject"
      expiry_time: "2025-01-29T18:19:41.350Z"
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
UPDATE_TIME: "2025-01-29T17:20:47.711Z"
EXPIRY_TIME: "2025-01-29T18:20:40.223Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665RWDWZ23%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T172040Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDn9oA9q%2Bq1EuhsF%2FlZdBOYtwFwvCJAEk11qq2QREsJOwIgNYRGakZlzbSC1KJd%2Fdcdh3p394yQYjLUzup2dCJw3vIqiAQIkv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDF7RtT%2FOdPJlC%2FGfJSrcA2pUwHngUP7te1C78Y1T97wPK%2F0MIKYXZD1DWji4Qo79aZECae5Xhxw9g7phTEu4%2FpdhM7gRfIP6%2Bo%2BgqdSfCfUoV8oBDXwkVuseJw4U%2BtTc5dfufM7U9KpIIFUiqqFbxm%2F0fpGrKLhdz0vcXDHhnZIM%2BDxVNvn4KUWh4zlUzkDMsn%2B7A9DNXNsAAcaIOYRUh6n63uUB6CyxQDQq88Ox5g3lRoYg9m2BVpUIR2YEJbM0SbE%2Fj1%2BhCgCZXA05Qil2Ed4GGb5rB2TGB6lfXDhPHcgS1iNNYg%2B9uTQ7NDxqS37OTGhzfxa8oNZa4N5ivEEk%2BjtVRPKZslK8FzJuZF8P64WEVamLP0EiHMA1wQw0nQdCN7ZLJijSqxV93yKnNA3mOFGO0Cr9hEW2TA5bwR4rZWMmlvPTeZPOwvPrAehmnd6jA6zHxI04j%2FKGruh1pkfIw%2FwDLVOCDV1UKtJ1cDqIBxm2y3ZotA26hefjAcBOeFcrVe6GziZgd9EITZM0QV2c2p%2BqpX%2ByJmCsPz%2FE4c1q%2BqL19wG2yI6MF6EmXn3vi3WUTEZjZ4drYClUgw%2FR5%2Bx%2F3%2Bc3Ldbzrh9Ze0jfCkvYyQxAaHe4HgARisjWCdcfULZKHNZksbmelA0liRz2MP696bwGOqUBLwylClB5Koqg6LlM6FJvAwjOtQQ5ZjuFKJMfHAvLRQiDNXg4BqnskTXE4znkTFJ3THOl4ubJDGauUwR33Z%2F18Yiawj6nED%2FtMcSi%2FpacS3302E6YdbhctXIkVnVY171Vkb7xMqImyzBtwRNAYT6mVRFhWA%2FMuCe3HK3wvX4kBOjGKe7k0rKc9AMu3eI%2BMmSL9ES8b1yAlr%2Fted7sisV0xK3i0WfT&X-Amz-Signature=32e3057a99a758d8317480149f4665fdea53754f63e5a43886f12c2a5e775508&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665RWDWZ23%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T172040Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDn9oA9q%2Bq1EuhsF%2FlZdBOYtwFwvCJAEk11qq2QREsJOwIgNYRGakZlzbSC1KJd%2Fdcdh3p394yQYjLUzup2dCJw3vIqiAQIkv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDF7RtT%2FOdPJlC%2FGfJSrcA2pUwHngUP7te1C78Y1T97wPK%2F0MIKYXZD1DWji4Qo79aZECae5Xhxw9g7phTEu4%2FpdhM7gRfIP6%2Bo%2BgqdSfCfUoV8oBDXwkVuseJw4U%2BtTc5dfufM7U9KpIIFUiqqFbxm%2F0fpGrKLhdz0vcXDHhnZIM%2BDxVNvn4KUWh4zlUzkDMsn%2B7A9DNXNsAAcaIOYRUh6n63uUB6CyxQDQq88Ox5g3lRoYg9m2BVpUIR2YEJbM0SbE%2Fj1%2BhCgCZXA05Qil2Ed4GGb5rB2TGB6lfXDhPHcgS1iNNYg%2B9uTQ7NDxqS37OTGhzfxa8oNZa4N5ivEEk%2BjtVRPKZslK8FzJuZF8P64WEVamLP0EiHMA1wQw0nQdCN7ZLJijSqxV93yKnNA3mOFGO0Cr9hEW2TA5bwR4rZWMmlvPTeZPOwvPrAehmnd6jA6zHxI04j%2FKGruh1pkfIw%2FwDLVOCDV1UKtJ1cDqIBxm2y3ZotA26hefjAcBOeFcrVe6GziZgd9EITZM0QV2c2p%2BqpX%2ByJmCsPz%2FE4c1q%2BqL19wG2yI6MF6EmXn3vi3WUTEZjZ4drYClUgw%2FR5%2Bx%2F3%2Bc3Ldbzrh9Ze0jfCkvYyQxAaHe4HgARisjWCdcfULZKHNZksbmelA0liRz2MP696bwGOqUBLwylClB5Koqg6LlM6FJvAwjOtQQ5ZjuFKJMfHAvLRQiDNXg4BqnskTXE4znkTFJ3THOl4ubJDGauUwR33Z%2F18Yiawj6nED%2FtMcSi%2FpacS3302E6YdbhctXIkVnVY171Vkb7xMqImyzBtwRNAYT6mVRFhWA%2FMuCe3HK3wvX4kBOjGKe7k0rKc9AMu3eI%2BMmSL9ES8b1yAlr%2Fted7sisV0xK3i0WfT&X-Amz-Signature=e35f5177096799ab566f7134baed60a409ee40dee6b3d1c5b6804b2fc903832a&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665RWDWZ23%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T172040Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDn9oA9q%2Bq1EuhsF%2FlZdBOYtwFwvCJAEk11qq2QREsJOwIgNYRGakZlzbSC1KJd%2Fdcdh3p394yQYjLUzup2dCJw3vIqiAQIkv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDF7RtT%2FOdPJlC%2FGfJSrcA2pUwHngUP7te1C78Y1T97wPK%2F0MIKYXZD1DWji4Qo79aZECae5Xhxw9g7phTEu4%2FpdhM7gRfIP6%2Bo%2BgqdSfCfUoV8oBDXwkVuseJw4U%2BtTc5dfufM7U9KpIIFUiqqFbxm%2F0fpGrKLhdz0vcXDHhnZIM%2BDxVNvn4KUWh4zlUzkDMsn%2B7A9DNXNsAAcaIOYRUh6n63uUB6CyxQDQq88Ox5g3lRoYg9m2BVpUIR2YEJbM0SbE%2Fj1%2BhCgCZXA05Qil2Ed4GGb5rB2TGB6lfXDhPHcgS1iNNYg%2B9uTQ7NDxqS37OTGhzfxa8oNZa4N5ivEEk%2BjtVRPKZslK8FzJuZF8P64WEVamLP0EiHMA1wQw0nQdCN7ZLJijSqxV93yKnNA3mOFGO0Cr9hEW2TA5bwR4rZWMmlvPTeZPOwvPrAehmnd6jA6zHxI04j%2FKGruh1pkfIw%2FwDLVOCDV1UKtJ1cDqIBxm2y3ZotA26hefjAcBOeFcrVe6GziZgd9EITZM0QV2c2p%2BqpX%2ByJmCsPz%2FE4c1q%2BqL19wG2yI6MF6EmXn3vi3WUTEZjZ4drYClUgw%2FR5%2Bx%2F3%2Bc3Ldbzrh9Ze0jfCkvYyQxAaHe4HgARisjWCdcfULZKHNZksbmelA0liRz2MP696bwGOqUBLwylClB5Koqg6LlM6FJvAwjOtQQ5ZjuFKJMfHAvLRQiDNXg4BqnskTXE4znkTFJ3THOl4ubJDGauUwR33Z%2F18Yiawj6nED%2FtMcSi%2FpacS3302E6YdbhctXIkVnVY171Vkb7xMqImyzBtwRNAYT6mVRFhWA%2FMuCe3HK3wvX4kBOjGKe7k0rKc9AMu3eI%2BMmSL9ES8b1yAlr%2Fted7sisV0xK3i0WfT&X-Amz-Signature=957d4204b9c40a5506eeac834bd658ec7366dba255f7b59bf50ced0d476bb417&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665RWDWZ23%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T172040Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDn9oA9q%2Bq1EuhsF%2FlZdBOYtwFwvCJAEk11qq2QREsJOwIgNYRGakZlzbSC1KJd%2Fdcdh3p394yQYjLUzup2dCJw3vIqiAQIkv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDF7RtT%2FOdPJlC%2FGfJSrcA2pUwHngUP7te1C78Y1T97wPK%2F0MIKYXZD1DWji4Qo79aZECae5Xhxw9g7phTEu4%2FpdhM7gRfIP6%2Bo%2BgqdSfCfUoV8oBDXwkVuseJw4U%2BtTc5dfufM7U9KpIIFUiqqFbxm%2F0fpGrKLhdz0vcXDHhnZIM%2BDxVNvn4KUWh4zlUzkDMsn%2B7A9DNXNsAAcaIOYRUh6n63uUB6CyxQDQq88Ox5g3lRoYg9m2BVpUIR2YEJbM0SbE%2Fj1%2BhCgCZXA05Qil2Ed4GGb5rB2TGB6lfXDhPHcgS1iNNYg%2B9uTQ7NDxqS37OTGhzfxa8oNZa4N5ivEEk%2BjtVRPKZslK8FzJuZF8P64WEVamLP0EiHMA1wQw0nQdCN7ZLJijSqxV93yKnNA3mOFGO0Cr9hEW2TA5bwR4rZWMmlvPTeZPOwvPrAehmnd6jA6zHxI04j%2FKGruh1pkfIw%2FwDLVOCDV1UKtJ1cDqIBxm2y3ZotA26hefjAcBOeFcrVe6GziZgd9EITZM0QV2c2p%2BqpX%2ByJmCsPz%2FE4c1q%2BqL19wG2yI6MF6EmXn3vi3WUTEZjZ4drYClUgw%2FR5%2Bx%2F3%2Bc3Ldbzrh9Ze0jfCkvYyQxAaHe4HgARisjWCdcfULZKHNZksbmelA0liRz2MP696bwGOqUBLwylClB5Koqg6LlM6FJvAwjOtQQ5ZjuFKJMfHAvLRQiDNXg4BqnskTXE4znkTFJ3THOl4ubJDGauUwR33Z%2F18Yiawj6nED%2FtMcSi%2FpacS3302E6YdbhctXIkVnVY171Vkb7xMqImyzBtwRNAYT6mVRFhWA%2FMuCe3HK3wvX4kBOjGKe7k0rKc9AMu3eI%2BMmSL9ES8b1yAlr%2Fted7sisV0xK3i0WfT&X-Amz-Signature=98ed0841847c33fa5c4ddc4a1db62e46a9ef636bc7263c65d56e7e4be1feae48&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665RWDWZ23%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T172040Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDn9oA9q%2Bq1EuhsF%2FlZdBOYtwFwvCJAEk11qq2QREsJOwIgNYRGakZlzbSC1KJd%2Fdcdh3p394yQYjLUzup2dCJw3vIqiAQIkv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDF7RtT%2FOdPJlC%2FGfJSrcA2pUwHngUP7te1C78Y1T97wPK%2F0MIKYXZD1DWji4Qo79aZECae5Xhxw9g7phTEu4%2FpdhM7gRfIP6%2Bo%2BgqdSfCfUoV8oBDXwkVuseJw4U%2BtTc5dfufM7U9KpIIFUiqqFbxm%2F0fpGrKLhdz0vcXDHhnZIM%2BDxVNvn4KUWh4zlUzkDMsn%2B7A9DNXNsAAcaIOYRUh6n63uUB6CyxQDQq88Ox5g3lRoYg9m2BVpUIR2YEJbM0SbE%2Fj1%2BhCgCZXA05Qil2Ed4GGb5rB2TGB6lfXDhPHcgS1iNNYg%2B9uTQ7NDxqS37OTGhzfxa8oNZa4N5ivEEk%2BjtVRPKZslK8FzJuZF8P64WEVamLP0EiHMA1wQw0nQdCN7ZLJijSqxV93yKnNA3mOFGO0Cr9hEW2TA5bwR4rZWMmlvPTeZPOwvPrAehmnd6jA6zHxI04j%2FKGruh1pkfIw%2FwDLVOCDV1UKtJ1cDqIBxm2y3ZotA26hefjAcBOeFcrVe6GziZgd9EITZM0QV2c2p%2BqpX%2ByJmCsPz%2FE4c1q%2BqL19wG2yI6MF6EmXn3vi3WUTEZjZ4drYClUgw%2FR5%2Bx%2F3%2Bc3Ldbzrh9Ze0jfCkvYyQxAaHe4HgARisjWCdcfULZKHNZksbmelA0liRz2MP696bwGOqUBLwylClB5Koqg6LlM6FJvAwjOtQQ5ZjuFKJMfHAvLRQiDNXg4BqnskTXE4znkTFJ3THOl4ubJDGauUwR33Z%2F18Yiawj6nED%2FtMcSi%2FpacS3302E6YdbhctXIkVnVY171Vkb7xMqImyzBtwRNAYT6mVRFhWA%2FMuCe3HK3wvX4kBOjGKe7k0rKc9AMu3eI%2BMmSL9ES8b1yAlr%2Fted7sisV0xK3i0WfT&X-Amz-Signature=6f1aba02f62ee48328d4555ee41ece2dfb68a273ad5fc9161c5b2ba0527972cc&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YOQOABMV%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T172041Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD%2BsEP7cR8Y6IxtBbZITmtiXDrQH970GcSf60O%2Bf%2B5XywIhAN9kKBeaIBEArlmZjrkYN390gRiQYBFWSzQOJTv6jz7mKogECJL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igx7h9QTDWd%2BU0YgauQq3ANlbcRNbslzSoBf4v%2FtHMhMxfd%2FKtV7pJr9Y14QTkL9atNqryolUyNpWo562P1m9v%2B9HzAnN79c5vA%2BKOJHFbqg6AukqqDG3RTCI7ciL6mwmTPEKr3iIUlokrZ%2FBCBX5XQ22ziIdOg2gsYaUPehhELHg4lTE1PjLZNFcG4ANX0rzGb3QTiDnw9CVUyV4ogcQ25hz0kmjeFUY%2BtF0E4CB%2FPG5bC65OmtZGeWp9HthIFWdm%2FWgcv3YUtfFF3rHD5R0JrbasWWdYW2MPvdO3KkiOr8hcglzAO1uKQDhgD9zbmgm0c%2FWcZZITxHP5dmfkv9a299QXHpxVzfGCQ5DG3%2FIvjeQTC0hXgq5WmaOJ90r5x7NaNbbMGgIM9BQJthVI%2BjFMYZe1SGPwHxUK%2Fb4y46JAiG13g9CUFAz8gD8d0b%2FBCECLN9UODzv3j5zeF02TvopATiSOL%2BNbN2jVlL%2F54wqbvWRat%2BxBWxS5Mj9jDOXXvcrVVUJnHcS4ZdeHrdC%2FW34xmczlveWA39B%2FivvnvlbPbvhtCUQnCxmbyyEJiBFUgKnxQ3%2FznR%2BGyPGyR6KuHuLluDzFA%2Fz3IgE0g4jLEJSGXcwN2GD61bE7VXLm2px4tDst2%2Fy0vLd0%2FwhJkWuTCdwem8BjqkAbWVibo9VsHb7dT5VSDGCdZGTsK7ZAmLzPzPEziuvRkV7L%2F8LFBcos6J%2Fur0LPX6wxVMnscQfGuEuI16kIILM2nz3mOFs1mpqwpkNqhKau5OfpbcqLYAQSP8aYecIiHOnM7%2FrrMu3jgCm8ys5uGcAZ65hTwq3aPri2ZnLhjbO2fgHgshKHu7r6hEhRzaxv9iHibkpdtUl2Dv4TMriM9h0gh1xsA3&X-Amz-Signature=9b06364165486ab0a9b216b943ba7afba258b78c3121462fcb917a3bc66dfc04&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XCJZJVQ4%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T172041Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIEEvsqj2ThgKI6gXj6sTRwZJ4sIC%2FxCctaW5z2yaB1tYAiEApMnQXT1vS2OXF5bZTX8dzxYKKaAY2PIarg85lTRjflkqiAQIkv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMOJhyzBY%2FWPEFln6yrcAxI6h3p5F3tMFfCndt9r32S9R6OSWwWnchNCcD70t%2FDnqWonKOvrX4UViUKI%2FnO0MgTM5LyboE8G1ZviVhqOlrUpH1kOQNUEqd%2BOmp6ySpY5Ryio%2BjfZ6EaokN3TY4%2FVZnLyLBGqoiZWvZQf39Vvfap8RDnx0v3EkcUFHmseDEHbXdEmMT3tmQnzNJb7z9xBYt4rV4E5VOGDpokpVq2AMUxLdu3nrkihtjRfNfkaz3%2FURZExgm7fTnB5JDkUZsRURZLhuPjdIynhaEZ2TdUTixf2dJQBUghR50BUYmbe6GDzsTRP1t0REVcbdP2G909UV7JOg2MXnef7GG2GrbViu6iR4piT9%2BPbM52O7WF3JaZfLpK9OqUtCIBlrp7EMXAVVzMVYCNj8awKQ222fgDCbm5euiOFevudLGQ0HnOG%2F7wIu6m7NymQ5TiOp2sliesN77GSe0HQDJX%2FenAyuDovNotj0fDfV%2Fm77gS4WiSp9%2FDaAm995T58zVwWRw6GCjOOf%2BwK9lb66IDARNXAm1rXEN1E3MmC%2BhRxzzVFRsFWBGRxc1dd78nSIFs5mg6XP9%2FHgTa8pT2PAAokUl1mRo0E%2Bz3neOBDh8JaMZmpVpKq3jT3HOr3qRYOTbbGemDDMO%2B96bwGOqUBB0v1ENo75kcmi10pMLLZT%2FPnsLSbkROQXFfm%2BJaQ21ZdhmhsAYBruqM51GgckK4KDC0oo%2BN5QR7YRihbfJ4NpQVaQDOz1NjkAll4YncYZWwBfLLEISkiGv3%2FS%2BKuav73EOzPjYn49lY0qwXbABZZ3XvjGCXoXHRUFX0V3w918ExAKycOhlWKjQsS1%2BvvA%2BnPlt%2FXR6wIDLNmE3iUBlWTedZ7XqAv&X-Amz-Signature=c2c79cb235378cae0be44688a519ef8745efe71f58c403147b48b91ac47f4ec9&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665RWDWZ23%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T172040Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDn9oA9q%2Bq1EuhsF%2FlZdBOYtwFwvCJAEk11qq2QREsJOwIgNYRGakZlzbSC1KJd%2Fdcdh3p394yQYjLUzup2dCJw3vIqiAQIkv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDF7RtT%2FOdPJlC%2FGfJSrcA2pUwHngUP7te1C78Y1T97wPK%2F0MIKYXZD1DWji4Qo79aZECae5Xhxw9g7phTEu4%2FpdhM7gRfIP6%2Bo%2BgqdSfCfUoV8oBDXwkVuseJw4U%2BtTc5dfufM7U9KpIIFUiqqFbxm%2F0fpGrKLhdz0vcXDHhnZIM%2BDxVNvn4KUWh4zlUzkDMsn%2B7A9DNXNsAAcaIOYRUh6n63uUB6CyxQDQq88Ox5g3lRoYg9m2BVpUIR2YEJbM0SbE%2Fj1%2BhCgCZXA05Qil2Ed4GGb5rB2TGB6lfXDhPHcgS1iNNYg%2B9uTQ7NDxqS37OTGhzfxa8oNZa4N5ivEEk%2BjtVRPKZslK8FzJuZF8P64WEVamLP0EiHMA1wQw0nQdCN7ZLJijSqxV93yKnNA3mOFGO0Cr9hEW2TA5bwR4rZWMmlvPTeZPOwvPrAehmnd6jA6zHxI04j%2FKGruh1pkfIw%2FwDLVOCDV1UKtJ1cDqIBxm2y3ZotA26hefjAcBOeFcrVe6GziZgd9EITZM0QV2c2p%2BqpX%2ByJmCsPz%2FE4c1q%2BqL19wG2yI6MF6EmXn3vi3WUTEZjZ4drYClUgw%2FR5%2Bx%2F3%2Bc3Ldbzrh9Ze0jfCkvYyQxAaHe4HgARisjWCdcfULZKHNZksbmelA0liRz2MP696bwGOqUBLwylClB5Koqg6LlM6FJvAwjOtQQ5ZjuFKJMfHAvLRQiDNXg4BqnskTXE4znkTFJ3THOl4ubJDGauUwR33Z%2F18Yiawj6nED%2FtMcSi%2FpacS3302E6YdbhctXIkVnVY171Vkb7xMqImyzBtwRNAYT6mVRFhWA%2FMuCe3HK3wvX4kBOjGKe7k0rKc9AMu3eI%2BMmSL9ES8b1yAlr%2Fted7sisV0xK3i0WfT&X-Amz-Signature=f511f61a89d62f69fe7e9fd1894d66c2e9f460b0344216d624085208add47b1e&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665RWDWZ23%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T172040Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDn9oA9q%2Bq1EuhsF%2FlZdBOYtwFwvCJAEk11qq2QREsJOwIgNYRGakZlzbSC1KJd%2Fdcdh3p394yQYjLUzup2dCJw3vIqiAQIkv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDF7RtT%2FOdPJlC%2FGfJSrcA2pUwHngUP7te1C78Y1T97wPK%2F0MIKYXZD1DWji4Qo79aZECae5Xhxw9g7phTEu4%2FpdhM7gRfIP6%2Bo%2BgqdSfCfUoV8oBDXwkVuseJw4U%2BtTc5dfufM7U9KpIIFUiqqFbxm%2F0fpGrKLhdz0vcXDHhnZIM%2BDxVNvn4KUWh4zlUzkDMsn%2B7A9DNXNsAAcaIOYRUh6n63uUB6CyxQDQq88Ox5g3lRoYg9m2BVpUIR2YEJbM0SbE%2Fj1%2BhCgCZXA05Qil2Ed4GGb5rB2TGB6lfXDhPHcgS1iNNYg%2B9uTQ7NDxqS37OTGhzfxa8oNZa4N5ivEEk%2BjtVRPKZslK8FzJuZF8P64WEVamLP0EiHMA1wQw0nQdCN7ZLJijSqxV93yKnNA3mOFGO0Cr9hEW2TA5bwR4rZWMmlvPTeZPOwvPrAehmnd6jA6zHxI04j%2FKGruh1pkfIw%2FwDLVOCDV1UKtJ1cDqIBxm2y3ZotA26hefjAcBOeFcrVe6GziZgd9EITZM0QV2c2p%2BqpX%2ByJmCsPz%2FE4c1q%2BqL19wG2yI6MF6EmXn3vi3WUTEZjZ4drYClUgw%2FR5%2Bx%2F3%2Bc3Ldbzrh9Ze0jfCkvYyQxAaHe4HgARisjWCdcfULZKHNZksbmelA0liRz2MP696bwGOqUBLwylClB5Koqg6LlM6FJvAwjOtQQ5ZjuFKJMfHAvLRQiDNXg4BqnskTXE4znkTFJ3THOl4ubJDGauUwR33Z%2F18Yiawj6nED%2FtMcSi%2FpacS3302E6YdbhctXIkVnVY171Vkb7xMqImyzBtwRNAYT6mVRFhWA%2FMuCe3HK3wvX4kBOjGKe7k0rKc9AMu3eI%2BMmSL9ES8b1yAlr%2Fted7sisV0xK3i0WfT&X-Amz-Signature=e1f17643a6cf5e7c75f9076aea4acd8122e19989b0da45c4ef73bac6a0e29ddd&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665RWDWZ23%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T172040Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDn9oA9q%2Bq1EuhsF%2FlZdBOYtwFwvCJAEk11qq2QREsJOwIgNYRGakZlzbSC1KJd%2Fdcdh3p394yQYjLUzup2dCJw3vIqiAQIkv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDF7RtT%2FOdPJlC%2FGfJSrcA2pUwHngUP7te1C78Y1T97wPK%2F0MIKYXZD1DWji4Qo79aZECae5Xhxw9g7phTEu4%2FpdhM7gRfIP6%2Bo%2BgqdSfCfUoV8oBDXwkVuseJw4U%2BtTc5dfufM7U9KpIIFUiqqFbxm%2F0fpGrKLhdz0vcXDHhnZIM%2BDxVNvn4KUWh4zlUzkDMsn%2B7A9DNXNsAAcaIOYRUh6n63uUB6CyxQDQq88Ox5g3lRoYg9m2BVpUIR2YEJbM0SbE%2Fj1%2BhCgCZXA05Qil2Ed4GGb5rB2TGB6lfXDhPHcgS1iNNYg%2B9uTQ7NDxqS37OTGhzfxa8oNZa4N5ivEEk%2BjtVRPKZslK8FzJuZF8P64WEVamLP0EiHMA1wQw0nQdCN7ZLJijSqxV93yKnNA3mOFGO0Cr9hEW2TA5bwR4rZWMmlvPTeZPOwvPrAehmnd6jA6zHxI04j%2FKGruh1pkfIw%2FwDLVOCDV1UKtJ1cDqIBxm2y3ZotA26hefjAcBOeFcrVe6GziZgd9EITZM0QV2c2p%2BqpX%2ByJmCsPz%2FE4c1q%2BqL19wG2yI6MF6EmXn3vi3WUTEZjZ4drYClUgw%2FR5%2Bx%2F3%2Bc3Ldbzrh9Ze0jfCkvYyQxAaHe4HgARisjWCdcfULZKHNZksbmelA0liRz2MP696bwGOqUBLwylClB5Koqg6LlM6FJvAwjOtQQ5ZjuFKJMfHAvLRQiDNXg4BqnskTXE4znkTFJ3THOl4ubJDGauUwR33Z%2F18Yiawj6nED%2FtMcSi%2FpacS3302E6YdbhctXIkVnVY171Vkb7xMqImyzBtwRNAYT6mVRFhWA%2FMuCe3HK3wvX4kBOjGKe7k0rKc9AMu3eI%2BMmSL9ES8b1yAlr%2Fted7sisV0xK3i0WfT&X-Amz-Signature=1e185f28789ff191f2d827c53864ddf651825039bc0427f49ca61e3a63104446&X-Amz-SignedHeaders=host&x-id=GetObject)


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

