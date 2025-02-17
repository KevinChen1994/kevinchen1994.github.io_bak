---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4666VGH6KWW%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250217T222200Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEFcaCXVzLXdlc3QtMiJHMEUCIQCctq8UCmIJW0iTzdCHfsHHw8KAzOTxzxL1IlPBBBd8dgIga%2\
  BCIWwNIxVahUJWR8ZAUddtdlcoTtaY%2Bvsm0%2BUbPbiAq%2FwMIfxAAGgw2Mzc0MjMxODM4MDUi\
  DCFK%2BLDw%2FU23jZrpcyrcAxTfM1CPSvGXmiTfbEW39MoNAAQvwhDFY%2BqF4ZQUZsVjtESdWux\
  fqmxVotDDUtCwMvlJM%2FeKzzYUiUoVB0YWcfnsLnUAYoZO1sts4M1dugVgsLGCXPmZID%2F9P5XK\
  8TEFDgi%2FnhbXddMgi3XH6F1LXqN%2FiNY%2F%2BfS2O17yByAt%2FjP6pUcflzBEx0kJnb02R42\
  YKqLsWZrpSNBpUk5GjCcCujV62uWQOP56napPIjcWqt9jxcK83pC2Cx3jZt6Wt%2FlAKhCZAf8BQ6\
  jucj8Ub84GZ9KFNFzFTlPBDkPEvUE7%2FhnT6HGcv%2FkBWgJ7JKtmrDOZfiSpX%2BhvOlkfo5svI\
  5%2FQ51NGmagZbuf7hLoZULM4hVKCU4jqM5Gua3lWefGHlyx5CcCX6iGgftaxKGiN2IqwUKrkmklp\
  T6p1mohxkIdmA2T%2BQZRWoOgKsyoLZ3XNFcoIVOHpiVY0Bogm3MSaX3TBX2hB6VA55Pum4t%2Fhf\
  qFneyGxnjJW5Rj06eIzP6fq63iZDJCAscx24esj3U%2FQeK%2FWolVq50HHyzT9x%2BThIfUEqThf\
  8lxkl5ajMbeO4NWxF4DyY8AqeXgmZBkm7EX8wQ919Ffn74bYxBLYfR8SiXhAYn45cPklOapSFP8q9\
  pSgMLfrzr0GOqUBlgHbOTiVcECMATTsi5IRzOmNUQU8PRo6h4yLix8nsnefly8MBF145t9MyCZXdm\
  hgEKXvv8B6Hz7yofBWACQCD5mtSG9ZFPpKcEuPxiw05olSBTAmBWwn2iVtXho81%2Bym8YMRPQOyS\
  PxgWuHZ9CxyCA4I0pT489vRpFwX2Z4%2B3YNQfKOTbDKkVEeiSPbRhEUrqYJ3bC0oYby0Ht2ERuKO\
  1oZxcXnc&X-Amz-Signature=d4a289ca6a0839ac2f08f955fcbcd71d826ca6fdd197813307eb\
  3b022f59c8fd&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466V2M5IXTC%2F20250217%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250217T222051Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEFUaCXVzLXdlc3QtMiJGMEQCIHxUerirQ1zg99EC9WsUBUDlyYeqqma\
        F%2F%2Bb3pD1lp%2F0JAiBmo%2F%2FXga1yDCwfwuCftIbi%2F5%2BX9Y6bBGFNMFa7IqMY\
        iyr%2FAwh%2BEAAaDDYzNzQyMzE4MzgwNSIM%2FGhFiVxL2ze%2Bz6bCKtwDeV4Ye8HbHB1\
        wgsVVHUrHHAMcFgqZJR58JOMvYaiybGsvFC9nDTn9r4yShmmf6nI55jeTdafq4kzQSl8Gjw\
        m9SNbHaZsIjMJa4fyY91DFWFw7OPSBBNe15r8zjWNxQTTaL1p5bRNLN2%2FOI0WlkOh5qBN\
        kXv8vWB2QHxhPIk%2BnYf9lnVRIeNhiGh6Teeq6WR1yidynTjD7MW3q%2FgZQ50T7SuH2d7\
        jHcuEcLwAOe8EPm2ySr1r44LjGcqwMSn%2F536xg3TBSnLQkF6jRmNV84G0RhFjYRDJd8HG\
        gl9%2B20R488C2lD7QRDGRNEFuFhka1rnIxtmzx6KNSgDcRjP9j54hOFnUvAdV%2BjDZIJk\
        GjdtjKUDrykRMfP52lcYQiPZxagO8Y4xGPeNp1O7tsT7rf1%2FsuxNpE5CnwJSHV8xvrJsn\
        CSA6LGJUdYpJA%2F6AgnHfXwUXIKHezIX3DCFgpV9sgMhK9yjPgxeD8sO3EO8%2BrfYU46a\
        Z07e%2B%2F%2BZagHINx%2FbnJU%2F2M9flU%2By7smcbOuykHTqBiETBI7Kt0EEFxkKiEw\
        CjgnhVDrq04YHCsBLhDNpoEeNI2m8wjHwqQshtqZQW3J2%2Ft%2BljMMFxGimcdp1sjHqDc\
        vh88qd6UAcbhUH4xwxcwo8rOvQY6pgG%2FpygVj%2BKewDr68bMfXx%2F78G4MTQhpaeSyZ\
        esCxwc7IlCVUjg%2F54%2FL7xq%2FV%2FiEs93tZT8eiqveCDDzBDUY1rTITAQQkzrZpUXB\
        Pzcmazyz7oBiNDXPKly13cSNE2mvUlLGpsAshqg%2FmZVvMcxtcocGuQkZG%2Bv1t7eTFMO\
        wS%2F9hVFR693VqwbZ96Cicx8gWd%2BvtxCpOQ6kplhsEttzN89eWOrCli684&X-Amz-Sig\
        nature=121edd9a9d2f7185250871deb1721ae26c36c65d9ed09dd621190b8a930e27bb\
        &X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-17T23:20:51.948Z"
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
UPDATE_TIME: "2025-02-17T22:22:05.008Z"
EXPIRY_TIME: "2025-02-17T23:21:58.552Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466R4BWSF6H%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T222158Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFYaCXVzLXdlc3QtMiJIMEYCIQC5%2BJ8EtB8N%2FLDYoCcD%2FXZjEUugA9TtA6tOxrCrPFt9TwIhAKinnOhy%2BkJZmv4NywU3d%2F8xDv1LCeNrze6k383ROI%2FVKv8DCH8QABoMNjM3NDIzMTgzODA1Igy6bJghFMGKNV%2BDZDoq3AOtQnIP0%2BcfaCwkbdVt1Nwdovjsx3wDnD89N4HwJ764Giz2kHnjeSOoHO3%2BPrMn%2F84jOI6GXr4qVFW%2FnOca6uvKA4mDuLJNltedN4VC4NGoBUL6k2b2tqwsq%2BGh5ecYKuf3PrX9PZZa%2BE%2B66%2BepyKQAmnlIi6wnPYtrl3BKd9BLW6WWv6oeAUGLilL3gf%2BMIE1cc4nlu81B%2FEtURh4FHO%2F%2Be79g4QuEYdMsSMSlsT89OoX00XGv2Jej3LiXO4aU97Myr2EF%2FNFe5av8YbV8UYfcOY5W9r1vVjTem0zEAP0wlvcPEfl4fSks3oNBtJPPFY9NaZ3ilpYAemUeKJHIScfOxZPec5xlJZp5Iawznp7g7c07DRRp8oDm7aPDIX6g0bwGXIGnbL%2FTHXSmO%2BEW7NN5PfedmPOrvYHyy44VLTNWmiuyJ86Q%2BdL3qz37y%2BeArauAzCv9yIVx%2FnIGgZaisqYMUTf2TzBql3WcqE3DHVigRIpkHvECUZC79pBu7uYiF9WWQGA8FL9dNB6Ptn%2Bv8D1jXbY%2BroXPRuyjUx1RINNftOb6N7X4cNQr9KZG9eAYf%2FIldlowICts5s7GtSZLmYayLPYw6g0Iq5tLv%2Bs4KNBYHEGDIopDwXDdM%2B4%2F8DC%2F6s69BjqkAQ1eHf7w%2BlwJriNp14kqNjxDs6ZvCot03bD%2FXP0N5NZuMTTlv9QqbHmPCuonSR7jkqk1WV7Nwyiu7BzGWa6%2FPMFhewdSksYlt5k67XAsQKnP9YZFKoHmBqG05d5oXaZ1sPze4x%2B2m0XpBNq%2FGca3pvrRkucbbH4KTZGM1UKLPcHoli0q08o9dmiIi6x1smlwjTAmmgs9QX0GcpXTqwwfKi1GJd%2FR&X-Amz-Signature=526bdd1fec6f517be0dfc0c26a5bbde9393f1c3cde5529af81bad24c10416d9e&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466R4BWSF6H%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T222158Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFYaCXVzLXdlc3QtMiJIMEYCIQC5%2BJ8EtB8N%2FLDYoCcD%2FXZjEUugA9TtA6tOxrCrPFt9TwIhAKinnOhy%2BkJZmv4NywU3d%2F8xDv1LCeNrze6k383ROI%2FVKv8DCH8QABoMNjM3NDIzMTgzODA1Igy6bJghFMGKNV%2BDZDoq3AOtQnIP0%2BcfaCwkbdVt1Nwdovjsx3wDnD89N4HwJ764Giz2kHnjeSOoHO3%2BPrMn%2F84jOI6GXr4qVFW%2FnOca6uvKA4mDuLJNltedN4VC4NGoBUL6k2b2tqwsq%2BGh5ecYKuf3PrX9PZZa%2BE%2B66%2BepyKQAmnlIi6wnPYtrl3BKd9BLW6WWv6oeAUGLilL3gf%2BMIE1cc4nlu81B%2FEtURh4FHO%2F%2Be79g4QuEYdMsSMSlsT89OoX00XGv2Jej3LiXO4aU97Myr2EF%2FNFe5av8YbV8UYfcOY5W9r1vVjTem0zEAP0wlvcPEfl4fSks3oNBtJPPFY9NaZ3ilpYAemUeKJHIScfOxZPec5xlJZp5Iawznp7g7c07DRRp8oDm7aPDIX6g0bwGXIGnbL%2FTHXSmO%2BEW7NN5PfedmPOrvYHyy44VLTNWmiuyJ86Q%2BdL3qz37y%2BeArauAzCv9yIVx%2FnIGgZaisqYMUTf2TzBql3WcqE3DHVigRIpkHvECUZC79pBu7uYiF9WWQGA8FL9dNB6Ptn%2Bv8D1jXbY%2BroXPRuyjUx1RINNftOb6N7X4cNQr9KZG9eAYf%2FIldlowICts5s7GtSZLmYayLPYw6g0Iq5tLv%2Bs4KNBYHEGDIopDwXDdM%2B4%2F8DC%2F6s69BjqkAQ1eHf7w%2BlwJriNp14kqNjxDs6ZvCot03bD%2FXP0N5NZuMTTlv9QqbHmPCuonSR7jkqk1WV7Nwyiu7BzGWa6%2FPMFhewdSksYlt5k67XAsQKnP9YZFKoHmBqG05d5oXaZ1sPze4x%2B2m0XpBNq%2FGca3pvrRkucbbH4KTZGM1UKLPcHoli0q08o9dmiIi6x1smlwjTAmmgs9QX0GcpXTqwwfKi1GJd%2FR&X-Amz-Signature=53fc0981de3b370abc3086f05fba0dbe4c6151f810047de23abe1c16c5314406&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466R4BWSF6H%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T222158Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFYaCXVzLXdlc3QtMiJIMEYCIQC5%2BJ8EtB8N%2FLDYoCcD%2FXZjEUugA9TtA6tOxrCrPFt9TwIhAKinnOhy%2BkJZmv4NywU3d%2F8xDv1LCeNrze6k383ROI%2FVKv8DCH8QABoMNjM3NDIzMTgzODA1Igy6bJghFMGKNV%2BDZDoq3AOtQnIP0%2BcfaCwkbdVt1Nwdovjsx3wDnD89N4HwJ764Giz2kHnjeSOoHO3%2BPrMn%2F84jOI6GXr4qVFW%2FnOca6uvKA4mDuLJNltedN4VC4NGoBUL6k2b2tqwsq%2BGh5ecYKuf3PrX9PZZa%2BE%2B66%2BepyKQAmnlIi6wnPYtrl3BKd9BLW6WWv6oeAUGLilL3gf%2BMIE1cc4nlu81B%2FEtURh4FHO%2F%2Be79g4QuEYdMsSMSlsT89OoX00XGv2Jej3LiXO4aU97Myr2EF%2FNFe5av8YbV8UYfcOY5W9r1vVjTem0zEAP0wlvcPEfl4fSks3oNBtJPPFY9NaZ3ilpYAemUeKJHIScfOxZPec5xlJZp5Iawznp7g7c07DRRp8oDm7aPDIX6g0bwGXIGnbL%2FTHXSmO%2BEW7NN5PfedmPOrvYHyy44VLTNWmiuyJ86Q%2BdL3qz37y%2BeArauAzCv9yIVx%2FnIGgZaisqYMUTf2TzBql3WcqE3DHVigRIpkHvECUZC79pBu7uYiF9WWQGA8FL9dNB6Ptn%2Bv8D1jXbY%2BroXPRuyjUx1RINNftOb6N7X4cNQr9KZG9eAYf%2FIldlowICts5s7GtSZLmYayLPYw6g0Iq5tLv%2Bs4KNBYHEGDIopDwXDdM%2B4%2F8DC%2F6s69BjqkAQ1eHf7w%2BlwJriNp14kqNjxDs6ZvCot03bD%2FXP0N5NZuMTTlv9QqbHmPCuonSR7jkqk1WV7Nwyiu7BzGWa6%2FPMFhewdSksYlt5k67XAsQKnP9YZFKoHmBqG05d5oXaZ1sPze4x%2B2m0XpBNq%2FGca3pvrRkucbbH4KTZGM1UKLPcHoli0q08o9dmiIi6x1smlwjTAmmgs9QX0GcpXTqwwfKi1GJd%2FR&X-Amz-Signature=472fb516d1aaefcadeb1922a58ab1aa283841bc782f365c54bc5f272a5319a8c&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466R4BWSF6H%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T222158Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFYaCXVzLXdlc3QtMiJIMEYCIQC5%2BJ8EtB8N%2FLDYoCcD%2FXZjEUugA9TtA6tOxrCrPFt9TwIhAKinnOhy%2BkJZmv4NywU3d%2F8xDv1LCeNrze6k383ROI%2FVKv8DCH8QABoMNjM3NDIzMTgzODA1Igy6bJghFMGKNV%2BDZDoq3AOtQnIP0%2BcfaCwkbdVt1Nwdovjsx3wDnD89N4HwJ764Giz2kHnjeSOoHO3%2BPrMn%2F84jOI6GXr4qVFW%2FnOca6uvKA4mDuLJNltedN4VC4NGoBUL6k2b2tqwsq%2BGh5ecYKuf3PrX9PZZa%2BE%2B66%2BepyKQAmnlIi6wnPYtrl3BKd9BLW6WWv6oeAUGLilL3gf%2BMIE1cc4nlu81B%2FEtURh4FHO%2F%2Be79g4QuEYdMsSMSlsT89OoX00XGv2Jej3LiXO4aU97Myr2EF%2FNFe5av8YbV8UYfcOY5W9r1vVjTem0zEAP0wlvcPEfl4fSks3oNBtJPPFY9NaZ3ilpYAemUeKJHIScfOxZPec5xlJZp5Iawznp7g7c07DRRp8oDm7aPDIX6g0bwGXIGnbL%2FTHXSmO%2BEW7NN5PfedmPOrvYHyy44VLTNWmiuyJ86Q%2BdL3qz37y%2BeArauAzCv9yIVx%2FnIGgZaisqYMUTf2TzBql3WcqE3DHVigRIpkHvECUZC79pBu7uYiF9WWQGA8FL9dNB6Ptn%2Bv8D1jXbY%2BroXPRuyjUx1RINNftOb6N7X4cNQr9KZG9eAYf%2FIldlowICts5s7GtSZLmYayLPYw6g0Iq5tLv%2Bs4KNBYHEGDIopDwXDdM%2B4%2F8DC%2F6s69BjqkAQ1eHf7w%2BlwJriNp14kqNjxDs6ZvCot03bD%2FXP0N5NZuMTTlv9QqbHmPCuonSR7jkqk1WV7Nwyiu7BzGWa6%2FPMFhewdSksYlt5k67XAsQKnP9YZFKoHmBqG05d5oXaZ1sPze4x%2B2m0XpBNq%2FGca3pvrRkucbbH4KTZGM1UKLPcHoli0q08o9dmiIi6x1smlwjTAmmgs9QX0GcpXTqwwfKi1GJd%2FR&X-Amz-Signature=1344df924142f6245c16883336478837a8d2d1f920991b423f8c66e03ca95e53&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466R4BWSF6H%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T222158Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFYaCXVzLXdlc3QtMiJIMEYCIQC5%2BJ8EtB8N%2FLDYoCcD%2FXZjEUugA9TtA6tOxrCrPFt9TwIhAKinnOhy%2BkJZmv4NywU3d%2F8xDv1LCeNrze6k383ROI%2FVKv8DCH8QABoMNjM3NDIzMTgzODA1Igy6bJghFMGKNV%2BDZDoq3AOtQnIP0%2BcfaCwkbdVt1Nwdovjsx3wDnD89N4HwJ764Giz2kHnjeSOoHO3%2BPrMn%2F84jOI6GXr4qVFW%2FnOca6uvKA4mDuLJNltedN4VC4NGoBUL6k2b2tqwsq%2BGh5ecYKuf3PrX9PZZa%2BE%2B66%2BepyKQAmnlIi6wnPYtrl3BKd9BLW6WWv6oeAUGLilL3gf%2BMIE1cc4nlu81B%2FEtURh4FHO%2F%2Be79g4QuEYdMsSMSlsT89OoX00XGv2Jej3LiXO4aU97Myr2EF%2FNFe5av8YbV8UYfcOY5W9r1vVjTem0zEAP0wlvcPEfl4fSks3oNBtJPPFY9NaZ3ilpYAemUeKJHIScfOxZPec5xlJZp5Iawznp7g7c07DRRp8oDm7aPDIX6g0bwGXIGnbL%2FTHXSmO%2BEW7NN5PfedmPOrvYHyy44VLTNWmiuyJ86Q%2BdL3qz37y%2BeArauAzCv9yIVx%2FnIGgZaisqYMUTf2TzBql3WcqE3DHVigRIpkHvECUZC79pBu7uYiF9WWQGA8FL9dNB6Ptn%2Bv8D1jXbY%2BroXPRuyjUx1RINNftOb6N7X4cNQr9KZG9eAYf%2FIldlowICts5s7GtSZLmYayLPYw6g0Iq5tLv%2Bs4KNBYHEGDIopDwXDdM%2B4%2F8DC%2F6s69BjqkAQ1eHf7w%2BlwJriNp14kqNjxDs6ZvCot03bD%2FXP0N5NZuMTTlv9QqbHmPCuonSR7jkqk1WV7Nwyiu7BzGWa6%2FPMFhewdSksYlt5k67XAsQKnP9YZFKoHmBqG05d5oXaZ1sPze4x%2B2m0XpBNq%2FGca3pvrRkucbbH4KTZGM1UKLPcHoli0q08o9dmiIi6x1smlwjTAmmgs9QX0GcpXTqwwfKi1GJd%2FR&X-Amz-Signature=a31a4093fa074d0833746b27f5476542f9d06a6fb86292e956d00c576ea2dccc&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663AAZUMAD%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T222159Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFYaCXVzLXdlc3QtMiJGMEQCIAn2H09Wv5%2BYNboCuBT9XKuOBMuZqvQnF1q5t6Cq1QVRAiApoTBnS33T2sDdVc67LZblkSIYl4hiQ%2BzRCLMODOqFsir%2FAwh%2FEAAaDDYzNzQyMzE4MzgwNSIM9IGqQ4pt8ftwRzCoKtwDe5HLEpMZcv0PulnSOnee78fcsHzH%2Bb2I8OjXq4HOhYuGoIwD4sXv2kxkm9vs5JPHiwlo%2BjP65CMB%2BTnuGdMfg7E2nBH%2BS9Kl3kn9YVXV7F3IgHeog31DL8xrSc1XL%2F3ZKe0oH4GTTGlt2CawxNT9kBR8gpCQrHxQE0qtStYFbFjuIGNZCMRAFUB2C1Kz0vthPRlNIwO5ynd4c6LqqqCMZ4jdP2uAqv2k2SW5YsFzO5HxEukupo0%2FpM0JiYJn0GLpprgtyFsPT48UfR8Quv2aD%2FH%2F1wHe4V0xAfXfiQP4sZVr5yUzgh4TNmSpCRutkhOLks4LeraxXKHISQAEjmm%2BrxOp%2B6J9tMwdFQoI21MP17y8BBbj092%2F3q8ysij0oNlhojJUwZkQz9T9wLr5%2FRAfrbGZ7vanP3AaFDlb%2FqZqdZCK0iWT%2BCXMbHn4mhZpL91MPIaB60uIwsbjJUJAIaLhDvs0MgW%2FmaF2wj87Gf3auJ69ThHbN0N2lH%2F5dcbKHuZ7h6AsCkf8SI15Pc3z4MQhpFJAyUTn0KjN4urE10GfFs%2F81%2FfBLgafNJ2nyhZEyWPJvuo1RaEfmw%2BrsUa6%2FFpIvEh10Gl3s0YochuIw7hxuHIgk9f3m%2Fpj3kmk6aIw4erOvQY6pgH7zqq3rxtlOo2Oo1OcgQh4TWfgD1FhU9Q724FHfvyzOaawDd%2Ft75fh%2F8Ep0cbQZCG8jYXqdNfOAjP94Ci1AYXyYjARC3sWHF0mDh%2B%2B8jG3cS5FXAcuOc0AEmAwWioG77ldIzqteDmkVa7bW1l19vnleIsECjZMEgeQFI9hfC29bWw%2FFJZzESP%2BKmawZMiErlDQl87ezhuT%2Fydqv1vAQM%2FCHp7Y%2FuV4&X-Amz-Signature=8184e16483627e2362037be96daffb06e29739fa47fccec2db97cf749c87a93f&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VWF5SS5T%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T222200Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFYaCXVzLXdlc3QtMiJGMEQCICEFjMXcW4EUrl9fXDkB%2BDTjv3mGaPw9RpQmlE%2BYTk%2FqAiA0t8LXu78TbEcMdgLWt7km2nhF3lhKGLAInnLLIAJiyyr%2FAwh%2FEAAaDDYzNzQyMzE4MzgwNSIMxD5lvNrwXU4JC8gVKtwDtP4%2BtXofajD5i%2Fbnr289opaTPeTklm7eBxxsfeicOEcbHoHQUcoZs2mrx2p2d55rIaqzcrVtIghyY4B6EqAQbJI8AYBqxxf2KSqqtUxxIld%2Fe32xiZcJCBJXApF56p6QSIb%2FLEXci6KmgB71HDwP1LaSGghYSc0NHevADEM499CMnaeHjqqyuHlXoUkddxKkvpj8CkP17riIMscue0PBQXtv9mjph8r%2FsWjoDb2RtTzKymYxa6CTDv3qiPbFTPAw2dU4QIFmLke5pYyr%2BYQ6eWpd6wKqk0DOtz0kkIdqdxC34h5XOoHLQY6yv6pu4hzmw8DlIQUe7XXocCv9VoU1IZPvy62wYpdiNfhydoR5ZM6zNK63umBSVz%2BnJS%2BYGzJMxW%2FOvkOPMjYqgsMYR2Fiz1xqw2KqjOSglxX9kS1XSSTdsCGHXhdaUtNCyEM3tRWkQgmKpDA0OaVW6ajMW%2B6a13P1koABvc%2FEaZos%2FCxuH3HXgTvhRS9cCjXiGO240FEEXklnnPGdK%2FXIY4NiNQSPIyleMH%2BaCYY4plqbeQ467w0u%2BHG5nrUTI9caGEMJajHt6Kr32VzwqTxF%2FJaBYk4kgSNjsAdwlqP6jYltQyorRq0JuhlwTyNuhs2JVh8w5erOvQY6pgGl5psG1B4VahMTNhFeRdhmi1TDkvb%2F1TR9L1TKeVx357UBWNw4V1x0pL%2BugRa23IqvgXoeE9qhaRS5Z%2BymNIRUx4BRUshs0PYRPBCo05s5ug%2BhKYdi%2FG1VkZ4SNwThysXehJVXjQKM1iA0QsOcqJvO%2BqxYfI24DFqUA7Iz3TTHFzDKuJpgS8GgD31LgurhR7ZhH87dlGWSkBZl0o%2BRTYfSecjLL92q&X-Amz-Signature=d7ad2b133bd411500b3d97c4db34627036093c0931431c4fa169eecf02c120bc&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466R4BWSF6H%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T222159Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFYaCXVzLXdlc3QtMiJIMEYCIQC5%2BJ8EtB8N%2FLDYoCcD%2FXZjEUugA9TtA6tOxrCrPFt9TwIhAKinnOhy%2BkJZmv4NywU3d%2F8xDv1LCeNrze6k383ROI%2FVKv8DCH8QABoMNjM3NDIzMTgzODA1Igy6bJghFMGKNV%2BDZDoq3AOtQnIP0%2BcfaCwkbdVt1Nwdovjsx3wDnD89N4HwJ764Giz2kHnjeSOoHO3%2BPrMn%2F84jOI6GXr4qVFW%2FnOca6uvKA4mDuLJNltedN4VC4NGoBUL6k2b2tqwsq%2BGh5ecYKuf3PrX9PZZa%2BE%2B66%2BepyKQAmnlIi6wnPYtrl3BKd9BLW6WWv6oeAUGLilL3gf%2BMIE1cc4nlu81B%2FEtURh4FHO%2F%2Be79g4QuEYdMsSMSlsT89OoX00XGv2Jej3LiXO4aU97Myr2EF%2FNFe5av8YbV8UYfcOY5W9r1vVjTem0zEAP0wlvcPEfl4fSks3oNBtJPPFY9NaZ3ilpYAemUeKJHIScfOxZPec5xlJZp5Iawznp7g7c07DRRp8oDm7aPDIX6g0bwGXIGnbL%2FTHXSmO%2BEW7NN5PfedmPOrvYHyy44VLTNWmiuyJ86Q%2BdL3qz37y%2BeArauAzCv9yIVx%2FnIGgZaisqYMUTf2TzBql3WcqE3DHVigRIpkHvECUZC79pBu7uYiF9WWQGA8FL9dNB6Ptn%2Bv8D1jXbY%2BroXPRuyjUx1RINNftOb6N7X4cNQr9KZG9eAYf%2FIldlowICts5s7GtSZLmYayLPYw6g0Iq5tLv%2Bs4KNBYHEGDIopDwXDdM%2B4%2F8DC%2F6s69BjqkAQ1eHf7w%2BlwJriNp14kqNjxDs6ZvCot03bD%2FXP0N5NZuMTTlv9QqbHmPCuonSR7jkqk1WV7Nwyiu7BzGWa6%2FPMFhewdSksYlt5k67XAsQKnP9YZFKoHmBqG05d5oXaZ1sPze4x%2B2m0XpBNq%2FGca3pvrRkucbbH4KTZGM1UKLPcHoli0q08o9dmiIi6x1smlwjTAmmgs9QX0GcpXTqwwfKi1GJd%2FR&X-Amz-Signature=2561635b4cee7264a8efa3be23e2f5761c9ff2a5016c6da74b7702c92adb32d0&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466R4BWSF6H%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T222158Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFYaCXVzLXdlc3QtMiJIMEYCIQC5%2BJ8EtB8N%2FLDYoCcD%2FXZjEUugA9TtA6tOxrCrPFt9TwIhAKinnOhy%2BkJZmv4NywU3d%2F8xDv1LCeNrze6k383ROI%2FVKv8DCH8QABoMNjM3NDIzMTgzODA1Igy6bJghFMGKNV%2BDZDoq3AOtQnIP0%2BcfaCwkbdVt1Nwdovjsx3wDnD89N4HwJ764Giz2kHnjeSOoHO3%2BPrMn%2F84jOI6GXr4qVFW%2FnOca6uvKA4mDuLJNltedN4VC4NGoBUL6k2b2tqwsq%2BGh5ecYKuf3PrX9PZZa%2BE%2B66%2BepyKQAmnlIi6wnPYtrl3BKd9BLW6WWv6oeAUGLilL3gf%2BMIE1cc4nlu81B%2FEtURh4FHO%2F%2Be79g4QuEYdMsSMSlsT89OoX00XGv2Jej3LiXO4aU97Myr2EF%2FNFe5av8YbV8UYfcOY5W9r1vVjTem0zEAP0wlvcPEfl4fSks3oNBtJPPFY9NaZ3ilpYAemUeKJHIScfOxZPec5xlJZp5Iawznp7g7c07DRRp8oDm7aPDIX6g0bwGXIGnbL%2FTHXSmO%2BEW7NN5PfedmPOrvYHyy44VLTNWmiuyJ86Q%2BdL3qz37y%2BeArauAzCv9yIVx%2FnIGgZaisqYMUTf2TzBql3WcqE3DHVigRIpkHvECUZC79pBu7uYiF9WWQGA8FL9dNB6Ptn%2Bv8D1jXbY%2BroXPRuyjUx1RINNftOb6N7X4cNQr9KZG9eAYf%2FIldlowICts5s7GtSZLmYayLPYw6g0Iq5tLv%2Bs4KNBYHEGDIopDwXDdM%2B4%2F8DC%2F6s69BjqkAQ1eHf7w%2BlwJriNp14kqNjxDs6ZvCot03bD%2FXP0N5NZuMTTlv9QqbHmPCuonSR7jkqk1WV7Nwyiu7BzGWa6%2FPMFhewdSksYlt5k67XAsQKnP9YZFKoHmBqG05d5oXaZ1sPze4x%2B2m0XpBNq%2FGca3pvrRkucbbH4KTZGM1UKLPcHoli0q08o9dmiIi6x1smlwjTAmmgs9QX0GcpXTqwwfKi1GJd%2FR&X-Amz-Signature=2e3881c42fb643930ca68572ddac845928a42fe8dfbd065e5a8bf2e09aebc930&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466R4BWSF6H%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T222159Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFYaCXVzLXdlc3QtMiJIMEYCIQC5%2BJ8EtB8N%2FLDYoCcD%2FXZjEUugA9TtA6tOxrCrPFt9TwIhAKinnOhy%2BkJZmv4NywU3d%2F8xDv1LCeNrze6k383ROI%2FVKv8DCH8QABoMNjM3NDIzMTgzODA1Igy6bJghFMGKNV%2BDZDoq3AOtQnIP0%2BcfaCwkbdVt1Nwdovjsx3wDnD89N4HwJ764Giz2kHnjeSOoHO3%2BPrMn%2F84jOI6GXr4qVFW%2FnOca6uvKA4mDuLJNltedN4VC4NGoBUL6k2b2tqwsq%2BGh5ecYKuf3PrX9PZZa%2BE%2B66%2BepyKQAmnlIi6wnPYtrl3BKd9BLW6WWv6oeAUGLilL3gf%2BMIE1cc4nlu81B%2FEtURh4FHO%2F%2Be79g4QuEYdMsSMSlsT89OoX00XGv2Jej3LiXO4aU97Myr2EF%2FNFe5av8YbV8UYfcOY5W9r1vVjTem0zEAP0wlvcPEfl4fSks3oNBtJPPFY9NaZ3ilpYAemUeKJHIScfOxZPec5xlJZp5Iawznp7g7c07DRRp8oDm7aPDIX6g0bwGXIGnbL%2FTHXSmO%2BEW7NN5PfedmPOrvYHyy44VLTNWmiuyJ86Q%2BdL3qz37y%2BeArauAzCv9yIVx%2FnIGgZaisqYMUTf2TzBql3WcqE3DHVigRIpkHvECUZC79pBu7uYiF9WWQGA8FL9dNB6Ptn%2Bv8D1jXbY%2BroXPRuyjUx1RINNftOb6N7X4cNQr9KZG9eAYf%2FIldlowICts5s7GtSZLmYayLPYw6g0Iq5tLv%2Bs4KNBYHEGDIopDwXDdM%2B4%2F8DC%2F6s69BjqkAQ1eHf7w%2BlwJriNp14kqNjxDs6ZvCot03bD%2FXP0N5NZuMTTlv9QqbHmPCuonSR7jkqk1WV7Nwyiu7BzGWa6%2FPMFhewdSksYlt5k67XAsQKnP9YZFKoHmBqG05d5oXaZ1sPze4x%2B2m0XpBNq%2FGca3pvrRkucbbH4KTZGM1UKLPcHoli0q08o9dmiIi6x1smlwjTAmmgs9QX0GcpXTqwwfKi1GJd%2FR&X-Amz-Signature=74b9537864220618a23f087b987261f0b5e8301a1d14a21dd8d036ac89b90720&X-Amz-SignedHeaders=host&x-id=GetObject)


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

