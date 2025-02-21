---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB46673RGJSFJ%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250221T072250Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEKf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIH3S85S4BeZRMev3i%2\
  FGypo8L%2BuyN7XX2wr4ahNDhWAP3AiBTjTg0amAolBWJYhAeuUZ40dYTxoVDEqWOKrYbX%2FAcTy\
  qIBAjQ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM0gYeDyxbMXdx%2F\
  lPxKtwDkDTGJY50opsVXDvxY2tiZ%2F3YGVuAcgMpyixtROe7NYBfH9aHMfkDihaOZaGR8mJKgGLM\
  UiTuWbv6MBAbo7rg8xb%2BAjQLRDzrRV26dj%2B065CxmXb6UaOpoVTM1n1h0%2FasaJ7Mym%2BV2\
  fkI77qSf6yfXS2XHldP0vH4MdhV2QpWAQYQCjAEdp1sDvgNoIBq823uM%2Bzrsb7jcaOH5cQL0DOi\
  pgbIMLnp6%2BuPh%2BMF1ybnDwiWQFHPs%2F2QMo4lRnSKeIRvxucgU9yvfPhbjNzNEWXc5s1BIX0\
  JdVRuaPMbHr6DmFiNH70pk962PM%2B0fGQ0k2qCgi%2Bs97bXs6FmkKMCGV0KytpVXPaEihHk2GS2\
  SR%2FRtLhs1NDBesu7298dQHGC%2BDbPlkPrBXepUvv1AWWemXRAhbP%2F%2BL9%2BTyGaaMxuKd%\
  2FGREiRO89EbbEo3d1dGSINDScAcJ31FlmIbddLcn%2Fy4vVbQsMRY4V30menNnMcyeazBRyML7xx\
  F1ya4CrR69hU8E1PXz032woP35saExaLIwBO5PT2NEzGIt9flPFo%2BApwkteQcR%2F3kzfQXDxCd\
  GR5egu%2B9vfJQ84BBxE%2B8H1UdFmudrNsGWbTqbwkldTt7LTgDMSt0VA%2FDa6DcD5xQB4wvsHg\
  vQY6pgEMD5nTZgL6Jdryxzw1lV0QXGbuOV8Q65hsLhRdqfOLlJ7liodjxRSu%2FFvsyPdNIiFhsG9\
  DnDp%2BNFr4OZAbuc2Daz0NaJ%2BcvxhW0%2Brbj1k6%2FuwHDQ5F%2Bo3xq8o7dSexRx1nV8DO1p\
  pGLmW0p9jM9hFV47n9VO9ZIPjyP8RpNuAFL2Bd%2BULTLGUZsOlFo3KtoSy8EKCf6H%2FnXK%2BY5\
  jK5xQaCCPq8fTWg&X-Amz-Signature=f88940cf9d6897704e4001caa5393a3cedf4906d0a122\
  26a536fcce1b3c6b109&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466X3ASGP4Z%2F20250221%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250221T072126Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEKf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIQCg4EWIN4gInfbKhdJu7JyTIGJFNV%2F2wM8bp%2BxsfR6hJQIgQWmgMS9zyqkrIAxP2N\
        AYfH3eV94BHimdbNL4AsxzfsQqiAQI0P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2M\
        zc0MjMxODM4MDUiDL%2FMiPBESJiIPLzW4yrcA2CjyaeK01whvpvaWQsm9ayjEL5atoD0wp\
        tE5H812sEr8lbu3J0yG5A9dhmixCbE%2B91hG2JtXYkORk%2BRjTqQRfm6XqvNBE926ESE5\
        YYpPOlno8t9FnRivYqXtuHURnZq7ZnaTqYD%2BIqZAjhf4XdjcpMv3H90j0199fyCs4vJlB\
        Ckv0uIdjgKpCELCPjGknqXRHhVQQPZ%2BAde4e6CtEeUpQYVnf%2BDocQ1uBgCUaO3wSWOZ\
        QhuPIWNfn2ekdBJjYAOJvFxid39Xh5wUqHNyAPULJdMSOMwSfDxMEmhOQpajQndMYvEYM0Q\
        bSmGkXC1%2Fp5motR6ESxIPoLuSSlUqGQPuEBZRQCbxR2WRl5hclfyQLwN%2BA4eMVQCVX3\
        MpR7Vf0Z5%2BzBj0MVkcPPK%2BDel7%2FYDDC0lTHroKSN9QwkNh7fb0DnafZZqu5nQJA5V\
        an7VLm1r4l3eQIVq8Key9q3zff2vSd7cpPD6jtPDx4FIRBn7wvveL7ZbUHI%2F98qYWk4zs\
        xPb2LzKgGxHzHmAAxGrz%2BSfZi0SOGP56wFIMKvGQHU6SzmaQln%2BOaU%2FguqfV427SZ\
        J3WZNjOn3aP0OxVsmOzBBJawku5xf1SpS8duYvsk9H3Fkn8XHwCALU7N9LukxDMMnB4L0GO\
        qUBbQsJ2nNmafvc1mtq2Qb1yqlBDts8bwfOHWt7zSvqXEjo%2BKJl%2F2HA%2BRKBC%2F1R\
        v9INBmyuo5%2FivR6wYQOAmhrF4F9DuIASlOWshw7CVqk%2BVpJ9F4jeh5HnlbsLAY3jWwL\
        g9H5LwY1jfjbVVd1XYpvTKkPlH7FzpwgR1w0gugJytTA6F0%2BN%2B726nN305qPR58vDMR\
        4D4nPaxwiDbnVexWh38w3cYaX5&X-Amz-Signature=f808018f33c7409d82be3ff08043\
        707dcc1429a28bb31bc7986f56b36d4f95c8&X-Amz-SignedHeaders=host&x-id=GetO\
        bject"
      expiry_time: "2025-02-21T08:21:26.727Z"
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
UPDATE_TIME: "2025-02-21T07:23:01.569Z"
EXPIRY_TIME: "2025-02-21T08:22:48.200Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RRD5SDYA%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T072248Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIBuHeOoQEW8AtEWf6tYXB4OrzAEtHR%2FKY6ODQPZF8BqdAiASpvHLZXCoA8%2F4UUDaks65vIIohDS4ZI7Y4YbCZTwHuCqIBAjQ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMzzOpBRUjKB9rQfiaKtwDCI8ILLL64FTytlQoObV3dXGqd4u%2BpzSKt8m7CHy44Lh%2BVaPOZhVLwjPF%2F7YR2%2B%2FsOAq1GQaFJsks3N3E8D5fClYszt8rm56EuByzC6HZu4VM3mJ37R6S6KvZtktl2qC6xNeQNGKCwksIRiRRi0hQZeDeKid13ULVTQqzAwHZ%2B2Msp2jcVdHD7mwbpANH44ZqE2el%2BQ2sDiJW2WRZeXMDMOxcj%2BIElujKFQtR4OG9riNjuIy%2B4gV7K5pNeL4gMaufCb5P%2Bfn5G2IRcYAIMVPYhEVeh7GKVrR2dQsmvzW1eZIQxbiKUaZL6yIeQCkHjPC24oLD8n1tORGH97gCZ%2BeaZ5tsAv0sc0H6YTtp45kaUzzcGr3D6lF98ZsgVDhzTfFb3EGHD2mzf5uKknOAgA0bRWY6PEpQ5vmdTokJqSSz%2BhL1PgkKuO13BxS0Eq%2FVDBs5nZrRZmHMNTrle43s7hUAimxS9ru7xuJI%2B6eeNzdZvkhBrIe8fHrrlZNK%2F0P3V8dB84uU3euRRI%2FdHqn7GduCWDoZKFeIjeZ%2Be6EC7REt2ELNwh1IMjBnDBEFBB8pTH9Tb8lBYnUqkEhw2BbBuvMMTJLDPsqxruFKMt0gPtA%2FwNlQsRtCtKMBIltY8tgwvcHgvQY6pgGh4hLYmZHs3UlhCbNDhm4SPO89xTWbCRAuBAXy8gydfEvMyUAdoP3Dz9rEVVmilBjHJTsrTEnzzdap1XvyENyO%2F8hxLcquuhvXXdyS0myyUbBy0jrgKPwxyOMwxTKYZ61KfDRdqNn%2Bq7E3tokdZ7o828WcNtu2gQBhDiyPfFPOyVbv7kAjJhOpA28Xa93a3Etndo1JKb7TL0eBL4ImRKdQlOnn5cCZ&X-Amz-Signature=b4a9228853ad9e6e14b7e62ea41f6d2b27125df26ecca5f6cfb7dcc5aa0f2cff&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RRD5SDYA%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T072248Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIBuHeOoQEW8AtEWf6tYXB4OrzAEtHR%2FKY6ODQPZF8BqdAiASpvHLZXCoA8%2F4UUDaks65vIIohDS4ZI7Y4YbCZTwHuCqIBAjQ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMzzOpBRUjKB9rQfiaKtwDCI8ILLL64FTytlQoObV3dXGqd4u%2BpzSKt8m7CHy44Lh%2BVaPOZhVLwjPF%2F7YR2%2B%2FsOAq1GQaFJsks3N3E8D5fClYszt8rm56EuByzC6HZu4VM3mJ37R6S6KvZtktl2qC6xNeQNGKCwksIRiRRi0hQZeDeKid13ULVTQqzAwHZ%2B2Msp2jcVdHD7mwbpANH44ZqE2el%2BQ2sDiJW2WRZeXMDMOxcj%2BIElujKFQtR4OG9riNjuIy%2B4gV7K5pNeL4gMaufCb5P%2Bfn5G2IRcYAIMVPYhEVeh7GKVrR2dQsmvzW1eZIQxbiKUaZL6yIeQCkHjPC24oLD8n1tORGH97gCZ%2BeaZ5tsAv0sc0H6YTtp45kaUzzcGr3D6lF98ZsgVDhzTfFb3EGHD2mzf5uKknOAgA0bRWY6PEpQ5vmdTokJqSSz%2BhL1PgkKuO13BxS0Eq%2FVDBs5nZrRZmHMNTrle43s7hUAimxS9ru7xuJI%2B6eeNzdZvkhBrIe8fHrrlZNK%2F0P3V8dB84uU3euRRI%2FdHqn7GduCWDoZKFeIjeZ%2Be6EC7REt2ELNwh1IMjBnDBEFBB8pTH9Tb8lBYnUqkEhw2BbBuvMMTJLDPsqxruFKMt0gPtA%2FwNlQsRtCtKMBIltY8tgwvcHgvQY6pgGh4hLYmZHs3UlhCbNDhm4SPO89xTWbCRAuBAXy8gydfEvMyUAdoP3Dz9rEVVmilBjHJTsrTEnzzdap1XvyENyO%2F8hxLcquuhvXXdyS0myyUbBy0jrgKPwxyOMwxTKYZ61KfDRdqNn%2Bq7E3tokdZ7o828WcNtu2gQBhDiyPfFPOyVbv7kAjJhOpA28Xa93a3Etndo1JKb7TL0eBL4ImRKdQlOnn5cCZ&X-Amz-Signature=64513bb54113618da2153e4df3d8e8c2a0a83c5d22beb7372ffc1b40863a6ca9&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RRD5SDYA%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T072248Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIBuHeOoQEW8AtEWf6tYXB4OrzAEtHR%2FKY6ODQPZF8BqdAiASpvHLZXCoA8%2F4UUDaks65vIIohDS4ZI7Y4YbCZTwHuCqIBAjQ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMzzOpBRUjKB9rQfiaKtwDCI8ILLL64FTytlQoObV3dXGqd4u%2BpzSKt8m7CHy44Lh%2BVaPOZhVLwjPF%2F7YR2%2B%2FsOAq1GQaFJsks3N3E8D5fClYszt8rm56EuByzC6HZu4VM3mJ37R6S6KvZtktl2qC6xNeQNGKCwksIRiRRi0hQZeDeKid13ULVTQqzAwHZ%2B2Msp2jcVdHD7mwbpANH44ZqE2el%2BQ2sDiJW2WRZeXMDMOxcj%2BIElujKFQtR4OG9riNjuIy%2B4gV7K5pNeL4gMaufCb5P%2Bfn5G2IRcYAIMVPYhEVeh7GKVrR2dQsmvzW1eZIQxbiKUaZL6yIeQCkHjPC24oLD8n1tORGH97gCZ%2BeaZ5tsAv0sc0H6YTtp45kaUzzcGr3D6lF98ZsgVDhzTfFb3EGHD2mzf5uKknOAgA0bRWY6PEpQ5vmdTokJqSSz%2BhL1PgkKuO13BxS0Eq%2FVDBs5nZrRZmHMNTrle43s7hUAimxS9ru7xuJI%2B6eeNzdZvkhBrIe8fHrrlZNK%2F0P3V8dB84uU3euRRI%2FdHqn7GduCWDoZKFeIjeZ%2Be6EC7REt2ELNwh1IMjBnDBEFBB8pTH9Tb8lBYnUqkEhw2BbBuvMMTJLDPsqxruFKMt0gPtA%2FwNlQsRtCtKMBIltY8tgwvcHgvQY6pgGh4hLYmZHs3UlhCbNDhm4SPO89xTWbCRAuBAXy8gydfEvMyUAdoP3Dz9rEVVmilBjHJTsrTEnzzdap1XvyENyO%2F8hxLcquuhvXXdyS0myyUbBy0jrgKPwxyOMwxTKYZ61KfDRdqNn%2Bq7E3tokdZ7o828WcNtu2gQBhDiyPfFPOyVbv7kAjJhOpA28Xa93a3Etndo1JKb7TL0eBL4ImRKdQlOnn5cCZ&X-Amz-Signature=0a7237f596554eb2f0db9b4d27c97670aa9bbbb6b3124fc341c74d1fb0b5b48d&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RRD5SDYA%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T072248Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIBuHeOoQEW8AtEWf6tYXB4OrzAEtHR%2FKY6ODQPZF8BqdAiASpvHLZXCoA8%2F4UUDaks65vIIohDS4ZI7Y4YbCZTwHuCqIBAjQ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMzzOpBRUjKB9rQfiaKtwDCI8ILLL64FTytlQoObV3dXGqd4u%2BpzSKt8m7CHy44Lh%2BVaPOZhVLwjPF%2F7YR2%2B%2FsOAq1GQaFJsks3N3E8D5fClYszt8rm56EuByzC6HZu4VM3mJ37R6S6KvZtktl2qC6xNeQNGKCwksIRiRRi0hQZeDeKid13ULVTQqzAwHZ%2B2Msp2jcVdHD7mwbpANH44ZqE2el%2BQ2sDiJW2WRZeXMDMOxcj%2BIElujKFQtR4OG9riNjuIy%2B4gV7K5pNeL4gMaufCb5P%2Bfn5G2IRcYAIMVPYhEVeh7GKVrR2dQsmvzW1eZIQxbiKUaZL6yIeQCkHjPC24oLD8n1tORGH97gCZ%2BeaZ5tsAv0sc0H6YTtp45kaUzzcGr3D6lF98ZsgVDhzTfFb3EGHD2mzf5uKknOAgA0bRWY6PEpQ5vmdTokJqSSz%2BhL1PgkKuO13BxS0Eq%2FVDBs5nZrRZmHMNTrle43s7hUAimxS9ru7xuJI%2B6eeNzdZvkhBrIe8fHrrlZNK%2F0P3V8dB84uU3euRRI%2FdHqn7GduCWDoZKFeIjeZ%2Be6EC7REt2ELNwh1IMjBnDBEFBB8pTH9Tb8lBYnUqkEhw2BbBuvMMTJLDPsqxruFKMt0gPtA%2FwNlQsRtCtKMBIltY8tgwvcHgvQY6pgGh4hLYmZHs3UlhCbNDhm4SPO89xTWbCRAuBAXy8gydfEvMyUAdoP3Dz9rEVVmilBjHJTsrTEnzzdap1XvyENyO%2F8hxLcquuhvXXdyS0myyUbBy0jrgKPwxyOMwxTKYZ61KfDRdqNn%2Bq7E3tokdZ7o828WcNtu2gQBhDiyPfFPOyVbv7kAjJhOpA28Xa93a3Etndo1JKb7TL0eBL4ImRKdQlOnn5cCZ&X-Amz-Signature=4fecd03e878e8704621f8526d0eaa806ef3c37442fa0fd4cbafa935f5ae95f1e&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RRD5SDYA%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T072248Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIBuHeOoQEW8AtEWf6tYXB4OrzAEtHR%2FKY6ODQPZF8BqdAiASpvHLZXCoA8%2F4UUDaks65vIIohDS4ZI7Y4YbCZTwHuCqIBAjQ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMzzOpBRUjKB9rQfiaKtwDCI8ILLL64FTytlQoObV3dXGqd4u%2BpzSKt8m7CHy44Lh%2BVaPOZhVLwjPF%2F7YR2%2B%2FsOAq1GQaFJsks3N3E8D5fClYszt8rm56EuByzC6HZu4VM3mJ37R6S6KvZtktl2qC6xNeQNGKCwksIRiRRi0hQZeDeKid13ULVTQqzAwHZ%2B2Msp2jcVdHD7mwbpANH44ZqE2el%2BQ2sDiJW2WRZeXMDMOxcj%2BIElujKFQtR4OG9riNjuIy%2B4gV7K5pNeL4gMaufCb5P%2Bfn5G2IRcYAIMVPYhEVeh7GKVrR2dQsmvzW1eZIQxbiKUaZL6yIeQCkHjPC24oLD8n1tORGH97gCZ%2BeaZ5tsAv0sc0H6YTtp45kaUzzcGr3D6lF98ZsgVDhzTfFb3EGHD2mzf5uKknOAgA0bRWY6PEpQ5vmdTokJqSSz%2BhL1PgkKuO13BxS0Eq%2FVDBs5nZrRZmHMNTrle43s7hUAimxS9ru7xuJI%2B6eeNzdZvkhBrIe8fHrrlZNK%2F0P3V8dB84uU3euRRI%2FdHqn7GduCWDoZKFeIjeZ%2Be6EC7REt2ELNwh1IMjBnDBEFBB8pTH9Tb8lBYnUqkEhw2BbBuvMMTJLDPsqxruFKMt0gPtA%2FwNlQsRtCtKMBIltY8tgwvcHgvQY6pgGh4hLYmZHs3UlhCbNDhm4SPO89xTWbCRAuBAXy8gydfEvMyUAdoP3Dz9rEVVmilBjHJTsrTEnzzdap1XvyENyO%2F8hxLcquuhvXXdyS0myyUbBy0jrgKPwxyOMwxTKYZ61KfDRdqNn%2Bq7E3tokdZ7o828WcNtu2gQBhDiyPfFPOyVbv7kAjJhOpA28Xa93a3Etndo1JKb7TL0eBL4ImRKdQlOnn5cCZ&X-Amz-Signature=e76dadb05a1f2f87231fa0e2c75e5c18e0a3c79b047eb38fb0d376b786d2dfe0&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YXGO36QV%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T072249Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCHpcR%2Fx4ewwpoZPv2mgoy1TdMTM2pqoDXaHAw5rE7CRQIhAP0YutiY84cAiD6%2BR8bVcVU5ePl6nnmSnmOyF7%2Fdx8CkKogECND%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyXbqBOODgzQTuNBycq3APg6IivWhoR0S7amSsJLn4Iv9KM7KlN0Wgz7koo2%2BrJfInrojE7En%2FMeFBBIEPUxBmogvyZKWj%2BuI5JX5vOaL0Oe1qVHeZcwkdiR9%2Fq8vu44eiNMHmAJ8CrEKob2duLEZx5qjIo5T2n5v4MrqQ2rBS1o69tSYtiZxi5JytVbuALUk8mkqhuMiwlxkz96VPRsPrxPNS0TY7qFQKrOLO%2BSP%2BL3WNPMJW%2FO0qdmQvQQyYM1xv0MWRQHpOfBkCMGVH%2BJ9jO6vi9UgFzMgL8ZgH5HOpdtKvmTMv4eus8zFw2GUI1Sdp5c6KRVQlJy2Hv2yQcizOIQXylHn5PS3lMbSILckFOkfinqvZVLJvcitNKl4%2B9t4w5QiU9C0SnOYzdGI8gSzXuy8eAYtP2krYiSEHXFxdf%2BhNiQ1QueO5AqH0UxQclSYhZqqybUAPvdgy4MFe6vrshc38H%2FwtPb2IpmU0KeWXlEpqduGj%2F99nYy4YY%2Fdr8tToSpDnSwEtW42Qd%2Fs2uG%2Be70yGXd3iyjl9yAtj%2BfzysDIESWndj0lK%2Barq8UdI4OJ6uNnNoHdhs6JY9%2BJkB945mlzqJ7OZiqhkF6hG5QL0P0SOS0kc8azgv79Q%2BD92WcocrEaz%2Bm7u4URWI4TDvwOC9BjqkATcscUz4lXIF1KPkXBm4%2BdDvW99MvAISOWIsw0Osvio622ci7Yhuse2XOU4yK7%2BNoQJEsAbJ9GjpH7YUrRLjxRUncNvTPQU3vHL62wUBrfX%2FYghT4BcejklAFLJ8dEAggOOGmqaeZoBPEZgYQc7S1KcpWkhs%2BN3pTAxmRvSzJ9BvSsBjZEKjvSzc3bdw76uJyTLUGWYAIL8%2FlDbhnNRBOaCNPEIb&X-Amz-Signature=14ae287b556e0cb8edaede10fed92a0bab94ebad020f3d551d185943688343cb&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664YAT7EOH%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T072249Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIHQsdujOLNZX3SU1pIDsjUDca2ozefm9OppBigBemSN5AiEAvcnUYZ7PdZRigGos5vZG3GrW4TPbmOEeTivmoflsXS8qiAQI0P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKHdbhH2DdO4%2B62hZCrcAwUZYEfI1fcIrbu8CnkgQ7deqwRJI%2F6ZuivWDjgQo0e0kz2p0l6xdcU1kHWQLBGeQTFn3oFYNDIrLb6Jcxt3C9Tiw5ULHSHzkqH8kQ3enQb7tS7iHFrQ0%2B8G0CkR7d8F4lUhtRf279t0viSMmu0tNmQvdt7hDmVXCPlC%2FCAxGjsQxg%2Fi8wKVLfRii9HIa5iK29FtdGHpt6vIv8VRTtTrxlHHHV4RjvPocMvKDKpEtuo9KHx5RZ%2BitOa2psEF7u60Iyb8td%2BcyWiWU7JgICS63rQSYDhnhMALJlQKD9h1w46hkF032xnqaGJUHfM64wxjXFLOPn0IHpW0gm2Bj8UH%2FxUW1bA4GQ%2F3Zi9gw8SF%2Bg5yEfuSIhQtdTkm6WHuyOXB6hsMaNRJq2T%2F72AJ75y1eAqMAdPIF7JLg2SIuAc2tmed%2Bv0Nu8k6rFPuwcS%2FS8UGM9VqziOd2JeyDY%2FOwGdwIvyad%2FFXTI%2Fa%2Fej%2FYcJiY8QCJ06tZUjUgiu208CxT%2BR4X6D3UmMRZvSYyWP20NXpu1vt8Pp3UwK%2F%2BUko1POPKGOuD8C1oe99wytcGQ1hwncF9nYAQ1Qu54LWRjPVMrsXBfVp0corMSi8VWEfx0VRdECJCToJMqrBUYb53ghRMNLA4L0GOqUBG27j9GTELo%2BD%2F0Z0DzHR59QV60WoWDqQo9r73QI5hunkNsqlu8DY8gEe0%2BM%2FPbvSvNljx6zDg3EilNFqZ3Op%2FYVWdNfmLS531MyBzxFHo6NOxLR0820hjxA%2Btp3nUpJHquusN4C8mA%2FibP%2F%2B3OOqF%2BrFxzfx5pJSRggNGXwrttJOw7ImdnISXCBQj5fl1VM8ijNzK0mtio9LIQBXRlJK9FJkavw6&X-Amz-Signature=8e601db22124fcc759047aa4fc8cc9a7c29887e920356e7634025246a43928cc&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RRD5SDYA%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T072248Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIBuHeOoQEW8AtEWf6tYXB4OrzAEtHR%2FKY6ODQPZF8BqdAiASpvHLZXCoA8%2F4UUDaks65vIIohDS4ZI7Y4YbCZTwHuCqIBAjQ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMzzOpBRUjKB9rQfiaKtwDCI8ILLL64FTytlQoObV3dXGqd4u%2BpzSKt8m7CHy44Lh%2BVaPOZhVLwjPF%2F7YR2%2B%2FsOAq1GQaFJsks3N3E8D5fClYszt8rm56EuByzC6HZu4VM3mJ37R6S6KvZtktl2qC6xNeQNGKCwksIRiRRi0hQZeDeKid13ULVTQqzAwHZ%2B2Msp2jcVdHD7mwbpANH44ZqE2el%2BQ2sDiJW2WRZeXMDMOxcj%2BIElujKFQtR4OG9riNjuIy%2B4gV7K5pNeL4gMaufCb5P%2Bfn5G2IRcYAIMVPYhEVeh7GKVrR2dQsmvzW1eZIQxbiKUaZL6yIeQCkHjPC24oLD8n1tORGH97gCZ%2BeaZ5tsAv0sc0H6YTtp45kaUzzcGr3D6lF98ZsgVDhzTfFb3EGHD2mzf5uKknOAgA0bRWY6PEpQ5vmdTokJqSSz%2BhL1PgkKuO13BxS0Eq%2FVDBs5nZrRZmHMNTrle43s7hUAimxS9ru7xuJI%2B6eeNzdZvkhBrIe8fHrrlZNK%2F0P3V8dB84uU3euRRI%2FdHqn7GduCWDoZKFeIjeZ%2Be6EC7REt2ELNwh1IMjBnDBEFBB8pTH9Tb8lBYnUqkEhw2BbBuvMMTJLDPsqxruFKMt0gPtA%2FwNlQsRtCtKMBIltY8tgwvcHgvQY6pgGh4hLYmZHs3UlhCbNDhm4SPO89xTWbCRAuBAXy8gydfEvMyUAdoP3Dz9rEVVmilBjHJTsrTEnzzdap1XvyENyO%2F8hxLcquuhvXXdyS0myyUbBy0jrgKPwxyOMwxTKYZ61KfDRdqNn%2Bq7E3tokdZ7o828WcNtu2gQBhDiyPfFPOyVbv7kAjJhOpA28Xa93a3Etndo1JKb7TL0eBL4ImRKdQlOnn5cCZ&X-Amz-Signature=22fe4344fdeb4af3826bd23a09ed75ed3b4170f54b3367ca68d6cc66ca0f402b&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RRD5SDYA%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T072248Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIBuHeOoQEW8AtEWf6tYXB4OrzAEtHR%2FKY6ODQPZF8BqdAiASpvHLZXCoA8%2F4UUDaks65vIIohDS4ZI7Y4YbCZTwHuCqIBAjQ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMzzOpBRUjKB9rQfiaKtwDCI8ILLL64FTytlQoObV3dXGqd4u%2BpzSKt8m7CHy44Lh%2BVaPOZhVLwjPF%2F7YR2%2B%2FsOAq1GQaFJsks3N3E8D5fClYszt8rm56EuByzC6HZu4VM3mJ37R6S6KvZtktl2qC6xNeQNGKCwksIRiRRi0hQZeDeKid13ULVTQqzAwHZ%2B2Msp2jcVdHD7mwbpANH44ZqE2el%2BQ2sDiJW2WRZeXMDMOxcj%2BIElujKFQtR4OG9riNjuIy%2B4gV7K5pNeL4gMaufCb5P%2Bfn5G2IRcYAIMVPYhEVeh7GKVrR2dQsmvzW1eZIQxbiKUaZL6yIeQCkHjPC24oLD8n1tORGH97gCZ%2BeaZ5tsAv0sc0H6YTtp45kaUzzcGr3D6lF98ZsgVDhzTfFb3EGHD2mzf5uKknOAgA0bRWY6PEpQ5vmdTokJqSSz%2BhL1PgkKuO13BxS0Eq%2FVDBs5nZrRZmHMNTrle43s7hUAimxS9ru7xuJI%2B6eeNzdZvkhBrIe8fHrrlZNK%2F0P3V8dB84uU3euRRI%2FdHqn7GduCWDoZKFeIjeZ%2Be6EC7REt2ELNwh1IMjBnDBEFBB8pTH9Tb8lBYnUqkEhw2BbBuvMMTJLDPsqxruFKMt0gPtA%2FwNlQsRtCtKMBIltY8tgwvcHgvQY6pgGh4hLYmZHs3UlhCbNDhm4SPO89xTWbCRAuBAXy8gydfEvMyUAdoP3Dz9rEVVmilBjHJTsrTEnzzdap1XvyENyO%2F8hxLcquuhvXXdyS0myyUbBy0jrgKPwxyOMwxTKYZ61KfDRdqNn%2Bq7E3tokdZ7o828WcNtu2gQBhDiyPfFPOyVbv7kAjJhOpA28Xa93a3Etndo1JKb7TL0eBL4ImRKdQlOnn5cCZ&X-Amz-Signature=762b8eb91198265195d89b76bea0cfdf416d5f4f31ca303eba009ca6a0d5cf12&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RRD5SDYA%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T072248Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIBuHeOoQEW8AtEWf6tYXB4OrzAEtHR%2FKY6ODQPZF8BqdAiASpvHLZXCoA8%2F4UUDaks65vIIohDS4ZI7Y4YbCZTwHuCqIBAjQ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMzzOpBRUjKB9rQfiaKtwDCI8ILLL64FTytlQoObV3dXGqd4u%2BpzSKt8m7CHy44Lh%2BVaPOZhVLwjPF%2F7YR2%2B%2FsOAq1GQaFJsks3N3E8D5fClYszt8rm56EuByzC6HZu4VM3mJ37R6S6KvZtktl2qC6xNeQNGKCwksIRiRRi0hQZeDeKid13ULVTQqzAwHZ%2B2Msp2jcVdHD7mwbpANH44ZqE2el%2BQ2sDiJW2WRZeXMDMOxcj%2BIElujKFQtR4OG9riNjuIy%2B4gV7K5pNeL4gMaufCb5P%2Bfn5G2IRcYAIMVPYhEVeh7GKVrR2dQsmvzW1eZIQxbiKUaZL6yIeQCkHjPC24oLD8n1tORGH97gCZ%2BeaZ5tsAv0sc0H6YTtp45kaUzzcGr3D6lF98ZsgVDhzTfFb3EGHD2mzf5uKknOAgA0bRWY6PEpQ5vmdTokJqSSz%2BhL1PgkKuO13BxS0Eq%2FVDBs5nZrRZmHMNTrle43s7hUAimxS9ru7xuJI%2B6eeNzdZvkhBrIe8fHrrlZNK%2F0P3V8dB84uU3euRRI%2FdHqn7GduCWDoZKFeIjeZ%2Be6EC7REt2ELNwh1IMjBnDBEFBB8pTH9Tb8lBYnUqkEhw2BbBuvMMTJLDPsqxruFKMt0gPtA%2FwNlQsRtCtKMBIltY8tgwvcHgvQY6pgGh4hLYmZHs3UlhCbNDhm4SPO89xTWbCRAuBAXy8gydfEvMyUAdoP3Dz9rEVVmilBjHJTsrTEnzzdap1XvyENyO%2F8hxLcquuhvXXdyS0myyUbBy0jrgKPwxyOMwxTKYZ61KfDRdqNn%2Bq7E3tokdZ7o828WcNtu2gQBhDiyPfFPOyVbv7kAjJhOpA28Xa93a3Etndo1JKb7TL0eBL4ImRKdQlOnn5cCZ&X-Amz-Signature=1652aebd037bcfa31b1d73155181e563ea0f083ee9031bef03bcbc072800049d&X-Amz-SignedHeaders=host&x-id=GetObject)


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

