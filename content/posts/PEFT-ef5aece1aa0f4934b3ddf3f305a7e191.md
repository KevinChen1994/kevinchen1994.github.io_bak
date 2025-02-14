---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4667ZYKKG5C%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250214T102452Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEAMaCXVzLXdlc3QtMiJGMEQCIDXMzwsYFnjZ1D3Bs9p3fKoPtQyJodnYyN0N2ERLKo5bAiA6Z%2\
  F4Ajdety7KEdfzcvrStQdiH2yuK95dSvYEIkOuKlir%2FAwgrEAAaDDYzNzQyMzE4MzgwNSIMfDgY\
  p%2BFGTxP%2BET1lKtwDzrVZKhH0NYdhT%2F%2FGWaCgMZkuCiYYphf8gvbdH4y8cp34y%2FYfdXc\
  K3p1arfcVTVDMgKIAFFsxqili7qoBUjeebtLfdReRtUOVif70LPcm0ZEEzMD4hESPcjZSu%2BjAcD\
  Achz8iXQswxZvLaXH2t8FMxJnjjo%2Bw7duN5kQ0Cy8fM8NT5%2FPmg43SHiK2A5nxrKhY4iT0Ub6\
  1hCdnlnwz0trYT3pNvPy3jg9%2B6vwAu5kDOosG8kB1LzE5oKX7632GxtUcalP%2F3mCQDtxxIa2d\
  pjOkPinSab0mUnlbpey00YS5mreTNYDxB%2BPvvT%2FEy%2BXkRM2iSEB0ShOptn7ZMOmnY9EjIyh\
  eRoVmQlaDBCpSzQ1XgdoiXzAGJyxCdjcbcwXZDriG8XWVx2dQmCbL28bMCcDIQUUMHys0iSr3eG2t\
  Rv5UnGMG5LFCSzxhKRN6y%2B5kOG4m2WslQZXpYjo%2BQUO8yzFYY3yNf74X2MC7FSY9HVVzKdJXx\
  E19bvZsAV4DJbdYGP%2F2GD%2BzOD9jNOE99orTtUQBE8h2FYcsL2O82lvB4mksqj6PFugjSm8ksd\
  ThMw3Vp8fBzmmZUNHraPGLQfH2a36aDHOmSWAcXaDqZScnBxfJNxrSPH%2BrD0l2U0XjXn8w27G8v\
  QY6pgH7cng6QImqgg%2BaS%2Bile4YyiYfJ8U%2ByZ9ZN2N%2BT07ZiGyt%2BNmqpIr4FmsHwLNIg\
  8yY%2FO%2BDtqm1JxSyHFapvmX%2BB79LWgJfhNiOzAaSdpkF481QXM7YelgNa5gReYcdbXNyDOY0\
  zAhJUdYnKVVymBTpEi1uxqFI%2Fr3NbIPMv4HhL9CCRJ1KYS9NlGkXTes%2B9o1rjNDdTHxYvm9Fq\
  Ipdctc4ITmZjdp8L&X-Amz-Signature=af4ea29f984fa905ed49de5bb674f98fde1a51196308\
  9768c5c7d689195a4563&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466WGPZ67NC%2F20250214%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250214T102334Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEAMaCXVzLXdlc3QtMiJGMEQCIDYaYDm0CaF7SkkB9JlGLBKUnmMwKnh\
        Yb7CdHfrUPVbsAiA1nXHlpT35RR7GSWkG6fh3vfP38fnv5%2B6IrR%2BYPa0Rfir%2FAwgr\
        EAAaDDYzNzQyMzE4MzgwNSIMA7lcCdYMx86q2RFlKtwDDYfTydfgpfw91jENevudZYRYR5G\
        loIIASfdY7FMWZzLBL%2BLVDcLVxucJBMdHQfd3yKVBJmFfvWx5y9vARouzAnzqLkhKJQLg\
        NmWgTi4vC0w4jKvKscwc0Z35XVPYKUu69NhuoMowRmDaoeVYwAbImYUNtufzXvkF7lFWsNJ\
        3Ng7qW5U7h9cemW8ZOavI%2F%2BwL2%2BoyfPjXFLWwQ1pAvW6id3wgS53MdE%2FNGDIoPH\
        sz7T%2BRvza6M%2FxXYXoN80lfHsHL1a6%2Bm1BuOhyBc%2FDSp%2BMYqIMPRAuVf12I%2B\
        1fmCWhp3gzwYssaArTEmhz%2BUX0Dx6PKNIVqpGEoiaWJBYGhc2a70we5v09KBK16Ysikx0\
        OE23v7CyfDv%2FCMgRK8wkAserHXH7NVASoM2IaGIsEymVpkGzABzSPok59A%2B1MvtkMew\
        esESy4CiN5pCs4hvyE7b6hIIEf5Eyrq9Veijfa5S1Rf%2BREisErsifOv%2FdwoqCPi6Pav\
        g0DHp3F9hJXDVJ41v6iDU%2BXcrY4HxuLIttFASh%2Fr0nJqtxr0pDTHunXHuA5AajKXKBm\
        JptBDXmZWGrecQxAlcyMmuSEhizihLl23mhZV24hdVGuWaTGM42%2ByhygnIr5Ln9hfbPTs\
        wTknDSYw5rG8vQY6pgHRYIbRqJCEacB7LVBIlRaQ3QHzkg%2FDKh8Tg433U7mgFumXftBv9\
        ocsLDxTK8un8HXL1NUT8prDDC94RS1uOwpc3JAr5rj4bhVW211EWWHljY5NENlLJUEfgNzJ\
        yg6uZSWpjtOYlfJVjnkEnEORgYiW6rIlI27givnJmuLOI6ZfgyT17iD6C44rQeWUsSqtlqO\
        oczj0oerXtMxE4XX94wkHiNgByR2w&X-Amz-Signature=489645940aaee7bd883f86873\
        17a4278f502d96c993d84ec4cc8a88f53ff6dab&X-Amz-SignedHeaders=host&x-id=G\
        etObject"
      expiry_time: "2025-02-14T11:23:34.753Z"
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
UPDATE_TIME: "2025-02-14T10:25:03.196Z"
EXPIRY_TIME: "2025-02-14T11:24:48.434Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WTRIT5PP%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T102448Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAMaCXVzLXdlc3QtMiJHMEUCIQDhV2OZAVM4act1ViCCsH2dA9yBAQeXHgzRd%2BsjUzQm6QIgTX3XYu1e21IrXf%2B%2BkT%2Fmm0qQ3u74R%2BWgi17VZnURsd4q%2FwMIKxAAGgw2Mzc0MjMxODM4MDUiDAiKTfQofdsPOCTD%2ByrcA%2Fc2Klp2lGOvcDYYZPvjTmsKDwraN3Sdja9FPWhuLdUzRK1L1Uk%2F07Kmopc1i33l3CN29B3ABpR1CfGYmlkuKFhAKGp6k1Vd5O3atDAsidhON5wzda73fc2UlX5tJcWKieyOGjkRIjUx%2FbYUxnymdrbwnMFU9S4BGlmUMeAv1aqDM1G2mxDDun1euvMyTHxpu0Lxdk4DcT90B8bSnI1SIw8Qnnh13n8V9bpQMa8XQ9oXb3AtER%2FPYO%2BhLrv4%2BdQLvDdqhZqt5LRIUrcIPPaY4lOBP%2BtQSVTL58W6iaqpDxeHUDIVCaORBx29obiFTvxiuodas3tSP5M4gD8H9ikQSuBwWUm%2BBGv2wMHjeI1xeEI%2BIW4H%2BnjZDxYfjmGyk78xoZUu2iDI7AT0jcbcnUO9A0KecdYJInOxC%2FM7qf9%2B1aNbcJ%2F1aZUf4xxKF9KgFV1dLibEUW9glFbx%2FSMsTMLiIv9t2dV4PauMy5Ye2GwW7xoEl%2FoOvq5KODOohS7NUHu0%2BMGPcomZzo7%2BFVPq%2BsTW9vr%2F2m5o0Ld4AjuSA%2FrC1lkmKk3vD8i6amxBqimW1xzY8XfSqMx6WoJD8NEPKOf2vJQxWOUpsrqLg25in64vzpfTe8neAJiDDse3bZL7MLayvL0GOqUBPJkx283SDBw4VOo8JWschQ9jTIRp53hkbBGTP9RsEJ6i6AKO6WisHpHy4c44Bmg4qitaSVkw7%2BQLUqyA4Wk8miP8Z3VGtpe9GPybxMZmAAq%2FERE7X8mQ087cd2cIoxMKso4QuGpueFW71%2BoBtRgotVC%2FmDHRX96YH66WBZzl%2FYi10tk3fhTjuA3RofvRJjdIe8xTnE2wZPEJoD0mW7%2FzJdHyzzUb&X-Amz-Signature=8425e8695778b3763774f4e31e2a443755024113c4ad91b86c9e4c44c2e23148&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WTRIT5PP%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T102449Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAMaCXVzLXdlc3QtMiJHMEUCIQDhV2OZAVM4act1ViCCsH2dA9yBAQeXHgzRd%2BsjUzQm6QIgTX3XYu1e21IrXf%2B%2BkT%2Fmm0qQ3u74R%2BWgi17VZnURsd4q%2FwMIKxAAGgw2Mzc0MjMxODM4MDUiDAiKTfQofdsPOCTD%2ByrcA%2Fc2Klp2lGOvcDYYZPvjTmsKDwraN3Sdja9FPWhuLdUzRK1L1Uk%2F07Kmopc1i33l3CN29B3ABpR1CfGYmlkuKFhAKGp6k1Vd5O3atDAsidhON5wzda73fc2UlX5tJcWKieyOGjkRIjUx%2FbYUxnymdrbwnMFU9S4BGlmUMeAv1aqDM1G2mxDDun1euvMyTHxpu0Lxdk4DcT90B8bSnI1SIw8Qnnh13n8V9bpQMa8XQ9oXb3AtER%2FPYO%2BhLrv4%2BdQLvDdqhZqt5LRIUrcIPPaY4lOBP%2BtQSVTL58W6iaqpDxeHUDIVCaORBx29obiFTvxiuodas3tSP5M4gD8H9ikQSuBwWUm%2BBGv2wMHjeI1xeEI%2BIW4H%2BnjZDxYfjmGyk78xoZUu2iDI7AT0jcbcnUO9A0KecdYJInOxC%2FM7qf9%2B1aNbcJ%2F1aZUf4xxKF9KgFV1dLibEUW9glFbx%2FSMsTMLiIv9t2dV4PauMy5Ye2GwW7xoEl%2FoOvq5KODOohS7NUHu0%2BMGPcomZzo7%2BFVPq%2BsTW9vr%2F2m5o0Ld4AjuSA%2FrC1lkmKk3vD8i6amxBqimW1xzY8XfSqMx6WoJD8NEPKOf2vJQxWOUpsrqLg25in64vzpfTe8neAJiDDse3bZL7MLayvL0GOqUBPJkx283SDBw4VOo8JWschQ9jTIRp53hkbBGTP9RsEJ6i6AKO6WisHpHy4c44Bmg4qitaSVkw7%2BQLUqyA4Wk8miP8Z3VGtpe9GPybxMZmAAq%2FERE7X8mQ087cd2cIoxMKso4QuGpueFW71%2BoBtRgotVC%2FmDHRX96YH66WBZzl%2FYi10tk3fhTjuA3RofvRJjdIe8xTnE2wZPEJoD0mW7%2FzJdHyzzUb&X-Amz-Signature=9201d3735480e0008bda98c4d5a677519c3e7ced6538cfcf15ab4dd9c524509d&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WTRIT5PP%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T102449Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAMaCXVzLXdlc3QtMiJHMEUCIQDhV2OZAVM4act1ViCCsH2dA9yBAQeXHgzRd%2BsjUzQm6QIgTX3XYu1e21IrXf%2B%2BkT%2Fmm0qQ3u74R%2BWgi17VZnURsd4q%2FwMIKxAAGgw2Mzc0MjMxODM4MDUiDAiKTfQofdsPOCTD%2ByrcA%2Fc2Klp2lGOvcDYYZPvjTmsKDwraN3Sdja9FPWhuLdUzRK1L1Uk%2F07Kmopc1i33l3CN29B3ABpR1CfGYmlkuKFhAKGp6k1Vd5O3atDAsidhON5wzda73fc2UlX5tJcWKieyOGjkRIjUx%2FbYUxnymdrbwnMFU9S4BGlmUMeAv1aqDM1G2mxDDun1euvMyTHxpu0Lxdk4DcT90B8bSnI1SIw8Qnnh13n8V9bpQMa8XQ9oXb3AtER%2FPYO%2BhLrv4%2BdQLvDdqhZqt5LRIUrcIPPaY4lOBP%2BtQSVTL58W6iaqpDxeHUDIVCaORBx29obiFTvxiuodas3tSP5M4gD8H9ikQSuBwWUm%2BBGv2wMHjeI1xeEI%2BIW4H%2BnjZDxYfjmGyk78xoZUu2iDI7AT0jcbcnUO9A0KecdYJInOxC%2FM7qf9%2B1aNbcJ%2F1aZUf4xxKF9KgFV1dLibEUW9glFbx%2FSMsTMLiIv9t2dV4PauMy5Ye2GwW7xoEl%2FoOvq5KODOohS7NUHu0%2BMGPcomZzo7%2BFVPq%2BsTW9vr%2F2m5o0Ld4AjuSA%2FrC1lkmKk3vD8i6amxBqimW1xzY8XfSqMx6WoJD8NEPKOf2vJQxWOUpsrqLg25in64vzpfTe8neAJiDDse3bZL7MLayvL0GOqUBPJkx283SDBw4VOo8JWschQ9jTIRp53hkbBGTP9RsEJ6i6AKO6WisHpHy4c44Bmg4qitaSVkw7%2BQLUqyA4Wk8miP8Z3VGtpe9GPybxMZmAAq%2FERE7X8mQ087cd2cIoxMKso4QuGpueFW71%2BoBtRgotVC%2FmDHRX96YH66WBZzl%2FYi10tk3fhTjuA3RofvRJjdIe8xTnE2wZPEJoD0mW7%2FzJdHyzzUb&X-Amz-Signature=5d256fd75162bccf31c909744a448c69cd681049bb352f27d6946af87f4eb1cc&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WTRIT5PP%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T102449Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAMaCXVzLXdlc3QtMiJHMEUCIQDhV2OZAVM4act1ViCCsH2dA9yBAQeXHgzRd%2BsjUzQm6QIgTX3XYu1e21IrXf%2B%2BkT%2Fmm0qQ3u74R%2BWgi17VZnURsd4q%2FwMIKxAAGgw2Mzc0MjMxODM4MDUiDAiKTfQofdsPOCTD%2ByrcA%2Fc2Klp2lGOvcDYYZPvjTmsKDwraN3Sdja9FPWhuLdUzRK1L1Uk%2F07Kmopc1i33l3CN29B3ABpR1CfGYmlkuKFhAKGp6k1Vd5O3atDAsidhON5wzda73fc2UlX5tJcWKieyOGjkRIjUx%2FbYUxnymdrbwnMFU9S4BGlmUMeAv1aqDM1G2mxDDun1euvMyTHxpu0Lxdk4DcT90B8bSnI1SIw8Qnnh13n8V9bpQMa8XQ9oXb3AtER%2FPYO%2BhLrv4%2BdQLvDdqhZqt5LRIUrcIPPaY4lOBP%2BtQSVTL58W6iaqpDxeHUDIVCaORBx29obiFTvxiuodas3tSP5M4gD8H9ikQSuBwWUm%2BBGv2wMHjeI1xeEI%2BIW4H%2BnjZDxYfjmGyk78xoZUu2iDI7AT0jcbcnUO9A0KecdYJInOxC%2FM7qf9%2B1aNbcJ%2F1aZUf4xxKF9KgFV1dLibEUW9glFbx%2FSMsTMLiIv9t2dV4PauMy5Ye2GwW7xoEl%2FoOvq5KODOohS7NUHu0%2BMGPcomZzo7%2BFVPq%2BsTW9vr%2F2m5o0Ld4AjuSA%2FrC1lkmKk3vD8i6amxBqimW1xzY8XfSqMx6WoJD8NEPKOf2vJQxWOUpsrqLg25in64vzpfTe8neAJiDDse3bZL7MLayvL0GOqUBPJkx283SDBw4VOo8JWschQ9jTIRp53hkbBGTP9RsEJ6i6AKO6WisHpHy4c44Bmg4qitaSVkw7%2BQLUqyA4Wk8miP8Z3VGtpe9GPybxMZmAAq%2FERE7X8mQ087cd2cIoxMKso4QuGpueFW71%2BoBtRgotVC%2FmDHRX96YH66WBZzl%2FYi10tk3fhTjuA3RofvRJjdIe8xTnE2wZPEJoD0mW7%2FzJdHyzzUb&X-Amz-Signature=a60a43d0e719297374f7afb7b70f9b09b787697582d4a158f22a909c6213f6f9&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WTRIT5PP%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T102449Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAMaCXVzLXdlc3QtMiJHMEUCIQDhV2OZAVM4act1ViCCsH2dA9yBAQeXHgzRd%2BsjUzQm6QIgTX3XYu1e21IrXf%2B%2BkT%2Fmm0qQ3u74R%2BWgi17VZnURsd4q%2FwMIKxAAGgw2Mzc0MjMxODM4MDUiDAiKTfQofdsPOCTD%2ByrcA%2Fc2Klp2lGOvcDYYZPvjTmsKDwraN3Sdja9FPWhuLdUzRK1L1Uk%2F07Kmopc1i33l3CN29B3ABpR1CfGYmlkuKFhAKGp6k1Vd5O3atDAsidhON5wzda73fc2UlX5tJcWKieyOGjkRIjUx%2FbYUxnymdrbwnMFU9S4BGlmUMeAv1aqDM1G2mxDDun1euvMyTHxpu0Lxdk4DcT90B8bSnI1SIw8Qnnh13n8V9bpQMa8XQ9oXb3AtER%2FPYO%2BhLrv4%2BdQLvDdqhZqt5LRIUrcIPPaY4lOBP%2BtQSVTL58W6iaqpDxeHUDIVCaORBx29obiFTvxiuodas3tSP5M4gD8H9ikQSuBwWUm%2BBGv2wMHjeI1xeEI%2BIW4H%2BnjZDxYfjmGyk78xoZUu2iDI7AT0jcbcnUO9A0KecdYJInOxC%2FM7qf9%2B1aNbcJ%2F1aZUf4xxKF9KgFV1dLibEUW9glFbx%2FSMsTMLiIv9t2dV4PauMy5Ye2GwW7xoEl%2FoOvq5KODOohS7NUHu0%2BMGPcomZzo7%2BFVPq%2BsTW9vr%2F2m5o0Ld4AjuSA%2FrC1lkmKk3vD8i6amxBqimW1xzY8XfSqMx6WoJD8NEPKOf2vJQxWOUpsrqLg25in64vzpfTe8neAJiDDse3bZL7MLayvL0GOqUBPJkx283SDBw4VOo8JWschQ9jTIRp53hkbBGTP9RsEJ6i6AKO6WisHpHy4c44Bmg4qitaSVkw7%2BQLUqyA4Wk8miP8Z3VGtpe9GPybxMZmAAq%2FERE7X8mQ087cd2cIoxMKso4QuGpueFW71%2BoBtRgotVC%2FmDHRX96YH66WBZzl%2FYi10tk3fhTjuA3RofvRJjdIe8xTnE2wZPEJoD0mW7%2FzJdHyzzUb&X-Amz-Signature=338303bec7a3546e2b325cfa8e610b4a744baad1bf07a3d72ffad4155806d8d6&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662CGJ7XUO%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T102451Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAMaCXVzLXdlc3QtMiJHMEUCIQDlVRyQwDCny8vgYGN3D4MTXKGG9WkUMi9LfjHw52%2FJ%2BQIgfivd4GM0SVTq3nmuRbA7uXz1uhcxM%2B4RoU7OG8A8%2Bxgq%2FwMIKxAAGgw2Mzc0MjMxODM4MDUiDAxxjeI9VIu38WBOYyrcA%2FnUyNvB3q%2FRVGTbO91EiHC5oaVnUpFC2OtLc54REDuidhGT34dNCweVBVisxTPxfgeC1lpMEVxmU0N4wJ1rzM2B0DInAoXx4iczjPXI3%2FHT2XETKO29SLRnmBD0cZ557J10la2hwafV0GeFRT3mjoMSLrvT41%2Bv7ZgsU9oeENlqCDTVrqIJXpoE9YtdDYp8soBiEvw%2BU5B%2FSLOlBQNoK0DlYjmdOqZpzeTZ8Lpcbcd7MWhMtDOTqzIOpTy0URs2B1JFRQISF4qPgLymbs11e1dP56i5UUM4Lw0zlC6WtgsuYnEkwS3LDTD92vBTk81Z%2Fq8Cl5b686c96f%2FDyQgJqdzSnVVGi4KwvlBj1dkzw7DTl72hCNFZfleryX9QGbg0x%2FbM13hPEqt3w60Nbao7wvRCwBrel3Ji%2FIjdaA9RzfzcBxuW3BalKSw%2BDeVAJeYyJsBZpfei9aCQMHjmaXoujbwPSXCbvpo%2F7L6kSyJ%2FTEvFs1wlCPBkieqMdUwdhvumgFkUsavg2trI7HLk6PChx8WF4tDJlpQSBLHS5WRrQQ5ktUrxVBdmQiH7ghFk86IZ940aEgOxkr4oQOZS4eHIPB48cxzQD96wm2NcyZXDS7nxrAXpDY6TSSvqMGIRMLKyvL0GOqUBW9Pb4wb8Ujsgjn4O6vkeC3lG3Ucjuz8nsQAMDnh0WcoY8CsAcjZBXhON5WQlKZ8BlT%2BkXipdSg5FP6%2B4g1boMasbOQUQ2XKuesv4h6kcKl3PEDQmnHoG1jj1ImVgpPmUk%2B%2BHtJHhxVlTV%2BRtfAqz3%2Fy%2BYT%2B4v32l1PITj8o8U56FkyA%2F9hDtPP9TThmNpVjSdfogtcPc3opivH3z5tUCn%2FT9TeWK&X-Amz-Signature=9b7e4d0382db2a48b212888a47516ab1b8f9a5bda1281b290f8873e6d1f09c9f&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662IFZTX3E%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T102452Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAMaCXVzLXdlc3QtMiJGMEQCIB%2FX2KsrU0igpGShUL9TPBO7vEaVGqR8TCGLg585njuoAiAIa6Yy6O6C8Q3ncSbQe9lSPhI%2B3Xx%2F9%2B3cRjl9HZIhpSr%2FAwgrEAAaDDYzNzQyMzE4MzgwNSIM5AoestW%2FCzEt%2F12IKtwD%2FhLoKjtMCX9N1anHTzrb2arROHETLUaGnDJT5cqYOTTjgw6I1ewh0xIFNyh5ogD8S3og%2FJEofLDaMiYUoL7NFCwbx%2BVx52Hf2q3dGyWN%2BKGNTDtPpNIg%2BWvCQmjYu3r6lqbg0PMhsE42MX5Ur05SRTHR72l8rYeEPPoesxsTeG6J1bcRBYQGsUcUb9QPw4xmLlV%2F0e3f7GFTCu9GKZqvJwjpepePy9iYkYnwVmjx3%2Fm1PVNA3WKW7YjQd59fYjcnHTnaRko%2FHTOxqminSpVGDIx1EHdOyzFi9ueDah69LAKub9Z7r8NwcDlD0jz4etvyxSoEAlOdQXSmaelJZx%2FDFJHgVjlYjOQvdga4r57XSJ3um5421FUMrW1VtNO2agVAMY1zOhn5p81ECao9oAuS4EEu87INwO5r64GXa6%2B5XDawLRfSR%2Bi49FIa6BcMaK0IrTSQ%2FlFBbZ3vkQFxzmzxoC6N9ScvK7WgsARN1VBd91cZlFZRmziPRQbM3F9DMnnY0cDJdcN7O8Pz7OrTDrxGXxUYv9NOQFsUHfsx%2BExX77xr%2BlfPydgeSxFzo6nqyfwY3MuVr72S3zhr9nwWWGNjLD4GQGIyOJbRr9h0BDg2pwZzNl2IDzfK1ixcOskwgrK8vQY6pgErNS0MtATu3zla02qEEhMbJBG5RO6gr1nAGrQvaPBQkbnw6RuvZE8MMu71JvXTCr%2Bl1YZZcVCHEGkjlq%2BKdn8aIIybIm5eFeAUSvZs1PSBdchVxOrpNjR5xqkMTyF9liJ2xULly7WMoj0IOmtqaQMU3lB2vjGOeK5lpU%2Ftma1Dh6wY5xj%2BOwgUUpThvG4lLNP7%2FDMRkjqT793f7VY4g8bATvxSpBTl&X-Amz-Signature=4a50c3f7d0c28f0c6f2b1f1f1d13a7c60976965070f7aef35cea146edea99917&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WTRIT5PP%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T102449Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAMaCXVzLXdlc3QtMiJHMEUCIQDhV2OZAVM4act1ViCCsH2dA9yBAQeXHgzRd%2BsjUzQm6QIgTX3XYu1e21IrXf%2B%2BkT%2Fmm0qQ3u74R%2BWgi17VZnURsd4q%2FwMIKxAAGgw2Mzc0MjMxODM4MDUiDAiKTfQofdsPOCTD%2ByrcA%2Fc2Klp2lGOvcDYYZPvjTmsKDwraN3Sdja9FPWhuLdUzRK1L1Uk%2F07Kmopc1i33l3CN29B3ABpR1CfGYmlkuKFhAKGp6k1Vd5O3atDAsidhON5wzda73fc2UlX5tJcWKieyOGjkRIjUx%2FbYUxnymdrbwnMFU9S4BGlmUMeAv1aqDM1G2mxDDun1euvMyTHxpu0Lxdk4DcT90B8bSnI1SIw8Qnnh13n8V9bpQMa8XQ9oXb3AtER%2FPYO%2BhLrv4%2BdQLvDdqhZqt5LRIUrcIPPaY4lOBP%2BtQSVTL58W6iaqpDxeHUDIVCaORBx29obiFTvxiuodas3tSP5M4gD8H9ikQSuBwWUm%2BBGv2wMHjeI1xeEI%2BIW4H%2BnjZDxYfjmGyk78xoZUu2iDI7AT0jcbcnUO9A0KecdYJInOxC%2FM7qf9%2B1aNbcJ%2F1aZUf4xxKF9KgFV1dLibEUW9glFbx%2FSMsTMLiIv9t2dV4PauMy5Ye2GwW7xoEl%2FoOvq5KODOohS7NUHu0%2BMGPcomZzo7%2BFVPq%2BsTW9vr%2F2m5o0Ld4AjuSA%2FrC1lkmKk3vD8i6amxBqimW1xzY8XfSqMx6WoJD8NEPKOf2vJQxWOUpsrqLg25in64vzpfTe8neAJiDDse3bZL7MLayvL0GOqUBPJkx283SDBw4VOo8JWschQ9jTIRp53hkbBGTP9RsEJ6i6AKO6WisHpHy4c44Bmg4qitaSVkw7%2BQLUqyA4Wk8miP8Z3VGtpe9GPybxMZmAAq%2FERE7X8mQ087cd2cIoxMKso4QuGpueFW71%2BoBtRgotVC%2FmDHRX96YH66WBZzl%2FYi10tk3fhTjuA3RofvRJjdIe8xTnE2wZPEJoD0mW7%2FzJdHyzzUb&X-Amz-Signature=85a8c07a0a5925a266773d276aa0a06fc3ed30ddec1da7a42c0d629282c066cd&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WTRIT5PP%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T102449Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAMaCXVzLXdlc3QtMiJHMEUCIQDhV2OZAVM4act1ViCCsH2dA9yBAQeXHgzRd%2BsjUzQm6QIgTX3XYu1e21IrXf%2B%2BkT%2Fmm0qQ3u74R%2BWgi17VZnURsd4q%2FwMIKxAAGgw2Mzc0MjMxODM4MDUiDAiKTfQofdsPOCTD%2ByrcA%2Fc2Klp2lGOvcDYYZPvjTmsKDwraN3Sdja9FPWhuLdUzRK1L1Uk%2F07Kmopc1i33l3CN29B3ABpR1CfGYmlkuKFhAKGp6k1Vd5O3atDAsidhON5wzda73fc2UlX5tJcWKieyOGjkRIjUx%2FbYUxnymdrbwnMFU9S4BGlmUMeAv1aqDM1G2mxDDun1euvMyTHxpu0Lxdk4DcT90B8bSnI1SIw8Qnnh13n8V9bpQMa8XQ9oXb3AtER%2FPYO%2BhLrv4%2BdQLvDdqhZqt5LRIUrcIPPaY4lOBP%2BtQSVTL58W6iaqpDxeHUDIVCaORBx29obiFTvxiuodas3tSP5M4gD8H9ikQSuBwWUm%2BBGv2wMHjeI1xeEI%2BIW4H%2BnjZDxYfjmGyk78xoZUu2iDI7AT0jcbcnUO9A0KecdYJInOxC%2FM7qf9%2B1aNbcJ%2F1aZUf4xxKF9KgFV1dLibEUW9glFbx%2FSMsTMLiIv9t2dV4PauMy5Ye2GwW7xoEl%2FoOvq5KODOohS7NUHu0%2BMGPcomZzo7%2BFVPq%2BsTW9vr%2F2m5o0Ld4AjuSA%2FrC1lkmKk3vD8i6amxBqimW1xzY8XfSqMx6WoJD8NEPKOf2vJQxWOUpsrqLg25in64vzpfTe8neAJiDDse3bZL7MLayvL0GOqUBPJkx283SDBw4VOo8JWschQ9jTIRp53hkbBGTP9RsEJ6i6AKO6WisHpHy4c44Bmg4qitaSVkw7%2BQLUqyA4Wk8miP8Z3VGtpe9GPybxMZmAAq%2FERE7X8mQ087cd2cIoxMKso4QuGpueFW71%2BoBtRgotVC%2FmDHRX96YH66WBZzl%2FYi10tk3fhTjuA3RofvRJjdIe8xTnE2wZPEJoD0mW7%2FzJdHyzzUb&X-Amz-Signature=71eb3717cfef2a0d86b4362a0d73fe39ea0c1e835531d8f3d90dab99cae1ef3b&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WTRIT5PP%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T102449Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAMaCXVzLXdlc3QtMiJHMEUCIQDhV2OZAVM4act1ViCCsH2dA9yBAQeXHgzRd%2BsjUzQm6QIgTX3XYu1e21IrXf%2B%2BkT%2Fmm0qQ3u74R%2BWgi17VZnURsd4q%2FwMIKxAAGgw2Mzc0MjMxODM4MDUiDAiKTfQofdsPOCTD%2ByrcA%2Fc2Klp2lGOvcDYYZPvjTmsKDwraN3Sdja9FPWhuLdUzRK1L1Uk%2F07Kmopc1i33l3CN29B3ABpR1CfGYmlkuKFhAKGp6k1Vd5O3atDAsidhON5wzda73fc2UlX5tJcWKieyOGjkRIjUx%2FbYUxnymdrbwnMFU9S4BGlmUMeAv1aqDM1G2mxDDun1euvMyTHxpu0Lxdk4DcT90B8bSnI1SIw8Qnnh13n8V9bpQMa8XQ9oXb3AtER%2FPYO%2BhLrv4%2BdQLvDdqhZqt5LRIUrcIPPaY4lOBP%2BtQSVTL58W6iaqpDxeHUDIVCaORBx29obiFTvxiuodas3tSP5M4gD8H9ikQSuBwWUm%2BBGv2wMHjeI1xeEI%2BIW4H%2BnjZDxYfjmGyk78xoZUu2iDI7AT0jcbcnUO9A0KecdYJInOxC%2FM7qf9%2B1aNbcJ%2F1aZUf4xxKF9KgFV1dLibEUW9glFbx%2FSMsTMLiIv9t2dV4PauMy5Ye2GwW7xoEl%2FoOvq5KODOohS7NUHu0%2BMGPcomZzo7%2BFVPq%2BsTW9vr%2F2m5o0Ld4AjuSA%2FrC1lkmKk3vD8i6amxBqimW1xzY8XfSqMx6WoJD8NEPKOf2vJQxWOUpsrqLg25in64vzpfTe8neAJiDDse3bZL7MLayvL0GOqUBPJkx283SDBw4VOo8JWschQ9jTIRp53hkbBGTP9RsEJ6i6AKO6WisHpHy4c44Bmg4qitaSVkw7%2BQLUqyA4Wk8miP8Z3VGtpe9GPybxMZmAAq%2FERE7X8mQ087cd2cIoxMKso4QuGpueFW71%2BoBtRgotVC%2FmDHRX96YH66WBZzl%2FYi10tk3fhTjuA3RofvRJjdIe8xTnE2wZPEJoD0mW7%2FzJdHyzzUb&X-Amz-Signature=14f2f079ff1a17616b7ae48348febefae42423cfec695fd9bd2da8e306d34705&X-Amz-SignedHeaders=host&x-id=GetObject)


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

