---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4666AI5N4XN%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250221T025449Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEKP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEX%2B%2BymVyl%2BA4\
  dK4JE3DaBpu5fqdkHz%2BxOQBy42UPqy%2FAiBVHzzH21drOWBy3sDmiDkUgfl5z%2B%2FE94VvnV\
  CXcwoylCqIBAjM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMKJsH%2B\
  rmPCd44V6y4KtwDQC0HEnBYy9RYRS5CeFeh5ZwXj3uWGTEufX41eN%2BG9ZnlhMldVh1yF%2FbTtl\
  56TBFHPTAKpQfo8dfRkykgN2ciMt4Vo%2F26qkVfogOD8P2cYqON9Pa7v%2BZxQS9KiAckRqLzlY%\
  2BAcjr6Db3%2BMb4YPCqjFt9LppNEvqk5ybKpD67UitbxrmQZlx35hmjyuYoQFmVjUY3rjpiKMEi7\
  4lAyvz%2BKUvCgcnh5LeGQdKbUPPO0HaZcWZJgtLPWhEQYPC%2F18vTYr8xMG%2FIDqpmDJLa9RYb\
  IM9QCwkHgX1Ccl2qnJJkpGdCprS63ZAE8xGUw%2BO54aHSpOMcwosnKglHfEEIPdWErmhrg0Ch%2B\
  mBSy3%2BKgHrbAsPkoS0JQg59MIvon3tkQEwKQhmI6hvqGMLVD10wIMqu7gv31KCMVhpxvHkdcs9j\
  SexB4wovor4ui7768gCJaya3upHfEeiMaa8ad1qXmkIe2YAygD%2BE2k17ylPpz9kKCbjBdC8sXHd\
  w9QrlNTop6WOOA1G3QVZn6vzyFrlKUJXpV4xC1QmIlj37Xu75%2FLDcZZnfffZdM4oCqsuEQY417z\
  96%2BKFFTM0ZJvUI9fAwUPhyiOtatrTFexXHui0xRVrA%2BidR3iqogVHV45fCaRf0wgsvfvQY6pg\
  GgE4fIjethr7uYMH%2BU%2FhKlAO%2BNvNVDzkVnOlCR9EP4mjEO9GbnSta0%2FUTAK97v0tzWZrG\
  0pMjCxQBbOEyy6Ao%2BT5PH1ZEU00TqJZxIZhNLB83fymtIrw4bR%2FopXMrjjkjXwMfoGxpp4ELL\
  MaQwCm0oi26Rlqp5aPHljREaie7Dpfqy%2FXP%2FURC7FWczAHDRh2j1SyJq8Lxiny8D9EiBzt43c\
  ODDl9XP&X-Amz-Signature=5f93bffef8ce1fcf8f663eb32a1162f557fad5f536cb261ffafe0\
  3be72f73e78&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466QZQX4LG5%2F20250221%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250221T025312Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEKP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIQCylHjaLC1U%2BpYh1syxR8q4sgdRhZkTa0bQRLrQQTFhugIger3BNc54qM%2B0vVa48j\
        cbDu%2FM7OjoR50FyBxvsTl2YQ0qiAQIzP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw\
        2Mzc0MjMxODM4MDUiDFT1BqGBtQpCvCVvNCrcA8%2FIdGNeMzFR7WAvYfDZsHMboYfDGwl9\
        1eO3YgClcfg9yjTUFfgZdmNjIKclppYnTQByHA6Wt4LJ1y%2B74hy8Md%2FWf7%2FQd5MV2\
        RzGogFheKBTFcaSbfT%2BTRoocE04zv7NOc6QWxB7i82ArPZwB489%2FsHgsDs%2B9C3%2B\
        QApLOqRHkCg2VlhJdQmEXkIGB3g09%2FQvIILVMduvw0LuSXayxmvrayVsRU4pu2YSFS7aS\
        27qy3TnsX%2Bj%2Bn7FZrgOpDtl2hCIp4JYjcqK%2FNuQthjZGB0JmGNSxgL5wSSdWPOjke\
        X%2B1rtENfE%2F2vXBU8C1Gw0ew6JmGFgPm8KnjIxC%2BKNtt%2FgfYXFiY8zuoQZ3gCnSt\
        4VEVzRvX0bJF%2F9wb2r04g8Wxfza3wrcuFio5loE7%2FYfpO6SbuqTLFu7S3fz45zEpo3G\
        zZB7cJBQSLbJ0uovKsEjkKRto9HGFtV8P6CpKWmYJoxY0vd3As0EXfEp1TFbaZkV%2BWHfE\
        uw3f%2BmC%2Fl38R8%2BfsUBLvYYPhHM%2BdJIfraBS83R63Yo70fjnm3Zw9IeZSjxTuhDx\
        ONdoTFFSUBy%2FVPwo7uqbM7SHf%2F0g66hUaN1Ez0PQg%2B2NG%2BJGxoh%2FLHeMbabAe\
        KvLyoKmx2PPLjItmxEbMPbK370GOqUBv6I%2BRKPyQzQM8Z%2FdWiL4mTRQbRvOjUpxJVVO\
        XwPk9Olx18nkMAVL%2BcHtRoHKQAszD%2BVW4sVjiGhpLLUYx6tNd2K14PwCtFsaYEwBmRe\
        zcAEGXwA2AIq2xfJ7FpWpIq3H%2Fl09%2Fn17Bvenymfp0zCH33ziktakMDg4EwBluuA2on\
        0u%2Bf6H2TheO4xQMcJGIZLxhad3wS%2Fcd1OLCSp0RZiF9Djj01xU&X-Amz-Signature=\
        b996e7917eee29418bc58336a019ae4b02c75b900f285a96fc1ee3b99cd6a485&X-Amz-\
        SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-21T03:53:12.183Z"
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
UPDATE_TIME: "2025-02-21T02:54:54.245Z"
EXPIRY_TIME: "2025-02-21T03:54:47.107Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662JDIJWWJ%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T025447Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIHM0UDqZC%2Fc%2FZqa1SbxHBlsEvYdW%2FwBfByxf%2FIf0veIOAiBf8VUPiEph97iBQL9UvpipAlKrkODSQ88esTDTNyT7bCqIBAjM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMf8uxg4Gvn2Zqon5QKtwD%2FxY%2BNEIP5GdVkErLX7Gn5aE8fSWjKYzdBSMy8TOEslxwX9iTMVFSP0DPqfhOKYkWbAGNW77VMbacOC%2Bom9kqnK0wy3%2BWD2%2FfqbpB%2Bw51XpLOFojRStgbdCdO%2BoQpWA8iSlVXTk0eqhZ7N26mZfOnz62ErXRmWdIuzy5ALijNFWbJpdPFwBqv03GWhltNHHh7YRyuPJoNa2rhlyS1VbGj9ESVd8X878SzvcXKKDO8hicgYx8WCFKfUybG2UPSyvCaCj63Ue1ESubBZufTyY4n88iw9WTWQmrTIiu5uKxnbhVXIzONSlgmv03erf1VkyLMUAW1tkVE2wkBrYFlO%2BG0ZpkwY2dIm%2BYUyvGuqCU%2Bzy5Z%2FUT84PZRXAoKjTsoDBgMQigPGT0ggRZRDC9dMRnbsLDwjpNpo2%2F6uzuE2WwjlZFlT%2FrFeUdmkLf9Qr9BHXUbvAfikEGkX1ndJvDWz2Uj3JyQoUVqo53kVf1Uty%2B%2FnptvdUnQw9SF9W0kBOfaPtOHBDVhCgG87D%2FTjTkIlakOSIw6EpdUs%2Fvuk4x8kYyqOYs2nw29bKUkplY%2BydNy%2B6g7uAedeoePbefbJndoAQ%2FfchrhrHGQ3gvOvbLJr6u0kv58f89%2FDpFGei6T2Qcw2MrfvQY6pgEWEwXIcykwAVy3saYAsyxAbuqGhctF5Pxx61Nx4V8BmTPAb4FTz1ko6Dj5YHxhh2xddAlMVdS7ytbWPGsFeA4y0H8WBI70o5n0zUaSM1u%2BmMxsq0hEmlZUOYa5ZwQ53Jjwk2W%2B3NUTfvmDq%2B%2BQJSRH4REyKCp76Et5g%2BhoFCzLat0veG4f0HUnOo9Rgg5dhRD0NmjTct9kPTkjiyOPC%2B7u5dmnk5nL&X-Amz-Signature=ab81127fab91d0aa278fb9e06911afb5abf53d224bbb91a738bbe28f123ff3d3&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662JDIJWWJ%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T025447Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIHM0UDqZC%2Fc%2FZqa1SbxHBlsEvYdW%2FwBfByxf%2FIf0veIOAiBf8VUPiEph97iBQL9UvpipAlKrkODSQ88esTDTNyT7bCqIBAjM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMf8uxg4Gvn2Zqon5QKtwD%2FxY%2BNEIP5GdVkErLX7Gn5aE8fSWjKYzdBSMy8TOEslxwX9iTMVFSP0DPqfhOKYkWbAGNW77VMbacOC%2Bom9kqnK0wy3%2BWD2%2FfqbpB%2Bw51XpLOFojRStgbdCdO%2BoQpWA8iSlVXTk0eqhZ7N26mZfOnz62ErXRmWdIuzy5ALijNFWbJpdPFwBqv03GWhltNHHh7YRyuPJoNa2rhlyS1VbGj9ESVd8X878SzvcXKKDO8hicgYx8WCFKfUybG2UPSyvCaCj63Ue1ESubBZufTyY4n88iw9WTWQmrTIiu5uKxnbhVXIzONSlgmv03erf1VkyLMUAW1tkVE2wkBrYFlO%2BG0ZpkwY2dIm%2BYUyvGuqCU%2Bzy5Z%2FUT84PZRXAoKjTsoDBgMQigPGT0ggRZRDC9dMRnbsLDwjpNpo2%2F6uzuE2WwjlZFlT%2FrFeUdmkLf9Qr9BHXUbvAfikEGkX1ndJvDWz2Uj3JyQoUVqo53kVf1Uty%2B%2FnptvdUnQw9SF9W0kBOfaPtOHBDVhCgG87D%2FTjTkIlakOSIw6EpdUs%2Fvuk4x8kYyqOYs2nw29bKUkplY%2BydNy%2B6g7uAedeoePbefbJndoAQ%2FfchrhrHGQ3gvOvbLJr6u0kv58f89%2FDpFGei6T2Qcw2MrfvQY6pgEWEwXIcykwAVy3saYAsyxAbuqGhctF5Pxx61Nx4V8BmTPAb4FTz1ko6Dj5YHxhh2xddAlMVdS7ytbWPGsFeA4y0H8WBI70o5n0zUaSM1u%2BmMxsq0hEmlZUOYa5ZwQ53Jjwk2W%2B3NUTfvmDq%2B%2BQJSRH4REyKCp76Et5g%2BhoFCzLat0veG4f0HUnOo9Rgg5dhRD0NmjTct9kPTkjiyOPC%2B7u5dmnk5nL&X-Amz-Signature=45328e8057b50a6ed418f0c5cf8cda7ccb35ccb182c067e44383043b53ab4543&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662JDIJWWJ%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T025447Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIHM0UDqZC%2Fc%2FZqa1SbxHBlsEvYdW%2FwBfByxf%2FIf0veIOAiBf8VUPiEph97iBQL9UvpipAlKrkODSQ88esTDTNyT7bCqIBAjM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMf8uxg4Gvn2Zqon5QKtwD%2FxY%2BNEIP5GdVkErLX7Gn5aE8fSWjKYzdBSMy8TOEslxwX9iTMVFSP0DPqfhOKYkWbAGNW77VMbacOC%2Bom9kqnK0wy3%2BWD2%2FfqbpB%2Bw51XpLOFojRStgbdCdO%2BoQpWA8iSlVXTk0eqhZ7N26mZfOnz62ErXRmWdIuzy5ALijNFWbJpdPFwBqv03GWhltNHHh7YRyuPJoNa2rhlyS1VbGj9ESVd8X878SzvcXKKDO8hicgYx8WCFKfUybG2UPSyvCaCj63Ue1ESubBZufTyY4n88iw9WTWQmrTIiu5uKxnbhVXIzONSlgmv03erf1VkyLMUAW1tkVE2wkBrYFlO%2BG0ZpkwY2dIm%2BYUyvGuqCU%2Bzy5Z%2FUT84PZRXAoKjTsoDBgMQigPGT0ggRZRDC9dMRnbsLDwjpNpo2%2F6uzuE2WwjlZFlT%2FrFeUdmkLf9Qr9BHXUbvAfikEGkX1ndJvDWz2Uj3JyQoUVqo53kVf1Uty%2B%2FnptvdUnQw9SF9W0kBOfaPtOHBDVhCgG87D%2FTjTkIlakOSIw6EpdUs%2Fvuk4x8kYyqOYs2nw29bKUkplY%2BydNy%2B6g7uAedeoePbefbJndoAQ%2FfchrhrHGQ3gvOvbLJr6u0kv58f89%2FDpFGei6T2Qcw2MrfvQY6pgEWEwXIcykwAVy3saYAsyxAbuqGhctF5Pxx61Nx4V8BmTPAb4FTz1ko6Dj5YHxhh2xddAlMVdS7ytbWPGsFeA4y0H8WBI70o5n0zUaSM1u%2BmMxsq0hEmlZUOYa5ZwQ53Jjwk2W%2B3NUTfvmDq%2B%2BQJSRH4REyKCp76Et5g%2BhoFCzLat0veG4f0HUnOo9Rgg5dhRD0NmjTct9kPTkjiyOPC%2B7u5dmnk5nL&X-Amz-Signature=dd27b1545d19bbfa3217b0654ee4a2bfddfb48e715f1ae118ba811019e254c9b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662JDIJWWJ%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T025447Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIHM0UDqZC%2Fc%2FZqa1SbxHBlsEvYdW%2FwBfByxf%2FIf0veIOAiBf8VUPiEph97iBQL9UvpipAlKrkODSQ88esTDTNyT7bCqIBAjM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMf8uxg4Gvn2Zqon5QKtwD%2FxY%2BNEIP5GdVkErLX7Gn5aE8fSWjKYzdBSMy8TOEslxwX9iTMVFSP0DPqfhOKYkWbAGNW77VMbacOC%2Bom9kqnK0wy3%2BWD2%2FfqbpB%2Bw51XpLOFojRStgbdCdO%2BoQpWA8iSlVXTk0eqhZ7N26mZfOnz62ErXRmWdIuzy5ALijNFWbJpdPFwBqv03GWhltNHHh7YRyuPJoNa2rhlyS1VbGj9ESVd8X878SzvcXKKDO8hicgYx8WCFKfUybG2UPSyvCaCj63Ue1ESubBZufTyY4n88iw9WTWQmrTIiu5uKxnbhVXIzONSlgmv03erf1VkyLMUAW1tkVE2wkBrYFlO%2BG0ZpkwY2dIm%2BYUyvGuqCU%2Bzy5Z%2FUT84PZRXAoKjTsoDBgMQigPGT0ggRZRDC9dMRnbsLDwjpNpo2%2F6uzuE2WwjlZFlT%2FrFeUdmkLf9Qr9BHXUbvAfikEGkX1ndJvDWz2Uj3JyQoUVqo53kVf1Uty%2B%2FnptvdUnQw9SF9W0kBOfaPtOHBDVhCgG87D%2FTjTkIlakOSIw6EpdUs%2Fvuk4x8kYyqOYs2nw29bKUkplY%2BydNy%2B6g7uAedeoePbefbJndoAQ%2FfchrhrHGQ3gvOvbLJr6u0kv58f89%2FDpFGei6T2Qcw2MrfvQY6pgEWEwXIcykwAVy3saYAsyxAbuqGhctF5Pxx61Nx4V8BmTPAb4FTz1ko6Dj5YHxhh2xddAlMVdS7ytbWPGsFeA4y0H8WBI70o5n0zUaSM1u%2BmMxsq0hEmlZUOYa5ZwQ53Jjwk2W%2B3NUTfvmDq%2B%2BQJSRH4REyKCp76Et5g%2BhoFCzLat0veG4f0HUnOo9Rgg5dhRD0NmjTct9kPTkjiyOPC%2B7u5dmnk5nL&X-Amz-Signature=fba46da9ef4768db729e239ca9123d816c05727379b95e249aeca8c6e919008c&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662JDIJWWJ%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T025447Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIHM0UDqZC%2Fc%2FZqa1SbxHBlsEvYdW%2FwBfByxf%2FIf0veIOAiBf8VUPiEph97iBQL9UvpipAlKrkODSQ88esTDTNyT7bCqIBAjM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMf8uxg4Gvn2Zqon5QKtwD%2FxY%2BNEIP5GdVkErLX7Gn5aE8fSWjKYzdBSMy8TOEslxwX9iTMVFSP0DPqfhOKYkWbAGNW77VMbacOC%2Bom9kqnK0wy3%2BWD2%2FfqbpB%2Bw51XpLOFojRStgbdCdO%2BoQpWA8iSlVXTk0eqhZ7N26mZfOnz62ErXRmWdIuzy5ALijNFWbJpdPFwBqv03GWhltNHHh7YRyuPJoNa2rhlyS1VbGj9ESVd8X878SzvcXKKDO8hicgYx8WCFKfUybG2UPSyvCaCj63Ue1ESubBZufTyY4n88iw9WTWQmrTIiu5uKxnbhVXIzONSlgmv03erf1VkyLMUAW1tkVE2wkBrYFlO%2BG0ZpkwY2dIm%2BYUyvGuqCU%2Bzy5Z%2FUT84PZRXAoKjTsoDBgMQigPGT0ggRZRDC9dMRnbsLDwjpNpo2%2F6uzuE2WwjlZFlT%2FrFeUdmkLf9Qr9BHXUbvAfikEGkX1ndJvDWz2Uj3JyQoUVqo53kVf1Uty%2B%2FnptvdUnQw9SF9W0kBOfaPtOHBDVhCgG87D%2FTjTkIlakOSIw6EpdUs%2Fvuk4x8kYyqOYs2nw29bKUkplY%2BydNy%2B6g7uAedeoePbefbJndoAQ%2FfchrhrHGQ3gvOvbLJr6u0kv58f89%2FDpFGei6T2Qcw2MrfvQY6pgEWEwXIcykwAVy3saYAsyxAbuqGhctF5Pxx61Nx4V8BmTPAb4FTz1ko6Dj5YHxhh2xddAlMVdS7ytbWPGsFeA4y0H8WBI70o5n0zUaSM1u%2BmMxsq0hEmlZUOYa5ZwQ53Jjwk2W%2B3NUTfvmDq%2B%2BQJSRH4REyKCp76Et5g%2BhoFCzLat0veG4f0HUnOo9Rgg5dhRD0NmjTct9kPTkjiyOPC%2B7u5dmnk5nL&X-Amz-Signature=0459bfa35046ea10d302317ce3cee6a81fa4e6b5a06da38a7da49b73d73831ae&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WSU2SKJD%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T025447Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCeHEA2ntkkz8VELkY%2BA89lj97VBEPldFpgykvKQAA0RQIhAOpUTzvWqYZW%2BOWmnPAyQnpUll0kGBILW5M%2BqDP%2B3SwiKogECMz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzGmTs2MDl8iwrXoowq3APrlca426PvVfSdu1mdLRy2KEdY0wVoDyOViklxkhxb5%2BwPIbDaCRK8Dd68Q8qzzbKgj56VTGFSGIi%2BXmrBWzCHMW5K%2Fok6ZNnNTUIUC1TjkWYyhDKUfejXLN9d6X8skRRiXOTD38UZwsG4C6VFDIbt3VlNa9Kl%2FDtOQGJkDqREoT9KgMk%2B8IZ3jRmn3U27z41HI9ZKAO2yGBv45MEzgXap%2BqXVDuuOh8RITFp0vzVIIzaLGgx6lxYgsgPVqkLnPjSY8Qc%2FjD0mspYfZ1EuZaueoOCOpLCbP2sdNulGWYQpcJFGccEz46hVPLmvO3MN%2BIUVa1KBvDEi%2FbuIfZu91Jw8Z0AIsvy4p8mxZu679ZtgLe9GQhgZI0mumQ68V3iI371a0YUaFpsG8%2FHJ%2Be2DWejIXJrxfj9trfkb3SFdVbY9DNoGizshDjaCLcKOzbHAAJGNUn3ri57aANQwJ7w9hrcPIXapUmuJxh1mz1YA3EgB%2BC7gpdjnnbL7lWIZ4fhq%2FGmm%2FC2EgYQD7hBmmw78636gyrCijSClspTyGNkIBOWhGAeGgtlRF23iar48vpXtlTzIheVBcHbO40Lqj1ilTXp00V5cHyG4u74Gp9tmKdPh1nXwbZhG5hHirvcrZTCuzN%2B9BjqkASKAVXwcZCFaZGdJVvYsBkcZ8i89m%2BLPIlv01BDN6%2BtDs70gpKw9n%2B1GXyqr5LtmKj0S%2BUZVbCY4EIMSEx8rImDme1HQo%2FiWGVOJ0qunOfzcVy1EqJIBVYjKknvM1cyBuXOIGCJ252wahEiA7TyKMWMZwFXl%2BCMCztFcCv9w%2FgUr5YuKUVeTqO%2B9jBgknxUEc1alkJLy4FEJv53xC3GHTXfAaQ8P&X-Amz-Signature=f33a8f5059a853cc1d3a815ea62a33521027dd08a9c100cf219f0ef6feded63a&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662PWUPMVZ%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T025448Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCWUI1m%2BLvCGPAQ%2BKema2SFOlxv6O6ks8rtIYL%2Btu3bIQIgLfkbCCjgnFKQcfPekMfhv4YN7pyYmvW8TB1INqTsp5gqiAQIzP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOZxFrHYv71sTjpl4SrcAz3cIxvUDke%2Fzou3Ms1QytnMag%2BjZvQc7trQLsQmx54WixT3mMHZuCu59WvtFNzJ9amSi3SVOs6dX0qRy5wVTtZWXh2AvJBL1%2Fj2umxf51EW921IgCzDU5B%2BICUIKeKFOnavDNjTSFlwumicTNIAy7W7m0MVaFofjcGahWzTkLvQ1xs7fKIjx%2FM0%2BTY9NRQzjLmaXtnCKJeGMfZypkvpPYqXe5ITavRFW4HALJrZQUTovF1I5nExMPCe%2FU%2BfDUN%2FJg8sl68UtB5X%2FaDTAoyTOyjOZRyP0emvL%2FVGUmOtXko7RoMQec9qExu73fxDpTdRTcnnt%2FyZSAv3EQKdK10gW9lCZtx9WxtsddL%2B2xzBcLP53oD%2Ba7MCJPCX5WdFKJP1JDeHnF9Ne5RVMS0QGG0ObLcAK9GTyZmpg%2FfANTGMecbNudL9NiTa6FiXaNT15FXrMAeS06J5vEMHgXNLum1K1PeXNBAE0IiCodHZbKG9zJDnaUrJXItAhsbLavf2BGbiYN8jonmYoFAZsonTOejh%2BKNZUd25BF5f0KYHXKKAs%2BkGlTyUHmY0KEgkRmqhjZeCqiWYRL4KoXgsamCuP0jQwIEUO15j%2F0LxHdlJnNoupa397xkGImCIoptg3PmxMPXK370GOqUBAh5M5PKlvEP99wJjo6pgXo0dOKwLh26D2O36L2VB7RTSg1MRgeo8vYTSFM5p1MrU4E0lbhZkvEj8IIfW61oHgIo6YmIR8F%2FQNhgpLSoS8hQYYJLjNKjAiS%2B4Q3zxeIVN3FjCOpW6OjeRfvrS6sDtaIgru5C8nMbJXc8m77bWcZY5qvuRQ3v%2BMFvlmPcxdIF9%2FL%2FTk6GycxsTFgBSW1qwkAk21x1e&X-Amz-Signature=cb9e7c2741d525578b3b98003679b98c80da29638f707b9983f5f34e1147b749&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662JDIJWWJ%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T025447Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIHM0UDqZC%2Fc%2FZqa1SbxHBlsEvYdW%2FwBfByxf%2FIf0veIOAiBf8VUPiEph97iBQL9UvpipAlKrkODSQ88esTDTNyT7bCqIBAjM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMf8uxg4Gvn2Zqon5QKtwD%2FxY%2BNEIP5GdVkErLX7Gn5aE8fSWjKYzdBSMy8TOEslxwX9iTMVFSP0DPqfhOKYkWbAGNW77VMbacOC%2Bom9kqnK0wy3%2BWD2%2FfqbpB%2Bw51XpLOFojRStgbdCdO%2BoQpWA8iSlVXTk0eqhZ7N26mZfOnz62ErXRmWdIuzy5ALijNFWbJpdPFwBqv03GWhltNHHh7YRyuPJoNa2rhlyS1VbGj9ESVd8X878SzvcXKKDO8hicgYx8WCFKfUybG2UPSyvCaCj63Ue1ESubBZufTyY4n88iw9WTWQmrTIiu5uKxnbhVXIzONSlgmv03erf1VkyLMUAW1tkVE2wkBrYFlO%2BG0ZpkwY2dIm%2BYUyvGuqCU%2Bzy5Z%2FUT84PZRXAoKjTsoDBgMQigPGT0ggRZRDC9dMRnbsLDwjpNpo2%2F6uzuE2WwjlZFlT%2FrFeUdmkLf9Qr9BHXUbvAfikEGkX1ndJvDWz2Uj3JyQoUVqo53kVf1Uty%2B%2FnptvdUnQw9SF9W0kBOfaPtOHBDVhCgG87D%2FTjTkIlakOSIw6EpdUs%2Fvuk4x8kYyqOYs2nw29bKUkplY%2BydNy%2B6g7uAedeoePbefbJndoAQ%2FfchrhrHGQ3gvOvbLJr6u0kv58f89%2FDpFGei6T2Qcw2MrfvQY6pgEWEwXIcykwAVy3saYAsyxAbuqGhctF5Pxx61Nx4V8BmTPAb4FTz1ko6Dj5YHxhh2xddAlMVdS7ytbWPGsFeA4y0H8WBI70o5n0zUaSM1u%2BmMxsq0hEmlZUOYa5ZwQ53Jjwk2W%2B3NUTfvmDq%2B%2BQJSRH4REyKCp76Et5g%2BhoFCzLat0veG4f0HUnOo9Rgg5dhRD0NmjTct9kPTkjiyOPC%2B7u5dmnk5nL&X-Amz-Signature=b3e58d12e1d252a65140682abc31503a98a0d5842cd963f6131db4e435806503&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662JDIJWWJ%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T025447Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIHM0UDqZC%2Fc%2FZqa1SbxHBlsEvYdW%2FwBfByxf%2FIf0veIOAiBf8VUPiEph97iBQL9UvpipAlKrkODSQ88esTDTNyT7bCqIBAjM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMf8uxg4Gvn2Zqon5QKtwD%2FxY%2BNEIP5GdVkErLX7Gn5aE8fSWjKYzdBSMy8TOEslxwX9iTMVFSP0DPqfhOKYkWbAGNW77VMbacOC%2Bom9kqnK0wy3%2BWD2%2FfqbpB%2Bw51XpLOFojRStgbdCdO%2BoQpWA8iSlVXTk0eqhZ7N26mZfOnz62ErXRmWdIuzy5ALijNFWbJpdPFwBqv03GWhltNHHh7YRyuPJoNa2rhlyS1VbGj9ESVd8X878SzvcXKKDO8hicgYx8WCFKfUybG2UPSyvCaCj63Ue1ESubBZufTyY4n88iw9WTWQmrTIiu5uKxnbhVXIzONSlgmv03erf1VkyLMUAW1tkVE2wkBrYFlO%2BG0ZpkwY2dIm%2BYUyvGuqCU%2Bzy5Z%2FUT84PZRXAoKjTsoDBgMQigPGT0ggRZRDC9dMRnbsLDwjpNpo2%2F6uzuE2WwjlZFlT%2FrFeUdmkLf9Qr9BHXUbvAfikEGkX1ndJvDWz2Uj3JyQoUVqo53kVf1Uty%2B%2FnptvdUnQw9SF9W0kBOfaPtOHBDVhCgG87D%2FTjTkIlakOSIw6EpdUs%2Fvuk4x8kYyqOYs2nw29bKUkplY%2BydNy%2B6g7uAedeoePbefbJndoAQ%2FfchrhrHGQ3gvOvbLJr6u0kv58f89%2FDpFGei6T2Qcw2MrfvQY6pgEWEwXIcykwAVy3saYAsyxAbuqGhctF5Pxx61Nx4V8BmTPAb4FTz1ko6Dj5YHxhh2xddAlMVdS7ytbWPGsFeA4y0H8WBI70o5n0zUaSM1u%2BmMxsq0hEmlZUOYa5ZwQ53Jjwk2W%2B3NUTfvmDq%2B%2BQJSRH4REyKCp76Et5g%2BhoFCzLat0veG4f0HUnOo9Rgg5dhRD0NmjTct9kPTkjiyOPC%2B7u5dmnk5nL&X-Amz-Signature=189dec3f04dd4c2a16d1f4aef3954b4502900220eb8ac6b1dfe3bb8099511f90&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662JDIJWWJ%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T025447Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIHM0UDqZC%2Fc%2FZqa1SbxHBlsEvYdW%2FwBfByxf%2FIf0veIOAiBf8VUPiEph97iBQL9UvpipAlKrkODSQ88esTDTNyT7bCqIBAjM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMf8uxg4Gvn2Zqon5QKtwD%2FxY%2BNEIP5GdVkErLX7Gn5aE8fSWjKYzdBSMy8TOEslxwX9iTMVFSP0DPqfhOKYkWbAGNW77VMbacOC%2Bom9kqnK0wy3%2BWD2%2FfqbpB%2Bw51XpLOFojRStgbdCdO%2BoQpWA8iSlVXTk0eqhZ7N26mZfOnz62ErXRmWdIuzy5ALijNFWbJpdPFwBqv03GWhltNHHh7YRyuPJoNa2rhlyS1VbGj9ESVd8X878SzvcXKKDO8hicgYx8WCFKfUybG2UPSyvCaCj63Ue1ESubBZufTyY4n88iw9WTWQmrTIiu5uKxnbhVXIzONSlgmv03erf1VkyLMUAW1tkVE2wkBrYFlO%2BG0ZpkwY2dIm%2BYUyvGuqCU%2Bzy5Z%2FUT84PZRXAoKjTsoDBgMQigPGT0ggRZRDC9dMRnbsLDwjpNpo2%2F6uzuE2WwjlZFlT%2FrFeUdmkLf9Qr9BHXUbvAfikEGkX1ndJvDWz2Uj3JyQoUVqo53kVf1Uty%2B%2FnptvdUnQw9SF9W0kBOfaPtOHBDVhCgG87D%2FTjTkIlakOSIw6EpdUs%2Fvuk4x8kYyqOYs2nw29bKUkplY%2BydNy%2B6g7uAedeoePbefbJndoAQ%2FfchrhrHGQ3gvOvbLJr6u0kv58f89%2FDpFGei6T2Qcw2MrfvQY6pgEWEwXIcykwAVy3saYAsyxAbuqGhctF5Pxx61Nx4V8BmTPAb4FTz1ko6Dj5YHxhh2xddAlMVdS7ytbWPGsFeA4y0H8WBI70o5n0zUaSM1u%2BmMxsq0hEmlZUOYa5ZwQ53Jjwk2W%2B3NUTfvmDq%2B%2BQJSRH4REyKCp76Et5g%2BhoFCzLat0veG4f0HUnOo9Rgg5dhRD0NmjTct9kPTkjiyOPC%2B7u5dmnk5nL&X-Amz-Signature=c149948af2fc258522d4012775ffa9197586d6c2a3fede9b8c52d882794abf85&X-Amz-SignedHeaders=host&x-id=GetObject)


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

