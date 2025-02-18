---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4663JWISJ5S%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250218T083014Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEGAaCXVzLXdlc3QtMiJHMEUCIQCq8NZnXtCda%2FLTGAhncvzEVW1yguUzirQMIAU%2FHXOAVgI\
  gFeg3TrWRQV7%2FWR9PgwYKQN0syjtzEWtnMOhxp6lAQk4qiAQIif%2F%2F%2F%2F%2F%2F%2F%2F\
  %2F%2FARAAGgw2Mzc0MjMxODM4MDUiDEqLvvpGFY2PZhBF2CrcA2VC6DaIUa2ykHOZgHg%2FgRTJZ\
  7iE%2FiKaIdozu9kaHzNm8fp2TAiyrDqzhUNVb9RTBvfqTaEJKnd79touwNqiE8K7N0Gc9f4rKmxu\
  h51pIb6%2B%2Bh2V2whAcu6KCqif8UeGVIkLxGbL%2BqIvPRQjHDyuL5qUrnDCvqn7MeY%2Bal2hn\
  %2FZ1DA4N6iD10WlxZ7%2Bab%2B5%2FmplIffHRihXv6pmOrC6Gxn%2BSkfl%2FEm17Afg2zKX9Ta\
  2g2hW8xAqcHfDVwp5g%2BNs1TF0U8MCi%2FeeYFy2y428rsp%2Bhqe%2BiMaH9FkfjDZ9kdfLzCtl\
  %2Fd95xc6Z4nmGsL%2FzSQsXjxXz2RoZKexYTDzA11wjmbaIQ%2BjQqQg3xnetdYHfdCHrASd2o8b\
  %2B%2BC1tvonPz%2FoXAhAuCjBp1%2BXUi%2FqSW2ZltljrBmm9cmwKD%2FGOrt%2FKySvxI1%2F3\
  etOot9AvxqnutuT%2BLzudi762De2S%2F%2FtvC%2F1%2BLqT%2FqPYJ0R0LsQMsKNLg1sGpmOQ%2\
  BIunaCRpTsroL0nlxT4HpbkobLh6nz7bBBUTk6kfjoUT8FUofKeqAVc2OLdvgdH1e8SkPfDc%2F7R\
  YwUmgq%2BoVPEmR2bEihIMKxR1ZCQoQ66UKmVxV2BmaL3bwQnEnjhwVpaF5cNlfYkMOv%2B0L0GOq\
  UBfSdHfNFxPYS5OSDVtjDwU27nmup5R8%2Bz9sauf00qQ48E8HZ30RsJYBoHxeQxXI%2BdHC1Mbp9\
  peO6BvWZYXInRGy1gRP8FQj9%2Bd31syzXp13unO4W4xsZ20UscawBy8l5m8rfhsJwRfZVGrw0AEF\
  ngEOJTe4%2B3gZNQlNfESBJT3venRr8MUHYOdLnkwBN87mP4HtWHkHSPv3czrHEX5GO5VtUWVZjx&\
  X-Amz-Signature=910bee069099a6ceb8968305df77482bed98213c3837199c7c082b398ae7c\
  450&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466ULSWI2OB%2F20250218%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250218T082855Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEGAaCXVzLXdlc3QtMiJHMEUCIQC9XyJQwDK%2BbwZWJNgxhYs82K9kd\
        XKE4j1Mo4%2FlR46FKQIgRx8OLhj5DRJtv0NQKcMGEOcilIylD%2B7eTTb6P%2BsxBK0qiA\
        QIif%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPVeBIQOGHGvT\
        3Jl8ircA%2FC6ksHJ0Lh9TEZIKmICtwFtR0XhRjpM%2B3j6X7PUvslTXOyrcQlwNfThnFG%\
        2FUJ83g86EfXXQOWOLupMcTLtSVqqsiu6aPvPDaJOqHCoQ1L%2F1p%2FhTdvSiJ5k8ZVXyh\
        w1z6jUZBYZLL%2F0YU8W%2Bx%2FW0iITsMvQk%2FImUdwHiHhkXN3fnBCnzSsDVoWa9WECU\
        DsYKfJ6ovIo5GNOVT903CAF241YYJa4U%2Bz5s%2FfdLBmNvNpHUHh8APn3G42BFgPhgTes\
        KjE%2BQzOnT06cWg2kPtAZpTSXs12NPXB1O8QCWcuum7OERebQVGz19uRrA50S3udo6uSOW\
        BqgOC4ximNxwec7HepWFDK63NS8uebGq%2FmU8Axs4L6icyvJ76LSYcbQrjJnvD3ncItd1J\
        XNNIVQubRTFdc2maOeuzy23fBxW%2FIoadQC3fXmMlhuQrEbCOAHRczaKLmj%2FcMb3DpPI\
        DxzpOGm6vD6nNP%2FDP2QCwjOUa%2B6SIQhqxcbny3Evc3CP3RXzh%2B8NQ1%2BbPwSDmI1\
        Yc4l8Z1rPKA6dYfgBZVbC5xQCddOTDrcA3GmNxy%2F3Irutb3I7h%2FY47XatI8eL57e6uX\
        zr%2Ba1LuiB%2FEbf%2F97%2B%2FIk3x%2FFYeO7B%2FWtPj7JuISbbM5vdcMMv%2B0L0GO\
        qUBVrL%2FgtZ8EtCGrDStFRQnqqX%2BN2g7X3XeXAPwhFDFScbSfSXndUHHEYjsem%2F20N\
        qu83GZkn8PhRqaAcwbQyXr5q4KEBM89zBUcPhARlmf%2BCLuTz1Wie3xlInfdAPHtS6eTRH\
        aavJqFRonLWldgm%2BhKb3yb%2F%2FQTOgnMBwTqW3pzultEGrGvzuJ0JIRIdNs3kSg01Eu\
        dFMQgdVegtbrYJKX31V37Ve6&X-Amz-Signature=3ca51d8b5af742244758155e4bfddf\
        dbff023e4dd0cb247436dab30dd197e3f7&X-Amz-SignedHeaders=host&x-id=GetObj\
        ect"
      expiry_time: "2025-02-18T09:28:55.286Z"
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
UPDATE_TIME: "2025-02-18T08:30:27.048Z"
EXPIRY_TIME: "2025-02-18T09:30:12.302Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666CNYYABH%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T083012Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGAaCXVzLXdlc3QtMiJHMEUCIEmgI%2B9KxI5Vb%2FfQZQcR4%2BYjIfP5VclTB5psuxq6kl33AiEAtoP2MxScUZF16NoeoZ0w7V4gI7FHNAYYNbIFUR4sOYcqiAQIif%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKysyMjnFYW%2BMnRGgSrcA3WG9qRhRs783srGHRLq3le%2FJTVZUehyQ7TE%2BGc4iPnESiId%2FAEYL3OTOzMt2TFgNTLZLZYmeHj6twI1znGBc99%2FX1m5ttFQw7YTBcLyCzuHiNpc9dKjBQD7UuLWuOrFPekqatMxsQZ2%2FecBGCdTAMQmSU56sWXEyVAgZPSNCv65R5bjdXgL%2FOCHAv762tqSkV%2FRmCITe23d20wLx3oh293KlLs5gvHcwIfMgHVuyTxorM0V%2FbR%2FLQCjYNw0PvFehCsMuoTDcTkJ2M1n5zQpdxMx08tISuVdJmvqyfLawuiHWOT6o5lh7K%2Bfd7icVze2XX5t%2BSb%2F6gayJzaYH%2Byljq6aBsG4qqxOyOid2uh%2BXVAgdOhny6K8jIV9ocK%2FPLJ5KUMPKaWBJ101uHxOkeexjUHKIaj6XoBeGFRhgGV5pzZ5uEXD5LEAaNLmQzsF1iHXwHROMBX4pGPRcqDklUbOUzwjvMiEIc5Lv95AUa%2B96drhf8jyHdhrq5brRV0O4bBgNPpAF%2Falh0Zk7A6LZzx5UAEgJXqIiEk3JzxvTKZojR5%2ForCJPrP2XDjJDzUytYKLmB%2B9aMJCE4rhOtu21Ajj1O8CD8wOaW0YvLrPhIh16uIXUg3UJFXlzLfMJ%2BKJMMj%2B0L0GOqUBpRmsCERmxVc6W4fJTN7CbpcRwwlIqHCjbIus3qopajCrm6%2BOF5IftCoKgfq0uz%2FNwNtpb8nmuCViyTDOj8C%2B4Z4RxQfscHDjRGaNJYM2CMDYaXjQCwM80kqsph2JGg1ggmM0%2FyhNI6XYm1sN5xLGG4EEstaCvWHjj5Oa5HsvC5Os9e4QUOo%2Bs8q48gdJbGoj3fupwJiJkj2wwmqkdranZAoy2xZi&X-Amz-Signature=ceb17a9a2a32be3cbb0d0cb12d373ca5d775e03ba4fb60482fb82b2ba454d745&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666CNYYABH%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T083012Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGAaCXVzLXdlc3QtMiJHMEUCIEmgI%2B9KxI5Vb%2FfQZQcR4%2BYjIfP5VclTB5psuxq6kl33AiEAtoP2MxScUZF16NoeoZ0w7V4gI7FHNAYYNbIFUR4sOYcqiAQIif%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKysyMjnFYW%2BMnRGgSrcA3WG9qRhRs783srGHRLq3le%2FJTVZUehyQ7TE%2BGc4iPnESiId%2FAEYL3OTOzMt2TFgNTLZLZYmeHj6twI1znGBc99%2FX1m5ttFQw7YTBcLyCzuHiNpc9dKjBQD7UuLWuOrFPekqatMxsQZ2%2FecBGCdTAMQmSU56sWXEyVAgZPSNCv65R5bjdXgL%2FOCHAv762tqSkV%2FRmCITe23d20wLx3oh293KlLs5gvHcwIfMgHVuyTxorM0V%2FbR%2FLQCjYNw0PvFehCsMuoTDcTkJ2M1n5zQpdxMx08tISuVdJmvqyfLawuiHWOT6o5lh7K%2Bfd7icVze2XX5t%2BSb%2F6gayJzaYH%2Byljq6aBsG4qqxOyOid2uh%2BXVAgdOhny6K8jIV9ocK%2FPLJ5KUMPKaWBJ101uHxOkeexjUHKIaj6XoBeGFRhgGV5pzZ5uEXD5LEAaNLmQzsF1iHXwHROMBX4pGPRcqDklUbOUzwjvMiEIc5Lv95AUa%2B96drhf8jyHdhrq5brRV0O4bBgNPpAF%2Falh0Zk7A6LZzx5UAEgJXqIiEk3JzxvTKZojR5%2ForCJPrP2XDjJDzUytYKLmB%2B9aMJCE4rhOtu21Ajj1O8CD8wOaW0YvLrPhIh16uIXUg3UJFXlzLfMJ%2BKJMMj%2B0L0GOqUBpRmsCERmxVc6W4fJTN7CbpcRwwlIqHCjbIus3qopajCrm6%2BOF5IftCoKgfq0uz%2FNwNtpb8nmuCViyTDOj8C%2B4Z4RxQfscHDjRGaNJYM2CMDYaXjQCwM80kqsph2JGg1ggmM0%2FyhNI6XYm1sN5xLGG4EEstaCvWHjj5Oa5HsvC5Os9e4QUOo%2Bs8q48gdJbGoj3fupwJiJkj2wwmqkdranZAoy2xZi&X-Amz-Signature=35576d1645c6f0d80d2ddfac398eb89768487887ce3205bafe09f19c2399fe23&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666CNYYABH%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T083012Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGAaCXVzLXdlc3QtMiJHMEUCIEmgI%2B9KxI5Vb%2FfQZQcR4%2BYjIfP5VclTB5psuxq6kl33AiEAtoP2MxScUZF16NoeoZ0w7V4gI7FHNAYYNbIFUR4sOYcqiAQIif%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKysyMjnFYW%2BMnRGgSrcA3WG9qRhRs783srGHRLq3le%2FJTVZUehyQ7TE%2BGc4iPnESiId%2FAEYL3OTOzMt2TFgNTLZLZYmeHj6twI1znGBc99%2FX1m5ttFQw7YTBcLyCzuHiNpc9dKjBQD7UuLWuOrFPekqatMxsQZ2%2FecBGCdTAMQmSU56sWXEyVAgZPSNCv65R5bjdXgL%2FOCHAv762tqSkV%2FRmCITe23d20wLx3oh293KlLs5gvHcwIfMgHVuyTxorM0V%2FbR%2FLQCjYNw0PvFehCsMuoTDcTkJ2M1n5zQpdxMx08tISuVdJmvqyfLawuiHWOT6o5lh7K%2Bfd7icVze2XX5t%2BSb%2F6gayJzaYH%2Byljq6aBsG4qqxOyOid2uh%2BXVAgdOhny6K8jIV9ocK%2FPLJ5KUMPKaWBJ101uHxOkeexjUHKIaj6XoBeGFRhgGV5pzZ5uEXD5LEAaNLmQzsF1iHXwHROMBX4pGPRcqDklUbOUzwjvMiEIc5Lv95AUa%2B96drhf8jyHdhrq5brRV0O4bBgNPpAF%2Falh0Zk7A6LZzx5UAEgJXqIiEk3JzxvTKZojR5%2ForCJPrP2XDjJDzUytYKLmB%2B9aMJCE4rhOtu21Ajj1O8CD8wOaW0YvLrPhIh16uIXUg3UJFXlzLfMJ%2BKJMMj%2B0L0GOqUBpRmsCERmxVc6W4fJTN7CbpcRwwlIqHCjbIus3qopajCrm6%2BOF5IftCoKgfq0uz%2FNwNtpb8nmuCViyTDOj8C%2B4Z4RxQfscHDjRGaNJYM2CMDYaXjQCwM80kqsph2JGg1ggmM0%2FyhNI6XYm1sN5xLGG4EEstaCvWHjj5Oa5HsvC5Os9e4QUOo%2Bs8q48gdJbGoj3fupwJiJkj2wwmqkdranZAoy2xZi&X-Amz-Signature=36212e8b04f404c84d633b997c045984f5436ee8d866f17784f02a49e567d20c&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666CNYYABH%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T083012Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGAaCXVzLXdlc3QtMiJHMEUCIEmgI%2B9KxI5Vb%2FfQZQcR4%2BYjIfP5VclTB5psuxq6kl33AiEAtoP2MxScUZF16NoeoZ0w7V4gI7FHNAYYNbIFUR4sOYcqiAQIif%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKysyMjnFYW%2BMnRGgSrcA3WG9qRhRs783srGHRLq3le%2FJTVZUehyQ7TE%2BGc4iPnESiId%2FAEYL3OTOzMt2TFgNTLZLZYmeHj6twI1znGBc99%2FX1m5ttFQw7YTBcLyCzuHiNpc9dKjBQD7UuLWuOrFPekqatMxsQZ2%2FecBGCdTAMQmSU56sWXEyVAgZPSNCv65R5bjdXgL%2FOCHAv762tqSkV%2FRmCITe23d20wLx3oh293KlLs5gvHcwIfMgHVuyTxorM0V%2FbR%2FLQCjYNw0PvFehCsMuoTDcTkJ2M1n5zQpdxMx08tISuVdJmvqyfLawuiHWOT6o5lh7K%2Bfd7icVze2XX5t%2BSb%2F6gayJzaYH%2Byljq6aBsG4qqxOyOid2uh%2BXVAgdOhny6K8jIV9ocK%2FPLJ5KUMPKaWBJ101uHxOkeexjUHKIaj6XoBeGFRhgGV5pzZ5uEXD5LEAaNLmQzsF1iHXwHROMBX4pGPRcqDklUbOUzwjvMiEIc5Lv95AUa%2B96drhf8jyHdhrq5brRV0O4bBgNPpAF%2Falh0Zk7A6LZzx5UAEgJXqIiEk3JzxvTKZojR5%2ForCJPrP2XDjJDzUytYKLmB%2B9aMJCE4rhOtu21Ajj1O8CD8wOaW0YvLrPhIh16uIXUg3UJFXlzLfMJ%2BKJMMj%2B0L0GOqUBpRmsCERmxVc6W4fJTN7CbpcRwwlIqHCjbIus3qopajCrm6%2BOF5IftCoKgfq0uz%2FNwNtpb8nmuCViyTDOj8C%2B4Z4RxQfscHDjRGaNJYM2CMDYaXjQCwM80kqsph2JGg1ggmM0%2FyhNI6XYm1sN5xLGG4EEstaCvWHjj5Oa5HsvC5Os9e4QUOo%2Bs8q48gdJbGoj3fupwJiJkj2wwmqkdranZAoy2xZi&X-Amz-Signature=f831b8e2fce6615ef189d2aeb2d833059dae06962c46b4683294b100342216ab&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666CNYYABH%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T083012Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGAaCXVzLXdlc3QtMiJHMEUCIEmgI%2B9KxI5Vb%2FfQZQcR4%2BYjIfP5VclTB5psuxq6kl33AiEAtoP2MxScUZF16NoeoZ0w7V4gI7FHNAYYNbIFUR4sOYcqiAQIif%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKysyMjnFYW%2BMnRGgSrcA3WG9qRhRs783srGHRLq3le%2FJTVZUehyQ7TE%2BGc4iPnESiId%2FAEYL3OTOzMt2TFgNTLZLZYmeHj6twI1znGBc99%2FX1m5ttFQw7YTBcLyCzuHiNpc9dKjBQD7UuLWuOrFPekqatMxsQZ2%2FecBGCdTAMQmSU56sWXEyVAgZPSNCv65R5bjdXgL%2FOCHAv762tqSkV%2FRmCITe23d20wLx3oh293KlLs5gvHcwIfMgHVuyTxorM0V%2FbR%2FLQCjYNw0PvFehCsMuoTDcTkJ2M1n5zQpdxMx08tISuVdJmvqyfLawuiHWOT6o5lh7K%2Bfd7icVze2XX5t%2BSb%2F6gayJzaYH%2Byljq6aBsG4qqxOyOid2uh%2BXVAgdOhny6K8jIV9ocK%2FPLJ5KUMPKaWBJ101uHxOkeexjUHKIaj6XoBeGFRhgGV5pzZ5uEXD5LEAaNLmQzsF1iHXwHROMBX4pGPRcqDklUbOUzwjvMiEIc5Lv95AUa%2B96drhf8jyHdhrq5brRV0O4bBgNPpAF%2Falh0Zk7A6LZzx5UAEgJXqIiEk3JzxvTKZojR5%2ForCJPrP2XDjJDzUytYKLmB%2B9aMJCE4rhOtu21Ajj1O8CD8wOaW0YvLrPhIh16uIXUg3UJFXlzLfMJ%2BKJMMj%2B0L0GOqUBpRmsCERmxVc6W4fJTN7CbpcRwwlIqHCjbIus3qopajCrm6%2BOF5IftCoKgfq0uz%2FNwNtpb8nmuCViyTDOj8C%2B4Z4RxQfscHDjRGaNJYM2CMDYaXjQCwM80kqsph2JGg1ggmM0%2FyhNI6XYm1sN5xLGG4EEstaCvWHjj5Oa5HsvC5Os9e4QUOo%2Bs8q48gdJbGoj3fupwJiJkj2wwmqkdranZAoy2xZi&X-Amz-Signature=755909805c9ed4b8138c37ceb4aaac62341019be44c583ea56ec5d9a8c878d82&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666WWYFSZK%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T083013Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGAaCXVzLXdlc3QtMiJGMEQCIG6h%2BcD3Z7%2B9VA0A1sbxM2oFWH%2B4yWP0dvjgpquIS9n7AiBmOM07PHygSndJc7kcvpd4s5WRsXw%2FSigi0SbIJazopSqIBAiJ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMGHY54086EnOdnH28KtwDClNbk%2FGhHsC0pZeSzCsFo1VAvurTfHUbONe1Qoi4FFXpCGUE0fbjvpw9ZaSMy%2FZcPqrqJL%2BF%2FSXtF%2Br4exsmoQY%2BUe4qoIvsfLSk1YUp3hg3WeVJW6KikqIZNet6bC946vfabXtTKem59AjUI9c5%2B%2FljVQXzfKcqSzy8KadAq2OYZD4EEyxFRUWG3PueEPHF01nhLdtTn6egsGMJBXWfaVZ8ldhcWY4bsI2%2BB9yifnO7M5rQqVmzfHl5MTC2PKrytso2D05nfSdSqIl5kZHSA%2FT%2FYBmx9xfDp4lEZBxualjnAmrg7JcCnyTfFfSlEW54jp%2B6414Pew%2FhvfOuKPa0mNyD3hhdl66YL%2FppfcuNFxU9GxkFqE9SpbfFDaFLpJC%2F3xv%2FTO0TerjZQwcTqhwsDIdufBhC36a4dsjg0SyRtpGPnv2EocEHc8gZn%2FR15CsQz205FY6TH9OKMez49ewMZfQZx0WBUxevSsnmYVyco5AF6RvbyJzdr%2BngvFXYT2WU6j9%2F%2Fh2A%2FLa3sa5m6k3Jmg8bFwF4zFN9b4wpbeg3h4w1FrMnL7JdUH1RVa%2BAtGefZ7oc3fOAmA2RCCWolc99gbV43GbV1AqWSjQQrcLzLdIdRT7scuxWgp7h07cw%2FP7QvQY6pgEp9HrQExbdVgfq1Fzu3OOgs1JNZp7rxNR%2BF4a1f%2FvDGCORI9OXfIzH0sEYXstuUp2QoXuIE5jOxa1OH6NWTseAbN3pHSTqo3q1VGQ9ujWFZYV%2FNytC5wu0vw3cY6al8R5OP8EpBOVSbkP8LiFgsu9fP%2BSyjKACkWlLltpg3bK%2BnqUarZEHVN8v%2F3qO5VEb4iLApoMNz5HxFJ%2FkqZp36YJ0yq66d1Uh&X-Amz-Signature=584000ebb79aa58d10edccf183d14705cf934002ba71aea56ed7bca0cf3e4b3d&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QFMBU3L3%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T083014Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGAaCXVzLXdlc3QtMiJHMEUCIQC0z0vnF5cxAtV%2Fy8elqqvOwDsmR488wxr4mvteE1MOFQIgCog3gyjm0i30EIOXeTaSk%2BcDq30HI6P4REvViAU3vJwqiAQIif%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOA5IQvmZA1k5wIFVircA1jcF8xzSwqgLvSfx029Gil6Vl5ARZmaT5Ge4jYrMeDhDykLDlZrX4Nn6%2Bx8rRslypYctNbxWt3USIUUWXWqyajQIr6kEQoDrW03PTirpZy3kMLUcMCPKb2fLigDq9tIKtyxxTujeZvwFqLxmPBX%2BeEyGXFQ83olZq1zC3G%2FsweB1SxnR3APeKwrqTmrK7F3kvC8KTMicZljd8PrcgWzuBR4ARfLXhwbJdZh3GMc21uX2HdHWNxQDKhcxS2mwL2VNcpTi4B0vfDKMuw%2Fn2yrXQ6TOz4PU6rqB2%2BB2s5G6uiXw0KW90zJ6jVxsYgppEAeQw4rM6Af2uFSZkG0SGunrSArU%2FQJV%2BjL%2F8AvCOhfKZKAseZjH%2B921zdDSoGdlv2s2u2cAyao%2FvDTj8zNNosFYR9MZqoTM1STSmF%2BLcbVS1jQmfT%2FfbH3esVHRxNnSbQ8JOVyy3tFnNThRKvuOk9CHfzoDtB4dL41md4NTKPqBaMCLK6ZwthRkgqAsjY%2FUiHEIvNfn1V3b4p%2FlALjA7pQQWeuknVtnB4OWJ7gNrCRDn5hGWSe1wXdMSEBMopjhdjOHE1TLGMAfLwZs9Uh76CYUMnm23N2PTVrJckFr3NxODVS9VYyJ8hKqY6volkHMIb%2F0L0GOqUB2EEzWAA%2BwxQh1Tx91l5fn3eMzRPOD8mImZRjbMKwzvu49PR96dbAdvD3QBWq%2FqD9%2Fd7gPRtHU%2BhNmsUM5MiB8TW94g9kBbPBHv4Gtlx2amYj7G2XtMa2yyb0hCG%2BrLYtZT4MRD0P1QSAeqbmuVMiNV0LqZkuroipYOls%2BNwpduatjCdU4OLsYQlc14JWTll%2F5BrOGBgYJ94QblLwGulEhU79M8Bt&X-Amz-Signature=b8fe65bc632db2568a8b62bd7f972683fefa1d8023150ecd968d73f2eed0c999&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666CNYYABH%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T083012Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGAaCXVzLXdlc3QtMiJHMEUCIEmgI%2B9KxI5Vb%2FfQZQcR4%2BYjIfP5VclTB5psuxq6kl33AiEAtoP2MxScUZF16NoeoZ0w7V4gI7FHNAYYNbIFUR4sOYcqiAQIif%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKysyMjnFYW%2BMnRGgSrcA3WG9qRhRs783srGHRLq3le%2FJTVZUehyQ7TE%2BGc4iPnESiId%2FAEYL3OTOzMt2TFgNTLZLZYmeHj6twI1znGBc99%2FX1m5ttFQw7YTBcLyCzuHiNpc9dKjBQD7UuLWuOrFPekqatMxsQZ2%2FecBGCdTAMQmSU56sWXEyVAgZPSNCv65R5bjdXgL%2FOCHAv762tqSkV%2FRmCITe23d20wLx3oh293KlLs5gvHcwIfMgHVuyTxorM0V%2FbR%2FLQCjYNw0PvFehCsMuoTDcTkJ2M1n5zQpdxMx08tISuVdJmvqyfLawuiHWOT6o5lh7K%2Bfd7icVze2XX5t%2BSb%2F6gayJzaYH%2Byljq6aBsG4qqxOyOid2uh%2BXVAgdOhny6K8jIV9ocK%2FPLJ5KUMPKaWBJ101uHxOkeexjUHKIaj6XoBeGFRhgGV5pzZ5uEXD5LEAaNLmQzsF1iHXwHROMBX4pGPRcqDklUbOUzwjvMiEIc5Lv95AUa%2B96drhf8jyHdhrq5brRV0O4bBgNPpAF%2Falh0Zk7A6LZzx5UAEgJXqIiEk3JzxvTKZojR5%2ForCJPrP2XDjJDzUytYKLmB%2B9aMJCE4rhOtu21Ajj1O8CD8wOaW0YvLrPhIh16uIXUg3UJFXlzLfMJ%2BKJMMj%2B0L0GOqUBpRmsCERmxVc6W4fJTN7CbpcRwwlIqHCjbIus3qopajCrm6%2BOF5IftCoKgfq0uz%2FNwNtpb8nmuCViyTDOj8C%2B4Z4RxQfscHDjRGaNJYM2CMDYaXjQCwM80kqsph2JGg1ggmM0%2FyhNI6XYm1sN5xLGG4EEstaCvWHjj5Oa5HsvC5Os9e4QUOo%2Bs8q48gdJbGoj3fupwJiJkj2wwmqkdranZAoy2xZi&X-Amz-Signature=e00b9989e433a37d8b4d49164c764f4980fc5c20931a64a0cdd3852bbebcb7a5&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666CNYYABH%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T083012Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGAaCXVzLXdlc3QtMiJHMEUCIEmgI%2B9KxI5Vb%2FfQZQcR4%2BYjIfP5VclTB5psuxq6kl33AiEAtoP2MxScUZF16NoeoZ0w7V4gI7FHNAYYNbIFUR4sOYcqiAQIif%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKysyMjnFYW%2BMnRGgSrcA3WG9qRhRs783srGHRLq3le%2FJTVZUehyQ7TE%2BGc4iPnESiId%2FAEYL3OTOzMt2TFgNTLZLZYmeHj6twI1znGBc99%2FX1m5ttFQw7YTBcLyCzuHiNpc9dKjBQD7UuLWuOrFPekqatMxsQZ2%2FecBGCdTAMQmSU56sWXEyVAgZPSNCv65R5bjdXgL%2FOCHAv762tqSkV%2FRmCITe23d20wLx3oh293KlLs5gvHcwIfMgHVuyTxorM0V%2FbR%2FLQCjYNw0PvFehCsMuoTDcTkJ2M1n5zQpdxMx08tISuVdJmvqyfLawuiHWOT6o5lh7K%2Bfd7icVze2XX5t%2BSb%2F6gayJzaYH%2Byljq6aBsG4qqxOyOid2uh%2BXVAgdOhny6K8jIV9ocK%2FPLJ5KUMPKaWBJ101uHxOkeexjUHKIaj6XoBeGFRhgGV5pzZ5uEXD5LEAaNLmQzsF1iHXwHROMBX4pGPRcqDklUbOUzwjvMiEIc5Lv95AUa%2B96drhf8jyHdhrq5brRV0O4bBgNPpAF%2Falh0Zk7A6LZzx5UAEgJXqIiEk3JzxvTKZojR5%2ForCJPrP2XDjJDzUytYKLmB%2B9aMJCE4rhOtu21Ajj1O8CD8wOaW0YvLrPhIh16uIXUg3UJFXlzLfMJ%2BKJMMj%2B0L0GOqUBpRmsCERmxVc6W4fJTN7CbpcRwwlIqHCjbIus3qopajCrm6%2BOF5IftCoKgfq0uz%2FNwNtpb8nmuCViyTDOj8C%2B4Z4RxQfscHDjRGaNJYM2CMDYaXjQCwM80kqsph2JGg1ggmM0%2FyhNI6XYm1sN5xLGG4EEstaCvWHjj5Oa5HsvC5Os9e4QUOo%2Bs8q48gdJbGoj3fupwJiJkj2wwmqkdranZAoy2xZi&X-Amz-Signature=84b598483e16ffa99c584636a5567fb69735382ae4fef19a1e25cbb3037d24c8&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666CNYYABH%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T083012Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGAaCXVzLXdlc3QtMiJHMEUCIEmgI%2B9KxI5Vb%2FfQZQcR4%2BYjIfP5VclTB5psuxq6kl33AiEAtoP2MxScUZF16NoeoZ0w7V4gI7FHNAYYNbIFUR4sOYcqiAQIif%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKysyMjnFYW%2BMnRGgSrcA3WG9qRhRs783srGHRLq3le%2FJTVZUehyQ7TE%2BGc4iPnESiId%2FAEYL3OTOzMt2TFgNTLZLZYmeHj6twI1znGBc99%2FX1m5ttFQw7YTBcLyCzuHiNpc9dKjBQD7UuLWuOrFPekqatMxsQZ2%2FecBGCdTAMQmSU56sWXEyVAgZPSNCv65R5bjdXgL%2FOCHAv762tqSkV%2FRmCITe23d20wLx3oh293KlLs5gvHcwIfMgHVuyTxorM0V%2FbR%2FLQCjYNw0PvFehCsMuoTDcTkJ2M1n5zQpdxMx08tISuVdJmvqyfLawuiHWOT6o5lh7K%2Bfd7icVze2XX5t%2BSb%2F6gayJzaYH%2Byljq6aBsG4qqxOyOid2uh%2BXVAgdOhny6K8jIV9ocK%2FPLJ5KUMPKaWBJ101uHxOkeexjUHKIaj6XoBeGFRhgGV5pzZ5uEXD5LEAaNLmQzsF1iHXwHROMBX4pGPRcqDklUbOUzwjvMiEIc5Lv95AUa%2B96drhf8jyHdhrq5brRV0O4bBgNPpAF%2Falh0Zk7A6LZzx5UAEgJXqIiEk3JzxvTKZojR5%2ForCJPrP2XDjJDzUytYKLmB%2B9aMJCE4rhOtu21Ajj1O8CD8wOaW0YvLrPhIh16uIXUg3UJFXlzLfMJ%2BKJMMj%2B0L0GOqUBpRmsCERmxVc6W4fJTN7CbpcRwwlIqHCjbIus3qopajCrm6%2BOF5IftCoKgfq0uz%2FNwNtpb8nmuCViyTDOj8C%2B4Z4RxQfscHDjRGaNJYM2CMDYaXjQCwM80kqsph2JGg1ggmM0%2FyhNI6XYm1sN5xLGG4EEstaCvWHjj5Oa5HsvC5Os9e4QUOo%2Bs8q48gdJbGoj3fupwJiJkj2wwmqkdranZAoy2xZi&X-Amz-Signature=1f654a21046d5a93bf8a29787ce4ca9409714cb7702b7755cf127a9c5ff2d4b7&X-Amz-SignedHeaders=host&x-id=GetObject)


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

