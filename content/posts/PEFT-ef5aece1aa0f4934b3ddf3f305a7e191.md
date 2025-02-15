---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4662XIYAHY2%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250215T202256Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjECQaCXVzLXdlc3QtMiJGMEQCIG2bMKUR7lsdEuT4E%2BeNwdE9vQv8poHEF2iPzSWNdOGdAiBTk\
  n4y%2FDIw8QsJxi6Z1cXYPlYV3bFohLjgpf%2BI6ccHWyr%2FAwhNEAAaDDYzNzQyMzE4MzgwNSIM\
  7F3R9axLBxGNuhA%2FKtwDP8KJMBll7wX7lXBVt0CHc%2Fc1ywKqZgO8QbMSv%2BJc2HVBON0vQo7\
  m09I1xey3K46ZPmr0RYly%2FywvZxI%2FClT5LC788X%2BzeVqvjx%2BB8KpLI1cbPzk0h0hLeW22\
  H9aKxcjqvjyh1b8ssB3%2BnxGHyWwXzrX0hFY6ARx0mvBlL3KEu029%2BFZSsrMjirvkHO7QpufOD\
  7vIO%2F0gZPq0kIlbDvejjszLBgytiGKnlLkPo35JgS3r83yMamUO1ZAWuYJKplt1tuYuNC2Cvvsr\
  hw6MWmZQzqMr674kSOO5QygnskKu0dt7k%2FoVZVuqJ%2FF2KGinudeYkz0Y1F2HLczAS1I1hLUnk\
  J1nzWwlFUu8hBw9pWnNzYjUDW%2BEoMRLDSMLy%2BhCpRWYYgskll8nQ6rxcc4qB55R2rTdNuVYRp\
  %2BQFeREbRa2cOFxD6oKzFjUj%2B%2FkFUKGAZrqPPiQ4XtDk%2BhylFqs8cMYdHl%2Btoz9aUiUe\
  vnuRbJgc5qlqA8re2NafsA3ZmRKo9UuQySoDfALvP7nmpubSD8o2qvwMlui%2Fgy4b1r9WOcTtOaA\
  DnMufQ0dm7IqJVSxwhWACKDYefN9qF83shFEDardbxNtT3Es5Mt0FhaH4kk3SRSm%2FvwY3cojC8Q\
  tc2Aw8NjDvQY6pgEf5%2BDaXrsp%2BNoFXoSWh%2FXSmSb1ob1WEl4VCuWPCSLKmqhIGyEq4I8AT8\
  zQDa3JaSnq1uRPgpjxw7SAxKYEjij4qZcs2ojUUWs4AvNkIIjjLZYgkp8jTMlwt9Fux51PR4gL%2F\
  GkYn1u6VZgm9xCQ51n6wDPcH5D8nu5oX%2BRV0bbXI4YdidO0qnFPXFgR4Zdh3QkLIspjhBfaZCtV\
  %2B7oxiBiwDHRDa2pq&X-Amz-Signature=cf39449508712b25b3b5e3813dbd4fc731447a7078\
  ce5c89cf2383eedc72be8a&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466VWYURMQP%2F20250215%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250215T202137Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjECQaCXVzLXdlc3QtMiJGMEQCICY1JnZ%2FvsR8dnoMnv4MRNBozM5Dt\
        ToB5GTTPywHJkF5AiAkGwWoNPoSQ5jXbbuWkRv7HWLhZiWebUHtbtAELnvEhyr%2FAwhNEA\
        AaDDYzNzQyMzE4MzgwNSIMJR7Yo38UA7A5VHMqKtwDOzKTg457CjgvUhUnq2oEDzhJO3%2B\
        21jc21HJQ7pj0v79iW8Q%2FeWXj0TI8YfO24Rdb0uIpWSuoOQSjfOq3OaLdNkLQOKUfW83m\
        7TYOdTiimHdMaZ8ASnUftB6w4tdVBcw3Ks1dNhGchT%2BGpqKtcKjmw2JiHA0XMEIQ9cHCh\
        CGKInXslSwGQSKqGtwhyNI64d9q16byXXHxsUyvbgaMEzaCFJE6ZV4iouIaR%2FaGDivoDw\
        TQy0j%2FKrrfMUpksn0PSCOtbZFN5%2FuCDAz9UWmQ%2FqVLd3QNJ1NuX9E4YptCVHcaJX9\
        lVDv%2B7qhIffT3fsvGcRJe3O5QVYZaeKhJ9TzVNJmSZY%2BV7Uk%2FQ6Agkph%2FvIt9Tc\
        TsbORju4GWGmgIyeAbedsV1NEUk8ZtaX6pFLJ%2BsaiXMjJ2wo3kh8ez%2BjkMKF8bWPmLK\
        rZddcSIW0MibDsRv3Y9putXEyxzgyns3K91ZToRGe1skNgC%2Fmv2LX515sHSrWc4WmNAbv\
        3imFp96GRamBp2kZ5BUn0ZeDCmnZZoaJ9RlvBXWB%2BIDBRMIZajfFQGNXKa0fNiWF9W8sY\
        wtTuNU84Gyj5rIhBPPwiza2dtNHpk5Vv1ZN3VxLgMmJbDyrazPgSjnTzWtCK%2B40LSMXow\
        5NjDvQY6pgHfUZOI685Z%2Bn%2B1ObP2U1Gi2UL6%2FDvbDU40R6ICsjLs%2FVc%2B9vX2C\
        pyAeRU%2FrlRrXbGX6vgMhIq6VUxBh1vFMZAGdUJoutYQapS5HbAOhEr5Yp1o%2BW%2F4Z3\
        u2HA%2FWO%2FFDi7gKUjZpd3Ifo4yuB7Y8LPoTnxwIdi7ivpPjRwjIDEpBxE9Natn9AxIuR\
        mAq812%2BPidrOjlJFsZoxX6FFECiNkFzA64lOQFn&X-Amz-Signature=600482d40820d\
        a1c0e6df15b6ac3dd587f63df46ee7e1013d90d6349f2b40bb1&X-Amz-SignedHeaders\
        =host&x-id=GetObject"
      expiry_time: "2025-02-15T21:21:37.897Z"
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
UPDATE_TIME: "2025-02-15T20:23:03.532Z"
EXPIRY_TIME: "2025-02-15T21:22:54.440Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662UVWBECK%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T202254Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECQaCXVzLXdlc3QtMiJIMEYCIQD3hUCxuqmL5bFq4u7W1LzvpJ2%2BNfscVNXCR9NbZ5Sn2QIhAK3vTmodsLKkrEcN%2F92fVGJxb08K57HWd84zYf7WnuH6Kv8DCE0QABoMNjM3NDIzMTgzODA1IgyEcpsKKUBhbeu1RPwq3ANhe6pwuQVfFYlQXPRfYtRlhYXD3eFuSku5sjZ%2FlgsUtgl6X%2BRYZs%2BoDH3r%2BDiT9insGX8JJu7WYBZupBs%2BrQn6gfb4VcpOqZrLg6meRjZrTXkGowDDVmd%2B%2BtZ0lXgcy2eansUx2HyFO%2BllPHOSg9cCtbhOo87KeYmuXPUcPBqOgUUts8Ing8nL2L%2Bpfik%2BQucpcs4lzzIh%2BK6l%2BdlZSOQNDO68ljLsfTbprF1t1mZJhlal52HASkPnmngZe5d0NypGzbFItnXkHERp0YB%2FglsEGoZihfwWNVsNn7wIrZK1c2558AJg1R31Li1ZpfrfT9VNW1QZEGG6remT%2Bnx49EkCojfLx88AdbZy%2F0niRemZqUuAuIeHiEfPXaN1aT5ZFO4q3t8RT0GkS9T0UIy6DW0spH2uXKbXNmVI%2BOOWaxXFVBCYyX1N4FcFNhI0IcIMN4rIBUJ%2FSO6ddfjOHEqEz7qD%2BMnsosijhxrlne0Lz%2FZOJSY7hb21V8uAzENBW95bEb26yFJnnQCY0747uLg%2F3YjBTF8ewdcKlz14vFuRJSRxBbq4JE%2Bo3TPknC8bY48E0uU8v2KUZ%2BKt8HWwyykJvCca7TgvdX%2BpL4UCcvgUBGlEFgJkp9tqmda8LjrsEzD62MO9BjqkAZZBqhIou540%2BIIWeY9lx%2FqdgQ0R6DcyJtNNmWxZwBkvQLT34uwHQYivw93XADpDT1r3eziK5G7HulQjQc9ATbTqK%2B9gKcy6uA%2BhXug1%2BimRm4Qm29A00mxk3MTuO0me6As7Xh1ufvySv7y4mxFdveVNoPHrZ7biFexRuM9Dd%2FpS6rByTV0oR0MKs2%2FzwMqSmOlp7nvtvv8E3XXYdHt2wgfn80aO&X-Amz-Signature=71267b0aadcf012046e06efb1e447042097cc84d7368776694cd713772efe1df&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662UVWBECK%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T202254Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECQaCXVzLXdlc3QtMiJIMEYCIQD3hUCxuqmL5bFq4u7W1LzvpJ2%2BNfscVNXCR9NbZ5Sn2QIhAK3vTmodsLKkrEcN%2F92fVGJxb08K57HWd84zYf7WnuH6Kv8DCE0QABoMNjM3NDIzMTgzODA1IgyEcpsKKUBhbeu1RPwq3ANhe6pwuQVfFYlQXPRfYtRlhYXD3eFuSku5sjZ%2FlgsUtgl6X%2BRYZs%2BoDH3r%2BDiT9insGX8JJu7WYBZupBs%2BrQn6gfb4VcpOqZrLg6meRjZrTXkGowDDVmd%2B%2BtZ0lXgcy2eansUx2HyFO%2BllPHOSg9cCtbhOo87KeYmuXPUcPBqOgUUts8Ing8nL2L%2Bpfik%2BQucpcs4lzzIh%2BK6l%2BdlZSOQNDO68ljLsfTbprF1t1mZJhlal52HASkPnmngZe5d0NypGzbFItnXkHERp0YB%2FglsEGoZihfwWNVsNn7wIrZK1c2558AJg1R31Li1ZpfrfT9VNW1QZEGG6remT%2Bnx49EkCojfLx88AdbZy%2F0niRemZqUuAuIeHiEfPXaN1aT5ZFO4q3t8RT0GkS9T0UIy6DW0spH2uXKbXNmVI%2BOOWaxXFVBCYyX1N4FcFNhI0IcIMN4rIBUJ%2FSO6ddfjOHEqEz7qD%2BMnsosijhxrlne0Lz%2FZOJSY7hb21V8uAzENBW95bEb26yFJnnQCY0747uLg%2F3YjBTF8ewdcKlz14vFuRJSRxBbq4JE%2Bo3TPknC8bY48E0uU8v2KUZ%2BKt8HWwyykJvCca7TgvdX%2BpL4UCcvgUBGlEFgJkp9tqmda8LjrsEzD62MO9BjqkAZZBqhIou540%2BIIWeY9lx%2FqdgQ0R6DcyJtNNmWxZwBkvQLT34uwHQYivw93XADpDT1r3eziK5G7HulQjQc9ATbTqK%2B9gKcy6uA%2BhXug1%2BimRm4Qm29A00mxk3MTuO0me6As7Xh1ufvySv7y4mxFdveVNoPHrZ7biFexRuM9Dd%2FpS6rByTV0oR0MKs2%2FzwMqSmOlp7nvtvv8E3XXYdHt2wgfn80aO&X-Amz-Signature=414abc2f9a4277cb4e887037f36267340f2184ea9d503d05fd973185f1e2e3a8&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662UVWBECK%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T202254Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECQaCXVzLXdlc3QtMiJIMEYCIQD3hUCxuqmL5bFq4u7W1LzvpJ2%2BNfscVNXCR9NbZ5Sn2QIhAK3vTmodsLKkrEcN%2F92fVGJxb08K57HWd84zYf7WnuH6Kv8DCE0QABoMNjM3NDIzMTgzODA1IgyEcpsKKUBhbeu1RPwq3ANhe6pwuQVfFYlQXPRfYtRlhYXD3eFuSku5sjZ%2FlgsUtgl6X%2BRYZs%2BoDH3r%2BDiT9insGX8JJu7WYBZupBs%2BrQn6gfb4VcpOqZrLg6meRjZrTXkGowDDVmd%2B%2BtZ0lXgcy2eansUx2HyFO%2BllPHOSg9cCtbhOo87KeYmuXPUcPBqOgUUts8Ing8nL2L%2Bpfik%2BQucpcs4lzzIh%2BK6l%2BdlZSOQNDO68ljLsfTbprF1t1mZJhlal52HASkPnmngZe5d0NypGzbFItnXkHERp0YB%2FglsEGoZihfwWNVsNn7wIrZK1c2558AJg1R31Li1ZpfrfT9VNW1QZEGG6remT%2Bnx49EkCojfLx88AdbZy%2F0niRemZqUuAuIeHiEfPXaN1aT5ZFO4q3t8RT0GkS9T0UIy6DW0spH2uXKbXNmVI%2BOOWaxXFVBCYyX1N4FcFNhI0IcIMN4rIBUJ%2FSO6ddfjOHEqEz7qD%2BMnsosijhxrlne0Lz%2FZOJSY7hb21V8uAzENBW95bEb26yFJnnQCY0747uLg%2F3YjBTF8ewdcKlz14vFuRJSRxBbq4JE%2Bo3TPknC8bY48E0uU8v2KUZ%2BKt8HWwyykJvCca7TgvdX%2BpL4UCcvgUBGlEFgJkp9tqmda8LjrsEzD62MO9BjqkAZZBqhIou540%2BIIWeY9lx%2FqdgQ0R6DcyJtNNmWxZwBkvQLT34uwHQYivw93XADpDT1r3eziK5G7HulQjQc9ATbTqK%2B9gKcy6uA%2BhXug1%2BimRm4Qm29A00mxk3MTuO0me6As7Xh1ufvySv7y4mxFdveVNoPHrZ7biFexRuM9Dd%2FpS6rByTV0oR0MKs2%2FzwMqSmOlp7nvtvv8E3XXYdHt2wgfn80aO&X-Amz-Signature=bccbee31d3f4055e995f0fec9bb28dbdd83b86b38ded582d37d09e895c779fdf&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662UVWBECK%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T202254Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECQaCXVzLXdlc3QtMiJIMEYCIQD3hUCxuqmL5bFq4u7W1LzvpJ2%2BNfscVNXCR9NbZ5Sn2QIhAK3vTmodsLKkrEcN%2F92fVGJxb08K57HWd84zYf7WnuH6Kv8DCE0QABoMNjM3NDIzMTgzODA1IgyEcpsKKUBhbeu1RPwq3ANhe6pwuQVfFYlQXPRfYtRlhYXD3eFuSku5sjZ%2FlgsUtgl6X%2BRYZs%2BoDH3r%2BDiT9insGX8JJu7WYBZupBs%2BrQn6gfb4VcpOqZrLg6meRjZrTXkGowDDVmd%2B%2BtZ0lXgcy2eansUx2HyFO%2BllPHOSg9cCtbhOo87KeYmuXPUcPBqOgUUts8Ing8nL2L%2Bpfik%2BQucpcs4lzzIh%2BK6l%2BdlZSOQNDO68ljLsfTbprF1t1mZJhlal52HASkPnmngZe5d0NypGzbFItnXkHERp0YB%2FglsEGoZihfwWNVsNn7wIrZK1c2558AJg1R31Li1ZpfrfT9VNW1QZEGG6remT%2Bnx49EkCojfLx88AdbZy%2F0niRemZqUuAuIeHiEfPXaN1aT5ZFO4q3t8RT0GkS9T0UIy6DW0spH2uXKbXNmVI%2BOOWaxXFVBCYyX1N4FcFNhI0IcIMN4rIBUJ%2FSO6ddfjOHEqEz7qD%2BMnsosijhxrlne0Lz%2FZOJSY7hb21V8uAzENBW95bEb26yFJnnQCY0747uLg%2F3YjBTF8ewdcKlz14vFuRJSRxBbq4JE%2Bo3TPknC8bY48E0uU8v2KUZ%2BKt8HWwyykJvCca7TgvdX%2BpL4UCcvgUBGlEFgJkp9tqmda8LjrsEzD62MO9BjqkAZZBqhIou540%2BIIWeY9lx%2FqdgQ0R6DcyJtNNmWxZwBkvQLT34uwHQYivw93XADpDT1r3eziK5G7HulQjQc9ATbTqK%2B9gKcy6uA%2BhXug1%2BimRm4Qm29A00mxk3MTuO0me6As7Xh1ufvySv7y4mxFdveVNoPHrZ7biFexRuM9Dd%2FpS6rByTV0oR0MKs2%2FzwMqSmOlp7nvtvv8E3XXYdHt2wgfn80aO&X-Amz-Signature=a6f99f90a2efe5fe73df6e083ddcae0223bcd52df979e7e0ad606a428c2e2e2d&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662UVWBECK%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T202254Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECQaCXVzLXdlc3QtMiJIMEYCIQD3hUCxuqmL5bFq4u7W1LzvpJ2%2BNfscVNXCR9NbZ5Sn2QIhAK3vTmodsLKkrEcN%2F92fVGJxb08K57HWd84zYf7WnuH6Kv8DCE0QABoMNjM3NDIzMTgzODA1IgyEcpsKKUBhbeu1RPwq3ANhe6pwuQVfFYlQXPRfYtRlhYXD3eFuSku5sjZ%2FlgsUtgl6X%2BRYZs%2BoDH3r%2BDiT9insGX8JJu7WYBZupBs%2BrQn6gfb4VcpOqZrLg6meRjZrTXkGowDDVmd%2B%2BtZ0lXgcy2eansUx2HyFO%2BllPHOSg9cCtbhOo87KeYmuXPUcPBqOgUUts8Ing8nL2L%2Bpfik%2BQucpcs4lzzIh%2BK6l%2BdlZSOQNDO68ljLsfTbprF1t1mZJhlal52HASkPnmngZe5d0NypGzbFItnXkHERp0YB%2FglsEGoZihfwWNVsNn7wIrZK1c2558AJg1R31Li1ZpfrfT9VNW1QZEGG6remT%2Bnx49EkCojfLx88AdbZy%2F0niRemZqUuAuIeHiEfPXaN1aT5ZFO4q3t8RT0GkS9T0UIy6DW0spH2uXKbXNmVI%2BOOWaxXFVBCYyX1N4FcFNhI0IcIMN4rIBUJ%2FSO6ddfjOHEqEz7qD%2BMnsosijhxrlne0Lz%2FZOJSY7hb21V8uAzENBW95bEb26yFJnnQCY0747uLg%2F3YjBTF8ewdcKlz14vFuRJSRxBbq4JE%2Bo3TPknC8bY48E0uU8v2KUZ%2BKt8HWwyykJvCca7TgvdX%2BpL4UCcvgUBGlEFgJkp9tqmda8LjrsEzD62MO9BjqkAZZBqhIou540%2BIIWeY9lx%2FqdgQ0R6DcyJtNNmWxZwBkvQLT34uwHQYivw93XADpDT1r3eziK5G7HulQjQc9ATbTqK%2B9gKcy6uA%2BhXug1%2BimRm4Qm29A00mxk3MTuO0me6As7Xh1ufvySv7y4mxFdveVNoPHrZ7biFexRuM9Dd%2FpS6rByTV0oR0MKs2%2FzwMqSmOlp7nvtvv8E3XXYdHt2wgfn80aO&X-Amz-Signature=4a919a5b829569510b7b066256c0fc9749a233adf485ba5a407dcf047134f199&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UL4BASDZ%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T202255Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECQaCXVzLXdlc3QtMiJGMEQCIFfmzZK8UBVP95e3PeZidyFE7GaNEhtbN1IrHaVwXnTmAiANtqGUS9GQpCBheTaSx1p%2BVFep9ybK8TX71%2BFLlfFPdir%2FAwhNEAAaDDYzNzQyMzE4MzgwNSIMJQrWgd1s%2BHYTjNtCKtwDld7FYG%2FOuB6Ch7UA9Ju1ujnBeQVVppAD%2BPFrdjuIibCa%2BZ0x9jf6gqMJfKNB8gDFkT%2BqG9C%2BJtSv94yGQcAULKqENherw1bvLdChOfhrNwsBi1nl0fqsIxlCwRi9cA%2BnLa4cvF0CntOw%2By5BbbGdoiREEJkRs%2BFqfn37q0kqugzSGDhpgYHY4kGBGeOc0QVej2irc0%2FcdDP5pBkGURzNEIJtKF4KeBD8rvuB7n%2FtmArENtLNb4jwC%2Bh6IGiq7pNacuvddjhlbwor1nxq7%2FIPvOHTANZoOVPL6AXGXqiAvTNKD66%2BwXqEXtf7%2FEMD0WXgKykDbNsu5Y0cNGjj2kCFSGT0ujJ7S1mvnQv%2FL%2F8jbnftMyxtsgGfK3A%2FjIMr%2B5JEy9lyJxSJTdI23me%2BRDfgN1MhP6hjIGPdAtbdwbZNeUSPV7S8kAZY%2BZTAUFeaN61LfneLwJ2zQ26cmysJXvPzRn%2FkBMzbSfxjiIoo7mbz%2Bw44dvK2lSu9YajYPvjcZz3HBtHklOzbeIlfoe0vNHxm7tS6oDxO21RfB8pVmWTLpiqnHhfe8liaX2CE6IepD14%2BW5KwfijUNOdWcuHku4i8tWn9CD3NyrYVJaJ6tfc4zKFkrpsf%2BbZhZOEp0DMwhNnDvQY6pgFzmr%2F9CEGINKeyYl0YadKkp8ZcE67i112ztQ%2Bp%2FWpsTOTc0cdjVmEjJEcFCAjgbzhpG%2FxLZuTwxIL0%2FL4XBU1JLqcWAEszbxFfgsbB2chVL1vB%2BjuPfg0af69RtrzR2ZGAg9Rc3qq%2B%2BRotdjT8kh%2BU4tLF05PFRFAVa%2FPuudIbF2BTnIyCoSZZFrH36a%2BJEetAnZjFYkYNtQZRbDKjJGeDHGtMtX7c&X-Amz-Signature=1406dc0977b0843a125d7fb3b946a769ad20c51e81d164700923c2cc94526bf3&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WM37KWFM%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T202256Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECQaCXVzLXdlc3QtMiJGMEQCIChloG111rhbGAvjL%2FNk69iFYr%2F02IVPzqVJVPH6%2BeAtAiBWRhCH682Lxs92JlabGLHKqQQ9zJ9jh1PW8qxo7lhq3Sr%2FAwhNEAAaDDYzNzQyMzE4MzgwNSIMtD6rgU686Zy3mSzkKtwDv87rWC7bJcohy%2BvB77K4cyMPiORWK80%2Fs%2BLG%2BFLx17UjmwdSOIenSOxhrSGot9mGAuQHohzoiruvlGZc%2B5676tIHejGzbBlk0yEttA51Uz40oz5YpVJ%2FHFcQ%2F3q6Y1q9360T5kKumCwC6pmZr99UgePgsnpZQFDtLGfh5z3dJ%2FTesEjPBYnbSh2ISyQwvqgw0pRF9sDNO0xZjJIWg1HsVTRIuGtC7C6C2zglfe9rPBZDN8XFV9xsoGOe9Mt53IUDI628ta1FE0PR%2BXwwYSYla3zp%2BLmYao4F6jIWKvoyiRyICWMqxEDaAlXJG8i6oSF%2B4GWsv2sddO26eOhcdJX8Bx7Yc424Iq9O6221rHKWNL7%2BehIGV7yztODSXePFTKEFYDAJkFRZnw2ygMChwVEehE2vTQhmGUxs10hvfLwjX2dL1g7Zt8U%2F2EOhgwUhmdOruzZCLuCJYSx2%2F5xGVdc1mkQzGYedF3KD%2Bm6pJ%2FmJDwbeJB6BUVwsEwHW0aw6V7Ro6QmtshvEH1qRTY1H0jqzBHUve5z9pcNnGyKQVgbHVGc4Oxe2LbjuAFL6RQtje58fUsidiocIf4NSHhAAcYSK56vwG%2Bk%2F03INbT3dibacoNDQ4ya27ZJoddeOe7Uw8NjDvQY6pgHkqepVvuuMtHH8oAJ12qwhbj%2BhhJhSgneHnFoMkka0ZijXuxpLsrGPrxXjLRSYlsZqga0l1cX9aMKA%2FA4ryWMj81aTD2wovilgCfmfyRP372bp8PItPAJ9zZOQS14%2BLklC6eCP4Yo4jhhnEY7kf8xbjCOmMEBk7%2B%2FiMGCUkq2e5pHUG6u8XcAG7z0pEPIRu%2BSlHIxqy3matLmwZNbA0kvEzII8W3Jq&X-Amz-Signature=9428a2be479176553ecdfe517c71db080c9974e27fec27ca0624efc550e141f9&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662UVWBECK%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T202254Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECQaCXVzLXdlc3QtMiJIMEYCIQD3hUCxuqmL5bFq4u7W1LzvpJ2%2BNfscVNXCR9NbZ5Sn2QIhAK3vTmodsLKkrEcN%2F92fVGJxb08K57HWd84zYf7WnuH6Kv8DCE0QABoMNjM3NDIzMTgzODA1IgyEcpsKKUBhbeu1RPwq3ANhe6pwuQVfFYlQXPRfYtRlhYXD3eFuSku5sjZ%2FlgsUtgl6X%2BRYZs%2BoDH3r%2BDiT9insGX8JJu7WYBZupBs%2BrQn6gfb4VcpOqZrLg6meRjZrTXkGowDDVmd%2B%2BtZ0lXgcy2eansUx2HyFO%2BllPHOSg9cCtbhOo87KeYmuXPUcPBqOgUUts8Ing8nL2L%2Bpfik%2BQucpcs4lzzIh%2BK6l%2BdlZSOQNDO68ljLsfTbprF1t1mZJhlal52HASkPnmngZe5d0NypGzbFItnXkHERp0YB%2FglsEGoZihfwWNVsNn7wIrZK1c2558AJg1R31Li1ZpfrfT9VNW1QZEGG6remT%2Bnx49EkCojfLx88AdbZy%2F0niRemZqUuAuIeHiEfPXaN1aT5ZFO4q3t8RT0GkS9T0UIy6DW0spH2uXKbXNmVI%2BOOWaxXFVBCYyX1N4FcFNhI0IcIMN4rIBUJ%2FSO6ddfjOHEqEz7qD%2BMnsosijhxrlne0Lz%2FZOJSY7hb21V8uAzENBW95bEb26yFJnnQCY0747uLg%2F3YjBTF8ewdcKlz14vFuRJSRxBbq4JE%2Bo3TPknC8bY48E0uU8v2KUZ%2BKt8HWwyykJvCca7TgvdX%2BpL4UCcvgUBGlEFgJkp9tqmda8LjrsEzD62MO9BjqkAZZBqhIou540%2BIIWeY9lx%2FqdgQ0R6DcyJtNNmWxZwBkvQLT34uwHQYivw93XADpDT1r3eziK5G7HulQjQc9ATbTqK%2B9gKcy6uA%2BhXug1%2BimRm4Qm29A00mxk3MTuO0me6As7Xh1ufvySv7y4mxFdveVNoPHrZ7biFexRuM9Dd%2FpS6rByTV0oR0MKs2%2FzwMqSmOlp7nvtvv8E3XXYdHt2wgfn80aO&X-Amz-Signature=a307701d55a0ab67116fbdab9f1c9ac88d7c46f614ed159faf79fec557cd4f6f&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662UVWBECK%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T202254Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECQaCXVzLXdlc3QtMiJIMEYCIQD3hUCxuqmL5bFq4u7W1LzvpJ2%2BNfscVNXCR9NbZ5Sn2QIhAK3vTmodsLKkrEcN%2F92fVGJxb08K57HWd84zYf7WnuH6Kv8DCE0QABoMNjM3NDIzMTgzODA1IgyEcpsKKUBhbeu1RPwq3ANhe6pwuQVfFYlQXPRfYtRlhYXD3eFuSku5sjZ%2FlgsUtgl6X%2BRYZs%2BoDH3r%2BDiT9insGX8JJu7WYBZupBs%2BrQn6gfb4VcpOqZrLg6meRjZrTXkGowDDVmd%2B%2BtZ0lXgcy2eansUx2HyFO%2BllPHOSg9cCtbhOo87KeYmuXPUcPBqOgUUts8Ing8nL2L%2Bpfik%2BQucpcs4lzzIh%2BK6l%2BdlZSOQNDO68ljLsfTbprF1t1mZJhlal52HASkPnmngZe5d0NypGzbFItnXkHERp0YB%2FglsEGoZihfwWNVsNn7wIrZK1c2558AJg1R31Li1ZpfrfT9VNW1QZEGG6remT%2Bnx49EkCojfLx88AdbZy%2F0niRemZqUuAuIeHiEfPXaN1aT5ZFO4q3t8RT0GkS9T0UIy6DW0spH2uXKbXNmVI%2BOOWaxXFVBCYyX1N4FcFNhI0IcIMN4rIBUJ%2FSO6ddfjOHEqEz7qD%2BMnsosijhxrlne0Lz%2FZOJSY7hb21V8uAzENBW95bEb26yFJnnQCY0747uLg%2F3YjBTF8ewdcKlz14vFuRJSRxBbq4JE%2Bo3TPknC8bY48E0uU8v2KUZ%2BKt8HWwyykJvCca7TgvdX%2BpL4UCcvgUBGlEFgJkp9tqmda8LjrsEzD62MO9BjqkAZZBqhIou540%2BIIWeY9lx%2FqdgQ0R6DcyJtNNmWxZwBkvQLT34uwHQYivw93XADpDT1r3eziK5G7HulQjQc9ATbTqK%2B9gKcy6uA%2BhXug1%2BimRm4Qm29A00mxk3MTuO0me6As7Xh1ufvySv7y4mxFdveVNoPHrZ7biFexRuM9Dd%2FpS6rByTV0oR0MKs2%2FzwMqSmOlp7nvtvv8E3XXYdHt2wgfn80aO&X-Amz-Signature=cac548453762a227604a73aeedd7d6a27ef6710816f5299ca7f473dff3af9a1b&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662UVWBECK%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T202254Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECQaCXVzLXdlc3QtMiJIMEYCIQD3hUCxuqmL5bFq4u7W1LzvpJ2%2BNfscVNXCR9NbZ5Sn2QIhAK3vTmodsLKkrEcN%2F92fVGJxb08K57HWd84zYf7WnuH6Kv8DCE0QABoMNjM3NDIzMTgzODA1IgyEcpsKKUBhbeu1RPwq3ANhe6pwuQVfFYlQXPRfYtRlhYXD3eFuSku5sjZ%2FlgsUtgl6X%2BRYZs%2BoDH3r%2BDiT9insGX8JJu7WYBZupBs%2BrQn6gfb4VcpOqZrLg6meRjZrTXkGowDDVmd%2B%2BtZ0lXgcy2eansUx2HyFO%2BllPHOSg9cCtbhOo87KeYmuXPUcPBqOgUUts8Ing8nL2L%2Bpfik%2BQucpcs4lzzIh%2BK6l%2BdlZSOQNDO68ljLsfTbprF1t1mZJhlal52HASkPnmngZe5d0NypGzbFItnXkHERp0YB%2FglsEGoZihfwWNVsNn7wIrZK1c2558AJg1R31Li1ZpfrfT9VNW1QZEGG6remT%2Bnx49EkCojfLx88AdbZy%2F0niRemZqUuAuIeHiEfPXaN1aT5ZFO4q3t8RT0GkS9T0UIy6DW0spH2uXKbXNmVI%2BOOWaxXFVBCYyX1N4FcFNhI0IcIMN4rIBUJ%2FSO6ddfjOHEqEz7qD%2BMnsosijhxrlne0Lz%2FZOJSY7hb21V8uAzENBW95bEb26yFJnnQCY0747uLg%2F3YjBTF8ewdcKlz14vFuRJSRxBbq4JE%2Bo3TPknC8bY48E0uU8v2KUZ%2BKt8HWwyykJvCca7TgvdX%2BpL4UCcvgUBGlEFgJkp9tqmda8LjrsEzD62MO9BjqkAZZBqhIou540%2BIIWeY9lx%2FqdgQ0R6DcyJtNNmWxZwBkvQLT34uwHQYivw93XADpDT1r3eziK5G7HulQjQc9ATbTqK%2B9gKcy6uA%2BhXug1%2BimRm4Qm29A00mxk3MTuO0me6As7Xh1ufvySv7y4mxFdveVNoPHrZ7biFexRuM9Dd%2FpS6rByTV0oR0MKs2%2FzwMqSmOlp7nvtvv8E3XXYdHt2wgfn80aO&X-Amz-Signature=85ea491c4d68fa38b9730efdf74add20e670c9a32c7035b68ed35ce4d37beefe&X-Amz-SignedHeaders=host&x-id=GetObject)


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

