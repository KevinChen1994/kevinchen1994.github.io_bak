---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB46655AUGOTA%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250219T222152Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEIb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIAd%2FaCiqw3LbEjLg%\
  2FlfWhKC6DaaB3i7vupHos%2BimDXpwAiEAz1ucfvJO9e1NQ72zLq56jR%2BoAk%2BrOsVR2q78XW\
  a7OlwqiAQIr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGKLM49BT\
  v1DpRHMLircA3Zw9GS9Rdz%2BHqKWaxtBsQ%2FB77Xm%2BvEiR6dagKWxzzjEWI6qS6%2Bb7V%2Fk\
  xpq9Ob0vfaFopWgyKkxCB8haEKyA85lSK6mWF2285UO2S8iPYxdrmi7KF6M0R38Qk9QYoJ3XRlQEG\
  XAMcr%2Bh8VVHWjY7gAnk%2BWaesoyU8wx4Qn2ByezyA9BRn1z9B%2Fgl3NYADzy6OKCRdg1084%2\
  FcTy5J7%2FNhGzAo2IYr%2B3Y%2FSTRR0Sk3FGVgkmZVATYpHPexoOUGYxoYfFPIhVJXzbciUWd6Y\
  EJkMlowWCX9sBKJwsKbqsLu1aIieP3FDYFM6nsq20eD8jRvXHStu12LGtTF3E5UlH3k4TZ8qYVcSE\
  z0x2j%2FGOvQjfKYqX4ldnaaZNa%2BMHj%2F5QU7DwpDFpUAfu5b1MHikvxBbwvvcY08WFDTZOvcj\
  gsmuF3nFFEceyzSej76ouMJOBvKUqpEwVeXHFz14SFqUCt7JicJeay2YG5qPLizAz86z38mkJKPSq\
  qIWu5o0CLN5KuqWVhZULz%2Bi9jTIWb88mLO9u2Dn%2BW3632ibLUg19yWCiIogdjmWNTaIrf94KB\
  Fm7%2F5FmAX1Eai7KzR%2BdeCEZNBsNxkM1U4GGVdsjkBHCS2MEZdwkRTu12AIJcW8DLhMLmu2b0G\
  OqUBhfRVo86g7zmtyOadjFW%2Frh69T3ALao8JCiEgT66LV48xTJQP3WswTPQRg4wgvo0lyQRm13J\
  8yFof2H1PDQ2A6WEwsZ2HD354XHqdbTUKtHnzPfQh6rHKH%2Bfb3pLm%2BKzTWnYoCC4shbAZMh%2\
  BzMKFRRea27p79T4E8GTE2jawcRbVAbGbr6VhPhCk5zbxL5%2FBLkixxuSxFgM341lckYEmbGtBv9\
  3MO&X-Amz-Signature=9ffcb50fd3e1c271b513e56d0a6c06f8313b87a69228e33ee68b38c11\
  66950e9&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB46656GKGQ55%2F20250219%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250219T222018Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEIb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIQDNrs7CWe3SFR2j1TuOfebO8DGEHZi9apUlEJVunCmssAIgV984LX2mBXdjIHAJQOC8NI\
        YbiQZdsizUF8N1vU9bcvgqiAQIr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc\
        0MjMxODM4MDUiDOhtfea1iBJ%2FbhtLBircA2qkwC6fiOL%2BauqS7lvrbct9jjpUDUdPs2\
        Yf9Q4rj0QneENzqvQsSamqybsfd4qb6BQnAo%2BzlnTrF2F8lPBfUBVgc3baLVjKKLQPytw\
        rB6G0YE5bfJkLtV11T5EFps0t8vG1VLgT1gxelqBDKPZPqFotMLv0yAAkoJo5ZPqc%2BEB7\
        U%2FgayOgXYub1gIT4qy8qmj5x4%2BtEu9zI3BUvwoANSU2tOEh8yeiaijj5%2B0fcMw5QV\
        LwobOqPzW2S5%2B4XgTNd89Ld%2FS3SWlSshHDxl4ljG5H1G5D83bo%2FaVARbBm%2Focz4\
        Dcg4BbIQPMKSxdNLlAJ3Zfj3v7mGFwwuTeczdtngyeakfmG8HCiiUmAFkKMwm5YdmdfFu8g\
        bm7NuajjkT%2Fp1ldhSlMRroDvby7oZtfth3o%2FY%2BLuW8N%2Fv1wsbOzP1IG%2BphdIG\
        Rpey%2FPGszw5B7WVwfvzFan21PIyIddw8%2Fo6s8zLuH0K0YPgJb8xlYwInj68mLamZyk0\
        U6hVbWA%2Bj3X5NfmY1kaxJIP5oqJjOSD1mtkWXRoLVMurxcZQ8N83E9xv%2FRxh8zOfJIb\
        EA8vDeso%2F02DS3LtpVhJ4Z0mVq0jQ0L1PnDEbs2VQlWvpzDaKnUyWc8F2u2ZPx8tQWP%2\
        BfKMKGu2b0GOqUB59jb%2F3E3SfYm9Bcqn7rgVMkiimapGR%2BgHjk4wRmG1tJHkMJVkpm9\
        fkFUnOR7clfQBHfu%2BWMHAeJc%2BVJp0JuR7Iaw9sg1hTCgIIX3Zyg1OSj0mW7ZFTP%2BS\
        p3ExUo2Mc8SVQcJY4K%2FKmQy5Y%2BcLNkQ%2Fp1%2FG%2BtgtUPH%2BwQruaH3Qanoqjg6\
        v%2BT7F4dknaR42tRwh5dTtSb1IQw5%2BJa4%2BfpaPDuyp4fw&X-Amz-Signature=ec4f\
        586e256b9b162dd659d66fda2c11f32c299a96d6f9432861fda3b8fcdb58&X-Amz-Sign\
        edHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-19T23:20:18.326Z"
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
UPDATE_TIME: "2025-02-19T22:21:59.176Z"
EXPIRY_TIME: "2025-02-19T23:21:48.814Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665KAETHWA%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T222149Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEQLx5NSqkGp9o%2Br8UVkevva1UIqhh0N%2FUZh%2FPzZPNvzAiApx%2F5wt0%2FYO7M1OlU9RKE%2FWrY3bYpex3F7KGeiqvmtciqIBAiv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMabwM7iBry%2FISRZxbKtwDNwfq%2BdJ42zj%2BEdx3wCS1UcGgLgTmidIaotS5F0co7oC7eHxYVe8r9bgXtxqJVC3seRE8k0wIJuyu9Rnknf0PiA9W%2FpBdCWqWAWtm3PRytfYjyJBkIaPbY0jdvhpIZ6AxPShTlMJ8IU%2BJ0B50jssuf317nDNDB4Wx1EE9Ud%2BKE4oZSnPr5c9Dxon5%2B%2B2r1m3cbmeI0S0GLxf1qB6p66Y6lWaoHyk6dbigqIxkIW7QVemnmrkQlWS%2FpYwKJy6HWMahdQgxj6o8EJl%2Bg%2FaCuGD4r5ofsTVJrZT36t6cWyzdpQ86uIBMQ0huVQkSxbVjY3R1EQl1hJhjNy%2F0EwJ7%2Fe6A0TUxbQz4dx%2FkulZeicfwM9slQtIi8glvGOl0odO3fSQDQC%2B%2FcegjFi3JliJpTTTjcotEDzRnaTn6bArmrpE%2B2hH%2BrtQ9n8VvqQu2z%2FyBGldtex9THsLeqWgG%2BMluI2mWi9H7zMy2HR9F%2FyvIT8rQGmUWR%2BuqamgM3VcW%2FzarYZyTnfXu7gYdjnBzp0lGCCLtT9VlUgM5vItAi%2FLHDobIhCNKB%2FAy9HT5OIMTJo5AACv%2FxZ7XiEARNuTVU%2F2vPIawfait%2FQFcUFhnSx6fPtzZbgw4kYB0vdjwpXR5wlQw7K3ZvQY6pgHmeb6iFqlMx02dTzH3YeCKxm%2FO8veQex%2FJSKY4RAV7NJsg7kYnz6S9nevEqwwOZuAQ%2FfWqVwnLfAybZPesMnNSbYWqksdsjTOnOVQYFA%2FVN66QK4BRCZmR8C8uB457Gbo2gwD0msYwT3eWcKHk9CvFzu0PT7GG%2B94AXyaLCS%2BN7pJm62Jr5F3bPxkGE4U%2FYICnWh6ZjJ1JlGJ%2BwGTj3jHJazLODyn8&X-Amz-Signature=c002084bc2b4f4c29f0442c4a33e358bd3dab19b77fd99f48aad9001aa1448ff&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665KAETHWA%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T222149Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEQLx5NSqkGp9o%2Br8UVkevva1UIqhh0N%2FUZh%2FPzZPNvzAiApx%2F5wt0%2FYO7M1OlU9RKE%2FWrY3bYpex3F7KGeiqvmtciqIBAiv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMabwM7iBry%2FISRZxbKtwDNwfq%2BdJ42zj%2BEdx3wCS1UcGgLgTmidIaotS5F0co7oC7eHxYVe8r9bgXtxqJVC3seRE8k0wIJuyu9Rnknf0PiA9W%2FpBdCWqWAWtm3PRytfYjyJBkIaPbY0jdvhpIZ6AxPShTlMJ8IU%2BJ0B50jssuf317nDNDB4Wx1EE9Ud%2BKE4oZSnPr5c9Dxon5%2B%2B2r1m3cbmeI0S0GLxf1qB6p66Y6lWaoHyk6dbigqIxkIW7QVemnmrkQlWS%2FpYwKJy6HWMahdQgxj6o8EJl%2Bg%2FaCuGD4r5ofsTVJrZT36t6cWyzdpQ86uIBMQ0huVQkSxbVjY3R1EQl1hJhjNy%2F0EwJ7%2Fe6A0TUxbQz4dx%2FkulZeicfwM9slQtIi8glvGOl0odO3fSQDQC%2B%2FcegjFi3JliJpTTTjcotEDzRnaTn6bArmrpE%2B2hH%2BrtQ9n8VvqQu2z%2FyBGldtex9THsLeqWgG%2BMluI2mWi9H7zMy2HR9F%2FyvIT8rQGmUWR%2BuqamgM3VcW%2FzarYZyTnfXu7gYdjnBzp0lGCCLtT9VlUgM5vItAi%2FLHDobIhCNKB%2FAy9HT5OIMTJo5AACv%2FxZ7XiEARNuTVU%2F2vPIawfait%2FQFcUFhnSx6fPtzZbgw4kYB0vdjwpXR5wlQw7K3ZvQY6pgHmeb6iFqlMx02dTzH3YeCKxm%2FO8veQex%2FJSKY4RAV7NJsg7kYnz6S9nevEqwwOZuAQ%2FfWqVwnLfAybZPesMnNSbYWqksdsjTOnOVQYFA%2FVN66QK4BRCZmR8C8uB457Gbo2gwD0msYwT3eWcKHk9CvFzu0PT7GG%2B94AXyaLCS%2BN7pJm62Jr5F3bPxkGE4U%2FYICnWh6ZjJ1JlGJ%2BwGTj3jHJazLODyn8&X-Amz-Signature=1ef9327548eb5d6e37942978b4fef9fef6f6b4060853dbbcccf887e5dc3ad415&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665KAETHWA%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T222149Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEQLx5NSqkGp9o%2Br8UVkevva1UIqhh0N%2FUZh%2FPzZPNvzAiApx%2F5wt0%2FYO7M1OlU9RKE%2FWrY3bYpex3F7KGeiqvmtciqIBAiv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMabwM7iBry%2FISRZxbKtwDNwfq%2BdJ42zj%2BEdx3wCS1UcGgLgTmidIaotS5F0co7oC7eHxYVe8r9bgXtxqJVC3seRE8k0wIJuyu9Rnknf0PiA9W%2FpBdCWqWAWtm3PRytfYjyJBkIaPbY0jdvhpIZ6AxPShTlMJ8IU%2BJ0B50jssuf317nDNDB4Wx1EE9Ud%2BKE4oZSnPr5c9Dxon5%2B%2B2r1m3cbmeI0S0GLxf1qB6p66Y6lWaoHyk6dbigqIxkIW7QVemnmrkQlWS%2FpYwKJy6HWMahdQgxj6o8EJl%2Bg%2FaCuGD4r5ofsTVJrZT36t6cWyzdpQ86uIBMQ0huVQkSxbVjY3R1EQl1hJhjNy%2F0EwJ7%2Fe6A0TUxbQz4dx%2FkulZeicfwM9slQtIi8glvGOl0odO3fSQDQC%2B%2FcegjFi3JliJpTTTjcotEDzRnaTn6bArmrpE%2B2hH%2BrtQ9n8VvqQu2z%2FyBGldtex9THsLeqWgG%2BMluI2mWi9H7zMy2HR9F%2FyvIT8rQGmUWR%2BuqamgM3VcW%2FzarYZyTnfXu7gYdjnBzp0lGCCLtT9VlUgM5vItAi%2FLHDobIhCNKB%2FAy9HT5OIMTJo5AACv%2FxZ7XiEARNuTVU%2F2vPIawfait%2FQFcUFhnSx6fPtzZbgw4kYB0vdjwpXR5wlQw7K3ZvQY6pgHmeb6iFqlMx02dTzH3YeCKxm%2FO8veQex%2FJSKY4RAV7NJsg7kYnz6S9nevEqwwOZuAQ%2FfWqVwnLfAybZPesMnNSbYWqksdsjTOnOVQYFA%2FVN66QK4BRCZmR8C8uB457Gbo2gwD0msYwT3eWcKHk9CvFzu0PT7GG%2B94AXyaLCS%2BN7pJm62Jr5F3bPxkGE4U%2FYICnWh6ZjJ1JlGJ%2BwGTj3jHJazLODyn8&X-Amz-Signature=0d21fad23c013a201acc8541b2312794cfcf9a96f29de71f803b347232578bae&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665KAETHWA%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T222149Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEQLx5NSqkGp9o%2Br8UVkevva1UIqhh0N%2FUZh%2FPzZPNvzAiApx%2F5wt0%2FYO7M1OlU9RKE%2FWrY3bYpex3F7KGeiqvmtciqIBAiv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMabwM7iBry%2FISRZxbKtwDNwfq%2BdJ42zj%2BEdx3wCS1UcGgLgTmidIaotS5F0co7oC7eHxYVe8r9bgXtxqJVC3seRE8k0wIJuyu9Rnknf0PiA9W%2FpBdCWqWAWtm3PRytfYjyJBkIaPbY0jdvhpIZ6AxPShTlMJ8IU%2BJ0B50jssuf317nDNDB4Wx1EE9Ud%2BKE4oZSnPr5c9Dxon5%2B%2B2r1m3cbmeI0S0GLxf1qB6p66Y6lWaoHyk6dbigqIxkIW7QVemnmrkQlWS%2FpYwKJy6HWMahdQgxj6o8EJl%2Bg%2FaCuGD4r5ofsTVJrZT36t6cWyzdpQ86uIBMQ0huVQkSxbVjY3R1EQl1hJhjNy%2F0EwJ7%2Fe6A0TUxbQz4dx%2FkulZeicfwM9slQtIi8glvGOl0odO3fSQDQC%2B%2FcegjFi3JliJpTTTjcotEDzRnaTn6bArmrpE%2B2hH%2BrtQ9n8VvqQu2z%2FyBGldtex9THsLeqWgG%2BMluI2mWi9H7zMy2HR9F%2FyvIT8rQGmUWR%2BuqamgM3VcW%2FzarYZyTnfXu7gYdjnBzp0lGCCLtT9VlUgM5vItAi%2FLHDobIhCNKB%2FAy9HT5OIMTJo5AACv%2FxZ7XiEARNuTVU%2F2vPIawfait%2FQFcUFhnSx6fPtzZbgw4kYB0vdjwpXR5wlQw7K3ZvQY6pgHmeb6iFqlMx02dTzH3YeCKxm%2FO8veQex%2FJSKY4RAV7NJsg7kYnz6S9nevEqwwOZuAQ%2FfWqVwnLfAybZPesMnNSbYWqksdsjTOnOVQYFA%2FVN66QK4BRCZmR8C8uB457Gbo2gwD0msYwT3eWcKHk9CvFzu0PT7GG%2B94AXyaLCS%2BN7pJm62Jr5F3bPxkGE4U%2FYICnWh6ZjJ1JlGJ%2BwGTj3jHJazLODyn8&X-Amz-Signature=1c2800c5f559f2ad77e9a8fc231ee823ab827bfeee8b0971444879db9a1530da&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665KAETHWA%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T222149Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEQLx5NSqkGp9o%2Br8UVkevva1UIqhh0N%2FUZh%2FPzZPNvzAiApx%2F5wt0%2FYO7M1OlU9RKE%2FWrY3bYpex3F7KGeiqvmtciqIBAiv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMabwM7iBry%2FISRZxbKtwDNwfq%2BdJ42zj%2BEdx3wCS1UcGgLgTmidIaotS5F0co7oC7eHxYVe8r9bgXtxqJVC3seRE8k0wIJuyu9Rnknf0PiA9W%2FpBdCWqWAWtm3PRytfYjyJBkIaPbY0jdvhpIZ6AxPShTlMJ8IU%2BJ0B50jssuf317nDNDB4Wx1EE9Ud%2BKE4oZSnPr5c9Dxon5%2B%2B2r1m3cbmeI0S0GLxf1qB6p66Y6lWaoHyk6dbigqIxkIW7QVemnmrkQlWS%2FpYwKJy6HWMahdQgxj6o8EJl%2Bg%2FaCuGD4r5ofsTVJrZT36t6cWyzdpQ86uIBMQ0huVQkSxbVjY3R1EQl1hJhjNy%2F0EwJ7%2Fe6A0TUxbQz4dx%2FkulZeicfwM9slQtIi8glvGOl0odO3fSQDQC%2B%2FcegjFi3JliJpTTTjcotEDzRnaTn6bArmrpE%2B2hH%2BrtQ9n8VvqQu2z%2FyBGldtex9THsLeqWgG%2BMluI2mWi9H7zMy2HR9F%2FyvIT8rQGmUWR%2BuqamgM3VcW%2FzarYZyTnfXu7gYdjnBzp0lGCCLtT9VlUgM5vItAi%2FLHDobIhCNKB%2FAy9HT5OIMTJo5AACv%2FxZ7XiEARNuTVU%2F2vPIawfait%2FQFcUFhnSx6fPtzZbgw4kYB0vdjwpXR5wlQw7K3ZvQY6pgHmeb6iFqlMx02dTzH3YeCKxm%2FO8veQex%2FJSKY4RAV7NJsg7kYnz6S9nevEqwwOZuAQ%2FfWqVwnLfAybZPesMnNSbYWqksdsjTOnOVQYFA%2FVN66QK4BRCZmR8C8uB457Gbo2gwD0msYwT3eWcKHk9CvFzu0PT7GG%2B94AXyaLCS%2BN7pJm62Jr5F3bPxkGE4U%2FYICnWh6ZjJ1JlGJ%2BwGTj3jHJazLODyn8&X-Amz-Signature=f95f50e6e8a1ff631c2dcefeceb8fb2151732a81cbe9436940a8ad80cd454815&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46652ELRLG5%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T222149Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBq1obiCAs4ShlzXnSWLE%2BsopJfL6OGv8%2Fs6QiklqnJDAiEAnDTo81k1z05PRsG4CyYw4Yhui4G0O0svNZcBQsSxnHkqiAQIr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOFOyhj%2FHEj44GQbASrcA2fHtz2pHi7bD9cYPBkNZpHiuuR2a6Le%2FE2CwaeoaIO9yNAgw2GZ8mPeElBht54u8fPvjLoEtQjorZCWP4Pxwz26gX6cSRKPRLpUBqSNh9A1YM645OKpD0UfIgVPKwIIyexwCG6MKSxrw8%2FJvyBSU5NOwDS0AJaunD2xqROXV5FKfMc9FwFHFsgJfw6Vy1ysEO9uobbuQvYAiHbnqf3zhPztkG7utVXzpaac6jekGoSsaOeWK5C6JBCkUVuN95GKlNcglPFe8GF7v9gd5t0%2F8XWCh3f2CIO8NC5H1g%2FmAuiOdsceGZQ9ZDXqntFaYsfMty8QfukFFbuGm0e731gKemiWWAYkEcf2G3eERJpx9zjxWIX7gFdti1ok85lBFURiMc1OQYHEG5NhN6FdSJ4a8uCnks3qD6sE3tOetskBHMVmWELzIxr%2B9O73KuLZQK9kn6k9UxAM0YBwT9jyJVbJbTCrXrojRiasiQFCtP9ZGeya6uq3RhEuo%2Fc7zVS16KHx1oYhJUYD7ernjBrJ03A9CSl1927l1PttwLhedDPnRMNsJYze6xvW4oItuDoYDS5A2bIiQYnupCSdJLXD9eThm7a%2F2BNCMxvEysCJvqA6y2kJ5RdX7BdqUhingLhVMNet2b0GOqUBsKEKAY6RnEnvDJHe3hE6l2lou1ZOP1prgBq%2F%2BwoTIwo5N5z7FdNmii3oQH%2B36F6GoDKMMcZ7oNXPm1XNr%2FV%2F%2F6tmfVLUZMnKR56Swt995NQ2g%2BubiaxD5ZXP%2Bi6GjflqyPBEhb%2Fzy7KRKLv72VasUeMqKIz8zVuzXjw1ISSwC%2FzXcdsx7EWapKCO5rFMw0nu06BI84GG73zSZCYXy1VyKM9ejCks&X-Amz-Signature=6887c2b2ace57ddb5188522aaa746c42ff8adcb0624c4dd2fb183fee9c7aef68&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667XLAXI6Y%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T222150Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCWxX5uAP3k%2F3SIrtQFdys59huXFSldou9pMhoWdpS3JQIhAOxh6UIZa9t4fPhbRi2YAQXDZqFZrYayALza2Md%2BlDxSKogECK%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwpB9qba2nf6eUWTiEq3APfyZsgRCLup5XVYQyNetLyMHYs0dBpwWfbc05wcC3mrhHxvgOVdZ0wHXjNiW%2FYS4%2FbsZswZB4iqig4EibjnH7Vz6tfuqFq4wdyfOIeEQpzENdZOO8pUGkdGeeGSbEoIRwHuMu%2FAJxvH3kNcwi1WQvEakQyfBYfEEFL4YT8MmIXEZsHRaGiSIuM1%2BtTH%2F1cyt5%2FO9uC5PZvTq626udHEuo7GO8fydgNHW1y6hMgDehBf5nulH7m2BPQ9iPPxSZpU9FWO0Va%2BDaub83cWjgp20yf1lZiP4PsaAp2tJPzvPRC%2BVF25Me%2BBQYGv4xuvCjWRmyFVxzPb9OVWC5doyEAJCi%2Fg6ABjoJR%2FY0Rx9S4XqPIBOHdNnh8xAZ9frYADmHay%2BpU3JMfCUCGmwgFc5cS%2FTTPeJF2cAx3J5AXw%2BvpGO5RbOCDQ3sZaB1BmvSx4uyM%2Fyn6iQZd13hbNWqtmpiLaiIQSQ9ZCIz1Dz3PPituPCiWalKjoLRG4nAerij%2FvKpi8A%2BV9adQh5hX2BePwvEecpMn7k8M7WegaORFj9xRmIlc4ZHNq%2BmRH0fpT%2Fqs6MmFFSoG9eyq9uCh9LbF7qG6hzBlDybaDY6ASaSk5cOgFy57knzhTfURHq9dey8A%2FTC%2Frdm9BjqkAY7hcB3vHMvWC1l%2F8GSDNQxG2axQ16%2FueilezEpy7VYl0DN4nU3vvt0W5YaPswta8zLunHe9oGc65VAHyHIO%2Bok0GTC3RmqYg8m%2Fa9doeLeGRFNjbNPQi4NwM7gaTic420sooN%2BqIMClXGvy0GeOy6n9oXXrP6r11i0ZixwgBAkLXM8TrbVp6%2BmD%2FQFjCg4MZbBOPX6ELgA8k7IaLWowMCdSk%2F%2BE&X-Amz-Signature=d7e084872bddc3e7be7ca6018b0386a9fc5f966192403f181828a9195d56f9de&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665KAETHWA%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T222149Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEQLx5NSqkGp9o%2Br8UVkevva1UIqhh0N%2FUZh%2FPzZPNvzAiApx%2F5wt0%2FYO7M1OlU9RKE%2FWrY3bYpex3F7KGeiqvmtciqIBAiv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMabwM7iBry%2FISRZxbKtwDNwfq%2BdJ42zj%2BEdx3wCS1UcGgLgTmidIaotS5F0co7oC7eHxYVe8r9bgXtxqJVC3seRE8k0wIJuyu9Rnknf0PiA9W%2FpBdCWqWAWtm3PRytfYjyJBkIaPbY0jdvhpIZ6AxPShTlMJ8IU%2BJ0B50jssuf317nDNDB4Wx1EE9Ud%2BKE4oZSnPr5c9Dxon5%2B%2B2r1m3cbmeI0S0GLxf1qB6p66Y6lWaoHyk6dbigqIxkIW7QVemnmrkQlWS%2FpYwKJy6HWMahdQgxj6o8EJl%2Bg%2FaCuGD4r5ofsTVJrZT36t6cWyzdpQ86uIBMQ0huVQkSxbVjY3R1EQl1hJhjNy%2F0EwJ7%2Fe6A0TUxbQz4dx%2FkulZeicfwM9slQtIi8glvGOl0odO3fSQDQC%2B%2FcegjFi3JliJpTTTjcotEDzRnaTn6bArmrpE%2B2hH%2BrtQ9n8VvqQu2z%2FyBGldtex9THsLeqWgG%2BMluI2mWi9H7zMy2HR9F%2FyvIT8rQGmUWR%2BuqamgM3VcW%2FzarYZyTnfXu7gYdjnBzp0lGCCLtT9VlUgM5vItAi%2FLHDobIhCNKB%2FAy9HT5OIMTJo5AACv%2FxZ7XiEARNuTVU%2F2vPIawfait%2FQFcUFhnSx6fPtzZbgw4kYB0vdjwpXR5wlQw7K3ZvQY6pgHmeb6iFqlMx02dTzH3YeCKxm%2FO8veQex%2FJSKY4RAV7NJsg7kYnz6S9nevEqwwOZuAQ%2FfWqVwnLfAybZPesMnNSbYWqksdsjTOnOVQYFA%2FVN66QK4BRCZmR8C8uB457Gbo2gwD0msYwT3eWcKHk9CvFzu0PT7GG%2B94AXyaLCS%2BN7pJm62Jr5F3bPxkGE4U%2FYICnWh6ZjJ1JlGJ%2BwGTj3jHJazLODyn8&X-Amz-Signature=7d38829a132d400c3a6c76163e9bf58c94dae3a92dac9877ca1bb51feafb3bff&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665KAETHWA%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T222149Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEQLx5NSqkGp9o%2Br8UVkevva1UIqhh0N%2FUZh%2FPzZPNvzAiApx%2F5wt0%2FYO7M1OlU9RKE%2FWrY3bYpex3F7KGeiqvmtciqIBAiv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMabwM7iBry%2FISRZxbKtwDNwfq%2BdJ42zj%2BEdx3wCS1UcGgLgTmidIaotS5F0co7oC7eHxYVe8r9bgXtxqJVC3seRE8k0wIJuyu9Rnknf0PiA9W%2FpBdCWqWAWtm3PRytfYjyJBkIaPbY0jdvhpIZ6AxPShTlMJ8IU%2BJ0B50jssuf317nDNDB4Wx1EE9Ud%2BKE4oZSnPr5c9Dxon5%2B%2B2r1m3cbmeI0S0GLxf1qB6p66Y6lWaoHyk6dbigqIxkIW7QVemnmrkQlWS%2FpYwKJy6HWMahdQgxj6o8EJl%2Bg%2FaCuGD4r5ofsTVJrZT36t6cWyzdpQ86uIBMQ0huVQkSxbVjY3R1EQl1hJhjNy%2F0EwJ7%2Fe6A0TUxbQz4dx%2FkulZeicfwM9slQtIi8glvGOl0odO3fSQDQC%2B%2FcegjFi3JliJpTTTjcotEDzRnaTn6bArmrpE%2B2hH%2BrtQ9n8VvqQu2z%2FyBGldtex9THsLeqWgG%2BMluI2mWi9H7zMy2HR9F%2FyvIT8rQGmUWR%2BuqamgM3VcW%2FzarYZyTnfXu7gYdjnBzp0lGCCLtT9VlUgM5vItAi%2FLHDobIhCNKB%2FAy9HT5OIMTJo5AACv%2FxZ7XiEARNuTVU%2F2vPIawfait%2FQFcUFhnSx6fPtzZbgw4kYB0vdjwpXR5wlQw7K3ZvQY6pgHmeb6iFqlMx02dTzH3YeCKxm%2FO8veQex%2FJSKY4RAV7NJsg7kYnz6S9nevEqwwOZuAQ%2FfWqVwnLfAybZPesMnNSbYWqksdsjTOnOVQYFA%2FVN66QK4BRCZmR8C8uB457Gbo2gwD0msYwT3eWcKHk9CvFzu0PT7GG%2B94AXyaLCS%2BN7pJm62Jr5F3bPxkGE4U%2FYICnWh6ZjJ1JlGJ%2BwGTj3jHJazLODyn8&X-Amz-Signature=6671f75a561ca3a5813d83ebf7f1a2325638a949a241ed6b1239f94c48a7f94d&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665KAETHWA%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T222149Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEQLx5NSqkGp9o%2Br8UVkevva1UIqhh0N%2FUZh%2FPzZPNvzAiApx%2F5wt0%2FYO7M1OlU9RKE%2FWrY3bYpex3F7KGeiqvmtciqIBAiv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMabwM7iBry%2FISRZxbKtwDNwfq%2BdJ42zj%2BEdx3wCS1UcGgLgTmidIaotS5F0co7oC7eHxYVe8r9bgXtxqJVC3seRE8k0wIJuyu9Rnknf0PiA9W%2FpBdCWqWAWtm3PRytfYjyJBkIaPbY0jdvhpIZ6AxPShTlMJ8IU%2BJ0B50jssuf317nDNDB4Wx1EE9Ud%2BKE4oZSnPr5c9Dxon5%2B%2B2r1m3cbmeI0S0GLxf1qB6p66Y6lWaoHyk6dbigqIxkIW7QVemnmrkQlWS%2FpYwKJy6HWMahdQgxj6o8EJl%2Bg%2FaCuGD4r5ofsTVJrZT36t6cWyzdpQ86uIBMQ0huVQkSxbVjY3R1EQl1hJhjNy%2F0EwJ7%2Fe6A0TUxbQz4dx%2FkulZeicfwM9slQtIi8glvGOl0odO3fSQDQC%2B%2FcegjFi3JliJpTTTjcotEDzRnaTn6bArmrpE%2B2hH%2BrtQ9n8VvqQu2z%2FyBGldtex9THsLeqWgG%2BMluI2mWi9H7zMy2HR9F%2FyvIT8rQGmUWR%2BuqamgM3VcW%2FzarYZyTnfXu7gYdjnBzp0lGCCLtT9VlUgM5vItAi%2FLHDobIhCNKB%2FAy9HT5OIMTJo5AACv%2FxZ7XiEARNuTVU%2F2vPIawfait%2FQFcUFhnSx6fPtzZbgw4kYB0vdjwpXR5wlQw7K3ZvQY6pgHmeb6iFqlMx02dTzH3YeCKxm%2FO8veQex%2FJSKY4RAV7NJsg7kYnz6S9nevEqwwOZuAQ%2FfWqVwnLfAybZPesMnNSbYWqksdsjTOnOVQYFA%2FVN66QK4BRCZmR8C8uB457Gbo2gwD0msYwT3eWcKHk9CvFzu0PT7GG%2B94AXyaLCS%2BN7pJm62Jr5F3bPxkGE4U%2FYICnWh6ZjJ1JlGJ%2BwGTj3jHJazLODyn8&X-Amz-Signature=97ef017da1bd9e7a84045d4bc276897a482721ed0b2a3dd7267d2ead3eca10c7&X-Amz-SignedHeaders=host&x-id=GetObject)


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

