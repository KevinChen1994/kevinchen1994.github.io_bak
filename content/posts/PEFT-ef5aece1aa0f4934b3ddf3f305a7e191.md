---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4664BAESGBN%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250221T222302Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjELb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIA0WJ0im75nbqvAzcwi\
  S0uB%2Frjcr9e2NvU5bp3CAVzbGAiAgnj5ZPzjM6UZJ9grXL9EThpQlpB8Gikq0SK8ypVdABCqIBA\
  jf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMksdGpvYuj%2BLytdMZK\
  twD3RtXTgCGtJvQSRHlEzTqByrGd0Rlo88n3HzA6ra8cE8UJGQbYMHFrRpLYkVzwfavT66axmHKYq\
  VPg7bHEo26sTe6iAogSQuUww5BDIn6ul7Iv9KmhTTcgoC%2BoRN7ua9hPtUeLwKnL8Z6Qpw5L9zv1\
  miXxLZIDNJ8uOQU9S3Lmk0ZC8ECXM7CHUXv7TiWfEKVVq9Eb0qERMmoREO5sdZxxRVI%2B%2FTb7m\
  GsBBAtZbVwlEzjjeTfo0yt%2FTEfRci498JDNvnIHm7Xw6ik7gpWSD3wzSSynRSP5S4J91fDyVntX\
  x4r5i8IrRFoPpSz6l0rK49DLtFvdM%2FfQM1HcFCYopxt1F3tiaV1aQy3fFEUf2Z1aaNQHXAICsIG\
  sQbuwjvnuW7bgeDmdKyXa0kSRZ0TWfql%2FzUEGoRm9xDqD2e0kS1zRxfqC2iU9iKw9lCiT3pe1RJ\
  GCuQ%2FZRbc8tuRvNN7K0GRPI2%2FRUbQxuMlF%2BmCpyBo6Fq6z6gvnYvA3dJhUG0s6JG95dqAL4\
  OnViuULTYa1ZX3TUEq4GNaaTF%2BCPc%2BiQOjsD0DYnfe%2F7UDuvcaniFuJcTg379av5IQlv9Fz\
  juj6e8HdIo3rtgv7BUiY%2FYxbCZqUZ4bhbLIDOwm5Sy%2BhJYw5%2FXjvQY6pgHyDxF6FX10fpy0\
  xLioIsYvqFbmihlq9MAMPpRkA%2B6J9uJwDs2vzfCWY3E2Oph9RhCO8HB9B0ibDZ0ZJSoWuaNBzmB\
  YaVP93Xe05HqE8LtgFMOPUaZj0e3tuBofeYGDBMIvCWFVJpkM46cu70V%2BqQhGg4aCltku95omvt\
  3e4XYlFi4ZdwnSuR%2FoM7WfJPDLVBsw9deLGEOnlM1q25BShS0rUtvRNuz%2F&X-Amz-Signatur\
  e=7b47a71448030f52435667c2bb85344ba7c493453e37b44f32ee343031cf7b4c&X-Amz-Sign\
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
        redential=ASIAZI2LB466VT2PNNPW%2F20250221%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250221T222128Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjELb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQ\
        CIBUMbvAhdNtCze86%2BnU58HP7yJ5usWiyCSVWI4%2BVeJIhAiBc0gUzh5ssfO4MwHPnkg\
        x4xYZPXKY%2BpRKm1UPO8o9R9CqIBAjf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDY\
        zNzQyMzE4MzgwNSIMMIt%2FmCY2cwyHtLtqKtwDbRKO%2FJY6E%2FgFvG50HJ1x8uwXsSWE\
        OjT2yiNJp6L7QskeBjLggXbSDvSEzZ0VLiQWqaDicQO1wsKQ9O8vA5j9GFTbvX6CHnO%2BY\
        NOW4AeP%2FHDmCXusmBJD0XZTwoXd7De9jLYPb9ICWPHm29vL%2FimFLmHwx2i9tE8Y4cyz\
        0C46S4XzUmp6%2FJxKnC2PB9P3cE1KgmlU6A3BU6Q%2BS0PkgIDsK%2FnFsmGtZV%2FtSxz\
        Y1a0m2Ukw31rl4kafJhSPrnq7CS6tN8Fq5j3LziI26ZXawYQzulEoAfxeS83Po7MQDhYnNI\
        DOqdt1AXgBq0sCaYGovQeKwudByjScGzYIx6MmOCuLSpoeyd1HHHAsN%2FT6K%2FX2MWWrP\
        79321NunQef7OUYkis7q1ir4U%2BIpqhgnV3TWD1HY7ODwWc3WuMkoeR1duNQLKukM7RRFf\
        cBLxb0BTrDPhSHFlG6%2BibhLM6F7QoGjJFYKCwIMzFrkBK42xg%2Bl%2F6%2Fa7rAaOCjp\
        sbVUVJ6GZJFpTnqzA2HUva6YWQnsLG1wbzF3z6kZND8PrTb%2FBBBykmv%2F8xal8vsVy6M\
        TPl6UPJ8Vyw9u5OZ8GA8zskrOZiKBxz8t0VlxqHZzVO0V1%2B58EGmyplv95CprHexQZOEG\
        EIw0vXjvQY6pgH79zh6qHjN78WK%2BjU6zdywJPIw1RDJlD3bNxaD8Py7Z2uSzka9YsryqA\
        RfsITaRRLgmXQYESxmYaRPfjY4Tb4stWI74YRcV2ZMBPLXgNCbvOZz68bowMnRoGaN0Y5N0\
        N1BtU96Ny4o6tuPcLAwfMcomntNxk%2BL4QUMgpELhcRh5VpZ3SUlzN3wnou4VfIJgqPRee\
        njhQJTHDypgc1GCNsy%2BkLQ1RU7&X-Amz-Signature=3ebe0625711d9abe85f4914a63\
        69fad5a0da32b2f3d5fbee99ae17f316ede82b&X-Amz-SignedHeaders=host&x-id=Ge\
        tObject"
      expiry_time: "2025-02-21T23:21:28.919Z"
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
UPDATE_TIME: "2025-02-21T22:23:07.867Z"
EXPIRY_TIME: "2025-02-21T23:22:59.959Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VX63FHD7%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T222300Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDd2QdbGEzjUpM3hwigOrQ9qqb%2FDFof5KkoZtqR%2F3FGEgIhANVFkO2jk%2BigD82bkXuC2OhaGetwNCXx1213eWb5aDqFKogECN%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxofSEfE5T15VMja3Mq3APEJoWTnzvKZXJqY%2FOKsniB4%2Bklp16Vcn5seb%2Br5SY9RUqEFMQcy7a63Z2qu0YDJDviJNgTe2XFhZCeM4DPznWDYbTF2qIQDEaQl7DnaDcLMFiwGW3Ccirm%2FEqGLVQJi4ce3lNeicPW0pI4189R8Y3b7LaZ7qKTlf0Oxjg00h9sfVHHHL7vQ0kbKBoEF4N9SRTqv3RzLdODF76h9fUS15irAzdOwAM%2FehSdP9aRysrRnH0WZaJx%2Fp4ocbM3oC0LdfT6NLaSeIh8XQ1d0CsVzgrM0ZlLZM%2BImJ%2Ftm9s4Xi7hfWoRkdsDY4%2FQ7ZxU6ZU0fl%2F%2FQvVWmMzOvzwoop6%2FTFam5%2FxUEvUWkIrt3tHOkpxJi69Gy4IML7HXHHPsWGX3Ufv3Nxd7zfB8YfGZk%2BAgVgokk8XGkwh%2FxDx9s7xfwRxxk7Wn6SjHiZbhQEVT8KUV7uh5bGWy2JpiAeK%2FWF0vwRjZdvS%2F9U99kWaFGF9wm%2Fx%2FkL2zGVefHHUkmCjUXfr1mJ91GqM7wOjRFAJskq1OKHjr5Y5QpEuMCPyA6loafMQMa2OhYMQ2mj0kdJZsiXNM%2F4j1ofDFmbPQ%2BurX53iZDj43%2BcCxM9l%2B6z7rV1CKtPkczgpv5utP6fV1WY%2BCxzDM9uO9BjqkAYcoQXrVkByNWNEfZmPEKJqlwKalvz4J1O8InprK9OqBZJRZlwWURDx63Dbup1KyjCph68rlSH1dxxAB7N7m1%2BHoZsSmmshzNbo512om7ZBF3sNu7YgjASsbrdDFyj4hQuSIC4N5EUwdeym1FfqkKYV0GaCs6rqlerCfkGERBydVHaZ%2Fft0ZnTIPpzPAlv%2B55bmIiZvHVl8WA6hMLx%2BzSH4IDGTq&X-Amz-Signature=b41f0edb0303d3186770603e32b6d409d7f1b693b117c21a3735d1ab3422089a&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VX63FHD7%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T222300Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDd2QdbGEzjUpM3hwigOrQ9qqb%2FDFof5KkoZtqR%2F3FGEgIhANVFkO2jk%2BigD82bkXuC2OhaGetwNCXx1213eWb5aDqFKogECN%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxofSEfE5T15VMja3Mq3APEJoWTnzvKZXJqY%2FOKsniB4%2Bklp16Vcn5seb%2Br5SY9RUqEFMQcy7a63Z2qu0YDJDviJNgTe2XFhZCeM4DPznWDYbTF2qIQDEaQl7DnaDcLMFiwGW3Ccirm%2FEqGLVQJi4ce3lNeicPW0pI4189R8Y3b7LaZ7qKTlf0Oxjg00h9sfVHHHL7vQ0kbKBoEF4N9SRTqv3RzLdODF76h9fUS15irAzdOwAM%2FehSdP9aRysrRnH0WZaJx%2Fp4ocbM3oC0LdfT6NLaSeIh8XQ1d0CsVzgrM0ZlLZM%2BImJ%2Ftm9s4Xi7hfWoRkdsDY4%2FQ7ZxU6ZU0fl%2F%2FQvVWmMzOvzwoop6%2FTFam5%2FxUEvUWkIrt3tHOkpxJi69Gy4IML7HXHHPsWGX3Ufv3Nxd7zfB8YfGZk%2BAgVgokk8XGkwh%2FxDx9s7xfwRxxk7Wn6SjHiZbhQEVT8KUV7uh5bGWy2JpiAeK%2FWF0vwRjZdvS%2F9U99kWaFGF9wm%2Fx%2FkL2zGVefHHUkmCjUXfr1mJ91GqM7wOjRFAJskq1OKHjr5Y5QpEuMCPyA6loafMQMa2OhYMQ2mj0kdJZsiXNM%2F4j1ofDFmbPQ%2BurX53iZDj43%2BcCxM9l%2B6z7rV1CKtPkczgpv5utP6fV1WY%2BCxzDM9uO9BjqkAYcoQXrVkByNWNEfZmPEKJqlwKalvz4J1O8InprK9OqBZJRZlwWURDx63Dbup1KyjCph68rlSH1dxxAB7N7m1%2BHoZsSmmshzNbo512om7ZBF3sNu7YgjASsbrdDFyj4hQuSIC4N5EUwdeym1FfqkKYV0GaCs6rqlerCfkGERBydVHaZ%2Fft0ZnTIPpzPAlv%2B55bmIiZvHVl8WA6hMLx%2BzSH4IDGTq&X-Amz-Signature=5b7aacb375e98c0d808cea676b925f1dd6012fa913d49bd3187d6a3a54ffd3b9&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VX63FHD7%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T222300Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDd2QdbGEzjUpM3hwigOrQ9qqb%2FDFof5KkoZtqR%2F3FGEgIhANVFkO2jk%2BigD82bkXuC2OhaGetwNCXx1213eWb5aDqFKogECN%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxofSEfE5T15VMja3Mq3APEJoWTnzvKZXJqY%2FOKsniB4%2Bklp16Vcn5seb%2Br5SY9RUqEFMQcy7a63Z2qu0YDJDviJNgTe2XFhZCeM4DPznWDYbTF2qIQDEaQl7DnaDcLMFiwGW3Ccirm%2FEqGLVQJi4ce3lNeicPW0pI4189R8Y3b7LaZ7qKTlf0Oxjg00h9sfVHHHL7vQ0kbKBoEF4N9SRTqv3RzLdODF76h9fUS15irAzdOwAM%2FehSdP9aRysrRnH0WZaJx%2Fp4ocbM3oC0LdfT6NLaSeIh8XQ1d0CsVzgrM0ZlLZM%2BImJ%2Ftm9s4Xi7hfWoRkdsDY4%2FQ7ZxU6ZU0fl%2F%2FQvVWmMzOvzwoop6%2FTFam5%2FxUEvUWkIrt3tHOkpxJi69Gy4IML7HXHHPsWGX3Ufv3Nxd7zfB8YfGZk%2BAgVgokk8XGkwh%2FxDx9s7xfwRxxk7Wn6SjHiZbhQEVT8KUV7uh5bGWy2JpiAeK%2FWF0vwRjZdvS%2F9U99kWaFGF9wm%2Fx%2FkL2zGVefHHUkmCjUXfr1mJ91GqM7wOjRFAJskq1OKHjr5Y5QpEuMCPyA6loafMQMa2OhYMQ2mj0kdJZsiXNM%2F4j1ofDFmbPQ%2BurX53iZDj43%2BcCxM9l%2B6z7rV1CKtPkczgpv5utP6fV1WY%2BCxzDM9uO9BjqkAYcoQXrVkByNWNEfZmPEKJqlwKalvz4J1O8InprK9OqBZJRZlwWURDx63Dbup1KyjCph68rlSH1dxxAB7N7m1%2BHoZsSmmshzNbo512om7ZBF3sNu7YgjASsbrdDFyj4hQuSIC4N5EUwdeym1FfqkKYV0GaCs6rqlerCfkGERBydVHaZ%2Fft0ZnTIPpzPAlv%2B55bmIiZvHVl8WA6hMLx%2BzSH4IDGTq&X-Amz-Signature=c082b1d6c6f5fc058b6b94e8e873f66690d3205340c7a3823411e1f9f703b816&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VX63FHD7%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T222300Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDd2QdbGEzjUpM3hwigOrQ9qqb%2FDFof5KkoZtqR%2F3FGEgIhANVFkO2jk%2BigD82bkXuC2OhaGetwNCXx1213eWb5aDqFKogECN%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxofSEfE5T15VMja3Mq3APEJoWTnzvKZXJqY%2FOKsniB4%2Bklp16Vcn5seb%2Br5SY9RUqEFMQcy7a63Z2qu0YDJDviJNgTe2XFhZCeM4DPznWDYbTF2qIQDEaQl7DnaDcLMFiwGW3Ccirm%2FEqGLVQJi4ce3lNeicPW0pI4189R8Y3b7LaZ7qKTlf0Oxjg00h9sfVHHHL7vQ0kbKBoEF4N9SRTqv3RzLdODF76h9fUS15irAzdOwAM%2FehSdP9aRysrRnH0WZaJx%2Fp4ocbM3oC0LdfT6NLaSeIh8XQ1d0CsVzgrM0ZlLZM%2BImJ%2Ftm9s4Xi7hfWoRkdsDY4%2FQ7ZxU6ZU0fl%2F%2FQvVWmMzOvzwoop6%2FTFam5%2FxUEvUWkIrt3tHOkpxJi69Gy4IML7HXHHPsWGX3Ufv3Nxd7zfB8YfGZk%2BAgVgokk8XGkwh%2FxDx9s7xfwRxxk7Wn6SjHiZbhQEVT8KUV7uh5bGWy2JpiAeK%2FWF0vwRjZdvS%2F9U99kWaFGF9wm%2Fx%2FkL2zGVefHHUkmCjUXfr1mJ91GqM7wOjRFAJskq1OKHjr5Y5QpEuMCPyA6loafMQMa2OhYMQ2mj0kdJZsiXNM%2F4j1ofDFmbPQ%2BurX53iZDj43%2BcCxM9l%2B6z7rV1CKtPkczgpv5utP6fV1WY%2BCxzDM9uO9BjqkAYcoQXrVkByNWNEfZmPEKJqlwKalvz4J1O8InprK9OqBZJRZlwWURDx63Dbup1KyjCph68rlSH1dxxAB7N7m1%2BHoZsSmmshzNbo512om7ZBF3sNu7YgjASsbrdDFyj4hQuSIC4N5EUwdeym1FfqkKYV0GaCs6rqlerCfkGERBydVHaZ%2Fft0ZnTIPpzPAlv%2B55bmIiZvHVl8WA6hMLx%2BzSH4IDGTq&X-Amz-Signature=55dc3721511aec82a3b0f9b57827a64bf1b2cec73bd94b22f21c3c4fafe44d27&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VX63FHD7%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T222300Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDd2QdbGEzjUpM3hwigOrQ9qqb%2FDFof5KkoZtqR%2F3FGEgIhANVFkO2jk%2BigD82bkXuC2OhaGetwNCXx1213eWb5aDqFKogECN%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxofSEfE5T15VMja3Mq3APEJoWTnzvKZXJqY%2FOKsniB4%2Bklp16Vcn5seb%2Br5SY9RUqEFMQcy7a63Z2qu0YDJDviJNgTe2XFhZCeM4DPznWDYbTF2qIQDEaQl7DnaDcLMFiwGW3Ccirm%2FEqGLVQJi4ce3lNeicPW0pI4189R8Y3b7LaZ7qKTlf0Oxjg00h9sfVHHHL7vQ0kbKBoEF4N9SRTqv3RzLdODF76h9fUS15irAzdOwAM%2FehSdP9aRysrRnH0WZaJx%2Fp4ocbM3oC0LdfT6NLaSeIh8XQ1d0CsVzgrM0ZlLZM%2BImJ%2Ftm9s4Xi7hfWoRkdsDY4%2FQ7ZxU6ZU0fl%2F%2FQvVWmMzOvzwoop6%2FTFam5%2FxUEvUWkIrt3tHOkpxJi69Gy4IML7HXHHPsWGX3Ufv3Nxd7zfB8YfGZk%2BAgVgokk8XGkwh%2FxDx9s7xfwRxxk7Wn6SjHiZbhQEVT8KUV7uh5bGWy2JpiAeK%2FWF0vwRjZdvS%2F9U99kWaFGF9wm%2Fx%2FkL2zGVefHHUkmCjUXfr1mJ91GqM7wOjRFAJskq1OKHjr5Y5QpEuMCPyA6loafMQMa2OhYMQ2mj0kdJZsiXNM%2F4j1ofDFmbPQ%2BurX53iZDj43%2BcCxM9l%2B6z7rV1CKtPkczgpv5utP6fV1WY%2BCxzDM9uO9BjqkAYcoQXrVkByNWNEfZmPEKJqlwKalvz4J1O8InprK9OqBZJRZlwWURDx63Dbup1KyjCph68rlSH1dxxAB7N7m1%2BHoZsSmmshzNbo512om7ZBF3sNu7YgjASsbrdDFyj4hQuSIC4N5EUwdeym1FfqkKYV0GaCs6rqlerCfkGERBydVHaZ%2Fft0ZnTIPpzPAlv%2B55bmIiZvHVl8WA6hMLx%2BzSH4IDGTq&X-Amz-Signature=2134810cb45929c11da74d653f2754faf418ec3da5eaf35e4d0c566a82d28a3a&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SPLW2LLX%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T222301Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCAodA6%2F%2BhqHq%2F7zK0QIsa9Q%2F3qkbPfnA93%2B4PWIDlPZQIgc8fPceUcwfar7Z5arVxDPCkOmaJli0tfblu3xIQyyu4qiAQI3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDI%2F8DQsNOGGjPZsv%2FSrcAwPQRYoCSofqRiT6rz1dLK5ulmRZVOzN84OOQlzlbwQzGy%2FJig6nqhYJ0HrXFiWfcl5H%2FwHxyEaNhvIhmAn7Ce1Hcl7cNG%2BpLQh92YUUpEXW4vdCqFHKKiK3bK3sbyynK%2FG3030X5Vd8KQj6VskAVlJjcPLvUzFODiU7NLlaL6cF9311YaFPDh7r5ol2Wrs0%2Fkfy%2BGiRQvkSgXHAavrjo5j0lZQ32fGDcoTQ432kx2JghzNZWqx6WVztGk1R3Vk8boayWT0%2F%2BFPBUHWBZYTEvQM9S2qz8OD0ukTB0cKYgBMuW%2BIKX9Cvd%2BZCNf4N3UwObs%2FAJEPs3ozAO2kx26Zybqy%2B69cRnZK0fSsC34%2B8J7N3ziYTFLaWvYKivh%2Fe%2FFa3R855VCbxco8Giik4mNCVr3dLIzy%2BXE0xTx%2B1yKpFMdFAbZJ2fxeVQvqKoiziYkNJlWedfW9tcdumx4T3IyRuFyyfShZ1lRQcC8%2B3%2Fukca1lV6sbQDRMOkyESppt3devfzqMJnoAmJysAJ0tAdNbUAPI%2B%2FROZBbtjKd83GztygWpy7awyBpLOROe4waDivmoDKgNysy80%2FcYlz5S5RSXZA%2FBqaacOtyIU%2FOs3CQOJfdnv5VX0nzcz4FDXYeYMMOz2470GOqUBYeZIHfsVqX5JAbRNlAyd%2BpTrfVp0YC6xj2TtiL5X4yTmKTQ%2BwGgK92e07CdBRnCsvO9ZZW%2Buno7INx0eBtBxvhEhIygYtA6SXsnHGfY5cVrdcvkn7MqFjoRgnWPTB1Ez%2BVJnsrQupt4OMn3Olq7nttZbzd1D9AmzDSRML1r93ozrUR3twgswk1YN%2FY3WwzEn17TrNEpatpX3wNJNbT1xPcmbuRaM&X-Amz-Signature=16f26f44baca4fa1eb2b238c9fc3317f4d1c13159b8c68e613be9726ed93a5b5&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664BP73A2I%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T222301Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIF8YBP1CPrrWIBS19CIWsBxv5xBuPAKR1wP0c5rf0BfSAiEA9RLO9ehxYewc7L9QwwkU4fLWx6Oi61LUmLi1TbyH0%2FAqiAQI3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDG0i2n0kwuCfZrwlCSrcA6A8uRK%2FW8ywKPX8HrFwvM1wWR7nWO1KexvSgiFZC9JY56jq4Dy%2FuyH%2By5hBu1sOtl%2F7o2Txr%2BbQVty23Ay2NoR%2FrfkNUa9yzhdvcv2KeyjcxK46RKX6xaNwQd2O1fIV0XYDTB5cWjaAIFdAV%2FA43QyXHUUDAUWLJR9%2BoQrRHlUa6OMzdQgavd70PIUeCjEM%2BFMvOoAes6MeUJIMhxkkbe5oNyxyHYUC9cCZKtn9Vb2Q1pD4C7e72Rwf7GQfHOiNlqn6fxREYn63h6gZVve39Vl%2BOc2rTR1BCYsAWoI2uS%2FQXMm449q4cGzuWwfPqobbemoBXtqm9AyetF4vbDIEqrm5ssLp0Q2rrbobaJL2ILE5cRYmn%2B%2B%2BnLmo5jsj3Dgv9Vq62OPVEBVXHsodnhY%2FAO5urMUl7FCj52QKYPQA1wKO4ZHr7g0eR6LWxvJqYJp7YYbU6WygPuGUNjSYk1l%2FTGAKRIJnNpBYZUhJn51LI%2FxUK8nTfRrP0IoUh0knetRKA2K5fX0QxiitHu1U%2BhE1vESGMfHNdc0Yny%2BY%2BsLjj74qhcTcQGamE22WBe9yNQSPmePnqZZfpHDSpr8zOvINUaQzB0EEwAj7So9ElOgh%2FWAj9LEAjIIZdCwezZrUMO31470GOqUB2o9vvQvs28sZD10KQdwZx2gb2FDLJHfnXZ1EmOndw4z82BygZAO7N4CsJZSuMCQoZBOhG4ZwrZeNHwvqzH0IkMe2TbsiKqUyZsnR8s%2BV7jRIBJeUlrUKMAzbbYDFHsyZyW65EzO5CgkRyN4JJ09mRu1sUDy5HUB%2FtTpdAyT42mGKIt6ZY8C%2FBLweACmyxLRP5AOmRB7X53h4dwbPvA4YQXqMi28W&X-Amz-Signature=e0df8550fab07b6517507ed81094388cbfcbae305f6d52887feefac01a870952&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VX63FHD7%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T222300Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDd2QdbGEzjUpM3hwigOrQ9qqb%2FDFof5KkoZtqR%2F3FGEgIhANVFkO2jk%2BigD82bkXuC2OhaGetwNCXx1213eWb5aDqFKogECN%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxofSEfE5T15VMja3Mq3APEJoWTnzvKZXJqY%2FOKsniB4%2Bklp16Vcn5seb%2Br5SY9RUqEFMQcy7a63Z2qu0YDJDviJNgTe2XFhZCeM4DPznWDYbTF2qIQDEaQl7DnaDcLMFiwGW3Ccirm%2FEqGLVQJi4ce3lNeicPW0pI4189R8Y3b7LaZ7qKTlf0Oxjg00h9sfVHHHL7vQ0kbKBoEF4N9SRTqv3RzLdODF76h9fUS15irAzdOwAM%2FehSdP9aRysrRnH0WZaJx%2Fp4ocbM3oC0LdfT6NLaSeIh8XQ1d0CsVzgrM0ZlLZM%2BImJ%2Ftm9s4Xi7hfWoRkdsDY4%2FQ7ZxU6ZU0fl%2F%2FQvVWmMzOvzwoop6%2FTFam5%2FxUEvUWkIrt3tHOkpxJi69Gy4IML7HXHHPsWGX3Ufv3Nxd7zfB8YfGZk%2BAgVgokk8XGkwh%2FxDx9s7xfwRxxk7Wn6SjHiZbhQEVT8KUV7uh5bGWy2JpiAeK%2FWF0vwRjZdvS%2F9U99kWaFGF9wm%2Fx%2FkL2zGVefHHUkmCjUXfr1mJ91GqM7wOjRFAJskq1OKHjr5Y5QpEuMCPyA6loafMQMa2OhYMQ2mj0kdJZsiXNM%2F4j1ofDFmbPQ%2BurX53iZDj43%2BcCxM9l%2B6z7rV1CKtPkczgpv5utP6fV1WY%2BCxzDM9uO9BjqkAYcoQXrVkByNWNEfZmPEKJqlwKalvz4J1O8InprK9OqBZJRZlwWURDx63Dbup1KyjCph68rlSH1dxxAB7N7m1%2BHoZsSmmshzNbo512om7ZBF3sNu7YgjASsbrdDFyj4hQuSIC4N5EUwdeym1FfqkKYV0GaCs6rqlerCfkGERBydVHaZ%2Fft0ZnTIPpzPAlv%2B55bmIiZvHVl8WA6hMLx%2BzSH4IDGTq&X-Amz-Signature=b37a45391ba5b317758228785805ffa8e066b0b729d93baacfffeacb73531f7a&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VX63FHD7%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T222300Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDd2QdbGEzjUpM3hwigOrQ9qqb%2FDFof5KkoZtqR%2F3FGEgIhANVFkO2jk%2BigD82bkXuC2OhaGetwNCXx1213eWb5aDqFKogECN%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxofSEfE5T15VMja3Mq3APEJoWTnzvKZXJqY%2FOKsniB4%2Bklp16Vcn5seb%2Br5SY9RUqEFMQcy7a63Z2qu0YDJDviJNgTe2XFhZCeM4DPznWDYbTF2qIQDEaQl7DnaDcLMFiwGW3Ccirm%2FEqGLVQJi4ce3lNeicPW0pI4189R8Y3b7LaZ7qKTlf0Oxjg00h9sfVHHHL7vQ0kbKBoEF4N9SRTqv3RzLdODF76h9fUS15irAzdOwAM%2FehSdP9aRysrRnH0WZaJx%2Fp4ocbM3oC0LdfT6NLaSeIh8XQ1d0CsVzgrM0ZlLZM%2BImJ%2Ftm9s4Xi7hfWoRkdsDY4%2FQ7ZxU6ZU0fl%2F%2FQvVWmMzOvzwoop6%2FTFam5%2FxUEvUWkIrt3tHOkpxJi69Gy4IML7HXHHPsWGX3Ufv3Nxd7zfB8YfGZk%2BAgVgokk8XGkwh%2FxDx9s7xfwRxxk7Wn6SjHiZbhQEVT8KUV7uh5bGWy2JpiAeK%2FWF0vwRjZdvS%2F9U99kWaFGF9wm%2Fx%2FkL2zGVefHHUkmCjUXfr1mJ91GqM7wOjRFAJskq1OKHjr5Y5QpEuMCPyA6loafMQMa2OhYMQ2mj0kdJZsiXNM%2F4j1ofDFmbPQ%2BurX53iZDj43%2BcCxM9l%2B6z7rV1CKtPkczgpv5utP6fV1WY%2BCxzDM9uO9BjqkAYcoQXrVkByNWNEfZmPEKJqlwKalvz4J1O8InprK9OqBZJRZlwWURDx63Dbup1KyjCph68rlSH1dxxAB7N7m1%2BHoZsSmmshzNbo512om7ZBF3sNu7YgjASsbrdDFyj4hQuSIC4N5EUwdeym1FfqkKYV0GaCs6rqlerCfkGERBydVHaZ%2Fft0ZnTIPpzPAlv%2B55bmIiZvHVl8WA6hMLx%2BzSH4IDGTq&X-Amz-Signature=dea913d70aff2b3d2613a7e26152e979093f0b35cd62039ee9e7d67a4130a8f4&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VX63FHD7%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T222300Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDd2QdbGEzjUpM3hwigOrQ9qqb%2FDFof5KkoZtqR%2F3FGEgIhANVFkO2jk%2BigD82bkXuC2OhaGetwNCXx1213eWb5aDqFKogECN%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxofSEfE5T15VMja3Mq3APEJoWTnzvKZXJqY%2FOKsniB4%2Bklp16Vcn5seb%2Br5SY9RUqEFMQcy7a63Z2qu0YDJDviJNgTe2XFhZCeM4DPznWDYbTF2qIQDEaQl7DnaDcLMFiwGW3Ccirm%2FEqGLVQJi4ce3lNeicPW0pI4189R8Y3b7LaZ7qKTlf0Oxjg00h9sfVHHHL7vQ0kbKBoEF4N9SRTqv3RzLdODF76h9fUS15irAzdOwAM%2FehSdP9aRysrRnH0WZaJx%2Fp4ocbM3oC0LdfT6NLaSeIh8XQ1d0CsVzgrM0ZlLZM%2BImJ%2Ftm9s4Xi7hfWoRkdsDY4%2FQ7ZxU6ZU0fl%2F%2FQvVWmMzOvzwoop6%2FTFam5%2FxUEvUWkIrt3tHOkpxJi69Gy4IML7HXHHPsWGX3Ufv3Nxd7zfB8YfGZk%2BAgVgokk8XGkwh%2FxDx9s7xfwRxxk7Wn6SjHiZbhQEVT8KUV7uh5bGWy2JpiAeK%2FWF0vwRjZdvS%2F9U99kWaFGF9wm%2Fx%2FkL2zGVefHHUkmCjUXfr1mJ91GqM7wOjRFAJskq1OKHjr5Y5QpEuMCPyA6loafMQMa2OhYMQ2mj0kdJZsiXNM%2F4j1ofDFmbPQ%2BurX53iZDj43%2BcCxM9l%2B6z7rV1CKtPkczgpv5utP6fV1WY%2BCxzDM9uO9BjqkAYcoQXrVkByNWNEfZmPEKJqlwKalvz4J1O8InprK9OqBZJRZlwWURDx63Dbup1KyjCph68rlSH1dxxAB7N7m1%2BHoZsSmmshzNbo512om7ZBF3sNu7YgjASsbrdDFyj4hQuSIC4N5EUwdeym1FfqkKYV0GaCs6rqlerCfkGERBydVHaZ%2Fft0ZnTIPpzPAlv%2B55bmIiZvHVl8WA6hMLx%2BzSH4IDGTq&X-Amz-Signature=7c4b3307a000d34e63a7b513570c7b1dddfb3aa72097b689406473f73e1bcb13&X-Amz-SignedHeaders=host&x-id=GetObject)


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

