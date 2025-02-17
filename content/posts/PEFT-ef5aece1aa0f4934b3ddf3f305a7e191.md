---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4666QMS6WFH%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250217T112053Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEEkaCXVzLXdlc3QtMiJHMEUCIEFLgTzRAkXQ1%2BqESyObJEqwdqEd9gilePTlkMlfIf4aAiEAw\
  AxH1jKiEWeveSsv5J0Z7YMTB80ZqVOTOD58VekJK98q%2FwMIchAAGgw2Mzc0MjMxODM4MDUiDF%2\
  BIA8JQbzRGYj7iLSrcAymN84yOeWJhnoeTC56r3HNQA8SfZCR9otXNdl8PwaV7Mz1p4m7Yev7QfVn\
  gyS707ocZbXddeHT5gPG57QOjoiYH3HMh5z%2Btjilo35OvUdpfzfUeZBNAGK%2B5%2BWUTU7YnMQ\
  ISQAzOLgd0v6bWi8%2BPG3SQ%2BfCqeO1l0Cj88KQv7PVGNrFYPx0KnJmjgqU3m64JYwdjtgjqroo\
  OmdAOMdMOvDwCXByHWmgGz2sIndAIGhphhYDnNuJ9OEunUBYmuvIoIViu%2Fr82fLqtoxP526a5xb\
  wqrvh8rF%2BT4%2BTy7rKjrT%2BTodw4PfZ4vGjRpF%2FgnmKxQkuX8v%2BVv2htFin8pqOZ%2BfW\
  NNm9sENkbuD%2FJzMCg0qd5ZlwmzGmuHyYEFD515QUSbeMpydGI1fZnIN49BF7zuMslTF%2BX48M9\
  NJYGIqOPrtllWPXIortn5R3vPs%2B%2BEwHtJeBtfk032jiq1kqJb9SH7csYIqiWhCkYsyiaMoTnP\
  urIjxMZpDHn6fqKoK7TNY7uRMjTP%2BluRh8UMAEJFj%2F1nMjvp6hn7iUuhsQPcdzgLYBz2PDohd\
  %2FpfgTKU3xAGjZvFNSGxFxCP5aRuTnWiEqm1XVXdj76%2FrUVq2R4De83TCJ5gzzxF2FMLEiNHqN\
  PMK7qy70GOqUBgAHLPcwY22Wck%2FtCwDU87nahWeDFsMMrA19tg0aKfERlFO68w7BjgJTC%2Fwbg\
  0rh4tgfkwWoHcA1mWfDVr8KTmiIus%2FsXCkvrIRMgvFYiPZe3m2J9476Ir938GYTP4hnJs44TF85\
  lnayJWk72hBXF8o%2Fs0EoETavwiJgfjewOo4n%2FnRUDHNRMWz4Lvb1QiqgHfBX18gQDh7zTSNvm\
  ylhx%2Ffj%2FKyuM&X-Amz-Signature=4123d14254d5f7229d6b8a1619f8a8120b543303883e\
  95f8315eaf7ed3fe8e3a&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4663Q2U6ACC%2F20250217%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250217T111916Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEEkaCXVzLXdlc3QtMiJHMEUCIHl1zA4fCKE%2FQ5DOT8JepmNVSG806\
        yDxq0l2tUavFFX6AiEAmAAqGmYwp1HxMk0XDIweSGldCfTVr4QJZDMM7LulMsQq%2FwMIch\
        AAGgw2Mzc0MjMxODM4MDUiDA7bgstgEKf21jnOICrcA7vbwNAs16h5cJ%2F%2BBIL8%2FbA\
        LWH7rmPxI8w9uhSoAsT8e%2BmSqr9hfKu9N0q7PlFjT9fWR739JmGdM0orxoBXLsq4yPpF%\
        2BxougT8B6fgew5j13qW7cdzI3KC1hLuAm90JWs2lIeRYjXS3L36oNEKyUaFpTijfwZAh%2\
        FpShuzftUp%2FCLyCk891Aiju%2FEe4M1QY7lRydRdBOP3yzScy%2Fpl1TR%2FsTVnvTBR9\
        kxTIvW5ochlbClQ8NB7fPH91ww0w3sqLFG%2F8Jq7fS4XEC8tQ3kzQHPEviJ8KpRUya1u84\
        HjHUiliaY1CAIh%2BhoYeVLbLlhfbnjBIj8r5TCdh0t3TFFdlvCX5IdREubcE3cLTe2psHs\
        7kRPiaGwFrMIGRSUvYsP4WZwAMSmqR4xzyXS0JEvtmZ4OjcEI%2FrC1KcXluWjJBg241jBj\
        QMAa3KCMGjs2zARvxH3UqIV2HWJNG06yCAIXwtwXT7ef5eJetni95iKA0LR7O2t2nlEIt%2\
        FFuVnWkzphgA%2FM0IWntDyrabloAch93tMF5f%2FPW%2BWa%2FmsI8L7lGgQ66ZLNmWJih\
        7FXT2HfOtCWhNhUQM7KSiopDzYErroM%2B0JWBOgm6NWaoyl5nn5OJT4uI4lI2q074aHh%2\
        Fc%2Fnlt%2BSMMfpy70GOqUBFYIWJrx3s8WkyTh38HIYVOkowAHn7caoYU4PUukpOSIm7%2\
        BIt%2BqJ3X%2FZhqBfszgyfDTmof6QiSrb78gWrdKRcvdT%2BzQIGEMluF1TB%2Ff8xhPh6\
        ealn4hQXXfSj5zOMk%2FufLNNRGFDH9KL8Z0TyHDURuaMiMyDljoRxJWX1n%2FAT8aCubiy\
        5uDC50IvCBHYuDi8tzHS8nKeebGiqUTxLC8LDoz7v%2F5jp&X-Amz-Signature=4fa1c59\
        cd55f1ad11f41e836053d1e9db39d594969f1bb99b8e36d7fe8909cfe&X-Amz-SignedH\
        eaders=host&x-id=GetObject"
      expiry_time: "2025-02-17T12:19:16.457Z"
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
UPDATE_TIME: "2025-02-17T11:20:57.852Z"
EXPIRY_TIME: "2025-02-17T12:20:50.822Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664AFY6B3Z%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T112051Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEkaCXVzLXdlc3QtMiJHMEUCIQCH9SmoUxipWUqjxwX5VfRgY%2Fl%2BB12mG84huluAyBGRrQIgPQ1jkA9Pu3zUtMz91k7WMC%2Bm4qrVuzVlKApopsDsmFQq%2FwMIchAAGgw2Mzc0MjMxODM4MDUiDDCjX5uG6BudWIjzmyrcA3Qcsuw4V5rZqraOLbiNfTw%2FrvYZ0qRjZ8V%2FE6c31Jj8q0H14GXy7gcOlJRxgK7i%2Bfq4Yr80JA9hMUOn5G7eFa%2FD90vdRdG0Tm0WDZVat8Hfarb%2BIoTG0h4e%2Fbf6vWjF%2Fl5a1vr0HxSU5eip2D2QguHkaPoCfIoO5K7pZlcggoAYCVOXSDgJM5cgeCEgIFPiC1yH%2BoccZEw53wiEbFMP4iEa7iXO2lsvNjNsBGS1sxVplVUiOthk2E90%2FPk1m7hkVn3vo111qJSIKsXGjwkbq9qNp1ghpZDrfqxqyAEVMRXrAIw%2BNj0fvHohmhaHABuUNneokAsBLR3jLVMaGvc2k4Yhvqena%2Fm5fKp29FcGgiR6az3rX%2FNa%2BIdooOOFj3OrcGoOhiP6XYVix4ick6uq1hL2ib1vsKn68iP4oRKgBBLXw7X3AlXL580A847XEtwdxIVHpLy2W%2FOtZce5m%2B5Z6NQtljvis%2FhdvTEejVv%2BJc1U8UvsenJeOgJ39rRUqklS3TXGxHE0X%2FasSxfS%2Fvq%2ByoIWSTY%2Bcn8P7ISI%2FvWYW6pV%2F8Tgjib2LrfKobOJ68rPK5D7FrIiZBXRuHFKqWCRZb82a4OY1K2Hz0LOweMfM1H18e1VBXUuGXvcLTJXMMnpy70GOqUBXcZIR2%2BuGkWnaOMw70T5m0FC5V6ewuoHJQ6xIQfW6A%2BFL%2BmBMB9556NeZUN9gy6nWREoF%2BzfLHhsNgBfgQuzVO8%2BpwFEsdZ5vDvs4a%2FMOkTPE3eSgBVV5x%2FV5TzSfiSBu9T8J%2FEhhYV46%2BfhaihLotDvdP0%2B%2FgDeGEZY5356CcrnGTYRf9PsJs0GtLwgF%2BqxEEDxogViAJZ7fzHGilkBCMtu03CR&X-Amz-Signature=9ce8e151d21c3fd09de7a1429f34f4c5f36de794172fdee9214e120d57654e76&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664AFY6B3Z%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T112051Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEkaCXVzLXdlc3QtMiJHMEUCIQCH9SmoUxipWUqjxwX5VfRgY%2Fl%2BB12mG84huluAyBGRrQIgPQ1jkA9Pu3zUtMz91k7WMC%2Bm4qrVuzVlKApopsDsmFQq%2FwMIchAAGgw2Mzc0MjMxODM4MDUiDDCjX5uG6BudWIjzmyrcA3Qcsuw4V5rZqraOLbiNfTw%2FrvYZ0qRjZ8V%2FE6c31Jj8q0H14GXy7gcOlJRxgK7i%2Bfq4Yr80JA9hMUOn5G7eFa%2FD90vdRdG0Tm0WDZVat8Hfarb%2BIoTG0h4e%2Fbf6vWjF%2Fl5a1vr0HxSU5eip2D2QguHkaPoCfIoO5K7pZlcggoAYCVOXSDgJM5cgeCEgIFPiC1yH%2BoccZEw53wiEbFMP4iEa7iXO2lsvNjNsBGS1sxVplVUiOthk2E90%2FPk1m7hkVn3vo111qJSIKsXGjwkbq9qNp1ghpZDrfqxqyAEVMRXrAIw%2BNj0fvHohmhaHABuUNneokAsBLR3jLVMaGvc2k4Yhvqena%2Fm5fKp29FcGgiR6az3rX%2FNa%2BIdooOOFj3OrcGoOhiP6XYVix4ick6uq1hL2ib1vsKn68iP4oRKgBBLXw7X3AlXL580A847XEtwdxIVHpLy2W%2FOtZce5m%2B5Z6NQtljvis%2FhdvTEejVv%2BJc1U8UvsenJeOgJ39rRUqklS3TXGxHE0X%2FasSxfS%2Fvq%2ByoIWSTY%2Bcn8P7ISI%2FvWYW6pV%2F8Tgjib2LrfKobOJ68rPK5D7FrIiZBXRuHFKqWCRZb82a4OY1K2Hz0LOweMfM1H18e1VBXUuGXvcLTJXMMnpy70GOqUBXcZIR2%2BuGkWnaOMw70T5m0FC5V6ewuoHJQ6xIQfW6A%2BFL%2BmBMB9556NeZUN9gy6nWREoF%2BzfLHhsNgBfgQuzVO8%2BpwFEsdZ5vDvs4a%2FMOkTPE3eSgBVV5x%2FV5TzSfiSBu9T8J%2FEhhYV46%2BfhaihLotDvdP0%2B%2FgDeGEZY5356CcrnGTYRf9PsJs0GtLwgF%2BqxEEDxogViAJZ7fzHGilkBCMtu03CR&X-Amz-Signature=95d6086c93c43392bae69d2b1aed2f679afef10ba2e0a0bdff44a0b6bff64763&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664AFY6B3Z%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T112051Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEkaCXVzLXdlc3QtMiJHMEUCIQCH9SmoUxipWUqjxwX5VfRgY%2Fl%2BB12mG84huluAyBGRrQIgPQ1jkA9Pu3zUtMz91k7WMC%2Bm4qrVuzVlKApopsDsmFQq%2FwMIchAAGgw2Mzc0MjMxODM4MDUiDDCjX5uG6BudWIjzmyrcA3Qcsuw4V5rZqraOLbiNfTw%2FrvYZ0qRjZ8V%2FE6c31Jj8q0H14GXy7gcOlJRxgK7i%2Bfq4Yr80JA9hMUOn5G7eFa%2FD90vdRdG0Tm0WDZVat8Hfarb%2BIoTG0h4e%2Fbf6vWjF%2Fl5a1vr0HxSU5eip2D2QguHkaPoCfIoO5K7pZlcggoAYCVOXSDgJM5cgeCEgIFPiC1yH%2BoccZEw53wiEbFMP4iEa7iXO2lsvNjNsBGS1sxVplVUiOthk2E90%2FPk1m7hkVn3vo111qJSIKsXGjwkbq9qNp1ghpZDrfqxqyAEVMRXrAIw%2BNj0fvHohmhaHABuUNneokAsBLR3jLVMaGvc2k4Yhvqena%2Fm5fKp29FcGgiR6az3rX%2FNa%2BIdooOOFj3OrcGoOhiP6XYVix4ick6uq1hL2ib1vsKn68iP4oRKgBBLXw7X3AlXL580A847XEtwdxIVHpLy2W%2FOtZce5m%2B5Z6NQtljvis%2FhdvTEejVv%2BJc1U8UvsenJeOgJ39rRUqklS3TXGxHE0X%2FasSxfS%2Fvq%2ByoIWSTY%2Bcn8P7ISI%2FvWYW6pV%2F8Tgjib2LrfKobOJ68rPK5D7FrIiZBXRuHFKqWCRZb82a4OY1K2Hz0LOweMfM1H18e1VBXUuGXvcLTJXMMnpy70GOqUBXcZIR2%2BuGkWnaOMw70T5m0FC5V6ewuoHJQ6xIQfW6A%2BFL%2BmBMB9556NeZUN9gy6nWREoF%2BzfLHhsNgBfgQuzVO8%2BpwFEsdZ5vDvs4a%2FMOkTPE3eSgBVV5x%2FV5TzSfiSBu9T8J%2FEhhYV46%2BfhaihLotDvdP0%2B%2FgDeGEZY5356CcrnGTYRf9PsJs0GtLwgF%2BqxEEDxogViAJZ7fzHGilkBCMtu03CR&X-Amz-Signature=1d3d65b01e3175d35b509890063a25d85cfa085cd2c12057c32f7b3dbcfbb00c&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664AFY6B3Z%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T112051Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEkaCXVzLXdlc3QtMiJHMEUCIQCH9SmoUxipWUqjxwX5VfRgY%2Fl%2BB12mG84huluAyBGRrQIgPQ1jkA9Pu3zUtMz91k7WMC%2Bm4qrVuzVlKApopsDsmFQq%2FwMIchAAGgw2Mzc0MjMxODM4MDUiDDCjX5uG6BudWIjzmyrcA3Qcsuw4V5rZqraOLbiNfTw%2FrvYZ0qRjZ8V%2FE6c31Jj8q0H14GXy7gcOlJRxgK7i%2Bfq4Yr80JA9hMUOn5G7eFa%2FD90vdRdG0Tm0WDZVat8Hfarb%2BIoTG0h4e%2Fbf6vWjF%2Fl5a1vr0HxSU5eip2D2QguHkaPoCfIoO5K7pZlcggoAYCVOXSDgJM5cgeCEgIFPiC1yH%2BoccZEw53wiEbFMP4iEa7iXO2lsvNjNsBGS1sxVplVUiOthk2E90%2FPk1m7hkVn3vo111qJSIKsXGjwkbq9qNp1ghpZDrfqxqyAEVMRXrAIw%2BNj0fvHohmhaHABuUNneokAsBLR3jLVMaGvc2k4Yhvqena%2Fm5fKp29FcGgiR6az3rX%2FNa%2BIdooOOFj3OrcGoOhiP6XYVix4ick6uq1hL2ib1vsKn68iP4oRKgBBLXw7X3AlXL580A847XEtwdxIVHpLy2W%2FOtZce5m%2B5Z6NQtljvis%2FhdvTEejVv%2BJc1U8UvsenJeOgJ39rRUqklS3TXGxHE0X%2FasSxfS%2Fvq%2ByoIWSTY%2Bcn8P7ISI%2FvWYW6pV%2F8Tgjib2LrfKobOJ68rPK5D7FrIiZBXRuHFKqWCRZb82a4OY1K2Hz0LOweMfM1H18e1VBXUuGXvcLTJXMMnpy70GOqUBXcZIR2%2BuGkWnaOMw70T5m0FC5V6ewuoHJQ6xIQfW6A%2BFL%2BmBMB9556NeZUN9gy6nWREoF%2BzfLHhsNgBfgQuzVO8%2BpwFEsdZ5vDvs4a%2FMOkTPE3eSgBVV5x%2FV5TzSfiSBu9T8J%2FEhhYV46%2BfhaihLotDvdP0%2B%2FgDeGEZY5356CcrnGTYRf9PsJs0GtLwgF%2BqxEEDxogViAJZ7fzHGilkBCMtu03CR&X-Amz-Signature=b2fa5482a13af2aa25356c94bd54a6e67a3b2a5d60facdc082d6de3224b880bc&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664AFY6B3Z%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T112051Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEkaCXVzLXdlc3QtMiJHMEUCIQCH9SmoUxipWUqjxwX5VfRgY%2Fl%2BB12mG84huluAyBGRrQIgPQ1jkA9Pu3zUtMz91k7WMC%2Bm4qrVuzVlKApopsDsmFQq%2FwMIchAAGgw2Mzc0MjMxODM4MDUiDDCjX5uG6BudWIjzmyrcA3Qcsuw4V5rZqraOLbiNfTw%2FrvYZ0qRjZ8V%2FE6c31Jj8q0H14GXy7gcOlJRxgK7i%2Bfq4Yr80JA9hMUOn5G7eFa%2FD90vdRdG0Tm0WDZVat8Hfarb%2BIoTG0h4e%2Fbf6vWjF%2Fl5a1vr0HxSU5eip2D2QguHkaPoCfIoO5K7pZlcggoAYCVOXSDgJM5cgeCEgIFPiC1yH%2BoccZEw53wiEbFMP4iEa7iXO2lsvNjNsBGS1sxVplVUiOthk2E90%2FPk1m7hkVn3vo111qJSIKsXGjwkbq9qNp1ghpZDrfqxqyAEVMRXrAIw%2BNj0fvHohmhaHABuUNneokAsBLR3jLVMaGvc2k4Yhvqena%2Fm5fKp29FcGgiR6az3rX%2FNa%2BIdooOOFj3OrcGoOhiP6XYVix4ick6uq1hL2ib1vsKn68iP4oRKgBBLXw7X3AlXL580A847XEtwdxIVHpLy2W%2FOtZce5m%2B5Z6NQtljvis%2FhdvTEejVv%2BJc1U8UvsenJeOgJ39rRUqklS3TXGxHE0X%2FasSxfS%2Fvq%2ByoIWSTY%2Bcn8P7ISI%2FvWYW6pV%2F8Tgjib2LrfKobOJ68rPK5D7FrIiZBXRuHFKqWCRZb82a4OY1K2Hz0LOweMfM1H18e1VBXUuGXvcLTJXMMnpy70GOqUBXcZIR2%2BuGkWnaOMw70T5m0FC5V6ewuoHJQ6xIQfW6A%2BFL%2BmBMB9556NeZUN9gy6nWREoF%2BzfLHhsNgBfgQuzVO8%2BpwFEsdZ5vDvs4a%2FMOkTPE3eSgBVV5x%2FV5TzSfiSBu9T8J%2FEhhYV46%2BfhaihLotDvdP0%2B%2FgDeGEZY5356CcrnGTYRf9PsJs0GtLwgF%2BqxEEDxogViAJZ7fzHGilkBCMtu03CR&X-Amz-Signature=13fbc5cf98af02f4ba7cf252f0bd329d65b8193dc926fd232fe8373a27733624&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662Z4JIOF6%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T112052Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEkaCXVzLXdlc3QtMiJHMEUCIFpaWjrVVSCLIe%2BD4xNTt3%2BvlZXCzkFD5M4z3BxproVoAiEA84ifwU75px6p0P7qW5gKtDEZxKoDcqSf%2F8cSt6hoN5sq%2FwMIchAAGgw2Mzc0MjMxODM4MDUiDLfHxichU22QRsw68ircAzeSq1ERytJn2flVMOEPbejtCo05ruZ49mi8rNZBXIhHLm0pQdrHrUrqQHYIQi4VMPMGHzH5paB4GGzZ6Eg%2Fdbf0eGVKJtJBvb1GYx5qVBYnMV8OVEg6Ww2VesSOGqFhiJMSV8L6%2FhDgSPNglZyhPJ3cR%2FYY4YJiOtILyRz4jrnT%2BJveg%2BOM%2BqczqHDbzQeiU2ihMQ0XP8tYo%2FxuOsW%2BFIZltkcY5Q%2B4jLuBrWsj2fVnG3TpT30r6LXcES0%2F0W0veVi5xo0uRJdLSiu8TyRpD9sScMpGQ2%2Fh1wmM5DBOtu%2BaRAI5HqWdIMrFEeWlFNlWMp9%2B8KU%2Byz3dEYXMhnGxeZyHKHKrhEW91Hsq1XjYXMnaYDTwL4nl5n8jntYnIG6kjRjS5GScoYY3IbLRaXHFjv3xdqiMhXCWuTLBNn2gXHxwLPxiDft7DJayk%2Bbcy1tkIk1XjWTzAygJK4mntEWjDnqrZNiNmkBoD1%2BIgMV%2FfVMFTz7mQ3qDTzlwz8kOR%2B1HP2urUALkty5cxuFNKoiwfopsgWcWCLycaY8rBpB2x3I2CsRr75MV4MePKQ5B0%2FoYAxP1T4liEacbZuzDfqhJ9ytEvBd0nlS9MN7LHvZYlON5w1rmrKigz5iyXyiyMO3py70GOqUBN4KIf%2FrhcxT%2FjPPsCI%2BICtxIJXQzhSKlS3Qk5lvB9iLywdSDmHFwEY6sWuu2gZLwFi1Bnt%2FMeYBatbTQX3x%2F5OPZjAyssAsnBFh65dH08tBoBw%2B2i%2BJAWYrrFphWY1LGrQjNJDj%2Bh9KxO%2BzuaVo%2BY%2F88DiwwjjjXgZZOQ%2FwCy0yFOfVZJUR02GGVuCezCHgNA2GZLiQvv62kI32%2BWEFqasMnXwSN&X-Amz-Signature=92f8948add015b3bd0efbe0418d85463f2bd5a377875d913902b6d104bf3b165&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SIEN4XJ2%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T112052Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEkaCXVzLXdlc3QtMiJIMEYCIQC3CB5qJQiAYGkwp0%2BNSY%2BxDcPzB4gGAghZ2NQYpdxF%2BgIhAILaoJ3Bc6fu%2BZqfPnXWEn54EYeUVU9%2BgiK2G6SzfaD3Kv8DCHIQABoMNjM3NDIzMTgzODA1IgyK7gZEwbjNvIynTkoq3ANATixlrIORSQQH5JSehpYQOIKr3K1yRmufCVNK2i0PFw0tjpS6bv7voMgPwFYczdvlLmlGM31gdJRrCmtbWVzWeGcg7avTg1mLTDGxojE%2FsL7i92wPuATukMVRh1Jx0zSr3jb6J2rTAFZhYwnUt5VI%2BIcHQ1auXbGPEJ83RyuGvf1vNtk1yWncQSMYQJUyolRxvkipDNXsYzxGiQAvIAQeLZkQM09vgOpWYMlEITeVBi9j%2Bn2uADp2pBf3DE8L%2F39v8ZE5dzmFSfxv7E2zNqeaMS92XcI7Ce5Egv5EDTqWVc1cJ9%2BvFgfpXTbqVDJ5WyCQD5vKyU2QgTWZpIqGoFCazTQGvnxPGHxJB0B2uWpq4e%2FRZaT4sSQCx9K86Zkgkr3CYewEXz6m3GKrtXVa6X3zfODVzXoKBxrJrA3QlG%2Bb3VBHO%2FwddknyXmxbgjG%2Fp7SrUo9lDzTJtcSppHyApzIY4EvyL2XBPqr0OXi5pXNTo1PS0wPOgfT7Y05WLCVz%2FEbU%2FLe9EVvmTOw%2Bt3Vy3VYTe%2FrPhWkJM1iEz2LQLO3zt1FunIcoaV%2FrjRExbPxKSCw%2BVP75U9BmDOdeW326PRQr0XSiRTw8Uu%2BTypZp4ejVvXZ6ras8vvjgMEkEaDDR%2Bcu9BjqkARddBSxPECaXZCN1Q%2B5HqEIqnz63M6JNWzEx93zWDfGL3ArVLU0UR4w%2BJ%2BL5Zo%2FuNUt%2BYNCsbQpbUmqousyIZP6ECFR8KSGAPeRrb7tyxLOuGhVFMn3oG4JbrI3gsS3Blmh%2FPCMiUUERJTgffc3bWm4mQBoko0saNQ2V3CnH5B3WC4s9ml0fxbyu8hLkOM3iboq1vCeT7vI1oL%2BwsUgL3hBX2vEC&X-Amz-Signature=e8e4b529968dc9d838e27c1ff27a2430b1af5feeeef4d28171d7d7b37600ec08&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664AFY6B3Z%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T112051Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEkaCXVzLXdlc3QtMiJHMEUCIQCH9SmoUxipWUqjxwX5VfRgY%2Fl%2BB12mG84huluAyBGRrQIgPQ1jkA9Pu3zUtMz91k7WMC%2Bm4qrVuzVlKApopsDsmFQq%2FwMIchAAGgw2Mzc0MjMxODM4MDUiDDCjX5uG6BudWIjzmyrcA3Qcsuw4V5rZqraOLbiNfTw%2FrvYZ0qRjZ8V%2FE6c31Jj8q0H14GXy7gcOlJRxgK7i%2Bfq4Yr80JA9hMUOn5G7eFa%2FD90vdRdG0Tm0WDZVat8Hfarb%2BIoTG0h4e%2Fbf6vWjF%2Fl5a1vr0HxSU5eip2D2QguHkaPoCfIoO5K7pZlcggoAYCVOXSDgJM5cgeCEgIFPiC1yH%2BoccZEw53wiEbFMP4iEa7iXO2lsvNjNsBGS1sxVplVUiOthk2E90%2FPk1m7hkVn3vo111qJSIKsXGjwkbq9qNp1ghpZDrfqxqyAEVMRXrAIw%2BNj0fvHohmhaHABuUNneokAsBLR3jLVMaGvc2k4Yhvqena%2Fm5fKp29FcGgiR6az3rX%2FNa%2BIdooOOFj3OrcGoOhiP6XYVix4ick6uq1hL2ib1vsKn68iP4oRKgBBLXw7X3AlXL580A847XEtwdxIVHpLy2W%2FOtZce5m%2B5Z6NQtljvis%2FhdvTEejVv%2BJc1U8UvsenJeOgJ39rRUqklS3TXGxHE0X%2FasSxfS%2Fvq%2ByoIWSTY%2Bcn8P7ISI%2FvWYW6pV%2F8Tgjib2LrfKobOJ68rPK5D7FrIiZBXRuHFKqWCRZb82a4OY1K2Hz0LOweMfM1H18e1VBXUuGXvcLTJXMMnpy70GOqUBXcZIR2%2BuGkWnaOMw70T5m0FC5V6ewuoHJQ6xIQfW6A%2BFL%2BmBMB9556NeZUN9gy6nWREoF%2BzfLHhsNgBfgQuzVO8%2BpwFEsdZ5vDvs4a%2FMOkTPE3eSgBVV5x%2FV5TzSfiSBu9T8J%2FEhhYV46%2BfhaihLotDvdP0%2B%2FgDeGEZY5356CcrnGTYRf9PsJs0GtLwgF%2BqxEEDxogViAJZ7fzHGilkBCMtu03CR&X-Amz-Signature=85a9aafb269318c58594fc0ddd13119b814c5607ec0ce6129b92cd0e0846e18a&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664AFY6B3Z%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T112051Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEkaCXVzLXdlc3QtMiJHMEUCIQCH9SmoUxipWUqjxwX5VfRgY%2Fl%2BB12mG84huluAyBGRrQIgPQ1jkA9Pu3zUtMz91k7WMC%2Bm4qrVuzVlKApopsDsmFQq%2FwMIchAAGgw2Mzc0MjMxODM4MDUiDDCjX5uG6BudWIjzmyrcA3Qcsuw4V5rZqraOLbiNfTw%2FrvYZ0qRjZ8V%2FE6c31Jj8q0H14GXy7gcOlJRxgK7i%2Bfq4Yr80JA9hMUOn5G7eFa%2FD90vdRdG0Tm0WDZVat8Hfarb%2BIoTG0h4e%2Fbf6vWjF%2Fl5a1vr0HxSU5eip2D2QguHkaPoCfIoO5K7pZlcggoAYCVOXSDgJM5cgeCEgIFPiC1yH%2BoccZEw53wiEbFMP4iEa7iXO2lsvNjNsBGS1sxVplVUiOthk2E90%2FPk1m7hkVn3vo111qJSIKsXGjwkbq9qNp1ghpZDrfqxqyAEVMRXrAIw%2BNj0fvHohmhaHABuUNneokAsBLR3jLVMaGvc2k4Yhvqena%2Fm5fKp29FcGgiR6az3rX%2FNa%2BIdooOOFj3OrcGoOhiP6XYVix4ick6uq1hL2ib1vsKn68iP4oRKgBBLXw7X3AlXL580A847XEtwdxIVHpLy2W%2FOtZce5m%2B5Z6NQtljvis%2FhdvTEejVv%2BJc1U8UvsenJeOgJ39rRUqklS3TXGxHE0X%2FasSxfS%2Fvq%2ByoIWSTY%2Bcn8P7ISI%2FvWYW6pV%2F8Tgjib2LrfKobOJ68rPK5D7FrIiZBXRuHFKqWCRZb82a4OY1K2Hz0LOweMfM1H18e1VBXUuGXvcLTJXMMnpy70GOqUBXcZIR2%2BuGkWnaOMw70T5m0FC5V6ewuoHJQ6xIQfW6A%2BFL%2BmBMB9556NeZUN9gy6nWREoF%2BzfLHhsNgBfgQuzVO8%2BpwFEsdZ5vDvs4a%2FMOkTPE3eSgBVV5x%2FV5TzSfiSBu9T8J%2FEhhYV46%2BfhaihLotDvdP0%2B%2FgDeGEZY5356CcrnGTYRf9PsJs0GtLwgF%2BqxEEDxogViAJZ7fzHGilkBCMtu03CR&X-Amz-Signature=cd3072fa1a88229b040d91f8d01b038b5ee9b5d6e42c258e87c23bdc49864e17&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664AFY6B3Z%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T112051Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEkaCXVzLXdlc3QtMiJHMEUCIQCH9SmoUxipWUqjxwX5VfRgY%2Fl%2BB12mG84huluAyBGRrQIgPQ1jkA9Pu3zUtMz91k7WMC%2Bm4qrVuzVlKApopsDsmFQq%2FwMIchAAGgw2Mzc0MjMxODM4MDUiDDCjX5uG6BudWIjzmyrcA3Qcsuw4V5rZqraOLbiNfTw%2FrvYZ0qRjZ8V%2FE6c31Jj8q0H14GXy7gcOlJRxgK7i%2Bfq4Yr80JA9hMUOn5G7eFa%2FD90vdRdG0Tm0WDZVat8Hfarb%2BIoTG0h4e%2Fbf6vWjF%2Fl5a1vr0HxSU5eip2D2QguHkaPoCfIoO5K7pZlcggoAYCVOXSDgJM5cgeCEgIFPiC1yH%2BoccZEw53wiEbFMP4iEa7iXO2lsvNjNsBGS1sxVplVUiOthk2E90%2FPk1m7hkVn3vo111qJSIKsXGjwkbq9qNp1ghpZDrfqxqyAEVMRXrAIw%2BNj0fvHohmhaHABuUNneokAsBLR3jLVMaGvc2k4Yhvqena%2Fm5fKp29FcGgiR6az3rX%2FNa%2BIdooOOFj3OrcGoOhiP6XYVix4ick6uq1hL2ib1vsKn68iP4oRKgBBLXw7X3AlXL580A847XEtwdxIVHpLy2W%2FOtZce5m%2B5Z6NQtljvis%2FhdvTEejVv%2BJc1U8UvsenJeOgJ39rRUqklS3TXGxHE0X%2FasSxfS%2Fvq%2ByoIWSTY%2Bcn8P7ISI%2FvWYW6pV%2F8Tgjib2LrfKobOJ68rPK5D7FrIiZBXRuHFKqWCRZb82a4OY1K2Hz0LOweMfM1H18e1VBXUuGXvcLTJXMMnpy70GOqUBXcZIR2%2BuGkWnaOMw70T5m0FC5V6ewuoHJQ6xIQfW6A%2BFL%2BmBMB9556NeZUN9gy6nWREoF%2BzfLHhsNgBfgQuzVO8%2BpwFEsdZ5vDvs4a%2FMOkTPE3eSgBVV5x%2FV5TzSfiSBu9T8J%2FEhhYV46%2BfhaihLotDvdP0%2B%2FgDeGEZY5356CcrnGTYRf9PsJs0GtLwgF%2BqxEEDxogViAJZ7fzHGilkBCMtu03CR&X-Amz-Signature=d8b53f411c71515c506a283ace9be9593b0da9417ca25a65d9e128b746010822&X-Amz-SignedHeaders=host&x-id=GetObject)


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

