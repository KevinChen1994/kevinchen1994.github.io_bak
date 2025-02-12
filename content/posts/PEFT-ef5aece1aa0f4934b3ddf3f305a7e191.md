---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466W434OSLT%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250212T092519Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCMnFek4aEADk%2B\
  SWLXb0CHKQvej7kGhls0mV4YiC8uLaAIhAOhdHPzA4FvQhWnv0k%2F5uGQitPKw51%2FNUDW6v0A4\
  %2Fj81KogECOj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igwb%2F%2F3\
  w0Zl3X9yrr1Yq3ANAEATaMSzjFyi00jAzr4Qa%2BSEpi%2BwnpShG23ltXDyEVwu0QcNDwPJv2rsk\
  XNL%2Bg2C1Up3UB2quyCZp5dH2FOQmFlYpI%2B4bNKuDmSz%2Fb%2F23qcQeOzaf0UufwRLiqdrtU\
  0hKOL6EwqeSwOlA4Pp%2Fx4l3Tr7qqzKX526Q4TCypm0G5wenbFy7Gj3QMEnoZ74oDmdf9yaVMW25\
  DF9%2Fkedy%2FBFD0osOzw%2B1Pnw2e2dEvhum9XEl98SbYuKljMEIclTghs7ACifTWxI0w6rEDey\
  tGOX8glKcW2QHsvE1gnyq7E0%2FUsrsSyJQwEyUoyzph6k9SBNTU1H0dz4BkclrSCOSTFXR1uE8D5\
  Rjk%2FwXZhg5ICggA6AAKYcv8s3ks2lcFirzmfLO%2FphX3iajXezKQNiSRQXaXHTQxj0QbeK0sRU\
  scar3hSMqMNkcY%2FOVjCTMvlZ6Wag5csDCiU68z2bJm8dXecQr9MsQiu%2BRuoobs6y5tDK5zybX\
  3mAd%2FAAEbegY%2FfTQo8b5tQhCa%2BpaMAS0g7Q3ejdb0DbyrU6rsnI5s%2Bl%2BP7HGnfIXeC%\
  2FZeBGx5SUacTR5ZpTKTTJ6PQmUbidjGBuQv%2FnIINv0DgMVCYW99CEisOhjcWrKj%2BN2TYKWr5\
  ZKEjD%2BibG9BjqkAbYXrj%2F%2B8z5jgFUPeQsKFnHVOAgpXw3rSjpdqwL6qD%2Br2WnexnNFSIw\
  K1IN0RqydHw9vu8j9yU1pHj%2BzAxaxwF641k5411N%2BEj%2Bs%2FGlrrmhZa2oPogzzqFc%2BOn\
  J8rdUGDXpanrLPEI5HPPpI4ZP3DyCAq9dcPJWFIOeUTrQSyGiedL%2FCXHnomXHdgzRFMaUkxekdv\
  eRLPB7I9m%2BmFZP5%2FuFs3DUb&X-Amz-Signature=a83f1f13a7b6d0837391aa6df2b1aaaa4\
  2d938131a4ea98ed465a10843e9c51c&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466244TF2OM%2F20250212%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250212T092346Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGM\
        EQCIFAjKNJ%2BZ%2FZIYCDFXxjK4RublJOl816Q788w0fkfEMRmAiBw2CG2mCHtXXP2Jw04\
        IDgsothltk8zf2LJ3jxg4PvLBCqIBAjo%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDY\
        zNzQyMzE4MzgwNSIM2bs7EhNgTTuqfJ8IKtwD2YuW3DzvRZXRrmajGYdG3YZvL%2FCl1r1P\
        fBulBlKi2c354djdkzB6VBe67dKn09ivb9rA%2BmicHDqf4c9d7piNJ8ZZCgUfvRtCA1BCo\
        pASg6kKlfbnpovOO6rFBNHBz1rR9DOCpamI8kYUwALG7rP7JdPBNeyp79uI7oFnhc16FWlh\
        81yYzdxcKoPSec%2F%2BryyxA8EphfAMWhfC5%2FEManikKKOvPGMsf3%2B33hOB5%2BDNM\
        hr7xt2BeeJIchhYgrMyNfccoHNshw0nAb6jxmT3oXbm2FtcmORQpxPUfJ%2FOyi7XmK%2BR\
        8bgITWDyzLgjTCxO1rDaEszUmo1y0fYCSApHnyQR4HAkf%2B%2BpZxo73hsKGfPSZ5ALUX8\
        k3DCutoarnBBnwCRpLkMIgP02AtijtCeL166KNOmtqrYe4PH%2FcVqXlFM4j9SSDDOeqs5E\
        Mpu2zGltVAC8yIUA%2BWX6Bh7z7HNLZQgNROubPhl%2Fq12hlsIkFfhCpNfBfYPm5GRvo07\
        8sfDMdYXh%2BWokoxp4XRkaf5V3d4K9f805VQF9g4BFbFR5jgRKEYqKHFpUxAn1%2BJH1sv\
        sAi9Du7Xb%2FZuO7Qpr5M1etawi5wbDjYoeNYUHIqH4sOCvkyu%2FdGHwACm3EbQ3POWAw6\
        oaxvQY6pgE32XuGTcr%2Bw7z%2FwNZ5U6J06fLVRiInExSXF1eg26fe%2F3W%2FJYlGx2MC\
        pklw0T%2BrOGqLfrv9%2Br6yYeE3JX9MQwIJkKq3OW6XNHLHdsfFNCy8jaVHyFVU7MVUYkX\
        9Aijp6Bgz3PxfiDR90YrUt9DBUkdNHOT8c2FlzWk1ttQNqFslqldS1HfxBt8N%2Fgk6V5r6\
        X8ryqKscmkmJ0AvSB8uCahyqRIBUdZOx&X-Amz-Signature=55a8c6230f90a36a201d5e\
        219b3feb1d3a0c7e666445c7e4556a98268ea877ff&X-Amz-SignedHeaders=host&x-i\
        d=GetObject"
      expiry_time: "2025-02-12T10:23:46.027Z"
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
UPDATE_TIME: "2025-02-12T09:25:26.111Z"
EXPIRY_TIME: "2025-02-12T10:25:17.298Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664FP4UWC3%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T092517Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD8%2F8FAwg5Vc1yucToiMzC%2FeXSVDTUlHndKpT8ayjEoGAIgX0cWIBz73Vyv27a%2F7fNGkuVXzA21HlY8fPz3gWhZtDcqiAQI6P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDZ5XcZIkiBgnuBc4SrcA8E%2Bw0%2BJax2AdcbCEUhs%2Bkjefeccq7QA%2F9TmhKmWhkLycOoZkhPIxkX9QogGStpxvw8aokIFDJmQCALOzlqRAB8cPE6OVdkYLmZRpAdrEMadCUWfh6sMHE7DzdU6zHYROfQ8MXLaPB6huqE3hpJcq9c7vIZZETURfEqrnf4X1zokNuzxHZfa1pUIuqzzl0q9wooT0RyBcHFJxKDdjlwG%2F7fm25k9fyGb8q9omAD6HHJzSHjX6BrfLwTJsNC0vMvY0NCcv7hgWko6T02Tk0Go9tHcyuzWBUrIl%2FKGOVoOuZNu89WxOg3YU2QG63KlgiC6Z4%2Fk8aGqKEGin6KF9Ff9X%2BmRlb1QUh%2By2HAWgHVhzwFty7PMqphXfMXP%2BAwmVAWsWdr3qmox0a2saC3CZ6j0KWLZrgeEOeuHZ%2BWqpiZrAt1oZuxmwidUQqU2M9lPQ%2FtJaPD%2FgZI1qJR%2B6ij2297F9vWpCZbYVhws2cybq24fxv72xUXcrNkid%2Fz5SwCIdXI5%2BNQGJLxV7vbPEPuJp0M8eVCTPviN8v2IEv%2FFYVppS8Zj0gvFHeWTJoUtAbYEhXJ%2Bk4kVvMkutztYh3BO3sob4vHiNdtxchRheOLTwXdmkDkxTdYASlBd9A9Y77BWMOuRsb0GOqUBAmBWu9U8wOuhrVVr%2BHBWWJbYFh0PplgsCpVIWv%2B2RQwOkIK4ZsXwBHCvILZtiul8jmfeRJEGAIFRrbrRifrKHb7XbW9d8CFoP8NbpVNDsY5pvhNXU5XTiVP5Q6KQFDr1hGJqlCb%2BIJTNwXNxCB4ergOx%2BeBHPTCKZr2YG8OnPjPjNrV9mdLAMcfzDczuvDJ%2Bz%2FAqGSIi7RG8I9dVMO6U2%2BzTmity&X-Amz-Signature=70c8e5d166f6980f1b4f2b8f1c6f2e0b556b4245ccc9efff4e68d98b82e896a5&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664FP4UWC3%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T092517Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD8%2F8FAwg5Vc1yucToiMzC%2FeXSVDTUlHndKpT8ayjEoGAIgX0cWIBz73Vyv27a%2F7fNGkuVXzA21HlY8fPz3gWhZtDcqiAQI6P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDZ5XcZIkiBgnuBc4SrcA8E%2Bw0%2BJax2AdcbCEUhs%2Bkjefeccq7QA%2F9TmhKmWhkLycOoZkhPIxkX9QogGStpxvw8aokIFDJmQCALOzlqRAB8cPE6OVdkYLmZRpAdrEMadCUWfh6sMHE7DzdU6zHYROfQ8MXLaPB6huqE3hpJcq9c7vIZZETURfEqrnf4X1zokNuzxHZfa1pUIuqzzl0q9wooT0RyBcHFJxKDdjlwG%2F7fm25k9fyGb8q9omAD6HHJzSHjX6BrfLwTJsNC0vMvY0NCcv7hgWko6T02Tk0Go9tHcyuzWBUrIl%2FKGOVoOuZNu89WxOg3YU2QG63KlgiC6Z4%2Fk8aGqKEGin6KF9Ff9X%2BmRlb1QUh%2By2HAWgHVhzwFty7PMqphXfMXP%2BAwmVAWsWdr3qmox0a2saC3CZ6j0KWLZrgeEOeuHZ%2BWqpiZrAt1oZuxmwidUQqU2M9lPQ%2FtJaPD%2FgZI1qJR%2B6ij2297F9vWpCZbYVhws2cybq24fxv72xUXcrNkid%2Fz5SwCIdXI5%2BNQGJLxV7vbPEPuJp0M8eVCTPviN8v2IEv%2FFYVppS8Zj0gvFHeWTJoUtAbYEhXJ%2Bk4kVvMkutztYh3BO3sob4vHiNdtxchRheOLTwXdmkDkxTdYASlBd9A9Y77BWMOuRsb0GOqUBAmBWu9U8wOuhrVVr%2BHBWWJbYFh0PplgsCpVIWv%2B2RQwOkIK4ZsXwBHCvILZtiul8jmfeRJEGAIFRrbrRifrKHb7XbW9d8CFoP8NbpVNDsY5pvhNXU5XTiVP5Q6KQFDr1hGJqlCb%2BIJTNwXNxCB4ergOx%2BeBHPTCKZr2YG8OnPjPjNrV9mdLAMcfzDczuvDJ%2Bz%2FAqGSIi7RG8I9dVMO6U2%2BzTmity&X-Amz-Signature=42ed0cda02b952b23e87bc32abae58fd1c666592891f569c3eac81ef9bb49356&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664FP4UWC3%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T092517Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD8%2F8FAwg5Vc1yucToiMzC%2FeXSVDTUlHndKpT8ayjEoGAIgX0cWIBz73Vyv27a%2F7fNGkuVXzA21HlY8fPz3gWhZtDcqiAQI6P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDZ5XcZIkiBgnuBc4SrcA8E%2Bw0%2BJax2AdcbCEUhs%2Bkjefeccq7QA%2F9TmhKmWhkLycOoZkhPIxkX9QogGStpxvw8aokIFDJmQCALOzlqRAB8cPE6OVdkYLmZRpAdrEMadCUWfh6sMHE7DzdU6zHYROfQ8MXLaPB6huqE3hpJcq9c7vIZZETURfEqrnf4X1zokNuzxHZfa1pUIuqzzl0q9wooT0RyBcHFJxKDdjlwG%2F7fm25k9fyGb8q9omAD6HHJzSHjX6BrfLwTJsNC0vMvY0NCcv7hgWko6T02Tk0Go9tHcyuzWBUrIl%2FKGOVoOuZNu89WxOg3YU2QG63KlgiC6Z4%2Fk8aGqKEGin6KF9Ff9X%2BmRlb1QUh%2By2HAWgHVhzwFty7PMqphXfMXP%2BAwmVAWsWdr3qmox0a2saC3CZ6j0KWLZrgeEOeuHZ%2BWqpiZrAt1oZuxmwidUQqU2M9lPQ%2FtJaPD%2FgZI1qJR%2B6ij2297F9vWpCZbYVhws2cybq24fxv72xUXcrNkid%2Fz5SwCIdXI5%2BNQGJLxV7vbPEPuJp0M8eVCTPviN8v2IEv%2FFYVppS8Zj0gvFHeWTJoUtAbYEhXJ%2Bk4kVvMkutztYh3BO3sob4vHiNdtxchRheOLTwXdmkDkxTdYASlBd9A9Y77BWMOuRsb0GOqUBAmBWu9U8wOuhrVVr%2BHBWWJbYFh0PplgsCpVIWv%2B2RQwOkIK4ZsXwBHCvILZtiul8jmfeRJEGAIFRrbrRifrKHb7XbW9d8CFoP8NbpVNDsY5pvhNXU5XTiVP5Q6KQFDr1hGJqlCb%2BIJTNwXNxCB4ergOx%2BeBHPTCKZr2YG8OnPjPjNrV9mdLAMcfzDczuvDJ%2Bz%2FAqGSIi7RG8I9dVMO6U2%2BzTmity&X-Amz-Signature=b19d64393e45a72d5ec7843c9b21cfbf1904361d1c03ef67d259f15965ad8b2b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664FP4UWC3%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T092517Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD8%2F8FAwg5Vc1yucToiMzC%2FeXSVDTUlHndKpT8ayjEoGAIgX0cWIBz73Vyv27a%2F7fNGkuVXzA21HlY8fPz3gWhZtDcqiAQI6P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDZ5XcZIkiBgnuBc4SrcA8E%2Bw0%2BJax2AdcbCEUhs%2Bkjefeccq7QA%2F9TmhKmWhkLycOoZkhPIxkX9QogGStpxvw8aokIFDJmQCALOzlqRAB8cPE6OVdkYLmZRpAdrEMadCUWfh6sMHE7DzdU6zHYROfQ8MXLaPB6huqE3hpJcq9c7vIZZETURfEqrnf4X1zokNuzxHZfa1pUIuqzzl0q9wooT0RyBcHFJxKDdjlwG%2F7fm25k9fyGb8q9omAD6HHJzSHjX6BrfLwTJsNC0vMvY0NCcv7hgWko6T02Tk0Go9tHcyuzWBUrIl%2FKGOVoOuZNu89WxOg3YU2QG63KlgiC6Z4%2Fk8aGqKEGin6KF9Ff9X%2BmRlb1QUh%2By2HAWgHVhzwFty7PMqphXfMXP%2BAwmVAWsWdr3qmox0a2saC3CZ6j0KWLZrgeEOeuHZ%2BWqpiZrAt1oZuxmwidUQqU2M9lPQ%2FtJaPD%2FgZI1qJR%2B6ij2297F9vWpCZbYVhws2cybq24fxv72xUXcrNkid%2Fz5SwCIdXI5%2BNQGJLxV7vbPEPuJp0M8eVCTPviN8v2IEv%2FFYVppS8Zj0gvFHeWTJoUtAbYEhXJ%2Bk4kVvMkutztYh3BO3sob4vHiNdtxchRheOLTwXdmkDkxTdYASlBd9A9Y77BWMOuRsb0GOqUBAmBWu9U8wOuhrVVr%2BHBWWJbYFh0PplgsCpVIWv%2B2RQwOkIK4ZsXwBHCvILZtiul8jmfeRJEGAIFRrbrRifrKHb7XbW9d8CFoP8NbpVNDsY5pvhNXU5XTiVP5Q6KQFDr1hGJqlCb%2BIJTNwXNxCB4ergOx%2BeBHPTCKZr2YG8OnPjPjNrV9mdLAMcfzDczuvDJ%2Bz%2FAqGSIi7RG8I9dVMO6U2%2BzTmity&X-Amz-Signature=09c07155de507ebf5c0c42781c440b88cbee705c26bff695f5606907d0b5d445&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664FP4UWC3%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T092517Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD8%2F8FAwg5Vc1yucToiMzC%2FeXSVDTUlHndKpT8ayjEoGAIgX0cWIBz73Vyv27a%2F7fNGkuVXzA21HlY8fPz3gWhZtDcqiAQI6P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDZ5XcZIkiBgnuBc4SrcA8E%2Bw0%2BJax2AdcbCEUhs%2Bkjefeccq7QA%2F9TmhKmWhkLycOoZkhPIxkX9QogGStpxvw8aokIFDJmQCALOzlqRAB8cPE6OVdkYLmZRpAdrEMadCUWfh6sMHE7DzdU6zHYROfQ8MXLaPB6huqE3hpJcq9c7vIZZETURfEqrnf4X1zokNuzxHZfa1pUIuqzzl0q9wooT0RyBcHFJxKDdjlwG%2F7fm25k9fyGb8q9omAD6HHJzSHjX6BrfLwTJsNC0vMvY0NCcv7hgWko6T02Tk0Go9tHcyuzWBUrIl%2FKGOVoOuZNu89WxOg3YU2QG63KlgiC6Z4%2Fk8aGqKEGin6KF9Ff9X%2BmRlb1QUh%2By2HAWgHVhzwFty7PMqphXfMXP%2BAwmVAWsWdr3qmox0a2saC3CZ6j0KWLZrgeEOeuHZ%2BWqpiZrAt1oZuxmwidUQqU2M9lPQ%2FtJaPD%2FgZI1qJR%2B6ij2297F9vWpCZbYVhws2cybq24fxv72xUXcrNkid%2Fz5SwCIdXI5%2BNQGJLxV7vbPEPuJp0M8eVCTPviN8v2IEv%2FFYVppS8Zj0gvFHeWTJoUtAbYEhXJ%2Bk4kVvMkutztYh3BO3sob4vHiNdtxchRheOLTwXdmkDkxTdYASlBd9A9Y77BWMOuRsb0GOqUBAmBWu9U8wOuhrVVr%2BHBWWJbYFh0PplgsCpVIWv%2B2RQwOkIK4ZsXwBHCvILZtiul8jmfeRJEGAIFRrbrRifrKHb7XbW9d8CFoP8NbpVNDsY5pvhNXU5XTiVP5Q6KQFDr1hGJqlCb%2BIJTNwXNxCB4ergOx%2BeBHPTCKZr2YG8OnPjPjNrV9mdLAMcfzDczuvDJ%2Bz%2FAqGSIi7RG8I9dVMO6U2%2BzTmity&X-Amz-Signature=892175fd7ba67de3b6100d6bd73eb596b77944e24f3a8327299fbeabf3297f88&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662FJIL4KX%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T092518Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDp7COryhtsMDucDYtJWr0l0Pe04dQ9fEcXwue1Tgx8jAIgJyKZLq%2FDTVd7F4ja2KBlZatGLnT%2BT9T9vjWN6H3QGIsqiAQI6P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDIO1g1rG2N8IvuIjGSrcA%2BdlDQXB7n3CI3b42RzswqUlUeBy4UGsuGJPOzRP%2FPiYHzegYMXfgegZxCGkggPE9nzMfUHJY8ysq47W86ovyOmwbSN6TQyaHaSaS9CflHMD8ME1cZl4z27y6x7D5GkF5eN5Y7wji9xigReikVdxzdubrPIi2Rt%2Fj48eti8NNumj374UlxpWPXuKIfC3x6rC1IrqXOUi7e4Hx2%2FqcPyYjg4ngUCd1SwZhmPjXXByq3a%2B80XbHcFNc%2B%2F0yqglzaC8zIOetff%2FVSqNM7e18Poug%2BcLsmoB4XBRfw655B4eu5gphFRZwEDNu3qnhIgkqTt%2BHiIxZb7RK40yEGkWK1ExKK9E9fu%2BUYO8NTmBVWpUkqsPPlMIn1rRXjHkF6uB4QcGCA8Qt57IrERDhpyHnY6fSNRUuU%2BaTdoW3%2B%2B0ksiAPloMeUGn5grNG1EOmmIguMyNoPLQnd7TpYuxkR%2BF9Ez9nryLDR%2BE6DEx%2BH%2F87upjKbedSYjQNqLEV3YQUEQsb%2BpV%2BFedQ6p9iTyvwg9TTnzKuM9pozpauadPageTri7rElcqWMjK0Iur3FsJiQCpNpH0WC3T2a3YEd8ESjvktj210Q86gNFHAcyBim90cC2ctlJaWJyWBUcgl5vzW6J8MOyUsb0GOqUBTsMSjIlJjYory%2FKG4QcCXhBhJuPTdqoDJQFYelrRLc6YVT%2FpasfL4s9UGxn%2FBvcNNlARwvoLh3bkaMo8DzcAz%2BDNRpakbD3Lifq2Rjw%2BMt%2BuX1CpZF%2Fg9kqlrcADv1CN%2F2y7JLrp9Tvr7IYYUDJzrvT2CztJmEcyYXZzaaI%2F41zjoiglTtnbyKWd%2Fu3tXM90%2FVIorahuUuls8vr104b8NupT6vw2&X-Amz-Signature=a0b0b5a7a0c8f347bfcc4b8daca42e4f52ca1bce2fc388c4450cab05a7099c93&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WYYCWZEA%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T092519Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIHEAFEMYBkfRDLVeoqe3PrY3MzCPx465FP%2BCGPRNNvZRAiEAij9bRXkQPx%2FMEjRNF%2B6kIZJ0hzydw5BdLEDNazmWsFEqiAQI6P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDAdFHKigfsiL%2Fn%2BIICrcA9V%2B48LJvs4HEfxBL6R%2B6N2aNIHnu%2FGPGSTpAQw%2BDzfVASoKb5nmJsOUWToNXjbJc42Y4b0YfgKgDm5N5EkQk6xRE9QlFW4l5fwoQo0po5hVTuBkKOp0JfGX0WfU1MGNj8hcJZvMf93BUy%2BkJGi8v4bTY1oLwz912dHepwQjntzeB7kqxVgBUm2QIvOOEGzprK3V1nPA7iE7ziEgxC8bhVNySoM5ooRNFgTUnDGVBxy3PBIKc%2Bu6yA4WYQViic0g5OBMqBOGfOxbGDreisd7thxaa%2Bv3pk01AExYBZ0HmoYmsm0rqUSqzncjbHzOQORZpnnDoBD6BhH6yRINDhiNHNdCAhFFnfGFBXsemF%2BMDl3TXkkFeE5qq39ImjNrkwwJRB8mvJPle1kL%2FghJ78h2WW8En4xpLgBr%2FValPNzGepa6WAc0KsfAtSbH2M1DgkYc5lWUECJwyrdx5JXG6zrU1NtL0QB2CzrKAojamvF95vbOKWM90Th0R%2BS48187nTqDQi%2Bw5WKoC8tF%2B4aT%2BPAsQK1O6Ws%2Bxanxl8TkMkLutg9E1ZUZ1Bgz0sqmTPLRkVN%2FsrAfjQ7UMgkrWFD31yN5JIqrRl2EAgdffCgEL6aNQ8Y1WjEjlmqcshH6f2Z%2BMNWMsb0GOqUBUTTuHnMK%2Bw%2BYsigbVgAwbRMSRa%2BLdvZktADBwbx%2Fdt9Q%2BC%2B9Csj8VES2BbXiUWc85ATA4Dx95BQXe%2Fo5fa6ycJl93bt07JEkM8fzwfCMqbL0pawwhHvZvPKi1K5oXQAeME1KracqzaNMU4A63m2RbS4ASiTcyA13tmjrBCRBL4fcCZp8wD%2BdmKSr8ezCu94SyGm%2B9EWZZPRaMu1wdPCpVOCP0%2B2U&X-Amz-Signature=a968b5842cabc756ba9846c9744f43ca0b33e4aa52db17067dcf34fa0e5c26ee&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664FP4UWC3%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T092517Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD8%2F8FAwg5Vc1yucToiMzC%2FeXSVDTUlHndKpT8ayjEoGAIgX0cWIBz73Vyv27a%2F7fNGkuVXzA21HlY8fPz3gWhZtDcqiAQI6P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDZ5XcZIkiBgnuBc4SrcA8E%2Bw0%2BJax2AdcbCEUhs%2Bkjefeccq7QA%2F9TmhKmWhkLycOoZkhPIxkX9QogGStpxvw8aokIFDJmQCALOzlqRAB8cPE6OVdkYLmZRpAdrEMadCUWfh6sMHE7DzdU6zHYROfQ8MXLaPB6huqE3hpJcq9c7vIZZETURfEqrnf4X1zokNuzxHZfa1pUIuqzzl0q9wooT0RyBcHFJxKDdjlwG%2F7fm25k9fyGb8q9omAD6HHJzSHjX6BrfLwTJsNC0vMvY0NCcv7hgWko6T02Tk0Go9tHcyuzWBUrIl%2FKGOVoOuZNu89WxOg3YU2QG63KlgiC6Z4%2Fk8aGqKEGin6KF9Ff9X%2BmRlb1QUh%2By2HAWgHVhzwFty7PMqphXfMXP%2BAwmVAWsWdr3qmox0a2saC3CZ6j0KWLZrgeEOeuHZ%2BWqpiZrAt1oZuxmwidUQqU2M9lPQ%2FtJaPD%2FgZI1qJR%2B6ij2297F9vWpCZbYVhws2cybq24fxv72xUXcrNkid%2Fz5SwCIdXI5%2BNQGJLxV7vbPEPuJp0M8eVCTPviN8v2IEv%2FFYVppS8Zj0gvFHeWTJoUtAbYEhXJ%2Bk4kVvMkutztYh3BO3sob4vHiNdtxchRheOLTwXdmkDkxTdYASlBd9A9Y77BWMOuRsb0GOqUBAmBWu9U8wOuhrVVr%2BHBWWJbYFh0PplgsCpVIWv%2B2RQwOkIK4ZsXwBHCvILZtiul8jmfeRJEGAIFRrbrRifrKHb7XbW9d8CFoP8NbpVNDsY5pvhNXU5XTiVP5Q6KQFDr1hGJqlCb%2BIJTNwXNxCB4ergOx%2BeBHPTCKZr2YG8OnPjPjNrV9mdLAMcfzDczuvDJ%2Bz%2FAqGSIi7RG8I9dVMO6U2%2BzTmity&X-Amz-Signature=6dde12fec1f2bcfeab7eaa76ea42d31c3763460a713a500252af8d3b46808851&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664FP4UWC3%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T092517Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD8%2F8FAwg5Vc1yucToiMzC%2FeXSVDTUlHndKpT8ayjEoGAIgX0cWIBz73Vyv27a%2F7fNGkuVXzA21HlY8fPz3gWhZtDcqiAQI6P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDZ5XcZIkiBgnuBc4SrcA8E%2Bw0%2BJax2AdcbCEUhs%2Bkjefeccq7QA%2F9TmhKmWhkLycOoZkhPIxkX9QogGStpxvw8aokIFDJmQCALOzlqRAB8cPE6OVdkYLmZRpAdrEMadCUWfh6sMHE7DzdU6zHYROfQ8MXLaPB6huqE3hpJcq9c7vIZZETURfEqrnf4X1zokNuzxHZfa1pUIuqzzl0q9wooT0RyBcHFJxKDdjlwG%2F7fm25k9fyGb8q9omAD6HHJzSHjX6BrfLwTJsNC0vMvY0NCcv7hgWko6T02Tk0Go9tHcyuzWBUrIl%2FKGOVoOuZNu89WxOg3YU2QG63KlgiC6Z4%2Fk8aGqKEGin6KF9Ff9X%2BmRlb1QUh%2By2HAWgHVhzwFty7PMqphXfMXP%2BAwmVAWsWdr3qmox0a2saC3CZ6j0KWLZrgeEOeuHZ%2BWqpiZrAt1oZuxmwidUQqU2M9lPQ%2FtJaPD%2FgZI1qJR%2B6ij2297F9vWpCZbYVhws2cybq24fxv72xUXcrNkid%2Fz5SwCIdXI5%2BNQGJLxV7vbPEPuJp0M8eVCTPviN8v2IEv%2FFYVppS8Zj0gvFHeWTJoUtAbYEhXJ%2Bk4kVvMkutztYh3BO3sob4vHiNdtxchRheOLTwXdmkDkxTdYASlBd9A9Y77BWMOuRsb0GOqUBAmBWu9U8wOuhrVVr%2BHBWWJbYFh0PplgsCpVIWv%2B2RQwOkIK4ZsXwBHCvILZtiul8jmfeRJEGAIFRrbrRifrKHb7XbW9d8CFoP8NbpVNDsY5pvhNXU5XTiVP5Q6KQFDr1hGJqlCb%2BIJTNwXNxCB4ergOx%2BeBHPTCKZr2YG8OnPjPjNrV9mdLAMcfzDczuvDJ%2Bz%2FAqGSIi7RG8I9dVMO6U2%2BzTmity&X-Amz-Signature=cf63337249bf5f4c5036b91145e30e2a2604c0c793880305ce4481c7d76636f6&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664FP4UWC3%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T092517Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD8%2F8FAwg5Vc1yucToiMzC%2FeXSVDTUlHndKpT8ayjEoGAIgX0cWIBz73Vyv27a%2F7fNGkuVXzA21HlY8fPz3gWhZtDcqiAQI6P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDZ5XcZIkiBgnuBc4SrcA8E%2Bw0%2BJax2AdcbCEUhs%2Bkjefeccq7QA%2F9TmhKmWhkLycOoZkhPIxkX9QogGStpxvw8aokIFDJmQCALOzlqRAB8cPE6OVdkYLmZRpAdrEMadCUWfh6sMHE7DzdU6zHYROfQ8MXLaPB6huqE3hpJcq9c7vIZZETURfEqrnf4X1zokNuzxHZfa1pUIuqzzl0q9wooT0RyBcHFJxKDdjlwG%2F7fm25k9fyGb8q9omAD6HHJzSHjX6BrfLwTJsNC0vMvY0NCcv7hgWko6T02Tk0Go9tHcyuzWBUrIl%2FKGOVoOuZNu89WxOg3YU2QG63KlgiC6Z4%2Fk8aGqKEGin6KF9Ff9X%2BmRlb1QUh%2By2HAWgHVhzwFty7PMqphXfMXP%2BAwmVAWsWdr3qmox0a2saC3CZ6j0KWLZrgeEOeuHZ%2BWqpiZrAt1oZuxmwidUQqU2M9lPQ%2FtJaPD%2FgZI1qJR%2B6ij2297F9vWpCZbYVhws2cybq24fxv72xUXcrNkid%2Fz5SwCIdXI5%2BNQGJLxV7vbPEPuJp0M8eVCTPviN8v2IEv%2FFYVppS8Zj0gvFHeWTJoUtAbYEhXJ%2Bk4kVvMkutztYh3BO3sob4vHiNdtxchRheOLTwXdmkDkxTdYASlBd9A9Y77BWMOuRsb0GOqUBAmBWu9U8wOuhrVVr%2BHBWWJbYFh0PplgsCpVIWv%2B2RQwOkIK4ZsXwBHCvILZtiul8jmfeRJEGAIFRrbrRifrKHb7XbW9d8CFoP8NbpVNDsY5pvhNXU5XTiVP5Q6KQFDr1hGJqlCb%2BIJTNwXNxCB4ergOx%2BeBHPTCKZr2YG8OnPjPjNrV9mdLAMcfzDczuvDJ%2Bz%2FAqGSIi7RG8I9dVMO6U2%2BzTmity&X-Amz-Signature=af7011a92fda49bd7b3aa0663d36c4ee72ef22e3775e819207fb6aeea8d50f8c&X-Amz-SignedHeaders=host&x-id=GetObject)


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

