---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4663GYQ6XME%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250130T124414Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEJ3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDnyr7hlh4UaJuljbA\
  a5W%2BMSO5yv544UALl5goJptTqlAIgFt5jfC6HzTZgSsxSy0vQr2MvOYEx7DYX13%2BZHFV0hCEq\
  iAQIpf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGKwOdr3Jnc0b%2BC\
  r5ircAxwoE%2FO9Rx4ceJolECda6YaoCY9N3wLl4UQju5t41QPS1g%2F9cD3BIGkBiuhWBhnNTLbk\
  azL68kgG%2FBkxZ9RKtxRfRZlVmeSMtshyJV5f%2FxyY8AOMGWweUm%2FvoZDSbsRlsLOxDm1FaHb\
  EDsSsmw2RrsUFsLA9pkhffT0XlBFGTRLZw6ze4A%2F4sbveNYt9fhXZ%2BSJJakOfddYHBAoCKexa\
  hQt2tppWqDqjNDHcRBKoOEhlHx9vHoVOZblQNxzcztYnl4JT67tEPCJM4rKY8USX%2BQL16LmuJeq\
  xT4LNM1Mb9IViWH3mrBjKFb4nQ7iYjInNvF%2FgoRAAC9%2F6DxxA%2BjHffoSGpEciAzdrXtqxZG\
  EIASpB%2FgmCdZN6wo33tGp6D7RFEDD4za6%2FHJ4pu7jrFKMjlMHkRZ4dYazXSYPzMLST0t1ELTu\
  2AebuYkASS4dIWC%2FZjonjn%2FRI2iAbwIWAUGT0fO63vBqof7C5goLXcacWCGix0euC8M0JQpEl\
  p4qQzr%2Bx0seNI7byQ%2Bep4UxPztROpK1KECDq7ms%2FBfGIw7qHQn%2Fs3nSfB0dwdL72a6B8L\
  DXz99qaJ%2FJLGIXkfqJizq4JsrPuh9DobScdz4RMvlQsbocJYQznBO5j1lFLGqL%2BMKng7bwGOq\
  UB5T07kctXmeoAalvD7ruAKRQMPbRECu7B%2FEE3SRdw1N1y4BGjvdoUwg59eldqV6yBErp3r4gHd\
  i29RkDLeLfxZ6Kcste4fD%2FehT0W8eZWjKKVyjh05Npxgpeu62UmQHyosb7IpxZPjldoAKDy%2B9\
  jh2rwzm6LjW62FHEEqsULSjGbtlbAHNUTXp5HQHNZ1iOCBkF9qWvGzx5jajhXVQBwV%2BB0Cd32g&\
  X-Amz-Signature=c359a678e6de76a25a7c6cb27503a8e2fa3b4c43ca56f5cfc3434c88fffe6\
  8c9&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4663BKJTGOV%2F20250130%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250130T124241Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEJ3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIQCOb2hOvKkKZZgcJlTGyzchD1l0EIoOyiu1BEjLAzQA0QIgGaejPuFG06T6UDwhGLvzLi\
        IKe4Ytdee5tZGzzpbs358qiAQIpv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0M\
        jMxODM4MDUiDAg0ecuVCRp8GqffNCrcA4ybDJls2oqtEA09FvlJsAqvIh4uZIJ9XtL0cV6s\
        2Ca4ATwKmkq5GnXHcLoUURYwKC5Q6B8dFEq7ql3GxmBJeDqo5ECfWdFxjjbcYIMMwuKUK9o\
        HxXtL4LSa8AIHAeiSfwfDabOBmnAWzR3ONuhIxPnz5oID3MueORy9zR1A3iYTCxA54EGo84\
        oIy9dilWM9PPBYQacxJ1NZx%2Fd0ysmPUvTQKRVGmr%2FmhdqMtZNqs8aZ98bzQNXpwXbVU\
        shf%2B0LXp92IQxeI7%2BBigfv%2FrmKaJpIltDYoVoNGun8NVg%2FMacL6b0ALq8oRFRT3\
        Un6brbPw7Z7g9NjWghl%2BwhfidP3hC%2Fmp%2FfwrqpOGgWBV0NJ7W6WXdGTwKxXIUcJeQ\
        obs%2Byyyb9yURv1%2Fpq%2BgnwxXDjpxDPjmWJNY9%2F1mHEpXeMmZntdn3R9kuK5Id%2B\
        LIhI%2FR0xKf%2FFUil6QRkQvdBpijJPRg6IoCm0Z0lOPSYWX%2B2OMU2WzXrnJ7hqvGJ2%\
        2FhUBr4CkgJWE5OJ7D3x2Zcao58oOnxdJYAw4Vnix7CLEhaSTgqIrXflHPeZ5HxC7E6u1y8\
        SyQ6veJvj%2BGUh1HUC3dRUfjlUBszeh6ctT%2B0mPn1fpzTy%2B2D9x0OW2hHdfBUsCyCM\
        JPh7bwGOqUBV4y%2F7W4EDMZbnkLUXjvX5XbtmRtPMwF9lmMFR8W%2BbFzaFO8LHW%2FzSN\
        wEss%2FMCr5Mapcd9ciezztZPLU1TtoyY9qqnbPB9mj14nt5ysdVC4tWKyDOmdB1BjVtPjb\
        XPF9aFHZeRHFKfxxGCB7yKhYYT7t8rreGDUUv7nxqOqwFq9rJekV7jBFv%2BBO%2FSY5kt3\
        VIWNfADpCZ3T1wuZ4uX9uengSXvJBa&X-Amz-Signature=1a2b667048eb2834ca1de542\
        2330687690d6903bfbe0681961e214202e71d496&X-Amz-SignedHeaders=host&x-id=\
        GetObject"
      expiry_time: "2025-01-30T13:42:41.477Z"
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
UPDATE_TIME: "2025-01-30T12:44:22.383Z"
EXPIRY_TIME: "2025-01-30T13:44:11.391Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466S3Y23BKZ%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T124411Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJ3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD3i0AAAf4fHZyB7bXSPqDFXcZuvvSKFcpWM6cLiqSe4AIhANTTsG79CLwDOn7Chumg66m7TAXAfuVWbJq%2B4G2UDaC0KogECKb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyBOw7pfHS5nEmSkbUq3ANR9osLf6Xk846eCglR4LLpdjLR%2FqCnsjk24%2BKLPs25EksV3swS9NoNJjskQEr%2Bk%2BgtH7VIQ6b8QADaqkWoHQ1y43twteciehu8Yh43KVcwsZvUrsnk%2Fd%2BAOChZDgr0csGvIfanMixIhtgexxWrRjHaNd0%2FC7a5od4PLHR%2B3YAScLBdwrpwqIF%2F3vx0MELy%2BeQpaxIcGngB9XL%2FfDhVSooodbQ2WGXTbDV8taeYQglqvJ4GArWl5GFXo6g47rriNdej7iJJYcH8xfNpbOfBT5Pxolev6SJ2yM8j4LHkUSCN9NJMALUyfP%2FtnE%2B23YEde1cTSjfuDBKy0sdgVRMDDOg8I3r7v0EjDzjhoi6DSUB7cxeidZZz7vPzQclWIJHlfjeqFXoLBVq%2FSrbIzCfZYnUs8Wjvgz4naIi2RyoY0T3SjRNO5yRd3MQ4Uo5jinaHH7cxFAWhhz0Xq17Hf5z77vc7KTR6dSHP0eh7Iy0NgQzsP46FP22VmZYah4mMBjI58lLJHyTnfhUGhN8ACRha5Dt9roixRRTQKoqbG3L1%2B4g%2F5hvFChf%2B1AocFIHkJOBenPcIe%2FUeMkTQ5UI%2BbvQlQPnAs2bQVs%2FucIkUxDaJFlvof9pW3LXsnLT13w9YljDQ3%2B28BjqkAZX%2BCpNyEK4rw%2F7a3dfHBRWDhfOFI1%2BePGc1XiDHENVSjSWEMnseSlo5xjUuthPxZ5VzvDvzmuFoEW0GQV0YwjXDFJyZWXHmkBjBjVxM4bVOpVQpiUxHAlP43Okc6qK0XqZ%2BBiFwNkSMzTwZ6wHWnLww2LUHChsfgyBXYM120%2FrI3IfdcebdzIa1G6DJmAK9Fp4b%2BrKVS9eaqAmsC2lfEYKqQ7tW&X-Amz-Signature=902e2727d87bb72f1367e616e8110536aac6d953b7c5634d72390e59359215da&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466S3Y23BKZ%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T124411Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJ3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD3i0AAAf4fHZyB7bXSPqDFXcZuvvSKFcpWM6cLiqSe4AIhANTTsG79CLwDOn7Chumg66m7TAXAfuVWbJq%2B4G2UDaC0KogECKb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyBOw7pfHS5nEmSkbUq3ANR9osLf6Xk846eCglR4LLpdjLR%2FqCnsjk24%2BKLPs25EksV3swS9NoNJjskQEr%2Bk%2BgtH7VIQ6b8QADaqkWoHQ1y43twteciehu8Yh43KVcwsZvUrsnk%2Fd%2BAOChZDgr0csGvIfanMixIhtgexxWrRjHaNd0%2FC7a5od4PLHR%2B3YAScLBdwrpwqIF%2F3vx0MELy%2BeQpaxIcGngB9XL%2FfDhVSooodbQ2WGXTbDV8taeYQglqvJ4GArWl5GFXo6g47rriNdej7iJJYcH8xfNpbOfBT5Pxolev6SJ2yM8j4LHkUSCN9NJMALUyfP%2FtnE%2B23YEde1cTSjfuDBKy0sdgVRMDDOg8I3r7v0EjDzjhoi6DSUB7cxeidZZz7vPzQclWIJHlfjeqFXoLBVq%2FSrbIzCfZYnUs8Wjvgz4naIi2RyoY0T3SjRNO5yRd3MQ4Uo5jinaHH7cxFAWhhz0Xq17Hf5z77vc7KTR6dSHP0eh7Iy0NgQzsP46FP22VmZYah4mMBjI58lLJHyTnfhUGhN8ACRha5Dt9roixRRTQKoqbG3L1%2B4g%2F5hvFChf%2B1AocFIHkJOBenPcIe%2FUeMkTQ5UI%2BbvQlQPnAs2bQVs%2FucIkUxDaJFlvof9pW3LXsnLT13w9YljDQ3%2B28BjqkAZX%2BCpNyEK4rw%2F7a3dfHBRWDhfOFI1%2BePGc1XiDHENVSjSWEMnseSlo5xjUuthPxZ5VzvDvzmuFoEW0GQV0YwjXDFJyZWXHmkBjBjVxM4bVOpVQpiUxHAlP43Okc6qK0XqZ%2BBiFwNkSMzTwZ6wHWnLww2LUHChsfgyBXYM120%2FrI3IfdcebdzIa1G6DJmAK9Fp4b%2BrKVS9eaqAmsC2lfEYKqQ7tW&X-Amz-Signature=fd27b802a4baf4492c6c175f6e84c8ca1a61c574b08cc0fa50b9d8e658249f4d&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466S3Y23BKZ%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T124411Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJ3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD3i0AAAf4fHZyB7bXSPqDFXcZuvvSKFcpWM6cLiqSe4AIhANTTsG79CLwDOn7Chumg66m7TAXAfuVWbJq%2B4G2UDaC0KogECKb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyBOw7pfHS5nEmSkbUq3ANR9osLf6Xk846eCglR4LLpdjLR%2FqCnsjk24%2BKLPs25EksV3swS9NoNJjskQEr%2Bk%2BgtH7VIQ6b8QADaqkWoHQ1y43twteciehu8Yh43KVcwsZvUrsnk%2Fd%2BAOChZDgr0csGvIfanMixIhtgexxWrRjHaNd0%2FC7a5od4PLHR%2B3YAScLBdwrpwqIF%2F3vx0MELy%2BeQpaxIcGngB9XL%2FfDhVSooodbQ2WGXTbDV8taeYQglqvJ4GArWl5GFXo6g47rriNdej7iJJYcH8xfNpbOfBT5Pxolev6SJ2yM8j4LHkUSCN9NJMALUyfP%2FtnE%2B23YEde1cTSjfuDBKy0sdgVRMDDOg8I3r7v0EjDzjhoi6DSUB7cxeidZZz7vPzQclWIJHlfjeqFXoLBVq%2FSrbIzCfZYnUs8Wjvgz4naIi2RyoY0T3SjRNO5yRd3MQ4Uo5jinaHH7cxFAWhhz0Xq17Hf5z77vc7KTR6dSHP0eh7Iy0NgQzsP46FP22VmZYah4mMBjI58lLJHyTnfhUGhN8ACRha5Dt9roixRRTQKoqbG3L1%2B4g%2F5hvFChf%2B1AocFIHkJOBenPcIe%2FUeMkTQ5UI%2BbvQlQPnAs2bQVs%2FucIkUxDaJFlvof9pW3LXsnLT13w9YljDQ3%2B28BjqkAZX%2BCpNyEK4rw%2F7a3dfHBRWDhfOFI1%2BePGc1XiDHENVSjSWEMnseSlo5xjUuthPxZ5VzvDvzmuFoEW0GQV0YwjXDFJyZWXHmkBjBjVxM4bVOpVQpiUxHAlP43Okc6qK0XqZ%2BBiFwNkSMzTwZ6wHWnLww2LUHChsfgyBXYM120%2FrI3IfdcebdzIa1G6DJmAK9Fp4b%2BrKVS9eaqAmsC2lfEYKqQ7tW&X-Amz-Signature=e22fa05bc59c32a24502cc144dd50b5b2f532babe2057a31bbe4fb10a165bb2e&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466S3Y23BKZ%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T124411Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJ3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD3i0AAAf4fHZyB7bXSPqDFXcZuvvSKFcpWM6cLiqSe4AIhANTTsG79CLwDOn7Chumg66m7TAXAfuVWbJq%2B4G2UDaC0KogECKb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyBOw7pfHS5nEmSkbUq3ANR9osLf6Xk846eCglR4LLpdjLR%2FqCnsjk24%2BKLPs25EksV3swS9NoNJjskQEr%2Bk%2BgtH7VIQ6b8QADaqkWoHQ1y43twteciehu8Yh43KVcwsZvUrsnk%2Fd%2BAOChZDgr0csGvIfanMixIhtgexxWrRjHaNd0%2FC7a5od4PLHR%2B3YAScLBdwrpwqIF%2F3vx0MELy%2BeQpaxIcGngB9XL%2FfDhVSooodbQ2WGXTbDV8taeYQglqvJ4GArWl5GFXo6g47rriNdej7iJJYcH8xfNpbOfBT5Pxolev6SJ2yM8j4LHkUSCN9NJMALUyfP%2FtnE%2B23YEde1cTSjfuDBKy0sdgVRMDDOg8I3r7v0EjDzjhoi6DSUB7cxeidZZz7vPzQclWIJHlfjeqFXoLBVq%2FSrbIzCfZYnUs8Wjvgz4naIi2RyoY0T3SjRNO5yRd3MQ4Uo5jinaHH7cxFAWhhz0Xq17Hf5z77vc7KTR6dSHP0eh7Iy0NgQzsP46FP22VmZYah4mMBjI58lLJHyTnfhUGhN8ACRha5Dt9roixRRTQKoqbG3L1%2B4g%2F5hvFChf%2B1AocFIHkJOBenPcIe%2FUeMkTQ5UI%2BbvQlQPnAs2bQVs%2FucIkUxDaJFlvof9pW3LXsnLT13w9YljDQ3%2B28BjqkAZX%2BCpNyEK4rw%2F7a3dfHBRWDhfOFI1%2BePGc1XiDHENVSjSWEMnseSlo5xjUuthPxZ5VzvDvzmuFoEW0GQV0YwjXDFJyZWXHmkBjBjVxM4bVOpVQpiUxHAlP43Okc6qK0XqZ%2BBiFwNkSMzTwZ6wHWnLww2LUHChsfgyBXYM120%2FrI3IfdcebdzIa1G6DJmAK9Fp4b%2BrKVS9eaqAmsC2lfEYKqQ7tW&X-Amz-Signature=022aefaae5898cb8a0462ba3393486174bb0f5b62e1cadffa9c871eb5bebe038&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466S3Y23BKZ%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T124411Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJ3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD3i0AAAf4fHZyB7bXSPqDFXcZuvvSKFcpWM6cLiqSe4AIhANTTsG79CLwDOn7Chumg66m7TAXAfuVWbJq%2B4G2UDaC0KogECKb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyBOw7pfHS5nEmSkbUq3ANR9osLf6Xk846eCglR4LLpdjLR%2FqCnsjk24%2BKLPs25EksV3swS9NoNJjskQEr%2Bk%2BgtH7VIQ6b8QADaqkWoHQ1y43twteciehu8Yh43KVcwsZvUrsnk%2Fd%2BAOChZDgr0csGvIfanMixIhtgexxWrRjHaNd0%2FC7a5od4PLHR%2B3YAScLBdwrpwqIF%2F3vx0MELy%2BeQpaxIcGngB9XL%2FfDhVSooodbQ2WGXTbDV8taeYQglqvJ4GArWl5GFXo6g47rriNdej7iJJYcH8xfNpbOfBT5Pxolev6SJ2yM8j4LHkUSCN9NJMALUyfP%2FtnE%2B23YEde1cTSjfuDBKy0sdgVRMDDOg8I3r7v0EjDzjhoi6DSUB7cxeidZZz7vPzQclWIJHlfjeqFXoLBVq%2FSrbIzCfZYnUs8Wjvgz4naIi2RyoY0T3SjRNO5yRd3MQ4Uo5jinaHH7cxFAWhhz0Xq17Hf5z77vc7KTR6dSHP0eh7Iy0NgQzsP46FP22VmZYah4mMBjI58lLJHyTnfhUGhN8ACRha5Dt9roixRRTQKoqbG3L1%2B4g%2F5hvFChf%2B1AocFIHkJOBenPcIe%2FUeMkTQ5UI%2BbvQlQPnAs2bQVs%2FucIkUxDaJFlvof9pW3LXsnLT13w9YljDQ3%2B28BjqkAZX%2BCpNyEK4rw%2F7a3dfHBRWDhfOFI1%2BePGc1XiDHENVSjSWEMnseSlo5xjUuthPxZ5VzvDvzmuFoEW0GQV0YwjXDFJyZWXHmkBjBjVxM4bVOpVQpiUxHAlP43Okc6qK0XqZ%2BBiFwNkSMzTwZ6wHWnLww2LUHChsfgyBXYM120%2FrI3IfdcebdzIa1G6DJmAK9Fp4b%2BrKVS9eaqAmsC2lfEYKqQ7tW&X-Amz-Signature=905585de2feaa7b888acf88d1665ce9b0a749c5356635a831d0ffdde52d7df97&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZXID3IQW%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T124413Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJ3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIH1Fjgo3Pw6Cj88YuMgJ5Y6gN%2FBj5ifHDOgSRjXNvnkuAiBMJFVZzoKcTCDBSouna8DpMhM8ppVB0z%2BEIWYaPh3fliqIBAim%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMJJPQs%2BtxEZXfv6gcKtwD8nF3dJWprVWBh%2BgFcyrooFO4sbhHh%2BLiVuKcoSG2QT%2FW497tGt%2BXvG1DTtNGE4X64iaqDhdrFCnimROLnnDH6oy2HLDNKO3tR523e4KRGwQM5jc%2FRN%2BjobwRaohsScbxlvHF%2Fw3C2DCTvWb6YAFuDflK2EdLK1xzWeq5V1QC7THePdBBpwvvbMdK3fjxxAf7zUHijJvJo7LsFIH7wzHbvhTmRmQ0y7FniAvT17TvurdxL9L4q3GByriGMcfIFdWAgn%2BVt6Uw7x7MD1UujKLkHcbsAsI9iPDFIbwGoO%2FNSlK%2FLHzqw7x3BhcPrjRWV1osTg1mXYrhsSJT7xgtuWvqLPSTYDUSlFDDVxCr2nHuVVyfAJMfnN8Fv%2BRAveEUC7Np5MXNQbCtueurZ5HXvsT8eEOFWnm0gSMTySmxRXEKfh1r1%2BC3aYP%2BfTjiMs3kKQwWLxUkyXAUe6ax5WHzF0PH8aD9QVHNbRukStCTV7HCgJMdzb%2F%2BdWCFIfkJxN%2FLT7Y3QF5UbIu2KXV4tR2QrDcT0gl777xLTtjLC0w42yHibSSg3Ky1Bo4LwwvZt2RDJBAoNxx%2FaGzskWqJki3mwGAO0J1OFfKYkdgBDrZviCOAN2ChUTO0NerHBkYRctwwk%2BHtvAY6pgHGp2Nv%2F6ZhT6%2FHPLZDcOEyK10QoGY9A2%2BSe6mdj0ipESP7NXJsO3cy0eo8q0fewn1vprYeS0Fh1XSida0sFmypQVtI82ihRb4Z2TdCwI%2B2b9wbySs9DWsyLIbdptuoAlt4g1B6FFXCHastWAZAks%2BZavmdjOJGWhzEGDr39xNU0qFPUKsrmJvZ5Lu1YUGGkBzJjzF9uSxBAOHJFkmQg7oCmfWjVWC3&X-Amz-Signature=c579c87df7f4bf6a71b6ba0db30738b72612deab360f69be269d5207d030666f&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UXGG24AH%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T124414Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJ3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCE2Bpos%2BmA%2BoxzexrggtSG1nV21GnFwkoGZLFdjbtWgQIgVEiN8sF%2FA1UutYBHKXO5NtwhqLvCveGGCeDPxHeVmo0qiAQIpv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDFtbT0ABF8jnyac9UCrcA59tFZE8yJy1VZKLs15mu3%2BpZjXD6NEcUyjniAIFHrWljzsfXyjbt7pV%2FmV56EUQCu6eWBTejObsRPEXVGjHCTWDQf9xefCw1igEExOr2pgwe%2F7rdlNizTk%2F6ZyWV25701Acd4HuYPBIC3RPW3hS6UVM6AzIurwoClINSVQTGGOL4uWN0zu7L74MQKWOgoQzbMwBZ28AOCjMvuG%2FX8hpkgm9uemp%2FPN6fxbsvVdJ5AVWSiGWKfMipOFVJS78C8yKKSozgEGrD6e8qswGwz52dGH9%2B4xW6CngAx2rlKuI4W%2BeLsWULTPdssST13QCzhuME5F%2FnDzbdcEVQECpGxv%2FgizKJGr%2FCaVRo1Ezxexi9N%2B%2B%2FO4D8rGrI6zzDcCBHOLGtgzvx8cFFQIV7Lw3XrA4go%2BrK4dFd47tLUcpKPa%2BNTmB8KiURUbwnJTUvuhPNmm94%2Fhqifi6xOxkoB8ugVq4hukkt2eiuUY7cc4Drz5XwDI2uCuSC%2BP0IgBQ9JDs5aguT7UXO4X6HHFmUXH5jv%2Ft%2BQldeCBek6kZqi4pKj%2FgvzwhM0DVr1Ad9TtbgVXjebfWYqKk%2Bu%2BznuyL%2BFCkRNzERZU%2FwX4jJXc6d0ubKRd6LD8DMqiOGrSSU4wTwiJgMObf7bwGOqUB51WlwbzUrKWBpvD0ph3P6sML7WY8z3UpFimzIEPZTRvVBt%2FnyjB8ClUxP5MnSkgYRaraMt4Cks5ejRmFsqlccmgiYfPCitvqw6CGxnyQmML%2BVKhahdroEStmz0KP5QWE%2BEtbcafENL0CPGEVG2wetecQpldjjk0b4f%2F%2BgXIlqAlS%2B13XeTKztXagznFbFbf8u7j6y%2BCtmdCjjeHelJowyhHUTcvU&X-Amz-Signature=6a4c6d713e29f5c456b347b97ff823dca13671f768e3ab4750572cb08a400f72&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466S3Y23BKZ%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T124411Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJ3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD3i0AAAf4fHZyB7bXSPqDFXcZuvvSKFcpWM6cLiqSe4AIhANTTsG79CLwDOn7Chumg66m7TAXAfuVWbJq%2B4G2UDaC0KogECKb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyBOw7pfHS5nEmSkbUq3ANR9osLf6Xk846eCglR4LLpdjLR%2FqCnsjk24%2BKLPs25EksV3swS9NoNJjskQEr%2Bk%2BgtH7VIQ6b8QADaqkWoHQ1y43twteciehu8Yh43KVcwsZvUrsnk%2Fd%2BAOChZDgr0csGvIfanMixIhtgexxWrRjHaNd0%2FC7a5od4PLHR%2B3YAScLBdwrpwqIF%2F3vx0MELy%2BeQpaxIcGngB9XL%2FfDhVSooodbQ2WGXTbDV8taeYQglqvJ4GArWl5GFXo6g47rriNdej7iJJYcH8xfNpbOfBT5Pxolev6SJ2yM8j4LHkUSCN9NJMALUyfP%2FtnE%2B23YEde1cTSjfuDBKy0sdgVRMDDOg8I3r7v0EjDzjhoi6DSUB7cxeidZZz7vPzQclWIJHlfjeqFXoLBVq%2FSrbIzCfZYnUs8Wjvgz4naIi2RyoY0T3SjRNO5yRd3MQ4Uo5jinaHH7cxFAWhhz0Xq17Hf5z77vc7KTR6dSHP0eh7Iy0NgQzsP46FP22VmZYah4mMBjI58lLJHyTnfhUGhN8ACRha5Dt9roixRRTQKoqbG3L1%2B4g%2F5hvFChf%2B1AocFIHkJOBenPcIe%2FUeMkTQ5UI%2BbvQlQPnAs2bQVs%2FucIkUxDaJFlvof9pW3LXsnLT13w9YljDQ3%2B28BjqkAZX%2BCpNyEK4rw%2F7a3dfHBRWDhfOFI1%2BePGc1XiDHENVSjSWEMnseSlo5xjUuthPxZ5VzvDvzmuFoEW0GQV0YwjXDFJyZWXHmkBjBjVxM4bVOpVQpiUxHAlP43Okc6qK0XqZ%2BBiFwNkSMzTwZ6wHWnLww2LUHChsfgyBXYM120%2FrI3IfdcebdzIa1G6DJmAK9Fp4b%2BrKVS9eaqAmsC2lfEYKqQ7tW&X-Amz-Signature=c5d04d28e82644215bfc27a11d44dfe1d54a7216a0e7fa50d8d8d44984fb2e74&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466S3Y23BKZ%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T124411Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJ3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD3i0AAAf4fHZyB7bXSPqDFXcZuvvSKFcpWM6cLiqSe4AIhANTTsG79CLwDOn7Chumg66m7TAXAfuVWbJq%2B4G2UDaC0KogECKb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyBOw7pfHS5nEmSkbUq3ANR9osLf6Xk846eCglR4LLpdjLR%2FqCnsjk24%2BKLPs25EksV3swS9NoNJjskQEr%2Bk%2BgtH7VIQ6b8QADaqkWoHQ1y43twteciehu8Yh43KVcwsZvUrsnk%2Fd%2BAOChZDgr0csGvIfanMixIhtgexxWrRjHaNd0%2FC7a5od4PLHR%2B3YAScLBdwrpwqIF%2F3vx0MELy%2BeQpaxIcGngB9XL%2FfDhVSooodbQ2WGXTbDV8taeYQglqvJ4GArWl5GFXo6g47rriNdej7iJJYcH8xfNpbOfBT5Pxolev6SJ2yM8j4LHkUSCN9NJMALUyfP%2FtnE%2B23YEde1cTSjfuDBKy0sdgVRMDDOg8I3r7v0EjDzjhoi6DSUB7cxeidZZz7vPzQclWIJHlfjeqFXoLBVq%2FSrbIzCfZYnUs8Wjvgz4naIi2RyoY0T3SjRNO5yRd3MQ4Uo5jinaHH7cxFAWhhz0Xq17Hf5z77vc7KTR6dSHP0eh7Iy0NgQzsP46FP22VmZYah4mMBjI58lLJHyTnfhUGhN8ACRha5Dt9roixRRTQKoqbG3L1%2B4g%2F5hvFChf%2B1AocFIHkJOBenPcIe%2FUeMkTQ5UI%2BbvQlQPnAs2bQVs%2FucIkUxDaJFlvof9pW3LXsnLT13w9YljDQ3%2B28BjqkAZX%2BCpNyEK4rw%2F7a3dfHBRWDhfOFI1%2BePGc1XiDHENVSjSWEMnseSlo5xjUuthPxZ5VzvDvzmuFoEW0GQV0YwjXDFJyZWXHmkBjBjVxM4bVOpVQpiUxHAlP43Okc6qK0XqZ%2BBiFwNkSMzTwZ6wHWnLww2LUHChsfgyBXYM120%2FrI3IfdcebdzIa1G6DJmAK9Fp4b%2BrKVS9eaqAmsC2lfEYKqQ7tW&X-Amz-Signature=c8e2d59c173c849490cdb399c431f6e27a7fc584cc7bf4f7556d3c0ae062a19a&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466S3Y23BKZ%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T124411Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJ3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD3i0AAAf4fHZyB7bXSPqDFXcZuvvSKFcpWM6cLiqSe4AIhANTTsG79CLwDOn7Chumg66m7TAXAfuVWbJq%2B4G2UDaC0KogECKb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyBOw7pfHS5nEmSkbUq3ANR9osLf6Xk846eCglR4LLpdjLR%2FqCnsjk24%2BKLPs25EksV3swS9NoNJjskQEr%2Bk%2BgtH7VIQ6b8QADaqkWoHQ1y43twteciehu8Yh43KVcwsZvUrsnk%2Fd%2BAOChZDgr0csGvIfanMixIhtgexxWrRjHaNd0%2FC7a5od4PLHR%2B3YAScLBdwrpwqIF%2F3vx0MELy%2BeQpaxIcGngB9XL%2FfDhVSooodbQ2WGXTbDV8taeYQglqvJ4GArWl5GFXo6g47rriNdej7iJJYcH8xfNpbOfBT5Pxolev6SJ2yM8j4LHkUSCN9NJMALUyfP%2FtnE%2B23YEde1cTSjfuDBKy0sdgVRMDDOg8I3r7v0EjDzjhoi6DSUB7cxeidZZz7vPzQclWIJHlfjeqFXoLBVq%2FSrbIzCfZYnUs8Wjvgz4naIi2RyoY0T3SjRNO5yRd3MQ4Uo5jinaHH7cxFAWhhz0Xq17Hf5z77vc7KTR6dSHP0eh7Iy0NgQzsP46FP22VmZYah4mMBjI58lLJHyTnfhUGhN8ACRha5Dt9roixRRTQKoqbG3L1%2B4g%2F5hvFChf%2B1AocFIHkJOBenPcIe%2FUeMkTQ5UI%2BbvQlQPnAs2bQVs%2FucIkUxDaJFlvof9pW3LXsnLT13w9YljDQ3%2B28BjqkAZX%2BCpNyEK4rw%2F7a3dfHBRWDhfOFI1%2BePGc1XiDHENVSjSWEMnseSlo5xjUuthPxZ5VzvDvzmuFoEW0GQV0YwjXDFJyZWXHmkBjBjVxM4bVOpVQpiUxHAlP43Okc6qK0XqZ%2BBiFwNkSMzTwZ6wHWnLww2LUHChsfgyBXYM120%2FrI3IfdcebdzIa1G6DJmAK9Fp4b%2BrKVS9eaqAmsC2lfEYKqQ7tW&X-Amz-Signature=d7ba3e913eb741cce05a43f93cfe8ec6ebc4c345001599851f6a9229de7c2ffb&X-Amz-SignedHeaders=host&x-id=GetObject)


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

