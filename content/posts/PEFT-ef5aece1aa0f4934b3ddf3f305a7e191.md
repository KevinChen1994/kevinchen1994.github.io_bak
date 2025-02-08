---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4667UK4X4C2%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250208T222017Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEH4aCXVzLXdlc3QtMiJGMEQCIHtjuknWpuV%2B20cPvULAncDSKVYjoATx4y5bjeXQWUiLAiBLv\
  ZIs1HXxqLKQifF3It%2F8DrQAIL14F89REQysVWsReCqIBAiX%2F%2F%2F%2F%2F%2F%2F%2F%2F%\
  2F8BEAAaDDYzNzQyMzE4MzgwNSIMAJlslObXYEoqxu%2BHKtwDIRVrC1bSwUMFibHY5c14oI68u3t\
  %2BHQH7zMEjCvnkS6LpcXI4cB87PUADZS9gzTcZwnxoAxXlGUlZ%2BR%2BrdOzr0PTXRBJFz5o5Mc\
  YL2UK9EVDR5RUIwEJKEAVfHXcyaT5hh4FaBiWzkVxO0lWs13kkok6%2FQzRA3f3LTnKrTAATWM6f%\
  2By87ONWh8hCAjDAV20JKsxv0wW%2Fz5IgcXzzftK9nhiNkQOLEXqwR48%2FKRc%2BBvOzOofI8KC\
  6VdQEGX9W9VrgzTCTI%2BkYCm%2BYRCJVhXLJuPpcmfZZN1CiNUza%2Bl32Xgp9GOIaDbUId%2B%2\
  FAK1oHckRHEY9EnZXfGV9lU9e%2BJpQ3Mm8XJMZBJrUp5XmbELfjW5pzaDjer44eca4yi0bkOUyxg\
  f9IrTmH2j6vCvI2COqtef0HQ84kkCp6yMuTTp2IK%2FZ4Vfi%2F7pkB5mAio3yDto38ZK%2FxEX0n\
  zK18TwQ2Z3CxmpYwuayrYF21Khd%2Fs96S89D54pQkCKdqgVGB2yjpVWAyyjcRZJnuzgMbdkJMjb%\
  2FkL14MaR4LfBg0T%2BMpD5Q%2FPhbzypZyHl1LExLbcedePUGlE7ksZQhhpCzPdXg9JdTDz2HiKW\
  S0vBfFZtJCrn1nsOeUr2KyFSB4Y78Aj5Agw4ZifvQY6pgESa00rSejrqqGCgwHdfZPBDVl0eBuNpH\
  MNw2BggOD1H9PEwGtyL8WbuVa%2Fbl4m1k5JabOFHRBZEknzKMflP08vVJQEuwyT0j2ycAzVzBtCK\
  z6wAbZItwUwCa7Krg8XpgcBR5uvRP%2Bh90rPwmW7OlawimBZjYS409KqSbksxnnXCJjMtkLnosOn\
  t1cwcw5kH8fdo4wJod1MXcb614k8zvwt7aBkdrKF&X-Amz-Signature=60648951790585a2b97c\
  9e86facd74ebfef71838c5fddfdac0ec8ca2ab15c5bb&X-Amz-SignedHeaders=host&x-id=Ge\
  tObject"
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
        redential=ASIAZI2LB466SDHYL7GE%2F20250208%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250208T221917Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEH4aCXVzLXdlc3QtMiJHMEUCIQDqcXVLRk%2Fgj9Jane7jW2ogabWIu\
        OyCFs8uaEr3W0jNDQIgYcxCsgmnDQvPATOr29z%2BKSr1tf%2BLp9jA%2FLeUoHJI69oqiA\
        QIl%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDN9BKamdLqJ\
        a6bfx3CrcA81DczHsmKvTUjEyXg8Uyq4uuNYRdkliPSImvY53st3E8BKqzt7rSFz0fsABD%\
        2BBOhiqck7FNkJpy0KPMBi%2FRfpyXwrldW7Lazc7cq5yJwDa785TPtDMhNJmYWVMqPUDIX\
        5G9IKoShbBUeo6%2FbBh4sCXhJemc%2FORKhNUUNG7lmJ%2FLnBncPdETLrPo2uDmEnJ%2B\
        tqRLqeXQQJA4ZkiIb1soBrSzlCq8x%2Btwqiox%2ByI1Cflok6Nf6w3yb2qBIZq531gHGpW\
        XHCfxPLmQOM0L1Wv5ahXnbTZNQ%2FjqSlwUQ3pcQliztqaYAEQY1C303zLgURn9Yzkwlzyu\
        1Tu9C%2F2bRRLQOxrCRa8YkHeZXmtS9oEa0UuFEuR7XHuQ0JeBKZYAZuppHR1tk5zZxbitV\
        TOxYSQd6%2BPO2ZwkfL8WG%2FIutQYwUdXKPTal3MAJNLADW93PdG9vmYoHZReVrYaa37Jp\
        1rGGPnS1SCW53mdERYNiVO5PQMtJp5G1i1AzSX9uxp45T9oG0%2B%2Bn3eGYEc55Gd0lMJY\
        FIIcfg0uKpEnWHKJLGXaVXKbw75Ac5XPmw1YM77FuFpgkgIG4bH3crlWmIqeh1FR%2BmV4K\
        Qq%2FNrx%2B6viMIxPrbfrifcaghOQO%2F%2B1jksKNDML%2BYn70GOqUBdJC0WvNBT1YDP\
        FIEa4tNCgIrwtofpL1HG9iddoykhCD6RDE2%2F84oiFN6rU%2FqiIAvRv26MpjjFoj3CVsE\
        2hzR22N23K9Q9EGofhuyJCBRo134%2F0U1asS2ER7gZ7Sz6V3yyognU8OkjjrZF9HxHcYgC\
        oZBUoyJNIT7%2BI79Y5vCIUlUAZh%2BR7i4vaJUY8OFDtVY%2FIquV7ni%2Ft%2BBzhtx%2\
        Fl15EeDa7hSA&X-Amz-Signature=a80787dd1d8595db3bef0570a55e9ab5b268a5c0da\
        2dc97cc2f85a5e087bfa3f&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-08T23:19:17.827Z"
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
UPDATE_TIME: "2025-02-08T22:20:23.009Z"
EXPIRY_TIME: "2025-02-08T23:20:14.663Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663LVYNE7F%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T222015Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEH4aCXVzLXdlc3QtMiJHMEUCIEmV2Suc5Nt02IK3%2BnaRj8bJE8O2KLFw3q5VUtVg0p0RAiEA0pGo0q62U%2FN1o%2FcTOpFjQ9rEeRJvKdO5Hie7JHhJ0EsqiAQIl%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMBugWpKRvcCYRDYpCrcA7B4jpMWzi9KlB06CPXSvkcXoSImEK55QFaeVP9w10rTIWPRlgDQg4QatTFmG5yUHQDJI37W%2BKkf0O6BNTiUepzVMDc0HksLs5eEimHNfasc0nxZ95fMG2W%2FseJKeiMmYrs12BLEWSxyP1wJazFxQuDp0RURLWUkggPN47sPF5EHAZFamuN%2FxdVW8aBniNPW5bJjaoQ7ncUW7zrfWdxVe8fTW1hrjUrMF2NfGzffYizOQQlb6uz8kEtjUz3z%2FDkGKQta1aDwTiffuw7MDBXUAOqcySkYlfXI%2F9uVO7gW2G5TUa4e1QdvJoJvMIXbGZcxR8eGo6siAoLvSJrz1V6uc53CutOuUG3tclahdf1nxr6bBNk1a2k%2Fz2ws0ufspoqbK6lNfUjFN4k8%2FifK3usyH6fWLVq43cvQO5xCHVf15Y1VfsH25mxi27ii28%2B48Q6VzVbyjsRdsMy7%2FBExY58USkNacieSWa3m7DFgdqFNDqGJMBBq7K%2FXvwruLm0rAaXFPbzGSMk7sHXmDN98s7DSFmO1ZmspUpaaQyB7wzoykB07fzNydF1YdWlfntebs%2F4MLjBepIG7kDCS2lvPrJmeJZ%2FCkh6OS4nyyR4bDQRF7xEgUoOdMe2pma2WCpwlMKKYn70GOqUBFgocsfxk2kgHH4qhqswUDumE1tMpEbSzrOyH7%2FhDODtt6ainYm%2FLt%2BLBy13Fp9IrUPpXZ8ZjApBurd6W2DTMTuOKDJkGJgqCEBBO2wLjW079iSHsDCTDAke8nsNRWfMdN%2BLLIiAnjHtFP7XkolMzY%2BapuKzqFtJ%2BUlbAwdahuBOHeZ1k%2FDKqBPM0TI74nKjf6JVLRBDAlRYA6NACtVaoN%2FxEwzq8&X-Amz-Signature=068d038128f9bce1c9cc311685e1a3bc008188da9f4e9a3ddc0cf98d8d8df1b2&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663LVYNE7F%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T222015Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEH4aCXVzLXdlc3QtMiJHMEUCIEmV2Suc5Nt02IK3%2BnaRj8bJE8O2KLFw3q5VUtVg0p0RAiEA0pGo0q62U%2FN1o%2FcTOpFjQ9rEeRJvKdO5Hie7JHhJ0EsqiAQIl%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMBugWpKRvcCYRDYpCrcA7B4jpMWzi9KlB06CPXSvkcXoSImEK55QFaeVP9w10rTIWPRlgDQg4QatTFmG5yUHQDJI37W%2BKkf0O6BNTiUepzVMDc0HksLs5eEimHNfasc0nxZ95fMG2W%2FseJKeiMmYrs12BLEWSxyP1wJazFxQuDp0RURLWUkggPN47sPF5EHAZFamuN%2FxdVW8aBniNPW5bJjaoQ7ncUW7zrfWdxVe8fTW1hrjUrMF2NfGzffYizOQQlb6uz8kEtjUz3z%2FDkGKQta1aDwTiffuw7MDBXUAOqcySkYlfXI%2F9uVO7gW2G5TUa4e1QdvJoJvMIXbGZcxR8eGo6siAoLvSJrz1V6uc53CutOuUG3tclahdf1nxr6bBNk1a2k%2Fz2ws0ufspoqbK6lNfUjFN4k8%2FifK3usyH6fWLVq43cvQO5xCHVf15Y1VfsH25mxi27ii28%2B48Q6VzVbyjsRdsMy7%2FBExY58USkNacieSWa3m7DFgdqFNDqGJMBBq7K%2FXvwruLm0rAaXFPbzGSMk7sHXmDN98s7DSFmO1ZmspUpaaQyB7wzoykB07fzNydF1YdWlfntebs%2F4MLjBepIG7kDCS2lvPrJmeJZ%2FCkh6OS4nyyR4bDQRF7xEgUoOdMe2pma2WCpwlMKKYn70GOqUBFgocsfxk2kgHH4qhqswUDumE1tMpEbSzrOyH7%2FhDODtt6ainYm%2FLt%2BLBy13Fp9IrUPpXZ8ZjApBurd6W2DTMTuOKDJkGJgqCEBBO2wLjW079iSHsDCTDAke8nsNRWfMdN%2BLLIiAnjHtFP7XkolMzY%2BapuKzqFtJ%2BUlbAwdahuBOHeZ1k%2FDKqBPM0TI74nKjf6JVLRBDAlRYA6NACtVaoN%2FxEwzq8&X-Amz-Signature=7fceb359f84a35056264309f95a13615ce3d3bec7e82b291df2e78ac3d1dbcdd&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663LVYNE7F%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T222015Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEH4aCXVzLXdlc3QtMiJHMEUCIEmV2Suc5Nt02IK3%2BnaRj8bJE8O2KLFw3q5VUtVg0p0RAiEA0pGo0q62U%2FN1o%2FcTOpFjQ9rEeRJvKdO5Hie7JHhJ0EsqiAQIl%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMBugWpKRvcCYRDYpCrcA7B4jpMWzi9KlB06CPXSvkcXoSImEK55QFaeVP9w10rTIWPRlgDQg4QatTFmG5yUHQDJI37W%2BKkf0O6BNTiUepzVMDc0HksLs5eEimHNfasc0nxZ95fMG2W%2FseJKeiMmYrs12BLEWSxyP1wJazFxQuDp0RURLWUkggPN47sPF5EHAZFamuN%2FxdVW8aBniNPW5bJjaoQ7ncUW7zrfWdxVe8fTW1hrjUrMF2NfGzffYizOQQlb6uz8kEtjUz3z%2FDkGKQta1aDwTiffuw7MDBXUAOqcySkYlfXI%2F9uVO7gW2G5TUa4e1QdvJoJvMIXbGZcxR8eGo6siAoLvSJrz1V6uc53CutOuUG3tclahdf1nxr6bBNk1a2k%2Fz2ws0ufspoqbK6lNfUjFN4k8%2FifK3usyH6fWLVq43cvQO5xCHVf15Y1VfsH25mxi27ii28%2B48Q6VzVbyjsRdsMy7%2FBExY58USkNacieSWa3m7DFgdqFNDqGJMBBq7K%2FXvwruLm0rAaXFPbzGSMk7sHXmDN98s7DSFmO1ZmspUpaaQyB7wzoykB07fzNydF1YdWlfntebs%2F4MLjBepIG7kDCS2lvPrJmeJZ%2FCkh6OS4nyyR4bDQRF7xEgUoOdMe2pma2WCpwlMKKYn70GOqUBFgocsfxk2kgHH4qhqswUDumE1tMpEbSzrOyH7%2FhDODtt6ainYm%2FLt%2BLBy13Fp9IrUPpXZ8ZjApBurd6W2DTMTuOKDJkGJgqCEBBO2wLjW079iSHsDCTDAke8nsNRWfMdN%2BLLIiAnjHtFP7XkolMzY%2BapuKzqFtJ%2BUlbAwdahuBOHeZ1k%2FDKqBPM0TI74nKjf6JVLRBDAlRYA6NACtVaoN%2FxEwzq8&X-Amz-Signature=a3b67a8bac46f0849df2d5def405d73a6c7664d483fd3642b591ef56a628f038&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663LVYNE7F%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T222015Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEH4aCXVzLXdlc3QtMiJHMEUCIEmV2Suc5Nt02IK3%2BnaRj8bJE8O2KLFw3q5VUtVg0p0RAiEA0pGo0q62U%2FN1o%2FcTOpFjQ9rEeRJvKdO5Hie7JHhJ0EsqiAQIl%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMBugWpKRvcCYRDYpCrcA7B4jpMWzi9KlB06CPXSvkcXoSImEK55QFaeVP9w10rTIWPRlgDQg4QatTFmG5yUHQDJI37W%2BKkf0O6BNTiUepzVMDc0HksLs5eEimHNfasc0nxZ95fMG2W%2FseJKeiMmYrs12BLEWSxyP1wJazFxQuDp0RURLWUkggPN47sPF5EHAZFamuN%2FxdVW8aBniNPW5bJjaoQ7ncUW7zrfWdxVe8fTW1hrjUrMF2NfGzffYizOQQlb6uz8kEtjUz3z%2FDkGKQta1aDwTiffuw7MDBXUAOqcySkYlfXI%2F9uVO7gW2G5TUa4e1QdvJoJvMIXbGZcxR8eGo6siAoLvSJrz1V6uc53CutOuUG3tclahdf1nxr6bBNk1a2k%2Fz2ws0ufspoqbK6lNfUjFN4k8%2FifK3usyH6fWLVq43cvQO5xCHVf15Y1VfsH25mxi27ii28%2B48Q6VzVbyjsRdsMy7%2FBExY58USkNacieSWa3m7DFgdqFNDqGJMBBq7K%2FXvwruLm0rAaXFPbzGSMk7sHXmDN98s7DSFmO1ZmspUpaaQyB7wzoykB07fzNydF1YdWlfntebs%2F4MLjBepIG7kDCS2lvPrJmeJZ%2FCkh6OS4nyyR4bDQRF7xEgUoOdMe2pma2WCpwlMKKYn70GOqUBFgocsfxk2kgHH4qhqswUDumE1tMpEbSzrOyH7%2FhDODtt6ainYm%2FLt%2BLBy13Fp9IrUPpXZ8ZjApBurd6W2DTMTuOKDJkGJgqCEBBO2wLjW079iSHsDCTDAke8nsNRWfMdN%2BLLIiAnjHtFP7XkolMzY%2BapuKzqFtJ%2BUlbAwdahuBOHeZ1k%2FDKqBPM0TI74nKjf6JVLRBDAlRYA6NACtVaoN%2FxEwzq8&X-Amz-Signature=286ef1af48a9f7400ffeef7354a6b6d4d4648e22a639979742bcdbf39df09746&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663LVYNE7F%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T222015Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEH4aCXVzLXdlc3QtMiJHMEUCIEmV2Suc5Nt02IK3%2BnaRj8bJE8O2KLFw3q5VUtVg0p0RAiEA0pGo0q62U%2FN1o%2FcTOpFjQ9rEeRJvKdO5Hie7JHhJ0EsqiAQIl%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMBugWpKRvcCYRDYpCrcA7B4jpMWzi9KlB06CPXSvkcXoSImEK55QFaeVP9w10rTIWPRlgDQg4QatTFmG5yUHQDJI37W%2BKkf0O6BNTiUepzVMDc0HksLs5eEimHNfasc0nxZ95fMG2W%2FseJKeiMmYrs12BLEWSxyP1wJazFxQuDp0RURLWUkggPN47sPF5EHAZFamuN%2FxdVW8aBniNPW5bJjaoQ7ncUW7zrfWdxVe8fTW1hrjUrMF2NfGzffYizOQQlb6uz8kEtjUz3z%2FDkGKQta1aDwTiffuw7MDBXUAOqcySkYlfXI%2F9uVO7gW2G5TUa4e1QdvJoJvMIXbGZcxR8eGo6siAoLvSJrz1V6uc53CutOuUG3tclahdf1nxr6bBNk1a2k%2Fz2ws0ufspoqbK6lNfUjFN4k8%2FifK3usyH6fWLVq43cvQO5xCHVf15Y1VfsH25mxi27ii28%2B48Q6VzVbyjsRdsMy7%2FBExY58USkNacieSWa3m7DFgdqFNDqGJMBBq7K%2FXvwruLm0rAaXFPbzGSMk7sHXmDN98s7DSFmO1ZmspUpaaQyB7wzoykB07fzNydF1YdWlfntebs%2F4MLjBepIG7kDCS2lvPrJmeJZ%2FCkh6OS4nyyR4bDQRF7xEgUoOdMe2pma2WCpwlMKKYn70GOqUBFgocsfxk2kgHH4qhqswUDumE1tMpEbSzrOyH7%2FhDODtt6ainYm%2FLt%2BLBy13Fp9IrUPpXZ8ZjApBurd6W2DTMTuOKDJkGJgqCEBBO2wLjW079iSHsDCTDAke8nsNRWfMdN%2BLLIiAnjHtFP7XkolMzY%2BapuKzqFtJ%2BUlbAwdahuBOHeZ1k%2FDKqBPM0TI74nKjf6JVLRBDAlRYA6NACtVaoN%2FxEwzq8&X-Amz-Signature=0e2af724b51cfd9adc78ce75d0d2bd544f5dc8a6cc598026a7fc9121af207884&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466533RNCSI%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T222016Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEH4aCXVzLXdlc3QtMiJHMEUCIDMOT1l1hQ6PC7cV0GVIeGZv5geUACQkt%2FzvjaMSyvEmAiEA7XR8KX862mrEa3RJfPV4zOelWSKjYWmtvAdbIdNYh5kqiAQIl%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDlRGALIlYWPnX5yTircA%2B2ZfpsQfqfseH872hClUAYrP7r55Z%2FhcobpNbLxAPvjt92NDCb%2B5MFJzlzoGVYzOhDmUhZZC81P3%2FpBGLvSyqYENUdH9nE52KT3ylseVLdpcmfL0GMxmZnpY9ZdSixCn3ULIc0m6M7X56QcszXTWGkaUsFv7dWgoA3WzH8ypk0euWbTO8d7K2C%2BqoxUXzSI6AiH2fNYgoH95lNo%2BkjaxtN5%2BFwORzgIpUbf6tMyke%2F0sGc%2FVijMFnhOZjsVrzwmCgou0pkoWiS22F9%2BUzEaetGq7aJ1f%2BS3gOUkRZRAu%2BDsBDBSRy2s2E7zHNazsrQxYP%2BzRsnQpYWgdSGsETbPXwdZVrRXaQU%2By78EfntdY3y6u45xL120MK3v3%2Ba47fV%2BUz1WMHAPipIgYh4oYgHjvFBg7oJyv6jbRixdwSbCELbrq%2FZi2kSO2GagoMwSs8QfSQlw8d3dGjxMXdjL%2FImcBPaWXRrtXH0sLdscEpKNGjiv0Oey1qEfY%2Futto30p6kSHn3aPyubEN0Ll4RTcaTKbJHCipwBnVAJi%2BTY4V0oZ0Xd3C2D8xNQtO9rg%2F63yL1FyQpXTg0aWhS1HfYv7k3QNaNrzS7Lxmi6Phd9TzF%2BSGt7zSv4Xc1ARnBELaLxMOKYn70GOqUBqbyNqUUM%2B86iPyDWZ%2BL8gEtAoMBM%2FYhUbHVSOxYIoNAb6uSXvyyw1eMvJk330F8l3T3bnLwqH%2FcDh11U%2BJF9MOsTNLJhBEhlhPbRvjdpusKomNCcEIjzsbfJn3hhEqMfhaMjYIYBb6gJLl4rNW%2F2gmqmyGfyfSmffHefiQTdaeBeDU3o1sXR684szxOdUqkUcuVbulIHNkZtaQ4%2Bg88f8QLQ%2FpWy&X-Amz-Signature=e6decb145c8b0f3006218e7e180bb66f3e35d5b6adef35d58e653f29ba3c4f9d&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662UNPAYVP%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T222016Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEH4aCXVzLXdlc3QtMiJHMEUCIQDung9%2FbzWGpb6GEvZgg7KobSrMz1ebSvZIFTg%2FMQBiVAIgA525gSB%2F%2Br5wKZ%2FB6OkBBc0uIDi7nHWpdhSZV5F8MNwqiAQIl%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDDvie96rVCtkqiBVircAwA%2FMt7lO4AoycJO%2BzlGx9R2j69tS1CHUSYgjyxYQuvtdb5FYXyTbqciZJV8RpFIJ7x1u0BcoLJtMshgpaDDD4oeIYBg9hOzWb6A7eXpQ8Efi8z76RPdyEsYVZrtUkxOP979Eip%2F8wTribX7TuilBT7HK6EFM8D5qTWlt1gll%2FwmbtQfJznxo0FtaBGGTxCZO37TZBPOpHwFRE%2FD7tum4FJP%2FcJA38tcTQB4fg9PLIzebuB4xT%2BSrvcgYh5ZLDfvYCYh2INhMlxwQgqyMsEOy3NZ8E06GIZrTPoc9GNmIpItxEeqaDcBRiZjaiJGqGoDaCXO1KcOVJIacr8Aqb9MWDwWgPpj%2BoZoLXEbgXgQOzoYOAelJ%2FKfbN33znPFjb%2FM5xx63DyL%2B%2FfvJh9mBuUfhsrTozDov2w%2BkLIhS7q6knZlW%2Bh6O5nRsA%2B1ROMi9uUx5LyIx%2BuT3xBSEwoO33q8ZdQfPF0FatE4te9GmfMUBFVsCfA0p1Kn68KA2hCi9lXJ7EM%2FawDpw8XSJqtluDbqGbZ3bJ6k7hBWR%2FPn77YiayTs6sr002uXCHUNea3MR8zzBt8MW8q5PSKw3T5ytaFEjO6kt%2BKtNroLWKjI2G9wLwRpKIGD3tA2moY4FizWMOeYn70GOqUByH9RmqgB36ue22ou7%2FHKXoA%2FX9u0gW0EUL7t5oD%2FvZOejw72y84dV8RYTF3u9ZbMh80s13aFGNTzdMdOOoOss%2F3D8yvQrrg85Cb%2FRCYJk9rUkk88efiSE%2BXVQxqrsyB%2FujxKjZyM9yX2PNDDp3QOxT%2FIn4P0%2FyvzdhtcNo2p9v0mVzPNqixke%2FP5tOWw5hvbrVMWh4rT26LcMUbJaxDPUx7ZjqNa&X-Amz-Signature=4670bb09871a35906704a3c3e3ffa78e675d4d61503ae36d70b63e0c0277d01d&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663LVYNE7F%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T222015Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEH4aCXVzLXdlc3QtMiJHMEUCIEmV2Suc5Nt02IK3%2BnaRj8bJE8O2KLFw3q5VUtVg0p0RAiEA0pGo0q62U%2FN1o%2FcTOpFjQ9rEeRJvKdO5Hie7JHhJ0EsqiAQIl%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMBugWpKRvcCYRDYpCrcA7B4jpMWzi9KlB06CPXSvkcXoSImEK55QFaeVP9w10rTIWPRlgDQg4QatTFmG5yUHQDJI37W%2BKkf0O6BNTiUepzVMDc0HksLs5eEimHNfasc0nxZ95fMG2W%2FseJKeiMmYrs12BLEWSxyP1wJazFxQuDp0RURLWUkggPN47sPF5EHAZFamuN%2FxdVW8aBniNPW5bJjaoQ7ncUW7zrfWdxVe8fTW1hrjUrMF2NfGzffYizOQQlb6uz8kEtjUz3z%2FDkGKQta1aDwTiffuw7MDBXUAOqcySkYlfXI%2F9uVO7gW2G5TUa4e1QdvJoJvMIXbGZcxR8eGo6siAoLvSJrz1V6uc53CutOuUG3tclahdf1nxr6bBNk1a2k%2Fz2ws0ufspoqbK6lNfUjFN4k8%2FifK3usyH6fWLVq43cvQO5xCHVf15Y1VfsH25mxi27ii28%2B48Q6VzVbyjsRdsMy7%2FBExY58USkNacieSWa3m7DFgdqFNDqGJMBBq7K%2FXvwruLm0rAaXFPbzGSMk7sHXmDN98s7DSFmO1ZmspUpaaQyB7wzoykB07fzNydF1YdWlfntebs%2F4MLjBepIG7kDCS2lvPrJmeJZ%2FCkh6OS4nyyR4bDQRF7xEgUoOdMe2pma2WCpwlMKKYn70GOqUBFgocsfxk2kgHH4qhqswUDumE1tMpEbSzrOyH7%2FhDODtt6ainYm%2FLt%2BLBy13Fp9IrUPpXZ8ZjApBurd6W2DTMTuOKDJkGJgqCEBBO2wLjW079iSHsDCTDAke8nsNRWfMdN%2BLLIiAnjHtFP7XkolMzY%2BapuKzqFtJ%2BUlbAwdahuBOHeZ1k%2FDKqBPM0TI74nKjf6JVLRBDAlRYA6NACtVaoN%2FxEwzq8&X-Amz-Signature=17fc203ca53652560d36f42ba9ef7682ad44313f6b4b519638171c4f81c14ca5&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663LVYNE7F%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T222015Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEH4aCXVzLXdlc3QtMiJHMEUCIEmV2Suc5Nt02IK3%2BnaRj8bJE8O2KLFw3q5VUtVg0p0RAiEA0pGo0q62U%2FN1o%2FcTOpFjQ9rEeRJvKdO5Hie7JHhJ0EsqiAQIl%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMBugWpKRvcCYRDYpCrcA7B4jpMWzi9KlB06CPXSvkcXoSImEK55QFaeVP9w10rTIWPRlgDQg4QatTFmG5yUHQDJI37W%2BKkf0O6BNTiUepzVMDc0HksLs5eEimHNfasc0nxZ95fMG2W%2FseJKeiMmYrs12BLEWSxyP1wJazFxQuDp0RURLWUkggPN47sPF5EHAZFamuN%2FxdVW8aBniNPW5bJjaoQ7ncUW7zrfWdxVe8fTW1hrjUrMF2NfGzffYizOQQlb6uz8kEtjUz3z%2FDkGKQta1aDwTiffuw7MDBXUAOqcySkYlfXI%2F9uVO7gW2G5TUa4e1QdvJoJvMIXbGZcxR8eGo6siAoLvSJrz1V6uc53CutOuUG3tclahdf1nxr6bBNk1a2k%2Fz2ws0ufspoqbK6lNfUjFN4k8%2FifK3usyH6fWLVq43cvQO5xCHVf15Y1VfsH25mxi27ii28%2B48Q6VzVbyjsRdsMy7%2FBExY58USkNacieSWa3m7DFgdqFNDqGJMBBq7K%2FXvwruLm0rAaXFPbzGSMk7sHXmDN98s7DSFmO1ZmspUpaaQyB7wzoykB07fzNydF1YdWlfntebs%2F4MLjBepIG7kDCS2lvPrJmeJZ%2FCkh6OS4nyyR4bDQRF7xEgUoOdMe2pma2WCpwlMKKYn70GOqUBFgocsfxk2kgHH4qhqswUDumE1tMpEbSzrOyH7%2FhDODtt6ainYm%2FLt%2BLBy13Fp9IrUPpXZ8ZjApBurd6W2DTMTuOKDJkGJgqCEBBO2wLjW079iSHsDCTDAke8nsNRWfMdN%2BLLIiAnjHtFP7XkolMzY%2BapuKzqFtJ%2BUlbAwdahuBOHeZ1k%2FDKqBPM0TI74nKjf6JVLRBDAlRYA6NACtVaoN%2FxEwzq8&X-Amz-Signature=73517257c8aabd660fa1f0ed79cf5ae17fb13ccc9318bc16dda829c95f93828e&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663LVYNE7F%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T222015Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEH4aCXVzLXdlc3QtMiJHMEUCIEmV2Suc5Nt02IK3%2BnaRj8bJE8O2KLFw3q5VUtVg0p0RAiEA0pGo0q62U%2FN1o%2FcTOpFjQ9rEeRJvKdO5Hie7JHhJ0EsqiAQIl%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMBugWpKRvcCYRDYpCrcA7B4jpMWzi9KlB06CPXSvkcXoSImEK55QFaeVP9w10rTIWPRlgDQg4QatTFmG5yUHQDJI37W%2BKkf0O6BNTiUepzVMDc0HksLs5eEimHNfasc0nxZ95fMG2W%2FseJKeiMmYrs12BLEWSxyP1wJazFxQuDp0RURLWUkggPN47sPF5EHAZFamuN%2FxdVW8aBniNPW5bJjaoQ7ncUW7zrfWdxVe8fTW1hrjUrMF2NfGzffYizOQQlb6uz8kEtjUz3z%2FDkGKQta1aDwTiffuw7MDBXUAOqcySkYlfXI%2F9uVO7gW2G5TUa4e1QdvJoJvMIXbGZcxR8eGo6siAoLvSJrz1V6uc53CutOuUG3tclahdf1nxr6bBNk1a2k%2Fz2ws0ufspoqbK6lNfUjFN4k8%2FifK3usyH6fWLVq43cvQO5xCHVf15Y1VfsH25mxi27ii28%2B48Q6VzVbyjsRdsMy7%2FBExY58USkNacieSWa3m7DFgdqFNDqGJMBBq7K%2FXvwruLm0rAaXFPbzGSMk7sHXmDN98s7DSFmO1ZmspUpaaQyB7wzoykB07fzNydF1YdWlfntebs%2F4MLjBepIG7kDCS2lvPrJmeJZ%2FCkh6OS4nyyR4bDQRF7xEgUoOdMe2pma2WCpwlMKKYn70GOqUBFgocsfxk2kgHH4qhqswUDumE1tMpEbSzrOyH7%2FhDODtt6ainYm%2FLt%2BLBy13Fp9IrUPpXZ8ZjApBurd6W2DTMTuOKDJkGJgqCEBBO2wLjW079iSHsDCTDAke8nsNRWfMdN%2BLLIiAnjHtFP7XkolMzY%2BapuKzqFtJ%2BUlbAwdahuBOHeZ1k%2FDKqBPM0TI74nKjf6JVLRBDAlRYA6NACtVaoN%2FxEwzq8&X-Amz-Signature=00de894372e5a76bb31f17fc372f69af9bd5c99fa9fbcc1aa2cc212eb6aa2b69&X-Amz-SignedHeaders=host&x-id=GetObject)


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

