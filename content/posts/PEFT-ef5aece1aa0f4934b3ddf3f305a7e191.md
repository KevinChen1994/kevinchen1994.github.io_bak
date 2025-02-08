---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466UGQEKX23%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250208T182840Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEHsaCXVzLXdlc3QtMiJHMEUCIQDeMSyN%2FG3KonepsqJJR4629Zwzuchf%2FMTukffs1FPXKgI\
  gTzZGz5cnRFYSyjNSnutj6yF%2B1RiwZn7TX9G6iUfMoUYqiAQIk%2F%2F%2F%2F%2F%2F%2F%2F%\
  2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGbsoeEl%2BSf2iXZm5ircAyhKuGc8y9TPvxldkUDbr%2\
  FJOdzffgPYK9cUJuonYBQ%2Br39oMiPpCv2YxkAEoZhyjDEC3hi9aPYqkhteFMBiaDs7xkd7LCB%2\
  Bp4GQqSr%2F6%2F7j8r0f3r2m3107kDhyQy6PUZ38v2pYb3u4lmZQ65SilAieuR78w09O%2FSccHt\
  CoEku2mLk0oHwQB2oZZZbW5CD7fO5cQjscMtc7C6ni1dkItNN02%2Bx%2FThuIA3Ssg6FknSwUazy\
  Jd7zEicryjT%2FUwX9EcOw4vgHe4BANvFZAC2VdoTInAqwTW%2Fh5oUdQI7xnZklQpLdZBThb3nmO\
  XJIVN58%2BZxxZBlsI8IWggnm5P7j4LOlYPuS%2BwMC%2FovnEmP7vO1NSks%2FH7xTTz9RakpvNn\
  LVfvUTRAZv4h%2FuCYgwczAI5jL%2Fp%2FrHNxe%2FWIwmisjfqHxp7he60FNxbKhkRr4%2FLPl0u\
  8VTdO0FG35gmLwfOJMm3%2BrCfma7JfkcDLBLsfZMnChKsDwRb%2FOluMsYNExSTiM3IWnkCgXIjK\
  SoRLLfku7zB3TDDESPJ%2FWZtAWQQMxFgDo0Fwa2N7fP6CSJJUWx1TB4W84WWm8yoxr7l02hDunPF\
  z3oFVXAcdDVGeCZtud%2B6ZIvCbOGqzU%2FIE1LrpGHSfMKLBnr0GOqUBU1novOb2fSwsMa6BDPqs\
  DynsPtnuaeaypLH5VG1Hpd0oBJ5up%2B30LFDOfdSYcef3azGDvx9c63vxUg6PTTFCsNElzblLa8c\
  5deBXG9EcLjBc7bFpinm1AKtu7lYBFnJyn1iJ94iRY2%2FUC6ffrKQG5eFRtVoah%2F6M7cVS2vB8\
  l%2BTepFrSOiIRjEC8H7xFviEZjjBah0CDzirUscqqRrx4hparffeG&X-Amz-Signature=3af993\
  200935aa31f0d90de8c5ad5e7da767bd2e2036ef84c0925e5b99499979&X-Amz-SignedHeader\
  s=host&x-id=GetObject"
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
        redential=ASIAZI2LB466Q65YPOYR%2F20250208%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250208T182725Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJIMEYCIQDJQCX1iz4%2B4iDlSsZJgMEDurXhh\
        SIgF9SthRG%2FfrH01AIhAP7LogGzp6PtGG2GLKEz%2B1wxZn5Q39RoZmmRJAvhkaRkKogE\
        CJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzMCPNJEbgrEAk\
        R8vQq3ANJiXeG8a4GX%2BFoJJajkBhFxBb9fLwsJMrKLGfx2adpPh013s5BPDAsMw3DVdwx\
        fAxfG%2B5MIv85MkS%2F18fbhW58M7hF4%2FcAQY%2Bxxo9RdDb5ZTD%2B5OddePRx9lQ%2\
        FX0xodyCCrhTeyN2s0AKQYozKiS18EIKLCPGipgjV8YxQ3eHnDjefOw9eTHpXzSBZPqAHfV\
        hAI5R%2Bn8pZME279AHz53Q2ZH1q9Z7p66f25c%2F26MJOTeJpuq5qIHygZUJcjRsICQvtd\
        H5tH3VskDAF6v9iUURGWkHfrbpg9%2F20ojalic%2F2Du1%2Bp5lCsaXjvBA10YqiVVenkX\
        gxGTMFs3pL8xSUcdwVKw5bBXtOi86d8K5K6JKDcXJfpfp%2FmRxihWHGHx9EMa%2Bo3E3lY\
        r45s70FP%2Fyyu%2F%2BbCLemG5EFqgGnqlLMqkElqXC5LRgsnjlyzHl9QGCPjUAt2%2F%2\
        FrczWUcux5o9Htu41cfEgNvIvGplJRFZOXCtNJumoHnZuFUTL4PuCSiJmrqHhUkd6%2FYDP\
        LTI7NPHWTxXZjmMmFTkP7%2FPZboOWwhk1RhI42pjt9YoiqQ8UHFs4uHYaOL7%2FjFtOYME\
        lvHPA2dicWC5zIRPzT9WnVltKL3eL4O72UqcltA3V%2Fn%2FJR9DCYw569BjqkAf%2Fdm4d\
        TpSDd7FeqpRyeYVG0svu9KpYjTWR%2BXEaZlAtibjCJmxzVBQd4BOePuyMKstGAErP56zhG\
        t%2BJtpMaUJAYW3eBARiUs7gLE5t7WaVZYUSZ%2Bf2KRqrbRYzg6lSrbMPc28se6AtldN8E\
        %2FIVWRrDrXxZ68zD%2FIPzh4zmhRi0MspZ0VqbnXJp%2FfFKjTsedZ9hWF4jWiL3MltD4p\
        Pdre0NtZ2h4n&X-Amz-Signature=f9154863187c77e0c5ef263b603c8303d9b02e8556\
        449ca6e47d2063d2f06484&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-08T19:27:25.550Z"
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
UPDATE_TIME: "2025-02-08T18:28:44.657Z"
EXPIRY_TIME: "2025-02-08T19:28:36.531Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664N2LWQXF%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T182837Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJHMEUCIQDNbalAM0B87CMKOmo4OgueL5CXCdPCsimqY7q8HPEswAIgFPMNSjeBr54cEbRhus1nEWKByAYxyc%2FdZ1sg9q%2FiA0oqiAQIk%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDE45%2FYwjTXF9LbprVCrcA%2FxXomqtxLaN0OSIkU2yXE9PruWTT2%2FGTaNDTQaFlNWJ9UsEV9%2FFQLmIiYePVPxsnW9Om1%2FXWKxyjDLNakfgNSdM6V2xWT5lE9%2F6sHXsA6D2AkMMzFtKg8oCDHKsFzOGaUwdMZFGgNkXrFTNNYMabyeYRfOpTYhnNE%2F58yJ7DPYQraHQU9Oyf%2BahN7Xj7J8OVn1H3QnGdUbw2qm7u79jG10lu09od77OTTKLzyiOwBfAizLUvdM9zUC%2BbTx4LNJr7thQK%2BweeV16EsKy%2B1YHf3jLnHGSIA9fCbox2Tai4aTPaQpHHjGrwWW7LEEpKQJ34WoCcCqwcT19Tg%2FashPHHe6VZ5e%2BTEesN%2Fqd7xF3dK7lSsbkzz6Tc%2BNO65KWUuGae84ld7tH44pnpcLJLMDlaMpcqLT3xolR3jUAND1R%2Fycz3erZbAw42%2FD3DW2V%2FHnSTec6J8VQ15MVo74TdMBPCv6CI51h2huiiFBxBbLg1zkrw%2BRN2Y3w91V1vuqJsNF%2FWub36lRs2BPEmxS1a7AmSKWrooBCrQTH%2BfQfQT8TzndW%2BzMiEIu3ZRc0tvFcEzhx1RCttWoMYXXvOzEhdV%2FigSxQy2vNlKJ8xcGmHjr4w8pVY%2FJ7RCzgPNa4n3zHML7Bnr0GOqUBOrGnnMwMotuHbgcgs6xJGr%2BQbU7c%2B7bfUFEfqTj5n0qzg9hq4fSi9tgKC9UfoveIhIO3Bf6mU3ppsZq8ejmu%2FVcPv4JI83g37KNhpRGEH2Q4xs9saciCgLGqjJ%2FAOdp4LEDksZcywZlbRpVhPcCaTqOyXS3VIr6jl8bYkpEMwkT7hBJbdkYBNGP6NGVvH8owwPSLGs6rPd1pT3nVtn%2BhmOyBsoYs&X-Amz-Signature=c6720ae5fc947ba6d6d5c6e8d064533415e5854346fa1fdd1973cd6e3b395880&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664N2LWQXF%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T182837Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJHMEUCIQDNbalAM0B87CMKOmo4OgueL5CXCdPCsimqY7q8HPEswAIgFPMNSjeBr54cEbRhus1nEWKByAYxyc%2FdZ1sg9q%2FiA0oqiAQIk%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDE45%2FYwjTXF9LbprVCrcA%2FxXomqtxLaN0OSIkU2yXE9PruWTT2%2FGTaNDTQaFlNWJ9UsEV9%2FFQLmIiYePVPxsnW9Om1%2FXWKxyjDLNakfgNSdM6V2xWT5lE9%2F6sHXsA6D2AkMMzFtKg8oCDHKsFzOGaUwdMZFGgNkXrFTNNYMabyeYRfOpTYhnNE%2F58yJ7DPYQraHQU9Oyf%2BahN7Xj7J8OVn1H3QnGdUbw2qm7u79jG10lu09od77OTTKLzyiOwBfAizLUvdM9zUC%2BbTx4LNJr7thQK%2BweeV16EsKy%2B1YHf3jLnHGSIA9fCbox2Tai4aTPaQpHHjGrwWW7LEEpKQJ34WoCcCqwcT19Tg%2FashPHHe6VZ5e%2BTEesN%2Fqd7xF3dK7lSsbkzz6Tc%2BNO65KWUuGae84ld7tH44pnpcLJLMDlaMpcqLT3xolR3jUAND1R%2Fycz3erZbAw42%2FD3DW2V%2FHnSTec6J8VQ15MVo74TdMBPCv6CI51h2huiiFBxBbLg1zkrw%2BRN2Y3w91V1vuqJsNF%2FWub36lRs2BPEmxS1a7AmSKWrooBCrQTH%2BfQfQT8TzndW%2BzMiEIu3ZRc0tvFcEzhx1RCttWoMYXXvOzEhdV%2FigSxQy2vNlKJ8xcGmHjr4w8pVY%2FJ7RCzgPNa4n3zHML7Bnr0GOqUBOrGnnMwMotuHbgcgs6xJGr%2BQbU7c%2B7bfUFEfqTj5n0qzg9hq4fSi9tgKC9UfoveIhIO3Bf6mU3ppsZq8ejmu%2FVcPv4JI83g37KNhpRGEH2Q4xs9saciCgLGqjJ%2FAOdp4LEDksZcywZlbRpVhPcCaTqOyXS3VIr6jl8bYkpEMwkT7hBJbdkYBNGP6NGVvH8owwPSLGs6rPd1pT3nVtn%2BhmOyBsoYs&X-Amz-Signature=fe2e4189411081adcdfc329b3c8c83363ae29cad3af8d8065b9499a5dcf78fb9&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664N2LWQXF%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T182837Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJHMEUCIQDNbalAM0B87CMKOmo4OgueL5CXCdPCsimqY7q8HPEswAIgFPMNSjeBr54cEbRhus1nEWKByAYxyc%2FdZ1sg9q%2FiA0oqiAQIk%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDE45%2FYwjTXF9LbprVCrcA%2FxXomqtxLaN0OSIkU2yXE9PruWTT2%2FGTaNDTQaFlNWJ9UsEV9%2FFQLmIiYePVPxsnW9Om1%2FXWKxyjDLNakfgNSdM6V2xWT5lE9%2F6sHXsA6D2AkMMzFtKg8oCDHKsFzOGaUwdMZFGgNkXrFTNNYMabyeYRfOpTYhnNE%2F58yJ7DPYQraHQU9Oyf%2BahN7Xj7J8OVn1H3QnGdUbw2qm7u79jG10lu09od77OTTKLzyiOwBfAizLUvdM9zUC%2BbTx4LNJr7thQK%2BweeV16EsKy%2B1YHf3jLnHGSIA9fCbox2Tai4aTPaQpHHjGrwWW7LEEpKQJ34WoCcCqwcT19Tg%2FashPHHe6VZ5e%2BTEesN%2Fqd7xF3dK7lSsbkzz6Tc%2BNO65KWUuGae84ld7tH44pnpcLJLMDlaMpcqLT3xolR3jUAND1R%2Fycz3erZbAw42%2FD3DW2V%2FHnSTec6J8VQ15MVo74TdMBPCv6CI51h2huiiFBxBbLg1zkrw%2BRN2Y3w91V1vuqJsNF%2FWub36lRs2BPEmxS1a7AmSKWrooBCrQTH%2BfQfQT8TzndW%2BzMiEIu3ZRc0tvFcEzhx1RCttWoMYXXvOzEhdV%2FigSxQy2vNlKJ8xcGmHjr4w8pVY%2FJ7RCzgPNa4n3zHML7Bnr0GOqUBOrGnnMwMotuHbgcgs6xJGr%2BQbU7c%2B7bfUFEfqTj5n0qzg9hq4fSi9tgKC9UfoveIhIO3Bf6mU3ppsZq8ejmu%2FVcPv4JI83g37KNhpRGEH2Q4xs9saciCgLGqjJ%2FAOdp4LEDksZcywZlbRpVhPcCaTqOyXS3VIr6jl8bYkpEMwkT7hBJbdkYBNGP6NGVvH8owwPSLGs6rPd1pT3nVtn%2BhmOyBsoYs&X-Amz-Signature=3d4aa44ee174ab602a04d736e3ca1d7f4bbb4e81872c0b119fc1d95874092c1b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664N2LWQXF%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T182837Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJHMEUCIQDNbalAM0B87CMKOmo4OgueL5CXCdPCsimqY7q8HPEswAIgFPMNSjeBr54cEbRhus1nEWKByAYxyc%2FdZ1sg9q%2FiA0oqiAQIk%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDE45%2FYwjTXF9LbprVCrcA%2FxXomqtxLaN0OSIkU2yXE9PruWTT2%2FGTaNDTQaFlNWJ9UsEV9%2FFQLmIiYePVPxsnW9Om1%2FXWKxyjDLNakfgNSdM6V2xWT5lE9%2F6sHXsA6D2AkMMzFtKg8oCDHKsFzOGaUwdMZFGgNkXrFTNNYMabyeYRfOpTYhnNE%2F58yJ7DPYQraHQU9Oyf%2BahN7Xj7J8OVn1H3QnGdUbw2qm7u79jG10lu09od77OTTKLzyiOwBfAizLUvdM9zUC%2BbTx4LNJr7thQK%2BweeV16EsKy%2B1YHf3jLnHGSIA9fCbox2Tai4aTPaQpHHjGrwWW7LEEpKQJ34WoCcCqwcT19Tg%2FashPHHe6VZ5e%2BTEesN%2Fqd7xF3dK7lSsbkzz6Tc%2BNO65KWUuGae84ld7tH44pnpcLJLMDlaMpcqLT3xolR3jUAND1R%2Fycz3erZbAw42%2FD3DW2V%2FHnSTec6J8VQ15MVo74TdMBPCv6CI51h2huiiFBxBbLg1zkrw%2BRN2Y3w91V1vuqJsNF%2FWub36lRs2BPEmxS1a7AmSKWrooBCrQTH%2BfQfQT8TzndW%2BzMiEIu3ZRc0tvFcEzhx1RCttWoMYXXvOzEhdV%2FigSxQy2vNlKJ8xcGmHjr4w8pVY%2FJ7RCzgPNa4n3zHML7Bnr0GOqUBOrGnnMwMotuHbgcgs6xJGr%2BQbU7c%2B7bfUFEfqTj5n0qzg9hq4fSi9tgKC9UfoveIhIO3Bf6mU3ppsZq8ejmu%2FVcPv4JI83g37KNhpRGEH2Q4xs9saciCgLGqjJ%2FAOdp4LEDksZcywZlbRpVhPcCaTqOyXS3VIr6jl8bYkpEMwkT7hBJbdkYBNGP6NGVvH8owwPSLGs6rPd1pT3nVtn%2BhmOyBsoYs&X-Amz-Signature=89fe144b6070205faa2beb5a42a8e5cbf2295264dbbeaa6f8cf10963b98807f4&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664N2LWQXF%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T182837Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJHMEUCIQDNbalAM0B87CMKOmo4OgueL5CXCdPCsimqY7q8HPEswAIgFPMNSjeBr54cEbRhus1nEWKByAYxyc%2FdZ1sg9q%2FiA0oqiAQIk%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDE45%2FYwjTXF9LbprVCrcA%2FxXomqtxLaN0OSIkU2yXE9PruWTT2%2FGTaNDTQaFlNWJ9UsEV9%2FFQLmIiYePVPxsnW9Om1%2FXWKxyjDLNakfgNSdM6V2xWT5lE9%2F6sHXsA6D2AkMMzFtKg8oCDHKsFzOGaUwdMZFGgNkXrFTNNYMabyeYRfOpTYhnNE%2F58yJ7DPYQraHQU9Oyf%2BahN7Xj7J8OVn1H3QnGdUbw2qm7u79jG10lu09od77OTTKLzyiOwBfAizLUvdM9zUC%2BbTx4LNJr7thQK%2BweeV16EsKy%2B1YHf3jLnHGSIA9fCbox2Tai4aTPaQpHHjGrwWW7LEEpKQJ34WoCcCqwcT19Tg%2FashPHHe6VZ5e%2BTEesN%2Fqd7xF3dK7lSsbkzz6Tc%2BNO65KWUuGae84ld7tH44pnpcLJLMDlaMpcqLT3xolR3jUAND1R%2Fycz3erZbAw42%2FD3DW2V%2FHnSTec6J8VQ15MVo74TdMBPCv6CI51h2huiiFBxBbLg1zkrw%2BRN2Y3w91V1vuqJsNF%2FWub36lRs2BPEmxS1a7AmSKWrooBCrQTH%2BfQfQT8TzndW%2BzMiEIu3ZRc0tvFcEzhx1RCttWoMYXXvOzEhdV%2FigSxQy2vNlKJ8xcGmHjr4w8pVY%2FJ7RCzgPNa4n3zHML7Bnr0GOqUBOrGnnMwMotuHbgcgs6xJGr%2BQbU7c%2B7bfUFEfqTj5n0qzg9hq4fSi9tgKC9UfoveIhIO3Bf6mU3ppsZq8ejmu%2FVcPv4JI83g37KNhpRGEH2Q4xs9saciCgLGqjJ%2FAOdp4LEDksZcywZlbRpVhPcCaTqOyXS3VIr6jl8bYkpEMwkT7hBJbdkYBNGP6NGVvH8owwPSLGs6rPd1pT3nVtn%2BhmOyBsoYs&X-Amz-Signature=d8736678b05c23ee863a9411b1426998c05229f98240e017b81545ea6e1422e2&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TFVQACB3%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T182839Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJIMEYCIQDF2cOtPLSrF0gzSpU6xdlzS%2BX90BVhGBwgsu4vB7yzMQIhAOoWwLVkv30fgajRAV8dp7LwypGlsfuveX2teGzIiHp3KogECJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igwmvupei31azRtL8p4q3APQFRLCeeMDEKcihWU21qtu9wC4EHbJLlOtUHWjRMvVBRMtWynttZju2bs9i20WQYPQkQtT2ye4w5lohUTvzMx3gRGjOKN%2FdY4cQp7RkxcCZZZaxKjMAr2s2vBGQmCfMtCmgTrnN7prCVienw%2BXedwgD%2BLkdBa4LZAE1TPjlCGeU%2FJGFjzpxRMjtmaDICPWRN0EQF1REkZP8Rn8QKVox%2B88FFAxPjEj%2BJm8nFzXXvpC4Kb0pf8UbrxRd2XytfapSW9VT9TXQkNZpjIOs%2BSqxNMLZmrbhR6GDX2CCoXHX%2BFVGWUNJI01mUv5iLGW3xUSauGcJ0DpEh5lVlAVYgkyfeq73pdGaI35IBC4eYysQ85lH3lUm2p2qhaYVchnyd9H9Q99MmBe4Lj2atcOf2DYiKJDJEfqla%2FcKlLbwnftOyNs1pcDYHVy8B1ymR1WfeJhhohaF3O91QRoJYSrkcvab2gJHjclg58gZBQMfOz7FwVVfBM20bZgJr%2FIUy8asAYPIJKaAJxeKdejKfmjimnYRMcfaq5egahfo9PCdsvBG5Pwe44qEy2dnovRtMnAnI%2FMtCjWnbaU2ZwH%2BE8vU3KfMQ1C3kQeIpJfPE03pBKfyguIk0eh6M699chyfDuaADDLwZ69BjqkAT5BZcA388pG0%2FAzslvY%2FbngRJ%2FTOIQ0inWaOWTTxAynApeL%2B0aUI%2BQDr2nauCaxIzupNxAoPxdAfrZu1WBPGeoVQQDG8WYx0mPGhsKOFPBJnJZuNtKHEJqBBEu%2Fv3AO79%2F%2FPcP8soQHk0DkxCOrR%2F%2FUwpXZLf0rB4drPxz0zhCY5HPwEl6O4IaW7qIodywjnTtrTdDh787qmKaOe56RCM6NyU3I&X-Amz-Signature=21d33ac3cfea1bc42a9ae09c5fd6dea4a7db3f2dc868531d03fce4d15e8f9931&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YLBQPUGL%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T182840Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJIMEYCIQCSGiUXQo1UJk0S%2BodvMq5akLUlIaUXMdlwlo%2FFV2i7VAIhAKMQDIWEefvvZp9jU54xt04mYd68LmWAKbJ1Sw1JJtvTKogECJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwVkaKVZTuftsZXpxwq3APP4e412%2F80dWeA8CyoiIkrR5MZifFaiPY5InwaRanRqss3kb%2BteGZPcKEnUQP8ix4ooL2dNRgDefsuezmIqmz5F%2FN5Zb6IZtCXd3hehEOsIDiw9G0yQgLfrQZ%2FZamnwJwuK%2B3sWzgPmQOyj6q5qx%2BJS2VPdhqGBfKoXUpeBa8rJ0D8Oc9CfkXDS6L%2FAhSvYxcc%2F26LUcw5Iuzzv1iBEsOH8GOamIO66yllzkN7BZ9jO4f%2FxYndGinsFp6Lkke%2Bd%2BNQf12C6jAqM7%2FMtcCltkV%2BoDTxX3%2BfCaC0400qBvSsKjzZ47Ewde5Dl5PqEVXRN6bcGWZ4J9AeaeWJhP%2BQxTkqP%2FCJFOuWQvTzrnaDOR9U%2BnreiBXyDXYaPjir6DZ8uoGp9WW6R1bVR6duZ6cRSMq4y4wdGTpypSkQAKe1p%2BzuPQ8C5mf%2BdxW6vw3Hx26ZU4pR6l%2FKwrpXUD6P8UUSv90MyAATeoCGt4fJZfOy0XEx6hg93dpm0ZqwgV4ZAR7z11nDey9vCWng165bhivAAJq70U%2BrMrAyno%2B%2FMnzpsIy7EMEcJQ2XrNA5RFkT9qzpUY10M9ZC7JsEORDPxX8x9tSeL3f%2BM1kL%2FdeJMf4p3XCQ6J0Rp5cj%2Fx3J227ZoTC6wZ69BjqkAcVVGLUdg4AmUIat97uo%2FXv1i%2BwZh%2Fh35dtXURUYBAqBjQ7amfOkENvG8y3y4rY8lrKhCicqc1NuRCqhwBGGWKvwMLW536xdNXKfltY6cZD9%2F03mM6qTvfZ0azxjk0f%2B6CuC695p2CkKDaQKRu3X%2BD%2BFndkAWGR6z7BAg8RU049TXVddRVoOx6pmruQsy4U4vG0G4OXXsYAu8pPqcbioeOgnpYwc&X-Amz-Signature=8c25f12c9b2c95dfd7b7bb3d952133a2493c11b023e32322ec4dfbb6bffea9ff&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664N2LWQXF%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T182837Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJHMEUCIQDNbalAM0B87CMKOmo4OgueL5CXCdPCsimqY7q8HPEswAIgFPMNSjeBr54cEbRhus1nEWKByAYxyc%2FdZ1sg9q%2FiA0oqiAQIk%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDE45%2FYwjTXF9LbprVCrcA%2FxXomqtxLaN0OSIkU2yXE9PruWTT2%2FGTaNDTQaFlNWJ9UsEV9%2FFQLmIiYePVPxsnW9Om1%2FXWKxyjDLNakfgNSdM6V2xWT5lE9%2F6sHXsA6D2AkMMzFtKg8oCDHKsFzOGaUwdMZFGgNkXrFTNNYMabyeYRfOpTYhnNE%2F58yJ7DPYQraHQU9Oyf%2BahN7Xj7J8OVn1H3QnGdUbw2qm7u79jG10lu09od77OTTKLzyiOwBfAizLUvdM9zUC%2BbTx4LNJr7thQK%2BweeV16EsKy%2B1YHf3jLnHGSIA9fCbox2Tai4aTPaQpHHjGrwWW7LEEpKQJ34WoCcCqwcT19Tg%2FashPHHe6VZ5e%2BTEesN%2Fqd7xF3dK7lSsbkzz6Tc%2BNO65KWUuGae84ld7tH44pnpcLJLMDlaMpcqLT3xolR3jUAND1R%2Fycz3erZbAw42%2FD3DW2V%2FHnSTec6J8VQ15MVo74TdMBPCv6CI51h2huiiFBxBbLg1zkrw%2BRN2Y3w91V1vuqJsNF%2FWub36lRs2BPEmxS1a7AmSKWrooBCrQTH%2BfQfQT8TzndW%2BzMiEIu3ZRc0tvFcEzhx1RCttWoMYXXvOzEhdV%2FigSxQy2vNlKJ8xcGmHjr4w8pVY%2FJ7RCzgPNa4n3zHML7Bnr0GOqUBOrGnnMwMotuHbgcgs6xJGr%2BQbU7c%2B7bfUFEfqTj5n0qzg9hq4fSi9tgKC9UfoveIhIO3Bf6mU3ppsZq8ejmu%2FVcPv4JI83g37KNhpRGEH2Q4xs9saciCgLGqjJ%2FAOdp4LEDksZcywZlbRpVhPcCaTqOyXS3VIr6jl8bYkpEMwkT7hBJbdkYBNGP6NGVvH8owwPSLGs6rPd1pT3nVtn%2BhmOyBsoYs&X-Amz-Signature=571ce3cc975e6248a7cda869f525ccd65e179b50a747763e97cc85cdd4a2e24c&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664N2LWQXF%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T182837Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJHMEUCIQDNbalAM0B87CMKOmo4OgueL5CXCdPCsimqY7q8HPEswAIgFPMNSjeBr54cEbRhus1nEWKByAYxyc%2FdZ1sg9q%2FiA0oqiAQIk%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDE45%2FYwjTXF9LbprVCrcA%2FxXomqtxLaN0OSIkU2yXE9PruWTT2%2FGTaNDTQaFlNWJ9UsEV9%2FFQLmIiYePVPxsnW9Om1%2FXWKxyjDLNakfgNSdM6V2xWT5lE9%2F6sHXsA6D2AkMMzFtKg8oCDHKsFzOGaUwdMZFGgNkXrFTNNYMabyeYRfOpTYhnNE%2F58yJ7DPYQraHQU9Oyf%2BahN7Xj7J8OVn1H3QnGdUbw2qm7u79jG10lu09od77OTTKLzyiOwBfAizLUvdM9zUC%2BbTx4LNJr7thQK%2BweeV16EsKy%2B1YHf3jLnHGSIA9fCbox2Tai4aTPaQpHHjGrwWW7LEEpKQJ34WoCcCqwcT19Tg%2FashPHHe6VZ5e%2BTEesN%2Fqd7xF3dK7lSsbkzz6Tc%2BNO65KWUuGae84ld7tH44pnpcLJLMDlaMpcqLT3xolR3jUAND1R%2Fycz3erZbAw42%2FD3DW2V%2FHnSTec6J8VQ15MVo74TdMBPCv6CI51h2huiiFBxBbLg1zkrw%2BRN2Y3w91V1vuqJsNF%2FWub36lRs2BPEmxS1a7AmSKWrooBCrQTH%2BfQfQT8TzndW%2BzMiEIu3ZRc0tvFcEzhx1RCttWoMYXXvOzEhdV%2FigSxQy2vNlKJ8xcGmHjr4w8pVY%2FJ7RCzgPNa4n3zHML7Bnr0GOqUBOrGnnMwMotuHbgcgs6xJGr%2BQbU7c%2B7bfUFEfqTj5n0qzg9hq4fSi9tgKC9UfoveIhIO3Bf6mU3ppsZq8ejmu%2FVcPv4JI83g37KNhpRGEH2Q4xs9saciCgLGqjJ%2FAOdp4LEDksZcywZlbRpVhPcCaTqOyXS3VIr6jl8bYkpEMwkT7hBJbdkYBNGP6NGVvH8owwPSLGs6rPd1pT3nVtn%2BhmOyBsoYs&X-Amz-Signature=4fa1c795406b5323333c9307d8ea41b713d31f35f8726d064121f3d3ea0072db&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664N2LWQXF%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T182837Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJHMEUCIQDNbalAM0B87CMKOmo4OgueL5CXCdPCsimqY7q8HPEswAIgFPMNSjeBr54cEbRhus1nEWKByAYxyc%2FdZ1sg9q%2FiA0oqiAQIk%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDE45%2FYwjTXF9LbprVCrcA%2FxXomqtxLaN0OSIkU2yXE9PruWTT2%2FGTaNDTQaFlNWJ9UsEV9%2FFQLmIiYePVPxsnW9Om1%2FXWKxyjDLNakfgNSdM6V2xWT5lE9%2F6sHXsA6D2AkMMzFtKg8oCDHKsFzOGaUwdMZFGgNkXrFTNNYMabyeYRfOpTYhnNE%2F58yJ7DPYQraHQU9Oyf%2BahN7Xj7J8OVn1H3QnGdUbw2qm7u79jG10lu09od77OTTKLzyiOwBfAizLUvdM9zUC%2BbTx4LNJr7thQK%2BweeV16EsKy%2B1YHf3jLnHGSIA9fCbox2Tai4aTPaQpHHjGrwWW7LEEpKQJ34WoCcCqwcT19Tg%2FashPHHe6VZ5e%2BTEesN%2Fqd7xF3dK7lSsbkzz6Tc%2BNO65KWUuGae84ld7tH44pnpcLJLMDlaMpcqLT3xolR3jUAND1R%2Fycz3erZbAw42%2FD3DW2V%2FHnSTec6J8VQ15MVo74TdMBPCv6CI51h2huiiFBxBbLg1zkrw%2BRN2Y3w91V1vuqJsNF%2FWub36lRs2BPEmxS1a7AmSKWrooBCrQTH%2BfQfQT8TzndW%2BzMiEIu3ZRc0tvFcEzhx1RCttWoMYXXvOzEhdV%2FigSxQy2vNlKJ8xcGmHjr4w8pVY%2FJ7RCzgPNa4n3zHML7Bnr0GOqUBOrGnnMwMotuHbgcgs6xJGr%2BQbU7c%2B7bfUFEfqTj5n0qzg9hq4fSi9tgKC9UfoveIhIO3Bf6mU3ppsZq8ejmu%2FVcPv4JI83g37KNhpRGEH2Q4xs9saciCgLGqjJ%2FAOdp4LEDksZcywZlbRpVhPcCaTqOyXS3VIr6jl8bYkpEMwkT7hBJbdkYBNGP6NGVvH8owwPSLGs6rPd1pT3nVtn%2BhmOyBsoYs&X-Amz-Signature=011a056447f1599afde9d5229335abe5755bf544db0ce584a4190ed05d064cf1&X-Amz-SignedHeaders=host&x-id=GetObject)


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

