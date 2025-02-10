---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466QV7MSFUC%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250210T014901Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEJn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDBwGk3ux0muXVPWDT\
  iw2bfJm3TNWmtgJ72gJPUoNKoIAIgYKI9HbDR9IzKDbE7PhmJmnabn%2Bj7wzerIBI7ZOChBrgqiA\
  QIsv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHwbimsvbRiSRTqPFir\
  cA5wXLPeTmTx28GMOymDiDK1l6dRwB%2FreJZIIdOp1KsBqD4SOFMprC%2BkmbfHhKBuXLMVcBDnO\
  XHF3MqyZN%2BuGF2QWLz%2BrGmyTOvnNBdof%2FhbTWW77PXhm%2Ba%2F%2F1KMNANW3huS%2BapC\
  oHU20Tz8bajM0fA19sYmtWzXV3GvJjL%2Fw4LS%2FF8bafWv5o0siIt3nUgIqDVMf2GSg5fpi7sXN\
  JD2YliZq0roqMxg2QI5HozdRXFvT8AbV5wAemst3BYjvcPR8Ee3YbFvngxAwLJoEUvG5jGPHQQehF\
  4QA4vGS6%2BWxPXiU22NwfDgrS5TzYGOAx5wni5l0fCT9FUeNtSI%2FZu%2BgJNBX7EjBbW%2B5Er\
  %2FtR2uGLlTKApWZyJljRdi2cR6QCUS8OFb5k38dDxm0vPzK295nkkVUXKKu3BB%2FEbQt9IMt6Md\
  NXi9OlWl9XOFoWc4e8kFBVoaLt8QXRkZD9fgm2eEcqGHLSAuMebBkAl3bkKuDPMDTRcXrlxwYKf41\
  8Abks6bQRuFk14DfG%2FR9nyvfD%2BIqjwv4WOhie6zWXhhEgCxqysW7TIEhCQzWInp%2FLmTM17p\
  2cPyrk0NiJ%2B0ADXnBB8TjlI1LcsSuyDlMPH4B4%2BqDAjTBhLdiK5DzxQH5TBDgMJCdpb0GOqUB\
  6WPgtQHV5Bbrl3f3Ps3LEGyIhba9tIJbCPwt7jIcsNdgQCB927n9bdxBML7qtIqSpxK1eXiSEjVV6\
  vg3fwJ1R3yNKdn8HnuDwzEdKm26kOca6SOSJT0e8A1ENQ22qCmWt5%2B4sDyJ2uMeeGBxmuv1VsZP\
  qyWIgL9A1BP68yR9vpksY9y1OMMrE7Z%2FlIuo4qFrIELewmnOZJEMF8Y7vSqHALxw0XC4&X-Amz-\
  Signature=8922f837b500b2cb3153d0b25d6216d707df8b2a116827a061e71eb2c3640a8d&X-\
  Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466456YDLNP%2F20250210%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250210T014731Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEJn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIBfYgr8zPjFu0hio8CDmE9v9bcWKKbDUmg%2BmkXR%2FcLQYAiEAiuZTpvSrkuax6j9%2F\
        HHtI1ufXN1rz4F2m7nbL%2Bj5S36kqiAQIsv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAG\
        gw2Mzc0MjMxODM4MDUiDFOi4X%2F7HOvBnc%2B19yrcA0fP6gZ2fHr9DfAoh4aUXgifyPAw\
        PgmfkVoxvYQIdwiIHXwyhnFOxuTfeaxxQHG%2FNg6hS%2BqKGQQ7RZ4QQiGdp1YMZAeV237\
        QPJ7KBViMeegsADU0QCJSCQvfMwUIic1HZeJbuPq89nSnuXa5a%2B1kg8neS6La3Sm7pozn\
        K3nvoTGgBDAwvAAggAFK4BIAviAqEUE6WOC0phH8RQL2ARzgEJnn1B2qT9cGWvQVuND7Jmb\
        9AZWOUhbt0wYVL8vaO863gK5pzfooLkJCBjdo7TWzSEzM0bFEzr2%2FbnZyQY6Atl%2BiE%\
        2BgSqny1d2XXeP2eNwjyBHoK31%2BUOKIQuBZ733E483KRJ6ltatOt3%2BOGch0htUol39M\
        Jao1FSi5%2BH50ZS83Ym%2FsKPTBUDvXEfgOR73cV8ZKjWlHLevg6XjCvfeT73jhZke9M2U\
        brvqR6Hs89J%2BxclkluwIzTRi6ySMb78F0xwU4K1b%2Fw0SVW5kCoHZE3WRACNhR2xqqZm\
        70d7Q7dfdxAmIDQc%2FDURF2dH%2Bn%2BBaUO%2BYM1hmFhodFF1GdJa3Mo%2B3nMaO0pWk\
        AHVoY4U%2Bw7lByosPWxHyYJVcBTK6j8sYyuTtMsNZYGv0rfxrkZckXK4PK8EJvGQ6cJNVF\
        %2BK6yEMNCbpb0GOqUB2Sp25mSaTBu6GzOfl7LH25X1t7v0DLTrDHbv7bSoedBrKO8uhOZb\
        pEqp3K5ECN3ZmTRnpiNcmZUCDRUdmp0XZ2uol%2FXG6VEA7qpTkKWqT4uSPDQMF%2B3d6YN\
        OM4AXkPxgLeo49uNISCgZXJZQlXUrJ%2BpPEYs90daWsJB20rgom99gXKeAE4Gxp%2B8g9d\
        S%2Bw3UNjlbK%2BTS%2Bg3pWY%2FuPlPGow4e4fBtz&X-Amz-Signature=3dd549451c52\
        e35c1ad27d882d51def19f5c4c469cc5d0e7dff7b13ac738f8e5&X-Amz-SignedHeader\
        s=host&x-id=GetObject"
      expiry_time: "2025-02-10T02:47:31.616Z"
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
UPDATE_TIME: "2025-02-10T01:49:08.631Z"
EXPIRY_TIME: "2025-02-10T02:48:57.483Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Q5F7CPLT%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T014857Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDF%2Fyt5R6Z3hQvUAy7Rcg1OgIrJ9zNH75CkErN%2F6hj7iQIhAOpHccbjYY2SWDMoDaH5jfwynPdHI8QvFlxCgANFKvUaKogECLL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwLptUVARKDFPNAkfMq3AM2UwPYX7ErdMvp0%2FzRx%2FMd3RDI%2BJrfOvTGuoPAHgmALTMb4NJ4Z7TqcVY5SDXTvXtkLhw6mkBdzQCM6U04GpJKabZ3VV1iVDcdAwc9G0ZMHdyIlA4erobRaFF5sYYABncg25B8HhIRnqaEA7URA7NmEsZkDOanv6YKvKjRF3EOtoPq%2Fq3awAUdsXZi1yN%2B%2FPn7J0eOIKS5etkFQtZN%2Fhys2wcR9k2nigGMvBZeDH%2Ftmqyud9LXgyLqwE6iFJjv6UgyCo2sI8wAhpcciuYkmpMR9IcXK2yNHLbK4tT5%2FK3XjAyLq%2Byo0LngT44QFjZ4LIegzlRnJFTq1lS0OgEr6dP9%2F7e2B7OYxm6jsKssQiCOOZlvjQ3rHrmKHkBEG6RnxiLCeh26uqt0vWTc3gsdQQA87HCSRGcKi8xlMXjFcc3F06c5eGQEl7sxTbi78205%2F7I8Y4j%2Fy9eneBT72%2BnSWFtmFDBPdYsTAE9%2Bg9eXUp6IuEBfBn1rjsNI%2FNcpL7Ku2Fe63UGTanuxoXsyT2hdHYQhCS9ld9Iw%2BNW989HgrTfPVcb1fcG25MimCToXY5rHlQwiCQS%2FEyUaOf3zgYykp4ohhQVwaYAlfQczwBvwutr4Y35Rw1a9q56jje5XiTCXnKW9BjqkAcjy0RgN0H4aPboMN8gsfrdgnDDF8xKmPJTGp6x6Ns6Ps97%2FCOES6fihr5nsFQAZGdubkqAZF%2BKcSJbvMbk9EA5TVsVaSHIZNQ6DrP48oxfT%2BImz38garWi1xLAQBl%2FqscDtB%2FPXkC10mxhMhgGFwTAhn93AxVqTxoXq%2FLhdsQsaaQ8jWM%2FiEYpKa5E2lPBSKBQQTxPvXwBA6S7r9y2pa3lOAFy7&X-Amz-Signature=f3eecbcd93f512aa4f25977711223edfa0d0fd63a235b950744bac76d3e0b933&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Q5F7CPLT%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T014857Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDF%2Fyt5R6Z3hQvUAy7Rcg1OgIrJ9zNH75CkErN%2F6hj7iQIhAOpHccbjYY2SWDMoDaH5jfwynPdHI8QvFlxCgANFKvUaKogECLL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwLptUVARKDFPNAkfMq3AM2UwPYX7ErdMvp0%2FzRx%2FMd3RDI%2BJrfOvTGuoPAHgmALTMb4NJ4Z7TqcVY5SDXTvXtkLhw6mkBdzQCM6U04GpJKabZ3VV1iVDcdAwc9G0ZMHdyIlA4erobRaFF5sYYABncg25B8HhIRnqaEA7URA7NmEsZkDOanv6YKvKjRF3EOtoPq%2Fq3awAUdsXZi1yN%2B%2FPn7J0eOIKS5etkFQtZN%2Fhys2wcR9k2nigGMvBZeDH%2Ftmqyud9LXgyLqwE6iFJjv6UgyCo2sI8wAhpcciuYkmpMR9IcXK2yNHLbK4tT5%2FK3XjAyLq%2Byo0LngT44QFjZ4LIegzlRnJFTq1lS0OgEr6dP9%2F7e2B7OYxm6jsKssQiCOOZlvjQ3rHrmKHkBEG6RnxiLCeh26uqt0vWTc3gsdQQA87HCSRGcKi8xlMXjFcc3F06c5eGQEl7sxTbi78205%2F7I8Y4j%2Fy9eneBT72%2BnSWFtmFDBPdYsTAE9%2Bg9eXUp6IuEBfBn1rjsNI%2FNcpL7Ku2Fe63UGTanuxoXsyT2hdHYQhCS9ld9Iw%2BNW989HgrTfPVcb1fcG25MimCToXY5rHlQwiCQS%2FEyUaOf3zgYykp4ohhQVwaYAlfQczwBvwutr4Y35Rw1a9q56jje5XiTCXnKW9BjqkAcjy0RgN0H4aPboMN8gsfrdgnDDF8xKmPJTGp6x6Ns6Ps97%2FCOES6fihr5nsFQAZGdubkqAZF%2BKcSJbvMbk9EA5TVsVaSHIZNQ6DrP48oxfT%2BImz38garWi1xLAQBl%2FqscDtB%2FPXkC10mxhMhgGFwTAhn93AxVqTxoXq%2FLhdsQsaaQ8jWM%2FiEYpKa5E2lPBSKBQQTxPvXwBA6S7r9y2pa3lOAFy7&X-Amz-Signature=22c1861ad81cc5cf73c4afbf5e8e2e8105b3dd7a51a37c5b7dc3284d068e617e&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Q5F7CPLT%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T014857Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDF%2Fyt5R6Z3hQvUAy7Rcg1OgIrJ9zNH75CkErN%2F6hj7iQIhAOpHccbjYY2SWDMoDaH5jfwynPdHI8QvFlxCgANFKvUaKogECLL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwLptUVARKDFPNAkfMq3AM2UwPYX7ErdMvp0%2FzRx%2FMd3RDI%2BJrfOvTGuoPAHgmALTMb4NJ4Z7TqcVY5SDXTvXtkLhw6mkBdzQCM6U04GpJKabZ3VV1iVDcdAwc9G0ZMHdyIlA4erobRaFF5sYYABncg25B8HhIRnqaEA7URA7NmEsZkDOanv6YKvKjRF3EOtoPq%2Fq3awAUdsXZi1yN%2B%2FPn7J0eOIKS5etkFQtZN%2Fhys2wcR9k2nigGMvBZeDH%2Ftmqyud9LXgyLqwE6iFJjv6UgyCo2sI8wAhpcciuYkmpMR9IcXK2yNHLbK4tT5%2FK3XjAyLq%2Byo0LngT44QFjZ4LIegzlRnJFTq1lS0OgEr6dP9%2F7e2B7OYxm6jsKssQiCOOZlvjQ3rHrmKHkBEG6RnxiLCeh26uqt0vWTc3gsdQQA87HCSRGcKi8xlMXjFcc3F06c5eGQEl7sxTbi78205%2F7I8Y4j%2Fy9eneBT72%2BnSWFtmFDBPdYsTAE9%2Bg9eXUp6IuEBfBn1rjsNI%2FNcpL7Ku2Fe63UGTanuxoXsyT2hdHYQhCS9ld9Iw%2BNW989HgrTfPVcb1fcG25MimCToXY5rHlQwiCQS%2FEyUaOf3zgYykp4ohhQVwaYAlfQczwBvwutr4Y35Rw1a9q56jje5XiTCXnKW9BjqkAcjy0RgN0H4aPboMN8gsfrdgnDDF8xKmPJTGp6x6Ns6Ps97%2FCOES6fihr5nsFQAZGdubkqAZF%2BKcSJbvMbk9EA5TVsVaSHIZNQ6DrP48oxfT%2BImz38garWi1xLAQBl%2FqscDtB%2FPXkC10mxhMhgGFwTAhn93AxVqTxoXq%2FLhdsQsaaQ8jWM%2FiEYpKa5E2lPBSKBQQTxPvXwBA6S7r9y2pa3lOAFy7&X-Amz-Signature=6855fe3320ff7493049ed753cf35c1ed04be586d5b72a922aaffad7d160a74cf&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Q5F7CPLT%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T014857Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDF%2Fyt5R6Z3hQvUAy7Rcg1OgIrJ9zNH75CkErN%2F6hj7iQIhAOpHccbjYY2SWDMoDaH5jfwynPdHI8QvFlxCgANFKvUaKogECLL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwLptUVARKDFPNAkfMq3AM2UwPYX7ErdMvp0%2FzRx%2FMd3RDI%2BJrfOvTGuoPAHgmALTMb4NJ4Z7TqcVY5SDXTvXtkLhw6mkBdzQCM6U04GpJKabZ3VV1iVDcdAwc9G0ZMHdyIlA4erobRaFF5sYYABncg25B8HhIRnqaEA7URA7NmEsZkDOanv6YKvKjRF3EOtoPq%2Fq3awAUdsXZi1yN%2B%2FPn7J0eOIKS5etkFQtZN%2Fhys2wcR9k2nigGMvBZeDH%2Ftmqyud9LXgyLqwE6iFJjv6UgyCo2sI8wAhpcciuYkmpMR9IcXK2yNHLbK4tT5%2FK3XjAyLq%2Byo0LngT44QFjZ4LIegzlRnJFTq1lS0OgEr6dP9%2F7e2B7OYxm6jsKssQiCOOZlvjQ3rHrmKHkBEG6RnxiLCeh26uqt0vWTc3gsdQQA87HCSRGcKi8xlMXjFcc3F06c5eGQEl7sxTbi78205%2F7I8Y4j%2Fy9eneBT72%2BnSWFtmFDBPdYsTAE9%2Bg9eXUp6IuEBfBn1rjsNI%2FNcpL7Ku2Fe63UGTanuxoXsyT2hdHYQhCS9ld9Iw%2BNW989HgrTfPVcb1fcG25MimCToXY5rHlQwiCQS%2FEyUaOf3zgYykp4ohhQVwaYAlfQczwBvwutr4Y35Rw1a9q56jje5XiTCXnKW9BjqkAcjy0RgN0H4aPboMN8gsfrdgnDDF8xKmPJTGp6x6Ns6Ps97%2FCOES6fihr5nsFQAZGdubkqAZF%2BKcSJbvMbk9EA5TVsVaSHIZNQ6DrP48oxfT%2BImz38garWi1xLAQBl%2FqscDtB%2FPXkC10mxhMhgGFwTAhn93AxVqTxoXq%2FLhdsQsaaQ8jWM%2FiEYpKa5E2lPBSKBQQTxPvXwBA6S7r9y2pa3lOAFy7&X-Amz-Signature=9f70aabd66fbb658a34bfd6e129ba48b73afe1ba3e32539933584d8889972d69&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Q5F7CPLT%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T014857Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDF%2Fyt5R6Z3hQvUAy7Rcg1OgIrJ9zNH75CkErN%2F6hj7iQIhAOpHccbjYY2SWDMoDaH5jfwynPdHI8QvFlxCgANFKvUaKogECLL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwLptUVARKDFPNAkfMq3AM2UwPYX7ErdMvp0%2FzRx%2FMd3RDI%2BJrfOvTGuoPAHgmALTMb4NJ4Z7TqcVY5SDXTvXtkLhw6mkBdzQCM6U04GpJKabZ3VV1iVDcdAwc9G0ZMHdyIlA4erobRaFF5sYYABncg25B8HhIRnqaEA7URA7NmEsZkDOanv6YKvKjRF3EOtoPq%2Fq3awAUdsXZi1yN%2B%2FPn7J0eOIKS5etkFQtZN%2Fhys2wcR9k2nigGMvBZeDH%2Ftmqyud9LXgyLqwE6iFJjv6UgyCo2sI8wAhpcciuYkmpMR9IcXK2yNHLbK4tT5%2FK3XjAyLq%2Byo0LngT44QFjZ4LIegzlRnJFTq1lS0OgEr6dP9%2F7e2B7OYxm6jsKssQiCOOZlvjQ3rHrmKHkBEG6RnxiLCeh26uqt0vWTc3gsdQQA87HCSRGcKi8xlMXjFcc3F06c5eGQEl7sxTbi78205%2F7I8Y4j%2Fy9eneBT72%2BnSWFtmFDBPdYsTAE9%2Bg9eXUp6IuEBfBn1rjsNI%2FNcpL7Ku2Fe63UGTanuxoXsyT2hdHYQhCS9ld9Iw%2BNW989HgrTfPVcb1fcG25MimCToXY5rHlQwiCQS%2FEyUaOf3zgYykp4ohhQVwaYAlfQczwBvwutr4Y35Rw1a9q56jje5XiTCXnKW9BjqkAcjy0RgN0H4aPboMN8gsfrdgnDDF8xKmPJTGp6x6Ns6Ps97%2FCOES6fihr5nsFQAZGdubkqAZF%2BKcSJbvMbk9EA5TVsVaSHIZNQ6DrP48oxfT%2BImz38garWi1xLAQBl%2FqscDtB%2FPXkC10mxhMhgGFwTAhn93AxVqTxoXq%2FLhdsQsaaQ8jWM%2FiEYpKa5E2lPBSKBQQTxPvXwBA6S7r9y2pa3lOAFy7&X-Amz-Signature=6da713c4af938545520f8c60d5788a9a9538d51085cbda38a57dc935a14a6ccb&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666LZFOPKR%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T014858Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIG98d47AFftPHfwVvVABPtDxrKx9pyHeH4NFZqc6ghWrAiAYlSPRCHJ0B5KMmeXCSzYg%2FugFAnZATLv2tF6qfSd15iqIBAiy%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMCfmDtP32lnorHTPOKtwDw7jTXGqaXNMCEs41UHOkskJGB4s2XYeMEeasl4cUw3m1tFv%2BAHMxPc5a2VTd60M0ZPgSO5vKQMhKpFrw6RJCByKBGDo4LJO9j%2Fknda9jOm5E5Wyf4pkPaE2Ks39Z0UQlutCO2s1zQm1hd7iRu5aw332N7YN30Z9znXesCTNUkTo4bujclBbMwavUVLFHQG5XCyDKpdpfFunp5bYlt24u4ogkFHTsAeE5Fa6Cf%2BtI%2BoYOSXGvxkdZHnRmtzFcRhp2Lkps%2FZuGBeW1EXKoXVafGXvaTXK4Z91%2BQ9VBjL2I6MLgoQ12FFF%2Bfjw%2B8sCR2jYbPqTufNccQCTx%2BjwzQXhwKbPcWv64x9NtPHUADttQYAc42nsW0zox3lCJ3PTLs%2FHcuFtTX0u68wgw3KRtGFgADToUou1aNqtWDXNtVJCa8UW1MFIh7NHU06RCVRhaXW9xiqz8VvK14hFzbvqISMudSsGSk6x5PCVQQsyvWxcnqlzygvjDaMYHNO5cxtpfrKaPsgzQBBgwfMIsgGAg4wgkjdzv7JCYShuwl1v9gHnirCIYVaIuiw0w4ZlZrtAqLim%2BBJBN8ovub%2FIWyFlx%2FTHnXkoOzbyGQAcwKQId%2BRBBKobKKNbW06cGbi0%2FMYYw%2FZulvQY6pgGhTJTuSVEod4CKIcegO2AJGKCE2ycSzf6P0Y2U6oKf3nH%2FuJk6zHfZrWmYNRCtfm2DHrC7XIqriv9eFyrQJQYcgg1csKRiPRI1wucQi3m%2F8Gx6mgCCcXHof37QntjiqTNSBHpzDWtBbU4syB%2FU2erjN%2FdNcFSt641g25omygpOgFZtcvAULIleIQuBx8qgd0Dsc7uoSF44VGCEAj9o7nK%2FlhYPEw8D&X-Amz-Signature=6252c101fe4b186ed5881e504f053d363fa03d6c163ae4e5adbae8d9bad2b872&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TBMDLRJB%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T014900Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIC6hRuhkix%2FaIq1uEdVWAA7Hx5%2Fq9Wzj%2FT%2BxvIBHJoDfAiEA%2BMKmE3Ku8gDq3N4D2y%2FaoHjt%2B4qZRACOnRRPTiZTGjcqiAQIsv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNM%2Bd1yb8Qb4dDLxoCrcA8KkKXq4AX3wOwuzqX6Cmn8WfPyZIX2V2nCvFCzJe3GED%2FHhY0sNFkEncqlS%2BibLNjrcLRmY54saDjP3ywiZP5lJxJvTNjjyf317wgKpTxKbiRmZ%2FfZE35RRHtYXzFM0mwryv%2B6%2FIWQcR23TipXkn8gII42MHaYPsZVLP7qfJEf6b96DDqEjJO7LTCJFD4PRfOaVJeYFY96T6LITEgSojvIKyxnCBamyfwQ5HotSVyEOPdHeZ56ktyONCAiftQ7HdSKsBmC0S7xTASm1lVmo5BsPN8vs4cSy2DTUv1mZeBILEF957djklR02A7axLlYyEtlc44gji0AEsGIY%2FsR0v4uVQ9IZbcL0OBCUxrxdPppii2Hbrn%2FjZ80hk1nRpH3V0nUsOz%2BVY01fzJz8h%2F%2BcVPmJV%2F9MT%2FoGoQeQVfyXALHWS8dpvmQ01na2ZwXVRhmbC5ng6c8kxevL51F5lM5AsAATDoXi1Zhku4EfQ%2BFI8biSlBmXj2ynk3bR1kl0BvbE7pkHG6bHCe1yrmsRux0jVllEUbKQjU7mzK5MQ8hZOpjOpPEbHoZegCxQ4DJMTd0AseERKEhvZlG9ScuMP9zClKKASBRrBsF8yI3YwHaFeImd8079o1MVdgyf4RoBMN%2Bbpb0GOqUBSHGMXJ2lJDUY0orFIRSc3FzGE%2FdQUZN8k9K9hkG0rAcRmK1DPyw5bWLCMLpr%2F5xGpIfoUD8hksXRsLQMCTy8VsC7v91O%2BBU42hmIk23cvTzVQ%2B0U9OrtffAQiEVMLUaB1UupAl1fWtpedhK73Io1U2Eq9TS3qQMqADHluIzit10Yx%2BOlE3E2Flu2BUc88WpnnxN04yrtCFJnBkgPupkfPV%2BSF93r&X-Amz-Signature=1a3c09d82ac1cce836c57e1cbacd72e2ea0875977b6ece8bd21c4ebf4cbaf768&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Q5F7CPLT%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T014857Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDF%2Fyt5R6Z3hQvUAy7Rcg1OgIrJ9zNH75CkErN%2F6hj7iQIhAOpHccbjYY2SWDMoDaH5jfwynPdHI8QvFlxCgANFKvUaKogECLL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwLptUVARKDFPNAkfMq3AM2UwPYX7ErdMvp0%2FzRx%2FMd3RDI%2BJrfOvTGuoPAHgmALTMb4NJ4Z7TqcVY5SDXTvXtkLhw6mkBdzQCM6U04GpJKabZ3VV1iVDcdAwc9G0ZMHdyIlA4erobRaFF5sYYABncg25B8HhIRnqaEA7URA7NmEsZkDOanv6YKvKjRF3EOtoPq%2Fq3awAUdsXZi1yN%2B%2FPn7J0eOIKS5etkFQtZN%2Fhys2wcR9k2nigGMvBZeDH%2Ftmqyud9LXgyLqwE6iFJjv6UgyCo2sI8wAhpcciuYkmpMR9IcXK2yNHLbK4tT5%2FK3XjAyLq%2Byo0LngT44QFjZ4LIegzlRnJFTq1lS0OgEr6dP9%2F7e2B7OYxm6jsKssQiCOOZlvjQ3rHrmKHkBEG6RnxiLCeh26uqt0vWTc3gsdQQA87HCSRGcKi8xlMXjFcc3F06c5eGQEl7sxTbi78205%2F7I8Y4j%2Fy9eneBT72%2BnSWFtmFDBPdYsTAE9%2Bg9eXUp6IuEBfBn1rjsNI%2FNcpL7Ku2Fe63UGTanuxoXsyT2hdHYQhCS9ld9Iw%2BNW989HgrTfPVcb1fcG25MimCToXY5rHlQwiCQS%2FEyUaOf3zgYykp4ohhQVwaYAlfQczwBvwutr4Y35Rw1a9q56jje5XiTCXnKW9BjqkAcjy0RgN0H4aPboMN8gsfrdgnDDF8xKmPJTGp6x6Ns6Ps97%2FCOES6fihr5nsFQAZGdubkqAZF%2BKcSJbvMbk9EA5TVsVaSHIZNQ6DrP48oxfT%2BImz38garWi1xLAQBl%2FqscDtB%2FPXkC10mxhMhgGFwTAhn93AxVqTxoXq%2FLhdsQsaaQ8jWM%2FiEYpKa5E2lPBSKBQQTxPvXwBA6S7r9y2pa3lOAFy7&X-Amz-Signature=78958317b85d75f1829ae8880daa978bb7870cac7786ac4f1c40164bf9f09b79&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Q5F7CPLT%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T014857Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDF%2Fyt5R6Z3hQvUAy7Rcg1OgIrJ9zNH75CkErN%2F6hj7iQIhAOpHccbjYY2SWDMoDaH5jfwynPdHI8QvFlxCgANFKvUaKogECLL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwLptUVARKDFPNAkfMq3AM2UwPYX7ErdMvp0%2FzRx%2FMd3RDI%2BJrfOvTGuoPAHgmALTMb4NJ4Z7TqcVY5SDXTvXtkLhw6mkBdzQCM6U04GpJKabZ3VV1iVDcdAwc9G0ZMHdyIlA4erobRaFF5sYYABncg25B8HhIRnqaEA7URA7NmEsZkDOanv6YKvKjRF3EOtoPq%2Fq3awAUdsXZi1yN%2B%2FPn7J0eOIKS5etkFQtZN%2Fhys2wcR9k2nigGMvBZeDH%2Ftmqyud9LXgyLqwE6iFJjv6UgyCo2sI8wAhpcciuYkmpMR9IcXK2yNHLbK4tT5%2FK3XjAyLq%2Byo0LngT44QFjZ4LIegzlRnJFTq1lS0OgEr6dP9%2F7e2B7OYxm6jsKssQiCOOZlvjQ3rHrmKHkBEG6RnxiLCeh26uqt0vWTc3gsdQQA87HCSRGcKi8xlMXjFcc3F06c5eGQEl7sxTbi78205%2F7I8Y4j%2Fy9eneBT72%2BnSWFtmFDBPdYsTAE9%2Bg9eXUp6IuEBfBn1rjsNI%2FNcpL7Ku2Fe63UGTanuxoXsyT2hdHYQhCS9ld9Iw%2BNW989HgrTfPVcb1fcG25MimCToXY5rHlQwiCQS%2FEyUaOf3zgYykp4ohhQVwaYAlfQczwBvwutr4Y35Rw1a9q56jje5XiTCXnKW9BjqkAcjy0RgN0H4aPboMN8gsfrdgnDDF8xKmPJTGp6x6Ns6Ps97%2FCOES6fihr5nsFQAZGdubkqAZF%2BKcSJbvMbk9EA5TVsVaSHIZNQ6DrP48oxfT%2BImz38garWi1xLAQBl%2FqscDtB%2FPXkC10mxhMhgGFwTAhn93AxVqTxoXq%2FLhdsQsaaQ8jWM%2FiEYpKa5E2lPBSKBQQTxPvXwBA6S7r9y2pa3lOAFy7&X-Amz-Signature=a7fdf750a0c906bbcc975c7d0b0a590b108f9b2c14d76ea8553ed4181a6289e2&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Q5F7CPLT%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T014857Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDF%2Fyt5R6Z3hQvUAy7Rcg1OgIrJ9zNH75CkErN%2F6hj7iQIhAOpHccbjYY2SWDMoDaH5jfwynPdHI8QvFlxCgANFKvUaKogECLL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwLptUVARKDFPNAkfMq3AM2UwPYX7ErdMvp0%2FzRx%2FMd3RDI%2BJrfOvTGuoPAHgmALTMb4NJ4Z7TqcVY5SDXTvXtkLhw6mkBdzQCM6U04GpJKabZ3VV1iVDcdAwc9G0ZMHdyIlA4erobRaFF5sYYABncg25B8HhIRnqaEA7URA7NmEsZkDOanv6YKvKjRF3EOtoPq%2Fq3awAUdsXZi1yN%2B%2FPn7J0eOIKS5etkFQtZN%2Fhys2wcR9k2nigGMvBZeDH%2Ftmqyud9LXgyLqwE6iFJjv6UgyCo2sI8wAhpcciuYkmpMR9IcXK2yNHLbK4tT5%2FK3XjAyLq%2Byo0LngT44QFjZ4LIegzlRnJFTq1lS0OgEr6dP9%2F7e2B7OYxm6jsKssQiCOOZlvjQ3rHrmKHkBEG6RnxiLCeh26uqt0vWTc3gsdQQA87HCSRGcKi8xlMXjFcc3F06c5eGQEl7sxTbi78205%2F7I8Y4j%2Fy9eneBT72%2BnSWFtmFDBPdYsTAE9%2Bg9eXUp6IuEBfBn1rjsNI%2FNcpL7Ku2Fe63UGTanuxoXsyT2hdHYQhCS9ld9Iw%2BNW989HgrTfPVcb1fcG25MimCToXY5rHlQwiCQS%2FEyUaOf3zgYykp4ohhQVwaYAlfQczwBvwutr4Y35Rw1a9q56jje5XiTCXnKW9BjqkAcjy0RgN0H4aPboMN8gsfrdgnDDF8xKmPJTGp6x6Ns6Ps97%2FCOES6fihr5nsFQAZGdubkqAZF%2BKcSJbvMbk9EA5TVsVaSHIZNQ6DrP48oxfT%2BImz38garWi1xLAQBl%2FqscDtB%2FPXkC10mxhMhgGFwTAhn93AxVqTxoXq%2FLhdsQsaaQ8jWM%2FiEYpKa5E2lPBSKBQQTxPvXwBA6S7r9y2pa3lOAFy7&X-Amz-Signature=2ddb34fe4ac78358967fb6774b93ab2f9c2d77d6a6a614be84c305e2e0ca48e3&X-Amz-SignedHeaders=host&x-id=GetObject)


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

