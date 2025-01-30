---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466Z5LIOL4X%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250130T092335Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEJn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIHAMq4qCRHxBpeRScuK\
  ypxS1khkh53c%2F6hQi9Ud38LT5AiEAgVpUiWZvRJ8vv393sUgFRTTOObVWGRbn6XX5KDnikXAqiA\
  QIov%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDAIwnsbHZwfEMITtOir\
  cA0j4z3kPNMy2TGuh6iic9JsEwHK%2BbJyNI3SGjPg3BenzgLGXJlRN7R79RTNY8JAMHpPwoHiNBL\
  %2BqHIERwJPQy6nsvBG79FVLyGMhO4Um1ket%2FKPtLENhpTI8OZ12lLO55iz%2BZjO%2FwkgfLAj\
  mfKyv3FtsKPnYX48Y2BPMqkD6aZdJnz1jUMePNfK5E5q29Z12p3MBpRA%2F8Xj5nDo0pEg4XFOXl2\
  lWTUq6%2FA1B00a3W89kaTtM4pAyeCz0VqNYC1jCqsFLu%2Fm2Ywo5TwKMsB2r9uw6L8xIgxKXzX2\
  JO9Uj99zR4Z%2B0%2BLRxAnOeMjDnjTI8owSroe%2BpwIgZ7mdMF2XUjk7%2BT5bIWUFsWw6kk2KA\
  gVVVUCrDS%2Bg9vhcKSmEKDf9SIDIHH2S1Dn0hlgG3Y0FmqB9hDFVsVBXi5o0qJUgihfw2%2Fd%2F\
  Ez9cN4ljnsWtWckUEMVjYVik8%2BrI%2Bzwrw7tOmkGXb4ubwe19KiTqYFwk1Wsn1rU529C8JmKyD\
  BsSL1agHT79qyBSOrMYhyk0dKLvLb0%2BtYEZDTgAD5M5qchgQcXpY%2FVb0EnTdrjBW6Zeo%2FZ8\
  TQ5dRKsGBcJT8NjnDR9jLTGxxDJ0ualfmaxonO2b80XKzuI4zBk3qs8vWv8%2FvMPbt7LwGOqUBzs\
  24kDD0S7AMP%2BvIK9JVfsIRcAWYElOav5q7%2FtLtjxkz%2FrM%2B5UqJfkWrtzm0kQQeuln0jYz\
  78mEy6eFeFeZqlchnnTT1FKBmgEtzo83CTZ0CH9WeQc8uje8AJSCDjrNjgUOCqg%2FYttl45BqRe6\
  d3HHz%2Bhk1MVDJXHjUnfJ318%2BKAYEuS5m7it1e3TVAn4B0cwHsmiSs7q1ObnYvgjicl%2BPZjk\
  GEU&X-Amz-Signature=b9f22845a7c9051941da4c7ed898a7013789c7f4bb5f3b290d3a735ce\
  dd89eca&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4663NGYS66W%2F20250130%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250130T092228Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEJn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQ\
        CIBVFUVcfCYxnV5Q5E0uVs5Gk1MOBrbou0yWgjM30QOh5AiBdw5026skm%2BinsO1C9lr4e\
        zsfacjCUuj4PJdzgfeV5KCqIBAih%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQ\
        yMzE4MzgwNSIMgoBz368jDy%2BaB1mjKtwDdbeth7V6v85ZZ0xJJ2cUZwFQD7LPM9Oi%2FA\
        Fqs5NHsdnPmbvcvMloNoUnxBSOVgfidqG%2F6mLD8G%2B4VeSLZDzV7P2WCFyE9RyFyaOvn\
        cQ3vATld4kiHtIm4EFZjPD1yK%2F4xks2hK84AWmOTBoQKMLK3NKCcOK%2BnR%2FDPX0Ang\
        IixtLZDrdf0JpYwH1Q5oU%2BZMxtnn%2FHqzrr1mhQlUbXpeE3e%2BdTHONxeopxVqy9h0T\
        IITFXoa8bRIN5KTlbGLDh0GK5MR3ncFNgqo%2B2t%2BnO4rNFN4DvIVAyc8MWXVMLG%2BbO\
        e6iKeaYImVVipzH6dAcjigFLNO1Yd5Xm72H61%2FjDKw6Q6AQ1DmkR6X6NSOyONoG0kVP1W\
        8y9W278xx1QS3WK23vO8yOJKCF6%2B2EiXp%2BjU3%2BQpN6XrYquXtIXJA%2Fbepd64w03\
        e7u27qG0y4ZqX9LkIIljqAvE%2FJYo4DTqLwqQyzIgyF7xoA2DheW%2FYhWmeYQ%2FyDswv\
        7uCbc%2F%2BphEv2o2Izocs6sL%2FgFFhJ%2F684OIReoKy5LADFFPA77ZdVj5G5SCsPsMs\
        q8M0Sc9AxvSk9qremKk1OrTuKHgmfPacyEyi8%2BWFNiBOqJl1e7ukiA1kvqeF8p1bicLWm\
        0gXCEb7HWkwsO3svAY6pgFLgC%2Fdi%2BACZdmDV06DA9AaeIO%2Brzl2331R8uUDTgYPoJ\
        Gq7e76EpRHzwGSffHZul2cy3bsNJtCkWyFgTTDTU0b95EhLlt8xAZmwZ0aWe5tEyia1Hi9u\
        GhHnmhjK5vFkqGImdrO7L%2FbwsI5d60zBZz0Ggluv8xafza06NjKRSYzD6Zrkg4z0nTYCo\
        7GPwrNz8ykQ0qVg3M61fGJLPU45PMdDWpsxI3f&X-Amz-Signature=ca70dffadb571168\
        13e118a7d3848f448e5e544dc769ddc8364d9da1c2e3bc14&X-Amz-SignedHeaders=ho\
        st&x-id=GetObject"
      expiry_time: "2025-01-30T10:22:28.669Z"
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
UPDATE_TIME: "2025-01-30T09:23:43.492Z"
EXPIRY_TIME: "2025-01-30T10:23:33.867Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZSC7M6VH%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T092334Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDetSKIvhJfvumzcHEN3aJ6KepiQlZsAc45UE9cF%2F5wkAIgGXMclgeUG7CVFSU6sX0rIqH9KqHhxcorMqbbLFgaBfwqiAQIov%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDE5MKlc0D1WmyFT%2FBSrcA6n3ksJsfu%2FXP9UEeaoqMvCPHuw9IhvVvdxoZW%2FLLKlFUmPOprc1YqhLSo5joLjy5%2Fge6Hs35UZHUSG8%2Bf4UmU2EubFRujzMlAIkPdchmJIVtrtlf%2B6%2FHvniiS6uzCpnIjdAybeNt2jCjLDeADY9XqKYA9wKeJYz%2By1xEDLm69HvSzQa84rto%2B61DuKcsB6kbWRKJgEbPnzuRTdTtFFarqMyWD6ed6vEDuZ9Q5jkZm7DMghy%2Bk8%2FRkHqa%2BaQWjeXymMyeK1MGLxD8jU2Z%2BLiPLXt442ae7wb9iBr65Sd90MTuq%2FCN7c2MqekVFtps8JAQf5L8T8J1%2BxI%2Fcb1PHA5pjCns%2Bf8AWWce68YrcxGlOY%2BF1fAe0YfedwyhW1hB15eqo7j2tL5peRfF%2FAyt03AzyDvbraEAFx2Z%2BQwjDnOrw39x1e43h9sRHzaxPPwxtrYvOfo9qF7dfUyE5Iaz21vLEsVrnw7aSj9qkcU6960Blo9bpqwMQJVLsuTEiM3PhO9U2W9t6DKZsqeJz%2BQasmV9%2FfHif8Y2KbiKqKoUj%2Bh4%2FGKGlSuPpb3TgXBcbMdyx2enT4v%2F%2Fm51EjghtNsTxUGD92LR1dgfUSXl9LT7IUe2s96cG6QTuY6zdmiDKPXMKTu7LwGOqUBmL5E5uSjz9bpbkz9I82xg5v0scOHvvx1si49fRlcxjdYlSKYfc9Gr1Lp9PAGKfOYpZXIG0HDHuoLgjGJczld12HeyCPEDXc9%2FRIaiEAptwig%2BKjndM85Y%2BdzemAnq1EQ8EVNouWwd%2BCcu%2BYuGlH6tagdyB8ouWQZ8flO5i8lZK%2F3vvAq4qoZiW7QGXneQafPaIkxBR1Vs7tHosWX%2BfSeAUyzOh9Y&X-Amz-Signature=fd940474c280c007a075015d074a5cfe6ca39352886dd04d97340233178f3f41&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZSC7M6VH%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T092334Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDetSKIvhJfvumzcHEN3aJ6KepiQlZsAc45UE9cF%2F5wkAIgGXMclgeUG7CVFSU6sX0rIqH9KqHhxcorMqbbLFgaBfwqiAQIov%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDE5MKlc0D1WmyFT%2FBSrcA6n3ksJsfu%2FXP9UEeaoqMvCPHuw9IhvVvdxoZW%2FLLKlFUmPOprc1YqhLSo5joLjy5%2Fge6Hs35UZHUSG8%2Bf4UmU2EubFRujzMlAIkPdchmJIVtrtlf%2B6%2FHvniiS6uzCpnIjdAybeNt2jCjLDeADY9XqKYA9wKeJYz%2By1xEDLm69HvSzQa84rto%2B61DuKcsB6kbWRKJgEbPnzuRTdTtFFarqMyWD6ed6vEDuZ9Q5jkZm7DMghy%2Bk8%2FRkHqa%2BaQWjeXymMyeK1MGLxD8jU2Z%2BLiPLXt442ae7wb9iBr65Sd90MTuq%2FCN7c2MqekVFtps8JAQf5L8T8J1%2BxI%2Fcb1PHA5pjCns%2Bf8AWWce68YrcxGlOY%2BF1fAe0YfedwyhW1hB15eqo7j2tL5peRfF%2FAyt03AzyDvbraEAFx2Z%2BQwjDnOrw39x1e43h9sRHzaxPPwxtrYvOfo9qF7dfUyE5Iaz21vLEsVrnw7aSj9qkcU6960Blo9bpqwMQJVLsuTEiM3PhO9U2W9t6DKZsqeJz%2BQasmV9%2FfHif8Y2KbiKqKoUj%2Bh4%2FGKGlSuPpb3TgXBcbMdyx2enT4v%2F%2Fm51EjghtNsTxUGD92LR1dgfUSXl9LT7IUe2s96cG6QTuY6zdmiDKPXMKTu7LwGOqUBmL5E5uSjz9bpbkz9I82xg5v0scOHvvx1si49fRlcxjdYlSKYfc9Gr1Lp9PAGKfOYpZXIG0HDHuoLgjGJczld12HeyCPEDXc9%2FRIaiEAptwig%2BKjndM85Y%2BdzemAnq1EQ8EVNouWwd%2BCcu%2BYuGlH6tagdyB8ouWQZ8flO5i8lZK%2F3vvAq4qoZiW7QGXneQafPaIkxBR1Vs7tHosWX%2BfSeAUyzOh9Y&X-Amz-Signature=e23514ae80b04281fd2a6f127fd8474268e5b64fde18de40e20b71198202d466&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZSC7M6VH%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T092334Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDetSKIvhJfvumzcHEN3aJ6KepiQlZsAc45UE9cF%2F5wkAIgGXMclgeUG7CVFSU6sX0rIqH9KqHhxcorMqbbLFgaBfwqiAQIov%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDE5MKlc0D1WmyFT%2FBSrcA6n3ksJsfu%2FXP9UEeaoqMvCPHuw9IhvVvdxoZW%2FLLKlFUmPOprc1YqhLSo5joLjy5%2Fge6Hs35UZHUSG8%2Bf4UmU2EubFRujzMlAIkPdchmJIVtrtlf%2B6%2FHvniiS6uzCpnIjdAybeNt2jCjLDeADY9XqKYA9wKeJYz%2By1xEDLm69HvSzQa84rto%2B61DuKcsB6kbWRKJgEbPnzuRTdTtFFarqMyWD6ed6vEDuZ9Q5jkZm7DMghy%2Bk8%2FRkHqa%2BaQWjeXymMyeK1MGLxD8jU2Z%2BLiPLXt442ae7wb9iBr65Sd90MTuq%2FCN7c2MqekVFtps8JAQf5L8T8J1%2BxI%2Fcb1PHA5pjCns%2Bf8AWWce68YrcxGlOY%2BF1fAe0YfedwyhW1hB15eqo7j2tL5peRfF%2FAyt03AzyDvbraEAFx2Z%2BQwjDnOrw39x1e43h9sRHzaxPPwxtrYvOfo9qF7dfUyE5Iaz21vLEsVrnw7aSj9qkcU6960Blo9bpqwMQJVLsuTEiM3PhO9U2W9t6DKZsqeJz%2BQasmV9%2FfHif8Y2KbiKqKoUj%2Bh4%2FGKGlSuPpb3TgXBcbMdyx2enT4v%2F%2Fm51EjghtNsTxUGD92LR1dgfUSXl9LT7IUe2s96cG6QTuY6zdmiDKPXMKTu7LwGOqUBmL5E5uSjz9bpbkz9I82xg5v0scOHvvx1si49fRlcxjdYlSKYfc9Gr1Lp9PAGKfOYpZXIG0HDHuoLgjGJczld12HeyCPEDXc9%2FRIaiEAptwig%2BKjndM85Y%2BdzemAnq1EQ8EVNouWwd%2BCcu%2BYuGlH6tagdyB8ouWQZ8flO5i8lZK%2F3vvAq4qoZiW7QGXneQafPaIkxBR1Vs7tHosWX%2BfSeAUyzOh9Y&X-Amz-Signature=7815b0ca9dbbf4ef55778c92c026c365d1ab9812018a2aa16e49e1edd7b74079&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZSC7M6VH%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T092334Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDetSKIvhJfvumzcHEN3aJ6KepiQlZsAc45UE9cF%2F5wkAIgGXMclgeUG7CVFSU6sX0rIqH9KqHhxcorMqbbLFgaBfwqiAQIov%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDE5MKlc0D1WmyFT%2FBSrcA6n3ksJsfu%2FXP9UEeaoqMvCPHuw9IhvVvdxoZW%2FLLKlFUmPOprc1YqhLSo5joLjy5%2Fge6Hs35UZHUSG8%2Bf4UmU2EubFRujzMlAIkPdchmJIVtrtlf%2B6%2FHvniiS6uzCpnIjdAybeNt2jCjLDeADY9XqKYA9wKeJYz%2By1xEDLm69HvSzQa84rto%2B61DuKcsB6kbWRKJgEbPnzuRTdTtFFarqMyWD6ed6vEDuZ9Q5jkZm7DMghy%2Bk8%2FRkHqa%2BaQWjeXymMyeK1MGLxD8jU2Z%2BLiPLXt442ae7wb9iBr65Sd90MTuq%2FCN7c2MqekVFtps8JAQf5L8T8J1%2BxI%2Fcb1PHA5pjCns%2Bf8AWWce68YrcxGlOY%2BF1fAe0YfedwyhW1hB15eqo7j2tL5peRfF%2FAyt03AzyDvbraEAFx2Z%2BQwjDnOrw39x1e43h9sRHzaxPPwxtrYvOfo9qF7dfUyE5Iaz21vLEsVrnw7aSj9qkcU6960Blo9bpqwMQJVLsuTEiM3PhO9U2W9t6DKZsqeJz%2BQasmV9%2FfHif8Y2KbiKqKoUj%2Bh4%2FGKGlSuPpb3TgXBcbMdyx2enT4v%2F%2Fm51EjghtNsTxUGD92LR1dgfUSXl9LT7IUe2s96cG6QTuY6zdmiDKPXMKTu7LwGOqUBmL5E5uSjz9bpbkz9I82xg5v0scOHvvx1si49fRlcxjdYlSKYfc9Gr1Lp9PAGKfOYpZXIG0HDHuoLgjGJczld12HeyCPEDXc9%2FRIaiEAptwig%2BKjndM85Y%2BdzemAnq1EQ8EVNouWwd%2BCcu%2BYuGlH6tagdyB8ouWQZ8flO5i8lZK%2F3vvAq4qoZiW7QGXneQafPaIkxBR1Vs7tHosWX%2BfSeAUyzOh9Y&X-Amz-Signature=78fa8442e3341a3627beb95cad87844c11d7d7bd2eeccaac624d9ac9fea496f8&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZSC7M6VH%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T092334Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDetSKIvhJfvumzcHEN3aJ6KepiQlZsAc45UE9cF%2F5wkAIgGXMclgeUG7CVFSU6sX0rIqH9KqHhxcorMqbbLFgaBfwqiAQIov%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDE5MKlc0D1WmyFT%2FBSrcA6n3ksJsfu%2FXP9UEeaoqMvCPHuw9IhvVvdxoZW%2FLLKlFUmPOprc1YqhLSo5joLjy5%2Fge6Hs35UZHUSG8%2Bf4UmU2EubFRujzMlAIkPdchmJIVtrtlf%2B6%2FHvniiS6uzCpnIjdAybeNt2jCjLDeADY9XqKYA9wKeJYz%2By1xEDLm69HvSzQa84rto%2B61DuKcsB6kbWRKJgEbPnzuRTdTtFFarqMyWD6ed6vEDuZ9Q5jkZm7DMghy%2Bk8%2FRkHqa%2BaQWjeXymMyeK1MGLxD8jU2Z%2BLiPLXt442ae7wb9iBr65Sd90MTuq%2FCN7c2MqekVFtps8JAQf5L8T8J1%2BxI%2Fcb1PHA5pjCns%2Bf8AWWce68YrcxGlOY%2BF1fAe0YfedwyhW1hB15eqo7j2tL5peRfF%2FAyt03AzyDvbraEAFx2Z%2BQwjDnOrw39x1e43h9sRHzaxPPwxtrYvOfo9qF7dfUyE5Iaz21vLEsVrnw7aSj9qkcU6960Blo9bpqwMQJVLsuTEiM3PhO9U2W9t6DKZsqeJz%2BQasmV9%2FfHif8Y2KbiKqKoUj%2Bh4%2FGKGlSuPpb3TgXBcbMdyx2enT4v%2F%2Fm51EjghtNsTxUGD92LR1dgfUSXl9LT7IUe2s96cG6QTuY6zdmiDKPXMKTu7LwGOqUBmL5E5uSjz9bpbkz9I82xg5v0scOHvvx1si49fRlcxjdYlSKYfc9Gr1Lp9PAGKfOYpZXIG0HDHuoLgjGJczld12HeyCPEDXc9%2FRIaiEAptwig%2BKjndM85Y%2BdzemAnq1EQ8EVNouWwd%2BCcu%2BYuGlH6tagdyB8ouWQZ8flO5i8lZK%2F3vvAq4qoZiW7QGXneQafPaIkxBR1Vs7tHosWX%2BfSeAUyzOh9Y&X-Amz-Signature=e0d8076f44e3a45818871e9f7e85aae20d331554da86ef5e9549d7b2155aafcc&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663RBPNSKL%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T092334Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIDXE%2Fx4A2iV7cHu7sHjlgqB5oRoJSxCrdjt67rOpySW%2FAiBszSY%2FhuWw3Wf0yt385AtKzd3mVlao5Q6%2FWX30Nyqz7SqIBAih%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM25J%2FZa5sJEq%2FfNbVKtwDf%2FPd3hOMeJH%2FcbTrdn2lIxQEq37Q2Ewd%2BtIp2H%2B7fhz8mUED3qzljgLF3AwWyjUzrFrfizOVDRq2EkcMdvYr%2Fn%2BvYSPabjcpIwXr8FhZDM7YiXKwItRXwW2yIMbl%2B9Oe71WhX5474Uv%2BsWFhg%2BJy5%2FlwUEqEIo4e%2FNmG7L%2FS48y1FEJFlGx8zPWjzvWG3XwEiF8Cb4k9qvvq1OkV94HFMJbYPT00a3%2Bw6BNFKl6Wud0Za7EqOrFrNl3wvZjiKm%2BOf40MBmX3oJ2vQP0SRILpll3UzfYEehwq4YtKBE1139yEMYlKQFtf4ZcG1a80rPNicclSoydxFU%2F%2BLLC6YhbAFxt%2BjXgcukK0dTWLa%2FpDyUegyM9vTLbdjheuTFPrKSKw2367HA2FsDUpM9MpRY5XrPfUMw4licWRzmH1GV871DkUoVAov6SvuEFuskC794h2xIbU06f7%2FfqKPpfiN4mAg9yJNdWtC%2FupebWhg6%2BgvF3hVnzfBryyC2RcHKhtgFUdQo25bkyq06j3WVafsXD3M9lcPYWHCQUPrbVRXbuDfM26sf4e9Z8nWJBBUwgpc5%2B95lx%2FMb0rWY4Y0i%2BNYHYtNMQzBCRa8W6ovjuc4nj7Ksstk9DkrmEHcdXSlmow%2Be3svAY6pgExYr%2ByFyKsJDjZQAlUeZJ2z5c53Eph%2F%2BfQnXfiZ9PXh6N%2FSpGqwLdZtfkf%2Fo3gyIyoj3pdFONKcDUYRu9tS7xuQIxb%2F60BVahVT1WsAxuS1uLTFgOC4oOd4PUoIk%2Bks%2FkSR8gSj9MalvIWDr0p46h513vpzjvGkSal0Xwo6QANqxs4254510MijFL7hgEkHqNrXEJi5%2FX7w0dWo7WDP7ZVt5NvrHjp&X-Amz-Signature=2e5fdf62bf90d2343d88b58a44b32d602d9ca5adfe128d583a0e1ac10113e6d7&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XWQVTAYN%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T092335Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDHSbHhD6bFhGXxX65x%2BzySX9wtoKl9uUL1fcpMuBFXqwIhAN1MWwnCELMBi6i28ECnu6Ia4sgAImckQRHAtQXDtb1mKogECKH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzRmkNmzu%2Fxc4vKg7Qq3AOKQBxrPiNYVWpMnDxSbaPVB%2BdW7%2B%2FZsM0PQUEJ1K8eTm0tBRVU05x%2FkOOCqKLFnaCgZg4Sag2E1rbg7ksgHg0eGOJ7TBc5dDlqB5nwv8dRy7FcxC39x6kORokbol3HWkwEcOXGktvXusIKhbaFniwvDLIqjmQGOcapzPVXblMtIIJXt2%2FCorhNuR2PANciEnmtPDOc5WNLauISuv588L6UP%2Bj%2BrMTjzkNG17SctOGigYWROEOiT8gDeTkAepDJ1EVpa5f%2BM7syyTyHcbLdNgfMPBg7lrQixzqA6tQyR%2BNpYO0YtRsaGPvPwa8nD8%2FE838WEpBkHceW1yqztyIzmz9gvsLaVrrdGJZO027Z3Q5vA42NKZtfM6axRHY%2B%2FvCGFe%2FrVuYFy6p0oRnmULOk7lD0wTCcNOsUXyOonf81fVob1W7%2Bjj6tGiRI36MTjYIyJLuk61WrSfa7ZEBohJnlFf5QOrxkniPJwUrgOXMjav%2BNL4MiKI7i7HZAckPHUjy%2B0ew1f4tH4bZ97GLGMNfRx97w5RLbaqyic4dxW2bpX67MJ5koPXe7R7OK65qvBYVkDbaFfGXLRxPq%2FZLHq0odYLcdQo33Fd03shylRl04aRDOMCHUSQ8PLAxT0IOfATDg7ey8BjqkAR%2FxRpTbSskpfhkci4XTj6xsgt%2B54jvG4CFqzIhI3pDHAC0Zj%2BuU8UDgym6XwdUinjZ7ZitnC6nZTJO1cLpIVW5mJnOdx8GS%2BykLqbectq57Mur8b%2FOEDKJYatzRoRat1%2BRahHTbMnC4ufjH1R5qroY3V27SefoIunaHUq9DVyapRpYvkGRAs7t9zAwlZCI%2FxBU0mZ0LQLPmHJbFPyqgvD9HqbDu&X-Amz-Signature=12a6dc5ce1c5d643be75f4f7f4f56779386a9171b38b0466dc73190deb3527ed&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZSC7M6VH%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T092334Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDetSKIvhJfvumzcHEN3aJ6KepiQlZsAc45UE9cF%2F5wkAIgGXMclgeUG7CVFSU6sX0rIqH9KqHhxcorMqbbLFgaBfwqiAQIov%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDE5MKlc0D1WmyFT%2FBSrcA6n3ksJsfu%2FXP9UEeaoqMvCPHuw9IhvVvdxoZW%2FLLKlFUmPOprc1YqhLSo5joLjy5%2Fge6Hs35UZHUSG8%2Bf4UmU2EubFRujzMlAIkPdchmJIVtrtlf%2B6%2FHvniiS6uzCpnIjdAybeNt2jCjLDeADY9XqKYA9wKeJYz%2By1xEDLm69HvSzQa84rto%2B61DuKcsB6kbWRKJgEbPnzuRTdTtFFarqMyWD6ed6vEDuZ9Q5jkZm7DMghy%2Bk8%2FRkHqa%2BaQWjeXymMyeK1MGLxD8jU2Z%2BLiPLXt442ae7wb9iBr65Sd90MTuq%2FCN7c2MqekVFtps8JAQf5L8T8J1%2BxI%2Fcb1PHA5pjCns%2Bf8AWWce68YrcxGlOY%2BF1fAe0YfedwyhW1hB15eqo7j2tL5peRfF%2FAyt03AzyDvbraEAFx2Z%2BQwjDnOrw39x1e43h9sRHzaxPPwxtrYvOfo9qF7dfUyE5Iaz21vLEsVrnw7aSj9qkcU6960Blo9bpqwMQJVLsuTEiM3PhO9U2W9t6DKZsqeJz%2BQasmV9%2FfHif8Y2KbiKqKoUj%2Bh4%2FGKGlSuPpb3TgXBcbMdyx2enT4v%2F%2Fm51EjghtNsTxUGD92LR1dgfUSXl9LT7IUe2s96cG6QTuY6zdmiDKPXMKTu7LwGOqUBmL5E5uSjz9bpbkz9I82xg5v0scOHvvx1si49fRlcxjdYlSKYfc9Gr1Lp9PAGKfOYpZXIG0HDHuoLgjGJczld12HeyCPEDXc9%2FRIaiEAptwig%2BKjndM85Y%2BdzemAnq1EQ8EVNouWwd%2BCcu%2BYuGlH6tagdyB8ouWQZ8flO5i8lZK%2F3vvAq4qoZiW7QGXneQafPaIkxBR1Vs7tHosWX%2BfSeAUyzOh9Y&X-Amz-Signature=7ec30108d09f77216a14c5c5633b9de822f0cd42b04e890c3c6beb18793d95da&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZSC7M6VH%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T092334Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDetSKIvhJfvumzcHEN3aJ6KepiQlZsAc45UE9cF%2F5wkAIgGXMclgeUG7CVFSU6sX0rIqH9KqHhxcorMqbbLFgaBfwqiAQIov%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDE5MKlc0D1WmyFT%2FBSrcA6n3ksJsfu%2FXP9UEeaoqMvCPHuw9IhvVvdxoZW%2FLLKlFUmPOprc1YqhLSo5joLjy5%2Fge6Hs35UZHUSG8%2Bf4UmU2EubFRujzMlAIkPdchmJIVtrtlf%2B6%2FHvniiS6uzCpnIjdAybeNt2jCjLDeADY9XqKYA9wKeJYz%2By1xEDLm69HvSzQa84rto%2B61DuKcsB6kbWRKJgEbPnzuRTdTtFFarqMyWD6ed6vEDuZ9Q5jkZm7DMghy%2Bk8%2FRkHqa%2BaQWjeXymMyeK1MGLxD8jU2Z%2BLiPLXt442ae7wb9iBr65Sd90MTuq%2FCN7c2MqekVFtps8JAQf5L8T8J1%2BxI%2Fcb1PHA5pjCns%2Bf8AWWce68YrcxGlOY%2BF1fAe0YfedwyhW1hB15eqo7j2tL5peRfF%2FAyt03AzyDvbraEAFx2Z%2BQwjDnOrw39x1e43h9sRHzaxPPwxtrYvOfo9qF7dfUyE5Iaz21vLEsVrnw7aSj9qkcU6960Blo9bpqwMQJVLsuTEiM3PhO9U2W9t6DKZsqeJz%2BQasmV9%2FfHif8Y2KbiKqKoUj%2Bh4%2FGKGlSuPpb3TgXBcbMdyx2enT4v%2F%2Fm51EjghtNsTxUGD92LR1dgfUSXl9LT7IUe2s96cG6QTuY6zdmiDKPXMKTu7LwGOqUBmL5E5uSjz9bpbkz9I82xg5v0scOHvvx1si49fRlcxjdYlSKYfc9Gr1Lp9PAGKfOYpZXIG0HDHuoLgjGJczld12HeyCPEDXc9%2FRIaiEAptwig%2BKjndM85Y%2BdzemAnq1EQ8EVNouWwd%2BCcu%2BYuGlH6tagdyB8ouWQZ8flO5i8lZK%2F3vvAq4qoZiW7QGXneQafPaIkxBR1Vs7tHosWX%2BfSeAUyzOh9Y&X-Amz-Signature=6b5093ef58a5195e07eb17937cc1aa2e60747239501069a6db0bbcce323928b7&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZSC7M6VH%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T092334Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDetSKIvhJfvumzcHEN3aJ6KepiQlZsAc45UE9cF%2F5wkAIgGXMclgeUG7CVFSU6sX0rIqH9KqHhxcorMqbbLFgaBfwqiAQIov%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDE5MKlc0D1WmyFT%2FBSrcA6n3ksJsfu%2FXP9UEeaoqMvCPHuw9IhvVvdxoZW%2FLLKlFUmPOprc1YqhLSo5joLjy5%2Fge6Hs35UZHUSG8%2Bf4UmU2EubFRujzMlAIkPdchmJIVtrtlf%2B6%2FHvniiS6uzCpnIjdAybeNt2jCjLDeADY9XqKYA9wKeJYz%2By1xEDLm69HvSzQa84rto%2B61DuKcsB6kbWRKJgEbPnzuRTdTtFFarqMyWD6ed6vEDuZ9Q5jkZm7DMghy%2Bk8%2FRkHqa%2BaQWjeXymMyeK1MGLxD8jU2Z%2BLiPLXt442ae7wb9iBr65Sd90MTuq%2FCN7c2MqekVFtps8JAQf5L8T8J1%2BxI%2Fcb1PHA5pjCns%2Bf8AWWce68YrcxGlOY%2BF1fAe0YfedwyhW1hB15eqo7j2tL5peRfF%2FAyt03AzyDvbraEAFx2Z%2BQwjDnOrw39x1e43h9sRHzaxPPwxtrYvOfo9qF7dfUyE5Iaz21vLEsVrnw7aSj9qkcU6960Blo9bpqwMQJVLsuTEiM3PhO9U2W9t6DKZsqeJz%2BQasmV9%2FfHif8Y2KbiKqKoUj%2Bh4%2FGKGlSuPpb3TgXBcbMdyx2enT4v%2F%2Fm51EjghtNsTxUGD92LR1dgfUSXl9LT7IUe2s96cG6QTuY6zdmiDKPXMKTu7LwGOqUBmL5E5uSjz9bpbkz9I82xg5v0scOHvvx1si49fRlcxjdYlSKYfc9Gr1Lp9PAGKfOYpZXIG0HDHuoLgjGJczld12HeyCPEDXc9%2FRIaiEAptwig%2BKjndM85Y%2BdzemAnq1EQ8EVNouWwd%2BCcu%2BYuGlH6tagdyB8ouWQZ8flO5i8lZK%2F3vvAq4qoZiW7QGXneQafPaIkxBR1Vs7tHosWX%2BfSeAUyzOh9Y&X-Amz-Signature=5213a8a4935b5608247f3f054a48c884867cbc1dd349c93b2245af61ec9ac575&X-Amz-SignedHeaders=host&x-id=GetObject)


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

