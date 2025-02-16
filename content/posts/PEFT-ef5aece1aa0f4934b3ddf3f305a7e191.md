---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB46626ZWUPWN%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250216T015456Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjECkaCXVzLXdlc3QtMiJHMEUCIQCxBgN3K7X8%2FY9YsUo2WTWkleRrDxTzZ1Fx3nA7todGDwIgc\
  5nhlYQa11W3DZMZr%2BGIRbRYypPxGaKj%2B4KKZLvsQJsq%2FwMIUhAAGgw2Mzc0MjMxODM4MDUi\
  DLYvQGpu%2F9FpApNRsircA0zq4CCXzhrnMXi3JRqGLdfdioCIKj7BzpJT4mzFOa6LOBDZVrXtz24\
  5fOSXU4oIy%2Fg0CLfP%2Bps4LSfoSntJSYISPVJi3PRwrA9mCSAypvLuzH%2FwmSVzmYZ4YVwCo8\
  PhBRrE1WqVKR5M5SmIl21ZpR88PcHI5z7erH1dkPhsJLi6UEStFAOLrFLmLVQMmWUuJCoSX1JoYeg\
  zhsgO32KMHOlp%2F20QF%2B9B3In2DbsTp34ZUL9PqKLYmDua%2BCYQDsOklcyWgnpmBfCWzhVsMF\
  cFksH%2F4pR%2FqBuoEbX7e%2ByYWW1pNHa6UONKyfc%2F%2B%2BZPgr6%2Fv05EZg0ITKTxAS6gf\
  vG8vWxWC%2FiX2jPdyhjmcLxfc9Wr6gVN1ghMiJI%2BbDlU3svJChWbBgnUbcPjBYDl8j6uki4Pqw\
  fd9P%2FlXuWZUhaKF60GmHK1Z7DLMj3ixKTZqEsJx5ZOnfF19pkKfXIgvlNd67ogAXYdUP85FNZdW\
  b23NiZ2KFO3qFev2MS%2FywcCsEWswpXuCcmO7qb5WvXFilz%2FMc3HKP1hrvFhMlCC0GbmzyHWu6\
  4EfZHyOLL1SDXZ4w7I1a0X0mtzdH65KlaldUp5gRcFyGskdLMr1gYxXwqZ5qMP8giw6AB2c950mVJ\
  YMOflxL0GOqUBqNJbI8hM%2BGA6sTLDU03uCEVtLeN5%2BncZJfevbeavSPSRzzSaH6A214QO5EZu\
  W%2Bf3%2FuDa%2BsyQunpMv%2BrmgJNnb9O7c3DEFUnVq2GlH9I2BiO9NJhbiDXb4aU6wpA%2Bcgb\
  iI9qEKIsDQ4zhS9%2BeA8urDOCilHLT9JNmVBO%2FLZz3RjMlBG99UQbYKcVpnPw82%2BJfWAJubJ\
  X72shHfJqyK5YZlDIQkOkv&X-Amz-Signature=5749d5a6edc28118e962dd3dee97bafaca7e36\
  0674343b527405a3f78e8625e2&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466QS66NOMI%2F20250216%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250216T015337Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjECkaCXVzLXdlc3QtMiJHMEUCIQDevcGl1U44he0uKDQ%2FmZHSiaiSP\
        UeaOklYXmbEwp5yzQIgNUivozO8LJGvd4Zj4ChrxMeWRVe5wtyXIyFSbjwR8yEq%2FwMIUh\
        AAGgw2Mzc0MjMxODM4MDUiDCloSJcXUf1FxL74MCrcA1%2Bol4MwZ3LerdtW9ww%2BqPfYZ\
        dYLOZjZzHNk%2ByqdHPM0xrUa4U8O1QHHyayUdpbT6o%2FRdkLhtGPe7oR6NvUnaxIC5x1Y\
        z6hSBBRYlEyanVCpdMMQQYAGw8NvUR7HnDfUyzomRCBdcoWANH4fkMgFo0qh%2BQ2FEpbTV\
        36XdIkEYMzVi6IDb%2F%2FYpaKcxhxnRwxflZefDnYkJsuE%2FBWlduO7UQ11wW0tZKSR7Q\
        dnzLzUNHOh%2BZomw7AXWv6ZDeCvNF%2BZzyM3kZ4rBgh4PjD8BFKNODnG1A9vNVHiTJKPJ\
        bDtFB50q2C6ruJHrIlCgWcFPOazrlA7zuCMIBcsKJgLY1WENPiOJKFhaiVsMcpp1FgvL0hS\
        %2BwpAx5VGlsa4CZ%2B3mb7vZR1Wt7AAZ61SFfY68Plr7L7h81QyJMFCvbUOTlGU5z9b4tK\
        nRWp0v99g1wdaEzYyj%2FBzxxaQs6DmH7IVF41aMe30NeLNFx5ZkaKtRoLzcAKriQvC1M54\
        IUfLfCV5A5UUbJQ%2FYwlz7AU7%2F%2FuOwUTb00OdKgyWbdwLCxRZR8PnkFw1oNTSJjyww\
        8L8T%2BkFzdiny9OlrnEG3h9BXK6mSaPY5AmBgyVjTL8dvQkJdKq5Rgzt5NoH3DWQIWbUTX\
        zBMNXlxL0GOqUBvlHfbBRA9749yvp6FBr0JJ1%2FuNr2wZpG8UDCRIUkBoiHSmyiunlyN27\
        OSho2v%2BxLtriUeyKkod3Asa3Z76dYcF4N0cVj5ym8eIKaRGbk3a765igSKOmVn6pd%2B3\
        sgbTJF%2FsiKs6zSh6R3sisNhX89AE3ig1AmYe28TJtb%2B4%2BL2r4OASrhJnTk0umJ%2F\
        JH7EZXb%2BkuuJwsiksjWaG4qc7kaF3EE4Vpx&X-Amz-Signature=308121fe29abfbd4e\
        fc8ee4b91f91bb3a2ffbdf16761fb999e55c19566e15aba&X-Amz-SignedHeaders=hos\
        t&x-id=GetObject"
      expiry_time: "2025-02-16T02:53:37.822Z"
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
UPDATE_TIME: "2025-02-16T01:55:04.569Z"
EXPIRY_TIME: "2025-02-16T02:54:50.553Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U3HQ2RAD%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T015450Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECkaCXVzLXdlc3QtMiJGMEQCIHl29a%2Bs4bTpgaHlu%2FPYUsG3qrI2Pkr7IJOp2i7zDTOpAiAVbEqADeIp6h%2BZbn0uN2xMKwkiewZauZD1nCxvelVLbir%2FAwhSEAAaDDYzNzQyMzE4MzgwNSIM%2Fgs2l22phpaTKyERKtwDxijR6YCmSb%2BasMjeL4SPsjFvgpXyYFVBm94KDDiZuERrm3MeoILSaBj0aRIGxpkmKIXSReCPTIdfQ1G10Qv5ka%2B1Kdadegb60JJBGdZrCIEtE98nZJgG0S3s6b9MLnaN61CGiEdNNcp9nidkTcm1wn7c5Q5CyE8pI%2FdDydqi3%2FtZYKzu8ILXo34gAiXbdkFJWcffTxOmhvm7Jaqpszcr7abl%2BwXH0fmPKCYy48eyzwHdWUbrlEVP6wPfjVUHCaLi4%2FP3HBtaImcRNup9qX1GDwTPgCTEvpmuy%2FXihM9PVQBJk1YvxFFnadYWNg32BAbugeu%2F%2FF0h253ZTfvRU1DKjnhASSU%2Babp6oWCXKPw4g%2B5yjutyi%2B6yFtVJ9BURXoUcmmuSYTf8HP%2BOu%2BckpHAiJaWLeqtzyatq%2Bu8g3JYHnY6pk6DVcgQv%2FiM14MsaKDafTrYMMIkQ3qNxZYumFMLbwyRqDlU646YuKUbLuZftcG34NBsq37PRSRUV51AatYD9wy%2FQEro5AK%2BcEip3l2%2F%2FKHPM05DTUG%2FtAycgr0Zyzxlygw%2BBc7ag7CwYGdONaUY6a5UO7z4pAJvIHkMkKyC2Sn2iTFlLGWvRssP%2Bf0zS3Gu3WW%2B9nuw%2FNgek%2BPow6ObEvQY6pgFvNsIJ6p7BQvtK4xLsG9d0awwWPG5%2BFmYlDyg1PYUNPST7rf2Oprp8vVcpy6zHlnSp2ptjdMR9H5VeTT54GAVquV6qbNSOcWQH%2B58uzEs5QI8mdaWXejvZ%2Bfn1E4Qv9%2F7QYeQ4%2FIU%2Fwz%2Bow1Ey1HlMpl6FOnvboQPFdVi8Xdk3WcyC0Uv2%2B9QFtMX67C43EnPqRt8merqzALYDiMlAekPT5uBbH3N7&X-Amz-Signature=59ce039ac1cc3b8eb0257fbefa3c5e212fe3237c08d97568dc0e956a0690509c&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U3HQ2RAD%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T015450Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECkaCXVzLXdlc3QtMiJGMEQCIHl29a%2Bs4bTpgaHlu%2FPYUsG3qrI2Pkr7IJOp2i7zDTOpAiAVbEqADeIp6h%2BZbn0uN2xMKwkiewZauZD1nCxvelVLbir%2FAwhSEAAaDDYzNzQyMzE4MzgwNSIM%2Fgs2l22phpaTKyERKtwDxijR6YCmSb%2BasMjeL4SPsjFvgpXyYFVBm94KDDiZuERrm3MeoILSaBj0aRIGxpkmKIXSReCPTIdfQ1G10Qv5ka%2B1Kdadegb60JJBGdZrCIEtE98nZJgG0S3s6b9MLnaN61CGiEdNNcp9nidkTcm1wn7c5Q5CyE8pI%2FdDydqi3%2FtZYKzu8ILXo34gAiXbdkFJWcffTxOmhvm7Jaqpszcr7abl%2BwXH0fmPKCYy48eyzwHdWUbrlEVP6wPfjVUHCaLi4%2FP3HBtaImcRNup9qX1GDwTPgCTEvpmuy%2FXihM9PVQBJk1YvxFFnadYWNg32BAbugeu%2F%2FF0h253ZTfvRU1DKjnhASSU%2Babp6oWCXKPw4g%2B5yjutyi%2B6yFtVJ9BURXoUcmmuSYTf8HP%2BOu%2BckpHAiJaWLeqtzyatq%2Bu8g3JYHnY6pk6DVcgQv%2FiM14MsaKDafTrYMMIkQ3qNxZYumFMLbwyRqDlU646YuKUbLuZftcG34NBsq37PRSRUV51AatYD9wy%2FQEro5AK%2BcEip3l2%2F%2FKHPM05DTUG%2FtAycgr0Zyzxlygw%2BBc7ag7CwYGdONaUY6a5UO7z4pAJvIHkMkKyC2Sn2iTFlLGWvRssP%2Bf0zS3Gu3WW%2B9nuw%2FNgek%2BPow6ObEvQY6pgFvNsIJ6p7BQvtK4xLsG9d0awwWPG5%2BFmYlDyg1PYUNPST7rf2Oprp8vVcpy6zHlnSp2ptjdMR9H5VeTT54GAVquV6qbNSOcWQH%2B58uzEs5QI8mdaWXejvZ%2Bfn1E4Qv9%2F7QYeQ4%2FIU%2Fwz%2Bow1Ey1HlMpl6FOnvboQPFdVi8Xdk3WcyC0Uv2%2B9QFtMX67C43EnPqRt8merqzALYDiMlAekPT5uBbH3N7&X-Amz-Signature=eac68a953912c7e71dac118d1d99037370b2ac7c9c91858eb98fe91845ca8a2b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U3HQ2RAD%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T015450Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECkaCXVzLXdlc3QtMiJGMEQCIHl29a%2Bs4bTpgaHlu%2FPYUsG3qrI2Pkr7IJOp2i7zDTOpAiAVbEqADeIp6h%2BZbn0uN2xMKwkiewZauZD1nCxvelVLbir%2FAwhSEAAaDDYzNzQyMzE4MzgwNSIM%2Fgs2l22phpaTKyERKtwDxijR6YCmSb%2BasMjeL4SPsjFvgpXyYFVBm94KDDiZuERrm3MeoILSaBj0aRIGxpkmKIXSReCPTIdfQ1G10Qv5ka%2B1Kdadegb60JJBGdZrCIEtE98nZJgG0S3s6b9MLnaN61CGiEdNNcp9nidkTcm1wn7c5Q5CyE8pI%2FdDydqi3%2FtZYKzu8ILXo34gAiXbdkFJWcffTxOmhvm7Jaqpszcr7abl%2BwXH0fmPKCYy48eyzwHdWUbrlEVP6wPfjVUHCaLi4%2FP3HBtaImcRNup9qX1GDwTPgCTEvpmuy%2FXihM9PVQBJk1YvxFFnadYWNg32BAbugeu%2F%2FF0h253ZTfvRU1DKjnhASSU%2Babp6oWCXKPw4g%2B5yjutyi%2B6yFtVJ9BURXoUcmmuSYTf8HP%2BOu%2BckpHAiJaWLeqtzyatq%2Bu8g3JYHnY6pk6DVcgQv%2FiM14MsaKDafTrYMMIkQ3qNxZYumFMLbwyRqDlU646YuKUbLuZftcG34NBsq37PRSRUV51AatYD9wy%2FQEro5AK%2BcEip3l2%2F%2FKHPM05DTUG%2FtAycgr0Zyzxlygw%2BBc7ag7CwYGdONaUY6a5UO7z4pAJvIHkMkKyC2Sn2iTFlLGWvRssP%2Bf0zS3Gu3WW%2B9nuw%2FNgek%2BPow6ObEvQY6pgFvNsIJ6p7BQvtK4xLsG9d0awwWPG5%2BFmYlDyg1PYUNPST7rf2Oprp8vVcpy6zHlnSp2ptjdMR9H5VeTT54GAVquV6qbNSOcWQH%2B58uzEs5QI8mdaWXejvZ%2Bfn1E4Qv9%2F7QYeQ4%2FIU%2Fwz%2Bow1Ey1HlMpl6FOnvboQPFdVi8Xdk3WcyC0Uv2%2B9QFtMX67C43EnPqRt8merqzALYDiMlAekPT5uBbH3N7&X-Amz-Signature=d28a8a2aff133f666844a4fd124ba0a58f83a50921fbb74ebcad60d76eb7602b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U3HQ2RAD%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T015450Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECkaCXVzLXdlc3QtMiJGMEQCIHl29a%2Bs4bTpgaHlu%2FPYUsG3qrI2Pkr7IJOp2i7zDTOpAiAVbEqADeIp6h%2BZbn0uN2xMKwkiewZauZD1nCxvelVLbir%2FAwhSEAAaDDYzNzQyMzE4MzgwNSIM%2Fgs2l22phpaTKyERKtwDxijR6YCmSb%2BasMjeL4SPsjFvgpXyYFVBm94KDDiZuERrm3MeoILSaBj0aRIGxpkmKIXSReCPTIdfQ1G10Qv5ka%2B1Kdadegb60JJBGdZrCIEtE98nZJgG0S3s6b9MLnaN61CGiEdNNcp9nidkTcm1wn7c5Q5CyE8pI%2FdDydqi3%2FtZYKzu8ILXo34gAiXbdkFJWcffTxOmhvm7Jaqpszcr7abl%2BwXH0fmPKCYy48eyzwHdWUbrlEVP6wPfjVUHCaLi4%2FP3HBtaImcRNup9qX1GDwTPgCTEvpmuy%2FXihM9PVQBJk1YvxFFnadYWNg32BAbugeu%2F%2FF0h253ZTfvRU1DKjnhASSU%2Babp6oWCXKPw4g%2B5yjutyi%2B6yFtVJ9BURXoUcmmuSYTf8HP%2BOu%2BckpHAiJaWLeqtzyatq%2Bu8g3JYHnY6pk6DVcgQv%2FiM14MsaKDafTrYMMIkQ3qNxZYumFMLbwyRqDlU646YuKUbLuZftcG34NBsq37PRSRUV51AatYD9wy%2FQEro5AK%2BcEip3l2%2F%2FKHPM05DTUG%2FtAycgr0Zyzxlygw%2BBc7ag7CwYGdONaUY6a5UO7z4pAJvIHkMkKyC2Sn2iTFlLGWvRssP%2Bf0zS3Gu3WW%2B9nuw%2FNgek%2BPow6ObEvQY6pgFvNsIJ6p7BQvtK4xLsG9d0awwWPG5%2BFmYlDyg1PYUNPST7rf2Oprp8vVcpy6zHlnSp2ptjdMR9H5VeTT54GAVquV6qbNSOcWQH%2B58uzEs5QI8mdaWXejvZ%2Bfn1E4Qv9%2F7QYeQ4%2FIU%2Fwz%2Bow1Ey1HlMpl6FOnvboQPFdVi8Xdk3WcyC0Uv2%2B9QFtMX67C43EnPqRt8merqzALYDiMlAekPT5uBbH3N7&X-Amz-Signature=fbd4ed12a4afd84ec237507c4cbbd864501aadd7426faba677776a756f30b5bc&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U3HQ2RAD%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T015450Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECkaCXVzLXdlc3QtMiJGMEQCIHl29a%2Bs4bTpgaHlu%2FPYUsG3qrI2Pkr7IJOp2i7zDTOpAiAVbEqADeIp6h%2BZbn0uN2xMKwkiewZauZD1nCxvelVLbir%2FAwhSEAAaDDYzNzQyMzE4MzgwNSIM%2Fgs2l22phpaTKyERKtwDxijR6YCmSb%2BasMjeL4SPsjFvgpXyYFVBm94KDDiZuERrm3MeoILSaBj0aRIGxpkmKIXSReCPTIdfQ1G10Qv5ka%2B1Kdadegb60JJBGdZrCIEtE98nZJgG0S3s6b9MLnaN61CGiEdNNcp9nidkTcm1wn7c5Q5CyE8pI%2FdDydqi3%2FtZYKzu8ILXo34gAiXbdkFJWcffTxOmhvm7Jaqpszcr7abl%2BwXH0fmPKCYy48eyzwHdWUbrlEVP6wPfjVUHCaLi4%2FP3HBtaImcRNup9qX1GDwTPgCTEvpmuy%2FXihM9PVQBJk1YvxFFnadYWNg32BAbugeu%2F%2FF0h253ZTfvRU1DKjnhASSU%2Babp6oWCXKPw4g%2B5yjutyi%2B6yFtVJ9BURXoUcmmuSYTf8HP%2BOu%2BckpHAiJaWLeqtzyatq%2Bu8g3JYHnY6pk6DVcgQv%2FiM14MsaKDafTrYMMIkQ3qNxZYumFMLbwyRqDlU646YuKUbLuZftcG34NBsq37PRSRUV51AatYD9wy%2FQEro5AK%2BcEip3l2%2F%2FKHPM05DTUG%2FtAycgr0Zyzxlygw%2BBc7ag7CwYGdONaUY6a5UO7z4pAJvIHkMkKyC2Sn2iTFlLGWvRssP%2Bf0zS3Gu3WW%2B9nuw%2FNgek%2BPow6ObEvQY6pgFvNsIJ6p7BQvtK4xLsG9d0awwWPG5%2BFmYlDyg1PYUNPST7rf2Oprp8vVcpy6zHlnSp2ptjdMR9H5VeTT54GAVquV6qbNSOcWQH%2B58uzEs5QI8mdaWXejvZ%2Bfn1E4Qv9%2F7QYeQ4%2FIU%2Fwz%2Bow1Ey1HlMpl6FOnvboQPFdVi8Xdk3WcyC0Uv2%2B9QFtMX67C43EnPqRt8merqzALYDiMlAekPT5uBbH3N7&X-Amz-Signature=36fa0c446f31615f34c4ec82a73c0a5edc33be821b43c81b7d060c663f5d537b&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VD6HCO45%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T015452Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECkaCXVzLXdlc3QtMiJHMEUCIQDsb1mKCw9hkRNNxk4X4MKvqcU7MlPZTnCmLj%2FC3WTLrAIgP2DotsCgDV1xRGAyuG27A8ZagDsV4IhbkXvinYJh7o8q%2FwMIUhAAGgw2Mzc0MjMxODM4MDUiDCiAK%2FPYEiQYvd8d7CrcA8TaDrGj5ciH2R8Ic51cBuXbB9aj4%2FJKsR%2FiT6A4kW8kyboPFGW3jYo6oOWyf6yS%2FW2nZLUEPtC%2BxRViYuSJLiEDAcmdi5cHC9VsAWpFWVfbLDwx3gP5NRdmDFxU7Hgi2uxkrcqQvc5pUNsAizJLxai2QeH8qNZbmsnwu%2B83u3j8uRdJz7q4rkKEJvwTWLObPoBJAF17dHrH9Nh28uq2b%2BFPC%2BNTWtYD8OJHGcMLhA9rcxndrTGFsehFtyXxv%2FoMQSKZObl7333kuEhO41QTcvUUg4Pop27ifjoQKTMIWJsE1TV%2FgQDZ5BkUsQrFwtZUE3PD1UhDgeuUjDHMh2N%2FD9MQIMoMn5nllzax9X0VG12maPHReLCr8TXioua60U4Axt1Engthiu3MDFGboE3cBmdS8Aj2lMRlZoK3ims4FPpmFBTlOHYlO3gt4h7YWgjYe5MEXODSFgCtEdSEJ1bKAk0tBhTyXF8ym7qJRBPdu3jfhGtB4TtBiw6gCigP8dVsXXG42xt%2Bd8vuf2%2FXvSXA6aqrgMvrvtn0X5nnEewGHMMjNuSfvGoEmQsvZE86bTa2PEk4xtBBRyh1o10a5Rm7E4bMdGbeUUZB8U4FV575JXVLF%2BFtYVsk3H%2Ba6of1MNPmxL0GOqUBJPXVz%2FOiYR2LMxBw9dslJsEIKAck0rRCa%2FnW4XQNgkzMXpYrI5pd5RcF7omvR7kejqgNh4ZC%2BBS2TyM5f4jxHiB0DuQNUfihA7XlWW9OAP1oTnLy7GSbPx%2BTI3Q7aFOr33uD2iqK93OH6Xdha58PEAsotkJR06D8EgArZAIMsxH%2FCpDzGmQ3kyB%2F4JDn1U20sio%2B1ERdOuw2c8TqEM64ddsC9kIX&X-Amz-Signature=f42f0b040a26651dfe4102b8ca4626e5ef87d894810fcaec479192ee1484814c&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WUEUWVU6%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T015456Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECkaCXVzLXdlc3QtMiJHMEUCIEu7ITPb3aw%2FNT%2B1QbjonYIciCxvTWr5%2BM0kIJh1P4SQAiEAxpvcyVJMrXg5qnHC6w7Q%2Fy9b5hhaMyMUXqvEO4OgJm4q%2FwMIUhAAGgw2Mzc0MjMxODM4MDUiDJARAuspuCSogM6YoircA%2FEBN81hHSZt7dNvr2lizHBubLztENhZW8y8LvBqxXdOiiMC1B0i93VoDrKHygmBIvjM3bfV69HM3myNCEdr91u3%2B0yZxzlD30NhP2bPIg8XYm43pv3zFAaTXq01BWq%2BW5xZU6QGYr1SPebtfOipyVUO80G4PM%2B%2F91fVbpJ%2BKjjHD9M52hd2x1kIA8FAbPia3UT7lHLEhGJI%2FYKhGnH1NclCl%2Bxe0b6qxTfN5au6Z0zKLGhVMAuVYauOQqoPkj1EydzLC7eBVMijYRUX4gQWd3hN3F7sO4kMe%2FuxlwbSyiQX6%2F6iGF27ONUwylIq84iTjqp3XTXoPvgq5jPpbVgX7%2FMfd%2FGiwfnPs%2BJD489hkeIYCEsgykDM6FzfEwwKO%2FKIcrL2IkPnMaB61nAsseuhCNdbWyJdiVyp112QJugfiFomXnFJoPQRTNG0aIDf%2FW6ztEgyt0lwoHwczr4fPHkPt8NTKgJTFxDeuUjR4j8YPzDdbDT%2FcKaBcEK5t4gb4rJg0VGBnawkj0S3zAQdqGhefUAobthcI4dbndNLkv9OvygJJDXLmbKgrf2Pj8MeqWxmNovPkdTeplcsb9uExy%2FaxzJafKJfI4317MFGI6xs8JHnkN2W6JLytZrVEY9OMIvnxL0GOqUBt5CTFExxij0F%2FQsmzriH4L5pG6LumX14UUHdB2f4Waed%2FjM5ABeme18IqYl4Wzhre9%2ByKdqQ6TL%2B6NANddSu7KPpxET6NHgW3tg%2BnjCovCJz5zhOrohtoY0NV8eREw4XobRoun8K5E6Y9MwhVNXfEGWsQJS%2FAuI9UN2lDf0IRWpwgW6CEJOgQF8EpOLDUuGE%2FbUq76jNOuDDsKIzJamqKs%2FJaDXh&X-Amz-Signature=45f31fa71ab2afcd43a25687880c3d40bbc63e60bccc734892c944c9fa8432df&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U3HQ2RAD%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T015450Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECkaCXVzLXdlc3QtMiJGMEQCIHl29a%2Bs4bTpgaHlu%2FPYUsG3qrI2Pkr7IJOp2i7zDTOpAiAVbEqADeIp6h%2BZbn0uN2xMKwkiewZauZD1nCxvelVLbir%2FAwhSEAAaDDYzNzQyMzE4MzgwNSIM%2Fgs2l22phpaTKyERKtwDxijR6YCmSb%2BasMjeL4SPsjFvgpXyYFVBm94KDDiZuERrm3MeoILSaBj0aRIGxpkmKIXSReCPTIdfQ1G10Qv5ka%2B1Kdadegb60JJBGdZrCIEtE98nZJgG0S3s6b9MLnaN61CGiEdNNcp9nidkTcm1wn7c5Q5CyE8pI%2FdDydqi3%2FtZYKzu8ILXo34gAiXbdkFJWcffTxOmhvm7Jaqpszcr7abl%2BwXH0fmPKCYy48eyzwHdWUbrlEVP6wPfjVUHCaLi4%2FP3HBtaImcRNup9qX1GDwTPgCTEvpmuy%2FXihM9PVQBJk1YvxFFnadYWNg32BAbugeu%2F%2FF0h253ZTfvRU1DKjnhASSU%2Babp6oWCXKPw4g%2B5yjutyi%2B6yFtVJ9BURXoUcmmuSYTf8HP%2BOu%2BckpHAiJaWLeqtzyatq%2Bu8g3JYHnY6pk6DVcgQv%2FiM14MsaKDafTrYMMIkQ3qNxZYumFMLbwyRqDlU646YuKUbLuZftcG34NBsq37PRSRUV51AatYD9wy%2FQEro5AK%2BcEip3l2%2F%2FKHPM05DTUG%2FtAycgr0Zyzxlygw%2BBc7ag7CwYGdONaUY6a5UO7z4pAJvIHkMkKyC2Sn2iTFlLGWvRssP%2Bf0zS3Gu3WW%2B9nuw%2FNgek%2BPow6ObEvQY6pgFvNsIJ6p7BQvtK4xLsG9d0awwWPG5%2BFmYlDyg1PYUNPST7rf2Oprp8vVcpy6zHlnSp2ptjdMR9H5VeTT54GAVquV6qbNSOcWQH%2B58uzEs5QI8mdaWXejvZ%2Bfn1E4Qv9%2F7QYeQ4%2FIU%2Fwz%2Bow1Ey1HlMpl6FOnvboQPFdVi8Xdk3WcyC0Uv2%2B9QFtMX67C43EnPqRt8merqzALYDiMlAekPT5uBbH3N7&X-Amz-Signature=4cf67146be0e9e986f2fe1ebcd8d532f7e88abf3afe0199c88575f3de7da2f41&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U3HQ2RAD%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T015450Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECkaCXVzLXdlc3QtMiJGMEQCIHl29a%2Bs4bTpgaHlu%2FPYUsG3qrI2Pkr7IJOp2i7zDTOpAiAVbEqADeIp6h%2BZbn0uN2xMKwkiewZauZD1nCxvelVLbir%2FAwhSEAAaDDYzNzQyMzE4MzgwNSIM%2Fgs2l22phpaTKyERKtwDxijR6YCmSb%2BasMjeL4SPsjFvgpXyYFVBm94KDDiZuERrm3MeoILSaBj0aRIGxpkmKIXSReCPTIdfQ1G10Qv5ka%2B1Kdadegb60JJBGdZrCIEtE98nZJgG0S3s6b9MLnaN61CGiEdNNcp9nidkTcm1wn7c5Q5CyE8pI%2FdDydqi3%2FtZYKzu8ILXo34gAiXbdkFJWcffTxOmhvm7Jaqpszcr7abl%2BwXH0fmPKCYy48eyzwHdWUbrlEVP6wPfjVUHCaLi4%2FP3HBtaImcRNup9qX1GDwTPgCTEvpmuy%2FXihM9PVQBJk1YvxFFnadYWNg32BAbugeu%2F%2FF0h253ZTfvRU1DKjnhASSU%2Babp6oWCXKPw4g%2B5yjutyi%2B6yFtVJ9BURXoUcmmuSYTf8HP%2BOu%2BckpHAiJaWLeqtzyatq%2Bu8g3JYHnY6pk6DVcgQv%2FiM14MsaKDafTrYMMIkQ3qNxZYumFMLbwyRqDlU646YuKUbLuZftcG34NBsq37PRSRUV51AatYD9wy%2FQEro5AK%2BcEip3l2%2F%2FKHPM05DTUG%2FtAycgr0Zyzxlygw%2BBc7ag7CwYGdONaUY6a5UO7z4pAJvIHkMkKyC2Sn2iTFlLGWvRssP%2Bf0zS3Gu3WW%2B9nuw%2FNgek%2BPow6ObEvQY6pgFvNsIJ6p7BQvtK4xLsG9d0awwWPG5%2BFmYlDyg1PYUNPST7rf2Oprp8vVcpy6zHlnSp2ptjdMR9H5VeTT54GAVquV6qbNSOcWQH%2B58uzEs5QI8mdaWXejvZ%2Bfn1E4Qv9%2F7QYeQ4%2FIU%2Fwz%2Bow1Ey1HlMpl6FOnvboQPFdVi8Xdk3WcyC0Uv2%2B9QFtMX67C43EnPqRt8merqzALYDiMlAekPT5uBbH3N7&X-Amz-Signature=5112ce819a4ae71ee56ae99872ab7309fcc456c5c372555a02357c3cc1c95b19&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U3HQ2RAD%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T015450Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECkaCXVzLXdlc3QtMiJGMEQCIHl29a%2Bs4bTpgaHlu%2FPYUsG3qrI2Pkr7IJOp2i7zDTOpAiAVbEqADeIp6h%2BZbn0uN2xMKwkiewZauZD1nCxvelVLbir%2FAwhSEAAaDDYzNzQyMzE4MzgwNSIM%2Fgs2l22phpaTKyERKtwDxijR6YCmSb%2BasMjeL4SPsjFvgpXyYFVBm94KDDiZuERrm3MeoILSaBj0aRIGxpkmKIXSReCPTIdfQ1G10Qv5ka%2B1Kdadegb60JJBGdZrCIEtE98nZJgG0S3s6b9MLnaN61CGiEdNNcp9nidkTcm1wn7c5Q5CyE8pI%2FdDydqi3%2FtZYKzu8ILXo34gAiXbdkFJWcffTxOmhvm7Jaqpszcr7abl%2BwXH0fmPKCYy48eyzwHdWUbrlEVP6wPfjVUHCaLi4%2FP3HBtaImcRNup9qX1GDwTPgCTEvpmuy%2FXihM9PVQBJk1YvxFFnadYWNg32BAbugeu%2F%2FF0h253ZTfvRU1DKjnhASSU%2Babp6oWCXKPw4g%2B5yjutyi%2B6yFtVJ9BURXoUcmmuSYTf8HP%2BOu%2BckpHAiJaWLeqtzyatq%2Bu8g3JYHnY6pk6DVcgQv%2FiM14MsaKDafTrYMMIkQ3qNxZYumFMLbwyRqDlU646YuKUbLuZftcG34NBsq37PRSRUV51AatYD9wy%2FQEro5AK%2BcEip3l2%2F%2FKHPM05DTUG%2FtAycgr0Zyzxlygw%2BBc7ag7CwYGdONaUY6a5UO7z4pAJvIHkMkKyC2Sn2iTFlLGWvRssP%2Bf0zS3Gu3WW%2B9nuw%2FNgek%2BPow6ObEvQY6pgFvNsIJ6p7BQvtK4xLsG9d0awwWPG5%2BFmYlDyg1PYUNPST7rf2Oprp8vVcpy6zHlnSp2ptjdMR9H5VeTT54GAVquV6qbNSOcWQH%2B58uzEs5QI8mdaWXejvZ%2Bfn1E4Qv9%2F7QYeQ4%2FIU%2Fwz%2Bow1Ey1HlMpl6FOnvboQPFdVi8Xdk3WcyC0Uv2%2B9QFtMX67C43EnPqRt8merqzALYDiMlAekPT5uBbH3N7&X-Amz-Signature=c687882674200c5a913cda45463e2348d83c5dd5d6d39edd43db43727b733a36&X-Amz-SignedHeaders=host&x-id=GetObject)


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

