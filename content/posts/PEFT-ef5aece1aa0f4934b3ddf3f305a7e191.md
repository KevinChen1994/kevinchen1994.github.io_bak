---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466UMEDE3UO%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250217T232150Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEFYaCXVzLXdlc3QtMiJGMEQCIFOTu74lGEejqRbKSRE11S3G%2BwS4YtDuyDR6OwhoXKncAiBAo\
  Ol%2FhVkxwD0i4ldRR%2F952c6XNGTx5GqbIxn3YcAnTCr%2FAwh%2FEAAaDDYzNzQyMzE4MzgwNS\
  IMeVEmyWrAK3Fo8iJiKtwDhUsUknbSnKdRus4%2FFZH8z6VG3Xo443hCpDnHgBH%2BiAUwntpuuVx\
  wRhdPc1hxtpmc6I71uFa09kEEn3yf4ST5auaM%2F3SLiYR7%2F8%2BrOSKXYd%2F%2BkSpN8u89Yx\
  GMQjOmGZtzrYNbCO0QyM6JzWFPZSWtaHF7T7JxG0ibh7Mz%2B%2Bn8Y4CKKI1dWi6ke5IbU68NGVy\
  OcjCvtWda2MbEkgNfAOGaH9tF5ZLvsyhiR8QaL%2F8qqmaQWZPnAca5%2FOq8mbyRHl2ewJP%2FBT\
  Tgzs9VDVnwwFP6qX8wbib%2FAHdwzqwixHp%2F53riEGE%2F2zaFHgcm4zNIhhu2JoEnB94RSu%2B\
  uP0wjpwkNMPhHVHuw1s1k1hG3whtx6L2PVCsPXV%2BuWoPdrfGmbNA%2Beod%2BXsL6HzNhOHeQy8\
  gnwC6SbQzo%2BMBxvxpjaA1aN%2F0WJZuP4I4B9jOCq%2B2xo2iVGUpXX1gNbH6gFqZvoKvRHhrg%\
  2BW8HD0tQkofUhf626fEYG8O06E9UYrkvQtzVlyoU9%2FvI6sxcdVzmx3zN4h%2BKcg%2B4dqlpcO\
  tPoTJF4ts8Nqx8KyB5NySO4t5SiSjDBoYGhZh8Nzk7hb%2F1m1DA%2F7AqyF48kentvlNCUROTK7S\
  LqON7N8MUvZKs2PE5Ujwwr%2BrOvQY6pgGK6nJHnSt3Epe%2BV8EVn5X5%2BrjD3XEqT28Oiid7yT\
  g%2BgeRHvSvz48mX%2F4WqJMfSHiiS%2FV9d3ew%2BTuf00FWDMk48WhCZx86ZgJq5ZnnIxzNtmo6\
  nYYwiM8mqZpGoglCPKkk%2BAElrAK5UvCHHxzlcEw%2FCgJPWMtlc8WiewHWE6v%2Bo3HEOJc7i6a\
  zhx6hEwvfJEYukVWrcP%2B%2F3GyeC5Ywt5qaiybisXcni&X-Amz-Signature=683c0868e53be9\
  649044cd1f8970732b0c73422e3539d1e583256c22f81194a7&X-Amz-SignedHeaders=host&x\
  -id=GetObject"
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
        redential=ASIAZI2LB466WVHS3BQV%2F20250217%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250217T232029Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEFYaCXVzLXdlc3QtMiJGMEQCIH0z%2Fyb6t4UYCGu%2Bo1AXLwojEG7\
        5KmKAe1WS48nS4vWoAiBPFrQ2C5OabER%2F4yED2J6UcRADl3v25zv0oeOppX85WCr%2FAw\
        h%2FEAAaDDYzNzQyMzE4MzgwNSIMPpKcHPvVt4kwbmzyKtwDVwn8NNXYX3KHuRwNQT04Y7y\
        Co6Vl8fyNtx%2BN9jXxGE%2Bg0zXpzrFku6QsTJalR92eYsi4ZzecTR5quI4n5Vhy9%2B47\
        jinkEg8t%2BE9btIVl7Di4uPeiFcjuGTYEI0M8G4luYgsJF%2BlRahtfM6doTLop8WYEwcG\
        brGiX9nf%2BZgh1MTf4YgHC5OeFTOYNR2U8DuExB%2Ff9hf8Nwkyg3HLaeYvUsQBlt%2FJ7\
        WZAnDBgRdDrcpGM8ZBZr%2FsJYOmBppZZ%2FCcwuNAzf2xeym5pYKMHB%2Ba4ETrgX2KGPQ\
        gxzzBy62%2F8FsV2l6hHjPiJ5PWFXkp5YY9KN43OZeRaMvRJ56YdV5sNLoHOsbybn836vlK\
        Zz9xwI5BEpAzBEE04QEdZPhy0KjHKNiHog5lzKKFyE7OefjgRT%2B%2FG5TckYEhXaL3d6E\
        4ORLsNfKReyOta40CVw9frgGg7AT8LtqcpTSZ15tbYNd%2BxVeNoY1SDcZ7o2ypataXudwk\
        FWZSwfVIjO%2FVA1jkCeaHk5H%2FCdedMnapX5awIwlapSVgVuBTrc%2Fm6amXYzbh4Ghl2\
        ROXOOY8LlZu0pF421zRb7nlniU4ynn34JMeLGtKla%2FFhd%2FxTgt%2FvXPsjV0VFzF1gf\
        w21LGti%2Fbl5E6pEw6%2BrOvQY6pgEBbhUbbXcmtHmgVnejmHCkUDwAnqeYODNymermr48\
        LanzwjtVeV2Ju%2BZ0UQ%2FZVQ9PcjhKLd0CGxc0Su8ZvkN1Jf9cd4QkfFIGJFq4IHHYx5z\
        V%2FrpmJtDi%2F1JWqapQ0G7yl%2FAqtrYArT27AIa3wWTOMjwWinAZiECodlWIHQhtK6Ge\
        3%2BoQu5ak6D%2FoHirbYn2Yde2yquX%2F5iA1QWmQ5kcvf25Jb7XfQ&X-Amz-Signature\
        =791334b9d24a617a5524172953d76d26ae169b6e37d3ce4fdd33ac8cb98478b6&X-Amz\
        -SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-18T00:20:29.051Z"
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
UPDATE_TIME: "2025-02-17T23:21:54.603Z"
EXPIRY_TIME: "2025-02-18T00:21:48.419Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TOVLWVBB%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T232148Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFYaCXVzLXdlc3QtMiJIMEYCIQCX%2BfQ4bjphnEL48Fhu2L5M6Qc0s4v%2FNHAl3KVRuWNY6QIhAMebNzNevLO8Tf0Tsn7FAP0WU72F2rabFtNmEToGHwVWKv8DCH8QABoMNjM3NDIzMTgzODA1IgxFZ09E8znJPWdkic8q3ANhYaZlPZIRINzMe7EsJfGB3nwA54iWESYYKQATy6daOMUT12YsrOd6v9QKkn06XmemyAA2AdDWr2bBN%2BYy3CdK3HUhgPjMv7zH9HpRlrLIDIgk5KJ5hwsydFA%2B%2BaAl1Kx51cO8W73JvQgq56%2F2gLzXDVnuOT2WZPTTmL65efirS2la0QO38n8JwcK77uVXz2263364GIkwcxNCVLBUcTZElWNnGVgNGL27X35Tq6ikYjacRqnhWOx5rL5db4DByp2SvY3JYg%2F96ouSSTt7OR%2BRFIp%2FDlyBJVYT%2FGSoSPlMYIZa1VB92ePExPu40Nrpp20duqGIXLXujVAGdw5txiF%2BkLn0%2BXMOoeeo40S8ijyZGK49ziUEGQgemSpyotzG%2BX8mbSBE%2FmAPhvL688DpxQbH2Ylr5Ax8jRnEx9Ihu5rMy%2B4mie6J%2FycQ3Vb8U0Lq7HgPrem8gbJlRwWUtFxhLsnrOqrRGOwqpzJENvlyAunUJX%2BtHsQdgHIm%2BU8gZ6vld1WvbiwooY%2F93JYc8cAxduSsBbnm0um1UbN8P4YMcGR7IU5mmo35eVVOsi9N6xL9lTBrz9IcdEAPTijKeYRr6XDWNr%2B4XTrHazSxOedycjM49%2BKNddaMnde1YKeXPTDC6s69BjqkAdU7LGOAcUUl0hXPfrzU8FMaR6z64t2J5%2BQxaKIz9twh6gOGe3QZcQe0LM9yzYGUVcBvJIa2u8yiZgVlrYv8bpJbth0u9e80QmCYmMZ9Qba5GfsAa8%2FHa9OJIGmYIlpHC4f7C9AOJQbozKc7EotzR0Mdaa9ZaHS5nEKSGKaouYiy6j%2B3zIhLsFiSKGZb3tNg%2BvazyEs3ZYS7GeAa7CciiesvPVQO&X-Amz-Signature=e96848a563f4c74c104912f92800473ecc44ea1104d2ce1898d8f1700dc84962&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TOVLWVBB%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T232148Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFYaCXVzLXdlc3QtMiJIMEYCIQCX%2BfQ4bjphnEL48Fhu2L5M6Qc0s4v%2FNHAl3KVRuWNY6QIhAMebNzNevLO8Tf0Tsn7FAP0WU72F2rabFtNmEToGHwVWKv8DCH8QABoMNjM3NDIzMTgzODA1IgxFZ09E8znJPWdkic8q3ANhYaZlPZIRINzMe7EsJfGB3nwA54iWESYYKQATy6daOMUT12YsrOd6v9QKkn06XmemyAA2AdDWr2bBN%2BYy3CdK3HUhgPjMv7zH9HpRlrLIDIgk5KJ5hwsydFA%2B%2BaAl1Kx51cO8W73JvQgq56%2F2gLzXDVnuOT2WZPTTmL65efirS2la0QO38n8JwcK77uVXz2263364GIkwcxNCVLBUcTZElWNnGVgNGL27X35Tq6ikYjacRqnhWOx5rL5db4DByp2SvY3JYg%2F96ouSSTt7OR%2BRFIp%2FDlyBJVYT%2FGSoSPlMYIZa1VB92ePExPu40Nrpp20duqGIXLXujVAGdw5txiF%2BkLn0%2BXMOoeeo40S8ijyZGK49ziUEGQgemSpyotzG%2BX8mbSBE%2FmAPhvL688DpxQbH2Ylr5Ax8jRnEx9Ihu5rMy%2B4mie6J%2FycQ3Vb8U0Lq7HgPrem8gbJlRwWUtFxhLsnrOqrRGOwqpzJENvlyAunUJX%2BtHsQdgHIm%2BU8gZ6vld1WvbiwooY%2F93JYc8cAxduSsBbnm0um1UbN8P4YMcGR7IU5mmo35eVVOsi9N6xL9lTBrz9IcdEAPTijKeYRr6XDWNr%2B4XTrHazSxOedycjM49%2BKNddaMnde1YKeXPTDC6s69BjqkAdU7LGOAcUUl0hXPfrzU8FMaR6z64t2J5%2BQxaKIz9twh6gOGe3QZcQe0LM9yzYGUVcBvJIa2u8yiZgVlrYv8bpJbth0u9e80QmCYmMZ9Qba5GfsAa8%2FHa9OJIGmYIlpHC4f7C9AOJQbozKc7EotzR0Mdaa9ZaHS5nEKSGKaouYiy6j%2B3zIhLsFiSKGZb3tNg%2BvazyEs3ZYS7GeAa7CciiesvPVQO&X-Amz-Signature=5943196589aff59f7d757243e1dac02f72840fc0ef06e9f9b4b0621c1eed9c5c&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TOVLWVBB%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T232148Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFYaCXVzLXdlc3QtMiJIMEYCIQCX%2BfQ4bjphnEL48Fhu2L5M6Qc0s4v%2FNHAl3KVRuWNY6QIhAMebNzNevLO8Tf0Tsn7FAP0WU72F2rabFtNmEToGHwVWKv8DCH8QABoMNjM3NDIzMTgzODA1IgxFZ09E8znJPWdkic8q3ANhYaZlPZIRINzMe7EsJfGB3nwA54iWESYYKQATy6daOMUT12YsrOd6v9QKkn06XmemyAA2AdDWr2bBN%2BYy3CdK3HUhgPjMv7zH9HpRlrLIDIgk5KJ5hwsydFA%2B%2BaAl1Kx51cO8W73JvQgq56%2F2gLzXDVnuOT2WZPTTmL65efirS2la0QO38n8JwcK77uVXz2263364GIkwcxNCVLBUcTZElWNnGVgNGL27X35Tq6ikYjacRqnhWOx5rL5db4DByp2SvY3JYg%2F96ouSSTt7OR%2BRFIp%2FDlyBJVYT%2FGSoSPlMYIZa1VB92ePExPu40Nrpp20duqGIXLXujVAGdw5txiF%2BkLn0%2BXMOoeeo40S8ijyZGK49ziUEGQgemSpyotzG%2BX8mbSBE%2FmAPhvL688DpxQbH2Ylr5Ax8jRnEx9Ihu5rMy%2B4mie6J%2FycQ3Vb8U0Lq7HgPrem8gbJlRwWUtFxhLsnrOqrRGOwqpzJENvlyAunUJX%2BtHsQdgHIm%2BU8gZ6vld1WvbiwooY%2F93JYc8cAxduSsBbnm0um1UbN8P4YMcGR7IU5mmo35eVVOsi9N6xL9lTBrz9IcdEAPTijKeYRr6XDWNr%2B4XTrHazSxOedycjM49%2BKNddaMnde1YKeXPTDC6s69BjqkAdU7LGOAcUUl0hXPfrzU8FMaR6z64t2J5%2BQxaKIz9twh6gOGe3QZcQe0LM9yzYGUVcBvJIa2u8yiZgVlrYv8bpJbth0u9e80QmCYmMZ9Qba5GfsAa8%2FHa9OJIGmYIlpHC4f7C9AOJQbozKc7EotzR0Mdaa9ZaHS5nEKSGKaouYiy6j%2B3zIhLsFiSKGZb3tNg%2BvazyEs3ZYS7GeAa7CciiesvPVQO&X-Amz-Signature=8a0d300de62123023e2c0fddf68188bf3e2120de1b048ce0cc78e2fd6a78b6be&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TOVLWVBB%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T232148Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFYaCXVzLXdlc3QtMiJIMEYCIQCX%2BfQ4bjphnEL48Fhu2L5M6Qc0s4v%2FNHAl3KVRuWNY6QIhAMebNzNevLO8Tf0Tsn7FAP0WU72F2rabFtNmEToGHwVWKv8DCH8QABoMNjM3NDIzMTgzODA1IgxFZ09E8znJPWdkic8q3ANhYaZlPZIRINzMe7EsJfGB3nwA54iWESYYKQATy6daOMUT12YsrOd6v9QKkn06XmemyAA2AdDWr2bBN%2BYy3CdK3HUhgPjMv7zH9HpRlrLIDIgk5KJ5hwsydFA%2B%2BaAl1Kx51cO8W73JvQgq56%2F2gLzXDVnuOT2WZPTTmL65efirS2la0QO38n8JwcK77uVXz2263364GIkwcxNCVLBUcTZElWNnGVgNGL27X35Tq6ikYjacRqnhWOx5rL5db4DByp2SvY3JYg%2F96ouSSTt7OR%2BRFIp%2FDlyBJVYT%2FGSoSPlMYIZa1VB92ePExPu40Nrpp20duqGIXLXujVAGdw5txiF%2BkLn0%2BXMOoeeo40S8ijyZGK49ziUEGQgemSpyotzG%2BX8mbSBE%2FmAPhvL688DpxQbH2Ylr5Ax8jRnEx9Ihu5rMy%2B4mie6J%2FycQ3Vb8U0Lq7HgPrem8gbJlRwWUtFxhLsnrOqrRGOwqpzJENvlyAunUJX%2BtHsQdgHIm%2BU8gZ6vld1WvbiwooY%2F93JYc8cAxduSsBbnm0um1UbN8P4YMcGR7IU5mmo35eVVOsi9N6xL9lTBrz9IcdEAPTijKeYRr6XDWNr%2B4XTrHazSxOedycjM49%2BKNddaMnde1YKeXPTDC6s69BjqkAdU7LGOAcUUl0hXPfrzU8FMaR6z64t2J5%2BQxaKIz9twh6gOGe3QZcQe0LM9yzYGUVcBvJIa2u8yiZgVlrYv8bpJbth0u9e80QmCYmMZ9Qba5GfsAa8%2FHa9OJIGmYIlpHC4f7C9AOJQbozKc7EotzR0Mdaa9ZaHS5nEKSGKaouYiy6j%2B3zIhLsFiSKGZb3tNg%2BvazyEs3ZYS7GeAa7CciiesvPVQO&X-Amz-Signature=64fc4d364ee1418faa2498634b40f92b6336421704ae56bd9befe32f44926e86&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TOVLWVBB%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T232148Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFYaCXVzLXdlc3QtMiJIMEYCIQCX%2BfQ4bjphnEL48Fhu2L5M6Qc0s4v%2FNHAl3KVRuWNY6QIhAMebNzNevLO8Tf0Tsn7FAP0WU72F2rabFtNmEToGHwVWKv8DCH8QABoMNjM3NDIzMTgzODA1IgxFZ09E8znJPWdkic8q3ANhYaZlPZIRINzMe7EsJfGB3nwA54iWESYYKQATy6daOMUT12YsrOd6v9QKkn06XmemyAA2AdDWr2bBN%2BYy3CdK3HUhgPjMv7zH9HpRlrLIDIgk5KJ5hwsydFA%2B%2BaAl1Kx51cO8W73JvQgq56%2F2gLzXDVnuOT2WZPTTmL65efirS2la0QO38n8JwcK77uVXz2263364GIkwcxNCVLBUcTZElWNnGVgNGL27X35Tq6ikYjacRqnhWOx5rL5db4DByp2SvY3JYg%2F96ouSSTt7OR%2BRFIp%2FDlyBJVYT%2FGSoSPlMYIZa1VB92ePExPu40Nrpp20duqGIXLXujVAGdw5txiF%2BkLn0%2BXMOoeeo40S8ijyZGK49ziUEGQgemSpyotzG%2BX8mbSBE%2FmAPhvL688DpxQbH2Ylr5Ax8jRnEx9Ihu5rMy%2B4mie6J%2FycQ3Vb8U0Lq7HgPrem8gbJlRwWUtFxhLsnrOqrRGOwqpzJENvlyAunUJX%2BtHsQdgHIm%2BU8gZ6vld1WvbiwooY%2F93JYc8cAxduSsBbnm0um1UbN8P4YMcGR7IU5mmo35eVVOsi9N6xL9lTBrz9IcdEAPTijKeYRr6XDWNr%2B4XTrHazSxOedycjM49%2BKNddaMnde1YKeXPTDC6s69BjqkAdU7LGOAcUUl0hXPfrzU8FMaR6z64t2J5%2BQxaKIz9twh6gOGe3QZcQe0LM9yzYGUVcBvJIa2u8yiZgVlrYv8bpJbth0u9e80QmCYmMZ9Qba5GfsAa8%2FHa9OJIGmYIlpHC4f7C9AOJQbozKc7EotzR0Mdaa9ZaHS5nEKSGKaouYiy6j%2B3zIhLsFiSKGZb3tNg%2BvazyEs3ZYS7GeAa7CciiesvPVQO&X-Amz-Signature=3b1959b423e8af53d526b5dcd43bfb95b20379fdd85b518db373403dbab70914&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46635KQAEKD%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T232149Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFYaCXVzLXdlc3QtMiJHMEUCIBC63kK5Q%2B2wa%2BocbXzgb%2BbP30jElUR8Qe6tDsqIRDiKAiEAyhRCJcS3oIWs9iSuTcREsL6Y95w9nh1aD0DZqJ4Ir4kq%2FwMIfxAAGgw2Mzc0MjMxODM4MDUiDK%2Bgz9oZNBmhDbr%2BICrcA7cIJmiL6DgT6jpUYs72VlIVZYreZ3%2FjKDEsC6uTLSOPO3ZAjp6QU%2BriIQDVzwSL4fYNzxVXRWNH9qEGLI1bGo9SSpZFPor8scOOsefw0SK4mMabvf4JE2T%2F1Rtc5e31%2BS4oonk%2BS%2Bp9aGRsRu9Ibc8WIdo%2BBN9kUog%2F2mE7nvi25IDSNkLhNLp2amFW0je1ERQLsfeOTVChxbitmRucnVoUCWBBd1u9F9BSnzxzZ5F4aLT1hZHIynr9vip8MDwthKTqU6SlQwWXKo2Y3CtxhNZqvVIuHy9GU079QgbYyE2c3nb%2BBTx5Dpe3V98tI7G1G7hFTl9sftIs57fyjx4BZc095As2eAkJoMJJctGlT%2BDKkT1%2Fb2XgcIEVyWlKbzmKJbWLqmIYAwYOdKCs6kJ8r9uxiBjIFKOkjJpjUR8R8QI%2FmkYbKJB%2B%2Fk82x7PR5bAWf7rkyYmXO1uh%2BZ4e04r1JW9Ag7rmKeGzU4wxKGagT32XfH1jYIbduKhI2Eb8B6YvmdiiQx7MiQgBWr%2FqK129OGRsQsuy%2FB%2BmpNFo1wDIMg58jzPVhODyVqw89Qph8RCDa6kdfOHH9pAe7xzzyOvo8mfF5Fm%2B4FnLI6KvpfKvKOacI0%2BpiUXn7Y3TGD3TMLrqzr0GOqUBZohprTAdaTbji%2BlztN4ElNjEC4ET4qD%2FX9RJfY%2FNUd1SGiz1edoryDgBrgbLfoWfD5f4CzYlzGhk5oaqFh1Yg%2B%2BLAGmsdFLPthPtBTdDX13PrZGmEa2b5mb3LgZqH%2BtnE2iBTeSVK5k5B28hqITM%2FQVdZW%2BpoNd9FVulcFrJ%2BdmIz5pkM%2B7OwkfRUpFdhOqrLMMYOar7xqrYRc3Np0ZnCu9qgVf4&X-Amz-Signature=be5dc7b5e792120c9108391407d0867a48111b2b440e986e901702224dffb7a1&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665LY3MXRH%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T232149Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFcaCXVzLXdlc3QtMiJHMEUCIEuvZUFPD5ZJfOmwYh2QcfTVfEy2ToMTDAqzrFh5mKPzAiEAlP5hzYx%2FGDdjMbpYdMjKFEXGA0r4F8CGj5%2F%2F1iaK8eoq%2FwMIfxAAGgw2Mzc0MjMxODM4MDUiDI2N0ripG4hvq3Vy3yrcAwBvvwag5XzvDjnzMSeurlZxLjBVz054Ea9BllC0aQx7GN3znPznLF8lnPolnYPN348qINtOwa1k1f4s%2F85UQ86RgdulX1eB9ofwlk1yUQSnwKIfP8iXp6LMz1jniTYukGF0OiBBj2wrF4PqLuz7RcRhHl1KNp4AL68CAccoOKjoKZzc7JtxYOd1IpSkR%2BVbilOEuOcQAt6pMJgFz9d6n19gBWF1w1r%2BffRHq4tAlQuI9zTnV9d2AjWmW2AMQ8sadatiYaNJNpuEh2Ox5NjJEZztjaRJIQc%2FEmhLB9cbBz0qYUrVVBhERnrKgZG8oGmj2AB%2F%2BItyzkGa5euWBhvwVGMDQUwc16feMvieXwKGXE8bF7gHIIXMVy4wOdDmupvKUubzLxNltV38uPizbC0IzmL0ZLb9Yulx9y2wShfauXmq%2FQ4ic1CwgE8E52gfDlEkN5h7G0cEUHDYnfMbi0uzS55F3EA2siqI8mFAXXCyqsTOZs6JJdvC6Hj2lRY02Qxt%2BpOHEZeLHail6FxJUFeGFlyU5bbIHTs89m7GgwO4bg6tH5%2BcTKiC%2Blrx%2BWsJsEVsgsqgk3QcbUonEefmVg5e8Uicsy1VDtuH5sHuXX1uU2D8H9IOle3Jzxf1xwsKMKLrzr0GOqUBybQKyB2I2y6TkG5WtrdsMehxT0dW36kKa014%2FU5PCZFBsyoE6sB3zNcuSBPn57FVpV4%2F%2Fi6CU2LOzoxPjVhEwRRTqQmN8x9gDAfLA2esB8zW6hkk7%2BZpHWJ%2FbG5Gn%2Bz0RBUreaHx%2BEDHxq0qLTt9IwPzNA0qDdIlJgCla8qUVu%2F0WODgb1pnLHbvqwgSPPq%2Bt%2FwcnwZxws%2FtrB3qBLlUkRQbaU81&X-Amz-Signature=026a511452871dacc7fed86213fa844e98d68e656860d3a01a7be4f44592e655&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TOVLWVBB%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T232148Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFYaCXVzLXdlc3QtMiJIMEYCIQCX%2BfQ4bjphnEL48Fhu2L5M6Qc0s4v%2FNHAl3KVRuWNY6QIhAMebNzNevLO8Tf0Tsn7FAP0WU72F2rabFtNmEToGHwVWKv8DCH8QABoMNjM3NDIzMTgzODA1IgxFZ09E8znJPWdkic8q3ANhYaZlPZIRINzMe7EsJfGB3nwA54iWESYYKQATy6daOMUT12YsrOd6v9QKkn06XmemyAA2AdDWr2bBN%2BYy3CdK3HUhgPjMv7zH9HpRlrLIDIgk5KJ5hwsydFA%2B%2BaAl1Kx51cO8W73JvQgq56%2F2gLzXDVnuOT2WZPTTmL65efirS2la0QO38n8JwcK77uVXz2263364GIkwcxNCVLBUcTZElWNnGVgNGL27X35Tq6ikYjacRqnhWOx5rL5db4DByp2SvY3JYg%2F96ouSSTt7OR%2BRFIp%2FDlyBJVYT%2FGSoSPlMYIZa1VB92ePExPu40Nrpp20duqGIXLXujVAGdw5txiF%2BkLn0%2BXMOoeeo40S8ijyZGK49ziUEGQgemSpyotzG%2BX8mbSBE%2FmAPhvL688DpxQbH2Ylr5Ax8jRnEx9Ihu5rMy%2B4mie6J%2FycQ3Vb8U0Lq7HgPrem8gbJlRwWUtFxhLsnrOqrRGOwqpzJENvlyAunUJX%2BtHsQdgHIm%2BU8gZ6vld1WvbiwooY%2F93JYc8cAxduSsBbnm0um1UbN8P4YMcGR7IU5mmo35eVVOsi9N6xL9lTBrz9IcdEAPTijKeYRr6XDWNr%2B4XTrHazSxOedycjM49%2BKNddaMnde1YKeXPTDC6s69BjqkAdU7LGOAcUUl0hXPfrzU8FMaR6z64t2J5%2BQxaKIz9twh6gOGe3QZcQe0LM9yzYGUVcBvJIa2u8yiZgVlrYv8bpJbth0u9e80QmCYmMZ9Qba5GfsAa8%2FHa9OJIGmYIlpHC4f7C9AOJQbozKc7EotzR0Mdaa9ZaHS5nEKSGKaouYiy6j%2B3zIhLsFiSKGZb3tNg%2BvazyEs3ZYS7GeAa7CciiesvPVQO&X-Amz-Signature=ac3e005e8a784428340e30c883db6cbe9b6e121e3496a3d303c8820104a08b6f&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TOVLWVBB%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T232148Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFYaCXVzLXdlc3QtMiJIMEYCIQCX%2BfQ4bjphnEL48Fhu2L5M6Qc0s4v%2FNHAl3KVRuWNY6QIhAMebNzNevLO8Tf0Tsn7FAP0WU72F2rabFtNmEToGHwVWKv8DCH8QABoMNjM3NDIzMTgzODA1IgxFZ09E8znJPWdkic8q3ANhYaZlPZIRINzMe7EsJfGB3nwA54iWESYYKQATy6daOMUT12YsrOd6v9QKkn06XmemyAA2AdDWr2bBN%2BYy3CdK3HUhgPjMv7zH9HpRlrLIDIgk5KJ5hwsydFA%2B%2BaAl1Kx51cO8W73JvQgq56%2F2gLzXDVnuOT2WZPTTmL65efirS2la0QO38n8JwcK77uVXz2263364GIkwcxNCVLBUcTZElWNnGVgNGL27X35Tq6ikYjacRqnhWOx5rL5db4DByp2SvY3JYg%2F96ouSSTt7OR%2BRFIp%2FDlyBJVYT%2FGSoSPlMYIZa1VB92ePExPu40Nrpp20duqGIXLXujVAGdw5txiF%2BkLn0%2BXMOoeeo40S8ijyZGK49ziUEGQgemSpyotzG%2BX8mbSBE%2FmAPhvL688DpxQbH2Ylr5Ax8jRnEx9Ihu5rMy%2B4mie6J%2FycQ3Vb8U0Lq7HgPrem8gbJlRwWUtFxhLsnrOqrRGOwqpzJENvlyAunUJX%2BtHsQdgHIm%2BU8gZ6vld1WvbiwooY%2F93JYc8cAxduSsBbnm0um1UbN8P4YMcGR7IU5mmo35eVVOsi9N6xL9lTBrz9IcdEAPTijKeYRr6XDWNr%2B4XTrHazSxOedycjM49%2BKNddaMnde1YKeXPTDC6s69BjqkAdU7LGOAcUUl0hXPfrzU8FMaR6z64t2J5%2BQxaKIz9twh6gOGe3QZcQe0LM9yzYGUVcBvJIa2u8yiZgVlrYv8bpJbth0u9e80QmCYmMZ9Qba5GfsAa8%2FHa9OJIGmYIlpHC4f7C9AOJQbozKc7EotzR0Mdaa9ZaHS5nEKSGKaouYiy6j%2B3zIhLsFiSKGZb3tNg%2BvazyEs3ZYS7GeAa7CciiesvPVQO&X-Amz-Signature=2ad3828e777a1ae4d421f11a234911fad126647138a92d2a1d390d4cf18d8767&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TOVLWVBB%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T232148Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFYaCXVzLXdlc3QtMiJIMEYCIQCX%2BfQ4bjphnEL48Fhu2L5M6Qc0s4v%2FNHAl3KVRuWNY6QIhAMebNzNevLO8Tf0Tsn7FAP0WU72F2rabFtNmEToGHwVWKv8DCH8QABoMNjM3NDIzMTgzODA1IgxFZ09E8znJPWdkic8q3ANhYaZlPZIRINzMe7EsJfGB3nwA54iWESYYKQATy6daOMUT12YsrOd6v9QKkn06XmemyAA2AdDWr2bBN%2BYy3CdK3HUhgPjMv7zH9HpRlrLIDIgk5KJ5hwsydFA%2B%2BaAl1Kx51cO8W73JvQgq56%2F2gLzXDVnuOT2WZPTTmL65efirS2la0QO38n8JwcK77uVXz2263364GIkwcxNCVLBUcTZElWNnGVgNGL27X35Tq6ikYjacRqnhWOx5rL5db4DByp2SvY3JYg%2F96ouSSTt7OR%2BRFIp%2FDlyBJVYT%2FGSoSPlMYIZa1VB92ePExPu40Nrpp20duqGIXLXujVAGdw5txiF%2BkLn0%2BXMOoeeo40S8ijyZGK49ziUEGQgemSpyotzG%2BX8mbSBE%2FmAPhvL688DpxQbH2Ylr5Ax8jRnEx9Ihu5rMy%2B4mie6J%2FycQ3Vb8U0Lq7HgPrem8gbJlRwWUtFxhLsnrOqrRGOwqpzJENvlyAunUJX%2BtHsQdgHIm%2BU8gZ6vld1WvbiwooY%2F93JYc8cAxduSsBbnm0um1UbN8P4YMcGR7IU5mmo35eVVOsi9N6xL9lTBrz9IcdEAPTijKeYRr6XDWNr%2B4XTrHazSxOedycjM49%2BKNddaMnde1YKeXPTDC6s69BjqkAdU7LGOAcUUl0hXPfrzU8FMaR6z64t2J5%2BQxaKIz9twh6gOGe3QZcQe0LM9yzYGUVcBvJIa2u8yiZgVlrYv8bpJbth0u9e80QmCYmMZ9Qba5GfsAa8%2FHa9OJIGmYIlpHC4f7C9AOJQbozKc7EotzR0Mdaa9ZaHS5nEKSGKaouYiy6j%2B3zIhLsFiSKGZb3tNg%2BvazyEs3ZYS7GeAa7CciiesvPVQO&X-Amz-Signature=254a7a1c63e5d913a455796d990ea8ed246cb3881a1a99e89c32ebab50f477a3&X-Amz-SignedHeaders=host&x-id=GetObject)


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

