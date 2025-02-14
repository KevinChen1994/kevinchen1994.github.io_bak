---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4664U7Q6ROT%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250214T063219Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDMtdfNutdG76zQX\
  XgKy8XP%2FJe0w%2FiRXVIS%2FE7wmC7iEgIhAJyeh5zIaTKnPTSVOslhjeYECpAQ93IDL6ZcXege\
  Z3V4Kv8DCCcQABoMNjM3NDIzMTgzODA1IgzKnw5uXUuVWzysrREq3ANgRIkptlKO01w0bKNWK8xZ%\
  2BpCxiYD9u8DSdgQZAWPzaNwoBmFRbwrQA34%2FeQm%2B9zAm5UzXU%2FK40xKrhDJBlnJwsSkwgO\
  TBUYR6Af%2FNYUJmu4YgLhCZblJMJQ4sACwerySjkx%2BxzGfXw4Igqv3duDMzOdIU3LY0nIm4d%2\
  B3f9NbEXvznWqa0dP1%2B%2F93RxV1rFB3%2Bj%2B1EcP6HS%2BoSoCtVjhVXeAJCQVCROsyLiQ7F\
  SunnLCjsncI0pGLAptG4yngZgk6SA4orM8GNvtp8hUK021TtSqLCdkTndpd9rgnxwIgWOiguw6UZK\
  iY3G%2BJhkerVOH7imA%2BUoN2HWgH6bY5KHiYnqw5p%2FGoPvONLagV6eFK4WbSXIF5j%2Bu1ZN8\
  pxLG1xRoDGQrxBJTsRXwDUQ%2BsMjn4sRTCECr0iWz%2F2DNZARqkS9eH6l7MlfjY52Hmt0Ra694N\
  tra0AOpG6dRM%2Be0GES1VmEjXNHAxSaRqecTbXZIJugIGtreLQNGB5xhTLyst17hq8beVVXr1kmp\
  %2F%2FCYy35G4fNkLAS0ZOUe%2F2sVmlAgFQeLRe8CxC4bUIW%2FtkR0zIc5uMzLK6tleAweMu7I%\
  2F13GBjD%2FYuSlIvRmtI%2FLrbjInzC%2FLWM9bdF5Nl5w9oNzC6wbu9BjqkAZVGuLHebmy0zP4f\
  XJkm8c8NE3wcm5kjv8nmO8jERRy47K%2BMR1zg8VI8Q8YPvw8xvaRnu%2FnHsk%2FZyWqfbszwn%2\
  FIjaxDcZzuYYv3UBgHQ5RFZ1uUw9YF%2Fr5y%2BdNcBkauR4dFdV0AlV3s6ji7G60CMSuOjeqTeoW\
  ZkESwCzUYu8uh7bDYe6VKYVVW60KjYdyEneWUr1d5m0WnygEwkqAN4I7EKg6ZT&X-Amz-Signatur\
  e=7da3c9aa851ce89c845e663b4eed231b52676735834c8e646f5bbf27722953ff&X-Amz-Sign\
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
        redential=ASIAZI2LB466VOVIH63R%2F20250214%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250214T063045Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIM\
        EYCIQCNhZn8DHRCD1GJNMPW%2FUiifAccJ6v5307zravAYu9RNgIhAJqXy2aTUgqezfnbfB\
        ONEDPvokm%2FkFcr0fJMjGZ%2BrnM7Kv8DCCcQABoMNjM3NDIzMTgzODA1IgzVKiEJ2407J\
        A1qI%2B8q3ANfjpd3BoXwfmJqRDcBwtrKV%2BAGmhjvzFCZGaVTC8xLoYvgXyIyAFwrm%2B\
        4p%2BrBQuumpN%2Fm3Qv65OgYsgpeQY%2B4O8nFYOxEogMpo5c8e0G8FFibd7UpMUnfm53P\
        R%2F1ho31hObseyhGLpwOMiDuLCfW9Jf0s6alS%2F5BDGLyW15mcWV2HFl18Pk43XZOqVWQ\
        lSdf3NVxbHqtTbEoKxUqK2pbaeQSEAXH%2F6pXJLlO4hMJebK5qyTx3nUWCDMdJKMnh0V8H\
        KCPP3KMgq6jYa9IveUlpAlg2nOP4AFR1JUQyMJRP8ki4ttGGlJrQy0CxpXB7vPEOHWC6ML%\
        2BQ09%2BCY5tQhmeZmuDvStOi4putYv01dqKklPs8K3H%2Bg1%2Foi9NgbZAoi1l1yViRDI\
        uPhnc4Cv4l53ZP8i%2BXtg8DHdPCBPpT5JcdKFqDTmLVhFc3542KwzY%2Bo%2B8CeOUDbaW\
        MuFGthNmKLWFNfxms%2BH6qs823mn74OP5i0HssQw%2B8G3bUzHYP%2BAC8E%2BofLUdhsK\
        UG9KvjPGoRAXBoXDBs%2FkS45GNhoahEfBa9CMzuAx6q6UAga1XtFG63dSO3HDLkkOwlEtU\
        2ZGW0imEnmgKW9G%2Fb4Gw7g2qbmFrqTs2%2BapXKTZK%2FyysHciTCuwbu9BjqkAe786gp\
        vzuwJSa8W9X7dg9HKfkcDDLaVW4Ilupmi2wAx1HUi5D31FOPJlxH1SlBYOUE2TsST%2B%2B\
        JEObpcci59FLfQ7DYul2AO7DselGAfC5sJE%2F8ku%2BSEuGBjkhloUde2A2xRxWEoCFqrd\
        WmXeaQc1HwvUOGQT5o9QGeYdcoYEnNNYHxo8Au01SLATR7ky5OMm4JODxp5mLBD6RD3o0sJ\
        fxXqIMLv&X-Amz-Signature=66420ae10c3bb6ba3200bc744ecef18a05a6d51a057a89\
        7ba91b3197835a802e&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-14T07:30:45.329Z"
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
UPDATE_TIME: "2025-02-14T06:32:26.251Z"
EXPIRY_TIME: "2025-02-14T07:32:17.259Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YS5EJEQS%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T063217Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCFy65CuYpUz6ON%2BBsTCUmUHKnHiNAQ0vtG7acVGKoqKQIhAL9a1cYL7GoRIq%2FQ9zb3%2B5orVGrDIB5XTHJjLgGK2vfSKv8DCCcQABoMNjM3NDIzMTgzODA1IgzGjtXUsj6z6pVaUFMq3AOaq2JxdjHi0tkdnpl341TV7SITTEzflDxht7VTH75bcYepCXJtK7QQGdxXEHJ1%2FNBFUcEIf%2BMQp107aw5xCQ3TOOuHVtf7Tf03McnYAjuWXQfcALdpGumE5E6233QpaKRSUFm9D2IvQRAwljTEpBuqorIMBd8UPjaPndsqGxTHR0ri2S7PwHX4b%2FlXzr7BmRjk2Nu85gxzplyxzjDMB%2FsSaV6v3slhQZbyWpYmsJig8RBhHnK%2BJx1GxXiARKZChEFm70gIXZhS8HujTrJNcEBhOol78vW2djlmzaPHxEMFOk1QMfhuEZuIdC3%2BFTJkeSR3krh7SzWDVkphAhLr1uRpsUOKaDe6sI20ChHzM5Wk82Vy0LuJ3PbD0TeNCz2876hAObk0uD60A6Y0keel4pyXioynRkEqTHH7UD8z8CuiObzWuh78275wiSWwpQF9jY0q4Mj6pWH%2FgiAcgM5Fc5k85d94pLkPA64xc28o1ZRrf%2BUyPUUkDG36Vp59bfa1iR8xujVX6EZcWakTzmh4RuoGlsynN%2BI%2BqDfjhbnqjeFYOpG%2BYlD0%2FedR4GyC1zjMKODSll3Cvjdt2A0glu5eTqwSKIEmp9XEZmYmREkkp2nEOnPLyrk77YFwq%2Fl1CzCswbu9BjqkAYCvcTUuOhr3LDwnr9nDVLKyn8sdb6g45T0C7FhfWQqPu4fwCzyTPAkuLL21D2%2FfdCYDxW7qhY9%2FrC3JZY%2FSHvU4qUR6yWD1Oa1bZXGxEKVfWmdPqCuMMd3A81%2F1VTeqBmPZGVzSx%2BgrdrA4rIuwyQcquUxIJtmiMzUeFJ0uYSC0qb1Alvyn6pRoBI%2FKIuU5cIDFsEvi4MPFYA8i6SVQWI2DrmUV&X-Amz-Signature=d1dbaa1579b412d537bcb2c1a7e67bd6fdf2eb833af6de6fc17be5f6b5ad480b&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YS5EJEQS%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T063217Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCFy65CuYpUz6ON%2BBsTCUmUHKnHiNAQ0vtG7acVGKoqKQIhAL9a1cYL7GoRIq%2FQ9zb3%2B5orVGrDIB5XTHJjLgGK2vfSKv8DCCcQABoMNjM3NDIzMTgzODA1IgzGjtXUsj6z6pVaUFMq3AOaq2JxdjHi0tkdnpl341TV7SITTEzflDxht7VTH75bcYepCXJtK7QQGdxXEHJ1%2FNBFUcEIf%2BMQp107aw5xCQ3TOOuHVtf7Tf03McnYAjuWXQfcALdpGumE5E6233QpaKRSUFm9D2IvQRAwljTEpBuqorIMBd8UPjaPndsqGxTHR0ri2S7PwHX4b%2FlXzr7BmRjk2Nu85gxzplyxzjDMB%2FsSaV6v3slhQZbyWpYmsJig8RBhHnK%2BJx1GxXiARKZChEFm70gIXZhS8HujTrJNcEBhOol78vW2djlmzaPHxEMFOk1QMfhuEZuIdC3%2BFTJkeSR3krh7SzWDVkphAhLr1uRpsUOKaDe6sI20ChHzM5Wk82Vy0LuJ3PbD0TeNCz2876hAObk0uD60A6Y0keel4pyXioynRkEqTHH7UD8z8CuiObzWuh78275wiSWwpQF9jY0q4Mj6pWH%2FgiAcgM5Fc5k85d94pLkPA64xc28o1ZRrf%2BUyPUUkDG36Vp59bfa1iR8xujVX6EZcWakTzmh4RuoGlsynN%2BI%2BqDfjhbnqjeFYOpG%2BYlD0%2FedR4GyC1zjMKODSll3Cvjdt2A0glu5eTqwSKIEmp9XEZmYmREkkp2nEOnPLyrk77YFwq%2Fl1CzCswbu9BjqkAYCvcTUuOhr3LDwnr9nDVLKyn8sdb6g45T0C7FhfWQqPu4fwCzyTPAkuLL21D2%2FfdCYDxW7qhY9%2FrC3JZY%2FSHvU4qUR6yWD1Oa1bZXGxEKVfWmdPqCuMMd3A81%2F1VTeqBmPZGVzSx%2BgrdrA4rIuwyQcquUxIJtmiMzUeFJ0uYSC0qb1Alvyn6pRoBI%2FKIuU5cIDFsEvi4MPFYA8i6SVQWI2DrmUV&X-Amz-Signature=3c5ee355a38d55867d3acfbc9fe1f611f2dc65abafa5c70860efa88ccf4a4572&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YS5EJEQS%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T063217Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCFy65CuYpUz6ON%2BBsTCUmUHKnHiNAQ0vtG7acVGKoqKQIhAL9a1cYL7GoRIq%2FQ9zb3%2B5orVGrDIB5XTHJjLgGK2vfSKv8DCCcQABoMNjM3NDIzMTgzODA1IgzGjtXUsj6z6pVaUFMq3AOaq2JxdjHi0tkdnpl341TV7SITTEzflDxht7VTH75bcYepCXJtK7QQGdxXEHJ1%2FNBFUcEIf%2BMQp107aw5xCQ3TOOuHVtf7Tf03McnYAjuWXQfcALdpGumE5E6233QpaKRSUFm9D2IvQRAwljTEpBuqorIMBd8UPjaPndsqGxTHR0ri2S7PwHX4b%2FlXzr7BmRjk2Nu85gxzplyxzjDMB%2FsSaV6v3slhQZbyWpYmsJig8RBhHnK%2BJx1GxXiARKZChEFm70gIXZhS8HujTrJNcEBhOol78vW2djlmzaPHxEMFOk1QMfhuEZuIdC3%2BFTJkeSR3krh7SzWDVkphAhLr1uRpsUOKaDe6sI20ChHzM5Wk82Vy0LuJ3PbD0TeNCz2876hAObk0uD60A6Y0keel4pyXioynRkEqTHH7UD8z8CuiObzWuh78275wiSWwpQF9jY0q4Mj6pWH%2FgiAcgM5Fc5k85d94pLkPA64xc28o1ZRrf%2BUyPUUkDG36Vp59bfa1iR8xujVX6EZcWakTzmh4RuoGlsynN%2BI%2BqDfjhbnqjeFYOpG%2BYlD0%2FedR4GyC1zjMKODSll3Cvjdt2A0glu5eTqwSKIEmp9XEZmYmREkkp2nEOnPLyrk77YFwq%2Fl1CzCswbu9BjqkAYCvcTUuOhr3LDwnr9nDVLKyn8sdb6g45T0C7FhfWQqPu4fwCzyTPAkuLL21D2%2FfdCYDxW7qhY9%2FrC3JZY%2FSHvU4qUR6yWD1Oa1bZXGxEKVfWmdPqCuMMd3A81%2F1VTeqBmPZGVzSx%2BgrdrA4rIuwyQcquUxIJtmiMzUeFJ0uYSC0qb1Alvyn6pRoBI%2FKIuU5cIDFsEvi4MPFYA8i6SVQWI2DrmUV&X-Amz-Signature=8e5001fb1d8582579971a792be124e516d0401a73fe0aa71f32107376f386cdb&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YS5EJEQS%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T063217Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCFy65CuYpUz6ON%2BBsTCUmUHKnHiNAQ0vtG7acVGKoqKQIhAL9a1cYL7GoRIq%2FQ9zb3%2B5orVGrDIB5XTHJjLgGK2vfSKv8DCCcQABoMNjM3NDIzMTgzODA1IgzGjtXUsj6z6pVaUFMq3AOaq2JxdjHi0tkdnpl341TV7SITTEzflDxht7VTH75bcYepCXJtK7QQGdxXEHJ1%2FNBFUcEIf%2BMQp107aw5xCQ3TOOuHVtf7Tf03McnYAjuWXQfcALdpGumE5E6233QpaKRSUFm9D2IvQRAwljTEpBuqorIMBd8UPjaPndsqGxTHR0ri2S7PwHX4b%2FlXzr7BmRjk2Nu85gxzplyxzjDMB%2FsSaV6v3slhQZbyWpYmsJig8RBhHnK%2BJx1GxXiARKZChEFm70gIXZhS8HujTrJNcEBhOol78vW2djlmzaPHxEMFOk1QMfhuEZuIdC3%2BFTJkeSR3krh7SzWDVkphAhLr1uRpsUOKaDe6sI20ChHzM5Wk82Vy0LuJ3PbD0TeNCz2876hAObk0uD60A6Y0keel4pyXioynRkEqTHH7UD8z8CuiObzWuh78275wiSWwpQF9jY0q4Mj6pWH%2FgiAcgM5Fc5k85d94pLkPA64xc28o1ZRrf%2BUyPUUkDG36Vp59bfa1iR8xujVX6EZcWakTzmh4RuoGlsynN%2BI%2BqDfjhbnqjeFYOpG%2BYlD0%2FedR4GyC1zjMKODSll3Cvjdt2A0glu5eTqwSKIEmp9XEZmYmREkkp2nEOnPLyrk77YFwq%2Fl1CzCswbu9BjqkAYCvcTUuOhr3LDwnr9nDVLKyn8sdb6g45T0C7FhfWQqPu4fwCzyTPAkuLL21D2%2FfdCYDxW7qhY9%2FrC3JZY%2FSHvU4qUR6yWD1Oa1bZXGxEKVfWmdPqCuMMd3A81%2F1VTeqBmPZGVzSx%2BgrdrA4rIuwyQcquUxIJtmiMzUeFJ0uYSC0qb1Alvyn6pRoBI%2FKIuU5cIDFsEvi4MPFYA8i6SVQWI2DrmUV&X-Amz-Signature=233fa2ba59b618d2deb7f972256342b8bde2ab680ddc51f22e488db8812840d0&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YS5EJEQS%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T063217Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCFy65CuYpUz6ON%2BBsTCUmUHKnHiNAQ0vtG7acVGKoqKQIhAL9a1cYL7GoRIq%2FQ9zb3%2B5orVGrDIB5XTHJjLgGK2vfSKv8DCCcQABoMNjM3NDIzMTgzODA1IgzGjtXUsj6z6pVaUFMq3AOaq2JxdjHi0tkdnpl341TV7SITTEzflDxht7VTH75bcYepCXJtK7QQGdxXEHJ1%2FNBFUcEIf%2BMQp107aw5xCQ3TOOuHVtf7Tf03McnYAjuWXQfcALdpGumE5E6233QpaKRSUFm9D2IvQRAwljTEpBuqorIMBd8UPjaPndsqGxTHR0ri2S7PwHX4b%2FlXzr7BmRjk2Nu85gxzplyxzjDMB%2FsSaV6v3slhQZbyWpYmsJig8RBhHnK%2BJx1GxXiARKZChEFm70gIXZhS8HujTrJNcEBhOol78vW2djlmzaPHxEMFOk1QMfhuEZuIdC3%2BFTJkeSR3krh7SzWDVkphAhLr1uRpsUOKaDe6sI20ChHzM5Wk82Vy0LuJ3PbD0TeNCz2876hAObk0uD60A6Y0keel4pyXioynRkEqTHH7UD8z8CuiObzWuh78275wiSWwpQF9jY0q4Mj6pWH%2FgiAcgM5Fc5k85d94pLkPA64xc28o1ZRrf%2BUyPUUkDG36Vp59bfa1iR8xujVX6EZcWakTzmh4RuoGlsynN%2BI%2BqDfjhbnqjeFYOpG%2BYlD0%2FedR4GyC1zjMKODSll3Cvjdt2A0glu5eTqwSKIEmp9XEZmYmREkkp2nEOnPLyrk77YFwq%2Fl1CzCswbu9BjqkAYCvcTUuOhr3LDwnr9nDVLKyn8sdb6g45T0C7FhfWQqPu4fwCzyTPAkuLL21D2%2FfdCYDxW7qhY9%2FrC3JZY%2FSHvU4qUR6yWD1Oa1bZXGxEKVfWmdPqCuMMd3A81%2F1VTeqBmPZGVzSx%2BgrdrA4rIuwyQcquUxIJtmiMzUeFJ0uYSC0qb1Alvyn6pRoBI%2FKIuU5cIDFsEvi4MPFYA8i6SVQWI2DrmUV&X-Amz-Signature=be416a76b65e92b23574e1c0edb8013afdc4f7507cdc6626560438b70edf42d6&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665EZRTJJK%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T063218Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDTL%2BAcGPSDFAjop2EufEu5N2nlaeF%2BcMU5kNjFtGxZOgIgaOW8Y9y%2BFHLh5WSPE3jBRytQ4oTFg8YBvcj7cCU9aEgq%2FwMIJxAAGgw2Mzc0MjMxODM4MDUiDDnRSwT%2FoZVXjpHtvyrcAw%2FN6RzK0PKWcDwkQ739lh6w6BykxoEXR4M%2BZagkKKG07DinsKd%2F8fiCe2NKNZt5qh%2FcZenG1iBRUfl3KseviOasnSDwCr%2BiS8UmC5NE0K4pl8ZHYfvLhryX%2FvPsU6duP6xdkWEUTwOw1sCdNyoxNoMezRpiEeMYXU4k%2FIkt2WP1lEiSZ98YOBcHmvly%2Fd2wTaZiEgTpDJY%2FzPLGefJ1UKEDtIrxSdkCiHzdQK4ULrW1Bdpwbdk%2BtYoLVHSFybmV745HR0J2ewXH4w9NHzxweYwTsP1WY%2Bp%2BsUsW7WVKdoBqA%2B0Zt9%2Fw7PPGEpvXkY5hR2qSdA0h73jjtYQrGvjCKnega5E%2B8eMxT2ic3R7mSwRwnoo%2Br9HXyVYK%2BmCiKfw3EkCriHGtxSQPq%2BTKEGyrdjAZiOAWSjbN0PMGJ4M4i%2BLBdZ9dERTZd8T%2BLqESjXmZECvPKKHY0CA%2BZm9K6B7dkqvkyQ4asaAjhdkba%2FOzrbpAXso0oiUvyPhOBtt64NRSmlWpSLfvJvWtWt9Mwpp4mEBZZOqrOcmtWCHZoaKAjfTUHyYHmVlC4d6Xs8VPxAEKMGB89sj81xPocjpxHaShAdrVIeNIbpmvWX8ZXHb%2BblFXQeL6cYljBtFAYFZOMKXCu70GOqUBdZx7wLdLtPGkUM5e8hfErvIpG%2BnbmxPLU43NKUN5uzQ7KVKHDbea07mWqgEGbmAFXVFkpU3bT7Ney9Nd%2FfwuP%2F%2F9W0z5kciEcLwqFHHHAe0lw7XAinDeT%2FuIM%2F8ZM1zn0UQA3fmeGq7zS4BXMB5Ba%2BoRxdOl8m%2BAKbzIAfN6yaX3DgJWiSoR40Q7Qsg7KTVnMbr%2FZMo%2F73J6al2Nh%2Bhe8olcusBm&X-Amz-Signature=08dcab206724b66deade3a208cf4ce6aa4eb50586196d7e6af1be92d74e82897&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665BBZZMPC%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T063218Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEAyIta6HweAlIga4JrlyO7r5OyO34Q03nRhjyZW3%2FGlAiBYxvyTZmUqQoDGxhaQv9DhCJ6oVdN2pVv1LEmrJvZmEyr%2FAwgnEAAaDDYzNzQyMzE4MzgwNSIMdnMUhaEFufNBqD9dKtwD2q%2FhFivHTpzUm%2FBSy%2FuDQwNGkSLmPbBN6fjpTprRFk8G0aGXnvInKxBuAD9vsEjdii%2FNKGl1HRcdS6Zta3JPYdQj7hRJcd79Xa8YeaIQkBMyc6fXZrNjHIAyjkhiLUtxArhKhnIPzpaIvG2iUbPb18uYd%2F7KCjKwTYEcM61ttah0pMVu%2Fjwt86THCqvzhjF4kXjkLvvX2QN346Yo3HYz672eYFHMZgi%2Bq9OaqrvkQN3Iua6O3Q%2BvFLf670jaKQci6ZrZVNMGJeAoZp9TThJTvaqoB5YtKcLwe3VrbcDIy4pEI27fOXEEWFhAgKR6YVc8YwjnQMfCu5ghpcoiwvmR%2ByDmtQRlSXlhXXBgfAEbE3IjkKUaiWaryrWXe7kuCalLk06B6WHfY4Ft0wx8BNDTR%2B%2FK%2FfzBEBm1WLYU0A8%2BWgM7s3KWqIkdwEVmVZ%2BzCau8blmzxkABBrqj6sJHAMnf7w2v%2BeQFuIBVDJDMCA5URvnCaaV762%2FSdCGBYRxs0rIkUiSnq4ChLI5Keepx%2BSYKEma8Aqs8H4qJe7deyv0mCraAVxmD5g5jQQhvLuCqKaf1y%2FRLKNcDOvUTv76NiNZkDVbMj10Z8I%2FSFnfHxrjNJaUqhGgvAvllDfoLe9UwrMG7vQY6pgEJPfHto0WkLqzCRPThidIrdgMz7IlncE%2FRs2YcWSjYYRhWnrjYIbfIM5NXSVr%2BM6yIuXiqn6qNL7U%2FOtifoAS%2FYfBaHs5Q%2B3kX49WsiAtL7KeU0BIjwMUcpWFwpJJ6idSV2srjDL3x1CDwY%2BUjZAX8izkMTvdd0Wt%2BVt2Hmdx3gS5u7WJu5GLXuJW7uGw2EWtNSRRrEkyAHM%2Bgi9tw1%2BftiqkAcDoa&X-Amz-Signature=8e8ad045361b96b812d4b9069173c1695fb9af54e912387db1bd58a84a8a9fd1&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YS5EJEQS%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T063217Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCFy65CuYpUz6ON%2BBsTCUmUHKnHiNAQ0vtG7acVGKoqKQIhAL9a1cYL7GoRIq%2FQ9zb3%2B5orVGrDIB5XTHJjLgGK2vfSKv8DCCcQABoMNjM3NDIzMTgzODA1IgzGjtXUsj6z6pVaUFMq3AOaq2JxdjHi0tkdnpl341TV7SITTEzflDxht7VTH75bcYepCXJtK7QQGdxXEHJ1%2FNBFUcEIf%2BMQp107aw5xCQ3TOOuHVtf7Tf03McnYAjuWXQfcALdpGumE5E6233QpaKRSUFm9D2IvQRAwljTEpBuqorIMBd8UPjaPndsqGxTHR0ri2S7PwHX4b%2FlXzr7BmRjk2Nu85gxzplyxzjDMB%2FsSaV6v3slhQZbyWpYmsJig8RBhHnK%2BJx1GxXiARKZChEFm70gIXZhS8HujTrJNcEBhOol78vW2djlmzaPHxEMFOk1QMfhuEZuIdC3%2BFTJkeSR3krh7SzWDVkphAhLr1uRpsUOKaDe6sI20ChHzM5Wk82Vy0LuJ3PbD0TeNCz2876hAObk0uD60A6Y0keel4pyXioynRkEqTHH7UD8z8CuiObzWuh78275wiSWwpQF9jY0q4Mj6pWH%2FgiAcgM5Fc5k85d94pLkPA64xc28o1ZRrf%2BUyPUUkDG36Vp59bfa1iR8xujVX6EZcWakTzmh4RuoGlsynN%2BI%2BqDfjhbnqjeFYOpG%2BYlD0%2FedR4GyC1zjMKODSll3Cvjdt2A0glu5eTqwSKIEmp9XEZmYmREkkp2nEOnPLyrk77YFwq%2Fl1CzCswbu9BjqkAYCvcTUuOhr3LDwnr9nDVLKyn8sdb6g45T0C7FhfWQqPu4fwCzyTPAkuLL21D2%2FfdCYDxW7qhY9%2FrC3JZY%2FSHvU4qUR6yWD1Oa1bZXGxEKVfWmdPqCuMMd3A81%2F1VTeqBmPZGVzSx%2BgrdrA4rIuwyQcquUxIJtmiMzUeFJ0uYSC0qb1Alvyn6pRoBI%2FKIuU5cIDFsEvi4MPFYA8i6SVQWI2DrmUV&X-Amz-Signature=d426b8f79779a46f11e868d144916d4e4016ba1264d23278a2c4cece4c24cc9c&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YS5EJEQS%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T063217Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCFy65CuYpUz6ON%2BBsTCUmUHKnHiNAQ0vtG7acVGKoqKQIhAL9a1cYL7GoRIq%2FQ9zb3%2B5orVGrDIB5XTHJjLgGK2vfSKv8DCCcQABoMNjM3NDIzMTgzODA1IgzGjtXUsj6z6pVaUFMq3AOaq2JxdjHi0tkdnpl341TV7SITTEzflDxht7VTH75bcYepCXJtK7QQGdxXEHJ1%2FNBFUcEIf%2BMQp107aw5xCQ3TOOuHVtf7Tf03McnYAjuWXQfcALdpGumE5E6233QpaKRSUFm9D2IvQRAwljTEpBuqorIMBd8UPjaPndsqGxTHR0ri2S7PwHX4b%2FlXzr7BmRjk2Nu85gxzplyxzjDMB%2FsSaV6v3slhQZbyWpYmsJig8RBhHnK%2BJx1GxXiARKZChEFm70gIXZhS8HujTrJNcEBhOol78vW2djlmzaPHxEMFOk1QMfhuEZuIdC3%2BFTJkeSR3krh7SzWDVkphAhLr1uRpsUOKaDe6sI20ChHzM5Wk82Vy0LuJ3PbD0TeNCz2876hAObk0uD60A6Y0keel4pyXioynRkEqTHH7UD8z8CuiObzWuh78275wiSWwpQF9jY0q4Mj6pWH%2FgiAcgM5Fc5k85d94pLkPA64xc28o1ZRrf%2BUyPUUkDG36Vp59bfa1iR8xujVX6EZcWakTzmh4RuoGlsynN%2BI%2BqDfjhbnqjeFYOpG%2BYlD0%2FedR4GyC1zjMKODSll3Cvjdt2A0glu5eTqwSKIEmp9XEZmYmREkkp2nEOnPLyrk77YFwq%2Fl1CzCswbu9BjqkAYCvcTUuOhr3LDwnr9nDVLKyn8sdb6g45T0C7FhfWQqPu4fwCzyTPAkuLL21D2%2FfdCYDxW7qhY9%2FrC3JZY%2FSHvU4qUR6yWD1Oa1bZXGxEKVfWmdPqCuMMd3A81%2F1VTeqBmPZGVzSx%2BgrdrA4rIuwyQcquUxIJtmiMzUeFJ0uYSC0qb1Alvyn6pRoBI%2FKIuU5cIDFsEvi4MPFYA8i6SVQWI2DrmUV&X-Amz-Signature=c55385dba6d9a5ac67e507c22563c86a59ec63484de569a1c394d91c8344f51b&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YS5EJEQS%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T063217Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCFy65CuYpUz6ON%2BBsTCUmUHKnHiNAQ0vtG7acVGKoqKQIhAL9a1cYL7GoRIq%2FQ9zb3%2B5orVGrDIB5XTHJjLgGK2vfSKv8DCCcQABoMNjM3NDIzMTgzODA1IgzGjtXUsj6z6pVaUFMq3AOaq2JxdjHi0tkdnpl341TV7SITTEzflDxht7VTH75bcYepCXJtK7QQGdxXEHJ1%2FNBFUcEIf%2BMQp107aw5xCQ3TOOuHVtf7Tf03McnYAjuWXQfcALdpGumE5E6233QpaKRSUFm9D2IvQRAwljTEpBuqorIMBd8UPjaPndsqGxTHR0ri2S7PwHX4b%2FlXzr7BmRjk2Nu85gxzplyxzjDMB%2FsSaV6v3slhQZbyWpYmsJig8RBhHnK%2BJx1GxXiARKZChEFm70gIXZhS8HujTrJNcEBhOol78vW2djlmzaPHxEMFOk1QMfhuEZuIdC3%2BFTJkeSR3krh7SzWDVkphAhLr1uRpsUOKaDe6sI20ChHzM5Wk82Vy0LuJ3PbD0TeNCz2876hAObk0uD60A6Y0keel4pyXioynRkEqTHH7UD8z8CuiObzWuh78275wiSWwpQF9jY0q4Mj6pWH%2FgiAcgM5Fc5k85d94pLkPA64xc28o1ZRrf%2BUyPUUkDG36Vp59bfa1iR8xujVX6EZcWakTzmh4RuoGlsynN%2BI%2BqDfjhbnqjeFYOpG%2BYlD0%2FedR4GyC1zjMKODSll3Cvjdt2A0glu5eTqwSKIEmp9XEZmYmREkkp2nEOnPLyrk77YFwq%2Fl1CzCswbu9BjqkAYCvcTUuOhr3LDwnr9nDVLKyn8sdb6g45T0C7FhfWQqPu4fwCzyTPAkuLL21D2%2FfdCYDxW7qhY9%2FrC3JZY%2FSHvU4qUR6yWD1Oa1bZXGxEKVfWmdPqCuMMd3A81%2F1VTeqBmPZGVzSx%2BgrdrA4rIuwyQcquUxIJtmiMzUeFJ0uYSC0qb1Alvyn6pRoBI%2FKIuU5cIDFsEvi4MPFYA8i6SVQWI2DrmUV&X-Amz-Signature=764418c9dc36ece60d6c67c33ca156eed2af97d4f665cde830e0410216a43d17&X-Amz-SignedHeaders=host&x-id=GetObject)


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

