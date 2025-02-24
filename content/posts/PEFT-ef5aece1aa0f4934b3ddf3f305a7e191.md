---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4663OJU4YEF%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250224T152752Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEPj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDBFND%2FtEBYaA0M6\
  VgVlH%2FiD24YSV8FChOMhAvE7JomWgIhAPxtzSLa%2BjlFO2Sq8NkQHlKw6sUlrq4Sqh1lXISzTH\
  D5Kv8DCDAQABoMNjM3NDIzMTgzODA1IgyL0YLzXzmnimbdoP4q3AOVkTZrWufeVPCeLMJBxI%2Fli\
  x1G1kC2vZeBklqucDKJLtbVNGdL17DXGlM14dzpAZ4ce3NKY2JFhsU%2B5kmefFB2qsyQRm64UmKd\
  T8zdCRRwIRqN3Wu4adPqemrZwTARSkSMlmSKghYnIwL%2F6Tsoy%2BTqThfTkIolx1DX4rtNvdFrO\
  %2BkRH%2FPfD44VImHqB4I2nOPUcwni40I2dUJKew2It9IQ20%2FUppvubLwSGsit6vIA9rVeZk%2\
  Bn%2B2Lk281T83AxuX2Gevjxbv%2B871fnZGZ2bDbpRTznRhCzYq0sLscSXoelN5n5nFc01%2BQYn\
  hOyKaAxNSLdYygqHtFX2ypFOoxacQeAm88Zj3Nb1b3DzIWyAIzn3dUF8xl4G9pp0raU3U%2BeXvm3\
  ja1cBBkxq5xDydNX5xlHnayQHg9YiKd03i9dmB7c0REh2qLwcXAnZ14T6Z%2B6oWPhQZfNY%2FsPK\
  5qoPwnhBGw2UKEgyVKc4W3KTVEmeOSuVvZscw5NSw%2Fk0s3WYn3pVjJmgiKnuYWP%2FrDOZTscXE\
  GobJIpoTPoFvgL6jxnirz0csw2uIWiflhDaoB%2BCgQM8jk%2F1xQssO9Mao3hXCTjT8FmZiWHUVv\
  iG8AM%2Feosz8vHD2KmMmbaVW%2FTCCrOqzDEnPK9BjqkAUJKA3GSgdO7GIvlljytjrT3QrF24bom\
  VhBHa8rWRLtmvVlf0N9%2BjfqEesj1srBYtJzhKBgJ9JFqeCfPSKlEVtAWvI4KLn3NaP77NnnRrSM\
  EvllJEP3lu7ZOEpaOUxFU2AVydJ9G%2BXneHIzhHF84H9MXaPIrWuuLyzVPf0NLchPrUCF2ZC0Q8x\
  CKclf%2BKspSXjVfUAhuHG%2BV5aCYCZf7j0UpVlfX&X-Amz-Signature=4cc396076d41426ac7\
  44478696fbd7a33d67057a6650476e56e02e4874f6588f&X-Amz-SignedHeaders=host&x-id=\
  GetObject"
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
        redential=ASIAZI2LB466WAOYGHWH%2F20250224%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250224T152606Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEPj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQ\
        CIA30wHt%2B5NpRaQJmpWXjI4Bwhn6Hi9PoMkid6y6%2Fk48%2FAiAontPdPjUJwnKk1dBU\
        2aqU7R0tb4iFvqoASIAfyTc93ir%2FAwgwEAAaDDYzNzQyMzE4MzgwNSIMY0wgfymjI%2Bc\
        ItP6nKtwDp%2BzVE6HtZmpDJNeWXHuYP6ZT%2FKdswCUJH4e4cHIDa%2BNp5AJq6Em%2BfH\
        zJtEUT781hVslWsZpDNVX0CbDhrRNuPSTvQxAc45EA1dMOUmt%2BFBT0x5HprIBAoe4pC%2\
        Fqx%2FZ4xCeIlY9U2%2F7G8Z5rr17%2FPI5xpmg6Fiw1hEhBYu6J77lYhTYndQNUpIQ%2Fn\
        JknORFMeoe4JZ8nQ2nMJ5X%2FlJ4ms3gyRNxYW3W%2Fo%2Bq9%2BlMXF8AuF78y%2FIaqI9\
        Hhsa3SBBUQsZvlPn9wQGM2B9FhAefro4%2FsQIwuRZ0%2F1FJAZ7Py71oyyR1NJp8lhZney\
        3Hgk7bj7PbRbHVeZLwntP5e5ohpRGhiq4B7k5ulWqXtbbH1f8eoydjxM96NGAA1XDiixMPI\
        zMwwWn%2FZXL16HqgPeYUo3JmLlzAuRGi8vLrTbyqZWiUcKrmgaJixSOIirBsbip%2Bxtxo\
        EgDo6IcH1ZPj6rMZQWdiKYcQT1Ik3YqtEsJn%2B%2FZ7XCNltfioH4Xtr0QG3WxR5zki5pJ\
        J461lnNAcBgxH5h3of8FGfQ76z4LdBiGFF752jeJ7ZUp2tvrl8KSwSHv7utqa97pbnIohXa\
        pT0Ey2ETxbqZXzft6lZcHxfaGUcSGMh7%2F9%2BzJmPoZR%2F%2B1ucwppzyvQY6pgF%2Bu\
        uYpliJ8z10s0ymj3bKej7LftaolIaohhhBLWcd3WCDE4pZy%2BJoY6HN6tslfsjv7GCWu2%\
        2BldWschIF4CB8b2292fKizibwoiwJvsBy9xZcWHiDXo%2FqqduSIKLyHX3nykBRb9FonYv\
        9DHzBbqRMVUa1QmEg9S%2F60KLtBOILyp8v%2FzlmjVhLi776opaJcn9aw2Y3ZE7v9UZFQ9\
        dD0KUNyEqQU6V3IO&X-Amz-Signature=ab4e84acab72bf04694b05a8e41a810dba50a8\
        cb76f574c927dac387921da160&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-24T16:26:06.222Z"
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
UPDATE_TIME: "2025-02-24T15:27:59.947Z"
EXPIRY_TIME: "2025-02-24T16:27:49.593Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XM5GWP7C%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T152750Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDpW0G2FqobuPannPhIztyGHpfRMZZMivhO8HrIZEPirAIhAPpWtCrsiVa9ygMKZPwYWPLa%2BVuNPGB0Wv%2FS%2BekuO6INKv8DCDAQABoMNjM3NDIzMTgzODA1IgwCRVynGGJW3HNpg5cq3AOUf2n8OlNi7AzvDHH9WnymzL1UQHIoNByvbH1VYNzCphJhRaODgZkb6rT6aVuQBaJRDgx8o8NIf%2FZ4uDCRHKiooxm8f%2F34VX9BEGVGaZANsda1jSonmK8h6FCs4vVmeiHiLJOjmrLaq4Vp11cHYnJmzpIR1ywC7RqyQzswNs04L0pTS66MOM6TXBLn8cXxb1B1J5f61C02evDtw8K0392ZgTI4usXbzKsRlMxJZZzERnmVd0hbm45d9cqUL5u%2B1HI6Uae26ljNb53Az1kIIM4rbuOMfaBN6jUEMWej8UBwh8oRT79hsdrlrJqT0SWom2sv2uwhZL0PjyprslFTsoNCJLqA6zYnjTtBlv5jc0GD5IofZIDjVI%2F9aOm8gfsjOTegxHP30DE2jCS%2FFZkmU7H36rH8RrwclKHULPYga2o5pwVWbuc2Pp3Cay9%2FRIhMMn6g6VyB6hxk%2Ftrkzv8AVxlhGGkE7qxRLRmYOEkyQV0LuCBRB00nHBiPCzBJjV%2F3PgnjRXpI15ONdV9v5Of3UeER0fbqisIGx5IlqIGfSJ8x0wY%2B73ldJ9jpDzsWKuU3d8WbNw%2BmTtiMnLW5TGeJpt%2B%2FipDCImD%2BF48tV%2Fe%2Bl4K9InpJk%2B0KmIFVKbS%2BYjC7nPK9BjqkAXjcTofzvvCMpGJQt1nAYwN6a4kh3HN6Xmz41pvUQYXJYpw2wMbdkpAEsANlqzxeP8DT3OO2uXytYcoOWJEsIm6lllxXXqjiH%2BG1O5%2Bz2tq6fj79uFdKQUypgw8868EeyawSeIqzjswwyhjeDcSPt3vDJBYEzb0htA7ebGRoHRNV28usP9kV4CY9vdVMMVRK7W1JkkGN3i2%2ByDydRdw%2FB7FgHFEx&X-Amz-Signature=5920bda71728bde7ba6d6120c67e40e4208535efbdcb4c9b3a841a95d94cb7ce&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XM5GWP7C%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T152750Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDpW0G2FqobuPannPhIztyGHpfRMZZMivhO8HrIZEPirAIhAPpWtCrsiVa9ygMKZPwYWPLa%2BVuNPGB0Wv%2FS%2BekuO6INKv8DCDAQABoMNjM3NDIzMTgzODA1IgwCRVynGGJW3HNpg5cq3AOUf2n8OlNi7AzvDHH9WnymzL1UQHIoNByvbH1VYNzCphJhRaODgZkb6rT6aVuQBaJRDgx8o8NIf%2FZ4uDCRHKiooxm8f%2F34VX9BEGVGaZANsda1jSonmK8h6FCs4vVmeiHiLJOjmrLaq4Vp11cHYnJmzpIR1ywC7RqyQzswNs04L0pTS66MOM6TXBLn8cXxb1B1J5f61C02evDtw8K0392ZgTI4usXbzKsRlMxJZZzERnmVd0hbm45d9cqUL5u%2B1HI6Uae26ljNb53Az1kIIM4rbuOMfaBN6jUEMWej8UBwh8oRT79hsdrlrJqT0SWom2sv2uwhZL0PjyprslFTsoNCJLqA6zYnjTtBlv5jc0GD5IofZIDjVI%2F9aOm8gfsjOTegxHP30DE2jCS%2FFZkmU7H36rH8RrwclKHULPYga2o5pwVWbuc2Pp3Cay9%2FRIhMMn6g6VyB6hxk%2Ftrkzv8AVxlhGGkE7qxRLRmYOEkyQV0LuCBRB00nHBiPCzBJjV%2F3PgnjRXpI15ONdV9v5Of3UeER0fbqisIGx5IlqIGfSJ8x0wY%2B73ldJ9jpDzsWKuU3d8WbNw%2BmTtiMnLW5TGeJpt%2B%2FipDCImD%2BF48tV%2Fe%2Bl4K9InpJk%2B0KmIFVKbS%2BYjC7nPK9BjqkAXjcTofzvvCMpGJQt1nAYwN6a4kh3HN6Xmz41pvUQYXJYpw2wMbdkpAEsANlqzxeP8DT3OO2uXytYcoOWJEsIm6lllxXXqjiH%2BG1O5%2Bz2tq6fj79uFdKQUypgw8868EeyawSeIqzjswwyhjeDcSPt3vDJBYEzb0htA7ebGRoHRNV28usP9kV4CY9vdVMMVRK7W1JkkGN3i2%2ByDydRdw%2FB7FgHFEx&X-Amz-Signature=9604cd0cafbbf621315ad4c7d23e4d542f1297407b86a4ff0548f33025d14b8f&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XM5GWP7C%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T152750Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDpW0G2FqobuPannPhIztyGHpfRMZZMivhO8HrIZEPirAIhAPpWtCrsiVa9ygMKZPwYWPLa%2BVuNPGB0Wv%2FS%2BekuO6INKv8DCDAQABoMNjM3NDIzMTgzODA1IgwCRVynGGJW3HNpg5cq3AOUf2n8OlNi7AzvDHH9WnymzL1UQHIoNByvbH1VYNzCphJhRaODgZkb6rT6aVuQBaJRDgx8o8NIf%2FZ4uDCRHKiooxm8f%2F34VX9BEGVGaZANsda1jSonmK8h6FCs4vVmeiHiLJOjmrLaq4Vp11cHYnJmzpIR1ywC7RqyQzswNs04L0pTS66MOM6TXBLn8cXxb1B1J5f61C02evDtw8K0392ZgTI4usXbzKsRlMxJZZzERnmVd0hbm45d9cqUL5u%2B1HI6Uae26ljNb53Az1kIIM4rbuOMfaBN6jUEMWej8UBwh8oRT79hsdrlrJqT0SWom2sv2uwhZL0PjyprslFTsoNCJLqA6zYnjTtBlv5jc0GD5IofZIDjVI%2F9aOm8gfsjOTegxHP30DE2jCS%2FFZkmU7H36rH8RrwclKHULPYga2o5pwVWbuc2Pp3Cay9%2FRIhMMn6g6VyB6hxk%2Ftrkzv8AVxlhGGkE7qxRLRmYOEkyQV0LuCBRB00nHBiPCzBJjV%2F3PgnjRXpI15ONdV9v5Of3UeER0fbqisIGx5IlqIGfSJ8x0wY%2B73ldJ9jpDzsWKuU3d8WbNw%2BmTtiMnLW5TGeJpt%2B%2FipDCImD%2BF48tV%2Fe%2Bl4K9InpJk%2B0KmIFVKbS%2BYjC7nPK9BjqkAXjcTofzvvCMpGJQt1nAYwN6a4kh3HN6Xmz41pvUQYXJYpw2wMbdkpAEsANlqzxeP8DT3OO2uXytYcoOWJEsIm6lllxXXqjiH%2BG1O5%2Bz2tq6fj79uFdKQUypgw8868EeyawSeIqzjswwyhjeDcSPt3vDJBYEzb0htA7ebGRoHRNV28usP9kV4CY9vdVMMVRK7W1JkkGN3i2%2ByDydRdw%2FB7FgHFEx&X-Amz-Signature=fdeee6c89efe4c0036b7ac6f45450326d4e4dc73de6a99a93395e4d80eac6a3c&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XM5GWP7C%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T152750Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDpW0G2FqobuPannPhIztyGHpfRMZZMivhO8HrIZEPirAIhAPpWtCrsiVa9ygMKZPwYWPLa%2BVuNPGB0Wv%2FS%2BekuO6INKv8DCDAQABoMNjM3NDIzMTgzODA1IgwCRVynGGJW3HNpg5cq3AOUf2n8OlNi7AzvDHH9WnymzL1UQHIoNByvbH1VYNzCphJhRaODgZkb6rT6aVuQBaJRDgx8o8NIf%2FZ4uDCRHKiooxm8f%2F34VX9BEGVGaZANsda1jSonmK8h6FCs4vVmeiHiLJOjmrLaq4Vp11cHYnJmzpIR1ywC7RqyQzswNs04L0pTS66MOM6TXBLn8cXxb1B1J5f61C02evDtw8K0392ZgTI4usXbzKsRlMxJZZzERnmVd0hbm45d9cqUL5u%2B1HI6Uae26ljNb53Az1kIIM4rbuOMfaBN6jUEMWej8UBwh8oRT79hsdrlrJqT0SWom2sv2uwhZL0PjyprslFTsoNCJLqA6zYnjTtBlv5jc0GD5IofZIDjVI%2F9aOm8gfsjOTegxHP30DE2jCS%2FFZkmU7H36rH8RrwclKHULPYga2o5pwVWbuc2Pp3Cay9%2FRIhMMn6g6VyB6hxk%2Ftrkzv8AVxlhGGkE7qxRLRmYOEkyQV0LuCBRB00nHBiPCzBJjV%2F3PgnjRXpI15ONdV9v5Of3UeER0fbqisIGx5IlqIGfSJ8x0wY%2B73ldJ9jpDzsWKuU3d8WbNw%2BmTtiMnLW5TGeJpt%2B%2FipDCImD%2BF48tV%2Fe%2Bl4K9InpJk%2B0KmIFVKbS%2BYjC7nPK9BjqkAXjcTofzvvCMpGJQt1nAYwN6a4kh3HN6Xmz41pvUQYXJYpw2wMbdkpAEsANlqzxeP8DT3OO2uXytYcoOWJEsIm6lllxXXqjiH%2BG1O5%2Bz2tq6fj79uFdKQUypgw8868EeyawSeIqzjswwyhjeDcSPt3vDJBYEzb0htA7ebGRoHRNV28usP9kV4CY9vdVMMVRK7W1JkkGN3i2%2ByDydRdw%2FB7FgHFEx&X-Amz-Signature=71e0b4ffe0987522a97a43242b3f3d5f1254985fb766f74b9e2357f59387b88a&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XM5GWP7C%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T152750Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDpW0G2FqobuPannPhIztyGHpfRMZZMivhO8HrIZEPirAIhAPpWtCrsiVa9ygMKZPwYWPLa%2BVuNPGB0Wv%2FS%2BekuO6INKv8DCDAQABoMNjM3NDIzMTgzODA1IgwCRVynGGJW3HNpg5cq3AOUf2n8OlNi7AzvDHH9WnymzL1UQHIoNByvbH1VYNzCphJhRaODgZkb6rT6aVuQBaJRDgx8o8NIf%2FZ4uDCRHKiooxm8f%2F34VX9BEGVGaZANsda1jSonmK8h6FCs4vVmeiHiLJOjmrLaq4Vp11cHYnJmzpIR1ywC7RqyQzswNs04L0pTS66MOM6TXBLn8cXxb1B1J5f61C02evDtw8K0392ZgTI4usXbzKsRlMxJZZzERnmVd0hbm45d9cqUL5u%2B1HI6Uae26ljNb53Az1kIIM4rbuOMfaBN6jUEMWej8UBwh8oRT79hsdrlrJqT0SWom2sv2uwhZL0PjyprslFTsoNCJLqA6zYnjTtBlv5jc0GD5IofZIDjVI%2F9aOm8gfsjOTegxHP30DE2jCS%2FFZkmU7H36rH8RrwclKHULPYga2o5pwVWbuc2Pp3Cay9%2FRIhMMn6g6VyB6hxk%2Ftrkzv8AVxlhGGkE7qxRLRmYOEkyQV0LuCBRB00nHBiPCzBJjV%2F3PgnjRXpI15ONdV9v5Of3UeER0fbqisIGx5IlqIGfSJ8x0wY%2B73ldJ9jpDzsWKuU3d8WbNw%2BmTtiMnLW5TGeJpt%2B%2FipDCImD%2BF48tV%2Fe%2Bl4K9InpJk%2B0KmIFVKbS%2BYjC7nPK9BjqkAXjcTofzvvCMpGJQt1nAYwN6a4kh3HN6Xmz41pvUQYXJYpw2wMbdkpAEsANlqzxeP8DT3OO2uXytYcoOWJEsIm6lllxXXqjiH%2BG1O5%2Bz2tq6fj79uFdKQUypgw8868EeyawSeIqzjswwyhjeDcSPt3vDJBYEzb0htA7ebGRoHRNV28usP9kV4CY9vdVMMVRK7W1JkkGN3i2%2ByDydRdw%2FB7FgHFEx&X-Amz-Signature=b31f3f80f86975848823c2447cc83c345d0df74eeb8b6b422f45c857d4617d3d&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RW233ROY%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T152750Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICVDcR7ZrTW%2B7PlUp487kGHTA77aa%2Bs6C%2BLTjzkZho99AiBCe03FQoBYut1VyOZfQGeiVHEbAN7JyvDc7JmGeD%2BeKir%2FAwgwEAAaDDYzNzQyMzE4MzgwNSIMpSlhxQHyEVsP2MntKtwDikFJzZnxfj%2FFRVBnu3MGNn8kOVE6E7GThn5N1Ao4FjdkXLI%2B51jN1wlZF4Gq4G5nzKNWVFZKURpTE%2FHia5KQFvuA9netZDpznINvVNcRud1bUZX1KoaOwzUyQSRSwozFiGgzFmbo3%2FcutsshcfMIruBfWW%2FmLTWVa7HNRNGIsQUpoxVW6j2lu6Z5xh0sI4HVDTAO5%2BoWjPkrg%2BaHEMDoGt5zJCbUUaGmlhTk3n9rVFHH%2F2LDnw9uBqUabbYXXS6yJzXeaiO7FICAsWBmxpK5dc8POzu6H2oZZpgwSglfgTYH70cBTWVRSGaDvltg8TWJOD3zo67ZTow4yGwAo4MvSidAsqWrtOfTJevnvIwhZIlCG%2B3kMDuQUdKFoHCAcxF71T1Fsk4czLnc%2FEIyWNb8VpPTbSk8v8D5zI7uhnNdpxwMmJbmJQ0w09tQ8iquBtorZojTwyZtznXtrDGbOrmX2Sb7290CrdD7cyrEdRW1EV7Vpvkp0VjKHK40%2Bhv%2FlY8I17uQPGmvN7XAPjX5DpeZZLvBVe6CxFZiA5DLkLVFhxlioxV4UbGgXceg%2F6SH3GjP2gxte8Cl28bM7K8LBySPhMPTaUm41j28hQ6VKhog5ANF0gpWUri0macviCwwwZzyvQY6pgFi6sioGLa376dN0yoGZrN%2F2MOQknrlUhvGCCgnPZnup9C0%2BG4Ug0veK9ODDlzarfwp30b769yfOlr%2BrrZ2zxlt7wqubr0rnWLzI802O2QfMmj3216lR03h8bIG%2FJxtegA5aMuqWIGKXc1lQMy9p6%2B9BYaKKdbC3mkznM340RUmXO%2FgAomqidaDqrHbvUi0PhW8x%2BO5T7YahUzYPOwN6talRTP6rFfe&X-Amz-Signature=c087c539601fc287039406f0a2f3a0509c4ec9d4bb5c5b90828da7d56d6a3e67&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SK4Q2OTI%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T152751Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIHPm5SL8wBR%2F2kMXZKzTRv%2FKSzlb%2Fdq9V63AdbEwhJB4AiA8JKsBpUyDCOn5Ai%2FMwc1QzYjL9uDwU9fI78tmce692ir%2FAwgwEAAaDDYzNzQyMzE4MzgwNSIMnF6hfLbfpLb3vg85KtwDUb3JRWNYo8LW97%2Be%2FHWuitYjcqRKBRpzX5%2B3Xz%2FuLctzC9Gdo3UUALaJyZndm2UoDnnOlolJDD3O00CBPOh1B7TmowkeEc7Vt7X41QExcAga9OrrKIFaoQsMg0Mmlqo2MKiyjoRJqkYik79KH9ce43fqv%2FBFT%2BZ2MnPi7RfiJTnYimvT6DJilxahD8gzo%2FMdDYVwDQ2J959gVh%2FOumZ7vWtNnSDAL6DkHIfhOcmIl4%2FbVd1kVX8T9ThojeKUqfohTkMlzmNuvrLdNE91lTjZOvBnSAgBc%2Fo22xNOHvb5%2BPTvpWIvCLCMFRjUH7l2fJsqYsjdTQFqL9xIlA0CPAFFDPaIW%2FIcXycBVGHlEzetBGGYBEyAczVuryiqq8K4zXFTJyn3tvBUkHIKhKj9EjxjgtgA9aJNek30rbteEeR7gM5kY%2BYkJ4YNtdMf2k2IDokytOCYJp1nxf2V%2FEST0V%2F5UA5%2FB6S2DYsjNbcS3VLdSC%2Fetf%2FpWAltStscuWdFXWh32ud%2BhgwpX81znVyQF9xyWsi1OJlfIImBJQiibzrCVOCCxbIox%2Fn7mKfX%2B2JL8NoUNQi41vNXjbRx9DoLTnV0b%2FtV7MIWjeqermmJr0%2F3wq%2BB9a9%2BCR6q5lTMloIwg53yvQY6pgHeW99q67uWCL0AI6H%2B5EmC4BmTejIJtwl3mbG%2FDZIUsREqmxAZqIc0hxH2kgtpl8qCk4WcC409ehn8DnTtio56HbLdA%2Bi0XqBZJiau4Ie%2BnTf4u6Ib7CNNqT9dut0FHxknQQud1hhpATvMzIRYrCQZAC8HRbPXsMR5Ur6Q%2B%2BiVe8exc5R1dXjX6k9ZTOKSM6DiWenDoxHkad1TIyKrWGJdVSXjSfGS&X-Amz-Signature=4e72895b0762f98a583913de8e711f29ab7617f988922407f2929a01138fc63c&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XM5GWP7C%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T152750Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDpW0G2FqobuPannPhIztyGHpfRMZZMivhO8HrIZEPirAIhAPpWtCrsiVa9ygMKZPwYWPLa%2BVuNPGB0Wv%2FS%2BekuO6INKv8DCDAQABoMNjM3NDIzMTgzODA1IgwCRVynGGJW3HNpg5cq3AOUf2n8OlNi7AzvDHH9WnymzL1UQHIoNByvbH1VYNzCphJhRaODgZkb6rT6aVuQBaJRDgx8o8NIf%2FZ4uDCRHKiooxm8f%2F34VX9BEGVGaZANsda1jSonmK8h6FCs4vVmeiHiLJOjmrLaq4Vp11cHYnJmzpIR1ywC7RqyQzswNs04L0pTS66MOM6TXBLn8cXxb1B1J5f61C02evDtw8K0392ZgTI4usXbzKsRlMxJZZzERnmVd0hbm45d9cqUL5u%2B1HI6Uae26ljNb53Az1kIIM4rbuOMfaBN6jUEMWej8UBwh8oRT79hsdrlrJqT0SWom2sv2uwhZL0PjyprslFTsoNCJLqA6zYnjTtBlv5jc0GD5IofZIDjVI%2F9aOm8gfsjOTegxHP30DE2jCS%2FFZkmU7H36rH8RrwclKHULPYga2o5pwVWbuc2Pp3Cay9%2FRIhMMn6g6VyB6hxk%2Ftrkzv8AVxlhGGkE7qxRLRmYOEkyQV0LuCBRB00nHBiPCzBJjV%2F3PgnjRXpI15ONdV9v5Of3UeER0fbqisIGx5IlqIGfSJ8x0wY%2B73ldJ9jpDzsWKuU3d8WbNw%2BmTtiMnLW5TGeJpt%2B%2FipDCImD%2BF48tV%2Fe%2Bl4K9InpJk%2B0KmIFVKbS%2BYjC7nPK9BjqkAXjcTofzvvCMpGJQt1nAYwN6a4kh3HN6Xmz41pvUQYXJYpw2wMbdkpAEsANlqzxeP8DT3OO2uXytYcoOWJEsIm6lllxXXqjiH%2BG1O5%2Bz2tq6fj79uFdKQUypgw8868EeyawSeIqzjswwyhjeDcSPt3vDJBYEzb0htA7ebGRoHRNV28usP9kV4CY9vdVMMVRK7W1JkkGN3i2%2ByDydRdw%2FB7FgHFEx&X-Amz-Signature=364092b48f90c2217112f82cb16066896a4f541ec29decde1ab172013d4c22a0&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XM5GWP7C%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T152750Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDpW0G2FqobuPannPhIztyGHpfRMZZMivhO8HrIZEPirAIhAPpWtCrsiVa9ygMKZPwYWPLa%2BVuNPGB0Wv%2FS%2BekuO6INKv8DCDAQABoMNjM3NDIzMTgzODA1IgwCRVynGGJW3HNpg5cq3AOUf2n8OlNi7AzvDHH9WnymzL1UQHIoNByvbH1VYNzCphJhRaODgZkb6rT6aVuQBaJRDgx8o8NIf%2FZ4uDCRHKiooxm8f%2F34VX9BEGVGaZANsda1jSonmK8h6FCs4vVmeiHiLJOjmrLaq4Vp11cHYnJmzpIR1ywC7RqyQzswNs04L0pTS66MOM6TXBLn8cXxb1B1J5f61C02evDtw8K0392ZgTI4usXbzKsRlMxJZZzERnmVd0hbm45d9cqUL5u%2B1HI6Uae26ljNb53Az1kIIM4rbuOMfaBN6jUEMWej8UBwh8oRT79hsdrlrJqT0SWom2sv2uwhZL0PjyprslFTsoNCJLqA6zYnjTtBlv5jc0GD5IofZIDjVI%2F9aOm8gfsjOTegxHP30DE2jCS%2FFZkmU7H36rH8RrwclKHULPYga2o5pwVWbuc2Pp3Cay9%2FRIhMMn6g6VyB6hxk%2Ftrkzv8AVxlhGGkE7qxRLRmYOEkyQV0LuCBRB00nHBiPCzBJjV%2F3PgnjRXpI15ONdV9v5Of3UeER0fbqisIGx5IlqIGfSJ8x0wY%2B73ldJ9jpDzsWKuU3d8WbNw%2BmTtiMnLW5TGeJpt%2B%2FipDCImD%2BF48tV%2Fe%2Bl4K9InpJk%2B0KmIFVKbS%2BYjC7nPK9BjqkAXjcTofzvvCMpGJQt1nAYwN6a4kh3HN6Xmz41pvUQYXJYpw2wMbdkpAEsANlqzxeP8DT3OO2uXytYcoOWJEsIm6lllxXXqjiH%2BG1O5%2Bz2tq6fj79uFdKQUypgw8868EeyawSeIqzjswwyhjeDcSPt3vDJBYEzb0htA7ebGRoHRNV28usP9kV4CY9vdVMMVRK7W1JkkGN3i2%2ByDydRdw%2FB7FgHFEx&X-Amz-Signature=4fb4dee6664393a3c86463d279c20fd3665f2ae34eeb864a565243d402198052&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XM5GWP7C%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T152750Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDpW0G2FqobuPannPhIztyGHpfRMZZMivhO8HrIZEPirAIhAPpWtCrsiVa9ygMKZPwYWPLa%2BVuNPGB0Wv%2FS%2BekuO6INKv8DCDAQABoMNjM3NDIzMTgzODA1IgwCRVynGGJW3HNpg5cq3AOUf2n8OlNi7AzvDHH9WnymzL1UQHIoNByvbH1VYNzCphJhRaODgZkb6rT6aVuQBaJRDgx8o8NIf%2FZ4uDCRHKiooxm8f%2F34VX9BEGVGaZANsda1jSonmK8h6FCs4vVmeiHiLJOjmrLaq4Vp11cHYnJmzpIR1ywC7RqyQzswNs04L0pTS66MOM6TXBLn8cXxb1B1J5f61C02evDtw8K0392ZgTI4usXbzKsRlMxJZZzERnmVd0hbm45d9cqUL5u%2B1HI6Uae26ljNb53Az1kIIM4rbuOMfaBN6jUEMWej8UBwh8oRT79hsdrlrJqT0SWom2sv2uwhZL0PjyprslFTsoNCJLqA6zYnjTtBlv5jc0GD5IofZIDjVI%2F9aOm8gfsjOTegxHP30DE2jCS%2FFZkmU7H36rH8RrwclKHULPYga2o5pwVWbuc2Pp3Cay9%2FRIhMMn6g6VyB6hxk%2Ftrkzv8AVxlhGGkE7qxRLRmYOEkyQV0LuCBRB00nHBiPCzBJjV%2F3PgnjRXpI15ONdV9v5Of3UeER0fbqisIGx5IlqIGfSJ8x0wY%2B73ldJ9jpDzsWKuU3d8WbNw%2BmTtiMnLW5TGeJpt%2B%2FipDCImD%2BF48tV%2Fe%2Bl4K9InpJk%2B0KmIFVKbS%2BYjC7nPK9BjqkAXjcTofzvvCMpGJQt1nAYwN6a4kh3HN6Xmz41pvUQYXJYpw2wMbdkpAEsANlqzxeP8DT3OO2uXytYcoOWJEsIm6lllxXXqjiH%2BG1O5%2Bz2tq6fj79uFdKQUypgw8868EeyawSeIqzjswwyhjeDcSPt3vDJBYEzb0htA7ebGRoHRNV28usP9kV4CY9vdVMMVRK7W1JkkGN3i2%2ByDydRdw%2FB7FgHFEx&X-Amz-Signature=83c2ac743d9e78cebd5290c3751a7d653d2aa1a6164bb92217f83cf485c9175b&X-Amz-SignedHeaders=host&x-id=GetObject)


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

