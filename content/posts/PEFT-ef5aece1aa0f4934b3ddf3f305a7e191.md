---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466ZUXHL7DZ%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250215T063115Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEBYaCXVzLXdlc3QtMiJHMEUCIQCdXImduPBwrIoar%2FUSg0mO9KpwmATyH6QtoBIIe84f0QIgF\
  xZpLPoiuH17S8Yc%2FmZKawhhKNnwjcCmszYvi2MN5Xsq%2FwMIPxAAGgw2Mzc0MjMxODM4MDUiDD\
  kf6PVHIyVjoLV81ircA8UhCf6kEUIfWMw1uZuQu09wb%2Fx7PxNYASnaaXVCSQA1LZRw1iBka2rxb\
  Qy%2FuV2xpi9jXgRg2EvvdmP4VzFuiUtI9V4tNWmObDdvClN6SKaCch0jo1CygW6O7SMQlq02eJuB\
  %2BnuedaKiBRPY4EFrLIBwLAdbanZV7YTWNs62Wa1uW8mGgOh27YLBB%2FU%2F0vo%2F2JqvZR40E\
  5XbOeWkjAoljPscHp81jJkw%2Bii%2FFOJ%2Fq1Dznm4fB4%2FfM4gGnKa1NUadotGWnsY86N34g7\
  7wTRo%2BQYZc2J8xVu4JYhsiS6SqmkIeLl9Px2Jt0km4CWThaxaO2aPS1GQGtityWHK8f7liG4%2B\
  y41qFNqBzUHSIAZ9igz%2Fy%2Bv9IsgYQApgkyXK3q8gNOfCOVwKYAWoil1l5OHZ%2FDZhk1Mi0D9\
  UEDkOTyzAzxDw8HnXZaZtm1if2m%2FS2f9O2TYpjlguoOWI0r4FSFH7oi1wqe0nu8Oy8SZUMFnj8L\
  AW%2Fs6nPQsA75YM9VzWBB0xO07RGK8fR9zIBvDol%2B1VtKg0vvZgMoRaYI60NTVhg%2BmZymCN1\
  bjhd3PXtz9%2B1bqIrlpmowrsDsr6V3aNZqHThcAYmGN9xcvg5AeIT%2BlSfoiB5a7sNp1FGtxQSh\
  MiAMNvMwL0GOqUBC5RQQucPckkISRGJqVJ2AMuiJTnvYNKYk8pzC%2BgTh%2FalvnP0n1dz%2F8fZ\
  doTa4OiTAm5rDlOsmjWhSQEE%2BGTQhWZ7OcZwp6RF9fU2dzmaOPbpQofWulm542psg%2FvMV4fLb\
  9%2B6Py31XUu5Tn1G3AJ5wv0XWtITpX6EQDuiNx%2FqNxFOD5UPFaeD65sQoAJz%2BY0N62CgAtaL\
  %2FBeT%2Bts8ji1MxsdD8ssY&X-Amz-Signature=7b6fcbc33685899102d1a0e0220ead4e6ef7\
  9d50ac275d50b24bae2ac6699b64&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466VVNZODNO%2F20250215%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250215T062951Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEBYaCXVzLXdlc3QtMiJGMEQCIAHDVViRURp4CRr33T6VTn9X9VDYHEN\
        JhdAdeEJWzSW1AiA5Q7HuvQFovW9BSmsR83Y7c%2BtOlTdMu1%2Fepd2tr%2B6qdSr%2FAw\
        g%2FEAAaDDYzNzQyMzE4MzgwNSIMm6RP4BVwmxn4PdYRKtwDFCcrQSxGv5uTZnSnnU6SCBd\
        J987yDcaEAVuE1exrh6Jnl%2BECxEVLm6WfBZhphAh9wZqJCohUvepTIhmTPPg9Q8DOJcn3\
        ADLfgl7L9W9q6Ie8rLQaykAfBo%2BoDRKSfRfhI8bC4Dso1U517AQrAIMb0FuUDJfY0elhC\
        KUlFJb7VMbRS8i7ifhFG4P%2Faeu9a60ht6N091NWLp2H86wgctIXbZOPXwc7CD7p9x8aNC\
        ryTOv%2Fah1a2haL1jC%2BKqLz%2BuLL5sK9VOWkEuKbSnv1RwPXud6q%2BaHjUtf71Tn4G\
        J143fCRDwj33YuTRHHC5zYIE9TztT27mRytkqW58sRjEE%2Fa98%2BXcb%2F6QchlotfYGK\
        %2BRsA7HgOLDQwR2IvImwtO%2FTKXXQpmdCf6Kxa5KA9fLMMTSia%2Bse9GoBQuX%2FipqT\
        U%2B%2BM3aSbmBHpLCY3X%2BrUU69esRGapUr6SYt38v088jWrl%2BolNdXDVyZWcdZarBO\
        QTQsLuBcIf1L2p5DOsZ4VWOn595w4M5KHkrf5UlkN0iTbKnb7NWJ4cy6WqrJXrqPCSxmmDV\
        qLzlFQ9tmNtTeoaFPl3FKcV2PSllJrzpbxRQJ0K73olfiuOmyndQMaCKpZ85sUV%2FAZDv7\
        ok%2Bua10hWdIwhM3AvQY6pgFafgwOjSZXTKNvdRNCBqdyYBb%2BJuvqcZGifimQJQvA%2F\
        gMgmOpkOedxg2SBXu6CKyD7EfZH1bSZU74eWVhWH0gU1kHbLoM6mkKpBViEmfvOTEEWbQgq\
        1OeXZ1BXxRL9JwrIGaxeByY1KQjtKZe86sV5Eond7WH2s5hOobF54MN2yxdZXI87j0mCxSo\
        a0IzwQiKIsqtdKRTklMWNVbRgY2DJKLbFr%2Bpg&X-Amz-Signature=76188b7bd9dfbcb\
        0c6ab15171c8c8e0dae462c879ae4dd760c6c17ca68d947b0&X-Amz-SignedHeaders=h\
        ost&x-id=GetObject"
      expiry_time: "2025-02-15T07:29:51.269Z"
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
UPDATE_TIME: "2025-02-15T06:31:21.975Z"
EXPIRY_TIME: "2025-02-15T07:31:13.723Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466W3XDD5T6%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T063114Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBYaCXVzLXdlc3QtMiJHMEUCIQC4%2BaCrgH6O5yGV7VvJfqjJfHiiTT%2F%2B2BmbZNXfxp%2F3zwIgZVeduf%2FUMOoXiGJ3LbpRkkT%2BmQlncCylWZOwHn6upkwq%2FwMIPhAAGgw2Mzc0MjMxODM4MDUiDFt966PnR0pu2Bj6HyrcAyAdJNEFWVCnl8XwBY2CkdAtDYKS2N4jDtuh9KoYF2waKcA4CVS8lsqUPc2Ee0GfKa3TAf7n1TDM84d4EMQ5cY%2FbmnoiUzGNVMoLsGykSrtY1MVg9GkZK4bmLaNofaM%2FOHkEEHpOCgJ9kFgZmWQT2u7JlUECzIdzkAi0c120q3duZGtoYhhOy2RLboxIr%2B4suentf7QqNhXtloBG1DF1HQl4X0asaGFTXSSTq4H0apL2WiF%2BUmt68A9DPVJiC6d%2BkQoIXjkkCazxXMWMxY%2FhpR6%2BgrNa%2BB74NSMNQwHsTeZhJILL5E06DtnfPzeSs7sMrA7OypzSG5nDO0%2F%2BFJafg%2BbdE%2Ftkpc4WL7SiJqYm0x0XxGRL6p75Q%2BAa90XH8LVBCfreCzQCsWH4JIDyJSNyDMDry8dwov9D%2FClV3mTxXTMoE9X0ql6uDw4nX%2BfgdODg5DQmcgqRyNTujjFVMTb5aOKmgsFy36Fm7elvBdw8jNnyKzu0IGOYXB2F0T4glBY%2BLK7sTi4xuV932ZKVla36ZKHSBzKnRYjopRxN14Fk5kQgNa%2BgRefcHR%2BNqgZGs9cvWEWAPfDFhmUENho9unxTt5XhznO7yqiRkPUhtxAzFaA22nqZngXTpU0v62dPMIPNwL0GOqUB79UJL9K88lg4rv9n5%2FKqHjcquej6sw2lG2SDzoNNfnNeBJYf9QbTfWq0GWD%2Fvp%2BCaRiqMhIp6A6x%2BVKzdmTn5oi9ABpFrSLtwvPn0zyejxeNoiHpr%2BLSP%2FglsxpM7OGGv%2F8rM1aP4b0%2BM%2BZNrW8C3G6KbSJDZatDzQQlbwrd3Vv%2FXybKZohdYHs40wAu6x%2FcfG7Khy4q%2FUfqWICe6MAKGJ4slUlJ&X-Amz-Signature=94cd07a342e9e91deb8d102673f1c93041ddf3b31fbdac78d03a3aa7bab9d16b&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466W3XDD5T6%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T063114Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBYaCXVzLXdlc3QtMiJHMEUCIQC4%2BaCrgH6O5yGV7VvJfqjJfHiiTT%2F%2B2BmbZNXfxp%2F3zwIgZVeduf%2FUMOoXiGJ3LbpRkkT%2BmQlncCylWZOwHn6upkwq%2FwMIPhAAGgw2Mzc0MjMxODM4MDUiDFt966PnR0pu2Bj6HyrcAyAdJNEFWVCnl8XwBY2CkdAtDYKS2N4jDtuh9KoYF2waKcA4CVS8lsqUPc2Ee0GfKa3TAf7n1TDM84d4EMQ5cY%2FbmnoiUzGNVMoLsGykSrtY1MVg9GkZK4bmLaNofaM%2FOHkEEHpOCgJ9kFgZmWQT2u7JlUECzIdzkAi0c120q3duZGtoYhhOy2RLboxIr%2B4suentf7QqNhXtloBG1DF1HQl4X0asaGFTXSSTq4H0apL2WiF%2BUmt68A9DPVJiC6d%2BkQoIXjkkCazxXMWMxY%2FhpR6%2BgrNa%2BB74NSMNQwHsTeZhJILL5E06DtnfPzeSs7sMrA7OypzSG5nDO0%2F%2BFJafg%2BbdE%2Ftkpc4WL7SiJqYm0x0XxGRL6p75Q%2BAa90XH8LVBCfreCzQCsWH4JIDyJSNyDMDry8dwov9D%2FClV3mTxXTMoE9X0ql6uDw4nX%2BfgdODg5DQmcgqRyNTujjFVMTb5aOKmgsFy36Fm7elvBdw8jNnyKzu0IGOYXB2F0T4glBY%2BLK7sTi4xuV932ZKVla36ZKHSBzKnRYjopRxN14Fk5kQgNa%2BgRefcHR%2BNqgZGs9cvWEWAPfDFhmUENho9unxTt5XhznO7yqiRkPUhtxAzFaA22nqZngXTpU0v62dPMIPNwL0GOqUB79UJL9K88lg4rv9n5%2FKqHjcquej6sw2lG2SDzoNNfnNeBJYf9QbTfWq0GWD%2Fvp%2BCaRiqMhIp6A6x%2BVKzdmTn5oi9ABpFrSLtwvPn0zyejxeNoiHpr%2BLSP%2FglsxpM7OGGv%2F8rM1aP4b0%2BM%2BZNrW8C3G6KbSJDZatDzQQlbwrd3Vv%2FXybKZohdYHs40wAu6x%2FcfG7Khy4q%2FUfqWICe6MAKGJ4slUlJ&X-Amz-Signature=91ed185a93cee840e64f5d32e89280eb97b43d90581e77887693f207a812e012&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466W3XDD5T6%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T063114Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBYaCXVzLXdlc3QtMiJHMEUCIQC4%2BaCrgH6O5yGV7VvJfqjJfHiiTT%2F%2B2BmbZNXfxp%2F3zwIgZVeduf%2FUMOoXiGJ3LbpRkkT%2BmQlncCylWZOwHn6upkwq%2FwMIPhAAGgw2Mzc0MjMxODM4MDUiDFt966PnR0pu2Bj6HyrcAyAdJNEFWVCnl8XwBY2CkdAtDYKS2N4jDtuh9KoYF2waKcA4CVS8lsqUPc2Ee0GfKa3TAf7n1TDM84d4EMQ5cY%2FbmnoiUzGNVMoLsGykSrtY1MVg9GkZK4bmLaNofaM%2FOHkEEHpOCgJ9kFgZmWQT2u7JlUECzIdzkAi0c120q3duZGtoYhhOy2RLboxIr%2B4suentf7QqNhXtloBG1DF1HQl4X0asaGFTXSSTq4H0apL2WiF%2BUmt68A9DPVJiC6d%2BkQoIXjkkCazxXMWMxY%2FhpR6%2BgrNa%2BB74NSMNQwHsTeZhJILL5E06DtnfPzeSs7sMrA7OypzSG5nDO0%2F%2BFJafg%2BbdE%2Ftkpc4WL7SiJqYm0x0XxGRL6p75Q%2BAa90XH8LVBCfreCzQCsWH4JIDyJSNyDMDry8dwov9D%2FClV3mTxXTMoE9X0ql6uDw4nX%2BfgdODg5DQmcgqRyNTujjFVMTb5aOKmgsFy36Fm7elvBdw8jNnyKzu0IGOYXB2F0T4glBY%2BLK7sTi4xuV932ZKVla36ZKHSBzKnRYjopRxN14Fk5kQgNa%2BgRefcHR%2BNqgZGs9cvWEWAPfDFhmUENho9unxTt5XhznO7yqiRkPUhtxAzFaA22nqZngXTpU0v62dPMIPNwL0GOqUB79UJL9K88lg4rv9n5%2FKqHjcquej6sw2lG2SDzoNNfnNeBJYf9QbTfWq0GWD%2Fvp%2BCaRiqMhIp6A6x%2BVKzdmTn5oi9ABpFrSLtwvPn0zyejxeNoiHpr%2BLSP%2FglsxpM7OGGv%2F8rM1aP4b0%2BM%2BZNrW8C3G6KbSJDZatDzQQlbwrd3Vv%2FXybKZohdYHs40wAu6x%2FcfG7Khy4q%2FUfqWICe6MAKGJ4slUlJ&X-Amz-Signature=a7049d11f1bb19c11a2a35b4fbf1e43fec66eafaafff6b65d0a252b1ee478b91&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466W3XDD5T6%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T063114Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBYaCXVzLXdlc3QtMiJHMEUCIQC4%2BaCrgH6O5yGV7VvJfqjJfHiiTT%2F%2B2BmbZNXfxp%2F3zwIgZVeduf%2FUMOoXiGJ3LbpRkkT%2BmQlncCylWZOwHn6upkwq%2FwMIPhAAGgw2Mzc0MjMxODM4MDUiDFt966PnR0pu2Bj6HyrcAyAdJNEFWVCnl8XwBY2CkdAtDYKS2N4jDtuh9KoYF2waKcA4CVS8lsqUPc2Ee0GfKa3TAf7n1TDM84d4EMQ5cY%2FbmnoiUzGNVMoLsGykSrtY1MVg9GkZK4bmLaNofaM%2FOHkEEHpOCgJ9kFgZmWQT2u7JlUECzIdzkAi0c120q3duZGtoYhhOy2RLboxIr%2B4suentf7QqNhXtloBG1DF1HQl4X0asaGFTXSSTq4H0apL2WiF%2BUmt68A9DPVJiC6d%2BkQoIXjkkCazxXMWMxY%2FhpR6%2BgrNa%2BB74NSMNQwHsTeZhJILL5E06DtnfPzeSs7sMrA7OypzSG5nDO0%2F%2BFJafg%2BbdE%2Ftkpc4WL7SiJqYm0x0XxGRL6p75Q%2BAa90XH8LVBCfreCzQCsWH4JIDyJSNyDMDry8dwov9D%2FClV3mTxXTMoE9X0ql6uDw4nX%2BfgdODg5DQmcgqRyNTujjFVMTb5aOKmgsFy36Fm7elvBdw8jNnyKzu0IGOYXB2F0T4glBY%2BLK7sTi4xuV932ZKVla36ZKHSBzKnRYjopRxN14Fk5kQgNa%2BgRefcHR%2BNqgZGs9cvWEWAPfDFhmUENho9unxTt5XhznO7yqiRkPUhtxAzFaA22nqZngXTpU0v62dPMIPNwL0GOqUB79UJL9K88lg4rv9n5%2FKqHjcquej6sw2lG2SDzoNNfnNeBJYf9QbTfWq0GWD%2Fvp%2BCaRiqMhIp6A6x%2BVKzdmTn5oi9ABpFrSLtwvPn0zyejxeNoiHpr%2BLSP%2FglsxpM7OGGv%2F8rM1aP4b0%2BM%2BZNrW8C3G6KbSJDZatDzQQlbwrd3Vv%2FXybKZohdYHs40wAu6x%2FcfG7Khy4q%2FUfqWICe6MAKGJ4slUlJ&X-Amz-Signature=db9b41114de92de39977ef7a72c322a372e51b2a92756efe3ffe09f610e35102&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466W3XDD5T6%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T063114Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBYaCXVzLXdlc3QtMiJHMEUCIQC4%2BaCrgH6O5yGV7VvJfqjJfHiiTT%2F%2B2BmbZNXfxp%2F3zwIgZVeduf%2FUMOoXiGJ3LbpRkkT%2BmQlncCylWZOwHn6upkwq%2FwMIPhAAGgw2Mzc0MjMxODM4MDUiDFt966PnR0pu2Bj6HyrcAyAdJNEFWVCnl8XwBY2CkdAtDYKS2N4jDtuh9KoYF2waKcA4CVS8lsqUPc2Ee0GfKa3TAf7n1TDM84d4EMQ5cY%2FbmnoiUzGNVMoLsGykSrtY1MVg9GkZK4bmLaNofaM%2FOHkEEHpOCgJ9kFgZmWQT2u7JlUECzIdzkAi0c120q3duZGtoYhhOy2RLboxIr%2B4suentf7QqNhXtloBG1DF1HQl4X0asaGFTXSSTq4H0apL2WiF%2BUmt68A9DPVJiC6d%2BkQoIXjkkCazxXMWMxY%2FhpR6%2BgrNa%2BB74NSMNQwHsTeZhJILL5E06DtnfPzeSs7sMrA7OypzSG5nDO0%2F%2BFJafg%2BbdE%2Ftkpc4WL7SiJqYm0x0XxGRL6p75Q%2BAa90XH8LVBCfreCzQCsWH4JIDyJSNyDMDry8dwov9D%2FClV3mTxXTMoE9X0ql6uDw4nX%2BfgdODg5DQmcgqRyNTujjFVMTb5aOKmgsFy36Fm7elvBdw8jNnyKzu0IGOYXB2F0T4glBY%2BLK7sTi4xuV932ZKVla36ZKHSBzKnRYjopRxN14Fk5kQgNa%2BgRefcHR%2BNqgZGs9cvWEWAPfDFhmUENho9unxTt5XhznO7yqiRkPUhtxAzFaA22nqZngXTpU0v62dPMIPNwL0GOqUB79UJL9K88lg4rv9n5%2FKqHjcquej6sw2lG2SDzoNNfnNeBJYf9QbTfWq0GWD%2Fvp%2BCaRiqMhIp6A6x%2BVKzdmTn5oi9ABpFrSLtwvPn0zyejxeNoiHpr%2BLSP%2FglsxpM7OGGv%2F8rM1aP4b0%2BM%2BZNrW8C3G6KbSJDZatDzQQlbwrd3Vv%2FXybKZohdYHs40wAu6x%2FcfG7Khy4q%2FUfqWICe6MAKGJ4slUlJ&X-Amz-Signature=9c775a127c2884e717b640c5d5540bee89b5ff8d9979d9fcd611f3708c957809&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666KZ42JOC%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T063114Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBcaCXVzLXdlc3QtMiJHMEUCIQCG09GElHTE1sKJpvS18hDqFFz%2FimA74At4Wyl%2F%2B1r2ngIgJuXjFW7SVk1YATLb5ak9SWkxx8b22dTXP%2B7tupX6FDIq%2FwMIQBAAGgw2Mzc0MjMxODM4MDUiDKL3xORNV3epCz7oCyrcA2kIMSOWIfTna4ZX45KePK9DDu0ZdFLf8ivP2G2zINVuN2iyQO%2FuTRtfSa4JsTYDzbPLEbqL48nAmNbawxXSZVa%2FyucJXk6P84HHHPL5s7hZJlXRKGPPW4t6sDttOtG1Z2np4iGfGMh75j61oE6%2FLppqG2tEZbSyV4eKmKmV8wLNRWXY%2ByOOopB3QDepC58si6RVlhEOw9OGbFXvW118J3ACV6YBR37YoOKqweB6Zt3C2Z1Lqasr5Och6Q4XlTzsrWMeW0BjLVYfXv7jTwKT6gq7NOK0QvXInSyk2o9D3JCKg8HRWC8%2BxY8P0ZjceFrHkUk8hbO%2BODwXHjSzKx%2BQ0P4ecuUX%2BQv0A9OsbfxObom56Cw0LYWiSWuvdNZdqJBvI36TZ15DtJKtLxp55LNwN7r9%2B4hHoWzA%2F7z1NJ2q5ru6%2B4pUa5yXPp03s%2FENnclDsp2PBN0%2FQZWbP5CGGBC8tTNmu%2B0pacYQXH4IFl92FCyerVtenokEWrtSCYFQuEmANyff9Fi8N3WqHVhZyV%2F%2Fcku7vt67uxIHcaEkImzuwabPYpgywZf7ZL3KIactOXRUxDoY1p%2BvjrrQu9z8%2BxcWndq%2BkVxk4EEe5Rb6lnTVmPytLC8V4aA2PF8YEoGJMIbpwL0GOqUBwut1JRDJp8a1GthzPTBh%2B471NBWWvX25QKmyV7%2BtshIkzKySMqvxhWMN9I0elq5Nt4YIUP2Tl3Aj0Y%2F5%2B27XJa73F96YMY7iV8Z6vVZOYaUsbfeloTkzRe0fB78YUttoOkYRU82NObP8G2f3xV7xRLqXTsEwaqPI99H4l4WKDRd4Uif9wHpmgb17%2BlwHbDsEzOoffqaAgny%2Bjj0R16bdxXjj4nb2&X-Amz-Signature=c6cd7a1a0f1b27710e9093c06c5c99ee6952acba0fca8168a6dfef3c8981f36a&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662HOW2IEW%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T063115Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBYaCXVzLXdlc3QtMiJHMEUCIBDHRdBQHR%2FJsraho%2BBziRUv1Jh6j22wyU3BwYwkAtG%2BAiEAiHFZxmDMPQMAb6y1iIUFyBA%2FXarmGK2V%2Ba%2Fkf%2BcKDrsq%2FwMIPhAAGgw2Mzc0MjMxODM4MDUiDHTqdtDiDVUrMAoVkyrcA1PNQzO6%2BOr7Wy75pWsiofYtrq4E%2F%2FB3aqi7RwSanNNGkdfOUluLphVtbeXgahd8bee%2FuKBqo9u%2Fmi1hRcsfvGDeHtVqOWuRerJIbIKNiyRMjUCmYt1RFk4gPa81QwS%2BfNwBGXdCVM72bsOiDFPwbPsa4s%2FNstqF39FnGgDKlhnigCJLx3OM9aucAYz1m71VHC2MzelMrovh2mb0n1KY%2F3w67eI%2F6bQLt4t8F8BGkfQ8HtskmLMYkVpjRzEJYdzepArx%2BkEjLI%2F2QKF7aDxfXbMaqjr7o3WsK8MD5T9LqENyVAWXjNN849nsU5tRBsdvkqkeq6KjLBsO5F41cIFLKILLXZRtBcvOBxqCYGm4OsBLPMsKW0AnpPEsmX9qxVG8XgXr6fgjMGj%2BvRn5b4rGextHlag1UUMwWTpk55Ok3LefsjDHRtK0bCTwyNMkpfr69OKF4cqlUl4vyVj77wC6Jd3op3%2F3RIID8WCYE1Nq9nC5bKjPp4uQ41xMYutxFIPMwf0iurPx6356oEA7hDtHzBfKlnltkKuLkl3QxTs6VIxJlio7QA2g4zGBIJQZFQzmVaywdTUVTPoe%2FL6MrSObUVoRjLhGnRxy8WVBtc212IVaPrm4FOVjOq1UvClJMJnNwL0GOqUBY1vagUcocTqjAbJcnjCVR5HQsYlIkJrWHgPvNXrd5TOpkJH0hqozmw6Uww4W1C7kRk1tp8f1dyAtgFOXPG31yb5CnnML8BEaVo5RTjod9CK2qBHeNAod2k0q6feAuRkbHp4PhUrnO%2Bp1ESxIg6oe3G1QarMrl2ycK8JzFkJyzk0d%2FEMrZfQxLy3yckhpj4U02RMfddcsMOvlhLBU3lWkn9AMeWuU&X-Amz-Signature=30868c50724d45a30257e9cf5dc73c2aa9825215afc4a76e633b3d7a96b74e85&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466W3XDD5T6%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T063114Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBYaCXVzLXdlc3QtMiJHMEUCIQC4%2BaCrgH6O5yGV7VvJfqjJfHiiTT%2F%2B2BmbZNXfxp%2F3zwIgZVeduf%2FUMOoXiGJ3LbpRkkT%2BmQlncCylWZOwHn6upkwq%2FwMIPhAAGgw2Mzc0MjMxODM4MDUiDFt966PnR0pu2Bj6HyrcAyAdJNEFWVCnl8XwBY2CkdAtDYKS2N4jDtuh9KoYF2waKcA4CVS8lsqUPc2Ee0GfKa3TAf7n1TDM84d4EMQ5cY%2FbmnoiUzGNVMoLsGykSrtY1MVg9GkZK4bmLaNofaM%2FOHkEEHpOCgJ9kFgZmWQT2u7JlUECzIdzkAi0c120q3duZGtoYhhOy2RLboxIr%2B4suentf7QqNhXtloBG1DF1HQl4X0asaGFTXSSTq4H0apL2WiF%2BUmt68A9DPVJiC6d%2BkQoIXjkkCazxXMWMxY%2FhpR6%2BgrNa%2BB74NSMNQwHsTeZhJILL5E06DtnfPzeSs7sMrA7OypzSG5nDO0%2F%2BFJafg%2BbdE%2Ftkpc4WL7SiJqYm0x0XxGRL6p75Q%2BAa90XH8LVBCfreCzQCsWH4JIDyJSNyDMDry8dwov9D%2FClV3mTxXTMoE9X0ql6uDw4nX%2BfgdODg5DQmcgqRyNTujjFVMTb5aOKmgsFy36Fm7elvBdw8jNnyKzu0IGOYXB2F0T4glBY%2BLK7sTi4xuV932ZKVla36ZKHSBzKnRYjopRxN14Fk5kQgNa%2BgRefcHR%2BNqgZGs9cvWEWAPfDFhmUENho9unxTt5XhznO7yqiRkPUhtxAzFaA22nqZngXTpU0v62dPMIPNwL0GOqUB79UJL9K88lg4rv9n5%2FKqHjcquej6sw2lG2SDzoNNfnNeBJYf9QbTfWq0GWD%2Fvp%2BCaRiqMhIp6A6x%2BVKzdmTn5oi9ABpFrSLtwvPn0zyejxeNoiHpr%2BLSP%2FglsxpM7OGGv%2F8rM1aP4b0%2BM%2BZNrW8C3G6KbSJDZatDzQQlbwrd3Vv%2FXybKZohdYHs40wAu6x%2FcfG7Khy4q%2FUfqWICe6MAKGJ4slUlJ&X-Amz-Signature=6b310fb2bdb45c60349d69b1c2a961c924f84a927fbe577f772146c1c9714c13&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466W3XDD5T6%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T063114Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBYaCXVzLXdlc3QtMiJHMEUCIQC4%2BaCrgH6O5yGV7VvJfqjJfHiiTT%2F%2B2BmbZNXfxp%2F3zwIgZVeduf%2FUMOoXiGJ3LbpRkkT%2BmQlncCylWZOwHn6upkwq%2FwMIPhAAGgw2Mzc0MjMxODM4MDUiDFt966PnR0pu2Bj6HyrcAyAdJNEFWVCnl8XwBY2CkdAtDYKS2N4jDtuh9KoYF2waKcA4CVS8lsqUPc2Ee0GfKa3TAf7n1TDM84d4EMQ5cY%2FbmnoiUzGNVMoLsGykSrtY1MVg9GkZK4bmLaNofaM%2FOHkEEHpOCgJ9kFgZmWQT2u7JlUECzIdzkAi0c120q3duZGtoYhhOy2RLboxIr%2B4suentf7QqNhXtloBG1DF1HQl4X0asaGFTXSSTq4H0apL2WiF%2BUmt68A9DPVJiC6d%2BkQoIXjkkCazxXMWMxY%2FhpR6%2BgrNa%2BB74NSMNQwHsTeZhJILL5E06DtnfPzeSs7sMrA7OypzSG5nDO0%2F%2BFJafg%2BbdE%2Ftkpc4WL7SiJqYm0x0XxGRL6p75Q%2BAa90XH8LVBCfreCzQCsWH4JIDyJSNyDMDry8dwov9D%2FClV3mTxXTMoE9X0ql6uDw4nX%2BfgdODg5DQmcgqRyNTujjFVMTb5aOKmgsFy36Fm7elvBdw8jNnyKzu0IGOYXB2F0T4glBY%2BLK7sTi4xuV932ZKVla36ZKHSBzKnRYjopRxN14Fk5kQgNa%2BgRefcHR%2BNqgZGs9cvWEWAPfDFhmUENho9unxTt5XhznO7yqiRkPUhtxAzFaA22nqZngXTpU0v62dPMIPNwL0GOqUB79UJL9K88lg4rv9n5%2FKqHjcquej6sw2lG2SDzoNNfnNeBJYf9QbTfWq0GWD%2Fvp%2BCaRiqMhIp6A6x%2BVKzdmTn5oi9ABpFrSLtwvPn0zyejxeNoiHpr%2BLSP%2FglsxpM7OGGv%2F8rM1aP4b0%2BM%2BZNrW8C3G6KbSJDZatDzQQlbwrd3Vv%2FXybKZohdYHs40wAu6x%2FcfG7Khy4q%2FUfqWICe6MAKGJ4slUlJ&X-Amz-Signature=4ec827813e5642d028728922542ff1034e203805d9e1f0bce19c4844298a2919&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466W3XDD5T6%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T063114Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBYaCXVzLXdlc3QtMiJHMEUCIQC4%2BaCrgH6O5yGV7VvJfqjJfHiiTT%2F%2B2BmbZNXfxp%2F3zwIgZVeduf%2FUMOoXiGJ3LbpRkkT%2BmQlncCylWZOwHn6upkwq%2FwMIPhAAGgw2Mzc0MjMxODM4MDUiDFt966PnR0pu2Bj6HyrcAyAdJNEFWVCnl8XwBY2CkdAtDYKS2N4jDtuh9KoYF2waKcA4CVS8lsqUPc2Ee0GfKa3TAf7n1TDM84d4EMQ5cY%2FbmnoiUzGNVMoLsGykSrtY1MVg9GkZK4bmLaNofaM%2FOHkEEHpOCgJ9kFgZmWQT2u7JlUECzIdzkAi0c120q3duZGtoYhhOy2RLboxIr%2B4suentf7QqNhXtloBG1DF1HQl4X0asaGFTXSSTq4H0apL2WiF%2BUmt68A9DPVJiC6d%2BkQoIXjkkCazxXMWMxY%2FhpR6%2BgrNa%2BB74NSMNQwHsTeZhJILL5E06DtnfPzeSs7sMrA7OypzSG5nDO0%2F%2BFJafg%2BbdE%2Ftkpc4WL7SiJqYm0x0XxGRL6p75Q%2BAa90XH8LVBCfreCzQCsWH4JIDyJSNyDMDry8dwov9D%2FClV3mTxXTMoE9X0ql6uDw4nX%2BfgdODg5DQmcgqRyNTujjFVMTb5aOKmgsFy36Fm7elvBdw8jNnyKzu0IGOYXB2F0T4glBY%2BLK7sTi4xuV932ZKVla36ZKHSBzKnRYjopRxN14Fk5kQgNa%2BgRefcHR%2BNqgZGs9cvWEWAPfDFhmUENho9unxTt5XhznO7yqiRkPUhtxAzFaA22nqZngXTpU0v62dPMIPNwL0GOqUB79UJL9K88lg4rv9n5%2FKqHjcquej6sw2lG2SDzoNNfnNeBJYf9QbTfWq0GWD%2Fvp%2BCaRiqMhIp6A6x%2BVKzdmTn5oi9ABpFrSLtwvPn0zyejxeNoiHpr%2BLSP%2FglsxpM7OGGv%2F8rM1aP4b0%2BM%2BZNrW8C3G6KbSJDZatDzQQlbwrd3Vv%2FXybKZohdYHs40wAu6x%2FcfG7Khy4q%2FUfqWICe6MAKGJ4slUlJ&X-Amz-Signature=d27f30ed146b5e9cdba27f2b43f48b01e8a3cb60139d2e936f6683b36eff5403&X-Amz-SignedHeaders=host&x-id=GetObject)


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

