---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466YG5V2MU7%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250213T232250Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEPb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIFY62u2WGuiY3XGVYUY\
  vKJae0Iz%2BhNYZW7FQRaXs1PHuAiEAkdkn12P4cRr21dTsnStMdWvjLDAkG1JN8w4V5B3WFnIq%2\
  FwMIHxAAGgw2Mzc0MjMxODM4MDUiDMrW3WdgqRPUUlaZQCrcA9OMwOq550MwnvtXNdXUx9FujhKCl\
  nnzG7N%2BHNdqXbH2m%2FplJ2nn0nBLTVuH5hwa5j3yf916wO8Fij%2BdH6%2F1VXfTKMBqrB0Jcm\
  0RqRjJgPjZqkY82sP%2F7EpzYtrkkR66F16j9ffqGawbxYiubJEdeDwA2VMQfQKn3LzhF2YqnIunw\
  3Gs3%2BE%2Fh8a1mVkvpQuAvEnflgzZ9CbBskbOkkxkJQm1Apuj%2F6TgLrHhMqtOHNZLr%2BNWtB\
  hh34NFaRuxLo29Q9ST7npy2qZLrVw8QipXuZwxyrxxeNXoR9fgjCmry2OGig%2FuCdyA832XtZDc5\
  oKiOQ62ttiCdNutD%2B8cJIKGnL%2FUuI82s2e6b1UhPmS%2BOd3pZ0f8p3gFgaLjpS1AxEcub1KC\
  8zwAcCr54YiOgZedqu3qTyNCKfVp%2FfOkfBhhacHAEOlozC9on%2F8qqNsQSWoEAv2MO4%2FZX1C\
  0Fe%2BfSMhahA0fMRX98ohkred4tOupC9usi97FTEvLXnQAyrzBZ9OUqc3JPQlVZLRWXl3AQDx49v\
  uog9%2BYMpIEdphfaxI3irZ8flax1J9jAIRX1%2BJpAJjU%2B233YIcSN3EDrsqHzqkh%2FhfbR43\
  f9KZbBGTlBte6mVfaMNpU5BDfkZBp3890MILaub0GOqUBk%2Bk18Nxm9JPwske921PEYYTNE%2F0F\
  cGHCCGESECCRvb8%2FomzEO7of9f4EHqlmbwI3elLnexuLdgw%2Fcnr6Zb2XoCAW7A%2FXX36DRtf\
  mE1BYb1omOHdPFeBW2lA4w4TdKqKDr2DzM5gJCo3Yx4m1pkgYBvUheWquCfB%2BUEQf6u2Inrxg7P\
  GI44o3Trcaj28hqFE1WGFyXZsf9p%2FTQ%2FY8lO7OEWULiY6y&X-Amz-Signature=789b27e97f\
  82127005fd2ec88221f8caf9ded910f9e27cfb2253d38ecdff513a&X-Amz-SignedHeaders=ho\
  st&x-id=GetObject"
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
        redential=ASIAZI2LB46623MPPFVO%2F20250213%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250213T232137Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEPb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQ\
        CIGwjNZouhBCtswR9YspxbxcrIkxAiJ08Ut4ChvSnmlM6AiAH3nlPyyjBwNm%2BRmc%2B1H\
        sRUoMPb6nZVgxp0OnGAeOn%2Bir%2FAwgfEAAaDDYzNzQyMzE4MzgwNSIMjz8xTqTwe7I4G\
        ju7KtwDPEbdvBHC%2FRThDEUFMjhsyJClaViI2wuI5p66J6ReH5OAa7qz9ok5h0LfocwEta\
        BJhMROWn75GSLxnJ1DZFxcwNE3zQbJNu5oRO7299T9CHVDge9prxHcknmREBcYaxM7sDs1v\
        msoOChRtxXH%2B1uwP58siw2bzv5ZEyMD705Ykfr7jEkgvJwibBB0vE6021gbPIwTk7mmZZ\
        grEsLpW1a6%2FwZi53UI027I8RazdlBfCoS%2BAGhmNg5Z8mmE1p9XwQegpehKUfW1gBM0T\
        WMcSiLGK8vpbnoFziO%2BtO5i6pQL8EzNNhAISHCanHP2bNO9etG3o6fVW6Rsd2R104rmpM\
        lfWwccyvBzmf8d7azGnfLhNA52Q0werN53YOH6K7X6HkpJWtEciqgM4u8G3HqUxALjjzrEl\
        YuzZ9Ft73cUE6U9sFSpenrYNosNA6vefKbI0DZHImlsRaqIODtoZFVoc%2BYoMoN9j3uhn%\
        2Bd%2F8MeMtfbFlQ%2FdZ0nSOY%2BgHjY%2Fgg7Eb1bYBoiU4LMKkD%2Fll4sTuDVto%2Bs\
        1QtBx28godsof4LFLUZjnTZdU3spH8DzrzPNtKcPz9hgMhFbqYDwid1CRS5G%2FaekuSg2R\
        YxEPqvmbQwIETpQAY5J9GKZLuDj7E0Iw0dm5vQY6pgHOm%2Bc49InnviOFw3q7gtBi59Nfc\
        YZY1Wn7TnXt9UFxRmt7RJupqzaUmAHHKcp68ZMAXhzpVM4dIfffxNILaMm%2BWEbX4Fm%2B\
        iZA1%2FXS%2FcPgkIryOTeGaBi63T1R4bUFkLtAnFwWcEkYrRqP4C5%2BZaEjVC8v4Oi4%2\
        FMZDfSvmbNVDYB0ByZyoFaVoQ66A1BO7VTZGEy1WB0abyK0Qksr94VG1Rd%2Feusooj&X-A\
        mz-Signature=8b1aea9ee031c500741e7677a9dcbe59c79174eb6ce06cf8855829fa36\
        7ee9f3&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-14T00:21:36.972Z"
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
UPDATE_TIME: "2025-02-13T23:22:54.975Z"
EXPIRY_TIME: "2025-02-14T00:22:47.038Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665ZDPBLH3%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T232247Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD0la6NT8mWfZ4yf8dfu6IgxyVNIv2n1VjQscU1ZOpBXgIhAPRimJc6GoS6AhU9FtKx299Ue3JA8H0RJcfFsXQUeXYuKv8DCB8QABoMNjM3NDIzMTgzODA1IgyYWVJXdxHlulTh%2BW4q3AMrNMP1IygzoyO6JE5QRRimKXC%2Fsafx7UP9xk2kE8bovXReiTt1Eov7VAnPBA6ip4mkXx5Qpa5PM9AOeoLUmmRD3btLQlEICLEflr02jvBNCVeuM1CAZ5anYNu2AQNlMqdWZDIqig8d15l2H6%2BHxXVfqs3%2FkJUrcTxzfLoGcDxxi%2BkkJTr9SipQcosmSNaaJgPO5HNUxDCN3oOoDLxmMg62CMAgUqbuAHaeLCWmePtp%2BXvlKfspOioQJNC0en9rCNRc8m5QDV0xYhyEvFehmizvVOPaCg%2BgTNExg3LLnjdSQw9IagzdAxB0RniNR8FN0lUk0154Fid0YJXqm%2B%2BZhdbHELs6KjK3QZe51gIwYilJozGW479%2FlsrqFoMKFt5jUH7gJlawdhOs%2F0qTNkFFQWHmxSJwEl6GwlZ8RakrzO1n7iw7J6Iwd5EggiDMvLHioXSFeWjfQMxPG6VA0KBKiORLvW%2BrAqdOh1HmL43C8dNGvw%2BPYd5XliuK4PSspLA4hu1sRQjX4pev8xLj7WSUNxA9XBPfNwURpfpg4KLUyXlj0CkToo9Cv1fV9o%2B0BUu2B9HBYmZvuCE21NdvakotPnTW5VdCObxQL2a27Tvi8XPv4PJ4fpR98XsaOv82czDX2bm9BjqkAQnJZjqIQNGFDLsbLyOb4zWs4b5FRh%2F7VTezbexcFrRbc3p2BE%2F3BhVqa%2Bv6DY5GjdcfBZh6CCLjYYQlC%2BtKg5TwyXURqHzJDP5pRdxLQSJEWx0dZq9ddI00YdiNAbZEcXXSsuJ7WOq5U3siWneKXcekcOKAsoEUV%2FXRlzsvtac9QdO%2BfCelIACJOr4kcyRJmQBjTIciesRxhS0BvMkKwXhcujsn&X-Amz-Signature=c1f010bffb080150f88e505034a0168aaa80b3ca4141a1463e2cc1d18e915599&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665ZDPBLH3%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T232247Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD0la6NT8mWfZ4yf8dfu6IgxyVNIv2n1VjQscU1ZOpBXgIhAPRimJc6GoS6AhU9FtKx299Ue3JA8H0RJcfFsXQUeXYuKv8DCB8QABoMNjM3NDIzMTgzODA1IgyYWVJXdxHlulTh%2BW4q3AMrNMP1IygzoyO6JE5QRRimKXC%2Fsafx7UP9xk2kE8bovXReiTt1Eov7VAnPBA6ip4mkXx5Qpa5PM9AOeoLUmmRD3btLQlEICLEflr02jvBNCVeuM1CAZ5anYNu2AQNlMqdWZDIqig8d15l2H6%2BHxXVfqs3%2FkJUrcTxzfLoGcDxxi%2BkkJTr9SipQcosmSNaaJgPO5HNUxDCN3oOoDLxmMg62CMAgUqbuAHaeLCWmePtp%2BXvlKfspOioQJNC0en9rCNRc8m5QDV0xYhyEvFehmizvVOPaCg%2BgTNExg3LLnjdSQw9IagzdAxB0RniNR8FN0lUk0154Fid0YJXqm%2B%2BZhdbHELs6KjK3QZe51gIwYilJozGW479%2FlsrqFoMKFt5jUH7gJlawdhOs%2F0qTNkFFQWHmxSJwEl6GwlZ8RakrzO1n7iw7J6Iwd5EggiDMvLHioXSFeWjfQMxPG6VA0KBKiORLvW%2BrAqdOh1HmL43C8dNGvw%2BPYd5XliuK4PSspLA4hu1sRQjX4pev8xLj7WSUNxA9XBPfNwURpfpg4KLUyXlj0CkToo9Cv1fV9o%2B0BUu2B9HBYmZvuCE21NdvakotPnTW5VdCObxQL2a27Tvi8XPv4PJ4fpR98XsaOv82czDX2bm9BjqkAQnJZjqIQNGFDLsbLyOb4zWs4b5FRh%2F7VTezbexcFrRbc3p2BE%2F3BhVqa%2Bv6DY5GjdcfBZh6CCLjYYQlC%2BtKg5TwyXURqHzJDP5pRdxLQSJEWx0dZq9ddI00YdiNAbZEcXXSsuJ7WOq5U3siWneKXcekcOKAsoEUV%2FXRlzsvtac9QdO%2BfCelIACJOr4kcyRJmQBjTIciesRxhS0BvMkKwXhcujsn&X-Amz-Signature=e5eab11fbc199d560752814e6538d39d347044c626ee8c7d8da96ff34d5d81e6&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665ZDPBLH3%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T232247Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD0la6NT8mWfZ4yf8dfu6IgxyVNIv2n1VjQscU1ZOpBXgIhAPRimJc6GoS6AhU9FtKx299Ue3JA8H0RJcfFsXQUeXYuKv8DCB8QABoMNjM3NDIzMTgzODA1IgyYWVJXdxHlulTh%2BW4q3AMrNMP1IygzoyO6JE5QRRimKXC%2Fsafx7UP9xk2kE8bovXReiTt1Eov7VAnPBA6ip4mkXx5Qpa5PM9AOeoLUmmRD3btLQlEICLEflr02jvBNCVeuM1CAZ5anYNu2AQNlMqdWZDIqig8d15l2H6%2BHxXVfqs3%2FkJUrcTxzfLoGcDxxi%2BkkJTr9SipQcosmSNaaJgPO5HNUxDCN3oOoDLxmMg62CMAgUqbuAHaeLCWmePtp%2BXvlKfspOioQJNC0en9rCNRc8m5QDV0xYhyEvFehmizvVOPaCg%2BgTNExg3LLnjdSQw9IagzdAxB0RniNR8FN0lUk0154Fid0YJXqm%2B%2BZhdbHELs6KjK3QZe51gIwYilJozGW479%2FlsrqFoMKFt5jUH7gJlawdhOs%2F0qTNkFFQWHmxSJwEl6GwlZ8RakrzO1n7iw7J6Iwd5EggiDMvLHioXSFeWjfQMxPG6VA0KBKiORLvW%2BrAqdOh1HmL43C8dNGvw%2BPYd5XliuK4PSspLA4hu1sRQjX4pev8xLj7WSUNxA9XBPfNwURpfpg4KLUyXlj0CkToo9Cv1fV9o%2B0BUu2B9HBYmZvuCE21NdvakotPnTW5VdCObxQL2a27Tvi8XPv4PJ4fpR98XsaOv82czDX2bm9BjqkAQnJZjqIQNGFDLsbLyOb4zWs4b5FRh%2F7VTezbexcFrRbc3p2BE%2F3BhVqa%2Bv6DY5GjdcfBZh6CCLjYYQlC%2BtKg5TwyXURqHzJDP5pRdxLQSJEWx0dZq9ddI00YdiNAbZEcXXSsuJ7WOq5U3siWneKXcekcOKAsoEUV%2FXRlzsvtac9QdO%2BfCelIACJOr4kcyRJmQBjTIciesRxhS0BvMkKwXhcujsn&X-Amz-Signature=21fafe1db5dba92c3bc985e6efdebc59ac510b17350bc2942b0f84fa0ee566ec&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665ZDPBLH3%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T232247Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD0la6NT8mWfZ4yf8dfu6IgxyVNIv2n1VjQscU1ZOpBXgIhAPRimJc6GoS6AhU9FtKx299Ue3JA8H0RJcfFsXQUeXYuKv8DCB8QABoMNjM3NDIzMTgzODA1IgyYWVJXdxHlulTh%2BW4q3AMrNMP1IygzoyO6JE5QRRimKXC%2Fsafx7UP9xk2kE8bovXReiTt1Eov7VAnPBA6ip4mkXx5Qpa5PM9AOeoLUmmRD3btLQlEICLEflr02jvBNCVeuM1CAZ5anYNu2AQNlMqdWZDIqig8d15l2H6%2BHxXVfqs3%2FkJUrcTxzfLoGcDxxi%2BkkJTr9SipQcosmSNaaJgPO5HNUxDCN3oOoDLxmMg62CMAgUqbuAHaeLCWmePtp%2BXvlKfspOioQJNC0en9rCNRc8m5QDV0xYhyEvFehmizvVOPaCg%2BgTNExg3LLnjdSQw9IagzdAxB0RniNR8FN0lUk0154Fid0YJXqm%2B%2BZhdbHELs6KjK3QZe51gIwYilJozGW479%2FlsrqFoMKFt5jUH7gJlawdhOs%2F0qTNkFFQWHmxSJwEl6GwlZ8RakrzO1n7iw7J6Iwd5EggiDMvLHioXSFeWjfQMxPG6VA0KBKiORLvW%2BrAqdOh1HmL43C8dNGvw%2BPYd5XliuK4PSspLA4hu1sRQjX4pev8xLj7WSUNxA9XBPfNwURpfpg4KLUyXlj0CkToo9Cv1fV9o%2B0BUu2B9HBYmZvuCE21NdvakotPnTW5VdCObxQL2a27Tvi8XPv4PJ4fpR98XsaOv82czDX2bm9BjqkAQnJZjqIQNGFDLsbLyOb4zWs4b5FRh%2F7VTezbexcFrRbc3p2BE%2F3BhVqa%2Bv6DY5GjdcfBZh6CCLjYYQlC%2BtKg5TwyXURqHzJDP5pRdxLQSJEWx0dZq9ddI00YdiNAbZEcXXSsuJ7WOq5U3siWneKXcekcOKAsoEUV%2FXRlzsvtac9QdO%2BfCelIACJOr4kcyRJmQBjTIciesRxhS0BvMkKwXhcujsn&X-Amz-Signature=a1b95e59b55b454c8a88375b83d437a32b64b6c3c677633fc3a1ff078576f760&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665ZDPBLH3%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T232247Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD0la6NT8mWfZ4yf8dfu6IgxyVNIv2n1VjQscU1ZOpBXgIhAPRimJc6GoS6AhU9FtKx299Ue3JA8H0RJcfFsXQUeXYuKv8DCB8QABoMNjM3NDIzMTgzODA1IgyYWVJXdxHlulTh%2BW4q3AMrNMP1IygzoyO6JE5QRRimKXC%2Fsafx7UP9xk2kE8bovXReiTt1Eov7VAnPBA6ip4mkXx5Qpa5PM9AOeoLUmmRD3btLQlEICLEflr02jvBNCVeuM1CAZ5anYNu2AQNlMqdWZDIqig8d15l2H6%2BHxXVfqs3%2FkJUrcTxzfLoGcDxxi%2BkkJTr9SipQcosmSNaaJgPO5HNUxDCN3oOoDLxmMg62CMAgUqbuAHaeLCWmePtp%2BXvlKfspOioQJNC0en9rCNRc8m5QDV0xYhyEvFehmizvVOPaCg%2BgTNExg3LLnjdSQw9IagzdAxB0RniNR8FN0lUk0154Fid0YJXqm%2B%2BZhdbHELs6KjK3QZe51gIwYilJozGW479%2FlsrqFoMKFt5jUH7gJlawdhOs%2F0qTNkFFQWHmxSJwEl6GwlZ8RakrzO1n7iw7J6Iwd5EggiDMvLHioXSFeWjfQMxPG6VA0KBKiORLvW%2BrAqdOh1HmL43C8dNGvw%2BPYd5XliuK4PSspLA4hu1sRQjX4pev8xLj7WSUNxA9XBPfNwURpfpg4KLUyXlj0CkToo9Cv1fV9o%2B0BUu2B9HBYmZvuCE21NdvakotPnTW5VdCObxQL2a27Tvi8XPv4PJ4fpR98XsaOv82czDX2bm9BjqkAQnJZjqIQNGFDLsbLyOb4zWs4b5FRh%2F7VTezbexcFrRbc3p2BE%2F3BhVqa%2Bv6DY5GjdcfBZh6CCLjYYQlC%2BtKg5TwyXURqHzJDP5pRdxLQSJEWx0dZq9ddI00YdiNAbZEcXXSsuJ7WOq5U3siWneKXcekcOKAsoEUV%2FXRlzsvtac9QdO%2BfCelIACJOr4kcyRJmQBjTIciesRxhS0BvMkKwXhcujsn&X-Amz-Signature=5b0f19ec965c7c874b45f0184a6caf9917d2c3f7d28adeaf2dc909536c6d55f7&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667ULFFCEP%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T232248Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCxAg92hf4YARf9NT3rUChCozPGltFQaXdC7WI83QczTgIgKhaWNICNYP3tpGMY757A9SaLkRKu9DQ3aF7asYpvr%2Bgq%2FwMIHxAAGgw2Mzc0MjMxODM4MDUiDAWoiOMIWkL%2FxJ5KNyrcA3ChFEQzfcKtjGpPI6nOEJfi%2Fmn8SaEmoJpjCnojNZ8Gp6IdzXeHR%2FjbMYt%2FRa8B8tnhk%2FrnMatMLMDU%2BPZVqUOC6Uk%2FEREVZuj5oZfEV%2B59gGtkPI%2BGMFT%2F3iGlPchSVjkQkYmlw3EAyh0NC5VxUIdsJ2v7iU4DHZBRPrxcTrD6QDvnvuQG4c2EuPMEnw1RhNiXxNzfcOZ1AsHJLMGhzTWzDVRF%2FTmgjwTj67oUaU1MltDeWqb4YALEC2%2BPghmt7JyGeu5etTUDSdB6haHBs73ga1%2FzTIu0LEAL7NfOx8NE3lwOjSSvowBB6iq2Mz%2Bu7d6hIAwPjvJDEmTfashCOUgEZ2pDSJZgIFD4GtMXuxpNm%2Fa9pbWARs0yVKsQlkr0%2FmL9EPxIPYY628%2Fs6%2BBs4nhnsA4QOI9WT2e%2F5%2FITvkaJW0ru8%2BWogHRTB7a8cyEzxqE5Y7s9%2FEXK0gc%2FE1IJ80ABnAJsABqT96kVeCDu%2B4jUoHB%2F9I2oIuqId2SfC2%2FpQ%2BvzUB5UQWtWoeUZVW6d6nhOat5HGf%2FDaICV3KHBmLTUAnNJJu7qjsSGnvhSnG2fBhmc8LapzCnufVH0hLj3cVwzBP%2FNgyQ%2F%2F9AUhYg1Pikj43K7En8q6JPGiSybMP3Zub0GOqUBihXbEWDq%2FgdxEHa087W0NltdGeQhuoOGsCJfsLnho9wak%2B8qlL5Nke4VNy2SNgBNr%2Fn%2FKitP9b5QJtoecxGAi2OMWI5%2FGK1k0wXEvQGX%2BvC9MPrXYTOLvJSAsDTbrZo9nwrSua4Y%2BrLFPfNSqOAFRh%2Bb9huWoLaGrU%2FtyfPIwZt35l2E3%2B%2Fo6y2W631U1mJQ4AhvgzNNwGCbl0Oxm0rN04iZTiu8&X-Amz-Signature=185fa8db7ca73df7982037a2da1c1a1a378639825efabfb3914f30484635b915&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RQKORB2Q%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T232248Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDl17NR%2BsxPejtb%2BqhBMP3Yod8HO1F6%2B9yag7PJTv4k%2BwIgKlDF%2FYCn6sFCjYu6BRCr9N%2BSKEkmXfeSA5h%2B9xZ3va0q%2FwMIHxAAGgw2Mzc0MjMxODM4MDUiDIbGAlhNARpZzNGxsircA4GWGKimjznS%2BHkPm5IDbeyHi4F31oxyGJd7yjV9MBmlUdR%2FdzOKh2Qqh3VeQBdnjpJ9uBPekyh1RqmQN43iy6QqAI6kErAqc8TV5pZblEpRBtLHAtPBNGdWqsa7BAibgy14b7DMyXBqUE%2BkUwvjdPsduoWgonAEtbFqk9ckf8P1FsOSKBdrN091k2ynHMRWowaY%2FD3iHYk%2BpVnhGyDVb8G0RZ9UD%2BEZc11r7VjsTHXjtfMkyCaKnnYlzssgj8zhZ%2B8H1Vx%2F94J2v8NWJjieLnDsSsFu%2BMqvGSr8pnxhdrxMmv1crPI0S%2FtC765V5Nk4jmf8dnfHJl%2Fs7SqT7QhlNVLSrLZPAXlatqoJE96QXr1p0lBCs2A%2BNXLaXplxjuXY7IRmMSqeKqU7NQweEYHOTAGf4UP%2BZ%2BNYf421slbm8dXSidrGq1COBEyzEOKCe8y2g7qk8mKk5VvJ%2Bgm7yB5wdOMm7liMBJLqD%2B8HUN6%2BGs7u9EPA%2FoHkBBiFoOb6nxczQZNm84iVZBwrGFiQydqsogZjIDS2lsfEiNzcyzwzFKThvX%2F%2B%2FaPbsCXRsCZMSWtIsC7k5XAFLp5NzILQkmmKZQmq72twEc%2BNqTwXOme%2BewWe%2BJK1x4Td9B2QuUzRMPjZub0GOqUBvIrz7KGBj%2FW2JqR86i9yaLA0YXdyGJj%2BftoP2iQtldBPgTiRerZfiI1b0kJXuYhn%2BTejDSlwlktMEreFEJs5zEXsv4%2Fwe41z6q9FgOhyxWYofWix4LSUcPgqUZlZnfSvOVOdoU0zzM%2BvBS8t%2Fdqphi1OvdEljiFdbEYPw0VK%2Fd7qCk01ImcmggDoyz%2By2XbVF73ySu8QjCTnZBqAIe43QeA%2BETd3&X-Amz-Signature=60e9f62738fcff40b2203f7268b843d65955356a0b7794a8a4c16ba2dcb98020&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665ZDPBLH3%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T232247Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD0la6NT8mWfZ4yf8dfu6IgxyVNIv2n1VjQscU1ZOpBXgIhAPRimJc6GoS6AhU9FtKx299Ue3JA8H0RJcfFsXQUeXYuKv8DCB8QABoMNjM3NDIzMTgzODA1IgyYWVJXdxHlulTh%2BW4q3AMrNMP1IygzoyO6JE5QRRimKXC%2Fsafx7UP9xk2kE8bovXReiTt1Eov7VAnPBA6ip4mkXx5Qpa5PM9AOeoLUmmRD3btLQlEICLEflr02jvBNCVeuM1CAZ5anYNu2AQNlMqdWZDIqig8d15l2H6%2BHxXVfqs3%2FkJUrcTxzfLoGcDxxi%2BkkJTr9SipQcosmSNaaJgPO5HNUxDCN3oOoDLxmMg62CMAgUqbuAHaeLCWmePtp%2BXvlKfspOioQJNC0en9rCNRc8m5QDV0xYhyEvFehmizvVOPaCg%2BgTNExg3LLnjdSQw9IagzdAxB0RniNR8FN0lUk0154Fid0YJXqm%2B%2BZhdbHELs6KjK3QZe51gIwYilJozGW479%2FlsrqFoMKFt5jUH7gJlawdhOs%2F0qTNkFFQWHmxSJwEl6GwlZ8RakrzO1n7iw7J6Iwd5EggiDMvLHioXSFeWjfQMxPG6VA0KBKiORLvW%2BrAqdOh1HmL43C8dNGvw%2BPYd5XliuK4PSspLA4hu1sRQjX4pev8xLj7WSUNxA9XBPfNwURpfpg4KLUyXlj0CkToo9Cv1fV9o%2B0BUu2B9HBYmZvuCE21NdvakotPnTW5VdCObxQL2a27Tvi8XPv4PJ4fpR98XsaOv82czDX2bm9BjqkAQnJZjqIQNGFDLsbLyOb4zWs4b5FRh%2F7VTezbexcFrRbc3p2BE%2F3BhVqa%2Bv6DY5GjdcfBZh6CCLjYYQlC%2BtKg5TwyXURqHzJDP5pRdxLQSJEWx0dZq9ddI00YdiNAbZEcXXSsuJ7WOq5U3siWneKXcekcOKAsoEUV%2FXRlzsvtac9QdO%2BfCelIACJOr4kcyRJmQBjTIciesRxhS0BvMkKwXhcujsn&X-Amz-Signature=25362ef2290462f8254f2a070bc7da50be828f5fa8ba68fc4e1698ab01c067dc&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665ZDPBLH3%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T232247Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD0la6NT8mWfZ4yf8dfu6IgxyVNIv2n1VjQscU1ZOpBXgIhAPRimJc6GoS6AhU9FtKx299Ue3JA8H0RJcfFsXQUeXYuKv8DCB8QABoMNjM3NDIzMTgzODA1IgyYWVJXdxHlulTh%2BW4q3AMrNMP1IygzoyO6JE5QRRimKXC%2Fsafx7UP9xk2kE8bovXReiTt1Eov7VAnPBA6ip4mkXx5Qpa5PM9AOeoLUmmRD3btLQlEICLEflr02jvBNCVeuM1CAZ5anYNu2AQNlMqdWZDIqig8d15l2H6%2BHxXVfqs3%2FkJUrcTxzfLoGcDxxi%2BkkJTr9SipQcosmSNaaJgPO5HNUxDCN3oOoDLxmMg62CMAgUqbuAHaeLCWmePtp%2BXvlKfspOioQJNC0en9rCNRc8m5QDV0xYhyEvFehmizvVOPaCg%2BgTNExg3LLnjdSQw9IagzdAxB0RniNR8FN0lUk0154Fid0YJXqm%2B%2BZhdbHELs6KjK3QZe51gIwYilJozGW479%2FlsrqFoMKFt5jUH7gJlawdhOs%2F0qTNkFFQWHmxSJwEl6GwlZ8RakrzO1n7iw7J6Iwd5EggiDMvLHioXSFeWjfQMxPG6VA0KBKiORLvW%2BrAqdOh1HmL43C8dNGvw%2BPYd5XliuK4PSspLA4hu1sRQjX4pev8xLj7WSUNxA9XBPfNwURpfpg4KLUyXlj0CkToo9Cv1fV9o%2B0BUu2B9HBYmZvuCE21NdvakotPnTW5VdCObxQL2a27Tvi8XPv4PJ4fpR98XsaOv82czDX2bm9BjqkAQnJZjqIQNGFDLsbLyOb4zWs4b5FRh%2F7VTezbexcFrRbc3p2BE%2F3BhVqa%2Bv6DY5GjdcfBZh6CCLjYYQlC%2BtKg5TwyXURqHzJDP5pRdxLQSJEWx0dZq9ddI00YdiNAbZEcXXSsuJ7WOq5U3siWneKXcekcOKAsoEUV%2FXRlzsvtac9QdO%2BfCelIACJOr4kcyRJmQBjTIciesRxhS0BvMkKwXhcujsn&X-Amz-Signature=7d970bb14ca52074362b24d6e9d9ee38b85508c7a4abc045961f27b93bd41726&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665ZDPBLH3%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T232247Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD0la6NT8mWfZ4yf8dfu6IgxyVNIv2n1VjQscU1ZOpBXgIhAPRimJc6GoS6AhU9FtKx299Ue3JA8H0RJcfFsXQUeXYuKv8DCB8QABoMNjM3NDIzMTgzODA1IgyYWVJXdxHlulTh%2BW4q3AMrNMP1IygzoyO6JE5QRRimKXC%2Fsafx7UP9xk2kE8bovXReiTt1Eov7VAnPBA6ip4mkXx5Qpa5PM9AOeoLUmmRD3btLQlEICLEflr02jvBNCVeuM1CAZ5anYNu2AQNlMqdWZDIqig8d15l2H6%2BHxXVfqs3%2FkJUrcTxzfLoGcDxxi%2BkkJTr9SipQcosmSNaaJgPO5HNUxDCN3oOoDLxmMg62CMAgUqbuAHaeLCWmePtp%2BXvlKfspOioQJNC0en9rCNRc8m5QDV0xYhyEvFehmizvVOPaCg%2BgTNExg3LLnjdSQw9IagzdAxB0RniNR8FN0lUk0154Fid0YJXqm%2B%2BZhdbHELs6KjK3QZe51gIwYilJozGW479%2FlsrqFoMKFt5jUH7gJlawdhOs%2F0qTNkFFQWHmxSJwEl6GwlZ8RakrzO1n7iw7J6Iwd5EggiDMvLHioXSFeWjfQMxPG6VA0KBKiORLvW%2BrAqdOh1HmL43C8dNGvw%2BPYd5XliuK4PSspLA4hu1sRQjX4pev8xLj7WSUNxA9XBPfNwURpfpg4KLUyXlj0CkToo9Cv1fV9o%2B0BUu2B9HBYmZvuCE21NdvakotPnTW5VdCObxQL2a27Tvi8XPv4PJ4fpR98XsaOv82czDX2bm9BjqkAQnJZjqIQNGFDLsbLyOb4zWs4b5FRh%2F7VTezbexcFrRbc3p2BE%2F3BhVqa%2Bv6DY5GjdcfBZh6CCLjYYQlC%2BtKg5TwyXURqHzJDP5pRdxLQSJEWx0dZq9ddI00YdiNAbZEcXXSsuJ7WOq5U3siWneKXcekcOKAsoEUV%2FXRlzsvtac9QdO%2BfCelIACJOr4kcyRJmQBjTIciesRxhS0BvMkKwXhcujsn&X-Amz-Signature=3cce65f32e09a701a03a16448767f5f7a04d74673a101446802e993a972e11f7&X-Amz-SignedHeaders=host&x-id=GetObject)


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

