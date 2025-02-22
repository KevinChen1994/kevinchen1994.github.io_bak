---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4662CRB4OBY%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250222T162655Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEMj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIEnv8YgM5M560WHLsWY\
  zz9FF5nP4wWnjfJtvHPe15iNeAiEA9UALAmvt3Wt2o57gpIhY0SzNryiicXmfzKjKLSkJj9UqiAQI\
  8f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGSAiO4RlgL6Cl5dBSrcA\
  0JI4IePFn424iH9O2pDcnOIq45UgFYNKTKX0I64mrs0X05sajD9Jhzwsz82GApAyByT1muG0xAu5R\
  KeTHEQXVq%2FNS1gy2msOx212%2BRrwZxQJaRNmc4LNxazMJpGRCrpbSExB95sR3QhVeZdGPx4NEC\
  CZSbOe%2FSuo5GYvm%2FXx04mK4sUNsYdiY3JvdNNFgTvz2TYzGEKNTS3NKKx67Ahv3a6P0xNBlin\
  lXPh2AkD32xYOYz9yASo%2FKGer%2B1GtJKIxc0gs6SbmRlfBeGU3xUjxKgFQ7FlDXMX00r7MOLTG\
  WXnNQL51PBvDQPNyrq7WkDMAq9LWT5tl0Ikumrj27mA3brIjtplScC%2F9mPTvOM0xyhy1EN2EvXX\
  Dng6AifDkHguAi1vhub4XiRIBkrFS9vCJwcrqmeeHyZmYra9qwMxKkLIQN8JoYMII3G%2B%2Femy4\
  kJmGPdysc0ZYwLbqNXnjhnALy2b1boI%2B%2FGDBVbkdAynVCdXKa8i%2FZWO4sOzQ0Glz4UvWqFg\
  fvS9tASPoTnCBZz5dJXuAUsrJYVCzzRD6nwjKMyjeuIapcgTQGCAxMBVWsoGjpml%2F6JbjpUCYQR\
  2fxklNOifRh9SBQlY7sdmmvHhBTtYPvf%2FUkOiMOPzvLUeMKPx570GOqUBL3MQsLfjzhNPSeOPe9\
  AFicDS6ar6jXDTiCIbqLGocgTP4AN7Yu%2FszsfeSKp50pGMgWYa6Y47fnp4K%2BoeiIZg%2FrS5X\
  HJz4sWez63W5h3q%2BzKSnGXsrX%2BWRxjLU0ethy0iYfA7IMsItXNgp451TaXiPsn3HVDOMTpD2V\
  Y2HTlvD29nia33%2FV3QokVftsJPYt6mcMQOIMC%2Fuf1pYlEDFnpgCj3R28E1&X-Amz-Signatur\
  e=06f9f5ad784ce39ac5b59ab3cd8e7270412d5be91a6d9d5fc59b2fb1aa029ece&X-Amz-Sign\
  edHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4667KHDCPLJ%2F20250222%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250222T162525Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEMT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIQC1vamjnsegw48xJKRvbLgwi9Qz6TpeH6SgSBp4No7k%2FwIgcY%2BK%2FC2jr7I0ijha\
        GyX2iFoBgI5M38VR8hm7dc2Wds0qiAQI7P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw\
        2Mzc0MjMxODM4MDUiDCZAZPO1NKiD7OwxzircA1Ho9kJObBmcjX5vIdRBMup%2FbmNnaSui\
        t9tFRERnTCl%2FMP43e1vhQNncKMCj6ROAs6%2BNcZ69pWe%2Fcv5hwLF3%2FbHAkYfk2A6\
        w35MXzlmX6QIESzs78x3lfComFha19pb0lYWmec3f1nnUv1Z76VNNHwoq3hCbG1MPaPaoU8\
        ONQEraT5WTi1XBfgE5gwe4i72i25DZtjcNT5XvfPL7x1UNOI6m9AdlwdUrk3zck%2Fpw1Kf\
        42Ll8a8Awsm41YHW%2FNGVKZ%2FzCIMNBlErIZsLyfwTBj%2BdJeUPh8Z81vmDyWTer6o1t\
        8zSRbFpbF1URpjCbRbjedi%2FjocGf7SJy7Wb74e6lfi7u%2BK7nQRHyNpBcy4QAyxJ5sh7\
        zYrFIWm0DxnMr%2Batqx4fP9y7AzHrd3rz8IiGtPFdtfEK6gW4h1pEIgMqpUL2GieV%2BRo\
        r6J2z5dgG8TZxJh%2FiaL6QCK9uW4vhko4ou60gkQsdyP%2Fin0XtPgCpdriEOmPuT2QGQB\
        tyBb%2FopHpDrmJWs8s3EIbxN2EuIc6xK4pmCs51rz7Dfeg44Et2eR2uE8fT%2F0ryD9cJZ\
        p9OK7OyWuyFInRkX91evQy7uSEtxm3sDtdHnpB7vb1JgjtnRRDS0JRYudmAWdm4n8g%2BwM\
        Mrl5r0GOqUB3V048lNq067iYzFEJQ4Qefc2pc7M9Uxkb1Y3xGy06FBz8Cl7qhE6Wrv9XsDp\
        4KPGA5JYGFo0esg4BwwFWSiU7go5qHqh%2BdFko9O0FfWma26%2Bmc6YmZ%2F2RyMSMYCkZ\
        vxCxOXNO1cBc6fNR%2Bkiisx%2FNyF%2Br5gqUfugIs%2FMmScozhXnDPVXwAHF%2Fv%2FR\
        62r2hTscBOKt%2FWjB3jNckAdboNxfed38hdAY&X-Amz-Signature=013a5cb3c60b00d8\
        538c24754183259c25e9e2a484ced8e437a3715840d97750&X-Amz-SignedHeaders=ho\
        st&x-id=GetObject"
      expiry_time: "2025-02-22T17:25:25.743Z"
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
UPDATE_TIME: "2025-02-22T16:27:00.756Z"
EXPIRY_TIME: "2025-02-22T17:26:51.187Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QYUDCV6A%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T162651Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCXJjZw2tB52Mi%2BPiTocfX0sh4rs4ylm4DSWz6txwxd8QIgBYhqB6s2OHSw9%2FOvdJyaB2SvxQs6iuVXoljJVrQE864qiAQI7P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLA%2FV4tKRYm2QmIikircAxU74GuxOD18KMuHiYdRJEri%2F4cq0zr4HWyfVhoOx2%2F1xV%2BQgJwZ1gQ3dcZZdf3xi69iACKF82MDueCox6tgZa%2F5mjQcCHS4bnmgpJVMO1dWehCWnno499qcGZImMA%2BJmCHm22T38DvXgRXxIa%2ButbO3hrb0qs9S%2BivRjX3NRv7IISKXPi4SdP3pds6qL2cb2%2F4PhtsNWM%2BSbFRKbt8yKYrRXtALLTU7XsWf2jc%2BZ%2BW0R%2FCBkLvYR8JgqNgv6MKAmMEd2aYocmHwNmccVsruq85%2B5QaRrjyA7J5oXognRPX9J99ehq1P6%2BL2Lc%2FMdcd2KXpYUXjCcWr1jCsEKtiVEKjs%2B9d9IZZzSrQHJ4i66ruSh8uHTicUMn4Dbs52EK7CbG8e4RJQjlesdEaCmh1HXr6dldFfXCKbPlpMoOqijTXmJlvAlPTUF%2B3DdA5DBZuzoNnRJ697ygb76%2BsyozWOQjE3n16jHiEF590VmESaKP2%2B6w8oc5MZjYIFKStzjNw0wQJO7XhDfafLhMDBzB3n56JfHugfZcUAGiCdHFVSOqbKmeuOMjidJyHKi1WHbTZnfTwWi5lFsit%2BXlsNVd5L2wQ3ejpUF4TyiX0bjL%2BwzN51Qc%2BGKqsawwMAv9suMOXi5r0GOqUB6qMFzgTnHEM3kaajsmUlCz2kQ4rVWA%2BT4lC7Y2IzLzAytDjKoNJ48r9a2Bn%2FEnr%2B4XWtCMGA78fRoh9QNb6jfkbFEbmutIv8zyKgRx6OFimzWcW%2Fif8fO3XXf3wXsrCk0q2bR7sbqqUNKcCpfzmykDOAtW9is85nkO1e3cQ3BLbYfR%2FAhEcIb%2BaB9LGwzEu1kwsJLd%2BmwVQNqYDFzYc9CZSbiWJ4&X-Amz-Signature=be1bb1013c2423abed73b1990aa1b17737a4c70c234827d032603cb9c3b7c8e6&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QYUDCV6A%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T162651Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCXJjZw2tB52Mi%2BPiTocfX0sh4rs4ylm4DSWz6txwxd8QIgBYhqB6s2OHSw9%2FOvdJyaB2SvxQs6iuVXoljJVrQE864qiAQI7P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLA%2FV4tKRYm2QmIikircAxU74GuxOD18KMuHiYdRJEri%2F4cq0zr4HWyfVhoOx2%2F1xV%2BQgJwZ1gQ3dcZZdf3xi69iACKF82MDueCox6tgZa%2F5mjQcCHS4bnmgpJVMO1dWehCWnno499qcGZImMA%2BJmCHm22T38DvXgRXxIa%2ButbO3hrb0qs9S%2BivRjX3NRv7IISKXPi4SdP3pds6qL2cb2%2F4PhtsNWM%2BSbFRKbt8yKYrRXtALLTU7XsWf2jc%2BZ%2BW0R%2FCBkLvYR8JgqNgv6MKAmMEd2aYocmHwNmccVsruq85%2B5QaRrjyA7J5oXognRPX9J99ehq1P6%2BL2Lc%2FMdcd2KXpYUXjCcWr1jCsEKtiVEKjs%2B9d9IZZzSrQHJ4i66ruSh8uHTicUMn4Dbs52EK7CbG8e4RJQjlesdEaCmh1HXr6dldFfXCKbPlpMoOqijTXmJlvAlPTUF%2B3DdA5DBZuzoNnRJ697ygb76%2BsyozWOQjE3n16jHiEF590VmESaKP2%2B6w8oc5MZjYIFKStzjNw0wQJO7XhDfafLhMDBzB3n56JfHugfZcUAGiCdHFVSOqbKmeuOMjidJyHKi1WHbTZnfTwWi5lFsit%2BXlsNVd5L2wQ3ejpUF4TyiX0bjL%2BwzN51Qc%2BGKqsawwMAv9suMOXi5r0GOqUB6qMFzgTnHEM3kaajsmUlCz2kQ4rVWA%2BT4lC7Y2IzLzAytDjKoNJ48r9a2Bn%2FEnr%2B4XWtCMGA78fRoh9QNb6jfkbFEbmutIv8zyKgRx6OFimzWcW%2Fif8fO3XXf3wXsrCk0q2bR7sbqqUNKcCpfzmykDOAtW9is85nkO1e3cQ3BLbYfR%2FAhEcIb%2BaB9LGwzEu1kwsJLd%2BmwVQNqYDFzYc9CZSbiWJ4&X-Amz-Signature=e990bf1d07e604aac3d8ddfc9757708915be79e7ee116cba1e214c17dd7f1d60&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QYUDCV6A%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T162651Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCXJjZw2tB52Mi%2BPiTocfX0sh4rs4ylm4DSWz6txwxd8QIgBYhqB6s2OHSw9%2FOvdJyaB2SvxQs6iuVXoljJVrQE864qiAQI7P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLA%2FV4tKRYm2QmIikircAxU74GuxOD18KMuHiYdRJEri%2F4cq0zr4HWyfVhoOx2%2F1xV%2BQgJwZ1gQ3dcZZdf3xi69iACKF82MDueCox6tgZa%2F5mjQcCHS4bnmgpJVMO1dWehCWnno499qcGZImMA%2BJmCHm22T38DvXgRXxIa%2ButbO3hrb0qs9S%2BivRjX3NRv7IISKXPi4SdP3pds6qL2cb2%2F4PhtsNWM%2BSbFRKbt8yKYrRXtALLTU7XsWf2jc%2BZ%2BW0R%2FCBkLvYR8JgqNgv6MKAmMEd2aYocmHwNmccVsruq85%2B5QaRrjyA7J5oXognRPX9J99ehq1P6%2BL2Lc%2FMdcd2KXpYUXjCcWr1jCsEKtiVEKjs%2B9d9IZZzSrQHJ4i66ruSh8uHTicUMn4Dbs52EK7CbG8e4RJQjlesdEaCmh1HXr6dldFfXCKbPlpMoOqijTXmJlvAlPTUF%2B3DdA5DBZuzoNnRJ697ygb76%2BsyozWOQjE3n16jHiEF590VmESaKP2%2B6w8oc5MZjYIFKStzjNw0wQJO7XhDfafLhMDBzB3n56JfHugfZcUAGiCdHFVSOqbKmeuOMjidJyHKi1WHbTZnfTwWi5lFsit%2BXlsNVd5L2wQ3ejpUF4TyiX0bjL%2BwzN51Qc%2BGKqsawwMAv9suMOXi5r0GOqUB6qMFzgTnHEM3kaajsmUlCz2kQ4rVWA%2BT4lC7Y2IzLzAytDjKoNJ48r9a2Bn%2FEnr%2B4XWtCMGA78fRoh9QNb6jfkbFEbmutIv8zyKgRx6OFimzWcW%2Fif8fO3XXf3wXsrCk0q2bR7sbqqUNKcCpfzmykDOAtW9is85nkO1e3cQ3BLbYfR%2FAhEcIb%2BaB9LGwzEu1kwsJLd%2BmwVQNqYDFzYc9CZSbiWJ4&X-Amz-Signature=137e109cf6c1adf51d5542b415bbef444e77892d56a3d51a633e10432e737324&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QYUDCV6A%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T162651Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCXJjZw2tB52Mi%2BPiTocfX0sh4rs4ylm4DSWz6txwxd8QIgBYhqB6s2OHSw9%2FOvdJyaB2SvxQs6iuVXoljJVrQE864qiAQI7P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLA%2FV4tKRYm2QmIikircAxU74GuxOD18KMuHiYdRJEri%2F4cq0zr4HWyfVhoOx2%2F1xV%2BQgJwZ1gQ3dcZZdf3xi69iACKF82MDueCox6tgZa%2F5mjQcCHS4bnmgpJVMO1dWehCWnno499qcGZImMA%2BJmCHm22T38DvXgRXxIa%2ButbO3hrb0qs9S%2BivRjX3NRv7IISKXPi4SdP3pds6qL2cb2%2F4PhtsNWM%2BSbFRKbt8yKYrRXtALLTU7XsWf2jc%2BZ%2BW0R%2FCBkLvYR8JgqNgv6MKAmMEd2aYocmHwNmccVsruq85%2B5QaRrjyA7J5oXognRPX9J99ehq1P6%2BL2Lc%2FMdcd2KXpYUXjCcWr1jCsEKtiVEKjs%2B9d9IZZzSrQHJ4i66ruSh8uHTicUMn4Dbs52EK7CbG8e4RJQjlesdEaCmh1HXr6dldFfXCKbPlpMoOqijTXmJlvAlPTUF%2B3DdA5DBZuzoNnRJ697ygb76%2BsyozWOQjE3n16jHiEF590VmESaKP2%2B6w8oc5MZjYIFKStzjNw0wQJO7XhDfafLhMDBzB3n56JfHugfZcUAGiCdHFVSOqbKmeuOMjidJyHKi1WHbTZnfTwWi5lFsit%2BXlsNVd5L2wQ3ejpUF4TyiX0bjL%2BwzN51Qc%2BGKqsawwMAv9suMOXi5r0GOqUB6qMFzgTnHEM3kaajsmUlCz2kQ4rVWA%2BT4lC7Y2IzLzAytDjKoNJ48r9a2Bn%2FEnr%2B4XWtCMGA78fRoh9QNb6jfkbFEbmutIv8zyKgRx6OFimzWcW%2Fif8fO3XXf3wXsrCk0q2bR7sbqqUNKcCpfzmykDOAtW9is85nkO1e3cQ3BLbYfR%2FAhEcIb%2BaB9LGwzEu1kwsJLd%2BmwVQNqYDFzYc9CZSbiWJ4&X-Amz-Signature=1acb047c1c3de9d34431893e85334d159d463ebcde3c3c6e8bb0df2fb3b610b9&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QYUDCV6A%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T162651Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCXJjZw2tB52Mi%2BPiTocfX0sh4rs4ylm4DSWz6txwxd8QIgBYhqB6s2OHSw9%2FOvdJyaB2SvxQs6iuVXoljJVrQE864qiAQI7P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLA%2FV4tKRYm2QmIikircAxU74GuxOD18KMuHiYdRJEri%2F4cq0zr4HWyfVhoOx2%2F1xV%2BQgJwZ1gQ3dcZZdf3xi69iACKF82MDueCox6tgZa%2F5mjQcCHS4bnmgpJVMO1dWehCWnno499qcGZImMA%2BJmCHm22T38DvXgRXxIa%2ButbO3hrb0qs9S%2BivRjX3NRv7IISKXPi4SdP3pds6qL2cb2%2F4PhtsNWM%2BSbFRKbt8yKYrRXtALLTU7XsWf2jc%2BZ%2BW0R%2FCBkLvYR8JgqNgv6MKAmMEd2aYocmHwNmccVsruq85%2B5QaRrjyA7J5oXognRPX9J99ehq1P6%2BL2Lc%2FMdcd2KXpYUXjCcWr1jCsEKtiVEKjs%2B9d9IZZzSrQHJ4i66ruSh8uHTicUMn4Dbs52EK7CbG8e4RJQjlesdEaCmh1HXr6dldFfXCKbPlpMoOqijTXmJlvAlPTUF%2B3DdA5DBZuzoNnRJ697ygb76%2BsyozWOQjE3n16jHiEF590VmESaKP2%2B6w8oc5MZjYIFKStzjNw0wQJO7XhDfafLhMDBzB3n56JfHugfZcUAGiCdHFVSOqbKmeuOMjidJyHKi1WHbTZnfTwWi5lFsit%2BXlsNVd5L2wQ3ejpUF4TyiX0bjL%2BwzN51Qc%2BGKqsawwMAv9suMOXi5r0GOqUB6qMFzgTnHEM3kaajsmUlCz2kQ4rVWA%2BT4lC7Y2IzLzAytDjKoNJ48r9a2Bn%2FEnr%2B4XWtCMGA78fRoh9QNb6jfkbFEbmutIv8zyKgRx6OFimzWcW%2Fif8fO3XXf3wXsrCk0q2bR7sbqqUNKcCpfzmykDOAtW9is85nkO1e3cQ3BLbYfR%2FAhEcIb%2BaB9LGwzEu1kwsJLd%2BmwVQNqYDFzYc9CZSbiWJ4&X-Amz-Signature=10ac0dad2c40ff29d8b1046f925785d1a75252b462979a92544263753e35fd1f&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466R5NQNKQK%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T162652Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIHFz7SBTXrR2272bwXJ1zwF%2BeJdxLNcZTlDUgndUwb6iAiEAtDppJmtg4idLZS3bvhZ%2BQ%2BvLnTEM90bcQJqmLfsSLjMqiAQI7f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDFOUWSkftfqSUGCk4SrcA2%2Fy6PyLKsdlMTH4%2FVCD4HyZZgaY2Qp6MQssS4B%2FiUQXCfBEVLT%2BX9nZjFfo4LAt%2FkXvhyHKOeHhcaNC0OA%2BoYdyJE0wfJvQ5kSfrSkK8E%2Fv%2Fo2Z9u2y0X0YIHBLOm9hD5SilF7pUOE8xlm%2BYxjyicAGc%2BD%2F1lfb1Z9PE8BRqMaKG89gH6UpxGzQ7ZipWOx6zQGsb8zb4giVz%2B8P20mFDvskUIzYZPq588ZJ6Dv9pcWwUZJpxiRY8JX4jmw0JATyJJlAlP0%2BQcTQLCKJ5faVC%2BMEYsWk2kshQOtCImDlE9T0qpZvWa%2FuvQyZA6fgvfvRtcPKlJcerkAjQM9g2yRPDnezhNd8Q3eAaPzjb5SjCe3mBLQpZLLNzMsd8T4f%2FbynOafP8E4EBxno%2BzKWW5A41T4385Cx6EIUzlzMx57j6T1Kj6IZ%2BJp8U5VoAuS4ITGZWUz2zG42zcVmnn39tqNkzg19FXmaQZlo6jeFUEQ%2B9pGVRifB9xT%2F7PTYDFZ7UH2DgRvXvtRiuy6cEJTKaCv9egz%2FHu62BE6afrQ2OqMUXMuJw3oktpuWo%2BTfXrC9BFbHQ3WTgP303v8ZvOlEhpxNNYWGrt7p%2FWFWDwe13WJvnG%2FjrZoTA4oEyFMFZc9PMPzp5r0GOqUBduoSEvDdwIUwNbA7H9Td%2BpMgZRjdEH%2FznNIKE%2Br%2B2m1k7bYRKEXZIoRQS0mnUbjUYbx%2B%2BERVwIHUMC5zPHU1dGgBwVOFCNpjLCosPg5uyH2W71sCrimkqmgGooQIf4wIWZCVaU13gVWoc8hw%2BbJj3MwdpKdifWPI8BbbxZaY1HiGB%2FwS2%2BnkHrBzBMmyzSflYwQzX6iW%2BQ4rvj78Uv%2BWykGoeT0C&X-Amz-Signature=c26c4f3cc0126fb0573ad704efd13b5471fcf770de4bb9af379e0347d6a60b5d&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667XWNYKDB%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T162654Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDDVngaBdqFoZdxaumdEit%2F0FRgiB7a12l%2Btc7OrZDnlQIhALg2uPnDGFqb7iq3rOU%2B68sPe4kXXaQ3%2FrNzpZxSvR%2FzKogECOz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igz1ANm2%2B50rKsWokX8q3APKIOc62eA13VlSlacltDC1WoklYvX4v4lvRZF%2BsHwIOyv4NtyLKCN5paRNUa5bk9IMwPMc%2Fo4hm50UFR1%2BvX%2Fit81%2FWQ0w3QaK0b9qT7RxbuQcZJL24r%2F4c6NlqW2OyXCf19%2BdHWBAVLkl2TyhDPsfzdkOm856wUw7Bd%2Fa8XE1j2jQ0vVLbv5VjrvzMLtBUB9rb8%2FONbdZVAwuwpMc%2BzfevRG7SeJ3IUAC6dCLIdaprG8TNQ6JaM33ZwBHE8JmZkeoeE6iqBPN%2FLaG8m2RgyYF%2BeACUxvtFNGjUbtvIKRxMdDh60uTlv2HyvcEw7FnoqAmCF8CRiySROztHNHu12NJ9oUMrh0kKeSfSDXyg1WOwnE%2FKzhhJGrWCbOlRbhn0ZBY7enN4otoLsIy2i2BVuuNq%2FYuhVz%2B6Rw3ukjkJyHpLyx98TsHrnGYuuWOlZRGOCNSER1hd7GIKvLV0pybM19B3aC3xkDv%2B%2BGuE1l7r3q4ob5rK5iMYk%2BwfpRkSm5Uh9XA5jXwFi9vFVAuRuoNVqKKAczyty%2FmmDC1aJcm4pvVcT%2Bv5XhjjCdH3ZiURO7mUr5Mc6aWPYzknTiuTqZtel2r%2BVaFDa2HOtK%2BkUMHc0wOVlLa0M%2BoT%2FH%2FC0zECzCu5ea9BjqkAQCyZlK1xj8sDsFWHNrLt4vNdNIi9A1hbpQ1ZCg%2BMGtPhpsRzoN0vwXQ9VnIfqSFPgjymt6IXTUYrqVblhlt%2FdtiESOpgVYtWdQ%2BGETJWLMEgVTWht252aHmS1MAQRz%2Fsixhg2KAXxgQJXXmPTk907LrnwSEco%2BLWeAhAk4SJhnH0tBMmFBFNMPcK65qgjQnomBhb350Td2nsG1BmwuOHavPjygR&X-Amz-Signature=2d590df9820c89953292833577fbb984e62f4c86e03fdd57e3880b55fb9dc52f&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QYUDCV6A%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T162651Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCXJjZw2tB52Mi%2BPiTocfX0sh4rs4ylm4DSWz6txwxd8QIgBYhqB6s2OHSw9%2FOvdJyaB2SvxQs6iuVXoljJVrQE864qiAQI7P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLA%2FV4tKRYm2QmIikircAxU74GuxOD18KMuHiYdRJEri%2F4cq0zr4HWyfVhoOx2%2F1xV%2BQgJwZ1gQ3dcZZdf3xi69iACKF82MDueCox6tgZa%2F5mjQcCHS4bnmgpJVMO1dWehCWnno499qcGZImMA%2BJmCHm22T38DvXgRXxIa%2ButbO3hrb0qs9S%2BivRjX3NRv7IISKXPi4SdP3pds6qL2cb2%2F4PhtsNWM%2BSbFRKbt8yKYrRXtALLTU7XsWf2jc%2BZ%2BW0R%2FCBkLvYR8JgqNgv6MKAmMEd2aYocmHwNmccVsruq85%2B5QaRrjyA7J5oXognRPX9J99ehq1P6%2BL2Lc%2FMdcd2KXpYUXjCcWr1jCsEKtiVEKjs%2B9d9IZZzSrQHJ4i66ruSh8uHTicUMn4Dbs52EK7CbG8e4RJQjlesdEaCmh1HXr6dldFfXCKbPlpMoOqijTXmJlvAlPTUF%2B3DdA5DBZuzoNnRJ697ygb76%2BsyozWOQjE3n16jHiEF590VmESaKP2%2B6w8oc5MZjYIFKStzjNw0wQJO7XhDfafLhMDBzB3n56JfHugfZcUAGiCdHFVSOqbKmeuOMjidJyHKi1WHbTZnfTwWi5lFsit%2BXlsNVd5L2wQ3ejpUF4TyiX0bjL%2BwzN51Qc%2BGKqsawwMAv9suMOXi5r0GOqUB6qMFzgTnHEM3kaajsmUlCz2kQ4rVWA%2BT4lC7Y2IzLzAytDjKoNJ48r9a2Bn%2FEnr%2B4XWtCMGA78fRoh9QNb6jfkbFEbmutIv8zyKgRx6OFimzWcW%2Fif8fO3XXf3wXsrCk0q2bR7sbqqUNKcCpfzmykDOAtW9is85nkO1e3cQ3BLbYfR%2FAhEcIb%2BaB9LGwzEu1kwsJLd%2BmwVQNqYDFzYc9CZSbiWJ4&X-Amz-Signature=9944ba9ae574305ed4e5b85aebd092bf4bdfcfc3dfaf2fb4b5ded63789561365&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QYUDCV6A%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T162651Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCXJjZw2tB52Mi%2BPiTocfX0sh4rs4ylm4DSWz6txwxd8QIgBYhqB6s2OHSw9%2FOvdJyaB2SvxQs6iuVXoljJVrQE864qiAQI7P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLA%2FV4tKRYm2QmIikircAxU74GuxOD18KMuHiYdRJEri%2F4cq0zr4HWyfVhoOx2%2F1xV%2BQgJwZ1gQ3dcZZdf3xi69iACKF82MDueCox6tgZa%2F5mjQcCHS4bnmgpJVMO1dWehCWnno499qcGZImMA%2BJmCHm22T38DvXgRXxIa%2ButbO3hrb0qs9S%2BivRjX3NRv7IISKXPi4SdP3pds6qL2cb2%2F4PhtsNWM%2BSbFRKbt8yKYrRXtALLTU7XsWf2jc%2BZ%2BW0R%2FCBkLvYR8JgqNgv6MKAmMEd2aYocmHwNmccVsruq85%2B5QaRrjyA7J5oXognRPX9J99ehq1P6%2BL2Lc%2FMdcd2KXpYUXjCcWr1jCsEKtiVEKjs%2B9d9IZZzSrQHJ4i66ruSh8uHTicUMn4Dbs52EK7CbG8e4RJQjlesdEaCmh1HXr6dldFfXCKbPlpMoOqijTXmJlvAlPTUF%2B3DdA5DBZuzoNnRJ697ygb76%2BsyozWOQjE3n16jHiEF590VmESaKP2%2B6w8oc5MZjYIFKStzjNw0wQJO7XhDfafLhMDBzB3n56JfHugfZcUAGiCdHFVSOqbKmeuOMjidJyHKi1WHbTZnfTwWi5lFsit%2BXlsNVd5L2wQ3ejpUF4TyiX0bjL%2BwzN51Qc%2BGKqsawwMAv9suMOXi5r0GOqUB6qMFzgTnHEM3kaajsmUlCz2kQ4rVWA%2BT4lC7Y2IzLzAytDjKoNJ48r9a2Bn%2FEnr%2B4XWtCMGA78fRoh9QNb6jfkbFEbmutIv8zyKgRx6OFimzWcW%2Fif8fO3XXf3wXsrCk0q2bR7sbqqUNKcCpfzmykDOAtW9is85nkO1e3cQ3BLbYfR%2FAhEcIb%2BaB9LGwzEu1kwsJLd%2BmwVQNqYDFzYc9CZSbiWJ4&X-Amz-Signature=2f999071122f26605995b1620a6c47041b02c7a183e6ceb3bb57e606c344b0b3&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QYUDCV6A%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T162651Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCXJjZw2tB52Mi%2BPiTocfX0sh4rs4ylm4DSWz6txwxd8QIgBYhqB6s2OHSw9%2FOvdJyaB2SvxQs6iuVXoljJVrQE864qiAQI7P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLA%2FV4tKRYm2QmIikircAxU74GuxOD18KMuHiYdRJEri%2F4cq0zr4HWyfVhoOx2%2F1xV%2BQgJwZ1gQ3dcZZdf3xi69iACKF82MDueCox6tgZa%2F5mjQcCHS4bnmgpJVMO1dWehCWnno499qcGZImMA%2BJmCHm22T38DvXgRXxIa%2ButbO3hrb0qs9S%2BivRjX3NRv7IISKXPi4SdP3pds6qL2cb2%2F4PhtsNWM%2BSbFRKbt8yKYrRXtALLTU7XsWf2jc%2BZ%2BW0R%2FCBkLvYR8JgqNgv6MKAmMEd2aYocmHwNmccVsruq85%2B5QaRrjyA7J5oXognRPX9J99ehq1P6%2BL2Lc%2FMdcd2KXpYUXjCcWr1jCsEKtiVEKjs%2B9d9IZZzSrQHJ4i66ruSh8uHTicUMn4Dbs52EK7CbG8e4RJQjlesdEaCmh1HXr6dldFfXCKbPlpMoOqijTXmJlvAlPTUF%2B3DdA5DBZuzoNnRJ697ygb76%2BsyozWOQjE3n16jHiEF590VmESaKP2%2B6w8oc5MZjYIFKStzjNw0wQJO7XhDfafLhMDBzB3n56JfHugfZcUAGiCdHFVSOqbKmeuOMjidJyHKi1WHbTZnfTwWi5lFsit%2BXlsNVd5L2wQ3ejpUF4TyiX0bjL%2BwzN51Qc%2BGKqsawwMAv9suMOXi5r0GOqUB6qMFzgTnHEM3kaajsmUlCz2kQ4rVWA%2BT4lC7Y2IzLzAytDjKoNJ48r9a2Bn%2FEnr%2B4XWtCMGA78fRoh9QNb6jfkbFEbmutIv8zyKgRx6OFimzWcW%2Fif8fO3XXf3wXsrCk0q2bR7sbqqUNKcCpfzmykDOAtW9is85nkO1e3cQ3BLbYfR%2FAhEcIb%2BaB9LGwzEu1kwsJLd%2BmwVQNqYDFzYc9CZSbiWJ4&X-Amz-Signature=ddfba42d497acaa44a226d86b1f4981b4cf65c04e24119eb877f7960aebdf98b&X-Amz-SignedHeaders=host&x-id=GetObject)


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

