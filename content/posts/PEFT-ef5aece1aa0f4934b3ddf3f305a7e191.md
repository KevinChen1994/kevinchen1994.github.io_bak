---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466XFNXAP2G%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250221T063323Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEKb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIAwMPOklq%2FvfjwuiQ\
  SLVNfPAwtnF0hrWDdub5%2FQL5DgBAiEA%2BoidPMfmRYUpYP6B9eYYglf6L3n567VaZofWA0dmWm\
  8qiAQIz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDJFQmWnvqRG94\
  Ep5ayrcA2rK5eqCW57ez2F5dWh7crfxbvxSGmbg0umX3DJdwbkj1iEM5zYYJ5gIc2x6XIwgIYOW49\
  Ojm4urPhN3Ph7xAm6OctPq3wJNeevN5DMcCCWUecu4fPkpqsaBTpoNs7rhXl5f233GZN0k5q%2Bb9\
  2cF2M2jCTU8eWUl9rpJUWLuT7Gg9On1s2zhicqW9ObmrBCFA4v4V9gqf%2Fj1CZ8d%2FGpi4tcGlz\
  P89Uku1FA306b3z%2FMCN%2BVct2BD%2BxdG4YUvyAI16w6vMc2%2BFcLE8%2FjZGZ4%2FtjpDE%2\
  F1q%2FEyjdhIiEVqQGchWfRDIV%2FJG9wTfVqYct5ELlOaNZFH3ZgzdBIi1tLsPztnP0VGIgbipg%\
  2BrmWJGZ6hA3J4tSTqjFoZ78XkT92uhgq0vWhhgq3ga1uXL0WrNNsITdVTP1Lj5oPwTfxXbKcJ8oS\
  yR%2BqfP7UdtSd4BNMD76oh5CBgW9NajIELRE73IOLpmKZxQOuwBdFAb%2BWr4eBR%2BbftufI1v0\
  fmGMGj6DUuNDGyX48jnxmUGvK9jYbXgQAtFTC5edSQ3ahwwhxT8AZPmjSz9TGI%2BaJZG%2FRf7lK\
  Qs%2B2UxT67pgtXeF2CruG0Wd6zMBhU3N5LXKs%2B9H%2BFPH2YMvzmH4d3ldhIy1aORQMK2j4L0G\
  OqUBx2Kos33oK6KwD7uscdfiU6F9QT2douLIXHJ0E%2Fxg1tC6TQ8nDq0Zb9ENmHwm4dLq0CNEqAF\
  jcCqGtwtmih5PyUKxxKbMFfcvj7IA26lV%2FmWj%2B6OrQeZ8jUDcHpCeXZ0AM%2BVYDMWm3XEsZp\
  Bdm1uKrLY2njUGOK2u1Bb5eA6E4LbE6fXzMnnfMazUBZxMEHhYG2PQPkxPxk67EtYmFYs7dmeH0XY\
  o&X-Amz-Signature=a3b414043cbd11f002ecbe1d10d109a0e6ece307de5d55cab6e77150a42\
  3e4d3&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4663IRQG3OQ%2F20250221%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250221T063131Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEKb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIGMGYRETH5nogKpXHy4v1Bcn5EJyUl8OeUSbE0UE3WleAiEAsPXp9tQQe8KAQg%2BVFWIG\
        yCyCUeChkEOyucuX%2F4Q%2BKOsqiAQIz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAG\
        gw2Mzc0MjMxODM4MDUiDHrrlGezBPV%2FZZC3nyrcAya5qR7OzGk8%2Fj9Ievek7JTQDkTi\
        XSSJ6xk9NjbyluPedswcSR%2Bix98MSzuWllKVogLLiSluU5YU6skNEq%2BZXV9wTecJdju\
        BQlAhjoKkffZT4nCglza4dfR279YtO1%2BvAXrd579Hc%2F6C1R4GHKGuqa8K2yqchZkDmz\
        13%2Br%2BHZMTYZPpYQR808I9aVILHl2eLYAzZOCEyYnnjor0F8qt1BoPPfAfJA5bPIYtiX\
        rmu4cmJefLJvfghHMM4yXjAS7p1uRAABoE4td6mQnIiHKdHeVBYSY6QnhwxCblr8iJNHFSz\
        OeruKuYguE2fSM7drpSwFGcgZXZ9gYmgojBs5k%2FYA7SBkle85BusfFJaP%2B88hKCmRRE\
        G4WoD5%2F%2FrKl3nX8zWQE1SAoiiwh7LphKGIutEyFI04BEwMC4CvCOPxyBHdjlCbtbdI%\
        2FKFQUjd8addAwOw1L%2Fh0CmydDqN8LvdOUq8%2FNHYt0PHldA4X64DwUUiLaVMrQECjX7\
        mclJigq%2Fvv4ccx%2FPwkH5gDkf7eFig0ISJ5o4N33rBCs7Z4f8JHFrOcfLnBNsCeFnbdS\
        %2FIMMUucHpsoYBTQMj5fbv1dk%2BNhlK4Dgu5HdFMK%2BhE83MYtZuKmpDZSOsG5ML9tHL\
        jvXQgMLmj4L0GOqUB2Hhuv2AbiLa0Fpa%2Fb7qIb2rUcV4nONsoSrU64pSOsI2izE%2BgBo\
        A343t7Rrn18rzWn8DrT9h3ZGgUSSbd8yq2tjQirAg7wTptywzfYAXs5cNBKO1aabXVSoJ%2\
        F3Z1CoasHJC%2BP9lbNQmMA42Wo%2BOeTQiz2Ahh1P1kmd7E4xb7e754574gzQP6Osc9vTf\
        sRKfjtU%2FJzGNqLt5HXjNLI7hZafAj6h3st&X-Amz-Signature=762b620167d0b7ed39\
        385abb7c180f47b6681ee03805996a41c36602c450cc88&X-Amz-SignedHeaders=host\
        &x-id=GetObject"
      expiry_time: "2025-02-21T07:31:31.188Z"
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
UPDATE_TIME: "2025-02-21T06:33:28.494Z"
EXPIRY_TIME: "2025-02-21T07:33:17.897Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WJ5FGREL%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T063318Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCIcpElDWWKDhxQOrqE9xuBGcj0ZrnTgKnfeptu32cPAwIgcS0nYUjbjAs8StGop21OctLgBkYfygj7dusBzlRQ1GYqiAQIz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOYC7GAeCoCR3pIYayrcA15uHJlVCTaTEAGS3Kn5bLmWVBxXTWU5TU98mv%2B6DA264u86fNCrQaEpSEt9fLr2YDC0uPfvBiLtU6lzYBzxeLokkoXzM5txo4RzSReK1X6U0EdiSwuNmt0HCYWBU9sIlMloHImbLHgben1TtdmzN20BIaYsBf1oL7XqS2jKE9FtXscBiW3a5h0lH3A4swvsbhVbGE4bnEkAZyqlYmWMemhm3Zl8TKhPG9s1OVE0XevJRHqrwhhqg7QElPzy3jrwHbDyFyPiU%2FBZnGi9skfIiL%2FImu%2Bjn96wxuT%2FXbBbQ14ocPkl1wbWtxDo10hY5odZkY5%2BJsocNqowJeF5p5tWpav%2BHGYQVJC1RN5Kt1FfaLQy%2Bya%2Bqrt1vaeKHYrSkXM4zbQFB%2BlI%2F93yRFC1O%2FlenGnsabrxgOLpWx%2B%2BQdP3rydjpIbEbsfgQ7r%2Ffl4K0SM3fmjCqnUBoiSJO2CXuwRw5H68oNLn1R1E7f7kYpB3xGKTczXeJLBbaIPr8pZXTX86RYh1v5IY%2F6ibUXXXKD3DfGQDQDmSqk5vH3Btb5U5qHcnH8YqgTcxj55b0LiI%2Fm51sae66GsZyDG%2BIQYC9cY5Imy0vUEsaqekoagLEkG76H6ahIyYvWXagANKLzfnMJCj4L0GOqUBzrsymcnh8FSDVvm3Y4xGcZLAxTLU0b016RuwnrVWQ2j6kAAJLkZWMtWrQopJ9K898tOI8vZP0DZavzIY8qcVS9ofo5knkEKo9UsYHrkYhvXrixAcCFh70ad8tWVvsG1m26lb2tckrUTJKPA3VkqfeXRCPRG3KHfWmID%2B%2BWPhTV0exy1%2F6yuRJCGwcwW1x9%2Fhsc5%2BXlyWQpPLCIq23WqVfO%2BZ6CG8&X-Amz-Signature=1c2fc081b9ebe2f33d8f49290e99242f9bb101b995175aa3766813280302b6c4&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WJ5FGREL%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T063318Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCIcpElDWWKDhxQOrqE9xuBGcj0ZrnTgKnfeptu32cPAwIgcS0nYUjbjAs8StGop21OctLgBkYfygj7dusBzlRQ1GYqiAQIz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOYC7GAeCoCR3pIYayrcA15uHJlVCTaTEAGS3Kn5bLmWVBxXTWU5TU98mv%2B6DA264u86fNCrQaEpSEt9fLr2YDC0uPfvBiLtU6lzYBzxeLokkoXzM5txo4RzSReK1X6U0EdiSwuNmt0HCYWBU9sIlMloHImbLHgben1TtdmzN20BIaYsBf1oL7XqS2jKE9FtXscBiW3a5h0lH3A4swvsbhVbGE4bnEkAZyqlYmWMemhm3Zl8TKhPG9s1OVE0XevJRHqrwhhqg7QElPzy3jrwHbDyFyPiU%2FBZnGi9skfIiL%2FImu%2Bjn96wxuT%2FXbBbQ14ocPkl1wbWtxDo10hY5odZkY5%2BJsocNqowJeF5p5tWpav%2BHGYQVJC1RN5Kt1FfaLQy%2Bya%2Bqrt1vaeKHYrSkXM4zbQFB%2BlI%2F93yRFC1O%2FlenGnsabrxgOLpWx%2B%2BQdP3rydjpIbEbsfgQ7r%2Ffl4K0SM3fmjCqnUBoiSJO2CXuwRw5H68oNLn1R1E7f7kYpB3xGKTczXeJLBbaIPr8pZXTX86RYh1v5IY%2F6ibUXXXKD3DfGQDQDmSqk5vH3Btb5U5qHcnH8YqgTcxj55b0LiI%2Fm51sae66GsZyDG%2BIQYC9cY5Imy0vUEsaqekoagLEkG76H6ahIyYvWXagANKLzfnMJCj4L0GOqUBzrsymcnh8FSDVvm3Y4xGcZLAxTLU0b016RuwnrVWQ2j6kAAJLkZWMtWrQopJ9K898tOI8vZP0DZavzIY8qcVS9ofo5knkEKo9UsYHrkYhvXrixAcCFh70ad8tWVvsG1m26lb2tckrUTJKPA3VkqfeXRCPRG3KHfWmID%2B%2BWPhTV0exy1%2F6yuRJCGwcwW1x9%2Fhsc5%2BXlyWQpPLCIq23WqVfO%2BZ6CG8&X-Amz-Signature=d804a532a1555424fc1b59d6211288927dc7e2d74f946e36c09ea8e48de7ef2d&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WJ5FGREL%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T063318Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCIcpElDWWKDhxQOrqE9xuBGcj0ZrnTgKnfeptu32cPAwIgcS0nYUjbjAs8StGop21OctLgBkYfygj7dusBzlRQ1GYqiAQIz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOYC7GAeCoCR3pIYayrcA15uHJlVCTaTEAGS3Kn5bLmWVBxXTWU5TU98mv%2B6DA264u86fNCrQaEpSEt9fLr2YDC0uPfvBiLtU6lzYBzxeLokkoXzM5txo4RzSReK1X6U0EdiSwuNmt0HCYWBU9sIlMloHImbLHgben1TtdmzN20BIaYsBf1oL7XqS2jKE9FtXscBiW3a5h0lH3A4swvsbhVbGE4bnEkAZyqlYmWMemhm3Zl8TKhPG9s1OVE0XevJRHqrwhhqg7QElPzy3jrwHbDyFyPiU%2FBZnGi9skfIiL%2FImu%2Bjn96wxuT%2FXbBbQ14ocPkl1wbWtxDo10hY5odZkY5%2BJsocNqowJeF5p5tWpav%2BHGYQVJC1RN5Kt1FfaLQy%2Bya%2Bqrt1vaeKHYrSkXM4zbQFB%2BlI%2F93yRFC1O%2FlenGnsabrxgOLpWx%2B%2BQdP3rydjpIbEbsfgQ7r%2Ffl4K0SM3fmjCqnUBoiSJO2CXuwRw5H68oNLn1R1E7f7kYpB3xGKTczXeJLBbaIPr8pZXTX86RYh1v5IY%2F6ibUXXXKD3DfGQDQDmSqk5vH3Btb5U5qHcnH8YqgTcxj55b0LiI%2Fm51sae66GsZyDG%2BIQYC9cY5Imy0vUEsaqekoagLEkG76H6ahIyYvWXagANKLzfnMJCj4L0GOqUBzrsymcnh8FSDVvm3Y4xGcZLAxTLU0b016RuwnrVWQ2j6kAAJLkZWMtWrQopJ9K898tOI8vZP0DZavzIY8qcVS9ofo5knkEKo9UsYHrkYhvXrixAcCFh70ad8tWVvsG1m26lb2tckrUTJKPA3VkqfeXRCPRG3KHfWmID%2B%2BWPhTV0exy1%2F6yuRJCGwcwW1x9%2Fhsc5%2BXlyWQpPLCIq23WqVfO%2BZ6CG8&X-Amz-Signature=d8c4c8ba0cd3ac79b8d52e792c05f64636d81d8e4edd1b86c267ac9ce5989979&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WJ5FGREL%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T063318Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCIcpElDWWKDhxQOrqE9xuBGcj0ZrnTgKnfeptu32cPAwIgcS0nYUjbjAs8StGop21OctLgBkYfygj7dusBzlRQ1GYqiAQIz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOYC7GAeCoCR3pIYayrcA15uHJlVCTaTEAGS3Kn5bLmWVBxXTWU5TU98mv%2B6DA264u86fNCrQaEpSEt9fLr2YDC0uPfvBiLtU6lzYBzxeLokkoXzM5txo4RzSReK1X6U0EdiSwuNmt0HCYWBU9sIlMloHImbLHgben1TtdmzN20BIaYsBf1oL7XqS2jKE9FtXscBiW3a5h0lH3A4swvsbhVbGE4bnEkAZyqlYmWMemhm3Zl8TKhPG9s1OVE0XevJRHqrwhhqg7QElPzy3jrwHbDyFyPiU%2FBZnGi9skfIiL%2FImu%2Bjn96wxuT%2FXbBbQ14ocPkl1wbWtxDo10hY5odZkY5%2BJsocNqowJeF5p5tWpav%2BHGYQVJC1RN5Kt1FfaLQy%2Bya%2Bqrt1vaeKHYrSkXM4zbQFB%2BlI%2F93yRFC1O%2FlenGnsabrxgOLpWx%2B%2BQdP3rydjpIbEbsfgQ7r%2Ffl4K0SM3fmjCqnUBoiSJO2CXuwRw5H68oNLn1R1E7f7kYpB3xGKTczXeJLBbaIPr8pZXTX86RYh1v5IY%2F6ibUXXXKD3DfGQDQDmSqk5vH3Btb5U5qHcnH8YqgTcxj55b0LiI%2Fm51sae66GsZyDG%2BIQYC9cY5Imy0vUEsaqekoagLEkG76H6ahIyYvWXagANKLzfnMJCj4L0GOqUBzrsymcnh8FSDVvm3Y4xGcZLAxTLU0b016RuwnrVWQ2j6kAAJLkZWMtWrQopJ9K898tOI8vZP0DZavzIY8qcVS9ofo5knkEKo9UsYHrkYhvXrixAcCFh70ad8tWVvsG1m26lb2tckrUTJKPA3VkqfeXRCPRG3KHfWmID%2B%2BWPhTV0exy1%2F6yuRJCGwcwW1x9%2Fhsc5%2BXlyWQpPLCIq23WqVfO%2BZ6CG8&X-Amz-Signature=53b94ac31fd94559c9e93f3c93924df1d9637d118145823661732b77977c5e97&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WJ5FGREL%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T063318Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCIcpElDWWKDhxQOrqE9xuBGcj0ZrnTgKnfeptu32cPAwIgcS0nYUjbjAs8StGop21OctLgBkYfygj7dusBzlRQ1GYqiAQIz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOYC7GAeCoCR3pIYayrcA15uHJlVCTaTEAGS3Kn5bLmWVBxXTWU5TU98mv%2B6DA264u86fNCrQaEpSEt9fLr2YDC0uPfvBiLtU6lzYBzxeLokkoXzM5txo4RzSReK1X6U0EdiSwuNmt0HCYWBU9sIlMloHImbLHgben1TtdmzN20BIaYsBf1oL7XqS2jKE9FtXscBiW3a5h0lH3A4swvsbhVbGE4bnEkAZyqlYmWMemhm3Zl8TKhPG9s1OVE0XevJRHqrwhhqg7QElPzy3jrwHbDyFyPiU%2FBZnGi9skfIiL%2FImu%2Bjn96wxuT%2FXbBbQ14ocPkl1wbWtxDo10hY5odZkY5%2BJsocNqowJeF5p5tWpav%2BHGYQVJC1RN5Kt1FfaLQy%2Bya%2Bqrt1vaeKHYrSkXM4zbQFB%2BlI%2F93yRFC1O%2FlenGnsabrxgOLpWx%2B%2BQdP3rydjpIbEbsfgQ7r%2Ffl4K0SM3fmjCqnUBoiSJO2CXuwRw5H68oNLn1R1E7f7kYpB3xGKTczXeJLBbaIPr8pZXTX86RYh1v5IY%2F6ibUXXXKD3DfGQDQDmSqk5vH3Btb5U5qHcnH8YqgTcxj55b0LiI%2Fm51sae66GsZyDG%2BIQYC9cY5Imy0vUEsaqekoagLEkG76H6ahIyYvWXagANKLzfnMJCj4L0GOqUBzrsymcnh8FSDVvm3Y4xGcZLAxTLU0b016RuwnrVWQ2j6kAAJLkZWMtWrQopJ9K898tOI8vZP0DZavzIY8qcVS9ofo5knkEKo9UsYHrkYhvXrixAcCFh70ad8tWVvsG1m26lb2tckrUTJKPA3VkqfeXRCPRG3KHfWmID%2B%2BWPhTV0exy1%2F6yuRJCGwcwW1x9%2Fhsc5%2BXlyWQpPLCIq23WqVfO%2BZ6CG8&X-Amz-Signature=27bb6fb239fec484e3bec045238c700f622da5899cc8793ec21b43f604a82234&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666VTU6BLD%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T063318Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBk4rxus5ySJMyThloemeNViUpNQukbd9vusxFoqaT6YAiEAyVNfrV5%2FlkMDPtYU%2Bq9Zv8qOP89XG%2FH%2FbHM7mrJYeTAqiAQIz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMXr%2BG2Ptqpw2gRMtircA1Gx0yQiN5oDcHCLrRFp9ogigMnKdVtDcksKDAHWM%2BqpUsnf7jZl2Oesu0ADv1%2BTgiEZzvXYqnNokZihLUITOhU2G6he%2BUqHdlK6O4iwbcJfymz1E0QBUzL6k%2FojGkq8qkU2EQFU46TMjdPUXA1d%2FJ7xW8XXJbND0EejNN6wQYn98eVQBYF60r5WV%2BiDhm0bgcmFzRVdG%2BW%2B76pxkSDmwKa5bbB9gefVUTrKn62VeKXpkAuztUay%2BudcIoQA33D8S0ChfB7TJl0aHLpAEt235NvgUN6uw6ZBxAeUPRQ93ZDvKjnGf2VpNq%2FjpSxZoJsvqz25jLIW2flRgp4OfPA%2FDgLDUTEnKVRy%2B08KbcYN%2Bj7PvpAKEkK2Bb%2F%2BKv4SKS4W4XxNt4c8MLyjWGqluKY%2B827lQt90Qd1bMoFcsIHsRDYmAhHjt0f0K3E59D18%2FbZSv%2FBONOCDAVQSwRqZupFOeBitRvb0mXOIzj8khYy6PA7bVXKSYXxKufljYRHJJdQr%2FXhBEH0sMf5KSDw5SgvKmg4D5vEcO9IoVHl33y5vSWJNKBRKpfqif6UEPDMDgbpOlDLTh9M1mGv15zlCgOea6TwVCCqU3rswq7oJZgPslz%2FmqIufJVsTjp9agdJNMOqi4L0GOqUBPzL%2BNtJ0SObVVdDKpejmOqC8%2B3Sv2taL4RPDO2jtZxqlE3JtAKJBcaQQiIelIvDg7EiE7QiRZrU2riZZN4MPn6uNfFOye5O%2BFy%2FEn6YRpA1yvxCcD%2Bap4HbbxexX%2BEtoGQW9K0lMbQrfCx1REU9SJjjavVWmrp8Rnlyjgxr0AiA9qz4xFHM0TRTCAImYDJ0R8eKS6wnHudriJvMQyhpiWd8KBSKY&X-Amz-Signature=4031233f376f29672b048a33a35b81083e32758924d9d344e262330ecd9d215e&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YVC7SVGG%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T063319Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIB%2BGJtNVA7B6731zPlY%2F4RuJuz8BXUWYED82Q5LPtMvOAiEAigWoJdBw4bz9vkp4uIJPch%2BXMCYI8rabSKeeRHJhx5EqiAQIz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCsj1jxTOJvooIBBUSrcA6c4lqHOybXwfmv7nSuOWiLEWjFPsSo0kHbTYGJoYIWq9e3aNbFWug%2Bap7bw3w7HYai9eQFDCJipY%2F7L7Vv2foJKQiGXLixtY%2FxuajEAm3PpAiq5e9dqzUtoIrvexrOlGUfJ7PKRa8lZqmZQbZskUBLNv3yJhqpF3TuWy8Hi0gB2cRCHAORy9jzZmn9UtfjWK9Hgc2jhvfMiktR%2BmwwqK3ifF2j9dNg4BOZKjdnGmwxw9HgL4W5Zke%2F9Yf1kJ60qgzdtA4NcmhWzuW20xqdYFQ3iQn%2BfW9bqtB7yd9Z1f36RTHL3xzzH4npo5s%2FviHsSi3DbGnnuAFdE3JCgP5rRoRc3GrYsQqxQhiXkTPInz6u8pdFCNh425yASn84HgitZsx5DEMxHqNhVIV0WJjPUVWnqEicPMIq1FNBAkDdunfS3bpDLXLz6XafY3ZalzRx5IMjr675tgFMWynuyXYghpR9NeO%2BCqSiGK7V611tzft0KvnwdWl4%2Fbn2Q%2FNzwStpoqpQur3UVESBP69dwKZTmi6br%2FXXeBwcjMGFYYfUia6qR5sykoCDMJYWMbVTIv%2BvXzs1aTuSmQMsrMw2FOlcwNjjSfWaCM9NlR87Fxz3YAnizAmm8z3cDpXruSeTPMIuj4L0GOqUBkigv6La6GqmLnrox7GRW1hcTl3lu8aAvFQVbPuRAlx5DNCU0MQg4gpMmKYwmS5Jp%2Bd5NWYqgsiFsd%2BPCNSzQ3rvkf%2B463k8nZEvRud%2FjaT9Xnt0QU1LQqdMnOwzqCd%2FOGxOx9OUln9ZQHQOxgUe67ZW2ST76CB%2BsnztcSe7H1gKRr8ZFEe132FAYJXUpmua4LihXkdb3RDYheV2sUqEl2OTDqxPf&X-Amz-Signature=675de3dd1c44aceaf1406be97f36980eb9efbde4229de60dc6b097d89777044a&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WJ5FGREL%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T063318Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCIcpElDWWKDhxQOrqE9xuBGcj0ZrnTgKnfeptu32cPAwIgcS0nYUjbjAs8StGop21OctLgBkYfygj7dusBzlRQ1GYqiAQIz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOYC7GAeCoCR3pIYayrcA15uHJlVCTaTEAGS3Kn5bLmWVBxXTWU5TU98mv%2B6DA264u86fNCrQaEpSEt9fLr2YDC0uPfvBiLtU6lzYBzxeLokkoXzM5txo4RzSReK1X6U0EdiSwuNmt0HCYWBU9sIlMloHImbLHgben1TtdmzN20BIaYsBf1oL7XqS2jKE9FtXscBiW3a5h0lH3A4swvsbhVbGE4bnEkAZyqlYmWMemhm3Zl8TKhPG9s1OVE0XevJRHqrwhhqg7QElPzy3jrwHbDyFyPiU%2FBZnGi9skfIiL%2FImu%2Bjn96wxuT%2FXbBbQ14ocPkl1wbWtxDo10hY5odZkY5%2BJsocNqowJeF5p5tWpav%2BHGYQVJC1RN5Kt1FfaLQy%2Bya%2Bqrt1vaeKHYrSkXM4zbQFB%2BlI%2F93yRFC1O%2FlenGnsabrxgOLpWx%2B%2BQdP3rydjpIbEbsfgQ7r%2Ffl4K0SM3fmjCqnUBoiSJO2CXuwRw5H68oNLn1R1E7f7kYpB3xGKTczXeJLBbaIPr8pZXTX86RYh1v5IY%2F6ibUXXXKD3DfGQDQDmSqk5vH3Btb5U5qHcnH8YqgTcxj55b0LiI%2Fm51sae66GsZyDG%2BIQYC9cY5Imy0vUEsaqekoagLEkG76H6ahIyYvWXagANKLzfnMJCj4L0GOqUBzrsymcnh8FSDVvm3Y4xGcZLAxTLU0b016RuwnrVWQ2j6kAAJLkZWMtWrQopJ9K898tOI8vZP0DZavzIY8qcVS9ofo5knkEKo9UsYHrkYhvXrixAcCFh70ad8tWVvsG1m26lb2tckrUTJKPA3VkqfeXRCPRG3KHfWmID%2B%2BWPhTV0exy1%2F6yuRJCGwcwW1x9%2Fhsc5%2BXlyWQpPLCIq23WqVfO%2BZ6CG8&X-Amz-Signature=9dbd121241c5ff5a375ca14f30e768a6333594dd1932c864fe7f520c851b6fe7&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WJ5FGREL%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T063318Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCIcpElDWWKDhxQOrqE9xuBGcj0ZrnTgKnfeptu32cPAwIgcS0nYUjbjAs8StGop21OctLgBkYfygj7dusBzlRQ1GYqiAQIz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOYC7GAeCoCR3pIYayrcA15uHJlVCTaTEAGS3Kn5bLmWVBxXTWU5TU98mv%2B6DA264u86fNCrQaEpSEt9fLr2YDC0uPfvBiLtU6lzYBzxeLokkoXzM5txo4RzSReK1X6U0EdiSwuNmt0HCYWBU9sIlMloHImbLHgben1TtdmzN20BIaYsBf1oL7XqS2jKE9FtXscBiW3a5h0lH3A4swvsbhVbGE4bnEkAZyqlYmWMemhm3Zl8TKhPG9s1OVE0XevJRHqrwhhqg7QElPzy3jrwHbDyFyPiU%2FBZnGi9skfIiL%2FImu%2Bjn96wxuT%2FXbBbQ14ocPkl1wbWtxDo10hY5odZkY5%2BJsocNqowJeF5p5tWpav%2BHGYQVJC1RN5Kt1FfaLQy%2Bya%2Bqrt1vaeKHYrSkXM4zbQFB%2BlI%2F93yRFC1O%2FlenGnsabrxgOLpWx%2B%2BQdP3rydjpIbEbsfgQ7r%2Ffl4K0SM3fmjCqnUBoiSJO2CXuwRw5H68oNLn1R1E7f7kYpB3xGKTczXeJLBbaIPr8pZXTX86RYh1v5IY%2F6ibUXXXKD3DfGQDQDmSqk5vH3Btb5U5qHcnH8YqgTcxj55b0LiI%2Fm51sae66GsZyDG%2BIQYC9cY5Imy0vUEsaqekoagLEkG76H6ahIyYvWXagANKLzfnMJCj4L0GOqUBzrsymcnh8FSDVvm3Y4xGcZLAxTLU0b016RuwnrVWQ2j6kAAJLkZWMtWrQopJ9K898tOI8vZP0DZavzIY8qcVS9ofo5knkEKo9UsYHrkYhvXrixAcCFh70ad8tWVvsG1m26lb2tckrUTJKPA3VkqfeXRCPRG3KHfWmID%2B%2BWPhTV0exy1%2F6yuRJCGwcwW1x9%2Fhsc5%2BXlyWQpPLCIq23WqVfO%2BZ6CG8&X-Amz-Signature=7ca401914301da54c03e2638434fe4f6e764960e09a31e26046f9c00e6687e2c&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WJ5FGREL%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T063318Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCIcpElDWWKDhxQOrqE9xuBGcj0ZrnTgKnfeptu32cPAwIgcS0nYUjbjAs8StGop21OctLgBkYfygj7dusBzlRQ1GYqiAQIz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOYC7GAeCoCR3pIYayrcA15uHJlVCTaTEAGS3Kn5bLmWVBxXTWU5TU98mv%2B6DA264u86fNCrQaEpSEt9fLr2YDC0uPfvBiLtU6lzYBzxeLokkoXzM5txo4RzSReK1X6U0EdiSwuNmt0HCYWBU9sIlMloHImbLHgben1TtdmzN20BIaYsBf1oL7XqS2jKE9FtXscBiW3a5h0lH3A4swvsbhVbGE4bnEkAZyqlYmWMemhm3Zl8TKhPG9s1OVE0XevJRHqrwhhqg7QElPzy3jrwHbDyFyPiU%2FBZnGi9skfIiL%2FImu%2Bjn96wxuT%2FXbBbQ14ocPkl1wbWtxDo10hY5odZkY5%2BJsocNqowJeF5p5tWpav%2BHGYQVJC1RN5Kt1FfaLQy%2Bya%2Bqrt1vaeKHYrSkXM4zbQFB%2BlI%2F93yRFC1O%2FlenGnsabrxgOLpWx%2B%2BQdP3rydjpIbEbsfgQ7r%2Ffl4K0SM3fmjCqnUBoiSJO2CXuwRw5H68oNLn1R1E7f7kYpB3xGKTczXeJLBbaIPr8pZXTX86RYh1v5IY%2F6ibUXXXKD3DfGQDQDmSqk5vH3Btb5U5qHcnH8YqgTcxj55b0LiI%2Fm51sae66GsZyDG%2BIQYC9cY5Imy0vUEsaqekoagLEkG76H6ahIyYvWXagANKLzfnMJCj4L0GOqUBzrsymcnh8FSDVvm3Y4xGcZLAxTLU0b016RuwnrVWQ2j6kAAJLkZWMtWrQopJ9K898tOI8vZP0DZavzIY8qcVS9ofo5knkEKo9UsYHrkYhvXrixAcCFh70ad8tWVvsG1m26lb2tckrUTJKPA3VkqfeXRCPRG3KHfWmID%2B%2BWPhTV0exy1%2F6yuRJCGwcwW1x9%2Fhsc5%2BXlyWQpPLCIq23WqVfO%2BZ6CG8&X-Amz-Signature=d8511a9a3ec488c542c228bc5ccb5bb0ea0fb51cc05102645c704653e1d9600d&X-Amz-SignedHeaders=host&x-id=GetObject)


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

