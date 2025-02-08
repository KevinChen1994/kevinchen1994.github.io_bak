---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4666E2MDPNX%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250208T062943Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEG8aCXVzLXdlc3QtMiJHMEUCIQCaR2%2F2pwBvMl5FUnkhetWB%2BkJq4nmvtzLagB%2BDageYU\
  wIgI95vTv7iRj%2BbQVFt4BXurKH28Y8zFDdw4r4FLabI4wMqiAQIh%2F%2F%2F%2F%2F%2F%2F%2\
  F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCdyd67Cx6iCvaQ9PyrcA5I%2FH%2BBZZhDHZmR%2BT\
  vY5lJsNADqw%2FM9NHeoRfpV%2FVX8D2fJohcMCaUaZv752%2FF6PlZ2G%2F3RBiBYyPUkNMKWSbw\
  7aJQrRifCmckcIZcaXxZZ86c2af7jGNr7Quu0LmHVWhn7Mq5BaCgb2bfYnLxviWdgayEjMAmvfoWP\
  3S7P4bA7tSeCstnGm6MfoaCag8uiJ9yNIj53V3W9o9nti%2B6PlzY9mJUklDvB5WkioP21K2ZDqoO\
  F3kvgTTKvraLvPIDdORv%2BNOssLQX0ibogCYxjf4BbEOIb6j2D%2FbtMVFkcjxQNJYpuZvx2QJ0n\
  MT%2FivbDo5HUFO3gqoUQXvORDyFikQeI5CZtMKTGADu1axhuAsP%2FWh6tUfQICzdDB07qtceJQy\
  cCArz8JXXZzprDiqPXhsFc%2F3U8IXZNRvTliYpO1qG6Ya5wKQZHk99rkc9XctQJhtB1jhpT%2F%2\
  Bp082iE4Ryqc5kIouDprk32FNjjjwME0PsgXrjTk60b%2FDLDuFdc%2FcGNrcBnRPcelJ9WASCsW1\
  akTy%2BBQ%2BKwX923KwtTR4t%2Bg45jl3i367nV%2FyLMSuKehD%2FhLcQcWU%2F%2FlOw3MDpMj\
  mwXRLakkSgqvhKCPc2ZWK2Ih2nasSkLvmkHxdWEJ9PHMHML%2Fwm70GOqUBGSeIXKM5RPhC8WK%2F\
  OdP8MoyYe2JWJBKEQwUNkWaREDVJg%2F77hsNVBNmoRBNHRO8JrHz2p%2Buz6ujVTw6d8Cfhb%2F%\
  2FkBYMBWHp0b3WU1Vr5d9BX9mEzElAV6I2FPFzTPE3MLJbLspmIp5PSpNBgL13CmtdwUKsrR4gYD8\
  vbh1kM1IkPq2tPjeys2LmiQx%2BQqOOpddx2pjwWdILUsRE0bWFFYOEevRR3&X-Amz-Signature=\
  aee0ec4075d40426b72464768360a28cba5bd73834e00c5e89f1fa4412cc8df6&X-Amz-Signed\
  Headers=host&x-id=GetObject"
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
        redential=ASIAZI2LB4666B7RDS54%2F20250208%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250208T062831Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEG8aCXVzLXdlc3QtMiJHMEUCIDJvDjxd20icvfhKb64zl7dGDfcvjLQ\
        SG%2FEtr4pB6VznAiEAs%2BugVGBJP9QZ78UEDI12R07rkcLdF5%2F%2Bs%2Bef%2Bn0Jju\
        gqiAQIiP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDFaehHZGD\
        YZfLgrGgCrcA2GcsEzDsxMnI1jovGgh513PW%2FrOLC5XNDY4PxdAn9jSVmu9Symo6E5XQ3\
        GO3UjZ%2BfTlXCzEx6nq9JVh2xJXPFzaudHbctaV%2FuuHumuRII7o%2BX%2FQdZzcgWNfq\
        sBMW7C5l7iyLtIdqHmFj4Q3TEWE5Dhra11ZQHCpK%2B8UJCBgdO67Atuixpt4Jw%2FHyyeT\
        nPQ3PG%2F%2FxSvYtH1NHbF%2FaUitvlhsEAf3HC%2F%2FR1Y%2BSJ8DErPg9m1rqj%2F2D\
        Kc8VjiQnki5Y0Ux5jtxTJoa7%2Bgg9ICB5ZnKSksRYaqPiB0rrvt0tXSGWfShXj8PDGv4ST\
        uIQ6rsjh8BIyPmZ%2F1yEaRsDbdqclsZFQJTP8NiduUl0%2F75rCZOaHPnBc76HDjEQp9uA\
        3810M0UYC41bFAznXg33mBAZzZmuXsp7tEu4HUEsrftxeui44NaZWRoy34cy00uamqrzWSj\
        iXIEG%2BzNba%2F%2Fv50rzqTKNiWf7f5q9dEzcOP5c2Bz%2FHfTj1Gyl0qxzWQKeI3ggSt\
        v0OD7BmmUDOzfa02SYe63UcRbxh02CXcnggvIqkOL0sCaq9Xay3faXR1xX8M6tHkEoixuUF\
        lWRQT6KxIVpAh1RjWUhwiqBooAUk%2FLq%2BB7PzzLTsc%2BiugALGpHMIPxm70GOqUBy6M\
        LOickWZSegE2A701cUz9FzBKWm1mKmmPwCTXZGqAON0KJYigdz12Plt6reJ9Ev4n7n9VJYl\
        R65jPRiz4Wg7bA%2F03iIomtCBcnXwmPKjf9LeoDGTbJvXR2ExHUMkXesgLyZModIyTtPeS\
        drgu5fFP6VUXm57RWKYlCS4DBVc2di%2F%2FwTvxIee2h2BRK%2Fb8poJhzW2yKDFiP8aNq\
        nwq%2F01Yw7akW&X-Amz-Signature=b0635075c071fdd57b7968d6a4e0adb606863739\
        0990f6c15c7eae1dfa71ccaf&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-08T07:28:31.256Z"
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
UPDATE_TIME: "2025-02-08T06:29:47.249Z"
EXPIRY_TIME: "2025-02-08T07:29:41.118Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SBVJ7BO6%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T062941Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG8aCXVzLXdlc3QtMiJIMEYCIQDcoLaNBMn%2B9RTM3SztK%2BC3m713mtn49Hf%2FAFiImbarWAIhAOLS1BtL58m0zrMms%2Fz6Js6D7xRGj%2FX5PXcwHzIx22U2KogECIj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgznVp6z0ozHvY1%2FspAq3APtXRgl3wb2ThVwYcz7VyNe%2BP7SQt6vm%2FF0CIW%2F2fXDsBDdwULlahE849Wng8nQCvkReuJ69vxiorg9UeVYUbwvcwsbRCE8p8TTwVYRy%2F8sjtLq3s19bwjacMtvthZcPutg9qsodp6E8WY13t6QLcjz1VG3EjYpAkqfKWGxbTrex2SxpjaymUde7bxFKLrIkoNeCLUqHAELP7SKuBGQOP4s0f8Je6DPuCScFO2j%2FfLSpKyhZO9T%2BNHQKW8eLTO3BG1ZP7gS%2BkGz696TnaAjBwENUhEa5NmDGam%2FvzOO4L8aN0p1Hhcsb41Py7ZH9foMf%2FSN5m5Bg%2F1ydu9J220iRhSu6ILeIHtNlN7xxKYL%2BZk38U5f9v%2FQELNneFQq7VVlFZQbsNvPUjDnllChVzwrMXZwRkRvqtAU6BU3vzp15%2BQUxHrGRkCG92Zu6GqSqlb0YqAqqfm3rZJR7tvu0Mr2t7511Q0ebItPaOauiVmAFQCuziLTSPFQ5od4xIYGtErcVaJETBt%2BZ4li39m0XlLAC68sgxD0YgBX0CvydJH7%2Bqdpc3EdkqGnBlRfqq8IhvsBXLXgpxeBy93LwSKIwrH1wKJ6yQrCiylyiC%2B0W2jLPs8wsO4H6TIN6YlGUtV%2FtzCq8Ju9BjqkAcCgHsZ036wVWrz%2BqkB0nvBf59HpRpEbGwswOWEsqs3oy%2BAbFVXA517I8GXTqcqSnBUvB08JjwYZavUYYGf7FTd%2BG%2F%2FwaHrObXMQkryrvI%2Bt%2BfT1MyiojH%2F04FJ40PAhcP4gUrt9ltw%2FvsBtAHTXMu4IePvHKb4m0wttlg36S1ZUMa7cPl9uDoVSLjnyFMnTOts37TxSYEL84raq3G3dvU%2FsZPg%2F&X-Amz-Signature=4489d11ea005aa1ddd34e8a2239b679302bdc01cc49fb4d074400358f3729a96&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SBVJ7BO6%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T062941Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG8aCXVzLXdlc3QtMiJIMEYCIQDcoLaNBMn%2B9RTM3SztK%2BC3m713mtn49Hf%2FAFiImbarWAIhAOLS1BtL58m0zrMms%2Fz6Js6D7xRGj%2FX5PXcwHzIx22U2KogECIj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgznVp6z0ozHvY1%2FspAq3APtXRgl3wb2ThVwYcz7VyNe%2BP7SQt6vm%2FF0CIW%2F2fXDsBDdwULlahE849Wng8nQCvkReuJ69vxiorg9UeVYUbwvcwsbRCE8p8TTwVYRy%2F8sjtLq3s19bwjacMtvthZcPutg9qsodp6E8WY13t6QLcjz1VG3EjYpAkqfKWGxbTrex2SxpjaymUde7bxFKLrIkoNeCLUqHAELP7SKuBGQOP4s0f8Je6DPuCScFO2j%2FfLSpKyhZO9T%2BNHQKW8eLTO3BG1ZP7gS%2BkGz696TnaAjBwENUhEa5NmDGam%2FvzOO4L8aN0p1Hhcsb41Py7ZH9foMf%2FSN5m5Bg%2F1ydu9J220iRhSu6ILeIHtNlN7xxKYL%2BZk38U5f9v%2FQELNneFQq7VVlFZQbsNvPUjDnllChVzwrMXZwRkRvqtAU6BU3vzp15%2BQUxHrGRkCG92Zu6GqSqlb0YqAqqfm3rZJR7tvu0Mr2t7511Q0ebItPaOauiVmAFQCuziLTSPFQ5od4xIYGtErcVaJETBt%2BZ4li39m0XlLAC68sgxD0YgBX0CvydJH7%2Bqdpc3EdkqGnBlRfqq8IhvsBXLXgpxeBy93LwSKIwrH1wKJ6yQrCiylyiC%2B0W2jLPs8wsO4H6TIN6YlGUtV%2FtzCq8Ju9BjqkAcCgHsZ036wVWrz%2BqkB0nvBf59HpRpEbGwswOWEsqs3oy%2BAbFVXA517I8GXTqcqSnBUvB08JjwYZavUYYGf7FTd%2BG%2F%2FwaHrObXMQkryrvI%2Bt%2BfT1MyiojH%2F04FJ40PAhcP4gUrt9ltw%2FvsBtAHTXMu4IePvHKb4m0wttlg36S1ZUMa7cPl9uDoVSLjnyFMnTOts37TxSYEL84raq3G3dvU%2FsZPg%2F&X-Amz-Signature=4b68417d52a94e94defeb442c72245398ffe4d8dace361baed54ab8f265da723&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SBVJ7BO6%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T062941Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG8aCXVzLXdlc3QtMiJIMEYCIQDcoLaNBMn%2B9RTM3SztK%2BC3m713mtn49Hf%2FAFiImbarWAIhAOLS1BtL58m0zrMms%2Fz6Js6D7xRGj%2FX5PXcwHzIx22U2KogECIj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgznVp6z0ozHvY1%2FspAq3APtXRgl3wb2ThVwYcz7VyNe%2BP7SQt6vm%2FF0CIW%2F2fXDsBDdwULlahE849Wng8nQCvkReuJ69vxiorg9UeVYUbwvcwsbRCE8p8TTwVYRy%2F8sjtLq3s19bwjacMtvthZcPutg9qsodp6E8WY13t6QLcjz1VG3EjYpAkqfKWGxbTrex2SxpjaymUde7bxFKLrIkoNeCLUqHAELP7SKuBGQOP4s0f8Je6DPuCScFO2j%2FfLSpKyhZO9T%2BNHQKW8eLTO3BG1ZP7gS%2BkGz696TnaAjBwENUhEa5NmDGam%2FvzOO4L8aN0p1Hhcsb41Py7ZH9foMf%2FSN5m5Bg%2F1ydu9J220iRhSu6ILeIHtNlN7xxKYL%2BZk38U5f9v%2FQELNneFQq7VVlFZQbsNvPUjDnllChVzwrMXZwRkRvqtAU6BU3vzp15%2BQUxHrGRkCG92Zu6GqSqlb0YqAqqfm3rZJR7tvu0Mr2t7511Q0ebItPaOauiVmAFQCuziLTSPFQ5od4xIYGtErcVaJETBt%2BZ4li39m0XlLAC68sgxD0YgBX0CvydJH7%2Bqdpc3EdkqGnBlRfqq8IhvsBXLXgpxeBy93LwSKIwrH1wKJ6yQrCiylyiC%2B0W2jLPs8wsO4H6TIN6YlGUtV%2FtzCq8Ju9BjqkAcCgHsZ036wVWrz%2BqkB0nvBf59HpRpEbGwswOWEsqs3oy%2BAbFVXA517I8GXTqcqSnBUvB08JjwYZavUYYGf7FTd%2BG%2F%2FwaHrObXMQkryrvI%2Bt%2BfT1MyiojH%2F04FJ40PAhcP4gUrt9ltw%2FvsBtAHTXMu4IePvHKb4m0wttlg36S1ZUMa7cPl9uDoVSLjnyFMnTOts37TxSYEL84raq3G3dvU%2FsZPg%2F&X-Amz-Signature=28070f79e3d1b798b3d59d1195a616adfb8ea34cc7e0a273ee4ee42842e0b884&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SBVJ7BO6%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T062941Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG8aCXVzLXdlc3QtMiJIMEYCIQDcoLaNBMn%2B9RTM3SztK%2BC3m713mtn49Hf%2FAFiImbarWAIhAOLS1BtL58m0zrMms%2Fz6Js6D7xRGj%2FX5PXcwHzIx22U2KogECIj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgznVp6z0ozHvY1%2FspAq3APtXRgl3wb2ThVwYcz7VyNe%2BP7SQt6vm%2FF0CIW%2F2fXDsBDdwULlahE849Wng8nQCvkReuJ69vxiorg9UeVYUbwvcwsbRCE8p8TTwVYRy%2F8sjtLq3s19bwjacMtvthZcPutg9qsodp6E8WY13t6QLcjz1VG3EjYpAkqfKWGxbTrex2SxpjaymUde7bxFKLrIkoNeCLUqHAELP7SKuBGQOP4s0f8Je6DPuCScFO2j%2FfLSpKyhZO9T%2BNHQKW8eLTO3BG1ZP7gS%2BkGz696TnaAjBwENUhEa5NmDGam%2FvzOO4L8aN0p1Hhcsb41Py7ZH9foMf%2FSN5m5Bg%2F1ydu9J220iRhSu6ILeIHtNlN7xxKYL%2BZk38U5f9v%2FQELNneFQq7VVlFZQbsNvPUjDnllChVzwrMXZwRkRvqtAU6BU3vzp15%2BQUxHrGRkCG92Zu6GqSqlb0YqAqqfm3rZJR7tvu0Mr2t7511Q0ebItPaOauiVmAFQCuziLTSPFQ5od4xIYGtErcVaJETBt%2BZ4li39m0XlLAC68sgxD0YgBX0CvydJH7%2Bqdpc3EdkqGnBlRfqq8IhvsBXLXgpxeBy93LwSKIwrH1wKJ6yQrCiylyiC%2B0W2jLPs8wsO4H6TIN6YlGUtV%2FtzCq8Ju9BjqkAcCgHsZ036wVWrz%2BqkB0nvBf59HpRpEbGwswOWEsqs3oy%2BAbFVXA517I8GXTqcqSnBUvB08JjwYZavUYYGf7FTd%2BG%2F%2FwaHrObXMQkryrvI%2Bt%2BfT1MyiojH%2F04FJ40PAhcP4gUrt9ltw%2FvsBtAHTXMu4IePvHKb4m0wttlg36S1ZUMa7cPl9uDoVSLjnyFMnTOts37TxSYEL84raq3G3dvU%2FsZPg%2F&X-Amz-Signature=d12a5d020082bedacb04ce389c5e2d64517a2d07856a11c18dffa9e50c361c49&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SBVJ7BO6%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T062941Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG8aCXVzLXdlc3QtMiJIMEYCIQDcoLaNBMn%2B9RTM3SztK%2BC3m713mtn49Hf%2FAFiImbarWAIhAOLS1BtL58m0zrMms%2Fz6Js6D7xRGj%2FX5PXcwHzIx22U2KogECIj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgznVp6z0ozHvY1%2FspAq3APtXRgl3wb2ThVwYcz7VyNe%2BP7SQt6vm%2FF0CIW%2F2fXDsBDdwULlahE849Wng8nQCvkReuJ69vxiorg9UeVYUbwvcwsbRCE8p8TTwVYRy%2F8sjtLq3s19bwjacMtvthZcPutg9qsodp6E8WY13t6QLcjz1VG3EjYpAkqfKWGxbTrex2SxpjaymUde7bxFKLrIkoNeCLUqHAELP7SKuBGQOP4s0f8Je6DPuCScFO2j%2FfLSpKyhZO9T%2BNHQKW8eLTO3BG1ZP7gS%2BkGz696TnaAjBwENUhEa5NmDGam%2FvzOO4L8aN0p1Hhcsb41Py7ZH9foMf%2FSN5m5Bg%2F1ydu9J220iRhSu6ILeIHtNlN7xxKYL%2BZk38U5f9v%2FQELNneFQq7VVlFZQbsNvPUjDnllChVzwrMXZwRkRvqtAU6BU3vzp15%2BQUxHrGRkCG92Zu6GqSqlb0YqAqqfm3rZJR7tvu0Mr2t7511Q0ebItPaOauiVmAFQCuziLTSPFQ5od4xIYGtErcVaJETBt%2BZ4li39m0XlLAC68sgxD0YgBX0CvydJH7%2Bqdpc3EdkqGnBlRfqq8IhvsBXLXgpxeBy93LwSKIwrH1wKJ6yQrCiylyiC%2B0W2jLPs8wsO4H6TIN6YlGUtV%2FtzCq8Ju9BjqkAcCgHsZ036wVWrz%2BqkB0nvBf59HpRpEbGwswOWEsqs3oy%2BAbFVXA517I8GXTqcqSnBUvB08JjwYZavUYYGf7FTd%2BG%2F%2FwaHrObXMQkryrvI%2Bt%2BfT1MyiojH%2F04FJ40PAhcP4gUrt9ltw%2FvsBtAHTXMu4IePvHKb4m0wttlg36S1ZUMa7cPl9uDoVSLjnyFMnTOts37TxSYEL84raq3G3dvU%2FsZPg%2F&X-Amz-Signature=591deb4c276bb91cb3d1777c4259eaa55b6a79b34527d6dc20a850f5595bfaea&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WYUSRZWT%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T062942Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG8aCXVzLXdlc3QtMiJIMEYCIQC%2BPHff1HgwgR0GZe1r6wCSb0NgNb%2BC7VHKO0THu1BwZAIhAPbpsPjgI%2BKLEz4VIqCVYLVjrOjvgZVzCA45VrlfKD4dKogECIf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgykEIRS7wGAy31TwSkq3ANTQoS%2BPz3m58cYe6E9uoJUmkbvPPowUPLTJE%2B2%2Fmcld9rOca7aglCJ38R3NOCIfM1Ibc8BIZ7uPE4NLzOfCjtEntfD2oHxlbts%2BAuBAjU%2BeDockNIvgo7fiZFkLBJwilr6PJ%2FShQBgBmgg5eAXelb8s5jDjDyFVUT4AkjZfPaDEdS0AupjQwBxlqViuQyMLys5MGQ4V3qOa8B7XkwS8r50oqyt9MojR6EY6gA4yNZXzaOs41vTKL6UteBMKl3dcRsHt76c1N6axIGNLTn05xVuL5Iz0npF%2BvWeyft6qDgP7UhBfG4JekdxRm%2BSdqV22pAfeg8esRAIf3F2piIlY7OzFT%2BV3Xct7hptbl%2Bi0b3T8i5fUiQKndPk%2F%2F9y%2BX89PwIrp8CvpiSd1T8IY36igUypdzKBh%2BdLccYu4siN%2BXL7HBX074UTc%2BS9F76xWGNyd4XTrV09dr0hBr9ekUWe0AeysZ4uQuK08E4HB0OFi8nObifvLT87bjBD2Ch7Wqkwo0v2R7lISWNIKWmDlI6%2BOzXdr%2FUQOqlHcpinrdT0XNmHzfa028BmHC8QYXPo7A37mEYEHc%2FE1nmrhGfGxLiOjKvd0YFzj2YokmTOjHLkEeeA6C5MuZPR4e86fK%2FaqzCx8Ju9BjqkAZaIKIqacSvfskdtMdSHV63JcntgT8jV0V8tD867NcfUzfw2%2Fmpfwdbxc9cFzyKsYIUTZIjZmQiLt2L0Oh8hiu62eBtmcPyGtjQDIpP9mu1bznGXqFL4fdhCiPbM0%2BG%2FKVhXDZjcef%2Br8l%2B%2FZHT%2F7DEteLI0EnlojGE0cP0hO6nMpYrwzdGI7AWadyYuc32h992ELNKZd%2F68XDrnVMO1uVH%2BbX2B&X-Amz-Signature=1c03d707f7f2191499eb981767cb251e827716e59c1d48f65d74b28ee7950429&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XX2DX2XQ%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T062943Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG8aCXVzLXdlc3QtMiJIMEYCIQCafoQtSAhN%2FoHpIvjZIlRA%2BPzVr9Z7QY9me6%2BtfWznbwIhANubucRBB56DssmHcmzVXUqc0F05QGU%2BvYMCcrSBcFOcKogECIf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxWfzoXftO02VYEQbsq3APutqODKedyxB9SYTZJw2CLZUC1hzAXfHh6Y5Rk0qI%2FHUy5wxeXVATsrc87JStdFVQgvoWF%2Bs63hRrAhJ2eI5MiMppAQ9sH2SctbzbLk7iezg%2BF01nHEedx0od7Cq%2FULyOeTT7cBMlSG7cBZq240RC7oz9KA7bdlxKYHwYJTBJjuP60lZYDTBvnVg4apwM6JigHXB3QzewTfAA5EhEyInqphBXwUF5HXpYffK7luLSTAW3%2B8%2Bj9JsGAGQXR%2BbUqwrY7UDkypO1%2BMg2DtpGZx0g1HxSn8g%2BDrbFQvdYeo1sAFWwPjjwwZlblNBLuAhv8qnERJOiUBcbQFPqhki0qysZbPg3xWatP1h2aEWck8Cc%2FzkL4qo2HA0uW8daskilnTr57zfVBTmMAI5iWe2qk%2FymyarXmGnaiiDU9Kex2RmV5EOn7t43sSFW%2FJ45Sr4X3I6hzG%2FLCv2QSezGNjGt21frMOmimryEQzn%2FqDhAyhDOKJDNfJVqRgqutHrIpex4K0BD72T2m5eW4hs5efSeesfv6mD3SUXdKwG1iUKsAMt8yvRdECbgrA0ll0jqdzRLXBbnXD9ZwbBsDm468MHj3NYqOlJ%2BtTty7qPirFBYEPqvu5EX7fPL%2F1cvGetz2KDD875u9BjqkASqyOC86KooAk%2FXfzMibeMhH%2FexVYy06JzHTK2kJLw%2B5bGyymtT%2BjxCk3N7CbxlRud3eM%2B3dI%2BmoZNRDxGdkKMGsm5VQAOg2eyMn0E0UGwLxMGYJnUSlG6qFqftmU0BE5V4gZI12%2BCb%2BZSbPZhHywzHILA5z0Qou%2F4asCrjg%2F4okagsfyn3A8%2FoQMvDrXWes3o51I%2FmccpSTcUMvDWdBx59acyil&X-Amz-Signature=097125a2eb49a93ba29e15de5456805c348d754e8db782bb14c174cb47b35fde&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SBVJ7BO6%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T062941Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG8aCXVzLXdlc3QtMiJIMEYCIQDcoLaNBMn%2B9RTM3SztK%2BC3m713mtn49Hf%2FAFiImbarWAIhAOLS1BtL58m0zrMms%2Fz6Js6D7xRGj%2FX5PXcwHzIx22U2KogECIj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgznVp6z0ozHvY1%2FspAq3APtXRgl3wb2ThVwYcz7VyNe%2BP7SQt6vm%2FF0CIW%2F2fXDsBDdwULlahE849Wng8nQCvkReuJ69vxiorg9UeVYUbwvcwsbRCE8p8TTwVYRy%2F8sjtLq3s19bwjacMtvthZcPutg9qsodp6E8WY13t6QLcjz1VG3EjYpAkqfKWGxbTrex2SxpjaymUde7bxFKLrIkoNeCLUqHAELP7SKuBGQOP4s0f8Je6DPuCScFO2j%2FfLSpKyhZO9T%2BNHQKW8eLTO3BG1ZP7gS%2BkGz696TnaAjBwENUhEa5NmDGam%2FvzOO4L8aN0p1Hhcsb41Py7ZH9foMf%2FSN5m5Bg%2F1ydu9J220iRhSu6ILeIHtNlN7xxKYL%2BZk38U5f9v%2FQELNneFQq7VVlFZQbsNvPUjDnllChVzwrMXZwRkRvqtAU6BU3vzp15%2BQUxHrGRkCG92Zu6GqSqlb0YqAqqfm3rZJR7tvu0Mr2t7511Q0ebItPaOauiVmAFQCuziLTSPFQ5od4xIYGtErcVaJETBt%2BZ4li39m0XlLAC68sgxD0YgBX0CvydJH7%2Bqdpc3EdkqGnBlRfqq8IhvsBXLXgpxeBy93LwSKIwrH1wKJ6yQrCiylyiC%2B0W2jLPs8wsO4H6TIN6YlGUtV%2FtzCq8Ju9BjqkAcCgHsZ036wVWrz%2BqkB0nvBf59HpRpEbGwswOWEsqs3oy%2BAbFVXA517I8GXTqcqSnBUvB08JjwYZavUYYGf7FTd%2BG%2F%2FwaHrObXMQkryrvI%2Bt%2BfT1MyiojH%2F04FJ40PAhcP4gUrt9ltw%2FvsBtAHTXMu4IePvHKb4m0wttlg36S1ZUMa7cPl9uDoVSLjnyFMnTOts37TxSYEL84raq3G3dvU%2FsZPg%2F&X-Amz-Signature=4ec0255798cc8beaacb026863e086113467863037101f93f8879cf5edc140bc9&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SBVJ7BO6%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T062941Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG8aCXVzLXdlc3QtMiJIMEYCIQDcoLaNBMn%2B9RTM3SztK%2BC3m713mtn49Hf%2FAFiImbarWAIhAOLS1BtL58m0zrMms%2Fz6Js6D7xRGj%2FX5PXcwHzIx22U2KogECIj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgznVp6z0ozHvY1%2FspAq3APtXRgl3wb2ThVwYcz7VyNe%2BP7SQt6vm%2FF0CIW%2F2fXDsBDdwULlahE849Wng8nQCvkReuJ69vxiorg9UeVYUbwvcwsbRCE8p8TTwVYRy%2F8sjtLq3s19bwjacMtvthZcPutg9qsodp6E8WY13t6QLcjz1VG3EjYpAkqfKWGxbTrex2SxpjaymUde7bxFKLrIkoNeCLUqHAELP7SKuBGQOP4s0f8Je6DPuCScFO2j%2FfLSpKyhZO9T%2BNHQKW8eLTO3BG1ZP7gS%2BkGz696TnaAjBwENUhEa5NmDGam%2FvzOO4L8aN0p1Hhcsb41Py7ZH9foMf%2FSN5m5Bg%2F1ydu9J220iRhSu6ILeIHtNlN7xxKYL%2BZk38U5f9v%2FQELNneFQq7VVlFZQbsNvPUjDnllChVzwrMXZwRkRvqtAU6BU3vzp15%2BQUxHrGRkCG92Zu6GqSqlb0YqAqqfm3rZJR7tvu0Mr2t7511Q0ebItPaOauiVmAFQCuziLTSPFQ5od4xIYGtErcVaJETBt%2BZ4li39m0XlLAC68sgxD0YgBX0CvydJH7%2Bqdpc3EdkqGnBlRfqq8IhvsBXLXgpxeBy93LwSKIwrH1wKJ6yQrCiylyiC%2B0W2jLPs8wsO4H6TIN6YlGUtV%2FtzCq8Ju9BjqkAcCgHsZ036wVWrz%2BqkB0nvBf59HpRpEbGwswOWEsqs3oy%2BAbFVXA517I8GXTqcqSnBUvB08JjwYZavUYYGf7FTd%2BG%2F%2FwaHrObXMQkryrvI%2Bt%2BfT1MyiojH%2F04FJ40PAhcP4gUrt9ltw%2FvsBtAHTXMu4IePvHKb4m0wttlg36S1ZUMa7cPl9uDoVSLjnyFMnTOts37TxSYEL84raq3G3dvU%2FsZPg%2F&X-Amz-Signature=10063c1e3e8c8a65ccb0db8d9699077d188a8684b549fbb7e51edcd8b2b2e0c0&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SBVJ7BO6%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T062941Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG8aCXVzLXdlc3QtMiJIMEYCIQDcoLaNBMn%2B9RTM3SztK%2BC3m713mtn49Hf%2FAFiImbarWAIhAOLS1BtL58m0zrMms%2Fz6Js6D7xRGj%2FX5PXcwHzIx22U2KogECIj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgznVp6z0ozHvY1%2FspAq3APtXRgl3wb2ThVwYcz7VyNe%2BP7SQt6vm%2FF0CIW%2F2fXDsBDdwULlahE849Wng8nQCvkReuJ69vxiorg9UeVYUbwvcwsbRCE8p8TTwVYRy%2F8sjtLq3s19bwjacMtvthZcPutg9qsodp6E8WY13t6QLcjz1VG3EjYpAkqfKWGxbTrex2SxpjaymUde7bxFKLrIkoNeCLUqHAELP7SKuBGQOP4s0f8Je6DPuCScFO2j%2FfLSpKyhZO9T%2BNHQKW8eLTO3BG1ZP7gS%2BkGz696TnaAjBwENUhEa5NmDGam%2FvzOO4L8aN0p1Hhcsb41Py7ZH9foMf%2FSN5m5Bg%2F1ydu9J220iRhSu6ILeIHtNlN7xxKYL%2BZk38U5f9v%2FQELNneFQq7VVlFZQbsNvPUjDnllChVzwrMXZwRkRvqtAU6BU3vzp15%2BQUxHrGRkCG92Zu6GqSqlb0YqAqqfm3rZJR7tvu0Mr2t7511Q0ebItPaOauiVmAFQCuziLTSPFQ5od4xIYGtErcVaJETBt%2BZ4li39m0XlLAC68sgxD0YgBX0CvydJH7%2Bqdpc3EdkqGnBlRfqq8IhvsBXLXgpxeBy93LwSKIwrH1wKJ6yQrCiylyiC%2B0W2jLPs8wsO4H6TIN6YlGUtV%2FtzCq8Ju9BjqkAcCgHsZ036wVWrz%2BqkB0nvBf59HpRpEbGwswOWEsqs3oy%2BAbFVXA517I8GXTqcqSnBUvB08JjwYZavUYYGf7FTd%2BG%2F%2FwaHrObXMQkryrvI%2Bt%2BfT1MyiojH%2F04FJ40PAhcP4gUrt9ltw%2FvsBtAHTXMu4IePvHKb4m0wttlg36S1ZUMa7cPl9uDoVSLjnyFMnTOts37TxSYEL84raq3G3dvU%2FsZPg%2F&X-Amz-Signature=95291fac866f3857496b5fb31d068c2c4fc639582584e67bc86fb8aff3b41909&X-Amz-SignedHeaders=host&x-id=GetObject)


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

