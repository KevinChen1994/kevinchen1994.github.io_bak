---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466XYU3DKHF%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250211T222221Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEMT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCf3LX71gkDmdJF7xN\
  6rVjc2T8qlFlokipfBCk15nPJewIgWn3owgfqLxUjQFX0gu1zOv4XwDPg9iG%2BxD9%2FE7frbfAq\
  iAQI3f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHwjOKnK0YF1qmI4J\
  ircAwi5lqAJoaoen4Lz%2BvOM2MX3DZJ7Ir3XUehLgZg3O7sP2Z%2Fy6tz2G%2BZ9wK6d%2FdJ7zO\
  xvSN4FYJb1uWgxa4JDTnqFH5vBlSF8x6unboaOp86RHPiSwrAe4Vn8c2F9oZrrsRbF97XuQvziCS2\
  7DwYjvDCOHkn8H0JO69GIvujrVcgTXIkF5NXUVmtQ1Wr%2BHtF%2BC%2FQBEU2X5iKVfelOM9JcA6\
  I7v4S1Kdt41Ls0%2B4TWlvz9f3zpBlaGaaSLDfJQc79s4vF0mdKogJzIKb0HqlMtiOVlO57F4HUCx\
  n1ow2XZJqK1hA9%2Bc4iEm5WjbweUzCBDqYBn3rO1rghROBmMze34fW3qsKB4gmouPQHB2xejciW8\
  JE3dgfPBteHyuzCPvF7CCGwc4vMj%2FIWtKmulim2oeYz%2BtjNnK9ISowtn%2BviqTaKXL5eJ5Go\
  lGccWKC0zXwlMUejA8mI0K3s5zgoK7HSd4nd0YL%2FCXcAztk9IXR0BWSTpmkC6RckOk9hnquOQd1\
  IgmHJ8wbPL5Pdjw4WJTOSvJGmlxZKWkyIe5FEw4twyPCIxBOJJlMP0LDP5S3bW80HKkYM7gnDGxsA\
  DVDK%2BVuKnZ1j0nXA1DI%2FUG8UT%2F5TlsYVMx9PvY1ffNKdSrdWAMODIrr0GOqUBWgIuBaIAuc\
  YBoBrDG6dJLfwGdAwUbhOMrvc3MIG6zHON2Fc8ok9BanM4OVdUK1IfmdhVT7IzhBM7L84N3sdgVlO\
  tKRE2fQz69AvcHY60FbNuIYCAQZm7rIu2VIC5oQrI9nbZE8c%2FP25NLXtQFQeT5hBL1Zj%2Br4CD\
  8%2BrlCOsfBX506YK134tloN%2BbyySTYx9UKpkqsKMZRPpeLuZ5ZQ34k%2FfkZmeM&X-Amz-Sign\
  ature=956b6948d97e6ee479b7fe5d0efbf97d50bca656aca51aff160e6edab0419fbf&X-Amz-\
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
        redential=ASIAZI2LB466USFTHBOK%2F20250211%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250211T222110Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEMT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIE%2BHpXAjUjMl0lt%2BuwCIR%2B0Jrn7yVxtyQDU%2FA4%2B%2FcXz1AiEAmb2GcR6KFA\
        RRaH4wLov0hDFAb7KczUoKYP616tEc36UqiAQI3P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FA\
        RAAGgw2Mzc0MjMxODM4MDUiDO0qipLHW%2FmCO%2FC9syrcA7OjSeln5uPb%2F60GH37BSS\
        F%2BOYsr2r7UX%2FqzFZQ%2FaeXFO84DlMa59j5npD7G72JCpZQUCEjcRaHtuQuHPgE5PCO\
        ycRyoGCJVtvjcYnEH%2Bddx29cE8ZbeFl2HgXQjybVjUMDWVIxjs%2FWEszEK7W7cRb0OkX\
        9X930kZl2LZuFy9YwEbGhZdypb3r9ziopIwA5CVOhkvmMc3W7YTi8etMePMBYm5Zu7yV5oO\
        13T4GMyseWq47F2inH%2BNFn%2Fl%2BbI%2FURBbyOUUp45GoqaTnSDBMP%2F%2FjwoZUZP\
        J8SVdQHjbH97xi6Yy2IXeqf8MltoCWdONrs4mDRrrb%2BqbbkWqwnvUUzaB0JFW1nB0P0VI\
        6Mhbcvd6%2FmJkp8wqV%2BmnJVmVFuKT%2FgXpOFk885%2BKbb35WxAVLeua1WxwaoxvGvA\
        wRkNweMv208bbV2BCiSOZ9W%2Fdx75yThBYYK6lTSxeKkrUI3d0DIpdyNVTwv98q0ZCm9Rb\
        EmhedLQrTcEW2cz0WLYrrerbDOmWSyPSTd3fvPcn4N%2Bm2nvl1kB5ylv%2BrMh8NXILm%2\
        B%2Fxw4aG8DeGQa0G770%2B3UADhwIZvLrl20%2BfxCIa%2FTtCbRrcQiYJLI%2BcibkoVA\
        1HlFRMvJwktuE3N9%2FAWHMu4uXMIjJrr0GOqUBEv0eVubPEJtiPYE5MSJzRjacblchBAgl\
        dloP4Dv5rufCuTyIBW8ogFGRcNi0a4QilJ96aTKQ0mtkv%2Bgy2mC20Ped90PSylLzz8Vny\
        pp%2FXMTLakmDVXMEGcNkpKV6RoCdGVRRy0wnhnOlLMXQ1UFG5Q2VmNOTulAWMK1UQK4Ize\
        xFLMkIl2Xk8YroREc6D%2BYu1t5%2BqBYAF5wp0gPsWUPrhTQyHZDA&X-Amz-Signature=\
        aa4741cc3f895f5d62466c6373069443d4b0d0cf9727d9e2e605622cc98143b9&X-Amz-\
        SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-11T23:21:10.421Z"
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
UPDATE_TIME: "2025-02-11T22:22:25.797Z"
EXPIRY_TIME: "2025-02-11T23:22:19.519Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VSGCYXOJ%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T222219Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDPfOLWRTf%2FREXMZq1URofBlYAnypnIKp8pSwxzpZJKvQIgPjNr%2Fu3zAHzjBy7DMnwh8R6azTq54p1UejdaOPYvOLoqiAQI3f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPBMq7Pp7l0U0HNj0SrcAxmBB%2BhbVLs5M%2FZkAC%2Fcl%2FiS2%2FOo3pooCS7zv4H4dGJVA4TZS7hbOQb5UWajrANi9zi6U2xWWOwyyPlo4fiBzb1yczkbndzJKqnL8SeKulQlzwGn0BogcjWftEthBay8HLnUEvXHsPBf7AEQn2E3A%2BBl3%2B9QfoFA5JLxWU5gcMZM8OWknfXqXlhRPPf549FcxkyyewTCe%2FYSn4eVGaGgMw6cqC0WfPwMgwpQgwZSWulEphBBHpnmoVdQBDgEDNy04YRCpl8P2g5Q0tj79gyTqe5OqXoeXL77PrPIG%2Fg8FJ%2Flh5kckzBv6PuTJRCyR71k6IXT0sTHQsh1m8l8Js6405vNyfUoRnQmn40TSfZwep%2BYzLYyPs98n6RnpEW0x2nHQ8QGv8NTcNVLjR4vhA2ccyi8DKv8FC246TcE8dGps2ub7Iiz5ts7TQK7B3L%2Fus2mtXKs0iPLUbsE0KqRABBn%2F%2BzZZiPjwSotDRXExLyRXdHWg2s%2FY8QKvdNvazcNabJWvjv1mLk3C9L62UA52xcGQ0JaXTcZqNUbt9n5%2F5vg3KR4PFp4pjygcXTfudmqYgRSFLB4QsM83%2BoegTkqWYqxFw3MX%2Fn3QMVd%2F2chgsgpt3w4eUq1szELLv51LtxXMInJrr0GOqUBOUlER0C8t4tio4%2Fdjk2VklnyTVwHgxhSSrzycwLy1pTLnL3UNY8ti4TcUI8xWUU17Sop3oIv9PzbUQyVa9niel8%2FvjRIrCk8sY44Kf30mqF5k0UnweoXVTDOHBRUg9BQZdBwCkgI5E7ZcWgJxytOe%2BDBKMW%2FUbnIsxLL60DFLGjwE%2B8n%2Bi5Ifr4kDmNQxCtB6BGg2iGW8L9OXJ%2FgQjnZwM9ROy73&X-Amz-Signature=7bfd028bf16ad3b9921cc895422e4e256fe6781afd77b1bde340fac4a3ec28a0&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VSGCYXOJ%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T222219Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDPfOLWRTf%2FREXMZq1URofBlYAnypnIKp8pSwxzpZJKvQIgPjNr%2Fu3zAHzjBy7DMnwh8R6azTq54p1UejdaOPYvOLoqiAQI3f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPBMq7Pp7l0U0HNj0SrcAxmBB%2BhbVLs5M%2FZkAC%2Fcl%2FiS2%2FOo3pooCS7zv4H4dGJVA4TZS7hbOQb5UWajrANi9zi6U2xWWOwyyPlo4fiBzb1yczkbndzJKqnL8SeKulQlzwGn0BogcjWftEthBay8HLnUEvXHsPBf7AEQn2E3A%2BBl3%2B9QfoFA5JLxWU5gcMZM8OWknfXqXlhRPPf549FcxkyyewTCe%2FYSn4eVGaGgMw6cqC0WfPwMgwpQgwZSWulEphBBHpnmoVdQBDgEDNy04YRCpl8P2g5Q0tj79gyTqe5OqXoeXL77PrPIG%2Fg8FJ%2Flh5kckzBv6PuTJRCyR71k6IXT0sTHQsh1m8l8Js6405vNyfUoRnQmn40TSfZwep%2BYzLYyPs98n6RnpEW0x2nHQ8QGv8NTcNVLjR4vhA2ccyi8DKv8FC246TcE8dGps2ub7Iiz5ts7TQK7B3L%2Fus2mtXKs0iPLUbsE0KqRABBn%2F%2BzZZiPjwSotDRXExLyRXdHWg2s%2FY8QKvdNvazcNabJWvjv1mLk3C9L62UA52xcGQ0JaXTcZqNUbt9n5%2F5vg3KR4PFp4pjygcXTfudmqYgRSFLB4QsM83%2BoegTkqWYqxFw3MX%2Fn3QMVd%2F2chgsgpt3w4eUq1szELLv51LtxXMInJrr0GOqUBOUlER0C8t4tio4%2Fdjk2VklnyTVwHgxhSSrzycwLy1pTLnL3UNY8ti4TcUI8xWUU17Sop3oIv9PzbUQyVa9niel8%2FvjRIrCk8sY44Kf30mqF5k0UnweoXVTDOHBRUg9BQZdBwCkgI5E7ZcWgJxytOe%2BDBKMW%2FUbnIsxLL60DFLGjwE%2B8n%2Bi5Ifr4kDmNQxCtB6BGg2iGW8L9OXJ%2FgQjnZwM9ROy73&X-Amz-Signature=00373e0e2542f14975230218abf8da790f6ddcc2c4da55d8488f2e89abe863df&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VSGCYXOJ%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T222219Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDPfOLWRTf%2FREXMZq1URofBlYAnypnIKp8pSwxzpZJKvQIgPjNr%2Fu3zAHzjBy7DMnwh8R6azTq54p1UejdaOPYvOLoqiAQI3f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPBMq7Pp7l0U0HNj0SrcAxmBB%2BhbVLs5M%2FZkAC%2Fcl%2FiS2%2FOo3pooCS7zv4H4dGJVA4TZS7hbOQb5UWajrANi9zi6U2xWWOwyyPlo4fiBzb1yczkbndzJKqnL8SeKulQlzwGn0BogcjWftEthBay8HLnUEvXHsPBf7AEQn2E3A%2BBl3%2B9QfoFA5JLxWU5gcMZM8OWknfXqXlhRPPf549FcxkyyewTCe%2FYSn4eVGaGgMw6cqC0WfPwMgwpQgwZSWulEphBBHpnmoVdQBDgEDNy04YRCpl8P2g5Q0tj79gyTqe5OqXoeXL77PrPIG%2Fg8FJ%2Flh5kckzBv6PuTJRCyR71k6IXT0sTHQsh1m8l8Js6405vNyfUoRnQmn40TSfZwep%2BYzLYyPs98n6RnpEW0x2nHQ8QGv8NTcNVLjR4vhA2ccyi8DKv8FC246TcE8dGps2ub7Iiz5ts7TQK7B3L%2Fus2mtXKs0iPLUbsE0KqRABBn%2F%2BzZZiPjwSotDRXExLyRXdHWg2s%2FY8QKvdNvazcNabJWvjv1mLk3C9L62UA52xcGQ0JaXTcZqNUbt9n5%2F5vg3KR4PFp4pjygcXTfudmqYgRSFLB4QsM83%2BoegTkqWYqxFw3MX%2Fn3QMVd%2F2chgsgpt3w4eUq1szELLv51LtxXMInJrr0GOqUBOUlER0C8t4tio4%2Fdjk2VklnyTVwHgxhSSrzycwLy1pTLnL3UNY8ti4TcUI8xWUU17Sop3oIv9PzbUQyVa9niel8%2FvjRIrCk8sY44Kf30mqF5k0UnweoXVTDOHBRUg9BQZdBwCkgI5E7ZcWgJxytOe%2BDBKMW%2FUbnIsxLL60DFLGjwE%2B8n%2Bi5Ifr4kDmNQxCtB6BGg2iGW8L9OXJ%2FgQjnZwM9ROy73&X-Amz-Signature=7eb96f14b5a4095c0a0753b3392d36c4dbbeb238814e752883d3a2a45d7c50fc&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VSGCYXOJ%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T222219Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDPfOLWRTf%2FREXMZq1URofBlYAnypnIKp8pSwxzpZJKvQIgPjNr%2Fu3zAHzjBy7DMnwh8R6azTq54p1UejdaOPYvOLoqiAQI3f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPBMq7Pp7l0U0HNj0SrcAxmBB%2BhbVLs5M%2FZkAC%2Fcl%2FiS2%2FOo3pooCS7zv4H4dGJVA4TZS7hbOQb5UWajrANi9zi6U2xWWOwyyPlo4fiBzb1yczkbndzJKqnL8SeKulQlzwGn0BogcjWftEthBay8HLnUEvXHsPBf7AEQn2E3A%2BBl3%2B9QfoFA5JLxWU5gcMZM8OWknfXqXlhRPPf549FcxkyyewTCe%2FYSn4eVGaGgMw6cqC0WfPwMgwpQgwZSWulEphBBHpnmoVdQBDgEDNy04YRCpl8P2g5Q0tj79gyTqe5OqXoeXL77PrPIG%2Fg8FJ%2Flh5kckzBv6PuTJRCyR71k6IXT0sTHQsh1m8l8Js6405vNyfUoRnQmn40TSfZwep%2BYzLYyPs98n6RnpEW0x2nHQ8QGv8NTcNVLjR4vhA2ccyi8DKv8FC246TcE8dGps2ub7Iiz5ts7TQK7B3L%2Fus2mtXKs0iPLUbsE0KqRABBn%2F%2BzZZiPjwSotDRXExLyRXdHWg2s%2FY8QKvdNvazcNabJWvjv1mLk3C9L62UA52xcGQ0JaXTcZqNUbt9n5%2F5vg3KR4PFp4pjygcXTfudmqYgRSFLB4QsM83%2BoegTkqWYqxFw3MX%2Fn3QMVd%2F2chgsgpt3w4eUq1szELLv51LtxXMInJrr0GOqUBOUlER0C8t4tio4%2Fdjk2VklnyTVwHgxhSSrzycwLy1pTLnL3UNY8ti4TcUI8xWUU17Sop3oIv9PzbUQyVa9niel8%2FvjRIrCk8sY44Kf30mqF5k0UnweoXVTDOHBRUg9BQZdBwCkgI5E7ZcWgJxytOe%2BDBKMW%2FUbnIsxLL60DFLGjwE%2B8n%2Bi5Ifr4kDmNQxCtB6BGg2iGW8L9OXJ%2FgQjnZwM9ROy73&X-Amz-Signature=4a29c9d04e0564da3c3c93cd433bc6b50388878b4156957fb3d783a70bfd483f&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VSGCYXOJ%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T222219Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDPfOLWRTf%2FREXMZq1URofBlYAnypnIKp8pSwxzpZJKvQIgPjNr%2Fu3zAHzjBy7DMnwh8R6azTq54p1UejdaOPYvOLoqiAQI3f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPBMq7Pp7l0U0HNj0SrcAxmBB%2BhbVLs5M%2FZkAC%2Fcl%2FiS2%2FOo3pooCS7zv4H4dGJVA4TZS7hbOQb5UWajrANi9zi6U2xWWOwyyPlo4fiBzb1yczkbndzJKqnL8SeKulQlzwGn0BogcjWftEthBay8HLnUEvXHsPBf7AEQn2E3A%2BBl3%2B9QfoFA5JLxWU5gcMZM8OWknfXqXlhRPPf549FcxkyyewTCe%2FYSn4eVGaGgMw6cqC0WfPwMgwpQgwZSWulEphBBHpnmoVdQBDgEDNy04YRCpl8P2g5Q0tj79gyTqe5OqXoeXL77PrPIG%2Fg8FJ%2Flh5kckzBv6PuTJRCyR71k6IXT0sTHQsh1m8l8Js6405vNyfUoRnQmn40TSfZwep%2BYzLYyPs98n6RnpEW0x2nHQ8QGv8NTcNVLjR4vhA2ccyi8DKv8FC246TcE8dGps2ub7Iiz5ts7TQK7B3L%2Fus2mtXKs0iPLUbsE0KqRABBn%2F%2BzZZiPjwSotDRXExLyRXdHWg2s%2FY8QKvdNvazcNabJWvjv1mLk3C9L62UA52xcGQ0JaXTcZqNUbt9n5%2F5vg3KR4PFp4pjygcXTfudmqYgRSFLB4QsM83%2BoegTkqWYqxFw3MX%2Fn3QMVd%2F2chgsgpt3w4eUq1szELLv51LtxXMInJrr0GOqUBOUlER0C8t4tio4%2Fdjk2VklnyTVwHgxhSSrzycwLy1pTLnL3UNY8ti4TcUI8xWUU17Sop3oIv9PzbUQyVa9niel8%2FvjRIrCk8sY44Kf30mqF5k0UnweoXVTDOHBRUg9BQZdBwCkgI5E7ZcWgJxytOe%2BDBKMW%2FUbnIsxLL60DFLGjwE%2B8n%2Bi5Ifr4kDmNQxCtB6BGg2iGW8L9OXJ%2FgQjnZwM9ROy73&X-Amz-Signature=acc0194272576d0e8808d841f3628017c79efb7250ede0b902e6d17ce686ed27&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662B3M5FQZ%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T222220Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICCOjgAH0Ikeypx4LtGJiE4eEfcu%2FjddtE3oT53dnfGBAiAXVVWieJjas8G1DTJdnI7pUiCkYSQu6w%2BGnP1X1UHlVCqIBAjd%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMnYmixIstXKRtYtg3KtwDYyngKYwW%2Ba4pNt8lteOUctZelLO1udbUdt%2Bc0ldepJ2mQXWyovHbDhePQaQ9NqJtD6tN4p2esYWmUXTGmFfY%2FG1BlcyFW9cbNZnOn5Je85%2BOQ%2FDExVpWOjWSeLAL6kacIxXUwP%2BXUnf8NnNYzV5%2FH%2BrObRt7HJ%2FZ2hCju02inAvPXs9c5wfT28GSb1LhLEmeJOYHnfpb0EcfYljz49IPcTmmPWGcDFfx07G8l0exb3DA3gYDPvwHloJH9hVpvTxyB57B9XSdIVH193gP70vqrHZ9e0U8mM8%2B0imrQg%2BO18vGEMbilBUcvEUbjecBFPs1GZZxPUHWQlsU%2FihIHbrTbZiLw8sh7hXMXC9q%2BbYiAL33Gf82%2BpClq2JD1ULiYAqmnq60FkRN20kDzT4lsQaG23wHx6L%2Fw41QsJipaKKklaofv0pG8%2Bf0WgCUVhw%2BJq5%2B7UFVdL1eSHTGO6DdDKlgBCUv8Y98F4TtiQBfZWw1UU7rucws0T0u8m1MiKB%2FXi3GMWoz%2B%2FZAyHOE81QlB50agjb6r4vH2M0Yt97J%2FHWf%2BI1MR5Sg4iahjNSGXf0DxJOVm6EIgaxY9K4bYcarOKRri2tslm%2F5NM9QTs%2B5y4a5TEA4B6M4ym0Dx7vjJgUwwcmuvQY6pgH1z11aSAAIMV%2FhOISFh7dY1ls6ubYSwtlJsL1R8PhX532f7Ja9Fav9QSGIsRR6Hggt8SmTZ8FTB2fG2kqJw2JdX8YTm48V87k5WtkFRd3wuIjYcVexvZtcPgyqW1CousVn%2F3qj0ZK8LPNbI8mjMkqmRcPiqb0eimBXqEB3HVUzXSuYwqu3qav8hEkigmj1Kcbq6cXxarqpjcd6fNslVxOvH9w%2FKJu1&X-Amz-Signature=76add578cfa8e2fc4cd5141293152ec1df87d956fbbbbf91c26e0bc4033950eb&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667ANVN7WC%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T222221Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDvsLdFZ5JXncvxChqBuqgb5yELr1Gcw2iNzoyXXiCe%2FgIhAMD4UEx6gtPAmOgIZ%2FkjDoW5GKfJttaReSa8Q5dJS2FRKogECNz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igyi84cDZvTfpdoVxgUq3AMqjOIascHxOEf2v6zIhajU9NTN66SwKzKGmc7pTwkTprH6YMTnBRybadiWBdq%2FBREGbA8D3ShCgLvSvvRnu6jWnWd%2BIy7QSeNAaoka8y96Z6n9FnEHQSzs%2F9K6cUmIfIBBGX9LOn45BB5MpUXJ3%2F6h%2F73iZGVekI%2BqzxDGVtnyrBY3D%2BQogubRPcAKjJNBvYVHoE3HuYv1PsfttTM2iyCFw8G6Np29xRXskszj33hUAcplLEzLo0Ddt3QnsGxkfEKT4TYXwg1H3nTtB9xB3f8dfeb2nzEfHlfw3YNsJ0Ntazxprx1YvxUUBhF6Xi1z%2B3IYSc%2FlIGInrSGfHclfCcMxS8DeS380RJCeh3dc5haSOAKjAFp4v7lcXZzzFqh9XCg24iBxkBqcKw95%2FB0C8DPt4buaEX0908569x%2BFF3MmMymJ3Kl3W1GvDFTbOz8yEb9RbTdVN5GAC9BtpU4MlfFrY0jEp343y3hAK6Mzn522C9T%2FmK6eIaKfGJgufhPedHUHhwZjoAtLcA10QoiMcmbEqvkrOpjeyUuzvEXVm8elsGAiKidn9w9QrJE1ctQqqG%2FdzlzYvZ3DZ3vAIiFOVc8LB35AmI7KYKE6YoLxZARObTl%2BNT%2Bn2%2Fys5%2FHTIzDnyK69BjqkAfcp6uWl3ixzkH55MWT9Nfg23zNhUJpJORyheNneNeIOAm%2F0mNTtXJs8e4U%2Bc%2Fm%2FOZZrXpdWLLEhwQ3bc11c0hbBBCo%2FZNYaOCEfig%2FYaY2T6BNrHwlywano6cVTqyrf8BG7CJQUY6mq5aGX4T%2BvXTk508itJLY318Ut2xm25UMESpVy%2BzwQq2MLh6%2ByVYSLRoQCq5UMs%2FrLyELHPnes8BGIRWt3&X-Amz-Signature=66e8adf9b6002a1fd36088d87d0fc87ccc6d8f57d4a384f6ea6c71996867e0a3&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VSGCYXOJ%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T222219Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDPfOLWRTf%2FREXMZq1URofBlYAnypnIKp8pSwxzpZJKvQIgPjNr%2Fu3zAHzjBy7DMnwh8R6azTq54p1UejdaOPYvOLoqiAQI3f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPBMq7Pp7l0U0HNj0SrcAxmBB%2BhbVLs5M%2FZkAC%2Fcl%2FiS2%2FOo3pooCS7zv4H4dGJVA4TZS7hbOQb5UWajrANi9zi6U2xWWOwyyPlo4fiBzb1yczkbndzJKqnL8SeKulQlzwGn0BogcjWftEthBay8HLnUEvXHsPBf7AEQn2E3A%2BBl3%2B9QfoFA5JLxWU5gcMZM8OWknfXqXlhRPPf549FcxkyyewTCe%2FYSn4eVGaGgMw6cqC0WfPwMgwpQgwZSWulEphBBHpnmoVdQBDgEDNy04YRCpl8P2g5Q0tj79gyTqe5OqXoeXL77PrPIG%2Fg8FJ%2Flh5kckzBv6PuTJRCyR71k6IXT0sTHQsh1m8l8Js6405vNyfUoRnQmn40TSfZwep%2BYzLYyPs98n6RnpEW0x2nHQ8QGv8NTcNVLjR4vhA2ccyi8DKv8FC246TcE8dGps2ub7Iiz5ts7TQK7B3L%2Fus2mtXKs0iPLUbsE0KqRABBn%2F%2BzZZiPjwSotDRXExLyRXdHWg2s%2FY8QKvdNvazcNabJWvjv1mLk3C9L62UA52xcGQ0JaXTcZqNUbt9n5%2F5vg3KR4PFp4pjygcXTfudmqYgRSFLB4QsM83%2BoegTkqWYqxFw3MX%2Fn3QMVd%2F2chgsgpt3w4eUq1szELLv51LtxXMInJrr0GOqUBOUlER0C8t4tio4%2Fdjk2VklnyTVwHgxhSSrzycwLy1pTLnL3UNY8ti4TcUI8xWUU17Sop3oIv9PzbUQyVa9niel8%2FvjRIrCk8sY44Kf30mqF5k0UnweoXVTDOHBRUg9BQZdBwCkgI5E7ZcWgJxytOe%2BDBKMW%2FUbnIsxLL60DFLGjwE%2B8n%2Bi5Ifr4kDmNQxCtB6BGg2iGW8L9OXJ%2FgQjnZwM9ROy73&X-Amz-Signature=bfa3b805c785c06a2f9101f6a89c1f3ffd6676519c14051ba7ef7ca5cdfe328b&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VSGCYXOJ%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T222219Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDPfOLWRTf%2FREXMZq1URofBlYAnypnIKp8pSwxzpZJKvQIgPjNr%2Fu3zAHzjBy7DMnwh8R6azTq54p1UejdaOPYvOLoqiAQI3f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPBMq7Pp7l0U0HNj0SrcAxmBB%2BhbVLs5M%2FZkAC%2Fcl%2FiS2%2FOo3pooCS7zv4H4dGJVA4TZS7hbOQb5UWajrANi9zi6U2xWWOwyyPlo4fiBzb1yczkbndzJKqnL8SeKulQlzwGn0BogcjWftEthBay8HLnUEvXHsPBf7AEQn2E3A%2BBl3%2B9QfoFA5JLxWU5gcMZM8OWknfXqXlhRPPf549FcxkyyewTCe%2FYSn4eVGaGgMw6cqC0WfPwMgwpQgwZSWulEphBBHpnmoVdQBDgEDNy04YRCpl8P2g5Q0tj79gyTqe5OqXoeXL77PrPIG%2Fg8FJ%2Flh5kckzBv6PuTJRCyR71k6IXT0sTHQsh1m8l8Js6405vNyfUoRnQmn40TSfZwep%2BYzLYyPs98n6RnpEW0x2nHQ8QGv8NTcNVLjR4vhA2ccyi8DKv8FC246TcE8dGps2ub7Iiz5ts7TQK7B3L%2Fus2mtXKs0iPLUbsE0KqRABBn%2F%2BzZZiPjwSotDRXExLyRXdHWg2s%2FY8QKvdNvazcNabJWvjv1mLk3C9L62UA52xcGQ0JaXTcZqNUbt9n5%2F5vg3KR4PFp4pjygcXTfudmqYgRSFLB4QsM83%2BoegTkqWYqxFw3MX%2Fn3QMVd%2F2chgsgpt3w4eUq1szELLv51LtxXMInJrr0GOqUBOUlER0C8t4tio4%2Fdjk2VklnyTVwHgxhSSrzycwLy1pTLnL3UNY8ti4TcUI8xWUU17Sop3oIv9PzbUQyVa9niel8%2FvjRIrCk8sY44Kf30mqF5k0UnweoXVTDOHBRUg9BQZdBwCkgI5E7ZcWgJxytOe%2BDBKMW%2FUbnIsxLL60DFLGjwE%2B8n%2Bi5Ifr4kDmNQxCtB6BGg2iGW8L9OXJ%2FgQjnZwM9ROy73&X-Amz-Signature=51067e020c0d0fd0ac8509ccc6c0653c7ed947b2597c0e3493562afa3b68e3d2&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VSGCYXOJ%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T222219Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDPfOLWRTf%2FREXMZq1URofBlYAnypnIKp8pSwxzpZJKvQIgPjNr%2Fu3zAHzjBy7DMnwh8R6azTq54p1UejdaOPYvOLoqiAQI3f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPBMq7Pp7l0U0HNj0SrcAxmBB%2BhbVLs5M%2FZkAC%2Fcl%2FiS2%2FOo3pooCS7zv4H4dGJVA4TZS7hbOQb5UWajrANi9zi6U2xWWOwyyPlo4fiBzb1yczkbndzJKqnL8SeKulQlzwGn0BogcjWftEthBay8HLnUEvXHsPBf7AEQn2E3A%2BBl3%2B9QfoFA5JLxWU5gcMZM8OWknfXqXlhRPPf549FcxkyyewTCe%2FYSn4eVGaGgMw6cqC0WfPwMgwpQgwZSWulEphBBHpnmoVdQBDgEDNy04YRCpl8P2g5Q0tj79gyTqe5OqXoeXL77PrPIG%2Fg8FJ%2Flh5kckzBv6PuTJRCyR71k6IXT0sTHQsh1m8l8Js6405vNyfUoRnQmn40TSfZwep%2BYzLYyPs98n6RnpEW0x2nHQ8QGv8NTcNVLjR4vhA2ccyi8DKv8FC246TcE8dGps2ub7Iiz5ts7TQK7B3L%2Fus2mtXKs0iPLUbsE0KqRABBn%2F%2BzZZiPjwSotDRXExLyRXdHWg2s%2FY8QKvdNvazcNabJWvjv1mLk3C9L62UA52xcGQ0JaXTcZqNUbt9n5%2F5vg3KR4PFp4pjygcXTfudmqYgRSFLB4QsM83%2BoegTkqWYqxFw3MX%2Fn3QMVd%2F2chgsgpt3w4eUq1szELLv51LtxXMInJrr0GOqUBOUlER0C8t4tio4%2Fdjk2VklnyTVwHgxhSSrzycwLy1pTLnL3UNY8ti4TcUI8xWUU17Sop3oIv9PzbUQyVa9niel8%2FvjRIrCk8sY44Kf30mqF5k0UnweoXVTDOHBRUg9BQZdBwCkgI5E7ZcWgJxytOe%2BDBKMW%2FUbnIsxLL60DFLGjwE%2B8n%2Bi5Ifr4kDmNQxCtB6BGg2iGW8L9OXJ%2FgQjnZwM9ROy73&X-Amz-Signature=e9a9c3522c940c1b06b543324aa3908fac990384884ab32ca1ae1c6b43eab09e&X-Amz-SignedHeaders=host&x-id=GetObject)


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

