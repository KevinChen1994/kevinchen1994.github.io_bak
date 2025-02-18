---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4662WJGWP5X%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250218T222232Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEG4aCXVzLXdlc3QtMiJHMEUCIBQp5r1NX1q2znYagWCiXzEcIWVtrQ3VUUmBpVRX%2BjHRAiEAt\
  3tWISfJfbSgrkinIpxpYCZo8KGG7BER1ev96koUu1IqiAQIlv%2F%2F%2F%2F%2F%2F%2F%2F%2F%\
  2FARAAGgw2Mzc0MjMxODM4MDUiDKVBgz8hIFHJwQpuxyrcA5X6yVZb24e9JrM7SpWiFc%2FQMqlYy\
  vQHEllcHVIucFXjHW3WpVsc0b7FruLV5WRwL55R3fDpt1sOs0oORLQwofmXBjicfjEjQTsGPsv48N\
  fygKkqA39HXRWSAJzMroRTIvNLq3gjVdvjqfMAGs9HAoHsd0N1CoNoQ4snTk%2BuHenLbNbXvxmhu\
  TIRREzsoW5KpbVMb7Wwc4gg6V2%2FhI5dPLfJ2xfRPWS8ZAa2p9ia1jRBMoaBTU56TNRfit%2BmL8\
  lGhP9DA21pFDyfnEGL6gWyM9aosa3EGdzA%2Fx0KFflV58PGyjHjtbAh6IAAvxdwiZBJ9ZNYddZVY\
  y0goNe0I0jbbIWpXf7wYdeWeEjeN1HMndmJjC1EXksgJjGthGVtV9URVF3E%2FjvDluC48f%2F4mE\
  hrT70VCWaw73C8q2IXwl1fY2LLm5T%2BnIE97rmrGyWCon35%2BP88fh2UrGkUV32ns3B2o5tk8l3\
  lPh%2FjkgBF266UlWFDHrhfWJr%2FWNNRpTvGqPJ04nXjXgE26%2BBr%2BEHsn5Nlxg6VK3SFGEZW\
  h0dCWN8nxuVM%2BDYePjpqLj99HtVrOd6UH2%2FVNFSituZOVnD68OXbXJ84VDflXgXThsl%2FiIm\
  6%2BYjO%2FZLyttRnZyiFOM1GMNb2070GOqUBATnb4LXXJKLBZcvMaTT5hfh%2BfqNFySVt8ecIKu\
  JcW%2Bwy38iNN1x6KJVw%2Fd4ebb6BImkLo3p9aGbqX3JwiaGBv5lowJdhF%2Fmhhcz8AKsKLaV24\
  Le8p16P6qrfoB%2BUGy2XK%2B2vkb1j7F%2BUAQkJzBPpMT7YEQuM3P8G8uNtjIYjFm%2Fyvgq8IE\
  annDzxAo9T8HIUi81mv0MCUhSe7jsN%2FfoX1%2FrflqCV&X-Amz-Signature=a78e56b80f31e7\
  2f97cc7ae7db15f0722506c32c3bc74bc9ff69b797b277eb5e&X-Amz-SignedHeaders=host&x\
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
        redential=ASIAZI2LB4666G4APNCA%2F20250218%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250218T222114Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEG4aCXVzLXdlc3QtMiJIMEYCIQD4fGcehRdHiRwZb18av6yJJj6IGk5\
        eCHeVRtdSinIRrQIhAJwE5PMGHWJySQrzIehAgzmI8oDzfm1mfR%2Bye5xqdDsBKogECJf%\
        2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igw%2BMlxMQoRzKaKGM\
        kIq3ANloBTrUF7fFbgqGjekDwjZoCJkaqB3QGy8C8Agsh5AQRl%2F40pXXjmKXgAxYJi4Oh\
        FkRqUPGfAZKRv1sAqhlhsKvt7ZXjoxlJv5xAVHXR4MF8Zm3Uey3FSnFA0Ws20L%2F5MkdTL\
        Kr1KD37%2BTc4X0Ty8ptnNW%2FbnIFyqKsVCnSijaeTkHMzZ%2BeehRjkLyUlh8r6X2SlY4\
        bTQhAniRYMSLLxLmXXqG7xYKTCO38zDWKyqK1yzh1%2FXQSsJ3Ojjto0TKzg8NRba0tGDiD\
        i3BOpOi3VIuPM4Zw8z7W8BfTNQMdiQycd6TCIrx0%2Fu0pNlEnVizLtHyOkY9ivo2mjj74J\
        G8Z%2FU1iXseQIAul1Fuf0G5VzAIGUpldk9bs9jINER5PCPyCQ%2Fcln42LP36GY%2FsKG0\
        Wpb1g4RMBfyErikrRRdLawnSo8JKp%2BWFjiKFQZMtmhT0aTDMrtq81mwZjNqS7gt6VNoo2\
        vVUyExhqERGeK7swNjJ%2BK02oWXcuvlveNHq2DbsmpJUkSfik%2F5radNTwMKlTMCHJY2p\
        LpLvEjCNa9%2F8DYqOL3oC8qx0mXNa9GKdCT7QxS4uDMNzSkVL4oQMD9AdGcmT%2FLIILgL\
        mbjRvWCLlinod9WEdBQv%2FVceg09pYmXzDV9tO9BjqkAbMYP%2B%2BM07cs%2FZSlhCvpo\
        V%2Fvk4XkVW%2BT3SQFi4I2QfSOAq%2Fq7OxSw0VIjyUM%2B88i12ObpA8Dlaj5F56Qy4ir\
        Zmn1sfjCUbnZhGtPFAFGKkhrG%2FCZFQfGtK5lgb%2BlasRWBXkiCUTuANQ3sw1yDM8FElV\
        4HbJkSAvV2b8w%2Bfnfc4wfVv8SKMuIcsTqF5BfFwJVpFt1vrpV6Ob%2F97V5t%2BFCbikM\
        ZvGo&X-Amz-Signature=82c15ddcaa2cd62fd6061fce8b3badd39a0026d0acc084d8c6\
        e170e59105630c&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-18T23:21:14.356Z"
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
UPDATE_TIME: "2025-02-18T22:22:37.242Z"
EXPIRY_TIME: "2025-02-18T23:22:30.786Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666GHOVBBA%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T222231Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG4aCXVzLXdlc3QtMiJGMEQCID4QP9JUH8blYL%2BOA32nrI84aHrtoXLMl3iZndEOu1enAiAWIAOStHp4zFpmXj2jiNUWuu1Wlcq%2BEA6LM9MIOiYrGiqIBAiX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM%2Fxfk6vF9BcMtB1FMKtwDbl0C2no5UQ5Hh8LJyiVPqqb%2BxAKz1LMtOZ4rqCCG8ODmlDfjbaN1kDUtgrfETZCUlHEhJVKSfY3t8dxfz0OQOiaGeWee3M29haAXvs9Z7WjssMkRla6Lvb5eLicxroLXYdjNmgYEHozvgwtYC2aRSvWb%2FIJ3MRyIUrWTSBMQUEvQutq6G2AvTHHkvflDA6cku0poqxBiGYEHtQlk0korZa64vGIHL3BWyrfzE6Q1Y5kdRlvbTHxSTCElWAlCWB6K3G8hsac3%2FeSmvl7yu%2Bi%2B8DqTA%2FJGWaTKmRzcDrBiky%2FVzwuKTcsNo%2FzicwHv%2BNVWPdYQ1jrDeTlxN9RIatzmY1l%2F6NOVGO6WCXCZziHHCQvz09wTNeUXSko4g0Ps%2Fhjmx85S6NAGkQS%2BCj4Q20EFBJb%2BUh2RkA7zDzZ9xpsDLtG6%2F%2B0rym2Q1aICXKxcp94Tt8iEa2BqqL%2FTcTgkYOsHEYJpq5jhbgJRwJk2dJ0CoNwdPB7ecUlfD%2FbuEUMkUKsSc6qe2858hGeiR2lswRtNNaWAgKaYnbW9%2FVdjGjOqCqTHSHctPTpAf%2BvJhHXKwkA2d0MKivXEGnj%2BGra6qPuetvQZRQ1O92NhW%2B9cX3bUs2Evh9haVNHES%2FBzTAUw1vbTvQY6pgGOpjP89dKWR6NmFl%2BnRaSIaAavStc1329zfsrJTmfx51AsxnxLGdc1FEcKIOMZfyK3tD630TLx%2F1oa8jgC0YRXOJWmhRCITGsVwJwSBfp0BH%2BEh8CouRRad6eeQGvxR4CqIsjMilOjjawZOz5RNeE%2BKX0eKJj6nf%2B9zMOhbA1f636JZnEpFQuTbl3EjujKkN4b7zhx8rnCTCIwWdHwetIvpzsHiiUh&X-Amz-Signature=99479f50d585064b8f672b454ea5d3034db70598466d5711c55ef19cbcf6d695&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666GHOVBBA%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T222231Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG4aCXVzLXdlc3QtMiJGMEQCID4QP9JUH8blYL%2BOA32nrI84aHrtoXLMl3iZndEOu1enAiAWIAOStHp4zFpmXj2jiNUWuu1Wlcq%2BEA6LM9MIOiYrGiqIBAiX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM%2Fxfk6vF9BcMtB1FMKtwDbl0C2no5UQ5Hh8LJyiVPqqb%2BxAKz1LMtOZ4rqCCG8ODmlDfjbaN1kDUtgrfETZCUlHEhJVKSfY3t8dxfz0OQOiaGeWee3M29haAXvs9Z7WjssMkRla6Lvb5eLicxroLXYdjNmgYEHozvgwtYC2aRSvWb%2FIJ3MRyIUrWTSBMQUEvQutq6G2AvTHHkvflDA6cku0poqxBiGYEHtQlk0korZa64vGIHL3BWyrfzE6Q1Y5kdRlvbTHxSTCElWAlCWB6K3G8hsac3%2FeSmvl7yu%2Bi%2B8DqTA%2FJGWaTKmRzcDrBiky%2FVzwuKTcsNo%2FzicwHv%2BNVWPdYQ1jrDeTlxN9RIatzmY1l%2F6NOVGO6WCXCZziHHCQvz09wTNeUXSko4g0Ps%2Fhjmx85S6NAGkQS%2BCj4Q20EFBJb%2BUh2RkA7zDzZ9xpsDLtG6%2F%2B0rym2Q1aICXKxcp94Tt8iEa2BqqL%2FTcTgkYOsHEYJpq5jhbgJRwJk2dJ0CoNwdPB7ecUlfD%2FbuEUMkUKsSc6qe2858hGeiR2lswRtNNaWAgKaYnbW9%2FVdjGjOqCqTHSHctPTpAf%2BvJhHXKwkA2d0MKivXEGnj%2BGra6qPuetvQZRQ1O92NhW%2B9cX3bUs2Evh9haVNHES%2FBzTAUw1vbTvQY6pgGOpjP89dKWR6NmFl%2BnRaSIaAavStc1329zfsrJTmfx51AsxnxLGdc1FEcKIOMZfyK3tD630TLx%2F1oa8jgC0YRXOJWmhRCITGsVwJwSBfp0BH%2BEh8CouRRad6eeQGvxR4CqIsjMilOjjawZOz5RNeE%2BKX0eKJj6nf%2B9zMOhbA1f636JZnEpFQuTbl3EjujKkN4b7zhx8rnCTCIwWdHwetIvpzsHiiUh&X-Amz-Signature=6bda44f3ae042494734af9dc4cf377ce23ca11b290a853add38603fb2bbdc8bc&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666GHOVBBA%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T222231Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG4aCXVzLXdlc3QtMiJGMEQCID4QP9JUH8blYL%2BOA32nrI84aHrtoXLMl3iZndEOu1enAiAWIAOStHp4zFpmXj2jiNUWuu1Wlcq%2BEA6LM9MIOiYrGiqIBAiX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM%2Fxfk6vF9BcMtB1FMKtwDbl0C2no5UQ5Hh8LJyiVPqqb%2BxAKz1LMtOZ4rqCCG8ODmlDfjbaN1kDUtgrfETZCUlHEhJVKSfY3t8dxfz0OQOiaGeWee3M29haAXvs9Z7WjssMkRla6Lvb5eLicxroLXYdjNmgYEHozvgwtYC2aRSvWb%2FIJ3MRyIUrWTSBMQUEvQutq6G2AvTHHkvflDA6cku0poqxBiGYEHtQlk0korZa64vGIHL3BWyrfzE6Q1Y5kdRlvbTHxSTCElWAlCWB6K3G8hsac3%2FeSmvl7yu%2Bi%2B8DqTA%2FJGWaTKmRzcDrBiky%2FVzwuKTcsNo%2FzicwHv%2BNVWPdYQ1jrDeTlxN9RIatzmY1l%2F6NOVGO6WCXCZziHHCQvz09wTNeUXSko4g0Ps%2Fhjmx85S6NAGkQS%2BCj4Q20EFBJb%2BUh2RkA7zDzZ9xpsDLtG6%2F%2B0rym2Q1aICXKxcp94Tt8iEa2BqqL%2FTcTgkYOsHEYJpq5jhbgJRwJk2dJ0CoNwdPB7ecUlfD%2FbuEUMkUKsSc6qe2858hGeiR2lswRtNNaWAgKaYnbW9%2FVdjGjOqCqTHSHctPTpAf%2BvJhHXKwkA2d0MKivXEGnj%2BGra6qPuetvQZRQ1O92NhW%2B9cX3bUs2Evh9haVNHES%2FBzTAUw1vbTvQY6pgGOpjP89dKWR6NmFl%2BnRaSIaAavStc1329zfsrJTmfx51AsxnxLGdc1FEcKIOMZfyK3tD630TLx%2F1oa8jgC0YRXOJWmhRCITGsVwJwSBfp0BH%2BEh8CouRRad6eeQGvxR4CqIsjMilOjjawZOz5RNeE%2BKX0eKJj6nf%2B9zMOhbA1f636JZnEpFQuTbl3EjujKkN4b7zhx8rnCTCIwWdHwetIvpzsHiiUh&X-Amz-Signature=16e761a7c59eb78cddabea2fc72b0faed3a59e222a0c3b2ab7650cda490c5e27&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666GHOVBBA%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T222231Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG4aCXVzLXdlc3QtMiJGMEQCID4QP9JUH8blYL%2BOA32nrI84aHrtoXLMl3iZndEOu1enAiAWIAOStHp4zFpmXj2jiNUWuu1Wlcq%2BEA6LM9MIOiYrGiqIBAiX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM%2Fxfk6vF9BcMtB1FMKtwDbl0C2no5UQ5Hh8LJyiVPqqb%2BxAKz1LMtOZ4rqCCG8ODmlDfjbaN1kDUtgrfETZCUlHEhJVKSfY3t8dxfz0OQOiaGeWee3M29haAXvs9Z7WjssMkRla6Lvb5eLicxroLXYdjNmgYEHozvgwtYC2aRSvWb%2FIJ3MRyIUrWTSBMQUEvQutq6G2AvTHHkvflDA6cku0poqxBiGYEHtQlk0korZa64vGIHL3BWyrfzE6Q1Y5kdRlvbTHxSTCElWAlCWB6K3G8hsac3%2FeSmvl7yu%2Bi%2B8DqTA%2FJGWaTKmRzcDrBiky%2FVzwuKTcsNo%2FzicwHv%2BNVWPdYQ1jrDeTlxN9RIatzmY1l%2F6NOVGO6WCXCZziHHCQvz09wTNeUXSko4g0Ps%2Fhjmx85S6NAGkQS%2BCj4Q20EFBJb%2BUh2RkA7zDzZ9xpsDLtG6%2F%2B0rym2Q1aICXKxcp94Tt8iEa2BqqL%2FTcTgkYOsHEYJpq5jhbgJRwJk2dJ0CoNwdPB7ecUlfD%2FbuEUMkUKsSc6qe2858hGeiR2lswRtNNaWAgKaYnbW9%2FVdjGjOqCqTHSHctPTpAf%2BvJhHXKwkA2d0MKivXEGnj%2BGra6qPuetvQZRQ1O92NhW%2B9cX3bUs2Evh9haVNHES%2FBzTAUw1vbTvQY6pgGOpjP89dKWR6NmFl%2BnRaSIaAavStc1329zfsrJTmfx51AsxnxLGdc1FEcKIOMZfyK3tD630TLx%2F1oa8jgC0YRXOJWmhRCITGsVwJwSBfp0BH%2BEh8CouRRad6eeQGvxR4CqIsjMilOjjawZOz5RNeE%2BKX0eKJj6nf%2B9zMOhbA1f636JZnEpFQuTbl3EjujKkN4b7zhx8rnCTCIwWdHwetIvpzsHiiUh&X-Amz-Signature=20f21e120512b0e3eae5551a118bcaa4584a94b738955702374dcbc0e96e6647&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666GHOVBBA%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T222231Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG4aCXVzLXdlc3QtMiJGMEQCID4QP9JUH8blYL%2BOA32nrI84aHrtoXLMl3iZndEOu1enAiAWIAOStHp4zFpmXj2jiNUWuu1Wlcq%2BEA6LM9MIOiYrGiqIBAiX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM%2Fxfk6vF9BcMtB1FMKtwDbl0C2no5UQ5Hh8LJyiVPqqb%2BxAKz1LMtOZ4rqCCG8ODmlDfjbaN1kDUtgrfETZCUlHEhJVKSfY3t8dxfz0OQOiaGeWee3M29haAXvs9Z7WjssMkRla6Lvb5eLicxroLXYdjNmgYEHozvgwtYC2aRSvWb%2FIJ3MRyIUrWTSBMQUEvQutq6G2AvTHHkvflDA6cku0poqxBiGYEHtQlk0korZa64vGIHL3BWyrfzE6Q1Y5kdRlvbTHxSTCElWAlCWB6K3G8hsac3%2FeSmvl7yu%2Bi%2B8DqTA%2FJGWaTKmRzcDrBiky%2FVzwuKTcsNo%2FzicwHv%2BNVWPdYQ1jrDeTlxN9RIatzmY1l%2F6NOVGO6WCXCZziHHCQvz09wTNeUXSko4g0Ps%2Fhjmx85S6NAGkQS%2BCj4Q20EFBJb%2BUh2RkA7zDzZ9xpsDLtG6%2F%2B0rym2Q1aICXKxcp94Tt8iEa2BqqL%2FTcTgkYOsHEYJpq5jhbgJRwJk2dJ0CoNwdPB7ecUlfD%2FbuEUMkUKsSc6qe2858hGeiR2lswRtNNaWAgKaYnbW9%2FVdjGjOqCqTHSHctPTpAf%2BvJhHXKwkA2d0MKivXEGnj%2BGra6qPuetvQZRQ1O92NhW%2B9cX3bUs2Evh9haVNHES%2FBzTAUw1vbTvQY6pgGOpjP89dKWR6NmFl%2BnRaSIaAavStc1329zfsrJTmfx51AsxnxLGdc1FEcKIOMZfyK3tD630TLx%2F1oa8jgC0YRXOJWmhRCITGsVwJwSBfp0BH%2BEh8CouRRad6eeQGvxR4CqIsjMilOjjawZOz5RNeE%2BKX0eKJj6nf%2B9zMOhbA1f636JZnEpFQuTbl3EjujKkN4b7zhx8rnCTCIwWdHwetIvpzsHiiUh&X-Amz-Signature=ba68ffc837b95279e7e3cf99cbbad75f89dd13a927d4753a36f92ebf3300a29b&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466S2PLDUBU%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T222231Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG4aCXVzLXdlc3QtMiJGMEQCIC%2Ffwg7Bvu5WrJdi%2Fk%2Fmovhv6OhoxWFTfHovNePELK8zAiA7h%2FHkM1WvkW78OIpgaH1K8PGSdREkw7uAbkV86rorCCqIBAiX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMyKVm8R%2Fxf65lDiUFKtwDabGTX5L7McxydHhdZopAjdszl5YGO5B5ZrbWVBTaQ0RKR0GTyRBWg9FUF1XVSHCQPNi7c9S%2B%2Bzb9Rsn4zloE%2FqauJffjYQdOEQW6Uw7rs3moRSdTksSNrrGtf9v5v85UXWyAAw%2FNowXWOmuYPT7pXD6TWWNHXVoisVnde1l%2FzA29nXF7pYrdo6TBX6Vi16CrtuBSo6fN4juFOWUPK4mDiZFKCDGBXhgJknYEHH9P8pZJQFbwKXRrGw3DgnBfkXNIUWq1Yp8OHtm0VZSN5lHDDJh1U%2BHxB2TqWvDFRmrhzQnuurBfEvKK%2BiKJgdJPc3A7rslQe6THo%2FxGmqdGSm5ZjNaPoGDYJsjDGpw6rlZZrt6ZURlW4yMRcKu1t7ockkYvt39qsIy%2BgWvGsVXozX32%2F2NZP7IwFPbDfsX%2FHHOhH90igQHR1ZX7JUPljmYv93gFUtuwbZdkJJgHGevUEbVq06J6aH%2Fy1VdIF4cTrmND%2F0S2qOlW6IR5c9lmeXDPIfco4rUVbR4LyRqly1j1DPHjDhI%2Fa%2BTr2lPu1dy8fABSkx%2FjkXTguE7e7tjBwPeDahQQk421Kb8X4NQHm4T3WkSsta%2FHOmvfOtLVhGjegI6GOlEHiArP9p895eWm1Iowj%2FfTvQY6pgHs2yYbCn5L%2Bl%2FCuizTrcJ7EjFMz5KkQGK%2BCeS3G4%2BUJL7eTpKbHNbQR09us5QInugWvUQyyhn%2FGy27FhwGfdmLNflOA35IQAymz%2BP3RzqWHHgyl08BDtomDfjXxW0siRUd%2BXW2jOtQ8%2FDhlScvulINrwXAhM3JnrtceZaEvvZUZxE0vNJd4ZKH73Q6NXMzOTfw6%2Fc70tfG9jHbblzPdbsXinyn8MGW&X-Amz-Signature=53493db0a0ee7b239b47b90ff7da18faccb43a82d062513d1c46be748b6b6532&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WU4TWRVH%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T222232Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG4aCXVzLXdlc3QtMiJHMEUCIQDJSuuW75p6bLW6wOREw%2Bdnt9M4mPJxXimsi%2BMXwOsviAIgSNWRMliiN0Sn7%2B6gywMXsjm9%2Fo5qCqwDg4K%2FilyWQRUqiAQIl%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDK2Pu8PDCQR5yWW6DircA7zUzGEY5DTZQ%2BAc%2FYQ9sPUXmvxLMXM0H%2FCINC4wX1mMT2tbuMyVFD53w2pbZe4x2K0Y%2FLAHW7p2KRWL8raP72ghjWjHuArLVdFL5GtkZI%2FMfk5rM6Dk6yJFSXYE%2FHNVDc1o%2FWITsBQnYclqQTCaum%2F1Gc4kfxtUW2aoAqb%2B8KJjtoKiOjG4fx4h7IkGYIhZHcBQeN%2BaR9iBIECPPCGyjLmP2WNswI3uJSm5Q9vaDh3uUwIHvx%2BbpA3QLLYvyb1bZYDDLFsNo9DbBy%2Fr792N2RgREJhy3pd2fjAZJ%2F3kYRghIWV0t0PWMtBt9IijpsmjxBfyB%2FF%2BO6G0iXoYlou%2FoRVk69Jr5HRWxObkkH3wdV0IKkAfoJytj5HPyDdiyAEB%2BXLEa4KlZ9XLXvbCM8fNikwSZVRevqAyssamvEHKgoLB8fJh1z6iPcAyCNW4%2Fe2JjpZfoHXal45sp3TDXT9PeNc93Fb7ILglBhhF0qJ92l5vZWLXTX9d0w6xrYo5uQzoG%2F4KJcAUMwjlmZzedeHttKC%2FHsZg9yXlS%2F57dsIvNBgiLdpFgXkJ6uXleqgSKfFy47BNn2lUhSnELUZPvgtU792NGA57gxcNf0jMYUYplsG%2FIf1P5hvAg2iQh8dMMN72070GOqUBhHOuht%2FF6xfvZ%2BMgJhJkv36uEwhlt3I%2BiP1RCRMMzLB3ANe8SF%2FG0E5i3ECD1rXt7kL6%2BFWXY%2Bo75XgtfyFq97%2F6mYnwHzF1PPuQG1ytICcgRy1NLYJzXKBOb4S5p1nsE9d%2BqUdftAxRimQWH61GdtUJ%2BciSCeNz7it366stAIvFz06NRxRZogdCmBqJ%2Fxq83rbn0dfjSK5JhWQ7cFypR5n97JRO&X-Amz-Signature=5eaddc3cca7ce69cd0b834eb9dee5904cf371203b2b22908a51f26547417999f&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666GHOVBBA%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T222231Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG4aCXVzLXdlc3QtMiJGMEQCID4QP9JUH8blYL%2BOA32nrI84aHrtoXLMl3iZndEOu1enAiAWIAOStHp4zFpmXj2jiNUWuu1Wlcq%2BEA6LM9MIOiYrGiqIBAiX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM%2Fxfk6vF9BcMtB1FMKtwDbl0C2no5UQ5Hh8LJyiVPqqb%2BxAKz1LMtOZ4rqCCG8ODmlDfjbaN1kDUtgrfETZCUlHEhJVKSfY3t8dxfz0OQOiaGeWee3M29haAXvs9Z7WjssMkRla6Lvb5eLicxroLXYdjNmgYEHozvgwtYC2aRSvWb%2FIJ3MRyIUrWTSBMQUEvQutq6G2AvTHHkvflDA6cku0poqxBiGYEHtQlk0korZa64vGIHL3BWyrfzE6Q1Y5kdRlvbTHxSTCElWAlCWB6K3G8hsac3%2FeSmvl7yu%2Bi%2B8DqTA%2FJGWaTKmRzcDrBiky%2FVzwuKTcsNo%2FzicwHv%2BNVWPdYQ1jrDeTlxN9RIatzmY1l%2F6NOVGO6WCXCZziHHCQvz09wTNeUXSko4g0Ps%2Fhjmx85S6NAGkQS%2BCj4Q20EFBJb%2BUh2RkA7zDzZ9xpsDLtG6%2F%2B0rym2Q1aICXKxcp94Tt8iEa2BqqL%2FTcTgkYOsHEYJpq5jhbgJRwJk2dJ0CoNwdPB7ecUlfD%2FbuEUMkUKsSc6qe2858hGeiR2lswRtNNaWAgKaYnbW9%2FVdjGjOqCqTHSHctPTpAf%2BvJhHXKwkA2d0MKivXEGnj%2BGra6qPuetvQZRQ1O92NhW%2B9cX3bUs2Evh9haVNHES%2FBzTAUw1vbTvQY6pgGOpjP89dKWR6NmFl%2BnRaSIaAavStc1329zfsrJTmfx51AsxnxLGdc1FEcKIOMZfyK3tD630TLx%2F1oa8jgC0YRXOJWmhRCITGsVwJwSBfp0BH%2BEh8CouRRad6eeQGvxR4CqIsjMilOjjawZOz5RNeE%2BKX0eKJj6nf%2B9zMOhbA1f636JZnEpFQuTbl3EjujKkN4b7zhx8rnCTCIwWdHwetIvpzsHiiUh&X-Amz-Signature=e337b682674b6f71be5047883793d1e86d945c7b27f50214cd4d5b2377b100ac&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666GHOVBBA%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T222231Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG4aCXVzLXdlc3QtMiJGMEQCID4QP9JUH8blYL%2BOA32nrI84aHrtoXLMl3iZndEOu1enAiAWIAOStHp4zFpmXj2jiNUWuu1Wlcq%2BEA6LM9MIOiYrGiqIBAiX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM%2Fxfk6vF9BcMtB1FMKtwDbl0C2no5UQ5Hh8LJyiVPqqb%2BxAKz1LMtOZ4rqCCG8ODmlDfjbaN1kDUtgrfETZCUlHEhJVKSfY3t8dxfz0OQOiaGeWee3M29haAXvs9Z7WjssMkRla6Lvb5eLicxroLXYdjNmgYEHozvgwtYC2aRSvWb%2FIJ3MRyIUrWTSBMQUEvQutq6G2AvTHHkvflDA6cku0poqxBiGYEHtQlk0korZa64vGIHL3BWyrfzE6Q1Y5kdRlvbTHxSTCElWAlCWB6K3G8hsac3%2FeSmvl7yu%2Bi%2B8DqTA%2FJGWaTKmRzcDrBiky%2FVzwuKTcsNo%2FzicwHv%2BNVWPdYQ1jrDeTlxN9RIatzmY1l%2F6NOVGO6WCXCZziHHCQvz09wTNeUXSko4g0Ps%2Fhjmx85S6NAGkQS%2BCj4Q20EFBJb%2BUh2RkA7zDzZ9xpsDLtG6%2F%2B0rym2Q1aICXKxcp94Tt8iEa2BqqL%2FTcTgkYOsHEYJpq5jhbgJRwJk2dJ0CoNwdPB7ecUlfD%2FbuEUMkUKsSc6qe2858hGeiR2lswRtNNaWAgKaYnbW9%2FVdjGjOqCqTHSHctPTpAf%2BvJhHXKwkA2d0MKivXEGnj%2BGra6qPuetvQZRQ1O92NhW%2B9cX3bUs2Evh9haVNHES%2FBzTAUw1vbTvQY6pgGOpjP89dKWR6NmFl%2BnRaSIaAavStc1329zfsrJTmfx51AsxnxLGdc1FEcKIOMZfyK3tD630TLx%2F1oa8jgC0YRXOJWmhRCITGsVwJwSBfp0BH%2BEh8CouRRad6eeQGvxR4CqIsjMilOjjawZOz5RNeE%2BKX0eKJj6nf%2B9zMOhbA1f636JZnEpFQuTbl3EjujKkN4b7zhx8rnCTCIwWdHwetIvpzsHiiUh&X-Amz-Signature=842bff4cb7e8d0125a922b838808484d9a5c8e71a01f46a55724cc04cda4f1f4&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666GHOVBBA%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T222231Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG4aCXVzLXdlc3QtMiJGMEQCID4QP9JUH8blYL%2BOA32nrI84aHrtoXLMl3iZndEOu1enAiAWIAOStHp4zFpmXj2jiNUWuu1Wlcq%2BEA6LM9MIOiYrGiqIBAiX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM%2Fxfk6vF9BcMtB1FMKtwDbl0C2no5UQ5Hh8LJyiVPqqb%2BxAKz1LMtOZ4rqCCG8ODmlDfjbaN1kDUtgrfETZCUlHEhJVKSfY3t8dxfz0OQOiaGeWee3M29haAXvs9Z7WjssMkRla6Lvb5eLicxroLXYdjNmgYEHozvgwtYC2aRSvWb%2FIJ3MRyIUrWTSBMQUEvQutq6G2AvTHHkvflDA6cku0poqxBiGYEHtQlk0korZa64vGIHL3BWyrfzE6Q1Y5kdRlvbTHxSTCElWAlCWB6K3G8hsac3%2FeSmvl7yu%2Bi%2B8DqTA%2FJGWaTKmRzcDrBiky%2FVzwuKTcsNo%2FzicwHv%2BNVWPdYQ1jrDeTlxN9RIatzmY1l%2F6NOVGO6WCXCZziHHCQvz09wTNeUXSko4g0Ps%2Fhjmx85S6NAGkQS%2BCj4Q20EFBJb%2BUh2RkA7zDzZ9xpsDLtG6%2F%2B0rym2Q1aICXKxcp94Tt8iEa2BqqL%2FTcTgkYOsHEYJpq5jhbgJRwJk2dJ0CoNwdPB7ecUlfD%2FbuEUMkUKsSc6qe2858hGeiR2lswRtNNaWAgKaYnbW9%2FVdjGjOqCqTHSHctPTpAf%2BvJhHXKwkA2d0MKivXEGnj%2BGra6qPuetvQZRQ1O92NhW%2B9cX3bUs2Evh9haVNHES%2FBzTAUw1vbTvQY6pgGOpjP89dKWR6NmFl%2BnRaSIaAavStc1329zfsrJTmfx51AsxnxLGdc1FEcKIOMZfyK3tD630TLx%2F1oa8jgC0YRXOJWmhRCITGsVwJwSBfp0BH%2BEh8CouRRad6eeQGvxR4CqIsjMilOjjawZOz5RNeE%2BKX0eKJj6nf%2B9zMOhbA1f636JZnEpFQuTbl3EjujKkN4b7zhx8rnCTCIwWdHwetIvpzsHiiUh&X-Amz-Signature=6e3a1ffd2e7a262326c35bb0b82fd5a291743e5e3e6753f51ef13d2740c7379c&X-Amz-SignedHeaders=host&x-id=GetObject)


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

