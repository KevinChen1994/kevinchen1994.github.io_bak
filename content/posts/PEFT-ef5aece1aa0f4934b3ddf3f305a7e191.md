---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466WGIRGRDT%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250215T014625Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEBAaCXVzLXdlc3QtMiJHMEUCIFnsg3L2%2FRIbobomQfD9TKwgEOdMb9ACAvO2fdL2f8aPAiEA3\
  RxxlMzVcFiLu5UUtZVUKyNJgMPJLDFymYRHKDl2p0Iq%2FwMIORAAGgw2Mzc0MjMxODM4MDUiDJd%\
  2B0OZZqTsezF6E9CrcA06jvxcu2oHbnpfKlmMSGIWV%2F18h6NISssWML7R2wCy5P0ZUS%2B6LIph\
  Jf2PGtCA3OcG8FU6%2BxOExysaML9zm9ZWAAXEyFodRtCh8aKxCL%2FtfCKH%2Byxex7CGR7oRn6F\
  D9TMdi8kTFZmnSMDmJtBBtXyaGv5cEP0q74Wd7GzeVx0zSxNuDsD%2BoW0c%2FlQHDBpqWEcbhkho\
  e%2BC0ujnJCztVZzVmh1xdqZXQBGYx22D5T6KxjdEqA8FFFyUshGDLJm8c6OEnpys%2BTIossqoA9\
  foQlbZjQhM50iyqCpR341rhSeYDb6inTHe2IJi15gGMcWZiHU0ACAcyqZV8dBhTNHOew%2BcbObzO\
  v%2BvQS36Dgf%2Bnx8eGZiOQikBME6OqxOLYiyrVD3oI5MxHWU6HgqakVdPOg0padina7ODy0cW4f\
  M3jqdndzQHfVPcJGySZPS20B7kXuOuhUZD%2FiRzTj6w%2FyFmm4nPYSPp6Jq0WZBppGOfc6MlfmS\
  87dVA7eb7wxe8e365gKWlLxe9D47mcBEj8oEpUFasQxfnxaZCaeF%2FsBdzwZ42NWF0fXtkEEpbS9\
  Lm0FUPkErI9nXTSKQ7XVLBZLFbKOcu89TlI6E9SsusNOz3vuc91jBwjdO6FgjIBkO0ydMIy0v70GO\
  qUBJcow61WzABP7nU0QYGzNL8QsJvscjkqj4lnPQFI8XJMRWCQ53tk%2FsDgzlETBTf90fAishW9C\
  MFMP04gJ7N0d%2F%2F1MalKsT8LpbDKqtmhkib8iNztro7F07H%2BSfxmGU%2BLOUA9OwB0fWZArp\
  PEctMW1k%2F%2BqFFPIdVNR5l7gdSWKnsPPKAQXuua8StAWKLfaagBjZtQvlsdgn%2B3eXJRJOu3P\
  g1wWMv9f&X-Amz-Signature=3788832bf09f43c186e8cfdcf8e6cafdb46c63d312e2a22fb309\
  124efc8908c3&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4662LTYJH65%2F20250215%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250215T014500Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEBAaCXVzLXdlc3QtMiJHMEUCIQD0xlaaKovslp%2BKCpdNUtZcYvSq%\
        2FIA6cZrrD8MgfI9AhwIgCBpKb%2FyfgLbAvF2qGhcTdKZJhQM0JkSHEVVCqeD13Nkq%2Fw\
        MIORAAGgw2Mzc0MjMxODM4MDUiDE2zzCecWeeOY1eDACrcA2%2FWlONQIajdpRQb7QOn8PG\
        Vh64GFw0yZ3WBnevfI9w9hNP5CJy4vYYUUsKKs33zbv%2FpWC6XB7l%2BurjzwPdQrVcgmx\
        9q3CF%2BBtgT7b4nK3t%2FM9%2FK7i5LHjqZxyiXHtMnqpXR44gMarR0bvDmQlLqqpfvjeg\
        VLjUI1GdPZg0ejGn8KZt8zXCPEUBKDJH7FEuGRN97MEB%2FjMer1Hwrt48I710vG8s2TBv6\
        Uxi0nQy0Jr9cH1hIlw9m46cro26NOWqVkZkZ5qaZVghCSDjeSB8Rj5yf5I3Wbwj7ayW%2BD\
        9fBpyIzZHa8Jd2lSwZFj3sBu4xGSFXx8d8aB8qMyk2CkcGRlxYyYiD%2BE1rvqKezpXtJ%2\
        BNPYSr6fqqWne5v09EihFQyLdvVHtmrB0ikgzsED7vQCEgxJcFsD%2BtBrQtodooaXgIC1u\
        4LG9e%2FumfRKZIslT0pj0%2Bm5KB71Gm1Z1OTGU7q5ov83KV1uOcXAtDU5pppb7fDb5nsj\
        RU2QWVqmATWkgo9%2BIayM6Cw5I0ZZEx85vRlcf0wsDqF8S5vxGubyR7do%2B8l1N6HoDIj\
        arz2MGh%2BI0%2BFbGkSscAAACAzlmZeA6GHw5S5tjHEEZ2GwQfxptFNYTfOfcXW4Qko7Wg\
        Ws0hCLMKC0v70GOqUBucNb0W4kC4W0GTlPsKmMizwbR1sFoBYQyqmMBNjlb%2Bw%2FyjNpn\
        PlbcCQ1xfVqu4sLySokulhP5%2FZmT7QKKSkKfcPqtYfn5riS%2BQSvQlUF5JNH694fEiy4\
        P5gcAR9GPyA4Ry%2F5abo8w4QBSZakEYeUQVt3qiPjcBVRGKowC4QWnohV547l0syehd9Hx\
        o02RXce7g%2F0Bn2N07zQgCrveh4oHYenig25&X-Amz-Signature=f81cd2d901dbc8233\
        305f18df327e391985ddec5f4d2298540cb713c5448a602&X-Amz-SignedHeaders=hos\
        t&x-id=GetObject"
      expiry_time: "2025-02-15T02:45:00.785Z"
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
UPDATE_TIME: "2025-02-15T01:46:29.802Z"
EXPIRY_TIME: "2025-02-15T02:46:22.341Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RIIIUSN6%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T014622Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBAaCXVzLXdlc3QtMiJHMEUCIHOMlgF%2BQmMRWlbWIhJ%2Bza3ZPqnaHlrQ6hwh88zkLhPBAiEAhzuswL5xvIBMSxze5y4rlVPoI0HhrT1%2BqTyMXYskWxcq%2FwMIORAAGgw2Mzc0MjMxODM4MDUiDPg7%2Blcz2cjvgkev0CrcAzGANwo8knaD%2F3UCHMULmlhABGvQovqD7CUKxennwDwQGNvym72ASpeAqCnu8cruVb7fI4gBnGrchCFGPbbM%2BcLkPHtkZi5%2FldcT1Hx8GENZ7lN2OSvTjN6YiylbSk3pw20BBGF1FiZcFOxO%2Bmf6WjXT386ntBAPzaysSO6hmiD%2Baq0pf2fsPjrrO9kVf9l1%2Bnbwf%2BMi45a8aAiTDJyEuUkqgG2DrdjAX5GZ%2B9bcKSZkficASPgOozxXVgde2B3O5HqQv8m0jGeW7UgbaHrRHja1Hehf%2BmVKXuKXT57jivWcXyXtf0QTntVfCToomB2Xt5bEQDCpOaFkUnL6UiBh2wkLEp%2BLlX6tNIdrQHJYjKWaoPJ3emNrz3RmMltEC66h%2BKbJQroFiUlPYGrMN9yNis%2FAkLMYuIveBLGBIVIrHq2PRTwY7WyLNOTkeuc%2Fe5KWga6gvf2lA8wivY9EFP7eUPXOytH0iNX8z4WAMEE6ZFiJMOiEo3vRKNnMLLLqSOBJwIaO4oTYUJ7PLyoN0M5e5zlaVAPo0H2D9F6yNjv7ubxZrnu7wTE2bopCPVfuyeax%2BF1L7nTZV%2FF3aDkeRv3uoCh5C8dueOmcLIOjZ16YaPoJbxsXKoyljR7rm7BQMJK0v70GOqUBp4%2FWEDAgqwTn07Z2cV9is66adR3vvtNin3wjkBThrGaIZ%2F09ov9PbVRElrH8Uc1SFyxiu%2BX0f7lUKAp%2BdgnQbnF8D5qeLhJixq3cw9JySgFDD1ts%2BDSUvszYH089Ce1AdB7uKT8%2FkOZ2jMa3mx8F8ScGLwKWQ798XzdzQlJvwvHZ7fNxgkJrt160K%2Bmd4EB5HUqi5%2BxW5PHIUgcB%2F%2BbhGhG5SZTr&X-Amz-Signature=1f9a9e95b29391d1c2d34d65efa68fe28657e8c7bf4fdc68354a277f02982387&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RIIIUSN6%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T014622Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBAaCXVzLXdlc3QtMiJHMEUCIHOMlgF%2BQmMRWlbWIhJ%2Bza3ZPqnaHlrQ6hwh88zkLhPBAiEAhzuswL5xvIBMSxze5y4rlVPoI0HhrT1%2BqTyMXYskWxcq%2FwMIORAAGgw2Mzc0MjMxODM4MDUiDPg7%2Blcz2cjvgkev0CrcAzGANwo8knaD%2F3UCHMULmlhABGvQovqD7CUKxennwDwQGNvym72ASpeAqCnu8cruVb7fI4gBnGrchCFGPbbM%2BcLkPHtkZi5%2FldcT1Hx8GENZ7lN2OSvTjN6YiylbSk3pw20BBGF1FiZcFOxO%2Bmf6WjXT386ntBAPzaysSO6hmiD%2Baq0pf2fsPjrrO9kVf9l1%2Bnbwf%2BMi45a8aAiTDJyEuUkqgG2DrdjAX5GZ%2B9bcKSZkficASPgOozxXVgde2B3O5HqQv8m0jGeW7UgbaHrRHja1Hehf%2BmVKXuKXT57jivWcXyXtf0QTntVfCToomB2Xt5bEQDCpOaFkUnL6UiBh2wkLEp%2BLlX6tNIdrQHJYjKWaoPJ3emNrz3RmMltEC66h%2BKbJQroFiUlPYGrMN9yNis%2FAkLMYuIveBLGBIVIrHq2PRTwY7WyLNOTkeuc%2Fe5KWga6gvf2lA8wivY9EFP7eUPXOytH0iNX8z4WAMEE6ZFiJMOiEo3vRKNnMLLLqSOBJwIaO4oTYUJ7PLyoN0M5e5zlaVAPo0H2D9F6yNjv7ubxZrnu7wTE2bopCPVfuyeax%2BF1L7nTZV%2FF3aDkeRv3uoCh5C8dueOmcLIOjZ16YaPoJbxsXKoyljR7rm7BQMJK0v70GOqUBp4%2FWEDAgqwTn07Z2cV9is66adR3vvtNin3wjkBThrGaIZ%2F09ov9PbVRElrH8Uc1SFyxiu%2BX0f7lUKAp%2BdgnQbnF8D5qeLhJixq3cw9JySgFDD1ts%2BDSUvszYH089Ce1AdB7uKT8%2FkOZ2jMa3mx8F8ScGLwKWQ798XzdzQlJvwvHZ7fNxgkJrt160K%2Bmd4EB5HUqi5%2BxW5PHIUgcB%2F%2BbhGhG5SZTr&X-Amz-Signature=ee7d0551d522a1e21f65d2bc203af6ecf9d5f25b9f90a67ffcd7745117e84459&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RIIIUSN6%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T014622Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBAaCXVzLXdlc3QtMiJHMEUCIHOMlgF%2BQmMRWlbWIhJ%2Bza3ZPqnaHlrQ6hwh88zkLhPBAiEAhzuswL5xvIBMSxze5y4rlVPoI0HhrT1%2BqTyMXYskWxcq%2FwMIORAAGgw2Mzc0MjMxODM4MDUiDPg7%2Blcz2cjvgkev0CrcAzGANwo8knaD%2F3UCHMULmlhABGvQovqD7CUKxennwDwQGNvym72ASpeAqCnu8cruVb7fI4gBnGrchCFGPbbM%2BcLkPHtkZi5%2FldcT1Hx8GENZ7lN2OSvTjN6YiylbSk3pw20BBGF1FiZcFOxO%2Bmf6WjXT386ntBAPzaysSO6hmiD%2Baq0pf2fsPjrrO9kVf9l1%2Bnbwf%2BMi45a8aAiTDJyEuUkqgG2DrdjAX5GZ%2B9bcKSZkficASPgOozxXVgde2B3O5HqQv8m0jGeW7UgbaHrRHja1Hehf%2BmVKXuKXT57jivWcXyXtf0QTntVfCToomB2Xt5bEQDCpOaFkUnL6UiBh2wkLEp%2BLlX6tNIdrQHJYjKWaoPJ3emNrz3RmMltEC66h%2BKbJQroFiUlPYGrMN9yNis%2FAkLMYuIveBLGBIVIrHq2PRTwY7WyLNOTkeuc%2Fe5KWga6gvf2lA8wivY9EFP7eUPXOytH0iNX8z4WAMEE6ZFiJMOiEo3vRKNnMLLLqSOBJwIaO4oTYUJ7PLyoN0M5e5zlaVAPo0H2D9F6yNjv7ubxZrnu7wTE2bopCPVfuyeax%2BF1L7nTZV%2FF3aDkeRv3uoCh5C8dueOmcLIOjZ16YaPoJbxsXKoyljR7rm7BQMJK0v70GOqUBp4%2FWEDAgqwTn07Z2cV9is66adR3vvtNin3wjkBThrGaIZ%2F09ov9PbVRElrH8Uc1SFyxiu%2BX0f7lUKAp%2BdgnQbnF8D5qeLhJixq3cw9JySgFDD1ts%2BDSUvszYH089Ce1AdB7uKT8%2FkOZ2jMa3mx8F8ScGLwKWQ798XzdzQlJvwvHZ7fNxgkJrt160K%2Bmd4EB5HUqi5%2BxW5PHIUgcB%2F%2BbhGhG5SZTr&X-Amz-Signature=d0c0c66681713391f22cecfe141bbd25e217652c54f69b3463bf04e72adfea18&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RIIIUSN6%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T014622Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBAaCXVzLXdlc3QtMiJHMEUCIHOMlgF%2BQmMRWlbWIhJ%2Bza3ZPqnaHlrQ6hwh88zkLhPBAiEAhzuswL5xvIBMSxze5y4rlVPoI0HhrT1%2BqTyMXYskWxcq%2FwMIORAAGgw2Mzc0MjMxODM4MDUiDPg7%2Blcz2cjvgkev0CrcAzGANwo8knaD%2F3UCHMULmlhABGvQovqD7CUKxennwDwQGNvym72ASpeAqCnu8cruVb7fI4gBnGrchCFGPbbM%2BcLkPHtkZi5%2FldcT1Hx8GENZ7lN2OSvTjN6YiylbSk3pw20BBGF1FiZcFOxO%2Bmf6WjXT386ntBAPzaysSO6hmiD%2Baq0pf2fsPjrrO9kVf9l1%2Bnbwf%2BMi45a8aAiTDJyEuUkqgG2DrdjAX5GZ%2B9bcKSZkficASPgOozxXVgde2B3O5HqQv8m0jGeW7UgbaHrRHja1Hehf%2BmVKXuKXT57jivWcXyXtf0QTntVfCToomB2Xt5bEQDCpOaFkUnL6UiBh2wkLEp%2BLlX6tNIdrQHJYjKWaoPJ3emNrz3RmMltEC66h%2BKbJQroFiUlPYGrMN9yNis%2FAkLMYuIveBLGBIVIrHq2PRTwY7WyLNOTkeuc%2Fe5KWga6gvf2lA8wivY9EFP7eUPXOytH0iNX8z4WAMEE6ZFiJMOiEo3vRKNnMLLLqSOBJwIaO4oTYUJ7PLyoN0M5e5zlaVAPo0H2D9F6yNjv7ubxZrnu7wTE2bopCPVfuyeax%2BF1L7nTZV%2FF3aDkeRv3uoCh5C8dueOmcLIOjZ16YaPoJbxsXKoyljR7rm7BQMJK0v70GOqUBp4%2FWEDAgqwTn07Z2cV9is66adR3vvtNin3wjkBThrGaIZ%2F09ov9PbVRElrH8Uc1SFyxiu%2BX0f7lUKAp%2BdgnQbnF8D5qeLhJixq3cw9JySgFDD1ts%2BDSUvszYH089Ce1AdB7uKT8%2FkOZ2jMa3mx8F8ScGLwKWQ798XzdzQlJvwvHZ7fNxgkJrt160K%2Bmd4EB5HUqi5%2BxW5PHIUgcB%2F%2BbhGhG5SZTr&X-Amz-Signature=ab18444a6131ffac85ad448b3a5447b2188566d8ed4890f7bd63c799b9920829&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RIIIUSN6%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T014622Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBAaCXVzLXdlc3QtMiJHMEUCIHOMlgF%2BQmMRWlbWIhJ%2Bza3ZPqnaHlrQ6hwh88zkLhPBAiEAhzuswL5xvIBMSxze5y4rlVPoI0HhrT1%2BqTyMXYskWxcq%2FwMIORAAGgw2Mzc0MjMxODM4MDUiDPg7%2Blcz2cjvgkev0CrcAzGANwo8knaD%2F3UCHMULmlhABGvQovqD7CUKxennwDwQGNvym72ASpeAqCnu8cruVb7fI4gBnGrchCFGPbbM%2BcLkPHtkZi5%2FldcT1Hx8GENZ7lN2OSvTjN6YiylbSk3pw20BBGF1FiZcFOxO%2Bmf6WjXT386ntBAPzaysSO6hmiD%2Baq0pf2fsPjrrO9kVf9l1%2Bnbwf%2BMi45a8aAiTDJyEuUkqgG2DrdjAX5GZ%2B9bcKSZkficASPgOozxXVgde2B3O5HqQv8m0jGeW7UgbaHrRHja1Hehf%2BmVKXuKXT57jivWcXyXtf0QTntVfCToomB2Xt5bEQDCpOaFkUnL6UiBh2wkLEp%2BLlX6tNIdrQHJYjKWaoPJ3emNrz3RmMltEC66h%2BKbJQroFiUlPYGrMN9yNis%2FAkLMYuIveBLGBIVIrHq2PRTwY7WyLNOTkeuc%2Fe5KWga6gvf2lA8wivY9EFP7eUPXOytH0iNX8z4WAMEE6ZFiJMOiEo3vRKNnMLLLqSOBJwIaO4oTYUJ7PLyoN0M5e5zlaVAPo0H2D9F6yNjv7ubxZrnu7wTE2bopCPVfuyeax%2BF1L7nTZV%2FF3aDkeRv3uoCh5C8dueOmcLIOjZ16YaPoJbxsXKoyljR7rm7BQMJK0v70GOqUBp4%2FWEDAgqwTn07Z2cV9is66adR3vvtNin3wjkBThrGaIZ%2F09ov9PbVRElrH8Uc1SFyxiu%2BX0f7lUKAp%2BdgnQbnF8D5qeLhJixq3cw9JySgFDD1ts%2BDSUvszYH089Ce1AdB7uKT8%2FkOZ2jMa3mx8F8ScGLwKWQ798XzdzQlJvwvHZ7fNxgkJrt160K%2Bmd4EB5HUqi5%2BxW5PHIUgcB%2F%2BbhGhG5SZTr&X-Amz-Signature=689c43476595ffe2851438d821efca6dd236af51554a31946ca015923eaf586d&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UN5AUYUT%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T014623Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBAaCXVzLXdlc3QtMiJIMEYCIQCDFFlOvN0QqwlT0i%2BgdQTZtWSm4FNKCzHwb1FwULrHXgIhALiUsXRG4xirsiK0V8FC4c%2Bf4xQTYiiJDU3N%2F%2F4FXOMOKv8DCDkQABoMNjM3NDIzMTgzODA1IgzajBahAHCI8p57FFkq3AMVVPdx7wEVgRvBkw3fN4QNTLVufH4CRISTEVfqZ7vP7rv%2FTslLzyVJS4JRAEakRV1NK2PIQNmUIFkwgcM4SgXEbXP9lWvr%2FeJxMA3JK6yJOT7d9oyDnO1MD%2FVwE0B7r4Pz15TvZVSKeUfF1y%2Bl8FhkjP568UZu9lmpLRZzZhtNqv8s20tYEjFY5IsbINQ5isdD5NT1F0Jht8c9gUa2UzMT9l3WUIC6N2ka7s%2BnWNTgXa%2BCcCXV6hUHtg5oq6x6soMlH8K1wsML0kmfcJdGxN42QnFJG%2BP5WaEJRQ86GEvMmm%2FBKIx0yfMkfdwhmRKBRHfYEDhe0AM9ZoGZA4OalpODSTusY%2BmBDv8l%2BhEoROITMphmDOc49MUE1AkLRDTQpF0kzihd99o3IvmpMtHZD125WbiXpBKHwjb8%2FHONwXqOenxDJO7hnVRndpXpqsbEOcnVswhcVpRmTNt5RRMKJQwkijVUoIEk37%2BmQP%2BW0%2FuCVDvWa3Vr7fcn%2Fo71GNOqz5Y5be68vddsvUoy3R5XdcsOTyrDW5mnjiPmshLaunJfsi6pBX7CHFQqH%2BasWlj9FthJGW4DaNkU%2FRjtwL5qs4uubGoNVF5u516%2FZu5qA1rm2VAg10XGmiFAc9NXWzCrtL%2B9BjqkAcEc3Cl8i%2Fb0Qe1Qbn8j8YPf5Y57XMd%2FPUF3Z3kWUvxguI4X%2BsW0sPouAj05BWq%2FypC7JIpTi3wX90VEPCy%2BYip7z9G2y1PHjkYLR6lf9DmXoSQVHn4nhI4PnuW12kw59vdpChE%2Bf5ZOLiOAPckhs%2FTK22zNToI6WasgZzRmc6njCqdQlR64B1ma%2F2CyJtxEG1PvlW%2BmPko3F6tGQhyuK0IScJ3z&X-Amz-Signature=91ed65fdc2b8a81747bafedd3adfac9dba21495aa45c52fb04cb4ee86d24369b&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XPUPNH5D%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T014624Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBAaCXVzLXdlc3QtMiJIMEYCIQCwKFD02DTHx4Oc1rAN9JQl2K7jl7VWFkzqTlY7n2s00gIhAKtHR7my%2BR0N%2BRCCnUoE4GpPR0butQwIFTExCGuaGxxRKv8DCDkQABoMNjM3NDIzMTgzODA1Igyj%2FT5J8JaBFWpijIAq3ANMnBsgAn1JrwM8d4j%2Bxc5ebZhDpexzitxrkZIWAn6RzDyUY4ELwK%2FfSzNLA%2FK6mpfpYnRvAY6HPrdIeCQfDCi2CO5xspCVDtIiFp8LSZ%2FnKNk24qhmamlj8juij1csjvjp1XWztdlOhIp6w2Q2ZMI8NKtPNK7MLhFYEa0NmpK4%2BIN0zS9wn4isM8i7%2B5Vrq88mZPQCNVEWwT%2FBl9pxivd18T3H%2FwqiG1qifFG5i5KZQagHMyPPcq%2BpkzYaJNV%2BbkeY0zJgbKBZm6ABKUHMGdIvFcws29T2gcmKEZm3J6K1yxcnR%2BBxJlkSB2vMdZXBFVLnIc%2Fc2L9gbroSgWLQoEB7IxWTqrzTEbGAEehIhgfcVeLgC7jj1afmRPh77w3EG6RVkeML7X5pd7LWBUtzhVDEpAcT62bNVrrrzOPRWgOuKiMLWNVpwj5i4W4mhzCZK0NOvZj3bHF1VFiXheZtxtYjqHIiIIf%2Fho%2F1yJkiIpZ%2BNpZRWosGYI2SG4uC6ikh4zorj9LvPb7BDQXitaJzS4LYVnkME89k5i%2BlmdG7EtjgyuiyGtfVFBbt6mwXvgX52RXOb6tLXJ5aMH6TRt06egQbF6wB8uZnM%2Bf%2BS83j5F3%2Fa8wpDQe0MGJQww5l3jCDtL%2B9BjqkAWVHbdSFeHLLpeDrdiEOFt0dsQLZnsuUvFJZnV1acz%2BKGLCT6p8XaEY6nCHEChhNPEn9h%2FVjOA8LDAXYeNtysHev4c7JubOpiUjrBsTwBU7gOTVJdqUYlnLc9O1%2FpaSvZF8EoI0r8NWERY2WuoikkN1D7LhcpuSpJ5qwOIN7B6LlXSK4Z2SW4St3nc0fZH1LOb4wCAMaGTUk3AJ9IevNVqc8jL2u&X-Amz-Signature=c7663bce31bf16f2c99d484d4e4e6d19167793b2e0f610078608b59349c46691&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RIIIUSN6%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T014622Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBAaCXVzLXdlc3QtMiJHMEUCIHOMlgF%2BQmMRWlbWIhJ%2Bza3ZPqnaHlrQ6hwh88zkLhPBAiEAhzuswL5xvIBMSxze5y4rlVPoI0HhrT1%2BqTyMXYskWxcq%2FwMIORAAGgw2Mzc0MjMxODM4MDUiDPg7%2Blcz2cjvgkev0CrcAzGANwo8knaD%2F3UCHMULmlhABGvQovqD7CUKxennwDwQGNvym72ASpeAqCnu8cruVb7fI4gBnGrchCFGPbbM%2BcLkPHtkZi5%2FldcT1Hx8GENZ7lN2OSvTjN6YiylbSk3pw20BBGF1FiZcFOxO%2Bmf6WjXT386ntBAPzaysSO6hmiD%2Baq0pf2fsPjrrO9kVf9l1%2Bnbwf%2BMi45a8aAiTDJyEuUkqgG2DrdjAX5GZ%2B9bcKSZkficASPgOozxXVgde2B3O5HqQv8m0jGeW7UgbaHrRHja1Hehf%2BmVKXuKXT57jivWcXyXtf0QTntVfCToomB2Xt5bEQDCpOaFkUnL6UiBh2wkLEp%2BLlX6tNIdrQHJYjKWaoPJ3emNrz3RmMltEC66h%2BKbJQroFiUlPYGrMN9yNis%2FAkLMYuIveBLGBIVIrHq2PRTwY7WyLNOTkeuc%2Fe5KWga6gvf2lA8wivY9EFP7eUPXOytH0iNX8z4WAMEE6ZFiJMOiEo3vRKNnMLLLqSOBJwIaO4oTYUJ7PLyoN0M5e5zlaVAPo0H2D9F6yNjv7ubxZrnu7wTE2bopCPVfuyeax%2BF1L7nTZV%2FF3aDkeRv3uoCh5C8dueOmcLIOjZ16YaPoJbxsXKoyljR7rm7BQMJK0v70GOqUBp4%2FWEDAgqwTn07Z2cV9is66adR3vvtNin3wjkBThrGaIZ%2F09ov9PbVRElrH8Uc1SFyxiu%2BX0f7lUKAp%2BdgnQbnF8D5qeLhJixq3cw9JySgFDD1ts%2BDSUvszYH089Ce1AdB7uKT8%2FkOZ2jMa3mx8F8ScGLwKWQ798XzdzQlJvwvHZ7fNxgkJrt160K%2Bmd4EB5HUqi5%2BxW5PHIUgcB%2F%2BbhGhG5SZTr&X-Amz-Signature=f4ae11907c8c6afb906a24c9ce3f9f34227d1232b9e2e717c762982da14b74b8&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RIIIUSN6%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T014622Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBAaCXVzLXdlc3QtMiJHMEUCIHOMlgF%2BQmMRWlbWIhJ%2Bza3ZPqnaHlrQ6hwh88zkLhPBAiEAhzuswL5xvIBMSxze5y4rlVPoI0HhrT1%2BqTyMXYskWxcq%2FwMIORAAGgw2Mzc0MjMxODM4MDUiDPg7%2Blcz2cjvgkev0CrcAzGANwo8knaD%2F3UCHMULmlhABGvQovqD7CUKxennwDwQGNvym72ASpeAqCnu8cruVb7fI4gBnGrchCFGPbbM%2BcLkPHtkZi5%2FldcT1Hx8GENZ7lN2OSvTjN6YiylbSk3pw20BBGF1FiZcFOxO%2Bmf6WjXT386ntBAPzaysSO6hmiD%2Baq0pf2fsPjrrO9kVf9l1%2Bnbwf%2BMi45a8aAiTDJyEuUkqgG2DrdjAX5GZ%2B9bcKSZkficASPgOozxXVgde2B3O5HqQv8m0jGeW7UgbaHrRHja1Hehf%2BmVKXuKXT57jivWcXyXtf0QTntVfCToomB2Xt5bEQDCpOaFkUnL6UiBh2wkLEp%2BLlX6tNIdrQHJYjKWaoPJ3emNrz3RmMltEC66h%2BKbJQroFiUlPYGrMN9yNis%2FAkLMYuIveBLGBIVIrHq2PRTwY7WyLNOTkeuc%2Fe5KWga6gvf2lA8wivY9EFP7eUPXOytH0iNX8z4WAMEE6ZFiJMOiEo3vRKNnMLLLqSOBJwIaO4oTYUJ7PLyoN0M5e5zlaVAPo0H2D9F6yNjv7ubxZrnu7wTE2bopCPVfuyeax%2BF1L7nTZV%2FF3aDkeRv3uoCh5C8dueOmcLIOjZ16YaPoJbxsXKoyljR7rm7BQMJK0v70GOqUBp4%2FWEDAgqwTn07Z2cV9is66adR3vvtNin3wjkBThrGaIZ%2F09ov9PbVRElrH8Uc1SFyxiu%2BX0f7lUKAp%2BdgnQbnF8D5qeLhJixq3cw9JySgFDD1ts%2BDSUvszYH089Ce1AdB7uKT8%2FkOZ2jMa3mx8F8ScGLwKWQ798XzdzQlJvwvHZ7fNxgkJrt160K%2Bmd4EB5HUqi5%2BxW5PHIUgcB%2F%2BbhGhG5SZTr&X-Amz-Signature=d4919d254bddc45c5d2d46046e9c8478ecf484c331029b14eecea9105318ab76&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RIIIUSN6%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T014622Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBAaCXVzLXdlc3QtMiJHMEUCIHOMlgF%2BQmMRWlbWIhJ%2Bza3ZPqnaHlrQ6hwh88zkLhPBAiEAhzuswL5xvIBMSxze5y4rlVPoI0HhrT1%2BqTyMXYskWxcq%2FwMIORAAGgw2Mzc0MjMxODM4MDUiDPg7%2Blcz2cjvgkev0CrcAzGANwo8knaD%2F3UCHMULmlhABGvQovqD7CUKxennwDwQGNvym72ASpeAqCnu8cruVb7fI4gBnGrchCFGPbbM%2BcLkPHtkZi5%2FldcT1Hx8GENZ7lN2OSvTjN6YiylbSk3pw20BBGF1FiZcFOxO%2Bmf6WjXT386ntBAPzaysSO6hmiD%2Baq0pf2fsPjrrO9kVf9l1%2Bnbwf%2BMi45a8aAiTDJyEuUkqgG2DrdjAX5GZ%2B9bcKSZkficASPgOozxXVgde2B3O5HqQv8m0jGeW7UgbaHrRHja1Hehf%2BmVKXuKXT57jivWcXyXtf0QTntVfCToomB2Xt5bEQDCpOaFkUnL6UiBh2wkLEp%2BLlX6tNIdrQHJYjKWaoPJ3emNrz3RmMltEC66h%2BKbJQroFiUlPYGrMN9yNis%2FAkLMYuIveBLGBIVIrHq2PRTwY7WyLNOTkeuc%2Fe5KWga6gvf2lA8wivY9EFP7eUPXOytH0iNX8z4WAMEE6ZFiJMOiEo3vRKNnMLLLqSOBJwIaO4oTYUJ7PLyoN0M5e5zlaVAPo0H2D9F6yNjv7ubxZrnu7wTE2bopCPVfuyeax%2BF1L7nTZV%2FF3aDkeRv3uoCh5C8dueOmcLIOjZ16YaPoJbxsXKoyljR7rm7BQMJK0v70GOqUBp4%2FWEDAgqwTn07Z2cV9is66adR3vvtNin3wjkBThrGaIZ%2F09ov9PbVRElrH8Uc1SFyxiu%2BX0f7lUKAp%2BdgnQbnF8D5qeLhJixq3cw9JySgFDD1ts%2BDSUvszYH089Ce1AdB7uKT8%2FkOZ2jMa3mx8F8ScGLwKWQ798XzdzQlJvwvHZ7fNxgkJrt160K%2Bmd4EB5HUqi5%2BxW5PHIUgcB%2F%2BbhGhG5SZTr&X-Amz-Signature=83ac512a1315802af0731719d66eab8796dc94fa190d2f9a05498f21b54d5014&X-Amz-SignedHeaders=host&x-id=GetObject)


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

