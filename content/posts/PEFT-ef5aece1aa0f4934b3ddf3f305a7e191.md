---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4664EZ2GCMG%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250130T042644Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDfD%2FbcX%2BPFr1x\
  2VWdZe0EuGcRatNTmU5ZG0JJxtqMEmwIgUb9LGYV3KEArPBkx60jVrPQM6HZ%2Fr%2FzPZwgWEj9B\
  8E4qiAQInf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDD1RWKrYYeOfP\
  AQTxSrcA29uvdHkx1lQxzAbm034Rj%2F%2FqahJ7BWSPnCkk%2BjWAYa5aWZT%2FsFB4K%2BavA9X\
  m6oiIXqQsHBEUKUgqvNKJM9xPvy%2BJIjSfvojJQpp2J9VvLnDwhfihzkFZaxmOdr5SMn0pHEk3BB\
  LM2PUasYPumPp3IPtOUA6nW%2FxJutfLqu4Dc8DcdCtPCiX%2FJbRb04aRVHmGE9u2BKjisGqxYFN\
  QANxaFpFIeu9g9zvCvStvVO38lcuW7Ss53GP%2F%2FSQ%2FoZahbvGC66u74Y4hLJszoO6YMbCkB8\
  Yhs%2Fls8RbuWqUC2J6VBkhe3%2BmCsVz5duK9EHD%2FhlU%2BD7p%2B2LPQUcDFjsSvP1xc4zCGi\
  JKIvxjhiO1f0S1Mn8Xwie%2FJBYeBWiuLdKSsL%2Bh1gPN3ps2dzwxaAjNb3WUdEmUUCS2opG05EN\
  QQVgHXuZG%2FhOEBd6RspN%2FfsVEzVBkU9KumzWJzvJiixrPxr33unfupzDjpCQ%2FfiMZDMs%2F\
  vtGKFCOatXfk5YFhmAx6yqf3No4RQWfy5u07MQdzYR8cCiOIaQYBfiM%2Bf%2B%2Bhu59JvKQm4ab\
  fu4Z11hnnkAkS3eifUcrJFU6jqEdzTUgPxWOt41LohzY6zlxJOJynJNkMoTEfw2RcFtn9Gr7hA%2B\
  diMO7r67wGOqUBd0cX%2BkmHSqlokJis32RMkx0lH%2BQQLkqQjRXUFYix4Nf426CuVlH1BwLFV3R\
  CIhqQpqSCcX7a5UPZb6nFusCyPr8gZafJ3L830vTTjTvcxIjaDE71XfPDzx%2FkMDjPYEbk1vErs%\
  2F7SZcr%2FLVJ%2Fa9riKX7mhHRcVusoduodCnCTiWhbqKsmLV96%2FTiSAjWGog6hI%2BakpMAJI\
  iIzq%2BBX4G6nVRcbfdha&X-Amz-Signature=a32d024ae6233e8bdea437cd160c064fa56d365\
  9f2237ca641a7773dafda2fb0&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4664QZRJCEE%2F20250130%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250130T042543Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIGQ05bXhI%2B4c5BeqXjmsRe%2BfllfBZjgL%2BI4Wa47Nh37UAiEAkYenoiAyZTQfr9qT\
        hnQn4IhfuRHJkvMchklgddn7f2wqiAQInf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw\
        2Mzc0MjMxODM4MDUiDEhouZzlFOp%2B9uwXtCrcA7eMo5R2Y6ovNklxP3SVNUWZrT7kVZ5G\
        kzWOOeiYgtMqe8H%2FxXfrlUd3UKf1imUJIy52SUNISlzL%2FuKCAWDLSrPZHukD1j7Yqv7\
        2oT2yNf41Uempql27RtzHxOsRjjRcFxAV3Eegj2ETnLCk7el5MWUIdHkLn8yM4A%2F9rx9F\
        m5Y52PsXbUc7Kvt8RmEFLg0CRbtHJkE93BEvvPxTZmbqhTYDcqbpEAMFPzAsRS0KjYjG76Z\
        Djbbx6QE2wF%2FEm8Wg%2BWRliik%2BjNUANpPDYFQXkJnzNgJlSmflCt69V0J98pAxyhbp\
        1iWzUN9rZJ3oPeVm0MoiAh38%2FjRvaT1lrZSiFsy%2FwjZoJx6eyWB51NSfAzB1Xq4POrO\
        iXnMpXaOPkpuCj7I%2BpxZW8Fhpt9pDllshvNQfC9w9XnXPPZOulCy7UeuR8CaVyyD5QJPA\
        bHvU7mx13BSPIwx4j6F55WIKpBirR99m0CnYsfXe89v%2FghmhJiXsyaopth90Rg2Pyn0vd\
        HcyzajKGyuOLyKe0nTSG3WR%2Bh6trN6aZ27bIqWB9twzxnDE4pQMamgxggKeoL65TvHDmq\
        QQTafRdLHR9KjtIbqj1sH0GgVLeV4eQhqkyx0mP3ztJimMZ%2BqNUENz%2Bz37MMDr67wGO\
        qUBSWeROOoXeHbBK5Bh1hdl8Y%2F3Zy%2FeQ1wA%2Fw0To5mhK%2BDT%2F9qZC3fFuyoUqr\
        mKDttxX69Yer%2FjPBIHOyi%2BsYa6yfXgq%2BHW8%2BTO%2Ba3mP7Y0IV3z2EC18YxF6St\
        lUma2QcFj5LPoOnVHW7fqR%2Fd0M7cAzJrWpoNlnSW4Cf%2FYb7bB20EUV1JLF00nqPDMTh\
        FycTeOXYQb3kTDdnbJPpcIEIrFCIIkBGqB&X-Amz-Signature=26d8f6b85f7b3d2d9bea\
        67c8c17561e408849adb731e49d36606671adf73d520&X-Amz-SignedHeaders=host&x\
        -id=GetObject"
      expiry_time: "2025-01-30T05:25:42.866Z"
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
UPDATE_TIME: "2025-01-30T04:26:54.688Z"
EXPIRY_TIME: "2025-01-30T05:26:42.487Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VUI45LPU%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T042642Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIE925QSVLgTEpe6u1Um1lCmjgysdbp44BficWLiov0pTAiAfh1H5ExAuP087X8wTFUko5Adbl9PpOFZGv2F3i1aRWyqIBAid%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMZ5hk7w55svCVqjWpKtwDsxehpt7Kp5Zw8MY0M20zaBA68ZjhHILSX%2FtyjATrElk%2BGm7kWN5S715KSSABIM8Yb3Y97KGeA8kh1DrHtM%2B5QR9BISmc%2BjqArfusS2ty6H5jttujN7afIiS%2FfMoCxOzwghUm0Br7V5trkWb4ECZyHWvPjlD5SrPSaVoSpmDoxEA7z8HCyjDJxU9OgRw6XsFu8xJ0fChutdIPwkWI1AezCEq5uPiZrxKg5Ba8HE6M791A7JRXOGaj4cTDfZLKKh8paLi%2F1q6ZyFhbMXtxlTnDPO0H51%2B9W%2FfTsHt%2FFBbAxqLquhp3UfZQbCVv3t8MgpvzqGMI3cEcuCj3FoPFOJJxWMy6kAN6RiEUiUuBtY6NMppb0Rdc0XcVJUu2%2B5B1OtdrB9EHpKFs0VGkPhGjy%2Fgp8pREdwOnwoqjBZu5%2BjZwdmzp80NZoqYxDHovRsM90FzNfIv25HudmIt4YQdx02yrw8WrpPYough2IkJJHYMxD6b%2FQZWbwFtt9gNu%2FWxuaC3CUithkZWlCg0MCQD3A6sqBgkNBnHSZsNB0CEGPunqF3jTFJ5AUHUTxp%2FV2Wviy3pfqAftoSozPUpuIOHpbpjX1y5%2BJXOCVazt4Hn8gPmu42Pvg6ua1Q%2FH%2BhM%2Bo2Ew5uvrvAY6pgEHS5HFnprQdBTtvP0bSeqli5v4DgJHpXhtAbTX7UQS3GfiOly8A44B9vRvSmIt0c7T1juL6eJpPb7rjFMLBPRcVr4eZt%2F94RS6aCM7dYLJOFKA5MgEPLQ1InS5JFHN5zziASIY8icqz%2BFpokIgb6TURqwDvdoZ%2FDoIwThmZOnvz%2FrKUxohxCHb7XQiWGAgdRlNWNsfRtkCJQ6qNgQ4k3X9qj8%2BRIMr&X-Amz-Signature=7295146797959282a28eddca3b23329d8ef734c1da4467f3a636a3295b957f28&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VUI45LPU%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T042642Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIE925QSVLgTEpe6u1Um1lCmjgysdbp44BficWLiov0pTAiAfh1H5ExAuP087X8wTFUko5Adbl9PpOFZGv2F3i1aRWyqIBAid%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMZ5hk7w55svCVqjWpKtwDsxehpt7Kp5Zw8MY0M20zaBA68ZjhHILSX%2FtyjATrElk%2BGm7kWN5S715KSSABIM8Yb3Y97KGeA8kh1DrHtM%2B5QR9BISmc%2BjqArfusS2ty6H5jttujN7afIiS%2FfMoCxOzwghUm0Br7V5trkWb4ECZyHWvPjlD5SrPSaVoSpmDoxEA7z8HCyjDJxU9OgRw6XsFu8xJ0fChutdIPwkWI1AezCEq5uPiZrxKg5Ba8HE6M791A7JRXOGaj4cTDfZLKKh8paLi%2F1q6ZyFhbMXtxlTnDPO0H51%2B9W%2FfTsHt%2FFBbAxqLquhp3UfZQbCVv3t8MgpvzqGMI3cEcuCj3FoPFOJJxWMy6kAN6RiEUiUuBtY6NMppb0Rdc0XcVJUu2%2B5B1OtdrB9EHpKFs0VGkPhGjy%2Fgp8pREdwOnwoqjBZu5%2BjZwdmzp80NZoqYxDHovRsM90FzNfIv25HudmIt4YQdx02yrw8WrpPYough2IkJJHYMxD6b%2FQZWbwFtt9gNu%2FWxuaC3CUithkZWlCg0MCQD3A6sqBgkNBnHSZsNB0CEGPunqF3jTFJ5AUHUTxp%2FV2Wviy3pfqAftoSozPUpuIOHpbpjX1y5%2BJXOCVazt4Hn8gPmu42Pvg6ua1Q%2FH%2BhM%2Bo2Ew5uvrvAY6pgEHS5HFnprQdBTtvP0bSeqli5v4DgJHpXhtAbTX7UQS3GfiOly8A44B9vRvSmIt0c7T1juL6eJpPb7rjFMLBPRcVr4eZt%2F94RS6aCM7dYLJOFKA5MgEPLQ1InS5JFHN5zziASIY8icqz%2BFpokIgb6TURqwDvdoZ%2FDoIwThmZOnvz%2FrKUxohxCHb7XQiWGAgdRlNWNsfRtkCJQ6qNgQ4k3X9qj8%2BRIMr&X-Amz-Signature=ff1ddd4b42342daebfbb7596ca02f5e527f970f9a18dae996e118dede67773f3&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VUI45LPU%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T042642Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIE925QSVLgTEpe6u1Um1lCmjgysdbp44BficWLiov0pTAiAfh1H5ExAuP087X8wTFUko5Adbl9PpOFZGv2F3i1aRWyqIBAid%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMZ5hk7w55svCVqjWpKtwDsxehpt7Kp5Zw8MY0M20zaBA68ZjhHILSX%2FtyjATrElk%2BGm7kWN5S715KSSABIM8Yb3Y97KGeA8kh1DrHtM%2B5QR9BISmc%2BjqArfusS2ty6H5jttujN7afIiS%2FfMoCxOzwghUm0Br7V5trkWb4ECZyHWvPjlD5SrPSaVoSpmDoxEA7z8HCyjDJxU9OgRw6XsFu8xJ0fChutdIPwkWI1AezCEq5uPiZrxKg5Ba8HE6M791A7JRXOGaj4cTDfZLKKh8paLi%2F1q6ZyFhbMXtxlTnDPO0H51%2B9W%2FfTsHt%2FFBbAxqLquhp3UfZQbCVv3t8MgpvzqGMI3cEcuCj3FoPFOJJxWMy6kAN6RiEUiUuBtY6NMppb0Rdc0XcVJUu2%2B5B1OtdrB9EHpKFs0VGkPhGjy%2Fgp8pREdwOnwoqjBZu5%2BjZwdmzp80NZoqYxDHovRsM90FzNfIv25HudmIt4YQdx02yrw8WrpPYough2IkJJHYMxD6b%2FQZWbwFtt9gNu%2FWxuaC3CUithkZWlCg0MCQD3A6sqBgkNBnHSZsNB0CEGPunqF3jTFJ5AUHUTxp%2FV2Wviy3pfqAftoSozPUpuIOHpbpjX1y5%2BJXOCVazt4Hn8gPmu42Pvg6ua1Q%2FH%2BhM%2Bo2Ew5uvrvAY6pgEHS5HFnprQdBTtvP0bSeqli5v4DgJHpXhtAbTX7UQS3GfiOly8A44B9vRvSmIt0c7T1juL6eJpPb7rjFMLBPRcVr4eZt%2F94RS6aCM7dYLJOFKA5MgEPLQ1InS5JFHN5zziASIY8icqz%2BFpokIgb6TURqwDvdoZ%2FDoIwThmZOnvz%2FrKUxohxCHb7XQiWGAgdRlNWNsfRtkCJQ6qNgQ4k3X9qj8%2BRIMr&X-Amz-Signature=05d1aaf8642537855d8854f5f686a127d922436c5999db03c67bca6ce8a3ddb1&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VUI45LPU%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T042642Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIE925QSVLgTEpe6u1Um1lCmjgysdbp44BficWLiov0pTAiAfh1H5ExAuP087X8wTFUko5Adbl9PpOFZGv2F3i1aRWyqIBAid%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMZ5hk7w55svCVqjWpKtwDsxehpt7Kp5Zw8MY0M20zaBA68ZjhHILSX%2FtyjATrElk%2BGm7kWN5S715KSSABIM8Yb3Y97KGeA8kh1DrHtM%2B5QR9BISmc%2BjqArfusS2ty6H5jttujN7afIiS%2FfMoCxOzwghUm0Br7V5trkWb4ECZyHWvPjlD5SrPSaVoSpmDoxEA7z8HCyjDJxU9OgRw6XsFu8xJ0fChutdIPwkWI1AezCEq5uPiZrxKg5Ba8HE6M791A7JRXOGaj4cTDfZLKKh8paLi%2F1q6ZyFhbMXtxlTnDPO0H51%2B9W%2FfTsHt%2FFBbAxqLquhp3UfZQbCVv3t8MgpvzqGMI3cEcuCj3FoPFOJJxWMy6kAN6RiEUiUuBtY6NMppb0Rdc0XcVJUu2%2B5B1OtdrB9EHpKFs0VGkPhGjy%2Fgp8pREdwOnwoqjBZu5%2BjZwdmzp80NZoqYxDHovRsM90FzNfIv25HudmIt4YQdx02yrw8WrpPYough2IkJJHYMxD6b%2FQZWbwFtt9gNu%2FWxuaC3CUithkZWlCg0MCQD3A6sqBgkNBnHSZsNB0CEGPunqF3jTFJ5AUHUTxp%2FV2Wviy3pfqAftoSozPUpuIOHpbpjX1y5%2BJXOCVazt4Hn8gPmu42Pvg6ua1Q%2FH%2BhM%2Bo2Ew5uvrvAY6pgEHS5HFnprQdBTtvP0bSeqli5v4DgJHpXhtAbTX7UQS3GfiOly8A44B9vRvSmIt0c7T1juL6eJpPb7rjFMLBPRcVr4eZt%2F94RS6aCM7dYLJOFKA5MgEPLQ1InS5JFHN5zziASIY8icqz%2BFpokIgb6TURqwDvdoZ%2FDoIwThmZOnvz%2FrKUxohxCHb7XQiWGAgdRlNWNsfRtkCJQ6qNgQ4k3X9qj8%2BRIMr&X-Amz-Signature=d1638609361ac7bf9313ef6c1b0e22f45366ce2dae15a9e03f41c4adf71ea3ae&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VUI45LPU%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T042642Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIE925QSVLgTEpe6u1Um1lCmjgysdbp44BficWLiov0pTAiAfh1H5ExAuP087X8wTFUko5Adbl9PpOFZGv2F3i1aRWyqIBAid%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMZ5hk7w55svCVqjWpKtwDsxehpt7Kp5Zw8MY0M20zaBA68ZjhHILSX%2FtyjATrElk%2BGm7kWN5S715KSSABIM8Yb3Y97KGeA8kh1DrHtM%2B5QR9BISmc%2BjqArfusS2ty6H5jttujN7afIiS%2FfMoCxOzwghUm0Br7V5trkWb4ECZyHWvPjlD5SrPSaVoSpmDoxEA7z8HCyjDJxU9OgRw6XsFu8xJ0fChutdIPwkWI1AezCEq5uPiZrxKg5Ba8HE6M791A7JRXOGaj4cTDfZLKKh8paLi%2F1q6ZyFhbMXtxlTnDPO0H51%2B9W%2FfTsHt%2FFBbAxqLquhp3UfZQbCVv3t8MgpvzqGMI3cEcuCj3FoPFOJJxWMy6kAN6RiEUiUuBtY6NMppb0Rdc0XcVJUu2%2B5B1OtdrB9EHpKFs0VGkPhGjy%2Fgp8pREdwOnwoqjBZu5%2BjZwdmzp80NZoqYxDHovRsM90FzNfIv25HudmIt4YQdx02yrw8WrpPYough2IkJJHYMxD6b%2FQZWbwFtt9gNu%2FWxuaC3CUithkZWlCg0MCQD3A6sqBgkNBnHSZsNB0CEGPunqF3jTFJ5AUHUTxp%2FV2Wviy3pfqAftoSozPUpuIOHpbpjX1y5%2BJXOCVazt4Hn8gPmu42Pvg6ua1Q%2FH%2BhM%2Bo2Ew5uvrvAY6pgEHS5HFnprQdBTtvP0bSeqli5v4DgJHpXhtAbTX7UQS3GfiOly8A44B9vRvSmIt0c7T1juL6eJpPb7rjFMLBPRcVr4eZt%2F94RS6aCM7dYLJOFKA5MgEPLQ1InS5JFHN5zziASIY8icqz%2BFpokIgb6TURqwDvdoZ%2FDoIwThmZOnvz%2FrKUxohxCHb7XQiWGAgdRlNWNsfRtkCJQ6qNgQ4k3X9qj8%2BRIMr&X-Amz-Signature=dd24ea729f1173b101e729d2342680f5930011a9b843592bab48682308000d08&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664O7F6E2J%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T042643Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIH2852Ic82%2BOd3OhQUcn%2FSrmnt195uukmF9TtBNBzChDAiBTISoEY7w9ETb9OdAz2M8j0rgvfHjaM9zeKlYfQpWVfCqIBAid%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMRr%2BxQhyFx2rH2dZAKtwDO5t9IWQf3GQEILfjWgOaiVb7lj9pl8Qitq68wP3hQaU2hUS%2FXSM6pzdOEI9ynUbKbV81hQSaneJpqWBWzFIZ327rDvw%2FvQTrhItD%2B8Q%2FkLQaOgSwfMo0i4%2FSNwD6GnPKqiXFvvjZaVg0RPw0F%2FOHI0Al8cw3gGKECF1On5dGVnAQ8Qxcc27nkTcnyTkm5UhaFt7dyXeCMWyJPdfJKGX3CHQ8nc88VMqyNu5e%2BK3kWLkxNFj0%2B0oam72pZzO4r3WztFpx3IxQwVTYdRuxP4GuDryt4tVMln5eXRUDXGbZeHmRIgpWW9ajmtv84oIqklT5frQie8eQHropBY%2Bf77zJ5Ty0gL7KuY5RVESC31YChncVLp1J0rJGieQfjksu55M3i%2BImCvamai%2F%2Ba67NSphiAVEByymufKNPAF4PNwWYsm02yt5jksuzIdBpHe0MB6eVQRreI8Mbs0%2BoJ61Vok2l8UOrZSyzW7cIEor4%2BQqwoY5z33Swr%2F%2F2S0qYCDAI03igezsML8eVW10xJNNXzxpQ6xUUCMFScwq4MtSBNQnfYfvOWfA9XqWluzG%2BeWnxC0rASRlfllAz9Z5zjIkm96kZNeo8vS4%2FsgpVvyV7RycjolmTG2KCjlpgZyoAJ2EwoezrvAY6pgGztOYhXJ6UiNHpSvxV5VjPlHjdkf78xUggTfNfqn4%2B7CWItSkfehcGSe6T8NYsCPHgm%2ByjSqYlNjeZjqHZEJEavLVJhJRYl4tligghxw7UtqzgnnIgd1juuo0FoQHjVAAoa5WLB3ttXqWsjsTRR3FGU4ps4dxY%2FY9%2BEeoof9hHLbjzAmaJi%2FlZoRCNcRqPZEylr0kBBVYXvgZzPejvE5tfvtiHpkJk&X-Amz-Signature=82fc490efa4ca674bab106465847acdc23020ff05b8ba9710983167f2cec7871&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TJJ3O3HW%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T042644Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCCfweRohTZBQEwcgsnu%2Brxkzd5GNoGsByCXiE0%2BkNjwwIhAI4S8DISpmo5PdFkj3lgBUYdpfbsq0jF9Ew1i1%2Bv%2F8i7KogECJ3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igy8fR4kvGCiodtPgD4q3APZ0kRofatw1WHRLiweNyRx%2FuBCFVY9ElUilUdLYrj2JH9mZd%2F1cnK2%2BGHVKuvOTVFkvdRCc%2FQi8%2BREB7W8Sf8oxUHzoVk8Z8z17G5ZGhf%2F8mKQJQEqLl2xgM84PwApE6brOXTU2HqDgXw15R5F%2FuDaBzpctsurkR9c9VZHU8%2FEReZmmvfd9nOm5AXplpX4rtUiZRRE%2BrMRR0rMKDY%2Fyz7NT505E8iBnQPn2XRQJZnSaQUScrdLiiUvLxx8MEBa22f%2B4Dx1%2Fc%2BF9L%2FDnbAMkhKVsgQWv5C2fP%2BijHScdthopj0K1xyCfQNITQeM9SJVQF9fDBqw4exmSCB2FmN4hBRepz%2F3B%2FC87eJHTAcHqvMQTuEFvVELH3%2B4BhYbmDAWRmgpffm3PnKeZKsRuOFdqhZ2ZmFpLsalY3ZHzLI5y%2FkLeP2j3lgd%2B8Nx8y1%2BX%2BPcWZjT%2FTp9P37nRlbp8aj91PQR8x3oWp%2BpSzPbEY3Lnnw%2B5H4rOypXUhVoWiFP%2BsqvEfeuAllWSfFVGZEARIKMtDQMCCNG0iWL2E6ZCPLIUO4OCOiGpFSqN7Jcwe0qyEXQmf3On9uL5QOqwqMuwTEho%2BBOg6ajM4ng50Kh2FnEEop8O1J%2BSp%2BQvsMf0t3f9TDg6%2Bu8BjqkARJSIl3Wv3D5hcfJaiSWVm7QPYiV6sEbYBbdZaU4WSiPotofaIzaYPPlYm53MlzewQBS59MZAIvI4%2BkEG%2BycIwivpdXHYki9cvNYQhARs9zrVRQj8zvTMTi%2FFSZnmlxKaRN0jVkg4t6%2Bh7yJ3WOOQ8hD1Ix4zVaWsjdjFi32F%2FLhejtvOiWlFAIjcGXlaQOHnXSs964EdRLApWg6zCzWyQUAmMyy&X-Amz-Signature=2eb14a8a8b5a663e4bc12d35f52954ce2e0462ec97254184edf6ab1902fdf3f9&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VUI45LPU%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T042642Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIE925QSVLgTEpe6u1Um1lCmjgysdbp44BficWLiov0pTAiAfh1H5ExAuP087X8wTFUko5Adbl9PpOFZGv2F3i1aRWyqIBAid%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMZ5hk7w55svCVqjWpKtwDsxehpt7Kp5Zw8MY0M20zaBA68ZjhHILSX%2FtyjATrElk%2BGm7kWN5S715KSSABIM8Yb3Y97KGeA8kh1DrHtM%2B5QR9BISmc%2BjqArfusS2ty6H5jttujN7afIiS%2FfMoCxOzwghUm0Br7V5trkWb4ECZyHWvPjlD5SrPSaVoSpmDoxEA7z8HCyjDJxU9OgRw6XsFu8xJ0fChutdIPwkWI1AezCEq5uPiZrxKg5Ba8HE6M791A7JRXOGaj4cTDfZLKKh8paLi%2F1q6ZyFhbMXtxlTnDPO0H51%2B9W%2FfTsHt%2FFBbAxqLquhp3UfZQbCVv3t8MgpvzqGMI3cEcuCj3FoPFOJJxWMy6kAN6RiEUiUuBtY6NMppb0Rdc0XcVJUu2%2B5B1OtdrB9EHpKFs0VGkPhGjy%2Fgp8pREdwOnwoqjBZu5%2BjZwdmzp80NZoqYxDHovRsM90FzNfIv25HudmIt4YQdx02yrw8WrpPYough2IkJJHYMxD6b%2FQZWbwFtt9gNu%2FWxuaC3CUithkZWlCg0MCQD3A6sqBgkNBnHSZsNB0CEGPunqF3jTFJ5AUHUTxp%2FV2Wviy3pfqAftoSozPUpuIOHpbpjX1y5%2BJXOCVazt4Hn8gPmu42Pvg6ua1Q%2FH%2BhM%2Bo2Ew5uvrvAY6pgEHS5HFnprQdBTtvP0bSeqli5v4DgJHpXhtAbTX7UQS3GfiOly8A44B9vRvSmIt0c7T1juL6eJpPb7rjFMLBPRcVr4eZt%2F94RS6aCM7dYLJOFKA5MgEPLQ1InS5JFHN5zziASIY8icqz%2BFpokIgb6TURqwDvdoZ%2FDoIwThmZOnvz%2FrKUxohxCHb7XQiWGAgdRlNWNsfRtkCJQ6qNgQ4k3X9qj8%2BRIMr&X-Amz-Signature=5301234f8b845479bccce5e3bec1bd99963fb7ec233692e7b101420238099aeb&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VUI45LPU%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T042642Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIE925QSVLgTEpe6u1Um1lCmjgysdbp44BficWLiov0pTAiAfh1H5ExAuP087X8wTFUko5Adbl9PpOFZGv2F3i1aRWyqIBAid%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMZ5hk7w55svCVqjWpKtwDsxehpt7Kp5Zw8MY0M20zaBA68ZjhHILSX%2FtyjATrElk%2BGm7kWN5S715KSSABIM8Yb3Y97KGeA8kh1DrHtM%2B5QR9BISmc%2BjqArfusS2ty6H5jttujN7afIiS%2FfMoCxOzwghUm0Br7V5trkWb4ECZyHWvPjlD5SrPSaVoSpmDoxEA7z8HCyjDJxU9OgRw6XsFu8xJ0fChutdIPwkWI1AezCEq5uPiZrxKg5Ba8HE6M791A7JRXOGaj4cTDfZLKKh8paLi%2F1q6ZyFhbMXtxlTnDPO0H51%2B9W%2FfTsHt%2FFBbAxqLquhp3UfZQbCVv3t8MgpvzqGMI3cEcuCj3FoPFOJJxWMy6kAN6RiEUiUuBtY6NMppb0Rdc0XcVJUu2%2B5B1OtdrB9EHpKFs0VGkPhGjy%2Fgp8pREdwOnwoqjBZu5%2BjZwdmzp80NZoqYxDHovRsM90FzNfIv25HudmIt4YQdx02yrw8WrpPYough2IkJJHYMxD6b%2FQZWbwFtt9gNu%2FWxuaC3CUithkZWlCg0MCQD3A6sqBgkNBnHSZsNB0CEGPunqF3jTFJ5AUHUTxp%2FV2Wviy3pfqAftoSozPUpuIOHpbpjX1y5%2BJXOCVazt4Hn8gPmu42Pvg6ua1Q%2FH%2BhM%2Bo2Ew5uvrvAY6pgEHS5HFnprQdBTtvP0bSeqli5v4DgJHpXhtAbTX7UQS3GfiOly8A44B9vRvSmIt0c7T1juL6eJpPb7rjFMLBPRcVr4eZt%2F94RS6aCM7dYLJOFKA5MgEPLQ1InS5JFHN5zziASIY8icqz%2BFpokIgb6TURqwDvdoZ%2FDoIwThmZOnvz%2FrKUxohxCHb7XQiWGAgdRlNWNsfRtkCJQ6qNgQ4k3X9qj8%2BRIMr&X-Amz-Signature=fc37f1d91b1cdd6e79fa0db07fe1494baa36c0e21092e6be009465b3339ba5d3&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VUI45LPU%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T042642Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIE925QSVLgTEpe6u1Um1lCmjgysdbp44BficWLiov0pTAiAfh1H5ExAuP087X8wTFUko5Adbl9PpOFZGv2F3i1aRWyqIBAid%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMZ5hk7w55svCVqjWpKtwDsxehpt7Kp5Zw8MY0M20zaBA68ZjhHILSX%2FtyjATrElk%2BGm7kWN5S715KSSABIM8Yb3Y97KGeA8kh1DrHtM%2B5QR9BISmc%2BjqArfusS2ty6H5jttujN7afIiS%2FfMoCxOzwghUm0Br7V5trkWb4ECZyHWvPjlD5SrPSaVoSpmDoxEA7z8HCyjDJxU9OgRw6XsFu8xJ0fChutdIPwkWI1AezCEq5uPiZrxKg5Ba8HE6M791A7JRXOGaj4cTDfZLKKh8paLi%2F1q6ZyFhbMXtxlTnDPO0H51%2B9W%2FfTsHt%2FFBbAxqLquhp3UfZQbCVv3t8MgpvzqGMI3cEcuCj3FoPFOJJxWMy6kAN6RiEUiUuBtY6NMppb0Rdc0XcVJUu2%2B5B1OtdrB9EHpKFs0VGkPhGjy%2Fgp8pREdwOnwoqjBZu5%2BjZwdmzp80NZoqYxDHovRsM90FzNfIv25HudmIt4YQdx02yrw8WrpPYough2IkJJHYMxD6b%2FQZWbwFtt9gNu%2FWxuaC3CUithkZWlCg0MCQD3A6sqBgkNBnHSZsNB0CEGPunqF3jTFJ5AUHUTxp%2FV2Wviy3pfqAftoSozPUpuIOHpbpjX1y5%2BJXOCVazt4Hn8gPmu42Pvg6ua1Q%2FH%2BhM%2Bo2Ew5uvrvAY6pgEHS5HFnprQdBTtvP0bSeqli5v4DgJHpXhtAbTX7UQS3GfiOly8A44B9vRvSmIt0c7T1juL6eJpPb7rjFMLBPRcVr4eZt%2F94RS6aCM7dYLJOFKA5MgEPLQ1InS5JFHN5zziASIY8icqz%2BFpokIgb6TURqwDvdoZ%2FDoIwThmZOnvz%2FrKUxohxCHb7XQiWGAgdRlNWNsfRtkCJQ6qNgQ4k3X9qj8%2BRIMr&X-Amz-Signature=578d53313b384102c1770f23099182471ba13ac5c12adb30767a790ba34827c8&X-Amz-SignedHeaders=host&x-id=GetObject)


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

