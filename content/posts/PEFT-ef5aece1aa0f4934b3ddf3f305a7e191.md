---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466RV5RPIOL%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250214T202447Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEAwaCXVzLXdlc3QtMiJIMEYCIQCT3I69X%2FlOCXCburq2GZ1VcE48mzCOayeoL0HRmLedbgIhA\
  IXg4zIvg1tK4Lk0YgOg%2F3Mzf72i6owJEaOAtYYO3vWvKv8DCDUQABoMNjM3NDIzMTgzODA1IgyB\
  827e%2FQwVcPVU3AQq3AMuEHVqLOCRgSVZ%2Fca5mL34TUWsaf7GqOfp0ysgIuspXzsTACtK%2Bub\
  H9k3NlQQeWyn1A6pAzbmp0B5cLtGGQPDTiwOjYWolmTPrm5IFo%2BIVkSFy4VCqWWVexgqzEl%2Fh\
  oYjbXIeNHcpfS3t%2FeyDdgcP%2FZiUmrYf5WojBVvR2IsCdljkqHzl4UltuRA7YFw4YCUys12ks5\
  OJX24AmPrFQ6hKJoQntz0fLgoIErShbtENwfxyWSDJ3KyReS5E2ZDPN5fxBvE9PBB%2FN09YvMFUT\
  UNqP8M9jGwYpqpopexJ4s5JjXAtL9z8kVVOZcwlVbIdy0KB%2F8V%2BVq1Oz4o2dlcLEfJZy1sB%2\
  BuKLOeTpp2RhOslAyFAWxu3ZvdZ8EwrFDM8xPOov%2FbJ%2BPB%2Fdw%2B243zDW5WZ0jcaq9faxH\
  JvIZd66sNwqldJvyJOI1%2Fr0doYJunCuIURuri%2FlRKO%2BD0E1e4mTwPcW3%2FVlGEQXJMWjqV\
  783htoNTbqvWXecVm7%2BsyoTufObhvJcP8mO7q%2BbcSG%2BPIermaFNpSitnoB8bGpfCeoXNsTw\
  AsaCViGrWVsTlhjeWjucjEy6gP4Gz8QePBMw1%2FRwOZUb%2FimoBfDimiUq9t7xESZYxU%2Bfprk\
  1gyeokhnEOjDDtb69BjqkAdJ0NI0Fj7003mF6qK28LGTTdI5pomS4bTs3tmGZTfIsr8LxCZ9goMxw\
  V4y%2F2VVrWR%2FkCyfgq2fdP6iADwRqNbpqAW9JgLsIjz5ib2XHQ0wGW%2FOwQe9Mj0LZRHVPP5z\
  rVgYzaxR6CDI%2FowKx27lN1F11USJuGycYbVX%2FD10mU1caAA2n8SxbwqcOPG%2FQm0GPLeTqdO\
  KwszTScai8oxnVvPAhLhYz&X-Amz-Signature=b367ad4692a6058bc0c871b1e87b46778ddcfb\
  f7e5c2d458d6f205ff1816081b&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466YYML6G2M%2F20250214%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250214T202334Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEAwaCXVzLXdlc3QtMiJHMEUCIQCwlUBjgHz58EMUptbvmE5ilBJ3nUr\
        990GtQGBOm5TvfwIgOx%2F3I23peLpKkxfFYCJug95cyI9C4yV9apkNJcw%2FE6cq%2FwMI\
        NRAAGgw2Mzc0MjMxODM4MDUiDOD2X5aqGPog0jWvFSrcA%2BeZWcn%2B%2BRiqieO0gTpKw\
        X8TtoMh8nuZNp4ZDRZQDnI8WfIqh8Rd%2B9dEG%2BPspnbDIEsdLevydi67HSbela59IvCT\
        NJBUj6U3pIH3Z9zjBPVffO%2Bnpp1rUhEGbcKmQInnKbRxooNLEuvw2%2FNBkoWdaInjSz0\
        lkC3eu1%2BzrtAOKtFyEb1Q26QX0JAzl5fYB6iQRxaZRFIlT6Xg7%2BrJqEE%2Biiw2mfJ3\
        V40U9bWF0lWcpB5nPjmqO8hU480%2B31l%2B1YSM33aGhb%2BfFGu%2B5ugChOnX9GtqEQB\
        bWZrvafw7523hba%2F1fkdqr%2FbbY6MypM3gp4o%2BoUDicMsyeRnPFNiNehPUmt0YE%2B\
        TMqz6xDeRLpKjnRYWbVHchxL3UWSheQSYqtlq%2BDNBUWva37E%2BWonGF1pGA%2F2CRUbh\
        E%2FKld12ScFO6ODnsi8pXVUGQ1Z1Dzp2RFuSl6a0tMozjpH42f1dk3wjMVQucpNXbDIG2Z\
        vAQdVy6YkupNit8vTjKfNqBDXVzzZOIa3srzodwAtWsEZUDnRvSVdPIRI0apIcFtt5iuFHW\
        vpBOd94Z2XPwip17LN%2FSsT78xvnpIX4jimA8LY7hGH1%2Fz0Hji1TPKrMfuW%2Fjp3D1n\
        fAkYqohMEHu45tvBWOPtMK21vr0GOqUBm9DbrqqzLsn1P3s96QP6CJVylVu1WQ9AGJO5mWQ\
        vCHh86CFNG0UElG5GFBTaG5yUVyY4Jgjvno9EmwNbysSB6duG%2FXOlmrgKCXWON2OtmHJA\
        brSgTtCf066kjTBDcejRSxt8zxyhhgfRey6dcgzyc%2B00p6VNawoC%2Fc5H%2FguKcRWYi\
        wdRsJIHIS59IkdAZehRImClGCHm9UY1r0RSF7lg9rJaXReG&X-Amz-Signature=7bd290e\
        cc8bc44923a57a24ee7070a189f648252da8e489a8f4a2a0a7fc9e718&X-Amz-SignedH\
        eaders=host&x-id=GetObject"
      expiry_time: "2025-02-14T21:23:34.891Z"
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
UPDATE_TIME: "2025-02-14T20:24:51.518Z"
EXPIRY_TIME: "2025-02-14T21:24:45.033Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YULOXJTW%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T202445Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAwaCXVzLXdlc3QtMiJHMEUCIALUukEwzXUOXLK75D51hqtpUPN0evYL2IG%2BFrGJWAIxAiEA8IzgHtXqpcSpWsxWFF7KhqNUz9LMJWhxA7dqFePtb8Iq%2FwMINRAAGgw2Mzc0MjMxODM4MDUiDHiZ3GAwNGDR2M3FUCrcAxVBa9wIfdpxF50OagSlmuUs9En5%2FvtlpG68FFAQgUrqXWJ1bDlT%2FIM7jeJ9oka4u%2B4FzlevN8SxRuCxbL%2B8eJ2iSmRZGqaai4K%2BxrqyWTWgD7TH%2ByDxID9AJ9j3R1s7FVcpHw%2FCmf85HXC%2F4GEudv3W9iuhorP7niifv6lbosokCAXvA%2BNNmwqDOuYcwPbhoBq4VLkV2E9ghWGKM5UCZoKW1VozwVhfhwRvaZABfKKuuzFPMAWAEKIL9EyutQnP%2BSfz6AvWdETt6sOP%2BAe8vFnPIA3vK3TeGWwxweNHMu4pUGaomagHhVp1RNh1jUKDurngoyKDkCyBK%2Fp9jNz4buDYDlkypBx7xx%2FI9z%2FTw4BfCuw4JnfRQpx8t9B6sJJk6RrQHq%2Fl1BxiEZTCfHFTGlje3N0fshV7%2BiJYoSZrJMGy%2BJu6TD2ehtg5NOU%2FzwckziINoBRSOMfTQnp%2FYZ0btCtdbM9FJj2G7frd3wZvyhheSxFR2ppjVGu1aZPsdDzOETtuNm9r6mUpTBXtmB%2BpuuSzbU6qwVegxRb8bggBJVDDpiU1IxwewXAhPimKbKg7HLlp884UCmVV5lp46MPkodMTCKVfD5PLrBixPolI3AumKjPbVbELv%2B68N93NMMK1vr0GOqUBrdH44tvmsE2X7Qq%2FSZxghuufR0QqFHXaXvlHmelnCfo7FhLvPii%2FYv3GJU380a5wFrvGKS1I7fUiF6jHUDMG4QzLW7BNPHiLBUaCr44hkfEGxuVCdBXUMCl%2BxnRTqxm2P%2BLAQi%2BS2Wndn9Zk10bxBcXbVrGTRqzkI5u%2FPIZxtT0DzSQY3okzmRdg0fFNmHVMu7dTWSr4pj2X0N1xq8GaFaBVvut7&X-Amz-Signature=ba39117a130d751c21bc29cd3864dd738b7f00286a980a2a774ffee84aab313b&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YULOXJTW%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T202445Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAwaCXVzLXdlc3QtMiJHMEUCIALUukEwzXUOXLK75D51hqtpUPN0evYL2IG%2BFrGJWAIxAiEA8IzgHtXqpcSpWsxWFF7KhqNUz9LMJWhxA7dqFePtb8Iq%2FwMINRAAGgw2Mzc0MjMxODM4MDUiDHiZ3GAwNGDR2M3FUCrcAxVBa9wIfdpxF50OagSlmuUs9En5%2FvtlpG68FFAQgUrqXWJ1bDlT%2FIM7jeJ9oka4u%2B4FzlevN8SxRuCxbL%2B8eJ2iSmRZGqaai4K%2BxrqyWTWgD7TH%2ByDxID9AJ9j3R1s7FVcpHw%2FCmf85HXC%2F4GEudv3W9iuhorP7niifv6lbosokCAXvA%2BNNmwqDOuYcwPbhoBq4VLkV2E9ghWGKM5UCZoKW1VozwVhfhwRvaZABfKKuuzFPMAWAEKIL9EyutQnP%2BSfz6AvWdETt6sOP%2BAe8vFnPIA3vK3TeGWwxweNHMu4pUGaomagHhVp1RNh1jUKDurngoyKDkCyBK%2Fp9jNz4buDYDlkypBx7xx%2FI9z%2FTw4BfCuw4JnfRQpx8t9B6sJJk6RrQHq%2Fl1BxiEZTCfHFTGlje3N0fshV7%2BiJYoSZrJMGy%2BJu6TD2ehtg5NOU%2FzwckziINoBRSOMfTQnp%2FYZ0btCtdbM9FJj2G7frd3wZvyhheSxFR2ppjVGu1aZPsdDzOETtuNm9r6mUpTBXtmB%2BpuuSzbU6qwVegxRb8bggBJVDDpiU1IxwewXAhPimKbKg7HLlp884UCmVV5lp46MPkodMTCKVfD5PLrBixPolI3AumKjPbVbELv%2B68N93NMMK1vr0GOqUBrdH44tvmsE2X7Qq%2FSZxghuufR0QqFHXaXvlHmelnCfo7FhLvPii%2FYv3GJU380a5wFrvGKS1I7fUiF6jHUDMG4QzLW7BNPHiLBUaCr44hkfEGxuVCdBXUMCl%2BxnRTqxm2P%2BLAQi%2BS2Wndn9Zk10bxBcXbVrGTRqzkI5u%2FPIZxtT0DzSQY3okzmRdg0fFNmHVMu7dTWSr4pj2X0N1xq8GaFaBVvut7&X-Amz-Signature=e4c57556790b7d44ab3b7d78d5bf90e46115b46eaeb18975e3fbea9e871f1b7a&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YULOXJTW%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T202445Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAwaCXVzLXdlc3QtMiJHMEUCIALUukEwzXUOXLK75D51hqtpUPN0evYL2IG%2BFrGJWAIxAiEA8IzgHtXqpcSpWsxWFF7KhqNUz9LMJWhxA7dqFePtb8Iq%2FwMINRAAGgw2Mzc0MjMxODM4MDUiDHiZ3GAwNGDR2M3FUCrcAxVBa9wIfdpxF50OagSlmuUs9En5%2FvtlpG68FFAQgUrqXWJ1bDlT%2FIM7jeJ9oka4u%2B4FzlevN8SxRuCxbL%2B8eJ2iSmRZGqaai4K%2BxrqyWTWgD7TH%2ByDxID9AJ9j3R1s7FVcpHw%2FCmf85HXC%2F4GEudv3W9iuhorP7niifv6lbosokCAXvA%2BNNmwqDOuYcwPbhoBq4VLkV2E9ghWGKM5UCZoKW1VozwVhfhwRvaZABfKKuuzFPMAWAEKIL9EyutQnP%2BSfz6AvWdETt6sOP%2BAe8vFnPIA3vK3TeGWwxweNHMu4pUGaomagHhVp1RNh1jUKDurngoyKDkCyBK%2Fp9jNz4buDYDlkypBx7xx%2FI9z%2FTw4BfCuw4JnfRQpx8t9B6sJJk6RrQHq%2Fl1BxiEZTCfHFTGlje3N0fshV7%2BiJYoSZrJMGy%2BJu6TD2ehtg5NOU%2FzwckziINoBRSOMfTQnp%2FYZ0btCtdbM9FJj2G7frd3wZvyhheSxFR2ppjVGu1aZPsdDzOETtuNm9r6mUpTBXtmB%2BpuuSzbU6qwVegxRb8bggBJVDDpiU1IxwewXAhPimKbKg7HLlp884UCmVV5lp46MPkodMTCKVfD5PLrBixPolI3AumKjPbVbELv%2B68N93NMMK1vr0GOqUBrdH44tvmsE2X7Qq%2FSZxghuufR0QqFHXaXvlHmelnCfo7FhLvPii%2FYv3GJU380a5wFrvGKS1I7fUiF6jHUDMG4QzLW7BNPHiLBUaCr44hkfEGxuVCdBXUMCl%2BxnRTqxm2P%2BLAQi%2BS2Wndn9Zk10bxBcXbVrGTRqzkI5u%2FPIZxtT0DzSQY3okzmRdg0fFNmHVMu7dTWSr4pj2X0N1xq8GaFaBVvut7&X-Amz-Signature=1c027801e3a941eb0bdda91dd022d9036cdb70bdf535d54661fb8c0e19fcdb98&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YULOXJTW%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T202445Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAwaCXVzLXdlc3QtMiJHMEUCIALUukEwzXUOXLK75D51hqtpUPN0evYL2IG%2BFrGJWAIxAiEA8IzgHtXqpcSpWsxWFF7KhqNUz9LMJWhxA7dqFePtb8Iq%2FwMINRAAGgw2Mzc0MjMxODM4MDUiDHiZ3GAwNGDR2M3FUCrcAxVBa9wIfdpxF50OagSlmuUs9En5%2FvtlpG68FFAQgUrqXWJ1bDlT%2FIM7jeJ9oka4u%2B4FzlevN8SxRuCxbL%2B8eJ2iSmRZGqaai4K%2BxrqyWTWgD7TH%2ByDxID9AJ9j3R1s7FVcpHw%2FCmf85HXC%2F4GEudv3W9iuhorP7niifv6lbosokCAXvA%2BNNmwqDOuYcwPbhoBq4VLkV2E9ghWGKM5UCZoKW1VozwVhfhwRvaZABfKKuuzFPMAWAEKIL9EyutQnP%2BSfz6AvWdETt6sOP%2BAe8vFnPIA3vK3TeGWwxweNHMu4pUGaomagHhVp1RNh1jUKDurngoyKDkCyBK%2Fp9jNz4buDYDlkypBx7xx%2FI9z%2FTw4BfCuw4JnfRQpx8t9B6sJJk6RrQHq%2Fl1BxiEZTCfHFTGlje3N0fshV7%2BiJYoSZrJMGy%2BJu6TD2ehtg5NOU%2FzwckziINoBRSOMfTQnp%2FYZ0btCtdbM9FJj2G7frd3wZvyhheSxFR2ppjVGu1aZPsdDzOETtuNm9r6mUpTBXtmB%2BpuuSzbU6qwVegxRb8bggBJVDDpiU1IxwewXAhPimKbKg7HLlp884UCmVV5lp46MPkodMTCKVfD5PLrBixPolI3AumKjPbVbELv%2B68N93NMMK1vr0GOqUBrdH44tvmsE2X7Qq%2FSZxghuufR0QqFHXaXvlHmelnCfo7FhLvPii%2FYv3GJU380a5wFrvGKS1I7fUiF6jHUDMG4QzLW7BNPHiLBUaCr44hkfEGxuVCdBXUMCl%2BxnRTqxm2P%2BLAQi%2BS2Wndn9Zk10bxBcXbVrGTRqzkI5u%2FPIZxtT0DzSQY3okzmRdg0fFNmHVMu7dTWSr4pj2X0N1xq8GaFaBVvut7&X-Amz-Signature=104218640488f373cf875add3783ef3b2b6e98f0ee00da4bb40770888a2e9da5&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YULOXJTW%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T202445Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAwaCXVzLXdlc3QtMiJHMEUCIALUukEwzXUOXLK75D51hqtpUPN0evYL2IG%2BFrGJWAIxAiEA8IzgHtXqpcSpWsxWFF7KhqNUz9LMJWhxA7dqFePtb8Iq%2FwMINRAAGgw2Mzc0MjMxODM4MDUiDHiZ3GAwNGDR2M3FUCrcAxVBa9wIfdpxF50OagSlmuUs9En5%2FvtlpG68FFAQgUrqXWJ1bDlT%2FIM7jeJ9oka4u%2B4FzlevN8SxRuCxbL%2B8eJ2iSmRZGqaai4K%2BxrqyWTWgD7TH%2ByDxID9AJ9j3R1s7FVcpHw%2FCmf85HXC%2F4GEudv3W9iuhorP7niifv6lbosokCAXvA%2BNNmwqDOuYcwPbhoBq4VLkV2E9ghWGKM5UCZoKW1VozwVhfhwRvaZABfKKuuzFPMAWAEKIL9EyutQnP%2BSfz6AvWdETt6sOP%2BAe8vFnPIA3vK3TeGWwxweNHMu4pUGaomagHhVp1RNh1jUKDurngoyKDkCyBK%2Fp9jNz4buDYDlkypBx7xx%2FI9z%2FTw4BfCuw4JnfRQpx8t9B6sJJk6RrQHq%2Fl1BxiEZTCfHFTGlje3N0fshV7%2BiJYoSZrJMGy%2BJu6TD2ehtg5NOU%2FzwckziINoBRSOMfTQnp%2FYZ0btCtdbM9FJj2G7frd3wZvyhheSxFR2ppjVGu1aZPsdDzOETtuNm9r6mUpTBXtmB%2BpuuSzbU6qwVegxRb8bggBJVDDpiU1IxwewXAhPimKbKg7HLlp884UCmVV5lp46MPkodMTCKVfD5PLrBixPolI3AumKjPbVbELv%2B68N93NMMK1vr0GOqUBrdH44tvmsE2X7Qq%2FSZxghuufR0QqFHXaXvlHmelnCfo7FhLvPii%2FYv3GJU380a5wFrvGKS1I7fUiF6jHUDMG4QzLW7BNPHiLBUaCr44hkfEGxuVCdBXUMCl%2BxnRTqxm2P%2BLAQi%2BS2Wndn9Zk10bxBcXbVrGTRqzkI5u%2FPIZxtT0DzSQY3okzmRdg0fFNmHVMu7dTWSr4pj2X0N1xq8GaFaBVvut7&X-Amz-Signature=a611e6482890970b9979a52b4ce58debfc3630c3c807d8e4a00aeccfadd9ceee&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667NKI5IRK%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T202445Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAwaCXVzLXdlc3QtMiJHMEUCIQCifGEG%2B9fqBnfnNtOBce5EISyeJtPeBv4KTQZZLd%2BkFwIgUnkZysxqWq7ndsMtQa0kEISoR%2BM37C78m%2FZ5UKCvRgIq%2FwMINRAAGgw2Mzc0MjMxODM4MDUiDBTm%2B5nZgiHBeygohyrcA9k2BlLd3pko0nDAqmhi9nzz5oAo52AopGWZlFIdj67MSXv5NKEjdXLFyKYrHD9GcFnKq4OksmXzQf%2BaI7y9vW0qkMGCMcs%2Fd3g2KQpzPcPYKcGY%2FdX5Iv72t0kw7w2IJYqGUpz6y0Okmvj88cDEkXSAU%2FLIAtf2%2F2c7Y8r7%2BfOubSYxdPq2C3jpz3%2F167Ltgz0xdf7lyoMhEfLXWB3cmev%2Bv%2BJ%2BNhlOUp0hW%2FK%2FWMk%2BjTPMen7CW0mvNt8zz9ckGgCU9XiKXa8WvvuYtTenlp%2Bdi10Y73EiietvFAt%2BSUA8T3DtC1S77F6sbav%2F78QiQb%2By3wbsIRAd6Z3CpEh85fHam1v%2BblrL%2FqdqguQEDg5vVb8f7Sf%2Ba%2BMHyM6d%2Fm3%2FE5BVOtmq1lssRZW9p10Z7HJK7fxNfkJP%2BS5KaBQF729YMMdZVTTcoMpfEau9cl68X7fkSJIFZ7Qr5v3ppKh7N1amGwXYFh5NnhVc3GUntz0byoAPAmHLaBmANJV4ky89qgRq4zy9cN0WiCxeHJOGmIaCO63JxIEGgpaTdlbi%2Br7MnYDVyr9p07F5JTmKBTGp%2FGOBQ%2BJ2%2F%2FoER7QfOAFPXMTDzR606g9wvWb%2FqOGhLLSiRbr9BIMoK34D%2BnysMIC2vr0GOqUBCcvdJVUFOwj0UPccMCg6HbL9VKIr81REuM4WeM%2BBBMSjqbOg%2B3DWvp8s0yZdMo2lX6lIHg8MxmWu50IYJUdRxTb2kwxG7z9ovYKBSlVvq0%2FXzTlSXtiVilhpDysAcsFm2hAsW9snARHWDuU7HIxHiFHyyz7VGwMf5uX0lTCYpED6ey0D8B1ktqhYGzsSr8OGXGtlV%2F%2FDcjIzt19wjH%2F0t50tHLZw&X-Amz-Signature=10886364dc54dd85581e8681f1a8d195bc0eecf003731927bce450c551267ff1&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666D7LZ7N4%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T202446Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAwaCXVzLXdlc3QtMiJHMEUCIQD1PdtslXymPsK73FQtHdwOfOhZsIzk7pwqGy5aZjx%2FewIgA4TX2vIT%2BY8RRGkBSYWHfyxmw7iFIQRlr%2F4xxMmdqW0q%2FwMINRAAGgw2Mzc0MjMxODM4MDUiDFz%2BzrzGok5CQR5owircA6T%2FCy4Khu474vv2Vi%2BsKZ3OsnHlJZOr6J7xJu2fUxbiLO70GaAkGKoHG%2BmdBvnyP5G%2B5dk0AV2tc4yKjv4FNFSHKCIzAM94gQEfCeA4Hkfcd01pmr09jaWbqELWzoPMrTfUhwRZ6jkLjRduLu%2FkvCReJJiyqIquBTc6O%2FYuSyJ7j9giOa%2BJgiWkdr9XEnaeQ6G9SUw7Ej023lu2gXr7QSW2YcNggQU6eO2sXHrQhUy98ZS6Boov%2BgBtf0qKLtfQCOni%2B%2FP71AtFxL9%2FUNmso3eru64JCUP%2B3wOC3kr4E%2BbSPCz%2FfRjfq%2BFqmaxhUXGIsuqVlX2T%2FcHdduBasOsi%2BNyGJEQkC5IugU3zM4LcJPULvQMTYqM%2FBH7tstli1L7SCDL%2FknchiOucetzVsyNmQke6HdXw%2FkuVSsTbQA2d11EtjTFwytXkuXD%2FQawjJMICOsA0ynf%2BRIe4kBqdEsTe72OO%2BPqHeoMRetT44amAnhPLLRP7xbYiyQDhbqhkLM5t4usroMAvndl4g8bv8BU1XcthdL8ynY6bvtvkOP5K83DI%2BK5fT5Li7lUgONasdx9nwRL%2BlKdmXwURftTLi9Gdw7%2FYmZVm07eEbOy614U2upKf611uueZwePPNLMdQMNy2vr0GOqUBlTE2%2FSXy27jUxSaHlqVQoKCaLBcwaVTA7XMFkuboq9WnJFoZspOMM%2FmZL%2Fzf3Cu5mU7GmpDy8CG95A0H0WmkgyJEKv%2F8lrxHk3LSE1k9JuWwlEa1pQmJUuDvMGNQVMoFNF19VPT31QumDAgOQrjc%2BOKXyWdUv6GrN%2BIIJmc%2FOYN%2BjE8OhdBECj2qfOmO3R89xCKla2%2BDRRqhOIxSt19dUqXLcB7a&X-Amz-Signature=46b554668592422f7d4e9966313fbad01a04ccc7744ea01a41d7aad384f73426&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YULOXJTW%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T202445Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAwaCXVzLXdlc3QtMiJHMEUCIALUukEwzXUOXLK75D51hqtpUPN0evYL2IG%2BFrGJWAIxAiEA8IzgHtXqpcSpWsxWFF7KhqNUz9LMJWhxA7dqFePtb8Iq%2FwMINRAAGgw2Mzc0MjMxODM4MDUiDHiZ3GAwNGDR2M3FUCrcAxVBa9wIfdpxF50OagSlmuUs9En5%2FvtlpG68FFAQgUrqXWJ1bDlT%2FIM7jeJ9oka4u%2B4FzlevN8SxRuCxbL%2B8eJ2iSmRZGqaai4K%2BxrqyWTWgD7TH%2ByDxID9AJ9j3R1s7FVcpHw%2FCmf85HXC%2F4GEudv3W9iuhorP7niifv6lbosokCAXvA%2BNNmwqDOuYcwPbhoBq4VLkV2E9ghWGKM5UCZoKW1VozwVhfhwRvaZABfKKuuzFPMAWAEKIL9EyutQnP%2BSfz6AvWdETt6sOP%2BAe8vFnPIA3vK3TeGWwxweNHMu4pUGaomagHhVp1RNh1jUKDurngoyKDkCyBK%2Fp9jNz4buDYDlkypBx7xx%2FI9z%2FTw4BfCuw4JnfRQpx8t9B6sJJk6RrQHq%2Fl1BxiEZTCfHFTGlje3N0fshV7%2BiJYoSZrJMGy%2BJu6TD2ehtg5NOU%2FzwckziINoBRSOMfTQnp%2FYZ0btCtdbM9FJj2G7frd3wZvyhheSxFR2ppjVGu1aZPsdDzOETtuNm9r6mUpTBXtmB%2BpuuSzbU6qwVegxRb8bggBJVDDpiU1IxwewXAhPimKbKg7HLlp884UCmVV5lp46MPkodMTCKVfD5PLrBixPolI3AumKjPbVbELv%2B68N93NMMK1vr0GOqUBrdH44tvmsE2X7Qq%2FSZxghuufR0QqFHXaXvlHmelnCfo7FhLvPii%2FYv3GJU380a5wFrvGKS1I7fUiF6jHUDMG4QzLW7BNPHiLBUaCr44hkfEGxuVCdBXUMCl%2BxnRTqxm2P%2BLAQi%2BS2Wndn9Zk10bxBcXbVrGTRqzkI5u%2FPIZxtT0DzSQY3okzmRdg0fFNmHVMu7dTWSr4pj2X0N1xq8GaFaBVvut7&X-Amz-Signature=046922009d4a154c1162cc43cbb5b79e88456b9fbe4c380465f35c1eaef09065&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YULOXJTW%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T202445Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAwaCXVzLXdlc3QtMiJHMEUCIALUukEwzXUOXLK75D51hqtpUPN0evYL2IG%2BFrGJWAIxAiEA8IzgHtXqpcSpWsxWFF7KhqNUz9LMJWhxA7dqFePtb8Iq%2FwMINRAAGgw2Mzc0MjMxODM4MDUiDHiZ3GAwNGDR2M3FUCrcAxVBa9wIfdpxF50OagSlmuUs9En5%2FvtlpG68FFAQgUrqXWJ1bDlT%2FIM7jeJ9oka4u%2B4FzlevN8SxRuCxbL%2B8eJ2iSmRZGqaai4K%2BxrqyWTWgD7TH%2ByDxID9AJ9j3R1s7FVcpHw%2FCmf85HXC%2F4GEudv3W9iuhorP7niifv6lbosokCAXvA%2BNNmwqDOuYcwPbhoBq4VLkV2E9ghWGKM5UCZoKW1VozwVhfhwRvaZABfKKuuzFPMAWAEKIL9EyutQnP%2BSfz6AvWdETt6sOP%2BAe8vFnPIA3vK3TeGWwxweNHMu4pUGaomagHhVp1RNh1jUKDurngoyKDkCyBK%2Fp9jNz4buDYDlkypBx7xx%2FI9z%2FTw4BfCuw4JnfRQpx8t9B6sJJk6RrQHq%2Fl1BxiEZTCfHFTGlje3N0fshV7%2BiJYoSZrJMGy%2BJu6TD2ehtg5NOU%2FzwckziINoBRSOMfTQnp%2FYZ0btCtdbM9FJj2G7frd3wZvyhheSxFR2ppjVGu1aZPsdDzOETtuNm9r6mUpTBXtmB%2BpuuSzbU6qwVegxRb8bggBJVDDpiU1IxwewXAhPimKbKg7HLlp884UCmVV5lp46MPkodMTCKVfD5PLrBixPolI3AumKjPbVbELv%2B68N93NMMK1vr0GOqUBrdH44tvmsE2X7Qq%2FSZxghuufR0QqFHXaXvlHmelnCfo7FhLvPii%2FYv3GJU380a5wFrvGKS1I7fUiF6jHUDMG4QzLW7BNPHiLBUaCr44hkfEGxuVCdBXUMCl%2BxnRTqxm2P%2BLAQi%2BS2Wndn9Zk10bxBcXbVrGTRqzkI5u%2FPIZxtT0DzSQY3okzmRdg0fFNmHVMu7dTWSr4pj2X0N1xq8GaFaBVvut7&X-Amz-Signature=9382d36ac99211e3efa57ce7e0de590bf445a66fdd0d43a5e4e2a8548511eb34&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YULOXJTW%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T202445Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAwaCXVzLXdlc3QtMiJHMEUCIALUukEwzXUOXLK75D51hqtpUPN0evYL2IG%2BFrGJWAIxAiEA8IzgHtXqpcSpWsxWFF7KhqNUz9LMJWhxA7dqFePtb8Iq%2FwMINRAAGgw2Mzc0MjMxODM4MDUiDHiZ3GAwNGDR2M3FUCrcAxVBa9wIfdpxF50OagSlmuUs9En5%2FvtlpG68FFAQgUrqXWJ1bDlT%2FIM7jeJ9oka4u%2B4FzlevN8SxRuCxbL%2B8eJ2iSmRZGqaai4K%2BxrqyWTWgD7TH%2ByDxID9AJ9j3R1s7FVcpHw%2FCmf85HXC%2F4GEudv3W9iuhorP7niifv6lbosokCAXvA%2BNNmwqDOuYcwPbhoBq4VLkV2E9ghWGKM5UCZoKW1VozwVhfhwRvaZABfKKuuzFPMAWAEKIL9EyutQnP%2BSfz6AvWdETt6sOP%2BAe8vFnPIA3vK3TeGWwxweNHMu4pUGaomagHhVp1RNh1jUKDurngoyKDkCyBK%2Fp9jNz4buDYDlkypBx7xx%2FI9z%2FTw4BfCuw4JnfRQpx8t9B6sJJk6RrQHq%2Fl1BxiEZTCfHFTGlje3N0fshV7%2BiJYoSZrJMGy%2BJu6TD2ehtg5NOU%2FzwckziINoBRSOMfTQnp%2FYZ0btCtdbM9FJj2G7frd3wZvyhheSxFR2ppjVGu1aZPsdDzOETtuNm9r6mUpTBXtmB%2BpuuSzbU6qwVegxRb8bggBJVDDpiU1IxwewXAhPimKbKg7HLlp884UCmVV5lp46MPkodMTCKVfD5PLrBixPolI3AumKjPbVbELv%2B68N93NMMK1vr0GOqUBrdH44tvmsE2X7Qq%2FSZxghuufR0QqFHXaXvlHmelnCfo7FhLvPii%2FYv3GJU380a5wFrvGKS1I7fUiF6jHUDMG4QzLW7BNPHiLBUaCr44hkfEGxuVCdBXUMCl%2BxnRTqxm2P%2BLAQi%2BS2Wndn9Zk10bxBcXbVrGTRqzkI5u%2FPIZxtT0DzSQY3okzmRdg0fFNmHVMu7dTWSr4pj2X0N1xq8GaFaBVvut7&X-Amz-Signature=b732105b79d329432e763d9ea63c83bd520c759519ad7319283fd09afca63dfd&X-Amz-SignedHeaders=host&x-id=GetObject)


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

