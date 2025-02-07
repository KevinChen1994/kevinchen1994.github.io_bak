---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466ZWWM3QGL%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250207T072140Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEFcaCXVzLXdlc3QtMiJGMEQCIAPUeWm2fsKRPI1rxmUBEw4en3B3%2FTIPgiPPqcVJiEcWAiAp1\
  Z4h%2FLRLyVz7z0FgBDofQnltizQs1lfBsQkWakUCHyr%2FAwhwEAAaDDYzNzQyMzE4MzgwNSIMKx\
  YW52i4rey2yR6WKtwD0GpnH7OELmXOSOtma%2FU1CMzuq0qZT1p5D0Kx%2Bn%2F4CCmg0Tq97daMT\
  8n5SaP%2BRkqUG24O4IdiU9hCKsprB2uK36zXs2sGxVgJGOY8iPRu%2FcAmswOnZ2kKGlwjyxryVX\
  3KZ2w%2B4e7dJpBCGWmVV2wAzvOMbXiXy45hrRtrE0KUhqTlVtiauNXOzeTSHLmGM4pUfDJoed8Yq\
  uQ8u2AraPD09jbklWBr7JDkGjZ9uxFolHoKjSQqZTzswhlhTrpRBwHv7EevRDSHXMxkmqykn4%2FZ\
  h0rInHM34yGF8x5UNj%2F1UPoow%2B4I6HRd%2F09yEX1%2BKVa4QvMTwYJxhI2uUetjH32KrRUL5\
  IwcXzLZAvb9Al%2Fg5ljwg2gF9jA3k6HhD07nSY1KtTUC4ARwo%2BsI%2FCMSPiu6sMbHF8iDEn9r\
  HDR7lgpU0VR7Lo9InNColbvjDmIetc4okun7O3LFwcDSPjWJFZilamLdbpt1nDK2ZXkG5p8vK999%\
  2BiGy4BmZ0F1BsUhJlHc0dOJHD%2BaoqicCpFk%2FbT1qNIecqwct74jAOOon9B7X0DBeiRgaRVpe\
  pDI1phY75rCcdLh%2FJV8Mp%2BwQhHUueiyaDP5EBdK0cRm6igNAzdEx%2FGaScVIFJ7smr07NipQ\
  w%2Ft2WvQY6pgH3m3QHviWwicafbo63gBxy579Pv1QeXXlsl6wtJIOy%2FWY3%2F7H27yluRYc50R\
  pncghQDAm9oXunCYp%2FI232BNf4FoWzpnKifC62s82%2Fkf0okaf0qIraEPd1ybV%2F9B8PavZNP\
  pBTRs2CKGQ6%2BeFQXR9GB5iQJGpvpYTZxukr82FD5ymrKPAse%2FZDR193lIkVGVH0IpAirsZwM9\
  4n3uEZ8wSaBPvupVky&X-Amz-Signature=610b1199207c471b4cdbfa7fa5902653c46cb3c7ef\
  1777f0aac15c905ce71f15&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466VB5C43HX%2F20250207%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250207T072025Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEFcaCXVzLXdlc3QtMiJGMEQCIAPNtMBwi%2Fck1a%2F7LzvfdcP7jtG\
        D56F6QcsSSXBGMR44AiBF3yBtquhDBthnPbjogqtbswSEI5B%2BLyTGviFxsrvXlyr%2FAw\
        hwEAAaDDYzNzQyMzE4MzgwNSIMPu9XHraDllh5VO0NKtwDJm8hm%2FLsILi7GeAvnFb%2F9\
        NBhjDJnYR8ogHXVgegUCQaCU%2B8kdhclLh8v95WmUstzKBBdq7VD6eBFxEA4fAptSPfVeO\
        vgOlpC%2FwFaKuzf7SxF64ZCPbnVHxsazursx1UVfawwngy9yiUhtPwYw%2BN334iGtYX6z\
        MCs3la6Z30o7B0lskjh7an%2B7lMSwGxflMTIRf9UwfMYf1GMda7yvj9%2BHzqyw1E9vxFy\
        AOlrsw9IhxfiAR922T9%2FFHUu1vRE6F%2BlI3swZMWL7OfIwMzKj%2BqmETREmTlVFT0v7\
        0NzT2IGZXbTgJ%2FICHjFC9RVTwJtolEUVOSVNVASUwHdFKl3BqZ%2FUYri2CqDOzJ%2Blv\
        i8vCtQkw5Cu%2B8t2WgeQDWVTOVRSt1TOh6%2BtpRoIy%2FtakYj0UQiTT%2FUq0a8WNqgE\
        vy5N76h572wcubIfDqshE1MtR7axtkSRlJHEfDX8ZFLYVIVMmtH7KfSVqzAIeV73BhqZmbZ\
        u4nCL43Vt5ZskBYsfN3R4l902BS1l00MTzZBqH%2BjMxuq1NQYXO%2B1pGBFeVO6DSIt4cr\
        E7RibDsellOfcTDIpYLRlAz7mSbWIo8lnmzYSJ5a5UVbEvZeGYJmV6CA61avMAAO1IRmo0c\
        6yVQni3XIw7d2WvQY6pgF7cjvTiKxKhq6pHdi%2FPrftNyc8Ga7PXHu9kvYInUTzqePgOmY\
        T9pveYYh1ENeOghjW9PckgS4h%2Bk4CF40iuvEEyMGAfOyNi5cns5GOkHYARno5AWX4kFPh\
        Pus9wyBRnMZLXDXLdb%2FIj84yzULrJkzBqnh%2FpkDkG23qDS8J8ClreQwZax2AZNsemIw\
        QL6MV%2Bg2zFffZ9YPjfJpcxXHPfObVX0MgP92z&X-Amz-Signature=6e85c90acab4863\
        b95436081da24ebfb0cd39cc42aaa7a1a4cd704950bd228c9&X-Amz-SignedHeaders=h\
        ost&x-id=GetObject"
      expiry_time: "2025-02-07T08:20:25.788Z"
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
UPDATE_TIME: "2025-02-07T07:21:48.751Z"
EXPIRY_TIME: "2025-02-07T08:21:36.705Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466546L7YY5%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T072137Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFcaCXVzLXdlc3QtMiJHMEUCIE5Ykg83Hsi5QBoYAaTLUqdoh491pcN9qPYy7QHXDOa0AiEA9ANxlR4i1gW5O33mM1AvIqAp%2ByHYuqF0QddMujvMDDYq%2FwMIcBAAGgw2Mzc0MjMxODM4MDUiDOxIEiXDOyhQF237jCrcA5%2FHp4%2BEfue%2BF0XB8tGlQKBHWR1jGssjmna33Qitkr9fJoUPh2usv5ql8oB9eBEQZhhAc%2FzxnuiGsLU4PT4NfEf9F8G50lMf9OoY6hP7It2c0OqwMxUK57dE8gB43p0Xwnks5xqarjYO%2F2cM8XwFDe3xLDlMd69H%2BRvRqwOLGBQ%2F1%2F5DJefyjetBcBdSFBSu8pmZ39gdgQGZyKF76VFfo86lNcvqD2vTrbQdU9b9xm63W88Wd004JKAAU8Xh%2B1Ca%2Ba%2BGYRjVq8Qjuxa8pj52m9XGlaZ3Khf5dFbIEgA%2BiB%2B96xETyv7AXbpoty5L9GghtTnlU1LYnwoju9Z%2B%2BHUfbw6KvPn%2B643t8aGkpK6D9qhBHmaD9BaIHoz0QxTumzzrR%2BYEHM3WpWcCdDfS0dUm8nkQYcsPOFJAId476aBrm7hZSLFoCJQ1a3w8rCjfSmss0V%2BgqoyLSJUHV9Z6jD4IbuMEtm%2BWpBv3kf09SeO14fJzLbLRNCMPi8cDQ3h7RwYPukypgadUgQdB9rTP2QKkD934Zy6ils5mGdjOa7S1XmedDaAQAreo2YD70EEtzd4fur5RHwwx3Qh2Et5%2F%2BqNUD7k%2FaiGLrKh%2F%2BsCRI1XpS73D8C%2FnUcSBvtGeElPbML%2Fflr0GOqUB2zJMAhQ1iWU0VK1xr1SL1XC1CWf%2FOzXHmleap2YrRkCsqMKoez70IuPL%2F%2BNYMgGLM3WYPCV2wfUD%2BxB4mWkvbAtehykACJb3bbr0NDoQb7XuKHuQymRRRiB97NWxAX4JAJIFto%2BY%2FbqgQKZmzVdsKCEKhHmAo3cUdIiQAD33yjiNa1RXyjF6u826y%2BxxwVA2ypLo2II4YNCHLoro5IWhghy0Ncp%2B&X-Amz-Signature=5ea45b0854d9de4e36ee7d48e2f269dadaa8357cc8d774495dbb440670ec84ed&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466546L7YY5%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T072137Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFcaCXVzLXdlc3QtMiJHMEUCIE5Ykg83Hsi5QBoYAaTLUqdoh491pcN9qPYy7QHXDOa0AiEA9ANxlR4i1gW5O33mM1AvIqAp%2ByHYuqF0QddMujvMDDYq%2FwMIcBAAGgw2Mzc0MjMxODM4MDUiDOxIEiXDOyhQF237jCrcA5%2FHp4%2BEfue%2BF0XB8tGlQKBHWR1jGssjmna33Qitkr9fJoUPh2usv5ql8oB9eBEQZhhAc%2FzxnuiGsLU4PT4NfEf9F8G50lMf9OoY6hP7It2c0OqwMxUK57dE8gB43p0Xwnks5xqarjYO%2F2cM8XwFDe3xLDlMd69H%2BRvRqwOLGBQ%2F1%2F5DJefyjetBcBdSFBSu8pmZ39gdgQGZyKF76VFfo86lNcvqD2vTrbQdU9b9xm63W88Wd004JKAAU8Xh%2B1Ca%2Ba%2BGYRjVq8Qjuxa8pj52m9XGlaZ3Khf5dFbIEgA%2BiB%2B96xETyv7AXbpoty5L9GghtTnlU1LYnwoju9Z%2B%2BHUfbw6KvPn%2B643t8aGkpK6D9qhBHmaD9BaIHoz0QxTumzzrR%2BYEHM3WpWcCdDfS0dUm8nkQYcsPOFJAId476aBrm7hZSLFoCJQ1a3w8rCjfSmss0V%2BgqoyLSJUHV9Z6jD4IbuMEtm%2BWpBv3kf09SeO14fJzLbLRNCMPi8cDQ3h7RwYPukypgadUgQdB9rTP2QKkD934Zy6ils5mGdjOa7S1XmedDaAQAreo2YD70EEtzd4fur5RHwwx3Qh2Et5%2F%2BqNUD7k%2FaiGLrKh%2F%2BsCRI1XpS73D8C%2FnUcSBvtGeElPbML%2Fflr0GOqUB2zJMAhQ1iWU0VK1xr1SL1XC1CWf%2FOzXHmleap2YrRkCsqMKoez70IuPL%2F%2BNYMgGLM3WYPCV2wfUD%2BxB4mWkvbAtehykACJb3bbr0NDoQb7XuKHuQymRRRiB97NWxAX4JAJIFto%2BY%2FbqgQKZmzVdsKCEKhHmAo3cUdIiQAD33yjiNa1RXyjF6u826y%2BxxwVA2ypLo2II4YNCHLoro5IWhghy0Ncp%2B&X-Amz-Signature=9100c10ce2942ff310f1dd9af32bf54903236a556ce8087accfa31b8d6e58889&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466546L7YY5%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T072137Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFcaCXVzLXdlc3QtMiJHMEUCIE5Ykg83Hsi5QBoYAaTLUqdoh491pcN9qPYy7QHXDOa0AiEA9ANxlR4i1gW5O33mM1AvIqAp%2ByHYuqF0QddMujvMDDYq%2FwMIcBAAGgw2Mzc0MjMxODM4MDUiDOxIEiXDOyhQF237jCrcA5%2FHp4%2BEfue%2BF0XB8tGlQKBHWR1jGssjmna33Qitkr9fJoUPh2usv5ql8oB9eBEQZhhAc%2FzxnuiGsLU4PT4NfEf9F8G50lMf9OoY6hP7It2c0OqwMxUK57dE8gB43p0Xwnks5xqarjYO%2F2cM8XwFDe3xLDlMd69H%2BRvRqwOLGBQ%2F1%2F5DJefyjetBcBdSFBSu8pmZ39gdgQGZyKF76VFfo86lNcvqD2vTrbQdU9b9xm63W88Wd004JKAAU8Xh%2B1Ca%2Ba%2BGYRjVq8Qjuxa8pj52m9XGlaZ3Khf5dFbIEgA%2BiB%2B96xETyv7AXbpoty5L9GghtTnlU1LYnwoju9Z%2B%2BHUfbw6KvPn%2B643t8aGkpK6D9qhBHmaD9BaIHoz0QxTumzzrR%2BYEHM3WpWcCdDfS0dUm8nkQYcsPOFJAId476aBrm7hZSLFoCJQ1a3w8rCjfSmss0V%2BgqoyLSJUHV9Z6jD4IbuMEtm%2BWpBv3kf09SeO14fJzLbLRNCMPi8cDQ3h7RwYPukypgadUgQdB9rTP2QKkD934Zy6ils5mGdjOa7S1XmedDaAQAreo2YD70EEtzd4fur5RHwwx3Qh2Et5%2F%2BqNUD7k%2FaiGLrKh%2F%2BsCRI1XpS73D8C%2FnUcSBvtGeElPbML%2Fflr0GOqUB2zJMAhQ1iWU0VK1xr1SL1XC1CWf%2FOzXHmleap2YrRkCsqMKoez70IuPL%2F%2BNYMgGLM3WYPCV2wfUD%2BxB4mWkvbAtehykACJb3bbr0NDoQb7XuKHuQymRRRiB97NWxAX4JAJIFto%2BY%2FbqgQKZmzVdsKCEKhHmAo3cUdIiQAD33yjiNa1RXyjF6u826y%2BxxwVA2ypLo2II4YNCHLoro5IWhghy0Ncp%2B&X-Amz-Signature=042f5e59db97af6e07262f9964b385dfca0b69cc4bb2032e244907c0053cc5ba&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466546L7YY5%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T072137Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFcaCXVzLXdlc3QtMiJHMEUCIE5Ykg83Hsi5QBoYAaTLUqdoh491pcN9qPYy7QHXDOa0AiEA9ANxlR4i1gW5O33mM1AvIqAp%2ByHYuqF0QddMujvMDDYq%2FwMIcBAAGgw2Mzc0MjMxODM4MDUiDOxIEiXDOyhQF237jCrcA5%2FHp4%2BEfue%2BF0XB8tGlQKBHWR1jGssjmna33Qitkr9fJoUPh2usv5ql8oB9eBEQZhhAc%2FzxnuiGsLU4PT4NfEf9F8G50lMf9OoY6hP7It2c0OqwMxUK57dE8gB43p0Xwnks5xqarjYO%2F2cM8XwFDe3xLDlMd69H%2BRvRqwOLGBQ%2F1%2F5DJefyjetBcBdSFBSu8pmZ39gdgQGZyKF76VFfo86lNcvqD2vTrbQdU9b9xm63W88Wd004JKAAU8Xh%2B1Ca%2Ba%2BGYRjVq8Qjuxa8pj52m9XGlaZ3Khf5dFbIEgA%2BiB%2B96xETyv7AXbpoty5L9GghtTnlU1LYnwoju9Z%2B%2BHUfbw6KvPn%2B643t8aGkpK6D9qhBHmaD9BaIHoz0QxTumzzrR%2BYEHM3WpWcCdDfS0dUm8nkQYcsPOFJAId476aBrm7hZSLFoCJQ1a3w8rCjfSmss0V%2BgqoyLSJUHV9Z6jD4IbuMEtm%2BWpBv3kf09SeO14fJzLbLRNCMPi8cDQ3h7RwYPukypgadUgQdB9rTP2QKkD934Zy6ils5mGdjOa7S1XmedDaAQAreo2YD70EEtzd4fur5RHwwx3Qh2Et5%2F%2BqNUD7k%2FaiGLrKh%2F%2BsCRI1XpS73D8C%2FnUcSBvtGeElPbML%2Fflr0GOqUB2zJMAhQ1iWU0VK1xr1SL1XC1CWf%2FOzXHmleap2YrRkCsqMKoez70IuPL%2F%2BNYMgGLM3WYPCV2wfUD%2BxB4mWkvbAtehykACJb3bbr0NDoQb7XuKHuQymRRRiB97NWxAX4JAJIFto%2BY%2FbqgQKZmzVdsKCEKhHmAo3cUdIiQAD33yjiNa1RXyjF6u826y%2BxxwVA2ypLo2II4YNCHLoro5IWhghy0Ncp%2B&X-Amz-Signature=9c006cda8d1c9b9358ff140ebe77e4c29f0fa59ce661e202dc59e6d9171de5a1&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466546L7YY5%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T072137Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFcaCXVzLXdlc3QtMiJHMEUCIE5Ykg83Hsi5QBoYAaTLUqdoh491pcN9qPYy7QHXDOa0AiEA9ANxlR4i1gW5O33mM1AvIqAp%2ByHYuqF0QddMujvMDDYq%2FwMIcBAAGgw2Mzc0MjMxODM4MDUiDOxIEiXDOyhQF237jCrcA5%2FHp4%2BEfue%2BF0XB8tGlQKBHWR1jGssjmna33Qitkr9fJoUPh2usv5ql8oB9eBEQZhhAc%2FzxnuiGsLU4PT4NfEf9F8G50lMf9OoY6hP7It2c0OqwMxUK57dE8gB43p0Xwnks5xqarjYO%2F2cM8XwFDe3xLDlMd69H%2BRvRqwOLGBQ%2F1%2F5DJefyjetBcBdSFBSu8pmZ39gdgQGZyKF76VFfo86lNcvqD2vTrbQdU9b9xm63W88Wd004JKAAU8Xh%2B1Ca%2Ba%2BGYRjVq8Qjuxa8pj52m9XGlaZ3Khf5dFbIEgA%2BiB%2B96xETyv7AXbpoty5L9GghtTnlU1LYnwoju9Z%2B%2BHUfbw6KvPn%2B643t8aGkpK6D9qhBHmaD9BaIHoz0QxTumzzrR%2BYEHM3WpWcCdDfS0dUm8nkQYcsPOFJAId476aBrm7hZSLFoCJQ1a3w8rCjfSmss0V%2BgqoyLSJUHV9Z6jD4IbuMEtm%2BWpBv3kf09SeO14fJzLbLRNCMPi8cDQ3h7RwYPukypgadUgQdB9rTP2QKkD934Zy6ils5mGdjOa7S1XmedDaAQAreo2YD70EEtzd4fur5RHwwx3Qh2Et5%2F%2BqNUD7k%2FaiGLrKh%2F%2BsCRI1XpS73D8C%2FnUcSBvtGeElPbML%2Fflr0GOqUB2zJMAhQ1iWU0VK1xr1SL1XC1CWf%2FOzXHmleap2YrRkCsqMKoez70IuPL%2F%2BNYMgGLM3WYPCV2wfUD%2BxB4mWkvbAtehykACJb3bbr0NDoQb7XuKHuQymRRRiB97NWxAX4JAJIFto%2BY%2FbqgQKZmzVdsKCEKhHmAo3cUdIiQAD33yjiNa1RXyjF6u826y%2BxxwVA2ypLo2II4YNCHLoro5IWhghy0Ncp%2B&X-Amz-Signature=5a21a6bca24688ef20f77e77ea4c60bc52d795586429c421aa2f8ebb370f3c92&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VRBPGNI4%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T072137Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFcaCXVzLXdlc3QtMiJHMEUCIQCui7QSa2lpkUtA1E9hGB9E%2FS10Umc01m%2FXSDQrZiiRjQIgayLaxBh4TZHs9xfL78dmiRf%2B7a7ZjKJg38gRJiDiJscq%2FwMIcBAAGgw2Mzc0MjMxODM4MDUiDHOF9hPdO0ksuDkYVSrcA947LQJaR3ciGE0nUa3rKX3yaTFq3K1AIkxHkvXd0oE2HRWiuvlnOW6ALJDHlePjejxm5rAdbVK6ser76snFZRoDe5Xhlz7Ru9OAHvMxP0KJyY9R3rQEYfg3s%2Bt4aZ3ZaWOKoe3Hr1%2BiKPMzGCvRbB1H7No1qTG7CD2r8b7I95ZKONGwTLx92ySZEqgAjqPuDVb3LHLhXhzlboHKuJcsYU0TG6bNp89FKWmsThX1u0c4oFBAyfr11V0qzhlg231l4uYR6ZkUNsOPqHmVDu58COi2V%2F6QgbE2k3CG%2BZ9ZX5Q8UBYKmOVj%2F7fcuZCMWjyr8FfdcZ4t4b8dZsvhqF4AnZDRckamdEWT0JmtBZCFIutzVxeocS136fWevYxQq1M5Yt%2F2ydjGsx8zFsSQiArihZI2tx7tY2kJo%2FI0szaqGnHQ6gMIs7W2c9scwItcsFgJCcU3RjSjEX14V20T6YQzr1A%2Bjp9i15DR7fgpR%2FgMCQ3aRFkjknMM1ujTRm4hisqq8Tut1AfDyvlzR8YS9hEMyVOkEmNkv%2FuIE%2BWGErcQ%2FJS%2FMVUpLFzBmtNNNy0fifYGW6iblsKGkSUYG7jHOcHtbzsZhmCQlP4O8OlPwHXbCSQTx1DfXRZkpEHawh6yMOjdlr0GOqUBlCQOGZOlLhelE%2BIN58hEORYrZbnOe6fOno%2BU85EsEl7PPsVpUCUWPCrNmaOcJJxRQDQIFe8az4G5nWnSxIZ0x%2BQfog6ffYLJ%2FxDAO2Kw%2BNR49B7kjV6KCDY%2FeXPjhPUdUpph%2Frjd2tY9Nkdht8QYNtnkVy1erRlefnYpchJThq%2BVp6GoNS8dUP4d7U%2BNl%2BD3zGswP4n7DNXjNQS7sPX%2FtsicKWKU&X-Amz-Signature=190b9d2e31268e40f2ce0d0d1ff0d41c9c7617a79b24a55c6c5dcc9ecd1d0f89&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466R34FMY7T%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T072139Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFcaCXVzLXdlc3QtMiJHMEUCIQCWMuhBCi6u8yXOwUZYm7ohmvRffv3j43CgaGxc9CGwZwIgJFZo01IvYu%2BcKnXXMMPeRrELuQ1iFOuadcbcMX2pc%2FMq%2FwMIcBAAGgw2Mzc0MjMxODM4MDUiDP0CCGRn%2BqxV%2FGTOKSrcA4TSykPWDhh0BeVTqMDq6lCw%2FA7RVqclWeajsi%2FhOE5VpSI0NWQ5LtPXJBpDvk5y5%2B6Mxk%2BnV99gI7rvjG4H4aDgs1qzAnjYx46jZTtCES9pxioVYRBV4oU3Akvvrl%2FvnOR7UnpBpmjmCrKeXNuMAPnIZP%2BZel6si%2F5kq3c2M3G3bGld5gAoTCy33x92FUaMxCVEtktS9ROB3spLIFaPrmNpO10xe8Um%2BG8REXHmF41T9YDyc7Mb%2FEqfvY2mqtIbYpo6x4W4Pc8kEPBS%2BzpnhVAI72lWefBLVkGxV5QV1FarNDgwNNn6BYBaIxdh9eLBGt4eiaIKCLG8r2qf%2BFy%2FwjiR5gsjATHnkxc9eRuMpZ2729JGS9YpWQrPqAEf8LUrTYAancSZOGbBJP9vsZUelwhV0AFr%2B2SbI8F7%2FaebXry2VykmPnO7EloAi0sFMVakk5801ap5EMpiVYS8hztSqWlB%2B1OY9oVQjHaJcgEm%2BK2n4Xv4tEjmoaoeyjmyUo8Add0NNvJ250%2B3YCMBANCwxgY39YL%2FsAtyLCxAIS%2BGbyhtEqmKhIkrzM4t6wr6CBBVYekxo7zTuYT1AFrLPP8LdGg7zj1K1st%2BoJiqtpHcLnUFyvo6bn5C2RYVhqFqMP%2Felr0GOqUBXq3Pr9dP%2BDUjQVtKlLAOkjSswzncyyhysWMAjO%2BkvonAwFIFIwp2GJE%2BO3B5VOtvT9yomFCxuUsyu5LzGK%2BUscXFMqR5lfsH0pcTtoqv%2BLOyTXEwZaFXkGTk1p2zAT82xWTu7%2FtNLF5Cl3fWiPoo5qW9CMOQKS5%2BVh7SewqmazmbSMQndc1uGk3VS1jeSc7Z1pY0%2BOv2KLmDD9n105iX6s8QZ0WC&X-Amz-Signature=8d8a85b20b048d4e091a8c8fb2cb1ef360e38436e17c364b38b20a23fa6ec79e&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466546L7YY5%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T072137Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFcaCXVzLXdlc3QtMiJHMEUCIE5Ykg83Hsi5QBoYAaTLUqdoh491pcN9qPYy7QHXDOa0AiEA9ANxlR4i1gW5O33mM1AvIqAp%2ByHYuqF0QddMujvMDDYq%2FwMIcBAAGgw2Mzc0MjMxODM4MDUiDOxIEiXDOyhQF237jCrcA5%2FHp4%2BEfue%2BF0XB8tGlQKBHWR1jGssjmna33Qitkr9fJoUPh2usv5ql8oB9eBEQZhhAc%2FzxnuiGsLU4PT4NfEf9F8G50lMf9OoY6hP7It2c0OqwMxUK57dE8gB43p0Xwnks5xqarjYO%2F2cM8XwFDe3xLDlMd69H%2BRvRqwOLGBQ%2F1%2F5DJefyjetBcBdSFBSu8pmZ39gdgQGZyKF76VFfo86lNcvqD2vTrbQdU9b9xm63W88Wd004JKAAU8Xh%2B1Ca%2Ba%2BGYRjVq8Qjuxa8pj52m9XGlaZ3Khf5dFbIEgA%2BiB%2B96xETyv7AXbpoty5L9GghtTnlU1LYnwoju9Z%2B%2BHUfbw6KvPn%2B643t8aGkpK6D9qhBHmaD9BaIHoz0QxTumzzrR%2BYEHM3WpWcCdDfS0dUm8nkQYcsPOFJAId476aBrm7hZSLFoCJQ1a3w8rCjfSmss0V%2BgqoyLSJUHV9Z6jD4IbuMEtm%2BWpBv3kf09SeO14fJzLbLRNCMPi8cDQ3h7RwYPukypgadUgQdB9rTP2QKkD934Zy6ils5mGdjOa7S1XmedDaAQAreo2YD70EEtzd4fur5RHwwx3Qh2Et5%2F%2BqNUD7k%2FaiGLrKh%2F%2BsCRI1XpS73D8C%2FnUcSBvtGeElPbML%2Fflr0GOqUB2zJMAhQ1iWU0VK1xr1SL1XC1CWf%2FOzXHmleap2YrRkCsqMKoez70IuPL%2F%2BNYMgGLM3WYPCV2wfUD%2BxB4mWkvbAtehykACJb3bbr0NDoQb7XuKHuQymRRRiB97NWxAX4JAJIFto%2BY%2FbqgQKZmzVdsKCEKhHmAo3cUdIiQAD33yjiNa1RXyjF6u826y%2BxxwVA2ypLo2II4YNCHLoro5IWhghy0Ncp%2B&X-Amz-Signature=bf7686c15055d7938c721d8997e1a8f467199802b39b51b04b3dc8a407b9799e&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466546L7YY5%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T072137Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFcaCXVzLXdlc3QtMiJHMEUCIE5Ykg83Hsi5QBoYAaTLUqdoh491pcN9qPYy7QHXDOa0AiEA9ANxlR4i1gW5O33mM1AvIqAp%2ByHYuqF0QddMujvMDDYq%2FwMIcBAAGgw2Mzc0MjMxODM4MDUiDOxIEiXDOyhQF237jCrcA5%2FHp4%2BEfue%2BF0XB8tGlQKBHWR1jGssjmna33Qitkr9fJoUPh2usv5ql8oB9eBEQZhhAc%2FzxnuiGsLU4PT4NfEf9F8G50lMf9OoY6hP7It2c0OqwMxUK57dE8gB43p0Xwnks5xqarjYO%2F2cM8XwFDe3xLDlMd69H%2BRvRqwOLGBQ%2F1%2F5DJefyjetBcBdSFBSu8pmZ39gdgQGZyKF76VFfo86lNcvqD2vTrbQdU9b9xm63W88Wd004JKAAU8Xh%2B1Ca%2Ba%2BGYRjVq8Qjuxa8pj52m9XGlaZ3Khf5dFbIEgA%2BiB%2B96xETyv7AXbpoty5L9GghtTnlU1LYnwoju9Z%2B%2BHUfbw6KvPn%2B643t8aGkpK6D9qhBHmaD9BaIHoz0QxTumzzrR%2BYEHM3WpWcCdDfS0dUm8nkQYcsPOFJAId476aBrm7hZSLFoCJQ1a3w8rCjfSmss0V%2BgqoyLSJUHV9Z6jD4IbuMEtm%2BWpBv3kf09SeO14fJzLbLRNCMPi8cDQ3h7RwYPukypgadUgQdB9rTP2QKkD934Zy6ils5mGdjOa7S1XmedDaAQAreo2YD70EEtzd4fur5RHwwx3Qh2Et5%2F%2BqNUD7k%2FaiGLrKh%2F%2BsCRI1XpS73D8C%2FnUcSBvtGeElPbML%2Fflr0GOqUB2zJMAhQ1iWU0VK1xr1SL1XC1CWf%2FOzXHmleap2YrRkCsqMKoez70IuPL%2F%2BNYMgGLM3WYPCV2wfUD%2BxB4mWkvbAtehykACJb3bbr0NDoQb7XuKHuQymRRRiB97NWxAX4JAJIFto%2BY%2FbqgQKZmzVdsKCEKhHmAo3cUdIiQAD33yjiNa1RXyjF6u826y%2BxxwVA2ypLo2II4YNCHLoro5IWhghy0Ncp%2B&X-Amz-Signature=d939496a55af78932a408f9401493cdb71db3ec747d5956ada91fac565f4cef9&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466546L7YY5%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T072137Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFcaCXVzLXdlc3QtMiJHMEUCIE5Ykg83Hsi5QBoYAaTLUqdoh491pcN9qPYy7QHXDOa0AiEA9ANxlR4i1gW5O33mM1AvIqAp%2ByHYuqF0QddMujvMDDYq%2FwMIcBAAGgw2Mzc0MjMxODM4MDUiDOxIEiXDOyhQF237jCrcA5%2FHp4%2BEfue%2BF0XB8tGlQKBHWR1jGssjmna33Qitkr9fJoUPh2usv5ql8oB9eBEQZhhAc%2FzxnuiGsLU4PT4NfEf9F8G50lMf9OoY6hP7It2c0OqwMxUK57dE8gB43p0Xwnks5xqarjYO%2F2cM8XwFDe3xLDlMd69H%2BRvRqwOLGBQ%2F1%2F5DJefyjetBcBdSFBSu8pmZ39gdgQGZyKF76VFfo86lNcvqD2vTrbQdU9b9xm63W88Wd004JKAAU8Xh%2B1Ca%2Ba%2BGYRjVq8Qjuxa8pj52m9XGlaZ3Khf5dFbIEgA%2BiB%2B96xETyv7AXbpoty5L9GghtTnlU1LYnwoju9Z%2B%2BHUfbw6KvPn%2B643t8aGkpK6D9qhBHmaD9BaIHoz0QxTumzzrR%2BYEHM3WpWcCdDfS0dUm8nkQYcsPOFJAId476aBrm7hZSLFoCJQ1a3w8rCjfSmss0V%2BgqoyLSJUHV9Z6jD4IbuMEtm%2BWpBv3kf09SeO14fJzLbLRNCMPi8cDQ3h7RwYPukypgadUgQdB9rTP2QKkD934Zy6ils5mGdjOa7S1XmedDaAQAreo2YD70EEtzd4fur5RHwwx3Qh2Et5%2F%2BqNUD7k%2FaiGLrKh%2F%2BsCRI1XpS73D8C%2FnUcSBvtGeElPbML%2Fflr0GOqUB2zJMAhQ1iWU0VK1xr1SL1XC1CWf%2FOzXHmleap2YrRkCsqMKoez70IuPL%2F%2BNYMgGLM3WYPCV2wfUD%2BxB4mWkvbAtehykACJb3bbr0NDoQb7XuKHuQymRRRiB97NWxAX4JAJIFto%2BY%2FbqgQKZmzVdsKCEKhHmAo3cUdIiQAD33yjiNa1RXyjF6u826y%2BxxwVA2ypLo2II4YNCHLoro5IWhghy0Ncp%2B&X-Amz-Signature=ca55167eec3f7eb6000a17a949871f7d0dff25ddef37a33b5418bdcc11fe5f50&X-Amz-SignedHeaders=host&x-id=GetObject)


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

