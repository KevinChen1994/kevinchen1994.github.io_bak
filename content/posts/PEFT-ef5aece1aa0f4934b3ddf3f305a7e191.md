---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466WN3RJELJ%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250207T191822Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEGMaCXVzLXdlc3QtMiJHMEUCIFl%2BcafG60KwgNQz2n4hU7vgJfzqASbEL4TUA6b1sVlbAiEAx\
  QXCFFdxEyGNPFuBucwL7k4dNOfG6CymqdMfHeCiqiAq%2FwMIfBAAGgw2Mzc0MjMxODM4MDUiDCFp\
  d024teW%2BQkkFkyrcA6bUfeBEZZDSeHEyV1pRLtmTSVZIZzzHwOGoKGF8HUCu5CPBorvZ%2FWA5u\
  wGAV1fURTdhu9ceV5wkZYIMs7R0VYURdoac445PQbnd34VmKvLuZKr4hYhLtSAABUdmObNtxawN1N\
  T74IlKeE5TZgnjYOIEbBXwM%2FOGsli%2BGev6i4tyRBm3cB3pQTkhjZm47pw70XxRbqva%2BvU%2\
  FFmH8l%2Br%2Bd4RNC3jQgesdyloE4%2BETh%2FGITMhzaMpLxPwYVBYjCwQBUL2D4Nirfq9F9mU1\
  MAVZq8rNh8EDViztzVRCGugITl8g11TMVzSJ3TBZjneRpAWgPyG0s7IGWdmSEp%2Bzj5H0nQL%2BJ\
  ChQLayYrRvMl%2BK31ajbkY8vAL2VBsSNdEzwo1qJs74EzRDCgj6%2BQnm%2Fl5%2FkPQWyqtcITH\
  FaAKTM3v6qsSjlzeHL2Ym9I0hZIkHf9gF45ryfF6VTmTuXPCKrC0SRqvUuO7RC6lJW0whmY11AujC\
  2RfxJPkuJTArskGQf%2B7Gs0zUGgMHw7ob19sL5J1ZHtPAt0ZO%2B%2B35yQK6QHq3csSrVRBwhwp\
  lN6egzQMlJI%2BcXhoJjeSt61%2FG%2BHJkbzIJyxNbMgh55aHoBKeCHwgcgL49ukI3CUg%2Bm3g8\
  SKbndMO%2B2mb0GOqUBkUMBaNGMl5nhZ5DRt0hhbaWSRfz0wAUpaUg95tKD5cooGiUcjdxtQHq0gv\
  dypOZb0uLPhHZvLl%2FcKisJ2sgLnRjNmsMgmsLSYSszA%2FrvkpnD2bF6%2BTAZmkZwLNg8hOdoj\
  k4WdagwpcOwPeKBrGFC9KHbrU6OWWul6%2BHdSLRfMwAzat8JQc9mddKYaZY%2F69swv03%2Fs312\
  9U%2BDLecR%2FKlhTYh%2F%2FwRY&X-Amz-Signature=3a1c15b89e8e791326e8c4658d1ec3ff\
  0da13ea2d785fa252aac7d0cb248e588&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466TEM6JXN2%2F20250207%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250207T191704Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEGMaCXVzLXdlc3QtMiJHMEUCIC2Q3hnea8B5Sie9%2BJ3ehm9tCM3iR\
        xWN4S9Eopfe81KhAiEAp7w3hxegcAxLp5rEUmBefclbAfqiheFr4IXR0%2FAuB6Yq%2FwMI\
        fBAAGgw2Mzc0MjMxODM4MDUiDJRXVyQq8x%2F1oAN1UCrcA2xjvV2km3GgTQSY%2FWNDGjc\
        U3XA7EJYjGFbJTcNhQhPjcFmrB%2FM2UD8MYfubCW3axtZKxZqozc9Xcd1gQvuDlZ4vLk0S\
        KPpRiCw5ZzAKxW6nRU%2BIMvtROtL3WF1zYKdlu3gyAbUjCcGQnBpmvoMi92Hd7H0fZyd7M\
        oTsKA%2BhaXE6%2Fl2%2FFr%2FXgQxfug%2B5eajXQ7Y8vV8dn%2F14d%2BwLFMKgrFRyOm\
        yE53fMt%2FzMgHbanFAOrKheoVFeod3z8pvpGy%2B9B3FOAkNYWh%2FTdGLQFluNvdxvfYE\
        0%2FN41SqXArdRH0jHqExaRyK4Z8w%2BNb7mL6tadtf1wNhRpBH2BAtvNCFP9%2FWhfYZ7F\
        rZfWwzVU%2B2pd58C9vkNwj0XNa5K270Pnsu0cL2TWZYDHAdw3RTZO7nH3nKnPelsUy%2Fs\
        lCGBinigih3ssOyKxVE74f1ewQJA0Rk2h0%2FKtQFRrjf2GfGu4xRPndKb9MTuhFs6WwFlW\
        nRFX7FMjwmJXm3A3TOf2Ud5gZCxsan7ug%2BKd2APOnuI5773XRuh%2F5EwLg0k8rvSWQ89\
        qSnhnb7Mo0LETkMJBDSwYk9b75DchZlwkuHjE8iBhhOTl2TVLoXqRKCrJyhgua%2Fhv6L51\
        wXF1ZJ7q%2FwI3QWfNMK63mb0GOqUBvuJe4zvK3fG2qlpDxyhRCO6uQbBDnD%2BRWpeT2ts\
        BJjjJZHSGX4A4T1n4BWR6MRu3dZLFyqWrQduReuX9hTRZFMoxk6P9Eq3EAaEPQmIBxucfaI\
        kPmpf4qHJm%2Bp2dOxr9IMzcVg9otvmdfWWZ5nvNRcbJB7%2BhRaBn%2F%2FsAGmoqFPTwT\
        dWLENMIwYzpATs2VLAniEfOM4F4A9hjcnh9OcH1xtuMLde4&X-Amz-Signature=4fd52b1\
        0b5f39fbb14c7293b18ed14aaddfd9986cfe515e1832182bd9be62a7f&X-Amz-SignedH\
        eaders=host&x-id=GetObject"
      expiry_time: "2025-02-07T20:17:04.385Z"
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
UPDATE_TIME: "2025-02-07T19:18:28.544Z"
EXPIRY_TIME: "2025-02-07T20:18:20.320Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664TI4NUMD%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T191820Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGMaCXVzLXdlc3QtMiJHMEUCICvt7uh1pg0fml6BDkeiiQfLSagDEDx%2Fy4q5jtukn5pZAiEA3ySWicZ9Yl2%2B1HsNPFqyt3QNG8n%2FU7cdHpxrQWwQJVsq%2FwMIfBAAGgw2Mzc0MjMxODM4MDUiDOzrCDzWD1PzfAdMUCrcAwxw63Rl%2FDd32De%2FzC4DLnFxsP5cJ1oVp%2BxJg6PhuGRZOWn1hzpgafTPKCXYWi3rAq%2BhKFD3cFM%2B4yW0xGeWcJThgCKTbj1ffjK99qDL5jNIeRTqctZzAAFx2nvmhZkzHE37RKvk2Kt8e3jJGysGzob0sFMABCEaRG49w08G7nJJsu2oEZFDzY6FXLDN4ON6fld1UP2hxvKesSjj5N2wj%2Fgl48s6J63HQG0vcWjjan1BE9YXCVP%2BwkK7pEjePNGdB%2BXgKZQCPUSRZi6pxjtI4NyHBu3ojQ8Onl9MmQPGfkWJ%2F72Vg5WwbH19SfftTNlbZUCUo%2BNlz0%2FUYE2HbGkcPCckZ5aP8u3mB2Njafyen1OsM5ovHTAgsycS08FqGJv1nOwSyvhKwQZNKQUNnLO7ZQoeD9rmfhY3QADOoj%2BkIqvm1k3KnAqa5INn82Y8kP%2Frjv55T0qygP%2BdYMKwipU%2FqbBjikf6QsxvuXpNOwDxFTdhEIVVf8ezQib6yrHTxL9e3mox%2Fw2tUu1hdAwVgjaqUCv64nuaLgKNfvl%2B9x21Falay5s1TruSZS1PpLBuVyJalC%2FDPp%2B%2BGEBaX43fck42UkEnN2o8d62i9T%2FEfPojEOtSYZZ5Am9MDPVHqTLLMOm2mb0GOqUB4f0YlsxnylAdX4t8fJhRZl34GQl16b0T80WRB%2BqNIt%2B4QC7j2cBdaWJQcDQozz6q9lVqK6hw8AhN3NIUNTQ8NA1uLyiH4LBnaOjyroJDTSvWj%2FEscCauiZgO5OM8VcK75azrAv1vy%2BpTTCKRm4N5VXeoiiQZlJFqMhU3k0eSooG0A%2FGxXfs64KXuTOIYqxBx5SgSRNWn%2F8ua8N2uvexYlXt9zMwk&X-Amz-Signature=224949256a366c55b4042958c66fb90c78d9ec35d8b2290909cbb9d4f33e51a2&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664TI4NUMD%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T191820Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGMaCXVzLXdlc3QtMiJHMEUCICvt7uh1pg0fml6BDkeiiQfLSagDEDx%2Fy4q5jtukn5pZAiEA3ySWicZ9Yl2%2B1HsNPFqyt3QNG8n%2FU7cdHpxrQWwQJVsq%2FwMIfBAAGgw2Mzc0MjMxODM4MDUiDOzrCDzWD1PzfAdMUCrcAwxw63Rl%2FDd32De%2FzC4DLnFxsP5cJ1oVp%2BxJg6PhuGRZOWn1hzpgafTPKCXYWi3rAq%2BhKFD3cFM%2B4yW0xGeWcJThgCKTbj1ffjK99qDL5jNIeRTqctZzAAFx2nvmhZkzHE37RKvk2Kt8e3jJGysGzob0sFMABCEaRG49w08G7nJJsu2oEZFDzY6FXLDN4ON6fld1UP2hxvKesSjj5N2wj%2Fgl48s6J63HQG0vcWjjan1BE9YXCVP%2BwkK7pEjePNGdB%2BXgKZQCPUSRZi6pxjtI4NyHBu3ojQ8Onl9MmQPGfkWJ%2F72Vg5WwbH19SfftTNlbZUCUo%2BNlz0%2FUYE2HbGkcPCckZ5aP8u3mB2Njafyen1OsM5ovHTAgsycS08FqGJv1nOwSyvhKwQZNKQUNnLO7ZQoeD9rmfhY3QADOoj%2BkIqvm1k3KnAqa5INn82Y8kP%2Frjv55T0qygP%2BdYMKwipU%2FqbBjikf6QsxvuXpNOwDxFTdhEIVVf8ezQib6yrHTxL9e3mox%2Fw2tUu1hdAwVgjaqUCv64nuaLgKNfvl%2B9x21Falay5s1TruSZS1PpLBuVyJalC%2FDPp%2B%2BGEBaX43fck42UkEnN2o8d62i9T%2FEfPojEOtSYZZ5Am9MDPVHqTLLMOm2mb0GOqUB4f0YlsxnylAdX4t8fJhRZl34GQl16b0T80WRB%2BqNIt%2B4QC7j2cBdaWJQcDQozz6q9lVqK6hw8AhN3NIUNTQ8NA1uLyiH4LBnaOjyroJDTSvWj%2FEscCauiZgO5OM8VcK75azrAv1vy%2BpTTCKRm4N5VXeoiiQZlJFqMhU3k0eSooG0A%2FGxXfs64KXuTOIYqxBx5SgSRNWn%2F8ua8N2uvexYlXt9zMwk&X-Amz-Signature=85fa355ed082477a2b405c36dd2128fbc125807a5272406dc7cf5943220ee347&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664TI4NUMD%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T191820Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGMaCXVzLXdlc3QtMiJHMEUCICvt7uh1pg0fml6BDkeiiQfLSagDEDx%2Fy4q5jtukn5pZAiEA3ySWicZ9Yl2%2B1HsNPFqyt3QNG8n%2FU7cdHpxrQWwQJVsq%2FwMIfBAAGgw2Mzc0MjMxODM4MDUiDOzrCDzWD1PzfAdMUCrcAwxw63Rl%2FDd32De%2FzC4DLnFxsP5cJ1oVp%2BxJg6PhuGRZOWn1hzpgafTPKCXYWi3rAq%2BhKFD3cFM%2B4yW0xGeWcJThgCKTbj1ffjK99qDL5jNIeRTqctZzAAFx2nvmhZkzHE37RKvk2Kt8e3jJGysGzob0sFMABCEaRG49w08G7nJJsu2oEZFDzY6FXLDN4ON6fld1UP2hxvKesSjj5N2wj%2Fgl48s6J63HQG0vcWjjan1BE9YXCVP%2BwkK7pEjePNGdB%2BXgKZQCPUSRZi6pxjtI4NyHBu3ojQ8Onl9MmQPGfkWJ%2F72Vg5WwbH19SfftTNlbZUCUo%2BNlz0%2FUYE2HbGkcPCckZ5aP8u3mB2Njafyen1OsM5ovHTAgsycS08FqGJv1nOwSyvhKwQZNKQUNnLO7ZQoeD9rmfhY3QADOoj%2BkIqvm1k3KnAqa5INn82Y8kP%2Frjv55T0qygP%2BdYMKwipU%2FqbBjikf6QsxvuXpNOwDxFTdhEIVVf8ezQib6yrHTxL9e3mox%2Fw2tUu1hdAwVgjaqUCv64nuaLgKNfvl%2B9x21Falay5s1TruSZS1PpLBuVyJalC%2FDPp%2B%2BGEBaX43fck42UkEnN2o8d62i9T%2FEfPojEOtSYZZ5Am9MDPVHqTLLMOm2mb0GOqUB4f0YlsxnylAdX4t8fJhRZl34GQl16b0T80WRB%2BqNIt%2B4QC7j2cBdaWJQcDQozz6q9lVqK6hw8AhN3NIUNTQ8NA1uLyiH4LBnaOjyroJDTSvWj%2FEscCauiZgO5OM8VcK75azrAv1vy%2BpTTCKRm4N5VXeoiiQZlJFqMhU3k0eSooG0A%2FGxXfs64KXuTOIYqxBx5SgSRNWn%2F8ua8N2uvexYlXt9zMwk&X-Amz-Signature=d233db89d9ae1daa7dc062802d591d8b7563fe06fb6617e66c9219e555aeadd2&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664TI4NUMD%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T191820Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGMaCXVzLXdlc3QtMiJHMEUCICvt7uh1pg0fml6BDkeiiQfLSagDEDx%2Fy4q5jtukn5pZAiEA3ySWicZ9Yl2%2B1HsNPFqyt3QNG8n%2FU7cdHpxrQWwQJVsq%2FwMIfBAAGgw2Mzc0MjMxODM4MDUiDOzrCDzWD1PzfAdMUCrcAwxw63Rl%2FDd32De%2FzC4DLnFxsP5cJ1oVp%2BxJg6PhuGRZOWn1hzpgafTPKCXYWi3rAq%2BhKFD3cFM%2B4yW0xGeWcJThgCKTbj1ffjK99qDL5jNIeRTqctZzAAFx2nvmhZkzHE37RKvk2Kt8e3jJGysGzob0sFMABCEaRG49w08G7nJJsu2oEZFDzY6FXLDN4ON6fld1UP2hxvKesSjj5N2wj%2Fgl48s6J63HQG0vcWjjan1BE9YXCVP%2BwkK7pEjePNGdB%2BXgKZQCPUSRZi6pxjtI4NyHBu3ojQ8Onl9MmQPGfkWJ%2F72Vg5WwbH19SfftTNlbZUCUo%2BNlz0%2FUYE2HbGkcPCckZ5aP8u3mB2Njafyen1OsM5ovHTAgsycS08FqGJv1nOwSyvhKwQZNKQUNnLO7ZQoeD9rmfhY3QADOoj%2BkIqvm1k3KnAqa5INn82Y8kP%2Frjv55T0qygP%2BdYMKwipU%2FqbBjikf6QsxvuXpNOwDxFTdhEIVVf8ezQib6yrHTxL9e3mox%2Fw2tUu1hdAwVgjaqUCv64nuaLgKNfvl%2B9x21Falay5s1TruSZS1PpLBuVyJalC%2FDPp%2B%2BGEBaX43fck42UkEnN2o8d62i9T%2FEfPojEOtSYZZ5Am9MDPVHqTLLMOm2mb0GOqUB4f0YlsxnylAdX4t8fJhRZl34GQl16b0T80WRB%2BqNIt%2B4QC7j2cBdaWJQcDQozz6q9lVqK6hw8AhN3NIUNTQ8NA1uLyiH4LBnaOjyroJDTSvWj%2FEscCauiZgO5OM8VcK75azrAv1vy%2BpTTCKRm4N5VXeoiiQZlJFqMhU3k0eSooG0A%2FGxXfs64KXuTOIYqxBx5SgSRNWn%2F8ua8N2uvexYlXt9zMwk&X-Amz-Signature=947c4935097f0a5db027b4b0fa87475abdade889638e500c024ad1121ca094ae&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664TI4NUMD%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T191820Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGMaCXVzLXdlc3QtMiJHMEUCICvt7uh1pg0fml6BDkeiiQfLSagDEDx%2Fy4q5jtukn5pZAiEA3ySWicZ9Yl2%2B1HsNPFqyt3QNG8n%2FU7cdHpxrQWwQJVsq%2FwMIfBAAGgw2Mzc0MjMxODM4MDUiDOzrCDzWD1PzfAdMUCrcAwxw63Rl%2FDd32De%2FzC4DLnFxsP5cJ1oVp%2BxJg6PhuGRZOWn1hzpgafTPKCXYWi3rAq%2BhKFD3cFM%2B4yW0xGeWcJThgCKTbj1ffjK99qDL5jNIeRTqctZzAAFx2nvmhZkzHE37RKvk2Kt8e3jJGysGzob0sFMABCEaRG49w08G7nJJsu2oEZFDzY6FXLDN4ON6fld1UP2hxvKesSjj5N2wj%2Fgl48s6J63HQG0vcWjjan1BE9YXCVP%2BwkK7pEjePNGdB%2BXgKZQCPUSRZi6pxjtI4NyHBu3ojQ8Onl9MmQPGfkWJ%2F72Vg5WwbH19SfftTNlbZUCUo%2BNlz0%2FUYE2HbGkcPCckZ5aP8u3mB2Njafyen1OsM5ovHTAgsycS08FqGJv1nOwSyvhKwQZNKQUNnLO7ZQoeD9rmfhY3QADOoj%2BkIqvm1k3KnAqa5INn82Y8kP%2Frjv55T0qygP%2BdYMKwipU%2FqbBjikf6QsxvuXpNOwDxFTdhEIVVf8ezQib6yrHTxL9e3mox%2Fw2tUu1hdAwVgjaqUCv64nuaLgKNfvl%2B9x21Falay5s1TruSZS1PpLBuVyJalC%2FDPp%2B%2BGEBaX43fck42UkEnN2o8d62i9T%2FEfPojEOtSYZZ5Am9MDPVHqTLLMOm2mb0GOqUB4f0YlsxnylAdX4t8fJhRZl34GQl16b0T80WRB%2BqNIt%2B4QC7j2cBdaWJQcDQozz6q9lVqK6hw8AhN3NIUNTQ8NA1uLyiH4LBnaOjyroJDTSvWj%2FEscCauiZgO5OM8VcK75azrAv1vy%2BpTTCKRm4N5VXeoiiQZlJFqMhU3k0eSooG0A%2FGxXfs64KXuTOIYqxBx5SgSRNWn%2F8ua8N2uvexYlXt9zMwk&X-Amz-Signature=fc9998cbd0bf65c2e3864f1c4b1f2f9b7bc41ad8e9b1909d41d40a3552d8a166&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RO6DFEUJ%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T191821Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGMaCXVzLXdlc3QtMiJIMEYCIQDr16sHlMz%2BJ1TJsn288OEnUVg7hhjJYEf3g9XBYlwhhwIhAJEeltD0bwfKHzaEqq%2B76GaEEaayYZ1%2FJ0mj6rP9agHGKv8DCHwQABoMNjM3NDIzMTgzODA1IgxUilukJiSk%2BVnmRjIq3AOqex1qYbls65L%2BBmb2iJ01VSfIvtjIPCY2F%2FuA0yjBs0TR7990%2F5a3wDVAh4WnoxnoYdp8ZIyJSYF9Ss6VsEVP1GiCCXITC0DuZnJ9jqMitxGL%2FhniWrq1p02dWtKaL8cNdgwq50saJiTcVfzvPiYOB91HWFDA1l49YcdxKVLumEt4zLssrQSn4%2Bcg2bKz3WLXx0TIxKqcfHSkgWyrus3gACLXqm4d3P0nO%2FSS9RjghKaj%2F1ThT3Xuh4UEgu8B5skCz1lHIx6W8I2WieWVd3Uer9gb6HuNlWzos4%2BcxILKAWZRfcckpD33lSD6VFx%2FDnwpyhDTfiUC6ZIznJ3EOGvvFDgGXKkLHht9Qb33jO1m%2FcPZ6iS%2FJz1T9iPb49LEUIq5Phv1zak1BxjzENzgaqm%2FwinEYKR%2BJbEejYmh9%2BF5DIvoYsyYYsvXeLNywmHLyaF6XJ3AbURXwCawvL3nLQ1%2BUwBQK74wqqEupapxnfgndP5A%2B2XmqmiXNCkWoNJW2k%2Bby%2FqZZVrmZSjaeAQdUPv3sMwrw3enbAyuBSCmQ%2FKGlN1XmFqRO8b5%2B1kh%2FOxVEKuos%2BGmNBew4VxIG77afmAxpEpOqiauoOJpoEFv6F%2BzspYfERf%2Bz1kfP6UYEjDxtpm9BjqkAU%2FlB4G2aCwIk6Dt4bVqkNjlUYK1o4amN4DH%2FUiOIXyQzgLWmgqb7K8wX3lK7LX%2BoERbKvgCx0Cbtv%2BcSLk%2BtFwi%2FWPIJd9O4m958JRLeYx0SksNE9OOdgUENTBYwstRuMC4Z7O2XCJAdH6Oi0PUKQLrCsUyJHmqzys8E686WFZqUZm%2Fs%2BwD7x1EkFn1L4fFEkXC%2FxCKwjbBtHY4VivOYsb55X5g&X-Amz-Signature=292faa35d1783f7468dc83c9ed69136c0e1ea3550fd2d1f427d7613e61b59edc&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RPHYPV6F%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T191821Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGMaCXVzLXdlc3QtMiJHMEUCIQCyIo5QlXNXcqnWBNao18x02CM7bfsIYDspWpt1zNLxowIgMut6r0dSwyLRA7Mx20dZJYWW0k9BtBBLm6Sh1%2BWo%2Bukq%2FwMIfBAAGgw2Mzc0MjMxODM4MDUiDKbc9%2F9br69d0A80SSrcAzyJs9R2qi6cTVkJIheRdvknmp%2FPLkmh96l2dQV6m%2FXx6IZFvHMRdt8IncLgX%2FBnWdxb8Bpg29Do1b59q2X%2FKtIoqQ%2FNd6KBYxeYBdHGpgw1zZHNX03cTK51knHLGFbCJvKupX0oAlrSkpUTbdntsEk77Ajjq6ZGUeS6ur6e6u3NOaAb8PnCwrvVJ3cK9EiaNYMou387ImaOK1tGBNnHugAzAtqnaGCy8TEM5zMhLcd7ebdG1y1STYNcSPJyIDfzo%2FCY8nlCE0lAWLmLRgjh4enzZ7Jc3tCU%2FKbLYwTW1kiEyBXLih2LCmLO3fETqioeEFn26wrU%2Fyp6c3SPBNTpgtQTVtNVvXKcDX%2FuEHM8vALp%2FAuj7Y3C763EztP71Ho3C7UXMSvfVdGRDS6KavqJVmC%2FZfZooj%2FM0H16u1mg52QjK4PamCdXllJDksi7y%2F8OgAGbbVXnljoK0gsF%2FrekxRG4Q15Zu%2BQvW43o8YS1FU2nFBNhaTnM5d0UsM7zNvp0w%2FP1GIhgZUduN27ZmtjGzBDVmX6eW%2Fc1geGJ7HIaeBK24t3kUquzD2q%2FGpjDnPWav0WIBh%2Bbq0SVBg3i2MW5p0hh2NMKUKvhSnUWZHBzL7FCkzsrqRdd%2F2Pe8AioMIi3mb0GOqUBRzko42DtPcdsvcqjXSC705wWCy7jfXTa2QMEVuDcrD00E0RwDwolGhYGxoaY2Q5Qh7dgarmZjGrAsknbkqaAUBPTrIfp%2BLrvd4vQI8M4adPCa5tSsOMOdc%2Blon8CaftP7mRBGGpBnOT1J2MQ4A7heGfDEnKH6SGXUQ14JO0OHWZacypiHHolKjZmT4F%2F2ZYEfRBiOulyfpwXUCm6Hl%2FtZGuR4Dpu&X-Amz-Signature=c6e55f35ec0ece07272488efe17c98125a34850e27903e05585e3ff55a978fa6&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664TI4NUMD%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T191820Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGMaCXVzLXdlc3QtMiJHMEUCICvt7uh1pg0fml6BDkeiiQfLSagDEDx%2Fy4q5jtukn5pZAiEA3ySWicZ9Yl2%2B1HsNPFqyt3QNG8n%2FU7cdHpxrQWwQJVsq%2FwMIfBAAGgw2Mzc0MjMxODM4MDUiDOzrCDzWD1PzfAdMUCrcAwxw63Rl%2FDd32De%2FzC4DLnFxsP5cJ1oVp%2BxJg6PhuGRZOWn1hzpgafTPKCXYWi3rAq%2BhKFD3cFM%2B4yW0xGeWcJThgCKTbj1ffjK99qDL5jNIeRTqctZzAAFx2nvmhZkzHE37RKvk2Kt8e3jJGysGzob0sFMABCEaRG49w08G7nJJsu2oEZFDzY6FXLDN4ON6fld1UP2hxvKesSjj5N2wj%2Fgl48s6J63HQG0vcWjjan1BE9YXCVP%2BwkK7pEjePNGdB%2BXgKZQCPUSRZi6pxjtI4NyHBu3ojQ8Onl9MmQPGfkWJ%2F72Vg5WwbH19SfftTNlbZUCUo%2BNlz0%2FUYE2HbGkcPCckZ5aP8u3mB2Njafyen1OsM5ovHTAgsycS08FqGJv1nOwSyvhKwQZNKQUNnLO7ZQoeD9rmfhY3QADOoj%2BkIqvm1k3KnAqa5INn82Y8kP%2Frjv55T0qygP%2BdYMKwipU%2FqbBjikf6QsxvuXpNOwDxFTdhEIVVf8ezQib6yrHTxL9e3mox%2Fw2tUu1hdAwVgjaqUCv64nuaLgKNfvl%2B9x21Falay5s1TruSZS1PpLBuVyJalC%2FDPp%2B%2BGEBaX43fck42UkEnN2o8d62i9T%2FEfPojEOtSYZZ5Am9MDPVHqTLLMOm2mb0GOqUB4f0YlsxnylAdX4t8fJhRZl34GQl16b0T80WRB%2BqNIt%2B4QC7j2cBdaWJQcDQozz6q9lVqK6hw8AhN3NIUNTQ8NA1uLyiH4LBnaOjyroJDTSvWj%2FEscCauiZgO5OM8VcK75azrAv1vy%2BpTTCKRm4N5VXeoiiQZlJFqMhU3k0eSooG0A%2FGxXfs64KXuTOIYqxBx5SgSRNWn%2F8ua8N2uvexYlXt9zMwk&X-Amz-Signature=b92bf6b45ce33c7b5acc3d1c66594e183f5e3c6271f84592641ec41980195178&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664TI4NUMD%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T191820Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGMaCXVzLXdlc3QtMiJHMEUCICvt7uh1pg0fml6BDkeiiQfLSagDEDx%2Fy4q5jtukn5pZAiEA3ySWicZ9Yl2%2B1HsNPFqyt3QNG8n%2FU7cdHpxrQWwQJVsq%2FwMIfBAAGgw2Mzc0MjMxODM4MDUiDOzrCDzWD1PzfAdMUCrcAwxw63Rl%2FDd32De%2FzC4DLnFxsP5cJ1oVp%2BxJg6PhuGRZOWn1hzpgafTPKCXYWi3rAq%2BhKFD3cFM%2B4yW0xGeWcJThgCKTbj1ffjK99qDL5jNIeRTqctZzAAFx2nvmhZkzHE37RKvk2Kt8e3jJGysGzob0sFMABCEaRG49w08G7nJJsu2oEZFDzY6FXLDN4ON6fld1UP2hxvKesSjj5N2wj%2Fgl48s6J63HQG0vcWjjan1BE9YXCVP%2BwkK7pEjePNGdB%2BXgKZQCPUSRZi6pxjtI4NyHBu3ojQ8Onl9MmQPGfkWJ%2F72Vg5WwbH19SfftTNlbZUCUo%2BNlz0%2FUYE2HbGkcPCckZ5aP8u3mB2Njafyen1OsM5ovHTAgsycS08FqGJv1nOwSyvhKwQZNKQUNnLO7ZQoeD9rmfhY3QADOoj%2BkIqvm1k3KnAqa5INn82Y8kP%2Frjv55T0qygP%2BdYMKwipU%2FqbBjikf6QsxvuXpNOwDxFTdhEIVVf8ezQib6yrHTxL9e3mox%2Fw2tUu1hdAwVgjaqUCv64nuaLgKNfvl%2B9x21Falay5s1TruSZS1PpLBuVyJalC%2FDPp%2B%2BGEBaX43fck42UkEnN2o8d62i9T%2FEfPojEOtSYZZ5Am9MDPVHqTLLMOm2mb0GOqUB4f0YlsxnylAdX4t8fJhRZl34GQl16b0T80WRB%2BqNIt%2B4QC7j2cBdaWJQcDQozz6q9lVqK6hw8AhN3NIUNTQ8NA1uLyiH4LBnaOjyroJDTSvWj%2FEscCauiZgO5OM8VcK75azrAv1vy%2BpTTCKRm4N5VXeoiiQZlJFqMhU3k0eSooG0A%2FGxXfs64KXuTOIYqxBx5SgSRNWn%2F8ua8N2uvexYlXt9zMwk&X-Amz-Signature=e82d71bda154eeb4522104f1aebfb3ffe9052a901c92978d2834148f236469a1&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664TI4NUMD%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T191820Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGMaCXVzLXdlc3QtMiJHMEUCICvt7uh1pg0fml6BDkeiiQfLSagDEDx%2Fy4q5jtukn5pZAiEA3ySWicZ9Yl2%2B1HsNPFqyt3QNG8n%2FU7cdHpxrQWwQJVsq%2FwMIfBAAGgw2Mzc0MjMxODM4MDUiDOzrCDzWD1PzfAdMUCrcAwxw63Rl%2FDd32De%2FzC4DLnFxsP5cJ1oVp%2BxJg6PhuGRZOWn1hzpgafTPKCXYWi3rAq%2BhKFD3cFM%2B4yW0xGeWcJThgCKTbj1ffjK99qDL5jNIeRTqctZzAAFx2nvmhZkzHE37RKvk2Kt8e3jJGysGzob0sFMABCEaRG49w08G7nJJsu2oEZFDzY6FXLDN4ON6fld1UP2hxvKesSjj5N2wj%2Fgl48s6J63HQG0vcWjjan1BE9YXCVP%2BwkK7pEjePNGdB%2BXgKZQCPUSRZi6pxjtI4NyHBu3ojQ8Onl9MmQPGfkWJ%2F72Vg5WwbH19SfftTNlbZUCUo%2BNlz0%2FUYE2HbGkcPCckZ5aP8u3mB2Njafyen1OsM5ovHTAgsycS08FqGJv1nOwSyvhKwQZNKQUNnLO7ZQoeD9rmfhY3QADOoj%2BkIqvm1k3KnAqa5INn82Y8kP%2Frjv55T0qygP%2BdYMKwipU%2FqbBjikf6QsxvuXpNOwDxFTdhEIVVf8ezQib6yrHTxL9e3mox%2Fw2tUu1hdAwVgjaqUCv64nuaLgKNfvl%2B9x21Falay5s1TruSZS1PpLBuVyJalC%2FDPp%2B%2BGEBaX43fck42UkEnN2o8d62i9T%2FEfPojEOtSYZZ5Am9MDPVHqTLLMOm2mb0GOqUB4f0YlsxnylAdX4t8fJhRZl34GQl16b0T80WRB%2BqNIt%2B4QC7j2cBdaWJQcDQozz6q9lVqK6hw8AhN3NIUNTQ8NA1uLyiH4LBnaOjyroJDTSvWj%2FEscCauiZgO5OM8VcK75azrAv1vy%2BpTTCKRm4N5VXeoiiQZlJFqMhU3k0eSooG0A%2FGxXfs64KXuTOIYqxBx5SgSRNWn%2F8ua8N2uvexYlXt9zMwk&X-Amz-Signature=a9c3d7da2d279c9d25423cf20d6c8ed57c441b62e447bda6743717d04a4c0df0&X-Amz-SignedHeaders=host&x-id=GetObject)


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

