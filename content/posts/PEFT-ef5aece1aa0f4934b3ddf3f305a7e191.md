---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466QAA3M7SS%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250213T152640Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCn8iiAGpioY6zZVU9\
  8pj5VeI2DYe0g9Bc%2FY8IufDR5BwIgIO06pGz89Cyd7yQF%2FdGciz6vFJe1gOk6R5SN8Saun7gq\
  %2FwMIFhAAGgw2Mzc0MjMxODM4MDUiDDRGTQyg02NIDKT8BCrcA9SKGsosqzDYMbbTxHnx88ZY7MX\
  5QVXHc7j7117O1uBFEmxY4g%2BgsL%2BqNb0Mz9Tr3McNl1hmIgDMegl72OcywcgXUMcYBKpGcXtX\
  R6Ge9M5cg49AZtx7Y4tBrw8cWBVEzNDS6fU1IZuG64b7EV3HvBBvkAoX2mH1mh4EoyJhKiTRRNkgD\
  aLmZz20qdLtcF4hsEwdejswgBycMx3mn8iQ4%2BgBjRpmPJqtVYO1uVQA%2B%2FGZuLqEoTBcPdZR\
  zm5BiVRcWDWcVQTYekjtnF2q4SbvM2Y8KuFv22J1qqyJbZ5oX71x9pARHN1GP7dltlCqYy5%2Boik\
  RKhdEGQlXI97oyEvKgXQYvZ3VwrUo9Pn6VJkhZlpoq3Aa%2BEk4xdgJAuZgD9kgmo5Xhq5N%2BICu\
  9cezpwwLKgSwDVTrP3nOVIg77m7dSOI%2Bs%2FSgxBszElKkQ8TS%2BmKZNDzs%2FXBYiCuSQYMfw\
  rXjgIhRuIo5GNjPHYj38omc2adWnzR1bX0JTsQPgf571z6m8eou7MBMKUEhMCgwpLAiG%2BP71818\
  32Xp0wjDqKDewZPlopKxIDdrg59rqs2tCQ5jiDSqHgKmih%2FYHDi%2Fs4P5GwVubhZZUsZFp1Dqn\
  cF133K2OcSUVTyC%2FgF2o20fMK7dt70GOqUBFNr5gR%2FzythR7D1VxS8BxDqFVmsu6L%2F9N0X8\
  GqZcYv8csaM%2BO4SHv30341%2BJUw0w19EtR097sCAC1WJOQl2x5PRjggqCbLFmIJiiy%2BblAZE\
  YnlJ3rGoTz2bwNWgqowTaO5L3DWQ8gPTNlkrr0HnYY1vFxSwlWUB2laxYJFpvSKYhyKePlsIe5xMS\
  S1kzBp%2BA88vc1KKaJnt270BMv50VGOZTBcgp&X-Amz-Signature=fa2ae71c904e967dc900f6\
  40be318d9561d69fc2ac32a03c0e24505d7eb2ab0d&X-Amz-SignedHeaders=host&x-id=GetO\
  bject"
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
        redential=ASIAZI2LB466YAWEMTYG%2F20250213%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250213T152444Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIQDVwqW%2BC%2BKyqhcSExUsGsh5OQu4INjfp5XfYPRF1lutkQIgKoyaSrXdOaYtxllW%2\
        B2CosDi0Vw7Gccyqd74WHXQ%2Bulkq%2FwMIFhAAGgw2Mzc0MjMxODM4MDUiDPneTGn13zW\
        3zqhhFSrcA2RAHDsDtXw1YHXCB6LmKh6BznzcvnTeDyPXfnTcxo9HqibzC50udN%2Byc%2B\
        p7yPaULgIQK7pULsbAkjmG2l7YWpxnrA8Gv8PUtAzxTdTI8Do%2B1s63qHSfK9oUXdrlROF\
        m%2FChvEM48RLqzf3Wo1garM1KO%2FCJum0mvYYqw30UEelPF55PvFV9Bo5JIzZjUDPCi0l\
        FJgWxI4bP3AlUi%2BAvnWfQGygCrxfAJ7ijuXNCF3pEbT1vK3Y%2FXnJPTfLx%2FSG%2F5v\
        XF9et2E%2BUjlGRTIx5xOkSZdsRIjOqTbID6T8OJkNIEwXuGFs6cpO5UEbm0ZukbVu6Vdpf\
        O6d9G0WnhxeX25q9q1UEKpHtKpQx8Be3wAGGYV5%2FJnZQrPPtX9mZ41NZFcpCYiL2PJWR4\
        34OwK1z%2FhhNtMEfH1i6ZzvDQ%2F%2Bze2aTEYduLfE5ZpW7wx%2BMCdxE0L1CFzcsWbKA\
        4MJewTBdwscCe%2F%2BEZb2IglTOucDNg336Ga63JEdRCvRSF5ZDB3bZM4jLJWMDCs4vv1T\
        gL8kdeLRwta2N8MEtVVAL9XlcozTa160%2F63753ZciY22dU2ANYBu2M19yaB%2FwoB1aGX\
        Vl7BaKWoZcm%2Ba2MkypcLSt%2BK0SBIEiq5kq8YSdfeEsTIMLPdt70GOqUBHxocD4h%2FO\
        RAE%2FRctylbdsZyMQISHAknPuL7s9KQCP5IZF4%2FztG7BQf3dGRrHVH1MyaRiyZfeoT2D\
        RDc%2Bii9dReZJDPtL43Of47yUVgoVvHiL%2BxV8JKzYH4C5piFxvbDOMLPpMITYtv0y6CL\
        VNu0YfEF%2FIUW%2BG%2Bfemjf7KNAM9VzHoWUOHsa9Q0g%2B%2BqOr9kqyMCp9c2M20qPO\
        dmcLX3mx04M6RMrF&X-Amz-Signature=8891f422df389fb1c9a2d176ccf9dda5853184\
        dac913c033a0afaf755cf70146&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-13T16:24:44.419Z"
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
UPDATE_TIME: "2025-02-13T15:26:45.271Z"
EXPIRY_TIME: "2025-02-13T16:26:38.421Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZXZ5TW73%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T152638Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCBUiFNhPSoodIDSeBEoshSGCZe9csNNrnq5HDOd0%2BY9gIgau8wYnAbg7Yno6JGcykJmnBWoZPMkEA30U4fLeo7HQcq%2FwMIFhAAGgw2Mzc0MjMxODM4MDUiDBLLJcpB3n7g25gCGircA1opS%2BhOYGMDd%2FFNoTnb7qyL9XkPTgkoghZGh8TmFGeX4AqbCB7MnLCuXSTwgs1OAM%2BfA%2Bot2e7YkfYwbKm3w3fkRULRkWRJ%2BNQRIw3flbBB00m8I%2FXR0xBvDu7VMSyindBeITw1fkbx4K4%2BxgunTd%2BudGdEc%2BOvnl0ZqIOV7vSS8dldzIrePDk5w58tjhgc1ZMJM5E6OxjglN69jNb%2B7hKV15%2FO1S1wyQL0RZwVJ5w%2FtxQomzqQ6yzN1Y%2Fts%2FZrEFoqS4FdYJ8vVr0l8nBbBcMXo6MVmjjtTgBOWEHSCVNxrd5rSr4%2BDiRS9ZiWSIMY%2F4nkWlXS8125Wea0vk4o5C73wy8Z21WSZ1pNL1VkQLi5HlSaI5bMnnlR38N3YSMemw0rBYOA6ZxFSRDSiFbCGyHHOceCMpCmAYRsaG08O0H%2B%2FZSGZDUa6AYPNk1VWY40xaYlfEnJPWkEpQgb1owHzjjpFgcu81IXQ5wsTsjktqZAqVHGPjyBRzD1i13czOBznpF%2BH2ThaMsDo4%2FbJJofV6hEP10jJogAZN4wmfvxsYFJ3Lj261vUU3W9r8dWE8CIx%2FIYLI7CITGVHCXzYo6h4DgOHozPDnAKuXZjvCql1JsEV9e6GlS46SNKkqNcMILet70GOqUBOb2UIsBcUe9nsgf8VRWx8Yhn0OJEs88Il%2FAwKBcfEtvlfCxPk2bc16fQu2X1sqOkF9utXHmFVYRFyy7nE6fT17p5BBggqnW55hOHVfRO7TBXtjayRBqOTjw2lHrQGbteiv1iOwyi2OntInwnjP%2BW%2B1me%2B0%2BaKV3fY7%2FDr2S%2B7MGiwaTalIYS8fhr%2F3FeU9mlxx2W19BlDA7uCMA2Y3XICwWt4bGq&X-Amz-Signature=a5ba981ddde7b693166cc820490d0afc21b03d76d4e94c6a78446329b2988dc5&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZXZ5TW73%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T152638Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCBUiFNhPSoodIDSeBEoshSGCZe9csNNrnq5HDOd0%2BY9gIgau8wYnAbg7Yno6JGcykJmnBWoZPMkEA30U4fLeo7HQcq%2FwMIFhAAGgw2Mzc0MjMxODM4MDUiDBLLJcpB3n7g25gCGircA1opS%2BhOYGMDd%2FFNoTnb7qyL9XkPTgkoghZGh8TmFGeX4AqbCB7MnLCuXSTwgs1OAM%2BfA%2Bot2e7YkfYwbKm3w3fkRULRkWRJ%2BNQRIw3flbBB00m8I%2FXR0xBvDu7VMSyindBeITw1fkbx4K4%2BxgunTd%2BudGdEc%2BOvnl0ZqIOV7vSS8dldzIrePDk5w58tjhgc1ZMJM5E6OxjglN69jNb%2B7hKV15%2FO1S1wyQL0RZwVJ5w%2FtxQomzqQ6yzN1Y%2Fts%2FZrEFoqS4FdYJ8vVr0l8nBbBcMXo6MVmjjtTgBOWEHSCVNxrd5rSr4%2BDiRS9ZiWSIMY%2F4nkWlXS8125Wea0vk4o5C73wy8Z21WSZ1pNL1VkQLi5HlSaI5bMnnlR38N3YSMemw0rBYOA6ZxFSRDSiFbCGyHHOceCMpCmAYRsaG08O0H%2B%2FZSGZDUa6AYPNk1VWY40xaYlfEnJPWkEpQgb1owHzjjpFgcu81IXQ5wsTsjktqZAqVHGPjyBRzD1i13czOBznpF%2BH2ThaMsDo4%2FbJJofV6hEP10jJogAZN4wmfvxsYFJ3Lj261vUU3W9r8dWE8CIx%2FIYLI7CITGVHCXzYo6h4DgOHozPDnAKuXZjvCql1JsEV9e6GlS46SNKkqNcMILet70GOqUBOb2UIsBcUe9nsgf8VRWx8Yhn0OJEs88Il%2FAwKBcfEtvlfCxPk2bc16fQu2X1sqOkF9utXHmFVYRFyy7nE6fT17p5BBggqnW55hOHVfRO7TBXtjayRBqOTjw2lHrQGbteiv1iOwyi2OntInwnjP%2BW%2B1me%2B0%2BaKV3fY7%2FDr2S%2B7MGiwaTalIYS8fhr%2F3FeU9mlxx2W19BlDA7uCMA2Y3XICwWt4bGq&X-Amz-Signature=01bc8ad93667799e3292c8cecd0e8c71a13dbe47206c0f87cc5bf7ca8fef3736&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZXZ5TW73%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T152638Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCBUiFNhPSoodIDSeBEoshSGCZe9csNNrnq5HDOd0%2BY9gIgau8wYnAbg7Yno6JGcykJmnBWoZPMkEA30U4fLeo7HQcq%2FwMIFhAAGgw2Mzc0MjMxODM4MDUiDBLLJcpB3n7g25gCGircA1opS%2BhOYGMDd%2FFNoTnb7qyL9XkPTgkoghZGh8TmFGeX4AqbCB7MnLCuXSTwgs1OAM%2BfA%2Bot2e7YkfYwbKm3w3fkRULRkWRJ%2BNQRIw3flbBB00m8I%2FXR0xBvDu7VMSyindBeITw1fkbx4K4%2BxgunTd%2BudGdEc%2BOvnl0ZqIOV7vSS8dldzIrePDk5w58tjhgc1ZMJM5E6OxjglN69jNb%2B7hKV15%2FO1S1wyQL0RZwVJ5w%2FtxQomzqQ6yzN1Y%2Fts%2FZrEFoqS4FdYJ8vVr0l8nBbBcMXo6MVmjjtTgBOWEHSCVNxrd5rSr4%2BDiRS9ZiWSIMY%2F4nkWlXS8125Wea0vk4o5C73wy8Z21WSZ1pNL1VkQLi5HlSaI5bMnnlR38N3YSMemw0rBYOA6ZxFSRDSiFbCGyHHOceCMpCmAYRsaG08O0H%2B%2FZSGZDUa6AYPNk1VWY40xaYlfEnJPWkEpQgb1owHzjjpFgcu81IXQ5wsTsjktqZAqVHGPjyBRzD1i13czOBznpF%2BH2ThaMsDo4%2FbJJofV6hEP10jJogAZN4wmfvxsYFJ3Lj261vUU3W9r8dWE8CIx%2FIYLI7CITGVHCXzYo6h4DgOHozPDnAKuXZjvCql1JsEV9e6GlS46SNKkqNcMILet70GOqUBOb2UIsBcUe9nsgf8VRWx8Yhn0OJEs88Il%2FAwKBcfEtvlfCxPk2bc16fQu2X1sqOkF9utXHmFVYRFyy7nE6fT17p5BBggqnW55hOHVfRO7TBXtjayRBqOTjw2lHrQGbteiv1iOwyi2OntInwnjP%2BW%2B1me%2B0%2BaKV3fY7%2FDr2S%2B7MGiwaTalIYS8fhr%2F3FeU9mlxx2W19BlDA7uCMA2Y3XICwWt4bGq&X-Amz-Signature=b13eb552d4696c6e0cf985d5a8e3b5f6559264e6ab757f43281b54beb4d52017&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZXZ5TW73%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T152638Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCBUiFNhPSoodIDSeBEoshSGCZe9csNNrnq5HDOd0%2BY9gIgau8wYnAbg7Yno6JGcykJmnBWoZPMkEA30U4fLeo7HQcq%2FwMIFhAAGgw2Mzc0MjMxODM4MDUiDBLLJcpB3n7g25gCGircA1opS%2BhOYGMDd%2FFNoTnb7qyL9XkPTgkoghZGh8TmFGeX4AqbCB7MnLCuXSTwgs1OAM%2BfA%2Bot2e7YkfYwbKm3w3fkRULRkWRJ%2BNQRIw3flbBB00m8I%2FXR0xBvDu7VMSyindBeITw1fkbx4K4%2BxgunTd%2BudGdEc%2BOvnl0ZqIOV7vSS8dldzIrePDk5w58tjhgc1ZMJM5E6OxjglN69jNb%2B7hKV15%2FO1S1wyQL0RZwVJ5w%2FtxQomzqQ6yzN1Y%2Fts%2FZrEFoqS4FdYJ8vVr0l8nBbBcMXo6MVmjjtTgBOWEHSCVNxrd5rSr4%2BDiRS9ZiWSIMY%2F4nkWlXS8125Wea0vk4o5C73wy8Z21WSZ1pNL1VkQLi5HlSaI5bMnnlR38N3YSMemw0rBYOA6ZxFSRDSiFbCGyHHOceCMpCmAYRsaG08O0H%2B%2FZSGZDUa6AYPNk1VWY40xaYlfEnJPWkEpQgb1owHzjjpFgcu81IXQ5wsTsjktqZAqVHGPjyBRzD1i13czOBznpF%2BH2ThaMsDo4%2FbJJofV6hEP10jJogAZN4wmfvxsYFJ3Lj261vUU3W9r8dWE8CIx%2FIYLI7CITGVHCXzYo6h4DgOHozPDnAKuXZjvCql1JsEV9e6GlS46SNKkqNcMILet70GOqUBOb2UIsBcUe9nsgf8VRWx8Yhn0OJEs88Il%2FAwKBcfEtvlfCxPk2bc16fQu2X1sqOkF9utXHmFVYRFyy7nE6fT17p5BBggqnW55hOHVfRO7TBXtjayRBqOTjw2lHrQGbteiv1iOwyi2OntInwnjP%2BW%2B1me%2B0%2BaKV3fY7%2FDr2S%2B7MGiwaTalIYS8fhr%2F3FeU9mlxx2W19BlDA7uCMA2Y3XICwWt4bGq&X-Amz-Signature=6a8d609f6bd837e9ff77c1cba54d869614f73097f526d53881eab9798dd8d635&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZXZ5TW73%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T152638Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCBUiFNhPSoodIDSeBEoshSGCZe9csNNrnq5HDOd0%2BY9gIgau8wYnAbg7Yno6JGcykJmnBWoZPMkEA30U4fLeo7HQcq%2FwMIFhAAGgw2Mzc0MjMxODM4MDUiDBLLJcpB3n7g25gCGircA1opS%2BhOYGMDd%2FFNoTnb7qyL9XkPTgkoghZGh8TmFGeX4AqbCB7MnLCuXSTwgs1OAM%2BfA%2Bot2e7YkfYwbKm3w3fkRULRkWRJ%2BNQRIw3flbBB00m8I%2FXR0xBvDu7VMSyindBeITw1fkbx4K4%2BxgunTd%2BudGdEc%2BOvnl0ZqIOV7vSS8dldzIrePDk5w58tjhgc1ZMJM5E6OxjglN69jNb%2B7hKV15%2FO1S1wyQL0RZwVJ5w%2FtxQomzqQ6yzN1Y%2Fts%2FZrEFoqS4FdYJ8vVr0l8nBbBcMXo6MVmjjtTgBOWEHSCVNxrd5rSr4%2BDiRS9ZiWSIMY%2F4nkWlXS8125Wea0vk4o5C73wy8Z21WSZ1pNL1VkQLi5HlSaI5bMnnlR38N3YSMemw0rBYOA6ZxFSRDSiFbCGyHHOceCMpCmAYRsaG08O0H%2B%2FZSGZDUa6AYPNk1VWY40xaYlfEnJPWkEpQgb1owHzjjpFgcu81IXQ5wsTsjktqZAqVHGPjyBRzD1i13czOBznpF%2BH2ThaMsDo4%2FbJJofV6hEP10jJogAZN4wmfvxsYFJ3Lj261vUU3W9r8dWE8CIx%2FIYLI7CITGVHCXzYo6h4DgOHozPDnAKuXZjvCql1JsEV9e6GlS46SNKkqNcMILet70GOqUBOb2UIsBcUe9nsgf8VRWx8Yhn0OJEs88Il%2FAwKBcfEtvlfCxPk2bc16fQu2X1sqOkF9utXHmFVYRFyy7nE6fT17p5BBggqnW55hOHVfRO7TBXtjayRBqOTjw2lHrQGbteiv1iOwyi2OntInwnjP%2BW%2B1me%2B0%2BaKV3fY7%2FDr2S%2B7MGiwaTalIYS8fhr%2F3FeU9mlxx2W19BlDA7uCMA2Y3XICwWt4bGq&X-Amz-Signature=ed5502449be0c6d81b8ae7819dc763b6d9fc2e3ee91354f3e9dda19f40815586&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Y7JXQ44N%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T152639Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIDyMLCJpcRmIBLZ761sWJAh6Oj83jqK7nSYBGVNsikC%2BAiBogvrIs%2FBXHCUhb0RfxsWuLBqNY%2Bux4BGSMg%2FNE01Vlyr%2FAwgWEAAaDDYzNzQyMzE4MzgwNSIM1oL3SJQVJf545Dd3KtwDbBnojw%2B5nNtQ8K61VJyV6TV6L79izQJtGJca30Tl4Kfxv%2BP7NHaPHYDku376HLzH%2FCb4LbA%2B85LdmnlvjVegx%2Bk%2BZIs6DY%2FHpwAULEjwsocQHdDfAWFZ00eAprr2SGWiwpbMAo5qlUBVH%2Fd2raKCbExHwvNQEvf5xmxV41tTtGhXHKK9JKYMuCK3mx8zef8irRE59HmZtlIeUVUXESGQg3pBrJjoaNsorVfd1n7VYBWMMhW%2BcX%2F8%2BPSbAKfvAxSS6nwidqEESmhMkx%2FHgkTK%2F1N6Tc5LgQmpddBWkDklIViEVw18hLp159CYu3IHj78RYjpGGbMHu%2BA2VzE9LBmr5mw4wx5EBr2NloPNBNMaEzaEIh07AKJ448E3LlEpUNnjX9p5omj3RKMr0FG9JQ824XMdE80aNtkKA%2B%2FEuSYkN8P6BgYHqQhByjIqpPzKKz2WDVw3dsxqtKgra7%2B1RsooreykkQ0PuIT%2BGTF0lzl%2BpMb7z1ERZW33ka8tpVhK0X0JV8NhKtu2bQNEQMOKcYO4sdLzrphJIxlpuWUgtvmuCo9nWrwpSXKdwPuVTrKMC6G9YynlpfRQk9kKzSILgY4gxoAxFip9SAfRfeqg9BY0tbPYTBtOrHT3Bux6gtgwwd23vQY6pgFYeA40h%2BMCr83YyRxeif6FHzk4LAOo0eR9nTCNYJkOJzydGnJB7Mn7nU0ib%2Bb7jmYbppOFk8ZQD2j9KvmpDWi%2B9JajUCUSJeB5ofJgMcHnY1ETlWsv6%2FatX7wPnWTWujzfAfIUu8ypvpwy%2FTjmRH6nyKrKE3Fgc4ebTzSfMmSS0Lud7Sz4S2dZit3bxcN9zXCkh1puf9xxEmvRtfoW95YuDkkldxvr&X-Amz-Signature=ee21c63d5c3981e045198f10ffbe9a68cbf5bab544ecc2d9391639b1a988021a&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663MFTJQDL%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T152640Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCQzXNX16YfCQu2gigQOvN3xbVOjNunhE1GkmuGE6sI2gIgbXijTEGr9eaNWTRdQ%2BHFDXYOb9PRG4cVmVSeyxIyFg0q%2FwMIGRAAGgw2Mzc0MjMxODM4MDUiDIaqq4Le6GVK%2BGfEeSrcA9E04tISBa1KEndlt2sQGUDbJVrn2U%2FPW0jkFruKJr2iynYsz%2Bpz4OWwsbDnkrGegHTDQwbjskhWGQHkQ7KXxPwb9%2Bqkjww%2BKFCB6cdrThbzb1WUUwR1FKynFJIPAkGO2VR3zqQmUOht0SOkRxMBOk1LbV9jHa1CBY%2FhAk%2BE1RyctfQ3SvqhXENDoiDHi8hFrjoD1rPzyLfgswGvgpk6xFho9cXm%2BULFw6N8y4AhHiIT8gdBPhUGP%2BtlDWJfOpfgZBwN29JfMLHOJRru9K4usvvgPgYe7DCcbTDUg2K0PWg4JSbIrSdaj4J1YYgRDJ%2BJj2sdakvhr5qIG%2FYJ2GxVe9RoAqcF52EJR3wNt%2B0vczs3lvKYUGKdBT96dftFqd5l7b3tK893V5BNuZoLTLcCQFG1IP9SFvDwjL75PHoG0P1HBsfjuqH%2Ff8BqP8VmwfkRGbbzLyWPO3xrjOcgeRiAkmI6INWmiLz%2FE0yJewvmvVPV%2FW82lBudmTXe9u%2FgbGiO8fQKesIH0gfnS%2FuBk716jUX1IUYELxPsB%2F2tZH1DaHHtFCdRupMRywMnu9mYI4%2B29bHBXvgyuN%2B%2FhOIl593TS8Ynzg29QtuE5ECzApu%2F2xm%2FL4u2x5LO4mkkcr5WMO2duL0GOqUBaorUJtG9stHY0573gari5%2Bm6xmS16E6YxBWE%2BTVrurDKdm06Ql7ArbtqT4KfaVhYjPLsnfkRobYed6jBnoDctK%2BgTUuftg8NXKyYuieF6yuSbZnv28xyeqchZhQvFNf5Gs5irIY2uTHZ9RoO9yBuw8ZXp1dcTkY4RLJXcuNMIfBI8pJuzrqY1E871vkVsVoF6se0YOotiXuU6EFyDu54M%2F2LEd%2Bx&X-Amz-Signature=13598cb85af643421ee55b2a3974f6627876c2efa5d92443ec81fcbd54e1ee36&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZXZ5TW73%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T152638Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCBUiFNhPSoodIDSeBEoshSGCZe9csNNrnq5HDOd0%2BY9gIgau8wYnAbg7Yno6JGcykJmnBWoZPMkEA30U4fLeo7HQcq%2FwMIFhAAGgw2Mzc0MjMxODM4MDUiDBLLJcpB3n7g25gCGircA1opS%2BhOYGMDd%2FFNoTnb7qyL9XkPTgkoghZGh8TmFGeX4AqbCB7MnLCuXSTwgs1OAM%2BfA%2Bot2e7YkfYwbKm3w3fkRULRkWRJ%2BNQRIw3flbBB00m8I%2FXR0xBvDu7VMSyindBeITw1fkbx4K4%2BxgunTd%2BudGdEc%2BOvnl0ZqIOV7vSS8dldzIrePDk5w58tjhgc1ZMJM5E6OxjglN69jNb%2B7hKV15%2FO1S1wyQL0RZwVJ5w%2FtxQomzqQ6yzN1Y%2Fts%2FZrEFoqS4FdYJ8vVr0l8nBbBcMXo6MVmjjtTgBOWEHSCVNxrd5rSr4%2BDiRS9ZiWSIMY%2F4nkWlXS8125Wea0vk4o5C73wy8Z21WSZ1pNL1VkQLi5HlSaI5bMnnlR38N3YSMemw0rBYOA6ZxFSRDSiFbCGyHHOceCMpCmAYRsaG08O0H%2B%2FZSGZDUa6AYPNk1VWY40xaYlfEnJPWkEpQgb1owHzjjpFgcu81IXQ5wsTsjktqZAqVHGPjyBRzD1i13czOBznpF%2BH2ThaMsDo4%2FbJJofV6hEP10jJogAZN4wmfvxsYFJ3Lj261vUU3W9r8dWE8CIx%2FIYLI7CITGVHCXzYo6h4DgOHozPDnAKuXZjvCql1JsEV9e6GlS46SNKkqNcMILet70GOqUBOb2UIsBcUe9nsgf8VRWx8Yhn0OJEs88Il%2FAwKBcfEtvlfCxPk2bc16fQu2X1sqOkF9utXHmFVYRFyy7nE6fT17p5BBggqnW55hOHVfRO7TBXtjayRBqOTjw2lHrQGbteiv1iOwyi2OntInwnjP%2BW%2B1me%2B0%2BaKV3fY7%2FDr2S%2B7MGiwaTalIYS8fhr%2F3FeU9mlxx2W19BlDA7uCMA2Y3XICwWt4bGq&X-Amz-Signature=91ff5a33d1a5c296ec30ad55b52e85c4b3eacb7ea169bd957ef2fd29173b1918&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZXZ5TW73%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T152638Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCBUiFNhPSoodIDSeBEoshSGCZe9csNNrnq5HDOd0%2BY9gIgau8wYnAbg7Yno6JGcykJmnBWoZPMkEA30U4fLeo7HQcq%2FwMIFhAAGgw2Mzc0MjMxODM4MDUiDBLLJcpB3n7g25gCGircA1opS%2BhOYGMDd%2FFNoTnb7qyL9XkPTgkoghZGh8TmFGeX4AqbCB7MnLCuXSTwgs1OAM%2BfA%2Bot2e7YkfYwbKm3w3fkRULRkWRJ%2BNQRIw3flbBB00m8I%2FXR0xBvDu7VMSyindBeITw1fkbx4K4%2BxgunTd%2BudGdEc%2BOvnl0ZqIOV7vSS8dldzIrePDk5w58tjhgc1ZMJM5E6OxjglN69jNb%2B7hKV15%2FO1S1wyQL0RZwVJ5w%2FtxQomzqQ6yzN1Y%2Fts%2FZrEFoqS4FdYJ8vVr0l8nBbBcMXo6MVmjjtTgBOWEHSCVNxrd5rSr4%2BDiRS9ZiWSIMY%2F4nkWlXS8125Wea0vk4o5C73wy8Z21WSZ1pNL1VkQLi5HlSaI5bMnnlR38N3YSMemw0rBYOA6ZxFSRDSiFbCGyHHOceCMpCmAYRsaG08O0H%2B%2FZSGZDUa6AYPNk1VWY40xaYlfEnJPWkEpQgb1owHzjjpFgcu81IXQ5wsTsjktqZAqVHGPjyBRzD1i13czOBznpF%2BH2ThaMsDo4%2FbJJofV6hEP10jJogAZN4wmfvxsYFJ3Lj261vUU3W9r8dWE8CIx%2FIYLI7CITGVHCXzYo6h4DgOHozPDnAKuXZjvCql1JsEV9e6GlS46SNKkqNcMILet70GOqUBOb2UIsBcUe9nsgf8VRWx8Yhn0OJEs88Il%2FAwKBcfEtvlfCxPk2bc16fQu2X1sqOkF9utXHmFVYRFyy7nE6fT17p5BBggqnW55hOHVfRO7TBXtjayRBqOTjw2lHrQGbteiv1iOwyi2OntInwnjP%2BW%2B1me%2B0%2BaKV3fY7%2FDr2S%2B7MGiwaTalIYS8fhr%2F3FeU9mlxx2W19BlDA7uCMA2Y3XICwWt4bGq&X-Amz-Signature=0f789dd0777c6d9e5114c2bb64efc1009469dcc599b475608927e1c6baae3b93&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZXZ5TW73%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T152638Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCBUiFNhPSoodIDSeBEoshSGCZe9csNNrnq5HDOd0%2BY9gIgau8wYnAbg7Yno6JGcykJmnBWoZPMkEA30U4fLeo7HQcq%2FwMIFhAAGgw2Mzc0MjMxODM4MDUiDBLLJcpB3n7g25gCGircA1opS%2BhOYGMDd%2FFNoTnb7qyL9XkPTgkoghZGh8TmFGeX4AqbCB7MnLCuXSTwgs1OAM%2BfA%2Bot2e7YkfYwbKm3w3fkRULRkWRJ%2BNQRIw3flbBB00m8I%2FXR0xBvDu7VMSyindBeITw1fkbx4K4%2BxgunTd%2BudGdEc%2BOvnl0ZqIOV7vSS8dldzIrePDk5w58tjhgc1ZMJM5E6OxjglN69jNb%2B7hKV15%2FO1S1wyQL0RZwVJ5w%2FtxQomzqQ6yzN1Y%2Fts%2FZrEFoqS4FdYJ8vVr0l8nBbBcMXo6MVmjjtTgBOWEHSCVNxrd5rSr4%2BDiRS9ZiWSIMY%2F4nkWlXS8125Wea0vk4o5C73wy8Z21WSZ1pNL1VkQLi5HlSaI5bMnnlR38N3YSMemw0rBYOA6ZxFSRDSiFbCGyHHOceCMpCmAYRsaG08O0H%2B%2FZSGZDUa6AYPNk1VWY40xaYlfEnJPWkEpQgb1owHzjjpFgcu81IXQ5wsTsjktqZAqVHGPjyBRzD1i13czOBznpF%2BH2ThaMsDo4%2FbJJofV6hEP10jJogAZN4wmfvxsYFJ3Lj261vUU3W9r8dWE8CIx%2FIYLI7CITGVHCXzYo6h4DgOHozPDnAKuXZjvCql1JsEV9e6GlS46SNKkqNcMILet70GOqUBOb2UIsBcUe9nsgf8VRWx8Yhn0OJEs88Il%2FAwKBcfEtvlfCxPk2bc16fQu2X1sqOkF9utXHmFVYRFyy7nE6fT17p5BBggqnW55hOHVfRO7TBXtjayRBqOTjw2lHrQGbteiv1iOwyi2OntInwnjP%2BW%2B1me%2B0%2BaKV3fY7%2FDr2S%2B7MGiwaTalIYS8fhr%2F3FeU9mlxx2W19BlDA7uCMA2Y3XICwWt4bGq&X-Amz-Signature=cc0ebfc2374a142e5336ffd2615b783ec25a7aafd7c667b3278e936d84789c70&X-Amz-SignedHeaders=host&x-id=GetObject)


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

