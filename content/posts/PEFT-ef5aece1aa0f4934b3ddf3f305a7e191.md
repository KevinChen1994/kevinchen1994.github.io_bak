---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466SB5BTCQB%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250218T102553Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEGMaCXVzLXdlc3QtMiJHMEUCIDlMflwJrvW7F%2Bqu7dU2b2sN7%2BZRLm7TDp2f%2BK0%2Bbdv\
  5AiEAo2z3hlB36L5BVwPqzlk5zK1USdRRav%2BdcCh0QU2tVhMqiAQIi%2F%2F%2F%2F%2F%2F%2F\
  %2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDZ4HQ9Wdf5I6DlYWCrcA5BtwtrsT4N88YO4so9qq\
  vOrfncdaUIDjP81BJi9sSQZUYh4ca7VMHZAdefatIM3zh5Q6cIqVmOiMTOXiwKsxW%2BKlj5uHPH0\
  raFCsTf85%2B9ZqIvB1OKNilW%2BEcI8RrBkCjr9rhFKsPrLcNSklOwym%2Fy2xOh7fw5d2bA3C2v\
  mA4ZOK9pmUCc0oBNdKb2NJhk6687kbj0yhpGwPyl6OuO9VceJ%2BIuKg%2BdDIISZ6bOzYrusHrO2\
  VRfT38Byqi6ToHKVQbhPVSx61PjQyaI8m5IAPwGu6lhKFbkdcRw3WtIdfCHzyki7j9LL2jRcp%2Fy\
  bXS1S0qHzEeBfeLTUbIK6e56PyidFYn1d9zY3cOMexYZWmwHk1itQRFgo%2FwYZM1zfVfqRiAkwqL\
  DQKgAV%2BzWxsWPJeNoGf8aC4TfAxMJk4NF%2FuUepfPF2zY%2BHVUP5ntlS6rqo3cgM8jL%2B0DX\
  8DXrSHxxx5dl2fwTeXlxu8%2B5hGawH%2FJhgyb2rx2qzEtDIfGyAort7HwW6joILC41%2FoFRSKH\
  1gRO3F691tXxSu98zW5p7RtzDdyAxPIWT%2BZ4h2TkRG7TTQnGgsKnBQ35BkO7OOPrj2B7KTlj2%2\
  FCZtiNe%2FRHzYGHl3rrw5vS0S5KFADi9RvMIa%2F0b0GOqUBbAKaFmuXPtfvxtoypW0MJExhs3bz\
  ZLDIWbt1x2Wl44gIDNyridYyQdkIlp%2By6eRQ%2FQRR95plW0G6xPYoi4egaCw%2BU%2BcdSDfvA\
  C5xOiewJ9TknTwG8IfpdCJrmNwsxOb2tT%2FOzRNvl%2BPK2JjXY%2BCP9vIu0qrTzH%2BepX4pnc\
  tdY%2B3UzGGL5ihtiw7XL%2BnUHOOvQIVI57Vjapn963X9IXCr77hUVmar&X-Amz-Signature=12\
  52604a00c5b28313a8f76dd6b8548f9e70f584a3a8648cd29751a514070466&X-Amz-SignedHe\
  aders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466TQR66LXH%2F20250218%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250218T102431Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEGIaCXVzLXdlc3QtMiJHMEUCIQD0Vv4XpG9l3cr%2BqV43WWI5uA4R2\
        xeRKDIXsD5il5e1WQIgBQzQke0qzRkicPRbpop5%2F2JCYKMZQW2mJLpryFKYKdkqiAQIiv\
        %2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCx%2Bm7UqUMhlK3X\
        y%2BCrcAx2N05SE4cAnNU1fDK7o2P412f0EfbAf7apV8KG9%2Bsla9IcsKKBWKtNz7K4eWQ\
        NjI1SMr07kuHYOhudq9d5zxiY5G8R9xukzlm2VUW0EVWjpm%2BkwV9ry9nZOG3YLX9vBVEr\
        MEP3871jQv5a2rJCl2BKn3OjXY9ZafRi2%2FV68HkIUqhW2X9W0gaBs%2BfnnBnqZFN5%2B\
        nqUM7KJYAvgoPFv079XeIzQN6Gal6LT5bblQmqfWY9VvKJxQFddWoBeLTdMhlEx1eq%2Bjv\
        M9zj%2Fj4DbABkwOO2AzVvMOrkWJMUgUPA00fB2JXvmxn2ULi83zK%2Bcm6UWa3X1fjkh1%\
        2BmJDlUhz3VivSqQ7mZfdLshNN4e%2F2RJ%2B9PbJpRTb7RxGcRsHqBjfEynJ8MzPkhi7Oh\
        8T9rueatPvLI%2FsDMGH6siFcQoeCPw8%2BMv%2FDShFB9ppMDZGrT0AOCmru4i0xWFsgOc\
        ia3mnHmL97piVs5C7v4NPCO%2F6WkkV%2B0XEnm442HSisq9zPWuX3bDnRhKQjjYIE%2FpN\
        eyHLDOsbsU4MR2M8VgQGIyoTP2Z0AtLlngTsE8TefX1m647B9b2t6LUeloNuOwlPOcPDVXQ\
        7i0KtGAH8q%2B%2FwqxkLHO84rcBVTQOxll77xainPMIui0b0GOqUBMCPOrQ14W%2B%2F1k\
        7XoJ6rihUdVAmFAz0eoM%2FnfoiyiOc5HbikrwPuZDb%2B3R5mtNle9L76B%2FpN3H8Qw%2\
        BkWNK6ICh%2BT7dzXrMPSeJQY0r8umRrp6grqNVAO9duxblHv4LHSJ5WFHjV0o0IBo9c6Vg\
        OnK09gpoXJ3%2BdksmOSxD9xuDepxTL80lyKLk%2FJyt3cycJfyoDWxGLQjwlFECSypu1r%\
        2B%2FK1%2B378b&X-Amz-Signature=0e6423de06bb04242193a8817b1985ce03f023c3\
        ef3517a0070f1ff6ec4ecfdc&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-18T11:24:31.840Z"
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
UPDATE_TIME: "2025-02-18T10:25:59.387Z"
EXPIRY_TIME: "2025-02-18T11:25:46.901Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663WCP65Z5%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T102547Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGIaCXVzLXdlc3QtMiJHMEUCIQDG5WNP6kP2gUy63aQ3ob3d1S9HaPvW5e%2FYflvgtoIopgIgCt9A7u8U7rrBqQ5IGsPSJRmZD2fnEDIUYhpXKSJ1kJMqiAQIiv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCB1VRE9wwyx1vndbCrcA4FAeMZIaxh3liu06qlc8%2BBa6V8KdE8Q9fVz%2FpUpU3b9XWrJcMsgBPi6IhVB9zlLzQrOsPIDg7kkyZ2epaxiJJ5hRu%2FosP%2FNn4qp%2BWfHldZ5GT8%2BHkMtgAJrtymWqm8Dmad%2F0xG1%2BdsrMuIRhumebnvV875NDrfc6YE3dtBVHYNjCYr7EqswdbJqa%2B89wz%2BZrfttVbce3U5Jk03ILXmaB6sWdSvCyx%2F6BdMf0AG9nov%2FSqH4E%2FXZbwUdXo%2F2D9%2FCbyuR0m02iXjKcWLuXj5gO72XwNxem2pkDdAVto0kVNBI06rdUVY1MBIBSeVLULrU611rjyxRe44pK5LZjpLvw1tTSy1f%2F3%2BCVRkzTz6v6csGcRz7TsACo2EjB3Hs%2FPqeehhvWXBsw7%2FKkqCVOSuN6u8m0jnyfyRgudLbX8uabjM0SKvFKSsg0OPiy4Crb5MGRPMKnwNVpVdGMouI64IXKAR7ZDHU8On43%2BLJFBIaIP0fiEMlLneAK4nCK1hBcQdWAi1V1YNd9ZU737vth4NbqCgEmE%2BjNXJctMGIfR4Ns0Jrl4i%2Fctdsf%2FNdhVE%2Bm%2Bqp8hxNKfi1SRN1UrczZW8fZNF2qQdhwk09wtZv%2F3LmVUCskoTy7q8OMzjVlKLiMNui0b0GOqUBtkBye9HilqPP1%2FirXAHS3V%2FEEIF%2FtsH4QzkdpjCY0PIMnrap%2BnooT73tGEcLKm7Ap8XJIw7Lw18kh3ubsSz%2FrLllsi9eAfo69%2FwLKuu0%2B1nnRc9XV8Gq7GUa%2F8Tavt6Q8CjycrCZJRTPfSrw1gA3kXEuCq2kYi8hcnRRBMFTOkURYlot5OjwxLT8OBvHb84KBZxDr826tf498gMUw40NDuCP3QaH&X-Amz-Signature=21567c9cec645af2502150d68e1a909ee1af6ce18280e53c288f8c0b13d087b4&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663WCP65Z5%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T102547Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGIaCXVzLXdlc3QtMiJHMEUCIQDG5WNP6kP2gUy63aQ3ob3d1S9HaPvW5e%2FYflvgtoIopgIgCt9A7u8U7rrBqQ5IGsPSJRmZD2fnEDIUYhpXKSJ1kJMqiAQIiv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCB1VRE9wwyx1vndbCrcA4FAeMZIaxh3liu06qlc8%2BBa6V8KdE8Q9fVz%2FpUpU3b9XWrJcMsgBPi6IhVB9zlLzQrOsPIDg7kkyZ2epaxiJJ5hRu%2FosP%2FNn4qp%2BWfHldZ5GT8%2BHkMtgAJrtymWqm8Dmad%2F0xG1%2BdsrMuIRhumebnvV875NDrfc6YE3dtBVHYNjCYr7EqswdbJqa%2B89wz%2BZrfttVbce3U5Jk03ILXmaB6sWdSvCyx%2F6BdMf0AG9nov%2FSqH4E%2FXZbwUdXo%2F2D9%2FCbyuR0m02iXjKcWLuXj5gO72XwNxem2pkDdAVto0kVNBI06rdUVY1MBIBSeVLULrU611rjyxRe44pK5LZjpLvw1tTSy1f%2F3%2BCVRkzTz6v6csGcRz7TsACo2EjB3Hs%2FPqeehhvWXBsw7%2FKkqCVOSuN6u8m0jnyfyRgudLbX8uabjM0SKvFKSsg0OPiy4Crb5MGRPMKnwNVpVdGMouI64IXKAR7ZDHU8On43%2BLJFBIaIP0fiEMlLneAK4nCK1hBcQdWAi1V1YNd9ZU737vth4NbqCgEmE%2BjNXJctMGIfR4Ns0Jrl4i%2Fctdsf%2FNdhVE%2Bm%2Bqp8hxNKfi1SRN1UrczZW8fZNF2qQdhwk09wtZv%2F3LmVUCskoTy7q8OMzjVlKLiMNui0b0GOqUBtkBye9HilqPP1%2FirXAHS3V%2FEEIF%2FtsH4QzkdpjCY0PIMnrap%2BnooT73tGEcLKm7Ap8XJIw7Lw18kh3ubsSz%2FrLllsi9eAfo69%2FwLKuu0%2B1nnRc9XV8Gq7GUa%2F8Tavt6Q8CjycrCZJRTPfSrw1gA3kXEuCq2kYi8hcnRRBMFTOkURYlot5OjwxLT8OBvHb84KBZxDr826tf498gMUw40NDuCP3QaH&X-Amz-Signature=4df385d3811b8236651f9bce423bcca7889c118d47873b31578aa3fa7d127d91&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663WCP65Z5%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T102547Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGIaCXVzLXdlc3QtMiJHMEUCIQDG5WNP6kP2gUy63aQ3ob3d1S9HaPvW5e%2FYflvgtoIopgIgCt9A7u8U7rrBqQ5IGsPSJRmZD2fnEDIUYhpXKSJ1kJMqiAQIiv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCB1VRE9wwyx1vndbCrcA4FAeMZIaxh3liu06qlc8%2BBa6V8KdE8Q9fVz%2FpUpU3b9XWrJcMsgBPi6IhVB9zlLzQrOsPIDg7kkyZ2epaxiJJ5hRu%2FosP%2FNn4qp%2BWfHldZ5GT8%2BHkMtgAJrtymWqm8Dmad%2F0xG1%2BdsrMuIRhumebnvV875NDrfc6YE3dtBVHYNjCYr7EqswdbJqa%2B89wz%2BZrfttVbce3U5Jk03ILXmaB6sWdSvCyx%2F6BdMf0AG9nov%2FSqH4E%2FXZbwUdXo%2F2D9%2FCbyuR0m02iXjKcWLuXj5gO72XwNxem2pkDdAVto0kVNBI06rdUVY1MBIBSeVLULrU611rjyxRe44pK5LZjpLvw1tTSy1f%2F3%2BCVRkzTz6v6csGcRz7TsACo2EjB3Hs%2FPqeehhvWXBsw7%2FKkqCVOSuN6u8m0jnyfyRgudLbX8uabjM0SKvFKSsg0OPiy4Crb5MGRPMKnwNVpVdGMouI64IXKAR7ZDHU8On43%2BLJFBIaIP0fiEMlLneAK4nCK1hBcQdWAi1V1YNd9ZU737vth4NbqCgEmE%2BjNXJctMGIfR4Ns0Jrl4i%2Fctdsf%2FNdhVE%2Bm%2Bqp8hxNKfi1SRN1UrczZW8fZNF2qQdhwk09wtZv%2F3LmVUCskoTy7q8OMzjVlKLiMNui0b0GOqUBtkBye9HilqPP1%2FirXAHS3V%2FEEIF%2FtsH4QzkdpjCY0PIMnrap%2BnooT73tGEcLKm7Ap8XJIw7Lw18kh3ubsSz%2FrLllsi9eAfo69%2FwLKuu0%2B1nnRc9XV8Gq7GUa%2F8Tavt6Q8CjycrCZJRTPfSrw1gA3kXEuCq2kYi8hcnRRBMFTOkURYlot5OjwxLT8OBvHb84KBZxDr826tf498gMUw40NDuCP3QaH&X-Amz-Signature=39dd71e02e8f5209ca6b648f02a16d2922040f0e449321b653a1b9b46b58406d&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663WCP65Z5%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T102547Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGIaCXVzLXdlc3QtMiJHMEUCIQDG5WNP6kP2gUy63aQ3ob3d1S9HaPvW5e%2FYflvgtoIopgIgCt9A7u8U7rrBqQ5IGsPSJRmZD2fnEDIUYhpXKSJ1kJMqiAQIiv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCB1VRE9wwyx1vndbCrcA4FAeMZIaxh3liu06qlc8%2BBa6V8KdE8Q9fVz%2FpUpU3b9XWrJcMsgBPi6IhVB9zlLzQrOsPIDg7kkyZ2epaxiJJ5hRu%2FosP%2FNn4qp%2BWfHldZ5GT8%2BHkMtgAJrtymWqm8Dmad%2F0xG1%2BdsrMuIRhumebnvV875NDrfc6YE3dtBVHYNjCYr7EqswdbJqa%2B89wz%2BZrfttVbce3U5Jk03ILXmaB6sWdSvCyx%2F6BdMf0AG9nov%2FSqH4E%2FXZbwUdXo%2F2D9%2FCbyuR0m02iXjKcWLuXj5gO72XwNxem2pkDdAVto0kVNBI06rdUVY1MBIBSeVLULrU611rjyxRe44pK5LZjpLvw1tTSy1f%2F3%2BCVRkzTz6v6csGcRz7TsACo2EjB3Hs%2FPqeehhvWXBsw7%2FKkqCVOSuN6u8m0jnyfyRgudLbX8uabjM0SKvFKSsg0OPiy4Crb5MGRPMKnwNVpVdGMouI64IXKAR7ZDHU8On43%2BLJFBIaIP0fiEMlLneAK4nCK1hBcQdWAi1V1YNd9ZU737vth4NbqCgEmE%2BjNXJctMGIfR4Ns0Jrl4i%2Fctdsf%2FNdhVE%2Bm%2Bqp8hxNKfi1SRN1UrczZW8fZNF2qQdhwk09wtZv%2F3LmVUCskoTy7q8OMzjVlKLiMNui0b0GOqUBtkBye9HilqPP1%2FirXAHS3V%2FEEIF%2FtsH4QzkdpjCY0PIMnrap%2BnooT73tGEcLKm7Ap8XJIw7Lw18kh3ubsSz%2FrLllsi9eAfo69%2FwLKuu0%2B1nnRc9XV8Gq7GUa%2F8Tavt6Q8CjycrCZJRTPfSrw1gA3kXEuCq2kYi8hcnRRBMFTOkURYlot5OjwxLT8OBvHb84KBZxDr826tf498gMUw40NDuCP3QaH&X-Amz-Signature=043b00c9f189e86a9ac1dde1ea90704586dca9569cf41874c5a720c39c7ce5e5&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663WCP65Z5%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T102547Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGIaCXVzLXdlc3QtMiJHMEUCIQDG5WNP6kP2gUy63aQ3ob3d1S9HaPvW5e%2FYflvgtoIopgIgCt9A7u8U7rrBqQ5IGsPSJRmZD2fnEDIUYhpXKSJ1kJMqiAQIiv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCB1VRE9wwyx1vndbCrcA4FAeMZIaxh3liu06qlc8%2BBa6V8KdE8Q9fVz%2FpUpU3b9XWrJcMsgBPi6IhVB9zlLzQrOsPIDg7kkyZ2epaxiJJ5hRu%2FosP%2FNn4qp%2BWfHldZ5GT8%2BHkMtgAJrtymWqm8Dmad%2F0xG1%2BdsrMuIRhumebnvV875NDrfc6YE3dtBVHYNjCYr7EqswdbJqa%2B89wz%2BZrfttVbce3U5Jk03ILXmaB6sWdSvCyx%2F6BdMf0AG9nov%2FSqH4E%2FXZbwUdXo%2F2D9%2FCbyuR0m02iXjKcWLuXj5gO72XwNxem2pkDdAVto0kVNBI06rdUVY1MBIBSeVLULrU611rjyxRe44pK5LZjpLvw1tTSy1f%2F3%2BCVRkzTz6v6csGcRz7TsACo2EjB3Hs%2FPqeehhvWXBsw7%2FKkqCVOSuN6u8m0jnyfyRgudLbX8uabjM0SKvFKSsg0OPiy4Crb5MGRPMKnwNVpVdGMouI64IXKAR7ZDHU8On43%2BLJFBIaIP0fiEMlLneAK4nCK1hBcQdWAi1V1YNd9ZU737vth4NbqCgEmE%2BjNXJctMGIfR4Ns0Jrl4i%2Fctdsf%2FNdhVE%2Bm%2Bqp8hxNKfi1SRN1UrczZW8fZNF2qQdhwk09wtZv%2F3LmVUCskoTy7q8OMzjVlKLiMNui0b0GOqUBtkBye9HilqPP1%2FirXAHS3V%2FEEIF%2FtsH4QzkdpjCY0PIMnrap%2BnooT73tGEcLKm7Ap8XJIw7Lw18kh3ubsSz%2FrLllsi9eAfo69%2FwLKuu0%2B1nnRc9XV8Gq7GUa%2F8Tavt6Q8CjycrCZJRTPfSrw1gA3kXEuCq2kYi8hcnRRBMFTOkURYlot5OjwxLT8OBvHb84KBZxDr826tf498gMUw40NDuCP3QaH&X-Amz-Signature=0efa9ffefd8fc32de73604e027a1d4e89a516219e7f9f096a7a9111eef30b5e0&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667BJZEZZA%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T102548Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGIaCXVzLXdlc3QtMiJIMEYCIQDeTOnW64y96pk398Zs2d61Uc7RBpZDFEmN1mv9aB%2BVtQIhAMmwVG0LlR5r6vZGJ%2FW5OynRmxHi8xv0qy0OFwtqFp4VKogECIr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyUgSipFAtWxgkqHBcq3AMcQT1pSMS9TJXndBgDxXFPJ7zjiF0sUN%2BC6qAs1vg%2BpLU%2BkN4dFah7bM%2BnQeNLayLlQ3wUv2vMyninJBwmFe2DfOlwip7RaFq%2FlOuea92nF3KtW7UgwWgKKqDJjFarJM2xumldeZPgaPWt5Vnwxu4px3rAkCEU8Jv%2B0pPjFL8sN%2BJ27fNQ6Blr%2BRH0o%2BG2YC1auVjd%2B8D9Xdq%2FZhH%2FTv2gLXvfyHbkSydu1o59sVi3uWVzeVYsm53knQ0HZwo169oUg5kv5%2B1znktHpmQgLCJmnp8dR6SOQ3Q9vm7U5OS%2BxJQEQnJVUR19%2FpDil7RodI9XKOkwgWXrIA4RV4uJIj5IFd2mCS6wybjNxKjcuy0926M%2Bj5X0y5tBPozmEISfZr0aEkIpTyb0zFg21hiSpRGbe8l8D8uD0KL0yFhOy7O0RGW2xAaBUx%2FOxzUfTvoHcP7eXgFP5DTDF9AVtz5UfSr5kxGMVs90oXHJSjaPoKw%2F0Ou9HM0QUi24fleQas9xHrKjl57xN%2FZ6OmhZrQmQwOfV9TnWvCG68jcy3gPko0MUyf8GXmwWl43tfw60tYPs%2B8Dmew6y7MZHfJko4P3Yk5GQbp1x1sU08rkzz5lMuMgID8L37hE3Niafbua3aTCaotG9BjqkAU6QiWq7aQgPc3%2FC1F2nptUbMokkylw6g0%2FjuTnfadg9wEoUDgBhV85DL4an3jsIS6BNUtarXF3nGDaVt1HeGQjFMLymXDWhw%2F6nSlEmBJwPheZWk2lB3%2BZbeAyhsk675HboIgIwifkheffZ%2BVZsqzNA7q%2Bdc%2BfJNnZlxtl7qfeFcDcTJlrD20SXmJFJ7mUFg3warF24WPnBNox6xIT33pNnSyji&X-Amz-Signature=6cfa012af812300b502c984a55e7b995e4e0de90ccd00e298a393919bacf7a15&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VQIKXMD2%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T102552Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGIaCXVzLXdlc3QtMiJHMEUCIEmzSEOnZyRMEDmGUtTSwN3dB%2F1aNctZDT%2FyZSUTaZBmAiEAhOOeEhypNQCe4%2BtmwE4J0e%2FwlYNKteyVH1W5D2Kr8uoqiAQIiv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDB28g9cUkRVvkeoJ1yrcAx5QRnY0HSpKUjHjz%2FsLO8jy1Skns2Ab4saTdxf8eWLi6nME7wM8B3sbiOtwywkVPtIeG4uTVDuOVkNpVgMBUHQSCaVvFsfUuBlJxQPvCe%2F%2FNp0R1F07ycgxyniAAohjAzEUqabymeK8m0tPhB0tg40Qj7x9C5VdXB4qLhc8zzyQS%2Flf55fenoEhej2sScC9PqHyK5SchFSSWtA4G4hJklkTc7Cu9YjilvB4fqvyrdURyu74oFtXGse7LAM6NGaLgvQusIwdijbjBdD8zfG%2BYq9flUEskSEhgCPQKVqyOhr1EXdhtrRFiZJKMWTF%2BKyQizo7IuJJQ0UyRawTiIEOPyCZV1zD3LRFcSHpUI5T1444Njh7D4dUVQf8H8RTuPAUSWd2Fleu16DXj5JP2GABb7JvvEPS%2B2WoBpOY62%2Fz0lYW64u9MOiANpaDkmqJHNQBSVN0htZgi%2B0peuXqI2ElO%2Bou3HoiQuf1zvocjUIM3TmwgQV%2BoH4Mq6RLDNak2E79N91j%2FSVSmLyY9WHD8hemLHHaPDvExX0Gosr%2BbO1AsvB9ESbUGLLYx4OeG0SqdYJjWD9UdtG6QZSIQTgokox4o9elhpm8LlnDWI6nsRh07Omsjh3sztDp4v2mg7fKMJui0b0GOqUBaweW4tEk3IKbQg4RCWkPIF8h3Sbm%2BCs%2BaxDHnF3SkU2b3STXj11Ia1LMC2aA1dq77%2BKnIEdRYewKHvL9liy5pBXgGBLdoGZolcaSk4MtsG%2BnV9EQ8pSZxB4uHkGygcrmy5To%2Ft9%2BpmQ0rS%2Bh7ALXK5Hbt%2BwgJhCuVoCksuHCXm8hct1LTvxa%2FGNHfIRbGSKclDezX0oNxSwyEFSFz5K8vL%2BsIR2g&X-Amz-Signature=5ba90b657b9b020fbe3ec6e15f48e1cabbfc2cb04ef9d94e1927f7cc648c88ce&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663WCP65Z5%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T102547Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGIaCXVzLXdlc3QtMiJHMEUCIQDG5WNP6kP2gUy63aQ3ob3d1S9HaPvW5e%2FYflvgtoIopgIgCt9A7u8U7rrBqQ5IGsPSJRmZD2fnEDIUYhpXKSJ1kJMqiAQIiv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCB1VRE9wwyx1vndbCrcA4FAeMZIaxh3liu06qlc8%2BBa6V8KdE8Q9fVz%2FpUpU3b9XWrJcMsgBPi6IhVB9zlLzQrOsPIDg7kkyZ2epaxiJJ5hRu%2FosP%2FNn4qp%2BWfHldZ5GT8%2BHkMtgAJrtymWqm8Dmad%2F0xG1%2BdsrMuIRhumebnvV875NDrfc6YE3dtBVHYNjCYr7EqswdbJqa%2B89wz%2BZrfttVbce3U5Jk03ILXmaB6sWdSvCyx%2F6BdMf0AG9nov%2FSqH4E%2FXZbwUdXo%2F2D9%2FCbyuR0m02iXjKcWLuXj5gO72XwNxem2pkDdAVto0kVNBI06rdUVY1MBIBSeVLULrU611rjyxRe44pK5LZjpLvw1tTSy1f%2F3%2BCVRkzTz6v6csGcRz7TsACo2EjB3Hs%2FPqeehhvWXBsw7%2FKkqCVOSuN6u8m0jnyfyRgudLbX8uabjM0SKvFKSsg0OPiy4Crb5MGRPMKnwNVpVdGMouI64IXKAR7ZDHU8On43%2BLJFBIaIP0fiEMlLneAK4nCK1hBcQdWAi1V1YNd9ZU737vth4NbqCgEmE%2BjNXJctMGIfR4Ns0Jrl4i%2Fctdsf%2FNdhVE%2Bm%2Bqp8hxNKfi1SRN1UrczZW8fZNF2qQdhwk09wtZv%2F3LmVUCskoTy7q8OMzjVlKLiMNui0b0GOqUBtkBye9HilqPP1%2FirXAHS3V%2FEEIF%2FtsH4QzkdpjCY0PIMnrap%2BnooT73tGEcLKm7Ap8XJIw7Lw18kh3ubsSz%2FrLllsi9eAfo69%2FwLKuu0%2B1nnRc9XV8Gq7GUa%2F8Tavt6Q8CjycrCZJRTPfSrw1gA3kXEuCq2kYi8hcnRRBMFTOkURYlot5OjwxLT8OBvHb84KBZxDr826tf498gMUw40NDuCP3QaH&X-Amz-Signature=f791d8574a02a27da71391f71816aedd7ad7ac3dc9caaf74a65e659503c04012&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663WCP65Z5%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T102547Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGIaCXVzLXdlc3QtMiJHMEUCIQDG5WNP6kP2gUy63aQ3ob3d1S9HaPvW5e%2FYflvgtoIopgIgCt9A7u8U7rrBqQ5IGsPSJRmZD2fnEDIUYhpXKSJ1kJMqiAQIiv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCB1VRE9wwyx1vndbCrcA4FAeMZIaxh3liu06qlc8%2BBa6V8KdE8Q9fVz%2FpUpU3b9XWrJcMsgBPi6IhVB9zlLzQrOsPIDg7kkyZ2epaxiJJ5hRu%2FosP%2FNn4qp%2BWfHldZ5GT8%2BHkMtgAJrtymWqm8Dmad%2F0xG1%2BdsrMuIRhumebnvV875NDrfc6YE3dtBVHYNjCYr7EqswdbJqa%2B89wz%2BZrfttVbce3U5Jk03ILXmaB6sWdSvCyx%2F6BdMf0AG9nov%2FSqH4E%2FXZbwUdXo%2F2D9%2FCbyuR0m02iXjKcWLuXj5gO72XwNxem2pkDdAVto0kVNBI06rdUVY1MBIBSeVLULrU611rjyxRe44pK5LZjpLvw1tTSy1f%2F3%2BCVRkzTz6v6csGcRz7TsACo2EjB3Hs%2FPqeehhvWXBsw7%2FKkqCVOSuN6u8m0jnyfyRgudLbX8uabjM0SKvFKSsg0OPiy4Crb5MGRPMKnwNVpVdGMouI64IXKAR7ZDHU8On43%2BLJFBIaIP0fiEMlLneAK4nCK1hBcQdWAi1V1YNd9ZU737vth4NbqCgEmE%2BjNXJctMGIfR4Ns0Jrl4i%2Fctdsf%2FNdhVE%2Bm%2Bqp8hxNKfi1SRN1UrczZW8fZNF2qQdhwk09wtZv%2F3LmVUCskoTy7q8OMzjVlKLiMNui0b0GOqUBtkBye9HilqPP1%2FirXAHS3V%2FEEIF%2FtsH4QzkdpjCY0PIMnrap%2BnooT73tGEcLKm7Ap8XJIw7Lw18kh3ubsSz%2FrLllsi9eAfo69%2FwLKuu0%2B1nnRc9XV8Gq7GUa%2F8Tavt6Q8CjycrCZJRTPfSrw1gA3kXEuCq2kYi8hcnRRBMFTOkURYlot5OjwxLT8OBvHb84KBZxDr826tf498gMUw40NDuCP3QaH&X-Amz-Signature=a5e6538faf4489606c577bfb52c19e25007fd8f79e009be05da335acb90cf61a&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663WCP65Z5%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T102547Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGIaCXVzLXdlc3QtMiJHMEUCIQDG5WNP6kP2gUy63aQ3ob3d1S9HaPvW5e%2FYflvgtoIopgIgCt9A7u8U7rrBqQ5IGsPSJRmZD2fnEDIUYhpXKSJ1kJMqiAQIiv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCB1VRE9wwyx1vndbCrcA4FAeMZIaxh3liu06qlc8%2BBa6V8KdE8Q9fVz%2FpUpU3b9XWrJcMsgBPi6IhVB9zlLzQrOsPIDg7kkyZ2epaxiJJ5hRu%2FosP%2FNn4qp%2BWfHldZ5GT8%2BHkMtgAJrtymWqm8Dmad%2F0xG1%2BdsrMuIRhumebnvV875NDrfc6YE3dtBVHYNjCYr7EqswdbJqa%2B89wz%2BZrfttVbce3U5Jk03ILXmaB6sWdSvCyx%2F6BdMf0AG9nov%2FSqH4E%2FXZbwUdXo%2F2D9%2FCbyuR0m02iXjKcWLuXj5gO72XwNxem2pkDdAVto0kVNBI06rdUVY1MBIBSeVLULrU611rjyxRe44pK5LZjpLvw1tTSy1f%2F3%2BCVRkzTz6v6csGcRz7TsACo2EjB3Hs%2FPqeehhvWXBsw7%2FKkqCVOSuN6u8m0jnyfyRgudLbX8uabjM0SKvFKSsg0OPiy4Crb5MGRPMKnwNVpVdGMouI64IXKAR7ZDHU8On43%2BLJFBIaIP0fiEMlLneAK4nCK1hBcQdWAi1V1YNd9ZU737vth4NbqCgEmE%2BjNXJctMGIfR4Ns0Jrl4i%2Fctdsf%2FNdhVE%2Bm%2Bqp8hxNKfi1SRN1UrczZW8fZNF2qQdhwk09wtZv%2F3LmVUCskoTy7q8OMzjVlKLiMNui0b0GOqUBtkBye9HilqPP1%2FirXAHS3V%2FEEIF%2FtsH4QzkdpjCY0PIMnrap%2BnooT73tGEcLKm7Ap8XJIw7Lw18kh3ubsSz%2FrLllsi9eAfo69%2FwLKuu0%2B1nnRc9XV8Gq7GUa%2F8Tavt6Q8CjycrCZJRTPfSrw1gA3kXEuCq2kYi8hcnRRBMFTOkURYlot5OjwxLT8OBvHb84KBZxDr826tf498gMUw40NDuCP3QaH&X-Amz-Signature=fa67ddde07882d8681d5081304ab2fc1269fafbaff9695514da27a9a0bce90ba&X-Amz-SignedHeaders=host&x-id=GetObject)


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

