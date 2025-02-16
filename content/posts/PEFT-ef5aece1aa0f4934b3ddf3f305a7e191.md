---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4666EL2JKAV%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250216T162619Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEDQaCXVzLXdlc3QtMiJIMEYCIQCZUggoC1tr4rpHiegBJJNN8%2FfOLdc6CZ5Oq8GvK8cBdQIhA\
  OT6eIHBPF2%2FNVju%2F%2BLVVGXv2l5mfP3gTbfMZFWGk5VXKv8DCF0QABoMNjM3NDIzMTgzODA1\
  Igzl3QVwuf%2B5aBLvlNkq3AN9UyIZjToOwj%2FEG9mJD31Z03LDkBLfyGM7BDh4C3x4B3XMrmrvy\
  VW46B2BWJEKzv6O8nvITcfQthhWbKAkojh9015gNcCW7%2FDYM25BKPQpLPpCLKITLJTXErhYgON%\
  2Fdb2Toidio2n3GEeSilut6T3rnkdHUo9JUJpWSv0w%2BvwAMnSxNN9VCcs07qrire3qvom0T7wT7\
  VErzgFhdTlZfY%2B7oH8oz8B1kIU9dhiVnRqTCp5ynPR%2FKJCBgkUNpMjUfrkaFvDTM8dfs%2BpJ\
  E9yJSZsyTkzjerE88n%2FPvJo0iqBrwWuVrx7OvxQFaLJc12tt8sRwFRRCaGBy%2Fvpg%2FnZC4Hu\
  t3apWBFcTrfhB51bFUzeuTeqDRG2yILfBtsv32THEF4N3ya1mApC9c9BSpcpe%2BbMwlDwVy9jRmZ\
  uU4aVzcgOATghsZ0NEUn01NLP3yG10Zs9NsfQr9kLMPOPNzYb2nx6tD9iFfKKNGyUuI0VZvsKbSdX\
  ETMwoa0AiO3h2DUDebPmZgtzVEkYRX5tmeQ4pr%2B6BNfz%2BOBxdQ7%2FR68SC8XyhC1Abu%2FWY\
  WKaJDmQlFzwvPGMW0fVrBzcudyC48FO%2FxRfAu7wAsEbxZA2mmlVUMzGFUKDcMBwW2T9YifUVIDC\
  En8e9BjqkAdMepDkThnBrRYLzLyK5m1PittzLyqMYATUjkahXrT67nfCHpMYwVq8h%2BLaDB2xXEC\
  DBYlAYexvB3rjXzDisz4X%2BvACo0NwK65Mom0v5sy3iR%2BcIpOgIXg9E%2BgyxLiJKWRiv8Sb9S\
  ApCl6AgeIT3Tyye8xkGPpeVTtL829aiRjVPnJtVDmSU536c0G19ndefG%2FFdsCR0Q6naRRP6lqHH\
  XEe0f4p5&X-Amz-Signature=e236aaeeaf38ac36662fc62e7f2512d91f9f04527e478b4069d5\
  e4ad212ff2e5&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4662VHM5OQW%2F20250216%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250216T162455Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJHMEUCIQDkHVfrIdS2tn0lrqWwO775laR366s\
        HYWqYSFJZ5oFauwIgMuD%2Bd8AmaF6tLKOiZrHWlh%2B1dg5uX1sr4YDbiJNyw2Iq%2FwMI\
        XRAAGgw2Mzc0MjMxODM4MDUiDB2AgOZwKukhCQ%2BVcircA82qIU81K5Qy3QLpARPAAqqE6\
        MoP3tNxfww7hkpyi6UD2vdKQHJDeghWjZT%2B4CghvMvtlNUks4PQNOc%2BEsUSeNVXJnT2\
        nMfQeODndyn3wiBSlIjB3ZucbyawtIy76uGTuEUg21qmWoWLHqamGvsUe3OYqLmjUVHSoHo\
        bWgI7IzmVXniFsZgRTF6Yb7pWZ74UN0MgHLRU4lWnAPn4Le%2FXh3wY51%2Fa26a3Vghu1j\
        1P8NoBt3BvorS0k7ZUaLjukqIx4%2Fa3DatR8bRQAHxXDLEaj9Rykiw4iWV97qxuqf3sEnX\
        8gbBgW%2BV7jyn3WFLOPxy1wYkVUGh7Fy2y4RiQTAT0zCd7XEEcgotO22ixYgZ4WRwifo4O\
        5Z0hJbVexewwXjM6CCCQM5SSMuO%2B%2Bf8Midmy0yG8W3MkxbEXuhKv4adVNmbsSi7w0PF\
        MW7zX7BLUY%2Fd5pUXirpN7XlMpxeSQeEQaKrTuhOhD9dR9P7MsS2qMt22ltDdTVT3KVtTl\
        L9%2BC7vn26gQiUI4E%2B35dXNfKSEB3NHrk11IYekXxUoeHDfvUHnf7Zfc76pI7LeJDuH%\
        2BN4kOhsdsqwjg0QHJRTIPULSCozWT1o00nwWB%2BQqbRkSZPYhQ3fX4j0AwUg%2FvUBcND\
        MImbx70GOqUBhKrgBAsSkx5yF7l16sG8P61ZQUvOQ%2FeYGZ0GtUgtwPTiIc%2BXN9yB7NY\
        %2FxfO8smNJCffCFM6gYJvRv0I%2BewOxl6s9T%2FxSY2K8U6eIjifhiGgiylZe5%2B%2BZ\
        Z9JvngzOIzhSJ4Eh1%2Ff7uLtBMoNx1b3HyAX6iSgHL0JEIEh%2B%2FsoRxnmHiJt0rTbL0\
        pYxVFlpPlb2yVNj0uEK68RD1eT7THuhMLzG0NOi&X-Amz-Signature=094486df6324a24\
        cb4ea9497cd9197be14688fbae13a28e94d36c643e827373f&X-Amz-SignedHeaders=h\
        ost&x-id=GetObject"
      expiry_time: "2025-02-16T17:24:55.428Z"
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
UPDATE_TIME: "2025-02-16T16:26:27.239Z"
EXPIRY_TIME: "2025-02-16T17:26:15.088Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QK4DFSB4%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T162615Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJIMEYCIQCIeHB5gC6lyYg8WhTPYLzwM4OENxDrmIywRaQlYFBCQQIhANowd7vuTnta7w3IlOhvl0JBzeJ0pr3UREvhl0hdy1BHKv8DCF0QABoMNjM3NDIzMTgzODA1IgzIoBwb6VJnFUcfUBQq3AMLOco7KkaBpzoPGP%2FC3l1eFLvy4SJyIZGoTvR5K9taNLXUVe9dAEIXoFyMF%2FGd5pmoefIh2gxXrekQplVDVADeOjGMAwP82mGUfWyntf37wAZF4d4%2FScZWKEgd74n76s%2BWNWrKq6b8xhM2n81MK%2FSVOAP%2FaeknVkuYQeaEXyil5LHWKHMi8VNlcP%2FZCBITxfqejbLU%2FigSd%2FVmMT%2Fld7WY8whAYwCkj0fE7mZpODqe5OVYfHfIkttu26RW2cMQhhBQtcbvY1sd0Ix6Bw%2BP3RoErr7aSmgfafZo2c68w6HyQE5PORAT%2Fj%2BwF43dUXdAuVtYuX12UMqVCp5cj5s%2BD%2FloHkusgj6vcmFJr6l8wDuS%2FYQGkiWfzEG0bDxNSPkzdseXYuMsT6bEYpfpF10T4%2B6XsX5uZTpEU%2FYUaR1N3Q3gjJzdF8kR582B1fzDcTQ7y8Uwo4v%2FEWVkjsw09w4YH%2Fb4PbHw2HQx3sG%2F4Rpr2ysoDoMrQc9yC7B0ihMr%2FPcre2QGdeUEUD3gMa9u57SBcAph4ICUmjfB1RHLM3juowh3R04ygr8VQDDmfoYYD2Km6mQxcYLcewz8TU6DVQteeMYslqnUVW8uWcXi1oM9YaEp4TiD595XGjPxOWnhlTD6mMe9BjqkAfd0Y6aWXWxuH4dNPc96yLJc6Sit3OeKb46ulCA2EzxPY3wKVFuxb27hyHm9Ab8s6vjcdBunRQgBKYjjJYipuiZL77y2W8NWXhzG49J9n0WS6O11GIW0cXiVv%2F4Xg5bP%2FaARob0ZGIgECgUqNnGp9Sk5OB7XwlEuxEdSWoQApMn7DlGYxdMftzNyxPeahbr7dwImePMgK%2FTGfQG%2FpghgY7qDx8%2FA&X-Amz-Signature=20722e53b49c25531c91781bff6f1d5726edb1a8f3e791f2b157e040bcb538b1&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QK4DFSB4%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T162616Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJIMEYCIQCIeHB5gC6lyYg8WhTPYLzwM4OENxDrmIywRaQlYFBCQQIhANowd7vuTnta7w3IlOhvl0JBzeJ0pr3UREvhl0hdy1BHKv8DCF0QABoMNjM3NDIzMTgzODA1IgzIoBwb6VJnFUcfUBQq3AMLOco7KkaBpzoPGP%2FC3l1eFLvy4SJyIZGoTvR5K9taNLXUVe9dAEIXoFyMF%2FGd5pmoefIh2gxXrekQplVDVADeOjGMAwP82mGUfWyntf37wAZF4d4%2FScZWKEgd74n76s%2BWNWrKq6b8xhM2n81MK%2FSVOAP%2FaeknVkuYQeaEXyil5LHWKHMi8VNlcP%2FZCBITxfqejbLU%2FigSd%2FVmMT%2Fld7WY8whAYwCkj0fE7mZpODqe5OVYfHfIkttu26RW2cMQhhBQtcbvY1sd0Ix6Bw%2BP3RoErr7aSmgfafZo2c68w6HyQE5PORAT%2Fj%2BwF43dUXdAuVtYuX12UMqVCp5cj5s%2BD%2FloHkusgj6vcmFJr6l8wDuS%2FYQGkiWfzEG0bDxNSPkzdseXYuMsT6bEYpfpF10T4%2B6XsX5uZTpEU%2FYUaR1N3Q3gjJzdF8kR582B1fzDcTQ7y8Uwo4v%2FEWVkjsw09w4YH%2Fb4PbHw2HQx3sG%2F4Rpr2ysoDoMrQc9yC7B0ihMr%2FPcre2QGdeUEUD3gMa9u57SBcAph4ICUmjfB1RHLM3juowh3R04ygr8VQDDmfoYYD2Km6mQxcYLcewz8TU6DVQteeMYslqnUVW8uWcXi1oM9YaEp4TiD595XGjPxOWnhlTD6mMe9BjqkAfd0Y6aWXWxuH4dNPc96yLJc6Sit3OeKb46ulCA2EzxPY3wKVFuxb27hyHm9Ab8s6vjcdBunRQgBKYjjJYipuiZL77y2W8NWXhzG49J9n0WS6O11GIW0cXiVv%2F4Xg5bP%2FaARob0ZGIgECgUqNnGp9Sk5OB7XwlEuxEdSWoQApMn7DlGYxdMftzNyxPeahbr7dwImePMgK%2FTGfQG%2FpghgY7qDx8%2FA&X-Amz-Signature=40de1c183493b065c001f8d29da10156acbb0fa09302da38afec9c7e8eed9ef9&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QK4DFSB4%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T162616Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJIMEYCIQCIeHB5gC6lyYg8WhTPYLzwM4OENxDrmIywRaQlYFBCQQIhANowd7vuTnta7w3IlOhvl0JBzeJ0pr3UREvhl0hdy1BHKv8DCF0QABoMNjM3NDIzMTgzODA1IgzIoBwb6VJnFUcfUBQq3AMLOco7KkaBpzoPGP%2FC3l1eFLvy4SJyIZGoTvR5K9taNLXUVe9dAEIXoFyMF%2FGd5pmoefIh2gxXrekQplVDVADeOjGMAwP82mGUfWyntf37wAZF4d4%2FScZWKEgd74n76s%2BWNWrKq6b8xhM2n81MK%2FSVOAP%2FaeknVkuYQeaEXyil5LHWKHMi8VNlcP%2FZCBITxfqejbLU%2FigSd%2FVmMT%2Fld7WY8whAYwCkj0fE7mZpODqe5OVYfHfIkttu26RW2cMQhhBQtcbvY1sd0Ix6Bw%2BP3RoErr7aSmgfafZo2c68w6HyQE5PORAT%2Fj%2BwF43dUXdAuVtYuX12UMqVCp5cj5s%2BD%2FloHkusgj6vcmFJr6l8wDuS%2FYQGkiWfzEG0bDxNSPkzdseXYuMsT6bEYpfpF10T4%2B6XsX5uZTpEU%2FYUaR1N3Q3gjJzdF8kR582B1fzDcTQ7y8Uwo4v%2FEWVkjsw09w4YH%2Fb4PbHw2HQx3sG%2F4Rpr2ysoDoMrQc9yC7B0ihMr%2FPcre2QGdeUEUD3gMa9u57SBcAph4ICUmjfB1RHLM3juowh3R04ygr8VQDDmfoYYD2Km6mQxcYLcewz8TU6DVQteeMYslqnUVW8uWcXi1oM9YaEp4TiD595XGjPxOWnhlTD6mMe9BjqkAfd0Y6aWXWxuH4dNPc96yLJc6Sit3OeKb46ulCA2EzxPY3wKVFuxb27hyHm9Ab8s6vjcdBunRQgBKYjjJYipuiZL77y2W8NWXhzG49J9n0WS6O11GIW0cXiVv%2F4Xg5bP%2FaARob0ZGIgECgUqNnGp9Sk5OB7XwlEuxEdSWoQApMn7DlGYxdMftzNyxPeahbr7dwImePMgK%2FTGfQG%2FpghgY7qDx8%2FA&X-Amz-Signature=e7562fa5822fa62e33f6229dd1dbeb4886fec58901d26bc871210dac3cb30c8f&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QK4DFSB4%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T162616Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJIMEYCIQCIeHB5gC6lyYg8WhTPYLzwM4OENxDrmIywRaQlYFBCQQIhANowd7vuTnta7w3IlOhvl0JBzeJ0pr3UREvhl0hdy1BHKv8DCF0QABoMNjM3NDIzMTgzODA1IgzIoBwb6VJnFUcfUBQq3AMLOco7KkaBpzoPGP%2FC3l1eFLvy4SJyIZGoTvR5K9taNLXUVe9dAEIXoFyMF%2FGd5pmoefIh2gxXrekQplVDVADeOjGMAwP82mGUfWyntf37wAZF4d4%2FScZWKEgd74n76s%2BWNWrKq6b8xhM2n81MK%2FSVOAP%2FaeknVkuYQeaEXyil5LHWKHMi8VNlcP%2FZCBITxfqejbLU%2FigSd%2FVmMT%2Fld7WY8whAYwCkj0fE7mZpODqe5OVYfHfIkttu26RW2cMQhhBQtcbvY1sd0Ix6Bw%2BP3RoErr7aSmgfafZo2c68w6HyQE5PORAT%2Fj%2BwF43dUXdAuVtYuX12UMqVCp5cj5s%2BD%2FloHkusgj6vcmFJr6l8wDuS%2FYQGkiWfzEG0bDxNSPkzdseXYuMsT6bEYpfpF10T4%2B6XsX5uZTpEU%2FYUaR1N3Q3gjJzdF8kR582B1fzDcTQ7y8Uwo4v%2FEWVkjsw09w4YH%2Fb4PbHw2HQx3sG%2F4Rpr2ysoDoMrQc9yC7B0ihMr%2FPcre2QGdeUEUD3gMa9u57SBcAph4ICUmjfB1RHLM3juowh3R04ygr8VQDDmfoYYD2Km6mQxcYLcewz8TU6DVQteeMYslqnUVW8uWcXi1oM9YaEp4TiD595XGjPxOWnhlTD6mMe9BjqkAfd0Y6aWXWxuH4dNPc96yLJc6Sit3OeKb46ulCA2EzxPY3wKVFuxb27hyHm9Ab8s6vjcdBunRQgBKYjjJYipuiZL77y2W8NWXhzG49J9n0WS6O11GIW0cXiVv%2F4Xg5bP%2FaARob0ZGIgECgUqNnGp9Sk5OB7XwlEuxEdSWoQApMn7DlGYxdMftzNyxPeahbr7dwImePMgK%2FTGfQG%2FpghgY7qDx8%2FA&X-Amz-Signature=a3e24edcb313dff5cb9e21af23d3ac8b3e6803e6273be736d46853cc23a8468b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QK4DFSB4%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T162616Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJIMEYCIQCIeHB5gC6lyYg8WhTPYLzwM4OENxDrmIywRaQlYFBCQQIhANowd7vuTnta7w3IlOhvl0JBzeJ0pr3UREvhl0hdy1BHKv8DCF0QABoMNjM3NDIzMTgzODA1IgzIoBwb6VJnFUcfUBQq3AMLOco7KkaBpzoPGP%2FC3l1eFLvy4SJyIZGoTvR5K9taNLXUVe9dAEIXoFyMF%2FGd5pmoefIh2gxXrekQplVDVADeOjGMAwP82mGUfWyntf37wAZF4d4%2FScZWKEgd74n76s%2BWNWrKq6b8xhM2n81MK%2FSVOAP%2FaeknVkuYQeaEXyil5LHWKHMi8VNlcP%2FZCBITxfqejbLU%2FigSd%2FVmMT%2Fld7WY8whAYwCkj0fE7mZpODqe5OVYfHfIkttu26RW2cMQhhBQtcbvY1sd0Ix6Bw%2BP3RoErr7aSmgfafZo2c68w6HyQE5PORAT%2Fj%2BwF43dUXdAuVtYuX12UMqVCp5cj5s%2BD%2FloHkusgj6vcmFJr6l8wDuS%2FYQGkiWfzEG0bDxNSPkzdseXYuMsT6bEYpfpF10T4%2B6XsX5uZTpEU%2FYUaR1N3Q3gjJzdF8kR582B1fzDcTQ7y8Uwo4v%2FEWVkjsw09w4YH%2Fb4PbHw2HQx3sG%2F4Rpr2ysoDoMrQc9yC7B0ihMr%2FPcre2QGdeUEUD3gMa9u57SBcAph4ICUmjfB1RHLM3juowh3R04ygr8VQDDmfoYYD2Km6mQxcYLcewz8TU6DVQteeMYslqnUVW8uWcXi1oM9YaEp4TiD595XGjPxOWnhlTD6mMe9BjqkAfd0Y6aWXWxuH4dNPc96yLJc6Sit3OeKb46ulCA2EzxPY3wKVFuxb27hyHm9Ab8s6vjcdBunRQgBKYjjJYipuiZL77y2W8NWXhzG49J9n0WS6O11GIW0cXiVv%2F4Xg5bP%2FaARob0ZGIgECgUqNnGp9Sk5OB7XwlEuxEdSWoQApMn7DlGYxdMftzNyxPeahbr7dwImePMgK%2FTGfQG%2FpghgY7qDx8%2FA&X-Amz-Signature=5ffe91dcba16878c1a1f8350d1b7c723b98539c42b384d984ee31f32e5466dd6&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46644OI2A3C%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T162616Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJIMEYCIQDeHFPVCy4Rk3YM6noILmpbjACMqpcvL%2BOXHn%2Bqjtx2kQIhAMZADSxhdB5GIfnYMp9cfJDOPqnv%2FhI6bPM5RzA%2BkbkTKv8DCF0QABoMNjM3NDIzMTgzODA1IgxXQQ%2FkU80DhpCOwFkq3APQCNcU3AXw8FH2Kgv6obdJagmKNKBFlY22twQHBRhFavEeDxKj3Zsa%2Ba2oltpybun5Y%2Faaat5jqD5yS9pXHPxlrAvD2j9kNwqS7WrjagaNKZ%2FkL46kmQkHDtm70S4X8vomrt1e%2BfW175%2BcZ9M8lvEcY4vUcebURh3UdE%2BPYJZcaqLZPKzjf1oQXyiZhBZcFJhPvNPbh5PAvbI2P0BULmCT9m1q%2Fgmdzx43PqXXS3PVFCzegf4prF9iir0PxVVYleuAwq9uQXd6DsEfAhL4abBUKKOipO%2B%2BXywfnJqfnlqPIM6rDlTrGckl5f0eKIAuWjUhMX5KyrAkXmCMiOfDXxx%2BVsX8EeuYWPCYNSHcK%2F%2Bd9xtI1EJDXKe8xKHtRxKX8JRmmEKbokMTNtN4o5BSxgqCBmU1n3MZSpVL8P99vcsi84VontzJAIqxVP7ZU64qwjha4KJbgz6XZ09B3xnUTkpUAnG6hynS%2B0aN4kHWVmHpt%2BsaSFyEtEinsphV9%2BHTQmHtSPGAao1iLk1ZSpFiPwjbHhgEgOCznYQHAMZ46fNEGZxbYCHB7tRL31rW3A0t7Qk4r3VBbUxK6XL5pCUjQZ2O0QNYEMEltmtLySKy0QX7DXPvNujutuZMEZOoljCCnMe9BjqkARxv39YySWcq013hlKNYV3wYlgPK8jhZWygNilhBVR%2BE%2BfD9bsLlXyCpNtUOamgROBnfaDlAYtXphtm3RnKnZE9Z1fr63jrSfOMO9NAD3PjZl6xJco1cqznjFMIGYUV%2FLMPf6%2FqHWaGYcNM5kunNUyb4xpfJNfgYJSEI8m7xoFS4pGbVpR9Na%2F2LnjtYnsjEokWRhJxoB9rQT84fxholTxekYiuT&X-Amz-Signature=40bc55c7d600dd56a1bbb27b89fe24fd581eaeb8bdb2a6d1756bb6b54cf80470&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664K3YL4UO%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T162619Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJHMEUCIQCWKQXvOZxMQInPtdsLIyQ5LDoje7pkz%2BHAhyC8Y8x70wIgU6lAgxkWnqNuO6fFOG8g2peZ2aN7yQDbA%2FgtrEOFdYoq%2FwMIXRAAGgw2Mzc0MjMxODM4MDUiDLj6r5fv%2Fl1yXZECRircA%2FBw8csYxkx8ee9zSvwdRw1cS7fyI1DVgXGoDSUNnkr8l2BJiQpU3Su%2BNsKwp1V80TfjjCMa%2BfOC76GSG2RxImThGJ5tmqKQlR8C47hasYPY%2FkOFZRysyjAFR58kTTvdCXquuif9cHsugSalb0YKgDsaaZ4B1JA3%2FdoSdRwujVsrpmfEd1hqWh%2F4KY0HpzGEJukhY6e8bF%2FHwhtpdW8ycr%2FLynuocByV9gvyS0oeZ%2BLj54u3nyHtSvVtEHNv1WT3rVsm%2FkWnZVgfR1HF%2BVNyEpJJYfm5V1JJZwGuridZ5TeObFMcQ14W%2FODYMKJDx%2FgIBauifDnLK8%2BMG0MVrsK8Viu4h%2BJMB7PhN0DFD6NVZ%2FX%2FMqS2o4B0FjzR%2B7ASIz9661wNW7EdExlblQfnCwOib8tLjGW%2FW0fNYvwQ5GJgi4pN36Mx13Kr8epJro%2F7s86Jt4ers4L5YgveXbMvLJX6wGNH%2Bza5G6NubVhtG8Bz0njnEhIdOWg%2B%2FX7n1KaJTNY%2FnLd%2BlnAFceS34pOIpxUY%2FAhI9BHSU2YGSDWaAArNG5hsJK9d38aqB%2FjZaUgaWIzkMm%2BJP04aLtdSPmdjfjKR5BybSVluyAXX%2BVMIua2XJRiVIMgGYoXwmdpnB%2FV%2BMM%2Bax70GOqUB0FNIKA%2F%2Bh9xz9FcskrkoXBxhN%2Bq0Q1hCUNHZG111DjuBgrQkDlmGMWevJelNtCq0Fl5PoYFr6EK8Em33G1OFFsq9Qf0AMbs%2BpwtoPX2MYCJ1tMGCpdGITzMK%2B7yoscfh%2FFcisbKVuFjpU3doKz6EffVREhZ3fLDmGuYpTIWW2ggI0wkh5slYUkqVNhE0Y8wmTIVImzDwDHqWdlhjMgV9Ow1jL1eH&X-Amz-Signature=081217941311263db3b70f43413220204c397e87af89bc566f67fa73d3d7d850&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QK4DFSB4%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T162616Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJIMEYCIQCIeHB5gC6lyYg8WhTPYLzwM4OENxDrmIywRaQlYFBCQQIhANowd7vuTnta7w3IlOhvl0JBzeJ0pr3UREvhl0hdy1BHKv8DCF0QABoMNjM3NDIzMTgzODA1IgzIoBwb6VJnFUcfUBQq3AMLOco7KkaBpzoPGP%2FC3l1eFLvy4SJyIZGoTvR5K9taNLXUVe9dAEIXoFyMF%2FGd5pmoefIh2gxXrekQplVDVADeOjGMAwP82mGUfWyntf37wAZF4d4%2FScZWKEgd74n76s%2BWNWrKq6b8xhM2n81MK%2FSVOAP%2FaeknVkuYQeaEXyil5LHWKHMi8VNlcP%2FZCBITxfqejbLU%2FigSd%2FVmMT%2Fld7WY8whAYwCkj0fE7mZpODqe5OVYfHfIkttu26RW2cMQhhBQtcbvY1sd0Ix6Bw%2BP3RoErr7aSmgfafZo2c68w6HyQE5PORAT%2Fj%2BwF43dUXdAuVtYuX12UMqVCp5cj5s%2BD%2FloHkusgj6vcmFJr6l8wDuS%2FYQGkiWfzEG0bDxNSPkzdseXYuMsT6bEYpfpF10T4%2B6XsX5uZTpEU%2FYUaR1N3Q3gjJzdF8kR582B1fzDcTQ7y8Uwo4v%2FEWVkjsw09w4YH%2Fb4PbHw2HQx3sG%2F4Rpr2ysoDoMrQc9yC7B0ihMr%2FPcre2QGdeUEUD3gMa9u57SBcAph4ICUmjfB1RHLM3juowh3R04ygr8VQDDmfoYYD2Km6mQxcYLcewz8TU6DVQteeMYslqnUVW8uWcXi1oM9YaEp4TiD595XGjPxOWnhlTD6mMe9BjqkAfd0Y6aWXWxuH4dNPc96yLJc6Sit3OeKb46ulCA2EzxPY3wKVFuxb27hyHm9Ab8s6vjcdBunRQgBKYjjJYipuiZL77y2W8NWXhzG49J9n0WS6O11GIW0cXiVv%2F4Xg5bP%2FaARob0ZGIgECgUqNnGp9Sk5OB7XwlEuxEdSWoQApMn7DlGYxdMftzNyxPeahbr7dwImePMgK%2FTGfQG%2FpghgY7qDx8%2FA&X-Amz-Signature=23aef6ce912a4a7a99d12ab460482e475b6f97c85e38583cae3a046efd485d67&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QK4DFSB4%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T162616Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJIMEYCIQCIeHB5gC6lyYg8WhTPYLzwM4OENxDrmIywRaQlYFBCQQIhANowd7vuTnta7w3IlOhvl0JBzeJ0pr3UREvhl0hdy1BHKv8DCF0QABoMNjM3NDIzMTgzODA1IgzIoBwb6VJnFUcfUBQq3AMLOco7KkaBpzoPGP%2FC3l1eFLvy4SJyIZGoTvR5K9taNLXUVe9dAEIXoFyMF%2FGd5pmoefIh2gxXrekQplVDVADeOjGMAwP82mGUfWyntf37wAZF4d4%2FScZWKEgd74n76s%2BWNWrKq6b8xhM2n81MK%2FSVOAP%2FaeknVkuYQeaEXyil5LHWKHMi8VNlcP%2FZCBITxfqejbLU%2FigSd%2FVmMT%2Fld7WY8whAYwCkj0fE7mZpODqe5OVYfHfIkttu26RW2cMQhhBQtcbvY1sd0Ix6Bw%2BP3RoErr7aSmgfafZo2c68w6HyQE5PORAT%2Fj%2BwF43dUXdAuVtYuX12UMqVCp5cj5s%2BD%2FloHkusgj6vcmFJr6l8wDuS%2FYQGkiWfzEG0bDxNSPkzdseXYuMsT6bEYpfpF10T4%2B6XsX5uZTpEU%2FYUaR1N3Q3gjJzdF8kR582B1fzDcTQ7y8Uwo4v%2FEWVkjsw09w4YH%2Fb4PbHw2HQx3sG%2F4Rpr2ysoDoMrQc9yC7B0ihMr%2FPcre2QGdeUEUD3gMa9u57SBcAph4ICUmjfB1RHLM3juowh3R04ygr8VQDDmfoYYD2Km6mQxcYLcewz8TU6DVQteeMYslqnUVW8uWcXi1oM9YaEp4TiD595XGjPxOWnhlTD6mMe9BjqkAfd0Y6aWXWxuH4dNPc96yLJc6Sit3OeKb46ulCA2EzxPY3wKVFuxb27hyHm9Ab8s6vjcdBunRQgBKYjjJYipuiZL77y2W8NWXhzG49J9n0WS6O11GIW0cXiVv%2F4Xg5bP%2FaARob0ZGIgECgUqNnGp9Sk5OB7XwlEuxEdSWoQApMn7DlGYxdMftzNyxPeahbr7dwImePMgK%2FTGfQG%2FpghgY7qDx8%2FA&X-Amz-Signature=d8344b1ba0951a1c1e2acaad984cc894930673f73f89c7b6bfe99e7135a83070&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QK4DFSB4%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T162616Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJIMEYCIQCIeHB5gC6lyYg8WhTPYLzwM4OENxDrmIywRaQlYFBCQQIhANowd7vuTnta7w3IlOhvl0JBzeJ0pr3UREvhl0hdy1BHKv8DCF0QABoMNjM3NDIzMTgzODA1IgzIoBwb6VJnFUcfUBQq3AMLOco7KkaBpzoPGP%2FC3l1eFLvy4SJyIZGoTvR5K9taNLXUVe9dAEIXoFyMF%2FGd5pmoefIh2gxXrekQplVDVADeOjGMAwP82mGUfWyntf37wAZF4d4%2FScZWKEgd74n76s%2BWNWrKq6b8xhM2n81MK%2FSVOAP%2FaeknVkuYQeaEXyil5LHWKHMi8VNlcP%2FZCBITxfqejbLU%2FigSd%2FVmMT%2Fld7WY8whAYwCkj0fE7mZpODqe5OVYfHfIkttu26RW2cMQhhBQtcbvY1sd0Ix6Bw%2BP3RoErr7aSmgfafZo2c68w6HyQE5PORAT%2Fj%2BwF43dUXdAuVtYuX12UMqVCp5cj5s%2BD%2FloHkusgj6vcmFJr6l8wDuS%2FYQGkiWfzEG0bDxNSPkzdseXYuMsT6bEYpfpF10T4%2B6XsX5uZTpEU%2FYUaR1N3Q3gjJzdF8kR582B1fzDcTQ7y8Uwo4v%2FEWVkjsw09w4YH%2Fb4PbHw2HQx3sG%2F4Rpr2ysoDoMrQc9yC7B0ihMr%2FPcre2QGdeUEUD3gMa9u57SBcAph4ICUmjfB1RHLM3juowh3R04ygr8VQDDmfoYYD2Km6mQxcYLcewz8TU6DVQteeMYslqnUVW8uWcXi1oM9YaEp4TiD595XGjPxOWnhlTD6mMe9BjqkAfd0Y6aWXWxuH4dNPc96yLJc6Sit3OeKb46ulCA2EzxPY3wKVFuxb27hyHm9Ab8s6vjcdBunRQgBKYjjJYipuiZL77y2W8NWXhzG49J9n0WS6O11GIW0cXiVv%2F4Xg5bP%2FaARob0ZGIgECgUqNnGp9Sk5OB7XwlEuxEdSWoQApMn7DlGYxdMftzNyxPeahbr7dwImePMgK%2FTGfQG%2FpghgY7qDx8%2FA&X-Amz-Signature=b99791dc748644a41157a716f15031e5f93da7daefc42964ce11f14da65d9d6e&X-Amz-SignedHeaders=host&x-id=GetObject)


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

