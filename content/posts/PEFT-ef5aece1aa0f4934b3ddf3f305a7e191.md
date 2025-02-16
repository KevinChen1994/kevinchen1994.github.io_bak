---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466QAL4POV2%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250216T102257Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEC4aCXVzLXdlc3QtMiJHMEUCICmhr5F5vtm5jSytrjOfB9DRmY%2BvRePnGlgQfHoTdjSMAiEAy\
  6DbDwBuFbNL4E1J%2FQo5cT2QVSIuKZYiAoKnsi2gkrsq%2FwMIVxAAGgw2Mzc0MjMxODM4MDUiDA\
  %2BRD9JFCCwZ4i5zYCrcA%2FYAb609p7MBbZWrQYQ5QeLkIF1NI7iOJ0mL04PmV6sq2hLZWvEx9qs\
  WfwFpomNc0KRfXOHeolHL3ejMkuLnSAs9H%2B2ui3zt%2B5z8Y9VPgWBKk4R9%2Bi9Ibz%2Bsgfip\
  Tvnqh9Q%2BWHQnCQMtlU%2BtW0dzW4tuZERdzJuQhhKJzEEAX%2B%2BQaZAtSevtHaMXyPEH7w60k\
  cxxA4KlEj30P0zjREjcI%2FPF2EnkJORvgbxRPUb83L8ih9zgPh2JFrvzFSRDpD%2FDmeD%2BJsGM\
  TDiNwlYpyNPIe1yr%2Fqdja1ui5o1%2F0WC%2BDDWxjtJvAXXUOjYDC33QLJLUTpA6uVJme5YiOIH\
  6xSo4P1R1%2F6DsRghvrXYKHMoXz4lCuhA0lhhu9t8Jw%2BRMAXzmEPH8WZyqSbOZdh0EyoB%2Btq\
  4swoTjDA1Y7C0UA4QduS%2Bz%2FBRkLaryyYr8BmFWaezp7rF6Zp3MU1EGei821u9VHY10LrEPG7A\
  5Vvvy77UDLuJKJpaZQg2XfDFBZxDZnFStq2Q9cqmUQoQ2ae7Tp2ZlIYghDMNdMinFltWFBDZ8XjL%\
  2BQAbdjLo88XGrt7vzCyRT4N4Ym9afnkt%2FIp48ZKkE2kMj%2Bj6OkiNGdAQZQv4txHxlExKUgOa\
  HbQ88%2BBIkMNX9xb0GOqUBjRzsXE33CujJDxl98uH9kY5xU0VMqKctYWL4%2FB%2Bi9NXvXXN4%2\
  BhXNeMqAuYn7VcOS5glthqvjDULIFrpMQfbPXbNYx7M1X94ZvT6XVFuDqdz1GIniVXhoRvcoe5YPo\
  fJr%2F5lC7%2FOmfxLz1Qk6thV6SCuOqttZ8rJ%2FU%2BwYgY0a0z57HbrAre2GCN2eWsSrxoE0eW\
  SwP8nEVNMUuKHXV6WzQLp%2FFiZ0&X-Amz-Signature=6e98031f5705a05deda7c3ea9b7cf09a\
  6b9578b6011bfce15e413a10899eff87&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4663VZ465JU%2F20250216%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250216T102140Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEC4aCXVzLXdlc3QtMiJGMEQCIBJy7QstPqpLnCd9P5LHwxykSBrIDO0\
        fzNV1SWyEziWTAiB8VqHWltTQ5ELqIYHKPhVfYiNAuMRHb4c%2BAjPobqk2ISr%2FAwhXEA\
        AaDDYzNzQyMzE4MzgwNSIMPgvbTO5Po1cJGcZPKtwDc%2Fod0mDiOFOYf2jQPmXq1qZl%2F\
        Si5aI1tH%2BEWXRCqApvg%2BahUPyOFvT%2FSr4LKaOqX%2Fl9D2jh%2F7FEykALgVn5ub%\
        2BDeQup0qgiBOIkOsFvAde8Z7c1oKTck9bH%2Fol8r0DahDJ9BxV2O4%2BX9s79ZN7XcsJg\
        YYJWzmgvjZ8cc1TMgqbNMCYaxnrq9eAoWJUxpQPaLt8%2FjjNsygOdpvBrID4pXdYVxeUYH\
        jZVy5bIGjNNdPgRRbZNLVoV8OXr63Uk8UvfsLBP%2BhgLAG3l1t5AZJv07AQYHjCa1swy1%\
        2BDIi55QjEdYJOY4oAxMbeokx74vjtE%2FRdXVXjjRFrcWizIKPXWMrzvX2%2BUz14dk2Z2\
        xzVA34sFwc0yCFv8OYBlBIV6IGef435VDrnypI6R7lF4y6A6D9%2F%2BxmTKX2B1%2Foq%2\
        BAVkqg0iz%2BxJEUTTyl96KCkCrnDfdFSeX2n9i5%2Fu1UbDl90MhfE4q3DbvSMEA01xz64\
        ne4u2xxpDICADrgxg4pTirnt0P4Arj6Q9qo3ifSRPkM4mILzrNy1cm3cJeqmgnMvngGaluX\
        4c3w%2BKbGpD0lKQn6TZKurfwdSTzXDgckk99rdnU6e8QIo%2FepjZimAJ7R0mWrNYvpNlT\
        7f0o89Px%2BiMQAwgP7FvQY6pgEEgq9xD9GUEvkiVlQfio%2BAYahq%2BGD0opxA9OG8gax\
        NNZnrmKLA5nOlHJyG32Dx%2BZOEj1a960P6oh02rGF%2BEP3htMr5cKjw%2BNl5apDW%2BB\
        sSovi4EV9atn%2Fp8MOKjiMs3%2FtOJOD2n4R8VoyqzoL%2Bd%2BDPkqzvK3wUmwqutIlsI\
        yUhBVguSuDXoJuzNpM1zsWGmT%2BqnHJSVO4oetcqT%2FuzeWIRtTNsc4vD&X-Amz-Signa\
        ture=56fd1c1116d9fa2e9ac852030f0af670abed8f2fe3a32b45def52d1e77cd4327&X\
        -Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-16T11:21:40.950Z"
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
UPDATE_TIME: "2025-02-16T10:23:00.852Z"
EXPIRY_TIME: "2025-02-16T11:22:55.688Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666IYIAVQT%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T102255Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEC4aCXVzLXdlc3QtMiJHMEUCIQC46iADESObEWdId7p3onQoZQACfQJSqrk4qk2Ln7I3QgIgc2btMPe0LOyvH%2FUXQ%2Fad6FOfPgYUOoh6jUmXzxVv8zoq%2FwMIVxAAGgw2Mzc0MjMxODM4MDUiDH%2BvFHCVzuwrcixiFyrcA5d3QZ8e66XKD%2BdOM1bvzKa5Yh9OXXWG64fQ6P%2FPDU%2Bfrrgss5zG4rwWlxfgpXNi4NWLDNyA4snOnlWgc1nteDghprJUVCQt%2B7sit0%2FWFhp0%2B9IpimANG57met8TKzOEvyKldTgY5%2F88OI%2Ff0%2BmtNRDl9F75a%2Bh3iFGKXNiqhyvDATFvBDdfvAds8MJS2AjHFCEctyE4h6dp7nnXtVmvU7M1HrQ1MkjKe5jw1yOddEGhqRrJhvjVR9wkoEX%2FwpKEGMZ0gj1TNC44%2F1YOsLeI7wquLhYN%2Bivksy4xmckrDQ7uT%2BUMnkCEm%2FnUSneFBFJ2V0bULv22czd1urv%2BrgvgrqAzNrrae0VyoZ4wYyVEhV9GJYLN%2FVwoaxfUuoqzp11KGPr7e55L0fRMTQeTpCx5AcF0dhobuRq6DtGYr46AOL8tBfwnjtbqT5DmevDLnYb0eIWb5xS%2BhOx72GzdWZiFoWC8VcvUX5c3wR0puu%2BOqP9x9xgCwGnCuQw1rvgdyuKbRP%2B73mLaqFyvPNZw97ZOQ2A737g2RxX2xkG%2BQ6idU8jrTiu3nlnmlayshy3jvvJOwhAoo81Iu4rSvJ4ZzPntl0ziGthPHWkUPbqS3ZInzXUr2fVU%2F3mtqVDtfpNyMMH9xb0GOqUBCZXL9CvH3AI42baJ%2FHyYY6IEMlrhRPnaEdhsHsgdj0k59sl2AOfk7hCC3bHnHPKFjTCviwNN9SCsFrd0VH20eqbv1EBUPy9fCP61wdJrV61hYWY8UPqURzjqne5BsHjY3jlSwzjPLWJ0YtbIKBA0jOCR%2B0G99vwSi7YiogUJ18gaE9gCDUIoECSYuHn7xmTquEYxUOhptowEGJcMbEt5OSXFrjAV&X-Amz-Signature=0d9b2507695d44fa09777d8d4446a095ed23ffb5f48485e40caccbac62d906a2&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666IYIAVQT%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T102255Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEC4aCXVzLXdlc3QtMiJHMEUCIQC46iADESObEWdId7p3onQoZQACfQJSqrk4qk2Ln7I3QgIgc2btMPe0LOyvH%2FUXQ%2Fad6FOfPgYUOoh6jUmXzxVv8zoq%2FwMIVxAAGgw2Mzc0MjMxODM4MDUiDH%2BvFHCVzuwrcixiFyrcA5d3QZ8e66XKD%2BdOM1bvzKa5Yh9OXXWG64fQ6P%2FPDU%2Bfrrgss5zG4rwWlxfgpXNi4NWLDNyA4snOnlWgc1nteDghprJUVCQt%2B7sit0%2FWFhp0%2B9IpimANG57met8TKzOEvyKldTgY5%2F88OI%2Ff0%2BmtNRDl9F75a%2Bh3iFGKXNiqhyvDATFvBDdfvAds8MJS2AjHFCEctyE4h6dp7nnXtVmvU7M1HrQ1MkjKe5jw1yOddEGhqRrJhvjVR9wkoEX%2FwpKEGMZ0gj1TNC44%2F1YOsLeI7wquLhYN%2Bivksy4xmckrDQ7uT%2BUMnkCEm%2FnUSneFBFJ2V0bULv22czd1urv%2BrgvgrqAzNrrae0VyoZ4wYyVEhV9GJYLN%2FVwoaxfUuoqzp11KGPr7e55L0fRMTQeTpCx5AcF0dhobuRq6DtGYr46AOL8tBfwnjtbqT5DmevDLnYb0eIWb5xS%2BhOx72GzdWZiFoWC8VcvUX5c3wR0puu%2BOqP9x9xgCwGnCuQw1rvgdyuKbRP%2B73mLaqFyvPNZw97ZOQ2A737g2RxX2xkG%2BQ6idU8jrTiu3nlnmlayshy3jvvJOwhAoo81Iu4rSvJ4ZzPntl0ziGthPHWkUPbqS3ZInzXUr2fVU%2F3mtqVDtfpNyMMH9xb0GOqUBCZXL9CvH3AI42baJ%2FHyYY6IEMlrhRPnaEdhsHsgdj0k59sl2AOfk7hCC3bHnHPKFjTCviwNN9SCsFrd0VH20eqbv1EBUPy9fCP61wdJrV61hYWY8UPqURzjqne5BsHjY3jlSwzjPLWJ0YtbIKBA0jOCR%2B0G99vwSi7YiogUJ18gaE9gCDUIoECSYuHn7xmTquEYxUOhptowEGJcMbEt5OSXFrjAV&X-Amz-Signature=555c30cf730c2a510df8f7645c1f1923c8cc88386533c6755d59f8f8a8223606&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666IYIAVQT%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T102256Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEC4aCXVzLXdlc3QtMiJHMEUCIQC46iADESObEWdId7p3onQoZQACfQJSqrk4qk2Ln7I3QgIgc2btMPe0LOyvH%2FUXQ%2Fad6FOfPgYUOoh6jUmXzxVv8zoq%2FwMIVxAAGgw2Mzc0MjMxODM4MDUiDH%2BvFHCVzuwrcixiFyrcA5d3QZ8e66XKD%2BdOM1bvzKa5Yh9OXXWG64fQ6P%2FPDU%2Bfrrgss5zG4rwWlxfgpXNi4NWLDNyA4snOnlWgc1nteDghprJUVCQt%2B7sit0%2FWFhp0%2B9IpimANG57met8TKzOEvyKldTgY5%2F88OI%2Ff0%2BmtNRDl9F75a%2Bh3iFGKXNiqhyvDATFvBDdfvAds8MJS2AjHFCEctyE4h6dp7nnXtVmvU7M1HrQ1MkjKe5jw1yOddEGhqRrJhvjVR9wkoEX%2FwpKEGMZ0gj1TNC44%2F1YOsLeI7wquLhYN%2Bivksy4xmckrDQ7uT%2BUMnkCEm%2FnUSneFBFJ2V0bULv22czd1urv%2BrgvgrqAzNrrae0VyoZ4wYyVEhV9GJYLN%2FVwoaxfUuoqzp11KGPr7e55L0fRMTQeTpCx5AcF0dhobuRq6DtGYr46AOL8tBfwnjtbqT5DmevDLnYb0eIWb5xS%2BhOx72GzdWZiFoWC8VcvUX5c3wR0puu%2BOqP9x9xgCwGnCuQw1rvgdyuKbRP%2B73mLaqFyvPNZw97ZOQ2A737g2RxX2xkG%2BQ6idU8jrTiu3nlnmlayshy3jvvJOwhAoo81Iu4rSvJ4ZzPntl0ziGthPHWkUPbqS3ZInzXUr2fVU%2F3mtqVDtfpNyMMH9xb0GOqUBCZXL9CvH3AI42baJ%2FHyYY6IEMlrhRPnaEdhsHsgdj0k59sl2AOfk7hCC3bHnHPKFjTCviwNN9SCsFrd0VH20eqbv1EBUPy9fCP61wdJrV61hYWY8UPqURzjqne5BsHjY3jlSwzjPLWJ0YtbIKBA0jOCR%2B0G99vwSi7YiogUJ18gaE9gCDUIoECSYuHn7xmTquEYxUOhptowEGJcMbEt5OSXFrjAV&X-Amz-Signature=4ae54e4a0ea32c09c5ee2cb0176a65d50730af6c5069b653bb6adabc24fa301f&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666IYIAVQT%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T102256Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEC4aCXVzLXdlc3QtMiJHMEUCIQC46iADESObEWdId7p3onQoZQACfQJSqrk4qk2Ln7I3QgIgc2btMPe0LOyvH%2FUXQ%2Fad6FOfPgYUOoh6jUmXzxVv8zoq%2FwMIVxAAGgw2Mzc0MjMxODM4MDUiDH%2BvFHCVzuwrcixiFyrcA5d3QZ8e66XKD%2BdOM1bvzKa5Yh9OXXWG64fQ6P%2FPDU%2Bfrrgss5zG4rwWlxfgpXNi4NWLDNyA4snOnlWgc1nteDghprJUVCQt%2B7sit0%2FWFhp0%2B9IpimANG57met8TKzOEvyKldTgY5%2F88OI%2Ff0%2BmtNRDl9F75a%2Bh3iFGKXNiqhyvDATFvBDdfvAds8MJS2AjHFCEctyE4h6dp7nnXtVmvU7M1HrQ1MkjKe5jw1yOddEGhqRrJhvjVR9wkoEX%2FwpKEGMZ0gj1TNC44%2F1YOsLeI7wquLhYN%2Bivksy4xmckrDQ7uT%2BUMnkCEm%2FnUSneFBFJ2V0bULv22czd1urv%2BrgvgrqAzNrrae0VyoZ4wYyVEhV9GJYLN%2FVwoaxfUuoqzp11KGPr7e55L0fRMTQeTpCx5AcF0dhobuRq6DtGYr46AOL8tBfwnjtbqT5DmevDLnYb0eIWb5xS%2BhOx72GzdWZiFoWC8VcvUX5c3wR0puu%2BOqP9x9xgCwGnCuQw1rvgdyuKbRP%2B73mLaqFyvPNZw97ZOQ2A737g2RxX2xkG%2BQ6idU8jrTiu3nlnmlayshy3jvvJOwhAoo81Iu4rSvJ4ZzPntl0ziGthPHWkUPbqS3ZInzXUr2fVU%2F3mtqVDtfpNyMMH9xb0GOqUBCZXL9CvH3AI42baJ%2FHyYY6IEMlrhRPnaEdhsHsgdj0k59sl2AOfk7hCC3bHnHPKFjTCviwNN9SCsFrd0VH20eqbv1EBUPy9fCP61wdJrV61hYWY8UPqURzjqne5BsHjY3jlSwzjPLWJ0YtbIKBA0jOCR%2B0G99vwSi7YiogUJ18gaE9gCDUIoECSYuHn7xmTquEYxUOhptowEGJcMbEt5OSXFrjAV&X-Amz-Signature=866d082db2904c4923b97c711faf95550d8fd1856a511f3d33c60eb2b6736f4b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666IYIAVQT%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T102256Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEC4aCXVzLXdlc3QtMiJHMEUCIQC46iADESObEWdId7p3onQoZQACfQJSqrk4qk2Ln7I3QgIgc2btMPe0LOyvH%2FUXQ%2Fad6FOfPgYUOoh6jUmXzxVv8zoq%2FwMIVxAAGgw2Mzc0MjMxODM4MDUiDH%2BvFHCVzuwrcixiFyrcA5d3QZ8e66XKD%2BdOM1bvzKa5Yh9OXXWG64fQ6P%2FPDU%2Bfrrgss5zG4rwWlxfgpXNi4NWLDNyA4snOnlWgc1nteDghprJUVCQt%2B7sit0%2FWFhp0%2B9IpimANG57met8TKzOEvyKldTgY5%2F88OI%2Ff0%2BmtNRDl9F75a%2Bh3iFGKXNiqhyvDATFvBDdfvAds8MJS2AjHFCEctyE4h6dp7nnXtVmvU7M1HrQ1MkjKe5jw1yOddEGhqRrJhvjVR9wkoEX%2FwpKEGMZ0gj1TNC44%2F1YOsLeI7wquLhYN%2Bivksy4xmckrDQ7uT%2BUMnkCEm%2FnUSneFBFJ2V0bULv22czd1urv%2BrgvgrqAzNrrae0VyoZ4wYyVEhV9GJYLN%2FVwoaxfUuoqzp11KGPr7e55L0fRMTQeTpCx5AcF0dhobuRq6DtGYr46AOL8tBfwnjtbqT5DmevDLnYb0eIWb5xS%2BhOx72GzdWZiFoWC8VcvUX5c3wR0puu%2BOqP9x9xgCwGnCuQw1rvgdyuKbRP%2B73mLaqFyvPNZw97ZOQ2A737g2RxX2xkG%2BQ6idU8jrTiu3nlnmlayshy3jvvJOwhAoo81Iu4rSvJ4ZzPntl0ziGthPHWkUPbqS3ZInzXUr2fVU%2F3mtqVDtfpNyMMH9xb0GOqUBCZXL9CvH3AI42baJ%2FHyYY6IEMlrhRPnaEdhsHsgdj0k59sl2AOfk7hCC3bHnHPKFjTCviwNN9SCsFrd0VH20eqbv1EBUPy9fCP61wdJrV61hYWY8UPqURzjqne5BsHjY3jlSwzjPLWJ0YtbIKBA0jOCR%2B0G99vwSi7YiogUJ18gaE9gCDUIoECSYuHn7xmTquEYxUOhptowEGJcMbEt5OSXFrjAV&X-Amz-Signature=ef61452fb1f2aaf63c7d34e261864c2e2c0e79b00e54b353d977ec2dbbf6e08d&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WTBP4KPF%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T102256Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEC4aCXVzLXdlc3QtMiJHMEUCIQC5TFKqxhLdre4FH5yFSNPMXUmlDa%2BT6tCQIF3mfgZMdwIgYA5hLav0TPBc9tTFR6yArhsoqOoT0I0MJrapoaE3QDgq%2FwMIVxAAGgw2Mzc0MjMxODM4MDUiDGaBU4DZoP3TT%2B%2BgtSrcAy8w3WzLNG5jsWKSN4QjIqhyWDtFQpjKDtSjHtXp%2FjZnUv1baok%2BL7p8t1PHckrg3JOkim6y0S2rpxnDUvCK9BrXah4WbpMr7KEc4U8Z8YEfR9Bymt%2B1ZfZK5v0HeW0NELqfLu6NVaRdN%2Fp1UBQTBDnkIU4t1SaG0v%2Bfgzoml5LqdCpU5sb6nso44iaAWEMQZz7RPabUXIaasuOpg5znpnYS8mi05nzOfGBG%2FEiWdK65KaLNW1hkAiRxZGR0OKNKUboYPX3HaIaZhUAYpA1PxGXXReP8qGIZeIoamyYpIolWV1J3rIRiNq25cau1I7OJM6x61jTcWiSvySBFWe%2B5H8JtMmlaNLeYyk%2FlPOT0sewFeEYV4ACugAv1tcplLdywzAW3MTjznQ0Xo4Cdki96IawFFR31SMI6ETinFeLQiuSoI%2BmHwed6DcoV2Th5x4jpYJWCw6vGJRU6PDc78QO9SR50noasDilhxJZF87xPaaZIo2dHnTo5gGKVudosrvVAMIuh12MMyKSOJt6JR8c8eB2JUj4LfZpJIHVUPkQijthvnMK4s6zx6yYAaVYS9r3byso5LpL3iktUnPk1AEMK045Hp%2FugFWjvlzAOkJsYoc9V6iNYXa3%2FcywD5WmZMPP9xb0GOqUBS1plUNNdImSRK4EweL3e0WSOgA4ZrjAtOZw%2Fbj7o%2F7QbSSwvUWAJRFRYdduw%2BdHwsMpDQeC%2FSFnLoD4X0jlAQZ4N5p0RGzxw4aBzLg%2Bt3jFnt%2BvpJVnFgTuH%2FMP4W2hUzCDy2SryWG1xr1IeR3BtKhjgZbvWguTruaMTDBv2%2B2aS21M7M18F62Q1ZxtH9Zz29M7pvLEydWhVoKQCJMrSrhQhqKwU&X-Amz-Signature=6d251a8af0d78253df8e344074a41f95bcc1e283bcf2f40182197770efbf853e&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666D7H6QRW%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T102256Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEC4aCXVzLXdlc3QtMiJIMEYCIQDo9QQKiDtutGGTfPHU%2BjcNiujOezveePooHjkTNJZwpgIhAMjUDbPCdCj3sotfoqfWPNM9lcBLIKfjc85a%2BXwCOx7RKv8DCFcQABoMNjM3NDIzMTgzODA1IgwzOTHUF4Jq403PCGgq3APppaBiL3ZTKxtyDrzDDkiJSg%2F%2BbgvD%2FpOkklv5GNTzZT6r96B%2BZqtKsLlUwF2SUodfsWORumpLZyNWKd%2FoAeQjyUF43jwaz%2B1VwxhR1TXcm%2Bj%2BK9Z9IoQeN553RVOM%2B52lo2%2BWvqRsy8zOkPT5e8LFmx%2BFAIjCBm7xj4bIVlG3rDWk3ErATJg3SlUGdbLLRwlzpp0eKCRY7rCLgnj1eEU5CWq94aenfkwsrULRaCH5DgSxbDIQTQU%2FchtnSpsFnRzu%2BIc96WXKtK311EU6tO1TZ7UHpb2EePc0m6EhlYmphWbcQRrRiOuvmPaHEfpMu1RVkm1BIY36wmGtxZuQuzMJ3YgIgd1pqu6RQd0xhJ83nrFrYkbsouNG1SHzt1Gj62uwbq0osOeyll1OubIcq0R2jFvuTeVqqxB6YfI9T%2FEB7kiXA1PBDc6mgzQbhOxGVBzl93Syj5sDiVN1%2BmWsYnnrKOuuO0NdPo%2FyGdUkcRpfGYsAyI9NjZ7IZdHewYYtnQeqjSHgK1sORIdxVw74AT6SkJMbgPwNWyngeKgWW4FaSSGzmnBIQQVH2%2BjbOgulNjZmvdpzslRhiAc5leWUf%2FWHUgJPIShmBPAwJ5LyRHetYh7JkhTZJiKBkXSiEDDB%2FcW9BjqkAVULcPDEO1xl%2FWuyezyY%2BBXiMT0uD52Ws6k%2FNBoYkYarpZ7%2BGePvFB5WFfyZnpEvIz5g0KVea7IpIFz1wmjNj%2B9Evd3ebLyArIcz8iTtrLO%2B%2BUoQ3R2d5Oe3C37iRTxx67KjG3%2BW44W%2BP6aH47pP%2FRmh6Rj26cFoPG8j%2F6dXMdHTFKESGRDyByfTIzTv7tMQ85OHmCQW14bjOV7MDu5rhFB90H9Z&X-Amz-Signature=9e1ae47ec6d3ccf9fb4bc3180185f523e8a3a664abed0e34584faf8c92cf9d48&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666IYIAVQT%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T102256Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEC4aCXVzLXdlc3QtMiJHMEUCIQC46iADESObEWdId7p3onQoZQACfQJSqrk4qk2Ln7I3QgIgc2btMPe0LOyvH%2FUXQ%2Fad6FOfPgYUOoh6jUmXzxVv8zoq%2FwMIVxAAGgw2Mzc0MjMxODM4MDUiDH%2BvFHCVzuwrcixiFyrcA5d3QZ8e66XKD%2BdOM1bvzKa5Yh9OXXWG64fQ6P%2FPDU%2Bfrrgss5zG4rwWlxfgpXNi4NWLDNyA4snOnlWgc1nteDghprJUVCQt%2B7sit0%2FWFhp0%2B9IpimANG57met8TKzOEvyKldTgY5%2F88OI%2Ff0%2BmtNRDl9F75a%2Bh3iFGKXNiqhyvDATFvBDdfvAds8MJS2AjHFCEctyE4h6dp7nnXtVmvU7M1HrQ1MkjKe5jw1yOddEGhqRrJhvjVR9wkoEX%2FwpKEGMZ0gj1TNC44%2F1YOsLeI7wquLhYN%2Bivksy4xmckrDQ7uT%2BUMnkCEm%2FnUSneFBFJ2V0bULv22czd1urv%2BrgvgrqAzNrrae0VyoZ4wYyVEhV9GJYLN%2FVwoaxfUuoqzp11KGPr7e55L0fRMTQeTpCx5AcF0dhobuRq6DtGYr46AOL8tBfwnjtbqT5DmevDLnYb0eIWb5xS%2BhOx72GzdWZiFoWC8VcvUX5c3wR0puu%2BOqP9x9xgCwGnCuQw1rvgdyuKbRP%2B73mLaqFyvPNZw97ZOQ2A737g2RxX2xkG%2BQ6idU8jrTiu3nlnmlayshy3jvvJOwhAoo81Iu4rSvJ4ZzPntl0ziGthPHWkUPbqS3ZInzXUr2fVU%2F3mtqVDtfpNyMMH9xb0GOqUBCZXL9CvH3AI42baJ%2FHyYY6IEMlrhRPnaEdhsHsgdj0k59sl2AOfk7hCC3bHnHPKFjTCviwNN9SCsFrd0VH20eqbv1EBUPy9fCP61wdJrV61hYWY8UPqURzjqne5BsHjY3jlSwzjPLWJ0YtbIKBA0jOCR%2B0G99vwSi7YiogUJ18gaE9gCDUIoECSYuHn7xmTquEYxUOhptowEGJcMbEt5OSXFrjAV&X-Amz-Signature=0a2e03493f339433c49b2dbbd95a2db9244c470723dfe66acd83809657c5814c&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666IYIAVQT%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T102256Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEC4aCXVzLXdlc3QtMiJHMEUCIQC46iADESObEWdId7p3onQoZQACfQJSqrk4qk2Ln7I3QgIgc2btMPe0LOyvH%2FUXQ%2Fad6FOfPgYUOoh6jUmXzxVv8zoq%2FwMIVxAAGgw2Mzc0MjMxODM4MDUiDH%2BvFHCVzuwrcixiFyrcA5d3QZ8e66XKD%2BdOM1bvzKa5Yh9OXXWG64fQ6P%2FPDU%2Bfrrgss5zG4rwWlxfgpXNi4NWLDNyA4snOnlWgc1nteDghprJUVCQt%2B7sit0%2FWFhp0%2B9IpimANG57met8TKzOEvyKldTgY5%2F88OI%2Ff0%2BmtNRDl9F75a%2Bh3iFGKXNiqhyvDATFvBDdfvAds8MJS2AjHFCEctyE4h6dp7nnXtVmvU7M1HrQ1MkjKe5jw1yOddEGhqRrJhvjVR9wkoEX%2FwpKEGMZ0gj1TNC44%2F1YOsLeI7wquLhYN%2Bivksy4xmckrDQ7uT%2BUMnkCEm%2FnUSneFBFJ2V0bULv22czd1urv%2BrgvgrqAzNrrae0VyoZ4wYyVEhV9GJYLN%2FVwoaxfUuoqzp11KGPr7e55L0fRMTQeTpCx5AcF0dhobuRq6DtGYr46AOL8tBfwnjtbqT5DmevDLnYb0eIWb5xS%2BhOx72GzdWZiFoWC8VcvUX5c3wR0puu%2BOqP9x9xgCwGnCuQw1rvgdyuKbRP%2B73mLaqFyvPNZw97ZOQ2A737g2RxX2xkG%2BQ6idU8jrTiu3nlnmlayshy3jvvJOwhAoo81Iu4rSvJ4ZzPntl0ziGthPHWkUPbqS3ZInzXUr2fVU%2F3mtqVDtfpNyMMH9xb0GOqUBCZXL9CvH3AI42baJ%2FHyYY6IEMlrhRPnaEdhsHsgdj0k59sl2AOfk7hCC3bHnHPKFjTCviwNN9SCsFrd0VH20eqbv1EBUPy9fCP61wdJrV61hYWY8UPqURzjqne5BsHjY3jlSwzjPLWJ0YtbIKBA0jOCR%2B0G99vwSi7YiogUJ18gaE9gCDUIoECSYuHn7xmTquEYxUOhptowEGJcMbEt5OSXFrjAV&X-Amz-Signature=75cc5c7be8282beeab67f215b1d9b3c7fc40bb17768a473ba61782da21b0df92&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666IYIAVQT%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T102256Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEC4aCXVzLXdlc3QtMiJHMEUCIQC46iADESObEWdId7p3onQoZQACfQJSqrk4qk2Ln7I3QgIgc2btMPe0LOyvH%2FUXQ%2Fad6FOfPgYUOoh6jUmXzxVv8zoq%2FwMIVxAAGgw2Mzc0MjMxODM4MDUiDH%2BvFHCVzuwrcixiFyrcA5d3QZ8e66XKD%2BdOM1bvzKa5Yh9OXXWG64fQ6P%2FPDU%2Bfrrgss5zG4rwWlxfgpXNi4NWLDNyA4snOnlWgc1nteDghprJUVCQt%2B7sit0%2FWFhp0%2B9IpimANG57met8TKzOEvyKldTgY5%2F88OI%2Ff0%2BmtNRDl9F75a%2Bh3iFGKXNiqhyvDATFvBDdfvAds8MJS2AjHFCEctyE4h6dp7nnXtVmvU7M1HrQ1MkjKe5jw1yOddEGhqRrJhvjVR9wkoEX%2FwpKEGMZ0gj1TNC44%2F1YOsLeI7wquLhYN%2Bivksy4xmckrDQ7uT%2BUMnkCEm%2FnUSneFBFJ2V0bULv22czd1urv%2BrgvgrqAzNrrae0VyoZ4wYyVEhV9GJYLN%2FVwoaxfUuoqzp11KGPr7e55L0fRMTQeTpCx5AcF0dhobuRq6DtGYr46AOL8tBfwnjtbqT5DmevDLnYb0eIWb5xS%2BhOx72GzdWZiFoWC8VcvUX5c3wR0puu%2BOqP9x9xgCwGnCuQw1rvgdyuKbRP%2B73mLaqFyvPNZw97ZOQ2A737g2RxX2xkG%2BQ6idU8jrTiu3nlnmlayshy3jvvJOwhAoo81Iu4rSvJ4ZzPntl0ziGthPHWkUPbqS3ZInzXUr2fVU%2F3mtqVDtfpNyMMH9xb0GOqUBCZXL9CvH3AI42baJ%2FHyYY6IEMlrhRPnaEdhsHsgdj0k59sl2AOfk7hCC3bHnHPKFjTCviwNN9SCsFrd0VH20eqbv1EBUPy9fCP61wdJrV61hYWY8UPqURzjqne5BsHjY3jlSwzjPLWJ0YtbIKBA0jOCR%2B0G99vwSi7YiogUJ18gaE9gCDUIoECSYuHn7xmTquEYxUOhptowEGJcMbEt5OSXFrjAV&X-Amz-Signature=49530b5056c88ae7353226359923ee6eee4b40e4f0c86795a06adf26fd727048&X-Amz-SignedHeaders=host&x-id=GetObject)


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

