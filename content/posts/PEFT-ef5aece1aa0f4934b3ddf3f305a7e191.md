---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466VYJWKXH2%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250221T132921Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEK3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCFxno11eRkQThBPJE\
  jFdbNzS6kRv3VlT0z0Oy66W9dwQIgYZ5C10ny0QOcyNZ5%2FSCQ0yiUug9Tb0QuJYn7QaR0bbgqiA\
  QI1v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDBq1L0UovU7Kn59OyCr\
  cA%2FEh49H2dviLwEQH2e2T50QBaW%2Bt1wxYmD6KP8uZ9pvxJ3aZPORJYg%2F1P1%2BYSpnrCmLN\
  4PBWkAKZaSk2ao3bj%2BT%2Fv2MTX0Q7DlD5nLHOeUog%2Bz1G2rH1izlIbB15IfxYsOWWpg9%2Bb\
  53gcU7r4wowvZXEuiJuge6Rp3fS39XxL8xa4DGm4zpRJgAo4fYOPctnzRa%2FSlAqDInCxodYAp%2\
  BFElYteZK6RIvWtYFe0ecedvzyEHegCEem6cyTRSuXreIjuP0suLZzoFU%2Fu1w%2FK4TIAaHiUFn\
  w%2Bi7zjeTLGhtNRMx73QQDuTwWfB1ov2KwFhKk8FCKFBqToqiK6e0Sf5a6V1FyAUyjC8klvb2Gb2\
  QZu5qv5V1CCleCfunLF0PfOETBkVWtrhNCwPXFFSCRU6BZgLQxn%2FSspLtpVb5TmcAl4bTz1U5ww\
  s8fsLqg%2FEjrV0GXz6gcLDA0G6D2ZSzpNKp6K9ksp%2FAnRwUSd4z%2Be3jAcbsQc7nE%2Fl3HsU\
  9xN9pSLY65sUIPOxZ%2BiEPCsnXvlQ70lp7QHmpyhIEFIgWeEn4bm1ZuP8mNXVfucik6Oj%2FcDpN\
  8uav17x9%2BXBO47ZzgsvPwALDNENSHYam%2F3fYy%2FJaKrY0nHvG5NKG1k%2FlCmyKHMKDl4b0G\
  OqUBR6q8E9qNXAPk4o1URUjzeH7tdyvLSWf6XpToAGRvALIpjShJhNctoKL5PxdvnJONvb4KH3ypk\
  SSZ%2FMqfLnqxW7wsbBYzUAwyOR9JF%2BxpvcLIA9igMOPYE9jeTojUIpqsvO9S9uc2awm9LiEc2j\
  %2BHBU5iOMSI%2FAFq3d3hiXIkzBMy8GeymF0tv7BhB2i1g2zxxVSL5iHm2J43T4vnhns864h9RUk\
  6&X-Amz-Signature=d39b53e5b83a7ff91e9ef47ba756177bec73424b26612897bc6d91b64e8\
  8c496&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466WIC27RCP%2F20250221%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250221T132656Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEK3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIFvci1pw6x9OEqNrBDWBE7EVb9gqa4BAxkK8%2BQF4osuYAiEAv%2F2nQE68m2LKtdxlLW\
        ZL1K8e9vJlebjF3RZxncEVDYEqiAQI1v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2M\
        zc0MjMxODM4MDUiDLQtZt8POGVWlRs57ircAzft%2Ba9%2FEGwskm3xP9A9XjLaTxosYr%2\
        FbJTu7McU38yUcZ5nEQEuRmgRx%2BfzOrl7A9HTh%2FoOdh%2BJwpqfAg6dKE6tNwt3USEy\
        A4m77stNqO%2BStgW414vGT2LF%2Fm%2BtgQ%2FbEaZrlgzR0LBsFEsViFNxVPFdRxjGNJK\
        gGARTPnZTqQtYAj9L6t2W2jUwBugY4vJbvwVQ6mu%2Fk7PSRj0xH1Lam23wKT1oyHroGKQK\
        uEDz6MQVgWb4uGg%2F6hwUqFf%2F8g1ynvEZCE7wFR5obm0kE0G5yTSU8VURyTvPvIB2hQx\
        uN79d6XJFBZhee8COOB9CGO9lLncz88kozAanXzhb2Z8%2BYtEJbAbp6FjXM9MUIGK1rDji\
        hfkDWJywE%2F6kknyIkbKvtRpwj5PJz8rtfGLAY5RZZleQ7VEjvlD2mKfNxQ7mBK5xHqCB%\
        2BqbNX9U2%2BNCVDeAybSU0LhdbehVanJNjb4KA0rZEpmQB2wp7D9I4KJkMLArcxnQATTxB\
        L2PuE%2BLzBX9NhKsKt2Y6iDlgok2qGvhBYwaMaCqHxHMClWXqDPgzB0Dh3O1gq0BoFQa%2\
        BjDodh0ldHXWnfBmh8NRsjZhyxGb7ClHTjhj%2Bd1Ry38Zz%2Bo7oadu3qLmMgjk51nkdQm\
        cl%2BMKvm4b0GOqUB7ht3PUxGBCyhk9DdsJczvRkNH6buSek7n66CWh2H0KjGOVh3Qa5KOt\
        ag4XuWQhhLtn413SFIhIlVvx6JV3AJ2jFqUZ5T4s4BjfkbcvQfFGZKo9sz8zwXi68mOvn%2\
        Fs%2BrHVPfX5%2FFxg9bLSGKiszZP2gnSs0xVYdoDmpvaRmSBSbW00cCa1gAvwovybWGb%2\
        B3mRtX7i24KPs4lcWjVGfWN365oREsxG&X-Amz-Signature=83556980dcedba662499da\
        626b603f8db2832fb034a180ebf4953699cc1588c8&X-Amz-SignedHeaders=host&x-i\
        d=GetObject"
      expiry_time: "2025-02-21T14:26:56.796Z"
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
UPDATE_TIME: "2025-02-21T13:29:32.641Z"
EXPIRY_TIME: "2025-02-21T14:29:17.992Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663DNSBHGM%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T132918Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEK3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAyEiZG%2FgOagcMKAGIYZ2oYniT1MX%2F652GK0e%2FLF5iIpAiBNAFAB2X7n7Xr%2F%2Fh2hfq21B71OHgC9louw0vtRXj%2FrDyqIBAjW%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMm1VyWkRKo6PH8R2KKtwDJ%2FJcMGettviNc92WRGUoy6ORqUDcCLIL45Wvu4K55JQMCPEDYqG6%2FLYgR2enHJDbcU5kxvzQEMQ87mWXtfItHxsof9eYWH8a1vfY448OqB9rsAMbjKwcsvwxp6DkuLgXBsMEmgBNSDpSVcSR7FKo%2BqHC9jJkyx1%2BXrO7xnpOv7ofXPNWc0c56x%2BjpuXg50tzO9Y1F0ac6reZj0FYdbI3lA5vvWGmLmZcTBLbGzrUnyJUtl92P3hSQogklpmXGsrETZ1GlRRbEkPO4O3y1haknDbRhjhxZdepJxS3qRUJgQgZq6ROQjcU%2BMX4FkxLvgASjCJUEi6nVBmehYhdLgMqTiAF1BiwZWZrNL2VipozdN9R42Q6X0nvapuCFWSm1BqDO%2B5MZWex7xB2X9WQl%2Bmpt1qyI%2Fq977xcsfbt3VdK3DSbQ%2FyfcB62eFaLgB0ESG6m9vO4OJduziFt6ixgIIKaVMiDv%2FPG34YdmEufbmaEieBOf4fCoVKz5ANG%2FNcuUT3EdGPURLDak9T1IGeYjsdSgegg0E1ozz6dBAN2k34NGxaS3djmAaG%2FBXK6TwSv54vA7fOyH0rXXBmJKdYKQgszUXyaPlKOKnjL%2BR%2B9Rkbr9PYjXmzFWwRZeH7oxEswjuXhvQY6pgHrm%2B63y64fVppKu7xanWrmq5LAgY7GblTkwqjgOPEZwgRQ1MVA1eJbmHoe3%2F5J%2BUF4iQw3RcACUGYipMRGhgu3IiVDcpo6bVcWSOrrKS6BQoyNZKEIjqJx0tIPb0VhW0xqTXrR5L1n1MLbN4ebYczVs3FhPOZDdjg4dtOBFPy%2B5F3Q7QIjQwtTX3axhaLeJAibPfVVoE6hAh9yLLdyXkiNRX1Db9IQ&X-Amz-Signature=62980cfa682cdb7e3fcedcf9759c320777a3f9493b951fcdd6199789250c3a38&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663DNSBHGM%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T132918Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEK3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAyEiZG%2FgOagcMKAGIYZ2oYniT1MX%2F652GK0e%2FLF5iIpAiBNAFAB2X7n7Xr%2F%2Fh2hfq21B71OHgC9louw0vtRXj%2FrDyqIBAjW%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMm1VyWkRKo6PH8R2KKtwDJ%2FJcMGettviNc92WRGUoy6ORqUDcCLIL45Wvu4K55JQMCPEDYqG6%2FLYgR2enHJDbcU5kxvzQEMQ87mWXtfItHxsof9eYWH8a1vfY448OqB9rsAMbjKwcsvwxp6DkuLgXBsMEmgBNSDpSVcSR7FKo%2BqHC9jJkyx1%2BXrO7xnpOv7ofXPNWc0c56x%2BjpuXg50tzO9Y1F0ac6reZj0FYdbI3lA5vvWGmLmZcTBLbGzrUnyJUtl92P3hSQogklpmXGsrETZ1GlRRbEkPO4O3y1haknDbRhjhxZdepJxS3qRUJgQgZq6ROQjcU%2BMX4FkxLvgASjCJUEi6nVBmehYhdLgMqTiAF1BiwZWZrNL2VipozdN9R42Q6X0nvapuCFWSm1BqDO%2B5MZWex7xB2X9WQl%2Bmpt1qyI%2Fq977xcsfbt3VdK3DSbQ%2FyfcB62eFaLgB0ESG6m9vO4OJduziFt6ixgIIKaVMiDv%2FPG34YdmEufbmaEieBOf4fCoVKz5ANG%2FNcuUT3EdGPURLDak9T1IGeYjsdSgegg0E1ozz6dBAN2k34NGxaS3djmAaG%2FBXK6TwSv54vA7fOyH0rXXBmJKdYKQgszUXyaPlKOKnjL%2BR%2B9Rkbr9PYjXmzFWwRZeH7oxEswjuXhvQY6pgHrm%2B63y64fVppKu7xanWrmq5LAgY7GblTkwqjgOPEZwgRQ1MVA1eJbmHoe3%2F5J%2BUF4iQw3RcACUGYipMRGhgu3IiVDcpo6bVcWSOrrKS6BQoyNZKEIjqJx0tIPb0VhW0xqTXrR5L1n1MLbN4ebYczVs3FhPOZDdjg4dtOBFPy%2B5F3Q7QIjQwtTX3axhaLeJAibPfVVoE6hAh9yLLdyXkiNRX1Db9IQ&X-Amz-Signature=139f6e893a1bb9a013632c1c309c38df9ee9d17e8bc802b1de5b379ff28237b8&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663DNSBHGM%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T132918Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEK3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAyEiZG%2FgOagcMKAGIYZ2oYniT1MX%2F652GK0e%2FLF5iIpAiBNAFAB2X7n7Xr%2F%2Fh2hfq21B71OHgC9louw0vtRXj%2FrDyqIBAjW%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMm1VyWkRKo6PH8R2KKtwDJ%2FJcMGettviNc92WRGUoy6ORqUDcCLIL45Wvu4K55JQMCPEDYqG6%2FLYgR2enHJDbcU5kxvzQEMQ87mWXtfItHxsof9eYWH8a1vfY448OqB9rsAMbjKwcsvwxp6DkuLgXBsMEmgBNSDpSVcSR7FKo%2BqHC9jJkyx1%2BXrO7xnpOv7ofXPNWc0c56x%2BjpuXg50tzO9Y1F0ac6reZj0FYdbI3lA5vvWGmLmZcTBLbGzrUnyJUtl92P3hSQogklpmXGsrETZ1GlRRbEkPO4O3y1haknDbRhjhxZdepJxS3qRUJgQgZq6ROQjcU%2BMX4FkxLvgASjCJUEi6nVBmehYhdLgMqTiAF1BiwZWZrNL2VipozdN9R42Q6X0nvapuCFWSm1BqDO%2B5MZWex7xB2X9WQl%2Bmpt1qyI%2Fq977xcsfbt3VdK3DSbQ%2FyfcB62eFaLgB0ESG6m9vO4OJduziFt6ixgIIKaVMiDv%2FPG34YdmEufbmaEieBOf4fCoVKz5ANG%2FNcuUT3EdGPURLDak9T1IGeYjsdSgegg0E1ozz6dBAN2k34NGxaS3djmAaG%2FBXK6TwSv54vA7fOyH0rXXBmJKdYKQgszUXyaPlKOKnjL%2BR%2B9Rkbr9PYjXmzFWwRZeH7oxEswjuXhvQY6pgHrm%2B63y64fVppKu7xanWrmq5LAgY7GblTkwqjgOPEZwgRQ1MVA1eJbmHoe3%2F5J%2BUF4iQw3RcACUGYipMRGhgu3IiVDcpo6bVcWSOrrKS6BQoyNZKEIjqJx0tIPb0VhW0xqTXrR5L1n1MLbN4ebYczVs3FhPOZDdjg4dtOBFPy%2B5F3Q7QIjQwtTX3axhaLeJAibPfVVoE6hAh9yLLdyXkiNRX1Db9IQ&X-Amz-Signature=4a51d908156796f7ada2af064789777bd28619629a5091e2b8070115cbab707e&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663DNSBHGM%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T132918Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEK3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAyEiZG%2FgOagcMKAGIYZ2oYniT1MX%2F652GK0e%2FLF5iIpAiBNAFAB2X7n7Xr%2F%2Fh2hfq21B71OHgC9louw0vtRXj%2FrDyqIBAjW%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMm1VyWkRKo6PH8R2KKtwDJ%2FJcMGettviNc92WRGUoy6ORqUDcCLIL45Wvu4K55JQMCPEDYqG6%2FLYgR2enHJDbcU5kxvzQEMQ87mWXtfItHxsof9eYWH8a1vfY448OqB9rsAMbjKwcsvwxp6DkuLgXBsMEmgBNSDpSVcSR7FKo%2BqHC9jJkyx1%2BXrO7xnpOv7ofXPNWc0c56x%2BjpuXg50tzO9Y1F0ac6reZj0FYdbI3lA5vvWGmLmZcTBLbGzrUnyJUtl92P3hSQogklpmXGsrETZ1GlRRbEkPO4O3y1haknDbRhjhxZdepJxS3qRUJgQgZq6ROQjcU%2BMX4FkxLvgASjCJUEi6nVBmehYhdLgMqTiAF1BiwZWZrNL2VipozdN9R42Q6X0nvapuCFWSm1BqDO%2B5MZWex7xB2X9WQl%2Bmpt1qyI%2Fq977xcsfbt3VdK3DSbQ%2FyfcB62eFaLgB0ESG6m9vO4OJduziFt6ixgIIKaVMiDv%2FPG34YdmEufbmaEieBOf4fCoVKz5ANG%2FNcuUT3EdGPURLDak9T1IGeYjsdSgegg0E1ozz6dBAN2k34NGxaS3djmAaG%2FBXK6TwSv54vA7fOyH0rXXBmJKdYKQgszUXyaPlKOKnjL%2BR%2B9Rkbr9PYjXmzFWwRZeH7oxEswjuXhvQY6pgHrm%2B63y64fVppKu7xanWrmq5LAgY7GblTkwqjgOPEZwgRQ1MVA1eJbmHoe3%2F5J%2BUF4iQw3RcACUGYipMRGhgu3IiVDcpo6bVcWSOrrKS6BQoyNZKEIjqJx0tIPb0VhW0xqTXrR5L1n1MLbN4ebYczVs3FhPOZDdjg4dtOBFPy%2B5F3Q7QIjQwtTX3axhaLeJAibPfVVoE6hAh9yLLdyXkiNRX1Db9IQ&X-Amz-Signature=d6601da69c7484a37b51da6e583aeafac96236591ccd32465a2c511ad6a810c2&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663DNSBHGM%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T132918Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEK3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAyEiZG%2FgOagcMKAGIYZ2oYniT1MX%2F652GK0e%2FLF5iIpAiBNAFAB2X7n7Xr%2F%2Fh2hfq21B71OHgC9louw0vtRXj%2FrDyqIBAjW%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMm1VyWkRKo6PH8R2KKtwDJ%2FJcMGettviNc92WRGUoy6ORqUDcCLIL45Wvu4K55JQMCPEDYqG6%2FLYgR2enHJDbcU5kxvzQEMQ87mWXtfItHxsof9eYWH8a1vfY448OqB9rsAMbjKwcsvwxp6DkuLgXBsMEmgBNSDpSVcSR7FKo%2BqHC9jJkyx1%2BXrO7xnpOv7ofXPNWc0c56x%2BjpuXg50tzO9Y1F0ac6reZj0FYdbI3lA5vvWGmLmZcTBLbGzrUnyJUtl92P3hSQogklpmXGsrETZ1GlRRbEkPO4O3y1haknDbRhjhxZdepJxS3qRUJgQgZq6ROQjcU%2BMX4FkxLvgASjCJUEi6nVBmehYhdLgMqTiAF1BiwZWZrNL2VipozdN9R42Q6X0nvapuCFWSm1BqDO%2B5MZWex7xB2X9WQl%2Bmpt1qyI%2Fq977xcsfbt3VdK3DSbQ%2FyfcB62eFaLgB0ESG6m9vO4OJduziFt6ixgIIKaVMiDv%2FPG34YdmEufbmaEieBOf4fCoVKz5ANG%2FNcuUT3EdGPURLDak9T1IGeYjsdSgegg0E1ozz6dBAN2k34NGxaS3djmAaG%2FBXK6TwSv54vA7fOyH0rXXBmJKdYKQgszUXyaPlKOKnjL%2BR%2B9Rkbr9PYjXmzFWwRZeH7oxEswjuXhvQY6pgHrm%2B63y64fVppKu7xanWrmq5LAgY7GblTkwqjgOPEZwgRQ1MVA1eJbmHoe3%2F5J%2BUF4iQw3RcACUGYipMRGhgu3IiVDcpo6bVcWSOrrKS6BQoyNZKEIjqJx0tIPb0VhW0xqTXrR5L1n1MLbN4ebYczVs3FhPOZDdjg4dtOBFPy%2B5F3Q7QIjQwtTX3axhaLeJAibPfVVoE6hAh9yLLdyXkiNRX1Db9IQ&X-Amz-Signature=239794281d2dc687057c6554b2df7006e239c25cea588e186ed1358e0767ec8a&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466W7FDPIF2%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T132919Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEK3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIChIYuGm0nhAXG0XdJIJI197e8r%2FLoZoih%2FWQYkCH534AiEA6%2BOckSvDVn4NnQHqTTucicV55S4BdDY%2FpN5EDMDmww0qiAQI1v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOIgQn7dC9FV0gg1jircA3oJ9IRjbZXQQ%2BhLd%2FalFv%2BsG1kvGLQnXt4qn4bKLAnlfao8G7TR%2Bx9s%2BRtuxFdBPrFd3Pkv5N%2B1e7azt1HPZK4rvf%2BiuS0F5ba%2FCtR6PrAGkBY0z6z848Lo7MqTbcCXzA2eWXemY01soWHYdgKsrwdkMlT3EsFp4F%2BeWS%2Fr9rGbpbcm8bEpKw3zHMEVvMRFM9344sq%2By4QpG1POMI8tVgamB%2Fu8iPaUhebYllB7vhFqopCBUklhrR3M5E7ZIFLDsQ62D9%2FflWu3c%2B%2FrZI9q4ppiUPV3RatWhPd9D8FozR6RFI5Skw%2B39FMWJDusEkMnqRZflFrG14YIjR5nv8cADefRu7tWc2VZ14K8OBbxOjJxy%2BY1C1uStIEUFXw3XUjZUY%2BhGYhXY5v5nao1npp%2BbAVmzUXHUfolo%2BLB5TDXtrlJQ6diBZL8wpclDsq2f7UMa9hWhEqy1ncOWi%2BUaKKnEyiUigqQ5UHl28SpZkzVQiLMeKSBKbhWSn7FovdM8wHogN62Yc9R74ytXmsVb90v%2FzalhH%2FoNayempm60vwzDoNtvmWC5iAObIoIuLrd9avbT33fNe0XPQ2WoKJyapC0SBleYqjg8Xo4aQiTsXFvQ94K8Ai%2FzkexoUA5uYPRMPrl4b0GOqUBygFNmydcB8jMpAWfhxkx6F%2Bc0C7Yw7Y4W8bNUGSI25CmDBkINfeEYfraPgLkLgBP%2Bbn58Y8res2MBbi1W7ENXI060yZx%2FfilKSLFANeNrVyDJq7kMlGumcC5qAxdjaRNXKzTeijK9KQzSEH8AFCJVgEn1Re4Ss0W26ThaKaqMUI5cUUyPgMsH8swmMJyq%2Buz7Bj2uDT7f6EmmkVAgVeXt175t5w3&X-Amz-Signature=f3c2357281f928b7bec2a82ec25489fdf8050589af4d820162e246c769304785&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UBKV2QLF%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T132920Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEK3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDprQYCfV0dNk%2BW7iva93aZq2WxQgmEKsr9L%2FFZ6kc3XgIhANqnJE4omXexqfZHGdRzBIeVY4VjpsYM1008858bwW5WKogECNb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igz3o9%2F%2FEwF5%2FHNdzk0q3AMvd9OCqk943VYsGiL7GD%2Bz3TbZWySYEsF38CVVov6WYMlmKQrp25C1vkBre9vQYGpHabP0PpzakwGMY3rx5kXiwnd6EaKhoH0DGWWvgHabGJ8i%2BXHItwGLtxwTSOaVcqXb%2Fbdu0X2nSTwoS65ozJlnTEZF0HFMmRhST4J0X%2F1F3VrlOH6xrmIqcJUt3lgA8ch8KSNYa5k9dDSTb%2BPiLski3gQ6b0Xu4GriLhQSol91gT1kh17WADVRbSDnTHvcPyHxwDFGB0jI9gmF3ppSk8FaD2AcfERlWhkzMWE3NIGGHTXZgozW4SP1r24KTGNFutqR4lhJSlySc94CntHUNJslsZ7tx%2BEZ9qm35aP92zzSkJIRFxKGvH2ILExnwDPAOR4dw3rN0gw5jq2qHB4uudFS6fXfb6fomyfvrUmGxVfB3i4%2BIuNmxMggmBRRe42dvmci%2BKIwGmZACrM4Pb66NlITnAsjci4fnEDjd2dT3qS6454R9LWk7uFAUlvMlNQaq3J6bVDRH72HtIPTmDsVTFijWd0wguuz7oAKGjoAPt88ZBB%2Fl%2FYuVq8U7BwyVZK%2Blq%2FWbLYrAsGZA4UOe7%2B5aa3NznsX%2FwjlzVhx73ssyvanR1q%2FNVtiuh4knX5HeTCW5eG9BjqkAR9DZfRKdMmt2LPe9cCzA2qwFTB%2BGnMd%2B3aZLcsGLe%2F5KuGlk5cMF26F8JdkCCpfeVwROcR4uYiiERYr29ljMzrgzKPl6QoqYK94ILQaLL5NCBnP%2BCV6dWgb%2B3J77p2EiAejX29rhbTwXFDwVl3orrQBU6mvXK%2Bh7KwlAmVZrUMfGpqAp8CRK635s09YnX%2FgLwgjz6hWZUjRHxXBQzfjw3UyMoCE&X-Amz-Signature=b043a9df254cba3145d7290ae7c4c6d285be2e26ef983251a7f66aab53fd5d77&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663DNSBHGM%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T132918Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEK3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAyEiZG%2FgOagcMKAGIYZ2oYniT1MX%2F652GK0e%2FLF5iIpAiBNAFAB2X7n7Xr%2F%2Fh2hfq21B71OHgC9louw0vtRXj%2FrDyqIBAjW%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMm1VyWkRKo6PH8R2KKtwDJ%2FJcMGettviNc92WRGUoy6ORqUDcCLIL45Wvu4K55JQMCPEDYqG6%2FLYgR2enHJDbcU5kxvzQEMQ87mWXtfItHxsof9eYWH8a1vfY448OqB9rsAMbjKwcsvwxp6DkuLgXBsMEmgBNSDpSVcSR7FKo%2BqHC9jJkyx1%2BXrO7xnpOv7ofXPNWc0c56x%2BjpuXg50tzO9Y1F0ac6reZj0FYdbI3lA5vvWGmLmZcTBLbGzrUnyJUtl92P3hSQogklpmXGsrETZ1GlRRbEkPO4O3y1haknDbRhjhxZdepJxS3qRUJgQgZq6ROQjcU%2BMX4FkxLvgASjCJUEi6nVBmehYhdLgMqTiAF1BiwZWZrNL2VipozdN9R42Q6X0nvapuCFWSm1BqDO%2B5MZWex7xB2X9WQl%2Bmpt1qyI%2Fq977xcsfbt3VdK3DSbQ%2FyfcB62eFaLgB0ESG6m9vO4OJduziFt6ixgIIKaVMiDv%2FPG34YdmEufbmaEieBOf4fCoVKz5ANG%2FNcuUT3EdGPURLDak9T1IGeYjsdSgegg0E1ozz6dBAN2k34NGxaS3djmAaG%2FBXK6TwSv54vA7fOyH0rXXBmJKdYKQgszUXyaPlKOKnjL%2BR%2B9Rkbr9PYjXmzFWwRZeH7oxEswjuXhvQY6pgHrm%2B63y64fVppKu7xanWrmq5LAgY7GblTkwqjgOPEZwgRQ1MVA1eJbmHoe3%2F5J%2BUF4iQw3RcACUGYipMRGhgu3IiVDcpo6bVcWSOrrKS6BQoyNZKEIjqJx0tIPb0VhW0xqTXrR5L1n1MLbN4ebYczVs3FhPOZDdjg4dtOBFPy%2B5F3Q7QIjQwtTX3axhaLeJAibPfVVoE6hAh9yLLdyXkiNRX1Db9IQ&X-Amz-Signature=ac3c974bd530f8d5e36bf50a2e51eaab1762f86872f1f3e71e865d6369ec6403&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663DNSBHGM%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T132918Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEK3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAyEiZG%2FgOagcMKAGIYZ2oYniT1MX%2F652GK0e%2FLF5iIpAiBNAFAB2X7n7Xr%2F%2Fh2hfq21B71OHgC9louw0vtRXj%2FrDyqIBAjW%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMm1VyWkRKo6PH8R2KKtwDJ%2FJcMGettviNc92WRGUoy6ORqUDcCLIL45Wvu4K55JQMCPEDYqG6%2FLYgR2enHJDbcU5kxvzQEMQ87mWXtfItHxsof9eYWH8a1vfY448OqB9rsAMbjKwcsvwxp6DkuLgXBsMEmgBNSDpSVcSR7FKo%2BqHC9jJkyx1%2BXrO7xnpOv7ofXPNWc0c56x%2BjpuXg50tzO9Y1F0ac6reZj0FYdbI3lA5vvWGmLmZcTBLbGzrUnyJUtl92P3hSQogklpmXGsrETZ1GlRRbEkPO4O3y1haknDbRhjhxZdepJxS3qRUJgQgZq6ROQjcU%2BMX4FkxLvgASjCJUEi6nVBmehYhdLgMqTiAF1BiwZWZrNL2VipozdN9R42Q6X0nvapuCFWSm1BqDO%2B5MZWex7xB2X9WQl%2Bmpt1qyI%2Fq977xcsfbt3VdK3DSbQ%2FyfcB62eFaLgB0ESG6m9vO4OJduziFt6ixgIIKaVMiDv%2FPG34YdmEufbmaEieBOf4fCoVKz5ANG%2FNcuUT3EdGPURLDak9T1IGeYjsdSgegg0E1ozz6dBAN2k34NGxaS3djmAaG%2FBXK6TwSv54vA7fOyH0rXXBmJKdYKQgszUXyaPlKOKnjL%2BR%2B9Rkbr9PYjXmzFWwRZeH7oxEswjuXhvQY6pgHrm%2B63y64fVppKu7xanWrmq5LAgY7GblTkwqjgOPEZwgRQ1MVA1eJbmHoe3%2F5J%2BUF4iQw3RcACUGYipMRGhgu3IiVDcpo6bVcWSOrrKS6BQoyNZKEIjqJx0tIPb0VhW0xqTXrR5L1n1MLbN4ebYczVs3FhPOZDdjg4dtOBFPy%2B5F3Q7QIjQwtTX3axhaLeJAibPfVVoE6hAh9yLLdyXkiNRX1Db9IQ&X-Amz-Signature=98bfcad83d8bb39851fbb03985c80f13aba05ee4f24390d035de48e74dfaa660&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663DNSBHGM%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T132918Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEK3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAyEiZG%2FgOagcMKAGIYZ2oYniT1MX%2F652GK0e%2FLF5iIpAiBNAFAB2X7n7Xr%2F%2Fh2hfq21B71OHgC9louw0vtRXj%2FrDyqIBAjW%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMm1VyWkRKo6PH8R2KKtwDJ%2FJcMGettviNc92WRGUoy6ORqUDcCLIL45Wvu4K55JQMCPEDYqG6%2FLYgR2enHJDbcU5kxvzQEMQ87mWXtfItHxsof9eYWH8a1vfY448OqB9rsAMbjKwcsvwxp6DkuLgXBsMEmgBNSDpSVcSR7FKo%2BqHC9jJkyx1%2BXrO7xnpOv7ofXPNWc0c56x%2BjpuXg50tzO9Y1F0ac6reZj0FYdbI3lA5vvWGmLmZcTBLbGzrUnyJUtl92P3hSQogklpmXGsrETZ1GlRRbEkPO4O3y1haknDbRhjhxZdepJxS3qRUJgQgZq6ROQjcU%2BMX4FkxLvgASjCJUEi6nVBmehYhdLgMqTiAF1BiwZWZrNL2VipozdN9R42Q6X0nvapuCFWSm1BqDO%2B5MZWex7xB2X9WQl%2Bmpt1qyI%2Fq977xcsfbt3VdK3DSbQ%2FyfcB62eFaLgB0ESG6m9vO4OJduziFt6ixgIIKaVMiDv%2FPG34YdmEufbmaEieBOf4fCoVKz5ANG%2FNcuUT3EdGPURLDak9T1IGeYjsdSgegg0E1ozz6dBAN2k34NGxaS3djmAaG%2FBXK6TwSv54vA7fOyH0rXXBmJKdYKQgszUXyaPlKOKnjL%2BR%2B9Rkbr9PYjXmzFWwRZeH7oxEswjuXhvQY6pgHrm%2B63y64fVppKu7xanWrmq5LAgY7GblTkwqjgOPEZwgRQ1MVA1eJbmHoe3%2F5J%2BUF4iQw3RcACUGYipMRGhgu3IiVDcpo6bVcWSOrrKS6BQoyNZKEIjqJx0tIPb0VhW0xqTXrR5L1n1MLbN4ebYczVs3FhPOZDdjg4dtOBFPy%2B5F3Q7QIjQwtTX3axhaLeJAibPfVVoE6hAh9yLLdyXkiNRX1Db9IQ&X-Amz-Signature=b7feb6d7bb6b5407e7766163dbcec46ab2b5ca980aac669c625840ce4c43d017&X-Amz-SignedHeaders=host&x-id=GetObject)


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

