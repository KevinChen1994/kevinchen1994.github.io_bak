---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466XY56YVER%2F20250128%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250128T232134Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEHcaCXVzLXdlc3QtMiJGMEQCIDhVcGyvA0295qSnkPAo2XLRhyPPJh%2FC3cFWazRp4i6uAiB%2\
  BnoyZ%2F0ijjYA3py9o70VIMVaJTmw0Ywdh87ne5sDU8yqIBAiA%2F%2F%2F%2F%2F%2F%2F%2F%2\
  F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMuTKSYK9sOOF3vOebKtwDdUnh8EBWP4MHNSwjyGkDndB0t6y\
  7KgxSUCXNMbSNT1eVv9Zh0mRwqmiwxHsFUnu9AeKYKVurdXfOaCAdlk6CIcRmZbUqsD6HqU3WBT4L\
  UuH0ceJ3wIGkWhmq7xpFzDgeJiMJsXPsRr8acx5CCYEy7cOJR%2FuwU9kWP%2Fgh6SLGFo6Kinsqh\
  uMZvCvMEzkgxXPww4dksqg%2Fsgwo3OoQJbX%2BGR7GNXn4UQrU2CjvmLVtaS2wNpUSn%2FUxlJTO\
  jGMx7ZqMuYc35u1R91DYHTQR8scpXh57YJfAOvtAJRN9wurPMctQ%2BrBhOXT5rH%2Fs4hgmIPFJs\
  YvoOjZ3Jqvl6JfJC78wTwzjigyZ14PL52xf4%2BwfzVwygsCAm873W2HNQZ0nGU7ZthhAzeodi8rf\
  6hs7xm%2BOMumDGABKAnvBdl3nP4H55SaO85hnBRH4abOdiwnC%2BAT8pH8g%2FHEoadWUx56lGJx\
  Pr3iv2M1GItYtkBgFLilt5O3tNhEfIJ7mRA8MenT9tGZD0Ud2hXSvD0wJvuMbh%2FmO79WAywmNJI\
  1TBc1CeprMdmPhEWcv9HQeqei0D3N6OD6J9Dl4EkLwXANTaf0QnBwSujz8oq33vNIxCnOL7Couw8Y\
  UnUNl3uK2XsHK3HYws7LlvAY6pgGacmyG1o%2Fv3FbJnKMRUges6fRzsl21zSVXStN6t3qJMWJg11\
  vJEtqD59aMmlkZMd7oG4dX7ZDjCgdEi2YeqihWnl923HlVmXfrvDBVI0CxvlkDskNv7PeygGFaVUI\
  tHntqgLDF0bdrS3gFGEinS2AW5sHK%2BYRaKoGz7tK2WFwQ9Rl%2BMlshR%2Fgdu9gpKke3RZpYUR\
  bjqWjyCOOgewc8ymSsZB9N2CtR&X-Amz-Signature=59efbe8fbb83c549487f3822d27c505972\
  addbfb558f9f150b2d8ec1f8fc8665&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4664F4F42DO%2F20250128%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250128T232011Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEHcaCXVzLXdlc3QtMiJGMEQCIDwBJUZIJc7vkH6INzQi%2Bvh5DB84O\
        gjP6JFuqsdg95L0AiAPEQiTWRe071DGZqfiZPI5vy5ZWcY2ZIzSSjRMlSSRpSqIBAiA%2F%\
        2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMydpHdlh%2BgjJYrkwZK\
        twDEU7%2F5%2FpSgXum39LCIKFHAhnXW9UgLfFjvUmEqze0DHk87g8R0DgflswcPdcjjtBY\
        GJLnniemdBx8ZdvGZV29bnciPcof5cDG5C9SZM%2BPdrK5OuKAWSHpxJvtk%2FCH5aZ%2F8\
        G9rWrWjjwih%2B4KHT4zoh26cKMN%2BBLCD6j79vysVqpZguTMlCx9M9Wa5P2TRfSqu9P%2\
        BWPUkAW3USI30acUyEZyahQIFZoZdq221TnUac%2FpjppRpw6jrO9loy2nMWp5E0vDYiFb9\
        oLnqZHjHxRKLJCb4f3UFKOWtc0H98ykUDHC8UBkDjeHvp6JVaDZJ6pWNouijx21Q9hR%2Fb\
        Prdqq%2BhhCFKYFskunFLEUlFmOjmUD%2BoYXCDKZgkJruVX6hKyh2vWKn%2F1J710pLJEA\
        iFFBBAd4U6kRiwReMfZCUUNG%2BZwWlSbZ1Rx8naPRMBwj6UIUqxTuhmgDWEENgKr%2BqUy\
        9KK6N4TAZPc%2BbCkPJAkCg2Osv0TZ%2BRcGFjWGIUBFdGoPQLwk7Ai8dddJwTMN1F%2Bu4\
        eqppE7%2BKLFIM53bO7PGfTVpx0CVkhPpuNxD1bG1qlxCrOXNmBOJ5%2BVaiv68B8YJ7FRl\
        v6QMI%2FfVvl7x5KMviF%2BMsIWD4uwfbbvIJqRncPgwp7PlvAY6pgGqUpv4CpmKWyStjGh\
        K4dpukG23HALEk9aqq%2FuLE%2FYzE%2BrPxroTho6tFaajLTF5BqLZqBzcQpW3ptxyCGOA\
        diCEBt3apJdTiGeovmRjhdO1il19R3kQmRWwJxZx3hIafYl4YDkelhZnVB7p3jxYyfEQRzW\
        Ms2ig2n9ifjR%2FjxjQ57bBG9P1ra9x%2F1s0cGw2vns4vNSlMC9rm6b68kkkPyiAljYxZ8\
        q2&X-Amz-Signature=084aefecbc527c93c9944b88953c3361e7c3d22802a670509c45\
        9d330bd6e044&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-01-29T00:20:11.317Z"
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
UPDATE_TIME: "2025-01-28T23:21:40.122Z"
EXPIRY_TIME: "2025-01-29T00:21:32.540Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Y373QQOQ%2F20250128%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250128T232133Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHcaCXVzLXdlc3QtMiJHMEUCIQDQNkLmkOei6vOav4oVuSnOK8KiktjiaUGd6s51V1xJBQIgBNjrFOximKE42WMqTLtAaImwFrNmh%2B3pnWJBv2TF2dMq%2FwMIfxAAGgw2Mzc0MjMxODM4MDUiDLnUer%2BHS1S9x47aYSrcA5xoTkxBsPn29nBS3lO87VEbtp3kBqtI8yQdo%2FZHSPF3Z%2BmucAQpVso4x1yWS6R0tOYSN9WNMAdq9tmjj0mEL5RpXuCkCfYFP7e2WZ8VGtZH8eFGi%2BE6Feirc0o6TJXELy6o%2Fo9MWsjRyVbTVql2DQLoTpUUF0o6QuD8S4vgEIj8XXsfCPPmfN2PoVegS1w%2Bz80V9OBxgqHq10sOL%2BjosnAeqJdEyVQEYQUyn%2Fjy3WhJjvL4zQrl4AL14lPlje2yvCVMQxhyEb8lnU04De6QpzayaEc7ZLmlkL0JWv6i%2F4CLu%2BUD5qReP5My8EzoqLrNWtDCOqnDowiQ09%2B8DKDQYE9F2M6FKQCkTEqHJkwuUGVRgttWPFx4hqH%2BG8TmqeZuWEQSC0SGhirXjAddI79y%2Bg1F1Ho7pvid8Bg%2FKW1J%2BAgjThTWTptgUgvvgcp%2FAV5VzFjKebAqee%2BmngOM5lEhYsGOnKzUvaHTo%2Fu6JtQUJMcUJPKJmlX7WQhslVJDEZx4ocKYFdIKjpzHEydeB3tIRSnGrYk51ObYjDIJyGhwTjBVCBWWKhYXnPdAjdoDbkcOj19fYUScpaNLQpfH243UUdtPMsoIaRp%2BGPwhHz01W6WaQpKRz8gMR1Pu%2BXjNMOey5bwGOqUBxsUSvI3ArciHBYusqtq1uHZoe%2FKYW5lmXZxpOK0PhHiFKytPdfIPG0M%2Fi%2FVBr7GKr%2FgREwllbFqaIwzKSrsOZVhBMsNl1WUrBRqDarX2gHYinPz2cde3iNHvQNL%2Fi1vylrwvDvSSukI6JNs8l%2Fps8Vx%2F86JNuTxXtag3nZQBntM4wJLYt2Y6YV1ELg1%2BTHNVDH8hGyJOfc2RZgQuonDWWezh8g9W&X-Amz-Signature=eadc142c8a5c1db8866b306439007b1708a2777b38bfc1748b7faf134c45b097&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Y373QQOQ%2F20250128%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250128T232133Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHcaCXVzLXdlc3QtMiJHMEUCIQDQNkLmkOei6vOav4oVuSnOK8KiktjiaUGd6s51V1xJBQIgBNjrFOximKE42WMqTLtAaImwFrNmh%2B3pnWJBv2TF2dMq%2FwMIfxAAGgw2Mzc0MjMxODM4MDUiDLnUer%2BHS1S9x47aYSrcA5xoTkxBsPn29nBS3lO87VEbtp3kBqtI8yQdo%2FZHSPF3Z%2BmucAQpVso4x1yWS6R0tOYSN9WNMAdq9tmjj0mEL5RpXuCkCfYFP7e2WZ8VGtZH8eFGi%2BE6Feirc0o6TJXELy6o%2Fo9MWsjRyVbTVql2DQLoTpUUF0o6QuD8S4vgEIj8XXsfCPPmfN2PoVegS1w%2Bz80V9OBxgqHq10sOL%2BjosnAeqJdEyVQEYQUyn%2Fjy3WhJjvL4zQrl4AL14lPlje2yvCVMQxhyEb8lnU04De6QpzayaEc7ZLmlkL0JWv6i%2F4CLu%2BUD5qReP5My8EzoqLrNWtDCOqnDowiQ09%2B8DKDQYE9F2M6FKQCkTEqHJkwuUGVRgttWPFx4hqH%2BG8TmqeZuWEQSC0SGhirXjAddI79y%2Bg1F1Ho7pvid8Bg%2FKW1J%2BAgjThTWTptgUgvvgcp%2FAV5VzFjKebAqee%2BmngOM5lEhYsGOnKzUvaHTo%2Fu6JtQUJMcUJPKJmlX7WQhslVJDEZx4ocKYFdIKjpzHEydeB3tIRSnGrYk51ObYjDIJyGhwTjBVCBWWKhYXnPdAjdoDbkcOj19fYUScpaNLQpfH243UUdtPMsoIaRp%2BGPwhHz01W6WaQpKRz8gMR1Pu%2BXjNMOey5bwGOqUBxsUSvI3ArciHBYusqtq1uHZoe%2FKYW5lmXZxpOK0PhHiFKytPdfIPG0M%2Fi%2FVBr7GKr%2FgREwllbFqaIwzKSrsOZVhBMsNl1WUrBRqDarX2gHYinPz2cde3iNHvQNL%2Fi1vylrwvDvSSukI6JNs8l%2Fps8Vx%2F86JNuTxXtag3nZQBntM4wJLYt2Y6YV1ELg1%2BTHNVDH8hGyJOfc2RZgQuonDWWezh8g9W&X-Amz-Signature=b2d378aa17230322e0f9f18feee0082b9f52fa0190239d5c970b097477368353&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Y373QQOQ%2F20250128%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250128T232133Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHcaCXVzLXdlc3QtMiJHMEUCIQDQNkLmkOei6vOav4oVuSnOK8KiktjiaUGd6s51V1xJBQIgBNjrFOximKE42WMqTLtAaImwFrNmh%2B3pnWJBv2TF2dMq%2FwMIfxAAGgw2Mzc0MjMxODM4MDUiDLnUer%2BHS1S9x47aYSrcA5xoTkxBsPn29nBS3lO87VEbtp3kBqtI8yQdo%2FZHSPF3Z%2BmucAQpVso4x1yWS6R0tOYSN9WNMAdq9tmjj0mEL5RpXuCkCfYFP7e2WZ8VGtZH8eFGi%2BE6Feirc0o6TJXELy6o%2Fo9MWsjRyVbTVql2DQLoTpUUF0o6QuD8S4vgEIj8XXsfCPPmfN2PoVegS1w%2Bz80V9OBxgqHq10sOL%2BjosnAeqJdEyVQEYQUyn%2Fjy3WhJjvL4zQrl4AL14lPlje2yvCVMQxhyEb8lnU04De6QpzayaEc7ZLmlkL0JWv6i%2F4CLu%2BUD5qReP5My8EzoqLrNWtDCOqnDowiQ09%2B8DKDQYE9F2M6FKQCkTEqHJkwuUGVRgttWPFx4hqH%2BG8TmqeZuWEQSC0SGhirXjAddI79y%2Bg1F1Ho7pvid8Bg%2FKW1J%2BAgjThTWTptgUgvvgcp%2FAV5VzFjKebAqee%2BmngOM5lEhYsGOnKzUvaHTo%2Fu6JtQUJMcUJPKJmlX7WQhslVJDEZx4ocKYFdIKjpzHEydeB3tIRSnGrYk51ObYjDIJyGhwTjBVCBWWKhYXnPdAjdoDbkcOj19fYUScpaNLQpfH243UUdtPMsoIaRp%2BGPwhHz01W6WaQpKRz8gMR1Pu%2BXjNMOey5bwGOqUBxsUSvI3ArciHBYusqtq1uHZoe%2FKYW5lmXZxpOK0PhHiFKytPdfIPG0M%2Fi%2FVBr7GKr%2FgREwllbFqaIwzKSrsOZVhBMsNl1WUrBRqDarX2gHYinPz2cde3iNHvQNL%2Fi1vylrwvDvSSukI6JNs8l%2Fps8Vx%2F86JNuTxXtag3nZQBntM4wJLYt2Y6YV1ELg1%2BTHNVDH8hGyJOfc2RZgQuonDWWezh8g9W&X-Amz-Signature=dca533895f23f79c7a7990d0dd367a07b7b84a423ba18b6c8b9cec0c658846af&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Y373QQOQ%2F20250128%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250128T232133Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHcaCXVzLXdlc3QtMiJHMEUCIQDQNkLmkOei6vOav4oVuSnOK8KiktjiaUGd6s51V1xJBQIgBNjrFOximKE42WMqTLtAaImwFrNmh%2B3pnWJBv2TF2dMq%2FwMIfxAAGgw2Mzc0MjMxODM4MDUiDLnUer%2BHS1S9x47aYSrcA5xoTkxBsPn29nBS3lO87VEbtp3kBqtI8yQdo%2FZHSPF3Z%2BmucAQpVso4x1yWS6R0tOYSN9WNMAdq9tmjj0mEL5RpXuCkCfYFP7e2WZ8VGtZH8eFGi%2BE6Feirc0o6TJXELy6o%2Fo9MWsjRyVbTVql2DQLoTpUUF0o6QuD8S4vgEIj8XXsfCPPmfN2PoVegS1w%2Bz80V9OBxgqHq10sOL%2BjosnAeqJdEyVQEYQUyn%2Fjy3WhJjvL4zQrl4AL14lPlje2yvCVMQxhyEb8lnU04De6QpzayaEc7ZLmlkL0JWv6i%2F4CLu%2BUD5qReP5My8EzoqLrNWtDCOqnDowiQ09%2B8DKDQYE9F2M6FKQCkTEqHJkwuUGVRgttWPFx4hqH%2BG8TmqeZuWEQSC0SGhirXjAddI79y%2Bg1F1Ho7pvid8Bg%2FKW1J%2BAgjThTWTptgUgvvgcp%2FAV5VzFjKebAqee%2BmngOM5lEhYsGOnKzUvaHTo%2Fu6JtQUJMcUJPKJmlX7WQhslVJDEZx4ocKYFdIKjpzHEydeB3tIRSnGrYk51ObYjDIJyGhwTjBVCBWWKhYXnPdAjdoDbkcOj19fYUScpaNLQpfH243UUdtPMsoIaRp%2BGPwhHz01W6WaQpKRz8gMR1Pu%2BXjNMOey5bwGOqUBxsUSvI3ArciHBYusqtq1uHZoe%2FKYW5lmXZxpOK0PhHiFKytPdfIPG0M%2Fi%2FVBr7GKr%2FgREwllbFqaIwzKSrsOZVhBMsNl1WUrBRqDarX2gHYinPz2cde3iNHvQNL%2Fi1vylrwvDvSSukI6JNs8l%2Fps8Vx%2F86JNuTxXtag3nZQBntM4wJLYt2Y6YV1ELg1%2BTHNVDH8hGyJOfc2RZgQuonDWWezh8g9W&X-Amz-Signature=b4ddf4caa8f46c887c97c0b050c4190e7a85f633784b81945f08c95b762e4167&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Y373QQOQ%2F20250128%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250128T232133Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHcaCXVzLXdlc3QtMiJHMEUCIQDQNkLmkOei6vOav4oVuSnOK8KiktjiaUGd6s51V1xJBQIgBNjrFOximKE42WMqTLtAaImwFrNmh%2B3pnWJBv2TF2dMq%2FwMIfxAAGgw2Mzc0MjMxODM4MDUiDLnUer%2BHS1S9x47aYSrcA5xoTkxBsPn29nBS3lO87VEbtp3kBqtI8yQdo%2FZHSPF3Z%2BmucAQpVso4x1yWS6R0tOYSN9WNMAdq9tmjj0mEL5RpXuCkCfYFP7e2WZ8VGtZH8eFGi%2BE6Feirc0o6TJXELy6o%2Fo9MWsjRyVbTVql2DQLoTpUUF0o6QuD8S4vgEIj8XXsfCPPmfN2PoVegS1w%2Bz80V9OBxgqHq10sOL%2BjosnAeqJdEyVQEYQUyn%2Fjy3WhJjvL4zQrl4AL14lPlje2yvCVMQxhyEb8lnU04De6QpzayaEc7ZLmlkL0JWv6i%2F4CLu%2BUD5qReP5My8EzoqLrNWtDCOqnDowiQ09%2B8DKDQYE9F2M6FKQCkTEqHJkwuUGVRgttWPFx4hqH%2BG8TmqeZuWEQSC0SGhirXjAddI79y%2Bg1F1Ho7pvid8Bg%2FKW1J%2BAgjThTWTptgUgvvgcp%2FAV5VzFjKebAqee%2BmngOM5lEhYsGOnKzUvaHTo%2Fu6JtQUJMcUJPKJmlX7WQhslVJDEZx4ocKYFdIKjpzHEydeB3tIRSnGrYk51ObYjDIJyGhwTjBVCBWWKhYXnPdAjdoDbkcOj19fYUScpaNLQpfH243UUdtPMsoIaRp%2BGPwhHz01W6WaQpKRz8gMR1Pu%2BXjNMOey5bwGOqUBxsUSvI3ArciHBYusqtq1uHZoe%2FKYW5lmXZxpOK0PhHiFKytPdfIPG0M%2Fi%2FVBr7GKr%2FgREwllbFqaIwzKSrsOZVhBMsNl1WUrBRqDarX2gHYinPz2cde3iNHvQNL%2Fi1vylrwvDvSSukI6JNs8l%2Fps8Vx%2F86JNuTxXtag3nZQBntM4wJLYt2Y6YV1ELg1%2BTHNVDH8hGyJOfc2RZgQuonDWWezh8g9W&X-Amz-Signature=e51d5c7e0909c60880fadc6e38365460c9740c1613d87ed34cd4d7f7df1792f5&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YP5UAP5S%2F20250128%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250128T232134Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHcaCXVzLXdlc3QtMiJHMEUCIQDZ1UGeFxpbAvudoj8lKfd116aZcUB01HwUvkk2gWNlYAIgavmtbkN1H7lEXhOr6Y4j8Bpnu%2FIlpdb5EzGhm0RN7NsqiAQIgP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDDSNboBJEeykmFIrCrcAyalTtgYTHDv02AP8lfKE%2BnocbPXpNNIGSGZl%2BKqegnI3XyFvD4UMzFn7lcAs0G8p9I6PRKcO65LEc42NQmxAt5DwMCZV1DsyJkXb5BWvPc2LHQANPXqR%2B7JPhmZJaxYwK4WCBAffLHa0D9XeSFsPSTwDFs00ufNd5ys%2FOI%2FkFxnU8ryDv0PDjInFQyqtk1tx0wBmsm2Zm3ecaWBp%2F98wg4AYRdgb0xjLKRRL8EazRjjPDj5X23hoPJYFZ8dqFuDy%2FotXojfC%2FMp5kh%2F7JOFZMjgQA%2F681sF7tEXZholT3XyJ%2B2TVs1hTNTXpsETCEM83EXQEwRS7q2IEHGjpW90DM%2BGxuWfJ82o%2FKxcKfvdJ21rJOad8poUGOaV1VLs7oFTQiGsI%2BNhJzqhOEiYQWJGCN5gJNRTfWs75sCwKbI3sIkOZ46N14d0fMthI5FIPignrFgaD6Yh%2FNTCHv%2B33Q7D3NGFZqUDco4VLSX2nl7ZO28jKqGzEwynHrtC62Ll2UdLxuGpjFduJQoncQcP%2Bj2D6lO1budEIUMdV6dIS4oAqGINyJK66qaWGu5va26Dtkl%2BLT0qi%2FlsdhUQuYcB9i02w8M5A%2B4BN9mbdQefv0Bonh9av1K82v1knaT%2Bw6vUMKC75bwGOqUB%2B6VZlvWPYx5ZocykIcQk3mHWSKD%2FF2wvq%2Bw3qpcOlQYKrwJtQFyLspDTVz8QcmgNAwXv%2FNci2ObXt3A8RDus5sg39U3oap5C%2Biwt8uC1Gy3AjLkiQEUKBPg4EOliy%2BdHo5GoFDqHHsQHxzCeS%2B2kPrmlI48TDJwFpu%2BDNtFa3Sie1G9JVmHg7RM4gChPKxLcQum1t2pRHUwrmaHrQ3EZ9vCbrGJs&X-Amz-Signature=d21b53f6bd34cf7a2fb6e770e48c68cab4c11854097e59c1e2d53e2d71f007ed&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YWXK5B45%2F20250128%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250128T232134Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHcaCXVzLXdlc3QtMiJHMEUCIQDpxubxtvyfO89JigkCCLlqxRk%2BbLWCUKIYI0dki4pHKQIgQJ1HYvhu6kd%2BsjLb7GSnmv9QuRRfzX3mdlR13MQiGIYq%2FwMIfxAAGgw2Mzc0MjMxODM4MDUiDMIDfPs0ULcD84iVmircAz7OXRRGvMgIawl84L0sEQf2Xy%2FT7wHFNVYUmM2bv0aGuhJv6P%2BUvtcTYtiIz%2BddYo6lWOqNMeiiEph1W%2F49OVhPiE9%2FAqMTeNuj3YhGt1Gc1utLz8G6PtdRp2TBx%2FhTo%2BKm2IEL9hHn4ejlwqAIGR2bhS1sUGLtC5Mfuc%2BHNhFv7qW1xxNywDj2nSYM54UIr%2FnfV%2Fo4neVoIkrxJn4RiLDgUJzYaPljIRK54qVrw6RF4wB0kopG76XGKKm7pqWnFFi4z4rGv%2BYa9VqvyNyK7oWE6xSOJXhJkySN31f7q%2FLrmwvx0tshzbjNqpA0Uw8PUtcduuwdhQKXFrUNNx4Adfqy8e0BmgzHtuo9z9%2Beey9yMe4m9XXfK4uc%2B0I0rfMaXD9IGcLv6UxvB5i0nCGGbP2hL5%2Be6QaAon4J3SlNCG%2FOqJ0bDfKHSsg%2BfiMli%2BeAJnlI6npzqgh1ZJLmqXD%2BSQJrc5pFvq9VFnbHKDfQT0DNhqYU%2BZp0qa79zUQxDwhC38IMYPY%2BYcX1wmx%2BYuZCUOw1M6hInD%2FsxBOxYZTL1mkswiAcwMhS%2BBDavY%2B13drqvPqfZFhWIyFmuEORSc%2FEjpUowVgxhPC39HETRGgK8lfcxEvksB3y%2BuaSjVCJMPax5bwGOqUBFW%2BeK14vUMj1KLHJufGp8waHPxnuxHeg1yQbrC4kLyD%2Bq3jw2Haq4KNE6m63pMRzQitvlSVplKJRW%2FkdwXdQEhOkKLUSL6oIRIdtkSsvsmSndmrsC2fHl4fvTJSO4nD7g1bcnJvpXFJ2fUC9746xP0lgqy70jdX0LFE%2Bgr1yzgbRp%2BJj98ki1tOa373XzlaieoIHwI%2BEIDlkQZ9tf3erdyqOBIps&X-Amz-Signature=5e509a3896c7f5be2d346b726ea30bbe16d8e65d4e8deff26b3650ae3f7069f9&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Y373QQOQ%2F20250128%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250128T232133Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHcaCXVzLXdlc3QtMiJHMEUCIQDQNkLmkOei6vOav4oVuSnOK8KiktjiaUGd6s51V1xJBQIgBNjrFOximKE42WMqTLtAaImwFrNmh%2B3pnWJBv2TF2dMq%2FwMIfxAAGgw2Mzc0MjMxODM4MDUiDLnUer%2BHS1S9x47aYSrcA5xoTkxBsPn29nBS3lO87VEbtp3kBqtI8yQdo%2FZHSPF3Z%2BmucAQpVso4x1yWS6R0tOYSN9WNMAdq9tmjj0mEL5RpXuCkCfYFP7e2WZ8VGtZH8eFGi%2BE6Feirc0o6TJXELy6o%2Fo9MWsjRyVbTVql2DQLoTpUUF0o6QuD8S4vgEIj8XXsfCPPmfN2PoVegS1w%2Bz80V9OBxgqHq10sOL%2BjosnAeqJdEyVQEYQUyn%2Fjy3WhJjvL4zQrl4AL14lPlje2yvCVMQxhyEb8lnU04De6QpzayaEc7ZLmlkL0JWv6i%2F4CLu%2BUD5qReP5My8EzoqLrNWtDCOqnDowiQ09%2B8DKDQYE9F2M6FKQCkTEqHJkwuUGVRgttWPFx4hqH%2BG8TmqeZuWEQSC0SGhirXjAddI79y%2Bg1F1Ho7pvid8Bg%2FKW1J%2BAgjThTWTptgUgvvgcp%2FAV5VzFjKebAqee%2BmngOM5lEhYsGOnKzUvaHTo%2Fu6JtQUJMcUJPKJmlX7WQhslVJDEZx4ocKYFdIKjpzHEydeB3tIRSnGrYk51ObYjDIJyGhwTjBVCBWWKhYXnPdAjdoDbkcOj19fYUScpaNLQpfH243UUdtPMsoIaRp%2BGPwhHz01W6WaQpKRz8gMR1Pu%2BXjNMOey5bwGOqUBxsUSvI3ArciHBYusqtq1uHZoe%2FKYW5lmXZxpOK0PhHiFKytPdfIPG0M%2Fi%2FVBr7GKr%2FgREwllbFqaIwzKSrsOZVhBMsNl1WUrBRqDarX2gHYinPz2cde3iNHvQNL%2Fi1vylrwvDvSSukI6JNs8l%2Fps8Vx%2F86JNuTxXtag3nZQBntM4wJLYt2Y6YV1ELg1%2BTHNVDH8hGyJOfc2RZgQuonDWWezh8g9W&X-Amz-Signature=7805da9b70a649ffb7a9ddd81ef09fce608c3d285474c989e6a2c1a5c1e5adf4&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Y373QQOQ%2F20250128%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250128T232133Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHcaCXVzLXdlc3QtMiJHMEUCIQDQNkLmkOei6vOav4oVuSnOK8KiktjiaUGd6s51V1xJBQIgBNjrFOximKE42WMqTLtAaImwFrNmh%2B3pnWJBv2TF2dMq%2FwMIfxAAGgw2Mzc0MjMxODM4MDUiDLnUer%2BHS1S9x47aYSrcA5xoTkxBsPn29nBS3lO87VEbtp3kBqtI8yQdo%2FZHSPF3Z%2BmucAQpVso4x1yWS6R0tOYSN9WNMAdq9tmjj0mEL5RpXuCkCfYFP7e2WZ8VGtZH8eFGi%2BE6Feirc0o6TJXELy6o%2Fo9MWsjRyVbTVql2DQLoTpUUF0o6QuD8S4vgEIj8XXsfCPPmfN2PoVegS1w%2Bz80V9OBxgqHq10sOL%2BjosnAeqJdEyVQEYQUyn%2Fjy3WhJjvL4zQrl4AL14lPlje2yvCVMQxhyEb8lnU04De6QpzayaEc7ZLmlkL0JWv6i%2F4CLu%2BUD5qReP5My8EzoqLrNWtDCOqnDowiQ09%2B8DKDQYE9F2M6FKQCkTEqHJkwuUGVRgttWPFx4hqH%2BG8TmqeZuWEQSC0SGhirXjAddI79y%2Bg1F1Ho7pvid8Bg%2FKW1J%2BAgjThTWTptgUgvvgcp%2FAV5VzFjKebAqee%2BmngOM5lEhYsGOnKzUvaHTo%2Fu6JtQUJMcUJPKJmlX7WQhslVJDEZx4ocKYFdIKjpzHEydeB3tIRSnGrYk51ObYjDIJyGhwTjBVCBWWKhYXnPdAjdoDbkcOj19fYUScpaNLQpfH243UUdtPMsoIaRp%2BGPwhHz01W6WaQpKRz8gMR1Pu%2BXjNMOey5bwGOqUBxsUSvI3ArciHBYusqtq1uHZoe%2FKYW5lmXZxpOK0PhHiFKytPdfIPG0M%2Fi%2FVBr7GKr%2FgREwllbFqaIwzKSrsOZVhBMsNl1WUrBRqDarX2gHYinPz2cde3iNHvQNL%2Fi1vylrwvDvSSukI6JNs8l%2Fps8Vx%2F86JNuTxXtag3nZQBntM4wJLYt2Y6YV1ELg1%2BTHNVDH8hGyJOfc2RZgQuonDWWezh8g9W&X-Amz-Signature=62b7262f6baa268a44297fb2871beebfcd54bd1c18d1d7d5a691fe0d0c7418a4&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Y373QQOQ%2F20250128%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250128T232133Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHcaCXVzLXdlc3QtMiJHMEUCIQDQNkLmkOei6vOav4oVuSnOK8KiktjiaUGd6s51V1xJBQIgBNjrFOximKE42WMqTLtAaImwFrNmh%2B3pnWJBv2TF2dMq%2FwMIfxAAGgw2Mzc0MjMxODM4MDUiDLnUer%2BHS1S9x47aYSrcA5xoTkxBsPn29nBS3lO87VEbtp3kBqtI8yQdo%2FZHSPF3Z%2BmucAQpVso4x1yWS6R0tOYSN9WNMAdq9tmjj0mEL5RpXuCkCfYFP7e2WZ8VGtZH8eFGi%2BE6Feirc0o6TJXELy6o%2Fo9MWsjRyVbTVql2DQLoTpUUF0o6QuD8S4vgEIj8XXsfCPPmfN2PoVegS1w%2Bz80V9OBxgqHq10sOL%2BjosnAeqJdEyVQEYQUyn%2Fjy3WhJjvL4zQrl4AL14lPlje2yvCVMQxhyEb8lnU04De6QpzayaEc7ZLmlkL0JWv6i%2F4CLu%2BUD5qReP5My8EzoqLrNWtDCOqnDowiQ09%2B8DKDQYE9F2M6FKQCkTEqHJkwuUGVRgttWPFx4hqH%2BG8TmqeZuWEQSC0SGhirXjAddI79y%2Bg1F1Ho7pvid8Bg%2FKW1J%2BAgjThTWTptgUgvvgcp%2FAV5VzFjKebAqee%2BmngOM5lEhYsGOnKzUvaHTo%2Fu6JtQUJMcUJPKJmlX7WQhslVJDEZx4ocKYFdIKjpzHEydeB3tIRSnGrYk51ObYjDIJyGhwTjBVCBWWKhYXnPdAjdoDbkcOj19fYUScpaNLQpfH243UUdtPMsoIaRp%2BGPwhHz01W6WaQpKRz8gMR1Pu%2BXjNMOey5bwGOqUBxsUSvI3ArciHBYusqtq1uHZoe%2FKYW5lmXZxpOK0PhHiFKytPdfIPG0M%2Fi%2FVBr7GKr%2FgREwllbFqaIwzKSrsOZVhBMsNl1WUrBRqDarX2gHYinPz2cde3iNHvQNL%2Fi1vylrwvDvSSukI6JNs8l%2Fps8Vx%2F86JNuTxXtag3nZQBntM4wJLYt2Y6YV1ELg1%2BTHNVDH8hGyJOfc2RZgQuonDWWezh8g9W&X-Amz-Signature=2ac1bb860afb85628b590fa154b2461acda83871f765023547e1dc4e829c1cf8&X-Amz-SignedHeaders=host&x-id=GetObject)


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

