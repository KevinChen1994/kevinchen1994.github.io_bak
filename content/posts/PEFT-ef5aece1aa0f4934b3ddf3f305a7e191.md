---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4663TCVUJCE%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250208T191813Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEHsaCXVzLXdlc3QtMiJGMEQCIBs6YYJZCyXdsU7q7tnvA6VjgZIHzF%2Ff7nnTMpKWPc%2F4AiB\
  3j6VEaB40hAWrlD10DQt2Zj7MWj805ePtwjxwRLjg2SqIBAiT%2F%2F%2F%2F%2F%2F%2F%2F%2F%\
  2F8BEAAaDDYzNzQyMzE4MzgwNSIMaKofVvo%2FgWvqgOh6KtwDl4y5UoBKOGY9PlHQ%2BsC4jmj3v\
  uIGaHtAXGu3oOV3DvFx3bRCKkzZ4fErU5B2gxPg6w9lE6%2FE5etPo5uLjiLXbJXx3CEywwJqYKYE\
  CJVWOlMqfmApU7dt70NATbeeyemOShyJiLIk8S2dOz5j7QWzFsfaoE3qdEbLpXZOS45JjhrN7hJQC\
  xZ6HLClzUxWQHNdXl0dvh%2F6QNH9N8bK%2BcIPRDhfeYKl%2F3Y5pFO%2F6VJ1Lo2oSczILsIH1O\
  Uqvee1kluem3C9Mf9tXYLEMgTuQSEzsGi6OklTI5rb4rpdoEHclK%2B0%2FHD9JGRJOpxjxR1hyd8\
  6pvpTA8%2B3OMNtkx%2BSyq0I3rNBpXSvhkWYACSgQdo0Kv8jqdAaRcPANrNNbi3WazDMAFqKYVZR\
  m8AaEMk1JlO0FEPjaioazf0V4%2B5QCNHiQb5%2FKvEV2bvh7h%2B7Eju2iAybEDoJIVB3OkIkbmi\
  hrxCo5jCsSqI7t52Vqnk79K9fx8hpsqfY6oV%2BGyUKDxbtrd2U0n%2FuzONvueuY3dJA9VKQWM3L\
  uu1RE8QSrv%2FTvijhjU2eMigWkhbItjrVJFH4X0K%2BYzemHWVB17ClLyPPxhgneoTaIYrM9lKJ0\
  EbqmzbY5D9JVfeB0o8HgpUA6q0w5cGevQY6pgFZJxZukeRlNMDrv%2FtDyamk%2FqstToCvkApuHD\
  jRfbZJbnEfDat66CBTNxfOLMT3QXozNPxAACcEHDNcjv6b3rSLfFViTGt77ZD8sNUdJW6h2rAgh80\
  R0Xx8qYzy8Jt0E1C9OJBgK%2BsbzIhMhLZV5mxid2V%2BAXD2jmYHRL%2FfdJLqftJU4YxRTknjVc\
  floFmzlUdwFHIwm2EQY3ABQORK80okWEUq57GP&X-Amz-Signature=c36d52b567b1908f54881c\
  4a8f0e13eee7c83f8d84b7570fcb363bc7df2c16a3&X-Amz-SignedHeaders=host&x-id=GetO\
  bject"
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
        redential=ASIAZI2LB466VXF533GC%2F20250208%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250208T191708Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJIMEYCIQDTBA3GEqDoeVtngIqFF22ksQWEl61\
        wu3vA9oY5DUposgIhAPaH12wA5JYmzoyIVCpGpSQjGLeFoWgKhSN%2FtiNquht4KogECJP%\
        2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igz6MPVsHVIvN88pLL0\
        q3APVDAybw4Yap%2FT5TNd45yHiYiGL1HrKDFrACjTZjnrnAVj23MjIDupJagMJVHjP%2Bm\
        bOg64sGk1CWKD7AZWv1cHviMH8B%2FMSQBsxeF1J7jJJMenpzdB56GY%2FcjD%2F1WLoOGn\
        y6muQgmQ4fjCnIqMlpUpojDC2l2dcc1xdBxaMOKUGlDGg2wbRdZbkxE8uh8OIMiAUJxkmT6\
        L3E%2F5wE4buV06WZRydndB3WkjwO535PDDV%2BrRBxXBlIwN3GJEP5fF18YiR%2BuHXI8e\
        pvDG21cNFgAxaD%2BMcl9joSLfvZW7tdemVOWdgy7NUaTtXpDXCe4il9QcWbtZxQHy3PvlQ\
        5HY81ByXYKvHY4hOWByPu2h2z0YuIbrPVZ5kIt7aToT%2Fxr3yHBeALhnm6rAoe7zaw0yuV\
        xsGW3ErdkiNv3b8WTkECEk%2BXmEC%2Fn8N1chehjjxoKoXfbrcwLTtQbShHXQvqBZvJpKL\
        8fgtrG%2Fd8rwTSJoK6wW4DMYKIf3N68lKNDl1mDT31XaERANA7UJGZ1Zbl%2FvKmrMDFOQ\
        ayz8K3BdWEIrl8GwzMeXXvDEjvDqR%2BHG%2B0V4%2Fy2J8vyvNrVDNsao73B6wjL19KwxX\
        9RMY4NH1aiDbMNauXz8prha7rU2QHI9I0DC%2BwZ69BjqkAf3Xkni%2Fv5RXmBe86d4XETc\
        NH%2BU1Eck2CF0fU8xvsE8UAFiOQBr67pg7%2FQavG3pkAeXy7KfuKv%2FN%2FY3aJLLVXC\
        NwzM9ogNKaP90lTzUYQqXypw2k0uyo3NXsifFI60i7%2Flagm6SsP%2BuJEOAnGI7WcDr0F\
        9xYB%2FGZMIsiZp2V5qPsWne0jNXE3Fey4w10wx1YeGvZz0FtyG4xu6ANJFvjYNZST29e&X\
        -Amz-Signature=6c9d83c57634a5bc57ddd24407aad4dd6467b4d0825d7476c31a4def\
        cb27faf3&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-08T20:17:08.897Z"
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
UPDATE_TIME: "2025-02-08T19:18:18.317Z"
EXPIRY_TIME: "2025-02-08T20:18:10.590Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662DG4TX2I%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T191811Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJIMEYCIQDtgmfI1PaalGelLDvlRlm20aD1PFNUu8SWtvCrB%2F2lggIhANBLJZgHKz3I8x9gvpFRcvKNIzE3HbL6e3njyBIBsD8ZKogECJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igw1wwZdG0y9%2FrMyM0Eq3AOxv9UDAKpZ9zOPYZuThKnjFcnVyuto9VRb01no5iv2kemGTAJTkF93F0qFG%2FutaxDT4vqjiOpI87jHHMF2v7qzbqYiiMTnWPTywQiDISedfDz9xgXxAxxGfLyUspLqRV3QkKnU7v9bGliVK1QCQdZQXtS1eatlPw409syZzrAYpKLkXFMtUyUHMUDI0%2BUWo6VycAVA3suFQVRxFoarYwr0vhyo3MRH50VuPjSZirGTBsCyr%2BPe6RVgPmOlRSGSI%2F8cK2bo4Rmjw%2BcPwMKGXTDGirCxZ0lJnx5DVwEVS%2FamI5mQLqF2CBN3Zlydm%2BhzWqi1EGDVH4lM0l5%2FVyJh61DU9eROQDRGYG7dAihODZblp8Kwp1Uyhuxu7ryct84E%2Fp2%2FIVGAcLL%2FabL0hzEGyVEuUCUGHhrdon8GZ6gTA4nHxdHAJ1Ur4JcTsJzgCQEAD7UzK3OdI6gU43HcdlOUo0BxNFZcJLeHcWjRwXm0MoJGo8a02S6LpFrCCJ3GG2dQKQZJMhw7s5puiqpdpTKJUSn%2BsYxlksQ4ItVch3%2BH%2FMpLk68CTVG1%2B7NvpEwX9eOL56fr3q4sB%2BxMqPJPYLS4LdV5N79PMeAP3o2psVrq1U85TBS1K5as0PMOCVFUejCiwZ69BjqkAZPe3X268i%2FuAz8wBKRGXzwqBgdTHv0NmgLuRQMY0du8HrqEqhe9fWJ%2BNBMqJDLea0gjy8wpZVWXqn2yCGFGzok1st8lJ3DOhBv1tPbIOBGnQBpLXJPWMCQsQx1GzrSohzDMijx0DICrVY6Otftf6Nq5lThKPhpBWdkM62fMPHWs4CI1vvTPIt%2F4qaAqQS0BXO93rndVGB9muXfCA0ULWsntmWxk&X-Amz-Signature=2fd4300c71fb873f54a5ba5c678bd65a6df40a5ff26df563f15348790b3a80b8&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662DG4TX2I%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T191811Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJIMEYCIQDtgmfI1PaalGelLDvlRlm20aD1PFNUu8SWtvCrB%2F2lggIhANBLJZgHKz3I8x9gvpFRcvKNIzE3HbL6e3njyBIBsD8ZKogECJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igw1wwZdG0y9%2FrMyM0Eq3AOxv9UDAKpZ9zOPYZuThKnjFcnVyuto9VRb01no5iv2kemGTAJTkF93F0qFG%2FutaxDT4vqjiOpI87jHHMF2v7qzbqYiiMTnWPTywQiDISedfDz9xgXxAxxGfLyUspLqRV3QkKnU7v9bGliVK1QCQdZQXtS1eatlPw409syZzrAYpKLkXFMtUyUHMUDI0%2BUWo6VycAVA3suFQVRxFoarYwr0vhyo3MRH50VuPjSZirGTBsCyr%2BPe6RVgPmOlRSGSI%2F8cK2bo4Rmjw%2BcPwMKGXTDGirCxZ0lJnx5DVwEVS%2FamI5mQLqF2CBN3Zlydm%2BhzWqi1EGDVH4lM0l5%2FVyJh61DU9eROQDRGYG7dAihODZblp8Kwp1Uyhuxu7ryct84E%2Fp2%2FIVGAcLL%2FabL0hzEGyVEuUCUGHhrdon8GZ6gTA4nHxdHAJ1Ur4JcTsJzgCQEAD7UzK3OdI6gU43HcdlOUo0BxNFZcJLeHcWjRwXm0MoJGo8a02S6LpFrCCJ3GG2dQKQZJMhw7s5puiqpdpTKJUSn%2BsYxlksQ4ItVch3%2BH%2FMpLk68CTVG1%2B7NvpEwX9eOL56fr3q4sB%2BxMqPJPYLS4LdV5N79PMeAP3o2psVrq1U85TBS1K5as0PMOCVFUejCiwZ69BjqkAZPe3X268i%2FuAz8wBKRGXzwqBgdTHv0NmgLuRQMY0du8HrqEqhe9fWJ%2BNBMqJDLea0gjy8wpZVWXqn2yCGFGzok1st8lJ3DOhBv1tPbIOBGnQBpLXJPWMCQsQx1GzrSohzDMijx0DICrVY6Otftf6Nq5lThKPhpBWdkM62fMPHWs4CI1vvTPIt%2F4qaAqQS0BXO93rndVGB9muXfCA0ULWsntmWxk&X-Amz-Signature=5e8c6296b53958d03e3e599c79a647c3377c8d529bce35ab5f5cc86ba5bbbbb4&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662DG4TX2I%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T191811Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJIMEYCIQDtgmfI1PaalGelLDvlRlm20aD1PFNUu8SWtvCrB%2F2lggIhANBLJZgHKz3I8x9gvpFRcvKNIzE3HbL6e3njyBIBsD8ZKogECJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igw1wwZdG0y9%2FrMyM0Eq3AOxv9UDAKpZ9zOPYZuThKnjFcnVyuto9VRb01no5iv2kemGTAJTkF93F0qFG%2FutaxDT4vqjiOpI87jHHMF2v7qzbqYiiMTnWPTywQiDISedfDz9xgXxAxxGfLyUspLqRV3QkKnU7v9bGliVK1QCQdZQXtS1eatlPw409syZzrAYpKLkXFMtUyUHMUDI0%2BUWo6VycAVA3suFQVRxFoarYwr0vhyo3MRH50VuPjSZirGTBsCyr%2BPe6RVgPmOlRSGSI%2F8cK2bo4Rmjw%2BcPwMKGXTDGirCxZ0lJnx5DVwEVS%2FamI5mQLqF2CBN3Zlydm%2BhzWqi1EGDVH4lM0l5%2FVyJh61DU9eROQDRGYG7dAihODZblp8Kwp1Uyhuxu7ryct84E%2Fp2%2FIVGAcLL%2FabL0hzEGyVEuUCUGHhrdon8GZ6gTA4nHxdHAJ1Ur4JcTsJzgCQEAD7UzK3OdI6gU43HcdlOUo0BxNFZcJLeHcWjRwXm0MoJGo8a02S6LpFrCCJ3GG2dQKQZJMhw7s5puiqpdpTKJUSn%2BsYxlksQ4ItVch3%2BH%2FMpLk68CTVG1%2B7NvpEwX9eOL56fr3q4sB%2BxMqPJPYLS4LdV5N79PMeAP3o2psVrq1U85TBS1K5as0PMOCVFUejCiwZ69BjqkAZPe3X268i%2FuAz8wBKRGXzwqBgdTHv0NmgLuRQMY0du8HrqEqhe9fWJ%2BNBMqJDLea0gjy8wpZVWXqn2yCGFGzok1st8lJ3DOhBv1tPbIOBGnQBpLXJPWMCQsQx1GzrSohzDMijx0DICrVY6Otftf6Nq5lThKPhpBWdkM62fMPHWs4CI1vvTPIt%2F4qaAqQS0BXO93rndVGB9muXfCA0ULWsntmWxk&X-Amz-Signature=5d6508b0a6e52242eb1fee6a260d48e1a2695e01fa13830516a6618505a57305&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662DG4TX2I%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T191811Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJIMEYCIQDtgmfI1PaalGelLDvlRlm20aD1PFNUu8SWtvCrB%2F2lggIhANBLJZgHKz3I8x9gvpFRcvKNIzE3HbL6e3njyBIBsD8ZKogECJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igw1wwZdG0y9%2FrMyM0Eq3AOxv9UDAKpZ9zOPYZuThKnjFcnVyuto9VRb01no5iv2kemGTAJTkF93F0qFG%2FutaxDT4vqjiOpI87jHHMF2v7qzbqYiiMTnWPTywQiDISedfDz9xgXxAxxGfLyUspLqRV3QkKnU7v9bGliVK1QCQdZQXtS1eatlPw409syZzrAYpKLkXFMtUyUHMUDI0%2BUWo6VycAVA3suFQVRxFoarYwr0vhyo3MRH50VuPjSZirGTBsCyr%2BPe6RVgPmOlRSGSI%2F8cK2bo4Rmjw%2BcPwMKGXTDGirCxZ0lJnx5DVwEVS%2FamI5mQLqF2CBN3Zlydm%2BhzWqi1EGDVH4lM0l5%2FVyJh61DU9eROQDRGYG7dAihODZblp8Kwp1Uyhuxu7ryct84E%2Fp2%2FIVGAcLL%2FabL0hzEGyVEuUCUGHhrdon8GZ6gTA4nHxdHAJ1Ur4JcTsJzgCQEAD7UzK3OdI6gU43HcdlOUo0BxNFZcJLeHcWjRwXm0MoJGo8a02S6LpFrCCJ3GG2dQKQZJMhw7s5puiqpdpTKJUSn%2BsYxlksQ4ItVch3%2BH%2FMpLk68CTVG1%2B7NvpEwX9eOL56fr3q4sB%2BxMqPJPYLS4LdV5N79PMeAP3o2psVrq1U85TBS1K5as0PMOCVFUejCiwZ69BjqkAZPe3X268i%2FuAz8wBKRGXzwqBgdTHv0NmgLuRQMY0du8HrqEqhe9fWJ%2BNBMqJDLea0gjy8wpZVWXqn2yCGFGzok1st8lJ3DOhBv1tPbIOBGnQBpLXJPWMCQsQx1GzrSohzDMijx0DICrVY6Otftf6Nq5lThKPhpBWdkM62fMPHWs4CI1vvTPIt%2F4qaAqQS0BXO93rndVGB9muXfCA0ULWsntmWxk&X-Amz-Signature=154b176b1587b9886102b7cd0d70d73285bf9083584a32d0753438d1bbb462c9&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662DG4TX2I%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T191811Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJIMEYCIQDtgmfI1PaalGelLDvlRlm20aD1PFNUu8SWtvCrB%2F2lggIhANBLJZgHKz3I8x9gvpFRcvKNIzE3HbL6e3njyBIBsD8ZKogECJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igw1wwZdG0y9%2FrMyM0Eq3AOxv9UDAKpZ9zOPYZuThKnjFcnVyuto9VRb01no5iv2kemGTAJTkF93F0qFG%2FutaxDT4vqjiOpI87jHHMF2v7qzbqYiiMTnWPTywQiDISedfDz9xgXxAxxGfLyUspLqRV3QkKnU7v9bGliVK1QCQdZQXtS1eatlPw409syZzrAYpKLkXFMtUyUHMUDI0%2BUWo6VycAVA3suFQVRxFoarYwr0vhyo3MRH50VuPjSZirGTBsCyr%2BPe6RVgPmOlRSGSI%2F8cK2bo4Rmjw%2BcPwMKGXTDGirCxZ0lJnx5DVwEVS%2FamI5mQLqF2CBN3Zlydm%2BhzWqi1EGDVH4lM0l5%2FVyJh61DU9eROQDRGYG7dAihODZblp8Kwp1Uyhuxu7ryct84E%2Fp2%2FIVGAcLL%2FabL0hzEGyVEuUCUGHhrdon8GZ6gTA4nHxdHAJ1Ur4JcTsJzgCQEAD7UzK3OdI6gU43HcdlOUo0BxNFZcJLeHcWjRwXm0MoJGo8a02S6LpFrCCJ3GG2dQKQZJMhw7s5puiqpdpTKJUSn%2BsYxlksQ4ItVch3%2BH%2FMpLk68CTVG1%2B7NvpEwX9eOL56fr3q4sB%2BxMqPJPYLS4LdV5N79PMeAP3o2psVrq1U85TBS1K5as0PMOCVFUejCiwZ69BjqkAZPe3X268i%2FuAz8wBKRGXzwqBgdTHv0NmgLuRQMY0du8HrqEqhe9fWJ%2BNBMqJDLea0gjy8wpZVWXqn2yCGFGzok1st8lJ3DOhBv1tPbIOBGnQBpLXJPWMCQsQx1GzrSohzDMijx0DICrVY6Otftf6Nq5lThKPhpBWdkM62fMPHWs4CI1vvTPIt%2F4qaAqQS0BXO93rndVGB9muXfCA0ULWsntmWxk&X-Amz-Signature=e8e095c4cc0c4cb6439346a4f8bc2b0c6f2f1d7a77b28d74db75f7614b0e1bb8&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665RDXOBZQ%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T191812Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJIMEYCIQCnDwpajRxIe4GygprrR1KqtSqi%2Fydjzlo1CTi3OV27EAIhAJqoNeLqx7ktn7v8XA%2Bf1VVvpNAcEeSDoV7ISpvHn06MKogECJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwnKWQ6KmrD%2FeKXbGEq3AO5PwdWX9wBbGtnkkIAA1XvFzbpKVFa1qHOsic5ftGOcVJ1i0GRa8WHWZCS7FlLpzSxlcSAXN814zBrvHl7u6yqPFZeql5OTllth4SilLEhy1J0iYjwuIjZytteb3YLiNsZStcuBY2S%2FVB%2B%2BGRb4gHdfm82EKHO3EIGfcprbYa7ZhOlOFM6ioq8Pj6nlARp5nKFTvgtOVXqybbf%2B%2FZ8BTmQ%2F9k5nSDq0%2BWfF3%2BfOxE8eRFEbek4uRP6qkYbi5JrrhXPA95vsRt2%2B%2FkJ%2B3N%2BbPWxVRRq%2FmRELI18PKCBWme0p0GRTdPS7%2BQ2DUP3sIlnlI%2BifPTpLneYQb6rwZ8Sys%2FJNZR%2F0tg0Kq9r%2Ba2y5KWe0vPjwdwodQwI6rfRPC%2F2Dls140tjPE8zvEAYH0POw5obnGWnVEej0ErbFvgVxuZTkG5JlHugMr6M%2BSADSp8bxpi9bGaN%2BIPofrRE0iG7e0wilSzdXC8EjIkFq2aVz575ySGMSVF%2BNzOpk9bsX%2FYSiIKNmeQj%2FDtL%2BuEIdkaYCAXopJLSxbEBUJoGGZlVfNhcy4XKT%2BlNLkG62rQHMXGgIR%2FyyLpq2Dt5Q%2FOIUzXwhXPYvSI5wEGt9gAPWNzmKqLvBATrUOOZY0zeW%2FyeezCgwp69BjqkAezB04S2UADswWsiaDK7CnMAlHxnIUE%2FvToSQI%2BNaSpa6knluake3FFVwl14chBbsP4ObaMa0YZHJmC%2F9ntSiAKJfnOSEVrfSFK5wM5Y4tLItydtscGQCFfOBjnLAP1r%2FvRc9yuqNAWWgxt%2Bs2Sgk%2FhTazdLLB3NP3jzhOm74PuvcN8iHt7Z6iuDly4XkLJ1EDgxiSzZt4jEx%2B3yLON8lDHhr8AL&X-Amz-Signature=7a723d283f2cd1081f91063c9cfaa919c278dcfe8c86e4de4c6977db3de5ec0d&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZSG2PNVI%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T191813Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJIMEYCIQCyhx2OcM9zx7kPp7dYByRDGnB3M9w18ER%2F1JVuS%2BX8%2BgIhAJuC0IYpDikGGxTkr6FvLATlXBhuB9er1QBtdhbm3mw6KogECJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgycBghUgsj7OLFgfAgq3AMddjIORvDavPNq%2F6v739%2BMIIUKKwBK40mmdLXNgh7T0B5v9z7AwCaiVgtxZ%2FM9tvCrv11wiaFGZXgxUeerKCKUPoBELj3Zcb2P21yROwXdIULdL2UUZv1hib5wjCFyKszB9ONKkAeQ4ViPQxdgkRXozmROvLi6a8YbQbPfaIZL3xlSFnrpxlYPE0wtIhtxlqJX9DRShC8L%2FXT16%2BSEy9784p9CSFDiPY9Sq1AV5jUWEjtqJlRKW7wrb83YuVBtBfEr7MJp00bSf4G2pVxvvCUe3%2FdP0g0jCNU%2BZeB76ehTGk39LVZHR64lMOPBWKLOIW%2BDa0khsRuqiOOUHjPJJjL72eMR3wjQVdkc%2B0PxnnA5i9foxT7q7CK%2FabrQG7w5A34GaZsn9aK81CSq2mOwLub2fqs823VLfF8czGwPJTErIruvtGqzkU9ZPtKke5MmjICYpadwO6xsfFxjUVazH6ESEHeMbJEOb5cRI%2FCUpAfxKSO8sfflbdt3Wa2t5pkpphSCQZRHfuQzqYSsKVbacg8CVVvF27h6M25UU7f2NT9CglkSw%2BN3uRy%2FZ%2BYpmhrVBtvJUsciYi5XOYZQZ1BCFuEupccIhRK1UoAKdrTC%2BeTxfooUGrhJpDrLTDHsODCmwZ69BjqkAXzZqZN1tStJTtfP3hb2ukd%2FlVA%2BynuzVdJ8m8YWKLk32lV3GaYox4h0jSiksgSNPUjQHhucoG%2FF39RR9n3cJDbrrVUfli2NqH24%2F6TytpBCdAmGrZZyYZHHFXFbmto0ViOoN1X6Wn1Mzm%2F6qSo1DR1Sus9YR4XcrFKpCKVDPLxeIDE7EScw%2FaSP7y61l7F%2FXP89FTynTvP5b4psiYezSu8WHsP0&X-Amz-Signature=c788d78b95b328dcc42be4e4c5db0856cc375e4cfbefb9dc5eff13f4d31a12bb&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662DG4TX2I%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T191811Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJIMEYCIQDtgmfI1PaalGelLDvlRlm20aD1PFNUu8SWtvCrB%2F2lggIhANBLJZgHKz3I8x9gvpFRcvKNIzE3HbL6e3njyBIBsD8ZKogECJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igw1wwZdG0y9%2FrMyM0Eq3AOxv9UDAKpZ9zOPYZuThKnjFcnVyuto9VRb01no5iv2kemGTAJTkF93F0qFG%2FutaxDT4vqjiOpI87jHHMF2v7qzbqYiiMTnWPTywQiDISedfDz9xgXxAxxGfLyUspLqRV3QkKnU7v9bGliVK1QCQdZQXtS1eatlPw409syZzrAYpKLkXFMtUyUHMUDI0%2BUWo6VycAVA3suFQVRxFoarYwr0vhyo3MRH50VuPjSZirGTBsCyr%2BPe6RVgPmOlRSGSI%2F8cK2bo4Rmjw%2BcPwMKGXTDGirCxZ0lJnx5DVwEVS%2FamI5mQLqF2CBN3Zlydm%2BhzWqi1EGDVH4lM0l5%2FVyJh61DU9eROQDRGYG7dAihODZblp8Kwp1Uyhuxu7ryct84E%2Fp2%2FIVGAcLL%2FabL0hzEGyVEuUCUGHhrdon8GZ6gTA4nHxdHAJ1Ur4JcTsJzgCQEAD7UzK3OdI6gU43HcdlOUo0BxNFZcJLeHcWjRwXm0MoJGo8a02S6LpFrCCJ3GG2dQKQZJMhw7s5puiqpdpTKJUSn%2BsYxlksQ4ItVch3%2BH%2FMpLk68CTVG1%2B7NvpEwX9eOL56fr3q4sB%2BxMqPJPYLS4LdV5N79PMeAP3o2psVrq1U85TBS1K5as0PMOCVFUejCiwZ69BjqkAZPe3X268i%2FuAz8wBKRGXzwqBgdTHv0NmgLuRQMY0du8HrqEqhe9fWJ%2BNBMqJDLea0gjy8wpZVWXqn2yCGFGzok1st8lJ3DOhBv1tPbIOBGnQBpLXJPWMCQsQx1GzrSohzDMijx0DICrVY6Otftf6Nq5lThKPhpBWdkM62fMPHWs4CI1vvTPIt%2F4qaAqQS0BXO93rndVGB9muXfCA0ULWsntmWxk&X-Amz-Signature=f93e668c6b90432905b23c4dc6c1bf178dc21bf1ddc3d50e08c48f9a17c72d2b&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662DG4TX2I%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T191811Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJIMEYCIQDtgmfI1PaalGelLDvlRlm20aD1PFNUu8SWtvCrB%2F2lggIhANBLJZgHKz3I8x9gvpFRcvKNIzE3HbL6e3njyBIBsD8ZKogECJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igw1wwZdG0y9%2FrMyM0Eq3AOxv9UDAKpZ9zOPYZuThKnjFcnVyuto9VRb01no5iv2kemGTAJTkF93F0qFG%2FutaxDT4vqjiOpI87jHHMF2v7qzbqYiiMTnWPTywQiDISedfDz9xgXxAxxGfLyUspLqRV3QkKnU7v9bGliVK1QCQdZQXtS1eatlPw409syZzrAYpKLkXFMtUyUHMUDI0%2BUWo6VycAVA3suFQVRxFoarYwr0vhyo3MRH50VuPjSZirGTBsCyr%2BPe6RVgPmOlRSGSI%2F8cK2bo4Rmjw%2BcPwMKGXTDGirCxZ0lJnx5DVwEVS%2FamI5mQLqF2CBN3Zlydm%2BhzWqi1EGDVH4lM0l5%2FVyJh61DU9eROQDRGYG7dAihODZblp8Kwp1Uyhuxu7ryct84E%2Fp2%2FIVGAcLL%2FabL0hzEGyVEuUCUGHhrdon8GZ6gTA4nHxdHAJ1Ur4JcTsJzgCQEAD7UzK3OdI6gU43HcdlOUo0BxNFZcJLeHcWjRwXm0MoJGo8a02S6LpFrCCJ3GG2dQKQZJMhw7s5puiqpdpTKJUSn%2BsYxlksQ4ItVch3%2BH%2FMpLk68CTVG1%2B7NvpEwX9eOL56fr3q4sB%2BxMqPJPYLS4LdV5N79PMeAP3o2psVrq1U85TBS1K5as0PMOCVFUejCiwZ69BjqkAZPe3X268i%2FuAz8wBKRGXzwqBgdTHv0NmgLuRQMY0du8HrqEqhe9fWJ%2BNBMqJDLea0gjy8wpZVWXqn2yCGFGzok1st8lJ3DOhBv1tPbIOBGnQBpLXJPWMCQsQx1GzrSohzDMijx0DICrVY6Otftf6Nq5lThKPhpBWdkM62fMPHWs4CI1vvTPIt%2F4qaAqQS0BXO93rndVGB9muXfCA0ULWsntmWxk&X-Amz-Signature=644c262dfff4c43f3ca9ed2488549e191469f24511c1692d94c230633b18444c&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662DG4TX2I%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T191811Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJIMEYCIQDtgmfI1PaalGelLDvlRlm20aD1PFNUu8SWtvCrB%2F2lggIhANBLJZgHKz3I8x9gvpFRcvKNIzE3HbL6e3njyBIBsD8ZKogECJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igw1wwZdG0y9%2FrMyM0Eq3AOxv9UDAKpZ9zOPYZuThKnjFcnVyuto9VRb01no5iv2kemGTAJTkF93F0qFG%2FutaxDT4vqjiOpI87jHHMF2v7qzbqYiiMTnWPTywQiDISedfDz9xgXxAxxGfLyUspLqRV3QkKnU7v9bGliVK1QCQdZQXtS1eatlPw409syZzrAYpKLkXFMtUyUHMUDI0%2BUWo6VycAVA3suFQVRxFoarYwr0vhyo3MRH50VuPjSZirGTBsCyr%2BPe6RVgPmOlRSGSI%2F8cK2bo4Rmjw%2BcPwMKGXTDGirCxZ0lJnx5DVwEVS%2FamI5mQLqF2CBN3Zlydm%2BhzWqi1EGDVH4lM0l5%2FVyJh61DU9eROQDRGYG7dAihODZblp8Kwp1Uyhuxu7ryct84E%2Fp2%2FIVGAcLL%2FabL0hzEGyVEuUCUGHhrdon8GZ6gTA4nHxdHAJ1Ur4JcTsJzgCQEAD7UzK3OdI6gU43HcdlOUo0BxNFZcJLeHcWjRwXm0MoJGo8a02S6LpFrCCJ3GG2dQKQZJMhw7s5puiqpdpTKJUSn%2BsYxlksQ4ItVch3%2BH%2FMpLk68CTVG1%2B7NvpEwX9eOL56fr3q4sB%2BxMqPJPYLS4LdV5N79PMeAP3o2psVrq1U85TBS1K5as0PMOCVFUejCiwZ69BjqkAZPe3X268i%2FuAz8wBKRGXzwqBgdTHv0NmgLuRQMY0du8HrqEqhe9fWJ%2BNBMqJDLea0gjy8wpZVWXqn2yCGFGzok1st8lJ3DOhBv1tPbIOBGnQBpLXJPWMCQsQx1GzrSohzDMijx0DICrVY6Otftf6Nq5lThKPhpBWdkM62fMPHWs4CI1vvTPIt%2F4qaAqQS0BXO93rndVGB9muXfCA0ULWsntmWxk&X-Amz-Signature=1557ad84378d923864dd9501d580f528d90bff6910068b3b4b15d029b579280a&X-Amz-SignedHeaders=host&x-id=GetObject)


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

