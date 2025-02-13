---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4665HOZX2SS%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250213T163102Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEPD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDNHG5xdf%2B5z37sJ\
  vfRcQepbhEdTPzn6ourgXqR1dHozQIhAIRHP0RDKiI%2F5BKiAJ8XQc7YUCK5ks3gNLPU5rUHMnBN\
  Kv8DCBkQABoMNjM3NDIzMTgzODA1IgzVKGO5v8EG%2BVppNyoq3ANlsp498oVLwMe%2FZCsa6LwJ3\
  ZsXODzDyTtZn2Gydt74m1PvycnfwWz1w40hD%2B8jc%2Fx6LWkSvM8e%2FGPdTt8SOcSZQ66NjKz5\
  YSB2LPaMOMUvFr8LpwVP1wUqZTwSmfWH7Nj1RpyfhNgbvyY6eLAkloqJHx6n1Xb0IelChgmVPRIYA\
  Lowr9AKT3nqXeFncwxCkMHHWAMRRQj%2BGCeOofUNpCrLnsifii%2ForwtYStH5avzFXQ9ha%2Bcq\
  rSSO3jso5L%2BUbi3jdOoDVyRpWoPmRIafH4JAhptv%2FOd9ibFHzElg2vw8W4FDzJrB%2BjIHT%2\
  B41uz4H%2FhwaGd6Nr2nQFGXqwm4pu9NsO3wdTHXa0lF6CWvUySNf9yw7pnHJ0yYZIlScTfEvpdAW\
  UBEl8QltuuIFFnMhd355QFKitRjhSIAnrngCjEo7WQRSeBdNiyz%2Btxz%2BXMcm02guGLm%2FFHf\
  GoVYoKjtLizLrG0Q1aGF5d1zkgMpsvy8YWq99qYH7cBXhUkJM4wy8mFOMfYoHdxvXa%2F%2FkwdxP\
  XHa783p6Sk6kfYWBlBRhas%2FHTrI%2B8OKLYcPPhKQ%2FdUysav%2FQ3r9uKRE%2Fb1wYj12wH%2\
  FSJo4DuBn%2FDa29Q2ksSrCCUygwRPnAxjLUglppTizDer7i9BjqkAYrWiKM%2B1KQLGsnLmcMfh9\
  EQMyBOWK5VRCyDtTVrdN7MZlwu9LJzpopBjmmtr2GBNbrVx%2BE%2FzdEeJ%2BehEgefYvUHDzmXV\
  gz11XE0VAimP6VxtL5InAgVVnxbOkPw%2B6RFz7P%2Bjo1opXfuaMolVt6vASU%2FgUhE3hPZ120%\
  2BX1QPkPhuOib68N8yJFaIer7sB7ICI1xt91MYIsGe6vACHnVwVef541SZ&X-Amz-Signature=75\
  056eba574a79fa3f929c1820f1dd79da7560187e8714b140b0ab1d1510c658&X-Amz-SignedHe\
  aders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4662Z4QQQL5%2F20250213%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250213T162921Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEPD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIQCRxVTaPpItxKyynsUmwraXR0w418g%2BL7nI7itPWBzkqQIgPQSI9DW9oxovMaJ4Pem2\
        RgZfxRBOGZo%2FFwIjmc79lrcq%2FwMIGBAAGgw2Mzc0MjMxODM4MDUiDOEn4vdXtGfX8o5\
        yKCrcA4hLx07xWIjAuMKPkxxBIHvAudClxryxaJFsBPTEaQ2DZJRDyHjScCv47XAzSg8f0M\
        FIkUasuCQmqSu7zEbzmUYCiM%2FLolbDwNwN7LTz7dR0C40fn76IXrtLQWUcboP4llJzmFN\
        b4F8m%2BG%2BzQzkskhIeAbATNxLwBHBF9FadR3UR5PW9AXNH0s9n30XH4QT6BmuwPfj8tM\
        KskAwS9WzkH5yGKSZQwkDTt2wHIZrpzGb063U%2BxcWTpZ3yFHhjB2vEjqUC1g9F1zOdMMe\
        29ahcJI27zwnm3V2mPCqS%2FqeBpio5CJxexUIb5aMJ6hsnasVm%2BR4Yj1UQexfhW%2BHs\
        D7PHjkpN92FSIv4%2F7SUZ%2BZG9vJQ9tEBYBQGx3%2BMa8eTR3NPicJ3c0LPzSiqG0%2Fg\
        LyuO6Rgg%2F3M9FT1ehr10FfA35I0wsFfPfoVcbW5n4n007ZkNJio%2BuNfFf2jFJP6bf7Q\
        ZifeJO4xMR4aN5w9wycobsP9oFz3Ho3hgssYa%2FJvaSatox8UWkN1wHJSCvdyDO2jDeCTW\
        U03qjxr%2F%2FXuIDmpa6Cb6dyB7mkqTeWbJPxWSBBDNqh8JD65v%2Bz3ehm1V%2FThKbw0\
        FG6f2yRs%2BZJWMxUETqBURTQiv26MDA4GtTi1f0MISfuL0GOqUBurxXVE1U766Tp1Qk3fZ\
        iGIZZq2A%2FMaN%2BjIDboVDoLB3vZERJ7tOXDlzpwEf0aYiZ5h%2BG3LqYjVfYQWS2EOxZ\
        wMpQteoKUbxf2QlNw0oieAgeDmVugI09jR3TsyRiZp7LpoDPdcROEckESBcjx1tMreYZHTH\
        UJiLhnHTeJUL3xNaDpupE9SjkXtI5s0D6Qm1AWoBRm7QeZLAaJcioFwsqSlysYagr&X-Amz\
        -Signature=03f56b2de28cfb18a956cbc120a4de730016696144b34207b4a32298a0d6\
        da47&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-13T17:29:21.321Z"
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
UPDATE_TIME: "2025-02-13T16:31:08.551Z"
EXPIRY_TIME: "2025-02-13T17:30:58.863Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663KIM35WP%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T163059Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIBZE4GNjzWo8nOUkBPWoPYsg4P18gbscitOi2mV%2Bn3PgAiBQ4t2pOFjjJzAcukC9tDrrAPkjGidd4OdiiX%2F7zxO11Cr%2FAwgZEAAaDDYzNzQyMzE4MzgwNSIM8x%2B7d6cO3%2FIiF%2FKUKtwDknbChNBIuB5F1%2F7lEeT2SzSHFI13xvcQCVBQZD58A8IIvSXxxzgV1ooQ8j0%2BaJqqDcDAPbIRj7N%2BMAJ2JLlhca2yPGibM8N2WiW7wa5xKisWhjxbCb51nKu1fh1V8rvCqls%2B%2FJaxNRP0FuKEDfztxhrZnKgkulgHH4ai5%2FyuKoi42zQETK9Q7U2Igg79faofOJLHQTvo3no9S9jr6xpV7jurDujLUwFSSZ9IxkI7FvPDEW3WzdcpSkYT0GEPuQengyeNFCuCNyucfxqxEC%2F5oAUFjj3pSgrgGzlt5X1%2FoSv0BD9XdGfkkkhY%2FgYHDM%2BeRdpoUzvOPJAcHdIriZTi%2B0vpYEHhVhBAEAChHPOD6R0tYDrvXMhHmPgu0ZLueo30bzUokPLcJcDAk6QCZv88ObH3a36Wp9yQAiVbqLTwl4Ik%2FNa14YN6uTrpfaYEJIB%2B5I87f3NifLUZSfcyNdRnsFmxVf4ZEoITQIIRYWTh8d0XpCvsJPdIoI7U4DziBNpMTKee0cSa2qR0LWykHK71%2FezVYczalZ8u8tXW6JE9VYWzaTqBUEhGsckrfO607mnTYJC5EleZEWPMhiFY74ZCn29%2Bl49gxfzWT848aGQYeDz0akNFtne0tB3Zxnkw3564vQY6pgHi%2Fx7wItH%2B%2B5odC45ZTTtgPsIbcyWZr%2BvltHMhZdg6383P3wUs1NA%2FogV1zzWfRHAF%2FebWBCZMURlFkWWgnmjt5R6iBm6W5WbvtYOx%2BwyJJBttlXCpXvU2ztwJXtHdxeg9gfPP2MYzWV0CfJBw4UM4f474IZfA6zxnEmlYOyYVhI4hpIJzbpTYpjZGYNxBM4chd9JGxXRUh5oxLirTCflVioW%2Fxz3N&X-Amz-Signature=6a0b3bd6f833fe879580816f38d66ba40fc6774ac74949e662be26ae64c5c543&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663KIM35WP%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T163059Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIBZE4GNjzWo8nOUkBPWoPYsg4P18gbscitOi2mV%2Bn3PgAiBQ4t2pOFjjJzAcukC9tDrrAPkjGidd4OdiiX%2F7zxO11Cr%2FAwgZEAAaDDYzNzQyMzE4MzgwNSIM8x%2B7d6cO3%2FIiF%2FKUKtwDknbChNBIuB5F1%2F7lEeT2SzSHFI13xvcQCVBQZD58A8IIvSXxxzgV1ooQ8j0%2BaJqqDcDAPbIRj7N%2BMAJ2JLlhca2yPGibM8N2WiW7wa5xKisWhjxbCb51nKu1fh1V8rvCqls%2B%2FJaxNRP0FuKEDfztxhrZnKgkulgHH4ai5%2FyuKoi42zQETK9Q7U2Igg79faofOJLHQTvo3no9S9jr6xpV7jurDujLUwFSSZ9IxkI7FvPDEW3WzdcpSkYT0GEPuQengyeNFCuCNyucfxqxEC%2F5oAUFjj3pSgrgGzlt5X1%2FoSv0BD9XdGfkkkhY%2FgYHDM%2BeRdpoUzvOPJAcHdIriZTi%2B0vpYEHhVhBAEAChHPOD6R0tYDrvXMhHmPgu0ZLueo30bzUokPLcJcDAk6QCZv88ObH3a36Wp9yQAiVbqLTwl4Ik%2FNa14YN6uTrpfaYEJIB%2B5I87f3NifLUZSfcyNdRnsFmxVf4ZEoITQIIRYWTh8d0XpCvsJPdIoI7U4DziBNpMTKee0cSa2qR0LWykHK71%2FezVYczalZ8u8tXW6JE9VYWzaTqBUEhGsckrfO607mnTYJC5EleZEWPMhiFY74ZCn29%2Bl49gxfzWT848aGQYeDz0akNFtne0tB3Zxnkw3564vQY6pgHi%2Fx7wItH%2B%2B5odC45ZTTtgPsIbcyWZr%2BvltHMhZdg6383P3wUs1NA%2FogV1zzWfRHAF%2FebWBCZMURlFkWWgnmjt5R6iBm6W5WbvtYOx%2BwyJJBttlXCpXvU2ztwJXtHdxeg9gfPP2MYzWV0CfJBw4UM4f474IZfA6zxnEmlYOyYVhI4hpIJzbpTYpjZGYNxBM4chd9JGxXRUh5oxLirTCflVioW%2Fxz3N&X-Amz-Signature=16dff670faf78fc67e4532f740eb184bf637fa73042fef63fdaab106a9d3a2fc&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663KIM35WP%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T163059Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIBZE4GNjzWo8nOUkBPWoPYsg4P18gbscitOi2mV%2Bn3PgAiBQ4t2pOFjjJzAcukC9tDrrAPkjGidd4OdiiX%2F7zxO11Cr%2FAwgZEAAaDDYzNzQyMzE4MzgwNSIM8x%2B7d6cO3%2FIiF%2FKUKtwDknbChNBIuB5F1%2F7lEeT2SzSHFI13xvcQCVBQZD58A8IIvSXxxzgV1ooQ8j0%2BaJqqDcDAPbIRj7N%2BMAJ2JLlhca2yPGibM8N2WiW7wa5xKisWhjxbCb51nKu1fh1V8rvCqls%2B%2FJaxNRP0FuKEDfztxhrZnKgkulgHH4ai5%2FyuKoi42zQETK9Q7U2Igg79faofOJLHQTvo3no9S9jr6xpV7jurDujLUwFSSZ9IxkI7FvPDEW3WzdcpSkYT0GEPuQengyeNFCuCNyucfxqxEC%2F5oAUFjj3pSgrgGzlt5X1%2FoSv0BD9XdGfkkkhY%2FgYHDM%2BeRdpoUzvOPJAcHdIriZTi%2B0vpYEHhVhBAEAChHPOD6R0tYDrvXMhHmPgu0ZLueo30bzUokPLcJcDAk6QCZv88ObH3a36Wp9yQAiVbqLTwl4Ik%2FNa14YN6uTrpfaYEJIB%2B5I87f3NifLUZSfcyNdRnsFmxVf4ZEoITQIIRYWTh8d0XpCvsJPdIoI7U4DziBNpMTKee0cSa2qR0LWykHK71%2FezVYczalZ8u8tXW6JE9VYWzaTqBUEhGsckrfO607mnTYJC5EleZEWPMhiFY74ZCn29%2Bl49gxfzWT848aGQYeDz0akNFtne0tB3Zxnkw3564vQY6pgHi%2Fx7wItH%2B%2B5odC45ZTTtgPsIbcyWZr%2BvltHMhZdg6383P3wUs1NA%2FogV1zzWfRHAF%2FebWBCZMURlFkWWgnmjt5R6iBm6W5WbvtYOx%2BwyJJBttlXCpXvU2ztwJXtHdxeg9gfPP2MYzWV0CfJBw4UM4f474IZfA6zxnEmlYOyYVhI4hpIJzbpTYpjZGYNxBM4chd9JGxXRUh5oxLirTCflVioW%2Fxz3N&X-Amz-Signature=447544506e6cc59da85cd20685b45abb676115dcc52a47dc2bc5579357fa98a6&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663KIM35WP%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T163059Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIBZE4GNjzWo8nOUkBPWoPYsg4P18gbscitOi2mV%2Bn3PgAiBQ4t2pOFjjJzAcukC9tDrrAPkjGidd4OdiiX%2F7zxO11Cr%2FAwgZEAAaDDYzNzQyMzE4MzgwNSIM8x%2B7d6cO3%2FIiF%2FKUKtwDknbChNBIuB5F1%2F7lEeT2SzSHFI13xvcQCVBQZD58A8IIvSXxxzgV1ooQ8j0%2BaJqqDcDAPbIRj7N%2BMAJ2JLlhca2yPGibM8N2WiW7wa5xKisWhjxbCb51nKu1fh1V8rvCqls%2B%2FJaxNRP0FuKEDfztxhrZnKgkulgHH4ai5%2FyuKoi42zQETK9Q7U2Igg79faofOJLHQTvo3no9S9jr6xpV7jurDujLUwFSSZ9IxkI7FvPDEW3WzdcpSkYT0GEPuQengyeNFCuCNyucfxqxEC%2F5oAUFjj3pSgrgGzlt5X1%2FoSv0BD9XdGfkkkhY%2FgYHDM%2BeRdpoUzvOPJAcHdIriZTi%2B0vpYEHhVhBAEAChHPOD6R0tYDrvXMhHmPgu0ZLueo30bzUokPLcJcDAk6QCZv88ObH3a36Wp9yQAiVbqLTwl4Ik%2FNa14YN6uTrpfaYEJIB%2B5I87f3NifLUZSfcyNdRnsFmxVf4ZEoITQIIRYWTh8d0XpCvsJPdIoI7U4DziBNpMTKee0cSa2qR0LWykHK71%2FezVYczalZ8u8tXW6JE9VYWzaTqBUEhGsckrfO607mnTYJC5EleZEWPMhiFY74ZCn29%2Bl49gxfzWT848aGQYeDz0akNFtne0tB3Zxnkw3564vQY6pgHi%2Fx7wItH%2B%2B5odC45ZTTtgPsIbcyWZr%2BvltHMhZdg6383P3wUs1NA%2FogV1zzWfRHAF%2FebWBCZMURlFkWWgnmjt5R6iBm6W5WbvtYOx%2BwyJJBttlXCpXvU2ztwJXtHdxeg9gfPP2MYzWV0CfJBw4UM4f474IZfA6zxnEmlYOyYVhI4hpIJzbpTYpjZGYNxBM4chd9JGxXRUh5oxLirTCflVioW%2Fxz3N&X-Amz-Signature=1696ab4ce1e8b7190a6148f5ba5cdf04f03c74e835e5537954f2d434b58ea19a&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663KIM35WP%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T163059Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIBZE4GNjzWo8nOUkBPWoPYsg4P18gbscitOi2mV%2Bn3PgAiBQ4t2pOFjjJzAcukC9tDrrAPkjGidd4OdiiX%2F7zxO11Cr%2FAwgZEAAaDDYzNzQyMzE4MzgwNSIM8x%2B7d6cO3%2FIiF%2FKUKtwDknbChNBIuB5F1%2F7lEeT2SzSHFI13xvcQCVBQZD58A8IIvSXxxzgV1ooQ8j0%2BaJqqDcDAPbIRj7N%2BMAJ2JLlhca2yPGibM8N2WiW7wa5xKisWhjxbCb51nKu1fh1V8rvCqls%2B%2FJaxNRP0FuKEDfztxhrZnKgkulgHH4ai5%2FyuKoi42zQETK9Q7U2Igg79faofOJLHQTvo3no9S9jr6xpV7jurDujLUwFSSZ9IxkI7FvPDEW3WzdcpSkYT0GEPuQengyeNFCuCNyucfxqxEC%2F5oAUFjj3pSgrgGzlt5X1%2FoSv0BD9XdGfkkkhY%2FgYHDM%2BeRdpoUzvOPJAcHdIriZTi%2B0vpYEHhVhBAEAChHPOD6R0tYDrvXMhHmPgu0ZLueo30bzUokPLcJcDAk6QCZv88ObH3a36Wp9yQAiVbqLTwl4Ik%2FNa14YN6uTrpfaYEJIB%2B5I87f3NifLUZSfcyNdRnsFmxVf4ZEoITQIIRYWTh8d0XpCvsJPdIoI7U4DziBNpMTKee0cSa2qR0LWykHK71%2FezVYczalZ8u8tXW6JE9VYWzaTqBUEhGsckrfO607mnTYJC5EleZEWPMhiFY74ZCn29%2Bl49gxfzWT848aGQYeDz0akNFtne0tB3Zxnkw3564vQY6pgHi%2Fx7wItH%2B%2B5odC45ZTTtgPsIbcyWZr%2BvltHMhZdg6383P3wUs1NA%2FogV1zzWfRHAF%2FebWBCZMURlFkWWgnmjt5R6iBm6W5WbvtYOx%2BwyJJBttlXCpXvU2ztwJXtHdxeg9gfPP2MYzWV0CfJBw4UM4f474IZfA6zxnEmlYOyYVhI4hpIJzbpTYpjZGYNxBM4chd9JGxXRUh5oxLirTCflVioW%2Fxz3N&X-Amz-Signature=c55b5d72b8bc7a86f76754a98093202addaf627412947db12e97e51224da7b42&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YLYY27DE%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T163100Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIFkeFziiYGU13XwIh44T1xv7vnyuASCkipxyAlYZ%2FqIqAiAw7IKV%2BGXt0rAkSHOBmJTjGceJKMDqsJq4KzPtIV9SSir%2FAwgZEAAaDDYzNzQyMzE4MzgwNSIMpNvgU49J30u6CY1HKtwDjJuQC66bdocSjiQmY4aTD1aQOEBe4CZkI3Vqzym%2BOn83BEAtJEAvgjxFg8T4Ce%2FrnCkzkdi3bxQWz3PPsAughVIOwh6WiLtYKK%2F9KHgln6Ocy%2Fbw5uXONCYjNx548yg%2F9v5UNB1itherYK7tuZ11YfqLWuLaJ4DyZsOSRK0IrzYb46XykBS3TISrDnUUD%2F%2F1tziijKbwJrYIerpL3KOIwgMZHz4dh1rzbDSUsTp1HlmLM%2Bc%2FQ2UwMIwOFzIu9J61htJ5ToC9nfJJaberecv55ZR6xrqwcUMGEHCCmTSF9MsxYzYFtWVie7%2BhLO3io2F5yEc2y49fx60uxBj15DiBGx%2BEYgnGoM0saxodxAw0Fj8ChPu2EGg7H8SKTCbhMyrcnHTTk6zCCgglDhBo75SSlJgXCVj%2Bjt1wsFg1ruYFwz9aMnf9wMUuWTyjtcIgXIG7W%2FOX%2Be6z%2Flg%2BJUJ%2F4W9coZKyPIaQxGHIPEs4KjrvpOBViWTYg%2Bm1iYtZdjr8HUsu4SxDw8z%2BHd9SgRg07RBhzbig5Vb6PL6GkHGhl3F15KaGu8zHLUCo6ym7rOKq08FR59FABk%2F%2BC%2FiIFU%2BXKcj8V9pKSg12CSAD8biH8Z0WTz3v5%2FRlnIn8kA0RHwsw%2BJ64vQY6pgFEZtHFbOOj3PoS3cftQU%2FEKDsXigZxchNIb9x95COV%2FKwTByvaieagmQx5O2XcKjJvXT6NQiEtCFoB3U3EFjhWMPh7EbSh84v0Q2ed1NZMz%2FbDDpJNYe7ydepSd1BJqNMXu%2FAkKQvzKApTkElCgDWpTGH7HCL7WBkrX5zr4%2FwNx0FJ2M2J9XZx2RqGMSoQlVGxxnFDoJWIQIKZ4m7yq4%2FMjh80E1da&X-Amz-Signature=27bb2afb57f0af16d49cd122f4b6383665d0bcd76d23725c59ab7086301b99e8&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SV3HPRYL%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T163102Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCQdh3z%2BjzSgmyRhKvQk%2FVF78SvHIyDNQ%2B9NhFZvGwX5gIgeszE5R%2B5P%2BAdrojUGkKMLW7wY7oWGfrUAxK4E4MzU7Mq%2FwMIGBAAGgw2Mzc0MjMxODM4MDUiDPCkmlXsWyN0NEt6YircAwNpbHEpW%2BQDgq1KwSuHD8KqD%2BLXowkaFoY8FvTCKtoICRsVtjrXTDyjscEHlRZx3Vxz4Am8bcCJiyTZtqkx6mZ0wxQ7ZpFAIr5iTfomun6VR7DohlwLoiVw0iBbkpfzuAOMEWzEP%2BKFKNh4KrAHQOHTSw%2FuPvPzaJqaMH%2BX72%2BWHiRdI%2FljFyAz%2BJuhWu0z%2Fpi4uZF3wa9R2%2FvIbCb65k8ZyX3saOLGHqmQOjGSK04IMi0tqgf4H%2FqPxpX9%2BeqZiNhFZlNQobIFR4xlNAXVFp%2BKrONeHS3XWegsDogUZMumPmVDmxfaSHw8vFcdi4GWLaBhfkvTX%2FXUPIh8rzlYS0D%2BzmS%2F5qx2Nz2cfCmSGZSnY4CAnXSd4Rzsj2%2B1DAneBn7KTq2Z7jg9Tc%2FsoH8%2B%2BvZLc5pEXfCPAbEzK%2B7EZT2JPxA8xn7r8573O9PbQPXQu0TT1LZ6liOUMDOj9Tv%2BCdpuHlG8mbkWWa960pX0ZNOE6LJKr2307X1TGM8Kw6Q%2BYNoaE6RTDiPoQML3B6zBJHqU5MuHxEUcq0UuObrB7dnA9qGs0HXCZ%2FvYuzE2EMEuLjvJ7KnBB74fL97jd1a6oGIXrpgs8qd1dbTauA3WMgooSZjehrSFeH0idEcmMPCduL0GOqUBAjNJW0mEVsPd%2BhgVncYVJJRvF81VlCEszuAE%2F2%2FF0uaxB9jc7UZHDXsDGLuPPeMjrR2btfz1OlgXri7SmqQctlV84HyNeEOPfxjbU3gQ7Mc%2Bf08CFGNXs7t4NFe49LkbodKLt0GReeN9P2sP6nMlmyvmBT6eQ8f6Yh8ynavS0X32jHsyUSZ%2BGL6S%2F7yfEZvk84IFiJA%2Fofiyql6usdD%2B1pPUVPUF&X-Amz-Signature=d429ed898459dd830744f914ce5b87371f9463c641b78d9314de07e039e6b67e&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663KIM35WP%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T163059Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIBZE4GNjzWo8nOUkBPWoPYsg4P18gbscitOi2mV%2Bn3PgAiBQ4t2pOFjjJzAcukC9tDrrAPkjGidd4OdiiX%2F7zxO11Cr%2FAwgZEAAaDDYzNzQyMzE4MzgwNSIM8x%2B7d6cO3%2FIiF%2FKUKtwDknbChNBIuB5F1%2F7lEeT2SzSHFI13xvcQCVBQZD58A8IIvSXxxzgV1ooQ8j0%2BaJqqDcDAPbIRj7N%2BMAJ2JLlhca2yPGibM8N2WiW7wa5xKisWhjxbCb51nKu1fh1V8rvCqls%2B%2FJaxNRP0FuKEDfztxhrZnKgkulgHH4ai5%2FyuKoi42zQETK9Q7U2Igg79faofOJLHQTvo3no9S9jr6xpV7jurDujLUwFSSZ9IxkI7FvPDEW3WzdcpSkYT0GEPuQengyeNFCuCNyucfxqxEC%2F5oAUFjj3pSgrgGzlt5X1%2FoSv0BD9XdGfkkkhY%2FgYHDM%2BeRdpoUzvOPJAcHdIriZTi%2B0vpYEHhVhBAEAChHPOD6R0tYDrvXMhHmPgu0ZLueo30bzUokPLcJcDAk6QCZv88ObH3a36Wp9yQAiVbqLTwl4Ik%2FNa14YN6uTrpfaYEJIB%2B5I87f3NifLUZSfcyNdRnsFmxVf4ZEoITQIIRYWTh8d0XpCvsJPdIoI7U4DziBNpMTKee0cSa2qR0LWykHK71%2FezVYczalZ8u8tXW6JE9VYWzaTqBUEhGsckrfO607mnTYJC5EleZEWPMhiFY74ZCn29%2Bl49gxfzWT848aGQYeDz0akNFtne0tB3Zxnkw3564vQY6pgHi%2Fx7wItH%2B%2B5odC45ZTTtgPsIbcyWZr%2BvltHMhZdg6383P3wUs1NA%2FogV1zzWfRHAF%2FebWBCZMURlFkWWgnmjt5R6iBm6W5WbvtYOx%2BwyJJBttlXCpXvU2ztwJXtHdxeg9gfPP2MYzWV0CfJBw4UM4f474IZfA6zxnEmlYOyYVhI4hpIJzbpTYpjZGYNxBM4chd9JGxXRUh5oxLirTCflVioW%2Fxz3N&X-Amz-Signature=8b756d4673586ac7a4606c424ea5d98901360ce201f607da46b46f46cc77622f&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663KIM35WP%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T163059Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIBZE4GNjzWo8nOUkBPWoPYsg4P18gbscitOi2mV%2Bn3PgAiBQ4t2pOFjjJzAcukC9tDrrAPkjGidd4OdiiX%2F7zxO11Cr%2FAwgZEAAaDDYzNzQyMzE4MzgwNSIM8x%2B7d6cO3%2FIiF%2FKUKtwDknbChNBIuB5F1%2F7lEeT2SzSHFI13xvcQCVBQZD58A8IIvSXxxzgV1ooQ8j0%2BaJqqDcDAPbIRj7N%2BMAJ2JLlhca2yPGibM8N2WiW7wa5xKisWhjxbCb51nKu1fh1V8rvCqls%2B%2FJaxNRP0FuKEDfztxhrZnKgkulgHH4ai5%2FyuKoi42zQETK9Q7U2Igg79faofOJLHQTvo3no9S9jr6xpV7jurDujLUwFSSZ9IxkI7FvPDEW3WzdcpSkYT0GEPuQengyeNFCuCNyucfxqxEC%2F5oAUFjj3pSgrgGzlt5X1%2FoSv0BD9XdGfkkkhY%2FgYHDM%2BeRdpoUzvOPJAcHdIriZTi%2B0vpYEHhVhBAEAChHPOD6R0tYDrvXMhHmPgu0ZLueo30bzUokPLcJcDAk6QCZv88ObH3a36Wp9yQAiVbqLTwl4Ik%2FNa14YN6uTrpfaYEJIB%2B5I87f3NifLUZSfcyNdRnsFmxVf4ZEoITQIIRYWTh8d0XpCvsJPdIoI7U4DziBNpMTKee0cSa2qR0LWykHK71%2FezVYczalZ8u8tXW6JE9VYWzaTqBUEhGsckrfO607mnTYJC5EleZEWPMhiFY74ZCn29%2Bl49gxfzWT848aGQYeDz0akNFtne0tB3Zxnkw3564vQY6pgHi%2Fx7wItH%2B%2B5odC45ZTTtgPsIbcyWZr%2BvltHMhZdg6383P3wUs1NA%2FogV1zzWfRHAF%2FebWBCZMURlFkWWgnmjt5R6iBm6W5WbvtYOx%2BwyJJBttlXCpXvU2ztwJXtHdxeg9gfPP2MYzWV0CfJBw4UM4f474IZfA6zxnEmlYOyYVhI4hpIJzbpTYpjZGYNxBM4chd9JGxXRUh5oxLirTCflVioW%2Fxz3N&X-Amz-Signature=4e6103acc17faf980e241571ef8d3f6053b148a850b94620dbbb69df39b334e4&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663KIM35WP%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T163059Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIBZE4GNjzWo8nOUkBPWoPYsg4P18gbscitOi2mV%2Bn3PgAiBQ4t2pOFjjJzAcukC9tDrrAPkjGidd4OdiiX%2F7zxO11Cr%2FAwgZEAAaDDYzNzQyMzE4MzgwNSIM8x%2B7d6cO3%2FIiF%2FKUKtwDknbChNBIuB5F1%2F7lEeT2SzSHFI13xvcQCVBQZD58A8IIvSXxxzgV1ooQ8j0%2BaJqqDcDAPbIRj7N%2BMAJ2JLlhca2yPGibM8N2WiW7wa5xKisWhjxbCb51nKu1fh1V8rvCqls%2B%2FJaxNRP0FuKEDfztxhrZnKgkulgHH4ai5%2FyuKoi42zQETK9Q7U2Igg79faofOJLHQTvo3no9S9jr6xpV7jurDujLUwFSSZ9IxkI7FvPDEW3WzdcpSkYT0GEPuQengyeNFCuCNyucfxqxEC%2F5oAUFjj3pSgrgGzlt5X1%2FoSv0BD9XdGfkkkhY%2FgYHDM%2BeRdpoUzvOPJAcHdIriZTi%2B0vpYEHhVhBAEAChHPOD6R0tYDrvXMhHmPgu0ZLueo30bzUokPLcJcDAk6QCZv88ObH3a36Wp9yQAiVbqLTwl4Ik%2FNa14YN6uTrpfaYEJIB%2B5I87f3NifLUZSfcyNdRnsFmxVf4ZEoITQIIRYWTh8d0XpCvsJPdIoI7U4DziBNpMTKee0cSa2qR0LWykHK71%2FezVYczalZ8u8tXW6JE9VYWzaTqBUEhGsckrfO607mnTYJC5EleZEWPMhiFY74ZCn29%2Bl49gxfzWT848aGQYeDz0akNFtne0tB3Zxnkw3564vQY6pgHi%2Fx7wItH%2B%2B5odC45ZTTtgPsIbcyWZr%2BvltHMhZdg6383P3wUs1NA%2FogV1zzWfRHAF%2FebWBCZMURlFkWWgnmjt5R6iBm6W5WbvtYOx%2BwyJJBttlXCpXvU2ztwJXtHdxeg9gfPP2MYzWV0CfJBw4UM4f474IZfA6zxnEmlYOyYVhI4hpIJzbpTYpjZGYNxBM4chd9JGxXRUh5oxLirTCflVioW%2Fxz3N&X-Amz-Signature=164e4c207a200b3ea88f5135edb6801a92c20063251a5103da8f92ffe989969a&X-Amz-SignedHeaders=host&x-id=GetObject)


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

