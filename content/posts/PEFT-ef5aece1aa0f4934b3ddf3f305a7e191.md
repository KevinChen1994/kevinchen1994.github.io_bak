---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466TYV2EOPB%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250214T124442Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEAUaCXVzLXdlc3QtMiJHMEUCIGNfQvbFBMeltQTyB6t1slrHCeTLBa1AR7yn4OhSPTtQAiEArV3\
  mXy87BZ9DZeZ9G1xAuDCDEesImU%2FgMm118V%2B6e5Uq%2FwMILRAAGgw2Mzc0MjMxODM4MDUiDM\
  J30bhv%2B%2B7t2DjZVyrcAwjmF7f295RNugBYLrsURQgXq86EgzSMb6n8rE7ug%2FDMdJ6A6LZso\
  kyJ4wy%2Fz%2F850X%2Bhj1pYifbHybVJH5HrBBuYXbA5FQV%2FV9XLPgPnhV8Ycaz6g%2FGBSHRp\
  1LHkqGH5Nh1Co%2BY%2F4XhCnDRrNEuBu2DzR3F1voqSaB0AL12Kj%2FPDnq0N6Qh41tsVZV6Gb8K\
  %2FO6Fs4K6urXlsvedou6lGZzdVROdTSwevee82sHepntcVsNfdfdnXrLR1EqldHA%2B672yp9xXM\
  pP08BJ8JvJFcpJ%2FBiL6QxAHaFnpXR4MRWZUDgCRXKfOEAmSCC%2BrVj%2Bl4ARWe1enUi9XwaXB\
  9fr7EzbMIADgdrd%2F%2Fnc4dWvycudM7hLY0Nls045LDnEbvIs8%2F0tdjyKwpXpo2BSzG6TAyNJ\
  rSd6wE49AFM18IpKEF9wdDFXqJHSla03JeDfZeFkMsmMwYiNJFJImLn4nc2Rzj%2BuT9SC78Ut8fS\
  yP3wFdB%2BRUnGyOFZjCxzlDwudjuf7NYFAAb8mcXxZniCAcEe2TtCtM1PWlrjWIOcaRzLTIVkwA7\
  LooxpHSlbcYn2uK5izU%2BmJYi2Aa4gaUMQ%2BC%2BCtDQ7fnq6QxCeF%2BQ6RoqFbYA58e5itd9V\
  Zka1OJwkR2IMP3qvL0GOqUBlxwOfv2fVPSS9avJL0p7ojgQTTqwsAiAf03g%2FPj86pNnqIGlvHXM\
  mOBCGKfVTXdOE4u64IwsdKAq6yDgPi%2BGX8Qj87lrc7%2FONgfxV9VqRxoj6g2%2FsFwecOpYmE%\
  2Fn9SF2sHeKVjwo0vDL49gZ8SAT3qAe%2FFv9jU6ikEvslcvFIY5wtYEv0fxirPNnVc4fU36hABU3\
  8uQQfdq9WAe43zE9TF3Pes2m&X-Amz-Signature=58c0fd6b52e865409c4643f5b4d6d92e5dc0\
  1905534d0393be8b07f04b2a31fe&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB46622EJKCTA%2F20250214%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250214T124323Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEAUaCXVzLXdlc3QtMiJIMEYCIQDCbWq0rOhg4fe1amN0LlbTWzt%2B4\
        w8Gdb6LRuZtB61OQgIhAMDVAtEhm3tTDTrRfuW8e8Wzeqov5y1Cb5P%2FgYG2pYdsKv8DCC\
        0QABoMNjM3NDIzMTgzODA1IgzQLWBZFhBnuIyPwTMq3AOE2XqhxilYopjTxOm1Xw%2BQs8p\
        RANHCWClajdlU30qnHN3Fy6O%2Bznlkj8CXO%2FRXIyqBSO7XdN71CO4H9r8LpoW3QJer5q\
        GyMBnYA8LDQPvDytvHFL9Xu7k8TUxWfCoBs9o9l%2FEC2pc7sVKQE6TLT2mgVbL9L2XI%2B\
        EvDusaQDdXExq0V8DjNaDTXiUjgZllDCVfwAZQXuk%2FKeIEItK6SE7FD3uXpugQj3Do27n\
        WGDDCeAKJQ7TvTcL9W96MVWGxeC16IQ%2FqwmsDy8XFkV%2FUT4eFFmjZpufUqDUnKjYQIF\
        rw2Acspun7TDrk4KhV7TjT9MZ7TmqtvXLFIF8KGhnY0BqG%2BDt7JJzyrgDXxrFqy9tTqWP\
        %2FwVIgAvOorBekh5UFd15ssDnDoubOcLJl%2BtM4QLQnnzCzQ%2FPdpezgXsCcErF1X9J3\
        FkY%2FKa76sZYHD9xG%2Fik7Vm5O%2BMQZ6vP27ITiXgsWo6nTKB44POh8lP00426mnNN7M\
        7dYb3cfEPEOOD7w6LyQm%2FxFmOxIKpFT5%2BAYu1IMxv%2BL7uponk1amHM%2BgwzYFFUv\
        BBRuGd5jUi9Z1lo3%2BAVdUrXXIY25Rh1ANjFY4b2r9aLzsTl8DiBBG1zkJmw%2BlyS22XO\
        BY%2FpC9wC5fmDDB6ry9BjqkAaY%2B6y98ZLZJA3fWakL9y5M6IKRNT2H0oiC4v3Fn1lQRA\
        ubwgUDA%2FoWNAhHP2X7VicpAQrqvioGiawJlbOcXMYHHQz2IYlDJyHwmGbue4W5I44Tnvh\
        kOSsmOwoZzqBGG6OmSPRub1oDDpxt7yNo3%2FfT7%2Bflvmmwbqy64qLAfk5EketbC8R%2B\
        %2B0z4DU1gYXybKWcOalieN68H1KEbD9ODzngYvo8zV&X-Amz-Signature=3c109664171\
        74139cd07d669add1ea2ee3ccb388282ec45ddd80fbbea48fcc65&X-Amz-SignedHeade\
        rs=host&x-id=GetObject"
      expiry_time: "2025-02-14T13:43:23.336Z"
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
UPDATE_TIME: "2025-02-14T12:44:48.850Z"
EXPIRY_TIME: "2025-02-14T13:44:36.703Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663442IXOK%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T124437Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAUaCXVzLXdlc3QtMiJIMEYCIQDfiaAD9RLkgYB4aPwkl3trPUlAwtpyAgVbUzTOQPFGbwIhAPuMwM0COpLc8xAmkof5D%2FDG0CqWIZPrRcimH51Dhi05Kv8DCC0QABoMNjM3NDIzMTgzODA1IgxD5O4bxPHC3Qy1yjwq3AP6WOyz35UyuKztWSCKX%2Fz5tWS48Q3xsmiMNuHxDdesa5C%2FOyNjnJu2adrmBYEjZO2DG5rbdIkturcq8xCUgNrZqjFRpLbkOw8mDmIu2nGHuh4M0q%2B4F3Jspf2QTa1ECiGx7tt%2BIRyr13LEwl4pcFeUg8cmbjNE%2FHJ7sOIbEVNv1iAnRBryzvc5RH0M9OwWeMHNVVhgqr%2B8hAbTysU4jrrM1WBVNKieDqvh3OR8Or%2FIkRKbrifcMMVmI2xHvxalIUNpK3gdxWZNilI3GQRzlkRhYf5tr8JSTUFaJBw5o1aRmTiN7wdEK3w6nwgHgDxLfV4QDuocnocun4lQzx2%2F%2B7Von25GlnZs23Fvc6hD2Fn5O%2FryVKJ8qF%2BZucgGP5pocnqIgc0sOL4NbKzrlXLbLZKfAEHLtPbWdvtYQ3FzeHhBZXVbnFM6CDChNmk7aCw6G6o15OWY5UHT4vrWXUb8HTLlmbEaODXrK3q6Fnn6hzJcFcEhz%2BVc8QF%2BqCc7QLSxoxmQ08ek0EpGxR0YF7FjJvT9Ke431C71PrChaMT82mtrvCvbYSdqI1Z7suEwWggxVgrcjnheDrSXWqB2XDkEQV4wy2ZSFnw8qkBs0WQC9LoqGnQAE1hqmm48b1UkmDDs6ry9BjqkAWE3Szd8YVyiA9Ty%2BHoqwiCPswoCqXhFTUb1RAV0edc9%2B8B3q794Q%2FYZcyMGaOtHWDlcNvea1MTkntmHAfJ5lQWntLRBiE9M7%2F73ke4J%2FqgYYXN8ewBbeIIvNyfXmz2899P9gPM%2BWHxP36ra8FM8wp%2Fu7fGCpRXyC2yjbMfsqKXTB9dKKva64yPVlJ2Y8kogcp4aozQrtbcMnRD1a7xNlipn16xq&X-Amz-Signature=ba991162071f9ecf91f38e45a339a43d02bc4a0f335b86bd7e70c0f930a88457&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663442IXOK%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T124437Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAUaCXVzLXdlc3QtMiJIMEYCIQDfiaAD9RLkgYB4aPwkl3trPUlAwtpyAgVbUzTOQPFGbwIhAPuMwM0COpLc8xAmkof5D%2FDG0CqWIZPrRcimH51Dhi05Kv8DCC0QABoMNjM3NDIzMTgzODA1IgxD5O4bxPHC3Qy1yjwq3AP6WOyz35UyuKztWSCKX%2Fz5tWS48Q3xsmiMNuHxDdesa5C%2FOyNjnJu2adrmBYEjZO2DG5rbdIkturcq8xCUgNrZqjFRpLbkOw8mDmIu2nGHuh4M0q%2B4F3Jspf2QTa1ECiGx7tt%2BIRyr13LEwl4pcFeUg8cmbjNE%2FHJ7sOIbEVNv1iAnRBryzvc5RH0M9OwWeMHNVVhgqr%2B8hAbTysU4jrrM1WBVNKieDqvh3OR8Or%2FIkRKbrifcMMVmI2xHvxalIUNpK3gdxWZNilI3GQRzlkRhYf5tr8JSTUFaJBw5o1aRmTiN7wdEK3w6nwgHgDxLfV4QDuocnocun4lQzx2%2F%2B7Von25GlnZs23Fvc6hD2Fn5O%2FryVKJ8qF%2BZucgGP5pocnqIgc0sOL4NbKzrlXLbLZKfAEHLtPbWdvtYQ3FzeHhBZXVbnFM6CDChNmk7aCw6G6o15OWY5UHT4vrWXUb8HTLlmbEaODXrK3q6Fnn6hzJcFcEhz%2BVc8QF%2BqCc7QLSxoxmQ08ek0EpGxR0YF7FjJvT9Ke431C71PrChaMT82mtrvCvbYSdqI1Z7suEwWggxVgrcjnheDrSXWqB2XDkEQV4wy2ZSFnw8qkBs0WQC9LoqGnQAE1hqmm48b1UkmDDs6ry9BjqkAWE3Szd8YVyiA9Ty%2BHoqwiCPswoCqXhFTUb1RAV0edc9%2B8B3q794Q%2FYZcyMGaOtHWDlcNvea1MTkntmHAfJ5lQWntLRBiE9M7%2F73ke4J%2FqgYYXN8ewBbeIIvNyfXmz2899P9gPM%2BWHxP36ra8FM8wp%2Fu7fGCpRXyC2yjbMfsqKXTB9dKKva64yPVlJ2Y8kogcp4aozQrtbcMnRD1a7xNlipn16xq&X-Amz-Signature=8b5e8efb2e9fbeced78d658dcc58caee98dae0de7dce783dbeeefb9bc3597e69&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663442IXOK%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T124437Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAUaCXVzLXdlc3QtMiJIMEYCIQDfiaAD9RLkgYB4aPwkl3trPUlAwtpyAgVbUzTOQPFGbwIhAPuMwM0COpLc8xAmkof5D%2FDG0CqWIZPrRcimH51Dhi05Kv8DCC0QABoMNjM3NDIzMTgzODA1IgxD5O4bxPHC3Qy1yjwq3AP6WOyz35UyuKztWSCKX%2Fz5tWS48Q3xsmiMNuHxDdesa5C%2FOyNjnJu2adrmBYEjZO2DG5rbdIkturcq8xCUgNrZqjFRpLbkOw8mDmIu2nGHuh4M0q%2B4F3Jspf2QTa1ECiGx7tt%2BIRyr13LEwl4pcFeUg8cmbjNE%2FHJ7sOIbEVNv1iAnRBryzvc5RH0M9OwWeMHNVVhgqr%2B8hAbTysU4jrrM1WBVNKieDqvh3OR8Or%2FIkRKbrifcMMVmI2xHvxalIUNpK3gdxWZNilI3GQRzlkRhYf5tr8JSTUFaJBw5o1aRmTiN7wdEK3w6nwgHgDxLfV4QDuocnocun4lQzx2%2F%2B7Von25GlnZs23Fvc6hD2Fn5O%2FryVKJ8qF%2BZucgGP5pocnqIgc0sOL4NbKzrlXLbLZKfAEHLtPbWdvtYQ3FzeHhBZXVbnFM6CDChNmk7aCw6G6o15OWY5UHT4vrWXUb8HTLlmbEaODXrK3q6Fnn6hzJcFcEhz%2BVc8QF%2BqCc7QLSxoxmQ08ek0EpGxR0YF7FjJvT9Ke431C71PrChaMT82mtrvCvbYSdqI1Z7suEwWggxVgrcjnheDrSXWqB2XDkEQV4wy2ZSFnw8qkBs0WQC9LoqGnQAE1hqmm48b1UkmDDs6ry9BjqkAWE3Szd8YVyiA9Ty%2BHoqwiCPswoCqXhFTUb1RAV0edc9%2B8B3q794Q%2FYZcyMGaOtHWDlcNvea1MTkntmHAfJ5lQWntLRBiE9M7%2F73ke4J%2FqgYYXN8ewBbeIIvNyfXmz2899P9gPM%2BWHxP36ra8FM8wp%2Fu7fGCpRXyC2yjbMfsqKXTB9dKKva64yPVlJ2Y8kogcp4aozQrtbcMnRD1a7xNlipn16xq&X-Amz-Signature=c18a0c232ee1c6fed7cda890abee54c66356a7534e049b4324e7477e8f783b35&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663442IXOK%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T124437Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAUaCXVzLXdlc3QtMiJIMEYCIQDfiaAD9RLkgYB4aPwkl3trPUlAwtpyAgVbUzTOQPFGbwIhAPuMwM0COpLc8xAmkof5D%2FDG0CqWIZPrRcimH51Dhi05Kv8DCC0QABoMNjM3NDIzMTgzODA1IgxD5O4bxPHC3Qy1yjwq3AP6WOyz35UyuKztWSCKX%2Fz5tWS48Q3xsmiMNuHxDdesa5C%2FOyNjnJu2adrmBYEjZO2DG5rbdIkturcq8xCUgNrZqjFRpLbkOw8mDmIu2nGHuh4M0q%2B4F3Jspf2QTa1ECiGx7tt%2BIRyr13LEwl4pcFeUg8cmbjNE%2FHJ7sOIbEVNv1iAnRBryzvc5RH0M9OwWeMHNVVhgqr%2B8hAbTysU4jrrM1WBVNKieDqvh3OR8Or%2FIkRKbrifcMMVmI2xHvxalIUNpK3gdxWZNilI3GQRzlkRhYf5tr8JSTUFaJBw5o1aRmTiN7wdEK3w6nwgHgDxLfV4QDuocnocun4lQzx2%2F%2B7Von25GlnZs23Fvc6hD2Fn5O%2FryVKJ8qF%2BZucgGP5pocnqIgc0sOL4NbKzrlXLbLZKfAEHLtPbWdvtYQ3FzeHhBZXVbnFM6CDChNmk7aCw6G6o15OWY5UHT4vrWXUb8HTLlmbEaODXrK3q6Fnn6hzJcFcEhz%2BVc8QF%2BqCc7QLSxoxmQ08ek0EpGxR0YF7FjJvT9Ke431C71PrChaMT82mtrvCvbYSdqI1Z7suEwWggxVgrcjnheDrSXWqB2XDkEQV4wy2ZSFnw8qkBs0WQC9LoqGnQAE1hqmm48b1UkmDDs6ry9BjqkAWE3Szd8YVyiA9Ty%2BHoqwiCPswoCqXhFTUb1RAV0edc9%2B8B3q794Q%2FYZcyMGaOtHWDlcNvea1MTkntmHAfJ5lQWntLRBiE9M7%2F73ke4J%2FqgYYXN8ewBbeIIvNyfXmz2899P9gPM%2BWHxP36ra8FM8wp%2Fu7fGCpRXyC2yjbMfsqKXTB9dKKva64yPVlJ2Y8kogcp4aozQrtbcMnRD1a7xNlipn16xq&X-Amz-Signature=da0bf508e8bca260afcc167168b27c95a28492981ef5159c44da59480c025ca1&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663442IXOK%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T124437Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAUaCXVzLXdlc3QtMiJIMEYCIQDfiaAD9RLkgYB4aPwkl3trPUlAwtpyAgVbUzTOQPFGbwIhAPuMwM0COpLc8xAmkof5D%2FDG0CqWIZPrRcimH51Dhi05Kv8DCC0QABoMNjM3NDIzMTgzODA1IgxD5O4bxPHC3Qy1yjwq3AP6WOyz35UyuKztWSCKX%2Fz5tWS48Q3xsmiMNuHxDdesa5C%2FOyNjnJu2adrmBYEjZO2DG5rbdIkturcq8xCUgNrZqjFRpLbkOw8mDmIu2nGHuh4M0q%2B4F3Jspf2QTa1ECiGx7tt%2BIRyr13LEwl4pcFeUg8cmbjNE%2FHJ7sOIbEVNv1iAnRBryzvc5RH0M9OwWeMHNVVhgqr%2B8hAbTysU4jrrM1WBVNKieDqvh3OR8Or%2FIkRKbrifcMMVmI2xHvxalIUNpK3gdxWZNilI3GQRzlkRhYf5tr8JSTUFaJBw5o1aRmTiN7wdEK3w6nwgHgDxLfV4QDuocnocun4lQzx2%2F%2B7Von25GlnZs23Fvc6hD2Fn5O%2FryVKJ8qF%2BZucgGP5pocnqIgc0sOL4NbKzrlXLbLZKfAEHLtPbWdvtYQ3FzeHhBZXVbnFM6CDChNmk7aCw6G6o15OWY5UHT4vrWXUb8HTLlmbEaODXrK3q6Fnn6hzJcFcEhz%2BVc8QF%2BqCc7QLSxoxmQ08ek0EpGxR0YF7FjJvT9Ke431C71PrChaMT82mtrvCvbYSdqI1Z7suEwWggxVgrcjnheDrSXWqB2XDkEQV4wy2ZSFnw8qkBs0WQC9LoqGnQAE1hqmm48b1UkmDDs6ry9BjqkAWE3Szd8YVyiA9Ty%2BHoqwiCPswoCqXhFTUb1RAV0edc9%2B8B3q794Q%2FYZcyMGaOtHWDlcNvea1MTkntmHAfJ5lQWntLRBiE9M7%2F73ke4J%2FqgYYXN8ewBbeIIvNyfXmz2899P9gPM%2BWHxP36ra8FM8wp%2Fu7fGCpRXyC2yjbMfsqKXTB9dKKva64yPVlJ2Y8kogcp4aozQrtbcMnRD1a7xNlipn16xq&X-Amz-Signature=c3accd9461efcd2e9731ae629025afeb51d5b64cb46f3cbd924f2539eea0d484&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665MUSHFD4%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T124438Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAUaCXVzLXdlc3QtMiJHMEUCIH89n6rFDbASLs8jqI1nBNIpIVwZ8kDfuvySDlICNQ3oAiEAng1co2ONkCLZ%2BTgfiIV3FHFPSs41Tk9SeD1nWQI%2BdGsq%2FwMILRAAGgw2Mzc0MjMxODM4MDUiDGEx8rHCss0rTDSkJircAyxyfmUo87QUNnYShWK5ZE7I2Jt7VChVFOiuA29B1l3o1xgh%2BKa9lgDAPoPp1VIfZrGgDwEsE5WVicdC0M6bVZHIH76K9ZLoe12yLbFd4aG7Qzcum6Ukp0l9VM3SrjytV4aME6l7gL0EYaOKcH4br3qR8FhpxlQxiE2q29tY1KEhqNGI7VlQp%2BH1%2BzwfgRLkNUMS0%2BDzl1kS2v7HWmnuyWmR74V5oxPsqnivvGs5Pphp3MLPvmXlg6g1Za32ua8JOm0YlZ4Mrve3QL5WL25JixFlRHVyc8fU%2BSiWegCvKVdS7D%2BfXxykz54qnrk%2BgkhUxAnOzsg%2B3kK2%2BRa65l6xoL8kBES8VnEkiaveNC5U%2BZubFDErWPFvePO4pZ2e8AvjgAGiXc0FytiFYbRn%2B%2FbIQN5Jzjb4d4yc1oeMrbJlksHV2TxwggX6tRcic9kqDhS5O5nIriv2IjEnMx8NYEnk6dv6lZgk7fhUTGxicQbvFwHT%2BmfQJo83AhCLSzqCDChW956WME2OK08ejEjAntM79UAOdyFJIUDMTCLeVaIYSKnMps2wcc21yFYQND2UnPgGPQ%2F0PzuFt9cgpDkPs17%2F0PHGpo%2BzdfJ1aOUyuhR17ng00otlK0CWZCqvt1wFMNrqvL0GOqUBehxp9oaqLNDxb6hJpsYzMcwg2uRwZci0U0OdDFOSbHCACIqB2BejvAZxKC6SCEDDiabpKEjSGcitEw%2BDcZj6CzFa%2BdukF3aZIJriA6%2BRwLg6ixm%2Bj7bNo5Dlb%2FXjeF09vFYAkCA6pMKyEaAXX8g37j8%2FyDP1rUlMMeSIA5bUUKViIEG6pqz5I83jknPnv3vMr9Ai%2Ffudza%2B5QwXjUqsW95uVw%2FAi&X-Amz-Signature=486188eaeb62b6df6981a6aac6dc8002ab55c9dee7b25369bb694fcbec2f0a86&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YRFKDAJ4%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T124440Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAUaCXVzLXdlc3QtMiJGMEQCIBiYcD%2BkN338KZ75vNNzU9yjcCi8sHa6Ct1SWya7iPhFAiBBbep3soS56W1Tw%2FIVHQh3DguYCehJxIt%2BKYGUZGkENCr%2FAwgtEAAaDDYzNzQyMzE4MzgwNSIMHURVLcyLNlsFkiu2KtwDOmRomQ2rOGR1E5CGCNEy9s%2BhMEXMA52FCqu4ayi6DjQXMCfsWgg6Bd3HM11B0rFy5JtzNM0nxkp5BkiMFR92om3zMydTYh%2F%2BeLj3VmMx9cRSb6psL2gNqItsJL8D62MycRVhqmQUTKf51oaibbdCwOIkLCWaQ9FpTSOydfc4umfwBdjn6wfVDHrMqrkdAVTeXALtCkt1FOxl3zrupOfhAkY16f0MEwj5AjO0s7tTMHfhi2B6FtILemJbDKSmMHE4KvKY5UWaY%2Bu4KpUfklFA0rgld6upp0%2BDw3bqREZUzdin1hRGpkVCOkwNXsgB5KKwk7P9I6egVNuAYdGhzb0YJh00gzIdFuE%2Bcc8bagFPcgPwrw9Ek7zo4kKDg9kGnn%2BbW9BtDHAuKOwx0bMINAvA2HR3xuOPankUfNtQNXF7Nx6J4aydVHjCrO9sBc8AlS%2Bk9CMrsXaXoTDii3gmo0e8vDf2tCjEGShaqkczhAJ1cICdP3C2mqmlt67gYRzRGUtL%2FQ8Q%2FNIeAD8gqUL08lIQEtDf3YOq9wLRENCPMyEME%2F%2FaFJ3SMarlnidSv8pe3S2gIqOlK%2BQq1WhPWIq%2Fjib05kbfL40qVLjtc8G9diLgeHBHoIQeZGLVzaWduU4w%2FOq8vQY6pgFjOUMh6HwJ250QLytcT0Of89G%2F3W4JWY4MPdQ6uEIwH3cBUaEelVWxrhqtR1M%2FHMNiKiiLGu6WXa7RkYuHb0bZnnipVDDRie%2FvGWaVMHki80w5WKHXUB5AbY23bFC8UyIUQ953UOtuJDOCjoLU1V6wybbV5ggIoitbhZSy16rd7tXfCV7FM59Q9sHr%2FDR6%2B5SJZshbUkk11aX6HJEhodX61a4Y%2F4Fx&X-Amz-Signature=63bf2b90766f8409df18180a275ede9c9fc6fefbc7b081818d49a94a801d7726&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663442IXOK%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T124437Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAUaCXVzLXdlc3QtMiJIMEYCIQDfiaAD9RLkgYB4aPwkl3trPUlAwtpyAgVbUzTOQPFGbwIhAPuMwM0COpLc8xAmkof5D%2FDG0CqWIZPrRcimH51Dhi05Kv8DCC0QABoMNjM3NDIzMTgzODA1IgxD5O4bxPHC3Qy1yjwq3AP6WOyz35UyuKztWSCKX%2Fz5tWS48Q3xsmiMNuHxDdesa5C%2FOyNjnJu2adrmBYEjZO2DG5rbdIkturcq8xCUgNrZqjFRpLbkOw8mDmIu2nGHuh4M0q%2B4F3Jspf2QTa1ECiGx7tt%2BIRyr13LEwl4pcFeUg8cmbjNE%2FHJ7sOIbEVNv1iAnRBryzvc5RH0M9OwWeMHNVVhgqr%2B8hAbTysU4jrrM1WBVNKieDqvh3OR8Or%2FIkRKbrifcMMVmI2xHvxalIUNpK3gdxWZNilI3GQRzlkRhYf5tr8JSTUFaJBw5o1aRmTiN7wdEK3w6nwgHgDxLfV4QDuocnocun4lQzx2%2F%2B7Von25GlnZs23Fvc6hD2Fn5O%2FryVKJ8qF%2BZucgGP5pocnqIgc0sOL4NbKzrlXLbLZKfAEHLtPbWdvtYQ3FzeHhBZXVbnFM6CDChNmk7aCw6G6o15OWY5UHT4vrWXUb8HTLlmbEaODXrK3q6Fnn6hzJcFcEhz%2BVc8QF%2BqCc7QLSxoxmQ08ek0EpGxR0YF7FjJvT9Ke431C71PrChaMT82mtrvCvbYSdqI1Z7suEwWggxVgrcjnheDrSXWqB2XDkEQV4wy2ZSFnw8qkBs0WQC9LoqGnQAE1hqmm48b1UkmDDs6ry9BjqkAWE3Szd8YVyiA9Ty%2BHoqwiCPswoCqXhFTUb1RAV0edc9%2B8B3q794Q%2FYZcyMGaOtHWDlcNvea1MTkntmHAfJ5lQWntLRBiE9M7%2F73ke4J%2FqgYYXN8ewBbeIIvNyfXmz2899P9gPM%2BWHxP36ra8FM8wp%2Fu7fGCpRXyC2yjbMfsqKXTB9dKKva64yPVlJ2Y8kogcp4aozQrtbcMnRD1a7xNlipn16xq&X-Amz-Signature=687c8aa999fc05e5a60586fddb52e4562a1afdb5e342d3f64d7a9e7f82a7a9d4&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663442IXOK%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T124437Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAUaCXVzLXdlc3QtMiJIMEYCIQDfiaAD9RLkgYB4aPwkl3trPUlAwtpyAgVbUzTOQPFGbwIhAPuMwM0COpLc8xAmkof5D%2FDG0CqWIZPrRcimH51Dhi05Kv8DCC0QABoMNjM3NDIzMTgzODA1IgxD5O4bxPHC3Qy1yjwq3AP6WOyz35UyuKztWSCKX%2Fz5tWS48Q3xsmiMNuHxDdesa5C%2FOyNjnJu2adrmBYEjZO2DG5rbdIkturcq8xCUgNrZqjFRpLbkOw8mDmIu2nGHuh4M0q%2B4F3Jspf2QTa1ECiGx7tt%2BIRyr13LEwl4pcFeUg8cmbjNE%2FHJ7sOIbEVNv1iAnRBryzvc5RH0M9OwWeMHNVVhgqr%2B8hAbTysU4jrrM1WBVNKieDqvh3OR8Or%2FIkRKbrifcMMVmI2xHvxalIUNpK3gdxWZNilI3GQRzlkRhYf5tr8JSTUFaJBw5o1aRmTiN7wdEK3w6nwgHgDxLfV4QDuocnocun4lQzx2%2F%2B7Von25GlnZs23Fvc6hD2Fn5O%2FryVKJ8qF%2BZucgGP5pocnqIgc0sOL4NbKzrlXLbLZKfAEHLtPbWdvtYQ3FzeHhBZXVbnFM6CDChNmk7aCw6G6o15OWY5UHT4vrWXUb8HTLlmbEaODXrK3q6Fnn6hzJcFcEhz%2BVc8QF%2BqCc7QLSxoxmQ08ek0EpGxR0YF7FjJvT9Ke431C71PrChaMT82mtrvCvbYSdqI1Z7suEwWggxVgrcjnheDrSXWqB2XDkEQV4wy2ZSFnw8qkBs0WQC9LoqGnQAE1hqmm48b1UkmDDs6ry9BjqkAWE3Szd8YVyiA9Ty%2BHoqwiCPswoCqXhFTUb1RAV0edc9%2B8B3q794Q%2FYZcyMGaOtHWDlcNvea1MTkntmHAfJ5lQWntLRBiE9M7%2F73ke4J%2FqgYYXN8ewBbeIIvNyfXmz2899P9gPM%2BWHxP36ra8FM8wp%2Fu7fGCpRXyC2yjbMfsqKXTB9dKKva64yPVlJ2Y8kogcp4aozQrtbcMnRD1a7xNlipn16xq&X-Amz-Signature=89ab01e72b73df2c50b675e501194cee45b6436dde5c9ce1c7cda47c12922c14&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663442IXOK%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T124437Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAUaCXVzLXdlc3QtMiJIMEYCIQDfiaAD9RLkgYB4aPwkl3trPUlAwtpyAgVbUzTOQPFGbwIhAPuMwM0COpLc8xAmkof5D%2FDG0CqWIZPrRcimH51Dhi05Kv8DCC0QABoMNjM3NDIzMTgzODA1IgxD5O4bxPHC3Qy1yjwq3AP6WOyz35UyuKztWSCKX%2Fz5tWS48Q3xsmiMNuHxDdesa5C%2FOyNjnJu2adrmBYEjZO2DG5rbdIkturcq8xCUgNrZqjFRpLbkOw8mDmIu2nGHuh4M0q%2B4F3Jspf2QTa1ECiGx7tt%2BIRyr13LEwl4pcFeUg8cmbjNE%2FHJ7sOIbEVNv1iAnRBryzvc5RH0M9OwWeMHNVVhgqr%2B8hAbTysU4jrrM1WBVNKieDqvh3OR8Or%2FIkRKbrifcMMVmI2xHvxalIUNpK3gdxWZNilI3GQRzlkRhYf5tr8JSTUFaJBw5o1aRmTiN7wdEK3w6nwgHgDxLfV4QDuocnocun4lQzx2%2F%2B7Von25GlnZs23Fvc6hD2Fn5O%2FryVKJ8qF%2BZucgGP5pocnqIgc0sOL4NbKzrlXLbLZKfAEHLtPbWdvtYQ3FzeHhBZXVbnFM6CDChNmk7aCw6G6o15OWY5UHT4vrWXUb8HTLlmbEaODXrK3q6Fnn6hzJcFcEhz%2BVc8QF%2BqCc7QLSxoxmQ08ek0EpGxR0YF7FjJvT9Ke431C71PrChaMT82mtrvCvbYSdqI1Z7suEwWggxVgrcjnheDrSXWqB2XDkEQV4wy2ZSFnw8qkBs0WQC9LoqGnQAE1hqmm48b1UkmDDs6ry9BjqkAWE3Szd8YVyiA9Ty%2BHoqwiCPswoCqXhFTUb1RAV0edc9%2B8B3q794Q%2FYZcyMGaOtHWDlcNvea1MTkntmHAfJ5lQWntLRBiE9M7%2F73ke4J%2FqgYYXN8ewBbeIIvNyfXmz2899P9gPM%2BWHxP36ra8FM8wp%2Fu7fGCpRXyC2yjbMfsqKXTB9dKKva64yPVlJ2Y8kogcp4aozQrtbcMnRD1a7xNlipn16xq&X-Amz-Signature=dca5b83dc64223565133b330acfd4fd58c1ecbaf9afc423a198e3fe1f1aef0f0&X-Amz-SignedHeaders=host&x-id=GetObject)


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

