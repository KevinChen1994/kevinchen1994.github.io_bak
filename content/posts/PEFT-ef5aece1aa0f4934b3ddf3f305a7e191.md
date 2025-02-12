---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466XAZSW2OI%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250212T072236Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCID7h5QC4s%2BZAMrC\
  LkuCt5A7k4iYJke31gHCHs1EWzsM7AiEAmqWfPNnKs93kQpL4ru7hnmlX4MZeB3QwbARvArDRoOQq\
  iAQI6P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDODIZYtY8vgDfGl%2\
  FQSrcAx2lguzEohmG%2BlOWN07sYbcNv96GVpQJXWSZqfEl7yvahHOQfsdXBn4MtcauTQFoX1V3s%\
  2F5cOJyHwfzXZz1TNzEtvgNFHY6u8M4J5jBmdesmXq%2Bhk6SgQsTmz4wytTDUVJa1mQr7%2FG7qm\
  X4JAPR2r3BCivyys2RhOyL8drJb5U6N6fY9Ce3DFNJ07kilCfPhl9TCYlqNZsF9aCyYLyCtKetbDG\
  7633cC8HSKsUh6bff6FsHj7EPiR2vppSsYHPHK0YahNbi8R3rEpMoONccGI6ZO%2FoIsIpstmtsBh\
  FyEHT2SJLbuxYrZe2Zy7EVquCceN1187M6d90iUKRKAnUPIMCR0kB2RJ8FnXJdVu7sx4cP6yYmrag\
  zyU6H%2FkrB4HvwHXYnu0iJ%2FA8JaKryD4jgBLsQ2GnAkicOF%2BhyijwZ%2Bp5Ql6Hw%2FCZT1U\
  zokMZE41CNeKu2m7uBzpnDc2xOsL268qTE5Rl%2Bf0%2FJKrwiRMCGlF0t4XBiGyk6CO9MAGeAf2e\
  X6inNvge1G%2FS%2BA%2Fh17%2B4ijIpS3jH%2BzgE3GyjLGLCrP%2Bkl7kpTH5jmIVUAs0q8p5WJ\
  ALVAwSjusrSrOUKcsYtQd3uN2BWhBDdVXfDJ%2B8OVkpT44AzR8JsqJbhy5IB1IMMeTsb0GOqUB1%\
  2BNQzGcuITd%2BWqK%2BtryGtjR9Sej76JEu3aG%2FeYZOODTdreFxDEp3Thz3Tj9GRhNA%2BDPRX\
  rzCG7wOC%2FnLrc2wTaPAIemF%2BzLwtT7dDrQaUFUJPNvoySK5FjRwoSVlhzlb1H8LZBX6f%2Fse\
  XKp0GQTXWKiXKskGwuxFuMWEoIpzFfxStu8bYaGG7Mlxu3lqI%2Bl8MtFlcJoQNVKXpHta83QVO1Q\
  jSLem&X-Amz-Signature=dfef1f8ec00161b051fb5a062a89bea51279ab45722413a7a9a611b\
  89153bf76&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4666L77FYYA%2F20250212%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250212T072053Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHM\
        EUCIAKs1D3nzyhgW4DbnPk1a%2BumPQBNiHMQSxxvw1ANe66rAiEA4o6mrMZ7VLZ5TJcdqA\
        M%2F48mHW0%2FkNt55AymqarRtsxcqiAQI6P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAG\
        gw2Mzc0MjMxODM4MDUiDO%2FD7DlrutWGG9zFGSrcA3htne364fXvLtLRDwDti0nGAb%2Bk\
        45Uha8wVREbaVkniO%2FWNJe9I01OpI1%2FZqAf94vu26ei4YytsQ4ZHJhHSiQllooS11YM\
        GGh%2FevfTZ7nXgBnJWbQzhqTS2qNf%2Fq7LvRgDne5ZSGFKhfQs8pob7HQN8GuoRPAtPO6\
        hXI1Ca7u%2BkfFE4ClEFXOF5BhdFBOPB7MPnzSi1CwVI2Yr9MfPkCm1bZISVyzsE6iZO%2F\
        9y%2B4jLCDRB1tgIgbjqg3MRGPGFkYaCTI77uIwEyksFKu9BgSNKnhqcXmnR2t3OaYsjKFo\
        O0PVRngGJJpxJz5O8UMXT1oaNivV5Z%2F8vuj7TK5XF0u%2F9irYwFEIg4PQVXw0L6B%2Fl\
        xAObP%2BiqPNJaXp2MbyHMQi0TPPoxOGID2zc1zZTYWEnAN3k44qr4ataXdY%2BI2vhKkQl\
        S5D%2BYwp%2F8JmhaAqirQDTOI%2FwmxJboPGi6Eqhk5MogHjXZUm2rrLXSqXCGpmkYc6d7\
        YtVCjB71h4P69%2BeSCvJrD%2FDmhUbx3gE8kWWNBqY4JsvzUz2QDwhzinbA8lYi%2FLEQ%\
        2BhT7yOk7oclqw5dGyZ6wB2KgDkra%2BCl5CPqyT%2Bc%2BqSB9%2FnKYbyTDdQDpDjvjaP\
        sbuEDqvwfcRkLNwMJqKsb0GOqUBq8ssASp8nzbcqJ%2FuNc0riJrA1j0pHx3pz%2FpI0kBX\
        0y3X235EL03Ner6k5EfknOsAAsl6WCPM3UkBAG29FJ2%2F5Ae2k%2BJUFmzZdMqOI%2B9hB\
        3WgRs6pkDM%2B6mSAp%2B06%2BvQD1g3N%2B5o6OVNfdcg5PA%2BEE9Eos%2Bsw%2B0IsvI\
        KzL8IeycJT4FqmLMiWrazr8nIxfi568YRY%2BQoAK%2F6WJJmgmHiZeL44xCFU&X-Amz-Si\
        gnature=ce9596f42c29877d1c014a91bb29b77704dda746e832fbe89908d9874bfb1a8\
        6&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-12T08:20:53.275Z"
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
UPDATE_TIME: "2025-02-12T07:22:46.506Z"
EXPIRY_TIME: "2025-02-12T08:22:33.058Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U7O2SOUY%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T072233Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCzywROjhQSeUTSoxiW%2Bw%2F6t%2F4umzrpwNB8F%2BUfWMjSOAIgbRygsTvDYYj7ejBabuEmqPtRNhJXHlPyUv%2FZG0MgMPEqiAQI6P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGuD3etJExpaHYRBNSrcA7R5iCegoWo1mSy483uADp6kLVJoHHCwNR0RSDaDQr2wQc3Hs%2BN4LiFTJNjcvG4wWSIf%2F8IXfqrz%2BiBviTYZtDDcvgXk0OMPJDcT4SktIk0UHrhf2PsdaboqHeO9%2Bjl3VezVeL6Hekcl3Vdgd%2FiXPNVkKYHpD9IR8RFE7VL%2BQC9jcksmO%2FWH59aO1ocnJ8d1015%2BIKpTaVHsprzr35GD6Q%2Bpr9Rtg4dOcdoil6SkOfnpRfjMe5eRG9hQI8kQQkfUdXvgbIfRl1WlzrCnat3YugAmXeVd6FkgZWEyuRcthuWHVV3ZYIqPKAG2IVLIajJlQVeeJiiOS1YBAvxf21F7QhFVYlocE8Y3UpbhLrSiuJlemFwxzPwGibSrFLRZm%2Bhs13G9CMs0HeNehpfBSmNm8PmtNoSj439EMXEz%2F%2FXM4EoQ%2FmHhMz%2B7eVGAf%2FwyggXk7JbL%2FfviVSAt5X6GvsWEf7%2FvlByZthMPafX0SIvgIRZ6Tsf5F%2BFLdkfBAgu3tFkoHjzIzIzmiIWdWucqOOvDgJGi5hsca7YMAI2575jZ%2BbW5dxULoz%2BjKcQD0dsHimpossGxBgt%2BnKKGn4nrP3DGs91qHEwn57hVdavj8obK7L1uL0%2F%2FOoy5DO5%2BtUPYMPqEsb0GOqUBytueFihD9KjRmuFb6DNNCwKxRvx%2FVIg6pAJwKv8adkVM3Tn3Jl30CEs%2BfgkwocGdCqDgKxYnxEatCvEJL0zyEcLznEEbnfR77dJg4FY3JOj72k5oKuqpW7u1mL694D4orgoUmrqog6yeNc75zj%2B2MiC8b5LyEOVMZOKm8O5Tph7UD5bPejE1zL0%2Ba3%2FV%2BS5%2F4Cxu0Hxv2gOxhd5awiv%2FRBb04DWV&X-Amz-Signature=e8b362c018e91e6a591659312b29f8a8cfb460373a602e430359f84832b30901&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U7O2SOUY%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T072233Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCzywROjhQSeUTSoxiW%2Bw%2F6t%2F4umzrpwNB8F%2BUfWMjSOAIgbRygsTvDYYj7ejBabuEmqPtRNhJXHlPyUv%2FZG0MgMPEqiAQI6P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGuD3etJExpaHYRBNSrcA7R5iCegoWo1mSy483uADp6kLVJoHHCwNR0RSDaDQr2wQc3Hs%2BN4LiFTJNjcvG4wWSIf%2F8IXfqrz%2BiBviTYZtDDcvgXk0OMPJDcT4SktIk0UHrhf2PsdaboqHeO9%2Bjl3VezVeL6Hekcl3Vdgd%2FiXPNVkKYHpD9IR8RFE7VL%2BQC9jcksmO%2FWH59aO1ocnJ8d1015%2BIKpTaVHsprzr35GD6Q%2Bpr9Rtg4dOcdoil6SkOfnpRfjMe5eRG9hQI8kQQkfUdXvgbIfRl1WlzrCnat3YugAmXeVd6FkgZWEyuRcthuWHVV3ZYIqPKAG2IVLIajJlQVeeJiiOS1YBAvxf21F7QhFVYlocE8Y3UpbhLrSiuJlemFwxzPwGibSrFLRZm%2Bhs13G9CMs0HeNehpfBSmNm8PmtNoSj439EMXEz%2F%2FXM4EoQ%2FmHhMz%2B7eVGAf%2FwyggXk7JbL%2FfviVSAt5X6GvsWEf7%2FvlByZthMPafX0SIvgIRZ6Tsf5F%2BFLdkfBAgu3tFkoHjzIzIzmiIWdWucqOOvDgJGi5hsca7YMAI2575jZ%2BbW5dxULoz%2BjKcQD0dsHimpossGxBgt%2BnKKGn4nrP3DGs91qHEwn57hVdavj8obK7L1uL0%2F%2FOoy5DO5%2BtUPYMPqEsb0GOqUBytueFihD9KjRmuFb6DNNCwKxRvx%2FVIg6pAJwKv8adkVM3Tn3Jl30CEs%2BfgkwocGdCqDgKxYnxEatCvEJL0zyEcLznEEbnfR77dJg4FY3JOj72k5oKuqpW7u1mL694D4orgoUmrqog6yeNc75zj%2B2MiC8b5LyEOVMZOKm8O5Tph7UD5bPejE1zL0%2Ba3%2FV%2BS5%2F4Cxu0Hxv2gOxhd5awiv%2FRBb04DWV&X-Amz-Signature=66e6c1ae1a77b751a16829bc3b7902566053b9e3e4bdb5f9c219d79a955b2e5a&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U7O2SOUY%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T072234Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCzywROjhQSeUTSoxiW%2Bw%2F6t%2F4umzrpwNB8F%2BUfWMjSOAIgbRygsTvDYYj7ejBabuEmqPtRNhJXHlPyUv%2FZG0MgMPEqiAQI6P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGuD3etJExpaHYRBNSrcA7R5iCegoWo1mSy483uADp6kLVJoHHCwNR0RSDaDQr2wQc3Hs%2BN4LiFTJNjcvG4wWSIf%2F8IXfqrz%2BiBviTYZtDDcvgXk0OMPJDcT4SktIk0UHrhf2PsdaboqHeO9%2Bjl3VezVeL6Hekcl3Vdgd%2FiXPNVkKYHpD9IR8RFE7VL%2BQC9jcksmO%2FWH59aO1ocnJ8d1015%2BIKpTaVHsprzr35GD6Q%2Bpr9Rtg4dOcdoil6SkOfnpRfjMe5eRG9hQI8kQQkfUdXvgbIfRl1WlzrCnat3YugAmXeVd6FkgZWEyuRcthuWHVV3ZYIqPKAG2IVLIajJlQVeeJiiOS1YBAvxf21F7QhFVYlocE8Y3UpbhLrSiuJlemFwxzPwGibSrFLRZm%2Bhs13G9CMs0HeNehpfBSmNm8PmtNoSj439EMXEz%2F%2FXM4EoQ%2FmHhMz%2B7eVGAf%2FwyggXk7JbL%2FfviVSAt5X6GvsWEf7%2FvlByZthMPafX0SIvgIRZ6Tsf5F%2BFLdkfBAgu3tFkoHjzIzIzmiIWdWucqOOvDgJGi5hsca7YMAI2575jZ%2BbW5dxULoz%2BjKcQD0dsHimpossGxBgt%2BnKKGn4nrP3DGs91qHEwn57hVdavj8obK7L1uL0%2F%2FOoy5DO5%2BtUPYMPqEsb0GOqUBytueFihD9KjRmuFb6DNNCwKxRvx%2FVIg6pAJwKv8adkVM3Tn3Jl30CEs%2BfgkwocGdCqDgKxYnxEatCvEJL0zyEcLznEEbnfR77dJg4FY3JOj72k5oKuqpW7u1mL694D4orgoUmrqog6yeNc75zj%2B2MiC8b5LyEOVMZOKm8O5Tph7UD5bPejE1zL0%2Ba3%2FV%2BS5%2F4Cxu0Hxv2gOxhd5awiv%2FRBb04DWV&X-Amz-Signature=0946b995af35c04d3c865297165a949785099abec5bc28b77c030b76f82a2996&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U7O2SOUY%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T072233Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCzywROjhQSeUTSoxiW%2Bw%2F6t%2F4umzrpwNB8F%2BUfWMjSOAIgbRygsTvDYYj7ejBabuEmqPtRNhJXHlPyUv%2FZG0MgMPEqiAQI6P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGuD3etJExpaHYRBNSrcA7R5iCegoWo1mSy483uADp6kLVJoHHCwNR0RSDaDQr2wQc3Hs%2BN4LiFTJNjcvG4wWSIf%2F8IXfqrz%2BiBviTYZtDDcvgXk0OMPJDcT4SktIk0UHrhf2PsdaboqHeO9%2Bjl3VezVeL6Hekcl3Vdgd%2FiXPNVkKYHpD9IR8RFE7VL%2BQC9jcksmO%2FWH59aO1ocnJ8d1015%2BIKpTaVHsprzr35GD6Q%2Bpr9Rtg4dOcdoil6SkOfnpRfjMe5eRG9hQI8kQQkfUdXvgbIfRl1WlzrCnat3YugAmXeVd6FkgZWEyuRcthuWHVV3ZYIqPKAG2IVLIajJlQVeeJiiOS1YBAvxf21F7QhFVYlocE8Y3UpbhLrSiuJlemFwxzPwGibSrFLRZm%2Bhs13G9CMs0HeNehpfBSmNm8PmtNoSj439EMXEz%2F%2FXM4EoQ%2FmHhMz%2B7eVGAf%2FwyggXk7JbL%2FfviVSAt5X6GvsWEf7%2FvlByZthMPafX0SIvgIRZ6Tsf5F%2BFLdkfBAgu3tFkoHjzIzIzmiIWdWucqOOvDgJGi5hsca7YMAI2575jZ%2BbW5dxULoz%2BjKcQD0dsHimpossGxBgt%2BnKKGn4nrP3DGs91qHEwn57hVdavj8obK7L1uL0%2F%2FOoy5DO5%2BtUPYMPqEsb0GOqUBytueFihD9KjRmuFb6DNNCwKxRvx%2FVIg6pAJwKv8adkVM3Tn3Jl30CEs%2BfgkwocGdCqDgKxYnxEatCvEJL0zyEcLznEEbnfR77dJg4FY3JOj72k5oKuqpW7u1mL694D4orgoUmrqog6yeNc75zj%2B2MiC8b5LyEOVMZOKm8O5Tph7UD5bPejE1zL0%2Ba3%2FV%2BS5%2F4Cxu0Hxv2gOxhd5awiv%2FRBb04DWV&X-Amz-Signature=ed14d653572a87213800b959d32fb93381c1be4ffd1e563b24e6fb634b27ac18&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U7O2SOUY%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T072234Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCzywROjhQSeUTSoxiW%2Bw%2F6t%2F4umzrpwNB8F%2BUfWMjSOAIgbRygsTvDYYj7ejBabuEmqPtRNhJXHlPyUv%2FZG0MgMPEqiAQI6P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGuD3etJExpaHYRBNSrcA7R5iCegoWo1mSy483uADp6kLVJoHHCwNR0RSDaDQr2wQc3Hs%2BN4LiFTJNjcvG4wWSIf%2F8IXfqrz%2BiBviTYZtDDcvgXk0OMPJDcT4SktIk0UHrhf2PsdaboqHeO9%2Bjl3VezVeL6Hekcl3Vdgd%2FiXPNVkKYHpD9IR8RFE7VL%2BQC9jcksmO%2FWH59aO1ocnJ8d1015%2BIKpTaVHsprzr35GD6Q%2Bpr9Rtg4dOcdoil6SkOfnpRfjMe5eRG9hQI8kQQkfUdXvgbIfRl1WlzrCnat3YugAmXeVd6FkgZWEyuRcthuWHVV3ZYIqPKAG2IVLIajJlQVeeJiiOS1YBAvxf21F7QhFVYlocE8Y3UpbhLrSiuJlemFwxzPwGibSrFLRZm%2Bhs13G9CMs0HeNehpfBSmNm8PmtNoSj439EMXEz%2F%2FXM4EoQ%2FmHhMz%2B7eVGAf%2FwyggXk7JbL%2FfviVSAt5X6GvsWEf7%2FvlByZthMPafX0SIvgIRZ6Tsf5F%2BFLdkfBAgu3tFkoHjzIzIzmiIWdWucqOOvDgJGi5hsca7YMAI2575jZ%2BbW5dxULoz%2BjKcQD0dsHimpossGxBgt%2BnKKGn4nrP3DGs91qHEwn57hVdavj8obK7L1uL0%2F%2FOoy5DO5%2BtUPYMPqEsb0GOqUBytueFihD9KjRmuFb6DNNCwKxRvx%2FVIg6pAJwKv8adkVM3Tn3Jl30CEs%2BfgkwocGdCqDgKxYnxEatCvEJL0zyEcLznEEbnfR77dJg4FY3JOj72k5oKuqpW7u1mL694D4orgoUmrqog6yeNc75zj%2B2MiC8b5LyEOVMZOKm8O5Tph7UD5bPejE1zL0%2Ba3%2FV%2BS5%2F4Cxu0Hxv2gOxhd5awiv%2FRBb04DWV&X-Amz-Signature=6cee46ac8b35cdcabc983d1610f72ffba059bae4739e06fddee7027b88da6995&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666IUFISAX%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T072234Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQC%2BjewbDuRiBIq976sA9dAQvtpYzGGL9WVFzKNoLFSXZAIgLbADawjd3bwAPOsrJ9EjU4YZLvexYmYjdMixl9550SwqiAQI6P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDAYFZJZ%2BXt%2BCuxUjJyrcAy60gnXtRrpF87ZVz5UVvKxSfwTvQakBDtr30ujiwt4O6Q%2BY4gMEYOChQVR6xrX668xzVII7oA7Ykg30NPxNWDUtPBg%2FegC1RUddSg0Ddn8OhgfX3gTs2uqvc4cNNhxgnzyuJbt%2BrfHeIxje%2FWVTJz1jy9I47ADQd1PYCorZrf8NicXqJFEIeDB4sC6YB8yXzsOACKgFycPGcCNkqJzfBm41IV5KfFHTPORm57kLea7VVic%2FQl02GcG%2FmEPMj0u7Uzd1V95o9yGSrc7QjePpWuIEPci4W7jXYpT%2F8bySLIQBaL4fZvz6aUYuycCMvAZsPioW0ldg3%2F%2F1Gt5b3kN7HVQcryeb%2B0ZlZNxr52zy7NvttTPdYQXDutKHf%2FO0fFUhBgoLPJYRzb7uDjmhHJdHveWb2S1YpRsUSXMf1qfMn0Yx3jBZB04psoJneocD4HnIYTB47OXE1eRbFkjOC9YkI5h6O1phXOi4ekb95VWrUazoYTrQwL7BdOf23xaiZyyFI35tn17yqAaBop0X71BRfKu3JmCINy3iTexrjWr%2F2kcW32EtMZKIkOGwCKDeUovuVLfAS4QMwb%2BXFMTPrQefE1zaTBsRNrsDmnGA0iSwInt54rDsGZH8HLaFJqSmMMGGsb0GOqUBIG7gg56t%2FszkXv9qbXIiP6to%2FdB8EFn8%2BSF5ds%2F29%2F%2Fq7YtCNssTQo00HrWZmSkf1Eg%2FydQuMAK%2Bp4b5EB8xQ1FzV3CsPGKqQ9EJzRMoZpXKUD%2BNg282OurMx%2B9HGF92EEEBokruEQgfN6M5tek%2F0DMzy%2BFLIKyEBFphCHrZHiIfMVlFVuX5Vm8ToiGvWgAW2alTEOEx3omckEIA61UGKQ%2B75rgA&X-Amz-Signature=1a6c7b79f58530a165e3df3e625c2e78c165fefc96048b559a91363c5f61f0aa&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46635NGVDLR%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T072235Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDl4CqeMux2EeYcL4AuYx6Z%2BlAV8%2FTfbqbKa8AhWN3oUQIgScvcKHnQ1W5gRnzsBx7R%2FAy2VGi71Yw0omeGAlf1ZXcqiAQI6P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDAwPbFOvZTpCLqL4DyrcA3hCiOqJ9Z5A0w78P5g12VWEy5h8CKOSz%2BFuGDh34t1cY5HretYAg9EJg6jW1G3zvEiEhLvpQ10x2wuUGv3jrM74ZQnJmjLenpr8NQgTQT%2FAhMM8IhfYuf%2B1O4CfANuUXEgN2dWBDK9AMNcnY4uNyjSI22SVuPc2cbUYV%2FWTOF900Q3eiDe7%2Feg740PsKdU3%2FzJiXUePaClg1E5qgkA0mCsCA1f1XrmBa4JPCUmMZAYQsGx8zU1EgVYo0RKICos1K5onUk28trqPgEHbYVrOyKq6gnkiiHeK7yZLYyU%2BQcn%2Fwp%2Bikotj7aEEOz00C11xgNTxyKVRsSAJ2cowMtAZT8%2FUZ5yTB0eFEZ4nAfCWRABrzc3oMnUrgVZCrEBsaCCSE1Fjxs3E%2BetbTpFUsmNBku5Ym%2F9nHniakee34KuCCJa1nKTLpKEf3m5Dx1vt%2FuJ%2BHseyXxiGH9DCiMKHvNpC33Hi0ydBqXU0xjP3TEYhntorP2N4OlYAX4SeG7h004Mgmsdh7UdR9ZiBYlReTHTv8pm%2FzRtKG2D0gZ2zQoPwScaUepyvmqQfhajcZP0bH%2FDu25sSOvSucg%2FPiLMONph1KdsAB5DKTb92cDi7rIwGwyGWNJ5bE%2Bov45Mo9c98MN6Lsb0GOqUBJPWfIw2Ly0oB0yGJ3dUDeV22gkk%2FO8prHQRYUu1HnTDbkAtR6Y1wuiGof%2BOM%2FAjD0NxmsiQ7Sr59ioY43%2BBtCG9MvBHbMlkVYX3wpJZZjVi%2BgBaJsp3f%2BmBXB6HST3Vf904kk30Wtud%2BRDda2KLH0loWe4GGpYvCEx8ghCKAHkPAP9MSoQ54kEroNEaDndvaJZvCEO22W2Fh9ToYtnvHAulfP002&X-Amz-Signature=31b82e26ebfaf91cc20d3dcc2009a3721c9dcc8b9a19c8555b66d6c5f732e194&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U7O2SOUY%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T072234Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCzywROjhQSeUTSoxiW%2Bw%2F6t%2F4umzrpwNB8F%2BUfWMjSOAIgbRygsTvDYYj7ejBabuEmqPtRNhJXHlPyUv%2FZG0MgMPEqiAQI6P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGuD3etJExpaHYRBNSrcA7R5iCegoWo1mSy483uADp6kLVJoHHCwNR0RSDaDQr2wQc3Hs%2BN4LiFTJNjcvG4wWSIf%2F8IXfqrz%2BiBviTYZtDDcvgXk0OMPJDcT4SktIk0UHrhf2PsdaboqHeO9%2Bjl3VezVeL6Hekcl3Vdgd%2FiXPNVkKYHpD9IR8RFE7VL%2BQC9jcksmO%2FWH59aO1ocnJ8d1015%2BIKpTaVHsprzr35GD6Q%2Bpr9Rtg4dOcdoil6SkOfnpRfjMe5eRG9hQI8kQQkfUdXvgbIfRl1WlzrCnat3YugAmXeVd6FkgZWEyuRcthuWHVV3ZYIqPKAG2IVLIajJlQVeeJiiOS1YBAvxf21F7QhFVYlocE8Y3UpbhLrSiuJlemFwxzPwGibSrFLRZm%2Bhs13G9CMs0HeNehpfBSmNm8PmtNoSj439EMXEz%2F%2FXM4EoQ%2FmHhMz%2B7eVGAf%2FwyggXk7JbL%2FfviVSAt5X6GvsWEf7%2FvlByZthMPafX0SIvgIRZ6Tsf5F%2BFLdkfBAgu3tFkoHjzIzIzmiIWdWucqOOvDgJGi5hsca7YMAI2575jZ%2BbW5dxULoz%2BjKcQD0dsHimpossGxBgt%2BnKKGn4nrP3DGs91qHEwn57hVdavj8obK7L1uL0%2F%2FOoy5DO5%2BtUPYMPqEsb0GOqUBytueFihD9KjRmuFb6DNNCwKxRvx%2FVIg6pAJwKv8adkVM3Tn3Jl30CEs%2BfgkwocGdCqDgKxYnxEatCvEJL0zyEcLznEEbnfR77dJg4FY3JOj72k5oKuqpW7u1mL694D4orgoUmrqog6yeNc75zj%2B2MiC8b5LyEOVMZOKm8O5Tph7UD5bPejE1zL0%2Ba3%2FV%2BS5%2F4Cxu0Hxv2gOxhd5awiv%2FRBb04DWV&X-Amz-Signature=c35ea77b0ad74cb136f45c52d5f3d6b9615891ab63119db07f7680d503513db1&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U7O2SOUY%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T072234Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCzywROjhQSeUTSoxiW%2Bw%2F6t%2F4umzrpwNB8F%2BUfWMjSOAIgbRygsTvDYYj7ejBabuEmqPtRNhJXHlPyUv%2FZG0MgMPEqiAQI6P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGuD3etJExpaHYRBNSrcA7R5iCegoWo1mSy483uADp6kLVJoHHCwNR0RSDaDQr2wQc3Hs%2BN4LiFTJNjcvG4wWSIf%2F8IXfqrz%2BiBviTYZtDDcvgXk0OMPJDcT4SktIk0UHrhf2PsdaboqHeO9%2Bjl3VezVeL6Hekcl3Vdgd%2FiXPNVkKYHpD9IR8RFE7VL%2BQC9jcksmO%2FWH59aO1ocnJ8d1015%2BIKpTaVHsprzr35GD6Q%2Bpr9Rtg4dOcdoil6SkOfnpRfjMe5eRG9hQI8kQQkfUdXvgbIfRl1WlzrCnat3YugAmXeVd6FkgZWEyuRcthuWHVV3ZYIqPKAG2IVLIajJlQVeeJiiOS1YBAvxf21F7QhFVYlocE8Y3UpbhLrSiuJlemFwxzPwGibSrFLRZm%2Bhs13G9CMs0HeNehpfBSmNm8PmtNoSj439EMXEz%2F%2FXM4EoQ%2FmHhMz%2B7eVGAf%2FwyggXk7JbL%2FfviVSAt5X6GvsWEf7%2FvlByZthMPafX0SIvgIRZ6Tsf5F%2BFLdkfBAgu3tFkoHjzIzIzmiIWdWucqOOvDgJGi5hsca7YMAI2575jZ%2BbW5dxULoz%2BjKcQD0dsHimpossGxBgt%2BnKKGn4nrP3DGs91qHEwn57hVdavj8obK7L1uL0%2F%2FOoy5DO5%2BtUPYMPqEsb0GOqUBytueFihD9KjRmuFb6DNNCwKxRvx%2FVIg6pAJwKv8adkVM3Tn3Jl30CEs%2BfgkwocGdCqDgKxYnxEatCvEJL0zyEcLznEEbnfR77dJg4FY3JOj72k5oKuqpW7u1mL694D4orgoUmrqog6yeNc75zj%2B2MiC8b5LyEOVMZOKm8O5Tph7UD5bPejE1zL0%2Ba3%2FV%2BS5%2F4Cxu0Hxv2gOxhd5awiv%2FRBb04DWV&X-Amz-Signature=6e539faac4858a59e6c30fa1b66c5c9e528aa270d8f861264fab0d498fc8e66f&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U7O2SOUY%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T072234Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCzywROjhQSeUTSoxiW%2Bw%2F6t%2F4umzrpwNB8F%2BUfWMjSOAIgbRygsTvDYYj7ejBabuEmqPtRNhJXHlPyUv%2FZG0MgMPEqiAQI6P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGuD3etJExpaHYRBNSrcA7R5iCegoWo1mSy483uADp6kLVJoHHCwNR0RSDaDQr2wQc3Hs%2BN4LiFTJNjcvG4wWSIf%2F8IXfqrz%2BiBviTYZtDDcvgXk0OMPJDcT4SktIk0UHrhf2PsdaboqHeO9%2Bjl3VezVeL6Hekcl3Vdgd%2FiXPNVkKYHpD9IR8RFE7VL%2BQC9jcksmO%2FWH59aO1ocnJ8d1015%2BIKpTaVHsprzr35GD6Q%2Bpr9Rtg4dOcdoil6SkOfnpRfjMe5eRG9hQI8kQQkfUdXvgbIfRl1WlzrCnat3YugAmXeVd6FkgZWEyuRcthuWHVV3ZYIqPKAG2IVLIajJlQVeeJiiOS1YBAvxf21F7QhFVYlocE8Y3UpbhLrSiuJlemFwxzPwGibSrFLRZm%2Bhs13G9CMs0HeNehpfBSmNm8PmtNoSj439EMXEz%2F%2FXM4EoQ%2FmHhMz%2B7eVGAf%2FwyggXk7JbL%2FfviVSAt5X6GvsWEf7%2FvlByZthMPafX0SIvgIRZ6Tsf5F%2BFLdkfBAgu3tFkoHjzIzIzmiIWdWucqOOvDgJGi5hsca7YMAI2575jZ%2BbW5dxULoz%2BjKcQD0dsHimpossGxBgt%2BnKKGn4nrP3DGs91qHEwn57hVdavj8obK7L1uL0%2F%2FOoy5DO5%2BtUPYMPqEsb0GOqUBytueFihD9KjRmuFb6DNNCwKxRvx%2FVIg6pAJwKv8adkVM3Tn3Jl30CEs%2BfgkwocGdCqDgKxYnxEatCvEJL0zyEcLznEEbnfR77dJg4FY3JOj72k5oKuqpW7u1mL694D4orgoUmrqog6yeNc75zj%2B2MiC8b5LyEOVMZOKm8O5Tph7UD5bPejE1zL0%2Ba3%2FV%2BS5%2F4Cxu0Hxv2gOxhd5awiv%2FRBb04DWV&X-Amz-Signature=260c41ea1b6730a4e90fbe7358514c89ae4282f7be0fd6a3e84ca35a32d150ac&X-Amz-SignedHeaders=host&x-id=GetObject)


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

