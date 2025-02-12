---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB46642WL3HC3%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250212T212213Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEN3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQC9XFDhT4EiOxC3gL1\
  Q9a1yfaPIotn4b13ILMldo1xtIwIgNfjHtF1rfLgyQ74YgL16FPQ14QtixHPSHGFNxcYsPcsqiAQI\
  9v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNNJNOS4WmMyAxgQhircA\
  ylRkH6ImgEr17UlWOrgASy9Kpq8pDZeHcVzftpmgSSE5umjthIHgPTkYnhYbrpi6yTHVD9Ryvceus\
  u%2FJQtljrxxdFu5feZBxb3IEhQThEJiNfuicq53BfnVBmPZLMV80h1DtTlGsc4rrJ0Gls4IfoONZ\
  77aemrNMohhOdAQYIgDmty7Sn0dTGnOS3RO02Ff%2FLezygD5a7aIEu7GjKd9z2Efe2WoWkHfIe4h\
  %2BVNBNBKTpR03kbE30uKOvSp%2FksEFTnD%2FPLNdSY2R9ZDFOERxA9f%2FmGALVYH%2FqV%2Fwt\
  pIqczpybTrzYnX%2FF4cBm6mT9kNI4fdvAzomdlNJdkQB9%2FtjaiCGsPNSD%2FhjCjEfJ4S1LtAy\
  8xzu7xxZNS5V%2FEzEulNLnSjGkpJf3ytYBn9RsCshYQF1Thr%2BqNCzNYYETgy%2BMa0A4wX%2BI\
  bRFZLx41HsOvqL%2FdH%2BuJ5aLJ3PeUCWyvJJDgY6iUMrzZek%2FlAxSPEt2qw6dE3K00plT6Q9%\
  2BUA3XgfrXti1rzh4V8GnGg%2FGsI%2BDChFT%2F6QWGMfnI7ltYJqFWcyQ4zzbA3RLMb0uDe4Shl\
  8fiClZi4JqFJfy7kFjIGZgEm3nPXFZo1tjAxp7YjmP88IcwJD20ismTsqZMFTq%2FMNaNtL0GOqUB\
  8zS%2BTbx%2B84khUJpOKjJjll6lPByzTMe%2BLk5DddsH1hewTqLhbbwbkxhmJkcjg6Aw7VF2ui%\
  2BdVGCwJQ2%2BIoYN9Tt5bxLUlTUMyqGH%2BfHlqD6Puaej3GIixarvGXlL7To5zQeZwghr1mwCQu\
  nTJvpVnQtaTKPGJFvh05wuAI5bKtDLYxOsaW6EFRS%2FWy8xFiD2ulwNrzUKvaSMPrFQBRx4iIbPB\
  YSt&X-Amz-Signature=df656ce42313e3ecb424ac834ca1b174eccadbb0ef83783c228b980bf\
  19d4ba9&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466TCENF5JQ%2F20250212%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250212T212045Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEN3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEY\
        CIQDfPGXZOEvlQYlOqbck9K4%2FXhxQOWFeROtS1FVJXPGsfgIhALGvuDNyMzsPrHzn6VDN\
        8o7i3VTnsjZaqhqJR711Zu7AKogECPb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM\
        3NDIzMTgzODA1IgwdHHAkdE7T9uq1rngq3AOP%2FPDicpLZso3tgQ%2FzgwgJLDdFSoq7iF\
        NpR79UQaYSK3CrykFUa8rqee2tFsumxQ2BGcKRHpS4Fybbqat3H6zR9jKuxBGtSabZ6dHXB\
        AMzUf394o2NVdo7sma3WEtujAxLfIuE9R0ueyHvmmElB3wxaUUJuKyPJ4UpBNuMKSol%2B4\
        eQCYL%2F6fjGAzZrgHUp%2BWPMeAhl2iqXSb%2BBNzyxDzQfmwYVf0Efee4oAHAUu0PRFqj\
        9OQ2x9DGV5B3%2BAoxJeG41m6WElm8UC9bCAA0xKXuMM9Zx95WB2IpKI3izzUhgRbHafSJU\
        %2BERIye682HBZLV5nSJIbX3%2BLT5nG1d1JaI9CyKOToiEcomua7m2N%2FY%2FBfHiOarE\
        %2BJQZltbGt6n98B1EN%2F4cRfz%2FfvIKF9eoyfLq0m6D%2FabnDsNYC1RPR6rArTHsDIf\
        pH2iZ13SkA8csc%2BPPcTJ%2FhD0%2FGH8kyxirIEts4iQi81FhkM1s1fjY8GfYPVYrLpW%\
        2Fo8tX41IlUDdxf2Z83bueN9L8gpVfmDo4M5a7YvlZhXGY1OUfpW%2Bp3q3NE%2BmJRaIgN\
        Mj1EWpGZrHsH8kBUGUBN5gI42ETrdOBpUTgyi36aLRvo1AhfURNXF6nrntWO6X7dPS9dC5j\
        pTzC1jbS9BjqkAaCPyZoNimiaJI9EiH%2BxTQIfdG5goTG9EJVHAN6GikjNddaZ1EwceIZ9\
        8Tu3iOczapGTHMl6tj1axKepOVWDJiQvV6veyB46oUsxawTlgX2u8TMQ3FeD32HkMuHNKWj\
        S8DiAN7WL2P6r34KfrILqp1Cl5GAwLYDcnBYlhSUn0%2FZlP9DpdrwYqBU64BMfYiMDprBn\
        8zHqGjfwvkoWS4hT4zU6ySmo&X-Amz-Signature=6c9255ea0479e537fe5b2615ad2b47\
        7e9b2981d3aa996e0fb9700e3d7bd98069&X-Amz-SignedHeaders=host&x-id=GetObj\
        ect"
      expiry_time: "2025-02-12T22:20:45.412Z"
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
UPDATE_TIME: "2025-02-12T21:22:19.403Z"
EXPIRY_TIME: "2025-02-12T22:22:10.773Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z35BL5LA%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T212211Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEN3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDIUcUObUppX0tg7nGw8SZdhUFXFKPeo%2FM7UTtVjzmdPwIgX9ZYpRWs4XLy1LTNuV1ibDnMtjEDCLoiq%2FIvT%2FBslBAqiAQI9v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDB4ycSBXX8CfkRIaaircA8%2FkzC64k1aUaWRaQ7NhQhWbwqVUoam2ojzjhkr9LGTysD2tgH%2BZ0hoICgGSJDJFQf1xDYcR2VHex4gV%2BX4gq%2FrWLX5hxuGN4nFAPQmRi7J7bULo2U1jv%2F3aFVHVdnApY9Wc%2FYvm1MuZF3UYa1%2B58A4oBpjGLLPZq4UJnszx8BCj2JGDIuP5NoG0TIbPeJGgGjGcQKQe6qKHmXfjFHIUqn2ONXsJkapgBONpjesdCivoFRzTEc7A7EloQXIYo45yMCC5qCjDfIiBDK4euB6BkahzCjrVR45x9qwJGrMPoyolIkiXczceT6VkNtm07JkT5UR3%2FWV%2BQKFM6a7ulFBztLRqT5qIAVvsOMpLzEIph6vZ3oIdLHIncGzoE8p5CcxSkIHmb1xwjTtAdMiwPneuPAgTNgBf0zYrOjhseHiDkI0w2YKhSfrV9mocCufNihXYpjJ8OnzXK%2Bg7XO3ug0JYqw%2FVLVESbhCOHIaKl3TgqHG6sD2Hl495oCM%2F1L5NdYtOWmnPY25WNCuclKV%2FrQRX5zQP2u5uiCTtxRqz9Z205mlwrl86NgssrEPSd3XHZjgQEAPIljOnNvUyS8BhenC71rSZ25eQPp6pcGFtUMZfhlPmQ78g2OfZX8zM15jkMIeNtL0GOqUBCo0us%2F7D5zh74zNxFZi7vgBEdCuZMMd1ZCp6V9NlRCbkJ1ZZYFtkt%2FVwqVxN5xLWDxJxIfJcFHniqWF2GEePcfLjdO%2FXR19eAwlz5uj%2BAMNYlzEUbuOFdas7PNkEn2kqqlMtSc4NCUD5N3hhMWB4iwIIbQgJUxKNhIEhoFlIUH4rKHBngHKc0Ergwn3ACcHAYISlnbhApZoxTCbyZtzGrwnPzJEf&X-Amz-Signature=44aaa85840da48a769b9edd7dd596c1c10a68be110fd77e2a732fda80907d317&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z35BL5LA%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T212211Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEN3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDIUcUObUppX0tg7nGw8SZdhUFXFKPeo%2FM7UTtVjzmdPwIgX9ZYpRWs4XLy1LTNuV1ibDnMtjEDCLoiq%2FIvT%2FBslBAqiAQI9v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDB4ycSBXX8CfkRIaaircA8%2FkzC64k1aUaWRaQ7NhQhWbwqVUoam2ojzjhkr9LGTysD2tgH%2BZ0hoICgGSJDJFQf1xDYcR2VHex4gV%2BX4gq%2FrWLX5hxuGN4nFAPQmRi7J7bULo2U1jv%2F3aFVHVdnApY9Wc%2FYvm1MuZF3UYa1%2B58A4oBpjGLLPZq4UJnszx8BCj2JGDIuP5NoG0TIbPeJGgGjGcQKQe6qKHmXfjFHIUqn2ONXsJkapgBONpjesdCivoFRzTEc7A7EloQXIYo45yMCC5qCjDfIiBDK4euB6BkahzCjrVR45x9qwJGrMPoyolIkiXczceT6VkNtm07JkT5UR3%2FWV%2BQKFM6a7ulFBztLRqT5qIAVvsOMpLzEIph6vZ3oIdLHIncGzoE8p5CcxSkIHmb1xwjTtAdMiwPneuPAgTNgBf0zYrOjhseHiDkI0w2YKhSfrV9mocCufNihXYpjJ8OnzXK%2Bg7XO3ug0JYqw%2FVLVESbhCOHIaKl3TgqHG6sD2Hl495oCM%2F1L5NdYtOWmnPY25WNCuclKV%2FrQRX5zQP2u5uiCTtxRqz9Z205mlwrl86NgssrEPSd3XHZjgQEAPIljOnNvUyS8BhenC71rSZ25eQPp6pcGFtUMZfhlPmQ78g2OfZX8zM15jkMIeNtL0GOqUBCo0us%2F7D5zh74zNxFZi7vgBEdCuZMMd1ZCp6V9NlRCbkJ1ZZYFtkt%2FVwqVxN5xLWDxJxIfJcFHniqWF2GEePcfLjdO%2FXR19eAwlz5uj%2BAMNYlzEUbuOFdas7PNkEn2kqqlMtSc4NCUD5N3hhMWB4iwIIbQgJUxKNhIEhoFlIUH4rKHBngHKc0Ergwn3ACcHAYISlnbhApZoxTCbyZtzGrwnPzJEf&X-Amz-Signature=5317a1b37b05121bb2d169f18408a00ec231d194302a0389af57e269216d4a85&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z35BL5LA%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T212211Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEN3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDIUcUObUppX0tg7nGw8SZdhUFXFKPeo%2FM7UTtVjzmdPwIgX9ZYpRWs4XLy1LTNuV1ibDnMtjEDCLoiq%2FIvT%2FBslBAqiAQI9v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDB4ycSBXX8CfkRIaaircA8%2FkzC64k1aUaWRaQ7NhQhWbwqVUoam2ojzjhkr9LGTysD2tgH%2BZ0hoICgGSJDJFQf1xDYcR2VHex4gV%2BX4gq%2FrWLX5hxuGN4nFAPQmRi7J7bULo2U1jv%2F3aFVHVdnApY9Wc%2FYvm1MuZF3UYa1%2B58A4oBpjGLLPZq4UJnszx8BCj2JGDIuP5NoG0TIbPeJGgGjGcQKQe6qKHmXfjFHIUqn2ONXsJkapgBONpjesdCivoFRzTEc7A7EloQXIYo45yMCC5qCjDfIiBDK4euB6BkahzCjrVR45x9qwJGrMPoyolIkiXczceT6VkNtm07JkT5UR3%2FWV%2BQKFM6a7ulFBztLRqT5qIAVvsOMpLzEIph6vZ3oIdLHIncGzoE8p5CcxSkIHmb1xwjTtAdMiwPneuPAgTNgBf0zYrOjhseHiDkI0w2YKhSfrV9mocCufNihXYpjJ8OnzXK%2Bg7XO3ug0JYqw%2FVLVESbhCOHIaKl3TgqHG6sD2Hl495oCM%2F1L5NdYtOWmnPY25WNCuclKV%2FrQRX5zQP2u5uiCTtxRqz9Z205mlwrl86NgssrEPSd3XHZjgQEAPIljOnNvUyS8BhenC71rSZ25eQPp6pcGFtUMZfhlPmQ78g2OfZX8zM15jkMIeNtL0GOqUBCo0us%2F7D5zh74zNxFZi7vgBEdCuZMMd1ZCp6V9NlRCbkJ1ZZYFtkt%2FVwqVxN5xLWDxJxIfJcFHniqWF2GEePcfLjdO%2FXR19eAwlz5uj%2BAMNYlzEUbuOFdas7PNkEn2kqqlMtSc4NCUD5N3hhMWB4iwIIbQgJUxKNhIEhoFlIUH4rKHBngHKc0Ergwn3ACcHAYISlnbhApZoxTCbyZtzGrwnPzJEf&X-Amz-Signature=c2be26f080f015f14c011e19de65dacbe371d1c7baec7f872d437c9c0961eb84&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z35BL5LA%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T212211Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEN3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDIUcUObUppX0tg7nGw8SZdhUFXFKPeo%2FM7UTtVjzmdPwIgX9ZYpRWs4XLy1LTNuV1ibDnMtjEDCLoiq%2FIvT%2FBslBAqiAQI9v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDB4ycSBXX8CfkRIaaircA8%2FkzC64k1aUaWRaQ7NhQhWbwqVUoam2ojzjhkr9LGTysD2tgH%2BZ0hoICgGSJDJFQf1xDYcR2VHex4gV%2BX4gq%2FrWLX5hxuGN4nFAPQmRi7J7bULo2U1jv%2F3aFVHVdnApY9Wc%2FYvm1MuZF3UYa1%2B58A4oBpjGLLPZq4UJnszx8BCj2JGDIuP5NoG0TIbPeJGgGjGcQKQe6qKHmXfjFHIUqn2ONXsJkapgBONpjesdCivoFRzTEc7A7EloQXIYo45yMCC5qCjDfIiBDK4euB6BkahzCjrVR45x9qwJGrMPoyolIkiXczceT6VkNtm07JkT5UR3%2FWV%2BQKFM6a7ulFBztLRqT5qIAVvsOMpLzEIph6vZ3oIdLHIncGzoE8p5CcxSkIHmb1xwjTtAdMiwPneuPAgTNgBf0zYrOjhseHiDkI0w2YKhSfrV9mocCufNihXYpjJ8OnzXK%2Bg7XO3ug0JYqw%2FVLVESbhCOHIaKl3TgqHG6sD2Hl495oCM%2F1L5NdYtOWmnPY25WNCuclKV%2FrQRX5zQP2u5uiCTtxRqz9Z205mlwrl86NgssrEPSd3XHZjgQEAPIljOnNvUyS8BhenC71rSZ25eQPp6pcGFtUMZfhlPmQ78g2OfZX8zM15jkMIeNtL0GOqUBCo0us%2F7D5zh74zNxFZi7vgBEdCuZMMd1ZCp6V9NlRCbkJ1ZZYFtkt%2FVwqVxN5xLWDxJxIfJcFHniqWF2GEePcfLjdO%2FXR19eAwlz5uj%2BAMNYlzEUbuOFdas7PNkEn2kqqlMtSc4NCUD5N3hhMWB4iwIIbQgJUxKNhIEhoFlIUH4rKHBngHKc0Ergwn3ACcHAYISlnbhApZoxTCbyZtzGrwnPzJEf&X-Amz-Signature=26e40cfaac40f4d494793416cbcc45ce50dbd23c9526e27da06473c2d5bdb2c8&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z35BL5LA%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T212211Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEN3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDIUcUObUppX0tg7nGw8SZdhUFXFKPeo%2FM7UTtVjzmdPwIgX9ZYpRWs4XLy1LTNuV1ibDnMtjEDCLoiq%2FIvT%2FBslBAqiAQI9v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDB4ycSBXX8CfkRIaaircA8%2FkzC64k1aUaWRaQ7NhQhWbwqVUoam2ojzjhkr9LGTysD2tgH%2BZ0hoICgGSJDJFQf1xDYcR2VHex4gV%2BX4gq%2FrWLX5hxuGN4nFAPQmRi7J7bULo2U1jv%2F3aFVHVdnApY9Wc%2FYvm1MuZF3UYa1%2B58A4oBpjGLLPZq4UJnszx8BCj2JGDIuP5NoG0TIbPeJGgGjGcQKQe6qKHmXfjFHIUqn2ONXsJkapgBONpjesdCivoFRzTEc7A7EloQXIYo45yMCC5qCjDfIiBDK4euB6BkahzCjrVR45x9qwJGrMPoyolIkiXczceT6VkNtm07JkT5UR3%2FWV%2BQKFM6a7ulFBztLRqT5qIAVvsOMpLzEIph6vZ3oIdLHIncGzoE8p5CcxSkIHmb1xwjTtAdMiwPneuPAgTNgBf0zYrOjhseHiDkI0w2YKhSfrV9mocCufNihXYpjJ8OnzXK%2Bg7XO3ug0JYqw%2FVLVESbhCOHIaKl3TgqHG6sD2Hl495oCM%2F1L5NdYtOWmnPY25WNCuclKV%2FrQRX5zQP2u5uiCTtxRqz9Z205mlwrl86NgssrEPSd3XHZjgQEAPIljOnNvUyS8BhenC71rSZ25eQPp6pcGFtUMZfhlPmQ78g2OfZX8zM15jkMIeNtL0GOqUBCo0us%2F7D5zh74zNxFZi7vgBEdCuZMMd1ZCp6V9NlRCbkJ1ZZYFtkt%2FVwqVxN5xLWDxJxIfJcFHniqWF2GEePcfLjdO%2FXR19eAwlz5uj%2BAMNYlzEUbuOFdas7PNkEn2kqqlMtSc4NCUD5N3hhMWB4iwIIbQgJUxKNhIEhoFlIUH4rKHBngHKc0Ergwn3ACcHAYISlnbhApZoxTCbyZtzGrwnPzJEf&X-Amz-Signature=ffef0f7d2497b5092e5c69ecd17817cbe85f4f84a760f9e6160a0934b61a45cc&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667IXCW2HB%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T212211Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEN3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCWqSC1mvmjnW1EkMOPeeE898k6MfN0kK58SDdeu0WpxgIhAKt8yTWD7FFPlAgtHBBwdnPOWRyAV78pL2z2PUCneP3yKogECPb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyR%2Bh49dpF1I6EjwPQq3AMBZP89baSUOgeDMt7GgTGGEangex7fSa5Zd0PBx7JJpJnr%2BeDxq6yL%2F0WHOE3zDmVv6KwPThZ07Lb3Z9ltHGQai%2FHos6P0naY%2BwdYhmqXOPMrkvf6hQ6gX3NkszH0BwWAK4TCQiunq0Gt5%2BYpka%2BHRsdKFPraCKA363UFmS9AFOk%2F1J4L1sg4UkAvxAy%2FrIsry7RS6KWQJgfPro3TkkzqXlxQyRPT2aslp%2BOZ%2F4WVGr00Ffaq%2BOCs1LnhSzwosnDTpcfLazaxUC2O4fpjdv0H4wUE1EfjxRKoz1i8%2BsE5nRPCiw4MXLvG%2B1ghAGJlTTFwk5%2BZgFb4NYbkSATsvMEa%2BFTn5WEafyPi%2FX%2BQwlEH1eLIwdv79HndKsvQ%2B853OIxhjOjUNk71PKq5vIDFyaNsMCgzCX9osE2bnookiM8Vh%2FNTlkjG%2FSoUI6DGgkKddmXPKBeE7XNTb6eudrgbeVx4xONPIneRWP05bcqk%2FmMjDih2yL0Ku%2B%2BPHNwiaK8eWv6SixRGwlBiCkyr%2B7nXgWaWbDAhTBJlkfs55ekGIpaU23FRrbf9e660bJsKlzNbqFCffijNUhk%2FkLANPdhIU2N4BPDunSJ0n%2BSYKrWcK7FB97p2OQ%2FJ8%2FehIhmK2gzDEjbS9BjqkAQ1e9dKzbUYA6rMNiLecr0IZbfQOg3F5VQvsa6%2FBfXJUH%2FwrPJl%2BKG6yZ1mNeVO7PmvGJ98coAfNQ7KqwFk21770%2BMh3XYS3MJpV8G861kb5CjJ8FPE7nDz1d%2BLJ8mo%2BEjVDjUYRqJkZXcIomaYbHTqJCD1FTRGoSPaBK9broGJfAgYqCn90DKC1SOzUN0SvZk8r1t7G12yTW6luxOH1QZp4ka7d&X-Amz-Signature=7b101861c5da58cf237189cd9d75a1d400df123318c221cd18f9e19e1c5b003d&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UCF5HCPL%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T212212Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEN3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIF2hR0TZODLEwzsbcU7fuSy90GxPBP3LzvpM9jVumNpNAiBw2sH3huJ1auSQLVv3MeGxhJSnnvCeUmP6RJEE%2Bf4I0SqIBAj2%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMPI5gonk6nGTGbGlBKtwD2ac%2Bw2fuRO5KbWetd8Xjpfeizxev0uh%2FYc7vLWbPvCDqSaszkbrECxtO3W5LYBOJRQ0iTmTWRzuVyAnk4BYZKA6ICO8vjmp9qW6Ixi9Dc3TQyFgBtdfbEsS4xDrGdBLUwNrPZ1X%2FiRn5nN22LRJ%2FgkEhUm%2F%2BdRTBjZDF9Rnrff6uVS97SJ90OJa7ThABisPlIP9HQXwhodNqnUCao3nK%2Fi6hU0jsPI7wlquz1nLeYhnrrFVFWzmyE1aNdqOFLJm2EfgytK4kAI0lxU7xu3zq%2BYD5qkwQqmhqCxVoxeLONAyvAD1m8dCgekDQIOKqDkAgWcEp3c7%2Fl7kZ29TPfjf5hdrGnmRTn0ArD2nVVILUdq8Nuts53Z09f6fA53n%2Bl2oYiu65srlod6Hu8R4T5MbX%2F75%2BN0wyJSpTGgu8n75Ab3mM6dv%2F8VB7f%2BnfiovKlIr0wECJFhG4nWCnktftPYFJ1A5SaBUDYkO86U7xlLkRUSseYCIp6EJvQ9bnWS8RhEm6UCblNLIHyclT21Lzg%2F%2FKW0g4OWP1zQt%2FgrMNNnr2301J%2Bdo%2BPeiJQx%2Baf%2BZbcUiuZB%2FUa%2BEjqNQbvgOF4LodNFVLYROvympF%2BnQFtmXwm%2BNhx8wUvGJlwV0uKfkw3I20vQY6pgFRFJpEPbFSvIsO41aIooWA3qkcllbWZvWZs0I%2BAXYzfyVmgI7Q2gGiCvQwI6CzPGfVGLGWJaFbKt2uZGepDXe6KM4RPW9s%2FVSOLdZ91lSvSiirdNEpCsc5V5fqDr4e9ytLA%2FG%2FeQezbWRPj9rA%2F%2BEkMCzShazYMYNjPBXM6fQH6l2%2F5g50yglIcTIktsQyA8cj%2FF1kzwcr8FpQJj0JSAFhQwghmuI7&X-Amz-Signature=74b99a0ec9b8a6429dc85ae2cde9725c51c5f426e2a3dd53b33156deedf5091f&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z35BL5LA%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T212211Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEN3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDIUcUObUppX0tg7nGw8SZdhUFXFKPeo%2FM7UTtVjzmdPwIgX9ZYpRWs4XLy1LTNuV1ibDnMtjEDCLoiq%2FIvT%2FBslBAqiAQI9v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDB4ycSBXX8CfkRIaaircA8%2FkzC64k1aUaWRaQ7NhQhWbwqVUoam2ojzjhkr9LGTysD2tgH%2BZ0hoICgGSJDJFQf1xDYcR2VHex4gV%2BX4gq%2FrWLX5hxuGN4nFAPQmRi7J7bULo2U1jv%2F3aFVHVdnApY9Wc%2FYvm1MuZF3UYa1%2B58A4oBpjGLLPZq4UJnszx8BCj2JGDIuP5NoG0TIbPeJGgGjGcQKQe6qKHmXfjFHIUqn2ONXsJkapgBONpjesdCivoFRzTEc7A7EloQXIYo45yMCC5qCjDfIiBDK4euB6BkahzCjrVR45x9qwJGrMPoyolIkiXczceT6VkNtm07JkT5UR3%2FWV%2BQKFM6a7ulFBztLRqT5qIAVvsOMpLzEIph6vZ3oIdLHIncGzoE8p5CcxSkIHmb1xwjTtAdMiwPneuPAgTNgBf0zYrOjhseHiDkI0w2YKhSfrV9mocCufNihXYpjJ8OnzXK%2Bg7XO3ug0JYqw%2FVLVESbhCOHIaKl3TgqHG6sD2Hl495oCM%2F1L5NdYtOWmnPY25WNCuclKV%2FrQRX5zQP2u5uiCTtxRqz9Z205mlwrl86NgssrEPSd3XHZjgQEAPIljOnNvUyS8BhenC71rSZ25eQPp6pcGFtUMZfhlPmQ78g2OfZX8zM15jkMIeNtL0GOqUBCo0us%2F7D5zh74zNxFZi7vgBEdCuZMMd1ZCp6V9NlRCbkJ1ZZYFtkt%2FVwqVxN5xLWDxJxIfJcFHniqWF2GEePcfLjdO%2FXR19eAwlz5uj%2BAMNYlzEUbuOFdas7PNkEn2kqqlMtSc4NCUD5N3hhMWB4iwIIbQgJUxKNhIEhoFlIUH4rKHBngHKc0Ergwn3ACcHAYISlnbhApZoxTCbyZtzGrwnPzJEf&X-Amz-Signature=0715f71886c2cb050f4b9dafab78d925724b707ade7785e8b0f754cd48e3b4a4&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z35BL5LA%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T212211Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEN3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDIUcUObUppX0tg7nGw8SZdhUFXFKPeo%2FM7UTtVjzmdPwIgX9ZYpRWs4XLy1LTNuV1ibDnMtjEDCLoiq%2FIvT%2FBslBAqiAQI9v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDB4ycSBXX8CfkRIaaircA8%2FkzC64k1aUaWRaQ7NhQhWbwqVUoam2ojzjhkr9LGTysD2tgH%2BZ0hoICgGSJDJFQf1xDYcR2VHex4gV%2BX4gq%2FrWLX5hxuGN4nFAPQmRi7J7bULo2U1jv%2F3aFVHVdnApY9Wc%2FYvm1MuZF3UYa1%2B58A4oBpjGLLPZq4UJnszx8BCj2JGDIuP5NoG0TIbPeJGgGjGcQKQe6qKHmXfjFHIUqn2ONXsJkapgBONpjesdCivoFRzTEc7A7EloQXIYo45yMCC5qCjDfIiBDK4euB6BkahzCjrVR45x9qwJGrMPoyolIkiXczceT6VkNtm07JkT5UR3%2FWV%2BQKFM6a7ulFBztLRqT5qIAVvsOMpLzEIph6vZ3oIdLHIncGzoE8p5CcxSkIHmb1xwjTtAdMiwPneuPAgTNgBf0zYrOjhseHiDkI0w2YKhSfrV9mocCufNihXYpjJ8OnzXK%2Bg7XO3ug0JYqw%2FVLVESbhCOHIaKl3TgqHG6sD2Hl495oCM%2F1L5NdYtOWmnPY25WNCuclKV%2FrQRX5zQP2u5uiCTtxRqz9Z205mlwrl86NgssrEPSd3XHZjgQEAPIljOnNvUyS8BhenC71rSZ25eQPp6pcGFtUMZfhlPmQ78g2OfZX8zM15jkMIeNtL0GOqUBCo0us%2F7D5zh74zNxFZi7vgBEdCuZMMd1ZCp6V9NlRCbkJ1ZZYFtkt%2FVwqVxN5xLWDxJxIfJcFHniqWF2GEePcfLjdO%2FXR19eAwlz5uj%2BAMNYlzEUbuOFdas7PNkEn2kqqlMtSc4NCUD5N3hhMWB4iwIIbQgJUxKNhIEhoFlIUH4rKHBngHKc0Ergwn3ACcHAYISlnbhApZoxTCbyZtzGrwnPzJEf&X-Amz-Signature=4220145756a04cdaf6564295aba4a39952e0e7d44bb46bc390607a6d357fc5f7&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z35BL5LA%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T212211Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEN3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDIUcUObUppX0tg7nGw8SZdhUFXFKPeo%2FM7UTtVjzmdPwIgX9ZYpRWs4XLy1LTNuV1ibDnMtjEDCLoiq%2FIvT%2FBslBAqiAQI9v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDB4ycSBXX8CfkRIaaircA8%2FkzC64k1aUaWRaQ7NhQhWbwqVUoam2ojzjhkr9LGTysD2tgH%2BZ0hoICgGSJDJFQf1xDYcR2VHex4gV%2BX4gq%2FrWLX5hxuGN4nFAPQmRi7J7bULo2U1jv%2F3aFVHVdnApY9Wc%2FYvm1MuZF3UYa1%2B58A4oBpjGLLPZq4UJnszx8BCj2JGDIuP5NoG0TIbPeJGgGjGcQKQe6qKHmXfjFHIUqn2ONXsJkapgBONpjesdCivoFRzTEc7A7EloQXIYo45yMCC5qCjDfIiBDK4euB6BkahzCjrVR45x9qwJGrMPoyolIkiXczceT6VkNtm07JkT5UR3%2FWV%2BQKFM6a7ulFBztLRqT5qIAVvsOMpLzEIph6vZ3oIdLHIncGzoE8p5CcxSkIHmb1xwjTtAdMiwPneuPAgTNgBf0zYrOjhseHiDkI0w2YKhSfrV9mocCufNihXYpjJ8OnzXK%2Bg7XO3ug0JYqw%2FVLVESbhCOHIaKl3TgqHG6sD2Hl495oCM%2F1L5NdYtOWmnPY25WNCuclKV%2FrQRX5zQP2u5uiCTtxRqz9Z205mlwrl86NgssrEPSd3XHZjgQEAPIljOnNvUyS8BhenC71rSZ25eQPp6pcGFtUMZfhlPmQ78g2OfZX8zM15jkMIeNtL0GOqUBCo0us%2F7D5zh74zNxFZi7vgBEdCuZMMd1ZCp6V9NlRCbkJ1ZZYFtkt%2FVwqVxN5xLWDxJxIfJcFHniqWF2GEePcfLjdO%2FXR19eAwlz5uj%2BAMNYlzEUbuOFdas7PNkEn2kqqlMtSc4NCUD5N3hhMWB4iwIIbQgJUxKNhIEhoFlIUH4rKHBngHKc0Ergwn3ACcHAYISlnbhApZoxTCbyZtzGrwnPzJEf&X-Amz-Signature=f90d6addb8aab8389aadef36ead9459b37ec4f27c6a0c3f838c17b3fdf89868b&X-Amz-SignedHeaders=host&x-id=GetObject)


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

