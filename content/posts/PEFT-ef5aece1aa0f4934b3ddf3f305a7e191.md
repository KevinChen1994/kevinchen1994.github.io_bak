---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466ZOAMIHZ5%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250223T152238Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjENv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCBDB2SZlHsmJP1qBW\
  zSoaAYlBuvsX%2F1nhNoUNHYaKzEwIhAIoPKeBiEfu811f5OrG%2FIY4GYSpMQNE9iiBGYmCNu%2F\
  wmKv8DCBQQABoMNjM3NDIzMTgzODA1Igy4rx%2BuM31cDdxemr8q3AO6ek1FcpDdGHfvLZ7i1%2F7\
  jaLpuExSbyHcj3vK%2BB6n2n1QML0F5XUlnMshdtOdbhpgr6c%2FZcgmCAvXi2zePZSlDMoMI%2Fg\
  plZeCp7wn3ym6Zlt3J6m71Pjc4rY8j7rcv0G56CQNYY1NPOf79OBYT5D6TCO30n6L6pXe1Y3aCCUG\
  e17M%2BxD%2B4hPjTItES0fpdhiosfAGoe%2FFJHNjR%2B5g12QH1PBsNhoD1l8ZsZy9hykZ5e2h4\
  CO15epHjV2MmG68Cvu%2FCMmTerSXviwfUDpIcBRS4O%2BFdaMtnmFfVfw7c6enGEWQ4IOFsS8uUZ\
  9231oqeMFZG%2BrcaAE43OYuA54NfMpHWn39AANxYgv49BXjnLWf99w88DPB9R%2BT1HpSau6O%2F\
  STmcwSyKwkEH6H1%2FF1YTHUNV5qKNUfnU0oqPygRzJEF4OJJbvp5b73%2Fj1ZyyKCybQqDnz6bRF\
  zHsznTCSWZqy3wmJo4N21OyBTj42QqHf9ZKBPeaSSr3%2Btv%2FO9QaURWCbvulxzd%2F5eHLlHUc\
  3gbgxkYb%2FcarHuZLHJ7nTpDEavjGm5zphPqt3uzbaVDIA8jN7A%2FbfkMEgaXa85ugrgRB4dW68\
  azPgINzBhVghnXTePX9ga1lq4YxOkXGLWgHyTDG%2Beu9BjqkAXkCL1qfQ2Ys1YSI4Jd1hrBj7pCI\
  EIEC8X0SwpvihvqQDxEgti%2BBTa0OYWCGdu4TJ3q4JICsisyXGA1SYyLUqkNUrDJ0ipkeG%2BwJ0\
  KXNzWIJFXVNd2lLzY3QYKdBdPOlhzDKF4k9RzXNnG8ZqPIF0mnKwKTzgUWcfiZJ442EyvudLNPjFe\
  0%2FDQo6PsVp5RyqwMHxKIZ8w5YHjR%2Bk3%2FhFgkyKWS9Y&X-Amz-Signature=311d71c255e5\
  9bab7e05a2646b5eb01195c3a5a1542903ff8e14c6d02c82a03d&X-Amz-SignedHeaders=host\
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
        redential=ASIAZI2LB466SGI4XOKR%2F20250223%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250223T152050Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjENv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIFRTALvkWLEVOf6lR1C8ABe5X1jlbPtAteUf2mETx6sTAiEA0ZJAaVOBAbpodLjyWkjeIH\
        PEaQmYevmtscll1XdfNMMq%2FwMIFBAAGgw2Mzc0MjMxODM4MDUiDBLwqO9R6JyRt5Zd4ir\
        cA5yBo8fdRvw7eHSHsigpO3ab76vDzVBuVT%2BVNQE%2FD%2FbSueiTB1mvKVuO%2BKHHBQ\
        skVIyEeQUjunS%2BhiDbDfPwedFYBUKVeyhW8rrFIbpQGqmVBNhx5lwoRT3exKortMAxqfM\
        XGE3tbXM0axNSCHSrJI4bu0r8mtATzhenBb19BjlTiepJoDMjbAR1b9a9a4TBXMjUFp27sm\
        Z8luaxAC2VPJlb3KNp7k5Imb1pxpj%2BGgxxbzfZdGF7VQZz7CUKT6%2F0pwoKSdrBiVnFp\
        rnOkLY0aDHblVHTd1OaXS7Qxnd19TAq6yZMMADVKddKuF%2B9532Iq0UBcdgvGj1vhMtJmi\
        lGeUhVmm0xZTj8b4Uj4v46kS0cDycsBWcAFYgi3hIn%2B3%2BIUSdPoW1TFIwvOB4jLBCQj\
        tb2qAzCtfOnCxKHfqq7dCOJs1Zcw5S8plTR%2B32YSOHp4d7xu93ZVYlQ9fkWRXlGgC4e8B\
        6ReaG0TInkaTwedJnQGIHLZF0dv6nveFbbqEy5FjOSMpMtNCJPH2%2F3oLuH3T1KKCMM1XK\
        AtgyucZPhHRIpIWTqjNUBJNcsGnP7xFlZjtJPN%2FVa31O%2BIWMdOmJgwVLVDNZRpabRCW\
        BwVUHe1%2FsiyD1i%2Bth7BMy58MsyMJTu670GOqUB7O533VxTzLfYs364O5un0snS34NW4\
        fFBpY2pTeVAyPYmLhOa8MIV%2BMl9Ai63buy2a4mffxeuxKJwusKHWj%2FPAm6PrlgW8Q3d\
        UODYL5rPkO4D4LnrzfGKZb05KqexIePVtImmvcxg6UjyjYPiibH5bDUkGZVp14ANJrWAK%2\
        F81HFftd7284ql2jlLkaicEu7qbh%2F6cC%2BVgvFD57risQM1SW5Az0vm1&X-Amz-Signa\
        ture=c9887ff846f54c5d7d8e8828c3176a8b0af8e21ac0d53560aa815811a026ec0c&X\
        -Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-23T16:20:50.622Z"
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
UPDATE_TIME: "2025-02-23T15:22:46.859Z"
EXPIRY_TIME: "2025-02-23T16:22:34.239Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QY3I7SB3%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T152234Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEN%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDFxo4oDME2FoLOdKNqvHr4Kpt9I4hbygE3oTdzMVGDPQIgeLWAQ28dXrpcrT%2FNd0CYA8gigJ6eUVW0mHm0DwbdC0gq%2FwMIGBAAGgw2Mzc0MjMxODM4MDUiDMIkm4J%2BxEnnvcwrJyrcA9bJ75TVSSJt%2BOCxccckBH0XGCHtEIneyNsWF%2BG4M95tlHHi3w6A%2Bo%2FVxKL9kioUf%2FOCv6QzYtL2ZDIGCqyYesMh3kq5Kmdf3hoOiOH4Y%2BJLPut73X5s2q%2BZq9kel2noBtDtgU3%2BwT%2FCpApiI8S1chsaqZHwW%2BA1qjJ0qtydiADEiXyjxqPADm4h%2BO0WlDMbSei8N4Sg%2BDRkNYS4pPDLzkrBdBooLqR2mjRKuc4Lb1WYW57nA0mfBKbikGf3f4QuQOLw79xlzLQOGffPWjJfTgm%2F0iumdEMqiHevTO0ZjZOzqAeZ7S9yh%2FACw4Oxi4kP7wXrJzxrBZ0VJ%2BBDO2fufgyzvQNxtSjqC4v%2B3mcO8l9pgjb%2B5lKYWeQEphJTY0AQYdMOmuBmtucMaEc09xTDunTShXk0Pz7f23%2BfAbuGB1ndC9%2FCbdS36CDd6cxULKVk2bYYZojj5ExEOIVDFghJkGz8TDCiKxX%2Fl87DrN8Yt47TWSUpufL8p%2FBAA80q4IhTK9uJmtxqV339dLfWqPcu5Ojx0xijmGbAZJMgX1wKIEox3%2BS75XyiZQetbPVGI3CygB%2FEFZNOcvdXXzd%2FQjvpFQP1DGuVVZcLrRM1YA6S4ilwAY5w4Vfia5RoT1WnMOfx7L0GOqUBWtBauwu91QQN7ZpNzTZIgZtRErJ6IfpMqs8fxFskyDwOXA6PgOs4W5M0zVQJ4iA2yW2HAYo4XCNo9YZTNDlATSZS5OytjCvkYibknD3brI9HbXz5bAHcF8aRCdrRxe4UzKpX3X37Zk1ND7o1A6x3GWm4ZOpsq45lX%2BZzR%2FP5gj8igAwyezM%2B%2F6rzkracBX%2BYaaoi1rimkkYw70od%2Fb4t%2FgF10Bho&X-Amz-Signature=06b07dedc6ea8da3198829c96a1c6f44197479d70d9a8a6ca424ba9d547330bd&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QY3I7SB3%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T152234Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEN%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDFxo4oDME2FoLOdKNqvHr4Kpt9I4hbygE3oTdzMVGDPQIgeLWAQ28dXrpcrT%2FNd0CYA8gigJ6eUVW0mHm0DwbdC0gq%2FwMIGBAAGgw2Mzc0MjMxODM4MDUiDMIkm4J%2BxEnnvcwrJyrcA9bJ75TVSSJt%2BOCxccckBH0XGCHtEIneyNsWF%2BG4M95tlHHi3w6A%2Bo%2FVxKL9kioUf%2FOCv6QzYtL2ZDIGCqyYesMh3kq5Kmdf3hoOiOH4Y%2BJLPut73X5s2q%2BZq9kel2noBtDtgU3%2BwT%2FCpApiI8S1chsaqZHwW%2BA1qjJ0qtydiADEiXyjxqPADm4h%2BO0WlDMbSei8N4Sg%2BDRkNYS4pPDLzkrBdBooLqR2mjRKuc4Lb1WYW57nA0mfBKbikGf3f4QuQOLw79xlzLQOGffPWjJfTgm%2F0iumdEMqiHevTO0ZjZOzqAeZ7S9yh%2FACw4Oxi4kP7wXrJzxrBZ0VJ%2BBDO2fufgyzvQNxtSjqC4v%2B3mcO8l9pgjb%2B5lKYWeQEphJTY0AQYdMOmuBmtucMaEc09xTDunTShXk0Pz7f23%2BfAbuGB1ndC9%2FCbdS36CDd6cxULKVk2bYYZojj5ExEOIVDFghJkGz8TDCiKxX%2Fl87DrN8Yt47TWSUpufL8p%2FBAA80q4IhTK9uJmtxqV339dLfWqPcu5Ojx0xijmGbAZJMgX1wKIEox3%2BS75XyiZQetbPVGI3CygB%2FEFZNOcvdXXzd%2FQjvpFQP1DGuVVZcLrRM1YA6S4ilwAY5w4Vfia5RoT1WnMOfx7L0GOqUBWtBauwu91QQN7ZpNzTZIgZtRErJ6IfpMqs8fxFskyDwOXA6PgOs4W5M0zVQJ4iA2yW2HAYo4XCNo9YZTNDlATSZS5OytjCvkYibknD3brI9HbXz5bAHcF8aRCdrRxe4UzKpX3X37Zk1ND7o1A6x3GWm4ZOpsq45lX%2BZzR%2FP5gj8igAwyezM%2B%2F6rzkracBX%2BYaaoi1rimkkYw70od%2Fb4t%2FgF10Bho&X-Amz-Signature=541be2423f6928dc3e12a302e9ab9255d84fcb82549ea2c4dc2f5981fb74df8b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QY3I7SB3%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T152234Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEN%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDFxo4oDME2FoLOdKNqvHr4Kpt9I4hbygE3oTdzMVGDPQIgeLWAQ28dXrpcrT%2FNd0CYA8gigJ6eUVW0mHm0DwbdC0gq%2FwMIGBAAGgw2Mzc0MjMxODM4MDUiDMIkm4J%2BxEnnvcwrJyrcA9bJ75TVSSJt%2BOCxccckBH0XGCHtEIneyNsWF%2BG4M95tlHHi3w6A%2Bo%2FVxKL9kioUf%2FOCv6QzYtL2ZDIGCqyYesMh3kq5Kmdf3hoOiOH4Y%2BJLPut73X5s2q%2BZq9kel2noBtDtgU3%2BwT%2FCpApiI8S1chsaqZHwW%2BA1qjJ0qtydiADEiXyjxqPADm4h%2BO0WlDMbSei8N4Sg%2BDRkNYS4pPDLzkrBdBooLqR2mjRKuc4Lb1WYW57nA0mfBKbikGf3f4QuQOLw79xlzLQOGffPWjJfTgm%2F0iumdEMqiHevTO0ZjZOzqAeZ7S9yh%2FACw4Oxi4kP7wXrJzxrBZ0VJ%2BBDO2fufgyzvQNxtSjqC4v%2B3mcO8l9pgjb%2B5lKYWeQEphJTY0AQYdMOmuBmtucMaEc09xTDunTShXk0Pz7f23%2BfAbuGB1ndC9%2FCbdS36CDd6cxULKVk2bYYZojj5ExEOIVDFghJkGz8TDCiKxX%2Fl87DrN8Yt47TWSUpufL8p%2FBAA80q4IhTK9uJmtxqV339dLfWqPcu5Ojx0xijmGbAZJMgX1wKIEox3%2BS75XyiZQetbPVGI3CygB%2FEFZNOcvdXXzd%2FQjvpFQP1DGuVVZcLrRM1YA6S4ilwAY5w4Vfia5RoT1WnMOfx7L0GOqUBWtBauwu91QQN7ZpNzTZIgZtRErJ6IfpMqs8fxFskyDwOXA6PgOs4W5M0zVQJ4iA2yW2HAYo4XCNo9YZTNDlATSZS5OytjCvkYibknD3brI9HbXz5bAHcF8aRCdrRxe4UzKpX3X37Zk1ND7o1A6x3GWm4ZOpsq45lX%2BZzR%2FP5gj8igAwyezM%2B%2F6rzkracBX%2BYaaoi1rimkkYw70od%2Fb4t%2FgF10Bho&X-Amz-Signature=7508f3d54bb0b130225378d370989b8a6a22b84af26ecf976c7a7bb972934dfd&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QY3I7SB3%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T152234Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEN%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDFxo4oDME2FoLOdKNqvHr4Kpt9I4hbygE3oTdzMVGDPQIgeLWAQ28dXrpcrT%2FNd0CYA8gigJ6eUVW0mHm0DwbdC0gq%2FwMIGBAAGgw2Mzc0MjMxODM4MDUiDMIkm4J%2BxEnnvcwrJyrcA9bJ75TVSSJt%2BOCxccckBH0XGCHtEIneyNsWF%2BG4M95tlHHi3w6A%2Bo%2FVxKL9kioUf%2FOCv6QzYtL2ZDIGCqyYesMh3kq5Kmdf3hoOiOH4Y%2BJLPut73X5s2q%2BZq9kel2noBtDtgU3%2BwT%2FCpApiI8S1chsaqZHwW%2BA1qjJ0qtydiADEiXyjxqPADm4h%2BO0WlDMbSei8N4Sg%2BDRkNYS4pPDLzkrBdBooLqR2mjRKuc4Lb1WYW57nA0mfBKbikGf3f4QuQOLw79xlzLQOGffPWjJfTgm%2F0iumdEMqiHevTO0ZjZOzqAeZ7S9yh%2FACw4Oxi4kP7wXrJzxrBZ0VJ%2BBDO2fufgyzvQNxtSjqC4v%2B3mcO8l9pgjb%2B5lKYWeQEphJTY0AQYdMOmuBmtucMaEc09xTDunTShXk0Pz7f23%2BfAbuGB1ndC9%2FCbdS36CDd6cxULKVk2bYYZojj5ExEOIVDFghJkGz8TDCiKxX%2Fl87DrN8Yt47TWSUpufL8p%2FBAA80q4IhTK9uJmtxqV339dLfWqPcu5Ojx0xijmGbAZJMgX1wKIEox3%2BS75XyiZQetbPVGI3CygB%2FEFZNOcvdXXzd%2FQjvpFQP1DGuVVZcLrRM1YA6S4ilwAY5w4Vfia5RoT1WnMOfx7L0GOqUBWtBauwu91QQN7ZpNzTZIgZtRErJ6IfpMqs8fxFskyDwOXA6PgOs4W5M0zVQJ4iA2yW2HAYo4XCNo9YZTNDlATSZS5OytjCvkYibknD3brI9HbXz5bAHcF8aRCdrRxe4UzKpX3X37Zk1ND7o1A6x3GWm4ZOpsq45lX%2BZzR%2FP5gj8igAwyezM%2B%2F6rzkracBX%2BYaaoi1rimkkYw70od%2Fb4t%2FgF10Bho&X-Amz-Signature=d3a15954c8356b0626a32b141b2e4f60434e32439807f3ff53901f7374409f34&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QY3I7SB3%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T152234Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEN%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDFxo4oDME2FoLOdKNqvHr4Kpt9I4hbygE3oTdzMVGDPQIgeLWAQ28dXrpcrT%2FNd0CYA8gigJ6eUVW0mHm0DwbdC0gq%2FwMIGBAAGgw2Mzc0MjMxODM4MDUiDMIkm4J%2BxEnnvcwrJyrcA9bJ75TVSSJt%2BOCxccckBH0XGCHtEIneyNsWF%2BG4M95tlHHi3w6A%2Bo%2FVxKL9kioUf%2FOCv6QzYtL2ZDIGCqyYesMh3kq5Kmdf3hoOiOH4Y%2BJLPut73X5s2q%2BZq9kel2noBtDtgU3%2BwT%2FCpApiI8S1chsaqZHwW%2BA1qjJ0qtydiADEiXyjxqPADm4h%2BO0WlDMbSei8N4Sg%2BDRkNYS4pPDLzkrBdBooLqR2mjRKuc4Lb1WYW57nA0mfBKbikGf3f4QuQOLw79xlzLQOGffPWjJfTgm%2F0iumdEMqiHevTO0ZjZOzqAeZ7S9yh%2FACw4Oxi4kP7wXrJzxrBZ0VJ%2BBDO2fufgyzvQNxtSjqC4v%2B3mcO8l9pgjb%2B5lKYWeQEphJTY0AQYdMOmuBmtucMaEc09xTDunTShXk0Pz7f23%2BfAbuGB1ndC9%2FCbdS36CDd6cxULKVk2bYYZojj5ExEOIVDFghJkGz8TDCiKxX%2Fl87DrN8Yt47TWSUpufL8p%2FBAA80q4IhTK9uJmtxqV339dLfWqPcu5Ojx0xijmGbAZJMgX1wKIEox3%2BS75XyiZQetbPVGI3CygB%2FEFZNOcvdXXzd%2FQjvpFQP1DGuVVZcLrRM1YA6S4ilwAY5w4Vfia5RoT1WnMOfx7L0GOqUBWtBauwu91QQN7ZpNzTZIgZtRErJ6IfpMqs8fxFskyDwOXA6PgOs4W5M0zVQJ4iA2yW2HAYo4XCNo9YZTNDlATSZS5OytjCvkYibknD3brI9HbXz5bAHcF8aRCdrRxe4UzKpX3X37Zk1ND7o1A6x3GWm4ZOpsq45lX%2BZzR%2FP5gj8igAwyezM%2B%2F6rzkracBX%2BYaaoi1rimkkYw70od%2Fb4t%2FgF10Bho&X-Amz-Signature=a000caf1f70133c9c486236004638f3746ca6ce3f0856a544d76cd464be812db&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667E4CPCUV%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T152236Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCVTNKliR9b3ZHDekpvEQN5KLf%2FXPB%2Fynoe0yN701SEpQIgbvO1Vd%2FZkV65Xaps7L22K2y2t1vgu5TYgbKhU9dSFQwq%2FwMIExAAGgw2Mzc0MjMxODM4MDUiDG2ysD4iTfaQ91XiSCrcA6C2Z10UmLSTjMnRPRxxNlyJWt8ycxNY2%2FoA3E6%2BbRau6GVAGxxYKPMKTaUok5%2Fps2s%2FsHFX%2B5kZqzAAZ81bGAtGLy57Ge7rc6cxZ4crsMi5DhAZEBCXhIhUZLm109Vjo1tOfq7Trk%2Fb%2B1Pjh2XQIA9o8zkvw4Tslt7dtk%2FUXkXk%2FkY0nbza9LnHR9eIMz7j2jBqtu5VSlV2fFLNh7F2Lffjy2u%2FkhkVWw98NqoRMi5%2FQWWzbLSnKnxMLcTH%2FjNi%2F2oRX6yDU9LICZrfHTtKs9bumZNNE%2BovK%2FMzfJi23Ws4q%2FzpeJyvgPBM0qV%2BpACCNMXCarMbdMZuirLpI3aH%2BRmzy5cjqU13Z1sICVi3%2BcGXvaQAsaYfFIJpkyrnnzTNdpQgzDi2G0IO%2FUoXQUKFOocFruuQREidZH%2FRCtqbEfZmBotlnQ4vTWN0t1PYHXk3aHgf3bN0LFIWrjCMNBCS3awsLe8NGUmBKXbEpPdyWyCYkj%2F6msvyk8%2FNz8uEbuSEv01%2BFwYnEeept7HacpIsKIilUByyIdtsapx8AW%2F1kvCGbRG80odw4C66%2Fgvh3ryFi4hRX4niWWEERfbp%2FLEvgpkBwrRg03Hy%2F%2BIwuAizCmi3ljHcsj2ZNXhKi7uZMMPq670GOqUBga01RCcYhh%2Bkp7Kw5ncttiwKWYfF6OgloTK1x5rVwMlJijg8pouBTK2%2FNl0B50vNjd5JdzUC2AwCXgEbPoQFB7Q2a8L5vv993MdaMM4hUlONR%2Bmjyg7%2BTq0WenbiPZXqrA3lytmuIykWnzJ30aTPUctCLaLuTaY51I4%2BqlDUi%2BZyDD6aTAtW9DY1LXzyuoe%2B81f5IoUZUqhp99J7tIv0qgCtZgU4&X-Amz-Signature=a4057b868d52fb78fd4feee57b1591bb8c3fd71c6b2886c3610ff30a6db02a51&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QY4LZA7J%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T152237Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIC7Df25sLREMUirkH1bc%2BKLrajOylUoO%2F3boDR%2BlqQIAAiAG6zsYBcCydQygsF7WgFDuMLVMUTyrregTt0fl4r0mmCr%2FAwgUEAAaDDYzNzQyMzE4MzgwNSIM9Wjz0Rssit4fiANhKtwDjTfyP7bkRL00U3DjzQOvKM%2FoumhmeLqdATDMWJaGOaOiTzrjHDUepHU176Vv7y6eTuPZxwqZ76lekt6S0XsRSoC5Lc8FMMaDVySmhHHLWD5MqlWvYgviYV%2BY9ucS9P3mHzDyDpJCIyPpaIm3zNWJWUDPxHekp82S2wdPguRdNCGciSDagSOTpK53HC0ZFPXoq0ro71EMH6AHVu%2FGZIFkbolmy3kYxk4qr4SoZFElablS%2BTOGOV%2FDT%2BKLPgphfbK3Ewxm33h4SKVJda3%2BnEzmLxn9abIAt4nI39GR4ChFcEFG6%2FCtH40CWK6Iif%2F0A3J8yxsRpzBImnlovgQNP3S6k%2BvUZfXCnU9HE%2FT%2F7utvDeUWd5FPFo1qeoYQJOQaIvsq12gsOlYYeFt%2FDeIx2U3mlMSd3ruEdot6p5HuW7WGRdEZ7wU%2B9yJ%2F87%2BfTQHXVJTl7RNKCd%2BQdoc2unjSGusm5VzRVdUvurN%2B0Tbq9RA0uh4LHXBMhV50QHFclcE%2BKKCh%2FdjG2QCreuhMLifjRUMBxXWpD4BOWuQ1K88JDIw2CYR7pgeWKvOoriRHRCII1eN6HW%2BSRI0wl052%2B6A%2B0RcnMYL%2BgKIYl2Ljto94U%2B9be6WIOPeBVQnmQnYJsK8wsvHrvQY6pgEP738RU7AXYc%2FCSoOrMxvHADiW9XGL81kB4Ih07lqaa%2B4XssY1mZUOIofQG8Iy2Upj3paBHcvavyEB%2F%2F9Mmu97Yvp1u6guQaqKNe6NKzjO3rNi0IOL%2FHidAuwap58mDh0bfhnZWMg8fYBEncEj%2Ft%2FQXd5ewShEqaUsfuVHL6efVxMY2os9W5Bwtg0fnFT%2BsTwxernz6%2BjrK5q8ZrJgPrhj9h6uM8lH&X-Amz-Signature=e4788fce5eaff5817775af5e57c9313aecfbbbb4c4267892cf8353cc06b0864f&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QY3I7SB3%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T152234Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEN%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDFxo4oDME2FoLOdKNqvHr4Kpt9I4hbygE3oTdzMVGDPQIgeLWAQ28dXrpcrT%2FNd0CYA8gigJ6eUVW0mHm0DwbdC0gq%2FwMIGBAAGgw2Mzc0MjMxODM4MDUiDMIkm4J%2BxEnnvcwrJyrcA9bJ75TVSSJt%2BOCxccckBH0XGCHtEIneyNsWF%2BG4M95tlHHi3w6A%2Bo%2FVxKL9kioUf%2FOCv6QzYtL2ZDIGCqyYesMh3kq5Kmdf3hoOiOH4Y%2BJLPut73X5s2q%2BZq9kel2noBtDtgU3%2BwT%2FCpApiI8S1chsaqZHwW%2BA1qjJ0qtydiADEiXyjxqPADm4h%2BO0WlDMbSei8N4Sg%2BDRkNYS4pPDLzkrBdBooLqR2mjRKuc4Lb1WYW57nA0mfBKbikGf3f4QuQOLw79xlzLQOGffPWjJfTgm%2F0iumdEMqiHevTO0ZjZOzqAeZ7S9yh%2FACw4Oxi4kP7wXrJzxrBZ0VJ%2BBDO2fufgyzvQNxtSjqC4v%2B3mcO8l9pgjb%2B5lKYWeQEphJTY0AQYdMOmuBmtucMaEc09xTDunTShXk0Pz7f23%2BfAbuGB1ndC9%2FCbdS36CDd6cxULKVk2bYYZojj5ExEOIVDFghJkGz8TDCiKxX%2Fl87DrN8Yt47TWSUpufL8p%2FBAA80q4IhTK9uJmtxqV339dLfWqPcu5Ojx0xijmGbAZJMgX1wKIEox3%2BS75XyiZQetbPVGI3CygB%2FEFZNOcvdXXzd%2FQjvpFQP1DGuVVZcLrRM1YA6S4ilwAY5w4Vfia5RoT1WnMOfx7L0GOqUBWtBauwu91QQN7ZpNzTZIgZtRErJ6IfpMqs8fxFskyDwOXA6PgOs4W5M0zVQJ4iA2yW2HAYo4XCNo9YZTNDlATSZS5OytjCvkYibknD3brI9HbXz5bAHcF8aRCdrRxe4UzKpX3X37Zk1ND7o1A6x3GWm4ZOpsq45lX%2BZzR%2FP5gj8igAwyezM%2B%2F6rzkracBX%2BYaaoi1rimkkYw70od%2Fb4t%2FgF10Bho&X-Amz-Signature=29de1726df8276fcd936a06fdb8799bb4d3f57e0d7741adb47adf92addda3789&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QY3I7SB3%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T152234Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEN%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDFxo4oDME2FoLOdKNqvHr4Kpt9I4hbygE3oTdzMVGDPQIgeLWAQ28dXrpcrT%2FNd0CYA8gigJ6eUVW0mHm0DwbdC0gq%2FwMIGBAAGgw2Mzc0MjMxODM4MDUiDMIkm4J%2BxEnnvcwrJyrcA9bJ75TVSSJt%2BOCxccckBH0XGCHtEIneyNsWF%2BG4M95tlHHi3w6A%2Bo%2FVxKL9kioUf%2FOCv6QzYtL2ZDIGCqyYesMh3kq5Kmdf3hoOiOH4Y%2BJLPut73X5s2q%2BZq9kel2noBtDtgU3%2BwT%2FCpApiI8S1chsaqZHwW%2BA1qjJ0qtydiADEiXyjxqPADm4h%2BO0WlDMbSei8N4Sg%2BDRkNYS4pPDLzkrBdBooLqR2mjRKuc4Lb1WYW57nA0mfBKbikGf3f4QuQOLw79xlzLQOGffPWjJfTgm%2F0iumdEMqiHevTO0ZjZOzqAeZ7S9yh%2FACw4Oxi4kP7wXrJzxrBZ0VJ%2BBDO2fufgyzvQNxtSjqC4v%2B3mcO8l9pgjb%2B5lKYWeQEphJTY0AQYdMOmuBmtucMaEc09xTDunTShXk0Pz7f23%2BfAbuGB1ndC9%2FCbdS36CDd6cxULKVk2bYYZojj5ExEOIVDFghJkGz8TDCiKxX%2Fl87DrN8Yt47TWSUpufL8p%2FBAA80q4IhTK9uJmtxqV339dLfWqPcu5Ojx0xijmGbAZJMgX1wKIEox3%2BS75XyiZQetbPVGI3CygB%2FEFZNOcvdXXzd%2FQjvpFQP1DGuVVZcLrRM1YA6S4ilwAY5w4Vfia5RoT1WnMOfx7L0GOqUBWtBauwu91QQN7ZpNzTZIgZtRErJ6IfpMqs8fxFskyDwOXA6PgOs4W5M0zVQJ4iA2yW2HAYo4XCNo9YZTNDlATSZS5OytjCvkYibknD3brI9HbXz5bAHcF8aRCdrRxe4UzKpX3X37Zk1ND7o1A6x3GWm4ZOpsq45lX%2BZzR%2FP5gj8igAwyezM%2B%2F6rzkracBX%2BYaaoi1rimkkYw70od%2Fb4t%2FgF10Bho&X-Amz-Signature=4ef90043bb71c93bbbc434d1628911a616744c091231cef34de78ed528831b21&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QY3I7SB3%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T152234Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEN%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDFxo4oDME2FoLOdKNqvHr4Kpt9I4hbygE3oTdzMVGDPQIgeLWAQ28dXrpcrT%2FNd0CYA8gigJ6eUVW0mHm0DwbdC0gq%2FwMIGBAAGgw2Mzc0MjMxODM4MDUiDMIkm4J%2BxEnnvcwrJyrcA9bJ75TVSSJt%2BOCxccckBH0XGCHtEIneyNsWF%2BG4M95tlHHi3w6A%2Bo%2FVxKL9kioUf%2FOCv6QzYtL2ZDIGCqyYesMh3kq5Kmdf3hoOiOH4Y%2BJLPut73X5s2q%2BZq9kel2noBtDtgU3%2BwT%2FCpApiI8S1chsaqZHwW%2BA1qjJ0qtydiADEiXyjxqPADm4h%2BO0WlDMbSei8N4Sg%2BDRkNYS4pPDLzkrBdBooLqR2mjRKuc4Lb1WYW57nA0mfBKbikGf3f4QuQOLw79xlzLQOGffPWjJfTgm%2F0iumdEMqiHevTO0ZjZOzqAeZ7S9yh%2FACw4Oxi4kP7wXrJzxrBZ0VJ%2BBDO2fufgyzvQNxtSjqC4v%2B3mcO8l9pgjb%2B5lKYWeQEphJTY0AQYdMOmuBmtucMaEc09xTDunTShXk0Pz7f23%2BfAbuGB1ndC9%2FCbdS36CDd6cxULKVk2bYYZojj5ExEOIVDFghJkGz8TDCiKxX%2Fl87DrN8Yt47TWSUpufL8p%2FBAA80q4IhTK9uJmtxqV339dLfWqPcu5Ojx0xijmGbAZJMgX1wKIEox3%2BS75XyiZQetbPVGI3CygB%2FEFZNOcvdXXzd%2FQjvpFQP1DGuVVZcLrRM1YA6S4ilwAY5w4Vfia5RoT1WnMOfx7L0GOqUBWtBauwu91QQN7ZpNzTZIgZtRErJ6IfpMqs8fxFskyDwOXA6PgOs4W5M0zVQJ4iA2yW2HAYo4XCNo9YZTNDlATSZS5OytjCvkYibknD3brI9HbXz5bAHcF8aRCdrRxe4UzKpX3X37Zk1ND7o1A6x3GWm4ZOpsq45lX%2BZzR%2FP5gj8igAwyezM%2B%2F6rzkracBX%2BYaaoi1rimkkYw70od%2Fb4t%2FgF10Bho&X-Amz-Signature=5f829ec5744bdc6643612bac4d77bb778a67798944dbb5310fcf5b3e96652951&X-Amz-SignedHeaders=host&x-id=GetObject)


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

