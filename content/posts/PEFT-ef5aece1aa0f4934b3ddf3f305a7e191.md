---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4664PSW3IRZ%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250216T072227Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEC4aCXVzLXdlc3QtMiJHMEUCIQCzH2As0rMs8FRugRP9xBR97d8wHBCVdMBR8ahpcqHfLgIgNOb\
  qzbP7NVEM1lQwStO9eu9G1CUCmqO5bhz7UUFirtsq%2FwMIVxAAGgw2Mzc0MjMxODM4MDUiDBNiAA\
  Isd%2BCRU8mShCrcA1pqEa2lcdc%2BD%2BzCmajbFcvvzoFhN4P0hTUX0wVE7z%2Bo52U55gT3xE8\
  NxDe6gcFMOmF0avZVHFHzt0q5AjZdXaA5ix70a8CYK2CCpPV3Z8dOdB2xzEINOnmcLmDFD6JlqRa6\
  M%2BSfxChO4FDJjqO7OQ%2Bwq6dbDV%2F7KXYCdq0l8bGzVnc03va%2BoEiLET4lpUn662yO5cBHT\
  jOIjA8p0luBQhy4u4W%2Bz2KqURrtDnm%2FzjuTP7hJZl3f19yCgck9h%2BY40OeXyTcSw8xudQ1i\
  4o2zoj%2Brvo%2Bs4nZm7PGD23wbR6iy29v9FojUtT4tTlbA80AuzFWKrvPNt6bjI4xNMmjECDifV\
  dmaPXM5w0G99OkYZ0jlALbwHA3lMDZJlaRQFocn%2BNI%2BiWbXz4s5MrTm3W4ljI5FAl%2FWIegV\
  qntPcNnmNShDSMIBQX7XXp0VIVo5IqnKXhBZ90n8v6ChpXgOndfFmJ2B%2B4YSbr6VX8OiPFfWlQd\
  blAfrsb9wfa2Fxr2KiqHAUDuau054%2B1hwmk2F5Gnqjb5S%2F7XZrSSpNvTswBO08%2BwxmdUkp0\
  %2BRJoWnjHIJID78dsXD6hjtAIytO3uoEpR0dqc9IrNqBo37N%2BsXIlUDi4il8eCTG91SZgngQYI\
  xMKb%2Bxb0GOqUB8jxOBuvTGADuxPmWD8XgK1DVv0qRGqu6c%2FT3CDup3cA9JmOyEeSWBMQpPoO2\
  KYGdMKgosEq5We%2FNWM%2FsURuhYb4oZkFaHC0Tn8ux4NS88Vobq3MyFqluRPfO3UBHb1k8UsVhq\
  onJhiST2MVJraHV4J%2BSitQU2u2Xy%2BJKf8Cg1DmQJ0KC7OB0cXFuLRprMYEx7hHjLTRkYPlqJu\
  PxSKgOGM8C1XSx&X-Amz-Signature=6ba974828e5e2cc8e2f9fbb1044fe6a2fd6cee3c456fc5\
  02fdbb23e7bc8ad740&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466XVE2UWWU%2F20250216%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250216T072106Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEC4aCXVzLXdlc3QtMiJGMEQCIBqyCwKpZ%2FFqNvKQVG4BShC2u6TXg\
        jal81bDdbgJTqkcAiANvbJJqBAC9fNcFdQeSZf408K48Ye02sAcYzRShGBIUyr%2FAwhXEA\
        AaDDYzNzQyMzE4MzgwNSIMi78L8xJTsgjP7pRwKtwDPoAFNMuib2CQveTDs8Dk1M80zURVX\
        0K2YLQExn7ppW49mPIywzpVppHHheU1tZDLJoWAThgB5I2j3O%2B4azPTSTTLb%2F0ulJRS\
        AXQyXWqaPjVR3a6QBPobBAZQsnF%2BzGedhJZx9DiLyCdbVYQqLYt6rZauTFEX0ayirAvUf\
        xSvmvfac9pn3FjxP0r19epVBgSzL%2B9hL6DchKnczX0UZdO2XLyZVfV0VvuhCKPCZe%2Fo\
        QbgWJbck6sc6BOOkAePlWHBo9BCOSJ%2FMqU9iFGyhwvdG4vmkHxo%2BV3ZLAnTTN6f3AMX\
        1LvTGAGsl2D2UYl2AyAnFbKwaiQ0K24w5ifaB%2BlNZ08U92HmCHYphPSHOGgGJxDWw8jLF\
        MllBfbubx%2BRZvytOqK%2BXg%2FE10Qp73sK%2BSGqiWQy3c6Wn3ELTJrgA2IZg46XGsGs\
        5g1HcjSytVQ4HDYTO5y6Ycp48q81abqLQD%2BK03pHx3OPXFU6FpuL4v2NRT4srcLbWFCs%\
        2B2QqPNCCqMQnWBqSTDHr3NEsERNBbUGxh6TBh9l0VB15uvl8NY5BCYrEDfqQza%2FI7zEg\
        CxqUf3%2Be%2BlfaiUnFkAOfgtfb98ptMv7CgOKHvyNzEPVOxuveaO6G5WyIrHMFdN5qhC4\
        Iw6f3FvQY6pgHtF9khManUCIoX6fcbuqj%2FfivNUj4CNyZfXOC%2FOe4dmun7ghaTV7N6L\
        uF45KelLWB6FxJDNyz9fv2%2BvariQP0%2BtiTnuutyiU2nvnI9XJjirDfxYZVN99pehXBA\
        Fbw%2BVbVBAGKRpHPY86ybf%2FSXTSj5gXiEfdpezQeqQZSoCwtdgcwy%2FkB07KOLkvzlG\
        aDzM1j9xQmS0OUsPsvyiu%2BPrYxK1m9X6CXZ&X-Amz-Signature=584de526dea4ddd21\
        1f8e9f45eb64957eb92c681ae94f49b8fda412cb48460ef&X-Amz-SignedHeaders=hos\
        t&x-id=GetObject"
      expiry_time: "2025-02-16T08:21:06.144Z"
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
UPDATE_TIME: "2025-02-16T07:22:32.406Z"
EXPIRY_TIME: "2025-02-16T08:22:25.394Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TIMOLQ7D%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T072225Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEC4aCXVzLXdlc3QtMiJGMEQCIDRplf6wC2Yt5gR6nUmA3oEREcEDId2G%2BzyU75SAo4kWAiBOY38Hu0%2Bt45Yne5z6Y7qRBxaqG09NlBey0ugsrQeqRSr%2FAwhXEAAaDDYzNzQyMzE4MzgwNSIMClBXbbrKSShxi5BkKtwDXI8EmbNnvEaVNP7keJU9o1QCGmFvPDvaDV511Jwp0XwYUm1mUIeUL3zzg%2Bm9JxbwFW9NqkScpnowVYz%2BvBqhg6U1TllENP5fa%2Fdd%2FEcsryW8G8GLUteJSZEp1WRr5bSYDVIIUfNHMwkh9tKpK%2BQtY5obJQ1roys2f7xBWQWw5wB2PoI%2FXDYmKi%2FlowxxEv9fP2ip14HroYWcM2MzwzgFQEllQW0HLgiZRKuhR93LY67oU9AuHPFvb9neW21PFLNYCcHuJCQNbfBudPT0FGQxednQ%2BFT38zKoqt9bdo2%2B%2BbpubN2q%2Fgp7LkNGO62U9%2B6gOkDEfAG%2FClIGQepsYdG3OoJzKKnGTywS9SG4c87lOFZ0JOKqTQbNkzmIohx3sja8MSs%2B%2FZ%2BQMjpvwLN7GO4r7JIwPkztzRZ9lWM04c21eLmknUmMjhs73ykLXz4TV9SCflmibEOcmBruNLJs50voRSIx52Nkt1zewpAM2vn37y8yoVASwyIQ6uM16Pnz1vu93pa4pspXFPgTYn0UZ05GTSlLsL4BqoECTtwIvEwlVxezNQ36ThmYsijib2HhMVr%2BWAkZrq8kdFqjNFYopQg0PgpfQMiaXL2xplqNQF4JLkBZ3%2F0ZoUZmCHUh408wuv7FvQY6pgHQVnBVRVYUHDvAKMdpGihTaPWiFtpMZRHentJb4UPbxzyqNL3%2BbBuW5xIlQn5lmqy7jH9Ut%2FXNWp9Wzfd2KboXN%2BD58k4KdiyFKaiYT4uAuh%2BXeboWtwwCfuiB0KKt6jz1vod65gNOc4YJR1mcr1uek6uauTsJBTl7ztwXEATd0PCHWZi13nuFINs5cn1LbnW4qO3pZo7cehYFwTMdxRfQaly%2FI5cf&X-Amz-Signature=2ddb53c69beedd3180219763e8609db3b133f9914bb422818baa84344c33d340&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TIMOLQ7D%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T072225Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEC4aCXVzLXdlc3QtMiJGMEQCIDRplf6wC2Yt5gR6nUmA3oEREcEDId2G%2BzyU75SAo4kWAiBOY38Hu0%2Bt45Yne5z6Y7qRBxaqG09NlBey0ugsrQeqRSr%2FAwhXEAAaDDYzNzQyMzE4MzgwNSIMClBXbbrKSShxi5BkKtwDXI8EmbNnvEaVNP7keJU9o1QCGmFvPDvaDV511Jwp0XwYUm1mUIeUL3zzg%2Bm9JxbwFW9NqkScpnowVYz%2BvBqhg6U1TllENP5fa%2Fdd%2FEcsryW8G8GLUteJSZEp1WRr5bSYDVIIUfNHMwkh9tKpK%2BQtY5obJQ1roys2f7xBWQWw5wB2PoI%2FXDYmKi%2FlowxxEv9fP2ip14HroYWcM2MzwzgFQEllQW0HLgiZRKuhR93LY67oU9AuHPFvb9neW21PFLNYCcHuJCQNbfBudPT0FGQxednQ%2BFT38zKoqt9bdo2%2B%2BbpubN2q%2Fgp7LkNGO62U9%2B6gOkDEfAG%2FClIGQepsYdG3OoJzKKnGTywS9SG4c87lOFZ0JOKqTQbNkzmIohx3sja8MSs%2B%2FZ%2BQMjpvwLN7GO4r7JIwPkztzRZ9lWM04c21eLmknUmMjhs73ykLXz4TV9SCflmibEOcmBruNLJs50voRSIx52Nkt1zewpAM2vn37y8yoVASwyIQ6uM16Pnz1vu93pa4pspXFPgTYn0UZ05GTSlLsL4BqoECTtwIvEwlVxezNQ36ThmYsijib2HhMVr%2BWAkZrq8kdFqjNFYopQg0PgpfQMiaXL2xplqNQF4JLkBZ3%2F0ZoUZmCHUh408wuv7FvQY6pgHQVnBVRVYUHDvAKMdpGihTaPWiFtpMZRHentJb4UPbxzyqNL3%2BbBuW5xIlQn5lmqy7jH9Ut%2FXNWp9Wzfd2KboXN%2BD58k4KdiyFKaiYT4uAuh%2BXeboWtwwCfuiB0KKt6jz1vod65gNOc4YJR1mcr1uek6uauTsJBTl7ztwXEATd0PCHWZi13nuFINs5cn1LbnW4qO3pZo7cehYFwTMdxRfQaly%2FI5cf&X-Amz-Signature=9f4620aeaf56b4c409b4f10e1ac5a6716cb86bbc4337cf1a7d8bbd4a4fb4f71b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TIMOLQ7D%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T072225Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEC4aCXVzLXdlc3QtMiJGMEQCIDRplf6wC2Yt5gR6nUmA3oEREcEDId2G%2BzyU75SAo4kWAiBOY38Hu0%2Bt45Yne5z6Y7qRBxaqG09NlBey0ugsrQeqRSr%2FAwhXEAAaDDYzNzQyMzE4MzgwNSIMClBXbbrKSShxi5BkKtwDXI8EmbNnvEaVNP7keJU9o1QCGmFvPDvaDV511Jwp0XwYUm1mUIeUL3zzg%2Bm9JxbwFW9NqkScpnowVYz%2BvBqhg6U1TllENP5fa%2Fdd%2FEcsryW8G8GLUteJSZEp1WRr5bSYDVIIUfNHMwkh9tKpK%2BQtY5obJQ1roys2f7xBWQWw5wB2PoI%2FXDYmKi%2FlowxxEv9fP2ip14HroYWcM2MzwzgFQEllQW0HLgiZRKuhR93LY67oU9AuHPFvb9neW21PFLNYCcHuJCQNbfBudPT0FGQxednQ%2BFT38zKoqt9bdo2%2B%2BbpubN2q%2Fgp7LkNGO62U9%2B6gOkDEfAG%2FClIGQepsYdG3OoJzKKnGTywS9SG4c87lOFZ0JOKqTQbNkzmIohx3sja8MSs%2B%2FZ%2BQMjpvwLN7GO4r7JIwPkztzRZ9lWM04c21eLmknUmMjhs73ykLXz4TV9SCflmibEOcmBruNLJs50voRSIx52Nkt1zewpAM2vn37y8yoVASwyIQ6uM16Pnz1vu93pa4pspXFPgTYn0UZ05GTSlLsL4BqoECTtwIvEwlVxezNQ36ThmYsijib2HhMVr%2BWAkZrq8kdFqjNFYopQg0PgpfQMiaXL2xplqNQF4JLkBZ3%2F0ZoUZmCHUh408wuv7FvQY6pgHQVnBVRVYUHDvAKMdpGihTaPWiFtpMZRHentJb4UPbxzyqNL3%2BbBuW5xIlQn5lmqy7jH9Ut%2FXNWp9Wzfd2KboXN%2BD58k4KdiyFKaiYT4uAuh%2BXeboWtwwCfuiB0KKt6jz1vod65gNOc4YJR1mcr1uek6uauTsJBTl7ztwXEATd0PCHWZi13nuFINs5cn1LbnW4qO3pZo7cehYFwTMdxRfQaly%2FI5cf&X-Amz-Signature=5e3bdea8105bd7382b0783edafd8900385b097631d129aef2de17e0463535015&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TIMOLQ7D%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T072225Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEC4aCXVzLXdlc3QtMiJGMEQCIDRplf6wC2Yt5gR6nUmA3oEREcEDId2G%2BzyU75SAo4kWAiBOY38Hu0%2Bt45Yne5z6Y7qRBxaqG09NlBey0ugsrQeqRSr%2FAwhXEAAaDDYzNzQyMzE4MzgwNSIMClBXbbrKSShxi5BkKtwDXI8EmbNnvEaVNP7keJU9o1QCGmFvPDvaDV511Jwp0XwYUm1mUIeUL3zzg%2Bm9JxbwFW9NqkScpnowVYz%2BvBqhg6U1TllENP5fa%2Fdd%2FEcsryW8G8GLUteJSZEp1WRr5bSYDVIIUfNHMwkh9tKpK%2BQtY5obJQ1roys2f7xBWQWw5wB2PoI%2FXDYmKi%2FlowxxEv9fP2ip14HroYWcM2MzwzgFQEllQW0HLgiZRKuhR93LY67oU9AuHPFvb9neW21PFLNYCcHuJCQNbfBudPT0FGQxednQ%2BFT38zKoqt9bdo2%2B%2BbpubN2q%2Fgp7LkNGO62U9%2B6gOkDEfAG%2FClIGQepsYdG3OoJzKKnGTywS9SG4c87lOFZ0JOKqTQbNkzmIohx3sja8MSs%2B%2FZ%2BQMjpvwLN7GO4r7JIwPkztzRZ9lWM04c21eLmknUmMjhs73ykLXz4TV9SCflmibEOcmBruNLJs50voRSIx52Nkt1zewpAM2vn37y8yoVASwyIQ6uM16Pnz1vu93pa4pspXFPgTYn0UZ05GTSlLsL4BqoECTtwIvEwlVxezNQ36ThmYsijib2HhMVr%2BWAkZrq8kdFqjNFYopQg0PgpfQMiaXL2xplqNQF4JLkBZ3%2F0ZoUZmCHUh408wuv7FvQY6pgHQVnBVRVYUHDvAKMdpGihTaPWiFtpMZRHentJb4UPbxzyqNL3%2BbBuW5xIlQn5lmqy7jH9Ut%2FXNWp9Wzfd2KboXN%2BD58k4KdiyFKaiYT4uAuh%2BXeboWtwwCfuiB0KKt6jz1vod65gNOc4YJR1mcr1uek6uauTsJBTl7ztwXEATd0PCHWZi13nuFINs5cn1LbnW4qO3pZo7cehYFwTMdxRfQaly%2FI5cf&X-Amz-Signature=c9c4e3ff80ba631bf692bc849caaa0c889fb7eefd90e88be15de1bea789fc695&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TIMOLQ7D%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T072225Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEC4aCXVzLXdlc3QtMiJGMEQCIDRplf6wC2Yt5gR6nUmA3oEREcEDId2G%2BzyU75SAo4kWAiBOY38Hu0%2Bt45Yne5z6Y7qRBxaqG09NlBey0ugsrQeqRSr%2FAwhXEAAaDDYzNzQyMzE4MzgwNSIMClBXbbrKSShxi5BkKtwDXI8EmbNnvEaVNP7keJU9o1QCGmFvPDvaDV511Jwp0XwYUm1mUIeUL3zzg%2Bm9JxbwFW9NqkScpnowVYz%2BvBqhg6U1TllENP5fa%2Fdd%2FEcsryW8G8GLUteJSZEp1WRr5bSYDVIIUfNHMwkh9tKpK%2BQtY5obJQ1roys2f7xBWQWw5wB2PoI%2FXDYmKi%2FlowxxEv9fP2ip14HroYWcM2MzwzgFQEllQW0HLgiZRKuhR93LY67oU9AuHPFvb9neW21PFLNYCcHuJCQNbfBudPT0FGQxednQ%2BFT38zKoqt9bdo2%2B%2BbpubN2q%2Fgp7LkNGO62U9%2B6gOkDEfAG%2FClIGQepsYdG3OoJzKKnGTywS9SG4c87lOFZ0JOKqTQbNkzmIohx3sja8MSs%2B%2FZ%2BQMjpvwLN7GO4r7JIwPkztzRZ9lWM04c21eLmknUmMjhs73ykLXz4TV9SCflmibEOcmBruNLJs50voRSIx52Nkt1zewpAM2vn37y8yoVASwyIQ6uM16Pnz1vu93pa4pspXFPgTYn0UZ05GTSlLsL4BqoECTtwIvEwlVxezNQ36ThmYsijib2HhMVr%2BWAkZrq8kdFqjNFYopQg0PgpfQMiaXL2xplqNQF4JLkBZ3%2F0ZoUZmCHUh408wuv7FvQY6pgHQVnBVRVYUHDvAKMdpGihTaPWiFtpMZRHentJb4UPbxzyqNL3%2BbBuW5xIlQn5lmqy7jH9Ut%2FXNWp9Wzfd2KboXN%2BD58k4KdiyFKaiYT4uAuh%2BXeboWtwwCfuiB0KKt6jz1vod65gNOc4YJR1mcr1uek6uauTsJBTl7ztwXEATd0PCHWZi13nuFINs5cn1LbnW4qO3pZo7cehYFwTMdxRfQaly%2FI5cf&X-Amz-Signature=fb02aa7a01d5f89e832abd00bd5e8b36ad9f07d5da7ebfcb0eb0807ccb35d79a&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667MIT5PXT%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T072226Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEC4aCXVzLXdlc3QtMiJGMEQCIFpV1iLNqKg4k8HQ3kW%2Bqn75FNRJJOsQObUgVbwbslbgAiBuaygU4FUEbqKf2jLRfbjA%2FLZq%2Fs57t4Xf%2BMc98C5dEyr%2FAwhXEAAaDDYzNzQyMzE4MzgwNSIMm%2FLtkqV9c%2F0WCjs3KtwDrm31si6xjHdmwba4CAQtSBNgsrBDZKj34PXR4T8tbx6HgTR0HEl4TlsP7g8T61FCzryOxc9jIKjoSG4s9AADbOL197Q9CMtq%2BTTMhJMQUGfQ%2FBpsy8pV0kGppjYKICwhNAHPnW2o%2BrmWjeOpkhd0ZwcWDXF1ccK3b5OAkGZ2FD2pUD2%2FBViAfleB8BDhSej7mcJ27ECfrNfrelcYBZ2GcNV%2BZZTlkBdXs5uhz%2FvJt904F0iULqMtIyRz5cDxxnmW9ldLIiO8PmrqByTavXbEdJ32l5XO50AS5uPAgV7iHzKCL74POhw1%2BJqBFo7CiRJg8vpuSy%2F8dZnEFKVNU6aZZ7%2F7Z3bRp5VRnEXrg1UoAfIyZOSeHJADnQ0go%2B3CJODGt9wcard%2BM0V6tO%2BXdBtQZtPceJ20BP5cpAF%2Fg%2Fe7uGmO9FgBps3y1pGPNG3fiZAOzWBnBMpJ0mRAvki4DLd6dba4wCbeL2pHUkgwnNycYwm960nPavVepX3ktJntIAiBtxcNFdTXcr4HkjdxxA5tNC6DtiEDQYVR64spm3L6RmDzqFc56ZO2%2FkBH195Uusvugc3vyC5AW0afQqXQ7FA%2BMtRefaxmqNPMPlAMBZyTJtWIDUHPTytcuvuBNDgwqf7FvQY6pgHqRf7FIOohPqTm%2B4CWuI41bR96yf7bj9nphlYcQSh%2B4zefgOBYjRYnOhqXOR1ncB6o50Z64K53Kx%2FEe%2BoMdqxMLE8pe%2FzmFlu1NwAi%2BenT%2Bcvr37CPpSPGwq2tI7GgbzxOi%2FlM7wapwfBMOhBAzOmroXDxhZYZSALb8eprx2H6fmEkZ6wPAtpDmfBZ9A%2F0SdVwOIVwKpyPkL%2FvkD0ymj%2Fq7nsLwow1&X-Amz-Signature=7479141a6d543b621f0fdf34af244221c30776aee7c0a377dc048f5c4dde0c6f&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RPYLARYF%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T072227Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEC4aCXVzLXdlc3QtMiJIMEYCIQDp76F6gFtA91uBT6xcVIY3bupjMMEKnZYUR6xn1ttOvgIhAP%2FLbJptTOl6NyB31EQlWz4rIIWYqvsiuhyj2WXFqhpZKv8DCFcQABoMNjM3NDIzMTgzODA1IgxgjoDCLd9p6ruNi6wq3AN0aDyQQ%2FbicU%2B71pBPHFumNn8KgCqKhzRJva6jL6Q81zzMVzhecvBuH2jYrpNvcyIibSTECcT2Agijxvqyeg0KkX%2BIsJth%2BEEbj20NO2nUGp%2Bqesp28OHB9gc0OCatvbhjlwIeT1y9EkO66Uj7W1VYozAum75%2BYZUFgv%2FmEnAwAOerHhvm%2ByzjURZdqGo7KJNtSm95yLYnujMUtUXUwDKFgjOPgYociiGCVi4P5U0ee09UIM3qrHhqlFVvczDvwGutc%2F3WC0khjK9YFAiwwZsqZyaR1h1a0GRfnc6FLn86x1byuqqlTMaCVo7nEjHT2cxVqBKx1A6cynQutsOU%2FxDcLnSW6zNBgv%2FugXSNmmTfj5RzsdV2l8lhmpZZ4xvsWy%2FntciGek%2F2hOQuWxjCNWHTysTBLZhK2XGNCMzEQIfttWOPe0ZGDZYUKPN887%2FiSXUp%2FcVarvpHy2S%2FctQQ2reKagIxgOOlS6HYxJjfhyomtNleWEsFvxIQ%2F5z69PbKhYTag3BZw96IPmgyo2iJNS8nSQXpJp%2B3KsbMVdJWFCueoZyOafca%2B1SvFNhFOB27HuNXsXEY5thluK5EWNm%2FwxOPhUkiL1wH%2F9r0hufIDikUkmqBZoF9zhAMnQgzLzDp%2FcW9BjqkAbZPRrR6Vrv1VmwmA0rBHIBYZsUSI93K0wcKLqw2WK%2FgWhqJjnFcXBp96sSrgQjwmVMSLkPkH8aAPtUzb%2BpUsUnOQZRrc99BPmAA6AGrrR7qwQCCxpQ3x34%2BEgACpMUvyR4Ec1sRfH2xctnVY%2F1VzdsiQDKJp%2Fje%2B6jI3WWEzc5DrwwRobhoNxUaqX1VnTdF9tuMbwMzr4imhgCsNdH04S897q%2Fr&X-Amz-Signature=632420612a4495664ab034808dfbdb1558163cd1dda1c81bc411ae9eea1a93c9&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TIMOLQ7D%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T072225Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEC4aCXVzLXdlc3QtMiJGMEQCIDRplf6wC2Yt5gR6nUmA3oEREcEDId2G%2BzyU75SAo4kWAiBOY38Hu0%2Bt45Yne5z6Y7qRBxaqG09NlBey0ugsrQeqRSr%2FAwhXEAAaDDYzNzQyMzE4MzgwNSIMClBXbbrKSShxi5BkKtwDXI8EmbNnvEaVNP7keJU9o1QCGmFvPDvaDV511Jwp0XwYUm1mUIeUL3zzg%2Bm9JxbwFW9NqkScpnowVYz%2BvBqhg6U1TllENP5fa%2Fdd%2FEcsryW8G8GLUteJSZEp1WRr5bSYDVIIUfNHMwkh9tKpK%2BQtY5obJQ1roys2f7xBWQWw5wB2PoI%2FXDYmKi%2FlowxxEv9fP2ip14HroYWcM2MzwzgFQEllQW0HLgiZRKuhR93LY67oU9AuHPFvb9neW21PFLNYCcHuJCQNbfBudPT0FGQxednQ%2BFT38zKoqt9bdo2%2B%2BbpubN2q%2Fgp7LkNGO62U9%2B6gOkDEfAG%2FClIGQepsYdG3OoJzKKnGTywS9SG4c87lOFZ0JOKqTQbNkzmIohx3sja8MSs%2B%2FZ%2BQMjpvwLN7GO4r7JIwPkztzRZ9lWM04c21eLmknUmMjhs73ykLXz4TV9SCflmibEOcmBruNLJs50voRSIx52Nkt1zewpAM2vn37y8yoVASwyIQ6uM16Pnz1vu93pa4pspXFPgTYn0UZ05GTSlLsL4BqoECTtwIvEwlVxezNQ36ThmYsijib2HhMVr%2BWAkZrq8kdFqjNFYopQg0PgpfQMiaXL2xplqNQF4JLkBZ3%2F0ZoUZmCHUh408wuv7FvQY6pgHQVnBVRVYUHDvAKMdpGihTaPWiFtpMZRHentJb4UPbxzyqNL3%2BbBuW5xIlQn5lmqy7jH9Ut%2FXNWp9Wzfd2KboXN%2BD58k4KdiyFKaiYT4uAuh%2BXeboWtwwCfuiB0KKt6jz1vod65gNOc4YJR1mcr1uek6uauTsJBTl7ztwXEATd0PCHWZi13nuFINs5cn1LbnW4qO3pZo7cehYFwTMdxRfQaly%2FI5cf&X-Amz-Signature=492a42ef47bb4f3c0dff9f17a8f95e1b667ec2fbd812ba8bf480f1b6ef0d3d36&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TIMOLQ7D%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T072225Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEC4aCXVzLXdlc3QtMiJGMEQCIDRplf6wC2Yt5gR6nUmA3oEREcEDId2G%2BzyU75SAo4kWAiBOY38Hu0%2Bt45Yne5z6Y7qRBxaqG09NlBey0ugsrQeqRSr%2FAwhXEAAaDDYzNzQyMzE4MzgwNSIMClBXbbrKSShxi5BkKtwDXI8EmbNnvEaVNP7keJU9o1QCGmFvPDvaDV511Jwp0XwYUm1mUIeUL3zzg%2Bm9JxbwFW9NqkScpnowVYz%2BvBqhg6U1TllENP5fa%2Fdd%2FEcsryW8G8GLUteJSZEp1WRr5bSYDVIIUfNHMwkh9tKpK%2BQtY5obJQ1roys2f7xBWQWw5wB2PoI%2FXDYmKi%2FlowxxEv9fP2ip14HroYWcM2MzwzgFQEllQW0HLgiZRKuhR93LY67oU9AuHPFvb9neW21PFLNYCcHuJCQNbfBudPT0FGQxednQ%2BFT38zKoqt9bdo2%2B%2BbpubN2q%2Fgp7LkNGO62U9%2B6gOkDEfAG%2FClIGQepsYdG3OoJzKKnGTywS9SG4c87lOFZ0JOKqTQbNkzmIohx3sja8MSs%2B%2FZ%2BQMjpvwLN7GO4r7JIwPkztzRZ9lWM04c21eLmknUmMjhs73ykLXz4TV9SCflmibEOcmBruNLJs50voRSIx52Nkt1zewpAM2vn37y8yoVASwyIQ6uM16Pnz1vu93pa4pspXFPgTYn0UZ05GTSlLsL4BqoECTtwIvEwlVxezNQ36ThmYsijib2HhMVr%2BWAkZrq8kdFqjNFYopQg0PgpfQMiaXL2xplqNQF4JLkBZ3%2F0ZoUZmCHUh408wuv7FvQY6pgHQVnBVRVYUHDvAKMdpGihTaPWiFtpMZRHentJb4UPbxzyqNL3%2BbBuW5xIlQn5lmqy7jH9Ut%2FXNWp9Wzfd2KboXN%2BD58k4KdiyFKaiYT4uAuh%2BXeboWtwwCfuiB0KKt6jz1vod65gNOc4YJR1mcr1uek6uauTsJBTl7ztwXEATd0PCHWZi13nuFINs5cn1LbnW4qO3pZo7cehYFwTMdxRfQaly%2FI5cf&X-Amz-Signature=abb3c18b01712aecc8a08d91b8f8e9ad95c6d6dd6e70cbe5e63ac62b81ea5dc9&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TIMOLQ7D%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T072225Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEC4aCXVzLXdlc3QtMiJGMEQCIDRplf6wC2Yt5gR6nUmA3oEREcEDId2G%2BzyU75SAo4kWAiBOY38Hu0%2Bt45Yne5z6Y7qRBxaqG09NlBey0ugsrQeqRSr%2FAwhXEAAaDDYzNzQyMzE4MzgwNSIMClBXbbrKSShxi5BkKtwDXI8EmbNnvEaVNP7keJU9o1QCGmFvPDvaDV511Jwp0XwYUm1mUIeUL3zzg%2Bm9JxbwFW9NqkScpnowVYz%2BvBqhg6U1TllENP5fa%2Fdd%2FEcsryW8G8GLUteJSZEp1WRr5bSYDVIIUfNHMwkh9tKpK%2BQtY5obJQ1roys2f7xBWQWw5wB2PoI%2FXDYmKi%2FlowxxEv9fP2ip14HroYWcM2MzwzgFQEllQW0HLgiZRKuhR93LY67oU9AuHPFvb9neW21PFLNYCcHuJCQNbfBudPT0FGQxednQ%2BFT38zKoqt9bdo2%2B%2BbpubN2q%2Fgp7LkNGO62U9%2B6gOkDEfAG%2FClIGQepsYdG3OoJzKKnGTywS9SG4c87lOFZ0JOKqTQbNkzmIohx3sja8MSs%2B%2FZ%2BQMjpvwLN7GO4r7JIwPkztzRZ9lWM04c21eLmknUmMjhs73ykLXz4TV9SCflmibEOcmBruNLJs50voRSIx52Nkt1zewpAM2vn37y8yoVASwyIQ6uM16Pnz1vu93pa4pspXFPgTYn0UZ05GTSlLsL4BqoECTtwIvEwlVxezNQ36ThmYsijib2HhMVr%2BWAkZrq8kdFqjNFYopQg0PgpfQMiaXL2xplqNQF4JLkBZ3%2F0ZoUZmCHUh408wuv7FvQY6pgHQVnBVRVYUHDvAKMdpGihTaPWiFtpMZRHentJb4UPbxzyqNL3%2BbBuW5xIlQn5lmqy7jH9Ut%2FXNWp9Wzfd2KboXN%2BD58k4KdiyFKaiYT4uAuh%2BXeboWtwwCfuiB0KKt6jz1vod65gNOc4YJR1mcr1uek6uauTsJBTl7ztwXEATd0PCHWZi13nuFINs5cn1LbnW4qO3pZo7cehYFwTMdxRfQaly%2FI5cf&X-Amz-Signature=06f3a2fe0dbe18b5d45b11f035ee5526650b866d0729767fddce2ce1bb3ddab7&X-Amz-SignedHeaders=host&x-id=GetObject)


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

