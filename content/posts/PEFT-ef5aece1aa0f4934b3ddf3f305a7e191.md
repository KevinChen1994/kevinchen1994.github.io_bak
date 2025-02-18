---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4664NZ37XRR%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250218T191909Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEGoaCXVzLXdlc3QtMiJHMEUCIQDYOFOBxOvOgwd2QzfSjJey0TLMFUxRvk5cXKBGDDzK9gIgdut\
  aXBJk3ZRhlT82VGXmwDMuC81w7sRhVo3MV79D6O0qiAQIk%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%\
  2FARAAGgw2Mzc0MjMxODM4MDUiDA0pHKG9ERA%2BZO3X4CrcAyr9wxZ1fQunVDEgsBtfg3Z4w7VPo\
  GiJm7UqGyOmbYZR4GJFWEQ4o5bW8NIHy7kEink58lEBykB8SoThEbvBRxHNzuwLpqBlziZ56zzPKM\
  RG0VPWdqJ8Cb52Y1j3xILSiBVjD8GnpHMEme6U4UvWITCUNrEHNIz4n%2By6igDi6tqMd5SXJmRKR\
  7k4GQsGNHDsG6KrtAG7TJ1136iW46hNeiaMMOkizaOiZ0T5LEpi11vf%2BLyYpyX9IAPLA92YyJtg\
  %2BEHK94OK7EUQKCY3CFhLHbM%2F7qc%2BBF5WKt9CzCrU%2BuDBgLVkQNkn9JVYb1ZNH22z6Fjp0\
  qjAzimMV3uVr%2Fx1U0fFjAR%2B6iYLLUnpdWHsncTE%2BNpaTZmetG%2FMX1G4PXT7dUgeuO3OiA\
  u3DPIMWVqE9HWu3Vh6TxY9Rar2QK4lqaeIN2bcCzy4a1vvzdz93BWU8Re80ZunWo4hTjBcscHbO7y\
  vNDdVOF2ZRpWUpSDPaexyWi5lxf0imoClKh7K6%2BoL4ji10%2FXxOt7t05%2FpgcxuVhWFXOCGaQ\
  khkbHzZU0MIBIz7CR9wUjQ7l9VK5ItwG8ZxeepnkVrTvC8R5jwP2POMIKO4uSSuLhx09XbWp0Xz1%\
  2B5TmwLXsE8THW0oSY%2FMN6a070GOqUBXedOWXKwztw0lDOHjpRpcNBDJpRYippeaBc7iL0RUU3k\
  eG9T0l4v%2FKNQrGCsh0fE18hugxx2VFJB9lwqiUBbBFsz%2Fa8XHONAKZOF9ER5r8PbT4sJh1ysR\
  4cLLm%2BTZiSgFIL1SAvqJLP1vcvyuCes4LAMl7me7gIB7z9aCB6ctpVxHGXPuEa0Q45XGh%2Frw1\
  x6dTlXxNstqGUAn0KT9i3IdrJL2djl&X-Amz-Signature=229783d1d730538555f880adfbdc04\
  e9b0e15b4d39f8374404d945637393d1a7&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466RXS7526H%2F20250218%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250218T191750Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEGoaCXVzLXdlc3QtMiJHMEUCIBwaWhUBWE85EMox2FnBVQg3sJuwjH%\
        2FCnQkRuLk0zSehAiEAi93AAmqIq2TjIAzPWYxCa2rmfIAexdxP8%2FKCAd8J3acqiAQIk%\
        2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDF%2B%2FNmv9EwU\
        lDDS4RyrcA%2Bc2yDyPQzGnLCAJka6mP%2BlwYxUBMtJIMFhVB4Ny9m1yn9dpJt7LEpfx%2\
        F2pKXiiY5%2BunX0eF2HJGQzTGsXety1SxmyN9BBbrB1s5UVrjm9TKRMEzyej4QHJpVUklU\
        pwYPcLvkbg1Tkx2THlp7URhwrwGBu3vWRr3lsXVy56uwoGy0%2F9%2F%2F79O7qKcZgo7CZ\
        Xvl97zd%2FtdMp9Df32tZyAwqU19FXzEaeobPy1xIx1uD7YQjtQLuwpHXPw6SU72HI2Vec4\
        pTqHHhi3x2ii7f8sF%2B1ABC1A4ztXlV6Ti6z5O5jFIFHHbWVi%2F7Ne42DxBz7wd%2FklR\
        G3ts5QQlqUm9izzbt%2FS7H77OZVDy%2B7hDmPj5GP6xgKTMXTVGglNZ%2FJEEDIE2cahuJ\
        5kpWZ48gzbbZkH%2Fcwj0ogYsBZ60MVhLCwu7531zESt210gfLfnjZJKVqSTzWFk1De2ML1\
        eAkHmtiLvRTjX8FtHDE%2BqCRTEzuB37yINSCvd%2BtJRArzpKdf%2BHSWMU6j9P99e0jN4\
        tpkuHX1BmyL8TZ8Kj20%2B2Vhm1uIIr7L3vwqVbWZfN8YXEwOrlX%2F2tCAmqtNeP7Faha8\
        4YMzy0%2FSyRJZUZoV8gI6ecgbRYWscro02VntFPfTQEKP75MN%2Ba070GOqUB0eUIKoLPs\
        0M0T40Jr8Yk9nHJEAprODVBqf1fDmeJA1JjrE4JjwJtUkySTb0BeJ%2FpeXgBFgjCIytXZr\
        Yv4yRdyqkbrsqLU3ns0dgIvEyKwXElfGJJ7KBd4gap9TLe7ctRuYnBoXaDLlaLfw186GxGh\
        7dLZY9bQBzFuzojOGyitDc9FVq6q70MnG8AqIWeB7HBNO%2F%2FLkyIf%2FKwDh0g6G99Dr\
        Mz1OgQ&X-Amz-Signature=a32311f1cc1bc930379ddf5327859e588284c76185336bea\
        e2b315b84ca0a9b1&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-18T20:17:50.711Z"
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
UPDATE_TIME: "2025-02-18T19:19:15.339Z"
EXPIRY_TIME: "2025-02-18T20:19:07.506Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QKST74FI%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T191908Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGsaCXVzLXdlc3QtMiJHMEUCIEabKIy9v7Ahs%2F1%2BrH0OWdhPx%2BtoyRdVaacsfy6VLqszAiEAqjVnRNEBTgx57Az6yRzI3rnD%2FW5%2BHEnvOcTEAi5fnBwqiAQIlP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDAqs8K9Lsr24w6vx4ircA7OCXpg1LsJ3c29FP%2FYV7phd%2BQBNK3t8TTvz1ngc%2BGoDEDxFuGawjBh%2BZ17fwtx%2Bp0elfmT4OnLPwms7RmyYcc13Q29JAZB5iMtDepg8e7tvqP8FLjswzSOg2wiO9GCGbg8W8pYTYG%2BYY%2B4m2eM2dOIvFQkkagm4TEOY0s3wrApuN9DbDvdWz9AdlA1%2F%2FbpFftMOKcKRGQ2Mh3cymd4S%2FLR8r3UtjEOC%2BF%2BJ2uD7s4Yx2Q4IHyQD%2Bg6bHRxB7YnfYG6IEo0D3VYAX%2BZx3sJb7MYlYrPHdKQX2JbIPrgsWXKrVY4fqNshQih6fx0nqmlVa5JMsJrBf150037%2FvImb6iDjulzjITYFbYRWg2%2FCwHdOLsuMZGKcfa60Vx%2FTVFu5ugIDmvrTnZJxErmADs53p0ZP%2FiDFwyGb779TnVxL6CNSElEmvh7I9hI2jcwdiQHeDBF1kyTW6MQPrF%2FUNL8HP4Ad9yN5s%2BKDZD0GJW0pqYREfcC1ICFg0me6mucLnjvOiZHhXpYzB2oxyykQnKElYGguiSEwbhNuInH7z%2BGHlXoSCZRS30UZf%2FZSsK6rUVoiPg8sd1l8kh5juFh8M5kjmNn22jv%2FuQ5YR%2B1onsfRRKVtFZ56G63zT9y6YTVfMLq5070GOqUBhIXuwp6r7wCg6Kkoy0K2%2BwU4V%2BpWV0tn4O2J1%2Bqb4X87rI0yQvMKcwFuNo9%2FbfmrcwCb7CKcKqkvhVFwpq8KecjkH%2FFSWy6SFKOWVC447162YI3mNXtfxcs3xctf0ikm3aY0XeVTkhQ%2B2TivyRto7Tml0ROmN4xoh1frWPKUXk%2F42AcUFuA82vVyVP2BT0ZgQq5xISDi5%2BCovt58h5HwIzjqcVWn&X-Amz-Signature=bccd4f6dfc1abef6599a974bdf59fb9417f921adf91800a7c6bff4a31d9b8408&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QKST74FI%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T191908Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGsaCXVzLXdlc3QtMiJHMEUCIEabKIy9v7Ahs%2F1%2BrH0OWdhPx%2BtoyRdVaacsfy6VLqszAiEAqjVnRNEBTgx57Az6yRzI3rnD%2FW5%2BHEnvOcTEAi5fnBwqiAQIlP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDAqs8K9Lsr24w6vx4ircA7OCXpg1LsJ3c29FP%2FYV7phd%2BQBNK3t8TTvz1ngc%2BGoDEDxFuGawjBh%2BZ17fwtx%2Bp0elfmT4OnLPwms7RmyYcc13Q29JAZB5iMtDepg8e7tvqP8FLjswzSOg2wiO9GCGbg8W8pYTYG%2BYY%2B4m2eM2dOIvFQkkagm4TEOY0s3wrApuN9DbDvdWz9AdlA1%2F%2FbpFftMOKcKRGQ2Mh3cymd4S%2FLR8r3UtjEOC%2BF%2BJ2uD7s4Yx2Q4IHyQD%2Bg6bHRxB7YnfYG6IEo0D3VYAX%2BZx3sJb7MYlYrPHdKQX2JbIPrgsWXKrVY4fqNshQih6fx0nqmlVa5JMsJrBf150037%2FvImb6iDjulzjITYFbYRWg2%2FCwHdOLsuMZGKcfa60Vx%2FTVFu5ugIDmvrTnZJxErmADs53p0ZP%2FiDFwyGb779TnVxL6CNSElEmvh7I9hI2jcwdiQHeDBF1kyTW6MQPrF%2FUNL8HP4Ad9yN5s%2BKDZD0GJW0pqYREfcC1ICFg0me6mucLnjvOiZHhXpYzB2oxyykQnKElYGguiSEwbhNuInH7z%2BGHlXoSCZRS30UZf%2FZSsK6rUVoiPg8sd1l8kh5juFh8M5kjmNn22jv%2FuQ5YR%2B1onsfRRKVtFZ56G63zT9y6YTVfMLq5070GOqUBhIXuwp6r7wCg6Kkoy0K2%2BwU4V%2BpWV0tn4O2J1%2Bqb4X87rI0yQvMKcwFuNo9%2FbfmrcwCb7CKcKqkvhVFwpq8KecjkH%2FFSWy6SFKOWVC447162YI3mNXtfxcs3xctf0ikm3aY0XeVTkhQ%2B2TivyRto7Tml0ROmN4xoh1frWPKUXk%2F42AcUFuA82vVyVP2BT0ZgQq5xISDi5%2BCovt58h5HwIzjqcVWn&X-Amz-Signature=c6681718094b2fb49920b02f2e64d3888e2dc2737635a79e77b74694ca3a3fce&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QKST74FI%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T191908Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGsaCXVzLXdlc3QtMiJHMEUCIEabKIy9v7Ahs%2F1%2BrH0OWdhPx%2BtoyRdVaacsfy6VLqszAiEAqjVnRNEBTgx57Az6yRzI3rnD%2FW5%2BHEnvOcTEAi5fnBwqiAQIlP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDAqs8K9Lsr24w6vx4ircA7OCXpg1LsJ3c29FP%2FYV7phd%2BQBNK3t8TTvz1ngc%2BGoDEDxFuGawjBh%2BZ17fwtx%2Bp0elfmT4OnLPwms7RmyYcc13Q29JAZB5iMtDepg8e7tvqP8FLjswzSOg2wiO9GCGbg8W8pYTYG%2BYY%2B4m2eM2dOIvFQkkagm4TEOY0s3wrApuN9DbDvdWz9AdlA1%2F%2FbpFftMOKcKRGQ2Mh3cymd4S%2FLR8r3UtjEOC%2BF%2BJ2uD7s4Yx2Q4IHyQD%2Bg6bHRxB7YnfYG6IEo0D3VYAX%2BZx3sJb7MYlYrPHdKQX2JbIPrgsWXKrVY4fqNshQih6fx0nqmlVa5JMsJrBf150037%2FvImb6iDjulzjITYFbYRWg2%2FCwHdOLsuMZGKcfa60Vx%2FTVFu5ugIDmvrTnZJxErmADs53p0ZP%2FiDFwyGb779TnVxL6CNSElEmvh7I9hI2jcwdiQHeDBF1kyTW6MQPrF%2FUNL8HP4Ad9yN5s%2BKDZD0GJW0pqYREfcC1ICFg0me6mucLnjvOiZHhXpYzB2oxyykQnKElYGguiSEwbhNuInH7z%2BGHlXoSCZRS30UZf%2FZSsK6rUVoiPg8sd1l8kh5juFh8M5kjmNn22jv%2FuQ5YR%2B1onsfRRKVtFZ56G63zT9y6YTVfMLq5070GOqUBhIXuwp6r7wCg6Kkoy0K2%2BwU4V%2BpWV0tn4O2J1%2Bqb4X87rI0yQvMKcwFuNo9%2FbfmrcwCb7CKcKqkvhVFwpq8KecjkH%2FFSWy6SFKOWVC447162YI3mNXtfxcs3xctf0ikm3aY0XeVTkhQ%2B2TivyRto7Tml0ROmN4xoh1frWPKUXk%2F42AcUFuA82vVyVP2BT0ZgQq5xISDi5%2BCovt58h5HwIzjqcVWn&X-Amz-Signature=a6100a7e888c3b11c74b509f66b57a3d731124c2d5b29c7da43fe34afdaaf968&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QKST74FI%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T191908Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGsaCXVzLXdlc3QtMiJHMEUCIEabKIy9v7Ahs%2F1%2BrH0OWdhPx%2BtoyRdVaacsfy6VLqszAiEAqjVnRNEBTgx57Az6yRzI3rnD%2FW5%2BHEnvOcTEAi5fnBwqiAQIlP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDAqs8K9Lsr24w6vx4ircA7OCXpg1LsJ3c29FP%2FYV7phd%2BQBNK3t8TTvz1ngc%2BGoDEDxFuGawjBh%2BZ17fwtx%2Bp0elfmT4OnLPwms7RmyYcc13Q29JAZB5iMtDepg8e7tvqP8FLjswzSOg2wiO9GCGbg8W8pYTYG%2BYY%2B4m2eM2dOIvFQkkagm4TEOY0s3wrApuN9DbDvdWz9AdlA1%2F%2FbpFftMOKcKRGQ2Mh3cymd4S%2FLR8r3UtjEOC%2BF%2BJ2uD7s4Yx2Q4IHyQD%2Bg6bHRxB7YnfYG6IEo0D3VYAX%2BZx3sJb7MYlYrPHdKQX2JbIPrgsWXKrVY4fqNshQih6fx0nqmlVa5JMsJrBf150037%2FvImb6iDjulzjITYFbYRWg2%2FCwHdOLsuMZGKcfa60Vx%2FTVFu5ugIDmvrTnZJxErmADs53p0ZP%2FiDFwyGb779TnVxL6CNSElEmvh7I9hI2jcwdiQHeDBF1kyTW6MQPrF%2FUNL8HP4Ad9yN5s%2BKDZD0GJW0pqYREfcC1ICFg0me6mucLnjvOiZHhXpYzB2oxyykQnKElYGguiSEwbhNuInH7z%2BGHlXoSCZRS30UZf%2FZSsK6rUVoiPg8sd1l8kh5juFh8M5kjmNn22jv%2FuQ5YR%2B1onsfRRKVtFZ56G63zT9y6YTVfMLq5070GOqUBhIXuwp6r7wCg6Kkoy0K2%2BwU4V%2BpWV0tn4O2J1%2Bqb4X87rI0yQvMKcwFuNo9%2FbfmrcwCb7CKcKqkvhVFwpq8KecjkH%2FFSWy6SFKOWVC447162YI3mNXtfxcs3xctf0ikm3aY0XeVTkhQ%2B2TivyRto7Tml0ROmN4xoh1frWPKUXk%2F42AcUFuA82vVyVP2BT0ZgQq5xISDi5%2BCovt58h5HwIzjqcVWn&X-Amz-Signature=5f2778820d04f2cd94843617015f0cf37727d127dc80a8098c24631aebf924e4&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QKST74FI%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T191908Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGsaCXVzLXdlc3QtMiJHMEUCIEabKIy9v7Ahs%2F1%2BrH0OWdhPx%2BtoyRdVaacsfy6VLqszAiEAqjVnRNEBTgx57Az6yRzI3rnD%2FW5%2BHEnvOcTEAi5fnBwqiAQIlP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDAqs8K9Lsr24w6vx4ircA7OCXpg1LsJ3c29FP%2FYV7phd%2BQBNK3t8TTvz1ngc%2BGoDEDxFuGawjBh%2BZ17fwtx%2Bp0elfmT4OnLPwms7RmyYcc13Q29JAZB5iMtDepg8e7tvqP8FLjswzSOg2wiO9GCGbg8W8pYTYG%2BYY%2B4m2eM2dOIvFQkkagm4TEOY0s3wrApuN9DbDvdWz9AdlA1%2F%2FbpFftMOKcKRGQ2Mh3cymd4S%2FLR8r3UtjEOC%2BF%2BJ2uD7s4Yx2Q4IHyQD%2Bg6bHRxB7YnfYG6IEo0D3VYAX%2BZx3sJb7MYlYrPHdKQX2JbIPrgsWXKrVY4fqNshQih6fx0nqmlVa5JMsJrBf150037%2FvImb6iDjulzjITYFbYRWg2%2FCwHdOLsuMZGKcfa60Vx%2FTVFu5ugIDmvrTnZJxErmADs53p0ZP%2FiDFwyGb779TnVxL6CNSElEmvh7I9hI2jcwdiQHeDBF1kyTW6MQPrF%2FUNL8HP4Ad9yN5s%2BKDZD0GJW0pqYREfcC1ICFg0me6mucLnjvOiZHhXpYzB2oxyykQnKElYGguiSEwbhNuInH7z%2BGHlXoSCZRS30UZf%2FZSsK6rUVoiPg8sd1l8kh5juFh8M5kjmNn22jv%2FuQ5YR%2B1onsfRRKVtFZ56G63zT9y6YTVfMLq5070GOqUBhIXuwp6r7wCg6Kkoy0K2%2BwU4V%2BpWV0tn4O2J1%2Bqb4X87rI0yQvMKcwFuNo9%2FbfmrcwCb7CKcKqkvhVFwpq8KecjkH%2FFSWy6SFKOWVC447162YI3mNXtfxcs3xctf0ikm3aY0XeVTkhQ%2B2TivyRto7Tml0ROmN4xoh1frWPKUXk%2F42AcUFuA82vVyVP2BT0ZgQq5xISDi5%2BCovt58h5HwIzjqcVWn&X-Amz-Signature=5630312cd823cc67ecc91a5fb59c79615e157d018a7bf30a2f6a181cfbe53f2c&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YD6XQOUS%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T191908Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGwaCXVzLXdlc3QtMiJIMEYCIQC058GQSmR%2FgEnWEALQCL8Nf%2Bjj5t93P9cKMk2v7b4pQQIhAIaBZnrN5CWRkF%2FwS2KAXnNhVSadzC76ct%2Bd7VsrxwCtKogECJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzZYwml%2BIXmnWHMudQq3APRHVTE5pbbBTkSE1Xpfyzc9oodbAbWQuG8Z2DILMg4IKLqdy6QHSOwy1oyyQkvahnC1ZtoGdWPhyRP4l7YZ4o0NBRVN%2BTi5934w4AV5weE9b2jsofhHICf2HVf6QWNidYS8TIxaShT4Kb8i0fpqZfay59HbxocpDGdt%2B6VOB%2Bkr9tg9Gze%2Bj66PMBhDlVxVMTUErmYePlTEDLgE7erHo54tExolz7jZLbFjUgBWjCOfhHz%2FOOttxIUut1aDhAlix4xHW0WAL556%2B1dnjuj2dyp1eMfMetjU2c9lmskybB5fm25n8yVYT6JqJo1GTEjTLgmX7z3yyYP3IL6V62Gfj5uLGGIivYComkP8ZxdUABE4kEZXzISArjeS%2FeGNgO5DQVaH8T6Tb%2F2%2BdRrUsG6l6bOjZ24yI0NBn%2Fra2M%2Bg6EakbD2HpAwlVoFPwXKY09dTxScXjAnYZfw3btpcQK3fMAK1nz7fMNsElo9JpoBotGPlwcAOE4NVH6FzM3g0sP1IrLQRr8hqvEtsY%2FxQBehegrsM6xkWSUI9rze%2F2%2Fht%2FLAKTdM42lyFRMLPHE3M7SIsZSGZej%2F6w3y9hqGjV46SVDZJRO4CMdvESUv3z9e9F5TUMqEivKwFCQoXGETPDDsudO9BjqkAei44cMQ%2Fv0QfR4IVaxucwQKGHDJR39fgJ1JODl2ZQ7Sw3SxZokAW6aD9QC0ULuxeRLaeAHIppLOw2zCc7DEg1LL1fUfoDRw5fyyy5uNCl7wtj9yC8z3IIZxIzWW5YwjR69tGfJgoundxOEWeGwYWXE%2FOWSIFcoxeYYsGo4JffrCi3dPHsIUBoZ6j%2ByNHgGI1a3q27IfWw06ekidnlqWocUAnqeB&X-Amz-Signature=19be903c61a47c050cd1759910c3714e3d100ebb4e95cd2c26d7fd7471fc269d&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663CMKFYV2%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T191909Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGoaCXVzLXdlc3QtMiJHMEUCICq4WN9FyXLuRrzhNgb71%2FNpiVbG7nfZZGzrz%2BtWaSZlAiEA4EycFf%2FqpPIOQ%2BRKTtGOPSIsUV37Mw63h%2BhlIgoxXNEqiAQIk%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDK5zVHYmvXUOhO1FyCrcA5lsZ1GJ9ITK7TOZfPWwgb8Qn3rnAOkp4supiNzdod%2FMMg4g7dPRW1qs0cHI3KsIWqSpk%2BPBFsnsbvm%2FIPWWfGpmBc42q5vFW0cs5UWo5vC2Nf6o6AMEIXEWHsQnBfySL3YMn8YnjF%2FdsHmyCfVzYpeFkcsamoWl0V2kRbw36EU0h302xovIbW2RDEiL1eKYABNY9q6cxYcP%2BJvKnDKJcR7DsCJ5s6IUc%2BkXUZ3e45swpOwyVFTJBdwsGJFY600MQxZTg0sJZoRJRInuLV5%2F%2FpWBDe%2BicG2wvWoYBj5wNZGhI3qlbbWieo0K21LFqaF8%2FYcUDrwncoypHzkUFf4MLV6bGZnoIFAbzJB3wxJSr0aFBVjh%2BvvDvSFPZqS1zjTcuhPnQkk3T2SjSX9%2FyFdDKsMZXvWXGPRJ%2BTTAd1uQV9F0gNxRrESp0crpobwlJtGROgLQqrQJlUuUX2%2Bk%2BFWaPwwMt15DlA5xBOkNyHnCNgeFJojZI1xq%2FjPOWegXDh2xUkcUEMWQBulWv8wKY3ahnz0R%2BtIaeQc8tCQevKWhD%2BD2cYEKOWjbu1OxiQLaAoZFGAXt%2BjUhCDELyLO5KqD2yGWvnKzVJ6qAc9uMQuf2Ae8SfyYA49DarqAxoTv9MOia070GOqUB%2B60zfGd2wRHYMfYoDmZSDUSRXNhm1WWcHjtUZvvhWR%2Bwnusbnwl3L6826hv2Mgpu7B6ra%2BhxyGC062LGRYybjP%2F7NY%2BBG%2F5OqzKl%2Fmc3%2BwPlaQ%2FclLvcE4KyBuhjgRdEctdSSeAzc%2BoOFfMPXqUNQrsK0gV2m%2F62aw0Sh1BIoJHg2bVIGqGZu0MdqN29u3zj%2Faaoo6RnYklKdHHmEFHWR7Mysu7C&X-Amz-Signature=68f1bc8f30f4ad3f94d8c2b005bdc0dae9cd6578f7386209a7b230199a632c2c&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QKST74FI%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T191908Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGsaCXVzLXdlc3QtMiJHMEUCIEabKIy9v7Ahs%2F1%2BrH0OWdhPx%2BtoyRdVaacsfy6VLqszAiEAqjVnRNEBTgx57Az6yRzI3rnD%2FW5%2BHEnvOcTEAi5fnBwqiAQIlP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDAqs8K9Lsr24w6vx4ircA7OCXpg1LsJ3c29FP%2FYV7phd%2BQBNK3t8TTvz1ngc%2BGoDEDxFuGawjBh%2BZ17fwtx%2Bp0elfmT4OnLPwms7RmyYcc13Q29JAZB5iMtDepg8e7tvqP8FLjswzSOg2wiO9GCGbg8W8pYTYG%2BYY%2B4m2eM2dOIvFQkkagm4TEOY0s3wrApuN9DbDvdWz9AdlA1%2F%2FbpFftMOKcKRGQ2Mh3cymd4S%2FLR8r3UtjEOC%2BF%2BJ2uD7s4Yx2Q4IHyQD%2Bg6bHRxB7YnfYG6IEo0D3VYAX%2BZx3sJb7MYlYrPHdKQX2JbIPrgsWXKrVY4fqNshQih6fx0nqmlVa5JMsJrBf150037%2FvImb6iDjulzjITYFbYRWg2%2FCwHdOLsuMZGKcfa60Vx%2FTVFu5ugIDmvrTnZJxErmADs53p0ZP%2FiDFwyGb779TnVxL6CNSElEmvh7I9hI2jcwdiQHeDBF1kyTW6MQPrF%2FUNL8HP4Ad9yN5s%2BKDZD0GJW0pqYREfcC1ICFg0me6mucLnjvOiZHhXpYzB2oxyykQnKElYGguiSEwbhNuInH7z%2BGHlXoSCZRS30UZf%2FZSsK6rUVoiPg8sd1l8kh5juFh8M5kjmNn22jv%2FuQ5YR%2B1onsfRRKVtFZ56G63zT9y6YTVfMLq5070GOqUBhIXuwp6r7wCg6Kkoy0K2%2BwU4V%2BpWV0tn4O2J1%2Bqb4X87rI0yQvMKcwFuNo9%2FbfmrcwCb7CKcKqkvhVFwpq8KecjkH%2FFSWy6SFKOWVC447162YI3mNXtfxcs3xctf0ikm3aY0XeVTkhQ%2B2TivyRto7Tml0ROmN4xoh1frWPKUXk%2F42AcUFuA82vVyVP2BT0ZgQq5xISDi5%2BCovt58h5HwIzjqcVWn&X-Amz-Signature=57b2e1f4d9d219639b1cbbeaaa8c661ab6ccab3aa5705f4fc672c2a68e5c7ac0&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QKST74FI%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T191908Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGsaCXVzLXdlc3QtMiJHMEUCIEabKIy9v7Ahs%2F1%2BrH0OWdhPx%2BtoyRdVaacsfy6VLqszAiEAqjVnRNEBTgx57Az6yRzI3rnD%2FW5%2BHEnvOcTEAi5fnBwqiAQIlP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDAqs8K9Lsr24w6vx4ircA7OCXpg1LsJ3c29FP%2FYV7phd%2BQBNK3t8TTvz1ngc%2BGoDEDxFuGawjBh%2BZ17fwtx%2Bp0elfmT4OnLPwms7RmyYcc13Q29JAZB5iMtDepg8e7tvqP8FLjswzSOg2wiO9GCGbg8W8pYTYG%2BYY%2B4m2eM2dOIvFQkkagm4TEOY0s3wrApuN9DbDvdWz9AdlA1%2F%2FbpFftMOKcKRGQ2Mh3cymd4S%2FLR8r3UtjEOC%2BF%2BJ2uD7s4Yx2Q4IHyQD%2Bg6bHRxB7YnfYG6IEo0D3VYAX%2BZx3sJb7MYlYrPHdKQX2JbIPrgsWXKrVY4fqNshQih6fx0nqmlVa5JMsJrBf150037%2FvImb6iDjulzjITYFbYRWg2%2FCwHdOLsuMZGKcfa60Vx%2FTVFu5ugIDmvrTnZJxErmADs53p0ZP%2FiDFwyGb779TnVxL6CNSElEmvh7I9hI2jcwdiQHeDBF1kyTW6MQPrF%2FUNL8HP4Ad9yN5s%2BKDZD0GJW0pqYREfcC1ICFg0me6mucLnjvOiZHhXpYzB2oxyykQnKElYGguiSEwbhNuInH7z%2BGHlXoSCZRS30UZf%2FZSsK6rUVoiPg8sd1l8kh5juFh8M5kjmNn22jv%2FuQ5YR%2B1onsfRRKVtFZ56G63zT9y6YTVfMLq5070GOqUBhIXuwp6r7wCg6Kkoy0K2%2BwU4V%2BpWV0tn4O2J1%2Bqb4X87rI0yQvMKcwFuNo9%2FbfmrcwCb7CKcKqkvhVFwpq8KecjkH%2FFSWy6SFKOWVC447162YI3mNXtfxcs3xctf0ikm3aY0XeVTkhQ%2B2TivyRto7Tml0ROmN4xoh1frWPKUXk%2F42AcUFuA82vVyVP2BT0ZgQq5xISDi5%2BCovt58h5HwIzjqcVWn&X-Amz-Signature=bcefd9d7491f1392bfa4f52d604811c0ae2b7c11ba72c825b14fee6932c1cbfb&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QKST74FI%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T191908Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGsaCXVzLXdlc3QtMiJHMEUCIEabKIy9v7Ahs%2F1%2BrH0OWdhPx%2BtoyRdVaacsfy6VLqszAiEAqjVnRNEBTgx57Az6yRzI3rnD%2FW5%2BHEnvOcTEAi5fnBwqiAQIlP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDAqs8K9Lsr24w6vx4ircA7OCXpg1LsJ3c29FP%2FYV7phd%2BQBNK3t8TTvz1ngc%2BGoDEDxFuGawjBh%2BZ17fwtx%2Bp0elfmT4OnLPwms7RmyYcc13Q29JAZB5iMtDepg8e7tvqP8FLjswzSOg2wiO9GCGbg8W8pYTYG%2BYY%2B4m2eM2dOIvFQkkagm4TEOY0s3wrApuN9DbDvdWz9AdlA1%2F%2FbpFftMOKcKRGQ2Mh3cymd4S%2FLR8r3UtjEOC%2BF%2BJ2uD7s4Yx2Q4IHyQD%2Bg6bHRxB7YnfYG6IEo0D3VYAX%2BZx3sJb7MYlYrPHdKQX2JbIPrgsWXKrVY4fqNshQih6fx0nqmlVa5JMsJrBf150037%2FvImb6iDjulzjITYFbYRWg2%2FCwHdOLsuMZGKcfa60Vx%2FTVFu5ugIDmvrTnZJxErmADs53p0ZP%2FiDFwyGb779TnVxL6CNSElEmvh7I9hI2jcwdiQHeDBF1kyTW6MQPrF%2FUNL8HP4Ad9yN5s%2BKDZD0GJW0pqYREfcC1ICFg0me6mucLnjvOiZHhXpYzB2oxyykQnKElYGguiSEwbhNuInH7z%2BGHlXoSCZRS30UZf%2FZSsK6rUVoiPg8sd1l8kh5juFh8M5kjmNn22jv%2FuQ5YR%2B1onsfRRKVtFZ56G63zT9y6YTVfMLq5070GOqUBhIXuwp6r7wCg6Kkoy0K2%2BwU4V%2BpWV0tn4O2J1%2Bqb4X87rI0yQvMKcwFuNo9%2FbfmrcwCb7CKcKqkvhVFwpq8KecjkH%2FFSWy6SFKOWVC447162YI3mNXtfxcs3xctf0ikm3aY0XeVTkhQ%2B2TivyRto7Tml0ROmN4xoh1frWPKUXk%2F42AcUFuA82vVyVP2BT0ZgQq5xISDi5%2BCovt58h5HwIzjqcVWn&X-Amz-Signature=e2577dc5a9cd193203ef8181e6a13e872027b7aceee0856aedd4afe07d07910d&X-Amz-SignedHeaders=host&x-id=GetObject)


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

