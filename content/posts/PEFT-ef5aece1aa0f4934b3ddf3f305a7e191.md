---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466V3PL2GO7%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250217T072253Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEEcaCXVzLXdlc3QtMiJGMEQCIGCMoB%2B6v9x1AWhCFVOVmoe1isuelAPdhiAYGKjd1Zb1AiBnF\
  zsDwC1w4m4SE6ON5S%2BpfyasLJxKez%2BUc1jQ6apqlCr%2FAwhwEAAaDDYzNzQyMzE4MzgwNSIM\
  fXtsn5SxkAT7XBMLKtwDNGBoyeQ5nYA7o6yvSFxh6c9ew9NAuyGA7sgwkyz%2BVRRKJo%2BaUgFvL\
  HGLjk20vxjrLH2mR8gOjY7FUSQ3YYD04ISZukT7Wa4d3QA%2FArvh3Tu3CzgeFPb6kIlP%2FVpMzJ\
  rL490ZAJI65YUs6h1VnWE22h%2FLdOFAVILHkYuQAQbr0hDwVdspAcmbFfqWQdk%2Fk1OBolIotI%\
  2BNZ3OSzT%2BJZDwn6Tw8z69VKHJzeKdOiQ1TQdhBXEj%2F56MasJ%2FW8MVkhfJ4DIb1VV1p3%2F\
  HPzRvmIc3YsAQaUKMOj%2B%2BMgkGGyQceak7MhakC0BzeWZ%2FcSRilIoCb75clqTT61Hr4K4G8t\
  EPE919h5YXfgRyyWOnDWP3QavNE6CY4IjA27rvrYaRt8ZxpczSe%2B1YNzsHS7bSXEdxS%2Fnnk%2\
  FUNcDSAxQ2VNKM4G87Ux%2F9%2BzFjTBOnWEIeKidU%2BhBtkrSt6B3G0EBf0dIkRDP0uE6fKTCQT\
  mAipAuCrPRvrQ6C6AX7pnQHaTLgt4Ygi%2FJ7fFC8sl02EMk%2BCtK41qWsmFNjyXNjrzMozb3nF4\
  O3Hq0Rx6Z9EyKCtqh8xemwbNcEhZ7zVYBP83YAEY1R7CCdLACyxYdzWX3JiW4D7yHLiX6d5%2BgdR\
  92EOi%2FNow06%2FLvQY6pgHAmCMFvFxXhaIfIDLasPmueideM7Ve%2Fug9ucQixm75ykFKxnaaOr\
  1uCwVt%2BKlSRKrL17WNMaqJFY3uQ2tdKjxophxPn0LC8afsGprIV9xmLpzC0WSTrqBje4UASWZ%2\
  BINLJyBBDN8wr%2FzQFZyLFR9p%2BhPqBVkvsYTSoQDGZ4jqnrW2juTypJECgPkuE5PgwQrBTKsEM\
  QQycKprGupOkYY2SMGfIMHQ7&X-Amz-Signature=486636f57a26c4dfc327b9ac47ba8ae3e50b\
  d565a83ec48d81020fc9cd739364&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466ZJ7ZXYO4%2F20250217%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250217T072143Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEEcaCXVzLXdlc3QtMiJHMEUCIQDoJg89ieC0%2BxbsEkL1QH1k6ZeGu\
        Q6APIFhVoavre%2F1GAIgOEviEWTxRcpTCn1Q0jQ1I9JCPXBANetZdMj6LuRClIAq%2FwMI\
        cBAAGgw2Mzc0MjMxODM4MDUiDPOM92Cytj1JLpoelSrcA9wJtlWejsDoGDBmaN54oFHEElM\
        4C7tUp0wX7Wm%2BFop4C8woZPWXekN49d7Jnj5g4C6Qf228YCqOu0ZCC7w%2BG8cRYfPKhR\
        ML%2FfU666XRPu4r3MgYi5Yg4UMGYTrEZIPR9sgEZtuAn%2BMqcXikmsFWk2jsg3z0fWQ%2\
        BjrTlkDDpGhncTS4%2FHI7j4KkvNsnQ0a75KORRuE9UoiqpASInxWDLBBg9Ivvp6LB97F2y\
        wwdDc4UxofGhMh89a%2By1LkAecPYzlNlqPGXPTJmRotVuPMpwQa%2FXR8ooMdXmy8MsXNS\
        PVUUhYjFmf6333YoJF%2BJd095ME4iJt1Dg9xZcrOQi632C84%2FyDbG7%2F%2B5IcDL1kB\
        lHPfuOt5iJix0KmjSnVjdjzRwK%2Fi5EbGLIlTWxbhrfaDwym8xTl26bUcgIhwz5qtpH8aJ\
        i7jwU1WMlpYn9FrnGNtPCn8gUSd9UEJy4xTvUEm%2BP5QqKeYv9E%2FEf5TzMzl4amOJAfs\
        Q8ZalvGDvah5dDdddThlt37z3XAKRQusHgr2Jfwzxe4NuQ4R0CgH3yReBbwptLcOWJi29aG\
        4ccKOt2Sl5PMHqxc46z%2BTDWEmPFZhDB1119A%2BnH810z%2FUrcTJeLW0xUM%2FC0IeU4\
        d9WPmtXzMJqvy70GOqUBaaWLuHc2gD2MyKGF5awJMdl2%2Fe88ft0Y2P1WAlkhLkuKSUTwo\
        ZRZusSjz%2BSBIatZMkxaPZZFvMnT2D58NnS7WCDn%2ByW95g2eTA3PQWUXMb9dwA5zy2Go\
        7xW6whejq%2BA2Tp3RMG7HMm9BUoj32TKdisYcpRfe7%2FZs%2B9VJq7n7JviXfbo749E7V\
        jErstXUBJeVTe1F5p215TA25UDb4YoBQ21VYi3b&X-Amz-Signature=db39e8428eea624\
        88ba279b45585b5ab82f63651174a1185daf79b79dccb5ad3&X-Amz-SignedHeaders=h\
        ost&x-id=GetObject"
      expiry_time: "2025-02-17T08:21:43.590Z"
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
UPDATE_TIME: "2025-02-17T07:23:00.396Z"
EXPIRY_TIME: "2025-02-17T08:22:50.471Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466STVNSLBE%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T072251Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEcaCXVzLXdlc3QtMiJIMEYCIQC74ZkVzmvbtzpIA%2FusmvfumqJvWBSwtCHBdEXqF0S%2BnQIhAPOR3WmZuLw8qzydOf0XLIR9AyhF3yqgHg9ZKvXyfh5UKv8DCHAQABoMNjM3NDIzMTgzODA1IgyaiaH8Kb5H0UYNBZMq3AO%2F2mTULb3p2OUGIX3HE8PbIQcCgk4I4MAaZiDd7GLcpUWC6piurlV6omfZEw6yLxHf2mO9JqTvduxEzcSuL%2FxlO5R%2BB9de8bBdn3jwuGtfAtj0W%2FfJvaiP%2FbCk8DfNcmEISEeNXZRWafCwFjtnyuAEbIv88N975r0ueNq5a2luknJXYxofd2fmDLvND9t4%2FHrVhwQCTbRkpHwupA6mQIdmdZSPRFw2DTbX%2BzIWmxFLC5NNJT7nw0asY7I4OXXxWEzsZFdaRMDvV%2F%2B8fhG32btJ8zeyj3pfaE3wb%2Fu%2FAM54Zlj0Ut%2Bgtow4grkfsjDkvWslxBJkfnKgckTeR%2B5OxoDaH2O%2BeHsg362NCo9D8JRjzsCfdBgHNZQf5fx4lwOk4SYhf%2BZ7dry1xmWLbUuvlGILc0D0Oaxm6BxmO8eb55%2Bta2Ow1AumVQjqHr4gry%2Fz7Wbp%2B8ml3UJ1EE187AoIweHfN4VfTTsimRDV4BBlNrdK2jUVHoZalz18liMw3ShZ3bkVb9yTuVNgniwCI5XXYlq%2BGMbNrhk697ySt9HQy6AwtdshwDhb1RVt0eLCGLMWBUkWHpCoAOg%2BhWtJolq28Ug2mcaeKqga%2BPvP2DWvbWkndisnbd4Fc%2FjUqgpGMDCSsMu9BjqkAQky8TJf%2BLRU9KSPeG3X2JBZTC92lGeY4KNNoHZw2CKGQM%2BSj4p80LhMbJH0fP7JLrDe2RLb2Ft3CfsazuY8YUAIA%2FJCOsaayYOpgqobOJGmL6rnfG01dUwuK4iZQi1tZ30gmcx6TB%2B%2ByRU20Z0UMWTzz8D7ExqGanzD8kDDa4ZUDPibjYWPCnJ3p2ZIF7VoiJ%2BvdNpHpLn1G8vDvLjzk4pkal5i&X-Amz-Signature=9b7d0aee0e07722f2d6f68cd9a89eca27d0baacb4fa4841e2d0ff668bbf7528e&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466STVNSLBE%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T072251Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEcaCXVzLXdlc3QtMiJIMEYCIQC74ZkVzmvbtzpIA%2FusmvfumqJvWBSwtCHBdEXqF0S%2BnQIhAPOR3WmZuLw8qzydOf0XLIR9AyhF3yqgHg9ZKvXyfh5UKv8DCHAQABoMNjM3NDIzMTgzODA1IgyaiaH8Kb5H0UYNBZMq3AO%2F2mTULb3p2OUGIX3HE8PbIQcCgk4I4MAaZiDd7GLcpUWC6piurlV6omfZEw6yLxHf2mO9JqTvduxEzcSuL%2FxlO5R%2BB9de8bBdn3jwuGtfAtj0W%2FfJvaiP%2FbCk8DfNcmEISEeNXZRWafCwFjtnyuAEbIv88N975r0ueNq5a2luknJXYxofd2fmDLvND9t4%2FHrVhwQCTbRkpHwupA6mQIdmdZSPRFw2DTbX%2BzIWmxFLC5NNJT7nw0asY7I4OXXxWEzsZFdaRMDvV%2F%2B8fhG32btJ8zeyj3pfaE3wb%2Fu%2FAM54Zlj0Ut%2Bgtow4grkfsjDkvWslxBJkfnKgckTeR%2B5OxoDaH2O%2BeHsg362NCo9D8JRjzsCfdBgHNZQf5fx4lwOk4SYhf%2BZ7dry1xmWLbUuvlGILc0D0Oaxm6BxmO8eb55%2Bta2Ow1AumVQjqHr4gry%2Fz7Wbp%2B8ml3UJ1EE187AoIweHfN4VfTTsimRDV4BBlNrdK2jUVHoZalz18liMw3ShZ3bkVb9yTuVNgniwCI5XXYlq%2BGMbNrhk697ySt9HQy6AwtdshwDhb1RVt0eLCGLMWBUkWHpCoAOg%2BhWtJolq28Ug2mcaeKqga%2BPvP2DWvbWkndisnbd4Fc%2FjUqgpGMDCSsMu9BjqkAQky8TJf%2BLRU9KSPeG3X2JBZTC92lGeY4KNNoHZw2CKGQM%2BSj4p80LhMbJH0fP7JLrDe2RLb2Ft3CfsazuY8YUAIA%2FJCOsaayYOpgqobOJGmL6rnfG01dUwuK4iZQi1tZ30gmcx6TB%2B%2ByRU20Z0UMWTzz8D7ExqGanzD8kDDa4ZUDPibjYWPCnJ3p2ZIF7VoiJ%2BvdNpHpLn1G8vDvLjzk4pkal5i&X-Amz-Signature=2644a51ad3bf691be1ca950baa0f083be4039a425ffba7087c7b682b9b6d2619&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466STVNSLBE%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T072251Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEcaCXVzLXdlc3QtMiJIMEYCIQC74ZkVzmvbtzpIA%2FusmvfumqJvWBSwtCHBdEXqF0S%2BnQIhAPOR3WmZuLw8qzydOf0XLIR9AyhF3yqgHg9ZKvXyfh5UKv8DCHAQABoMNjM3NDIzMTgzODA1IgyaiaH8Kb5H0UYNBZMq3AO%2F2mTULb3p2OUGIX3HE8PbIQcCgk4I4MAaZiDd7GLcpUWC6piurlV6omfZEw6yLxHf2mO9JqTvduxEzcSuL%2FxlO5R%2BB9de8bBdn3jwuGtfAtj0W%2FfJvaiP%2FbCk8DfNcmEISEeNXZRWafCwFjtnyuAEbIv88N975r0ueNq5a2luknJXYxofd2fmDLvND9t4%2FHrVhwQCTbRkpHwupA6mQIdmdZSPRFw2DTbX%2BzIWmxFLC5NNJT7nw0asY7I4OXXxWEzsZFdaRMDvV%2F%2B8fhG32btJ8zeyj3pfaE3wb%2Fu%2FAM54Zlj0Ut%2Bgtow4grkfsjDkvWslxBJkfnKgckTeR%2B5OxoDaH2O%2BeHsg362NCo9D8JRjzsCfdBgHNZQf5fx4lwOk4SYhf%2BZ7dry1xmWLbUuvlGILc0D0Oaxm6BxmO8eb55%2Bta2Ow1AumVQjqHr4gry%2Fz7Wbp%2B8ml3UJ1EE187AoIweHfN4VfTTsimRDV4BBlNrdK2jUVHoZalz18liMw3ShZ3bkVb9yTuVNgniwCI5XXYlq%2BGMbNrhk697ySt9HQy6AwtdshwDhb1RVt0eLCGLMWBUkWHpCoAOg%2BhWtJolq28Ug2mcaeKqga%2BPvP2DWvbWkndisnbd4Fc%2FjUqgpGMDCSsMu9BjqkAQky8TJf%2BLRU9KSPeG3X2JBZTC92lGeY4KNNoHZw2CKGQM%2BSj4p80LhMbJH0fP7JLrDe2RLb2Ft3CfsazuY8YUAIA%2FJCOsaayYOpgqobOJGmL6rnfG01dUwuK4iZQi1tZ30gmcx6TB%2B%2ByRU20Z0UMWTzz8D7ExqGanzD8kDDa4ZUDPibjYWPCnJ3p2ZIF7VoiJ%2BvdNpHpLn1G8vDvLjzk4pkal5i&X-Amz-Signature=d0e8b6dac1cd588819bc2d7c854d8dbecb678f6f1b5b3ab7500dd41221b094ac&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466STVNSLBE%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T072251Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEcaCXVzLXdlc3QtMiJIMEYCIQC74ZkVzmvbtzpIA%2FusmvfumqJvWBSwtCHBdEXqF0S%2BnQIhAPOR3WmZuLw8qzydOf0XLIR9AyhF3yqgHg9ZKvXyfh5UKv8DCHAQABoMNjM3NDIzMTgzODA1IgyaiaH8Kb5H0UYNBZMq3AO%2F2mTULb3p2OUGIX3HE8PbIQcCgk4I4MAaZiDd7GLcpUWC6piurlV6omfZEw6yLxHf2mO9JqTvduxEzcSuL%2FxlO5R%2BB9de8bBdn3jwuGtfAtj0W%2FfJvaiP%2FbCk8DfNcmEISEeNXZRWafCwFjtnyuAEbIv88N975r0ueNq5a2luknJXYxofd2fmDLvND9t4%2FHrVhwQCTbRkpHwupA6mQIdmdZSPRFw2DTbX%2BzIWmxFLC5NNJT7nw0asY7I4OXXxWEzsZFdaRMDvV%2F%2B8fhG32btJ8zeyj3pfaE3wb%2Fu%2FAM54Zlj0Ut%2Bgtow4grkfsjDkvWslxBJkfnKgckTeR%2B5OxoDaH2O%2BeHsg362NCo9D8JRjzsCfdBgHNZQf5fx4lwOk4SYhf%2BZ7dry1xmWLbUuvlGILc0D0Oaxm6BxmO8eb55%2Bta2Ow1AumVQjqHr4gry%2Fz7Wbp%2B8ml3UJ1EE187AoIweHfN4VfTTsimRDV4BBlNrdK2jUVHoZalz18liMw3ShZ3bkVb9yTuVNgniwCI5XXYlq%2BGMbNrhk697ySt9HQy6AwtdshwDhb1RVt0eLCGLMWBUkWHpCoAOg%2BhWtJolq28Ug2mcaeKqga%2BPvP2DWvbWkndisnbd4Fc%2FjUqgpGMDCSsMu9BjqkAQky8TJf%2BLRU9KSPeG3X2JBZTC92lGeY4KNNoHZw2CKGQM%2BSj4p80LhMbJH0fP7JLrDe2RLb2Ft3CfsazuY8YUAIA%2FJCOsaayYOpgqobOJGmL6rnfG01dUwuK4iZQi1tZ30gmcx6TB%2B%2ByRU20Z0UMWTzz8D7ExqGanzD8kDDa4ZUDPibjYWPCnJ3p2ZIF7VoiJ%2BvdNpHpLn1G8vDvLjzk4pkal5i&X-Amz-Signature=aefbaaecac2a87197966c3bf38715dd95edecff5186420f18a7605904052ee01&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466STVNSLBE%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T072251Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEcaCXVzLXdlc3QtMiJIMEYCIQC74ZkVzmvbtzpIA%2FusmvfumqJvWBSwtCHBdEXqF0S%2BnQIhAPOR3WmZuLw8qzydOf0XLIR9AyhF3yqgHg9ZKvXyfh5UKv8DCHAQABoMNjM3NDIzMTgzODA1IgyaiaH8Kb5H0UYNBZMq3AO%2F2mTULb3p2OUGIX3HE8PbIQcCgk4I4MAaZiDd7GLcpUWC6piurlV6omfZEw6yLxHf2mO9JqTvduxEzcSuL%2FxlO5R%2BB9de8bBdn3jwuGtfAtj0W%2FfJvaiP%2FbCk8DfNcmEISEeNXZRWafCwFjtnyuAEbIv88N975r0ueNq5a2luknJXYxofd2fmDLvND9t4%2FHrVhwQCTbRkpHwupA6mQIdmdZSPRFw2DTbX%2BzIWmxFLC5NNJT7nw0asY7I4OXXxWEzsZFdaRMDvV%2F%2B8fhG32btJ8zeyj3pfaE3wb%2Fu%2FAM54Zlj0Ut%2Bgtow4grkfsjDkvWslxBJkfnKgckTeR%2B5OxoDaH2O%2BeHsg362NCo9D8JRjzsCfdBgHNZQf5fx4lwOk4SYhf%2BZ7dry1xmWLbUuvlGILc0D0Oaxm6BxmO8eb55%2Bta2Ow1AumVQjqHr4gry%2Fz7Wbp%2B8ml3UJ1EE187AoIweHfN4VfTTsimRDV4BBlNrdK2jUVHoZalz18liMw3ShZ3bkVb9yTuVNgniwCI5XXYlq%2BGMbNrhk697ySt9HQy6AwtdshwDhb1RVt0eLCGLMWBUkWHpCoAOg%2BhWtJolq28Ug2mcaeKqga%2BPvP2DWvbWkndisnbd4Fc%2FjUqgpGMDCSsMu9BjqkAQky8TJf%2BLRU9KSPeG3X2JBZTC92lGeY4KNNoHZw2CKGQM%2BSj4p80LhMbJH0fP7JLrDe2RLb2Ft3CfsazuY8YUAIA%2FJCOsaayYOpgqobOJGmL6rnfG01dUwuK4iZQi1tZ30gmcx6TB%2B%2ByRU20Z0UMWTzz8D7ExqGanzD8kDDa4ZUDPibjYWPCnJ3p2ZIF7VoiJ%2BvdNpHpLn1G8vDvLjzk4pkal5i&X-Amz-Signature=a8a25fc8e258aa851f424dc5e54523c5d9d37f8a283f415f23e43ff71d934156&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YI7YVE23%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T072251Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEcaCXVzLXdlc3QtMiJIMEYCIQDTMtTeEqMbhACMbr6T4FM3n8tW7gQhlLptErgjLR%2BkPwIhALyFKEEMfAcWFgoQiyz7331k8Gd7lvP5WZFtze4ySrF9Kv8DCHAQABoMNjM3NDIzMTgzODA1IgxkO9kkmtYhAQVt0PMq3APM068HWcjRd3iSeNKPFRk9FBtoQBMR6uJsWxXRzwIycjJ0H4QY%2Bu5kr%2FVLDzPAXIdQhxDyWfuujn8Vbx6D9s6r7QNavrsHm7rnnev30gxh700zZZo3PHN0ygpdicHBYWU%2BfqKd2CZ17D3c6evUbaA1e2gWRcAqa%2B%2BYvUe5QlAP%2FaaI3%2Bnv45yNqSd4gX5OJnxIsj%2FxOosqY%2B5HykTL5%2FcpjxcZGL1xg6SAR6NZkJO5XrRaW5u6OSDRF9H9NIJvP4ke0uNEipvTsr9Jk%2Fz2aLFsYG3et63fQg5XtUKGk0uy7FwpdROZPK3AyiiaJKNsCdq%2BBuFhgvBl6S308rAUrhBtTzKSToa%2B6azQkKJ912nXdTiwiBifRWaqXLo5Zgcqptx235jxHPi3jjG5kU%2B1440%2BtqhTWEGwCLyUklxYEe9yFQb6p4w6M%2Fv2KZtbId3u4R5zA0I1JEKStdrtecVrVo44ixAPzYKFYvuupycFJax4YnKEyfRcXNjStfR%2B%2BYjKEl8qyqjwtlTwFBtfBK41JJOJtvhw14%2FZobPLBVzzLvsrO7nl9J8vIA6Mhry%2FqvtwqEZka3VyORGf4D6ThzqJ0TL%2Fhkrkl79CD3e9PFWoICsGmKOyavJHzxoFj6XMsTDTr8u9BjqkAVyPfDoaH%2FXiIEpPdZ4QdUnC5SN%2FTKc9CgIfHJrX%2FoTgc7zkRtC%2Bt7g0HGKOyys%2Fe0MdKG7gf%2FCxQpCKz7g7lGLirhi3mbpu7G0PpsTitYUkpVbFsn6ciWOVQuQi%2BJF4Md%2F1CdWdcJMmRzqRkZVboVv8yYhIJKTz5%2Fwj2%2BCAnZpmvMhyhBw%2BnmZjhXlPbDYzIurhVl4b6TZ6B5DIru83BRd1j%2BHP&X-Amz-Signature=ce9012c2c932eb91cdd1d09fd6ad4f86367bcb171755adf4b5f4df7fd81784ea&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZM6JKIDA%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T072253Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEcaCXVzLXdlc3QtMiJIMEYCIQCLd7x3Zm6oNxNNJ14qCo5glmTYumJ6F0zQ95YaTfdHpgIhANYdLjDXMI80f3GzpXtE5MZwWJ%2Fyy7Y6X7dnw6hCS%2BptKv8DCHAQABoMNjM3NDIzMTgzODA1IgzboOLghH1JmSRkC3gq3AOTJXpecPSU9mtgcl7LbJ1ae%2FAAol1jP%2F4fHIv5jU9FohPQ0wpgIRvCOPGCfQteaodg%2FYo%2BO1Pbx4gg7Z9wZG7x%2B2Ksag7vDRjT89vbvuPh4o7Beyryyw8%2BOE4IcyEnAU8PXw3ejaZ7RApIv0i0z%2Fw%2F0xfhPJ4LU0zAJTBQAq70OKWt700I5YZalxg2l04obPfQubVcUHKpIyFDO%2Bdvb5XoIUWElRLkOCGQfBxGSaSjt3KBTbOoEMlQK7PsRdiEpHd1Cc0Onh151N7UHjaja9DNmzthES0Z9Un9zKWHvuq6dooZDOJhrKnS7rB4Q0tSQcXm3Fv3n9Q8BAaVV5mauO%2B9QfftQ%2FlX%2F5hkHC7YiKAUv%2Fm694kqp06mvp%2B18GfSRt9%2B%2F5BD6tFk27cOUWC3DhwFhSMgS6Rncw34%2BGXLIkHAU45RhpBISjKD%2FgXnq4Wf0X2f0ButByfmREY3JU2kcmFS16jHqFDTIXMP%2B32iMEX3eo1%2F13mXOGsg4Ku4L0r30G30tf2atiZk1T6Q72jL5PThsHyv9lKOcVAkLpYOYxpy2bxFiLqoItNhUV%2Fe1Zbq5aVpWOd6UvEn7ooM0miKc5TSTZpYEVeRF%2BXlZ%2FokEKz3BUTpjwycoXyWeP9RmjCLr8u9BjqkAbEgftX1Kn1%2BCizlQeDc%2BYxFTuPWFs096knHURLP%2B8SGwovEXliqCTJucZaRCIgtIPT7DAvr9vrlxP03z7lLN2NgGzMc%2BygOz4Ho1sU4yKyS0qkeiYLGL4lssNgAuMdej6i%2FYTzXaE4JgB%2BKdO%2FNEY51kAsRQTqGpd6aoogurKjat6eNGR53oORM6DMdiyHmHH4bxIsXsh4%2BFmRyKleTeLbnyEWd&X-Amz-Signature=c1dc2038727498594ac3d514a0cd672a65307481a6dd87295e9f3418362450f5&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466STVNSLBE%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T072251Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEcaCXVzLXdlc3QtMiJIMEYCIQC74ZkVzmvbtzpIA%2FusmvfumqJvWBSwtCHBdEXqF0S%2BnQIhAPOR3WmZuLw8qzydOf0XLIR9AyhF3yqgHg9ZKvXyfh5UKv8DCHAQABoMNjM3NDIzMTgzODA1IgyaiaH8Kb5H0UYNBZMq3AO%2F2mTULb3p2OUGIX3HE8PbIQcCgk4I4MAaZiDd7GLcpUWC6piurlV6omfZEw6yLxHf2mO9JqTvduxEzcSuL%2FxlO5R%2BB9de8bBdn3jwuGtfAtj0W%2FfJvaiP%2FbCk8DfNcmEISEeNXZRWafCwFjtnyuAEbIv88N975r0ueNq5a2luknJXYxofd2fmDLvND9t4%2FHrVhwQCTbRkpHwupA6mQIdmdZSPRFw2DTbX%2BzIWmxFLC5NNJT7nw0asY7I4OXXxWEzsZFdaRMDvV%2F%2B8fhG32btJ8zeyj3pfaE3wb%2Fu%2FAM54Zlj0Ut%2Bgtow4grkfsjDkvWslxBJkfnKgckTeR%2B5OxoDaH2O%2BeHsg362NCo9D8JRjzsCfdBgHNZQf5fx4lwOk4SYhf%2BZ7dry1xmWLbUuvlGILc0D0Oaxm6BxmO8eb55%2Bta2Ow1AumVQjqHr4gry%2Fz7Wbp%2B8ml3UJ1EE187AoIweHfN4VfTTsimRDV4BBlNrdK2jUVHoZalz18liMw3ShZ3bkVb9yTuVNgniwCI5XXYlq%2BGMbNrhk697ySt9HQy6AwtdshwDhb1RVt0eLCGLMWBUkWHpCoAOg%2BhWtJolq28Ug2mcaeKqga%2BPvP2DWvbWkndisnbd4Fc%2FjUqgpGMDCSsMu9BjqkAQky8TJf%2BLRU9KSPeG3X2JBZTC92lGeY4KNNoHZw2CKGQM%2BSj4p80LhMbJH0fP7JLrDe2RLb2Ft3CfsazuY8YUAIA%2FJCOsaayYOpgqobOJGmL6rnfG01dUwuK4iZQi1tZ30gmcx6TB%2B%2ByRU20Z0UMWTzz8D7ExqGanzD8kDDa4ZUDPibjYWPCnJ3p2ZIF7VoiJ%2BvdNpHpLn1G8vDvLjzk4pkal5i&X-Amz-Signature=2f8e77e93adbbb0eb57f02889659173cad0bfa26da115d291fb6b661bd9358d1&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466STVNSLBE%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T072251Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEcaCXVzLXdlc3QtMiJIMEYCIQC74ZkVzmvbtzpIA%2FusmvfumqJvWBSwtCHBdEXqF0S%2BnQIhAPOR3WmZuLw8qzydOf0XLIR9AyhF3yqgHg9ZKvXyfh5UKv8DCHAQABoMNjM3NDIzMTgzODA1IgyaiaH8Kb5H0UYNBZMq3AO%2F2mTULb3p2OUGIX3HE8PbIQcCgk4I4MAaZiDd7GLcpUWC6piurlV6omfZEw6yLxHf2mO9JqTvduxEzcSuL%2FxlO5R%2BB9de8bBdn3jwuGtfAtj0W%2FfJvaiP%2FbCk8DfNcmEISEeNXZRWafCwFjtnyuAEbIv88N975r0ueNq5a2luknJXYxofd2fmDLvND9t4%2FHrVhwQCTbRkpHwupA6mQIdmdZSPRFw2DTbX%2BzIWmxFLC5NNJT7nw0asY7I4OXXxWEzsZFdaRMDvV%2F%2B8fhG32btJ8zeyj3pfaE3wb%2Fu%2FAM54Zlj0Ut%2Bgtow4grkfsjDkvWslxBJkfnKgckTeR%2B5OxoDaH2O%2BeHsg362NCo9D8JRjzsCfdBgHNZQf5fx4lwOk4SYhf%2BZ7dry1xmWLbUuvlGILc0D0Oaxm6BxmO8eb55%2Bta2Ow1AumVQjqHr4gry%2Fz7Wbp%2B8ml3UJ1EE187AoIweHfN4VfTTsimRDV4BBlNrdK2jUVHoZalz18liMw3ShZ3bkVb9yTuVNgniwCI5XXYlq%2BGMbNrhk697ySt9HQy6AwtdshwDhb1RVt0eLCGLMWBUkWHpCoAOg%2BhWtJolq28Ug2mcaeKqga%2BPvP2DWvbWkndisnbd4Fc%2FjUqgpGMDCSsMu9BjqkAQky8TJf%2BLRU9KSPeG3X2JBZTC92lGeY4KNNoHZw2CKGQM%2BSj4p80LhMbJH0fP7JLrDe2RLb2Ft3CfsazuY8YUAIA%2FJCOsaayYOpgqobOJGmL6rnfG01dUwuK4iZQi1tZ30gmcx6TB%2B%2ByRU20Z0UMWTzz8D7ExqGanzD8kDDa4ZUDPibjYWPCnJ3p2ZIF7VoiJ%2BvdNpHpLn1G8vDvLjzk4pkal5i&X-Amz-Signature=a40b79fc06a7b577922e64e074bef2c65f97fbb92f871b3158172521a6ed090c&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466STVNSLBE%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T072251Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEcaCXVzLXdlc3QtMiJIMEYCIQC74ZkVzmvbtzpIA%2FusmvfumqJvWBSwtCHBdEXqF0S%2BnQIhAPOR3WmZuLw8qzydOf0XLIR9AyhF3yqgHg9ZKvXyfh5UKv8DCHAQABoMNjM3NDIzMTgzODA1IgyaiaH8Kb5H0UYNBZMq3AO%2F2mTULb3p2OUGIX3HE8PbIQcCgk4I4MAaZiDd7GLcpUWC6piurlV6omfZEw6yLxHf2mO9JqTvduxEzcSuL%2FxlO5R%2BB9de8bBdn3jwuGtfAtj0W%2FfJvaiP%2FbCk8DfNcmEISEeNXZRWafCwFjtnyuAEbIv88N975r0ueNq5a2luknJXYxofd2fmDLvND9t4%2FHrVhwQCTbRkpHwupA6mQIdmdZSPRFw2DTbX%2BzIWmxFLC5NNJT7nw0asY7I4OXXxWEzsZFdaRMDvV%2F%2B8fhG32btJ8zeyj3pfaE3wb%2Fu%2FAM54Zlj0Ut%2Bgtow4grkfsjDkvWslxBJkfnKgckTeR%2B5OxoDaH2O%2BeHsg362NCo9D8JRjzsCfdBgHNZQf5fx4lwOk4SYhf%2BZ7dry1xmWLbUuvlGILc0D0Oaxm6BxmO8eb55%2Bta2Ow1AumVQjqHr4gry%2Fz7Wbp%2B8ml3UJ1EE187AoIweHfN4VfTTsimRDV4BBlNrdK2jUVHoZalz18liMw3ShZ3bkVb9yTuVNgniwCI5XXYlq%2BGMbNrhk697ySt9HQy6AwtdshwDhb1RVt0eLCGLMWBUkWHpCoAOg%2BhWtJolq28Ug2mcaeKqga%2BPvP2DWvbWkndisnbd4Fc%2FjUqgpGMDCSsMu9BjqkAQky8TJf%2BLRU9KSPeG3X2JBZTC92lGeY4KNNoHZw2CKGQM%2BSj4p80LhMbJH0fP7JLrDe2RLb2Ft3CfsazuY8YUAIA%2FJCOsaayYOpgqobOJGmL6rnfG01dUwuK4iZQi1tZ30gmcx6TB%2B%2ByRU20Z0UMWTzz8D7ExqGanzD8kDDa4ZUDPibjYWPCnJ3p2ZIF7VoiJ%2BvdNpHpLn1G8vDvLjzk4pkal5i&X-Amz-Signature=341290436d09c328542ca3fc2cbf6974c9e7b6b7a5d7619a0c3356969661167c&X-Amz-SignedHeaders=host&x-id=GetObject)


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

