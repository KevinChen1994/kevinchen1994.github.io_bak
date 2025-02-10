---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466SZ6JFNCO%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250210T142338Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEKb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIEpJSYV2I578lVTMnGR\
  SDPEXUsMlcrHGOs%2Fd5aXT71QuAiEAoGMoGgakYB2T4d7ZKp3QkH1lLHW3JBjnTicLYsIp7qIqiA\
  QIv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDO6l%2Byev3cHo6fq\
  ybSrcA2KrUaf4dytxP8UWPN32Q8O%2BzJmnDycZ4twKTKPJ5g1Fkv%2BuSXutcmSYQzSrc4CUlPI8\
  CtwU7QA1Aw9MQuFoyInW9Dzdzky95w74qQ3RBzcNGrMw56h7WKIePKu%2FTf8Yp4Qk2WpsEEeGQhX\
  xMWua92DFbJ5ntwKC8t2XspsqrUFKI%2BiGkbGVSHv0NMU1DqC%2FNkkNxkxW0cGIG1JDkgkwA8ew\
  9FJ52wl2AnAZmEJzizLQvrl%2BC5nod9OB9zWkUiVzK0cJMpJgy5pjWibNHvEE6t2ofL3AWUnUX3h\
  Hgn4xuizEiLcBVOqLZwSz4xYydhXCGpjBI3O8IQHVB%2FlNrzLSjdTQRaTzJAls48axhy8JfFJcG1\
  syd3DoiaqjQ2RToE5HkzGHyK%2FDl3xW%2BWEAuTIeTLCCVwojofZCC%2FynY07S1ixO5znSUUK4l\
  apAA5bni7AFGJgVM4HPxmtbDVrXfg2xYxDslxqph2yzInaqVuGvnBwsZkySssOobAe%2BC0KnZuZi\
  Yp3vom0k8l2GcH6iPiAWqtc6iMtmXQI14cliDcncq2a03H3FPXBUZYHEXpeyT%2B6A5zZEIsEehG5\
  vXXTLG4dvAR1qwT40bs4EckZTuUfjSdDoE2TdUmpc8XS0%2BOUIMJOEqL0GOqUBxPNYSfjWw%2FRB\
  v0jg%2FS6ZgQSjgcEtv04Y7YVUIe%2Fe4666aFk03FSB9%2FiE%2Fgz70atvA69B0xhVsSbqq9x9e\
  76zqAcPZEmLRITOoCMtuZ9jhnW%2FBrZE5bk6yjlSapLmHNYW4ix6FIdwuh%2F5AiPmkBr7VCF30S\
  jzMZ0Epl44Rpjw7SIyqbPc0UVg1tVqrVi4Q4yR1220jUslEjtYG1Ju7v5R5GQwy2sg&X-Amz-Sign\
  ature=8b1ef7be3ad7754a7ae6e258f812f109c57082e9bcf60be58bdc91b4762150d2&X-Amz-\
  SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466352JU5ZH%2F20250210%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250210T142200Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEKb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEY\
        CIQD35tA7uP7taXi9VSgKtpFYSsZIfaxaymGJY2bD2z%2BzSgIhANUUGNnfP68cQTk9IX%2\
        FZSit5se0HAACMzDpQ1Dtd9o9%2FKogECL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQA\
        BoMNjM3NDIzMTgzODA1IgwphrXrbE6bmfz%2BbX0q3APmabdK2o6oY5P4z00inZCp%2BjMo\
        p%2FfdiQ7D4c3mLFdhhgG3cTvlxmM8V0vsNcfliOgdJfHlk5qQ1Hlnub2%2FzrR8x6%2Bb1\
        fPaSxLlBR32IIUwvzuuOTbMjT3WByugzRMnb0ppTfSNhl%2BSVq9ZvoBA1QGI0DybL4lwC%\
        2Bf0gabg8NCtawM5gcXSdXrIN0deGzxe2h7znhgOGdXJjUBpphLJJePKRq0wwwLSvUHycDB\
        2x2epT8jSi8rWQ3TBd5VljB%2Fe3mZicVLikPXR59ipYVoxcBUEZwKIwCnqDpS2nJmftPYE\
        j8fQGAf1yJNAx9U20lKyFzVEEIq0dTuXwGlpMbtUwX6TZ35PTGrqYA61zLYOdKM%2FpSfiy\
        C8CvJn3LHqa%2FhoMfcy1XJah3JYCL47fPNSp%2B5tc8SIGp3yBP8Zircx2RNRLPDJ38zmT\
        JoIBhOteq4%2F9eENWdli7Ofvl8xfzvE31Bb%2BfuJGsMJqSAsvrfFpEvg4blT6UMbZlMZK\
        dByWX0xEPss7YOPeIgpY8OPM6vMc%2BLJKVZUXFMHo2qN7PYnVU6o2831qbrKDQhOjJVOLP\
        u5mGFp1oQ15cF6s%2BotcwCmkG8wvFrwMokMDS7JjWoyjFtvPG0Ldnl8GSK6lGJcHTsjDRh\
        Ki9BjqkAQX7qa7CuOMAK%2BTs9KxxHVj53f8AOOJkBR4Ygq69PQWdV4b7fY7xcDMlB8NUQv\
        8fiP7c917yU%2F2kOgdw88aP6QaBtCef6fVm665jh1aOBF3G71Ryi2b5qK8u4UrhgNmNwmk\
        I%2BgAzfowbo%2Fr3PR8ES56gd5HFHX90Nr5PNChPrMyXNN2Ys3jo0CzwUsRQVOu3%2B8KT\
        5Fz%2Fk6uPH9e%2BjKk2XT9W8Yjy&X-Amz-Signature=c4aae0c43f7458a99255d2c748\
        c6a6f650ebca8346725a0cb1030119509b2de6&X-Amz-SignedHeaders=host&x-id=Ge\
        tObject"
      expiry_time: "2025-02-10T15:22:00.627Z"
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
UPDATE_TIME: "2025-02-10T14:23:44.182Z"
EXPIRY_TIME: "2025-02-10T15:23:31.563Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662VHKMITA%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T142332Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEUunB8qUGwBYl%2FJQddF4uYmv8pEKOk2%2BF7%2B%2FuGhv1WeAiAZiF9tRQ5vxmBOO%2FoHWq9%2BDZR6K8901s4xIaLI9uU%2BqCqIBAi%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMPLvRQhIGpUoD5Um5KtwD4KcK%2FgK7cRy%2BuCwnC%2Fuo9oZ%2FZC8icA02Z9tNI1O5spr3xuMlOf7w9zACUR8skhHTZESdzniinf7lSuNWUfKXpwt%2BRsSGD3f5y24FVe2ntnLlFLpnVAVAYlp%2Fg8FDt5aC49zZ1xq2BffFG78Ab0sF1%2BB6%2B6MnTpNjfWWHgeVaBvsKTECX2SlFZ8p1eHmzeU3MuvNoHQTfMLv7oH7kPHytArRBbEsYfn1TXY6OE%2B9LYh36OPEut%2BdlForGrCGfQW7jiuYGI3lF9rSx7GF6Q8zeXSHZmS8wGCt%2BH4Q1M%2BtxphKlcv%2FUAVFqU3kaNzsz09UdwaAt563dQf%2BW781fQqwdb12upHwU%2BOoAg%2BJda8y462eF7iJke8CXmHMX2ui4W%2F4YKhVtfEkAea4P%2BBKSCQHrTPLXLTKjYlq6yxrMWVwVVGSD8KEo9EeE0FdOQdFnL5cpAAffOYSKyWf1JrxAG68IROwPiqpOPITFBf4NuNRzfsDMORYPBS3AZXIS9TDSPa%2FkQvCsq1TpK%2F%2FHlSlYw8%2F48rny2Z4nETWtmHVMr%2BPieL7FqBpuT%2FQZt6wGbLqBAwu15tKd5x6j5o3UFyzRMUtpaulkivi1wzYPs20RfAWsP5ktoqNuJ4mPYUuYklgwmoSovQY6pgGd2Xlm5Zt3HlszOTDg%2BEuIH9%2BgZVnyYuteqFaoUCMM%2BU7VlfK2%2BUUqUedxZOsivz%2BZkEWPIwnapGIf9aWDm3x0k2mjTyYvc0yoQNLanBKyMNl44DzmRsly6EvPtIvW%2Fo6cak7RdcSJZCtGr4sxTQW1zMjZfbQLiXMZDa%2FOaha3wIQkN6KTO4Ra4rn86iE9iiSDMfDx1ZuHZTilIMVlqdpVYIMJ9xSs&X-Amz-Signature=d14e72ed816ad88ddd4587a5dc2016d668549d66aea467b4d042e9f16e4514b2&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662VHKMITA%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T142332Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEUunB8qUGwBYl%2FJQddF4uYmv8pEKOk2%2BF7%2B%2FuGhv1WeAiAZiF9tRQ5vxmBOO%2FoHWq9%2BDZR6K8901s4xIaLI9uU%2BqCqIBAi%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMPLvRQhIGpUoD5Um5KtwD4KcK%2FgK7cRy%2BuCwnC%2Fuo9oZ%2FZC8icA02Z9tNI1O5spr3xuMlOf7w9zACUR8skhHTZESdzniinf7lSuNWUfKXpwt%2BRsSGD3f5y24FVe2ntnLlFLpnVAVAYlp%2Fg8FDt5aC49zZ1xq2BffFG78Ab0sF1%2BB6%2B6MnTpNjfWWHgeVaBvsKTECX2SlFZ8p1eHmzeU3MuvNoHQTfMLv7oH7kPHytArRBbEsYfn1TXY6OE%2B9LYh36OPEut%2BdlForGrCGfQW7jiuYGI3lF9rSx7GF6Q8zeXSHZmS8wGCt%2BH4Q1M%2BtxphKlcv%2FUAVFqU3kaNzsz09UdwaAt563dQf%2BW781fQqwdb12upHwU%2BOoAg%2BJda8y462eF7iJke8CXmHMX2ui4W%2F4YKhVtfEkAea4P%2BBKSCQHrTPLXLTKjYlq6yxrMWVwVVGSD8KEo9EeE0FdOQdFnL5cpAAffOYSKyWf1JrxAG68IROwPiqpOPITFBf4NuNRzfsDMORYPBS3AZXIS9TDSPa%2FkQvCsq1TpK%2F%2FHlSlYw8%2F48rny2Z4nETWtmHVMr%2BPieL7FqBpuT%2FQZt6wGbLqBAwu15tKd5x6j5o3UFyzRMUtpaulkivi1wzYPs20RfAWsP5ktoqNuJ4mPYUuYklgwmoSovQY6pgGd2Xlm5Zt3HlszOTDg%2BEuIH9%2BgZVnyYuteqFaoUCMM%2BU7VlfK2%2BUUqUedxZOsivz%2BZkEWPIwnapGIf9aWDm3x0k2mjTyYvc0yoQNLanBKyMNl44DzmRsly6EvPtIvW%2Fo6cak7RdcSJZCtGr4sxTQW1zMjZfbQLiXMZDa%2FOaha3wIQkN6KTO4Ra4rn86iE9iiSDMfDx1ZuHZTilIMVlqdpVYIMJ9xSs&X-Amz-Signature=f1fb15226cc74e2d0989943582066d97420e97cf9873419f94b583d89c827126&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662VHKMITA%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T142332Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEUunB8qUGwBYl%2FJQddF4uYmv8pEKOk2%2BF7%2B%2FuGhv1WeAiAZiF9tRQ5vxmBOO%2FoHWq9%2BDZR6K8901s4xIaLI9uU%2BqCqIBAi%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMPLvRQhIGpUoD5Um5KtwD4KcK%2FgK7cRy%2BuCwnC%2Fuo9oZ%2FZC8icA02Z9tNI1O5spr3xuMlOf7w9zACUR8skhHTZESdzniinf7lSuNWUfKXpwt%2BRsSGD3f5y24FVe2ntnLlFLpnVAVAYlp%2Fg8FDt5aC49zZ1xq2BffFG78Ab0sF1%2BB6%2B6MnTpNjfWWHgeVaBvsKTECX2SlFZ8p1eHmzeU3MuvNoHQTfMLv7oH7kPHytArRBbEsYfn1TXY6OE%2B9LYh36OPEut%2BdlForGrCGfQW7jiuYGI3lF9rSx7GF6Q8zeXSHZmS8wGCt%2BH4Q1M%2BtxphKlcv%2FUAVFqU3kaNzsz09UdwaAt563dQf%2BW781fQqwdb12upHwU%2BOoAg%2BJda8y462eF7iJke8CXmHMX2ui4W%2F4YKhVtfEkAea4P%2BBKSCQHrTPLXLTKjYlq6yxrMWVwVVGSD8KEo9EeE0FdOQdFnL5cpAAffOYSKyWf1JrxAG68IROwPiqpOPITFBf4NuNRzfsDMORYPBS3AZXIS9TDSPa%2FkQvCsq1TpK%2F%2FHlSlYw8%2F48rny2Z4nETWtmHVMr%2BPieL7FqBpuT%2FQZt6wGbLqBAwu15tKd5x6j5o3UFyzRMUtpaulkivi1wzYPs20RfAWsP5ktoqNuJ4mPYUuYklgwmoSovQY6pgGd2Xlm5Zt3HlszOTDg%2BEuIH9%2BgZVnyYuteqFaoUCMM%2BU7VlfK2%2BUUqUedxZOsivz%2BZkEWPIwnapGIf9aWDm3x0k2mjTyYvc0yoQNLanBKyMNl44DzmRsly6EvPtIvW%2Fo6cak7RdcSJZCtGr4sxTQW1zMjZfbQLiXMZDa%2FOaha3wIQkN6KTO4Ra4rn86iE9iiSDMfDx1ZuHZTilIMVlqdpVYIMJ9xSs&X-Amz-Signature=2a784b044133c915231e67b4fd89ecce713d4f32b716c2d265da6bba3dcc9260&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662VHKMITA%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T142332Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEUunB8qUGwBYl%2FJQddF4uYmv8pEKOk2%2BF7%2B%2FuGhv1WeAiAZiF9tRQ5vxmBOO%2FoHWq9%2BDZR6K8901s4xIaLI9uU%2BqCqIBAi%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMPLvRQhIGpUoD5Um5KtwD4KcK%2FgK7cRy%2BuCwnC%2Fuo9oZ%2FZC8icA02Z9tNI1O5spr3xuMlOf7w9zACUR8skhHTZESdzniinf7lSuNWUfKXpwt%2BRsSGD3f5y24FVe2ntnLlFLpnVAVAYlp%2Fg8FDt5aC49zZ1xq2BffFG78Ab0sF1%2BB6%2B6MnTpNjfWWHgeVaBvsKTECX2SlFZ8p1eHmzeU3MuvNoHQTfMLv7oH7kPHytArRBbEsYfn1TXY6OE%2B9LYh36OPEut%2BdlForGrCGfQW7jiuYGI3lF9rSx7GF6Q8zeXSHZmS8wGCt%2BH4Q1M%2BtxphKlcv%2FUAVFqU3kaNzsz09UdwaAt563dQf%2BW781fQqwdb12upHwU%2BOoAg%2BJda8y462eF7iJke8CXmHMX2ui4W%2F4YKhVtfEkAea4P%2BBKSCQHrTPLXLTKjYlq6yxrMWVwVVGSD8KEo9EeE0FdOQdFnL5cpAAffOYSKyWf1JrxAG68IROwPiqpOPITFBf4NuNRzfsDMORYPBS3AZXIS9TDSPa%2FkQvCsq1TpK%2F%2FHlSlYw8%2F48rny2Z4nETWtmHVMr%2BPieL7FqBpuT%2FQZt6wGbLqBAwu15tKd5x6j5o3UFyzRMUtpaulkivi1wzYPs20RfAWsP5ktoqNuJ4mPYUuYklgwmoSovQY6pgGd2Xlm5Zt3HlszOTDg%2BEuIH9%2BgZVnyYuteqFaoUCMM%2BU7VlfK2%2BUUqUedxZOsivz%2BZkEWPIwnapGIf9aWDm3x0k2mjTyYvc0yoQNLanBKyMNl44DzmRsly6EvPtIvW%2Fo6cak7RdcSJZCtGr4sxTQW1zMjZfbQLiXMZDa%2FOaha3wIQkN6KTO4Ra4rn86iE9iiSDMfDx1ZuHZTilIMVlqdpVYIMJ9xSs&X-Amz-Signature=776d1de37612e6bf9e28c0546b6f9b1612988bcf986ba8d538cea1aba0df1574&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662VHKMITA%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T142332Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEUunB8qUGwBYl%2FJQddF4uYmv8pEKOk2%2BF7%2B%2FuGhv1WeAiAZiF9tRQ5vxmBOO%2FoHWq9%2BDZR6K8901s4xIaLI9uU%2BqCqIBAi%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMPLvRQhIGpUoD5Um5KtwD4KcK%2FgK7cRy%2BuCwnC%2Fuo9oZ%2FZC8icA02Z9tNI1O5spr3xuMlOf7w9zACUR8skhHTZESdzniinf7lSuNWUfKXpwt%2BRsSGD3f5y24FVe2ntnLlFLpnVAVAYlp%2Fg8FDt5aC49zZ1xq2BffFG78Ab0sF1%2BB6%2B6MnTpNjfWWHgeVaBvsKTECX2SlFZ8p1eHmzeU3MuvNoHQTfMLv7oH7kPHytArRBbEsYfn1TXY6OE%2B9LYh36OPEut%2BdlForGrCGfQW7jiuYGI3lF9rSx7GF6Q8zeXSHZmS8wGCt%2BH4Q1M%2BtxphKlcv%2FUAVFqU3kaNzsz09UdwaAt563dQf%2BW781fQqwdb12upHwU%2BOoAg%2BJda8y462eF7iJke8CXmHMX2ui4W%2F4YKhVtfEkAea4P%2BBKSCQHrTPLXLTKjYlq6yxrMWVwVVGSD8KEo9EeE0FdOQdFnL5cpAAffOYSKyWf1JrxAG68IROwPiqpOPITFBf4NuNRzfsDMORYPBS3AZXIS9TDSPa%2FkQvCsq1TpK%2F%2FHlSlYw8%2F48rny2Z4nETWtmHVMr%2BPieL7FqBpuT%2FQZt6wGbLqBAwu15tKd5x6j5o3UFyzRMUtpaulkivi1wzYPs20RfAWsP5ktoqNuJ4mPYUuYklgwmoSovQY6pgGd2Xlm5Zt3HlszOTDg%2BEuIH9%2BgZVnyYuteqFaoUCMM%2BU7VlfK2%2BUUqUedxZOsivz%2BZkEWPIwnapGIf9aWDm3x0k2mjTyYvc0yoQNLanBKyMNl44DzmRsly6EvPtIvW%2Fo6cak7RdcSJZCtGr4sxTQW1zMjZfbQLiXMZDa%2FOaha3wIQkN6KTO4Ra4rn86iE9iiSDMfDx1ZuHZTilIMVlqdpVYIMJ9xSs&X-Amz-Signature=f32f0880c399035a8b1a989d8fe3f065c1c6507aa0c17a5c88b38e07f2b98d70&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RHNB7OUX%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T142335Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCClpJBjmzLNFtrO%2BEzyYKMn%2FcSi1SE9B1SQpSy%2BkJQ8AIgFa8FSoIs1ScRI1PJtztwfksrm3QdYa3pAnNN9inNx1wqiAQIv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDETmPoPxwUPpz7l1wyrcA9zTU2rZaVgiGxrEy15r%2BF96pn5YefBgkuf2ycuBF1TfXRtLk%2FJ2R0gbJ45wFPgTHyOnfO4OnVgTiQLC2k%2BoY%2FymL1gUqbVqFn%2B3rXzRqydAyvlrZdrV%2BjGGbKQFOShdDbVgjfatdLsQg4llP9ZP8Kn69TnmLXzy6%2BCYYqrwobu%2Bj2%2F5CzoHcedT29qF3hCytvZu3dAejTZe%2BoGD09x9b6dde%2BQowo%2BDbgeNJW9t9z%2F6CCzoYrH%2BGJ75hKqZc3aZZjKkvDSTGQ6WANicK6C%2F99ASEF4%2BPBKb3J8dljtafc9WwTR56BvnUT1tVSoClUq1pPSFU0PpxHjCQcRU9mH6yfcNOA2ye%2Fr3xaPewSP9fy7iQe%2FEsi3c8jRq6VFYS%2Fll1YX9nJbS3EoWDS%2BPWXePspqcLOR1L6Lb7dJ4XPPOu3C4SCsxs1J2KYyvtYel7UevFTwhHa7HR9LfH5%2B2amZbVFB6gMym3PGA3cfD4hg2IG9ZHZEi%2BV%2BXCK3JuciCJVnJu%2BgbmNlDhGo0Xn4wuklE8eLB%2F66A2rRF6UViYUiqf1Lpp%2FroiBL15GR13nLp5kU1HzUlj2b2CYn7A547T7r9lyh3pS9JBr%2BlfrmXTlrgDZEmNT2mF%2FjU8Ej3LcUyMKSEqL0GOqUB8xftqyuAm24c466n1t0ctN11DwnkkuUj8nXfykhA5MAG7Z3XEEOORNi7ZV0iGh%2FlUm59i%2FZsIbDK4PM4T83mt5NzjtlvKpT6E%2FrTbZdfFgi8gTy03NVaqBmajmlhKkq5jfAv5og5UyyPR4%2BXLPyO4yMJN7syx7eaTTt%2BQmIEnm36Ig3Iu1G5mHFuYMYK9agTopC0rz1jCxc5tbioqai3xFYzx1Mh&X-Amz-Signature=36aa7d64b3ca4f29cfc6db16f3616aa158df32c41f382c663f13600d3fa457c6&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XVB2AJKV%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T142338Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDOwlqR4WRRqK6QWpjXdbauqJJYPDEa7vM75W1N0xjnNwIhANhFhDTILkSj9DrHRef3nadGwTyjmoR%2F%2FbkqkM0egI5mKogECL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxKdoar9mRxlgR9W%2B0q3AMULtAipukp2l%2Bccz0pQDtqROsw0iqxCzfwdvylxoFL%2FksADVxnz2yZWoBHrB%2BRQmicvoqwvRqGW%2BIi712QLfOT4pA1KeL8jf2LVSKgtleYQ%2FFciIOK8BVfepmw5dBUOoRWI2XwzcSXekGz7%2F%2FOflTqhr2vYk5eaSNUfgfQeXD2N1L6YkpjVOLI8zawquRdjVYtpqJjAejJ8UoB2%2FJgqr1%2B76GVuV52aECzTSnmRzkBjcrHyerwB1HoTxanI6ZVC88y%2BI69v%2Fa4jQsx1jYvoE9AnjJB6woGUE76DuGZECthATKihP9a7Rn4%2B4WGL%2BSouGlYlH9QNSlDbcuSJEzLqisoTsB%2BuqeRsmITGn6KFI8h%2BUQ9skKl66TVnLY24EchXSNxbRcgh4v4TB4H1RAO5KeHrcFophtt0iDQoasgtILoZAmz48HQRdeyRFM%2B1ul2tqTP0BjhhwjlKn4A9ttpL%2BvMml7XgYjW14G0D4YKrLHCCi2U5OewStX0rksVGqss6BcRep7upaGR74hNUWs%2B%2F2EMuJ1D8IztwIEeBaEglPDhK5GBoJ6SZL2M5Xpcgld%2BpAq6OVzMAqnKjyZS%2BHTj9P%2BUrG2a0xrDeYq1w8VZ0Nrifl1jcy0O8z%2FgmkdzOTC2g6i9BjqkAaULPdV9thFKbv1WJMOO%2BXCZx7ulAFQRP0ASAON7FGCljSu9epEoJGOIive7PXfBi%2Bi%2FYzCBIIB9JnHtrHBLcOmMx8%2FwuiOBZueezLIy33%2FztkpIOs0M0ydtE9qs%2Fm3dodHV1MMHqlLkUIdPceKxnD3NupIp2ivx8m2007HUnqU723i9Qt%2FTJfBXXTcB%2BfDbeO9qlBVU4bkSgZ%2BWM3nfM3FYzDxa&X-Amz-Signature=28d49c170769f8a88ee40b1e5d828bc2d4ab640931d1c8b88eb82c89895c399f&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662VHKMITA%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T142332Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEUunB8qUGwBYl%2FJQddF4uYmv8pEKOk2%2BF7%2B%2FuGhv1WeAiAZiF9tRQ5vxmBOO%2FoHWq9%2BDZR6K8901s4xIaLI9uU%2BqCqIBAi%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMPLvRQhIGpUoD5Um5KtwD4KcK%2FgK7cRy%2BuCwnC%2Fuo9oZ%2FZC8icA02Z9tNI1O5spr3xuMlOf7w9zACUR8skhHTZESdzniinf7lSuNWUfKXpwt%2BRsSGD3f5y24FVe2ntnLlFLpnVAVAYlp%2Fg8FDt5aC49zZ1xq2BffFG78Ab0sF1%2BB6%2B6MnTpNjfWWHgeVaBvsKTECX2SlFZ8p1eHmzeU3MuvNoHQTfMLv7oH7kPHytArRBbEsYfn1TXY6OE%2B9LYh36OPEut%2BdlForGrCGfQW7jiuYGI3lF9rSx7GF6Q8zeXSHZmS8wGCt%2BH4Q1M%2BtxphKlcv%2FUAVFqU3kaNzsz09UdwaAt563dQf%2BW781fQqwdb12upHwU%2BOoAg%2BJda8y462eF7iJke8CXmHMX2ui4W%2F4YKhVtfEkAea4P%2BBKSCQHrTPLXLTKjYlq6yxrMWVwVVGSD8KEo9EeE0FdOQdFnL5cpAAffOYSKyWf1JrxAG68IROwPiqpOPITFBf4NuNRzfsDMORYPBS3AZXIS9TDSPa%2FkQvCsq1TpK%2F%2FHlSlYw8%2F48rny2Z4nETWtmHVMr%2BPieL7FqBpuT%2FQZt6wGbLqBAwu15tKd5x6j5o3UFyzRMUtpaulkivi1wzYPs20RfAWsP5ktoqNuJ4mPYUuYklgwmoSovQY6pgGd2Xlm5Zt3HlszOTDg%2BEuIH9%2BgZVnyYuteqFaoUCMM%2BU7VlfK2%2BUUqUedxZOsivz%2BZkEWPIwnapGIf9aWDm3x0k2mjTyYvc0yoQNLanBKyMNl44DzmRsly6EvPtIvW%2Fo6cak7RdcSJZCtGr4sxTQW1zMjZfbQLiXMZDa%2FOaha3wIQkN6KTO4Ra4rn86iE9iiSDMfDx1ZuHZTilIMVlqdpVYIMJ9xSs&X-Amz-Signature=da3e59c2b838344bbf5a08288eaf335e6816211eb85c00679bb6536ffbbc1183&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662VHKMITA%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T142332Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEUunB8qUGwBYl%2FJQddF4uYmv8pEKOk2%2BF7%2B%2FuGhv1WeAiAZiF9tRQ5vxmBOO%2FoHWq9%2BDZR6K8901s4xIaLI9uU%2BqCqIBAi%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMPLvRQhIGpUoD5Um5KtwD4KcK%2FgK7cRy%2BuCwnC%2Fuo9oZ%2FZC8icA02Z9tNI1O5spr3xuMlOf7w9zACUR8skhHTZESdzniinf7lSuNWUfKXpwt%2BRsSGD3f5y24FVe2ntnLlFLpnVAVAYlp%2Fg8FDt5aC49zZ1xq2BffFG78Ab0sF1%2BB6%2B6MnTpNjfWWHgeVaBvsKTECX2SlFZ8p1eHmzeU3MuvNoHQTfMLv7oH7kPHytArRBbEsYfn1TXY6OE%2B9LYh36OPEut%2BdlForGrCGfQW7jiuYGI3lF9rSx7GF6Q8zeXSHZmS8wGCt%2BH4Q1M%2BtxphKlcv%2FUAVFqU3kaNzsz09UdwaAt563dQf%2BW781fQqwdb12upHwU%2BOoAg%2BJda8y462eF7iJke8CXmHMX2ui4W%2F4YKhVtfEkAea4P%2BBKSCQHrTPLXLTKjYlq6yxrMWVwVVGSD8KEo9EeE0FdOQdFnL5cpAAffOYSKyWf1JrxAG68IROwPiqpOPITFBf4NuNRzfsDMORYPBS3AZXIS9TDSPa%2FkQvCsq1TpK%2F%2FHlSlYw8%2F48rny2Z4nETWtmHVMr%2BPieL7FqBpuT%2FQZt6wGbLqBAwu15tKd5x6j5o3UFyzRMUtpaulkivi1wzYPs20RfAWsP5ktoqNuJ4mPYUuYklgwmoSovQY6pgGd2Xlm5Zt3HlszOTDg%2BEuIH9%2BgZVnyYuteqFaoUCMM%2BU7VlfK2%2BUUqUedxZOsivz%2BZkEWPIwnapGIf9aWDm3x0k2mjTyYvc0yoQNLanBKyMNl44DzmRsly6EvPtIvW%2Fo6cak7RdcSJZCtGr4sxTQW1zMjZfbQLiXMZDa%2FOaha3wIQkN6KTO4Ra4rn86iE9iiSDMfDx1ZuHZTilIMVlqdpVYIMJ9xSs&X-Amz-Signature=f4a9347e30c581e8bf4b54facc255df9026d7095c364f6b7fdbadc2b21580879&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662VHKMITA%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T142332Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEUunB8qUGwBYl%2FJQddF4uYmv8pEKOk2%2BF7%2B%2FuGhv1WeAiAZiF9tRQ5vxmBOO%2FoHWq9%2BDZR6K8901s4xIaLI9uU%2BqCqIBAi%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMPLvRQhIGpUoD5Um5KtwD4KcK%2FgK7cRy%2BuCwnC%2Fuo9oZ%2FZC8icA02Z9tNI1O5spr3xuMlOf7w9zACUR8skhHTZESdzniinf7lSuNWUfKXpwt%2BRsSGD3f5y24FVe2ntnLlFLpnVAVAYlp%2Fg8FDt5aC49zZ1xq2BffFG78Ab0sF1%2BB6%2B6MnTpNjfWWHgeVaBvsKTECX2SlFZ8p1eHmzeU3MuvNoHQTfMLv7oH7kPHytArRBbEsYfn1TXY6OE%2B9LYh36OPEut%2BdlForGrCGfQW7jiuYGI3lF9rSx7GF6Q8zeXSHZmS8wGCt%2BH4Q1M%2BtxphKlcv%2FUAVFqU3kaNzsz09UdwaAt563dQf%2BW781fQqwdb12upHwU%2BOoAg%2BJda8y462eF7iJke8CXmHMX2ui4W%2F4YKhVtfEkAea4P%2BBKSCQHrTPLXLTKjYlq6yxrMWVwVVGSD8KEo9EeE0FdOQdFnL5cpAAffOYSKyWf1JrxAG68IROwPiqpOPITFBf4NuNRzfsDMORYPBS3AZXIS9TDSPa%2FkQvCsq1TpK%2F%2FHlSlYw8%2F48rny2Z4nETWtmHVMr%2BPieL7FqBpuT%2FQZt6wGbLqBAwu15tKd5x6j5o3UFyzRMUtpaulkivi1wzYPs20RfAWsP5ktoqNuJ4mPYUuYklgwmoSovQY6pgGd2Xlm5Zt3HlszOTDg%2BEuIH9%2BgZVnyYuteqFaoUCMM%2BU7VlfK2%2BUUqUedxZOsivz%2BZkEWPIwnapGIf9aWDm3x0k2mjTyYvc0yoQNLanBKyMNl44DzmRsly6EvPtIvW%2Fo6cak7RdcSJZCtGr4sxTQW1zMjZfbQLiXMZDa%2FOaha3wIQkN6KTO4Ra4rn86iE9iiSDMfDx1ZuHZTilIMVlqdpVYIMJ9xSs&X-Amz-Signature=bfd40ba9c33773ae6b0e1ca4260bae357f9fa5197d089d4a5395afed1949b391&X-Amz-SignedHeaders=host&x-id=GetObject)


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

