---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466Q2II7L35%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250210T212214Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEK3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIBKC6heftvphXIV%2Fn\
  XZMGdv7eKIs1PwtH1s0Cu7puiwxAiA%2FKjXcQRe5mCACZwtZp%2BO87yJh%2FbI35wOK0XMTYxmo\
  kiqIBAjG%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMIUrmZnj8ZGy9J\
  z%2BwKtwDU3dQOniKYu0oPEmAsd0wyrllSHyr4mrZOPUC0%2BcbLTRIcv%2FojewZrQSQZr5gJhf6\
  xIA8SboNfOdfVptET1CfAxeR69lybJc2NyFCIFzKGqn%2FlN6sNF3OdLI%2FqR%2B0sN3HxH5TNj%\
  2Bbin6%2BkKYyeZY2myDONfJ0Dbz89cQ%2F32NuPSGL8cv4NxpK614eOX%2FNYA8v01YUUYkZP5qB\
  Oa0SQOIWpcTC7faVqJiSo%2FfbhhqhW2VM7hRz4bjMxUqr7nCRaA9J3Lfv2e7IR5aHl%2FWz5j1sD\
  Gl19a2Y1G5%2FLShBHYvIejaBs%2BRlN0qh0q%2FdWPEPfvwNhph9FIlylBIGKRkrSEnyj%2FQYgL\
  HAyyNzEdHhx96jy45iMpNvYvByTh4xIJv%2B4%2BxHsmMPtfrSn%2F4ETzN7Cnn3zLWr2f%2FKesn\
  9%2FGYdXpka0224BZiqO%2F%2FeliCrnRrWb2uWIDNthiWQNxCU6PmqnJhPXHNZ2qdrIo4TUvwyhx\
  lhnBkCLwZSxzoVCiLaZEBzb2MveZybHYcKIIz%2BTJQUSO30WSMIu3vOO0mmTW%2B3ZwNRaHrIwqh\
  4l7UItP8hOuePoSkGsjWpi0zDggd%2F1JQK7u0sdHr2KYkTQTXzSCIw1Scyv0Gi%2FOacn%2B0yAw\
  bYDo4wtc2pvQY6pgE7Qmz%2Ban0TDjkr9yXwC475nwvYZqvKfJjzS456mnnkHXdshEP4%2Fv%2BtX\
  INDD3vKkbvLrJ2e%2FphCNzI64F%2Fd4nqs3UBtGpcIg0usfOlvMzPkmwsJDrckbe7cGP%2F4GHsA\
  R1x8B3pC7iAZYC7dYAi7LA1%2F%2BBaZyk9LF3xMMDpaURSM8A%2BEOrjvPPEgeStSF9beT5AyzhK\
  HUSdmmn0tgM3asnQtU8Yw%2FmEZ&X-Amz-Signature=ff39fe1f093b5c7453c5b6cd0b60b55a2\
  23ceb44864e51400a726fdfc22deaa8&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466U5OWNEBY%2F20250210%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250210T212042Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEK3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIHj0fnMT3WvD3rqKwkOydIVQequrgipCjFunAAPZYnvZAiEAkW3vxiZXYGaUWfzkcY55cQ\
        MSr9gHBAo8ctvwFpT4rRoqiAQIxv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0M\
        jMxODM4MDUiDHKbocWy11k9PMSzpCrcA5tYXYJgAr372XNGWTdBqsbSMGWouysaXV1ZKZNs\
        Buqs07GHrUEsSY62FpPl7xvkfxq8OBrMhpw8zZLzpLV5iT1%2B1Ccp%2B83KYiFs3qIBC9K\
        pIH6P4lFrGVpf9WRID8wFxgHxOPpqRVf%2BCPeK7ZIb6YwuuStOspzR0kVjayj1VAF97lY5\
        Lzim0Vum3VjiLwcpPEarO051yO9d8Zcg1d99%2BjvfSl%2FGsofYBGVHUqbHv2mu2Cv%2F1\
        O8C5N80hOhoecyGWz5tQBPwUry3UCTrh62iKPYeINwaV2MUm%2BDJ2X2%2FRo5swIxohePB\
        8Mx%2F76JzkfBTBFcrHn9DDfzUGxu9E7%2FcTYNkMS1TQuHrg32%2F9%2BlbUC5A%2BLSVF\
        %2FQj1etmyq1A55aVELxrP7ZRNNzAHheFu6R%2FwN%2B%2FxN46e4WXX4%2Fz7tWc0iiVnC\
        65O8PSnG9mhB8eZv2snQrKZEcBPT029GW%2FhE83WYkTBhTLhWaCtUoAL4Ul3C6OTdWtthY\
        %2B2sdXc7Fb9%2FyHYahWBAINwmcmMCLfgJ4bBjMLGZMs8HHl37kc3I%2BE5frWFI78uCp8\
        pBMc%2F%2Fh%2Bc%2FBhIezdWFZUZeHDqQT2gsUjdYdRlrYHCA5DZVlAdDuoPzr%2Fr%2Fc\
        RTKaOW03tTvFGMPbMqb0GOqUBwflW%2Bf6UhvqYInj4B4Gw%2F4FGvw8dfmcntP7YLlDPAw\
        wdIRU6BjSk0FXTRfwYse%2BbN5a4ejBYhwsJhKjEYiv80YSUJ3x1Dq5qHmagCitWEPXowif\
        EvBkLp0AW0NTe3tD6wJnUh%2BV1Y%2BVle1i4zcdMdNVrFzKC8lDuraZz6c2dlavZe7ea13\
        3ZbVNnTJ%2BHz1qiyU3WEfhIwQo28Z1iS2xTTggK%2F5aM&X-Amz-Signature=f39634c3\
        233cc3e3c2c740e121e020a67c88e3860cfc3a2e09c489469fbb6f65&X-Amz-SignedHe\
        aders=host&x-id=GetObject"
      expiry_time: "2025-02-10T22:20:42.575Z"
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
UPDATE_TIME: "2025-02-10T21:22:25.214Z"
EXPIRY_TIME: "2025-02-10T22:22:12.253Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZSSNIURH%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T212212Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEK3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCpSU9ugq9LixPhndG42DhRXLk3kL3UF2Y2kAgzGW%2BkKgIgO2mQR19qfqslDPlFKuw6jkoNI6m7nWTQ2lwFBr5Yc0wqiAQIxv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDBez9AFfmrgWp25B3ircA2xNHN2aIw46BTYja4OlcroqUgRvp2Mp0trYTzFzwBc4dXWiHxLf6EU%2Fd3U%2FcEEF4GpptYBgQx1POngGhUX8akQ%2BAITBLHwTYRZecQ2SkgKFyFqH8vRmOelVTJgX73dfydng3pdRf3gEUTyj3wv8snZeEn%2FX3eZpvaeMv042Zu8Cu2IIvbsku%2BW79pX8%2FujOm%2FJ4IaVQKZH4MRIdJrF7nXOLHh5fnkCWrRgGxnRyEFoQ0M33Vgu720yTAgT7PUxlMBFTRKUd9NGHKIFMX5HAGZ0R7fn0C2UaLeWmMXethxt8aQER1%2BvwOGiMfG0HmARXQK6ToA4Cp3WYIueSDLXptFn30awypKVJbbwUTZCYDL91QwBKxOKdMYaduX6XPqlVbO7cxaONo5LfPojg13YDiughTXmj%2B%2FnZVnwnZeJxlzCicGCaeKW2YzYI8roZAqmR%2B60b84AJsapeBfigkgxHApcAHP1tWL9ewo8mqKrK7sR5Wsq%2B9uvdw0sNXF1YtmXe17Z5ICtRQJDjY8exkKbfcSQlnm6G6uE%2B0shkbVdnYkYlhumxI0ZZmgiwymGR5bE7RzgcMbrNM6mtdCjlsQwgd%2Bdw3GoL0AbLrCURICzNOSRfNTrhvNhkYXxalON6ML%2FNqb0GOqUB3DOBcHUGoI6LL%2BbsR3l5CgIOwstRI8yYvBnCIQGNJF6LFFfBiZAYcib6n%2F3Ax1CNyBP4c9vnRZaoUqYA0mmti1T%2BdIDmyY3HXfTmV1tosDqEfg7fxQxvCuCewslwxmWCS2YYkmssHEcVaZChAMaW3qZjLs3LhBG1ApG008Ul19VM0Yq7XaFst6HEV0Y%2FpBuqr5t1aXuzfnpfNBWnf%2BMgPfyliYwY&X-Amz-Signature=43e061e18485edcb36c78c9aac9c82da8bacb234a62beea04e104e5b11fa3871&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZSSNIURH%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T212212Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEK3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCpSU9ugq9LixPhndG42DhRXLk3kL3UF2Y2kAgzGW%2BkKgIgO2mQR19qfqslDPlFKuw6jkoNI6m7nWTQ2lwFBr5Yc0wqiAQIxv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDBez9AFfmrgWp25B3ircA2xNHN2aIw46BTYja4OlcroqUgRvp2Mp0trYTzFzwBc4dXWiHxLf6EU%2Fd3U%2FcEEF4GpptYBgQx1POngGhUX8akQ%2BAITBLHwTYRZecQ2SkgKFyFqH8vRmOelVTJgX73dfydng3pdRf3gEUTyj3wv8snZeEn%2FX3eZpvaeMv042Zu8Cu2IIvbsku%2BW79pX8%2FujOm%2FJ4IaVQKZH4MRIdJrF7nXOLHh5fnkCWrRgGxnRyEFoQ0M33Vgu720yTAgT7PUxlMBFTRKUd9NGHKIFMX5HAGZ0R7fn0C2UaLeWmMXethxt8aQER1%2BvwOGiMfG0HmARXQK6ToA4Cp3WYIueSDLXptFn30awypKVJbbwUTZCYDL91QwBKxOKdMYaduX6XPqlVbO7cxaONo5LfPojg13YDiughTXmj%2B%2FnZVnwnZeJxlzCicGCaeKW2YzYI8roZAqmR%2B60b84AJsapeBfigkgxHApcAHP1tWL9ewo8mqKrK7sR5Wsq%2B9uvdw0sNXF1YtmXe17Z5ICtRQJDjY8exkKbfcSQlnm6G6uE%2B0shkbVdnYkYlhumxI0ZZmgiwymGR5bE7RzgcMbrNM6mtdCjlsQwgd%2Bdw3GoL0AbLrCURICzNOSRfNTrhvNhkYXxalON6ML%2FNqb0GOqUB3DOBcHUGoI6LL%2BbsR3l5CgIOwstRI8yYvBnCIQGNJF6LFFfBiZAYcib6n%2F3Ax1CNyBP4c9vnRZaoUqYA0mmti1T%2BdIDmyY3HXfTmV1tosDqEfg7fxQxvCuCewslwxmWCS2YYkmssHEcVaZChAMaW3qZjLs3LhBG1ApG008Ul19VM0Yq7XaFst6HEV0Y%2FpBuqr5t1aXuzfnpfNBWnf%2BMgPfyliYwY&X-Amz-Signature=1f9fe62954b2b6e6118b5d88caf0c0645590b7acc93a422ab09d378cd4a5b2ae&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZSSNIURH%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T212212Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEK3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCpSU9ugq9LixPhndG42DhRXLk3kL3UF2Y2kAgzGW%2BkKgIgO2mQR19qfqslDPlFKuw6jkoNI6m7nWTQ2lwFBr5Yc0wqiAQIxv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDBez9AFfmrgWp25B3ircA2xNHN2aIw46BTYja4OlcroqUgRvp2Mp0trYTzFzwBc4dXWiHxLf6EU%2Fd3U%2FcEEF4GpptYBgQx1POngGhUX8akQ%2BAITBLHwTYRZecQ2SkgKFyFqH8vRmOelVTJgX73dfydng3pdRf3gEUTyj3wv8snZeEn%2FX3eZpvaeMv042Zu8Cu2IIvbsku%2BW79pX8%2FujOm%2FJ4IaVQKZH4MRIdJrF7nXOLHh5fnkCWrRgGxnRyEFoQ0M33Vgu720yTAgT7PUxlMBFTRKUd9NGHKIFMX5HAGZ0R7fn0C2UaLeWmMXethxt8aQER1%2BvwOGiMfG0HmARXQK6ToA4Cp3WYIueSDLXptFn30awypKVJbbwUTZCYDL91QwBKxOKdMYaduX6XPqlVbO7cxaONo5LfPojg13YDiughTXmj%2B%2FnZVnwnZeJxlzCicGCaeKW2YzYI8roZAqmR%2B60b84AJsapeBfigkgxHApcAHP1tWL9ewo8mqKrK7sR5Wsq%2B9uvdw0sNXF1YtmXe17Z5ICtRQJDjY8exkKbfcSQlnm6G6uE%2B0shkbVdnYkYlhumxI0ZZmgiwymGR5bE7RzgcMbrNM6mtdCjlsQwgd%2Bdw3GoL0AbLrCURICzNOSRfNTrhvNhkYXxalON6ML%2FNqb0GOqUB3DOBcHUGoI6LL%2BbsR3l5CgIOwstRI8yYvBnCIQGNJF6LFFfBiZAYcib6n%2F3Ax1CNyBP4c9vnRZaoUqYA0mmti1T%2BdIDmyY3HXfTmV1tosDqEfg7fxQxvCuCewslwxmWCS2YYkmssHEcVaZChAMaW3qZjLs3LhBG1ApG008Ul19VM0Yq7XaFst6HEV0Y%2FpBuqr5t1aXuzfnpfNBWnf%2BMgPfyliYwY&X-Amz-Signature=0214e41523cb469d021138b127805b81a1f928d093b30cbb2dc5ad6ab9389542&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZSSNIURH%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T212212Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEK3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCpSU9ugq9LixPhndG42DhRXLk3kL3UF2Y2kAgzGW%2BkKgIgO2mQR19qfqslDPlFKuw6jkoNI6m7nWTQ2lwFBr5Yc0wqiAQIxv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDBez9AFfmrgWp25B3ircA2xNHN2aIw46BTYja4OlcroqUgRvp2Mp0trYTzFzwBc4dXWiHxLf6EU%2Fd3U%2FcEEF4GpptYBgQx1POngGhUX8akQ%2BAITBLHwTYRZecQ2SkgKFyFqH8vRmOelVTJgX73dfydng3pdRf3gEUTyj3wv8snZeEn%2FX3eZpvaeMv042Zu8Cu2IIvbsku%2BW79pX8%2FujOm%2FJ4IaVQKZH4MRIdJrF7nXOLHh5fnkCWrRgGxnRyEFoQ0M33Vgu720yTAgT7PUxlMBFTRKUd9NGHKIFMX5HAGZ0R7fn0C2UaLeWmMXethxt8aQER1%2BvwOGiMfG0HmARXQK6ToA4Cp3WYIueSDLXptFn30awypKVJbbwUTZCYDL91QwBKxOKdMYaduX6XPqlVbO7cxaONo5LfPojg13YDiughTXmj%2B%2FnZVnwnZeJxlzCicGCaeKW2YzYI8roZAqmR%2B60b84AJsapeBfigkgxHApcAHP1tWL9ewo8mqKrK7sR5Wsq%2B9uvdw0sNXF1YtmXe17Z5ICtRQJDjY8exkKbfcSQlnm6G6uE%2B0shkbVdnYkYlhumxI0ZZmgiwymGR5bE7RzgcMbrNM6mtdCjlsQwgd%2Bdw3GoL0AbLrCURICzNOSRfNTrhvNhkYXxalON6ML%2FNqb0GOqUB3DOBcHUGoI6LL%2BbsR3l5CgIOwstRI8yYvBnCIQGNJF6LFFfBiZAYcib6n%2F3Ax1CNyBP4c9vnRZaoUqYA0mmti1T%2BdIDmyY3HXfTmV1tosDqEfg7fxQxvCuCewslwxmWCS2YYkmssHEcVaZChAMaW3qZjLs3LhBG1ApG008Ul19VM0Yq7XaFst6HEV0Y%2FpBuqr5t1aXuzfnpfNBWnf%2BMgPfyliYwY&X-Amz-Signature=6693ac230ce19b39aceed57846c953094b4e2147dbcb35d83768053e69ebbd3d&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZSSNIURH%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T212212Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEK3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCpSU9ugq9LixPhndG42DhRXLk3kL3UF2Y2kAgzGW%2BkKgIgO2mQR19qfqslDPlFKuw6jkoNI6m7nWTQ2lwFBr5Yc0wqiAQIxv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDBez9AFfmrgWp25B3ircA2xNHN2aIw46BTYja4OlcroqUgRvp2Mp0trYTzFzwBc4dXWiHxLf6EU%2Fd3U%2FcEEF4GpptYBgQx1POngGhUX8akQ%2BAITBLHwTYRZecQ2SkgKFyFqH8vRmOelVTJgX73dfydng3pdRf3gEUTyj3wv8snZeEn%2FX3eZpvaeMv042Zu8Cu2IIvbsku%2BW79pX8%2FujOm%2FJ4IaVQKZH4MRIdJrF7nXOLHh5fnkCWrRgGxnRyEFoQ0M33Vgu720yTAgT7PUxlMBFTRKUd9NGHKIFMX5HAGZ0R7fn0C2UaLeWmMXethxt8aQER1%2BvwOGiMfG0HmARXQK6ToA4Cp3WYIueSDLXptFn30awypKVJbbwUTZCYDL91QwBKxOKdMYaduX6XPqlVbO7cxaONo5LfPojg13YDiughTXmj%2B%2FnZVnwnZeJxlzCicGCaeKW2YzYI8roZAqmR%2B60b84AJsapeBfigkgxHApcAHP1tWL9ewo8mqKrK7sR5Wsq%2B9uvdw0sNXF1YtmXe17Z5ICtRQJDjY8exkKbfcSQlnm6G6uE%2B0shkbVdnYkYlhumxI0ZZmgiwymGR5bE7RzgcMbrNM6mtdCjlsQwgd%2Bdw3GoL0AbLrCURICzNOSRfNTrhvNhkYXxalON6ML%2FNqb0GOqUB3DOBcHUGoI6LL%2BbsR3l5CgIOwstRI8yYvBnCIQGNJF6LFFfBiZAYcib6n%2F3Ax1CNyBP4c9vnRZaoUqYA0mmti1T%2BdIDmyY3HXfTmV1tosDqEfg7fxQxvCuCewslwxmWCS2YYkmssHEcVaZChAMaW3qZjLs3LhBG1ApG008Ul19VM0Yq7XaFst6HEV0Y%2FpBuqr5t1aXuzfnpfNBWnf%2BMgPfyliYwY&X-Amz-Signature=990ef21fb707441eac0885ec8bec9624a67ae299f1c9bb07e07e9f8a65418ecb&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TBW4FWPR%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T212213Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEK3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDKlSrqqjJF8%2FSZNZp%2F9vfjJkurxiMDO2bGiq5xwr0xIAIgB6W5lbeUDL%2FLoIc0jYBIEp2AnP4Uconv9yCLPiOzu1gqiAQIxv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDJhvx4nmLNPBnMnMcCrcAxBR1Ab5gGDL5XZavYnHBHZdJ0UgSiBU6%2FocaJv%2BiWI9CyncARIh8b8S2IXf76j3W5sgAxf9oovl0rypNQD1xZmKawMjqRAer9yOtLwtGBnSy62AZxwvAkPVHboFneRfuJzSZPqwRPhhRBD9p4wXYruE6Vc88WF70exrrVHdI0NxIbzSWzv3XJ1vu04R1ydI8bZ53reMkuIjQBn6Cz187AI8PHXKg2FtHM9YDOOjhFpvAHEYN%2FEiVtCdmAlr12ah8XJOFJ7Uj2wWRqWbeDCrXOL8K8XYfOtTG8QBveyCJQxt%2BMKFUrElZygDtekISNFxUQT3IomF1%2FmVBAvpKfryo91EyO2i%2FfxspM9h%2Fa3obN2yby22mrBTqdbMsmxk%2BPs%2BznSCjaW4L%2F%2FvZyMD9pN0Vfbrl%2FLxqUs6UJTyrt%2FI1Stht12dC4%2FqNcec9A5OlbyPOx%2Bqn08UPUjok%2FyhDMLS%2BQ9YJ2LLcbUK7UJMlQABi%2FEX0IlQ75vI8HDYbwE9czZVobp6NdelNCyb6QvmaaHi2zj%2B%2BirshgF1T6gdY34tAOo7hgeKEOt4qOqPcwdmhEByOogn5qGsxHRpij%2F98AHoLaDCQDC6PZ1Say%2FEVCbgovLD4TbnRGWXWMUgIkQVMNrNqb0GOqUBLqVME28fZ8VFQK%2F%2BL1ct2RrVUtZzO6fFlE7Bj14NBEIVNRkgGEyNXnTNVL7PxUPn7G71B97n7jpvKGPPqadHmmD%2BqFce8Yehm%2BHrvHPWTcxFuMjfUxY1dJvVVJvja2M0ZhKwe%2B9%2BFbu4pr96oO5sBbdoVNz1vyxCrWyCsckY6yH6op1z4iRBh%2BvPZzAc7m3QqHQ36d8hPTD6jecaV%2FC%2B0l1WFbw5&X-Amz-Signature=5ffa94422b927196e8ddfb5f6a8002e92411d108f1172cab0466d52d42432277&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WQV22GQL%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T212213Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEK3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDubIn1CIED%2BcFkoiTWcQhlOlKtI9%2B2hGJcjpePTHLjGwIhAMMr%2BStBz4dVsglfN5GmGcrWenT9crvvIcCgs4FIZW2%2BKogECMb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxSwTYmcTbr2D%2BjoKIq3AP%2F%2BCeZ95FmsQn7G42QvW4NXKQDAllXosevHrYIpigQ81h3JT6sPgyFHbq3c924w4yy4WLFlwQKAWL2Jzopc0ABNc%2Bj5vgXolkpjHxu22mYw3gY2AC4EGz9zdi5Pp9TSM6lXAX8PrBr6j3pIUfdYLcsxy%2FFipJ%2FI7h%2BnRoIcSd1a7Y9%2Bbp1TRC%2BmsXC7kFmx2IFz1MTT507vDDtclq2bvWVADgiLhKj9MKOEkAI8KWRhTA2PbkiSBvl3tjv%2FkvxtM%2FpWYZEZk9q4mzpFnhjtkB1sZ7neZ26Ty1kMFMnhqXlVCdVW6mL3FpWccQyPtlU5rHNOiIsATElLLlYvRR2ZUEPzUbju%2FymeNnvUe2DO1yAaScGXIQ8XURyO%2FgcUAKFqxPk0DvnHufFVtbBnCui%2Bb8rZLzHAHOEw1Z%2BVV1K8EufrK2bbLYzrpXDtB2g%2FpRQbGIs%2Ba%2BKLxc6ssDg7xsmsMmGYUNJWGjpkyft0KNKIInseouMoOsntaDp4ONKr0zBLmEU1NkeYqQMo0NGVQqc%2BD032OGLijcexsMnJzXRExbKo1IPeG2FTLgbpoDee4b1jXYqyUCgjdtn1yelOerLrlJqu1U5L3jskenzIfTT4jaevVGhSTaU5y8miMv23TDrzKm9BjqkATRb%2BlGiwTfee8MxufTMJ25e6ziegbHZDzo77XoKc8rUXB46WqQI%2BFQ0bxwMP5yAvM6w6N4mrb9zmYPcEOxZgAMHOuBl8wh8ha0%2FrEgG1R%2BIpPphx62DqwMBqqs7K%2Ftl2iwKbyrMxrLCJ1ZSkoA234HFXxoZkB4g1Ht3UigMV%2FDxl1Di5iAS4rPopvEp5Knx%2BxOI8ywYhJfGsA1d%2BQgnVlqTop9H&X-Amz-Signature=7df48c4bbdb4f7b81a732426ed42ab7f0a1c5ffa4c1e4d4312a13d759a1aab2b&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZSSNIURH%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T212212Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEK3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCpSU9ugq9LixPhndG42DhRXLk3kL3UF2Y2kAgzGW%2BkKgIgO2mQR19qfqslDPlFKuw6jkoNI6m7nWTQ2lwFBr5Yc0wqiAQIxv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDBez9AFfmrgWp25B3ircA2xNHN2aIw46BTYja4OlcroqUgRvp2Mp0trYTzFzwBc4dXWiHxLf6EU%2Fd3U%2FcEEF4GpptYBgQx1POngGhUX8akQ%2BAITBLHwTYRZecQ2SkgKFyFqH8vRmOelVTJgX73dfydng3pdRf3gEUTyj3wv8snZeEn%2FX3eZpvaeMv042Zu8Cu2IIvbsku%2BW79pX8%2FujOm%2FJ4IaVQKZH4MRIdJrF7nXOLHh5fnkCWrRgGxnRyEFoQ0M33Vgu720yTAgT7PUxlMBFTRKUd9NGHKIFMX5HAGZ0R7fn0C2UaLeWmMXethxt8aQER1%2BvwOGiMfG0HmARXQK6ToA4Cp3WYIueSDLXptFn30awypKVJbbwUTZCYDL91QwBKxOKdMYaduX6XPqlVbO7cxaONo5LfPojg13YDiughTXmj%2B%2FnZVnwnZeJxlzCicGCaeKW2YzYI8roZAqmR%2B60b84AJsapeBfigkgxHApcAHP1tWL9ewo8mqKrK7sR5Wsq%2B9uvdw0sNXF1YtmXe17Z5ICtRQJDjY8exkKbfcSQlnm6G6uE%2B0shkbVdnYkYlhumxI0ZZmgiwymGR5bE7RzgcMbrNM6mtdCjlsQwgd%2Bdw3GoL0AbLrCURICzNOSRfNTrhvNhkYXxalON6ML%2FNqb0GOqUB3DOBcHUGoI6LL%2BbsR3l5CgIOwstRI8yYvBnCIQGNJF6LFFfBiZAYcib6n%2F3Ax1CNyBP4c9vnRZaoUqYA0mmti1T%2BdIDmyY3HXfTmV1tosDqEfg7fxQxvCuCewslwxmWCS2YYkmssHEcVaZChAMaW3qZjLs3LhBG1ApG008Ul19VM0Yq7XaFst6HEV0Y%2FpBuqr5t1aXuzfnpfNBWnf%2BMgPfyliYwY&X-Amz-Signature=52d4b9540cf63201a8bca82383ae9fc61b99ff6674452a3be4da3b42dcd95745&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZSSNIURH%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T212212Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEK3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCpSU9ugq9LixPhndG42DhRXLk3kL3UF2Y2kAgzGW%2BkKgIgO2mQR19qfqslDPlFKuw6jkoNI6m7nWTQ2lwFBr5Yc0wqiAQIxv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDBez9AFfmrgWp25B3ircA2xNHN2aIw46BTYja4OlcroqUgRvp2Mp0trYTzFzwBc4dXWiHxLf6EU%2Fd3U%2FcEEF4GpptYBgQx1POngGhUX8akQ%2BAITBLHwTYRZecQ2SkgKFyFqH8vRmOelVTJgX73dfydng3pdRf3gEUTyj3wv8snZeEn%2FX3eZpvaeMv042Zu8Cu2IIvbsku%2BW79pX8%2FujOm%2FJ4IaVQKZH4MRIdJrF7nXOLHh5fnkCWrRgGxnRyEFoQ0M33Vgu720yTAgT7PUxlMBFTRKUd9NGHKIFMX5HAGZ0R7fn0C2UaLeWmMXethxt8aQER1%2BvwOGiMfG0HmARXQK6ToA4Cp3WYIueSDLXptFn30awypKVJbbwUTZCYDL91QwBKxOKdMYaduX6XPqlVbO7cxaONo5LfPojg13YDiughTXmj%2B%2FnZVnwnZeJxlzCicGCaeKW2YzYI8roZAqmR%2B60b84AJsapeBfigkgxHApcAHP1tWL9ewo8mqKrK7sR5Wsq%2B9uvdw0sNXF1YtmXe17Z5ICtRQJDjY8exkKbfcSQlnm6G6uE%2B0shkbVdnYkYlhumxI0ZZmgiwymGR5bE7RzgcMbrNM6mtdCjlsQwgd%2Bdw3GoL0AbLrCURICzNOSRfNTrhvNhkYXxalON6ML%2FNqb0GOqUB3DOBcHUGoI6LL%2BbsR3l5CgIOwstRI8yYvBnCIQGNJF6LFFfBiZAYcib6n%2F3Ax1CNyBP4c9vnRZaoUqYA0mmti1T%2BdIDmyY3HXfTmV1tosDqEfg7fxQxvCuCewslwxmWCS2YYkmssHEcVaZChAMaW3qZjLs3LhBG1ApG008Ul19VM0Yq7XaFst6HEV0Y%2FpBuqr5t1aXuzfnpfNBWnf%2BMgPfyliYwY&X-Amz-Signature=dd6d4988cc16bea5b530d6524076580896af8a18cb75ce7d901172b3b93bf4d6&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZSSNIURH%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T212212Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEK3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCpSU9ugq9LixPhndG42DhRXLk3kL3UF2Y2kAgzGW%2BkKgIgO2mQR19qfqslDPlFKuw6jkoNI6m7nWTQ2lwFBr5Yc0wqiAQIxv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDBez9AFfmrgWp25B3ircA2xNHN2aIw46BTYja4OlcroqUgRvp2Mp0trYTzFzwBc4dXWiHxLf6EU%2Fd3U%2FcEEF4GpptYBgQx1POngGhUX8akQ%2BAITBLHwTYRZecQ2SkgKFyFqH8vRmOelVTJgX73dfydng3pdRf3gEUTyj3wv8snZeEn%2FX3eZpvaeMv042Zu8Cu2IIvbsku%2BW79pX8%2FujOm%2FJ4IaVQKZH4MRIdJrF7nXOLHh5fnkCWrRgGxnRyEFoQ0M33Vgu720yTAgT7PUxlMBFTRKUd9NGHKIFMX5HAGZ0R7fn0C2UaLeWmMXethxt8aQER1%2BvwOGiMfG0HmARXQK6ToA4Cp3WYIueSDLXptFn30awypKVJbbwUTZCYDL91QwBKxOKdMYaduX6XPqlVbO7cxaONo5LfPojg13YDiughTXmj%2B%2FnZVnwnZeJxlzCicGCaeKW2YzYI8roZAqmR%2B60b84AJsapeBfigkgxHApcAHP1tWL9ewo8mqKrK7sR5Wsq%2B9uvdw0sNXF1YtmXe17Z5ICtRQJDjY8exkKbfcSQlnm6G6uE%2B0shkbVdnYkYlhumxI0ZZmgiwymGR5bE7RzgcMbrNM6mtdCjlsQwgd%2Bdw3GoL0AbLrCURICzNOSRfNTrhvNhkYXxalON6ML%2FNqb0GOqUB3DOBcHUGoI6LL%2BbsR3l5CgIOwstRI8yYvBnCIQGNJF6LFFfBiZAYcib6n%2F3Ax1CNyBP4c9vnRZaoUqYA0mmti1T%2BdIDmyY3HXfTmV1tosDqEfg7fxQxvCuCewslwxmWCS2YYkmssHEcVaZChAMaW3qZjLs3LhBG1ApG008Ul19VM0Yq7XaFst6HEV0Y%2FpBuqr5t1aXuzfnpfNBWnf%2BMgPfyliYwY&X-Amz-Signature=dab31f692720a3b39c82fe7d5882b21601116712a51cc43fa771351cc13f58ed&X-Amz-SignedHeaders=host&x-id=GetObject)


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

