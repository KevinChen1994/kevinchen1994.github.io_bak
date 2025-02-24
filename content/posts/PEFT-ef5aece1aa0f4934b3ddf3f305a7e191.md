---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466VFHZALDH%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250224T183337Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEPr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCDs868zC8z75RT3gA\
  Jh4%2BQ1A1AxnjnR0jOeftb17S5CgIhANGJHl255F8HSNrlwO5Dbjca%2FbnkqtWRpKi65QZxjPio\
  Kv8DCDMQABoMNjM3NDIzMTgzODA1IgxJr3KykmzuJa05U0Aq3AMbQPzFqALytImwvfnp8UxOiwXdH\
  A1BCD7xvqVanBS3UGxt9dHahepoc9wWAc1eFa1k1irw5qtiybNlO8YmbDc66mSvTkG1u1t36DJEl4\
  ElJaP7pRA4vE3zov0QqOBSma%2BXr3I0A7SoL1HQ4UGfI7l09Jop1f%2BLBYFMiXhbx9JLmFOXxMg\
  RX4DwlpmQGo8QhOElrV76v3DEbo5OKyYPIagyzqpMfoHxGE6lA8nZsuIm6rSPkpd1uYBSfO%2FA5w\
  JwpCLmFDWMgoJnGiVk5OTei3XU8t1Be4ln%2B%2BUrYD4Q9fS8i5bUzy6erh4q3WpALBeE4bVL3nM\
  ZAyPle%2FcM92Co1OFxcsy58EUGvIimZzF9e4oYDSVfrsnhj2wAndDvxjSECtSNf7H68hmqZsWRCD\
  Qd8LshW8t5wwU44uxe3D29aMLpX9kEJUbuF%2B1gOyJwqFIotHsPDWy%2FSEe7eWIZp71s7iYHcGQ\
  cryQnzKLaNjVmKhKbm63djwbMUFoKTf1Rc5te9lcY5fKZ6Aooeki%2Be5OqmhkeoznRQtifpPsFzy\
  kM2JjN5bieh4iz%2Bukj1DPpjPXlAjqsbp5wt7B7oe8hZogWqAqRXlmiqxuzanDJ6GHcQ7CNVJL5w\
  0A45HHqODMw3zDC3vK9BjqkAc7LjRzI66ZVPM3XDfr6EF7K2WbcLc8SG23XoS8SYpSBQrQoNhUNZs\
  ij7rnKo8%2FH5tVUqej4c3yjtqAhWIkdIh90g%2FJvVBbEa8w9TR0iCBjsFwUDQhMFpjzuyhY3QUf\
  ROe1YGmHnxFJ9t3tBtT9UeX9FI7QCdp7omf84yi33qe0piiqQPGDC97kjsk0dyPXtVHUBkg%2Bd9%\
  2FL2Ya2qCB3KnFnVjzw%2F&X-Amz-Signature=f157f9788c9d6aa0b0211884d73f92a590102a\
  a8cdc943f269c9928f74e9bfed&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466RHV6AWHG%2F20250224%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250224T183207Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEPr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIGYx%2BG82rWZLWMV4v1IF%2FF1sLu6%2B85eeC%2FSb1YG5%2FG7RAiEA5JjmbugX4Nma\
        EahE9iemameQ6qSMVbmAzaH25AA1kNcq%2FwMIMxAAGgw2Mzc0MjMxODM4MDUiDH5J55mdC\
        5jV%2BmBtvyrcA2T2w8m1sbD2OeV8v1z22WXEcx6tM1qsldy%2Bkufe0XazISCHUVk%2F9K\
        B5tFJa36MxbH8qqtGvbqxnsyvMAyX6PlNnlhYtNReGloNrpWkVm9LBEB0ryKkRs9MOATyEU\
        u3w74c%2Fm16FRxrJipxfa9CofFKkXbQ3zGJ47CXWOJLmEVQZE8fab91nvjE6YAyum2UsYu\
        sLCFbcglGaJCkciFw66Y0bWHVI3deuUyfCvDUy8eHavaL%2BDSEZEJdA3riZ2I%2FvwPxBV\
        5jArrlJk%2B9WwRf8haMcBItn4IQmeAaFJ5dN%2BxUR3Y7cxYXA5KZjkCb%2B78Xzm%2F02\
        GBnfhZnGzVfU3d7ltk3hIEwC3DTpgmOgW9lWAbnuTxmko5CabflFrl1ZtDnxVQPyko6WhCV\
        12Hf39qkngdRSUTapMTnc%2F3Z3q0SUlaRQFup6Qrp430cIl8zGwd%2BdTn5xAVOIa1fcKK\
        Oe7HmeCQDYLSInexl%2FdPbHoCuWVrCgtTU%2F7yqmg4jhaPeV83x2hVnngm8i64hp%2F6C\
        AO25r4ahDLcH6IjwJ0ZKpfCSUISPn4jBBA3BVikkvingZEUrQBtvdtWggssXU30PGR8EOyQ\
        y5aFlFAHJGsIy4zYjcvbAKTLWcHL6NyfI95hiYMJnd8r0GOqUB3ZQJn7GObO6ODQ2%2FzrO\
        c14gXh5Mqxv0bWYYg8GWWm2lYshDdjgnxm4uOjm%2F0avhHavAEIvQwJKOy0PQMwXGv0VKy\
        fOvDbUA1dcOubzFy5gZpYMOeI%2BliJlS6oxC88XGfoFF0IAatGgEl7Jes%2F6eEQYCIVph\
        GufNg4gPyoEheEpko65IlqHuSUU62yZa670o2zETG9KA4hyx0lBEFhvVXRXZyEN5U&X-Amz\
        -Signature=d53c4f5b236ad8bcaee30d88dbc73b749b1d70c6a795d576584722c1b4c6\
        259c&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-24T19:32:07.126Z"
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
UPDATE_TIME: "2025-02-24T18:33:43.132Z"
EXPIRY_TIME: "2025-02-24T19:33:32.408Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667F3O6EQJ%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T183332Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIHHh%2B8K41NTXjBmG30gbP6u0h1IeFKSpQ0wfXcpeAzOKAiB8e7QiKL6QSxVe%2B1Pj21VWDe5UzjEcP4gQg%2Buj6uGiJSr%2FAwgzEAAaDDYzNzQyMzE4MzgwNSIM8y1QqaRo1RdSGOklKtwDfAiTEeFo7RYHInU1ptAKQCS5byJdDEblfexy8vmdNMZZSwbQ75PWl%2FJQlzuSyLQFoCS4p3USof9r5bq2xgSQFR93rarUNdi%2FB1YVVLxs4ULYhchDh2p%2BhqETmxENqeOODvFKAFTnfUREylW%2FdxHWB1KcyCSxwrSAMxouXCJTOd5QSaunx9PQXaCK6dpMnMdm8z%2BeF8EGdBIIIf2A7vJWEHAAWkEebBetTp7BS2AlbhXTHxMzl0zjq4oO8XVY7y2fh1bhX875H6wmiCOgWP6JG9vWUxs6NAR50R4UFUgZ7feIYqYrYFR1bR8DGr0tXeDFX%2BYjOjyIt2KywKXcKqHX1%2B5Fm%2FnT%2BNw71aBByLGsIqrN3QOdo8si3x9j0GEIKFvxOh7RN3cZK3Qlou87Je2Lt3tr3twsQNPIyLXJWz1rFQr98u%2BlEBz%2BbLmGQC5AI4Kh8nz7NxhC7a601T3FvGGg2LtcfPxBl7YY9dEmYb2M5gFVETnZ%2FuOI1v4xVXgzxma%2FV2jYZ2VrcE4VVH51zdaVN8ZWX6SGD6NHXPAbOYvgDH76WBzQ2cwFrWNk6NxNIDOgEZnRL%2B6Z5Wzx%2Fax3RN4ac2nnHXXCZTpKV2ub17rkV6s%2FSjy3cKPF0qOoQgUwr93yvQY6pgGIALgcJBGJhnskq6HZUWsQm9VrxzWYoN1ZS6WUdIoHjygIQWM8TudlF9uWNqqfhYgVBoBQPSbQylnJJ2WQ0cWQkvlBvh5J2rg1mLqgXUgLydYOWBuny1tAPKvtV69Hg5WfKYm9MgiroJ6HbMuJmDd%2BEWlxQLLi6lpf8N22sc5yT%2BfYk5Lw4%2FvbPskqxe1cHvUw2jRRFy2Zt6eyRJ%2F9blBpikJNN0N3&X-Amz-Signature=ecdcfec6d8e8b86c19168559a841da50ba74dfee8377506828ac045e9ddf7c5d&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667F3O6EQJ%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T183332Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIHHh%2B8K41NTXjBmG30gbP6u0h1IeFKSpQ0wfXcpeAzOKAiB8e7QiKL6QSxVe%2B1Pj21VWDe5UzjEcP4gQg%2Buj6uGiJSr%2FAwgzEAAaDDYzNzQyMzE4MzgwNSIM8y1QqaRo1RdSGOklKtwDfAiTEeFo7RYHInU1ptAKQCS5byJdDEblfexy8vmdNMZZSwbQ75PWl%2FJQlzuSyLQFoCS4p3USof9r5bq2xgSQFR93rarUNdi%2FB1YVVLxs4ULYhchDh2p%2BhqETmxENqeOODvFKAFTnfUREylW%2FdxHWB1KcyCSxwrSAMxouXCJTOd5QSaunx9PQXaCK6dpMnMdm8z%2BeF8EGdBIIIf2A7vJWEHAAWkEebBetTp7BS2AlbhXTHxMzl0zjq4oO8XVY7y2fh1bhX875H6wmiCOgWP6JG9vWUxs6NAR50R4UFUgZ7feIYqYrYFR1bR8DGr0tXeDFX%2BYjOjyIt2KywKXcKqHX1%2B5Fm%2FnT%2BNw71aBByLGsIqrN3QOdo8si3x9j0GEIKFvxOh7RN3cZK3Qlou87Je2Lt3tr3twsQNPIyLXJWz1rFQr98u%2BlEBz%2BbLmGQC5AI4Kh8nz7NxhC7a601T3FvGGg2LtcfPxBl7YY9dEmYb2M5gFVETnZ%2FuOI1v4xVXgzxma%2FV2jYZ2VrcE4VVH51zdaVN8ZWX6SGD6NHXPAbOYvgDH76WBzQ2cwFrWNk6NxNIDOgEZnRL%2B6Z5Wzx%2Fax3RN4ac2nnHXXCZTpKV2ub17rkV6s%2FSjy3cKPF0qOoQgUwr93yvQY6pgGIALgcJBGJhnskq6HZUWsQm9VrxzWYoN1ZS6WUdIoHjygIQWM8TudlF9uWNqqfhYgVBoBQPSbQylnJJ2WQ0cWQkvlBvh5J2rg1mLqgXUgLydYOWBuny1tAPKvtV69Hg5WfKYm9MgiroJ6HbMuJmDd%2BEWlxQLLi6lpf8N22sc5yT%2BfYk5Lw4%2FvbPskqxe1cHvUw2jRRFy2Zt6eyRJ%2F9blBpikJNN0N3&X-Amz-Signature=7ea07102c4c43f33fff3d77e2d628980a3f926cdaeb4c563d7230028a2bd81dc&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667F3O6EQJ%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T183332Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIHHh%2B8K41NTXjBmG30gbP6u0h1IeFKSpQ0wfXcpeAzOKAiB8e7QiKL6QSxVe%2B1Pj21VWDe5UzjEcP4gQg%2Buj6uGiJSr%2FAwgzEAAaDDYzNzQyMzE4MzgwNSIM8y1QqaRo1RdSGOklKtwDfAiTEeFo7RYHInU1ptAKQCS5byJdDEblfexy8vmdNMZZSwbQ75PWl%2FJQlzuSyLQFoCS4p3USof9r5bq2xgSQFR93rarUNdi%2FB1YVVLxs4ULYhchDh2p%2BhqETmxENqeOODvFKAFTnfUREylW%2FdxHWB1KcyCSxwrSAMxouXCJTOd5QSaunx9PQXaCK6dpMnMdm8z%2BeF8EGdBIIIf2A7vJWEHAAWkEebBetTp7BS2AlbhXTHxMzl0zjq4oO8XVY7y2fh1bhX875H6wmiCOgWP6JG9vWUxs6NAR50R4UFUgZ7feIYqYrYFR1bR8DGr0tXeDFX%2BYjOjyIt2KywKXcKqHX1%2B5Fm%2FnT%2BNw71aBByLGsIqrN3QOdo8si3x9j0GEIKFvxOh7RN3cZK3Qlou87Je2Lt3tr3twsQNPIyLXJWz1rFQr98u%2BlEBz%2BbLmGQC5AI4Kh8nz7NxhC7a601T3FvGGg2LtcfPxBl7YY9dEmYb2M5gFVETnZ%2FuOI1v4xVXgzxma%2FV2jYZ2VrcE4VVH51zdaVN8ZWX6SGD6NHXPAbOYvgDH76WBzQ2cwFrWNk6NxNIDOgEZnRL%2B6Z5Wzx%2Fax3RN4ac2nnHXXCZTpKV2ub17rkV6s%2FSjy3cKPF0qOoQgUwr93yvQY6pgGIALgcJBGJhnskq6HZUWsQm9VrxzWYoN1ZS6WUdIoHjygIQWM8TudlF9uWNqqfhYgVBoBQPSbQylnJJ2WQ0cWQkvlBvh5J2rg1mLqgXUgLydYOWBuny1tAPKvtV69Hg5WfKYm9MgiroJ6HbMuJmDd%2BEWlxQLLi6lpf8N22sc5yT%2BfYk5Lw4%2FvbPskqxe1cHvUw2jRRFy2Zt6eyRJ%2F9blBpikJNN0N3&X-Amz-Signature=7651e3b59cb2d2e65d96abd0ec3ff7128a160cd58afa70a656c2835271fc0110&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667F3O6EQJ%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T183332Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIHHh%2B8K41NTXjBmG30gbP6u0h1IeFKSpQ0wfXcpeAzOKAiB8e7QiKL6QSxVe%2B1Pj21VWDe5UzjEcP4gQg%2Buj6uGiJSr%2FAwgzEAAaDDYzNzQyMzE4MzgwNSIM8y1QqaRo1RdSGOklKtwDfAiTEeFo7RYHInU1ptAKQCS5byJdDEblfexy8vmdNMZZSwbQ75PWl%2FJQlzuSyLQFoCS4p3USof9r5bq2xgSQFR93rarUNdi%2FB1YVVLxs4ULYhchDh2p%2BhqETmxENqeOODvFKAFTnfUREylW%2FdxHWB1KcyCSxwrSAMxouXCJTOd5QSaunx9PQXaCK6dpMnMdm8z%2BeF8EGdBIIIf2A7vJWEHAAWkEebBetTp7BS2AlbhXTHxMzl0zjq4oO8XVY7y2fh1bhX875H6wmiCOgWP6JG9vWUxs6NAR50R4UFUgZ7feIYqYrYFR1bR8DGr0tXeDFX%2BYjOjyIt2KywKXcKqHX1%2B5Fm%2FnT%2BNw71aBByLGsIqrN3QOdo8si3x9j0GEIKFvxOh7RN3cZK3Qlou87Je2Lt3tr3twsQNPIyLXJWz1rFQr98u%2BlEBz%2BbLmGQC5AI4Kh8nz7NxhC7a601T3FvGGg2LtcfPxBl7YY9dEmYb2M5gFVETnZ%2FuOI1v4xVXgzxma%2FV2jYZ2VrcE4VVH51zdaVN8ZWX6SGD6NHXPAbOYvgDH76WBzQ2cwFrWNk6NxNIDOgEZnRL%2B6Z5Wzx%2Fax3RN4ac2nnHXXCZTpKV2ub17rkV6s%2FSjy3cKPF0qOoQgUwr93yvQY6pgGIALgcJBGJhnskq6HZUWsQm9VrxzWYoN1ZS6WUdIoHjygIQWM8TudlF9uWNqqfhYgVBoBQPSbQylnJJ2WQ0cWQkvlBvh5J2rg1mLqgXUgLydYOWBuny1tAPKvtV69Hg5WfKYm9MgiroJ6HbMuJmDd%2BEWlxQLLi6lpf8N22sc5yT%2BfYk5Lw4%2FvbPskqxe1cHvUw2jRRFy2Zt6eyRJ%2F9blBpikJNN0N3&X-Amz-Signature=c7c402d03fdb30c8a504560558137f365676291283a4033ff37dc29874df8bc9&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667F3O6EQJ%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T183332Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIHHh%2B8K41NTXjBmG30gbP6u0h1IeFKSpQ0wfXcpeAzOKAiB8e7QiKL6QSxVe%2B1Pj21VWDe5UzjEcP4gQg%2Buj6uGiJSr%2FAwgzEAAaDDYzNzQyMzE4MzgwNSIM8y1QqaRo1RdSGOklKtwDfAiTEeFo7RYHInU1ptAKQCS5byJdDEblfexy8vmdNMZZSwbQ75PWl%2FJQlzuSyLQFoCS4p3USof9r5bq2xgSQFR93rarUNdi%2FB1YVVLxs4ULYhchDh2p%2BhqETmxENqeOODvFKAFTnfUREylW%2FdxHWB1KcyCSxwrSAMxouXCJTOd5QSaunx9PQXaCK6dpMnMdm8z%2BeF8EGdBIIIf2A7vJWEHAAWkEebBetTp7BS2AlbhXTHxMzl0zjq4oO8XVY7y2fh1bhX875H6wmiCOgWP6JG9vWUxs6NAR50R4UFUgZ7feIYqYrYFR1bR8DGr0tXeDFX%2BYjOjyIt2KywKXcKqHX1%2B5Fm%2FnT%2BNw71aBByLGsIqrN3QOdo8si3x9j0GEIKFvxOh7RN3cZK3Qlou87Je2Lt3tr3twsQNPIyLXJWz1rFQr98u%2BlEBz%2BbLmGQC5AI4Kh8nz7NxhC7a601T3FvGGg2LtcfPxBl7YY9dEmYb2M5gFVETnZ%2FuOI1v4xVXgzxma%2FV2jYZ2VrcE4VVH51zdaVN8ZWX6SGD6NHXPAbOYvgDH76WBzQ2cwFrWNk6NxNIDOgEZnRL%2B6Z5Wzx%2Fax3RN4ac2nnHXXCZTpKV2ub17rkV6s%2FSjy3cKPF0qOoQgUwr93yvQY6pgGIALgcJBGJhnskq6HZUWsQm9VrxzWYoN1ZS6WUdIoHjygIQWM8TudlF9uWNqqfhYgVBoBQPSbQylnJJ2WQ0cWQkvlBvh5J2rg1mLqgXUgLydYOWBuny1tAPKvtV69Hg5WfKYm9MgiroJ6HbMuJmDd%2BEWlxQLLi6lpf8N22sc5yT%2BfYk5Lw4%2FvbPskqxe1cHvUw2jRRFy2Zt6eyRJ%2F9blBpikJNN0N3&X-Amz-Signature=b666768fde91898959244cca8563ce8fb9bdaa16fe4ae4c2306f153960e961ba&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662BU75DGJ%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T183333Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIAJDxhI0Ou1%2FGksrtSqmHEIAwvLnZ7eDb%2BtUT5q7GG1XAiEAzppNqq2QyUR2JIpptARsQI7ARjY6Q%2Fn%2BzJMZCJLmTcIq%2FwMIMxAAGgw2Mzc0MjMxODM4MDUiDDQ7iR6YVac1nRbS6CrcA4WHCpz1Uu3yX4JeGZ%2BV7k%2FWD4E7pJSnXU5T5YlmoB%2FNXFVQZtD7jabhC6DPBVade0DvPqgJcscN994syo1y4hq1R5NPKmBUDbPAd5OZaYSUtEMnuS%2BUIYWUFAJK8xzyi7iGopUi83gShTsypqBcgxamcWmLEk3U527HGJa9AEWIngNCXC5BqPLUDMxMSbMGem%2B0aiDAi0MNWdIZAohERxD8zcpRaxbYU9ONw597cjeFrn7UFmdFNCCANxRyW2levxkr0QymLjr%2Fda3J1mBO%2FSlXctHSOUkYYcDt4FOsW4niBD01%2BStbbEvVRMHekgOG1lUviKj02ZdhKhTq3d45TB1%2BNOpDq6TXpD9gEYTqSXoTnGUUgjC7Gk0pipMRVkgUEs8Tf8mRxlEIxk9oNhSAjq1kAlyFrFkoXjhtz5sY7LICoopO0cMrT2%2BvsFhVmDc5A3GrY0n9UXZcoq2Mhcx%2F8%2B6e2pA0UVz8VFadqcjdRsORI0YzvE01W4BPy7BkBwfUp89Nd%2FGrbz71Cj80lw3p8Pn2NqfKNFTKt%2Fjq2Sg%2FY%2BRmGS6WXySolBFqfBtytOehUenjH1I%2F%2BAbgt3VjIODBYllXqYO%2FuK6NRLNdjbeum1y4%2BVKQzuVJ8mhP4RfxMLHd8r0GOqUBH4ZeYZKP4gBol6bFlQqsZISgod2afefvvMhUb%2BowDsjtaruXrIDJ4%2BklTQzhc1JoEv2Q5BqRuPqrKloxpygv%2BsCRrsiePSHhxz4wNI%2BWEJ6rEJ5ywLlVsnI9jTGwnj5JnOymWRNb9Kvl5Mq4N6bmYYz2sPYGxM64WDqw3qn4zJRuWG3EUpFyBtyFOD%2FoX3aKh7XulrrX4IlnV2YefzB2mINb4mwS&X-Amz-Signature=44e908b5581eb4679a251e7227633b69b24976f6873584eb112063eea922fcdb&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46667YW5FBF%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T183337Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDr6Lsd61bIy0Y8aqU10iWfE2R9K5owQdWfSY2zgUir8wIgIhjMGZ8ngZ40q3FuWT4E8bI7d0j0zU%2Fqmo81XIUIIacq%2FwMIMxAAGgw2Mzc0MjMxODM4MDUiDCPrxzhP1fseAXXe2SrcAx7NfTwTsLMWYEf9EryBeOQJyKssC1XoxtXr9WsdrZjMPY%2B1z1qGrEpa5HYVfmpIHJ1w4d%2BUiPOWm4Si%2FKaZ97Y1lpFJI3Q4cdO3173fyBoWCtKm7Uq85k5%2B4t7giZQTS6bso2HKa7I7qe198Mi496BGlEfgSwkLoRGsF0ikpxEn86HEJYsk2n7DdKBRIrSKNBGcE%2B5%2F0IZ20OkAZ2fIViHQnjv88BwDZgJyRVWaLUwttex2Xpol%2FErBqmREeEHPHn1g1UIOpwPVBLouDNf0ct79r9q%2Fn%2Bwl4GaydGqb9zwlOSAglVlOUfa%2Fd6qxkGC7BUUSgiCas5EKkONTXRrtlaIPRxVCqQOO13000iuxEYY3JjsaxH6o5P9LamoUYnfdpMjkgz3eoJzmH9kN5zwXaRzgx8leRd9RYVh21VcUp%2FfVUOOL73WtrLW7Xgwx98sSfEPmpNY3jUCzAoqHgMAWpnR4mXoBJGtcdjqfGpl4w2pc48NpKQA1ws%2BUznbxTtQFnjVDCUYLUoIRWDsvoKVlYgPTJ91gH4uZvWcUr1YBeVN6nFPt%2Bov%2FuyeJXKf%2FLALEZmhsJ%2FZkc4ORaeaXVvOlVtkbKyMVvdytYjNotS3v4z5UY7%2B1Dtz8rgQLIgoIMMne8r0GOqUBewTJVx9dWvzwtVbrgsAdSqh3V5aE8u8hGGw%2FhaMxZ8XD6vMv7x9j%2FBtKNM5VKnV9c%2BLKgzx1hZVZNXKVQaLSCbkFMN7mZeswS7l9YYVbfFtHe3c%2FkYCP3D3P6fHAaLLq08xfqMr59JVNI%2B0ELlW049DO4ZexHL5pc1gdBPeX8Ar3phWrvTopodzv%2Fels7Chv6xuGrNjhE9BiyhrJta0ObH2yS2m1&X-Amz-Signature=113c9eadaeb2889666ae8e1a1732854b879fbe7c8cfcc8711c3cfa4df21dc227&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667F3O6EQJ%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T183332Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIHHh%2B8K41NTXjBmG30gbP6u0h1IeFKSpQ0wfXcpeAzOKAiB8e7QiKL6QSxVe%2B1Pj21VWDe5UzjEcP4gQg%2Buj6uGiJSr%2FAwgzEAAaDDYzNzQyMzE4MzgwNSIM8y1QqaRo1RdSGOklKtwDfAiTEeFo7RYHInU1ptAKQCS5byJdDEblfexy8vmdNMZZSwbQ75PWl%2FJQlzuSyLQFoCS4p3USof9r5bq2xgSQFR93rarUNdi%2FB1YVVLxs4ULYhchDh2p%2BhqETmxENqeOODvFKAFTnfUREylW%2FdxHWB1KcyCSxwrSAMxouXCJTOd5QSaunx9PQXaCK6dpMnMdm8z%2BeF8EGdBIIIf2A7vJWEHAAWkEebBetTp7BS2AlbhXTHxMzl0zjq4oO8XVY7y2fh1bhX875H6wmiCOgWP6JG9vWUxs6NAR50R4UFUgZ7feIYqYrYFR1bR8DGr0tXeDFX%2BYjOjyIt2KywKXcKqHX1%2B5Fm%2FnT%2BNw71aBByLGsIqrN3QOdo8si3x9j0GEIKFvxOh7RN3cZK3Qlou87Je2Lt3tr3twsQNPIyLXJWz1rFQr98u%2BlEBz%2BbLmGQC5AI4Kh8nz7NxhC7a601T3FvGGg2LtcfPxBl7YY9dEmYb2M5gFVETnZ%2FuOI1v4xVXgzxma%2FV2jYZ2VrcE4VVH51zdaVN8ZWX6SGD6NHXPAbOYvgDH76WBzQ2cwFrWNk6NxNIDOgEZnRL%2B6Z5Wzx%2Fax3RN4ac2nnHXXCZTpKV2ub17rkV6s%2FSjy3cKPF0qOoQgUwr93yvQY6pgGIALgcJBGJhnskq6HZUWsQm9VrxzWYoN1ZS6WUdIoHjygIQWM8TudlF9uWNqqfhYgVBoBQPSbQylnJJ2WQ0cWQkvlBvh5J2rg1mLqgXUgLydYOWBuny1tAPKvtV69Hg5WfKYm9MgiroJ6HbMuJmDd%2BEWlxQLLi6lpf8N22sc5yT%2BfYk5Lw4%2FvbPskqxe1cHvUw2jRRFy2Zt6eyRJ%2F9blBpikJNN0N3&X-Amz-Signature=56afaed48a34ed35560f399c22b967784677dca429d4a6328299dad9434199b5&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667F3O6EQJ%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T183332Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIHHh%2B8K41NTXjBmG30gbP6u0h1IeFKSpQ0wfXcpeAzOKAiB8e7QiKL6QSxVe%2B1Pj21VWDe5UzjEcP4gQg%2Buj6uGiJSr%2FAwgzEAAaDDYzNzQyMzE4MzgwNSIM8y1QqaRo1RdSGOklKtwDfAiTEeFo7RYHInU1ptAKQCS5byJdDEblfexy8vmdNMZZSwbQ75PWl%2FJQlzuSyLQFoCS4p3USof9r5bq2xgSQFR93rarUNdi%2FB1YVVLxs4ULYhchDh2p%2BhqETmxENqeOODvFKAFTnfUREylW%2FdxHWB1KcyCSxwrSAMxouXCJTOd5QSaunx9PQXaCK6dpMnMdm8z%2BeF8EGdBIIIf2A7vJWEHAAWkEebBetTp7BS2AlbhXTHxMzl0zjq4oO8XVY7y2fh1bhX875H6wmiCOgWP6JG9vWUxs6NAR50R4UFUgZ7feIYqYrYFR1bR8DGr0tXeDFX%2BYjOjyIt2KywKXcKqHX1%2B5Fm%2FnT%2BNw71aBByLGsIqrN3QOdo8si3x9j0GEIKFvxOh7RN3cZK3Qlou87Je2Lt3tr3twsQNPIyLXJWz1rFQr98u%2BlEBz%2BbLmGQC5AI4Kh8nz7NxhC7a601T3FvGGg2LtcfPxBl7YY9dEmYb2M5gFVETnZ%2FuOI1v4xVXgzxma%2FV2jYZ2VrcE4VVH51zdaVN8ZWX6SGD6NHXPAbOYvgDH76WBzQ2cwFrWNk6NxNIDOgEZnRL%2B6Z5Wzx%2Fax3RN4ac2nnHXXCZTpKV2ub17rkV6s%2FSjy3cKPF0qOoQgUwr93yvQY6pgGIALgcJBGJhnskq6HZUWsQm9VrxzWYoN1ZS6WUdIoHjygIQWM8TudlF9uWNqqfhYgVBoBQPSbQylnJJ2WQ0cWQkvlBvh5J2rg1mLqgXUgLydYOWBuny1tAPKvtV69Hg5WfKYm9MgiroJ6HbMuJmDd%2BEWlxQLLi6lpf8N22sc5yT%2BfYk5Lw4%2FvbPskqxe1cHvUw2jRRFy2Zt6eyRJ%2F9blBpikJNN0N3&X-Amz-Signature=e6995b299473d2523027f0e7b7c08e309c1abfd6a79ac56ec38d4edafaaba6d7&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667F3O6EQJ%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T183332Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIHHh%2B8K41NTXjBmG30gbP6u0h1IeFKSpQ0wfXcpeAzOKAiB8e7QiKL6QSxVe%2B1Pj21VWDe5UzjEcP4gQg%2Buj6uGiJSr%2FAwgzEAAaDDYzNzQyMzE4MzgwNSIM8y1QqaRo1RdSGOklKtwDfAiTEeFo7RYHInU1ptAKQCS5byJdDEblfexy8vmdNMZZSwbQ75PWl%2FJQlzuSyLQFoCS4p3USof9r5bq2xgSQFR93rarUNdi%2FB1YVVLxs4ULYhchDh2p%2BhqETmxENqeOODvFKAFTnfUREylW%2FdxHWB1KcyCSxwrSAMxouXCJTOd5QSaunx9PQXaCK6dpMnMdm8z%2BeF8EGdBIIIf2A7vJWEHAAWkEebBetTp7BS2AlbhXTHxMzl0zjq4oO8XVY7y2fh1bhX875H6wmiCOgWP6JG9vWUxs6NAR50R4UFUgZ7feIYqYrYFR1bR8DGr0tXeDFX%2BYjOjyIt2KywKXcKqHX1%2B5Fm%2FnT%2BNw71aBByLGsIqrN3QOdo8si3x9j0GEIKFvxOh7RN3cZK3Qlou87Je2Lt3tr3twsQNPIyLXJWz1rFQr98u%2BlEBz%2BbLmGQC5AI4Kh8nz7NxhC7a601T3FvGGg2LtcfPxBl7YY9dEmYb2M5gFVETnZ%2FuOI1v4xVXgzxma%2FV2jYZ2VrcE4VVH51zdaVN8ZWX6SGD6NHXPAbOYvgDH76WBzQ2cwFrWNk6NxNIDOgEZnRL%2B6Z5Wzx%2Fax3RN4ac2nnHXXCZTpKV2ub17rkV6s%2FSjy3cKPF0qOoQgUwr93yvQY6pgGIALgcJBGJhnskq6HZUWsQm9VrxzWYoN1ZS6WUdIoHjygIQWM8TudlF9uWNqqfhYgVBoBQPSbQylnJJ2WQ0cWQkvlBvh5J2rg1mLqgXUgLydYOWBuny1tAPKvtV69Hg5WfKYm9MgiroJ6HbMuJmDd%2BEWlxQLLi6lpf8N22sc5yT%2BfYk5Lw4%2FvbPskqxe1cHvUw2jRRFy2Zt6eyRJ%2F9blBpikJNN0N3&X-Amz-Signature=669b271a0e0a5943bf253a248c65becd1ed1e631b56bcfc987b2e4776c21cc59&X-Amz-SignedHeaders=host&x-id=GetObject)


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

