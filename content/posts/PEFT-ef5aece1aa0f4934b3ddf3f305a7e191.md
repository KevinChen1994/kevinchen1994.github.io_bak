---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466R46JEDKI%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250207T232140Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEGYaCXVzLXdlc3QtMiJIMEYCIQD6a8h63QJqH7vjQHs23TZLjpcFr%2BhbGggblrx1qldWbwIhA\
  IkJQ0Hjl1Mp3L2LRK%2FAe3kKJqojpNVcF%2FkgpgtB3DSKKv8DCH8QABoMNjM3NDIzMTgzODA1Ig\
  zxY%2FWxt6ZYINr6s3kq3AOw7IEVnzxmC93gQ7hSl%2FZ3djWrSoms2hRcUr14cU5pfOM1LqxeHF1\
  5n8q6MNhsoYIs0wsE03r12eSThSM8CJYcV%2BNdLzjghOxfWgmlwoW86x%2BY99ylswzV5tVa3638\
  %2Fa%2BHGiuAPpknu6GJ0Q%2B5WY%2F%2FvStxvoTLqz9mN9n3cQVqWravhdq2a4V%2BG0aQyJyfO\
  9lVUk6KLnThWFnaZmzXWwqP82KDlU%2FdCdmgqE32r7AL9z0vax0niu1cazP0%2Bn%2F95PD1SGdU\
  MEdn3%2F%2BPhtB7ILcZ1UylpA11apCGXG8Z5TulUsb9LYt8KyFlUXBqCN%2FD9W%2BG3X65wZRz2\
  te1h3XbhofhKT2KUjM%2BX8UQSKFYb5YVL189ZNYJmWT3ngmyU2zyNNtAtju%2Bj0h8Ylpni2NO2g\
  x7gnZO2PDOOlh9FOYC6ZG6Y2Z1ZsjzkpYvhs4LGR7zn5dZqtQjJjk82b9zseym6Vnv73BsqSOig02\
  t0X%2BMHZp%2F6zKWQ1SkScc2HSpDI1Z2lYJ9zp2ZGvw%2B6UHMNe%2BsbiWQSBiXx7t%2FD1Z%2F\
  d0Znv6B6mNThQkoZQtdqYD5hvFavsf7nlejdDYINP%2BBII3%2BrddOBRMW3NMXShXlV%2FXSf%2B\
  3hGoDNzF98cBDIht6TAdTCQgJq9BjqkASGqFv8eJEAwshhnZNgKQ1jBhCe%2BqrFIxxtxvtBHaUTj\
  rHuRrSLfaZ%2BlLKShpsVFWEi5pfyxDA4PJvK1AuOX577DtAtoCxCBqBC4G3FIhPeupxAeBrqJal1\
  OvbMMCnoooP1EleY%2BMTV%2B6wZOPv3Hkx1uokKHuznGeqBs8gGXqSSVuwKfu5VWbFI%2FdfnT1F\
  xVUXVIj543PlA%2Fx0hU2LxOGKWpPYJ2&X-Amz-Signature=ea552553304a4da75a7e18fd13e5\
  c60a6cb326725233816ddb63ea77e9fc91e9&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466Z45URNOY%2F20250207%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250207T232029Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEGYaCXVzLXdlc3QtMiJHMEUCIQCIyAD0YD1q9ST6JSKIrtID0b6AfAJ\
        D4ZSk5FTY7GXJ8gIgOwl6PT0wOMm41Jrm0ueWbHWJBDprfUuiOuWxgignXpEq%2FwMIfxAA\
        Ggw2Mzc0MjMxODM4MDUiDCsWny7NSTzJk%2BxVXCrcA8PksVY69wnwuqwPOEQtyYhCJYflT\
        %2BJXF1H3fUEyBklUUmTv%2F1ZeWSlxoTlimtMEvXGZv2UOCNiKUeV1EuwD%2FH7cq6Fnro\
        GoGrcuzXT3FW8I3ao35rYUjBoCiyIYaTdYJ4eD5%2FIDz%2FKMjdhki%2BHc5KhJSTwze%2\
        FdvUHHSVK%2FGVHCiuuspBVgn9K9%2FSyO7Wdl2vjm07jIdDDGjBbDh7AwZ210JBRPA%2BU\
        a8VeN674DGfuEFPKuM4A9vId43aSFXM94R1IUArE6GjlFPmrcOqi1%2FQMpBG02WERsueSg\
        9hTUw9dhnExCMDL%2F1HLLEKV%2BIkYUqTstUUIRYyheLE3M3zrPMUBmx6UoXnQrt2MSNjc\
        qkirWcSZ5QTmo8%2F12OJ9arwNWnmNsOyIu0xBZda6PMZlDieKNF9WpDojxsPz8%2BJ721N\
        rIeHFzHn7hXdwRwFXipNBD8Jym%2FUu5Nq6H%2FGVGHQk%2B6J4EsL6Iz%2Bwr6r9RbVZsJ\
        530x%2FXiNel%2FWZC4SUkRfTaV7NKz0g4FTa9L6Owyp9AUggW%2FZwy%2FgKmZKLH3%2FU\
        nz5yuyQ4EpEs0aVoHu3Ak8fUx5pSjY9rM80le90dXFW4kWOxJBa%2FThmKlIfp2Etb7TYsj\
        fTQKzPaCsT5sqto%2B4yMLn%2Fmb0GOqUBuzTxVbBkxHcOcDTKJAGeYYrpqiNC4qj1kTPqr\
        ZqWMTQoniKi668kmCAcxF9qHtoGksmuK7umUNE9OPuY8d0kDaek92jRzAh1brKeuwRFuTcP\
        VEk6TgSc6H%2BzpxNMof0%2F4DtSPCp3%2FbEWRneWXCUVjxlbsCxf3xZ5nk%2BEw37PnrI\
        TjUFUdz%2B7T2fMWpUMQvoWhe7hEdLU0kda2x%2Bqs9tiuZCnXbWc&X-Amz-Signature=8\
        2bd7f74fe1583497cdde79db0d06ee6138f14f7857f15bafdf15d207bf6c96c&X-Amz-S\
        ignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-08T00:20:29.589Z"
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
UPDATE_TIME: "2025-02-07T23:21:46.064Z"
EXPIRY_TIME: "2025-02-08T00:21:38.637Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U62NCMN2%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T232139Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGYaCXVzLXdlc3QtMiJIMEYCIQCukOJtJtzRVzJqD39uPAzZ%2Fzqif8rXcsxLvBDZL8PSZgIhANrrD%2FDY3OFaxK%2Bt3cBhsZ1NWBqHV%2B3cR4dOlH5F6BWYKv8DCH8QABoMNjM3NDIzMTgzODA1Igy8HzvJsquuwKg%2B3VAq3APBJdeIps%2FCk3Yu4EpHKZXUCPHKd9RnhWxu4BLrAeL2FQNHYzjHAOoWenw3unUf1CADipvnJqGCV0OzWTOjH4J8IZvxv%2FSfm57nQNvHLbIPHK%2FvLsFmOLuoo2%2BAjVtbEZBZDfQyzo%2BJHMWDzpz9rT%2FAYEFNx4nvkOLiULMC7FjftlKphCAMGcrzrFRb6lntPuBrGobWFI09j68PjiL%2FETdYjTiAYe85vZcxGD8T3G1ZV30WdXv7UEV2t1FvGWP2r3W7WshXGmsdShDF0zrLo85WS9vzSA94ke7QP0nMTpyBAtW3t0Zfk5icdOYbKWM0qXDHg%2FAqmFPCoe%2BEyEM%2BO0%2Fd1p%2FgZIPOd%2FpMAW1tUsjohvi1k4DL%2FETZo%2BDEhGSwWK%2FMRzb4jayaVU5zCkkOQFThvfRHZb7DkWigaBJEwdYDpgkc0rHdgthJThhlQagSgfy4%2Bj%2FJhEcuZrdav9oJxV2TdDUv%2BQOFdki%2B%2FRH326Lc4csbkYt2t6W%2F2sJq7ScKxW4Ful%2BfzY9uIa0P8GUAWwJllvZ9%2B%2BqAWMoJqpEuZ0z9ixHzoDS6BmWaB%2Bxo6ESq%2BF03nSFJ3UpCSzOIJP1PGVWeS7H7jp2jVAif%2FJHW5G%2BUbmGyp9H3OEgb328MaTDZ%2F5m9BjqkAaLlpOmfEAnSyjetCzl7McY7SkoaJN%2BUCzae9yzByDFX0NJBRf2kxLIMzCD1R5TbgLnjqxc2fMMMxqee9kT2GUw27Q29xwDRQA0%2FUhEdxmBDFpdVR2El8eCOPbY0NLNqpwJfAIp3ikfTOczUovO5FjqBF5nyDUNGwbROMhUV%2FxDGVFZP1vSQ98OfyDakDPsk8GVfVsypYZHUgZIQvjUhYlpn9oVP&X-Amz-Signature=9e2d7f963dc3879755cc5feb8ca891db34b9e449133f31677d5646ef6af1a884&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U62NCMN2%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T232139Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGYaCXVzLXdlc3QtMiJIMEYCIQCukOJtJtzRVzJqD39uPAzZ%2Fzqif8rXcsxLvBDZL8PSZgIhANrrD%2FDY3OFaxK%2Bt3cBhsZ1NWBqHV%2B3cR4dOlH5F6BWYKv8DCH8QABoMNjM3NDIzMTgzODA1Igy8HzvJsquuwKg%2B3VAq3APBJdeIps%2FCk3Yu4EpHKZXUCPHKd9RnhWxu4BLrAeL2FQNHYzjHAOoWenw3unUf1CADipvnJqGCV0OzWTOjH4J8IZvxv%2FSfm57nQNvHLbIPHK%2FvLsFmOLuoo2%2BAjVtbEZBZDfQyzo%2BJHMWDzpz9rT%2FAYEFNx4nvkOLiULMC7FjftlKphCAMGcrzrFRb6lntPuBrGobWFI09j68PjiL%2FETdYjTiAYe85vZcxGD8T3G1ZV30WdXv7UEV2t1FvGWP2r3W7WshXGmsdShDF0zrLo85WS9vzSA94ke7QP0nMTpyBAtW3t0Zfk5icdOYbKWM0qXDHg%2FAqmFPCoe%2BEyEM%2BO0%2Fd1p%2FgZIPOd%2FpMAW1tUsjohvi1k4DL%2FETZo%2BDEhGSwWK%2FMRzb4jayaVU5zCkkOQFThvfRHZb7DkWigaBJEwdYDpgkc0rHdgthJThhlQagSgfy4%2Bj%2FJhEcuZrdav9oJxV2TdDUv%2BQOFdki%2B%2FRH326Lc4csbkYt2t6W%2F2sJq7ScKxW4Ful%2BfzY9uIa0P8GUAWwJllvZ9%2B%2BqAWMoJqpEuZ0z9ixHzoDS6BmWaB%2Bxo6ESq%2BF03nSFJ3UpCSzOIJP1PGVWeS7H7jp2jVAif%2FJHW5G%2BUbmGyp9H3OEgb328MaTDZ%2F5m9BjqkAaLlpOmfEAnSyjetCzl7McY7SkoaJN%2BUCzae9yzByDFX0NJBRf2kxLIMzCD1R5TbgLnjqxc2fMMMxqee9kT2GUw27Q29xwDRQA0%2FUhEdxmBDFpdVR2El8eCOPbY0NLNqpwJfAIp3ikfTOczUovO5FjqBF5nyDUNGwbROMhUV%2FxDGVFZP1vSQ98OfyDakDPsk8GVfVsypYZHUgZIQvjUhYlpn9oVP&X-Amz-Signature=270463de0906658fae368a19a4052e2c8c7416d17c70e70b8ac146c5da3aeb13&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U62NCMN2%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T232139Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGYaCXVzLXdlc3QtMiJIMEYCIQCukOJtJtzRVzJqD39uPAzZ%2Fzqif8rXcsxLvBDZL8PSZgIhANrrD%2FDY3OFaxK%2Bt3cBhsZ1NWBqHV%2B3cR4dOlH5F6BWYKv8DCH8QABoMNjM3NDIzMTgzODA1Igy8HzvJsquuwKg%2B3VAq3APBJdeIps%2FCk3Yu4EpHKZXUCPHKd9RnhWxu4BLrAeL2FQNHYzjHAOoWenw3unUf1CADipvnJqGCV0OzWTOjH4J8IZvxv%2FSfm57nQNvHLbIPHK%2FvLsFmOLuoo2%2BAjVtbEZBZDfQyzo%2BJHMWDzpz9rT%2FAYEFNx4nvkOLiULMC7FjftlKphCAMGcrzrFRb6lntPuBrGobWFI09j68PjiL%2FETdYjTiAYe85vZcxGD8T3G1ZV30WdXv7UEV2t1FvGWP2r3W7WshXGmsdShDF0zrLo85WS9vzSA94ke7QP0nMTpyBAtW3t0Zfk5icdOYbKWM0qXDHg%2FAqmFPCoe%2BEyEM%2BO0%2Fd1p%2FgZIPOd%2FpMAW1tUsjohvi1k4DL%2FETZo%2BDEhGSwWK%2FMRzb4jayaVU5zCkkOQFThvfRHZb7DkWigaBJEwdYDpgkc0rHdgthJThhlQagSgfy4%2Bj%2FJhEcuZrdav9oJxV2TdDUv%2BQOFdki%2B%2FRH326Lc4csbkYt2t6W%2F2sJq7ScKxW4Ful%2BfzY9uIa0P8GUAWwJllvZ9%2B%2BqAWMoJqpEuZ0z9ixHzoDS6BmWaB%2Bxo6ESq%2BF03nSFJ3UpCSzOIJP1PGVWeS7H7jp2jVAif%2FJHW5G%2BUbmGyp9H3OEgb328MaTDZ%2F5m9BjqkAaLlpOmfEAnSyjetCzl7McY7SkoaJN%2BUCzae9yzByDFX0NJBRf2kxLIMzCD1R5TbgLnjqxc2fMMMxqee9kT2GUw27Q29xwDRQA0%2FUhEdxmBDFpdVR2El8eCOPbY0NLNqpwJfAIp3ikfTOczUovO5FjqBF5nyDUNGwbROMhUV%2FxDGVFZP1vSQ98OfyDakDPsk8GVfVsypYZHUgZIQvjUhYlpn9oVP&X-Amz-Signature=bd2f0193142c5bec11b4b25a801ae3dfe401cf832d80a847b7c9b9b4c7c44bea&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U62NCMN2%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T232139Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGYaCXVzLXdlc3QtMiJIMEYCIQCukOJtJtzRVzJqD39uPAzZ%2Fzqif8rXcsxLvBDZL8PSZgIhANrrD%2FDY3OFaxK%2Bt3cBhsZ1NWBqHV%2B3cR4dOlH5F6BWYKv8DCH8QABoMNjM3NDIzMTgzODA1Igy8HzvJsquuwKg%2B3VAq3APBJdeIps%2FCk3Yu4EpHKZXUCPHKd9RnhWxu4BLrAeL2FQNHYzjHAOoWenw3unUf1CADipvnJqGCV0OzWTOjH4J8IZvxv%2FSfm57nQNvHLbIPHK%2FvLsFmOLuoo2%2BAjVtbEZBZDfQyzo%2BJHMWDzpz9rT%2FAYEFNx4nvkOLiULMC7FjftlKphCAMGcrzrFRb6lntPuBrGobWFI09j68PjiL%2FETdYjTiAYe85vZcxGD8T3G1ZV30WdXv7UEV2t1FvGWP2r3W7WshXGmsdShDF0zrLo85WS9vzSA94ke7QP0nMTpyBAtW3t0Zfk5icdOYbKWM0qXDHg%2FAqmFPCoe%2BEyEM%2BO0%2Fd1p%2FgZIPOd%2FpMAW1tUsjohvi1k4DL%2FETZo%2BDEhGSwWK%2FMRzb4jayaVU5zCkkOQFThvfRHZb7DkWigaBJEwdYDpgkc0rHdgthJThhlQagSgfy4%2Bj%2FJhEcuZrdav9oJxV2TdDUv%2BQOFdki%2B%2FRH326Lc4csbkYt2t6W%2F2sJq7ScKxW4Ful%2BfzY9uIa0P8GUAWwJllvZ9%2B%2BqAWMoJqpEuZ0z9ixHzoDS6BmWaB%2Bxo6ESq%2BF03nSFJ3UpCSzOIJP1PGVWeS7H7jp2jVAif%2FJHW5G%2BUbmGyp9H3OEgb328MaTDZ%2F5m9BjqkAaLlpOmfEAnSyjetCzl7McY7SkoaJN%2BUCzae9yzByDFX0NJBRf2kxLIMzCD1R5TbgLnjqxc2fMMMxqee9kT2GUw27Q29xwDRQA0%2FUhEdxmBDFpdVR2El8eCOPbY0NLNqpwJfAIp3ikfTOczUovO5FjqBF5nyDUNGwbROMhUV%2FxDGVFZP1vSQ98OfyDakDPsk8GVfVsypYZHUgZIQvjUhYlpn9oVP&X-Amz-Signature=35fd7b4b33eb333805674e25158fe23501817b6106377ea242c78fae6ff72523&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U62NCMN2%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T232139Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGYaCXVzLXdlc3QtMiJIMEYCIQCukOJtJtzRVzJqD39uPAzZ%2Fzqif8rXcsxLvBDZL8PSZgIhANrrD%2FDY3OFaxK%2Bt3cBhsZ1NWBqHV%2B3cR4dOlH5F6BWYKv8DCH8QABoMNjM3NDIzMTgzODA1Igy8HzvJsquuwKg%2B3VAq3APBJdeIps%2FCk3Yu4EpHKZXUCPHKd9RnhWxu4BLrAeL2FQNHYzjHAOoWenw3unUf1CADipvnJqGCV0OzWTOjH4J8IZvxv%2FSfm57nQNvHLbIPHK%2FvLsFmOLuoo2%2BAjVtbEZBZDfQyzo%2BJHMWDzpz9rT%2FAYEFNx4nvkOLiULMC7FjftlKphCAMGcrzrFRb6lntPuBrGobWFI09j68PjiL%2FETdYjTiAYe85vZcxGD8T3G1ZV30WdXv7UEV2t1FvGWP2r3W7WshXGmsdShDF0zrLo85WS9vzSA94ke7QP0nMTpyBAtW3t0Zfk5icdOYbKWM0qXDHg%2FAqmFPCoe%2BEyEM%2BO0%2Fd1p%2FgZIPOd%2FpMAW1tUsjohvi1k4DL%2FETZo%2BDEhGSwWK%2FMRzb4jayaVU5zCkkOQFThvfRHZb7DkWigaBJEwdYDpgkc0rHdgthJThhlQagSgfy4%2Bj%2FJhEcuZrdav9oJxV2TdDUv%2BQOFdki%2B%2FRH326Lc4csbkYt2t6W%2F2sJq7ScKxW4Ful%2BfzY9uIa0P8GUAWwJllvZ9%2B%2BqAWMoJqpEuZ0z9ixHzoDS6BmWaB%2Bxo6ESq%2BF03nSFJ3UpCSzOIJP1PGVWeS7H7jp2jVAif%2FJHW5G%2BUbmGyp9H3OEgb328MaTDZ%2F5m9BjqkAaLlpOmfEAnSyjetCzl7McY7SkoaJN%2BUCzae9yzByDFX0NJBRf2kxLIMzCD1R5TbgLnjqxc2fMMMxqee9kT2GUw27Q29xwDRQA0%2FUhEdxmBDFpdVR2El8eCOPbY0NLNqpwJfAIp3ikfTOczUovO5FjqBF5nyDUNGwbROMhUV%2FxDGVFZP1vSQ98OfyDakDPsk8GVfVsypYZHUgZIQvjUhYlpn9oVP&X-Amz-Signature=98ccf98435ac328c3d63bb607ae38741bede6d81875a452645c6c366c1f02de0&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SMB2FY6X%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T232140Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGYaCXVzLXdlc3QtMiJIMEYCIQC6QA8Sc%2FEsP%2FAbky6H4nbr5tfh5y%2Fy45QtaD1mA8D3OAIhAO8Ny12SHjiE8gP946OcuLAReas2VJlIW8HPI7rY0EY5Kv8DCH8QABoMNjM3NDIzMTgzODA1Igz7TxaVVkWlG%2B3uRV8q3AOSU4h7%2B%2FFxmWdYU283cNX6%2BvhlxJmuk%2BZ0E5eHWlDEzpopVI%2B7Bwz0KK%2F5nTNQqD6uLuq2yVJxyPGE96f61kox7dGJJt8VeR7p%2FdR0Dj6ZLFFTEDdIkgczKWqrJsQq%2BU2HRwPwxsDxdmrDmI5IAGNuEH74WNrTXMTd7zqXNB5YXorUaUFVb2Q%2FXNCpvtI%2BTT9vQ7MgpZB%2F5JCTNobnOcaKm2Veobm46gBjNtlz%2FV6LKLOX8gIHaluE9VWSt3Esj%2FuB3YstlsiKJ9kXjFkFtGqNDiwheupkObGC7SbHpEMhvYto3CntM28VVNdmRh1BeBgEM4u0U7lF7ezbqdnek9SOym6WMyFuS2kaMDq%2BJpF73M7TPF6mTJyPqIe0Ro3d%2BvauGkVckBEdJQBqHU4Ab6a0ameyue9o%2B%2FbH0pbzuc4qonsCxPOgY3k%2FzZn56H8AyNqBUcuMCAyPi6nP1up3FfFmvoCxnFNgRUnQS1YoCRZVtpehap%2BdLMSNuUIywWovsD4c6sDdAHenuZ96JtOxq2crKczoWGc0GfhGcBQkwigdIADTJiwcRHQ2M6%2FBsBa1SWyTl0GZI7GcmigN1x7IHsSLWilYG9UHqa8rTwhFbM5f7l0MbJVUmksekq4%2F1TDG%2F5m9BjqkAcBMDl%2B8%2FE7158s32dYNXN7ehNik%2BjFtdz89kKORDoHWMxZe77adbKsWPelfJDQAdvWlVxGQO2FJcFUne571UmC5lHCzrmNpytQmNSBYsWqoaxxK2YitoEiK2R37E80s9QrD0Y5nvKOnWSQSnCjNbF7ecEVNDJU4s03cwGdxALewvn6g%2FgwJnFbZgR9safF%2FKqDRmM9mLqsTzvycSGitrJ5sH8jD&X-Amz-Signature=2511815b87159055e099b5e904b43ca39163f717dfe2f1aca062df853df16567&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZJG32UQF%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T232140Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGYaCXVzLXdlc3QtMiJIMEYCIQCEKlU8EbcHF%2FvdCuHxPP3%2F84gn38QC%2FIF0tK53lTlP2gIhANP5pgnEP8rPGycwoBp5zXnfXCi94g08jVjFgY2ky0dCKv8DCH8QABoMNjM3NDIzMTgzODA1IgxNdEAAj4FBYFVpnUgq3ANsWgtRAk6Y%2FsbXOpHyBN%2B8%2BzwuL5ioWfrBV9ag5uZXGowURl0TQRgv05bi9Pf71R0VPOtd1hemPs5U6ClSdXggvMTdRqgb927VMPe8lGfMlOP5IXkvqFc5YiHjaZ2lrF3cOFz%2Fxq72WpeOe84vlnKsMwsf64L8ESQqs3a68fXXqIdEw1lx7Tf%2FoOifGMAIJMu9qcxvgCHzKEq55%2FiPDbVipwO3NtXBVfXK62CxcUHvAqAfKeyoJNncruZRPtSpd1M9otK8MQT4cAKqwuUMMY1Y0Nplj5eyTKzVZe60ZVs6IbnJSTTgpRsX5kURxhfZt%2Fxmzyls88ve%2FSIxnDLQkCJCIkooY%2FJcoPJYbsBYonWjjK5LvJIfMae6hOYs4hB4GJpjhno32ejqQgoBSW2EYOlu9wzr2OKFAqitKB3lc9%2BwbTL9wHZE%2B6gLXViEeaCZcXwaT7OxKdTbMNYtIykxRqg3iNy%2Fs%2BDzicVcfJeRZ0OMN7cmwbi4zJ%2BEr4weV5MZPhpdylXk0xksQgVuZa%2FZLDrOo%2FFZ8hv5wuZ82cV%2Ff2UGZ0GPTpMzwatMIeRds1RJrNNGxTP%2BgcUWqZL2nm%2B%2FT5ptkDMktTS2O5aALa6uvzAZt9fqP0kDIqo4YICWxDC8%2F5m9BjqkAahD4l3eH4NAjCKhyt8eolHLFbpMhqxf90KrUP6sYEcTMaasDKM6pfuzRay3JKoG5UJgN20v2xhhQOiICJVQADwqVqkjXLcA9cj8XbZPDWcxV5bl8rdotZXupMsvbFwE%2FprjSCHhh6DxqMX6Pzh%2B9INman5H3RKVR2ebCyBwTTvMDRilQe2%2B2uuvHO7pBrvmJ3MobgBn6r0tmv82vB6TVSkt2EXg&X-Amz-Signature=9691a6cf377865a82f355801f3633133177f957363a40f214f786e862654cddd&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U62NCMN2%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T232139Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGYaCXVzLXdlc3QtMiJIMEYCIQCukOJtJtzRVzJqD39uPAzZ%2Fzqif8rXcsxLvBDZL8PSZgIhANrrD%2FDY3OFaxK%2Bt3cBhsZ1NWBqHV%2B3cR4dOlH5F6BWYKv8DCH8QABoMNjM3NDIzMTgzODA1Igy8HzvJsquuwKg%2B3VAq3APBJdeIps%2FCk3Yu4EpHKZXUCPHKd9RnhWxu4BLrAeL2FQNHYzjHAOoWenw3unUf1CADipvnJqGCV0OzWTOjH4J8IZvxv%2FSfm57nQNvHLbIPHK%2FvLsFmOLuoo2%2BAjVtbEZBZDfQyzo%2BJHMWDzpz9rT%2FAYEFNx4nvkOLiULMC7FjftlKphCAMGcrzrFRb6lntPuBrGobWFI09j68PjiL%2FETdYjTiAYe85vZcxGD8T3G1ZV30WdXv7UEV2t1FvGWP2r3W7WshXGmsdShDF0zrLo85WS9vzSA94ke7QP0nMTpyBAtW3t0Zfk5icdOYbKWM0qXDHg%2FAqmFPCoe%2BEyEM%2BO0%2Fd1p%2FgZIPOd%2FpMAW1tUsjohvi1k4DL%2FETZo%2BDEhGSwWK%2FMRzb4jayaVU5zCkkOQFThvfRHZb7DkWigaBJEwdYDpgkc0rHdgthJThhlQagSgfy4%2Bj%2FJhEcuZrdav9oJxV2TdDUv%2BQOFdki%2B%2FRH326Lc4csbkYt2t6W%2F2sJq7ScKxW4Ful%2BfzY9uIa0P8GUAWwJllvZ9%2B%2BqAWMoJqpEuZ0z9ixHzoDS6BmWaB%2Bxo6ESq%2BF03nSFJ3UpCSzOIJP1PGVWeS7H7jp2jVAif%2FJHW5G%2BUbmGyp9H3OEgb328MaTDZ%2F5m9BjqkAaLlpOmfEAnSyjetCzl7McY7SkoaJN%2BUCzae9yzByDFX0NJBRf2kxLIMzCD1R5TbgLnjqxc2fMMMxqee9kT2GUw27Q29xwDRQA0%2FUhEdxmBDFpdVR2El8eCOPbY0NLNqpwJfAIp3ikfTOczUovO5FjqBF5nyDUNGwbROMhUV%2FxDGVFZP1vSQ98OfyDakDPsk8GVfVsypYZHUgZIQvjUhYlpn9oVP&X-Amz-Signature=1b3f002230403484e9462317dcc6058e0b579326330ec34567fc1c530e5d2c00&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U62NCMN2%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T232139Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGYaCXVzLXdlc3QtMiJIMEYCIQCukOJtJtzRVzJqD39uPAzZ%2Fzqif8rXcsxLvBDZL8PSZgIhANrrD%2FDY3OFaxK%2Bt3cBhsZ1NWBqHV%2B3cR4dOlH5F6BWYKv8DCH8QABoMNjM3NDIzMTgzODA1Igy8HzvJsquuwKg%2B3VAq3APBJdeIps%2FCk3Yu4EpHKZXUCPHKd9RnhWxu4BLrAeL2FQNHYzjHAOoWenw3unUf1CADipvnJqGCV0OzWTOjH4J8IZvxv%2FSfm57nQNvHLbIPHK%2FvLsFmOLuoo2%2BAjVtbEZBZDfQyzo%2BJHMWDzpz9rT%2FAYEFNx4nvkOLiULMC7FjftlKphCAMGcrzrFRb6lntPuBrGobWFI09j68PjiL%2FETdYjTiAYe85vZcxGD8T3G1ZV30WdXv7UEV2t1FvGWP2r3W7WshXGmsdShDF0zrLo85WS9vzSA94ke7QP0nMTpyBAtW3t0Zfk5icdOYbKWM0qXDHg%2FAqmFPCoe%2BEyEM%2BO0%2Fd1p%2FgZIPOd%2FpMAW1tUsjohvi1k4DL%2FETZo%2BDEhGSwWK%2FMRzb4jayaVU5zCkkOQFThvfRHZb7DkWigaBJEwdYDpgkc0rHdgthJThhlQagSgfy4%2Bj%2FJhEcuZrdav9oJxV2TdDUv%2BQOFdki%2B%2FRH326Lc4csbkYt2t6W%2F2sJq7ScKxW4Ful%2BfzY9uIa0P8GUAWwJllvZ9%2B%2BqAWMoJqpEuZ0z9ixHzoDS6BmWaB%2Bxo6ESq%2BF03nSFJ3UpCSzOIJP1PGVWeS7H7jp2jVAif%2FJHW5G%2BUbmGyp9H3OEgb328MaTDZ%2F5m9BjqkAaLlpOmfEAnSyjetCzl7McY7SkoaJN%2BUCzae9yzByDFX0NJBRf2kxLIMzCD1R5TbgLnjqxc2fMMMxqee9kT2GUw27Q29xwDRQA0%2FUhEdxmBDFpdVR2El8eCOPbY0NLNqpwJfAIp3ikfTOczUovO5FjqBF5nyDUNGwbROMhUV%2FxDGVFZP1vSQ98OfyDakDPsk8GVfVsypYZHUgZIQvjUhYlpn9oVP&X-Amz-Signature=47eaabd1fe84605ebae416bb29045b03c2febc2215a6ca2356b363ab0a3a9b6a&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U62NCMN2%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T232139Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGYaCXVzLXdlc3QtMiJIMEYCIQCukOJtJtzRVzJqD39uPAzZ%2Fzqif8rXcsxLvBDZL8PSZgIhANrrD%2FDY3OFaxK%2Bt3cBhsZ1NWBqHV%2B3cR4dOlH5F6BWYKv8DCH8QABoMNjM3NDIzMTgzODA1Igy8HzvJsquuwKg%2B3VAq3APBJdeIps%2FCk3Yu4EpHKZXUCPHKd9RnhWxu4BLrAeL2FQNHYzjHAOoWenw3unUf1CADipvnJqGCV0OzWTOjH4J8IZvxv%2FSfm57nQNvHLbIPHK%2FvLsFmOLuoo2%2BAjVtbEZBZDfQyzo%2BJHMWDzpz9rT%2FAYEFNx4nvkOLiULMC7FjftlKphCAMGcrzrFRb6lntPuBrGobWFI09j68PjiL%2FETdYjTiAYe85vZcxGD8T3G1ZV30WdXv7UEV2t1FvGWP2r3W7WshXGmsdShDF0zrLo85WS9vzSA94ke7QP0nMTpyBAtW3t0Zfk5icdOYbKWM0qXDHg%2FAqmFPCoe%2BEyEM%2BO0%2Fd1p%2FgZIPOd%2FpMAW1tUsjohvi1k4DL%2FETZo%2BDEhGSwWK%2FMRzb4jayaVU5zCkkOQFThvfRHZb7DkWigaBJEwdYDpgkc0rHdgthJThhlQagSgfy4%2Bj%2FJhEcuZrdav9oJxV2TdDUv%2BQOFdki%2B%2FRH326Lc4csbkYt2t6W%2F2sJq7ScKxW4Ful%2BfzY9uIa0P8GUAWwJllvZ9%2B%2BqAWMoJqpEuZ0z9ixHzoDS6BmWaB%2Bxo6ESq%2BF03nSFJ3UpCSzOIJP1PGVWeS7H7jp2jVAif%2FJHW5G%2BUbmGyp9H3OEgb328MaTDZ%2F5m9BjqkAaLlpOmfEAnSyjetCzl7McY7SkoaJN%2BUCzae9yzByDFX0NJBRf2kxLIMzCD1R5TbgLnjqxc2fMMMxqee9kT2GUw27Q29xwDRQA0%2FUhEdxmBDFpdVR2El8eCOPbY0NLNqpwJfAIp3ikfTOczUovO5FjqBF5nyDUNGwbROMhUV%2FxDGVFZP1vSQ98OfyDakDPsk8GVfVsypYZHUgZIQvjUhYlpn9oVP&X-Amz-Signature=f8cafe0f4592e5d5f57f4e4eec2c8c0e5cc6e374d9ce5b142c8652703ac46b29&X-Amz-SignedHeaders=host&x-id=GetObject)


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

