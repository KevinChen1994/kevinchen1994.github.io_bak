---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4663RWIZLY2%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250217T033007Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEEMaCXVzLXdlc3QtMiJHMEUCIEbglmnRtdNzOLwd%2BhMhGd8y9I%2F46RZyUrh%2BXJs0TuU5A\
  iEAzJEDbbHwM6YnBYBGwNoWXC1vVNrDg0f0LkDI5lrT07Qq%2FwMIbBAAGgw2Mzc0MjMxODM4MDUi\
  DPhRkjkqjHdhIiju8ircA3eb8v4evx%2BD6wKzk3hbFHQhySzXx%2FbF%2BNIhEHzqYJJKp4AGU%2\
  BmKzkhYTY12BHhVGl%2BYQ285D38oAdpaJvWN1XGhziOenlyMySZEVYIn3AIUXKWXEYbEzNtpddGz\
  JmPXjdc3TSr3B973G8y88bXUfCbdfRCABHMYIv8PwueQ%2B%2B5FwE7x7RJ3cDUtzAsjuanfmA%2F\
  ay4PymjRCKeJNhbre2bnxskBG9f2AJd46RyWYzKuVrSkQ%2BMLYsrVTnsvNMuG%2BMGyaChe0uVkI\
  P%2FWSI2doPuO9rwoJCoEyyhsRM3JPf%2Bpyjsshndrz0iMrsKtOOOB%2FkOqHAqfmbQ59369k8Uq\
  QqqeMzlKlpA74RZJWKY6S0hoo9HAyCmzCJelwckKx9PfVBoXRt62QW4TIPlgB%2BYlZ1nlFqB9fOe\
  d1Kqc0FD0Mc2Z4pS5wlVr9HLzzbfmI8Dd848VIzktn4ipjTVor6WzTzLgw3Auwz12ZrcgVhmSucLM\
  okBFgeMPTNGcbOj%2BjjflXkzZTg1N19TDd8V7BNnfSaC9cYsMkoZ0FC6nCQfOWGaHUg%2FqI22OU\
  XvYc%2F3wigh5R0ew4%2Fi%2BncYVSo%2FGmqgcIjvSqMivSW5BO8SkvI1kbcbZRwp8Csaze3gKlG\
  rdCMJDLyr0GOqUB32hfu7TAZjJjilPQHLw74ciWEgROvgwMLEZgIPUoZtcen8Z%2BhSEqy7U%2Bfv\
  kBgVsly6ZBaaRVhFgx8VcJ%2Bk45EFWFq5l05q0JV21MKt9yYGnqFd1BrNGWNiqXm43lTGJ7SJIf%\
  2B9brBaOibafOGy72R%2Fqq4e4pMqz1oE%2B%2BDRqBsidmr%2FIKh9dNv89JmXT3bbg04MIGFEzV\
  zmVZKYpoAkeGoHeepwZN&X-Amz-Signature=266d803730dbaebeb266c6b7f342f93f74747242\
  24dd31ce502eab8f73fc2253&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466QYMZJ35O%2F20250217%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250217T032837Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEEMaCXVzLXdlc3QtMiJGMEQCIFlqGwWnWFdRBmcSPH3vSNIXGgb5uPe\
        F%2BQVnfx5NdEKoAiB67CNOPH1OAuva%2FP3WdorQw6kY6C2Im5VFrQfZG5KkDir%2FAwhs\
        EAAaDDYzNzQyMzE4MzgwNSIMYoZb1EVNszl9OUVuKtwD2etsMLefNRhF2UaE5X35Y0H9KX8\
        hml2lTAKDSIvlgUjhRmR5hFIGT%2BTeIKKwhx%2BM1X9h%2FAtliD3wOhyrzMo0tSS634%2\
        BNM9N0I6bwejWZKjOyPOQXnvMpaT8NLKQapVVBsr%2F14hcypkXJpIlKOtBgdJXMUuqkbs9\
        TqQtMuRHf5dCRvjyclDLpONX%2BzEZy0TV9npxjmcQX3mtbH0vok8SeAvoxAs%2FE8XmmsS\
        Tp6ANZZ32%2BAI43LKPR65jUtnnBaYrwS42%2F5FAEhBGHFT2PYpjHrGYADQanF0OwIJPwa\
        2TJRU6K8pyYbUQC76L9KHNyUyy7OT9amI1hMtTwG3baU2oNgt63bBsUeqBaxkQwEXvZw%2F\
        jfIFnQERM1yFoxptagxj1w1KkRmQ2F94VtM0NRAaDzTfqNED473XF7npatdOxDkhYtZ1gBR\
        S8SP7EtflG3hjJOthPAM7HCSWl466WbXf90w%2BVal7Vxo0lOhUW%2BwpfIJapYVR20V%2F\
        8SoKQ1Opx%2FhjEJS4HYjqWUkP%2FSXJZTcOUW3xCHaj52HKwYYOzmTFSVkEAOtwqhus%2B\
        9AywtD221bl0nRDcxCkyGBrzBRwH10qhWVV3wBvRl74hWKJw%2FMBdjrKEnEy%2FbpFkq3Y\
        kuvmgwksvKvQY6pgFc4nKfXYS3uf0%2FnhjJcRyfHXzPTEc8%2Bdy49MBQiRKd6xHdGYVKA\
        uyt8DQfohdoabNCK7r4zz7Ij%2FcQ4lg1n7Kj8lBQ7uj4pUuolEe4Eu7UkVrAae6cotCZFu\
        H8139t4pbQPAj85GGkvAufZeDnyKbmfR1cJtofa8gGEVNnLKMPbN49zoUhNcNeUl8cCTjBV\
        Y5B5RoOWFl8OzJbGx4%2FIuSoRD3lRuLq&X-Amz-Signature=dfe6fbd5cac2f35633d9d\
        b36c1e19c92c8214552872d48f240997181a0f6e586&X-Amz-SignedHeaders=host&x-\
        id=GetObject"
      expiry_time: "2025-02-17T04:28:37.918Z"
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
UPDATE_TIME: "2025-02-17T03:30:14.275Z"
EXPIRY_TIME: "2025-02-17T04:30:04.969Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XYTCSYTU%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T033005Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEMaCXVzLXdlc3QtMiJIMEYCIQDSnkxhNDpjd82bV3iOVQV7QTckzG1EpmM%2Blr%2FdASbT3QIhAKTRW5HUnZeX9hHB7WNgxo%2FM7au%2FnlD0ya8Nw3DtYFn0Kv8DCGwQABoMNjM3NDIzMTgzODA1IgzFI6z2d9jfYdYbZ%2Fkq3AMKg9Sa8T2NpNQ1QtkwacXbbXjuNLpRGiIP4ZCIjC5KVz6wXxDFwQ%2FeOpvJALaZdP0e%2BW3yrIMqAyBWOyoIu%2ByStjNIR5A8glj9K7KpsP29NYXgh8S4j9CsJSY66Ej4QbxLOgxC%2FXgKe%2Fxx6xqeBJHuWyMSSJR5RTWVotw4XKV%2FcHsqVcJHP5tGZnCUnnC5VW08ubTk2h18frBtL7vbBvMHCwMr0UK7jEoPhO0TeUEqRaBVvScJHolZT75E6HfP0AOU8q9SggZxruxtQ9pGoEmMUohz6VoBBMYQ0J%2BagdLxMYoyO0uhZcYZi6gLPjL7MlaZSGAomz6S%2BoNd%2BPHuj3QspiJlzYXNpcJUhMGrRQno%2BTUAwRTgshVximQnze2fcwMH3YS%2FrHOx02s6L%2Frvi5dofh5f7a9Pf2iXXQevryopv0qVQpEJfHIv62S99R1aLPCYirq2yFqIvuLJaxNxxUbc5QHv%2B9uVLRFXlpzBQ%2Bx7z2urZ9sYkt771VihX6M%2Bs5vAcRF6XK4wgFQETe1rlZHRxm1RaH3EUFm%2BwW3JCOF9QlutzpjOkoaoHCXSwW5X5WsoOYpdTC%2BKuOEMKJRaMWV9Q%2BK5l7%2FizYZWdjdaI2Rrkwm%2Bk0ZMRclT0h0IZDCWysq9BjqkAb6EUnVICNz1bnmbDbdi593Bu5TfqKoSGRobcAHljT9gclDoU76NzbasHU9rE3XpuEzg5vUc3mYIceE0zFl2fcNdWKW8txP7KxXzWaCCKxk9shh%2FZQ2Dex0Za4BZ5wdQtZ3A%2BreGwXqNSaqA2CNQtY9Xmh5W4E8CduIQKO7ZQbyZRz8GM4PfDBK90yFV28btDtGh81ZPFyJj1OXr%2B6BcXUySVNJv&X-Amz-Signature=8f9dfed4846f712c45393b50b65af2da0f5fc3a7d9895c0d7909e88bff220c1c&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XYTCSYTU%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T033005Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEMaCXVzLXdlc3QtMiJIMEYCIQDSnkxhNDpjd82bV3iOVQV7QTckzG1EpmM%2Blr%2FdASbT3QIhAKTRW5HUnZeX9hHB7WNgxo%2FM7au%2FnlD0ya8Nw3DtYFn0Kv8DCGwQABoMNjM3NDIzMTgzODA1IgzFI6z2d9jfYdYbZ%2Fkq3AMKg9Sa8T2NpNQ1QtkwacXbbXjuNLpRGiIP4ZCIjC5KVz6wXxDFwQ%2FeOpvJALaZdP0e%2BW3yrIMqAyBWOyoIu%2ByStjNIR5A8glj9K7KpsP29NYXgh8S4j9CsJSY66Ej4QbxLOgxC%2FXgKe%2Fxx6xqeBJHuWyMSSJR5RTWVotw4XKV%2FcHsqVcJHP5tGZnCUnnC5VW08ubTk2h18frBtL7vbBvMHCwMr0UK7jEoPhO0TeUEqRaBVvScJHolZT75E6HfP0AOU8q9SggZxruxtQ9pGoEmMUohz6VoBBMYQ0J%2BagdLxMYoyO0uhZcYZi6gLPjL7MlaZSGAomz6S%2BoNd%2BPHuj3QspiJlzYXNpcJUhMGrRQno%2BTUAwRTgshVximQnze2fcwMH3YS%2FrHOx02s6L%2Frvi5dofh5f7a9Pf2iXXQevryopv0qVQpEJfHIv62S99R1aLPCYirq2yFqIvuLJaxNxxUbc5QHv%2B9uVLRFXlpzBQ%2Bx7z2urZ9sYkt771VihX6M%2Bs5vAcRF6XK4wgFQETe1rlZHRxm1RaH3EUFm%2BwW3JCOF9QlutzpjOkoaoHCXSwW5X5WsoOYpdTC%2BKuOEMKJRaMWV9Q%2BK5l7%2FizYZWdjdaI2Rrkwm%2Bk0ZMRclT0h0IZDCWysq9BjqkAb6EUnVICNz1bnmbDbdi593Bu5TfqKoSGRobcAHljT9gclDoU76NzbasHU9rE3XpuEzg5vUc3mYIceE0zFl2fcNdWKW8txP7KxXzWaCCKxk9shh%2FZQ2Dex0Za4BZ5wdQtZ3A%2BreGwXqNSaqA2CNQtY9Xmh5W4E8CduIQKO7ZQbyZRz8GM4PfDBK90yFV28btDtGh81ZPFyJj1OXr%2B6BcXUySVNJv&X-Amz-Signature=56a96dc3179af56c08596152ce296115007ae9572413456da722c99794ebba5b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XYTCSYTU%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T033005Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEMaCXVzLXdlc3QtMiJIMEYCIQDSnkxhNDpjd82bV3iOVQV7QTckzG1EpmM%2Blr%2FdASbT3QIhAKTRW5HUnZeX9hHB7WNgxo%2FM7au%2FnlD0ya8Nw3DtYFn0Kv8DCGwQABoMNjM3NDIzMTgzODA1IgzFI6z2d9jfYdYbZ%2Fkq3AMKg9Sa8T2NpNQ1QtkwacXbbXjuNLpRGiIP4ZCIjC5KVz6wXxDFwQ%2FeOpvJALaZdP0e%2BW3yrIMqAyBWOyoIu%2ByStjNIR5A8glj9K7KpsP29NYXgh8S4j9CsJSY66Ej4QbxLOgxC%2FXgKe%2Fxx6xqeBJHuWyMSSJR5RTWVotw4XKV%2FcHsqVcJHP5tGZnCUnnC5VW08ubTk2h18frBtL7vbBvMHCwMr0UK7jEoPhO0TeUEqRaBVvScJHolZT75E6HfP0AOU8q9SggZxruxtQ9pGoEmMUohz6VoBBMYQ0J%2BagdLxMYoyO0uhZcYZi6gLPjL7MlaZSGAomz6S%2BoNd%2BPHuj3QspiJlzYXNpcJUhMGrRQno%2BTUAwRTgshVximQnze2fcwMH3YS%2FrHOx02s6L%2Frvi5dofh5f7a9Pf2iXXQevryopv0qVQpEJfHIv62S99R1aLPCYirq2yFqIvuLJaxNxxUbc5QHv%2B9uVLRFXlpzBQ%2Bx7z2urZ9sYkt771VihX6M%2Bs5vAcRF6XK4wgFQETe1rlZHRxm1RaH3EUFm%2BwW3JCOF9QlutzpjOkoaoHCXSwW5X5WsoOYpdTC%2BKuOEMKJRaMWV9Q%2BK5l7%2FizYZWdjdaI2Rrkwm%2Bk0ZMRclT0h0IZDCWysq9BjqkAb6EUnVICNz1bnmbDbdi593Bu5TfqKoSGRobcAHljT9gclDoU76NzbasHU9rE3XpuEzg5vUc3mYIceE0zFl2fcNdWKW8txP7KxXzWaCCKxk9shh%2FZQ2Dex0Za4BZ5wdQtZ3A%2BreGwXqNSaqA2CNQtY9Xmh5W4E8CduIQKO7ZQbyZRz8GM4PfDBK90yFV28btDtGh81ZPFyJj1OXr%2B6BcXUySVNJv&X-Amz-Signature=686f9f8e7cb8ca6c92bfad919dd65a56c02dc79c3ab050440ea3401dffd4d05e&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XYTCSYTU%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T033005Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEMaCXVzLXdlc3QtMiJIMEYCIQDSnkxhNDpjd82bV3iOVQV7QTckzG1EpmM%2Blr%2FdASbT3QIhAKTRW5HUnZeX9hHB7WNgxo%2FM7au%2FnlD0ya8Nw3DtYFn0Kv8DCGwQABoMNjM3NDIzMTgzODA1IgzFI6z2d9jfYdYbZ%2Fkq3AMKg9Sa8T2NpNQ1QtkwacXbbXjuNLpRGiIP4ZCIjC5KVz6wXxDFwQ%2FeOpvJALaZdP0e%2BW3yrIMqAyBWOyoIu%2ByStjNIR5A8glj9K7KpsP29NYXgh8S4j9CsJSY66Ej4QbxLOgxC%2FXgKe%2Fxx6xqeBJHuWyMSSJR5RTWVotw4XKV%2FcHsqVcJHP5tGZnCUnnC5VW08ubTk2h18frBtL7vbBvMHCwMr0UK7jEoPhO0TeUEqRaBVvScJHolZT75E6HfP0AOU8q9SggZxruxtQ9pGoEmMUohz6VoBBMYQ0J%2BagdLxMYoyO0uhZcYZi6gLPjL7MlaZSGAomz6S%2BoNd%2BPHuj3QspiJlzYXNpcJUhMGrRQno%2BTUAwRTgshVximQnze2fcwMH3YS%2FrHOx02s6L%2Frvi5dofh5f7a9Pf2iXXQevryopv0qVQpEJfHIv62S99R1aLPCYirq2yFqIvuLJaxNxxUbc5QHv%2B9uVLRFXlpzBQ%2Bx7z2urZ9sYkt771VihX6M%2Bs5vAcRF6XK4wgFQETe1rlZHRxm1RaH3EUFm%2BwW3JCOF9QlutzpjOkoaoHCXSwW5X5WsoOYpdTC%2BKuOEMKJRaMWV9Q%2BK5l7%2FizYZWdjdaI2Rrkwm%2Bk0ZMRclT0h0IZDCWysq9BjqkAb6EUnVICNz1bnmbDbdi593Bu5TfqKoSGRobcAHljT9gclDoU76NzbasHU9rE3XpuEzg5vUc3mYIceE0zFl2fcNdWKW8txP7KxXzWaCCKxk9shh%2FZQ2Dex0Za4BZ5wdQtZ3A%2BreGwXqNSaqA2CNQtY9Xmh5W4E8CduIQKO7ZQbyZRz8GM4PfDBK90yFV28btDtGh81ZPFyJj1OXr%2B6BcXUySVNJv&X-Amz-Signature=e29e8918bc39cb3cced55226a41f4c071a6187d5139be22b33224ea7d00f5080&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XYTCSYTU%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T033005Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEMaCXVzLXdlc3QtMiJIMEYCIQDSnkxhNDpjd82bV3iOVQV7QTckzG1EpmM%2Blr%2FdASbT3QIhAKTRW5HUnZeX9hHB7WNgxo%2FM7au%2FnlD0ya8Nw3DtYFn0Kv8DCGwQABoMNjM3NDIzMTgzODA1IgzFI6z2d9jfYdYbZ%2Fkq3AMKg9Sa8T2NpNQ1QtkwacXbbXjuNLpRGiIP4ZCIjC5KVz6wXxDFwQ%2FeOpvJALaZdP0e%2BW3yrIMqAyBWOyoIu%2ByStjNIR5A8glj9K7KpsP29NYXgh8S4j9CsJSY66Ej4QbxLOgxC%2FXgKe%2Fxx6xqeBJHuWyMSSJR5RTWVotw4XKV%2FcHsqVcJHP5tGZnCUnnC5VW08ubTk2h18frBtL7vbBvMHCwMr0UK7jEoPhO0TeUEqRaBVvScJHolZT75E6HfP0AOU8q9SggZxruxtQ9pGoEmMUohz6VoBBMYQ0J%2BagdLxMYoyO0uhZcYZi6gLPjL7MlaZSGAomz6S%2BoNd%2BPHuj3QspiJlzYXNpcJUhMGrRQno%2BTUAwRTgshVximQnze2fcwMH3YS%2FrHOx02s6L%2Frvi5dofh5f7a9Pf2iXXQevryopv0qVQpEJfHIv62S99R1aLPCYirq2yFqIvuLJaxNxxUbc5QHv%2B9uVLRFXlpzBQ%2Bx7z2urZ9sYkt771VihX6M%2Bs5vAcRF6XK4wgFQETe1rlZHRxm1RaH3EUFm%2BwW3JCOF9QlutzpjOkoaoHCXSwW5X5WsoOYpdTC%2BKuOEMKJRaMWV9Q%2BK5l7%2FizYZWdjdaI2Rrkwm%2Bk0ZMRclT0h0IZDCWysq9BjqkAb6EUnVICNz1bnmbDbdi593Bu5TfqKoSGRobcAHljT9gclDoU76NzbasHU9rE3XpuEzg5vUc3mYIceE0zFl2fcNdWKW8txP7KxXzWaCCKxk9shh%2FZQ2Dex0Za4BZ5wdQtZ3A%2BreGwXqNSaqA2CNQtY9Xmh5W4E8CduIQKO7ZQbyZRz8GM4PfDBK90yFV28btDtGh81ZPFyJj1OXr%2B6BcXUySVNJv&X-Amz-Signature=a0a14b7ba7d3e30167bfd2e015ecbdddb305af31b2942ffc02838c413366bd49&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RILRVUUW%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T033006Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEMaCXVzLXdlc3QtMiJHMEUCIQCeiXkxE2%2FbNuad3vmfA21qfsnQckqx54VGkAh%2BUkII8wIgE0uU%2F1B0eihPBxYCYLapkZOiQCMYdlaEWmJMZQAOK%2FQq%2FwMIbBAAGgw2Mzc0MjMxODM4MDUiDHbjOIRk87J1Hg2iySrcAy3cZxdm%2Fcf2xBBCdNF5tS8Uxq8dWz2QRpbHqXoJiIggEvSi7L1%2BW0XuBnJCNrnl1XhLbmbpotTXC%2BGKtS%2Bzkt90MEBubIvSSN22DfuedSKSvrt66sELytpr1pwd1xC10Zk1iUSuDGBRsGOtR20ZO6O1KDMFPn0ZLovVax8XUHuI%2B88KmZK2WtXWljRjych0Z7aTnV2smxYUu7FySK8soxrxIx1NwrMMXg5kfikzAfLr4fX0S2El%2BgpnkluRXZ%2Bv%2BaEW87VwayJDkP0n3uTmSx9QKUEjviymEbba18IQBo44AjNVwVdA64IDy1A2BNkSl2CSW8u9oCxil5h5rCqTkd8vIqe4F%2BUySuuvV%2B2d%2BN2I1ktIjirj8%2F9TclzFLlEsu1WO9p4XNpHJpRsUdMB432iILAZgdFUOb1reb6NkAYUhIg%2FeoFyY8xOaTRgLd%2Br0OcM4dfkgL7MGYMdEQoF%2FevSvkSh25g3scZxjUie4eRZFMON5fvttsWeDayGq5lfVKJh4zo26UF5Jfd2ACFu9i4IylZn9ZydeLg9PL%2B0UCOfOhK7rWlNV2sArL2%2BMuSzVbdU%2BYn8rNVXhYHsYIt3HKkZ8KTIxF7T5DyQU6FBDEDm9fwK31z8FJSyH639mMJzKyr0GOqUBNcHKYHXLtYqaw4Jo1onGBDilbWvpLqjo4wJsOPFjgOLX0RNmmCcff46qVQhZetVFLX%2Bpjnd3qdBzSzZQqRpdF1hzu0xmFs%2BsNSYZ3L2K3ZAvppaXX%2Br6iW%2BT7xEvA2r8jaJogPY8zrUeDONSuDEUcx89QIQwscghs%2BioRKxbIkuNSzhNlqHcRlrSQWh0BMo3PSoiQFBfRJ%2BdXA54v1xrCvWcf8z1&X-Amz-Signature=69a4bd0290cd5762a18adfa7e75f1c1615b21a3cf898c9ca3014cec4b445cf6b&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WJOBRANY%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T033006Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEMaCXVzLXdlc3QtMiJHMEUCIQC4uEyUlxBlEAyAIC8bhk8EyiyeAoCmPuPRo1%2BKe%2F5Q9QIgeVf4iZXiiJGSa5yvHrM%2B%2FLOPkG2X73jzLWfcYpV0T6Iq%2FwMIbBAAGgw2Mzc0MjMxODM4MDUiDEaEpZ3qrVDsiffBuyrcA47cTb5J2YAt98D4gi3R3FPpXVmX9iGqS1nIbDeA5I0b4dgD5zCOTZyyoLl9ExhKO%2FsZ4vgTvbkH%2B%2F%2FKYq2oNi94BBvFsPt2TI3RtGN6x4%2FjqZ6P1R%2FWKaTX2eTBdLaSWA6AZuqOUUHduCYSkCnFXoHnR2lpUGAG%2FChcwP9EdRrV6UC8dWAUJ4K62t5GSWKiOGrlSGgS%2FsqD55a%2FvCga1riWMeQyaYIB9e1OOn1m5vg3XbZmA1gTfrifPW%2FvgLThe79dhkoZgkMxETwUaeNGIJJqdvT%2Fc8fOgUtzxS1FQwiPEX7VEVJy57Ge49D1aq3qPtt0eOb9BbLpKXmq0uBZsFTEAx7MpaPX00a9CXVYWiD16oEp%2F1X8V6W88OFuIEwfDdBtth2y%2B0PKa%2BOirac9Qi%2B6n9RsFh26hO9Zg%2BqBOW9tzWiYzXWMCYmn9wDsqgi0qVpPbRmmgSGLWwH9NxC5ciJZTuPT24OFPrIy68XrkHxG%2BdkVM7Lx%2FJ9Sa6NCELQQAq%2BuVNvRaaNWrqDyfhvh73StSqkb2B3VCzthF8mF28M5c38du6P6kZy4W3%2Fe0BXveCyLpM289UDDzACB8Mpx3jTG4M7z8JjJZta%2B%2FFh4Q0OmpBXobqtlzCNUp%2F7%2FMI%2FLyr0GOqUBgPbI%2B0cZ1MliWtc%2FMMdLb%2FNpsWCuLzgv9CxRymEjf7dllxqVkWG7eiLsnAVyyXkfbNqguxg%2BO2ZW7RHtXL9j0lUPX8psD1sE4MqCaTqohhTTGFd2wG83UP4CMYeUXfJu1yXVcpBVjOwjmCSo%2BH5OphV81gmQtb5nNdTROvmj7pnFqvE2ccuDYQq1O9%2BRS405qe22fQ4MgRxHHFkvCVve2CmF3N0i&X-Amz-Signature=e5b69bec4c2866cd453f3ca72242417b237949241b2c0195ca0c5fc1cd7e21f4&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XYTCSYTU%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T033005Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEMaCXVzLXdlc3QtMiJIMEYCIQDSnkxhNDpjd82bV3iOVQV7QTckzG1EpmM%2Blr%2FdASbT3QIhAKTRW5HUnZeX9hHB7WNgxo%2FM7au%2FnlD0ya8Nw3DtYFn0Kv8DCGwQABoMNjM3NDIzMTgzODA1IgzFI6z2d9jfYdYbZ%2Fkq3AMKg9Sa8T2NpNQ1QtkwacXbbXjuNLpRGiIP4ZCIjC5KVz6wXxDFwQ%2FeOpvJALaZdP0e%2BW3yrIMqAyBWOyoIu%2ByStjNIR5A8glj9K7KpsP29NYXgh8S4j9CsJSY66Ej4QbxLOgxC%2FXgKe%2Fxx6xqeBJHuWyMSSJR5RTWVotw4XKV%2FcHsqVcJHP5tGZnCUnnC5VW08ubTk2h18frBtL7vbBvMHCwMr0UK7jEoPhO0TeUEqRaBVvScJHolZT75E6HfP0AOU8q9SggZxruxtQ9pGoEmMUohz6VoBBMYQ0J%2BagdLxMYoyO0uhZcYZi6gLPjL7MlaZSGAomz6S%2BoNd%2BPHuj3QspiJlzYXNpcJUhMGrRQno%2BTUAwRTgshVximQnze2fcwMH3YS%2FrHOx02s6L%2Frvi5dofh5f7a9Pf2iXXQevryopv0qVQpEJfHIv62S99R1aLPCYirq2yFqIvuLJaxNxxUbc5QHv%2B9uVLRFXlpzBQ%2Bx7z2urZ9sYkt771VihX6M%2Bs5vAcRF6XK4wgFQETe1rlZHRxm1RaH3EUFm%2BwW3JCOF9QlutzpjOkoaoHCXSwW5X5WsoOYpdTC%2BKuOEMKJRaMWV9Q%2BK5l7%2FizYZWdjdaI2Rrkwm%2Bk0ZMRclT0h0IZDCWysq9BjqkAb6EUnVICNz1bnmbDbdi593Bu5TfqKoSGRobcAHljT9gclDoU76NzbasHU9rE3XpuEzg5vUc3mYIceE0zFl2fcNdWKW8txP7KxXzWaCCKxk9shh%2FZQ2Dex0Za4BZ5wdQtZ3A%2BreGwXqNSaqA2CNQtY9Xmh5W4E8CduIQKO7ZQbyZRz8GM4PfDBK90yFV28btDtGh81ZPFyJj1OXr%2B6BcXUySVNJv&X-Amz-Signature=c24d5565780afce57e5af5d72a591249a99caa8545e567d61cb7aaec8299e46d&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XYTCSYTU%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T033005Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEMaCXVzLXdlc3QtMiJIMEYCIQDSnkxhNDpjd82bV3iOVQV7QTckzG1EpmM%2Blr%2FdASbT3QIhAKTRW5HUnZeX9hHB7WNgxo%2FM7au%2FnlD0ya8Nw3DtYFn0Kv8DCGwQABoMNjM3NDIzMTgzODA1IgzFI6z2d9jfYdYbZ%2Fkq3AMKg9Sa8T2NpNQ1QtkwacXbbXjuNLpRGiIP4ZCIjC5KVz6wXxDFwQ%2FeOpvJALaZdP0e%2BW3yrIMqAyBWOyoIu%2ByStjNIR5A8glj9K7KpsP29NYXgh8S4j9CsJSY66Ej4QbxLOgxC%2FXgKe%2Fxx6xqeBJHuWyMSSJR5RTWVotw4XKV%2FcHsqVcJHP5tGZnCUnnC5VW08ubTk2h18frBtL7vbBvMHCwMr0UK7jEoPhO0TeUEqRaBVvScJHolZT75E6HfP0AOU8q9SggZxruxtQ9pGoEmMUohz6VoBBMYQ0J%2BagdLxMYoyO0uhZcYZi6gLPjL7MlaZSGAomz6S%2BoNd%2BPHuj3QspiJlzYXNpcJUhMGrRQno%2BTUAwRTgshVximQnze2fcwMH3YS%2FrHOx02s6L%2Frvi5dofh5f7a9Pf2iXXQevryopv0qVQpEJfHIv62S99R1aLPCYirq2yFqIvuLJaxNxxUbc5QHv%2B9uVLRFXlpzBQ%2Bx7z2urZ9sYkt771VihX6M%2Bs5vAcRF6XK4wgFQETe1rlZHRxm1RaH3EUFm%2BwW3JCOF9QlutzpjOkoaoHCXSwW5X5WsoOYpdTC%2BKuOEMKJRaMWV9Q%2BK5l7%2FizYZWdjdaI2Rrkwm%2Bk0ZMRclT0h0IZDCWysq9BjqkAb6EUnVICNz1bnmbDbdi593Bu5TfqKoSGRobcAHljT9gclDoU76NzbasHU9rE3XpuEzg5vUc3mYIceE0zFl2fcNdWKW8txP7KxXzWaCCKxk9shh%2FZQ2Dex0Za4BZ5wdQtZ3A%2BreGwXqNSaqA2CNQtY9Xmh5W4E8CduIQKO7ZQbyZRz8GM4PfDBK90yFV28btDtGh81ZPFyJj1OXr%2B6BcXUySVNJv&X-Amz-Signature=47507cc6f8ce52a951219def156212fd7cd7a74768e07a73b3593ea1a80932f7&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XYTCSYTU%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T033005Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEMaCXVzLXdlc3QtMiJIMEYCIQDSnkxhNDpjd82bV3iOVQV7QTckzG1EpmM%2Blr%2FdASbT3QIhAKTRW5HUnZeX9hHB7WNgxo%2FM7au%2FnlD0ya8Nw3DtYFn0Kv8DCGwQABoMNjM3NDIzMTgzODA1IgzFI6z2d9jfYdYbZ%2Fkq3AMKg9Sa8T2NpNQ1QtkwacXbbXjuNLpRGiIP4ZCIjC5KVz6wXxDFwQ%2FeOpvJALaZdP0e%2BW3yrIMqAyBWOyoIu%2ByStjNIR5A8glj9K7KpsP29NYXgh8S4j9CsJSY66Ej4QbxLOgxC%2FXgKe%2Fxx6xqeBJHuWyMSSJR5RTWVotw4XKV%2FcHsqVcJHP5tGZnCUnnC5VW08ubTk2h18frBtL7vbBvMHCwMr0UK7jEoPhO0TeUEqRaBVvScJHolZT75E6HfP0AOU8q9SggZxruxtQ9pGoEmMUohz6VoBBMYQ0J%2BagdLxMYoyO0uhZcYZi6gLPjL7MlaZSGAomz6S%2BoNd%2BPHuj3QspiJlzYXNpcJUhMGrRQno%2BTUAwRTgshVximQnze2fcwMH3YS%2FrHOx02s6L%2Frvi5dofh5f7a9Pf2iXXQevryopv0qVQpEJfHIv62S99R1aLPCYirq2yFqIvuLJaxNxxUbc5QHv%2B9uVLRFXlpzBQ%2Bx7z2urZ9sYkt771VihX6M%2Bs5vAcRF6XK4wgFQETe1rlZHRxm1RaH3EUFm%2BwW3JCOF9QlutzpjOkoaoHCXSwW5X5WsoOYpdTC%2BKuOEMKJRaMWV9Q%2BK5l7%2FizYZWdjdaI2Rrkwm%2Bk0ZMRclT0h0IZDCWysq9BjqkAb6EUnVICNz1bnmbDbdi593Bu5TfqKoSGRobcAHljT9gclDoU76NzbasHU9rE3XpuEzg5vUc3mYIceE0zFl2fcNdWKW8txP7KxXzWaCCKxk9shh%2FZQ2Dex0Za4BZ5wdQtZ3A%2BreGwXqNSaqA2CNQtY9Xmh5W4E8CduIQKO7ZQbyZRz8GM4PfDBK90yFV28btDtGh81ZPFyJj1OXr%2B6BcXUySVNJv&X-Amz-Signature=91244c960e4e46e0720e062b119f5a23cd7854a0536ae9c91a45f76a5fe6b33b&X-Amz-SignedHeaders=host&x-id=GetObject)


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

