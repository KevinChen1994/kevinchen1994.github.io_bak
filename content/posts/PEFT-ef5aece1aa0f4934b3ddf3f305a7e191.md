---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4666PKH62FH%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250215T152233Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEB8aCXVzLXdlc3QtMiJHMEUCIEPEP6xvOu0EJLSMaQBds%2FoTcjL%2BtXBR1p%2F%2FhBKNqMX\
  1AiEA0pleKeHucO%2BGy8pqYvDAPzdY9591fBK2J41pu8d3rr0q%2FwMIRxAAGgw2Mzc0MjMxODM4\
  MDUiDJkkZ7MjOj34YRQyqSrcAyx%2BkA0GaurmrbhubniHfckgkLnYtWuCD6323iNEfRt%2FiaXZy\
  xDwHXbPmfxl4UUIgZXitUZ2SCypPjBkdDqV1myOEiPJITzg1j%2FMB26I61BeChXahWoWWIMWoDN1\
  wEK5Q%2F2Iw7rU5HLTpp09JL%2FIYostKds7FJbfqb2GP6DhrytywER9mPn631Kv4WUBx8FBD%2Bc\
  %2FCwPBgoocZVYeE5DoempEJlQ6hFZnLPBzwbGoojTDWCTZ%2B%2FXW86M9Q6xodhHAyAsVEeDuxj\
  oZE2hvpX1fkc9GxCFGbEXAkbcOOYEOuQ4eGMefSH0NN6qQ%2Fjz6myKwwjrw91fbI9vrOWzSniZyr\
  xXdc3qCHtH3PdZalaSoLUp2VjJ%2FaNuK1VHJ8EgBx%2FG67HwXELi8RUc0FfQQdVxO0Xw7KEve1%\
  2FrW4%2BFwHXDKqr6mA7drJU25JUt5gjPYMYTKNdycku8IH1DOhxdJ4W1onSNn5QVjcnRQLCKuObU\
  cXvWBlpWvZgqT%2F4ShyzfHLy869FPmac9BgUvHOtyoOj90lc5fJCPPo5UzvH3tvovmrHl68PJ5T3\
  EZxQOEnSrObZZV5Az3Hg4VJp2U%2BbOdJdheODgaZPi1yYTMzkNeMK%2FXC%2BiAScWiw%2BID94C\
  QFBoKML7Gwr0GOqUBmK2tc36NXTjdy6T2%2BU7HZxt4g9eEVcSRBc6mXpelh4PEuDqZEEgbu8TBku\
  bp%2BRRGhZa61UNnjqYm0BbYWBzHtRfZ5JjSWuKmPP5dsBBMKC8tykQbZg7SrVvR4TwgYtyPHy0%2\
  Be7XWL3wRz6zuyf5urVdt7tBk5dNSu3oeFfmcNzU6BHqVs7bDhhc%2Fnj%2BZU1WOOJWbqsFQCNvM\
  Ru7GQ%2FBCfxmPzwvF&X-Amz-Signature=818e44e41085211df98e783c65affe3c1f29b5fdee\
  5c474a615dfc55ba630369&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466QLPSAHLW%2F20250215%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250215T152136Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEB8aCXVzLXdlc3QtMiJHMEUCIDeapp6mbtYSZuZEaiwX5tedZfFhPm%\
        2BKh4YblaIrOhFiAiEAy3SN%2FJ6WlWut%2F%2F43DRyRtStx5y9iWlo1lz3FS%2BiZ3wcq\
        %2FwMIRxAAGgw2Mzc0MjMxODM4MDUiDEsC2MB9WpYKdUualSrcA00wJv%2BqI%2B1m5MO7J\
        ONLFhlujut1NjyrtvQkxTlgle1gL%2BVY0Dz%2Fa5X2i0Y0P5orI4wn87NthrMkD%2FoSpY\
        be5K1PLGMZZ5T2WdSlKRqp%2FW55tGWmmqBiaVTP%2FJeI0SqO%2BvVgLKWFIoHUwiuQ5hG\
        CHqmhFByd6xhqof%2BHfIBUTjGkNknFFezKrIPxofTuiL1m5mK3ShxoWIoNV40U9H8q7Cx9\
        JZCY0W2vIGBZKhY%2Bvi5apHdRAkjak9AUbrSYdH6XOBz8w8xT5DtkfptFowmeoUhoN5hG%\
        2BE6%2F4RqwbVvDQ3wHoCy4Jnz86T0jnk%2FXpDHtmUmvIb30dJ91N44QLXerSJ%2F2qHny\
        sbXQI%2BEhrs3%2Blh7kTJPNehMYbOW9zbo%2BkcBNH2u8d9YqaWzn2GyzBG193xAgvq3ay\
        VT%2BblxPrmwvdQ07YdXdBAaIAHFsL2osDiEXNB0xwWLJJFdZ3S%2Buf33uM3wXx6%2F3sk\
        1LN5cZPpFr5sbHCCvyECFXkzEcIObHw1GYAngrx0gh5uwv2SiW6a22P7Zn1J1ZBqGchjDLp\
        tTX7dRX26zmXGTLEopnPfuu3OsGg9AvCH3z25ZHWe7f5DQAj%2FNNSI5GxrCZL8sGTR%2FZ\
        B6X9ih%2BOGPVNGPOtcwvxMP3Fwr0GOqUBAaFgrLZcH6abJcNYWmqWpc%2BX9X6eeNKLTmh\
        QHbTbuxqUI2Bm6Xt3Kv%2FgsCwEZk8LosZTJMmxSw392WkV21OQRdMPJHEHKG8ilx3%2F71\
        GfxF8BXqGFVm%2FZyiuGS0tIN6Vmqj11EYraPmftK%2F0Qt958FLDWmTrd4gcrX9KYjjD8q\
        H%2F9Dep8i7pvZA40QuqkYWka5krjq2wNNCBFmsj%2F9HymC9nBAzHy&X-Amz-Signature\
        =e389cd8e9d912d5d6ea36586376ab72eede5e95a230c3141196226e4f04a688c&X-Amz\
        -SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-15T16:21:36.566Z"
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
UPDATE_TIME: "2025-02-15T15:22:38.527Z"
EXPIRY_TIME: "2025-02-15T16:22:31.502Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663YFKJNTY%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T152231Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEB8aCXVzLXdlc3QtMiJHMEUCIBrLQ%2B%2FtOwmnSPX8LE0WDefXfgPHK4SmSsJcrtnjXGIqAiEAlhgDV%2FOhd5YJUiXR3DKfiz3EqRy46yB0A2uwEIqhnecq%2FwMIRxAAGgw2Mzc0MjMxODM4MDUiDBv3DE%2FFFi9T3flOzircA92E6GR5h4oSzJgiGDmLLQz6MoJutRogl5Cxbh42gg2v0Xqg7ymG%2BO5OXrs6vlkCNhhk8ejX172uHLjjTxUPzs6KsLS8zbwO%2BUjWNGylcSy7h1stxSY%2B3n32B9wPv3TQnhPaiXoR8xtkg1%2F9V2WGI9d1oZUt45t0sBOobk8CUYK1ItNM9eyEXzpK6HJa7fN0Ffovn1mVMIwJ1itWSJKflF%2FtSZsJluBb8SqMMiFYoS5ZmOlnEQY41%2Bu4Iqycf5fq8i3lCBizCrPxHXc5IizvlrUtQzIH5iQ%2FlfBC7C9GpmH%2BkGevQsItp9uXCa3NMTCwtvo0EWA4PtJY7%2FiFp25hVE%2Fy83g3mltB8uoJUs03%2BRonHJHvHfWZSrKb4tuu27xtLMx3ooule9z%2B5kW%2B8LAivtq89lTchs5dQMMAF%2FAJACWovhUfItvHis0xL60kxIvZSWTZs%2FN7M5paR6XAx6huT8b1Kw%2FlFMU26emd3ce8m4SDXkBJ6EdBm6m0XU1%2B%2BrvO7IJXyRjeYQkndOvWAJOQaey1yGSoCcq5GshR3aeAi8IZtrXg0BU1i11TJ3N6H8SvUNw8Onkl5z9NMWPKdiZ%2FLkFJEfjaAZTU9Sh5gwsFVpp7m9EqECQGna%2FN0CErMLjGwr0GOqUBr16p2CJ93oSLIUAT%2FX%2FZ6Ahd%2BKulN8TaVjtb88TeTD6o%2Fc%2FG40wJS1z%2BcHIXhGEvfEd7JskT7mLUmPySXu8XOGn5cWkBzuQ%2FEFc2qYzNISl6PrtImzrDNgptBOGgouInCFtspYoBko1bZ%2FNGf8wYEKYg%2BLCBSv1bp9INXA%2FHGn3w0J%2B31xvHmqOJ1tGXzwADX8YdCCxcEdNGHS58Jf6E2v%2FW8DRL&X-Amz-Signature=c587f1606de7db8fb6a36473e61e1f98533dace354be4dd58e0888a7708f6219&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663YFKJNTY%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T152231Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEB8aCXVzLXdlc3QtMiJHMEUCIBrLQ%2B%2FtOwmnSPX8LE0WDefXfgPHK4SmSsJcrtnjXGIqAiEAlhgDV%2FOhd5YJUiXR3DKfiz3EqRy46yB0A2uwEIqhnecq%2FwMIRxAAGgw2Mzc0MjMxODM4MDUiDBv3DE%2FFFi9T3flOzircA92E6GR5h4oSzJgiGDmLLQz6MoJutRogl5Cxbh42gg2v0Xqg7ymG%2BO5OXrs6vlkCNhhk8ejX172uHLjjTxUPzs6KsLS8zbwO%2BUjWNGylcSy7h1stxSY%2B3n32B9wPv3TQnhPaiXoR8xtkg1%2F9V2WGI9d1oZUt45t0sBOobk8CUYK1ItNM9eyEXzpK6HJa7fN0Ffovn1mVMIwJ1itWSJKflF%2FtSZsJluBb8SqMMiFYoS5ZmOlnEQY41%2Bu4Iqycf5fq8i3lCBizCrPxHXc5IizvlrUtQzIH5iQ%2FlfBC7C9GpmH%2BkGevQsItp9uXCa3NMTCwtvo0EWA4PtJY7%2FiFp25hVE%2Fy83g3mltB8uoJUs03%2BRonHJHvHfWZSrKb4tuu27xtLMx3ooule9z%2B5kW%2B8LAivtq89lTchs5dQMMAF%2FAJACWovhUfItvHis0xL60kxIvZSWTZs%2FN7M5paR6XAx6huT8b1Kw%2FlFMU26emd3ce8m4SDXkBJ6EdBm6m0XU1%2B%2BrvO7IJXyRjeYQkndOvWAJOQaey1yGSoCcq5GshR3aeAi8IZtrXg0BU1i11TJ3N6H8SvUNw8Onkl5z9NMWPKdiZ%2FLkFJEfjaAZTU9Sh5gwsFVpp7m9EqECQGna%2FN0CErMLjGwr0GOqUBr16p2CJ93oSLIUAT%2FX%2FZ6Ahd%2BKulN8TaVjtb88TeTD6o%2Fc%2FG40wJS1z%2BcHIXhGEvfEd7JskT7mLUmPySXu8XOGn5cWkBzuQ%2FEFc2qYzNISl6PrtImzrDNgptBOGgouInCFtspYoBko1bZ%2FNGf8wYEKYg%2BLCBSv1bp9INXA%2FHGn3w0J%2B31xvHmqOJ1tGXzwADX8YdCCxcEdNGHS58Jf6E2v%2FW8DRL&X-Amz-Signature=ef9bf1f0d283910f70e394ad4f4903c365f45b613747d75d556f487f42cce008&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663YFKJNTY%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T152231Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEB8aCXVzLXdlc3QtMiJHMEUCIBrLQ%2B%2FtOwmnSPX8LE0WDefXfgPHK4SmSsJcrtnjXGIqAiEAlhgDV%2FOhd5YJUiXR3DKfiz3EqRy46yB0A2uwEIqhnecq%2FwMIRxAAGgw2Mzc0MjMxODM4MDUiDBv3DE%2FFFi9T3flOzircA92E6GR5h4oSzJgiGDmLLQz6MoJutRogl5Cxbh42gg2v0Xqg7ymG%2BO5OXrs6vlkCNhhk8ejX172uHLjjTxUPzs6KsLS8zbwO%2BUjWNGylcSy7h1stxSY%2B3n32B9wPv3TQnhPaiXoR8xtkg1%2F9V2WGI9d1oZUt45t0sBOobk8CUYK1ItNM9eyEXzpK6HJa7fN0Ffovn1mVMIwJ1itWSJKflF%2FtSZsJluBb8SqMMiFYoS5ZmOlnEQY41%2Bu4Iqycf5fq8i3lCBizCrPxHXc5IizvlrUtQzIH5iQ%2FlfBC7C9GpmH%2BkGevQsItp9uXCa3NMTCwtvo0EWA4PtJY7%2FiFp25hVE%2Fy83g3mltB8uoJUs03%2BRonHJHvHfWZSrKb4tuu27xtLMx3ooule9z%2B5kW%2B8LAivtq89lTchs5dQMMAF%2FAJACWovhUfItvHis0xL60kxIvZSWTZs%2FN7M5paR6XAx6huT8b1Kw%2FlFMU26emd3ce8m4SDXkBJ6EdBm6m0XU1%2B%2BrvO7IJXyRjeYQkndOvWAJOQaey1yGSoCcq5GshR3aeAi8IZtrXg0BU1i11TJ3N6H8SvUNw8Onkl5z9NMWPKdiZ%2FLkFJEfjaAZTU9Sh5gwsFVpp7m9EqECQGna%2FN0CErMLjGwr0GOqUBr16p2CJ93oSLIUAT%2FX%2FZ6Ahd%2BKulN8TaVjtb88TeTD6o%2Fc%2FG40wJS1z%2BcHIXhGEvfEd7JskT7mLUmPySXu8XOGn5cWkBzuQ%2FEFc2qYzNISl6PrtImzrDNgptBOGgouInCFtspYoBko1bZ%2FNGf8wYEKYg%2BLCBSv1bp9INXA%2FHGn3w0J%2B31xvHmqOJ1tGXzwADX8YdCCxcEdNGHS58Jf6E2v%2FW8DRL&X-Amz-Signature=0e7221bd5e0aced487b4cc42f52082e10d08293ec70bfd391f0e3ef1546c9e43&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663YFKJNTY%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T152231Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEB8aCXVzLXdlc3QtMiJHMEUCIBrLQ%2B%2FtOwmnSPX8LE0WDefXfgPHK4SmSsJcrtnjXGIqAiEAlhgDV%2FOhd5YJUiXR3DKfiz3EqRy46yB0A2uwEIqhnecq%2FwMIRxAAGgw2Mzc0MjMxODM4MDUiDBv3DE%2FFFi9T3flOzircA92E6GR5h4oSzJgiGDmLLQz6MoJutRogl5Cxbh42gg2v0Xqg7ymG%2BO5OXrs6vlkCNhhk8ejX172uHLjjTxUPzs6KsLS8zbwO%2BUjWNGylcSy7h1stxSY%2B3n32B9wPv3TQnhPaiXoR8xtkg1%2F9V2WGI9d1oZUt45t0sBOobk8CUYK1ItNM9eyEXzpK6HJa7fN0Ffovn1mVMIwJ1itWSJKflF%2FtSZsJluBb8SqMMiFYoS5ZmOlnEQY41%2Bu4Iqycf5fq8i3lCBizCrPxHXc5IizvlrUtQzIH5iQ%2FlfBC7C9GpmH%2BkGevQsItp9uXCa3NMTCwtvo0EWA4PtJY7%2FiFp25hVE%2Fy83g3mltB8uoJUs03%2BRonHJHvHfWZSrKb4tuu27xtLMx3ooule9z%2B5kW%2B8LAivtq89lTchs5dQMMAF%2FAJACWovhUfItvHis0xL60kxIvZSWTZs%2FN7M5paR6XAx6huT8b1Kw%2FlFMU26emd3ce8m4SDXkBJ6EdBm6m0XU1%2B%2BrvO7IJXyRjeYQkndOvWAJOQaey1yGSoCcq5GshR3aeAi8IZtrXg0BU1i11TJ3N6H8SvUNw8Onkl5z9NMWPKdiZ%2FLkFJEfjaAZTU9Sh5gwsFVpp7m9EqECQGna%2FN0CErMLjGwr0GOqUBr16p2CJ93oSLIUAT%2FX%2FZ6Ahd%2BKulN8TaVjtb88TeTD6o%2Fc%2FG40wJS1z%2BcHIXhGEvfEd7JskT7mLUmPySXu8XOGn5cWkBzuQ%2FEFc2qYzNISl6PrtImzrDNgptBOGgouInCFtspYoBko1bZ%2FNGf8wYEKYg%2BLCBSv1bp9INXA%2FHGn3w0J%2B31xvHmqOJ1tGXzwADX8YdCCxcEdNGHS58Jf6E2v%2FW8DRL&X-Amz-Signature=34633acbbc310fa51d0c92bb65a0177db5d3a53228164cdee666bb7eed7f79de&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663YFKJNTY%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T152231Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEB8aCXVzLXdlc3QtMiJHMEUCIBrLQ%2B%2FtOwmnSPX8LE0WDefXfgPHK4SmSsJcrtnjXGIqAiEAlhgDV%2FOhd5YJUiXR3DKfiz3EqRy46yB0A2uwEIqhnecq%2FwMIRxAAGgw2Mzc0MjMxODM4MDUiDBv3DE%2FFFi9T3flOzircA92E6GR5h4oSzJgiGDmLLQz6MoJutRogl5Cxbh42gg2v0Xqg7ymG%2BO5OXrs6vlkCNhhk8ejX172uHLjjTxUPzs6KsLS8zbwO%2BUjWNGylcSy7h1stxSY%2B3n32B9wPv3TQnhPaiXoR8xtkg1%2F9V2WGI9d1oZUt45t0sBOobk8CUYK1ItNM9eyEXzpK6HJa7fN0Ffovn1mVMIwJ1itWSJKflF%2FtSZsJluBb8SqMMiFYoS5ZmOlnEQY41%2Bu4Iqycf5fq8i3lCBizCrPxHXc5IizvlrUtQzIH5iQ%2FlfBC7C9GpmH%2BkGevQsItp9uXCa3NMTCwtvo0EWA4PtJY7%2FiFp25hVE%2Fy83g3mltB8uoJUs03%2BRonHJHvHfWZSrKb4tuu27xtLMx3ooule9z%2B5kW%2B8LAivtq89lTchs5dQMMAF%2FAJACWovhUfItvHis0xL60kxIvZSWTZs%2FN7M5paR6XAx6huT8b1Kw%2FlFMU26emd3ce8m4SDXkBJ6EdBm6m0XU1%2B%2BrvO7IJXyRjeYQkndOvWAJOQaey1yGSoCcq5GshR3aeAi8IZtrXg0BU1i11TJ3N6H8SvUNw8Onkl5z9NMWPKdiZ%2FLkFJEfjaAZTU9Sh5gwsFVpp7m9EqECQGna%2FN0CErMLjGwr0GOqUBr16p2CJ93oSLIUAT%2FX%2FZ6Ahd%2BKulN8TaVjtb88TeTD6o%2Fc%2FG40wJS1z%2BcHIXhGEvfEd7JskT7mLUmPySXu8XOGn5cWkBzuQ%2FEFc2qYzNISl6PrtImzrDNgptBOGgouInCFtspYoBko1bZ%2FNGf8wYEKYg%2BLCBSv1bp9INXA%2FHGn3w0J%2B31xvHmqOJ1tGXzwADX8YdCCxcEdNGHS58Jf6E2v%2FW8DRL&X-Amz-Signature=9261e431ac0ace2a32101cc3b1f3ba51fba676641effd0eb6012a529c5bda101&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664GSVSMT6%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T152232Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEB8aCXVzLXdlc3QtMiJHMEUCICgmTYn3NBomiaD8nD2up8bzyqFELH%2FUYb14x91dKkq9AiEA77IOSgkbbFqy2kPtH5EpW0H%2BIPz93VxYzQWp0kUo3GAq%2FwMIRxAAGgw2Mzc0MjMxODM4MDUiDH6ndqu%2B6rA0JH1qISrcA6IPTrliKz8agUN6JTZ7qPuBlOdSTiM6rp%2FWdRzjCHp%2F63slxHVE1yJEZfa%2BMRgIfHrT2p3y394c%2F88yB8R29iSxuKR1yRop8WrjsxsOBxxn5KCNfKvO7GDZVNH0%2F9qtqfx2SJnIaPFPO0KddzScCGQzyoVTzJW6DFEttD9lSMT6QpcVrnIvEeZjADqZD%2Fc8ELGS2tYEQ29ACDTJEVXzVWAr%2FBHMSF%2Boi15OeAllFZG6roB%2FUaq2L7RkD4NlCpkLbwQuiyq6Oc1lgCx1l8VcopKWAT8KyYB3Ob4e%2BRMUs6rnhXs7VPioD0cwKVuJyYW8gAPu6c6wwlJ7EZUiIC2qV8hZMS4HbKXI1y9c9XrROP1DI%2FtzdxxyUIF4%2FZ7TVac2zpm5XQK1nAQhMgA2y4dqlpOGTf%2BMI9KE4K7IQ68cqN7E5Be4cjOgeRqQlMDhz9FSOLLFep%2FLBQJyFzuL7beu3KHBIJEX%2F6wTroW66wXzd9wI%2BHuHViVl7aUM2%2B%2BO55l%2BrSgVyv%2BM7aETLDXN2n%2FeOSMFxkGGkCNHaBfeirkTl4ca0mI8eTQ9jzldIRJPACQ4bGDpNX%2BITsYok38JMWMzlbFqewzKq3URlLLHuJf5Ymts%2BkEKTX0sZhN2ZYtrMPrFwr0GOqUB5GGmkVYYKTre9jGc0EheLtmVv%2Bm9%2Fld94yB215CqV3rrLuUQQ%2FsvfeYx21VS9uhFUSKZ3uKfej6uxFAJIhRd0BZ%2FLN5m8UwUlV%2FDTBfSYuQ7SX0GpsWBeZrPg7I2W%2F%2FxXRhabZtvfHhrFFExnh3A%2FNUgbiACyDM6wynwDwBKS4shkSRZae59kQRJNcvQ2pZCZgySvbX8jOAmWEfausgQcQXKyTJl&X-Amz-Signature=ed166630a3112ecc314d2b16b1d803b8eafd63d91d17c01d253153559bf80ba0&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z4MFPFVZ%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T152233Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEB8aCXVzLXdlc3QtMiJHMEUCIQDW%2BOyA5rEilfEBHFqEwHyGPhSu4AwwFR%2BFnX27nP2v5AIgcw8lqI8sWdDrdDLQxjsO6VLb0aEvdY0dk6OL%2B0SH9M8q%2FwMIRxAAGgw2Mzc0MjMxODM4MDUiDG9L8JldlTGlmdZ2dircA2jZq8G5eVIIMs9%2BlC4tiHG576N%2Brf3FUFVOUeJ8F1tnl5JVMXBkAMr7reO9MAzm1y1YMVyAUjWoa2tca%2FsqNp2zkeBaqUl1FHrrQxfG8Gqy0u0J8ruY7IfkBV%2BO6LWd7UYb5%2Ba%2FJea9ayh3NT1v8zd%2FITlTZjqBkl0ePplMLGY%2FFMBdPN%2BLWA1qNsuCbYFSTT%2BgO%2BhEtRmVeSo7JSUhKUsYoPkCZTDx9ANAv%2BnhdijGzfpcniKua%2Bs%2FTMmQxNgPXSUVZqftI6TSBRNT2D2wMy8%2B0%2FI2QFFVzTVLbyaBwtD%2B09igt0GncuPAY0beaJvqQAZD4HgoHM6%2B38bX6Sczw3oXTwybx9BCYajxe%2F33L6ai7lRy9mG6IrTFTT5JUWUiBCJGGJKJoFDlTmBB%2BCXxlbiFBmWy8bPkQXqaqkzS%2Bb2htYB4OJSjX6%2BuJQ9YyAHkN6MwrV9VHiFtOYwa3XCLcQ7ChVWxwpsv1K97271ZFMKVPyYFF5k6vxmyLTgu1OTCJTly1IiDxZOLROHN59973PLvoFuxxpRy8M6oqkqfPXFUpQrrxH%2FlMm2r7c0zaOLR3xQy8zpBUSMWuDT66Rydo3hwwryA0DIf8UqK3iRdzfszRuqUXGsbwIXEsowwMJDGwr0GOqUBXK6zRbgnkW6mOfY8vRHMlRL3n2YooiI%2F0YVqO2awF7x%2F58CNFv%2B7F%2B6CY2YRk4lfkqoejonKBFA6kQvCSvhBGJiQAc6lukmsy%2BoFj4d4GMNY3rzdTsJOZTZdDRc5XlPfyIqp3i9PgUQAQ5M5rE7D3xRL4GS6iexJACEuYBM2HmfWG68rZ%2FMdEt1uVcDtu7zCu6eo1FusgSFFXYQtLpo%2BShU1GFPt&X-Amz-Signature=ecf08d219213c66ae306d0f3c28eb0346af93ac39e0c6b17d7c78d47fd579f79&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663YFKJNTY%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T152231Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEB8aCXVzLXdlc3QtMiJHMEUCIBrLQ%2B%2FtOwmnSPX8LE0WDefXfgPHK4SmSsJcrtnjXGIqAiEAlhgDV%2FOhd5YJUiXR3DKfiz3EqRy46yB0A2uwEIqhnecq%2FwMIRxAAGgw2Mzc0MjMxODM4MDUiDBv3DE%2FFFi9T3flOzircA92E6GR5h4oSzJgiGDmLLQz6MoJutRogl5Cxbh42gg2v0Xqg7ymG%2BO5OXrs6vlkCNhhk8ejX172uHLjjTxUPzs6KsLS8zbwO%2BUjWNGylcSy7h1stxSY%2B3n32B9wPv3TQnhPaiXoR8xtkg1%2F9V2WGI9d1oZUt45t0sBOobk8CUYK1ItNM9eyEXzpK6HJa7fN0Ffovn1mVMIwJ1itWSJKflF%2FtSZsJluBb8SqMMiFYoS5ZmOlnEQY41%2Bu4Iqycf5fq8i3lCBizCrPxHXc5IizvlrUtQzIH5iQ%2FlfBC7C9GpmH%2BkGevQsItp9uXCa3NMTCwtvo0EWA4PtJY7%2FiFp25hVE%2Fy83g3mltB8uoJUs03%2BRonHJHvHfWZSrKb4tuu27xtLMx3ooule9z%2B5kW%2B8LAivtq89lTchs5dQMMAF%2FAJACWovhUfItvHis0xL60kxIvZSWTZs%2FN7M5paR6XAx6huT8b1Kw%2FlFMU26emd3ce8m4SDXkBJ6EdBm6m0XU1%2B%2BrvO7IJXyRjeYQkndOvWAJOQaey1yGSoCcq5GshR3aeAi8IZtrXg0BU1i11TJ3N6H8SvUNw8Onkl5z9NMWPKdiZ%2FLkFJEfjaAZTU9Sh5gwsFVpp7m9EqECQGna%2FN0CErMLjGwr0GOqUBr16p2CJ93oSLIUAT%2FX%2FZ6Ahd%2BKulN8TaVjtb88TeTD6o%2Fc%2FG40wJS1z%2BcHIXhGEvfEd7JskT7mLUmPySXu8XOGn5cWkBzuQ%2FEFc2qYzNISl6PrtImzrDNgptBOGgouInCFtspYoBko1bZ%2FNGf8wYEKYg%2BLCBSv1bp9INXA%2FHGn3w0J%2B31xvHmqOJ1tGXzwADX8YdCCxcEdNGHS58Jf6E2v%2FW8DRL&X-Amz-Signature=2e0f76e3a1c95ce744cec4fa1eebe944e2d6a6a9b46b597ed78b8c89cb10fe67&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663YFKJNTY%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T152231Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEB8aCXVzLXdlc3QtMiJHMEUCIBrLQ%2B%2FtOwmnSPX8LE0WDefXfgPHK4SmSsJcrtnjXGIqAiEAlhgDV%2FOhd5YJUiXR3DKfiz3EqRy46yB0A2uwEIqhnecq%2FwMIRxAAGgw2Mzc0MjMxODM4MDUiDBv3DE%2FFFi9T3flOzircA92E6GR5h4oSzJgiGDmLLQz6MoJutRogl5Cxbh42gg2v0Xqg7ymG%2BO5OXrs6vlkCNhhk8ejX172uHLjjTxUPzs6KsLS8zbwO%2BUjWNGylcSy7h1stxSY%2B3n32B9wPv3TQnhPaiXoR8xtkg1%2F9V2WGI9d1oZUt45t0sBOobk8CUYK1ItNM9eyEXzpK6HJa7fN0Ffovn1mVMIwJ1itWSJKflF%2FtSZsJluBb8SqMMiFYoS5ZmOlnEQY41%2Bu4Iqycf5fq8i3lCBizCrPxHXc5IizvlrUtQzIH5iQ%2FlfBC7C9GpmH%2BkGevQsItp9uXCa3NMTCwtvo0EWA4PtJY7%2FiFp25hVE%2Fy83g3mltB8uoJUs03%2BRonHJHvHfWZSrKb4tuu27xtLMx3ooule9z%2B5kW%2B8LAivtq89lTchs5dQMMAF%2FAJACWovhUfItvHis0xL60kxIvZSWTZs%2FN7M5paR6XAx6huT8b1Kw%2FlFMU26emd3ce8m4SDXkBJ6EdBm6m0XU1%2B%2BrvO7IJXyRjeYQkndOvWAJOQaey1yGSoCcq5GshR3aeAi8IZtrXg0BU1i11TJ3N6H8SvUNw8Onkl5z9NMWPKdiZ%2FLkFJEfjaAZTU9Sh5gwsFVpp7m9EqECQGna%2FN0CErMLjGwr0GOqUBr16p2CJ93oSLIUAT%2FX%2FZ6Ahd%2BKulN8TaVjtb88TeTD6o%2Fc%2FG40wJS1z%2BcHIXhGEvfEd7JskT7mLUmPySXu8XOGn5cWkBzuQ%2FEFc2qYzNISl6PrtImzrDNgptBOGgouInCFtspYoBko1bZ%2FNGf8wYEKYg%2BLCBSv1bp9INXA%2FHGn3w0J%2B31xvHmqOJ1tGXzwADX8YdCCxcEdNGHS58Jf6E2v%2FW8DRL&X-Amz-Signature=2d6c2bc0476e8e6732f4bc84697b3132593669f997b1001b41f9f098be88e241&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663YFKJNTY%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T152231Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEB8aCXVzLXdlc3QtMiJHMEUCIBrLQ%2B%2FtOwmnSPX8LE0WDefXfgPHK4SmSsJcrtnjXGIqAiEAlhgDV%2FOhd5YJUiXR3DKfiz3EqRy46yB0A2uwEIqhnecq%2FwMIRxAAGgw2Mzc0MjMxODM4MDUiDBv3DE%2FFFi9T3flOzircA92E6GR5h4oSzJgiGDmLLQz6MoJutRogl5Cxbh42gg2v0Xqg7ymG%2BO5OXrs6vlkCNhhk8ejX172uHLjjTxUPzs6KsLS8zbwO%2BUjWNGylcSy7h1stxSY%2B3n32B9wPv3TQnhPaiXoR8xtkg1%2F9V2WGI9d1oZUt45t0sBOobk8CUYK1ItNM9eyEXzpK6HJa7fN0Ffovn1mVMIwJ1itWSJKflF%2FtSZsJluBb8SqMMiFYoS5ZmOlnEQY41%2Bu4Iqycf5fq8i3lCBizCrPxHXc5IizvlrUtQzIH5iQ%2FlfBC7C9GpmH%2BkGevQsItp9uXCa3NMTCwtvo0EWA4PtJY7%2FiFp25hVE%2Fy83g3mltB8uoJUs03%2BRonHJHvHfWZSrKb4tuu27xtLMx3ooule9z%2B5kW%2B8LAivtq89lTchs5dQMMAF%2FAJACWovhUfItvHis0xL60kxIvZSWTZs%2FN7M5paR6XAx6huT8b1Kw%2FlFMU26emd3ce8m4SDXkBJ6EdBm6m0XU1%2B%2BrvO7IJXyRjeYQkndOvWAJOQaey1yGSoCcq5GshR3aeAi8IZtrXg0BU1i11TJ3N6H8SvUNw8Onkl5z9NMWPKdiZ%2FLkFJEfjaAZTU9Sh5gwsFVpp7m9EqECQGna%2FN0CErMLjGwr0GOqUBr16p2CJ93oSLIUAT%2FX%2FZ6Ahd%2BKulN8TaVjtb88TeTD6o%2Fc%2FG40wJS1z%2BcHIXhGEvfEd7JskT7mLUmPySXu8XOGn5cWkBzuQ%2FEFc2qYzNISl6PrtImzrDNgptBOGgouInCFtspYoBko1bZ%2FNGf8wYEKYg%2BLCBSv1bp9INXA%2FHGn3w0J%2B31xvHmqOJ1tGXzwADX8YdCCxcEdNGHS58Jf6E2v%2FW8DRL&X-Amz-Signature=caaa22fe561bc54226b9a37306d68e1115df77d412d46fde4fa6d8a884e1e0bc&X-Amz-SignedHeaders=host&x-id=GetObject)


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

