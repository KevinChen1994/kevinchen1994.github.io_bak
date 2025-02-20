---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4665MRE27RD%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250220T083042Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEJD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCUTnpAQN0dnd%2F56\
  OQsaWBQ5Osx%2F2SuJBqKcVfgaC8pGwIgNrjREGzCSayZqk8Lx26yobZgDDAuqPRFRtcpg0mI1Jsq\
  iAQIuf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDA%2BhwsySiVL4KDx\
  RzircAyBWK72KNCWHRJj15kcA3PHt8FjB3GarR23wne5usoIoz7zlzjsvBfWZBHAK4YsDHyB6Lt%2\
  FYdUj9ZgvAf8BthPt%2Bo8mHwZeIZb8mMPduhpe2E1thDbZGVWBrdrhG91hwgHW31IrIjg5X46im2\
  lbd52Pjqyxjcuo%2BeT6d04zUsqNJYf9ciJltchxpnNrVvrVZIAKS%2FjOAAlNxuVlnVFV7Ru4%2F\
  4Zz7rX%2FduJp1F9epJbGxIhCifJPj8kFPNE8Kkdpptx7KA7zujoNVnFCRaIKOZg94OvlZKUCtmx3\
  B%2FMooZ7mlGmxjEJjctlNDg2BEyxbEBuB7zwJU7n9jCzOMGsHEKMvtHMSbwCrzEa6eixmQagR0E9\
  w5m2Rg9%2F0e2rA4pbbvyNyekCFkogLfto8aF3r5fvcxwLLwAoKe%2Fa3ip9w%2FGV8ySXVqB9cKf\
  WcNvzqN%2BnTFve48qyBeuGLgZ10g72nITquIygOehKmA%2FQPq67Z3HC5hpNcY4437K8ta6%2BTp\
  san9rDP4a5YNSquxDHBRjmtloZvbuONwHXsq7Jls8yFFAVwqmotEUBHKBoA68f7FL1Y1ErBfoaH8U\
  SocaZl0%2BMHzC2%2B%2B7g4pmyHfgtmdhBY%2BYca5rOVR0xyooR0c4rraMLG8270GOqUBtiKvXI\
  OsdZLoHLeZkVhC5lQkg9kGGNzYP%2BiWg6G5wDB7vm%2BQQ9oWvMJm1tw73M%2BLNqlbMb7b3gkzW\
  m4Z7%2Fw7eV4b91h8oujS9TpMq4%2FZ2yOaJ7gM79kJpP5%2FRTbLxxfifz82XIFn4ezzHhy2kB1Z\
  xmkt3JgA9A9yJyfwsFZSuv0XmBqDK20h%2BMVV%2BBQ9xl1%2BYW%2BN1A%2F5MGy%2BALCxSZxtU\
  j1YOVsl&X-Amz-Signature=0709c2faf34767a4c8cf0f6c312176ffdf0d3f04e803e4d4d36fa\
  4d87fa0b294&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4663AOEMSOW%2F20250220%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250220T082920Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEJD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQ\
        CIE9lL0Se5rubGZhl5I0rMMXCfNCyi2j1Ubwy8dxKl4vXAiBzT4u87vSZNugv1b3awTaTcz\
        Fn3ZKXuf%2FxPI5TkgKCXSqIBAi5%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQ\
        yMzE4MzgwNSIMh%2Fv75fIkwWC27c6yKtwD1WxMDZQenR9cdiqhetC89TZ%2Bx2yWZHFZ3S\
        Lo%2BeYh2LUUpkE2D2aCmMKBAZ714gjXBLX%2Btxd%2FHgCMzCeuAxRwwOdmPHEOyVUsGu6\
        sXgMfJHZw8lRFcfJQK333Cigr2bfrR%2FrNpaLrE%2B%2BNR83vq5P2Y7LMo%2BIPY9FWrE\
        YFDx0fao8hD6%2FrNw9DSyuAk7%2FzFFREMLvk3nLpE58EUy3LIlsDSvXCQ1cqaDV9z5%2B\
        DDYqySD7kB%2FIGKOxAhHD1i8ROsQ8vwzbHEmau0leMS%2FP7%2B6lQn55Hi%2BlCh5BeCj\
        sm74HwSN%2BoXAOsY3LuLR6BS6KUEaJJUtbzjDgqXoT6kOaFlzND7PJgWUIZKglWf0mv7d6\
        4lSeEbR%2Fz4ZYyyWJ%2BzlfXY6xTRfzHKhJzZUPOwnTEgHJE%2Bg3QtxzMFbp31vQSbmzB\
        IaULN%2BUr1ASvC1HscHpV34hwQCVqs8NFbCLtTX3U%2F0L3YijIBZB6wbfBkeknxa7oTtT\
        K%2Be89PoAifhF6eT6mavwZZbsn%2B4BRLsGPWuDr893qcH%2FdkDlFVggWrzcYQTbOfa96\
        nKblQt38rHn7Omv%2F7tqPbnxYrgLz8R%2FgLgJut0zzgeghBALv1wyyJwIaqxCTsOig3Vp\
        %2FRQU9CAsTbmswi7zbvQY6pgGO7FUK12OkbkGMFh%2FlAnreQYSTOkosFPw2hnY6tk7HeZ\
        wi4fZQh4PKrv7yF7CyRTo3jTZgZzDkeGw3Q4PIUoKTJcuG1cEUGEkvbXTDqXKwjwk%2BrBC\
        vpPA4FrFqBFs8%2FqjpfU7X10A2k5ezypZU%2F3CaIbyY4lYv11%2BG9ewpa3RH9gNapeAY\
        0COVoyiA5g9JbujyWKC0%2FoiiXhCeB%2FHQwNJqQy2UKFmD&X-Amz-Signature=a0b4de\
        02543ac113d746f19907f3317a43cc7ab4ba5a10bb1e18631d8c29629b&X-Amz-Signed\
        Headers=host&x-id=GetObject"
      expiry_time: "2025-02-20T09:29:20.196Z"
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
UPDATE_TIME: "2025-02-20T08:30:51.108Z"
EXPIRY_TIME: "2025-02-20T09:30:39.850Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RYZKYSO7%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T083040Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCPkjfJLrb3Tk0bItZq4NuVz1J6JqZdxpljbD4MdvdZCQIhAMxyrQKSwpSZnNvDY2j9g2DOb9se5nj%2Fd9xtH%2FZroRYOKogECLn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwjbzFhDRP9uXV7GAoq3AP42PxdOp8UTabGW%2FCdP8fF4CnlXDdfWcSlSSvirVcGCWFvI0MQAlJoWAhfkdJCxDp%2FN4OnWtOLvp5euT%2Fu32%2BZmJyYLv2evY88mdKqmXRTYsu%2FaG0mOYvOl76Ge6fahbBFKB4fb8ig7aQUbFn2D1G1u3eozDj0q0I1h3CHvjLi%2FRFesKXouEldBO6HBAlUYlQJzoFsCFSvstixzPJ6RLxylCA3EWRg5CSLVJHa49J%2FAD3IhZLGBhe2Fth%2BSVaOvkEuLBbWknTpV%2BwU%2Bnosy%2BVChUownenCNZALghTSkkxZWgWx6EAKFDtd0HvNfkC2k%2BxbOmczOI0ylszFELN3RMjOcTQ4toKciGGDqE5zLNc3UO2cgao6rAGpGvESqsmeuLbT8eNn5pTHIJnYjO1hVFjSQFVvBkCd%2BXRxVmfubHIUnMwwEOTzxBXyAx6IpIrjLuA26f7ig6V1ARaUJ%2BQVaReeaaihRbJICDOu2foTfp2Z9vin%2F0c4OxNc6bCbpEAjVoipWenhbu%2BSXRHkdGSuoWHwYKJj0g7WTBstKNnH86LZZKk2uvjM5ypfpS9wJGdL%2BBHRAzH74yXC%2BUjhBq7JTCb3MNpiTypvh36LFKZlsAtJ1FEZMo5eLuDjz3N1DzCgvNu9BjqkAdS1Wf74hD9DcHGBHqtxRi0EYE%2BzwlH%2Frgna048CR4oj77t5PjDADI%2FK5upfCy1TVpNfMAdtb%2B9Vj4%2BLACmrcMmPbG2%2BkIeLI1zl4YKnHnWrE8%2Fw%2Be%2BiL8DDD5cfRPiC%2Bld6RUyAzAe9j2sZzfmWsWyMXmdazLEYUlTNdaa7yVFZYznpONaOSgWETlx%2FaEYi0mZVWhAy8nBbL%2B9hm15zegLmlAPG&X-Amz-Signature=d2d00408399bdef8dbcc1ae06d72141c0b3e8154229b066d1c307e83f9da7983&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RYZKYSO7%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T083040Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCPkjfJLrb3Tk0bItZq4NuVz1J6JqZdxpljbD4MdvdZCQIhAMxyrQKSwpSZnNvDY2j9g2DOb9se5nj%2Fd9xtH%2FZroRYOKogECLn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwjbzFhDRP9uXV7GAoq3AP42PxdOp8UTabGW%2FCdP8fF4CnlXDdfWcSlSSvirVcGCWFvI0MQAlJoWAhfkdJCxDp%2FN4OnWtOLvp5euT%2Fu32%2BZmJyYLv2evY88mdKqmXRTYsu%2FaG0mOYvOl76Ge6fahbBFKB4fb8ig7aQUbFn2D1G1u3eozDj0q0I1h3CHvjLi%2FRFesKXouEldBO6HBAlUYlQJzoFsCFSvstixzPJ6RLxylCA3EWRg5CSLVJHa49J%2FAD3IhZLGBhe2Fth%2BSVaOvkEuLBbWknTpV%2BwU%2Bnosy%2BVChUownenCNZALghTSkkxZWgWx6EAKFDtd0HvNfkC2k%2BxbOmczOI0ylszFELN3RMjOcTQ4toKciGGDqE5zLNc3UO2cgao6rAGpGvESqsmeuLbT8eNn5pTHIJnYjO1hVFjSQFVvBkCd%2BXRxVmfubHIUnMwwEOTzxBXyAx6IpIrjLuA26f7ig6V1ARaUJ%2BQVaReeaaihRbJICDOu2foTfp2Z9vin%2F0c4OxNc6bCbpEAjVoipWenhbu%2BSXRHkdGSuoWHwYKJj0g7WTBstKNnH86LZZKk2uvjM5ypfpS9wJGdL%2BBHRAzH74yXC%2BUjhBq7JTCb3MNpiTypvh36LFKZlsAtJ1FEZMo5eLuDjz3N1DzCgvNu9BjqkAdS1Wf74hD9DcHGBHqtxRi0EYE%2BzwlH%2Frgna048CR4oj77t5PjDADI%2FK5upfCy1TVpNfMAdtb%2B9Vj4%2BLACmrcMmPbG2%2BkIeLI1zl4YKnHnWrE8%2Fw%2Be%2BiL8DDD5cfRPiC%2Bld6RUyAzAe9j2sZzfmWsWyMXmdazLEYUlTNdaa7yVFZYznpONaOSgWETlx%2FaEYi0mZVWhAy8nBbL%2B9hm15zegLmlAPG&X-Amz-Signature=caab71764434847a97acbcb892d9c472bba92e2198a63c5400c0dd3bf84b5f3e&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RYZKYSO7%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T083040Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCPkjfJLrb3Tk0bItZq4NuVz1J6JqZdxpljbD4MdvdZCQIhAMxyrQKSwpSZnNvDY2j9g2DOb9se5nj%2Fd9xtH%2FZroRYOKogECLn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwjbzFhDRP9uXV7GAoq3AP42PxdOp8UTabGW%2FCdP8fF4CnlXDdfWcSlSSvirVcGCWFvI0MQAlJoWAhfkdJCxDp%2FN4OnWtOLvp5euT%2Fu32%2BZmJyYLv2evY88mdKqmXRTYsu%2FaG0mOYvOl76Ge6fahbBFKB4fb8ig7aQUbFn2D1G1u3eozDj0q0I1h3CHvjLi%2FRFesKXouEldBO6HBAlUYlQJzoFsCFSvstixzPJ6RLxylCA3EWRg5CSLVJHa49J%2FAD3IhZLGBhe2Fth%2BSVaOvkEuLBbWknTpV%2BwU%2Bnosy%2BVChUownenCNZALghTSkkxZWgWx6EAKFDtd0HvNfkC2k%2BxbOmczOI0ylszFELN3RMjOcTQ4toKciGGDqE5zLNc3UO2cgao6rAGpGvESqsmeuLbT8eNn5pTHIJnYjO1hVFjSQFVvBkCd%2BXRxVmfubHIUnMwwEOTzxBXyAx6IpIrjLuA26f7ig6V1ARaUJ%2BQVaReeaaihRbJICDOu2foTfp2Z9vin%2F0c4OxNc6bCbpEAjVoipWenhbu%2BSXRHkdGSuoWHwYKJj0g7WTBstKNnH86LZZKk2uvjM5ypfpS9wJGdL%2BBHRAzH74yXC%2BUjhBq7JTCb3MNpiTypvh36LFKZlsAtJ1FEZMo5eLuDjz3N1DzCgvNu9BjqkAdS1Wf74hD9DcHGBHqtxRi0EYE%2BzwlH%2Frgna048CR4oj77t5PjDADI%2FK5upfCy1TVpNfMAdtb%2B9Vj4%2BLACmrcMmPbG2%2BkIeLI1zl4YKnHnWrE8%2Fw%2Be%2BiL8DDD5cfRPiC%2Bld6RUyAzAe9j2sZzfmWsWyMXmdazLEYUlTNdaa7yVFZYznpONaOSgWETlx%2FaEYi0mZVWhAy8nBbL%2B9hm15zegLmlAPG&X-Amz-Signature=f5a5a2ce6e3a5febf42e748f7589ea5941a349936ac63f5a665b1015538ea566&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RYZKYSO7%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T083040Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCPkjfJLrb3Tk0bItZq4NuVz1J6JqZdxpljbD4MdvdZCQIhAMxyrQKSwpSZnNvDY2j9g2DOb9se5nj%2Fd9xtH%2FZroRYOKogECLn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwjbzFhDRP9uXV7GAoq3AP42PxdOp8UTabGW%2FCdP8fF4CnlXDdfWcSlSSvirVcGCWFvI0MQAlJoWAhfkdJCxDp%2FN4OnWtOLvp5euT%2Fu32%2BZmJyYLv2evY88mdKqmXRTYsu%2FaG0mOYvOl76Ge6fahbBFKB4fb8ig7aQUbFn2D1G1u3eozDj0q0I1h3CHvjLi%2FRFesKXouEldBO6HBAlUYlQJzoFsCFSvstixzPJ6RLxylCA3EWRg5CSLVJHa49J%2FAD3IhZLGBhe2Fth%2BSVaOvkEuLBbWknTpV%2BwU%2Bnosy%2BVChUownenCNZALghTSkkxZWgWx6EAKFDtd0HvNfkC2k%2BxbOmczOI0ylszFELN3RMjOcTQ4toKciGGDqE5zLNc3UO2cgao6rAGpGvESqsmeuLbT8eNn5pTHIJnYjO1hVFjSQFVvBkCd%2BXRxVmfubHIUnMwwEOTzxBXyAx6IpIrjLuA26f7ig6V1ARaUJ%2BQVaReeaaihRbJICDOu2foTfp2Z9vin%2F0c4OxNc6bCbpEAjVoipWenhbu%2BSXRHkdGSuoWHwYKJj0g7WTBstKNnH86LZZKk2uvjM5ypfpS9wJGdL%2BBHRAzH74yXC%2BUjhBq7JTCb3MNpiTypvh36LFKZlsAtJ1FEZMo5eLuDjz3N1DzCgvNu9BjqkAdS1Wf74hD9DcHGBHqtxRi0EYE%2BzwlH%2Frgna048CR4oj77t5PjDADI%2FK5upfCy1TVpNfMAdtb%2B9Vj4%2BLACmrcMmPbG2%2BkIeLI1zl4YKnHnWrE8%2Fw%2Be%2BiL8DDD5cfRPiC%2Bld6RUyAzAe9j2sZzfmWsWyMXmdazLEYUlTNdaa7yVFZYznpONaOSgWETlx%2FaEYi0mZVWhAy8nBbL%2B9hm15zegLmlAPG&X-Amz-Signature=d0fe41a647074219ddf14612643682b543eb4e279bd921742f440e5a4913c825&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RYZKYSO7%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T083040Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCPkjfJLrb3Tk0bItZq4NuVz1J6JqZdxpljbD4MdvdZCQIhAMxyrQKSwpSZnNvDY2j9g2DOb9se5nj%2Fd9xtH%2FZroRYOKogECLn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwjbzFhDRP9uXV7GAoq3AP42PxdOp8UTabGW%2FCdP8fF4CnlXDdfWcSlSSvirVcGCWFvI0MQAlJoWAhfkdJCxDp%2FN4OnWtOLvp5euT%2Fu32%2BZmJyYLv2evY88mdKqmXRTYsu%2FaG0mOYvOl76Ge6fahbBFKB4fb8ig7aQUbFn2D1G1u3eozDj0q0I1h3CHvjLi%2FRFesKXouEldBO6HBAlUYlQJzoFsCFSvstixzPJ6RLxylCA3EWRg5CSLVJHa49J%2FAD3IhZLGBhe2Fth%2BSVaOvkEuLBbWknTpV%2BwU%2Bnosy%2BVChUownenCNZALghTSkkxZWgWx6EAKFDtd0HvNfkC2k%2BxbOmczOI0ylszFELN3RMjOcTQ4toKciGGDqE5zLNc3UO2cgao6rAGpGvESqsmeuLbT8eNn5pTHIJnYjO1hVFjSQFVvBkCd%2BXRxVmfubHIUnMwwEOTzxBXyAx6IpIrjLuA26f7ig6V1ARaUJ%2BQVaReeaaihRbJICDOu2foTfp2Z9vin%2F0c4OxNc6bCbpEAjVoipWenhbu%2BSXRHkdGSuoWHwYKJj0g7WTBstKNnH86LZZKk2uvjM5ypfpS9wJGdL%2BBHRAzH74yXC%2BUjhBq7JTCb3MNpiTypvh36LFKZlsAtJ1FEZMo5eLuDjz3N1DzCgvNu9BjqkAdS1Wf74hD9DcHGBHqtxRi0EYE%2BzwlH%2Frgna048CR4oj77t5PjDADI%2FK5upfCy1TVpNfMAdtb%2B9Vj4%2BLACmrcMmPbG2%2BkIeLI1zl4YKnHnWrE8%2Fw%2Be%2BiL8DDD5cfRPiC%2Bld6RUyAzAe9j2sZzfmWsWyMXmdazLEYUlTNdaa7yVFZYznpONaOSgWETlx%2FaEYi0mZVWhAy8nBbL%2B9hm15zegLmlAPG&X-Amz-Signature=2a1c3cc4ddabd1dd7bacf9434e136af8164a36086c2ad5eff53f7f4d7bd2adbc&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YSW2DSXZ%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T083041Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIGUXtuKfzXcTHzNV%2F43gXFzAk6qNIsKEaZw7gl7Ylr7KAiBACwLJUVDEtMsUM5RFWhUZf9fBGKWivrFmEUXeYJPqkyqIBAi5%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM3uxB3ITOL%2Bm6qJaxKtwDMoLjsPC8U0RixBn9DkUYpqazX2OIxuWtjJKpp7MAHdQI9x6oOwMYa0QAcycZWJGVR0k8hyJos7GlaRXHEAwYdoeAyGAHxZZJnKF5Wd8gvH19Nc5fBNqx26Y3XSKwamjJJ%2FO%2BGgrbwkO1EysGXlrjQtzTRuO94Bjgn9wtlLB%2B376%2BXTR36IjkAtcWa%2Bf%2FiQbHuZysrU2yFqxuiMJpxVe7bhqOOLPkgnxMtJdakkSM83lB8uzB%2BZDRwLlN814EK80ArIbEOiEEc586abH%2BBSUDic8nDCNfP8eWVnhNk6myrxqF9jxTPTmcaVj3baeCvC%2Fg1akkctEIgid3OQuvi2vFAYjOfD7HVAb7B7aFY61B6Y4kH0EHKvIZIR9RUsJ6%2BctxY1%2Fj3hss%2FDaetEKwso%2BcpLPsuxoMwNLzs0TlGRoryNCGq7gnOlG4qWnj74FAExs7QdHm0yeULY%2BNStdFYCMrHCEyKr8BGg16m8RKLSXZqNarjsgBJmjA5Oa4LL60%2BgReeMJA5wjXO5ZjRCqdieO0c6iO%2F1lLszCfvKVKkFOuB3r0mr8VVz3tZyJk6v4vKgEKJLyQzG7T4ve0mlhCpWYXc3GQVuvxHvQm46fXjqbAiaNrJKfCd1%2Fxzj%2BzrH8wgbzbvQY6pgGpLXxuI3vg2i2GGDjHOUC1RDsXJpp1Qz32DPZyxymoos6amVN%2F%2FDoWAAThbXAQO2I1NNhGo8dxcbq7K%2BzGCsWPBJoDXioItArgHfkdoMMtMbMwlZ4CXKt%2Bu3zDIsUtuYGUnnKwwrRequetLWzR6PsKFIe9vKaq4bxQLZOJMtUgR75hcjgafsedzaIG1SOtPQmg%2FCPQeYhTJ0sxr4WzD%2BMuUh1DAdy3&X-Amz-Signature=9efa5de557cf6172099883014b87a7d8ac82f83da73460a86b46ac61be9a64b7&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664QY3DNMD%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T083041Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIFK9nA8U%2F1qu82oglDRqmgwBcA54Oh%2FMzSyqtydFzdHXAiBaxUZzx6WRXg41vwRw3VCP4Kfdl7eAvP1%2BiwWkWUN2TiqIBAi5%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMnrjn0pWzrF7FLJzkKtwDdgDXNPOBABotg7Za1L5kdN%2Bm4lpVevk%2FUbaMCuIO2v%2FwB91cym5Wrywdjf6TRhdc4KyzoJdo1U5KHRqc%2BhOD4F9MDb77G0igRTMLsTmk6sXkxSaCy5fiSDl6Ji84VtB9JbVNShHsp%2B1s0KxRGDTw6E6s2TGHGyG2CCHqKXL3mMPmOiwFxgilBQxQLmu7k%2BqK7n5LzkBGTDuDXb07mwaMpLRCiOf2RPHzU9gMDJ0WEPnlkypvlbCmHgzrz3KPt2N1lWup4akWzt7vsvhynFxNt1AmXOC95C8iLFIPg%2ByKioUz59vrIN1CCCrpho1FVivdQC%2FfbnOV6VfEf4HT2q5GUjH0CUj9HS6UoObiCrM0PxWdnkXxPgVnl6RGmjoyDqNLIeamuNEavcVV6wjtlOtf23%2BHaXZejgwxW%2FfN0CJikMLFmLxErVq28pHCtU7jRSBHa0xwT0%2BT%2FYEQ7d6t9xa0JOTGVLAP3y5bYzKPBi5T2Dn18jXUrM%2Bew6YQ7kfjH0R4Su9Lvw0P%2FeJB3YfuRXOQZGC3LypujiteZ45DqDO7MqvcjtdKTW%2FjJ8WlnZG2Y9DEUQ%2FXSOSSw4wBXpLfYjYrvXahxWlzPAYiKxEo42QrsjsZLYIVPK%2FQOf7PlxswsbzbvQY6pgFfer4e8%2Fn2NuwUo%2Fu2h%2Fso0eyAjKSLD8j8xPEKK0vUaYjxa5gspTaJH0o2iiaWBl9u6H9A0Gx%2BiunT50DsB1TgYqfYL0vd2%2F04Njke4PeqrUCoEWEad8sOfvZ0Xn5uXuH7UYHyBmrbNl8XK0FPVjnRZzljAEAsH97jy33QGaveO5fdtS0syNqlQSHkfOCbNA08H33v1rOMqdV3b%2FUdXCXtL%2BWyG9WK&X-Amz-Signature=1cd2d67abc3e90ec97f3bdfa386f9ef6a177df30d10685e3fcb17101e1f474de&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RYZKYSO7%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T083040Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCPkjfJLrb3Tk0bItZq4NuVz1J6JqZdxpljbD4MdvdZCQIhAMxyrQKSwpSZnNvDY2j9g2DOb9se5nj%2Fd9xtH%2FZroRYOKogECLn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwjbzFhDRP9uXV7GAoq3AP42PxdOp8UTabGW%2FCdP8fF4CnlXDdfWcSlSSvirVcGCWFvI0MQAlJoWAhfkdJCxDp%2FN4OnWtOLvp5euT%2Fu32%2BZmJyYLv2evY88mdKqmXRTYsu%2FaG0mOYvOl76Ge6fahbBFKB4fb8ig7aQUbFn2D1G1u3eozDj0q0I1h3CHvjLi%2FRFesKXouEldBO6HBAlUYlQJzoFsCFSvstixzPJ6RLxylCA3EWRg5CSLVJHa49J%2FAD3IhZLGBhe2Fth%2BSVaOvkEuLBbWknTpV%2BwU%2Bnosy%2BVChUownenCNZALghTSkkxZWgWx6EAKFDtd0HvNfkC2k%2BxbOmczOI0ylszFELN3RMjOcTQ4toKciGGDqE5zLNc3UO2cgao6rAGpGvESqsmeuLbT8eNn5pTHIJnYjO1hVFjSQFVvBkCd%2BXRxVmfubHIUnMwwEOTzxBXyAx6IpIrjLuA26f7ig6V1ARaUJ%2BQVaReeaaihRbJICDOu2foTfp2Z9vin%2F0c4OxNc6bCbpEAjVoipWenhbu%2BSXRHkdGSuoWHwYKJj0g7WTBstKNnH86LZZKk2uvjM5ypfpS9wJGdL%2BBHRAzH74yXC%2BUjhBq7JTCb3MNpiTypvh36LFKZlsAtJ1FEZMo5eLuDjz3N1DzCgvNu9BjqkAdS1Wf74hD9DcHGBHqtxRi0EYE%2BzwlH%2Frgna048CR4oj77t5PjDADI%2FK5upfCy1TVpNfMAdtb%2B9Vj4%2BLACmrcMmPbG2%2BkIeLI1zl4YKnHnWrE8%2Fw%2Be%2BiL8DDD5cfRPiC%2Bld6RUyAzAe9j2sZzfmWsWyMXmdazLEYUlTNdaa7yVFZYznpONaOSgWETlx%2FaEYi0mZVWhAy8nBbL%2B9hm15zegLmlAPG&X-Amz-Signature=abbf160659e68d48d36cbfe14e1547446bbd79863f9ae9db0b13bc2f3c1bbd02&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RYZKYSO7%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T083040Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCPkjfJLrb3Tk0bItZq4NuVz1J6JqZdxpljbD4MdvdZCQIhAMxyrQKSwpSZnNvDY2j9g2DOb9se5nj%2Fd9xtH%2FZroRYOKogECLn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwjbzFhDRP9uXV7GAoq3AP42PxdOp8UTabGW%2FCdP8fF4CnlXDdfWcSlSSvirVcGCWFvI0MQAlJoWAhfkdJCxDp%2FN4OnWtOLvp5euT%2Fu32%2BZmJyYLv2evY88mdKqmXRTYsu%2FaG0mOYvOl76Ge6fahbBFKB4fb8ig7aQUbFn2D1G1u3eozDj0q0I1h3CHvjLi%2FRFesKXouEldBO6HBAlUYlQJzoFsCFSvstixzPJ6RLxylCA3EWRg5CSLVJHa49J%2FAD3IhZLGBhe2Fth%2BSVaOvkEuLBbWknTpV%2BwU%2Bnosy%2BVChUownenCNZALghTSkkxZWgWx6EAKFDtd0HvNfkC2k%2BxbOmczOI0ylszFELN3RMjOcTQ4toKciGGDqE5zLNc3UO2cgao6rAGpGvESqsmeuLbT8eNn5pTHIJnYjO1hVFjSQFVvBkCd%2BXRxVmfubHIUnMwwEOTzxBXyAx6IpIrjLuA26f7ig6V1ARaUJ%2BQVaReeaaihRbJICDOu2foTfp2Z9vin%2F0c4OxNc6bCbpEAjVoipWenhbu%2BSXRHkdGSuoWHwYKJj0g7WTBstKNnH86LZZKk2uvjM5ypfpS9wJGdL%2BBHRAzH74yXC%2BUjhBq7JTCb3MNpiTypvh36LFKZlsAtJ1FEZMo5eLuDjz3N1DzCgvNu9BjqkAdS1Wf74hD9DcHGBHqtxRi0EYE%2BzwlH%2Frgna048CR4oj77t5PjDADI%2FK5upfCy1TVpNfMAdtb%2B9Vj4%2BLACmrcMmPbG2%2BkIeLI1zl4YKnHnWrE8%2Fw%2Be%2BiL8DDD5cfRPiC%2Bld6RUyAzAe9j2sZzfmWsWyMXmdazLEYUlTNdaa7yVFZYznpONaOSgWETlx%2FaEYi0mZVWhAy8nBbL%2B9hm15zegLmlAPG&X-Amz-Signature=5ca44a53051891a193cf9e4198c2aa883b80177158d73c1eeac50f633da98f57&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RYZKYSO7%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T083040Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCPkjfJLrb3Tk0bItZq4NuVz1J6JqZdxpljbD4MdvdZCQIhAMxyrQKSwpSZnNvDY2j9g2DOb9se5nj%2Fd9xtH%2FZroRYOKogECLn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwjbzFhDRP9uXV7GAoq3AP42PxdOp8UTabGW%2FCdP8fF4CnlXDdfWcSlSSvirVcGCWFvI0MQAlJoWAhfkdJCxDp%2FN4OnWtOLvp5euT%2Fu32%2BZmJyYLv2evY88mdKqmXRTYsu%2FaG0mOYvOl76Ge6fahbBFKB4fb8ig7aQUbFn2D1G1u3eozDj0q0I1h3CHvjLi%2FRFesKXouEldBO6HBAlUYlQJzoFsCFSvstixzPJ6RLxylCA3EWRg5CSLVJHa49J%2FAD3IhZLGBhe2Fth%2BSVaOvkEuLBbWknTpV%2BwU%2Bnosy%2BVChUownenCNZALghTSkkxZWgWx6EAKFDtd0HvNfkC2k%2BxbOmczOI0ylszFELN3RMjOcTQ4toKciGGDqE5zLNc3UO2cgao6rAGpGvESqsmeuLbT8eNn5pTHIJnYjO1hVFjSQFVvBkCd%2BXRxVmfubHIUnMwwEOTzxBXyAx6IpIrjLuA26f7ig6V1ARaUJ%2BQVaReeaaihRbJICDOu2foTfp2Z9vin%2F0c4OxNc6bCbpEAjVoipWenhbu%2BSXRHkdGSuoWHwYKJj0g7WTBstKNnH86LZZKk2uvjM5ypfpS9wJGdL%2BBHRAzH74yXC%2BUjhBq7JTCb3MNpiTypvh36LFKZlsAtJ1FEZMo5eLuDjz3N1DzCgvNu9BjqkAdS1Wf74hD9DcHGBHqtxRi0EYE%2BzwlH%2Frgna048CR4oj77t5PjDADI%2FK5upfCy1TVpNfMAdtb%2B9Vj4%2BLACmrcMmPbG2%2BkIeLI1zl4YKnHnWrE8%2Fw%2Be%2BiL8DDD5cfRPiC%2Bld6RUyAzAe9j2sZzfmWsWyMXmdazLEYUlTNdaa7yVFZYznpONaOSgWETlx%2FaEYi0mZVWhAy8nBbL%2B9hm15zegLmlAPG&X-Amz-Signature=d2fed4653a5bea0f8dab708be21ecc912cca5c08527e45b2aecd0a4f48bb6950&X-Amz-SignedHeaders=host&x-id=GetObject)


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

