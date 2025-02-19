---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466Z5HDL57V%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250219T202640Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIFRCDsQB8MrsqjCRJXo\
  BE39aNrDM4sXw%2FwpZT1PeamHJAiA%2Fkku6C9WZBTn5u8WW1iGLbhj8UqhBDB7mEMCuS5p8AiqI\
  BAit%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMZqcbDvo4e%2Br6rGo\
  eKtwDJRyl81kQJ%2BynZZseAjpnANnzNP8WfG1ejxfMurC8eTNXdzxVpFFJ3bOVmIe9ilZki1cuOl\
  OlIZqlHQFQjf%2F2CrjthrLd3pXVdP1V1T2eQyBav25NQiKAK2LD%2FLXA4K%2B25Jc5ozwyyqONl\
  Ry6wNkvdYB%2FdzNZxI4to2UORJGmOLewlE3e1UxeLZZBp4%2FHLqO1O5Vhsz1B6t%2BNq2RZKuqa\
  B%2BoVyNZUciZBOYAptKExR%2BgTT7Q1F2GgKMKocXL0jVDeDPsG8%2FH7w7%2F8SWGJGsaIuJTmS\
  VV8FFGJ6fc2DcrfoJcVMQ8UvHqhmysSOJEKg8fEjm6XLm2OV2Kag7kA%2BsCwbj2SvfQe%2FNo1wU\
  1PwfXwPd8IMsD8T%2B3lSJYo6S7XDeLbEH6%2BMIbn2grsu1EBMXMdyMrZkvul57RPRcyCFo7%2Bh\
  IOjI6GFzVZ4nUzBF4oMKhSCv%2Bjxi3QSv0arHQLiK4uw%2FEi60s7FS81GFsT1h%2FvEtyf1nA4f\
  HXu1RA%2Bje2fjFSFvscDtCYjTix0sqtgBkLRmhaTZertWDA6JQCBWh8Z0tBlmX%2BsL1ohI1i%2F\
  Y%2BsbfjzVi%2Bppqq%2F5A7ZdlMiRUIEjp6tx2GPa3eqhIw%2FyrSm2YcKzSXLHC6DiOvNoQVqQw\
  oO%2FYvQY6pgED3aYDsNM29ldj7cHZ3Gj5rG6N2Ks0Hca5w1%2BKsaqtsdPqB083FAO7UacXAHlTw\
  f3THX7wErjEGgwabjC2iwVS87Shm%2Fb%2BWOgfWYenyiskZj3n228%2FLvz2Zm3xgiCxTqIlZL3v\
  TgwOLf25fK%2F3KZF4T9GL7NDkxPPtO4LjzrGGVqVVOz%2FkQ40uHYYJpSbHO4A%2B9Yb0qSu0%2B\
  KJOh%2FzrywTT9VDwa7Xb&X-Amz-Signature=0b6c7c12b38fac1d63135780aa561e5618edffe\
  43e9480a708c075b3d2101464&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4666ICCM736%2F20250219%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250219T202503Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEY\
        CIQDEjY7fxmaaRMulQBc70MT5EPSoA6O24sVeqPNVTGctNgIhAI7vRNRabbEy6NlaXLyJSI\
        %2F051nJdtmaQIHJRfngpABeKogECK3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM\
        3NDIzMTgzODA1IgzjypwCZeooVqk%2BI0Yq3AP%2Fn%2FOWkEbHnvCgF3HsvPr%2FGBb%2B\
        ugcDjZwgJChkQRFtwtEF03T9BLY0c16XuBGxOPJq4fg7GSfookwmU4vEH9vgQy%2Bmqo%2B\
        qBDLT%2BS4b6uQoQA0%2B8ih0JRlaA9ErCfpK3f4bQTMwB1EiQoLfPJnZkblsk4uoOJUtVv\
        HDzVUhWW%2F7hBWgn08eN2AFSj4%2FEpWMvB2MMAjSrfeiZmBIiZJOua7KsRaesytIISpmw\
        LmrnXanjSVwJ47Zz9mZsYbeiw3%2FeOYFOTZKw0xhC23Q1DS65VzX3rJjOKgHL8acZrkekF\
        gkQ9BjZdWPiw%2Fw%2BQZ2927oZ9tkLf2APEg0oUdQVpESHkr2mKywujBTBNQiUPKu%2FQN\
        5VVPOPm1oBWPEdFjckXmEesSgkpYDztPOlFBaL%2BewFzqHt1YIFnNOPDATRTTrITIwpFf6\
        3ZbP12Q89QOzd2RH9oghE%2FTt5Tm41pFW2j3%2BQkzrhRQwBm5oL15oejO6YIf4y27ywWN\
        fw6ehT8WjEO7Lwzs5U1FNEx31HBLD0uSL4x3gQWIP1C9gKai80OUdQ7KUUaIf6X2xWfHlDE\
        hgZSs6LkDMYFhX5jQUsalZWluYnfzld7RwNflWUFm%2F2T4eIo%2BlQUQ0KHvo3zIHQySbq\
        jDP7ti9BjqkATjZWsABnpWmDpPezIofWslA4Gr7WT0AKE7J1izYoy9V3pAKX2rbIEF87Iib\
        dg9P97O6k%2FEpm4biIFs2xQRO8PD9Hl5FzcLPXmyDFTlbksG4V7RfytHwX05IuOIz0q66m\
        zoqnN2zhmgEiiMxXpJ3NEDm7V%2F2LvNPjxTURp3qDM17WKO6tb0RR57QUWRU%2F%2BVcJL\
        %2FIMe%2BGDLsHlgvCeoUwy133P8Pd&X-Amz-Signature=e6cc24ce8a520fcd5747b8b7\
        5657dc16d260edc14a050f2427c1d015f3dd9490&X-Amz-SignedHeaders=host&x-id=\
        GetObject"
      expiry_time: "2025-02-19T21:25:03.958Z"
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
UPDATE_TIME: "2025-02-19T20:26:47.325Z"
EXPIRY_TIME: "2025-02-19T21:26:36.710Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663OM7ONGO%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T202637Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDX2b3%2BR4RcCMEob2kLXQzy8LfT%2BRQn1sxB3eQ3X576BwIhAKBobf6GYubyUtLrgvH00JahqYyOYVUh%2BjojSmEI5k6%2FKogECK3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igwwdmx12aM3RgIBvgoq3APrNEuIgxug1hE9P%2Fj4taaaFHAeyUlHboIJsArt7cE7yai2hostNvaMznXwrr%2Bidl5J5UZaf7kQT2Gh2Aa7Vh3P%2BzEi3KX1mmFdQdafvFnuGbBo57yKXvxq8%2BPpk05T8HFbtXLa7mc%2Fj7gTX9QBFBu9qAdFUl4VdGokpBC6nO1TfE7O3mnyKDkCWXmvQSn5O8x1HNgEootsPTLZjgLPenCpLrUNxYmT61kZV9CNNAfRocmJtZAbNifBb86E%2FAH%2FisBmvon8bE7Wf7CSn4kDzSCxlNELd5wTKwlukCZjmsaItORagewG6mjoehIM%2BINRPXkTd46NCyUMGF%2FYDgSgJErEIMJ7j0t9DT58jzxCAj9fPWV%2FcHaD9py87VRR6hO8gTjOPKvfA1PXjM17BI57UPov1dQ5sjkZIvviaMpBHza1E21Ib1376QszUjOlxOsjL6Fxd%2B0zMy8eTEP1y72%2FzL5TBvog9wLiKrBpB4uf%2Fig1OiqAaelcddrJ5OIjDBpoFPYYhY56ssjKBIAnEsY4p2NPh%2F%2BR80MDmh7g59DsPvdd8tzwyLj7rhilF7oOmDBd3QN2nsXkfkY0chtRMWnAk1EdYf9TNxSZbAKQ%2BviHqqYz681viGDa3jEHVDaCLjDu7ti9BjqkAdDpoAX2m9ZoP30xNB20tbl1JkeIKs3F2lsYPUUqgxcMNH%2FNzocymoNVf4a%2B9hXJgfzCT0fKGwO%2B%2BPDHlp4nQ99%2BnxMy4RzoPvvgY4C%2BLThea7oLPC7yFMysC2u%2FypmMuAiGu2MzJx9PsDYJrVS4ZkDFczd5zIkIO3lzmVxlsVxvf6k81opLH6ggGpc2qJ%2FoExiJGlUxZmmkSTwQcyeg3olFebsF&X-Amz-Signature=5f70d0ffdf2ad3221698e76e1f19708eac262bba0fa958b4adc975befdb23031&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663OM7ONGO%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T202637Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDX2b3%2BR4RcCMEob2kLXQzy8LfT%2BRQn1sxB3eQ3X576BwIhAKBobf6GYubyUtLrgvH00JahqYyOYVUh%2BjojSmEI5k6%2FKogECK3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igwwdmx12aM3RgIBvgoq3APrNEuIgxug1hE9P%2Fj4taaaFHAeyUlHboIJsArt7cE7yai2hostNvaMznXwrr%2Bidl5J5UZaf7kQT2Gh2Aa7Vh3P%2BzEi3KX1mmFdQdafvFnuGbBo57yKXvxq8%2BPpk05T8HFbtXLa7mc%2Fj7gTX9QBFBu9qAdFUl4VdGokpBC6nO1TfE7O3mnyKDkCWXmvQSn5O8x1HNgEootsPTLZjgLPenCpLrUNxYmT61kZV9CNNAfRocmJtZAbNifBb86E%2FAH%2FisBmvon8bE7Wf7CSn4kDzSCxlNELd5wTKwlukCZjmsaItORagewG6mjoehIM%2BINRPXkTd46NCyUMGF%2FYDgSgJErEIMJ7j0t9DT58jzxCAj9fPWV%2FcHaD9py87VRR6hO8gTjOPKvfA1PXjM17BI57UPov1dQ5sjkZIvviaMpBHza1E21Ib1376QszUjOlxOsjL6Fxd%2B0zMy8eTEP1y72%2FzL5TBvog9wLiKrBpB4uf%2Fig1OiqAaelcddrJ5OIjDBpoFPYYhY56ssjKBIAnEsY4p2NPh%2F%2BR80MDmh7g59DsPvdd8tzwyLj7rhilF7oOmDBd3QN2nsXkfkY0chtRMWnAk1EdYf9TNxSZbAKQ%2BviHqqYz681viGDa3jEHVDaCLjDu7ti9BjqkAdDpoAX2m9ZoP30xNB20tbl1JkeIKs3F2lsYPUUqgxcMNH%2FNzocymoNVf4a%2B9hXJgfzCT0fKGwO%2B%2BPDHlp4nQ99%2BnxMy4RzoPvvgY4C%2BLThea7oLPC7yFMysC2u%2FypmMuAiGu2MzJx9PsDYJrVS4ZkDFczd5zIkIO3lzmVxlsVxvf6k81opLH6ggGpc2qJ%2FoExiJGlUxZmmkSTwQcyeg3olFebsF&X-Amz-Signature=c82ae57d96eb97d847c6cae662bfb5fc6ecbde1aa8afba5be9bc29511569626d&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663OM7ONGO%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T202637Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDX2b3%2BR4RcCMEob2kLXQzy8LfT%2BRQn1sxB3eQ3X576BwIhAKBobf6GYubyUtLrgvH00JahqYyOYVUh%2BjojSmEI5k6%2FKogECK3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igwwdmx12aM3RgIBvgoq3APrNEuIgxug1hE9P%2Fj4taaaFHAeyUlHboIJsArt7cE7yai2hostNvaMznXwrr%2Bidl5J5UZaf7kQT2Gh2Aa7Vh3P%2BzEi3KX1mmFdQdafvFnuGbBo57yKXvxq8%2BPpk05T8HFbtXLa7mc%2Fj7gTX9QBFBu9qAdFUl4VdGokpBC6nO1TfE7O3mnyKDkCWXmvQSn5O8x1HNgEootsPTLZjgLPenCpLrUNxYmT61kZV9CNNAfRocmJtZAbNifBb86E%2FAH%2FisBmvon8bE7Wf7CSn4kDzSCxlNELd5wTKwlukCZjmsaItORagewG6mjoehIM%2BINRPXkTd46NCyUMGF%2FYDgSgJErEIMJ7j0t9DT58jzxCAj9fPWV%2FcHaD9py87VRR6hO8gTjOPKvfA1PXjM17BI57UPov1dQ5sjkZIvviaMpBHza1E21Ib1376QszUjOlxOsjL6Fxd%2B0zMy8eTEP1y72%2FzL5TBvog9wLiKrBpB4uf%2Fig1OiqAaelcddrJ5OIjDBpoFPYYhY56ssjKBIAnEsY4p2NPh%2F%2BR80MDmh7g59DsPvdd8tzwyLj7rhilF7oOmDBd3QN2nsXkfkY0chtRMWnAk1EdYf9TNxSZbAKQ%2BviHqqYz681viGDa3jEHVDaCLjDu7ti9BjqkAdDpoAX2m9ZoP30xNB20tbl1JkeIKs3F2lsYPUUqgxcMNH%2FNzocymoNVf4a%2B9hXJgfzCT0fKGwO%2B%2BPDHlp4nQ99%2BnxMy4RzoPvvgY4C%2BLThea7oLPC7yFMysC2u%2FypmMuAiGu2MzJx9PsDYJrVS4ZkDFczd5zIkIO3lzmVxlsVxvf6k81opLH6ggGpc2qJ%2FoExiJGlUxZmmkSTwQcyeg3olFebsF&X-Amz-Signature=1fbee381e3a26a8757d842df1f7f5d7134d487af602d67643d59007a3433f9fa&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663OM7ONGO%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T202637Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDX2b3%2BR4RcCMEob2kLXQzy8LfT%2BRQn1sxB3eQ3X576BwIhAKBobf6GYubyUtLrgvH00JahqYyOYVUh%2BjojSmEI5k6%2FKogECK3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igwwdmx12aM3RgIBvgoq3APrNEuIgxug1hE9P%2Fj4taaaFHAeyUlHboIJsArt7cE7yai2hostNvaMznXwrr%2Bidl5J5UZaf7kQT2Gh2Aa7Vh3P%2BzEi3KX1mmFdQdafvFnuGbBo57yKXvxq8%2BPpk05T8HFbtXLa7mc%2Fj7gTX9QBFBu9qAdFUl4VdGokpBC6nO1TfE7O3mnyKDkCWXmvQSn5O8x1HNgEootsPTLZjgLPenCpLrUNxYmT61kZV9CNNAfRocmJtZAbNifBb86E%2FAH%2FisBmvon8bE7Wf7CSn4kDzSCxlNELd5wTKwlukCZjmsaItORagewG6mjoehIM%2BINRPXkTd46NCyUMGF%2FYDgSgJErEIMJ7j0t9DT58jzxCAj9fPWV%2FcHaD9py87VRR6hO8gTjOPKvfA1PXjM17BI57UPov1dQ5sjkZIvviaMpBHza1E21Ib1376QszUjOlxOsjL6Fxd%2B0zMy8eTEP1y72%2FzL5TBvog9wLiKrBpB4uf%2Fig1OiqAaelcddrJ5OIjDBpoFPYYhY56ssjKBIAnEsY4p2NPh%2F%2BR80MDmh7g59DsPvdd8tzwyLj7rhilF7oOmDBd3QN2nsXkfkY0chtRMWnAk1EdYf9TNxSZbAKQ%2BviHqqYz681viGDa3jEHVDaCLjDu7ti9BjqkAdDpoAX2m9ZoP30xNB20tbl1JkeIKs3F2lsYPUUqgxcMNH%2FNzocymoNVf4a%2B9hXJgfzCT0fKGwO%2B%2BPDHlp4nQ99%2BnxMy4RzoPvvgY4C%2BLThea7oLPC7yFMysC2u%2FypmMuAiGu2MzJx9PsDYJrVS4ZkDFczd5zIkIO3lzmVxlsVxvf6k81opLH6ggGpc2qJ%2FoExiJGlUxZmmkSTwQcyeg3olFebsF&X-Amz-Signature=b3b24fec3aa956cfe586ef7fb72fd936bfd4744e8cfa4ecec49f618345052ebf&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663OM7ONGO%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T202637Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDX2b3%2BR4RcCMEob2kLXQzy8LfT%2BRQn1sxB3eQ3X576BwIhAKBobf6GYubyUtLrgvH00JahqYyOYVUh%2BjojSmEI5k6%2FKogECK3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igwwdmx12aM3RgIBvgoq3APrNEuIgxug1hE9P%2Fj4taaaFHAeyUlHboIJsArt7cE7yai2hostNvaMznXwrr%2Bidl5J5UZaf7kQT2Gh2Aa7Vh3P%2BzEi3KX1mmFdQdafvFnuGbBo57yKXvxq8%2BPpk05T8HFbtXLa7mc%2Fj7gTX9QBFBu9qAdFUl4VdGokpBC6nO1TfE7O3mnyKDkCWXmvQSn5O8x1HNgEootsPTLZjgLPenCpLrUNxYmT61kZV9CNNAfRocmJtZAbNifBb86E%2FAH%2FisBmvon8bE7Wf7CSn4kDzSCxlNELd5wTKwlukCZjmsaItORagewG6mjoehIM%2BINRPXkTd46NCyUMGF%2FYDgSgJErEIMJ7j0t9DT58jzxCAj9fPWV%2FcHaD9py87VRR6hO8gTjOPKvfA1PXjM17BI57UPov1dQ5sjkZIvviaMpBHza1E21Ib1376QszUjOlxOsjL6Fxd%2B0zMy8eTEP1y72%2FzL5TBvog9wLiKrBpB4uf%2Fig1OiqAaelcddrJ5OIjDBpoFPYYhY56ssjKBIAnEsY4p2NPh%2F%2BR80MDmh7g59DsPvdd8tzwyLj7rhilF7oOmDBd3QN2nsXkfkY0chtRMWnAk1EdYf9TNxSZbAKQ%2BviHqqYz681viGDa3jEHVDaCLjDu7ti9BjqkAdDpoAX2m9ZoP30xNB20tbl1JkeIKs3F2lsYPUUqgxcMNH%2FNzocymoNVf4a%2B9hXJgfzCT0fKGwO%2B%2BPDHlp4nQ99%2BnxMy4RzoPvvgY4C%2BLThea7oLPC7yFMysC2u%2FypmMuAiGu2MzJx9PsDYJrVS4ZkDFczd5zIkIO3lzmVxlsVxvf6k81opLH6ggGpc2qJ%2FoExiJGlUxZmmkSTwQcyeg3olFebsF&X-Amz-Signature=4c6a25fee09fcaf59faa3aaa228899f2de500556866312a532ecee1e043ef3d1&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QIK7UBSO%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T202637Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQClMYIt8M8ukiUV8RsJQ38lb%2BDSyN9UPtYsf8jB3pmoCgIhAPe3EyMN4nOj6KNQQU0D9BNM11p8p5zG9QGqZuHqsxa8KogECK3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxX7iUO6eDUIK9xwgMq3AN5kNbYwPdcpytKKGF2%2FqNWfxOMLD8RrPhKHkHoH2%2FfGvAL1WYXoiAEC3iV%2FrkL5fMvbmx%2FejqIldGhM9P0OY5cTfrw2V5lVj%2BzYz5W7OXfFtg8%2BrYLNleW8ZsdjKRwSNfuwz2bCFthnoHYp8E8DWMXfEEycC%2BssAWDkeF74KpFbCx9pu%2BWsHAAd1mHGjYg2qXe8GkrCULwntXLbM4uhvN0okb1CF95wScrotLOOE3UepTI%2FOh0ARkUSfHZTn%2FlKr%2FSBMM3SIR4uxFRT%2BHy3sw%2BC%2F%2FU4QpI32f8yu9idZ1YFscQKcep%2FdMfEbirEODwQXprz9PUvqAwuTV5HtkpUVbuYVSaE%2Bdfa2qQdOLc2vK2aG5RGV69AfEqqidYbbumBj6Vz%2F35wWFtfNqiu6A7KP%2FSVP%2BwLEYiCi5hqRAqsBsfN48eqLZsWX8Hba6ACrlLbbmauryJiqY7nP1QrKtigBST9aKhE9qM7G1LzkgZAOTeEYSW4mC6Lpz5o4wZuBvSJZ%2BiC0IBfmQu0QMRnjgntdQ0WdJhBlAYdxjSc2I80%2BS23XMEdsZ9tDBRmD8xPuX3trcZneVWA2FDq0lmpxI8RbmlMFjOxDCujGSm5g3N06uCJTv9asVLsk0hY4OeADD%2B7ti9BjqkASWVLoZJwRiy0WR6dKeDphmL%2FSvN4b6OtGH6uT%2FRvz58Uiw%2BbiWjCXzKgYvd9fKtqhuAdQmZP31gIKfOI36XOCDjuax723PflR1urKE%2BEzg7Pdh00rPM6HmhvgJKHtbxFMc4y55%2FbPf%2FFz9Fjkpbrq8Cov3Q4Zk0BRlYDvbsr67H%2BlTWVHwIlMbdGze9mrZriehyM6lQ6gcN1fG31z%2BWzoMp4Frm&X-Amz-Signature=bbe838dd6fbb930dee9482df35a72a0d0f1769efa015ee4e46402d162357ac88&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SUMLI6F6%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T202639Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCICnEMtTwH8pev0PnDgl3UCDCal5EaPqbHN1myIXlpTIAAiEAxAv8cidNmK7lOIm4ihsP49Tjt4XF%2BQr6kw0Pyrba8HMqiAQIrf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDBh9cPeCJP4A5iRsbSrcA6DrEVTyjk3v%2F%2FvppS%2Bpd19M%2BbdQwdXj9sjdg5OhhG0eryJHWuk5H9XedKNNiToVxNMJ9CppMuCfhuqakT81mJbpT6UMaAyxdST%2Fefqe8c%2FuO6Dz51dE1Levnb4xvh1RdHT57AvwD8EOtVT%2FY2CSW7d38IWqMOiEw3TxXi41Bew5QpbNHv%2BeSQdAWt7qQmHVciltV8BkbdTb5i7YGk9l0R3wstG3KGgwEG8oxZrma8QCMXLuI1OuEvfyB%2FGskrSIqnpkzvRucApuhezMUxigsraSLYnaX%2FS9PGN3td89GFn9KkecWddiyGpIcCTYe4%2FxC%2Fc4BCIqgy9MouTYI3KH3ZVi1d8tloqSyOtwX9EC8Q8oMqtOT0XcA8mlcqHjZR6fqZ10EFNQwsBX2BCN3NJe7fxMhrOcXzQb2bQzOQbFgExTlmr52KTUCZXNRzjTlsWEpNAq9WmSivQpoHJxCw%2F5OkqWj71XpPSNBFoxWxJ2q5y1EBcD5HuiPKhxeNsHaXsS7mEiyYHTbrYF10OjrtL%2FTMb772jOrHZq4Hjfe4pwRlM%2FOeuMn59rpopfhLxHfos%2FHKIL4jlHd%2Bl4zuW%2F7omc2CYq39UVbokuqs%2B9NlZDMlC5YCvZ19fOVlR3ekziMJbv2L0GOqUBJu6zx13PzJQtPhYYnc0rvbg%2B%2FK8GJH%2FNJQrgS8AAOfsVYYjYMmaWNOmWfvZwmoojz7WXvq5q9Tq8iJK%2BgKMS3K4m%2Fky5aRoDNWhPw9qiy%2FmOHB8xE5MAwMnbyQsqzkcQcz8in%2Bck6M5eu1G4JvhshefzVPmyauRXYqcB2eijbDivCrIINYBV81tgm0Zf%2Bzc73LlJlPjplKGbQMUXJVNRBv1wIyuC&X-Amz-Signature=f6d00e574e3cc600b8568310fd710ff5be78f7770f62f419004d4fd3a7c8d84d&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663OM7ONGO%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T202637Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDX2b3%2BR4RcCMEob2kLXQzy8LfT%2BRQn1sxB3eQ3X576BwIhAKBobf6GYubyUtLrgvH00JahqYyOYVUh%2BjojSmEI5k6%2FKogECK3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igwwdmx12aM3RgIBvgoq3APrNEuIgxug1hE9P%2Fj4taaaFHAeyUlHboIJsArt7cE7yai2hostNvaMznXwrr%2Bidl5J5UZaf7kQT2Gh2Aa7Vh3P%2BzEi3KX1mmFdQdafvFnuGbBo57yKXvxq8%2BPpk05T8HFbtXLa7mc%2Fj7gTX9QBFBu9qAdFUl4VdGokpBC6nO1TfE7O3mnyKDkCWXmvQSn5O8x1HNgEootsPTLZjgLPenCpLrUNxYmT61kZV9CNNAfRocmJtZAbNifBb86E%2FAH%2FisBmvon8bE7Wf7CSn4kDzSCxlNELd5wTKwlukCZjmsaItORagewG6mjoehIM%2BINRPXkTd46NCyUMGF%2FYDgSgJErEIMJ7j0t9DT58jzxCAj9fPWV%2FcHaD9py87VRR6hO8gTjOPKvfA1PXjM17BI57UPov1dQ5sjkZIvviaMpBHza1E21Ib1376QszUjOlxOsjL6Fxd%2B0zMy8eTEP1y72%2FzL5TBvog9wLiKrBpB4uf%2Fig1OiqAaelcddrJ5OIjDBpoFPYYhY56ssjKBIAnEsY4p2NPh%2F%2BR80MDmh7g59DsPvdd8tzwyLj7rhilF7oOmDBd3QN2nsXkfkY0chtRMWnAk1EdYf9TNxSZbAKQ%2BviHqqYz681viGDa3jEHVDaCLjDu7ti9BjqkAdDpoAX2m9ZoP30xNB20tbl1JkeIKs3F2lsYPUUqgxcMNH%2FNzocymoNVf4a%2B9hXJgfzCT0fKGwO%2B%2BPDHlp4nQ99%2BnxMy4RzoPvvgY4C%2BLThea7oLPC7yFMysC2u%2FypmMuAiGu2MzJx9PsDYJrVS4ZkDFczd5zIkIO3lzmVxlsVxvf6k81opLH6ggGpc2qJ%2FoExiJGlUxZmmkSTwQcyeg3olFebsF&X-Amz-Signature=686e5cd8a977070badb694f326c9ab87f3be9b3744dd542728756ecf97824094&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663OM7ONGO%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T202637Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDX2b3%2BR4RcCMEob2kLXQzy8LfT%2BRQn1sxB3eQ3X576BwIhAKBobf6GYubyUtLrgvH00JahqYyOYVUh%2BjojSmEI5k6%2FKogECK3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igwwdmx12aM3RgIBvgoq3APrNEuIgxug1hE9P%2Fj4taaaFHAeyUlHboIJsArt7cE7yai2hostNvaMznXwrr%2Bidl5J5UZaf7kQT2Gh2Aa7Vh3P%2BzEi3KX1mmFdQdafvFnuGbBo57yKXvxq8%2BPpk05T8HFbtXLa7mc%2Fj7gTX9QBFBu9qAdFUl4VdGokpBC6nO1TfE7O3mnyKDkCWXmvQSn5O8x1HNgEootsPTLZjgLPenCpLrUNxYmT61kZV9CNNAfRocmJtZAbNifBb86E%2FAH%2FisBmvon8bE7Wf7CSn4kDzSCxlNELd5wTKwlukCZjmsaItORagewG6mjoehIM%2BINRPXkTd46NCyUMGF%2FYDgSgJErEIMJ7j0t9DT58jzxCAj9fPWV%2FcHaD9py87VRR6hO8gTjOPKvfA1PXjM17BI57UPov1dQ5sjkZIvviaMpBHza1E21Ib1376QszUjOlxOsjL6Fxd%2B0zMy8eTEP1y72%2FzL5TBvog9wLiKrBpB4uf%2Fig1OiqAaelcddrJ5OIjDBpoFPYYhY56ssjKBIAnEsY4p2NPh%2F%2BR80MDmh7g59DsPvdd8tzwyLj7rhilF7oOmDBd3QN2nsXkfkY0chtRMWnAk1EdYf9TNxSZbAKQ%2BviHqqYz681viGDa3jEHVDaCLjDu7ti9BjqkAdDpoAX2m9ZoP30xNB20tbl1JkeIKs3F2lsYPUUqgxcMNH%2FNzocymoNVf4a%2B9hXJgfzCT0fKGwO%2B%2BPDHlp4nQ99%2BnxMy4RzoPvvgY4C%2BLThea7oLPC7yFMysC2u%2FypmMuAiGu2MzJx9PsDYJrVS4ZkDFczd5zIkIO3lzmVxlsVxvf6k81opLH6ggGpc2qJ%2FoExiJGlUxZmmkSTwQcyeg3olFebsF&X-Amz-Signature=13bf73aabb7aa70f6fbcfa5043b424f6ecc929198d07dcf6da6e1cdf7bfbe40f&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663OM7ONGO%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T202637Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDX2b3%2BR4RcCMEob2kLXQzy8LfT%2BRQn1sxB3eQ3X576BwIhAKBobf6GYubyUtLrgvH00JahqYyOYVUh%2BjojSmEI5k6%2FKogECK3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igwwdmx12aM3RgIBvgoq3APrNEuIgxug1hE9P%2Fj4taaaFHAeyUlHboIJsArt7cE7yai2hostNvaMznXwrr%2Bidl5J5UZaf7kQT2Gh2Aa7Vh3P%2BzEi3KX1mmFdQdafvFnuGbBo57yKXvxq8%2BPpk05T8HFbtXLa7mc%2Fj7gTX9QBFBu9qAdFUl4VdGokpBC6nO1TfE7O3mnyKDkCWXmvQSn5O8x1HNgEootsPTLZjgLPenCpLrUNxYmT61kZV9CNNAfRocmJtZAbNifBb86E%2FAH%2FisBmvon8bE7Wf7CSn4kDzSCxlNELd5wTKwlukCZjmsaItORagewG6mjoehIM%2BINRPXkTd46NCyUMGF%2FYDgSgJErEIMJ7j0t9DT58jzxCAj9fPWV%2FcHaD9py87VRR6hO8gTjOPKvfA1PXjM17BI57UPov1dQ5sjkZIvviaMpBHza1E21Ib1376QszUjOlxOsjL6Fxd%2B0zMy8eTEP1y72%2FzL5TBvog9wLiKrBpB4uf%2Fig1OiqAaelcddrJ5OIjDBpoFPYYhY56ssjKBIAnEsY4p2NPh%2F%2BR80MDmh7g59DsPvdd8tzwyLj7rhilF7oOmDBd3QN2nsXkfkY0chtRMWnAk1EdYf9TNxSZbAKQ%2BviHqqYz681viGDa3jEHVDaCLjDu7ti9BjqkAdDpoAX2m9ZoP30xNB20tbl1JkeIKs3F2lsYPUUqgxcMNH%2FNzocymoNVf4a%2B9hXJgfzCT0fKGwO%2B%2BPDHlp4nQ99%2BnxMy4RzoPvvgY4C%2BLThea7oLPC7yFMysC2u%2FypmMuAiGu2MzJx9PsDYJrVS4ZkDFczd5zIkIO3lzmVxlsVxvf6k81opLH6ggGpc2qJ%2FoExiJGlUxZmmkSTwQcyeg3olFebsF&X-Amz-Signature=d0468df5b2224a37e5b09ad850e25eebb6672ddbf9f5a579bc0e8735844fafd3&X-Amz-SignedHeaders=host&x-id=GetObject)


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

