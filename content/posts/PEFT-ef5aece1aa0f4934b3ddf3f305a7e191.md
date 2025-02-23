---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466VWVACRO5%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250223T142135Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEN3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIBljLmzBa7qCYnSUVfQ\
  lJOXByG93knsLx5CY9hiiLYZQAiAhntZT8Jc9O50UNogYlGDtMYTZDxlDP0I4mIfW4dCZ3yr%2FAw\
  gWEAAaDDYzNzQyMzE4MzgwNSIMy2AuanSOrI%2Ber6hnKtwD5uRe0czzjBhwSw8XgIKsYCYTC5kib\
  xgan%2FhpLwk3KRBRFPi0Xdg4bpRZ%2ByrmD5JsaCkDMwsAi%2BK0tE%2FwsDykoUrQ0%2FbWpUhj\
  qpqa4VRqfiFcH8qiRBNHCj2CkoBsTq4JTmS1eJLZqtUKPytBuhdjp5HmI3e%2B%2FV26T0Lc%2BCt\
  B%2BuuUc0AiVnfdi45U1IscemvQM1WxYE35WCV07%2B0cpgQfZ%2Bx7TCVt7voCgTkRdKu5GacHqc\
  lzK7VjJSfalfaR4Rkwju4D4VemKkIe5fV%2Bcvke1s0kd4PpdCEGTHIPNeAD%2BExg5oCifpIy%2B\
  x6Zt1AyvqvwQcWmVErpcTI2s8Y6sYEzgi7GofNv5WOYjREsnlWWsiyK7p0q6Cp%2BYD3fT7bwVRpy\
  o3T%2BmZ6AC7Obhl7lKLUTolgpWz1MdQHzeZ8M%2F8zFCddchrFHcSKEaT9%2Ffrq2FhkWtLuw2vP\
  Xe9JM%2BFcrtFdHmnRxR%2BU63SNSp4gfNtMHVWp%2BsnLpY0RRsDGTsH4EVJ%2BTBFHC%2BvIqWs\
  Tyb93wCVQBPyMCgPHgEPhSCq%2FOgz%2BxQUnyfpFRVbY%2Ff4PePgX8jrtoDb5OZWS3ZrsKGCt7p\
  iP7HN6gVezxLpRh2zBw31xZIw0SWSrkPbn6b57r9DYwjL%2FsvQY6pgEBrn5dHSY6KRsCHVL7WXxE\
  QdGlCYILY7fYFz3Mc18gQxbPvBHXA815uBJEHNu%2F%2B8y0qh5l7dGAxseIjOKi7tnCZ%2B7pqAh\
  0t4e4mE9BtJefYQ4DmtU9pzRaVXOwsrWBPISP%2F4atBxhf2sO%2FoCRRUJE3VP6ZE8ZC%2BjQfMl\
  EVlk8zI9YTR%2FZulb8B8v3b%2Fw6VEU2cAMa7gBhapi644A764DoJtEVEttQD&X-Amz-Signatur\
  e=d821fe3a25f3bd7ce3eaedb16317497f4a1cfb5c59953526079bc406d95651e6&X-Amz-Sign\
  edHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466WI5XGRJA%2F20250223%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250223T141953Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjENn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEY\
        CIQCpTKQL0%2Bo2yBVg68WA6%2BtQEwXWUtf70178tmu8crBBFAIhALd%2BYxAFG2ubSHSe\
        gn%2BDXKkchKUoYAr5kHKehC3iXnwbKv8DCBIQABoMNjM3NDIzMTgzODA1IgxCWzHRLD3PX\
        qO77Rkq3APy3ilDdeoJw%2BuQ%2FY1Vp04pTu%2FI6ZjGk9qMYwZI%2BsAjR5inlCGQS3ku\
        nEsgU%2BMtbIW8KRwkwRqw480x2GgBw8NXJeSoSCSnoIowhlgohirRtT7rA3vK1cp318Sdj\
        YK3qgK3w365P9kiWktNfuJTmKtK3CqYQ%2Foyv9X0JRt1ZwIvlWCpzRmdJLB6wb788NEB3w\
        Y%2Fk88SixWyvHdvuQNM5VDV66A2dDMP77NLzd9VYckOspwPuw0FdgkpbI34MD%2FjXatj1\
        S1X1J9A95ZFFDrWcEBaUR8QI7i7h9aY4yn%2BkCmpsUGoA5X7Vm1fWRdP7qYg%2FGndBgug\
        JHlQpR3Df0pAmgp3BIkZgD7aCRN0geIeLlJaDSb18DD3W3J6V6NYPl9jXvfqvnsjXLhQhiS\
        4BfSR7%2BuZKwZiI1S1ReX72xJesZ3%2FQUgQASSL14aHUfWXjBc%2F%2FFKxk6v67ED5d7\
        X4Q7yPOgAhVzoyi%2BiNXxsOPxBTogm%2FEUVmIES408Alt%2FXlnIge%2F813xENo8qzWe\
        hpiDCUknuDDywWw3o%2BL89Iqp5pMbopl6XD1svTTLT79PI2uRHvme5ABQwC3OsoYJxBPm%\
        2BPov%2BFLTtquxGnMQGR5mc%2F9798vpPzTagCqZW0aJCvoWTCOzeu9BjqkAZ%2BPZ7%2F\
        01oG3902KCUlPz7M5le2%2B2gN0Ll6QU5jg7RFOgbrlvcPYY066iFZ1ANzALisT%2BQiKr5\
        mGFsmhBOEslUetklzU0BKnL12H2PfWaukqhVigq6LcP7rYkuqC%2Fe1%2BG8D%2Fu2ctXQv\
        sTHeeXsOqhGPv47I73b%2BhY%2BPFfaLRQ%2FnayWk3UJNwHL%2FphZCN3lLO78mBXcrEyS\
        dZtQPvX9A5lKtf0iGx&X-Amz-Signature=c3bcadf5f3eba1f575e4cee464dea3164cf6\
        8afa9b1e10e3560f0c2ec338d715&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-23T15:19:53.554Z"
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
UPDATE_TIME: "2025-02-23T14:21:40.704Z"
EXPIRY_TIME: "2025-02-23T15:21:29.465Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665HELN6U7%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T142129Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD9rX5QVU6Rvi4%2BrKlHFBoAD3HhmEVBXVVFIvqJIKmnsgIhAMmhA6Ma%2BHZu62XaYGiMLYlQC0pqSAVAIbx9tSbhghQXKv8DCBIQABoMNjM3NDIzMTgzODA1IgyD1SW75xGz0ky%2Ff48q3ANy5tVp4BOAxV%2FBID3MZgo1ZbnWJ%2B97rNpICN9aZiWW3SddnK1OMXrWpnwUkP2WslwQTHLYCh5%2Fyql9P62wiGpFbJE79x696h0tiKb3gWMMIYqqILCxifQKan7%2FNrtZ3blv%2FDZuz0q8fmDOVQfRTmNfzUna%2BYZdUC4GGFNtsH2%2BwB%2BNQNzNlGW2kaRqaqD19mNqFf5qDfDD3GqzqIAS0MvfL3OfrJji4norLv%2FjJuU4ypIXU9O%2BaKazW0IQhYn%2BG6%2BkgZAiwTwLZlpB6kwgQVkUBLUHDN4OdPuZCY0CD%2Ffx%2F2icCkQ9PvZb1rJE%2FSWAdmeN4D4ImkQWWZAOLh3avTC7tAg5MKI%2Bd9E6vS%2Bqr0YtYsINdUYPhsxcRqUFVrmrI%2FSFQKOfvtWurbu56i0QfmA0%2BkpGKJM1Bj%2FQQfxfeVzV6Y7NJw1lq3VnIxx6lCZdy60fgqk8VFimPu0woqP%2BfmE40noGslH1B%2FLIdfMRpXJlmHomQadH8oXlImyvSR5SQyycSRDs0uUOXQ2eIg3ci4vO7jy0VYEaOtPlMLx3RyA0vvBUIrL7beuUMcmGHnEK0vdFkH1%2BAO2quij7YYSLEjQMubZ519sp43ibvCTSVxh1mnOWWHvuvc%2FsT7zrBjCpz%2Bu9BjqkATL%2FfzvhYByoGD07oGKnUurxGxQMHDlRzLmYscJ%2BJA3mFHoHSZ6zUJH22U%2BrdhhpEA5JTb0YUtB6%2Bi%2F23%2F309g4%2BOY%2B0rHkUcakSo4pfFsXzvBqUydu8Xr1WYGfqYLqhG7ZM7i5lNVijnlnhf0PZ4A9sVl8bljhomHn5S1Q7uuABj%2FQIcZskbAJVWfZa17%2FSJSU7XP9RU5TTiVxeRM7J9ofaUSeJ&X-Amz-Signature=795816d7df641387e261be738dd6b80d4cb46615a1d75e12ad0555fb2e334d1a&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665HELN6U7%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T142129Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD9rX5QVU6Rvi4%2BrKlHFBoAD3HhmEVBXVVFIvqJIKmnsgIhAMmhA6Ma%2BHZu62XaYGiMLYlQC0pqSAVAIbx9tSbhghQXKv8DCBIQABoMNjM3NDIzMTgzODA1IgyD1SW75xGz0ky%2Ff48q3ANy5tVp4BOAxV%2FBID3MZgo1ZbnWJ%2B97rNpICN9aZiWW3SddnK1OMXrWpnwUkP2WslwQTHLYCh5%2Fyql9P62wiGpFbJE79x696h0tiKb3gWMMIYqqILCxifQKan7%2FNrtZ3blv%2FDZuz0q8fmDOVQfRTmNfzUna%2BYZdUC4GGFNtsH2%2BwB%2BNQNzNlGW2kaRqaqD19mNqFf5qDfDD3GqzqIAS0MvfL3OfrJji4norLv%2FjJuU4ypIXU9O%2BaKazW0IQhYn%2BG6%2BkgZAiwTwLZlpB6kwgQVkUBLUHDN4OdPuZCY0CD%2Ffx%2F2icCkQ9PvZb1rJE%2FSWAdmeN4D4ImkQWWZAOLh3avTC7tAg5MKI%2Bd9E6vS%2Bqr0YtYsINdUYPhsxcRqUFVrmrI%2FSFQKOfvtWurbu56i0QfmA0%2BkpGKJM1Bj%2FQQfxfeVzV6Y7NJw1lq3VnIxx6lCZdy60fgqk8VFimPu0woqP%2BfmE40noGslH1B%2FLIdfMRpXJlmHomQadH8oXlImyvSR5SQyycSRDs0uUOXQ2eIg3ci4vO7jy0VYEaOtPlMLx3RyA0vvBUIrL7beuUMcmGHnEK0vdFkH1%2BAO2quij7YYSLEjQMubZ519sp43ibvCTSVxh1mnOWWHvuvc%2FsT7zrBjCpz%2Bu9BjqkATL%2FfzvhYByoGD07oGKnUurxGxQMHDlRzLmYscJ%2BJA3mFHoHSZ6zUJH22U%2BrdhhpEA5JTb0YUtB6%2Bi%2F23%2F309g4%2BOY%2B0rHkUcakSo4pfFsXzvBqUydu8Xr1WYGfqYLqhG7ZM7i5lNVijnlnhf0PZ4A9sVl8bljhomHn5S1Q7uuABj%2FQIcZskbAJVWfZa17%2FSJSU7XP9RU5TTiVxeRM7J9ofaUSeJ&X-Amz-Signature=ceadb20202203c4f935a7519d68ff4f18bb35d56b9fcc46da983899661a9ec6c&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665HELN6U7%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T142129Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD9rX5QVU6Rvi4%2BrKlHFBoAD3HhmEVBXVVFIvqJIKmnsgIhAMmhA6Ma%2BHZu62XaYGiMLYlQC0pqSAVAIbx9tSbhghQXKv8DCBIQABoMNjM3NDIzMTgzODA1IgyD1SW75xGz0ky%2Ff48q3ANy5tVp4BOAxV%2FBID3MZgo1ZbnWJ%2B97rNpICN9aZiWW3SddnK1OMXrWpnwUkP2WslwQTHLYCh5%2Fyql9P62wiGpFbJE79x696h0tiKb3gWMMIYqqILCxifQKan7%2FNrtZ3blv%2FDZuz0q8fmDOVQfRTmNfzUna%2BYZdUC4GGFNtsH2%2BwB%2BNQNzNlGW2kaRqaqD19mNqFf5qDfDD3GqzqIAS0MvfL3OfrJji4norLv%2FjJuU4ypIXU9O%2BaKazW0IQhYn%2BG6%2BkgZAiwTwLZlpB6kwgQVkUBLUHDN4OdPuZCY0CD%2Ffx%2F2icCkQ9PvZb1rJE%2FSWAdmeN4D4ImkQWWZAOLh3avTC7tAg5MKI%2Bd9E6vS%2Bqr0YtYsINdUYPhsxcRqUFVrmrI%2FSFQKOfvtWurbu56i0QfmA0%2BkpGKJM1Bj%2FQQfxfeVzV6Y7NJw1lq3VnIxx6lCZdy60fgqk8VFimPu0woqP%2BfmE40noGslH1B%2FLIdfMRpXJlmHomQadH8oXlImyvSR5SQyycSRDs0uUOXQ2eIg3ci4vO7jy0VYEaOtPlMLx3RyA0vvBUIrL7beuUMcmGHnEK0vdFkH1%2BAO2quij7YYSLEjQMubZ519sp43ibvCTSVxh1mnOWWHvuvc%2FsT7zrBjCpz%2Bu9BjqkATL%2FfzvhYByoGD07oGKnUurxGxQMHDlRzLmYscJ%2BJA3mFHoHSZ6zUJH22U%2BrdhhpEA5JTb0YUtB6%2Bi%2F23%2F309g4%2BOY%2B0rHkUcakSo4pfFsXzvBqUydu8Xr1WYGfqYLqhG7ZM7i5lNVijnlnhf0PZ4A9sVl8bljhomHn5S1Q7uuABj%2FQIcZskbAJVWfZa17%2FSJSU7XP9RU5TTiVxeRM7J9ofaUSeJ&X-Amz-Signature=f231a09a7c5a2dfe6ba3e031df46f4f4a0cef2d059686d94d625958dc1fbe0e3&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665HELN6U7%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T142129Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD9rX5QVU6Rvi4%2BrKlHFBoAD3HhmEVBXVVFIvqJIKmnsgIhAMmhA6Ma%2BHZu62XaYGiMLYlQC0pqSAVAIbx9tSbhghQXKv8DCBIQABoMNjM3NDIzMTgzODA1IgyD1SW75xGz0ky%2Ff48q3ANy5tVp4BOAxV%2FBID3MZgo1ZbnWJ%2B97rNpICN9aZiWW3SddnK1OMXrWpnwUkP2WslwQTHLYCh5%2Fyql9P62wiGpFbJE79x696h0tiKb3gWMMIYqqILCxifQKan7%2FNrtZ3blv%2FDZuz0q8fmDOVQfRTmNfzUna%2BYZdUC4GGFNtsH2%2BwB%2BNQNzNlGW2kaRqaqD19mNqFf5qDfDD3GqzqIAS0MvfL3OfrJji4norLv%2FjJuU4ypIXU9O%2BaKazW0IQhYn%2BG6%2BkgZAiwTwLZlpB6kwgQVkUBLUHDN4OdPuZCY0CD%2Ffx%2F2icCkQ9PvZb1rJE%2FSWAdmeN4D4ImkQWWZAOLh3avTC7tAg5MKI%2Bd9E6vS%2Bqr0YtYsINdUYPhsxcRqUFVrmrI%2FSFQKOfvtWurbu56i0QfmA0%2BkpGKJM1Bj%2FQQfxfeVzV6Y7NJw1lq3VnIxx6lCZdy60fgqk8VFimPu0woqP%2BfmE40noGslH1B%2FLIdfMRpXJlmHomQadH8oXlImyvSR5SQyycSRDs0uUOXQ2eIg3ci4vO7jy0VYEaOtPlMLx3RyA0vvBUIrL7beuUMcmGHnEK0vdFkH1%2BAO2quij7YYSLEjQMubZ519sp43ibvCTSVxh1mnOWWHvuvc%2FsT7zrBjCpz%2Bu9BjqkATL%2FfzvhYByoGD07oGKnUurxGxQMHDlRzLmYscJ%2BJA3mFHoHSZ6zUJH22U%2BrdhhpEA5JTb0YUtB6%2Bi%2F23%2F309g4%2BOY%2B0rHkUcakSo4pfFsXzvBqUydu8Xr1WYGfqYLqhG7ZM7i5lNVijnlnhf0PZ4A9sVl8bljhomHn5S1Q7uuABj%2FQIcZskbAJVWfZa17%2FSJSU7XP9RU5TTiVxeRM7J9ofaUSeJ&X-Amz-Signature=db3f5738f130a26a172220003e0c8c328055abd746d7ab104b1e97a4a626701c&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665HELN6U7%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T142129Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD9rX5QVU6Rvi4%2BrKlHFBoAD3HhmEVBXVVFIvqJIKmnsgIhAMmhA6Ma%2BHZu62XaYGiMLYlQC0pqSAVAIbx9tSbhghQXKv8DCBIQABoMNjM3NDIzMTgzODA1IgyD1SW75xGz0ky%2Ff48q3ANy5tVp4BOAxV%2FBID3MZgo1ZbnWJ%2B97rNpICN9aZiWW3SddnK1OMXrWpnwUkP2WslwQTHLYCh5%2Fyql9P62wiGpFbJE79x696h0tiKb3gWMMIYqqILCxifQKan7%2FNrtZ3blv%2FDZuz0q8fmDOVQfRTmNfzUna%2BYZdUC4GGFNtsH2%2BwB%2BNQNzNlGW2kaRqaqD19mNqFf5qDfDD3GqzqIAS0MvfL3OfrJji4norLv%2FjJuU4ypIXU9O%2BaKazW0IQhYn%2BG6%2BkgZAiwTwLZlpB6kwgQVkUBLUHDN4OdPuZCY0CD%2Ffx%2F2icCkQ9PvZb1rJE%2FSWAdmeN4D4ImkQWWZAOLh3avTC7tAg5MKI%2Bd9E6vS%2Bqr0YtYsINdUYPhsxcRqUFVrmrI%2FSFQKOfvtWurbu56i0QfmA0%2BkpGKJM1Bj%2FQQfxfeVzV6Y7NJw1lq3VnIxx6lCZdy60fgqk8VFimPu0woqP%2BfmE40noGslH1B%2FLIdfMRpXJlmHomQadH8oXlImyvSR5SQyycSRDs0uUOXQ2eIg3ci4vO7jy0VYEaOtPlMLx3RyA0vvBUIrL7beuUMcmGHnEK0vdFkH1%2BAO2quij7YYSLEjQMubZ519sp43ibvCTSVxh1mnOWWHvuvc%2FsT7zrBjCpz%2Bu9BjqkATL%2FfzvhYByoGD07oGKnUurxGxQMHDlRzLmYscJ%2BJA3mFHoHSZ6zUJH22U%2BrdhhpEA5JTb0YUtB6%2Bi%2F23%2F309g4%2BOY%2B0rHkUcakSo4pfFsXzvBqUydu8Xr1WYGfqYLqhG7ZM7i5lNVijnlnhf0PZ4A9sVl8bljhomHn5S1Q7uuABj%2FQIcZskbAJVWfZa17%2FSJSU7XP9RU5TTiVxeRM7J9ofaUSeJ&X-Amz-Signature=c13f7dedb4b39f0d2ff515a0b6c67c7b06a8cc37e1fa9c82d5fa0190e10dc1d9&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VI4G4SQZ%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T142130Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEN3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCf0lQflTaNuD3DYCo5Lzv0Ftfz444fa9zYN8EJgmR9tQIgf1EDHV79YA1wHAJaH5Kc8JYZuKl4y1tPZYecH2JeCLwq%2FwMIFhAAGgw2Mzc0MjMxODM4MDUiDNJ%2BU%2F6jJkMa7zXt7SrcAzYU94%2B4LqxEgPNBjxeEYXmK%2BM0%2BDRcXBG8ZfoqwtZvaJeblucsfYL7X65GZ175L2%2FPpkizG5XOIfP954rd6RIbjaxRCspmmFBYRsIJL4l21hoZIrWMeP4VPhyjGBlofh87%2F4YdRTrSQGMZBJdJdYvziTp0D2klCraFL1ZUeoSouyxPV%2FLujpUWY8RIJcVqXMGPDPGku7eqks85tu7lMfd9CE1HLcbgwP1mc1Z5%2BmBfNanpqNBPxBJdK40%2FurFiA0GbPQX9IuzjVjT665oOYlc4j0UiQWjWywLlECuqW3sD5uncg4p%2F1IP%2BeOV%2BGGJf%2FelUnorcvSbcHt200Iyuly2VGQM34kulq%2FcptqOqhHSpoUvkRmSCorsm6o4I%2Flw4gzq6iN9elri0irSa%2BNIGKCpdGpDQe5yS5DgILJaT2r8%2FqQP3KmrQcNBlhbrAW8mQ2SvfludLtSN3XEauJERGsNCXl%2FjCUin7JTfzWlP3lC6VLPZvzqNKWkkoWqFL18RyRmaLHU%2Br1yJkKK3O0GJ%2BSL5c0JZmaGRN9QDuOICW4ghQ7iSB1upm62ciXMVz9HSNS66ScKa%2FzsEJ%2Bazy4PNmc0A4bTSPZL2%2FE9fRijZGZqIAfOt7rOtQB0XBlM1LyMOiy7L0GOqUBVXHk%2FUCy2j%2BgzTCXSU9MjhEUw2t8A2pvcrUn8MXxZo%2BTHOq45uGFq7RrDvUg9Z3Ge3ge46OuA%2FPN6rYE%2FLoc%2BNCaj1JIoS1oPWtF3gXdWx4hcilK%2FBS1KCW%2BzZ5%2FCIBYZ7aY0j998Pr41Y4rabbBvPy2FqucDOekcMt%2BpBKGAOcQzy%2BRPfyAKSeFbNnli4YY3OrwjdD4ic5d%2BZXZ%2Fn9WPq23Wcym&X-Amz-Signature=4eee5e3183f53e29762b38bf81fba07e1b79915e0b9a1e0d0478830c38d241c9&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RMZRFOIJ%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T142134Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIA%2FuZeHs4w6fLGDSI7qbLjvKcWYr3quGAGXVj5dohUO1AiBke1IElD%2BvSTx%2FA2JqDjcUcwjFLUnHzzF9aflwmwTZtSr%2FAwgSEAAaDDYzNzQyMzE4MzgwNSIMF9oD0%2FK3qYi99s1jKtwDaaica1Q72mnzKg98OUFXuxhZ2HH8xpYaRNv%2ByCF4Ed3z%2FfUC6aDML6ONMSN0yAbH3uP534bCSp%2BM%2BlEz2tQCBZ5DrjzwdqTSPLyrNiBUZHZtxcXN1Pd1goM72b%2BRKazh90JPz2TYmCmPdX2d4yIxrCqaoelBd6Os2hFCFUlWAigtutkDUZr9hnTefnwoUJnJsiR1t806xj5nBZuO104%2BNI51pFkZjGtJ6kxuqmZKKobi51WKd78ifN8LIo%2BKkTVkcHMxqaMGbo02qAYLVpOkiqnDprYG7A%2BLZNJjQhOJsWP%2F5bOuY0KFKuc8S7FIPPG0nN7lAYdKMsHbAtpHB1Cz%2FEyeW7Pvw5jnD567ybdYiejWUKDR9ixhChVt2ULfwLWWgvrx07qk7Va%2BULUzt3Fas0Zvf9k6CUbjwQyLRQiFNhBVG5Usqor71lK4uopDMTNbqd4dwspVa9NbQSCE3iMDlhb8YNOzoBsv5sHeBUJ0J7plGF9D6cJsRqQNwtpdCfBHMP%2FJeQBahWoJBCdwB5sPehW3Zw9WOOgLIlFptv%2B46WOfK1gARCDrdL8xGabQKFmlkEiSE1RTPRwA9QdgIoNmxcLkiBhqz3gILbvhQQRC%2FIncFOXYrqMIoLyFxJswkrvrvQY6pgE41KCH1fHP26LCiZvfa8c5JsioXLJ4CqC%2Fp%2BWJX74%2BRcAyFgI8lOWZCmE19g34TYXK%2BpTCti1WmWo9ZyhBflPjtlG8j7HF4Zi2TrF2cD6ubQZQNknA%2Ffl4m1sguczW%2FeS9PSmrUMPO8%2B0vUKl4tg7sSNfvVs6SDq0BYsZ7CulUf7Wi8WPT%2FzshSMr4QzRPCI11AwUsfA%2BK79%2F8yI7SonvwJcMNGrqp&X-Amz-Signature=9cd2eb163c3ff42fc5a6ce7db3fa0a669874b6a1897986aed9680903d9fc7fd5&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665HELN6U7%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T142129Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD9rX5QVU6Rvi4%2BrKlHFBoAD3HhmEVBXVVFIvqJIKmnsgIhAMmhA6Ma%2BHZu62XaYGiMLYlQC0pqSAVAIbx9tSbhghQXKv8DCBIQABoMNjM3NDIzMTgzODA1IgyD1SW75xGz0ky%2Ff48q3ANy5tVp4BOAxV%2FBID3MZgo1ZbnWJ%2B97rNpICN9aZiWW3SddnK1OMXrWpnwUkP2WslwQTHLYCh5%2Fyql9P62wiGpFbJE79x696h0tiKb3gWMMIYqqILCxifQKan7%2FNrtZ3blv%2FDZuz0q8fmDOVQfRTmNfzUna%2BYZdUC4GGFNtsH2%2BwB%2BNQNzNlGW2kaRqaqD19mNqFf5qDfDD3GqzqIAS0MvfL3OfrJji4norLv%2FjJuU4ypIXU9O%2BaKazW0IQhYn%2BG6%2BkgZAiwTwLZlpB6kwgQVkUBLUHDN4OdPuZCY0CD%2Ffx%2F2icCkQ9PvZb1rJE%2FSWAdmeN4D4ImkQWWZAOLh3avTC7tAg5MKI%2Bd9E6vS%2Bqr0YtYsINdUYPhsxcRqUFVrmrI%2FSFQKOfvtWurbu56i0QfmA0%2BkpGKJM1Bj%2FQQfxfeVzV6Y7NJw1lq3VnIxx6lCZdy60fgqk8VFimPu0woqP%2BfmE40noGslH1B%2FLIdfMRpXJlmHomQadH8oXlImyvSR5SQyycSRDs0uUOXQ2eIg3ci4vO7jy0VYEaOtPlMLx3RyA0vvBUIrL7beuUMcmGHnEK0vdFkH1%2BAO2quij7YYSLEjQMubZ519sp43ibvCTSVxh1mnOWWHvuvc%2FsT7zrBjCpz%2Bu9BjqkATL%2FfzvhYByoGD07oGKnUurxGxQMHDlRzLmYscJ%2BJA3mFHoHSZ6zUJH22U%2BrdhhpEA5JTb0YUtB6%2Bi%2F23%2F309g4%2BOY%2B0rHkUcakSo4pfFsXzvBqUydu8Xr1WYGfqYLqhG7ZM7i5lNVijnlnhf0PZ4A9sVl8bljhomHn5S1Q7uuABj%2FQIcZskbAJVWfZa17%2FSJSU7XP9RU5TTiVxeRM7J9ofaUSeJ&X-Amz-Signature=7994d0316fd90c384d3c8825031b54c19bc7696d0da997189a552e8c86399377&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665HELN6U7%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T142129Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD9rX5QVU6Rvi4%2BrKlHFBoAD3HhmEVBXVVFIvqJIKmnsgIhAMmhA6Ma%2BHZu62XaYGiMLYlQC0pqSAVAIbx9tSbhghQXKv8DCBIQABoMNjM3NDIzMTgzODA1IgyD1SW75xGz0ky%2Ff48q3ANy5tVp4BOAxV%2FBID3MZgo1ZbnWJ%2B97rNpICN9aZiWW3SddnK1OMXrWpnwUkP2WslwQTHLYCh5%2Fyql9P62wiGpFbJE79x696h0tiKb3gWMMIYqqILCxifQKan7%2FNrtZ3blv%2FDZuz0q8fmDOVQfRTmNfzUna%2BYZdUC4GGFNtsH2%2BwB%2BNQNzNlGW2kaRqaqD19mNqFf5qDfDD3GqzqIAS0MvfL3OfrJji4norLv%2FjJuU4ypIXU9O%2BaKazW0IQhYn%2BG6%2BkgZAiwTwLZlpB6kwgQVkUBLUHDN4OdPuZCY0CD%2Ffx%2F2icCkQ9PvZb1rJE%2FSWAdmeN4D4ImkQWWZAOLh3avTC7tAg5MKI%2Bd9E6vS%2Bqr0YtYsINdUYPhsxcRqUFVrmrI%2FSFQKOfvtWurbu56i0QfmA0%2BkpGKJM1Bj%2FQQfxfeVzV6Y7NJw1lq3VnIxx6lCZdy60fgqk8VFimPu0woqP%2BfmE40noGslH1B%2FLIdfMRpXJlmHomQadH8oXlImyvSR5SQyycSRDs0uUOXQ2eIg3ci4vO7jy0VYEaOtPlMLx3RyA0vvBUIrL7beuUMcmGHnEK0vdFkH1%2BAO2quij7YYSLEjQMubZ519sp43ibvCTSVxh1mnOWWHvuvc%2FsT7zrBjCpz%2Bu9BjqkATL%2FfzvhYByoGD07oGKnUurxGxQMHDlRzLmYscJ%2BJA3mFHoHSZ6zUJH22U%2BrdhhpEA5JTb0YUtB6%2Bi%2F23%2F309g4%2BOY%2B0rHkUcakSo4pfFsXzvBqUydu8Xr1WYGfqYLqhG7ZM7i5lNVijnlnhf0PZ4A9sVl8bljhomHn5S1Q7uuABj%2FQIcZskbAJVWfZa17%2FSJSU7XP9RU5TTiVxeRM7J9ofaUSeJ&X-Amz-Signature=f5e7cbcfde448db85a1fc712ede6bac0ed26b0b79bfadaccfb09b52e4ae2d920&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665HELN6U7%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T142129Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD9rX5QVU6Rvi4%2BrKlHFBoAD3HhmEVBXVVFIvqJIKmnsgIhAMmhA6Ma%2BHZu62XaYGiMLYlQC0pqSAVAIbx9tSbhghQXKv8DCBIQABoMNjM3NDIzMTgzODA1IgyD1SW75xGz0ky%2Ff48q3ANy5tVp4BOAxV%2FBID3MZgo1ZbnWJ%2B97rNpICN9aZiWW3SddnK1OMXrWpnwUkP2WslwQTHLYCh5%2Fyql9P62wiGpFbJE79x696h0tiKb3gWMMIYqqILCxifQKan7%2FNrtZ3blv%2FDZuz0q8fmDOVQfRTmNfzUna%2BYZdUC4GGFNtsH2%2BwB%2BNQNzNlGW2kaRqaqD19mNqFf5qDfDD3GqzqIAS0MvfL3OfrJji4norLv%2FjJuU4ypIXU9O%2BaKazW0IQhYn%2BG6%2BkgZAiwTwLZlpB6kwgQVkUBLUHDN4OdPuZCY0CD%2Ffx%2F2icCkQ9PvZb1rJE%2FSWAdmeN4D4ImkQWWZAOLh3avTC7tAg5MKI%2Bd9E6vS%2Bqr0YtYsINdUYPhsxcRqUFVrmrI%2FSFQKOfvtWurbu56i0QfmA0%2BkpGKJM1Bj%2FQQfxfeVzV6Y7NJw1lq3VnIxx6lCZdy60fgqk8VFimPu0woqP%2BfmE40noGslH1B%2FLIdfMRpXJlmHomQadH8oXlImyvSR5SQyycSRDs0uUOXQ2eIg3ci4vO7jy0VYEaOtPlMLx3RyA0vvBUIrL7beuUMcmGHnEK0vdFkH1%2BAO2quij7YYSLEjQMubZ519sp43ibvCTSVxh1mnOWWHvuvc%2FsT7zrBjCpz%2Bu9BjqkATL%2FfzvhYByoGD07oGKnUurxGxQMHDlRzLmYscJ%2BJA3mFHoHSZ6zUJH22U%2BrdhhpEA5JTb0YUtB6%2Bi%2F23%2F309g4%2BOY%2B0rHkUcakSo4pfFsXzvBqUydu8Xr1WYGfqYLqhG7ZM7i5lNVijnlnhf0PZ4A9sVl8bljhomHn5S1Q7uuABj%2FQIcZskbAJVWfZa17%2FSJSU7XP9RU5TTiVxeRM7J9ofaUSeJ&X-Amz-Signature=f09f9d0710d58cedb3367ede4139fc90ed0a72a907daeed4d20c1c2987068bbc&X-Amz-SignedHeaders=host&x-id=GetObject)


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

