---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4667T2MNBXW%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250205T202613Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEDIaCXVzLXdlc3QtMiJHMEUCIQD29uW2Fe%2FRV1wOWEoyfJVFINQOUD1E1uLHRYBN0s76dQIgO\
  iaAUxi0bBOe2okocGaBdyux%2BeDNl%2B%2Fno06l9WSKJwUq%2FwMIShAAGgw2Mzc0MjMxODM4MD\
  UiDIRHlOwsc7hARZl%2FaSrcA1TTp9h0mENnxi2dnoiqosyprc54Ive7Izej%2FZCqGrbQk9iWD1j\
  mWMdYIPFrDElmYqZ11dongkFzjGFHgBIK0n9OXiV2BbfcipWMS9XAp0shLRz%2Bmtdu5W%2FCWPnL\
  m%2F3%2BdWxJV9MXZV8B6CSwiKutGSOnOhxRgRk4%2BRtiM%2Bzwrto9ZKBMv9Fh9kF3zTkT8KE8G\
  m1vlsHiDAZDtKm%2FkPAnSDMV%2BNyNZeW7cY7MTcjg4EZ3qoDBLzdKR%2B7Tgg4ucykndqS3s4kO\
  5fEdqHZ%2B%2F%2Fvwn7eKIA12qfPo3WkaWr0wsHSROQVW%2BRaME6b21PWTrUzLdHo4dHz2Ctm6l\
  FoV31HaXaVW13BdWHlEuB4pKtTHWefuDU%2BCOqjjU4JdTjm1GG2YmwENF7Ui7OxWC0eorPvh9Igo\
  WZyVNnyLH1tfRVwybF%2BcGuA905cSDbdu4eZe8jmCydM%2B%2BNZlN%2BfwpaRDZcZul45UEy5dX\
  oE4zdsC3V9xEmjnuKbe2ppipVXUUD61Ll0n00W5ixG7xvZesIGihha54p%2BoQgFSYsOyNW84fF2m\
  WQ2gure0MJ8Jq7XVsWErA%2BiHWAgySnpLfrP3jQlIJ6MoXcFMwjveai61cLk5VfSBHZakK4jkvFc\
  8rTpRTBruMLK8jr0GOqUBE9jedpluBNYJpj8jy9IA7mg%2F7O09sukNrEaEyambajxUzGe%2F2xSA\
  K9dp7dDLbDGtoilxyaD6js2WSQrYV5NkF6pxdBZMlnfWHjTiw5i7vv%2F3mll0E9jNS5TF%2Fg6n3\
  rFY6HVbzTTOG%2BWXavamifIsPz2Hy6aOj9MlzE15YM0xdtgtdHOKmXAoQmmTOyThELOwhp294Wm%\
  2BzrpgF1hjRNtEa8KWqOT3&X-Amz-Signature=6b87a534ef41b392d1eb262288fe07e6ddba2f\
  ac20eb9fd20e8a9123befae73e&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB46627L2CVUU%2F20250205%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250205T202443Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEDIaCXVzLXdlc3QtMiJHMEUCIF4UEyB4h8l0NBeHoHxponVBitW78V9\
        nd%2BABhr6ecIuxAiEA2panEaKYj4htZL1DjTHwgCt0eu4MX9E9U5oUUfdfmyQq%2FwMISh\
        AAGgw2Mzc0MjMxODM4MDUiDBc09wiTo3thvV3YfSrcAzUEqs1YC4uLfZh18h11lSpRDIheL\
        P4gxHnv43PJrYch5pEKhh8%2FPP7yanBr%2B9hj9PxHVpM4FU7%2BLjwCC9PBmy%2BPAyeb\
        1lHJRKx2ivlwctpKebVrr1lCL9R6tGaWjVKSRLxXWt5E9L3PoCxgJ9E5s%2BNJW2ultwCrq\
        Y8c8Gs%2FgZGVQxbeIUH3FXwB2m9q2cXX98gmf9y2IM4ZVl44%2BhhPdcoAjnkrWpd5I%2F\
        %2BwfXJrEkNxByRpKEjiPKSDguyru0N5saDhlM3b0aLdlyDxb4NoFQLW5wmaPv6HwJuI1h%\
        2FFC7Cfv4kjuMUTpyRtdBYfk2KZ%2Bppp77xIwo2Jlj4wytEbaa5Jeij05VvSYgkcQS87W5\
        RSmRuPFniblAOOab6OeuT0aJp66Vyh3WvgDeLei9aBuId7wdGfgdhqBMjrR2N9XyKkwHscW\
        va%2Ff56voj4HJ%2B1qyIxzBT1ws49JYf%2FP0TJzS5PN0in3nzckA8tUBDmidMQw3x1ZEz\
        VzoNfj0qrIW0X8OjpYZ3qpzLy5%2FDmSaUNZfRVuwwWfk3zsj1fFEZw4HMwW3wDtHkGF7oU\
        Q2P5800%2FBnNJ7sks3A8nz5lPFsnR%2BUQzN%2BViWVhyMyNLP94rg5gE9%2BOyEtH8faJ\
        KjJw14MIq8jr0GOqUBwQQDeGxYFR6%2BVHq%2FNLc2Z8wnW7TDH8skMF9P80chPpxUaqR0Z\
        BHIhF7NVm3VdDCV4oXczqhranH519Dy%2BfYCjbt7Q12BOFP7z6Ys5%2BAZiNZNi7J5zdMv\
        oSYlC0bYIkBM6s26cRZ9N43oyeStiU4ADHQYG4O9zv6jtnW4UbecZcw3C%2BsNe0Bt7agZR\
        XwG9NM3KrP%2B1U0EnvvzVCaKYPq7ZgPxvc%2Bl&X-Amz-Signature=1bd2440595ff38a\
        d85731e2db93a3edb050f1037d28538a368fefd760ba5bb5f&X-Amz-SignedHeaders=h\
        ost&x-id=GetObject"
      expiry_time: "2025-02-05T21:24:43.492Z"
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
UPDATE_TIME: "2025-02-05T20:26:20.476Z"
EXPIRY_TIME: "2025-02-05T21:26:07.297Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YQOXNLNC%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T202607Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDIaCXVzLXdlc3QtMiJHMEUCIQCkpvQaXXZO9iswzy%2BcfyzFP%2FAd5ihBxKqOkmGNlsZRHQIgIWx4jmdocg8oU5%2FwEpLjI545fe7MmvhIlRH6XCdVyUQq%2FwMIShAAGgw2Mzc0MjMxODM4MDUiDF05wkykhefHMvKrLCrcA4vAe0szj2sSioW09aClP%2BCU61Xani5LMOtd3erG29XEYtJ2pmE1pvp50rlB5hEmQ8sdyvD1rv3wxvuxqE1%2BxctZGq8BKt94k9PWWblvJ3OiBKt%2BRL4bAATHjaSr1pmLXYCKU%2BcGc2Cj1p0dBwIWQ4phRhaXYEDyXnqmy6KI4t2%2F7G9RN2WfT3A%2Fp%2BUT4PYkyYbys9L%2FWwkxDpmYfmPQon%2FxyEjlCSR%2Fa0OjwMEgvV%2BpY1eEJ3UeTyHQbuGPmw7UZwSRvXIwjf3LCalAWzkITe5oUU6q3Q1ZcYOaZtz65UrhEJqP3g9qgod78M1xU7AU%2Blizgjevpabpui%2BEmIaW6nx%2BSHJyl6jmFl301KLPVjojq1pbVpY1saSqiR%2BBOFavqHP2UKhcxFEf0cNRxIZUFfEJmT9w8XJ8lqmO5eFys9KhgV5SUVBZ6SFzA%2BB2bLUkxJKkmTcHSzqEZGaqfrEPCDJivgDxKA5mvP1rtWEi1H8glDLduPc925UwsCbRF4TcTAWVr7tkxWrD2hQy032dnbRzCFaBdg4fiqjTktMk%2F1%2BT%2FkUGCFR5mAvSHA6msrD3KZt9b9KdyeR1pXnOlbg%2B7gomexT%2FLuI%2FmP9hcBniPNOsCYMqUzcx%2FYNctoLNMMO7jr0GOqUB9bHvwcrAji0GKd1Ze8WBceNMSnYO9oVQqIJQkjPH91I90WT%2Fpz2kQSQwPxUP70tvAwSX7YYGSCcBDwrC%2BcT0QgpY98TLRrzHtRnpRuRrKJuk3AaveJQhHGgJbuPUlIJpT063ACakHvvQx4sxn4fuqOXxEtABsmzuo%2FDV3c8o7fHcwLMxqitwSQsch4wBWXhXYQAkodiyPaeeyTrVD4N0hnH4hjJZ&X-Amz-Signature=a3f5ceae8cd90160113d8d2aa1d56f68a0255588b2a1e61e49286c372111735b&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YQOXNLNC%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T202607Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDIaCXVzLXdlc3QtMiJHMEUCIQCkpvQaXXZO9iswzy%2BcfyzFP%2FAd5ihBxKqOkmGNlsZRHQIgIWx4jmdocg8oU5%2FwEpLjI545fe7MmvhIlRH6XCdVyUQq%2FwMIShAAGgw2Mzc0MjMxODM4MDUiDF05wkykhefHMvKrLCrcA4vAe0szj2sSioW09aClP%2BCU61Xani5LMOtd3erG29XEYtJ2pmE1pvp50rlB5hEmQ8sdyvD1rv3wxvuxqE1%2BxctZGq8BKt94k9PWWblvJ3OiBKt%2BRL4bAATHjaSr1pmLXYCKU%2BcGc2Cj1p0dBwIWQ4phRhaXYEDyXnqmy6KI4t2%2F7G9RN2WfT3A%2Fp%2BUT4PYkyYbys9L%2FWwkxDpmYfmPQon%2FxyEjlCSR%2Fa0OjwMEgvV%2BpY1eEJ3UeTyHQbuGPmw7UZwSRvXIwjf3LCalAWzkITe5oUU6q3Q1ZcYOaZtz65UrhEJqP3g9qgod78M1xU7AU%2Blizgjevpabpui%2BEmIaW6nx%2BSHJyl6jmFl301KLPVjojq1pbVpY1saSqiR%2BBOFavqHP2UKhcxFEf0cNRxIZUFfEJmT9w8XJ8lqmO5eFys9KhgV5SUVBZ6SFzA%2BB2bLUkxJKkmTcHSzqEZGaqfrEPCDJivgDxKA5mvP1rtWEi1H8glDLduPc925UwsCbRF4TcTAWVr7tkxWrD2hQy032dnbRzCFaBdg4fiqjTktMk%2F1%2BT%2FkUGCFR5mAvSHA6msrD3KZt9b9KdyeR1pXnOlbg%2B7gomexT%2FLuI%2FmP9hcBniPNOsCYMqUzcx%2FYNctoLNMMO7jr0GOqUB9bHvwcrAji0GKd1Ze8WBceNMSnYO9oVQqIJQkjPH91I90WT%2Fpz2kQSQwPxUP70tvAwSX7YYGSCcBDwrC%2BcT0QgpY98TLRrzHtRnpRuRrKJuk3AaveJQhHGgJbuPUlIJpT063ACakHvvQx4sxn4fuqOXxEtABsmzuo%2FDV3c8o7fHcwLMxqitwSQsch4wBWXhXYQAkodiyPaeeyTrVD4N0hnH4hjJZ&X-Amz-Signature=cd9e205d06c9228e0f96a41c3c096f60feee84ab7acb94ec8f3f8fb94078d3b0&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YQOXNLNC%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T202607Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDIaCXVzLXdlc3QtMiJHMEUCIQCkpvQaXXZO9iswzy%2BcfyzFP%2FAd5ihBxKqOkmGNlsZRHQIgIWx4jmdocg8oU5%2FwEpLjI545fe7MmvhIlRH6XCdVyUQq%2FwMIShAAGgw2Mzc0MjMxODM4MDUiDF05wkykhefHMvKrLCrcA4vAe0szj2sSioW09aClP%2BCU61Xani5LMOtd3erG29XEYtJ2pmE1pvp50rlB5hEmQ8sdyvD1rv3wxvuxqE1%2BxctZGq8BKt94k9PWWblvJ3OiBKt%2BRL4bAATHjaSr1pmLXYCKU%2BcGc2Cj1p0dBwIWQ4phRhaXYEDyXnqmy6KI4t2%2F7G9RN2WfT3A%2Fp%2BUT4PYkyYbys9L%2FWwkxDpmYfmPQon%2FxyEjlCSR%2Fa0OjwMEgvV%2BpY1eEJ3UeTyHQbuGPmw7UZwSRvXIwjf3LCalAWzkITe5oUU6q3Q1ZcYOaZtz65UrhEJqP3g9qgod78M1xU7AU%2Blizgjevpabpui%2BEmIaW6nx%2BSHJyl6jmFl301KLPVjojq1pbVpY1saSqiR%2BBOFavqHP2UKhcxFEf0cNRxIZUFfEJmT9w8XJ8lqmO5eFys9KhgV5SUVBZ6SFzA%2BB2bLUkxJKkmTcHSzqEZGaqfrEPCDJivgDxKA5mvP1rtWEi1H8glDLduPc925UwsCbRF4TcTAWVr7tkxWrD2hQy032dnbRzCFaBdg4fiqjTktMk%2F1%2BT%2FkUGCFR5mAvSHA6msrD3KZt9b9KdyeR1pXnOlbg%2B7gomexT%2FLuI%2FmP9hcBniPNOsCYMqUzcx%2FYNctoLNMMO7jr0GOqUB9bHvwcrAji0GKd1Ze8WBceNMSnYO9oVQqIJQkjPH91I90WT%2Fpz2kQSQwPxUP70tvAwSX7YYGSCcBDwrC%2BcT0QgpY98TLRrzHtRnpRuRrKJuk3AaveJQhHGgJbuPUlIJpT063ACakHvvQx4sxn4fuqOXxEtABsmzuo%2FDV3c8o7fHcwLMxqitwSQsch4wBWXhXYQAkodiyPaeeyTrVD4N0hnH4hjJZ&X-Amz-Signature=3682eb503ab4e66fc87835c6863cf5bfefddc34e01eeded9872e2117e7320aa1&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YQOXNLNC%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T202607Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDIaCXVzLXdlc3QtMiJHMEUCIQCkpvQaXXZO9iswzy%2BcfyzFP%2FAd5ihBxKqOkmGNlsZRHQIgIWx4jmdocg8oU5%2FwEpLjI545fe7MmvhIlRH6XCdVyUQq%2FwMIShAAGgw2Mzc0MjMxODM4MDUiDF05wkykhefHMvKrLCrcA4vAe0szj2sSioW09aClP%2BCU61Xani5LMOtd3erG29XEYtJ2pmE1pvp50rlB5hEmQ8sdyvD1rv3wxvuxqE1%2BxctZGq8BKt94k9PWWblvJ3OiBKt%2BRL4bAATHjaSr1pmLXYCKU%2BcGc2Cj1p0dBwIWQ4phRhaXYEDyXnqmy6KI4t2%2F7G9RN2WfT3A%2Fp%2BUT4PYkyYbys9L%2FWwkxDpmYfmPQon%2FxyEjlCSR%2Fa0OjwMEgvV%2BpY1eEJ3UeTyHQbuGPmw7UZwSRvXIwjf3LCalAWzkITe5oUU6q3Q1ZcYOaZtz65UrhEJqP3g9qgod78M1xU7AU%2Blizgjevpabpui%2BEmIaW6nx%2BSHJyl6jmFl301KLPVjojq1pbVpY1saSqiR%2BBOFavqHP2UKhcxFEf0cNRxIZUFfEJmT9w8XJ8lqmO5eFys9KhgV5SUVBZ6SFzA%2BB2bLUkxJKkmTcHSzqEZGaqfrEPCDJivgDxKA5mvP1rtWEi1H8glDLduPc925UwsCbRF4TcTAWVr7tkxWrD2hQy032dnbRzCFaBdg4fiqjTktMk%2F1%2BT%2FkUGCFR5mAvSHA6msrD3KZt9b9KdyeR1pXnOlbg%2B7gomexT%2FLuI%2FmP9hcBniPNOsCYMqUzcx%2FYNctoLNMMO7jr0GOqUB9bHvwcrAji0GKd1Ze8WBceNMSnYO9oVQqIJQkjPH91I90WT%2Fpz2kQSQwPxUP70tvAwSX7YYGSCcBDwrC%2BcT0QgpY98TLRrzHtRnpRuRrKJuk3AaveJQhHGgJbuPUlIJpT063ACakHvvQx4sxn4fuqOXxEtABsmzuo%2FDV3c8o7fHcwLMxqitwSQsch4wBWXhXYQAkodiyPaeeyTrVD4N0hnH4hjJZ&X-Amz-Signature=37b9098c27ac2e9bcd903157f3ddbcc828423a17a82174eedb13ec617d79209d&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YQOXNLNC%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T202607Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDIaCXVzLXdlc3QtMiJHMEUCIQCkpvQaXXZO9iswzy%2BcfyzFP%2FAd5ihBxKqOkmGNlsZRHQIgIWx4jmdocg8oU5%2FwEpLjI545fe7MmvhIlRH6XCdVyUQq%2FwMIShAAGgw2Mzc0MjMxODM4MDUiDF05wkykhefHMvKrLCrcA4vAe0szj2sSioW09aClP%2BCU61Xani5LMOtd3erG29XEYtJ2pmE1pvp50rlB5hEmQ8sdyvD1rv3wxvuxqE1%2BxctZGq8BKt94k9PWWblvJ3OiBKt%2BRL4bAATHjaSr1pmLXYCKU%2BcGc2Cj1p0dBwIWQ4phRhaXYEDyXnqmy6KI4t2%2F7G9RN2WfT3A%2Fp%2BUT4PYkyYbys9L%2FWwkxDpmYfmPQon%2FxyEjlCSR%2Fa0OjwMEgvV%2BpY1eEJ3UeTyHQbuGPmw7UZwSRvXIwjf3LCalAWzkITe5oUU6q3Q1ZcYOaZtz65UrhEJqP3g9qgod78M1xU7AU%2Blizgjevpabpui%2BEmIaW6nx%2BSHJyl6jmFl301KLPVjojq1pbVpY1saSqiR%2BBOFavqHP2UKhcxFEf0cNRxIZUFfEJmT9w8XJ8lqmO5eFys9KhgV5SUVBZ6SFzA%2BB2bLUkxJKkmTcHSzqEZGaqfrEPCDJivgDxKA5mvP1rtWEi1H8glDLduPc925UwsCbRF4TcTAWVr7tkxWrD2hQy032dnbRzCFaBdg4fiqjTktMk%2F1%2BT%2FkUGCFR5mAvSHA6msrD3KZt9b9KdyeR1pXnOlbg%2B7gomexT%2FLuI%2FmP9hcBniPNOsCYMqUzcx%2FYNctoLNMMO7jr0GOqUB9bHvwcrAji0GKd1Ze8WBceNMSnYO9oVQqIJQkjPH91I90WT%2Fpz2kQSQwPxUP70tvAwSX7YYGSCcBDwrC%2BcT0QgpY98TLRrzHtRnpRuRrKJuk3AaveJQhHGgJbuPUlIJpT063ACakHvvQx4sxn4fuqOXxEtABsmzuo%2FDV3c8o7fHcwLMxqitwSQsch4wBWXhXYQAkodiyPaeeyTrVD4N0hnH4hjJZ&X-Amz-Signature=32f7b81bb18644b3c34ed90ea8784fb6d6abdbc169d3e5816a7280302f3d1620&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662ZKJHQQB%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T202610Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDIaCXVzLXdlc3QtMiJIMEYCIQC9VA6qs29QJKJCPL5fL1BLGQOLP5kQ3d77jmyBEB7kNwIhANMyekKoosUIpprrvk0a3N9E5aesPztK%2FVcqBS809TErKv8DCEoQABoMNjM3NDIzMTgzODA1IgzH80ysYFZmeCoKoYAq3AOvYASxcnpd3T28OwYPmt9Q7ezvUE63kPa2qw6CgqEaNMRGreXW0kH7oaG7npvvi1Yz9MI6c%2BFB0bSy6DK3STHY7OV%2Fl0CaPert%2FPag9yQ4PWjaTs0s5kM4e0DGV84nvlf4wczZ5EJwGCkYiYlNbfNPiXOzPlF4e%2FaYyX7J61hujF1IhHShv83kBdd6cWumMmSCKzh5tl9gg%2BjK96d7FWm6iom3MwnxBGEZ73ctd2%2FqYvLzodBPdqlyg%2BkJxf3mAHm%2FpHD1P3isj8JtZHwlbip8p74hCF%2Fb8or5YEo%2BZg8sTMnNq4%2Fqk2ioaPwSfub%2Bzx9kPiyZuyy8ASiEO00x5jhRrMvqi1XLtxo9lWMGXjH86pLdGiMNZtL2XigRozOtJs2g4kUXOlfZydcxTQmko2ZgiNLRYdWfzJNXoVUs827gQjju4ihZd8rUeSpacbBVhmgoSC0uszM9MXyb786An7ykZsNFjo%2B3XKt8%2FoAhoCzGJeHV%2F%2F8xuiR5XoghKTVpTjatRzNm80%2FfY8P88tbHwu2expJa%2B8U%2FdVzqKYpcEHrWmfoYwqEWNKJeWL4xNIGJQtkqE7xQX5drVoa4HKLpF3PouE3nlq7YLBau02UYFmnbLlXfOVZYFFk09qdcZTDsu469BjqkAcJoO6Y61F4V0kIi8jn7mx141j79H9k6doLlKTsTS8BYrgH5JWb2zjybAr1PhejLIrnbhjb2ReKyBwSjc4n6bxDdY82dzTxR838ds3CInc7XmbWk0GOFgUucHenq6%2FCMaYRfJrBQakUcgG%2FC%2F4tkR8CSOURsC4e5JABIv2iZTEHblagwcjZPWLDAIfUVZ%2F4VRV13ErPSZWktky%2BCm6mS9SSZwbIn&X-Amz-Signature=a964f546639a83298fdbc7b8cdf4651a3737197942c83e9530ed14285bd92f3c&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46644PEDNZI%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T202612Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDIaCXVzLXdlc3QtMiJGMEQCIH2emzlUXlvolKkjQVzaGzr4bcWFTFhuCw6bMtU63VbLAiBHXH3QithhFa9nwCaFinyit9zuWHieP7OTze8TzEddbCr%2FAwhKEAAaDDYzNzQyMzE4MzgwNSIMmRjgmPh89vnL4%2BCKKtwDElrzw%2FKPfVPXkElxtACogvFq77eYryAWnCpVKMWcz8F7wCRuG1souAPKWdsJTuE%2BbJJ9sCb%2F%2BvFAxtZ1uLJGGxVWD2QUXIk7dGNsaNGNMSCP5sh1M%2FJ5dxQOfkd7q%2FrC22WnQo%2F%2Beisfn0k%2BK9PT7Ddo6F0Id6tEBwkngytSQPQUFY%2BGL0lGySM54k9EJTWX9n5JTrd9oRv3AvJJQnwLQfqIcdDKd3EEWmMDqNJKTL6%2BWDpp85vsrsHBb1ZzVVIW01R2lBPDieK1Yj6n7zhIZgPAOcHPTJNEn%2Fr%2FrcBXvvyxlyZpIadgryPWcAOlQ3QSy%2Bkx4EmXPA%2FHKS9%2BDbUQmy%2BYvggvd4ma5L39yFDU290XNvwPXF4ta5f7RJQ7I2A%2Bjw28z0%2BoholiJ9OOAN2zQDvnTs%2BOVFoMZj%2Bv0vN3pMZKbY7tVhuhX8j9JFu0ikq7vYiYJ63nWQStynB%2BYrhlLF34p5Ibhk72PEApqDjlFXFpmh4l1j5fH%2FHyLahUa%2BUYfe%2Bq84vOmSgUWiC1zuOak5POfYwL5hSJiv%2BD%2BgCC240dHCO8E%2BuyNjax8R1WsbKuF3QN5KJUtukjADUTEEpVYyPK7g9lsv8KbiSckFDUg%2FOJHKOJBWyChZlO50Ew9buOvQY6pgF6boc1n5mkaihQp%2Fa0fFjDK9zlTSY4L9V7RgSbT11M%2BOHXRZf1baBShHdppxItdQouYrRgXTp97NsWG9KlnUWEZU%2FWAf6p%2B%2BlUVVUtXRP3vt3i5xm5Et58NF4xxX%2BONMWdLOz7Bt0OMvpwzxG429y%2BSV74BUNAzhspKvn2qEF%2Fs3TbjAL4PRt6753zCryu131G8Dvu9QIurSlCdyhnrT8xeQ1IYkXu&X-Amz-Signature=9a62f1280a9830ea345e397162817c6f62026164aa2d9ab56187b557dfb4c5ae&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YQOXNLNC%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T202607Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDIaCXVzLXdlc3QtMiJHMEUCIQCkpvQaXXZO9iswzy%2BcfyzFP%2FAd5ihBxKqOkmGNlsZRHQIgIWx4jmdocg8oU5%2FwEpLjI545fe7MmvhIlRH6XCdVyUQq%2FwMIShAAGgw2Mzc0MjMxODM4MDUiDF05wkykhefHMvKrLCrcA4vAe0szj2sSioW09aClP%2BCU61Xani5LMOtd3erG29XEYtJ2pmE1pvp50rlB5hEmQ8sdyvD1rv3wxvuxqE1%2BxctZGq8BKt94k9PWWblvJ3OiBKt%2BRL4bAATHjaSr1pmLXYCKU%2BcGc2Cj1p0dBwIWQ4phRhaXYEDyXnqmy6KI4t2%2F7G9RN2WfT3A%2Fp%2BUT4PYkyYbys9L%2FWwkxDpmYfmPQon%2FxyEjlCSR%2Fa0OjwMEgvV%2BpY1eEJ3UeTyHQbuGPmw7UZwSRvXIwjf3LCalAWzkITe5oUU6q3Q1ZcYOaZtz65UrhEJqP3g9qgod78M1xU7AU%2Blizgjevpabpui%2BEmIaW6nx%2BSHJyl6jmFl301KLPVjojq1pbVpY1saSqiR%2BBOFavqHP2UKhcxFEf0cNRxIZUFfEJmT9w8XJ8lqmO5eFys9KhgV5SUVBZ6SFzA%2BB2bLUkxJKkmTcHSzqEZGaqfrEPCDJivgDxKA5mvP1rtWEi1H8glDLduPc925UwsCbRF4TcTAWVr7tkxWrD2hQy032dnbRzCFaBdg4fiqjTktMk%2F1%2BT%2FkUGCFR5mAvSHA6msrD3KZt9b9KdyeR1pXnOlbg%2B7gomexT%2FLuI%2FmP9hcBniPNOsCYMqUzcx%2FYNctoLNMMO7jr0GOqUB9bHvwcrAji0GKd1Ze8WBceNMSnYO9oVQqIJQkjPH91I90WT%2Fpz2kQSQwPxUP70tvAwSX7YYGSCcBDwrC%2BcT0QgpY98TLRrzHtRnpRuRrKJuk3AaveJQhHGgJbuPUlIJpT063ACakHvvQx4sxn4fuqOXxEtABsmzuo%2FDV3c8o7fHcwLMxqitwSQsch4wBWXhXYQAkodiyPaeeyTrVD4N0hnH4hjJZ&X-Amz-Signature=88791f4d68a92b4c8461e6d8460bf7ea9b3c739df1b2bd667fb9039b8c90f3c4&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YQOXNLNC%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T202607Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDIaCXVzLXdlc3QtMiJHMEUCIQCkpvQaXXZO9iswzy%2BcfyzFP%2FAd5ihBxKqOkmGNlsZRHQIgIWx4jmdocg8oU5%2FwEpLjI545fe7MmvhIlRH6XCdVyUQq%2FwMIShAAGgw2Mzc0MjMxODM4MDUiDF05wkykhefHMvKrLCrcA4vAe0szj2sSioW09aClP%2BCU61Xani5LMOtd3erG29XEYtJ2pmE1pvp50rlB5hEmQ8sdyvD1rv3wxvuxqE1%2BxctZGq8BKt94k9PWWblvJ3OiBKt%2BRL4bAATHjaSr1pmLXYCKU%2BcGc2Cj1p0dBwIWQ4phRhaXYEDyXnqmy6KI4t2%2F7G9RN2WfT3A%2Fp%2BUT4PYkyYbys9L%2FWwkxDpmYfmPQon%2FxyEjlCSR%2Fa0OjwMEgvV%2BpY1eEJ3UeTyHQbuGPmw7UZwSRvXIwjf3LCalAWzkITe5oUU6q3Q1ZcYOaZtz65UrhEJqP3g9qgod78M1xU7AU%2Blizgjevpabpui%2BEmIaW6nx%2BSHJyl6jmFl301KLPVjojq1pbVpY1saSqiR%2BBOFavqHP2UKhcxFEf0cNRxIZUFfEJmT9w8XJ8lqmO5eFys9KhgV5SUVBZ6SFzA%2BB2bLUkxJKkmTcHSzqEZGaqfrEPCDJivgDxKA5mvP1rtWEi1H8glDLduPc925UwsCbRF4TcTAWVr7tkxWrD2hQy032dnbRzCFaBdg4fiqjTktMk%2F1%2BT%2FkUGCFR5mAvSHA6msrD3KZt9b9KdyeR1pXnOlbg%2B7gomexT%2FLuI%2FmP9hcBniPNOsCYMqUzcx%2FYNctoLNMMO7jr0GOqUB9bHvwcrAji0GKd1Ze8WBceNMSnYO9oVQqIJQkjPH91I90WT%2Fpz2kQSQwPxUP70tvAwSX7YYGSCcBDwrC%2BcT0QgpY98TLRrzHtRnpRuRrKJuk3AaveJQhHGgJbuPUlIJpT063ACakHvvQx4sxn4fuqOXxEtABsmzuo%2FDV3c8o7fHcwLMxqitwSQsch4wBWXhXYQAkodiyPaeeyTrVD4N0hnH4hjJZ&X-Amz-Signature=04db743b7085d6d81483a3de3efbd06a91316a265b67cc8d5cd55df80e1842be&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YQOXNLNC%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T202607Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDIaCXVzLXdlc3QtMiJHMEUCIQCkpvQaXXZO9iswzy%2BcfyzFP%2FAd5ihBxKqOkmGNlsZRHQIgIWx4jmdocg8oU5%2FwEpLjI545fe7MmvhIlRH6XCdVyUQq%2FwMIShAAGgw2Mzc0MjMxODM4MDUiDF05wkykhefHMvKrLCrcA4vAe0szj2sSioW09aClP%2BCU61Xani5LMOtd3erG29XEYtJ2pmE1pvp50rlB5hEmQ8sdyvD1rv3wxvuxqE1%2BxctZGq8BKt94k9PWWblvJ3OiBKt%2BRL4bAATHjaSr1pmLXYCKU%2BcGc2Cj1p0dBwIWQ4phRhaXYEDyXnqmy6KI4t2%2F7G9RN2WfT3A%2Fp%2BUT4PYkyYbys9L%2FWwkxDpmYfmPQon%2FxyEjlCSR%2Fa0OjwMEgvV%2BpY1eEJ3UeTyHQbuGPmw7UZwSRvXIwjf3LCalAWzkITe5oUU6q3Q1ZcYOaZtz65UrhEJqP3g9qgod78M1xU7AU%2Blizgjevpabpui%2BEmIaW6nx%2BSHJyl6jmFl301KLPVjojq1pbVpY1saSqiR%2BBOFavqHP2UKhcxFEf0cNRxIZUFfEJmT9w8XJ8lqmO5eFys9KhgV5SUVBZ6SFzA%2BB2bLUkxJKkmTcHSzqEZGaqfrEPCDJivgDxKA5mvP1rtWEi1H8glDLduPc925UwsCbRF4TcTAWVr7tkxWrD2hQy032dnbRzCFaBdg4fiqjTktMk%2F1%2BT%2FkUGCFR5mAvSHA6msrD3KZt9b9KdyeR1pXnOlbg%2B7gomexT%2FLuI%2FmP9hcBniPNOsCYMqUzcx%2FYNctoLNMMO7jr0GOqUB9bHvwcrAji0GKd1Ze8WBceNMSnYO9oVQqIJQkjPH91I90WT%2Fpz2kQSQwPxUP70tvAwSX7YYGSCcBDwrC%2BcT0QgpY98TLRrzHtRnpRuRrKJuk3AaveJQhHGgJbuPUlIJpT063ACakHvvQx4sxn4fuqOXxEtABsmzuo%2FDV3c8o7fHcwLMxqitwSQsch4wBWXhXYQAkodiyPaeeyTrVD4N0hnH4hjJZ&X-Amz-Signature=5e461c2d0d5abf84fcd53124b0ef8d4ff5b94dd0e5b770481f6073ebee3657d6&X-Amz-SignedHeaders=host&x-id=GetObject)


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

