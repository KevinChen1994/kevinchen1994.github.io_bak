---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466XIBALFFI%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250205T102439Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjECoaCXVzLXdlc3QtMiJHMEUCIQDd5%2FhkLWvlCbgNFj2yxZ0meTEaF%2BUqtxM21i9wbgPovQI\
  gYfemLhWhm1VMfCQglnQkhnV4lLqiKFatmBprfw5GfmIq%2FwMIQxAAGgw2Mzc0MjMxODM4MDUiDG\
  je9ipw3dfHWKgGfyrcA5Cx1t2J1Lol4zSkFINhn7mUhB1aJCQMeq0BH27%2BmHAYT4Bd%2B%2Bhfi\
  ucvJAL9kIQ0wG0NnpNhMZlptt70QedxyxAykRaNZYiRhEqwHKrXs8lmhtS6CRBP%2FP3pAmEdzboG\
  lqncrVi0Y5gq0war9SmMt8hGZKwNRqBBA7iKVxsl8wfsvw1R53ht0%2Bh58H7x%2F4QVQ4LjqRaPb\
  ERucA2V1nh0SJYptRwa2STs%2FBi%2BcGAFf84tOE3v2n%2Fdk%2FrvgaxhMEl2CpGpgtxLbG7LFP\
  pBhWilV0J%2BZnoDvFZ6LoJZNAvw9dOqLfNhrHK4d4kpTcJRZo4ZyuZVx0K7KdJ5mchNtJX3c1TPa\
  %2Fijv9BKx3tCQBDnYe2Etcy5lMlxPJyw50fApYImrwP1yeFghstAGSNUylBIN7IlctnfjJxij6eY\
  YkG0qTIGKjro9zlQMI9hqz%2FrsXyhfTwEJaFjBoasGarHm9l6O9PDX%2FVQCmXy8%2BwfdAw%2Ft\
  JIeRuUwHSapgfITe4vPr%2FTr4mGSnlkE%2Fu4YtXi3%2FGz%2F6BOUpp7HQRzvOV1qgXn62yjmi0\
  B2ZuLFw2x3CqhkDCwed%2Fdcmz8TJnV9tCmyWlVa1BNxto%2FdCZNpuhT9UNAf%2FY83bi3s7Kybh\
  GOTMwnmMKzxjL0GOqUBR1m8arCOdePtXPgSZ1tQqqgF3CN6UukEqqpuuC5zhkj4sdAqX%2Fj3yMju\
  8CYYtIWUR295U1eNCsPSDSwbIlXmOCThJ1nekYQhxMkeZwtGXqL34MOXgP8aT3T5H9%2BqaHhX8Pl\
  rdZ9tUZQlj11A7H07NgjLDU43FzXE6YUW5en7X3AtOFUczcn2ijELnT%2BQZbyxl0vO0wOMwR4j5L\
  M6NN8Y%2BFfqqqTk&X-Amz-Signature=660e72e8211361e40b64cadc21376169abee46b22e17\
  897783fd5cc14ed2b0ae&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466YUYSWDIR%2F20250205%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250205T102337Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjECoaCXVzLXdlc3QtMiJGMEQCIA%2FktlPIuv0J9FQN9OB%2Fe3zUzgI\
        wZqiAtQV7PuZ1r7T%2BAiAXMIoufk3%2Bv8uDAULLEh8rych9xn26%2Bxzs4ogL5sTTSCr%\
        2FAwhDEAAaDDYzNzQyMzE4MzgwNSIMkocojTPV89gVLk5iKtwDG%2Fd4ra9op92a6HQw1ya\
        gQSca1O1O4z%2BMzKA8%2FMtgCPqAKR%2F849QqH16IxjGVAJN8tB9t9KlOWY6%2FItxjem\
        Tj0SViTP30oMhDq%2BmwfTxj%2Fk88upe8WlFdrNIwApD2V2%2FZRxIXfHKVxUDgfDDTGmR\
        avaFgrTbsHIRcA9I0In4U5ea4ZypisNMWBnfdiigetdw2ElX2go0jtgejoc4kPRascg%2BG\
        KUIUAjtSIKLuGUquBMvoCrGqe8xW410VpPvFg4%2BIOVefhLCZqyMMauUZOvrheRDeqA2Pk\
        itmfdeXJQ7U%2Bj6wTgj%2BBW8RufYFafwNo9xaCQRUnENaFgt1N7Vl9B9jYQqidcNCo3eE\
        JYkIqlNbFGORGsttebagDivrkmMf%2F%2F9UCLzOCaeVZfb6d3x2328SSAkYb13jp2SIE7B\
        6njHf2vRG%2FyLH91XfDAh%2BtpdGaCFqQ%2FYV1ynNdVKvPkruggracOFyCLmr1af4MVH9\
        lMTfMioKvybDalbuze4tIkH9vMFvJXNR1z3q6NZLCNI67Ph129glJ1vx2%2Fc9bKoF3gHUj\
        Nx5kV2FGep1YK8aPgi63RO5DjYmrfvebsE1hHeyWa7JtTRVdPsxZWEqKPRtDfL6FHdYH6Dl\
        ZXs2hTaHMWAwpPKMvQY6pgGBfcD%2BHsyYO7cHyr8ml28APpv8gBIbeA8z39UtPK%2BKAl%\
        2FXzSj2s25Wl%2BOT2eAwTCjs2XAdy6hoN8UZTZbkx2x%2FzgpLj8Bq%2FBfhcBZdYrU%2B\
        6v%2FNKdb%2F1kiomi243lS%2B%2BqSn3TXF2F09Cz58YBohTfSiL4s2HZvPaQNYb7n7ByT\
        1c3IYWK%2FS%2FHnE4NUFunNaDyIhdXeka8INuBPb%2BIn4NT%2BenOudD2Yk&X-Amz-Sig\
        nature=9dcd302ee7b429a49750492635fff310f910f4a162a71d0e4b376e702ce66932\
        &X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-05T11:23:37.564Z"
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
UPDATE_TIME: "2025-02-05T10:24:47.777Z"
EXPIRY_TIME: "2025-02-05T11:24:38.252Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667WCW47VJ%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T102438Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECoaCXVzLXdlc3QtMiJGMEQCIEFtv%2F7cxOA64rNO4Wgm1g06GKSVPZqnq2RrdFa2zHiNAiBaosS401Jq%2B4n78R58gqo9w0zgpFc77GYkrr7enHcuXCr%2FAwhDEAAaDDYzNzQyMzE4MzgwNSIMkCMu2plztIXxAfsjKtwDZuaqorg92FNbI4t%2FbFcSm74soqsGFYd%2FY%2FKEIcbatx89SLLUZCF4hMWrCGehg2YNkpN9AZbtB59X%2FNKnbEJ1QBgMO1nHuRhSrSuhKeN8QHtnAE6w8UlvyHfNEqQs4%2F5xQPIuIhTZD2lbDThxRsZOkog06PEFhxTzGLy1e6qSQN9MLPOet%2FvxhV%2BfHbGZRGRUqJv%2FPSrhiWDDVu%2FQIw7XBZPkYT0LtyBBfXoNfQEgQphWGguwWnvsrCe2EopgItIAWhxZZWVU9rAX9Fa7HkFdCcaXaGhyjjXbxqIdfQ5c%2B0HsX5QFWk4sav2krNYBFgwCYKs3ufGktsan2IzUIcnCwq6WQG2%2FyDR%2BQ69o45CrfXVbhSd6wunmgWZ90eVQTmvdcrSMQZV2%2FyQHPXjUqyGQ%2FDVEA2kKsV7R1ud5ufQNxxQaj42akEYRfGa1wrdJI8n2DlPi1t3i9%2BvGVllbvag%2FeVc1JdBKrkpV8UkplHrJT0F3kRjhtfkNRifBMMQrhpTUkZ91S5HYDUiWi2CtYS4THiBaWd7%2F3avWYOvjr96oCucL9t0zTwGLzQaYoEGD0b8lsB33bIuiLPjSPrr2knY3I9zexuWlWrpZjN28HD7t2DjvqBGCveEjCFi4ba0wjvKMvQY6pgGyeYR%2BtQcy2Pf1TMpd6XhKGeeG%2BCZoBDk3NKopYHJAG8rt0Eiz3cIIUgSFJ3a43fBrvC7FIKgVzNipJxEmVdaml4rInR97DamEEH5y%2BRTIXeRJlAL8RVs64x3LPTjch4lqMoWlTdjgLtknYCijWSaK6HMaX3EN7mG4CNUWOWj9coA9j6mwuU%2FYVFVDBjAMcKld7JhTVuqu5gQgxhXBOjkgZuqn81UX&X-Amz-Signature=62042843ed20b73099bb4193f4f2abfceec65841c1be946af3409f4fac35194f&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667WCW47VJ%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T102438Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECoaCXVzLXdlc3QtMiJGMEQCIEFtv%2F7cxOA64rNO4Wgm1g06GKSVPZqnq2RrdFa2zHiNAiBaosS401Jq%2B4n78R58gqo9w0zgpFc77GYkrr7enHcuXCr%2FAwhDEAAaDDYzNzQyMzE4MzgwNSIMkCMu2plztIXxAfsjKtwDZuaqorg92FNbI4t%2FbFcSm74soqsGFYd%2FY%2FKEIcbatx89SLLUZCF4hMWrCGehg2YNkpN9AZbtB59X%2FNKnbEJ1QBgMO1nHuRhSrSuhKeN8QHtnAE6w8UlvyHfNEqQs4%2F5xQPIuIhTZD2lbDThxRsZOkog06PEFhxTzGLy1e6qSQN9MLPOet%2FvxhV%2BfHbGZRGRUqJv%2FPSrhiWDDVu%2FQIw7XBZPkYT0LtyBBfXoNfQEgQphWGguwWnvsrCe2EopgItIAWhxZZWVU9rAX9Fa7HkFdCcaXaGhyjjXbxqIdfQ5c%2B0HsX5QFWk4sav2krNYBFgwCYKs3ufGktsan2IzUIcnCwq6WQG2%2FyDR%2BQ69o45CrfXVbhSd6wunmgWZ90eVQTmvdcrSMQZV2%2FyQHPXjUqyGQ%2FDVEA2kKsV7R1ud5ufQNxxQaj42akEYRfGa1wrdJI8n2DlPi1t3i9%2BvGVllbvag%2FeVc1JdBKrkpV8UkplHrJT0F3kRjhtfkNRifBMMQrhpTUkZ91S5HYDUiWi2CtYS4THiBaWd7%2F3avWYOvjr96oCucL9t0zTwGLzQaYoEGD0b8lsB33bIuiLPjSPrr2knY3I9zexuWlWrpZjN28HD7t2DjvqBGCveEjCFi4ba0wjvKMvQY6pgGyeYR%2BtQcy2Pf1TMpd6XhKGeeG%2BCZoBDk3NKopYHJAG8rt0Eiz3cIIUgSFJ3a43fBrvC7FIKgVzNipJxEmVdaml4rInR97DamEEH5y%2BRTIXeRJlAL8RVs64x3LPTjch4lqMoWlTdjgLtknYCijWSaK6HMaX3EN7mG4CNUWOWj9coA9j6mwuU%2FYVFVDBjAMcKld7JhTVuqu5gQgxhXBOjkgZuqn81UX&X-Amz-Signature=7e39334dc1c2d764614a249e6c1cb74c04653cd5d2dc9588354641ca45ec3f16&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667WCW47VJ%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T102438Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECoaCXVzLXdlc3QtMiJGMEQCIEFtv%2F7cxOA64rNO4Wgm1g06GKSVPZqnq2RrdFa2zHiNAiBaosS401Jq%2B4n78R58gqo9w0zgpFc77GYkrr7enHcuXCr%2FAwhDEAAaDDYzNzQyMzE4MzgwNSIMkCMu2plztIXxAfsjKtwDZuaqorg92FNbI4t%2FbFcSm74soqsGFYd%2FY%2FKEIcbatx89SLLUZCF4hMWrCGehg2YNkpN9AZbtB59X%2FNKnbEJ1QBgMO1nHuRhSrSuhKeN8QHtnAE6w8UlvyHfNEqQs4%2F5xQPIuIhTZD2lbDThxRsZOkog06PEFhxTzGLy1e6qSQN9MLPOet%2FvxhV%2BfHbGZRGRUqJv%2FPSrhiWDDVu%2FQIw7XBZPkYT0LtyBBfXoNfQEgQphWGguwWnvsrCe2EopgItIAWhxZZWVU9rAX9Fa7HkFdCcaXaGhyjjXbxqIdfQ5c%2B0HsX5QFWk4sav2krNYBFgwCYKs3ufGktsan2IzUIcnCwq6WQG2%2FyDR%2BQ69o45CrfXVbhSd6wunmgWZ90eVQTmvdcrSMQZV2%2FyQHPXjUqyGQ%2FDVEA2kKsV7R1ud5ufQNxxQaj42akEYRfGa1wrdJI8n2DlPi1t3i9%2BvGVllbvag%2FeVc1JdBKrkpV8UkplHrJT0F3kRjhtfkNRifBMMQrhpTUkZ91S5HYDUiWi2CtYS4THiBaWd7%2F3avWYOvjr96oCucL9t0zTwGLzQaYoEGD0b8lsB33bIuiLPjSPrr2knY3I9zexuWlWrpZjN28HD7t2DjvqBGCveEjCFi4ba0wjvKMvQY6pgGyeYR%2BtQcy2Pf1TMpd6XhKGeeG%2BCZoBDk3NKopYHJAG8rt0Eiz3cIIUgSFJ3a43fBrvC7FIKgVzNipJxEmVdaml4rInR97DamEEH5y%2BRTIXeRJlAL8RVs64x3LPTjch4lqMoWlTdjgLtknYCijWSaK6HMaX3EN7mG4CNUWOWj9coA9j6mwuU%2FYVFVDBjAMcKld7JhTVuqu5gQgxhXBOjkgZuqn81UX&X-Amz-Signature=8b4c654c10181bfec0448aec265e7270a8aa86d6411078d2a7b6b567a4dd78d7&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667WCW47VJ%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T102438Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECoaCXVzLXdlc3QtMiJGMEQCIEFtv%2F7cxOA64rNO4Wgm1g06GKSVPZqnq2RrdFa2zHiNAiBaosS401Jq%2B4n78R58gqo9w0zgpFc77GYkrr7enHcuXCr%2FAwhDEAAaDDYzNzQyMzE4MzgwNSIMkCMu2plztIXxAfsjKtwDZuaqorg92FNbI4t%2FbFcSm74soqsGFYd%2FY%2FKEIcbatx89SLLUZCF4hMWrCGehg2YNkpN9AZbtB59X%2FNKnbEJ1QBgMO1nHuRhSrSuhKeN8QHtnAE6w8UlvyHfNEqQs4%2F5xQPIuIhTZD2lbDThxRsZOkog06PEFhxTzGLy1e6qSQN9MLPOet%2FvxhV%2BfHbGZRGRUqJv%2FPSrhiWDDVu%2FQIw7XBZPkYT0LtyBBfXoNfQEgQphWGguwWnvsrCe2EopgItIAWhxZZWVU9rAX9Fa7HkFdCcaXaGhyjjXbxqIdfQ5c%2B0HsX5QFWk4sav2krNYBFgwCYKs3ufGktsan2IzUIcnCwq6WQG2%2FyDR%2BQ69o45CrfXVbhSd6wunmgWZ90eVQTmvdcrSMQZV2%2FyQHPXjUqyGQ%2FDVEA2kKsV7R1ud5ufQNxxQaj42akEYRfGa1wrdJI8n2DlPi1t3i9%2BvGVllbvag%2FeVc1JdBKrkpV8UkplHrJT0F3kRjhtfkNRifBMMQrhpTUkZ91S5HYDUiWi2CtYS4THiBaWd7%2F3avWYOvjr96oCucL9t0zTwGLzQaYoEGD0b8lsB33bIuiLPjSPrr2knY3I9zexuWlWrpZjN28HD7t2DjvqBGCveEjCFi4ba0wjvKMvQY6pgGyeYR%2BtQcy2Pf1TMpd6XhKGeeG%2BCZoBDk3NKopYHJAG8rt0Eiz3cIIUgSFJ3a43fBrvC7FIKgVzNipJxEmVdaml4rInR97DamEEH5y%2BRTIXeRJlAL8RVs64x3LPTjch4lqMoWlTdjgLtknYCijWSaK6HMaX3EN7mG4CNUWOWj9coA9j6mwuU%2FYVFVDBjAMcKld7JhTVuqu5gQgxhXBOjkgZuqn81UX&X-Amz-Signature=e2e12a9472a6f0c26de54dfd623fc2fc733d237602596ee1f2aa94afad01e1dd&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667WCW47VJ%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T102438Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECoaCXVzLXdlc3QtMiJGMEQCIEFtv%2F7cxOA64rNO4Wgm1g06GKSVPZqnq2RrdFa2zHiNAiBaosS401Jq%2B4n78R58gqo9w0zgpFc77GYkrr7enHcuXCr%2FAwhDEAAaDDYzNzQyMzE4MzgwNSIMkCMu2plztIXxAfsjKtwDZuaqorg92FNbI4t%2FbFcSm74soqsGFYd%2FY%2FKEIcbatx89SLLUZCF4hMWrCGehg2YNkpN9AZbtB59X%2FNKnbEJ1QBgMO1nHuRhSrSuhKeN8QHtnAE6w8UlvyHfNEqQs4%2F5xQPIuIhTZD2lbDThxRsZOkog06PEFhxTzGLy1e6qSQN9MLPOet%2FvxhV%2BfHbGZRGRUqJv%2FPSrhiWDDVu%2FQIw7XBZPkYT0LtyBBfXoNfQEgQphWGguwWnvsrCe2EopgItIAWhxZZWVU9rAX9Fa7HkFdCcaXaGhyjjXbxqIdfQ5c%2B0HsX5QFWk4sav2krNYBFgwCYKs3ufGktsan2IzUIcnCwq6WQG2%2FyDR%2BQ69o45CrfXVbhSd6wunmgWZ90eVQTmvdcrSMQZV2%2FyQHPXjUqyGQ%2FDVEA2kKsV7R1ud5ufQNxxQaj42akEYRfGa1wrdJI8n2DlPi1t3i9%2BvGVllbvag%2FeVc1JdBKrkpV8UkplHrJT0F3kRjhtfkNRifBMMQrhpTUkZ91S5HYDUiWi2CtYS4THiBaWd7%2F3avWYOvjr96oCucL9t0zTwGLzQaYoEGD0b8lsB33bIuiLPjSPrr2knY3I9zexuWlWrpZjN28HD7t2DjvqBGCveEjCFi4ba0wjvKMvQY6pgGyeYR%2BtQcy2Pf1TMpd6XhKGeeG%2BCZoBDk3NKopYHJAG8rt0Eiz3cIIUgSFJ3a43fBrvC7FIKgVzNipJxEmVdaml4rInR97DamEEH5y%2BRTIXeRJlAL8RVs64x3LPTjch4lqMoWlTdjgLtknYCijWSaK6HMaX3EN7mG4CNUWOWj9coA9j6mwuU%2FYVFVDBjAMcKld7JhTVuqu5gQgxhXBOjkgZuqn81UX&X-Amz-Signature=8cb9a6971deeba542c27ecfa4e586d16e8fa7e682056ad048cc09349502ba309&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665G5V7EMD%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T102438Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECoaCXVzLXdlc3QtMiJHMEUCIQCyqqWUosERMOKMB16sBxshu4oWTok%2BupMtWNpAe6TDdAIgI1NLlxAzCCgdP6udIreB6zjxm9%2B269X0Ek%2FNc%2BQmR70q%2FwMIQxAAGgw2Mzc0MjMxODM4MDUiDIi1uWPrHCsLtsKLuyrcAz%2B%2B6GcxY99f%2BiPsKKTMluFI8Dqn1yPB8A7XMf%2FBU7mtdtZRE9N0wTqIemUlzMWL2hL1gnW9TzNEiJePve9r9mBj%2Bbm0jMym8nEl%2B10Tdtr7Tyqu0imNLHOOF9kF%2FnVB5qKH5mFiZl6wuajetoprfo4azj72wcVoTG%2BTin2MNEyKxTtj0UTpMKOV%2FzZ%2BW0NhacAvTrmSMHnBm6Iop51TOE%2BmCzAYQypoGToHVkIt0fNAvUnpPH66%2BYhRShFOk%2BDKD7fNrBuHX8YY4sp5ip1wfwW3J7H9p2AvPTKNaow8EMJaY2gy77WW49yq%2BanvRjaTPV3A7ohuUW13naW4Ph0T%2FcRTCg9V5en%2B%2BWxaiyXCKvo44mbQZG0GPoWlCeq5CvGyzotfqTMOuG6Ju%2BGyfchDtqWZiY4R4iwDJw2o9ryWj6IsN1l0kGhifToMZvs24G%2FhFBqtfdG9wbQTRuMzIW4Y%2FqOsBsduhGdScQc6j2wQK9WtosQ59Aq4bhdWJ3STQb93WsOL6%2BSibB0KiZQdJ2Li2OVcJVJCzvuNMxP7cLBjjzgn9Xy59nIct%2Bd0lCppedBPHCt34LrTUk%2BARL7zicribKbe1IDCAPxVIKOckji6rn5%2BjkFVMjdj5A1eKhEsMKDxjL0GOqUBbBaixCc3LZDQSMa%2BXCX%2FBKNoi4kkhWuiFsVwIrpeNCzf4NfAo5%2BRsgGZ8HPoo%2FA7S5Ep1jK%2B1J3te2Ks3D34%2BPY4GiQ3Tx6PXYy5h6NpLCDxA2IiyE3rIfxslQ51S9MFh6f4Wf425BLo%2BOJLAU0C66b2LqKDoQmJ52KRUvn4PBkLdwCifyb6dINou2f3Zk4yOGr4OqTFABw9YsgnH3Kxm%2B9H3pus&X-Amz-Signature=a66261e489a90c66b036ea220bb71424f098023ce5aebe78e91681c738b9a8fe&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662PEJWCX6%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T102439Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECoaCXVzLXdlc3QtMiJIMEYCIQDZn2ZU0fgiD1QS3FrXj9vbFc0Dk0B%2FsssI%2FQke6AKU%2FgIhAIbqyqy3p3D%2FLaOkQZ1GHKRBt0MOvHzbuZPY51V6GlnKKv8DCEMQABoMNjM3NDIzMTgzODA1IgxKyDOX2w9bzQnAadYq3APhZGA4m%2FqrKDDRoMT6EU7RiUEPlCfuWEIqwoU7fyo5iAR48sARfqeQ7UckZ5QhQGa7sFvhDnYGNdLOMAp63QKKJtk%2BgCcTBMw4a7Ow6mI3f8EmY8uOQQLcrqCuOhY2m%2F%2FxRA%2BY5VcOVtgy2h6dBZhizXrFs0wVYF6HX1yZmp0s9QjsbyLPKP%2BseELRfnQov6yXf6FG%2FU0cAgug7jzL%2B0f%2BgA3FeBPSPr7HkdbN9G3BygPpUXkvlLcBILF4W3i3Ma3N6EjS%2BAfkA93PxTdynPqtRArS%2FJx5ON8NyrfYk1OYTwqMoGTZVqsZGtW3AVla2m67IP0Af7hoHJHLmvDtDkaWY7T1pwObgfKDre8p81S8UffZuAH6IExpql3NgbK0yA0BfQLhK1bRX8aYvpF4c4Wf0icuyfQjeh%2B8feWwwbNNRN56yw2NdKVK%2FeWT3iPLtHYX0fSFb%2FeExqokfJfymwkxnLSULMCnK%2FrStdADufu7kzkGcRmxE7fWNXtzMgX7B3epbk0dq2UTMBB8a4gMIAHotR3Ihn37pfyoK0yoKwDME92GRauY%2FKfxP02RDbFeQbOL2Nab0iBzXaot070AbrQz%2Fqvxx46jsvFEEvYHsd7DCpqkFkWykrCqGHNqUTDT8Yy9BjqkAcxjoo6rYu1NbStHlLy9lpptiyAlhpqDGoaPLFDw783%2FnGYpIeKEp57H%2BgcjdPgFExEeSWy0DuZdikS7cs%2BZxfo%2Bjcfqla2HQyZqld4aNjFj9NJ1YJB7vqhrYjw1Ik5FvXgOV7QFHyjk6pS2J%2FhWRlDFRenONom30biJDSR4OsjBMR%2BL5D5uafau2fhuWuhQktczC1TLM7qArXpIC5v99s8Qgriu&X-Amz-Signature=820ba159f49dc5ef6d469a707a892e7c73eaecead6d78088b06c301b28ae2149&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667WCW47VJ%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T102438Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECoaCXVzLXdlc3QtMiJGMEQCIEFtv%2F7cxOA64rNO4Wgm1g06GKSVPZqnq2RrdFa2zHiNAiBaosS401Jq%2B4n78R58gqo9w0zgpFc77GYkrr7enHcuXCr%2FAwhDEAAaDDYzNzQyMzE4MzgwNSIMkCMu2plztIXxAfsjKtwDZuaqorg92FNbI4t%2FbFcSm74soqsGFYd%2FY%2FKEIcbatx89SLLUZCF4hMWrCGehg2YNkpN9AZbtB59X%2FNKnbEJ1QBgMO1nHuRhSrSuhKeN8QHtnAE6w8UlvyHfNEqQs4%2F5xQPIuIhTZD2lbDThxRsZOkog06PEFhxTzGLy1e6qSQN9MLPOet%2FvxhV%2BfHbGZRGRUqJv%2FPSrhiWDDVu%2FQIw7XBZPkYT0LtyBBfXoNfQEgQphWGguwWnvsrCe2EopgItIAWhxZZWVU9rAX9Fa7HkFdCcaXaGhyjjXbxqIdfQ5c%2B0HsX5QFWk4sav2krNYBFgwCYKs3ufGktsan2IzUIcnCwq6WQG2%2FyDR%2BQ69o45CrfXVbhSd6wunmgWZ90eVQTmvdcrSMQZV2%2FyQHPXjUqyGQ%2FDVEA2kKsV7R1ud5ufQNxxQaj42akEYRfGa1wrdJI8n2DlPi1t3i9%2BvGVllbvag%2FeVc1JdBKrkpV8UkplHrJT0F3kRjhtfkNRifBMMQrhpTUkZ91S5HYDUiWi2CtYS4THiBaWd7%2F3avWYOvjr96oCucL9t0zTwGLzQaYoEGD0b8lsB33bIuiLPjSPrr2knY3I9zexuWlWrpZjN28HD7t2DjvqBGCveEjCFi4ba0wjvKMvQY6pgGyeYR%2BtQcy2Pf1TMpd6XhKGeeG%2BCZoBDk3NKopYHJAG8rt0Eiz3cIIUgSFJ3a43fBrvC7FIKgVzNipJxEmVdaml4rInR97DamEEH5y%2BRTIXeRJlAL8RVs64x3LPTjch4lqMoWlTdjgLtknYCijWSaK6HMaX3EN7mG4CNUWOWj9coA9j6mwuU%2FYVFVDBjAMcKld7JhTVuqu5gQgxhXBOjkgZuqn81UX&X-Amz-Signature=af28c2ebc9d046bbd001e8a8df87069c1e49e94d3d3ba1013c6e3e99dbdc766d&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667WCW47VJ%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T102438Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECoaCXVzLXdlc3QtMiJGMEQCIEFtv%2F7cxOA64rNO4Wgm1g06GKSVPZqnq2RrdFa2zHiNAiBaosS401Jq%2B4n78R58gqo9w0zgpFc77GYkrr7enHcuXCr%2FAwhDEAAaDDYzNzQyMzE4MzgwNSIMkCMu2plztIXxAfsjKtwDZuaqorg92FNbI4t%2FbFcSm74soqsGFYd%2FY%2FKEIcbatx89SLLUZCF4hMWrCGehg2YNkpN9AZbtB59X%2FNKnbEJ1QBgMO1nHuRhSrSuhKeN8QHtnAE6w8UlvyHfNEqQs4%2F5xQPIuIhTZD2lbDThxRsZOkog06PEFhxTzGLy1e6qSQN9MLPOet%2FvxhV%2BfHbGZRGRUqJv%2FPSrhiWDDVu%2FQIw7XBZPkYT0LtyBBfXoNfQEgQphWGguwWnvsrCe2EopgItIAWhxZZWVU9rAX9Fa7HkFdCcaXaGhyjjXbxqIdfQ5c%2B0HsX5QFWk4sav2krNYBFgwCYKs3ufGktsan2IzUIcnCwq6WQG2%2FyDR%2BQ69o45CrfXVbhSd6wunmgWZ90eVQTmvdcrSMQZV2%2FyQHPXjUqyGQ%2FDVEA2kKsV7R1ud5ufQNxxQaj42akEYRfGa1wrdJI8n2DlPi1t3i9%2BvGVllbvag%2FeVc1JdBKrkpV8UkplHrJT0F3kRjhtfkNRifBMMQrhpTUkZ91S5HYDUiWi2CtYS4THiBaWd7%2F3avWYOvjr96oCucL9t0zTwGLzQaYoEGD0b8lsB33bIuiLPjSPrr2knY3I9zexuWlWrpZjN28HD7t2DjvqBGCveEjCFi4ba0wjvKMvQY6pgGyeYR%2BtQcy2Pf1TMpd6XhKGeeG%2BCZoBDk3NKopYHJAG8rt0Eiz3cIIUgSFJ3a43fBrvC7FIKgVzNipJxEmVdaml4rInR97DamEEH5y%2BRTIXeRJlAL8RVs64x3LPTjch4lqMoWlTdjgLtknYCijWSaK6HMaX3EN7mG4CNUWOWj9coA9j6mwuU%2FYVFVDBjAMcKld7JhTVuqu5gQgxhXBOjkgZuqn81UX&X-Amz-Signature=7b77f699e2bf680d459785cde6a856019efa4b21bd01bffb05788511009c3c0f&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667WCW47VJ%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T102438Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECoaCXVzLXdlc3QtMiJGMEQCIEFtv%2F7cxOA64rNO4Wgm1g06GKSVPZqnq2RrdFa2zHiNAiBaosS401Jq%2B4n78R58gqo9w0zgpFc77GYkrr7enHcuXCr%2FAwhDEAAaDDYzNzQyMzE4MzgwNSIMkCMu2plztIXxAfsjKtwDZuaqorg92FNbI4t%2FbFcSm74soqsGFYd%2FY%2FKEIcbatx89SLLUZCF4hMWrCGehg2YNkpN9AZbtB59X%2FNKnbEJ1QBgMO1nHuRhSrSuhKeN8QHtnAE6w8UlvyHfNEqQs4%2F5xQPIuIhTZD2lbDThxRsZOkog06PEFhxTzGLy1e6qSQN9MLPOet%2FvxhV%2BfHbGZRGRUqJv%2FPSrhiWDDVu%2FQIw7XBZPkYT0LtyBBfXoNfQEgQphWGguwWnvsrCe2EopgItIAWhxZZWVU9rAX9Fa7HkFdCcaXaGhyjjXbxqIdfQ5c%2B0HsX5QFWk4sav2krNYBFgwCYKs3ufGktsan2IzUIcnCwq6WQG2%2FyDR%2BQ69o45CrfXVbhSd6wunmgWZ90eVQTmvdcrSMQZV2%2FyQHPXjUqyGQ%2FDVEA2kKsV7R1ud5ufQNxxQaj42akEYRfGa1wrdJI8n2DlPi1t3i9%2BvGVllbvag%2FeVc1JdBKrkpV8UkplHrJT0F3kRjhtfkNRifBMMQrhpTUkZ91S5HYDUiWi2CtYS4THiBaWd7%2F3avWYOvjr96oCucL9t0zTwGLzQaYoEGD0b8lsB33bIuiLPjSPrr2knY3I9zexuWlWrpZjN28HD7t2DjvqBGCveEjCFi4ba0wjvKMvQY6pgGyeYR%2BtQcy2Pf1TMpd6XhKGeeG%2BCZoBDk3NKopYHJAG8rt0Eiz3cIIUgSFJ3a43fBrvC7FIKgVzNipJxEmVdaml4rInR97DamEEH5y%2BRTIXeRJlAL8RVs64x3LPTjch4lqMoWlTdjgLtknYCijWSaK6HMaX3EN7mG4CNUWOWj9coA9j6mwuU%2FYVFVDBjAMcKld7JhTVuqu5gQgxhXBOjkgZuqn81UX&X-Amz-Signature=9879122823c0e442486551848b7048bd62408894bb251dcb32caa2cacb99798f&X-Amz-SignedHeaders=host&x-id=GetObject)


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

