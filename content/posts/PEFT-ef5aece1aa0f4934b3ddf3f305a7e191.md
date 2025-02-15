---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466R4LXAOA5%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250215T141930Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEBsaCXVzLXdlc3QtMiJIMEYCIQDTPG8CfWMKFE73%2F2L93xZpzyTpz2YIM6e8XSBCf6YNbgIhA\
  PF%2BaiSm3E7xbHwq82jzod%2Fv%2FCDXQkvLx7fCs9GUGKxlKv8DCEQQABoMNjM3NDIzMTgzODA1\
  IgywNSBWl6a5lM390GQq3AMjKmckIoSby%2BLkdc4zHYYrtNo6rATydQw25L1K8CKJ8jIb7T%2B%2\
  Fk9rMw4EvIF4KW2zQV%2B6lhLGyMz5xAht%2Fd0vXfr50MFQq9DeL%2BBn4D0JfP9J%2F02G%2F2D\
  54BJYVlK7qSWMdomsEag31qQNJv2vwkVZTEla7c08jf%2B6hNVw11eaknDm8JvttmD1HcUE1le4lU\
  oA7X5QxUH8F8D9BJMIAqkMwzNuyqWwVtFNTcDK9VasKw%2FZGV9F0PaIgSpoBl1lfjZim2oc%2FjU\
  Yv93o0J71tXttetxTxDOlU9%2BA3p%2BDnSvQ42%2BiZYwF13rBSSUaAIs67496phBCA%2BGZ0ZMj\
  KgHZIQhXZWWgWJpkRCbHlkipQasstVP2m9xOqgtGd1LcMzJVIsvgkKIu9b8C%2F8WcXzRNQRy8igc\
  ZYlcW2%2Bb1WoJ1bw%2FfgnW1i6ZW1bsDhFqbpi6a1r3vncy%2B6ZAqYJvJyw6SoS9UDHaAXcwWgR\
  wbHCrql4eZr9354y7jLJwP7fLWibCdTsd3Y3BYqwNVz%2FP6sAuaEhNgNFogEnuHhSh837Y3Etpx0\
  tI1Xuwz6cNLuJsfLiMvR5Z8Kx5p%2BQqCFKekvDsn0jw52ElbZZp350WDgV%2FgfsNVLtA08CczBO\
  zLp1m0mFDDM7MG9BjqkAXu7n74EH8lorKh68MtJXnNecAJ1bnDL3Uw%2Bu9zFvsXb%2FTUjKCuNBo\
  g24EPPljaDGRffPKUepzyPwUAD4uJDVUo%2FZWYTM0UAWVbqjvn8Bweoo695QFuCvsFrzs82LznM1\
  qLE6GVWZ2QDR6uegSI4uBd%2F8Chbn6Rj54N7bP1YhjkBqGpe1D6P6FJZVd8yWV2oqPi7u7oemf5h\
  AifnpqWP%2FU%2BcGK36&X-Amz-Signature=840ddf034dab38d5fb984f75452b2b2476bf9853\
  ea132cade550f54d21e95bb1&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4663WQTUIWG%2F20250215%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250215T141820Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEBsaCXVzLXdlc3QtMiJHMEUCIQCCMSbyQFPgSLRxOktBMq7S9VqV1QA\
        z138EhWDJDPxcfwIgDtvxl79zcYW3MNMNWSCUNcbOJQhOBBfXBbKGvyBkw1Aq%2FwMIRBAA\
        Ggw2Mzc0MjMxODM4MDUiDE6BTUWvbZEwnqIvjCrcAyd3UJJ3773NHXUy8ZfeR4qJBQeFPuD\
        72l95iflHwrG4YRyvdlhEpSsN4QVb6qDYi18xQLlxpEepdOR9TPZkFU4BzQdYuZylI1Qiij\
        wgJAIOW%2FnazSLjmX0IOnh08JYdhvVp54fKmTv304F2N2Gis7eSmdw0kG9tnBlEEhIA8fQ\
        ZJVEFeCs2cQqxJBALUK%2B%2FcfgHZLhl042UFVR%2BQ1vh0K5JJ3QxhUwAdaWRq31Ke0W2\
        XQ%2F68nplM1uOlAtl4F4yN3U%2BoC0xcAnEe7AdlVC9jX4RLX12nGGFCVA6jSp7ftFmsP%\
        2B150EYyU891vme3Oxetz0RSvcjlc6xx2MfXair3Q7MZevwyoHFlnNd%2FIOeclErKSen8N\
        nsAP%2FX7MNDT%2FxChnBMHl%2FQU9l87ZvtWHgtMmL08MuO4d5t7YeZJmPvRgTqAUCqiLq\
        AKNv4n1kEfVEK%2Fpd%2BKTRbw%2BkspyL%2BJ3BKex5Co8CiLApSHXc91lLYbAfoarFQ19\
        %2Ff%2F%2BKJ5nwXU82gq%2FJ%2FXoFKbETzioFrRZLon2FtxjBTQCIlMi72ZLFHXmwQ10C\
        EjCQ%2F8eiw7v6Uz3jMzjiBYhKogCS%2FOL8zr5BHAARrHcn%2B2Sk%2BsybZJ2t%2B3Zis\
        AdyEDNd9f7F8pplsMJDtwb0GOqUBYQdz37l4Kipv4OFmmQvKloSeWrPnjd92wAWcSAgW50I\
        tTJgDhZir7Ap9FN8ad19zbihq8UQwGCIwDIqawJqpY9PAJHZsYp5ZDMrwK9bvF8Kdg3MXmh\
        yTixM%2F7Z6Ym%2BN2rZjXqh1wD1Mv1X8kCJfgpuh7zFq4WGyUrF6wnen9lzMvi5LVsR9aC\
        7LQohIUktghLGB1UrpxsqUFvZbQKnxIa5vRGUDo&X-Amz-Signature=6291b93589c4396\
        100658bbd24f6baf9342f64f89bf4679f8efb0e226bf54111&X-Amz-SignedHeaders=h\
        ost&x-id=GetObject"
      expiry_time: "2025-02-15T15:18:19.942Z"
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
UPDATE_TIME: "2025-02-15T14:19:36.795Z"
EXPIRY_TIME: "2025-02-15T15:19:27.732Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZHAPGJWU%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T141928Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEB0aCXVzLXdlc3QtMiJHMEUCIQCNf6HA7h0phOLzI6Uyu5wM9iPRvvZgaM9fo1YV7uTk%2FgIgY3JoVBojbiEwnlUb8oLJ7r2IR1OjhldC1qkq0njx7BEq%2FwMIRhAAGgw2Mzc0MjMxODM4MDUiDCeOJk0yFwXUrD0EUyrcA9mAnDkwkodgyxVcXHjsLW0FvFSAQ9Q9CqcRJVb%2BgG9XikQfLWrbrK%2FeJwOKfLCE5VXJf2Osxw3wqnALSb4NbYjAAaNb%2BujQ2X9Qs5UiHrX3u%2BujUUueX1wjSVSO1SsCi%2BKOtpgEbwTrONDhtlEVVpvoTUfTuSefAq%2F6MXva5dPio%2BawlVNdxWh9dxgdAj4QSzAht8t8Z9KsSPdhlhpS4yX6tmvi3qz8pLOeYI9I0CvnEUUXIGHoL7aFPk2xZSLl9r928kQgHJBqI6xtxvARZGiEUeL73Ab4S9rhL8Qg62e3Qf6%2Fdmr1qCuH%2ByWH%2FVuvWGryVa%2F9q%2FdKU07cib%2FpjPvPL6JxswDaTiBJjoI9rnnCT%2BGoy8ybGzNat3baCTOdMyp2o%2F0yqjbHu4BEsmybenbMbKWFTSoqczOhgiSfUAUUZOv%2BzvMp2mYAV%2BER9F97Nue9WSYsV37Bu%2FOb3SEXQ7s3TCW%2BuLNMF0ME8UYSVvS8oymW4jGfVHxdzWsT%2BCPeltYVGVxoWULmWZRVi9v5gWiULBVFzoGL8n6kNWrwaeVAeBbLktOglDR6zAQxRkcskudneng2Wbvf4a7CoryBh8JmEb0CTA%2Fse%2Fcsuew5kFfTgmbcrR0HhgsjW3y1MKmZwr0GOqUBGgzY%2BDCPIXTHcfx4C2gQOxLBkSWNa%2B3IqVEoDWODQE36xa1%2BFTW4JLRjRAP07la5S8YC0BvL%2FrDhZkhcPRipks1lHeLytliom5MiBNp%2FBZYdz0q48R0avIquzW5pcE2k3MwbotgjYqt%2B7EZdM04nAb0bRcN6JtauP93kFAVpUWDmgHP23Ehm1JzXGYrsGsewMnV0Mt0%2BnkYLtbXuncxXD5V7z%2B%2BQ&X-Amz-Signature=c6d761b2cfefd750cfad057d59c18214fb8f9714bf3d4b49e54ffe4798bd32f8&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZHAPGJWU%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T141928Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEB0aCXVzLXdlc3QtMiJHMEUCIQCNf6HA7h0phOLzI6Uyu5wM9iPRvvZgaM9fo1YV7uTk%2FgIgY3JoVBojbiEwnlUb8oLJ7r2IR1OjhldC1qkq0njx7BEq%2FwMIRhAAGgw2Mzc0MjMxODM4MDUiDCeOJk0yFwXUrD0EUyrcA9mAnDkwkodgyxVcXHjsLW0FvFSAQ9Q9CqcRJVb%2BgG9XikQfLWrbrK%2FeJwOKfLCE5VXJf2Osxw3wqnALSb4NbYjAAaNb%2BujQ2X9Qs5UiHrX3u%2BujUUueX1wjSVSO1SsCi%2BKOtpgEbwTrONDhtlEVVpvoTUfTuSefAq%2F6MXva5dPio%2BawlVNdxWh9dxgdAj4QSzAht8t8Z9KsSPdhlhpS4yX6tmvi3qz8pLOeYI9I0CvnEUUXIGHoL7aFPk2xZSLl9r928kQgHJBqI6xtxvARZGiEUeL73Ab4S9rhL8Qg62e3Qf6%2Fdmr1qCuH%2ByWH%2FVuvWGryVa%2F9q%2FdKU07cib%2FpjPvPL6JxswDaTiBJjoI9rnnCT%2BGoy8ybGzNat3baCTOdMyp2o%2F0yqjbHu4BEsmybenbMbKWFTSoqczOhgiSfUAUUZOv%2BzvMp2mYAV%2BER9F97Nue9WSYsV37Bu%2FOb3SEXQ7s3TCW%2BuLNMF0ME8UYSVvS8oymW4jGfVHxdzWsT%2BCPeltYVGVxoWULmWZRVi9v5gWiULBVFzoGL8n6kNWrwaeVAeBbLktOglDR6zAQxRkcskudneng2Wbvf4a7CoryBh8JmEb0CTA%2Fse%2Fcsuew5kFfTgmbcrR0HhgsjW3y1MKmZwr0GOqUBGgzY%2BDCPIXTHcfx4C2gQOxLBkSWNa%2B3IqVEoDWODQE36xa1%2BFTW4JLRjRAP07la5S8YC0BvL%2FrDhZkhcPRipks1lHeLytliom5MiBNp%2FBZYdz0q48R0avIquzW5pcE2k3MwbotgjYqt%2B7EZdM04nAb0bRcN6JtauP93kFAVpUWDmgHP23Ehm1JzXGYrsGsewMnV0Mt0%2BnkYLtbXuncxXD5V7z%2B%2BQ&X-Amz-Signature=2f6895acaa62a4b8df05458b57b891b411de4885d1112ad9b71aae2b22528306&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZHAPGJWU%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T141928Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEB0aCXVzLXdlc3QtMiJHMEUCIQCNf6HA7h0phOLzI6Uyu5wM9iPRvvZgaM9fo1YV7uTk%2FgIgY3JoVBojbiEwnlUb8oLJ7r2IR1OjhldC1qkq0njx7BEq%2FwMIRhAAGgw2Mzc0MjMxODM4MDUiDCeOJk0yFwXUrD0EUyrcA9mAnDkwkodgyxVcXHjsLW0FvFSAQ9Q9CqcRJVb%2BgG9XikQfLWrbrK%2FeJwOKfLCE5VXJf2Osxw3wqnALSb4NbYjAAaNb%2BujQ2X9Qs5UiHrX3u%2BujUUueX1wjSVSO1SsCi%2BKOtpgEbwTrONDhtlEVVpvoTUfTuSefAq%2F6MXva5dPio%2BawlVNdxWh9dxgdAj4QSzAht8t8Z9KsSPdhlhpS4yX6tmvi3qz8pLOeYI9I0CvnEUUXIGHoL7aFPk2xZSLl9r928kQgHJBqI6xtxvARZGiEUeL73Ab4S9rhL8Qg62e3Qf6%2Fdmr1qCuH%2ByWH%2FVuvWGryVa%2F9q%2FdKU07cib%2FpjPvPL6JxswDaTiBJjoI9rnnCT%2BGoy8ybGzNat3baCTOdMyp2o%2F0yqjbHu4BEsmybenbMbKWFTSoqczOhgiSfUAUUZOv%2BzvMp2mYAV%2BER9F97Nue9WSYsV37Bu%2FOb3SEXQ7s3TCW%2BuLNMF0ME8UYSVvS8oymW4jGfVHxdzWsT%2BCPeltYVGVxoWULmWZRVi9v5gWiULBVFzoGL8n6kNWrwaeVAeBbLktOglDR6zAQxRkcskudneng2Wbvf4a7CoryBh8JmEb0CTA%2Fse%2Fcsuew5kFfTgmbcrR0HhgsjW3y1MKmZwr0GOqUBGgzY%2BDCPIXTHcfx4C2gQOxLBkSWNa%2B3IqVEoDWODQE36xa1%2BFTW4JLRjRAP07la5S8YC0BvL%2FrDhZkhcPRipks1lHeLytliom5MiBNp%2FBZYdz0q48R0avIquzW5pcE2k3MwbotgjYqt%2B7EZdM04nAb0bRcN6JtauP93kFAVpUWDmgHP23Ehm1JzXGYrsGsewMnV0Mt0%2BnkYLtbXuncxXD5V7z%2B%2BQ&X-Amz-Signature=911869877e4a0c9a9252754b6cf6d65dff106fd7fc0fe2d74fd5d2e8c7ed8bfe&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZHAPGJWU%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T141928Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEB0aCXVzLXdlc3QtMiJHMEUCIQCNf6HA7h0phOLzI6Uyu5wM9iPRvvZgaM9fo1YV7uTk%2FgIgY3JoVBojbiEwnlUb8oLJ7r2IR1OjhldC1qkq0njx7BEq%2FwMIRhAAGgw2Mzc0MjMxODM4MDUiDCeOJk0yFwXUrD0EUyrcA9mAnDkwkodgyxVcXHjsLW0FvFSAQ9Q9CqcRJVb%2BgG9XikQfLWrbrK%2FeJwOKfLCE5VXJf2Osxw3wqnALSb4NbYjAAaNb%2BujQ2X9Qs5UiHrX3u%2BujUUueX1wjSVSO1SsCi%2BKOtpgEbwTrONDhtlEVVpvoTUfTuSefAq%2F6MXva5dPio%2BawlVNdxWh9dxgdAj4QSzAht8t8Z9KsSPdhlhpS4yX6tmvi3qz8pLOeYI9I0CvnEUUXIGHoL7aFPk2xZSLl9r928kQgHJBqI6xtxvARZGiEUeL73Ab4S9rhL8Qg62e3Qf6%2Fdmr1qCuH%2ByWH%2FVuvWGryVa%2F9q%2FdKU07cib%2FpjPvPL6JxswDaTiBJjoI9rnnCT%2BGoy8ybGzNat3baCTOdMyp2o%2F0yqjbHu4BEsmybenbMbKWFTSoqczOhgiSfUAUUZOv%2BzvMp2mYAV%2BER9F97Nue9WSYsV37Bu%2FOb3SEXQ7s3TCW%2BuLNMF0ME8UYSVvS8oymW4jGfVHxdzWsT%2BCPeltYVGVxoWULmWZRVi9v5gWiULBVFzoGL8n6kNWrwaeVAeBbLktOglDR6zAQxRkcskudneng2Wbvf4a7CoryBh8JmEb0CTA%2Fse%2Fcsuew5kFfTgmbcrR0HhgsjW3y1MKmZwr0GOqUBGgzY%2BDCPIXTHcfx4C2gQOxLBkSWNa%2B3IqVEoDWODQE36xa1%2BFTW4JLRjRAP07la5S8YC0BvL%2FrDhZkhcPRipks1lHeLytliom5MiBNp%2FBZYdz0q48R0avIquzW5pcE2k3MwbotgjYqt%2B7EZdM04nAb0bRcN6JtauP93kFAVpUWDmgHP23Ehm1JzXGYrsGsewMnV0Mt0%2BnkYLtbXuncxXD5V7z%2B%2BQ&X-Amz-Signature=47306691e9269bc4aa849ef3ca7816a8cd96744e1b08caaab8fb786624d13ca9&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZHAPGJWU%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T141928Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEB0aCXVzLXdlc3QtMiJHMEUCIQCNf6HA7h0phOLzI6Uyu5wM9iPRvvZgaM9fo1YV7uTk%2FgIgY3JoVBojbiEwnlUb8oLJ7r2IR1OjhldC1qkq0njx7BEq%2FwMIRhAAGgw2Mzc0MjMxODM4MDUiDCeOJk0yFwXUrD0EUyrcA9mAnDkwkodgyxVcXHjsLW0FvFSAQ9Q9CqcRJVb%2BgG9XikQfLWrbrK%2FeJwOKfLCE5VXJf2Osxw3wqnALSb4NbYjAAaNb%2BujQ2X9Qs5UiHrX3u%2BujUUueX1wjSVSO1SsCi%2BKOtpgEbwTrONDhtlEVVpvoTUfTuSefAq%2F6MXva5dPio%2BawlVNdxWh9dxgdAj4QSzAht8t8Z9KsSPdhlhpS4yX6tmvi3qz8pLOeYI9I0CvnEUUXIGHoL7aFPk2xZSLl9r928kQgHJBqI6xtxvARZGiEUeL73Ab4S9rhL8Qg62e3Qf6%2Fdmr1qCuH%2ByWH%2FVuvWGryVa%2F9q%2FdKU07cib%2FpjPvPL6JxswDaTiBJjoI9rnnCT%2BGoy8ybGzNat3baCTOdMyp2o%2F0yqjbHu4BEsmybenbMbKWFTSoqczOhgiSfUAUUZOv%2BzvMp2mYAV%2BER9F97Nue9WSYsV37Bu%2FOb3SEXQ7s3TCW%2BuLNMF0ME8UYSVvS8oymW4jGfVHxdzWsT%2BCPeltYVGVxoWULmWZRVi9v5gWiULBVFzoGL8n6kNWrwaeVAeBbLktOglDR6zAQxRkcskudneng2Wbvf4a7CoryBh8JmEb0CTA%2Fse%2Fcsuew5kFfTgmbcrR0HhgsjW3y1MKmZwr0GOqUBGgzY%2BDCPIXTHcfx4C2gQOxLBkSWNa%2B3IqVEoDWODQE36xa1%2BFTW4JLRjRAP07la5S8YC0BvL%2FrDhZkhcPRipks1lHeLytliom5MiBNp%2FBZYdz0q48R0avIquzW5pcE2k3MwbotgjYqt%2B7EZdM04nAb0bRcN6JtauP93kFAVpUWDmgHP23Ehm1JzXGYrsGsewMnV0Mt0%2BnkYLtbXuncxXD5V7z%2B%2BQ&X-Amz-Signature=190e39427bd6a713459c299c4473d0d80b9286717ea2ef8b7edcee354ee93e58&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZSQVZTUB%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T141928Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBsaCXVzLXdlc3QtMiJHMEUCIBRQfh%2Fl6n2NGwxoWGPMg7561jlx6lMEiOcDgCbdTTbcAiEAm9cx1hmRgQ2ddfojHGENiKyzBKwcCW4wmhKUw4K87Ggq%2FwMIRBAAGgw2Mzc0MjMxODM4MDUiDCxZxRU7%2BA1aNuHSMCrcA3IsEr%2BiFgxUuEYXXvc%2B2A8BLh9zcePNjei%2FQ0eHf%2Bdexws2mMvt8ccK6%2BdzCBoc5%2BeXZUwF0kYZCu4vfyNVudOpPIydNrsTBqElI3ojjWu%2BnpUMu5%2F5DJUjZv3A7nwXVcjtnrXibewFyfV6D%2BttKtnWadZI6YHiACipIUxeEuoSvs5x0PGXjyUZGTFCHHC3m94bbssTenm7TONrs%2F1KMgtMU6Ll68b4wM2Jk8LbzeR9Rf7gfnJRK5f60uqnLCVZvrtVJdGZPBloZRYYJ%2F4ii8%2FZwfYpv8SL6hmB9gQrkFrjXk4SCYSzgbfUMbB%2BXj38lttz1x76rhVqSGy%2Byfkw%2B79JIVgJDFST0%2B0T8z3y0HMV%2Fn8w0K0oA6pq6KxPriOyibpC3zu12%2BL6etbYTFtwGWC6Gfjmb1jUdqCbxpWegDU7CDFAYYPqYN9CBsGqXwqBbwJg1lNf1pvCb%2BbXgRd%2Fi%2F2vK%2FQzBrkluNxWR26ON7zYZjekJai0EJThL0N%2FDnW2OPDOgGc8N8hhIvDY3skfqVbPrunu%2FfgJNRDraxKmYm3bjJJqF7kb1PLbNTUmAqGx0kZHKeptmyCPDQhixUJXZnY7JULzMXI4DgwKojD%2BeGCFVdh42wOnQTJFa%2Fy5MMHswb0GOqUBb6khj03nhqXcJ2DF72ywb744%2B1PORX21okXshd66beApqdp2YVM%2BZkDnUytSAbCuJoixdx8NQ4fVzKhrIDF0xmjHSgOKrKHW33qJsKJyviIAoyUsrKX8Ou3QnzcMsHHEkxJnJwyht%2Bz9FLKmDjFMVNHnUyDTxJoovbeEQZhSN%2B2x2IWtrEmrhfxvO2MXoDtlD5BVeH4YEsCCcZbDUyv0onZaOQou&X-Amz-Signature=ea99f867b9861d09a791f86671b3c52aeecaabcbdf148d1448a0c216b39cda37&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UDAS4ODR%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T141929Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBsaCXVzLXdlc3QtMiJGMEQCIFInwQ22vP1MFSDAxMSYPFOkpjdq8KmgRixBuGsXlWngAiByagYTE7xng%2Fh0L53Wi99FbBu%2FPIrq6VNbU7wWaPOqKir%2FAwhEEAAaDDYzNzQyMzE4MzgwNSIMS%2F%2FC%2Br4N1VjiG%2BdMKtwDMfrs2LUIIXlbHg2GONXAHBlh9EaDDPv7rdWMZeNkDHgbvmTqLyC683AhOBBVM%2FuWmA5qwsIj0COD%2BXQHN6Ba7OxpzcQFOntLbW1XZkcQ7Gtebm41Z6o8bAUS6%2FMICgz8xJ1PPJ56gwmJbBtlEqZkIM9gnIoeLcvHl7eaoiN0zkpHzOqU6t7IvvgvhPz8pPpIfrDZZibXhSWT21zYkWoeo5MT1WD%2F6wMeMpCsb%2FP4QQdiKfKMaRx1zIorjyuK3H260K1%2FWWwnNB5iPIw1pCkVF5SzybjmeoiDKbv7UIip1fhpKEu%2FJ3dwNUfPu4ijWXZbDFndehoREuLjq7L97EFNMsE2rH5vY54wVpJfblNMnFHNJPjh0M5swznP4Dou%2FxupY4itq9lqLLRFBe5bFzR4jQ2xkvgMLQpVnxvw5okHxY3rdbLqo9W7m4MD9a13lr9DXghiMngHmWM0FBPBFOK5fpYS72g3x8vIqkug7xS%2F%2B7N1cWMWmZcXD6OUMRXkoTBl9vouljTAAwU0KoANfa0T561uO1jT%2Fw0HJ%2BBlimrwFFtBVf40JDdg%2FJYyG8fmiURkEFDARPxz7z1Zr2Gp6CnqcdFAY1KistC2SH8CLO4FzVTnCf4cugmvDf2Jc2sw1%2BzBvQY6pgGz39Ywkp0f1msuZrcKzeSTdjH%2FTVQVh5Y78m4M5rXnaGoi3d%2B2rwlMcTySBaVHHUHVQ7uQ%2BZ9ibX7D4hNpwMIiBVf8iNNz%2F8%2FIGpYANHyQcNYQeDZ8%2Ft25ej%2FWGjS4bO%2BAcUo62u73pQ9Kn4ux4JV8QMZr4g0EsDdM3bMQimNZVJ0g7s3lDNq%2BaHkvZsQD0GHmNPqZmDO7mZ38m%2FfBVLc4xcXPv8f%2B&X-Amz-Signature=cf338a3843ced49e092453bc67310d72783979bd7bd59aa8fb6a2d9ec69f737f&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZHAPGJWU%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T141928Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEB0aCXVzLXdlc3QtMiJHMEUCIQCNf6HA7h0phOLzI6Uyu5wM9iPRvvZgaM9fo1YV7uTk%2FgIgY3JoVBojbiEwnlUb8oLJ7r2IR1OjhldC1qkq0njx7BEq%2FwMIRhAAGgw2Mzc0MjMxODM4MDUiDCeOJk0yFwXUrD0EUyrcA9mAnDkwkodgyxVcXHjsLW0FvFSAQ9Q9CqcRJVb%2BgG9XikQfLWrbrK%2FeJwOKfLCE5VXJf2Osxw3wqnALSb4NbYjAAaNb%2BujQ2X9Qs5UiHrX3u%2BujUUueX1wjSVSO1SsCi%2BKOtpgEbwTrONDhtlEVVpvoTUfTuSefAq%2F6MXva5dPio%2BawlVNdxWh9dxgdAj4QSzAht8t8Z9KsSPdhlhpS4yX6tmvi3qz8pLOeYI9I0CvnEUUXIGHoL7aFPk2xZSLl9r928kQgHJBqI6xtxvARZGiEUeL73Ab4S9rhL8Qg62e3Qf6%2Fdmr1qCuH%2ByWH%2FVuvWGryVa%2F9q%2FdKU07cib%2FpjPvPL6JxswDaTiBJjoI9rnnCT%2BGoy8ybGzNat3baCTOdMyp2o%2F0yqjbHu4BEsmybenbMbKWFTSoqczOhgiSfUAUUZOv%2BzvMp2mYAV%2BER9F97Nue9WSYsV37Bu%2FOb3SEXQ7s3TCW%2BuLNMF0ME8UYSVvS8oymW4jGfVHxdzWsT%2BCPeltYVGVxoWULmWZRVi9v5gWiULBVFzoGL8n6kNWrwaeVAeBbLktOglDR6zAQxRkcskudneng2Wbvf4a7CoryBh8JmEb0CTA%2Fse%2Fcsuew5kFfTgmbcrR0HhgsjW3y1MKmZwr0GOqUBGgzY%2BDCPIXTHcfx4C2gQOxLBkSWNa%2B3IqVEoDWODQE36xa1%2BFTW4JLRjRAP07la5S8YC0BvL%2FrDhZkhcPRipks1lHeLytliom5MiBNp%2FBZYdz0q48R0avIquzW5pcE2k3MwbotgjYqt%2B7EZdM04nAb0bRcN6JtauP93kFAVpUWDmgHP23Ehm1JzXGYrsGsewMnV0Mt0%2BnkYLtbXuncxXD5V7z%2B%2BQ&X-Amz-Signature=06bc80a22282c946336b7bb3ff70aab0b1624bc25151b810dfb7b4f7d4223b0f&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZHAPGJWU%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T141928Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEB0aCXVzLXdlc3QtMiJHMEUCIQCNf6HA7h0phOLzI6Uyu5wM9iPRvvZgaM9fo1YV7uTk%2FgIgY3JoVBojbiEwnlUb8oLJ7r2IR1OjhldC1qkq0njx7BEq%2FwMIRhAAGgw2Mzc0MjMxODM4MDUiDCeOJk0yFwXUrD0EUyrcA9mAnDkwkodgyxVcXHjsLW0FvFSAQ9Q9CqcRJVb%2BgG9XikQfLWrbrK%2FeJwOKfLCE5VXJf2Osxw3wqnALSb4NbYjAAaNb%2BujQ2X9Qs5UiHrX3u%2BujUUueX1wjSVSO1SsCi%2BKOtpgEbwTrONDhtlEVVpvoTUfTuSefAq%2F6MXva5dPio%2BawlVNdxWh9dxgdAj4QSzAht8t8Z9KsSPdhlhpS4yX6tmvi3qz8pLOeYI9I0CvnEUUXIGHoL7aFPk2xZSLl9r928kQgHJBqI6xtxvARZGiEUeL73Ab4S9rhL8Qg62e3Qf6%2Fdmr1qCuH%2ByWH%2FVuvWGryVa%2F9q%2FdKU07cib%2FpjPvPL6JxswDaTiBJjoI9rnnCT%2BGoy8ybGzNat3baCTOdMyp2o%2F0yqjbHu4BEsmybenbMbKWFTSoqczOhgiSfUAUUZOv%2BzvMp2mYAV%2BER9F97Nue9WSYsV37Bu%2FOb3SEXQ7s3TCW%2BuLNMF0ME8UYSVvS8oymW4jGfVHxdzWsT%2BCPeltYVGVxoWULmWZRVi9v5gWiULBVFzoGL8n6kNWrwaeVAeBbLktOglDR6zAQxRkcskudneng2Wbvf4a7CoryBh8JmEb0CTA%2Fse%2Fcsuew5kFfTgmbcrR0HhgsjW3y1MKmZwr0GOqUBGgzY%2BDCPIXTHcfx4C2gQOxLBkSWNa%2B3IqVEoDWODQE36xa1%2BFTW4JLRjRAP07la5S8YC0BvL%2FrDhZkhcPRipks1lHeLytliom5MiBNp%2FBZYdz0q48R0avIquzW5pcE2k3MwbotgjYqt%2B7EZdM04nAb0bRcN6JtauP93kFAVpUWDmgHP23Ehm1JzXGYrsGsewMnV0Mt0%2BnkYLtbXuncxXD5V7z%2B%2BQ&X-Amz-Signature=fee0048f0aec5a38ee582979da2f840c7bc5a4e8ffb02c1ca40861c7c4775d46&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZHAPGJWU%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T141928Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEB0aCXVzLXdlc3QtMiJHMEUCIQCNf6HA7h0phOLzI6Uyu5wM9iPRvvZgaM9fo1YV7uTk%2FgIgY3JoVBojbiEwnlUb8oLJ7r2IR1OjhldC1qkq0njx7BEq%2FwMIRhAAGgw2Mzc0MjMxODM4MDUiDCeOJk0yFwXUrD0EUyrcA9mAnDkwkodgyxVcXHjsLW0FvFSAQ9Q9CqcRJVb%2BgG9XikQfLWrbrK%2FeJwOKfLCE5VXJf2Osxw3wqnALSb4NbYjAAaNb%2BujQ2X9Qs5UiHrX3u%2BujUUueX1wjSVSO1SsCi%2BKOtpgEbwTrONDhtlEVVpvoTUfTuSefAq%2F6MXva5dPio%2BawlVNdxWh9dxgdAj4QSzAht8t8Z9KsSPdhlhpS4yX6tmvi3qz8pLOeYI9I0CvnEUUXIGHoL7aFPk2xZSLl9r928kQgHJBqI6xtxvARZGiEUeL73Ab4S9rhL8Qg62e3Qf6%2Fdmr1qCuH%2ByWH%2FVuvWGryVa%2F9q%2FdKU07cib%2FpjPvPL6JxswDaTiBJjoI9rnnCT%2BGoy8ybGzNat3baCTOdMyp2o%2F0yqjbHu4BEsmybenbMbKWFTSoqczOhgiSfUAUUZOv%2BzvMp2mYAV%2BER9F97Nue9WSYsV37Bu%2FOb3SEXQ7s3TCW%2BuLNMF0ME8UYSVvS8oymW4jGfVHxdzWsT%2BCPeltYVGVxoWULmWZRVi9v5gWiULBVFzoGL8n6kNWrwaeVAeBbLktOglDR6zAQxRkcskudneng2Wbvf4a7CoryBh8JmEb0CTA%2Fse%2Fcsuew5kFfTgmbcrR0HhgsjW3y1MKmZwr0GOqUBGgzY%2BDCPIXTHcfx4C2gQOxLBkSWNa%2B3IqVEoDWODQE36xa1%2BFTW4JLRjRAP07la5S8YC0BvL%2FrDhZkhcPRipks1lHeLytliom5MiBNp%2FBZYdz0q48R0avIquzW5pcE2k3MwbotgjYqt%2B7EZdM04nAb0bRcN6JtauP93kFAVpUWDmgHP23Ehm1JzXGYrsGsewMnV0Mt0%2BnkYLtbXuncxXD5V7z%2B%2BQ&X-Amz-Signature=4198272a9540c8be5395ae6624506817906af1edc9c3509153f627cd38481e91&X-Amz-SignedHeaders=host&x-id=GetObject)


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

