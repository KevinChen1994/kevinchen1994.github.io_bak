---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466V6S7OL3H%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250130T024707Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQC3sdyR2DbW%2BSYTt\
  vE2zXfdL%2B%2F%2BVa8eNCPQxDX1rPtVAgIgLa2kQQhWRKoxP7ecXLaGR0dqrt01EWvuo9RLBLgG\
  m7QqiAQInP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHmqmaN%2FPpD\
  wQAkpPircA7%2Fd%2FYMnHGD0usS3WOCFIUPZPwkmI4I9OFRlZFbYEaV8RnO6NQGZ2yl9avdukgdM\
  KHJNkISiL4hYt7Zf6UHIETc2JeZwp0MetOANjIIKHXZMjPGWM%2BzDJxJm%2FeRe%2FwQz6j2oUB%\
  2FYYrpyzuNZ2ZzzvCqwVRV63rPd6iHPSuzLROe2e%2FEp65HlN%2BsazDLhtPGUScNiZsx7ljmCcP\
  uBFL9%2BMeWf2rCo49aisYgvYnhbpEFzMJFNQKjgmYEphER06tvOdecHcOXzs9gHRnREcJPvhXQw8\
  Yk1LH1tlNovEYGJE1PY80rVukfMzivarT21FE64iH8PiWBnfaGiCqD3sm%2B%2Bw2OjWqAJxQcduC\
  Fvjtnq%2BLUP44gs3PxbJdrtV04%2BJcern0Y6%2B4Jxo5Yr1R0mkwXTKd7PQtd4qaATlVn%2FIlD\
  jIkNFfPrgqVKc2IY%2Ft7QdVoKyTWWwvTmd2d6l2vAVadW8MI1m9umFhAj1QnyeIYN4RLPQWQb76s\
  i2LIX0tK9FNpJJOs8kqovDzrPWTkckcGYeeQR4ecdwio%2BPmdGCkjCJ%2BZVX%2BljxDgeKNOm1M\
  0Ydcn5gtlAkzl2x2YE1oXzXQ0ihHGVmAfRSMSGVVHZqM0fQOtpfONjGAnpxxhj76Vr5MJbP67wGOq\
  UBH4XDpJt6PC9IKhXosN1xx6Wk1%2FGVgvya%2Bt2uEqXOlSsUpVp6nEHil9STbpBiRzkLsxQU3aU\
  mTPDNcImzZQVDV%2BXFE7luHIAzdIFubteZ4pFReUU9aN0qkDk6zMQHowrrc6dKhOXLGszB5unytO\
  I9lJLPHL1ZahdIkjxYz9OdNozxqp7cZhm63tMx94wiz8PsnPvX%2Bd2Ys1Ki2fByvE7rJ4EVrr25&\
  X-Amz-Signature=ba4f29c549ed845d5a1b2dc119509a2c1f2e014452fa7d6a9d47d3901ad19\
  a99&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466RXBVRQGU%2F20250130%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250130T024559Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEJL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIG5b%2BHgvl532mfcHrtktuoavTNvuvDrGKI%2FA%2BhtxIUToAiEAnP12vZ4o0uuPIGi8\
        PE6KYspB4SxFjOWLtrWG0gZHWycqiAQIm%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAG\
        gw2Mzc0MjMxODM4MDUiDJhDI4Cnv2ssmb38WyrcA218rfJPHrQmm56uNCDgQ%2FfOUhtUmV\
        rxe8dPjuF0Kt2HwJdIKiV3u%2Fad0aHL9ushPZkg2doyuQCQL0nE712V66sbgmR%2FIKnWe\
        Qx0kKRaq%2BGm2MFKc98a7hIAyeqcdqIP05QpupFHVraSwXoGwXJERy4sNnH9IIxTk%2BtD\
        LBPznsz%2FRSb8%2F8oqAx3l%2FSmYyQZD7Y0WjOCxd1CG1xclgw3zua%2FE6UGp0%2F5nB\
        CSsqLVlh1SCGvTI9ehK6boLO06CPkUtc5TilZXO%2BkWabr%2FmqQAtyzW9LspN8UA%2BnW\
        A8RiBGkwde3HGJ0HfzRHkmnNEeHjbp%2Bhdq0V2FTxZTa8Bn%2FpzDrRtWcdHWavUA5XdnX\
        qGJEwUfUGTFNjEBMdpEH52lv6hEIatFJXuJ1kcADT39fD7mMTVKu8caGfAn%2BM%2FoHN7z\
        FALls0zB%2Bp2qIOwUhaC7Z3sQdJEgqfVqgF0z3LUeyJB%2FvXxYxhv9QgBY7PVIrp%2BeT\
        aBhvqnF%2F7XO8lbMMCAsdsEiTL2rU%2Fo65zhl9Pd%2FTG4fb%2FiVAH2%2FpJu%2FkJrO\
        UbsJ7ZdqfqqXgtwaEeaiI%2FGQJoC012%2BFq70I4Uq8t8O5rB5pIY03Vss0hDZ0WgJ%2Fs\
        JgrFp9%2FU5S4oaUzVm9OdDsGMO2z67wGOqUBzEI%2Fqi3EJbZks4Uk2KlI4JmF2VbrqOCP\
        V9%2F0jRja%2BBdR%2B5KcipGx13X3sHresFX8sg8ZSQNICUrAQ9SoeVsOlge3pbl7pr%2F\
        SCx4xiYM0MV8Nx8LWqkAURxl9bjNVsW39h8NW1jN%2BJLupLgjaTE3nCsN5Cy66uJYNceGU\
        YNen5SsG33tkmeSjfs17eWSuHC7qnFEgDe7Mm0TVwvVrJ9PqRbxagm0y&X-Amz-Signatur\
        e=8cc0622822125c5d75e00c5b5b4068d9da055b13047294594b18bf06f4571547&X-Am\
        z-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-01-30T03:45:59.751Z"
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
UPDATE_TIME: "2025-01-30T02:47:13.520Z"
EXPIRY_TIME: "2025-01-30T03:47:05.664Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RKUOIK23%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T024705Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDb6rowj0GlTCt5bPo%2BSokrOwQdEOeRJyltVyMvPJv%2FrwIhAJlwWYlZExwkHoGWom1Oxjazr5KxDU97s2UmNHwdVb6nKogECJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igyw3GkTp69Du9Lie3Yq3AMcnMwPpfd7i%2FslnI6YaVANdLosBN1g0QYQ8xqii7ZnHMWNDYv9XO2PzfReewkKNQhQT6sDWaHbjnXloMHRcaa3zmIx7cCkPlJA27lcoU3ipstzLQ8Xl2dR0Ti3wHi6%2Fk9xgzhLOP1fl8RMH4h3%2B9C8uN5HEcBw20gzybAbkQ4g44xpDbnW8y2WGRd8PplvM%2BuEwi4Z%2BjO3tFl8qmOTnNzkI7XFxBhUo1QfPJMdzcwANRgryvc%2F6DVm6y6ChUfrwRP1Sek2yEs7LCT86kA78ehj1vwXKjyKnPp0Vd8GC8RCzjjWbGwOXskOL%2F0KmBnbFRcDqnOC69lRPP5TahedmFp7gZo9r7gEFiJ0%2FUxfSH3uffFwIWceBirGTU8wOLgYMK23%2BrRP%2Ff9JxrGwLTQcmmCaHLHrICqXgsLUqObz7JreM95ZgPwkPLiFWlgABeXnXpkFozMtyezPd9MyRrjTbr79n2GnXmWurRIx5Lpip%2FgR5rVG0Ujclp68lEhfA%2FWXRoiInUyo9OcM1CmjZK%2FWmPSHCgj%2FzWl9%2FDv%2BJA1e6ZTXHnSRUdzM2gH1D%2F8cpVtE7HwD92P0N0RabS7TeKwWRTOTUdohYGeK6pt0rJsV5QEXDeWcpFc8ekdN%2BTdYyDCez%2Bu8BjqkAcuBTEpT6UT8e2kMP%2BzSG831%2Fs4x9G4njAq%2B2UADYDfLnvHkdPPJT3YFp8XdqmNxIutE9PPztKHH1Md0E5DT4KrIokKn524d59Y0ckCfbp%2BNdAnXdBwmdwwrweFbJqjYQdR87hCbRxMEeQVXbcJ5FRCpSnAuMtCc1KaOPf4IP68UBcv2bdWi8Q%2B8rQ7EsT9MQgMO9XnuHD35VC7h6k4ARciofw6V&X-Amz-Signature=2a9d4716161fb3e1a5becbc53c8a5bd04ea258bbd4e1e69003ea929a3ce9b581&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RKUOIK23%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T024705Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDb6rowj0GlTCt5bPo%2BSokrOwQdEOeRJyltVyMvPJv%2FrwIhAJlwWYlZExwkHoGWom1Oxjazr5KxDU97s2UmNHwdVb6nKogECJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igyw3GkTp69Du9Lie3Yq3AMcnMwPpfd7i%2FslnI6YaVANdLosBN1g0QYQ8xqii7ZnHMWNDYv9XO2PzfReewkKNQhQT6sDWaHbjnXloMHRcaa3zmIx7cCkPlJA27lcoU3ipstzLQ8Xl2dR0Ti3wHi6%2Fk9xgzhLOP1fl8RMH4h3%2B9C8uN5HEcBw20gzybAbkQ4g44xpDbnW8y2WGRd8PplvM%2BuEwi4Z%2BjO3tFl8qmOTnNzkI7XFxBhUo1QfPJMdzcwANRgryvc%2F6DVm6y6ChUfrwRP1Sek2yEs7LCT86kA78ehj1vwXKjyKnPp0Vd8GC8RCzjjWbGwOXskOL%2F0KmBnbFRcDqnOC69lRPP5TahedmFp7gZo9r7gEFiJ0%2FUxfSH3uffFwIWceBirGTU8wOLgYMK23%2BrRP%2Ff9JxrGwLTQcmmCaHLHrICqXgsLUqObz7JreM95ZgPwkPLiFWlgABeXnXpkFozMtyezPd9MyRrjTbr79n2GnXmWurRIx5Lpip%2FgR5rVG0Ujclp68lEhfA%2FWXRoiInUyo9OcM1CmjZK%2FWmPSHCgj%2FzWl9%2FDv%2BJA1e6ZTXHnSRUdzM2gH1D%2F8cpVtE7HwD92P0N0RabS7TeKwWRTOTUdohYGeK6pt0rJsV5QEXDeWcpFc8ekdN%2BTdYyDCez%2Bu8BjqkAcuBTEpT6UT8e2kMP%2BzSG831%2Fs4x9G4njAq%2B2UADYDfLnvHkdPPJT3YFp8XdqmNxIutE9PPztKHH1Md0E5DT4KrIokKn524d59Y0ckCfbp%2BNdAnXdBwmdwwrweFbJqjYQdR87hCbRxMEeQVXbcJ5FRCpSnAuMtCc1KaOPf4IP68UBcv2bdWi8Q%2B8rQ7EsT9MQgMO9XnuHD35VC7h6k4ARciofw6V&X-Amz-Signature=91fac9725a0b5dcdffbc09e564665d91598b8a51c6f91ad55bcae164266083fa&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RKUOIK23%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T024705Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDb6rowj0GlTCt5bPo%2BSokrOwQdEOeRJyltVyMvPJv%2FrwIhAJlwWYlZExwkHoGWom1Oxjazr5KxDU97s2UmNHwdVb6nKogECJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igyw3GkTp69Du9Lie3Yq3AMcnMwPpfd7i%2FslnI6YaVANdLosBN1g0QYQ8xqii7ZnHMWNDYv9XO2PzfReewkKNQhQT6sDWaHbjnXloMHRcaa3zmIx7cCkPlJA27lcoU3ipstzLQ8Xl2dR0Ti3wHi6%2Fk9xgzhLOP1fl8RMH4h3%2B9C8uN5HEcBw20gzybAbkQ4g44xpDbnW8y2WGRd8PplvM%2BuEwi4Z%2BjO3tFl8qmOTnNzkI7XFxBhUo1QfPJMdzcwANRgryvc%2F6DVm6y6ChUfrwRP1Sek2yEs7LCT86kA78ehj1vwXKjyKnPp0Vd8GC8RCzjjWbGwOXskOL%2F0KmBnbFRcDqnOC69lRPP5TahedmFp7gZo9r7gEFiJ0%2FUxfSH3uffFwIWceBirGTU8wOLgYMK23%2BrRP%2Ff9JxrGwLTQcmmCaHLHrICqXgsLUqObz7JreM95ZgPwkPLiFWlgABeXnXpkFozMtyezPd9MyRrjTbr79n2GnXmWurRIx5Lpip%2FgR5rVG0Ujclp68lEhfA%2FWXRoiInUyo9OcM1CmjZK%2FWmPSHCgj%2FzWl9%2FDv%2BJA1e6ZTXHnSRUdzM2gH1D%2F8cpVtE7HwD92P0N0RabS7TeKwWRTOTUdohYGeK6pt0rJsV5QEXDeWcpFc8ekdN%2BTdYyDCez%2Bu8BjqkAcuBTEpT6UT8e2kMP%2BzSG831%2Fs4x9G4njAq%2B2UADYDfLnvHkdPPJT3YFp8XdqmNxIutE9PPztKHH1Md0E5DT4KrIokKn524d59Y0ckCfbp%2BNdAnXdBwmdwwrweFbJqjYQdR87hCbRxMEeQVXbcJ5FRCpSnAuMtCc1KaOPf4IP68UBcv2bdWi8Q%2B8rQ7EsT9MQgMO9XnuHD35VC7h6k4ARciofw6V&X-Amz-Signature=d7fd5372e5b87e82c57d2e0baf809262281d63ee061558edeab96e3215d52fd2&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RKUOIK23%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T024705Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDb6rowj0GlTCt5bPo%2BSokrOwQdEOeRJyltVyMvPJv%2FrwIhAJlwWYlZExwkHoGWom1Oxjazr5KxDU97s2UmNHwdVb6nKogECJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igyw3GkTp69Du9Lie3Yq3AMcnMwPpfd7i%2FslnI6YaVANdLosBN1g0QYQ8xqii7ZnHMWNDYv9XO2PzfReewkKNQhQT6sDWaHbjnXloMHRcaa3zmIx7cCkPlJA27lcoU3ipstzLQ8Xl2dR0Ti3wHi6%2Fk9xgzhLOP1fl8RMH4h3%2B9C8uN5HEcBw20gzybAbkQ4g44xpDbnW8y2WGRd8PplvM%2BuEwi4Z%2BjO3tFl8qmOTnNzkI7XFxBhUo1QfPJMdzcwANRgryvc%2F6DVm6y6ChUfrwRP1Sek2yEs7LCT86kA78ehj1vwXKjyKnPp0Vd8GC8RCzjjWbGwOXskOL%2F0KmBnbFRcDqnOC69lRPP5TahedmFp7gZo9r7gEFiJ0%2FUxfSH3uffFwIWceBirGTU8wOLgYMK23%2BrRP%2Ff9JxrGwLTQcmmCaHLHrICqXgsLUqObz7JreM95ZgPwkPLiFWlgABeXnXpkFozMtyezPd9MyRrjTbr79n2GnXmWurRIx5Lpip%2FgR5rVG0Ujclp68lEhfA%2FWXRoiInUyo9OcM1CmjZK%2FWmPSHCgj%2FzWl9%2FDv%2BJA1e6ZTXHnSRUdzM2gH1D%2F8cpVtE7HwD92P0N0RabS7TeKwWRTOTUdohYGeK6pt0rJsV5QEXDeWcpFc8ekdN%2BTdYyDCez%2Bu8BjqkAcuBTEpT6UT8e2kMP%2BzSG831%2Fs4x9G4njAq%2B2UADYDfLnvHkdPPJT3YFp8XdqmNxIutE9PPztKHH1Md0E5DT4KrIokKn524d59Y0ckCfbp%2BNdAnXdBwmdwwrweFbJqjYQdR87hCbRxMEeQVXbcJ5FRCpSnAuMtCc1KaOPf4IP68UBcv2bdWi8Q%2B8rQ7EsT9MQgMO9XnuHD35VC7h6k4ARciofw6V&X-Amz-Signature=0990abf0c5887848d51131000a99f432273c2e0e59db0f030a9626ebc6c88546&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RKUOIK23%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T024705Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDb6rowj0GlTCt5bPo%2BSokrOwQdEOeRJyltVyMvPJv%2FrwIhAJlwWYlZExwkHoGWom1Oxjazr5KxDU97s2UmNHwdVb6nKogECJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igyw3GkTp69Du9Lie3Yq3AMcnMwPpfd7i%2FslnI6YaVANdLosBN1g0QYQ8xqii7ZnHMWNDYv9XO2PzfReewkKNQhQT6sDWaHbjnXloMHRcaa3zmIx7cCkPlJA27lcoU3ipstzLQ8Xl2dR0Ti3wHi6%2Fk9xgzhLOP1fl8RMH4h3%2B9C8uN5HEcBw20gzybAbkQ4g44xpDbnW8y2WGRd8PplvM%2BuEwi4Z%2BjO3tFl8qmOTnNzkI7XFxBhUo1QfPJMdzcwANRgryvc%2F6DVm6y6ChUfrwRP1Sek2yEs7LCT86kA78ehj1vwXKjyKnPp0Vd8GC8RCzjjWbGwOXskOL%2F0KmBnbFRcDqnOC69lRPP5TahedmFp7gZo9r7gEFiJ0%2FUxfSH3uffFwIWceBirGTU8wOLgYMK23%2BrRP%2Ff9JxrGwLTQcmmCaHLHrICqXgsLUqObz7JreM95ZgPwkPLiFWlgABeXnXpkFozMtyezPd9MyRrjTbr79n2GnXmWurRIx5Lpip%2FgR5rVG0Ujclp68lEhfA%2FWXRoiInUyo9OcM1CmjZK%2FWmPSHCgj%2FzWl9%2FDv%2BJA1e6ZTXHnSRUdzM2gH1D%2F8cpVtE7HwD92P0N0RabS7TeKwWRTOTUdohYGeK6pt0rJsV5QEXDeWcpFc8ekdN%2BTdYyDCez%2Bu8BjqkAcuBTEpT6UT8e2kMP%2BzSG831%2Fs4x9G4njAq%2B2UADYDfLnvHkdPPJT3YFp8XdqmNxIutE9PPztKHH1Md0E5DT4KrIokKn524d59Y0ckCfbp%2BNdAnXdBwmdwwrweFbJqjYQdR87hCbRxMEeQVXbcJ5FRCpSnAuMtCc1KaOPf4IP68UBcv2bdWi8Q%2B8rQ7EsT9MQgMO9XnuHD35VC7h6k4ARciofw6V&X-Amz-Signature=a4594bf49f582db0b3f34a8350d9cd65fc7ef1d66e294e0cdbeaf66560447e2c&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RHU3XGLV%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T024706Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIHWhBZNNXBAU8XxhQsXB%2FWfFih9ZHf%2Bm3rMzmtIMBV9UAiEA7fEpDkTPSx1MQhfWtvXezmcNU31kUJr5y2aVk7XsyNQqiAQInP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDH1XOm0x1Pab%2Bkuz8SrcA%2BtlP6K0YXvmIcP45j8G82PsleuqWdR6gYtOtQirpje3jC11p7cXrmgPh67jYICdWwS3ewqzZHXjSb65FYh8PRz4XMz6h0oznce802yLVdvqLNJGs4Mh18wpByM4EDuGhn5vNhh8fD668DmF%2B8x8EgGIqOEsxkMw6hYfgIMtA1RyY6iKcpubhlGkq8MaHCIgF6M0k8%2FeivU3ictXyd4KmwpueaMZdYiW7IUzhLK36oJGrYOW1edA%2F3g5%2FxmlM1pOzP4aBR5sO6DVPwS58bxa%2BfPDpUeqAYeuKnwzjKlKWbXkjh%2BgPJ4qbh22P9p5J%2FUpAmjzA0VrLyw1MPnuRKPDCs%2B4zRUgCSvp8rTibHDjyrLeb8tFDv5s13hE7mkRANthmvSCeQ0sfcp1mRU4LHBYFIOmcN2CmWrzdsLrvXlmBat0jm1hA53m5YnWZQyiTuJnVSQgf0zZPHOSBvDaDkPlLP2MmAPbjrcc43l2a1uILUBtPkH2j3rtxeZY5oSlVBh01OmUKyF%2BJpftgmncnGFBWm%2Fyt%2BEQ7CTxzaudstw4ugx5d%2B12iWm7e2SV%2Fo0j890r4hTaRevJqebSiblytCwcrI2GwuBxoEOByjPuBkCCW6FP3i5x5EeoaLrEBZzHMLPP67wGOqUB14VNvgwFBTivq2IQfIUhhqU0yRUCrBxwoPfwgo6FLRAxYL6mnzsJfh8ntLjSqJDRJ5p2jm8%2Bn1gnscbPOrKhMVMKUoypVC0jSCm%2FY6tonWJJckAFLEceC%2BPk%2Fbb3GjlNz8w8Qp2j3HRJ7iaIV4QcL7Hc%2Bn3ql3cK9wsxpVUwXIn62sy6rpWq%2BFTthiCRdnki7lESVwJfzf%2BY0ITI%2BuT0QVkW0cYa&X-Amz-Signature=9bd2697d2f7a9047c55008c47b5dc048428ac5f7c0501e03749d85abe620ba18&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663ZXJV4U7%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T024707Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIAVN%2BBmAslfxp0CUV9X6TKm8rLZUIdw1jRGDTbyIA515AiEAtJ301qE6lcw%2BcKEWQBvONb4vrLuldtGTI%2BQ4VsMORhkqiAQIm%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOUQVKVYZg5chMTZ1yrcA1hhqivZe6V06QPn96rW1zYscvtKzG3%2BUssx3YG18%2BYOajLrJopp5P8i%2Fw5EomZ%2BnKZ0cIZBUvhPkjIul5joHR3gRd%2F4WLYB03KgW0S5PrfD%2FETIWfQEc%2FAtZ5KcBUERlaON4RDhB96JrX6cWCPQOXAFCDL4czT7kxguZ%2B%2BdjSeI5nIfYkqt%2FNbU5XR0j4vm7FwnVKKZYKIfwFtdLFasDW55ofNI6qKuWSYHwmSH4seChIEOFV8MUKJTyMS8OMYNkDvyGRYyn2fslOOp%2Bhzu%2BHz5C1TwldNhvsBDW3B0%2BYAz%2BA2HILE2FBMn5it%2BwD0hUpTZQ7%2FfZaXQMIpwBRTkEXohbktaYowvjz2TMpxV4OQCmuvkTDWnVkhFVobUooy5%2BNFwlVjt6ntUIBlKWLjrhT%2BJm46mqxvfWtoNIAROwKOgb35NNJs1yaWZY9CDdvJsmeujnMXw7dnGKAdLnTKNbaJtgwdsCa%2Bdg8Eorz94IbyzVJEjV8xqUDxuiYofIYuLN%2FhTVdmGyUCPef8YBGy13znQ7qPYA2jbrN01%2B3xWL9yu8iWNTPoeDxbrw1u8Dz98vn63%2F0wIXt4msJEiNIbMog9Q9rYQDbzktJf%2Fo%2B2k5OcVSeTBItmm1OaHPKCiMIO067wGOqUB%2Ft2QJm8plaLQQkRLdCVeWtH9iqcrufXkgCV%2F0pg4zK96eTYRX%2BS9FPekWQSJICw%2Bd8TScAtTAe2aLrS2P5odL%2FHkdba84jzotb4B%2FMtGQrFLHUZ6uohHzQ0q8Dq2DoPUxCb%2FXD50hzJmGGXSMDjE40LwN6EdHUx%2B1U60QnpX8Mm%2FivfzO02mwBzMUNp%2BHeThiWhUOSbtYNEXu4VyAcf8V5EgIrhU&X-Amz-Signature=94e42e9b2e6b9ec082edc87a17135f3f0a341b5d8c4484ede59ed1580c8c0ae4&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RKUOIK23%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T024706Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDb6rowj0GlTCt5bPo%2BSokrOwQdEOeRJyltVyMvPJv%2FrwIhAJlwWYlZExwkHoGWom1Oxjazr5KxDU97s2UmNHwdVb6nKogECJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igyw3GkTp69Du9Lie3Yq3AMcnMwPpfd7i%2FslnI6YaVANdLosBN1g0QYQ8xqii7ZnHMWNDYv9XO2PzfReewkKNQhQT6sDWaHbjnXloMHRcaa3zmIx7cCkPlJA27lcoU3ipstzLQ8Xl2dR0Ti3wHi6%2Fk9xgzhLOP1fl8RMH4h3%2B9C8uN5HEcBw20gzybAbkQ4g44xpDbnW8y2WGRd8PplvM%2BuEwi4Z%2BjO3tFl8qmOTnNzkI7XFxBhUo1QfPJMdzcwANRgryvc%2F6DVm6y6ChUfrwRP1Sek2yEs7LCT86kA78ehj1vwXKjyKnPp0Vd8GC8RCzjjWbGwOXskOL%2F0KmBnbFRcDqnOC69lRPP5TahedmFp7gZo9r7gEFiJ0%2FUxfSH3uffFwIWceBirGTU8wOLgYMK23%2BrRP%2Ff9JxrGwLTQcmmCaHLHrICqXgsLUqObz7JreM95ZgPwkPLiFWlgABeXnXpkFozMtyezPd9MyRrjTbr79n2GnXmWurRIx5Lpip%2FgR5rVG0Ujclp68lEhfA%2FWXRoiInUyo9OcM1CmjZK%2FWmPSHCgj%2FzWl9%2FDv%2BJA1e6ZTXHnSRUdzM2gH1D%2F8cpVtE7HwD92P0N0RabS7TeKwWRTOTUdohYGeK6pt0rJsV5QEXDeWcpFc8ekdN%2BTdYyDCez%2Bu8BjqkAcuBTEpT6UT8e2kMP%2BzSG831%2Fs4x9G4njAq%2B2UADYDfLnvHkdPPJT3YFp8XdqmNxIutE9PPztKHH1Md0E5DT4KrIokKn524d59Y0ckCfbp%2BNdAnXdBwmdwwrweFbJqjYQdR87hCbRxMEeQVXbcJ5FRCpSnAuMtCc1KaOPf4IP68UBcv2bdWi8Q%2B8rQ7EsT9MQgMO9XnuHD35VC7h6k4ARciofw6V&X-Amz-Signature=bffc6124b65efef07c0f6c408308ffe1a6aad73175a3616517cc0580f012f86a&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RKUOIK23%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T024705Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDb6rowj0GlTCt5bPo%2BSokrOwQdEOeRJyltVyMvPJv%2FrwIhAJlwWYlZExwkHoGWom1Oxjazr5KxDU97s2UmNHwdVb6nKogECJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igyw3GkTp69Du9Lie3Yq3AMcnMwPpfd7i%2FslnI6YaVANdLosBN1g0QYQ8xqii7ZnHMWNDYv9XO2PzfReewkKNQhQT6sDWaHbjnXloMHRcaa3zmIx7cCkPlJA27lcoU3ipstzLQ8Xl2dR0Ti3wHi6%2Fk9xgzhLOP1fl8RMH4h3%2B9C8uN5HEcBw20gzybAbkQ4g44xpDbnW8y2WGRd8PplvM%2BuEwi4Z%2BjO3tFl8qmOTnNzkI7XFxBhUo1QfPJMdzcwANRgryvc%2F6DVm6y6ChUfrwRP1Sek2yEs7LCT86kA78ehj1vwXKjyKnPp0Vd8GC8RCzjjWbGwOXskOL%2F0KmBnbFRcDqnOC69lRPP5TahedmFp7gZo9r7gEFiJ0%2FUxfSH3uffFwIWceBirGTU8wOLgYMK23%2BrRP%2Ff9JxrGwLTQcmmCaHLHrICqXgsLUqObz7JreM95ZgPwkPLiFWlgABeXnXpkFozMtyezPd9MyRrjTbr79n2GnXmWurRIx5Lpip%2FgR5rVG0Ujclp68lEhfA%2FWXRoiInUyo9OcM1CmjZK%2FWmPSHCgj%2FzWl9%2FDv%2BJA1e6ZTXHnSRUdzM2gH1D%2F8cpVtE7HwD92P0N0RabS7TeKwWRTOTUdohYGeK6pt0rJsV5QEXDeWcpFc8ekdN%2BTdYyDCez%2Bu8BjqkAcuBTEpT6UT8e2kMP%2BzSG831%2Fs4x9G4njAq%2B2UADYDfLnvHkdPPJT3YFp8XdqmNxIutE9PPztKHH1Md0E5DT4KrIokKn524d59Y0ckCfbp%2BNdAnXdBwmdwwrweFbJqjYQdR87hCbRxMEeQVXbcJ5FRCpSnAuMtCc1KaOPf4IP68UBcv2bdWi8Q%2B8rQ7EsT9MQgMO9XnuHD35VC7h6k4ARciofw6V&X-Amz-Signature=716838bbe6c7ddcf96db6e688ca134285d8347385ba0fc4b0a58635403f71280&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RKUOIK23%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T024705Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDb6rowj0GlTCt5bPo%2BSokrOwQdEOeRJyltVyMvPJv%2FrwIhAJlwWYlZExwkHoGWom1Oxjazr5KxDU97s2UmNHwdVb6nKogECJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igyw3GkTp69Du9Lie3Yq3AMcnMwPpfd7i%2FslnI6YaVANdLosBN1g0QYQ8xqii7ZnHMWNDYv9XO2PzfReewkKNQhQT6sDWaHbjnXloMHRcaa3zmIx7cCkPlJA27lcoU3ipstzLQ8Xl2dR0Ti3wHi6%2Fk9xgzhLOP1fl8RMH4h3%2B9C8uN5HEcBw20gzybAbkQ4g44xpDbnW8y2WGRd8PplvM%2BuEwi4Z%2BjO3tFl8qmOTnNzkI7XFxBhUo1QfPJMdzcwANRgryvc%2F6DVm6y6ChUfrwRP1Sek2yEs7LCT86kA78ehj1vwXKjyKnPp0Vd8GC8RCzjjWbGwOXskOL%2F0KmBnbFRcDqnOC69lRPP5TahedmFp7gZo9r7gEFiJ0%2FUxfSH3uffFwIWceBirGTU8wOLgYMK23%2BrRP%2Ff9JxrGwLTQcmmCaHLHrICqXgsLUqObz7JreM95ZgPwkPLiFWlgABeXnXpkFozMtyezPd9MyRrjTbr79n2GnXmWurRIx5Lpip%2FgR5rVG0Ujclp68lEhfA%2FWXRoiInUyo9OcM1CmjZK%2FWmPSHCgj%2FzWl9%2FDv%2BJA1e6ZTXHnSRUdzM2gH1D%2F8cpVtE7HwD92P0N0RabS7TeKwWRTOTUdohYGeK6pt0rJsV5QEXDeWcpFc8ekdN%2BTdYyDCez%2Bu8BjqkAcuBTEpT6UT8e2kMP%2BzSG831%2Fs4x9G4njAq%2B2UADYDfLnvHkdPPJT3YFp8XdqmNxIutE9PPztKHH1Md0E5DT4KrIokKn524d59Y0ckCfbp%2BNdAnXdBwmdwwrweFbJqjYQdR87hCbRxMEeQVXbcJ5FRCpSnAuMtCc1KaOPf4IP68UBcv2bdWi8Q%2B8rQ7EsT9MQgMO9XnuHD35VC7h6k4ARciofw6V&X-Amz-Signature=0517933621cd1e00d10a139d38fe0cc2ec545586a0d52ee98eea620cae5448cf&X-Amz-SignedHeaders=host&x-id=GetObject)


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

