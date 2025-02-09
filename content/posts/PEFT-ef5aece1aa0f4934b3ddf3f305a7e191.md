---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466Q4RAHGDD%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250209T015118Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEIH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIGZ3X2KC%2F9y%2BExy\
  WW%2FkYhgtUXIGvWT%2Ft88NxRLa5HHfiAiBxbKonTO6sc1GQcot57tYSC7twN8s%2F0JgCwASjyX\
  YqoiqIBAia%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMDpdGvECPvVZ\
  2bpaRKtwDGa8SlFY7ltAcwlHB8faZMy3BCS1NcJNfQ%2BIzn0Gpu6vTNQsDNAy3RSz6mxA85Kgp6a\
  0%2BuJtOWWebMRkchzUhF3IOCGEOAt9g4brONOfsJi934IFWGmCahThokA%2FBk6g6DeUI7%2FHSO\
  871YtgaRa5imjjXgPKINsj4SLbtjsxTIFbmALOj44zR6LuqbxCWkjlZHaS45bRV81srGBYzlUM5gk\
  0Cta%2Bz1mc%2BaoQc19a0oY0p%2Btl5IABF13eOF1AKmpLsjow1TnHvujC5MXGCao%2BdRRiAGjr\
  Bj2OrUs2J8uqnmPO%2FyxWiXsR9TYNVVuHadPeAKBn3WYhdtTOcXe1tMEfo8G0MkC1tRTwzUI%2Bv\
  6UF4CdC1ZRFj1JrsMbP0fmfwG2gOkdiAMdLsWmmye5pPG1oJov9LmjudhXbzI3Icfu2cgD%2F68l0\
  0W9nTFcDp8f8MS8Zm7JVj91L3u%2BlB6G%2FyTUoNhjpXDMODFMqK8akKKc2v0KFezWWVcSPcHnmS\
  SIpcdVu5o40%2FbE3vi33AuN2XSbNoc%2FZrfa8Sbn%2FGpMOYjBX%2Fk%2FbRbzh2NupZjGscn%2\
  FR%2FnyLd88s4qszD2qiLI5y1Yp%2BKZ1qlDzXI%2FBnniTYoXh5CBjDnZ%2BbwnWu6mg%2Byon8w\
  zPSfvQY6pgFJFFMAyM8PLRVnxTPqZhoszRxQkpPiWOnY2QDuF%2FRtP9WAnvZCyos3mDHP3YZXuOr\
  paKNMOfkeu6jad2%2F5A4vVtsRQuxi36GNCMMoCvan4w1tJqjWfy8imk4gFp0HKuLI8pJKFP07Jm1\
  77aIInuHh9seOrJk5JAI5gnswtcq7O%2BBl5s9KG3bknuuhh%2BXi%2F1IziB18IA%2Fzu5pyLHOj\
  3tUq%2B0gg9c8Uf&X-Amz-Signature=7509ef31595b519dd11458bde32213f541b5886704530\
  1c6d1b7afd221914e97&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB46666IWXEDV%2F20250209%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250209T015002Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEIH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIAzMU4rsQ7ceWrjhLv0Jcucg67dXV4PX%2BlI8hpVPCvxtAiEAugb0f%2F5E2NM82jQGkC\
        U7jsrnXPgi3%2FV9Ic%2BeYgtdzhYqiAQImv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAG\
        gw2Mzc0MjMxODM4MDUiDJVDzX0Bg%2FUggtOg5ircAwi3gOyqjuIYcYsV9EQYlKWzAVQ4Oo\
        O1CSI7cTgbu1Vwo6rIL6I5dDAw60jwJjLV8%2FtDKQbeOVU9wT9AZcvCwHUwg%2FllnmfiX\
        KnYduuktPcpI3IhnQMWU3UN67mG1pAtJiqd8UwoFScNFu688faNSqqMU5HzPKq%2BcQulYq\
        i7GDIMKuj4g0wEIIaXE8r4pLoj78K02VHbYQukk9K6azuFlVUCuGzukfnw7515uVMDxOeES\
        PArCur4WYEV61js12K%2F4SwgN8XM8kGu3poYlXCZQyVfCcK3Ki3X89qwDVrrd3RL8045n2\
        NGoJTNuA%2BL05W60yEkC5v0WYOLQJZBX0OGdcXkjSTCZhsHZZUoHn1R4ogK7gygTSTH0o4\
        M98ybtean3bPZFeHBkqe%2FbIFww06jgdsEGQP39%2BlCYNLl4juovAlg0QmMz9vbLmIuzx\
        bC5wEc8i6v3Xgz0dOgOMwR92IQCwXRtlDYSFtdO%2BvkZRSuOLVqUZtjwuPr86On39yWjto\
        DdH1%2FUIr%2F59HCDEcEp3chmFKe2CQaAkXSx8EAe%2BWBl8e5NrJBu5ozGsI%2Fe4HKCJ\
        vheiyxFlGhT1zudVO6TQNXFmdHsbgYLvxkxXVDRoAV4gzyCPdk%2Fr1r4crWcQg7MKP0n70\
        GOqUBXkzBGZD%2BCzr4w0ksJJm%2BdIE%2B5pk%2Bd1ULxINxVFIkPEyXCiU7POV4Hsrm5G\
        bhjOoIofr43H%2Fvv%2FuYsJONJgecwtIL2YuyBfPcfKRoZKki8XvGqRNqFLPoqlw7tn1u3\
        MIwjLrIglidFZETjZaVzd1l2MCqUgHEsdnM3iQ9zNKpXgyA3XiX3OFaSu8Dg4V%2FIJSgxI\
        p%2Fbn9kcHzBD5tjg%2FoU0XD5Wfdz&X-Amz-Signature=4895c157990a213fa6ef5e17\
        2a8dbb07a1d548fbe5fb52c513840ef34206e7d7&X-Amz-SignedHeaders=host&x-id=\
        GetObject"
      expiry_time: "2025-02-09T02:50:02.296Z"
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
UPDATE_TIME: "2025-02-09T01:51:24.058Z"
EXPIRY_TIME: "2025-02-09T02:51:15.483Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666GOPPFSZ%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T015115Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD1FmQV2rpaDqBrGhGjiawoYI8G89Ifol6YfOb%2BTMtdsAIgMVOaV6o6T%2FR7h85yLp1lFc8rM561fLr1Bv5vkQEyCikqiAQImv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDC4WOOmsxWAAfrEW9yrcAw7KCKqopM556r98SYpFblE9gCPdCzr1dAGzNTVpyO1D4n0exoynu380k872QHFKdB5yEb%2BTWQ%2B99snHblJ%2FMXamPZeCNC5hmZnPQumNVTKzoZoJYzan55MCYeXP12vNkV1nm7BPEwoZ%2F3b9aM%2Fwc2EIcXzVZWHHSr01ZhPv2NKPB9yHVaWBEMcyCwC1Njz8x1XqeyzObKCg3v56FHiz6TGOjnoGHNe9frTKU4NFYtajPaNlXZdiX6%2B8wyjZsamxhd8R4qaT5Dx7C%2B5Pm0Frd1Uog2mbPrmZrwJ7o2oVoQUnNdUwEq7v54J%2BFPcqIBWXQnmjMzpzCCBfH3bef%2FoMSvdKVGbvmZDTlyRZia376Rgm2K9ENpfXt0ubUBMhnCs47qTTCSTYVeT%2BXlea5oJKREu5fOB73hyi5mVZoBawJrRsIGS%2F0eB1uFSniqVS9y9IPbzUKXRia1DFfewAYCav%2B1TsPym3Fd1SQPAAneACVJ1TkRjCtH11%2F3afhuQe4VJw7B%2F8RC1cFGRb8Y5hAdD2E%2FsrjuyCrCYxBGK47uq6EWTkw7jsrP%2FNemNtizPXUikMzeEyXaSrf9xBCnxrqeY7hBMvuffi0MGUvlEZi05NtZUw2UT3Qg3Y04DABAlBMMz0n70GOqUBsBfgPy1b6IazjANwChnV4qt37LCkoM%2FNd7iUg7SsFJo0fHRautbdFxsklbrXondIg1XCVrBzu2xMV8Ql2JS0SCIWQPqxgM2LBkNxwcW7n002QonGAlNlJU37iBv6zJ8EUhMIiCKPnGKp%2BQR2O%2B%2B6QlEVDJg3DmNFFX1FeaNyBdpBSVgGmUy53tXCB%2BicTeLBKjE7ruG1WtcMr7dwGvwgoSMe4GwW&X-Amz-Signature=7d208c5b243982061cf8b2acc0f1b7a62381f2bb29ff71c7be1c640a5b52b412&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666GOPPFSZ%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T015115Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD1FmQV2rpaDqBrGhGjiawoYI8G89Ifol6YfOb%2BTMtdsAIgMVOaV6o6T%2FR7h85yLp1lFc8rM561fLr1Bv5vkQEyCikqiAQImv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDC4WOOmsxWAAfrEW9yrcAw7KCKqopM556r98SYpFblE9gCPdCzr1dAGzNTVpyO1D4n0exoynu380k872QHFKdB5yEb%2BTWQ%2B99snHblJ%2FMXamPZeCNC5hmZnPQumNVTKzoZoJYzan55MCYeXP12vNkV1nm7BPEwoZ%2F3b9aM%2Fwc2EIcXzVZWHHSr01ZhPv2NKPB9yHVaWBEMcyCwC1Njz8x1XqeyzObKCg3v56FHiz6TGOjnoGHNe9frTKU4NFYtajPaNlXZdiX6%2B8wyjZsamxhd8R4qaT5Dx7C%2B5Pm0Frd1Uog2mbPrmZrwJ7o2oVoQUnNdUwEq7v54J%2BFPcqIBWXQnmjMzpzCCBfH3bef%2FoMSvdKVGbvmZDTlyRZia376Rgm2K9ENpfXt0ubUBMhnCs47qTTCSTYVeT%2BXlea5oJKREu5fOB73hyi5mVZoBawJrRsIGS%2F0eB1uFSniqVS9y9IPbzUKXRia1DFfewAYCav%2B1TsPym3Fd1SQPAAneACVJ1TkRjCtH11%2F3afhuQe4VJw7B%2F8RC1cFGRb8Y5hAdD2E%2FsrjuyCrCYxBGK47uq6EWTkw7jsrP%2FNemNtizPXUikMzeEyXaSrf9xBCnxrqeY7hBMvuffi0MGUvlEZi05NtZUw2UT3Qg3Y04DABAlBMMz0n70GOqUBsBfgPy1b6IazjANwChnV4qt37LCkoM%2FNd7iUg7SsFJo0fHRautbdFxsklbrXondIg1XCVrBzu2xMV8Ql2JS0SCIWQPqxgM2LBkNxwcW7n002QonGAlNlJU37iBv6zJ8EUhMIiCKPnGKp%2BQR2O%2B%2B6QlEVDJg3DmNFFX1FeaNyBdpBSVgGmUy53tXCB%2BicTeLBKjE7ruG1WtcMr7dwGvwgoSMe4GwW&X-Amz-Signature=57517c4a15fd025c34af292e4b95c5b966594832c04488a19b4df85594244ff6&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666GOPPFSZ%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T015115Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD1FmQV2rpaDqBrGhGjiawoYI8G89Ifol6YfOb%2BTMtdsAIgMVOaV6o6T%2FR7h85yLp1lFc8rM561fLr1Bv5vkQEyCikqiAQImv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDC4WOOmsxWAAfrEW9yrcAw7KCKqopM556r98SYpFblE9gCPdCzr1dAGzNTVpyO1D4n0exoynu380k872QHFKdB5yEb%2BTWQ%2B99snHblJ%2FMXamPZeCNC5hmZnPQumNVTKzoZoJYzan55MCYeXP12vNkV1nm7BPEwoZ%2F3b9aM%2Fwc2EIcXzVZWHHSr01ZhPv2NKPB9yHVaWBEMcyCwC1Njz8x1XqeyzObKCg3v56FHiz6TGOjnoGHNe9frTKU4NFYtajPaNlXZdiX6%2B8wyjZsamxhd8R4qaT5Dx7C%2B5Pm0Frd1Uog2mbPrmZrwJ7o2oVoQUnNdUwEq7v54J%2BFPcqIBWXQnmjMzpzCCBfH3bef%2FoMSvdKVGbvmZDTlyRZia376Rgm2K9ENpfXt0ubUBMhnCs47qTTCSTYVeT%2BXlea5oJKREu5fOB73hyi5mVZoBawJrRsIGS%2F0eB1uFSniqVS9y9IPbzUKXRia1DFfewAYCav%2B1TsPym3Fd1SQPAAneACVJ1TkRjCtH11%2F3afhuQe4VJw7B%2F8RC1cFGRb8Y5hAdD2E%2FsrjuyCrCYxBGK47uq6EWTkw7jsrP%2FNemNtizPXUikMzeEyXaSrf9xBCnxrqeY7hBMvuffi0MGUvlEZi05NtZUw2UT3Qg3Y04DABAlBMMz0n70GOqUBsBfgPy1b6IazjANwChnV4qt37LCkoM%2FNd7iUg7SsFJo0fHRautbdFxsklbrXondIg1XCVrBzu2xMV8Ql2JS0SCIWQPqxgM2LBkNxwcW7n002QonGAlNlJU37iBv6zJ8EUhMIiCKPnGKp%2BQR2O%2B%2B6QlEVDJg3DmNFFX1FeaNyBdpBSVgGmUy53tXCB%2BicTeLBKjE7ruG1WtcMr7dwGvwgoSMe4GwW&X-Amz-Signature=54b68818efa42f715f7df80d77f498ec5a1ec915a4ccc75aeece358372cf4721&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666GOPPFSZ%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T015115Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD1FmQV2rpaDqBrGhGjiawoYI8G89Ifol6YfOb%2BTMtdsAIgMVOaV6o6T%2FR7h85yLp1lFc8rM561fLr1Bv5vkQEyCikqiAQImv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDC4WOOmsxWAAfrEW9yrcAw7KCKqopM556r98SYpFblE9gCPdCzr1dAGzNTVpyO1D4n0exoynu380k872QHFKdB5yEb%2BTWQ%2B99snHblJ%2FMXamPZeCNC5hmZnPQumNVTKzoZoJYzan55MCYeXP12vNkV1nm7BPEwoZ%2F3b9aM%2Fwc2EIcXzVZWHHSr01ZhPv2NKPB9yHVaWBEMcyCwC1Njz8x1XqeyzObKCg3v56FHiz6TGOjnoGHNe9frTKU4NFYtajPaNlXZdiX6%2B8wyjZsamxhd8R4qaT5Dx7C%2B5Pm0Frd1Uog2mbPrmZrwJ7o2oVoQUnNdUwEq7v54J%2BFPcqIBWXQnmjMzpzCCBfH3bef%2FoMSvdKVGbvmZDTlyRZia376Rgm2K9ENpfXt0ubUBMhnCs47qTTCSTYVeT%2BXlea5oJKREu5fOB73hyi5mVZoBawJrRsIGS%2F0eB1uFSniqVS9y9IPbzUKXRia1DFfewAYCav%2B1TsPym3Fd1SQPAAneACVJ1TkRjCtH11%2F3afhuQe4VJw7B%2F8RC1cFGRb8Y5hAdD2E%2FsrjuyCrCYxBGK47uq6EWTkw7jsrP%2FNemNtizPXUikMzeEyXaSrf9xBCnxrqeY7hBMvuffi0MGUvlEZi05NtZUw2UT3Qg3Y04DABAlBMMz0n70GOqUBsBfgPy1b6IazjANwChnV4qt37LCkoM%2FNd7iUg7SsFJo0fHRautbdFxsklbrXondIg1XCVrBzu2xMV8Ql2JS0SCIWQPqxgM2LBkNxwcW7n002QonGAlNlJU37iBv6zJ8EUhMIiCKPnGKp%2BQR2O%2B%2B6QlEVDJg3DmNFFX1FeaNyBdpBSVgGmUy53tXCB%2BicTeLBKjE7ruG1WtcMr7dwGvwgoSMe4GwW&X-Amz-Signature=fa6972026dd81cac22b414ac3d516c56e3963b1a1e0e121f280e7c69871f0ca1&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666GOPPFSZ%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T015115Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD1FmQV2rpaDqBrGhGjiawoYI8G89Ifol6YfOb%2BTMtdsAIgMVOaV6o6T%2FR7h85yLp1lFc8rM561fLr1Bv5vkQEyCikqiAQImv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDC4WOOmsxWAAfrEW9yrcAw7KCKqopM556r98SYpFblE9gCPdCzr1dAGzNTVpyO1D4n0exoynu380k872QHFKdB5yEb%2BTWQ%2B99snHblJ%2FMXamPZeCNC5hmZnPQumNVTKzoZoJYzan55MCYeXP12vNkV1nm7BPEwoZ%2F3b9aM%2Fwc2EIcXzVZWHHSr01ZhPv2NKPB9yHVaWBEMcyCwC1Njz8x1XqeyzObKCg3v56FHiz6TGOjnoGHNe9frTKU4NFYtajPaNlXZdiX6%2B8wyjZsamxhd8R4qaT5Dx7C%2B5Pm0Frd1Uog2mbPrmZrwJ7o2oVoQUnNdUwEq7v54J%2BFPcqIBWXQnmjMzpzCCBfH3bef%2FoMSvdKVGbvmZDTlyRZia376Rgm2K9ENpfXt0ubUBMhnCs47qTTCSTYVeT%2BXlea5oJKREu5fOB73hyi5mVZoBawJrRsIGS%2F0eB1uFSniqVS9y9IPbzUKXRia1DFfewAYCav%2B1TsPym3Fd1SQPAAneACVJ1TkRjCtH11%2F3afhuQe4VJw7B%2F8RC1cFGRb8Y5hAdD2E%2FsrjuyCrCYxBGK47uq6EWTkw7jsrP%2FNemNtizPXUikMzeEyXaSrf9xBCnxrqeY7hBMvuffi0MGUvlEZi05NtZUw2UT3Qg3Y04DABAlBMMz0n70GOqUBsBfgPy1b6IazjANwChnV4qt37LCkoM%2FNd7iUg7SsFJo0fHRautbdFxsklbrXondIg1XCVrBzu2xMV8Ql2JS0SCIWQPqxgM2LBkNxwcW7n002QonGAlNlJU37iBv6zJ8EUhMIiCKPnGKp%2BQR2O%2B%2B6QlEVDJg3DmNFFX1FeaNyBdpBSVgGmUy53tXCB%2BicTeLBKjE7ruG1WtcMr7dwGvwgoSMe4GwW&X-Amz-Signature=d3c9056d08b2a19cd2d4b9467a4b90443ebb7628427d6d72bb096e40cc6a6a7d&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RKOEXJPQ%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T015117Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD7kPacYmWBwbrbYll%2BXsAoGzmNzYPDe%2B6lzWM8nK6c5AIgV%2Fij7DqtRrsBCZvEIEZyHoJWO10L2Kqc8UX%2FG4x6%2FhwqiAQImv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNuTgRzBaeBZonX3UCrcA00wR31iwzro0vzr1c55NU4Zrmsfsl4a4OxrKi%2BH9knh2FCpa%2BiOK0XKk0I6KsOL%2BtJrJTGkZm2MroVmzxIdnpBjxZ6hWBGNpfHfYzYw%2BEKClQBv7hbGBWN8SZkcMuUmXloRPIgz%2FpGeHmsXs2yzwhqj0QevdGSS6BiT6gj70acN7xua46hLKPHJE%2BJIrXBbMtQRC0o52LeoUQwvMViJd71kitB%2B6uq4NOnUB8H4kOlYUjpJrcHf2dOEAM1cxJA%2BmhJMSeWzQ%2FTZ92MAsUtq5OH5Lx0UL0s6EwyfYivpHuHTPUf13CMRIum1cBAr5Z8XSB%2FKOIbUWnyk1gWv%2B7GcvQS2zOrqrsqWyDM5GqxSJc9Dw30VB8gNGW5%2BNpvpIlAqz7h9OGFGjE%2Fr%2BIQfO%2BfLUQ1GYW5P34DThzA5%2FiwEztEw%2Bza3TvqycQ8F3Kzm0KtN5Uw8GKLOwTj6gQEMhRb%2FPJcOZUi%2BAxvKzi3iYtAi7DUigQvoLNFPIFodDLpjo49eoU8yu4qspwvGf3ZRGvhnot7cXxrDWNV3dtE%2BeQPkyThTdaMFpI4GsY3EpWeas1iqZ4FaA%2BDJOP0HrMmY%2FDHS7i52Dak81Nvl0ds3UaJsuGWfzPL9uaMXgwtxEgQaMPr0n70GOqUBslx6uvTtwNaW1tejR6WuMISgZZr%2BgCCkqKAO%2FhZbbE3%2B6CdSMMA6QVCElLJhRWQTn6mTUpPCGzOYNXkAZyq6nIZL3R1O5MtfaLi2vZh%2F4dHOJi63%2B15A2qalaz%2F8fraQZHrtwuhoK3Vj3xiuiN3kmSTTZILt58uEkiWMCQVu0%2FcgqKf9ENy6%2Fdyao%2BVE1%2B5s1764K5WZsJLf6FLCROOrqdVSpBOJ&X-Amz-Signature=d312215043c300a074e5d1b415a6171d69708c3d20cd1d05a594b30c96585440&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XE5KEAZL%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T015118Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIBwLQa%2FfMgQbqFj7MQRAqNJK1ER5uXriV%2FCPPVST3CUSAiB3YX1x6jG%2Bqk3GK%2Bxe1RhMRI1WnkrFRwZd%2FLVQ3JxaXyqIBAia%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMtsM23zffC1gURd%2BSKtwDpj8z85EiCWX2pngBoq7gA9ZQnMKxLi1Y64GY7OTqV2e1D7elLG8TwarW6N6kavpWInLdTGYfxMJ82QsYDiIH4IWrd53Ea8zRLBkeUp97rMOeo54Oq96wjfrJt21fwfbRN64ZjuTDeNLhiUZqpDq9yEYsFyaCOjHMkvgBQ%2FO%2F48nbbNACladN2a6GD0KoyedT6eZlZmbsKNHtEkI4NIsSgFHR29sZTXUqeF61tgGd7%2B833zLby1kA16sk0c8ruqZ65RnYrDKtYjR4DPMXt9yzfAcQsS5Rvo%2BWBiuTe3damVy6yh1HDxOykO7FsnTWv4cS7rzlKL0zh5TTQOZHZh523iiNT4KNjp9kYaQP68Y8AeS66JIT52v75lF%2FsR1TVdxIP20p6VQ5Yxn4VE8QuDRe541I8Sbk8T1XbWpdCJlsNLxD5uIfmz%2B2wuScsh%2Bv4FoS00S87FZDmOkrVoPBit7mCx0e7eK%2FBr1KA5gHX73Ufih0dm42IDVdITMm%2BKmwysF0GX39oWO4jvhQSJXFtvc4yPHAKDtdiz7zCYpHggzJANbUKn1CZWreQbaD6TupWJfwmv84HHDha4uJMJWlT%2FY%2FXKMJ%2BtToeeidUnNB4oCAtMEvqh2mKAcGHI6uqoUw8PSfvQY6pgHYZmdp%2FTEyXGZh49h1pf9Eh8BTR3jcSd%2BJLAQhmO3sGF%2B7uTKrgfkOum9VPn9s%2FR2cqz8GhP%2BHCaEgI%2Fy%2B%2Bjvq52qOnt2bkyPM%2F07%2BogOkLsZHQtWN0RwwBYEBBTCXB9NqY%2FVlwd%2BxmMsbISLZ9RKASMq5zwQwrp0KWK7hzuuIu%2Bkpzk%2BYbD5MsBPEyOHvEezMzeuZw8dWmPjt8Baky0kEnllYl1yR&X-Amz-Signature=bd5c6ac7a41441f63e4692ebb2f10b4aa30301e645120fe5144e5d5d6a1dd7e5&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666GOPPFSZ%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T015115Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD1FmQV2rpaDqBrGhGjiawoYI8G89Ifol6YfOb%2BTMtdsAIgMVOaV6o6T%2FR7h85yLp1lFc8rM561fLr1Bv5vkQEyCikqiAQImv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDC4WOOmsxWAAfrEW9yrcAw7KCKqopM556r98SYpFblE9gCPdCzr1dAGzNTVpyO1D4n0exoynu380k872QHFKdB5yEb%2BTWQ%2B99snHblJ%2FMXamPZeCNC5hmZnPQumNVTKzoZoJYzan55MCYeXP12vNkV1nm7BPEwoZ%2F3b9aM%2Fwc2EIcXzVZWHHSr01ZhPv2NKPB9yHVaWBEMcyCwC1Njz8x1XqeyzObKCg3v56FHiz6TGOjnoGHNe9frTKU4NFYtajPaNlXZdiX6%2B8wyjZsamxhd8R4qaT5Dx7C%2B5Pm0Frd1Uog2mbPrmZrwJ7o2oVoQUnNdUwEq7v54J%2BFPcqIBWXQnmjMzpzCCBfH3bef%2FoMSvdKVGbvmZDTlyRZia376Rgm2K9ENpfXt0ubUBMhnCs47qTTCSTYVeT%2BXlea5oJKREu5fOB73hyi5mVZoBawJrRsIGS%2F0eB1uFSniqVS9y9IPbzUKXRia1DFfewAYCav%2B1TsPym3Fd1SQPAAneACVJ1TkRjCtH11%2F3afhuQe4VJw7B%2F8RC1cFGRb8Y5hAdD2E%2FsrjuyCrCYxBGK47uq6EWTkw7jsrP%2FNemNtizPXUikMzeEyXaSrf9xBCnxrqeY7hBMvuffi0MGUvlEZi05NtZUw2UT3Qg3Y04DABAlBMMz0n70GOqUBsBfgPy1b6IazjANwChnV4qt37LCkoM%2FNd7iUg7SsFJo0fHRautbdFxsklbrXondIg1XCVrBzu2xMV8Ql2JS0SCIWQPqxgM2LBkNxwcW7n002QonGAlNlJU37iBv6zJ8EUhMIiCKPnGKp%2BQR2O%2B%2B6QlEVDJg3DmNFFX1FeaNyBdpBSVgGmUy53tXCB%2BicTeLBKjE7ruG1WtcMr7dwGvwgoSMe4GwW&X-Amz-Signature=4f821317a477de64166acf3d89006b296dd7be6f7d29df169418b9ccb6b72b7b&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666GOPPFSZ%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T015115Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD1FmQV2rpaDqBrGhGjiawoYI8G89Ifol6YfOb%2BTMtdsAIgMVOaV6o6T%2FR7h85yLp1lFc8rM561fLr1Bv5vkQEyCikqiAQImv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDC4WOOmsxWAAfrEW9yrcAw7KCKqopM556r98SYpFblE9gCPdCzr1dAGzNTVpyO1D4n0exoynu380k872QHFKdB5yEb%2BTWQ%2B99snHblJ%2FMXamPZeCNC5hmZnPQumNVTKzoZoJYzan55MCYeXP12vNkV1nm7BPEwoZ%2F3b9aM%2Fwc2EIcXzVZWHHSr01ZhPv2NKPB9yHVaWBEMcyCwC1Njz8x1XqeyzObKCg3v56FHiz6TGOjnoGHNe9frTKU4NFYtajPaNlXZdiX6%2B8wyjZsamxhd8R4qaT5Dx7C%2B5Pm0Frd1Uog2mbPrmZrwJ7o2oVoQUnNdUwEq7v54J%2BFPcqIBWXQnmjMzpzCCBfH3bef%2FoMSvdKVGbvmZDTlyRZia376Rgm2K9ENpfXt0ubUBMhnCs47qTTCSTYVeT%2BXlea5oJKREu5fOB73hyi5mVZoBawJrRsIGS%2F0eB1uFSniqVS9y9IPbzUKXRia1DFfewAYCav%2B1TsPym3Fd1SQPAAneACVJ1TkRjCtH11%2F3afhuQe4VJw7B%2F8RC1cFGRb8Y5hAdD2E%2FsrjuyCrCYxBGK47uq6EWTkw7jsrP%2FNemNtizPXUikMzeEyXaSrf9xBCnxrqeY7hBMvuffi0MGUvlEZi05NtZUw2UT3Qg3Y04DABAlBMMz0n70GOqUBsBfgPy1b6IazjANwChnV4qt37LCkoM%2FNd7iUg7SsFJo0fHRautbdFxsklbrXondIg1XCVrBzu2xMV8Ql2JS0SCIWQPqxgM2LBkNxwcW7n002QonGAlNlJU37iBv6zJ8EUhMIiCKPnGKp%2BQR2O%2B%2B6QlEVDJg3DmNFFX1FeaNyBdpBSVgGmUy53tXCB%2BicTeLBKjE7ruG1WtcMr7dwGvwgoSMe4GwW&X-Amz-Signature=3984abc41e9c913f1f6cc3f4ae5677b3ff0f719ed3dfbe4050da2663992f0c4f&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666GOPPFSZ%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T015115Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD1FmQV2rpaDqBrGhGjiawoYI8G89Ifol6YfOb%2BTMtdsAIgMVOaV6o6T%2FR7h85yLp1lFc8rM561fLr1Bv5vkQEyCikqiAQImv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDC4WOOmsxWAAfrEW9yrcAw7KCKqopM556r98SYpFblE9gCPdCzr1dAGzNTVpyO1D4n0exoynu380k872QHFKdB5yEb%2BTWQ%2B99snHblJ%2FMXamPZeCNC5hmZnPQumNVTKzoZoJYzan55MCYeXP12vNkV1nm7BPEwoZ%2F3b9aM%2Fwc2EIcXzVZWHHSr01ZhPv2NKPB9yHVaWBEMcyCwC1Njz8x1XqeyzObKCg3v56FHiz6TGOjnoGHNe9frTKU4NFYtajPaNlXZdiX6%2B8wyjZsamxhd8R4qaT5Dx7C%2B5Pm0Frd1Uog2mbPrmZrwJ7o2oVoQUnNdUwEq7v54J%2BFPcqIBWXQnmjMzpzCCBfH3bef%2FoMSvdKVGbvmZDTlyRZia376Rgm2K9ENpfXt0ubUBMhnCs47qTTCSTYVeT%2BXlea5oJKREu5fOB73hyi5mVZoBawJrRsIGS%2F0eB1uFSniqVS9y9IPbzUKXRia1DFfewAYCav%2B1TsPym3Fd1SQPAAneACVJ1TkRjCtH11%2F3afhuQe4VJw7B%2F8RC1cFGRb8Y5hAdD2E%2FsrjuyCrCYxBGK47uq6EWTkw7jsrP%2FNemNtizPXUikMzeEyXaSrf9xBCnxrqeY7hBMvuffi0MGUvlEZi05NtZUw2UT3Qg3Y04DABAlBMMz0n70GOqUBsBfgPy1b6IazjANwChnV4qt37LCkoM%2FNd7iUg7SsFJo0fHRautbdFxsklbrXondIg1XCVrBzu2xMV8Ql2JS0SCIWQPqxgM2LBkNxwcW7n002QonGAlNlJU37iBv6zJ8EUhMIiCKPnGKp%2BQR2O%2B%2B6QlEVDJg3DmNFFX1FeaNyBdpBSVgGmUy53tXCB%2BicTeLBKjE7ruG1WtcMr7dwGvwgoSMe4GwW&X-Amz-Signature=670f56cbc8fa475810e9baa663fab870caf351b391ddfa008cb1de6e3de5f35f&X-Amz-SignedHeaders=host&x-id=GetObject)


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

