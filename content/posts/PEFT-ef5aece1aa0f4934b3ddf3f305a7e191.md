---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466U2KA7BAI%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250210T202505Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEKz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDPQ9gqaxOx8ZSwU%2\
  BJR7TztPaD0Wo%2BmTqTHxOEjSov96AIhAKsjRc5q6JuC%2BuO6LRMcr7tb7JX8JRIPB%2BtMwCnY\
  JKXWKogECMX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwqaBQEO4v3R\
  Ti05zkq3AOhp38qdjWUGFtkd8BsX0AioXjm1UY1nSrAspxHDRMd2pwiQecFoVBxAcXsq4NJzDtva%\
  2FRqpzPa5Jzthfkyrd%2B7zG7S%2Fcev5rDog999JKXnfsksoMDZ9vi%2FrX7s1%2BbJMt4ZSyOVJ\
  RBmRsyOl4BhLBD2b7XS5hh0TNjaSHHjzho5ZUudUGUXof9TEBP9vBzKxO06a9MFldhIJEPSX5bhrd\
  hk3%2FeGynZjzipCJhlV3FcyL%2FXWwdiFQCf%2BkyfKYiJPzM4bJhfeHqTDQx80FfU2hKnpQw2Co\
  AkQV0TgCnOs3Be7sCWMPfXhhLRRR54V8brdCn%2FIFwYqEULa0d%2BWm1yVbD2dT%2BiQTKNu5ZIU\
  uDdEkTV29fqyfbU5Xtd7OHLgdlfsCn%2FQs48ZSLQbVkey2f1332gMBsHoPMHO21BekF333fU%2Fw\
  Cb8ns7NIC82meWQd4tvfj4FwfisLM3LuDM6uWOma8rSG7r2YWUgj1m9duNYohOVXqnRRu5YYh3HbY\
  CnGm0X4A74rBoJvS8uKrorUuzTDlECT3k7rugMIFFLtc6cGHnH5y2WHPjj%2Fm%2BCJBfk1jws%2F\
  JEEsUpHuLPOh7BaBTp2vl6upZHGtbasS91zc5n5%2B6DaWhYAXb02lmxIiSaozzCps6m9BjqkAX5h\
  GTjCP7QcDdgy45T2Kypulo%2Fh6rE5zmk2YSoMHtVuhJg27851emtLB52VAu4%2F%2BBRwY9O%2FO\
  nJ3hDj%2BohP0p%2FKYk1kUujodeR6waSCmq5biaflNuGwLxhagT61G%2BylaUT6L7cHs4qHTNAxx\
  ma3Lg071wUBMQqqn8fCkgynUXc3pJox0HPHi3%2FJc85%2FpAvwmxUwJeWdMa%2B2IkOL5iW0KKkq\
  Ew2Lq&X-Amz-Signature=4d6e56cc621acc3e721172344aef40516be2885fbe4f6d4be9a03cb\
  6e73c1025&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4667KWBJLR7%2F20250210%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250210T202347Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEKz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQ\
        CICm6hTAU8rhpsvWCm5ZIKaEUK03QkspENxJrctU604aOAiB2g%2Bjce02%2F8zJhF%2FPJ\
        EfO%2FzshbjXFghne%2BD7YFvIv%2BVSqIBAjF%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BE\
        AAaDDYzNzQyMzE4MzgwNSIMAYICwY7nkK97R5qqKtwDwwmHO6R6Ywq4wfnz6WI%2BlHu6Y2\
        wEbyiaF7F4As9HU%2BDj4JRDK4jEHzFN8JvkVjBUBLalMvBYfQWz0mFHM1EbQSIN6Tzzrpz\
        Wqcl9JlDa%2FrAq35XFNijrOvG5wK9gcWbrDWAx8Q0tIcBovhoV4XlwojzXRk3pDSo8s%2B\
        f3EJsHoGBif4D7f6vSmWJCM%2BP%2Fv%2F93Yw0BliXb5YUlGYo0Xx6hTaq1Pi9AfYyuACC\
        qouEHwjqN%2BS%2BAcwacWOTIyS2GRQHf%2FUhImkrmbcZg26GHsB0cIR8pSyp2rYuW0UhN\
        SZIZQ0mbjYnIkAZNry7fe%2Fm54qMy38dsqRY1hOf76OHlYoRF4XG06OGpaLUzbHoA68sis\
        poT59NbE0vcKGRnQRJ4IvfjLXPEI45T90zBupvEinSlxsCzWbqbJfqJhBvBlDBtilt7rdM8\
        0tySmAuMoMfnMw2u%2ByIzexhG3ZYkczOiLuSWmITqgTHsU8wof3VPe9T1J9P128wN8A83I\
        XWNGAsNu04pOucwr3z%2BDScar0N2hgU0E2WUEKRk%2B0LnRlNmNjvu3otx94%2BFDZRZ7G\
        bQ32M19Gg0qqQR0QUybLG4kXNjGLOMjUEszPH%2FVwN8eNWAywO06cfWjI7aK8Y9zrdj9mo\
        w67KpvQY6pgEmTHltgeDa0cLPnt%2Fvb%2B0m02DIpZCHDRuVsXVDYdopyJPxnfTiMdv53W\
        VJ30WdMBc6VAdldZNWptSoYvPndL0S2d0EGdyQpqddeNaporFtfPmwiSXiq3p7hPEo3JKCZ\
        y06bYNQxPkRl2B5Q2VsPgiNAwleJ%2FwyXpklegH%2BKFILhXPXq9XO%2FdwhgEJZ4jVVCi\
        RrwAkqcsqWYf6a5QZqRViQ5zdpXcyO&X-Amz-Signature=ba8c1e5445efbf8b71420200\
        f0e909ffc27e90e772e7999444ab5c5b6dd16cbd&X-Amz-SignedHeaders=host&x-id=\
        GetObject"
      expiry_time: "2025-02-10T21:23:47.851Z"
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
UPDATE_TIME: "2025-02-10T20:25:12.339Z"
EXPIRY_TIME: "2025-02-10T21:25:02.429Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466S5AC4P35%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T202502Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIGreN%2Bz6KuOKeOKPfTuKvGzT4YlIW6w37rnnBMOzR61LAiAHNZM8pBcdDi61bDGkHf7mbZOgFkl3CBSsmpk3wWNGISqIBAjF%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM4jA5q%2F18xs6dAgoyKtwDLnKP0dN0XqzhIO2QK1ODv3cwFLbujY1NDcE9tSAiNsqd9VzoqDMFLw9zVHlpc4FqHIJIkuI01a1a1rSP4j3Uh%2Bi0y4oDNW%2F6kn6H%2FpVxKN025chHwJ6c6js3HQz6ajiNmHcyKsxAFsVV1VPLf9eywl0lf%2F2g0l9waNSJhQf4WndSxFGgc1WuuSjkASfgPjHeVGlPAc0Vl05QppdXqMmjg4%2BQeeSfwaNja26VWpKxfJdBLTZdhjGadrH459VStmJQi%2Fl5jwA6x9HLwc%2Fm%2BnQxhXStZQPTWXFHCcXi7lyc48gHm7r2gBH%2FyDbj%2FEvaZtGjs2lie7f3sl1ZBsQp5gkFXM3XGoA87pYz1y1RXo0PpVCzm%2FWD8pjbMCP8ChrjpYlRKD%2F12JGv5V5t2Ta7JW%2BZHEq0vF5x9xFANhn%2Fx%2B4IHl4Ts0D4RHAiJ0A0clSF8kMMaGDvNStLx61ZPvl%2B9sA93VV8I%2FxBQXG9Dm0PXiGLgQiWGw9Gx1t%2FYwxdMQsc454RA%2BYDAAZL1RkubnA3oKik50%2Bw4R75s%2FVjlor7Bt1TZTnu1NW5CYH8RvSr%2B1D4V2nWYyDVLg8NdG0zcRdlth0rsRcKQsUbzGBVcMiiYfzS%2B3Mh000GjY%2BVMgy0Tusw9rKpvQY6pgFYRNAuAcWSmWH%2BN2U3T6e%2FyRk6LdUcXvvhtFaAFRN52K8YqzZKSmYhrBSj8CUaNc0KLPxAetk3EkzwP0fIzE5xE6%2BqFrU751jbf6YayQTsA%2FYeQ3Fp37dhb8oowcUAwLeviOm0l%2BWwuG2m1L9axqLll%2FCO7ZtYmh1ht5BnGgDxgf9bjbQuXNdhzxxV4NHiz4vk0Dq36jhlftokLTNY5dtpiLz5S2Ql&X-Amz-Signature=76d00d012e76c5813446098cfb0b17cb6a3ba748e469133cf07ea4af942562ad&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466S5AC4P35%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T202502Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIGreN%2Bz6KuOKeOKPfTuKvGzT4YlIW6w37rnnBMOzR61LAiAHNZM8pBcdDi61bDGkHf7mbZOgFkl3CBSsmpk3wWNGISqIBAjF%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM4jA5q%2F18xs6dAgoyKtwDLnKP0dN0XqzhIO2QK1ODv3cwFLbujY1NDcE9tSAiNsqd9VzoqDMFLw9zVHlpc4FqHIJIkuI01a1a1rSP4j3Uh%2Bi0y4oDNW%2F6kn6H%2FpVxKN025chHwJ6c6js3HQz6ajiNmHcyKsxAFsVV1VPLf9eywl0lf%2F2g0l9waNSJhQf4WndSxFGgc1WuuSjkASfgPjHeVGlPAc0Vl05QppdXqMmjg4%2BQeeSfwaNja26VWpKxfJdBLTZdhjGadrH459VStmJQi%2Fl5jwA6x9HLwc%2Fm%2BnQxhXStZQPTWXFHCcXi7lyc48gHm7r2gBH%2FyDbj%2FEvaZtGjs2lie7f3sl1ZBsQp5gkFXM3XGoA87pYz1y1RXo0PpVCzm%2FWD8pjbMCP8ChrjpYlRKD%2F12JGv5V5t2Ta7JW%2BZHEq0vF5x9xFANhn%2Fx%2B4IHl4Ts0D4RHAiJ0A0clSF8kMMaGDvNStLx61ZPvl%2B9sA93VV8I%2FxBQXG9Dm0PXiGLgQiWGw9Gx1t%2FYwxdMQsc454RA%2BYDAAZL1RkubnA3oKik50%2Bw4R75s%2FVjlor7Bt1TZTnu1NW5CYH8RvSr%2B1D4V2nWYyDVLg8NdG0zcRdlth0rsRcKQsUbzGBVcMiiYfzS%2B3Mh000GjY%2BVMgy0Tusw9rKpvQY6pgFYRNAuAcWSmWH%2BN2U3T6e%2FyRk6LdUcXvvhtFaAFRN52K8YqzZKSmYhrBSj8CUaNc0KLPxAetk3EkzwP0fIzE5xE6%2BqFrU751jbf6YayQTsA%2FYeQ3Fp37dhb8oowcUAwLeviOm0l%2BWwuG2m1L9axqLll%2FCO7ZtYmh1ht5BnGgDxgf9bjbQuXNdhzxxV4NHiz4vk0Dq36jhlftokLTNY5dtpiLz5S2Ql&X-Amz-Signature=942da58696b9f33db4e1bc6d5dc1fc56f70d438454cec1e47a4213710b542f4a&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466S5AC4P35%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T202502Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIGreN%2Bz6KuOKeOKPfTuKvGzT4YlIW6w37rnnBMOzR61LAiAHNZM8pBcdDi61bDGkHf7mbZOgFkl3CBSsmpk3wWNGISqIBAjF%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM4jA5q%2F18xs6dAgoyKtwDLnKP0dN0XqzhIO2QK1ODv3cwFLbujY1NDcE9tSAiNsqd9VzoqDMFLw9zVHlpc4FqHIJIkuI01a1a1rSP4j3Uh%2Bi0y4oDNW%2F6kn6H%2FpVxKN025chHwJ6c6js3HQz6ajiNmHcyKsxAFsVV1VPLf9eywl0lf%2F2g0l9waNSJhQf4WndSxFGgc1WuuSjkASfgPjHeVGlPAc0Vl05QppdXqMmjg4%2BQeeSfwaNja26VWpKxfJdBLTZdhjGadrH459VStmJQi%2Fl5jwA6x9HLwc%2Fm%2BnQxhXStZQPTWXFHCcXi7lyc48gHm7r2gBH%2FyDbj%2FEvaZtGjs2lie7f3sl1ZBsQp5gkFXM3XGoA87pYz1y1RXo0PpVCzm%2FWD8pjbMCP8ChrjpYlRKD%2F12JGv5V5t2Ta7JW%2BZHEq0vF5x9xFANhn%2Fx%2B4IHl4Ts0D4RHAiJ0A0clSF8kMMaGDvNStLx61ZPvl%2B9sA93VV8I%2FxBQXG9Dm0PXiGLgQiWGw9Gx1t%2FYwxdMQsc454RA%2BYDAAZL1RkubnA3oKik50%2Bw4R75s%2FVjlor7Bt1TZTnu1NW5CYH8RvSr%2B1D4V2nWYyDVLg8NdG0zcRdlth0rsRcKQsUbzGBVcMiiYfzS%2B3Mh000GjY%2BVMgy0Tusw9rKpvQY6pgFYRNAuAcWSmWH%2BN2U3T6e%2FyRk6LdUcXvvhtFaAFRN52K8YqzZKSmYhrBSj8CUaNc0KLPxAetk3EkzwP0fIzE5xE6%2BqFrU751jbf6YayQTsA%2FYeQ3Fp37dhb8oowcUAwLeviOm0l%2BWwuG2m1L9axqLll%2FCO7ZtYmh1ht5BnGgDxgf9bjbQuXNdhzxxV4NHiz4vk0Dq36jhlftokLTNY5dtpiLz5S2Ql&X-Amz-Signature=474e1d708e170cd74112d2b64590a3092ee378acc7f8f755a82d974dfa031267&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466S5AC4P35%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T202502Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIGreN%2Bz6KuOKeOKPfTuKvGzT4YlIW6w37rnnBMOzR61LAiAHNZM8pBcdDi61bDGkHf7mbZOgFkl3CBSsmpk3wWNGISqIBAjF%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM4jA5q%2F18xs6dAgoyKtwDLnKP0dN0XqzhIO2QK1ODv3cwFLbujY1NDcE9tSAiNsqd9VzoqDMFLw9zVHlpc4FqHIJIkuI01a1a1rSP4j3Uh%2Bi0y4oDNW%2F6kn6H%2FpVxKN025chHwJ6c6js3HQz6ajiNmHcyKsxAFsVV1VPLf9eywl0lf%2F2g0l9waNSJhQf4WndSxFGgc1WuuSjkASfgPjHeVGlPAc0Vl05QppdXqMmjg4%2BQeeSfwaNja26VWpKxfJdBLTZdhjGadrH459VStmJQi%2Fl5jwA6x9HLwc%2Fm%2BnQxhXStZQPTWXFHCcXi7lyc48gHm7r2gBH%2FyDbj%2FEvaZtGjs2lie7f3sl1ZBsQp5gkFXM3XGoA87pYz1y1RXo0PpVCzm%2FWD8pjbMCP8ChrjpYlRKD%2F12JGv5V5t2Ta7JW%2BZHEq0vF5x9xFANhn%2Fx%2B4IHl4Ts0D4RHAiJ0A0clSF8kMMaGDvNStLx61ZPvl%2B9sA93VV8I%2FxBQXG9Dm0PXiGLgQiWGw9Gx1t%2FYwxdMQsc454RA%2BYDAAZL1RkubnA3oKik50%2Bw4R75s%2FVjlor7Bt1TZTnu1NW5CYH8RvSr%2B1D4V2nWYyDVLg8NdG0zcRdlth0rsRcKQsUbzGBVcMiiYfzS%2B3Mh000GjY%2BVMgy0Tusw9rKpvQY6pgFYRNAuAcWSmWH%2BN2U3T6e%2FyRk6LdUcXvvhtFaAFRN52K8YqzZKSmYhrBSj8CUaNc0KLPxAetk3EkzwP0fIzE5xE6%2BqFrU751jbf6YayQTsA%2FYeQ3Fp37dhb8oowcUAwLeviOm0l%2BWwuG2m1L9axqLll%2FCO7ZtYmh1ht5BnGgDxgf9bjbQuXNdhzxxV4NHiz4vk0Dq36jhlftokLTNY5dtpiLz5S2Ql&X-Amz-Signature=843aa8f7492b24fc616bde818db63cdb84607cdaab4ad16db6cc0cbda550570b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466S5AC4P35%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T202502Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIGreN%2Bz6KuOKeOKPfTuKvGzT4YlIW6w37rnnBMOzR61LAiAHNZM8pBcdDi61bDGkHf7mbZOgFkl3CBSsmpk3wWNGISqIBAjF%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM4jA5q%2F18xs6dAgoyKtwDLnKP0dN0XqzhIO2QK1ODv3cwFLbujY1NDcE9tSAiNsqd9VzoqDMFLw9zVHlpc4FqHIJIkuI01a1a1rSP4j3Uh%2Bi0y4oDNW%2F6kn6H%2FpVxKN025chHwJ6c6js3HQz6ajiNmHcyKsxAFsVV1VPLf9eywl0lf%2F2g0l9waNSJhQf4WndSxFGgc1WuuSjkASfgPjHeVGlPAc0Vl05QppdXqMmjg4%2BQeeSfwaNja26VWpKxfJdBLTZdhjGadrH459VStmJQi%2Fl5jwA6x9HLwc%2Fm%2BnQxhXStZQPTWXFHCcXi7lyc48gHm7r2gBH%2FyDbj%2FEvaZtGjs2lie7f3sl1ZBsQp5gkFXM3XGoA87pYz1y1RXo0PpVCzm%2FWD8pjbMCP8ChrjpYlRKD%2F12JGv5V5t2Ta7JW%2BZHEq0vF5x9xFANhn%2Fx%2B4IHl4Ts0D4RHAiJ0A0clSF8kMMaGDvNStLx61ZPvl%2B9sA93VV8I%2FxBQXG9Dm0PXiGLgQiWGw9Gx1t%2FYwxdMQsc454RA%2BYDAAZL1RkubnA3oKik50%2Bw4R75s%2FVjlor7Bt1TZTnu1NW5CYH8RvSr%2B1D4V2nWYyDVLg8NdG0zcRdlth0rsRcKQsUbzGBVcMiiYfzS%2B3Mh000GjY%2BVMgy0Tusw9rKpvQY6pgFYRNAuAcWSmWH%2BN2U3T6e%2FyRk6LdUcXvvhtFaAFRN52K8YqzZKSmYhrBSj8CUaNc0KLPxAetk3EkzwP0fIzE5xE6%2BqFrU751jbf6YayQTsA%2FYeQ3Fp37dhb8oowcUAwLeviOm0l%2BWwuG2m1L9axqLll%2FCO7ZtYmh1ht5BnGgDxgf9bjbQuXNdhzxxV4NHiz4vk0Dq36jhlftokLTNY5dtpiLz5S2Ql&X-Amz-Signature=b4bdf4852ef619e6116747cde4c203a7573dd55b0acb9062d7aa67b807060290&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XPGSM54H%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T202503Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIDGNpcr2tLNqhIytwHgtX0qrREQb66W3qnh9ieAgG91%2BAiBuXQklcBviwdQAP6zRnUmQjvgbB%2FYm2oXv71gF2y5DlSqIBAjF%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM5xhWu8YGGt3kMEONKtwD%2BfoHeyZEIojLmq6x18PwaY7VHFNncQMJSJ7lIjv%2FvLgp5T%2Bt3PHmTDeECkuHoYLs7rweaf2vo9%2Bc%2BFxCiayO7qlTFPLCJQU1Ljc%2BDjaZRbcsmdr3CcZZmQHUSnKwknunqmDqcnXxPu%2F2yM6g4P4LmOGfxHNDiAJHb%2Bsu%2FoHvv3jBRptE1J9pjnwobc7LHtLNUSc%2Bv9S5%2BYWQZTeRNTD8zLdPnHCgFtKEAKqFuQbFi25FLejHfkIQLlJi5fYobVx2lMVj6W4YcY5Johg5pFi0cHgzAixTINK0mHi%2B9o3jtEwV3ONFDBGKcGDOMLkXVXtmPJJRuRazHVbhUbr2PQr48xCcI21169tdonogefzotOmHo2Kbth2%2FIFoLaBpI%2F%2BcZHU8ULJMbQ%2FSd5FVmqsErrFNSaVZen0XDisHftJ3kBPN0b8ujIuwncuEPi2cIp%2F67ecDsRCSLxDaFZ58%2Fbforr8O04qewK9m8%2BkruDpgjiG%2FGY9PuxVzvGb86LQfU1Znm58QIWjM0iSufD5aIn24psmRFXQ4jGk0jrTlT2zTZrc0NDhh1IyWPR4UHsQNfBhEqw4NkhQFblVsN9e7JuyZXWEB1hI%2B7rENPF%2BCJ3jjr1xcC40N1ysDe%2FsAmy3EwgbOpvQY6pgGMGZ1l5NBMY0Zha6q9NNVb7B2TWGC3%2FQcPkgAu1hebHmclcWq4nbpMbFpj6g%2FnUSkXovVodRoVAYjEGqhOVb70CxHMKobu0jlaws9OpgKVCF9kjiH3ju2y5C5972io3vZ%2F9hp3BHZGbhl5qQfSm816WEVXmBbDMu6EWVLj1aP91b67LRnRMu9TT7qUKhqAleyTGIQig0tsvQwYR2TCw%2Bn3EJ%2BjsO1V&X-Amz-Signature=d1e7578ffa379f1b8e9f9ea9a0c5b4b68edcfb601859d6c4a6de3d5b49803760&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UFYZHOFY%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T202504Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIC%2F9XR2Ssp15vk54Pyfq0dcZsrhSGcNpNvZMxWzPrLoPAiB65beKQpXCKQzqAXEr2D0fmRkddn5HoS7kv%2BD8AQ%2B59iqIBAjF%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMMfcnXXTuf82ZJeNLKtwDUYVeWl%2B3JkaNpwTxeA9v8aLle0bUAwyeU8xH59781T760IK8DRjvrsN3iMm%2BswrueBY4zjf4znONwXCTZzgGncrp0oIQ%2FEichw8wYivmyNZp3Urb%2B5ZZeCYQM82o7fjFW9kCOnyIGzq4ow56IEyzld3GopBYCk2xgCACHI2lW7oE%2FLqzA73VE%2BSAfMC%2F0kAOb514ThoWMYwUf5CB0gkNifxEt7qac6ji0Wc2EVx8YeShnuzrKkkolDPBHCri4IwS6g269DJON%2F4h0Y9FYtJNCDSFQ7O4tIxihwDchijw9%2FAT8NXOL9ENQOyG7lHlkUOls1RoV2UFReBupTza4%2BQr4yuZL3s1OL0j5EUq%2FV8WKXTsB4OQhVzbVIs2kA4NWdnqO7K9KU71qFVpPr1CPK4BPmCgAfwxr2VI44i4LF2D1RDivCX1Ua2MftZNZdLbKAgGXvI7BU%2FVhoE0TLfhqr8YGX1ksxj11JVYJP23Z%2BEHUvEQO8Rqq7U%2Bod9wI0x5Kkzhc3RU3ZEFMNfNYHmiGPn2MYXkkd74TrCm0dsr9lQ%2F3ssf2LtYAjeQbop4yMBhE0t8yGzR1WR7wfYD5sWBLvIipP2fzMzr9%2BcsHE8QgOJwztaNJkc2kjg7%2BQekNdowqrOpvQY6pgGokVvO%2FxN4DtpX2favPpaA6jLGvcZGAyolIa9u941BSLPiGKVf7guszrBd%2FBGCWCaxWUKHjCp10pM6jtc3pMxjxJ6gS2HSkOu29fcNAPr6%2BM6LzixcgaIhzRVseNRUuxoqlD0Ds%2FFTlzGefHk%2BmjapwlBhZDLfEAiVA1p%2BXT3te%2F28PzuwGo1fIn%2F%2FL6vfXX5fIqApYaf7%2BCozc0UQOEt0wzp2h%2BlM&X-Amz-Signature=e9d3bff861594ee023840889aee76b505c254a8cff0df2d42bf0e720a9e183e0&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466S5AC4P35%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T202502Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIGreN%2Bz6KuOKeOKPfTuKvGzT4YlIW6w37rnnBMOzR61LAiAHNZM8pBcdDi61bDGkHf7mbZOgFkl3CBSsmpk3wWNGISqIBAjF%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM4jA5q%2F18xs6dAgoyKtwDLnKP0dN0XqzhIO2QK1ODv3cwFLbujY1NDcE9tSAiNsqd9VzoqDMFLw9zVHlpc4FqHIJIkuI01a1a1rSP4j3Uh%2Bi0y4oDNW%2F6kn6H%2FpVxKN025chHwJ6c6js3HQz6ajiNmHcyKsxAFsVV1VPLf9eywl0lf%2F2g0l9waNSJhQf4WndSxFGgc1WuuSjkASfgPjHeVGlPAc0Vl05QppdXqMmjg4%2BQeeSfwaNja26VWpKxfJdBLTZdhjGadrH459VStmJQi%2Fl5jwA6x9HLwc%2Fm%2BnQxhXStZQPTWXFHCcXi7lyc48gHm7r2gBH%2FyDbj%2FEvaZtGjs2lie7f3sl1ZBsQp5gkFXM3XGoA87pYz1y1RXo0PpVCzm%2FWD8pjbMCP8ChrjpYlRKD%2F12JGv5V5t2Ta7JW%2BZHEq0vF5x9xFANhn%2Fx%2B4IHl4Ts0D4RHAiJ0A0clSF8kMMaGDvNStLx61ZPvl%2B9sA93VV8I%2FxBQXG9Dm0PXiGLgQiWGw9Gx1t%2FYwxdMQsc454RA%2BYDAAZL1RkubnA3oKik50%2Bw4R75s%2FVjlor7Bt1TZTnu1NW5CYH8RvSr%2B1D4V2nWYyDVLg8NdG0zcRdlth0rsRcKQsUbzGBVcMiiYfzS%2B3Mh000GjY%2BVMgy0Tusw9rKpvQY6pgFYRNAuAcWSmWH%2BN2U3T6e%2FyRk6LdUcXvvhtFaAFRN52K8YqzZKSmYhrBSj8CUaNc0KLPxAetk3EkzwP0fIzE5xE6%2BqFrU751jbf6YayQTsA%2FYeQ3Fp37dhb8oowcUAwLeviOm0l%2BWwuG2m1L9axqLll%2FCO7ZtYmh1ht5BnGgDxgf9bjbQuXNdhzxxV4NHiz4vk0Dq36jhlftokLTNY5dtpiLz5S2Ql&X-Amz-Signature=85c0517df25e71dab159d76d4171b6456847633d2876e9e0007aa7066379e537&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466S5AC4P35%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T202502Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIGreN%2Bz6KuOKeOKPfTuKvGzT4YlIW6w37rnnBMOzR61LAiAHNZM8pBcdDi61bDGkHf7mbZOgFkl3CBSsmpk3wWNGISqIBAjF%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM4jA5q%2F18xs6dAgoyKtwDLnKP0dN0XqzhIO2QK1ODv3cwFLbujY1NDcE9tSAiNsqd9VzoqDMFLw9zVHlpc4FqHIJIkuI01a1a1rSP4j3Uh%2Bi0y4oDNW%2F6kn6H%2FpVxKN025chHwJ6c6js3HQz6ajiNmHcyKsxAFsVV1VPLf9eywl0lf%2F2g0l9waNSJhQf4WndSxFGgc1WuuSjkASfgPjHeVGlPAc0Vl05QppdXqMmjg4%2BQeeSfwaNja26VWpKxfJdBLTZdhjGadrH459VStmJQi%2Fl5jwA6x9HLwc%2Fm%2BnQxhXStZQPTWXFHCcXi7lyc48gHm7r2gBH%2FyDbj%2FEvaZtGjs2lie7f3sl1ZBsQp5gkFXM3XGoA87pYz1y1RXo0PpVCzm%2FWD8pjbMCP8ChrjpYlRKD%2F12JGv5V5t2Ta7JW%2BZHEq0vF5x9xFANhn%2Fx%2B4IHl4Ts0D4RHAiJ0A0clSF8kMMaGDvNStLx61ZPvl%2B9sA93VV8I%2FxBQXG9Dm0PXiGLgQiWGw9Gx1t%2FYwxdMQsc454RA%2BYDAAZL1RkubnA3oKik50%2Bw4R75s%2FVjlor7Bt1TZTnu1NW5CYH8RvSr%2B1D4V2nWYyDVLg8NdG0zcRdlth0rsRcKQsUbzGBVcMiiYfzS%2B3Mh000GjY%2BVMgy0Tusw9rKpvQY6pgFYRNAuAcWSmWH%2BN2U3T6e%2FyRk6LdUcXvvhtFaAFRN52K8YqzZKSmYhrBSj8CUaNc0KLPxAetk3EkzwP0fIzE5xE6%2BqFrU751jbf6YayQTsA%2FYeQ3Fp37dhb8oowcUAwLeviOm0l%2BWwuG2m1L9axqLll%2FCO7ZtYmh1ht5BnGgDxgf9bjbQuXNdhzxxV4NHiz4vk0Dq36jhlftokLTNY5dtpiLz5S2Ql&X-Amz-Signature=b6430619842e8ecf4a47843f90dbafc3cc74843edec666235286d5df5a023b94&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466S5AC4P35%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T202502Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIGreN%2Bz6KuOKeOKPfTuKvGzT4YlIW6w37rnnBMOzR61LAiAHNZM8pBcdDi61bDGkHf7mbZOgFkl3CBSsmpk3wWNGISqIBAjF%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM4jA5q%2F18xs6dAgoyKtwDLnKP0dN0XqzhIO2QK1ODv3cwFLbujY1NDcE9tSAiNsqd9VzoqDMFLw9zVHlpc4FqHIJIkuI01a1a1rSP4j3Uh%2Bi0y4oDNW%2F6kn6H%2FpVxKN025chHwJ6c6js3HQz6ajiNmHcyKsxAFsVV1VPLf9eywl0lf%2F2g0l9waNSJhQf4WndSxFGgc1WuuSjkASfgPjHeVGlPAc0Vl05QppdXqMmjg4%2BQeeSfwaNja26VWpKxfJdBLTZdhjGadrH459VStmJQi%2Fl5jwA6x9HLwc%2Fm%2BnQxhXStZQPTWXFHCcXi7lyc48gHm7r2gBH%2FyDbj%2FEvaZtGjs2lie7f3sl1ZBsQp5gkFXM3XGoA87pYz1y1RXo0PpVCzm%2FWD8pjbMCP8ChrjpYlRKD%2F12JGv5V5t2Ta7JW%2BZHEq0vF5x9xFANhn%2Fx%2B4IHl4Ts0D4RHAiJ0A0clSF8kMMaGDvNStLx61ZPvl%2B9sA93VV8I%2FxBQXG9Dm0PXiGLgQiWGw9Gx1t%2FYwxdMQsc454RA%2BYDAAZL1RkubnA3oKik50%2Bw4R75s%2FVjlor7Bt1TZTnu1NW5CYH8RvSr%2B1D4V2nWYyDVLg8NdG0zcRdlth0rsRcKQsUbzGBVcMiiYfzS%2B3Mh000GjY%2BVMgy0Tusw9rKpvQY6pgFYRNAuAcWSmWH%2BN2U3T6e%2FyRk6LdUcXvvhtFaAFRN52K8YqzZKSmYhrBSj8CUaNc0KLPxAetk3EkzwP0fIzE5xE6%2BqFrU751jbf6YayQTsA%2FYeQ3Fp37dhb8oowcUAwLeviOm0l%2BWwuG2m1L9axqLll%2FCO7ZtYmh1ht5BnGgDxgf9bjbQuXNdhzxxV4NHiz4vk0Dq36jhlftokLTNY5dtpiLz5S2Ql&X-Amz-Signature=0a3b996a9919e4756cd389e29b25123d099f11d8e436a8a4f88a3a594df9ace4&X-Amz-SignedHeaders=host&x-id=GetObject)


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

