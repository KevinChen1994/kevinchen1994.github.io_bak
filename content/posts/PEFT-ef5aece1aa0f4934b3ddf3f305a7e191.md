---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466XKYBB5GB%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250207T212130Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEGQaCXVzLXdlc3QtMiJHMEUCIH83%2FnzzHS5JjUKgWFyKSysEGQMsfDpC4qIOtY5S%2BAR1AiE\
  AqyYCbvs7ry6z0IAn6ZPnpCbkokiRXh9Pny%2BG%2FeuVGw8q%2FwMIfRAAGgw2Mzc0MjMxODM4MD\
  UiDN6XhfWP8V1NMK1lgyrcAzyImqC6SzQbiZmgpQfpR1Au1Ww868okXx69G3HjZvCr3dySQW3LwWn\
  Iel6qQMYb6IuNmJerB%2B6wS7JsDz58o8ka1OMYFZ4bcaqlNa0NXh9hi%2F2FB5Q%2BiPt0QYHoo4\
  VTGFRDctfhb7cNPvsMz8bxit9WyRI8xDHBXS4JbZho%2BZVIaR0SPMdPmU6XIT1XcaLxMjSfJ7HOG\
  qPPnsQmELvjLrLisy0vcg%2B0o%2BUMLcW1OFY%2FEBVqVyUv3XS0k85Wd0QO6fa0UnOXz0G%2BEb\
  DGchFst2V4KvKvSllP1hJsuFCmEdmKNsL0ErNXSwTaJTXsqADoe%2F1g0iyncLscHyKd1ZfcS1Yx%\
  2B2vAQygEP%2F3CYwq4w4EdrWqF40zn%2FN%2Fo%2Fry1r6uG1T%2BQ6jw7EDF9bgQO3G0Zijkt7N\
  %2F1NXHUA5EqoNk4wBmwE8vhMhUMPrbXfM27yVazaPm8IFjKAicTTq0Nlb2SMZeZySblykf6H0B4m\
  fxbeXsFpPcru4qNGzxHAxpnByakYwCp7E%2BYXTcuOnIttiWcIpBzyW0nqe0gtvos3XbyyAK2dyjA\
  p4%2BcpreTM5JaVBq0e33fCMlXydllTMh1pdGo1yPCYoB41nsOxRGxmlqBw%2FiuLBvZWPt61FTFS\
  Q3qMJjUmb0GOqUB3S8Qwjn6PiD8sEKqt2ZmmI53iM0VGHEnlDdaf0Jtn4zWix7qd7LAWQ0k%2FPXk\
  W5yrTnyEYJKlqElxzX2H%2B3AL%2Fa9mOKXudY%2BANxRxqtM5jIC%2FqTrotTWMN54CEnKrLxMCL\
  y6AATz9OS%2BP8dUpcgKFmsFPBCwnJFgSBUlUysZFACpcOBt3yrikhlz5oeGmSozW9VcBX7EdFlzK\
  96sDIds0B4aR%2BJqa&X-Amz-Signature=da8798e7f95f8066e1f6831a3d562aa8d29ab833be\
  a2e29f5ce0fe842dfb06ff&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466QLNYCARJ%2F20250207%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250207T211953Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEGQaCXVzLXdlc3QtMiJIMEYCIQDV%2BsAnFDXpsDYM0sFJJ96BRdk4o\
        MhY%2BRCchDd9xptXzQIhAJrlrYTAIqlUhMbjL9m9552%2BbR5fWvjAoy0h1PN7wbTnKv8D\
        CH0QABoMNjM3NDIzMTgzODA1IgzTRdDgb%2BcN%2FZkwE8Aq3AMxzZJyaczRKYgQVP4R9e6\
        8A%2B4JGc%2BtjLkZDA8wS7G3JWyIJ0Gi%2Bdr%2F1geBjAyN9%2BSzrjQ%2BmgstvrRoRN\
        v11quoueD07r6Bn0J5ubqs%2BafpEIm7r%2FDY8VWPx4DLWRYf2vtLnqnJEvH0XuN7VNB%2\
        FYsTgV2VIajUTSA8J7j2Z8tdSoFOLzNWUtTsMrC6M7CKt7n%2FjayUw%2FoMAp6dZAaAghU\
        ArHGIchEO8OeHOJBu2IbUT4k1NOlUdxqC0fSTJnhnanjlpxrqh%2BZ3F9dgsGtx7lIexhKG\
        vlxFDm%2B537uCO3pJ5mVsdC1lUk87WYT9VEiSPnGN%2FjIlJWwXKgieANf8WiKp0gRYKsL\
        y5DxeRGTAvBC6XbgTQwDruPeR62COcNz4Zzqj3XVmIw7YCQxuP%2Fgo%2B49YAzey5USL4r\
        K6J5riCTxDyEIkoscTgGmDwCofAxygh%2F6bPMZkadjD1%2FKdjft%2Fkg2kzTx4RZ39WSR\
        a0GO76iK85fbrzLWcpKmKIif2TbDBUoXUS58ceT1JO%2FxH216TvBO%2BuDVAseuqyuMw5j\
        1rK0KX0a2qeb4GHeBxMLaNymRovgAIRftcC1KJsjUnR4U4HItIaKs0nvcMK229oBE2l4i6l\
        oVgkt97HNMo9TXNsKzDA1Jm9BjqkAZyzNhtdnDePvFkQnxte4bpiX0qdn%2B%2FETRI%2BZ\
        P4SJY%2FIpA24ViIS3dDhD8T4KrpKcJ9KgYMu5x8JlHSlh7aWRltMnCgWPtQEFU7WuoK%2B\
        S449aGZOtXQ1SDfhLCnTEA%2BnorVJkMxwaJBRGC5rM3F6QvFp1ON8yStEwyaPV0M%2BLoO\
        TVKWD%2BXJasu8%2BzjTuogq80SmV7zYKkcbhYLIEV%2B2xJ1xoTpdN&X-Amz-Signature\
        =62c93577e099b20ad086c2090f3a9d38f1d4dba6d5b28a1367fbf91ca595c049&X-Amz\
        -SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-07T22:19:53.626Z"
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
UPDATE_TIME: "2025-02-07T21:21:37.846Z"
EXPIRY_TIME: "2025-02-07T22:21:24.615Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665OHRI5IF%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T212124Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGQaCXVzLXdlc3QtMiJHMEUCICcIuQ7otGsre5%2FSh8zGBhlaUAoTtHPqKkvoI6BwHRxdAiEAxw%2FcTBbtPXRaYwe%2Bt7qTdJ7A8llFl%2FKYxdAw9AUNEe8q%2FwMIfRAAGgw2Mzc0MjMxODM4MDUiDC5UK2M5JnGKu4wodircAwP5opV7EvKpTUJ%2B6D9bfeXppDtYPyEi8yR0V0QKuvG8jt8%2F97MQwIfwYsGzAbCR%2BhVyu1Ho83k%2BafC9ETB9aiR7zyF80GLRRFbs%2Feup4zB5iZkN%2B%2BVanOw6IgmhnsiUAC6QJE2AL9SR8ETTiC3%2FvVwz8ri3lTSCo6XafjeaZFQL59LrFmIC6nvXXybJxf4QrU8WFTco%2FM6KIibGTVyi3rste2tM5IV3uKOL1WEmEZY5LIGh%2F0WcmBRrIeNSdGtf8uA2DmtZJkuDGlpu5C7HvTGoL2N8JVkW2Fdn4Dp0ee2G95P8fllxNsb3ePX6BEn4qsM7uGudJRqpIXpkVNkfB0aIzzD5ZGcs%2Bbd6KDrX%2FfquQnu80iGNoyOqxabcSShy56aPKaneM7fwIOQ2R2V%2BzHgTy8DdCYbn3t3Qh7fR%2Bh83xFs4AuxA0N1f3Xx1SJq4WfF%2Fu0QKFVqtNvdC0JgE1rVlg8B1rjIhDVKGj%2BvraMz4tj0PayEzpwVmNYW0jfwe01M3PBeLfPYMQ9pl93AO3K%2FigkvqptkqXTtOdDTsN0zhQ2sd6%2F%2FTJ9IXvBz%2FTKHJeq1XkN%2B2IJRHbVszihNGfygyDig00gwCgHdKYrrArizHTXPx0hMOqf5xlDCfMMPUmb0GOqUBjzVu4Ta5zcDeaTTs4FdhKkYGXKKfse1l3PXCtR2no1csKmkG7FqrfCyRkcYn4K%2BJyXCf%2FlugCXsT7hiVlXYPlxlT10HIj9MkAYgzfr9zoWcCSxAKtR6%2FLMmEyO0Wm56NhDFe2tWaKDoubEL0qPOwU6qit5YPEVM2tv%2B9P1xoA9IKeA4cUYgtpwm%2B8Kldf9IOQsHcBVbF9YoxkEe8eHwloT4u7u54&X-Amz-Signature=78c04593a594347aa9b22b341faaffe78d1c7cc87d4aed9b8a41fa2cb45f6b2c&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665OHRI5IF%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T212124Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGQaCXVzLXdlc3QtMiJHMEUCICcIuQ7otGsre5%2FSh8zGBhlaUAoTtHPqKkvoI6BwHRxdAiEAxw%2FcTBbtPXRaYwe%2Bt7qTdJ7A8llFl%2FKYxdAw9AUNEe8q%2FwMIfRAAGgw2Mzc0MjMxODM4MDUiDC5UK2M5JnGKu4wodircAwP5opV7EvKpTUJ%2B6D9bfeXppDtYPyEi8yR0V0QKuvG8jt8%2F97MQwIfwYsGzAbCR%2BhVyu1Ho83k%2BafC9ETB9aiR7zyF80GLRRFbs%2Feup4zB5iZkN%2B%2BVanOw6IgmhnsiUAC6QJE2AL9SR8ETTiC3%2FvVwz8ri3lTSCo6XafjeaZFQL59LrFmIC6nvXXybJxf4QrU8WFTco%2FM6KIibGTVyi3rste2tM5IV3uKOL1WEmEZY5LIGh%2F0WcmBRrIeNSdGtf8uA2DmtZJkuDGlpu5C7HvTGoL2N8JVkW2Fdn4Dp0ee2G95P8fllxNsb3ePX6BEn4qsM7uGudJRqpIXpkVNkfB0aIzzD5ZGcs%2Bbd6KDrX%2FfquQnu80iGNoyOqxabcSShy56aPKaneM7fwIOQ2R2V%2BzHgTy8DdCYbn3t3Qh7fR%2Bh83xFs4AuxA0N1f3Xx1SJq4WfF%2Fu0QKFVqtNvdC0JgE1rVlg8B1rjIhDVKGj%2BvraMz4tj0PayEzpwVmNYW0jfwe01M3PBeLfPYMQ9pl93AO3K%2FigkvqptkqXTtOdDTsN0zhQ2sd6%2F%2FTJ9IXvBz%2FTKHJeq1XkN%2B2IJRHbVszihNGfygyDig00gwCgHdKYrrArizHTXPx0hMOqf5xlDCfMMPUmb0GOqUBjzVu4Ta5zcDeaTTs4FdhKkYGXKKfse1l3PXCtR2no1csKmkG7FqrfCyRkcYn4K%2BJyXCf%2FlugCXsT7hiVlXYPlxlT10HIj9MkAYgzfr9zoWcCSxAKtR6%2FLMmEyO0Wm56NhDFe2tWaKDoubEL0qPOwU6qit5YPEVM2tv%2B9P1xoA9IKeA4cUYgtpwm%2B8Kldf9IOQsHcBVbF9YoxkEe8eHwloT4u7u54&X-Amz-Signature=c469cad7675a367ba9dd27091cc7313565d18142033709e1d2b37e52aca45bc7&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665OHRI5IF%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T212125Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGQaCXVzLXdlc3QtMiJHMEUCICcIuQ7otGsre5%2FSh8zGBhlaUAoTtHPqKkvoI6BwHRxdAiEAxw%2FcTBbtPXRaYwe%2Bt7qTdJ7A8llFl%2FKYxdAw9AUNEe8q%2FwMIfRAAGgw2Mzc0MjMxODM4MDUiDC5UK2M5JnGKu4wodircAwP5opV7EvKpTUJ%2B6D9bfeXppDtYPyEi8yR0V0QKuvG8jt8%2F97MQwIfwYsGzAbCR%2BhVyu1Ho83k%2BafC9ETB9aiR7zyF80GLRRFbs%2Feup4zB5iZkN%2B%2BVanOw6IgmhnsiUAC6QJE2AL9SR8ETTiC3%2FvVwz8ri3lTSCo6XafjeaZFQL59LrFmIC6nvXXybJxf4QrU8WFTco%2FM6KIibGTVyi3rste2tM5IV3uKOL1WEmEZY5LIGh%2F0WcmBRrIeNSdGtf8uA2DmtZJkuDGlpu5C7HvTGoL2N8JVkW2Fdn4Dp0ee2G95P8fllxNsb3ePX6BEn4qsM7uGudJRqpIXpkVNkfB0aIzzD5ZGcs%2Bbd6KDrX%2FfquQnu80iGNoyOqxabcSShy56aPKaneM7fwIOQ2R2V%2BzHgTy8DdCYbn3t3Qh7fR%2Bh83xFs4AuxA0N1f3Xx1SJq4WfF%2Fu0QKFVqtNvdC0JgE1rVlg8B1rjIhDVKGj%2BvraMz4tj0PayEzpwVmNYW0jfwe01M3PBeLfPYMQ9pl93AO3K%2FigkvqptkqXTtOdDTsN0zhQ2sd6%2F%2FTJ9IXvBz%2FTKHJeq1XkN%2B2IJRHbVszihNGfygyDig00gwCgHdKYrrArizHTXPx0hMOqf5xlDCfMMPUmb0GOqUBjzVu4Ta5zcDeaTTs4FdhKkYGXKKfse1l3PXCtR2no1csKmkG7FqrfCyRkcYn4K%2BJyXCf%2FlugCXsT7hiVlXYPlxlT10HIj9MkAYgzfr9zoWcCSxAKtR6%2FLMmEyO0Wm56NhDFe2tWaKDoubEL0qPOwU6qit5YPEVM2tv%2B9P1xoA9IKeA4cUYgtpwm%2B8Kldf9IOQsHcBVbF9YoxkEe8eHwloT4u7u54&X-Amz-Signature=57f302e537a03509ae3bc046e5c203e493761a9e20e586370e5a4cc1ec222d01&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665OHRI5IF%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T212125Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGQaCXVzLXdlc3QtMiJHMEUCICcIuQ7otGsre5%2FSh8zGBhlaUAoTtHPqKkvoI6BwHRxdAiEAxw%2FcTBbtPXRaYwe%2Bt7qTdJ7A8llFl%2FKYxdAw9AUNEe8q%2FwMIfRAAGgw2Mzc0MjMxODM4MDUiDC5UK2M5JnGKu4wodircAwP5opV7EvKpTUJ%2B6D9bfeXppDtYPyEi8yR0V0QKuvG8jt8%2F97MQwIfwYsGzAbCR%2BhVyu1Ho83k%2BafC9ETB9aiR7zyF80GLRRFbs%2Feup4zB5iZkN%2B%2BVanOw6IgmhnsiUAC6QJE2AL9SR8ETTiC3%2FvVwz8ri3lTSCo6XafjeaZFQL59LrFmIC6nvXXybJxf4QrU8WFTco%2FM6KIibGTVyi3rste2tM5IV3uKOL1WEmEZY5LIGh%2F0WcmBRrIeNSdGtf8uA2DmtZJkuDGlpu5C7HvTGoL2N8JVkW2Fdn4Dp0ee2G95P8fllxNsb3ePX6BEn4qsM7uGudJRqpIXpkVNkfB0aIzzD5ZGcs%2Bbd6KDrX%2FfquQnu80iGNoyOqxabcSShy56aPKaneM7fwIOQ2R2V%2BzHgTy8DdCYbn3t3Qh7fR%2Bh83xFs4AuxA0N1f3Xx1SJq4WfF%2Fu0QKFVqtNvdC0JgE1rVlg8B1rjIhDVKGj%2BvraMz4tj0PayEzpwVmNYW0jfwe01M3PBeLfPYMQ9pl93AO3K%2FigkvqptkqXTtOdDTsN0zhQ2sd6%2F%2FTJ9IXvBz%2FTKHJeq1XkN%2B2IJRHbVszihNGfygyDig00gwCgHdKYrrArizHTXPx0hMOqf5xlDCfMMPUmb0GOqUBjzVu4Ta5zcDeaTTs4FdhKkYGXKKfse1l3PXCtR2no1csKmkG7FqrfCyRkcYn4K%2BJyXCf%2FlugCXsT7hiVlXYPlxlT10HIj9MkAYgzfr9zoWcCSxAKtR6%2FLMmEyO0Wm56NhDFe2tWaKDoubEL0qPOwU6qit5YPEVM2tv%2B9P1xoA9IKeA4cUYgtpwm%2B8Kldf9IOQsHcBVbF9YoxkEe8eHwloT4u7u54&X-Amz-Signature=871dcfe1a36914a4589221cd13ecdad274858e225c65a354207ef07698cde090&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665OHRI5IF%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T212125Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGQaCXVzLXdlc3QtMiJHMEUCICcIuQ7otGsre5%2FSh8zGBhlaUAoTtHPqKkvoI6BwHRxdAiEAxw%2FcTBbtPXRaYwe%2Bt7qTdJ7A8llFl%2FKYxdAw9AUNEe8q%2FwMIfRAAGgw2Mzc0MjMxODM4MDUiDC5UK2M5JnGKu4wodircAwP5opV7EvKpTUJ%2B6D9bfeXppDtYPyEi8yR0V0QKuvG8jt8%2F97MQwIfwYsGzAbCR%2BhVyu1Ho83k%2BafC9ETB9aiR7zyF80GLRRFbs%2Feup4zB5iZkN%2B%2BVanOw6IgmhnsiUAC6QJE2AL9SR8ETTiC3%2FvVwz8ri3lTSCo6XafjeaZFQL59LrFmIC6nvXXybJxf4QrU8WFTco%2FM6KIibGTVyi3rste2tM5IV3uKOL1WEmEZY5LIGh%2F0WcmBRrIeNSdGtf8uA2DmtZJkuDGlpu5C7HvTGoL2N8JVkW2Fdn4Dp0ee2G95P8fllxNsb3ePX6BEn4qsM7uGudJRqpIXpkVNkfB0aIzzD5ZGcs%2Bbd6KDrX%2FfquQnu80iGNoyOqxabcSShy56aPKaneM7fwIOQ2R2V%2BzHgTy8DdCYbn3t3Qh7fR%2Bh83xFs4AuxA0N1f3Xx1SJq4WfF%2Fu0QKFVqtNvdC0JgE1rVlg8B1rjIhDVKGj%2BvraMz4tj0PayEzpwVmNYW0jfwe01M3PBeLfPYMQ9pl93AO3K%2FigkvqptkqXTtOdDTsN0zhQ2sd6%2F%2FTJ9IXvBz%2FTKHJeq1XkN%2B2IJRHbVszihNGfygyDig00gwCgHdKYrrArizHTXPx0hMOqf5xlDCfMMPUmb0GOqUBjzVu4Ta5zcDeaTTs4FdhKkYGXKKfse1l3PXCtR2no1csKmkG7FqrfCyRkcYn4K%2BJyXCf%2FlugCXsT7hiVlXYPlxlT10HIj9MkAYgzfr9zoWcCSxAKtR6%2FLMmEyO0Wm56NhDFe2tWaKDoubEL0qPOwU6qit5YPEVM2tv%2B9P1xoA9IKeA4cUYgtpwm%2B8Kldf9IOQsHcBVbF9YoxkEe8eHwloT4u7u54&X-Amz-Signature=b291a41ca3f0d7d8a4a0c3d867662997fc93c84f95d59e6fd6f0330aaa77be10&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TPAXARZS%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T212125Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGQaCXVzLXdlc3QtMiJHMEUCIGqtWrDC7e08gryiZcCoxlG37VoYgcEoxsVMvWCMFeViAiEAwVCCgYK5H0UH7852aClElb5jErLIOzxYW9Oy%2FvoepP8q%2FwMIfRAAGgw2Mzc0MjMxODM4MDUiDHUvXXvXh2eX1olnaSrcA%2Bi6KNiXaCIVPv85w4nnm%2BRblLDaSyTkWinLjyYsQS%2BH2cB2YU9d%2FRb0PUsOExX1CnxbZKTlJ47pwlfH2EAsDZJz84C4LGOEToLqoQ4QbW%2FymIezq9cWnzK%2FUyIGaUKWou%2F4eI1hA1ktz7YjZIIRuiTrZkpC%2FGLzE%2B5%2B%2BDvm6PW9DU1oVrzUIksiAHGG0992bqlgkqGOlYe%2FW8GNZuufy5icI%2FQM%2BMtnzOAhKMkiCjhO3BDFnEOQKHblFf28wPAMBvUlsVw0G8fpqCr7UqBm8c7gMil95OBfD9Lto2JGaKLQKwlLjWCYOwLTur%2F7TlF91sMUTHIkLMe05fCzSNxEZa%2Bn1R4LfIB5KzEBUe%2BrUiHlQn7npX0sRnMv8VkwODFPP8uAgZG0CUdeLk9%2BkKgqAjrhUI0WXXxo3cjaQgHjBPZR6oe0Ue6%2BKHkD9OONmi1H2LIxKu9kfVj3YxS9h4Q5nGewzDvlAJz1%2FH4RGpIGDen0ZY%2FjqtFn5kZDP5EPIkfRA8UM8EByU7VRVJX6HNu1vpiBX%2B8GtuUviDYK4g7r1TAAB4%2F4NxuwFCKnea%2FU1Jh%2F5XjI%2BVqNYiasuYYPTb7NA%2BzDbFWzmh6PGgL%2FpqGRdpzB8UyIAoWBZI8QGGjUMMTUmb0GOqUBV%2FbCjDbnaM7jcgjGIY8xIzEDLi0KQTyOBDDRq%2FL6sYDFoxV%2Bf6mTEX3cEpRmN9VfrBqt9xE8fd51JtawcuDkw5EHYwLOsD9%2FHm6i1%2FBBPsLgt62nDc4%2BaPOBLphjywElfGPrsy6vOIw7LLIdqTq3ufL5Fe6oHMd%2BfnQVarReXXjFE1vjr%2BrvaH%2FocmudV6CxBMJSTydJ4HN2ZXCyaziNMjduEu6C&X-Amz-Signature=85521bded8c3dc9d0db067bf5abf75a9b11e6229dc15f3b3edcd9ec7ba401e5c&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XUTKDPI4%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T212125Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGQaCXVzLXdlc3QtMiJGMEQCIE5N21FlR4uzwpi9cXFVP4fP3T89scmiRyr8e7FqG1IqAiB2TlABPqvIXmZagGwISp1ZKSEjRTBz%2B8BL9l42q7gtkyr%2FAwh9EAAaDDYzNzQyMzE4MzgwNSIMrn746sgOSed3T5JfKtwDsfK0t49ahkW2HZGbFJ%2F%2Fy6ksD1Do3T0I0kvbCMe5bTvt%2FaaBZucEpGKqsqPsNbPjcfrxzKOpyo79BA0Mh6vHYzAQFSot6P2lIUlFLm8AxY1ykY6GzjuulT%2FW1Jz8BbAynCV4I0gEkW1eYPDmLCAaL4j0N7BJbTlNwqQtPDnEVQnYVLRq1rZrymt7z8JpezATk2sFvsPna%2BSFLC4QHfCnNIkEbdeOd7%2F6cLcgphhz%2FIp67mXbW%2BNhrL0xDfxULw7nZj79rqEZBW2QhyqYPKTl3zsEJlvtvvy94FeICT40Nxan828BVMaQf8gLaBxNYrBrFi8d9s3sSsyImsuQdUKEjuBFOSZhi3cbnD0Kq%2FXz%2BgjTPbGV82Z6slzicXJYY%2FSFnp9NFxqTo4JTXgWl3%2BY4PkSOor2SeVk%2F4XlOvwdeq79Ro4su2ewwkbGU%2FgneuiXLnwJT%2B%2BlzF4PSrZc9TjSk6XZJ9i4JN4QtaoMMEhoIeGCF4jIowSHyibjsLjWUFH%2BWwaYppbSTKLxa0aCjz1BmkWsXMOzuWDbUCh4xdQiKZ13RhxWg4bHzKWW5sy05CAvNJEHhq9LBYIoIIg9gD1iiDNTZW9HZGHeMIa9rsE%2Bviq8otqB3JD4VAQ7fagYwhNSZvQY6pgHJq4uO7Q%2FAhgUcrlwgbaL%2FONVPBEweMC9gkg8NqPWpBp%2BnwZYNsXRPskAi3U86PwxgApkDX%2FgKcshVu5DJq7nnQVFhBmBm5guWTos6FSpgxH7hWWcpeNIKtBBOchaPzgqth9PWnijQcowTlWP3kCm5f0CV4tTGaC1E5TJwsedS0762%2Fn3c5dUIEryLiUIeYjtWsqPoYvpoirJGOEM89caL4%2BmchNXE&X-Amz-Signature=646b5777359110ac0e85d66e6f6cab747a4245ff598800ef1a76751b596c0c09&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665OHRI5IF%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T212125Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGQaCXVzLXdlc3QtMiJHMEUCICcIuQ7otGsre5%2FSh8zGBhlaUAoTtHPqKkvoI6BwHRxdAiEAxw%2FcTBbtPXRaYwe%2Bt7qTdJ7A8llFl%2FKYxdAw9AUNEe8q%2FwMIfRAAGgw2Mzc0MjMxODM4MDUiDC5UK2M5JnGKu4wodircAwP5opV7EvKpTUJ%2B6D9bfeXppDtYPyEi8yR0V0QKuvG8jt8%2F97MQwIfwYsGzAbCR%2BhVyu1Ho83k%2BafC9ETB9aiR7zyF80GLRRFbs%2Feup4zB5iZkN%2B%2BVanOw6IgmhnsiUAC6QJE2AL9SR8ETTiC3%2FvVwz8ri3lTSCo6XafjeaZFQL59LrFmIC6nvXXybJxf4QrU8WFTco%2FM6KIibGTVyi3rste2tM5IV3uKOL1WEmEZY5LIGh%2F0WcmBRrIeNSdGtf8uA2DmtZJkuDGlpu5C7HvTGoL2N8JVkW2Fdn4Dp0ee2G95P8fllxNsb3ePX6BEn4qsM7uGudJRqpIXpkVNkfB0aIzzD5ZGcs%2Bbd6KDrX%2FfquQnu80iGNoyOqxabcSShy56aPKaneM7fwIOQ2R2V%2BzHgTy8DdCYbn3t3Qh7fR%2Bh83xFs4AuxA0N1f3Xx1SJq4WfF%2Fu0QKFVqtNvdC0JgE1rVlg8B1rjIhDVKGj%2BvraMz4tj0PayEzpwVmNYW0jfwe01M3PBeLfPYMQ9pl93AO3K%2FigkvqptkqXTtOdDTsN0zhQ2sd6%2F%2FTJ9IXvBz%2FTKHJeq1XkN%2B2IJRHbVszihNGfygyDig00gwCgHdKYrrArizHTXPx0hMOqf5xlDCfMMPUmb0GOqUBjzVu4Ta5zcDeaTTs4FdhKkYGXKKfse1l3PXCtR2no1csKmkG7FqrfCyRkcYn4K%2BJyXCf%2FlugCXsT7hiVlXYPlxlT10HIj9MkAYgzfr9zoWcCSxAKtR6%2FLMmEyO0Wm56NhDFe2tWaKDoubEL0qPOwU6qit5YPEVM2tv%2B9P1xoA9IKeA4cUYgtpwm%2B8Kldf9IOQsHcBVbF9YoxkEe8eHwloT4u7u54&X-Amz-Signature=3c3128c6223f86bf6010ff09edc28c34351a05662b7b665c77f64a8134eeca79&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665OHRI5IF%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T212125Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGQaCXVzLXdlc3QtMiJHMEUCICcIuQ7otGsre5%2FSh8zGBhlaUAoTtHPqKkvoI6BwHRxdAiEAxw%2FcTBbtPXRaYwe%2Bt7qTdJ7A8llFl%2FKYxdAw9AUNEe8q%2FwMIfRAAGgw2Mzc0MjMxODM4MDUiDC5UK2M5JnGKu4wodircAwP5opV7EvKpTUJ%2B6D9bfeXppDtYPyEi8yR0V0QKuvG8jt8%2F97MQwIfwYsGzAbCR%2BhVyu1Ho83k%2BafC9ETB9aiR7zyF80GLRRFbs%2Feup4zB5iZkN%2B%2BVanOw6IgmhnsiUAC6QJE2AL9SR8ETTiC3%2FvVwz8ri3lTSCo6XafjeaZFQL59LrFmIC6nvXXybJxf4QrU8WFTco%2FM6KIibGTVyi3rste2tM5IV3uKOL1WEmEZY5LIGh%2F0WcmBRrIeNSdGtf8uA2DmtZJkuDGlpu5C7HvTGoL2N8JVkW2Fdn4Dp0ee2G95P8fllxNsb3ePX6BEn4qsM7uGudJRqpIXpkVNkfB0aIzzD5ZGcs%2Bbd6KDrX%2FfquQnu80iGNoyOqxabcSShy56aPKaneM7fwIOQ2R2V%2BzHgTy8DdCYbn3t3Qh7fR%2Bh83xFs4AuxA0N1f3Xx1SJq4WfF%2Fu0QKFVqtNvdC0JgE1rVlg8B1rjIhDVKGj%2BvraMz4tj0PayEzpwVmNYW0jfwe01M3PBeLfPYMQ9pl93AO3K%2FigkvqptkqXTtOdDTsN0zhQ2sd6%2F%2FTJ9IXvBz%2FTKHJeq1XkN%2B2IJRHbVszihNGfygyDig00gwCgHdKYrrArizHTXPx0hMOqf5xlDCfMMPUmb0GOqUBjzVu4Ta5zcDeaTTs4FdhKkYGXKKfse1l3PXCtR2no1csKmkG7FqrfCyRkcYn4K%2BJyXCf%2FlugCXsT7hiVlXYPlxlT10HIj9MkAYgzfr9zoWcCSxAKtR6%2FLMmEyO0Wm56NhDFe2tWaKDoubEL0qPOwU6qit5YPEVM2tv%2B9P1xoA9IKeA4cUYgtpwm%2B8Kldf9IOQsHcBVbF9YoxkEe8eHwloT4u7u54&X-Amz-Signature=412021c2744ff8d32b574c672780bc1bdf7d5535d9a01061c362ead49dde5ca0&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665OHRI5IF%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T212125Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGQaCXVzLXdlc3QtMiJHMEUCICcIuQ7otGsre5%2FSh8zGBhlaUAoTtHPqKkvoI6BwHRxdAiEAxw%2FcTBbtPXRaYwe%2Bt7qTdJ7A8llFl%2FKYxdAw9AUNEe8q%2FwMIfRAAGgw2Mzc0MjMxODM4MDUiDC5UK2M5JnGKu4wodircAwP5opV7EvKpTUJ%2B6D9bfeXppDtYPyEi8yR0V0QKuvG8jt8%2F97MQwIfwYsGzAbCR%2BhVyu1Ho83k%2BafC9ETB9aiR7zyF80GLRRFbs%2Feup4zB5iZkN%2B%2BVanOw6IgmhnsiUAC6QJE2AL9SR8ETTiC3%2FvVwz8ri3lTSCo6XafjeaZFQL59LrFmIC6nvXXybJxf4QrU8WFTco%2FM6KIibGTVyi3rste2tM5IV3uKOL1WEmEZY5LIGh%2F0WcmBRrIeNSdGtf8uA2DmtZJkuDGlpu5C7HvTGoL2N8JVkW2Fdn4Dp0ee2G95P8fllxNsb3ePX6BEn4qsM7uGudJRqpIXpkVNkfB0aIzzD5ZGcs%2Bbd6KDrX%2FfquQnu80iGNoyOqxabcSShy56aPKaneM7fwIOQ2R2V%2BzHgTy8DdCYbn3t3Qh7fR%2Bh83xFs4AuxA0N1f3Xx1SJq4WfF%2Fu0QKFVqtNvdC0JgE1rVlg8B1rjIhDVKGj%2BvraMz4tj0PayEzpwVmNYW0jfwe01M3PBeLfPYMQ9pl93AO3K%2FigkvqptkqXTtOdDTsN0zhQ2sd6%2F%2FTJ9IXvBz%2FTKHJeq1XkN%2B2IJRHbVszihNGfygyDig00gwCgHdKYrrArizHTXPx0hMOqf5xlDCfMMPUmb0GOqUBjzVu4Ta5zcDeaTTs4FdhKkYGXKKfse1l3PXCtR2no1csKmkG7FqrfCyRkcYn4K%2BJyXCf%2FlugCXsT7hiVlXYPlxlT10HIj9MkAYgzfr9zoWcCSxAKtR6%2FLMmEyO0Wm56NhDFe2tWaKDoubEL0qPOwU6qit5YPEVM2tv%2B9P1xoA9IKeA4cUYgtpwm%2B8Kldf9IOQsHcBVbF9YoxkEe8eHwloT4u7u54&X-Amz-Signature=022f16a2f8f548cac7020c66750394594d0a9a82d0b4c6fd5dd6ba435c4b7c04&X-Amz-SignedHeaders=host&x-id=GetObject)


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

