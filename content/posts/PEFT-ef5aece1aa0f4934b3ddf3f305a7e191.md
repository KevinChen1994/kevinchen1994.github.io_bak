---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466SRYYTOCE%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250221T092515Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEKn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIAPQGMo2VqYwE3zLkRI\
  ejWVao0kUOmmXobnp2c4bIz5bAiEApEmDsrU1RluZmHem39o%2FyAWSfH0FMkAokgBqRdOXx%2FEq\
  iAQI0v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPhogxxykiw0ACe3m\
  ircA0OPo9Lke1St5dCDtev4P0inJ0APzsBSTUsTCxrI0DE1ewdWL3KiMx0wCX9dsXe0C5NBzmAiyY\
  jz0Jt0tILkhmIN%2BeXakOG1rqoatOKRrnZXhI99%2BFRSEQWneu%2BaGZ8y7BOhd13ovu%2FR%2B\
  mEtmneGpNDCRlD9EPCakhmCi31QXamGr5e%2FN1sv0ADlOdoA%2Fw5cpICZM3vMX0J8aBA5yiH%2F\
  V4%2F6niLcB76WgQy2T1866d4Wl6pKZQMzSNkaby3oZ1uoHqhSbEohNTJlRBRkIfUnp4NpxYApJPm\
  KzWTSZOhGpN7vzI%2BNIXPbL4qcLO2uGvWrOGpu9EVWmrgitcLz96MOQs57S%2BqB%2FyHycR2rRF\
  MBohzQg1Y6oc8ixMzdGOqsPPydk%2BXmJbHAw3pGs%2FSQe7ByZChsbzF1%2FELwAyblNF%2B2whg\
  ILX6dke3z625KmLE%2FRj7jZ%2F1xh0ze459NmxVLN9cU4pBn2A9YB7zDaUe3BnzUPx4IZV6%2FLv\
  Z48dCJ6T7y2pEjrZ%2BApjatONivXZPN7wafkaz7q5q0cuOFo3LssMxiVioLO9D5SgSyLZtwWBbp3\
  gddk%2FLIaw4br4rKQAcjpCKVKnyyB7QBZ3I%2B%2BUgNibmASmdu6EfHRdfMoJrWAqToMIn74L0G\
  OqUBt623dKNTyfTqyUhHw4k2WYJ7g%2ByiDaxp1Y8JLCHNRQ8pB3kRgyhE6titoeN9YOvrI53izRf\
  %2F%2FxFCnioVsXNTpciRCA9hgeDamYLOajQPFozjlfEqGWmQ%2BNzw3VuLvc8X6jxB3VK%2BUXme\
  QGAb9qA5WJ2Va6Zej9fGZkZjrImI7c%2FbU%2BLWhpfzFxiK4T9esluhta9zpDC6%2FaINVzfA2uS\
  vjyPV2ule&X-Amz-Signature=210992b6fd2fec25413c1df39ca575540a6012b3b67ca069b5d\
  5a3017cc52a8d&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4665VJJHYDV%2F20250221%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250221T092325Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEKn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIQC5%2FdOCxNuHfGGYhtVZTRsVxXaHpLm%2FZMPg2GeZt52P1QIgTF3%2BYXV%2FmydFaj\
        wUramysyNaP8xTGblu5gjAEMEiEv0qiAQI0v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAG\
        gw2Mzc0MjMxODM4MDUiDIkRGYLAqCy5kGvRayrcA7q3aPb5c%2BHnj%2FdAh1zlmG%2BHGS\
        7fiwXhbOLdH%2BY7dH9EQGQkCpP4BszQZGU9KiioXoSjeJdHP7FmW3KFaISnn0R1jD5y9hl\
        ymh3Hj5jSONs%2Bk7iGnMpUy%2FXZqhzG9kfRo8xc1LPH%2F%2BZsOxCKP2ppJ4b3bYBHCy\
        JsxWHB7uURqFkYvKidLmBhaAsr4UqZnBWBEeamyprFq4fUN%2FyL62BESXTNyTWceclzFge\
        wSqF8QQji9sI0QhrgW30qsj8hiUIHTQRQIXa5NTpqE1J4hdPjwsleo4Z6luoJGRLfx%2BqZ\
        2CYAgKBho5T8swCMnbb2F2zBqpH%2Bwp4FEca7%2BvJALwIt44sluThJ4t4aL%2FDNhz34v\
        LC8Km9V0%2FF6baB9aRFE8v6%2FjAfCUFl9EHwRPJSdPMhGE%2FfsbWRx0jSPnRZIjriDcn\
        zBvSIEMrogfire43aW9SpadHII7bj8iIsYRSLYPAY7Q%2FvMcl2xfuCax7Ar3p5nFBPHNRK\
        KnFGPEQHrpdMeGDMltDCQXguQgnBM8VdFyo8Qeb0SYBxjrU7NwqcNgHOBGrpaQni44GtwYg\
        ycnDUb1xvJ3QTVkQMZUHh%2FYgbU6jUGbosaAZEK01Ka4tCTL0mWeosQ%2FoPFMG%2F%2FJ\
        DueblZRMKT64L0GOqUB0x9QroU54I8JJRY%2FNTE4MShNn9xQP8byIA1AcGTkTlOR5zdsUX\
        kXFKQVd%2BJ0IcJCBbKVvdg9qkzbK6EgB5EFbueq5dRxktKo3BWm3%2BAwoQ6SrSQ5ESl6Z\
        oNUv9CY3lefm7X5%2F3BdZvrsG2GZKEY685n91hlzGP3Dr3TZ%2FQfwUB5ivQpBeZ8eucl5\
        IzgZ8h5kzsGzhcMc%2BfFf89rV3HalWGrOvQ6J&X-Amz-Signature=3be335666c6416d3\
        37d5e00a99f632b43be4244da3e51bbbe0a52a016faac716&X-Amz-SignedHeaders=ho\
        st&x-id=GetObject"
      expiry_time: "2025-02-21T10:23:25.318Z"
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
UPDATE_TIME: "2025-02-21T09:25:23.185Z"
EXPIRY_TIME: "2025-02-21T10:25:10.955Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663SN6WZB5%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T092511Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIEJglH15XwGORIqI3r7YWen%2BS1G6Ok9QCzonRMQDoPubAiEA3ZxW44H1pM2IP24YV8QOZOMcbr0JhXfd355kwgD7tdAqiAQI0v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPuLwI9lEKIj5had9ircA2A7xwN%2Bju%2BH%2BTyqQH4c5eTNtix5qxpIJG7MNgUvZd%2BTZ5UhdVZrJUnD%2F1vX6yyg9zUVzjmFAcCOYvq3yRQQvVs2S5lKYGb6quvr%2FANsvmfyL7oAhTDJXmvYwnozTZC5rhO0QcTBnqCshlSGw%2FgFTRNCjlzv5P6Fkcr0q9XEiAoEjJ0bXF%2Bb91EBY15pSC%2Fhyz5xcZvUhwOG50UCxb9Ng6%2BUwSYn9H2nXbEfuSKW5QsljjxtH1kE3M9MQrPz4cgIRbVI%2B9%2BIFXYObfUdwKSj63l%2Bu5ss0IyMk3wGNUkegumX6asGFGhBXNB%2F9nMdvo0%2F4zDbh%2BKVLwTJosF7hW6rmKryy4SGNby2m29Okzgf0KFLycI6i68LBf6muY8OCZN0vXfN9Qw30F7Hr4CrW0zyr6SE9AXIOfI%2FVZ6a0O8enzefsHm7gxQkEwLGTkJ7xTJuL4a6y1IsF9LSDDOxZolRzksyAzQDhv1NY5KppeIZVqpsR1l8%2BYDYvTO50g4besZJrUGjUOyEzLHBKrC1RaQs4bNy4eFyhhH%2BQTRWy0Kweepeo6YVhBnclCWNLwTbwJkZIh6EMb6iHCz6RTMOQcDacFOck%2FIvi7uGrQHr77O9MOLW5nywJy934q%2BeHjnTMJb64L0GOqUBxIJMYQ9ancUTiLv9q3%2FvRSyllstWkI2VVP1jGxIrTR3bNQnFysyITJpsA2ijJ6ZxXrLADOP8QmAwpm4X54rkqnZ1ID3MmL7Y7ye%2BX4t14Kvf1gcZU%2Fecy0c5lxP6IyLUFEXFjuwklEkYbSRdmLNfMXnjalFCW1P9ojlHCDpc7eu3fxiR29jLQyDRLui%2FLMFIDDVsKTJIj6cKN6Qd30sAUVTvVevM&X-Amz-Signature=9ce4dc8d16c2cdee679aa602dcd3603ae0365fae4a69dd16c9c0975f06f20fa3&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663SN6WZB5%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T092511Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIEJglH15XwGORIqI3r7YWen%2BS1G6Ok9QCzonRMQDoPubAiEA3ZxW44H1pM2IP24YV8QOZOMcbr0JhXfd355kwgD7tdAqiAQI0v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPuLwI9lEKIj5had9ircA2A7xwN%2Bju%2BH%2BTyqQH4c5eTNtix5qxpIJG7MNgUvZd%2BTZ5UhdVZrJUnD%2F1vX6yyg9zUVzjmFAcCOYvq3yRQQvVs2S5lKYGb6quvr%2FANsvmfyL7oAhTDJXmvYwnozTZC5rhO0QcTBnqCshlSGw%2FgFTRNCjlzv5P6Fkcr0q9XEiAoEjJ0bXF%2Bb91EBY15pSC%2Fhyz5xcZvUhwOG50UCxb9Ng6%2BUwSYn9H2nXbEfuSKW5QsljjxtH1kE3M9MQrPz4cgIRbVI%2B9%2BIFXYObfUdwKSj63l%2Bu5ss0IyMk3wGNUkegumX6asGFGhBXNB%2F9nMdvo0%2F4zDbh%2BKVLwTJosF7hW6rmKryy4SGNby2m29Okzgf0KFLycI6i68LBf6muY8OCZN0vXfN9Qw30F7Hr4CrW0zyr6SE9AXIOfI%2FVZ6a0O8enzefsHm7gxQkEwLGTkJ7xTJuL4a6y1IsF9LSDDOxZolRzksyAzQDhv1NY5KppeIZVqpsR1l8%2BYDYvTO50g4besZJrUGjUOyEzLHBKrC1RaQs4bNy4eFyhhH%2BQTRWy0Kweepeo6YVhBnclCWNLwTbwJkZIh6EMb6iHCz6RTMOQcDacFOck%2FIvi7uGrQHr77O9MOLW5nywJy934q%2BeHjnTMJb64L0GOqUBxIJMYQ9ancUTiLv9q3%2FvRSyllstWkI2VVP1jGxIrTR3bNQnFysyITJpsA2ijJ6ZxXrLADOP8QmAwpm4X54rkqnZ1ID3MmL7Y7ye%2BX4t14Kvf1gcZU%2Fecy0c5lxP6IyLUFEXFjuwklEkYbSRdmLNfMXnjalFCW1P9ojlHCDpc7eu3fxiR29jLQyDRLui%2FLMFIDDVsKTJIj6cKN6Qd30sAUVTvVevM&X-Amz-Signature=7359a90f2d989fed6410696a639a1156fd9f43f15e157a90ecd376da880f5f3c&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663SN6WZB5%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T092511Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIEJglH15XwGORIqI3r7YWen%2BS1G6Ok9QCzonRMQDoPubAiEA3ZxW44H1pM2IP24YV8QOZOMcbr0JhXfd355kwgD7tdAqiAQI0v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPuLwI9lEKIj5had9ircA2A7xwN%2Bju%2BH%2BTyqQH4c5eTNtix5qxpIJG7MNgUvZd%2BTZ5UhdVZrJUnD%2F1vX6yyg9zUVzjmFAcCOYvq3yRQQvVs2S5lKYGb6quvr%2FANsvmfyL7oAhTDJXmvYwnozTZC5rhO0QcTBnqCshlSGw%2FgFTRNCjlzv5P6Fkcr0q9XEiAoEjJ0bXF%2Bb91EBY15pSC%2Fhyz5xcZvUhwOG50UCxb9Ng6%2BUwSYn9H2nXbEfuSKW5QsljjxtH1kE3M9MQrPz4cgIRbVI%2B9%2BIFXYObfUdwKSj63l%2Bu5ss0IyMk3wGNUkegumX6asGFGhBXNB%2F9nMdvo0%2F4zDbh%2BKVLwTJosF7hW6rmKryy4SGNby2m29Okzgf0KFLycI6i68LBf6muY8OCZN0vXfN9Qw30F7Hr4CrW0zyr6SE9AXIOfI%2FVZ6a0O8enzefsHm7gxQkEwLGTkJ7xTJuL4a6y1IsF9LSDDOxZolRzksyAzQDhv1NY5KppeIZVqpsR1l8%2BYDYvTO50g4besZJrUGjUOyEzLHBKrC1RaQs4bNy4eFyhhH%2BQTRWy0Kweepeo6YVhBnclCWNLwTbwJkZIh6EMb6iHCz6RTMOQcDacFOck%2FIvi7uGrQHr77O9MOLW5nywJy934q%2BeHjnTMJb64L0GOqUBxIJMYQ9ancUTiLv9q3%2FvRSyllstWkI2VVP1jGxIrTR3bNQnFysyITJpsA2ijJ6ZxXrLADOP8QmAwpm4X54rkqnZ1ID3MmL7Y7ye%2BX4t14Kvf1gcZU%2Fecy0c5lxP6IyLUFEXFjuwklEkYbSRdmLNfMXnjalFCW1P9ojlHCDpc7eu3fxiR29jLQyDRLui%2FLMFIDDVsKTJIj6cKN6Qd30sAUVTvVevM&X-Amz-Signature=4f0339215ee85ff61b9fe5a7a0eb4d54b0b950b04041836554f53c63a2693eaa&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663SN6WZB5%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T092511Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIEJglH15XwGORIqI3r7YWen%2BS1G6Ok9QCzonRMQDoPubAiEA3ZxW44H1pM2IP24YV8QOZOMcbr0JhXfd355kwgD7tdAqiAQI0v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPuLwI9lEKIj5had9ircA2A7xwN%2Bju%2BH%2BTyqQH4c5eTNtix5qxpIJG7MNgUvZd%2BTZ5UhdVZrJUnD%2F1vX6yyg9zUVzjmFAcCOYvq3yRQQvVs2S5lKYGb6quvr%2FANsvmfyL7oAhTDJXmvYwnozTZC5rhO0QcTBnqCshlSGw%2FgFTRNCjlzv5P6Fkcr0q9XEiAoEjJ0bXF%2Bb91EBY15pSC%2Fhyz5xcZvUhwOG50UCxb9Ng6%2BUwSYn9H2nXbEfuSKW5QsljjxtH1kE3M9MQrPz4cgIRbVI%2B9%2BIFXYObfUdwKSj63l%2Bu5ss0IyMk3wGNUkegumX6asGFGhBXNB%2F9nMdvo0%2F4zDbh%2BKVLwTJosF7hW6rmKryy4SGNby2m29Okzgf0KFLycI6i68LBf6muY8OCZN0vXfN9Qw30F7Hr4CrW0zyr6SE9AXIOfI%2FVZ6a0O8enzefsHm7gxQkEwLGTkJ7xTJuL4a6y1IsF9LSDDOxZolRzksyAzQDhv1NY5KppeIZVqpsR1l8%2BYDYvTO50g4besZJrUGjUOyEzLHBKrC1RaQs4bNy4eFyhhH%2BQTRWy0Kweepeo6YVhBnclCWNLwTbwJkZIh6EMb6iHCz6RTMOQcDacFOck%2FIvi7uGrQHr77O9MOLW5nywJy934q%2BeHjnTMJb64L0GOqUBxIJMYQ9ancUTiLv9q3%2FvRSyllstWkI2VVP1jGxIrTR3bNQnFysyITJpsA2ijJ6ZxXrLADOP8QmAwpm4X54rkqnZ1ID3MmL7Y7ye%2BX4t14Kvf1gcZU%2Fecy0c5lxP6IyLUFEXFjuwklEkYbSRdmLNfMXnjalFCW1P9ojlHCDpc7eu3fxiR29jLQyDRLui%2FLMFIDDVsKTJIj6cKN6Qd30sAUVTvVevM&X-Amz-Signature=38a329d470e5cb78d71de4901587510c00446a28cd68a38cea16625c28287582&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663SN6WZB5%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T092511Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIEJglH15XwGORIqI3r7YWen%2BS1G6Ok9QCzonRMQDoPubAiEA3ZxW44H1pM2IP24YV8QOZOMcbr0JhXfd355kwgD7tdAqiAQI0v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPuLwI9lEKIj5had9ircA2A7xwN%2Bju%2BH%2BTyqQH4c5eTNtix5qxpIJG7MNgUvZd%2BTZ5UhdVZrJUnD%2F1vX6yyg9zUVzjmFAcCOYvq3yRQQvVs2S5lKYGb6quvr%2FANsvmfyL7oAhTDJXmvYwnozTZC5rhO0QcTBnqCshlSGw%2FgFTRNCjlzv5P6Fkcr0q9XEiAoEjJ0bXF%2Bb91EBY15pSC%2Fhyz5xcZvUhwOG50UCxb9Ng6%2BUwSYn9H2nXbEfuSKW5QsljjxtH1kE3M9MQrPz4cgIRbVI%2B9%2BIFXYObfUdwKSj63l%2Bu5ss0IyMk3wGNUkegumX6asGFGhBXNB%2F9nMdvo0%2F4zDbh%2BKVLwTJosF7hW6rmKryy4SGNby2m29Okzgf0KFLycI6i68LBf6muY8OCZN0vXfN9Qw30F7Hr4CrW0zyr6SE9AXIOfI%2FVZ6a0O8enzefsHm7gxQkEwLGTkJ7xTJuL4a6y1IsF9LSDDOxZolRzksyAzQDhv1NY5KppeIZVqpsR1l8%2BYDYvTO50g4besZJrUGjUOyEzLHBKrC1RaQs4bNy4eFyhhH%2BQTRWy0Kweepeo6YVhBnclCWNLwTbwJkZIh6EMb6iHCz6RTMOQcDacFOck%2FIvi7uGrQHr77O9MOLW5nywJy934q%2BeHjnTMJb64L0GOqUBxIJMYQ9ancUTiLv9q3%2FvRSyllstWkI2VVP1jGxIrTR3bNQnFysyITJpsA2ijJ6ZxXrLADOP8QmAwpm4X54rkqnZ1ID3MmL7Y7ye%2BX4t14Kvf1gcZU%2Fecy0c5lxP6IyLUFEXFjuwklEkYbSRdmLNfMXnjalFCW1P9ojlHCDpc7eu3fxiR29jLQyDRLui%2FLMFIDDVsKTJIj6cKN6Qd30sAUVTvVevM&X-Amz-Signature=dd25505f84a9a089ce28744385a05b5737b6f1b1f23e8776250beaf1bb8f7974&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SRXEE6IC%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T092512Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCh0WhXYa5HYEqTFlxpIedsthpBSQYRpqzNAL6xs9R42gIgbXnCzUVAYkiSfvfDKOGG5T40acY9%2BWUtvFvGlF%2FNRaQqiAQI0v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDO5piByJNzame%2FOQPyrcA3AjwqlY816uWTA7h1S8BrliMz7HMWLV46ZK4zkfqClGl8VmuhnBJjA3WvdI%2B7Mpo9pexLK1zwLD3G6CPY4HYqhGe6yY%2BLO0tpnrc%2BjugYdOjknw0xL6bCH7W6S8gkt4k7drWnkqweMnRFJ6ZyI4AaAltKcn1pUGfXi0zmnStRPKvH8kC8o%2BGJVHeJ%2BauDj8SKG%2Fgzv5NgS2Su75nvFqNFpEQrpqTffnFem5o5okx54ngXQq8J1cwkAGKI0cb8%2B7FVdLMy1O4Nx8GFTux3AyBcTCH5pauUZGzgXOo1QwBYo1eVmf9Yp0MjK9IuZzaCTLq82lhbM0wq9QGC9p1ewDzCqwNW%2F%2BPhrEblplnqqnq0D2%2FzjH%2BzGudHI2fgtoOOgZx2c9bcXV%2BqMORanr5ogf9BYnLH1E9N%2BDs06T3qMdhCFF5jUijb8DNcgKlQq%2FQOULFLgcXqMndSC2%2BlOCKzIFB%2BTc6StLA92fwwUoGHoZ1rTcMHRMYxXOqtiWQppl4XPxfcbmYRlynMHJVkB1GfcQuoyrSvsOSFN8mxoCadx423at4z0t4yXG%2FdRLt7HsTU81UOJ%2BFjYqyP7J5CFz%2FWvKD%2BLMfvdciz5%2BJip%2BK9fy3qG3D5arpnYaKqcv7LGeMLf74L0GOqUBHIy34WrRwLeMukwXCW5U6DYflj%2F6ARLqHmFhQwDTTD9a3cqu4qpuPzLuMWKvA00y4Ra8OyA4CTYStKFEsfLDgcmXI1thyLp%2FDvWQUoWq47T4JUmIDwvOW9u%2FmNoIpWWirVrg%2BSNJlsn7yjy1hrNdvdbF7pHLoZDtdFYJ9Rb2F51vknEaghD0iioOPz89J0VPwRy7aCDw%2FS2VqjHcxxJRn9PO6c36&X-Amz-Signature=3b85d945d3606d90fdd468ce4413f78f768d00619613240d7012c380b78a51b1&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YQPHKLMG%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T092514Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCy2QiA0r3gHATIC4Stgq8x68OySGnHt2JEpph2bu7mgwIgOYx9PfTUPIiDzxovc3PbHEM7JnbXN1qMeGTqLgmafWUqiAQI0v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDIUQTm5TjMJv%2FUswBircA7m78Db0hbQLFuORNvf64Mf7ozsoMAAoXHwM2WGzHyE4jV8RtyMuVooul08fd4LLbfIaJCpo6YaWwwsSt2h46I5ZnDQADF9f4qGRwxlQQbC4xs2ThlOF%2F7VX%2B%2Fz4UJ1wkNrrbWLRRFtBhygzPftbY%2FY81%2BciXErEhs5GAykXcjIxvD5wlCi4owWXv3%2BLJRk4yf2R8M21OOiFXHxDfwlVU5pXQYWDeI%2F%2FGLsIJtFuM%2BLtf5hl4031DU5A2MqWAy5lpIjBS6vuTupaYSrjrmVwJtDOBupp8suSUPCEt2%2FCU60xDf6o9Xdv1POoEkqJOvZXsR1aFUvtGFjiJDYkpaMfQKzlP05k%2B0IUf2h93yhiN3Y0pSKUC2uE6xu9eiOTU%2BOBp5Px7InqUmij7bkxwmGxLSil%2FGs7dCJ7vvusBesMgb65%2FZmc0sWP3LCShDHWtHQo2drk6GMLgLFsDowOWRalCtVg5liYpFSJkk%2BdQN0l2eWh9Kglg3UqQOdmzp%2B7rXE%2FccFnHAeMZOW1LqFMeVLPderLQdyuyAchnSFuTGFnBMKn4UASxJsGqiDWyFTzA5%2FF8Ap1qICCGAbjW5Ik0a%2FnQsIVXXOnf2Fx5XWHr0TPyGT8kue0LdLMohz6oM%2BtMOL64L0GOqUBT9f1EPgbCJdmOEcx9OlSuzwChQMs2suzZOcVacxteQ%2FKXUaP1dBdWOYDx7mDKpeRek7PvCHaKzZqfz30WIcDbugy73iYPo%2BF5v5ISRm1u%2B83mvxz4d8eLE7TNhIq8P3Lv1YRBIpiUZvq%2FcMJ4jDC9jQ3Jfc9h6wPrByaPf9IeLkAQ3I5v9w1KmXYilgz6nLItGMJMXzB972ZSjrJTI3x0WYKt1IS&X-Amz-Signature=da9f535ba8760a114ad73b9ca1a8f75698be54ef259affc2632dc995ff84e264&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663SN6WZB5%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T092511Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIEJglH15XwGORIqI3r7YWen%2BS1G6Ok9QCzonRMQDoPubAiEA3ZxW44H1pM2IP24YV8QOZOMcbr0JhXfd355kwgD7tdAqiAQI0v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPuLwI9lEKIj5had9ircA2A7xwN%2Bju%2BH%2BTyqQH4c5eTNtix5qxpIJG7MNgUvZd%2BTZ5UhdVZrJUnD%2F1vX6yyg9zUVzjmFAcCOYvq3yRQQvVs2S5lKYGb6quvr%2FANsvmfyL7oAhTDJXmvYwnozTZC5rhO0QcTBnqCshlSGw%2FgFTRNCjlzv5P6Fkcr0q9XEiAoEjJ0bXF%2Bb91EBY15pSC%2Fhyz5xcZvUhwOG50UCxb9Ng6%2BUwSYn9H2nXbEfuSKW5QsljjxtH1kE3M9MQrPz4cgIRbVI%2B9%2BIFXYObfUdwKSj63l%2Bu5ss0IyMk3wGNUkegumX6asGFGhBXNB%2F9nMdvo0%2F4zDbh%2BKVLwTJosF7hW6rmKryy4SGNby2m29Okzgf0KFLycI6i68LBf6muY8OCZN0vXfN9Qw30F7Hr4CrW0zyr6SE9AXIOfI%2FVZ6a0O8enzefsHm7gxQkEwLGTkJ7xTJuL4a6y1IsF9LSDDOxZolRzksyAzQDhv1NY5KppeIZVqpsR1l8%2BYDYvTO50g4besZJrUGjUOyEzLHBKrC1RaQs4bNy4eFyhhH%2BQTRWy0Kweepeo6YVhBnclCWNLwTbwJkZIh6EMb6iHCz6RTMOQcDacFOck%2FIvi7uGrQHr77O9MOLW5nywJy934q%2BeHjnTMJb64L0GOqUBxIJMYQ9ancUTiLv9q3%2FvRSyllstWkI2VVP1jGxIrTR3bNQnFysyITJpsA2ijJ6ZxXrLADOP8QmAwpm4X54rkqnZ1ID3MmL7Y7ye%2BX4t14Kvf1gcZU%2Fecy0c5lxP6IyLUFEXFjuwklEkYbSRdmLNfMXnjalFCW1P9ojlHCDpc7eu3fxiR29jLQyDRLui%2FLMFIDDVsKTJIj6cKN6Qd30sAUVTvVevM&X-Amz-Signature=e2ece7210a9683440da31b21586cc7f2b89b4c8887f961193f4b0a3c1ced75cd&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663SN6WZB5%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T092511Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIEJglH15XwGORIqI3r7YWen%2BS1G6Ok9QCzonRMQDoPubAiEA3ZxW44H1pM2IP24YV8QOZOMcbr0JhXfd355kwgD7tdAqiAQI0v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPuLwI9lEKIj5had9ircA2A7xwN%2Bju%2BH%2BTyqQH4c5eTNtix5qxpIJG7MNgUvZd%2BTZ5UhdVZrJUnD%2F1vX6yyg9zUVzjmFAcCOYvq3yRQQvVs2S5lKYGb6quvr%2FANsvmfyL7oAhTDJXmvYwnozTZC5rhO0QcTBnqCshlSGw%2FgFTRNCjlzv5P6Fkcr0q9XEiAoEjJ0bXF%2Bb91EBY15pSC%2Fhyz5xcZvUhwOG50UCxb9Ng6%2BUwSYn9H2nXbEfuSKW5QsljjxtH1kE3M9MQrPz4cgIRbVI%2B9%2BIFXYObfUdwKSj63l%2Bu5ss0IyMk3wGNUkegumX6asGFGhBXNB%2F9nMdvo0%2F4zDbh%2BKVLwTJosF7hW6rmKryy4SGNby2m29Okzgf0KFLycI6i68LBf6muY8OCZN0vXfN9Qw30F7Hr4CrW0zyr6SE9AXIOfI%2FVZ6a0O8enzefsHm7gxQkEwLGTkJ7xTJuL4a6y1IsF9LSDDOxZolRzksyAzQDhv1NY5KppeIZVqpsR1l8%2BYDYvTO50g4besZJrUGjUOyEzLHBKrC1RaQs4bNy4eFyhhH%2BQTRWy0Kweepeo6YVhBnclCWNLwTbwJkZIh6EMb6iHCz6RTMOQcDacFOck%2FIvi7uGrQHr77O9MOLW5nywJy934q%2BeHjnTMJb64L0GOqUBxIJMYQ9ancUTiLv9q3%2FvRSyllstWkI2VVP1jGxIrTR3bNQnFysyITJpsA2ijJ6ZxXrLADOP8QmAwpm4X54rkqnZ1ID3MmL7Y7ye%2BX4t14Kvf1gcZU%2Fecy0c5lxP6IyLUFEXFjuwklEkYbSRdmLNfMXnjalFCW1P9ojlHCDpc7eu3fxiR29jLQyDRLui%2FLMFIDDVsKTJIj6cKN6Qd30sAUVTvVevM&X-Amz-Signature=2be4c3d94697651f75015384b369bbee05aadd52c4fc0955318d18770ea8b561&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663SN6WZB5%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T092511Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIEJglH15XwGORIqI3r7YWen%2BS1G6Ok9QCzonRMQDoPubAiEA3ZxW44H1pM2IP24YV8QOZOMcbr0JhXfd355kwgD7tdAqiAQI0v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPuLwI9lEKIj5had9ircA2A7xwN%2Bju%2BH%2BTyqQH4c5eTNtix5qxpIJG7MNgUvZd%2BTZ5UhdVZrJUnD%2F1vX6yyg9zUVzjmFAcCOYvq3yRQQvVs2S5lKYGb6quvr%2FANsvmfyL7oAhTDJXmvYwnozTZC5rhO0QcTBnqCshlSGw%2FgFTRNCjlzv5P6Fkcr0q9XEiAoEjJ0bXF%2Bb91EBY15pSC%2Fhyz5xcZvUhwOG50UCxb9Ng6%2BUwSYn9H2nXbEfuSKW5QsljjxtH1kE3M9MQrPz4cgIRbVI%2B9%2BIFXYObfUdwKSj63l%2Bu5ss0IyMk3wGNUkegumX6asGFGhBXNB%2F9nMdvo0%2F4zDbh%2BKVLwTJosF7hW6rmKryy4SGNby2m29Okzgf0KFLycI6i68LBf6muY8OCZN0vXfN9Qw30F7Hr4CrW0zyr6SE9AXIOfI%2FVZ6a0O8enzefsHm7gxQkEwLGTkJ7xTJuL4a6y1IsF9LSDDOxZolRzksyAzQDhv1NY5KppeIZVqpsR1l8%2BYDYvTO50g4besZJrUGjUOyEzLHBKrC1RaQs4bNy4eFyhhH%2BQTRWy0Kweepeo6YVhBnclCWNLwTbwJkZIh6EMb6iHCz6RTMOQcDacFOck%2FIvi7uGrQHr77O9MOLW5nywJy934q%2BeHjnTMJb64L0GOqUBxIJMYQ9ancUTiLv9q3%2FvRSyllstWkI2VVP1jGxIrTR3bNQnFysyITJpsA2ijJ6ZxXrLADOP8QmAwpm4X54rkqnZ1ID3MmL7Y7ye%2BX4t14Kvf1gcZU%2Fecy0c5lxP6IyLUFEXFjuwklEkYbSRdmLNfMXnjalFCW1P9ojlHCDpc7eu3fxiR29jLQyDRLui%2FLMFIDDVsKTJIj6cKN6Qd30sAUVTvVevM&X-Amz-Signature=2b50a7f3763daf49a142cb85ac46f3ddcfbeec6080425da2e0cd3e1a87f670ba&X-Amz-SignedHeaders=host&x-id=GetObject)


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

