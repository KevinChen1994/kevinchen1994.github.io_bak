---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4662YAQ4UBA%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250218T063246Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEF4aCXVzLXdlc3QtMiJHMEUCIBxoCU2RJzCmH3wYqBsM4R%2B866t2wHUcU79HpX9f2sLPAiEAh\
  M4RAdaDmMniY8ppVqUnUjPnb42vcTC2zc%2B1BfybI0cqiAQIh%2F%2F%2F%2F%2F%2F%2F%2F%2F\
  %2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGeeo%2FnVHJrTmNx3SyrcAztf10YIFHVLwlMQe74uSPj4n\
  1J05LEcxOE1RDHVIJlq2IZ3ly98wrNloymXziWtaTrUwJbQ1x6qFJ0NG7muZq346y4EJ634m2cUgg\
  18Lj2Hru64RRi5pzg8l9ULcHcoIvDT0dEPKTDE2HLbu2GLEXuk4SRH4VN%2B4d1Bu04mFowZSt5WM\
  HuB1nUIFlSJKKqy1nThQX2%2BCaArM%2BBKf%2Byist%2B0XXPmcsTK%2Fq7F0Ia8GrhphIe0PUK5\
  BtCzT1%2FUdXkOalSalK8rts2C1IudmFm2Z%2B3XInirW9JlXJa%2BDWD1BN8IDwgncaNbNCJwX2W\
  o8LCAdeR1QivZp%2FZJaYS1LXNQj1HzKJazJGFu7oix%2BwBjYNrxwUGgtFbPP%2Bwm5qtdaJ4XIU\
  ZL3OErBQ5cR%2Bs6VHlja3ft6cp7cKy1GVBp6fQSgZbDy5XqGY%2Fe9Tuc2gCesecaSuewfWkNqkB\
  qRGSmny%2Fbm2BvEVXnHjzPoaOcT2VQ3%2BJ5T4bQ27R4R8V5xLnudcQXJPkKzvDOdJLHYgh%2BSB\
  HbV%2B%2B5Pg%2FrGcA8l%2BCYsA1zbv%2BdL4RgDxuFGeW3tTTegVDTL3cjcjijCNaSPWzDAaAEh\
  lk2F1HZ4X2MyY3jMgvIrKRhAVD4cSNNL7RbSbdWMKTI0L0GOqUBYhfghbkSI74or4P19LXqeo1bj6\
  nZGp7LS1qUS%2B2%2FxX6fEaitbbG6BTTmgmQAmsYhgav%2BoRXnm2ETQjjqH0Vyx51vvZAbC9ZJd\
  dA8XKk7uOABHBIhXZGaDvpQ98Y%2B6riJY06Ehsr%2BIZD2sM6gz%2BwioEDcbokyKTHuP0j%2BrG\
  gpXuQN%2FnRhn6KoGuE5EnYT8OnA1nLHcAebsOLXCbS2w3LyJBNTBKDV&X-Amz-Signature=84fc\
  56b095b66e7c0cfbe155c6c2fa56f264c88d7078fde7f501b21fc445e265&X-Amz-SignedHead\
  ers=host&x-id=GetObject"
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
        redential=ASIAZI2LB466SB3KJ2QY%2F20250218%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250218T063119Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEF4aCXVzLXdlc3QtMiJHMEUCICWggx0kQt9IqX%2BCdX8KM2acM90Ec\
        e%2FL6%2Fj13sMV1zt%2FAiEA8a30M4OJYbOqFBnf%2BAsA3gvWBEbM9cQalHzYa5%2FJrK\
        gqiAQIh%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDBZjosQ\
        j21OnT%2FgCjyrcA5YIyeLD9DWZHZu1RKsu5pRLsPzLfYD6WoYGhAYMRMQQabWwg9rGZp3K\
        XB4IkQVvgicK9u3YREcToGE3H9ni88tu7vtsULy5JOsGy61CvlCEvsJcWYRBAUNJHggFqem\
        bKSRLfMDLF%2FwTpmiZFwMBBgOuIJpH7zarLYei5XANIGKlZSFdTfPjMa5f3vTLKQ1sg%2F\
        jNQ%2BJtbnszQXVptaWoxFrItgxJhipRuDJqrD5phUL7unTz%2BGZ88MSs1WiDz%2FGzeUC\
        SlIU3xHrcd7xS7wsl4ovsBznioCtGKkYsoiISw%2Bx9Qmsw8JrFFHMvanVDLAS87LYpi0sR\
        BrDSlitMRt8H6YdMoaWU8DvMxlNwlYJuT0yTiR9l2vX%2BiawLl6GJ8TKVS4e0zNRUXjmj3\
        42%2B5m7su3fDCKrHOXs1dOHbDcRvpm6LAuYeJDjuIW9nJNTIp2vCbz43mjv872GF83VETK\
        fvs79aLbIyknpFxOA7h%2BUudT6X5HRgj9NabhsW8HLQg8x6cjXY9ke5jaqbPmy1unQUZsI\
        3ZfO4hRt7fK6b48vyuNc4TFp9l70w%2FHL%2FTGajFZp9%2BvuQLt%2Fe53KKFYokow68JU\
        u%2BQvPAfo9fYSgCo3hWXnsWeax3wIZYwyPUOuzXMLLI0L0GOqUBz1RS95WyDOUdJgjRIpr\
        6jnDQkW0em4lSBECtxWMoXhJfUNwzhv2bYqYOKMqj8MgYpYnIgOgIO7Sg84XOV0LmlsBuBg\
        IOuewoR892vP98bczKQRfoy7hkabHgKQJK%2BhuqO0quzJDLH%2F1Y3RowMfsVDFXTaHSqC\
        gs5jWuTPZyXqffWobONPYSOhTjfzs%2Fm%2Fi8xvs8y70chtpZ3OdcSo5JabIlW78KX&X-A\
        mz-Signature=7579b33439337b121ae695e36889a7bc91bb8db376e8ccfde1320933b9\
        2e8570&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-18T07:31:19.143Z"
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
UPDATE_TIME: "2025-02-18T06:32:51.440Z"
EXPIRY_TIME: "2025-02-18T07:32:43.093Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TPSXHZQV%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T063243Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEF4aCXVzLXdlc3QtMiJHMEUCIBa0coA8mfGu1xoLjqOZWyr73%2B14E9eB3kIsqUhvcHC%2FAiEA4PJufX1vVxiagGoKqb%2Bs%2FnscCcwuM4g61doDO6N7Sw4qiAQIh%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDJfzn%2Bv864W5PnrhUyrcAz77cpI4rdyrVeJpEDdA%2FcnzZhu1DG5nN3e7ojItvYfGb0ASEJ7YyrIQ74VZ50xozyvwLDfTxeS4BT80D2ig09MLI7HpQqlyo%2BuYoHuGNAEWvof9WibQVXLydLH8HaooUnjusQT06cHNNlEz6mMHAo7Co4v32U3XGjYK4D%2BoeKU6%2FJ6fTwx8pjl1B4WgjyfoSt%2FqsegOZm8y%2FeK0N%2BcXqAlBR3hrYbd7LxWbQNTldTFL%2BuAsJeLRYTrmWW%2B7bxFiV6VCagI3LhQOrkYqlR%2BrYU8LvkZNqa%2FTq0hjdbbiIyTj%2FfV9dQ5yXkmv%2BfWMV%2BHSLqskf%2Bq82QCaM32Gm8mFifOexSLWoNp9HQJuCdFbOkBcAQl9orrAwxag1ipt1mtFvjkKtR11GreUY1xrlytwDBF7Sf9vrBX1BbzgXB6Z7o7P2Ws06JB%2BFJ7i13vmaKSd%2FPhDpbpFATdOBUUogAclhsVPAZj4%2FElBtjeinLWq8V525k0sR0u0cGiY14xYMpayfE7RdKdij2bwiUO7I9JrHgOgs3zjOmXwb4KXfxVv2sRIRu1xyMKk2tadrPHQgn430CoZLxt6SmbrWi1ugDdpzhTUWHttyPFsco9eyQcmvC2i6aZKfdPyE99cEf%2FcMJzI0L0GOqUBWBhGbaQCroGvsPo3NmlOA5cNVlCCm2yc8brTw19eehCdcSPhu1B7VmlC9fQdJjPWYYI8M1kyOd2XkKLYAKMeU9tnkfZDCNx3t7iXUfqwofkY0e%2BxRIpzgyyb8vBBT4LV%2FZhtxTKkhmPnvWEJ%2FuDFNc%2BodP3P2MkfY4uZ0egL6mj%2FMNFiAobLb7478oRkxj0EYyl%2FIgiRkFN8l1%2FlFfn6OfR9wXCL&X-Amz-Signature=35a7ff799ed8544838518019979ac4f2f99197448a96882c00ce5a24de9397ef&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TPSXHZQV%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T063243Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEF4aCXVzLXdlc3QtMiJHMEUCIBa0coA8mfGu1xoLjqOZWyr73%2B14E9eB3kIsqUhvcHC%2FAiEA4PJufX1vVxiagGoKqb%2Bs%2FnscCcwuM4g61doDO6N7Sw4qiAQIh%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDJfzn%2Bv864W5PnrhUyrcAz77cpI4rdyrVeJpEDdA%2FcnzZhu1DG5nN3e7ojItvYfGb0ASEJ7YyrIQ74VZ50xozyvwLDfTxeS4BT80D2ig09MLI7HpQqlyo%2BuYoHuGNAEWvof9WibQVXLydLH8HaooUnjusQT06cHNNlEz6mMHAo7Co4v32U3XGjYK4D%2BoeKU6%2FJ6fTwx8pjl1B4WgjyfoSt%2FqsegOZm8y%2FeK0N%2BcXqAlBR3hrYbd7LxWbQNTldTFL%2BuAsJeLRYTrmWW%2B7bxFiV6VCagI3LhQOrkYqlR%2BrYU8LvkZNqa%2FTq0hjdbbiIyTj%2FfV9dQ5yXkmv%2BfWMV%2BHSLqskf%2Bq82QCaM32Gm8mFifOexSLWoNp9HQJuCdFbOkBcAQl9orrAwxag1ipt1mtFvjkKtR11GreUY1xrlytwDBF7Sf9vrBX1BbzgXB6Z7o7P2Ws06JB%2BFJ7i13vmaKSd%2FPhDpbpFATdOBUUogAclhsVPAZj4%2FElBtjeinLWq8V525k0sR0u0cGiY14xYMpayfE7RdKdij2bwiUO7I9JrHgOgs3zjOmXwb4KXfxVv2sRIRu1xyMKk2tadrPHQgn430CoZLxt6SmbrWi1ugDdpzhTUWHttyPFsco9eyQcmvC2i6aZKfdPyE99cEf%2FcMJzI0L0GOqUBWBhGbaQCroGvsPo3NmlOA5cNVlCCm2yc8brTw19eehCdcSPhu1B7VmlC9fQdJjPWYYI8M1kyOd2XkKLYAKMeU9tnkfZDCNx3t7iXUfqwofkY0e%2BxRIpzgyyb8vBBT4LV%2FZhtxTKkhmPnvWEJ%2FuDFNc%2BodP3P2MkfY4uZ0egL6mj%2FMNFiAobLb7478oRkxj0EYyl%2FIgiRkFN8l1%2FlFfn6OfR9wXCL&X-Amz-Signature=7d304eb3ce40ca066763dc198d043bb2cf928dea7b50a7ae6eeda73b875b4451&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TPSXHZQV%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T063243Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEF4aCXVzLXdlc3QtMiJHMEUCIBa0coA8mfGu1xoLjqOZWyr73%2B14E9eB3kIsqUhvcHC%2FAiEA4PJufX1vVxiagGoKqb%2Bs%2FnscCcwuM4g61doDO6N7Sw4qiAQIh%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDJfzn%2Bv864W5PnrhUyrcAz77cpI4rdyrVeJpEDdA%2FcnzZhu1DG5nN3e7ojItvYfGb0ASEJ7YyrIQ74VZ50xozyvwLDfTxeS4BT80D2ig09MLI7HpQqlyo%2BuYoHuGNAEWvof9WibQVXLydLH8HaooUnjusQT06cHNNlEz6mMHAo7Co4v32U3XGjYK4D%2BoeKU6%2FJ6fTwx8pjl1B4WgjyfoSt%2FqsegOZm8y%2FeK0N%2BcXqAlBR3hrYbd7LxWbQNTldTFL%2BuAsJeLRYTrmWW%2B7bxFiV6VCagI3LhQOrkYqlR%2BrYU8LvkZNqa%2FTq0hjdbbiIyTj%2FfV9dQ5yXkmv%2BfWMV%2BHSLqskf%2Bq82QCaM32Gm8mFifOexSLWoNp9HQJuCdFbOkBcAQl9orrAwxag1ipt1mtFvjkKtR11GreUY1xrlytwDBF7Sf9vrBX1BbzgXB6Z7o7P2Ws06JB%2BFJ7i13vmaKSd%2FPhDpbpFATdOBUUogAclhsVPAZj4%2FElBtjeinLWq8V525k0sR0u0cGiY14xYMpayfE7RdKdij2bwiUO7I9JrHgOgs3zjOmXwb4KXfxVv2sRIRu1xyMKk2tadrPHQgn430CoZLxt6SmbrWi1ugDdpzhTUWHttyPFsco9eyQcmvC2i6aZKfdPyE99cEf%2FcMJzI0L0GOqUBWBhGbaQCroGvsPo3NmlOA5cNVlCCm2yc8brTw19eehCdcSPhu1B7VmlC9fQdJjPWYYI8M1kyOd2XkKLYAKMeU9tnkfZDCNx3t7iXUfqwofkY0e%2BxRIpzgyyb8vBBT4LV%2FZhtxTKkhmPnvWEJ%2FuDFNc%2BodP3P2MkfY4uZ0egL6mj%2FMNFiAobLb7478oRkxj0EYyl%2FIgiRkFN8l1%2FlFfn6OfR9wXCL&X-Amz-Signature=fa33aa338e0365cd5ff32cb75db3069d67379ff0a8caf1b4b2fd20766e820a0a&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TPSXHZQV%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T063243Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEF4aCXVzLXdlc3QtMiJHMEUCIBa0coA8mfGu1xoLjqOZWyr73%2B14E9eB3kIsqUhvcHC%2FAiEA4PJufX1vVxiagGoKqb%2Bs%2FnscCcwuM4g61doDO6N7Sw4qiAQIh%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDJfzn%2Bv864W5PnrhUyrcAz77cpI4rdyrVeJpEDdA%2FcnzZhu1DG5nN3e7ojItvYfGb0ASEJ7YyrIQ74VZ50xozyvwLDfTxeS4BT80D2ig09MLI7HpQqlyo%2BuYoHuGNAEWvof9WibQVXLydLH8HaooUnjusQT06cHNNlEz6mMHAo7Co4v32U3XGjYK4D%2BoeKU6%2FJ6fTwx8pjl1B4WgjyfoSt%2FqsegOZm8y%2FeK0N%2BcXqAlBR3hrYbd7LxWbQNTldTFL%2BuAsJeLRYTrmWW%2B7bxFiV6VCagI3LhQOrkYqlR%2BrYU8LvkZNqa%2FTq0hjdbbiIyTj%2FfV9dQ5yXkmv%2BfWMV%2BHSLqskf%2Bq82QCaM32Gm8mFifOexSLWoNp9HQJuCdFbOkBcAQl9orrAwxag1ipt1mtFvjkKtR11GreUY1xrlytwDBF7Sf9vrBX1BbzgXB6Z7o7P2Ws06JB%2BFJ7i13vmaKSd%2FPhDpbpFATdOBUUogAclhsVPAZj4%2FElBtjeinLWq8V525k0sR0u0cGiY14xYMpayfE7RdKdij2bwiUO7I9JrHgOgs3zjOmXwb4KXfxVv2sRIRu1xyMKk2tadrPHQgn430CoZLxt6SmbrWi1ugDdpzhTUWHttyPFsco9eyQcmvC2i6aZKfdPyE99cEf%2FcMJzI0L0GOqUBWBhGbaQCroGvsPo3NmlOA5cNVlCCm2yc8brTw19eehCdcSPhu1B7VmlC9fQdJjPWYYI8M1kyOd2XkKLYAKMeU9tnkfZDCNx3t7iXUfqwofkY0e%2BxRIpzgyyb8vBBT4LV%2FZhtxTKkhmPnvWEJ%2FuDFNc%2BodP3P2MkfY4uZ0egL6mj%2FMNFiAobLb7478oRkxj0EYyl%2FIgiRkFN8l1%2FlFfn6OfR9wXCL&X-Amz-Signature=2effd5681350de4adcd15e4f4fac818025ef5781ecd6110f8484e06978a345a7&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TPSXHZQV%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T063243Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEF4aCXVzLXdlc3QtMiJHMEUCIBa0coA8mfGu1xoLjqOZWyr73%2B14E9eB3kIsqUhvcHC%2FAiEA4PJufX1vVxiagGoKqb%2Bs%2FnscCcwuM4g61doDO6N7Sw4qiAQIh%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDJfzn%2Bv864W5PnrhUyrcAz77cpI4rdyrVeJpEDdA%2FcnzZhu1DG5nN3e7ojItvYfGb0ASEJ7YyrIQ74VZ50xozyvwLDfTxeS4BT80D2ig09MLI7HpQqlyo%2BuYoHuGNAEWvof9WibQVXLydLH8HaooUnjusQT06cHNNlEz6mMHAo7Co4v32U3XGjYK4D%2BoeKU6%2FJ6fTwx8pjl1B4WgjyfoSt%2FqsegOZm8y%2FeK0N%2BcXqAlBR3hrYbd7LxWbQNTldTFL%2BuAsJeLRYTrmWW%2B7bxFiV6VCagI3LhQOrkYqlR%2BrYU8LvkZNqa%2FTq0hjdbbiIyTj%2FfV9dQ5yXkmv%2BfWMV%2BHSLqskf%2Bq82QCaM32Gm8mFifOexSLWoNp9HQJuCdFbOkBcAQl9orrAwxag1ipt1mtFvjkKtR11GreUY1xrlytwDBF7Sf9vrBX1BbzgXB6Z7o7P2Ws06JB%2BFJ7i13vmaKSd%2FPhDpbpFATdOBUUogAclhsVPAZj4%2FElBtjeinLWq8V525k0sR0u0cGiY14xYMpayfE7RdKdij2bwiUO7I9JrHgOgs3zjOmXwb4KXfxVv2sRIRu1xyMKk2tadrPHQgn430CoZLxt6SmbrWi1ugDdpzhTUWHttyPFsco9eyQcmvC2i6aZKfdPyE99cEf%2FcMJzI0L0GOqUBWBhGbaQCroGvsPo3NmlOA5cNVlCCm2yc8brTw19eehCdcSPhu1B7VmlC9fQdJjPWYYI8M1kyOd2XkKLYAKMeU9tnkfZDCNx3t7iXUfqwofkY0e%2BxRIpzgyyb8vBBT4LV%2FZhtxTKkhmPnvWEJ%2FuDFNc%2BodP3P2MkfY4uZ0egL6mj%2FMNFiAobLb7478oRkxj0EYyl%2FIgiRkFN8l1%2FlFfn6OfR9wXCL&X-Amz-Signature=62156f1e7a0dce06873b2659810a394edcd14d2fc3be76df431244db63ff6576&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665FS4MI4K%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T063244Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEF4aCXVzLXdlc3QtMiJHMEUCIAsyzmffas1bIPq1BV%2B6hTaMsWiVM8v%2BUo3c63oCJVORAiEAisB4EbnIZV6sfoe2waOLvui6Yb4vFbZdFA6Q%2BIODF6YqiAQIh%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDH4EWvGjyCUoOZ2v1ircA2XMJqh3%2BzkDC3C8l5Ix9zFAX%2BwIafZCuekSEWBM55BIsroyJtuHLboOp7MujFAKYsiNBclaCD4B4hwCR48IR9xSMxLa0wpehJ6LRspIMYlhXJfcbTem2L7f8%2BsL9EPK5z9xPxSXLxRHEH6T2AheJUmIqNpunN04KtAZmIY0QeV5pvjOwO8R6FxBIGNVoWtAtg2%2FupkNsXlghoatKciV9LAR0wqJ0FmaiLifdCpJsRFdlh%2BGL1wX8HmKLd%2FwOGde5hjyqpFVi%2FttZgb4ASzMeGt34bOTrmG4T1eQNVDAJLZpp6gaHK5cNvqg3CeKReq5E8nLanOUPfj3hGp3Vvpzcq%2BapRS4rP5AYYHaucnicli1oC%2BO%2FaxtTOe%2FULOB69uN8p5HsOT4Zg2O7VwKmthJAEZF%2F%2FthwhfslavqvK1wNPKjmV7pXwLOfLYNC0Nc7AUM3GZfN6gSLlnL0CAzH6GpKhjqe1xAlbV4arlgYm6eVY7TrMj1JhUNfUXBJxrOaZSFZRX80el5GvRCLBMWBiLLWfmYwPdhagPvhDeWExJn7pBbkbhUUKzKJobioUjvsJki9WDz8SuPfYH4QxAk8jp1TiisyfKcIQOhJMLcmHEbBTSKIHHEyZ8DOZfcDPtKMJzI0L0GOqUBc8D%2BTvwv7Z%2BGVzqbgM7tf9mLHDm2G8%2Fi1CNpEGXAWBZcofWhYJ%2Bz8fJfkbpJvQWotXykiaGSeOQYyxerNh3%2BF0jZ01BhJu1Xh2K6%2BWj7HgZNxj0CA98yKMf6rM10d1n64K7SpACZM7lEfoZPBm1KNcLCGekPgq6P%2BG7He%2BHQJOhwrIrkWF2sp8oPKOPtTp%2Bg4xGnC9QnWCpZ0A6OJmhp64GhUJbI&X-Amz-Signature=3966d78e78a4fd2a50639dd71d5474ffde47706068e5417b57ad541768a4ac1d&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662D4Z2LUT%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T063246Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEF4aCXVzLXdlc3QtMiJHMEUCIQCEyzOONnL7G1lkPnvmLrRnDzg%2FEiihz91e8Pj168oMSAIgBJnxRba%2BlfZ1hmkQGDZg98VNxboksi8z2KfsGMYzf8wqiAQIh%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDG4gqkD8ZOX8y7WI5ircAzRnVPF6TLEjbMnkGl1EvtXIwvENBA3VIOb8AYOgK2f%2FdBJQuKGv9FtQ01Lx6BJDsYN2%2F2srrGQaHCK%2Fr00iDc4Ggh9qevEYbct4J9uMFqVshZp7QVzIix7XxRi0Bpn%2F4IVoaPi37tKSlS7ddbtCeQVpqDTjwn3oLV9aClx2DVQscmOkjMBYsXdT4lMD93BD3%2BymvzrMa7xYAyx4uTV%2FgKxmAZ6dw77fHnS2lrmU2iIR3fnEzHejdQpGGARfeoVnjiGIAx0cVBteEYG2EJixo2lRM%2FYmuVjdJVAsZsHJHmOUMfe6v67pgYv5rXsTND4r3JavZs3x%2BCsMowFVnwavmgqR9OCbr0t6c2%2BmrYi%2BWkiRG04Qu%2BYNh0Gs6DDml2Wbzs2%2BJ35MN4xl5e8Q3phCh1ubvz0dmWFF%2Bnh%2F7PPYgp3aNa1bcSCRYN1d8lTNQLeXYnU0iM3odlewiIo4os4fhMmJ1Fuq1hFz%2Be7P%2F8%2BXMN6v5mvwmH632Sl7yzZsyYv5HlTRul8B1OCs%2BfWNCr%2Bj1A2zokLy0whWydO0DBQkvag%2BiIaUSYOsB31VoZcYE6W%2FyUGViE0WOQY1p3%2FAyDsSZHnP7df%2BjtN%2BTL%2BGA%2FJvocIWSJmwCWf%2FcFeI74%2FCMJPI0L0GOqUBOPbXOQiq06IuOa%2FaVDnjPAa7LQ6Of7fopME311OTJ%2FjuDLoSqc%2FhFlO47rVqi8CAV%2FkCFdi80bEExImInN6BcBhMzNOQBCHqBna0vlf4YGwnZpw8s8q4cwxXD8FvvoKLHWOIUMEoG%2FYka15%2FD0Z9l1zAcr2G7Se2nhqelOQW8LxadLprGleb65jVChERdoYHrVIf6dgubjyxeJ8UsKeU1Ar1JjP2&X-Amz-Signature=cbc89097aca5dfa0e81fac6197938fc59bb17501dcef5fcbadf4adf8b6998654&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TPSXHZQV%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T063243Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEF4aCXVzLXdlc3QtMiJHMEUCIBa0coA8mfGu1xoLjqOZWyr73%2B14E9eB3kIsqUhvcHC%2FAiEA4PJufX1vVxiagGoKqb%2Bs%2FnscCcwuM4g61doDO6N7Sw4qiAQIh%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDJfzn%2Bv864W5PnrhUyrcAz77cpI4rdyrVeJpEDdA%2FcnzZhu1DG5nN3e7ojItvYfGb0ASEJ7YyrIQ74VZ50xozyvwLDfTxeS4BT80D2ig09MLI7HpQqlyo%2BuYoHuGNAEWvof9WibQVXLydLH8HaooUnjusQT06cHNNlEz6mMHAo7Co4v32U3XGjYK4D%2BoeKU6%2FJ6fTwx8pjl1B4WgjyfoSt%2FqsegOZm8y%2FeK0N%2BcXqAlBR3hrYbd7LxWbQNTldTFL%2BuAsJeLRYTrmWW%2B7bxFiV6VCagI3LhQOrkYqlR%2BrYU8LvkZNqa%2FTq0hjdbbiIyTj%2FfV9dQ5yXkmv%2BfWMV%2BHSLqskf%2Bq82QCaM32Gm8mFifOexSLWoNp9HQJuCdFbOkBcAQl9orrAwxag1ipt1mtFvjkKtR11GreUY1xrlytwDBF7Sf9vrBX1BbzgXB6Z7o7P2Ws06JB%2BFJ7i13vmaKSd%2FPhDpbpFATdOBUUogAclhsVPAZj4%2FElBtjeinLWq8V525k0sR0u0cGiY14xYMpayfE7RdKdij2bwiUO7I9JrHgOgs3zjOmXwb4KXfxVv2sRIRu1xyMKk2tadrPHQgn430CoZLxt6SmbrWi1ugDdpzhTUWHttyPFsco9eyQcmvC2i6aZKfdPyE99cEf%2FcMJzI0L0GOqUBWBhGbaQCroGvsPo3NmlOA5cNVlCCm2yc8brTw19eehCdcSPhu1B7VmlC9fQdJjPWYYI8M1kyOd2XkKLYAKMeU9tnkfZDCNx3t7iXUfqwofkY0e%2BxRIpzgyyb8vBBT4LV%2FZhtxTKkhmPnvWEJ%2FuDFNc%2BodP3P2MkfY4uZ0egL6mj%2FMNFiAobLb7478oRkxj0EYyl%2FIgiRkFN8l1%2FlFfn6OfR9wXCL&X-Amz-Signature=730574d8c06e2e02b19966d78717cc98746633f13dcc51f7e208efaa6f5f55e2&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TPSXHZQV%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T063243Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEF4aCXVzLXdlc3QtMiJHMEUCIBa0coA8mfGu1xoLjqOZWyr73%2B14E9eB3kIsqUhvcHC%2FAiEA4PJufX1vVxiagGoKqb%2Bs%2FnscCcwuM4g61doDO6N7Sw4qiAQIh%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDJfzn%2Bv864W5PnrhUyrcAz77cpI4rdyrVeJpEDdA%2FcnzZhu1DG5nN3e7ojItvYfGb0ASEJ7YyrIQ74VZ50xozyvwLDfTxeS4BT80D2ig09MLI7HpQqlyo%2BuYoHuGNAEWvof9WibQVXLydLH8HaooUnjusQT06cHNNlEz6mMHAo7Co4v32U3XGjYK4D%2BoeKU6%2FJ6fTwx8pjl1B4WgjyfoSt%2FqsegOZm8y%2FeK0N%2BcXqAlBR3hrYbd7LxWbQNTldTFL%2BuAsJeLRYTrmWW%2B7bxFiV6VCagI3LhQOrkYqlR%2BrYU8LvkZNqa%2FTq0hjdbbiIyTj%2FfV9dQ5yXkmv%2BfWMV%2BHSLqskf%2Bq82QCaM32Gm8mFifOexSLWoNp9HQJuCdFbOkBcAQl9orrAwxag1ipt1mtFvjkKtR11GreUY1xrlytwDBF7Sf9vrBX1BbzgXB6Z7o7P2Ws06JB%2BFJ7i13vmaKSd%2FPhDpbpFATdOBUUogAclhsVPAZj4%2FElBtjeinLWq8V525k0sR0u0cGiY14xYMpayfE7RdKdij2bwiUO7I9JrHgOgs3zjOmXwb4KXfxVv2sRIRu1xyMKk2tadrPHQgn430CoZLxt6SmbrWi1ugDdpzhTUWHttyPFsco9eyQcmvC2i6aZKfdPyE99cEf%2FcMJzI0L0GOqUBWBhGbaQCroGvsPo3NmlOA5cNVlCCm2yc8brTw19eehCdcSPhu1B7VmlC9fQdJjPWYYI8M1kyOd2XkKLYAKMeU9tnkfZDCNx3t7iXUfqwofkY0e%2BxRIpzgyyb8vBBT4LV%2FZhtxTKkhmPnvWEJ%2FuDFNc%2BodP3P2MkfY4uZ0egL6mj%2FMNFiAobLb7478oRkxj0EYyl%2FIgiRkFN8l1%2FlFfn6OfR9wXCL&X-Amz-Signature=3bd9f1aba99d931d87ff92d0d0bb9752f23289066214baa52dc60a1531dc1ed9&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TPSXHZQV%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T063243Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEF4aCXVzLXdlc3QtMiJHMEUCIBa0coA8mfGu1xoLjqOZWyr73%2B14E9eB3kIsqUhvcHC%2FAiEA4PJufX1vVxiagGoKqb%2Bs%2FnscCcwuM4g61doDO6N7Sw4qiAQIh%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDJfzn%2Bv864W5PnrhUyrcAz77cpI4rdyrVeJpEDdA%2FcnzZhu1DG5nN3e7ojItvYfGb0ASEJ7YyrIQ74VZ50xozyvwLDfTxeS4BT80D2ig09MLI7HpQqlyo%2BuYoHuGNAEWvof9WibQVXLydLH8HaooUnjusQT06cHNNlEz6mMHAo7Co4v32U3XGjYK4D%2BoeKU6%2FJ6fTwx8pjl1B4WgjyfoSt%2FqsegOZm8y%2FeK0N%2BcXqAlBR3hrYbd7LxWbQNTldTFL%2BuAsJeLRYTrmWW%2B7bxFiV6VCagI3LhQOrkYqlR%2BrYU8LvkZNqa%2FTq0hjdbbiIyTj%2FfV9dQ5yXkmv%2BfWMV%2BHSLqskf%2Bq82QCaM32Gm8mFifOexSLWoNp9HQJuCdFbOkBcAQl9orrAwxag1ipt1mtFvjkKtR11GreUY1xrlytwDBF7Sf9vrBX1BbzgXB6Z7o7P2Ws06JB%2BFJ7i13vmaKSd%2FPhDpbpFATdOBUUogAclhsVPAZj4%2FElBtjeinLWq8V525k0sR0u0cGiY14xYMpayfE7RdKdij2bwiUO7I9JrHgOgs3zjOmXwb4KXfxVv2sRIRu1xyMKk2tadrPHQgn430CoZLxt6SmbrWi1ugDdpzhTUWHttyPFsco9eyQcmvC2i6aZKfdPyE99cEf%2FcMJzI0L0GOqUBWBhGbaQCroGvsPo3NmlOA5cNVlCCm2yc8brTw19eehCdcSPhu1B7VmlC9fQdJjPWYYI8M1kyOd2XkKLYAKMeU9tnkfZDCNx3t7iXUfqwofkY0e%2BxRIpzgyyb8vBBT4LV%2FZhtxTKkhmPnvWEJ%2FuDFNc%2BodP3P2MkfY4uZ0egL6mj%2FMNFiAobLb7478oRkxj0EYyl%2FIgiRkFN8l1%2FlFfn6OfR9wXCL&X-Amz-Signature=b6cdfd3059541795f793f0f7beff6fba8250d4d7b1b03bb55e043590e79170a9&X-Amz-SignedHeaders=host&x-id=GetObject)


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

