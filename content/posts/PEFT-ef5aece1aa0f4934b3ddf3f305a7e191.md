---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466TZONT6JN%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250209T222157Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAo2w0qGMC6LDT2y5h1\
  cA4pCKLO2ZRQhJlIxjZvE8eMuAiADVElVuk9bE2d8W3%2BTr8vDgRAHrc8KUrGa6Z8Q0nRdfSqIBA\
  it%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM28E3p5LJnRriyJ4eKtw\
  DVOErGnerBeyixFwy6x8J80HuNEQFUD14QwGb%2F45dX4J8pUTy5ruhp4Low8hXLP7wIq8%2B1ioP\
  70hHoeiDtxlvtXgH8DjZxJePRXL4KdOAw9xRff3G6ORMgkoITgHu0DD3wH4LnYrwVAEUxKHTSwLtu\
  5L4ibaBZPBLdm4ufe8F45WFdhBpvx4upnrmCiCtWw48B4avgWmkBbv54VG2lC9tTJivRujwWkQo1f\
  ifnrKVQ%2F%2Bx7Oz8gdkFIWtOlJF23%2FpXHigQSWJq6c33coGx2KCL0Ixtgz8vs12M%2BOmJcEA\
  zl%2BZMhziotdYD71MdepBOJ4zYV6MSBfop6%2BBHzYTig50%2F4z10QoHdOtHhlOwwotQdjBnfXr\
  OzssvRfUghjHjhHDwhfNH4tRMcGt7B26kPkVWTpsK%2BnY7jjmdL7%2FT9KmcZCHOwbdHZPjQJFsF\
  4wsN2hL1aEmuYfs97v0UC4q%2FVvh0R4WyGkTY6Ora799zC1Rfr4ZqgZAS102Cy7EBFKOAtSKXJGw\
  9mSuS3LUD5bcpZBV9aRKOEn7DeiSp6UAGzXwnUqlmY%2FMjjoQ83UsDD7VcUO4FrVSg4U6Z4lyLZQ\
  nNN%2BrNQQek6oqYGi4rtbokcuiOSRD%2FQRaex3vKcK38RbqUw746kvQY6pgEeekGRodDziUKWTW\
  LJiinrB9oh%2Ft4RehUZH4RROxzleYKpaqLSfkD9Zv5ocfD7xuam576GsXkf0r0eaF9ytkZA7NeqR\
  wpscCJsk7BLe3Ti%2B8Oq5nL3CklcdiHjUtBvjypcGaQBfbMefwCyOvVcTsKDaV%2BJc1LTkwgdoK\
  150B12EiVVNWJlBA1kh7icK%2Fhhsz35xcylMHe%2B2sUli48V0p5%2F7dTofl%2BB&X-Amz-Sign\
  ature=d3fc95161f783367eb28ba0fcd5a3f0845072a0044f9a22c6f7e8aaa3909faf9&X-Amz-\
  SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466X6C3NY3M%2F20250209%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250209T222059Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIQDMUmTVnXvEDzjHCWMlsVDMOJA%2FgrNKioMVa679%2BX4atQIgAQb8FiU3PM05JcCfJN\
        812nSurFANZ5g4cZqQ2BP7nA8qiAQIrf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2M\
        zc0MjMxODM4MDUiDCkodfh6dN%2BAk0y2SircA2srSjZ%2FV0UjM%2BXTFwi4JBcmJHuluP\
        8XXbqWEIjRynPZKwhVqs%2BUR6PBI%2F6h20GSXwGq9mPBBgTfxfaorKA6pZCIVp3bCADzJ\
        FTA%2F%2FlccbwBmy0qJNcGj06Jomboc6lopIAGtJPHHUoZTCGlO1dpyRB98qKjkoNS3xZ9\
        YZCFyFAHRG7bLtyPALICLweCeI%2FZ14u%2BdKLUW44cSADtI1xAqoyhGZ4XTCr7Two%2FO\
        GSmIoVHiHgnjAnQTwIJ4XrEmdLO7HKIAXO4qtU4Ttmpb22GRQw81YMvBtjnaxNsc0umv6sm\
        MsaP4IFONtu9pDwhFADRdwqFLhyTu4L7gQ4isSLd1vDbcirJ3cee%2F5KCHmMXc%2FvzBCe\
        xK4DHP2CFr4cR7CNtoOOoNs%2B0KqCO7VW%2BLJV2tmd7PeWayVuiO40CBZten6PsSDe6a8\
        qcPSQDJ2ZDIKRDWMUymNgJrNbCX71MAn4p6ypei2jGW7G0RJa%2FeklYhwDf4IxxmMIklqU\
        tcefcdEuHd3EXMgvvnWikxwhsB8Putf18mm3ncU6pq8O86KKvWhmSnYU2pUH7WOANnWVD3b\
        sa7U1ZcfM3Te%2BmpKS09LwiMMoKcNOO6a5OOsKHY4xV0FAh4leakuSzDxBeMwLzMOGPpL0\
        GOqUBlDOxsFXV6tVNUlLdYruUIm9hFD0igxFgcrTrqyFrLMLoB2zK4HIki2o2xImdU8SGhI\
        JfYtYeb9YrHcxq%2B1sTo0R55PeT48K8TOX%2Fy%2FkdmEDb%2FQUJCzq3tRC1qsjfHSWuI\
        CFRpOaCMP6vI2rO%2FkgcZnfzwaLMvWp1Rbxw8f%2FT27GcCnp3wtTP4xqrPCoh%2FEwI82\
        h1IRcrTs2EitqLnA0Pc%2Ftjwqaj&X-Amz-Signature=cb6a2e76673bd22f4247675054\
        1543f37793b15fbd1169e168a5a24db1c176b0&X-Amz-SignedHeaders=host&x-id=Ge\
        tObject"
      expiry_time: "2025-02-09T23:20:59.806Z"
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
UPDATE_TIME: "2025-02-09T22:22:03.919Z"
EXPIRY_TIME: "2025-02-09T23:21:55.776Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UGIDCHHT%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T222156Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCHk1zlCSlrDqWiJ6jCotgJJTwzwRGAt4zfzePrdVZs5wIgBUwD%2BvWJSvSTNCL6fqnfbfuTFYEPthbCP8jYpB5AuG0qiAQIrf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLTUV2%2FlhgpX6NTZgircA0ZZ4QryJwsDovfjo4nd7gX8fefHpibBjOpB%2FXF9hnFXSwEs4sEg44HOTxZcW9CyshrezkY%2Fgo6OA7tsBbc1uFqOEJ7Lc43vqyJA%2F2TCwJrEhIfGTqY5Xqdiv2HPRxec7PHRmIJGziVZ0SzlWUVDammHd6E2yeZg1e04fyuMbs8otGDDPZOOtmx6UsBJrPcl466uJmgd%2FLEowjAtNjw0NZt3EmHSRRzOrnogbf6gbOFXl6jKJek1pphJ9Jt%2FxfR4KYqyFdLVQC9xEJntYFHLzWm03EMRr97tAijZ6GQGNp9precX%2BBvZgst6W9N%2B6oG2kYpA%2FJj2BvRK7FGLjAdg1unUlLEHrKjWwT7JlPu2yh2EYQxfGYEdarwCztVdrdA8YmKuTJr2cyfIBHi3hhLRYOS2u6p%2B%2FIoh2qv9DwM5E%2BvlC5rsqa71gemL5LamwsuIIpXU74XPossyKVryF4LyPC9TeIWa3VKLbOczJVER%2FQkSKvpGn71%2FCigqFI6AcnxIX9cjLGXkbssGdBZxm64wQIK9TrMyKXTaKSYQy5NrLUdh1%2FZJS4dn3vV14vocR5aANIZAL0VmQbBKeFmY%2BfYba2oYf1XZInNw7Ax86AJcdG%2FpB42qY0EuYHM%2B9Y72MIKPpL0GOqUBwwg7Y7BADw5oFaLrZOEUzKPn6LScgrqk0ZoncLSHZN7ZhldNqPf3JSV8FkU%2BoPTKc%2BAH3i7Xdy%2Fb1mJ4Qj345zGCtsgnW8Vivki%2BC3aSBKYeJvjz8hP%2BFlqyW%2Bnn3e6E9a4QKfCsf3NzF2jZHw5aq%2FL9g4aT4I%2FSAOlIh8PuR%2B4mAz7iGKaNibR%2FuigND48yY4Q69VQEdajCw3iYlg2qlx1gWasA&X-Amz-Signature=a3aa55bcf86287188d649632d267a320737abe4635de01935221c56e6e88edf0&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UGIDCHHT%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T222156Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCHk1zlCSlrDqWiJ6jCotgJJTwzwRGAt4zfzePrdVZs5wIgBUwD%2BvWJSvSTNCL6fqnfbfuTFYEPthbCP8jYpB5AuG0qiAQIrf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLTUV2%2FlhgpX6NTZgircA0ZZ4QryJwsDovfjo4nd7gX8fefHpibBjOpB%2FXF9hnFXSwEs4sEg44HOTxZcW9CyshrezkY%2Fgo6OA7tsBbc1uFqOEJ7Lc43vqyJA%2F2TCwJrEhIfGTqY5Xqdiv2HPRxec7PHRmIJGziVZ0SzlWUVDammHd6E2yeZg1e04fyuMbs8otGDDPZOOtmx6UsBJrPcl466uJmgd%2FLEowjAtNjw0NZt3EmHSRRzOrnogbf6gbOFXl6jKJek1pphJ9Jt%2FxfR4KYqyFdLVQC9xEJntYFHLzWm03EMRr97tAijZ6GQGNp9precX%2BBvZgst6W9N%2B6oG2kYpA%2FJj2BvRK7FGLjAdg1unUlLEHrKjWwT7JlPu2yh2EYQxfGYEdarwCztVdrdA8YmKuTJr2cyfIBHi3hhLRYOS2u6p%2B%2FIoh2qv9DwM5E%2BvlC5rsqa71gemL5LamwsuIIpXU74XPossyKVryF4LyPC9TeIWa3VKLbOczJVER%2FQkSKvpGn71%2FCigqFI6AcnxIX9cjLGXkbssGdBZxm64wQIK9TrMyKXTaKSYQy5NrLUdh1%2FZJS4dn3vV14vocR5aANIZAL0VmQbBKeFmY%2BfYba2oYf1XZInNw7Ax86AJcdG%2FpB42qY0EuYHM%2B9Y72MIKPpL0GOqUBwwg7Y7BADw5oFaLrZOEUzKPn6LScgrqk0ZoncLSHZN7ZhldNqPf3JSV8FkU%2BoPTKc%2BAH3i7Xdy%2Fb1mJ4Qj345zGCtsgnW8Vivki%2BC3aSBKYeJvjz8hP%2BFlqyW%2Bnn3e6E9a4QKfCsf3NzF2jZHw5aq%2FL9g4aT4I%2FSAOlIh8PuR%2B4mAz7iGKaNibR%2FuigND48yY4Q69VQEdajCw3iYlg2qlx1gWasA&X-Amz-Signature=01a3ff6ef1e2337180ee09860fb031c77d7ca37598225e55b7dfff32eaac3674&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UGIDCHHT%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T222156Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCHk1zlCSlrDqWiJ6jCotgJJTwzwRGAt4zfzePrdVZs5wIgBUwD%2BvWJSvSTNCL6fqnfbfuTFYEPthbCP8jYpB5AuG0qiAQIrf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLTUV2%2FlhgpX6NTZgircA0ZZ4QryJwsDovfjo4nd7gX8fefHpibBjOpB%2FXF9hnFXSwEs4sEg44HOTxZcW9CyshrezkY%2Fgo6OA7tsBbc1uFqOEJ7Lc43vqyJA%2F2TCwJrEhIfGTqY5Xqdiv2HPRxec7PHRmIJGziVZ0SzlWUVDammHd6E2yeZg1e04fyuMbs8otGDDPZOOtmx6UsBJrPcl466uJmgd%2FLEowjAtNjw0NZt3EmHSRRzOrnogbf6gbOFXl6jKJek1pphJ9Jt%2FxfR4KYqyFdLVQC9xEJntYFHLzWm03EMRr97tAijZ6GQGNp9precX%2BBvZgst6W9N%2B6oG2kYpA%2FJj2BvRK7FGLjAdg1unUlLEHrKjWwT7JlPu2yh2EYQxfGYEdarwCztVdrdA8YmKuTJr2cyfIBHi3hhLRYOS2u6p%2B%2FIoh2qv9DwM5E%2BvlC5rsqa71gemL5LamwsuIIpXU74XPossyKVryF4LyPC9TeIWa3VKLbOczJVER%2FQkSKvpGn71%2FCigqFI6AcnxIX9cjLGXkbssGdBZxm64wQIK9TrMyKXTaKSYQy5NrLUdh1%2FZJS4dn3vV14vocR5aANIZAL0VmQbBKeFmY%2BfYba2oYf1XZInNw7Ax86AJcdG%2FpB42qY0EuYHM%2B9Y72MIKPpL0GOqUBwwg7Y7BADw5oFaLrZOEUzKPn6LScgrqk0ZoncLSHZN7ZhldNqPf3JSV8FkU%2BoPTKc%2BAH3i7Xdy%2Fb1mJ4Qj345zGCtsgnW8Vivki%2BC3aSBKYeJvjz8hP%2BFlqyW%2Bnn3e6E9a4QKfCsf3NzF2jZHw5aq%2FL9g4aT4I%2FSAOlIh8PuR%2B4mAz7iGKaNibR%2FuigND48yY4Q69VQEdajCw3iYlg2qlx1gWasA&X-Amz-Signature=be0b005cc3e81dd6ceef0e9cb390fbf9a652a9191f112e0842907f86510ca186&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UGIDCHHT%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T222156Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCHk1zlCSlrDqWiJ6jCotgJJTwzwRGAt4zfzePrdVZs5wIgBUwD%2BvWJSvSTNCL6fqnfbfuTFYEPthbCP8jYpB5AuG0qiAQIrf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLTUV2%2FlhgpX6NTZgircA0ZZ4QryJwsDovfjo4nd7gX8fefHpibBjOpB%2FXF9hnFXSwEs4sEg44HOTxZcW9CyshrezkY%2Fgo6OA7tsBbc1uFqOEJ7Lc43vqyJA%2F2TCwJrEhIfGTqY5Xqdiv2HPRxec7PHRmIJGziVZ0SzlWUVDammHd6E2yeZg1e04fyuMbs8otGDDPZOOtmx6UsBJrPcl466uJmgd%2FLEowjAtNjw0NZt3EmHSRRzOrnogbf6gbOFXl6jKJek1pphJ9Jt%2FxfR4KYqyFdLVQC9xEJntYFHLzWm03EMRr97tAijZ6GQGNp9precX%2BBvZgst6W9N%2B6oG2kYpA%2FJj2BvRK7FGLjAdg1unUlLEHrKjWwT7JlPu2yh2EYQxfGYEdarwCztVdrdA8YmKuTJr2cyfIBHi3hhLRYOS2u6p%2B%2FIoh2qv9DwM5E%2BvlC5rsqa71gemL5LamwsuIIpXU74XPossyKVryF4LyPC9TeIWa3VKLbOczJVER%2FQkSKvpGn71%2FCigqFI6AcnxIX9cjLGXkbssGdBZxm64wQIK9TrMyKXTaKSYQy5NrLUdh1%2FZJS4dn3vV14vocR5aANIZAL0VmQbBKeFmY%2BfYba2oYf1XZInNw7Ax86AJcdG%2FpB42qY0EuYHM%2B9Y72MIKPpL0GOqUBwwg7Y7BADw5oFaLrZOEUzKPn6LScgrqk0ZoncLSHZN7ZhldNqPf3JSV8FkU%2BoPTKc%2BAH3i7Xdy%2Fb1mJ4Qj345zGCtsgnW8Vivki%2BC3aSBKYeJvjz8hP%2BFlqyW%2Bnn3e6E9a4QKfCsf3NzF2jZHw5aq%2FL9g4aT4I%2FSAOlIh8PuR%2B4mAz7iGKaNibR%2FuigND48yY4Q69VQEdajCw3iYlg2qlx1gWasA&X-Amz-Signature=eb9d427ef8691f3e17235d5ff296a7333faca4c87041bd34843ef4f957ebc523&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UGIDCHHT%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T222156Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCHk1zlCSlrDqWiJ6jCotgJJTwzwRGAt4zfzePrdVZs5wIgBUwD%2BvWJSvSTNCL6fqnfbfuTFYEPthbCP8jYpB5AuG0qiAQIrf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLTUV2%2FlhgpX6NTZgircA0ZZ4QryJwsDovfjo4nd7gX8fefHpibBjOpB%2FXF9hnFXSwEs4sEg44HOTxZcW9CyshrezkY%2Fgo6OA7tsBbc1uFqOEJ7Lc43vqyJA%2F2TCwJrEhIfGTqY5Xqdiv2HPRxec7PHRmIJGziVZ0SzlWUVDammHd6E2yeZg1e04fyuMbs8otGDDPZOOtmx6UsBJrPcl466uJmgd%2FLEowjAtNjw0NZt3EmHSRRzOrnogbf6gbOFXl6jKJek1pphJ9Jt%2FxfR4KYqyFdLVQC9xEJntYFHLzWm03EMRr97tAijZ6GQGNp9precX%2BBvZgst6W9N%2B6oG2kYpA%2FJj2BvRK7FGLjAdg1unUlLEHrKjWwT7JlPu2yh2EYQxfGYEdarwCztVdrdA8YmKuTJr2cyfIBHi3hhLRYOS2u6p%2B%2FIoh2qv9DwM5E%2BvlC5rsqa71gemL5LamwsuIIpXU74XPossyKVryF4LyPC9TeIWa3VKLbOczJVER%2FQkSKvpGn71%2FCigqFI6AcnxIX9cjLGXkbssGdBZxm64wQIK9TrMyKXTaKSYQy5NrLUdh1%2FZJS4dn3vV14vocR5aANIZAL0VmQbBKeFmY%2BfYba2oYf1XZInNw7Ax86AJcdG%2FpB42qY0EuYHM%2B9Y72MIKPpL0GOqUBwwg7Y7BADw5oFaLrZOEUzKPn6LScgrqk0ZoncLSHZN7ZhldNqPf3JSV8FkU%2BoPTKc%2BAH3i7Xdy%2Fb1mJ4Qj345zGCtsgnW8Vivki%2BC3aSBKYeJvjz8hP%2BFlqyW%2Bnn3e6E9a4QKfCsf3NzF2jZHw5aq%2FL9g4aT4I%2FSAOlIh8PuR%2B4mAz7iGKaNibR%2FuigND48yY4Q69VQEdajCw3iYlg2qlx1gWasA&X-Amz-Signature=84518e8f66fbd0c8fc4b69720909fec5599925559dd38908811f0dec1de35fb5&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZQNBHLD4%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T222156Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD9DWHfefLBR%2BmFwqgERKnqBWt1XtJNXpTa3sg1XfWKYgIhAML5tJuZg3lOVbqsAKf6RaGYWuU5Is2niBbzzIytjQ11KogECK3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzXyC7bqKGPN5z5HD0q3ANo4ARu5JhtyfMy0C8Nm092aSDL6katVBkt06yBdxYbKuhSjbXdrOjYXoVKKvSSHUcrgfoPoi24B1YSz%2F8s2uh0BPOpiOvKDdWPqO5uXFLjMr%2BNou14xRsvEqUB7UkRVDNE%2BIHmrNJhed6%2FZOgbwbRZLodYSl3PBLNKj%2B8jSxAwIHfCvPlDEmd%2F%2B9SxuEZG26izibgNZZ20n9JPAgch4xAQy5%2Fyi%2BSWz2ODRPoRAKSf2xRTZoNKUnEqOMBW4H7vfD%2B62o8o3%2Bm2uXjniF2i8DMK%2FCm9JIxb0vZsDxzRi9%2F0Kr8Wxx7%2BvycGFM%2BMmt95DrcGWOgM%2BczF0vV3AlEF54Ja4dxvT5x2xa%2BuHw5aZX9gUQxdRnQRGddyOCZApx59dLGbOcBYTNhdhE2EYIdQsrYX8VLxStL9raF5Bb9lAyDMbCwnfsfb8U3y7l%2FE%2B6ZYyH3kj6WW9bvl891WSO%2BwxsDKZxqODRxhz6bdmBrgzs0w%2FTGxNhKnpuv1FA0lzGEArp27BQ1zciFYhfBFj3RK5bGpqnj4tBzRrRnjwecWeCsJ1ZY%2FHGHNKVnIqjkZBkpLm9rA7RmVSmFWFXGGsUstnO6cqDt3rC07bISfMqyofEaW16w5zWbrdoegF0VtNDDnj6S9BjqkAcKO2ZqZ5OaUNBQrjMOudJCfwFUwdwznb1pV1hXYS79bD0ns2FpyKdIDf9sgHbUtDPO8NL3OcYFHdJHIhOEPdiyRDGcH63cjUuhQ1w6Pa8VL3y9qj8Bpy5iYrmBoZYrtT3cfrDJ%2F3uS8G54e9YWWk1FbpiQd3TDG8GZ3g2N0LYh3UlcpWH3XdP3ja7TCb2PysZ7Z%2BcgsOyNuUdadXHLrXflvgTfS&X-Amz-Signature=6bc977c292790ef6dea670a7a7b916b09de566c7c556a274a80c9693d60af5c2&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46644MR2XEH%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T222157Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIHp%2FoGVfIugNdBB%2FzkaSCz1xw%2Bi3I%2B%2F4fAPejRaseDDvAiA3r3vHoFJU1aDNrZb7Kvzs5ymwSfSk3pa9rGkFn9ku6CqIBAit%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMfoZa0FBfVlMIZGHTKtwDXkGeR39zhS%2FDqTzV2LEA9Hk8TCexp2nCVajT7Ylyn%2FFifgDcuZ%2FyvruDvNYacEZYQ%2BByyn2kPz3v5qgMilqpKqoTvwdPu5Q3tQDnHEpyds9i%2BSkVDZwBeY7Ck3OUeYBcOLOp8zdBjdDfPsRoHQiJhdipQOa8HxJKTq0%2FyOBStRRvKDD%2FesuTEanCV%2FXznQe6fjRVpNW5Xear%2BhoRL%2Bmx5DHquqcMMw2E%2B7n1f0I5AYnY3xVXLrANB%2BdnuWfi27YMqmAecHBJfwKbVqMHXiDQP1RF75fnVmgiFcR81AZp1tCJCemmL5EKJmgk6ao7YH3t42M31hgxVA8dHR6I%2FxokxwOvpZW79Sfns2P0pWCXTzN%2FtlWdV%2FmA0ue2a5fYkNwrRvvpIWdc75j%2F7tduGU9%2F8IOVRgHgP6zz9%2BqvmvOhpe7sxYFDFaFuYEs0T%2BKo%2F7U90Wz66PxbPpA016JoH0Byz6u8K8HHY0pF2hnDIh2PorpJVgWPWthDhZ4Q%2FvgZJzgqG5vxleLuktL%2B%2B6bvNrN%2FELOkXT3cCfo9ZdO6pZuwju9TR5hLbm1U6wh%2FR3jyMs%2FWgUeagTZFgLbwES2Kt%2BrynGk7V7vPtkfq6EoouIAF0sDBAPYWhsm7StB0gJkw%2FY6kvQY6pgF2TZA9m6n8%2Bj5Oho57E7EeeoMZ6Mk%2B7GlHS%2Bik9nS8OGGFKa3Jj82C8GEbhhC4wkfaMJb%2B7cbILkhuHwy3gB8Q4jA1ALwi%2B%2Fq6R9jxApQj1uoOKDGv9xZ3ROPeWx2Qzh%2BqSbHZIeyclIK4hcfMNbqI%2FAfx7a%2FAsqPaJ9WJsHO9041mL0NfAY8s09IdRh7jJwGgtLNG3V4BuSQVXS43f%2Bs%2F25nrAc1t&X-Amz-Signature=cf18cbd57eb8564625afe89aa1d887a414643220d6a4a117e1a6b059225c08b4&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UGIDCHHT%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T222156Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCHk1zlCSlrDqWiJ6jCotgJJTwzwRGAt4zfzePrdVZs5wIgBUwD%2BvWJSvSTNCL6fqnfbfuTFYEPthbCP8jYpB5AuG0qiAQIrf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLTUV2%2FlhgpX6NTZgircA0ZZ4QryJwsDovfjo4nd7gX8fefHpibBjOpB%2FXF9hnFXSwEs4sEg44HOTxZcW9CyshrezkY%2Fgo6OA7tsBbc1uFqOEJ7Lc43vqyJA%2F2TCwJrEhIfGTqY5Xqdiv2HPRxec7PHRmIJGziVZ0SzlWUVDammHd6E2yeZg1e04fyuMbs8otGDDPZOOtmx6UsBJrPcl466uJmgd%2FLEowjAtNjw0NZt3EmHSRRzOrnogbf6gbOFXl6jKJek1pphJ9Jt%2FxfR4KYqyFdLVQC9xEJntYFHLzWm03EMRr97tAijZ6GQGNp9precX%2BBvZgst6W9N%2B6oG2kYpA%2FJj2BvRK7FGLjAdg1unUlLEHrKjWwT7JlPu2yh2EYQxfGYEdarwCztVdrdA8YmKuTJr2cyfIBHi3hhLRYOS2u6p%2B%2FIoh2qv9DwM5E%2BvlC5rsqa71gemL5LamwsuIIpXU74XPossyKVryF4LyPC9TeIWa3VKLbOczJVER%2FQkSKvpGn71%2FCigqFI6AcnxIX9cjLGXkbssGdBZxm64wQIK9TrMyKXTaKSYQy5NrLUdh1%2FZJS4dn3vV14vocR5aANIZAL0VmQbBKeFmY%2BfYba2oYf1XZInNw7Ax86AJcdG%2FpB42qY0EuYHM%2B9Y72MIKPpL0GOqUBwwg7Y7BADw5oFaLrZOEUzKPn6LScgrqk0ZoncLSHZN7ZhldNqPf3JSV8FkU%2BoPTKc%2BAH3i7Xdy%2Fb1mJ4Qj345zGCtsgnW8Vivki%2BC3aSBKYeJvjz8hP%2BFlqyW%2Bnn3e6E9a4QKfCsf3NzF2jZHw5aq%2FL9g4aT4I%2FSAOlIh8PuR%2B4mAz7iGKaNibR%2FuigND48yY4Q69VQEdajCw3iYlg2qlx1gWasA&X-Amz-Signature=774a0a75b03929c44a4e7fb423fe6c86c5d365ea7e24eec927299eb6c3028ff2&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UGIDCHHT%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T222156Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCHk1zlCSlrDqWiJ6jCotgJJTwzwRGAt4zfzePrdVZs5wIgBUwD%2BvWJSvSTNCL6fqnfbfuTFYEPthbCP8jYpB5AuG0qiAQIrf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLTUV2%2FlhgpX6NTZgircA0ZZ4QryJwsDovfjo4nd7gX8fefHpibBjOpB%2FXF9hnFXSwEs4sEg44HOTxZcW9CyshrezkY%2Fgo6OA7tsBbc1uFqOEJ7Lc43vqyJA%2F2TCwJrEhIfGTqY5Xqdiv2HPRxec7PHRmIJGziVZ0SzlWUVDammHd6E2yeZg1e04fyuMbs8otGDDPZOOtmx6UsBJrPcl466uJmgd%2FLEowjAtNjw0NZt3EmHSRRzOrnogbf6gbOFXl6jKJek1pphJ9Jt%2FxfR4KYqyFdLVQC9xEJntYFHLzWm03EMRr97tAijZ6GQGNp9precX%2BBvZgst6W9N%2B6oG2kYpA%2FJj2BvRK7FGLjAdg1unUlLEHrKjWwT7JlPu2yh2EYQxfGYEdarwCztVdrdA8YmKuTJr2cyfIBHi3hhLRYOS2u6p%2B%2FIoh2qv9DwM5E%2BvlC5rsqa71gemL5LamwsuIIpXU74XPossyKVryF4LyPC9TeIWa3VKLbOczJVER%2FQkSKvpGn71%2FCigqFI6AcnxIX9cjLGXkbssGdBZxm64wQIK9TrMyKXTaKSYQy5NrLUdh1%2FZJS4dn3vV14vocR5aANIZAL0VmQbBKeFmY%2BfYba2oYf1XZInNw7Ax86AJcdG%2FpB42qY0EuYHM%2B9Y72MIKPpL0GOqUBwwg7Y7BADw5oFaLrZOEUzKPn6LScgrqk0ZoncLSHZN7ZhldNqPf3JSV8FkU%2BoPTKc%2BAH3i7Xdy%2Fb1mJ4Qj345zGCtsgnW8Vivki%2BC3aSBKYeJvjz8hP%2BFlqyW%2Bnn3e6E9a4QKfCsf3NzF2jZHw5aq%2FL9g4aT4I%2FSAOlIh8PuR%2B4mAz7iGKaNibR%2FuigND48yY4Q69VQEdajCw3iYlg2qlx1gWasA&X-Amz-Signature=f3f6e04fabcaad8945fd8753e84d11933db4cd8cb7f8c0f81ae1dfa4c603f921&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UGIDCHHT%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T222156Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCHk1zlCSlrDqWiJ6jCotgJJTwzwRGAt4zfzePrdVZs5wIgBUwD%2BvWJSvSTNCL6fqnfbfuTFYEPthbCP8jYpB5AuG0qiAQIrf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLTUV2%2FlhgpX6NTZgircA0ZZ4QryJwsDovfjo4nd7gX8fefHpibBjOpB%2FXF9hnFXSwEs4sEg44HOTxZcW9CyshrezkY%2Fgo6OA7tsBbc1uFqOEJ7Lc43vqyJA%2F2TCwJrEhIfGTqY5Xqdiv2HPRxec7PHRmIJGziVZ0SzlWUVDammHd6E2yeZg1e04fyuMbs8otGDDPZOOtmx6UsBJrPcl466uJmgd%2FLEowjAtNjw0NZt3EmHSRRzOrnogbf6gbOFXl6jKJek1pphJ9Jt%2FxfR4KYqyFdLVQC9xEJntYFHLzWm03EMRr97tAijZ6GQGNp9precX%2BBvZgst6W9N%2B6oG2kYpA%2FJj2BvRK7FGLjAdg1unUlLEHrKjWwT7JlPu2yh2EYQxfGYEdarwCztVdrdA8YmKuTJr2cyfIBHi3hhLRYOS2u6p%2B%2FIoh2qv9DwM5E%2BvlC5rsqa71gemL5LamwsuIIpXU74XPossyKVryF4LyPC9TeIWa3VKLbOczJVER%2FQkSKvpGn71%2FCigqFI6AcnxIX9cjLGXkbssGdBZxm64wQIK9TrMyKXTaKSYQy5NrLUdh1%2FZJS4dn3vV14vocR5aANIZAL0VmQbBKeFmY%2BfYba2oYf1XZInNw7Ax86AJcdG%2FpB42qY0EuYHM%2B9Y72MIKPpL0GOqUBwwg7Y7BADw5oFaLrZOEUzKPn6LScgrqk0ZoncLSHZN7ZhldNqPf3JSV8FkU%2BoPTKc%2BAH3i7Xdy%2Fb1mJ4Qj345zGCtsgnW8Vivki%2BC3aSBKYeJvjz8hP%2BFlqyW%2Bnn3e6E9a4QKfCsf3NzF2jZHw5aq%2FL9g4aT4I%2FSAOlIh8PuR%2B4mAz7iGKaNibR%2FuigND48yY4Q69VQEdajCw3iYlg2qlx1gWasA&X-Amz-Signature=39aa93da8cc5026945c5b705c908224928e50dff486db3aec0c698896fb41655&X-Amz-SignedHeaders=host&x-id=GetObject)


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

