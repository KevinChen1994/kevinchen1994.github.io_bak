---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466Y4F4OLCA%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250221T043037Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEKT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIGepINsU6Bwz0XYWbEV\
  thdp7dRaMABPtfP58fDpP6azaAiEAimo6mRvI%2BOi9NxqhxEeTzgCK3JSooEw6pmIEB3tBi%2BIq\
  iAQIzf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHN39nFXvOzBS3Wva\
  CrcA6HAuqKs%2Bu2ais1%2BEVbCmALE3%2FZM6EBVxwfOdWZhA2Ud2G23aDI0OCuEhLHxo97uzzVj\
  %2FQzye2KGGRtoH35%2F9nnQM1RRAF6fpOaZRhicfOlujesoZw2r1JmqbhTEvCVVIv5hGsFHZCp8g\
  im2v2NURAS6vwQIw4NJFhGR3kLf%2BmBWZ5pRl1MXl78rjYHZL4nIG%2BKfpI6LSOLflJ9YEFY7lw\
  W0TfC0AIEl%2Fa5USFb1Ye4kg8rGGEawCnkJNt0Iv%2F4kGTXNmsRmjqIPda2bpHWXLMuKHlt7IDb\
  sAoc%2Fjmqi9mdbrbFUDnd0Ml9T6xZP5rLxDUWpw9cwg2mO6F7dSkwpSs4mAoX8zvx67PxA63zkie\
  VTN0yinHMjoU%2FnlXyCWw94%2BBWjcwkSrTtQ2h58XwbqqAaiClwHEfWRNVuAeCoJjaQ2S9CPiLi\
  TAuM0Lpj7Fvv%2Fvr53wRREmpmRy%2BEuux0OKGmrV66d4mKFFLlZkNxtjKT8Wd8BygKUmJVQDcvD\
  ixAUM0XXTZQiQ2tl3xn7Hr7iOWKJcDuAkkKipXYqgA7RB3USrpqGUjvgZ77H2eCiKGEt1wL0yKXae\
  YbVYvlt5bLOMamDkrZ%2BpkkonBBmYl7SuaLUIOqS61vGajyjFlO6MPDn370GOqUBYhp4xVEhA9fq\
  bob0KXIhoq14TLofNm6smzk%2F0JGilVvpfi64wSNGd5DQkCvW7NB4gJOSVkVkZohKNu%2B7kj8gC\
  DF5%2FJCJfIjKg7woBOPyRlzQT%2FK773xAoOyeT%2BEjY9l9Uaqg19ufng0V6JT3wvSrbroZErn2\
  mphiLAY5QgwqPBsfo3lS%2FZH9LDYYeHbjz%2FOM9rDskFF5swrP2NRYfgulu75Ib7gs&X-Amz-Si\
  gnature=e83e0ae3ddd7d47e91a868ca64fce497e2cf21faf8f0a16fb8ce3d31155444b3&X-Am\
  z-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466ZHBASJDM%2F20250221%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250221T042858Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEKT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIQDmAt7c7Bmn4A2dlHqizOjpI3LUEt2MRqfXUsODhv%2FP7wIgO%2FxEoUaUNrQjqm0PsY\
        I%2FNgaRUPvV4abqSwKF4NjW8XYqiAQIzf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw\
        2Mzc0MjMxODM4MDUiDAy693YwIANTgxBEQyrcA9LhqhOnaFqfhfxptwcQ3GGpcEARmmk58M\
        PkUNwZEbnEQ32NIThenKlAklhTYBLDF4EbOVnNKm1X%2FF3GF6J8Had1FwTsxiXW2h3scyo\
        sGd2x2UtwghdkbLH4GD3xk0rA9NxFk4txgEOnG0kmvs1FM4Zdw82pEC1hSuLvg4pOniP8Kc\
        G0O%2BJpFIuF1XfOTOIGfGaD7nRJp9sWOJTurEIizVrA%2B6XMAmcqnMHxSmmPV5mP7YVOv\
        Tm2lcbrGEoIjqkrM4MSxObTqNt2Fd1Wd%2BY8K0SfRg5Wj6ii6%2B3%2BEf0PabckeA7nnP\
        ct1%2BiwNovBV80kVxmG91XZmL7KN5sQx1TKdd1SwwxJrQg%2BR8sCPqfP8zlGMomehU9G%\
        2BCW6th8Xs%2BskS8IPNahteiCa%2Bbf19g09fVyKNRbGIAQqilRaz8%2F06KVGZBGYswOD\
        Sf5LSFCDp0FioxVvQA%2FH%2FOfvgUmYfr2JJj0czipLXoYLQuwcKUXwXLgiV%2FnpCqsEr\
        tiuxbvYxmtrP9uocju2%2FI29A8wSkNmer5CW3fCHa5FwdAnOqmcurvV17mY4zmHyLWNtq9\
        Y8SSLaqFlPs6nO8e0kbav2e4hWBIXSYdC0u5O6qxh92R2%2Fsy%2BeE4HQXoCV5hlexwgFM\
        Orn370GOqUBhglM1%2FxnQH5ud%2B00Chm02VCp3%2FWFnZTujunpXx%2F4ipVktwMT%2Fd\
        syTPDYbEUAXv66ZqS78THJ%2BWhDUSXfEuVIebNzED%2BRSJfGY1KcbBDtcC37BNFbsIx6E\
        NGBloix%2BT14%2BzyAMwFfE%2BoajaFdcUFcN7y9YrJ2%2FV33b8qJfBTfGrVJoIu6v6DN\
        dCySCOiBG3ERzTUulBjQ5GoynIImMsNa3jHsPZBf&X-Amz-Signature=d9c7a86f08d702\
        b8a09f377c2b66aef9a384c425e1d51192d679002a86259715&X-Amz-SignedHeaders=\
        host&x-id=GetObject"
      expiry_time: "2025-02-21T05:28:58.142Z"
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
UPDATE_TIME: "2025-02-21T04:30:44.505Z"
EXPIRY_TIME: "2025-02-21T05:30:33.107Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46645HNYRHC%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T043033Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIC2U6lyUxAHgpsphisELz73fixkPZF0vkke2KLxoaZzRAiEAhEnxWUu8NW5YnKBBjpfNbXwllMACHMJi1nLBdcxsuLsqiAQIzf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLGNJDCPmvLGcmO0LircA%2FjyaAR9UNklLUNh0XiOZPy7BOdaWLpSLDPq1BdZmL6ZGy4RVgx4zn9toarogzxqF5m9QjvuJteMUEu1Ql%2FbfqvwWHPAufobOh32phalxL1CWO0RT5QIe8UAspDkAkX%2BT3Gk7zBfr%2BB3PJ%2FEB%2BpjOjjTxv%2FjJeBf%2BeTPEjq2Dfg7TJy9T9klKzFvLDtjslTkTXH3vBAn9ZhgmJJeI9vUe7FFZi2IGcirOFZBEUtO6kqyMq2Le4PNgLCaXhZpvS%2F5DNzK%2BNQQsTeMKRNLjSOJOEHkdDsiPA1pZIHGB1pwyYaW%2BharYoQFbUTD%2Fx7cJUBz2iza19oU%2F1j9Und6X6ziNYW1HCZ%2Fdbl1LmkfnnQ7LrbqX1B6wk4EwKCSNv6t5w2lcC3W63yK9EWZc7oo9HbxtNoVD4ANM82ALqQpGLk81gToFARAwVGnW08xWHur10P1lW8AlJyuBI3dC2JKij%2Fn1qaXcLli6zPb6OKOgfpNgWjtEKeTSWfjLEf2D%2Bbb5lmJW%2BXlDLHbzJuohi5uIURGXpzasBrHYfbPRHlvd%2FzdjaDpvNB8jCU8n9h3liItJhiHZP1uexOAV8ORMx1DHMA2LeYx6O1VhNaZuo5Hvx7%2F8FRQMh%2F0NNYco5wBJo0TMMno370GOqUBMwnSPerOGt%2FIR4N2lAcLA1PuSiscrJO5VHYfEXHbaaIBbBvQbEG0zmsVqzipo8tPNoC4y2b0UmJOukRIKne1XFo4dlfbsE8u%2BJyFLdsP15HaEXNvxUpAD7ONtb6We%2FzQcGuFdZHSrRNZm%2FdxmEGfq31cQwc3F3DN784DGRKTpH5emo2DRFa1lDbNqKST34lwLUEd2K6lBeDlb5yb0AhwYgb9Vzv6&X-Amz-Signature=862aada98d545d0a5561f12e9e785a3d219b2626b01496aaf9a71447e5ae9fab&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46645HNYRHC%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T043033Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIC2U6lyUxAHgpsphisELz73fixkPZF0vkke2KLxoaZzRAiEAhEnxWUu8NW5YnKBBjpfNbXwllMACHMJi1nLBdcxsuLsqiAQIzf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLGNJDCPmvLGcmO0LircA%2FjyaAR9UNklLUNh0XiOZPy7BOdaWLpSLDPq1BdZmL6ZGy4RVgx4zn9toarogzxqF5m9QjvuJteMUEu1Ql%2FbfqvwWHPAufobOh32phalxL1CWO0RT5QIe8UAspDkAkX%2BT3Gk7zBfr%2BB3PJ%2FEB%2BpjOjjTxv%2FjJeBf%2BeTPEjq2Dfg7TJy9T9klKzFvLDtjslTkTXH3vBAn9ZhgmJJeI9vUe7FFZi2IGcirOFZBEUtO6kqyMq2Le4PNgLCaXhZpvS%2F5DNzK%2BNQQsTeMKRNLjSOJOEHkdDsiPA1pZIHGB1pwyYaW%2BharYoQFbUTD%2Fx7cJUBz2iza19oU%2F1j9Und6X6ziNYW1HCZ%2Fdbl1LmkfnnQ7LrbqX1B6wk4EwKCSNv6t5w2lcC3W63yK9EWZc7oo9HbxtNoVD4ANM82ALqQpGLk81gToFARAwVGnW08xWHur10P1lW8AlJyuBI3dC2JKij%2Fn1qaXcLli6zPb6OKOgfpNgWjtEKeTSWfjLEf2D%2Bbb5lmJW%2BXlDLHbzJuohi5uIURGXpzasBrHYfbPRHlvd%2FzdjaDpvNB8jCU8n9h3liItJhiHZP1uexOAV8ORMx1DHMA2LeYx6O1VhNaZuo5Hvx7%2F8FRQMh%2F0NNYco5wBJo0TMMno370GOqUBMwnSPerOGt%2FIR4N2lAcLA1PuSiscrJO5VHYfEXHbaaIBbBvQbEG0zmsVqzipo8tPNoC4y2b0UmJOukRIKne1XFo4dlfbsE8u%2BJyFLdsP15HaEXNvxUpAD7ONtb6We%2FzQcGuFdZHSrRNZm%2FdxmEGfq31cQwc3F3DN784DGRKTpH5emo2DRFa1lDbNqKST34lwLUEd2K6lBeDlb5yb0AhwYgb9Vzv6&X-Amz-Signature=78194fe5ffdca0e6949dee286ca170620513fb7615bf02630dddcf8f070d9a27&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46645HNYRHC%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T043033Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIC2U6lyUxAHgpsphisELz73fixkPZF0vkke2KLxoaZzRAiEAhEnxWUu8NW5YnKBBjpfNbXwllMACHMJi1nLBdcxsuLsqiAQIzf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLGNJDCPmvLGcmO0LircA%2FjyaAR9UNklLUNh0XiOZPy7BOdaWLpSLDPq1BdZmL6ZGy4RVgx4zn9toarogzxqF5m9QjvuJteMUEu1Ql%2FbfqvwWHPAufobOh32phalxL1CWO0RT5QIe8UAspDkAkX%2BT3Gk7zBfr%2BB3PJ%2FEB%2BpjOjjTxv%2FjJeBf%2BeTPEjq2Dfg7TJy9T9klKzFvLDtjslTkTXH3vBAn9ZhgmJJeI9vUe7FFZi2IGcirOFZBEUtO6kqyMq2Le4PNgLCaXhZpvS%2F5DNzK%2BNQQsTeMKRNLjSOJOEHkdDsiPA1pZIHGB1pwyYaW%2BharYoQFbUTD%2Fx7cJUBz2iza19oU%2F1j9Und6X6ziNYW1HCZ%2Fdbl1LmkfnnQ7LrbqX1B6wk4EwKCSNv6t5w2lcC3W63yK9EWZc7oo9HbxtNoVD4ANM82ALqQpGLk81gToFARAwVGnW08xWHur10P1lW8AlJyuBI3dC2JKij%2Fn1qaXcLli6zPb6OKOgfpNgWjtEKeTSWfjLEf2D%2Bbb5lmJW%2BXlDLHbzJuohi5uIURGXpzasBrHYfbPRHlvd%2FzdjaDpvNB8jCU8n9h3liItJhiHZP1uexOAV8ORMx1DHMA2LeYx6O1VhNaZuo5Hvx7%2F8FRQMh%2F0NNYco5wBJo0TMMno370GOqUBMwnSPerOGt%2FIR4N2lAcLA1PuSiscrJO5VHYfEXHbaaIBbBvQbEG0zmsVqzipo8tPNoC4y2b0UmJOukRIKne1XFo4dlfbsE8u%2BJyFLdsP15HaEXNvxUpAD7ONtb6We%2FzQcGuFdZHSrRNZm%2FdxmEGfq31cQwc3F3DN784DGRKTpH5emo2DRFa1lDbNqKST34lwLUEd2K6lBeDlb5yb0AhwYgb9Vzv6&X-Amz-Signature=ef70241782a397064d27c548eb4fbe3c08581f4c36f2862f82ad1c790ed813a0&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46645HNYRHC%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T043033Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIC2U6lyUxAHgpsphisELz73fixkPZF0vkke2KLxoaZzRAiEAhEnxWUu8NW5YnKBBjpfNbXwllMACHMJi1nLBdcxsuLsqiAQIzf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLGNJDCPmvLGcmO0LircA%2FjyaAR9UNklLUNh0XiOZPy7BOdaWLpSLDPq1BdZmL6ZGy4RVgx4zn9toarogzxqF5m9QjvuJteMUEu1Ql%2FbfqvwWHPAufobOh32phalxL1CWO0RT5QIe8UAspDkAkX%2BT3Gk7zBfr%2BB3PJ%2FEB%2BpjOjjTxv%2FjJeBf%2BeTPEjq2Dfg7TJy9T9klKzFvLDtjslTkTXH3vBAn9ZhgmJJeI9vUe7FFZi2IGcirOFZBEUtO6kqyMq2Le4PNgLCaXhZpvS%2F5DNzK%2BNQQsTeMKRNLjSOJOEHkdDsiPA1pZIHGB1pwyYaW%2BharYoQFbUTD%2Fx7cJUBz2iza19oU%2F1j9Und6X6ziNYW1HCZ%2Fdbl1LmkfnnQ7LrbqX1B6wk4EwKCSNv6t5w2lcC3W63yK9EWZc7oo9HbxtNoVD4ANM82ALqQpGLk81gToFARAwVGnW08xWHur10P1lW8AlJyuBI3dC2JKij%2Fn1qaXcLli6zPb6OKOgfpNgWjtEKeTSWfjLEf2D%2Bbb5lmJW%2BXlDLHbzJuohi5uIURGXpzasBrHYfbPRHlvd%2FzdjaDpvNB8jCU8n9h3liItJhiHZP1uexOAV8ORMx1DHMA2LeYx6O1VhNaZuo5Hvx7%2F8FRQMh%2F0NNYco5wBJo0TMMno370GOqUBMwnSPerOGt%2FIR4N2lAcLA1PuSiscrJO5VHYfEXHbaaIBbBvQbEG0zmsVqzipo8tPNoC4y2b0UmJOukRIKne1XFo4dlfbsE8u%2BJyFLdsP15HaEXNvxUpAD7ONtb6We%2FzQcGuFdZHSrRNZm%2FdxmEGfq31cQwc3F3DN784DGRKTpH5emo2DRFa1lDbNqKST34lwLUEd2K6lBeDlb5yb0AhwYgb9Vzv6&X-Amz-Signature=f12f2fc4acade861efbff4c9992182e7990b6f03118515cf8bdfb3eb1d0e7fc5&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46645HNYRHC%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T043033Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIC2U6lyUxAHgpsphisELz73fixkPZF0vkke2KLxoaZzRAiEAhEnxWUu8NW5YnKBBjpfNbXwllMACHMJi1nLBdcxsuLsqiAQIzf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLGNJDCPmvLGcmO0LircA%2FjyaAR9UNklLUNh0XiOZPy7BOdaWLpSLDPq1BdZmL6ZGy4RVgx4zn9toarogzxqF5m9QjvuJteMUEu1Ql%2FbfqvwWHPAufobOh32phalxL1CWO0RT5QIe8UAspDkAkX%2BT3Gk7zBfr%2BB3PJ%2FEB%2BpjOjjTxv%2FjJeBf%2BeTPEjq2Dfg7TJy9T9klKzFvLDtjslTkTXH3vBAn9ZhgmJJeI9vUe7FFZi2IGcirOFZBEUtO6kqyMq2Le4PNgLCaXhZpvS%2F5DNzK%2BNQQsTeMKRNLjSOJOEHkdDsiPA1pZIHGB1pwyYaW%2BharYoQFbUTD%2Fx7cJUBz2iza19oU%2F1j9Und6X6ziNYW1HCZ%2Fdbl1LmkfnnQ7LrbqX1B6wk4EwKCSNv6t5w2lcC3W63yK9EWZc7oo9HbxtNoVD4ANM82ALqQpGLk81gToFARAwVGnW08xWHur10P1lW8AlJyuBI3dC2JKij%2Fn1qaXcLli6zPb6OKOgfpNgWjtEKeTSWfjLEf2D%2Bbb5lmJW%2BXlDLHbzJuohi5uIURGXpzasBrHYfbPRHlvd%2FzdjaDpvNB8jCU8n9h3liItJhiHZP1uexOAV8ORMx1DHMA2LeYx6O1VhNaZuo5Hvx7%2F8FRQMh%2F0NNYco5wBJo0TMMno370GOqUBMwnSPerOGt%2FIR4N2lAcLA1PuSiscrJO5VHYfEXHbaaIBbBvQbEG0zmsVqzipo8tPNoC4y2b0UmJOukRIKne1XFo4dlfbsE8u%2BJyFLdsP15HaEXNvxUpAD7ONtb6We%2FzQcGuFdZHSrRNZm%2FdxmEGfq31cQwc3F3DN784DGRKTpH5emo2DRFa1lDbNqKST34lwLUEd2K6lBeDlb5yb0AhwYgb9Vzv6&X-Amz-Signature=429af5b85bf77ee1c30441c1ad5dc806eb37b1d4642f620dba1a167a13e7c0ef&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SNPS6UFT%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T043034Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDXrvLiVsGH0fHTT2mbWkVtiRYwxalak%2FgiK04%2BtvhX7AIhAPGaVjNHs9vuTIAirf6rpZgJJt0sVZoQrIqx%2B7qrhWixKogECM3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igya7vokxBuAOyQAzXYq3AOk3rC8M7nrwpSTDluXEt0cV2Hw05FIwTw6ciE0OqxnWzwiRvlKKAX8EN9%2BIRBSpCk5q%2FxCcA5%2BE8w5jh7D9wHFHciMqZowtOoNwdlDxkLTi3q5r0wqVc8gVWLOnCtvxUvp0KkajEAlfnW591qAbrsYa7%2B6BFV9iOmTQNLWvPUsleulpe24PkqwKD5BPLGKgFP0LD%2FYCT7WCEEB3TQDmmp2gD2GKNRLORND0w3uXuW%2FnX4QUvz1IC4T9vICmvHQfrSyv8PO90163w3z1amRWb8DxIfYaI4o4eQ9lXoY2V%2BLql74VfmD7jX%2B1c7YmlqnaEGW0X7XZ9RpnTlqgpws7dyrso%2BQr3ADJbuKnE1rl8riLHPdOtsGlvheIq5F8%2FzeoK7Oifnp0Ef94Xb1LjexO69y1yVka6%2FoFdHHXlMAKj7xsYNuhuLWlSHzYJ5oyafox8kfDTrVnZ%2BdnPpVcG6xsptoahHeHlacjMw7t7mtI6mqTtpfZ15HlceL6kfOb1ZjfMNTzeIawNVFXO3Kcv6EHAEQjECs6uNzd7es0KsqzMwRTRQPkA7gn4QhmcNaSNOm47eszs7bFbF1MsXHpxWNc4TjV9JtLvSp3eNEtbsfZ77ZMGwraCHP7ewGsebNiTDe59%2B9BjqkAaUGKRYtA%2BJD%2FQ7txpSbxPc01UPnw%2BGitWsPn%2FWktsNPKS09QaJeScpRqgatcDSyTlCzyyKdYzfai7I83FzhUiJIbduHl%2F05tU7ah0esV7oUo00l34KFqntSuq38WnNz0kAfeZFnH9CiNHrQoGEyYq9WkKHcO%2BG5uW%2B51AJ6lhncrT1MwHRVF3PlTxo3ko1QPx7J9%2FeOR6%2FNK8zxhc97kZtkrZgC&X-Amz-Signature=f500f047d669dc062bc0206b7242db885ee0d8df3803068483ad8f5ef6134c1f&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QAZBS6RK%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T043036Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIHJq69B9HbXIjs2CSKGXPv5dmqvNvxmHNz5vo8VfpPEvAiEAtJRG7LeyUp%2F9texcVVIXNlCpuen7L0r7d4jzLCDRN7UqiAQIzf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDABzskbgBEBVCGn5iSrcAywDIo2Oo0cNrrKNHtR1fGJaM36lhsJ7uFNsl4jPlNrtWJlm884sWq0V5Y6s4VL9%2FROeZZgZGAxSRh%2FxqRxT%2FSmqRQt0b6hwPujquOqf31O1XTRHbqeSW3g0aEpPIHtQfpI00mW3cpGCd8k6OKBAIj8OunyhIGA65gBv9lgT7A2MzOLYgN1QGEriEZvO7f0NO3d5idKPX44e%2Fxf5%2FX1zRDrvJeolcv5DZvqNcGQ4QOPL07p0Q4wGjMXR58o3yWBNG9LJ6c8jjImTV7Oy6B78h54WmTfyjxKVBeCfeuf8qM9ALFeEhvRb1YPyzg7mX7LVHg7m5AaJRJEbivYKOCU4ZfGFmAr2%2BIZPZKxncO5EvFfUtKwHXqZ5VbfqgDRKblufH4u18TIJCvJuqwuaa3JSFL7u5i2XU4Xwwe1kWvuWBKS2QV%2BSTXD0boeR1J7hLe9DCeENumzLKurHcRMXTzvU2UPiJq9v1A376kMYRI3pFStYpcPHFw14dpTVxLDZfsT8Ua9lbiN4fvaOLdCw35CtD7i4l%2Fepep%2FKLLQZzd6%2B8xSALMAS%2Bi2XOr3CHIXl7cJj%2BBwLy9cW%2FsHF4J5vVM6hKqKmXioanpE%2FAx7QpElRyuhgn0H1d1xGIz2oUjFBMMTo370GOqUBmD0vIA49uznaeipmo8%2BYBIQBcQXVm7ylmGKVd0elgrBF0ePrJGrpf%2BqAuPMdKrsKrDk32DTCQl4A6bvwGmbMYqayjh3Z9LVPXHOYs3yaV5FST0CDK%2BQMkxxdxk2PMtVM%2F8yZrnzNr1avHkr3jwKIoNPoRi8MfXGXP2swH3kXQpAsZB8EikAnXLHYs%2FJiKT1CZ%2BhYLWvTI8S0JV0%2FtB6476bA4yh6&X-Amz-Signature=aa0bb2a4f37abac0b1161aec5502d152f7e627db3ebfe34d3253720edc44d5b3&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46645HNYRHC%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T043033Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIC2U6lyUxAHgpsphisELz73fixkPZF0vkke2KLxoaZzRAiEAhEnxWUu8NW5YnKBBjpfNbXwllMACHMJi1nLBdcxsuLsqiAQIzf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLGNJDCPmvLGcmO0LircA%2FjyaAR9UNklLUNh0XiOZPy7BOdaWLpSLDPq1BdZmL6ZGy4RVgx4zn9toarogzxqF5m9QjvuJteMUEu1Ql%2FbfqvwWHPAufobOh32phalxL1CWO0RT5QIe8UAspDkAkX%2BT3Gk7zBfr%2BB3PJ%2FEB%2BpjOjjTxv%2FjJeBf%2BeTPEjq2Dfg7TJy9T9klKzFvLDtjslTkTXH3vBAn9ZhgmJJeI9vUe7FFZi2IGcirOFZBEUtO6kqyMq2Le4PNgLCaXhZpvS%2F5DNzK%2BNQQsTeMKRNLjSOJOEHkdDsiPA1pZIHGB1pwyYaW%2BharYoQFbUTD%2Fx7cJUBz2iza19oU%2F1j9Und6X6ziNYW1HCZ%2Fdbl1LmkfnnQ7LrbqX1B6wk4EwKCSNv6t5w2lcC3W63yK9EWZc7oo9HbxtNoVD4ANM82ALqQpGLk81gToFARAwVGnW08xWHur10P1lW8AlJyuBI3dC2JKij%2Fn1qaXcLli6zPb6OKOgfpNgWjtEKeTSWfjLEf2D%2Bbb5lmJW%2BXlDLHbzJuohi5uIURGXpzasBrHYfbPRHlvd%2FzdjaDpvNB8jCU8n9h3liItJhiHZP1uexOAV8ORMx1DHMA2LeYx6O1VhNaZuo5Hvx7%2F8FRQMh%2F0NNYco5wBJo0TMMno370GOqUBMwnSPerOGt%2FIR4N2lAcLA1PuSiscrJO5VHYfEXHbaaIBbBvQbEG0zmsVqzipo8tPNoC4y2b0UmJOukRIKne1XFo4dlfbsE8u%2BJyFLdsP15HaEXNvxUpAD7ONtb6We%2FzQcGuFdZHSrRNZm%2FdxmEGfq31cQwc3F3DN784DGRKTpH5emo2DRFa1lDbNqKST34lwLUEd2K6lBeDlb5yb0AhwYgb9Vzv6&X-Amz-Signature=d78c2e724eaef6e72bd9684177645d6dcc6f8d526604599d661f5da581c3a566&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46645HNYRHC%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T043033Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIC2U6lyUxAHgpsphisELz73fixkPZF0vkke2KLxoaZzRAiEAhEnxWUu8NW5YnKBBjpfNbXwllMACHMJi1nLBdcxsuLsqiAQIzf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLGNJDCPmvLGcmO0LircA%2FjyaAR9UNklLUNh0XiOZPy7BOdaWLpSLDPq1BdZmL6ZGy4RVgx4zn9toarogzxqF5m9QjvuJteMUEu1Ql%2FbfqvwWHPAufobOh32phalxL1CWO0RT5QIe8UAspDkAkX%2BT3Gk7zBfr%2BB3PJ%2FEB%2BpjOjjTxv%2FjJeBf%2BeTPEjq2Dfg7TJy9T9klKzFvLDtjslTkTXH3vBAn9ZhgmJJeI9vUe7FFZi2IGcirOFZBEUtO6kqyMq2Le4PNgLCaXhZpvS%2F5DNzK%2BNQQsTeMKRNLjSOJOEHkdDsiPA1pZIHGB1pwyYaW%2BharYoQFbUTD%2Fx7cJUBz2iza19oU%2F1j9Und6X6ziNYW1HCZ%2Fdbl1LmkfnnQ7LrbqX1B6wk4EwKCSNv6t5w2lcC3W63yK9EWZc7oo9HbxtNoVD4ANM82ALqQpGLk81gToFARAwVGnW08xWHur10P1lW8AlJyuBI3dC2JKij%2Fn1qaXcLli6zPb6OKOgfpNgWjtEKeTSWfjLEf2D%2Bbb5lmJW%2BXlDLHbzJuohi5uIURGXpzasBrHYfbPRHlvd%2FzdjaDpvNB8jCU8n9h3liItJhiHZP1uexOAV8ORMx1DHMA2LeYx6O1VhNaZuo5Hvx7%2F8FRQMh%2F0NNYco5wBJo0TMMno370GOqUBMwnSPerOGt%2FIR4N2lAcLA1PuSiscrJO5VHYfEXHbaaIBbBvQbEG0zmsVqzipo8tPNoC4y2b0UmJOukRIKne1XFo4dlfbsE8u%2BJyFLdsP15HaEXNvxUpAD7ONtb6We%2FzQcGuFdZHSrRNZm%2FdxmEGfq31cQwc3F3DN784DGRKTpH5emo2DRFa1lDbNqKST34lwLUEd2K6lBeDlb5yb0AhwYgb9Vzv6&X-Amz-Signature=434033645471091f39a2a6b9be9ed5b7be7d3a03b1beb80ef0cf014c497aada6&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46645HNYRHC%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T043033Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIC2U6lyUxAHgpsphisELz73fixkPZF0vkke2KLxoaZzRAiEAhEnxWUu8NW5YnKBBjpfNbXwllMACHMJi1nLBdcxsuLsqiAQIzf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLGNJDCPmvLGcmO0LircA%2FjyaAR9UNklLUNh0XiOZPy7BOdaWLpSLDPq1BdZmL6ZGy4RVgx4zn9toarogzxqF5m9QjvuJteMUEu1Ql%2FbfqvwWHPAufobOh32phalxL1CWO0RT5QIe8UAspDkAkX%2BT3Gk7zBfr%2BB3PJ%2FEB%2BpjOjjTxv%2FjJeBf%2BeTPEjq2Dfg7TJy9T9klKzFvLDtjslTkTXH3vBAn9ZhgmJJeI9vUe7FFZi2IGcirOFZBEUtO6kqyMq2Le4PNgLCaXhZpvS%2F5DNzK%2BNQQsTeMKRNLjSOJOEHkdDsiPA1pZIHGB1pwyYaW%2BharYoQFbUTD%2Fx7cJUBz2iza19oU%2F1j9Und6X6ziNYW1HCZ%2Fdbl1LmkfnnQ7LrbqX1B6wk4EwKCSNv6t5w2lcC3W63yK9EWZc7oo9HbxtNoVD4ANM82ALqQpGLk81gToFARAwVGnW08xWHur10P1lW8AlJyuBI3dC2JKij%2Fn1qaXcLli6zPb6OKOgfpNgWjtEKeTSWfjLEf2D%2Bbb5lmJW%2BXlDLHbzJuohi5uIURGXpzasBrHYfbPRHlvd%2FzdjaDpvNB8jCU8n9h3liItJhiHZP1uexOAV8ORMx1DHMA2LeYx6O1VhNaZuo5Hvx7%2F8FRQMh%2F0NNYco5wBJo0TMMno370GOqUBMwnSPerOGt%2FIR4N2lAcLA1PuSiscrJO5VHYfEXHbaaIBbBvQbEG0zmsVqzipo8tPNoC4y2b0UmJOukRIKne1XFo4dlfbsE8u%2BJyFLdsP15HaEXNvxUpAD7ONtb6We%2FzQcGuFdZHSrRNZm%2FdxmEGfq31cQwc3F3DN784DGRKTpH5emo2DRFa1lDbNqKST34lwLUEd2K6lBeDlb5yb0AhwYgb9Vzv6&X-Amz-Signature=fa8086217c52456795e978a283309333476200f553e5c2abd3a81ec7bfed4e29&X-Amz-SignedHeaders=host&x-id=GetObject)


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

