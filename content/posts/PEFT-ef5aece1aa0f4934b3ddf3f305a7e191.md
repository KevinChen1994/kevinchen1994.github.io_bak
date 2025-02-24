---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466YY6CDL3H%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250224T063447Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEO7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIEk3he1k9qKBcHgC1cw\
  7mv3JLphFw7S2RCpl5hV48u5cAiEA%2BFQQMt6f%2BKY8CuCk9HPHR6zLN1fr4tzE%2FEGpJiToiS\
  kq%2FwMIJxAAGgw2Mzc0MjMxODM4MDUiDDAA%2B6GEVM9frU6E6ircA3HtEFur8yDSXfN2o%2BQi2\
  Dontx1dPobvR6L1D0AJ%2FoJwVchMveyGYqNPKNjGZet1ScbnW5sGp6B1g1%2FpZPA8ywHPu5%2Bx\
  GDlDz80TfaYXD4va%2BeX%2BNRb3UBS%2BIHkPg8RdyKxT9lMw6AEH9XcweIj78inqZBP%2BUmXMq\
  8T9%2BtbGc1G8BJk8YNXb3FqXvnHj8BjZ1GTz1mj3SqMww9l%2Bfi%2Bzwp2uEOMlOtLIfMXguPQW\
  7x4AUWCEo9Pd%2Fupt9s7zmH8y2nfP75ldw7Cle%2F8ExR%2FSZvSSG4rh9dfrclUL2RTwL8nN5PE\
  w1YVTZJHXuuBtLEs5sy%2BSYlgImpK8Mu0Jz3Fbjbe8qiS4q%2FPOnNqkskF3ftdhT5hVrIINfyvA\
  asCFHSDy04n5eXnLilS%2BHG9lt%2BOLUpk7M1a8Ig2F3MORnPKv8tXLMapQ1bDZdE0ez8M3YmsJg\
  hf0CJVvHZETUqrUFYMqlln%2FsN6tdROLdUyRg51xLfLpQ3Ej2FLR0jlzY9UgW9QS6X1Q5cc6Phi%\
  2B4tYGUXDMGJKa4A%2FNBbC1rtekPb9bgvRgxZnNHf4Q6KFjV5aKlRQYJh7s58Yfx%2FUsfuabkf9\
  R%2F%2FSRVcWk1dPFQD3gSgxa7zJG8Fef9ybUB9TbcSU%2BML%2BU8L0GOqUBcViHCUb4w4VNRAhK\
  IK%2Bv61BrB9%2BbBPnkHhu18aWU0iSlo1VoJ1FDknv73te7TPDtdBYRqFz9XmNYn1zeThu%2FG4e\
  anahfpsn3Iwehq0zW1aGG0rfnUPvPbplTNhRWPQ6wtPbZfe3qMSzgK6kcE81AJiEBAQ2uyyLkQsOk\
  iQx605UjyhEmfNx0qKE053VRqumFM0T9jF%2BBnTse5OrbtVooETMqR8OA&X-Amz-Signature=d2\
  d3438095bbaa54d90b8849b665603ff43faf60b37a5655970c7fb43753f0c1&X-Amz-SignedHe\
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
        redential=ASIAZI2LB466WJLLNM2F%2F20250224%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250224T063321Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEO7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIG%2B0g35P30JO%2FYZ1Ewy%2FfJUMXcrdDOcaL4D9aPklq9GjAiEAtEE96Xavnm8TXVsD\
        X77MZiboUDZdSHujk%2F2S%2FK1wl0Aq%2FwMIJxAAGgw2Mzc0MjMxODM4MDUiDFza9gGFG\
        7ptSMOqEyrcA6ZubneyVFAnvfIAmKVfrf9d%2FwmIY%2B%2B%2BsDOApdHQWQsSE7dVavXJ\
        p2Uk8AuKl55U2LVm%2Fyb6C5sF3N6%2FrK9qaY74wuF9jKCxL3VTugCph4qMT5K2maf2sGL\
        OeDxNJDXxKDjuaC7iKh%2FR9OSDSaVnzFfHkfP2h25McbCStc%2BFtD1Ncj9BiDQBgxPvd6\
        PIWnSLknNqiweXEkaKNwXsNk28KkEBbuUwUpdDwSS8ewoAEMXqep%2BxWeCkkKklsbWWQei\
        g2vUwcc60dhpiVeR2ujO6kHSE4zsU%2FOI8XcBxuHOPUL6bSFrMnyIRhq5z%2BXuaW4aidK\
        RB%2B7mNIqcdOFqn%2BItSiQS%2BxfXA8bbZ8Zy1dzAB4qxJnvAN9tCZRNSc91iZ8c7ttOA\
        qGeGJ5Y4n8jVOksYKnK3oEGE7ikcXKiGaVxDk3U4lmMHVF8eKZkWeB5rsEHdorSRqH2sbE1\
        ALUENxxiVBE4RKHZb8avgSi8n0lYXpy8fzGXVdOqScmCiSZfMo%2BfvsbZVBKDHVGZaEQsy\
        igQgMbJzUUaZ2X0mhUTzoad4mVygpKLqbRBvLyq942PyRpnhx6DBtvoU%2FMO995cXP5Dkm\
        BEWPJUprj5e%2Ftnkbsn2PPpzRbQKYjfRB4XZkMdAoMK2U8L0GOqUBZ7knm16JpbkxkwT5G\
        TQwfySli5HV7hF4WpJRKSzJPtuGl8xPs5j8oR%2BoICTM9NGcGMVr3qA4c63IaB0I10wHs0\
        oeqLZg2%2B%2Bd7kd4QaY4%2ByLAOLREs917wXsNxSaqCTz4dv8ixIAna9EBm6rrpsrIP2G\
        FXsxMYhJZXbChfzmhQPrY0xXt22803g6XUp9BUPVjGU%2F%2BXAIeo0c5oX0%2FvChFsqtU\
        4sff&X-Amz-Signature=73c2916b92127e0925934e33cad5de77d4bc7569db978ab46e\
        83b436813cf5b2&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-24T07:33:21.405Z"
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
UPDATE_TIME: "2025-02-24T06:34:57.354Z"
EXPIRY_TIME: "2025-02-24T07:34:44.023Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667GD22A46%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T063445Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEO7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCDBzqF%2FIt6Dl%2Bi3qNg%2Fc2xwUyGhpkBMDSwazywXvVIrAIgH%2FuLwgvPJCKH3xIYaPo8zjBwAfGkVlPPiuhTfMLwztkq%2FwMIJxAAGgw2Mzc0MjMxODM4MDUiDNcFS2RybZVg1zTSFSrcA67%2BYUXkc3USE6xkPukMPAJLZEw0Nz1GRxSgyHwdAW1MuW7TzAlaKaKzzIl%2BruqYOnZdl2ikVh%2FWIaHOcFv2cnSi99avRltPOM3OfENHlM0LsbDGQzoPKK101oqAHubWF3XpE5JmY9kpoSXdTYuowX1IerLGaTOETs74NPbgJABooikTGD%2F09FSV%2Bd%2F0zRs%2FD%2FqAm7BauPHpYeNppv2BGRVQhck6KnSO%2BHUhgNX1ZJBbyBNR9Vuoe8qr3nVqPxUlCN%2FJe7jeog%2BkSKT%2FLPZYDy9lZKcOtfqMyXMIgUO6LQiBYRBZonuoY%2BDJaIXsMpjJvC%2BElen5b68H4O0t8z6v6qBykQz5e94Pgfj6S97AG5wgtTu7FAIsnTk%2FgnyS8nemw3ndTeu1aq%2FfhAlZfWIsSJO0UEJ1ibBxk4k3nR6nw843wj%2B9OtSkf942xiS6cDfOJOP5Dww1n902fuUgaoSG9V1fU71a0Onr9yzlR17E3nhI8nCPbaownvM4o2dReN8eshvZdmBtjd5PWAnsntUGWb3lI%2B62IoiUU2rA4KWNRdrMwA9En2L1a2x3QtFte4tChErqngM%2FnHtWIMnBwSnpWg1%2BfOiD0lKJoEuEd%2BzCKFrxmvPCYgEs04o%2FMExWMKOU8L0GOqUBkMuRocFHK3wX4lIka9BBTDr6ZHTUBel6Zf0OIW7r%2FfX1U%2BVXbnHLfBjGMafcp1FTgE4ySKdv8FOYZLMkSdl2eMkYVl5vCbn9IBu88Fbbce%2BsDCDpECwreEM0QBm0qk9AV0%2BkAp%2F28xwHER9lM5hYSMsdyeJe3dT%2BUAFMnEDGV4lmFrSXPz2CmcNy6KDrTVNfmsMgdzyn56gi4MZ5OvpZyHhBVanT&X-Amz-Signature=3a135cfa1cf86d66e99d756876dc16398893fb361ee716bc9dc9730710de5771&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667GD22A46%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T063445Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEO7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCDBzqF%2FIt6Dl%2Bi3qNg%2Fc2xwUyGhpkBMDSwazywXvVIrAIgH%2FuLwgvPJCKH3xIYaPo8zjBwAfGkVlPPiuhTfMLwztkq%2FwMIJxAAGgw2Mzc0MjMxODM4MDUiDNcFS2RybZVg1zTSFSrcA67%2BYUXkc3USE6xkPukMPAJLZEw0Nz1GRxSgyHwdAW1MuW7TzAlaKaKzzIl%2BruqYOnZdl2ikVh%2FWIaHOcFv2cnSi99avRltPOM3OfENHlM0LsbDGQzoPKK101oqAHubWF3XpE5JmY9kpoSXdTYuowX1IerLGaTOETs74NPbgJABooikTGD%2F09FSV%2Bd%2F0zRs%2FD%2FqAm7BauPHpYeNppv2BGRVQhck6KnSO%2BHUhgNX1ZJBbyBNR9Vuoe8qr3nVqPxUlCN%2FJe7jeog%2BkSKT%2FLPZYDy9lZKcOtfqMyXMIgUO6LQiBYRBZonuoY%2BDJaIXsMpjJvC%2BElen5b68H4O0t8z6v6qBykQz5e94Pgfj6S97AG5wgtTu7FAIsnTk%2FgnyS8nemw3ndTeu1aq%2FfhAlZfWIsSJO0UEJ1ibBxk4k3nR6nw843wj%2B9OtSkf942xiS6cDfOJOP5Dww1n902fuUgaoSG9V1fU71a0Onr9yzlR17E3nhI8nCPbaownvM4o2dReN8eshvZdmBtjd5PWAnsntUGWb3lI%2B62IoiUU2rA4KWNRdrMwA9En2L1a2x3QtFte4tChErqngM%2FnHtWIMnBwSnpWg1%2BfOiD0lKJoEuEd%2BzCKFrxmvPCYgEs04o%2FMExWMKOU8L0GOqUBkMuRocFHK3wX4lIka9BBTDr6ZHTUBel6Zf0OIW7r%2FfX1U%2BVXbnHLfBjGMafcp1FTgE4ySKdv8FOYZLMkSdl2eMkYVl5vCbn9IBu88Fbbce%2BsDCDpECwreEM0QBm0qk9AV0%2BkAp%2F28xwHER9lM5hYSMsdyeJe3dT%2BUAFMnEDGV4lmFrSXPz2CmcNy6KDrTVNfmsMgdzyn56gi4MZ5OvpZyHhBVanT&X-Amz-Signature=9e7522c39b086eae608804501d67abc9bf0eeef5ab99a6117a75a791f7f7cb48&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667GD22A46%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T063445Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEO7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCDBzqF%2FIt6Dl%2Bi3qNg%2Fc2xwUyGhpkBMDSwazywXvVIrAIgH%2FuLwgvPJCKH3xIYaPo8zjBwAfGkVlPPiuhTfMLwztkq%2FwMIJxAAGgw2Mzc0MjMxODM4MDUiDNcFS2RybZVg1zTSFSrcA67%2BYUXkc3USE6xkPukMPAJLZEw0Nz1GRxSgyHwdAW1MuW7TzAlaKaKzzIl%2BruqYOnZdl2ikVh%2FWIaHOcFv2cnSi99avRltPOM3OfENHlM0LsbDGQzoPKK101oqAHubWF3XpE5JmY9kpoSXdTYuowX1IerLGaTOETs74NPbgJABooikTGD%2F09FSV%2Bd%2F0zRs%2FD%2FqAm7BauPHpYeNppv2BGRVQhck6KnSO%2BHUhgNX1ZJBbyBNR9Vuoe8qr3nVqPxUlCN%2FJe7jeog%2BkSKT%2FLPZYDy9lZKcOtfqMyXMIgUO6LQiBYRBZonuoY%2BDJaIXsMpjJvC%2BElen5b68H4O0t8z6v6qBykQz5e94Pgfj6S97AG5wgtTu7FAIsnTk%2FgnyS8nemw3ndTeu1aq%2FfhAlZfWIsSJO0UEJ1ibBxk4k3nR6nw843wj%2B9OtSkf942xiS6cDfOJOP5Dww1n902fuUgaoSG9V1fU71a0Onr9yzlR17E3nhI8nCPbaownvM4o2dReN8eshvZdmBtjd5PWAnsntUGWb3lI%2B62IoiUU2rA4KWNRdrMwA9En2L1a2x3QtFte4tChErqngM%2FnHtWIMnBwSnpWg1%2BfOiD0lKJoEuEd%2BzCKFrxmvPCYgEs04o%2FMExWMKOU8L0GOqUBkMuRocFHK3wX4lIka9BBTDr6ZHTUBel6Zf0OIW7r%2FfX1U%2BVXbnHLfBjGMafcp1FTgE4ySKdv8FOYZLMkSdl2eMkYVl5vCbn9IBu88Fbbce%2BsDCDpECwreEM0QBm0qk9AV0%2BkAp%2F28xwHER9lM5hYSMsdyeJe3dT%2BUAFMnEDGV4lmFrSXPz2CmcNy6KDrTVNfmsMgdzyn56gi4MZ5OvpZyHhBVanT&X-Amz-Signature=e6b551b9758da4d4a5c60f501106290c5ff4e9ea559435091bc33b3052cb672b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667GD22A46%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T063445Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEO7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCDBzqF%2FIt6Dl%2Bi3qNg%2Fc2xwUyGhpkBMDSwazywXvVIrAIgH%2FuLwgvPJCKH3xIYaPo8zjBwAfGkVlPPiuhTfMLwztkq%2FwMIJxAAGgw2Mzc0MjMxODM4MDUiDNcFS2RybZVg1zTSFSrcA67%2BYUXkc3USE6xkPukMPAJLZEw0Nz1GRxSgyHwdAW1MuW7TzAlaKaKzzIl%2BruqYOnZdl2ikVh%2FWIaHOcFv2cnSi99avRltPOM3OfENHlM0LsbDGQzoPKK101oqAHubWF3XpE5JmY9kpoSXdTYuowX1IerLGaTOETs74NPbgJABooikTGD%2F09FSV%2Bd%2F0zRs%2FD%2FqAm7BauPHpYeNppv2BGRVQhck6KnSO%2BHUhgNX1ZJBbyBNR9Vuoe8qr3nVqPxUlCN%2FJe7jeog%2BkSKT%2FLPZYDy9lZKcOtfqMyXMIgUO6LQiBYRBZonuoY%2BDJaIXsMpjJvC%2BElen5b68H4O0t8z6v6qBykQz5e94Pgfj6S97AG5wgtTu7FAIsnTk%2FgnyS8nemw3ndTeu1aq%2FfhAlZfWIsSJO0UEJ1ibBxk4k3nR6nw843wj%2B9OtSkf942xiS6cDfOJOP5Dww1n902fuUgaoSG9V1fU71a0Onr9yzlR17E3nhI8nCPbaownvM4o2dReN8eshvZdmBtjd5PWAnsntUGWb3lI%2B62IoiUU2rA4KWNRdrMwA9En2L1a2x3QtFte4tChErqngM%2FnHtWIMnBwSnpWg1%2BfOiD0lKJoEuEd%2BzCKFrxmvPCYgEs04o%2FMExWMKOU8L0GOqUBkMuRocFHK3wX4lIka9BBTDr6ZHTUBel6Zf0OIW7r%2FfX1U%2BVXbnHLfBjGMafcp1FTgE4ySKdv8FOYZLMkSdl2eMkYVl5vCbn9IBu88Fbbce%2BsDCDpECwreEM0QBm0qk9AV0%2BkAp%2F28xwHER9lM5hYSMsdyeJe3dT%2BUAFMnEDGV4lmFrSXPz2CmcNy6KDrTVNfmsMgdzyn56gi4MZ5OvpZyHhBVanT&X-Amz-Signature=31131a1d3689606fc6b089a41a0c826b7f34da10b8c673160a4fb1324ae1ee7c&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667GD22A46%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T063445Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEO7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCDBzqF%2FIt6Dl%2Bi3qNg%2Fc2xwUyGhpkBMDSwazywXvVIrAIgH%2FuLwgvPJCKH3xIYaPo8zjBwAfGkVlPPiuhTfMLwztkq%2FwMIJxAAGgw2Mzc0MjMxODM4MDUiDNcFS2RybZVg1zTSFSrcA67%2BYUXkc3USE6xkPukMPAJLZEw0Nz1GRxSgyHwdAW1MuW7TzAlaKaKzzIl%2BruqYOnZdl2ikVh%2FWIaHOcFv2cnSi99avRltPOM3OfENHlM0LsbDGQzoPKK101oqAHubWF3XpE5JmY9kpoSXdTYuowX1IerLGaTOETs74NPbgJABooikTGD%2F09FSV%2Bd%2F0zRs%2FD%2FqAm7BauPHpYeNppv2BGRVQhck6KnSO%2BHUhgNX1ZJBbyBNR9Vuoe8qr3nVqPxUlCN%2FJe7jeog%2BkSKT%2FLPZYDy9lZKcOtfqMyXMIgUO6LQiBYRBZonuoY%2BDJaIXsMpjJvC%2BElen5b68H4O0t8z6v6qBykQz5e94Pgfj6S97AG5wgtTu7FAIsnTk%2FgnyS8nemw3ndTeu1aq%2FfhAlZfWIsSJO0UEJ1ibBxk4k3nR6nw843wj%2B9OtSkf942xiS6cDfOJOP5Dww1n902fuUgaoSG9V1fU71a0Onr9yzlR17E3nhI8nCPbaownvM4o2dReN8eshvZdmBtjd5PWAnsntUGWb3lI%2B62IoiUU2rA4KWNRdrMwA9En2L1a2x3QtFte4tChErqngM%2FnHtWIMnBwSnpWg1%2BfOiD0lKJoEuEd%2BzCKFrxmvPCYgEs04o%2FMExWMKOU8L0GOqUBkMuRocFHK3wX4lIka9BBTDr6ZHTUBel6Zf0OIW7r%2FfX1U%2BVXbnHLfBjGMafcp1FTgE4ySKdv8FOYZLMkSdl2eMkYVl5vCbn9IBu88Fbbce%2BsDCDpECwreEM0QBm0qk9AV0%2BkAp%2F28xwHER9lM5hYSMsdyeJe3dT%2BUAFMnEDGV4lmFrSXPz2CmcNy6KDrTVNfmsMgdzyn56gi4MZ5OvpZyHhBVanT&X-Amz-Signature=96152e5aca7f00079dba10b44d9b7ae98b095356375f71f23875e04b5f880afb&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663XFYDHYW%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T063446Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEO7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIGX3uojdtua6O9zYVOLTlQtbIfD7KtUzoUaEip%2BBU5HpAiAs9x3zFXJFGm5YcfhicH%2BFuAg0WOy0oEeiWeAA5fLW2yr%2FAwgnEAAaDDYzNzQyMzE4MzgwNSIMX5dLJyxSSBpzcFqjKtwDO%2Bb7GF8%2FUakkpRHETZ9OoCA61bVcl%2BhwtNhW04bNEasWviB9AUSp%2BeeqS68tHCiw137v%2FwsEzyH8ka4MLBKQzH1vuq%2F1p2dtqStqT91Ev3V01SXoICXQI%2Few29VTbnrUT02z877BTzOGIacka5MNfQo4O0CzWje5AEm%2FbZC30ioI7l3BpRakSE66DVcIMgvf7opCk%2FBG15%2FhImY%2FlPV8vy3SP5Kw2tW9YWKZuaguWNT4AqHb96CCCf3Ghvyv%2BX7c29P6HkxwPHAmJ8OKQ%2BXYNIOu0ZkxvyRDtD5%2BJ506AKh12zD2bU4TSk7iEfN0y3h%2BI4xvUJvbQfhbUO9hZjkaH3C7pkzXzqOawl%2FCM0warq1O9L9O4kRCoOmVtznHSvwifEcBZ%2FHvq594Blo9MgJL7XtbsuSBCWGJmMVf%2B9XBPBF1w2tRmnbZAZjiiGOEWCSKlhgdtp7KYBg9ggDBEJPdRt2LI%2FyYfVjnUnZamIjIaJLCadFsUWOeqTm4dGnxKneTciRqDjmsVyHX%2BFW%2FYSGxsI7O6u5mNWIiqqOcCE0DhALGiu35UStrv5ccvPwddIbjvf%2FdIJCNypGlfXlh5IKiQjiwmfHBP9xY7HPItWstk3YeKmJIrvncu8z3Bhww4pTwvQY6pgFk2OPgmEAtU%2BGfup%2FYTbK3IAeLUgH10dVMFb05aP0a8S1YZlgBd54LFQw7B4CiJx03ZICDQA3K8eNSFXNXaTTF%2B5C6hTt0ZbUca2f9V53g6GaXDerR4wOplTbv64zv%2BLtMpoS41wVgMdnaJa477fJmtCEC3v6m6gGuzTFpR3lKdqOgG0nAganmAK1KoZyO8hh3yzEnykfZVCfOLsG3HypQLN%2BH7rtg&X-Amz-Signature=17bffb8b4d29c6b6c712cdc31bac674fcd17c14aa537496000fb6d815cd7e85d&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46653ERGC4T%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T063447Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEO7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIHioCuBFSpRnjNLS0POr4ZqY6pBbFlAgP4QenDd7GtYEAiANbY6M07zC68zmtDCV8WKWFSem%2FtApkhAz00ikIEKcZir%2FAwgnEAAaDDYzNzQyMzE4MzgwNSIMZ0%2BQ8OfTBolGd3XZKtwDMzYvUZh1Wm5tlIu8FuZqoRp72YdUCMzuAr9%2BfW6Oe6MR2Yca1c3my1qGVQWxyQztWXSgZVzfhFsYKdCM%2F%2BuVE5nveou0%2B3TjH0SCkMhvK0FQzkQUeyxey%2B5GaR2gyB6uO8jber1ptN6piF4BskNfzntLyisZwvRbEH4B5bpilZNepwoTXKyu%2FK1Qm6339DCLsbNMeVlpStNuqiiNHd54wnU%2BH2gVs%2Bni6N4Fjh1uWyKE0blG%2B0yvWaSDCNDQwB0t8Jo%2FZipLwNBk3eof5f4wWO%2F8JB44F%2BMe9HyNmiZt6acU4OnxJlO7dXZr8C%2BKMwXgSDbSm7QfwaC99L0BdDTmFRVM74vtkg%2BSueALEpJ3%2Bqp%2FRMUp0oNBgsY0kyTfW659WBcyAJBlXXqpEAsACgh2i6cP%2BiK2%2F2Wg2Xc0PCQrXpBaDSa3fWTc6N%2F3TBVNvqa5VkLTFtZdsyeVwBWCOkjiqf%2Fd7ZEvecmqcNfNjGRAq2vr8PfY%2BjlEyVct9ZBOxHxezLhtyLbgodpzSkht2uU2Iq5ElkJbRvYblVFarV%2FTecdq1e48Gbi1%2FPA1I9XcMklq9tV0w7E8AM5MJlP%2FWxbzCazHPfadO506Pp1OS9E%2BDiofDNgPjgG4AzKhjcMwrpTwvQY6pgFPGU6OHJUK%2Fyc8VZyI0cTu3d1zLd1D3RexUoei8Vs0NrYHPR%2B%2B1dMDbaE%2FCq7RooIQpbzHPInX3u6vJ9rI0hh0J0B3x2HImxXmSjUlrak53xCffhSdy%2FK4xKQwKgRpTfrkV9dhl8Wn83YBDaTrqy8y9VWuYH%2FPCJbz4q6nGUbsHYhb5CC9uatHrR1yzwlEb6oH6BeBXr5Wwe6etDLClCQtYQu8OPY6&X-Amz-Signature=3c40925f19f58589ce3d878390ad612c26fcf9a29d046584e87112d477f22c6f&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667GD22A46%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T063445Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEO7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCDBzqF%2FIt6Dl%2Bi3qNg%2Fc2xwUyGhpkBMDSwazywXvVIrAIgH%2FuLwgvPJCKH3xIYaPo8zjBwAfGkVlPPiuhTfMLwztkq%2FwMIJxAAGgw2Mzc0MjMxODM4MDUiDNcFS2RybZVg1zTSFSrcA67%2BYUXkc3USE6xkPukMPAJLZEw0Nz1GRxSgyHwdAW1MuW7TzAlaKaKzzIl%2BruqYOnZdl2ikVh%2FWIaHOcFv2cnSi99avRltPOM3OfENHlM0LsbDGQzoPKK101oqAHubWF3XpE5JmY9kpoSXdTYuowX1IerLGaTOETs74NPbgJABooikTGD%2F09FSV%2Bd%2F0zRs%2FD%2FqAm7BauPHpYeNppv2BGRVQhck6KnSO%2BHUhgNX1ZJBbyBNR9Vuoe8qr3nVqPxUlCN%2FJe7jeog%2BkSKT%2FLPZYDy9lZKcOtfqMyXMIgUO6LQiBYRBZonuoY%2BDJaIXsMpjJvC%2BElen5b68H4O0t8z6v6qBykQz5e94Pgfj6S97AG5wgtTu7FAIsnTk%2FgnyS8nemw3ndTeu1aq%2FfhAlZfWIsSJO0UEJ1ibBxk4k3nR6nw843wj%2B9OtSkf942xiS6cDfOJOP5Dww1n902fuUgaoSG9V1fU71a0Onr9yzlR17E3nhI8nCPbaownvM4o2dReN8eshvZdmBtjd5PWAnsntUGWb3lI%2B62IoiUU2rA4KWNRdrMwA9En2L1a2x3QtFte4tChErqngM%2FnHtWIMnBwSnpWg1%2BfOiD0lKJoEuEd%2BzCKFrxmvPCYgEs04o%2FMExWMKOU8L0GOqUBkMuRocFHK3wX4lIka9BBTDr6ZHTUBel6Zf0OIW7r%2FfX1U%2BVXbnHLfBjGMafcp1FTgE4ySKdv8FOYZLMkSdl2eMkYVl5vCbn9IBu88Fbbce%2BsDCDpECwreEM0QBm0qk9AV0%2BkAp%2F28xwHER9lM5hYSMsdyeJe3dT%2BUAFMnEDGV4lmFrSXPz2CmcNy6KDrTVNfmsMgdzyn56gi4MZ5OvpZyHhBVanT&X-Amz-Signature=bd4e3ae8eecfc59eb1cc43ae268f2f26acdbff98e5def304c8554fe6a7c41967&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667GD22A46%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T063445Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEO7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCDBzqF%2FIt6Dl%2Bi3qNg%2Fc2xwUyGhpkBMDSwazywXvVIrAIgH%2FuLwgvPJCKH3xIYaPo8zjBwAfGkVlPPiuhTfMLwztkq%2FwMIJxAAGgw2Mzc0MjMxODM4MDUiDNcFS2RybZVg1zTSFSrcA67%2BYUXkc3USE6xkPukMPAJLZEw0Nz1GRxSgyHwdAW1MuW7TzAlaKaKzzIl%2BruqYOnZdl2ikVh%2FWIaHOcFv2cnSi99avRltPOM3OfENHlM0LsbDGQzoPKK101oqAHubWF3XpE5JmY9kpoSXdTYuowX1IerLGaTOETs74NPbgJABooikTGD%2F09FSV%2Bd%2F0zRs%2FD%2FqAm7BauPHpYeNppv2BGRVQhck6KnSO%2BHUhgNX1ZJBbyBNR9Vuoe8qr3nVqPxUlCN%2FJe7jeog%2BkSKT%2FLPZYDy9lZKcOtfqMyXMIgUO6LQiBYRBZonuoY%2BDJaIXsMpjJvC%2BElen5b68H4O0t8z6v6qBykQz5e94Pgfj6S97AG5wgtTu7FAIsnTk%2FgnyS8nemw3ndTeu1aq%2FfhAlZfWIsSJO0UEJ1ibBxk4k3nR6nw843wj%2B9OtSkf942xiS6cDfOJOP5Dww1n902fuUgaoSG9V1fU71a0Onr9yzlR17E3nhI8nCPbaownvM4o2dReN8eshvZdmBtjd5PWAnsntUGWb3lI%2B62IoiUU2rA4KWNRdrMwA9En2L1a2x3QtFte4tChErqngM%2FnHtWIMnBwSnpWg1%2BfOiD0lKJoEuEd%2BzCKFrxmvPCYgEs04o%2FMExWMKOU8L0GOqUBkMuRocFHK3wX4lIka9BBTDr6ZHTUBel6Zf0OIW7r%2FfX1U%2BVXbnHLfBjGMafcp1FTgE4ySKdv8FOYZLMkSdl2eMkYVl5vCbn9IBu88Fbbce%2BsDCDpECwreEM0QBm0qk9AV0%2BkAp%2F28xwHER9lM5hYSMsdyeJe3dT%2BUAFMnEDGV4lmFrSXPz2CmcNy6KDrTVNfmsMgdzyn56gi4MZ5OvpZyHhBVanT&X-Amz-Signature=0022e367210e394136f774a865c242de81088b385c7050624d1fe719a14aa90f&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667GD22A46%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T063445Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEO7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCDBzqF%2FIt6Dl%2Bi3qNg%2Fc2xwUyGhpkBMDSwazywXvVIrAIgH%2FuLwgvPJCKH3xIYaPo8zjBwAfGkVlPPiuhTfMLwztkq%2FwMIJxAAGgw2Mzc0MjMxODM4MDUiDNcFS2RybZVg1zTSFSrcA67%2BYUXkc3USE6xkPukMPAJLZEw0Nz1GRxSgyHwdAW1MuW7TzAlaKaKzzIl%2BruqYOnZdl2ikVh%2FWIaHOcFv2cnSi99avRltPOM3OfENHlM0LsbDGQzoPKK101oqAHubWF3XpE5JmY9kpoSXdTYuowX1IerLGaTOETs74NPbgJABooikTGD%2F09FSV%2Bd%2F0zRs%2FD%2FqAm7BauPHpYeNppv2BGRVQhck6KnSO%2BHUhgNX1ZJBbyBNR9Vuoe8qr3nVqPxUlCN%2FJe7jeog%2BkSKT%2FLPZYDy9lZKcOtfqMyXMIgUO6LQiBYRBZonuoY%2BDJaIXsMpjJvC%2BElen5b68H4O0t8z6v6qBykQz5e94Pgfj6S97AG5wgtTu7FAIsnTk%2FgnyS8nemw3ndTeu1aq%2FfhAlZfWIsSJO0UEJ1ibBxk4k3nR6nw843wj%2B9OtSkf942xiS6cDfOJOP5Dww1n902fuUgaoSG9V1fU71a0Onr9yzlR17E3nhI8nCPbaownvM4o2dReN8eshvZdmBtjd5PWAnsntUGWb3lI%2B62IoiUU2rA4KWNRdrMwA9En2L1a2x3QtFte4tChErqngM%2FnHtWIMnBwSnpWg1%2BfOiD0lKJoEuEd%2BzCKFrxmvPCYgEs04o%2FMExWMKOU8L0GOqUBkMuRocFHK3wX4lIka9BBTDr6ZHTUBel6Zf0OIW7r%2FfX1U%2BVXbnHLfBjGMafcp1FTgE4ySKdv8FOYZLMkSdl2eMkYVl5vCbn9IBu88Fbbce%2BsDCDpECwreEM0QBm0qk9AV0%2BkAp%2F28xwHER9lM5hYSMsdyeJe3dT%2BUAFMnEDGV4lmFrSXPz2CmcNy6KDrTVNfmsMgdzyn56gi4MZ5OvpZyHhBVanT&X-Amz-Signature=24c025f5f3c3c23780e6556544acaf39f4f42bef939636a0b5b491f976f6e2cb&X-Amz-SignedHeaders=host&x-id=GetObject)


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

