---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4663TGARB4E%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250129T024825Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEHsaCXVzLXdlc3QtMiJHMEUCIQCH%2FfaahkFKqeuj7HOm3au1wsWaLszFvp7xXO7%2FaMxpuwI\
  gQrYbt062NHeooEMP9cIyfDbTnMBhmqfdpUdEaPxTFQUqiAQIg%2F%2F%2F%2F%2F%2F%2F%2F%2F\
  %2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCGDdSgWVdvaLwBiMyrcA3nNQbXoSswYnTx%2B6XhWYa2Ma\
  HJ8GzHq8M4Kmojls1VRGLZIoNJAAuu8WUeC5C%2FKUdOLOREnz%2F6BmaJCUOtnr7YX3N50iUmxOq\
  AOQ%2FC5JuZ%2BeECWEvV9pqvhlwU6Yd35mvBIDP2i3wF72HVZzZyoakW%2BaesIYFhrJ6A4Srm%2\
  BRsU9bw4TDqQ6CLPZ9X3dgUc03%2FD8OknvyBBx059ebp8NwLvTy2XH7scn6efspt4qRup0HihOhM\
  cFvB%2FlCBNfuQFgGKUVhXU0goGKEfCa6TiPBkIEAHjkSO693baKSjwKRJu0HeEZQXKYjjl15MhGJ\
  keSDVJ9SaniEa%2FSXXvyF9XmS%2F%2BI0hi5I5dd35vDDjISO3v9nGL6XmbUeHS4KKNdjhGjng9R\
  5nIrO5hsuSRcgb4YAG7ebAhuABf%2FQPOFSEcxYPpzIsdyQo0%2FmeKb9DismbbUgojdX3kVDgQJ4\
  lui%2Bw31C4CWO0HLs4poU62pwulPIrQRaGRxWn4a%2Bup%2BM8EdHaqHVk6NYmBYQChJg%2BUToH\
  5N%2FH8r491ibPqAG0vZq3DQQTRHiqcZ%2BoJr1ZO%2BMbp3FVWldWGC3X%2B4BDnjP3Rpl1P%2Fz\
  UAMnEjmNH%2FOt662wq3Lv49Kp%2FxpyBEav0AaMqr8MI%2Bh5rwGOqUBZmx9pqe1yhg3N8fJjkTb\
  vAnk%2FTZZNF55KyM5PujNxM2UD8ce4KkyvaDmcbH05k6NSRpy7nVGr%2BuiLj86B%2B67Rhok283\
  zsKMmifUaYcVylq7KA9tYQtgcVwfcEU55h52AdA3p191Ad0wX0%2BY5kJ5ulGndarOkkYaqokTQEJ\
  jMaYMcXjc2KfWp4W46hbC61s0s9UmVdIEw%2Fhemc3ms%2BJaOkswepeRe&X-Amz-Signature=9b\
  183f0a44b7a109667a7193ead7c10b7ce4c2f1e090107addb3ba03676effc0&X-Amz-SignedHe\
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
        redential=ASIAZI2LB466TMNZXLCP%2F20250129%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250129T024712Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJGMEQCIDzly2iw6oNulEa7kc%2BR9H8KOiqGp\
        7Gv9QC0GTEy9UT5AiApUO0gA2F3IglAfYD%2BzFIDmU9Ns3MUffXtdGhW%2B2VwmyqIBAiD\
        %2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMDgyE%2BKvrbWBvZ\
        dFvKtwD4c6pbz1u0WRqFh3Mc0YQ7cRg9Dpd1IHJxSm8Rx7tWgeyo0xQDzVxRXMIwj172wQH\
        ADcNtRsxGMANLWVPztOC0vTEwkcjmfRnOnimyn8iPMvn0oveff1Fk6iG%2BVB%2FUrQeoEo\
        4qFZOn1n3%2F1peHn0PyNG9l7ruL9ox7IUFxYgELbIOFOYxkHqVDY1ZBpyUOLGC1gZPGrOx\
        puQzyEQBgnYLLWndeY2meAJiFycfZyuC0ABtXfG1UaYUgs5b%2FUNNmlkdwbM0TvSLoQUP9\
        PX%2BsBbS62TziBXHt6eLyYEoMnT5OA%2F%2BjPyQivYuNgzNe67njW%2BdT%2FWxrLSpTa\
        wkYGri2LdTjUCUZTGB0SumiMQKmXiIzUdy%2BN4DNMyTvM%2BMJ%2FLuSVmLybB8yvSu%2B\
        qXb1EHGQr9McM3CerJru2SN8dBWqvs5K31IWu7HZq7UBrZfGGrDactZGOoohMb%2Fxkp0u2\
        0dNL4%2Bqr0bOYAHmJPUPSHYBpeOYMvZoaLXzi3K2Nfli3SLa%2FupHiJdnPIrlu5GFLlvC\
        hwjOsH%2F0OuFwgYQk44Y%2BDZelMO5%2FMYnoGuuWB0%2FQ00FU6hK0Gi7e94UEOxZtZjN\
        OxjUv8zZUa8Vgq%2BqvBmkElhBIA0TGj%2FBA%2B2%2B9MMdK8Yw36HmvAY6pgGFztRORoN\
        F1SJ4m5lXpiTqrs9MANjQsVufciHmO%2FFfkIBvgXILiLIr8WjVxj9PamgFVa3LDhzUTkt4\
        2PaYs6uztxV67iugJJgND9aaTDu380qaQHZ0thNjagc1kmdgkrR2cSjWjHDAGk8kNz75rq%\
        2FodrLhJZgiEq1Wwcmnop9A4LMewg1oI3M10fkGtfFdzcpmlLCr7iCp57oGoI%2BiW7ckft\
        hW8FNb&X-Amz-Signature=9acbb477554f958daad1b3cd0bd40dc6e4bf7b121d774f44\
        2326e7b18e6a7c78&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-01-29T03:47:12.945Z"
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
UPDATE_TIME: "2025-01-29T02:48:29.465Z"
EXPIRY_TIME: "2025-01-29T03:48:23.457Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466V2D7KJUU%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T024823Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJGMEQCIBi%2F9MBjNTeLJQwPY3SsCFgHiFir59heDp3eKDFsn1jbAiAY62zDgLQXNcnYDFQwg%2FzlzMDhuXrKqPn00GnadfkA7iqIBAiD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM1o7%2Bj2j2sIOtb%2B8tKtwDI0nSs9FKANgz07XAgLBXarTelBLir0beVxzrS7TfMrQiVfgysCuwaJakZJGNC9nRgmomRiXbICZJp3SkbhOCpIU9uC963cilLrKTp%2BQg4Q%2F1Bx%2F3oCaaku58Z8%2FbtFagGOPga%2FIsijrtZafjDsonSrGM65ApdHI39DH7AKgZWW2sn23%2FsatkjWUl2gHlrKkWpTfFY81CsyKxgZxW1T4p2pUsGiE2Pcpg0CoPnhoXcYLUp%2F3AFyUVwohi0sDmvi79zFW0Q4gZe6RWWbsB%2BFpJyeO5Rxf%2FCJRbOPqS41IQhKVAwgUt7PtsBr5PaPgJkNkhzYOtse0dQ9LQZ6sBtHnzDH0%2FcINABVbc%2BT%2FwBKmXK4VvsbyNGb0w%2B%2FraK%2Fg1ZM8nlV1CnG6xLcOwLwEe3AU%2BdIZT0SlL8Un26HhQuI%2F35%2BU06CbTzbroeP7kXFxFDhxbvWhmEeNx9xjk1DcXFAeMxK8I5bW3OfsKBMKQ76UgHecc7z%2FCAzaDUbISnrBaSLbXVviAP8ztc1SKMEQr8b0c7N0pv0Ih9MEMt3VWhjSf%2Bt6DsDefiuFHa%2BLSYJZPrGbJTkVG2UYBZQEJsC1kdKjbjLQokrU7cfBP6xnLeprJU9LUef3N7%2BIa53DG6J8w36DmvAY6pgFvv4TEDypdZksR81vLRm8cx5uGdJLFQ%2BtLfqOu%2FMFqFzPMukIT7MlAGx5YZH7Yb1ZirqYm51iUsGhtwfTytvjYtWeFL4LQWcU4L00SEurPKiINGBdB1KfMtKMmyjGH7XLlfMNwKVzB7JU3cvPM5NtqZNAiRfo7bZmvC%2Fc0AuoiD8qW7NHo8spsXMm253j20y4XSr9i1YS9basVjXdpG8qvyCViKDmh&X-Amz-Signature=4dec60a93058d4375a7b0f8c7e1e91dbb60c0e904970b16d60da7a4bfe4e6498&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466V2D7KJUU%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T024823Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJGMEQCIBi%2F9MBjNTeLJQwPY3SsCFgHiFir59heDp3eKDFsn1jbAiAY62zDgLQXNcnYDFQwg%2FzlzMDhuXrKqPn00GnadfkA7iqIBAiD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM1o7%2Bj2j2sIOtb%2B8tKtwDI0nSs9FKANgz07XAgLBXarTelBLir0beVxzrS7TfMrQiVfgysCuwaJakZJGNC9nRgmomRiXbICZJp3SkbhOCpIU9uC963cilLrKTp%2BQg4Q%2F1Bx%2F3oCaaku58Z8%2FbtFagGOPga%2FIsijrtZafjDsonSrGM65ApdHI39DH7AKgZWW2sn23%2FsatkjWUl2gHlrKkWpTfFY81CsyKxgZxW1T4p2pUsGiE2Pcpg0CoPnhoXcYLUp%2F3AFyUVwohi0sDmvi79zFW0Q4gZe6RWWbsB%2BFpJyeO5Rxf%2FCJRbOPqS41IQhKVAwgUt7PtsBr5PaPgJkNkhzYOtse0dQ9LQZ6sBtHnzDH0%2FcINABVbc%2BT%2FwBKmXK4VvsbyNGb0w%2B%2FraK%2Fg1ZM8nlV1CnG6xLcOwLwEe3AU%2BdIZT0SlL8Un26HhQuI%2F35%2BU06CbTzbroeP7kXFxFDhxbvWhmEeNx9xjk1DcXFAeMxK8I5bW3OfsKBMKQ76UgHecc7z%2FCAzaDUbISnrBaSLbXVviAP8ztc1SKMEQr8b0c7N0pv0Ih9MEMt3VWhjSf%2Bt6DsDefiuFHa%2BLSYJZPrGbJTkVG2UYBZQEJsC1kdKjbjLQokrU7cfBP6xnLeprJU9LUef3N7%2BIa53DG6J8w36DmvAY6pgFvv4TEDypdZksR81vLRm8cx5uGdJLFQ%2BtLfqOu%2FMFqFzPMukIT7MlAGx5YZH7Yb1ZirqYm51iUsGhtwfTytvjYtWeFL4LQWcU4L00SEurPKiINGBdB1KfMtKMmyjGH7XLlfMNwKVzB7JU3cvPM5NtqZNAiRfo7bZmvC%2Fc0AuoiD8qW7NHo8spsXMm253j20y4XSr9i1YS9basVjXdpG8qvyCViKDmh&X-Amz-Signature=d2af47e90de4610bd53513c099b7023c2883493e18a96fa39fbb3a18f7d30fbe&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466V2D7KJUU%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T024823Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJGMEQCIBi%2F9MBjNTeLJQwPY3SsCFgHiFir59heDp3eKDFsn1jbAiAY62zDgLQXNcnYDFQwg%2FzlzMDhuXrKqPn00GnadfkA7iqIBAiD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM1o7%2Bj2j2sIOtb%2B8tKtwDI0nSs9FKANgz07XAgLBXarTelBLir0beVxzrS7TfMrQiVfgysCuwaJakZJGNC9nRgmomRiXbICZJp3SkbhOCpIU9uC963cilLrKTp%2BQg4Q%2F1Bx%2F3oCaaku58Z8%2FbtFagGOPga%2FIsijrtZafjDsonSrGM65ApdHI39DH7AKgZWW2sn23%2FsatkjWUl2gHlrKkWpTfFY81CsyKxgZxW1T4p2pUsGiE2Pcpg0CoPnhoXcYLUp%2F3AFyUVwohi0sDmvi79zFW0Q4gZe6RWWbsB%2BFpJyeO5Rxf%2FCJRbOPqS41IQhKVAwgUt7PtsBr5PaPgJkNkhzYOtse0dQ9LQZ6sBtHnzDH0%2FcINABVbc%2BT%2FwBKmXK4VvsbyNGb0w%2B%2FraK%2Fg1ZM8nlV1CnG6xLcOwLwEe3AU%2BdIZT0SlL8Un26HhQuI%2F35%2BU06CbTzbroeP7kXFxFDhxbvWhmEeNx9xjk1DcXFAeMxK8I5bW3OfsKBMKQ76UgHecc7z%2FCAzaDUbISnrBaSLbXVviAP8ztc1SKMEQr8b0c7N0pv0Ih9MEMt3VWhjSf%2Bt6DsDefiuFHa%2BLSYJZPrGbJTkVG2UYBZQEJsC1kdKjbjLQokrU7cfBP6xnLeprJU9LUef3N7%2BIa53DG6J8w36DmvAY6pgFvv4TEDypdZksR81vLRm8cx5uGdJLFQ%2BtLfqOu%2FMFqFzPMukIT7MlAGx5YZH7Yb1ZirqYm51iUsGhtwfTytvjYtWeFL4LQWcU4L00SEurPKiINGBdB1KfMtKMmyjGH7XLlfMNwKVzB7JU3cvPM5NtqZNAiRfo7bZmvC%2Fc0AuoiD8qW7NHo8spsXMm253j20y4XSr9i1YS9basVjXdpG8qvyCViKDmh&X-Amz-Signature=360b85fa33036c628b2581614a168136edf689d9e6a41e9b6964e40232dbf998&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466V2D7KJUU%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T024823Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJGMEQCIBi%2F9MBjNTeLJQwPY3SsCFgHiFir59heDp3eKDFsn1jbAiAY62zDgLQXNcnYDFQwg%2FzlzMDhuXrKqPn00GnadfkA7iqIBAiD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM1o7%2Bj2j2sIOtb%2B8tKtwDI0nSs9FKANgz07XAgLBXarTelBLir0beVxzrS7TfMrQiVfgysCuwaJakZJGNC9nRgmomRiXbICZJp3SkbhOCpIU9uC963cilLrKTp%2BQg4Q%2F1Bx%2F3oCaaku58Z8%2FbtFagGOPga%2FIsijrtZafjDsonSrGM65ApdHI39DH7AKgZWW2sn23%2FsatkjWUl2gHlrKkWpTfFY81CsyKxgZxW1T4p2pUsGiE2Pcpg0CoPnhoXcYLUp%2F3AFyUVwohi0sDmvi79zFW0Q4gZe6RWWbsB%2BFpJyeO5Rxf%2FCJRbOPqS41IQhKVAwgUt7PtsBr5PaPgJkNkhzYOtse0dQ9LQZ6sBtHnzDH0%2FcINABVbc%2BT%2FwBKmXK4VvsbyNGb0w%2B%2FraK%2Fg1ZM8nlV1CnG6xLcOwLwEe3AU%2BdIZT0SlL8Un26HhQuI%2F35%2BU06CbTzbroeP7kXFxFDhxbvWhmEeNx9xjk1DcXFAeMxK8I5bW3OfsKBMKQ76UgHecc7z%2FCAzaDUbISnrBaSLbXVviAP8ztc1SKMEQr8b0c7N0pv0Ih9MEMt3VWhjSf%2Bt6DsDefiuFHa%2BLSYJZPrGbJTkVG2UYBZQEJsC1kdKjbjLQokrU7cfBP6xnLeprJU9LUef3N7%2BIa53DG6J8w36DmvAY6pgFvv4TEDypdZksR81vLRm8cx5uGdJLFQ%2BtLfqOu%2FMFqFzPMukIT7MlAGx5YZH7Yb1ZirqYm51iUsGhtwfTytvjYtWeFL4LQWcU4L00SEurPKiINGBdB1KfMtKMmyjGH7XLlfMNwKVzB7JU3cvPM5NtqZNAiRfo7bZmvC%2Fc0AuoiD8qW7NHo8spsXMm253j20y4XSr9i1YS9basVjXdpG8qvyCViKDmh&X-Amz-Signature=5e8d4696a7b76ae68f0f1dd50d1f7974d69c3e6b71201382294154f8c31fb169&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466V2D7KJUU%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T024823Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJGMEQCIBi%2F9MBjNTeLJQwPY3SsCFgHiFir59heDp3eKDFsn1jbAiAY62zDgLQXNcnYDFQwg%2FzlzMDhuXrKqPn00GnadfkA7iqIBAiD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM1o7%2Bj2j2sIOtb%2B8tKtwDI0nSs9FKANgz07XAgLBXarTelBLir0beVxzrS7TfMrQiVfgysCuwaJakZJGNC9nRgmomRiXbICZJp3SkbhOCpIU9uC963cilLrKTp%2BQg4Q%2F1Bx%2F3oCaaku58Z8%2FbtFagGOPga%2FIsijrtZafjDsonSrGM65ApdHI39DH7AKgZWW2sn23%2FsatkjWUl2gHlrKkWpTfFY81CsyKxgZxW1T4p2pUsGiE2Pcpg0CoPnhoXcYLUp%2F3AFyUVwohi0sDmvi79zFW0Q4gZe6RWWbsB%2BFpJyeO5Rxf%2FCJRbOPqS41IQhKVAwgUt7PtsBr5PaPgJkNkhzYOtse0dQ9LQZ6sBtHnzDH0%2FcINABVbc%2BT%2FwBKmXK4VvsbyNGb0w%2B%2FraK%2Fg1ZM8nlV1CnG6xLcOwLwEe3AU%2BdIZT0SlL8Un26HhQuI%2F35%2BU06CbTzbroeP7kXFxFDhxbvWhmEeNx9xjk1DcXFAeMxK8I5bW3OfsKBMKQ76UgHecc7z%2FCAzaDUbISnrBaSLbXVviAP8ztc1SKMEQr8b0c7N0pv0Ih9MEMt3VWhjSf%2Bt6DsDefiuFHa%2BLSYJZPrGbJTkVG2UYBZQEJsC1kdKjbjLQokrU7cfBP6xnLeprJU9LUef3N7%2BIa53DG6J8w36DmvAY6pgFvv4TEDypdZksR81vLRm8cx5uGdJLFQ%2BtLfqOu%2FMFqFzPMukIT7MlAGx5YZH7Yb1ZirqYm51iUsGhtwfTytvjYtWeFL4LQWcU4L00SEurPKiINGBdB1KfMtKMmyjGH7XLlfMNwKVzB7JU3cvPM5NtqZNAiRfo7bZmvC%2Fc0AuoiD8qW7NHo8spsXMm253j20y4XSr9i1YS9basVjXdpG8qvyCViKDmh&X-Amz-Signature=a5417690ec4f48821b82cba106c49d778655d2cf8402f8c7b915449a6500a762&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RVWC6VYS%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T024824Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJHMEUCIQCTbb8ByxIUchGoS80YQbTlhXr00TzBaBvhNSJ27cHdNAIgZetvzeOzASxvwJfiL%2BlTcvUxXNqrk3RfDcO7o97swMMqiAQIg%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHPbOYFqFVuFULPENyrcA3dKJp4y0pLWgfuXaeb8LXAKxVWPC9yGPBQ8JJSudBCenLSH17kQEls0m3jvRpQyHgPEeQeSocNgo3lW8CP2P%2BR4ps9BUbuPhQaMVZsQ%2Bj9MRkven7O9PE%2B9Us0dI7KimDYgyGMbqOamXWFzi5L7jwUuAClcidutD7IjyNt%2BM4E%2Bg7sTv4ZfhyvE9BNsQyFU6yKd5vWluMfZI7R%2F%2FHsP5Sr%2BIkbvZrHucboVG%2BfRNd8YOjVVPcGDtNM2sI31w1I%2BXEGzlgKq2nm0MS9cgqrrDg9Nk3%2FsLDqH%2FJYOEelOAj5OdStHzVC6kxe%2FvAGGMfMLFGNibe6B7n7qfvsvqEy4ab1dGQPedN%2Bn1AbYJv0YxRemvcxCExg9KNFELd1Om4M0fZWoqMEdLpCJZxVyThKeBGIQEpdtehRz2o%2BPBO8GKxlwaHABgK86fnfP5X%2BsAvRR7BF%2BT7UQ8zl5wRAlpOe9Jkq4Y1LxLLeKU%2F5UQqSoeX1bFUrA0GaESjgHyyp5r07MdEhmasYVubyFLcU4Won%2F0Lg2MYHz3qACweZUHRYMfw6Q0UCR10zyhWDtbiwfrV%2B8OOUqFtqu%2BK%2Fxs5El00Em7tDhj9nW05Ojf9dM4BcXitD00w0cRo%2FmoqaApwRMMI6h5rwGOqUBUITdLSqEBt1KlUqbydJdVh0IYFwR7H76S8gwLe116zOlpldv9cLe60fJwMlduZHfKmMa2asm23mLH%2FGXYH%2FJJmGLYtjL0iXE5aDYeeYdlIQ7QtY9uC%2F83Smww6Uk5sGfVvvDGtj0aIG2mNvRcV5CdaiXnLzXuyxsFNkSzlAQ50wNAkJ5qftWM9jivX7lEHalzTPObV3Kta%2FD%2FWlDYudAXc9EnmhO&X-Amz-Signature=09290b37f5a700c7ac9b95f0124e753c79d4ce81919e1969c1a5fa4e9f3f7b68&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664DZYESQI%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T024825Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJHMEUCIE1oG6ZT%2FuUJ9Ve4Jkhiu7Axf3%2FuJsHdL5tfaPS05OdAAiEAg2gDeeO%2F3Z2Xpnd8EcB1neRZNMVvg4HYeHB9YOyaOucqiAQIg%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPYutUqmS6PerdFjFyrcA%2BAmc6AQFX%2FKrClzafna5Zjyf8FZtkTRHM5Dqjb6tG6vyGLaBjTzsWi8yx4lz4XOKFXTxzh3gNa9IKtRIRcMMIOoA3yaIwJdf7CHr2YDG4eK0C20FJVWT28ZT9pzt7vyC5Oy%2BISr2SlT9LcgtCh2KVPLCdYxerm3C5bpcHL%2FerYp6P7pJhNqUb8FzpnkpQHqAMP8NNN4BYNXJl68NAssf5mNBhAipWfkS6aAJT8JjHnUL55dqAk8Y25r5shdlyrZMeQksJQmCyqfi4vkdgo3jiCk0Ptz4PrFUuG8QXsWJebn6KJTWfOTg1%2FWg5Rat2ll9arXclnyQF7rmxsMZ2%2BD77KiNrENwsQvKN2vpSNUJ%2BUITL%2F0%2BJZg3w%2Fg3pzwz77hjnNKf%2BjLF5PcNLZ9wGF76423kjsMCW6M0w6i4TupZFezNIiIZuiEpkHMhJG08uVxXoA41cynmWu%2FkBU%2FSBRwWjzYOBwUT3v4nWboBOSBGLGLxXj2qWgeiXpCy2ciICcvgBQLnPU%2B4cyHXxikrlI1au7MZUmdDiPcmenyYiuBmn4F%2FwLnHU1tlv%2Bo0lAo4cGewp6rTn89pYVJhM2%2BckoYKgzQS2iPcE8sdZjrEtKY9RIm2Y0cx6cQanAhfaoAMN%2Bh5rwGOqUBeUJ1023zQH0FPrJ3KASKVcRxO19CWU5OIJh9eOfFqJJyuxz%2FfyK18EZqCjyJ8FYTn%2B8JAjqEhLnu8GIpB2ZHww9ox%2BymWmiargWI2gbzWvr7Y53NKwz3o0EvKLLYrkPjLRcqeejV8jF6PjDVyQZLZQ0lu9%2FejeWFxDRDbtQcrtc5SczBzMLJv3noUIp81WuZ0IPJ6HmEeIMzcVjR%2FB%2B1FOOHCMeM&X-Amz-Signature=7d9cdaacffbe234b4362f8f959502a9905e15b8f55fea3d74bd262c30c9fbb0b&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466V2D7KJUU%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T024823Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJGMEQCIBi%2F9MBjNTeLJQwPY3SsCFgHiFir59heDp3eKDFsn1jbAiAY62zDgLQXNcnYDFQwg%2FzlzMDhuXrKqPn00GnadfkA7iqIBAiD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM1o7%2Bj2j2sIOtb%2B8tKtwDI0nSs9FKANgz07XAgLBXarTelBLir0beVxzrS7TfMrQiVfgysCuwaJakZJGNC9nRgmomRiXbICZJp3SkbhOCpIU9uC963cilLrKTp%2BQg4Q%2F1Bx%2F3oCaaku58Z8%2FbtFagGOPga%2FIsijrtZafjDsonSrGM65ApdHI39DH7AKgZWW2sn23%2FsatkjWUl2gHlrKkWpTfFY81CsyKxgZxW1T4p2pUsGiE2Pcpg0CoPnhoXcYLUp%2F3AFyUVwohi0sDmvi79zFW0Q4gZe6RWWbsB%2BFpJyeO5Rxf%2FCJRbOPqS41IQhKVAwgUt7PtsBr5PaPgJkNkhzYOtse0dQ9LQZ6sBtHnzDH0%2FcINABVbc%2BT%2FwBKmXK4VvsbyNGb0w%2B%2FraK%2Fg1ZM8nlV1CnG6xLcOwLwEe3AU%2BdIZT0SlL8Un26HhQuI%2F35%2BU06CbTzbroeP7kXFxFDhxbvWhmEeNx9xjk1DcXFAeMxK8I5bW3OfsKBMKQ76UgHecc7z%2FCAzaDUbISnrBaSLbXVviAP8ztc1SKMEQr8b0c7N0pv0Ih9MEMt3VWhjSf%2Bt6DsDefiuFHa%2BLSYJZPrGbJTkVG2UYBZQEJsC1kdKjbjLQokrU7cfBP6xnLeprJU9LUef3N7%2BIa53DG6J8w36DmvAY6pgFvv4TEDypdZksR81vLRm8cx5uGdJLFQ%2BtLfqOu%2FMFqFzPMukIT7MlAGx5YZH7Yb1ZirqYm51iUsGhtwfTytvjYtWeFL4LQWcU4L00SEurPKiINGBdB1KfMtKMmyjGH7XLlfMNwKVzB7JU3cvPM5NtqZNAiRfo7bZmvC%2Fc0AuoiD8qW7NHo8spsXMm253j20y4XSr9i1YS9basVjXdpG8qvyCViKDmh&X-Amz-Signature=9926826f931d9da9b5838ea33ceb251194bc2f400d462eb65d9a1b9f258d5839&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466V2D7KJUU%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T024823Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJGMEQCIBi%2F9MBjNTeLJQwPY3SsCFgHiFir59heDp3eKDFsn1jbAiAY62zDgLQXNcnYDFQwg%2FzlzMDhuXrKqPn00GnadfkA7iqIBAiD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM1o7%2Bj2j2sIOtb%2B8tKtwDI0nSs9FKANgz07XAgLBXarTelBLir0beVxzrS7TfMrQiVfgysCuwaJakZJGNC9nRgmomRiXbICZJp3SkbhOCpIU9uC963cilLrKTp%2BQg4Q%2F1Bx%2F3oCaaku58Z8%2FbtFagGOPga%2FIsijrtZafjDsonSrGM65ApdHI39DH7AKgZWW2sn23%2FsatkjWUl2gHlrKkWpTfFY81CsyKxgZxW1T4p2pUsGiE2Pcpg0CoPnhoXcYLUp%2F3AFyUVwohi0sDmvi79zFW0Q4gZe6RWWbsB%2BFpJyeO5Rxf%2FCJRbOPqS41IQhKVAwgUt7PtsBr5PaPgJkNkhzYOtse0dQ9LQZ6sBtHnzDH0%2FcINABVbc%2BT%2FwBKmXK4VvsbyNGb0w%2B%2FraK%2Fg1ZM8nlV1CnG6xLcOwLwEe3AU%2BdIZT0SlL8Un26HhQuI%2F35%2BU06CbTzbroeP7kXFxFDhxbvWhmEeNx9xjk1DcXFAeMxK8I5bW3OfsKBMKQ76UgHecc7z%2FCAzaDUbISnrBaSLbXVviAP8ztc1SKMEQr8b0c7N0pv0Ih9MEMt3VWhjSf%2Bt6DsDefiuFHa%2BLSYJZPrGbJTkVG2UYBZQEJsC1kdKjbjLQokrU7cfBP6xnLeprJU9LUef3N7%2BIa53DG6J8w36DmvAY6pgFvv4TEDypdZksR81vLRm8cx5uGdJLFQ%2BtLfqOu%2FMFqFzPMukIT7MlAGx5YZH7Yb1ZirqYm51iUsGhtwfTytvjYtWeFL4LQWcU4L00SEurPKiINGBdB1KfMtKMmyjGH7XLlfMNwKVzB7JU3cvPM5NtqZNAiRfo7bZmvC%2Fc0AuoiD8qW7NHo8spsXMm253j20y4XSr9i1YS9basVjXdpG8qvyCViKDmh&X-Amz-Signature=c2c816a2eadb80e2c908c1361a1591cee9f4a2d090b0a9c592e6d7ba9c8d0ac5&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466V2D7KJUU%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T024823Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJGMEQCIBi%2F9MBjNTeLJQwPY3SsCFgHiFir59heDp3eKDFsn1jbAiAY62zDgLQXNcnYDFQwg%2FzlzMDhuXrKqPn00GnadfkA7iqIBAiD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM1o7%2Bj2j2sIOtb%2B8tKtwDI0nSs9FKANgz07XAgLBXarTelBLir0beVxzrS7TfMrQiVfgysCuwaJakZJGNC9nRgmomRiXbICZJp3SkbhOCpIU9uC963cilLrKTp%2BQg4Q%2F1Bx%2F3oCaaku58Z8%2FbtFagGOPga%2FIsijrtZafjDsonSrGM65ApdHI39DH7AKgZWW2sn23%2FsatkjWUl2gHlrKkWpTfFY81CsyKxgZxW1T4p2pUsGiE2Pcpg0CoPnhoXcYLUp%2F3AFyUVwohi0sDmvi79zFW0Q4gZe6RWWbsB%2BFpJyeO5Rxf%2FCJRbOPqS41IQhKVAwgUt7PtsBr5PaPgJkNkhzYOtse0dQ9LQZ6sBtHnzDH0%2FcINABVbc%2BT%2FwBKmXK4VvsbyNGb0w%2B%2FraK%2Fg1ZM8nlV1CnG6xLcOwLwEe3AU%2BdIZT0SlL8Un26HhQuI%2F35%2BU06CbTzbroeP7kXFxFDhxbvWhmEeNx9xjk1DcXFAeMxK8I5bW3OfsKBMKQ76UgHecc7z%2FCAzaDUbISnrBaSLbXVviAP8ztc1SKMEQr8b0c7N0pv0Ih9MEMt3VWhjSf%2Bt6DsDefiuFHa%2BLSYJZPrGbJTkVG2UYBZQEJsC1kdKjbjLQokrU7cfBP6xnLeprJU9LUef3N7%2BIa53DG6J8w36DmvAY6pgFvv4TEDypdZksR81vLRm8cx5uGdJLFQ%2BtLfqOu%2FMFqFzPMukIT7MlAGx5YZH7Yb1ZirqYm51iUsGhtwfTytvjYtWeFL4LQWcU4L00SEurPKiINGBdB1KfMtKMmyjGH7XLlfMNwKVzB7JU3cvPM5NtqZNAiRfo7bZmvC%2Fc0AuoiD8qW7NHo8spsXMm253j20y4XSr9i1YS9basVjXdpG8qvyCViKDmh&X-Amz-Signature=2db245c9f9096bc4e01016c0f81c9cbc7b8389ef40606c970375914c1efd34f7&X-Amz-SignedHeaders=host&x-id=GetObject)


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

