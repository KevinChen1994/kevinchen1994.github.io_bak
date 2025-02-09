---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466WU2VRSCD%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250209T152400Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEI%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICRk2t2OwUK0Eu6rx\
  %2BMUyAVlylDUlyVRCkohF%2FBKM3G5AiAJdtCi7ZssJAav7wqKVSPqvVJ3SCV4HaBF0JpXlirdKS\
  qIBAio%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMHUyOPSAv5fcrdJL\
  OKtwD9Cx4Fi9v%2BwlUYgL5O4Z4TJc1pBFZowfCnIwqHqvx4P7I5p1KdaD6%2F%2BeYfTdzfO3Rny\
  a5MpuMRON8nM7fOUCZwLV8O7RR%2BbRfX9HLd%2FYu3%2BzrsKFUYIa87K0sJniNWnV2GMRBCE3xX\
  SRRuc3yEOh%2BBGMF8762aeuUtDpiDmtkoH6k3UV3XBx64oqODuMaIOY5y%2FPEh%2FTUwEBMgNW1\
  T94SUep3F%2Fe323VnXIJ9yL0Vrlg04asyE5l91osn1uEjT8uVTl7Rc8f1dNxSZvR7E2JNsFPRqmc\
  Cf3j8KzVxdvaULhAy7AwDQpNjVjyLBAPCXI5SLFuUSvyBNdKtq0Mf8fV0MYqfpgDtUju3OTK4%2B7\
  nuO45FS%2B%2BFjxviHF9VKPUKRc%2FV%2FzWKzbd7aBFVW5eaPHU9DO18UEeE9vXKSvaLoIL4QCn\
  8D3Zffk0yH3RsRXGFLqj3hzPtKFZIHOH8188uj9HCOlnlFApMQT31mShpm8tJ0tYlp4D9%2B1pE2H\
  CCdesdspaOmPjRsH16qVWxkBSeGuR8run23oh8YbOtXLl38dIy1zivpTM%2FFrffN9zDwt%2FxxnA\
  kt4mj6cKA1d7qxS9tAbHMd1HghuT3OAy596NoSVkn05O1Ko8TF64HO5biMbow8YijvQY6pgFuV5hv\
  HGs%2F7MLEr0z8CyYQ4EqE67ZKYXS5lpcu1vnpRq%2FkYpftCCQ3fK5EMKtYL2OaF58FczhFsAHKP\
  Z1QWMcbMaGavnF3sAu1wfzQxcd8kkMJn4uhd%2FQ05Qc5DmqySG1rnrZqYaXr0jqnX98sYt5eSigG\
  N7md4IKGz3G1BJYF%2FF2nhNadlmW1CThvp3X9AQsg1PJtkaBB4qCOeoJvIs9%2F%2BcSG4UK4&X-\
  Amz-Signature=82a20038c27afae89f3c119d5f11d585e4222e7a8466445f55bbd8cbdc4c656\
  4&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4662BBD3BSY%2F20250209%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250209T152234Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEI%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHM\
        EUCIQCrU7R7lpE0eQ0GYdMK33mFT77Sr1oEDp4WI9rovG7h0AIgYvgoYZQIKxS0TBK%2Bhl\
        Fm0ksoRfHV2%2Fdqsd%2FRIkD0P3EqiAQIqP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAG\
        gw2Mzc0MjMxODM4MDUiDHH82WUc8lSdF92oEyrcA3lYq6%2FOMozFoypnCg6JJ1MHnrGOed\
        z745e1OCyMTegqcpILIZANaUEa3GW4rRSgaJXN0hTatrlI4Fo7s1F3wu9BR3QtwmSo%2F43\
        YRtmosGsOdrbi06Iwb7gYFb9qx8AebEig6dfvNe0tGhjtvS3GNTL%2BvCg4l%2BDMTaaJiK\
        yLADMVs55WY8WxKio1p1AW81y6qtJ6ccmma87oY6CFYvzIkLyaHjR3WczEj8S7VoEOQVQ6s\
        lI05wMvaxvw5a7Sk51%2Ff65Jv9MVortxhBCm1zIUHRSmNg8cfRuyVngczQ9bXdF52iW45H\
        lRARoxTRt%2F5G8pVw44RbbjUblUKR0TmpnWXcpE%2Fp%2FFqUvzMzrsuKxgFE9u9mpcSXs\
        Q7FQ8RXWPkDY6QtBVILxy4rTLqrQxd4EKb0Mgb5mR1AV6UcLdaPjD6b%2BJHbX%2FNRz49k\
        EwVQD41IK1sw2MxtxC%2BPvJMKD87Odx%2BRDhVafLkgzFAbP%2F6pYaD9nXgda6IW6DoSU\
        FtYXQhAF%2B1yrVPlDYee24EqS44cXsXAQRFuf9fe7cg9gxGE5Um4jI%2Biuq9mv6dy1gai\
        dnWBm8Jz8%2FQIDsFUuHG8UUwWIH%2B4%2FelJoJCI8IF3CmMsV0%2Bo4q4zgGwGo%2By0S\
        Fxli2MJKBo70GOqUBCHWo5sbtcRmDUBB3MVrID5msBAn8H2mTrqE%2BnjsVimuRHSp6nMre\
        WmlaGM71B6zFQQcIbhNbN%2BZZQCnJ1zZAOyMaGMEA3UYspspVl5dQYWwiJOjaVc%2B6s2X\
        eVzoqzQMvD9cy3nrzY54sWJ6TKG80aKxYiKsJ024abMTSLKLHGYHIV0nX7c1JxFvTExaiBN\
        rnDQ0%2FHeoFM2j7eRyPUMwalROAcqRJ&X-Amz-Signature=2df7539336cbd4916f1b4d\
        e47874bca7a85a057e25c004d26f0a6d126ceee4bb&X-Amz-SignedHeaders=host&x-i\
        d=GetObject"
      expiry_time: "2025-02-09T16:22:34.535Z"
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
UPDATE_TIME: "2025-02-09T15:24:05.028Z"
EXPIRY_TIME: "2025-02-09T16:23:57.748Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RV2TUAKB%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T152358Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEI%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDolugcMR%2BeKtXd7WYe5pZi%2BcvqVNqTXQ83rrQ9fy%2BP%2BQIgBZQ5pF7uLk82c0BeJFwOb%2FZleGiWGD1eNM0ebJ9PVdkqiAQIqP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMAlZB7P9jibwlEWDyrcA2NY%2B0zblKYcr%2Fj9KeQv21Lzbm6OoN%2FBpiCDyICIT4DOtGNDufTr%2BA0qEbZDpZQCJnlloyXyhgSlzJtYilF9O3vJRdod69PLyAF6YiOj4J2w5YKNZ%2FPeorb0Im%2FW1%2BDXNUif3C3uS7O0D%2FEXIyHU8qsqXH4zuMLCTyo%2BJi%2FoiYz6wE4iEqiPMfkthqSQGt62ykgof5KlTdqsSuL%2BiKkg5mASNLcVTVOKlVjK1B0wiVM1wx4UlEu%2BCa5Q2zG8yGMQBVLuX7qx8qj3eGXe9uvKx%2Bj8HpOWBaSuzp25m6MFK4%2BCHX12BWXpZzBvcbYfwzEukXSbnnEdYwjG1USMfX2BsNHUvPYZ9V7BkKZfeOn4dRqVv0bYPqSw%2FfWwxBET55CgQeI6dGgJ2SSq2ylNSbuLq5EY9LN1f3WLtL2xCFuyE7mcr%2FoHVpcoWoGLtaPjFoq30dGgNBNYYyyMUkbE9SgGLhl4ipENr81rALS3p%2BX8%2B4hHx6opvZqwErD5k23hulLn2oDt7ifF83MLvIUXDjPW8K9pxiLcl68lXLofq4PvKffWkbrLo2kUUFbtq%2BaU2iCp5U9JS21zNAoni9Gbqlau8xgiSKs%2B0tbGJHjx9Q0rb6SdPa6mSaXg3WeSRP%2B%2FMJmIo70GOqUBVInj6v9IN8HetUaCkECnv7CYVedauLqoPiRh7vz6zyTCrcfY0TcxAHS0U496I5tp1RHbIwM%2FL9t2UfQq3Oexj4T%2FF%2B%2BwSeEZZhOE2nT9pKEwV%2Bn%2Fd0%2Fy%2BzdIncyYJayyecKFkVAd9o7EWlnoGIkpZZACQW8Uhr5AUGi3YVYqswOnUA4Ly%2FHKIFD2QE00C0Y6d5FXeLB93QB4%2F%2Fb%2BcaD%2F%2FIowV5lU&X-Amz-Signature=d83457da152a59218f77cd0705c9fad43e589b5db5c3f69dc87992ea6c506241&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RV2TUAKB%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T152358Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEI%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDolugcMR%2BeKtXd7WYe5pZi%2BcvqVNqTXQ83rrQ9fy%2BP%2BQIgBZQ5pF7uLk82c0BeJFwOb%2FZleGiWGD1eNM0ebJ9PVdkqiAQIqP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMAlZB7P9jibwlEWDyrcA2NY%2B0zblKYcr%2Fj9KeQv21Lzbm6OoN%2FBpiCDyICIT4DOtGNDufTr%2BA0qEbZDpZQCJnlloyXyhgSlzJtYilF9O3vJRdod69PLyAF6YiOj4J2w5YKNZ%2FPeorb0Im%2FW1%2BDXNUif3C3uS7O0D%2FEXIyHU8qsqXH4zuMLCTyo%2BJi%2FoiYz6wE4iEqiPMfkthqSQGt62ykgof5KlTdqsSuL%2BiKkg5mASNLcVTVOKlVjK1B0wiVM1wx4UlEu%2BCa5Q2zG8yGMQBVLuX7qx8qj3eGXe9uvKx%2Bj8HpOWBaSuzp25m6MFK4%2BCHX12BWXpZzBvcbYfwzEukXSbnnEdYwjG1USMfX2BsNHUvPYZ9V7BkKZfeOn4dRqVv0bYPqSw%2FfWwxBET55CgQeI6dGgJ2SSq2ylNSbuLq5EY9LN1f3WLtL2xCFuyE7mcr%2FoHVpcoWoGLtaPjFoq30dGgNBNYYyyMUkbE9SgGLhl4ipENr81rALS3p%2BX8%2B4hHx6opvZqwErD5k23hulLn2oDt7ifF83MLvIUXDjPW8K9pxiLcl68lXLofq4PvKffWkbrLo2kUUFbtq%2BaU2iCp5U9JS21zNAoni9Gbqlau8xgiSKs%2B0tbGJHjx9Q0rb6SdPa6mSaXg3WeSRP%2B%2FMJmIo70GOqUBVInj6v9IN8HetUaCkECnv7CYVedauLqoPiRh7vz6zyTCrcfY0TcxAHS0U496I5tp1RHbIwM%2FL9t2UfQq3Oexj4T%2FF%2B%2BwSeEZZhOE2nT9pKEwV%2Bn%2Fd0%2Fy%2BzdIncyYJayyecKFkVAd9o7EWlnoGIkpZZACQW8Uhr5AUGi3YVYqswOnUA4Ly%2FHKIFD2QE00C0Y6d5FXeLB93QB4%2F%2Fb%2BcaD%2F%2FIowV5lU&X-Amz-Signature=9f24895e4f6019a184f2951c6415bd276a5f3110e3dee54f29176c1b461cfa98&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RV2TUAKB%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T152358Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEI%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDolugcMR%2BeKtXd7WYe5pZi%2BcvqVNqTXQ83rrQ9fy%2BP%2BQIgBZQ5pF7uLk82c0BeJFwOb%2FZleGiWGD1eNM0ebJ9PVdkqiAQIqP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMAlZB7P9jibwlEWDyrcA2NY%2B0zblKYcr%2Fj9KeQv21Lzbm6OoN%2FBpiCDyICIT4DOtGNDufTr%2BA0qEbZDpZQCJnlloyXyhgSlzJtYilF9O3vJRdod69PLyAF6YiOj4J2w5YKNZ%2FPeorb0Im%2FW1%2BDXNUif3C3uS7O0D%2FEXIyHU8qsqXH4zuMLCTyo%2BJi%2FoiYz6wE4iEqiPMfkthqSQGt62ykgof5KlTdqsSuL%2BiKkg5mASNLcVTVOKlVjK1B0wiVM1wx4UlEu%2BCa5Q2zG8yGMQBVLuX7qx8qj3eGXe9uvKx%2Bj8HpOWBaSuzp25m6MFK4%2BCHX12BWXpZzBvcbYfwzEukXSbnnEdYwjG1USMfX2BsNHUvPYZ9V7BkKZfeOn4dRqVv0bYPqSw%2FfWwxBET55CgQeI6dGgJ2SSq2ylNSbuLq5EY9LN1f3WLtL2xCFuyE7mcr%2FoHVpcoWoGLtaPjFoq30dGgNBNYYyyMUkbE9SgGLhl4ipENr81rALS3p%2BX8%2B4hHx6opvZqwErD5k23hulLn2oDt7ifF83MLvIUXDjPW8K9pxiLcl68lXLofq4PvKffWkbrLo2kUUFbtq%2BaU2iCp5U9JS21zNAoni9Gbqlau8xgiSKs%2B0tbGJHjx9Q0rb6SdPa6mSaXg3WeSRP%2B%2FMJmIo70GOqUBVInj6v9IN8HetUaCkECnv7CYVedauLqoPiRh7vz6zyTCrcfY0TcxAHS0U496I5tp1RHbIwM%2FL9t2UfQq3Oexj4T%2FF%2B%2BwSeEZZhOE2nT9pKEwV%2Bn%2Fd0%2Fy%2BzdIncyYJayyecKFkVAd9o7EWlnoGIkpZZACQW8Uhr5AUGi3YVYqswOnUA4Ly%2FHKIFD2QE00C0Y6d5FXeLB93QB4%2F%2Fb%2BcaD%2F%2FIowV5lU&X-Amz-Signature=347cdeeee7c257384b747f76b3a1bc06cebde13f0a6e6b8401b3e770a5127d9c&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RV2TUAKB%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T152358Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEI%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDolugcMR%2BeKtXd7WYe5pZi%2BcvqVNqTXQ83rrQ9fy%2BP%2BQIgBZQ5pF7uLk82c0BeJFwOb%2FZleGiWGD1eNM0ebJ9PVdkqiAQIqP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMAlZB7P9jibwlEWDyrcA2NY%2B0zblKYcr%2Fj9KeQv21Lzbm6OoN%2FBpiCDyICIT4DOtGNDufTr%2BA0qEbZDpZQCJnlloyXyhgSlzJtYilF9O3vJRdod69PLyAF6YiOj4J2w5YKNZ%2FPeorb0Im%2FW1%2BDXNUif3C3uS7O0D%2FEXIyHU8qsqXH4zuMLCTyo%2BJi%2FoiYz6wE4iEqiPMfkthqSQGt62ykgof5KlTdqsSuL%2BiKkg5mASNLcVTVOKlVjK1B0wiVM1wx4UlEu%2BCa5Q2zG8yGMQBVLuX7qx8qj3eGXe9uvKx%2Bj8HpOWBaSuzp25m6MFK4%2BCHX12BWXpZzBvcbYfwzEukXSbnnEdYwjG1USMfX2BsNHUvPYZ9V7BkKZfeOn4dRqVv0bYPqSw%2FfWwxBET55CgQeI6dGgJ2SSq2ylNSbuLq5EY9LN1f3WLtL2xCFuyE7mcr%2FoHVpcoWoGLtaPjFoq30dGgNBNYYyyMUkbE9SgGLhl4ipENr81rALS3p%2BX8%2B4hHx6opvZqwErD5k23hulLn2oDt7ifF83MLvIUXDjPW8K9pxiLcl68lXLofq4PvKffWkbrLo2kUUFbtq%2BaU2iCp5U9JS21zNAoni9Gbqlau8xgiSKs%2B0tbGJHjx9Q0rb6SdPa6mSaXg3WeSRP%2B%2FMJmIo70GOqUBVInj6v9IN8HetUaCkECnv7CYVedauLqoPiRh7vz6zyTCrcfY0TcxAHS0U496I5tp1RHbIwM%2FL9t2UfQq3Oexj4T%2FF%2B%2BwSeEZZhOE2nT9pKEwV%2Bn%2Fd0%2Fy%2BzdIncyYJayyecKFkVAd9o7EWlnoGIkpZZACQW8Uhr5AUGi3YVYqswOnUA4Ly%2FHKIFD2QE00C0Y6d5FXeLB93QB4%2F%2Fb%2BcaD%2F%2FIowV5lU&X-Amz-Signature=c6bc1c14cd1f2147bbd276e2e4e69f28e3050032fc9fd249d7dd24259915dec7&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RV2TUAKB%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T152358Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEI%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDolugcMR%2BeKtXd7WYe5pZi%2BcvqVNqTXQ83rrQ9fy%2BP%2BQIgBZQ5pF7uLk82c0BeJFwOb%2FZleGiWGD1eNM0ebJ9PVdkqiAQIqP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMAlZB7P9jibwlEWDyrcA2NY%2B0zblKYcr%2Fj9KeQv21Lzbm6OoN%2FBpiCDyICIT4DOtGNDufTr%2BA0qEbZDpZQCJnlloyXyhgSlzJtYilF9O3vJRdod69PLyAF6YiOj4J2w5YKNZ%2FPeorb0Im%2FW1%2BDXNUif3C3uS7O0D%2FEXIyHU8qsqXH4zuMLCTyo%2BJi%2FoiYz6wE4iEqiPMfkthqSQGt62ykgof5KlTdqsSuL%2BiKkg5mASNLcVTVOKlVjK1B0wiVM1wx4UlEu%2BCa5Q2zG8yGMQBVLuX7qx8qj3eGXe9uvKx%2Bj8HpOWBaSuzp25m6MFK4%2BCHX12BWXpZzBvcbYfwzEukXSbnnEdYwjG1USMfX2BsNHUvPYZ9V7BkKZfeOn4dRqVv0bYPqSw%2FfWwxBET55CgQeI6dGgJ2SSq2ylNSbuLq5EY9LN1f3WLtL2xCFuyE7mcr%2FoHVpcoWoGLtaPjFoq30dGgNBNYYyyMUkbE9SgGLhl4ipENr81rALS3p%2BX8%2B4hHx6opvZqwErD5k23hulLn2oDt7ifF83MLvIUXDjPW8K9pxiLcl68lXLofq4PvKffWkbrLo2kUUFbtq%2BaU2iCp5U9JS21zNAoni9Gbqlau8xgiSKs%2B0tbGJHjx9Q0rb6SdPa6mSaXg3WeSRP%2B%2FMJmIo70GOqUBVInj6v9IN8HetUaCkECnv7CYVedauLqoPiRh7vz6zyTCrcfY0TcxAHS0U496I5tp1RHbIwM%2FL9t2UfQq3Oexj4T%2FF%2B%2BwSeEZZhOE2nT9pKEwV%2Bn%2Fd0%2Fy%2BzdIncyYJayyecKFkVAd9o7EWlnoGIkpZZACQW8Uhr5AUGi3YVYqswOnUA4Ly%2FHKIFD2QE00C0Y6d5FXeLB93QB4%2F%2Fb%2BcaD%2F%2FIowV5lU&X-Amz-Signature=556e6ddcce86aa9b364459d4cdb0728dac9c39e2d04f0ee2597692585250ba7a&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666ZAOMOJU%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T152359Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEI%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCDV4qJeH7o6LKxQ1qDvZJdAEjRKh3KF43TBXdYxgmsgwIhAOgsA8o%2F%2B1hoWKzmFrzAlXEnSNDNHxKkqbiESFOQXmDtKogECKj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzGiHPcefC3Cy90nM8q3AOC3rs9uye8aVK3Uk0BOB4kCh0vWUNNYx6szxnqwF0yKKDp5zcEUCWQRR3oVUOeuDu5%2FetMeQTZ1wzYo9bF8gbfpy4kPkknmHOpXyeoTMdNWSWZWdcBNXPj6ytLuIztCZ2XGiDoUG7gU26Y7GijnQg5BWDgKn5K5KLo1RxtezF85edDDl6OGOZ6Azu%2FEMIfqVVYpz78RYPiN5TGeSghLgKPZJxI2wnnCLnRvBOxA2bsNn0JDztQHlqaOmgP0SZaYDeFV139bYcqQJIj5KfcFVKgynq%2FsO3NMN4A%2FctL6U8RO7JmPPIsRw0JVq461Q3pGxCQkVeKFhcADfww65nrgBX19xhucNrgaNTIoRZj63Uf%2FsCjJAYnYjLs%2B9VMd%2F1OLdUJ0T2G0%2FIbB%2BBzWlXMS6DtI9QTcca2EuLo%2Fk0Z6hZLA9xnWKHFlx8c0CHGNUXvhl7WuuJUvPVRtBch4zdXjHvxQNbov4IRY%2Fw5ZDnogz%2FBIcQ22yQ8EOy3SXxMqb0ncYAvXda8e1V4EnXuUGDH%2BCupv7BednASXXjf%2B693iGMZg8XCMScb27bAO2CFvs%2Bl%2BeaJzY9HIFOUXzXCjHav0bFcmHnP5WsOwwxWhDlawoTdQej%2BW3N003j6DcFMnDDihKO9BjqkAUZinrsC3WlPqau2Ap5v16MVtwPk1%2BLgKWjjXXij6TYxAkMyEBfHNLjZj1RoQplsK%2BM6FNF3enAL40UYvwoCja4WwV3jitiW2jFvKkmodWrYFhcH8CcfmMERWegMUBzommGF5Ue9XCrIrBT4W2YAxg%2BQeUYDaWqLNpJ30xs7WRj39DWb%2FmlH1VfLbqDlhnCOmYySsb0Ojqw2vsHYj9tfiiV3xI7W&X-Amz-Signature=24769a6d50c6ec8b6ef536d5d03614a70720092146596b27c41796b03fbd120a&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z4RHD6GA%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T152359Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEI%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC%2BEFAowq7IRpibVA%2FLfZDHNSrJ%2BJ6BMLXBOzZbklmM6AIhAJBx%2BiraSKq%2BNczpqBIP8%2BFBf%2Fe76hZVqSGisTpeaKboKogECKj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwKSiz1yr4qEG2AhDcq3AO8FNiFTSYa1caX2Ytpt0W192XJYQnjvsxZ2fQIGNb7DU1qzO6fZPfNXGXNrDNO2bTJY3nrwjlWLqDhrNa24KR%2FXyvwwF3O4vc0vayPHVy9KAmxxoKTFUt%2F4kuGfZH7r3scIGNYCHswukhdd7gUO2xT4quhxOX%2FC9piPz0288QNWkKqbet%2BCuEi5c5QlI0mcbHoTmajoA2fXYcdK7KA6IkHKFsH78hunxQFyWDpG%2F%2FfuDetDHewqkkqjpn2yScNtGB1%2F0kFvJokc9MVFFETqf0uFnSr2DE6ISoXMNyiQtVJcBnDYtUCO3l5HUbIs3mfNNiiW6LQfOyqxnghMupHF94DQhoSxJFhc7M6lxWZX7c9M6a127Nm8tibU0kdtbCHaEDNVX6QqOmOF7SrB7vAkZfenIf%2FeC96C5%2BWzfjzh9Pyee8kV9bSGO3TRMEtSDAKfDipnvXg07%2BNoWAuJcZQF1UWsJXrfF2QpoEcZPFFDhmacaaPwJK64Gz53%2BenA%2BT2QWfqskO7cforF%2B3y7snkdqdBMytVqe5BToXY15%2BDTrTwjGjiWWHPURqyclTzAzzTHuZQnKu8PRdX7wq7L3mYeWYY8THLFesu3rM6gou0TdWQ6i%2FF%2F%2BKDYkQ9yW%2BZBTDLhqO9BjqkAdEWKCZmNBevIZ%2FCAmOWS0jdEssc6ss4MyxH%2FDNx09kd4n6mXa4ZWB6I4LqVvQAsEpbmWmMk9opv9%2Bar7c26hXMxY87Gw%2BwgNvf%2BOJWVjuWJCSj428geq6Iu9Gj5G1ZoRA35UTLeAvbEZ6KR8DrTHRImouHmo6ufW3YNVMfQ%2FDopkA5Nhz3SRRCkYrKzHRnUqFiEMJpH9tKAPgnXLX8iQuz8TX%2Bk&X-Amz-Signature=57fd3017a295898e2d6583258e44e5a78b69d02257c161e4790e2f85dbd014b1&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RV2TUAKB%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T152358Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEI%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDolugcMR%2BeKtXd7WYe5pZi%2BcvqVNqTXQ83rrQ9fy%2BP%2BQIgBZQ5pF7uLk82c0BeJFwOb%2FZleGiWGD1eNM0ebJ9PVdkqiAQIqP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMAlZB7P9jibwlEWDyrcA2NY%2B0zblKYcr%2Fj9KeQv21Lzbm6OoN%2FBpiCDyICIT4DOtGNDufTr%2BA0qEbZDpZQCJnlloyXyhgSlzJtYilF9O3vJRdod69PLyAF6YiOj4J2w5YKNZ%2FPeorb0Im%2FW1%2BDXNUif3C3uS7O0D%2FEXIyHU8qsqXH4zuMLCTyo%2BJi%2FoiYz6wE4iEqiPMfkthqSQGt62ykgof5KlTdqsSuL%2BiKkg5mASNLcVTVOKlVjK1B0wiVM1wx4UlEu%2BCa5Q2zG8yGMQBVLuX7qx8qj3eGXe9uvKx%2Bj8HpOWBaSuzp25m6MFK4%2BCHX12BWXpZzBvcbYfwzEukXSbnnEdYwjG1USMfX2BsNHUvPYZ9V7BkKZfeOn4dRqVv0bYPqSw%2FfWwxBET55CgQeI6dGgJ2SSq2ylNSbuLq5EY9LN1f3WLtL2xCFuyE7mcr%2FoHVpcoWoGLtaPjFoq30dGgNBNYYyyMUkbE9SgGLhl4ipENr81rALS3p%2BX8%2B4hHx6opvZqwErD5k23hulLn2oDt7ifF83MLvIUXDjPW8K9pxiLcl68lXLofq4PvKffWkbrLo2kUUFbtq%2BaU2iCp5U9JS21zNAoni9Gbqlau8xgiSKs%2B0tbGJHjx9Q0rb6SdPa6mSaXg3WeSRP%2B%2FMJmIo70GOqUBVInj6v9IN8HetUaCkECnv7CYVedauLqoPiRh7vz6zyTCrcfY0TcxAHS0U496I5tp1RHbIwM%2FL9t2UfQq3Oexj4T%2FF%2B%2BwSeEZZhOE2nT9pKEwV%2Bn%2Fd0%2Fy%2BzdIncyYJayyecKFkVAd9o7EWlnoGIkpZZACQW8Uhr5AUGi3YVYqswOnUA4Ly%2FHKIFD2QE00C0Y6d5FXeLB93QB4%2F%2Fb%2BcaD%2F%2FIowV5lU&X-Amz-Signature=dccb76758ef6571104f9fd064df6c9f4c5b4327375b807cde5ae44f14fbc3527&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RV2TUAKB%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T152358Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEI%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDolugcMR%2BeKtXd7WYe5pZi%2BcvqVNqTXQ83rrQ9fy%2BP%2BQIgBZQ5pF7uLk82c0BeJFwOb%2FZleGiWGD1eNM0ebJ9PVdkqiAQIqP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMAlZB7P9jibwlEWDyrcA2NY%2B0zblKYcr%2Fj9KeQv21Lzbm6OoN%2FBpiCDyICIT4DOtGNDufTr%2BA0qEbZDpZQCJnlloyXyhgSlzJtYilF9O3vJRdod69PLyAF6YiOj4J2w5YKNZ%2FPeorb0Im%2FW1%2BDXNUif3C3uS7O0D%2FEXIyHU8qsqXH4zuMLCTyo%2BJi%2FoiYz6wE4iEqiPMfkthqSQGt62ykgof5KlTdqsSuL%2BiKkg5mASNLcVTVOKlVjK1B0wiVM1wx4UlEu%2BCa5Q2zG8yGMQBVLuX7qx8qj3eGXe9uvKx%2Bj8HpOWBaSuzp25m6MFK4%2BCHX12BWXpZzBvcbYfwzEukXSbnnEdYwjG1USMfX2BsNHUvPYZ9V7BkKZfeOn4dRqVv0bYPqSw%2FfWwxBET55CgQeI6dGgJ2SSq2ylNSbuLq5EY9LN1f3WLtL2xCFuyE7mcr%2FoHVpcoWoGLtaPjFoq30dGgNBNYYyyMUkbE9SgGLhl4ipENr81rALS3p%2BX8%2B4hHx6opvZqwErD5k23hulLn2oDt7ifF83MLvIUXDjPW8K9pxiLcl68lXLofq4PvKffWkbrLo2kUUFbtq%2BaU2iCp5U9JS21zNAoni9Gbqlau8xgiSKs%2B0tbGJHjx9Q0rb6SdPa6mSaXg3WeSRP%2B%2FMJmIo70GOqUBVInj6v9IN8HetUaCkECnv7CYVedauLqoPiRh7vz6zyTCrcfY0TcxAHS0U496I5tp1RHbIwM%2FL9t2UfQq3Oexj4T%2FF%2B%2BwSeEZZhOE2nT9pKEwV%2Bn%2Fd0%2Fy%2BzdIncyYJayyecKFkVAd9o7EWlnoGIkpZZACQW8Uhr5AUGi3YVYqswOnUA4Ly%2FHKIFD2QE00C0Y6d5FXeLB93QB4%2F%2Fb%2BcaD%2F%2FIowV5lU&X-Amz-Signature=4bcb7d954e9364f2a467f6f9c3e9769be92dfece1036fb934dfc0cab7c043085&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RV2TUAKB%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T152358Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEI%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDolugcMR%2BeKtXd7WYe5pZi%2BcvqVNqTXQ83rrQ9fy%2BP%2BQIgBZQ5pF7uLk82c0BeJFwOb%2FZleGiWGD1eNM0ebJ9PVdkqiAQIqP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMAlZB7P9jibwlEWDyrcA2NY%2B0zblKYcr%2Fj9KeQv21Lzbm6OoN%2FBpiCDyICIT4DOtGNDufTr%2BA0qEbZDpZQCJnlloyXyhgSlzJtYilF9O3vJRdod69PLyAF6YiOj4J2w5YKNZ%2FPeorb0Im%2FW1%2BDXNUif3C3uS7O0D%2FEXIyHU8qsqXH4zuMLCTyo%2BJi%2FoiYz6wE4iEqiPMfkthqSQGt62ykgof5KlTdqsSuL%2BiKkg5mASNLcVTVOKlVjK1B0wiVM1wx4UlEu%2BCa5Q2zG8yGMQBVLuX7qx8qj3eGXe9uvKx%2Bj8HpOWBaSuzp25m6MFK4%2BCHX12BWXpZzBvcbYfwzEukXSbnnEdYwjG1USMfX2BsNHUvPYZ9V7BkKZfeOn4dRqVv0bYPqSw%2FfWwxBET55CgQeI6dGgJ2SSq2ylNSbuLq5EY9LN1f3WLtL2xCFuyE7mcr%2FoHVpcoWoGLtaPjFoq30dGgNBNYYyyMUkbE9SgGLhl4ipENr81rALS3p%2BX8%2B4hHx6opvZqwErD5k23hulLn2oDt7ifF83MLvIUXDjPW8K9pxiLcl68lXLofq4PvKffWkbrLo2kUUFbtq%2BaU2iCp5U9JS21zNAoni9Gbqlau8xgiSKs%2B0tbGJHjx9Q0rb6SdPa6mSaXg3WeSRP%2B%2FMJmIo70GOqUBVInj6v9IN8HetUaCkECnv7CYVedauLqoPiRh7vz6zyTCrcfY0TcxAHS0U496I5tp1RHbIwM%2FL9t2UfQq3Oexj4T%2FF%2B%2BwSeEZZhOE2nT9pKEwV%2Bn%2Fd0%2Fy%2BzdIncyYJayyecKFkVAd9o7EWlnoGIkpZZACQW8Uhr5AUGi3YVYqswOnUA4Ly%2FHKIFD2QE00C0Y6d5FXeLB93QB4%2F%2Fb%2BcaD%2F%2FIowV5lU&X-Amz-Signature=24761bfaa6da7f919f84e0d5fa5d12f1c7b59c4075ece2b0d55f621acad4d8c5&X-Amz-SignedHeaders=host&x-id=GetObject)


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

