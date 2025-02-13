---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4665YVT6PPG%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250213T092540Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEOn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIG%2F4%2FQ67PERM7tt\
  YXuOddkUPVsCqtmjvGKDzldbeJW3tAiEAyahGKWYnaErTAE%2BtfkMnkyykM1f10oROip7V2mwTSM\
  Iq%2FwMIEhAAGgw2Mzc0MjMxODM4MDUiDCthEMCKC%2BtO1DxD6CrcA01Wsek1Rp%2F%2Fa8xooUu\
  MvpSNGHZ7Y9LD6m%2Frp%2BPrwqS9zFUxsjEDC23TvUGULKMNnWMKUSw5b9comaQTZW3lLzleZ7Mo\
  B3d5Jf5Ve2I6PRWZ2lnw%2FUeZfyhucBgZPgsqmbFUvCiego%2FntLq7qFejaPgeKpaF4xcg5CRdt\
  nKvXyDGD9KZkkw5SKnP65Zdehdh%2BQjggoASxsnixiAk7x0R4OLKciogTXq62ketj3uBrcXTFA50\
  haHW3NnGhgE3Crfb8t%2BLpOgxMIMCCRvvsR32d5%2FMkY4wKPQd%2FL7AsZpZs5Fa56t6RCy0SFK\
  WxxqOBDjEehRmkJrs4F1xRmBc10Vi5KOdgC1dBt7%2BV%2BufaUp61e67RZoGuvzm07mN2XZ5j5Ry\
  z3jtcRguMKP4t1YneOhKtMYJFwlnpIDPGIxFyY1XaGZxITABlKnMskiRaBILXVfKm3XBx7UbapdBQ\
  es2hf4YMz8lybuUa5G9YIiO1bH9IxtwN8o%2By01m0gmFZWp%2By033jR0OP6Ut%2BQBxUES0gf5w\
  N1MY4TmnMnQfnlYuG2ydmgzKE3QAKvAVarldQI0uE%2BbJdoyJ%2FMmZSpPnxmxf9r8SQ5xW9NuoR\
  2HXQC2UEOMAKD6lEayxnKJUAHOV%2BQZ0MKPmtr0GOqUBF3wRCA1owAvjSVbUuQWx%2BYcVD%2BJz\
  qZmf5I6i2Q9RwXR8MQXR%2FhzAcpHiKiyGJ1rXZJOgRkTbKl5Y%2BtryTUZ9oE3KAJbqTIrjS%2FS\
  KvQP5KEAZnQ6jncqUPDx%2FiuZuLdJ4SiMj632Hd4hR2hnC5ypdsk0Ma9pdhl%2FXAQRtYirOC0Bl\
  H3TRYyKIOImMBDcAFezjvRtvHRx5o1x4puSn7UAMPaVs7LPx&X-Amz-Signature=72fd7bc5a17d\
  23c2850a33f98d6742452b6fea8354939f4d1185409c431b0398&X-Amz-SignedHeaders=host\
  &x-id=GetObject"
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
        redential=ASIAZI2LB466677V3MLG%2F20250213%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250213T092425Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEOn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIF6iEPnp5MF5L%2FNXWmc%2FPLQbSC0qeSGiQH6U9dB%2F%2FT5CAiEA2aq9iiCf9189Te\
        bVIwgMca7OJdnXbBLbM8o8unoc%2Fy0q%2FwMIEhAAGgw2Mzc0MjMxODM4MDUiDMl2f9Ldc\
        3cq%2Bw7AZCrcA8ksbe3K3jGhd63A7jfrKgCSTnd3Hr2Btb1Y1m9nfmEr%2BZkXUn64msh2\
        Fko5Da%2BbZw9DpM4ZxF26NoIuWFtewXphdd4YLxjzmrgVkV0GEc%2FKmF0dtNPuy6NDIUK\
        SzjwFbV5ED2UyC9NJ1fslzwS9%2B3dG3iuNKrVS8fQNwrkhQOwq%2BaO%2F3wUzjclg4g30\
        JmI3v%2Bf6MQrKjG6lVmQdTt%2FffxfI%2BYZz5VusOehu1UP%2FyFE0P%2FvBgMD2iFQOh\
        KpCbSeqnNHgkHE9o30X59SDUD955M2wTMJLVsCX5%2BmIiaXmj9aqXvt%2B6TZIShDOoxjE\
        sUPFHgJL9y%2BW7VXS%2FU67PrtBoIDvENyeVM89Guo2%2BhI3CF9atV4n9EH7ZjTn7%2BG\
        dw%2FyE5lI5BFzAT1VUSvujMZGRmWcuqhWTPpK8VTWx3IBGPlfxvfTdxVwiqMdnX%2BU9pB\
        MjPPsSbPdG0StUPqPCeXHZK2Q2B5Td17cO5O1e4QKQhDsQCOF%2FBun74YpTZfZNGw5IWlI\
        lP79PXAceD%2BoBaeojjcI4kSWZExdB89sm3yTlinXPBskzbSpiFzOhU5SmjaXWP%2F6zPU\
        kYOmTpGPhXKtvwsK8BXvG8xpaRA7GZwhSL%2Frt5QyWO9tc2SIRXjcIzMILmtr0GOqUB4xy\
        mEa%2B9AH8YwenWjIdIEg4iBduV1BKjqiiuzs3bMxexC6QF7cr8aWKJTDm5Iy6Nto3l1Tv%\
        2BosngUOP0H1KD6N4hj%2BcFITCYk8wy%2FI%2F8F3fC5Dw11Bd%2B3rnBbhAM2xkqNqsSW\
        n%2BMdBbYMYoELmjfKW5GxWa8HKH%2FZgkhKgeyIOUtfx%2FM%2BCcAFG3rX19QStfWpzzL\
        sPNPG6fXk6o51a%2BbjSg%2BxlWZ&X-Amz-Signature=7433ddb219c4d41ecccc4d8e91\
        a4eb4856655642a464f3330d68c9d538498669&X-Amz-SignedHeaders=host&x-id=Ge\
        tObject"
      expiry_time: "2025-02-13T10:24:24.990Z"
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
UPDATE_TIME: "2025-02-13T09:25:45.735Z"
EXPIRY_TIME: "2025-02-13T10:25:38.117Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UBCZVFG4%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T092538Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEieNcN%2BdOElz6%2F4Fq%2FNmKdP9SmqC4n2bgHnaOJz%2BGgtAiBkJC8bSxGiU4unaJUd%2Bme7W7vqFLGZruQ8tURn6p7FEir%2FAwgSEAAaDDYzNzQyMzE4MzgwNSIMC9Qa2w5IVtf15bRfKtwDhyLY3aSopx0VFjhCVY3j0D7YW4f2XPrz1fqHAG6T4KDafrj%2BSt0q7IW9k3IR6OTrycwoq5%2FBaEzCV9LqBK7IBqr5nOrOSexWPXYM%2FAwrsUowJFVwVYl8eUL0yqU73S11xkqGQbb64WFlNg7w4Jn4Y4cXwQ0x3l3aMwseNSqXPCLEGww%2BW0CNUfmC4viDYLdbXWWbvlEeNflrQA7jskA7ftW3Ef5emjkKaPOw4%2Bbq5PIRtaZoLqCT3pE6pDtIvu1gHf2XHXuAoD9npiVlQhYadTD89p48F%2B30gDeEzmmfo5XTM2dz2vWKGI4QVnGYwAxKGE%2FPbu7IrMr2Qa2ihJDhjfw9fF3x9dxtok2GaUFlOZP940iQYdPZlAkoRU6F9b9IALORS3tW71YHC1F5F5uY7ATQ8iptkUmrmPuUNq9uoTGlJDJqwEGLDfzKSru%2FKj1BLbOCJ7KLTLUePNK%2BPI9a2tSqJvJhVRNTqwl6FoVyS2jpJbHSUVQOpINWZ1a%2FD8eUka2Jo4L0FBZsTZLlV2vJ644aoX8F1GTGZhOz5%2Fw1cW1%2FlBaAth0xiKhlS4Ye7FSp5YIulyhUBDvKGMINkCc27%2F153CUF1dADkt0P0N6Se53fVunQ%2BCXyq35Dzrww4ua2vQY6pgFGFoiG%2F1pJ90CRUL1IgeFskUjEF3whggKkt69pi1783V31Vp5%2FwKP1LrkS6pxnOJ5A99A%2FYN95xvitagb9KfJ2EwsUPie%2B9mBcbAOslp9AZS3UqgL%2BpKj4DRUXnVqdJvpahr3hAmoFCVwvJkgVW21nWtlRoQJZaHZTSnDKcKWpc4jaWnERHSjpQ3XYmVXecLL6V2unkw7yOOJhgkUOk7Ktr4BeowQ2&X-Amz-Signature=add89bd00bcd672e554e1a47f3188f0cb3e126e50191027699bff5d6417c1d43&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UBCZVFG4%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T092538Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEieNcN%2BdOElz6%2F4Fq%2FNmKdP9SmqC4n2bgHnaOJz%2BGgtAiBkJC8bSxGiU4unaJUd%2Bme7W7vqFLGZruQ8tURn6p7FEir%2FAwgSEAAaDDYzNzQyMzE4MzgwNSIMC9Qa2w5IVtf15bRfKtwDhyLY3aSopx0VFjhCVY3j0D7YW4f2XPrz1fqHAG6T4KDafrj%2BSt0q7IW9k3IR6OTrycwoq5%2FBaEzCV9LqBK7IBqr5nOrOSexWPXYM%2FAwrsUowJFVwVYl8eUL0yqU73S11xkqGQbb64WFlNg7w4Jn4Y4cXwQ0x3l3aMwseNSqXPCLEGww%2BW0CNUfmC4viDYLdbXWWbvlEeNflrQA7jskA7ftW3Ef5emjkKaPOw4%2Bbq5PIRtaZoLqCT3pE6pDtIvu1gHf2XHXuAoD9npiVlQhYadTD89p48F%2B30gDeEzmmfo5XTM2dz2vWKGI4QVnGYwAxKGE%2FPbu7IrMr2Qa2ihJDhjfw9fF3x9dxtok2GaUFlOZP940iQYdPZlAkoRU6F9b9IALORS3tW71YHC1F5F5uY7ATQ8iptkUmrmPuUNq9uoTGlJDJqwEGLDfzKSru%2FKj1BLbOCJ7KLTLUePNK%2BPI9a2tSqJvJhVRNTqwl6FoVyS2jpJbHSUVQOpINWZ1a%2FD8eUka2Jo4L0FBZsTZLlV2vJ644aoX8F1GTGZhOz5%2Fw1cW1%2FlBaAth0xiKhlS4Ye7FSp5YIulyhUBDvKGMINkCc27%2F153CUF1dADkt0P0N6Se53fVunQ%2BCXyq35Dzrww4ua2vQY6pgFGFoiG%2F1pJ90CRUL1IgeFskUjEF3whggKkt69pi1783V31Vp5%2FwKP1LrkS6pxnOJ5A99A%2FYN95xvitagb9KfJ2EwsUPie%2B9mBcbAOslp9AZS3UqgL%2BpKj4DRUXnVqdJvpahr3hAmoFCVwvJkgVW21nWtlRoQJZaHZTSnDKcKWpc4jaWnERHSjpQ3XYmVXecLL6V2unkw7yOOJhgkUOk7Ktr4BeowQ2&X-Amz-Signature=f62f7c8861c991b4cfde5d3c50234e23e7e914f082e7b3deaf2c4aaa95516ea4&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UBCZVFG4%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T092538Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEieNcN%2BdOElz6%2F4Fq%2FNmKdP9SmqC4n2bgHnaOJz%2BGgtAiBkJC8bSxGiU4unaJUd%2Bme7W7vqFLGZruQ8tURn6p7FEir%2FAwgSEAAaDDYzNzQyMzE4MzgwNSIMC9Qa2w5IVtf15bRfKtwDhyLY3aSopx0VFjhCVY3j0D7YW4f2XPrz1fqHAG6T4KDafrj%2BSt0q7IW9k3IR6OTrycwoq5%2FBaEzCV9LqBK7IBqr5nOrOSexWPXYM%2FAwrsUowJFVwVYl8eUL0yqU73S11xkqGQbb64WFlNg7w4Jn4Y4cXwQ0x3l3aMwseNSqXPCLEGww%2BW0CNUfmC4viDYLdbXWWbvlEeNflrQA7jskA7ftW3Ef5emjkKaPOw4%2Bbq5PIRtaZoLqCT3pE6pDtIvu1gHf2XHXuAoD9npiVlQhYadTD89p48F%2B30gDeEzmmfo5XTM2dz2vWKGI4QVnGYwAxKGE%2FPbu7IrMr2Qa2ihJDhjfw9fF3x9dxtok2GaUFlOZP940iQYdPZlAkoRU6F9b9IALORS3tW71YHC1F5F5uY7ATQ8iptkUmrmPuUNq9uoTGlJDJqwEGLDfzKSru%2FKj1BLbOCJ7KLTLUePNK%2BPI9a2tSqJvJhVRNTqwl6FoVyS2jpJbHSUVQOpINWZ1a%2FD8eUka2Jo4L0FBZsTZLlV2vJ644aoX8F1GTGZhOz5%2Fw1cW1%2FlBaAth0xiKhlS4Ye7FSp5YIulyhUBDvKGMINkCc27%2F153CUF1dADkt0P0N6Se53fVunQ%2BCXyq35Dzrww4ua2vQY6pgFGFoiG%2F1pJ90CRUL1IgeFskUjEF3whggKkt69pi1783V31Vp5%2FwKP1LrkS6pxnOJ5A99A%2FYN95xvitagb9KfJ2EwsUPie%2B9mBcbAOslp9AZS3UqgL%2BpKj4DRUXnVqdJvpahr3hAmoFCVwvJkgVW21nWtlRoQJZaHZTSnDKcKWpc4jaWnERHSjpQ3XYmVXecLL6V2unkw7yOOJhgkUOk7Ktr4BeowQ2&X-Amz-Signature=fd2fa471e4a34e610c0a43afedeb83f2943612df4662af80c1dc376c6261d001&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UBCZVFG4%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T092538Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEieNcN%2BdOElz6%2F4Fq%2FNmKdP9SmqC4n2bgHnaOJz%2BGgtAiBkJC8bSxGiU4unaJUd%2Bme7W7vqFLGZruQ8tURn6p7FEir%2FAwgSEAAaDDYzNzQyMzE4MzgwNSIMC9Qa2w5IVtf15bRfKtwDhyLY3aSopx0VFjhCVY3j0D7YW4f2XPrz1fqHAG6T4KDafrj%2BSt0q7IW9k3IR6OTrycwoq5%2FBaEzCV9LqBK7IBqr5nOrOSexWPXYM%2FAwrsUowJFVwVYl8eUL0yqU73S11xkqGQbb64WFlNg7w4Jn4Y4cXwQ0x3l3aMwseNSqXPCLEGww%2BW0CNUfmC4viDYLdbXWWbvlEeNflrQA7jskA7ftW3Ef5emjkKaPOw4%2Bbq5PIRtaZoLqCT3pE6pDtIvu1gHf2XHXuAoD9npiVlQhYadTD89p48F%2B30gDeEzmmfo5XTM2dz2vWKGI4QVnGYwAxKGE%2FPbu7IrMr2Qa2ihJDhjfw9fF3x9dxtok2GaUFlOZP940iQYdPZlAkoRU6F9b9IALORS3tW71YHC1F5F5uY7ATQ8iptkUmrmPuUNq9uoTGlJDJqwEGLDfzKSru%2FKj1BLbOCJ7KLTLUePNK%2BPI9a2tSqJvJhVRNTqwl6FoVyS2jpJbHSUVQOpINWZ1a%2FD8eUka2Jo4L0FBZsTZLlV2vJ644aoX8F1GTGZhOz5%2Fw1cW1%2FlBaAth0xiKhlS4Ye7FSp5YIulyhUBDvKGMINkCc27%2F153CUF1dADkt0P0N6Se53fVunQ%2BCXyq35Dzrww4ua2vQY6pgFGFoiG%2F1pJ90CRUL1IgeFskUjEF3whggKkt69pi1783V31Vp5%2FwKP1LrkS6pxnOJ5A99A%2FYN95xvitagb9KfJ2EwsUPie%2B9mBcbAOslp9AZS3UqgL%2BpKj4DRUXnVqdJvpahr3hAmoFCVwvJkgVW21nWtlRoQJZaHZTSnDKcKWpc4jaWnERHSjpQ3XYmVXecLL6V2unkw7yOOJhgkUOk7Ktr4BeowQ2&X-Amz-Signature=100726c184d6ff08022985b596356bdc711c08f120065fa1745a30ed6e7c7945&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UBCZVFG4%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T092538Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEieNcN%2BdOElz6%2F4Fq%2FNmKdP9SmqC4n2bgHnaOJz%2BGgtAiBkJC8bSxGiU4unaJUd%2Bme7W7vqFLGZruQ8tURn6p7FEir%2FAwgSEAAaDDYzNzQyMzE4MzgwNSIMC9Qa2w5IVtf15bRfKtwDhyLY3aSopx0VFjhCVY3j0D7YW4f2XPrz1fqHAG6T4KDafrj%2BSt0q7IW9k3IR6OTrycwoq5%2FBaEzCV9LqBK7IBqr5nOrOSexWPXYM%2FAwrsUowJFVwVYl8eUL0yqU73S11xkqGQbb64WFlNg7w4Jn4Y4cXwQ0x3l3aMwseNSqXPCLEGww%2BW0CNUfmC4viDYLdbXWWbvlEeNflrQA7jskA7ftW3Ef5emjkKaPOw4%2Bbq5PIRtaZoLqCT3pE6pDtIvu1gHf2XHXuAoD9npiVlQhYadTD89p48F%2B30gDeEzmmfo5XTM2dz2vWKGI4QVnGYwAxKGE%2FPbu7IrMr2Qa2ihJDhjfw9fF3x9dxtok2GaUFlOZP940iQYdPZlAkoRU6F9b9IALORS3tW71YHC1F5F5uY7ATQ8iptkUmrmPuUNq9uoTGlJDJqwEGLDfzKSru%2FKj1BLbOCJ7KLTLUePNK%2BPI9a2tSqJvJhVRNTqwl6FoVyS2jpJbHSUVQOpINWZ1a%2FD8eUka2Jo4L0FBZsTZLlV2vJ644aoX8F1GTGZhOz5%2Fw1cW1%2FlBaAth0xiKhlS4Ye7FSp5YIulyhUBDvKGMINkCc27%2F153CUF1dADkt0P0N6Se53fVunQ%2BCXyq35Dzrww4ua2vQY6pgFGFoiG%2F1pJ90CRUL1IgeFskUjEF3whggKkt69pi1783V31Vp5%2FwKP1LrkS6pxnOJ5A99A%2FYN95xvitagb9KfJ2EwsUPie%2B9mBcbAOslp9AZS3UqgL%2BpKj4DRUXnVqdJvpahr3hAmoFCVwvJkgVW21nWtlRoQJZaHZTSnDKcKWpc4jaWnERHSjpQ3XYmVXecLL6V2unkw7yOOJhgkUOk7Ktr4BeowQ2&X-Amz-Signature=854ece382351f8e71d2312fef581a0002409c77ece29c7035e1362454a2796fc&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663QIRZTNA%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T092539Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDTJu7nL%2BxjTpiISXhZi9Ba6%2BdolrnfudiwQdTbCVBp9AIgL3r9Nc0IXJ%2Fq9tuk6Tc1ds4ynlm7GRQtDhJQSdm1xaAq%2FwMIEhAAGgw2Mzc0MjMxODM4MDUiDCf%2FSicW%2FCjjtuVT1yrcA7t3rfZnXMNwRwWP0sAa0DAEhBMEU4mTrxGtwTKgmxjY5I%2FjIIsLUrUqCgmwShHnv69DEyAVOheK2p30Va%2B2r%2Ff6NMyfOCa0prgNvU6Dp3DYwLxtRGAh3TBIabdWqMVoFZXQd%2BN9XK23OybTRKtjxLwwSUcXUquUeapqRQ9ONMwI1h%2BhosTc0ka45P5tKTVr7hE533Yd3rhFrzC%2FdEzZ9Wo1sFkWRytUgDq3WdwWiV8nJHsOJFHvpeo%2FTeshs6NeRYKb53BsxLoMfCifD63aHz5KEdnaL0NWPsVy37h4jeY4ZYm5UDnaekGz36%2BD7v1zwJ77E0CLqkgqZBSc4gFFdEIDa9R3lICtRcCX4cmo4o%2Ft64c%2B5OyNbW4LQHiWyIPv6CufnCNTCCe2LG%2FL65SW7UCySlNy3%2BLyQhyJhvFJRFwj6FctKpJaGG4Um%2B69sblLnldEGmSnmq2eZUXCQtey%2F2rBDoY5fEbq%2B5HtFOiAEwM88P7t%2B8f6j8Z%2BIDWn%2BRh%2BAeI2HzU2jirzaJwZQQff0dyPNBGBQ%2FtKG9gshpW%2BV%2FxVV3VDAx0pwB3LBVqrnCRpi7dL0fdpuKi%2F8Cw5L%2Brv3X1WcUW%2FvaaP92xEmcJX5U5xn%2FcQrW5TY6IFp0ZJMLjmtr0GOqUBK0NwO98E4N%2Fu%2FXVsQzGQ93534hx%2FP%2BxXKlpdWRsvC5f%2BApkDxXxc8CbvlMrPS110wldKYDzJORuPEBpdhK2U5I7DNR8UqIEoZ2Wi3O6w7BvW3de2VccMfhuzXC%2F1a1WqLWl4%2BnxwVpMYp4zGOvD%2B9AB%2FGf5yVeGcPqqbJ%2Fy2ds91n1rSFDSRphIlM8o24AI1pKzdcftgysUUxIgNPPLnsHVOO23v&X-Amz-Signature=4a7bcd4f2efd286f038824c2166af4793b98d7ea21668ed093967ed6169b5cac&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QGTNHKHB%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T092539Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIEJeBrpXXOm1Y6cIt3pwtPcOnoTWtGRh1mV2QxwD%2B5q2AiEA0E5yk9VY2eOIoG3l7XciOyUVz6%2FQCCQY2gFD6ZRc%2FEcq%2FwMIEhAAGgw2Mzc0MjMxODM4MDUiDBYFXrv8%2ByJTC9K%2BkyrcA183iFjOpqvBZkh06SQ%2Bdu2BKFxMo8m4WBGndRHWiOfxT%2F6qxNB0LHM3TcopfHTaKFLPQe4L1sXcUWYdB4cyF2ayZe%2BwHA%2BqpHR2iSNS1JV8LS9lxlnPZ4hg4HIrolkgpIxxaWXNoJXoZO%2B90mS6wuDoywmRGJESSAdeCEdlZEuMGMiFjf6cZLvhxjVgjzhsmIlQm%2Fap6HaLyq65zyRhIZNyQLGKrzrrTgwmYZ9lF97S7xmBWyvdGj4fkpv4lq%2BV6a786oH7VUGbyJZ3LfTJtXMJg0zziX6OHF0xwgcLY74g%2FUKK8SHqat3eijI6s0R0iDTRBKziHLF099FsXa3oitt4fMe0dmr7wpwYlqIdQ48sg6qYHUQXpH%2F%2ByBFU699YCJuqusZXXxfRULsZJbadIFOvqCplZTkSyhFQXqt37W3Blc%2BCjlG7W5Y0agX0hyoGnqzwMPUVdpo2DnshWNe3o3T7WFXwM1yPTxAdiFhDWFpa4aFMN%2B9PAXRyXclf4yv7NpV6P%2BCfG8%2F4YVu0mB8GvmN51ehmuvL9vpvsr1uNdD8E4rcP4AHkWVGUs66wYfMiXP%2Bn12%2FWNR%2FDq8aOypiTKEf19KQ8uxkbiGY899TdK%2FiI6jk0I1mQoDDRZyrsMP3ltr0GOqUBNtOdbn%2FKWq%2FrtguwiM4LZ3jZBYXCw2xieshUYGbp7QxyrXDmIigklchbpYSfEMy04kjobuRXg68HUa0wXfrQk5GuvnuOwmvnHdZxHxGNSgm9lcBaar2uSfOAWObAc98LMg4lSiY9iJBIN9rx4Tpw6QYIaLE6VyeoXxZj23aI0cJPAVNSq9tIrbPlOOkdU6ZGXNcuVxeN1s%2BQDRsp0QoJ3yfPsmHS&X-Amz-Signature=bc9c69dd0fa4a3cc6d27c6d0c6ac7575cba491c886566dd5945f0d81ee96d5bc&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UBCZVFG4%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T092538Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEieNcN%2BdOElz6%2F4Fq%2FNmKdP9SmqC4n2bgHnaOJz%2BGgtAiBkJC8bSxGiU4unaJUd%2Bme7W7vqFLGZruQ8tURn6p7FEir%2FAwgSEAAaDDYzNzQyMzE4MzgwNSIMC9Qa2w5IVtf15bRfKtwDhyLY3aSopx0VFjhCVY3j0D7YW4f2XPrz1fqHAG6T4KDafrj%2BSt0q7IW9k3IR6OTrycwoq5%2FBaEzCV9LqBK7IBqr5nOrOSexWPXYM%2FAwrsUowJFVwVYl8eUL0yqU73S11xkqGQbb64WFlNg7w4Jn4Y4cXwQ0x3l3aMwseNSqXPCLEGww%2BW0CNUfmC4viDYLdbXWWbvlEeNflrQA7jskA7ftW3Ef5emjkKaPOw4%2Bbq5PIRtaZoLqCT3pE6pDtIvu1gHf2XHXuAoD9npiVlQhYadTD89p48F%2B30gDeEzmmfo5XTM2dz2vWKGI4QVnGYwAxKGE%2FPbu7IrMr2Qa2ihJDhjfw9fF3x9dxtok2GaUFlOZP940iQYdPZlAkoRU6F9b9IALORS3tW71YHC1F5F5uY7ATQ8iptkUmrmPuUNq9uoTGlJDJqwEGLDfzKSru%2FKj1BLbOCJ7KLTLUePNK%2BPI9a2tSqJvJhVRNTqwl6FoVyS2jpJbHSUVQOpINWZ1a%2FD8eUka2Jo4L0FBZsTZLlV2vJ644aoX8F1GTGZhOz5%2Fw1cW1%2FlBaAth0xiKhlS4Ye7FSp5YIulyhUBDvKGMINkCc27%2F153CUF1dADkt0P0N6Se53fVunQ%2BCXyq35Dzrww4ua2vQY6pgFGFoiG%2F1pJ90CRUL1IgeFskUjEF3whggKkt69pi1783V31Vp5%2FwKP1LrkS6pxnOJ5A99A%2FYN95xvitagb9KfJ2EwsUPie%2B9mBcbAOslp9AZS3UqgL%2BpKj4DRUXnVqdJvpahr3hAmoFCVwvJkgVW21nWtlRoQJZaHZTSnDKcKWpc4jaWnERHSjpQ3XYmVXecLL6V2unkw7yOOJhgkUOk7Ktr4BeowQ2&X-Amz-Signature=274d48abf20e13ce09bef4e2648129820623141ed43e2724328f90e9d40a54e4&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UBCZVFG4%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T092538Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEieNcN%2BdOElz6%2F4Fq%2FNmKdP9SmqC4n2bgHnaOJz%2BGgtAiBkJC8bSxGiU4unaJUd%2Bme7W7vqFLGZruQ8tURn6p7FEir%2FAwgSEAAaDDYzNzQyMzE4MzgwNSIMC9Qa2w5IVtf15bRfKtwDhyLY3aSopx0VFjhCVY3j0D7YW4f2XPrz1fqHAG6T4KDafrj%2BSt0q7IW9k3IR6OTrycwoq5%2FBaEzCV9LqBK7IBqr5nOrOSexWPXYM%2FAwrsUowJFVwVYl8eUL0yqU73S11xkqGQbb64WFlNg7w4Jn4Y4cXwQ0x3l3aMwseNSqXPCLEGww%2BW0CNUfmC4viDYLdbXWWbvlEeNflrQA7jskA7ftW3Ef5emjkKaPOw4%2Bbq5PIRtaZoLqCT3pE6pDtIvu1gHf2XHXuAoD9npiVlQhYadTD89p48F%2B30gDeEzmmfo5XTM2dz2vWKGI4QVnGYwAxKGE%2FPbu7IrMr2Qa2ihJDhjfw9fF3x9dxtok2GaUFlOZP940iQYdPZlAkoRU6F9b9IALORS3tW71YHC1F5F5uY7ATQ8iptkUmrmPuUNq9uoTGlJDJqwEGLDfzKSru%2FKj1BLbOCJ7KLTLUePNK%2BPI9a2tSqJvJhVRNTqwl6FoVyS2jpJbHSUVQOpINWZ1a%2FD8eUka2Jo4L0FBZsTZLlV2vJ644aoX8F1GTGZhOz5%2Fw1cW1%2FlBaAth0xiKhlS4Ye7FSp5YIulyhUBDvKGMINkCc27%2F153CUF1dADkt0P0N6Se53fVunQ%2BCXyq35Dzrww4ua2vQY6pgFGFoiG%2F1pJ90CRUL1IgeFskUjEF3whggKkt69pi1783V31Vp5%2FwKP1LrkS6pxnOJ5A99A%2FYN95xvitagb9KfJ2EwsUPie%2B9mBcbAOslp9AZS3UqgL%2BpKj4DRUXnVqdJvpahr3hAmoFCVwvJkgVW21nWtlRoQJZaHZTSnDKcKWpc4jaWnERHSjpQ3XYmVXecLL6V2unkw7yOOJhgkUOk7Ktr4BeowQ2&X-Amz-Signature=9c4cbc9af94863b532b4a83cdfd9a711dde71eefff5160c6c220631f5ef30a1a&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UBCZVFG4%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T092538Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEieNcN%2BdOElz6%2F4Fq%2FNmKdP9SmqC4n2bgHnaOJz%2BGgtAiBkJC8bSxGiU4unaJUd%2Bme7W7vqFLGZruQ8tURn6p7FEir%2FAwgSEAAaDDYzNzQyMzE4MzgwNSIMC9Qa2w5IVtf15bRfKtwDhyLY3aSopx0VFjhCVY3j0D7YW4f2XPrz1fqHAG6T4KDafrj%2BSt0q7IW9k3IR6OTrycwoq5%2FBaEzCV9LqBK7IBqr5nOrOSexWPXYM%2FAwrsUowJFVwVYl8eUL0yqU73S11xkqGQbb64WFlNg7w4Jn4Y4cXwQ0x3l3aMwseNSqXPCLEGww%2BW0CNUfmC4viDYLdbXWWbvlEeNflrQA7jskA7ftW3Ef5emjkKaPOw4%2Bbq5PIRtaZoLqCT3pE6pDtIvu1gHf2XHXuAoD9npiVlQhYadTD89p48F%2B30gDeEzmmfo5XTM2dz2vWKGI4QVnGYwAxKGE%2FPbu7IrMr2Qa2ihJDhjfw9fF3x9dxtok2GaUFlOZP940iQYdPZlAkoRU6F9b9IALORS3tW71YHC1F5F5uY7ATQ8iptkUmrmPuUNq9uoTGlJDJqwEGLDfzKSru%2FKj1BLbOCJ7KLTLUePNK%2BPI9a2tSqJvJhVRNTqwl6FoVyS2jpJbHSUVQOpINWZ1a%2FD8eUka2Jo4L0FBZsTZLlV2vJ644aoX8F1GTGZhOz5%2Fw1cW1%2FlBaAth0xiKhlS4Ye7FSp5YIulyhUBDvKGMINkCc27%2F153CUF1dADkt0P0N6Se53fVunQ%2BCXyq35Dzrww4ua2vQY6pgFGFoiG%2F1pJ90CRUL1IgeFskUjEF3whggKkt69pi1783V31Vp5%2FwKP1LrkS6pxnOJ5A99A%2FYN95xvitagb9KfJ2EwsUPie%2B9mBcbAOslp9AZS3UqgL%2BpKj4DRUXnVqdJvpahr3hAmoFCVwvJkgVW21nWtlRoQJZaHZTSnDKcKWpc4jaWnERHSjpQ3XYmVXecLL6V2unkw7yOOJhgkUOk7Ktr4BeowQ2&X-Amz-Signature=cc314a506d8bf9d7aa015b73b8d6861c32f977fc3e7935d06054b24419b0263d&X-Amz-SignedHeaders=host&x-id=GetObject)


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

