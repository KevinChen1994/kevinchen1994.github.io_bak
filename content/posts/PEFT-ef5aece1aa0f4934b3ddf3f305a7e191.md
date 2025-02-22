---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466TZUK47SF%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250222T142039Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEMT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDMJNt%2Fc1E9z3ZR5\
  GqR3iBmhHrjG9fFNQY6tZpbSH%2BqfwIgL4H2oFzPbdbLrtA%2FnQq6ZndWE843I%2BahOfIkOghO\
  7gMqiAQI7P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDF71bUTd%2BCP\
  TZSHruSrcAzHYU6ud9X05DVGDj8mzd2sYN86maPnpjtXKRrb9Bst9xI%2BPrM5dcMhcpkiZN%2F%2\
  FPBCgobu3hOL8wo4L75Vnave99RjA4yzlH9UESmdFcJKHFyG9hoZUI1NDmktWSfVk9hgs29oIRkt9\
  R0MKn2zhptVPhm4c%2BuPbTJ7LyWtbX%2BwqYRKv0802n0l4Q1ueS1fvYfLms5WIDvssVo7G4z5iI\
  NxDjUzdIvIUrqDAP846H2mvBh7DHwrQDs2LBuXetW9J4ZoxwpVRWLVGwEmpcpAz2RU6HwpANkEcFS\
  HjVMca2%2FqGoD2R97ww1Be%2BPSFNKshqmVDd8fOVUNoOLTxq5hDabUt2dOnsX2WKN9sYQsxYrgt\
  cLtd5hkdEywg6i%2Fz%2Ff0%2BxLf9%2FLZWKgQqSysksbyiSDz%2B0xMI3XAh9EO69mPczp%2Br7\
  O5Vq3ANcg5Li4ks9vTw27NYJeKJpELA9E0M7YHcSQ8hUoLvq7HANvMV92nERKUqbAsNKZs9RxDaqt\
  g0UbbO4bVW79UkQzwRmTrF6XyQIJ0WU%2F9SZpreWsaLqnxpvvgUcPa2T1%2Be1gjadb6o6825IMv\
  HX%2F0mkgd7Y%2BO%2Bofc%2BpdhrRTe54%2B7fNdobejoWldLvAxjhCYTd0W0acUcjlXMK7l5r0G\
  OqUBNe0u00aS2qW2Prp%2FyHR49Xbw1RgkAAIVGhcLYU5Gf5bwFnh6%2Frh8EG8INPf8PgP50RA2r\
  m4cdYd7L8aBiaAWwV8yCfaYpG4RDg8akEZlTYS4N7g6dukRlDtYWwA%2BS4vwxZoF2ihofAEVjL1k\
  ZUSFMHFEv3DOjZwWjxiOYwi3bKB6ohqgGZXyimhA8A8yo15djvIwLB84gNP29TUUx42WjE%2Bagej\
  0&X-Amz-Signature=45907b2dd38feeb69a1178e1b239a3c3ff6dbcd74a904b384b128ae7550\
  0fbc1&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4665UMZXH5O%2F20250222%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250222T141903Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEMT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIQCQC7NLzcxvfZFpHyB4P8ROw9qwRw7GJ%2BtAMj8Dy0Aw6QIgCiPJPF9qW6%2FhGytA3T\
        sCHx%2Bp9Ubam8U%2Bwgs7vIWhnvUqiAQI7f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAG\
        gw2Mzc0MjMxODM4MDUiDHwq7otHGi%2F5g%2BW1IircA6JWDMyi6WTs%2BHNwISwsB0Aj1c\
        XwY%2Fajfj0G0MzNyjgwrS6zGABgBpYgkFaQYQqrjojJxHvzduQPV9wjMaeqtDhyULL1aw%\
        2BlsvtfbncnAWUUoDRA07rJoATgDkmzDUdzLsTzkiD75Xv9M7ocTr709GvURx2qrYOxqrBS\
        YfMDITwNLh0BE%2FuX6H1VbPU82oXOaW%2FxBDOzRLF%2FyPkj61GveU7aa9fkegHcURu4%\
        2FTQv4rp%2FJPQrx8%2BZu15iGdNF8wlCQ3Q2p7wds3y3c1%2FZoFxaIpnpecO5aSJnH2Cg\
        NS%2Bbyj53bvBuV4M5HvQG9Fa14jLS1l7JoBVAoWuUHH%2BJ2%2FFkhXUBZ64SNVqAySU8T\
        myM5wwX4m5oiGNwzohokha%2B2B4KKi2N54PNk2QyfVplfiIHGHIU2ycYaW9z7%2FOhKUrd\
        i%2FK1kY%2FoHdW8kIpUmSZYH1szA8mVPgdSzuMRdEE4L3Aijp5kcLeXjzwYy%2BwGEcZny\
        CVmbf2y8hmkTvI8apqOZJWO6Jd4dBcLk3VjQQESquymhzMBjpDuToLsVc5pX2pE7aqebaJI\
        An4ZxEL8G6FgeaUalymHFuMC2Y5gdYac9ox%2FNbC%2BC1fElRL3o59yD71j9ZedAQ2C76x\
        l3AnLkRP5MJ3r5r0GOqUBzkwL2ETJ%2FTfResavoXPsXXzwsrzpMoXhsmP3tlZ6LVgU%2BV\
        u7BiZ6o7V6jnkFMsx4Q1NbBGO6MsRA3CPADTgKZhSMErXwvuwlCZaDb%2BPoCtmNX0WqauC\
        lpbffLiqFUlmhCS0K0enuDEPxbUEnQ2gwe6tLE8IhUdj4pmniZg7bLwU2poEK9Mq5eC7%2F\
        eROL2g9speTT7pibEaVjDJdRkm8mAT7YJ1kN&X-Amz-Signature=a920016054f1fcb00b\
        412c3bb4ecab9c82d2b306430661e9f58dde722f523f3a&X-Amz-SignedHeaders=host\
        &x-id=GetObject"
      expiry_time: "2025-02-22T15:19:03.009Z"
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
UPDATE_TIME: "2025-02-22T14:20:45.139Z"
EXPIRY_TIME: "2025-02-22T15:20:34.280Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667LZS52QT%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T142035Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCCyx0TBGmhylASu72YCYeMvMHtrCprot3QByf0FEpT%2BQIgNo8%2FUxYZKfP45h%2FcC8CySmWnKLvwIJTJshBlPlO4ulUqiAQI6v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDFm5WNm93svovtITgCrcAymw0oXZzj8idtSV8KCTsFMJc8EMLEaI11UL5ydQ65ybuPLtMXy%2F4SI4ZJtq20b46iqoCjvpwXGFouJOfFH4iAR%2B26Pw8tN%2BprMNyMh%2F3mMVqLEA9IBdYjtPEnsPTPS9mU6DP67bvrlc3wTe8z0q71B1aY0CarF1%2FYJ5HdpZpgNUp%2BWOxrNRKPFsO0y6sq1pPPU8I5l7ELYxHhBok7T86ySJtyYT0kFisrd%2BVCt2gzCpDhf%2F6JRKzDwqO%2FOAt1py0z%2B%2BceVRFjl%2BneAp1o03ljEiipYXjxPY0ghxfxIgLCQfln3rS0evg2Vfe0qo%2FNqju88G1jxhGAVLji7tgEeGEIupjutFBuLHQ92y9prNd7C94%2F1XJD2wIv11CxvhU5kgof4Tc%2BitojLQFDoW7Ubggg6rUD3ONVcCoCLlr7oOM9mZpLFg%2BMB9FhVgkqhRLwhkCG8nJfGKg%2FD3HBjC7KlvdFphzrv%2B2vQmoPdT3aBSxnjq1xY5caUKMiZO3gma2MdS6Bk33mIJdzTtyNYUte2xJgRcPOEfdQh4GZqJe7pPAHmjiLtM8yPHJBkIlHRQw5FhrSntOpxHm1sE0%2BPR2wwgY0DmwYiJ5%2BQph9hrMdi2EsXLr%2BHODtMykYTLBI6EMN2U5r0GOqUB2rtV4aWEg7RwnHC8TAjim1ZXPFw2R%2FTrWi2L90p52S48dOJdsELnFuCKDiyuf3C4cNV3YQNsrz92Hpd3eLy2dKuEwYOZJn647Gf%2FIE8wVer2Uqd%2F0Yl4W1dmDixjA0apkb73vIaaKrSKUD6vWAf43R2YkopSM11CvxSzuFPner7wAUc0ngJyNDVcKQQgLTB%2FiLIJ7gcea9quwQNJ10b30WoQFYKf&X-Amz-Signature=dada1d614466c0d9a60dc14e81b1a45e63bec5df91cd36c48dbac0db971b32e7&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667LZS52QT%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T142035Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCCyx0TBGmhylASu72YCYeMvMHtrCprot3QByf0FEpT%2BQIgNo8%2FUxYZKfP45h%2FcC8CySmWnKLvwIJTJshBlPlO4ulUqiAQI6v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDFm5WNm93svovtITgCrcAymw0oXZzj8idtSV8KCTsFMJc8EMLEaI11UL5ydQ65ybuPLtMXy%2F4SI4ZJtq20b46iqoCjvpwXGFouJOfFH4iAR%2B26Pw8tN%2BprMNyMh%2F3mMVqLEA9IBdYjtPEnsPTPS9mU6DP67bvrlc3wTe8z0q71B1aY0CarF1%2FYJ5HdpZpgNUp%2BWOxrNRKPFsO0y6sq1pPPU8I5l7ELYxHhBok7T86ySJtyYT0kFisrd%2BVCt2gzCpDhf%2F6JRKzDwqO%2FOAt1py0z%2B%2BceVRFjl%2BneAp1o03ljEiipYXjxPY0ghxfxIgLCQfln3rS0evg2Vfe0qo%2FNqju88G1jxhGAVLji7tgEeGEIupjutFBuLHQ92y9prNd7C94%2F1XJD2wIv11CxvhU5kgof4Tc%2BitojLQFDoW7Ubggg6rUD3ONVcCoCLlr7oOM9mZpLFg%2BMB9FhVgkqhRLwhkCG8nJfGKg%2FD3HBjC7KlvdFphzrv%2B2vQmoPdT3aBSxnjq1xY5caUKMiZO3gma2MdS6Bk33mIJdzTtyNYUte2xJgRcPOEfdQh4GZqJe7pPAHmjiLtM8yPHJBkIlHRQw5FhrSntOpxHm1sE0%2BPR2wwgY0DmwYiJ5%2BQph9hrMdi2EsXLr%2BHODtMykYTLBI6EMN2U5r0GOqUB2rtV4aWEg7RwnHC8TAjim1ZXPFw2R%2FTrWi2L90p52S48dOJdsELnFuCKDiyuf3C4cNV3YQNsrz92Hpd3eLy2dKuEwYOZJn647Gf%2FIE8wVer2Uqd%2F0Yl4W1dmDixjA0apkb73vIaaKrSKUD6vWAf43R2YkopSM11CvxSzuFPner7wAUc0ngJyNDVcKQQgLTB%2FiLIJ7gcea9quwQNJ10b30WoQFYKf&X-Amz-Signature=9c77da4c300a9e95ea2e6de83b58a22cbc13a282c8df3b4364040aa8f848b649&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667LZS52QT%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T142035Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCCyx0TBGmhylASu72YCYeMvMHtrCprot3QByf0FEpT%2BQIgNo8%2FUxYZKfP45h%2FcC8CySmWnKLvwIJTJshBlPlO4ulUqiAQI6v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDFm5WNm93svovtITgCrcAymw0oXZzj8idtSV8KCTsFMJc8EMLEaI11UL5ydQ65ybuPLtMXy%2F4SI4ZJtq20b46iqoCjvpwXGFouJOfFH4iAR%2B26Pw8tN%2BprMNyMh%2F3mMVqLEA9IBdYjtPEnsPTPS9mU6DP67bvrlc3wTe8z0q71B1aY0CarF1%2FYJ5HdpZpgNUp%2BWOxrNRKPFsO0y6sq1pPPU8I5l7ELYxHhBok7T86ySJtyYT0kFisrd%2BVCt2gzCpDhf%2F6JRKzDwqO%2FOAt1py0z%2B%2BceVRFjl%2BneAp1o03ljEiipYXjxPY0ghxfxIgLCQfln3rS0evg2Vfe0qo%2FNqju88G1jxhGAVLji7tgEeGEIupjutFBuLHQ92y9prNd7C94%2F1XJD2wIv11CxvhU5kgof4Tc%2BitojLQFDoW7Ubggg6rUD3ONVcCoCLlr7oOM9mZpLFg%2BMB9FhVgkqhRLwhkCG8nJfGKg%2FD3HBjC7KlvdFphzrv%2B2vQmoPdT3aBSxnjq1xY5caUKMiZO3gma2MdS6Bk33mIJdzTtyNYUte2xJgRcPOEfdQh4GZqJe7pPAHmjiLtM8yPHJBkIlHRQw5FhrSntOpxHm1sE0%2BPR2wwgY0DmwYiJ5%2BQph9hrMdi2EsXLr%2BHODtMykYTLBI6EMN2U5r0GOqUB2rtV4aWEg7RwnHC8TAjim1ZXPFw2R%2FTrWi2L90p52S48dOJdsELnFuCKDiyuf3C4cNV3YQNsrz92Hpd3eLy2dKuEwYOZJn647Gf%2FIE8wVer2Uqd%2F0Yl4W1dmDixjA0apkb73vIaaKrSKUD6vWAf43R2YkopSM11CvxSzuFPner7wAUc0ngJyNDVcKQQgLTB%2FiLIJ7gcea9quwQNJ10b30WoQFYKf&X-Amz-Signature=d54ce87726e5928f4360c7e1e7d6514bbe160feef2898292e8f6344944e34374&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667LZS52QT%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T142035Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCCyx0TBGmhylASu72YCYeMvMHtrCprot3QByf0FEpT%2BQIgNo8%2FUxYZKfP45h%2FcC8CySmWnKLvwIJTJshBlPlO4ulUqiAQI6v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDFm5WNm93svovtITgCrcAymw0oXZzj8idtSV8KCTsFMJc8EMLEaI11UL5ydQ65ybuPLtMXy%2F4SI4ZJtq20b46iqoCjvpwXGFouJOfFH4iAR%2B26Pw8tN%2BprMNyMh%2F3mMVqLEA9IBdYjtPEnsPTPS9mU6DP67bvrlc3wTe8z0q71B1aY0CarF1%2FYJ5HdpZpgNUp%2BWOxrNRKPFsO0y6sq1pPPU8I5l7ELYxHhBok7T86ySJtyYT0kFisrd%2BVCt2gzCpDhf%2F6JRKzDwqO%2FOAt1py0z%2B%2BceVRFjl%2BneAp1o03ljEiipYXjxPY0ghxfxIgLCQfln3rS0evg2Vfe0qo%2FNqju88G1jxhGAVLji7tgEeGEIupjutFBuLHQ92y9prNd7C94%2F1XJD2wIv11CxvhU5kgof4Tc%2BitojLQFDoW7Ubggg6rUD3ONVcCoCLlr7oOM9mZpLFg%2BMB9FhVgkqhRLwhkCG8nJfGKg%2FD3HBjC7KlvdFphzrv%2B2vQmoPdT3aBSxnjq1xY5caUKMiZO3gma2MdS6Bk33mIJdzTtyNYUte2xJgRcPOEfdQh4GZqJe7pPAHmjiLtM8yPHJBkIlHRQw5FhrSntOpxHm1sE0%2BPR2wwgY0DmwYiJ5%2BQph9hrMdi2EsXLr%2BHODtMykYTLBI6EMN2U5r0GOqUB2rtV4aWEg7RwnHC8TAjim1ZXPFw2R%2FTrWi2L90p52S48dOJdsELnFuCKDiyuf3C4cNV3YQNsrz92Hpd3eLy2dKuEwYOZJn647Gf%2FIE8wVer2Uqd%2F0Yl4W1dmDixjA0apkb73vIaaKrSKUD6vWAf43R2YkopSM11CvxSzuFPner7wAUc0ngJyNDVcKQQgLTB%2FiLIJ7gcea9quwQNJ10b30WoQFYKf&X-Amz-Signature=8adfe99c8f2a8bb723d055aa4802258f47ba1f902854b43d2b8124cca564973b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667LZS52QT%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T142035Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCCyx0TBGmhylASu72YCYeMvMHtrCprot3QByf0FEpT%2BQIgNo8%2FUxYZKfP45h%2FcC8CySmWnKLvwIJTJshBlPlO4ulUqiAQI6v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDFm5WNm93svovtITgCrcAymw0oXZzj8idtSV8KCTsFMJc8EMLEaI11UL5ydQ65ybuPLtMXy%2F4SI4ZJtq20b46iqoCjvpwXGFouJOfFH4iAR%2B26Pw8tN%2BprMNyMh%2F3mMVqLEA9IBdYjtPEnsPTPS9mU6DP67bvrlc3wTe8z0q71B1aY0CarF1%2FYJ5HdpZpgNUp%2BWOxrNRKPFsO0y6sq1pPPU8I5l7ELYxHhBok7T86ySJtyYT0kFisrd%2BVCt2gzCpDhf%2F6JRKzDwqO%2FOAt1py0z%2B%2BceVRFjl%2BneAp1o03ljEiipYXjxPY0ghxfxIgLCQfln3rS0evg2Vfe0qo%2FNqju88G1jxhGAVLji7tgEeGEIupjutFBuLHQ92y9prNd7C94%2F1XJD2wIv11CxvhU5kgof4Tc%2BitojLQFDoW7Ubggg6rUD3ONVcCoCLlr7oOM9mZpLFg%2BMB9FhVgkqhRLwhkCG8nJfGKg%2FD3HBjC7KlvdFphzrv%2B2vQmoPdT3aBSxnjq1xY5caUKMiZO3gma2MdS6Bk33mIJdzTtyNYUte2xJgRcPOEfdQh4GZqJe7pPAHmjiLtM8yPHJBkIlHRQw5FhrSntOpxHm1sE0%2BPR2wwgY0DmwYiJ5%2BQph9hrMdi2EsXLr%2BHODtMykYTLBI6EMN2U5r0GOqUB2rtV4aWEg7RwnHC8TAjim1ZXPFw2R%2FTrWi2L90p52S48dOJdsELnFuCKDiyuf3C4cNV3YQNsrz92Hpd3eLy2dKuEwYOZJn647Gf%2FIE8wVer2Uqd%2F0Yl4W1dmDixjA0apkb73vIaaKrSKUD6vWAf43R2YkopSM11CvxSzuFPner7wAUc0ngJyNDVcKQQgLTB%2FiLIJ7gcea9quwQNJ10b30WoQFYKf&X-Amz-Signature=b4b8413d523f7d0fe822eef2181b11ec92e2c60b9102f814d4758cc55f585087&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666HVP235Q%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T142037Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIHrfpDuEj%2FlN8%2F7XPaDbAQTnqc0BWjoxiuFqoNsSmdNJAiEAwbgH7KEjNN53reqrgzaOS1V46Fs7bP9q3f%2B69NHm15EqiAQI7f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDBTlZeRLcwWGzEqvVircA6A0b2o%2BTOTYjLwkn83j6Iy906Sjm%2BrdG%2FDCaGVrdJypyzPKCOhIZx76DgQEeqriMHC%2Fzad0DzhzaF4u8WCMcaTy6b4cZ5YkiaZSHO4R1KiOyMY8t98wFIpKSyL5AdzF%2B3epHVGoAPR6M%2FopreCEks1MZN1KKlN5kQ4aC71yNHm%2FOe7ITBPfN94Jf6dPM3P4pAfoYic28NxN5QiD5%2BDZTO8WH2DAW80R7KM530c7SOw27AVde3OWY6KQ1N34EEMMIWsp%2B16rKZ%2Faq817TGV0khnnzhe6BwuQu27hqc0IeKvJEuuTUJjsA2YwR2jiG4OHUVWpm47ZJpK87%2FVZNeW%2BryNprXkCubJKYRUt9u0x5QiOm3v%2Fg6p%2FyUNE1YaYOgUfh0OfOUG0k6Va%2FQve0CC3jDunq9k8WiaD%2Fj5TcdByk1eHRcWVGihJP6eVF1gKku4hDRWrFXe0uIRhX%2FatxOAR8%2F6MC7VveqB7aL14jFL1PMFM97qWhhAisP59JX8SKvI5ldgKBvDiOM6IKmPYhYiDJnQP1AUXfFDnkLbRIPG%2BaBHuoIQo1Lhow%2BqpbVXLKlGeFHi0Bm231HTRQrwtwqVY%2B3qThHN6BbZhrKnP5Y73sWs9CYMfNFWyMSHYTjOOMN%2Fm5r0GOqUBGttPYPzeN5rvet2ySAZa16iz259IjUkjEi5MV%2FUAKWRZ7%2B1K2Nqo%2FtWZ9mOpQaNLQUPkOhVXyyzGxpPChiIAA7lj1a4tH9jyoZIGYqJgx56l%2FZ1UoWOWhsRgzfMQhaLgO0EhcfIGqgycJ8UlM3v7Ok9qgG1kdTmZqjZUsTF5BfsWwYW9ezPF%2Bnl5VSBnlIe7e7PehCj00UlmSp4JHI7p8iwHnbXA&X-Amz-Signature=e1c47802168cfd85a4587c7b7330085cd581f72c39ee12f1f3e5efbd56fd7255&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Q4J2SKWE%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T142038Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDatZDaTJJbGcfsodliET3e0mlSwhLsdfSlj59CzyiBRgIhAOqHRjZV2VESAXnyUMi7Uxa6%2FaXKLyslVtUHjVf64ouPKogECO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzHUzZldCITXXavrJEq3AMEEZHAnpyJYktwCkMY9F4xSbjxE5o4q2%2FHnRVYugMSaI%2F7uNw4ThFHPeVqY4vxxul%2BDUQboaK%2FhPp73MgeKrw5EmzQeTq5h7zO4qnp8eDFiUD0OjR%2BDx6m5LHdldGAqDLuireMFtM3tBEt6z3m7x0eTGg2Xe%2FxD5Ki7uTQEiherAJ1bB3%2FjSnJkaZ9HmYsDGMUYVufAh%2FKojeYBu%2F7gxhVV6qzXRYwFQ08JLMY0ac6hDK%2FixJx4c%2FhbvS8Di4fAUhP3MDkVkFOF7a6X8KEBqKlato1ZH86%2FkITT%2Fp1%2FA6on6Ibnufoh9Hyd%2BtkLHQHM7Y4yeEPor%2BSrHXXRLyZ4ptrF0Nh0XlNDM%2FY%2BxrtsDjY6pOlhvXaFTwjHN9e3nNRKc9Fmujefmp9Hlz5KMncZujE5BWYlVdTt73dvcHLf0ay5tEwH9Zfl8BbHEvwRPP0ag4Tl6oFEpevJKfGhNuva06mJOft9uHoTVR6%2FiJK%2FewPiPpbMStvsisaHex7Eg2fyL5I3%2BGsoh1ju2wxUAXHsDBkcF5nCYSwRp3XQ3D325nZZ1iVocc2DDJRhYdoQu8iMpXZnYxt1C6Pmrxc4Z%2F4Ww8DxgGNe4uamexPiNJUFCiCi6Rxu9Y8pp2YQaB6ATCd6%2Ba9BjqkAUAm6oCEVNJqRoK4pK3m3IwZETQ5Jo6sbntjIjgkxaoOtQybsQatNevZdGfY%2ByU7Xvn%2BBl00QMGpo2FHKqvKKytRb2QmEP9NJt%2F27r1lTXxICkKNMHjDA2enf1Pb66BEc8Sv46BGoK8qwWbcY3Pf3I1rdiacKzatPp4ezPHFavBwJ5uNfU69aj0l%2FDcDbgXoNVCZlWRbK2tiuF6yizlN%2BBI6kNj6&X-Amz-Signature=ebb673c152e345b467a8d7fcb711be3b799b2dbf4f70f9b30637ee1862666d43&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667LZS52QT%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T142035Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCCyx0TBGmhylASu72YCYeMvMHtrCprot3QByf0FEpT%2BQIgNo8%2FUxYZKfP45h%2FcC8CySmWnKLvwIJTJshBlPlO4ulUqiAQI6v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDFm5WNm93svovtITgCrcAymw0oXZzj8idtSV8KCTsFMJc8EMLEaI11UL5ydQ65ybuPLtMXy%2F4SI4ZJtq20b46iqoCjvpwXGFouJOfFH4iAR%2B26Pw8tN%2BprMNyMh%2F3mMVqLEA9IBdYjtPEnsPTPS9mU6DP67bvrlc3wTe8z0q71B1aY0CarF1%2FYJ5HdpZpgNUp%2BWOxrNRKPFsO0y6sq1pPPU8I5l7ELYxHhBok7T86ySJtyYT0kFisrd%2BVCt2gzCpDhf%2F6JRKzDwqO%2FOAt1py0z%2B%2BceVRFjl%2BneAp1o03ljEiipYXjxPY0ghxfxIgLCQfln3rS0evg2Vfe0qo%2FNqju88G1jxhGAVLji7tgEeGEIupjutFBuLHQ92y9prNd7C94%2F1XJD2wIv11CxvhU5kgof4Tc%2BitojLQFDoW7Ubggg6rUD3ONVcCoCLlr7oOM9mZpLFg%2BMB9FhVgkqhRLwhkCG8nJfGKg%2FD3HBjC7KlvdFphzrv%2B2vQmoPdT3aBSxnjq1xY5caUKMiZO3gma2MdS6Bk33mIJdzTtyNYUte2xJgRcPOEfdQh4GZqJe7pPAHmjiLtM8yPHJBkIlHRQw5FhrSntOpxHm1sE0%2BPR2wwgY0DmwYiJ5%2BQph9hrMdi2EsXLr%2BHODtMykYTLBI6EMN2U5r0GOqUB2rtV4aWEg7RwnHC8TAjim1ZXPFw2R%2FTrWi2L90p52S48dOJdsELnFuCKDiyuf3C4cNV3YQNsrz92Hpd3eLy2dKuEwYOZJn647Gf%2FIE8wVer2Uqd%2F0Yl4W1dmDixjA0apkb73vIaaKrSKUD6vWAf43R2YkopSM11CvxSzuFPner7wAUc0ngJyNDVcKQQgLTB%2FiLIJ7gcea9quwQNJ10b30WoQFYKf&X-Amz-Signature=45c066a6323828c8f60b626b673a7d2173a535664418ef57d4de8ef0d1866389&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667LZS52QT%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T142035Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCCyx0TBGmhylASu72YCYeMvMHtrCprot3QByf0FEpT%2BQIgNo8%2FUxYZKfP45h%2FcC8CySmWnKLvwIJTJshBlPlO4ulUqiAQI6v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDFm5WNm93svovtITgCrcAymw0oXZzj8idtSV8KCTsFMJc8EMLEaI11UL5ydQ65ybuPLtMXy%2F4SI4ZJtq20b46iqoCjvpwXGFouJOfFH4iAR%2B26Pw8tN%2BprMNyMh%2F3mMVqLEA9IBdYjtPEnsPTPS9mU6DP67bvrlc3wTe8z0q71B1aY0CarF1%2FYJ5HdpZpgNUp%2BWOxrNRKPFsO0y6sq1pPPU8I5l7ELYxHhBok7T86ySJtyYT0kFisrd%2BVCt2gzCpDhf%2F6JRKzDwqO%2FOAt1py0z%2B%2BceVRFjl%2BneAp1o03ljEiipYXjxPY0ghxfxIgLCQfln3rS0evg2Vfe0qo%2FNqju88G1jxhGAVLji7tgEeGEIupjutFBuLHQ92y9prNd7C94%2F1XJD2wIv11CxvhU5kgof4Tc%2BitojLQFDoW7Ubggg6rUD3ONVcCoCLlr7oOM9mZpLFg%2BMB9FhVgkqhRLwhkCG8nJfGKg%2FD3HBjC7KlvdFphzrv%2B2vQmoPdT3aBSxnjq1xY5caUKMiZO3gma2MdS6Bk33mIJdzTtyNYUte2xJgRcPOEfdQh4GZqJe7pPAHmjiLtM8yPHJBkIlHRQw5FhrSntOpxHm1sE0%2BPR2wwgY0DmwYiJ5%2BQph9hrMdi2EsXLr%2BHODtMykYTLBI6EMN2U5r0GOqUB2rtV4aWEg7RwnHC8TAjim1ZXPFw2R%2FTrWi2L90p52S48dOJdsELnFuCKDiyuf3C4cNV3YQNsrz92Hpd3eLy2dKuEwYOZJn647Gf%2FIE8wVer2Uqd%2F0Yl4W1dmDixjA0apkb73vIaaKrSKUD6vWAf43R2YkopSM11CvxSzuFPner7wAUc0ngJyNDVcKQQgLTB%2FiLIJ7gcea9quwQNJ10b30WoQFYKf&X-Amz-Signature=645e361c5353d5d58b7f595b8ac1beb7428ea278f51c6fd5d55a83975628af14&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667LZS52QT%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T142035Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCCyx0TBGmhylASu72YCYeMvMHtrCprot3QByf0FEpT%2BQIgNo8%2FUxYZKfP45h%2FcC8CySmWnKLvwIJTJshBlPlO4ulUqiAQI6v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDFm5WNm93svovtITgCrcAymw0oXZzj8idtSV8KCTsFMJc8EMLEaI11UL5ydQ65ybuPLtMXy%2F4SI4ZJtq20b46iqoCjvpwXGFouJOfFH4iAR%2B26Pw8tN%2BprMNyMh%2F3mMVqLEA9IBdYjtPEnsPTPS9mU6DP67bvrlc3wTe8z0q71B1aY0CarF1%2FYJ5HdpZpgNUp%2BWOxrNRKPFsO0y6sq1pPPU8I5l7ELYxHhBok7T86ySJtyYT0kFisrd%2BVCt2gzCpDhf%2F6JRKzDwqO%2FOAt1py0z%2B%2BceVRFjl%2BneAp1o03ljEiipYXjxPY0ghxfxIgLCQfln3rS0evg2Vfe0qo%2FNqju88G1jxhGAVLji7tgEeGEIupjutFBuLHQ92y9prNd7C94%2F1XJD2wIv11CxvhU5kgof4Tc%2BitojLQFDoW7Ubggg6rUD3ONVcCoCLlr7oOM9mZpLFg%2BMB9FhVgkqhRLwhkCG8nJfGKg%2FD3HBjC7KlvdFphzrv%2B2vQmoPdT3aBSxnjq1xY5caUKMiZO3gma2MdS6Bk33mIJdzTtyNYUte2xJgRcPOEfdQh4GZqJe7pPAHmjiLtM8yPHJBkIlHRQw5FhrSntOpxHm1sE0%2BPR2wwgY0DmwYiJ5%2BQph9hrMdi2EsXLr%2BHODtMykYTLBI6EMN2U5r0GOqUB2rtV4aWEg7RwnHC8TAjim1ZXPFw2R%2FTrWi2L90p52S48dOJdsELnFuCKDiyuf3C4cNV3YQNsrz92Hpd3eLy2dKuEwYOZJn647Gf%2FIE8wVer2Uqd%2F0Yl4W1dmDixjA0apkb73vIaaKrSKUD6vWAf43R2YkopSM11CvxSzuFPner7wAUc0ngJyNDVcKQQgLTB%2FiLIJ7gcea9quwQNJ10b30WoQFYKf&X-Amz-Signature=63dbc8022c6ed5c7cd06b94de492c5944d7f693f9d3e0a11de50cdba60484dad&X-Amz-SignedHeaders=host&x-id=GetObject)


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

