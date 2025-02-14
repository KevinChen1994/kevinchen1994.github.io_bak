---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466V4REOXG5%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250214T052308Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIGixKG3m95XnVwtHQ61\
  pBeDM3O%2F8FuYre0ieKfCAD8PLAiBD9ZKYMFgB40wuCpIIU9Hn1NOXZ5amVXFAyVVAHg70nir%2F\
  AwgkEAAaDDYzNzQyMzE4MzgwNSIMA8aFFeapKVhz7PabKtwDEbNRfjiKmT8p%2FMSEUiTe%2F7Xdf\
  Yy8Cf1I%2FfqMO5nxcbXAzIptkEnMPYXnImG94pBnIWXmPOXNQ6A8GXq3dpGCkM5VjPU%2B9d8TXI\
  RBr3%2B5%2B20KcKV0ZcaQIxZsbALhT6iQ9cTT0FoPAXf0yIC3tsDJGznBHco2iPGe4P9gM7rosfp\
  K7eWVbV%2Fe6ti%2FwfBfoN6vL845sgngt6xQcKjSz7bQ0XCjKJziIkiFsu0RKBKCQyq5sexmvXuf\
  T9a8ckVvRyjYq08r2nrWSlSJSqBftJrK%2Bs0907tQwrQjMjDURzFgJCMk9VyKhN9MEdhSPX%2Br7\
  UqwbK5VrhiQ0fJASHHnSZtykCXZe%2BUoFbgrFMzsJH44fJnfpLNrfYtBEUsdLRU2mOZ%2F08%2B2\
  P3p8qfzsu92IMy5B%2BHeBiobCX9TWilQqD6Gfclkh13EQHsh%2BOTUogGB5fxSnQh9d8Y4dyLbPA\
  TN1mvf2Wsd7Ft1ovBDpZxp1Som0dntQmtQHr%2Fxo7n%2FSE1MJFzOP7TP0Ocn4lO2UoCJ1yp1THW\
  woFfIUQSuYi0zKVNXC2L6meajrCKhL9Af91wRFXKG%2BmV6%2FzAY2eCJxlxonP%2B%2Fb3rkyg0i\
  PcdIeMNhM5RYl1x7TMNxB87m9E94vZG8wneu6vQY6pgF20bzH0jWDJjD0WOq8Y7SHB2abFPjBbZOn\
  ZW8%2BS5BN46n9ae%2FdofDk4FWilucRc%2FT83QT6Hdn25ZraFCbrwjeJYiEgQOaRuuzO5ogpPZb\
  aZ3DAZtUxVU9gL20KZaxL7oQzJybvFmTysn6wIIPabV1fSni%2BDXjhmh5tu%2B%2F0QT2cgRb%2B\
  SCWwXZh5IpS5TP2WdPo8g4OuhGNIn1JA8I6wyfUhKw9U5QF7&X-Amz-Signature=2a6fb7381dc7\
  b72d135b580ea66c9842183c057523acc5b1ead886a97a83cf4b&X-Amz-SignedHeaders=host\
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
        redential=ASIAZI2LB466QFVQ2IEX%2F20250214%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250214T052142Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQ\
        CID1TdWDmvpZ7ipO6KYKJqs30u8SVwqcZiV9o2ufmSduIAiBxOOHX32nZBrw7%2BWUPY0TX\
        KN8xM31YFqSxBdpo%2Bbg5pyr%2FAwgkEAAaDDYzNzQyMzE4MzgwNSIMl7X89%2FU4CjK2L\
        IZ%2FKtwDCH2EuZzK2euce1CbgvEyJ9KXDlKy0uBh%2FHgVcz86RZab%2BhPIwi0aQcD%2F\
        IofH2a7MMkUgNoz8zrtyVAKlWYkbzTCJLnU3R39KZPoHY7xpjJCLLbG0CJcXT97EsEhb46T\
        wOVh%2BgJHgoiRC7%2FRGBBqnN6TZoxGrzArQ419vr6gpIvdtY9pZzhWZXMe8uSZ%2BV26q\
        Vhx5JmU6VtNQj8pwkicH1uohREsOTdRcdntcx%2ByNAW9EPB3eY%2BGjE0WKhG8AVll4iMd\
        GMgxfiHDZkXgG32dPRM9je1KI2TvpUIikERYPitDAA%2F1R29MFtzBGnGi8NmqQQVxhEC3U\
        %2F5hCHzTssKjWK0Un65Ru1aFOUQq3kUATIlZA0vWrgi81Gn81wBiZNjfcpb5mBbzoSwl6G\
        u%2F6bMd9d5FvK3dfUi47Q4dNISSZ6PzFLzV2GQxhufRhjGz5RTGmWGv7TtULqDEQfCQQBB\
        un1WBsU3E15hIBHCIlKvd6Qcqywb8zdqdrkRUDizFqzkYSPFAjoxpcjBTBNguVxbz0DoHmd\
        dBTUYa6lQ%2BPgFxgFwxyfuEJRCl2fbDBIxzYjHE4g5TaALOe0Zl%2Ff9%2FpH%2Bm6WIDm\
        4FICwl3guqbm3R%2BBLQmTJRrOL5%2BA%2FhJVtiow9Oq6vQY6pgHrkdYud5hYepH3A7ya%\
        2Bpxm7y7NIcwyF%2Bs0rNBNFsSdOm1frL9kRYx7W8yQ%2BAyRJ%2BlpAL88QJXpcACJiRhM\
        rkXjW2rpzk2FPr%2FjpVnHyuU1yoQdUm8u8hxAXsR80v1dTDRO1iE3D%2FMlE75NrnWjJ6j\
        zW%2BuVUMFrveR3zLjy8OB5Jp%2B9UKmNIitr7SqM6avm1LCHf72IBgagrP0AJ7HLb4QpbK\
        l%2Fp%2BKS&X-Amz-Signature=989b96f786e202d9179d6ab2c8bcae607c46d5163407\
        ca5085aadf75c456f868&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-14T06:21:42.116Z"
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
UPDATE_TIME: "2025-02-14T05:23:15.908Z"
EXPIRY_TIME: "2025-02-14T06:23:01.863Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Q7AX5OGA%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T052302Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCfOzk2N%2BEphSd%2FMAqFQcCR5NzJR4EgCY5XbwjbDHVlSAIgE%2BJt4rIC26iXdjcsKP0D3pGA3nPEsrNsLsoGVFYMrqoq%2FwMIJBAAGgw2Mzc0MjMxODM4MDUiDHMs%2BINHPg1Wh1MywircA%2B2SKiKvPDZbpCNRuclQko4pQ%2FewMPdEa7ph1Oup9bEoLfv7v6M5rSzW5yDJwXObH6Ipvv%2BfqXrVd6bEoJrTPlBjWENcmWQKQ4I%2Fb%2B0yR8oWUyCAQDCwavkDRrvOlj2XLreiD55pG7zIdcWbvGZcGTNxmCEny3n%2Flwkz1udV60UhrXzX55qn%2F8yIlJ%2Fhv%2BSz1AWZfWGQtFNeiUrraUehCMbQmT%2B7hd3pyzjF%2FHvamHb0%2FS3WK3x%2B7y7hpQ5fXQbz9KEan3lNX%2FcuVvpo8WCrSkaTk5hcLRRtdf3yOWx20ROd06pwW%2B4AYlsIFYFUZeSm0wBzHSVKTwWhoAXFTiQjYzEc2UrBvYY5m%2B%2B7CrboFbKDsibmoAbxnuTQc5HnndkN%2FWZ9sLeQr8Tt6kK2UBVVP42w8WErS6U8c2QzheDDlyG2fwMnoMV3CsyJZNqwbgcVQCQcFheBoRiJhJKK5pWOyrDgkNMEirzZ%2BcWgWCfbA26qL4ujr%2Be3ztPyeRymHucoqjLH29XvHr4wSMPGF2d6yIUIL6kMKP2tqXQXhPPTKL1%2FGK1m8meRMPsO3Tvldx6UMlYfv3QLEQA1YfU%2FqGIDzPJCAL%2Bo%2FrLCBLUVenSDhPXnZLiylr2Jvk%2FsdC6FMPzqur0GOqUBZRABGZ9QSgGXIj%2BToaPlR%2Ff9fK7hwy6okJimE2sSBmd2KZvUvCNICi%2BcIcLz1r8pqeD7EuBNUMeeefeDoPnuHO%2FAsriDMXoTnVfwb3BleP1YpQV83HNncmp7gmk1EEsWbl2Oc8qyMwaVkmonAJ3B32xZ0BGP0ECBBuHI8BI9q9mtmU72TTz5XXDL08SErUsV%2FrceR7kk8uzf7zDq2exsUa%2B0a43D&X-Amz-Signature=8f93d23a208a7efc9c85a753bdf2d6313d380ff37a60fd2b5a5e8ab81b6c66b8&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Q7AX5OGA%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T052302Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCfOzk2N%2BEphSd%2FMAqFQcCR5NzJR4EgCY5XbwjbDHVlSAIgE%2BJt4rIC26iXdjcsKP0D3pGA3nPEsrNsLsoGVFYMrqoq%2FwMIJBAAGgw2Mzc0MjMxODM4MDUiDHMs%2BINHPg1Wh1MywircA%2B2SKiKvPDZbpCNRuclQko4pQ%2FewMPdEa7ph1Oup9bEoLfv7v6M5rSzW5yDJwXObH6Ipvv%2BfqXrVd6bEoJrTPlBjWENcmWQKQ4I%2Fb%2B0yR8oWUyCAQDCwavkDRrvOlj2XLreiD55pG7zIdcWbvGZcGTNxmCEny3n%2Flwkz1udV60UhrXzX55qn%2F8yIlJ%2Fhv%2BSz1AWZfWGQtFNeiUrraUehCMbQmT%2B7hd3pyzjF%2FHvamHb0%2FS3WK3x%2B7y7hpQ5fXQbz9KEan3lNX%2FcuVvpo8WCrSkaTk5hcLRRtdf3yOWx20ROd06pwW%2B4AYlsIFYFUZeSm0wBzHSVKTwWhoAXFTiQjYzEc2UrBvYY5m%2B%2B7CrboFbKDsibmoAbxnuTQc5HnndkN%2FWZ9sLeQr8Tt6kK2UBVVP42w8WErS6U8c2QzheDDlyG2fwMnoMV3CsyJZNqwbgcVQCQcFheBoRiJhJKK5pWOyrDgkNMEirzZ%2BcWgWCfbA26qL4ujr%2Be3ztPyeRymHucoqjLH29XvHr4wSMPGF2d6yIUIL6kMKP2tqXQXhPPTKL1%2FGK1m8meRMPsO3Tvldx6UMlYfv3QLEQA1YfU%2FqGIDzPJCAL%2Bo%2FrLCBLUVenSDhPXnZLiylr2Jvk%2FsdC6FMPzqur0GOqUBZRABGZ9QSgGXIj%2BToaPlR%2Ff9fK7hwy6okJimE2sSBmd2KZvUvCNICi%2BcIcLz1r8pqeD7EuBNUMeeefeDoPnuHO%2FAsriDMXoTnVfwb3BleP1YpQV83HNncmp7gmk1EEsWbl2Oc8qyMwaVkmonAJ3B32xZ0BGP0ECBBuHI8BI9q9mtmU72TTz5XXDL08SErUsV%2FrceR7kk8uzf7zDq2exsUa%2B0a43D&X-Amz-Signature=4187916531e2aa488ae2d5fccec805303d16e593140c14d23215c229c5af5a3d&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Q7AX5OGA%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T052302Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCfOzk2N%2BEphSd%2FMAqFQcCR5NzJR4EgCY5XbwjbDHVlSAIgE%2BJt4rIC26iXdjcsKP0D3pGA3nPEsrNsLsoGVFYMrqoq%2FwMIJBAAGgw2Mzc0MjMxODM4MDUiDHMs%2BINHPg1Wh1MywircA%2B2SKiKvPDZbpCNRuclQko4pQ%2FewMPdEa7ph1Oup9bEoLfv7v6M5rSzW5yDJwXObH6Ipvv%2BfqXrVd6bEoJrTPlBjWENcmWQKQ4I%2Fb%2B0yR8oWUyCAQDCwavkDRrvOlj2XLreiD55pG7zIdcWbvGZcGTNxmCEny3n%2Flwkz1udV60UhrXzX55qn%2F8yIlJ%2Fhv%2BSz1AWZfWGQtFNeiUrraUehCMbQmT%2B7hd3pyzjF%2FHvamHb0%2FS3WK3x%2B7y7hpQ5fXQbz9KEan3lNX%2FcuVvpo8WCrSkaTk5hcLRRtdf3yOWx20ROd06pwW%2B4AYlsIFYFUZeSm0wBzHSVKTwWhoAXFTiQjYzEc2UrBvYY5m%2B%2B7CrboFbKDsibmoAbxnuTQc5HnndkN%2FWZ9sLeQr8Tt6kK2UBVVP42w8WErS6U8c2QzheDDlyG2fwMnoMV3CsyJZNqwbgcVQCQcFheBoRiJhJKK5pWOyrDgkNMEirzZ%2BcWgWCfbA26qL4ujr%2Be3ztPyeRymHucoqjLH29XvHr4wSMPGF2d6yIUIL6kMKP2tqXQXhPPTKL1%2FGK1m8meRMPsO3Tvldx6UMlYfv3QLEQA1YfU%2FqGIDzPJCAL%2Bo%2FrLCBLUVenSDhPXnZLiylr2Jvk%2FsdC6FMPzqur0GOqUBZRABGZ9QSgGXIj%2BToaPlR%2Ff9fK7hwy6okJimE2sSBmd2KZvUvCNICi%2BcIcLz1r8pqeD7EuBNUMeeefeDoPnuHO%2FAsriDMXoTnVfwb3BleP1YpQV83HNncmp7gmk1EEsWbl2Oc8qyMwaVkmonAJ3B32xZ0BGP0ECBBuHI8BI9q9mtmU72TTz5XXDL08SErUsV%2FrceR7kk8uzf7zDq2exsUa%2B0a43D&X-Amz-Signature=942fc0d75203dc4d1d4205dbc5bab6d69025696d48f6d6a0c21ab05c63294cba&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Q7AX5OGA%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T052302Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCfOzk2N%2BEphSd%2FMAqFQcCR5NzJR4EgCY5XbwjbDHVlSAIgE%2BJt4rIC26iXdjcsKP0D3pGA3nPEsrNsLsoGVFYMrqoq%2FwMIJBAAGgw2Mzc0MjMxODM4MDUiDHMs%2BINHPg1Wh1MywircA%2B2SKiKvPDZbpCNRuclQko4pQ%2FewMPdEa7ph1Oup9bEoLfv7v6M5rSzW5yDJwXObH6Ipvv%2BfqXrVd6bEoJrTPlBjWENcmWQKQ4I%2Fb%2B0yR8oWUyCAQDCwavkDRrvOlj2XLreiD55pG7zIdcWbvGZcGTNxmCEny3n%2Flwkz1udV60UhrXzX55qn%2F8yIlJ%2Fhv%2BSz1AWZfWGQtFNeiUrraUehCMbQmT%2B7hd3pyzjF%2FHvamHb0%2FS3WK3x%2B7y7hpQ5fXQbz9KEan3lNX%2FcuVvpo8WCrSkaTk5hcLRRtdf3yOWx20ROd06pwW%2B4AYlsIFYFUZeSm0wBzHSVKTwWhoAXFTiQjYzEc2UrBvYY5m%2B%2B7CrboFbKDsibmoAbxnuTQc5HnndkN%2FWZ9sLeQr8Tt6kK2UBVVP42w8WErS6U8c2QzheDDlyG2fwMnoMV3CsyJZNqwbgcVQCQcFheBoRiJhJKK5pWOyrDgkNMEirzZ%2BcWgWCfbA26qL4ujr%2Be3ztPyeRymHucoqjLH29XvHr4wSMPGF2d6yIUIL6kMKP2tqXQXhPPTKL1%2FGK1m8meRMPsO3Tvldx6UMlYfv3QLEQA1YfU%2FqGIDzPJCAL%2Bo%2FrLCBLUVenSDhPXnZLiylr2Jvk%2FsdC6FMPzqur0GOqUBZRABGZ9QSgGXIj%2BToaPlR%2Ff9fK7hwy6okJimE2sSBmd2KZvUvCNICi%2BcIcLz1r8pqeD7EuBNUMeeefeDoPnuHO%2FAsriDMXoTnVfwb3BleP1YpQV83HNncmp7gmk1EEsWbl2Oc8qyMwaVkmonAJ3B32xZ0BGP0ECBBuHI8BI9q9mtmU72TTz5XXDL08SErUsV%2FrceR7kk8uzf7zDq2exsUa%2B0a43D&X-Amz-Signature=2cd2a0a1651e687eaa920c3532095454b816d181a43ea7be85711cb13210f489&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Q7AX5OGA%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T052302Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCfOzk2N%2BEphSd%2FMAqFQcCR5NzJR4EgCY5XbwjbDHVlSAIgE%2BJt4rIC26iXdjcsKP0D3pGA3nPEsrNsLsoGVFYMrqoq%2FwMIJBAAGgw2Mzc0MjMxODM4MDUiDHMs%2BINHPg1Wh1MywircA%2B2SKiKvPDZbpCNRuclQko4pQ%2FewMPdEa7ph1Oup9bEoLfv7v6M5rSzW5yDJwXObH6Ipvv%2BfqXrVd6bEoJrTPlBjWENcmWQKQ4I%2Fb%2B0yR8oWUyCAQDCwavkDRrvOlj2XLreiD55pG7zIdcWbvGZcGTNxmCEny3n%2Flwkz1udV60UhrXzX55qn%2F8yIlJ%2Fhv%2BSz1AWZfWGQtFNeiUrraUehCMbQmT%2B7hd3pyzjF%2FHvamHb0%2FS3WK3x%2B7y7hpQ5fXQbz9KEan3lNX%2FcuVvpo8WCrSkaTk5hcLRRtdf3yOWx20ROd06pwW%2B4AYlsIFYFUZeSm0wBzHSVKTwWhoAXFTiQjYzEc2UrBvYY5m%2B%2B7CrboFbKDsibmoAbxnuTQc5HnndkN%2FWZ9sLeQr8Tt6kK2UBVVP42w8WErS6U8c2QzheDDlyG2fwMnoMV3CsyJZNqwbgcVQCQcFheBoRiJhJKK5pWOyrDgkNMEirzZ%2BcWgWCfbA26qL4ujr%2Be3ztPyeRymHucoqjLH29XvHr4wSMPGF2d6yIUIL6kMKP2tqXQXhPPTKL1%2FGK1m8meRMPsO3Tvldx6UMlYfv3QLEQA1YfU%2FqGIDzPJCAL%2Bo%2FrLCBLUVenSDhPXnZLiylr2Jvk%2FsdC6FMPzqur0GOqUBZRABGZ9QSgGXIj%2BToaPlR%2Ff9fK7hwy6okJimE2sSBmd2KZvUvCNICi%2BcIcLz1r8pqeD7EuBNUMeeefeDoPnuHO%2FAsriDMXoTnVfwb3BleP1YpQV83HNncmp7gmk1EEsWbl2Oc8qyMwaVkmonAJ3B32xZ0BGP0ECBBuHI8BI9q9mtmU72TTz5XXDL08SErUsV%2FrceR7kk8uzf7zDq2exsUa%2B0a43D&X-Amz-Signature=272b9fefdb254cd6cfcb00161bea932c344344937b7d95985282d03d2e8fb5c5&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QMZ3WH6S%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T052303Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIDIrK0LA6dGbpm3RBHjaMomsEsUTMiDOMLVvW5YMoRvPAiEAnjN5VoWCJE7ruIXyuSsMNMsafDtLAfH%2FxPNY8wc3XLwq%2FwMIJBAAGgw2Mzc0MjMxODM4MDUiDGKIu1POlsQFpBjGgyrcA8TFlcmNmeaWhAGodeGuxxk6mlbZ0bykWTVe89z9%2B75DnDRYi6Ii0KNYOgzka00boruigZfiuU7SZq3ofJgNJGscrpihlhxXg%2FPEe3xKsEiTmWJr81R5rTHF5HLm5Aw%2FJ0gULk8Bk7gB%2B%2BVq5v8ppUE04zzRQYS9prXr2Io5HuzsthxV1CNwa2PqOAF6KLgoAlZmNWYxVaSZUrSlvClgCo6s84s78j%2FY2TH3BMPuKOH%2BYK7qSLRH%2BT9FzEh1GM3mvhd4O98nrIdN8s1hZyznbxPME3IXB6fHe1sNB8sKs4wGTp12aC3vMnJzauZgNNrn%2Bxl9%2F6x6yoGMM5E4PWv1pb99iAME%2B%2BUxJQXIGQnD%2FfB9jIRvSbsEOlBEy40OEbcOqkYxQwHnsXXIAbro4lQN9WBpXci%2FnFY1%2FDMjAuKfHf3%2FdGfzJ3JkSYGOMhbFeKqSvpQ3l3f1j%2FSRsYd%2B1aoIggB144jZFMJzo5DxxLhqE0m%2Fi1kDEzXPF5JeGsorLo4w9Wc43p2l28UmA9Yw7DAOiWHww8TluT70aDxg80SFwxLOsDqYApdMsr6ZiUerNLB04IeL5r5GALxc%2Bz1BGtfqa6ElRTjMEohjHyS1Tp%2FNVp4g7w5noFytOB6xPFeqMMzqur0GOqUBvM4kf%2FF55wyMCZPUjlYC7DbWN0kasmjdZh9rvhG%2FGss5IDdHwdeLCNW7aW77PIAbl7m%2BdtGPLegH2C2dZ5ysMAK%2B%2Fvz3geSMzoDGk8L8XORZcoWdFjzZ9U3s73pPRj7UlHx2R1qYzlyjWUuROU31%2BZyBQfFhO7M0xc4uAmOtmBjzuhnJztW0c%2Bb2j%2FG072qa8%2B1506C8DnEtf1bYbxZTWDcxoHBn&X-Amz-Signature=007b6f70f22949c963dac1a1a512845ffb825482864aebc59323d8527b5fa92d&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UEN2MQJQ%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T052303Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCICOVjsn%2BDsZmST3mzfA24TSyl6Opa0pMJUI8fIgQza0bAiEA%2BmZWHGg6o5xP27tdoQntuB3Xwja7HQ%2FyQAyL9YVEyscq%2FwMIJBAAGgw2Mzc0MjMxODM4MDUiDOEWJVBs6CBGQu6eoCrcA1IWcgJDNgoGBCRw3F8W3YJG3HyHOc1pz208QFICbRf7THNX2LdSJ8bOUnIdBTNmwqDsuESuHgSB0EoZ9zVAQTpa1cxUkT%2BB%2F0Pr0Bqze%2BnMaAI8fYZ%2BKddECYwm8o0CQFpbhmYDEQRzLdguhtBGetvr1BEpUi2SZwWqAf4fnC2YsjcWXaBQAiQlkyUjnRvMSr0VV0PgE7R7g0MkYiX7PnnPAbe1JSd8iae3rC9rg07d54sH3OLoEjtq%2FhfgJReMWHIW1kzqQ2I7VkXP4KlvI0Z7KCSS5S2KiZLOfkunGrJO9gd5VA3ivrun%2FTD%2BDn5jRvw7sI1SpxR%2BKsjwUAbme3Q%2B%2BTqt3Aql%2BEuqXpD6L75K2r7ZPRBE6ofSKJBCkXee3xgj6q8fgbm%2Fao2y4MX0uboVDDFL6b92PMLvXwjHMkFsEHgwyJCgQvHXxYMrBdofHNR5rKIxAIvXllCnlOREo2cL%2Bp%2BkichjTywKJzoS3cJayxyz525ZSPdjy%2FS1pSNIQ1POsHXEivP8amNxgaOEOWLwQ5htOejDtzcsepYJUA8oGGt44UxhT%2FYf2lDPofcampqMz%2B4zbUIf%2Fi5sZ7wB7DPAUISrSs%2FLvdXF8BKrLOBcccJQ3mm3aiU3Ic0eMNDqur0GOqUBiLjsRBGs1NOMSeJ9lT56%2Bnbs87mre43YVTJkuHcfvXvY%2FzRtSjbDKeFyswef6cTi33JvyqVmA4IokCorQSNJCoafZcsIwDoQCDIMOdW8e4RnvJaJYjVYd0SxdgWO7HGKNevcdHfMeRIfDNSnyb9BMHbYsMdEueObt0um7b0IGj0gdYdAh5AG2xySjqohfFksgexp1ukW0HS%2B7BDlW5pVTuCakzzE&X-Amz-Signature=efee5ee4eb846fe1cab022700ca4045bd8234600aabe8ce004a6f9b786c78f6f&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Q7AX5OGA%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T052302Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCfOzk2N%2BEphSd%2FMAqFQcCR5NzJR4EgCY5XbwjbDHVlSAIgE%2BJt4rIC26iXdjcsKP0D3pGA3nPEsrNsLsoGVFYMrqoq%2FwMIJBAAGgw2Mzc0MjMxODM4MDUiDHMs%2BINHPg1Wh1MywircA%2B2SKiKvPDZbpCNRuclQko4pQ%2FewMPdEa7ph1Oup9bEoLfv7v6M5rSzW5yDJwXObH6Ipvv%2BfqXrVd6bEoJrTPlBjWENcmWQKQ4I%2Fb%2B0yR8oWUyCAQDCwavkDRrvOlj2XLreiD55pG7zIdcWbvGZcGTNxmCEny3n%2Flwkz1udV60UhrXzX55qn%2F8yIlJ%2Fhv%2BSz1AWZfWGQtFNeiUrraUehCMbQmT%2B7hd3pyzjF%2FHvamHb0%2FS3WK3x%2B7y7hpQ5fXQbz9KEan3lNX%2FcuVvpo8WCrSkaTk5hcLRRtdf3yOWx20ROd06pwW%2B4AYlsIFYFUZeSm0wBzHSVKTwWhoAXFTiQjYzEc2UrBvYY5m%2B%2B7CrboFbKDsibmoAbxnuTQc5HnndkN%2FWZ9sLeQr8Tt6kK2UBVVP42w8WErS6U8c2QzheDDlyG2fwMnoMV3CsyJZNqwbgcVQCQcFheBoRiJhJKK5pWOyrDgkNMEirzZ%2BcWgWCfbA26qL4ujr%2Be3ztPyeRymHucoqjLH29XvHr4wSMPGF2d6yIUIL6kMKP2tqXQXhPPTKL1%2FGK1m8meRMPsO3Tvldx6UMlYfv3QLEQA1YfU%2FqGIDzPJCAL%2Bo%2FrLCBLUVenSDhPXnZLiylr2Jvk%2FsdC6FMPzqur0GOqUBZRABGZ9QSgGXIj%2BToaPlR%2Ff9fK7hwy6okJimE2sSBmd2KZvUvCNICi%2BcIcLz1r8pqeD7EuBNUMeeefeDoPnuHO%2FAsriDMXoTnVfwb3BleP1YpQV83HNncmp7gmk1EEsWbl2Oc8qyMwaVkmonAJ3B32xZ0BGP0ECBBuHI8BI9q9mtmU72TTz5XXDL08SErUsV%2FrceR7kk8uzf7zDq2exsUa%2B0a43D&X-Amz-Signature=f005cb66e0e7a9428f2b5900fe2bd5c3c687a660580dbd51721303aea94a39fc&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Q7AX5OGA%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T052302Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCfOzk2N%2BEphSd%2FMAqFQcCR5NzJR4EgCY5XbwjbDHVlSAIgE%2BJt4rIC26iXdjcsKP0D3pGA3nPEsrNsLsoGVFYMrqoq%2FwMIJBAAGgw2Mzc0MjMxODM4MDUiDHMs%2BINHPg1Wh1MywircA%2B2SKiKvPDZbpCNRuclQko4pQ%2FewMPdEa7ph1Oup9bEoLfv7v6M5rSzW5yDJwXObH6Ipvv%2BfqXrVd6bEoJrTPlBjWENcmWQKQ4I%2Fb%2B0yR8oWUyCAQDCwavkDRrvOlj2XLreiD55pG7zIdcWbvGZcGTNxmCEny3n%2Flwkz1udV60UhrXzX55qn%2F8yIlJ%2Fhv%2BSz1AWZfWGQtFNeiUrraUehCMbQmT%2B7hd3pyzjF%2FHvamHb0%2FS3WK3x%2B7y7hpQ5fXQbz9KEan3lNX%2FcuVvpo8WCrSkaTk5hcLRRtdf3yOWx20ROd06pwW%2B4AYlsIFYFUZeSm0wBzHSVKTwWhoAXFTiQjYzEc2UrBvYY5m%2B%2B7CrboFbKDsibmoAbxnuTQc5HnndkN%2FWZ9sLeQr8Tt6kK2UBVVP42w8WErS6U8c2QzheDDlyG2fwMnoMV3CsyJZNqwbgcVQCQcFheBoRiJhJKK5pWOyrDgkNMEirzZ%2BcWgWCfbA26qL4ujr%2Be3ztPyeRymHucoqjLH29XvHr4wSMPGF2d6yIUIL6kMKP2tqXQXhPPTKL1%2FGK1m8meRMPsO3Tvldx6UMlYfv3QLEQA1YfU%2FqGIDzPJCAL%2Bo%2FrLCBLUVenSDhPXnZLiylr2Jvk%2FsdC6FMPzqur0GOqUBZRABGZ9QSgGXIj%2BToaPlR%2Ff9fK7hwy6okJimE2sSBmd2KZvUvCNICi%2BcIcLz1r8pqeD7EuBNUMeeefeDoPnuHO%2FAsriDMXoTnVfwb3BleP1YpQV83HNncmp7gmk1EEsWbl2Oc8qyMwaVkmonAJ3B32xZ0BGP0ECBBuHI8BI9q9mtmU72TTz5XXDL08SErUsV%2FrceR7kk8uzf7zDq2exsUa%2B0a43D&X-Amz-Signature=d28b3db0e15439325f786a4c11b1ecb49bacc071dbdf2b4d6d5357e3abb8d75c&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Q7AX5OGA%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T052302Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCfOzk2N%2BEphSd%2FMAqFQcCR5NzJR4EgCY5XbwjbDHVlSAIgE%2BJt4rIC26iXdjcsKP0D3pGA3nPEsrNsLsoGVFYMrqoq%2FwMIJBAAGgw2Mzc0MjMxODM4MDUiDHMs%2BINHPg1Wh1MywircA%2B2SKiKvPDZbpCNRuclQko4pQ%2FewMPdEa7ph1Oup9bEoLfv7v6M5rSzW5yDJwXObH6Ipvv%2BfqXrVd6bEoJrTPlBjWENcmWQKQ4I%2Fb%2B0yR8oWUyCAQDCwavkDRrvOlj2XLreiD55pG7zIdcWbvGZcGTNxmCEny3n%2Flwkz1udV60UhrXzX55qn%2F8yIlJ%2Fhv%2BSz1AWZfWGQtFNeiUrraUehCMbQmT%2B7hd3pyzjF%2FHvamHb0%2FS3WK3x%2B7y7hpQ5fXQbz9KEan3lNX%2FcuVvpo8WCrSkaTk5hcLRRtdf3yOWx20ROd06pwW%2B4AYlsIFYFUZeSm0wBzHSVKTwWhoAXFTiQjYzEc2UrBvYY5m%2B%2B7CrboFbKDsibmoAbxnuTQc5HnndkN%2FWZ9sLeQr8Tt6kK2UBVVP42w8WErS6U8c2QzheDDlyG2fwMnoMV3CsyJZNqwbgcVQCQcFheBoRiJhJKK5pWOyrDgkNMEirzZ%2BcWgWCfbA26qL4ujr%2Be3ztPyeRymHucoqjLH29XvHr4wSMPGF2d6yIUIL6kMKP2tqXQXhPPTKL1%2FGK1m8meRMPsO3Tvldx6UMlYfv3QLEQA1YfU%2FqGIDzPJCAL%2Bo%2FrLCBLUVenSDhPXnZLiylr2Jvk%2FsdC6FMPzqur0GOqUBZRABGZ9QSgGXIj%2BToaPlR%2Ff9fK7hwy6okJimE2sSBmd2KZvUvCNICi%2BcIcLz1r8pqeD7EuBNUMeeefeDoPnuHO%2FAsriDMXoTnVfwb3BleP1YpQV83HNncmp7gmk1EEsWbl2Oc8qyMwaVkmonAJ3B32xZ0BGP0ECBBuHI8BI9q9mtmU72TTz5XXDL08SErUsV%2FrceR7kk8uzf7zDq2exsUa%2B0a43D&X-Amz-Signature=4f5088fc0c9259c0f1e86b2261f4d9cb2e64a01ca5e5b805ba6bb612f7a8b6d9&X-Amz-SignedHeaders=host&x-id=GetObject)


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

