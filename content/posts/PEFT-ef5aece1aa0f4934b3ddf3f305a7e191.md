---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466VIMVILNC%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250222T092313Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDqlkdXx2ZIvskOGa8\
  FtzQABJ5qYv2LUCt9FF9wLjq2%2BwIgYry3gOaidSQIUt1MNDRrpQxzH07%2FXhsM7kn9QT6cJwQq\
  iAQI5%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDBMVtIA54UzFP%2\
  BDvXCrcA4cuFLsImT%2BCw%2FpsiKA1SN7%2FxE8pu55kyMtTGCNT2F4tvKPTrAnM54FZe69x698N\
  WppsrCqXCdv4qBzqCanFQshxewDVI0BhKoECwfLVgrNeCJqZqDUEYzIb0E5l7fPjkIqV%2FLe1xeG\
  pt%2B4oHN41HFKyD6DIkRijM%2BQFPNSASFnOq9ZSusBkAtGT6SXDqGk5Zd8O%2ByzIDcK3l4f0km\
  JFe3UXEp%2F%2FQYFa%2FVICzIEg5lPtANQK8zZ82qRTqKBtrlMg95lHKizced1pim7CN23cy3tfC\
  mnCi%2F2GKLxsooQSQQIAvSEIPnDOoU%2Fc%2BT1BdVLsG%2BJiE1xVAJHBVGrmWEK9sskkL%2Bvd\
  XGwhfW3ArNQ75M%2FTqYWublOBXG%2B16HfQ2Mco6u8VWkiyigQ95lJw%2FU1YUYexQg7rIMk7fKF\
  dhm6lAlt0rRr9qzRZEtbVoAmrCt%2BE1%2BetXeB%2F0dk%2FmpydlJUydq4tb8BHeX1QnKIZ8596\
  %2BHEBIyTbYIKS1FyijfpjkmJPHhOsrOO%2F6yRy4QDNkeMDi7lYuXdcMQxxQvb4CSYbSaMZdpGxX\
  mVybSeC9iVoieNN4%2BvZPwHIhM9Iph1nga3i0zaUXs9wPTBGSKdF5k8Kn6QMrdxnRuiSPqirhmuM\
  MMPH5b0GOqUBbHYASUSMAJ9oig2D2ejdAaw6At0S7mz%2B8mNLoiNuNmv%2BeRCRgxb2fXFuWvYBs\
  gI4bzE5I%2FmO01sxe%2FwphHVSUriJN7DNHVMSss35jVvJuGqwuL2vEh%2B0o3hX2jSfA9DD4lgp\
  aFAgZztxgCNKjpRgCiBuLzUUSMCeV9hu7ePpuBxO8fDIoBSMTAlZYlvyataotLfXEqZur1MRp%2Bs\
  TKRlvFaqpFyf%2B&X-Amz-Signature=077e9e733e82e2d77ed3ada729c512ce9a59569573498\
  88d5488cb6c8bc877f4&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4666M45EETP%2F20250222%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250222T092150Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEMH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQ\
        CIAXHqajWEuqxJkZVpD5SC%2FC2SS8ma0ommb4CqVJxh23OAiBXMqBVHyhJ6CTM%2Fj1%2B\
        nGcMT7Bo6xs9FpDZd4fvYwictyqIBAjq%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDY\
        zNzQyMzE4MzgwNSIMY3MP9Lj5od1Nf1OCKtwDnG0M9JSAyAisb6000QGlPrLmNp4XguaGHk\
        2RcSgcMTE2I25YVAjt56lfOMDWmbqYBYkwMDj5fcYF7OAHyEF9OrHyFzaCQVF05IOozvLJ%\
        2BN2Nss50rK9SF7sWm3JJ%2F11IfCAHQ5yHoLMD2WhaVQ1sVpCMk1Z5OEA2w8%2FWZnw%2B\
        9Jfm7hEBH4%2FzL3t5TkaTE6A8hw6PB9Xbu7yIQQIS1Q4dmRTIzQ4zSUz0nH4feYTGl%2Bs\
        zJ6bo4eL4%2FhgnaWU3RFdbrBHzPnhV5SLoBm%2FBUFlMiycA6FOWg02Dv0Od%2BvrlK1XS\
        JSC9tB3c4vnNYvumBtEmOe1PcyG0196sC2K9BxTVRyQbz8De4aGc6KMLWagUQpiqA5t1KtO\
        0gkG%2B3TBY%2FYdiTCgtik%2BbjWRiKJDkfEjZZ6H%2BB222F9B92QQIOmWBlQnMjP8O%2\
        B6fgh10JxoOBy8zgoTxPiD1RIKdzbN7TInqmdQ%2FFEgKGiHS%2F%2FXvgo%2BAVnR90GvU\
        HTdwKxunsNE4hLXBGbv%2FnG25yf1jSk89%2FJklACLIi4duZ3ZVhWxAvXZ0SgnHHDE%2Fo\
        prNcvCzutV6RZG%2FdZxClQ%2BKwRKo92V7yURhKNugUV7U6%2BbKCqjAEtugM%2Bd1yUdO\
        r2fLvX8BTiQkw0ZjmvQY6pgFTLRbTa3eZ6mIRBtrJvRFx%2BBSWrePMTG2fVhRlvetwJSR1\
        Yh%2BIXjo%2BAR32jCFJv2yhKQeXkWFAWUY1rby2imoJzJ3lIaU3G1ZwFzbJZd%2FE%2FfB\
        ZAukpNLOBDhSIMorTUIuNaCCNzteLZMzIwBQ3TjeOdywHE48c1W2F1rTBGWQoeio5vPtkCA\
        5fd%2Fp6yaDWLjVOUb4E2ZQQQOE00RFiVSOFrBuC7Wv0&X-Amz-Signature=e31ffe6095\
        cea9565fde53e348073165c4e533dcac00b28d2a06bc0fe426a4dc&X-Amz-SignedHead\
        ers=host&x-id=GetObject"
      expiry_time: "2025-02-22T10:21:50.260Z"
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
UPDATE_TIME: "2025-02-22T09:23:17.667Z"
EXPIRY_TIME: "2025-02-22T10:23:12.154Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664JKVHSML%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T092312Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDS7s9hZEpwqBw4LIzqPg96IEXZc%2B%2Fjzsey5S0PC7gUhAIhAMWk8C2urEr8tj4lafyFnUI4cLK%2FBTprK56B45CbYCinKogECOf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwbWOLpQA8SpA9F8cIq3ANk9tWIFgtRPpzCPDAWR3jquAtmaI36WIO4M8QdtJvl45vzRK2yhC0dZeSi1F5rNdJVrMay0XHJmX5gZ2B8eiem4R%2Bzcxb0UAbORX3neUg%2Fb%2BZOaW94xI6khzfI6ttU6exWbz%2BbE9rDR4UmQGVkNJv9PK7jndHL9Tot%2FYD66UzZdcQ0T09q8aqvxfNJrApix9Z7cqeVUblpYsd0KxxQlMsQD49qobPVTl%2FVySbukAO7AUE39Yusog7IkBOchXXm4MY0B7FbmydnY59hOrtHQQKNB6x3lPpm52wqemQ99d6n0bEdlyW8zrZOcGwNonniwcE0P2iJscuhv8Xlt5W6Cj2Az%2BKtbx5Z6kykB28Hj1S5Rw4aDoTxnk8utQxTgR6Tcu5AUNJN53xvWzLw1LZ2QtilLhG2Or2KXsEs%2FWIfN5r7Zn9lt2sZCyLdsrSh3CNnTZqHXvIdTDFOBh2DrihoCP4g1B%2FeAbPDw%2BZ%2BGSu6ZzoYev%2FWTJBkvUkmJu3DTNVpZqDTsTBAAJfFapZUOMOhxz47VdgpaG4iOtP2VgBqlpbDFO%2BWgcXnV4D6wt2yOjp1cG7BWpTz30%2BK4nrxKBsJwds4F1RPKru31mFoRsgX5fRb06zS1Mnuk905Vn8S8zDBx%2BW9BjqkAQDH1E%2BGSUJ%2FW1gQUuekF2HOxnO8f6anLsaT1wCOVWVSPqZZiEh%2B4mBaP20FYIUMh1ok%2B7qoqOJKrqCr4RVvTGpgbet%2BCXR3dVYmaEiXM0SAXCJUMz9nu9HlV4yDCNEc3J%2BmVM9KdP8qwy7PwkXCLfbpyjB6B0tj129XD1KjfV85yArRMXpmUsTV132%2FtMjbaUhbIaDmN0XYy%2Fj7qFLR71i%2Fjz4j&X-Amz-Signature=99cd8402cd2f20313c530da45cd8d25258a77e751885547a2d9019d9f67a2b62&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664JKVHSML%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T092312Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDS7s9hZEpwqBw4LIzqPg96IEXZc%2B%2Fjzsey5S0PC7gUhAIhAMWk8C2urEr8tj4lafyFnUI4cLK%2FBTprK56B45CbYCinKogECOf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwbWOLpQA8SpA9F8cIq3ANk9tWIFgtRPpzCPDAWR3jquAtmaI36WIO4M8QdtJvl45vzRK2yhC0dZeSi1F5rNdJVrMay0XHJmX5gZ2B8eiem4R%2Bzcxb0UAbORX3neUg%2Fb%2BZOaW94xI6khzfI6ttU6exWbz%2BbE9rDR4UmQGVkNJv9PK7jndHL9Tot%2FYD66UzZdcQ0T09q8aqvxfNJrApix9Z7cqeVUblpYsd0KxxQlMsQD49qobPVTl%2FVySbukAO7AUE39Yusog7IkBOchXXm4MY0B7FbmydnY59hOrtHQQKNB6x3lPpm52wqemQ99d6n0bEdlyW8zrZOcGwNonniwcE0P2iJscuhv8Xlt5W6Cj2Az%2BKtbx5Z6kykB28Hj1S5Rw4aDoTxnk8utQxTgR6Tcu5AUNJN53xvWzLw1LZ2QtilLhG2Or2KXsEs%2FWIfN5r7Zn9lt2sZCyLdsrSh3CNnTZqHXvIdTDFOBh2DrihoCP4g1B%2FeAbPDw%2BZ%2BGSu6ZzoYev%2FWTJBkvUkmJu3DTNVpZqDTsTBAAJfFapZUOMOhxz47VdgpaG4iOtP2VgBqlpbDFO%2BWgcXnV4D6wt2yOjp1cG7BWpTz30%2BK4nrxKBsJwds4F1RPKru31mFoRsgX5fRb06zS1Mnuk905Vn8S8zDBx%2BW9BjqkAQDH1E%2BGSUJ%2FW1gQUuekF2HOxnO8f6anLsaT1wCOVWVSPqZZiEh%2B4mBaP20FYIUMh1ok%2B7qoqOJKrqCr4RVvTGpgbet%2BCXR3dVYmaEiXM0SAXCJUMz9nu9HlV4yDCNEc3J%2BmVM9KdP8qwy7PwkXCLfbpyjB6B0tj129XD1KjfV85yArRMXpmUsTV132%2FtMjbaUhbIaDmN0XYy%2Fj7qFLR71i%2Fjz4j&X-Amz-Signature=42c637dc402c80122389e8904c3f192f19773756b1524b1bff33b4c80d4d0c97&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664JKVHSML%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T092312Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDS7s9hZEpwqBw4LIzqPg96IEXZc%2B%2Fjzsey5S0PC7gUhAIhAMWk8C2urEr8tj4lafyFnUI4cLK%2FBTprK56B45CbYCinKogECOf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwbWOLpQA8SpA9F8cIq3ANk9tWIFgtRPpzCPDAWR3jquAtmaI36WIO4M8QdtJvl45vzRK2yhC0dZeSi1F5rNdJVrMay0XHJmX5gZ2B8eiem4R%2Bzcxb0UAbORX3neUg%2Fb%2BZOaW94xI6khzfI6ttU6exWbz%2BbE9rDR4UmQGVkNJv9PK7jndHL9Tot%2FYD66UzZdcQ0T09q8aqvxfNJrApix9Z7cqeVUblpYsd0KxxQlMsQD49qobPVTl%2FVySbukAO7AUE39Yusog7IkBOchXXm4MY0B7FbmydnY59hOrtHQQKNB6x3lPpm52wqemQ99d6n0bEdlyW8zrZOcGwNonniwcE0P2iJscuhv8Xlt5W6Cj2Az%2BKtbx5Z6kykB28Hj1S5Rw4aDoTxnk8utQxTgR6Tcu5AUNJN53xvWzLw1LZ2QtilLhG2Or2KXsEs%2FWIfN5r7Zn9lt2sZCyLdsrSh3CNnTZqHXvIdTDFOBh2DrihoCP4g1B%2FeAbPDw%2BZ%2BGSu6ZzoYev%2FWTJBkvUkmJu3DTNVpZqDTsTBAAJfFapZUOMOhxz47VdgpaG4iOtP2VgBqlpbDFO%2BWgcXnV4D6wt2yOjp1cG7BWpTz30%2BK4nrxKBsJwds4F1RPKru31mFoRsgX5fRb06zS1Mnuk905Vn8S8zDBx%2BW9BjqkAQDH1E%2BGSUJ%2FW1gQUuekF2HOxnO8f6anLsaT1wCOVWVSPqZZiEh%2B4mBaP20FYIUMh1ok%2B7qoqOJKrqCr4RVvTGpgbet%2BCXR3dVYmaEiXM0SAXCJUMz9nu9HlV4yDCNEc3J%2BmVM9KdP8qwy7PwkXCLfbpyjB6B0tj129XD1KjfV85yArRMXpmUsTV132%2FtMjbaUhbIaDmN0XYy%2Fj7qFLR71i%2Fjz4j&X-Amz-Signature=b6bf277c41abdb9e648fe86cc3a60e1244c079419db1c308e0cff899bc0a6572&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664JKVHSML%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T092312Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDS7s9hZEpwqBw4LIzqPg96IEXZc%2B%2Fjzsey5S0PC7gUhAIhAMWk8C2urEr8tj4lafyFnUI4cLK%2FBTprK56B45CbYCinKogECOf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwbWOLpQA8SpA9F8cIq3ANk9tWIFgtRPpzCPDAWR3jquAtmaI36WIO4M8QdtJvl45vzRK2yhC0dZeSi1F5rNdJVrMay0XHJmX5gZ2B8eiem4R%2Bzcxb0UAbORX3neUg%2Fb%2BZOaW94xI6khzfI6ttU6exWbz%2BbE9rDR4UmQGVkNJv9PK7jndHL9Tot%2FYD66UzZdcQ0T09q8aqvxfNJrApix9Z7cqeVUblpYsd0KxxQlMsQD49qobPVTl%2FVySbukAO7AUE39Yusog7IkBOchXXm4MY0B7FbmydnY59hOrtHQQKNB6x3lPpm52wqemQ99d6n0bEdlyW8zrZOcGwNonniwcE0P2iJscuhv8Xlt5W6Cj2Az%2BKtbx5Z6kykB28Hj1S5Rw4aDoTxnk8utQxTgR6Tcu5AUNJN53xvWzLw1LZ2QtilLhG2Or2KXsEs%2FWIfN5r7Zn9lt2sZCyLdsrSh3CNnTZqHXvIdTDFOBh2DrihoCP4g1B%2FeAbPDw%2BZ%2BGSu6ZzoYev%2FWTJBkvUkmJu3DTNVpZqDTsTBAAJfFapZUOMOhxz47VdgpaG4iOtP2VgBqlpbDFO%2BWgcXnV4D6wt2yOjp1cG7BWpTz30%2BK4nrxKBsJwds4F1RPKru31mFoRsgX5fRb06zS1Mnuk905Vn8S8zDBx%2BW9BjqkAQDH1E%2BGSUJ%2FW1gQUuekF2HOxnO8f6anLsaT1wCOVWVSPqZZiEh%2B4mBaP20FYIUMh1ok%2B7qoqOJKrqCr4RVvTGpgbet%2BCXR3dVYmaEiXM0SAXCJUMz9nu9HlV4yDCNEc3J%2BmVM9KdP8qwy7PwkXCLfbpyjB6B0tj129XD1KjfV85yArRMXpmUsTV132%2FtMjbaUhbIaDmN0XYy%2Fj7qFLR71i%2Fjz4j&X-Amz-Signature=e1f759e7f99cd595c885e041f8ca8466f81e4a4a08027983a244e855799d9e4d&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664JKVHSML%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T092312Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDS7s9hZEpwqBw4LIzqPg96IEXZc%2B%2Fjzsey5S0PC7gUhAIhAMWk8C2urEr8tj4lafyFnUI4cLK%2FBTprK56B45CbYCinKogECOf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwbWOLpQA8SpA9F8cIq3ANk9tWIFgtRPpzCPDAWR3jquAtmaI36WIO4M8QdtJvl45vzRK2yhC0dZeSi1F5rNdJVrMay0XHJmX5gZ2B8eiem4R%2Bzcxb0UAbORX3neUg%2Fb%2BZOaW94xI6khzfI6ttU6exWbz%2BbE9rDR4UmQGVkNJv9PK7jndHL9Tot%2FYD66UzZdcQ0T09q8aqvxfNJrApix9Z7cqeVUblpYsd0KxxQlMsQD49qobPVTl%2FVySbukAO7AUE39Yusog7IkBOchXXm4MY0B7FbmydnY59hOrtHQQKNB6x3lPpm52wqemQ99d6n0bEdlyW8zrZOcGwNonniwcE0P2iJscuhv8Xlt5W6Cj2Az%2BKtbx5Z6kykB28Hj1S5Rw4aDoTxnk8utQxTgR6Tcu5AUNJN53xvWzLw1LZ2QtilLhG2Or2KXsEs%2FWIfN5r7Zn9lt2sZCyLdsrSh3CNnTZqHXvIdTDFOBh2DrihoCP4g1B%2FeAbPDw%2BZ%2BGSu6ZzoYev%2FWTJBkvUkmJu3DTNVpZqDTsTBAAJfFapZUOMOhxz47VdgpaG4iOtP2VgBqlpbDFO%2BWgcXnV4D6wt2yOjp1cG7BWpTz30%2BK4nrxKBsJwds4F1RPKru31mFoRsgX5fRb06zS1Mnuk905Vn8S8zDBx%2BW9BjqkAQDH1E%2BGSUJ%2FW1gQUuekF2HOxnO8f6anLsaT1wCOVWVSPqZZiEh%2B4mBaP20FYIUMh1ok%2B7qoqOJKrqCr4RVvTGpgbet%2BCXR3dVYmaEiXM0SAXCJUMz9nu9HlV4yDCNEc3J%2BmVM9KdP8qwy7PwkXCLfbpyjB6B0tj129XD1KjfV85yArRMXpmUsTV132%2FtMjbaUhbIaDmN0XYy%2Fj7qFLR71i%2Fjz4j&X-Amz-Signature=c25852520c013dfe3802b53ea2ca397abe3de33bee2f6ce36ba1009a2b232a02&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VJ753LAI%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T092313Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD4Bl9BzMSW89RAh1gqyPc11I92nVf%2BeyEcFN%2FoOtmWRQIgDrOKFUTunhPPYZ5wa84w3AuxoaRw35YucdHjHKurdTgqiAQI6v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDE42xl3qCVELW0LwACrcA9%2FrDoz561aTVoMFs7MyAgpmPEp1k9WPRJZA%2FuLmR%2FjHhfF4tMQ0zRw6yFrsyeRm9x%2BOYcAoR0Nvm1c%2BL%2FG%2F3Kz3Psg%2F3CL8m1aPc4JSDB2KxuV2O3rMdH28Zgy0wVhaZsGP01BhIITshwBFK4bty6AL2ydc%2FW2RzVxJPIwXYiJkRWMdwE3ocIlOwZGejt%2B%2BBCuPSDNgEobSeXhDDndkqUX6qoXIfx1vVqzrhnGmIaRxLFMvRc1RQVAR1MDY0WaLfJjaS25Uro3CiUVrOyds%2BPsuoKKBhJ34Ow4lHiV2vCFroCtv1CoUZ4zG%2FY2IrBYkQzvimuOt7gwJhGlXiWX4Tmam2nRi9lEgWd23ZKsaMZ3FCccaoLp18UrQCp7E6wjB%2FrtPdVUAJEbwdVZCUE43NKZbLltgNvsX6jmv24mb2B1PDT757rOsNfQAlHvumHDg5YOcGsQTvidw3yPLdb7kVvv7hVS6HCKZJTc4VLxwQcDMVhq9RoPkVmqGjL6YC%2FEKZIyMK65JQFXgsZBrlkRmEkdze5KMtNtJVWM7SEcHgtmO01zr23g0OLWzxjwmHGgx6w7nuIWH%2FF80vodMQ932rfCiTjFs0A%2BOCw9XgKZVyx8e5Cyi%2F%2FwUIxszUoU4MMOq5r0GOqUBlyYhzjVdmpcOIhJTmMPnkdMRylkwZO5U83H0n7GS%2Frgxty2uKyV6p%2FQYwJXeEMXOPi3jVuwLF1uod%2BW2c5vsm5IHOXkYzrQy%2BTxbhyBKkPE809Gc7b0gHspD%2FdMr5s6ykkQFq2EJcuahrbC3TSpZa3%2FJ9b8A7BmwD%2FhXaGUI5LSNeZrwy90c7rqbmWY7e3uL%2BSv9mZcXMjKH1yjc5oGU3TGjh0lz&X-Amz-Signature=c22ef319e4d3a9bf07b28d6dbdbef7ba1393bdf79e4810f4ba22cd96cbaeb43c&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665KP6JKM5%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T092313Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIHV2PnOqZrJrc8DP7s1LrLFtPBOQqTJxl53Sd0t%2FRjmlAiEArKGcT1fipdiD8J8Nqn0a1fy8uS1obtq%2F52PvDmOd4KIqiAQI5%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDEuPAxNp5r%2BFeVw%2FYircAwcd1TNDW3BsrpPPnFuM4C86IpBkEKubPiuiwdd%2BHiptnPjOL8mu%2FCsnHzlJXHjoWnHSxFTu8MPQF7JR4pxyAPG7CZPcsUr%2BRiDbQAlbeqgTY6oRZA86Sx1B%2BQA8xEjVk8lootn3blXKZ9EegnGnmfnbRV8zg2leVfkUdtLKt9Vc13TDjdRL3D3xZhxR17AwDFsvvCI09L8STv3ZrVdepOGuvvXYexmBafHOP1QkLbt%2F52xZKdG0CiurY8RvMvB8XXvvDBtTHPGbPwGYKwEJK0152vsT%2FW8VnCwP0Y6syLJ%2B6oU8X0%2BSyM%2FQbp5cH1NWGQHFlGiTVb39%2BgGheFdwtkF%2FMjs5pusKN8EWsHSuDKeVqqn1S6tSlyJj%2Bj%2BSPzHQfhfjmC2cnscfFGL4MFdpFDTg8d%2FAS1aNxg%2BJ%2FV5WZ3XiAGDgA6ADtzmpb95UsNSlEA15%2Bq%2B7v9KxMcbAjzQ8%2FV5AbzSg6MuwHWuYwFq%2Fw3piHVohrnWhCj5UKMabRdjxaJVXNQsJStCMXAVC7a5LLROZ4NSyse8ZcXWHfsuI1VGILD4O7JDUvHrQboqk7QOgv1V7s2%2BKDH92hZOu8C1ahtzw6h6oveyDDnRExRTRPDWLGRm1tLm0%2FHz%2F80NNMJzH5b0GOqUBIKm4%2FDhqAtEZJXqC5eMb9Ek3OLemX5cn0b4I%2BfLK2twHV42cHt8HVpCofm35K8%2BgKs2PEChtd6nK9Rvk8Knlm7aV0Ma%2BfHXZhu3nL%2BATZvO4gUZmBvqg2NBnt61Uq0vptR8oWCrqAz0ND1Drc4Gp9RvhWrFr%2BLeOFzGi8ilcn5jXKmN3F4eDIN%2BhIiARrfdWhGIrPTjx9dOSrvwe9XpfMb0C%2FpBN&X-Amz-Signature=4fae8d62d37ad08c5c7e5b1eeaaa862afce425ae5467970df2471c3025814243&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664JKVHSML%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T092312Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDS7s9hZEpwqBw4LIzqPg96IEXZc%2B%2Fjzsey5S0PC7gUhAIhAMWk8C2urEr8tj4lafyFnUI4cLK%2FBTprK56B45CbYCinKogECOf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwbWOLpQA8SpA9F8cIq3ANk9tWIFgtRPpzCPDAWR3jquAtmaI36WIO4M8QdtJvl45vzRK2yhC0dZeSi1F5rNdJVrMay0XHJmX5gZ2B8eiem4R%2Bzcxb0UAbORX3neUg%2Fb%2BZOaW94xI6khzfI6ttU6exWbz%2BbE9rDR4UmQGVkNJv9PK7jndHL9Tot%2FYD66UzZdcQ0T09q8aqvxfNJrApix9Z7cqeVUblpYsd0KxxQlMsQD49qobPVTl%2FVySbukAO7AUE39Yusog7IkBOchXXm4MY0B7FbmydnY59hOrtHQQKNB6x3lPpm52wqemQ99d6n0bEdlyW8zrZOcGwNonniwcE0P2iJscuhv8Xlt5W6Cj2Az%2BKtbx5Z6kykB28Hj1S5Rw4aDoTxnk8utQxTgR6Tcu5AUNJN53xvWzLw1LZ2QtilLhG2Or2KXsEs%2FWIfN5r7Zn9lt2sZCyLdsrSh3CNnTZqHXvIdTDFOBh2DrihoCP4g1B%2FeAbPDw%2BZ%2BGSu6ZzoYev%2FWTJBkvUkmJu3DTNVpZqDTsTBAAJfFapZUOMOhxz47VdgpaG4iOtP2VgBqlpbDFO%2BWgcXnV4D6wt2yOjp1cG7BWpTz30%2BK4nrxKBsJwds4F1RPKru31mFoRsgX5fRb06zS1Mnuk905Vn8S8zDBx%2BW9BjqkAQDH1E%2BGSUJ%2FW1gQUuekF2HOxnO8f6anLsaT1wCOVWVSPqZZiEh%2B4mBaP20FYIUMh1ok%2B7qoqOJKrqCr4RVvTGpgbet%2BCXR3dVYmaEiXM0SAXCJUMz9nu9HlV4yDCNEc3J%2BmVM9KdP8qwy7PwkXCLfbpyjB6B0tj129XD1KjfV85yArRMXpmUsTV132%2FtMjbaUhbIaDmN0XYy%2Fj7qFLR71i%2Fjz4j&X-Amz-Signature=81531a32058dd6b0375f791e9064893ac471512c4e459909fa1ccf93082eb098&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664JKVHSML%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T092312Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDS7s9hZEpwqBw4LIzqPg96IEXZc%2B%2Fjzsey5S0PC7gUhAIhAMWk8C2urEr8tj4lafyFnUI4cLK%2FBTprK56B45CbYCinKogECOf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwbWOLpQA8SpA9F8cIq3ANk9tWIFgtRPpzCPDAWR3jquAtmaI36WIO4M8QdtJvl45vzRK2yhC0dZeSi1F5rNdJVrMay0XHJmX5gZ2B8eiem4R%2Bzcxb0UAbORX3neUg%2Fb%2BZOaW94xI6khzfI6ttU6exWbz%2BbE9rDR4UmQGVkNJv9PK7jndHL9Tot%2FYD66UzZdcQ0T09q8aqvxfNJrApix9Z7cqeVUblpYsd0KxxQlMsQD49qobPVTl%2FVySbukAO7AUE39Yusog7IkBOchXXm4MY0B7FbmydnY59hOrtHQQKNB6x3lPpm52wqemQ99d6n0bEdlyW8zrZOcGwNonniwcE0P2iJscuhv8Xlt5W6Cj2Az%2BKtbx5Z6kykB28Hj1S5Rw4aDoTxnk8utQxTgR6Tcu5AUNJN53xvWzLw1LZ2QtilLhG2Or2KXsEs%2FWIfN5r7Zn9lt2sZCyLdsrSh3CNnTZqHXvIdTDFOBh2DrihoCP4g1B%2FeAbPDw%2BZ%2BGSu6ZzoYev%2FWTJBkvUkmJu3DTNVpZqDTsTBAAJfFapZUOMOhxz47VdgpaG4iOtP2VgBqlpbDFO%2BWgcXnV4D6wt2yOjp1cG7BWpTz30%2BK4nrxKBsJwds4F1RPKru31mFoRsgX5fRb06zS1Mnuk905Vn8S8zDBx%2BW9BjqkAQDH1E%2BGSUJ%2FW1gQUuekF2HOxnO8f6anLsaT1wCOVWVSPqZZiEh%2B4mBaP20FYIUMh1ok%2B7qoqOJKrqCr4RVvTGpgbet%2BCXR3dVYmaEiXM0SAXCJUMz9nu9HlV4yDCNEc3J%2BmVM9KdP8qwy7PwkXCLfbpyjB6B0tj129XD1KjfV85yArRMXpmUsTV132%2FtMjbaUhbIaDmN0XYy%2Fj7qFLR71i%2Fjz4j&X-Amz-Signature=542cf4b525f7dc74071e5a3f3edcb28379d77467188bf63aea1fac8d73c96a62&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664JKVHSML%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T092312Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDS7s9hZEpwqBw4LIzqPg96IEXZc%2B%2Fjzsey5S0PC7gUhAIhAMWk8C2urEr8tj4lafyFnUI4cLK%2FBTprK56B45CbYCinKogECOf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwbWOLpQA8SpA9F8cIq3ANk9tWIFgtRPpzCPDAWR3jquAtmaI36WIO4M8QdtJvl45vzRK2yhC0dZeSi1F5rNdJVrMay0XHJmX5gZ2B8eiem4R%2Bzcxb0UAbORX3neUg%2Fb%2BZOaW94xI6khzfI6ttU6exWbz%2BbE9rDR4UmQGVkNJv9PK7jndHL9Tot%2FYD66UzZdcQ0T09q8aqvxfNJrApix9Z7cqeVUblpYsd0KxxQlMsQD49qobPVTl%2FVySbukAO7AUE39Yusog7IkBOchXXm4MY0B7FbmydnY59hOrtHQQKNB6x3lPpm52wqemQ99d6n0bEdlyW8zrZOcGwNonniwcE0P2iJscuhv8Xlt5W6Cj2Az%2BKtbx5Z6kykB28Hj1S5Rw4aDoTxnk8utQxTgR6Tcu5AUNJN53xvWzLw1LZ2QtilLhG2Or2KXsEs%2FWIfN5r7Zn9lt2sZCyLdsrSh3CNnTZqHXvIdTDFOBh2DrihoCP4g1B%2FeAbPDw%2BZ%2BGSu6ZzoYev%2FWTJBkvUkmJu3DTNVpZqDTsTBAAJfFapZUOMOhxz47VdgpaG4iOtP2VgBqlpbDFO%2BWgcXnV4D6wt2yOjp1cG7BWpTz30%2BK4nrxKBsJwds4F1RPKru31mFoRsgX5fRb06zS1Mnuk905Vn8S8zDBx%2BW9BjqkAQDH1E%2BGSUJ%2FW1gQUuekF2HOxnO8f6anLsaT1wCOVWVSPqZZiEh%2B4mBaP20FYIUMh1ok%2B7qoqOJKrqCr4RVvTGpgbet%2BCXR3dVYmaEiXM0SAXCJUMz9nu9HlV4yDCNEc3J%2BmVM9KdP8qwy7PwkXCLfbpyjB6B0tj129XD1KjfV85yArRMXpmUsTV132%2FtMjbaUhbIaDmN0XYy%2Fj7qFLR71i%2Fjz4j&X-Amz-Signature=214af72c0e9c3b09c14aa390bf1195d5ffe0703db6859204b51cb858ee3ae308&X-Amz-SignedHeaders=host&x-id=GetObject)


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

