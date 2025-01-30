---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4663A62A5NQ%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250130T072042Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEJb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDDGKWLeE237cn7qYz\
  Q2wmeaJs%2Ba6oCV3PMyMdqrNuefAIhALyEzoA4bUc8I%2BTBk%2BXQ2oPpSY5ZdFMAJJNj6kT8Hk\
  O%2FKogECJ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igy0pOkd3Op\
  A6PBLPE0q3AO2AmIt2UjwH9wY3fVLJX2u47IENbwZ05TN8yhS0B%2FzsVCPUvZfLJjG7q7fUlVRl4\
  3N8mGJY%2FO%2B0cmfZ2dzeGlwFOmNNfar1BPha9FYo0GUcPcUqnSAqTi%2B3Djod18%2Fkt0XZDY\
  oIF1AYIR%2FWn%2B8ZXnR8lJjSiC7t5kSgIVZfhzwOYBHtlAOe9F%2FLk7RLPRXZYdB8JGpm6opYM\
  dy3amwliTZWQwliBs1Xm3wXzsxmgEDF%2Bshsr8IhXFZ9dVmhcHRTenHgiaQfU%2FtvwyQL7gZuou\
  3wU9rdDLIlY6ZZqtxOvfD8ZckumU4KB9nXwpntKMZM5%2BUHvZ%2BfFbKecyquandT%2F5Mo9EeoZ\
  ZiXhWobQlfpGVVI9jmw4sflbfp7TXQAsUCIuvIjpsdvM44e%2FHTVpxlAOw7noNBn5fFLAhvQ0Wre\
  TD%2FVQA%2Fi%2FdFLj8CI3BI7eFEvEElAIfNtvxHimsWzqIQNRSaoV9EthHvn3%2BRF5XR4hjTmA\
  iHIThqcM5hlZyFDWzVjQZa98TERGjVHs1UxFl1Af3ZM9sKQkQanBJovlpJhvpaQdfS78wuCTW%2BQ\
  V6xFb1uiJOcOOnTvi5lzxMVub1CflW7T0szxNvwkg5BQhU%2FLGWoZd5N5nbT6NUvU5TPWTDeo%2B\
  y8BjqkAQB1qBdv29P5ExmKDnw%2Fa1vjpG3t6zb77ZTFci6UmwyPBrX1e2RKtPCY3jddxALdHhAF6\
  kGNJrLCUOiOLhnb1UbvHRrp4XlMs4bQlgzXZOFfKKqWLgZpCWNfShMYy9AhupTmjHj8DlGcd22B%2\
  FEE3F1w5wjfd3rbt4VJMd10y%2FFhumG%2Fatd1gcT0PQvpwmTz139PzIeGQxPFEuG7ryafjTvMJt\
  z8R&X-Amz-Signature=8a8b1a402670a330139a7838361586be0add419c6bbd56101129358aa\
  202b910&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466UJKT57HE%2F20250130%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250130T071932Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEJb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQ\
        CIC55p2SYkqbLqYTvcijdOqSm0HO2NRdTIwc%2FIaa5Nl87AiBOeoRBANJd0YGqdENLSvPM\
        zLz%2FKqME7W1V2ld0UZhEPSqIBAif%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzN\
        zQyMzE4MzgwNSIMETF%2FUGmz4rnLgtgaKtwDLKNNzpNUgpx%2F5ZgdP75W7VYwEhfTYafb\
        %2BHJsuKTDsRTlP8IGnwli1L%2Fqooab8st584MCohFvuGS4yVkyFvCCgpoHZn%2F3nvSLR\
        QJ4S768ZI8qFHgXXtaksVSjJSlpMu2HhRfXDrzdSa3m7Hlotni5pfus8LFQttA%2FzinbOi\
        npddESTZ7%2Fq8i61Jo8k40%2F19%2F48WDeHN7G6mBTlpo1qRJMRsI37KPNBa8pUKhY89d\
        VXQK7b1DE4pqvap9xXmfU1yt05ZryIvCRx8e1XPNltEcT4fcyCIMxQocoyj2PoPKradVDuA\
        ZPOim%2FTwek6UsWPN0HNG%2BLwQTpdhQfwjMeXNexFMK4E11Mhtwn0EI3rT6dWDCM4ctev\
        ILlZWmDycAZOq63liVaZhhJniON%2FusCa6lHMN%2F6mseC1qrILln28PsXnfe6WR%2FTEL\
        soorIwx9Xy%2B%2Bcnk2kICS7oA9Badrhxm6LmAj06fWpQbBtAOm%2FGiUoceKR5v0xwUwa\
        d89cSEJJfHx2aOuIpf%2F6a0TM3mB5UZwn0sYFlvStgf8QB8%2F4df5oMW4oIPLYOr8kRrT\
        wZGHe2aF9CZnuW9Qsh3f%2Brz14jKinhHx6nxJsFPOWgOEBARUUUOU6tg3wKti8qOwcYnUA\
        wp6TsvAY6pgHoaKaNoVAAVMvt%2BAEhZ5rwDF42XT0ZQ94%2Fhmr2ju%2F%2FuCD7BlZ6OQ\
        vlV0iWPHEnbMZSpQiIlE9YeAaUScIJgH25GXwsOG0N3I9CYjVih2nHOqESzA5QA8Due%2Bz\
        %2FeibnoOzMVhtR0XwwbG1M3ah%2BOn6AIX2myhr%2Bg3KeNP4KgAb4PSnUMGiqfBCMJROt\
        dOjhCzkiU3IyEhZzlk9YGd9AjJixzvdD%2Fuak&X-Amz-Signature=4a15bbcd7fd2f98f\
        0826b65b4022b4b2630e51294e8c0e5034e3ba37b20b7655&X-Amz-SignedHeaders=ho\
        st&x-id=GetObject"
      expiry_time: "2025-01-30T08:19:31.979Z"
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
UPDATE_TIME: "2025-01-30T07:20:53.650Z"
EXPIRY_TIME: "2025-01-30T08:20:40.740Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QKKEVPO7%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T072041Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCUxE79ZmOZpfvUTyXjxBjHwgH%2BsXP%2FtgbdH6c2o%2FKVMwIgHi2xJbnUnvQ7sZ7xlYpQ8XlNKJ6%2FxfifEZoW5k19b4QqiAQIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNTDF%2BZ%2FdBWD8BRLzircAyjZ9wSyv37IDo8NKl3p5SQraChbPMitvT9BrDox3mrX%2Bids25AdZxAQlYBYksagvUlP1sCZR8TPp37U3QcsQ2UGxGAOdABT48NPyrrCyV7nvrn2LACUEzQ8q4nKlllYujCsbZyKkcoOrRvHF9wJNo%2FGcR3W2mA38TA3thvc8v%2FMmpCmCHLYh1sLTBXpkB6J7sSOakQPGdcXO%2FVhZOJh40Q0E6PiF8buc3P9C5FMQOoK1pLs%2BA%2FKSd%2BQNkYTZgjzPgnTs5hyW%2FrgLilRBmZCbSBVe%2BtMXDRMMO%2BkrsXFWuXXkBfa1di%2BxiyFcd4Zl0TiizJd8WGb3h0r12jPHFApTrNAUCqYPZhEc8hlfFIlsTLPAXU1ZtSLp%2BQi7mOHkWkzBEx3g3qyYgQJAHwp7XxKnVlA47IDR%2Frort7jWqTVmaXV6V3FRWoGTFaVAtsC79w9g4mv3H6iPoswEkj4xjsZpXnc04kzDPhLrPZkYZjb%2Fd2qS4OgIWdkTHiwoyU5sNEcmBzvlmdxp9%2BXPwDENyauY670mvcfdXOYRHBGmAGb3Wcqwj0RhpAX8Sxs5eFllRZhNkOyVD7%2F0GGd%2FcU23a%2FIdDPYvbHOvjt%2Fbou52VmlqK1YL5azNMz5J1UECmr8MKmk7LwGOqUBscsdJX0y8iHtNWcAuSNdGZjwqrfeSMh1bfzMOAb5NxmScawwq2%2FFAbI2zCq7Gwu2YHbd3d9zb2pwb%2Fxdpm%2BJ08qrYj13Ur0knOSg%2Fo5be38tk4dVoDAAycwzbbovsqkRsIBEIOrU7TJpKpmTyrFzWEm2UcfSQSS7OZ7suwh76vpZWlmp5ES8daYhTooHGFbEf8kMAC7%2BM2YUMK3PyIvT2e1faaw4&X-Amz-Signature=1c0f27652400f8b695cc8a678fa301506c03cb00e65768cd195e9f5fe2833ef4&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QKKEVPO7%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T072041Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCUxE79ZmOZpfvUTyXjxBjHwgH%2BsXP%2FtgbdH6c2o%2FKVMwIgHi2xJbnUnvQ7sZ7xlYpQ8XlNKJ6%2FxfifEZoW5k19b4QqiAQIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNTDF%2BZ%2FdBWD8BRLzircAyjZ9wSyv37IDo8NKl3p5SQraChbPMitvT9BrDox3mrX%2Bids25AdZxAQlYBYksagvUlP1sCZR8TPp37U3QcsQ2UGxGAOdABT48NPyrrCyV7nvrn2LACUEzQ8q4nKlllYujCsbZyKkcoOrRvHF9wJNo%2FGcR3W2mA38TA3thvc8v%2FMmpCmCHLYh1sLTBXpkB6J7sSOakQPGdcXO%2FVhZOJh40Q0E6PiF8buc3P9C5FMQOoK1pLs%2BA%2FKSd%2BQNkYTZgjzPgnTs5hyW%2FrgLilRBmZCbSBVe%2BtMXDRMMO%2BkrsXFWuXXkBfa1di%2BxiyFcd4Zl0TiizJd8WGb3h0r12jPHFApTrNAUCqYPZhEc8hlfFIlsTLPAXU1ZtSLp%2BQi7mOHkWkzBEx3g3qyYgQJAHwp7XxKnVlA47IDR%2Frort7jWqTVmaXV6V3FRWoGTFaVAtsC79w9g4mv3H6iPoswEkj4xjsZpXnc04kzDPhLrPZkYZjb%2Fd2qS4OgIWdkTHiwoyU5sNEcmBzvlmdxp9%2BXPwDENyauY670mvcfdXOYRHBGmAGb3Wcqwj0RhpAX8Sxs5eFllRZhNkOyVD7%2F0GGd%2FcU23a%2FIdDPYvbHOvjt%2Fbou52VmlqK1YL5azNMz5J1UECmr8MKmk7LwGOqUBscsdJX0y8iHtNWcAuSNdGZjwqrfeSMh1bfzMOAb5NxmScawwq2%2FFAbI2zCq7Gwu2YHbd3d9zb2pwb%2Fxdpm%2BJ08qrYj13Ur0knOSg%2Fo5be38tk4dVoDAAycwzbbovsqkRsIBEIOrU7TJpKpmTyrFzWEm2UcfSQSS7OZ7suwh76vpZWlmp5ES8daYhTooHGFbEf8kMAC7%2BM2YUMK3PyIvT2e1faaw4&X-Amz-Signature=5310e038840c6fc6b62f323e58d84c92c1318fee1d53b68748c978cef56430a7&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QKKEVPO7%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T072041Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCUxE79ZmOZpfvUTyXjxBjHwgH%2BsXP%2FtgbdH6c2o%2FKVMwIgHi2xJbnUnvQ7sZ7xlYpQ8XlNKJ6%2FxfifEZoW5k19b4QqiAQIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNTDF%2BZ%2FdBWD8BRLzircAyjZ9wSyv37IDo8NKl3p5SQraChbPMitvT9BrDox3mrX%2Bids25AdZxAQlYBYksagvUlP1sCZR8TPp37U3QcsQ2UGxGAOdABT48NPyrrCyV7nvrn2LACUEzQ8q4nKlllYujCsbZyKkcoOrRvHF9wJNo%2FGcR3W2mA38TA3thvc8v%2FMmpCmCHLYh1sLTBXpkB6J7sSOakQPGdcXO%2FVhZOJh40Q0E6PiF8buc3P9C5FMQOoK1pLs%2BA%2FKSd%2BQNkYTZgjzPgnTs5hyW%2FrgLilRBmZCbSBVe%2BtMXDRMMO%2BkrsXFWuXXkBfa1di%2BxiyFcd4Zl0TiizJd8WGb3h0r12jPHFApTrNAUCqYPZhEc8hlfFIlsTLPAXU1ZtSLp%2BQi7mOHkWkzBEx3g3qyYgQJAHwp7XxKnVlA47IDR%2Frort7jWqTVmaXV6V3FRWoGTFaVAtsC79w9g4mv3H6iPoswEkj4xjsZpXnc04kzDPhLrPZkYZjb%2Fd2qS4OgIWdkTHiwoyU5sNEcmBzvlmdxp9%2BXPwDENyauY670mvcfdXOYRHBGmAGb3Wcqwj0RhpAX8Sxs5eFllRZhNkOyVD7%2F0GGd%2FcU23a%2FIdDPYvbHOvjt%2Fbou52VmlqK1YL5azNMz5J1UECmr8MKmk7LwGOqUBscsdJX0y8iHtNWcAuSNdGZjwqrfeSMh1bfzMOAb5NxmScawwq2%2FFAbI2zCq7Gwu2YHbd3d9zb2pwb%2Fxdpm%2BJ08qrYj13Ur0knOSg%2Fo5be38tk4dVoDAAycwzbbovsqkRsIBEIOrU7TJpKpmTyrFzWEm2UcfSQSS7OZ7suwh76vpZWlmp5ES8daYhTooHGFbEf8kMAC7%2BM2YUMK3PyIvT2e1faaw4&X-Amz-Signature=009bcd6a6e7b8cfa328ef082b7ac6db8c2832e15cdfec95eee21ed73c1fd3309&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QKKEVPO7%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T072041Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCUxE79ZmOZpfvUTyXjxBjHwgH%2BsXP%2FtgbdH6c2o%2FKVMwIgHi2xJbnUnvQ7sZ7xlYpQ8XlNKJ6%2FxfifEZoW5k19b4QqiAQIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNTDF%2BZ%2FdBWD8BRLzircAyjZ9wSyv37IDo8NKl3p5SQraChbPMitvT9BrDox3mrX%2Bids25AdZxAQlYBYksagvUlP1sCZR8TPp37U3QcsQ2UGxGAOdABT48NPyrrCyV7nvrn2LACUEzQ8q4nKlllYujCsbZyKkcoOrRvHF9wJNo%2FGcR3W2mA38TA3thvc8v%2FMmpCmCHLYh1sLTBXpkB6J7sSOakQPGdcXO%2FVhZOJh40Q0E6PiF8buc3P9C5FMQOoK1pLs%2BA%2FKSd%2BQNkYTZgjzPgnTs5hyW%2FrgLilRBmZCbSBVe%2BtMXDRMMO%2BkrsXFWuXXkBfa1di%2BxiyFcd4Zl0TiizJd8WGb3h0r12jPHFApTrNAUCqYPZhEc8hlfFIlsTLPAXU1ZtSLp%2BQi7mOHkWkzBEx3g3qyYgQJAHwp7XxKnVlA47IDR%2Frort7jWqTVmaXV6V3FRWoGTFaVAtsC79w9g4mv3H6iPoswEkj4xjsZpXnc04kzDPhLrPZkYZjb%2Fd2qS4OgIWdkTHiwoyU5sNEcmBzvlmdxp9%2BXPwDENyauY670mvcfdXOYRHBGmAGb3Wcqwj0RhpAX8Sxs5eFllRZhNkOyVD7%2F0GGd%2FcU23a%2FIdDPYvbHOvjt%2Fbou52VmlqK1YL5azNMz5J1UECmr8MKmk7LwGOqUBscsdJX0y8iHtNWcAuSNdGZjwqrfeSMh1bfzMOAb5NxmScawwq2%2FFAbI2zCq7Gwu2YHbd3d9zb2pwb%2Fxdpm%2BJ08qrYj13Ur0knOSg%2Fo5be38tk4dVoDAAycwzbbovsqkRsIBEIOrU7TJpKpmTyrFzWEm2UcfSQSS7OZ7suwh76vpZWlmp5ES8daYhTooHGFbEf8kMAC7%2BM2YUMK3PyIvT2e1faaw4&X-Amz-Signature=37c3046407cc2a6d28e85d5bdddaff6df63290970ba672930226dbc975cdf17f&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QKKEVPO7%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T072041Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCUxE79ZmOZpfvUTyXjxBjHwgH%2BsXP%2FtgbdH6c2o%2FKVMwIgHi2xJbnUnvQ7sZ7xlYpQ8XlNKJ6%2FxfifEZoW5k19b4QqiAQIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNTDF%2BZ%2FdBWD8BRLzircAyjZ9wSyv37IDo8NKl3p5SQraChbPMitvT9BrDox3mrX%2Bids25AdZxAQlYBYksagvUlP1sCZR8TPp37U3QcsQ2UGxGAOdABT48NPyrrCyV7nvrn2LACUEzQ8q4nKlllYujCsbZyKkcoOrRvHF9wJNo%2FGcR3W2mA38TA3thvc8v%2FMmpCmCHLYh1sLTBXpkB6J7sSOakQPGdcXO%2FVhZOJh40Q0E6PiF8buc3P9C5FMQOoK1pLs%2BA%2FKSd%2BQNkYTZgjzPgnTs5hyW%2FrgLilRBmZCbSBVe%2BtMXDRMMO%2BkrsXFWuXXkBfa1di%2BxiyFcd4Zl0TiizJd8WGb3h0r12jPHFApTrNAUCqYPZhEc8hlfFIlsTLPAXU1ZtSLp%2BQi7mOHkWkzBEx3g3qyYgQJAHwp7XxKnVlA47IDR%2Frort7jWqTVmaXV6V3FRWoGTFaVAtsC79w9g4mv3H6iPoswEkj4xjsZpXnc04kzDPhLrPZkYZjb%2Fd2qS4OgIWdkTHiwoyU5sNEcmBzvlmdxp9%2BXPwDENyauY670mvcfdXOYRHBGmAGb3Wcqwj0RhpAX8Sxs5eFllRZhNkOyVD7%2F0GGd%2FcU23a%2FIdDPYvbHOvjt%2Fbou52VmlqK1YL5azNMz5J1UECmr8MKmk7LwGOqUBscsdJX0y8iHtNWcAuSNdGZjwqrfeSMh1bfzMOAb5NxmScawwq2%2FFAbI2zCq7Gwu2YHbd3d9zb2pwb%2Fxdpm%2BJ08qrYj13Ur0knOSg%2Fo5be38tk4dVoDAAycwzbbovsqkRsIBEIOrU7TJpKpmTyrFzWEm2UcfSQSS7OZ7suwh76vpZWlmp5ES8daYhTooHGFbEf8kMAC7%2BM2YUMK3PyIvT2e1faaw4&X-Amz-Signature=7ca114e72817cf2f11bdee88ca17884d5dc17f5e97d7e22bb2cb8d2bef6c5ade&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RYZX2X35%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T072041Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCiv7kp4xSow56SnX%2B1BQWkQbfQVpq%2B6J9r6YX9tjzN1gIga6TtGt7t2w6SPJtGIZr4W047qhmCdvLCkniF55TpXS4qiAQIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDL%2F8O3TzW9v%2BZnUFAyrcAz68I48VGU5eh%2F73ZpLobRDl%2FzQiSYKnu2Krws%2Bqxn8uhY%2FxpjQoqaDW7c%2FEZu8%2F%2BsngkxKHtAMe3bHC2aDgiyJVISgZLXDCz1cuc8lhSrid%2BC3%2FA0RFdDDw%2FcO%2FCjicBpnE7FQdzTpdl3VN19WksT9KxNE3gTR8jnwNjzG5ZyRxiBgm1Bs4nuVQ5kA8Odeg42To2CXH7RCwzsb4M0cYQ6HV68cqE%2FrvmbG%2ByJOx3KrckeA2oXJp84T2ZIX633z079YY3C%2FgOmOrapOrIXgSkZ5BJIQUvX8hoL7ic3Fj6fFYSbihNqFLbbNcSEO%2F%2BAOxhim26TPEjd6eJWN1ykswHlEArMUokfqqIP7ixrLTA0ec1p5V8eFw8QIVPug%2FsFv%2BGTf0PGCoP4NCGxl%2Fg1iNFEK8Twnrl8ioH70WREF%2FIYSXMz6WGZUFsrWKwJkJR8tyhHa5WwLKfwTziyku21tgrRMrCFAj4CLZMbujzecaoRNZRhJpF6DYW4nO%2Fc5jZfRZ7WZunYRUQmdCKiie9AN%2BFJZVvhm1fQqmln5nBBrftws1FkDOXhpn0MI0RxksS%2Fe3e3cq3x2ODvl4DD9q%2BimnJPkU8v%2Bxb%2FmPsMsWPSQmlHlPyfykeTTegpcS44U3MKmk7LwGOqUBNZXUROvhU9FrFAM7NsybUctk2TMT4NtXd1q68G0q1baJ2sCGMSqvQzzJUb1qEU4K89KryQ4rPOMgtkVz8dy8PzGBJxMz2lXSItCm9JsRXQ%2F%2FH%2B7tERFsjPF6sjjNZtbrhBEOWch6araYbFG%2BMR7lMRFG1o0TfV4W75KDYL31J4JhnZ45Ct7F0riuhBSZsRYcTzHmDEYrPA4qUB6l9gWyieteiz4h&X-Amz-Signature=581ddf574745afd0a6c9581418b6c51a4177deeddd9e71adec96b65cffd3ca88&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XN3YHPDG%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T072042Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCID0C%2BCR8B0K4COdylihR2phaSwfTKt83%2FFZet1Kwtr1LAiBCDlOHjH4w9wZkBHBh5Xw49JRTE1T2nclW01LfuMFe%2BCqIBAif%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMKmdhF8SA%2BQbdrZzsKtwDn26MYLFZlAiOrpUEuOmfXBWP4kXa2hatmc4GrE%2Bc1egTMQ7H34cHJCuJnxl%2F2YSvR1fuknxRk57HVM1X7QZicVPa%2FsKf0%2B4kFS5E9UdbJJlgkTU02gPuGbhgPjJgqxq1aND%2BkZXyjS7phbhRLSl5ezp%2FO8%2BXerpp0PHmDrMinD2f2JQC7H2RgQAYXUkVR0N9Jhm09Rzam2b1W%2Ft3sb%2FFnRlyexp%2F%2BIhw3o9iZSzSi5YcJJn%2FiyLdeEtZu%2FrHE8nWJlXNFPUmvdMbmX62ig55wtF3VOlOUKB6bSypn1Rg3Q0qEOI5PP7hJi3xCseIf%2FVTz5noEHgCh3OQyGlX1iTJWyr1vY%2BlSZlosrMce8QJGUxbtyUM19vQ7sVIihsbxoHkjyTqpadmfSUYjS6dv1IOR1KsZGpjm%2FZcU5rV5y%2BVD%2F3QBOEhv4Z9hq6z%2FPA6WgygOcVRkBXOv5%2FofBhWmhaHYTRAbLLPjufQeT%2BqE5HoywbKVIQGi0ln3hzSHhS5Ep7O%2FDfkWN4%2FKxRHQZ7Jru920RnCH1%2FrdESNohq4MOhBORVqjQ%2F7BIhlUza5Mlqr0bqxnXLpa49XFiRdiGst0Q51XfbbX%2FrhT6ydhsHYDYNQBot8AoRHNRJc1pn0X30w7KPsvAY6pgHNGEuwxLJPpeBbJx6fIoxe5nU6wZG0PqVw4UIOI%2B2y3YDVg%2FknWbLTIFeWEJDv3qt2Mry2bcFpXbbnrwU%2FF%2FAChhsORaA320YfwZXh1HEC%2F2gWvF2Bu5lvhOb6Y2EK%2FaEiUC0w6dX7hTUCq%2BRRKJna%2BZ9bhAhvHpUB8DN0xO02%2Fhxtv1LgyrQ2FtQasfc7hXHCulJSG25txHl3FwMzPwMKCNb9uNqL&X-Amz-Signature=8caf8b5a8a2054c0c486ecab0f7df47a71449d79bc10317f9b8eafc5be72a4c9&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QKKEVPO7%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T072041Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCUxE79ZmOZpfvUTyXjxBjHwgH%2BsXP%2FtgbdH6c2o%2FKVMwIgHi2xJbnUnvQ7sZ7xlYpQ8XlNKJ6%2FxfifEZoW5k19b4QqiAQIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNTDF%2BZ%2FdBWD8BRLzircAyjZ9wSyv37IDo8NKl3p5SQraChbPMitvT9BrDox3mrX%2Bids25AdZxAQlYBYksagvUlP1sCZR8TPp37U3QcsQ2UGxGAOdABT48NPyrrCyV7nvrn2LACUEzQ8q4nKlllYujCsbZyKkcoOrRvHF9wJNo%2FGcR3W2mA38TA3thvc8v%2FMmpCmCHLYh1sLTBXpkB6J7sSOakQPGdcXO%2FVhZOJh40Q0E6PiF8buc3P9C5FMQOoK1pLs%2BA%2FKSd%2BQNkYTZgjzPgnTs5hyW%2FrgLilRBmZCbSBVe%2BtMXDRMMO%2BkrsXFWuXXkBfa1di%2BxiyFcd4Zl0TiizJd8WGb3h0r12jPHFApTrNAUCqYPZhEc8hlfFIlsTLPAXU1ZtSLp%2BQi7mOHkWkzBEx3g3qyYgQJAHwp7XxKnVlA47IDR%2Frort7jWqTVmaXV6V3FRWoGTFaVAtsC79w9g4mv3H6iPoswEkj4xjsZpXnc04kzDPhLrPZkYZjb%2Fd2qS4OgIWdkTHiwoyU5sNEcmBzvlmdxp9%2BXPwDENyauY670mvcfdXOYRHBGmAGb3Wcqwj0RhpAX8Sxs5eFllRZhNkOyVD7%2F0GGd%2FcU23a%2FIdDPYvbHOvjt%2Fbou52VmlqK1YL5azNMz5J1UECmr8MKmk7LwGOqUBscsdJX0y8iHtNWcAuSNdGZjwqrfeSMh1bfzMOAb5NxmScawwq2%2FFAbI2zCq7Gwu2YHbd3d9zb2pwb%2Fxdpm%2BJ08qrYj13Ur0knOSg%2Fo5be38tk4dVoDAAycwzbbovsqkRsIBEIOrU7TJpKpmTyrFzWEm2UcfSQSS7OZ7suwh76vpZWlmp5ES8daYhTooHGFbEf8kMAC7%2BM2YUMK3PyIvT2e1faaw4&X-Amz-Signature=234fe78d273f2faf59c4c6105f719cc444590cae45af875631975d2e4737dd4c&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QKKEVPO7%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T072041Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCUxE79ZmOZpfvUTyXjxBjHwgH%2BsXP%2FtgbdH6c2o%2FKVMwIgHi2xJbnUnvQ7sZ7xlYpQ8XlNKJ6%2FxfifEZoW5k19b4QqiAQIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNTDF%2BZ%2FdBWD8BRLzircAyjZ9wSyv37IDo8NKl3p5SQraChbPMitvT9BrDox3mrX%2Bids25AdZxAQlYBYksagvUlP1sCZR8TPp37U3QcsQ2UGxGAOdABT48NPyrrCyV7nvrn2LACUEzQ8q4nKlllYujCsbZyKkcoOrRvHF9wJNo%2FGcR3W2mA38TA3thvc8v%2FMmpCmCHLYh1sLTBXpkB6J7sSOakQPGdcXO%2FVhZOJh40Q0E6PiF8buc3P9C5FMQOoK1pLs%2BA%2FKSd%2BQNkYTZgjzPgnTs5hyW%2FrgLilRBmZCbSBVe%2BtMXDRMMO%2BkrsXFWuXXkBfa1di%2BxiyFcd4Zl0TiizJd8WGb3h0r12jPHFApTrNAUCqYPZhEc8hlfFIlsTLPAXU1ZtSLp%2BQi7mOHkWkzBEx3g3qyYgQJAHwp7XxKnVlA47IDR%2Frort7jWqTVmaXV6V3FRWoGTFaVAtsC79w9g4mv3H6iPoswEkj4xjsZpXnc04kzDPhLrPZkYZjb%2Fd2qS4OgIWdkTHiwoyU5sNEcmBzvlmdxp9%2BXPwDENyauY670mvcfdXOYRHBGmAGb3Wcqwj0RhpAX8Sxs5eFllRZhNkOyVD7%2F0GGd%2FcU23a%2FIdDPYvbHOvjt%2Fbou52VmlqK1YL5azNMz5J1UECmr8MKmk7LwGOqUBscsdJX0y8iHtNWcAuSNdGZjwqrfeSMh1bfzMOAb5NxmScawwq2%2FFAbI2zCq7Gwu2YHbd3d9zb2pwb%2Fxdpm%2BJ08qrYj13Ur0knOSg%2Fo5be38tk4dVoDAAycwzbbovsqkRsIBEIOrU7TJpKpmTyrFzWEm2UcfSQSS7OZ7suwh76vpZWlmp5ES8daYhTooHGFbEf8kMAC7%2BM2YUMK3PyIvT2e1faaw4&X-Amz-Signature=bdc749167b264cd49157f4e81bdff6bf97bb755606193308ee5f485ea3b6c556&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QKKEVPO7%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T072041Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCUxE79ZmOZpfvUTyXjxBjHwgH%2BsXP%2FtgbdH6c2o%2FKVMwIgHi2xJbnUnvQ7sZ7xlYpQ8XlNKJ6%2FxfifEZoW5k19b4QqiAQIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNTDF%2BZ%2FdBWD8BRLzircAyjZ9wSyv37IDo8NKl3p5SQraChbPMitvT9BrDox3mrX%2Bids25AdZxAQlYBYksagvUlP1sCZR8TPp37U3QcsQ2UGxGAOdABT48NPyrrCyV7nvrn2LACUEzQ8q4nKlllYujCsbZyKkcoOrRvHF9wJNo%2FGcR3W2mA38TA3thvc8v%2FMmpCmCHLYh1sLTBXpkB6J7sSOakQPGdcXO%2FVhZOJh40Q0E6PiF8buc3P9C5FMQOoK1pLs%2BA%2FKSd%2BQNkYTZgjzPgnTs5hyW%2FrgLilRBmZCbSBVe%2BtMXDRMMO%2BkrsXFWuXXkBfa1di%2BxiyFcd4Zl0TiizJd8WGb3h0r12jPHFApTrNAUCqYPZhEc8hlfFIlsTLPAXU1ZtSLp%2BQi7mOHkWkzBEx3g3qyYgQJAHwp7XxKnVlA47IDR%2Frort7jWqTVmaXV6V3FRWoGTFaVAtsC79w9g4mv3H6iPoswEkj4xjsZpXnc04kzDPhLrPZkYZjb%2Fd2qS4OgIWdkTHiwoyU5sNEcmBzvlmdxp9%2BXPwDENyauY670mvcfdXOYRHBGmAGb3Wcqwj0RhpAX8Sxs5eFllRZhNkOyVD7%2F0GGd%2FcU23a%2FIdDPYvbHOvjt%2Fbou52VmlqK1YL5azNMz5J1UECmr8MKmk7LwGOqUBscsdJX0y8iHtNWcAuSNdGZjwqrfeSMh1bfzMOAb5NxmScawwq2%2FFAbI2zCq7Gwu2YHbd3d9zb2pwb%2Fxdpm%2BJ08qrYj13Ur0knOSg%2Fo5be38tk4dVoDAAycwzbbovsqkRsIBEIOrU7TJpKpmTyrFzWEm2UcfSQSS7OZ7suwh76vpZWlmp5ES8daYhTooHGFbEf8kMAC7%2BM2YUMK3PyIvT2e1faaw4&X-Amz-Signature=8c3964598386fda37366afc43426745ee0dd28b27542d3009a4560a8c0381d06&X-Amz-SignedHeaders=host&x-id=GetObject)


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

