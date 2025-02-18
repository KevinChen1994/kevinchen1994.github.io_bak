---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4666K5LWYA5%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250218T142324Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEGYaCXVzLXdlc3QtMiJHMEUCICSrLf%2FGkuSJX1XKlj8x3WA7ZRPq3Mu5pE8HXBPC5IbKAiEAh\
  n%2BIYvKa%2FjjurbEf4GAda4hawDI0PWDBK99FfaVD0EcqiAQIjv%2F%2F%2F%2F%2F%2F%2F%2F\
  %2F%2FARAAGgw2Mzc0MjMxODM4MDUiDD%2Fue0JYWWQ3cOchZSrcA%2FwQEY6%2B7%2BwNV2EgxtB\
  Jfea4AxPd8Hf3UdI1DWiZAmB12blgftrgLSMs45osnp4mjABB9LCcl%2BCu%2FdzaBHueo8BaJOCy\
  c5G4ezoqJUxp4n9ts2e%2FSGIlwy1K5FKb7vyC6Qr0pwV8m48Q3YR3inEnTgjpAHBghtZ8v3pxW73\
  yGXxs60ir2bWz9di%2BKLkMlsPOxiNf5PebEJR6bukiIFHtVWCBL%2BdO5PuBIRzO2REcDQobq5Ys\
  PwtMVo7f8uDBiQ9vyulhk2pDhdrJjFwyaql8yLrLpNjTYm7mct7tG8wRv%2FDWKHeHV3WTNA9TY8b\
  9eeDlYZc2NsMzG%2FuEoihVBgpnf3w5FMMXKOHOsUi2hDx9s2YftH0nINWQr0bnr1jkChOnQbFzHv\
  OaN1xGwZ5L2Z6SwuwsrFE%2BAFVEOOZ0ygJvBBaLMIEJBy%2Faw%2FVUcmu2mozBvzsZQbfYoKRPr\
  OJUt6FDhMjiQYfp9yU7KtUaW78A%2BfGBlMX4e5hq04uxArZBBDo6uLsJsbG0A4zqJi3oYkVLTepb\
  jDyXkC2%2FRni1ldzmQM8elSLbBk3mcmFZ9UFNfZSnMSu4R04fNM%2F4wBMUX9kx3SKMLe7Rcy6NA\
  AZjV03sSn44K16XXp5%2B4NwH1kWuMP6T0r0GOqUBMQlxRYmAOd7bv0I6fCEzHp4hyR5tg8eYj3u7\
  GpLjaA4ZdCZi2CGaQC2KTXRmqnbT%2BXPqK3djeAStLWVJ6sQGR4jqP%2BzgvIJ5CY1owzYjY6977\
  Or6XbvZj0W2lcAfhjhVC%2BMZnDBRulSDjfPVUrav7Lo4XGsDxJQhe4nW%2FBf%2BAU5LqozmgBaR\
  8hWJ0FpEPmqVkEEuoP2O2gVFSZyBNwXqGZ55QOeD&X-Amz-Signature=e58dd601d2a1908b007c\
  157d858ebc96a36f7338f9eb67da88c1f053135b9bf0&X-Amz-SignedHeaders=host&x-id=Ge\
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
        redential=ASIAZI2LB466VK2LKDBB%2F20250218%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250218T142146Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEGYaCXVzLXdlc3QtMiJIMEYCIQC6GvvelOZsBmHhfPXOpaJYDte44o%\
        2BVcIcS%2BjDf4JA9QAIhALbFcQ6N8Tu30v%2B0PdLjO8q8dmNWqS%2BHT4hdG6m4DPdRKo\
        gECI7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxwcF%2BKpVD\
        PcxfnUBwq3ANgjZybKhfKgNDggsu58zgkL5oSLf1PJ%2FSr9q61YSfEDL6j94kQ5TpTkOOR\
        FCAZhMfCWjxc8Bj0zVK2UQZWBYQ%2FXdlxFx9G3S7COsuhXgdc9RAZ8f6Dw%2FxeuPg9sBE\
        dH5KobLvOWS9dFLtfSmMXT8Yunvhh%2BVVrwPzSiYijnRtEf0h722pbZDbOGC5%2BsPUzLx\
        HS%2BEMT9dTnyqMT8NExeQqloum3aj%2FSQ4hUM%2FF5SeB%2Bdz5CRD0vyvuJlIrJPwWYK\
        aMj1SyRb5mzS7DHY4eXfSLZ4oTnW%2By6swiHxbaGi1wg6YdTwX%2BZp%2BA1PjKfGm8OCN\
        xBdMWUoUG2ZzA30Zxt4EPSppsYO4UtQ94HQbjD41mWLyrJ29SDu9PkI7Qc3HnMnjqbaR3Fl\
        mI7AGUJFyPNr%2BbRMlRkGsfH4ZGtyRTX8EUHSouSqyatZxpGG4TukRBRA7DO7RYvHXOYCb\
        a11WxpZSD%2BBPMpiwS94hvSuoXuWIZ%2FoeH%2FUEtXI8uHbtYLJSWN%2FVvN5n71Ax6s3\
        4OKnAzfkvgWpgannOI9LHOZZ5Z26X0PlQeFZehx%2BiS0W3vJUiYKpLFRWumbrOMVPjWrWw\
        7c9cmG4BQoOfs%2F1hTPcWyPdNmwXkezZkL4FafAp6UHXjCllNK9BjqkAa9BioKeKfS3Qwl\
        iB2pMV4JZk%2FbAM0EqoXQzPiWD1TzbQ0hoBP%2F%2F4rmC77mCGwmpdhb2%2BP4HDakfwa\
        v3fGDzO%2FVE59cOpBLYOC2AgcsR7CdkOivpIhG4AnLqWOdml%2B118QjLAOyCZraeIojNF\
        2k22Id6GHByTuMoODUTafWGoFT9PSXnSsUg7%2F2a0Gc6rD214gd40AX%2F95VtaFgiYUMt\
        qWqXGHzd&X-Amz-Signature=5085f984b7d79707418d9273acf1200aba0bde9b28ce0c\
        97635d63bccce9bd42&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-18T15:21:46.771Z"
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
UPDATE_TIME: "2025-02-18T14:23:29.755Z"
EXPIRY_TIME: "2025-02-18T15:23:22.527Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TKQE3EJZ%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T142323Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGYaCXVzLXdlc3QtMiJHMEUCIAO4DH45qBpxR7SSJZn3%2Fb8LsoZxecoRmAnZYLrsmeSvAiEA7DpX0u57YnLzA%2FcEBDhUCVFsnECuxb%2FSZeoH%2B%2Bq68JcqiAQIj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKIsChpNglxrOBdb2yrcA6%2FvVjyC4XqGfrx0TNzlRSmn4dpyX9J0XuIuYde%2FnPU5M0yx%2FDSGUTWy14E0AD%2FCCyI%2BSkKKdFgXUuh1N9yn0lYuoXdbLaIwL1%2FBcl9yRGYgvsRqnybeSRBDOPBXuUGLCFrqfdwJ751fzOkYBK02Iqt4YXi%2BCl4NIrMTYzjDCMJRVHJVKCIGkfsOWpblNQlSbA0Gsng3wT19uUvgWO1Yw1c%2F9A7ayriFZZslZIr72fuy1LsKv7avwBQOTm%2Bs8rUhcDrovrYA5P9JOdNqzoJ%2FkA%2FeltwRKJZqyol2knci%2BrZvdCzHPjzPDrn5rkR5QmvaLQYMu6i%2F9LbXcWBj3mIcxAFIrA%2Fxin0tnyuVtCMMhN7zj8IujF8EVPWUOWnHrIHk2Aj8fU18dIi1DVk7siA%2FVpqGYPr6%2Ffk%2F259hlk8Owqg8RcVUgm4bkyYamMblinfb5N1s%2FdrSawtZmU42NU18jZJb4Ef0D%2BDtLHMgMtUgnUnVISys5Cw0MIC79XfI7sWN3CEgPrmU0Ku3Z4xoinOlB2a3whLHTEuClOI3EqDecCC1aq%2FEyy3fWQH6aUTZgtOnX%2FTD9p5wP0BN7xAtGUFwUponJNFttn9QIx7t4g0f5rRUduC2ShAFPUXW%2Fg0qMJqU0r0GOqUBKnEia4mByk%2BQ67drgKjPR9mYM0XdEeVjNfE%2B2B1DejqBLsFMjvQ6ujZcKo04ZRHsH9g3KuX0DeetDwc4O2lkvefHa%2FzeTFumTdrw%2Bzb1y5RhdloU%2F0wo2oX8ahWeo9l7ItESTbyMf2XE%2F%2FgweqctA59pu8wtqtxxviqKHmo4e0ojnznjKFkBNxDpqhte7YktMOosNXCclnJCUZH7Nwu%2FX4vkKQib&X-Amz-Signature=c6c20f06e832de56b278d59df689cc1ec2b779ca00ba64ddc467bedd9a816af5&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TKQE3EJZ%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T142323Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGYaCXVzLXdlc3QtMiJHMEUCIAO4DH45qBpxR7SSJZn3%2Fb8LsoZxecoRmAnZYLrsmeSvAiEA7DpX0u57YnLzA%2FcEBDhUCVFsnECuxb%2FSZeoH%2B%2Bq68JcqiAQIj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKIsChpNglxrOBdb2yrcA6%2FvVjyC4XqGfrx0TNzlRSmn4dpyX9J0XuIuYde%2FnPU5M0yx%2FDSGUTWy14E0AD%2FCCyI%2BSkKKdFgXUuh1N9yn0lYuoXdbLaIwL1%2FBcl9yRGYgvsRqnybeSRBDOPBXuUGLCFrqfdwJ751fzOkYBK02Iqt4YXi%2BCl4NIrMTYzjDCMJRVHJVKCIGkfsOWpblNQlSbA0Gsng3wT19uUvgWO1Yw1c%2F9A7ayriFZZslZIr72fuy1LsKv7avwBQOTm%2Bs8rUhcDrovrYA5P9JOdNqzoJ%2FkA%2FeltwRKJZqyol2knci%2BrZvdCzHPjzPDrn5rkR5QmvaLQYMu6i%2F9LbXcWBj3mIcxAFIrA%2Fxin0tnyuVtCMMhN7zj8IujF8EVPWUOWnHrIHk2Aj8fU18dIi1DVk7siA%2FVpqGYPr6%2Ffk%2F259hlk8Owqg8RcVUgm4bkyYamMblinfb5N1s%2FdrSawtZmU42NU18jZJb4Ef0D%2BDtLHMgMtUgnUnVISys5Cw0MIC79XfI7sWN3CEgPrmU0Ku3Z4xoinOlB2a3whLHTEuClOI3EqDecCC1aq%2FEyy3fWQH6aUTZgtOnX%2FTD9p5wP0BN7xAtGUFwUponJNFttn9QIx7t4g0f5rRUduC2ShAFPUXW%2Fg0qMJqU0r0GOqUBKnEia4mByk%2BQ67drgKjPR9mYM0XdEeVjNfE%2B2B1DejqBLsFMjvQ6ujZcKo04ZRHsH9g3KuX0DeetDwc4O2lkvefHa%2FzeTFumTdrw%2Bzb1y5RhdloU%2F0wo2oX8ahWeo9l7ItESTbyMf2XE%2F%2FgweqctA59pu8wtqtxxviqKHmo4e0ojnznjKFkBNxDpqhte7YktMOosNXCclnJCUZH7Nwu%2FX4vkKQib&X-Amz-Signature=796944fba7236679ee53c9ced192df00c6adce2d0b4f98e0da28515e0be8cdc3&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TKQE3EJZ%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T142323Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGYaCXVzLXdlc3QtMiJHMEUCIAO4DH45qBpxR7SSJZn3%2Fb8LsoZxecoRmAnZYLrsmeSvAiEA7DpX0u57YnLzA%2FcEBDhUCVFsnECuxb%2FSZeoH%2B%2Bq68JcqiAQIj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKIsChpNglxrOBdb2yrcA6%2FvVjyC4XqGfrx0TNzlRSmn4dpyX9J0XuIuYde%2FnPU5M0yx%2FDSGUTWy14E0AD%2FCCyI%2BSkKKdFgXUuh1N9yn0lYuoXdbLaIwL1%2FBcl9yRGYgvsRqnybeSRBDOPBXuUGLCFrqfdwJ751fzOkYBK02Iqt4YXi%2BCl4NIrMTYzjDCMJRVHJVKCIGkfsOWpblNQlSbA0Gsng3wT19uUvgWO1Yw1c%2F9A7ayriFZZslZIr72fuy1LsKv7avwBQOTm%2Bs8rUhcDrovrYA5P9JOdNqzoJ%2FkA%2FeltwRKJZqyol2knci%2BrZvdCzHPjzPDrn5rkR5QmvaLQYMu6i%2F9LbXcWBj3mIcxAFIrA%2Fxin0tnyuVtCMMhN7zj8IujF8EVPWUOWnHrIHk2Aj8fU18dIi1DVk7siA%2FVpqGYPr6%2Ffk%2F259hlk8Owqg8RcVUgm4bkyYamMblinfb5N1s%2FdrSawtZmU42NU18jZJb4Ef0D%2BDtLHMgMtUgnUnVISys5Cw0MIC79XfI7sWN3CEgPrmU0Ku3Z4xoinOlB2a3whLHTEuClOI3EqDecCC1aq%2FEyy3fWQH6aUTZgtOnX%2FTD9p5wP0BN7xAtGUFwUponJNFttn9QIx7t4g0f5rRUduC2ShAFPUXW%2Fg0qMJqU0r0GOqUBKnEia4mByk%2BQ67drgKjPR9mYM0XdEeVjNfE%2B2B1DejqBLsFMjvQ6ujZcKo04ZRHsH9g3KuX0DeetDwc4O2lkvefHa%2FzeTFumTdrw%2Bzb1y5RhdloU%2F0wo2oX8ahWeo9l7ItESTbyMf2XE%2F%2FgweqctA59pu8wtqtxxviqKHmo4e0ojnznjKFkBNxDpqhte7YktMOosNXCclnJCUZH7Nwu%2FX4vkKQib&X-Amz-Signature=4f9504d2efd31a67cad90b61c99f8e07d65706868a2243c96719b3c37a6ff2d6&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TKQE3EJZ%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T142323Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGYaCXVzLXdlc3QtMiJHMEUCIAO4DH45qBpxR7SSJZn3%2Fb8LsoZxecoRmAnZYLrsmeSvAiEA7DpX0u57YnLzA%2FcEBDhUCVFsnECuxb%2FSZeoH%2B%2Bq68JcqiAQIj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKIsChpNglxrOBdb2yrcA6%2FvVjyC4XqGfrx0TNzlRSmn4dpyX9J0XuIuYde%2FnPU5M0yx%2FDSGUTWy14E0AD%2FCCyI%2BSkKKdFgXUuh1N9yn0lYuoXdbLaIwL1%2FBcl9yRGYgvsRqnybeSRBDOPBXuUGLCFrqfdwJ751fzOkYBK02Iqt4YXi%2BCl4NIrMTYzjDCMJRVHJVKCIGkfsOWpblNQlSbA0Gsng3wT19uUvgWO1Yw1c%2F9A7ayriFZZslZIr72fuy1LsKv7avwBQOTm%2Bs8rUhcDrovrYA5P9JOdNqzoJ%2FkA%2FeltwRKJZqyol2knci%2BrZvdCzHPjzPDrn5rkR5QmvaLQYMu6i%2F9LbXcWBj3mIcxAFIrA%2Fxin0tnyuVtCMMhN7zj8IujF8EVPWUOWnHrIHk2Aj8fU18dIi1DVk7siA%2FVpqGYPr6%2Ffk%2F259hlk8Owqg8RcVUgm4bkyYamMblinfb5N1s%2FdrSawtZmU42NU18jZJb4Ef0D%2BDtLHMgMtUgnUnVISys5Cw0MIC79XfI7sWN3CEgPrmU0Ku3Z4xoinOlB2a3whLHTEuClOI3EqDecCC1aq%2FEyy3fWQH6aUTZgtOnX%2FTD9p5wP0BN7xAtGUFwUponJNFttn9QIx7t4g0f5rRUduC2ShAFPUXW%2Fg0qMJqU0r0GOqUBKnEia4mByk%2BQ67drgKjPR9mYM0XdEeVjNfE%2B2B1DejqBLsFMjvQ6ujZcKo04ZRHsH9g3KuX0DeetDwc4O2lkvefHa%2FzeTFumTdrw%2Bzb1y5RhdloU%2F0wo2oX8ahWeo9l7ItESTbyMf2XE%2F%2FgweqctA59pu8wtqtxxviqKHmo4e0ojnznjKFkBNxDpqhte7YktMOosNXCclnJCUZH7Nwu%2FX4vkKQib&X-Amz-Signature=65fb3b4d07e11e14e8dc8fc66b9b932a3fbf8f8e8eaaee7a048160a9ce514c63&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TKQE3EJZ%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T142323Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGYaCXVzLXdlc3QtMiJHMEUCIAO4DH45qBpxR7SSJZn3%2Fb8LsoZxecoRmAnZYLrsmeSvAiEA7DpX0u57YnLzA%2FcEBDhUCVFsnECuxb%2FSZeoH%2B%2Bq68JcqiAQIj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKIsChpNglxrOBdb2yrcA6%2FvVjyC4XqGfrx0TNzlRSmn4dpyX9J0XuIuYde%2FnPU5M0yx%2FDSGUTWy14E0AD%2FCCyI%2BSkKKdFgXUuh1N9yn0lYuoXdbLaIwL1%2FBcl9yRGYgvsRqnybeSRBDOPBXuUGLCFrqfdwJ751fzOkYBK02Iqt4YXi%2BCl4NIrMTYzjDCMJRVHJVKCIGkfsOWpblNQlSbA0Gsng3wT19uUvgWO1Yw1c%2F9A7ayriFZZslZIr72fuy1LsKv7avwBQOTm%2Bs8rUhcDrovrYA5P9JOdNqzoJ%2FkA%2FeltwRKJZqyol2knci%2BrZvdCzHPjzPDrn5rkR5QmvaLQYMu6i%2F9LbXcWBj3mIcxAFIrA%2Fxin0tnyuVtCMMhN7zj8IujF8EVPWUOWnHrIHk2Aj8fU18dIi1DVk7siA%2FVpqGYPr6%2Ffk%2F259hlk8Owqg8RcVUgm4bkyYamMblinfb5N1s%2FdrSawtZmU42NU18jZJb4Ef0D%2BDtLHMgMtUgnUnVISys5Cw0MIC79XfI7sWN3CEgPrmU0Ku3Z4xoinOlB2a3whLHTEuClOI3EqDecCC1aq%2FEyy3fWQH6aUTZgtOnX%2FTD9p5wP0BN7xAtGUFwUponJNFttn9QIx7t4g0f5rRUduC2ShAFPUXW%2Fg0qMJqU0r0GOqUBKnEia4mByk%2BQ67drgKjPR9mYM0XdEeVjNfE%2B2B1DejqBLsFMjvQ6ujZcKo04ZRHsH9g3KuX0DeetDwc4O2lkvefHa%2FzeTFumTdrw%2Bzb1y5RhdloU%2F0wo2oX8ahWeo9l7ItESTbyMf2XE%2F%2FgweqctA59pu8wtqtxxviqKHmo4e0ojnznjKFkBNxDpqhte7YktMOosNXCclnJCUZH7Nwu%2FX4vkKQib&X-Amz-Signature=9d4017922264c4b76fe5c466f74f2e7add8dbbd72f05b75778a1b652e2e9ff06&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667JCPNHCG%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T142323Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGYaCXVzLXdlc3QtMiJIMEYCIQDff8bPteKlNePbxBgf2atJ9YCCQ3KDPB48Kndy5oSTNAIhAKMAYqdSK273Tr%2Blp3cPd2RKWqeZfYSk4Zo0G3pkISe6KogECI7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzsGm92Eh3Hc8PGzYMq3ANoJz%2FFi4sGIF4gOsd%2FtaJ%2FXdSJhTgazo8XkKiQiDtZSl1UuWlvRYidQI4Jbp4N0UGFWGDDmxP5m%2F1h6zw7kVk6tT1eagXGW2aGBsrzalbe%2FLv%2Bhb06Hv7xzGOHmFfdOWP1uOw2AYdqmEm%2BOuGVboMRUC6qNp7H9y6EOlAHGKtU7ZY3jNpKEc0H2JgwemyScrdqZqe7flc30TNnOrbA8%2B2CYp0ruRJZFrDirhOph4f2PUJSCMmmuhx3vnzqwFovoXsbW%2Bq1gEqu927D%2B%2BPMcs6%2BKglONslSTlgYCyHXgkub4WItONpgjlYP4%2Fc3FtzmTQU5vapE2Bgsng8FI%2Bpx75%2BuYNEzYyjyJ3dhzHeja8Yb%2BnsnW%2BQItyfeZFJpXkuZ0rjJvOzgYpTZ262A9udh00D4kyB5MibEsZSHFLG7DMnOjrrBpJRi3Tt83NHrtkiT2d5hd2USDZxeHnWr6IfIhYGiv71xNAIAUV5UAH%2FWMjC9FkppTARQpUp3g52ydLrW9Zt9w%2B6znYVkZZU6oKZTkApd%2B8uonOO8e6pwNEZj8Or40k6OTuOMt6zcK5Dp0Zq0e8p3gtmtBuSh7VMxDsaeRzd6lo29d8TgQp6QuolOZp1gxX27UxVqhVA5Vv7PfTCilNK9BjqkAceMMroXP%2FHh8RL8jJsKCKMeOTyO5%2FitpWRD2PfexJCMLEJdF9fYvfD%2FeQKdD%2F8ItCRi37GgPxeHfo5nZfZj4%2BqHYH5ghwhLJ1liLsR66xE7RrWP4ujNdBimeNvhueAaYXikPrhz9myBhZYV9Q5soiQJ4A2%2FH8%2B%2FsGtkcKneXcXJjz%2FuEodvaS7U6VfR0vtQwR75ByAxv2RG4w%2B7WhgEBSFxa2Tw&X-Amz-Signature=b32fb660fdc9f9d8e968d1213828b2edff748e6aa9d49eca9f30489b93ba8358&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664IRCIEHE%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T142324Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGYaCXVzLXdlc3QtMiJGMEQCIHt6%2BNKTzyc4AyaCKpqyq3gG6FVM7iXV4vFvdzJQNO3mAiBLauQq6iYn%2FkSCltpkO3Fc92K7b4UnGpxga%2BjVLv0ulSqIBAiP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMHppds1QT%2BI7aWpQwKtwDPUcRczqKXjQwQGWOysLgu2IFE6%2BYV%2BiUx%2Fblt1hnrSEahbC5f5fnEpiPfIEOlR8JfFBwJ%2B2v%2FV7X3N9W4%2BTgxMLOCDN91rtTkAqXExwJlADQUNJesJhWWiBUlPklzT4mU47e45MgMiN4JSXZPMtXuJxO6XmnzUjR6dqmmsy2%2BniXxCSKyLUDWR3V9Tvv7bTNpOCZFUXqsHCfLxopbLvlS3RQe4gVkZol4Xf%2FJ9GbYwWH91bXXZirCl3WpOhKw6w%2FVA13yx1mjbogPauxwwPdZv26n5mc2yP4PSfgYcARehlwWKP%2B8%2FB43s93BECSiH%2BPmFOHPjP7YtsAFGskYsl4RdYRXzR4j0FXLWv3MOUpVu9Z4wLuS%2BqgWJ30XnF9z5tkwGZlr2jMqGniR29HcfhIGNdsDi29NVdWW5TXOvq144L8VvNWNfFUXVohWXBo9R%2Bg9tPQVe3iv7M4l8vYAw%2FZJvPn1xjKJxlB3%2Fr%2BSdRqlBDv0VDvOBiFb3TGS3qbFfOySVe7NgI3j8Bak4Pj1v8eUAPeH03yZdxlvkVnjTNImUc2gCpBSGucJJqEy3uuf5JinLJaiVTi64RzXV%2FsejkRg6epO9GBHSY7Yhhm4gnJI4LZUfSbi3ORw3snUSwwtpTSvQY6pgEmYNg2hDEx02WeMyWk5PnSC94UcXHmHucfjxNyrGJSKy%2FyB1Lx3k%2FL9zTFTf%2FX5GyyEC9UsqQ%2BitF9mlX2ZZ4SYk6Mo9dfWN6VJ8yWyFTRlckBlyDQIcI50iyhgCRfm2s0Iu6URi%2FRWJsYCo9cyZCVWDevzJcK88ypz4iCMFBENkzuF6YWMaOJ31QY8HwfWpWs43Wtm7Ae%2F3c3HcXco%2FMPWV2igHnT&X-Amz-Signature=f3016541056eb4a42b1191870abcb9afa5a24d5a4c31ce1df2a6b847d555a14e&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TKQE3EJZ%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T142323Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGYaCXVzLXdlc3QtMiJHMEUCIAO4DH45qBpxR7SSJZn3%2Fb8LsoZxecoRmAnZYLrsmeSvAiEA7DpX0u57YnLzA%2FcEBDhUCVFsnECuxb%2FSZeoH%2B%2Bq68JcqiAQIj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKIsChpNglxrOBdb2yrcA6%2FvVjyC4XqGfrx0TNzlRSmn4dpyX9J0XuIuYde%2FnPU5M0yx%2FDSGUTWy14E0AD%2FCCyI%2BSkKKdFgXUuh1N9yn0lYuoXdbLaIwL1%2FBcl9yRGYgvsRqnybeSRBDOPBXuUGLCFrqfdwJ751fzOkYBK02Iqt4YXi%2BCl4NIrMTYzjDCMJRVHJVKCIGkfsOWpblNQlSbA0Gsng3wT19uUvgWO1Yw1c%2F9A7ayriFZZslZIr72fuy1LsKv7avwBQOTm%2Bs8rUhcDrovrYA5P9JOdNqzoJ%2FkA%2FeltwRKJZqyol2knci%2BrZvdCzHPjzPDrn5rkR5QmvaLQYMu6i%2F9LbXcWBj3mIcxAFIrA%2Fxin0tnyuVtCMMhN7zj8IujF8EVPWUOWnHrIHk2Aj8fU18dIi1DVk7siA%2FVpqGYPr6%2Ffk%2F259hlk8Owqg8RcVUgm4bkyYamMblinfb5N1s%2FdrSawtZmU42NU18jZJb4Ef0D%2BDtLHMgMtUgnUnVISys5Cw0MIC79XfI7sWN3CEgPrmU0Ku3Z4xoinOlB2a3whLHTEuClOI3EqDecCC1aq%2FEyy3fWQH6aUTZgtOnX%2FTD9p5wP0BN7xAtGUFwUponJNFttn9QIx7t4g0f5rRUduC2ShAFPUXW%2Fg0qMJqU0r0GOqUBKnEia4mByk%2BQ67drgKjPR9mYM0XdEeVjNfE%2B2B1DejqBLsFMjvQ6ujZcKo04ZRHsH9g3KuX0DeetDwc4O2lkvefHa%2FzeTFumTdrw%2Bzb1y5RhdloU%2F0wo2oX8ahWeo9l7ItESTbyMf2XE%2F%2FgweqctA59pu8wtqtxxviqKHmo4e0ojnznjKFkBNxDpqhte7YktMOosNXCclnJCUZH7Nwu%2FX4vkKQib&X-Amz-Signature=b94c4c6f13a8cdd48ef7bd6e0c72e2f20794d5ed6173c2f4e01afd71d6258f89&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TKQE3EJZ%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T142323Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGYaCXVzLXdlc3QtMiJHMEUCIAO4DH45qBpxR7SSJZn3%2Fb8LsoZxecoRmAnZYLrsmeSvAiEA7DpX0u57YnLzA%2FcEBDhUCVFsnECuxb%2FSZeoH%2B%2Bq68JcqiAQIj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKIsChpNglxrOBdb2yrcA6%2FvVjyC4XqGfrx0TNzlRSmn4dpyX9J0XuIuYde%2FnPU5M0yx%2FDSGUTWy14E0AD%2FCCyI%2BSkKKdFgXUuh1N9yn0lYuoXdbLaIwL1%2FBcl9yRGYgvsRqnybeSRBDOPBXuUGLCFrqfdwJ751fzOkYBK02Iqt4YXi%2BCl4NIrMTYzjDCMJRVHJVKCIGkfsOWpblNQlSbA0Gsng3wT19uUvgWO1Yw1c%2F9A7ayriFZZslZIr72fuy1LsKv7avwBQOTm%2Bs8rUhcDrovrYA5P9JOdNqzoJ%2FkA%2FeltwRKJZqyol2knci%2BrZvdCzHPjzPDrn5rkR5QmvaLQYMu6i%2F9LbXcWBj3mIcxAFIrA%2Fxin0tnyuVtCMMhN7zj8IujF8EVPWUOWnHrIHk2Aj8fU18dIi1DVk7siA%2FVpqGYPr6%2Ffk%2F259hlk8Owqg8RcVUgm4bkyYamMblinfb5N1s%2FdrSawtZmU42NU18jZJb4Ef0D%2BDtLHMgMtUgnUnVISys5Cw0MIC79XfI7sWN3CEgPrmU0Ku3Z4xoinOlB2a3whLHTEuClOI3EqDecCC1aq%2FEyy3fWQH6aUTZgtOnX%2FTD9p5wP0BN7xAtGUFwUponJNFttn9QIx7t4g0f5rRUduC2ShAFPUXW%2Fg0qMJqU0r0GOqUBKnEia4mByk%2BQ67drgKjPR9mYM0XdEeVjNfE%2B2B1DejqBLsFMjvQ6ujZcKo04ZRHsH9g3KuX0DeetDwc4O2lkvefHa%2FzeTFumTdrw%2Bzb1y5RhdloU%2F0wo2oX8ahWeo9l7ItESTbyMf2XE%2F%2FgweqctA59pu8wtqtxxviqKHmo4e0ojnznjKFkBNxDpqhte7YktMOosNXCclnJCUZH7Nwu%2FX4vkKQib&X-Amz-Signature=2afad1e09a8e5d7a02a03aa9823600a9aa9af3e648a4e0aa8d1591c2df156008&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TKQE3EJZ%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T142323Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGYaCXVzLXdlc3QtMiJHMEUCIAO4DH45qBpxR7SSJZn3%2Fb8LsoZxecoRmAnZYLrsmeSvAiEA7DpX0u57YnLzA%2FcEBDhUCVFsnECuxb%2FSZeoH%2B%2Bq68JcqiAQIj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKIsChpNglxrOBdb2yrcA6%2FvVjyC4XqGfrx0TNzlRSmn4dpyX9J0XuIuYde%2FnPU5M0yx%2FDSGUTWy14E0AD%2FCCyI%2BSkKKdFgXUuh1N9yn0lYuoXdbLaIwL1%2FBcl9yRGYgvsRqnybeSRBDOPBXuUGLCFrqfdwJ751fzOkYBK02Iqt4YXi%2BCl4NIrMTYzjDCMJRVHJVKCIGkfsOWpblNQlSbA0Gsng3wT19uUvgWO1Yw1c%2F9A7ayriFZZslZIr72fuy1LsKv7avwBQOTm%2Bs8rUhcDrovrYA5P9JOdNqzoJ%2FkA%2FeltwRKJZqyol2knci%2BrZvdCzHPjzPDrn5rkR5QmvaLQYMu6i%2F9LbXcWBj3mIcxAFIrA%2Fxin0tnyuVtCMMhN7zj8IujF8EVPWUOWnHrIHk2Aj8fU18dIi1DVk7siA%2FVpqGYPr6%2Ffk%2F259hlk8Owqg8RcVUgm4bkyYamMblinfb5N1s%2FdrSawtZmU42NU18jZJb4Ef0D%2BDtLHMgMtUgnUnVISys5Cw0MIC79XfI7sWN3CEgPrmU0Ku3Z4xoinOlB2a3whLHTEuClOI3EqDecCC1aq%2FEyy3fWQH6aUTZgtOnX%2FTD9p5wP0BN7xAtGUFwUponJNFttn9QIx7t4g0f5rRUduC2ShAFPUXW%2Fg0qMJqU0r0GOqUBKnEia4mByk%2BQ67drgKjPR9mYM0XdEeVjNfE%2B2B1DejqBLsFMjvQ6ujZcKo04ZRHsH9g3KuX0DeetDwc4O2lkvefHa%2FzeTFumTdrw%2Bzb1y5RhdloU%2F0wo2oX8ahWeo9l7ItESTbyMf2XE%2F%2FgweqctA59pu8wtqtxxviqKHmo4e0ojnznjKFkBNxDpqhte7YktMOosNXCclnJCUZH7Nwu%2FX4vkKQib&X-Amz-Signature=dd8c19c0f0bcc6d05ce64c0976a1f1fed8f25cfb83ca7c002ead82af1b547844&X-Amz-SignedHeaders=host&x-id=GetObject)


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

