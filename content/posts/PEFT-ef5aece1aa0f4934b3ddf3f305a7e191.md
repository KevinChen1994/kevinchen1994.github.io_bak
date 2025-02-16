---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4664TV6NRT4%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250216T232113Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjED8aCXVzLXdlc3QtMiJGMEQCIG41xMJlNmQQlA%2B7fA8f3YXtULonhTHK2VrI%2BEOrINnoAiA\
  tzETKcSz%2BwZ9SAxDaYVtKcMPT6GxAeflKOC37CMfNNCr%2FAwhnEAAaDDYzNzQyMzE4MzgwNSIM\
  k9hWS358ojYCw8XhKtwDlEMOwT8ViIJ1fFNWGVRr2zUpOx2G2DKlCHerubgcv6O4EUfpRKg9uFfgp\
  QXdBUIIurg1ocsl5SKrnXcorgXdo5icA3tlSRhB4ryfoJ0xZQh4WafLcuFyYn3t0IJ7UNnmsXE6%2\
  Fs%2BD5eYYlvSvWYoPhhIhskGHIl1SV8od5LAhL9d3J0bFPLmXaxxNnfSCcXhUvbDSPCIKsROnS8A\
  S%2FyiRipY3liUVJWs%2BqJ3%2FbHf0ULJV%2FcT4bZ4Jsldc5Y2dAeYCFM%2FJo9MTrqlLDmpALn\
  lEiAM13rr218T6dLk%2F3onojmeatnqZ%2BLaYaykzW6d0oFNBfGveOmgqBO9iucUKNTqzcd06s9o\
  x4JHUlcc%2FSszzblDsqzDhvj%2FKq%2FB5hzoYuPi5517kLFqD7575yD5OZB7Hb8jFa7F%2B8OG5\
  vzbGS%2FplRHF%2BTdchYUQXtslvJj%2FXm8iTx6Veoi%2BgTgrDrBS79IpOH8orf96%2Fj6M2SO%\
  2F%2BI%2B90lOgjVGh8vmAqwjyZFRSig1XbspWhsz0%2FdAjJUeMzip8Z3%2BStWBQlo0rHHVxcF0\
  ItW%2ByI5IwlkkYVrgBDOJaASdu%2Bi9MmSWgSn48Dptq%2FasBoPwqn2iRo690b2PJR1QbHukRl2\
  dgfErg%2FqErlIeEwqMjJvQY6pgH1QT0ZORm5339dxDsw8SUSkhuLgpmFnIATeKEEH2RCn7VrWZoD\
  H2wBb6nTEsA0tVKpAJhkOA04H1Yhku3RiR3Pv4Zl3%2B4JjqH4FHKa%2B8aP9lhWyL9jlmqR9NxjC\
  LxSIAzWsVCLxVLGFPHfdzROdG7q8ToZHl%2FusKrG1LCVSZpd3KW5Hp00YpJF%2BOU8I1rH1HcqLX\
  TmyydyZdcCSW8yQlsZp5Rbz%2BLL&X-Amz-Signature=28ef65c2a045e59fbecfead388307b97\
  ea3d0b41b9041ffddf8ad2d40879f4fe&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB46626HUCZGT%2F20250216%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250216T231955Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjED8aCXVzLXdlc3QtMiJHMEUCIQDj%2FDbBoQ67%2Fb7Pwx2zqGBj3qv\
        R7SqWn4%2BYriq4h0n0KAIgAOxT5wU7QnvXhNwO5lAJTbpFfVxF2Y78IcOCmC70suwq%2Fw\
        MIZxAAGgw2Mzc0MjMxODM4MDUiDPqOzysaUyOVuDMakSrcAwJ5xqlok63h9APhsUC%2BPk9\
        N%2Fv2URUYvuKahix11vCoHH6VUxRq%2FDeTuAGbtBX%2BCBkA7LxYQX%2FurKmbPsNjO6n\
        WuRmA5L9%2Bwft1A1AXeafFuaXI%2F8Nzs1XxQNC%2BiRAHlziHz%2FOCiE8opTAMScCsOo\
        Bn7RCE6XaOLN6vg19Ihhb1Gcfv5NGHQPpsXYvg8tha90cIe3Aqer5sSsdNkHIhSY0OiEnZc\
        xzzMoPCqkKQtMbIIl1cd%2Bgwzb2WOswZ6aHknxYoc3pIjySHdEW0Nrjb8PEOqh7nX8iorJ\
        o3h32UgFearmoQ1woxFAHvsqqSQXlvqSdnQSWcL%2BQNtVOZ2nKu6%2FWjcCeKfNK5IxbL%\
        2BjladV%2BeNQH4wZZ7nHfIKsjJCtCiKXcjVPnbDL%2BaVY3DQIoozSFivsbFzN%2BhEqZj\
        jlGodV6bwV%2FdlV9%2BjAbYJigmmEh76%2B7IYneIutV6T9i3o2q1imm35pgCwvAbIQKG5\
        ZidywmAH93rZsruKPfxLLFeUeNu0ZuxchXgwgvHiYVyU5wVaGxnSqz9k8R8PO%2Fhyvzqzb\
        WnoRg9yP7nEPKFEVtTFDGHXio2Caif5pkLWW3D71fQr2%2BRH2OWtRTHyB1V8TA0%2Bwl96\
        ve3vv4zwM2LGOpfqMMXIyb0GOqUB%2FNxZnGa2fTkNmOIsYURPHpKE%2FspVzwWAU7W53AF\
        T8krfPPxaN5ajN40YD4CSF5fA%2Bs6r1NfLX6KuAhc7sL%2BNihZmyTaw5jfdiY%2F5OuEb\
        EQlp6bcHbS8jylOMT16LE6Y9IHk2vkjHQb5AeKmQTnrRM3W7%2F8Tw1j1EoSbiLeQznS%2F\
        bQ6FPYUDHVrsbGfIo4pKjxs%2BjoJzHWPEVeZPUwIjqSP5AOkkc&X-Amz-Signature=986\
        c635a2fe90172df72d766fef1c9256c8fc4c869897da18bdf5b1f283e4c8d&X-Amz-Sig\
        nedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-17T00:19:55.263Z"
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
UPDATE_TIME: "2025-02-16T23:21:18.745Z"
EXPIRY_TIME: "2025-02-17T00:21:07.184Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z3RAZBTN%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T232107Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjED8aCXVzLXdlc3QtMiJIMEYCIQCm%2FhIwQr0Io4U4uHm5twxSQas%2FYqrR56epmLLabDtJOAIhAJT%2F%2FGWGr%2FHn88ve4KeKWGREUFUp25JH9eHHmbl%2BEDpJKv8DCGcQABoMNjM3NDIzMTgzODA1Igzi9xtp65EGUy88zncq3AMUiL8Y3kpcG1F2WlW%2FNL7Ri30wS%2BauP4XBM1X3yAPAQ0elkO9%2FakiXUdeYm%2FhH4vsqS43JaD7T08lMG2l%2FO9mTXl3ULTivjYEo0f74ihflBpiiBetyhNe3GlVa2953fODFkCyvg2tRXOH5MuSHHuNSvXHWmIxmTLRSr67tLaE4sjkKeoLIoFj5dE4eDzdcbek2NRStgIWwxgemVjS03VXF35LWbhAyOtcBpUGBl%2BGubm8EH0R4edMSm8IQFfVb26iFGX5F188I7L1xtMqU6fIlTI5QkQXIqwCbk3N2ixHgBjCXmj1U%2F9Ng164mHNR4SLWzOEZX30L%2Beg9xebAN7DIBObq1x6nVAQIRQy3RZWEhNnPZrbtvRnh47TNCkuC0JTdleoFrIrEIp2mH4qT71wUXOVA6vZtZBZqBKjaW1tP3P%2FBL4E2SzjPZ56oWZ7JNqGARlVAJls5ztN0GNG6eezuvEBdNe0lrVns1yM2CoucBwwyX2x79J8Avpnvvhwgqy%2FmNcMlXRcus4WKWl2ovx5KMWoZlS4mpIiKdXEniXflEEAWmOH5QmmCTpmmAcT8qY05R71EQw2Oyg3BzVZc6wDrKx7dvdszoX17L7I3P%2B0u9jeJafmQUNxdCx6GC8zC0yMm9BjqkAQ5N6ixINK6uJUpf6tqR1egoWuKFh42NeQiHsHaXE8ssRVr5hbWYrPOcriOktda5eEP54yoUoDWZX5mVFOYgvzF9wE5V7YUOEc%2BdSLOlham2QWp2KQE3J1Scz0temNKr3Q6sjzZaEHam9X%2BL93EH3O3bOHiXfMis2nkgTG3pHJbWqWMiXJVfHpu3hrLDjFNmWtleq5Qb8gFYpXZnwSdDCG6RvsqL&X-Amz-Signature=795d100b6a3e53ccc32cad7acfe7766def4c7f721376d139e6a9d63e19e5bb92&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z3RAZBTN%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T232107Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjED8aCXVzLXdlc3QtMiJIMEYCIQCm%2FhIwQr0Io4U4uHm5twxSQas%2FYqrR56epmLLabDtJOAIhAJT%2F%2FGWGr%2FHn88ve4KeKWGREUFUp25JH9eHHmbl%2BEDpJKv8DCGcQABoMNjM3NDIzMTgzODA1Igzi9xtp65EGUy88zncq3AMUiL8Y3kpcG1F2WlW%2FNL7Ri30wS%2BauP4XBM1X3yAPAQ0elkO9%2FakiXUdeYm%2FhH4vsqS43JaD7T08lMG2l%2FO9mTXl3ULTivjYEo0f74ihflBpiiBetyhNe3GlVa2953fODFkCyvg2tRXOH5MuSHHuNSvXHWmIxmTLRSr67tLaE4sjkKeoLIoFj5dE4eDzdcbek2NRStgIWwxgemVjS03VXF35LWbhAyOtcBpUGBl%2BGubm8EH0R4edMSm8IQFfVb26iFGX5F188I7L1xtMqU6fIlTI5QkQXIqwCbk3N2ixHgBjCXmj1U%2F9Ng164mHNR4SLWzOEZX30L%2Beg9xebAN7DIBObq1x6nVAQIRQy3RZWEhNnPZrbtvRnh47TNCkuC0JTdleoFrIrEIp2mH4qT71wUXOVA6vZtZBZqBKjaW1tP3P%2FBL4E2SzjPZ56oWZ7JNqGARlVAJls5ztN0GNG6eezuvEBdNe0lrVns1yM2CoucBwwyX2x79J8Avpnvvhwgqy%2FmNcMlXRcus4WKWl2ovx5KMWoZlS4mpIiKdXEniXflEEAWmOH5QmmCTpmmAcT8qY05R71EQw2Oyg3BzVZc6wDrKx7dvdszoX17L7I3P%2B0u9jeJafmQUNxdCx6GC8zC0yMm9BjqkAQ5N6ixINK6uJUpf6tqR1egoWuKFh42NeQiHsHaXE8ssRVr5hbWYrPOcriOktda5eEP54yoUoDWZX5mVFOYgvzF9wE5V7YUOEc%2BdSLOlham2QWp2KQE3J1Scz0temNKr3Q6sjzZaEHam9X%2BL93EH3O3bOHiXfMis2nkgTG3pHJbWqWMiXJVfHpu3hrLDjFNmWtleq5Qb8gFYpXZnwSdDCG6RvsqL&X-Amz-Signature=410bd7ed8f595e69ce550a85866a0c2e1be42eb7074890a383bb80867fc02add&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z3RAZBTN%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T232107Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjED8aCXVzLXdlc3QtMiJIMEYCIQCm%2FhIwQr0Io4U4uHm5twxSQas%2FYqrR56epmLLabDtJOAIhAJT%2F%2FGWGr%2FHn88ve4KeKWGREUFUp25JH9eHHmbl%2BEDpJKv8DCGcQABoMNjM3NDIzMTgzODA1Igzi9xtp65EGUy88zncq3AMUiL8Y3kpcG1F2WlW%2FNL7Ri30wS%2BauP4XBM1X3yAPAQ0elkO9%2FakiXUdeYm%2FhH4vsqS43JaD7T08lMG2l%2FO9mTXl3ULTivjYEo0f74ihflBpiiBetyhNe3GlVa2953fODFkCyvg2tRXOH5MuSHHuNSvXHWmIxmTLRSr67tLaE4sjkKeoLIoFj5dE4eDzdcbek2NRStgIWwxgemVjS03VXF35LWbhAyOtcBpUGBl%2BGubm8EH0R4edMSm8IQFfVb26iFGX5F188I7L1xtMqU6fIlTI5QkQXIqwCbk3N2ixHgBjCXmj1U%2F9Ng164mHNR4SLWzOEZX30L%2Beg9xebAN7DIBObq1x6nVAQIRQy3RZWEhNnPZrbtvRnh47TNCkuC0JTdleoFrIrEIp2mH4qT71wUXOVA6vZtZBZqBKjaW1tP3P%2FBL4E2SzjPZ56oWZ7JNqGARlVAJls5ztN0GNG6eezuvEBdNe0lrVns1yM2CoucBwwyX2x79J8Avpnvvhwgqy%2FmNcMlXRcus4WKWl2ovx5KMWoZlS4mpIiKdXEniXflEEAWmOH5QmmCTpmmAcT8qY05R71EQw2Oyg3BzVZc6wDrKx7dvdszoX17L7I3P%2B0u9jeJafmQUNxdCx6GC8zC0yMm9BjqkAQ5N6ixINK6uJUpf6tqR1egoWuKFh42NeQiHsHaXE8ssRVr5hbWYrPOcriOktda5eEP54yoUoDWZX5mVFOYgvzF9wE5V7YUOEc%2BdSLOlham2QWp2KQE3J1Scz0temNKr3Q6sjzZaEHam9X%2BL93EH3O3bOHiXfMis2nkgTG3pHJbWqWMiXJVfHpu3hrLDjFNmWtleq5Qb8gFYpXZnwSdDCG6RvsqL&X-Amz-Signature=12ddc636ca2f54c3bc71208f72dae1fee0b463f24baeb1957e4c004dc91496ea&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z3RAZBTN%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T232107Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjED8aCXVzLXdlc3QtMiJIMEYCIQCm%2FhIwQr0Io4U4uHm5twxSQas%2FYqrR56epmLLabDtJOAIhAJT%2F%2FGWGr%2FHn88ve4KeKWGREUFUp25JH9eHHmbl%2BEDpJKv8DCGcQABoMNjM3NDIzMTgzODA1Igzi9xtp65EGUy88zncq3AMUiL8Y3kpcG1F2WlW%2FNL7Ri30wS%2BauP4XBM1X3yAPAQ0elkO9%2FakiXUdeYm%2FhH4vsqS43JaD7T08lMG2l%2FO9mTXl3ULTivjYEo0f74ihflBpiiBetyhNe3GlVa2953fODFkCyvg2tRXOH5MuSHHuNSvXHWmIxmTLRSr67tLaE4sjkKeoLIoFj5dE4eDzdcbek2NRStgIWwxgemVjS03VXF35LWbhAyOtcBpUGBl%2BGubm8EH0R4edMSm8IQFfVb26iFGX5F188I7L1xtMqU6fIlTI5QkQXIqwCbk3N2ixHgBjCXmj1U%2F9Ng164mHNR4SLWzOEZX30L%2Beg9xebAN7DIBObq1x6nVAQIRQy3RZWEhNnPZrbtvRnh47TNCkuC0JTdleoFrIrEIp2mH4qT71wUXOVA6vZtZBZqBKjaW1tP3P%2FBL4E2SzjPZ56oWZ7JNqGARlVAJls5ztN0GNG6eezuvEBdNe0lrVns1yM2CoucBwwyX2x79J8Avpnvvhwgqy%2FmNcMlXRcus4WKWl2ovx5KMWoZlS4mpIiKdXEniXflEEAWmOH5QmmCTpmmAcT8qY05R71EQw2Oyg3BzVZc6wDrKx7dvdszoX17L7I3P%2B0u9jeJafmQUNxdCx6GC8zC0yMm9BjqkAQ5N6ixINK6uJUpf6tqR1egoWuKFh42NeQiHsHaXE8ssRVr5hbWYrPOcriOktda5eEP54yoUoDWZX5mVFOYgvzF9wE5V7YUOEc%2BdSLOlham2QWp2KQE3J1Scz0temNKr3Q6sjzZaEHam9X%2BL93EH3O3bOHiXfMis2nkgTG3pHJbWqWMiXJVfHpu3hrLDjFNmWtleq5Qb8gFYpXZnwSdDCG6RvsqL&X-Amz-Signature=252d25c6969ba28fc806629a166052dbdb5ee33e9cafb5eb25f780893041de26&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z3RAZBTN%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T232107Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjED8aCXVzLXdlc3QtMiJIMEYCIQCm%2FhIwQr0Io4U4uHm5twxSQas%2FYqrR56epmLLabDtJOAIhAJT%2F%2FGWGr%2FHn88ve4KeKWGREUFUp25JH9eHHmbl%2BEDpJKv8DCGcQABoMNjM3NDIzMTgzODA1Igzi9xtp65EGUy88zncq3AMUiL8Y3kpcG1F2WlW%2FNL7Ri30wS%2BauP4XBM1X3yAPAQ0elkO9%2FakiXUdeYm%2FhH4vsqS43JaD7T08lMG2l%2FO9mTXl3ULTivjYEo0f74ihflBpiiBetyhNe3GlVa2953fODFkCyvg2tRXOH5MuSHHuNSvXHWmIxmTLRSr67tLaE4sjkKeoLIoFj5dE4eDzdcbek2NRStgIWwxgemVjS03VXF35LWbhAyOtcBpUGBl%2BGubm8EH0R4edMSm8IQFfVb26iFGX5F188I7L1xtMqU6fIlTI5QkQXIqwCbk3N2ixHgBjCXmj1U%2F9Ng164mHNR4SLWzOEZX30L%2Beg9xebAN7DIBObq1x6nVAQIRQy3RZWEhNnPZrbtvRnh47TNCkuC0JTdleoFrIrEIp2mH4qT71wUXOVA6vZtZBZqBKjaW1tP3P%2FBL4E2SzjPZ56oWZ7JNqGARlVAJls5ztN0GNG6eezuvEBdNe0lrVns1yM2CoucBwwyX2x79J8Avpnvvhwgqy%2FmNcMlXRcus4WKWl2ovx5KMWoZlS4mpIiKdXEniXflEEAWmOH5QmmCTpmmAcT8qY05R71EQw2Oyg3BzVZc6wDrKx7dvdszoX17L7I3P%2B0u9jeJafmQUNxdCx6GC8zC0yMm9BjqkAQ5N6ixINK6uJUpf6tqR1egoWuKFh42NeQiHsHaXE8ssRVr5hbWYrPOcriOktda5eEP54yoUoDWZX5mVFOYgvzF9wE5V7YUOEc%2BdSLOlham2QWp2KQE3J1Scz0temNKr3Q6sjzZaEHam9X%2BL93EH3O3bOHiXfMis2nkgTG3pHJbWqWMiXJVfHpu3hrLDjFNmWtleq5Qb8gFYpXZnwSdDCG6RvsqL&X-Amz-Signature=91825591012036bab3b09000806331d88582d55369f21fc26a45a89baf4454f8&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QBAKLOMO%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T232108Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjED8aCXVzLXdlc3QtMiJHMEUCIQD%2Bvaq01jsxYaH35Ury09VCZVRIYI1kW5oFhlVT2qaMFQIgTvqkOg76%2FFDaGPvJTFFtkRUzIXq5K%2FxdPMk9dUkn08Qq%2FwMIZxAAGgw2Mzc0MjMxODM4MDUiDOOCNWLi6GOm3f3otSrcA9OxvR%2Bdv93oSuaLPAuburMkCjvDJl1%2FJkpgkyeMrhF0toe8LwFrsU%2B18z09LRY54VYarxRMxhjs8NtA64aOeUqPy9q7e7c7%2F%2FAr9d0m9mpZwYyKZZfSZic%2BMaQ%2FpxjWIe%2BZq00cBIv%2BwqZWax6Rf6KCf4IWHWzj39y7QYpzv1Nyr6togR4KUS%2BvjCX7fY3RKPhg3xibhUzYJODDM5E5BxQy%2F%2BHNje7yNSGI%2B50MhP%2B%2FW0lC66953t4zsUk11yUbnpB5tmb8VjGoQSh1vn1%2F6UtaXyRiLCaU5xNmD7OLSg0%2BENFiS59uoaU991X8BX82lxbcVa0Tb8b7C0SDDl27wvLAXITqJy6FzLzkjqccCs8J3eNtRYQvGKtmFaRotcVGPTgwW6Eoz9TPHWV3Y2v6XWtYdoY6OTgepoANV%2F0aVSv%2BKWPNh0sj0kTkBHhx4WWfLMVNCq%2FdfF5WlkzniZVK3kZbBGsB5bN9PwsPdEadPlwXeFifZzc7MBlAc38a8td6At6t%2BtTrEdddF2HvAwaUcOWa64Qtb7XqxsEW6XepQPfT0%2Fio6h5CdevD7bGKKEKHMeXWxQWnp6QsNZqNbrxcFRV9zIobvi2xmum7A1Vzxrv%2FTdn%2B0y0BH1xstovOMMbIyb0GOqUBOLtA0XGJd7YSIAuA%2B51WR4uiy0EhpWHVk1Q7F4tKo%2BjLyP9IOWDKPyXU9XReCSn98r2uP1T0r6AHwh7%2BCVJlGZjPM4CAaywHyLR%2FF7kQ9YY%2FVXGRk64AoN16kXiayu96Q7aRwQ2psrvtUIqrqwmsKDQ16KcsF%2B2%2BzHKAYeW%2FyjgMw%2B3MyNgdF7mPrSiKUW1UoIzRcC0An3O%2BY%2FvP1b6ZRqD7%2F9q6&X-Amz-Signature=ba4f21020f7b06adad8e8d5ea43d53cbf40825aa45e7d6ebb78700530a9d4ae3&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SAKAOVHW%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T232112Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjED8aCXVzLXdlc3QtMiJIMEYCIQC7ZxAZPMzzkNz4tKdkp2g2pZEJU2d1N6A10M8YBprv7AIhAK0FTaAVsbW2X11wnAhkn4MuQ%2BtprGduVfhG%2BogqLZd6Kv8DCGcQABoMNjM3NDIzMTgzODA1Igzwdwsps3LqHbh4zS4q3ANBHuyE4RSfTUxf%2BhFdiCaBmhSIreb6yT%2FNUA34jwwBb%2FDwOxZY3VFC9b78kBo3pqDcJqbesRdZUeUcizFO%2FZrNDLmyvRjtiIOnufxRI0c1R9X3J5eT4bqk7NrKluDG0I0zqnTa4W2rOVLqgKl1hLQ2qrxlnaPOJnPspWKUG9G0d8dRXzd7XMhgGmPUZJH3f%2FKprBfwGNRJkH1%2B3kMW6Ds%2FzX8xC2dAg8Z8L7utqXL8rfdenJBM7xPSVC4sAvwTYRys9G13PtDIjPCghPM0BTcnx%2F3zg9uEvlytqF8O2svQG6hTx3popnYDilZLvKuoh6BPX%2BiMLgyNBLWOsOwno672Y06OoBMDak85fsQ4WjQ05ONY2rJ9qPrDoq2mqxKVtpkmtcUhXn2DIY4cV3gDNiTG%2FWsdjfySrvyRJA%2FQMsYQluOcYPPRARa02gsDz541hSLs0mGNp5%2Fsxf6x4yG%2FqBISxlWyJizHmGiwoW8MyH2BvLzy4QVpjdYpsbYzYI7a%2BxZdiXsMDCyI28XD9KSoP5gBGbejfb9P%2Fa1hawGwoPQQZEzWPRvEZgGElQRmVc2q0QzseE4MMfetplDAwP7iR0xIp8Ln04DrqsezKzf5niIJGxXtkKUu3jeJgve1qjCpyMm9BjqkAV0gGstTJjH3bva9Jpcc1gJksrfS2F5DkPS7vAEE7mJtNe%2Bk2Hy0wcwiWsuDQtvaX%2BZ0KrZhqCk8UlanhLhmBmZSi%2Bhk2TmQV4cq7cKRHp7pGB03n5%2BclIQkj6f1Uj0y5RdddWTEkovM75bvvyzRrPVff8o499ZjDdAcGseXZnH0cLy2KF%2F%2BNELdDo7lx88ida3vsc1D85Fo58TaHOHUOkxcLBJs&X-Amz-Signature=382048ce393019369efc949b345924d294ec7019bc428833cb2160ada00d5ae3&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z3RAZBTN%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T232107Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjED8aCXVzLXdlc3QtMiJIMEYCIQCm%2FhIwQr0Io4U4uHm5twxSQas%2FYqrR56epmLLabDtJOAIhAJT%2F%2FGWGr%2FHn88ve4KeKWGREUFUp25JH9eHHmbl%2BEDpJKv8DCGcQABoMNjM3NDIzMTgzODA1Igzi9xtp65EGUy88zncq3AMUiL8Y3kpcG1F2WlW%2FNL7Ri30wS%2BauP4XBM1X3yAPAQ0elkO9%2FakiXUdeYm%2FhH4vsqS43JaD7T08lMG2l%2FO9mTXl3ULTivjYEo0f74ihflBpiiBetyhNe3GlVa2953fODFkCyvg2tRXOH5MuSHHuNSvXHWmIxmTLRSr67tLaE4sjkKeoLIoFj5dE4eDzdcbek2NRStgIWwxgemVjS03VXF35LWbhAyOtcBpUGBl%2BGubm8EH0R4edMSm8IQFfVb26iFGX5F188I7L1xtMqU6fIlTI5QkQXIqwCbk3N2ixHgBjCXmj1U%2F9Ng164mHNR4SLWzOEZX30L%2Beg9xebAN7DIBObq1x6nVAQIRQy3RZWEhNnPZrbtvRnh47TNCkuC0JTdleoFrIrEIp2mH4qT71wUXOVA6vZtZBZqBKjaW1tP3P%2FBL4E2SzjPZ56oWZ7JNqGARlVAJls5ztN0GNG6eezuvEBdNe0lrVns1yM2CoucBwwyX2x79J8Avpnvvhwgqy%2FmNcMlXRcus4WKWl2ovx5KMWoZlS4mpIiKdXEniXflEEAWmOH5QmmCTpmmAcT8qY05R71EQw2Oyg3BzVZc6wDrKx7dvdszoX17L7I3P%2B0u9jeJafmQUNxdCx6GC8zC0yMm9BjqkAQ5N6ixINK6uJUpf6tqR1egoWuKFh42NeQiHsHaXE8ssRVr5hbWYrPOcriOktda5eEP54yoUoDWZX5mVFOYgvzF9wE5V7YUOEc%2BdSLOlham2QWp2KQE3J1Scz0temNKr3Q6sjzZaEHam9X%2BL93EH3O3bOHiXfMis2nkgTG3pHJbWqWMiXJVfHpu3hrLDjFNmWtleq5Qb8gFYpXZnwSdDCG6RvsqL&X-Amz-Signature=82afc0cf9b1b9ea9de80c0f31ef5b1cf817bb5e6d1de5084aa7c64974eb4dc31&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z3RAZBTN%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T232107Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjED8aCXVzLXdlc3QtMiJIMEYCIQCm%2FhIwQr0Io4U4uHm5twxSQas%2FYqrR56epmLLabDtJOAIhAJT%2F%2FGWGr%2FHn88ve4KeKWGREUFUp25JH9eHHmbl%2BEDpJKv8DCGcQABoMNjM3NDIzMTgzODA1Igzi9xtp65EGUy88zncq3AMUiL8Y3kpcG1F2WlW%2FNL7Ri30wS%2BauP4XBM1X3yAPAQ0elkO9%2FakiXUdeYm%2FhH4vsqS43JaD7T08lMG2l%2FO9mTXl3ULTivjYEo0f74ihflBpiiBetyhNe3GlVa2953fODFkCyvg2tRXOH5MuSHHuNSvXHWmIxmTLRSr67tLaE4sjkKeoLIoFj5dE4eDzdcbek2NRStgIWwxgemVjS03VXF35LWbhAyOtcBpUGBl%2BGubm8EH0R4edMSm8IQFfVb26iFGX5F188I7L1xtMqU6fIlTI5QkQXIqwCbk3N2ixHgBjCXmj1U%2F9Ng164mHNR4SLWzOEZX30L%2Beg9xebAN7DIBObq1x6nVAQIRQy3RZWEhNnPZrbtvRnh47TNCkuC0JTdleoFrIrEIp2mH4qT71wUXOVA6vZtZBZqBKjaW1tP3P%2FBL4E2SzjPZ56oWZ7JNqGARlVAJls5ztN0GNG6eezuvEBdNe0lrVns1yM2CoucBwwyX2x79J8Avpnvvhwgqy%2FmNcMlXRcus4WKWl2ovx5KMWoZlS4mpIiKdXEniXflEEAWmOH5QmmCTpmmAcT8qY05R71EQw2Oyg3BzVZc6wDrKx7dvdszoX17L7I3P%2B0u9jeJafmQUNxdCx6GC8zC0yMm9BjqkAQ5N6ixINK6uJUpf6tqR1egoWuKFh42NeQiHsHaXE8ssRVr5hbWYrPOcriOktda5eEP54yoUoDWZX5mVFOYgvzF9wE5V7YUOEc%2BdSLOlham2QWp2KQE3J1Scz0temNKr3Q6sjzZaEHam9X%2BL93EH3O3bOHiXfMis2nkgTG3pHJbWqWMiXJVfHpu3hrLDjFNmWtleq5Qb8gFYpXZnwSdDCG6RvsqL&X-Amz-Signature=476defeeb8a5adf2d38acc39991ac94e83d3e2a73ff1720c4ed3edc260522aa9&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z3RAZBTN%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T232107Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjED8aCXVzLXdlc3QtMiJIMEYCIQCm%2FhIwQr0Io4U4uHm5twxSQas%2FYqrR56epmLLabDtJOAIhAJT%2F%2FGWGr%2FHn88ve4KeKWGREUFUp25JH9eHHmbl%2BEDpJKv8DCGcQABoMNjM3NDIzMTgzODA1Igzi9xtp65EGUy88zncq3AMUiL8Y3kpcG1F2WlW%2FNL7Ri30wS%2BauP4XBM1X3yAPAQ0elkO9%2FakiXUdeYm%2FhH4vsqS43JaD7T08lMG2l%2FO9mTXl3ULTivjYEo0f74ihflBpiiBetyhNe3GlVa2953fODFkCyvg2tRXOH5MuSHHuNSvXHWmIxmTLRSr67tLaE4sjkKeoLIoFj5dE4eDzdcbek2NRStgIWwxgemVjS03VXF35LWbhAyOtcBpUGBl%2BGubm8EH0R4edMSm8IQFfVb26iFGX5F188I7L1xtMqU6fIlTI5QkQXIqwCbk3N2ixHgBjCXmj1U%2F9Ng164mHNR4SLWzOEZX30L%2Beg9xebAN7DIBObq1x6nVAQIRQy3RZWEhNnPZrbtvRnh47TNCkuC0JTdleoFrIrEIp2mH4qT71wUXOVA6vZtZBZqBKjaW1tP3P%2FBL4E2SzjPZ56oWZ7JNqGARlVAJls5ztN0GNG6eezuvEBdNe0lrVns1yM2CoucBwwyX2x79J8Avpnvvhwgqy%2FmNcMlXRcus4WKWl2ovx5KMWoZlS4mpIiKdXEniXflEEAWmOH5QmmCTpmmAcT8qY05R71EQw2Oyg3BzVZc6wDrKx7dvdszoX17L7I3P%2B0u9jeJafmQUNxdCx6GC8zC0yMm9BjqkAQ5N6ixINK6uJUpf6tqR1egoWuKFh42NeQiHsHaXE8ssRVr5hbWYrPOcriOktda5eEP54yoUoDWZX5mVFOYgvzF9wE5V7YUOEc%2BdSLOlham2QWp2KQE3J1Scz0temNKr3Q6sjzZaEHam9X%2BL93EH3O3bOHiXfMis2nkgTG3pHJbWqWMiXJVfHpu3hrLDjFNmWtleq5Qb8gFYpXZnwSdDCG6RvsqL&X-Amz-Signature=806d3ec8887da8ddc3c9fdf16831e9bea93685153b6a2c8ce638c13644008ca8&X-Amz-SignedHeaders=host&x-id=GetObject)


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

