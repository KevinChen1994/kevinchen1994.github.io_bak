---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466QWFNSKDL%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250214T032752Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCICynfkDee4dXT5YGcUv\
  jvmJmve1qpaBSuYpzfCNrgWerAiEAq0cA13s2LxqVpJGYqwyTLOYVAGV0dZNWErpD2CvFy3Aq%2Fw\
  MIJBAAGgw2Mzc0MjMxODM4MDUiDDqM5Tlrlvpc5UKXJCrcAzGlkwvvMD1i8xRcemgQR0KTVAGI9Ay\
  aMP8nE7VwlXOToZ6DltX3UJ0OcXTrNhvbnKCgl%2Bqc8H8TzN2AxoWyChGOhz0%2Bh%2BrQ3Amp1g\
  8s5A8iSnt8hX0BAwa9vVFGg8jZ27dSvHDeqxxcuP4hK%2F0lhLVetvKdioCUjxx%2FblQjlqvcUvI\
  Ios3VOMJZoJGuJTVGZ35HcaDMRgM9IjRKWpczw73EyDKHpTZRJFlqo%2Bq55uUhEJFNbsjhvq9uvs\
  zHtM9bvZKJvE27kSr5G%2Fx1%2BbYuE203tUmi0V8I0yVOXd51XKA6cwwyzv47o9OekYY9ujJxloh\
  Okbk6Wd8jegLQMG3hY4cGKmo3z5ozp2BvH8Kp3MkT3eX1nSB%2FMCBaG0lJh3CxvdjOLrTgizDqYh\
  f8%2B3p0b64%2FDgw5rpjnIQ3fgThhwZ1bOr14yOijNP3z7a2hHZue1oYC3t7KRAD0uMPbI4nFQBa\
  B5wDGkOAOUu71ZW2QSfg1ZMQ5oJRpK7YikktIpBql0%2FkkNXUf5wZxSPGVfx5qTOSkde8vDVviCg\
  8qGcQzZ67AN0MtrtLenthpCDY7qOv9kgGNZyBQuvFYCWORTA%2FLZF%2BPQCM1OTFvBss9HLHnYuQ\
  gMAps0%2FwQdu0bDjAMMMjrur0GOqUBPrktsuWcFnu3%2B4ZD4t0ykkWTs8f%2B3hJJod88bZsTVi\
  zT1xuTz641g1V0y47xcHn6o3yQmeGWpe5vOrfogx0hYe%2BXZ5dOWvKpRSxDey9FYXA2%2FFXAdsa\
  y115IRXO%2FsoIvjP6JNWRpopfRRLfF%2F9BFhXj0Q1Te3MOi3QSwSpQa%2B7chbLQLsNBBFKlIwy\
  7S40bTcc5rnogl%2BqvZDFlNrJwpaMi%2BM%2F6O&X-Amz-Signature=076ca4f61bb4bf395f39\
  c6fc763deef7b8b3082e00ed2515e2672af11146f861&X-Amz-SignedHeaders=host&x-id=Ge\
  tObject"
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
        redential=ASIAZI2LB4664Q4XOGEU%2F20250214%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250214T032610Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CICQYikmEbx0LWcErvkbiHKyU8ezhGu630W2mBlV31VOVAiEAh%2FRmHXx%2FbmlEp6neX5\
        6EM83qy7q1JQHN9Y%2B8%2BO8wPzIq%2FwMIJBAAGgw2Mzc0MjMxODM4MDUiDC9fz4CpfFa\
        5ye3bGyrcA2xl%2BsloCLzEddiFPV%2FZZ6hehhol2taDJpDMNbG2Ke%2FXLxeRd1rKM5zi\
        JaQXWcqYPUWm1ZcmpGt5gB0sbukn5DrWO8slpScECcZilt3a%2BbHHCr8L5iFmMucxVB8r9\
        u%2FfrinDIETb9g8Nfj8giAFndEA%2BxFiTKf92eQn505hZjbDaMkIuavOmuiK26RXTMuTo\
        MNcUgVS5gj2n2U%2FhflFgQOHMF0ft%2Bo23u529heW5gqwho3Z1XEiQdzQ88HySDtYb1Ka\
        xAG7k9vaOsEgtUMEEh3m6afjdS%2B7zLDh8bJd9NTFrGn8TLDhssMQouj9B8CTN4%2B%2Fu\
        oNzz9659HYnEnc3iteZMq4E6EHyGWzadqgeKsAae8%2FUk22X5wyTLkOGygK52eNKXLeLi7\
        tmMwTWI2fDq3wnNIio1NfDb5sfFo2CihSLgc7nc9K0GImWWGnzxSS6gLayIniH%2F6ecIaW\
        2xqAntLbnR91XRXSd9FDAd4%2B%2BSTJTdIjryLwQFN%2F90vBvf24UC8hOUDlGrUsnGDME\
        MooiwbQCobfKsP9i5UH0ShVJ7FmNlMQkoSDXMBi%2F4F1zOJOQS4vL6%2BWuwfGTvgFaHZy\
        kUkCx0i0Qchj3s1riiC%2BcMi90ssZx7WtljwuvSFFIXMIvrur0GOqUBEUeGc6ZHVcnnLDS\
        dsvsHNSFLwihwfjUzWHPqLLzA3WFW5XM5K6CmXJ7fJ88sXdgjIiluwNeH8IlmezdtBRXLNG\
        HjogseO7Pe%2FEwNtVWn%2BZKrL%2F%2FlSImWm3kXsdiBdsHoAruooZwuOs9yRcOlQTAl8\
        NEfJzVD5eNXrqDxS2CZgfNM6iz5AMhaGkk5v2uuqcW5lM%2FxKVHc0DAQUG%2B2XKavb2Ns\
        Ok5x&X-Amz-Signature=7ac30580debdb25128b189ef2da7d2d999f9524be9067d6ef2\
        7f0f8b01260d09&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-14T04:26:10.628Z"
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
UPDATE_TIME: "2025-02-14T03:27:58.111Z"
EXPIRY_TIME: "2025-02-14T04:27:47.137Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662BIIZXIH%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T032749Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD4GwwOz%2BvIrKjxPGIopvXqdDD4OF%2BDOpOR9oAoOnhuCgIgHWwGZl2A%2B3aNejQ92F%2B54U7x8DbpyNi0Pb5wU0WHMP8q%2FwMIJBAAGgw2Mzc0MjMxODM4MDUiDH36cm74s2OFyOVc%2BSrcAw33ooXZLcyU6BxQK%2F5TXpmRHVuZCnyJM9sucwbmzd810XFD2FXhgWGH1O9VuhzaG9pzRX9iM7WkiyZuDmzvoSOcF4AVO7cwdVkkZCjmfuJ%2FocUUyA4%2FnO2TSGzYtVbNwJr8tEjqge8iWtCfgCTs3s5GiJ8WzZZfjLR07xQPqWZrKWkvccWco4YKBgOdg7n1D9DskiLLXhZlyJZ2sVRiIs5qrEw1Y9IEy8f8iIOJnmD49K67DxI6QxQQvBxOY961%2FsAWbwwvaYZx1TRV%2BT1IJQ8KkXXqWRk5BDFaAy19E19KvNqnza9NGSjTY94LpOuXiKF6ldJSOLH1SLaExxrEDR5%2FKNx1o1a3teIjkvP6Nk8vQnubRR9qT4xV2i%2B9XIAYGDJ%2B8JFFyfPV1Fb9XHa0V9PI%2BbM1kKt9OxNFYBgW4FDeNh5ku9aPV14%2B2ZWm58AOYSuJyZ6%2F2I0nMJAISxxDXBaUxzyqSDxJiDOpZC3TCqRg1KsqzjdBYRWhYrGQlylRfU5C4SjNV1LwRwnKlRmC2eR8qREPhd08HvzOu%2BOEZXUmvxtYmz7ktXklkTS1nKP2oImB6y%2Bcks8AZTyhFejKz%2Fs36chz315qdcaXuspT5aKVVjmYhOy7Zyj0N5ZaMJDrur0GOqUBjRIKN%2BS3UMY3SaXCNdQJr3gPHNzeJMfavwrFrjv2gmGrWdx%2BxRJEbbPYTkKm2Rxb8FXClKLbalk25vSxNFH5xpp2cPRpjLJZSOSVj1F2ej5M5Y48mhrtrLVBYQXuFVbkyHiP2ZlXOQ5cW%2F4e4R7Ia7CE3OeWSpSn4fqBsKgQVLAvoD3%2B5LEdqQWFKx6KnP8KLOIsvOtLHRMljeUprH5uG5dS%2BDb5&X-Amz-Signature=8cfe5403dd8392fc3dfd27f37b756f3e8e5de6e605e34aa5b2eec55acaf928b2&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662BIIZXIH%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T032749Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD4GwwOz%2BvIrKjxPGIopvXqdDD4OF%2BDOpOR9oAoOnhuCgIgHWwGZl2A%2B3aNejQ92F%2B54U7x8DbpyNi0Pb5wU0WHMP8q%2FwMIJBAAGgw2Mzc0MjMxODM4MDUiDH36cm74s2OFyOVc%2BSrcAw33ooXZLcyU6BxQK%2F5TXpmRHVuZCnyJM9sucwbmzd810XFD2FXhgWGH1O9VuhzaG9pzRX9iM7WkiyZuDmzvoSOcF4AVO7cwdVkkZCjmfuJ%2FocUUyA4%2FnO2TSGzYtVbNwJr8tEjqge8iWtCfgCTs3s5GiJ8WzZZfjLR07xQPqWZrKWkvccWco4YKBgOdg7n1D9DskiLLXhZlyJZ2sVRiIs5qrEw1Y9IEy8f8iIOJnmD49K67DxI6QxQQvBxOY961%2FsAWbwwvaYZx1TRV%2BT1IJQ8KkXXqWRk5BDFaAy19E19KvNqnza9NGSjTY94LpOuXiKF6ldJSOLH1SLaExxrEDR5%2FKNx1o1a3teIjkvP6Nk8vQnubRR9qT4xV2i%2B9XIAYGDJ%2B8JFFyfPV1Fb9XHa0V9PI%2BbM1kKt9OxNFYBgW4FDeNh5ku9aPV14%2B2ZWm58AOYSuJyZ6%2F2I0nMJAISxxDXBaUxzyqSDxJiDOpZC3TCqRg1KsqzjdBYRWhYrGQlylRfU5C4SjNV1LwRwnKlRmC2eR8qREPhd08HvzOu%2BOEZXUmvxtYmz7ktXklkTS1nKP2oImB6y%2Bcks8AZTyhFejKz%2Fs36chz315qdcaXuspT5aKVVjmYhOy7Zyj0N5ZaMJDrur0GOqUBjRIKN%2BS3UMY3SaXCNdQJr3gPHNzeJMfavwrFrjv2gmGrWdx%2BxRJEbbPYTkKm2Rxb8FXClKLbalk25vSxNFH5xpp2cPRpjLJZSOSVj1F2ej5M5Y48mhrtrLVBYQXuFVbkyHiP2ZlXOQ5cW%2F4e4R7Ia7CE3OeWSpSn4fqBsKgQVLAvoD3%2B5LEdqQWFKx6KnP8KLOIsvOtLHRMljeUprH5uG5dS%2BDb5&X-Amz-Signature=a73b8694c82b39e6bd1ee28f1a9e8848934398996a0b9e708d1a3582a2762174&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662BIIZXIH%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T032749Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD4GwwOz%2BvIrKjxPGIopvXqdDD4OF%2BDOpOR9oAoOnhuCgIgHWwGZl2A%2B3aNejQ92F%2B54U7x8DbpyNi0Pb5wU0WHMP8q%2FwMIJBAAGgw2Mzc0MjMxODM4MDUiDH36cm74s2OFyOVc%2BSrcAw33ooXZLcyU6BxQK%2F5TXpmRHVuZCnyJM9sucwbmzd810XFD2FXhgWGH1O9VuhzaG9pzRX9iM7WkiyZuDmzvoSOcF4AVO7cwdVkkZCjmfuJ%2FocUUyA4%2FnO2TSGzYtVbNwJr8tEjqge8iWtCfgCTs3s5GiJ8WzZZfjLR07xQPqWZrKWkvccWco4YKBgOdg7n1D9DskiLLXhZlyJZ2sVRiIs5qrEw1Y9IEy8f8iIOJnmD49K67DxI6QxQQvBxOY961%2FsAWbwwvaYZx1TRV%2BT1IJQ8KkXXqWRk5BDFaAy19E19KvNqnza9NGSjTY94LpOuXiKF6ldJSOLH1SLaExxrEDR5%2FKNx1o1a3teIjkvP6Nk8vQnubRR9qT4xV2i%2B9XIAYGDJ%2B8JFFyfPV1Fb9XHa0V9PI%2BbM1kKt9OxNFYBgW4FDeNh5ku9aPV14%2B2ZWm58AOYSuJyZ6%2F2I0nMJAISxxDXBaUxzyqSDxJiDOpZC3TCqRg1KsqzjdBYRWhYrGQlylRfU5C4SjNV1LwRwnKlRmC2eR8qREPhd08HvzOu%2BOEZXUmvxtYmz7ktXklkTS1nKP2oImB6y%2Bcks8AZTyhFejKz%2Fs36chz315qdcaXuspT5aKVVjmYhOy7Zyj0N5ZaMJDrur0GOqUBjRIKN%2BS3UMY3SaXCNdQJr3gPHNzeJMfavwrFrjv2gmGrWdx%2BxRJEbbPYTkKm2Rxb8FXClKLbalk25vSxNFH5xpp2cPRpjLJZSOSVj1F2ej5M5Y48mhrtrLVBYQXuFVbkyHiP2ZlXOQ5cW%2F4e4R7Ia7CE3OeWSpSn4fqBsKgQVLAvoD3%2B5LEdqQWFKx6KnP8KLOIsvOtLHRMljeUprH5uG5dS%2BDb5&X-Amz-Signature=76fc6f19f00e2d5bf95e430ea17d38e5f38001d9ec5ede4c7f504157a648fd8f&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662BIIZXIH%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T032749Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD4GwwOz%2BvIrKjxPGIopvXqdDD4OF%2BDOpOR9oAoOnhuCgIgHWwGZl2A%2B3aNejQ92F%2B54U7x8DbpyNi0Pb5wU0WHMP8q%2FwMIJBAAGgw2Mzc0MjMxODM4MDUiDH36cm74s2OFyOVc%2BSrcAw33ooXZLcyU6BxQK%2F5TXpmRHVuZCnyJM9sucwbmzd810XFD2FXhgWGH1O9VuhzaG9pzRX9iM7WkiyZuDmzvoSOcF4AVO7cwdVkkZCjmfuJ%2FocUUyA4%2FnO2TSGzYtVbNwJr8tEjqge8iWtCfgCTs3s5GiJ8WzZZfjLR07xQPqWZrKWkvccWco4YKBgOdg7n1D9DskiLLXhZlyJZ2sVRiIs5qrEw1Y9IEy8f8iIOJnmD49K67DxI6QxQQvBxOY961%2FsAWbwwvaYZx1TRV%2BT1IJQ8KkXXqWRk5BDFaAy19E19KvNqnza9NGSjTY94LpOuXiKF6ldJSOLH1SLaExxrEDR5%2FKNx1o1a3teIjkvP6Nk8vQnubRR9qT4xV2i%2B9XIAYGDJ%2B8JFFyfPV1Fb9XHa0V9PI%2BbM1kKt9OxNFYBgW4FDeNh5ku9aPV14%2B2ZWm58AOYSuJyZ6%2F2I0nMJAISxxDXBaUxzyqSDxJiDOpZC3TCqRg1KsqzjdBYRWhYrGQlylRfU5C4SjNV1LwRwnKlRmC2eR8qREPhd08HvzOu%2BOEZXUmvxtYmz7ktXklkTS1nKP2oImB6y%2Bcks8AZTyhFejKz%2Fs36chz315qdcaXuspT5aKVVjmYhOy7Zyj0N5ZaMJDrur0GOqUBjRIKN%2BS3UMY3SaXCNdQJr3gPHNzeJMfavwrFrjv2gmGrWdx%2BxRJEbbPYTkKm2Rxb8FXClKLbalk25vSxNFH5xpp2cPRpjLJZSOSVj1F2ej5M5Y48mhrtrLVBYQXuFVbkyHiP2ZlXOQ5cW%2F4e4R7Ia7CE3OeWSpSn4fqBsKgQVLAvoD3%2B5LEdqQWFKx6KnP8KLOIsvOtLHRMljeUprH5uG5dS%2BDb5&X-Amz-Signature=a12eeb8930230625f47d660dd9d0f564b62b0c86cf5bc2d6e58a58e460ee814c&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662BIIZXIH%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T032749Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD4GwwOz%2BvIrKjxPGIopvXqdDD4OF%2BDOpOR9oAoOnhuCgIgHWwGZl2A%2B3aNejQ92F%2B54U7x8DbpyNi0Pb5wU0WHMP8q%2FwMIJBAAGgw2Mzc0MjMxODM4MDUiDH36cm74s2OFyOVc%2BSrcAw33ooXZLcyU6BxQK%2F5TXpmRHVuZCnyJM9sucwbmzd810XFD2FXhgWGH1O9VuhzaG9pzRX9iM7WkiyZuDmzvoSOcF4AVO7cwdVkkZCjmfuJ%2FocUUyA4%2FnO2TSGzYtVbNwJr8tEjqge8iWtCfgCTs3s5GiJ8WzZZfjLR07xQPqWZrKWkvccWco4YKBgOdg7n1D9DskiLLXhZlyJZ2sVRiIs5qrEw1Y9IEy8f8iIOJnmD49K67DxI6QxQQvBxOY961%2FsAWbwwvaYZx1TRV%2BT1IJQ8KkXXqWRk5BDFaAy19E19KvNqnza9NGSjTY94LpOuXiKF6ldJSOLH1SLaExxrEDR5%2FKNx1o1a3teIjkvP6Nk8vQnubRR9qT4xV2i%2B9XIAYGDJ%2B8JFFyfPV1Fb9XHa0V9PI%2BbM1kKt9OxNFYBgW4FDeNh5ku9aPV14%2B2ZWm58AOYSuJyZ6%2F2I0nMJAISxxDXBaUxzyqSDxJiDOpZC3TCqRg1KsqzjdBYRWhYrGQlylRfU5C4SjNV1LwRwnKlRmC2eR8qREPhd08HvzOu%2BOEZXUmvxtYmz7ktXklkTS1nKP2oImB6y%2Bcks8AZTyhFejKz%2Fs36chz315qdcaXuspT5aKVVjmYhOy7Zyj0N5ZaMJDrur0GOqUBjRIKN%2BS3UMY3SaXCNdQJr3gPHNzeJMfavwrFrjv2gmGrWdx%2BxRJEbbPYTkKm2Rxb8FXClKLbalk25vSxNFH5xpp2cPRpjLJZSOSVj1F2ej5M5Y48mhrtrLVBYQXuFVbkyHiP2ZlXOQ5cW%2F4e4R7Ia7CE3OeWSpSn4fqBsKgQVLAvoD3%2B5LEdqQWFKx6KnP8KLOIsvOtLHRMljeUprH5uG5dS%2BDb5&X-Amz-Signature=d435f85fa367ef9f02a7f65d5ed27ec7771c0f766f39aa99213302b1611cae67&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RZPYNBNV%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T032750Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC3LHESzsZNqCCpe7pITg39kx0kbHbZHEnZJCDzOx7n4wIhAJR2cgxKv6T6BpTXI8juUNXnxfyvqb4BeMD%2BhQSrcy70Kv8DCCQQABoMNjM3NDIzMTgzODA1Igz9SUr%2B%2BdLE%2BBnIqYIq3AP1SVx7EyuQ1PMdpzYwkdJ8ZpwdfYCttxwUoL1iO8ctT6lx3PY2PxS3rwiGFjTTsn%2BhKhKFLcKMTs5w2n8f6KtzX%2F1gO6%2F7%2BXVcIKFFg7Og%2FlfpJSh%2B6iYbJH0VVSM0B83MCipRutcnQxHRGbbKA20tpIyI8sxui%2FPE6%2Fpm7tadPFcQvECbEqLrCao3%2BeQzl8f295P%2BCjxNmIUOkI%2BSQS5q6YyiZ01iUhLxmLV6bX6ZjKvhj4s7fX7oBkaj2nOZhfPym3kIS4BirQUaJvfV2zIA2rpaUWq6nUDvxtE%2Fkejy1vjPiQwN54O8mln%2FKPj4bS5UJT0QboP2otdEAqpa0iJblRGcBN2qjDohg8Hi%2FyvGI7DCm%2Fs8CcJgqz%2BgY4Ggt9WNwjGvg5eG53BaFWngx8cyhxMAIbOnT6yB5OX9xH5GmrvXJ2%2FXyHw8su0cO3JZz6RhSeYPnIOadn1aaEmgheNyQBNZMNEEU%2F22rr4NE%2Fhe0eKbiwGy8NBdr9lH0bSrldtRwltsSRmwy2E47r%2FhvDUwFXnKQsgXtbXn9lAZyi0%2FI5EcFZFc3U632OTXsoXwUDPThgxb1VrBVIW2T8l9m4ynXTMk6Pj9YRuo90avo53Jb7hyI9AOT9tOfiTo2DD06rq9BjqkAWZpzK%2BvmgRV4eUdLoAadoy7vnQm2bW7F06nbuEFKVEBgMNUNqXe88N7OQi98BzBmNZcy4uXwR2TTtnOVqCpqyBLHxF0uYZ2y1SYgok%2FrYNWVL1uvrNRBVcwsQWSSL21tgVjGUv3nIVL0UumcxvaqVFCfOsVBq2wtwiCZlbHEJUxM8jGhkc5OJTq8qMI4rRzLmSXxtoSiouzX4BAiQ9SWVAVZtDa&X-Amz-Signature=a603f415ceb8b882acdb3481e033bd144fc964b6f36a2928e8b7ffbb81ee5c86&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YEBBKBZC%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T032752Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDFQYpy1biC8mOawi3bUpVCh24cjSDMX%2BZd2VDmrdsycgIgbE0p0ndD92SzaskCyMvF94CLqXkZSBrhWu%2FcMyUp514q%2FwMIJBAAGgw2Mzc0MjMxODM4MDUiDKyt0WxcZpjr4khDTyrcAzOUBeXP80mY0o0qPICdVTzzOL%2BILdeLNXK%2FB3bLGwZ0JXjwcaTOlpbgjGOgR0ngCgtWxG3lt%2BoWMZJmWfUfwIEGgcCZXNr9M6qVF2oQNPMrPTql6XyfQqPfUjPwsc3bfkvXtKy2MHcEU73%2BoFmJAMtCJdEQ2Za9LrxNcj5uV1fgafZQhl7UvwLaFA%2F6J8rvBteaGgEFOJGJ1DsJRWHAoOowvGf4wloM89Zt3a4iwkhQkyQIWS9EBIMZHj269qb7vNFS7dpIEw2CuiEImKdCinEO%2BOZOO0CLBicwhQ0M8edKwzWQ8Id74TdLfyiNrReSv4l20X6U9EKF%2FFGtrOtvrX3arMF1g0xdUy1CSfJ4Yy5449eYvVN3THQqvwxepCEs5LNrNnYoOKgJnxtpb2JwN0E%2BMwUFJpGG%2F8TmS0Aaw9ZSw1oQOvmWA%2BBGxuFiAo%2BsySq1HFBnUWTpddpocbN5LLpREowg4x%2FmXtxTnhieXmDUCm9edVPnb6H7EjI7oUbE4NC1CNOf75n6kBJBAlHX8BLvIte8AcymAeQgOpy6h8lTROTPziUiXOvD50OaQof5HTgAxGyIvkqKH%2F69zxRsZbGoevJccdXSJBczIa47ggs4WpY%2BDFHBPAU6%2Buf%2FMMTqur0GOqUBtGiKL7VLtR2DtWoX218FkS2nARPVgHLSKzcDVFNfddCYMYs%2BuamowroXxAH2C3r5D7%2BVDS2z5NxPSsf6x5ud3hp8RHTZN96G%2B9X9oTYRCGNnyAbxh5frDp8s0QoOBmmDu5XfCxep%2BxxVE12aeOKhV8xK5STZIvQuGEGdxsxc9VshF4apLStp%2FqeisZVoLBRe5jwTn%2FwNo%2BAWnQLG0nORwiutmgkY&X-Amz-Signature=d0fbbbc0734360bf589e79256a7856bb69b869a06bf09266797077ee1952e285&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662BIIZXIH%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T032749Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD4GwwOz%2BvIrKjxPGIopvXqdDD4OF%2BDOpOR9oAoOnhuCgIgHWwGZl2A%2B3aNejQ92F%2B54U7x8DbpyNi0Pb5wU0WHMP8q%2FwMIJBAAGgw2Mzc0MjMxODM4MDUiDH36cm74s2OFyOVc%2BSrcAw33ooXZLcyU6BxQK%2F5TXpmRHVuZCnyJM9sucwbmzd810XFD2FXhgWGH1O9VuhzaG9pzRX9iM7WkiyZuDmzvoSOcF4AVO7cwdVkkZCjmfuJ%2FocUUyA4%2FnO2TSGzYtVbNwJr8tEjqge8iWtCfgCTs3s5GiJ8WzZZfjLR07xQPqWZrKWkvccWco4YKBgOdg7n1D9DskiLLXhZlyJZ2sVRiIs5qrEw1Y9IEy8f8iIOJnmD49K67DxI6QxQQvBxOY961%2FsAWbwwvaYZx1TRV%2BT1IJQ8KkXXqWRk5BDFaAy19E19KvNqnza9NGSjTY94LpOuXiKF6ldJSOLH1SLaExxrEDR5%2FKNx1o1a3teIjkvP6Nk8vQnubRR9qT4xV2i%2B9XIAYGDJ%2B8JFFyfPV1Fb9XHa0V9PI%2BbM1kKt9OxNFYBgW4FDeNh5ku9aPV14%2B2ZWm58AOYSuJyZ6%2F2I0nMJAISxxDXBaUxzyqSDxJiDOpZC3TCqRg1KsqzjdBYRWhYrGQlylRfU5C4SjNV1LwRwnKlRmC2eR8qREPhd08HvzOu%2BOEZXUmvxtYmz7ktXklkTS1nKP2oImB6y%2Bcks8AZTyhFejKz%2Fs36chz315qdcaXuspT5aKVVjmYhOy7Zyj0N5ZaMJDrur0GOqUBjRIKN%2BS3UMY3SaXCNdQJr3gPHNzeJMfavwrFrjv2gmGrWdx%2BxRJEbbPYTkKm2Rxb8FXClKLbalk25vSxNFH5xpp2cPRpjLJZSOSVj1F2ej5M5Y48mhrtrLVBYQXuFVbkyHiP2ZlXOQ5cW%2F4e4R7Ia7CE3OeWSpSn4fqBsKgQVLAvoD3%2B5LEdqQWFKx6KnP8KLOIsvOtLHRMljeUprH5uG5dS%2BDb5&X-Amz-Signature=aede09152a0db54801ce410927a6f76837cfe24567a65da5851a7673f26a4c6f&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662BIIZXIH%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T032749Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD4GwwOz%2BvIrKjxPGIopvXqdDD4OF%2BDOpOR9oAoOnhuCgIgHWwGZl2A%2B3aNejQ92F%2B54U7x8DbpyNi0Pb5wU0WHMP8q%2FwMIJBAAGgw2Mzc0MjMxODM4MDUiDH36cm74s2OFyOVc%2BSrcAw33ooXZLcyU6BxQK%2F5TXpmRHVuZCnyJM9sucwbmzd810XFD2FXhgWGH1O9VuhzaG9pzRX9iM7WkiyZuDmzvoSOcF4AVO7cwdVkkZCjmfuJ%2FocUUyA4%2FnO2TSGzYtVbNwJr8tEjqge8iWtCfgCTs3s5GiJ8WzZZfjLR07xQPqWZrKWkvccWco4YKBgOdg7n1D9DskiLLXhZlyJZ2sVRiIs5qrEw1Y9IEy8f8iIOJnmD49K67DxI6QxQQvBxOY961%2FsAWbwwvaYZx1TRV%2BT1IJQ8KkXXqWRk5BDFaAy19E19KvNqnza9NGSjTY94LpOuXiKF6ldJSOLH1SLaExxrEDR5%2FKNx1o1a3teIjkvP6Nk8vQnubRR9qT4xV2i%2B9XIAYGDJ%2B8JFFyfPV1Fb9XHa0V9PI%2BbM1kKt9OxNFYBgW4FDeNh5ku9aPV14%2B2ZWm58AOYSuJyZ6%2F2I0nMJAISxxDXBaUxzyqSDxJiDOpZC3TCqRg1KsqzjdBYRWhYrGQlylRfU5C4SjNV1LwRwnKlRmC2eR8qREPhd08HvzOu%2BOEZXUmvxtYmz7ktXklkTS1nKP2oImB6y%2Bcks8AZTyhFejKz%2Fs36chz315qdcaXuspT5aKVVjmYhOy7Zyj0N5ZaMJDrur0GOqUBjRIKN%2BS3UMY3SaXCNdQJr3gPHNzeJMfavwrFrjv2gmGrWdx%2BxRJEbbPYTkKm2Rxb8FXClKLbalk25vSxNFH5xpp2cPRpjLJZSOSVj1F2ej5M5Y48mhrtrLVBYQXuFVbkyHiP2ZlXOQ5cW%2F4e4R7Ia7CE3OeWSpSn4fqBsKgQVLAvoD3%2B5LEdqQWFKx6KnP8KLOIsvOtLHRMljeUprH5uG5dS%2BDb5&X-Amz-Signature=255c2457bfc48facd9929db1fc7133a56324da71243694dfa25aeee0f4703754&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662BIIZXIH%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T032749Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD4GwwOz%2BvIrKjxPGIopvXqdDD4OF%2BDOpOR9oAoOnhuCgIgHWwGZl2A%2B3aNejQ92F%2B54U7x8DbpyNi0Pb5wU0WHMP8q%2FwMIJBAAGgw2Mzc0MjMxODM4MDUiDH36cm74s2OFyOVc%2BSrcAw33ooXZLcyU6BxQK%2F5TXpmRHVuZCnyJM9sucwbmzd810XFD2FXhgWGH1O9VuhzaG9pzRX9iM7WkiyZuDmzvoSOcF4AVO7cwdVkkZCjmfuJ%2FocUUyA4%2FnO2TSGzYtVbNwJr8tEjqge8iWtCfgCTs3s5GiJ8WzZZfjLR07xQPqWZrKWkvccWco4YKBgOdg7n1D9DskiLLXhZlyJZ2sVRiIs5qrEw1Y9IEy8f8iIOJnmD49K67DxI6QxQQvBxOY961%2FsAWbwwvaYZx1TRV%2BT1IJQ8KkXXqWRk5BDFaAy19E19KvNqnza9NGSjTY94LpOuXiKF6ldJSOLH1SLaExxrEDR5%2FKNx1o1a3teIjkvP6Nk8vQnubRR9qT4xV2i%2B9XIAYGDJ%2B8JFFyfPV1Fb9XHa0V9PI%2BbM1kKt9OxNFYBgW4FDeNh5ku9aPV14%2B2ZWm58AOYSuJyZ6%2F2I0nMJAISxxDXBaUxzyqSDxJiDOpZC3TCqRg1KsqzjdBYRWhYrGQlylRfU5C4SjNV1LwRwnKlRmC2eR8qREPhd08HvzOu%2BOEZXUmvxtYmz7ktXklkTS1nKP2oImB6y%2Bcks8AZTyhFejKz%2Fs36chz315qdcaXuspT5aKVVjmYhOy7Zyj0N5ZaMJDrur0GOqUBjRIKN%2BS3UMY3SaXCNdQJr3gPHNzeJMfavwrFrjv2gmGrWdx%2BxRJEbbPYTkKm2Rxb8FXClKLbalk25vSxNFH5xpp2cPRpjLJZSOSVj1F2ej5M5Y48mhrtrLVBYQXuFVbkyHiP2ZlXOQ5cW%2F4e4R7Ia7CE3OeWSpSn4fqBsKgQVLAvoD3%2B5LEdqQWFKx6KnP8KLOIsvOtLHRMljeUprH5uG5dS%2BDb5&X-Amz-Signature=2f639ad89c1761c0895e96275ba3e6bf0b013fc1ba832afc0c98e846473f649c&X-Amz-SignedHeaders=host&x-id=GetObject)


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

