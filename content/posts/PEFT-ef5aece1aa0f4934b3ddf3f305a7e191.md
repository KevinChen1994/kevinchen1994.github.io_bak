---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4663VVU3PX2%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250211T111955Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjELv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCWFjxzoOHCG3U1x%2\
  BQSU5QOwsn8EMAXab9RFIWQbjtMVAIhAITzmdmtwNPiyBTKA5fd13rgZDK%2Br8cJUKOaxL8Lm2Ot\
  KogECNT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyPWK%2BjApAHlu1\
  vBhsq3AOaNaqIb%2BK%2FXpNlXi%2BfgMQv4I2oEgXtZ2NA8%2BQV4MMwtJTBBTmYKcVi8iKeCFSW\
  q%2BcP%2BPC%2Fw9r%2FtDDSW%2FVkyRZ9RU6NhTlhmF7m9fQaqVllE%2B8HHgRX%2B6l32xxfama\
  U95ueolGafslGFT14y3wXe6ocdvdTva5TLbDDo%2BJHUpU7jlrgw6f2Y%2Bi12mhvUskNoGe1jV6x\
  v7NureB3Zyvp5fg8xuHCi%2B%2BtOxWt4c9kEcfRFrO30B85BLG3ZkdOuIXmnvNLbNPL9xgJRx0ju\
  Ctyj%2BrSUT1coCYo48Wlh8G0ba91cY%2BwYNT786oEvmP%2FLvieZscbfuYrmQehZvKQVgEY5tlS\
  vXRBpwOEhfcfIGCnsYclApvKNphuXmawabNg1tYeOLYpYbQKWawtsqf%2BDdEfa5qCs5cbhYntIup\
  vRLgXRLBJtDna81g7TGfGtP6Ra86kuZm8OPNeBREV3u%2BSDfzk6hQvhROqeMN%2F1HdIJc4WPRae\
  pfcyjOrbikMB9nFCpWp6t7oqO%2BfBha%2B4Balds2nj0ZXYFUT1%2FkxlMTjZPGrtwuPvPVZixjc\
  oVUnQihXzBeOEa3YFE49BYQrQo5SweYSdobpucqqbkZeI1IOL0gcLEGMrmA8QlQbn2uCPcK7C3TDd\
  0qy9BjqkAXZYu5tCmXPZKm%2FunoQJHsanP5S3qJKUPU%2BJRC2Ib4qyNA9FJdp8jQB4SSdCndbPy\
  6X69blVNE309kwBHf3%2F3U1Grru5IkDQm5%2B0jeJkYi%2FV%2Be%2FoTWigcZDMOXSiuKuzMEdh\
  JeuoeDhsvtdDC4sMAjeNU6XmxK7QK21BZGW8W6lAvFcaK4UtuY0XgQoNHMboUHxb%2FBGUNFZC8fc\
  QGVvUs8l1TKT1&X-Amz-Signature=82613b684756dbb7f5feba0480b34a75d2e4a9f4cdb375c\
  24b9340e7f3aeb72b&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466TIFTVREK%2F20250211%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250211T111842Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjELv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQ\
        CICYSlo0Lyj4fS8tL6cuBBgLd9%2Fk2Z2%2BChjmhlzuWK4dmAiAAum19xp5UzB65Pn6Roq\
        CFvKlyTYqd3D2FdeNeKLxh4yqIBAjU%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzN\
        zQyMzE4MzgwNSIMh1yuhrDLaB%2BNWjWbKtwDMWsDF9sYyExJt%2F93q7xQFQdlSRiaArxG\
        OxELBGJtBK8bnccsWLcFXBIHJ3omIYwmYP1xIieyB2fpTT%2FME3C5rac5YLJnCl1LvD52i\
        6dPewVKsyt4TFjDXVtwtsNIchJ95K9sKg7xq8TeTGVhj1w5C%2FUW79Ht7a8H1reMQkE0km\
        Mbw0d6Xndt9cmi%2B0u0uDhoR7%2FWsefhHh37cHq%2B%2FctEbgXPorFpRVh5YV0zg%2BN\
        4sdFV1uOcoN%2BHxz8fJMTOLIQtfSmw6GT80hvUh2zCY%2BE0mhzxpMxhMK%2FAMRROI%2F\
        kqqfE30xTHG7lm7%2FdgNRv793pAVlxISzi7v6j%2Fm7kfnvdkSKed6XTCv92GFYzsaq7Wc\
        Kr2zV2rUFRY%2BZsnFbwWvk2nUzL0rLybP34HCeOvUBhehUm45BSFaVbUcMCh1HI%2B5VYt\
        OEC81756jCFLe4y%2FzYUYZd2BookIFKuNYeKwPvoYZ%2FckTsxHsadVLzg3zB2U%2BON5K\
        tK7LwKyuMKhMf4CRDBnLzi4CqzPzndPjcY6B0lJkSTD8xNKtL7MxfLvKVIPXaR2p0Xg6u0G\
        RRMD3iPFmDzF3J%2FAbceBhQjo4SGm3SEnINKvyVk9NnRcubplANA7HK3ZbOCQQnt5IhW3T\
        JUwsNOsvQY6pgExdERXJz%2FVmMwZqMm1Y4brGycLcSe99duu%2BcrI69cgKAs139baYF5z\
        9zazBnNvgAMB6JQTMlxuRXEWhmxwANSi1m72wfzbZ0M3U%2BugyrN1P1WBXB8l%2BVFERqG\
        hllyo6pnRsHSJTTwvRIl7DNlYaVY2woh953rqZaNKeZD3b%2BSwBPFn%2BWQuVD3ct166DD\
        zG2Q4kQJMLD8vjsdlWO5i1ofdhw8feud6V&X-Amz-Signature=d54ddb5201d40380c0dd\
        efd3123be80a3c1b3d92ca43450233b80a94bda437b5&X-Amz-SignedHeaders=host&x\
        -id=GetObject"
      expiry_time: "2025-02-11T12:18:42.546Z"
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
UPDATE_TIME: "2025-02-11T11:19:59.910Z"
EXPIRY_TIME: "2025-02-11T12:19:51.439Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665G2KEYU4%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T111952Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIHKdh%2BhVJQIatC%2BbqLUqFKDDprgNfdzfKeMXH9PyXiLjAiEA%2Bk4K4O221ELpQ7H8%2FeDkp9hSIlvU3RUHJAFRXuHJL4sqiAQI1P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDO5F%2F6tMR5DFg%2FtbhircA5HdjmB3zwxibtrKF8x9V2zpSFdPMM0Ev9b5lpwaCAu3evrOaZY5Y%2BQzpt%2FlPxXlhFw8Wd9McO9195C0VHpUXqFS58MpeZfy4At5e1Sho25MHB7idIBzgbvkTZdxxgovYepEvJqlSxH0hQqoG2m%2FCgCV0KEO6foDOpsCcBlQ1pr%2FOi1QJ4kkM1IBhTvgmgVZQluYeo1nJuSXT9vupnm6uFkO2x9jLI0vpU9ROsTzFzIaFLeuIVSOqtLDITq0mJjQoFg8sy0F5K0ywKAy4rl77UrrrihZO9z1Fki%2BX713q%2B9l2fR%2FUrvnBy2ZxU1Hds%2BezZn2OR6avW4SmXP4AbCCFjzTUHNdDtK9F9HcHKGRdnk%2F1TcFVKp6hiNnGWju2GUGeaPtKYKfsOYU8WHgNt5RK1Z98xUi9cdlu4aBUHT16UsTzXBcljkF9COYDISaaEkH9r7dqIJVLzQMOi8O%2BhrZuWviudI9yvg3rFL2OB5Sgwze9qOjz8XyJuT2NS4%2BkquIgd%2BaOA%2FrIHT9eT8S1dASQ9H3UjQrhXTj5jEuZTYZfkhK0ffNoOYMmMs3sIpPCJNGsRxrMpsE89VH32H%2Ftvym6L3tyBst0xKZbX%2FexB5KpetmVP6e7IhrRhhT%2FbGPMJrTrL0GOqUBjWTEYNHYb8eXi%2Bcuuidk4xXB6pTp6LSCrvCID61VJ%2FsFS8EkABf3hc%2FaToIrdlidQgOCoS8DOZJ16pIBLQfnlFgb4G2jY6wNvuAFY3X7%2BfUUlKRiRpQO1N1LjTIdafy2BTj4WtUABCl1atvtAsPUhPtT3eBVcEcOEeELJolRF8STgfaJlyiUrULe%2Bo438k5EYEXwomU%2BB3kMwidZFPt1pCuMP3wl&X-Amz-Signature=79f2a54484a83844b3aabaed2749bdbf30e41bb6e2f5f6ee298b437d198e6d83&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665G2KEYU4%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T111952Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIHKdh%2BhVJQIatC%2BbqLUqFKDDprgNfdzfKeMXH9PyXiLjAiEA%2Bk4K4O221ELpQ7H8%2FeDkp9hSIlvU3RUHJAFRXuHJL4sqiAQI1P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDO5F%2F6tMR5DFg%2FtbhircA5HdjmB3zwxibtrKF8x9V2zpSFdPMM0Ev9b5lpwaCAu3evrOaZY5Y%2BQzpt%2FlPxXlhFw8Wd9McO9195C0VHpUXqFS58MpeZfy4At5e1Sho25MHB7idIBzgbvkTZdxxgovYepEvJqlSxH0hQqoG2m%2FCgCV0KEO6foDOpsCcBlQ1pr%2FOi1QJ4kkM1IBhTvgmgVZQluYeo1nJuSXT9vupnm6uFkO2x9jLI0vpU9ROsTzFzIaFLeuIVSOqtLDITq0mJjQoFg8sy0F5K0ywKAy4rl77UrrrihZO9z1Fki%2BX713q%2B9l2fR%2FUrvnBy2ZxU1Hds%2BezZn2OR6avW4SmXP4AbCCFjzTUHNdDtK9F9HcHKGRdnk%2F1TcFVKp6hiNnGWju2GUGeaPtKYKfsOYU8WHgNt5RK1Z98xUi9cdlu4aBUHT16UsTzXBcljkF9COYDISaaEkH9r7dqIJVLzQMOi8O%2BhrZuWviudI9yvg3rFL2OB5Sgwze9qOjz8XyJuT2NS4%2BkquIgd%2BaOA%2FrIHT9eT8S1dASQ9H3UjQrhXTj5jEuZTYZfkhK0ffNoOYMmMs3sIpPCJNGsRxrMpsE89VH32H%2Ftvym6L3tyBst0xKZbX%2FexB5KpetmVP6e7IhrRhhT%2FbGPMJrTrL0GOqUBjWTEYNHYb8eXi%2Bcuuidk4xXB6pTp6LSCrvCID61VJ%2FsFS8EkABf3hc%2FaToIrdlidQgOCoS8DOZJ16pIBLQfnlFgb4G2jY6wNvuAFY3X7%2BfUUlKRiRpQO1N1LjTIdafy2BTj4WtUABCl1atvtAsPUhPtT3eBVcEcOEeELJolRF8STgfaJlyiUrULe%2Bo438k5EYEXwomU%2BB3kMwidZFPt1pCuMP3wl&X-Amz-Signature=70324a93595376b897551edc7c293d731221a0624a6037b9dd3c6b5a139dee71&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665G2KEYU4%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T111952Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIHKdh%2BhVJQIatC%2BbqLUqFKDDprgNfdzfKeMXH9PyXiLjAiEA%2Bk4K4O221ELpQ7H8%2FeDkp9hSIlvU3RUHJAFRXuHJL4sqiAQI1P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDO5F%2F6tMR5DFg%2FtbhircA5HdjmB3zwxibtrKF8x9V2zpSFdPMM0Ev9b5lpwaCAu3evrOaZY5Y%2BQzpt%2FlPxXlhFw8Wd9McO9195C0VHpUXqFS58MpeZfy4At5e1Sho25MHB7idIBzgbvkTZdxxgovYepEvJqlSxH0hQqoG2m%2FCgCV0KEO6foDOpsCcBlQ1pr%2FOi1QJ4kkM1IBhTvgmgVZQluYeo1nJuSXT9vupnm6uFkO2x9jLI0vpU9ROsTzFzIaFLeuIVSOqtLDITq0mJjQoFg8sy0F5K0ywKAy4rl77UrrrihZO9z1Fki%2BX713q%2B9l2fR%2FUrvnBy2ZxU1Hds%2BezZn2OR6avW4SmXP4AbCCFjzTUHNdDtK9F9HcHKGRdnk%2F1TcFVKp6hiNnGWju2GUGeaPtKYKfsOYU8WHgNt5RK1Z98xUi9cdlu4aBUHT16UsTzXBcljkF9COYDISaaEkH9r7dqIJVLzQMOi8O%2BhrZuWviudI9yvg3rFL2OB5Sgwze9qOjz8XyJuT2NS4%2BkquIgd%2BaOA%2FrIHT9eT8S1dASQ9H3UjQrhXTj5jEuZTYZfkhK0ffNoOYMmMs3sIpPCJNGsRxrMpsE89VH32H%2Ftvym6L3tyBst0xKZbX%2FexB5KpetmVP6e7IhrRhhT%2FbGPMJrTrL0GOqUBjWTEYNHYb8eXi%2Bcuuidk4xXB6pTp6LSCrvCID61VJ%2FsFS8EkABf3hc%2FaToIrdlidQgOCoS8DOZJ16pIBLQfnlFgb4G2jY6wNvuAFY3X7%2BfUUlKRiRpQO1N1LjTIdafy2BTj4WtUABCl1atvtAsPUhPtT3eBVcEcOEeELJolRF8STgfaJlyiUrULe%2Bo438k5EYEXwomU%2BB3kMwidZFPt1pCuMP3wl&X-Amz-Signature=3fb1bf6f7a7c7982c92046bb01c1817b5bbcdebb970691d79b6fc87379935006&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665G2KEYU4%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T111952Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIHKdh%2BhVJQIatC%2BbqLUqFKDDprgNfdzfKeMXH9PyXiLjAiEA%2Bk4K4O221ELpQ7H8%2FeDkp9hSIlvU3RUHJAFRXuHJL4sqiAQI1P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDO5F%2F6tMR5DFg%2FtbhircA5HdjmB3zwxibtrKF8x9V2zpSFdPMM0Ev9b5lpwaCAu3evrOaZY5Y%2BQzpt%2FlPxXlhFw8Wd9McO9195C0VHpUXqFS58MpeZfy4At5e1Sho25MHB7idIBzgbvkTZdxxgovYepEvJqlSxH0hQqoG2m%2FCgCV0KEO6foDOpsCcBlQ1pr%2FOi1QJ4kkM1IBhTvgmgVZQluYeo1nJuSXT9vupnm6uFkO2x9jLI0vpU9ROsTzFzIaFLeuIVSOqtLDITq0mJjQoFg8sy0F5K0ywKAy4rl77UrrrihZO9z1Fki%2BX713q%2B9l2fR%2FUrvnBy2ZxU1Hds%2BezZn2OR6avW4SmXP4AbCCFjzTUHNdDtK9F9HcHKGRdnk%2F1TcFVKp6hiNnGWju2GUGeaPtKYKfsOYU8WHgNt5RK1Z98xUi9cdlu4aBUHT16UsTzXBcljkF9COYDISaaEkH9r7dqIJVLzQMOi8O%2BhrZuWviudI9yvg3rFL2OB5Sgwze9qOjz8XyJuT2NS4%2BkquIgd%2BaOA%2FrIHT9eT8S1dASQ9H3UjQrhXTj5jEuZTYZfkhK0ffNoOYMmMs3sIpPCJNGsRxrMpsE89VH32H%2Ftvym6L3tyBst0xKZbX%2FexB5KpetmVP6e7IhrRhhT%2FbGPMJrTrL0GOqUBjWTEYNHYb8eXi%2Bcuuidk4xXB6pTp6LSCrvCID61VJ%2FsFS8EkABf3hc%2FaToIrdlidQgOCoS8DOZJ16pIBLQfnlFgb4G2jY6wNvuAFY3X7%2BfUUlKRiRpQO1N1LjTIdafy2BTj4WtUABCl1atvtAsPUhPtT3eBVcEcOEeELJolRF8STgfaJlyiUrULe%2Bo438k5EYEXwomU%2BB3kMwidZFPt1pCuMP3wl&X-Amz-Signature=d374594c3e109566a12be97f3e8913c80f4f9858dd862337d912cf5ebff292db&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665G2KEYU4%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T111952Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIHKdh%2BhVJQIatC%2BbqLUqFKDDprgNfdzfKeMXH9PyXiLjAiEA%2Bk4K4O221ELpQ7H8%2FeDkp9hSIlvU3RUHJAFRXuHJL4sqiAQI1P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDO5F%2F6tMR5DFg%2FtbhircA5HdjmB3zwxibtrKF8x9V2zpSFdPMM0Ev9b5lpwaCAu3evrOaZY5Y%2BQzpt%2FlPxXlhFw8Wd9McO9195C0VHpUXqFS58MpeZfy4At5e1Sho25MHB7idIBzgbvkTZdxxgovYepEvJqlSxH0hQqoG2m%2FCgCV0KEO6foDOpsCcBlQ1pr%2FOi1QJ4kkM1IBhTvgmgVZQluYeo1nJuSXT9vupnm6uFkO2x9jLI0vpU9ROsTzFzIaFLeuIVSOqtLDITq0mJjQoFg8sy0F5K0ywKAy4rl77UrrrihZO9z1Fki%2BX713q%2B9l2fR%2FUrvnBy2ZxU1Hds%2BezZn2OR6avW4SmXP4AbCCFjzTUHNdDtK9F9HcHKGRdnk%2F1TcFVKp6hiNnGWju2GUGeaPtKYKfsOYU8WHgNt5RK1Z98xUi9cdlu4aBUHT16UsTzXBcljkF9COYDISaaEkH9r7dqIJVLzQMOi8O%2BhrZuWviudI9yvg3rFL2OB5Sgwze9qOjz8XyJuT2NS4%2BkquIgd%2BaOA%2FrIHT9eT8S1dASQ9H3UjQrhXTj5jEuZTYZfkhK0ffNoOYMmMs3sIpPCJNGsRxrMpsE89VH32H%2Ftvym6L3tyBst0xKZbX%2FexB5KpetmVP6e7IhrRhhT%2FbGPMJrTrL0GOqUBjWTEYNHYb8eXi%2Bcuuidk4xXB6pTp6LSCrvCID61VJ%2FsFS8EkABf3hc%2FaToIrdlidQgOCoS8DOZJ16pIBLQfnlFgb4G2jY6wNvuAFY3X7%2BfUUlKRiRpQO1N1LjTIdafy2BTj4WtUABCl1atvtAsPUhPtT3eBVcEcOEeELJolRF8STgfaJlyiUrULe%2Bo438k5EYEXwomU%2BB3kMwidZFPt1pCuMP3wl&X-Amz-Signature=212cf1c0ae61562561d84edd47dfadbc4d56462c7b4c48c945f7b8f00179a70f&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466X7N26XBS%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T111952Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIDR4zwsImW9cPcSyjjN1rNZPLlZIMc3jSrJXgCl2oQO5AiEAjaJ1BNpvMEiIjKCWWtJqysHwnvT3pZ4ToU03MATRjT4qiAQI1P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOkntPwuO2T1PXx4kyrcA%2Bg4UtzJ2Y7L%2FGg44070VWVfEwASsvgjLcePwolpt4xw2RxSzet%2FVoTxIGbljuG5clAWze%2BVjkaubjzocM4zDfm%2F9sWbUoaYImzof3WfgFxyS13YIBwvSPkQUeq%2Bo%2F51UtsAAMoFhOnD2mXHkBKMiSnmyRws1c7pkDZMlQUJZvwzGnST68nqoJP97pYS0c0CoHQ811p%2FaBwgcRcRCdO9mFtFYJtPTdVEgzA2KrDwfPDdgcyaB%2BDtMznjYZI7nOd4UIOXvrKYWTdYG31QfDxDTY9UeSeN1%2FTDN0hbGc6r76ZOEvC%2BrVs%2FdOeW7hzL1F3TcAE2XG2gX369Y972Xt2HvGpZEEiVcwwtpzmx%2FeXWJ3FiK%2FmFIhfNtaM30HvnawGl2oly7WG1DOXNZF0LPMmJZ5b7E1NeShkzFkr44J95Oe5pDqdYLMU4u5iZmCwdI1fsvMiZRi0tD%2F%2FWIKgy8ok3InMiFhoQgBoOj0XlPClpYRi1m9ZQqyLGuts8OrNtIjAsXen2ZWj8j1gL%2Bf2wKWLIf6bfggC6U%2F2T%2Fncsd%2FM5RmlMRSGThOE7S3CvqiJGQZS3Xo6HGk3pjP0SVM0f%2B3MzQEIGn%2BInB%2F2rRLP%2BzHL50GSxeMM0A3S53GJrzhyNMNLSrL0GOqUBtD2e6Hi88R96EMHaWO%2FNBN8H3Zx0q0e69xwY0A7HB62MiuZM8vmKJntuKlM3R6Ysn6Ngl9NjUIPIO2XYv75vXpCR1NarHooBhI5hUqvdmhtBHxmeGSKRiZH0c6pkVU2SjYMAdcxlZSjMBFa0JCLv8vWivpttdrKp1lS3Zom%2FklLadwEfWjxwpgwNc2lggTmo0FbfbmWrqKLwKA%2BKvkgNGxkno8xX&X-Amz-Signature=bb40704978e97a083d33b915560929cb9eceed09792465c89c2d1b107750ce8a&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RESKP2FJ%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T111954Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIE1%2BADI8UIE5aVDTSAUwp%2FOfVm19DVJ%2B58k7jKPnDIMrAiAplgWlyQxBii%2BLNnKG0pI%2BgTHD1%2FxR3%2BcEXlpWSKBo8SqIBAjU%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMXx6mEA2c6qoh802AKtwDTaCP5rMM8sZeQs10FiDvn5OmfC%2Bo8Kypekh8rVMz2Oz7v0aVNmAIAf%2BUVORLBRhZ8PyB0KjCGEUdTBcxQsnJVbgPW9DfytQzSDfrL2CCiSMk0%2BnA2%2Fr14G%2F%2B1HYVq97B8QYYbIMrZ0EZ6cp%2FyESvN5MifyvSirpSLMiJLQpd7hB7JEzvWLQA3NibMEWoYwzZods228p76NaZP4amXjF7q%2BzuUtIUjQ%2B8VR%2Fs98ut4PpIVbqivfNs0pZt0c8swFa7jdVn2c2%2B8eJkBInzMjEcOaV0ZQG40LzGLiZz4%2BhGsbclVakeyzhMmBcbTn%2BNWVzjVnoTlAg0r3bd9CgQNcry3Icc6tC3leax%2Byjc9vxNiYUBoT6EjJhCTEKyn0mEU8t%2Fgg4pUJ8XAd8oF51TumcNkPtX0dZePAqLWF%2BUvvT%2BTLqobhw%2FFq%2B%2BDGiyHH8sSdU%2BedmioUujJEKZkS4h0LVARnsh%2FMjScfjlvmyKKdpR8wyc5s5HA3nqcmWjmPps7cMxB0rTLHkdqqAKw8Uf2W2UzPvqLCJFFN3bXX9idvBf8Tfv3GV2QQI5O7gxNpqfe3MEccu5vpOWKrAyUipxB1rxz%2BFiFqqgMXzY4gmzoWFWQXoXcpBjCpt2RocBo2swt9OsvQY6pgHoyBypgZqBiGHbVUdkgUc%2FJkEdUa0wJsc%2BShadyiFaUtQCBWE%2BB5scItpysPqmXHGMUC4QAsfX20WIQ7upMuaUttWFMBx%2FOB3uxYsSXJc3WNdEQ512BSY42t%2BRVjDEj0Kvz%2FppgIONvOjQErrFwwBEY5oxkd12oyg8p42likAyCHKD6Ssh8ri8FXbrcy01x3sF66z%2F0CUE%2FOQAUaaZETUUlv1Ao4EB&X-Amz-Signature=4d42463476a48bb15a591809523c00fd1dae13bf2dd2d90f031a35db1b7be227&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665G2KEYU4%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T111952Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIHKdh%2BhVJQIatC%2BbqLUqFKDDprgNfdzfKeMXH9PyXiLjAiEA%2Bk4K4O221ELpQ7H8%2FeDkp9hSIlvU3RUHJAFRXuHJL4sqiAQI1P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDO5F%2F6tMR5DFg%2FtbhircA5HdjmB3zwxibtrKF8x9V2zpSFdPMM0Ev9b5lpwaCAu3evrOaZY5Y%2BQzpt%2FlPxXlhFw8Wd9McO9195C0VHpUXqFS58MpeZfy4At5e1Sho25MHB7idIBzgbvkTZdxxgovYepEvJqlSxH0hQqoG2m%2FCgCV0KEO6foDOpsCcBlQ1pr%2FOi1QJ4kkM1IBhTvgmgVZQluYeo1nJuSXT9vupnm6uFkO2x9jLI0vpU9ROsTzFzIaFLeuIVSOqtLDITq0mJjQoFg8sy0F5K0ywKAy4rl77UrrrihZO9z1Fki%2BX713q%2B9l2fR%2FUrvnBy2ZxU1Hds%2BezZn2OR6avW4SmXP4AbCCFjzTUHNdDtK9F9HcHKGRdnk%2F1TcFVKp6hiNnGWju2GUGeaPtKYKfsOYU8WHgNt5RK1Z98xUi9cdlu4aBUHT16UsTzXBcljkF9COYDISaaEkH9r7dqIJVLzQMOi8O%2BhrZuWviudI9yvg3rFL2OB5Sgwze9qOjz8XyJuT2NS4%2BkquIgd%2BaOA%2FrIHT9eT8S1dASQ9H3UjQrhXTj5jEuZTYZfkhK0ffNoOYMmMs3sIpPCJNGsRxrMpsE89VH32H%2Ftvym6L3tyBst0xKZbX%2FexB5KpetmVP6e7IhrRhhT%2FbGPMJrTrL0GOqUBjWTEYNHYb8eXi%2Bcuuidk4xXB6pTp6LSCrvCID61VJ%2FsFS8EkABf3hc%2FaToIrdlidQgOCoS8DOZJ16pIBLQfnlFgb4G2jY6wNvuAFY3X7%2BfUUlKRiRpQO1N1LjTIdafy2BTj4WtUABCl1atvtAsPUhPtT3eBVcEcOEeELJolRF8STgfaJlyiUrULe%2Bo438k5EYEXwomU%2BB3kMwidZFPt1pCuMP3wl&X-Amz-Signature=1e4bb683dee0ea7b733749244d94407df966beebe556bfb4cc3838a7e4ada1c4&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665G2KEYU4%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T111952Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIHKdh%2BhVJQIatC%2BbqLUqFKDDprgNfdzfKeMXH9PyXiLjAiEA%2Bk4K4O221ELpQ7H8%2FeDkp9hSIlvU3RUHJAFRXuHJL4sqiAQI1P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDO5F%2F6tMR5DFg%2FtbhircA5HdjmB3zwxibtrKF8x9V2zpSFdPMM0Ev9b5lpwaCAu3evrOaZY5Y%2BQzpt%2FlPxXlhFw8Wd9McO9195C0VHpUXqFS58MpeZfy4At5e1Sho25MHB7idIBzgbvkTZdxxgovYepEvJqlSxH0hQqoG2m%2FCgCV0KEO6foDOpsCcBlQ1pr%2FOi1QJ4kkM1IBhTvgmgVZQluYeo1nJuSXT9vupnm6uFkO2x9jLI0vpU9ROsTzFzIaFLeuIVSOqtLDITq0mJjQoFg8sy0F5K0ywKAy4rl77UrrrihZO9z1Fki%2BX713q%2B9l2fR%2FUrvnBy2ZxU1Hds%2BezZn2OR6avW4SmXP4AbCCFjzTUHNdDtK9F9HcHKGRdnk%2F1TcFVKp6hiNnGWju2GUGeaPtKYKfsOYU8WHgNt5RK1Z98xUi9cdlu4aBUHT16UsTzXBcljkF9COYDISaaEkH9r7dqIJVLzQMOi8O%2BhrZuWviudI9yvg3rFL2OB5Sgwze9qOjz8XyJuT2NS4%2BkquIgd%2BaOA%2FrIHT9eT8S1dASQ9H3UjQrhXTj5jEuZTYZfkhK0ffNoOYMmMs3sIpPCJNGsRxrMpsE89VH32H%2Ftvym6L3tyBst0xKZbX%2FexB5KpetmVP6e7IhrRhhT%2FbGPMJrTrL0GOqUBjWTEYNHYb8eXi%2Bcuuidk4xXB6pTp6LSCrvCID61VJ%2FsFS8EkABf3hc%2FaToIrdlidQgOCoS8DOZJ16pIBLQfnlFgb4G2jY6wNvuAFY3X7%2BfUUlKRiRpQO1N1LjTIdafy2BTj4WtUABCl1atvtAsPUhPtT3eBVcEcOEeELJolRF8STgfaJlyiUrULe%2Bo438k5EYEXwomU%2BB3kMwidZFPt1pCuMP3wl&X-Amz-Signature=083dc265e85f0e55a0d7eb8ce4ae07500b6e0884f7d5f86b6dd8a72c5df98f4c&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665G2KEYU4%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T111952Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIHKdh%2BhVJQIatC%2BbqLUqFKDDprgNfdzfKeMXH9PyXiLjAiEA%2Bk4K4O221ELpQ7H8%2FeDkp9hSIlvU3RUHJAFRXuHJL4sqiAQI1P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDO5F%2F6tMR5DFg%2FtbhircA5HdjmB3zwxibtrKF8x9V2zpSFdPMM0Ev9b5lpwaCAu3evrOaZY5Y%2BQzpt%2FlPxXlhFw8Wd9McO9195C0VHpUXqFS58MpeZfy4At5e1Sho25MHB7idIBzgbvkTZdxxgovYepEvJqlSxH0hQqoG2m%2FCgCV0KEO6foDOpsCcBlQ1pr%2FOi1QJ4kkM1IBhTvgmgVZQluYeo1nJuSXT9vupnm6uFkO2x9jLI0vpU9ROsTzFzIaFLeuIVSOqtLDITq0mJjQoFg8sy0F5K0ywKAy4rl77UrrrihZO9z1Fki%2BX713q%2B9l2fR%2FUrvnBy2ZxU1Hds%2BezZn2OR6avW4SmXP4AbCCFjzTUHNdDtK9F9HcHKGRdnk%2F1TcFVKp6hiNnGWju2GUGeaPtKYKfsOYU8WHgNt5RK1Z98xUi9cdlu4aBUHT16UsTzXBcljkF9COYDISaaEkH9r7dqIJVLzQMOi8O%2BhrZuWviudI9yvg3rFL2OB5Sgwze9qOjz8XyJuT2NS4%2BkquIgd%2BaOA%2FrIHT9eT8S1dASQ9H3UjQrhXTj5jEuZTYZfkhK0ffNoOYMmMs3sIpPCJNGsRxrMpsE89VH32H%2Ftvym6L3tyBst0xKZbX%2FexB5KpetmVP6e7IhrRhhT%2FbGPMJrTrL0GOqUBjWTEYNHYb8eXi%2Bcuuidk4xXB6pTp6LSCrvCID61VJ%2FsFS8EkABf3hc%2FaToIrdlidQgOCoS8DOZJ16pIBLQfnlFgb4G2jY6wNvuAFY3X7%2BfUUlKRiRpQO1N1LjTIdafy2BTj4WtUABCl1atvtAsPUhPtT3eBVcEcOEeELJolRF8STgfaJlyiUrULe%2Bo438k5EYEXwomU%2BB3kMwidZFPt1pCuMP3wl&X-Amz-Signature=1b68ee55769d8561dea1f51490efb2222fce5164d9e46d1a1a90e99970ac4ab2&X-Amz-SignedHeaders=host&x-id=GetObject)


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

