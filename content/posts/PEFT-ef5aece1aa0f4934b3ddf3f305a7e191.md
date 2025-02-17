---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466S55XYQQO%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250217T172105Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEFEaCXVzLXdlc3QtMiJHMEUCIQCo7JH16sUIo792rBJjTsZK5YuWQkQ1l9rjHjs8P7EpfgIgb%2\
  BmdunV9yj8Q7ICASCD6a%2FQ5s%2F1oZKifhpbYA%2B5ocP0q%2FwMIeRAAGgw2Mzc0MjMxODM4MD\
  UiDCTZHsT30XtSdsNvDSrcA%2BDnS7S8e4ODVVzcGgFxsBw%2BgbqjH4CF3Eyp3LyRXGqn%2FXqVQ\
  lLR3i%2FxuIDcd8EPfOxUuBvoVddnIDCX5geXRtzpo%2F9NdKq26TTvioCBOmqNC9wCTF9LVLlBCM\
  Dolt0FNa9LqU7KllZQdzKyhjP8LU2RPzUcIAYlXhU0da%2F8agJ55gCEwsJzODrsULHZ9Vgr3yRnP\
  kItiT3iJOPoVTzGGGwesk5MMuthFuH4x4pW8%2FHRF4tDxgZmSCM84Ui1%2BJTJ%2Bj7mjoDnMvGa\
  B3bv7SBUYdI079LkLbeKYxG3b49pxajHjOukigl%2BFWobyQ0wMoB2CnvH7yTljTQK4Le2tRlxhMk\
  8tRzGP6GOGBwkaorxjqyBMFIGISZvjJarGymUDBQy2wd0yZ2O4VBq2w53fjcYkYS486ZdGMsGtdSd\
  5%2BD9aUH8nV7E8M%2BheZZM0AylSfTE%2FdfWcafqb0wJLBDBl1K8RON5Mc1yu87%2FrPKDNM0uE\
  qdxS1RwJjJY2PgP0HmT1RuOuJSZ6MuR9ZdxqVyXGczuLvv8ASH2OexcOCHHRBYiR3uDaiTwoNHyp2\
  %2FSorWNdaO4i7JOUxcR%2FAoOwzgPKkHicvTICZDuBZfddHKltxjAY63zjKu%2BeEDVbIFj0DzMM\
  MDDzb0GOqUBpDf7zCizKdSg9j9P3vUyzSrP0uHH3fUs8rwbThRg0BKluhu5%2Fz44K6EDbKAtJRcv\
  y9NGZ5lnt4xAdbKrAOQplSTW5N1i%2Fr8jZbkw95wbzoOhnAQsZyLxZ5KiFbQ7PDPkM8I47dJD%2F\
  Vx3aQsSrML042V7YQ41o%2B7vYbRwkMWFOvJhpBp3W8GjR2MJD3Btxw0KQyU5CNOBEN0hBfBEVeF2\
  S7Fl%2FUkY&X-Amz-Signature=60033ac52312c54fe3dc283ff68d231989729a3daa87d378f3\
  728edadae42239&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466UMIEWOVR%2F20250217%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250217T171933Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEFEaCXVzLXdlc3QtMiJIMEYCIQCrKRzivylPHw0yMwDIh5X7LWyOmuO\
        01EJ0EHUWA%2F8g7AIhAP9NtOg0nNRQ21MzN%2F3THwbm7GvM%2F87lx8R0SxtWczfEKv8D\
        CHkQABoMNjM3NDIzMTgzODA1IgzkODeNPrx1qbrLtt8q3APeA9xM8fTiH4pscfGzRu5FUZw\
        pq5oDTJy%2Bld9zGTbhLMC%2BhBsNQ8IbVak30cRGwMvzy4PmJz0wx79mnLBBoNBYo8Sjsf\
        2pzS9X81DewwH70mgmuO7iXf144CHhUi9l6c7K1Oo3fH%2FwpSVCUthLwncMw8ydzK4TxVP\
        %2B13Tc740nHUA9BOOlsjRAIHmcMfi%2BhRh0SpLGHoQGcxQ5AXfhhoNqBbWfDRcKv6UiNw\
        QzNLuTazGeEkfnB9ptd2K2ZBxAmkPxJtN93%2BT71PFZQ91xos4EiCG01ge594LoVuxZU6D\
        y1rZkTNLrm4qGyDzfZv6gk9Yq6SCUQNTM%2FjN3d7TPjIGPL9AkXZny%2BBGFfgybhjDOpD\
        xbgwxdBhG7ci9zRF5QZs%2B84Ci88GiMFNGTIy%2FHHjkQsaWeQTH1T0sfjby8SZwDGIihF\
        lT1sWTrCuqGdiAumJJMVYb1%2BKOZZdLjQ%2FfLXKB7%2BZ8CBkiM33f%2FP32azy8%2B%2\
        BPkm7aKsAi%2BcDxqGYmhm7njoIIPxV7gJdOB%2Bb6e7gE5jyqKPZECozlngnmeF7RT%2F6\
        AhGMAEaujIYowD1YLZKrm62pzsym5DlnMwi24OheKL2ZWEGFKjyr2A%2FSwG%2B0kGwrtrx\
        7z%2B0vlt3VWmGsDDHws29BjqkAXXtLOj5JoxhHg4ny8jaJsG0FbXAdDS%2FrgjBOZs20xJ\
        ock9ouyYoa88rpZjQw2W6Xau2dxK0m9otZLjr5FMS%2Bg2%2FGbViJu124fIFIPFohuy5a8\
        FyGCzYXTD%2Fw7Ce3ePTs0yMV55jn4CjAZ4bCK%2Bz%2By6ZaUS2%2FRhQbANETpjodeFmD\
        HDCIhpKuW05moM94EGJIdSKLH1y9QLY5Fd5vMt62v2CneXW&X-Amz-Signature=70ee1eb\
        e14994fde8d6875b5a20541bd49f2bcdcd0921a1febfa93a999d7a65c&X-Amz-SignedH\
        eaders=host&x-id=GetObject"
      expiry_time: "2025-02-17T18:19:33.477Z"
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
UPDATE_TIME: "2025-02-17T17:21:14.574Z"
EXPIRY_TIME: "2025-02-17T18:21:02.569Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YCWOZ5U5%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T172103Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFAaCXVzLXdlc3QtMiJHMEUCIQDP2sMGnBK5cEKCDtQOElgMdgH6R1KnQSuOmEbGI9zmqwIgPEM%2BfYtVUhTt23COgfymJRDaf7Qvj01FPVv5co%2BYX88q%2FwMIeRAAGgw2Mzc0MjMxODM4MDUiDLM1aCtduqj2jmdGuSrcA6yVhUiFLOnJ3jGknVHs%2FRxfRuI6mIViuMYE8eHgt2%2FraoHc8uYGgkjjxTZ9iP5FQ0DpI%2F0p0hFdRBPO6aYLauzYiSvbpk1tAX1z7JB6AwHwx7RswHpkIa%2BL4scvSSv4Vdv0eNGR45qQjO33kR4gwjxSQDDLNW5sia0b3kN%2BOrNjUilgqFhCFhgB1NR8LJKIzKe91OF%2FOixH8Oa76YR%2Bij5wtx%2FN7W49U%2F%2FDl%2BbOIM79IaQ7ALth8psUwJOPO6nac4AeFFCOfxgwemhEsx4isX2ZiMyPlT%2FJa%2BxGKK9E1CJ6dYvZgdMUeHxrhEeafa0wBRTYX%2FNib9Db3MDDTy4UeKE9wivThIYLnZAEpMJWElbu7IWNtpqx14x0JDysoXOhWKafgpIp7QGHV2LwRd51hqtgCvJHQ0EZk9rsqZd6wr69N%2F9woSVg22SVNuxac8SiPtApp4jskUl1tzdJ8EGeqPUGh7kjnB%2FIMyHEpz2t%2B4YASQJSJAG%2F90ntpAlTYVZ4MITON5O1udEMg4avYeHqclQJMQpAckgCua8OMb00m84MIljfjJ4Whw0iEYFX71P3S8Kuyagze0ly1SJetoS0kuVXDFckwH8Ym6Oq%2BGVL4H7XWgiqbqp29dv6MT%2FpMJrCzb0GOqUB3R384W0%2FgnnzUas3pajEZn2VYCW4i48KO5F64zwbutca1bs99XN2PUmOZjFo7P48dYrj8gRBMko6qhKFbRlMEk5l8wH2zWCuPauW0%2FKCnnXAusqrGUrla%2FG8OMPi1PgcPRSdq0KvQG20VAqwZTdZjdeZu9qtaA7tvn4m8Y9ozNl09ix9dkEIxjfRG7JS8SxvZTMC79aaQLZvLiUfqIvaVO6TICz0&X-Amz-Signature=c6f8b931f3f942281e19f75c3c3fc7a2a1c7105efbe72adf0a01414323e049d8&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YCWOZ5U5%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T172103Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFAaCXVzLXdlc3QtMiJHMEUCIQDP2sMGnBK5cEKCDtQOElgMdgH6R1KnQSuOmEbGI9zmqwIgPEM%2BfYtVUhTt23COgfymJRDaf7Qvj01FPVv5co%2BYX88q%2FwMIeRAAGgw2Mzc0MjMxODM4MDUiDLM1aCtduqj2jmdGuSrcA6yVhUiFLOnJ3jGknVHs%2FRxfRuI6mIViuMYE8eHgt2%2FraoHc8uYGgkjjxTZ9iP5FQ0DpI%2F0p0hFdRBPO6aYLauzYiSvbpk1tAX1z7JB6AwHwx7RswHpkIa%2BL4scvSSv4Vdv0eNGR45qQjO33kR4gwjxSQDDLNW5sia0b3kN%2BOrNjUilgqFhCFhgB1NR8LJKIzKe91OF%2FOixH8Oa76YR%2Bij5wtx%2FN7W49U%2F%2FDl%2BbOIM79IaQ7ALth8psUwJOPO6nac4AeFFCOfxgwemhEsx4isX2ZiMyPlT%2FJa%2BxGKK9E1CJ6dYvZgdMUeHxrhEeafa0wBRTYX%2FNib9Db3MDDTy4UeKE9wivThIYLnZAEpMJWElbu7IWNtpqx14x0JDysoXOhWKafgpIp7QGHV2LwRd51hqtgCvJHQ0EZk9rsqZd6wr69N%2F9woSVg22SVNuxac8SiPtApp4jskUl1tzdJ8EGeqPUGh7kjnB%2FIMyHEpz2t%2B4YASQJSJAG%2F90ntpAlTYVZ4MITON5O1udEMg4avYeHqclQJMQpAckgCua8OMb00m84MIljfjJ4Whw0iEYFX71P3S8Kuyagze0ly1SJetoS0kuVXDFckwH8Ym6Oq%2BGVL4H7XWgiqbqp29dv6MT%2FpMJrCzb0GOqUB3R384W0%2FgnnzUas3pajEZn2VYCW4i48KO5F64zwbutca1bs99XN2PUmOZjFo7P48dYrj8gRBMko6qhKFbRlMEk5l8wH2zWCuPauW0%2FKCnnXAusqrGUrla%2FG8OMPi1PgcPRSdq0KvQG20VAqwZTdZjdeZu9qtaA7tvn4m8Y9ozNl09ix9dkEIxjfRG7JS8SxvZTMC79aaQLZvLiUfqIvaVO6TICz0&X-Amz-Signature=b02c76950ac99db002b6115dc147fbb6651bd9cce58f3ae4aadcb8a7768c57d4&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YCWOZ5U5%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T172103Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFAaCXVzLXdlc3QtMiJHMEUCIQDP2sMGnBK5cEKCDtQOElgMdgH6R1KnQSuOmEbGI9zmqwIgPEM%2BfYtVUhTt23COgfymJRDaf7Qvj01FPVv5co%2BYX88q%2FwMIeRAAGgw2Mzc0MjMxODM4MDUiDLM1aCtduqj2jmdGuSrcA6yVhUiFLOnJ3jGknVHs%2FRxfRuI6mIViuMYE8eHgt2%2FraoHc8uYGgkjjxTZ9iP5FQ0DpI%2F0p0hFdRBPO6aYLauzYiSvbpk1tAX1z7JB6AwHwx7RswHpkIa%2BL4scvSSv4Vdv0eNGR45qQjO33kR4gwjxSQDDLNW5sia0b3kN%2BOrNjUilgqFhCFhgB1NR8LJKIzKe91OF%2FOixH8Oa76YR%2Bij5wtx%2FN7W49U%2F%2FDl%2BbOIM79IaQ7ALth8psUwJOPO6nac4AeFFCOfxgwemhEsx4isX2ZiMyPlT%2FJa%2BxGKK9E1CJ6dYvZgdMUeHxrhEeafa0wBRTYX%2FNib9Db3MDDTy4UeKE9wivThIYLnZAEpMJWElbu7IWNtpqx14x0JDysoXOhWKafgpIp7QGHV2LwRd51hqtgCvJHQ0EZk9rsqZd6wr69N%2F9woSVg22SVNuxac8SiPtApp4jskUl1tzdJ8EGeqPUGh7kjnB%2FIMyHEpz2t%2B4YASQJSJAG%2F90ntpAlTYVZ4MITON5O1udEMg4avYeHqclQJMQpAckgCua8OMb00m84MIljfjJ4Whw0iEYFX71P3S8Kuyagze0ly1SJetoS0kuVXDFckwH8Ym6Oq%2BGVL4H7XWgiqbqp29dv6MT%2FpMJrCzb0GOqUB3R384W0%2FgnnzUas3pajEZn2VYCW4i48KO5F64zwbutca1bs99XN2PUmOZjFo7P48dYrj8gRBMko6qhKFbRlMEk5l8wH2zWCuPauW0%2FKCnnXAusqrGUrla%2FG8OMPi1PgcPRSdq0KvQG20VAqwZTdZjdeZu9qtaA7tvn4m8Y9ozNl09ix9dkEIxjfRG7JS8SxvZTMC79aaQLZvLiUfqIvaVO6TICz0&X-Amz-Signature=f34d9c2ab018124c77a96fb43e014cec915396353c45759da2100088d8ebb52b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YCWOZ5U5%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T172103Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFAaCXVzLXdlc3QtMiJHMEUCIQDP2sMGnBK5cEKCDtQOElgMdgH6R1KnQSuOmEbGI9zmqwIgPEM%2BfYtVUhTt23COgfymJRDaf7Qvj01FPVv5co%2BYX88q%2FwMIeRAAGgw2Mzc0MjMxODM4MDUiDLM1aCtduqj2jmdGuSrcA6yVhUiFLOnJ3jGknVHs%2FRxfRuI6mIViuMYE8eHgt2%2FraoHc8uYGgkjjxTZ9iP5FQ0DpI%2F0p0hFdRBPO6aYLauzYiSvbpk1tAX1z7JB6AwHwx7RswHpkIa%2BL4scvSSv4Vdv0eNGR45qQjO33kR4gwjxSQDDLNW5sia0b3kN%2BOrNjUilgqFhCFhgB1NR8LJKIzKe91OF%2FOixH8Oa76YR%2Bij5wtx%2FN7W49U%2F%2FDl%2BbOIM79IaQ7ALth8psUwJOPO6nac4AeFFCOfxgwemhEsx4isX2ZiMyPlT%2FJa%2BxGKK9E1CJ6dYvZgdMUeHxrhEeafa0wBRTYX%2FNib9Db3MDDTy4UeKE9wivThIYLnZAEpMJWElbu7IWNtpqx14x0JDysoXOhWKafgpIp7QGHV2LwRd51hqtgCvJHQ0EZk9rsqZd6wr69N%2F9woSVg22SVNuxac8SiPtApp4jskUl1tzdJ8EGeqPUGh7kjnB%2FIMyHEpz2t%2B4YASQJSJAG%2F90ntpAlTYVZ4MITON5O1udEMg4avYeHqclQJMQpAckgCua8OMb00m84MIljfjJ4Whw0iEYFX71P3S8Kuyagze0ly1SJetoS0kuVXDFckwH8Ym6Oq%2BGVL4H7XWgiqbqp29dv6MT%2FpMJrCzb0GOqUB3R384W0%2FgnnzUas3pajEZn2VYCW4i48KO5F64zwbutca1bs99XN2PUmOZjFo7P48dYrj8gRBMko6qhKFbRlMEk5l8wH2zWCuPauW0%2FKCnnXAusqrGUrla%2FG8OMPi1PgcPRSdq0KvQG20VAqwZTdZjdeZu9qtaA7tvn4m8Y9ozNl09ix9dkEIxjfRG7JS8SxvZTMC79aaQLZvLiUfqIvaVO6TICz0&X-Amz-Signature=03ce4abedab6b51c2bb996aed56b5269afab5f3082552c85507d95e9b03ca59d&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YCWOZ5U5%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T172103Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFAaCXVzLXdlc3QtMiJHMEUCIQDP2sMGnBK5cEKCDtQOElgMdgH6R1KnQSuOmEbGI9zmqwIgPEM%2BfYtVUhTt23COgfymJRDaf7Qvj01FPVv5co%2BYX88q%2FwMIeRAAGgw2Mzc0MjMxODM4MDUiDLM1aCtduqj2jmdGuSrcA6yVhUiFLOnJ3jGknVHs%2FRxfRuI6mIViuMYE8eHgt2%2FraoHc8uYGgkjjxTZ9iP5FQ0DpI%2F0p0hFdRBPO6aYLauzYiSvbpk1tAX1z7JB6AwHwx7RswHpkIa%2BL4scvSSv4Vdv0eNGR45qQjO33kR4gwjxSQDDLNW5sia0b3kN%2BOrNjUilgqFhCFhgB1NR8LJKIzKe91OF%2FOixH8Oa76YR%2Bij5wtx%2FN7W49U%2F%2FDl%2BbOIM79IaQ7ALth8psUwJOPO6nac4AeFFCOfxgwemhEsx4isX2ZiMyPlT%2FJa%2BxGKK9E1CJ6dYvZgdMUeHxrhEeafa0wBRTYX%2FNib9Db3MDDTy4UeKE9wivThIYLnZAEpMJWElbu7IWNtpqx14x0JDysoXOhWKafgpIp7QGHV2LwRd51hqtgCvJHQ0EZk9rsqZd6wr69N%2F9woSVg22SVNuxac8SiPtApp4jskUl1tzdJ8EGeqPUGh7kjnB%2FIMyHEpz2t%2B4YASQJSJAG%2F90ntpAlTYVZ4MITON5O1udEMg4avYeHqclQJMQpAckgCua8OMb00m84MIljfjJ4Whw0iEYFX71P3S8Kuyagze0ly1SJetoS0kuVXDFckwH8Ym6Oq%2BGVL4H7XWgiqbqp29dv6MT%2FpMJrCzb0GOqUB3R384W0%2FgnnzUas3pajEZn2VYCW4i48KO5F64zwbutca1bs99XN2PUmOZjFo7P48dYrj8gRBMko6qhKFbRlMEk5l8wH2zWCuPauW0%2FKCnnXAusqrGUrla%2FG8OMPi1PgcPRSdq0KvQG20VAqwZTdZjdeZu9qtaA7tvn4m8Y9ozNl09ix9dkEIxjfRG7JS8SxvZTMC79aaQLZvLiUfqIvaVO6TICz0&X-Amz-Signature=41ed0ea6d888e3aab6431486aaa8a74b1f3815ed673ab42f4d2fd167a57f258a&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QUIWBZVN%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T172103Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFAaCXVzLXdlc3QtMiJIMEYCIQCmpwkFXe5PImy8H9vkuF%2BRFsbkNQ796%2Fwt6U3pmsDMcAIhAJAX%2FJ0QX6HsVIl8sr8lA%2BKkUCDLw9%2FkPWhRpen24HNvKv8DCHkQABoMNjM3NDIzMTgzODA1IgyHEWtdrtmFxmfMz4Yq3AONIuUSbRZJqDex1j2GIhx8ZIPmKRQcumcWcXXBGHM2mZjRgU6xkmNql0QQwosdAIq%2BXZtQ1f0s7QKuLBEvVNKioXO4UGdrO4iXbx3EtrX3r1G06xItFDi46smLJNaJ2Xgu%2FuDZDQ7kxF6kJQSdvfLyG06XFXwLiLi2ham0ZuSfuE8HB2BlZ7fVXFSoJiUY5A%2F1BteWnlc5l30Pps8ltm8D7BK4cyEhcoo6T7SzWUZL6%2BT9RFscn4C5xaI7U71xSbV%2BBiFovgwNSZ6Q8UqM2TGB3RzRDrCptn%2FGVwU%2B2qJ9qvGMqSqLuBh2V%2B%2FJMxOCKJs6xmaij30cygPoC21USqsNAlc8RWazui%2FaXqfIaWCxnkFdBZqzcy5MS3PliGZN7DwyOK4rFv9rdd8CryMQnGqlGLTjTFHMGQnPOCLYtjrYadJyCLBPXZmbd6MGvWtH0E8%2FBHbj7Hwj35x%2Fafb9WvMoH%2BHViO1G%2FMObdFguTv6x6H4VgY67LlRtsXr49Q7wn6dsP9ilJf7Rj3G4lk88UFo2UaX%2FTkpWvf5mcFTxni8EMgWTdbyaB42QMFq3tjsblu11Ro1f1B81w3nn1fr64dPoJTpOiQI0UUJQatFZA%2Bog9E%2B%2FN0b1GKOH1oUuRjCXws29BjqkAalUO%2BZbWXvtrkr1JvDdALPbmmabd4vxZGsRr8LmDHJRvg9OYfOkFdrOqFV1vfaf2Oh9cAKbFlcDmkCy9vu7dEHtiY%2BU8TD%2FVU51jSZxrlfELMQIn4jyAxaG%2Fhr4OB1PuEgHKolTYlSF80SY2QNvG9WcHytIVCBHwPiswnSFiGh4NwbJDr63dqtHXKrWApwyLDyKPW7Yhp0rYnqWj3Py9ck8K92y&X-Amz-Signature=13f070100c0fc3b7ca5c5bd79a781f4a4e9becb3da024e9d520ad276311a0cdf&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VGCKNANO%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T172104Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFEaCXVzLXdlc3QtMiJHMEUCIQDtABa30aXrkN64v6mXdE6SNievKaI04zCmgiGM11Q%2BjwIgQw2L9M1%2Fp7egiSxMo20LDHmNDRnzAeIrUUMhCdc2llAq%2FwMIeRAAGgw2Mzc0MjMxODM4MDUiDNelJB1uwwifvJ6sLircA31Pwe55aFrYxsRhgQjlMFVDpJjT1uNEs1JDPJssGexJOw%2BRyXMxIglG5u4cN0gd5b2woUl1sy6%2FWeEQh3ZYobbm%2BLGqMin5gERm2Tq6dxlv8BRP5%2Bjx5SAr8ideuUI2S%2FD39k8Hhcyuc105aucRUpycfw1Gvj4l6u7FAs3geTgVpzB48uCwx1rzKGptmZ0S1kZjYDT1xhoj2hM9Js1Ngki9VbPgTte1GrFbMzNwdBrI6Mr6A%2BTH7sSxUe3LlzJIxdR%2Bqvt87NjWZ0seCnvbHXMJj23viGJ%2BhASn%2Fkul%2BiDjda%2BQ59fDp20tou3yA6gZvnGi0kymEwMQxPmV7srBTdhaHd6oVBvQ%2FVhXXiazc2JTECD1vc1SWVPtUHZE7JBYn1RBvnHGCrGg5tKLxtEUBvilYNilCQw2P%2BgG%2FEKhOD3WAbrkSRspyWl%2F87BI1wgzZAsXONsvQUAlNhffjSzufIklKhp%2Bms94sgrZVcTJvYjbpSdKRFmA%2BkHq%2BW4It51cgR%2FiG32GM973uhtRht151lniabTi9tQ9Qj05ag%2FKl4KBUgoz7QAJ%2BN9LPlwG945RdEaOlgZxOTx%2FDuq6MoTXgoOf0Ek%2BFVwtYfD3NW6gDxmkGmFezMw4led8R5aeMKXDzb0GOqUBTpKQ%2F8nTlPwmmW3US65Pl0t4GfaA7hwhQdORR4BlsZDbeJD%2BOAimrr25KmbtWZCZSvG8V1Bpehjvxf194d7865SZIPbDWRaJ%2FG2WlSydYZBx8xqiLA2wrg73NiJSy%2FAqNLw90S6McPRRxles%2FpZ0kCbvwLg%2F%2BJdBoFRdiPNHAAX6zS6xkwUYgr6K6SpPJwB96ptj8j1BFlCFkdKfcIjwNXZu8gRh&X-Amz-Signature=de80bbcd42bb4f956e552d7fa7488ee8c79e3f69ccc58682d327b022f24ea7d0&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YCWOZ5U5%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T172103Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFAaCXVzLXdlc3QtMiJHMEUCIQDP2sMGnBK5cEKCDtQOElgMdgH6R1KnQSuOmEbGI9zmqwIgPEM%2BfYtVUhTt23COgfymJRDaf7Qvj01FPVv5co%2BYX88q%2FwMIeRAAGgw2Mzc0MjMxODM4MDUiDLM1aCtduqj2jmdGuSrcA6yVhUiFLOnJ3jGknVHs%2FRxfRuI6mIViuMYE8eHgt2%2FraoHc8uYGgkjjxTZ9iP5FQ0DpI%2F0p0hFdRBPO6aYLauzYiSvbpk1tAX1z7JB6AwHwx7RswHpkIa%2BL4scvSSv4Vdv0eNGR45qQjO33kR4gwjxSQDDLNW5sia0b3kN%2BOrNjUilgqFhCFhgB1NR8LJKIzKe91OF%2FOixH8Oa76YR%2Bij5wtx%2FN7W49U%2F%2FDl%2BbOIM79IaQ7ALth8psUwJOPO6nac4AeFFCOfxgwemhEsx4isX2ZiMyPlT%2FJa%2BxGKK9E1CJ6dYvZgdMUeHxrhEeafa0wBRTYX%2FNib9Db3MDDTy4UeKE9wivThIYLnZAEpMJWElbu7IWNtpqx14x0JDysoXOhWKafgpIp7QGHV2LwRd51hqtgCvJHQ0EZk9rsqZd6wr69N%2F9woSVg22SVNuxac8SiPtApp4jskUl1tzdJ8EGeqPUGh7kjnB%2FIMyHEpz2t%2B4YASQJSJAG%2F90ntpAlTYVZ4MITON5O1udEMg4avYeHqclQJMQpAckgCua8OMb00m84MIljfjJ4Whw0iEYFX71P3S8Kuyagze0ly1SJetoS0kuVXDFckwH8Ym6Oq%2BGVL4H7XWgiqbqp29dv6MT%2FpMJrCzb0GOqUB3R384W0%2FgnnzUas3pajEZn2VYCW4i48KO5F64zwbutca1bs99XN2PUmOZjFo7P48dYrj8gRBMko6qhKFbRlMEk5l8wH2zWCuPauW0%2FKCnnXAusqrGUrla%2FG8OMPi1PgcPRSdq0KvQG20VAqwZTdZjdeZu9qtaA7tvn4m8Y9ozNl09ix9dkEIxjfRG7JS8SxvZTMC79aaQLZvLiUfqIvaVO6TICz0&X-Amz-Signature=5b2acc5e6ff941f17ba0c19dbb46fffe709d133b633198e0d5a0eea026f8c2b9&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YCWOZ5U5%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T172103Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFAaCXVzLXdlc3QtMiJHMEUCIQDP2sMGnBK5cEKCDtQOElgMdgH6R1KnQSuOmEbGI9zmqwIgPEM%2BfYtVUhTt23COgfymJRDaf7Qvj01FPVv5co%2BYX88q%2FwMIeRAAGgw2Mzc0MjMxODM4MDUiDLM1aCtduqj2jmdGuSrcA6yVhUiFLOnJ3jGknVHs%2FRxfRuI6mIViuMYE8eHgt2%2FraoHc8uYGgkjjxTZ9iP5FQ0DpI%2F0p0hFdRBPO6aYLauzYiSvbpk1tAX1z7JB6AwHwx7RswHpkIa%2BL4scvSSv4Vdv0eNGR45qQjO33kR4gwjxSQDDLNW5sia0b3kN%2BOrNjUilgqFhCFhgB1NR8LJKIzKe91OF%2FOixH8Oa76YR%2Bij5wtx%2FN7W49U%2F%2FDl%2BbOIM79IaQ7ALth8psUwJOPO6nac4AeFFCOfxgwemhEsx4isX2ZiMyPlT%2FJa%2BxGKK9E1CJ6dYvZgdMUeHxrhEeafa0wBRTYX%2FNib9Db3MDDTy4UeKE9wivThIYLnZAEpMJWElbu7IWNtpqx14x0JDysoXOhWKafgpIp7QGHV2LwRd51hqtgCvJHQ0EZk9rsqZd6wr69N%2F9woSVg22SVNuxac8SiPtApp4jskUl1tzdJ8EGeqPUGh7kjnB%2FIMyHEpz2t%2B4YASQJSJAG%2F90ntpAlTYVZ4MITON5O1udEMg4avYeHqclQJMQpAckgCua8OMb00m84MIljfjJ4Whw0iEYFX71P3S8Kuyagze0ly1SJetoS0kuVXDFckwH8Ym6Oq%2BGVL4H7XWgiqbqp29dv6MT%2FpMJrCzb0GOqUB3R384W0%2FgnnzUas3pajEZn2VYCW4i48KO5F64zwbutca1bs99XN2PUmOZjFo7P48dYrj8gRBMko6qhKFbRlMEk5l8wH2zWCuPauW0%2FKCnnXAusqrGUrla%2FG8OMPi1PgcPRSdq0KvQG20VAqwZTdZjdeZu9qtaA7tvn4m8Y9ozNl09ix9dkEIxjfRG7JS8SxvZTMC79aaQLZvLiUfqIvaVO6TICz0&X-Amz-Signature=17bbdd4bd9c46152229460496fb2673a28f0eec06accccd62cd1da963104e9d6&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YCWOZ5U5%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T172103Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFAaCXVzLXdlc3QtMiJHMEUCIQDP2sMGnBK5cEKCDtQOElgMdgH6R1KnQSuOmEbGI9zmqwIgPEM%2BfYtVUhTt23COgfymJRDaf7Qvj01FPVv5co%2BYX88q%2FwMIeRAAGgw2Mzc0MjMxODM4MDUiDLM1aCtduqj2jmdGuSrcA6yVhUiFLOnJ3jGknVHs%2FRxfRuI6mIViuMYE8eHgt2%2FraoHc8uYGgkjjxTZ9iP5FQ0DpI%2F0p0hFdRBPO6aYLauzYiSvbpk1tAX1z7JB6AwHwx7RswHpkIa%2BL4scvSSv4Vdv0eNGR45qQjO33kR4gwjxSQDDLNW5sia0b3kN%2BOrNjUilgqFhCFhgB1NR8LJKIzKe91OF%2FOixH8Oa76YR%2Bij5wtx%2FN7W49U%2F%2FDl%2BbOIM79IaQ7ALth8psUwJOPO6nac4AeFFCOfxgwemhEsx4isX2ZiMyPlT%2FJa%2BxGKK9E1CJ6dYvZgdMUeHxrhEeafa0wBRTYX%2FNib9Db3MDDTy4UeKE9wivThIYLnZAEpMJWElbu7IWNtpqx14x0JDysoXOhWKafgpIp7QGHV2LwRd51hqtgCvJHQ0EZk9rsqZd6wr69N%2F9woSVg22SVNuxac8SiPtApp4jskUl1tzdJ8EGeqPUGh7kjnB%2FIMyHEpz2t%2B4YASQJSJAG%2F90ntpAlTYVZ4MITON5O1udEMg4avYeHqclQJMQpAckgCua8OMb00m84MIljfjJ4Whw0iEYFX71P3S8Kuyagze0ly1SJetoS0kuVXDFckwH8Ym6Oq%2BGVL4H7XWgiqbqp29dv6MT%2FpMJrCzb0GOqUB3R384W0%2FgnnzUas3pajEZn2VYCW4i48KO5F64zwbutca1bs99XN2PUmOZjFo7P48dYrj8gRBMko6qhKFbRlMEk5l8wH2zWCuPauW0%2FKCnnXAusqrGUrla%2FG8OMPi1PgcPRSdq0KvQG20VAqwZTdZjdeZu9qtaA7tvn4m8Y9ozNl09ix9dkEIxjfRG7JS8SxvZTMC79aaQLZvLiUfqIvaVO6TICz0&X-Amz-Signature=2dc18e3de2d2cb6d772fae93925e08e79c489010e87052d1d2fe430a957f54f4&X-Amz-SignedHeaders=host&x-id=GetObject)


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

