---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466ZTLNIOHW%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250214T212147Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEA0aCXVzLXdlc3QtMiJHMEUCIQDDwCzyOzVud8pTlIurtUVMoZdM6Xg9YWO4dFQEKiB1uwIgGlN\
  Aq1rpODSIzbzemx1prrDtMk0K2mYx4iNEb5GtwkMq%2FwMINhAAGgw2Mzc0MjMxODM4MDUiDFNgU4\
  fYiE%2FCZYLIkCrcA5r%2BIBQE4Tx4SUZYKFdOcDwN09Myix8M3TisphAGPra7ZMv2h9J9btwLrgT\
  akWHv0mdmsZaPOR4ugM4wvArZ7ZSazp38449WrX1sSGmCW3J8CPPpvazEuYSNZR1DRAyv6h1EYox%\
  2F9KXH3SdoNCGAt5Y2iJJzSjKj49HDwwz4P72I%2BsshxSmwV5wsXl333xVGAXWXTlFw6nUVPlHUO\
  %2Fh%2FKy%2BTgKzUPJxYg%2F9AyOJYhFq0xwBrGavn2kEZNPntcewyO5M%2BT%2FE0hPJ43jx3rh\
  bDhKUi9TVujv6g4%2F%2FI8Da66%2BKHxng6MzRbLwuAA%2B1Q1rnUTweBL9h9nVgcxtux%2B0o8u\
  eLp4ZjKgP1f2Irc6MBlvGEdIquVB6DER8On6o%2BZfKfe71U12UwrIV%2BWLoloabXd7PlhIKdYTT\
  VGPrLTAW%2Ff5aUXN0PEYxQqwcrJXkm2%2FFHniKOPJ4%2FFedFw6ivp24TDR8%2FKCzycN1K2MZg\
  rGesViTW6xmshCvPeESvP6x7VUltB3AJpdjMG6dGUbBuJAbqMXBVg4OL84Dn6Dwpnk2ff00fWNNIt\
  jqh5KWLEOKouC6UxYx5f6Yb1chQPoB2tCIRfTW6Z3dAnyEbrb6uC%2BKg4d0Y6%2F0IxDQepn9Eai\
  1xrMI3Svr0GOqUB7JmiNDAZ35oNXIYNG%2BtPzkoLfN%2FCKPFts1cHi2DGe2hG%2BzjG5LxHb3P2\
  3d2%2BYoocms0Bxi%2FTO6mIm3571QeLaW1waGRyd9hQrmdlSN8ByEjR2sxslQg%2FSYOo%2B30NT\
  xNcsgtKX7epCAnEvUbNDuCbh8ACi2KstuEhTT890dzoLuJjm8lLUGmbzJEIddsE2qO8apy2dib%2F\
  3o3coS870FtUO9XZPh0M&X-Amz-Signature=d387eaad65b80406aad5deb19330c62f0ee3dfdd\
  25344b29576c1a1bccf9a296&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466Q5H6HLEL%2F20250214%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250214T212011Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEA0aCXVzLXdlc3QtMiJHMEUCIFXCVUqfK7GBhxFHB6hb1eld3uXYWRV\
        9JD4dcpdubgVzAiEAoA0lC7tbgZedwhqWDA%2FxrmGVpGioxRz%2FB%2FMRltOjCpwq%2Fw\
        MINhAAGgw2Mzc0MjMxODM4MDUiDO7NXHoP9SYil9VUHCrcA%2BSA45YzLJ9w5NWkDuHmDZu\
        S51wf7xFgkKl8WUMAYSARi3FW6KHNhxfZSm9G4X4M4eC5HN9pynb%2BCrV0UPDYuAeYSrAQ\
        3EciEfBBoVZG7o1Y9Ey5foqgTs6xplDK%2B9DCa%2BsTY4ppjPc%2BO4ErGqQ82epZePPpp\
        BRioEgKCYq8HfrIUIRmZpPi8ioUZquhnqtvHLZhhzCtA%2BSBbLsZ7zW%2BI1Cu9pXsKRWc\
        OrB%2BIyyitL7u2Jn4WpjKivgujRoYc3%2FIklZqeeUFNic%2BeA4DxyQjL%2BeAa3CiRqi\
        sHCi2RmpU%2BhVwI%2BWXbGhJ00Q05bm3mcmcoPSdezCGSZTwQcBVUsag0q%2BOLm9lVdes\
        gmINvjDkassT2ZMGOZz5ErEl0WQ%2BGDvgl0g7OrwixGduzN3qLVQwQjBlQae9WGbozinaj\
        rAVb0inyCo5JSaiB1zTtwVWjW2axdSUQvyAInwM6QwEAzb8iQ8vodcCkA5BaBaZtuvINxuw\
        gw3mhZvG3CbG64pKuJcZPwCELOQBKNpn3FNKgpd2FTj8zkuD%2BoBsXu3s%2BHfvcPZQSv8\
        ndA9oBkLK5v1%2FY1OrTZWtlSMfearozEIWnAVekHTglFKw0mg3UUC5comkGMHLiKa9MVau\
        euni4v31MObRvr0GOqUBJeEZUcLTgzaAk4BcfJHlPBzlxlTSxOYa96kqmLCNwc0j91lJSab\
        %2FPvbg%2B5uxztf3pk8EoodkMSq6ftpwiweNFx%2FfJVxPuzghdkUKUVxRkunP%2BItqhG\
        28EVu%2BCFwmSdbQ59V12GCNDcUuxMLZ5vF4yOMMFIS54NxN7jRXdz4YGjdrhZChxZ44JbP\
        iFPotoJyyqrklG2vlicIGcMXXy%2BhaY%2FQTzXCY&X-Amz-Signature=be0c1eabb21a0\
        a45ab1a825696037aeff69b5113cee879519690d88e395a68a9&X-Amz-SignedHeaders\
        =host&x-id=GetObject"
      expiry_time: "2025-02-14T22:20:11.102Z"
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
UPDATE_TIME: "2025-02-14T21:21:52.412Z"
EXPIRY_TIME: "2025-02-14T22:21:43.292Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662X46UH37%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T212143Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEA0aCXVzLXdlc3QtMiJHMEUCIQDFTY%2FX8HR7NLM7VB%2FIcDS95jZtO1JVKIZpd9Ne1cEImAIgJVTOLT6Qq04ijrHW6WFM0gLgNRUMKYfov09i1y20z6kq%2FwMINhAAGgw2Mzc0MjMxODM4MDUiDJvKRVIyG0YrMDYQLSrcA%2Bg6vwoFtf3LV9DdVSeKhpJNopr%2BaoGMROm1d%2F7ipTjWPLodCVCopkKoe4KA6sGXRW1V494qYP2CPcol%2FlYYZK7WELLlaZWf5wI22d%2Bz6I4E4Q75a5B0aEM5gGr5TLgosPO%2BiqtUgW8GNO3YInZPhiQrOn%2BuhF5MWoH0dVZzTR76efwuDORdcbemsMqMZLmSjHMSv4758cyWWF7ecG7Fg%2BJNNXLGKB41BOmxEa%2BqUgBhXVevkSiCawnygQ97wdDW7TcmVAY6%2B5nzrU1jlKlQahHQu63gc%2BDHMfgtx2shebylRrs%2B9y8lUHS22Fr2ZezWsmniXFODz3%2BkAj0s4J5XDdGknyxFw1V%2FDxT1KY3Oc%2FPxcYqOqgLh9Lm7t2qYs04w7qY2PLltLAoOH9vLCw%2F58Lp4xUU%2BveBYor9OtkQ3dt72J2ToNHki5f1ACjl%2BfNEv%2BobmbAe73j4O3yw3ZMvOElRf0YuJX95jmesmCBs1sRWr7q2UY3QKy1pA9smc1RhTWgiCWi9xrKc77LvCu9f4LVmHfZHcE0%2FSEH2RhwEkYeWyX8xx9BBO94T7Hb0bYIGpRwPWXAm0OJEgoY59Ztkhh9T%2Fyos9dOEsJUl2pcJL34ZM6Ip7HpBCyQ3R3vxGMITSvr0GOqUB3T2FlRW%2BDbKYtYR5Zra6QPkJeHxJJy51BI2rkhoHZ%2FSaOY3cJTb1bxFiom71QuZJBHp9EmEhcwTp0YgyvoBKjl5Q1m89Mhqfw9aMO489MLqp2k81xD%2BXnGb%2B1LrWger%2FsHhwJCu63I1DR%2BbLs1ZiL9sBjJdbBEVBGUjI1XyfITwI8x6ICUfVYyoVyiEcKcYQW92eCJsdocwciqucF37K80cgk288&X-Amz-Signature=fd842792036d439ca664b154b3a3809347661b6714bf6a0a653be284ad0352db&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662X46UH37%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T212143Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEA0aCXVzLXdlc3QtMiJHMEUCIQDFTY%2FX8HR7NLM7VB%2FIcDS95jZtO1JVKIZpd9Ne1cEImAIgJVTOLT6Qq04ijrHW6WFM0gLgNRUMKYfov09i1y20z6kq%2FwMINhAAGgw2Mzc0MjMxODM4MDUiDJvKRVIyG0YrMDYQLSrcA%2Bg6vwoFtf3LV9DdVSeKhpJNopr%2BaoGMROm1d%2F7ipTjWPLodCVCopkKoe4KA6sGXRW1V494qYP2CPcol%2FlYYZK7WELLlaZWf5wI22d%2Bz6I4E4Q75a5B0aEM5gGr5TLgosPO%2BiqtUgW8GNO3YInZPhiQrOn%2BuhF5MWoH0dVZzTR76efwuDORdcbemsMqMZLmSjHMSv4758cyWWF7ecG7Fg%2BJNNXLGKB41BOmxEa%2BqUgBhXVevkSiCawnygQ97wdDW7TcmVAY6%2B5nzrU1jlKlQahHQu63gc%2BDHMfgtx2shebylRrs%2B9y8lUHS22Fr2ZezWsmniXFODz3%2BkAj0s4J5XDdGknyxFw1V%2FDxT1KY3Oc%2FPxcYqOqgLh9Lm7t2qYs04w7qY2PLltLAoOH9vLCw%2F58Lp4xUU%2BveBYor9OtkQ3dt72J2ToNHki5f1ACjl%2BfNEv%2BobmbAe73j4O3yw3ZMvOElRf0YuJX95jmesmCBs1sRWr7q2UY3QKy1pA9smc1RhTWgiCWi9xrKc77LvCu9f4LVmHfZHcE0%2FSEH2RhwEkYeWyX8xx9BBO94T7Hb0bYIGpRwPWXAm0OJEgoY59Ztkhh9T%2Fyos9dOEsJUl2pcJL34ZM6Ip7HpBCyQ3R3vxGMITSvr0GOqUB3T2FlRW%2BDbKYtYR5Zra6QPkJeHxJJy51BI2rkhoHZ%2FSaOY3cJTb1bxFiom71QuZJBHp9EmEhcwTp0YgyvoBKjl5Q1m89Mhqfw9aMO489MLqp2k81xD%2BXnGb%2B1LrWger%2FsHhwJCu63I1DR%2BbLs1ZiL9sBjJdbBEVBGUjI1XyfITwI8x6ICUfVYyoVyiEcKcYQW92eCJsdocwciqucF37K80cgk288&X-Amz-Signature=f223ca3c5996696779ee44750720e696dc79c4e2d20ae82a0f05f58832b1bd2e&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662X46UH37%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T212143Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEA0aCXVzLXdlc3QtMiJHMEUCIQDFTY%2FX8HR7NLM7VB%2FIcDS95jZtO1JVKIZpd9Ne1cEImAIgJVTOLT6Qq04ijrHW6WFM0gLgNRUMKYfov09i1y20z6kq%2FwMINhAAGgw2Mzc0MjMxODM4MDUiDJvKRVIyG0YrMDYQLSrcA%2Bg6vwoFtf3LV9DdVSeKhpJNopr%2BaoGMROm1d%2F7ipTjWPLodCVCopkKoe4KA6sGXRW1V494qYP2CPcol%2FlYYZK7WELLlaZWf5wI22d%2Bz6I4E4Q75a5B0aEM5gGr5TLgosPO%2BiqtUgW8GNO3YInZPhiQrOn%2BuhF5MWoH0dVZzTR76efwuDORdcbemsMqMZLmSjHMSv4758cyWWF7ecG7Fg%2BJNNXLGKB41BOmxEa%2BqUgBhXVevkSiCawnygQ97wdDW7TcmVAY6%2B5nzrU1jlKlQahHQu63gc%2BDHMfgtx2shebylRrs%2B9y8lUHS22Fr2ZezWsmniXFODz3%2BkAj0s4J5XDdGknyxFw1V%2FDxT1KY3Oc%2FPxcYqOqgLh9Lm7t2qYs04w7qY2PLltLAoOH9vLCw%2F58Lp4xUU%2BveBYor9OtkQ3dt72J2ToNHki5f1ACjl%2BfNEv%2BobmbAe73j4O3yw3ZMvOElRf0YuJX95jmesmCBs1sRWr7q2UY3QKy1pA9smc1RhTWgiCWi9xrKc77LvCu9f4LVmHfZHcE0%2FSEH2RhwEkYeWyX8xx9BBO94T7Hb0bYIGpRwPWXAm0OJEgoY59Ztkhh9T%2Fyos9dOEsJUl2pcJL34ZM6Ip7HpBCyQ3R3vxGMITSvr0GOqUB3T2FlRW%2BDbKYtYR5Zra6QPkJeHxJJy51BI2rkhoHZ%2FSaOY3cJTb1bxFiom71QuZJBHp9EmEhcwTp0YgyvoBKjl5Q1m89Mhqfw9aMO489MLqp2k81xD%2BXnGb%2B1LrWger%2FsHhwJCu63I1DR%2BbLs1ZiL9sBjJdbBEVBGUjI1XyfITwI8x6ICUfVYyoVyiEcKcYQW92eCJsdocwciqucF37K80cgk288&X-Amz-Signature=473cf21bb1d88506faf60bdee4c8078faebefb407f42ac4a8fd2e22361ece138&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662X46UH37%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T212143Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEA0aCXVzLXdlc3QtMiJHMEUCIQDFTY%2FX8HR7NLM7VB%2FIcDS95jZtO1JVKIZpd9Ne1cEImAIgJVTOLT6Qq04ijrHW6WFM0gLgNRUMKYfov09i1y20z6kq%2FwMINhAAGgw2Mzc0MjMxODM4MDUiDJvKRVIyG0YrMDYQLSrcA%2Bg6vwoFtf3LV9DdVSeKhpJNopr%2BaoGMROm1d%2F7ipTjWPLodCVCopkKoe4KA6sGXRW1V494qYP2CPcol%2FlYYZK7WELLlaZWf5wI22d%2Bz6I4E4Q75a5B0aEM5gGr5TLgosPO%2BiqtUgW8GNO3YInZPhiQrOn%2BuhF5MWoH0dVZzTR76efwuDORdcbemsMqMZLmSjHMSv4758cyWWF7ecG7Fg%2BJNNXLGKB41BOmxEa%2BqUgBhXVevkSiCawnygQ97wdDW7TcmVAY6%2B5nzrU1jlKlQahHQu63gc%2BDHMfgtx2shebylRrs%2B9y8lUHS22Fr2ZezWsmniXFODz3%2BkAj0s4J5XDdGknyxFw1V%2FDxT1KY3Oc%2FPxcYqOqgLh9Lm7t2qYs04w7qY2PLltLAoOH9vLCw%2F58Lp4xUU%2BveBYor9OtkQ3dt72J2ToNHki5f1ACjl%2BfNEv%2BobmbAe73j4O3yw3ZMvOElRf0YuJX95jmesmCBs1sRWr7q2UY3QKy1pA9smc1RhTWgiCWi9xrKc77LvCu9f4LVmHfZHcE0%2FSEH2RhwEkYeWyX8xx9BBO94T7Hb0bYIGpRwPWXAm0OJEgoY59Ztkhh9T%2Fyos9dOEsJUl2pcJL34ZM6Ip7HpBCyQ3R3vxGMITSvr0GOqUB3T2FlRW%2BDbKYtYR5Zra6QPkJeHxJJy51BI2rkhoHZ%2FSaOY3cJTb1bxFiom71QuZJBHp9EmEhcwTp0YgyvoBKjl5Q1m89Mhqfw9aMO489MLqp2k81xD%2BXnGb%2B1LrWger%2FsHhwJCu63I1DR%2BbLs1ZiL9sBjJdbBEVBGUjI1XyfITwI8x6ICUfVYyoVyiEcKcYQW92eCJsdocwciqucF37K80cgk288&X-Amz-Signature=d8a2e5384ea6105d9168a175ae62e6f5c4e8a14b5b978f2f7f3285c34a693b34&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662X46UH37%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T212143Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEA0aCXVzLXdlc3QtMiJHMEUCIQDFTY%2FX8HR7NLM7VB%2FIcDS95jZtO1JVKIZpd9Ne1cEImAIgJVTOLT6Qq04ijrHW6WFM0gLgNRUMKYfov09i1y20z6kq%2FwMINhAAGgw2Mzc0MjMxODM4MDUiDJvKRVIyG0YrMDYQLSrcA%2Bg6vwoFtf3LV9DdVSeKhpJNopr%2BaoGMROm1d%2F7ipTjWPLodCVCopkKoe4KA6sGXRW1V494qYP2CPcol%2FlYYZK7WELLlaZWf5wI22d%2Bz6I4E4Q75a5B0aEM5gGr5TLgosPO%2BiqtUgW8GNO3YInZPhiQrOn%2BuhF5MWoH0dVZzTR76efwuDORdcbemsMqMZLmSjHMSv4758cyWWF7ecG7Fg%2BJNNXLGKB41BOmxEa%2BqUgBhXVevkSiCawnygQ97wdDW7TcmVAY6%2B5nzrU1jlKlQahHQu63gc%2BDHMfgtx2shebylRrs%2B9y8lUHS22Fr2ZezWsmniXFODz3%2BkAj0s4J5XDdGknyxFw1V%2FDxT1KY3Oc%2FPxcYqOqgLh9Lm7t2qYs04w7qY2PLltLAoOH9vLCw%2F58Lp4xUU%2BveBYor9OtkQ3dt72J2ToNHki5f1ACjl%2BfNEv%2BobmbAe73j4O3yw3ZMvOElRf0YuJX95jmesmCBs1sRWr7q2UY3QKy1pA9smc1RhTWgiCWi9xrKc77LvCu9f4LVmHfZHcE0%2FSEH2RhwEkYeWyX8xx9BBO94T7Hb0bYIGpRwPWXAm0OJEgoY59Ztkhh9T%2Fyos9dOEsJUl2pcJL34ZM6Ip7HpBCyQ3R3vxGMITSvr0GOqUB3T2FlRW%2BDbKYtYR5Zra6QPkJeHxJJy51BI2rkhoHZ%2FSaOY3cJTb1bxFiom71QuZJBHp9EmEhcwTp0YgyvoBKjl5Q1m89Mhqfw9aMO489MLqp2k81xD%2BXnGb%2B1LrWger%2FsHhwJCu63I1DR%2BbLs1ZiL9sBjJdbBEVBGUjI1XyfITwI8x6ICUfVYyoVyiEcKcYQW92eCJsdocwciqucF37K80cgk288&X-Amz-Signature=3b551039efb24356c44a1f1383cd3fd326e699dcd163c85bc94bbfcdcab09926&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667XODL3QV%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T212144Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEA0aCXVzLXdlc3QtMiJHMEUCIQCFy%2FnDvide3ZzUbAnew6MhK%2BH%2BJMzjT4Jzp3QZT1gDjAIgds2QaVk9Tr%2Fijqs8K21LJ0K%2BT5dvaeAw1scH%2FwD2%2BQMq%2FwMINhAAGgw2Mzc0MjMxODM4MDUiDIYIJdJb9OTHLmPgKircAzfbzc%2BSqIHzISpj%2Bc7NdRoGINEU5j23WqDsMIUKLHUFI53wCRYPuA9hbCtoK3Nn6w3mq01lO35K9YdfaY4JfRn9NuO%2FSHB6km1UempQj29VNKX7WYdv2ZLQlsUmLQ5obkbBJaYEdYsUQln3ycccrIHGZIYmpCBzLx1Mu38eTMroxNaUdgR6MPPRmI2F5%2BkS3dH0Azp8hQ6gJccVQ7IMgZE4ZxSSZbVSCdCyWnoPFoJWHFCa1Ziqb062x%2FDxJynGDKmGdW67mjmbhVJ0iYkM3TXL9m5rqVE4%2BOppdciGk7Sc%2BKEfsxFxvGGC2n0RCpO1HYBoV4EvRitvP%2BwLAS%2Bm5r1KIRuqmPvhxVvkT79av6uc7W79d49y3DspTvPpCc5MBwQIPzAvR0ZYw9TPcuFwedQUKZiqALUHeUDJZrx8OBGrbDnM21ZjKEI%2BvNHp0N1yLWqbYk%2BzbmAyrfxvZaat1TijjhzLEofPCeNwtrl%2FR18hb2WQcQX6STwuNXfuE6fOzTUmqQjM4MUR2ARieHzWUkJhQpHYKizfIAkv9m14m%2BV01ms0W8WABadV2TBUUK61N%2BK%2BSE4WuzWNIZX5D%2BV9zOhLKQdzAgrAUX3JG8EFMR%2F0uhTWOscq9IqpbsjrMM3Rvr0GOqUBWaCSlJidTLkAV1N6cF9X0HHpIyQHNgEyCj0h8Ko7phboOO7gHBPiY9wnxfJ6gXwbiVKdFT0Rc4hnas7u6hz9cV5EfUDJu7h6WpWS6PIGgsHaSv%2FJOfYIkI99J%2FWnuckrAVmMNhGl2%2B5j18whiv0AFeNvqix8IjzfOaWjlYYZttrAd9LPkzHHfApuxV3Ghj55LRykcAy8YgOKx%2B0r%2BEklxC1ydcRi&X-Amz-Signature=5cbf6a2e5053e1b0193948c8c5211a9be42f5e3ea8fbea30b0f834fc11076b7a&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466R3F5OC2T%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T212147Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEA0aCXVzLXdlc3QtMiJGMEQCIHHzxwDuZNodDbpUjJ15aQzOjdhxFwShpcGgoRAYn0PNAiBBvDwjZ9wT1X1J9%2B%2FU49dCiFeyGSK152ubvvwbQNfqDSr%2FAwg2EAAaDDYzNzQyMzE4MzgwNSIMpWarUCQHi0UjnK2QKtwD277wSwwo2eO1jlgm3LReqPYhWMRjj4hNLJ6RvMh9JOXN7TLgUQKFHCxX%2FYYXLkWO1lWefVmz99fZmZGVkvgP711XII54hZRDJxpxRZx7uc66TZhN56%2B27suBk5VbU2C1dhs771nogbOFSSNs0DCYjHEUJBwIECurVy7NjQUclYGSuCWuiQnDoEEx6jbbcCKu%2F9bTeDTHdxL6qc9QuQcxaStx9N0M04BN%2B%2FidLxN%2FFVNdLlv%2F0DkZismzM6cKu7yNH5F%2BZL0YCKd1p0vhcD5cjY5bnoRFp8P1dEKk8PAQLCboCvtCeyDxxLvTKGD%2BPMWTJYQ6k7hkJEH5fbciHTf0XXQEG76n2m3B3CLSSsS%2Ft9XN03oYVF%2Fjr%2FTMEHMP18ixFz5bKRWVRAAV%2Bs6goyVwhcaG9QQy%2BwwgQYH32H1ib3OIhK25qc5dzioNN1Cp%2BObISqDvU12e2N7hLBi4grfMsJlOqMyy3wgMkPH4nu0l7Djx0%2FdImhS3%2B1hoEuxaANyXkS2OFVKHNe5FVv6f5jtyeDghD%2Bj64nTRkfloHLbcmAX%2FcwTR5InOofP1ApHz%2FaMaeoK%2BElzcMtXUx%2F%2B624sKrfG6zwpXOdi84G472RQthTRSzHtTfVEZODBE%2BikwwtG%2BvQY6pgFdsFs9THY7PaCx1gF8Mz1kOtiPdu2Mk8vskaAd1pKdrs4lMVYRp6i6nle8xDYgR8kQU8NNRK%2BJ9lLfc7wm%2F8sT9EdQJzjbCnB7dr6OCYrZicpS5W5HlgB%2F4y03SafBP7JogJMCnmg5YuFS9oRrouM3q4n927YNQ0Ms1w9EHHkocVmjXwm1LTiVilBsUZaRi%2FOabbRWlwoG%2B8sfzYi6Eyhd5nbq%2Bmgq&X-Amz-Signature=dbe2423c633a9fc4ec0809a49218c70a924f795dbf00d1dc12ae23b5556f03ad&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662X46UH37%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T212143Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEA0aCXVzLXdlc3QtMiJHMEUCIQDFTY%2FX8HR7NLM7VB%2FIcDS95jZtO1JVKIZpd9Ne1cEImAIgJVTOLT6Qq04ijrHW6WFM0gLgNRUMKYfov09i1y20z6kq%2FwMINhAAGgw2Mzc0MjMxODM4MDUiDJvKRVIyG0YrMDYQLSrcA%2Bg6vwoFtf3LV9DdVSeKhpJNopr%2BaoGMROm1d%2F7ipTjWPLodCVCopkKoe4KA6sGXRW1V494qYP2CPcol%2FlYYZK7WELLlaZWf5wI22d%2Bz6I4E4Q75a5B0aEM5gGr5TLgosPO%2BiqtUgW8GNO3YInZPhiQrOn%2BuhF5MWoH0dVZzTR76efwuDORdcbemsMqMZLmSjHMSv4758cyWWF7ecG7Fg%2BJNNXLGKB41BOmxEa%2BqUgBhXVevkSiCawnygQ97wdDW7TcmVAY6%2B5nzrU1jlKlQahHQu63gc%2BDHMfgtx2shebylRrs%2B9y8lUHS22Fr2ZezWsmniXFODz3%2BkAj0s4J5XDdGknyxFw1V%2FDxT1KY3Oc%2FPxcYqOqgLh9Lm7t2qYs04w7qY2PLltLAoOH9vLCw%2F58Lp4xUU%2BveBYor9OtkQ3dt72J2ToNHki5f1ACjl%2BfNEv%2BobmbAe73j4O3yw3ZMvOElRf0YuJX95jmesmCBs1sRWr7q2UY3QKy1pA9smc1RhTWgiCWi9xrKc77LvCu9f4LVmHfZHcE0%2FSEH2RhwEkYeWyX8xx9BBO94T7Hb0bYIGpRwPWXAm0OJEgoY59Ztkhh9T%2Fyos9dOEsJUl2pcJL34ZM6Ip7HpBCyQ3R3vxGMITSvr0GOqUB3T2FlRW%2BDbKYtYR5Zra6QPkJeHxJJy51BI2rkhoHZ%2FSaOY3cJTb1bxFiom71QuZJBHp9EmEhcwTp0YgyvoBKjl5Q1m89Mhqfw9aMO489MLqp2k81xD%2BXnGb%2B1LrWger%2FsHhwJCu63I1DR%2BbLs1ZiL9sBjJdbBEVBGUjI1XyfITwI8x6ICUfVYyoVyiEcKcYQW92eCJsdocwciqucF37K80cgk288&X-Amz-Signature=605ab2531561525d492087e0a2537b8bae7c180bbd3c94b00113f86656d7ea21&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662X46UH37%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T212144Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEA0aCXVzLXdlc3QtMiJHMEUCIQDFTY%2FX8HR7NLM7VB%2FIcDS95jZtO1JVKIZpd9Ne1cEImAIgJVTOLT6Qq04ijrHW6WFM0gLgNRUMKYfov09i1y20z6kq%2FwMINhAAGgw2Mzc0MjMxODM4MDUiDJvKRVIyG0YrMDYQLSrcA%2Bg6vwoFtf3LV9DdVSeKhpJNopr%2BaoGMROm1d%2F7ipTjWPLodCVCopkKoe4KA6sGXRW1V494qYP2CPcol%2FlYYZK7WELLlaZWf5wI22d%2Bz6I4E4Q75a5B0aEM5gGr5TLgosPO%2BiqtUgW8GNO3YInZPhiQrOn%2BuhF5MWoH0dVZzTR76efwuDORdcbemsMqMZLmSjHMSv4758cyWWF7ecG7Fg%2BJNNXLGKB41BOmxEa%2BqUgBhXVevkSiCawnygQ97wdDW7TcmVAY6%2B5nzrU1jlKlQahHQu63gc%2BDHMfgtx2shebylRrs%2B9y8lUHS22Fr2ZezWsmniXFODz3%2BkAj0s4J5XDdGknyxFw1V%2FDxT1KY3Oc%2FPxcYqOqgLh9Lm7t2qYs04w7qY2PLltLAoOH9vLCw%2F58Lp4xUU%2BveBYor9OtkQ3dt72J2ToNHki5f1ACjl%2BfNEv%2BobmbAe73j4O3yw3ZMvOElRf0YuJX95jmesmCBs1sRWr7q2UY3QKy1pA9smc1RhTWgiCWi9xrKc77LvCu9f4LVmHfZHcE0%2FSEH2RhwEkYeWyX8xx9BBO94T7Hb0bYIGpRwPWXAm0OJEgoY59Ztkhh9T%2Fyos9dOEsJUl2pcJL34ZM6Ip7HpBCyQ3R3vxGMITSvr0GOqUB3T2FlRW%2BDbKYtYR5Zra6QPkJeHxJJy51BI2rkhoHZ%2FSaOY3cJTb1bxFiom71QuZJBHp9EmEhcwTp0YgyvoBKjl5Q1m89Mhqfw9aMO489MLqp2k81xD%2BXnGb%2B1LrWger%2FsHhwJCu63I1DR%2BbLs1ZiL9sBjJdbBEVBGUjI1XyfITwI8x6ICUfVYyoVyiEcKcYQW92eCJsdocwciqucF37K80cgk288&X-Amz-Signature=1b1996887babfac489f1164df52131ab213972982766c3ec8e4a6005407f6d2d&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662X46UH37%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T212144Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEA0aCXVzLXdlc3QtMiJHMEUCIQDFTY%2FX8HR7NLM7VB%2FIcDS95jZtO1JVKIZpd9Ne1cEImAIgJVTOLT6Qq04ijrHW6WFM0gLgNRUMKYfov09i1y20z6kq%2FwMINhAAGgw2Mzc0MjMxODM4MDUiDJvKRVIyG0YrMDYQLSrcA%2Bg6vwoFtf3LV9DdVSeKhpJNopr%2BaoGMROm1d%2F7ipTjWPLodCVCopkKoe4KA6sGXRW1V494qYP2CPcol%2FlYYZK7WELLlaZWf5wI22d%2Bz6I4E4Q75a5B0aEM5gGr5TLgosPO%2BiqtUgW8GNO3YInZPhiQrOn%2BuhF5MWoH0dVZzTR76efwuDORdcbemsMqMZLmSjHMSv4758cyWWF7ecG7Fg%2BJNNXLGKB41BOmxEa%2BqUgBhXVevkSiCawnygQ97wdDW7TcmVAY6%2B5nzrU1jlKlQahHQu63gc%2BDHMfgtx2shebylRrs%2B9y8lUHS22Fr2ZezWsmniXFODz3%2BkAj0s4J5XDdGknyxFw1V%2FDxT1KY3Oc%2FPxcYqOqgLh9Lm7t2qYs04w7qY2PLltLAoOH9vLCw%2F58Lp4xUU%2BveBYor9OtkQ3dt72J2ToNHki5f1ACjl%2BfNEv%2BobmbAe73j4O3yw3ZMvOElRf0YuJX95jmesmCBs1sRWr7q2UY3QKy1pA9smc1RhTWgiCWi9xrKc77LvCu9f4LVmHfZHcE0%2FSEH2RhwEkYeWyX8xx9BBO94T7Hb0bYIGpRwPWXAm0OJEgoY59Ztkhh9T%2Fyos9dOEsJUl2pcJL34ZM6Ip7HpBCyQ3R3vxGMITSvr0GOqUB3T2FlRW%2BDbKYtYR5Zra6QPkJeHxJJy51BI2rkhoHZ%2FSaOY3cJTb1bxFiom71QuZJBHp9EmEhcwTp0YgyvoBKjl5Q1m89Mhqfw9aMO489MLqp2k81xD%2BXnGb%2B1LrWger%2FsHhwJCu63I1DR%2BbLs1ZiL9sBjJdbBEVBGUjI1XyfITwI8x6ICUfVYyoVyiEcKcYQW92eCJsdocwciqucF37K80cgk288&X-Amz-Signature=6ef90e35735d3a5e6e71f5da9ce93d28f672418809b7ef4fac366407320ec38c&X-Amz-SignedHeaders=host&x-id=GetObject)


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

