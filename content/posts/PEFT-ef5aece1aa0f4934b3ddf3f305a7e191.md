---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466YKKO27WB%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250206T102521Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEEEaCXVzLXdlc3QtMiJHMEUCICA35iqJqVIW87hga8aH3%2FnM9RO5COadNR%2FfjIyMOV3yAiE\
  Aj7%2BSRuQBpf9THMiyxAxbI5NJI0zxVvDRPD9eo%2F%2FS8joq%2FwMIWhAAGgw2Mzc0MjMxODM4\
  MDUiDCLiuohvUNbzqanAxCrcA%2F%2F%2FIuuzzy2AjYP59XYMblim8t7jCJgyMUqyUT5EN4M4Z5C\
  WFDMmgZXCWVU4hX9UGM48PlQ8vsn%2BVRIPWo7fu9grTNRSOfrA3V1hQxyYXdL1LSZEdPVyp9H6BQ\
  Y2QBfO0TAiRyQ%2FEyg8HZVVAXOVVW0arnLhmVIwqiwmZ1xvbVaufhtw7haUmIWt8lkgYZOP4mnp2\
  bACMFmGXdOzDuCbP6qRUdaHOfgFmKZ0bJbRtAmCcHpf708v%2BWoSNaQCfGaH65E%2FRMf5w%2FAs\
  J8hZnQnuf0qBzjglBoYrZVZqcAZxyfIsG7JFx4d%2FB7P6zIBqBPVe%2FzKq44tfWNRHFtwuyZ2Oy\
  UmwGeuPisTiTfoj%2Fc4FE8VuNalEaesf9q49etnY2yC3XNHAnoTMLTyqoNSdVaG6WMud3buxOAYB\
  TO%2BiljvbOPXeTckpqjSDPP8WLsI6xwsU3%2Bd%2B7N2ukFibQIgWeQZEpfkiAq%2FAUnMFD3RnT\
  PQUnpnJa%2Bx3g43FZTMr5jz1hEaqXbPPdKheNYpHPOUML221mqhlceRYKo7nEIzktgh74lrhCUfH\
  qn25vT2IxIDWofIbF0oi3SDIicJgUV3trakjuOHuZKnZwHLJ%2BUMKY9tUmC7GTOEtBRibIuuWp9v\
  cMOPtkb0GOqUB98w7OzHtXZzIv8o6yF2m5obYK8e6UMJAIBMnjnNsmDFBIUOwS3Fxg5CUvptG4i6F\
  K3vmWH1fm7LO20vlap4wT18y0rtE7%2F219Wrj0k0d%2BW7EetOOqyjYCHaq2gCDFpeoEGPWdBivx\
  XT3yJCNxMvuD29jwVXbsvYVx5AaZMX%2FYUHxbWqtzfszNiB0PIrDT5SiNeNXCLE7u4Mchy7%2BgO\
  e%2FH2Z8NHxB&X-Amz-Signature=2111c42dcc6ebbc2d85d523658dfaa3f0281d87025fbdae3\
  e9132825b3973560&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466SOUENFAB%2F20250206%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250206T102417Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJHMEUCIQCban4X%2BLPD2WkF%2BJUFfUf4z6%\
        2F0xbt1o%2BYFF%2BpkDnRAiAIgIrORMJ7i0DDx5PIlE5F9K5E6LDGJqKsqTXMkQX0lCucq\
        %2FwMIWhAAGgw2Mzc0MjMxODM4MDUiDC%2B2nVyn5Sp0upXi0yrcA8IRutBLCMpGLJ9AlLr\
        R5Q9UBLA8NDgS%2F%2BKJCnGutjOhEZEee8UkNBrl7Q3%2B%2FjNFHOde19c0Td3tkqbgOg\
        mil%2BnAtZE0mPTM4LNzXzUevWATW1lFA%2FSNdrm0cf%2BJUAeQBTQ0qdADYUY65tuirnH\
        W2BFLGohsmcILKYCPgbiHNZGRH2%2FWZP0xpq14hXR4CJApjrIwII3cHyRC4ww8umkQWYkc\
        R4p62oEcTsZXpSE7pjcgH6MgX37am%2BWLqbAdU%2BanEV9seG%2F5r3jiXzm3sxBU%2BWi\
        dJKBiP8lwbWSu41p96n5tn5CdpiVRhetHy3QDKjc%2FoswigOahACvnpM3DV%2F1N8u5FB4\
        hNUxLRuSiF7S9PS8UfJiEmM8opk8iPhTt62USJ03gdoUNLLdmg%2FrGfDiFxTK6oYy9ClIG\
        78SODt1kaL3D8wo5IVouDBPtLUgcPVZyw5Tm9JS0L%2BeCq66NziI6rTkVIxTOyQJtKSKDT\
        yPN%2BDDRAEKTHOHD6HKuywvPGonk8vkPvqpMgaW6wJMOeP0RhdO1%2BHP26VEH%2BPfgD7\
        ELpWYBIpDY4BRgW7p1w7FlSzJKVw5V399it0VnNpk55eSSqWX%2BbE%2BCcDreioO65XSNM\
        T8yLfnZ4B2TvPxiOpgP5MKXtkb0GOqUBX%2FETpD337%2B0ONtClueN3EBY2o9hYb6L6TTP\
        EYWl1JPt4s6etv1nGckD6AyZKrH2NLw4RD2u2athW81301uKTGjmuGZ4aXh73T%2BW0z%2F\
        xPFiQbSTWiG%2BciUi2Vu7XZHAJ%2BZFJlagyHU1XrfcDRJVM6cB%2FbHSmIsQSFHxLPx9A\
        NMHXOyRIiZqw%2FieGo5804FsnSlB6j3FCRLH6ZhlZzL3CCwxVitajV&X-Amz-Signature\
        =eda9521b4eca1e862552676bd34983faff13ec2584cf269172c087f8f8b014a6&X-Amz\
        -SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-06T11:24:17.862Z"
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
UPDATE_TIME: "2025-02-06T10:25:25.045Z"
EXPIRY_TIME: "2025-02-06T11:25:16.877Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662W575NGZ%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T102517Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJHMEUCIAtmLXdgVLUN%2FfCCNzkeggeYe1v%2Bb7zYT59MMRFQrZimAiEA9SCeAjpvVVf9GIycNGWtcvD4xOu6XQHxH67Q0U%2BLV7Eq%2FwMIWhAAGgw2Mzc0MjMxODM4MDUiDPu7zCKmvgAlgCPVOCrcA4dtwnHJQHxSv5XKRgNJ0t67UuD7eCuRDhgo%2F%2FUXAnPflPWuvNURo0niJdbklOcBu0TiOXfmr%2BSZEBqoNnW1HuVLw9VHt7bfGgXYeX83wXU9U6DThd3xnLxRZlKscJj6ZzyUr4dj9KWErlEgwvOlZqqKN5Ps%2BrOJJR8%2FHegK0eC%2FiSjXfVKG3gEYmAsA2vutnoGt%2FHtsjyqgPVQS9SFd7k1CkfB98B%2FQbpCBFi%2FH9LPETVnq3Yi2kiH%2F4eWk7%2B9zTyzLoADm34IAL4jDWExo%2FLOgIJ6HFTgZRYDHkzoI%2F3Y19%2Bq4Q2BM%2BTNfCpNRw8tnmhZnuSl4G%2FCA4f4qBi7MNnKWiXMv6HOh3NHhoba7IlSn9Sa94Gu0r%2F51KvrHteEx54UB59UtfoTx71y%2FnOGMokUqPMH9WXaD7RqVm%2BuIHIfflaXnPmyTfco8HQRnW9sl%2B8m9ItqJ5mbvRK7St%2BxFQg3bkcwu80vH1oybfp709h0%2BRzftHA5pKmsDfYR8R4z1jptA6S1JMS%2F0Nhl2Ovvi%2FbzyYqj8qgFzRObbASVzpPoIvWFoosz%2BSvu52tmflyU7DDxOiamPvh6Rwr%2B8a13IICP9qVUyQmM2d5tJUo14FJrWiFmne7PDrny9qEprMIjtkb0GOqUBlB%2BWhaK5aoXCjfG9VKMw6OJPmbW51LvR8JRxDfwCBH80RsBYXnx28DhEIYfzTlyvo1rFksXqbRLCtrXm%2F02NUJhOc6iP%2BFqFPDCuz%2FeOdHtFdB465JQJrsRWkzJWOYtEV40e%2FKWWtImteyEiSjhC%2FgvA3mI%2Bi9K35pYRb3r8qwSmZTKL3GJr5htALMFszyGoKK6Phcj%2BkGq7TBTfE8NvcxX8pHQT&X-Amz-Signature=6c9bbc6a20d48146080e39dd14d56409adf515b1bafbea341d4cf27a76094bfd&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662W575NGZ%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T102517Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJHMEUCIAtmLXdgVLUN%2FfCCNzkeggeYe1v%2Bb7zYT59MMRFQrZimAiEA9SCeAjpvVVf9GIycNGWtcvD4xOu6XQHxH67Q0U%2BLV7Eq%2FwMIWhAAGgw2Mzc0MjMxODM4MDUiDPu7zCKmvgAlgCPVOCrcA4dtwnHJQHxSv5XKRgNJ0t67UuD7eCuRDhgo%2F%2FUXAnPflPWuvNURo0niJdbklOcBu0TiOXfmr%2BSZEBqoNnW1HuVLw9VHt7bfGgXYeX83wXU9U6DThd3xnLxRZlKscJj6ZzyUr4dj9KWErlEgwvOlZqqKN5Ps%2BrOJJR8%2FHegK0eC%2FiSjXfVKG3gEYmAsA2vutnoGt%2FHtsjyqgPVQS9SFd7k1CkfB98B%2FQbpCBFi%2FH9LPETVnq3Yi2kiH%2F4eWk7%2B9zTyzLoADm34IAL4jDWExo%2FLOgIJ6HFTgZRYDHkzoI%2F3Y19%2Bq4Q2BM%2BTNfCpNRw8tnmhZnuSl4G%2FCA4f4qBi7MNnKWiXMv6HOh3NHhoba7IlSn9Sa94Gu0r%2F51KvrHteEx54UB59UtfoTx71y%2FnOGMokUqPMH9WXaD7RqVm%2BuIHIfflaXnPmyTfco8HQRnW9sl%2B8m9ItqJ5mbvRK7St%2BxFQg3bkcwu80vH1oybfp709h0%2BRzftHA5pKmsDfYR8R4z1jptA6S1JMS%2F0Nhl2Ovvi%2FbzyYqj8qgFzRObbASVzpPoIvWFoosz%2BSvu52tmflyU7DDxOiamPvh6Rwr%2B8a13IICP9qVUyQmM2d5tJUo14FJrWiFmne7PDrny9qEprMIjtkb0GOqUBlB%2BWhaK5aoXCjfG9VKMw6OJPmbW51LvR8JRxDfwCBH80RsBYXnx28DhEIYfzTlyvo1rFksXqbRLCtrXm%2F02NUJhOc6iP%2BFqFPDCuz%2FeOdHtFdB465JQJrsRWkzJWOYtEV40e%2FKWWtImteyEiSjhC%2FgvA3mI%2Bi9K35pYRb3r8qwSmZTKL3GJr5htALMFszyGoKK6Phcj%2BkGq7TBTfE8NvcxX8pHQT&X-Amz-Signature=3de1cc32051503546c97b2c38d6772d3cca1354f096cade038a2f8b743e54a89&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662W575NGZ%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T102517Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJHMEUCIAtmLXdgVLUN%2FfCCNzkeggeYe1v%2Bb7zYT59MMRFQrZimAiEA9SCeAjpvVVf9GIycNGWtcvD4xOu6XQHxH67Q0U%2BLV7Eq%2FwMIWhAAGgw2Mzc0MjMxODM4MDUiDPu7zCKmvgAlgCPVOCrcA4dtwnHJQHxSv5XKRgNJ0t67UuD7eCuRDhgo%2F%2FUXAnPflPWuvNURo0niJdbklOcBu0TiOXfmr%2BSZEBqoNnW1HuVLw9VHt7bfGgXYeX83wXU9U6DThd3xnLxRZlKscJj6ZzyUr4dj9KWErlEgwvOlZqqKN5Ps%2BrOJJR8%2FHegK0eC%2FiSjXfVKG3gEYmAsA2vutnoGt%2FHtsjyqgPVQS9SFd7k1CkfB98B%2FQbpCBFi%2FH9LPETVnq3Yi2kiH%2F4eWk7%2B9zTyzLoADm34IAL4jDWExo%2FLOgIJ6HFTgZRYDHkzoI%2F3Y19%2Bq4Q2BM%2BTNfCpNRw8tnmhZnuSl4G%2FCA4f4qBi7MNnKWiXMv6HOh3NHhoba7IlSn9Sa94Gu0r%2F51KvrHteEx54UB59UtfoTx71y%2FnOGMokUqPMH9WXaD7RqVm%2BuIHIfflaXnPmyTfco8HQRnW9sl%2B8m9ItqJ5mbvRK7St%2BxFQg3bkcwu80vH1oybfp709h0%2BRzftHA5pKmsDfYR8R4z1jptA6S1JMS%2F0Nhl2Ovvi%2FbzyYqj8qgFzRObbASVzpPoIvWFoosz%2BSvu52tmflyU7DDxOiamPvh6Rwr%2B8a13IICP9qVUyQmM2d5tJUo14FJrWiFmne7PDrny9qEprMIjtkb0GOqUBlB%2BWhaK5aoXCjfG9VKMw6OJPmbW51LvR8JRxDfwCBH80RsBYXnx28DhEIYfzTlyvo1rFksXqbRLCtrXm%2F02NUJhOc6iP%2BFqFPDCuz%2FeOdHtFdB465JQJrsRWkzJWOYtEV40e%2FKWWtImteyEiSjhC%2FgvA3mI%2Bi9K35pYRb3r8qwSmZTKL3GJr5htALMFszyGoKK6Phcj%2BkGq7TBTfE8NvcxX8pHQT&X-Amz-Signature=9ecaece491f1f33fc5581adeae030f7e796033789fae000cd8ce8566ff2c0cdb&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662W575NGZ%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T102517Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJHMEUCIAtmLXdgVLUN%2FfCCNzkeggeYe1v%2Bb7zYT59MMRFQrZimAiEA9SCeAjpvVVf9GIycNGWtcvD4xOu6XQHxH67Q0U%2BLV7Eq%2FwMIWhAAGgw2Mzc0MjMxODM4MDUiDPu7zCKmvgAlgCPVOCrcA4dtwnHJQHxSv5XKRgNJ0t67UuD7eCuRDhgo%2F%2FUXAnPflPWuvNURo0niJdbklOcBu0TiOXfmr%2BSZEBqoNnW1HuVLw9VHt7bfGgXYeX83wXU9U6DThd3xnLxRZlKscJj6ZzyUr4dj9KWErlEgwvOlZqqKN5Ps%2BrOJJR8%2FHegK0eC%2FiSjXfVKG3gEYmAsA2vutnoGt%2FHtsjyqgPVQS9SFd7k1CkfB98B%2FQbpCBFi%2FH9LPETVnq3Yi2kiH%2F4eWk7%2B9zTyzLoADm34IAL4jDWExo%2FLOgIJ6HFTgZRYDHkzoI%2F3Y19%2Bq4Q2BM%2BTNfCpNRw8tnmhZnuSl4G%2FCA4f4qBi7MNnKWiXMv6HOh3NHhoba7IlSn9Sa94Gu0r%2F51KvrHteEx54UB59UtfoTx71y%2FnOGMokUqPMH9WXaD7RqVm%2BuIHIfflaXnPmyTfco8HQRnW9sl%2B8m9ItqJ5mbvRK7St%2BxFQg3bkcwu80vH1oybfp709h0%2BRzftHA5pKmsDfYR8R4z1jptA6S1JMS%2F0Nhl2Ovvi%2FbzyYqj8qgFzRObbASVzpPoIvWFoosz%2BSvu52tmflyU7DDxOiamPvh6Rwr%2B8a13IICP9qVUyQmM2d5tJUo14FJrWiFmne7PDrny9qEprMIjtkb0GOqUBlB%2BWhaK5aoXCjfG9VKMw6OJPmbW51LvR8JRxDfwCBH80RsBYXnx28DhEIYfzTlyvo1rFksXqbRLCtrXm%2F02NUJhOc6iP%2BFqFPDCuz%2FeOdHtFdB465JQJrsRWkzJWOYtEV40e%2FKWWtImteyEiSjhC%2FgvA3mI%2Bi9K35pYRb3r8qwSmZTKL3GJr5htALMFszyGoKK6Phcj%2BkGq7TBTfE8NvcxX8pHQT&X-Amz-Signature=0739492df42bcb35735b429dbe908c75721ccaea0942c2cf9e4c06ff8da7b8f4&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662W575NGZ%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T102517Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJHMEUCIAtmLXdgVLUN%2FfCCNzkeggeYe1v%2Bb7zYT59MMRFQrZimAiEA9SCeAjpvVVf9GIycNGWtcvD4xOu6XQHxH67Q0U%2BLV7Eq%2FwMIWhAAGgw2Mzc0MjMxODM4MDUiDPu7zCKmvgAlgCPVOCrcA4dtwnHJQHxSv5XKRgNJ0t67UuD7eCuRDhgo%2F%2FUXAnPflPWuvNURo0niJdbklOcBu0TiOXfmr%2BSZEBqoNnW1HuVLw9VHt7bfGgXYeX83wXU9U6DThd3xnLxRZlKscJj6ZzyUr4dj9KWErlEgwvOlZqqKN5Ps%2BrOJJR8%2FHegK0eC%2FiSjXfVKG3gEYmAsA2vutnoGt%2FHtsjyqgPVQS9SFd7k1CkfB98B%2FQbpCBFi%2FH9LPETVnq3Yi2kiH%2F4eWk7%2B9zTyzLoADm34IAL4jDWExo%2FLOgIJ6HFTgZRYDHkzoI%2F3Y19%2Bq4Q2BM%2BTNfCpNRw8tnmhZnuSl4G%2FCA4f4qBi7MNnKWiXMv6HOh3NHhoba7IlSn9Sa94Gu0r%2F51KvrHteEx54UB59UtfoTx71y%2FnOGMokUqPMH9WXaD7RqVm%2BuIHIfflaXnPmyTfco8HQRnW9sl%2B8m9ItqJ5mbvRK7St%2BxFQg3bkcwu80vH1oybfp709h0%2BRzftHA5pKmsDfYR8R4z1jptA6S1JMS%2F0Nhl2Ovvi%2FbzyYqj8qgFzRObbASVzpPoIvWFoosz%2BSvu52tmflyU7DDxOiamPvh6Rwr%2B8a13IICP9qVUyQmM2d5tJUo14FJrWiFmne7PDrny9qEprMIjtkb0GOqUBlB%2BWhaK5aoXCjfG9VKMw6OJPmbW51LvR8JRxDfwCBH80RsBYXnx28DhEIYfzTlyvo1rFksXqbRLCtrXm%2F02NUJhOc6iP%2BFqFPDCuz%2FeOdHtFdB465JQJrsRWkzJWOYtEV40e%2FKWWtImteyEiSjhC%2FgvA3mI%2Bi9K35pYRb3r8qwSmZTKL3GJr5htALMFszyGoKK6Phcj%2BkGq7TBTfE8NvcxX8pHQT&X-Amz-Signature=95fd67ddffa3d76b03366ebc30fbb9f8b829d503e22f647046343facb6db334d&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SKJL2IFY%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T102518Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJHMEUCIQCKNE01SFaTMIgM2i%2FavFiI0nqsrbXchdVU8eW98JEgigIgFPpW16%2BnXuusQn1WFyRg1E%2FO4NPZ7kAQxRQZQ%2FPASsYq%2FwMIWhAAGgw2Mzc0MjMxODM4MDUiDAD%2FtyfIPaexhkQA4CrcAy%2Bepd7mQdt1ROSlCPaFt3AIkKF3ZMP58B10D22DGsqgYrNtIfjjrCmAPRIP8hzwzgAZIw1hwEwYKh5FGKB3lpDTy425dzrZiJ0MWD568qkp0YKzZqgu6GuUFxU99qBMbFLO99hivRo5%2FDirpA1dSD5bh2wiA%2FCxSSa3ufjTYOG0Y8jLrzf7DfkfKKZ3zD%2BuQOzjqZpZvuwvTSidnNGA5MqB4nekWaKZTYMPU7XZK3rIwq0DV0ZEhxugoDkPLAZUAusfKOtBnfZnS0OUan24VsN%2BNlUqqE2rGi%2BZZqXqODjZTg%2By55dlvZSR2Lxs0wIlTE89eIokcbZwGh3RZAogDIOIuIJrsVnkovLT%2BdDcLIcwqCsWoEZl%2B%2B7uNE4biPu48WeNhZr%2BOHsELlEurOVqmRcGVg3ZhQNRPLiH%2Bdy7EvPJdQMY7yBY6%2B2Acyz9vRDgH6f8Zwr5L2hok5InMrmbgr%2FqZAK%2B6JR82CHVZ8zeGpiIJ%2F%2BgBlidWoFkDKxwfeiN4nJjWNk%2BQxQLvViyR3L4Ymr5ZKKrtQzElW9pqtPXeKki1maSDBDZvM4k3PjSoXPHD9HxHyVhJLA3Z%2BeEOtcZ4DzVK7d6ICZoKsePwpgnfUZAGBUYUeTU9X5TnFAXMI%2Ftkb0GOqUBk2EUauQyAMBaKChoXhYHl0%2F1zZp%2Bfk7eoAQbTR6iz2CshPGUZZ%2BodUE9r%2FHA6hi%2BNVigo9knlQkwxWQqQGs6gcnGnDHmRTyWGIyxUxCim8aZpvLXTWJq9OSa80b2QAkXz5cxn16hYuYPIsk8%2BG%2BljF49x58CaZGBEbJEch57pbkHOPA54Ww2NoSq%2Fk%2FAtSxDNNYfYTqoGsyOJRQgCrNJbcS062nU&X-Amz-Signature=1c62c994a809a893216e98b17e0b065cdbe6d3b9bec0b567db89ec463a720cd1&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665TMEKOYW%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T102518Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJHMEUCIBpkGgCPoBqDifUE4gL6%2Fbo%2FNnnBjHiLSaZfyEZwwP1rAiEA1ijqL%2FJihdFhXZSSOrhmkr3kusVd7BodOXwqSEIuTk8q%2FwMIWhAAGgw2Mzc0MjMxODM4MDUiDG337i3rkhz08XTEdircA86QDB2Ff4oX91uqSVlxNBNIrgLkfkOCL2GZRUua1FOC0IYTLc9koXlVxSrjfWpFJ0A5Uas5rUU7W50iLfr0Q3QKkuSe4tia%2F%2BSyETZfpLBTxo2j1OMGBcm%2FcJSpMCo1mSwe4INjil%2FXDYtxvN9%2FfgJ%2FeUi5jctnhKmDDgwzYOR4slGQig4ksf%2B9nsfm%2BurbGrQ68SsHb1zVoYzP3uYVG0Hs%2FSanzNWzrQsesFjmS5oPXKceqSSPANg3r9wwsZu1jlePZyuc8q5LmaEJw75J2V2GGEmmOl0tFv%2Fh%2FYH1XYFuh5Dtg6%2FVJveRZ5KRhWYB56y%2BT%2B2fxTPNpRnBzymUNpIQBBDjHJpc28acOz7ifHoZmWFOXZyxeKT5x%2FfxOqwSgImrEzvNDO0MZ%2FbQADoQKOfumfdPBYP9%2BJb7b8dsRpm%2BQD%2FfTDTg1%2B5zgN7A0btgOBuOF%2FBMe8PVhPgkdjA8iEdR%2BJukoiwozrcE7j1KYrpkKLavQa9gIT%2FcJtfPajSOUXJCYIH931gsGjYvPw8qWGfqA9vdSFhaMMDGwip%2FaZzbdutW9DADl%2FyC3TP2YJ4%2F4kGh%2B1tF60MsTgxIt6dB%2BvRm7gAOrp%2B8ZdQSuervO5Faft5LRG4VL6%2F7jY3IMOfukb0GOqUBjijwk1kIzk6mJOA%2BficHcoZpZEfB1sDuWfhec7r9H05PfctT3Nxda%2Fy7i7d3BZCmb5Mhaf7w6w4P8qmK74tqkLBH5FvDSq7eCOTfsjHTlYvPrSDlwm%2BHQZkI76Qum4h7IZDpE28kUvu3VlNtjEh0oPKBp8zyJo9JxoJQ2EfCNwUeKZl3o1HSk4dKZh5CHVZ9BNzmNG%2FVD7nHN03viV3vdrL15KfD&X-Amz-Signature=6bbd8911c7f8f74767b1e1cb985c21d11396babc08e3c7486d41a352f575d2cc&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662W575NGZ%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T102517Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJHMEUCIAtmLXdgVLUN%2FfCCNzkeggeYe1v%2Bb7zYT59MMRFQrZimAiEA9SCeAjpvVVf9GIycNGWtcvD4xOu6XQHxH67Q0U%2BLV7Eq%2FwMIWhAAGgw2Mzc0MjMxODM4MDUiDPu7zCKmvgAlgCPVOCrcA4dtwnHJQHxSv5XKRgNJ0t67UuD7eCuRDhgo%2F%2FUXAnPflPWuvNURo0niJdbklOcBu0TiOXfmr%2BSZEBqoNnW1HuVLw9VHt7bfGgXYeX83wXU9U6DThd3xnLxRZlKscJj6ZzyUr4dj9KWErlEgwvOlZqqKN5Ps%2BrOJJR8%2FHegK0eC%2FiSjXfVKG3gEYmAsA2vutnoGt%2FHtsjyqgPVQS9SFd7k1CkfB98B%2FQbpCBFi%2FH9LPETVnq3Yi2kiH%2F4eWk7%2B9zTyzLoADm34IAL4jDWExo%2FLOgIJ6HFTgZRYDHkzoI%2F3Y19%2Bq4Q2BM%2BTNfCpNRw8tnmhZnuSl4G%2FCA4f4qBi7MNnKWiXMv6HOh3NHhoba7IlSn9Sa94Gu0r%2F51KvrHteEx54UB59UtfoTx71y%2FnOGMokUqPMH9WXaD7RqVm%2BuIHIfflaXnPmyTfco8HQRnW9sl%2B8m9ItqJ5mbvRK7St%2BxFQg3bkcwu80vH1oybfp709h0%2BRzftHA5pKmsDfYR8R4z1jptA6S1JMS%2F0Nhl2Ovvi%2FbzyYqj8qgFzRObbASVzpPoIvWFoosz%2BSvu52tmflyU7DDxOiamPvh6Rwr%2B8a13IICP9qVUyQmM2d5tJUo14FJrWiFmne7PDrny9qEprMIjtkb0GOqUBlB%2BWhaK5aoXCjfG9VKMw6OJPmbW51LvR8JRxDfwCBH80RsBYXnx28DhEIYfzTlyvo1rFksXqbRLCtrXm%2F02NUJhOc6iP%2BFqFPDCuz%2FeOdHtFdB465JQJrsRWkzJWOYtEV40e%2FKWWtImteyEiSjhC%2FgvA3mI%2Bi9K35pYRb3r8qwSmZTKL3GJr5htALMFszyGoKK6Phcj%2BkGq7TBTfE8NvcxX8pHQT&X-Amz-Signature=9afe977cfcec40cdb59f0badd789d532ba4a7eb953ed9e6f82ed0f47fc1500a9&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662W575NGZ%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T102517Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJHMEUCIAtmLXdgVLUN%2FfCCNzkeggeYe1v%2Bb7zYT59MMRFQrZimAiEA9SCeAjpvVVf9GIycNGWtcvD4xOu6XQHxH67Q0U%2BLV7Eq%2FwMIWhAAGgw2Mzc0MjMxODM4MDUiDPu7zCKmvgAlgCPVOCrcA4dtwnHJQHxSv5XKRgNJ0t67UuD7eCuRDhgo%2F%2FUXAnPflPWuvNURo0niJdbklOcBu0TiOXfmr%2BSZEBqoNnW1HuVLw9VHt7bfGgXYeX83wXU9U6DThd3xnLxRZlKscJj6ZzyUr4dj9KWErlEgwvOlZqqKN5Ps%2BrOJJR8%2FHegK0eC%2FiSjXfVKG3gEYmAsA2vutnoGt%2FHtsjyqgPVQS9SFd7k1CkfB98B%2FQbpCBFi%2FH9LPETVnq3Yi2kiH%2F4eWk7%2B9zTyzLoADm34IAL4jDWExo%2FLOgIJ6HFTgZRYDHkzoI%2F3Y19%2Bq4Q2BM%2BTNfCpNRw8tnmhZnuSl4G%2FCA4f4qBi7MNnKWiXMv6HOh3NHhoba7IlSn9Sa94Gu0r%2F51KvrHteEx54UB59UtfoTx71y%2FnOGMokUqPMH9WXaD7RqVm%2BuIHIfflaXnPmyTfco8HQRnW9sl%2B8m9ItqJ5mbvRK7St%2BxFQg3bkcwu80vH1oybfp709h0%2BRzftHA5pKmsDfYR8R4z1jptA6S1JMS%2F0Nhl2Ovvi%2FbzyYqj8qgFzRObbASVzpPoIvWFoosz%2BSvu52tmflyU7DDxOiamPvh6Rwr%2B8a13IICP9qVUyQmM2d5tJUo14FJrWiFmne7PDrny9qEprMIjtkb0GOqUBlB%2BWhaK5aoXCjfG9VKMw6OJPmbW51LvR8JRxDfwCBH80RsBYXnx28DhEIYfzTlyvo1rFksXqbRLCtrXm%2F02NUJhOc6iP%2BFqFPDCuz%2FeOdHtFdB465JQJrsRWkzJWOYtEV40e%2FKWWtImteyEiSjhC%2FgvA3mI%2Bi9K35pYRb3r8qwSmZTKL3GJr5htALMFszyGoKK6Phcj%2BkGq7TBTfE8NvcxX8pHQT&X-Amz-Signature=a6da5d694de74974a277737d9b2c49f3a88ac2d11b600097fc51f9b16983595d&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662W575NGZ%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T102517Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJHMEUCIAtmLXdgVLUN%2FfCCNzkeggeYe1v%2Bb7zYT59MMRFQrZimAiEA9SCeAjpvVVf9GIycNGWtcvD4xOu6XQHxH67Q0U%2BLV7Eq%2FwMIWhAAGgw2Mzc0MjMxODM4MDUiDPu7zCKmvgAlgCPVOCrcA4dtwnHJQHxSv5XKRgNJ0t67UuD7eCuRDhgo%2F%2FUXAnPflPWuvNURo0niJdbklOcBu0TiOXfmr%2BSZEBqoNnW1HuVLw9VHt7bfGgXYeX83wXU9U6DThd3xnLxRZlKscJj6ZzyUr4dj9KWErlEgwvOlZqqKN5Ps%2BrOJJR8%2FHegK0eC%2FiSjXfVKG3gEYmAsA2vutnoGt%2FHtsjyqgPVQS9SFd7k1CkfB98B%2FQbpCBFi%2FH9LPETVnq3Yi2kiH%2F4eWk7%2B9zTyzLoADm34IAL4jDWExo%2FLOgIJ6HFTgZRYDHkzoI%2F3Y19%2Bq4Q2BM%2BTNfCpNRw8tnmhZnuSl4G%2FCA4f4qBi7MNnKWiXMv6HOh3NHhoba7IlSn9Sa94Gu0r%2F51KvrHteEx54UB59UtfoTx71y%2FnOGMokUqPMH9WXaD7RqVm%2BuIHIfflaXnPmyTfco8HQRnW9sl%2B8m9ItqJ5mbvRK7St%2BxFQg3bkcwu80vH1oybfp709h0%2BRzftHA5pKmsDfYR8R4z1jptA6S1JMS%2F0Nhl2Ovvi%2FbzyYqj8qgFzRObbASVzpPoIvWFoosz%2BSvu52tmflyU7DDxOiamPvh6Rwr%2B8a13IICP9qVUyQmM2d5tJUo14FJrWiFmne7PDrny9qEprMIjtkb0GOqUBlB%2BWhaK5aoXCjfG9VKMw6OJPmbW51LvR8JRxDfwCBH80RsBYXnx28DhEIYfzTlyvo1rFksXqbRLCtrXm%2F02NUJhOc6iP%2BFqFPDCuz%2FeOdHtFdB465JQJrsRWkzJWOYtEV40e%2FKWWtImteyEiSjhC%2FgvA3mI%2Bi9K35pYRb3r8qwSmZTKL3GJr5htALMFszyGoKK6Phcj%2BkGq7TBTfE8NvcxX8pHQT&X-Amz-Signature=55c52c0dfbdd81d8cffdda180da4294d9c343f27fcf564803a44f9400cee897a&X-Amz-SignedHeaders=host&x-id=GetObject)


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

