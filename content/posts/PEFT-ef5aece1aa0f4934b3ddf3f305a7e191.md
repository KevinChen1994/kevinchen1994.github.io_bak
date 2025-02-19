---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4665IYC34BM%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250219T111956Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEHsaCXVzLXdlc3QtMiJHMEUCIQCsq7I8QDBGsREvMLxTgUncMZlMxNb%2FCj02dhh7szWIPgIga\
  4u0HU2VM3YKm39ou5vfWUraP5iL54FWtf5kKU6kV94qiAQIpP%2F%2F%2F%2F%2F%2F%2F%2F%2F%\
  2FARAAGgw2Mzc0MjMxODM4MDUiDPAV208Ystq%2BEvtgiyrcAyz%2BfKvHtKiL6PxXOy8cMqqit94\
  79DmfExX4%2Bm6iWq2HGqpIWXlP45qSl9TdwyD%2FFFODBoe0Zu3NENvGpyiRRGi6UmUkD61uStKx\
  uxLC8NsabaopC54vi2M9REwMSCLDGmyo4JQrzGrN1bSbYe5lKA5ZXeXSgKwaRCmckK3Hjpies%2Bu\
  3GOuo8EAQ6HLrq5GEnLWSX9giFho410S%2B0T8e0Mi%2FlWhlxd8Q%2FqIqEYpX8ZDTgw8jS2pqZr\
  gpYK4HCQAgPHpg4fOtaupum39BEJ8FkTFLVkcPGy5LqfeFFolrRKe9VUgYntcJFSYON5II6h2Sh5M\
  bXw5hQi5ueyRXUxkN2fK4v1tp4lTAmp1UBoFWmUdIbccpCfbVWRdWiFJhcBHICz%2FgNCSX5a3bJg\
  EF8wM18%2F2zoGodSGbP%2BW7gYNPzd3MT2Yi9NrtQtBq2hkCwPALK2v%2BFO8u55rwEA3PLbVvMf\
  mKDBQ0itZTUAyFhN%2BS%2FAjAday2ckp5HsnpnlnpZIyjovMFDz8hpmf6XLqop%2BP1xzymA%2Bt\
  OeC01LOJBv3rEQ7sd1fWQENIHTTXnID%2B7%2B7JwDiqGgKTiPSoU5eqVE7QTMklTKircEtP8YxRR\
  Sul6SntZJ%2Fnk7yzyHsRms301lMPX61r0GOqUBHD6mY1Zcj9F4dO2jduXLm9U4%2Fhze6HHZ84um\
  hec19w4iU4%2Fr9FVl2DQhWQhpjH4KbhO9y9pq%2BU9844SLOQn3OGukQ92tbjnuoKpv2yUWM3w25\
  9zVCrSxG%2BR5Hmnfi7KIvGWOKF1DyxpkQJtqNz6G26jnoOgZJjfdT9oaUQKfMD5VNS8ayv6TOSWs\
  5ctCCBwXRasZJW0r7Q9pnx4s0B2Uf5z2EC7W&X-Amz-Signature=686b3bdddb16038034d322a0\
  51de76228a1ab4441aa1b95221ac3c2b80d0098d&X-Amz-SignedHeaders=host&x-id=GetObj\
  ect"
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
        redential=ASIAZI2LB4666KTHR3F3%2F20250219%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250219T111827Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEHoaCXVzLXdlc3QtMiJIMEYCIQDprn3CI6bTXGCCHfP5f6xBL313IMF\
        zOEx9%2F62AzLxcpAIhAI9GL8XjbrO8Mhw2iqu4mwQZtSLZTwIi5qvAyeOZHhWpKogECKP%\
        2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyzW8n9oMPHKwoK4Wg\
        q3AP0QkAV3T6TYpgjUBoVk6yT1FQBUAVNaW7HOQTWAwW5qBPnNXTaAWQwySnLZ3mKmJdQIk\
        5YK8svFXXYsFiwwNKFYaqpz%2BY%2F3SP5ORMqEKLDqZ4wG%2FDRiLA%2FIeNa6ZgO3jhbR\
        b%2F%2Bl8zAHDW09dRgRTI7cYsxtNZFupxkNdV%2BKe8cQP4FWKQxOHRAvCUmraZzPFw0qq\
        5DHYG29ZMAdW9myqSzki%2FCG9QPGNvjR3rIRRgHonVwzxebpo4wxAkfl63Gg1ZDCQZrs%2\
        FifxuKNxFUaPjTbVIku6mcBjGY%2BTrlzaWK1o2jfZJMiEmh7Lxo8NXFNUOP26%2B88Ch%2\
        FU7PrVjPuysWiIU1UdlIyJAA%2BRoyu2h5ZAYfCwTgc1%2FdpenPH4sBrQFbi2acABZ2vTH\
        AQ4d6BCxVG4W8YwLzT%2FLVHfEw7jiMuCEym%2F7BoTtDKlnJN1%2FRaz%2FLD2fwXjT9oQ\
        8rFnDUY2fwPLioHcL8C4BV%2FXvKs1u5tnBZ8QAELrFSETkzGIoPmvmdXfKktcDTbNSG8Pp\
        FGUpL39n3gkJS%2BudgQTRd1GAZjpz2yYFSxKSGDrsaPft5u%2Bftt1E8SbXWhWEsYW%2F8\
        aN7xkbKVsPRiOCT1g%2B68d4b4QMDkRWLvDkqKdYX5C3gzC13Na9BjqkAUnDx9BrOnaBsQQ\
        GrUQ6i5aMIhM8%2Bo4M%2BVayXOsVDi513ysowZzAj4Ym8aGf8YZhaTQmMHsZZuVskxSZ2P\
        4oRP2xxxSgIR61l5SIJvUcnzn4cJbMuMlAAM%2FqWGZPyHE27uQip5lBJBgAih0m3oV4XJO\
        nPQTjM8BbAszWQYMqq%2F1CPJR%2FOfoYyPw4gSJaUmS0C6aYu4ppx5W9nEbPDdefp9gXPb\
        kb&X-Amz-Signature=b1a29ab599feed6b477ab74fedc81cd03696e26cf43ea7d70a14\
        fdb20cb6bd6c&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-19T12:18:27.893Z"
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
UPDATE_TIME: "2025-02-19T11:20:02.142Z"
EXPIRY_TIME: "2025-02-19T12:19:51.914Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z72IJOKK%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T111952Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJGMEQCIEXVHoHp6lSlZudyCLarDHayPfF9vbFQsHc0C54oYtdeAiAGuaoUxQa5ETPTBj6trKhQYt%2FrIaHQUK1wZmbLXVJcqCqIBAik%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMAVJM7Q%2Bam9sTI9AXKtwDmwZbtC5RvkculFmSdNm4rtn26WFmujdAnspiV28E7qMXJG9nF2k6RYCgGet03Fnzh41mjT%2Ba9UJnidwykftH26lQPnBRUtthyCBhJWlbtwZfYlz8tD6yHPFMyUFOAuAdEGsFbYqYHFos4I4EQG5WDcuRyHkOc7Wm2Htq7pEUJR6AX1g8codFow%2F5B%2BIGj3XBSnkZvFN%2FD9KF2D9kWPygS6S0%2Bso2%2B92DlVEgr1JzOZzY9AYFtK7%2BO8xQLK3%2FOFCkYPduKANopmjyTBz4RwIFxdOJABJ7z%2Boa0K0MXiLFOw%2BBuWS6vU1feR61z0%2FrsVqrnOz5j0M6z6%2FhhZ%2BzkzU7ld5kDDdVkAdsl5zk%2F0zfRSMAmQY33f%2B3FMn5LX3lDO8eKoLwqFZNUlnTX0IM2DbXhb%2BFYfjGvDoBUAVeLJ3oGSE4Hrxvp7TQmcGg2NMilcoupdTJTOVBvgu7IsdBdp8RK%2F5%2FYIQMZtbY7F4HNHHxdex1zYUhe%2FDjPBYNfEmmi4PxtlJQely4JKfxeSPWEwfDr4R9%2FcB4GYY50j6dFVn%2B7V9XFdEN7pFfkfV8UUuXLeT0VppceoPBrB4ZGpCpHhe7Z60FjuxbVEGeBtBLOxVVQQ9BpKLWqM3e8vlzNHEwnvvWvQY6pgFctddVtHOmZPED1XteKGTxPVaXPfx9kImYCSzJw7D%2BRz33urEet3%2BKorNlaKUQCiIeKGfmKSCKO0%2FowCc%2FwK0eEJz1nw2%2BHRaRazpxmU4s4AkJJrPrpfJO%2BmwRG3t9VK1zAUkNzVdW551yKxiWMj%2F6ZETvsvn2K%2B8LxYDC2QeP%2FjCeUhWQ4e9TfxdoiCB0ccsW0VDdP582ySaL%2BKVR55B1PHiqzzn3&X-Amz-Signature=bfa2def6e9b943c4cf43d83e16b6cfef81ee02ae7ff0ed23fc1f5084bc012964&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z72IJOKK%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T111952Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJGMEQCIEXVHoHp6lSlZudyCLarDHayPfF9vbFQsHc0C54oYtdeAiAGuaoUxQa5ETPTBj6trKhQYt%2FrIaHQUK1wZmbLXVJcqCqIBAik%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMAVJM7Q%2Bam9sTI9AXKtwDmwZbtC5RvkculFmSdNm4rtn26WFmujdAnspiV28E7qMXJG9nF2k6RYCgGet03Fnzh41mjT%2Ba9UJnidwykftH26lQPnBRUtthyCBhJWlbtwZfYlz8tD6yHPFMyUFOAuAdEGsFbYqYHFos4I4EQG5WDcuRyHkOc7Wm2Htq7pEUJR6AX1g8codFow%2F5B%2BIGj3XBSnkZvFN%2FD9KF2D9kWPygS6S0%2Bso2%2B92DlVEgr1JzOZzY9AYFtK7%2BO8xQLK3%2FOFCkYPduKANopmjyTBz4RwIFxdOJABJ7z%2Boa0K0MXiLFOw%2BBuWS6vU1feR61z0%2FrsVqrnOz5j0M6z6%2FhhZ%2BzkzU7ld5kDDdVkAdsl5zk%2F0zfRSMAmQY33f%2B3FMn5LX3lDO8eKoLwqFZNUlnTX0IM2DbXhb%2BFYfjGvDoBUAVeLJ3oGSE4Hrxvp7TQmcGg2NMilcoupdTJTOVBvgu7IsdBdp8RK%2F5%2FYIQMZtbY7F4HNHHxdex1zYUhe%2FDjPBYNfEmmi4PxtlJQely4JKfxeSPWEwfDr4R9%2FcB4GYY50j6dFVn%2B7V9XFdEN7pFfkfV8UUuXLeT0VppceoPBrB4ZGpCpHhe7Z60FjuxbVEGeBtBLOxVVQQ9BpKLWqM3e8vlzNHEwnvvWvQY6pgFctddVtHOmZPED1XteKGTxPVaXPfx9kImYCSzJw7D%2BRz33urEet3%2BKorNlaKUQCiIeKGfmKSCKO0%2FowCc%2FwK0eEJz1nw2%2BHRaRazpxmU4s4AkJJrPrpfJO%2BmwRG3t9VK1zAUkNzVdW551yKxiWMj%2F6ZETvsvn2K%2B8LxYDC2QeP%2FjCeUhWQ4e9TfxdoiCB0ccsW0VDdP582ySaL%2BKVR55B1PHiqzzn3&X-Amz-Signature=cf1fe8f9c2914b0a816dcc983a0d56b8bee9a85c59bd58460749eec6dbc78de6&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z72IJOKK%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T111952Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJGMEQCIEXVHoHp6lSlZudyCLarDHayPfF9vbFQsHc0C54oYtdeAiAGuaoUxQa5ETPTBj6trKhQYt%2FrIaHQUK1wZmbLXVJcqCqIBAik%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMAVJM7Q%2Bam9sTI9AXKtwDmwZbtC5RvkculFmSdNm4rtn26WFmujdAnspiV28E7qMXJG9nF2k6RYCgGet03Fnzh41mjT%2Ba9UJnidwykftH26lQPnBRUtthyCBhJWlbtwZfYlz8tD6yHPFMyUFOAuAdEGsFbYqYHFos4I4EQG5WDcuRyHkOc7Wm2Htq7pEUJR6AX1g8codFow%2F5B%2BIGj3XBSnkZvFN%2FD9KF2D9kWPygS6S0%2Bso2%2B92DlVEgr1JzOZzY9AYFtK7%2BO8xQLK3%2FOFCkYPduKANopmjyTBz4RwIFxdOJABJ7z%2Boa0K0MXiLFOw%2BBuWS6vU1feR61z0%2FrsVqrnOz5j0M6z6%2FhhZ%2BzkzU7ld5kDDdVkAdsl5zk%2F0zfRSMAmQY33f%2B3FMn5LX3lDO8eKoLwqFZNUlnTX0IM2DbXhb%2BFYfjGvDoBUAVeLJ3oGSE4Hrxvp7TQmcGg2NMilcoupdTJTOVBvgu7IsdBdp8RK%2F5%2FYIQMZtbY7F4HNHHxdex1zYUhe%2FDjPBYNfEmmi4PxtlJQely4JKfxeSPWEwfDr4R9%2FcB4GYY50j6dFVn%2B7V9XFdEN7pFfkfV8UUuXLeT0VppceoPBrB4ZGpCpHhe7Z60FjuxbVEGeBtBLOxVVQQ9BpKLWqM3e8vlzNHEwnvvWvQY6pgFctddVtHOmZPED1XteKGTxPVaXPfx9kImYCSzJw7D%2BRz33urEet3%2BKorNlaKUQCiIeKGfmKSCKO0%2FowCc%2FwK0eEJz1nw2%2BHRaRazpxmU4s4AkJJrPrpfJO%2BmwRG3t9VK1zAUkNzVdW551yKxiWMj%2F6ZETvsvn2K%2B8LxYDC2QeP%2FjCeUhWQ4e9TfxdoiCB0ccsW0VDdP582ySaL%2BKVR55B1PHiqzzn3&X-Amz-Signature=d4f6f5416a1a94d037b9929867aeddfc580f32cefb7301a214a49a0e888f4bd4&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z72IJOKK%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T111952Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJGMEQCIEXVHoHp6lSlZudyCLarDHayPfF9vbFQsHc0C54oYtdeAiAGuaoUxQa5ETPTBj6trKhQYt%2FrIaHQUK1wZmbLXVJcqCqIBAik%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMAVJM7Q%2Bam9sTI9AXKtwDmwZbtC5RvkculFmSdNm4rtn26WFmujdAnspiV28E7qMXJG9nF2k6RYCgGet03Fnzh41mjT%2Ba9UJnidwykftH26lQPnBRUtthyCBhJWlbtwZfYlz8tD6yHPFMyUFOAuAdEGsFbYqYHFos4I4EQG5WDcuRyHkOc7Wm2Htq7pEUJR6AX1g8codFow%2F5B%2BIGj3XBSnkZvFN%2FD9KF2D9kWPygS6S0%2Bso2%2B92DlVEgr1JzOZzY9AYFtK7%2BO8xQLK3%2FOFCkYPduKANopmjyTBz4RwIFxdOJABJ7z%2Boa0K0MXiLFOw%2BBuWS6vU1feR61z0%2FrsVqrnOz5j0M6z6%2FhhZ%2BzkzU7ld5kDDdVkAdsl5zk%2F0zfRSMAmQY33f%2B3FMn5LX3lDO8eKoLwqFZNUlnTX0IM2DbXhb%2BFYfjGvDoBUAVeLJ3oGSE4Hrxvp7TQmcGg2NMilcoupdTJTOVBvgu7IsdBdp8RK%2F5%2FYIQMZtbY7F4HNHHxdex1zYUhe%2FDjPBYNfEmmi4PxtlJQely4JKfxeSPWEwfDr4R9%2FcB4GYY50j6dFVn%2B7V9XFdEN7pFfkfV8UUuXLeT0VppceoPBrB4ZGpCpHhe7Z60FjuxbVEGeBtBLOxVVQQ9BpKLWqM3e8vlzNHEwnvvWvQY6pgFctddVtHOmZPED1XteKGTxPVaXPfx9kImYCSzJw7D%2BRz33urEet3%2BKorNlaKUQCiIeKGfmKSCKO0%2FowCc%2FwK0eEJz1nw2%2BHRaRazpxmU4s4AkJJrPrpfJO%2BmwRG3t9VK1zAUkNzVdW551yKxiWMj%2F6ZETvsvn2K%2B8LxYDC2QeP%2FjCeUhWQ4e9TfxdoiCB0ccsW0VDdP582ySaL%2BKVR55B1PHiqzzn3&X-Amz-Signature=777398673ed5e293bd52901a06f685f19fcf21fd506490bbc0ef29c7e1587e09&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z72IJOKK%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T111952Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJGMEQCIEXVHoHp6lSlZudyCLarDHayPfF9vbFQsHc0C54oYtdeAiAGuaoUxQa5ETPTBj6trKhQYt%2FrIaHQUK1wZmbLXVJcqCqIBAik%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMAVJM7Q%2Bam9sTI9AXKtwDmwZbtC5RvkculFmSdNm4rtn26WFmujdAnspiV28E7qMXJG9nF2k6RYCgGet03Fnzh41mjT%2Ba9UJnidwykftH26lQPnBRUtthyCBhJWlbtwZfYlz8tD6yHPFMyUFOAuAdEGsFbYqYHFos4I4EQG5WDcuRyHkOc7Wm2Htq7pEUJR6AX1g8codFow%2F5B%2BIGj3XBSnkZvFN%2FD9KF2D9kWPygS6S0%2Bso2%2B92DlVEgr1JzOZzY9AYFtK7%2BO8xQLK3%2FOFCkYPduKANopmjyTBz4RwIFxdOJABJ7z%2Boa0K0MXiLFOw%2BBuWS6vU1feR61z0%2FrsVqrnOz5j0M6z6%2FhhZ%2BzkzU7ld5kDDdVkAdsl5zk%2F0zfRSMAmQY33f%2B3FMn5LX3lDO8eKoLwqFZNUlnTX0IM2DbXhb%2BFYfjGvDoBUAVeLJ3oGSE4Hrxvp7TQmcGg2NMilcoupdTJTOVBvgu7IsdBdp8RK%2F5%2FYIQMZtbY7F4HNHHxdex1zYUhe%2FDjPBYNfEmmi4PxtlJQely4JKfxeSPWEwfDr4R9%2FcB4GYY50j6dFVn%2B7V9XFdEN7pFfkfV8UUuXLeT0VppceoPBrB4ZGpCpHhe7Z60FjuxbVEGeBtBLOxVVQQ9BpKLWqM3e8vlzNHEwnvvWvQY6pgFctddVtHOmZPED1XteKGTxPVaXPfx9kImYCSzJw7D%2BRz33urEet3%2BKorNlaKUQCiIeKGfmKSCKO0%2FowCc%2FwK0eEJz1nw2%2BHRaRazpxmU4s4AkJJrPrpfJO%2BmwRG3t9VK1zAUkNzVdW551yKxiWMj%2F6ZETvsvn2K%2B8LxYDC2QeP%2FjCeUhWQ4e9TfxdoiCB0ccsW0VDdP582ySaL%2BKVR55B1PHiqzzn3&X-Amz-Signature=f0bd2d74b227f1679999823bd36565145bfbe5e80c003137ea841cefb1738b29&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666ONBSQ2N%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T111953Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJHMEUCIBJgZ07irlZAP55UFEBdZw32eseip7dj3XQYnJgWn53UAiEAw3qluFjVz1%2FvH8%2BPajIyFkhBPqAAtWwMK7o72VnDaaYqiAQIpP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDINoLJ91Xeqs1V00BCrcA4e2SEvOstVv3WEI0eDQxRz58vZikSDPNJa4V09Wz88KvMr1z30QZZoRwFbpOeirZRiJDxTNg3f130FV4BenTrvto1cl8C%2B9d9y6HO66yM9v8SQRqfLTaFXpUC7twfm%2FvaWfJ0Y6l2v9gcg9yj6yXz2HCqZvoZZy9RrmTDwMnuzIWjtLo29BcVmAbWTCm4XLBPkB0fKc5O%2BVHSW6%2BeFzxq8DYK0mlf5%2BlsTodCJPRu9ytp8W%2FNDX7xX70w3xSK%2Bt0T5XcAafc35oOskhLOY6e7Qv2C783MKHIEWVTckEg78LWT6YMwETtjy0waPqlwFgOEN3HZWi%2F7BHxndwEepM1%2Fpv%2Fz%2B0NHJsj3UJD4nSbXIMwPm44vYQVyue9kE4NRSVw8TykkukynycaJrGuAEpujKBYF7vY9QWwXIXxiFj%2BkBLpgxbiJbz8Km2Zv0FFt%2BHDZ1p5CZ00asQvYXLoBYOauIW6YAhQnFm7jyMM7gaV8xAKAZqO7fDYTejRErozJoRD8UuZOz3tzyp8fAU0Er0gwRYEERRJBLaGVwaBRcUK94O0TLx%2Fp75PX3J2C6bCVburC0J%2B1Yk%2BCLohOLjfj%2Fa7HnaA3OhFyNTkrLbOcSw1MCz9koa%2B%2FDzcgrpRSBPMKD71r0GOqUBkCZauYm81BB5V5Bm2%2FcbR2t5xOKUCJaemYrFWHPXcVR%2B2v8DANGz4cUHynuk5OwHGc5J4PAT0ln%2FmafDWM4PGPzryWXoMAN7nNTUHaDEwu7QP0zTvumj8h9f58a2iADCYZUmeE0VIgAilAdjMAKzqiLoLKsRaijVc%2BOh8bhEfMHIfyDw%2B1%2Fm5ImnnanZIcyEKbU66KJSfVV7TM3lZXbbtXhzhX9I&X-Amz-Signature=c0743ec1401fe05fd191980ac181b5c5aaa94ace4858086f06f23a72d39d3ca6&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UOL6GCRH%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T111954Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJIMEYCIQCCeqFNL8sT%2FP5wbVn9R6nupwrgfOmrZQS7qiNgF%2FSy0AIhAK%2BgU209Tv3AWI6TYdbAkSO9fIFPaLIVSc2TXP6mkMkXKogECKT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyltnETEO0cobKphXsq3AMQZEi2lvPBADJd04hKlG33GyL%2Br24Hl9aartSXcIwGiHyLFjMx6aVAJ%2FFAeRO37sSXw1vGDBws1hfsPk2gVeA1i8u8nPWzX9uT%2FWh6VbMkKByIH6otvqFHVJaIP8Aq3kzZbc1S6ZyvnVjRO9pmfcGHLtnQ23wUxT6vTzZ0Fe9LO%2F4G6dRB3YFtiNKOkniiJJU248RUxUS7B43DY%2FRhnLFn%2BMHrN5aaIL0kMnwxUw5SyIY3s3sdoNe%2BNO8F46RoPwPG6wC4PeIoOYDCHi3GDb5y5D3ykBDV7hFfpkKdIBSkqIC44M7pSg20sLEQhH5oR9iO6SKpsC4aIOgJpkDMoZ7%2FoUxPRxHD17OII5mrJ244U%2FCliCLMPzYFNCYdhvt6GmBTmlon22o7uy%2BMg5Y4iCVI8u9d%2FLiIOfVV%2FJuknzziqOPr7Ih5mC1kiVB6im0rfd%2B%2BT8gbGINhI9XBwZBK%2Bci1vmBXvdQp5YFPB6z2qvgerSwUpemlJJucTq%2F8w6VuPDknWBaqFgJHaV2GeJNoPp%2F9woXqyb8wGYQ%2FsE8XMtsWnXQuo8yxomASHtU84OEJxFhLhvVPu9a6GS5jX4waqEVUaGQ%2FOy3F5P0br8Yi7%2Bmm2tj1z1KlYmMBOEkY%2FDCL%2B9a9BjqkAYCYk2rL2WBAneLhyHGGghfcmmZ7wnPC88hM2KWjJS48v4iY0wOWVbRrsOZ%2BHcSicpGILoMfG9OkeAWeG1SkhgXF07GU2e1h5X%2FDDQ255EiUVG0QCa68QA%2BpylN9B%2F2MvbRUKkJQvkI2gEDfgD619VfV93Hmbz68C3A%2BNc7%2FavEOpXdqM2vfPzHTbRfBBBlXt3GVf1AefPF7C6FHwhWF%2B72LRtLw&X-Amz-Signature=ec94a97c6cd0df07645cef6ce1094b3b22d923c727a0e07f418aa0048906e11a&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z72IJOKK%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T111952Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJGMEQCIEXVHoHp6lSlZudyCLarDHayPfF9vbFQsHc0C54oYtdeAiAGuaoUxQa5ETPTBj6trKhQYt%2FrIaHQUK1wZmbLXVJcqCqIBAik%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMAVJM7Q%2Bam9sTI9AXKtwDmwZbtC5RvkculFmSdNm4rtn26WFmujdAnspiV28E7qMXJG9nF2k6RYCgGet03Fnzh41mjT%2Ba9UJnidwykftH26lQPnBRUtthyCBhJWlbtwZfYlz8tD6yHPFMyUFOAuAdEGsFbYqYHFos4I4EQG5WDcuRyHkOc7Wm2Htq7pEUJR6AX1g8codFow%2F5B%2BIGj3XBSnkZvFN%2FD9KF2D9kWPygS6S0%2Bso2%2B92DlVEgr1JzOZzY9AYFtK7%2BO8xQLK3%2FOFCkYPduKANopmjyTBz4RwIFxdOJABJ7z%2Boa0K0MXiLFOw%2BBuWS6vU1feR61z0%2FrsVqrnOz5j0M6z6%2FhhZ%2BzkzU7ld5kDDdVkAdsl5zk%2F0zfRSMAmQY33f%2B3FMn5LX3lDO8eKoLwqFZNUlnTX0IM2DbXhb%2BFYfjGvDoBUAVeLJ3oGSE4Hrxvp7TQmcGg2NMilcoupdTJTOVBvgu7IsdBdp8RK%2F5%2FYIQMZtbY7F4HNHHxdex1zYUhe%2FDjPBYNfEmmi4PxtlJQely4JKfxeSPWEwfDr4R9%2FcB4GYY50j6dFVn%2B7V9XFdEN7pFfkfV8UUuXLeT0VppceoPBrB4ZGpCpHhe7Z60FjuxbVEGeBtBLOxVVQQ9BpKLWqM3e8vlzNHEwnvvWvQY6pgFctddVtHOmZPED1XteKGTxPVaXPfx9kImYCSzJw7D%2BRz33urEet3%2BKorNlaKUQCiIeKGfmKSCKO0%2FowCc%2FwK0eEJz1nw2%2BHRaRazpxmU4s4AkJJrPrpfJO%2BmwRG3t9VK1zAUkNzVdW551yKxiWMj%2F6ZETvsvn2K%2B8LxYDC2QeP%2FjCeUhWQ4e9TfxdoiCB0ccsW0VDdP582ySaL%2BKVR55B1PHiqzzn3&X-Amz-Signature=411b3393fb775659cbed7ba77446c37034f670349a4586adb81d7b760eec22bb&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z72IJOKK%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T111952Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJGMEQCIEXVHoHp6lSlZudyCLarDHayPfF9vbFQsHc0C54oYtdeAiAGuaoUxQa5ETPTBj6trKhQYt%2FrIaHQUK1wZmbLXVJcqCqIBAik%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMAVJM7Q%2Bam9sTI9AXKtwDmwZbtC5RvkculFmSdNm4rtn26WFmujdAnspiV28E7qMXJG9nF2k6RYCgGet03Fnzh41mjT%2Ba9UJnidwykftH26lQPnBRUtthyCBhJWlbtwZfYlz8tD6yHPFMyUFOAuAdEGsFbYqYHFos4I4EQG5WDcuRyHkOc7Wm2Htq7pEUJR6AX1g8codFow%2F5B%2BIGj3XBSnkZvFN%2FD9KF2D9kWPygS6S0%2Bso2%2B92DlVEgr1JzOZzY9AYFtK7%2BO8xQLK3%2FOFCkYPduKANopmjyTBz4RwIFxdOJABJ7z%2Boa0K0MXiLFOw%2BBuWS6vU1feR61z0%2FrsVqrnOz5j0M6z6%2FhhZ%2BzkzU7ld5kDDdVkAdsl5zk%2F0zfRSMAmQY33f%2B3FMn5LX3lDO8eKoLwqFZNUlnTX0IM2DbXhb%2BFYfjGvDoBUAVeLJ3oGSE4Hrxvp7TQmcGg2NMilcoupdTJTOVBvgu7IsdBdp8RK%2F5%2FYIQMZtbY7F4HNHHxdex1zYUhe%2FDjPBYNfEmmi4PxtlJQely4JKfxeSPWEwfDr4R9%2FcB4GYY50j6dFVn%2B7V9XFdEN7pFfkfV8UUuXLeT0VppceoPBrB4ZGpCpHhe7Z60FjuxbVEGeBtBLOxVVQQ9BpKLWqM3e8vlzNHEwnvvWvQY6pgFctddVtHOmZPED1XteKGTxPVaXPfx9kImYCSzJw7D%2BRz33urEet3%2BKorNlaKUQCiIeKGfmKSCKO0%2FowCc%2FwK0eEJz1nw2%2BHRaRazpxmU4s4AkJJrPrpfJO%2BmwRG3t9VK1zAUkNzVdW551yKxiWMj%2F6ZETvsvn2K%2B8LxYDC2QeP%2FjCeUhWQ4e9TfxdoiCB0ccsW0VDdP582ySaL%2BKVR55B1PHiqzzn3&X-Amz-Signature=2cb286b47492c731c5955d7b77618995c0a1595d0a0e894b6a6f09f30557e845&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z72IJOKK%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T111952Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJGMEQCIEXVHoHp6lSlZudyCLarDHayPfF9vbFQsHc0C54oYtdeAiAGuaoUxQa5ETPTBj6trKhQYt%2FrIaHQUK1wZmbLXVJcqCqIBAik%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMAVJM7Q%2Bam9sTI9AXKtwDmwZbtC5RvkculFmSdNm4rtn26WFmujdAnspiV28E7qMXJG9nF2k6RYCgGet03Fnzh41mjT%2Ba9UJnidwykftH26lQPnBRUtthyCBhJWlbtwZfYlz8tD6yHPFMyUFOAuAdEGsFbYqYHFos4I4EQG5WDcuRyHkOc7Wm2Htq7pEUJR6AX1g8codFow%2F5B%2BIGj3XBSnkZvFN%2FD9KF2D9kWPygS6S0%2Bso2%2B92DlVEgr1JzOZzY9AYFtK7%2BO8xQLK3%2FOFCkYPduKANopmjyTBz4RwIFxdOJABJ7z%2Boa0K0MXiLFOw%2BBuWS6vU1feR61z0%2FrsVqrnOz5j0M6z6%2FhhZ%2BzkzU7ld5kDDdVkAdsl5zk%2F0zfRSMAmQY33f%2B3FMn5LX3lDO8eKoLwqFZNUlnTX0IM2DbXhb%2BFYfjGvDoBUAVeLJ3oGSE4Hrxvp7TQmcGg2NMilcoupdTJTOVBvgu7IsdBdp8RK%2F5%2FYIQMZtbY7F4HNHHxdex1zYUhe%2FDjPBYNfEmmi4PxtlJQely4JKfxeSPWEwfDr4R9%2FcB4GYY50j6dFVn%2B7V9XFdEN7pFfkfV8UUuXLeT0VppceoPBrB4ZGpCpHhe7Z60FjuxbVEGeBtBLOxVVQQ9BpKLWqM3e8vlzNHEwnvvWvQY6pgFctddVtHOmZPED1XteKGTxPVaXPfx9kImYCSzJw7D%2BRz33urEet3%2BKorNlaKUQCiIeKGfmKSCKO0%2FowCc%2FwK0eEJz1nw2%2BHRaRazpxmU4s4AkJJrPrpfJO%2BmwRG3t9VK1zAUkNzVdW551yKxiWMj%2F6ZETvsvn2K%2B8LxYDC2QeP%2FjCeUhWQ4e9TfxdoiCB0ccsW0VDdP582ySaL%2BKVR55B1PHiqzzn3&X-Amz-Signature=485e4366e031fd21e1e75f739f51569b1d8896da477c117105dfd60f7ede8683&X-Amz-SignedHeaders=host&x-id=GetObject)


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

