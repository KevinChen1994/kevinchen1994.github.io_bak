---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4666K47RWYD%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250220T183318Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEJr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD7%2F0XQWBI8%2F%2\
  FVOpEFW8tId7kyA6XXPgCd%2Fp%2BsCjPEz1wIgF4QRjhVJQ6qQNa60ykOGHKz08isDjGYPOJisNu\
  wAO40qiAQIw%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNNeNJjZ%\
  2Fzc6b1KeHyrcA3XaSKDW7etX5cHPKOBjZprNd0d8vI78DMl%2FJmptAOFE98zhcHCMoN2gMlCGoj\
  wfZijgKYrjpGYQSkUYnOBs7FBqz7uDafoWE4vCXZfoKjk6C2YGjjmRgy1tqzNe4zAI3LNjU9i8Vx%\
  2BYlGeOwC1ouTCoKFllyATfqVK1%2Bovk1HEXj2TJFTaC0Ith8rnljuxhyr0NxkUClqMyGV4ftwHY\
  T4V7gG2ppgwgTWT4Uc84lryA3w4ei9nZLW51ScVHRFWMWCWFqeWDOEDJ2BmDNnW1awrhgagisqAnJ\
  F%2BTWaCAXLc3Z5BwKVWsA3x8yGzwwqxGZJh1pQcYyLZhkCx%2FTE9SqgvK5%2FpGvp0UQYp%2FfX\
  xa9Vd3v7TEiqfD1dO9puTf%2Fdgfz8OKgMRbAYqh561Uw6Bpsuaek3VrhfQL8rxCODeFgsxvpejD1\
  8K65l69zuKRGFLFCH0rrH5yMu1YBtazNYg0Q5s6wxf0BeGrMP86mApkmRMh2Mt33mD8W%2FqrWWft\
  T8aoIwafeVnC6R8o2%2FEdLsEM9W%2B42CTSi8mqG84WO1IodMPUQ1Rek%2BKzqaSVAiZfd6rI9cV\
  jkgh5KK3RadofLccbVJ1uKfamM81cBN1jJIlpDGTmwqnwabOXAUUkO1LKMODR3b0GOqUB8yiQDaRD\
  pkm5h13W7WX%2BOWfsY%2BiVbxiZCapy8tJAN5RD7dbMI1YQv4cF4omXm8BHcOGIohuviTPk%2B1J\
  W9MbpNbSUpzBfevt97%2FGltJ0mDhvUi0LemLqERlYyXbnsLLCcHxpkVjEd%2BWY6ydgiVIAmZ5uR\
  XC1RN%2FiZGul3PvBkcYyqVbAkwZNsMqx%2BFqkLcI335fpCeGwcFxum%2F9yX60gl1i1ckaZI&X-\
  Amz-Signature=07aa6a518cf9104e5b6521fe518739ac27d48687d04a57daefc924918730264\
  1&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466YLQUJCMT%2F20250220%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250220T183110Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEJr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEY\
        CIQCAeEYeqvGAUqQU3%2BPhqQ0Y6IJ9S34rMv0fBJvAzwOPGQIhAICUnaYFjO9d6KQB1NHz\
        S%2B%2BNf5A3tMKlPCURuHv8ewudKogECMP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABo\
        MNjM3NDIzMTgzODA1IgztiY%2FipIFbcj%2BVvU4q3ANekyjM8sY3EyupBmUiXbkjFCTQ8s\
        kBLWp5BOvEKdNHDpeZk0IHeD58Qqgx2WYZLAOz5IweXxNejK4Kzv%2Fr2mVKpkMlJE0ffnC\
        9rbHKoDj7HTeRnNNMk5fO7ETVfhGQkUDiRTJQxTHEIks4KAKp7ikrGFHkjIJGBS8sVDXpRa\
        0gFqrhJ9ccSTf%2BTA6rYL%2BS7fSPE1RkVY8wOsLnBf9XmTX5N4iquLc1vBtOxGMRvp1Wr\
        KiukiWsDlMHV3e5bImm198d8wR2skFFhCQIihJp9hAJPpWz98JbnJLoPdykxYihmzVHvzW5\
        yak%2Ff%2BVPmL0sxiB14vEk9qd8%2B%2BgQa86ykYZIGcLLwlqOYUN3beUya3XmdKRBImN\
        ApjjFzOh9AW4n8wQ%2B%2FCM3yc8%2BPfL0JH600lwCicFIdXjnA22kn6ozFwpokgl2LTu6\
        OS3Q7cJ93XE4ARksHLP0gSZkeCkORIu7o4yTBpMg%2BPnsl5XE35HqHPDBdrSaA1QIzx1uP\
        EgXkN%2BmV%2F%2FpOyEApQXGPEz%2BiJF%2BxIBGjB0HTDtthXzEjncUlJrxxPpYwDFE4J\
        drn3D7ehAw4%2FoIWh8VFSaq9qQQbPsOr2IhTf85uz10gDktAqGTy7lUfrKXhRWwg0HQdXC\
        tCDC10t29BjqkAaCKdO0D7bFRaX%2BK9OAKA0EdhqfAm00z2c2pr6hdVITAXuo5nINcQ3oH\
        FL9xmPRVujwyOmV94OKblAf%2B%2BR6xRC%2F%2FTvAfTWEGHIM6B3TzG6qX6g49DGAawEw\
        Ef97XCXjNbf3hcEFG87rcg5qLqZ%2BC8hHWSVif8thmuwUMM8F61%2BRBpIN3aw9gFUq9qV\
        495qPjHm%2BKLOcqqpJBlHTRgOLy%2FIr7zt4M&X-Amz-Signature=2e3dd9781f3fd1da\
        4e9ca573bab8730cfe12795e737d0b29617215d1ef25ad15&X-Amz-SignedHeaders=ho\
        st&x-id=GetObject"
      expiry_time: "2025-02-20T19:31:10.899Z"
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
UPDATE_TIME: "2025-02-20T18:33:30.855Z"
EXPIRY_TIME: "2025-02-20T19:33:14.034Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665VRC7YIZ%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T183314Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBgzh8NY7t17OefxLqY%2F4Th25BgMGpmZm92klF10mjzEAiEAj2esZ5H6ujqA%2FFvNsZV4itQhRrE83bOwYjxpjxkGDNMqiAQIw%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDFVwqIPvLT775UDd3ircAyzgdoihmBW5Sf%2B1QSVzuYJ%2Brd8qkN3lCrD%2BviQAnGWnsuMrOVoDihnmLFNLLt95Z1QSuPYJJMKNPlt%2FBl1HtvBNaXZxAsJTRnQy9edZstLLFaRYj%2FFQEvGB0hIIkt275kGpPQVXBIya4p5bD1v%2BWzOLGOlxQY%2BHeRhgPkMuzqZDuCo0kTXePuVjbDaPN1YsBKmGP8LhflGKxiKwH44YM0twI0PiMJcMdvef0FQKu0vOYKcwqQE07%2FsTZzTeyQ90fc1sxRA0KVPZGcafwKYhZOIVbTXuP6bH8E6vc8DQZu3DDJywUgigXF6JvUkvwxCdpU6PNwzHND9q9jL3Q4GL1uzo6vOtQDHQ5Ug6acQEEBfb7hQu9cNcYoeyPoY9VWqW2dcpQ1T0aqQF%2FkJT20YBxIa%2BcTH3FSAequCewBrWlT3Ps6FmTEKwSWT6M9nNARqfKL%2FmLlY%2BEWAZZ3OuVOBnSZu1uSoSbbIDh3pjxxFildcUAsZ%2B1TI4Lds5fzK1NjrBvWFlfd6mFTneuXL3AxJCUFQCgMKe1vTJmqQ7mA64y9B87%2F%2BbyFFC%2BkxKWJtNCjf5R%2FVJN4Zy1gbrGh5lunJVeE%2FzI7PLm2aSFhhbnkKPnbnrC4QCWSw%2BQ%2BvxBJORMPrQ3b0GOqUBeeM3GGSmf9x72MWFx7pgHcQmtTJBE0ldrkeNGACXJv4zHK66Wzubl6DCIO1whFzKE2vEns%2BATt1r%2FentCeVf2hEiBTGkzPIda%2FiH8qeC9ChvDFWlAC4XNs9nanYjJ2YC0U6ZJf1I0DbwyRXm0MGOhEo3Mvx01yvMyOeyNeufIvNVBoJ7IS%2F0XaxQu7Xt4aQLBv%2Feewxq8XArfis%2BYmYD7%2BzEBpg2&X-Amz-Signature=89b10049826b8feb03d1b7ebd090e99bb5d4ba53cda87823b037a629ff8e401e&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665VRC7YIZ%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T183314Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBgzh8NY7t17OefxLqY%2F4Th25BgMGpmZm92klF10mjzEAiEAj2esZ5H6ujqA%2FFvNsZV4itQhRrE83bOwYjxpjxkGDNMqiAQIw%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDFVwqIPvLT775UDd3ircAyzgdoihmBW5Sf%2B1QSVzuYJ%2Brd8qkN3lCrD%2BviQAnGWnsuMrOVoDihnmLFNLLt95Z1QSuPYJJMKNPlt%2FBl1HtvBNaXZxAsJTRnQy9edZstLLFaRYj%2FFQEvGB0hIIkt275kGpPQVXBIya4p5bD1v%2BWzOLGOlxQY%2BHeRhgPkMuzqZDuCo0kTXePuVjbDaPN1YsBKmGP8LhflGKxiKwH44YM0twI0PiMJcMdvef0FQKu0vOYKcwqQE07%2FsTZzTeyQ90fc1sxRA0KVPZGcafwKYhZOIVbTXuP6bH8E6vc8DQZu3DDJywUgigXF6JvUkvwxCdpU6PNwzHND9q9jL3Q4GL1uzo6vOtQDHQ5Ug6acQEEBfb7hQu9cNcYoeyPoY9VWqW2dcpQ1T0aqQF%2FkJT20YBxIa%2BcTH3FSAequCewBrWlT3Ps6FmTEKwSWT6M9nNARqfKL%2FmLlY%2BEWAZZ3OuVOBnSZu1uSoSbbIDh3pjxxFildcUAsZ%2B1TI4Lds5fzK1NjrBvWFlfd6mFTneuXL3AxJCUFQCgMKe1vTJmqQ7mA64y9B87%2F%2BbyFFC%2BkxKWJtNCjf5R%2FVJN4Zy1gbrGh5lunJVeE%2FzI7PLm2aSFhhbnkKPnbnrC4QCWSw%2BQ%2BvxBJORMPrQ3b0GOqUBeeM3GGSmf9x72MWFx7pgHcQmtTJBE0ldrkeNGACXJv4zHK66Wzubl6DCIO1whFzKE2vEns%2BATt1r%2FentCeVf2hEiBTGkzPIda%2FiH8qeC9ChvDFWlAC4XNs9nanYjJ2YC0U6ZJf1I0DbwyRXm0MGOhEo3Mvx01yvMyOeyNeufIvNVBoJ7IS%2F0XaxQu7Xt4aQLBv%2Feewxq8XArfis%2BYmYD7%2BzEBpg2&X-Amz-Signature=40451939989b445910d029e329d6b0d58184c1fb9f876c603731701aa87e52a5&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665VRC7YIZ%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T183314Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBgzh8NY7t17OefxLqY%2F4Th25BgMGpmZm92klF10mjzEAiEAj2esZ5H6ujqA%2FFvNsZV4itQhRrE83bOwYjxpjxkGDNMqiAQIw%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDFVwqIPvLT775UDd3ircAyzgdoihmBW5Sf%2B1QSVzuYJ%2Brd8qkN3lCrD%2BviQAnGWnsuMrOVoDihnmLFNLLt95Z1QSuPYJJMKNPlt%2FBl1HtvBNaXZxAsJTRnQy9edZstLLFaRYj%2FFQEvGB0hIIkt275kGpPQVXBIya4p5bD1v%2BWzOLGOlxQY%2BHeRhgPkMuzqZDuCo0kTXePuVjbDaPN1YsBKmGP8LhflGKxiKwH44YM0twI0PiMJcMdvef0FQKu0vOYKcwqQE07%2FsTZzTeyQ90fc1sxRA0KVPZGcafwKYhZOIVbTXuP6bH8E6vc8DQZu3DDJywUgigXF6JvUkvwxCdpU6PNwzHND9q9jL3Q4GL1uzo6vOtQDHQ5Ug6acQEEBfb7hQu9cNcYoeyPoY9VWqW2dcpQ1T0aqQF%2FkJT20YBxIa%2BcTH3FSAequCewBrWlT3Ps6FmTEKwSWT6M9nNARqfKL%2FmLlY%2BEWAZZ3OuVOBnSZu1uSoSbbIDh3pjxxFildcUAsZ%2B1TI4Lds5fzK1NjrBvWFlfd6mFTneuXL3AxJCUFQCgMKe1vTJmqQ7mA64y9B87%2F%2BbyFFC%2BkxKWJtNCjf5R%2FVJN4Zy1gbrGh5lunJVeE%2FzI7PLm2aSFhhbnkKPnbnrC4QCWSw%2BQ%2BvxBJORMPrQ3b0GOqUBeeM3GGSmf9x72MWFx7pgHcQmtTJBE0ldrkeNGACXJv4zHK66Wzubl6DCIO1whFzKE2vEns%2BATt1r%2FentCeVf2hEiBTGkzPIda%2FiH8qeC9ChvDFWlAC4XNs9nanYjJ2YC0U6ZJf1I0DbwyRXm0MGOhEo3Mvx01yvMyOeyNeufIvNVBoJ7IS%2F0XaxQu7Xt4aQLBv%2Feewxq8XArfis%2BYmYD7%2BzEBpg2&X-Amz-Signature=df0f8f3dc551315f6f64e2248a1afde0a781b1dfa591c3f4e12d5cb65591cce7&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665VRC7YIZ%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T183314Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBgzh8NY7t17OefxLqY%2F4Th25BgMGpmZm92klF10mjzEAiEAj2esZ5H6ujqA%2FFvNsZV4itQhRrE83bOwYjxpjxkGDNMqiAQIw%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDFVwqIPvLT775UDd3ircAyzgdoihmBW5Sf%2B1QSVzuYJ%2Brd8qkN3lCrD%2BviQAnGWnsuMrOVoDihnmLFNLLt95Z1QSuPYJJMKNPlt%2FBl1HtvBNaXZxAsJTRnQy9edZstLLFaRYj%2FFQEvGB0hIIkt275kGpPQVXBIya4p5bD1v%2BWzOLGOlxQY%2BHeRhgPkMuzqZDuCo0kTXePuVjbDaPN1YsBKmGP8LhflGKxiKwH44YM0twI0PiMJcMdvef0FQKu0vOYKcwqQE07%2FsTZzTeyQ90fc1sxRA0KVPZGcafwKYhZOIVbTXuP6bH8E6vc8DQZu3DDJywUgigXF6JvUkvwxCdpU6PNwzHND9q9jL3Q4GL1uzo6vOtQDHQ5Ug6acQEEBfb7hQu9cNcYoeyPoY9VWqW2dcpQ1T0aqQF%2FkJT20YBxIa%2BcTH3FSAequCewBrWlT3Ps6FmTEKwSWT6M9nNARqfKL%2FmLlY%2BEWAZZ3OuVOBnSZu1uSoSbbIDh3pjxxFildcUAsZ%2B1TI4Lds5fzK1NjrBvWFlfd6mFTneuXL3AxJCUFQCgMKe1vTJmqQ7mA64y9B87%2F%2BbyFFC%2BkxKWJtNCjf5R%2FVJN4Zy1gbrGh5lunJVeE%2FzI7PLm2aSFhhbnkKPnbnrC4QCWSw%2BQ%2BvxBJORMPrQ3b0GOqUBeeM3GGSmf9x72MWFx7pgHcQmtTJBE0ldrkeNGACXJv4zHK66Wzubl6DCIO1whFzKE2vEns%2BATt1r%2FentCeVf2hEiBTGkzPIda%2FiH8qeC9ChvDFWlAC4XNs9nanYjJ2YC0U6ZJf1I0DbwyRXm0MGOhEo3Mvx01yvMyOeyNeufIvNVBoJ7IS%2F0XaxQu7Xt4aQLBv%2Feewxq8XArfis%2BYmYD7%2BzEBpg2&X-Amz-Signature=20e773fb986046db94d9787c129c0636fa218d955f1fb2be1fa23cdf8c491205&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665VRC7YIZ%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T183314Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBgzh8NY7t17OefxLqY%2F4Th25BgMGpmZm92klF10mjzEAiEAj2esZ5H6ujqA%2FFvNsZV4itQhRrE83bOwYjxpjxkGDNMqiAQIw%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDFVwqIPvLT775UDd3ircAyzgdoihmBW5Sf%2B1QSVzuYJ%2Brd8qkN3lCrD%2BviQAnGWnsuMrOVoDihnmLFNLLt95Z1QSuPYJJMKNPlt%2FBl1HtvBNaXZxAsJTRnQy9edZstLLFaRYj%2FFQEvGB0hIIkt275kGpPQVXBIya4p5bD1v%2BWzOLGOlxQY%2BHeRhgPkMuzqZDuCo0kTXePuVjbDaPN1YsBKmGP8LhflGKxiKwH44YM0twI0PiMJcMdvef0FQKu0vOYKcwqQE07%2FsTZzTeyQ90fc1sxRA0KVPZGcafwKYhZOIVbTXuP6bH8E6vc8DQZu3DDJywUgigXF6JvUkvwxCdpU6PNwzHND9q9jL3Q4GL1uzo6vOtQDHQ5Ug6acQEEBfb7hQu9cNcYoeyPoY9VWqW2dcpQ1T0aqQF%2FkJT20YBxIa%2BcTH3FSAequCewBrWlT3Ps6FmTEKwSWT6M9nNARqfKL%2FmLlY%2BEWAZZ3OuVOBnSZu1uSoSbbIDh3pjxxFildcUAsZ%2B1TI4Lds5fzK1NjrBvWFlfd6mFTneuXL3AxJCUFQCgMKe1vTJmqQ7mA64y9B87%2F%2BbyFFC%2BkxKWJtNCjf5R%2FVJN4Zy1gbrGh5lunJVeE%2FzI7PLm2aSFhhbnkKPnbnrC4QCWSw%2BQ%2BvxBJORMPrQ3b0GOqUBeeM3GGSmf9x72MWFx7pgHcQmtTJBE0ldrkeNGACXJv4zHK66Wzubl6DCIO1whFzKE2vEns%2BATt1r%2FentCeVf2hEiBTGkzPIda%2FiH8qeC9ChvDFWlAC4XNs9nanYjJ2YC0U6ZJf1I0DbwyRXm0MGOhEo3Mvx01yvMyOeyNeufIvNVBoJ7IS%2F0XaxQu7Xt4aQLBv%2Feewxq8XArfis%2BYmYD7%2BzEBpg2&X-Amz-Signature=bed3b9f8472f8d1eb4d7ded29625ffcea18208a8392ee4819cea73e6f7687268&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665UF5KT3B%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T183315Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIHUSfvSUaQDsoDGS1art0b3%2F4LAz%2FsX6K%2FCbK%2FpC4PRVAiBGZElo%2F3sWpMm9m7PsIdgY10A1QPKwlC4tz1%2Bf7RHfViqIBAjD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM32PGg6gBHwxmQk%2FwKtwD9EcsfZ6EA%2BqHoIGhUqD%2Fd7woFRoD1JRznwz0wpiNkvppRBiVd8o4LQuTmcJ%2BYj8XLe5AaZomulNZc9m2iMVfY%2F5pGX5zj%2FRnjd%2FSzWDq5izAi5HMS4nxoLt8bdez33Fdb4dSWx2t0RtiYgDJXhOPBzHAAl5vt4ekAPEXTgZ%2BNYWP2xdKSfrQLiIEt6AzSLCMIKa0xumiDc8Nwp7C7iiyRMjk3X8N7FGDvrSmd7t1bbcKJyJBhEbCv0%2B1S%2Bxnw1F0YfAHQr7ePtnHpa1LayP%2Fh2xZVrJFaEhPTqRYAUGjRKkrq2MIu1RHE2yb2l3zq9qnU713bS8t9xFleBf1Sq6hyqLeANfAPq%2FZKbGHVS40IMo0BQ%2BtY83qLF40SVxtDKFCEVFM3Pn8Ls24cUuvtgHlp4kJh7IIB%2BMBZkpcmPB1bRbgmKERrW3skbS8fGcLFJzvZOzw1aVs5kFJWRRdnHb2CM1OhUDPNkhN7Qj7F%2FyzYBVh4Zr3Uj1%2BmrZUyjJdS8j1K59bgZ52z%2B%2FjGvI0waR8r%2Fac28JI02JlMzPdCHUK1Dz6wDqWuqTqgYLckZ%2Ffr8un2QAOzeEuhld0yrey5cEHOJDgodiwMcBnLOrLkVBjK%2BnTg5jk7cumQme9KG4w7NDdvQY6pgGaJVXULutyjRUJbgvFQ%2BCbw6k%2BoeZVeTsCrpL8BGiaIoZ3jH%2B%2BG0zc2Oo4%2BPt2ncCsSwunZXDHFSXaO2JrvHacYgEH0ymku6f8uRWU102ZDSqMgZ2MZ0SqIf2Sn5esUAqCYn2skKhRQ9w5NXE0tI8BzLc7FcKJEMMcqivo8sW7ud2g%2F0meY2QsaiA4YHbmyTo1LYFb4PFaejmT%2FnNPbL6UoIpZ61Fe&X-Amz-Signature=a65d53e66970ba3254e2a7af43a430805b5aff6367437638179321e459c7d356&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664H6BLSQS%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T183317Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDNgQn9okmvGOmUusEE%2F13vD73RC%2FgGf7YEGIzs8d2mkgIhAOYYzCJIMw0qLzeMHGp2wz0r4FyjedKc5gJh32x1wiz0KogECMP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwfBKboYwKHbi0SAZIq3APaY2EDGGvjNjTngc1FHOdVND2kZo6ioVv4PbilOLMqtjANDikLZ4CIxUq435eGO25g%2Fdd8kjZeE%2FLuaKM7Yd%2Bv%2Bs7qgndoyg2aUKd52Br5cxm3AL%2BOJyje%2Fv0L2HHM5wvUS2H2qL9vHlfZI04EwaxhKrnbvnUyz4OkEdFKGBMvKIlVHZKud6qHJ4vw4wDQaWJwk6qHXC7uq4BwcGQEK%2BhbxKbpZsN7JwGMJSpEaslRxEnDlQLw%2BZbesn2YRmAV8Cc%2FkLFEIbsjHUn0Cg4PFPEbmgeQ%2FV4KHSCEx%2BmU14mac1ncaHUhBW4WaGszjSzSxxrfXvLZlcfzJMJNYh9wn789dDb8crhJdy5lzBaVe4CnLAgdmJYN7%2FdQW%2F%2F0nbXYH1W6YrM9DFbFMElbMEDL06T1jVwyXXWOsApYdvDi2P8BScvEUnCwdTVDES%2BZe4ZM4PNR%2BotnxiqMN6CQj%2F6b5oMO6ib0ZxeqGrMtQUX8UmEeqNVOYPVcbdINE%2BQolpyCJax3kT9%2BOyQOUfi%2FjXdM%2BgHTEAXtbbQnEGl4mM3dmh5tKyXBEQoayZ6FuVUrZQEG54nwfsKaG1qV5f7Z3cn4sfWYHEj7dpSUEO1cHe8zTUbw%2BX%2B37Ug02F3pPJubNzC40t29BjqkAW6qExb2uMzwgyy1obwIFeF1H9PU%2B%2B3W1b9C9a17wBHeQ13iwxAD9wKPbNys1f%2BYNTqbMPmbj5sPyPZ3icGkEgKa27k5zmA5yZgv6CPdGK0PF9wgw3YTzhiw%2Fbra3zv4gRLBgNJd4lAWieG6UC6Uswrg9sG8b245TPRd6Z2Nz2o3e9p6NkvQnJcIflU%2BA1LhsO4sprMpKGB%2BPsj6AskqNtMUOyYt&X-Amz-Signature=28a38fd7bc83dc44c9c20f2a250ebf862d175df704a394fa9935b886a6889e88&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665VRC7YIZ%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T183314Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBgzh8NY7t17OefxLqY%2F4Th25BgMGpmZm92klF10mjzEAiEAj2esZ5H6ujqA%2FFvNsZV4itQhRrE83bOwYjxpjxkGDNMqiAQIw%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDFVwqIPvLT775UDd3ircAyzgdoihmBW5Sf%2B1QSVzuYJ%2Brd8qkN3lCrD%2BviQAnGWnsuMrOVoDihnmLFNLLt95Z1QSuPYJJMKNPlt%2FBl1HtvBNaXZxAsJTRnQy9edZstLLFaRYj%2FFQEvGB0hIIkt275kGpPQVXBIya4p5bD1v%2BWzOLGOlxQY%2BHeRhgPkMuzqZDuCo0kTXePuVjbDaPN1YsBKmGP8LhflGKxiKwH44YM0twI0PiMJcMdvef0FQKu0vOYKcwqQE07%2FsTZzTeyQ90fc1sxRA0KVPZGcafwKYhZOIVbTXuP6bH8E6vc8DQZu3DDJywUgigXF6JvUkvwxCdpU6PNwzHND9q9jL3Q4GL1uzo6vOtQDHQ5Ug6acQEEBfb7hQu9cNcYoeyPoY9VWqW2dcpQ1T0aqQF%2FkJT20YBxIa%2BcTH3FSAequCewBrWlT3Ps6FmTEKwSWT6M9nNARqfKL%2FmLlY%2BEWAZZ3OuVOBnSZu1uSoSbbIDh3pjxxFildcUAsZ%2B1TI4Lds5fzK1NjrBvWFlfd6mFTneuXL3AxJCUFQCgMKe1vTJmqQ7mA64y9B87%2F%2BbyFFC%2BkxKWJtNCjf5R%2FVJN4Zy1gbrGh5lunJVeE%2FzI7PLm2aSFhhbnkKPnbnrC4QCWSw%2BQ%2BvxBJORMPrQ3b0GOqUBeeM3GGSmf9x72MWFx7pgHcQmtTJBE0ldrkeNGACXJv4zHK66Wzubl6DCIO1whFzKE2vEns%2BATt1r%2FentCeVf2hEiBTGkzPIda%2FiH8qeC9ChvDFWlAC4XNs9nanYjJ2YC0U6ZJf1I0DbwyRXm0MGOhEo3Mvx01yvMyOeyNeufIvNVBoJ7IS%2F0XaxQu7Xt4aQLBv%2Feewxq8XArfis%2BYmYD7%2BzEBpg2&X-Amz-Signature=0d036ed5715549f54eec1a97f869aea437a5ea40ee375e5db3b6aeec61f5a751&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665VRC7YIZ%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T183315Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBgzh8NY7t17OefxLqY%2F4Th25BgMGpmZm92klF10mjzEAiEAj2esZ5H6ujqA%2FFvNsZV4itQhRrE83bOwYjxpjxkGDNMqiAQIw%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDFVwqIPvLT775UDd3ircAyzgdoihmBW5Sf%2B1QSVzuYJ%2Brd8qkN3lCrD%2BviQAnGWnsuMrOVoDihnmLFNLLt95Z1QSuPYJJMKNPlt%2FBl1HtvBNaXZxAsJTRnQy9edZstLLFaRYj%2FFQEvGB0hIIkt275kGpPQVXBIya4p5bD1v%2BWzOLGOlxQY%2BHeRhgPkMuzqZDuCo0kTXePuVjbDaPN1YsBKmGP8LhflGKxiKwH44YM0twI0PiMJcMdvef0FQKu0vOYKcwqQE07%2FsTZzTeyQ90fc1sxRA0KVPZGcafwKYhZOIVbTXuP6bH8E6vc8DQZu3DDJywUgigXF6JvUkvwxCdpU6PNwzHND9q9jL3Q4GL1uzo6vOtQDHQ5Ug6acQEEBfb7hQu9cNcYoeyPoY9VWqW2dcpQ1T0aqQF%2FkJT20YBxIa%2BcTH3FSAequCewBrWlT3Ps6FmTEKwSWT6M9nNARqfKL%2FmLlY%2BEWAZZ3OuVOBnSZu1uSoSbbIDh3pjxxFildcUAsZ%2B1TI4Lds5fzK1NjrBvWFlfd6mFTneuXL3AxJCUFQCgMKe1vTJmqQ7mA64y9B87%2F%2BbyFFC%2BkxKWJtNCjf5R%2FVJN4Zy1gbrGh5lunJVeE%2FzI7PLm2aSFhhbnkKPnbnrC4QCWSw%2BQ%2BvxBJORMPrQ3b0GOqUBeeM3GGSmf9x72MWFx7pgHcQmtTJBE0ldrkeNGACXJv4zHK66Wzubl6DCIO1whFzKE2vEns%2BATt1r%2FentCeVf2hEiBTGkzPIda%2FiH8qeC9ChvDFWlAC4XNs9nanYjJ2YC0U6ZJf1I0DbwyRXm0MGOhEo3Mvx01yvMyOeyNeufIvNVBoJ7IS%2F0XaxQu7Xt4aQLBv%2Feewxq8XArfis%2BYmYD7%2BzEBpg2&X-Amz-Signature=51c3b6660c8d8d56040ad2607ab86559507859906930507c6bddcfe464ae9cc4&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665VRC7YIZ%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T183315Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBgzh8NY7t17OefxLqY%2F4Th25BgMGpmZm92klF10mjzEAiEAj2esZ5H6ujqA%2FFvNsZV4itQhRrE83bOwYjxpjxkGDNMqiAQIw%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDFVwqIPvLT775UDd3ircAyzgdoihmBW5Sf%2B1QSVzuYJ%2Brd8qkN3lCrD%2BviQAnGWnsuMrOVoDihnmLFNLLt95Z1QSuPYJJMKNPlt%2FBl1HtvBNaXZxAsJTRnQy9edZstLLFaRYj%2FFQEvGB0hIIkt275kGpPQVXBIya4p5bD1v%2BWzOLGOlxQY%2BHeRhgPkMuzqZDuCo0kTXePuVjbDaPN1YsBKmGP8LhflGKxiKwH44YM0twI0PiMJcMdvef0FQKu0vOYKcwqQE07%2FsTZzTeyQ90fc1sxRA0KVPZGcafwKYhZOIVbTXuP6bH8E6vc8DQZu3DDJywUgigXF6JvUkvwxCdpU6PNwzHND9q9jL3Q4GL1uzo6vOtQDHQ5Ug6acQEEBfb7hQu9cNcYoeyPoY9VWqW2dcpQ1T0aqQF%2FkJT20YBxIa%2BcTH3FSAequCewBrWlT3Ps6FmTEKwSWT6M9nNARqfKL%2FmLlY%2BEWAZZ3OuVOBnSZu1uSoSbbIDh3pjxxFildcUAsZ%2B1TI4Lds5fzK1NjrBvWFlfd6mFTneuXL3AxJCUFQCgMKe1vTJmqQ7mA64y9B87%2F%2BbyFFC%2BkxKWJtNCjf5R%2FVJN4Zy1gbrGh5lunJVeE%2FzI7PLm2aSFhhbnkKPnbnrC4QCWSw%2BQ%2BvxBJORMPrQ3b0GOqUBeeM3GGSmf9x72MWFx7pgHcQmtTJBE0ldrkeNGACXJv4zHK66Wzubl6DCIO1whFzKE2vEns%2BATt1r%2FentCeVf2hEiBTGkzPIda%2FiH8qeC9ChvDFWlAC4XNs9nanYjJ2YC0U6ZJf1I0DbwyRXm0MGOhEo3Mvx01yvMyOeyNeufIvNVBoJ7IS%2F0XaxQu7Xt4aQLBv%2Feewxq8XArfis%2BYmYD7%2BzEBpg2&X-Amz-Signature=bf6b3e8780d21365dde845f50c48f7e5ce91c2ce109edd0aa459f0890e020cbd&X-Amz-SignedHeaders=host&x-id=GetObject)


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

