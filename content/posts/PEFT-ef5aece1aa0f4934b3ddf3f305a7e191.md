---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4664TE5DX55%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250209T082659Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDGxOvH7KiOZCGyB1f\
  Tr%2BZPlCbDhLolDNKyfdHPG4PeuAIhAKeoypXIqnha%2BbkGn5ii6cUno8NAK%2B4FyUwjG%2FsK\
  STxwKogECJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igw6VkWh%2BRA\
  Xlns2q00q3APqCYI6Xb86rfpsYySJT%2Foy68C9t2%2Bnev33FaFlGKQ8OTN4UJjJsOHAQWVo894t\
  lDZdFcgxScS2Cvb%2Be4yLJlBmDxIADQjunXGqlMf1qbSMm9OCxEmPXixLqfB5cdxDvVG04Q1GC8S\
  3QzNjrdo1bRMJLQtTmlHcB0riAikBHe8Ra455bjplT6RNkedYcsFtJstOL5gMeN8KyRXkrftOly%2\
  F8HTfB2BBSpxDnbBDmN0wOdPuaphMdyIRE64%2FphXXBEz8R9Goxm2kOSnNHYA0ysSqz56r%2Fmlr\
  B%2B8p46LQe%2FllITLdjO8Yrp6GC1I4iAy0%2FnxXusbbUWrpO9JbYUMmXaV4bul1xfI%2Bd7TEX\
  nRwwa2vh4Qyg9wOIcs%2FOco5WFBsb%2FMsSEW5tvE1nDJDGXnAAO7jSx87AIEzfEEJmZFpvrJXjl\
  EDyoUGwjKVcTf6JbqNfJpHNBVvzqNT%2FRR2wsjFjRsx1nYyRMUjsn%2BdfL7adBLDUBBnnXIj%2F\
  tRrVNDzAn006HNTfZ%2FkPBYyesDEUlvMz%2F2Ms6J7vg9FVS1UP8gZmv%2BPuvdK1v1R9Q2%2FRg\
  MQdSYJs%2FXwYd5qHZsOelV1Vxyhm3QryUjG7WQN34u%2Bo6q%2Bet%2FllTaLHCihQKl06QWpInz\
  DevqC9BjqkAVOhxQ0MZ6YiDoqXY2mxyNCfjv1IpgKXmGIpTYbR%2BbdCGDG8eRsjoO2kkQJnLVkrI\
  F9%2FVx2HgI8j%2FwZbVrCFd%2F5N9mwK82ShlBwtL465Dup7%2FaRmT60OvCjnybYQDY815i6z1A\
  LfxF91TTrp22cAYQKzP2WQ9syZo57e5knKgsglnzZI9CEIihMuNN9zlkCRNXMIMIdiA2eDGtn3xJf\
  Q0PvbDszs&X-Amz-Signature=5653f40fb100aa766b2d1a39093c2d26d4e3dca4597805ec528\
  bac271a74796a&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466QYQGBKTA%2F20250209%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250209T082539Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIQC9Tw1bg99Pgd6v7DVDqBVI%2FGiMLMlgv71LctH%2F8TP2NgIgE06cqfANqsiYYZ9Aou\
        AqL4CgyMab1GZ7j12OABGWkWUqiAQInf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2M\
        zc0MjMxODM4MDUiDIg%2FU%2FP9G0WGJdBqrCrcA1wnOAHdIBze97PMXQDa2B%2BAEC%2FN\
        VnBIjW9COURSVoQa7iyaCcroYy09GBrIIlq9G5N4wWKCEJmZdMPK9H1RSu%2FaiVIp3WU8Y\
        NudfvfYF8jdqaaBjjlVlAfn3h8kkp%2FPuVaSYFRLK9f6iXjWefe6eFm7J3LPt5TUcUFsX5\
        qc0tnq6UfZ86Fvyhll6DpGWoPPY1bAL01YCjK4M6c0STxRGD%2BXbyr%2BvrZIexxQkaOFI\
        kZfyWT36p0hVgLfB0Hb3srD9UJtL9zL1t7HsH8XruB9UqGdEgit3vsUt5n%2BWvQ6LV%2BJ\
        fb9RGya5qxj5Ic1A%2FhZlhW%2BEW1dpW02ewqSPrKzdEgDa5IJWioXe9qWlPrSWQ3mhBsX\
        PHpq6o6t5StaCWEQ5PKpcv7X4cHZnwW2oq3rF6rPk1kCkQOtNN2%2FYc0t7e7jXJeicQZAY\
        eLpEC6bhApSFgVPncsEbnGRfBXjq8oqRcpDDN4yFmbPTavsgWGeQ3tlNG0D8kDOS7jXpiIY\
        nZUuBQSMmzs8yJxBwFYCU%2BY%2BtZT3TeHTgRA%2BV6I5Mag9%2Bo22zqEfVmPQHJxiaDe\
        IoHO1QTrz0EmHRXvYceGmc2rpyu9tiC2x%2BWQnn1EsPQLg3KLByqgi6IE59dV3t5z3cMPS\
        %2BoL0GOqUB1gepuKu3DqdQS3tDm%2FgN5CwgiRr2zBeDixjHrUmGFz8erDR1wzoBRs6HH4\
        XHyb7t6Z%2Bcl8pdYZwS44y1cKwoDmWO8lG%2FMWP79HwxHtUTJhtLwKQI8UHOZyu1yDkb1\
        ybZg%2F%2FdpvyAvBgGz1b59bw83FP60MTpgYk%2Fwo%2FkxlJxnyZBddCPMfJNhq8rOSqC\
        687w3IH1sSMHRQdTsKbzR6lmFXVfhEnG&X-Amz-Signature=aaf4bc5095f4d4149cbb9e\
        ec01c5e0c5cf7f50bc3e3bc9aa136c507afe4413a8&X-Amz-SignedHeaders=host&x-i\
        d=GetObject"
      expiry_time: "2025-02-09T09:25:39.878Z"
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
UPDATE_TIME: "2025-02-09T08:27:07.374Z"
EXPIRY_TIME: "2025-02-09T09:26:49.968Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665JWB7VU4%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T082650Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCtt1OZWuliJt3MRsVN3XBuumUhyZOgNtn1hY21zaQJFAIhAPbwCeifFvRNB85tALUQyQ49s5iIknStKuN%2Fh7tCw4%2FBKogECJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzT6Nc5D4WMKxiUMLsq3APE8rTjyRwxLMVy%2BjeV7jpPukD%2FvzgqNBfUweg61zQVX6teKnRUTIDKcjIumj0TzACa6jTXaeega1YWcuE02ZVohmY9kck2YoW5rudGrBoBPSbKZTFm3OwRwztW%2FxdQLIAakI1rvc%2Fa%2FdoDykT1YiW80bS3%2B3u0ZPC585YLiDhVB7%2BSQGxscMJ09taIu7q4PbOq1MtUzAa79ADsp2EVSKd5MXDgYjLrdIAzgfun106l2fTUAfGHiSBk1YAav6bnUUnQrCZinzIHNgx6k7PsCf8SHhirRz41sNPIQ6ik6zcfz0RgKDCx%2BqBxlYoncB1Qsq7WQyvOs518bfc%2FuRMwLkwgv22mWxGg6rPqkoK1vH5kOETMaP9bUh18r%2BJhk3mL5zV0NDefNi145paicmd%2ByQPVNRjhaZ%2Ftex8sSwHGR6Xl0XCQwjT6%2BklZs%2BVuDnwrMU%2Fy0J2IRgVfkixQkFMkkDc2oIB1BFSNsGPSfZdPb%2F6EonxflIpaSsPjn7SQ0YWFVxy%2BVXkoren5vV%2FJo8YlhU3bRWVE2kNNFXOk8ZN%2B35He9sZ19xpU%2BqfyPzv4fJ%2BsOxZ6Zd9tkvTTZzqgOFw0%2FHBWpA0b0ZhlUwKe7JBQrTpbKQnneH0lrgWhH55mqDCgv6C9BjqkAcgXM0UH922APg283d3YzSbrsLUplFfmyIlcne7b4S5lLCX6Mv5wJ2rdQJhEj%2FXfErniawg6L3QmXFy6mduzQlSJwCm3qHTG8PnP64329tabZCpp9cvU1Z7g19y1gJY97uTIkJn5V2Lp0s%2FLpjchpH%2FQz1i%2Bm%2FzFEeXZr6SEOhzbighNXeFwUQX0N%2B8YN79iwCrAYBWbot13e8vdGW8pKEZUWQqP&X-Amz-Signature=9c33266e699e137f5540d0e2509051eed0ef0d54b27a3f161d81c964526687b9&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665JWB7VU4%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T082650Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCtt1OZWuliJt3MRsVN3XBuumUhyZOgNtn1hY21zaQJFAIhAPbwCeifFvRNB85tALUQyQ49s5iIknStKuN%2Fh7tCw4%2FBKogECJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzT6Nc5D4WMKxiUMLsq3APE8rTjyRwxLMVy%2BjeV7jpPukD%2FvzgqNBfUweg61zQVX6teKnRUTIDKcjIumj0TzACa6jTXaeega1YWcuE02ZVohmY9kck2YoW5rudGrBoBPSbKZTFm3OwRwztW%2FxdQLIAakI1rvc%2Fa%2FdoDykT1YiW80bS3%2B3u0ZPC585YLiDhVB7%2BSQGxscMJ09taIu7q4PbOq1MtUzAa79ADsp2EVSKd5MXDgYjLrdIAzgfun106l2fTUAfGHiSBk1YAav6bnUUnQrCZinzIHNgx6k7PsCf8SHhirRz41sNPIQ6ik6zcfz0RgKDCx%2BqBxlYoncB1Qsq7WQyvOs518bfc%2FuRMwLkwgv22mWxGg6rPqkoK1vH5kOETMaP9bUh18r%2BJhk3mL5zV0NDefNi145paicmd%2ByQPVNRjhaZ%2Ftex8sSwHGR6Xl0XCQwjT6%2BklZs%2BVuDnwrMU%2Fy0J2IRgVfkixQkFMkkDc2oIB1BFSNsGPSfZdPb%2F6EonxflIpaSsPjn7SQ0YWFVxy%2BVXkoren5vV%2FJo8YlhU3bRWVE2kNNFXOk8ZN%2B35He9sZ19xpU%2BqfyPzv4fJ%2BsOxZ6Zd9tkvTTZzqgOFw0%2FHBWpA0b0ZhlUwKe7JBQrTpbKQnneH0lrgWhH55mqDCgv6C9BjqkAcgXM0UH922APg283d3YzSbrsLUplFfmyIlcne7b4S5lLCX6Mv5wJ2rdQJhEj%2FXfErniawg6L3QmXFy6mduzQlSJwCm3qHTG8PnP64329tabZCpp9cvU1Z7g19y1gJY97uTIkJn5V2Lp0s%2FLpjchpH%2FQz1i%2Bm%2FzFEeXZr6SEOhzbighNXeFwUQX0N%2B8YN79iwCrAYBWbot13e8vdGW8pKEZUWQqP&X-Amz-Signature=1d58bae41c6f9eddd633b1e36f70ecb28fbcd383ee2bfb9ce8c93319b443e50a&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665JWB7VU4%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T082650Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCtt1OZWuliJt3MRsVN3XBuumUhyZOgNtn1hY21zaQJFAIhAPbwCeifFvRNB85tALUQyQ49s5iIknStKuN%2Fh7tCw4%2FBKogECJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzT6Nc5D4WMKxiUMLsq3APE8rTjyRwxLMVy%2BjeV7jpPukD%2FvzgqNBfUweg61zQVX6teKnRUTIDKcjIumj0TzACa6jTXaeega1YWcuE02ZVohmY9kck2YoW5rudGrBoBPSbKZTFm3OwRwztW%2FxdQLIAakI1rvc%2Fa%2FdoDykT1YiW80bS3%2B3u0ZPC585YLiDhVB7%2BSQGxscMJ09taIu7q4PbOq1MtUzAa79ADsp2EVSKd5MXDgYjLrdIAzgfun106l2fTUAfGHiSBk1YAav6bnUUnQrCZinzIHNgx6k7PsCf8SHhirRz41sNPIQ6ik6zcfz0RgKDCx%2BqBxlYoncB1Qsq7WQyvOs518bfc%2FuRMwLkwgv22mWxGg6rPqkoK1vH5kOETMaP9bUh18r%2BJhk3mL5zV0NDefNi145paicmd%2ByQPVNRjhaZ%2Ftex8sSwHGR6Xl0XCQwjT6%2BklZs%2BVuDnwrMU%2Fy0J2IRgVfkixQkFMkkDc2oIB1BFSNsGPSfZdPb%2F6EonxflIpaSsPjn7SQ0YWFVxy%2BVXkoren5vV%2FJo8YlhU3bRWVE2kNNFXOk8ZN%2B35He9sZ19xpU%2BqfyPzv4fJ%2BsOxZ6Zd9tkvTTZzqgOFw0%2FHBWpA0b0ZhlUwKe7JBQrTpbKQnneH0lrgWhH55mqDCgv6C9BjqkAcgXM0UH922APg283d3YzSbrsLUplFfmyIlcne7b4S5lLCX6Mv5wJ2rdQJhEj%2FXfErniawg6L3QmXFy6mduzQlSJwCm3qHTG8PnP64329tabZCpp9cvU1Z7g19y1gJY97uTIkJn5V2Lp0s%2FLpjchpH%2FQz1i%2Bm%2FzFEeXZr6SEOhzbighNXeFwUQX0N%2B8YN79iwCrAYBWbot13e8vdGW8pKEZUWQqP&X-Amz-Signature=52eb0ccfe919b9815e02d0fc1380029ea26b26d3ffe3c2ecdd822a7643e39f7d&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665JWB7VU4%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T082650Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCtt1OZWuliJt3MRsVN3XBuumUhyZOgNtn1hY21zaQJFAIhAPbwCeifFvRNB85tALUQyQ49s5iIknStKuN%2Fh7tCw4%2FBKogECJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzT6Nc5D4WMKxiUMLsq3APE8rTjyRwxLMVy%2BjeV7jpPukD%2FvzgqNBfUweg61zQVX6teKnRUTIDKcjIumj0TzACa6jTXaeega1YWcuE02ZVohmY9kck2YoW5rudGrBoBPSbKZTFm3OwRwztW%2FxdQLIAakI1rvc%2Fa%2FdoDykT1YiW80bS3%2B3u0ZPC585YLiDhVB7%2BSQGxscMJ09taIu7q4PbOq1MtUzAa79ADsp2EVSKd5MXDgYjLrdIAzgfun106l2fTUAfGHiSBk1YAav6bnUUnQrCZinzIHNgx6k7PsCf8SHhirRz41sNPIQ6ik6zcfz0RgKDCx%2BqBxlYoncB1Qsq7WQyvOs518bfc%2FuRMwLkwgv22mWxGg6rPqkoK1vH5kOETMaP9bUh18r%2BJhk3mL5zV0NDefNi145paicmd%2ByQPVNRjhaZ%2Ftex8sSwHGR6Xl0XCQwjT6%2BklZs%2BVuDnwrMU%2Fy0J2IRgVfkixQkFMkkDc2oIB1BFSNsGPSfZdPb%2F6EonxflIpaSsPjn7SQ0YWFVxy%2BVXkoren5vV%2FJo8YlhU3bRWVE2kNNFXOk8ZN%2B35He9sZ19xpU%2BqfyPzv4fJ%2BsOxZ6Zd9tkvTTZzqgOFw0%2FHBWpA0b0ZhlUwKe7JBQrTpbKQnneH0lrgWhH55mqDCgv6C9BjqkAcgXM0UH922APg283d3YzSbrsLUplFfmyIlcne7b4S5lLCX6Mv5wJ2rdQJhEj%2FXfErniawg6L3QmXFy6mduzQlSJwCm3qHTG8PnP64329tabZCpp9cvU1Z7g19y1gJY97uTIkJn5V2Lp0s%2FLpjchpH%2FQz1i%2Bm%2FzFEeXZr6SEOhzbighNXeFwUQX0N%2B8YN79iwCrAYBWbot13e8vdGW8pKEZUWQqP&X-Amz-Signature=eb06df39c6275bb2a6680041d211743987bc76c6e8209b43e731a40159da3085&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665JWB7VU4%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T082650Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCtt1OZWuliJt3MRsVN3XBuumUhyZOgNtn1hY21zaQJFAIhAPbwCeifFvRNB85tALUQyQ49s5iIknStKuN%2Fh7tCw4%2FBKogECJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzT6Nc5D4WMKxiUMLsq3APE8rTjyRwxLMVy%2BjeV7jpPukD%2FvzgqNBfUweg61zQVX6teKnRUTIDKcjIumj0TzACa6jTXaeega1YWcuE02ZVohmY9kck2YoW5rudGrBoBPSbKZTFm3OwRwztW%2FxdQLIAakI1rvc%2Fa%2FdoDykT1YiW80bS3%2B3u0ZPC585YLiDhVB7%2BSQGxscMJ09taIu7q4PbOq1MtUzAa79ADsp2EVSKd5MXDgYjLrdIAzgfun106l2fTUAfGHiSBk1YAav6bnUUnQrCZinzIHNgx6k7PsCf8SHhirRz41sNPIQ6ik6zcfz0RgKDCx%2BqBxlYoncB1Qsq7WQyvOs518bfc%2FuRMwLkwgv22mWxGg6rPqkoK1vH5kOETMaP9bUh18r%2BJhk3mL5zV0NDefNi145paicmd%2ByQPVNRjhaZ%2Ftex8sSwHGR6Xl0XCQwjT6%2BklZs%2BVuDnwrMU%2Fy0J2IRgVfkixQkFMkkDc2oIB1BFSNsGPSfZdPb%2F6EonxflIpaSsPjn7SQ0YWFVxy%2BVXkoren5vV%2FJo8YlhU3bRWVE2kNNFXOk8ZN%2B35He9sZ19xpU%2BqfyPzv4fJ%2BsOxZ6Zd9tkvTTZzqgOFw0%2FHBWpA0b0ZhlUwKe7JBQrTpbKQnneH0lrgWhH55mqDCgv6C9BjqkAcgXM0UH922APg283d3YzSbrsLUplFfmyIlcne7b4S5lLCX6Mv5wJ2rdQJhEj%2FXfErniawg6L3QmXFy6mduzQlSJwCm3qHTG8PnP64329tabZCpp9cvU1Z7g19y1gJY97uTIkJn5V2Lp0s%2FLpjchpH%2FQz1i%2Bm%2FzFEeXZr6SEOhzbighNXeFwUQX0N%2B8YN79iwCrAYBWbot13e8vdGW8pKEZUWQqP&X-Amz-Signature=332b7b4f015da1235b68b0a2289a5871fad19bb90a02a8fa6c2241213b0ecad1&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UHQMDRFZ%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T082652Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIEGvj6uPj6Fj3TYKlWw3lfDS%2F%2BZu2yxvjjoa9pxCke2JAiEAzMhLBpLggBnHnkfuDwyEQO0Nz2cILre8hPOYrqgdndoqiAQInP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDIhtKwHwYBsflQCYtircA9Z5gTC5CDyXokgcTVN37Es5LrG9Zw83ntA9ll31mQo9RPpjmrX%2Fl1eqO9eZ%2Byd2dkQNZcuJRiANwvJqBFBHtnyw0Mr0qDkzD1vQzGhTiJvR8y%2B%2FqjR9EXqfW08rSeLFwbNjmITe1PhHirvPPa1cptA3oLw6R%2BneL08MpEBfdZVPPZHzSFn5WtYpcMZU0PDfReUoYsQjoyMe0vkKbCp6BtbV%2BG72gRtT%2B4yN11H5NQq0ko9mzDsnO7Oa%2BIMOf48pWqYbPUNIucOWx6oaF8CRUUxHgDBQeUV6LlAVOr%2FgnuaQPvgOgxD3Kn8KehhqCbJm%2Fk9BzD8903DIC%2BFSxO4ZwO0JVKLHTFPyQigd38FVndyjRqajH849MO9syxfZv03YM6dmLCUpcfe1jePTJuw4%2Bz89bjh8aOwUKdo%2FpS7ECT0yOSVUZMuvf1RNAuRn8TZg2pSqpzRhtCmWutiE%2FOAH8jipXlhQoASWSADQkCFMHBI3LRuydOcGqLdd7WQflk%2BDh7m0Ur4%2FlBingkyDX10al9z8EBpznT9a506DDUUqrftYVA7191Ewbr3JItLudydfZVN04JlVr5QvSXPC%2FCmuz4Z1ZwiHZxMWQJrIhpf%2FILAqCZ6o3uXBRNcHRkmRMMe%2FoL0GOqUBSFfLG6lUkhROzw%2BpZjQz7bFH3FPmS09FAX2Qsx8CPNEepieqFac%2Fu1wHYORywlAD8TJcyEVVpPLyBFbPxDpoNMw2ty0NiDz3GqufoGFWd6Tb5qZikGPJ2WBXnhTrfNKLbSg2hoCeC3NDb%2BMLS2gtHgS3n3ztRyE%2FoAySJFLYSKdiAV%2B4wxKtoNKH3f62%2FZgliFv8aFk8W551JQNWBM%2BqLyB0jCyy&X-Amz-Signature=c62fa68243a7a260adfe2ce76f610b1b209415b43c0499d72f9ed5373906d749&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665F7CEGM6%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T082659Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD8YYfNCRnaMhnFSaZSbwcTU6cmCAe6Z%2Bj7wBRLaYtBzgIhAO9jPXE8BFyMG2KOAjc7pTzhDupG86B7O1xwhiXwch3iKogECJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igw8zR4W3yMaGf7O7IIq3AOLmGV2AogcMy947Hf6rSsArNUmX12vcULIXgZCBqm6KuHVH9ot%2B5dOSy5WRPfCn0LaepIBBJyblFfGpTd9j3IcxX0gN0GTnPhfqt0bOIJ7eHhjvCNezvkCsPQhEtr4onxTSjDhgphr9lEFtwvGAfYpdPjxqTByAu0ZE2q6a5QODvcBWAl8mlA8whcxltXOM8ffW51Cw97hVyW14q106lQww5s7OmR7d%2BumxW4kJ9HNQlxQW6xkOkIU6r7WX3SoO%2FMnmigokd3LmppT4EeFpzDWbWAbQZIIDMzvPn2EloATddDXNZ7mfRq6obBCbCIpEyD0OkP1MfsMLLxGiyBMTmNkLYLH9iwTOHvMozzapviP3HXPRbhozQHhYzxtkkvnZOtnLYoAs7jlXErmb3yWf7OxkIxzDuojcFKQxObj2%2BrcGe%2BMEA4%2Ba3b2ZTOP39xKNerHubD3c76o5ipPzU5Nh89TIMYym2xC4BxY2HWaOmzneXGJESNCRYh9gkM6yd8NX5T4QptOdDlOUXxtsCdBXXqAMNslcXGaPvyWjZ9Ip1wJo6KdqHacgis%2FKXczWEAujPv9IJtcnfpNEh7pY5ZeFp1MyWDXTxC9soyX%2F5vFULLxFwHryKChxPcW5ipfSjC%2Bv6C9BjqkAU6Zg4JLzXMUPdr97PwRMzHNYoAKn2flS4eknzCcWZ3armYacjOTGkNJwdLz7RtF6bbBb4p%2F7ndJJSY7m22dXlxOfFexgqGZfEWpGyUbZF%2FQE7ad0y4hky6AoODKT5kwA%2BNUgwnR31Fg%2FNcDJIxJXQCoJ2mU5FleCHjL7ajSSvJpkX0i8Za3QyjETkGZMieqZKtRhm1X7Nj5LmpgEm11DHg9QbLh&X-Amz-Signature=e634efa75649dcf458aba1f78c11c5800597f35f45463823c77c1b0062c5281f&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665JWB7VU4%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T082650Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCtt1OZWuliJt3MRsVN3XBuumUhyZOgNtn1hY21zaQJFAIhAPbwCeifFvRNB85tALUQyQ49s5iIknStKuN%2Fh7tCw4%2FBKogECJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzT6Nc5D4WMKxiUMLsq3APE8rTjyRwxLMVy%2BjeV7jpPukD%2FvzgqNBfUweg61zQVX6teKnRUTIDKcjIumj0TzACa6jTXaeega1YWcuE02ZVohmY9kck2YoW5rudGrBoBPSbKZTFm3OwRwztW%2FxdQLIAakI1rvc%2Fa%2FdoDykT1YiW80bS3%2B3u0ZPC585YLiDhVB7%2BSQGxscMJ09taIu7q4PbOq1MtUzAa79ADsp2EVSKd5MXDgYjLrdIAzgfun106l2fTUAfGHiSBk1YAav6bnUUnQrCZinzIHNgx6k7PsCf8SHhirRz41sNPIQ6ik6zcfz0RgKDCx%2BqBxlYoncB1Qsq7WQyvOs518bfc%2FuRMwLkwgv22mWxGg6rPqkoK1vH5kOETMaP9bUh18r%2BJhk3mL5zV0NDefNi145paicmd%2ByQPVNRjhaZ%2Ftex8sSwHGR6Xl0XCQwjT6%2BklZs%2BVuDnwrMU%2Fy0J2IRgVfkixQkFMkkDc2oIB1BFSNsGPSfZdPb%2F6EonxflIpaSsPjn7SQ0YWFVxy%2BVXkoren5vV%2FJo8YlhU3bRWVE2kNNFXOk8ZN%2B35He9sZ19xpU%2BqfyPzv4fJ%2BsOxZ6Zd9tkvTTZzqgOFw0%2FHBWpA0b0ZhlUwKe7JBQrTpbKQnneH0lrgWhH55mqDCgv6C9BjqkAcgXM0UH922APg283d3YzSbrsLUplFfmyIlcne7b4S5lLCX6Mv5wJ2rdQJhEj%2FXfErniawg6L3QmXFy6mduzQlSJwCm3qHTG8PnP64329tabZCpp9cvU1Z7g19y1gJY97uTIkJn5V2Lp0s%2FLpjchpH%2FQz1i%2Bm%2FzFEeXZr6SEOhzbighNXeFwUQX0N%2B8YN79iwCrAYBWbot13e8vdGW8pKEZUWQqP&X-Amz-Signature=a85fca371d91367033d46da27fd48feec57e0e4028b00512332d52f2da495cec&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665JWB7VU4%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T082650Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCtt1OZWuliJt3MRsVN3XBuumUhyZOgNtn1hY21zaQJFAIhAPbwCeifFvRNB85tALUQyQ49s5iIknStKuN%2Fh7tCw4%2FBKogECJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzT6Nc5D4WMKxiUMLsq3APE8rTjyRwxLMVy%2BjeV7jpPukD%2FvzgqNBfUweg61zQVX6teKnRUTIDKcjIumj0TzACa6jTXaeega1YWcuE02ZVohmY9kck2YoW5rudGrBoBPSbKZTFm3OwRwztW%2FxdQLIAakI1rvc%2Fa%2FdoDykT1YiW80bS3%2B3u0ZPC585YLiDhVB7%2BSQGxscMJ09taIu7q4PbOq1MtUzAa79ADsp2EVSKd5MXDgYjLrdIAzgfun106l2fTUAfGHiSBk1YAav6bnUUnQrCZinzIHNgx6k7PsCf8SHhirRz41sNPIQ6ik6zcfz0RgKDCx%2BqBxlYoncB1Qsq7WQyvOs518bfc%2FuRMwLkwgv22mWxGg6rPqkoK1vH5kOETMaP9bUh18r%2BJhk3mL5zV0NDefNi145paicmd%2ByQPVNRjhaZ%2Ftex8sSwHGR6Xl0XCQwjT6%2BklZs%2BVuDnwrMU%2Fy0J2IRgVfkixQkFMkkDc2oIB1BFSNsGPSfZdPb%2F6EonxflIpaSsPjn7SQ0YWFVxy%2BVXkoren5vV%2FJo8YlhU3bRWVE2kNNFXOk8ZN%2B35He9sZ19xpU%2BqfyPzv4fJ%2BsOxZ6Zd9tkvTTZzqgOFw0%2FHBWpA0b0ZhlUwKe7JBQrTpbKQnneH0lrgWhH55mqDCgv6C9BjqkAcgXM0UH922APg283d3YzSbrsLUplFfmyIlcne7b4S5lLCX6Mv5wJ2rdQJhEj%2FXfErniawg6L3QmXFy6mduzQlSJwCm3qHTG8PnP64329tabZCpp9cvU1Z7g19y1gJY97uTIkJn5V2Lp0s%2FLpjchpH%2FQz1i%2Bm%2FzFEeXZr6SEOhzbighNXeFwUQX0N%2B8YN79iwCrAYBWbot13e8vdGW8pKEZUWQqP&X-Amz-Signature=d888a355ab6a970dd45d226e087d26cfb53a6b6a596f7aef6573d94ddff92fe5&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665JWB7VU4%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T082650Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCtt1OZWuliJt3MRsVN3XBuumUhyZOgNtn1hY21zaQJFAIhAPbwCeifFvRNB85tALUQyQ49s5iIknStKuN%2Fh7tCw4%2FBKogECJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzT6Nc5D4WMKxiUMLsq3APE8rTjyRwxLMVy%2BjeV7jpPukD%2FvzgqNBfUweg61zQVX6teKnRUTIDKcjIumj0TzACa6jTXaeega1YWcuE02ZVohmY9kck2YoW5rudGrBoBPSbKZTFm3OwRwztW%2FxdQLIAakI1rvc%2Fa%2FdoDykT1YiW80bS3%2B3u0ZPC585YLiDhVB7%2BSQGxscMJ09taIu7q4PbOq1MtUzAa79ADsp2EVSKd5MXDgYjLrdIAzgfun106l2fTUAfGHiSBk1YAav6bnUUnQrCZinzIHNgx6k7PsCf8SHhirRz41sNPIQ6ik6zcfz0RgKDCx%2BqBxlYoncB1Qsq7WQyvOs518bfc%2FuRMwLkwgv22mWxGg6rPqkoK1vH5kOETMaP9bUh18r%2BJhk3mL5zV0NDefNi145paicmd%2ByQPVNRjhaZ%2Ftex8sSwHGR6Xl0XCQwjT6%2BklZs%2BVuDnwrMU%2Fy0J2IRgVfkixQkFMkkDc2oIB1BFSNsGPSfZdPb%2F6EonxflIpaSsPjn7SQ0YWFVxy%2BVXkoren5vV%2FJo8YlhU3bRWVE2kNNFXOk8ZN%2B35He9sZ19xpU%2BqfyPzv4fJ%2BsOxZ6Zd9tkvTTZzqgOFw0%2FHBWpA0b0ZhlUwKe7JBQrTpbKQnneH0lrgWhH55mqDCgv6C9BjqkAcgXM0UH922APg283d3YzSbrsLUplFfmyIlcne7b4S5lLCX6Mv5wJ2rdQJhEj%2FXfErniawg6L3QmXFy6mduzQlSJwCm3qHTG8PnP64329tabZCpp9cvU1Z7g19y1gJY97uTIkJn5V2Lp0s%2FLpjchpH%2FQz1i%2Bm%2FzFEeXZr6SEOhzbighNXeFwUQX0N%2B8YN79iwCrAYBWbot13e8vdGW8pKEZUWQqP&X-Amz-Signature=89d9655503e22001d963cd9d5e41fa8a0a309143e286dc21e918d1975bb8400b&X-Amz-SignedHeaders=host&x-id=GetObject)


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

