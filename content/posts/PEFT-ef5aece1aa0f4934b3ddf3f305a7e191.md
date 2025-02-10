---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466TIZ4Q7HC%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250210T163001Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEKj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBCpfbpNwUqA8wKNNrf\
  o7iTItDMJpJFmUorPxXG%2B1jNpAiEA7krn109n%2BaNMXJgNsnyrBAtk0kdSQV3MsVJbZshl1oIq\
  iAQIwf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDARd7uTpMN34RYeMa\
  CrcAwo85jdfq%2BKC3Z6DNiqj%2FemoPE3MZ1AhpfSVy4sdpxcnp7FQBNlw4wLEt7G4Q8zDTvQZJx\
  G%2BZp0JNrzdybWCdp11qyh%2BvB6wXbv%2B3vle6RFd64Qhj3x1c1DJRS3U3MGTvh2eab1r%2B3V\
  qgtaEoWA5ycBdIDBK7uHXaxnBg0Gvn%2Bj7cmOiBlB2ySsUSCGieJwEfwQCv3MZKOMFXUndj4OxQ2\
  dv74mCITCDdr8AoWsdSbxZHhSdNf71nRczL823ogrZM7cyJnImOmgB%2B%2BhTeL3y%2FIguYB0LL\
  nb%2FvlYZDmJ0nSeLdgVPZE9%2Bcvjxh4zN6oAqjTx%2F6hLzbWqTW5LwyP4DgCaJnN%2FnxiihEb\
  TSU8Tz%2FVGiry%2FnWu7Ae8%2FF9XAbG5GNY%2BjTtgx4FhYWPc3gDeMoDSGMaRz1Bn0WnnZ5RnP\
  hHTN4jEPuZTJfrddF0TxjcRbCwpNaO2S5%2FgRL5T0GBrjDJSzzr69RctnfXXuA1HguDUTO%2FhDd\
  BBGy1PJfLIaHfekgxWoBop2tnZ0XMaEndPv9TMliUI1lqXvEFRfSmrXLKw9dD1FdJox4tvECl%2Fk\
  DhDOgDNSmYuZJ0fOvlVbBPmosUandLbzdeFsCzYN4edmViF3Yhd7YgO1b9%2FL8OVo%2FMJ68qL0G\
  OqUBN8u56gPEhaRSnlVx8XcTx1C16SWYXgQGS0DjAqSJrQ9N7bXUlffEGUmjtodnigfN1Tci09q%2\
  F0qtprNTxfgVn2memn1G%2FVqtJDJo8Gn3gzweo9aAoWwX90RnaMKppZ72AB6JS8HOMjAtAsE70mS\
  cshpS6MGGiU5PhPhl0MrxuLWlsiv%2FizuE7MG1g10Rmeeh8ECef8kDLH8vQ%2F84mkPD%2BAPCkA\
  GQC&X-Amz-Signature=03df0cb3d9a57c92469e3b1df81c2d8cd20847751ba41cf7b768a3065\
  cdb68c8&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466RUNXUHHV%2F20250210%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250210T162846Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEKj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQ\
        CICPLU7TfMW5oMIcwnsTHWyyYim0DH0kHUXy2I1%2BGaqZVAiBJDMEr408ZUlEjJ6JTUGDu\
        IQ70YzqU0S7srHHIzDt1%2FSqIBAjB%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzN\
        zQyMzE4MzgwNSIM8c7oisOyxT1KE31EKtwDuD9dKBO7OSZ2QXJ%2FlkaYtwfyI9R1OYQXLM\
        3hCeoh%2BrGX3iPggZk7thW1bcpB4N%2BzgfyYGFWaEptRhiRISjX%2FP3%2FFB5KZTDj%2\
        FCHl68Wy6%2FdKO6NeSAqUVjVwkFcCg%2BDG5CRgxY1s%2Fm3GQnaNn%2B%2FsyIr0JiV%2\
        BdNTU3XbwrZRxoqa1lz%2BnRzrlN53NP2Gk0%2BHcaDXzBoppWFqyO2koHQlPGfrFxV%2BW\
        Ijn1qFvI%2FEJMbNS65b%2BhSKqckVMnaSZqQAVNpn5xM51AZCH%2Fp8Cb9K%2BDLBk7nzy\
        zKdG2G9G1b29Ngo%2FOw2unWukQdGg0ELpssWqOerhbvg0eavptbuqOx8iOt6Uq8LOZOcJ6\
        31JFi4zcisrfSa1LMKfH0X8i7fuWdmEAmoIupawFeLmUT2%2BJRivVOBCxAApIZVaNgbNyq\
        XYrV1%2FRtrjoFG378MbmtpS6VvnYqu%2B8jQFVjaqquvg3rLklRHMzQ0%2FTqIAVKWP1k1\
        haxc0EoCVPZ6c%2Fkg5sbCClovlb661%2BO2cikPHY0QuEx%2FEUBqN49tTp4qiVFIFvOcV\
        nlV1ROpa1FNk8sda4mOQ4OeT0Vy3J2sNl4oRGrkt1Y%2BlFtidtz1iHidJ9gH2ZdGZ7TJX%\
        2FUsNLHb%2FL1KpfXrl0wnLyovQY6pgEzSyJQFfE2i%2BxrZeDZZ%2B5zMlqsWM37iGFtWR\
        RqVD11hSghDs5MYDxwbB%2B6SNbQ0M0A4nWqcmxs3S8cacWcWTiNf8CEMxoHNEkSqw73Ch7\
        NcynBJpywNg2T3X3lDVBKnozjW5mb3xDfCCZOtWWQpD%2BIgTGA33AwXAadbVyTRlShBarT\
        jwg8iVMRvA5RT1Jy9ZS67Px%2BnDn8GhMw8Qb%2BmGwM%2FMUcIvH%2B&X-Amz-Signatur\
        e=47bcbc8d6d9a00ef7e9923a40fcd0d900075f2d3eedecaf22e9d0f987de63133&X-Am\
        z-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-10T17:28:46.210Z"
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
UPDATE_TIME: "2025-02-10T16:30:06.552Z"
EXPIRY_TIME: "2025-02-10T17:29:56.576Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667MMA7BXY%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T162957Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICg3rZVaSGS7R2LrVwzKHULyZtBtr2YUkhkvnRoSHGZ3AiAzNKuwIci%2FOLdT7cMyhia%2B3jGnQG0x4YFkMuAQWAnXwCqIBAjB%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMEW0IcUcElYF5BGobKtwDKqAmzNqPhctYH7sEiyfbAm7WA5yGgnmbxS0NapItsmVxhPyuQfLM%2BtUUh5mEEfeXdlIQ%2FL%2B%2FpZkEHDjQziHaElG2U2QnUwLvI0SKrWxZN0Dw2vVN%2FUndcyBcDSJd5%2BRLyiTS29vqTEYBQqKDIvReRnYY6YAdjcMQd1DKcHSz9hTVH4%2FLardgwzcxej1CpJdwTtZdeLQHUNhhX5mYK%2FjSB4K2Y4jd%2BRyyyJMLhhSA%2BMzKDsGWr%2FT1owrYmcuRBPKzjrvhVON%2B0Wbc1EZJSRu8jlLUccQzQMKS9LGPZovrKXBHw89LTL3x3RuNt4Kw6mFi2XB9geZLe5q6M%2BNaDnvs5yrQTBDbUG9nL3nkjCctXmD%2F36RZ%2BIgR6Jd28AGAMigkzIHQmC67myKxqhVZvNqXJKKPzeHPzxjkcUY800doDHLaGbutL18pOv5U%2FJ4di6Ar2kgpb%2BRU1Z2MLvdn9i6uSz5KnDCnlm1s1h0BJl6Gc%2FUO%2FlG1xSlEZoaMCF2gERklBUUYLm7NbrP9A2tJ7yGF%2ByWT7Y7q1e3cq9oY%2FaopcmfWbUF2v67shaUdaHUAk7tuWs1Zw5%2BL%2BFlNYPagrgjeQnkM5gmDkT4jcsuWNk8qcmQdHDVkiBDgP0nl%2FPQw0byovQY6pgHnktOXy6MSuhtRnZaA9v%2BE2W9s67cTb%2BZhwD%2FbvqADOhP3ZTVVB4h6mcex6pTwXOE3rSumAoyxQoB2MfiMRAiNk2K1VVLtXXzbyw4XtGviMna1iArxMl1ZMD8vkV8YP8V9VjxEeOB7IqeOB29wlL4jH5ynD7Sjyqqf1Cbizh2ndGI68WA2HY6m4Y%2F13N8GZlMjqNS0DhIVabxX8YrnHFLMLehyGhCT&X-Amz-Signature=1f468fa1492ef7b4290aa6d89648ccbcb4c2dfe3865be29c84ba188edb0e3aef&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667MMA7BXY%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T162957Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICg3rZVaSGS7R2LrVwzKHULyZtBtr2YUkhkvnRoSHGZ3AiAzNKuwIci%2FOLdT7cMyhia%2B3jGnQG0x4YFkMuAQWAnXwCqIBAjB%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMEW0IcUcElYF5BGobKtwDKqAmzNqPhctYH7sEiyfbAm7WA5yGgnmbxS0NapItsmVxhPyuQfLM%2BtUUh5mEEfeXdlIQ%2FL%2B%2FpZkEHDjQziHaElG2U2QnUwLvI0SKrWxZN0Dw2vVN%2FUndcyBcDSJd5%2BRLyiTS29vqTEYBQqKDIvReRnYY6YAdjcMQd1DKcHSz9hTVH4%2FLardgwzcxej1CpJdwTtZdeLQHUNhhX5mYK%2FjSB4K2Y4jd%2BRyyyJMLhhSA%2BMzKDsGWr%2FT1owrYmcuRBPKzjrvhVON%2B0Wbc1EZJSRu8jlLUccQzQMKS9LGPZovrKXBHw89LTL3x3RuNt4Kw6mFi2XB9geZLe5q6M%2BNaDnvs5yrQTBDbUG9nL3nkjCctXmD%2F36RZ%2BIgR6Jd28AGAMigkzIHQmC67myKxqhVZvNqXJKKPzeHPzxjkcUY800doDHLaGbutL18pOv5U%2FJ4di6Ar2kgpb%2BRU1Z2MLvdn9i6uSz5KnDCnlm1s1h0BJl6Gc%2FUO%2FlG1xSlEZoaMCF2gERklBUUYLm7NbrP9A2tJ7yGF%2ByWT7Y7q1e3cq9oY%2FaopcmfWbUF2v67shaUdaHUAk7tuWs1Zw5%2BL%2BFlNYPagrgjeQnkM5gmDkT4jcsuWNk8qcmQdHDVkiBDgP0nl%2FPQw0byovQY6pgHnktOXy6MSuhtRnZaA9v%2BE2W9s67cTb%2BZhwD%2FbvqADOhP3ZTVVB4h6mcex6pTwXOE3rSumAoyxQoB2MfiMRAiNk2K1VVLtXXzbyw4XtGviMna1iArxMl1ZMD8vkV8YP8V9VjxEeOB7IqeOB29wlL4jH5ynD7Sjyqqf1Cbizh2ndGI68WA2HY6m4Y%2F13N8GZlMjqNS0DhIVabxX8YrnHFLMLehyGhCT&X-Amz-Signature=789d4d657c529bef4e0f90fdf9e6827c49eb55f01b99337069d03817aaa48d80&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667MMA7BXY%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T162957Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICg3rZVaSGS7R2LrVwzKHULyZtBtr2YUkhkvnRoSHGZ3AiAzNKuwIci%2FOLdT7cMyhia%2B3jGnQG0x4YFkMuAQWAnXwCqIBAjB%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMEW0IcUcElYF5BGobKtwDKqAmzNqPhctYH7sEiyfbAm7WA5yGgnmbxS0NapItsmVxhPyuQfLM%2BtUUh5mEEfeXdlIQ%2FL%2B%2FpZkEHDjQziHaElG2U2QnUwLvI0SKrWxZN0Dw2vVN%2FUndcyBcDSJd5%2BRLyiTS29vqTEYBQqKDIvReRnYY6YAdjcMQd1DKcHSz9hTVH4%2FLardgwzcxej1CpJdwTtZdeLQHUNhhX5mYK%2FjSB4K2Y4jd%2BRyyyJMLhhSA%2BMzKDsGWr%2FT1owrYmcuRBPKzjrvhVON%2B0Wbc1EZJSRu8jlLUccQzQMKS9LGPZovrKXBHw89LTL3x3RuNt4Kw6mFi2XB9geZLe5q6M%2BNaDnvs5yrQTBDbUG9nL3nkjCctXmD%2F36RZ%2BIgR6Jd28AGAMigkzIHQmC67myKxqhVZvNqXJKKPzeHPzxjkcUY800doDHLaGbutL18pOv5U%2FJ4di6Ar2kgpb%2BRU1Z2MLvdn9i6uSz5KnDCnlm1s1h0BJl6Gc%2FUO%2FlG1xSlEZoaMCF2gERklBUUYLm7NbrP9A2tJ7yGF%2ByWT7Y7q1e3cq9oY%2FaopcmfWbUF2v67shaUdaHUAk7tuWs1Zw5%2BL%2BFlNYPagrgjeQnkM5gmDkT4jcsuWNk8qcmQdHDVkiBDgP0nl%2FPQw0byovQY6pgHnktOXy6MSuhtRnZaA9v%2BE2W9s67cTb%2BZhwD%2FbvqADOhP3ZTVVB4h6mcex6pTwXOE3rSumAoyxQoB2MfiMRAiNk2K1VVLtXXzbyw4XtGviMna1iArxMl1ZMD8vkV8YP8V9VjxEeOB7IqeOB29wlL4jH5ynD7Sjyqqf1Cbizh2ndGI68WA2HY6m4Y%2F13N8GZlMjqNS0DhIVabxX8YrnHFLMLehyGhCT&X-Amz-Signature=248b63ad2f3dfdaa164d6ea4b5c10785800dc373e6365a2e7ca126f556562180&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667MMA7BXY%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T162957Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICg3rZVaSGS7R2LrVwzKHULyZtBtr2YUkhkvnRoSHGZ3AiAzNKuwIci%2FOLdT7cMyhia%2B3jGnQG0x4YFkMuAQWAnXwCqIBAjB%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMEW0IcUcElYF5BGobKtwDKqAmzNqPhctYH7sEiyfbAm7WA5yGgnmbxS0NapItsmVxhPyuQfLM%2BtUUh5mEEfeXdlIQ%2FL%2B%2FpZkEHDjQziHaElG2U2QnUwLvI0SKrWxZN0Dw2vVN%2FUndcyBcDSJd5%2BRLyiTS29vqTEYBQqKDIvReRnYY6YAdjcMQd1DKcHSz9hTVH4%2FLardgwzcxej1CpJdwTtZdeLQHUNhhX5mYK%2FjSB4K2Y4jd%2BRyyyJMLhhSA%2BMzKDsGWr%2FT1owrYmcuRBPKzjrvhVON%2B0Wbc1EZJSRu8jlLUccQzQMKS9LGPZovrKXBHw89LTL3x3RuNt4Kw6mFi2XB9geZLe5q6M%2BNaDnvs5yrQTBDbUG9nL3nkjCctXmD%2F36RZ%2BIgR6Jd28AGAMigkzIHQmC67myKxqhVZvNqXJKKPzeHPzxjkcUY800doDHLaGbutL18pOv5U%2FJ4di6Ar2kgpb%2BRU1Z2MLvdn9i6uSz5KnDCnlm1s1h0BJl6Gc%2FUO%2FlG1xSlEZoaMCF2gERklBUUYLm7NbrP9A2tJ7yGF%2ByWT7Y7q1e3cq9oY%2FaopcmfWbUF2v67shaUdaHUAk7tuWs1Zw5%2BL%2BFlNYPagrgjeQnkM5gmDkT4jcsuWNk8qcmQdHDVkiBDgP0nl%2FPQw0byovQY6pgHnktOXy6MSuhtRnZaA9v%2BE2W9s67cTb%2BZhwD%2FbvqADOhP3ZTVVB4h6mcex6pTwXOE3rSumAoyxQoB2MfiMRAiNk2K1VVLtXXzbyw4XtGviMna1iArxMl1ZMD8vkV8YP8V9VjxEeOB7IqeOB29wlL4jH5ynD7Sjyqqf1Cbizh2ndGI68WA2HY6m4Y%2F13N8GZlMjqNS0DhIVabxX8YrnHFLMLehyGhCT&X-Amz-Signature=1e0c41f82cc7b50cca8a6e4762ad6c9707412d5ef1e751d9f979c24308460bda&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667MMA7BXY%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T162957Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICg3rZVaSGS7R2LrVwzKHULyZtBtr2YUkhkvnRoSHGZ3AiAzNKuwIci%2FOLdT7cMyhia%2B3jGnQG0x4YFkMuAQWAnXwCqIBAjB%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMEW0IcUcElYF5BGobKtwDKqAmzNqPhctYH7sEiyfbAm7WA5yGgnmbxS0NapItsmVxhPyuQfLM%2BtUUh5mEEfeXdlIQ%2FL%2B%2FpZkEHDjQziHaElG2U2QnUwLvI0SKrWxZN0Dw2vVN%2FUndcyBcDSJd5%2BRLyiTS29vqTEYBQqKDIvReRnYY6YAdjcMQd1DKcHSz9hTVH4%2FLardgwzcxej1CpJdwTtZdeLQHUNhhX5mYK%2FjSB4K2Y4jd%2BRyyyJMLhhSA%2BMzKDsGWr%2FT1owrYmcuRBPKzjrvhVON%2B0Wbc1EZJSRu8jlLUccQzQMKS9LGPZovrKXBHw89LTL3x3RuNt4Kw6mFi2XB9geZLe5q6M%2BNaDnvs5yrQTBDbUG9nL3nkjCctXmD%2F36RZ%2BIgR6Jd28AGAMigkzIHQmC67myKxqhVZvNqXJKKPzeHPzxjkcUY800doDHLaGbutL18pOv5U%2FJ4di6Ar2kgpb%2BRU1Z2MLvdn9i6uSz5KnDCnlm1s1h0BJl6Gc%2FUO%2FlG1xSlEZoaMCF2gERklBUUYLm7NbrP9A2tJ7yGF%2ByWT7Y7q1e3cq9oY%2FaopcmfWbUF2v67shaUdaHUAk7tuWs1Zw5%2BL%2BFlNYPagrgjeQnkM5gmDkT4jcsuWNk8qcmQdHDVkiBDgP0nl%2FPQw0byovQY6pgHnktOXy6MSuhtRnZaA9v%2BE2W9s67cTb%2BZhwD%2FbvqADOhP3ZTVVB4h6mcex6pTwXOE3rSumAoyxQoB2MfiMRAiNk2K1VVLtXXzbyw4XtGviMna1iArxMl1ZMD8vkV8YP8V9VjxEeOB7IqeOB29wlL4jH5ynD7Sjyqqf1Cbizh2ndGI68WA2HY6m4Y%2F13N8GZlMjqNS0DhIVabxX8YrnHFLMLehyGhCT&X-Amz-Signature=93c6e589dee34e312ca7b848d91022a534947e5fe9b1746da8ed591752279ced&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663RRVHG7W%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T162957Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIH5%2BnNjvM%2BWgyLg0rxmy2YAitLIif7YVmAKQBgb%2FWCh8AiEA1DbUGzbIcf5lQY%2FtW3QivTqTCF8FtFdPBDp7L6%2BrGWUqiAQIwf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDF01RN%2BcUHwn%2B%2BY9LSrcA%2FQDZxxcv%2BGHZVbSG0PGwqWKAa18tImRxWmyI%2FjtPMSPJ6PbrZWBN8UsLSujw%2Fu1F%2BD1oCM27UUmlJfGzHtqABOGBLiDbIkCaP4RZZ5jkSIx9mprXq94L1iBH4yYo4DUhjjBsXNct5rQIm6rgAnQEeHx0mAmrhP4EvkPLADzS1wST3D4m9BuN9ejiaSVqSEeNI9pZHlsG7q64ncJii10fDcSr4brp9t3v0VgPSd82yWVaQPioFvmF3bz6g7aljJc6x2FjItxEYWCes4SIdiaW97ZnGv9ABgGj366OmBqcj8hHwolELTb0VgWcS8ADHCjmybT0NyuVLQxOvqzXr%2BubaPGM3nFa1ftnS%2FZ7h1psVGO%2FL62SF0gY%2FLDLtnh9C6BJC6jzIDM9qlvUR0GIIcfMZtmfZ3vgdjZVnzB2TvOh87uZTqhpIAt5OUtntvVW8ByP39yddQh5B7EITOUJr8s8pOaVsMcmBW5vbid7%2FQihkMB%2Bev8%2BtzPAuqNGMIMfW3UDUzni3ntcz9RAl%2Fz%2B%2BjIIPjE6NMGVSs1kp5fOTLBOxpk%2BlscQ8smMo1%2FCQY37sjFlu4NJiPi3C3mqbCxsF6F%2BcZoO3MiM6dpjxgF3KYVljjxwaVE%2FHtAzVZTGMjxMLi9qL0GOqUBQ%2Bhi2KtGj8CgwOCFWbvDSebcDOYlfg7sVFNE6In6%2BHCyp%2BT4Ffvnh%2F50Qfn4W90AC7COl1sXfkGrGW5BN4es5p2Yc6sq2EcugqDusplTy5x6frEVrMbIBVEqH0ELM3ZVvOrgLyzPWzIzf1r8RSCiODVHbB5IA%2BgGVHw9cssOkdnNvT6OoQAbntoHRKVI9cH2WhnsBErqp%2BgBUVLYpgx7xSaJGYhG&X-Amz-Signature=85fc213ba0a05e956d3850de717a26e044dfa28209e490159530eefa10acc907&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z7BONITD%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T163000Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDo1%2BCFCbmo2p2QAt69pvK1fC3dcxKL%2B0pEvEyp5rQmTQIhAOJDEir7J%2FQfb5OGNgY67oSQUcyIJr67dz8OMs81415WKogECMH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igzyc5tYqs5MLFQHu7Iq3AOXda%2Fc8tczg4oKoHesHftYxFlb7OQ3K3VcHuaROu0ljquF%2BnrO%2FeHTEvbxVsDUZ%2B9te14fENATYr9vEDJto5nx0Z%2BTB69muU2jHrroKRQzvg2nRPo6LUwQaK9wap7laq5GUm4GS2ivvt0SepR9Tex7uQfMp5ZfCbrY0DjnCCo0aJ1zpbpeJ9D5nAgCquLh0eD%2FNZYrDT1kCLd5fEzuhiGZI1kHLxxteejjxpVbGsiHEt6beBw7jPYwVeBhuKYTaPcVXxJivV03Ah75DO5McKOZHlQg2vZlNSKOBGzIE3Xf3293oTpRw0IcyeV4cMrzvUocEBZ1nXFZUS6FfdHsy%2FhFObo4CS76v7XZDOkwK6UsJWMiO6%2FSOR%2FPf9NZnpCXbQsPUoWqzgpMtFXQ%2F%2FQdWwcBEiWKmdFWAeydJIK2Pn%2FoKfcPMylReQmUALWVF4uYdh6pAL2IQ1MdmY2uS6A4siGMY%2B%2F9MmLzeWDnA8E594pKsL%2FjuOXu4AjHIhmMuDkTu1TlIvJO3XV%2FeH9OR4eISFXAnmjV%2Bcc2JOCocLaR4NOW4B%2FXNQ9kug1oThTrV%2BHPz%2BzgoP%2FSmCiL0NoX%2FvUYJJVIhbG3y%2FqXGWj7qAaro%2FYzhVfLNo%2Fa%2Baprs9DxfDCrvai9BjqkAa0r8serXGf%2F1vGtAx66pw540Nuz4vgf6c6IEbmuj6j7J7RTj20GhHQhn9jDRGG5nW5Ovw7mSAgHLjoeSGmlIpFghKAxuTfInGV14G%2BoSkbJ%2BEWDqF25yAe6Wv3mdW4GDk7oIxRqHWjdBbr4BTdVHJIFZwIC6eiObO5iJBVikeMow%2F73lmHZty0ZIBoo%2Fq9uexPd6UhRZuexQU9xvjUOc3mE64wK&X-Amz-Signature=7a58b507d8b1637973c5ab1922d306238e2934dd18d3b827186da9efbd0bfca5&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667MMA7BXY%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T162957Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICg3rZVaSGS7R2LrVwzKHULyZtBtr2YUkhkvnRoSHGZ3AiAzNKuwIci%2FOLdT7cMyhia%2B3jGnQG0x4YFkMuAQWAnXwCqIBAjB%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMEW0IcUcElYF5BGobKtwDKqAmzNqPhctYH7sEiyfbAm7WA5yGgnmbxS0NapItsmVxhPyuQfLM%2BtUUh5mEEfeXdlIQ%2FL%2B%2FpZkEHDjQziHaElG2U2QnUwLvI0SKrWxZN0Dw2vVN%2FUndcyBcDSJd5%2BRLyiTS29vqTEYBQqKDIvReRnYY6YAdjcMQd1DKcHSz9hTVH4%2FLardgwzcxej1CpJdwTtZdeLQHUNhhX5mYK%2FjSB4K2Y4jd%2BRyyyJMLhhSA%2BMzKDsGWr%2FT1owrYmcuRBPKzjrvhVON%2B0Wbc1EZJSRu8jlLUccQzQMKS9LGPZovrKXBHw89LTL3x3RuNt4Kw6mFi2XB9geZLe5q6M%2BNaDnvs5yrQTBDbUG9nL3nkjCctXmD%2F36RZ%2BIgR6Jd28AGAMigkzIHQmC67myKxqhVZvNqXJKKPzeHPzxjkcUY800doDHLaGbutL18pOv5U%2FJ4di6Ar2kgpb%2BRU1Z2MLvdn9i6uSz5KnDCnlm1s1h0BJl6Gc%2FUO%2FlG1xSlEZoaMCF2gERklBUUYLm7NbrP9A2tJ7yGF%2ByWT7Y7q1e3cq9oY%2FaopcmfWbUF2v67shaUdaHUAk7tuWs1Zw5%2BL%2BFlNYPagrgjeQnkM5gmDkT4jcsuWNk8qcmQdHDVkiBDgP0nl%2FPQw0byovQY6pgHnktOXy6MSuhtRnZaA9v%2BE2W9s67cTb%2BZhwD%2FbvqADOhP3ZTVVB4h6mcex6pTwXOE3rSumAoyxQoB2MfiMRAiNk2K1VVLtXXzbyw4XtGviMna1iArxMl1ZMD8vkV8YP8V9VjxEeOB7IqeOB29wlL4jH5ynD7Sjyqqf1Cbizh2ndGI68WA2HY6m4Y%2F13N8GZlMjqNS0DhIVabxX8YrnHFLMLehyGhCT&X-Amz-Signature=7ef499fe03da4560898924a1c5ac5d165dd5aa45cefd000952188095ecb514f1&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667MMA7BXY%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T162957Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICg3rZVaSGS7R2LrVwzKHULyZtBtr2YUkhkvnRoSHGZ3AiAzNKuwIci%2FOLdT7cMyhia%2B3jGnQG0x4YFkMuAQWAnXwCqIBAjB%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMEW0IcUcElYF5BGobKtwDKqAmzNqPhctYH7sEiyfbAm7WA5yGgnmbxS0NapItsmVxhPyuQfLM%2BtUUh5mEEfeXdlIQ%2FL%2B%2FpZkEHDjQziHaElG2U2QnUwLvI0SKrWxZN0Dw2vVN%2FUndcyBcDSJd5%2BRLyiTS29vqTEYBQqKDIvReRnYY6YAdjcMQd1DKcHSz9hTVH4%2FLardgwzcxej1CpJdwTtZdeLQHUNhhX5mYK%2FjSB4K2Y4jd%2BRyyyJMLhhSA%2BMzKDsGWr%2FT1owrYmcuRBPKzjrvhVON%2B0Wbc1EZJSRu8jlLUccQzQMKS9LGPZovrKXBHw89LTL3x3RuNt4Kw6mFi2XB9geZLe5q6M%2BNaDnvs5yrQTBDbUG9nL3nkjCctXmD%2F36RZ%2BIgR6Jd28AGAMigkzIHQmC67myKxqhVZvNqXJKKPzeHPzxjkcUY800doDHLaGbutL18pOv5U%2FJ4di6Ar2kgpb%2BRU1Z2MLvdn9i6uSz5KnDCnlm1s1h0BJl6Gc%2FUO%2FlG1xSlEZoaMCF2gERklBUUYLm7NbrP9A2tJ7yGF%2ByWT7Y7q1e3cq9oY%2FaopcmfWbUF2v67shaUdaHUAk7tuWs1Zw5%2BL%2BFlNYPagrgjeQnkM5gmDkT4jcsuWNk8qcmQdHDVkiBDgP0nl%2FPQw0byovQY6pgHnktOXy6MSuhtRnZaA9v%2BE2W9s67cTb%2BZhwD%2FbvqADOhP3ZTVVB4h6mcex6pTwXOE3rSumAoyxQoB2MfiMRAiNk2K1VVLtXXzbyw4XtGviMna1iArxMl1ZMD8vkV8YP8V9VjxEeOB7IqeOB29wlL4jH5ynD7Sjyqqf1Cbizh2ndGI68WA2HY6m4Y%2F13N8GZlMjqNS0DhIVabxX8YrnHFLMLehyGhCT&X-Amz-Signature=3cc0a5aac3ccaaff4b51bb776ce8f883b27ad6ab0649e2cc3e4e7429bc2f3e4e&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667MMA7BXY%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T162957Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICg3rZVaSGS7R2LrVwzKHULyZtBtr2YUkhkvnRoSHGZ3AiAzNKuwIci%2FOLdT7cMyhia%2B3jGnQG0x4YFkMuAQWAnXwCqIBAjB%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMEW0IcUcElYF5BGobKtwDKqAmzNqPhctYH7sEiyfbAm7WA5yGgnmbxS0NapItsmVxhPyuQfLM%2BtUUh5mEEfeXdlIQ%2FL%2B%2FpZkEHDjQziHaElG2U2QnUwLvI0SKrWxZN0Dw2vVN%2FUndcyBcDSJd5%2BRLyiTS29vqTEYBQqKDIvReRnYY6YAdjcMQd1DKcHSz9hTVH4%2FLardgwzcxej1CpJdwTtZdeLQHUNhhX5mYK%2FjSB4K2Y4jd%2BRyyyJMLhhSA%2BMzKDsGWr%2FT1owrYmcuRBPKzjrvhVON%2B0Wbc1EZJSRu8jlLUccQzQMKS9LGPZovrKXBHw89LTL3x3RuNt4Kw6mFi2XB9geZLe5q6M%2BNaDnvs5yrQTBDbUG9nL3nkjCctXmD%2F36RZ%2BIgR6Jd28AGAMigkzIHQmC67myKxqhVZvNqXJKKPzeHPzxjkcUY800doDHLaGbutL18pOv5U%2FJ4di6Ar2kgpb%2BRU1Z2MLvdn9i6uSz5KnDCnlm1s1h0BJl6Gc%2FUO%2FlG1xSlEZoaMCF2gERklBUUYLm7NbrP9A2tJ7yGF%2ByWT7Y7q1e3cq9oY%2FaopcmfWbUF2v67shaUdaHUAk7tuWs1Zw5%2BL%2BFlNYPagrgjeQnkM5gmDkT4jcsuWNk8qcmQdHDVkiBDgP0nl%2FPQw0byovQY6pgHnktOXy6MSuhtRnZaA9v%2BE2W9s67cTb%2BZhwD%2FbvqADOhP3ZTVVB4h6mcex6pTwXOE3rSumAoyxQoB2MfiMRAiNk2K1VVLtXXzbyw4XtGviMna1iArxMl1ZMD8vkV8YP8V9VjxEeOB7IqeOB29wlL4jH5ynD7Sjyqqf1Cbizh2ndGI68WA2HY6m4Y%2F13N8GZlMjqNS0DhIVabxX8YrnHFLMLehyGhCT&X-Amz-Signature=90bad5ec2d05b9465d8d5335e6f65fe51f4a070ba96028a781c0373622b7ea85&X-Amz-SignedHeaders=host&x-id=GetObject)


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

