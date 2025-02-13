---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466RGGRIC6U%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250213T183249Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEPL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIATHHY4dWi44RHtIrGk\
  RkrgklOgf9%2F%2BuRZzf3JEw%2F2R%2BAiEA84SghKT2BlZiIkJvcYKqL9yh0MEfDsirlKxo0JHS\
  85sq%2FwMIGxAAGgw2Mzc0MjMxODM4MDUiDJd3tnXznAN4ENuKcircA2r48fX5qkfT%2BTAOd0prH\
  Q6OF7nCUDYx4BhfWrN9Y%2FZFlEyKN0%2Fw7fIb7j4ba%2F%2BuiH4fOiR6MqXqQ8LB%2F86wXtdb\
  a1eza%2FFByVh7AbtX0HI3oOF7%2FIRS8EBpV3Te%2B6IU2wsXdz7r6ko9Lx2EKiLaOAGm%2FJK86\
  c8fwvOD80jGu61iPzHLDMLsbli0sDfBuHMtnHlnJaVEEByJ%2BXD3lYAqpwVf30QNiS64gW2QtWT5\
  GvlXT2D9YzrYJUUYUL0DfYrdCzSbTflR362BQ6lfsq%2BEPZkMtG4DOS3MsSXE8oUxA70b%2BmsDP\
  EZG8fdpOUQcdc9vqzWp0hqBOSgdAlyRcTAdueBMpZXqBVBs5a8%2FZMUDfZVsD2430H9MSn6V%2B5\
  6LDSk%2FtdAukTgDmegs5TLlarFUdb04fRf4%2BiFHZlNoyyysrGXLKpvVMaC8C7LFPiH63g5P0Q9\
  3XonPaaQ60Yy2DKzaJJy7%2F%2FvV5oUrzZnDBq%2BJ4moMZ%2BJWq%2BaBjn88aUSgdSMouKm06T\
  iDwhTMcF%2FRd%2FvisGM4B%2BUWHH6jTWL4vDqi3niokrw1YoiJGx%2BnnPsnSPQfP5v2derWH82\
  EDEk%2FQsgZSTDWJOg3bmFdZLVouyPXJfLOlPtuYCzpchzxSXpvMKLguL0GOqUBFPfYeSYVrXqoI5\
  R1NFKICNlZdhSVicsX4Qepa2h5EvbAy9sl8jV518vf9MUOSS0LLLlh%2FMrPFOBcxyZ6ZHDmbLmCZ\
  h8qQDf0RwB3Sd%2Bcsw%2BirYMGMA87inJfhot98SM%2FKJnAPqoI8LHYTs61lUhpG21E0WAFFmTZ\
  MCvVslsufTBTQ0ht36AYotgb0mbnHFVUPFoKZ%2FRdkys2ENsYey%2BhwAQWdZlX&X-Amz-Signat\
  ure=e52adec8fb23404ad46b26870641616082f2838d4b9d4297077a10c4fb2b123d&X-Amz-Si\
  gnedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB46663KN5KGZ%2F20250213%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250213T183120Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEPL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIB09oL5%2BAAuZD5DIlvrFlIpew1fSrwOXAYzi09ARtiXRAiEA4UVfHPN9pF2ofgLJ0fiv\
        rTkObmaPon%2BU2MyAYFC5jDYq%2FwMIGxAAGgw2Mzc0MjMxODM4MDUiDGZxUcymsMuy%2F\
        hHifyrcA1rWgnoFKIDay4%2B15TKAzZG4QxWzJHGBBNysazGl3VECMZHj7SS0eDc%2BLfIR\
        tm8oVMrcfWgWUa7uk4tGC13IS0%2FE%2FTBRAf%2BhKRyofRWBnjlPAt%2FwBovBZHrVpxd\
        4kdlq%2BlATaPuu43%2FdkQV2TLSMlzL0AjscRl%2B8WWOcNVmomOSj1Ke%2FJy3roRwyK1\
        L7m0c4u4oIaevba304c4mzNSe4bydCo3Q8Hg2tcln%2Bw5xVYRQ%2FN85vQz35fymHzA18G\
        W%2BD051M1YVqm8QlZOFeEKkbZViTKo3JMX%2FFJedQqNLZrbxMUBUV0%2F69BZvVRTz%2F\
        ZXsu6Bk9xDTGnqxF8CGWInN%2Bd60cgwKbTBWNdwcYBiCaOz5UpmiSRW6RI2%2F4icqDXWq\
        9a0U9V7plPoiHH8rwSXFDZR9cmY%2F3dEbydjmv%2BFGAcGHVbGAEHO9hAwYNIDxrDL%2Bv\
        i99eoJgjiVJoMpwGtyX9UgDLwzmZ4f9Bq%2BSG0ai%2B37YbusAAS53Ik%2BRkjIE7XnyPe\
        qrkeLzzKdJ3W2dMC4R%2B63uM%2Fwd6fGBkmixIP4A5KrqmD9eSqwG%2B7HTjgLrqrVPlc8\
        UDSCEct2yCAh0X3O1RGRI725%2FmBgbJRQTowgoNfhR49Nb5stGvt5xAE43UMP%2FfuL0GO\
        qUBsyk8ou4Lg6ZzndiNGce3%2FJe1oRFjC7aykq7BOjiTr%2B%2BQshff7LAQKJYRgJJ7ig\
        mM%2FWvUbrCGEa23JD1%2FKUZ8P99btpjssjgKJ0k9pIIXMzuO3vbeC7t6moK%2FAg%2Fyw\
        C6WKe43490sUdNwJ2SttcUNkhCw0qPjqgp%2FnVxySQapc3SUAWpr82bbS0oUbtQ4SKFHWf\
        WnHcEfzgCHpeE6sw2Mu3Vj97xk&X-Amz-Signature=ce8b9283fb5010c47c155e2b83cf\
        bda1386c5256da50c7078b0c7a0590ad5910&X-Amz-SignedHeaders=host&x-id=GetO\
        bject"
      expiry_time: "2025-02-13T19:31:20.842Z"
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
UPDATE_TIME: "2025-02-13T18:32:55.479Z"
EXPIRY_TIME: "2025-02-13T19:32:45.976Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QW3GZP3Y%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T183246Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCQ1pk47DiDzuePfItSarVsPjs34ppl4HZFAlPrR9rvjQIgK0Wty5UIC1FGugy2tiLC%2FwHCg3iFBE3QtZuOr47kRi8q%2FwMIGxAAGgw2Mzc0MjMxODM4MDUiDNwgyRydYO9GDxeuDSrcA4Dz3OEKf54qwuhfyB%2FLOJ4pIaKjTMgmTqCJwZBF%2BZqAv%2FqSmd7emTf1ER0omKq79SjfBZX9lO1h2tQuz7gCOd5iFQF1X51aL3VdGZ18MnYbVj9AKHGa9X3oiZs1HOzUKx31NODvykU3ljgEwHQEAE1gYp9afIa%2BnCgmw7ZKaWmtd0yMyxhJAYMHr1rrpXhVlhYJ0QYD%2BJKXFRqvfq9XydDsv6pmnOR3t1dwYDdFyFraOjEkHoVaq0Fi6ZX2iiceOzJQ9SFndqGMc6iWoQO9E63Qvx7e5dhAV0OdH1PO2VQpvRiplu6O0%2BEcQqqqUweYPcvMjFMda4ofYcQzvUn6PIq4x8lDSCUxcCbE6A%2Ba1aj8fhciPK9Pm6IrLwjnsWQHo9lJohqy4JGjit2FBtF2UfpfyGXImnbYa8uvQdPcBJIAQNUlAZ9kHawSjHD%2BP9c6XPibXyKfxrNO5ZVQIlqNaxLfqCy9SoRbgmlt99LEe0ESr8JhvSri8HqZ9u2WIdubI0mFKValh8Q%2F%2BXyNgeM2dLQzLDEYguDnR0%2B0477RTtcBNTkcsPkoHJutv09raQNci7Jd8c4Fn2CRsmrPfKwk%2Fr6VvWGY0erW0eGhvhQdjrp%2FnU6NIgtYeZiehUExMIbfuL0GOqUBYey1CSt2PRRqPCTK2IYtXMuefyTJcflpoBzbK3s%2FIckxhIS3%2Bd9ID2MB%2FK7s84EASCGiD4RvKd5FQwazRB1Ps0NTbTzHMdKP%2B5L5VRfk%2BnclkCJTkmcMir5uzH%2F8C5NG%2FFLJLonRdp3y8ImP8InoOZfFhnE283M3zGlPRQ19oafcM%2FSvRI%2FCfihnomoGEmoXCtlxMn%2Fk2y87dkwb%2Bvra8TlKv8Ul&X-Amz-Signature=2d45da0ecd4a819c59c9ccef8d0fed09bdc992f2cad1dcb728779e1a04d02c5f&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QW3GZP3Y%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T183246Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCQ1pk47DiDzuePfItSarVsPjs34ppl4HZFAlPrR9rvjQIgK0Wty5UIC1FGugy2tiLC%2FwHCg3iFBE3QtZuOr47kRi8q%2FwMIGxAAGgw2Mzc0MjMxODM4MDUiDNwgyRydYO9GDxeuDSrcA4Dz3OEKf54qwuhfyB%2FLOJ4pIaKjTMgmTqCJwZBF%2BZqAv%2FqSmd7emTf1ER0omKq79SjfBZX9lO1h2tQuz7gCOd5iFQF1X51aL3VdGZ18MnYbVj9AKHGa9X3oiZs1HOzUKx31NODvykU3ljgEwHQEAE1gYp9afIa%2BnCgmw7ZKaWmtd0yMyxhJAYMHr1rrpXhVlhYJ0QYD%2BJKXFRqvfq9XydDsv6pmnOR3t1dwYDdFyFraOjEkHoVaq0Fi6ZX2iiceOzJQ9SFndqGMc6iWoQO9E63Qvx7e5dhAV0OdH1PO2VQpvRiplu6O0%2BEcQqqqUweYPcvMjFMda4ofYcQzvUn6PIq4x8lDSCUxcCbE6A%2Ba1aj8fhciPK9Pm6IrLwjnsWQHo9lJohqy4JGjit2FBtF2UfpfyGXImnbYa8uvQdPcBJIAQNUlAZ9kHawSjHD%2BP9c6XPibXyKfxrNO5ZVQIlqNaxLfqCy9SoRbgmlt99LEe0ESr8JhvSri8HqZ9u2WIdubI0mFKValh8Q%2F%2BXyNgeM2dLQzLDEYguDnR0%2B0477RTtcBNTkcsPkoHJutv09raQNci7Jd8c4Fn2CRsmrPfKwk%2Fr6VvWGY0erW0eGhvhQdjrp%2FnU6NIgtYeZiehUExMIbfuL0GOqUBYey1CSt2PRRqPCTK2IYtXMuefyTJcflpoBzbK3s%2FIckxhIS3%2Bd9ID2MB%2FK7s84EASCGiD4RvKd5FQwazRB1Ps0NTbTzHMdKP%2B5L5VRfk%2BnclkCJTkmcMir5uzH%2F8C5NG%2FFLJLonRdp3y8ImP8InoOZfFhnE283M3zGlPRQ19oafcM%2FSvRI%2FCfihnomoGEmoXCtlxMn%2Fk2y87dkwb%2Bvra8TlKv8Ul&X-Amz-Signature=45e931db54f021b3230fa778605e3e03beb78f19a29e249d5b7b8fe7a11b39c5&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QW3GZP3Y%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T183246Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCQ1pk47DiDzuePfItSarVsPjs34ppl4HZFAlPrR9rvjQIgK0Wty5UIC1FGugy2tiLC%2FwHCg3iFBE3QtZuOr47kRi8q%2FwMIGxAAGgw2Mzc0MjMxODM4MDUiDNwgyRydYO9GDxeuDSrcA4Dz3OEKf54qwuhfyB%2FLOJ4pIaKjTMgmTqCJwZBF%2BZqAv%2FqSmd7emTf1ER0omKq79SjfBZX9lO1h2tQuz7gCOd5iFQF1X51aL3VdGZ18MnYbVj9AKHGa9X3oiZs1HOzUKx31NODvykU3ljgEwHQEAE1gYp9afIa%2BnCgmw7ZKaWmtd0yMyxhJAYMHr1rrpXhVlhYJ0QYD%2BJKXFRqvfq9XydDsv6pmnOR3t1dwYDdFyFraOjEkHoVaq0Fi6ZX2iiceOzJQ9SFndqGMc6iWoQO9E63Qvx7e5dhAV0OdH1PO2VQpvRiplu6O0%2BEcQqqqUweYPcvMjFMda4ofYcQzvUn6PIq4x8lDSCUxcCbE6A%2Ba1aj8fhciPK9Pm6IrLwjnsWQHo9lJohqy4JGjit2FBtF2UfpfyGXImnbYa8uvQdPcBJIAQNUlAZ9kHawSjHD%2BP9c6XPibXyKfxrNO5ZVQIlqNaxLfqCy9SoRbgmlt99LEe0ESr8JhvSri8HqZ9u2WIdubI0mFKValh8Q%2F%2BXyNgeM2dLQzLDEYguDnR0%2B0477RTtcBNTkcsPkoHJutv09raQNci7Jd8c4Fn2CRsmrPfKwk%2Fr6VvWGY0erW0eGhvhQdjrp%2FnU6NIgtYeZiehUExMIbfuL0GOqUBYey1CSt2PRRqPCTK2IYtXMuefyTJcflpoBzbK3s%2FIckxhIS3%2Bd9ID2MB%2FK7s84EASCGiD4RvKd5FQwazRB1Ps0NTbTzHMdKP%2B5L5VRfk%2BnclkCJTkmcMir5uzH%2F8C5NG%2FFLJLonRdp3y8ImP8InoOZfFhnE283M3zGlPRQ19oafcM%2FSvRI%2FCfihnomoGEmoXCtlxMn%2Fk2y87dkwb%2Bvra8TlKv8Ul&X-Amz-Signature=e6467f9f36a0db0b092645511ee34532177d7216d9dda031e160efe85bb681c2&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QW3GZP3Y%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T183246Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCQ1pk47DiDzuePfItSarVsPjs34ppl4HZFAlPrR9rvjQIgK0Wty5UIC1FGugy2tiLC%2FwHCg3iFBE3QtZuOr47kRi8q%2FwMIGxAAGgw2Mzc0MjMxODM4MDUiDNwgyRydYO9GDxeuDSrcA4Dz3OEKf54qwuhfyB%2FLOJ4pIaKjTMgmTqCJwZBF%2BZqAv%2FqSmd7emTf1ER0omKq79SjfBZX9lO1h2tQuz7gCOd5iFQF1X51aL3VdGZ18MnYbVj9AKHGa9X3oiZs1HOzUKx31NODvykU3ljgEwHQEAE1gYp9afIa%2BnCgmw7ZKaWmtd0yMyxhJAYMHr1rrpXhVlhYJ0QYD%2BJKXFRqvfq9XydDsv6pmnOR3t1dwYDdFyFraOjEkHoVaq0Fi6ZX2iiceOzJQ9SFndqGMc6iWoQO9E63Qvx7e5dhAV0OdH1PO2VQpvRiplu6O0%2BEcQqqqUweYPcvMjFMda4ofYcQzvUn6PIq4x8lDSCUxcCbE6A%2Ba1aj8fhciPK9Pm6IrLwjnsWQHo9lJohqy4JGjit2FBtF2UfpfyGXImnbYa8uvQdPcBJIAQNUlAZ9kHawSjHD%2BP9c6XPibXyKfxrNO5ZVQIlqNaxLfqCy9SoRbgmlt99LEe0ESr8JhvSri8HqZ9u2WIdubI0mFKValh8Q%2F%2BXyNgeM2dLQzLDEYguDnR0%2B0477RTtcBNTkcsPkoHJutv09raQNci7Jd8c4Fn2CRsmrPfKwk%2Fr6VvWGY0erW0eGhvhQdjrp%2FnU6NIgtYeZiehUExMIbfuL0GOqUBYey1CSt2PRRqPCTK2IYtXMuefyTJcflpoBzbK3s%2FIckxhIS3%2Bd9ID2MB%2FK7s84EASCGiD4RvKd5FQwazRB1Ps0NTbTzHMdKP%2B5L5VRfk%2BnclkCJTkmcMir5uzH%2F8C5NG%2FFLJLonRdp3y8ImP8InoOZfFhnE283M3zGlPRQ19oafcM%2FSvRI%2FCfihnomoGEmoXCtlxMn%2Fk2y87dkwb%2Bvra8TlKv8Ul&X-Amz-Signature=d47d3d84f82cce83a8d55cde03d886b691c9a2a178f102b24f4ed6dcd2441798&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QW3GZP3Y%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T183246Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCQ1pk47DiDzuePfItSarVsPjs34ppl4HZFAlPrR9rvjQIgK0Wty5UIC1FGugy2tiLC%2FwHCg3iFBE3QtZuOr47kRi8q%2FwMIGxAAGgw2Mzc0MjMxODM4MDUiDNwgyRydYO9GDxeuDSrcA4Dz3OEKf54qwuhfyB%2FLOJ4pIaKjTMgmTqCJwZBF%2BZqAv%2FqSmd7emTf1ER0omKq79SjfBZX9lO1h2tQuz7gCOd5iFQF1X51aL3VdGZ18MnYbVj9AKHGa9X3oiZs1HOzUKx31NODvykU3ljgEwHQEAE1gYp9afIa%2BnCgmw7ZKaWmtd0yMyxhJAYMHr1rrpXhVlhYJ0QYD%2BJKXFRqvfq9XydDsv6pmnOR3t1dwYDdFyFraOjEkHoVaq0Fi6ZX2iiceOzJQ9SFndqGMc6iWoQO9E63Qvx7e5dhAV0OdH1PO2VQpvRiplu6O0%2BEcQqqqUweYPcvMjFMda4ofYcQzvUn6PIq4x8lDSCUxcCbE6A%2Ba1aj8fhciPK9Pm6IrLwjnsWQHo9lJohqy4JGjit2FBtF2UfpfyGXImnbYa8uvQdPcBJIAQNUlAZ9kHawSjHD%2BP9c6XPibXyKfxrNO5ZVQIlqNaxLfqCy9SoRbgmlt99LEe0ESr8JhvSri8HqZ9u2WIdubI0mFKValh8Q%2F%2BXyNgeM2dLQzLDEYguDnR0%2B0477RTtcBNTkcsPkoHJutv09raQNci7Jd8c4Fn2CRsmrPfKwk%2Fr6VvWGY0erW0eGhvhQdjrp%2FnU6NIgtYeZiehUExMIbfuL0GOqUBYey1CSt2PRRqPCTK2IYtXMuefyTJcflpoBzbK3s%2FIckxhIS3%2Bd9ID2MB%2FK7s84EASCGiD4RvKd5FQwazRB1Ps0NTbTzHMdKP%2B5L5VRfk%2BnclkCJTkmcMir5uzH%2F8C5NG%2FFLJLonRdp3y8ImP8InoOZfFhnE283M3zGlPRQ19oafcM%2FSvRI%2FCfihnomoGEmoXCtlxMn%2Fk2y87dkwb%2Bvra8TlKv8Ul&X-Amz-Signature=c4b460c376d8107ceb40125d90816436a5cf13f2bfdf0de10facea8a434426e2&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664PADI5LV%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T183247Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCqmsmrL37a35aVwHZ%2F14p56OICdk2cdVL7rwgiljPbqQIgUVkQD%2F8FsAA2SuDDU7zq2i0xHPOSoZ%2FS89NV64nklKYq%2FwMIGxAAGgw2Mzc0MjMxODM4MDUiDHU5DoN3grrOLGgxFSrcA%2B9YDULqx4OCXEunXGA9I%2FkVU6H45T8o0iG27W9v6XJmLvwWpOmilq03OIza3qmUwvEtUQSqDyVweOiffp84UmCAvgvZHQxREXF4zd6MNjOWHSkdyp8ZFk4OJ4%2F6gJ%2BAZIYzfNjKE7Lm%2FBgAAECPN3wvkOF11ivE50B91zBTd2hjJGwBUAgXSSg1YYjbEvv11oGibJ%2FYOnMAdoT9qKvt7T8Wmvn1ejCVkOUjG2euvRzoR8kzE42a6JVC1DTkh86Q%2FfxPmPDhdg31M3tlhXNQs8a0o8Z39NikoxH02uaEeCfoGqhiiy8VKkCjnrSDnog%2Fo2lidFBczhjP4FZ79YaVTzc39b9y5qgA3lhir2gfWy375dJD%2BS8wi%2FeHUX%2FNV%2FsPqPagGx%2B3o6bhJTzs%2FJoUIF1p1%2BLVsJUOU%2BqCU9bGz3%2FLQR2ncgETTjNkGug4qmWaX%2FTQpygVDp%2B4MQ5LVxtj6v2SEMZvvZt6Xu76%2B845Q1K312UQDH0Nju99MUePGGoWvC%2BRfFOKmea3e2gG9Ka3%2Fn%2B9ke9dwv11X5djL3DJrVtxovZAa5vi3dI5O%2FBSQfcKTiQjUQDzSR1JyXE4dLUmLLk4djlRgVdPssRmUARaTIFztdKL2wzEBumhmM5yMITfuL0GOqUBQLlS8npIre36%2B0xqXGUPdNXIie7%2FgJw9wuO19z89mnzLx2LVKAUfbHPFYwtV8JWGbxde37Fu6Q2Z4zYk0%2BqthkhyvOcWOxYGAr9BBQ1jaDINMi%2BBuLwdK9assdim%2Btqt5h0STOK1T1FvDqrpIrGqs5QxsRC6INfE%2FBUYpgkKLK9khQcFuk3lsO10TLICdHucICvOo%2BprBKIFRpoWL3ZdLGDASRwi&X-Amz-Signature=21e0b83336a9cd78095194b1f518282b5a4799dcd77357aa6a02b99153332e55&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZDVERUGZ%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T183247Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIFjfGLXwcUBL5wLj4rYTJziEFrAd1CEGJkwdShKozhWkAiAsYQ0fZcxgMQ5krM9aw6cLRPjwnIQVw29JJMpj%2BR9efir%2FAwgbEAAaDDYzNzQyMzE4MzgwNSIMyQKuAm1H5y%2BbuLNgKtwDJje4Wo0YEEygcjWYcPNsjjdLjkPBSbEpJMkm4U7jcc2aqdPjDeF5v2NKQkxaLnl4CaYR9H%2FgR4rI2Kz1DPePM%2BTv%2B3E2vt%2BcGs9LNg2XSwMpX8VPzNHEHArEWsUcdnGzDJWbquQvr66oS8bZD0tpah%2BChywTomA9iOimZZfZsox%2B8BwPepQ5EBreOBl%2F3%2FI2kxCaQtCjFZEHi%2Br0GTxRqfdClCxOXzUXDWuplPkUix5PSy%2BL%2F1OWg5rFACDkjlRHPsiPs54Z0F62BH1swQz2K8BqTnmJDKU4q0AjUgHURWw6ySySDOqwxuRO2zKyLN6DPfa4ha0Q59WdZKCLcPccQqQMvALQGKhnKStNAJwElLUZ9%2Fl1rbtbBPK9Q67OaxHVc2Hkqs06jh0MSI0kz67SVZ6vACTfH2YYYfRvgH9ZeCDMqH7BwIHO2vsIuKj0WbNv9NGXbv4xyZ7O9BA2zcNzoyURAUNYXxuby9k1vTFC8KDS0q5OwghFX7TfQ%2FDoCSowgKU%2BFMjkj22YlvUExnbtR4qMqb5%2B0zlUWv4yc3BMZ2YpGoSV8A%2BSq4b2qrc5Q8PWaquTbWy76Qh9OauGMQGDLhc21%2BwOYMuVfJrdErdydxVCSo4Z4ps1quv%2BuYMwoN%2B4vQY6pgGtFw7j7NWVlRTbE9Y7RGXDV5dPAQleX19JF0Q%2BjmA6y4I%2B8nraFDLQgYYDi6HZ65VrRJBNd5LVndizPp42DFbr4BqFPyuzX2nwWstM7sfQMN0Wp2nF%2BpW0NNqa6%2BInYA0scavTzNd6NkphKm50wycG2gMWwYDpjdXEBfFgEm0EEFUlMD7bl6rcIVn5C0UgMlBt5SSCsKSEt%2F%2F%2FemPHI5fWn1DvnTf1&X-Amz-Signature=0eada1e34ed4127eaf046472bec92a39e4e9e23c121015e3bc6ca48cffd485f9&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QW3GZP3Y%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T183246Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCQ1pk47DiDzuePfItSarVsPjs34ppl4HZFAlPrR9rvjQIgK0Wty5UIC1FGugy2tiLC%2FwHCg3iFBE3QtZuOr47kRi8q%2FwMIGxAAGgw2Mzc0MjMxODM4MDUiDNwgyRydYO9GDxeuDSrcA4Dz3OEKf54qwuhfyB%2FLOJ4pIaKjTMgmTqCJwZBF%2BZqAv%2FqSmd7emTf1ER0omKq79SjfBZX9lO1h2tQuz7gCOd5iFQF1X51aL3VdGZ18MnYbVj9AKHGa9X3oiZs1HOzUKx31NODvykU3ljgEwHQEAE1gYp9afIa%2BnCgmw7ZKaWmtd0yMyxhJAYMHr1rrpXhVlhYJ0QYD%2BJKXFRqvfq9XydDsv6pmnOR3t1dwYDdFyFraOjEkHoVaq0Fi6ZX2iiceOzJQ9SFndqGMc6iWoQO9E63Qvx7e5dhAV0OdH1PO2VQpvRiplu6O0%2BEcQqqqUweYPcvMjFMda4ofYcQzvUn6PIq4x8lDSCUxcCbE6A%2Ba1aj8fhciPK9Pm6IrLwjnsWQHo9lJohqy4JGjit2FBtF2UfpfyGXImnbYa8uvQdPcBJIAQNUlAZ9kHawSjHD%2BP9c6XPibXyKfxrNO5ZVQIlqNaxLfqCy9SoRbgmlt99LEe0ESr8JhvSri8HqZ9u2WIdubI0mFKValh8Q%2F%2BXyNgeM2dLQzLDEYguDnR0%2B0477RTtcBNTkcsPkoHJutv09raQNci7Jd8c4Fn2CRsmrPfKwk%2Fr6VvWGY0erW0eGhvhQdjrp%2FnU6NIgtYeZiehUExMIbfuL0GOqUBYey1CSt2PRRqPCTK2IYtXMuefyTJcflpoBzbK3s%2FIckxhIS3%2Bd9ID2MB%2FK7s84EASCGiD4RvKd5FQwazRB1Ps0NTbTzHMdKP%2B5L5VRfk%2BnclkCJTkmcMir5uzH%2F8C5NG%2FFLJLonRdp3y8ImP8InoOZfFhnE283M3zGlPRQ19oafcM%2FSvRI%2FCfihnomoGEmoXCtlxMn%2Fk2y87dkwb%2Bvra8TlKv8Ul&X-Amz-Signature=6151e4300234dd7007ae9b2177c4580b128567c7a17375fd4aae0a83f6616aff&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QW3GZP3Y%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T183246Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCQ1pk47DiDzuePfItSarVsPjs34ppl4HZFAlPrR9rvjQIgK0Wty5UIC1FGugy2tiLC%2FwHCg3iFBE3QtZuOr47kRi8q%2FwMIGxAAGgw2Mzc0MjMxODM4MDUiDNwgyRydYO9GDxeuDSrcA4Dz3OEKf54qwuhfyB%2FLOJ4pIaKjTMgmTqCJwZBF%2BZqAv%2FqSmd7emTf1ER0omKq79SjfBZX9lO1h2tQuz7gCOd5iFQF1X51aL3VdGZ18MnYbVj9AKHGa9X3oiZs1HOzUKx31NODvykU3ljgEwHQEAE1gYp9afIa%2BnCgmw7ZKaWmtd0yMyxhJAYMHr1rrpXhVlhYJ0QYD%2BJKXFRqvfq9XydDsv6pmnOR3t1dwYDdFyFraOjEkHoVaq0Fi6ZX2iiceOzJQ9SFndqGMc6iWoQO9E63Qvx7e5dhAV0OdH1PO2VQpvRiplu6O0%2BEcQqqqUweYPcvMjFMda4ofYcQzvUn6PIq4x8lDSCUxcCbE6A%2Ba1aj8fhciPK9Pm6IrLwjnsWQHo9lJohqy4JGjit2FBtF2UfpfyGXImnbYa8uvQdPcBJIAQNUlAZ9kHawSjHD%2BP9c6XPibXyKfxrNO5ZVQIlqNaxLfqCy9SoRbgmlt99LEe0ESr8JhvSri8HqZ9u2WIdubI0mFKValh8Q%2F%2BXyNgeM2dLQzLDEYguDnR0%2B0477RTtcBNTkcsPkoHJutv09raQNci7Jd8c4Fn2CRsmrPfKwk%2Fr6VvWGY0erW0eGhvhQdjrp%2FnU6NIgtYeZiehUExMIbfuL0GOqUBYey1CSt2PRRqPCTK2IYtXMuefyTJcflpoBzbK3s%2FIckxhIS3%2Bd9ID2MB%2FK7s84EASCGiD4RvKd5FQwazRB1Ps0NTbTzHMdKP%2B5L5VRfk%2BnclkCJTkmcMir5uzH%2F8C5NG%2FFLJLonRdp3y8ImP8InoOZfFhnE283M3zGlPRQ19oafcM%2FSvRI%2FCfihnomoGEmoXCtlxMn%2Fk2y87dkwb%2Bvra8TlKv8Ul&X-Amz-Signature=a8d6f4696331edc285f546f14bd1e202e2d0cbad21031a2b817835fde3a7bcb1&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QW3GZP3Y%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T183246Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCQ1pk47DiDzuePfItSarVsPjs34ppl4HZFAlPrR9rvjQIgK0Wty5UIC1FGugy2tiLC%2FwHCg3iFBE3QtZuOr47kRi8q%2FwMIGxAAGgw2Mzc0MjMxODM4MDUiDNwgyRydYO9GDxeuDSrcA4Dz3OEKf54qwuhfyB%2FLOJ4pIaKjTMgmTqCJwZBF%2BZqAv%2FqSmd7emTf1ER0omKq79SjfBZX9lO1h2tQuz7gCOd5iFQF1X51aL3VdGZ18MnYbVj9AKHGa9X3oiZs1HOzUKx31NODvykU3ljgEwHQEAE1gYp9afIa%2BnCgmw7ZKaWmtd0yMyxhJAYMHr1rrpXhVlhYJ0QYD%2BJKXFRqvfq9XydDsv6pmnOR3t1dwYDdFyFraOjEkHoVaq0Fi6ZX2iiceOzJQ9SFndqGMc6iWoQO9E63Qvx7e5dhAV0OdH1PO2VQpvRiplu6O0%2BEcQqqqUweYPcvMjFMda4ofYcQzvUn6PIq4x8lDSCUxcCbE6A%2Ba1aj8fhciPK9Pm6IrLwjnsWQHo9lJohqy4JGjit2FBtF2UfpfyGXImnbYa8uvQdPcBJIAQNUlAZ9kHawSjHD%2BP9c6XPibXyKfxrNO5ZVQIlqNaxLfqCy9SoRbgmlt99LEe0ESr8JhvSri8HqZ9u2WIdubI0mFKValh8Q%2F%2BXyNgeM2dLQzLDEYguDnR0%2B0477RTtcBNTkcsPkoHJutv09raQNci7Jd8c4Fn2CRsmrPfKwk%2Fr6VvWGY0erW0eGhvhQdjrp%2FnU6NIgtYeZiehUExMIbfuL0GOqUBYey1CSt2PRRqPCTK2IYtXMuefyTJcflpoBzbK3s%2FIckxhIS3%2Bd9ID2MB%2FK7s84EASCGiD4RvKd5FQwazRB1Ps0NTbTzHMdKP%2B5L5VRfk%2BnclkCJTkmcMir5uzH%2F8C5NG%2FFLJLonRdp3y8ImP8InoOZfFhnE283M3zGlPRQ19oafcM%2FSvRI%2FCfihnomoGEmoXCtlxMn%2Fk2y87dkwb%2Bvra8TlKv8Ul&X-Amz-Signature=5e3caa736b3c18a846e96d4158d76c45901a868e9708473c91611962f8cbe729&X-Amz-SignedHeaders=host&x-id=GetObject)


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

