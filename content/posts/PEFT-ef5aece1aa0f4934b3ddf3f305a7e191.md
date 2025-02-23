---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466S2GVOAAB%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250223T033028Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjENP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDYY9FMuNn0EGIL9sd\
  XT7D%2BSIRVU164%2FtwPOmWZr48DWAIhALGfQTbw1i8RGuYg4XlJuIi04NbV4sy0IbEuIc%2BAKC\
  ueKogECPz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgztJ3MYVpA22WA\
  gee8q3AN1bpV01knGH6ouG7vHpmzFir5KmkWm8S81v%2BDn032tcNoLxisTzkiKJnxh8q06FELBIb\
  7j%2BBzuXvn4fdDYVmj7azPADzn4H7rg8btA8EQbR6M2pj%2B4UMHzVYiAkaA1s5Oqebh3TkAq4%2\
  BU9u9Q0%2Bakp%2F5mxQjo30I27kbNtfam48nc6Ne%2F81nzD7%2FTJLdFioV%2F28Hb3PjCdWoA7\
  PVbNSBFD0G2Taa7uABlQRt3%2FYFDCU9b7yKk4pD7caO1M%2ByH6DM%2BqXWVBsYVz5LqfyjLTQJR\
  46i7fDNGiD8skKZH0v4GPLQWQNVjbfmnd%2FUzxNsyBa%2B%2BDI0qu%2B0rqVqXv4DjJfjjSgYTV\
  tq5Hu4p8FRQExElh03pq%2B%2FryR9PCkdVazgxW4XB67jiy5X%2F1URaDtaQr07l82%2Fnz%2FRk\
  daZTs6bTx5Ib9I4KxOC6xZDfgh3B1N5FIK994phObkCCFKzbOxRNXZhmMb2OXE5YNsW17Jd%2BglM\
  g9THWRHKMFwZa%2F25xnGMMlSNLcTTGP3hn57d5yWmeuMHj17d%2BmV1nlUJDjQvfTxjN0ObnCp2S\
  nh9llyhY%2FxEJJ7i33%2BD5IxhbjmcsfX5M0a%2B4%2F8r%2BpmzLhjL7c4V3CNcXCYWLvkJL6C0\
  xriFyiFDC%2Bk%2Bq9BjqkAWIkOSINaKMOTYGwaSDU0QjHV4dhrN7Pd2jy6YkZsVC7oAHYvNpAt%2\
  F3b1Nn0r6%2B2hswqNn2%2B%2Bb6I%2Bs3%2Bd1HjWFvkCrxmBF1CAI0aDH2%2Ft9Dm%2Bc6GHajs\
  mBc7XyoFw7aV7dQSZ5CKHD7NlXHiuSb%2Fi4OgMQVta%2BRweURsCbFFG%2BahaEQ6rWj6VWBQGAX\
  xBGW2pHZZUviw5Wx9H6QiF8ZFW2UwvhVA&X-Amz-Signature=3478c1f349501fe492920c96070\
  2c9683be8f2545e6dccb48bb861a1acd80625&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466XJKSYFIV%2F20250223%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250223T032907Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHM\
        EUCIQDHz%2BXn0b0f1aWMRY8Vq0EZX6Gry%2B4K68KjPTSzZGweZAIgLs64gOS%2BH8rQfH\
        JJNFfNcPWtUXnI%2Fk8lXioP86UCfesqiAQI%2BP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FA\
        RAAGgw2Mzc0MjMxODM4MDUiDGj4wCAxylaMMcXU1CrcAzEwYI%2BNSoryollqct%2Bh16ck\
        Bl44Po9rOdHLeaa7K2IyRcj7wJ%2FPkuF5zuA4qu%2FSOGD8wkN2wAZWsFjZONHkNm3fXjU\
        ONmYAPwPVGDdBZbCr8WvYwkRrlIILhl%2Fh92rhbyRQbkWesBRk6mAlzqqQooFAxha5Uc5C\
        OaEp%2BGR9S3irlhsuH4HDVnxBZgZIzfWc7sqytB29NZ2uyko7KQZtRiCyiSSuiGc50BNBz\
        Or3n8fWb8UiaYN5jVO8JjC7en4VzH3S0KHqK%2BArQpMj4TcZoT%2Fk%2F8yLSBb%2FdhZA\
        73HcVV7mWlyMY6pnajxBt2aXeOAHXQCJtv4dfpqx5nAEWamp8PP8LnoUZq%2Bws0x8iAOyp\
        9Fl%2BbJJ1tWdI62lap8NKCAq9%2F5hW37%2FYUAy6xZheAAQmHLCXWt4evIijaCYfD4Etp\
        f%2FI%2BiG6Cj9aTwE0H4P1Gkh3Vf2b4FYC1AhiZzWkmjjoX2%2BwpG5%2BxrdcnwzQF5Op\
        WjEwcKcsArz70IS9TRZCgtOPbRVQPSFaSl2idDu5Rky%2FqX%2By0pKCvC13FsBI0B0Red3\
        ymVd42EnrzwyAtDIz56yxa%2BAEH9cxTm7l4itrk4VmRIMa11Wtnm1sfQIPKiaqTgdnNunY\
        6apXZNlJjV4MO%2Bk6b0GOqUBN82%2FLFvrV5weYW8jS8yAnUmin18VzgWZ2qE8knqPF8TE\
        byLj%2Bidm0sjRgiLHYdy%2FqqNksCdSy7vIjFxfw5Jg5iRw0DRSRBniBV%2BHxsAaBSyda\
        IeO789rgARNFZ6%2Fcw7f%2BVk4cM0GBKKX6hUk%2BueB75mFGcYvZ5D7QQzmO%2F29eYDM\
        hrnC2fApx%2F0gKT1Wlz1PDjIocTBUs2684CezM1XjE563JwFE&X-Amz-Signature=61c2\
        ea1296fe0f01c71d2ac9d4f51b4f8c5f665671a38210c709d841ea9fd7a6&X-Amz-Sign\
        edHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-23T04:29:07.087Z"
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
UPDATE_TIME: "2025-02-23T03:30:34.097Z"
EXPIRY_TIME: "2025-02-23T04:30:25.776Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SWNRBCBA%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T033026Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQC%2BWt1rxzYekZh437FX%2FIZUP5LgLfMNZwzvlIFe1HuB3AIgcqYg16FPJSnQNNwaP5a4WsW%2F%2B13BhVAi%2FzXFYeypAscqiAQI9%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPqcZ3dCUqi2BugyfSrcAxfQBwGn0BUWPJk8IxsRnR8zcQGqeOWGRMlqZwSjjnBGnJPmBxZyHkjPzUAq0GIVtBTm2ZJTYnO64%2BtcCqYQj%2BQhvdyZYpYhFvr5hlVmoixnxmTF3s7%2BB1UjJ%2BkyiwRf33q8YTqd0e1jeWeQadbO1Fgpw8wkyvC8JRx2OB1gla0LiCk31TSo72yvWs1ggeKd%2BcaUNgFCtNZgLr2w1to637zLL%2FpeKJquJg59QORoPuRmeDba6tJKepJcLUgWVPz4QUi1jngli5sA37kNXtzxXDYY8OGScIiSuThz9n1RJwxnx96zqRFtBinfFTIEEiYl%2BwvVGkKHtctQyaZlHl73z0tp%2B7c%2BEnYH%2Bt2LvFmaFE7O2AKk1Up9oKovZSutDCNcFcC9DFqK7j%2B9ZCVm0CLSbqLiAeNZ%2BaQqtJdL2xbv5nq38CgiD3zHuoAsZijp562cnOqTTw8jMz20ARf0oS6j1oFXQYe%2B8QK38M8vDGuH5%2FyeTzZsR%2F9TGqfSOhcHUuziWVdDL475FL6FV4OwOBGCc9TLvqm4eoPgVw0QzgkjLgsgjax5Pppo9WhGE0O0119arErEFgDsWJA5psxos2rUdLixgvxZp2uxkZreqLNXlGsxv5qbD3vkT1VGczA5MPWO6b0GOqUBkS7cFrFz7D%2F0G5Gi9CKz9blUiXuhzolqwn2U7zizNv9OwHH2luM1Ha7%2Fy8fmyFb7zqxtr3V1unIE8N3%2FWkQLqS5CVXwvbgOKJ4cjgyBVrUAKSs35ekOLh5Qm0oUPIxz3Xb%2BHhqvTjvwwUTUBtvQTREks2hTsrIARi1lE0a%2F8xTfb%2BSDu106EhVPhAUmOrYd%2FtKQN81b%2FjXRa99%2FTa1x5smFqa9jr&X-Amz-Signature=241ca46e8fc68c5ee273e6eb6ef77823fa771db7d6e0b7f8ecd54727208aa260&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SWNRBCBA%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T033026Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQC%2BWt1rxzYekZh437FX%2FIZUP5LgLfMNZwzvlIFe1HuB3AIgcqYg16FPJSnQNNwaP5a4WsW%2F%2B13BhVAi%2FzXFYeypAscqiAQI9%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPqcZ3dCUqi2BugyfSrcAxfQBwGn0BUWPJk8IxsRnR8zcQGqeOWGRMlqZwSjjnBGnJPmBxZyHkjPzUAq0GIVtBTm2ZJTYnO64%2BtcCqYQj%2BQhvdyZYpYhFvr5hlVmoixnxmTF3s7%2BB1UjJ%2BkyiwRf33q8YTqd0e1jeWeQadbO1Fgpw8wkyvC8JRx2OB1gla0LiCk31TSo72yvWs1ggeKd%2BcaUNgFCtNZgLr2w1to637zLL%2FpeKJquJg59QORoPuRmeDba6tJKepJcLUgWVPz4QUi1jngli5sA37kNXtzxXDYY8OGScIiSuThz9n1RJwxnx96zqRFtBinfFTIEEiYl%2BwvVGkKHtctQyaZlHl73z0tp%2B7c%2BEnYH%2Bt2LvFmaFE7O2AKk1Up9oKovZSutDCNcFcC9DFqK7j%2B9ZCVm0CLSbqLiAeNZ%2BaQqtJdL2xbv5nq38CgiD3zHuoAsZijp562cnOqTTw8jMz20ARf0oS6j1oFXQYe%2B8QK38M8vDGuH5%2FyeTzZsR%2F9TGqfSOhcHUuziWVdDL475FL6FV4OwOBGCc9TLvqm4eoPgVw0QzgkjLgsgjax5Pppo9WhGE0O0119arErEFgDsWJA5psxos2rUdLixgvxZp2uxkZreqLNXlGsxv5qbD3vkT1VGczA5MPWO6b0GOqUBkS7cFrFz7D%2F0G5Gi9CKz9blUiXuhzolqwn2U7zizNv9OwHH2luM1Ha7%2Fy8fmyFb7zqxtr3V1unIE8N3%2FWkQLqS5CVXwvbgOKJ4cjgyBVrUAKSs35ekOLh5Qm0oUPIxz3Xb%2BHhqvTjvwwUTUBtvQTREks2hTsrIARi1lE0a%2F8xTfb%2BSDu106EhVPhAUmOrYd%2FtKQN81b%2FjXRa99%2FTa1x5smFqa9jr&X-Amz-Signature=d104c11f2111a6d4f30e1d93ebebcd96d03fccc3f26f1124f2e83dba44d3e788&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SWNRBCBA%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T033026Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQC%2BWt1rxzYekZh437FX%2FIZUP5LgLfMNZwzvlIFe1HuB3AIgcqYg16FPJSnQNNwaP5a4WsW%2F%2B13BhVAi%2FzXFYeypAscqiAQI9%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPqcZ3dCUqi2BugyfSrcAxfQBwGn0BUWPJk8IxsRnR8zcQGqeOWGRMlqZwSjjnBGnJPmBxZyHkjPzUAq0GIVtBTm2ZJTYnO64%2BtcCqYQj%2BQhvdyZYpYhFvr5hlVmoixnxmTF3s7%2BB1UjJ%2BkyiwRf33q8YTqd0e1jeWeQadbO1Fgpw8wkyvC8JRx2OB1gla0LiCk31TSo72yvWs1ggeKd%2BcaUNgFCtNZgLr2w1to637zLL%2FpeKJquJg59QORoPuRmeDba6tJKepJcLUgWVPz4QUi1jngli5sA37kNXtzxXDYY8OGScIiSuThz9n1RJwxnx96zqRFtBinfFTIEEiYl%2BwvVGkKHtctQyaZlHl73z0tp%2B7c%2BEnYH%2Bt2LvFmaFE7O2AKk1Up9oKovZSutDCNcFcC9DFqK7j%2B9ZCVm0CLSbqLiAeNZ%2BaQqtJdL2xbv5nq38CgiD3zHuoAsZijp562cnOqTTw8jMz20ARf0oS6j1oFXQYe%2B8QK38M8vDGuH5%2FyeTzZsR%2F9TGqfSOhcHUuziWVdDL475FL6FV4OwOBGCc9TLvqm4eoPgVw0QzgkjLgsgjax5Pppo9WhGE0O0119arErEFgDsWJA5psxos2rUdLixgvxZp2uxkZreqLNXlGsxv5qbD3vkT1VGczA5MPWO6b0GOqUBkS7cFrFz7D%2F0G5Gi9CKz9blUiXuhzolqwn2U7zizNv9OwHH2luM1Ha7%2Fy8fmyFb7zqxtr3V1unIE8N3%2FWkQLqS5CVXwvbgOKJ4cjgyBVrUAKSs35ekOLh5Qm0oUPIxz3Xb%2BHhqvTjvwwUTUBtvQTREks2hTsrIARi1lE0a%2F8xTfb%2BSDu106EhVPhAUmOrYd%2FtKQN81b%2FjXRa99%2FTa1x5smFqa9jr&X-Amz-Signature=06b1a2e0ecdfbc88c456e9a0ec66b365a3cdd7381fbc1ff673e059d603eefdde&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SWNRBCBA%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T033026Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQC%2BWt1rxzYekZh437FX%2FIZUP5LgLfMNZwzvlIFe1HuB3AIgcqYg16FPJSnQNNwaP5a4WsW%2F%2B13BhVAi%2FzXFYeypAscqiAQI9%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPqcZ3dCUqi2BugyfSrcAxfQBwGn0BUWPJk8IxsRnR8zcQGqeOWGRMlqZwSjjnBGnJPmBxZyHkjPzUAq0GIVtBTm2ZJTYnO64%2BtcCqYQj%2BQhvdyZYpYhFvr5hlVmoixnxmTF3s7%2BB1UjJ%2BkyiwRf33q8YTqd0e1jeWeQadbO1Fgpw8wkyvC8JRx2OB1gla0LiCk31TSo72yvWs1ggeKd%2BcaUNgFCtNZgLr2w1to637zLL%2FpeKJquJg59QORoPuRmeDba6tJKepJcLUgWVPz4QUi1jngli5sA37kNXtzxXDYY8OGScIiSuThz9n1RJwxnx96zqRFtBinfFTIEEiYl%2BwvVGkKHtctQyaZlHl73z0tp%2B7c%2BEnYH%2Bt2LvFmaFE7O2AKk1Up9oKovZSutDCNcFcC9DFqK7j%2B9ZCVm0CLSbqLiAeNZ%2BaQqtJdL2xbv5nq38CgiD3zHuoAsZijp562cnOqTTw8jMz20ARf0oS6j1oFXQYe%2B8QK38M8vDGuH5%2FyeTzZsR%2F9TGqfSOhcHUuziWVdDL475FL6FV4OwOBGCc9TLvqm4eoPgVw0QzgkjLgsgjax5Pppo9WhGE0O0119arErEFgDsWJA5psxos2rUdLixgvxZp2uxkZreqLNXlGsxv5qbD3vkT1VGczA5MPWO6b0GOqUBkS7cFrFz7D%2F0G5Gi9CKz9blUiXuhzolqwn2U7zizNv9OwHH2luM1Ha7%2Fy8fmyFb7zqxtr3V1unIE8N3%2FWkQLqS5CVXwvbgOKJ4cjgyBVrUAKSs35ekOLh5Qm0oUPIxz3Xb%2BHhqvTjvwwUTUBtvQTREks2hTsrIARi1lE0a%2F8xTfb%2BSDu106EhVPhAUmOrYd%2FtKQN81b%2FjXRa99%2FTa1x5smFqa9jr&X-Amz-Signature=c44d9a070a5f197563be73e639368414659b78b8683540cf1c1686c2ef0b03f6&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SWNRBCBA%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T033026Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQC%2BWt1rxzYekZh437FX%2FIZUP5LgLfMNZwzvlIFe1HuB3AIgcqYg16FPJSnQNNwaP5a4WsW%2F%2B13BhVAi%2FzXFYeypAscqiAQI9%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPqcZ3dCUqi2BugyfSrcAxfQBwGn0BUWPJk8IxsRnR8zcQGqeOWGRMlqZwSjjnBGnJPmBxZyHkjPzUAq0GIVtBTm2ZJTYnO64%2BtcCqYQj%2BQhvdyZYpYhFvr5hlVmoixnxmTF3s7%2BB1UjJ%2BkyiwRf33q8YTqd0e1jeWeQadbO1Fgpw8wkyvC8JRx2OB1gla0LiCk31TSo72yvWs1ggeKd%2BcaUNgFCtNZgLr2w1to637zLL%2FpeKJquJg59QORoPuRmeDba6tJKepJcLUgWVPz4QUi1jngli5sA37kNXtzxXDYY8OGScIiSuThz9n1RJwxnx96zqRFtBinfFTIEEiYl%2BwvVGkKHtctQyaZlHl73z0tp%2B7c%2BEnYH%2Bt2LvFmaFE7O2AKk1Up9oKovZSutDCNcFcC9DFqK7j%2B9ZCVm0CLSbqLiAeNZ%2BaQqtJdL2xbv5nq38CgiD3zHuoAsZijp562cnOqTTw8jMz20ARf0oS6j1oFXQYe%2B8QK38M8vDGuH5%2FyeTzZsR%2F9TGqfSOhcHUuziWVdDL475FL6FV4OwOBGCc9TLvqm4eoPgVw0QzgkjLgsgjax5Pppo9WhGE0O0119arErEFgDsWJA5psxos2rUdLixgvxZp2uxkZreqLNXlGsxv5qbD3vkT1VGczA5MPWO6b0GOqUBkS7cFrFz7D%2F0G5Gi9CKz9blUiXuhzolqwn2U7zizNv9OwHH2luM1Ha7%2Fy8fmyFb7zqxtr3V1unIE8N3%2FWkQLqS5CVXwvbgOKJ4cjgyBVrUAKSs35ekOLh5Qm0oUPIxz3Xb%2BHhqvTjvwwUTUBtvQTREks2hTsrIARi1lE0a%2F8xTfb%2BSDu106EhVPhAUmOrYd%2FtKQN81b%2FjXRa99%2FTa1x5smFqa9jr&X-Amz-Signature=9e56ac433a61d74530c49086811df1749224f74be1606128911088307af5a94d&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YWU3KZG4%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T033027Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDygwmvhJkKDNZ3raQ89FankW7aMtlTrx711wmIx11qSAIgNAk%2Bu6368c6MUxir5uZOiEqgdqXrCRjA8V4HRt5c2WoqiAQI%2BP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOyKDVw0vXTB4NzkASrcAxdLKGSmaItH6yhhb%2Bdv3M3N2%2BE%2BTC7AaKGgevwExYWviqQ72tLSL3C0ZA0WqSA95RqOGtHNaqaA%2FcZTRG%2BI%2B9%2F3Umr9UBoWd%2BmFuNZ3bm6IP1OjkteaOG%2BuNq%2FIOdpwjtzGpPgV4PSdvtQTHVP0lYT6zqu1y6yPMyEmvvK5oo6kiX0xVld7pEIVqOBI3uUxkaReSlkJ%2FepfYbND9XYX2gTRd3xe2cz60RWojX957RXMxlYg0XkO5QCMi%2BLCPODovBkKoKgf5C1M1a2R651y1BgllxmmOps36Zpon6i5HmIkTJ9UBXlcwdXRfkJp7oJ6ztzYzpOiZQ53ETiWsm%2FmVUe%2BLb9xtwyxYLLf4s9A9PzsM5lDx0ptWOoUB1qemLgfYSkfyTg8OfqqfwhQW8Lp8RdG2a2n9GsNheOcQFr3NGux9KQhg42fql9Cj%2Bq0k1PNPqD1Qaj5fpZphCzkisC0%2BrwxPRhgve2ChQAGmANkEJrrLVhW820DFnm%2FbWPUNnkZ8NKx%2FMNfx1nVF8VQO7zaS0H3RIvy65REDnCO24CZr1GfBVh1fSIovs9uTOVeGyyLJAQFLkOvqJX052KJ8f8wnX4J8oKAd2N%2F5BQCJxKl38IN2V2ts%2FTyOdB0bioEMO2s6b0GOqUBzYWNVYBZlXw40rWyEaPhHjmEf25FJk6oxwMS8Xb%2FrKDhHLHNZ58hGIHbJxRycXXoBnRHBBSByXXKzNlXxL8t5Gm%2BEHHgeLd9QH%2Fb0gq8nP71MUjNF4Kfcz6RAfqh18vofYx1NXV6WwHxraTzcjeYvBxrmxkHA1g4gQjni5%2B%2BhnbvBeX72igtv43v7JpgvrMaZLk4uyysju2IEwZEqAiPBc48mBhu&X-Amz-Signature=2eab02039b02ef5751b3d16b0143cdabd386cb355a3d8a1f7ddd36518b4d0e6a&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466V3DHSGYO%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T033028Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQC5KsW6KyyoeQylW1CxPnxlCxPgZzjovih8n9l1Vfu9jQIgL7fvkVrkHq1kupf8NjMOWmwddV95t52BfFEHjFPHFFQqiAQI%2B%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDJOBPSx5%2FFjQuh%2F%2F8SrcA%2FIJiDqUnZVPtr8UtCKBOVNeJy57DDDzbBQmWbEutRvMp0DQWv1MwQ4f0dJfqRna58uNsLwzT8HUWun1REkA%2BcfTP5euktnM8TBPrFSm9lKjjqXH9%2Bx2S1P6%2BXEPx2n1kjA2uXpwIlKBAZ0eElHQtx7hj03gDk4hIP9pSOoP0M7JkIXut5BFirucj8jeWPdaIGgmU3KUKVclt9bPZQWrKwPZgEwOp0rHBE7%2FeOIeXM7Q%2FRpiZpjN9CwaZNSLB2Py7UtLJf6pM3%2FPFfw1ugmSanV7UcVcnJBFlwsrVGh2Uqzn%2B2O%2FDUfnyo2VOntSDwno4Ygsb8m2dztmtOaoUxEzcQVtEg%2BvFXFBzcBUp%2ByevqgvvEfVkaUUuIG9CRckBFBJO6NO%2FSjlDPraU6FHuAxD6aWWeyFpwur%2Bg0fHTu3Nf6HTS5zIKhjyxMOLutCtiP7xHb1Hv%2BgBV2rfd2xyst2fXaQISgvJot0BDDnwF%2FfQmgKM9RRIitYaOCOJJy9r4XWwyiKeQVO0cOAFGMaBbhnLKV%2FNF%2FsrjE95L%2Fm9m8VQsaMvjI5HpSNvShonHOrOeJ8BDBvSV7JpezAkdhv2%2FwSLTSPEzuQyFLUbSU9l3u%2FkSY4IgH5HyMe40tnK945YMP%2F46b0GOqUBWq2OPv2VtcCnAwm%2F9N848%2FPtpef3zMuyIimm0vNCOWJk16PYaaHLlKHEywyZQaUxZVIgKIzv2cbbURAyY8I4Iu3b2KFRYrnAfefR3xK%2B6lMvUjRcthBJeCB0p17uwRAwPdtCcIXL3eax0o4vFWGLe%2FR5KX5MORdTIVnFfTCfl%2BZoFGYgioxByNjsIH3OFZNi1rKNZxxVHhfMhaTKkLI7akgmdozK&X-Amz-Signature=3188970b07e6cb68b94d6096a3e21c5ed60c92d4850fb1fb63925a557b1e0dab&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SWNRBCBA%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T033026Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQC%2BWt1rxzYekZh437FX%2FIZUP5LgLfMNZwzvlIFe1HuB3AIgcqYg16FPJSnQNNwaP5a4WsW%2F%2B13BhVAi%2FzXFYeypAscqiAQI9%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPqcZ3dCUqi2BugyfSrcAxfQBwGn0BUWPJk8IxsRnR8zcQGqeOWGRMlqZwSjjnBGnJPmBxZyHkjPzUAq0GIVtBTm2ZJTYnO64%2BtcCqYQj%2BQhvdyZYpYhFvr5hlVmoixnxmTF3s7%2BB1UjJ%2BkyiwRf33q8YTqd0e1jeWeQadbO1Fgpw8wkyvC8JRx2OB1gla0LiCk31TSo72yvWs1ggeKd%2BcaUNgFCtNZgLr2w1to637zLL%2FpeKJquJg59QORoPuRmeDba6tJKepJcLUgWVPz4QUi1jngli5sA37kNXtzxXDYY8OGScIiSuThz9n1RJwxnx96zqRFtBinfFTIEEiYl%2BwvVGkKHtctQyaZlHl73z0tp%2B7c%2BEnYH%2Bt2LvFmaFE7O2AKk1Up9oKovZSutDCNcFcC9DFqK7j%2B9ZCVm0CLSbqLiAeNZ%2BaQqtJdL2xbv5nq38CgiD3zHuoAsZijp562cnOqTTw8jMz20ARf0oS6j1oFXQYe%2B8QK38M8vDGuH5%2FyeTzZsR%2F9TGqfSOhcHUuziWVdDL475FL6FV4OwOBGCc9TLvqm4eoPgVw0QzgkjLgsgjax5Pppo9WhGE0O0119arErEFgDsWJA5psxos2rUdLixgvxZp2uxkZreqLNXlGsxv5qbD3vkT1VGczA5MPWO6b0GOqUBkS7cFrFz7D%2F0G5Gi9CKz9blUiXuhzolqwn2U7zizNv9OwHH2luM1Ha7%2Fy8fmyFb7zqxtr3V1unIE8N3%2FWkQLqS5CVXwvbgOKJ4cjgyBVrUAKSs35ekOLh5Qm0oUPIxz3Xb%2BHhqvTjvwwUTUBtvQTREks2hTsrIARi1lE0a%2F8xTfb%2BSDu106EhVPhAUmOrYd%2FtKQN81b%2FjXRa99%2FTa1x5smFqa9jr&X-Amz-Signature=1f19350ff8a299072faf848b93b51a9960a43cc014b4d6780d6a63ef0c35e683&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SWNRBCBA%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T033026Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQC%2BWt1rxzYekZh437FX%2FIZUP5LgLfMNZwzvlIFe1HuB3AIgcqYg16FPJSnQNNwaP5a4WsW%2F%2B13BhVAi%2FzXFYeypAscqiAQI9%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPqcZ3dCUqi2BugyfSrcAxfQBwGn0BUWPJk8IxsRnR8zcQGqeOWGRMlqZwSjjnBGnJPmBxZyHkjPzUAq0GIVtBTm2ZJTYnO64%2BtcCqYQj%2BQhvdyZYpYhFvr5hlVmoixnxmTF3s7%2BB1UjJ%2BkyiwRf33q8YTqd0e1jeWeQadbO1Fgpw8wkyvC8JRx2OB1gla0LiCk31TSo72yvWs1ggeKd%2BcaUNgFCtNZgLr2w1to637zLL%2FpeKJquJg59QORoPuRmeDba6tJKepJcLUgWVPz4QUi1jngli5sA37kNXtzxXDYY8OGScIiSuThz9n1RJwxnx96zqRFtBinfFTIEEiYl%2BwvVGkKHtctQyaZlHl73z0tp%2B7c%2BEnYH%2Bt2LvFmaFE7O2AKk1Up9oKovZSutDCNcFcC9DFqK7j%2B9ZCVm0CLSbqLiAeNZ%2BaQqtJdL2xbv5nq38CgiD3zHuoAsZijp562cnOqTTw8jMz20ARf0oS6j1oFXQYe%2B8QK38M8vDGuH5%2FyeTzZsR%2F9TGqfSOhcHUuziWVdDL475FL6FV4OwOBGCc9TLvqm4eoPgVw0QzgkjLgsgjax5Pppo9WhGE0O0119arErEFgDsWJA5psxos2rUdLixgvxZp2uxkZreqLNXlGsxv5qbD3vkT1VGczA5MPWO6b0GOqUBkS7cFrFz7D%2F0G5Gi9CKz9blUiXuhzolqwn2U7zizNv9OwHH2luM1Ha7%2Fy8fmyFb7zqxtr3V1unIE8N3%2FWkQLqS5CVXwvbgOKJ4cjgyBVrUAKSs35ekOLh5Qm0oUPIxz3Xb%2BHhqvTjvwwUTUBtvQTREks2hTsrIARi1lE0a%2F8xTfb%2BSDu106EhVPhAUmOrYd%2FtKQN81b%2FjXRa99%2FTa1x5smFqa9jr&X-Amz-Signature=14087384aeb39fdbe1845e16f7a3b1205ee2f0691443e92c5709918f3deb40f8&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SWNRBCBA%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T033026Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQC%2BWt1rxzYekZh437FX%2FIZUP5LgLfMNZwzvlIFe1HuB3AIgcqYg16FPJSnQNNwaP5a4WsW%2F%2B13BhVAi%2FzXFYeypAscqiAQI9%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPqcZ3dCUqi2BugyfSrcAxfQBwGn0BUWPJk8IxsRnR8zcQGqeOWGRMlqZwSjjnBGnJPmBxZyHkjPzUAq0GIVtBTm2ZJTYnO64%2BtcCqYQj%2BQhvdyZYpYhFvr5hlVmoixnxmTF3s7%2BB1UjJ%2BkyiwRf33q8YTqd0e1jeWeQadbO1Fgpw8wkyvC8JRx2OB1gla0LiCk31TSo72yvWs1ggeKd%2BcaUNgFCtNZgLr2w1to637zLL%2FpeKJquJg59QORoPuRmeDba6tJKepJcLUgWVPz4QUi1jngli5sA37kNXtzxXDYY8OGScIiSuThz9n1RJwxnx96zqRFtBinfFTIEEiYl%2BwvVGkKHtctQyaZlHl73z0tp%2B7c%2BEnYH%2Bt2LvFmaFE7O2AKk1Up9oKovZSutDCNcFcC9DFqK7j%2B9ZCVm0CLSbqLiAeNZ%2BaQqtJdL2xbv5nq38CgiD3zHuoAsZijp562cnOqTTw8jMz20ARf0oS6j1oFXQYe%2B8QK38M8vDGuH5%2FyeTzZsR%2F9TGqfSOhcHUuziWVdDL475FL6FV4OwOBGCc9TLvqm4eoPgVw0QzgkjLgsgjax5Pppo9WhGE0O0119arErEFgDsWJA5psxos2rUdLixgvxZp2uxkZreqLNXlGsxv5qbD3vkT1VGczA5MPWO6b0GOqUBkS7cFrFz7D%2F0G5Gi9CKz9blUiXuhzolqwn2U7zizNv9OwHH2luM1Ha7%2Fy8fmyFb7zqxtr3V1unIE8N3%2FWkQLqS5CVXwvbgOKJ4cjgyBVrUAKSs35ekOLh5Qm0oUPIxz3Xb%2BHhqvTjvwwUTUBtvQTREks2hTsrIARi1lE0a%2F8xTfb%2BSDu106EhVPhAUmOrYd%2FtKQN81b%2FjXRa99%2FTa1x5smFqa9jr&X-Amz-Signature=312b5fdd2f6aee39be60170ee81b6ca2591609e8755c0f142295da60957e8e25&X-Amz-SignedHeaders=host&x-id=GetObject)


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

