---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466XHXBDU6C%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250222T052159Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEL3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCUowMO%2BgqYzeupi\
  qA9wP84P5irZ1KZ%2FSismc4gddZoUwIgcjn0IzqCv74EoqeLAWZCcKrbvBuEYelYAX3I0dU8FB0q\
  iAQI5v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPapLpP7HGIgb%2FH\
  ibSrcA5NG%2BeNe0snvlb%2BTt8zvdqUt4V3k2cCVjgMEfqKKiuBGbV50VKI%2B0L8Jr4aXslCdGs\
  92yItlTyj4C5W%2FmvI9kbv%2FupG7r2axFKvuRM8Bzejy8Ci%2BpHDCHE27PyJZdHKWE8uMlcM3E\
  CZfdo8BlEPeo4dQCqNGpexoVa%2FBWOc%2FSCe4wPxSjqh8sg70HW826XempIOL76j2oJayLsm%2B\
  Vc5nuw20CLe%2BmU5PxymoYszN16wgpsxr40uUmeD4nZDBqfD5DFG%2BreoFAFnr8EVZi1c5CISdI\
  pnv7f5tfME1jdvEN76qwBLBNoBO7pg6Gatccfa8w1EWy9jlwvP%2F9e5FEwlTAQhxBBHepkLqomQM\
  2GfsyLd%2BhzueNH3zXLp5%2B8OH3rHePSSTN0Gt9HgJaNOEuh7gp7Ie%2F9eWBtTZJwb3AlWXZq5\
  NzQi7M1HNxflgpDRATl7drM%2BEayy%2BEO7RNKJId%2Fcwo%2Fc3IPaCVLgpog11nneLZjK%2B8r\
  P0uBYl9ov5x40yq2MTr%2FeUQ7K7tzYdnvuqr8VQ%2BpL%2FrdfM4KTt0OolFdJz4wfCgeFMjbeKc\
  a9wtC273XKsJv%2B7K8ZsRtIzKH%2Fw9Fpn0tqMWgDxwByFHT%2FvAdrz9K0jiphaKsN9sM5mI06I\
  MLGq5b0GOqUBYGHwuWBpO2dbM9NQ%2F6F8cSNQ8ZUM0g3da8mlGAUdE1GdixRDImqK16Op7VE%2Bx\
  VZnpOZ%2B8Kt3zdTH9FhLMP7bV2l6AqVOYgnC341mpGjaKL44PmMyAXB7OBcTRRB9GXQIef7GSxva\
  xU%2BdqDjScg9aiCTGB31rf3TKIhzt%2FFmX1v8cy8t3arw5nW8gYg%2Fdk9etNAXfoyq5BWXMkw%\
  2BQPy5sJr9%2BBNqA&X-Amz-Signature=65f19c20945af8a85f3def64604ec8967889ed5a8c9\
  2b295837e7d65db6f4841&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466QLXYZCV5%2F20250222%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250222T052040Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEL3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIQDf1Qmt49FrtoOSQpHw7fKHfbhD2vM5%2Ftjv6%2BWtChhO1QIgL%2BnYj5YZ8H5mNwd%\
        2BLbTey5AnhytY1G%2F68sZw465eHDcqiAQI5v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARA\
        AGgw2Mzc0MjMxODM4MDUiDI5ShmXY4SAcSEEAzircA%2FSeMvaFH%2BN46%2BF8jqUlp6YU\
        w6UZ%2F3xCyZoXDim0v4xpl5YfWB8piHrGvun%2FllqPQYv5PpADjHq3U51W4MODUQ3JwM%\
        2FF3cQBgvPk64n%2B%2Fu7wPCb2NSGU2cupscupQqaYDD0kWSgAZUKABBX5Y2GIgcyJCHZk\
        aCY5Oti4tk6ggsmWG8lKHsylDp0iIhreCXcGeYi6nKYTxHCnitw5wHY5Rbr8xjS5vErC3n%\
        2BjOv25VcALvtnhOVP5MFiv4kwtxVHKQ26OBK28%2BlHhVe547VjTY3mnX2uVxSXIYXkWhI\
        imlUGc9DOKEhbkfPy6u7ismDloBzOvHPZTSjhBEW6rh%2FLiT6gRulqOulak5BN3%2F%2Fw\
        FHsPlsL7LI6LKb8daoa%2BLP0i4fr9PkajrAXyl7BervVDXSo2X6qLAoHfJspDDyapYSKeP\
        9S%2BXmi4to9DTOyhtaLNUfNMy4ZaWmgfcEfxzMerTOg5ruqFVL%2Fnu%2FvAO8xU%2Ft2V\
        2thNHtkayauthg4kVynk0JLWctrT4A4muZb75WanNWU5yT6fTQwYXcalSfp4AQn4zsJBxWI\
        WD%2BDN5%2B9KmhJ9%2BUC%2BLVyUW60mPsdd%2Bkvqs5QIGxLi7lH3UJ5Qy3JRwU8cn8%2\
        F5X3s6jJYiRyEXBMPap5b0GOqUB1wTL%2Fttm%2FauGbwatltDb9EsASed5IcwadDILTrKi\
        u%2FurBVMlle1TIC4TmTHxO6TWHKQLI%2FJ4jcTiHusrPha3tWZ8yP0g1XIGE8MFWckBPKi\
        m1pms%2FXJFYfr9mSJh3rRmHUuIh0eMks55XcZDzRYEoAYzMdQnofLpM%2BoekZG2yo%2Fz\
        JvNJ%2B526RLmte3tq3FxA90RicCCHmQzI%2FZKR7DQQc08uoLEK&X-Amz-Signature=3b\
        586a473cc0dd6733a928c80f1c1339e6447aa921bde5f54018d08715c71889&X-Amz-Si\
        gnedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-22T06:20:40.204Z"
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
UPDATE_TIME: "2025-02-22T05:22:04.434Z"
EXPIRY_TIME: "2025-02-22T06:21:54.934Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665BYEGL6X%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T052155Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCr4uLxkAkPp2r%2BagNQJvJQ2HzCNnF7a8vI%2FT7lwxAJkQIhAIJUuT6T6uS5PA0z1P0aXXYEtl98%2BtSfeCToK4SN47heKogECOb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyCtGk1SvoYFHnGvlsq3AMT2YUjwv7VnFQNZ9kIylQj8HlF%2Be5wXXLD0pIA%2FR6%2FlgWfRvzelXD547x4u9FJJeXtUiaXWzG9iJb%2FPZty8FPgf9RZN8LOCa3MpNkmayshuu3ejfYwHPbYz4%2FRhZRAJrggMdz1Z3nf1csvaMnXI%2BmJvs07JPd5mWuvFdYJl0%2BNFuiAdPgL1f%2FQUnfjyIYer2w%2Bx5vrSKum86oo3YuOGmVbLifWW22DETP1XfK2V39RWGpBBC%2BQTT6AeJ4Py86SlBAnhREVJgy7B%2BjSPXiVPDmLlwRUm5wD6Wf2aHKEHIPzoMeMiGLHneiQRrR5eeIRpqZL4cI3qWbwGCFFihhLHTIupGkXhYBCTWNCw7nAlU14I%2BLUTASU7jZ6iJMp9z43xpD5laZJlcuJuz725Rp5Yhj34Yr9tj%2BdKsKwFT3SZHWwYke%2FwZdvYVXWqNS%2BKXcH3ua%2FgQ2ziUh0xwIcgEufM9yVyn8kMcVWD8fC27ec%2FdYjz8%2FN%2FMZj06a9PxX%2Bimg8pUF3LZStNDqmLnbuASEymtzJ1wWxP5bPh7SWMnWu7WqmHhuM294S7fSgIXFMtnqL1%2FZ%2FkdM2rUqAyirz4JoNm5YkC%2ByEmPsuXMplBYgKDNaDguKhXxQxcKihqXOBxDCCquW9BjqkAfJn91iZ%2FFKRLi4vKuCU2nlsYdEtOW6LFt5AQTgjR1pGL6DQyvsN2KlmiIuuFFbFlPVqLvQTNOGkkLkD9dAPCwD%2BamNr58IS8dsXpt6tMpfY8rsGZV1Vh%2BbnjmqEapvdtCam83%2BQC933U3aSGOluts7DISfCI%2FJlh8yr%2BcYqWgCsdXiDEhBJiLIidCxsTVRaX6onKIlbr0T43zQYwplAxagips%2Bk&X-Amz-Signature=1e456524d0b75f0ec92e469c5def8aca97b1d63f421981e6571046d1721c8b20&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665BYEGL6X%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T052155Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCr4uLxkAkPp2r%2BagNQJvJQ2HzCNnF7a8vI%2FT7lwxAJkQIhAIJUuT6T6uS5PA0z1P0aXXYEtl98%2BtSfeCToK4SN47heKogECOb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyCtGk1SvoYFHnGvlsq3AMT2YUjwv7VnFQNZ9kIylQj8HlF%2Be5wXXLD0pIA%2FR6%2FlgWfRvzelXD547x4u9FJJeXtUiaXWzG9iJb%2FPZty8FPgf9RZN8LOCa3MpNkmayshuu3ejfYwHPbYz4%2FRhZRAJrggMdz1Z3nf1csvaMnXI%2BmJvs07JPd5mWuvFdYJl0%2BNFuiAdPgL1f%2FQUnfjyIYer2w%2Bx5vrSKum86oo3YuOGmVbLifWW22DETP1XfK2V39RWGpBBC%2BQTT6AeJ4Py86SlBAnhREVJgy7B%2BjSPXiVPDmLlwRUm5wD6Wf2aHKEHIPzoMeMiGLHneiQRrR5eeIRpqZL4cI3qWbwGCFFihhLHTIupGkXhYBCTWNCw7nAlU14I%2BLUTASU7jZ6iJMp9z43xpD5laZJlcuJuz725Rp5Yhj34Yr9tj%2BdKsKwFT3SZHWwYke%2FwZdvYVXWqNS%2BKXcH3ua%2FgQ2ziUh0xwIcgEufM9yVyn8kMcVWD8fC27ec%2FdYjz8%2FN%2FMZj06a9PxX%2Bimg8pUF3LZStNDqmLnbuASEymtzJ1wWxP5bPh7SWMnWu7WqmHhuM294S7fSgIXFMtnqL1%2FZ%2FkdM2rUqAyirz4JoNm5YkC%2ByEmPsuXMplBYgKDNaDguKhXxQxcKihqXOBxDCCquW9BjqkAfJn91iZ%2FFKRLi4vKuCU2nlsYdEtOW6LFt5AQTgjR1pGL6DQyvsN2KlmiIuuFFbFlPVqLvQTNOGkkLkD9dAPCwD%2BamNr58IS8dsXpt6tMpfY8rsGZV1Vh%2BbnjmqEapvdtCam83%2BQC933U3aSGOluts7DISfCI%2FJlh8yr%2BcYqWgCsdXiDEhBJiLIidCxsTVRaX6onKIlbr0T43zQYwplAxagips%2Bk&X-Amz-Signature=ff89549407d2368c7c9ed3eac9c8d237e7786d2c863eac3778a892b63c3b6f6b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665BYEGL6X%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T052155Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCr4uLxkAkPp2r%2BagNQJvJQ2HzCNnF7a8vI%2FT7lwxAJkQIhAIJUuT6T6uS5PA0z1P0aXXYEtl98%2BtSfeCToK4SN47heKogECOb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyCtGk1SvoYFHnGvlsq3AMT2YUjwv7VnFQNZ9kIylQj8HlF%2Be5wXXLD0pIA%2FR6%2FlgWfRvzelXD547x4u9FJJeXtUiaXWzG9iJb%2FPZty8FPgf9RZN8LOCa3MpNkmayshuu3ejfYwHPbYz4%2FRhZRAJrggMdz1Z3nf1csvaMnXI%2BmJvs07JPd5mWuvFdYJl0%2BNFuiAdPgL1f%2FQUnfjyIYer2w%2Bx5vrSKum86oo3YuOGmVbLifWW22DETP1XfK2V39RWGpBBC%2BQTT6AeJ4Py86SlBAnhREVJgy7B%2BjSPXiVPDmLlwRUm5wD6Wf2aHKEHIPzoMeMiGLHneiQRrR5eeIRpqZL4cI3qWbwGCFFihhLHTIupGkXhYBCTWNCw7nAlU14I%2BLUTASU7jZ6iJMp9z43xpD5laZJlcuJuz725Rp5Yhj34Yr9tj%2BdKsKwFT3SZHWwYke%2FwZdvYVXWqNS%2BKXcH3ua%2FgQ2ziUh0xwIcgEufM9yVyn8kMcVWD8fC27ec%2FdYjz8%2FN%2FMZj06a9PxX%2Bimg8pUF3LZStNDqmLnbuASEymtzJ1wWxP5bPh7SWMnWu7WqmHhuM294S7fSgIXFMtnqL1%2FZ%2FkdM2rUqAyirz4JoNm5YkC%2ByEmPsuXMplBYgKDNaDguKhXxQxcKihqXOBxDCCquW9BjqkAfJn91iZ%2FFKRLi4vKuCU2nlsYdEtOW6LFt5AQTgjR1pGL6DQyvsN2KlmiIuuFFbFlPVqLvQTNOGkkLkD9dAPCwD%2BamNr58IS8dsXpt6tMpfY8rsGZV1Vh%2BbnjmqEapvdtCam83%2BQC933U3aSGOluts7DISfCI%2FJlh8yr%2BcYqWgCsdXiDEhBJiLIidCxsTVRaX6onKIlbr0T43zQYwplAxagips%2Bk&X-Amz-Signature=0dd4ed384b06448f3adc8aa178c374018b2048068614a463af8410316089a6cc&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665BYEGL6X%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T052155Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCr4uLxkAkPp2r%2BagNQJvJQ2HzCNnF7a8vI%2FT7lwxAJkQIhAIJUuT6T6uS5PA0z1P0aXXYEtl98%2BtSfeCToK4SN47heKogECOb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyCtGk1SvoYFHnGvlsq3AMT2YUjwv7VnFQNZ9kIylQj8HlF%2Be5wXXLD0pIA%2FR6%2FlgWfRvzelXD547x4u9FJJeXtUiaXWzG9iJb%2FPZty8FPgf9RZN8LOCa3MpNkmayshuu3ejfYwHPbYz4%2FRhZRAJrggMdz1Z3nf1csvaMnXI%2BmJvs07JPd5mWuvFdYJl0%2BNFuiAdPgL1f%2FQUnfjyIYer2w%2Bx5vrSKum86oo3YuOGmVbLifWW22DETP1XfK2V39RWGpBBC%2BQTT6AeJ4Py86SlBAnhREVJgy7B%2BjSPXiVPDmLlwRUm5wD6Wf2aHKEHIPzoMeMiGLHneiQRrR5eeIRpqZL4cI3qWbwGCFFihhLHTIupGkXhYBCTWNCw7nAlU14I%2BLUTASU7jZ6iJMp9z43xpD5laZJlcuJuz725Rp5Yhj34Yr9tj%2BdKsKwFT3SZHWwYke%2FwZdvYVXWqNS%2BKXcH3ua%2FgQ2ziUh0xwIcgEufM9yVyn8kMcVWD8fC27ec%2FdYjz8%2FN%2FMZj06a9PxX%2Bimg8pUF3LZStNDqmLnbuASEymtzJ1wWxP5bPh7SWMnWu7WqmHhuM294S7fSgIXFMtnqL1%2FZ%2FkdM2rUqAyirz4JoNm5YkC%2ByEmPsuXMplBYgKDNaDguKhXxQxcKihqXOBxDCCquW9BjqkAfJn91iZ%2FFKRLi4vKuCU2nlsYdEtOW6LFt5AQTgjR1pGL6DQyvsN2KlmiIuuFFbFlPVqLvQTNOGkkLkD9dAPCwD%2BamNr58IS8dsXpt6tMpfY8rsGZV1Vh%2BbnjmqEapvdtCam83%2BQC933U3aSGOluts7DISfCI%2FJlh8yr%2BcYqWgCsdXiDEhBJiLIidCxsTVRaX6onKIlbr0T43zQYwplAxagips%2Bk&X-Amz-Signature=f5ab0e929d9bafd18a5593551d020873400ec486fe84deed05ebe86c24721895&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665BYEGL6X%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T052155Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCr4uLxkAkPp2r%2BagNQJvJQ2HzCNnF7a8vI%2FT7lwxAJkQIhAIJUuT6T6uS5PA0z1P0aXXYEtl98%2BtSfeCToK4SN47heKogECOb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyCtGk1SvoYFHnGvlsq3AMT2YUjwv7VnFQNZ9kIylQj8HlF%2Be5wXXLD0pIA%2FR6%2FlgWfRvzelXD547x4u9FJJeXtUiaXWzG9iJb%2FPZty8FPgf9RZN8LOCa3MpNkmayshuu3ejfYwHPbYz4%2FRhZRAJrggMdz1Z3nf1csvaMnXI%2BmJvs07JPd5mWuvFdYJl0%2BNFuiAdPgL1f%2FQUnfjyIYer2w%2Bx5vrSKum86oo3YuOGmVbLifWW22DETP1XfK2V39RWGpBBC%2BQTT6AeJ4Py86SlBAnhREVJgy7B%2BjSPXiVPDmLlwRUm5wD6Wf2aHKEHIPzoMeMiGLHneiQRrR5eeIRpqZL4cI3qWbwGCFFihhLHTIupGkXhYBCTWNCw7nAlU14I%2BLUTASU7jZ6iJMp9z43xpD5laZJlcuJuz725Rp5Yhj34Yr9tj%2BdKsKwFT3SZHWwYke%2FwZdvYVXWqNS%2BKXcH3ua%2FgQ2ziUh0xwIcgEufM9yVyn8kMcVWD8fC27ec%2FdYjz8%2FN%2FMZj06a9PxX%2Bimg8pUF3LZStNDqmLnbuASEymtzJ1wWxP5bPh7SWMnWu7WqmHhuM294S7fSgIXFMtnqL1%2FZ%2FkdM2rUqAyirz4JoNm5YkC%2ByEmPsuXMplBYgKDNaDguKhXxQxcKihqXOBxDCCquW9BjqkAfJn91iZ%2FFKRLi4vKuCU2nlsYdEtOW6LFt5AQTgjR1pGL6DQyvsN2KlmiIuuFFbFlPVqLvQTNOGkkLkD9dAPCwD%2BamNr58IS8dsXpt6tMpfY8rsGZV1Vh%2BbnjmqEapvdtCam83%2BQC933U3aSGOluts7DISfCI%2FJlh8yr%2BcYqWgCsdXiDEhBJiLIidCxsTVRaX6onKIlbr0T43zQYwplAxagips%2Bk&X-Amz-Signature=6f27e81773097015340c1a93c651295ce2cc14fcbbd733004c162cde776fc99d&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VSUZO4ZX%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T052156Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDBjGZ8EN3LQ09dHZKK7Hr0uo%2FNEc9oFLcWV7fKs%2FS4xwIgPVBWdtdoYBFyOE5Zj6d1hEOSX3ptH%2BG%2BsQ6LD6nRxfgqiAQI5v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLaD5n7kJTOOzeUmGSrcAwr11FiNo6gt7iUgCbecbDO8M7wOEec7n3AAfV02o9%2BMJnMdVhTEaJo4PKgsE4yp2NzcmyuDQHSO9Go9nJco1hCsDRZ%2FcrghKvosKvJoNsVymamPYQEyhJqW3V9Ltu%2BIDaQziNZWbQSYBqq3ig%2FakM54qneXOdu%2B4gjW9uNbmaVLkASYYIPHX14YOJ2%2FMWHOYAi%2FmL%2B124hqEXGexVqx6sJ0x7Xt5iOFfOnyWfit9gwMZlS8HtF4OUauYb4sZud81lqmYfjtNUkRYsbSFwJ3FWX%2FDmFY%2Fba%2BezvlPdXOBVbW0tEe6La%2B8qh%2FPjIAT7jvoqJ%2BGeCzdQnC9Gyds1LTc%2Fi0JUviDcBkmq4g7Q3fL%2BmUEAxGPWnG4LwRUWRYAfSICNDxBxCxYb23c6GDjgfpgKneknIvM7PI0RMIt8qPsPbW8Lp3oWaHUsY4H4MK9mYlQVfWHNi%2BPyWr%2B5WXebmPEuXB11%2BtnqImtfSuc4kcV%2FzEKhPLRECfkGuE09kselkAQ%2BgdzzHTA6XxCAEUArhgMZNaWuisMF3NOeJxoTmlH%2F0OxCKtRPQa1w%2FEFdWFG4YOwHzvo8EthSl2QFHl9RKuQjkxzAjFVOqZEbCI6%2Fz8o5NPrBD%2ByMlWVCSI%2FdtDMN6q5b0GOqUBdmf%2BPVfx3vsbaB6LIxSIQO0JiOUjEiBEiXtPNCwOJA%2Fh6HWe9CPNQXXTRH1vD3dfYi8YN4ITAyp%2FXEjpT0CkeKZv7k8a9QJ6LevmMUQtp3R9ovHtVNYhxAcOHuvApDLpEmsFYOsQCWHwo4pCCqNWZmT10Ddo8PuyQDlYM5mZ7l4f%2Bm5FCxCUjFAcON5AmBHT0KqyGhQym0Ds8RoJFjM81EmMER%2BG&X-Amz-Signature=1a1aa852b7e80384e0a38592f455b95864f2308fd4cda9eeacb341e0d0d3a6bf&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XTFATGZS%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T052157Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIHiUSADkKXuGCkMGXdRzNdO5hUGpRwfEAI1Er3w16gLwAiEA97rAguGAoAH2f8tslQ713LVYlIHTe1QOeRalrAujNNQqiAQI5v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDF2Y%2B2zJNFf3xiwJqircA14N%2Bl2AC7dgDr13YuFy36J0uahAP%2BvlUcwCmH2mUxpQM7LDtGi3sQgfGn2DJ%2BSX1nyEU0f1xKdUref5dkZ78JTRpxFHaFNFsIRXXliA2GhIWBX%2FMPf2YBKpp%2F3c8Ydx%2FbbDyPwVK1FQE0MwQEhpok6Qi3MQCKeHhp4CQdi4%2Fbn%2FTgTeeVXIN7vokvf0rLaJRCR4c%2Foko2Qq1gMJJPqT3S%2B7aHGd%2Fp3b1R6WNt4AB3xrn%2FLgCwUJJIpiLURP7nHX%2Fo6PjGR%2BQmry%2FFK472X2fnmh77IhSFVPn3CgypoS5U3o4SiNKVoFzpD0Equ7DlTr491xRul2A%2FsvRAAeQo11LkltjyM9M4E%2FNEd%2FbRW4QnUQ99nEl%2FhngUVrkTFbraAv%2FSDWSSICieXIYjY0rLjL5%2Bf5zABIh%2BUYAziUN9rxneSQVplL3WeCM%2BquhYb37Jk1ClNUwtX%2FwpPQ18MQj3lWnzXrztVfBHGLFod8XlaQlP90fI86cRDTXH8LT0xVkjAbJgCdLxQ2gmGZBJ%2BjjJUGqrbVQ0uZL0F73z5WB59XUjqHXojCVAuN1r6RpexMTbiBs%2B4ztE1yze9A7gzT3MPROaMMehayCfZUmKpaVmr%2FwRRYWr287ptv7B2rXvXYMLiq5b0GOqUB2RPVtNTThoIH5lB1ZBMmnlEhKDCTvddShnGyxdcqAbWghyzFRwnR0HMNWfSkcg6WAMTHhZwlLHoFbG%2FjdFLYh%2Bk20r96A7%2F24cJdf9g%2FvWm9FSzGeZkX2jYx9gsW%2FSUhQeY%2BLBFkJhZjvsNNXjgPvdkwijufkxYU2m6ji%2F49nvyusJrS9xSGQBdZnFdOWPDMxIwh83QXiolxf0qrdchWSYlWZnqC&X-Amz-Signature=3117bd11d63c80ea3a714335787d0d54ff19217dd87abd315c4d926f1a8d879f&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665BYEGL6X%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T052155Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCr4uLxkAkPp2r%2BagNQJvJQ2HzCNnF7a8vI%2FT7lwxAJkQIhAIJUuT6T6uS5PA0z1P0aXXYEtl98%2BtSfeCToK4SN47heKogECOb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyCtGk1SvoYFHnGvlsq3AMT2YUjwv7VnFQNZ9kIylQj8HlF%2Be5wXXLD0pIA%2FR6%2FlgWfRvzelXD547x4u9FJJeXtUiaXWzG9iJb%2FPZty8FPgf9RZN8LOCa3MpNkmayshuu3ejfYwHPbYz4%2FRhZRAJrggMdz1Z3nf1csvaMnXI%2BmJvs07JPd5mWuvFdYJl0%2BNFuiAdPgL1f%2FQUnfjyIYer2w%2Bx5vrSKum86oo3YuOGmVbLifWW22DETP1XfK2V39RWGpBBC%2BQTT6AeJ4Py86SlBAnhREVJgy7B%2BjSPXiVPDmLlwRUm5wD6Wf2aHKEHIPzoMeMiGLHneiQRrR5eeIRpqZL4cI3qWbwGCFFihhLHTIupGkXhYBCTWNCw7nAlU14I%2BLUTASU7jZ6iJMp9z43xpD5laZJlcuJuz725Rp5Yhj34Yr9tj%2BdKsKwFT3SZHWwYke%2FwZdvYVXWqNS%2BKXcH3ua%2FgQ2ziUh0xwIcgEufM9yVyn8kMcVWD8fC27ec%2FdYjz8%2FN%2FMZj06a9PxX%2Bimg8pUF3LZStNDqmLnbuASEymtzJ1wWxP5bPh7SWMnWu7WqmHhuM294S7fSgIXFMtnqL1%2FZ%2FkdM2rUqAyirz4JoNm5YkC%2ByEmPsuXMplBYgKDNaDguKhXxQxcKihqXOBxDCCquW9BjqkAfJn91iZ%2FFKRLi4vKuCU2nlsYdEtOW6LFt5AQTgjR1pGL6DQyvsN2KlmiIuuFFbFlPVqLvQTNOGkkLkD9dAPCwD%2BamNr58IS8dsXpt6tMpfY8rsGZV1Vh%2BbnjmqEapvdtCam83%2BQC933U3aSGOluts7DISfCI%2FJlh8yr%2BcYqWgCsdXiDEhBJiLIidCxsTVRaX6onKIlbr0T43zQYwplAxagips%2Bk&X-Amz-Signature=5a983507c3e2bd4f2424902c113ced5fca00afca05f9f8b4ac2d7d9211a15502&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665BYEGL6X%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T052155Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCr4uLxkAkPp2r%2BagNQJvJQ2HzCNnF7a8vI%2FT7lwxAJkQIhAIJUuT6T6uS5PA0z1P0aXXYEtl98%2BtSfeCToK4SN47heKogECOb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyCtGk1SvoYFHnGvlsq3AMT2YUjwv7VnFQNZ9kIylQj8HlF%2Be5wXXLD0pIA%2FR6%2FlgWfRvzelXD547x4u9FJJeXtUiaXWzG9iJb%2FPZty8FPgf9RZN8LOCa3MpNkmayshuu3ejfYwHPbYz4%2FRhZRAJrggMdz1Z3nf1csvaMnXI%2BmJvs07JPd5mWuvFdYJl0%2BNFuiAdPgL1f%2FQUnfjyIYer2w%2Bx5vrSKum86oo3YuOGmVbLifWW22DETP1XfK2V39RWGpBBC%2BQTT6AeJ4Py86SlBAnhREVJgy7B%2BjSPXiVPDmLlwRUm5wD6Wf2aHKEHIPzoMeMiGLHneiQRrR5eeIRpqZL4cI3qWbwGCFFihhLHTIupGkXhYBCTWNCw7nAlU14I%2BLUTASU7jZ6iJMp9z43xpD5laZJlcuJuz725Rp5Yhj34Yr9tj%2BdKsKwFT3SZHWwYke%2FwZdvYVXWqNS%2BKXcH3ua%2FgQ2ziUh0xwIcgEufM9yVyn8kMcVWD8fC27ec%2FdYjz8%2FN%2FMZj06a9PxX%2Bimg8pUF3LZStNDqmLnbuASEymtzJ1wWxP5bPh7SWMnWu7WqmHhuM294S7fSgIXFMtnqL1%2FZ%2FkdM2rUqAyirz4JoNm5YkC%2ByEmPsuXMplBYgKDNaDguKhXxQxcKihqXOBxDCCquW9BjqkAfJn91iZ%2FFKRLi4vKuCU2nlsYdEtOW6LFt5AQTgjR1pGL6DQyvsN2KlmiIuuFFbFlPVqLvQTNOGkkLkD9dAPCwD%2BamNr58IS8dsXpt6tMpfY8rsGZV1Vh%2BbnjmqEapvdtCam83%2BQC933U3aSGOluts7DISfCI%2FJlh8yr%2BcYqWgCsdXiDEhBJiLIidCxsTVRaX6onKIlbr0T43zQYwplAxagips%2Bk&X-Amz-Signature=64c572e9f79a1686c37e838909e3c24c91e8ac2e408958e205be7c948cd0fa99&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665BYEGL6X%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T052155Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCr4uLxkAkPp2r%2BagNQJvJQ2HzCNnF7a8vI%2FT7lwxAJkQIhAIJUuT6T6uS5PA0z1P0aXXYEtl98%2BtSfeCToK4SN47heKogECOb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyCtGk1SvoYFHnGvlsq3AMT2YUjwv7VnFQNZ9kIylQj8HlF%2Be5wXXLD0pIA%2FR6%2FlgWfRvzelXD547x4u9FJJeXtUiaXWzG9iJb%2FPZty8FPgf9RZN8LOCa3MpNkmayshuu3ejfYwHPbYz4%2FRhZRAJrggMdz1Z3nf1csvaMnXI%2BmJvs07JPd5mWuvFdYJl0%2BNFuiAdPgL1f%2FQUnfjyIYer2w%2Bx5vrSKum86oo3YuOGmVbLifWW22DETP1XfK2V39RWGpBBC%2BQTT6AeJ4Py86SlBAnhREVJgy7B%2BjSPXiVPDmLlwRUm5wD6Wf2aHKEHIPzoMeMiGLHneiQRrR5eeIRpqZL4cI3qWbwGCFFihhLHTIupGkXhYBCTWNCw7nAlU14I%2BLUTASU7jZ6iJMp9z43xpD5laZJlcuJuz725Rp5Yhj34Yr9tj%2BdKsKwFT3SZHWwYke%2FwZdvYVXWqNS%2BKXcH3ua%2FgQ2ziUh0xwIcgEufM9yVyn8kMcVWD8fC27ec%2FdYjz8%2FN%2FMZj06a9PxX%2Bimg8pUF3LZStNDqmLnbuASEymtzJ1wWxP5bPh7SWMnWu7WqmHhuM294S7fSgIXFMtnqL1%2FZ%2FkdM2rUqAyirz4JoNm5YkC%2ByEmPsuXMplBYgKDNaDguKhXxQxcKihqXOBxDCCquW9BjqkAfJn91iZ%2FFKRLi4vKuCU2nlsYdEtOW6LFt5AQTgjR1pGL6DQyvsN2KlmiIuuFFbFlPVqLvQTNOGkkLkD9dAPCwD%2BamNr58IS8dsXpt6tMpfY8rsGZV1Vh%2BbnjmqEapvdtCam83%2BQC933U3aSGOluts7DISfCI%2FJlh8yr%2BcYqWgCsdXiDEhBJiLIidCxsTVRaX6onKIlbr0T43zQYwplAxagips%2Bk&X-Amz-Signature=108b1d89a68283418234500305eb1a4108bd2853cee48925fe1f02503c5dece6&X-Amz-SignedHeaders=host&x-id=GetObject)


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

