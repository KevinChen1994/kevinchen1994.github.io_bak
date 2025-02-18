---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4667CYZJF2O%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250218T092519Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEGIaCXVzLXdlc3QtMiJGMEQCIG2dsHdZbVn5fwuV4zcLNB0A1mxrRllnRpT%2B8UdwIIsaAiAhE\
  gO9gK847Px32%2FS7nooufh9XthjIx0O6uZx4FtB5QiqIBAiK%2F%2F%2F%2F%2F%2F%2F%2F%2F%\
  2F8BEAAaDDYzNzQyMzE4MzgwNSIMmQy%2Fmh%2FWOnaGPdTLKtwDJW3A87EfRGBvGcCBcWILQxuIX\
  TpZqppk%2BjFLsBBKEgltLUg5w6dnkUAmqw%2FkpL57r8COYiPqd%2BXH9aYFUKhtkrlKf6hFiJXH\
  32nkJ%2BAjqqyx3GkC8bhRVM%2FulxhbECzyWzHajfYXIGB5Pg8ytoryKvMQBeacLzNoAdFZZF0cT\
  oXFpwKQ0vvTLLi9FFSNmByneOzRBfnImHUuB4Mg6TZ2S993kyTb%2FzsywNzLFuslP7QfFh3inGl8\
  JC%2BanPFCgDnwv2EvtslWo9%2F5RBo4ktbexcUA3IdV3k89gZHU572sSHsFr7Vo9HqZwhoiIphKl\
  WNmtdrA%2F6QK6uecz%2FHCe6LzsUhdh9ihq%2F4FPJA8foKYtyswZIaeZh5ytOFX7s9nLGKZjZCu\
  FZqqPA1h3cRAOmetuWB7f9WmXJCnzF0XIMhRAL9DoWDlsMt422%2BGhPtJvhXIKoYlhyuhtPktEdf\
  %2Fvt5QfpngTsRl55UjNv%2BouANvztgo8OLz7ruiTVMw3rXKmMT%2B970GgXnIth%2F4XGELBYVm\
  nMZZbaQAGK%2F679d5%2BFGbZxvQGy2XUNlN3%2B%2BggcTLOCzEbtT1PvbQ0kNtdz24mmzkW74K%\
  2BSubunUit%2BSvGWNcOGDyWU9Z3Eh9OYV4TxkwkKLRvQY6pgGfyHyo3HvgPF10C602jMedPzVLpy\
  K3eBBXfFcNQbImbGbwVAWmbGEOm62QZGnKFaAAd5%2FjuzBw6JIUys0h7%2FGTDS%2FtYVhpyPYXu\
  ZQ%2BGHriKMJ2rh0el4uq6MMWityX61kekfr8BjIxe76SlKj7Ga8LZvi7PtifWgykVBKwccrz09Nk\
  7hVdjlRZOSrVCabeKufiSaYBXTg0yai96c2YEr5%2FoML7CAbJ&X-Amz-Signature=3bb0b08f92\
  78fa8aae48e18f38c0615184d7a2d86a30d2110dd54398f53e635d&X-Amz-SignedHeaders=ho\
  st&x-id=GetObject"
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
        redential=ASIAZI2LB4666MLDO7B6%2F20250218%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250218T092354Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEGAaCXVzLXdlc3QtMiJGMEQCICmP82yTlKqelkjxq%2F3bcbD%2FPq7\
        wPTdD4LTWUNj1a7MFAiBjgSt8NYCZ7fwzCfu8KMrHkbMhY47cuXwoDJL1O%2Fs97SqIBAiJ\
        %2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMnrhmSNKIoClaHgH\
        BKtwDwPZVMTauq%2FiJT5TwBzkeM0ls27cRPNOxpyNqPGl1HmN5NGo%2Fp0OyZPZOJLe31A\
        qXrMQg1Y4jfpTJtJJ62%2BSNiPnR%2F1eBCnfMtBk0h3ecx4jFJzXD%2FOa4AKCCwXkWCMe\
        LaevhdTD0vQ10Pyg2HWmlQwh9Kj9cgKaDOXgTVPRxhNQA0plTYyQ27v3kh7wNKmn2cxP5VZ\
        LWsJlfnyTC6RzUJs43kQYPNkq6kJGXV0lJK73Zd6JpqXzWVC6Qj2U%2F4qP09VNZt9BN38H\
        FQLwP9E6gdkN8LKZBpX3zM0nL0J%2FunBvCuhQjS7HEeGV0T12%2B%2FFfnrju7wBF%2F%2\
        FMm%2FEXNW1lUlhMVrTPmDHBGfl0%2FMWIgGWRyn3Xsq5lk0a0tGM4MRiaMUSbqmRqKeuS7\
        VyVyEoNotNcgm0jooYpVPNYyFc6RRXLUvYQ83ezQUdojHlcBLz7GgG98PqQzDo5tY8veOCr\
        KcJR1uYjxIi22lWAVJbUrfe8QT7D1f7DPlaQqy29PmREMZAYZtcqhBoL4W8McTglBebomxO\
        3EAF44u%2BUJ2Lk82TJzSE2FrCS0uKCvLIKWVkosCmH7BCbTqFsv5IW5TNr2hMhEywiZenI\
        V%2B%2FsrfZGVB8QDxIrPXpuxYwwFWmM4w%2B%2F7QvQY6pgF2pmFJCkoXDmbgMqU4MkC0K\
        0JuXFr1eA2PjXd3c%2BpjEaPJZz9y7CgmwG3cg3Q1CSsFYM0iOw8UtEGp6j6hXcSIkB6feG\
        DNqqlV8%2BJ%2Fu0ZyUFIdbLVnssGuiSo%2B2uXzloVAksW3CE5n0QLeP3u8Afcdn8%2BgW\
        Ye%2FmXQwl%2Bo%2BF45jsL%2FtKiv7srcu4%2FYAzT%2FqJ%2F1BUrWtxXwTjEPvo7owcR\
        fGRP55%2FPeG&X-Amz-Signature=652306b27686d3f538e3f371e343085357340819e0\
        8ccaea28c9abf9c110e2bb&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-18T10:23:54.030Z"
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
UPDATE_TIME: "2025-02-18T09:25:27.068Z"
EXPIRY_TIME: "2025-02-18T10:25:14.219Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QWLHAGGL%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T092514Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGIaCXVzLXdlc3QtMiJHMEUCIHUtb4hzD2CIrNZYUzC%2FckMPOPQyBh95I4sXko1SCt%2BmAiEA3PF%2FNImg%2FxGVu%2FN0RXWZtPF3jUdVzOAykSxLmQMVKsQqiAQIiv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLN9sGbSIb2feKzP9CrcAy7KXPFb8zKTcthZR%2FNHP7Kdm28nDWV0y0nrUn%2BcwMLt2TwJOWIcd%2FsLnnOWdpBEyiY%2BYGIDI77i2RoXnPPz1VtodqPC0DCMGTNPaVxY9HjAMS9jZmYwBqZVDnUlX5ZNOxdsmRf1dXxFVVu0ifLnclVxB9%2FVh9NKgaH3674lKnRHBTDq9dM5zawi934%2B9Jnzm%2FLJGDKIm4%2FCothg8OvJ7AiYaTJ3MWdgitQtFs5bHRXumbxcBTKXdIYlaCz%2BTEg8KZvJPbPL%2BQ051MF4aajEOqsJurdMloksQ2jJnH%2FKzF92%2BOZ71WgMyDvIYFBH5nIJs%2BfeSc90BbMRQ80sxJEyDvatX4s73NB41na471W%2BEMFiDt%2FtsS%2FS1ZF9Ot8G085XF2u1%2Fk2GDzk210IrZNkHr%2BdsPJSxjHrY6gz%2BHGF1sb6l5%2F%2BjOBnmz2HVT7VXgJIVgeg0jAEZzkGSvuHc8hgWoyXwc3dKjgnk1Rfuah8pX6S27MmoGkSxEFneCyq7dnL3MBm0%2BQ72HoJczp6Q98PhwoA0lZmHEIgotnB%2FHePWJTwplVC%2FLyqqYXxSXtkonzn1VgLXg7fSQHx150lAY%2Bl19FkdfRoJ6G6l54F5j1j0TcLyfTFPbU42GEaA026hMPuh0b0GOqUBFD71JROreY5tUwM6k5m7rRu98BYR2NurI%2FxfY6LRH1D7VtMoG2thQDFgSrOm36JRFgSVbQJbFVwIQLC6zsAx45ylGIsNiLEx2GzIX%2Fw3uHrXoJGaTQPI82zU35MsdR7eZalzN3roJgMmzLcSYpHiBsEv9EB6kY2ew7GudWreg%2B00WXqDKqNf4JIzFrKoAH5IAWhxfbkgweGgoJTcoDs%2BSe16XVKx&X-Amz-Signature=897f6f7b070adc9b791b57f56cad7ac0f5b55d540485f794d109f53d4102b7a2&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QWLHAGGL%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T092514Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGIaCXVzLXdlc3QtMiJHMEUCIHUtb4hzD2CIrNZYUzC%2FckMPOPQyBh95I4sXko1SCt%2BmAiEA3PF%2FNImg%2FxGVu%2FN0RXWZtPF3jUdVzOAykSxLmQMVKsQqiAQIiv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLN9sGbSIb2feKzP9CrcAy7KXPFb8zKTcthZR%2FNHP7Kdm28nDWV0y0nrUn%2BcwMLt2TwJOWIcd%2FsLnnOWdpBEyiY%2BYGIDI77i2RoXnPPz1VtodqPC0DCMGTNPaVxY9HjAMS9jZmYwBqZVDnUlX5ZNOxdsmRf1dXxFVVu0ifLnclVxB9%2FVh9NKgaH3674lKnRHBTDq9dM5zawi934%2B9Jnzm%2FLJGDKIm4%2FCothg8OvJ7AiYaTJ3MWdgitQtFs5bHRXumbxcBTKXdIYlaCz%2BTEg8KZvJPbPL%2BQ051MF4aajEOqsJurdMloksQ2jJnH%2FKzF92%2BOZ71WgMyDvIYFBH5nIJs%2BfeSc90BbMRQ80sxJEyDvatX4s73NB41na471W%2BEMFiDt%2FtsS%2FS1ZF9Ot8G085XF2u1%2Fk2GDzk210IrZNkHr%2BdsPJSxjHrY6gz%2BHGF1sb6l5%2F%2BjOBnmz2HVT7VXgJIVgeg0jAEZzkGSvuHc8hgWoyXwc3dKjgnk1Rfuah8pX6S27MmoGkSxEFneCyq7dnL3MBm0%2BQ72HoJczp6Q98PhwoA0lZmHEIgotnB%2FHePWJTwplVC%2FLyqqYXxSXtkonzn1VgLXg7fSQHx150lAY%2Bl19FkdfRoJ6G6l54F5j1j0TcLyfTFPbU42GEaA026hMPuh0b0GOqUBFD71JROreY5tUwM6k5m7rRu98BYR2NurI%2FxfY6LRH1D7VtMoG2thQDFgSrOm36JRFgSVbQJbFVwIQLC6zsAx45ylGIsNiLEx2GzIX%2Fw3uHrXoJGaTQPI82zU35MsdR7eZalzN3roJgMmzLcSYpHiBsEv9EB6kY2ew7GudWreg%2B00WXqDKqNf4JIzFrKoAH5IAWhxfbkgweGgoJTcoDs%2BSe16XVKx&X-Amz-Signature=3a0a1fb46f54918383fab1659e478e2f413500879bf96a36c5bcba1125ac3afb&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QWLHAGGL%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T092514Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGIaCXVzLXdlc3QtMiJHMEUCIHUtb4hzD2CIrNZYUzC%2FckMPOPQyBh95I4sXko1SCt%2BmAiEA3PF%2FNImg%2FxGVu%2FN0RXWZtPF3jUdVzOAykSxLmQMVKsQqiAQIiv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLN9sGbSIb2feKzP9CrcAy7KXPFb8zKTcthZR%2FNHP7Kdm28nDWV0y0nrUn%2BcwMLt2TwJOWIcd%2FsLnnOWdpBEyiY%2BYGIDI77i2RoXnPPz1VtodqPC0DCMGTNPaVxY9HjAMS9jZmYwBqZVDnUlX5ZNOxdsmRf1dXxFVVu0ifLnclVxB9%2FVh9NKgaH3674lKnRHBTDq9dM5zawi934%2B9Jnzm%2FLJGDKIm4%2FCothg8OvJ7AiYaTJ3MWdgitQtFs5bHRXumbxcBTKXdIYlaCz%2BTEg8KZvJPbPL%2BQ051MF4aajEOqsJurdMloksQ2jJnH%2FKzF92%2BOZ71WgMyDvIYFBH5nIJs%2BfeSc90BbMRQ80sxJEyDvatX4s73NB41na471W%2BEMFiDt%2FtsS%2FS1ZF9Ot8G085XF2u1%2Fk2GDzk210IrZNkHr%2BdsPJSxjHrY6gz%2BHGF1sb6l5%2F%2BjOBnmz2HVT7VXgJIVgeg0jAEZzkGSvuHc8hgWoyXwc3dKjgnk1Rfuah8pX6S27MmoGkSxEFneCyq7dnL3MBm0%2BQ72HoJczp6Q98PhwoA0lZmHEIgotnB%2FHePWJTwplVC%2FLyqqYXxSXtkonzn1VgLXg7fSQHx150lAY%2Bl19FkdfRoJ6G6l54F5j1j0TcLyfTFPbU42GEaA026hMPuh0b0GOqUBFD71JROreY5tUwM6k5m7rRu98BYR2NurI%2FxfY6LRH1D7VtMoG2thQDFgSrOm36JRFgSVbQJbFVwIQLC6zsAx45ylGIsNiLEx2GzIX%2Fw3uHrXoJGaTQPI82zU35MsdR7eZalzN3roJgMmzLcSYpHiBsEv9EB6kY2ew7GudWreg%2B00WXqDKqNf4JIzFrKoAH5IAWhxfbkgweGgoJTcoDs%2BSe16XVKx&X-Amz-Signature=e55b1462d11f9f3f29ae5ecfd5a53c3edfa519905149dc5abb6239cdf66626e2&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QWLHAGGL%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T092514Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGIaCXVzLXdlc3QtMiJHMEUCIHUtb4hzD2CIrNZYUzC%2FckMPOPQyBh95I4sXko1SCt%2BmAiEA3PF%2FNImg%2FxGVu%2FN0RXWZtPF3jUdVzOAykSxLmQMVKsQqiAQIiv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLN9sGbSIb2feKzP9CrcAy7KXPFb8zKTcthZR%2FNHP7Kdm28nDWV0y0nrUn%2BcwMLt2TwJOWIcd%2FsLnnOWdpBEyiY%2BYGIDI77i2RoXnPPz1VtodqPC0DCMGTNPaVxY9HjAMS9jZmYwBqZVDnUlX5ZNOxdsmRf1dXxFVVu0ifLnclVxB9%2FVh9NKgaH3674lKnRHBTDq9dM5zawi934%2B9Jnzm%2FLJGDKIm4%2FCothg8OvJ7AiYaTJ3MWdgitQtFs5bHRXumbxcBTKXdIYlaCz%2BTEg8KZvJPbPL%2BQ051MF4aajEOqsJurdMloksQ2jJnH%2FKzF92%2BOZ71WgMyDvIYFBH5nIJs%2BfeSc90BbMRQ80sxJEyDvatX4s73NB41na471W%2BEMFiDt%2FtsS%2FS1ZF9Ot8G085XF2u1%2Fk2GDzk210IrZNkHr%2BdsPJSxjHrY6gz%2BHGF1sb6l5%2F%2BjOBnmz2HVT7VXgJIVgeg0jAEZzkGSvuHc8hgWoyXwc3dKjgnk1Rfuah8pX6S27MmoGkSxEFneCyq7dnL3MBm0%2BQ72HoJczp6Q98PhwoA0lZmHEIgotnB%2FHePWJTwplVC%2FLyqqYXxSXtkonzn1VgLXg7fSQHx150lAY%2Bl19FkdfRoJ6G6l54F5j1j0TcLyfTFPbU42GEaA026hMPuh0b0GOqUBFD71JROreY5tUwM6k5m7rRu98BYR2NurI%2FxfY6LRH1D7VtMoG2thQDFgSrOm36JRFgSVbQJbFVwIQLC6zsAx45ylGIsNiLEx2GzIX%2Fw3uHrXoJGaTQPI82zU35MsdR7eZalzN3roJgMmzLcSYpHiBsEv9EB6kY2ew7GudWreg%2B00WXqDKqNf4JIzFrKoAH5IAWhxfbkgweGgoJTcoDs%2BSe16XVKx&X-Amz-Signature=64809a9bc382500ee9fbf67a84226a3d0fbd3dd8e9ff83386a572d71ccfcbc85&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QWLHAGGL%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T092514Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGIaCXVzLXdlc3QtMiJHMEUCIHUtb4hzD2CIrNZYUzC%2FckMPOPQyBh95I4sXko1SCt%2BmAiEA3PF%2FNImg%2FxGVu%2FN0RXWZtPF3jUdVzOAykSxLmQMVKsQqiAQIiv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLN9sGbSIb2feKzP9CrcAy7KXPFb8zKTcthZR%2FNHP7Kdm28nDWV0y0nrUn%2BcwMLt2TwJOWIcd%2FsLnnOWdpBEyiY%2BYGIDI77i2RoXnPPz1VtodqPC0DCMGTNPaVxY9HjAMS9jZmYwBqZVDnUlX5ZNOxdsmRf1dXxFVVu0ifLnclVxB9%2FVh9NKgaH3674lKnRHBTDq9dM5zawi934%2B9Jnzm%2FLJGDKIm4%2FCothg8OvJ7AiYaTJ3MWdgitQtFs5bHRXumbxcBTKXdIYlaCz%2BTEg8KZvJPbPL%2BQ051MF4aajEOqsJurdMloksQ2jJnH%2FKzF92%2BOZ71WgMyDvIYFBH5nIJs%2BfeSc90BbMRQ80sxJEyDvatX4s73NB41na471W%2BEMFiDt%2FtsS%2FS1ZF9Ot8G085XF2u1%2Fk2GDzk210IrZNkHr%2BdsPJSxjHrY6gz%2BHGF1sb6l5%2F%2BjOBnmz2HVT7VXgJIVgeg0jAEZzkGSvuHc8hgWoyXwc3dKjgnk1Rfuah8pX6S27MmoGkSxEFneCyq7dnL3MBm0%2BQ72HoJczp6Q98PhwoA0lZmHEIgotnB%2FHePWJTwplVC%2FLyqqYXxSXtkonzn1VgLXg7fSQHx150lAY%2Bl19FkdfRoJ6G6l54F5j1j0TcLyfTFPbU42GEaA026hMPuh0b0GOqUBFD71JROreY5tUwM6k5m7rRu98BYR2NurI%2FxfY6LRH1D7VtMoG2thQDFgSrOm36JRFgSVbQJbFVwIQLC6zsAx45ylGIsNiLEx2GzIX%2Fw3uHrXoJGaTQPI82zU35MsdR7eZalzN3roJgMmzLcSYpHiBsEv9EB6kY2ew7GudWreg%2B00WXqDKqNf4JIzFrKoAH5IAWhxfbkgweGgoJTcoDs%2BSe16XVKx&X-Amz-Signature=80ad9ea5dd13e70b8dc83892c3981bad48a9282c9067e27c2cd916d1a781a1b3&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665WFCE4GG%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T092516Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGIaCXVzLXdlc3QtMiJIMEYCIQD3Zaj5AuVjnySwGZVMfjAJcu%2F%2BjTYPZHxbPKESyB5MkQIhALmC2G6T5Wtdzx1UKfJkMNczcsjlQ6rwpbmQnVA27u6%2FKogECIr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxOorp8nwd0k32lrswq3AM9Otdb0vMgryftlmbxfo%2BcS3%2FieeMKCczCkeqejpJe%2BbsGMYEPtLEWEDQToXlSeRMTZFkIBN9J96c4unpuYJp1a7BThd5xuQH5mvGPYk6J%2Bx2%2BOpoK1%2FtzIWXmU4j6yBGiJ4L7fDQoUEMNL1o60H61gRp3SNNObhYZfzMCiir%2FJUTQbqp8wpicTPmCamxWs89XroB91WOdb6ivQ3bb0BMxsdf9uUQmIfRlQyNVgKFx01UcxhqpxyOMBP1tROdFpKOjF8EtjDMssOpC0MpWT1ruy%2Fwo71Exeb9mwz35nzERnytLspxC0z%2B1lukW8MeHuHfidKGT7I7o13UK%2BpHEpqBpqokv5H7I8VQrLLLY2JvviSQIMgoucKJYrvupoZjxcFdZCSm8NyN6%2Fgs6%2FROq1AYMrPJMcaFABZrgJLAoOG2HeOkly%2BNpMbPUz2b7MoEnxebaGykNecVhKC3H1eR82SlA2MRjMSj6RX7sQ3%2F3wVMOzwuziT2z6DPxzuHkw2DAulxG5xUec53NQBZ%2F1Nx5pYitiPyQU6Dpeo4Ko%2F2WR21jHkvqPTDTmDnqKQo9tk6pt10WYi7x%2Fzru3Ses1D1hWbSXu6Vml%2BHqmIJXXJPQUj5xeFHJfRe80RYwDIKt%2FDCOotG9BjqkAW4%2FjHiOngFtGvp0EcvV%2FHYwvH7cw0noiMvYACrjbtosan%2BLXeNnJmh2o%2F0PZSqk62ch55uJ3l0nTAFLYDM1HPBNrisrj7%2Bwhfm3yMs35%2FptBVd00dQrTZ8qjmcyMnKnMC1VKuhh5teg63LKI16uyF4171nZ6db2W%2Bb3nyJWt2m%2BxsluoRPtKdJqufCV%2BBz8anVoWB4w%2BWVvwZjzOIoW2sUki0wx&X-Amz-Signature=6c2cd7eb8828eb934ef0e9c0db51a4ccca2c14ecfc0fdd0b868be4cf9cc9dfd0&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666GSCCKP6%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T092518Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGIaCXVzLXdlc3QtMiJGMEQCICcjC6i0b92f%2B%2BmEd%2FLv9J%2BsOm%2FWCfE8whZWbcQyEmu5AiBgEVpFPwSHutHDrBU6BsiioqfQ0JU%2BIjQKuzOvJ8Na9CqIBAiK%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMl5nj3T2eJUCR02pyKtwDAkaR07ilOhrWhhdczY7%2FtjCe6ue2yHYp3613VRHXy48L41kX9cqodjHLuebDOe7kxkFLyoe%2BQbTLKoYZDzFmJJuai461hczptJ8y2TzWODxGUHMdgfjAK%2BSfxvkS%2Bh5HDcEiD%2FtXzBA2Xi5%2B%2F4jWoIOM7fv4Z0jQgcrA%2BDd9iX5mcIzuz897ysto3TAodHp4qJqg96l6EWfL%2FSyvJUNdEyq%2FcnDJP12c66pyug9t32bDyp1ia1CfOktNL9FvBop4ozyy3wu5Yxw1ocOoyVUFUGC672WK4uxap9E8RQcjKKLtvnxl5miyjM%2FLqQw9it2CeLSi95H%2BE9zn%2Fcy9JcTtgRJDtZgs4xvwhm7ntii1gARw7pQzG%2FhEj%2FvDTOGJIQnxfEPBHIiwtNr%2BhlwYhkDJpN6fmuMhvRHq2UxkHs%2FXKxz0a0TFWnlR%2FbIVOp7OdJq4u0DDkt7LXMPDMEnW01%2BjKo7ZtTtojtrDtTyyrdycWfskZY0d1BaqW1dSE%2BnwcXCpiwqe3PvX0irS8zwIsQPV5kuZc4RQQ2UsQ25ZWgh624h82YPdpot1PfxN1kz6Dnea%2Bu2xaYDbKGBvfRJLhQrQbwB6fjaZa9dOIR8JomZxT1HFbWfHeOlrS8gEKXcw%2BKHRvQY6pgGwKouvpQb7V8CrZDRiJfIBxyaMNHinXTUudYxfYwmam8BdIzwS0UlG9KQE4DBQnvviIiGRWLGK4VmEBsq67FsiVH%2FOCFd0QP%2BBSEcw9z%2FL8drLoIOBYNwyTlrZeCVRY0%2B07LMngFN5c5B4HTWRrRNMRp%2B1bbw1ewbWa%2BQXfUanIMYP3rVDwxqDOpgThWQj6MS7nmKR3FPqYUHHcTY1cpQq4MRu23tn&X-Amz-Signature=6386ad2eaa4673268143dc96a3af08e4d0e6884deb3584960f3396b37a48a5ea&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QWLHAGGL%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T092514Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGIaCXVzLXdlc3QtMiJHMEUCIHUtb4hzD2CIrNZYUzC%2FckMPOPQyBh95I4sXko1SCt%2BmAiEA3PF%2FNImg%2FxGVu%2FN0RXWZtPF3jUdVzOAykSxLmQMVKsQqiAQIiv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLN9sGbSIb2feKzP9CrcAy7KXPFb8zKTcthZR%2FNHP7Kdm28nDWV0y0nrUn%2BcwMLt2TwJOWIcd%2FsLnnOWdpBEyiY%2BYGIDI77i2RoXnPPz1VtodqPC0DCMGTNPaVxY9HjAMS9jZmYwBqZVDnUlX5ZNOxdsmRf1dXxFVVu0ifLnclVxB9%2FVh9NKgaH3674lKnRHBTDq9dM5zawi934%2B9Jnzm%2FLJGDKIm4%2FCothg8OvJ7AiYaTJ3MWdgitQtFs5bHRXumbxcBTKXdIYlaCz%2BTEg8KZvJPbPL%2BQ051MF4aajEOqsJurdMloksQ2jJnH%2FKzF92%2BOZ71WgMyDvIYFBH5nIJs%2BfeSc90BbMRQ80sxJEyDvatX4s73NB41na471W%2BEMFiDt%2FtsS%2FS1ZF9Ot8G085XF2u1%2Fk2GDzk210IrZNkHr%2BdsPJSxjHrY6gz%2BHGF1sb6l5%2F%2BjOBnmz2HVT7VXgJIVgeg0jAEZzkGSvuHc8hgWoyXwc3dKjgnk1Rfuah8pX6S27MmoGkSxEFneCyq7dnL3MBm0%2BQ72HoJczp6Q98PhwoA0lZmHEIgotnB%2FHePWJTwplVC%2FLyqqYXxSXtkonzn1VgLXg7fSQHx150lAY%2Bl19FkdfRoJ6G6l54F5j1j0TcLyfTFPbU42GEaA026hMPuh0b0GOqUBFD71JROreY5tUwM6k5m7rRu98BYR2NurI%2FxfY6LRH1D7VtMoG2thQDFgSrOm36JRFgSVbQJbFVwIQLC6zsAx45ylGIsNiLEx2GzIX%2Fw3uHrXoJGaTQPI82zU35MsdR7eZalzN3roJgMmzLcSYpHiBsEv9EB6kY2ew7GudWreg%2B00WXqDKqNf4JIzFrKoAH5IAWhxfbkgweGgoJTcoDs%2BSe16XVKx&X-Amz-Signature=1fd5016d3225538dafcc6a0cdd62316a6f9e1e4858169474f86c4ec738535f97&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QWLHAGGL%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T092514Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGIaCXVzLXdlc3QtMiJHMEUCIHUtb4hzD2CIrNZYUzC%2FckMPOPQyBh95I4sXko1SCt%2BmAiEA3PF%2FNImg%2FxGVu%2FN0RXWZtPF3jUdVzOAykSxLmQMVKsQqiAQIiv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLN9sGbSIb2feKzP9CrcAy7KXPFb8zKTcthZR%2FNHP7Kdm28nDWV0y0nrUn%2BcwMLt2TwJOWIcd%2FsLnnOWdpBEyiY%2BYGIDI77i2RoXnPPz1VtodqPC0DCMGTNPaVxY9HjAMS9jZmYwBqZVDnUlX5ZNOxdsmRf1dXxFVVu0ifLnclVxB9%2FVh9NKgaH3674lKnRHBTDq9dM5zawi934%2B9Jnzm%2FLJGDKIm4%2FCothg8OvJ7AiYaTJ3MWdgitQtFs5bHRXumbxcBTKXdIYlaCz%2BTEg8KZvJPbPL%2BQ051MF4aajEOqsJurdMloksQ2jJnH%2FKzF92%2BOZ71WgMyDvIYFBH5nIJs%2BfeSc90BbMRQ80sxJEyDvatX4s73NB41na471W%2BEMFiDt%2FtsS%2FS1ZF9Ot8G085XF2u1%2Fk2GDzk210IrZNkHr%2BdsPJSxjHrY6gz%2BHGF1sb6l5%2F%2BjOBnmz2HVT7VXgJIVgeg0jAEZzkGSvuHc8hgWoyXwc3dKjgnk1Rfuah8pX6S27MmoGkSxEFneCyq7dnL3MBm0%2BQ72HoJczp6Q98PhwoA0lZmHEIgotnB%2FHePWJTwplVC%2FLyqqYXxSXtkonzn1VgLXg7fSQHx150lAY%2Bl19FkdfRoJ6G6l54F5j1j0TcLyfTFPbU42GEaA026hMPuh0b0GOqUBFD71JROreY5tUwM6k5m7rRu98BYR2NurI%2FxfY6LRH1D7VtMoG2thQDFgSrOm36JRFgSVbQJbFVwIQLC6zsAx45ylGIsNiLEx2GzIX%2Fw3uHrXoJGaTQPI82zU35MsdR7eZalzN3roJgMmzLcSYpHiBsEv9EB6kY2ew7GudWreg%2B00WXqDKqNf4JIzFrKoAH5IAWhxfbkgweGgoJTcoDs%2BSe16XVKx&X-Amz-Signature=4d9671180d93eef7524ccedb23b577aa754b170597371d046b6b71de0dcb854b&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QWLHAGGL%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T092514Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGIaCXVzLXdlc3QtMiJHMEUCIHUtb4hzD2CIrNZYUzC%2FckMPOPQyBh95I4sXko1SCt%2BmAiEA3PF%2FNImg%2FxGVu%2FN0RXWZtPF3jUdVzOAykSxLmQMVKsQqiAQIiv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLN9sGbSIb2feKzP9CrcAy7KXPFb8zKTcthZR%2FNHP7Kdm28nDWV0y0nrUn%2BcwMLt2TwJOWIcd%2FsLnnOWdpBEyiY%2BYGIDI77i2RoXnPPz1VtodqPC0DCMGTNPaVxY9HjAMS9jZmYwBqZVDnUlX5ZNOxdsmRf1dXxFVVu0ifLnclVxB9%2FVh9NKgaH3674lKnRHBTDq9dM5zawi934%2B9Jnzm%2FLJGDKIm4%2FCothg8OvJ7AiYaTJ3MWdgitQtFs5bHRXumbxcBTKXdIYlaCz%2BTEg8KZvJPbPL%2BQ051MF4aajEOqsJurdMloksQ2jJnH%2FKzF92%2BOZ71WgMyDvIYFBH5nIJs%2BfeSc90BbMRQ80sxJEyDvatX4s73NB41na471W%2BEMFiDt%2FtsS%2FS1ZF9Ot8G085XF2u1%2Fk2GDzk210IrZNkHr%2BdsPJSxjHrY6gz%2BHGF1sb6l5%2F%2BjOBnmz2HVT7VXgJIVgeg0jAEZzkGSvuHc8hgWoyXwc3dKjgnk1Rfuah8pX6S27MmoGkSxEFneCyq7dnL3MBm0%2BQ72HoJczp6Q98PhwoA0lZmHEIgotnB%2FHePWJTwplVC%2FLyqqYXxSXtkonzn1VgLXg7fSQHx150lAY%2Bl19FkdfRoJ6G6l54F5j1j0TcLyfTFPbU42GEaA026hMPuh0b0GOqUBFD71JROreY5tUwM6k5m7rRu98BYR2NurI%2FxfY6LRH1D7VtMoG2thQDFgSrOm36JRFgSVbQJbFVwIQLC6zsAx45ylGIsNiLEx2GzIX%2Fw3uHrXoJGaTQPI82zU35MsdR7eZalzN3roJgMmzLcSYpHiBsEv9EB6kY2ew7GudWreg%2B00WXqDKqNf4JIzFrKoAH5IAWhxfbkgweGgoJTcoDs%2BSe16XVKx&X-Amz-Signature=8b0c521cb119bce4b2c8eca338543ad786ed919d83a16ba80e5ca14d4ccdb398&X-Amz-SignedHeaders=host&x-id=GetObject)


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

