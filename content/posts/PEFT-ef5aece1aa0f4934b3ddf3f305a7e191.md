---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB46645ABBRTO%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250222T212147Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD1VhtGxu8SBFBG1Ui\
  xYO%2BAhnq8qF2wOeHYa5YAtnMHgQIhAIwLKT0nAc9YOfiufMprzoZ6fF8V%2FxmP%2B%2BlPWbU9\
  rZLvKogECPL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwcfkjR5znqk\
  69hYZAq3AMmqQjQmcRPiOICXkPK%2B5XdMKVIDDg%2B9wjHoX2BlH95%2BGtf%2FRScki08Rg6HCs\
  uRjEKnt1dgYYpwa7nOAM062TfK21xFhd8UneDaS%2F%2BEj9vqypDkk1K5ygI2CkFwX1b0yrSfJf0\
  esGfUgJScW5dUhGJSwQ5f8KukJjWvSA11FJTj0Sid%2FDY4PtxiW%2FULwO%2FaGlLyTUcye%2F4V\
  9zU%2BqVRqVSrVhHVtyVD2d2chuW7a%2FWxMVkCfa3pRxK3jPmzW5VQ8GYs3OzYDV0Vql8jBtte63\
  Ew5OAQTooYMreD2r6g5uMgFFI7BXyqlAC7khvS7TaPO84OJsRQcXi0gjNPBdYk9VTFU%2B%2FkpGB\
  bR0ygxs8Jy%2FrmMxvP9meeF2II3xZY8mx%2BG57plwXYCduv3vzSn013I63MJGG5GAi1pLy1MLbH\
  L0JSaJ%2BoOWvNz%2BDJijsEEJpRpEPEQyfUYquXTR%2B1d0d1xtN%2BljoNLpj12J%2FuMFBWXwR\
  ViFanrjOuSxunJefr46Af6GaLjWV6aXzxYZ5JEDeTPY%2BqV8w%2FAN3eC4wT1HyV11ASkhmOuuqa\
  V4hm6YjUrZ25ZYbEdtiC7pHqktnN24DUvCGxoDOpwGb3dvuyGZxH7Q32vCYmARBUGa6pn7OPQ9DDt\
  iOi9BjqkAaQggMy%2FFXxqUZ01h%2BsHO5cTNDk%2BeVWlIyQga9eXIQzDhx38go4EKdSDU32dUMH\
  p8WkzBg4ySwxTtRQo5Umx49kRXB8dEp8nyq2OAid0KatXEjLy%2Bn8bxbeQ%2FqVbUbzfQyLe76sz\
  k0edA1ZO15FBjtG72KynMPgpTjomR%2FvRid4VFr%2Buwf20bXFJ3PCYqzfowpaeBV73oRBhYc8vG\
  TNuh27JGiHw&X-Amz-Signature=ee7c338b9bc61da78f3876ed68c3043f6673c5827256d8db7\
  1a5a065aa15516d&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466Q4ESXTUF%2F20250222%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250222T212020Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEMj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEY\
        CIQCIRFNgqNwdCSOEuMtA9hkUzc1GEzpOuyhVMxp9pbdDTwIhALJrmk4EMshdv%2BuNc8wR\
        3Vs6DlVXnyYfpvaE63jlpmupKogECPH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM\
        3NDIzMTgzODA1IgyE91pgcFOhqRM5O30q3AOm%2FzRZPGz7nGjG6PP49a%2Fl%2F72v6bWu\
        R2LVHdEkLbrKc1jWrKTx7%2FYX%2BYK%2BfokoZrw64WZBuacNjc5oj9I3%2FZfchsp00Od\
        eBAyOz7IrqT3tduns8jmiR2OgxzSZi59QR5mDyFhuAgY0Z6PwGL1W34idYHZRkIwipIMhe9\
        MQr9HOZRQpRu1rNg8ERed3rdHV2plN3v%2FJSDmufZMkXpWbNsr4pEIKA1LR0%2BLwUcIh6\
        4tCIU8LgiHG4cf98B9cclxpEjMPGM0dJhzMC05zQKuu%2FhTTvu0nzOxe6leCXyvE6h3qoG\
        jwPn2YgO%2Fz1PW2jB40xAIoQ7XMP%2FO%2Fyb2QczOX9ONUwQGpe2fAhiyzX9z5CIOvn20\
        yf2dbo4lIbUrzdh1IvPp4StNifK5QB8dYnMrxVATKmfoy%2FyTIX1lSSeeh9zFS2oiysogq\
        vw9RA6Ua7Qyz5Vt8hGPDRkEEO%2FwZk8GZUPOTFXMfeSQbIteDPZTolpqGyJtSL9ToBNE1O\
        eDiyrDTJ4LUva9fvaafwH0XasdjwxYc850apLqzLmGMqeKBhgI9xCEfvlO%2FDGTY4TVUQ5\
        XkHzgXjR55JHz3xXokgwyiEdhg6oVwhO%2FiylC8PeEkc3qXE9hJdR6wjIB3G79LpzC87%2\
        Be9BjqkAbAnSHgQG5xIKeda7zUki0RXOOQei1Bj%2BHYIifrcSmRwSWvBD2azuQ0%2BUsB%\
        2FTCR14moAVXhkVse7U4LA6QlSZmdS7%2F%2BN41%2FJi5rS8RFJ30L5%2F5QhIVGgZuKeh\
        LvX7N2oyBpPuMb6Kmyg%2BE%2BMZ6dgJw%2B7NNwZ1NFVhJF0sDopUT5bks11pU0gsgJ2Cm\
        z5Sj3xo7fixhAmWIx%2BVRRCXEUe7qb6apA6&X-Amz-Signature=234c5ee70f5672545c\
        8a3c3d45075034c1cdfff2f33b8ffbb4ab6b14321ab601&X-Amz-SignedHeaders=host\
        &x-id=GetObject"
      expiry_time: "2025-02-22T22:20:20.309Z"
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
UPDATE_TIME: "2025-02-22T21:21:56.072Z"
EXPIRY_TIME: "2025-02-22T22:21:45.417Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SV66OO6K%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T212145Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEqzlKhzEX%2FdZRFrM6%2BocxB6X8gIkV%2Fw9jGvwEvAhFUjAiADhivxRydT97787M8SbEDMEo2LGlEdr1nuGeyBYLWS9SqIBAjy%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMoY%2FmBVpW%2FNiB%2BBDJKtwDIlQysnmcD2H2bXfnZaSos2wqJBKaoivuyBlK42whKi3d0%2BpgWktzzRXbodRW6PKbIIT5z3Hxpk23NOpUuBGlIT%2BsJFp7iqbVzGFH1D35QLOWt8xJnkfxXQoFABseRjhecQA5BsyTNvUIE86ilCW5AkkVBdscsWIkMTMe694I1nwg2V23RDJtZkOxZ9yJ2DzTVkSwNdkiG9HQluWusHnsMSWor5gBcYTimyKhmmrAk6aXASHuWUIhb9qFnyNFVrYwk9VsAoroFM4%2BLXniwjESaeC9gAyqiC1w2MiKRhaVFKwEHmjFe9iALI18rK%2BTEt7LtKbljgAUgOtzWexpsH4KXTfXjCUeoiInSxUcyVclAs19B%2BQzTlVoVP1yVw1eMVExZWWqMI7JL9ccegWh48ETqAWLdppTN4iqkkE3FA9kVotevgBJ00xMly4wPXn%2BHMOIAlu5BFB6kEX4vqbd8W4rRKB1KNh2qlZF2M7AEpMQAjOVNnleumP4FyTHuDQyPKXQXn1aqGBnlqlE5%2B2CT%2Bz7J4u3aykRMn2%2BSpLAruGAgqDQrPq2jvnzpcx%2BBlbY7M9bPgdNSO4qnmgDZxYV8DhX6nfbmq6uMLsPr688m0jgS%2Ff%2FKrG8uQB3ls79mMUwhInovQY6pgH5bpe4Gnx0MJ4%2F7hlMxA%2FM4ASL8V3UQecwzksIzRyELyClBqDspsftf%2BxWEdhfk0uWvommmM2kfIbh6DvfS77G2rNbG0WUx15P7un6OErwav6yhoy2WHduc0seRxuENo4AltwKensAIdLPlkTwBy2NZivHbqrm8s%2BAbI3xuqMK581kZ7bke1fPZ%2FAYz5iKfDblNqfdN2fFswqrL0iAGAcR9ACsKy1S&X-Amz-Signature=b2607568f9e9391706213f251e203dc48cff1553cf850a8f9ba6534591af8bb4&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SV66OO6K%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T212145Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEqzlKhzEX%2FdZRFrM6%2BocxB6X8gIkV%2Fw9jGvwEvAhFUjAiADhivxRydT97787M8SbEDMEo2LGlEdr1nuGeyBYLWS9SqIBAjy%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMoY%2FmBVpW%2FNiB%2BBDJKtwDIlQysnmcD2H2bXfnZaSos2wqJBKaoivuyBlK42whKi3d0%2BpgWktzzRXbodRW6PKbIIT5z3Hxpk23NOpUuBGlIT%2BsJFp7iqbVzGFH1D35QLOWt8xJnkfxXQoFABseRjhecQA5BsyTNvUIE86ilCW5AkkVBdscsWIkMTMe694I1nwg2V23RDJtZkOxZ9yJ2DzTVkSwNdkiG9HQluWusHnsMSWor5gBcYTimyKhmmrAk6aXASHuWUIhb9qFnyNFVrYwk9VsAoroFM4%2BLXniwjESaeC9gAyqiC1w2MiKRhaVFKwEHmjFe9iALI18rK%2BTEt7LtKbljgAUgOtzWexpsH4KXTfXjCUeoiInSxUcyVclAs19B%2BQzTlVoVP1yVw1eMVExZWWqMI7JL9ccegWh48ETqAWLdppTN4iqkkE3FA9kVotevgBJ00xMly4wPXn%2BHMOIAlu5BFB6kEX4vqbd8W4rRKB1KNh2qlZF2M7AEpMQAjOVNnleumP4FyTHuDQyPKXQXn1aqGBnlqlE5%2B2CT%2Bz7J4u3aykRMn2%2BSpLAruGAgqDQrPq2jvnzpcx%2BBlbY7M9bPgdNSO4qnmgDZxYV8DhX6nfbmq6uMLsPr688m0jgS%2Ff%2FKrG8uQB3ls79mMUwhInovQY6pgH5bpe4Gnx0MJ4%2F7hlMxA%2FM4ASL8V3UQecwzksIzRyELyClBqDspsftf%2BxWEdhfk0uWvommmM2kfIbh6DvfS77G2rNbG0WUx15P7un6OErwav6yhoy2WHduc0seRxuENo4AltwKensAIdLPlkTwBy2NZivHbqrm8s%2BAbI3xuqMK581kZ7bke1fPZ%2FAYz5iKfDblNqfdN2fFswqrL0iAGAcR9ACsKy1S&X-Amz-Signature=729de3428929c92048d515dd4cc723c057aa61c26055be2a933d87cbbbe2750d&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SV66OO6K%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T212145Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEqzlKhzEX%2FdZRFrM6%2BocxB6X8gIkV%2Fw9jGvwEvAhFUjAiADhivxRydT97787M8SbEDMEo2LGlEdr1nuGeyBYLWS9SqIBAjy%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMoY%2FmBVpW%2FNiB%2BBDJKtwDIlQysnmcD2H2bXfnZaSos2wqJBKaoivuyBlK42whKi3d0%2BpgWktzzRXbodRW6PKbIIT5z3Hxpk23NOpUuBGlIT%2BsJFp7iqbVzGFH1D35QLOWt8xJnkfxXQoFABseRjhecQA5BsyTNvUIE86ilCW5AkkVBdscsWIkMTMe694I1nwg2V23RDJtZkOxZ9yJ2DzTVkSwNdkiG9HQluWusHnsMSWor5gBcYTimyKhmmrAk6aXASHuWUIhb9qFnyNFVrYwk9VsAoroFM4%2BLXniwjESaeC9gAyqiC1w2MiKRhaVFKwEHmjFe9iALI18rK%2BTEt7LtKbljgAUgOtzWexpsH4KXTfXjCUeoiInSxUcyVclAs19B%2BQzTlVoVP1yVw1eMVExZWWqMI7JL9ccegWh48ETqAWLdppTN4iqkkE3FA9kVotevgBJ00xMly4wPXn%2BHMOIAlu5BFB6kEX4vqbd8W4rRKB1KNh2qlZF2M7AEpMQAjOVNnleumP4FyTHuDQyPKXQXn1aqGBnlqlE5%2B2CT%2Bz7J4u3aykRMn2%2BSpLAruGAgqDQrPq2jvnzpcx%2BBlbY7M9bPgdNSO4qnmgDZxYV8DhX6nfbmq6uMLsPr688m0jgS%2Ff%2FKrG8uQB3ls79mMUwhInovQY6pgH5bpe4Gnx0MJ4%2F7hlMxA%2FM4ASL8V3UQecwzksIzRyELyClBqDspsftf%2BxWEdhfk0uWvommmM2kfIbh6DvfS77G2rNbG0WUx15P7un6OErwav6yhoy2WHduc0seRxuENo4AltwKensAIdLPlkTwBy2NZivHbqrm8s%2BAbI3xuqMK581kZ7bke1fPZ%2FAYz5iKfDblNqfdN2fFswqrL0iAGAcR9ACsKy1S&X-Amz-Signature=edc087db56797320078d7ec546048c734793c7d2ae138b364053dd1fd65cdd17&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SV66OO6K%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T212145Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEqzlKhzEX%2FdZRFrM6%2BocxB6X8gIkV%2Fw9jGvwEvAhFUjAiADhivxRydT97787M8SbEDMEo2LGlEdr1nuGeyBYLWS9SqIBAjy%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMoY%2FmBVpW%2FNiB%2BBDJKtwDIlQysnmcD2H2bXfnZaSos2wqJBKaoivuyBlK42whKi3d0%2BpgWktzzRXbodRW6PKbIIT5z3Hxpk23NOpUuBGlIT%2BsJFp7iqbVzGFH1D35QLOWt8xJnkfxXQoFABseRjhecQA5BsyTNvUIE86ilCW5AkkVBdscsWIkMTMe694I1nwg2V23RDJtZkOxZ9yJ2DzTVkSwNdkiG9HQluWusHnsMSWor5gBcYTimyKhmmrAk6aXASHuWUIhb9qFnyNFVrYwk9VsAoroFM4%2BLXniwjESaeC9gAyqiC1w2MiKRhaVFKwEHmjFe9iALI18rK%2BTEt7LtKbljgAUgOtzWexpsH4KXTfXjCUeoiInSxUcyVclAs19B%2BQzTlVoVP1yVw1eMVExZWWqMI7JL9ccegWh48ETqAWLdppTN4iqkkE3FA9kVotevgBJ00xMly4wPXn%2BHMOIAlu5BFB6kEX4vqbd8W4rRKB1KNh2qlZF2M7AEpMQAjOVNnleumP4FyTHuDQyPKXQXn1aqGBnlqlE5%2B2CT%2Bz7J4u3aykRMn2%2BSpLAruGAgqDQrPq2jvnzpcx%2BBlbY7M9bPgdNSO4qnmgDZxYV8DhX6nfbmq6uMLsPr688m0jgS%2Ff%2FKrG8uQB3ls79mMUwhInovQY6pgH5bpe4Gnx0MJ4%2F7hlMxA%2FM4ASL8V3UQecwzksIzRyELyClBqDspsftf%2BxWEdhfk0uWvommmM2kfIbh6DvfS77G2rNbG0WUx15P7un6OErwav6yhoy2WHduc0seRxuENo4AltwKensAIdLPlkTwBy2NZivHbqrm8s%2BAbI3xuqMK581kZ7bke1fPZ%2FAYz5iKfDblNqfdN2fFswqrL0iAGAcR9ACsKy1S&X-Amz-Signature=fde9f6a2e2350d9cb5ddadc2cedfc47653f0a57bd046ed919a73d800b5baa107&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SV66OO6K%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T212145Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEqzlKhzEX%2FdZRFrM6%2BocxB6X8gIkV%2Fw9jGvwEvAhFUjAiADhivxRydT97787M8SbEDMEo2LGlEdr1nuGeyBYLWS9SqIBAjy%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMoY%2FmBVpW%2FNiB%2BBDJKtwDIlQysnmcD2H2bXfnZaSos2wqJBKaoivuyBlK42whKi3d0%2BpgWktzzRXbodRW6PKbIIT5z3Hxpk23NOpUuBGlIT%2BsJFp7iqbVzGFH1D35QLOWt8xJnkfxXQoFABseRjhecQA5BsyTNvUIE86ilCW5AkkVBdscsWIkMTMe694I1nwg2V23RDJtZkOxZ9yJ2DzTVkSwNdkiG9HQluWusHnsMSWor5gBcYTimyKhmmrAk6aXASHuWUIhb9qFnyNFVrYwk9VsAoroFM4%2BLXniwjESaeC9gAyqiC1w2MiKRhaVFKwEHmjFe9iALI18rK%2BTEt7LtKbljgAUgOtzWexpsH4KXTfXjCUeoiInSxUcyVclAs19B%2BQzTlVoVP1yVw1eMVExZWWqMI7JL9ccegWh48ETqAWLdppTN4iqkkE3FA9kVotevgBJ00xMly4wPXn%2BHMOIAlu5BFB6kEX4vqbd8W4rRKB1KNh2qlZF2M7AEpMQAjOVNnleumP4FyTHuDQyPKXQXn1aqGBnlqlE5%2B2CT%2Bz7J4u3aykRMn2%2BSpLAruGAgqDQrPq2jvnzpcx%2BBlbY7M9bPgdNSO4qnmgDZxYV8DhX6nfbmq6uMLsPr688m0jgS%2Ff%2FKrG8uQB3ls79mMUwhInovQY6pgH5bpe4Gnx0MJ4%2F7hlMxA%2FM4ASL8V3UQecwzksIzRyELyClBqDspsftf%2BxWEdhfk0uWvommmM2kfIbh6DvfS77G2rNbG0WUx15P7un6OErwav6yhoy2WHduc0seRxuENo4AltwKensAIdLPlkTwBy2NZivHbqrm8s%2BAbI3xuqMK581kZ7bke1fPZ%2FAYz5iKfDblNqfdN2fFswqrL0iAGAcR9ACsKy1S&X-Amz-Signature=67d28fbc4af2e5cc4dc00e45fdbf2a14e5377f9aabf372e7e1babce12b49e056&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QP4FQCHF%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T212146Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCKTp7eWmVLf9xJB2cBWx1h79FOPJU%2FLQ%2FygTWOW8A0dgIgV4EK9X7OINuIlWqZLxjxGvSFHH0ADwnZ68JQlqWecC8qiAQI8f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDM96jLJgT9yKUIt7UyrcA8x4Vs4FkRFG6iGvQPlJaaFF%2B9Yx8QFK4LOUqi4vGoadLDv68g3m%2BudEtuErXvc3KVj%2FyIj8mfzFrgrTkeEEIx58DKmWps8ORNqBwUrOLBp3XFtIYnWPtTrtGnYmzimW8VcUqtFDO7m8uPSfa1hyx87NsJlNw1rLGlvNd%2FD0cJZecakXp20ChRgUxDE%2BzmGpzY85d1xjEWDwCedKGnRuRYEu6hCbwkdrWcNFtp%2BgXqbRqaECKiOyOyRjTBxlpQY6gkfHvsv16JC5D20KWVZDgvxnyNiT%2BrkLsNn8zobe9c%2FA4o7ewbVprAicJE2O4PtUWS8014B7BMIWP1vzC1GJvLau44TSERRJB0sInNzPFZQ9YhWqKZ2ob3dd7EM5nkyq4QAs7eqFkr9vReG4kZpiG%2BWUwwyNQEcYe21cSq1fsdHACg6ZEyqZt00PmsZ1A0ntsQjBI1pBGXzwhPoVEQtKb8ndtg3D5WLfFPd6beQaLJ1z9mle7bf7TEDGYz68o2J8Vme9xG8q%2FwZq6uCidStEdpP7z1mKLVZ1WchGHB3b2fJARViSOfhT2PGemtK5KdZ1eB97oop3VT7I5BWdJ%2B1dHuKZxKdzzyqRd4O2zuqBcd5D3pd6UrD96mXBzUv%2FMJ7j570GOqUBjkeF0wAiAbok13ZUlZQ90sxWfG7nuI9SJseGLI5%2FBjXYMte9gugn1TjrwWEs86ozW62LoLx2Oj0389Ej5VzrKuDIKTB1BNsXNVpktO3XTNmPw5Xhw%2FdsFG0WWV3ss7JCu%2FBddWu%2BwuTVmga7rE2DpySXgc3ZEAoliCMRZKDvfskJk6XhiiH0Mlkt4GCVDZTv9omBI4JiSUp8EgTZTgOXwmmtml1A&X-Amz-Signature=c0687ae5f6c677a6a4192f76b7d435ad1103c58d31d8e2d00a1163bd772b1f2c&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46667WVQLYJ%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T212147Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDVFCpWivvzt9e6F%2ByxAxlqYFX1hpI%2Fm2bfSrp7RLGEkgIhANihWo1mGOTbTI8Y5iOvHbzq%2FyFmKM4cHq%2F8%2F03Sl%2BqpKogECPL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyrNyAf5XGm9vFare8q3AO%2FehHvhrcewYA%2BSVDRc%2FTyFmQRKdk6QamKa5rHcupvJvenqNiG%2F1S5lfYr1k%2Bruc7XWgfWKPT5rZRr4Bomrv%2Fk5%2Fsiz7U%2BgqyhgGTcsiGZl5v%2BSRBz6F%2BDPOLcD5HH4JEOcW9hQbup89BedtjH69kKg1OptVvdf%2FF3IAn1J02CZhjzgwihOEE7cavk7NP8%2BAxvTt8tcJGBgRGp7Cig9AVg6eORiIyhyv44LU2VgsPjHbvxx3D1oyVD2b2MGLpXBiFmyznUhyaVvD2LM17irAVyWBCTAkXceYAhtXO46RaDB%2BApN2BNpbSszP%2BPlX4rT8J2pK1aZ7CRT4DKVjYHsF1nRYM1K1V8ftOgyxycxCs29NP%2F%2BLDQ4NzBjHesGv%2FHXm3WDOYEfpLNNBJo5dCFSoAN%2FqPAuAmiKMsSL%2F85M6dnIqRWJVawAlUKBclxA7hNlazbiI3SUvsQoUSCSxZdmn67cZB0IKvhThEF52pQ8vihiOuT6iQFptGqf7HRwOwrtxX1kIVhw0Kq12nCMja5fAsWTGfLyB5u16DVIkhv0z8Bnf5E9qC9GAbYe9t9k26n4AIalpPOwSoG%2FO7mrfYtPo2bJ%2FawM2wJCRWocvr7h%2FBRBy%2Fzbj%2FVoVVyLeJQJDCfh%2Bi9BjqkAeR5d1O9pU1Ln%2FvQnh%2BXfwBC4JutU1nRotzJ%2BhrhOr8JZ8LcHBAvzu%2F%2BePtb9Dt4uk2Yck8n%2BlISXceBBlLSoky7UdWXnf1t2tLbX9xT%2BecDG9yyH03Wy7fk2vWKeclm33pJMn%2FhWmUPU7SNSeZhiU6iEZmiyegSyr1rqXKI%2BaEFtGZQxdho97fZrfWh16e%2BxHs4tye81sBvAFss4ib7saiSBS94&X-Amz-Signature=f2351f2ae9f7dd3681421a584373589df767db4fbeae22ce9b31382f9e45fc77&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SV66OO6K%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T212146Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEqzlKhzEX%2FdZRFrM6%2BocxB6X8gIkV%2Fw9jGvwEvAhFUjAiADhivxRydT97787M8SbEDMEo2LGlEdr1nuGeyBYLWS9SqIBAjy%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMoY%2FmBVpW%2FNiB%2BBDJKtwDIlQysnmcD2H2bXfnZaSos2wqJBKaoivuyBlK42whKi3d0%2BpgWktzzRXbodRW6PKbIIT5z3Hxpk23NOpUuBGlIT%2BsJFp7iqbVzGFH1D35QLOWt8xJnkfxXQoFABseRjhecQA5BsyTNvUIE86ilCW5AkkVBdscsWIkMTMe694I1nwg2V23RDJtZkOxZ9yJ2DzTVkSwNdkiG9HQluWusHnsMSWor5gBcYTimyKhmmrAk6aXASHuWUIhb9qFnyNFVrYwk9VsAoroFM4%2BLXniwjESaeC9gAyqiC1w2MiKRhaVFKwEHmjFe9iALI18rK%2BTEt7LtKbljgAUgOtzWexpsH4KXTfXjCUeoiInSxUcyVclAs19B%2BQzTlVoVP1yVw1eMVExZWWqMI7JL9ccegWh48ETqAWLdppTN4iqkkE3FA9kVotevgBJ00xMly4wPXn%2BHMOIAlu5BFB6kEX4vqbd8W4rRKB1KNh2qlZF2M7AEpMQAjOVNnleumP4FyTHuDQyPKXQXn1aqGBnlqlE5%2B2CT%2Bz7J4u3aykRMn2%2BSpLAruGAgqDQrPq2jvnzpcx%2BBlbY7M9bPgdNSO4qnmgDZxYV8DhX6nfbmq6uMLsPr688m0jgS%2Ff%2FKrG8uQB3ls79mMUwhInovQY6pgH5bpe4Gnx0MJ4%2F7hlMxA%2FM4ASL8V3UQecwzksIzRyELyClBqDspsftf%2BxWEdhfk0uWvommmM2kfIbh6DvfS77G2rNbG0WUx15P7un6OErwav6yhoy2WHduc0seRxuENo4AltwKensAIdLPlkTwBy2NZivHbqrm8s%2BAbI3xuqMK581kZ7bke1fPZ%2FAYz5iKfDblNqfdN2fFswqrL0iAGAcR9ACsKy1S&X-Amz-Signature=98118991d6d17e4072ddad2aeecf089b2865e091c83d1d6441d646bad02e02eb&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SV66OO6K%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T212145Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEqzlKhzEX%2FdZRFrM6%2BocxB6X8gIkV%2Fw9jGvwEvAhFUjAiADhivxRydT97787M8SbEDMEo2LGlEdr1nuGeyBYLWS9SqIBAjy%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMoY%2FmBVpW%2FNiB%2BBDJKtwDIlQysnmcD2H2bXfnZaSos2wqJBKaoivuyBlK42whKi3d0%2BpgWktzzRXbodRW6PKbIIT5z3Hxpk23NOpUuBGlIT%2BsJFp7iqbVzGFH1D35QLOWt8xJnkfxXQoFABseRjhecQA5BsyTNvUIE86ilCW5AkkVBdscsWIkMTMe694I1nwg2V23RDJtZkOxZ9yJ2DzTVkSwNdkiG9HQluWusHnsMSWor5gBcYTimyKhmmrAk6aXASHuWUIhb9qFnyNFVrYwk9VsAoroFM4%2BLXniwjESaeC9gAyqiC1w2MiKRhaVFKwEHmjFe9iALI18rK%2BTEt7LtKbljgAUgOtzWexpsH4KXTfXjCUeoiInSxUcyVclAs19B%2BQzTlVoVP1yVw1eMVExZWWqMI7JL9ccegWh48ETqAWLdppTN4iqkkE3FA9kVotevgBJ00xMly4wPXn%2BHMOIAlu5BFB6kEX4vqbd8W4rRKB1KNh2qlZF2M7AEpMQAjOVNnleumP4FyTHuDQyPKXQXn1aqGBnlqlE5%2B2CT%2Bz7J4u3aykRMn2%2BSpLAruGAgqDQrPq2jvnzpcx%2BBlbY7M9bPgdNSO4qnmgDZxYV8DhX6nfbmq6uMLsPr688m0jgS%2Ff%2FKrG8uQB3ls79mMUwhInovQY6pgH5bpe4Gnx0MJ4%2F7hlMxA%2FM4ASL8V3UQecwzksIzRyELyClBqDspsftf%2BxWEdhfk0uWvommmM2kfIbh6DvfS77G2rNbG0WUx15P7un6OErwav6yhoy2WHduc0seRxuENo4AltwKensAIdLPlkTwBy2NZivHbqrm8s%2BAbI3xuqMK581kZ7bke1fPZ%2FAYz5iKfDblNqfdN2fFswqrL0iAGAcR9ACsKy1S&X-Amz-Signature=403627ac8b4c6caefcde8a794b9d461a5f27bc837ab9357c98167dd835f45f54&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SV66OO6K%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T212146Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEqzlKhzEX%2FdZRFrM6%2BocxB6X8gIkV%2Fw9jGvwEvAhFUjAiADhivxRydT97787M8SbEDMEo2LGlEdr1nuGeyBYLWS9SqIBAjy%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMoY%2FmBVpW%2FNiB%2BBDJKtwDIlQysnmcD2H2bXfnZaSos2wqJBKaoivuyBlK42whKi3d0%2BpgWktzzRXbodRW6PKbIIT5z3Hxpk23NOpUuBGlIT%2BsJFp7iqbVzGFH1D35QLOWt8xJnkfxXQoFABseRjhecQA5BsyTNvUIE86ilCW5AkkVBdscsWIkMTMe694I1nwg2V23RDJtZkOxZ9yJ2DzTVkSwNdkiG9HQluWusHnsMSWor5gBcYTimyKhmmrAk6aXASHuWUIhb9qFnyNFVrYwk9VsAoroFM4%2BLXniwjESaeC9gAyqiC1w2MiKRhaVFKwEHmjFe9iALI18rK%2BTEt7LtKbljgAUgOtzWexpsH4KXTfXjCUeoiInSxUcyVclAs19B%2BQzTlVoVP1yVw1eMVExZWWqMI7JL9ccegWh48ETqAWLdppTN4iqkkE3FA9kVotevgBJ00xMly4wPXn%2BHMOIAlu5BFB6kEX4vqbd8W4rRKB1KNh2qlZF2M7AEpMQAjOVNnleumP4FyTHuDQyPKXQXn1aqGBnlqlE5%2B2CT%2Bz7J4u3aykRMn2%2BSpLAruGAgqDQrPq2jvnzpcx%2BBlbY7M9bPgdNSO4qnmgDZxYV8DhX6nfbmq6uMLsPr688m0jgS%2Ff%2FKrG8uQB3ls79mMUwhInovQY6pgH5bpe4Gnx0MJ4%2F7hlMxA%2FM4ASL8V3UQecwzksIzRyELyClBqDspsftf%2BxWEdhfk0uWvommmM2kfIbh6DvfS77G2rNbG0WUx15P7un6OErwav6yhoy2WHduc0seRxuENo4AltwKensAIdLPlkTwBy2NZivHbqrm8s%2BAbI3xuqMK581kZ7bke1fPZ%2FAYz5iKfDblNqfdN2fFswqrL0iAGAcR9ACsKy1S&X-Amz-Signature=d220b2ce1db29c60443baa6148689580e3813ebab82d957281278d0d9131986e&X-Amz-SignedHeaders=host&x-id=GetObject)


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

