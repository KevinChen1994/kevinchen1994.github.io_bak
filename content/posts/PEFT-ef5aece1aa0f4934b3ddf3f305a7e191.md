---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466W34VVMSB%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250221T163109Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjELD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIBhEUbTI31cET4K4jE%\
  2BZIkmBlp8Up8NXsMtYGATPmjtaAiBcPwYzWSVObcC6xuFpzD4WPKEBs84ndJvLLj87XuFRiiqIBA\
  jZ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMLtAnxEX78vKPd0%2FjK\
  twDf6a11PRoGgv%2FZUR06ZSgOoNRHELH01A8I0knFzdRXdStw9sUgN8yeWZClJzFu%2Fm0SmQrEh\
  Kb%2Fb4lC1gWpLlorgnKNnknsCSqFcfin1kATyE%2BXDipHTCOdFgDPovcATWk6AHj%2BrtjFolrh\
  ppzJM5RdDXkYj5cboEYDVv%2F%2BMMhdbkd9ysCXtL5Q8fFNlaZBV2QUBdGWTmc0C0kz3nAWiPL8Q\
  Ut1IIuTJBsNMvoIR1lh7hAb%2FTlvM2ivyjpVXLvHDQjopoHFel9wxF8U3ZWgUpeMEfsaVDLzGuP0\
  cbDbHRuxxItmrGqZRYi4vXi%2FZAKAZnkrcLOPYjKXZ4K4jCSOa4ifJFebKm0zEx7Afnf6dxvapB8\
  lim%2BuQmD%2B5czKK2%2BF2tKpAgD4k4Z%2FKgwZzqbBCnBPlHnDblL4jZgVOFzxXinpwX0JitPs\
  zU6WByueFoxbxzVsOm48S4FhT%2F3Z8wN0EAcT%2B7u3G4LevkJbV9hZfkmbKgtgznqn9I4Za5Ckn\
  Bz%2B2qocv5ajzkDQzBOyZfg7KAHGcLT3y19p7suS1QeUa8H1EjnXd8KwXrlMuCupiYsQjhRSg8H2\
  okiH1fhYrPPZiGPtp8r1W%2BTF0VQDxZ%2BsoecWsroqndEqo6TDpI820Uw%2FL3ivQY6pgE5vjmA\
  zEMl7eKgvXV9Oi9Bl8AG76glN7ZoAubhwb%2BhcGeulI5DijW76m0fTYUg%2BqK1LugyaKFdF78L5\
  loMIvmLspKY5Ds7Le3h0IC%2FUFEbUnFmRb4YGqte5vhGWPB0bNINEOghCgeYiddSWfGgx8ONrTYQ\
  tXUVTaiJHPZGd86MwEaTyuz%2BTWH2kXnhf6JQ0CJiBvtf2%2BJDOD2B1Maukjbitrwy57KW&X-Am\
  z-Signature=2d7eeca1901cb1f256b5eb8992895ba59c3a89d25ca971d8a501f3021ff7fe46&\
  X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4662OFKBAUF%2F20250221%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250221T162828Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjELD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIAeMii9SysfZfYnFyYueeYzicBxx%2FfgflgW7YyNbqqsUAiEApiCBY80dkA3PC1i1VtT5\
        N0yZCrGLy7M%2B22ubKHnka8MqiAQI2f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2M\
        zc0MjMxODM4MDUiDG8dpNA3kBPT%2B24ijCrcA6OKMBG8oLec4FQU466whFebws79AkcowW\
        y%2Bf99Qd%2FftfhlSL6AhsOMwn4t4lw4%2B5zH99i%2FC8JDDQt392UnQiH0aNi2P2ekXo\
        n92U1v1J0jbSUCRWHs9qWU1ljoJ9O4SCTNIacIm9Fc0zzY%2FA2f9%2BfX0jrnoW6U%2F%2\
        FWOGTojc3kk%2BCtzK5n42yGgOTd8G0AllPmAC0YM68IFJNDRCX0mUPgjceVKEQHKxnFB2A\
        LoiJwnWtis%2Fyi8GYQtrTXQCuA4suo5LKr%2F%2FLFt11ZgIAafdRB36%2B20ckJ1kbb6s\
        Mc6pQ2%2FcXvh8sQph%2FcJPW%2BQ5F%2FVYXiEcXi8lOJ0HMWvjHoPfDBhOi1meEzuwdgV\
        ykrDh%2BliQkRgiQmFbpZf9SQmAb5XYPrFukUqQofFIGOYW0oYvy9dOjvS2eI8%2BO8KAcO\
        5Ww1LoxhoLqAaSkLgWXCFqM2uihuWSb3A95ZUO0mnH5oKPQM2uvLEhX9bLfZnssyj6XRGUv\
        iS%2BhbfNlKdcXHoky68VfUJmjVYvYYq6ouY5Fhxh7TCRTze1ZgybxVDQm2w7NqB31RNaUt\
        xteNEb0zPIY9uup76aGYvNpSAUbLHN3Sa%2Bq1nf8lIFqnyO1UxQKHhbxPH6Rh4qY7NrsHL\
        KxOJvMKG%2B4r0GOqUBjO5pYXEPrkvFFixPsHnCkHGk01a5E9RBOM15A%2FA%2BmjUZPXp2\
        %2BLiZFJ%2BhORQq%2F%2F%2B0uQYUn4yoBGj4%2BveiA%2F9V7KrIfyjKwQGXy%2FglAUT\
        OsAXA73NNZb1A9mP%2FFg%2FXWyuVZ4iXQtN0wBB%2FPpaT%2BiniuXhi6r9KKh8TuVH3PX\
        zMQCY87jTqU2gfpIQSRD7gVg05K%2BiWEpNWIGVgrOzoow4XxvPfB1g0&X-Amz-Signatur\
        e=9c5cf654f46880a62694df09247d644768e99dd105580cd6c808d5585bcd68be&X-Am\
        z-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-21T17:28:28.317Z"
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
UPDATE_TIME: "2025-02-21T16:31:16.857Z"
EXPIRY_TIME: "2025-02-21T17:31:06.112Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YIGCLSBU%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T163106Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIDLPKa%2FBsu0tWrczrqbSa8lX1ZvW5eNCNJN12Jcnc3ZOAiEArFpSSYq22O0AzGXuGKSeFNTpUtYIodZqhX1pIcXE9d4qiAQI2f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDP%2FIlR%2FJzZmYbKSIkircA6zU9SnRyNd1mEEWkU8j0cXN1nBjgcDpc046yV%2BgVCfIeFFB9ma%2B%2BDbI1R1uSiiH%2BRCgvNXDOgeJLE1lqCl4VJZ7GqnualVkcwvZ5HKLYeZj5T2zXrkhaPDyAearfJLMZMAne6ZTqdUUc%2B%2Fz0O4ZeiNVF3I5m2xQkR9nJA7psvJuw0fya1KWQ2w%2BW4NBNSPe5i3K5yiatJWptuM3Z%2B%2FfSQlTCJTI%2BxLWCMP5mNfhot4E6VObi%2FbZNpv0AyEyOxUgNLcye13wGKac2kr2BADu12uCv5K8Elz4pHz5RuVYFCOOKLWQbUfy%2BI%2FCc3JnLspyErz6tnUHHV5QOF43XFMrAbkxXOKCEg9xkJM9JBaDXLGp7SwBbzfhR9hMkakSRvhsblk5EBCVBL10illDa1HIYYYMb9CaskaxBizyZDEfJZQRcEOpe%2FBTI0z4YDAjHclGuBpxX5DkDEbNQwiNmkxAZWQNSgxdTWhCpTLRIHNv9GcmMy46di3GKO%2FZC7BtBfPCUycuJ4cL5uUIeLUymEE%2BuM3wHO6HWX%2FbD5tHyULAfkFIwt6Rm5Lfmg008v1Aq0RWsMi7faYMmalE7eS0J%2FK6i8LcmmtpGtnYzkzVLG8JQJcuxj6OLyNLCIMDebIGMPu84r0GOqUBlBQnjqoL1APIt%2BT6dB71u%2FHfaYW%2BYWydJcVvWvTgN%2Fo%2FsfG1H9IJGpHVaENSTAcE42na6%2Bj%2FL%2FoRjt%2FDMJiyjcwBQ0H0pYT4Gd30C7GKFSqCgcowSGNb2mpRIR%2FxSDOt7STNLpGsf1nYDaIBgt6%2Fa25xL6oOjYXg3jAlBKG6V3tAyK5ChO0Kz3hYs3dYebnHq7rU24%2Fw%2FiJLAjhAB6xh23vjVUKf&X-Amz-Signature=b4682c534a4478aac863f86c014799a8999598ea17ee4ca77e32b51cea26f97c&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YIGCLSBU%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T163106Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIDLPKa%2FBsu0tWrczrqbSa8lX1ZvW5eNCNJN12Jcnc3ZOAiEArFpSSYq22O0AzGXuGKSeFNTpUtYIodZqhX1pIcXE9d4qiAQI2f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDP%2FIlR%2FJzZmYbKSIkircA6zU9SnRyNd1mEEWkU8j0cXN1nBjgcDpc046yV%2BgVCfIeFFB9ma%2B%2BDbI1R1uSiiH%2BRCgvNXDOgeJLE1lqCl4VJZ7GqnualVkcwvZ5HKLYeZj5T2zXrkhaPDyAearfJLMZMAne6ZTqdUUc%2B%2Fz0O4ZeiNVF3I5m2xQkR9nJA7psvJuw0fya1KWQ2w%2BW4NBNSPe5i3K5yiatJWptuM3Z%2B%2FfSQlTCJTI%2BxLWCMP5mNfhot4E6VObi%2FbZNpv0AyEyOxUgNLcye13wGKac2kr2BADu12uCv5K8Elz4pHz5RuVYFCOOKLWQbUfy%2BI%2FCc3JnLspyErz6tnUHHV5QOF43XFMrAbkxXOKCEg9xkJM9JBaDXLGp7SwBbzfhR9hMkakSRvhsblk5EBCVBL10illDa1HIYYYMb9CaskaxBizyZDEfJZQRcEOpe%2FBTI0z4YDAjHclGuBpxX5DkDEbNQwiNmkxAZWQNSgxdTWhCpTLRIHNv9GcmMy46di3GKO%2FZC7BtBfPCUycuJ4cL5uUIeLUymEE%2BuM3wHO6HWX%2FbD5tHyULAfkFIwt6Rm5Lfmg008v1Aq0RWsMi7faYMmalE7eS0J%2FK6i8LcmmtpGtnYzkzVLG8JQJcuxj6OLyNLCIMDebIGMPu84r0GOqUBlBQnjqoL1APIt%2BT6dB71u%2FHfaYW%2BYWydJcVvWvTgN%2Fo%2FsfG1H9IJGpHVaENSTAcE42na6%2Bj%2FL%2FoRjt%2FDMJiyjcwBQ0H0pYT4Gd30C7GKFSqCgcowSGNb2mpRIR%2FxSDOt7STNLpGsf1nYDaIBgt6%2Fa25xL6oOjYXg3jAlBKG6V3tAyK5ChO0Kz3hYs3dYebnHq7rU24%2Fw%2FiJLAjhAB6xh23vjVUKf&X-Amz-Signature=ab3515c20e02bfd1c9500a7c3ceac85aef1a69c3e45c41e08b24f9a360eb59b6&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YIGCLSBU%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T163106Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIDLPKa%2FBsu0tWrczrqbSa8lX1ZvW5eNCNJN12Jcnc3ZOAiEArFpSSYq22O0AzGXuGKSeFNTpUtYIodZqhX1pIcXE9d4qiAQI2f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDP%2FIlR%2FJzZmYbKSIkircA6zU9SnRyNd1mEEWkU8j0cXN1nBjgcDpc046yV%2BgVCfIeFFB9ma%2B%2BDbI1R1uSiiH%2BRCgvNXDOgeJLE1lqCl4VJZ7GqnualVkcwvZ5HKLYeZj5T2zXrkhaPDyAearfJLMZMAne6ZTqdUUc%2B%2Fz0O4ZeiNVF3I5m2xQkR9nJA7psvJuw0fya1KWQ2w%2BW4NBNSPe5i3K5yiatJWptuM3Z%2B%2FfSQlTCJTI%2BxLWCMP5mNfhot4E6VObi%2FbZNpv0AyEyOxUgNLcye13wGKac2kr2BADu12uCv5K8Elz4pHz5RuVYFCOOKLWQbUfy%2BI%2FCc3JnLspyErz6tnUHHV5QOF43XFMrAbkxXOKCEg9xkJM9JBaDXLGp7SwBbzfhR9hMkakSRvhsblk5EBCVBL10illDa1HIYYYMb9CaskaxBizyZDEfJZQRcEOpe%2FBTI0z4YDAjHclGuBpxX5DkDEbNQwiNmkxAZWQNSgxdTWhCpTLRIHNv9GcmMy46di3GKO%2FZC7BtBfPCUycuJ4cL5uUIeLUymEE%2BuM3wHO6HWX%2FbD5tHyULAfkFIwt6Rm5Lfmg008v1Aq0RWsMi7faYMmalE7eS0J%2FK6i8LcmmtpGtnYzkzVLG8JQJcuxj6OLyNLCIMDebIGMPu84r0GOqUBlBQnjqoL1APIt%2BT6dB71u%2FHfaYW%2BYWydJcVvWvTgN%2Fo%2FsfG1H9IJGpHVaENSTAcE42na6%2Bj%2FL%2FoRjt%2FDMJiyjcwBQ0H0pYT4Gd30C7GKFSqCgcowSGNb2mpRIR%2FxSDOt7STNLpGsf1nYDaIBgt6%2Fa25xL6oOjYXg3jAlBKG6V3tAyK5ChO0Kz3hYs3dYebnHq7rU24%2Fw%2FiJLAjhAB6xh23vjVUKf&X-Amz-Signature=ee77f9f2d171382e0147da39d3d2526f24cea3daed7a4498a06d1e4f5d8ebe45&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YIGCLSBU%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T163106Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIDLPKa%2FBsu0tWrczrqbSa8lX1ZvW5eNCNJN12Jcnc3ZOAiEArFpSSYq22O0AzGXuGKSeFNTpUtYIodZqhX1pIcXE9d4qiAQI2f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDP%2FIlR%2FJzZmYbKSIkircA6zU9SnRyNd1mEEWkU8j0cXN1nBjgcDpc046yV%2BgVCfIeFFB9ma%2B%2BDbI1R1uSiiH%2BRCgvNXDOgeJLE1lqCl4VJZ7GqnualVkcwvZ5HKLYeZj5T2zXrkhaPDyAearfJLMZMAne6ZTqdUUc%2B%2Fz0O4ZeiNVF3I5m2xQkR9nJA7psvJuw0fya1KWQ2w%2BW4NBNSPe5i3K5yiatJWptuM3Z%2B%2FfSQlTCJTI%2BxLWCMP5mNfhot4E6VObi%2FbZNpv0AyEyOxUgNLcye13wGKac2kr2BADu12uCv5K8Elz4pHz5RuVYFCOOKLWQbUfy%2BI%2FCc3JnLspyErz6tnUHHV5QOF43XFMrAbkxXOKCEg9xkJM9JBaDXLGp7SwBbzfhR9hMkakSRvhsblk5EBCVBL10illDa1HIYYYMb9CaskaxBizyZDEfJZQRcEOpe%2FBTI0z4YDAjHclGuBpxX5DkDEbNQwiNmkxAZWQNSgxdTWhCpTLRIHNv9GcmMy46di3GKO%2FZC7BtBfPCUycuJ4cL5uUIeLUymEE%2BuM3wHO6HWX%2FbD5tHyULAfkFIwt6Rm5Lfmg008v1Aq0RWsMi7faYMmalE7eS0J%2FK6i8LcmmtpGtnYzkzVLG8JQJcuxj6OLyNLCIMDebIGMPu84r0GOqUBlBQnjqoL1APIt%2BT6dB71u%2FHfaYW%2BYWydJcVvWvTgN%2Fo%2FsfG1H9IJGpHVaENSTAcE42na6%2Bj%2FL%2FoRjt%2FDMJiyjcwBQ0H0pYT4Gd30C7GKFSqCgcowSGNb2mpRIR%2FxSDOt7STNLpGsf1nYDaIBgt6%2Fa25xL6oOjYXg3jAlBKG6V3tAyK5ChO0Kz3hYs3dYebnHq7rU24%2Fw%2FiJLAjhAB6xh23vjVUKf&X-Amz-Signature=f943a0e964af57cab5e552641a487926218360ea9b3f3473c3b2ea8656a03a3a&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YIGCLSBU%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T163106Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIDLPKa%2FBsu0tWrczrqbSa8lX1ZvW5eNCNJN12Jcnc3ZOAiEArFpSSYq22O0AzGXuGKSeFNTpUtYIodZqhX1pIcXE9d4qiAQI2f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDP%2FIlR%2FJzZmYbKSIkircA6zU9SnRyNd1mEEWkU8j0cXN1nBjgcDpc046yV%2BgVCfIeFFB9ma%2B%2BDbI1R1uSiiH%2BRCgvNXDOgeJLE1lqCl4VJZ7GqnualVkcwvZ5HKLYeZj5T2zXrkhaPDyAearfJLMZMAne6ZTqdUUc%2B%2Fz0O4ZeiNVF3I5m2xQkR9nJA7psvJuw0fya1KWQ2w%2BW4NBNSPe5i3K5yiatJWptuM3Z%2B%2FfSQlTCJTI%2BxLWCMP5mNfhot4E6VObi%2FbZNpv0AyEyOxUgNLcye13wGKac2kr2BADu12uCv5K8Elz4pHz5RuVYFCOOKLWQbUfy%2BI%2FCc3JnLspyErz6tnUHHV5QOF43XFMrAbkxXOKCEg9xkJM9JBaDXLGp7SwBbzfhR9hMkakSRvhsblk5EBCVBL10illDa1HIYYYMb9CaskaxBizyZDEfJZQRcEOpe%2FBTI0z4YDAjHclGuBpxX5DkDEbNQwiNmkxAZWQNSgxdTWhCpTLRIHNv9GcmMy46di3GKO%2FZC7BtBfPCUycuJ4cL5uUIeLUymEE%2BuM3wHO6HWX%2FbD5tHyULAfkFIwt6Rm5Lfmg008v1Aq0RWsMi7faYMmalE7eS0J%2FK6i8LcmmtpGtnYzkzVLG8JQJcuxj6OLyNLCIMDebIGMPu84r0GOqUBlBQnjqoL1APIt%2BT6dB71u%2FHfaYW%2BYWydJcVvWvTgN%2Fo%2FsfG1H9IJGpHVaENSTAcE42na6%2Bj%2FL%2FoRjt%2FDMJiyjcwBQ0H0pYT4Gd30C7GKFSqCgcowSGNb2mpRIR%2FxSDOt7STNLpGsf1nYDaIBgt6%2Fa25xL6oOjYXg3jAlBKG6V3tAyK5ChO0Kz3hYs3dYebnHq7rU24%2Fw%2FiJLAjhAB6xh23vjVUKf&X-Amz-Signature=94309eede894b706967166b0034b4f36c4a9931d1745ce785d35d2360427f4e2&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SU7PUQCB%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T163107Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCD8HOaBpUYgjInvgqEIKz5RtqxeZNrTTSWuWSj9OLiMQIhANdBalq97kX9P0uXzkTlQQY1JeLVYkm3am0PBjuEsNEAKogECNn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzWSbiZoqmquq2XvIEq3AO17N2H4EKIPyjMuPKwiGCgvPi9EoXWrIKCXDG7Q%2FL9i2C17Pzaeq4yZy%2F1m%2B5BFJqGhn%2FvR%2F3YZLqxFrwZ7atA1geegS4WWvHadO%2F9k5iluOMrUgxSqjZPhuHOevcTUQE8Gh0%2FlndjA0HLcB%2Br7%2B2m0CHnolDUPu33FIfQSMAHwr7tHn8GKaQ94X%2B7PafuNACo7Y910Z6cmwgNZKjNUw%2BWPkeosfXiv6%2BWAQYXUAue2xCLSgDotsqEpH6T9wHyOvmHVRaPbxWath%2Bxh0%2BmRTAE6ovDig90rvD%2BJMpak4SNrIZuzdcGqaYMJAAcaAeQjxQG3Wlq3C63il0elWWpUDbA9ABkumIg7vOL1eMcXFELVCwk97es1PZ2O9SCxDvHir%2FBr9pZP7pVS%2B1iRvJETdGcETFl6%2FfvrZRk1cXBB7tMe9qeZPW7P2%2ByYIsYlzaB6p7kh46XhsWCnshyiiJB3ni4MWKQYzwEdzbfhf6xb4ozQKv3%2FsIfaGpU4JJBWGHe%2F%2FwG6EfG5%2FlHkyhmZQEDBG7BNPRvZdh4Pag4NCPav16PP7PwZc%2FPatFCVNpJXRzHv8WfzBGYriAlEL1uCXMW78BQrNQGPzg8vrBEb4JDdL3QQh76rKHmfFH3a9ZyXjCCveK9BjqkAQ9Uo0Epqd7zEHAiyjYlaCZPfl2M%2FGPlb0yfYoWMbxj%2FAki%2BF7hGD5BOot4Uob6OJ6wX1dDj7VbO2veRXqSf%2BiOzygZ9y7CyRolSltgiG0cCuHzW2c3HtN8ZmzHUrR4AgH%2BJdUiq61yX6DSpxWdVkUFPBF%2BGxeei8rykFga1bnOfv1vhd63UiAHKrhKqJMWBchuvcXAA9tjvDBU9Hu7zUMhjsy8%2B&X-Amz-Signature=5d4702f3e62941ac7cb32962ef9581189e982d3aa8a8b9c7a37194de674d780f&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665H2GKV5R%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T163108Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIDRMbmb2FTnl8mrmHYjruwg7IVjceAm2sJQ7uBUCdi0kAiA%2FR4F58T%2F6%2FX2gNhzfonphvUf1NZEeKiJcZzeD5r7fqCqIBAjZ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMQEclwihJRUaDp7gLKtwD5UBG18tr6KN%2FOXy9IJCHH8mZ9TnDEKRvVyp2cmqcrq67L%2BAQEB9AUpgI7INMvW6ViTbfvME9L7%2BtA8UthLlrgY5nwQBxzkuA%2F6D19EosVofj%2BC7RgPe7vD2UODWIOkHghcLoiABZvyNE%2BltnwtjWrtGQQSXaLEK3S%2F%2BlcKfu42LY8YZ%2B%2FI4I0vJ8yde8KyhR7loqk2QG5bMfEc%2FjTTNuyIQfaCdYDDFNAiHoOHB09WsJD4XGYDCGu2G99y1q44mfO9ft62OuXZsjNHWEaiMIFfoUToORTDQoTL0HupZqWU0VhLZiQ278rjE2C89PJPppGhimwThYHt04DsBUFw5233sy5QAZpKiDS6tXQ5H2cxiwy1doZ8NPUgS%2BB40MG2tFYwKUUkVhbnaaDnTRxpbzzcF9mdag3NnPGyrO8m%2Bd9RU%2BYo7QlRq0H%2BH2ZPjekhwxDTTvkZIPr53SFpIk9MTSbAORIJTDs3sMg3QQtpjMBxZpug4Uct70LjzHvjZyEHu8sXh5IZnCwuQJS1BRQVG0DxwhZV08IcFHZWwMeqrQJMfM%2F7N3aYf5dQDUBwPv51ZcK0pmqnkFSC1ZhtwOfygzV1QA5sK7s5kFpvGBl29JFFJKBfrqC3YhzSQeYr0w%2FL3ivQY6pgEV4UpztDir3UD%2BHGCbIyM4DictBTDvkg2T1Y9Gq79hUR2Zlz4Nnou2pyDE3s4JzhKRtiQleMuNGQJNj9WTA5iTMdt%2BeeTatzxmKv4RKjWv%2FTZUIKij5zarhQiJKwNM9d8gzilrkzDEmQBJT%2BWMMqBPjX2Tvue8Mx77%2BLkrt1GhgQKyG5JMX2nyoc1MbBnPXRzWcbc35s32gNBl02ugLqFH0%2FaJ9vNq&X-Amz-Signature=bab3a027fc22c4b770c7f9d0fa7136d00f5bf2bd64f782df775a1ecae15f87fb&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YIGCLSBU%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T163106Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIDLPKa%2FBsu0tWrczrqbSa8lX1ZvW5eNCNJN12Jcnc3ZOAiEArFpSSYq22O0AzGXuGKSeFNTpUtYIodZqhX1pIcXE9d4qiAQI2f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDP%2FIlR%2FJzZmYbKSIkircA6zU9SnRyNd1mEEWkU8j0cXN1nBjgcDpc046yV%2BgVCfIeFFB9ma%2B%2BDbI1R1uSiiH%2BRCgvNXDOgeJLE1lqCl4VJZ7GqnualVkcwvZ5HKLYeZj5T2zXrkhaPDyAearfJLMZMAne6ZTqdUUc%2B%2Fz0O4ZeiNVF3I5m2xQkR9nJA7psvJuw0fya1KWQ2w%2BW4NBNSPe5i3K5yiatJWptuM3Z%2B%2FfSQlTCJTI%2BxLWCMP5mNfhot4E6VObi%2FbZNpv0AyEyOxUgNLcye13wGKac2kr2BADu12uCv5K8Elz4pHz5RuVYFCOOKLWQbUfy%2BI%2FCc3JnLspyErz6tnUHHV5QOF43XFMrAbkxXOKCEg9xkJM9JBaDXLGp7SwBbzfhR9hMkakSRvhsblk5EBCVBL10illDa1HIYYYMb9CaskaxBizyZDEfJZQRcEOpe%2FBTI0z4YDAjHclGuBpxX5DkDEbNQwiNmkxAZWQNSgxdTWhCpTLRIHNv9GcmMy46di3GKO%2FZC7BtBfPCUycuJ4cL5uUIeLUymEE%2BuM3wHO6HWX%2FbD5tHyULAfkFIwt6Rm5Lfmg008v1Aq0RWsMi7faYMmalE7eS0J%2FK6i8LcmmtpGtnYzkzVLG8JQJcuxj6OLyNLCIMDebIGMPu84r0GOqUBlBQnjqoL1APIt%2BT6dB71u%2FHfaYW%2BYWydJcVvWvTgN%2Fo%2FsfG1H9IJGpHVaENSTAcE42na6%2Bj%2FL%2FoRjt%2FDMJiyjcwBQ0H0pYT4Gd30C7GKFSqCgcowSGNb2mpRIR%2FxSDOt7STNLpGsf1nYDaIBgt6%2Fa25xL6oOjYXg3jAlBKG6V3tAyK5ChO0Kz3hYs3dYebnHq7rU24%2Fw%2FiJLAjhAB6xh23vjVUKf&X-Amz-Signature=706911872ee50f6ab17c58cd832a9a1fecc911cec62e417780acaaec44cf344b&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YIGCLSBU%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T163106Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIDLPKa%2FBsu0tWrczrqbSa8lX1ZvW5eNCNJN12Jcnc3ZOAiEArFpSSYq22O0AzGXuGKSeFNTpUtYIodZqhX1pIcXE9d4qiAQI2f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDP%2FIlR%2FJzZmYbKSIkircA6zU9SnRyNd1mEEWkU8j0cXN1nBjgcDpc046yV%2BgVCfIeFFB9ma%2B%2BDbI1R1uSiiH%2BRCgvNXDOgeJLE1lqCl4VJZ7GqnualVkcwvZ5HKLYeZj5T2zXrkhaPDyAearfJLMZMAne6ZTqdUUc%2B%2Fz0O4ZeiNVF3I5m2xQkR9nJA7psvJuw0fya1KWQ2w%2BW4NBNSPe5i3K5yiatJWptuM3Z%2B%2FfSQlTCJTI%2BxLWCMP5mNfhot4E6VObi%2FbZNpv0AyEyOxUgNLcye13wGKac2kr2BADu12uCv5K8Elz4pHz5RuVYFCOOKLWQbUfy%2BI%2FCc3JnLspyErz6tnUHHV5QOF43XFMrAbkxXOKCEg9xkJM9JBaDXLGp7SwBbzfhR9hMkakSRvhsblk5EBCVBL10illDa1HIYYYMb9CaskaxBizyZDEfJZQRcEOpe%2FBTI0z4YDAjHclGuBpxX5DkDEbNQwiNmkxAZWQNSgxdTWhCpTLRIHNv9GcmMy46di3GKO%2FZC7BtBfPCUycuJ4cL5uUIeLUymEE%2BuM3wHO6HWX%2FbD5tHyULAfkFIwt6Rm5Lfmg008v1Aq0RWsMi7faYMmalE7eS0J%2FK6i8LcmmtpGtnYzkzVLG8JQJcuxj6OLyNLCIMDebIGMPu84r0GOqUBlBQnjqoL1APIt%2BT6dB71u%2FHfaYW%2BYWydJcVvWvTgN%2Fo%2FsfG1H9IJGpHVaENSTAcE42na6%2Bj%2FL%2FoRjt%2FDMJiyjcwBQ0H0pYT4Gd30C7GKFSqCgcowSGNb2mpRIR%2FxSDOt7STNLpGsf1nYDaIBgt6%2Fa25xL6oOjYXg3jAlBKG6V3tAyK5ChO0Kz3hYs3dYebnHq7rU24%2Fw%2FiJLAjhAB6xh23vjVUKf&X-Amz-Signature=70623c965d5cbc22f1f62b6783b4cac9574cc577049d617909a9110bcb7b909e&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YIGCLSBU%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T163106Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIDLPKa%2FBsu0tWrczrqbSa8lX1ZvW5eNCNJN12Jcnc3ZOAiEArFpSSYq22O0AzGXuGKSeFNTpUtYIodZqhX1pIcXE9d4qiAQI2f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDP%2FIlR%2FJzZmYbKSIkircA6zU9SnRyNd1mEEWkU8j0cXN1nBjgcDpc046yV%2BgVCfIeFFB9ma%2B%2BDbI1R1uSiiH%2BRCgvNXDOgeJLE1lqCl4VJZ7GqnualVkcwvZ5HKLYeZj5T2zXrkhaPDyAearfJLMZMAne6ZTqdUUc%2B%2Fz0O4ZeiNVF3I5m2xQkR9nJA7psvJuw0fya1KWQ2w%2BW4NBNSPe5i3K5yiatJWptuM3Z%2B%2FfSQlTCJTI%2BxLWCMP5mNfhot4E6VObi%2FbZNpv0AyEyOxUgNLcye13wGKac2kr2BADu12uCv5K8Elz4pHz5RuVYFCOOKLWQbUfy%2BI%2FCc3JnLspyErz6tnUHHV5QOF43XFMrAbkxXOKCEg9xkJM9JBaDXLGp7SwBbzfhR9hMkakSRvhsblk5EBCVBL10illDa1HIYYYMb9CaskaxBizyZDEfJZQRcEOpe%2FBTI0z4YDAjHclGuBpxX5DkDEbNQwiNmkxAZWQNSgxdTWhCpTLRIHNv9GcmMy46di3GKO%2FZC7BtBfPCUycuJ4cL5uUIeLUymEE%2BuM3wHO6HWX%2FbD5tHyULAfkFIwt6Rm5Lfmg008v1Aq0RWsMi7faYMmalE7eS0J%2FK6i8LcmmtpGtnYzkzVLG8JQJcuxj6OLyNLCIMDebIGMPu84r0GOqUBlBQnjqoL1APIt%2BT6dB71u%2FHfaYW%2BYWydJcVvWvTgN%2Fo%2FsfG1H9IJGpHVaENSTAcE42na6%2Bj%2FL%2FoRjt%2FDMJiyjcwBQ0H0pYT4Gd30C7GKFSqCgcowSGNb2mpRIR%2FxSDOt7STNLpGsf1nYDaIBgt6%2Fa25xL6oOjYXg3jAlBKG6V3tAyK5ChO0Kz3hYs3dYebnHq7rU24%2Fw%2FiJLAjhAB6xh23vjVUKf&X-Amz-Signature=ac1337c5d60c078c72460b313e9af73e4f6aaf64e2a80c8fd1778fdd5d94440f&X-Amz-SignedHeaders=host&x-id=GetObject)


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

