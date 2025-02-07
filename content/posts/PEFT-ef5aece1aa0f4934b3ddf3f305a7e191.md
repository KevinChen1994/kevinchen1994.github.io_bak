---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466RTFMIHD4%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250207T063254Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEFYaCXVzLXdlc3QtMiJIMEYCIQCcvmof0RsnEutvCm09tMlvuDj%2B3zPrku1RNImRVzrlzQIhA\
  PF8aM9AEkgt9uYVIJCVYNDBC%2BpOnd%2FYjV1%2F11qJKAG7Kv8DCG8QABoMNjM3NDIzMTgzODA1\
  IgyO0wAbz9ke5qg8D6oq3AOdLY3zfehy3%2FVbclSq%2B%2FtrrlQac49IOVV5iV9VUFMpiox7j6C\
  VouNtuEMeHYdKWvyEqPskGPE2lBxJjBMbMzuCQ2Cp2kQQuRbFxYl5w3y3vBj9cEJFmEe%2BNePF%2\
  Fy%2B8tj7cCPheQTuCn0789yXovW%2BhmWARwbwJ%2BNQLuB9oNVKfmS5r%2FvhLocC6ws1NHgyv2\
  SyYVZePztXNCo4rUwsfqyy9XBWd7C%2F6uXtSlxM%2BhctgAi8Ezsn2YDvMLRc1Jfy1Gvt%2BUyM4\
  xpuKtarG86wAYDqVo1eScQxXtU0wis9qZJHn6YTU6WxiO%2F2NVRTy7vaACAVfLrJX3KJ39RJVM74\
  78bfEyR%2F0yBlwn50%2Fogf7It8KAipTuB5UCIS2%2F0TcpDrXh12QX4gGRYi0gmGGpOAiKrz84b\
  %2FdbMtU%2Byq7EQaDPfYvBAto0A3BlMx1%2ByUfomdDlLVBN6a%2BwPEaLm%2FbKYlhXFV0ohuck\
  vv%2BRjOqk1FEyyMoXbqridws57NwpGWxBvcTjFeEe1MpZ7kIEc52HT2wn%2Bm3u6JoWOfmBh9Diw\
  T6vFA1ApZR0GhgCzUbcMFkx09gjmFE1xEh282fKD41upAznJabyjDuC8%2BfDPXaOgT8W7QbcMQN6\
  6PAAxxQ5oSUEDCjwZa9BjqkAePxFubiQw%2FGfmv%2BKVg%2B61kbDah6yqc2kutR1e6a1YXKr1tT\
  4Bs6Ik8pv8c3vP6xGK05yuj0Oz5M%2F5CiVMbA5dq6XRDodKDSB7p0CCnh93SSpR4xkjIv2eNuwyP\
  wWk1KKvwAbqRJRPaC7eEm4GDz8WhQLiKjJsjE3%2BWaCt8atNVNJk5mJ%2FmhjnhLv%2FliF1%2Fk\
  wEE8409fDdgV2LHdUBB7igFoyRb6&X-Amz-Signature=d93ef374654d602a9f60799db8c23498\
  8d10c6b118bd0dfa2007d33854190af9&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4665MAXJEJI%2F20250207%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250207T063136Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEFYaCXVzLXdlc3QtMiJHMEUCIQDUicGIbnhmS9YRvI9oDqmlAf7eNkM\
        %2Bh1akcoGRrfZxAQIgJsCX%2FknA3aZdM9XUs8wvj%2FbQ4y1n2RMiZOp%2FK0wSN1Mq%2\
        FwMIbxAAGgw2Mzc0MjMxODM4MDUiDPIVwnICdcl8SdSS1ircAxicXFsGmXVoDUeljruZveF\
        DtBsWSjzzJxlEiZrsXjca0nmgSZD6errd5%2Fm%2BRSJgKaWyY1Cjc%2FdMccKLjt71sIxd\
        3%2F7dKxKTGi7ob6lwHpAKoyAdU2RBgp3kPTY%2B9t2Zd%2Fm49vN3uF%2B2GSilziOUhjU\
        P9u5ohlfiOplsIOg1%2Fmil7GW45s9H1IEdEoxQi7FxTNJTZe5aXyb68SV0ZOWIWukB80D8\
        0JuczCPofkDB8el6VTR828O9Sa1my%2BFgBm2jIz7r7Qn3d8UbeWqI1kZvupLjWB2Rsziuj\
        zSmMoLtOBr6xuIcm9gUWSe%2BpM5dqIZ8GtrgiuNlsMMghNoOfhBqPimoisORYm2jg%2Fug\
        uRJOYXlZm7MlfPHXihUuI%2FoGhtsFgDU%2BEZQnKsZNFIoaMYfkrACK2wqAaXlnjHLdNSK\
        3sxWXlLOAaR7LV6Q9S4CutcmaoqDiECy6gxr8xpDyQ2p09Tnk45mOWRsB2rxiHept0mnGyD\
        YampXEIUsLZXpe7LWTnYEYtEsd4r%2FPw1HdHWp79NEx8V4AfyGzZ9xXx%2Bz91VeH7IZLj\
        66CY%2Bz%2F1AzHfu2wqJ4b6FKoCDR%2BF%2FOmMdII0Zimuq39gHJR8Z152nlHswayPNP%\
        2B3Z8Kzdky8A2KMKLBlr0GOqUBAxlhKR09duA3t5mW6WLi%2BXoHzxLi0Keh3elJVkeuS4k\
        oH%2F9psoWkfGsdbr0J97oUK1%2B6i0m3iHBYu6VwFt1whRGsnl86XzvudpHCaez75smGpe\
        bR%2F56rInLgA26eW1lncZ0kDJXInbl6FwsReKkZgQro%2BkC72TiWv5L9FQdtHLmIriMlj\
        DxpK3L8I%2FEnO8y1%2F91KcvwSeOoqGTF0fxNRhtTHRuUu&X-Amz-Signature=a1c6c40\
        795acc6e1c3206c78dfb80c6ccba02531090b3d883eb94421e85aca93&X-Amz-SignedH\
        eaders=host&x-id=GetObject"
      expiry_time: "2025-02-07T07:31:36.660Z"
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
UPDATE_TIME: "2025-02-07T06:33:00.338Z"
EXPIRY_TIME: "2025-02-07T07:32:50.886Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46636HWACIS%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T063251Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFYaCXVzLXdlc3QtMiJGMEQCIFMzXmatBvVAneg9bMenh8ayR1bSxxAC8J%2BeqkkLWHlXAiB12BuMTJLprhRGIA%2FiaqOx9mHG9Q%2BvUBeciep%2ByPaPhir%2FAwhvEAAaDDYzNzQyMzE4MzgwNSIM8iBFS5hnynuBRE%2BAKtwDm4yigirgtQ3JdSRjkyUUvlgUFLGzdDbYapxts8sry%2BUK8wLZqGzg9j0qTQmXN40XZDiDAnte6XcLzfCav4WP7f1lnrRY%2F1jgaIMNZtYLFsf4YjZQCPBCWVGx1MsFLkLcJZ9lSj%2FkbyPJdEiFMZWcLDPTtCdHM5ga2AlLieI8xYGN%2BZhroyOrVkAnKRnjOUHMLZqnIEZrSDq07tgXsQz5z67oQB3Q0jEouC5sCxQFEDrSzWqBOkPNG04s1D92UcVmPw91XFVUC6FQ5GyIhA2A0IbhQTRiUEW1riukfJAS7a2GUXyTFqvdPjxA4tH0WLA%2Fr6K9T5ezSAASUhPOI0l%2BGXwSUYcAwfUjKD1CG9Xh9S8b4H3FvBmp034lVsFtJbz0VgcbQjV%2F0fkNH467TFQSWItZYQUstV8Bc34i92ThziZKNTqy%2F5WbcHL%2BqLXk0Q74y8lI%2BbSyCxawavm8nZ8XTnN3zqXqzjJTb9XitVpglXpxN5lOLGm9PzIWHIjXz8Doc9Gh0pjM5JqywYolg6a6z1SZ0uitirYydJJLdBp8%2FCT6PlrtfH91A270QJb5ZEY7dvL3t9NlJK1IL9LcRc3et0Gv5StJWDpRbbilSiqtzD50V8B%2BMTjrmd01H70wmcGWvQY6pgEVr6upBb%2BurXdP7IUSij6Tr2MUxPNQxjyTpqfp9%2FM9f9K4qIk1obOz8ckHWyFlKqGZsjOna08g8DBZI1gGkwJZAtcO%2BDUqq0uMPsy5ztEBggL7JkSpNlomhw3R23BH1CNPy%2BO9RuEjsT%2BTJxxXMwzpxfbaC6MveNLqF%2FRZ9iT2wkuXVXg%2B6H8R6cdpepYm6lAfWfeVkLpR8puIixm77m%2FI9VL6Gl13&X-Amz-Signature=2c587de2f8b08820e4a962cfa5cd437370eb6ccc7dcdba305bb89ada4ecca30c&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46636HWACIS%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T063251Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFYaCXVzLXdlc3QtMiJGMEQCIFMzXmatBvVAneg9bMenh8ayR1bSxxAC8J%2BeqkkLWHlXAiB12BuMTJLprhRGIA%2FiaqOx9mHG9Q%2BvUBeciep%2ByPaPhir%2FAwhvEAAaDDYzNzQyMzE4MzgwNSIM8iBFS5hnynuBRE%2BAKtwDm4yigirgtQ3JdSRjkyUUvlgUFLGzdDbYapxts8sry%2BUK8wLZqGzg9j0qTQmXN40XZDiDAnte6XcLzfCav4WP7f1lnrRY%2F1jgaIMNZtYLFsf4YjZQCPBCWVGx1MsFLkLcJZ9lSj%2FkbyPJdEiFMZWcLDPTtCdHM5ga2AlLieI8xYGN%2BZhroyOrVkAnKRnjOUHMLZqnIEZrSDq07tgXsQz5z67oQB3Q0jEouC5sCxQFEDrSzWqBOkPNG04s1D92UcVmPw91XFVUC6FQ5GyIhA2A0IbhQTRiUEW1riukfJAS7a2GUXyTFqvdPjxA4tH0WLA%2Fr6K9T5ezSAASUhPOI0l%2BGXwSUYcAwfUjKD1CG9Xh9S8b4H3FvBmp034lVsFtJbz0VgcbQjV%2F0fkNH467TFQSWItZYQUstV8Bc34i92ThziZKNTqy%2F5WbcHL%2BqLXk0Q74y8lI%2BbSyCxawavm8nZ8XTnN3zqXqzjJTb9XitVpglXpxN5lOLGm9PzIWHIjXz8Doc9Gh0pjM5JqywYolg6a6z1SZ0uitirYydJJLdBp8%2FCT6PlrtfH91A270QJb5ZEY7dvL3t9NlJK1IL9LcRc3et0Gv5StJWDpRbbilSiqtzD50V8B%2BMTjrmd01H70wmcGWvQY6pgEVr6upBb%2BurXdP7IUSij6Tr2MUxPNQxjyTpqfp9%2FM9f9K4qIk1obOz8ckHWyFlKqGZsjOna08g8DBZI1gGkwJZAtcO%2BDUqq0uMPsy5ztEBggL7JkSpNlomhw3R23BH1CNPy%2BO9RuEjsT%2BTJxxXMwzpxfbaC6MveNLqF%2FRZ9iT2wkuXVXg%2B6H8R6cdpepYm6lAfWfeVkLpR8puIixm77m%2FI9VL6Gl13&X-Amz-Signature=5faddfa23c51bc5f8b4f9b16c5c2fed6f81c2c177f5288cd8b8931a8773a7f98&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46636HWACIS%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T063251Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFYaCXVzLXdlc3QtMiJGMEQCIFMzXmatBvVAneg9bMenh8ayR1bSxxAC8J%2BeqkkLWHlXAiB12BuMTJLprhRGIA%2FiaqOx9mHG9Q%2BvUBeciep%2ByPaPhir%2FAwhvEAAaDDYzNzQyMzE4MzgwNSIM8iBFS5hnynuBRE%2BAKtwDm4yigirgtQ3JdSRjkyUUvlgUFLGzdDbYapxts8sry%2BUK8wLZqGzg9j0qTQmXN40XZDiDAnte6XcLzfCav4WP7f1lnrRY%2F1jgaIMNZtYLFsf4YjZQCPBCWVGx1MsFLkLcJZ9lSj%2FkbyPJdEiFMZWcLDPTtCdHM5ga2AlLieI8xYGN%2BZhroyOrVkAnKRnjOUHMLZqnIEZrSDq07tgXsQz5z67oQB3Q0jEouC5sCxQFEDrSzWqBOkPNG04s1D92UcVmPw91XFVUC6FQ5GyIhA2A0IbhQTRiUEW1riukfJAS7a2GUXyTFqvdPjxA4tH0WLA%2Fr6K9T5ezSAASUhPOI0l%2BGXwSUYcAwfUjKD1CG9Xh9S8b4H3FvBmp034lVsFtJbz0VgcbQjV%2F0fkNH467TFQSWItZYQUstV8Bc34i92ThziZKNTqy%2F5WbcHL%2BqLXk0Q74y8lI%2BbSyCxawavm8nZ8XTnN3zqXqzjJTb9XitVpglXpxN5lOLGm9PzIWHIjXz8Doc9Gh0pjM5JqywYolg6a6z1SZ0uitirYydJJLdBp8%2FCT6PlrtfH91A270QJb5ZEY7dvL3t9NlJK1IL9LcRc3et0Gv5StJWDpRbbilSiqtzD50V8B%2BMTjrmd01H70wmcGWvQY6pgEVr6upBb%2BurXdP7IUSij6Tr2MUxPNQxjyTpqfp9%2FM9f9K4qIk1obOz8ckHWyFlKqGZsjOna08g8DBZI1gGkwJZAtcO%2BDUqq0uMPsy5ztEBggL7JkSpNlomhw3R23BH1CNPy%2BO9RuEjsT%2BTJxxXMwzpxfbaC6MveNLqF%2FRZ9iT2wkuXVXg%2B6H8R6cdpepYm6lAfWfeVkLpR8puIixm77m%2FI9VL6Gl13&X-Amz-Signature=f22bbdad152bb08a72c66c88a8162bfa541e7feb150705bd9529afeccc236631&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46636HWACIS%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T063251Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFYaCXVzLXdlc3QtMiJGMEQCIFMzXmatBvVAneg9bMenh8ayR1bSxxAC8J%2BeqkkLWHlXAiB12BuMTJLprhRGIA%2FiaqOx9mHG9Q%2BvUBeciep%2ByPaPhir%2FAwhvEAAaDDYzNzQyMzE4MzgwNSIM8iBFS5hnynuBRE%2BAKtwDm4yigirgtQ3JdSRjkyUUvlgUFLGzdDbYapxts8sry%2BUK8wLZqGzg9j0qTQmXN40XZDiDAnte6XcLzfCav4WP7f1lnrRY%2F1jgaIMNZtYLFsf4YjZQCPBCWVGx1MsFLkLcJZ9lSj%2FkbyPJdEiFMZWcLDPTtCdHM5ga2AlLieI8xYGN%2BZhroyOrVkAnKRnjOUHMLZqnIEZrSDq07tgXsQz5z67oQB3Q0jEouC5sCxQFEDrSzWqBOkPNG04s1D92UcVmPw91XFVUC6FQ5GyIhA2A0IbhQTRiUEW1riukfJAS7a2GUXyTFqvdPjxA4tH0WLA%2Fr6K9T5ezSAASUhPOI0l%2BGXwSUYcAwfUjKD1CG9Xh9S8b4H3FvBmp034lVsFtJbz0VgcbQjV%2F0fkNH467TFQSWItZYQUstV8Bc34i92ThziZKNTqy%2F5WbcHL%2BqLXk0Q74y8lI%2BbSyCxawavm8nZ8XTnN3zqXqzjJTb9XitVpglXpxN5lOLGm9PzIWHIjXz8Doc9Gh0pjM5JqywYolg6a6z1SZ0uitirYydJJLdBp8%2FCT6PlrtfH91A270QJb5ZEY7dvL3t9NlJK1IL9LcRc3et0Gv5StJWDpRbbilSiqtzD50V8B%2BMTjrmd01H70wmcGWvQY6pgEVr6upBb%2BurXdP7IUSij6Tr2MUxPNQxjyTpqfp9%2FM9f9K4qIk1obOz8ckHWyFlKqGZsjOna08g8DBZI1gGkwJZAtcO%2BDUqq0uMPsy5ztEBggL7JkSpNlomhw3R23BH1CNPy%2BO9RuEjsT%2BTJxxXMwzpxfbaC6MveNLqF%2FRZ9iT2wkuXVXg%2B6H8R6cdpepYm6lAfWfeVkLpR8puIixm77m%2FI9VL6Gl13&X-Amz-Signature=f13d0097c7f4aeaf3d6feeef80d641dd6e123ed9524a26cee42e1f3948921507&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46636HWACIS%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T063251Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFYaCXVzLXdlc3QtMiJGMEQCIFMzXmatBvVAneg9bMenh8ayR1bSxxAC8J%2BeqkkLWHlXAiB12BuMTJLprhRGIA%2FiaqOx9mHG9Q%2BvUBeciep%2ByPaPhir%2FAwhvEAAaDDYzNzQyMzE4MzgwNSIM8iBFS5hnynuBRE%2BAKtwDm4yigirgtQ3JdSRjkyUUvlgUFLGzdDbYapxts8sry%2BUK8wLZqGzg9j0qTQmXN40XZDiDAnte6XcLzfCav4WP7f1lnrRY%2F1jgaIMNZtYLFsf4YjZQCPBCWVGx1MsFLkLcJZ9lSj%2FkbyPJdEiFMZWcLDPTtCdHM5ga2AlLieI8xYGN%2BZhroyOrVkAnKRnjOUHMLZqnIEZrSDq07tgXsQz5z67oQB3Q0jEouC5sCxQFEDrSzWqBOkPNG04s1D92UcVmPw91XFVUC6FQ5GyIhA2A0IbhQTRiUEW1riukfJAS7a2GUXyTFqvdPjxA4tH0WLA%2Fr6K9T5ezSAASUhPOI0l%2BGXwSUYcAwfUjKD1CG9Xh9S8b4H3FvBmp034lVsFtJbz0VgcbQjV%2F0fkNH467TFQSWItZYQUstV8Bc34i92ThziZKNTqy%2F5WbcHL%2BqLXk0Q74y8lI%2BbSyCxawavm8nZ8XTnN3zqXqzjJTb9XitVpglXpxN5lOLGm9PzIWHIjXz8Doc9Gh0pjM5JqywYolg6a6z1SZ0uitirYydJJLdBp8%2FCT6PlrtfH91A270QJb5ZEY7dvL3t9NlJK1IL9LcRc3et0Gv5StJWDpRbbilSiqtzD50V8B%2BMTjrmd01H70wmcGWvQY6pgEVr6upBb%2BurXdP7IUSij6Tr2MUxPNQxjyTpqfp9%2FM9f9K4qIk1obOz8ckHWyFlKqGZsjOna08g8DBZI1gGkwJZAtcO%2BDUqq0uMPsy5ztEBggL7JkSpNlomhw3R23BH1CNPy%2BO9RuEjsT%2BTJxxXMwzpxfbaC6MveNLqF%2FRZ9iT2wkuXVXg%2B6H8R6cdpepYm6lAfWfeVkLpR8puIixm77m%2FI9VL6Gl13&X-Amz-Signature=66910c6cfa00be6535e58fa5965aed216b544487e453ad2a0f4c08f05967c114&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RJCXS52S%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T063252Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFYaCXVzLXdlc3QtMiJHMEUCIHQGcDX0D82U1M6cLwkEW317vcHyXFnbvyFuOMdHn6oRAiEAuJIUw9IYi6Kv%2BtlCS9GqHuq9GYtaR0oU5uVWlRDWGCoq%2FwMIbxAAGgw2Mzc0MjMxODM4MDUiDFnQ%2FICUmtCimte2OircA0STid%2Fa9K13g0jOPQ%2BiRIDm4k%2Fy33%2BYxNujBNyPoF90%2FsEK5lR3avSl8TvSmvTNAYdQ5M1dFbcSX8CjYBKhuWEEHH0%2F1AQWjyL7UFWNOfeP%2F%2B4phTIPoOlkemGfHlfWcUY%2BKjdzUiJyBZkePoGibwDR2XAWaogN8O29bvrCiViTiY7EfieCEi2%2FnrHy72hU66%2BATavApJfKc066HDbyBw0FobGqukacscfKCHvLQ9Qv22zQG0Ye3O87oZXp2L1Pgc1b7es83VBzlXXclcVl3%2Byil3tw6FY16MxJiziSlx8jkcR%2FeCq5jJUj%2BWZuPBypQSWknbbOoK3R%2BATSw6RbbZck%2BxGNyAnyDZLhU5n4j0MhKq4WLOuvG3OT9jPDscA54zBr5KCj1Egt3kMnv0kcpW6fz6jVQ1DKeuPY6IsBeUY0xRXmjoCiMWi7Qn8ux%2FwrTa5LHJeP8kXiyQualV0OZ%2FYJAPoV8MS8ISa2vsoKIPBXWOxUW2vbrShwFHQEVshKnq29UoSvjV2oQVuQCdrmMaluK486FRuzTmSUn%2BawQgU%2FFZsuMUcvJbddKkcOf54LBnW2aOLPfNznWPEZfwy5VdpbIDr0jruXNPhMfWGpNbRJ%2B79OML%2BMFFLPzUSHMKLBlr0GOqUBjgvQ7n4f9qS19MdgyEdBDIUnO4TUeJk1T8PlPzPP0Dkz1rQsq4RsUy4bA0%2F5szxyulXIZflKU0K2A%2FGu7AppDSqDKqC5MfNUqHJL4y5g7VjWIFw1OzpRVP%2BzJBWqWgSf2P0dCDztocAXs7xgMA8RuM6u%2BMZIYdfD7tAw0h3zYM91n3WOqNlKSB3pbe88INUtCFlSDuDSW9Bd23WWte22nkB8H%2BmI&X-Amz-Signature=c98d1b9073c59b2b39966a2e253be379d574e027b32d0c96a20357fa399e5577&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QA656EBS%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T063254Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFYaCXVzLXdlc3QtMiJIMEYCIQCMg%2BRJJfU%2BriBVDBOuiedjsd3nSVsfNxhpn166uh31%2FAIhAP9Jkoy64jb62LSXKFPNDuPqd6UTp6BBJj55aJaobZXsKv8DCG8QABoMNjM3NDIzMTgzODA1IgwfPah%2FTboUkVVXtVMq3AN7z9sC6R4UIwQG1FfK5wOOLPM%2FvWwkv9oxnc9CtsFnJwmtXtWfL4mGtg7NVtNfkGgGzHY7VXaqJzv6nIJiMOCy9SLQFoV5NknPObBmvJ1RlsLoZiHrt6eIkf36uN%2FwFelaOlE2jL1tVjVmECqS6JGRObGKqw0Scsh5fh0qm1go0nnrypAmAHLZb57bq6tBM615IRx25uemSvCxTwR%2BZKYQSgCtVzuWpczDMq2Q7cFzXO47ktJUdCPNApITDGR8bsElVS6VqzDdsyN3SHM9h9SYpEcrdXdGVPEqdvaa1djHjq1tUJuTnXnlvZYNaJgeXLyyZNSaweN4lgXtUKWWuQhDJRB3lHMrWkYjJToxeKChETJIyFXVvK9b4syLH6ztHzQYryZPbmPA7epqAzVWZr%2F8czeSTPsgZa%2BfIdktbXhaZ0E8JNpRcV62RbVSK4RWu267BnUaN3nVkpheQe3F0p%2Fi%2Bg%2F1ZXBI2Hd42gPwSchP1B0mjjI4ffPwPxQvaVmBz199zuZv2XJ863kZB9J3xcdeyX%2BpB8YZyrjqLKbz2M3y96MaWZjmGta9aub6MTKMkfslpbWD7naxhoqEqCvXUXIFkl0rRDgsDa%2FcSIyGx8OtgwkM53IW2j6HUkW7zzCiwZa9BjqkAUuwrht6c%2F5yahhykWwsjmvl9V75uXHe7IoEDYAaEGAYPp7HQ9J141XoeNZGTVIk25n5Bg%2FTqV9XC6%2BxY5WyHuOt7ecA6eiRC1fJTwbNyKY1BfrSeTR3o%2FISzhZUljRKsAp125fVeeqj8H4K6s9mtPW%2BvZTpsf59JLAa5FVo8spkApQIcUB2VNqJh5%2F9bQfqfLIEVCmJYvGoec3bJd0vRRon%2FuNW&X-Amz-Signature=bc8f434da1c96a55164131e2363cbbb3b39796dbb99551e7d2eb087c250bfe34&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46636HWACIS%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T063252Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFYaCXVzLXdlc3QtMiJGMEQCIFMzXmatBvVAneg9bMenh8ayR1bSxxAC8J%2BeqkkLWHlXAiB12BuMTJLprhRGIA%2FiaqOx9mHG9Q%2BvUBeciep%2ByPaPhir%2FAwhvEAAaDDYzNzQyMzE4MzgwNSIM8iBFS5hnynuBRE%2BAKtwDm4yigirgtQ3JdSRjkyUUvlgUFLGzdDbYapxts8sry%2BUK8wLZqGzg9j0qTQmXN40XZDiDAnte6XcLzfCav4WP7f1lnrRY%2F1jgaIMNZtYLFsf4YjZQCPBCWVGx1MsFLkLcJZ9lSj%2FkbyPJdEiFMZWcLDPTtCdHM5ga2AlLieI8xYGN%2BZhroyOrVkAnKRnjOUHMLZqnIEZrSDq07tgXsQz5z67oQB3Q0jEouC5sCxQFEDrSzWqBOkPNG04s1D92UcVmPw91XFVUC6FQ5GyIhA2A0IbhQTRiUEW1riukfJAS7a2GUXyTFqvdPjxA4tH0WLA%2Fr6K9T5ezSAASUhPOI0l%2BGXwSUYcAwfUjKD1CG9Xh9S8b4H3FvBmp034lVsFtJbz0VgcbQjV%2F0fkNH467TFQSWItZYQUstV8Bc34i92ThziZKNTqy%2F5WbcHL%2BqLXk0Q74y8lI%2BbSyCxawavm8nZ8XTnN3zqXqzjJTb9XitVpglXpxN5lOLGm9PzIWHIjXz8Doc9Gh0pjM5JqywYolg6a6z1SZ0uitirYydJJLdBp8%2FCT6PlrtfH91A270QJb5ZEY7dvL3t9NlJK1IL9LcRc3et0Gv5StJWDpRbbilSiqtzD50V8B%2BMTjrmd01H70wmcGWvQY6pgEVr6upBb%2BurXdP7IUSij6Tr2MUxPNQxjyTpqfp9%2FM9f9K4qIk1obOz8ckHWyFlKqGZsjOna08g8DBZI1gGkwJZAtcO%2BDUqq0uMPsy5ztEBggL7JkSpNlomhw3R23BH1CNPy%2BO9RuEjsT%2BTJxxXMwzpxfbaC6MveNLqF%2FRZ9iT2wkuXVXg%2B6H8R6cdpepYm6lAfWfeVkLpR8puIixm77m%2FI9VL6Gl13&X-Amz-Signature=61b38245d353d7a644eb75e58ca73144e29e4daeea141b7303f667d4fbf4724d&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46636HWACIS%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T063252Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFYaCXVzLXdlc3QtMiJGMEQCIFMzXmatBvVAneg9bMenh8ayR1bSxxAC8J%2BeqkkLWHlXAiB12BuMTJLprhRGIA%2FiaqOx9mHG9Q%2BvUBeciep%2ByPaPhir%2FAwhvEAAaDDYzNzQyMzE4MzgwNSIM8iBFS5hnynuBRE%2BAKtwDm4yigirgtQ3JdSRjkyUUvlgUFLGzdDbYapxts8sry%2BUK8wLZqGzg9j0qTQmXN40XZDiDAnte6XcLzfCav4WP7f1lnrRY%2F1jgaIMNZtYLFsf4YjZQCPBCWVGx1MsFLkLcJZ9lSj%2FkbyPJdEiFMZWcLDPTtCdHM5ga2AlLieI8xYGN%2BZhroyOrVkAnKRnjOUHMLZqnIEZrSDq07tgXsQz5z67oQB3Q0jEouC5sCxQFEDrSzWqBOkPNG04s1D92UcVmPw91XFVUC6FQ5GyIhA2A0IbhQTRiUEW1riukfJAS7a2GUXyTFqvdPjxA4tH0WLA%2Fr6K9T5ezSAASUhPOI0l%2BGXwSUYcAwfUjKD1CG9Xh9S8b4H3FvBmp034lVsFtJbz0VgcbQjV%2F0fkNH467TFQSWItZYQUstV8Bc34i92ThziZKNTqy%2F5WbcHL%2BqLXk0Q74y8lI%2BbSyCxawavm8nZ8XTnN3zqXqzjJTb9XitVpglXpxN5lOLGm9PzIWHIjXz8Doc9Gh0pjM5JqywYolg6a6z1SZ0uitirYydJJLdBp8%2FCT6PlrtfH91A270QJb5ZEY7dvL3t9NlJK1IL9LcRc3et0Gv5StJWDpRbbilSiqtzD50V8B%2BMTjrmd01H70wmcGWvQY6pgEVr6upBb%2BurXdP7IUSij6Tr2MUxPNQxjyTpqfp9%2FM9f9K4qIk1obOz8ckHWyFlKqGZsjOna08g8DBZI1gGkwJZAtcO%2BDUqq0uMPsy5ztEBggL7JkSpNlomhw3R23BH1CNPy%2BO9RuEjsT%2BTJxxXMwzpxfbaC6MveNLqF%2FRZ9iT2wkuXVXg%2B6H8R6cdpepYm6lAfWfeVkLpR8puIixm77m%2FI9VL6Gl13&X-Amz-Signature=ebae7f2a9df45f7220fa7ffdc043b6f8e21e9fe950a0c4a206d03024322199c2&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46636HWACIS%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T063252Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFYaCXVzLXdlc3QtMiJGMEQCIFMzXmatBvVAneg9bMenh8ayR1bSxxAC8J%2BeqkkLWHlXAiB12BuMTJLprhRGIA%2FiaqOx9mHG9Q%2BvUBeciep%2ByPaPhir%2FAwhvEAAaDDYzNzQyMzE4MzgwNSIM8iBFS5hnynuBRE%2BAKtwDm4yigirgtQ3JdSRjkyUUvlgUFLGzdDbYapxts8sry%2BUK8wLZqGzg9j0qTQmXN40XZDiDAnte6XcLzfCav4WP7f1lnrRY%2F1jgaIMNZtYLFsf4YjZQCPBCWVGx1MsFLkLcJZ9lSj%2FkbyPJdEiFMZWcLDPTtCdHM5ga2AlLieI8xYGN%2BZhroyOrVkAnKRnjOUHMLZqnIEZrSDq07tgXsQz5z67oQB3Q0jEouC5sCxQFEDrSzWqBOkPNG04s1D92UcVmPw91XFVUC6FQ5GyIhA2A0IbhQTRiUEW1riukfJAS7a2GUXyTFqvdPjxA4tH0WLA%2Fr6K9T5ezSAASUhPOI0l%2BGXwSUYcAwfUjKD1CG9Xh9S8b4H3FvBmp034lVsFtJbz0VgcbQjV%2F0fkNH467TFQSWItZYQUstV8Bc34i92ThziZKNTqy%2F5WbcHL%2BqLXk0Q74y8lI%2BbSyCxawavm8nZ8XTnN3zqXqzjJTb9XitVpglXpxN5lOLGm9PzIWHIjXz8Doc9Gh0pjM5JqywYolg6a6z1SZ0uitirYydJJLdBp8%2FCT6PlrtfH91A270QJb5ZEY7dvL3t9NlJK1IL9LcRc3et0Gv5StJWDpRbbilSiqtzD50V8B%2BMTjrmd01H70wmcGWvQY6pgEVr6upBb%2BurXdP7IUSij6Tr2MUxPNQxjyTpqfp9%2FM9f9K4qIk1obOz8ckHWyFlKqGZsjOna08g8DBZI1gGkwJZAtcO%2BDUqq0uMPsy5ztEBggL7JkSpNlomhw3R23BH1CNPy%2BO9RuEjsT%2BTJxxXMwzpxfbaC6MveNLqF%2FRZ9iT2wkuXVXg%2B6H8R6cdpepYm6lAfWfeVkLpR8puIixm77m%2FI9VL6Gl13&X-Amz-Signature=26fbe57e9c316b5acfd9072c19ec60da946a856048be84e082040f8a6cf8854b&X-Amz-SignedHeaders=host&x-id=GetObject)


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

