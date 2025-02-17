---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4662EH73HWD%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250217T025605Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEEEaCXVzLXdlc3QtMiJHMEUCIF9VsET4WhnrUb88TDeW2svacE1sByrVg84bUjTWR89cAiEA1jX\
  DH8JDtIStnSRh%2FzC7WXCm4QoVbN17K1M%2FMaFTb%2BAq%2FwMIahAAGgw2Mzc0MjMxODM4MDUi\
  DOtyUEtNggilGTsnHircA5IOrkxlxVl0fSzFljOn9sz%2BLkSk1NppCA79TO7kM4hAd2%2B8ZvUXP\
  JkkKkOKaPMgWSiTPDhmujWe2NjonoO42tD%2BjVSEQzUxhowc7yNXcEWpMqsjgENnS%2F0U3wVwz7\
  HnDoU3xJWMefG8JtmeF6EgqjA3FGV3yC92iK%2F0A9xfEudJQjulXY1hOh5%2BIO9nzLPnDNnXbUq\
  iFVa7Xpiw3gcoeEDV2mqS2COc1oc9UEEvsVPO02bSGGSFj1hK0no%2FJZP8YX6WZuOSMeIuYBAsip\
  AJrUFFle7gTO4oxQjXH8u%2FahoHSQVp2Y1gp4f1BvUgfbYQ2rsxQgDzoN8uOTsxo3aqouU0hbkuI\
  B9WQqZ8l0AsbeZGhgdPQNZlIB1zA6W78hsD0x6TcE3GQSYJhJKj0t77XPiX6fRtlrGS8WBpnV%2F5\
  zulp%2B8b8l89AEpzheaMxSVVnBjj8eOlfWqcCNeOVqSSvn67sTQKWt7pNGy29qst2biglmL6zb%2\
  FluiybPxAIho9oCPjEZRrYTBRtEWW2uFRJD4diS1XIW0NYd8ykAh7lhAQIVwXJGLf%2BcV83phvxD\
  ym5ZQokrruXHcRP8hIUcXfU8RgBuSmAm99VweMr%2FjSL3fOZFfORyqPnMmcILG4KUMI%2Bcyr0GO\
  qUBtsG7EmJ5JV9k4Tb3otX3aw9e1QML1DsYHSdmx0NBJgQnhJN%2BSJfS4weYByirU5RlEg6rNSCO\
  Xo8c%2BG3z9gHcSauysYH%2F33m9idmG06FVbI91qe72Ee93ychKumKkmAndKxduX3%2FkhSW8S1T\
  4jB4vItB0mGketcjqTSEZXw5QCuCGjx6UwWi4yc506qeLbd8Xr7VwVgC38b8QXRHfLR7HdJMYpwjB\
  &X-Amz-Signature=c59f93b006489e1bef98767501956c1b74c15ae60cb0ed436797375e201a\
  3340&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466ZEUGGX4Z%2F20250217%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250217T025447Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJGMEQCIBlUtSaX60WfbOR6vFjYSIOKaW2OnxO\
        kThp1VUQGhPboAiAQwt7Apg3bJkubfLALbFLskeVhtvwkcGIrRQZ6teBlvCr%2FAwhqEAAa\
        DDYzNzQyMzE4MzgwNSIMmgg7iyJNXZpI6FkyKtwDch3xrlhRp3osb4C%2FljBo4f4Htjvyw\
        IBsj82OaEWp3m0gyoskUPH%2Fb%2FqJSOAcWwjD803fKKiR2Jobk61JCTam0MvTHHgTSDDx\
        an%2BWK9A5sOjPjQaf0cw3zf2qScLhzzu%2FXd389qHENLtJJweklF4reUXxreXvhoKVoCX\
        UKYqHMIkUWYMOjj8NbMbdpdfxSmtm%2B2v43ycjI08jqcEfACe8gusx6%2BrJylLEfOJig2\
        fJ0KBjFND40Wf4pVhb3%2FZc3eb3hYckCEaRyOpXcGnbmY4fc838CTQcw9MSh0Ey0uZxIE2\
        PlNoDb0BPekQIHO1aLnVIJE%2F7Y8rXtCM4AIqRZPIQ04KT%2BEv3NkKdX3DsdshcUt7Rgx\
        xWXbXg7wXryTbcfLyxaB6wqx440BlTblK1eZ5ECX%2FyX2l%2BwtPgDz9vCX2wbhe79NxNY\
        8UpP7UBbRGdTW%2FlFbx1EC07TNb63YbWuWlSygsjFvglOIdxDR9tEKK5Yq5C3rr84j6iCz\
        QDNENiKJMVb1lysgMFuxSnG%2BxO4NgV3PkJ%2F%2FBQ%2Bfte88GV7uPD8lKV8UzHuM36Q\
        0tyVBJ8ciDkbUV9a62y630H8uf%2BFJnEcV48aRbxpMhIc6%2FyqF6GzbeUqf28rhFN5MjB\
        vOgwsZvKvQY6pgHrR%2F07%2FUyulzMYBFP%2BL30hAzajBTqoWIc94T4sK%2BOQBEDpZXi\
        %2FafJ88KzRoeSR0Q%2FJOmB8cDXJbP%2BnKqTHWpj%2FBYv4ITvbQgvjF76nS0w1sJ8Dbg\
        2TQVq0Oi%2BLOvHhHvVnEI%2FnUvK%2BShm07eST3mhSdCRBjvJDHwL7ClM%2B0l3oH4TD7\
        PrOyu7Zhu8R584AMOiXO6xi2ArVZ1cC1Rca%2BMg5k3Zkecoa&X-Amz-Signature=2518d\
        8899103825a49554cd796ca62d567515c8d7739176b73c0cbe558fdef9b&X-Amz-Signe\
        dHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-17T03:54:47.219Z"
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
UPDATE_TIME: "2025-02-17T02:56:15.191Z"
EXPIRY_TIME: "2025-02-17T03:55:57.637Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RKRLTYTL%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T025557Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJHMEUCIDqG%2BnLQNhccsWw%2BYGvxAew1Iy1Qinhxu3O15GePoYf3AiEAvfKTR1L2uNTU7QF41x1ihsMQYYOg9Yc%2BYnseUCjUWT4q%2FwMIahAAGgw2Mzc0MjMxODM4MDUiDK%2B1NWKOH9UQlMs69CrcAztPyzi528u7kc7n44KBzFdJePeUHObcaYUvhQ4xfcTK2goytjvZzyNXRsXiGe5IK0yRcGUmrVBnsz4zvhcB0HuzHsqBMVx%2FuPFRLSAUbUp7gnhod38VlnP%2FfnLb3q7fGtjyo%2B60E%2FF7J8gzFdAqZMro3EkdWBKbZK%2B%2FdV8O4T5gg203r1wFTtBv1olYpAGs%2Bm98IeKNkXZr3bZQAjIWR11wsC8ZBmIJVwOgiS9x2RTBqABsbiqPf2PZoRYarM6WJeT6ASCbOu76hR%2BM4rcnJAzZYgmrUlsb5EsOU6hYV5Qv%2FOAFkktiuWFLZPDp1NyMBWF5%2BHZ1YTnE4Fmy0uzei6GcnzQMLhqNYgRs1z1JvOLXdmj%2B97enDWWQcfdS8HZy7rA6DEaMFu3xoponfhNs21Veiotf1D5FTcODhVBnJKXeAcnFnEQm1QBAq88Em%2B64npy5CqP3BN3%2Fy0%2FfmnwyBJHh6xfQV0qnQZ72HhAs06BMD6y3yTnGmsYEraHQPnZ4moXv6Jx3Zz%2BySNkier4k1e4LYAhwgb%2Fo8Gp0nBkNNpOfkuGzF3kyp8%2BiiYyooPeejWmKeLsaTziAH7KlA6m%2F40IfSXlJTRRnoyoX%2FPrLFTNJoqTih0ju9YuWr74TMOabyr0GOqUBd2vx47rx45FfYUkr4WiECbSXV6jlULeFYrBjzEtRX63fYcN9Zs6kVQWowxl445%2FZawaVLelLD2BzfzHR1GLrVNvOK2eM%2FIBga8YVKmr3DJ%2FU048NQYZwE%2ByCKNacv%2FJTBIkiX%2BuxjGQh1Sa5SC1kjV1sVo4t1o8XM5Xz8hnkCYxWdaf6X9JrgT3vp%2FAM12GeDjiGh%2FjMk%2FK4nKigHIjuuKxf0a7W&X-Amz-Signature=3340592e7024b6a7a841b232ecfaef2fd2e800926b6f73826d6ae30188aa54c8&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RKRLTYTL%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T025557Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJHMEUCIDqG%2BnLQNhccsWw%2BYGvxAew1Iy1Qinhxu3O15GePoYf3AiEAvfKTR1L2uNTU7QF41x1ihsMQYYOg9Yc%2BYnseUCjUWT4q%2FwMIahAAGgw2Mzc0MjMxODM4MDUiDK%2B1NWKOH9UQlMs69CrcAztPyzi528u7kc7n44KBzFdJePeUHObcaYUvhQ4xfcTK2goytjvZzyNXRsXiGe5IK0yRcGUmrVBnsz4zvhcB0HuzHsqBMVx%2FuPFRLSAUbUp7gnhod38VlnP%2FfnLb3q7fGtjyo%2B60E%2FF7J8gzFdAqZMro3EkdWBKbZK%2B%2FdV8O4T5gg203r1wFTtBv1olYpAGs%2Bm98IeKNkXZr3bZQAjIWR11wsC8ZBmIJVwOgiS9x2RTBqABsbiqPf2PZoRYarM6WJeT6ASCbOu76hR%2BM4rcnJAzZYgmrUlsb5EsOU6hYV5Qv%2FOAFkktiuWFLZPDp1NyMBWF5%2BHZ1YTnE4Fmy0uzei6GcnzQMLhqNYgRs1z1JvOLXdmj%2B97enDWWQcfdS8HZy7rA6DEaMFu3xoponfhNs21Veiotf1D5FTcODhVBnJKXeAcnFnEQm1QBAq88Em%2B64npy5CqP3BN3%2Fy0%2FfmnwyBJHh6xfQV0qnQZ72HhAs06BMD6y3yTnGmsYEraHQPnZ4moXv6Jx3Zz%2BySNkier4k1e4LYAhwgb%2Fo8Gp0nBkNNpOfkuGzF3kyp8%2BiiYyooPeejWmKeLsaTziAH7KlA6m%2F40IfSXlJTRRnoyoX%2FPrLFTNJoqTih0ju9YuWr74TMOabyr0GOqUBd2vx47rx45FfYUkr4WiECbSXV6jlULeFYrBjzEtRX63fYcN9Zs6kVQWowxl445%2FZawaVLelLD2BzfzHR1GLrVNvOK2eM%2FIBga8YVKmr3DJ%2FU048NQYZwE%2ByCKNacv%2FJTBIkiX%2BuxjGQh1Sa5SC1kjV1sVo4t1o8XM5Xz8hnkCYxWdaf6X9JrgT3vp%2FAM12GeDjiGh%2FjMk%2FK4nKigHIjuuKxf0a7W&X-Amz-Signature=12f7ec896372fee25f8327cf5e20e651124e991f38c0b2e492e4c200a1eab6f4&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RKRLTYTL%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T025557Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJHMEUCIDqG%2BnLQNhccsWw%2BYGvxAew1Iy1Qinhxu3O15GePoYf3AiEAvfKTR1L2uNTU7QF41x1ihsMQYYOg9Yc%2BYnseUCjUWT4q%2FwMIahAAGgw2Mzc0MjMxODM4MDUiDK%2B1NWKOH9UQlMs69CrcAztPyzi528u7kc7n44KBzFdJePeUHObcaYUvhQ4xfcTK2goytjvZzyNXRsXiGe5IK0yRcGUmrVBnsz4zvhcB0HuzHsqBMVx%2FuPFRLSAUbUp7gnhod38VlnP%2FfnLb3q7fGtjyo%2B60E%2FF7J8gzFdAqZMro3EkdWBKbZK%2B%2FdV8O4T5gg203r1wFTtBv1olYpAGs%2Bm98IeKNkXZr3bZQAjIWR11wsC8ZBmIJVwOgiS9x2RTBqABsbiqPf2PZoRYarM6WJeT6ASCbOu76hR%2BM4rcnJAzZYgmrUlsb5EsOU6hYV5Qv%2FOAFkktiuWFLZPDp1NyMBWF5%2BHZ1YTnE4Fmy0uzei6GcnzQMLhqNYgRs1z1JvOLXdmj%2B97enDWWQcfdS8HZy7rA6DEaMFu3xoponfhNs21Veiotf1D5FTcODhVBnJKXeAcnFnEQm1QBAq88Em%2B64npy5CqP3BN3%2Fy0%2FfmnwyBJHh6xfQV0qnQZ72HhAs06BMD6y3yTnGmsYEraHQPnZ4moXv6Jx3Zz%2BySNkier4k1e4LYAhwgb%2Fo8Gp0nBkNNpOfkuGzF3kyp8%2BiiYyooPeejWmKeLsaTziAH7KlA6m%2F40IfSXlJTRRnoyoX%2FPrLFTNJoqTih0ju9YuWr74TMOabyr0GOqUBd2vx47rx45FfYUkr4WiECbSXV6jlULeFYrBjzEtRX63fYcN9Zs6kVQWowxl445%2FZawaVLelLD2BzfzHR1GLrVNvOK2eM%2FIBga8YVKmr3DJ%2FU048NQYZwE%2ByCKNacv%2FJTBIkiX%2BuxjGQh1Sa5SC1kjV1sVo4t1o8XM5Xz8hnkCYxWdaf6X9JrgT3vp%2FAM12GeDjiGh%2FjMk%2FK4nKigHIjuuKxf0a7W&X-Amz-Signature=95dc967daa571bfe79cebb2ad04245c2fe36adc7bd8f7c63e5b22a1250d5b4f7&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RKRLTYTL%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T025557Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJHMEUCIDqG%2BnLQNhccsWw%2BYGvxAew1Iy1Qinhxu3O15GePoYf3AiEAvfKTR1L2uNTU7QF41x1ihsMQYYOg9Yc%2BYnseUCjUWT4q%2FwMIahAAGgw2Mzc0MjMxODM4MDUiDK%2B1NWKOH9UQlMs69CrcAztPyzi528u7kc7n44KBzFdJePeUHObcaYUvhQ4xfcTK2goytjvZzyNXRsXiGe5IK0yRcGUmrVBnsz4zvhcB0HuzHsqBMVx%2FuPFRLSAUbUp7gnhod38VlnP%2FfnLb3q7fGtjyo%2B60E%2FF7J8gzFdAqZMro3EkdWBKbZK%2B%2FdV8O4T5gg203r1wFTtBv1olYpAGs%2Bm98IeKNkXZr3bZQAjIWR11wsC8ZBmIJVwOgiS9x2RTBqABsbiqPf2PZoRYarM6WJeT6ASCbOu76hR%2BM4rcnJAzZYgmrUlsb5EsOU6hYV5Qv%2FOAFkktiuWFLZPDp1NyMBWF5%2BHZ1YTnE4Fmy0uzei6GcnzQMLhqNYgRs1z1JvOLXdmj%2B97enDWWQcfdS8HZy7rA6DEaMFu3xoponfhNs21Veiotf1D5FTcODhVBnJKXeAcnFnEQm1QBAq88Em%2B64npy5CqP3BN3%2Fy0%2FfmnwyBJHh6xfQV0qnQZ72HhAs06BMD6y3yTnGmsYEraHQPnZ4moXv6Jx3Zz%2BySNkier4k1e4LYAhwgb%2Fo8Gp0nBkNNpOfkuGzF3kyp8%2BiiYyooPeejWmKeLsaTziAH7KlA6m%2F40IfSXlJTRRnoyoX%2FPrLFTNJoqTih0ju9YuWr74TMOabyr0GOqUBd2vx47rx45FfYUkr4WiECbSXV6jlULeFYrBjzEtRX63fYcN9Zs6kVQWowxl445%2FZawaVLelLD2BzfzHR1GLrVNvOK2eM%2FIBga8YVKmr3DJ%2FU048NQYZwE%2ByCKNacv%2FJTBIkiX%2BuxjGQh1Sa5SC1kjV1sVo4t1o8XM5Xz8hnkCYxWdaf6X9JrgT3vp%2FAM12GeDjiGh%2FjMk%2FK4nKigHIjuuKxf0a7W&X-Amz-Signature=dfc60ee2d249ccb3764d4fbdac89a1d4829302e2bed4fe088db73723bfc79fde&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RKRLTYTL%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T025557Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJHMEUCIDqG%2BnLQNhccsWw%2BYGvxAew1Iy1Qinhxu3O15GePoYf3AiEAvfKTR1L2uNTU7QF41x1ihsMQYYOg9Yc%2BYnseUCjUWT4q%2FwMIahAAGgw2Mzc0MjMxODM4MDUiDK%2B1NWKOH9UQlMs69CrcAztPyzi528u7kc7n44KBzFdJePeUHObcaYUvhQ4xfcTK2goytjvZzyNXRsXiGe5IK0yRcGUmrVBnsz4zvhcB0HuzHsqBMVx%2FuPFRLSAUbUp7gnhod38VlnP%2FfnLb3q7fGtjyo%2B60E%2FF7J8gzFdAqZMro3EkdWBKbZK%2B%2FdV8O4T5gg203r1wFTtBv1olYpAGs%2Bm98IeKNkXZr3bZQAjIWR11wsC8ZBmIJVwOgiS9x2RTBqABsbiqPf2PZoRYarM6WJeT6ASCbOu76hR%2BM4rcnJAzZYgmrUlsb5EsOU6hYV5Qv%2FOAFkktiuWFLZPDp1NyMBWF5%2BHZ1YTnE4Fmy0uzei6GcnzQMLhqNYgRs1z1JvOLXdmj%2B97enDWWQcfdS8HZy7rA6DEaMFu3xoponfhNs21Veiotf1D5FTcODhVBnJKXeAcnFnEQm1QBAq88Em%2B64npy5CqP3BN3%2Fy0%2FfmnwyBJHh6xfQV0qnQZ72HhAs06BMD6y3yTnGmsYEraHQPnZ4moXv6Jx3Zz%2BySNkier4k1e4LYAhwgb%2Fo8Gp0nBkNNpOfkuGzF3kyp8%2BiiYyooPeejWmKeLsaTziAH7KlA6m%2F40IfSXlJTRRnoyoX%2FPrLFTNJoqTih0ju9YuWr74TMOabyr0GOqUBd2vx47rx45FfYUkr4WiECbSXV6jlULeFYrBjzEtRX63fYcN9Zs6kVQWowxl445%2FZawaVLelLD2BzfzHR1GLrVNvOK2eM%2FIBga8YVKmr3DJ%2FU048NQYZwE%2ByCKNacv%2FJTBIkiX%2BuxjGQh1Sa5SC1kjV1sVo4t1o8XM5Xz8hnkCYxWdaf6X9JrgT3vp%2FAM12GeDjiGh%2FjMk%2FK4nKigHIjuuKxf0a7W&X-Amz-Signature=2cbd571ee00ee1ee87403fff0cee8e0d602244678d11827f11417a7c20f6cc39&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TWE7ZJJS%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T025604Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJGMEQCIGKLj1hV1saoXk2MZanF5d6%2F%2Bb%2F%2FqwNLcIsblfe7a%2FI2AiAOrj36fNQSG2Ea05x7MwKsjVf1x5M4ki%2FIkvXQccPQqCr%2FAwhqEAAaDDYzNzQyMzE4MzgwNSIM24GmSAJexK03FimkKtwDQRCW%2FrIud%2BDDwOEBeUwAFgPOUzGAE1V8v%2FtShwDaYV2JBLHHsl3T%2B6%2BH9STtAIK0%2FMV4fquzlk26r2HulFJlXN3Nm%2FOct5ZpTnF32g4YGWpxKVh7CTXErTdCMlY57w4rz4UHB45FIhB70hubBR4f5iherDQjxqF0hzWWjsto3reN51JV0mWKaztuUceyaCzSvNO2PGwDD5XAd1BNvVBGXr5l3HoWwDyDEMulpxC%2FZlwGZqK18W49F4ZaqCofNvjYeB5fywkE3QI7jtM4gIwmbaQdeP%2FTT7ODw9iT6NvCnk9frPBKaxqgFqWWjUJt%2B6Pxpr%2Fo5qjVnLdA23pT25CrGM%2B3%2BXsoZuISFfgW5kO5rWjdNafge5xrSgJlWYzpUU13LrgB6hDdCSRN%2BrQHMtjUKkGilupn1%2B4oxDYSJ9TERsmtDAz1opv%2FKhEXEoyDG%2BTgRhLtLxf3P1Spzb77KLiH4eSVgFJGDcmaEWWXDSjVC5omwYkoTqq0q7fZtucgYjaZEAWz0h%2Bk7vO2IucYDvcgZ0tLD%2FyaXvH8MHZpFO%2Bo%2Ff8%2BzsvvgOsoAzL70XaOmWu3xMBy%2FDjBkPpEfpf8LnZV6kcqVvoNldNPYhvOB0bRuPcDf360Mbv3ZeTJeyUw4JvKvQY6pgF0UPUu623DKUBvftRbs8G22eKVaIv3eh17%2FH96xiRGIA7li6UxXr88Vq5kOTO1yGUWqd5OGr7IphztIh1G%2B19D2aJHcCIKqbuV016DpG36pcxbgNw6tMAv1ALAnl9tirsLxLmz4hjFVTeFpb7sJiyZMw67prGcdshMF14QumffQb1vk1zOIXwQ3W0k0suIpEroiUATjWBc8m7oP8JxHxwkdssMO8gZ&X-Amz-Signature=384d01f1b240309f0cc8bf6dd033ea1bbc6e955408863e7d5ec6f5c2630acf84&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466URTKYQSI%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T025605Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEIaCXVzLXdlc3QtMiJGMEQCID%2Bhy8lsVtR3V5dPBmeskWr6YYYGEB5yH4ieWuXG2hfoAiBARgQ18y6%2BI2BMqb9Gbs5MqUosFvNkq4oCcLEzA9WAWyr%2FAwhqEAAaDDYzNzQyMzE4MzgwNSIMkrGaJGFvTwIWU49TKtwDS%2BScmnTrMRYHySjS8bh5jGcJXO%2FPrQ6scJiPMAlhjM%2FJe1fI01q0k%2B%2Fg9IAE%2Bu7jSQ3O%2BCOj31Rj%2FQ7jlTA0FJgtmQPoJPN3m3zbXVScbhserEDE3N2zdegKGFkvG%2FbwjNkrh1imNW1bEq2wEIYE4I%2BwwEGBZb7%2FuNWEvLRoIksUH%2B4fs%2Bsogy6hl5qSYbR8k%2BQmJilO%2Ffgfg7V9LzRqjbRtxWRqVASMJfTy9kBuD53y8Tei5yJXOXMfVEUAErkMRC%2BTyz0pgy8Vts%2FknllGq%2By53hvRj8dYcnm0SOdVvAGrrYRUeUmfThyCJm1Jnlme0e3PrRbdMzQM%2FvRyhJfSqT6oITFDNFnxvx0b4oHYsgtW6At2V5kpBzv6LG3aG0jjMFNpVmh1daPFhnoaFo8ebE3EfDQLsm5VT%2BsqLL5BY9yivdxpgrPBfG%2BnxeW%2BH84Mc%2FuGMaZBbMsRCwv7%2B8cyGdEVqBABeTDfv%2BpOqIdSl%2Bcg8ObAyeWaW29xqnLE3veSine%2BE%2FLRmIZGCeYNDEz32AJceYkuujTr0goI8vrgAlYOqN%2BW2JQ8iQx5avmrx01gh%2FpVWFgJ5mFSHSIFo%2FVcBEl74dm9Tu916piXtcYiHrNK%2FcqEh21iOZSD%2F0kw057KvQY6pgHdSLFql2%2BVRe0tRBbvMtvEImkkSqHOTzaZPeTmp6IOtO9pH3fj06%2BhGEZs2sY%2FvLXH5DjREFtiE%2FuXqQIYmaXuDHF3ETsCjQNr7vaNEMdTmFNq6zMwPEBqWXZJgaIsyE19dQEaRjG1Za8w27%2BEyhR73X25NbdKTzFATlOLIB8%2B3SwlKPPXqJl1JQgRuS%2FpfD6ksrjp9lbeDU4gLRXmdzmN9KMdduFP&X-Amz-Signature=b369db844ccc87caae1e495a13b5126806bcec3db427c9f0003d419bcb6c9254&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RKRLTYTL%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T025557Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJHMEUCIDqG%2BnLQNhccsWw%2BYGvxAew1Iy1Qinhxu3O15GePoYf3AiEAvfKTR1L2uNTU7QF41x1ihsMQYYOg9Yc%2BYnseUCjUWT4q%2FwMIahAAGgw2Mzc0MjMxODM4MDUiDK%2B1NWKOH9UQlMs69CrcAztPyzi528u7kc7n44KBzFdJePeUHObcaYUvhQ4xfcTK2goytjvZzyNXRsXiGe5IK0yRcGUmrVBnsz4zvhcB0HuzHsqBMVx%2FuPFRLSAUbUp7gnhod38VlnP%2FfnLb3q7fGtjyo%2B60E%2FF7J8gzFdAqZMro3EkdWBKbZK%2B%2FdV8O4T5gg203r1wFTtBv1olYpAGs%2Bm98IeKNkXZr3bZQAjIWR11wsC8ZBmIJVwOgiS9x2RTBqABsbiqPf2PZoRYarM6WJeT6ASCbOu76hR%2BM4rcnJAzZYgmrUlsb5EsOU6hYV5Qv%2FOAFkktiuWFLZPDp1NyMBWF5%2BHZ1YTnE4Fmy0uzei6GcnzQMLhqNYgRs1z1JvOLXdmj%2B97enDWWQcfdS8HZy7rA6DEaMFu3xoponfhNs21Veiotf1D5FTcODhVBnJKXeAcnFnEQm1QBAq88Em%2B64npy5CqP3BN3%2Fy0%2FfmnwyBJHh6xfQV0qnQZ72HhAs06BMD6y3yTnGmsYEraHQPnZ4moXv6Jx3Zz%2BySNkier4k1e4LYAhwgb%2Fo8Gp0nBkNNpOfkuGzF3kyp8%2BiiYyooPeejWmKeLsaTziAH7KlA6m%2F40IfSXlJTRRnoyoX%2FPrLFTNJoqTih0ju9YuWr74TMOabyr0GOqUBd2vx47rx45FfYUkr4WiECbSXV6jlULeFYrBjzEtRX63fYcN9Zs6kVQWowxl445%2FZawaVLelLD2BzfzHR1GLrVNvOK2eM%2FIBga8YVKmr3DJ%2FU048NQYZwE%2ByCKNacv%2FJTBIkiX%2BuxjGQh1Sa5SC1kjV1sVo4t1o8XM5Xz8hnkCYxWdaf6X9JrgT3vp%2FAM12GeDjiGh%2FjMk%2FK4nKigHIjuuKxf0a7W&X-Amz-Signature=47a5d3cbe4b2548b7d870b287e6d840a3e0b421d401b138db6b70d74ce5cb12d&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RKRLTYTL%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T025558Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJHMEUCIDqG%2BnLQNhccsWw%2BYGvxAew1Iy1Qinhxu3O15GePoYf3AiEAvfKTR1L2uNTU7QF41x1ihsMQYYOg9Yc%2BYnseUCjUWT4q%2FwMIahAAGgw2Mzc0MjMxODM4MDUiDK%2B1NWKOH9UQlMs69CrcAztPyzi528u7kc7n44KBzFdJePeUHObcaYUvhQ4xfcTK2goytjvZzyNXRsXiGe5IK0yRcGUmrVBnsz4zvhcB0HuzHsqBMVx%2FuPFRLSAUbUp7gnhod38VlnP%2FfnLb3q7fGtjyo%2B60E%2FF7J8gzFdAqZMro3EkdWBKbZK%2B%2FdV8O4T5gg203r1wFTtBv1olYpAGs%2Bm98IeKNkXZr3bZQAjIWR11wsC8ZBmIJVwOgiS9x2RTBqABsbiqPf2PZoRYarM6WJeT6ASCbOu76hR%2BM4rcnJAzZYgmrUlsb5EsOU6hYV5Qv%2FOAFkktiuWFLZPDp1NyMBWF5%2BHZ1YTnE4Fmy0uzei6GcnzQMLhqNYgRs1z1JvOLXdmj%2B97enDWWQcfdS8HZy7rA6DEaMFu3xoponfhNs21Veiotf1D5FTcODhVBnJKXeAcnFnEQm1QBAq88Em%2B64npy5CqP3BN3%2Fy0%2FfmnwyBJHh6xfQV0qnQZ72HhAs06BMD6y3yTnGmsYEraHQPnZ4moXv6Jx3Zz%2BySNkier4k1e4LYAhwgb%2Fo8Gp0nBkNNpOfkuGzF3kyp8%2BiiYyooPeejWmKeLsaTziAH7KlA6m%2F40IfSXlJTRRnoyoX%2FPrLFTNJoqTih0ju9YuWr74TMOabyr0GOqUBd2vx47rx45FfYUkr4WiECbSXV6jlULeFYrBjzEtRX63fYcN9Zs6kVQWowxl445%2FZawaVLelLD2BzfzHR1GLrVNvOK2eM%2FIBga8YVKmr3DJ%2FU048NQYZwE%2ByCKNacv%2FJTBIkiX%2BuxjGQh1Sa5SC1kjV1sVo4t1o8XM5Xz8hnkCYxWdaf6X9JrgT3vp%2FAM12GeDjiGh%2FjMk%2FK4nKigHIjuuKxf0a7W&X-Amz-Signature=88f04ed2847b7056b6546643fcb22b96c332f0524f8b67a478b779b5eaec3aa4&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RKRLTYTL%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T025558Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJHMEUCIDqG%2BnLQNhccsWw%2BYGvxAew1Iy1Qinhxu3O15GePoYf3AiEAvfKTR1L2uNTU7QF41x1ihsMQYYOg9Yc%2BYnseUCjUWT4q%2FwMIahAAGgw2Mzc0MjMxODM4MDUiDK%2B1NWKOH9UQlMs69CrcAztPyzi528u7kc7n44KBzFdJePeUHObcaYUvhQ4xfcTK2goytjvZzyNXRsXiGe5IK0yRcGUmrVBnsz4zvhcB0HuzHsqBMVx%2FuPFRLSAUbUp7gnhod38VlnP%2FfnLb3q7fGtjyo%2B60E%2FF7J8gzFdAqZMro3EkdWBKbZK%2B%2FdV8O4T5gg203r1wFTtBv1olYpAGs%2Bm98IeKNkXZr3bZQAjIWR11wsC8ZBmIJVwOgiS9x2RTBqABsbiqPf2PZoRYarM6WJeT6ASCbOu76hR%2BM4rcnJAzZYgmrUlsb5EsOU6hYV5Qv%2FOAFkktiuWFLZPDp1NyMBWF5%2BHZ1YTnE4Fmy0uzei6GcnzQMLhqNYgRs1z1JvOLXdmj%2B97enDWWQcfdS8HZy7rA6DEaMFu3xoponfhNs21Veiotf1D5FTcODhVBnJKXeAcnFnEQm1QBAq88Em%2B64npy5CqP3BN3%2Fy0%2FfmnwyBJHh6xfQV0qnQZ72HhAs06BMD6y3yTnGmsYEraHQPnZ4moXv6Jx3Zz%2BySNkier4k1e4LYAhwgb%2Fo8Gp0nBkNNpOfkuGzF3kyp8%2BiiYyooPeejWmKeLsaTziAH7KlA6m%2F40IfSXlJTRRnoyoX%2FPrLFTNJoqTih0ju9YuWr74TMOabyr0GOqUBd2vx47rx45FfYUkr4WiECbSXV6jlULeFYrBjzEtRX63fYcN9Zs6kVQWowxl445%2FZawaVLelLD2BzfzHR1GLrVNvOK2eM%2FIBga8YVKmr3DJ%2FU048NQYZwE%2ByCKNacv%2FJTBIkiX%2BuxjGQh1Sa5SC1kjV1sVo4t1o8XM5Xz8hnkCYxWdaf6X9JrgT3vp%2FAM12GeDjiGh%2FjMk%2FK4nKigHIjuuKxf0a7W&X-Amz-Signature=edebd1ee8c29e3ee7138d2a345e0d1feb48857d4886abffea145d4354aa1c89e&X-Amz-SignedHeaders=host&x-id=GetObject)


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

