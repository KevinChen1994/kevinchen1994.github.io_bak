---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466TH6VQPWO%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250206T025213Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEDgaCXVzLXdlc3QtMiJIMEYCIQDoOOBDjrssd%2FOmRgJa694lkwOxAsNyTzJnpwqa7dZLqQIhA\
  OvSN03HLmSPr9%2FPRNv6LqoCF6y1bKangnn1FkhhewrjKv8DCFEQABoMNjM3NDIzMTgzODA1IgxV\
  uecL8ErQ2Ni7%2B7sq3ANfM3SMXJJNT1Mu6mGDma5%2FaqZRQGZKZa%2B4wO2gpk8eN0uHMynUx4Z\
  LReVlw0xip%2BVOiR4WVrGMYS4HUdXZqeG35jdsKwZxZ%2B5EfTclA6LLvcT%2FDTBKOZjqDC0t62\
  HMu97%2BHcEXU%2BAO%2FIn8CJp7QMbvQWrKcJW6xOpCGOxmwMUYG%2FFJZWT1hqbui99PlpyNOFE\
  HY527SLkuTWRPpwEgFGSlhMs2LiI2CUM61RIgVxkCdtS%2BJh6ErZ2YQSHs9Uv1qhBcVu85X7EHJJ\
  W8rrB753crx3byCaCZcbtnXGG%2FFAxc%2FxT1EpvHyXtLiUOpr3n79SFG5Qar3gLkxA3B4BnZe7T\
  3vK1Odjcsb6JNn9TLBgyoxksM6%2BLL8R49GuiPUAuHeOxYhR3SSUAes6mqZMOtTTMeE73Jch4mjm\
  I4bvoVCz80efnsKn7BaU5uBKvkAxxOjxpTxTj6cm4CjqilAJFymsZE9f1sTNiu0g%2B2grljo7evP\
  K46R7GCT5ecQ5tW6E%2BkaAKOKcM4hsEB1HK2wov8TPQEtPPnrUVg7KYmSRgH71AlHvzLyOp5BPsF\
  0YJZIycrlMZ%2BICZEB57HtDEuG3aL819noJiF91Q5kesbOZOswddeh6JofoNnQDh1QZkAqDDP7I%\
  2B9BjqkASU96yn3fly2LV6RQlzk%2B23Az1TVdG%2BwgmK9QiYwrcDaYvwOa16erJLp6mwlkGKC%2\
  FjQJJk8uewnioZbWdQx%2FP0eMMeUvWTzJh0rgDuDh93nTFLfiLeu5A6fUG1Z6D6FtTDsKV4N5BJp\
  ppsvkxForicP3uI4xxD%2Fvh3uFjY1KNt0JI6tYr7h3QJr5QLuiiYA%2FBmVfvFSBmpk1zQvOQ89Q\
  h%2Fid0wRa&X-Amz-Signature=45e40b3ecb1181007ac7433f546ca5cec96599d7a00ccb2a0f\
  74ad6c23f57516&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4667NDEPDPF%2F20250206%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250206T025049Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEDgaCXVzLXdlc3QtMiJIMEYCIQCp2Kma%2BfQJEyTioor4TDAKDhV2S\
        JD4g97vHKVWt%2BmWbAIhAPy%2B%2BNGHviuTroJQTx7YdVBZqHffUYD2lHNemKQTgRz0Kv\
        8DCFEQABoMNjM3NDIzMTgzODA1Igy1Fkwe%2FZyoadRY9Qoq3AOD1PYizXNTTleMNPe2Kqu\
        AfFO%2BtBPtSizvoKXVL%2FjjjB9bRMlgunsrY5pVHlG3ah7DHLJl3VxBgrnG60Qx7U%2F0\
        2zzk2XhExG%2FjjGtS88W743I%2Fk%2Bb3UnqtiHhc7swxv7HMPTOXtZB3z9zvozNRLV4QY\
        m64uuBNr3eCFamd%2BElEbfOVemM3BP1aIarzkwkosdZOHzCQKBO4tONZbdIVV1pg%2BD%2\
        FVIbDA%2F10OlfQMtDcUvnnLrcwHHMlJe9nbZUYQ8iUD%2BiZ%2F9rxHGNhFsrGc4C2WBtZ\
        ZDbmOJo7bcUmJKDLMb70LFpLr7b3864K39EeSYPxJHBXEA%2Fgxi7WDmTUS5tXPS7BYxufy\
        ZJmreTHkZ6T6hqpk1fNT6a9EVxQca7qUjxmqZ4qr%2BywlRtDniXs6UhgmUusuHbVA%2F6V\
        jGhSSdUmh7t6OEU9I8m19ZBnEw8gzwuVXk2TlyKobxApC4cHAr2%2FQb%2BCtkGv4qzoqwd\
        MeHhYYZCGqqpcMUAms8p38PI6p45OfrMHyMiHDFQ7fTCxsi%2FG99FT6xZJULQlgly6u6Xd\
        rz8tD2gT%2FdRKzKe%2BIXjAKq6dB9n4QRCI503U7ClgxeuN4pQyTWcNH%2FQD36jTHiVjf\
        Qu46Qqx5rCnDwtxVBTD47I%2B9BjqkAWHGWTKq6hZxEdZz6xpgmnv0QKR6Yhuz6rPdALsKi\
        mGd4L2baN9KYQ6GH8DKUOIXeuZAAJ%2BfEo41WKDPnjaoTjqISqquea13Fkx9SDclv6Ylo%\
        2Br0peFSvaN0fiuAwkhMt88G6AGpzFUR6pfLrawxp7INxwfQIGMW%2BM53B1ll%2BFc4xzk\
        4xuDdPQPGRCfB4HOaMEF9lHgMDtKY%2FpJnX5Ek8tHZOGQy&X-Amz-Signature=a673027\
        91f94cdbc21e57997c32c10eb93bae5cbc64ad7a847e3973a4129b79c&X-Amz-SignedH\
        eaders=host&x-id=GetObject"
      expiry_time: "2025-02-06T03:50:49.612Z"
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
UPDATE_TIME: "2025-02-06T02:52:17.746Z"
EXPIRY_TIME: "2025-02-06T03:52:08.026Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XUVTJA2B%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T025209Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDgaCXVzLXdlc3QtMiJIMEYCIQDQBnODhaFbwhJE2gWOxeNRQa0B9f6dT0qnsMYrk32EMgIhAK4AEfEyqlUd3skIofCafPdwOel0Fr%2FDeMLq6IoYYtbQKv8DCFEQABoMNjM3NDIzMTgzODA1IgwCy0LYs4zyEi5sqtEq3APPDnMLvDzXdT%2Fc9jK0d6rn2F5Qe8pUQF1poSv99mkQfjreh3Azu825PjG3B6h86TnIPwCwr8GH%2FZg3yJ4UKIc6lw9lpVFXuS7OIfrrxyECReaas70tTazIZhdpXVsd9ydW5eOH0kYdkwiuo4Vtck9knBt9fhvdwJFkh8eOjkZxWLgszaVzFte8jX7NnnsqNhGTuoC4rz9%2FnBVbORmfH%2FQMg0tHRmOuTSKPH%2BSYMmLGnZomYSgBVi1tT6K5gSx193M%2FVWnsiLimppGyf4tZRWrl7NZSsZZDUneWcrlen6QeD%2F2uBVG2dtWMm2REP4QXOSybN16sD%2Bg0k%2FimYZUrhifPz%2F1kew4rh5CNqol5R82b3g0z0458T3huLOqLBIv8902Damnt5VLcBVLNGePrYdTJYZfKgQ03J1tZuMxTktjdCbpj70Ic2DuQnsYccKwYJ5FyuY%2BiTfNfkpYlydu2wt%2BnPE%2BnLW%2FNUgSUaaGMoj8BSl1BvDxiSQWtvVkH8SPRokACa7OamwdVNFyq9PehftQHMOQ3DFBYr0ehwcYTLcNaFaWeKWYwGFKvebuYRJZpy2VqgRxBeZGn9%2BDEq%2BTKwdFgcOUvmrkXgA%2F3X%2BHhYauRUVjnYTQTtYEwB%2BxC5zDH7I%2B9BjqkAdVIda5Jvd5CYI8Zt5fx0Hl6%2FurV9lfmOWnlU3gricZcCBUQxPasnrrQ76L4LP29zFkYg%2FjwsSnIzJgB%2FJiaX1dtEsZPCpSSjigq7vzE4aTlez%2FZ0zln9ABze0%2FxrFpALsHj3V9snlLtaJJ4kwwc3qUceMzobwWM6%2B3pO%2BrSw9yKN%2FvCEfOqDaBBro9us0B6vCVumLiCM7DJx0WjbKZwtm37A6Sf&X-Amz-Signature=171b25cf2f282be3450f4556a931f6d152209c99d9e4bd4e63c0d38eb9fb767e&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XUVTJA2B%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T025209Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDgaCXVzLXdlc3QtMiJIMEYCIQDQBnODhaFbwhJE2gWOxeNRQa0B9f6dT0qnsMYrk32EMgIhAK4AEfEyqlUd3skIofCafPdwOel0Fr%2FDeMLq6IoYYtbQKv8DCFEQABoMNjM3NDIzMTgzODA1IgwCy0LYs4zyEi5sqtEq3APPDnMLvDzXdT%2Fc9jK0d6rn2F5Qe8pUQF1poSv99mkQfjreh3Azu825PjG3B6h86TnIPwCwr8GH%2FZg3yJ4UKIc6lw9lpVFXuS7OIfrrxyECReaas70tTazIZhdpXVsd9ydW5eOH0kYdkwiuo4Vtck9knBt9fhvdwJFkh8eOjkZxWLgszaVzFte8jX7NnnsqNhGTuoC4rz9%2FnBVbORmfH%2FQMg0tHRmOuTSKPH%2BSYMmLGnZomYSgBVi1tT6K5gSx193M%2FVWnsiLimppGyf4tZRWrl7NZSsZZDUneWcrlen6QeD%2F2uBVG2dtWMm2REP4QXOSybN16sD%2Bg0k%2FimYZUrhifPz%2F1kew4rh5CNqol5R82b3g0z0458T3huLOqLBIv8902Damnt5VLcBVLNGePrYdTJYZfKgQ03J1tZuMxTktjdCbpj70Ic2DuQnsYccKwYJ5FyuY%2BiTfNfkpYlydu2wt%2BnPE%2BnLW%2FNUgSUaaGMoj8BSl1BvDxiSQWtvVkH8SPRokACa7OamwdVNFyq9PehftQHMOQ3DFBYr0ehwcYTLcNaFaWeKWYwGFKvebuYRJZpy2VqgRxBeZGn9%2BDEq%2BTKwdFgcOUvmrkXgA%2F3X%2BHhYauRUVjnYTQTtYEwB%2BxC5zDH7I%2B9BjqkAdVIda5Jvd5CYI8Zt5fx0Hl6%2FurV9lfmOWnlU3gricZcCBUQxPasnrrQ76L4LP29zFkYg%2FjwsSnIzJgB%2FJiaX1dtEsZPCpSSjigq7vzE4aTlez%2FZ0zln9ABze0%2FxrFpALsHj3V9snlLtaJJ4kwwc3qUceMzobwWM6%2B3pO%2BrSw9yKN%2FvCEfOqDaBBro9us0B6vCVumLiCM7DJx0WjbKZwtm37A6Sf&X-Amz-Signature=b1d2b5df627b12fceccf5f726697576d66397c25d701c8213c11116b8bc76ea9&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XUVTJA2B%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T025209Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDgaCXVzLXdlc3QtMiJIMEYCIQDQBnODhaFbwhJE2gWOxeNRQa0B9f6dT0qnsMYrk32EMgIhAK4AEfEyqlUd3skIofCafPdwOel0Fr%2FDeMLq6IoYYtbQKv8DCFEQABoMNjM3NDIzMTgzODA1IgwCy0LYs4zyEi5sqtEq3APPDnMLvDzXdT%2Fc9jK0d6rn2F5Qe8pUQF1poSv99mkQfjreh3Azu825PjG3B6h86TnIPwCwr8GH%2FZg3yJ4UKIc6lw9lpVFXuS7OIfrrxyECReaas70tTazIZhdpXVsd9ydW5eOH0kYdkwiuo4Vtck9knBt9fhvdwJFkh8eOjkZxWLgszaVzFte8jX7NnnsqNhGTuoC4rz9%2FnBVbORmfH%2FQMg0tHRmOuTSKPH%2BSYMmLGnZomYSgBVi1tT6K5gSx193M%2FVWnsiLimppGyf4tZRWrl7NZSsZZDUneWcrlen6QeD%2F2uBVG2dtWMm2REP4QXOSybN16sD%2Bg0k%2FimYZUrhifPz%2F1kew4rh5CNqol5R82b3g0z0458T3huLOqLBIv8902Damnt5VLcBVLNGePrYdTJYZfKgQ03J1tZuMxTktjdCbpj70Ic2DuQnsYccKwYJ5FyuY%2BiTfNfkpYlydu2wt%2BnPE%2BnLW%2FNUgSUaaGMoj8BSl1BvDxiSQWtvVkH8SPRokACa7OamwdVNFyq9PehftQHMOQ3DFBYr0ehwcYTLcNaFaWeKWYwGFKvebuYRJZpy2VqgRxBeZGn9%2BDEq%2BTKwdFgcOUvmrkXgA%2F3X%2BHhYauRUVjnYTQTtYEwB%2BxC5zDH7I%2B9BjqkAdVIda5Jvd5CYI8Zt5fx0Hl6%2FurV9lfmOWnlU3gricZcCBUQxPasnrrQ76L4LP29zFkYg%2FjwsSnIzJgB%2FJiaX1dtEsZPCpSSjigq7vzE4aTlez%2FZ0zln9ABze0%2FxrFpALsHj3V9snlLtaJJ4kwwc3qUceMzobwWM6%2B3pO%2BrSw9yKN%2FvCEfOqDaBBro9us0B6vCVumLiCM7DJx0WjbKZwtm37A6Sf&X-Amz-Signature=56d9c7cf372d0bc0390136494d0f4da0283c14a9b87caee8a06e591f1b96f5cb&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XUVTJA2B%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T025209Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDgaCXVzLXdlc3QtMiJIMEYCIQDQBnODhaFbwhJE2gWOxeNRQa0B9f6dT0qnsMYrk32EMgIhAK4AEfEyqlUd3skIofCafPdwOel0Fr%2FDeMLq6IoYYtbQKv8DCFEQABoMNjM3NDIzMTgzODA1IgwCy0LYs4zyEi5sqtEq3APPDnMLvDzXdT%2Fc9jK0d6rn2F5Qe8pUQF1poSv99mkQfjreh3Azu825PjG3B6h86TnIPwCwr8GH%2FZg3yJ4UKIc6lw9lpVFXuS7OIfrrxyECReaas70tTazIZhdpXVsd9ydW5eOH0kYdkwiuo4Vtck9knBt9fhvdwJFkh8eOjkZxWLgszaVzFte8jX7NnnsqNhGTuoC4rz9%2FnBVbORmfH%2FQMg0tHRmOuTSKPH%2BSYMmLGnZomYSgBVi1tT6K5gSx193M%2FVWnsiLimppGyf4tZRWrl7NZSsZZDUneWcrlen6QeD%2F2uBVG2dtWMm2REP4QXOSybN16sD%2Bg0k%2FimYZUrhifPz%2F1kew4rh5CNqol5R82b3g0z0458T3huLOqLBIv8902Damnt5VLcBVLNGePrYdTJYZfKgQ03J1tZuMxTktjdCbpj70Ic2DuQnsYccKwYJ5FyuY%2BiTfNfkpYlydu2wt%2BnPE%2BnLW%2FNUgSUaaGMoj8BSl1BvDxiSQWtvVkH8SPRokACa7OamwdVNFyq9PehftQHMOQ3DFBYr0ehwcYTLcNaFaWeKWYwGFKvebuYRJZpy2VqgRxBeZGn9%2BDEq%2BTKwdFgcOUvmrkXgA%2F3X%2BHhYauRUVjnYTQTtYEwB%2BxC5zDH7I%2B9BjqkAdVIda5Jvd5CYI8Zt5fx0Hl6%2FurV9lfmOWnlU3gricZcCBUQxPasnrrQ76L4LP29zFkYg%2FjwsSnIzJgB%2FJiaX1dtEsZPCpSSjigq7vzE4aTlez%2FZ0zln9ABze0%2FxrFpALsHj3V9snlLtaJJ4kwwc3qUceMzobwWM6%2B3pO%2BrSw9yKN%2FvCEfOqDaBBro9us0B6vCVumLiCM7DJx0WjbKZwtm37A6Sf&X-Amz-Signature=46dd1de65fac35e2431267847258f02d8019b9eb7a1f4a0ed29dbbd399883195&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XUVTJA2B%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T025209Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDgaCXVzLXdlc3QtMiJIMEYCIQDQBnODhaFbwhJE2gWOxeNRQa0B9f6dT0qnsMYrk32EMgIhAK4AEfEyqlUd3skIofCafPdwOel0Fr%2FDeMLq6IoYYtbQKv8DCFEQABoMNjM3NDIzMTgzODA1IgwCy0LYs4zyEi5sqtEq3APPDnMLvDzXdT%2Fc9jK0d6rn2F5Qe8pUQF1poSv99mkQfjreh3Azu825PjG3B6h86TnIPwCwr8GH%2FZg3yJ4UKIc6lw9lpVFXuS7OIfrrxyECReaas70tTazIZhdpXVsd9ydW5eOH0kYdkwiuo4Vtck9knBt9fhvdwJFkh8eOjkZxWLgszaVzFte8jX7NnnsqNhGTuoC4rz9%2FnBVbORmfH%2FQMg0tHRmOuTSKPH%2BSYMmLGnZomYSgBVi1tT6K5gSx193M%2FVWnsiLimppGyf4tZRWrl7NZSsZZDUneWcrlen6QeD%2F2uBVG2dtWMm2REP4QXOSybN16sD%2Bg0k%2FimYZUrhifPz%2F1kew4rh5CNqol5R82b3g0z0458T3huLOqLBIv8902Damnt5VLcBVLNGePrYdTJYZfKgQ03J1tZuMxTktjdCbpj70Ic2DuQnsYccKwYJ5FyuY%2BiTfNfkpYlydu2wt%2BnPE%2BnLW%2FNUgSUaaGMoj8BSl1BvDxiSQWtvVkH8SPRokACa7OamwdVNFyq9PehftQHMOQ3DFBYr0ehwcYTLcNaFaWeKWYwGFKvebuYRJZpy2VqgRxBeZGn9%2BDEq%2BTKwdFgcOUvmrkXgA%2F3X%2BHhYauRUVjnYTQTtYEwB%2BxC5zDH7I%2B9BjqkAdVIda5Jvd5CYI8Zt5fx0Hl6%2FurV9lfmOWnlU3gricZcCBUQxPasnrrQ76L4LP29zFkYg%2FjwsSnIzJgB%2FJiaX1dtEsZPCpSSjigq7vzE4aTlez%2FZ0zln9ABze0%2FxrFpALsHj3V9snlLtaJJ4kwwc3qUceMzobwWM6%2B3pO%2BrSw9yKN%2FvCEfOqDaBBro9us0B6vCVumLiCM7DJx0WjbKZwtm37A6Sf&X-Amz-Signature=795f7fd90de6ab0d90ec533113f6664713528b386e254a7a35cd332187d11f5b&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WGOFCATF%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T025211Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDgaCXVzLXdlc3QtMiJHMEUCIHHO%2BsG52OleL%2BE6%2FAgAV9q41ieFC1NZ7tdzLSKHpZ4nAiEAj7tdDiOU8BgB01%2F9rGEY8RSEtwFdAFFspd%2BU10SoFcwq%2FwMIURAAGgw2Mzc0MjMxODM4MDUiDHadeIlPQFc40sXhuircAy4FRoJLEEPLIuabJucmrpzE6S43ozmUJ9KoK93R4P55ET1Hm6XM%2Fm6x2YhVFQvcnaKEY4KabcAOlNxDzdNgvjADX1kmZY5hSumSIwtSoHADjUpZRZWFnfqGBxlMdNSMKDstCCkPbdFzZe1Uu9XohIZFD0jmv7RI3%2F8DC7Y%2BNelxSBlKOzCW9lPL0hg2DhO%2FfXr27vqc3yPR6vmqqdCchIfZpKs7xl%2Fl1BnCmSTg9vtnCAu8JepVi90lgBnFTrJ0dwDJ5GLQaOc%2BB2sD9etoWRSay%2FC%2FS0wU3iwUM9B8%2B1zCh94z9AnLCbWT4N%2FbMeIi6rNDmqVW8RcSCXJ4vtO0dtVaOimq5hTEAOhEeNfC90SKlkM3H5VYLOptyCx2m58iI5XIJwcrC5baGTii%2FOgkY45c%2FDwfV6f37HVZ%2B%2BRT2%2F0Z4sRfWWbQet08xdWS1%2FKTeK1InaTe7uEPj%2FxC7DWlfEPHSMKVQYh9ffgUj9jfxF1tJCOrbmiILRksgphEWNIDfrj3%2B081SpbyueOAiIY6HfIsRaId64xL6twHdkgeoJMMmYoFikxvfhXuF%2B%2FUDDI9ISApoEh%2Bv4MQMJfym7M2CvTs6Dg8EnYpIW54AdPMMJKm09AzPtou5Oiz0YpPMNLsj70GOqUBHqdw%2BY5BmO%2FCDtdv457pYB4D7JK4Ov0HQDOi5vszlaWpj30F%2BkmkHlwinahb4LA4vNl2pu6wzyHU0sKAGjDfD6jZdxXnd0DXuCES2D3a3tDtab%2F9Q1AJk1tRVV1oi6GpEvjVihO9vdgfrJi%2FWTH05J1gcrgUxzeC2lyWgUSdalXwBq3xfScZ2md2W0X%2F2zCEQXGLpgMgwRYEDqd%2BYhOJtk5nlsLk&X-Amz-Signature=4b608b48bc33edfa0ab8f8fc9ceb1fb96686064cf8a12b36f2c5231695e19d82&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666G5EPCY7%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T025212Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDgaCXVzLXdlc3QtMiJGMEQCIF1RnFMkfx86Qq4%2FAWvkO81p9f6E3vvJ15PjKE86iXVDAiBfn0mnppVnJNlm9bA41SL%2FxknzOQUw5xnhbvd0QFgzTyr%2FAwhREAAaDDYzNzQyMzE4MzgwNSIMbDVAmH9xR%2FcnGtTNKtwDACMhu3LRKPJzbn3h4K1AWhtZWYzyR9hHuB%2BlKug%2FW69oWSapbGlP%2BJA2HPvmPSEOlmHFFjzWMJMJntTY8xmiEaiTjg948WekWqmH52ovT7e5eQBRT3xcO7QGQxvcW%2F8g9AWCYUBijei4GeTrIXzBTXLbFiL6HELfLuQihRlCR7MTmX8BHk%2BLcHUfDRTIFLB3HOHyn2O9nRBnGZxnytT57Sb%2BcJ9zxWOuoIATtTzhJvBMqasCdue86obPINey8pWb7pTQ9c%2BbQIGiaa2PNRs7PaUPqk85MKTSiL6nAVd3G1vKbYL5ZGooRXMW80kC2rLrqenEIEW60xS1v3bt8wj0DnFRlhiEpt8Havy1Mu2AEFj2SAVd4y%2FsTLssj%2BP1n94v88%2FLeneVlk9jhc%2FPS2zVdXFCZ4Wc5rOTFJ1BlGqez2MWvBXoshuGOJOHVQtz%2BICvrrtRFZOCjmAyYjavQcPAUnFHY%2FIDkh2h7KkcssLuoE58iSRtFTt0mIRBDAwEM5WcxNC9m%2B%2FwNsH9zWdC9lId%2BejeYldf%2B%2FWH%2F4hXTa7zXGd6NSeNjEKp3xBYS4gp9rx8FU7mUcQpPhg7NchTF75nSvYVWnn4UwvrcC1G8Tz81DNNBstE0Nwbo12fIxUwveyPvQY6pgH%2BjTnP8Wwa3P7qUYG9y1ZF7MCOvNDhxZsPwbqyEdbCFyuXeWSrItLRMv6iFfUqE5OvW5vgoAydd7AGfav21Ka0A3K1nmVWWI1aFl5eGKnZOx9hm8P4zyfvEXDFBaweQi2%2B1L1O8nHvein8nq1bTU2lbiZHat3Ejy8OtU255KqTf0eWdf%2F5F%2F2sJDQg0ut5lhUNqh8sm%2BcjaCRIIgZSzp815VywqQdW&X-Amz-Signature=4060b51f6b576a39adcf5bc95ed962b5a5f759d0131087b820eede1a877d1b05&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XUVTJA2B%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T025209Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDgaCXVzLXdlc3QtMiJIMEYCIQDQBnODhaFbwhJE2gWOxeNRQa0B9f6dT0qnsMYrk32EMgIhAK4AEfEyqlUd3skIofCafPdwOel0Fr%2FDeMLq6IoYYtbQKv8DCFEQABoMNjM3NDIzMTgzODA1IgwCy0LYs4zyEi5sqtEq3APPDnMLvDzXdT%2Fc9jK0d6rn2F5Qe8pUQF1poSv99mkQfjreh3Azu825PjG3B6h86TnIPwCwr8GH%2FZg3yJ4UKIc6lw9lpVFXuS7OIfrrxyECReaas70tTazIZhdpXVsd9ydW5eOH0kYdkwiuo4Vtck9knBt9fhvdwJFkh8eOjkZxWLgszaVzFte8jX7NnnsqNhGTuoC4rz9%2FnBVbORmfH%2FQMg0tHRmOuTSKPH%2BSYMmLGnZomYSgBVi1tT6K5gSx193M%2FVWnsiLimppGyf4tZRWrl7NZSsZZDUneWcrlen6QeD%2F2uBVG2dtWMm2REP4QXOSybN16sD%2Bg0k%2FimYZUrhifPz%2F1kew4rh5CNqol5R82b3g0z0458T3huLOqLBIv8902Damnt5VLcBVLNGePrYdTJYZfKgQ03J1tZuMxTktjdCbpj70Ic2DuQnsYccKwYJ5FyuY%2BiTfNfkpYlydu2wt%2BnPE%2BnLW%2FNUgSUaaGMoj8BSl1BvDxiSQWtvVkH8SPRokACa7OamwdVNFyq9PehftQHMOQ3DFBYr0ehwcYTLcNaFaWeKWYwGFKvebuYRJZpy2VqgRxBeZGn9%2BDEq%2BTKwdFgcOUvmrkXgA%2F3X%2BHhYauRUVjnYTQTtYEwB%2BxC5zDH7I%2B9BjqkAdVIda5Jvd5CYI8Zt5fx0Hl6%2FurV9lfmOWnlU3gricZcCBUQxPasnrrQ76L4LP29zFkYg%2FjwsSnIzJgB%2FJiaX1dtEsZPCpSSjigq7vzE4aTlez%2FZ0zln9ABze0%2FxrFpALsHj3V9snlLtaJJ4kwwc3qUceMzobwWM6%2B3pO%2BrSw9yKN%2FvCEfOqDaBBro9us0B6vCVumLiCM7DJx0WjbKZwtm37A6Sf&X-Amz-Signature=a8c40df2d9455fc1d6929397face2c600d57e8e6bbf907d3b96f8b2d84bb2d9b&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XUVTJA2B%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T025209Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDgaCXVzLXdlc3QtMiJIMEYCIQDQBnODhaFbwhJE2gWOxeNRQa0B9f6dT0qnsMYrk32EMgIhAK4AEfEyqlUd3skIofCafPdwOel0Fr%2FDeMLq6IoYYtbQKv8DCFEQABoMNjM3NDIzMTgzODA1IgwCy0LYs4zyEi5sqtEq3APPDnMLvDzXdT%2Fc9jK0d6rn2F5Qe8pUQF1poSv99mkQfjreh3Azu825PjG3B6h86TnIPwCwr8GH%2FZg3yJ4UKIc6lw9lpVFXuS7OIfrrxyECReaas70tTazIZhdpXVsd9ydW5eOH0kYdkwiuo4Vtck9knBt9fhvdwJFkh8eOjkZxWLgszaVzFte8jX7NnnsqNhGTuoC4rz9%2FnBVbORmfH%2FQMg0tHRmOuTSKPH%2BSYMmLGnZomYSgBVi1tT6K5gSx193M%2FVWnsiLimppGyf4tZRWrl7NZSsZZDUneWcrlen6QeD%2F2uBVG2dtWMm2REP4QXOSybN16sD%2Bg0k%2FimYZUrhifPz%2F1kew4rh5CNqol5R82b3g0z0458T3huLOqLBIv8902Damnt5VLcBVLNGePrYdTJYZfKgQ03J1tZuMxTktjdCbpj70Ic2DuQnsYccKwYJ5FyuY%2BiTfNfkpYlydu2wt%2BnPE%2BnLW%2FNUgSUaaGMoj8BSl1BvDxiSQWtvVkH8SPRokACa7OamwdVNFyq9PehftQHMOQ3DFBYr0ehwcYTLcNaFaWeKWYwGFKvebuYRJZpy2VqgRxBeZGn9%2BDEq%2BTKwdFgcOUvmrkXgA%2F3X%2BHhYauRUVjnYTQTtYEwB%2BxC5zDH7I%2B9BjqkAdVIda5Jvd5CYI8Zt5fx0Hl6%2FurV9lfmOWnlU3gricZcCBUQxPasnrrQ76L4LP29zFkYg%2FjwsSnIzJgB%2FJiaX1dtEsZPCpSSjigq7vzE4aTlez%2FZ0zln9ABze0%2FxrFpALsHj3V9snlLtaJJ4kwwc3qUceMzobwWM6%2B3pO%2BrSw9yKN%2FvCEfOqDaBBro9us0B6vCVumLiCM7DJx0WjbKZwtm37A6Sf&X-Amz-Signature=9f93ccb1afaa68b786e22bebfe05931983ae380529c8a3af7e8e16c54d5816ec&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XUVTJA2B%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T025209Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDgaCXVzLXdlc3QtMiJIMEYCIQDQBnODhaFbwhJE2gWOxeNRQa0B9f6dT0qnsMYrk32EMgIhAK4AEfEyqlUd3skIofCafPdwOel0Fr%2FDeMLq6IoYYtbQKv8DCFEQABoMNjM3NDIzMTgzODA1IgwCy0LYs4zyEi5sqtEq3APPDnMLvDzXdT%2Fc9jK0d6rn2F5Qe8pUQF1poSv99mkQfjreh3Azu825PjG3B6h86TnIPwCwr8GH%2FZg3yJ4UKIc6lw9lpVFXuS7OIfrrxyECReaas70tTazIZhdpXVsd9ydW5eOH0kYdkwiuo4Vtck9knBt9fhvdwJFkh8eOjkZxWLgszaVzFte8jX7NnnsqNhGTuoC4rz9%2FnBVbORmfH%2FQMg0tHRmOuTSKPH%2BSYMmLGnZomYSgBVi1tT6K5gSx193M%2FVWnsiLimppGyf4tZRWrl7NZSsZZDUneWcrlen6QeD%2F2uBVG2dtWMm2REP4QXOSybN16sD%2Bg0k%2FimYZUrhifPz%2F1kew4rh5CNqol5R82b3g0z0458T3huLOqLBIv8902Damnt5VLcBVLNGePrYdTJYZfKgQ03J1tZuMxTktjdCbpj70Ic2DuQnsYccKwYJ5FyuY%2BiTfNfkpYlydu2wt%2BnPE%2BnLW%2FNUgSUaaGMoj8BSl1BvDxiSQWtvVkH8SPRokACa7OamwdVNFyq9PehftQHMOQ3DFBYr0ehwcYTLcNaFaWeKWYwGFKvebuYRJZpy2VqgRxBeZGn9%2BDEq%2BTKwdFgcOUvmrkXgA%2F3X%2BHhYauRUVjnYTQTtYEwB%2BxC5zDH7I%2B9BjqkAdVIda5Jvd5CYI8Zt5fx0Hl6%2FurV9lfmOWnlU3gricZcCBUQxPasnrrQ76L4LP29zFkYg%2FjwsSnIzJgB%2FJiaX1dtEsZPCpSSjigq7vzE4aTlez%2FZ0zln9ABze0%2FxrFpALsHj3V9snlLtaJJ4kwwc3qUceMzobwWM6%2B3pO%2BrSw9yKN%2FvCEfOqDaBBro9us0B6vCVumLiCM7DJx0WjbKZwtm37A6Sf&X-Amz-Signature=a4078a27459d62b8059b34ec3ec8386c031ada6a03793ddbcdcc0da128ba971f&X-Amz-SignedHeaders=host&x-id=GetObject)


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

