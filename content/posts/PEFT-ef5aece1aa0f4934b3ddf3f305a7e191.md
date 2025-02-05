---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB46636RTG3JY%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250205T020454Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjECAaCXVzLXdlc3QtMiJIMEYCIQCszuG0kIfVHXKAtjVoV3O7dBmmzypOSvK4A71q8%2FRMywIhA\
  KHHVpAgnEYvrhHR7DNYjMnB9rAyBMB2jjSvJ%2BYyW4M8Kv8DCDkQABoMNjM3NDIzMTgzODA1Igx7\
  SyjYIS5G6Czgf40q3ANxiCimgYhM%2Bc80Nj7g42zMiycB4Cxtptr9RSWwI8d0G3BRbbN3FAbvrEo\
  5mPbopVXYbMjDH0mmDoxIJAVbB0oZ3lNOF2WCaCst%2BeT1H5594w0FLv8pLhtHMfP54yYsTWQhq0\
  pe5LoGDyQQmvQau6cPvUqqHMkYhDLIxMRZ1zagL50JGsOBCKIWeOxqT7tSwTrgzoSDlmoshoQn5on\
  RRtS8dOKiTe9J5Y9LrrIl4ZvcJMNg9R923YcqLSOgt8PX88Ox3IaJ5d9%2FTHa2QGxNSXu4%2FZod\
  DAgw0cSL4CYu0BBZU13j2Mvwe0Ga5TtT89OO5wJq2e7a9O1dvqZ%2BcNn%2Fuzo5y6rNzsEGi%2Fk\
  9B%2Fl%2BVn1vePeDsbTrt%2FNRmjOrztlAzCvBFIveChYKMGCO6NwPauuIC5FqSvs1PYGc41kjsF\
  AXzbEfedaocBNunQN5Zy1CE%2BOaQM9IjwUNyQ555oOH%2FjNhOHFVLUD3xqvZBz6CixbIvNLIMDe\
  dIcVywU4Dnp7e1DHeT3XApC8xwrbjda9qc0NVLaMXcSLsWwhJFDXgYft7WV43Bqc5T%2BZwO1W626\
  FpbyvUsDg1pGSFZ2abqDQgI3BDX%2BzA8nzwAq5iXqVC7KrPghlN9jZd%2Fjd6MwInYTC3z4q9Bjq\
  kAdqz69qAUAs9wMkC43vu3Le1mqk10PUfLG3RAZ2tzB4jM3md8%2BLfzEvYIB7z1rCD1kulpHnR0r\
  fZUC8Awdz%2BNntvIBZa8LH%2BOSnxAY6XqzUl0x8ww83fAr%2BUA0Uk26tzBkD7OT%2B4kxiLa%2\
  B2SttPr5VVJf89q7zIhC6Xm0ZWtbZIROlkOTM%2Ba1b7%2FgpKNBz%2FTJn8TEUjv7izkLp8uyfi8\
  1znbOjVA&X-Amz-Signature=24358a4e739895ec12d6da8f0da8e6324546fb37e6e21c5a1f54\
  babef5921b94&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4667KTTDHEZ%2F20250205%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250205T020327Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJGMEQCIFe6O4pdGyVzfIKhMp2o6o3%2FAzBaF\
        zj9N9PuV7EW%2F5LXAiA%2Be53v9HdnzBQjUUCazdQaw2pswVTVCb4O7%2B8%2BSS2EgCr%\
        2FAwg5EAAaDDYzNzQyMzE4MzgwNSIMwcZaVbm6fHENhaDHKtwD63NY%2FvRjW1H3pgbvNCZ\
        qSLiHBA0pG1CjPHSAOvKZz%2BsRjwQzCN%2BiOxLx%2F%2B8Mus%2Bc3RvSrb%2BLy5EaP%\
        2B67cnewQ7ID%2F1fqK01p4CPpap2tBxjXJPRtzyMmkzQItEaDrd7gv4yzye8okr9zxvzZ5\
        LdoUkqt81i3ff46sXntu8B3b6nvtyL507XANSnDaTIc8jxqa27SlUOpiR5QvQWnfAwF1ZDf\
        h5XdQX4rR%2BV3nyO5YHpv3Hgo9%2FEaXIS10pSDzXslWR%2Fdwr2iVXnFErQdXILVIT79I\
        u6gtm2f%2BKd8GcT3StCvk2ZIMAnwgPwWW0CS1Eb0rBnzfgaP0UJLrNJE0hAE7P3VfSva8b\
        q7ProSmAhBpBVjEpNNeEpwfYmmmM4%2Ba0wrMMIB19PJ2w0wHcG9GEHzArUatCniqJJcZwc\
        LGUykQIINyz2y16t0rjSjQQxRLYh961DJgqy0wFMJkydFvd1v9kWU8tQSq%2FQulmg3UmZ0\
        Bd2zQ%2BP9tBUrCfQbn%2FJIGPbtjcJXa19vArXQDQGSuq1vbxlplSmN1yFm5u95G31QKFQ\
        MHyNBTU8NemHqj3Z0Op1gYIaQE52YHc5hkfeaMexymPnNtWi9Ecdu9eH0SvIiGin%2FiPUa\
        Y2x1HhkXIE4wwc%2BKvQY6pgGVfEUj4QtCcEMV9z11lBkHVxxOwSMzq1G0kgDKlSx4U77ca\
        hJQRHDocXUnIPDRkh5tquKKEApw6ZTc6gVIYDbqKakJxj7Iw8xZdMydG5QfrRFToRcLDh8H\
        duz5fCrqUkZpsTofpt9kqj1eKjERD4YyqELHFV6NbUfHza3LT8CTvHwxbXYdw5FEvmG%2Bd\
        419gcLS%2FBWvRVhDBn%2Bchs61HX6eod8AhBs2&X-Amz-Signature=660f51bfaab0629\
        f095214e84cf1bc5bf71a0128905a324a6fccaf042b1d472a&X-Amz-SignedHeaders=h\
        ost&x-id=GetObject"
      expiry_time: "2025-02-05T03:03:27.295Z"
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
UPDATE_TIME: "2025-02-05T02:04:58.945Z"
EXPIRY_TIME: "2025-02-05T03:04:51.227Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QG5VVRJP%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T020451Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJIMEYCIQC%2BSqrbFuJOrvpzGGHUNWe31s9dw%2B2GWJDgax%2Bu2ALW0QIhAJKJ58hhmYfe9PA15wXcQt9V5EtzhaWhIlraKgT8y3UcKv8DCDkQABoMNjM3NDIzMTgzODA1IgxWwWv4wjHUrZk43Joq3AO0h%2BZ1d150v%2BlCRbZm6K%2FmwKut2myEqHc6Ca1qVVa%2BxY7gM1d8Z1czXHveTvnoXucccwt1irpc4qcVtI768LoEowhnv8CWC0UcIOiVqksThVkhHuKkD86isNzxoS1NZ%2Bc7eQFNaBxiKD9YO7oN0jULPwgtwBPd2wYbUWzA51uzcC0lKNKdVQE%2B4v0d75OfJz2S57l%2BOksfM%2BXEKy%2Bz3ZS9uMJw9XNqqGENpQ9rKtbggd83yQdNC2YyuNbWIb6viUSs6Zt0lepfhl8PPc%2BDXh3%2FmjXt4oTokSb3Qr7KbVTIS9sIN2KJnjj9fBjheWwl3bYLK3KWmWZAdc7666LGlz2z%2BDj9PavH9qlr8l5aq57z3CcRvbZK113mdqBbZfteUMSnWSIDyAFJYkMqKDhVGUAxgxLMbW4%2BbbHFwhHj3ZPjMkDTzw91M06FJmvh0rISuw1TaVSGXf%2BiBTXmM07uJEz6KvAnHl%2FsWQQ34ZTcvy4kyogmrppyUSeM%2FK137e7M46wv%2BXz5xUUfV0Pe99zQrIhqiEVhxoHvy5eBP5sTqZ2TK9mw%2FUdJ93CbiwEimLllcPiY%2BqM8RR0cGy5Ib%2Bhu77%2FQ3ilfwnn0Z%2BHmaSU5zmJj3s5AqDkMjTqWadU6BTCfz4q9BjqkAUtlVC4JKZuZjoIfFuWveTNNph9Jy8q20y5V7BAL0piMNJ%2B0yBW0nCXECXCkSgl%2FvalMI6zcrmKI7xxOXl3%2B7XXcfqubSF5MDQyh0n9pnDsxDOQfkjTib2UXBr5cvbPFArsudtjQfRqvLK5So2MkeGG%2FHQH%2FNyv52A0naZEa2tDhoR2WWQCQIGTCGjUsbtkhK0F7qKLObc5hiBapdTsTGosol0JF&X-Amz-Signature=e4286c9150f2848d5203e10cb5da600aa9d02f46d30a35593067b09657ce71d2&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QG5VVRJP%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T020451Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJIMEYCIQC%2BSqrbFuJOrvpzGGHUNWe31s9dw%2B2GWJDgax%2Bu2ALW0QIhAJKJ58hhmYfe9PA15wXcQt9V5EtzhaWhIlraKgT8y3UcKv8DCDkQABoMNjM3NDIzMTgzODA1IgxWwWv4wjHUrZk43Joq3AO0h%2BZ1d150v%2BlCRbZm6K%2FmwKut2myEqHc6Ca1qVVa%2BxY7gM1d8Z1czXHveTvnoXucccwt1irpc4qcVtI768LoEowhnv8CWC0UcIOiVqksThVkhHuKkD86isNzxoS1NZ%2Bc7eQFNaBxiKD9YO7oN0jULPwgtwBPd2wYbUWzA51uzcC0lKNKdVQE%2B4v0d75OfJz2S57l%2BOksfM%2BXEKy%2Bz3ZS9uMJw9XNqqGENpQ9rKtbggd83yQdNC2YyuNbWIb6viUSs6Zt0lepfhl8PPc%2BDXh3%2FmjXt4oTokSb3Qr7KbVTIS9sIN2KJnjj9fBjheWwl3bYLK3KWmWZAdc7666LGlz2z%2BDj9PavH9qlr8l5aq57z3CcRvbZK113mdqBbZfteUMSnWSIDyAFJYkMqKDhVGUAxgxLMbW4%2BbbHFwhHj3ZPjMkDTzw91M06FJmvh0rISuw1TaVSGXf%2BiBTXmM07uJEz6KvAnHl%2FsWQQ34ZTcvy4kyogmrppyUSeM%2FK137e7M46wv%2BXz5xUUfV0Pe99zQrIhqiEVhxoHvy5eBP5sTqZ2TK9mw%2FUdJ93CbiwEimLllcPiY%2BqM8RR0cGy5Ib%2Bhu77%2FQ3ilfwnn0Z%2BHmaSU5zmJj3s5AqDkMjTqWadU6BTCfz4q9BjqkAUtlVC4JKZuZjoIfFuWveTNNph9Jy8q20y5V7BAL0piMNJ%2B0yBW0nCXECXCkSgl%2FvalMI6zcrmKI7xxOXl3%2B7XXcfqubSF5MDQyh0n9pnDsxDOQfkjTib2UXBr5cvbPFArsudtjQfRqvLK5So2MkeGG%2FHQH%2FNyv52A0naZEa2tDhoR2WWQCQIGTCGjUsbtkhK0F7qKLObc5hiBapdTsTGosol0JF&X-Amz-Signature=fb316f00843210387218065a15f70d8a53b1d11ce89fc7da2d4d919fd72ce544&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QG5VVRJP%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T020451Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJIMEYCIQC%2BSqrbFuJOrvpzGGHUNWe31s9dw%2B2GWJDgax%2Bu2ALW0QIhAJKJ58hhmYfe9PA15wXcQt9V5EtzhaWhIlraKgT8y3UcKv8DCDkQABoMNjM3NDIzMTgzODA1IgxWwWv4wjHUrZk43Joq3AO0h%2BZ1d150v%2BlCRbZm6K%2FmwKut2myEqHc6Ca1qVVa%2BxY7gM1d8Z1czXHveTvnoXucccwt1irpc4qcVtI768LoEowhnv8CWC0UcIOiVqksThVkhHuKkD86isNzxoS1NZ%2Bc7eQFNaBxiKD9YO7oN0jULPwgtwBPd2wYbUWzA51uzcC0lKNKdVQE%2B4v0d75OfJz2S57l%2BOksfM%2BXEKy%2Bz3ZS9uMJw9XNqqGENpQ9rKtbggd83yQdNC2YyuNbWIb6viUSs6Zt0lepfhl8PPc%2BDXh3%2FmjXt4oTokSb3Qr7KbVTIS9sIN2KJnjj9fBjheWwl3bYLK3KWmWZAdc7666LGlz2z%2BDj9PavH9qlr8l5aq57z3CcRvbZK113mdqBbZfteUMSnWSIDyAFJYkMqKDhVGUAxgxLMbW4%2BbbHFwhHj3ZPjMkDTzw91M06FJmvh0rISuw1TaVSGXf%2BiBTXmM07uJEz6KvAnHl%2FsWQQ34ZTcvy4kyogmrppyUSeM%2FK137e7M46wv%2BXz5xUUfV0Pe99zQrIhqiEVhxoHvy5eBP5sTqZ2TK9mw%2FUdJ93CbiwEimLllcPiY%2BqM8RR0cGy5Ib%2Bhu77%2FQ3ilfwnn0Z%2BHmaSU5zmJj3s5AqDkMjTqWadU6BTCfz4q9BjqkAUtlVC4JKZuZjoIfFuWveTNNph9Jy8q20y5V7BAL0piMNJ%2B0yBW0nCXECXCkSgl%2FvalMI6zcrmKI7xxOXl3%2B7XXcfqubSF5MDQyh0n9pnDsxDOQfkjTib2UXBr5cvbPFArsudtjQfRqvLK5So2MkeGG%2FHQH%2FNyv52A0naZEa2tDhoR2WWQCQIGTCGjUsbtkhK0F7qKLObc5hiBapdTsTGosol0JF&X-Amz-Signature=56d47dbdfc2756d69d9a547b2f32c8200c9d93b9a132770a483e310d3790cb51&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QG5VVRJP%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T020451Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJIMEYCIQC%2BSqrbFuJOrvpzGGHUNWe31s9dw%2B2GWJDgax%2Bu2ALW0QIhAJKJ58hhmYfe9PA15wXcQt9V5EtzhaWhIlraKgT8y3UcKv8DCDkQABoMNjM3NDIzMTgzODA1IgxWwWv4wjHUrZk43Joq3AO0h%2BZ1d150v%2BlCRbZm6K%2FmwKut2myEqHc6Ca1qVVa%2BxY7gM1d8Z1czXHveTvnoXucccwt1irpc4qcVtI768LoEowhnv8CWC0UcIOiVqksThVkhHuKkD86isNzxoS1NZ%2Bc7eQFNaBxiKD9YO7oN0jULPwgtwBPd2wYbUWzA51uzcC0lKNKdVQE%2B4v0d75OfJz2S57l%2BOksfM%2BXEKy%2Bz3ZS9uMJw9XNqqGENpQ9rKtbggd83yQdNC2YyuNbWIb6viUSs6Zt0lepfhl8PPc%2BDXh3%2FmjXt4oTokSb3Qr7KbVTIS9sIN2KJnjj9fBjheWwl3bYLK3KWmWZAdc7666LGlz2z%2BDj9PavH9qlr8l5aq57z3CcRvbZK113mdqBbZfteUMSnWSIDyAFJYkMqKDhVGUAxgxLMbW4%2BbbHFwhHj3ZPjMkDTzw91M06FJmvh0rISuw1TaVSGXf%2BiBTXmM07uJEz6KvAnHl%2FsWQQ34ZTcvy4kyogmrppyUSeM%2FK137e7M46wv%2BXz5xUUfV0Pe99zQrIhqiEVhxoHvy5eBP5sTqZ2TK9mw%2FUdJ93CbiwEimLllcPiY%2BqM8RR0cGy5Ib%2Bhu77%2FQ3ilfwnn0Z%2BHmaSU5zmJj3s5AqDkMjTqWadU6BTCfz4q9BjqkAUtlVC4JKZuZjoIfFuWveTNNph9Jy8q20y5V7BAL0piMNJ%2B0yBW0nCXECXCkSgl%2FvalMI6zcrmKI7xxOXl3%2B7XXcfqubSF5MDQyh0n9pnDsxDOQfkjTib2UXBr5cvbPFArsudtjQfRqvLK5So2MkeGG%2FHQH%2FNyv52A0naZEa2tDhoR2WWQCQIGTCGjUsbtkhK0F7qKLObc5hiBapdTsTGosol0JF&X-Amz-Signature=dc9a40d9e614a7f670c8f947dd66421ccae7fe9ec4eee51c41ab778dd728a157&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QG5VVRJP%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T020451Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJIMEYCIQC%2BSqrbFuJOrvpzGGHUNWe31s9dw%2B2GWJDgax%2Bu2ALW0QIhAJKJ58hhmYfe9PA15wXcQt9V5EtzhaWhIlraKgT8y3UcKv8DCDkQABoMNjM3NDIzMTgzODA1IgxWwWv4wjHUrZk43Joq3AO0h%2BZ1d150v%2BlCRbZm6K%2FmwKut2myEqHc6Ca1qVVa%2BxY7gM1d8Z1czXHveTvnoXucccwt1irpc4qcVtI768LoEowhnv8CWC0UcIOiVqksThVkhHuKkD86isNzxoS1NZ%2Bc7eQFNaBxiKD9YO7oN0jULPwgtwBPd2wYbUWzA51uzcC0lKNKdVQE%2B4v0d75OfJz2S57l%2BOksfM%2BXEKy%2Bz3ZS9uMJw9XNqqGENpQ9rKtbggd83yQdNC2YyuNbWIb6viUSs6Zt0lepfhl8PPc%2BDXh3%2FmjXt4oTokSb3Qr7KbVTIS9sIN2KJnjj9fBjheWwl3bYLK3KWmWZAdc7666LGlz2z%2BDj9PavH9qlr8l5aq57z3CcRvbZK113mdqBbZfteUMSnWSIDyAFJYkMqKDhVGUAxgxLMbW4%2BbbHFwhHj3ZPjMkDTzw91M06FJmvh0rISuw1TaVSGXf%2BiBTXmM07uJEz6KvAnHl%2FsWQQ34ZTcvy4kyogmrppyUSeM%2FK137e7M46wv%2BXz5xUUfV0Pe99zQrIhqiEVhxoHvy5eBP5sTqZ2TK9mw%2FUdJ93CbiwEimLllcPiY%2BqM8RR0cGy5Ib%2Bhu77%2FQ3ilfwnn0Z%2BHmaSU5zmJj3s5AqDkMjTqWadU6BTCfz4q9BjqkAUtlVC4JKZuZjoIfFuWveTNNph9Jy8q20y5V7BAL0piMNJ%2B0yBW0nCXECXCkSgl%2FvalMI6zcrmKI7xxOXl3%2B7XXcfqubSF5MDQyh0n9pnDsxDOQfkjTib2UXBr5cvbPFArsudtjQfRqvLK5So2MkeGG%2FHQH%2FNyv52A0naZEa2tDhoR2WWQCQIGTCGjUsbtkhK0F7qKLObc5hiBapdTsTGosol0JF&X-Amz-Signature=3662bd6890f9c8c3d6c67df0729316de868d67d92f2df8bb3ef18e38a6a7edca&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SEQKQIA4%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T020453Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJHMEUCIQCuFR3vYMJ7wEbJikcaApjbpMkf7y5uhW518tsPg%2FEMHAIgE6HQZC9PdjewbfU%2BwnqM2g0EjqBTeqWW1NpZI8RmPi8q%2FwMIORAAGgw2Mzc0MjMxODM4MDUiDCCttcv%2F07GZ3t7NzyrcAxNGNUyZfo0fKciRUVgSylhWSXYXoyaMEF97peH1xatgF9n7NwquKqRRly3RJ24MTBYR1u8yNWy4SsFqobUir%2FLVeFYrBY0nUpXlroucQ0t%2BmPuEJwaf9xe6QQl3Vr6CcyD4tlNjA6Uelkgwca36d2whFLfO7te95W0dY1ke4FHClRlH%2B4D4cJ0fE5wfyLPvHyfKITwNvpjjGgZeWIRiM0EVyx0W21sQCVxSocuIEtT4UnknjAg%2FEncqPIE%2B%2BiXM4Y0klWOuLhpZBf1clnhF4MkmnptSGIJmspnHIvRqVGQ37g4zLsTYOB%2F1gxSKYDdaLOv%2Ff%2FrbJG9elNUk0PBrVlSRcw6DWFUNyhuVJ7GqsW2DlgWirCA9vTPoNpUg%2FlJYtXyQW%2FLNKyosxCjpnntgvwqLpU4n5psJ4qOFgzT2fF0%2FfA4cNnVL9Jax08G%2B5%2F%2BS3d%2B9nOUlI9ePFMvHtlOYnxEmvjWGlhxicINd0qU7RNcCmYSB%2F0xn0imkg8qFM8VUgXtnahd7Wu3XHtHtJ3paUSq%2FjT1uB4JkhALSsxDum8Ax6u9dsEVcwCae8N7SvPkiW%2B%2FEduFPrAz1jNpCyQaikWqk7tlWPhgAguKdnK15tqBAUDtEtpsm8QSyeebgMKzPir0GOqUBovbplsCc2yt1WYncQxIyGcTr7%2Bc3OxR1h2ehekr%2FfcM2fy0QifY9hk29wO%2BIpmX2lcJKcpL75Un4zBcAyJRWDu6rMrQOGjJSSEErN4FFw17bHiXQbAjKHzr8St97sS7MoD4O35eYk0dQANLglIJXeHOGVDUkeY2KapD417Bs281zDCQMDb1DaEUpoL4sH7c9catLrKnoJ1srMorGz7TBD3y%2BRvZZ&X-Amz-Signature=72ed36f3aa061463eb348acee090c34d01df32623ddb8d61796c98ac51a7824a&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YNT3OJLQ%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T020454Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJGMEQCIFcZovPrjRTFMKHaAzW2arKu76VLahcBeTjwYO6%2BfGANAiATqjuW%2FaD8DLEGMfQcnmu%2BO%2FEPbWuesvzemt8p3%2BNS7Cr%2FAwg5EAAaDDYzNzQyMzE4MzgwNSIMNJ5eeeG5B1Qmd5oMKtwDy%2BXHo33pQ6hxYYwSv%2BbLmaEp9D13iO1ccCyEwHpsVRKfRZJji%2FQE9VH6iLolXs%2FBm%2FmkU9unq8%2FpXdGQGwm0r6wdWBWItbY9H1%2FwyXs6MvW9SKHazAzhXfErts3cAsJmOeNXePQeMjNYMx8IiMr%2FzLvGIiasqkXGMJF0uC02KDN7HBWS52ckouJyw0y07Czn0v95BbLrSBJOHryk1%2FA92YlR%2FJ%2FQR14rjtqDIjgwPC94f0Liph2tAQuQwiZjP9nkL6D8Sm6IEa%2B4jUidOx0fkUDhOMoEP0fWdoY1TJuCZsSFxqmR%2B%2FmSkBahNQZsdpmwTIkS%2BwJmoXTQQ6noxA%2BsyFaZBsmQGQvA%2BKelyjP%2FNzg3HgIYzzr9MebxHV8NeN4Iop%2BINH4z8LQ4MiK%2BlCI1ewv2sWMlAZR4W9wDa30JldZnTxRqqWHsrU1xvwD6Z4p31Ml3FDPJv5vnGRSPPDS1yXkyE8F9IsFNXsnYWwEXa6XnWZluJJSHf2%2BxKBUat27IlvZo1ZSmOX638J8YRe%2FreWhU7PQllCkD2VnL%2Bs%2FBVLoxVjfhPbH4hDk5aDvmnfGGJluRVEsdYW%2Fo%2FV59vGWCvN599FrnGzjWWi4MV4wcn9ITfgTbVIOxPZy8mH8w1s%2BKvQY6pgHqKOUmqoBTXc0C7sIx1xXynVNwT9ueZAnBKs6i5aZdJw6CFY9LMy58s8zg3Qlx1RupnCtGeBs%2Fv8mCf2PlpFZMHYu5rONZ7UH02tK68b%2B9SCgFUBQMT970Hed8UliepWNSO5ubGRBTtuliwYx1YMnBH%2B7MSXYRWrEF12CCFfQp6OUuNteHfFwhrRmg%2BCyS%2B1BycOT%2FTGWCMy8%2FA0VQBY8eZg60%2F0LR&X-Amz-Signature=8e26d8c1b01740713c86869396238dc5760fdfb2c772db4f1b02f831f15291cc&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QG5VVRJP%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T020452Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJIMEYCIQC%2BSqrbFuJOrvpzGGHUNWe31s9dw%2B2GWJDgax%2Bu2ALW0QIhAJKJ58hhmYfe9PA15wXcQt9V5EtzhaWhIlraKgT8y3UcKv8DCDkQABoMNjM3NDIzMTgzODA1IgxWwWv4wjHUrZk43Joq3AO0h%2BZ1d150v%2BlCRbZm6K%2FmwKut2myEqHc6Ca1qVVa%2BxY7gM1d8Z1czXHveTvnoXucccwt1irpc4qcVtI768LoEowhnv8CWC0UcIOiVqksThVkhHuKkD86isNzxoS1NZ%2Bc7eQFNaBxiKD9YO7oN0jULPwgtwBPd2wYbUWzA51uzcC0lKNKdVQE%2B4v0d75OfJz2S57l%2BOksfM%2BXEKy%2Bz3ZS9uMJw9XNqqGENpQ9rKtbggd83yQdNC2YyuNbWIb6viUSs6Zt0lepfhl8PPc%2BDXh3%2FmjXt4oTokSb3Qr7KbVTIS9sIN2KJnjj9fBjheWwl3bYLK3KWmWZAdc7666LGlz2z%2BDj9PavH9qlr8l5aq57z3CcRvbZK113mdqBbZfteUMSnWSIDyAFJYkMqKDhVGUAxgxLMbW4%2BbbHFwhHj3ZPjMkDTzw91M06FJmvh0rISuw1TaVSGXf%2BiBTXmM07uJEz6KvAnHl%2FsWQQ34ZTcvy4kyogmrppyUSeM%2FK137e7M46wv%2BXz5xUUfV0Pe99zQrIhqiEVhxoHvy5eBP5sTqZ2TK9mw%2FUdJ93CbiwEimLllcPiY%2BqM8RR0cGy5Ib%2Bhu77%2FQ3ilfwnn0Z%2BHmaSU5zmJj3s5AqDkMjTqWadU6BTCfz4q9BjqkAUtlVC4JKZuZjoIfFuWveTNNph9Jy8q20y5V7BAL0piMNJ%2B0yBW0nCXECXCkSgl%2FvalMI6zcrmKI7xxOXl3%2B7XXcfqubSF5MDQyh0n9pnDsxDOQfkjTib2UXBr5cvbPFArsudtjQfRqvLK5So2MkeGG%2FHQH%2FNyv52A0naZEa2tDhoR2WWQCQIGTCGjUsbtkhK0F7qKLObc5hiBapdTsTGosol0JF&X-Amz-Signature=15a06d57b7b0128ec4f72b54f95dac691a3fc3a7142e47927ac52167272d5e32&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QG5VVRJP%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T020452Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJIMEYCIQC%2BSqrbFuJOrvpzGGHUNWe31s9dw%2B2GWJDgax%2Bu2ALW0QIhAJKJ58hhmYfe9PA15wXcQt9V5EtzhaWhIlraKgT8y3UcKv8DCDkQABoMNjM3NDIzMTgzODA1IgxWwWv4wjHUrZk43Joq3AO0h%2BZ1d150v%2BlCRbZm6K%2FmwKut2myEqHc6Ca1qVVa%2BxY7gM1d8Z1czXHveTvnoXucccwt1irpc4qcVtI768LoEowhnv8CWC0UcIOiVqksThVkhHuKkD86isNzxoS1NZ%2Bc7eQFNaBxiKD9YO7oN0jULPwgtwBPd2wYbUWzA51uzcC0lKNKdVQE%2B4v0d75OfJz2S57l%2BOksfM%2BXEKy%2Bz3ZS9uMJw9XNqqGENpQ9rKtbggd83yQdNC2YyuNbWIb6viUSs6Zt0lepfhl8PPc%2BDXh3%2FmjXt4oTokSb3Qr7KbVTIS9sIN2KJnjj9fBjheWwl3bYLK3KWmWZAdc7666LGlz2z%2BDj9PavH9qlr8l5aq57z3CcRvbZK113mdqBbZfteUMSnWSIDyAFJYkMqKDhVGUAxgxLMbW4%2BbbHFwhHj3ZPjMkDTzw91M06FJmvh0rISuw1TaVSGXf%2BiBTXmM07uJEz6KvAnHl%2FsWQQ34ZTcvy4kyogmrppyUSeM%2FK137e7M46wv%2BXz5xUUfV0Pe99zQrIhqiEVhxoHvy5eBP5sTqZ2TK9mw%2FUdJ93CbiwEimLllcPiY%2BqM8RR0cGy5Ib%2Bhu77%2FQ3ilfwnn0Z%2BHmaSU5zmJj3s5AqDkMjTqWadU6BTCfz4q9BjqkAUtlVC4JKZuZjoIfFuWveTNNph9Jy8q20y5V7BAL0piMNJ%2B0yBW0nCXECXCkSgl%2FvalMI6zcrmKI7xxOXl3%2B7XXcfqubSF5MDQyh0n9pnDsxDOQfkjTib2UXBr5cvbPFArsudtjQfRqvLK5So2MkeGG%2FHQH%2FNyv52A0naZEa2tDhoR2WWQCQIGTCGjUsbtkhK0F7qKLObc5hiBapdTsTGosol0JF&X-Amz-Signature=6c2d37bf97854a5bc4962d6d71665f624c5c855bc7af825c6e66db1e9e42d698&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QG5VVRJP%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T020452Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJIMEYCIQC%2BSqrbFuJOrvpzGGHUNWe31s9dw%2B2GWJDgax%2Bu2ALW0QIhAJKJ58hhmYfe9PA15wXcQt9V5EtzhaWhIlraKgT8y3UcKv8DCDkQABoMNjM3NDIzMTgzODA1IgxWwWv4wjHUrZk43Joq3AO0h%2BZ1d150v%2BlCRbZm6K%2FmwKut2myEqHc6Ca1qVVa%2BxY7gM1d8Z1czXHveTvnoXucccwt1irpc4qcVtI768LoEowhnv8CWC0UcIOiVqksThVkhHuKkD86isNzxoS1NZ%2Bc7eQFNaBxiKD9YO7oN0jULPwgtwBPd2wYbUWzA51uzcC0lKNKdVQE%2B4v0d75OfJz2S57l%2BOksfM%2BXEKy%2Bz3ZS9uMJw9XNqqGENpQ9rKtbggd83yQdNC2YyuNbWIb6viUSs6Zt0lepfhl8PPc%2BDXh3%2FmjXt4oTokSb3Qr7KbVTIS9sIN2KJnjj9fBjheWwl3bYLK3KWmWZAdc7666LGlz2z%2BDj9PavH9qlr8l5aq57z3CcRvbZK113mdqBbZfteUMSnWSIDyAFJYkMqKDhVGUAxgxLMbW4%2BbbHFwhHj3ZPjMkDTzw91M06FJmvh0rISuw1TaVSGXf%2BiBTXmM07uJEz6KvAnHl%2FsWQQ34ZTcvy4kyogmrppyUSeM%2FK137e7M46wv%2BXz5xUUfV0Pe99zQrIhqiEVhxoHvy5eBP5sTqZ2TK9mw%2FUdJ93CbiwEimLllcPiY%2BqM8RR0cGy5Ib%2Bhu77%2FQ3ilfwnn0Z%2BHmaSU5zmJj3s5AqDkMjTqWadU6BTCfz4q9BjqkAUtlVC4JKZuZjoIfFuWveTNNph9Jy8q20y5V7BAL0piMNJ%2B0yBW0nCXECXCkSgl%2FvalMI6zcrmKI7xxOXl3%2B7XXcfqubSF5MDQyh0n9pnDsxDOQfkjTib2UXBr5cvbPFArsudtjQfRqvLK5So2MkeGG%2FHQH%2FNyv52A0naZEa2tDhoR2WWQCQIGTCGjUsbtkhK0F7qKLObc5hiBapdTsTGosol0JF&X-Amz-Signature=5e6602dee13e1fce66462915c17ccd23e1ee98570e835a2b2c55dc02dc477b9e&X-Amz-SignedHeaders=host&x-id=GetObject)


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

