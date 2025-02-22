---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466ZCY7HXVV%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250222T222133Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEMr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCXJ6V4XM6s6G47Cz7\
  cMTOQuRE6DK517%2FlRU8IFX40RtQIhAJVc96gpoJxgTHaZk7Mfb4B0eZYkiKI6Pwx3jdBGPDM9Ko\
  gECPP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igy%2B6q5%2FViMa3lg\
  y0yoq3AOi3mfpC%2B2ZU35mbvXMSDZzGBCRNru7yyI%2BMMrYK88dk0lJOHogNakJvlKuEP%2Fi3H\
  fiEFxHDeXem7f0YjKFLXRfOKtRr1QaFA4GKVabp%2BIYdLnvKDdWHHHgYAbBgVuBx7a8MzOwaALVr\
  HMoEo9ELN0IMUPxGCcQ6GFJdcz%2F7NapCquCpdkghXEy%2FR2DXR0HE%2B8Kq9pW9pmnaw9GGcY4\
  ubs1Gc4OE94cCC9KlgRY%2BZTuuDEnva45hLPTeImJzsL0VL%2BnfDzHjpdtV0y0fF6GElf1hsW03\
  Oy0nKlAh8LBBdzKl62ItYHx96hpGmMR0GO%2BFk%2FuKBjVATbcCnSGx078Mxy7Wzoz1WoPPOIVAV\
  O%2FZfNV9kdmzlbPQ5Y1%2FOp%2F%2FnL5%2Fsvns7Va3cZHEQf8tkbqWLuu0Oor7B20Wg8GQHEOj\
  8VBSNQztvTcvwPK1w%2BSV%2FQwDU5Q1HJGIU8qrGr2dfdbg8IUa5TyTwiZsqBY4fG%2BEUV9Whwz\
  1%2Ba1PK3WSkPtnU%2B3qmcybioN82ylM88F%2BIx2h0QSdotvoNeUkB7V%2F0EQJf6j1JuwkswzL\
  JWRV6SGZkOGwz9FIOLY5WPwy9kjBOCJ9gCZJMHn6XTNw8JVe7jXb52TTi0AC%2Bxz2iZAQzvRyzCG\
  k%2Bi9BjqkAUe%2BIP2oHM0ZnHmWYhi0DfPOWCXCf4j7OZp5hVoFUSpQsfGkSqm9l6fbBTKGKaJDP\
  JyVjHr7wb%2B9WGUma%2FSL%2BFaa7ZzVrRXApxc8TRw4SCoRBY7QMnNIsNkc0Q%2B41iPo7AaqYZ\
  LNQR70vGwvZpmA8awvNOsfa2C9IzWO%2BeEUDFE%2B2T0lwIiAjkEbYS8ecROZIOZMbBOqvNeJNBa\
  dGLIx6f%2FNbGL9&X-Amz-Signature=3f2a48327d5a85e70b09054a915e86e9a3a17a74b039f\
  be42ad7b846da436714&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466VKAGOF3H%2F20250222%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250222T222006Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEM7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIQCbReXn%2BST4AIhjwkcJ5ZR4cqxEA9T8n6BrS9B4QyIDHgIgOIFr7%2FcD89jiOSSD25\
        qqEzpTjTU2YzPcjC8QKInI7hoqiAQI9v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2M\
        zc0MjMxODM4MDUiDMjXGNLUKVWhzm2SayrcAx68xvpO%2FzShNOvLGyFXkhp2v8iTatMl5i\
        G7xt%2BdSZKVDUuG3S1sLI%2B5tEy1S4tZIsZyuva4DBYFi46RHQxonkC8hoNBE8ZYqvxtZ\
        uCEg7XaqictBMpR2qmZjgYd5ac2XdJ%2F1CY%2FEd4Pj8SPCgriZ2W12X5LG5cA6UuZkPnY\
        47%2BxWU7PtdvWrhalZaDDACbs2Qt5wKGbZk%2FusMEyDwsszmbdYzp1Vn0Ia1eq3jrPsw8\
        QTACWlKUTSQV%2BhZteey1%2FZvzWqgBWN5RCsE3xvLqhV32LarxVa5aR8KHaV0SLF%2F3x\
        SnqkEyUtIB8V7zclIaHBo0EEVeViw%2FBzHRQAfT3in5UfbvbO%2BI5OTeZ%2Bo4HUFpiGQ\
        dUSsCweXNda3nicqkIpGTnaiXKwEeumZmi7v%2B4EHEpORSP5drPd1CQ31RchOH4VMrunyG\
        iUVsEXVmNjUoU4MAvdxovcK3f6MsEr35gRh%2FSZVcX0KT3y6JxcLXBpdZq%2BJ3VCKPGDE\
        jUeaspYLVp9jRF5VEb6php0nEzq0bohX8HfBQMy7yyWLIcenje1Kl5Dmv%2BkrU5AmurMA3\
        fAtdUcDkwqyaSEHcGgb%2FNo5%2BviO6%2BeTV%2FrA%2B4sSzrZtgYpM5IOYuHxeTxaBCg\
        D8Y9KMJf%2F6L0GOqUBOhaUHLFtlw69vdLV5bBRNi0eIPjBtuJR8V3pAez55LaIAM16GNrA\
        zE0mMLlAm047exB46PcSFF%2FT5bI%2BsVL69fuk%2FWV1kS8eRRodPSm7AuiC4MKG6lv5O\
        oa%2BkZMXH41CIx1tqzmtF813e9b%2B4wwCWbMdfkPKABnLGAkewWrieqYEb1QNgmnTXY5j\
        DvPjuwllL1U2%2BoXTVYoqkpk1Ozdd8DqvaGel&X-Amz-Signature=2b0848230c3833c5\
        be14167f4381dea165ee2f7e966152204075573ebbcdcfe2&X-Amz-SignedHeaders=ho\
        st&x-id=GetObject"
      expiry_time: "2025-02-22T23:20:06.278Z"
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
UPDATE_TIME: "2025-02-22T22:21:40.139Z"
EXPIRY_TIME: "2025-02-22T23:21:29.522Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662GL7EPFW%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T222130Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDIsRFSvXQl%2FcvquO7RChLJSHA4B3triLFYQdfBDKZ0pwIgdtn%2FPT1GmeCXoKCdoA3q%2BviH2lP6BxxoxK0yIvKjodkqiAQI8%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDERLsQ0VAukRTSzm%2ByrcA98Vt6biohFcbq%2BTJwpyDtGEo0q0WgaY5O99r9F10%2Fx3JlMFYT4AyDrFp7H2lbZcaZWIiZa2OiwBLwBpGUlYcSLce3Ra99W%2Fc%2Bxlr634YbFN6kz0vFpoaHH39X5OLt2csAzfAPM2wltF9Z3wU2IVaBOGUwpO2QrGnEOSVgJDcKkjiXA4dg1IaUqXAadADligivypWAGiqCNtQQALXzPPGahrG7maPt%2F52vSrn44jFfWhRZ3pv8whP8ybOAXdA8QwsVr3nVG6lszOj1LnS7bmn0SsHWhsAemZJivTgfklqBBmRPoJcgc23llTpVRgwkVj2BRjIzNbPfQNWSJDwdQUStl2ZUEEPb8nEIRjfSU9mgdVFhmY0K66Rrg7h6vyoDtJWZIELxgLxbvgfpy6lFSl8gFuxdpi4Ai41JyU83Cz9rV4VDH7aRDgSSe0E8u1ex3%2FI28XCDb57PIetmfxrQoxjCvYd568AfqeyBA08nZAGZ69fhiRIIX5TDSubO6vK7NSFMor6u0fIrRiSVIwysJuLyUBYMbumYlyb%2BE96DFgPx6VICHNgr4JJSrCkD36xKfW0FsIfEJ4KOi9uTG5P3TFzUBiEV5V3EXBQyaHd7zSl0TRGxyiaigoMeXu3WwEMLuS6L0GOqUBLEP0kw2GK70QPXjYaFU2a%2B89Iq8z3YdHpjsJjUVQ%2FkFaSYsqSf%2BCoHAahV9GSEb8l7tdU%2FrNji3T3OPYsWw%2B2Bu6K0POGagW5VqnGJSJCgczQhWu9edjw9UrY7U8QNRTHdXn6uXw0q1D9uA%2B18FEhzvXoWFvYDQfGDrgoddBygABBkL2zHXn1mwLfUm98wjTMVh%2BZg4XtG41%2F%2BjebyOLBwGo1NJ9&X-Amz-Signature=ea9b7162d64bef5989fa4e689170e1b2f4ca0a2eaf2aa01d2418e35bc93e8ebe&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662GL7EPFW%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T222130Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDIsRFSvXQl%2FcvquO7RChLJSHA4B3triLFYQdfBDKZ0pwIgdtn%2FPT1GmeCXoKCdoA3q%2BviH2lP6BxxoxK0yIvKjodkqiAQI8%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDERLsQ0VAukRTSzm%2ByrcA98Vt6biohFcbq%2BTJwpyDtGEo0q0WgaY5O99r9F10%2Fx3JlMFYT4AyDrFp7H2lbZcaZWIiZa2OiwBLwBpGUlYcSLce3Ra99W%2Fc%2Bxlr634YbFN6kz0vFpoaHH39X5OLt2csAzfAPM2wltF9Z3wU2IVaBOGUwpO2QrGnEOSVgJDcKkjiXA4dg1IaUqXAadADligivypWAGiqCNtQQALXzPPGahrG7maPt%2F52vSrn44jFfWhRZ3pv8whP8ybOAXdA8QwsVr3nVG6lszOj1LnS7bmn0SsHWhsAemZJivTgfklqBBmRPoJcgc23llTpVRgwkVj2BRjIzNbPfQNWSJDwdQUStl2ZUEEPb8nEIRjfSU9mgdVFhmY0K66Rrg7h6vyoDtJWZIELxgLxbvgfpy6lFSl8gFuxdpi4Ai41JyU83Cz9rV4VDH7aRDgSSe0E8u1ex3%2FI28XCDb57PIetmfxrQoxjCvYd568AfqeyBA08nZAGZ69fhiRIIX5TDSubO6vK7NSFMor6u0fIrRiSVIwysJuLyUBYMbumYlyb%2BE96DFgPx6VICHNgr4JJSrCkD36xKfW0FsIfEJ4KOi9uTG5P3TFzUBiEV5V3EXBQyaHd7zSl0TRGxyiaigoMeXu3WwEMLuS6L0GOqUBLEP0kw2GK70QPXjYaFU2a%2B89Iq8z3YdHpjsJjUVQ%2FkFaSYsqSf%2BCoHAahV9GSEb8l7tdU%2FrNji3T3OPYsWw%2B2Bu6K0POGagW5VqnGJSJCgczQhWu9edjw9UrY7U8QNRTHdXn6uXw0q1D9uA%2B18FEhzvXoWFvYDQfGDrgoddBygABBkL2zHXn1mwLfUm98wjTMVh%2BZg4XtG41%2F%2BjebyOLBwGo1NJ9&X-Amz-Signature=2a8bc7ad6455dd5d841a686a762e3ce24f51cdc3b2165d60a10dc69e23a6ed67&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662GL7EPFW%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T222130Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDIsRFSvXQl%2FcvquO7RChLJSHA4B3triLFYQdfBDKZ0pwIgdtn%2FPT1GmeCXoKCdoA3q%2BviH2lP6BxxoxK0yIvKjodkqiAQI8%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDERLsQ0VAukRTSzm%2ByrcA98Vt6biohFcbq%2BTJwpyDtGEo0q0WgaY5O99r9F10%2Fx3JlMFYT4AyDrFp7H2lbZcaZWIiZa2OiwBLwBpGUlYcSLce3Ra99W%2Fc%2Bxlr634YbFN6kz0vFpoaHH39X5OLt2csAzfAPM2wltF9Z3wU2IVaBOGUwpO2QrGnEOSVgJDcKkjiXA4dg1IaUqXAadADligivypWAGiqCNtQQALXzPPGahrG7maPt%2F52vSrn44jFfWhRZ3pv8whP8ybOAXdA8QwsVr3nVG6lszOj1LnS7bmn0SsHWhsAemZJivTgfklqBBmRPoJcgc23llTpVRgwkVj2BRjIzNbPfQNWSJDwdQUStl2ZUEEPb8nEIRjfSU9mgdVFhmY0K66Rrg7h6vyoDtJWZIELxgLxbvgfpy6lFSl8gFuxdpi4Ai41JyU83Cz9rV4VDH7aRDgSSe0E8u1ex3%2FI28XCDb57PIetmfxrQoxjCvYd568AfqeyBA08nZAGZ69fhiRIIX5TDSubO6vK7NSFMor6u0fIrRiSVIwysJuLyUBYMbumYlyb%2BE96DFgPx6VICHNgr4JJSrCkD36xKfW0FsIfEJ4KOi9uTG5P3TFzUBiEV5V3EXBQyaHd7zSl0TRGxyiaigoMeXu3WwEMLuS6L0GOqUBLEP0kw2GK70QPXjYaFU2a%2B89Iq8z3YdHpjsJjUVQ%2FkFaSYsqSf%2BCoHAahV9GSEb8l7tdU%2FrNji3T3OPYsWw%2B2Bu6K0POGagW5VqnGJSJCgczQhWu9edjw9UrY7U8QNRTHdXn6uXw0q1D9uA%2B18FEhzvXoWFvYDQfGDrgoddBygABBkL2zHXn1mwLfUm98wjTMVh%2BZg4XtG41%2F%2BjebyOLBwGo1NJ9&X-Amz-Signature=98b57aef9f933617c3f0d20af9afced0e3452eaeeddbccb5fea9e70cf98b3317&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662GL7EPFW%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T222130Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDIsRFSvXQl%2FcvquO7RChLJSHA4B3triLFYQdfBDKZ0pwIgdtn%2FPT1GmeCXoKCdoA3q%2BviH2lP6BxxoxK0yIvKjodkqiAQI8%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDERLsQ0VAukRTSzm%2ByrcA98Vt6biohFcbq%2BTJwpyDtGEo0q0WgaY5O99r9F10%2Fx3JlMFYT4AyDrFp7H2lbZcaZWIiZa2OiwBLwBpGUlYcSLce3Ra99W%2Fc%2Bxlr634YbFN6kz0vFpoaHH39X5OLt2csAzfAPM2wltF9Z3wU2IVaBOGUwpO2QrGnEOSVgJDcKkjiXA4dg1IaUqXAadADligivypWAGiqCNtQQALXzPPGahrG7maPt%2F52vSrn44jFfWhRZ3pv8whP8ybOAXdA8QwsVr3nVG6lszOj1LnS7bmn0SsHWhsAemZJivTgfklqBBmRPoJcgc23llTpVRgwkVj2BRjIzNbPfQNWSJDwdQUStl2ZUEEPb8nEIRjfSU9mgdVFhmY0K66Rrg7h6vyoDtJWZIELxgLxbvgfpy6lFSl8gFuxdpi4Ai41JyU83Cz9rV4VDH7aRDgSSe0E8u1ex3%2FI28XCDb57PIetmfxrQoxjCvYd568AfqeyBA08nZAGZ69fhiRIIX5TDSubO6vK7NSFMor6u0fIrRiSVIwysJuLyUBYMbumYlyb%2BE96DFgPx6VICHNgr4JJSrCkD36xKfW0FsIfEJ4KOi9uTG5P3TFzUBiEV5V3EXBQyaHd7zSl0TRGxyiaigoMeXu3WwEMLuS6L0GOqUBLEP0kw2GK70QPXjYaFU2a%2B89Iq8z3YdHpjsJjUVQ%2FkFaSYsqSf%2BCoHAahV9GSEb8l7tdU%2FrNji3T3OPYsWw%2B2Bu6K0POGagW5VqnGJSJCgczQhWu9edjw9UrY7U8QNRTHdXn6uXw0q1D9uA%2B18FEhzvXoWFvYDQfGDrgoddBygABBkL2zHXn1mwLfUm98wjTMVh%2BZg4XtG41%2F%2BjebyOLBwGo1NJ9&X-Amz-Signature=213b36722e443a3e9b46368bc0495faafc4a654a8d64a35ccd92bc43ae4b3c52&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662GL7EPFW%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T222130Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDIsRFSvXQl%2FcvquO7RChLJSHA4B3triLFYQdfBDKZ0pwIgdtn%2FPT1GmeCXoKCdoA3q%2BviH2lP6BxxoxK0yIvKjodkqiAQI8%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDERLsQ0VAukRTSzm%2ByrcA98Vt6biohFcbq%2BTJwpyDtGEo0q0WgaY5O99r9F10%2Fx3JlMFYT4AyDrFp7H2lbZcaZWIiZa2OiwBLwBpGUlYcSLce3Ra99W%2Fc%2Bxlr634YbFN6kz0vFpoaHH39X5OLt2csAzfAPM2wltF9Z3wU2IVaBOGUwpO2QrGnEOSVgJDcKkjiXA4dg1IaUqXAadADligivypWAGiqCNtQQALXzPPGahrG7maPt%2F52vSrn44jFfWhRZ3pv8whP8ybOAXdA8QwsVr3nVG6lszOj1LnS7bmn0SsHWhsAemZJivTgfklqBBmRPoJcgc23llTpVRgwkVj2BRjIzNbPfQNWSJDwdQUStl2ZUEEPb8nEIRjfSU9mgdVFhmY0K66Rrg7h6vyoDtJWZIELxgLxbvgfpy6lFSl8gFuxdpi4Ai41JyU83Cz9rV4VDH7aRDgSSe0E8u1ex3%2FI28XCDb57PIetmfxrQoxjCvYd568AfqeyBA08nZAGZ69fhiRIIX5TDSubO6vK7NSFMor6u0fIrRiSVIwysJuLyUBYMbumYlyb%2BE96DFgPx6VICHNgr4JJSrCkD36xKfW0FsIfEJ4KOi9uTG5P3TFzUBiEV5V3EXBQyaHd7zSl0TRGxyiaigoMeXu3WwEMLuS6L0GOqUBLEP0kw2GK70QPXjYaFU2a%2B89Iq8z3YdHpjsJjUVQ%2FkFaSYsqSf%2BCoHAahV9GSEb8l7tdU%2FrNji3T3OPYsWw%2B2Bu6K0POGagW5VqnGJSJCgczQhWu9edjw9UrY7U8QNRTHdXn6uXw0q1D9uA%2B18FEhzvXoWFvYDQfGDrgoddBygABBkL2zHXn1mwLfUm98wjTMVh%2BZg4XtG41%2F%2BjebyOLBwGo1NJ9&X-Amz-Signature=dc6f7da76b820db9f8046d0fa2820e37826326de8f923b4ab5f223f5a003a339&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZM4YRWEG%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T222130Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCNiC1ZUaPzOhVLU1staOxxLycYZ3Cd95m5kKGM1soQOQIhAL8JRnI4TVUlesVRe3e13Ymm7VPj2av2CX%2FvOwBEbyEXKogECPL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwFVIBNEgSJy%2BWQYI0q3AOf0BFcWTRQZLdhJdkKEIZ1k26jSG2pfGdOSICx4DvB%2BOKUeTdUg66j5MMXPGRfAcEmv8A13axWKX6pnx6yPncwFUObzNjKmmZDUpLpWJcO1vkNjIexFGqrDohq2YrfT63N%2FWluzJw%2F00Df2O0WhV888cCX4tBWKtG8ejyogH1MFdK7CasuXHRseRP%2B7CNtc2z8I06fa7uYnldULAHOThMgn24PVYfsITfV%2FsxzyloifTRYnTvb02EekPyqfVk5n9Rir0qshhnAShAyo%2BLvJcpoyVpOgwz4Q8QYbYvyedYdzXrLXWCyqyFHJ86cX3M%2F8erAAF6rnP%2Fm9jZD6CLkCr%2FxabyTETQgIIya6QvszGSRVolJ3iQdjQsb2J4Xb1YJINK4I64mKrs33S8ciV9E3S3KTUXdw5fh89CJ%2Bd60nPWDAjYHNaHQ%2FRWPQ6W%2B3KOfgr3VevDyqbvkZQsjsZ3PY41hWYuIB2lstGKRy3Qhh6YsH%2BEkqsoag8XVbC%2BWBHjKIz0OJBWFy30FzeAZDyPOf5yrSj7cnr9zHOs2tUotnEUaiLNcNtxKvkv0bnDka8eDtYH344yZwXT3yFAzZBv7PoIvCFdPqABlpi0Oehs%2FMFApb2pvDBp668%2B%2FQH7EXzCYiOi9BjqkAYFY3i8KS2o6HuF7zZROJ2%2BY%2BKzCUEUfhQAqDgMv1EV53X8xVJZlA5rOP6kRCFv5h2vh993%2F6SSct1KBNpfHzC0S5rEhdR3zfkiaTBHZUkQYtWgrI%2BSd3i9xpZFcbkEXW2ztls%2B7%2FvlTLAU1TLnzLRiffvp1JgxAFGZfFbWcLBFNMgPLPRdpypqom6APDv1%2Bljlr%2BGcGDsw0PAVpSnone9pGgI2C&X-Amz-Signature=3c4d8c3bac758ffe2c1a42cade33414e376467b171f2fc2ad7075eec69e704b4&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662FYGTMJY%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T222133Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDIKRj35lQ8FqmCaOPqrfjtnYWkBPu0qEh35THqWGa%2FAQIgRt3Adm%2BDCx%2Fd9UpbZtPKtLtgVmlDNKmOnN8bB8f605YqiAQI9v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGagPmnlWUvWU8sL%2FyrcAwkdCYq%2BmJ3fYEeIDt7mujIgMOJgSPVMwI1zN5mXEApwQ6Hyp68nn5EvVkVhMbkGalzkPBlo7GCynf9KXfNb7Ux0WptBgaHKWuXw%2Fq3aRjuU3qwmalNfCpOfad06NunDXe5XVp9IEJN5%2FdHb8P9Z2PPI9XRHZ%2BAFvJZeAk42Cnn1J8S%2FuvMEpCtehmYS9YFfjVQI0SaXYa393DBu36vjvym5E9A1ZktPYuy%2FdtylM1o2JVZyS%2F952Mtk1H81ynZRpgULM3f6oj3Q0pKSFxhX6eER3aKq6BfvR4sjDRWc6VbIqCHcHikSf9EXLALLaX1ztIfR0Qd0W18mRAh9f%2FuF7iLAqDfRfca9X%2FYhC0VKdRDpa0wRwyh%2BvqPVEdBqH73eWHDw6TmAN9A7Wx2b10wqqNdK6TvXiqZveu8bzL9cyZVhLRcurub1PeJnVPEtr%2F8z1kFot7j5dnehzWacbgmf5NTgpmH%2Bvip5IATTSqV%2BNQjosSWc12JDXiTxd7QT%2FE0lbO%2BY4gKvEVELRdAoYnmppaNA%2Fjks4JXEsZ6qaFhWBOF%2F8kBB5lMJZOnr0C4yuP5LnSsH2QpDtmUstcGQ7bCyDP9noe76iNZrS2GZuwQZPni3iie%2B4taNqbdJlElHMJzy6L0GOqUBledLj1uI0%2BcFHbdHP4U5025pZO%2F13RiYaR25LGxBOqb36MhZ8xKFxjrDc2sn7y7yyKVFi0zTtfBzouMcgYpH2WRqUyohxCaH1GtOxIMwi8zzHioQnlXpCKYfFzoeAyFWAhUeivb3LAiz37sW1qET%2FwU7AOuzrrveQ6bADOdVsqvWUzhmrTYSJrZYfH8eY%2FfIAYmVkdBld0bzPkLlabtpMBogcyRP&X-Amz-Signature=68970075c8746c3b35eac79f5f0ca89bbdfbf9f34a51b60dcd297b42ad338e58&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662GL7EPFW%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T222130Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDIsRFSvXQl%2FcvquO7RChLJSHA4B3triLFYQdfBDKZ0pwIgdtn%2FPT1GmeCXoKCdoA3q%2BviH2lP6BxxoxK0yIvKjodkqiAQI8%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDERLsQ0VAukRTSzm%2ByrcA98Vt6biohFcbq%2BTJwpyDtGEo0q0WgaY5O99r9F10%2Fx3JlMFYT4AyDrFp7H2lbZcaZWIiZa2OiwBLwBpGUlYcSLce3Ra99W%2Fc%2Bxlr634YbFN6kz0vFpoaHH39X5OLt2csAzfAPM2wltF9Z3wU2IVaBOGUwpO2QrGnEOSVgJDcKkjiXA4dg1IaUqXAadADligivypWAGiqCNtQQALXzPPGahrG7maPt%2F52vSrn44jFfWhRZ3pv8whP8ybOAXdA8QwsVr3nVG6lszOj1LnS7bmn0SsHWhsAemZJivTgfklqBBmRPoJcgc23llTpVRgwkVj2BRjIzNbPfQNWSJDwdQUStl2ZUEEPb8nEIRjfSU9mgdVFhmY0K66Rrg7h6vyoDtJWZIELxgLxbvgfpy6lFSl8gFuxdpi4Ai41JyU83Cz9rV4VDH7aRDgSSe0E8u1ex3%2FI28XCDb57PIetmfxrQoxjCvYd568AfqeyBA08nZAGZ69fhiRIIX5TDSubO6vK7NSFMor6u0fIrRiSVIwysJuLyUBYMbumYlyb%2BE96DFgPx6VICHNgr4JJSrCkD36xKfW0FsIfEJ4KOi9uTG5P3TFzUBiEV5V3EXBQyaHd7zSl0TRGxyiaigoMeXu3WwEMLuS6L0GOqUBLEP0kw2GK70QPXjYaFU2a%2B89Iq8z3YdHpjsJjUVQ%2FkFaSYsqSf%2BCoHAahV9GSEb8l7tdU%2FrNji3T3OPYsWw%2B2Bu6K0POGagW5VqnGJSJCgczQhWu9edjw9UrY7U8QNRTHdXn6uXw0q1D9uA%2B18FEhzvXoWFvYDQfGDrgoddBygABBkL2zHXn1mwLfUm98wjTMVh%2BZg4XtG41%2F%2BjebyOLBwGo1NJ9&X-Amz-Signature=db4d94b998b938648832ccfde7044aecc6df7540230dd89e90b808dacc3880fd&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662GL7EPFW%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T222130Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDIsRFSvXQl%2FcvquO7RChLJSHA4B3triLFYQdfBDKZ0pwIgdtn%2FPT1GmeCXoKCdoA3q%2BviH2lP6BxxoxK0yIvKjodkqiAQI8%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDERLsQ0VAukRTSzm%2ByrcA98Vt6biohFcbq%2BTJwpyDtGEo0q0WgaY5O99r9F10%2Fx3JlMFYT4AyDrFp7H2lbZcaZWIiZa2OiwBLwBpGUlYcSLce3Ra99W%2Fc%2Bxlr634YbFN6kz0vFpoaHH39X5OLt2csAzfAPM2wltF9Z3wU2IVaBOGUwpO2QrGnEOSVgJDcKkjiXA4dg1IaUqXAadADligivypWAGiqCNtQQALXzPPGahrG7maPt%2F52vSrn44jFfWhRZ3pv8whP8ybOAXdA8QwsVr3nVG6lszOj1LnS7bmn0SsHWhsAemZJivTgfklqBBmRPoJcgc23llTpVRgwkVj2BRjIzNbPfQNWSJDwdQUStl2ZUEEPb8nEIRjfSU9mgdVFhmY0K66Rrg7h6vyoDtJWZIELxgLxbvgfpy6lFSl8gFuxdpi4Ai41JyU83Cz9rV4VDH7aRDgSSe0E8u1ex3%2FI28XCDb57PIetmfxrQoxjCvYd568AfqeyBA08nZAGZ69fhiRIIX5TDSubO6vK7NSFMor6u0fIrRiSVIwysJuLyUBYMbumYlyb%2BE96DFgPx6VICHNgr4JJSrCkD36xKfW0FsIfEJ4KOi9uTG5P3TFzUBiEV5V3EXBQyaHd7zSl0TRGxyiaigoMeXu3WwEMLuS6L0GOqUBLEP0kw2GK70QPXjYaFU2a%2B89Iq8z3YdHpjsJjUVQ%2FkFaSYsqSf%2BCoHAahV9GSEb8l7tdU%2FrNji3T3OPYsWw%2B2Bu6K0POGagW5VqnGJSJCgczQhWu9edjw9UrY7U8QNRTHdXn6uXw0q1D9uA%2B18FEhzvXoWFvYDQfGDrgoddBygABBkL2zHXn1mwLfUm98wjTMVh%2BZg4XtG41%2F%2BjebyOLBwGo1NJ9&X-Amz-Signature=a0024dee56ff1e553db5fc086b18d4ae539d596a40df82a3d38d24089317d4f0&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662GL7EPFW%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T222130Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDIsRFSvXQl%2FcvquO7RChLJSHA4B3triLFYQdfBDKZ0pwIgdtn%2FPT1GmeCXoKCdoA3q%2BviH2lP6BxxoxK0yIvKjodkqiAQI8%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDERLsQ0VAukRTSzm%2ByrcA98Vt6biohFcbq%2BTJwpyDtGEo0q0WgaY5O99r9F10%2Fx3JlMFYT4AyDrFp7H2lbZcaZWIiZa2OiwBLwBpGUlYcSLce3Ra99W%2Fc%2Bxlr634YbFN6kz0vFpoaHH39X5OLt2csAzfAPM2wltF9Z3wU2IVaBOGUwpO2QrGnEOSVgJDcKkjiXA4dg1IaUqXAadADligivypWAGiqCNtQQALXzPPGahrG7maPt%2F52vSrn44jFfWhRZ3pv8whP8ybOAXdA8QwsVr3nVG6lszOj1LnS7bmn0SsHWhsAemZJivTgfklqBBmRPoJcgc23llTpVRgwkVj2BRjIzNbPfQNWSJDwdQUStl2ZUEEPb8nEIRjfSU9mgdVFhmY0K66Rrg7h6vyoDtJWZIELxgLxbvgfpy6lFSl8gFuxdpi4Ai41JyU83Cz9rV4VDH7aRDgSSe0E8u1ex3%2FI28XCDb57PIetmfxrQoxjCvYd568AfqeyBA08nZAGZ69fhiRIIX5TDSubO6vK7NSFMor6u0fIrRiSVIwysJuLyUBYMbumYlyb%2BE96DFgPx6VICHNgr4JJSrCkD36xKfW0FsIfEJ4KOi9uTG5P3TFzUBiEV5V3EXBQyaHd7zSl0TRGxyiaigoMeXu3WwEMLuS6L0GOqUBLEP0kw2GK70QPXjYaFU2a%2B89Iq8z3YdHpjsJjUVQ%2FkFaSYsqSf%2BCoHAahV9GSEb8l7tdU%2FrNji3T3OPYsWw%2B2Bu6K0POGagW5VqnGJSJCgczQhWu9edjw9UrY7U8QNRTHdXn6uXw0q1D9uA%2B18FEhzvXoWFvYDQfGDrgoddBygABBkL2zHXn1mwLfUm98wjTMVh%2BZg4XtG41%2F%2BjebyOLBwGo1NJ9&X-Amz-Signature=53d5bc1a9f585fc3f48b99e46a0bbc6408f8fc1a79949bceb6a2e5aab21566bf&X-Amz-SignedHeaders=host&x-id=GetObject)


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

