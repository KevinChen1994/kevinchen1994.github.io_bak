---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466277GVM3O%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250221T014934Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEKD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQC0Ypo3tm%2B6fi%2F\
  IYGtO8j2I8on7vlW4CoDIS3rbhAisTQIgd7FbFx2BAxLTmrYSrsXOkdw4Frv4rWjDjDalsnul%2Be\
  MqiAQIyf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDB9HguAIk43aQni\
  w0ircA%2BGm4ZBse7NISwnPDnUFLZhCmAswQOG6jHpKkRMoTUYVoDwnmdMmatjh0zPOroRvag3ItX\
  0Deho39yhKLnecddmgGAAz1SIy%2FYo%2B5C8Zqw%2BRJ6VZOk8%2F6u8F2FsMH7kl6nx5CZk8%2F\
  %2FFjLnT5FAI6i%2BDI656%2FD6z27farCIFym%2FE5sbfbWoUY4tgut8n%2Bb6PRal9x9yVfn8fV\
  yN6d5CrB8KAZr%2FFKjdMf2rXmEwOuyArkqTmNTMUc1Nij3IKJijQ47CaW9AHqE8zReKkzOFNPNGl\
  DcFVU7gaFrR1F6QgGv%2BSjj9GC%2Bsj9zL8LcWBEmLWjUgI%2BjjUVcAXg3LO1N2Sm%2FTDlZEBt\
  GSX07QcVgr9CcHMlP3ofAbyyAyzPeBQX5C3X0kKA4o42Tlz%2FsJ4pgRCsyg22KIN%2F%2BpIPiDb\
  grlFTESJFADfE%2FXuTG%2BY1qwDbaGet2kiBy%2FjWH90LBduIkzFKEbpjI0YgJGfgvtsinLFaJP\
  zDthl9wIRbAGhv3enwkKqaz9qt7hq0zpUSeghWCkNfFKNkfsjbuB7QppZozNjd3amtYMag7wnQmau\
  Lj7ix3PnYFdO65z5EWPIzeiBmm4ujHDJY1CrhZjHPwrK6JqvDnTHPMxCBTnXQIVdDxG6oMPKD370G\
  OqUBXHB6R09Kha0uEHpHXMswcwLr7P4fp9MHRW%2F9V0sGDKNy9If6fSyxcxclVICbLLckxAIolEi\
  dbgJu40qg7a3WuJLjqc8SOtPYiMx1exmTznaVm%2F0jjncaGBk27iAXu19wZX7eNyPlXdUk%2Bt5R\
  91ffrB1wHGJgqO7S%2FAj2Ngi7sl6ldS108GwvGWwmHf3XicDaCCJmtZTDnrLMAXiPaAJCyJt%2FK\
  s9Y&X-Amz-Signature=a6ee605d5759ed0f71607b6266b948fd0903682cf5e6b4c0ac732c05c\
  cea8c7b&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466YOVZWGCF%2F20250221%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250221T014754Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEKD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQ\
        CIFxT1gRuppU%2Bfp85MKdC4JEMp%2BgmJBPSZ5ScJZE7gg1MAiBuHVV1kKuMkIVp5j%2B%\
        2BebO9oe15Hkh2Y5tEiNF66FKpnCqIBAjJ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaD\
        DYzNzQyMzE4MzgwNSIMkG7O3bm4Dze40szfKtwDjNpM7keXxNajUwKbcX6ptbvMeSHPZsHk\
        aFRx3HJ55U3FH6X51Zm2jPRGiK9jmGfslxPgqk68ZBo245F0eCRGuKypFxfX8SHeyxgsLBR\
        cc7At%2F2KNROIQflxpKstBdBigcm8q%2BWOw%2BSc1cjMVMKrQ8X5urCDGSARRuKAO0RLs\
        D7%2F%2FOuoKguRebxWB%2Fw5XOZQ56M4t7y3nmURA0qD21IKepDiICiYAQIgPQNuMVqi2a\
        jkAQvJDjIqkQZXpsWwOH8ovME6YbHXyWZvHN0uzqv2wtPoEfsP19HElXLGlxnQwAwOD%2F4\
        N1361%2BGMmNAxAI8FLAANHzCfeduCk70%2F%2FzPP%2Bsi1RrlssXEgN0VjwvVv9Z5hOqh\
        GnfjQW8wmNNAHDzU4rqPhveJpHtMqFbN2HqyJyi7yxEZbfWOmjIusq3tGOg4n2VlqsMBjuw\
        r86HlT%2FzAJrlrPnRLme1b5VEifyzbWVHlsz5deh9QK3KfcoGkVdf4lET15n%2BpF%2FkM\
        nFmO36fPnb5LdjRtN%2FHVDmSIGUq1mAFXLNCkULVnQx7r%2FbvvNgjqdPRWLGUbgDKHCgq\
        Nocx3krytAtzX95bSLdUUBNajthOA%2FElDZwXxiEb0bccQY2OYI%2FACueymCUyj5qRpB8\
        wkIXfvQY6pgF5bSM5cEgR3WsiKRkjvLgGI8epSISzOe5a%2FFmsK4Z4M8lGxBTTU9qlUGU4\
        8uiu21A2RbueGM6O5QE3KGY9%2F8%2F6kySZ%2FHeD%2BnI50WA2rXBSmOlEhXLjxRug4wO\
        p%2FfuQHckzaoC%2F7qMs3JCZHWrssxz8%2Bj5XEOSXdWNVsYx3ZDUzHidWFE7RwNrXBUFm\
        II8g1ocTv54JnzRkxNdaV8zgC0udxo4o8oKt&X-Amz-Signature=c47ec42e2ce865a009\
        7b6005fb22f99c86be99b7891c1b5704d959a82024d1ce&X-Amz-SignedHeaders=host\
        &x-id=GetObject"
      expiry_time: "2025-02-21T02:47:54.941Z"
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
UPDATE_TIME: "2025-02-21T01:49:47.815Z"
EXPIRY_TIME: "2025-02-21T02:49:30.561Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YK65VLJU%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T014931Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIFks95RW9EI14MICR%2Bjt4x9z6g%2BKvYMJoydaR2y%2FpGMLAiEA2I4OOCHjgDSoig8UuxcRKnpfADPn2Ot0GwpfNKPv%2FsQqiAQIyf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNX9KSIRTRs9bjz78SrcA73JfjRHpSDNA0zIl6MHAfQg5O1cD%2BAbWPL03pDD0QuHyAuKl3GrfrhpswZxQe168jDiVh8znbHkAXeCUx%2FOajfJuLxIPT6n21wkqqDU9EVW3sMgusyGGg7V1KgQcqhCpC7lMhxiaV1u55OBX29nInD0zN8WrwtFpcUOyifLnatrA2C4aQjqpRRSErC%2BAZ05Ya6lgcXApHvLV9K3UpdVdJAIUi%2BtB4i%2BPrhHQady%2FFnrMj%2BqfCABwbsv%2Fu9pMWlcHJjG8A%2FkrKNjqlOjotOBwZbeBxkk2zC7o3EAntLchmTj8%2FcUim7fdhhQ87dhh1X6l0oGYN%2BNVb7GECX39Z47QqFpIY56BDVOzY8hiub7VCUNaLx6rcAToRzCySPrw4Quu2zrAWLV405IFyQYFkwtI3zx7tq25JRR821qa9wPcDg9%2B6UJT9pKmKuT46RZbkqCbana9gz3jCZaY%2B10uhwtrCotpn9HUNns7TOTuvK86MwI%2FLEYCOZ02AVAdfQY5lq7um5tswfmQKREcF%2BxUXgCu7QC6Q7M7X2W%2B%2FxrwO3N6l3RtjnboUbogULI4rAdin6OzcpH%2FQ1ly8TTfNDH2guC5IjQqXn1dhUnYEXvB%2BoiXzYyKS55HCB52ELJrcXIMJyF370GOqUBzIIBUkQicwhel2rj2a6TAh9DOW7vvIkJlR2ESijhoQRdPwUPROq8bNfkNJMOg6w5FJx%2BJ4QuHSQnXj1U6DI3GIrqXYd4Sm8Xqp83LsT9z6BKIfrzM1Bz%2F8t18Di%2FttGc%2BjshE%2Fxhxh%2B8B8SGK%2BxH7VjMfLWfUqAH5x7vYm96m7Wy0XTkamEFkqsnHXw2yrEyx%2BNfpuEc8wWkqqZ6V1XHbGCbh7nN&X-Amz-Signature=d5d88f13296587193020eaced237c2916d6c5e53d3cc7b9e561c6d92b6bfbed3&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YK65VLJU%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T014931Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIFks95RW9EI14MICR%2Bjt4x9z6g%2BKvYMJoydaR2y%2FpGMLAiEA2I4OOCHjgDSoig8UuxcRKnpfADPn2Ot0GwpfNKPv%2FsQqiAQIyf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNX9KSIRTRs9bjz78SrcA73JfjRHpSDNA0zIl6MHAfQg5O1cD%2BAbWPL03pDD0QuHyAuKl3GrfrhpswZxQe168jDiVh8znbHkAXeCUx%2FOajfJuLxIPT6n21wkqqDU9EVW3sMgusyGGg7V1KgQcqhCpC7lMhxiaV1u55OBX29nInD0zN8WrwtFpcUOyifLnatrA2C4aQjqpRRSErC%2BAZ05Ya6lgcXApHvLV9K3UpdVdJAIUi%2BtB4i%2BPrhHQady%2FFnrMj%2BqfCABwbsv%2Fu9pMWlcHJjG8A%2FkrKNjqlOjotOBwZbeBxkk2zC7o3EAntLchmTj8%2FcUim7fdhhQ87dhh1X6l0oGYN%2BNVb7GECX39Z47QqFpIY56BDVOzY8hiub7VCUNaLx6rcAToRzCySPrw4Quu2zrAWLV405IFyQYFkwtI3zx7tq25JRR821qa9wPcDg9%2B6UJT9pKmKuT46RZbkqCbana9gz3jCZaY%2B10uhwtrCotpn9HUNns7TOTuvK86MwI%2FLEYCOZ02AVAdfQY5lq7um5tswfmQKREcF%2BxUXgCu7QC6Q7M7X2W%2B%2FxrwO3N6l3RtjnboUbogULI4rAdin6OzcpH%2FQ1ly8TTfNDH2guC5IjQqXn1dhUnYEXvB%2BoiXzYyKS55HCB52ELJrcXIMJyF370GOqUBzIIBUkQicwhel2rj2a6TAh9DOW7vvIkJlR2ESijhoQRdPwUPROq8bNfkNJMOg6w5FJx%2BJ4QuHSQnXj1U6DI3GIrqXYd4Sm8Xqp83LsT9z6BKIfrzM1Bz%2F8t18Di%2FttGc%2BjshE%2Fxhxh%2B8B8SGK%2BxH7VjMfLWfUqAH5x7vYm96m7Wy0XTkamEFkqsnHXw2yrEyx%2BNfpuEc8wWkqqZ6V1XHbGCbh7nN&X-Amz-Signature=479dfc8fa6ddeab33f0fea7346b8c3e8f3a28d6eafb587a16e3295b006a341b2&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YK65VLJU%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T014931Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIFks95RW9EI14MICR%2Bjt4x9z6g%2BKvYMJoydaR2y%2FpGMLAiEA2I4OOCHjgDSoig8UuxcRKnpfADPn2Ot0GwpfNKPv%2FsQqiAQIyf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNX9KSIRTRs9bjz78SrcA73JfjRHpSDNA0zIl6MHAfQg5O1cD%2BAbWPL03pDD0QuHyAuKl3GrfrhpswZxQe168jDiVh8znbHkAXeCUx%2FOajfJuLxIPT6n21wkqqDU9EVW3sMgusyGGg7V1KgQcqhCpC7lMhxiaV1u55OBX29nInD0zN8WrwtFpcUOyifLnatrA2C4aQjqpRRSErC%2BAZ05Ya6lgcXApHvLV9K3UpdVdJAIUi%2BtB4i%2BPrhHQady%2FFnrMj%2BqfCABwbsv%2Fu9pMWlcHJjG8A%2FkrKNjqlOjotOBwZbeBxkk2zC7o3EAntLchmTj8%2FcUim7fdhhQ87dhh1X6l0oGYN%2BNVb7GECX39Z47QqFpIY56BDVOzY8hiub7VCUNaLx6rcAToRzCySPrw4Quu2zrAWLV405IFyQYFkwtI3zx7tq25JRR821qa9wPcDg9%2B6UJT9pKmKuT46RZbkqCbana9gz3jCZaY%2B10uhwtrCotpn9HUNns7TOTuvK86MwI%2FLEYCOZ02AVAdfQY5lq7um5tswfmQKREcF%2BxUXgCu7QC6Q7M7X2W%2B%2FxrwO3N6l3RtjnboUbogULI4rAdin6OzcpH%2FQ1ly8TTfNDH2guC5IjQqXn1dhUnYEXvB%2BoiXzYyKS55HCB52ELJrcXIMJyF370GOqUBzIIBUkQicwhel2rj2a6TAh9DOW7vvIkJlR2ESijhoQRdPwUPROq8bNfkNJMOg6w5FJx%2BJ4QuHSQnXj1U6DI3GIrqXYd4Sm8Xqp83LsT9z6BKIfrzM1Bz%2F8t18Di%2FttGc%2BjshE%2Fxhxh%2B8B8SGK%2BxH7VjMfLWfUqAH5x7vYm96m7Wy0XTkamEFkqsnHXw2yrEyx%2BNfpuEc8wWkqqZ6V1XHbGCbh7nN&X-Amz-Signature=ff226833d7dbdb33fc21760f631b5da444f31b1cbc084506f2f78867c755140e&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YK65VLJU%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T014931Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIFks95RW9EI14MICR%2Bjt4x9z6g%2BKvYMJoydaR2y%2FpGMLAiEA2I4OOCHjgDSoig8UuxcRKnpfADPn2Ot0GwpfNKPv%2FsQqiAQIyf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNX9KSIRTRs9bjz78SrcA73JfjRHpSDNA0zIl6MHAfQg5O1cD%2BAbWPL03pDD0QuHyAuKl3GrfrhpswZxQe168jDiVh8znbHkAXeCUx%2FOajfJuLxIPT6n21wkqqDU9EVW3sMgusyGGg7V1KgQcqhCpC7lMhxiaV1u55OBX29nInD0zN8WrwtFpcUOyifLnatrA2C4aQjqpRRSErC%2BAZ05Ya6lgcXApHvLV9K3UpdVdJAIUi%2BtB4i%2BPrhHQady%2FFnrMj%2BqfCABwbsv%2Fu9pMWlcHJjG8A%2FkrKNjqlOjotOBwZbeBxkk2zC7o3EAntLchmTj8%2FcUim7fdhhQ87dhh1X6l0oGYN%2BNVb7GECX39Z47QqFpIY56BDVOzY8hiub7VCUNaLx6rcAToRzCySPrw4Quu2zrAWLV405IFyQYFkwtI3zx7tq25JRR821qa9wPcDg9%2B6UJT9pKmKuT46RZbkqCbana9gz3jCZaY%2B10uhwtrCotpn9HUNns7TOTuvK86MwI%2FLEYCOZ02AVAdfQY5lq7um5tswfmQKREcF%2BxUXgCu7QC6Q7M7X2W%2B%2FxrwO3N6l3RtjnboUbogULI4rAdin6OzcpH%2FQ1ly8TTfNDH2guC5IjQqXn1dhUnYEXvB%2BoiXzYyKS55HCB52ELJrcXIMJyF370GOqUBzIIBUkQicwhel2rj2a6TAh9DOW7vvIkJlR2ESijhoQRdPwUPROq8bNfkNJMOg6w5FJx%2BJ4QuHSQnXj1U6DI3GIrqXYd4Sm8Xqp83LsT9z6BKIfrzM1Bz%2F8t18Di%2FttGc%2BjshE%2Fxhxh%2B8B8SGK%2BxH7VjMfLWfUqAH5x7vYm96m7Wy0XTkamEFkqsnHXw2yrEyx%2BNfpuEc8wWkqqZ6V1XHbGCbh7nN&X-Amz-Signature=c73b19f4536fd15dc0d8403fec98ccf4aa46c3661ab67676ff3d2907be0c96e2&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YK65VLJU%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T014931Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIFks95RW9EI14MICR%2Bjt4x9z6g%2BKvYMJoydaR2y%2FpGMLAiEA2I4OOCHjgDSoig8UuxcRKnpfADPn2Ot0GwpfNKPv%2FsQqiAQIyf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNX9KSIRTRs9bjz78SrcA73JfjRHpSDNA0zIl6MHAfQg5O1cD%2BAbWPL03pDD0QuHyAuKl3GrfrhpswZxQe168jDiVh8znbHkAXeCUx%2FOajfJuLxIPT6n21wkqqDU9EVW3sMgusyGGg7V1KgQcqhCpC7lMhxiaV1u55OBX29nInD0zN8WrwtFpcUOyifLnatrA2C4aQjqpRRSErC%2BAZ05Ya6lgcXApHvLV9K3UpdVdJAIUi%2BtB4i%2BPrhHQady%2FFnrMj%2BqfCABwbsv%2Fu9pMWlcHJjG8A%2FkrKNjqlOjotOBwZbeBxkk2zC7o3EAntLchmTj8%2FcUim7fdhhQ87dhh1X6l0oGYN%2BNVb7GECX39Z47QqFpIY56BDVOzY8hiub7VCUNaLx6rcAToRzCySPrw4Quu2zrAWLV405IFyQYFkwtI3zx7tq25JRR821qa9wPcDg9%2B6UJT9pKmKuT46RZbkqCbana9gz3jCZaY%2B10uhwtrCotpn9HUNns7TOTuvK86MwI%2FLEYCOZ02AVAdfQY5lq7um5tswfmQKREcF%2BxUXgCu7QC6Q7M7X2W%2B%2FxrwO3N6l3RtjnboUbogULI4rAdin6OzcpH%2FQ1ly8TTfNDH2guC5IjQqXn1dhUnYEXvB%2BoiXzYyKS55HCB52ELJrcXIMJyF370GOqUBzIIBUkQicwhel2rj2a6TAh9DOW7vvIkJlR2ESijhoQRdPwUPROq8bNfkNJMOg6w5FJx%2BJ4QuHSQnXj1U6DI3GIrqXYd4Sm8Xqp83LsT9z6BKIfrzM1Bz%2F8t18Di%2FttGc%2BjshE%2Fxhxh%2B8B8SGK%2BxH7VjMfLWfUqAH5x7vYm96m7Wy0XTkamEFkqsnHXw2yrEyx%2BNfpuEc8wWkqqZ6V1XHbGCbh7nN&X-Amz-Signature=d9293e2a8c64b4805cd781a03a8d8b71a053045517af870316aa8bb0be5cbd6a&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46643QLDB5S%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T014931Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDNjc%2BGyzvJGOGkTDwkO1jQ8F%2FqZKGLPch8oddFtJAP6wIgFgizOnQWbTa9KYca562Knnnx%2BZbLNbTcgJDyiWYdVYsqiAQIyf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOMUS7UbQRY5vqx5xSrcA0APHFz%2BYfin8lMSZYX5%2BuPuMwOR22MW%2F8mp3xs7o82FcW0QESZvsfbjFM13J3Tpr7Xk7DaIoqwUBoNDEe6TpKV%2B%2BYCbj3MKNxlj5AalLyqCSajSYT0bt8HbHDpGcQqW5AzagtlpPBAtBtyKhlrndUUy7sr8YN8l1bRQDJALh9gqN4bGqBuzkMVjtduuJBduhRkXlaCzCgbWAO8Kg81FQmzsmaEBZ2lLdMwfE5B%2BlKDKjj1gpux7I%2FNXMPekxVVUcjc50ViPqfxgclF9wUt6k9z1Jkjm5SW0LpiK9XfW6rGFUp%2Bws5aORtrvxLI1xIfAhE4TzSbYs8jq4uXC791QdZCurJvUbu2IT6mqOfYvTDXOkhyCQkYkzDlrHYn%2BRrEuVSwgrlMYbPOiHusBkevIa8i1oSlXjtC8FAM0E5jyBdFSPQJG3h5XY87216m0K7954Yj43ZTj7d44hLrdFYmIvAMct%2F%2FBrZ2DrbOOWizOEUN5aqnR5d8pLV11nPMPf2mqWlqGZ9DzVn4ef1FEYgWMBfouaICbGEQSwGUm7rFBEqL7t0OXPK%2FgB%2BS0u7Yp5bmwOlE%2FUhzXmGK03oALU39KHFBoelx5CwKWMDVSp943MgHEvpOYaX44uEe9CQ0JMKSF370GOqUBiFGvl2WkZbjK9R%2B4DtM8DfJJhYJsv1Raa%2BvU4ezWQpxwq2LDca5pjQYKaEwi4NnpfKGgfnD23dU0tF4G39romMI9WIE7wWnqD9OsEWpezBWOjWLccYabHcMNWsglS4i8znsTEK%2F3cuRyk6zBwPwV2XIHBCbCfr4IsBUv6w8jq1AY02Ql6376IWhJo%2BpVPJjqZIdEci7nVdkWdtc4VvZJ0n6ujt9Z&X-Amz-Signature=e3b9fd64df5920e6b94dbe9e30ccfd557bae974399300857d4550e4a0d22b6f1&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z53YVJH7%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T014934Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICxjI0GlIc1nmGMMkdNPXKEUk8retfUDqX0Xu%2B86RgLpAiB8gTk0WdyqHbR0IMpCDNxjbAas8G9y2dz8c7kRWLw32iqIBAjJ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM2FHGYmay%2BMAPl99cKtwDhjCP6Eyg%2Fbxw5Pk5xT7wv6dU2yvfVUdSYNEqSnf0aPnDNYWfS2Nx%2BlRCkf3llLu0%2Bm0gkKHi%2FqhdfhKFETsHqQOK%2FLpmvY7xtCBUgVRaoh4hZFYi2HmP%2FYJg63xPZzmTRIBaSAhhLEroYSQnLDHIb%2B4zPrbELCY8qb6KYr0Kh1fFWzLwWTlc7TmVuHd9%2FuUVLIukMHo6s6hKBKiPVZ%2B8mNOyTWQaaOqaXKMACXp88HnK%2FJk0ykWjhAMug5XH2efOiHusB%2BsVgIaJ0iruPU9J5ZORKm6bcO65K5yHvx58Zp89AlcneOO7kFces9l6ImUDbxWxJH1Yfn7UaXEwhxWACeuHiNsmY5%2FWCPyFnxNz3G3fjx8IMAaMnLYsyy4dicRKHqQeP6mtBoFlkh6Cnv%2FQJQjllFFLHIEIc2mfXRFIS3wCXH8CYBKnbN9TVxtk7cnOfVazoSzRPGHF02lgsWUp7HGt%2FvzD103LscuUu4BsOzMn0BoZo3L30U1hwbdlHhbyiKD8KE0f3jYXqyazuYXtIuQPxJMLmSomF6JAPcVLda6FSFhaUgJsMgKwMLSosjGaC%2FmC3FiFsYZxzE2ejoMWiASwgpnc7VT%2ByRdSreFTL8wQV08TyAhTwGyFxLswoYXfvQY6pgGLj1BVYDNwxg3jbETHMah3rI7Y%2FXP4j0HiroT5i%2F1CidLCUKcLBcoUgSbSA26f67uMoLRpq%2ByCbDnB2j7oYnzYz%2BHlESD1xuWjPzpY6%2F9ZtJKOD9Xl0JJg9O2f39HparLachwSS6cA%2FMIYx4G%2BROmGrpElecPxKKf9XBpCHcPsnF6%2B%2FRnvA61Ru31jbxGjOp7Tg9ZF4X8%2F9KRgvs3pqGYskVxJ4ChP&X-Amz-Signature=cf05405e35176ce3939bd732a4525cd1b3a93a36967ce5490c5e92fae380cdd2&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YK65VLJU%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T014931Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIFks95RW9EI14MICR%2Bjt4x9z6g%2BKvYMJoydaR2y%2FpGMLAiEA2I4OOCHjgDSoig8UuxcRKnpfADPn2Ot0GwpfNKPv%2FsQqiAQIyf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNX9KSIRTRs9bjz78SrcA73JfjRHpSDNA0zIl6MHAfQg5O1cD%2BAbWPL03pDD0QuHyAuKl3GrfrhpswZxQe168jDiVh8znbHkAXeCUx%2FOajfJuLxIPT6n21wkqqDU9EVW3sMgusyGGg7V1KgQcqhCpC7lMhxiaV1u55OBX29nInD0zN8WrwtFpcUOyifLnatrA2C4aQjqpRRSErC%2BAZ05Ya6lgcXApHvLV9K3UpdVdJAIUi%2BtB4i%2BPrhHQady%2FFnrMj%2BqfCABwbsv%2Fu9pMWlcHJjG8A%2FkrKNjqlOjotOBwZbeBxkk2zC7o3EAntLchmTj8%2FcUim7fdhhQ87dhh1X6l0oGYN%2BNVb7GECX39Z47QqFpIY56BDVOzY8hiub7VCUNaLx6rcAToRzCySPrw4Quu2zrAWLV405IFyQYFkwtI3zx7tq25JRR821qa9wPcDg9%2B6UJT9pKmKuT46RZbkqCbana9gz3jCZaY%2B10uhwtrCotpn9HUNns7TOTuvK86MwI%2FLEYCOZ02AVAdfQY5lq7um5tswfmQKREcF%2BxUXgCu7QC6Q7M7X2W%2B%2FxrwO3N6l3RtjnboUbogULI4rAdin6OzcpH%2FQ1ly8TTfNDH2guC5IjQqXn1dhUnYEXvB%2BoiXzYyKS55HCB52ELJrcXIMJyF370GOqUBzIIBUkQicwhel2rj2a6TAh9DOW7vvIkJlR2ESijhoQRdPwUPROq8bNfkNJMOg6w5FJx%2BJ4QuHSQnXj1U6DI3GIrqXYd4Sm8Xqp83LsT9z6BKIfrzM1Bz%2F8t18Di%2FttGc%2BjshE%2Fxhxh%2B8B8SGK%2BxH7VjMfLWfUqAH5x7vYm96m7Wy0XTkamEFkqsnHXw2yrEyx%2BNfpuEc8wWkqqZ6V1XHbGCbh7nN&X-Amz-Signature=6070f82c96e577c157190aabead374dc13f9dca85dc3fc8e979977ce90c53ddb&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YK65VLJU%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T014931Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIFks95RW9EI14MICR%2Bjt4x9z6g%2BKvYMJoydaR2y%2FpGMLAiEA2I4OOCHjgDSoig8UuxcRKnpfADPn2Ot0GwpfNKPv%2FsQqiAQIyf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNX9KSIRTRs9bjz78SrcA73JfjRHpSDNA0zIl6MHAfQg5O1cD%2BAbWPL03pDD0QuHyAuKl3GrfrhpswZxQe168jDiVh8znbHkAXeCUx%2FOajfJuLxIPT6n21wkqqDU9EVW3sMgusyGGg7V1KgQcqhCpC7lMhxiaV1u55OBX29nInD0zN8WrwtFpcUOyifLnatrA2C4aQjqpRRSErC%2BAZ05Ya6lgcXApHvLV9K3UpdVdJAIUi%2BtB4i%2BPrhHQady%2FFnrMj%2BqfCABwbsv%2Fu9pMWlcHJjG8A%2FkrKNjqlOjotOBwZbeBxkk2zC7o3EAntLchmTj8%2FcUim7fdhhQ87dhh1X6l0oGYN%2BNVb7GECX39Z47QqFpIY56BDVOzY8hiub7VCUNaLx6rcAToRzCySPrw4Quu2zrAWLV405IFyQYFkwtI3zx7tq25JRR821qa9wPcDg9%2B6UJT9pKmKuT46RZbkqCbana9gz3jCZaY%2B10uhwtrCotpn9HUNns7TOTuvK86MwI%2FLEYCOZ02AVAdfQY5lq7um5tswfmQKREcF%2BxUXgCu7QC6Q7M7X2W%2B%2FxrwO3N6l3RtjnboUbogULI4rAdin6OzcpH%2FQ1ly8TTfNDH2guC5IjQqXn1dhUnYEXvB%2BoiXzYyKS55HCB52ELJrcXIMJyF370GOqUBzIIBUkQicwhel2rj2a6TAh9DOW7vvIkJlR2ESijhoQRdPwUPROq8bNfkNJMOg6w5FJx%2BJ4QuHSQnXj1U6DI3GIrqXYd4Sm8Xqp83LsT9z6BKIfrzM1Bz%2F8t18Di%2FttGc%2BjshE%2Fxhxh%2B8B8SGK%2BxH7VjMfLWfUqAH5x7vYm96m7Wy0XTkamEFkqsnHXw2yrEyx%2BNfpuEc8wWkqqZ6V1XHbGCbh7nN&X-Amz-Signature=a4727d986e07be6905cc0b9d2d84fa9e76cabaf287c7bb17310b60a550ea045f&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YK65VLJU%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T014931Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIFks95RW9EI14MICR%2Bjt4x9z6g%2BKvYMJoydaR2y%2FpGMLAiEA2I4OOCHjgDSoig8UuxcRKnpfADPn2Ot0GwpfNKPv%2FsQqiAQIyf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNX9KSIRTRs9bjz78SrcA73JfjRHpSDNA0zIl6MHAfQg5O1cD%2BAbWPL03pDD0QuHyAuKl3GrfrhpswZxQe168jDiVh8znbHkAXeCUx%2FOajfJuLxIPT6n21wkqqDU9EVW3sMgusyGGg7V1KgQcqhCpC7lMhxiaV1u55OBX29nInD0zN8WrwtFpcUOyifLnatrA2C4aQjqpRRSErC%2BAZ05Ya6lgcXApHvLV9K3UpdVdJAIUi%2BtB4i%2BPrhHQady%2FFnrMj%2BqfCABwbsv%2Fu9pMWlcHJjG8A%2FkrKNjqlOjotOBwZbeBxkk2zC7o3EAntLchmTj8%2FcUim7fdhhQ87dhh1X6l0oGYN%2BNVb7GECX39Z47QqFpIY56BDVOzY8hiub7VCUNaLx6rcAToRzCySPrw4Quu2zrAWLV405IFyQYFkwtI3zx7tq25JRR821qa9wPcDg9%2B6UJT9pKmKuT46RZbkqCbana9gz3jCZaY%2B10uhwtrCotpn9HUNns7TOTuvK86MwI%2FLEYCOZ02AVAdfQY5lq7um5tswfmQKREcF%2BxUXgCu7QC6Q7M7X2W%2B%2FxrwO3N6l3RtjnboUbogULI4rAdin6OzcpH%2FQ1ly8TTfNDH2guC5IjQqXn1dhUnYEXvB%2BoiXzYyKS55HCB52ELJrcXIMJyF370GOqUBzIIBUkQicwhel2rj2a6TAh9DOW7vvIkJlR2ESijhoQRdPwUPROq8bNfkNJMOg6w5FJx%2BJ4QuHSQnXj1U6DI3GIrqXYd4Sm8Xqp83LsT9z6BKIfrzM1Bz%2F8t18Di%2FttGc%2BjshE%2Fxhxh%2B8B8SGK%2BxH7VjMfLWfUqAH5x7vYm96m7Wy0XTkamEFkqsnHXw2yrEyx%2BNfpuEc8wWkqqZ6V1XHbGCbh7nN&X-Amz-Signature=2552e904ab19c0091a54a62aef36e8532834bbf2fa481b7e2e49a94123485ca3&X-Amz-SignedHeaders=host&x-id=GetObject)


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

