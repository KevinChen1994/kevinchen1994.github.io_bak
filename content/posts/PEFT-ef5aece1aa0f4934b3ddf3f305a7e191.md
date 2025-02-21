---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466V3XFSQHS%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250221T102610Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEKr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDcZEGz9qg1XS97ek7\
  G%2FpHgzCFJ5RtipyiB9O6doGVlgAIgS0ZvuqkRTDUXRly9HOIF0Z6lkZbNeL1j6qJbszbhKgEqiA\
  QI0%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDJZqwzXc4%2BV1FDl\
  KeircA89ydSmDnrTjgXDKyANXY13gHPuwSNqIsGU3X2wWFoFvyzVaWLM595l%2F5Ffs3aTWRbc%2B\
  1pNwafd9kJuNdFGkgYDBaAQ7G%2Fyroq8AqWb6tzjDv5K2tNymic%2FMnk4pBSWaSQRvQAXhwhftF\
  opx7mN1QWOfOPs4xdljZaOCSlWBgnuuNQPjI3mztN0g2Q8sAIkUt598v1k%2BCS9uog5az6mnjEB2\
  hEjvNpvcsIhpE9Eggdq4NB3rgHfGKOBSp5QLpJ05d%2BBuH6JGb%2BWcFS2r4ChryTKZRD9F3dDxk\
  aNvc8JiFXcBHRp0y9K11Skd6Wvvf7PCGVmMx%2BdOAxxJclRypVLsZkkz7Sla3ZwfmiVTG1FZx9ij\
  pP%2Fyu0A6qwa0ax8XqYNx8haVu%2FoE83%2Bn16sZPSS4Qp2gdjjdC5TNpbLCIfhSUcsjq%2BMjd\
  Jra0RfkC5wlItzQCXTIWuWFZ3DH6ZzmEjulkd%2BIwWuSDyvfm5u67KctiV8V4KVbf2BpGtb3TTH6\
  KDbAbHe%2FONxPYJxZv%2Fa1IW5g7PZaDFWU8pLlzflEi%2Fu8O4ZFMwRleAyIAOEd3oQ%2Fh7NoY\
  82uLROheR8p3%2FgTCFqKGPjzTrVLVHUK4WAJ8plTL5aHl9MBQhGozFqN10AXMOCZ4b0GOqUBromC\
  spr%2FCbh6phl2el7hfT0tLZO8LiuIc1979kyFj5mLvYO3vrQsG%2FjMxU%2FTyY0ibnyZqn8%2FO\
  ueXmRk%2BMQ1Tg4sKMdygI1FIRTRNia8ZFcdvS%2BqcUN3X6LWy799YL5laGQYpASRjH4wzxv8CPX\
  XlgEG3DLsEAq27HNrmSDlCsx1fOFVIHtqVT4An4xzzmNMv1Ho%2FNFtKvKROyhXQzNNU5MrQyZUF&\
  X-Amz-Signature=64232688f4441c6df652ade808e738aab3350bf1993311bba3e10ef517292\
  71b&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466RG7ED4IB%2F20250221%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250221T102417Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEKr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEY\
        CIQC0sBnehEW5okbfk2LTZCPn5f4diDHeEfKGRDya0dH5fgIhAMLOP%2BRPjOFp4MJmrXi8\
        EUUvDSib0K8pBzzkER4gsyZvKogECNP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM\
        3NDIzMTgzODA1Igy9QESIKRpNs8j6gVAq3ANIzNo%2Fm8hSUlD5qoPJzmow6UWi2HxauDY1\
        84GTFbX0M9D1kZN67zWzeVZgJnbbeteLFuDh9IVtMdvNz6%2BEBJcB1na8cWd6zztHBES90\
        PnrIVsPMFfTWN54tlFfb%2BwgqmiBWmI%2Fchji39ZoV3fangdXaWfmDTSb7LjScLIMiR1e\
        bQoJBGBrw%2BoaB%2BhPuk1l4gLc%2BwtekcdEfXtyFgkGex3VatvLYEhvXgKfAQjfDcusF\
        dOLuuHhBuZFVI8FmXyiW1LJuMmDEILKcWHdZKuNy5vdPKRHWp%2F%2FSHWv8kRnuqOQfB%2\
        BV4SYy8Bn0E6IxYAsVerxtwvlIyrTxW0vQC0h1Ny8MkfQvHq8X0gGlQ52HT6vU6yZOXeSJ5\
        qGArgYejh5PikHrHsULokUT1wXlg2QAaFe%2F2lC0bn5FFYRSGCLV2Foen1Rv35xpAieLFv\
        EsXTYzxa%2F8iALmIKEskHQVyDvudJYLXWhWo77F3UGMlTpvnvwefU3NLKcQyxb70m24A%2\
        FcEgBrfjPAFTWAxo7zbxx0RMtcoCMPuL7OGheQRsgo1lGpVHRGveqWlNRAK%2B8Mqf0woKv\
        IUV7p0llOkTnDR7ZBmIQ87VyuMzH0eh7pjvGD5m2HvSO0bYCfeXCmt4MFrwTCPmeG9BjqkA\
        Yd2FwEta8U5kjxrwIQZt82o1EDjG1Fgm47DTFRIaqnlraHndqK3OhIzsh9UVfKjuIpn2rC4\
        PJOlh4P2pQBdCsszzEm0aLhZE27xHOHciSs4tsq0%2Bm9o80CH7hUrroHO0ZqTeoOcJ1%2F\
        9iUv1wTsnJWPR%2F2PvWRKaNYj4dVAPqZcpuqTUzke5oSY3OYfVfxtpUE%2FZIbp5GmasAh\
        Q%2FUkI2lVlwVfAh&X-Amz-Signature=b79d1c4f89389671f0be735a2b6046338d682c\
        2a146f6d9d2bb47f2181ec798a&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-21T11:24:17.064Z"
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
UPDATE_TIME: "2025-02-21T10:26:22.213Z"
EXPIRY_TIME: "2025-02-21T11:26:03.999Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XIYA6QUG%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T102604Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCflvRcQ92Nv8HTDCRqHsT5Ht9YL%2FvYm1EwzO2KD81CLQIhAOvrtdEpMvfKchyKQ2YqSP1Rg80uLqHxezcPlYpf3yC0KogECNP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igwfa8fHq00NkCUPQQAq3AMws4LS9OIXGIOU3Z63jtpib1sE3j3EAopo3mbeglFHUj2KiZB%2BMTlp3jxxFQ2cY7h36m%2BDRDM8siyINGCopEg2htq%2BISKykQ%2FjvDg09PilI5Rl%2B2w07KLXiE0RC7RN0u4KliLAS63DjK4OkhYD5XqY59MO2sVHn1WeP%2FKjZO07rqdwnWChQnVuF4ZmCxxvjk9ec077mL4MdAAld34F3gh12ZVbe4Sg0A%2Fe53rt8PciNRmDXZXXu5ZJ1%2B3kVGIzc4fEl2qCDmDkRUluHy6gHp3u9Voj1VyV2eco%2FU9CRc0fdDI47yp%2BNZYd%2BiHGL3qpaLY2yUsiHCP%2Br66a6qjUVRn0pgUS03GuVonMymFiHWsdIZVOQu%2BrVbwlDmGv%2Fz9S%2BlinlgR8WdzXnVNetEvVknUnwBac%2FuGhxKYy2EHKhMV4rk1zHJ9JZciONJh5ZIZHL5ZEIiFYwOT1E2hWUQ1vb6ORr3bVw2zHwtLJg%2F5skU3lqmf3aCujDarY%2Bb6uX%2FN12cWaEtz7dNvTwWfI1vdNgaVk9Gm%2B8wJ4Bb7uy%2FOkaInAz6%2FifM0UuVVQzNfun%2FymJRX3Ei4CKjutYFLy8kz5MDsEg4yplvjS6AW2s0Ij189dqgtlCM5HnG3LteIE9TDTmeG9BjqkAbOk5zmLHjU%2F0nFk9g%2F4z10K4sJJMDgLeDhIW3vH%2FuC9eOHSUAxHuBb4lyQFFpL7Z2iawC7tJKd4W9GdD1jEn5g3OkjYhgvlLoRIUClShVEoDClNtnHgq%2Bk3oPbPp%2FL0%2FdA8CRAGgdjVW3MdLsReHhMD6iiLLmQUfZp1DkrM%2FmLiwBVXVArUFo23RFSzb0ySrdPZIlN8PIv2WC7C%2Ba%2FzV5WaFrhh&X-Amz-Signature=eec7bbbfcc8ca6120e51d29822c8176e71f87f6e1bad5a014dcee3d02209c1a7&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XIYA6QUG%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T102604Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCflvRcQ92Nv8HTDCRqHsT5Ht9YL%2FvYm1EwzO2KD81CLQIhAOvrtdEpMvfKchyKQ2YqSP1Rg80uLqHxezcPlYpf3yC0KogECNP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igwfa8fHq00NkCUPQQAq3AMws4LS9OIXGIOU3Z63jtpib1sE3j3EAopo3mbeglFHUj2KiZB%2BMTlp3jxxFQ2cY7h36m%2BDRDM8siyINGCopEg2htq%2BISKykQ%2FjvDg09PilI5Rl%2B2w07KLXiE0RC7RN0u4KliLAS63DjK4OkhYD5XqY59MO2sVHn1WeP%2FKjZO07rqdwnWChQnVuF4ZmCxxvjk9ec077mL4MdAAld34F3gh12ZVbe4Sg0A%2Fe53rt8PciNRmDXZXXu5ZJ1%2B3kVGIzc4fEl2qCDmDkRUluHy6gHp3u9Voj1VyV2eco%2FU9CRc0fdDI47yp%2BNZYd%2BiHGL3qpaLY2yUsiHCP%2Br66a6qjUVRn0pgUS03GuVonMymFiHWsdIZVOQu%2BrVbwlDmGv%2Fz9S%2BlinlgR8WdzXnVNetEvVknUnwBac%2FuGhxKYy2EHKhMV4rk1zHJ9JZciONJh5ZIZHL5ZEIiFYwOT1E2hWUQ1vb6ORr3bVw2zHwtLJg%2F5skU3lqmf3aCujDarY%2Bb6uX%2FN12cWaEtz7dNvTwWfI1vdNgaVk9Gm%2B8wJ4Bb7uy%2FOkaInAz6%2FifM0UuVVQzNfun%2FymJRX3Ei4CKjutYFLy8kz5MDsEg4yplvjS6AW2s0Ij189dqgtlCM5HnG3LteIE9TDTmeG9BjqkAbOk5zmLHjU%2F0nFk9g%2F4z10K4sJJMDgLeDhIW3vH%2FuC9eOHSUAxHuBb4lyQFFpL7Z2iawC7tJKd4W9GdD1jEn5g3OkjYhgvlLoRIUClShVEoDClNtnHgq%2Bk3oPbPp%2FL0%2FdA8CRAGgdjVW3MdLsReHhMD6iiLLmQUfZp1DkrM%2FmLiwBVXVArUFo23RFSzb0ySrdPZIlN8PIv2WC7C%2Ba%2FzV5WaFrhh&X-Amz-Signature=8af22001d94eefb0e81d297d8b59da0d598dde72ac485c587171eb2eea299e79&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XIYA6QUG%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T102604Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCflvRcQ92Nv8HTDCRqHsT5Ht9YL%2FvYm1EwzO2KD81CLQIhAOvrtdEpMvfKchyKQ2YqSP1Rg80uLqHxezcPlYpf3yC0KogECNP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igwfa8fHq00NkCUPQQAq3AMws4LS9OIXGIOU3Z63jtpib1sE3j3EAopo3mbeglFHUj2KiZB%2BMTlp3jxxFQ2cY7h36m%2BDRDM8siyINGCopEg2htq%2BISKykQ%2FjvDg09PilI5Rl%2B2w07KLXiE0RC7RN0u4KliLAS63DjK4OkhYD5XqY59MO2sVHn1WeP%2FKjZO07rqdwnWChQnVuF4ZmCxxvjk9ec077mL4MdAAld34F3gh12ZVbe4Sg0A%2Fe53rt8PciNRmDXZXXu5ZJ1%2B3kVGIzc4fEl2qCDmDkRUluHy6gHp3u9Voj1VyV2eco%2FU9CRc0fdDI47yp%2BNZYd%2BiHGL3qpaLY2yUsiHCP%2Br66a6qjUVRn0pgUS03GuVonMymFiHWsdIZVOQu%2BrVbwlDmGv%2Fz9S%2BlinlgR8WdzXnVNetEvVknUnwBac%2FuGhxKYy2EHKhMV4rk1zHJ9JZciONJh5ZIZHL5ZEIiFYwOT1E2hWUQ1vb6ORr3bVw2zHwtLJg%2F5skU3lqmf3aCujDarY%2Bb6uX%2FN12cWaEtz7dNvTwWfI1vdNgaVk9Gm%2B8wJ4Bb7uy%2FOkaInAz6%2FifM0UuVVQzNfun%2FymJRX3Ei4CKjutYFLy8kz5MDsEg4yplvjS6AW2s0Ij189dqgtlCM5HnG3LteIE9TDTmeG9BjqkAbOk5zmLHjU%2F0nFk9g%2F4z10K4sJJMDgLeDhIW3vH%2FuC9eOHSUAxHuBb4lyQFFpL7Z2iawC7tJKd4W9GdD1jEn5g3OkjYhgvlLoRIUClShVEoDClNtnHgq%2Bk3oPbPp%2FL0%2FdA8CRAGgdjVW3MdLsReHhMD6iiLLmQUfZp1DkrM%2FmLiwBVXVArUFo23RFSzb0ySrdPZIlN8PIv2WC7C%2Ba%2FzV5WaFrhh&X-Amz-Signature=6cbb4466e01bd3ff194049afa45a65b7a9472c28a60520cb4e8f97abfc0fdb50&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XIYA6QUG%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T102604Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCflvRcQ92Nv8HTDCRqHsT5Ht9YL%2FvYm1EwzO2KD81CLQIhAOvrtdEpMvfKchyKQ2YqSP1Rg80uLqHxezcPlYpf3yC0KogECNP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igwfa8fHq00NkCUPQQAq3AMws4LS9OIXGIOU3Z63jtpib1sE3j3EAopo3mbeglFHUj2KiZB%2BMTlp3jxxFQ2cY7h36m%2BDRDM8siyINGCopEg2htq%2BISKykQ%2FjvDg09PilI5Rl%2B2w07KLXiE0RC7RN0u4KliLAS63DjK4OkhYD5XqY59MO2sVHn1WeP%2FKjZO07rqdwnWChQnVuF4ZmCxxvjk9ec077mL4MdAAld34F3gh12ZVbe4Sg0A%2Fe53rt8PciNRmDXZXXu5ZJ1%2B3kVGIzc4fEl2qCDmDkRUluHy6gHp3u9Voj1VyV2eco%2FU9CRc0fdDI47yp%2BNZYd%2BiHGL3qpaLY2yUsiHCP%2Br66a6qjUVRn0pgUS03GuVonMymFiHWsdIZVOQu%2BrVbwlDmGv%2Fz9S%2BlinlgR8WdzXnVNetEvVknUnwBac%2FuGhxKYy2EHKhMV4rk1zHJ9JZciONJh5ZIZHL5ZEIiFYwOT1E2hWUQ1vb6ORr3bVw2zHwtLJg%2F5skU3lqmf3aCujDarY%2Bb6uX%2FN12cWaEtz7dNvTwWfI1vdNgaVk9Gm%2B8wJ4Bb7uy%2FOkaInAz6%2FifM0UuVVQzNfun%2FymJRX3Ei4CKjutYFLy8kz5MDsEg4yplvjS6AW2s0Ij189dqgtlCM5HnG3LteIE9TDTmeG9BjqkAbOk5zmLHjU%2F0nFk9g%2F4z10K4sJJMDgLeDhIW3vH%2FuC9eOHSUAxHuBb4lyQFFpL7Z2iawC7tJKd4W9GdD1jEn5g3OkjYhgvlLoRIUClShVEoDClNtnHgq%2Bk3oPbPp%2FL0%2FdA8CRAGgdjVW3MdLsReHhMD6iiLLmQUfZp1DkrM%2FmLiwBVXVArUFo23RFSzb0ySrdPZIlN8PIv2WC7C%2Ba%2FzV5WaFrhh&X-Amz-Signature=16b303fbaf346176994aa344c9be2905720fb732c0800773cb8ff72c34c78674&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XIYA6QUG%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T102604Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCflvRcQ92Nv8HTDCRqHsT5Ht9YL%2FvYm1EwzO2KD81CLQIhAOvrtdEpMvfKchyKQ2YqSP1Rg80uLqHxezcPlYpf3yC0KogECNP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igwfa8fHq00NkCUPQQAq3AMws4LS9OIXGIOU3Z63jtpib1sE3j3EAopo3mbeglFHUj2KiZB%2BMTlp3jxxFQ2cY7h36m%2BDRDM8siyINGCopEg2htq%2BISKykQ%2FjvDg09PilI5Rl%2B2w07KLXiE0RC7RN0u4KliLAS63DjK4OkhYD5XqY59MO2sVHn1WeP%2FKjZO07rqdwnWChQnVuF4ZmCxxvjk9ec077mL4MdAAld34F3gh12ZVbe4Sg0A%2Fe53rt8PciNRmDXZXXu5ZJ1%2B3kVGIzc4fEl2qCDmDkRUluHy6gHp3u9Voj1VyV2eco%2FU9CRc0fdDI47yp%2BNZYd%2BiHGL3qpaLY2yUsiHCP%2Br66a6qjUVRn0pgUS03GuVonMymFiHWsdIZVOQu%2BrVbwlDmGv%2Fz9S%2BlinlgR8WdzXnVNetEvVknUnwBac%2FuGhxKYy2EHKhMV4rk1zHJ9JZciONJh5ZIZHL5ZEIiFYwOT1E2hWUQ1vb6ORr3bVw2zHwtLJg%2F5skU3lqmf3aCujDarY%2Bb6uX%2FN12cWaEtz7dNvTwWfI1vdNgaVk9Gm%2B8wJ4Bb7uy%2FOkaInAz6%2FifM0UuVVQzNfun%2FymJRX3Ei4CKjutYFLy8kz5MDsEg4yplvjS6AW2s0Ij189dqgtlCM5HnG3LteIE9TDTmeG9BjqkAbOk5zmLHjU%2F0nFk9g%2F4z10K4sJJMDgLeDhIW3vH%2FuC9eOHSUAxHuBb4lyQFFpL7Z2iawC7tJKd4W9GdD1jEn5g3OkjYhgvlLoRIUClShVEoDClNtnHgq%2Bk3oPbPp%2FL0%2FdA8CRAGgdjVW3MdLsReHhMD6iiLLmQUfZp1DkrM%2FmLiwBVXVArUFo23RFSzb0ySrdPZIlN8PIv2WC7C%2Ba%2FzV5WaFrhh&X-Amz-Signature=f32a3705214e166af1f3cc4711e9ec4a68d946cfc342331ea07dd5489b069d58&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZXPKEOMU%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T102606Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAnMMC8RzEiY%2BbcZmP3XzcnkOawjOJ%2F8Tz4PYlDbYcrCAiBA%2BL1ENWPOST3zqf9XLsOUWNi4d4nrxnX7x6o6HDndeCqIBAjT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMyhHiy6qwAe0IukAJKtwDlohA0%2FJWEEsyI652dyieLtM%2BrN5zcCA3SqmyDiDEHeHp9H9NGFDiI%2FKrJLK35X%2FNu08xtxFIMHSdct%2Fk7uPrkFJqC4D8NVnMCnuUdwAsrsVGGERXsH5FW1Gi3X7aLeEKVh1NnMzBcpnElo2kHkMamILUOCXlkwqIz2xm0k9Zc1MYD1PZ836jjFKC%2FxKNL376ELplwxMYvoouMUIyqQ8Xn%2F%2FLD9Dzy3EsvJH9aMUWp74vqjLKdSHGrr%2BjWWFpGRhvA0UL3s25tLF3SEsiLvmbLOoWNg%2Fcid5mTQQis1vgCvduVxMBKjHmYWfK%2BKrfDZGOQLMAMnKRruEOTJzGDYwEvoOGYLUajH3CzaEYGgjlXDWsvAQC0%2BFxs61BF%2Fe2rItEHwXhvP6bgo%2Bzstq2yhZxuSAQtZgVkgn%2B4iTqBifmmS%2FZyHbprvolX4bWfTQNYh1tQNYnvZSZ0sHyfBcR8I5buGNxD8dUbEh78GUqdJNXkuhuiwmgEz62lW0WUv0Cg7TVN2iKFY%2F0wCtfJLU4jEloUKemBB68XwWg01fjfxmy8IKhDtOGGAFtK0aUj3nMGlLuCo%2FL1i0wtq2MunAOLGLiDVEaR1zCJ3j13cHezZ6%2FlhyIx5mmZNTN5aMh3u0wj5nhvQY6pgGb%2BxwCaUeo1mzW%2F4UTkpcH5B%2FjRU%2F9aZjErMt%2BuEureeTaFmeCCnwaSRpNkw8QMvpT5tFWs3QpoY6Yw2tEkMuV%2F2JT%2F4aMzXYiCbnjyCaZEx6nw%2BpscmKJw%2BE8mq0kMTk3H56NU9llut8zQ4F%2FnYkHJQBUl12DrskHhhn9iwq3tuKSWuakYURNGM21%2Fr9CzHedxxz7vfmmAZSe4pUKKrVf2bVcgsfC&X-Amz-Signature=7ad1be9fa709aab73831cbb3419b55390538de797f6bab3e48d9ac47e016d257&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667A4LTILP%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T102608Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIA5zq1%2FjJQUtP13w2zDI%2FG4gW%2BlY4nSer6ELoBf6T5q%2FAiB9sRFKCx0WDzz4HTh9meJdbLYzvv2jSkmXGGDJ%2BUiTDCqIBAjT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMLMhe834hZPfOKat2KtwDbK%2Fras9Ca7EfQxtR93csjaoP%2BMGvLfybOPtWcO8eGYHKaJmacPnikEqtK%2BZDnbuWiPeZtYSmRq98GNVfx6Va0%2FSXlAUB7U9fIVGrBQcnaOqoBiJkeUV9AnYvaxAOgyOb0QHdgY6ZJnKHcmItwGGtvwF%2FEhjjMVLkffnPweP67Jis9XClCwuvGaZLJfLaEerA1fk0GpPWsXgYhoqHLPMnNVfxvqfrmpaUGLkK7s9lLE3PMAnPvbUBc7cNpN7Jm56WfCcSq%2FP4tL14eINePC%2FmJTZpT714blCPv3agVNDiVq53CrA%2FMORKX0KdNl%2BgTiN%2FGb8yjsaVtWbTMozFD9CuKK8p3lQOx%2FmEQ2CrVTVkLKIW%2Fx8Pa%2F98FdPxPsgEioSy%2FY6oNXbd01G4khsIZjtGhXMZKTZ18fC0wP83Rn%2BqQbo%2F2G3s4D8%2BYjkxQ5OPB%2Brs9WS8beK2FgFCpwkn9d9OJtDEl2F1DtLRe1%2BLuWkVDwkYTKm3TxClWnqqN3iybayLcNykHvS028461hzy8oZmy7j2e1yT5s6ufiVcLHNnXvCB17AxYq5X7k71aWo%2F4%2ByKA1Mh4sBgtHc3iztOuz55arEz7PONX2bMF8oDdMwO9JovgDv4RBFhWmEkr1swqprhvQY6pgGbaMgEF7cLr7SiWRV2jZGROrQNrYJ%2FOpTIA5iBmonqeKU3zAAZZNEvGPM8eawLmvZJsMwyTVX2JuoMZMB3crXILT2AkSo9DFntpWYburWC1gLv4w6gsOo5ckhq9vpOjZmqACQgvmbfd9cpXvvc%2BSr2FNYMK7HwWkWDl4W4kytCwSfJBGKPZv0AFJV8LYxRSGbjRM25%2FSsD2Qf4fov98ou2kV1%2BEmeI&X-Amz-Signature=88960695912ef0df90cc182641f7f0c32c0a31df48fbbb83bf1173cace627921&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XIYA6QUG%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T102604Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCflvRcQ92Nv8HTDCRqHsT5Ht9YL%2FvYm1EwzO2KD81CLQIhAOvrtdEpMvfKchyKQ2YqSP1Rg80uLqHxezcPlYpf3yC0KogECNP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igwfa8fHq00NkCUPQQAq3AMws4LS9OIXGIOU3Z63jtpib1sE3j3EAopo3mbeglFHUj2KiZB%2BMTlp3jxxFQ2cY7h36m%2BDRDM8siyINGCopEg2htq%2BISKykQ%2FjvDg09PilI5Rl%2B2w07KLXiE0RC7RN0u4KliLAS63DjK4OkhYD5XqY59MO2sVHn1WeP%2FKjZO07rqdwnWChQnVuF4ZmCxxvjk9ec077mL4MdAAld34F3gh12ZVbe4Sg0A%2Fe53rt8PciNRmDXZXXu5ZJ1%2B3kVGIzc4fEl2qCDmDkRUluHy6gHp3u9Voj1VyV2eco%2FU9CRc0fdDI47yp%2BNZYd%2BiHGL3qpaLY2yUsiHCP%2Br66a6qjUVRn0pgUS03GuVonMymFiHWsdIZVOQu%2BrVbwlDmGv%2Fz9S%2BlinlgR8WdzXnVNetEvVknUnwBac%2FuGhxKYy2EHKhMV4rk1zHJ9JZciONJh5ZIZHL5ZEIiFYwOT1E2hWUQ1vb6ORr3bVw2zHwtLJg%2F5skU3lqmf3aCujDarY%2Bb6uX%2FN12cWaEtz7dNvTwWfI1vdNgaVk9Gm%2B8wJ4Bb7uy%2FOkaInAz6%2FifM0UuVVQzNfun%2FymJRX3Ei4CKjutYFLy8kz5MDsEg4yplvjS6AW2s0Ij189dqgtlCM5HnG3LteIE9TDTmeG9BjqkAbOk5zmLHjU%2F0nFk9g%2F4z10K4sJJMDgLeDhIW3vH%2FuC9eOHSUAxHuBb4lyQFFpL7Z2iawC7tJKd4W9GdD1jEn5g3OkjYhgvlLoRIUClShVEoDClNtnHgq%2Bk3oPbPp%2FL0%2FdA8CRAGgdjVW3MdLsReHhMD6iiLLmQUfZp1DkrM%2FmLiwBVXVArUFo23RFSzb0ySrdPZIlN8PIv2WC7C%2Ba%2FzV5WaFrhh&X-Amz-Signature=e8c0f9e5b12dd45159703605bdacce2cb243f942b8a3acf806bbc858e641f39f&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XIYA6QUG%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T102604Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCflvRcQ92Nv8HTDCRqHsT5Ht9YL%2FvYm1EwzO2KD81CLQIhAOvrtdEpMvfKchyKQ2YqSP1Rg80uLqHxezcPlYpf3yC0KogECNP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igwfa8fHq00NkCUPQQAq3AMws4LS9OIXGIOU3Z63jtpib1sE3j3EAopo3mbeglFHUj2KiZB%2BMTlp3jxxFQ2cY7h36m%2BDRDM8siyINGCopEg2htq%2BISKykQ%2FjvDg09PilI5Rl%2B2w07KLXiE0RC7RN0u4KliLAS63DjK4OkhYD5XqY59MO2sVHn1WeP%2FKjZO07rqdwnWChQnVuF4ZmCxxvjk9ec077mL4MdAAld34F3gh12ZVbe4Sg0A%2Fe53rt8PciNRmDXZXXu5ZJ1%2B3kVGIzc4fEl2qCDmDkRUluHy6gHp3u9Voj1VyV2eco%2FU9CRc0fdDI47yp%2BNZYd%2BiHGL3qpaLY2yUsiHCP%2Br66a6qjUVRn0pgUS03GuVonMymFiHWsdIZVOQu%2BrVbwlDmGv%2Fz9S%2BlinlgR8WdzXnVNetEvVknUnwBac%2FuGhxKYy2EHKhMV4rk1zHJ9JZciONJh5ZIZHL5ZEIiFYwOT1E2hWUQ1vb6ORr3bVw2zHwtLJg%2F5skU3lqmf3aCujDarY%2Bb6uX%2FN12cWaEtz7dNvTwWfI1vdNgaVk9Gm%2B8wJ4Bb7uy%2FOkaInAz6%2FifM0UuVVQzNfun%2FymJRX3Ei4CKjutYFLy8kz5MDsEg4yplvjS6AW2s0Ij189dqgtlCM5HnG3LteIE9TDTmeG9BjqkAbOk5zmLHjU%2F0nFk9g%2F4z10K4sJJMDgLeDhIW3vH%2FuC9eOHSUAxHuBb4lyQFFpL7Z2iawC7tJKd4W9GdD1jEn5g3OkjYhgvlLoRIUClShVEoDClNtnHgq%2Bk3oPbPp%2FL0%2FdA8CRAGgdjVW3MdLsReHhMD6iiLLmQUfZp1DkrM%2FmLiwBVXVArUFo23RFSzb0ySrdPZIlN8PIv2WC7C%2Ba%2FzV5WaFrhh&X-Amz-Signature=357ac2aea12be85639266e5e18b83f35bf9680665771beb8386b43f69f012f58&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XIYA6QUG%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T102604Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCflvRcQ92Nv8HTDCRqHsT5Ht9YL%2FvYm1EwzO2KD81CLQIhAOvrtdEpMvfKchyKQ2YqSP1Rg80uLqHxezcPlYpf3yC0KogECNP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igwfa8fHq00NkCUPQQAq3AMws4LS9OIXGIOU3Z63jtpib1sE3j3EAopo3mbeglFHUj2KiZB%2BMTlp3jxxFQ2cY7h36m%2BDRDM8siyINGCopEg2htq%2BISKykQ%2FjvDg09PilI5Rl%2B2w07KLXiE0RC7RN0u4KliLAS63DjK4OkhYD5XqY59MO2sVHn1WeP%2FKjZO07rqdwnWChQnVuF4ZmCxxvjk9ec077mL4MdAAld34F3gh12ZVbe4Sg0A%2Fe53rt8PciNRmDXZXXu5ZJ1%2B3kVGIzc4fEl2qCDmDkRUluHy6gHp3u9Voj1VyV2eco%2FU9CRc0fdDI47yp%2BNZYd%2BiHGL3qpaLY2yUsiHCP%2Br66a6qjUVRn0pgUS03GuVonMymFiHWsdIZVOQu%2BrVbwlDmGv%2Fz9S%2BlinlgR8WdzXnVNetEvVknUnwBac%2FuGhxKYy2EHKhMV4rk1zHJ9JZciONJh5ZIZHL5ZEIiFYwOT1E2hWUQ1vb6ORr3bVw2zHwtLJg%2F5skU3lqmf3aCujDarY%2Bb6uX%2FN12cWaEtz7dNvTwWfI1vdNgaVk9Gm%2B8wJ4Bb7uy%2FOkaInAz6%2FifM0UuVVQzNfun%2FymJRX3Ei4CKjutYFLy8kz5MDsEg4yplvjS6AW2s0Ij189dqgtlCM5HnG3LteIE9TDTmeG9BjqkAbOk5zmLHjU%2F0nFk9g%2F4z10K4sJJMDgLeDhIW3vH%2FuC9eOHSUAxHuBb4lyQFFpL7Z2iawC7tJKd4W9GdD1jEn5g3OkjYhgvlLoRIUClShVEoDClNtnHgq%2Bk3oPbPp%2FL0%2FdA8CRAGgdjVW3MdLsReHhMD6iiLLmQUfZp1DkrM%2FmLiwBVXVArUFo23RFSzb0ySrdPZIlN8PIv2WC7C%2Ba%2FzV5WaFrhh&X-Amz-Signature=20e66b58d8d1687a5295a9a1f4dfbdd23eeea797d9dcd3e2db56c821b2f0ec1a&X-Amz-SignedHeaders=host&x-id=GetObject)


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

