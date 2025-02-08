---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466TJAQYMUI%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250208T032522Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEGsaCXVzLXdlc3QtMiJGMEQCIEUpE%2FLa7%2FY8nCfX6LZgmoFTwcgFZ%2FiXEtkz%2FV9Zx3c\
  2AiAXtYgocwEK0a6zjKv4BJxzTTM2ZAO%2BvbzAxoIJRmxswyqIBAiE%2F%2F%2F%2F%2F%2F%2F%\
  2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMZA2%2Bu%2FnbGoF%2B7v6mKtwDShqHWXy0PdFmst%2B\
  %2Blg%2BGvy1z2YDqV2IEaTg6kp9crOlhQvtMWzxy4BUmATqPzGdNBc1OqZ9ZGHUCcxhjc5VsSwp%\
  2FFDC6vwCQ0Pr0dWdkvFaeX6gLRINBrdo6M92mrEAoQ81VmwMaCQA9OgDszicTKC5P4igVXI09eIy\
  9Pq3hnxernS4%2BCnYAJW3KbJrjaCgKCU4fIY%2FVrzOZL9eCjj6cl8WfpYCRkIS3g5u60OpL7txr\
  jXGodopumHQBuECSeQcOimGwsr2Nn9XA1%2F%2FrHT%2Fl7gEjmZU0NSxqhJ8n6zzlP6FDT%2Fz7D\
  xkcibQfVFc5Y8RTlnOeUWXfgAAZSR53WR2yvEcgsryqgYgQsMxIVW8E%2Bejs1Cm%2F2O%2BPchAR\
  HbvBF0k4XDKBES9JVdDWLLkymi1yHPxJ2psE6quE7J8lxf50h1RKoEat3S6llhuntQFPW46%2FwN5\
  FB5XivawMm%2Ftu%2B1nf8wTmgHT5RTbjAUXTyQ76kfjV8heSA6REYNGnBxRlzqznry7nnG4K2Dmd\
  6kg%2BvW1C8jVPnev2QXKur8pi6hOA9NEsly4bFcTI2I%2BTlHhY1tDTm2LfDGTXU8TDc9hI19Ovx\
  cwVYBPhnFadGZGFgrDmsQUtgSHOTHMdf5roYBEw%2BZabvQY6pgEoDtPvesgaT6aM%2FM9TBRQORl\
  mhAxSqX0EDcaxGBHWg9C7H72rUoxZUv1X3lqRVNU8Wb2VgeOmz%2BSOAtbi0yFNrI7JNDCsNhQNP%\
  2F%2FuMsqpmxY5aJ%2FfyVs96lfFVneQw1WCrk%2FtWKXkryaqyS7GiXFJEeGDa2ZWsYsjzj%2Bl8\
  OUF5JiaxhpR81J7GiYufhAUWbDS1lFAwT2EzsHjKM4MmwZWpqxzZpW%2Fz&X-Amz-Signature=05\
  e137a785dd7beed13aae36c7d67ca951818521675e79e33db9b49feaf4cd77&X-Amz-SignedHe\
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
        redential=ASIAZI2LB466TMIIV673%2F20250208%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250208T032401Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEGsaCXVzLXdlc3QtMiJIMEYCIQD1fmdPuBrtIiWUbVGwXUn%2BKfwZ8\
        Qa5sK0%2FIERn92A6WQIhAO%2Bbr5yFJgzRhEYjc3FfpFw%2BcP0mevZrq6NAIQwtvvyLKo\
        gECIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxUfjdN%2FLF\
        mhaEMH3gq3AP0DBHaCu3p0jo2yz7RzRMYjKsjHGEiFT0T781hoHf6cX70Y5OQptzToTLENJ\
        4M5%2FxyOrbVo%2B4KK9ZjDRRevbQqoFhh1EkzZy6D5j%2B1okBtcxsztxPAegxy5fYozrg\
        sR3vzBkud%2FOgQ9XYib44Fd%2Fuc3c5gFb7zo991BCokmk9%2FJrVj6j2VX%2B1hFXvdzl\
        IqFuig4KX7jjnEPjlg3Z%2BDCKx%2B2nF%2F5RCRcQVw4IlKajDijzwEv1FjXCcrxTIYqY4\
        6u9Lllx42A2cHikaUDYVjYcJy%2BPYXWKkKZksEebsvH6bghzHD2yJZlWtGS3jv%2FooU%2\
        BjHTeTSNOZ27mK2jO%2BtjfpEEC64KFrNNszmgcyfCrrEbGTnYcHsDc8zuATT1qgcPgG6x4\
        O5MWz4Zrng5SSxSr0NtyWVE4sMaVlrP%2FznZgmSISLc54z8ni7pjB0Sj4x1mmceKsVsWoC\
        lGUN%2B9aFfyHcdrCIuBYzIxmgl5WIRpveolatptoi5ZOZ46xpB2qMNT6urVyLbG3GNJjDW\
        R5BJVdL9WXrTAQlDDW1mOAR9Eqond%2FwadD%2BB%2FP8mhdiJQ4GADyUmQSKTUnR3SYv2R\
        b%2FvLoYLjwZgQlDK3pJ0lh8IOKg2j0hjvOrdLZmXjSNuepDCUl5u9BjqkAY%2FnbFERAaH\
        BrrMi1dIcoMasY6xgCLCowLsany2GwzfhfvLTIvzLM54Svg%2Fvd425klm9A%2F2PszJeUO\
        35sWpLoo8zv9gZyA953oQMin5xq7RNWPPc5tyK4G3gqgL21cbIOPxj9Dl1zUUX7Jal4zEJN\
        02w%2BxY009egEaSug1KsiU2WWBfL2BGVuLMZxzi%2FiWv1kgwU%2BxARVEO2FVbn0rzoSn\
        rCHe6e&X-Amz-Signature=76a5148470f122dd7a2000fa4b1b721bdd599b026fd41e76\
        9c8ecd705f156d73&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-08T04:24:01.502Z"
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
UPDATE_TIME: "2025-02-08T03:25:28.052Z"
EXPIRY_TIME: "2025-02-08T04:25:19.004Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QBE3VYUK%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T032519Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGsaCXVzLXdlc3QtMiJIMEYCIQCXJ%2FI8%2Fv2RziG3FsbgXA1d0hGiMivNH2CRePlNhsOMTwIhAOzrChnoB%2F5vRKx2a8zzx4Fjmv3EKoZtaHDibre%2BagICKogECIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxN6LSG74grltMiKk8q3AMqiL1oS8kIhmf0pAp6IHB6ztn786gdx2bZEPN7OdiScLQwUFYhrp61CG18zw1GbQiKiiFp0R2BfhTC%2BFEDkFieapCaOVExoS9mGvuZsHyPsO7j3mBYhhjK5DQaEKNpTBJDFgjHYag3HDaxUd1055qp%2F%2BX0nwltFBrUtG51RfPqUp8GZ9WvqXMc1YQoB8gb6DF4gZhOtpzXM4DKTY%2FOnYS27xNhkZIBswhBzjQhdfBgPLlHsnFtiHU9YVGKBIwdLpWKWm0AfUnMZ5tsV%2FpgQ50RY0I0v9ZARyQxwuPLAIPI%2FPrYG3jzcgJTuoZHOJ%2BoHOr3NUosAPzn08fRB07If8zIUHzTIMPuiDv0UjcLb1U5VBRFoGU28NY0S%2B8vy1XPThlmM8TwWF%2Bqy4NPJbRbGbHamtGg9Y%2B%2Fs66FJ659ELx9ajONTVlSZt0aWjwaBx1M%2BzFir7wD6Jyr%2BATLWcPEZtXLatpVt7Rg18cq2HsAVcrDFyGH7ZESGaHMGszC40kiD13OjyPRGfMMKmLuIY%2FHGiFfqYUF7UMQ%2BNm1logTc9lZXolRPMH9dZ1y0vLQ6swoXAG6MXzrdbGp9D61YK0skw%2BpnYnI9k6SgLZbP%2BKh%2BsI6v0K1Uhn1MUUIHnBjTTCFl5u9BjqkAZxkO4aLYuu2DrVw5NsGkjFfXZioUniqW%2FsmSRz%2BnLif4CaMt%2FXdjOhqGwrdDFcEzdsPetjm8PM7SiVcZRUbiXzWhr%2F2mNzkIJWWyquQBmDoeq5veRyMUoXVFMZ8GcmRTlmv4t5Zu%2F5%2FFsY7qGcSWyCn09UzPw8cJ3MKW9%2FOsqLwOTBqs4yZJwwwc9B8SSumzUAft6KkHdZBeOHTz9XOprnYSl%2FZ&X-Amz-Signature=3d7be28050065d593876b9d2a2e8da1e8a1dd849fe7a4cdcdd4a980630d9cfd8&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QBE3VYUK%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T032519Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGsaCXVzLXdlc3QtMiJIMEYCIQCXJ%2FI8%2Fv2RziG3FsbgXA1d0hGiMivNH2CRePlNhsOMTwIhAOzrChnoB%2F5vRKx2a8zzx4Fjmv3EKoZtaHDibre%2BagICKogECIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxN6LSG74grltMiKk8q3AMqiL1oS8kIhmf0pAp6IHB6ztn786gdx2bZEPN7OdiScLQwUFYhrp61CG18zw1GbQiKiiFp0R2BfhTC%2BFEDkFieapCaOVExoS9mGvuZsHyPsO7j3mBYhhjK5DQaEKNpTBJDFgjHYag3HDaxUd1055qp%2F%2BX0nwltFBrUtG51RfPqUp8GZ9WvqXMc1YQoB8gb6DF4gZhOtpzXM4DKTY%2FOnYS27xNhkZIBswhBzjQhdfBgPLlHsnFtiHU9YVGKBIwdLpWKWm0AfUnMZ5tsV%2FpgQ50RY0I0v9ZARyQxwuPLAIPI%2FPrYG3jzcgJTuoZHOJ%2BoHOr3NUosAPzn08fRB07If8zIUHzTIMPuiDv0UjcLb1U5VBRFoGU28NY0S%2B8vy1XPThlmM8TwWF%2Bqy4NPJbRbGbHamtGg9Y%2B%2Fs66FJ659ELx9ajONTVlSZt0aWjwaBx1M%2BzFir7wD6Jyr%2BATLWcPEZtXLatpVt7Rg18cq2HsAVcrDFyGH7ZESGaHMGszC40kiD13OjyPRGfMMKmLuIY%2FHGiFfqYUF7UMQ%2BNm1logTc9lZXolRPMH9dZ1y0vLQ6swoXAG6MXzrdbGp9D61YK0skw%2BpnYnI9k6SgLZbP%2BKh%2BsI6v0K1Uhn1MUUIHnBjTTCFl5u9BjqkAZxkO4aLYuu2DrVw5NsGkjFfXZioUniqW%2FsmSRz%2BnLif4CaMt%2FXdjOhqGwrdDFcEzdsPetjm8PM7SiVcZRUbiXzWhr%2F2mNzkIJWWyquQBmDoeq5veRyMUoXVFMZ8GcmRTlmv4t5Zu%2F5%2FFsY7qGcSWyCn09UzPw8cJ3MKW9%2FOsqLwOTBqs4yZJwwwc9B8SSumzUAft6KkHdZBeOHTz9XOprnYSl%2FZ&X-Amz-Signature=c9a99ab8282bad99b9af9fd57d30712e5eb4ce27cde1261c60e4e839b411a4c2&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QBE3VYUK%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T032519Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGsaCXVzLXdlc3QtMiJIMEYCIQCXJ%2FI8%2Fv2RziG3FsbgXA1d0hGiMivNH2CRePlNhsOMTwIhAOzrChnoB%2F5vRKx2a8zzx4Fjmv3EKoZtaHDibre%2BagICKogECIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxN6LSG74grltMiKk8q3AMqiL1oS8kIhmf0pAp6IHB6ztn786gdx2bZEPN7OdiScLQwUFYhrp61CG18zw1GbQiKiiFp0R2BfhTC%2BFEDkFieapCaOVExoS9mGvuZsHyPsO7j3mBYhhjK5DQaEKNpTBJDFgjHYag3HDaxUd1055qp%2F%2BX0nwltFBrUtG51RfPqUp8GZ9WvqXMc1YQoB8gb6DF4gZhOtpzXM4DKTY%2FOnYS27xNhkZIBswhBzjQhdfBgPLlHsnFtiHU9YVGKBIwdLpWKWm0AfUnMZ5tsV%2FpgQ50RY0I0v9ZARyQxwuPLAIPI%2FPrYG3jzcgJTuoZHOJ%2BoHOr3NUosAPzn08fRB07If8zIUHzTIMPuiDv0UjcLb1U5VBRFoGU28NY0S%2B8vy1XPThlmM8TwWF%2Bqy4NPJbRbGbHamtGg9Y%2B%2Fs66FJ659ELx9ajONTVlSZt0aWjwaBx1M%2BzFir7wD6Jyr%2BATLWcPEZtXLatpVt7Rg18cq2HsAVcrDFyGH7ZESGaHMGszC40kiD13OjyPRGfMMKmLuIY%2FHGiFfqYUF7UMQ%2BNm1logTc9lZXolRPMH9dZ1y0vLQ6swoXAG6MXzrdbGp9D61YK0skw%2BpnYnI9k6SgLZbP%2BKh%2BsI6v0K1Uhn1MUUIHnBjTTCFl5u9BjqkAZxkO4aLYuu2DrVw5NsGkjFfXZioUniqW%2FsmSRz%2BnLif4CaMt%2FXdjOhqGwrdDFcEzdsPetjm8PM7SiVcZRUbiXzWhr%2F2mNzkIJWWyquQBmDoeq5veRyMUoXVFMZ8GcmRTlmv4t5Zu%2F5%2FFsY7qGcSWyCn09UzPw8cJ3MKW9%2FOsqLwOTBqs4yZJwwwc9B8SSumzUAft6KkHdZBeOHTz9XOprnYSl%2FZ&X-Amz-Signature=3c0d0983b67428a8ac64f9a97840de5c3e9f0ebaa9a4d55f3c8d1c63f874fd8c&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QBE3VYUK%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T032519Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGsaCXVzLXdlc3QtMiJIMEYCIQCXJ%2FI8%2Fv2RziG3FsbgXA1d0hGiMivNH2CRePlNhsOMTwIhAOzrChnoB%2F5vRKx2a8zzx4Fjmv3EKoZtaHDibre%2BagICKogECIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxN6LSG74grltMiKk8q3AMqiL1oS8kIhmf0pAp6IHB6ztn786gdx2bZEPN7OdiScLQwUFYhrp61CG18zw1GbQiKiiFp0R2BfhTC%2BFEDkFieapCaOVExoS9mGvuZsHyPsO7j3mBYhhjK5DQaEKNpTBJDFgjHYag3HDaxUd1055qp%2F%2BX0nwltFBrUtG51RfPqUp8GZ9WvqXMc1YQoB8gb6DF4gZhOtpzXM4DKTY%2FOnYS27xNhkZIBswhBzjQhdfBgPLlHsnFtiHU9YVGKBIwdLpWKWm0AfUnMZ5tsV%2FpgQ50RY0I0v9ZARyQxwuPLAIPI%2FPrYG3jzcgJTuoZHOJ%2BoHOr3NUosAPzn08fRB07If8zIUHzTIMPuiDv0UjcLb1U5VBRFoGU28NY0S%2B8vy1XPThlmM8TwWF%2Bqy4NPJbRbGbHamtGg9Y%2B%2Fs66FJ659ELx9ajONTVlSZt0aWjwaBx1M%2BzFir7wD6Jyr%2BATLWcPEZtXLatpVt7Rg18cq2HsAVcrDFyGH7ZESGaHMGszC40kiD13OjyPRGfMMKmLuIY%2FHGiFfqYUF7UMQ%2BNm1logTc9lZXolRPMH9dZ1y0vLQ6swoXAG6MXzrdbGp9D61YK0skw%2BpnYnI9k6SgLZbP%2BKh%2BsI6v0K1Uhn1MUUIHnBjTTCFl5u9BjqkAZxkO4aLYuu2DrVw5NsGkjFfXZioUniqW%2FsmSRz%2BnLif4CaMt%2FXdjOhqGwrdDFcEzdsPetjm8PM7SiVcZRUbiXzWhr%2F2mNzkIJWWyquQBmDoeq5veRyMUoXVFMZ8GcmRTlmv4t5Zu%2F5%2FFsY7qGcSWyCn09UzPw8cJ3MKW9%2FOsqLwOTBqs4yZJwwwc9B8SSumzUAft6KkHdZBeOHTz9XOprnYSl%2FZ&X-Amz-Signature=d80b6b72b71d90ad92dd6730239fd7d6745dd1d40639fb920fabe32cc7dfa86b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QBE3VYUK%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T032519Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGsaCXVzLXdlc3QtMiJIMEYCIQCXJ%2FI8%2Fv2RziG3FsbgXA1d0hGiMivNH2CRePlNhsOMTwIhAOzrChnoB%2F5vRKx2a8zzx4Fjmv3EKoZtaHDibre%2BagICKogECIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxN6LSG74grltMiKk8q3AMqiL1oS8kIhmf0pAp6IHB6ztn786gdx2bZEPN7OdiScLQwUFYhrp61CG18zw1GbQiKiiFp0R2BfhTC%2BFEDkFieapCaOVExoS9mGvuZsHyPsO7j3mBYhhjK5DQaEKNpTBJDFgjHYag3HDaxUd1055qp%2F%2BX0nwltFBrUtG51RfPqUp8GZ9WvqXMc1YQoB8gb6DF4gZhOtpzXM4DKTY%2FOnYS27xNhkZIBswhBzjQhdfBgPLlHsnFtiHU9YVGKBIwdLpWKWm0AfUnMZ5tsV%2FpgQ50RY0I0v9ZARyQxwuPLAIPI%2FPrYG3jzcgJTuoZHOJ%2BoHOr3NUosAPzn08fRB07If8zIUHzTIMPuiDv0UjcLb1U5VBRFoGU28NY0S%2B8vy1XPThlmM8TwWF%2Bqy4NPJbRbGbHamtGg9Y%2B%2Fs66FJ659ELx9ajONTVlSZt0aWjwaBx1M%2BzFir7wD6Jyr%2BATLWcPEZtXLatpVt7Rg18cq2HsAVcrDFyGH7ZESGaHMGszC40kiD13OjyPRGfMMKmLuIY%2FHGiFfqYUF7UMQ%2BNm1logTc9lZXolRPMH9dZ1y0vLQ6swoXAG6MXzrdbGp9D61YK0skw%2BpnYnI9k6SgLZbP%2BKh%2BsI6v0K1Uhn1MUUIHnBjTTCFl5u9BjqkAZxkO4aLYuu2DrVw5NsGkjFfXZioUniqW%2FsmSRz%2BnLif4CaMt%2FXdjOhqGwrdDFcEzdsPetjm8PM7SiVcZRUbiXzWhr%2F2mNzkIJWWyquQBmDoeq5veRyMUoXVFMZ8GcmRTlmv4t5Zu%2F5%2FFsY7qGcSWyCn09UzPw8cJ3MKW9%2FOsqLwOTBqs4yZJwwwc9B8SSumzUAft6KkHdZBeOHTz9XOprnYSl%2FZ&X-Amz-Signature=281dd6fa722b286bcd4eff3029d2d1a573bd985dc5159204f0b34c305afa2c5f&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TVQJ3BIT%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T032520Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGsaCXVzLXdlc3QtMiJIMEYCIQDIcDfZc%2BuEZ%2BdpweQA0LdYGv1TSU%2FSSzdWzM03vvLAkQIhAJ0Lzynzq88x145qMW8S5evIxekGWHquUu1zmkuL8F%2FjKogECIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzyVR%2FZ3%2FWR78smJ6Qq3ANKIJE60Yk5yJMDf0TNoTw%2Bm3WZghOgyAdgEu7RE2NBHCzTnkD6jyUq%2Bf2Ln4oCkM%2BMoQIs7%2BMo18x5Gj6k%2BXAT1EuZxpmNNbOqZm8amtJaJL852Zy6gl8g3%2BhSPUDhzxOANkF93swfqgOaOF5aTUnjMuEAS2yIKi%2FISJ0ALwz5ZkrKyymh8dAnLz6rdQ3m846NB7HXUV7y4x1PXfZNA8L0z25NbRL%2FsJOrNDUB1whs8MnlHqsVx0W2C%2Frlf9GfvC7Lo2djRKy%2FDIy3WyjONLFdMM%2F3kLC%2BSQSRmUd6AyW6vciBgjqEuE%2BbPMWbeR%2FOFCdTvHsxgXWxebLb6EWJoHdrAlIhiDmWSYC4LknBdBsJmKqLef0v7huOHu8Eh%2BoecoaeG%2BwRI03DdxirRqYaEfkMsXZuDlji6RmEsxRMsmTLboCJ30rO8Z0CnF3QMkc7%2Fs7%2FTDmyKGyZPOHUTOeUhe6mH4ZWzmaeV%2Fgwcpub2YOhHmEul7q7iiBqSq%2FIgM7Mf%2BdU1SVaAQiVwxOBiy7DFhywcL9QlF0iStBaSM%2BBEgZNsvydrqqLvGX9sU3%2B%2FccnH9LBL8AGg9gPXuGjmv69bTNV4B%2FXvWBliZOIvFdAI9EHPJJQkmr5CQUdqVcUEDCLmJu9BjqkAUnzv1rzvvmYEiJ9H3QNY8q7AS4ZtMYWAabPOiKM%2BTHpr%2Fh4htttSiF1hTwHTP%2FpKIW0HHqc2hnptCZc0yYl1B1RHRWgvM2vZg9JSDa%2Fwx%2BOTHOzFJLEGgJw4TC5P4gvAtb0v8xJMtVCoEty0Bmp5lHINTqGRzl2Mdk8Gp7sX6Xzgk5NuzVeBnFAXyOlRSxSPnzADckA4NOLdgYGccXBt7hTZWcO&X-Amz-Signature=329546dfe7ff3895738b22234e568fce16d97342d45957c631b6ebead1204048&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46623Q4ZV4X%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T032521Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGsaCXVzLXdlc3QtMiJIMEYCIQDCVUFqlzKhl2aoKR8PPkJJ1cgyKWaUIclVOvM3EfR6MQIhAOS%2BlImiiw0nI8vba6l2xQeH1O9AbKbxR1c5fEURFw3zKogECIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igw475bQOQeiRGzjGK0q3ANu4009PVgf7p%2BUZzum3RGU5RuNcuynhUwA%2B9B4ay%2BZEvd5SJMhsGuAeljq37WdRnPPkgXUN5Y4cn5bIKw%2BSb3afLZJVE9zKUY3cwVdKsWxQeP443hpdHRmuEhRwQOr9s5ARI6wQIHUOcqVmzYSxtYFenfSPWUyNdSJ%2FgW7et8y%2FSO%2FYm5ByTaKzHjt5Sgnz8YmXuaZ6X6DK%2B4OuoeCU8UbUK7mhwe4mh2WyC6kx7D9tcnNUd9OSkloJzOggAwphPoi6g8Vz1jQXNZ1JZUJrRP3Q42FetNo2%2FjtVySwKser5rRg3nKruIjGlbkfVEfz1amHkgwHgCvUefPvHghNouu%2FJ%2FJQ1Guh8tpLltJUSwF49BT8lJbZh%2FJCVwFJ%2B1ZOW6cga4BTMhYh39r3pZsaUayhQ5IL63O86eqo1rj0foZnIqeymthvCsyfsfeWMHgZCvWwJ5VXBe7bQNRnR8WMDKmso5Yi9rUzZUB8qSQ%2F%2BLuBRyOh6Gx2q63%2F0EHtJSJ%2BMtSUcTR1QDMgLkx1RyA2ET159qenpPg0uRciV%2BLGnvPv%2BV0IGMS9OhChwuUKioB2r8lfigL1WCJTnafABEGVjKJGd4VLZVhNBFIWHkTQBTcGE1%2FZd7GON06ocZrPhzDfl5u9BjqkAeF36ebqtNYSHaX2xTKCGTtjyVFvjJCcsvNFsDxWhrynIA%2B64Mf1H7ORYleor1u1a4DUI04zGtjren24eKOr5OXrvttsBVAdlg7icbeiZiY%2Bt1YW5gOIwybeE963s%2BQ1WdN8KCw%2BBt1F8XdPZ2nbtl%2Fxo9tGKAoJqWt0ETdw1Qvy6AdiqYhjx5yuep9JZ2d7CBpmWB59N2lAtP%2Bzr3aXU%2FtH0U9a&X-Amz-Signature=0e80e2e01bfdd407123ab76f9b2584289fdfe2f0524e77fb55cf59ff7d082c48&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QBE3VYUK%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T032519Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGsaCXVzLXdlc3QtMiJIMEYCIQCXJ%2FI8%2Fv2RziG3FsbgXA1d0hGiMivNH2CRePlNhsOMTwIhAOzrChnoB%2F5vRKx2a8zzx4Fjmv3EKoZtaHDibre%2BagICKogECIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxN6LSG74grltMiKk8q3AMqiL1oS8kIhmf0pAp6IHB6ztn786gdx2bZEPN7OdiScLQwUFYhrp61CG18zw1GbQiKiiFp0R2BfhTC%2BFEDkFieapCaOVExoS9mGvuZsHyPsO7j3mBYhhjK5DQaEKNpTBJDFgjHYag3HDaxUd1055qp%2F%2BX0nwltFBrUtG51RfPqUp8GZ9WvqXMc1YQoB8gb6DF4gZhOtpzXM4DKTY%2FOnYS27xNhkZIBswhBzjQhdfBgPLlHsnFtiHU9YVGKBIwdLpWKWm0AfUnMZ5tsV%2FpgQ50RY0I0v9ZARyQxwuPLAIPI%2FPrYG3jzcgJTuoZHOJ%2BoHOr3NUosAPzn08fRB07If8zIUHzTIMPuiDv0UjcLb1U5VBRFoGU28NY0S%2B8vy1XPThlmM8TwWF%2Bqy4NPJbRbGbHamtGg9Y%2B%2Fs66FJ659ELx9ajONTVlSZt0aWjwaBx1M%2BzFir7wD6Jyr%2BATLWcPEZtXLatpVt7Rg18cq2HsAVcrDFyGH7ZESGaHMGszC40kiD13OjyPRGfMMKmLuIY%2FHGiFfqYUF7UMQ%2BNm1logTc9lZXolRPMH9dZ1y0vLQ6swoXAG6MXzrdbGp9D61YK0skw%2BpnYnI9k6SgLZbP%2BKh%2BsI6v0K1Uhn1MUUIHnBjTTCFl5u9BjqkAZxkO4aLYuu2DrVw5NsGkjFfXZioUniqW%2FsmSRz%2BnLif4CaMt%2FXdjOhqGwrdDFcEzdsPetjm8PM7SiVcZRUbiXzWhr%2F2mNzkIJWWyquQBmDoeq5veRyMUoXVFMZ8GcmRTlmv4t5Zu%2F5%2FFsY7qGcSWyCn09UzPw8cJ3MKW9%2FOsqLwOTBqs4yZJwwwc9B8SSumzUAft6KkHdZBeOHTz9XOprnYSl%2FZ&X-Amz-Signature=85b3adf6e5ac5b25b0db5f73bbc8ebc121d61438173ca1c7624d3728b3e96c80&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QBE3VYUK%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T032519Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGsaCXVzLXdlc3QtMiJIMEYCIQCXJ%2FI8%2Fv2RziG3FsbgXA1d0hGiMivNH2CRePlNhsOMTwIhAOzrChnoB%2F5vRKx2a8zzx4Fjmv3EKoZtaHDibre%2BagICKogECIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxN6LSG74grltMiKk8q3AMqiL1oS8kIhmf0pAp6IHB6ztn786gdx2bZEPN7OdiScLQwUFYhrp61CG18zw1GbQiKiiFp0R2BfhTC%2BFEDkFieapCaOVExoS9mGvuZsHyPsO7j3mBYhhjK5DQaEKNpTBJDFgjHYag3HDaxUd1055qp%2F%2BX0nwltFBrUtG51RfPqUp8GZ9WvqXMc1YQoB8gb6DF4gZhOtpzXM4DKTY%2FOnYS27xNhkZIBswhBzjQhdfBgPLlHsnFtiHU9YVGKBIwdLpWKWm0AfUnMZ5tsV%2FpgQ50RY0I0v9ZARyQxwuPLAIPI%2FPrYG3jzcgJTuoZHOJ%2BoHOr3NUosAPzn08fRB07If8zIUHzTIMPuiDv0UjcLb1U5VBRFoGU28NY0S%2B8vy1XPThlmM8TwWF%2Bqy4NPJbRbGbHamtGg9Y%2B%2Fs66FJ659ELx9ajONTVlSZt0aWjwaBx1M%2BzFir7wD6Jyr%2BATLWcPEZtXLatpVt7Rg18cq2HsAVcrDFyGH7ZESGaHMGszC40kiD13OjyPRGfMMKmLuIY%2FHGiFfqYUF7UMQ%2BNm1logTc9lZXolRPMH9dZ1y0vLQ6swoXAG6MXzrdbGp9D61YK0skw%2BpnYnI9k6SgLZbP%2BKh%2BsI6v0K1Uhn1MUUIHnBjTTCFl5u9BjqkAZxkO4aLYuu2DrVw5NsGkjFfXZioUniqW%2FsmSRz%2BnLif4CaMt%2FXdjOhqGwrdDFcEzdsPetjm8PM7SiVcZRUbiXzWhr%2F2mNzkIJWWyquQBmDoeq5veRyMUoXVFMZ8GcmRTlmv4t5Zu%2F5%2FFsY7qGcSWyCn09UzPw8cJ3MKW9%2FOsqLwOTBqs4yZJwwwc9B8SSumzUAft6KkHdZBeOHTz9XOprnYSl%2FZ&X-Amz-Signature=19dcc9b25e6a2e75c1ecc240c8b2e28a63078cc897904fd41b6b9a9e09a9c5fa&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QBE3VYUK%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T032519Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGsaCXVzLXdlc3QtMiJIMEYCIQCXJ%2FI8%2Fv2RziG3FsbgXA1d0hGiMivNH2CRePlNhsOMTwIhAOzrChnoB%2F5vRKx2a8zzx4Fjmv3EKoZtaHDibre%2BagICKogECIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxN6LSG74grltMiKk8q3AMqiL1oS8kIhmf0pAp6IHB6ztn786gdx2bZEPN7OdiScLQwUFYhrp61CG18zw1GbQiKiiFp0R2BfhTC%2BFEDkFieapCaOVExoS9mGvuZsHyPsO7j3mBYhhjK5DQaEKNpTBJDFgjHYag3HDaxUd1055qp%2F%2BX0nwltFBrUtG51RfPqUp8GZ9WvqXMc1YQoB8gb6DF4gZhOtpzXM4DKTY%2FOnYS27xNhkZIBswhBzjQhdfBgPLlHsnFtiHU9YVGKBIwdLpWKWm0AfUnMZ5tsV%2FpgQ50RY0I0v9ZARyQxwuPLAIPI%2FPrYG3jzcgJTuoZHOJ%2BoHOr3NUosAPzn08fRB07If8zIUHzTIMPuiDv0UjcLb1U5VBRFoGU28NY0S%2B8vy1XPThlmM8TwWF%2Bqy4NPJbRbGbHamtGg9Y%2B%2Fs66FJ659ELx9ajONTVlSZt0aWjwaBx1M%2BzFir7wD6Jyr%2BATLWcPEZtXLatpVt7Rg18cq2HsAVcrDFyGH7ZESGaHMGszC40kiD13OjyPRGfMMKmLuIY%2FHGiFfqYUF7UMQ%2BNm1logTc9lZXolRPMH9dZ1y0vLQ6swoXAG6MXzrdbGp9D61YK0skw%2BpnYnI9k6SgLZbP%2BKh%2BsI6v0K1Uhn1MUUIHnBjTTCFl5u9BjqkAZxkO4aLYuu2DrVw5NsGkjFfXZioUniqW%2FsmSRz%2BnLif4CaMt%2FXdjOhqGwrdDFcEzdsPetjm8PM7SiVcZRUbiXzWhr%2F2mNzkIJWWyquQBmDoeq5veRyMUoXVFMZ8GcmRTlmv4t5Zu%2F5%2FFsY7qGcSWyCn09UzPw8cJ3MKW9%2FOsqLwOTBqs4yZJwwwc9B8SSumzUAft6KkHdZBeOHTz9XOprnYSl%2FZ&X-Amz-Signature=ae70c983958006f6819e7d20e627837994e5749fcbd938854854f08aea0cab0a&X-Amz-SignedHeaders=host&x-id=GetObject)


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

