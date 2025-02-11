---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466VHCHBMZJ%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250211T212226Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEMT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIB0oklAmlOtFl4Phhs7\
  KQcvOsLpoK6R6XSSfN9vUKl6wAiBfGCoedOpVt11n8Pcb2iH0a49qPb1uI1ok%2Bt0aYK4OryqIBA\
  jc%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMgFz3U%2B5qZ%2F6mQ6H\
  EKtwDxSYIIfk3sXXaugGSJPWOy%2FFYyBtS%2Fk117kyu9bPNFKnpVkBQz6z0OUjP0IOLWr6JYXVl\
  UcVJlzVL8z4%2ByrJz4ioWf7OM%2BhbLSsQsAVd1y775CuEZPEubJead8CSs5r9VOT4jVjUeumnP0\
  FqNPxIx8pWGuwY9nvOhvDjkymBNokxnFrcg4gAIWORRb4LrI4HBO3VMhceKT%2BIK9b5FPZWb0WDa\
  PDw%2BWs2OykirXieZ9%2BAjIGAC6S7rEhstmyxeC9xbOmWPnCpWuJfnRf4DxadncsIMwZJn9Huyx\
  lSgtbQ6lcg25qmq9KvmCVSx5OOKuOojd49c%2BssrgdMbZQYTes42sML0PvezQe9lfztlUt4CTYV8\
  %2FUUc2cZynhwjgawq4iZ%2Flsl1vFGqf6GEgvdDxQvTPwFnLvKCkS9elp7Qszo2JAEurMkF1bgnc\
  OylKVs950MAp6FAgd2T%2FkzFFa3pHFhMBvFVgWjq34O81Ol4flJtB%2B5l9l0rasCyufymQb9I76\
  0TiG%2F7pzwsbRlmoo29vcWH3Oh9r8elha1TfDk9lD3P0yqjhmXfKs%2FkD7YYKHtuXoSE7GbIrmk\
  FIcY0AV%2FzgwkAcjIoDgq8YYS2DtKVDUqFJdRdx3W8RYKwYj9FD6AwusiuvQY6pgH85TyKDTQHHf\
  fl9m0BOaCpDtaEYm9Pn3wX%2BybpJw3hn%2F%2FLXs0Gy1RfRIyBJbvmMwPD%2BDKIaVrkpNDGty1\
  3UGF4dEF5x5S2wSpbyFVoRTwGHmftHvnFZj%2F34jJhGFXRCw3yPk1YnsQg9ylIr1fQFfn2fjTY9O\
  6wSdB4666L0mO7%2Fm4KosGXL0HZZyjPbEcvmTTPVJNmjuGwKiB%2B0EEJ59ZskyCakIHI&X-Amz-\
  Signature=f0eec0aaa9b8e3188e07055bf51277a1dd6cc98136d33e264bcd80b4b5923d54&X-\
  Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466Y4J2RK3C%2F20250211%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250211T212040Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEMT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQ\
        CIFvfAX3PhMWTu5Z%2BGZos7b01TPmhsRE5vVoryfvV%2BJhyAiBcnBYcVlwX895rrXKF5a\
        etbsvOWCEq6cEh8YzPM%2FZ5HiqIBAjd%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDY\
        zNzQyMzE4MzgwNSIMNq8uyAzV6warTQG3KtwDvHBJebq2HRMGyEnLgWs%2BSUpanfHWj%2B\
        HEewB11rXp8TGL5zLDL7nVVkE9mEJ94PdEubEUhGxUnePqxNncA8clHTkUGnjgLn7HGjTHY\
        %2Bqcy6Cfxb1LO%2FXHdck9zMnBYOiuk8lI6HRd4gY%2BXwhZ89R%2BURT8nHeIeRXDIMdS\
        9f70oynyv1C%2BfWJ97M9T8zj2rxfMuksb3XIbTKlsEg6j10VBtzYg26bgmAFo4QLpN7K4h\
        gnKuhd0pbd0soPfen10s%2BQENXY%2B67656DXTK4AqnvkIO2g3iO0hbQDAo5PVSCTkNUV1\
        n1vON6TlR7Z5WLbpoUC3VK77qYqrLKit%2BxqSZ%2FG%2BA3GZ266VSPqndp9EvZnJNSLQc\
        Juk5x1aUtMaPnB6l6h%2FI12GSiYAT9ogp7zAv4HWnJSTKyq15RtTvOWJy7e%2B%2BMgrVZ\
        RT0JaaKLJCWYQzdWSgnRvr6JKrne8fivN0hsOf7zwueXbSAYMdkmAn7hfz%2BNhLoyS3EaS\
        GALORoGsHb%2BR7HGND674AGaHU3HdxUovKRCNSPDcRPau6E9DdpvmRpUO550fcTSCEM8W1\
        h7NZaJOY1Ui%2BS8ajqksbQpG%2BufIYXBFDn%2FutrBh99WAN7w%2BDGh2ChGWl3vbVxc0\
        7q8MwxciuvQY6pgEF46kMX6YURtWB4w519CoPHCEA4XFR7VxX9hVz2jcb9xNhlCtn1QOr98\
        6DEuU5jnd0AzsBX9ZZMBzW%2BeoE32uyd2FB5j5MPLASuNB3LwSHC7I7pIzRu1DvNVLjpow\
        lI%2F0zm18a43sYEuBz2Oo60wPFbZbCjAMjMMBzkmGeSMQGTkHwI82vnmWOe1cxE1%2F8Pm\
        KIhncR1GBKr0oi4sRl9yBC3QqWizfM&X-Amz-Signature=7476af80cd4e041d72037579\
        1349755cd841f82d6d1f97a92f706ec0e23da01a&X-Amz-SignedHeaders=host&x-id=\
        GetObject"
      expiry_time: "2025-02-11T22:20:40.912Z"
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
UPDATE_TIME: "2025-02-11T21:22:33.620Z"
EXPIRY_TIME: "2025-02-11T22:22:21.821Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UTUVMPSF%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T212222Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCAF5zqhdcJ2CmIJrMwRAkOk99uPHGdu2DNjpbHfW%2F9KwIgagP1s8EL4pfbKwItlZPb556F2JvUYHJIr1BDIuw6ecAqiAQI3f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCPQjvLuGopOXXQo5CrcA308dI%2FdNOnlXNpV4UNtq1aB0xXM4929nYtXoJaHJv%2BTAaw5wMcWNrG%2F7syQtLnEW4e4LCDVMOZs5dd%2BOGjFkbFwwrrd%2BiTT99RmKceSh5F558i%2BMtLN68eC7OL%2BKgFyrDmpfQrXZOv284wFEAGTa0zF3QIS6jTDL4yyL%2BtqW1h8pKKk3NGB9VL%2FKv2GrbS1f7qNWxALKWRMhY%2FIqNocHGJTxeroJsOCvv1R5oa9Jx6q%2FemxHURVRaiHEwqXF1j0%2BkJgOJU%2BeRnnTru3GYUM09q%2BDCF7eSIG%2Bx1dZ8UInIs52xYp0pwUFCvOLOlH%2F4IHcQOyVr7i%2FkAn56PsJipWZJ8eiDnmyOppOUJmHnlo7HOM2AbvxcjG2lFE6b%2FkBKoXce%2Fn07t5MlgAQ%2F9Li6qbxQKdvZxreYem3X3Jim3UoLO8zSQaoh7tPofPr8Epf2yk9WIG6lVLPaGU3pIof7GXZiJbh9mqOn%2BuxOvdgS4C1ucHTFFVSrcNaYBn%2FburF9KFeKEHxOvBcXapFjhLvvKLSb2GTgJKH9vuQPn32fpbYZRBFNl6gNq0aCyGDQiUXXyKXoOlaAS3uxrKTn6aScG0d1CMPpaw2pKSQixVgHary17PtOSgCjEeLU%2BGxXQxMMHJrr0GOqUB5T%2BFZA4jAOJzounVn9ljtTEb5GHH7wDlXhrzX0YwsKS10Yp9Qc%2B5g4UkNvYJ9exVTuPnAs0u0epgkzFmges%2FF43wt5N7FYrTqWoee5DQCy%2F%2FoR8djJeE7x%2BswEOTgJDoNVaoR4NgG8QaFh3%2FzZkibgYdq91j6zdqdhXtfW3dSjs%2FKXgzdcguyXckG7h%2FdW%2BdqNqdmMFpytvPq1JXGu11ZTB3wVdk&X-Amz-Signature=ee39a7f6df2c5cd4882edb66da00de3c48043aa5b8c1920026b0dbd2bf74edaa&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UTUVMPSF%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T212222Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCAF5zqhdcJ2CmIJrMwRAkOk99uPHGdu2DNjpbHfW%2F9KwIgagP1s8EL4pfbKwItlZPb556F2JvUYHJIr1BDIuw6ecAqiAQI3f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCPQjvLuGopOXXQo5CrcA308dI%2FdNOnlXNpV4UNtq1aB0xXM4929nYtXoJaHJv%2BTAaw5wMcWNrG%2F7syQtLnEW4e4LCDVMOZs5dd%2BOGjFkbFwwrrd%2BiTT99RmKceSh5F558i%2BMtLN68eC7OL%2BKgFyrDmpfQrXZOv284wFEAGTa0zF3QIS6jTDL4yyL%2BtqW1h8pKKk3NGB9VL%2FKv2GrbS1f7qNWxALKWRMhY%2FIqNocHGJTxeroJsOCvv1R5oa9Jx6q%2FemxHURVRaiHEwqXF1j0%2BkJgOJU%2BeRnnTru3GYUM09q%2BDCF7eSIG%2Bx1dZ8UInIs52xYp0pwUFCvOLOlH%2F4IHcQOyVr7i%2FkAn56PsJipWZJ8eiDnmyOppOUJmHnlo7HOM2AbvxcjG2lFE6b%2FkBKoXce%2Fn07t5MlgAQ%2F9Li6qbxQKdvZxreYem3X3Jim3UoLO8zSQaoh7tPofPr8Epf2yk9WIG6lVLPaGU3pIof7GXZiJbh9mqOn%2BuxOvdgS4C1ucHTFFVSrcNaYBn%2FburF9KFeKEHxOvBcXapFjhLvvKLSb2GTgJKH9vuQPn32fpbYZRBFNl6gNq0aCyGDQiUXXyKXoOlaAS3uxrKTn6aScG0d1CMPpaw2pKSQixVgHary17PtOSgCjEeLU%2BGxXQxMMHJrr0GOqUB5T%2BFZA4jAOJzounVn9ljtTEb5GHH7wDlXhrzX0YwsKS10Yp9Qc%2B5g4UkNvYJ9exVTuPnAs0u0epgkzFmges%2FF43wt5N7FYrTqWoee5DQCy%2F%2FoR8djJeE7x%2BswEOTgJDoNVaoR4NgG8QaFh3%2FzZkibgYdq91j6zdqdhXtfW3dSjs%2FKXgzdcguyXckG7h%2FdW%2BdqNqdmMFpytvPq1JXGu11ZTB3wVdk&X-Amz-Signature=ce315039ba6e4bd0035343e573a81e2ff5d064f6d1e2b6f25b4a315e57e9c2ed&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UTUVMPSF%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T212222Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCAF5zqhdcJ2CmIJrMwRAkOk99uPHGdu2DNjpbHfW%2F9KwIgagP1s8EL4pfbKwItlZPb556F2JvUYHJIr1BDIuw6ecAqiAQI3f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCPQjvLuGopOXXQo5CrcA308dI%2FdNOnlXNpV4UNtq1aB0xXM4929nYtXoJaHJv%2BTAaw5wMcWNrG%2F7syQtLnEW4e4LCDVMOZs5dd%2BOGjFkbFwwrrd%2BiTT99RmKceSh5F558i%2BMtLN68eC7OL%2BKgFyrDmpfQrXZOv284wFEAGTa0zF3QIS6jTDL4yyL%2BtqW1h8pKKk3NGB9VL%2FKv2GrbS1f7qNWxALKWRMhY%2FIqNocHGJTxeroJsOCvv1R5oa9Jx6q%2FemxHURVRaiHEwqXF1j0%2BkJgOJU%2BeRnnTru3GYUM09q%2BDCF7eSIG%2Bx1dZ8UInIs52xYp0pwUFCvOLOlH%2F4IHcQOyVr7i%2FkAn56PsJipWZJ8eiDnmyOppOUJmHnlo7HOM2AbvxcjG2lFE6b%2FkBKoXce%2Fn07t5MlgAQ%2F9Li6qbxQKdvZxreYem3X3Jim3UoLO8zSQaoh7tPofPr8Epf2yk9WIG6lVLPaGU3pIof7GXZiJbh9mqOn%2BuxOvdgS4C1ucHTFFVSrcNaYBn%2FburF9KFeKEHxOvBcXapFjhLvvKLSb2GTgJKH9vuQPn32fpbYZRBFNl6gNq0aCyGDQiUXXyKXoOlaAS3uxrKTn6aScG0d1CMPpaw2pKSQixVgHary17PtOSgCjEeLU%2BGxXQxMMHJrr0GOqUB5T%2BFZA4jAOJzounVn9ljtTEb5GHH7wDlXhrzX0YwsKS10Yp9Qc%2B5g4UkNvYJ9exVTuPnAs0u0epgkzFmges%2FF43wt5N7FYrTqWoee5DQCy%2F%2FoR8djJeE7x%2BswEOTgJDoNVaoR4NgG8QaFh3%2FzZkibgYdq91j6zdqdhXtfW3dSjs%2FKXgzdcguyXckG7h%2FdW%2BdqNqdmMFpytvPq1JXGu11ZTB3wVdk&X-Amz-Signature=d186b023c23310b2b31b4f5610c49c7fd624bb63f53fea28a24388cc601cdeba&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UTUVMPSF%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T212222Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCAF5zqhdcJ2CmIJrMwRAkOk99uPHGdu2DNjpbHfW%2F9KwIgagP1s8EL4pfbKwItlZPb556F2JvUYHJIr1BDIuw6ecAqiAQI3f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCPQjvLuGopOXXQo5CrcA308dI%2FdNOnlXNpV4UNtq1aB0xXM4929nYtXoJaHJv%2BTAaw5wMcWNrG%2F7syQtLnEW4e4LCDVMOZs5dd%2BOGjFkbFwwrrd%2BiTT99RmKceSh5F558i%2BMtLN68eC7OL%2BKgFyrDmpfQrXZOv284wFEAGTa0zF3QIS6jTDL4yyL%2BtqW1h8pKKk3NGB9VL%2FKv2GrbS1f7qNWxALKWRMhY%2FIqNocHGJTxeroJsOCvv1R5oa9Jx6q%2FemxHURVRaiHEwqXF1j0%2BkJgOJU%2BeRnnTru3GYUM09q%2BDCF7eSIG%2Bx1dZ8UInIs52xYp0pwUFCvOLOlH%2F4IHcQOyVr7i%2FkAn56PsJipWZJ8eiDnmyOppOUJmHnlo7HOM2AbvxcjG2lFE6b%2FkBKoXce%2Fn07t5MlgAQ%2F9Li6qbxQKdvZxreYem3X3Jim3UoLO8zSQaoh7tPofPr8Epf2yk9WIG6lVLPaGU3pIof7GXZiJbh9mqOn%2BuxOvdgS4C1ucHTFFVSrcNaYBn%2FburF9KFeKEHxOvBcXapFjhLvvKLSb2GTgJKH9vuQPn32fpbYZRBFNl6gNq0aCyGDQiUXXyKXoOlaAS3uxrKTn6aScG0d1CMPpaw2pKSQixVgHary17PtOSgCjEeLU%2BGxXQxMMHJrr0GOqUB5T%2BFZA4jAOJzounVn9ljtTEb5GHH7wDlXhrzX0YwsKS10Yp9Qc%2B5g4UkNvYJ9exVTuPnAs0u0epgkzFmges%2FF43wt5N7FYrTqWoee5DQCy%2F%2FoR8djJeE7x%2BswEOTgJDoNVaoR4NgG8QaFh3%2FzZkibgYdq91j6zdqdhXtfW3dSjs%2FKXgzdcguyXckG7h%2FdW%2BdqNqdmMFpytvPq1JXGu11ZTB3wVdk&X-Amz-Signature=35cdbf8e6ea4692054a9240cc7d70133663114e073dd65da4f9316b8e35e4f15&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UTUVMPSF%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T212222Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCAF5zqhdcJ2CmIJrMwRAkOk99uPHGdu2DNjpbHfW%2F9KwIgagP1s8EL4pfbKwItlZPb556F2JvUYHJIr1BDIuw6ecAqiAQI3f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCPQjvLuGopOXXQo5CrcA308dI%2FdNOnlXNpV4UNtq1aB0xXM4929nYtXoJaHJv%2BTAaw5wMcWNrG%2F7syQtLnEW4e4LCDVMOZs5dd%2BOGjFkbFwwrrd%2BiTT99RmKceSh5F558i%2BMtLN68eC7OL%2BKgFyrDmpfQrXZOv284wFEAGTa0zF3QIS6jTDL4yyL%2BtqW1h8pKKk3NGB9VL%2FKv2GrbS1f7qNWxALKWRMhY%2FIqNocHGJTxeroJsOCvv1R5oa9Jx6q%2FemxHURVRaiHEwqXF1j0%2BkJgOJU%2BeRnnTru3GYUM09q%2BDCF7eSIG%2Bx1dZ8UInIs52xYp0pwUFCvOLOlH%2F4IHcQOyVr7i%2FkAn56PsJipWZJ8eiDnmyOppOUJmHnlo7HOM2AbvxcjG2lFE6b%2FkBKoXce%2Fn07t5MlgAQ%2F9Li6qbxQKdvZxreYem3X3Jim3UoLO8zSQaoh7tPofPr8Epf2yk9WIG6lVLPaGU3pIof7GXZiJbh9mqOn%2BuxOvdgS4C1ucHTFFVSrcNaYBn%2FburF9KFeKEHxOvBcXapFjhLvvKLSb2GTgJKH9vuQPn32fpbYZRBFNl6gNq0aCyGDQiUXXyKXoOlaAS3uxrKTn6aScG0d1CMPpaw2pKSQixVgHary17PtOSgCjEeLU%2BGxXQxMMHJrr0GOqUB5T%2BFZA4jAOJzounVn9ljtTEb5GHH7wDlXhrzX0YwsKS10Yp9Qc%2B5g4UkNvYJ9exVTuPnAs0u0epgkzFmges%2FF43wt5N7FYrTqWoee5DQCy%2F%2FoR8djJeE7x%2BswEOTgJDoNVaoR4NgG8QaFh3%2FzZkibgYdq91j6zdqdhXtfW3dSjs%2FKXgzdcguyXckG7h%2FdW%2BdqNqdmMFpytvPq1JXGu11ZTB3wVdk&X-Amz-Signature=194221c305d0f80a5227b4afb293ded2696551e30834b544bb2ca60d50536ae1&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZBPNIIQ7%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T212224Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDUiOO4RFd95dWO1YmSLWNOqO8Xo2XOUP1C2w3ItBT4fwIgHIvxRylcftMHnSRLHGAEn4QrMg194wRljjnVCbqyvPAqiAQI3f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMaBLKT4KP6qf1f5kircA0KbxmFazE2LVroj5U7P%2FDwYnm%2FcJu7yJBbLDu%2BWZBXMkfdRZ2nybLRIulruGekyb5xIjMmolZqI7syXpi%2FHcsSA9w%2B%2F9mpVJjwyNNHZXziuLVAeSacK15cw6L%2FStpBsUnKY6FQuwBb5o18yO6vCpoUWPF588l3qhu9Gr7%2FJdZ8iAj30ETxoRhVG9lFWqYTa%2Bfop2tfUSXxbtywL%2BhcSAdQ1VCmWxy0SE%2BNOmNNm2XqaV2HpNBxAII06nPe7OhVt4t%2BUqO%2BDlYBlyWslHBX3GcPJoVejFDqxVAqil0JOwc05tydTjBvlk%2FtxpvqbMAdGTc46B9b07JZuscIhvqQny%2BZk%2BpxtENQD8VzglNmsWIFq7YCDEym3ItdrLPh35RHmZ44CiLrp1vVheKS1I5yn6TBnGJSXYDAudUJnlOW9icEQvp%2FIkB%2B8%2BYg7lKsclwNkHS2Ard7o6A0yUL30qVGI8XfgsUwMDbtMPMH9h6%2FSaabx18CK82u1j3Dws9mqFm5LJ954u1%2BsfbnBuj5IH6l6Rbk2JPjJ5NPJGW93LJk875W3pi3YYh2jal%2BD2hLCB8V6HcaeyoqDl0fEXKAJiMg7X6iClichWfayzQHIfWsZUSLXBzNNE765xEQVly7zMOPIrr0GOqUBpwn2Fq1fs3qq7ayAZ9AAHgWaYSJ67dK6KFGCXsE1aMeOsQIu%2BDB9GnUDSGwi4Tudtgv%2BkgYfb7AQagB%2FM7IFQ%2B69TBNRgdDwZ3IScFNJ4MT1AtfdaSfRlqHRKEFJCwmg9u0VAD7OyESp26N3D25RQOx4NogewUYwIsiUtfO3q1130F3fVmNBmWH4I5dDECLe45Ev38%2BjKPrXDzRmg4nCRFvTFarr&X-Amz-Signature=4fa3c0fbf17dc752dbb0aa1b2c6d13ded663cd7497d163b70fc812463038b540&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664MZXKDPP%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T212226Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICyygk5aX5ifPE%2FL4b7V84oISyJ6wtNcxfwYlpixc4uTAiBzViJOJ5F%2Fme694aSWkj%2Bjo29xXPtHQSDuUX8m%2F8118SqIBAjd%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMZArB6kgqPnehiByQKtwD46S%2FT3FAVvyocs5p2N%2FNVyYHYm%2FbCYMZIPNCMmGajlQmmN9uzvNDFNyBYTeHVfuv9O6M8LFW%2BaHZ9NT7E0qnJmYjoRVGby%2FgwhbzTEM8Lfd7dDB9jLOYXYFocHcSIhL%2BGvBtqhIGz%2B7Ct1zTpTfE0OpRhRKXQNNJnP3TeVH7CcwY43tdSklc7hUvqnUN2aXfWYmIhdXl7ORUnp4FSnhjvNwOw3Hrgj5v%2BVNe9OElauv0gZpT%2Fl5ghj3xcMIqniTbwkqNAL0kRdlDsTRy3dEgRlbXQtF8P0OnNiLEusOL%2F9WkiGVYfKMBgOBRFg8Pn7VpGC4E%2FUUEsX%2BNF8sVk55vYrBhsn%2FddLHLQtjW1MWUlWH6l8QSCZpm1OSw0EbrS4Fncy51YKPq1coSyEPh1RFpqhgGA0PCif%2FeKFpzz1yBQR7pCWJ1Z7oTmxASznsYEwxGYKeZUsqmZEBbp%2FjniA9cBkDW2eNBn6G8nUT7k4ogrn5WPBuTE98jFOq%2FXTzEAFjZo6%2FA59wVCYK4BEgQvNXIDwmjXnohiGOpncSuazyagbhYmW46qvfexpTgOBQi%2BvEO%2B1OM0xTX%2FLgS2RcH8LrMZXV%2BkXUiO%2Fs%2Fb2Tgo0CBOa6otf1b3aqm3nlSq24w5siuvQY6pgEplZAqaITFEK2RAMc9w3CLdIY6Xcf7pGSKOVdkBTE3hYOocvdCXYNJW1%2Bd2O3iYGpoRcB9r4NT05a6f34kXindmfk9Q1ald1W38M7exBLA%2BexTllPOC3O8aPgOT5Iuf2kRvUZq9nU5nYs%2BEjVXcL%2Bipx%2FgEu2RcrEogopG0lUmpiFjLzmkBrWJjl8u0OyC35Rj4cxjDvk0CobvUGj0kiO4bPewlA5j&X-Amz-Signature=c0bb026b2bb6df559befd260df2b797c1e8ced3250388e4d1a5812e2d60a7234&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UTUVMPSF%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T212222Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCAF5zqhdcJ2CmIJrMwRAkOk99uPHGdu2DNjpbHfW%2F9KwIgagP1s8EL4pfbKwItlZPb556F2JvUYHJIr1BDIuw6ecAqiAQI3f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCPQjvLuGopOXXQo5CrcA308dI%2FdNOnlXNpV4UNtq1aB0xXM4929nYtXoJaHJv%2BTAaw5wMcWNrG%2F7syQtLnEW4e4LCDVMOZs5dd%2BOGjFkbFwwrrd%2BiTT99RmKceSh5F558i%2BMtLN68eC7OL%2BKgFyrDmpfQrXZOv284wFEAGTa0zF3QIS6jTDL4yyL%2BtqW1h8pKKk3NGB9VL%2FKv2GrbS1f7qNWxALKWRMhY%2FIqNocHGJTxeroJsOCvv1R5oa9Jx6q%2FemxHURVRaiHEwqXF1j0%2BkJgOJU%2BeRnnTru3GYUM09q%2BDCF7eSIG%2Bx1dZ8UInIs52xYp0pwUFCvOLOlH%2F4IHcQOyVr7i%2FkAn56PsJipWZJ8eiDnmyOppOUJmHnlo7HOM2AbvxcjG2lFE6b%2FkBKoXce%2Fn07t5MlgAQ%2F9Li6qbxQKdvZxreYem3X3Jim3UoLO8zSQaoh7tPofPr8Epf2yk9WIG6lVLPaGU3pIof7GXZiJbh9mqOn%2BuxOvdgS4C1ucHTFFVSrcNaYBn%2FburF9KFeKEHxOvBcXapFjhLvvKLSb2GTgJKH9vuQPn32fpbYZRBFNl6gNq0aCyGDQiUXXyKXoOlaAS3uxrKTn6aScG0d1CMPpaw2pKSQixVgHary17PtOSgCjEeLU%2BGxXQxMMHJrr0GOqUB5T%2BFZA4jAOJzounVn9ljtTEb5GHH7wDlXhrzX0YwsKS10Yp9Qc%2B5g4UkNvYJ9exVTuPnAs0u0epgkzFmges%2FF43wt5N7FYrTqWoee5DQCy%2F%2FoR8djJeE7x%2BswEOTgJDoNVaoR4NgG8QaFh3%2FzZkibgYdq91j6zdqdhXtfW3dSjs%2FKXgzdcguyXckG7h%2FdW%2BdqNqdmMFpytvPq1JXGu11ZTB3wVdk&X-Amz-Signature=3de141154c073d7122f73b07191d6601a223c06e36d844a29d8d56c99e3deaf0&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UTUVMPSF%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T212222Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCAF5zqhdcJ2CmIJrMwRAkOk99uPHGdu2DNjpbHfW%2F9KwIgagP1s8EL4pfbKwItlZPb556F2JvUYHJIr1BDIuw6ecAqiAQI3f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCPQjvLuGopOXXQo5CrcA308dI%2FdNOnlXNpV4UNtq1aB0xXM4929nYtXoJaHJv%2BTAaw5wMcWNrG%2F7syQtLnEW4e4LCDVMOZs5dd%2BOGjFkbFwwrrd%2BiTT99RmKceSh5F558i%2BMtLN68eC7OL%2BKgFyrDmpfQrXZOv284wFEAGTa0zF3QIS6jTDL4yyL%2BtqW1h8pKKk3NGB9VL%2FKv2GrbS1f7qNWxALKWRMhY%2FIqNocHGJTxeroJsOCvv1R5oa9Jx6q%2FemxHURVRaiHEwqXF1j0%2BkJgOJU%2BeRnnTru3GYUM09q%2BDCF7eSIG%2Bx1dZ8UInIs52xYp0pwUFCvOLOlH%2F4IHcQOyVr7i%2FkAn56PsJipWZJ8eiDnmyOppOUJmHnlo7HOM2AbvxcjG2lFE6b%2FkBKoXce%2Fn07t5MlgAQ%2F9Li6qbxQKdvZxreYem3X3Jim3UoLO8zSQaoh7tPofPr8Epf2yk9WIG6lVLPaGU3pIof7GXZiJbh9mqOn%2BuxOvdgS4C1ucHTFFVSrcNaYBn%2FburF9KFeKEHxOvBcXapFjhLvvKLSb2GTgJKH9vuQPn32fpbYZRBFNl6gNq0aCyGDQiUXXyKXoOlaAS3uxrKTn6aScG0d1CMPpaw2pKSQixVgHary17PtOSgCjEeLU%2BGxXQxMMHJrr0GOqUB5T%2BFZA4jAOJzounVn9ljtTEb5GHH7wDlXhrzX0YwsKS10Yp9Qc%2B5g4UkNvYJ9exVTuPnAs0u0epgkzFmges%2FF43wt5N7FYrTqWoee5DQCy%2F%2FoR8djJeE7x%2BswEOTgJDoNVaoR4NgG8QaFh3%2FzZkibgYdq91j6zdqdhXtfW3dSjs%2FKXgzdcguyXckG7h%2FdW%2BdqNqdmMFpytvPq1JXGu11ZTB3wVdk&X-Amz-Signature=73e83e8f535762c45b79882293b368e9c63bb5b6db81d347bf600e46d5af0b55&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UTUVMPSF%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T212222Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCAF5zqhdcJ2CmIJrMwRAkOk99uPHGdu2DNjpbHfW%2F9KwIgagP1s8EL4pfbKwItlZPb556F2JvUYHJIr1BDIuw6ecAqiAQI3f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCPQjvLuGopOXXQo5CrcA308dI%2FdNOnlXNpV4UNtq1aB0xXM4929nYtXoJaHJv%2BTAaw5wMcWNrG%2F7syQtLnEW4e4LCDVMOZs5dd%2BOGjFkbFwwrrd%2BiTT99RmKceSh5F558i%2BMtLN68eC7OL%2BKgFyrDmpfQrXZOv284wFEAGTa0zF3QIS6jTDL4yyL%2BtqW1h8pKKk3NGB9VL%2FKv2GrbS1f7qNWxALKWRMhY%2FIqNocHGJTxeroJsOCvv1R5oa9Jx6q%2FemxHURVRaiHEwqXF1j0%2BkJgOJU%2BeRnnTru3GYUM09q%2BDCF7eSIG%2Bx1dZ8UInIs52xYp0pwUFCvOLOlH%2F4IHcQOyVr7i%2FkAn56PsJipWZJ8eiDnmyOppOUJmHnlo7HOM2AbvxcjG2lFE6b%2FkBKoXce%2Fn07t5MlgAQ%2F9Li6qbxQKdvZxreYem3X3Jim3UoLO8zSQaoh7tPofPr8Epf2yk9WIG6lVLPaGU3pIof7GXZiJbh9mqOn%2BuxOvdgS4C1ucHTFFVSrcNaYBn%2FburF9KFeKEHxOvBcXapFjhLvvKLSb2GTgJKH9vuQPn32fpbYZRBFNl6gNq0aCyGDQiUXXyKXoOlaAS3uxrKTn6aScG0d1CMPpaw2pKSQixVgHary17PtOSgCjEeLU%2BGxXQxMMHJrr0GOqUB5T%2BFZA4jAOJzounVn9ljtTEb5GHH7wDlXhrzX0YwsKS10Yp9Qc%2B5g4UkNvYJ9exVTuPnAs0u0epgkzFmges%2FF43wt5N7FYrTqWoee5DQCy%2F%2FoR8djJeE7x%2BswEOTgJDoNVaoR4NgG8QaFh3%2FzZkibgYdq91j6zdqdhXtfW3dSjs%2FKXgzdcguyXckG7h%2FdW%2BdqNqdmMFpytvPq1JXGu11ZTB3wVdk&X-Amz-Signature=e1418366ae705d07d98c590785c391e37d7f0e005ad8d35373b7193570b1f5ac&X-Amz-SignedHeaders=host&x-id=GetObject)


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

