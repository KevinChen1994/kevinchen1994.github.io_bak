---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4666J3CC6YO%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250209T042625Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCH3qNHhMfa%2BkHdl%2B\
  h1zvSj7mrsCOwRizRZxytqwKSNuACIQCJvsLZfxxVcCJ9le53eNXP6GIsMrhfyKxKY27uQzl2gCqI\
  BAid%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM6HDppAdL%2BIZDUpF\
  %2BKtwD9rR7kaABMJib337BguC6a%2Fl5STVPDb98AsVi%2BBzGxES77fiyuD94OD7SQ0hY7rp2F8\
  K7OeamQYFkjA9k0WuXjc2z%2Bk5ZpCuQFNnUqa0PlFf4ohmrqO2%2FMer1LG7qViFiHi82hloIuEJ\
  OhwxkXQ1P3oAvAPAbWoCxL3J2PapqEmY3Af3Coq0c%2BlJJeLtpFIFS%2F6tdDmFUPbpusW%2BFJr\
  0WfFGYqmNPtFFk%2FyRnsDjRLtci8HTTEvOCGg2tFY26c9LDjz4rwO3eM1L%2Fn6IBeoCV1FRKFba\
  IaA9TtXRF365Fn7SqeVT1D9bVliY5Yj5Q%2FruBySiE%2Bi1K6xd%2BU9zAKIWX8lPiVd%2BnihoZ\
  NxhaQMrhofMqpecKTPlvXpYZ3D%2Fy%2BDik95%2BKNpg2hMHf1HV6Ba0uGlFRgBiCNOZsibaUPe9\
  Y7sisv06Z3fqWMeaftS3iVJYwZFUfNf8aJ2RRjIgNZY1hYtRAE1vZ%2Bwe7s7LFRiECxpbLRSgUKG\
  y%2BFfaM%2FRCOMU%2B%2F08eVheEyk%2BhiN9AgYhLh%2B3IR3%2BRvZIhbVRHI6NqsBRQMxeFwK\
  cExSKXvdwrVE0vXIeLn3%2F8XOv0YwwcLgeA4yK4xhinVKk3C0DeAiYJL77PXu7g008gRLkLCOUww\
  x7%2BgvQY6pgEi4WKj1o4cFZeoZRzrxJejQtW6QopzDbZJI%2FZPot8MqL2iGlbtoaraj6tKxXI%2\
  F8lAVBJYf76s1XrGODIEbs9ZRRza1QzvGnykb1lNEvQoXZLK5NKe0ZanvIQlhLjnIE7iuT8Fzb5UW\
  za5gzlfXptOPPPCCZFUET54p4XyL19DR%2BAm%2Bxc6OsrCS6zmnpBJKY%2BbwZCQSecqDiE5QbkK\
  Qt6vccyAJr3RA&X-Amz-Signature=cc3d5271ac9bb3dd5b4cfaf5d421bad0160db36efca604a\
  0718760a751d6922f&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4662B4PCNZV%2F20250209%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250209T042517Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIQCn6mcV%2Feqj0ecieMfBU6qlaRH7fOPANcSI7p9jEn7q3wIgCmWZgBuZ1a27B7FudjqF\
        %2FWZ7agtUhlV8BEBT1cv1%2BJsqiAQInP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw\
        2Mzc0MjMxODM4MDUiDMdtYiYMT3U7mQdq0ircA0AIZg%2FfiAO8kb%2BMhpv%2Fm8IofHek\
        wOBTyTNT3wUhc9gLKsOI2iJG6CvJ9%2BNHmoLLMb2478j%2FJErCzgozZHElArmqvN95Aqh\
        fxYEfw3jP4NV%2BN65bQgeaMY%2Fe3FVOik4SWPGXp%2BV06CS%2BJuzpn%2BFYFLqdnFuF\
        Z1eFBmOvYIcqwF6mmOTnrZNQA2bhGYQv1mms554Qd5MzmBLYMzGaWty7KIw5bVtlSaYDO4Q\
        iLmfpCS0ieE8fRPX9rpaD4venj1WWVG7s0jUG7%2B5WoGsxtm4FbqBNTSyJKgV8ANk34ZAl\
        2ZlF5QgbwT%2F6y2f%2FzNwtWp9YkabHsGj5mvPaFg4IIKGxiCiEomC1QCL1gDZnc9zaD%2\
        FdzoZQn0oeniWRULMdrV8elgCCt6qMLX5rhGI%2F7xbqPE0yqX0vImtVQl%2F1Lyo9GO39M\
        TAdo57STfeTxlZ1lRoPfK6SWkzepyXD7W2%2FhJD7FciqCiyj3O1c9nrBYytuyHuPMpxW%2\
        FeAU00ki3JgYX0LubvqwxVuaRqKupITz0uP6YX4u0%2BRvT6fyYyfXcaaKiRXxpi4GRC6ts\
        53v7VxC8yBYLq%2Bmq4fY7z4%2Bncv58pXsH2p34TfUCb2EqvhRIo87vcRbrM7IbHNDFGwZ\
        LT7TrMLe%2FoL0GOqUB6t1B3DfoTVQGCPtM0tEEKg69BxJJVU%2BxtHhC%2BNUlA%2B1cnP\
        CWOiLETl8X%2BNADH8a7iE6ac0xkTxPxno32LR3WqeZgz3sGCS45%2FuWyaWuXczaLk4B%2\
        FjKmbD19NxL4TD2HqEHV%2FUkGN%2BcRGNx1%2FjS%2BrHYpUONJZz3xQRNdUQE3Bi2UGE%\
        2BMlftYL73vbB03Puym5Fq3flki934pZI6nCfYYCPRSnN4is&X-Amz-Signature=113e68\
        134609458abeb721052a76a5a1b0487546d360c385d9b732ce9132542d&X-Amz-Signed\
        Headers=host&x-id=GetObject"
      expiry_time: "2025-02-09T05:25:16.952Z"
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
UPDATE_TIME: "2025-02-09T04:26:29.198Z"
EXPIRY_TIME: "2025-02-09T05:26:23.274Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UHPGUR3I%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T042623Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCID1xjRy%2BUV7loPiJ354vDu5S04X07QV8HMT67sJNJPSgAiEAglcgOHF9urfvGLlc2mglITg6QRvXeOXa%2BpJFiB6YstsqiAQInf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDEV3P2XtXaxM1xA6mircA1a%2FLHASFbCuNn9Sewu4asu3lz6CwScmdeR3U%2Fd8umDpsftAS3clwE4JZSOaABPHc4WtnlaUYKXVEQ5qzrMH0K4aqWnSQ7VMCbGVzBLwy6vYDqZDYhpmJYcaDr0GKS%2BfT4ApK1pX6oYiHUGMitEmi%2BGru2mlob6ilTnczyztDWrTXBaaa3IZmhY0sRUBwPNUL8l%2B9ft%2BFxr3f%2BktHRy1urkW8V6fcloWSuxKp5OnCEKzeicFLk5TRPQF9mZk647gpEDTCmbbkYt9NwP51R%2Fm6EvWzczM3d%2FUp0fK%2BdGGImYvZVnsU9oV51CxJnnN8S58hn0M9fIDvXjxHPTC7bcOYaX9Rta9zah3ymzZ1VaHK3s%2FpGWw%2FtP3WLrtDmfXsheAowmRUm7J73Udh2q4Lnw1jETk%2BiYoUXZxZYSYffdxTELCfPA4Cd0BRvKRaYr6Gq6yQX6R%2BeruML34XE%2BZ0vbq%2BKXTohEGJ67VB%2B%2FHsTrmDy6re9WWkuUO4zxMcAT9gf2G%2FcRcrA5z%2FujvEpSNT%2BkHxTWY5snUiaNHNVLOn5m%2FVbLFvZhOC%2FKVyvjb1CW7t57cz%2FLGsrMDRC7ke1u945t%2Fq4NWAJpa8BTFaOUyo5CsUZkqJhTgpHVaarlsmM2%2FMJm%2FoL0GOqUB7Hat2I4yM1hUK%2BpLyJ2MdR%2FnUPO3xM%2FkFrUqKZPtN9YUanKrAMX%2F5ZQDCbYjuIJXxnPr%2F5BsT3WuEtirYHXBLx1LY3qWJHBtrel9mQpZxAajmpfxXQYlPzPtaMi7G1kejSascabbV8HoMMLWqBsJBai1KkwUfUuz6TWdtsjUKMTUuocCOxg0mqlkoJcvgqIwVrt%2Fc85tai2GNcIU9joVgDPuX0IU&X-Amz-Signature=c087a0f96201a3de6bc0c1cc739672fd2a12c2858d498dab744a890fd7c63dbf&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UHPGUR3I%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T042623Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCID1xjRy%2BUV7loPiJ354vDu5S04X07QV8HMT67sJNJPSgAiEAglcgOHF9urfvGLlc2mglITg6QRvXeOXa%2BpJFiB6YstsqiAQInf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDEV3P2XtXaxM1xA6mircA1a%2FLHASFbCuNn9Sewu4asu3lz6CwScmdeR3U%2Fd8umDpsftAS3clwE4JZSOaABPHc4WtnlaUYKXVEQ5qzrMH0K4aqWnSQ7VMCbGVzBLwy6vYDqZDYhpmJYcaDr0GKS%2BfT4ApK1pX6oYiHUGMitEmi%2BGru2mlob6ilTnczyztDWrTXBaaa3IZmhY0sRUBwPNUL8l%2B9ft%2BFxr3f%2BktHRy1urkW8V6fcloWSuxKp5OnCEKzeicFLk5TRPQF9mZk647gpEDTCmbbkYt9NwP51R%2Fm6EvWzczM3d%2FUp0fK%2BdGGImYvZVnsU9oV51CxJnnN8S58hn0M9fIDvXjxHPTC7bcOYaX9Rta9zah3ymzZ1VaHK3s%2FpGWw%2FtP3WLrtDmfXsheAowmRUm7J73Udh2q4Lnw1jETk%2BiYoUXZxZYSYffdxTELCfPA4Cd0BRvKRaYr6Gq6yQX6R%2BeruML34XE%2BZ0vbq%2BKXTohEGJ67VB%2B%2FHsTrmDy6re9WWkuUO4zxMcAT9gf2G%2FcRcrA5z%2FujvEpSNT%2BkHxTWY5snUiaNHNVLOn5m%2FVbLFvZhOC%2FKVyvjb1CW7t57cz%2FLGsrMDRC7ke1u945t%2Fq4NWAJpa8BTFaOUyo5CsUZkqJhTgpHVaarlsmM2%2FMJm%2FoL0GOqUB7Hat2I4yM1hUK%2BpLyJ2MdR%2FnUPO3xM%2FkFrUqKZPtN9YUanKrAMX%2F5ZQDCbYjuIJXxnPr%2F5BsT3WuEtirYHXBLx1LY3qWJHBtrel9mQpZxAajmpfxXQYlPzPtaMi7G1kejSascabbV8HoMMLWqBsJBai1KkwUfUuz6TWdtsjUKMTUuocCOxg0mqlkoJcvgqIwVrt%2Fc85tai2GNcIU9joVgDPuX0IU&X-Amz-Signature=987436458e61216056f1ba0a53442949e0df0cba2676fe50ec5e244c14085be0&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UHPGUR3I%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T042623Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCID1xjRy%2BUV7loPiJ354vDu5S04X07QV8HMT67sJNJPSgAiEAglcgOHF9urfvGLlc2mglITg6QRvXeOXa%2BpJFiB6YstsqiAQInf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDEV3P2XtXaxM1xA6mircA1a%2FLHASFbCuNn9Sewu4asu3lz6CwScmdeR3U%2Fd8umDpsftAS3clwE4JZSOaABPHc4WtnlaUYKXVEQ5qzrMH0K4aqWnSQ7VMCbGVzBLwy6vYDqZDYhpmJYcaDr0GKS%2BfT4ApK1pX6oYiHUGMitEmi%2BGru2mlob6ilTnczyztDWrTXBaaa3IZmhY0sRUBwPNUL8l%2B9ft%2BFxr3f%2BktHRy1urkW8V6fcloWSuxKp5OnCEKzeicFLk5TRPQF9mZk647gpEDTCmbbkYt9NwP51R%2Fm6EvWzczM3d%2FUp0fK%2BdGGImYvZVnsU9oV51CxJnnN8S58hn0M9fIDvXjxHPTC7bcOYaX9Rta9zah3ymzZ1VaHK3s%2FpGWw%2FtP3WLrtDmfXsheAowmRUm7J73Udh2q4Lnw1jETk%2BiYoUXZxZYSYffdxTELCfPA4Cd0BRvKRaYr6Gq6yQX6R%2BeruML34XE%2BZ0vbq%2BKXTohEGJ67VB%2B%2FHsTrmDy6re9WWkuUO4zxMcAT9gf2G%2FcRcrA5z%2FujvEpSNT%2BkHxTWY5snUiaNHNVLOn5m%2FVbLFvZhOC%2FKVyvjb1CW7t57cz%2FLGsrMDRC7ke1u945t%2Fq4NWAJpa8BTFaOUyo5CsUZkqJhTgpHVaarlsmM2%2FMJm%2FoL0GOqUB7Hat2I4yM1hUK%2BpLyJ2MdR%2FnUPO3xM%2FkFrUqKZPtN9YUanKrAMX%2F5ZQDCbYjuIJXxnPr%2F5BsT3WuEtirYHXBLx1LY3qWJHBtrel9mQpZxAajmpfxXQYlPzPtaMi7G1kejSascabbV8HoMMLWqBsJBai1KkwUfUuz6TWdtsjUKMTUuocCOxg0mqlkoJcvgqIwVrt%2Fc85tai2GNcIU9joVgDPuX0IU&X-Amz-Signature=a0d81bba5aa72d1fb142cf4fb6e3cf5b5149e9a5e319a8660c40f5b90deacf80&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UHPGUR3I%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T042623Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCID1xjRy%2BUV7loPiJ354vDu5S04X07QV8HMT67sJNJPSgAiEAglcgOHF9urfvGLlc2mglITg6QRvXeOXa%2BpJFiB6YstsqiAQInf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDEV3P2XtXaxM1xA6mircA1a%2FLHASFbCuNn9Sewu4asu3lz6CwScmdeR3U%2Fd8umDpsftAS3clwE4JZSOaABPHc4WtnlaUYKXVEQ5qzrMH0K4aqWnSQ7VMCbGVzBLwy6vYDqZDYhpmJYcaDr0GKS%2BfT4ApK1pX6oYiHUGMitEmi%2BGru2mlob6ilTnczyztDWrTXBaaa3IZmhY0sRUBwPNUL8l%2B9ft%2BFxr3f%2BktHRy1urkW8V6fcloWSuxKp5OnCEKzeicFLk5TRPQF9mZk647gpEDTCmbbkYt9NwP51R%2Fm6EvWzczM3d%2FUp0fK%2BdGGImYvZVnsU9oV51CxJnnN8S58hn0M9fIDvXjxHPTC7bcOYaX9Rta9zah3ymzZ1VaHK3s%2FpGWw%2FtP3WLrtDmfXsheAowmRUm7J73Udh2q4Lnw1jETk%2BiYoUXZxZYSYffdxTELCfPA4Cd0BRvKRaYr6Gq6yQX6R%2BeruML34XE%2BZ0vbq%2BKXTohEGJ67VB%2B%2FHsTrmDy6re9WWkuUO4zxMcAT9gf2G%2FcRcrA5z%2FujvEpSNT%2BkHxTWY5snUiaNHNVLOn5m%2FVbLFvZhOC%2FKVyvjb1CW7t57cz%2FLGsrMDRC7ke1u945t%2Fq4NWAJpa8BTFaOUyo5CsUZkqJhTgpHVaarlsmM2%2FMJm%2FoL0GOqUB7Hat2I4yM1hUK%2BpLyJ2MdR%2FnUPO3xM%2FkFrUqKZPtN9YUanKrAMX%2F5ZQDCbYjuIJXxnPr%2F5BsT3WuEtirYHXBLx1LY3qWJHBtrel9mQpZxAajmpfxXQYlPzPtaMi7G1kejSascabbV8HoMMLWqBsJBai1KkwUfUuz6TWdtsjUKMTUuocCOxg0mqlkoJcvgqIwVrt%2Fc85tai2GNcIU9joVgDPuX0IU&X-Amz-Signature=1ddbfb26b4b73310e6645c3991ddc6ec2adc9fb03fa78d0f3f48eea76f12c228&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UHPGUR3I%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T042623Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCID1xjRy%2BUV7loPiJ354vDu5S04X07QV8HMT67sJNJPSgAiEAglcgOHF9urfvGLlc2mglITg6QRvXeOXa%2BpJFiB6YstsqiAQInf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDEV3P2XtXaxM1xA6mircA1a%2FLHASFbCuNn9Sewu4asu3lz6CwScmdeR3U%2Fd8umDpsftAS3clwE4JZSOaABPHc4WtnlaUYKXVEQ5qzrMH0K4aqWnSQ7VMCbGVzBLwy6vYDqZDYhpmJYcaDr0GKS%2BfT4ApK1pX6oYiHUGMitEmi%2BGru2mlob6ilTnczyztDWrTXBaaa3IZmhY0sRUBwPNUL8l%2B9ft%2BFxr3f%2BktHRy1urkW8V6fcloWSuxKp5OnCEKzeicFLk5TRPQF9mZk647gpEDTCmbbkYt9NwP51R%2Fm6EvWzczM3d%2FUp0fK%2BdGGImYvZVnsU9oV51CxJnnN8S58hn0M9fIDvXjxHPTC7bcOYaX9Rta9zah3ymzZ1VaHK3s%2FpGWw%2FtP3WLrtDmfXsheAowmRUm7J73Udh2q4Lnw1jETk%2BiYoUXZxZYSYffdxTELCfPA4Cd0BRvKRaYr6Gq6yQX6R%2BeruML34XE%2BZ0vbq%2BKXTohEGJ67VB%2B%2FHsTrmDy6re9WWkuUO4zxMcAT9gf2G%2FcRcrA5z%2FujvEpSNT%2BkHxTWY5snUiaNHNVLOn5m%2FVbLFvZhOC%2FKVyvjb1CW7t57cz%2FLGsrMDRC7ke1u945t%2Fq4NWAJpa8BTFaOUyo5CsUZkqJhTgpHVaarlsmM2%2FMJm%2FoL0GOqUB7Hat2I4yM1hUK%2BpLyJ2MdR%2FnUPO3xM%2FkFrUqKZPtN9YUanKrAMX%2F5ZQDCbYjuIJXxnPr%2F5BsT3WuEtirYHXBLx1LY3qWJHBtrel9mQpZxAajmpfxXQYlPzPtaMi7G1kejSascabbV8HoMMLWqBsJBai1KkwUfUuz6TWdtsjUKMTUuocCOxg0mqlkoJcvgqIwVrt%2Fc85tai2GNcIU9joVgDPuX0IU&X-Amz-Signature=656088b189c6c3a9fe6fb200a04b8edc50559a128fd2203d261ced80c3f66159&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666LDP3K4S%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T042624Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQChnqwMJwKRgGMSV4LhtG1d5X8uQudmbv4VT3d%2BYjGPNgIhAI7Yry4mepEq1RUv1GnPnu%2FraSTSiG99v9etofNKoNrdKogECJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwKjuK8%2BgebYRY8Ogwq3APS6GW0XQD3MBKMOGnDLeSx1og6HxYqgrZaBRPw7z9pnAZazrBi6aqounYGXOC72uKQSmzh0%2FN%2BtrCiFHQPIubN%2FhLvW0M%2FJey7v9Lv%2BS5unFWtIaJjKDOWnClZAk3GdXQLvpOTDyjCHShhbyzvRNAX8npZLM2D0%2BjJD8iEEr9QkLripYGz7oDUF%2BuiKhLY2fh8qa%2BjHr1FTfhGqCAzGf%2BFM3o5YdatiNrao2ISlpByyCEA0OyKaF7jYSozMqHF%2B9Fik19WwEy%2FLxaqSwGTV1utVAbFil%2BPvuDZhX3GiJE%2Fj1EQg63Asx9AOee%2BMz%2FOruB9kgR%2FvpDEMF%2BXEDvkVANPBjVqvTu244TEF3vfSBMYfZmjmz4d15JSsoYYgRILHLZirW%2F2QAbJwuP62uDfE47oDZQzlyh%2F6N4ssmbAfpve00gTMUhNh34RNmZipsy6kz3LFOH%2BvIxJUwjFnyUnX2EHoUdWCL5CMxXdxw6W3IqX2f6msU966VZqU6C8IW9njBrx%2Fuz4MNz7RALmGyvwOTkUbqxG0%2BwiAHGTTnTQAPTIHf6Wjq4XFwgHz%2FWwHxKN4qiV4IWTRh4JkR16AbYBtraDrweJkHRqJjk6rMRAa084TIbIWY2lxWaXE1MwmDDqvqC9BjqkAXk0ccTrIrAU2dkGq5ZR%2BnVu51Eah2ylXjRQ1wRSyrEZqLl5%2B77X%2Bi8YFI%2FE%2Fh2dg2HNcnqH%2FeRT%2FNm38k6LCmfyPflFJEOBjxmkKvMEQwZcTb4xkmTrQtt%2FWQyG3azfmL7rpd%2B4txcCJU2Si706OdG%2FUhq0pgaOMhae0UXhcyzi1BMJZN8NoTunqbV%2FqPIef74e342Vgjm2Oo86WEfZKDJfAE8j&X-Amz-Signature=f0f3f24348b0e90a9d5f1baa3892255b065fb2f4ebbadd04046ca9834c64434c&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665LDK2IUU%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T042625Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDDiYMautzpbkxuUzl3GTIVwzDHXHaXkTyuYm2yusLttwIgegQLoPnstEsJiP5sQcLCSn26IUvicxmTgj52l%2B7QN2QqiAQInP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPrg4keFkTlRqTQsQCrcA9c757LpgWB1k6Ihb0VIr3RH8mhQHvlKk3hN4BZDKI58aOhC2%2Fut4G2jda%2FuyBAYp27OVrs4rnhJtdF7CMvpo9A2quBWbOtJsxPJv6BKmBuwX0u4CoXcQfYTqfXdWWDyi7Mdnaap1i8dPTKnNb%2F3XP6uyeOTP1Q5oq94xImpI27mKqV0fn%2BomeyL7gWN2JY5%2BAXhpNK5qMLqOhBKoHXs0x%2BUMmuUXk97cWcvs0V5EuOtTu2GxP4AI17DfFmJ39KFBCX%2BLfrQ6yq1hP6nfofAvXESExtqvZUo%2F8skMOgEZ4L%2FiE9on4i4llAq2Av%2FBroc1glx1m5RYzC7t5ZAvgnVJ9Yh1KBW%2BBe2xtOsxPkeeUc%2Bu%2BrcqTl6%2BV77lYvG9XzeNl8W%2FSgQKRRSOPZkaa9AXhs2lzZamTEff%2Fm9cQVtb5d39PsklGPIKzFqHgZHl%2F9c1TZdCqQTrCt4it4NT5uulHHsFOg2%2FBuXj%2FHOvOZ59FCHtUbAMaaZX4IFBdqdjJAUJQ0gmWjAAaN29Dv92m7wk%2FLvcOfvCnETmU3YtZwX0M%2BvKOcdB5k7oOIeHK4qPB3%2FuK8E2IhZSFMjHt3b23hw1mIM7DOwYgZDxwZ7aWUzDq%2F%2BtY9keZA4j3074vMXMNa%2BoL0GOqUBVwoAygTJkxPbnYzXf1NMRu5wwAqCayOMTgSvKFEyf4ZiKAHIi2Hi8JRWxHVG0SV4LZLd71JhCx3o83IW9%2FXc730UDCZJ%2B9OnwILQPRrvbI8%2BLP%2FzlOqoYKyvj6QRIDqgLZ%2BVU97TU%2BAVOehFHv9M6bqRHUdGMORyAaEHsmojSG15Dwj8a%2FPNe7fs2Iktw%2BjMsqrhkpVQw9MtC%2BpFFWrS9MzzjXU0&X-Amz-Signature=167bbf2753566aafac6931c2d777022702ac2654063342476e4f6050785ad71c&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UHPGUR3I%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T042623Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCID1xjRy%2BUV7loPiJ354vDu5S04X07QV8HMT67sJNJPSgAiEAglcgOHF9urfvGLlc2mglITg6QRvXeOXa%2BpJFiB6YstsqiAQInf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDEV3P2XtXaxM1xA6mircA1a%2FLHASFbCuNn9Sewu4asu3lz6CwScmdeR3U%2Fd8umDpsftAS3clwE4JZSOaABPHc4WtnlaUYKXVEQ5qzrMH0K4aqWnSQ7VMCbGVzBLwy6vYDqZDYhpmJYcaDr0GKS%2BfT4ApK1pX6oYiHUGMitEmi%2BGru2mlob6ilTnczyztDWrTXBaaa3IZmhY0sRUBwPNUL8l%2B9ft%2BFxr3f%2BktHRy1urkW8V6fcloWSuxKp5OnCEKzeicFLk5TRPQF9mZk647gpEDTCmbbkYt9NwP51R%2Fm6EvWzczM3d%2FUp0fK%2BdGGImYvZVnsU9oV51CxJnnN8S58hn0M9fIDvXjxHPTC7bcOYaX9Rta9zah3ymzZ1VaHK3s%2FpGWw%2FtP3WLrtDmfXsheAowmRUm7J73Udh2q4Lnw1jETk%2BiYoUXZxZYSYffdxTELCfPA4Cd0BRvKRaYr6Gq6yQX6R%2BeruML34XE%2BZ0vbq%2BKXTohEGJ67VB%2B%2FHsTrmDy6re9WWkuUO4zxMcAT9gf2G%2FcRcrA5z%2FujvEpSNT%2BkHxTWY5snUiaNHNVLOn5m%2FVbLFvZhOC%2FKVyvjb1CW7t57cz%2FLGsrMDRC7ke1u945t%2Fq4NWAJpa8BTFaOUyo5CsUZkqJhTgpHVaarlsmM2%2FMJm%2FoL0GOqUB7Hat2I4yM1hUK%2BpLyJ2MdR%2FnUPO3xM%2FkFrUqKZPtN9YUanKrAMX%2F5ZQDCbYjuIJXxnPr%2F5BsT3WuEtirYHXBLx1LY3qWJHBtrel9mQpZxAajmpfxXQYlPzPtaMi7G1kejSascabbV8HoMMLWqBsJBai1KkwUfUuz6TWdtsjUKMTUuocCOxg0mqlkoJcvgqIwVrt%2Fc85tai2GNcIU9joVgDPuX0IU&X-Amz-Signature=68f435151623a8133a50e3a1f902fe1ec25cf6f62f5749abc66b823bd2affc2e&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UHPGUR3I%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T042623Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCID1xjRy%2BUV7loPiJ354vDu5S04X07QV8HMT67sJNJPSgAiEAglcgOHF9urfvGLlc2mglITg6QRvXeOXa%2BpJFiB6YstsqiAQInf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDEV3P2XtXaxM1xA6mircA1a%2FLHASFbCuNn9Sewu4asu3lz6CwScmdeR3U%2Fd8umDpsftAS3clwE4JZSOaABPHc4WtnlaUYKXVEQ5qzrMH0K4aqWnSQ7VMCbGVzBLwy6vYDqZDYhpmJYcaDr0GKS%2BfT4ApK1pX6oYiHUGMitEmi%2BGru2mlob6ilTnczyztDWrTXBaaa3IZmhY0sRUBwPNUL8l%2B9ft%2BFxr3f%2BktHRy1urkW8V6fcloWSuxKp5OnCEKzeicFLk5TRPQF9mZk647gpEDTCmbbkYt9NwP51R%2Fm6EvWzczM3d%2FUp0fK%2BdGGImYvZVnsU9oV51CxJnnN8S58hn0M9fIDvXjxHPTC7bcOYaX9Rta9zah3ymzZ1VaHK3s%2FpGWw%2FtP3WLrtDmfXsheAowmRUm7J73Udh2q4Lnw1jETk%2BiYoUXZxZYSYffdxTELCfPA4Cd0BRvKRaYr6Gq6yQX6R%2BeruML34XE%2BZ0vbq%2BKXTohEGJ67VB%2B%2FHsTrmDy6re9WWkuUO4zxMcAT9gf2G%2FcRcrA5z%2FujvEpSNT%2BkHxTWY5snUiaNHNVLOn5m%2FVbLFvZhOC%2FKVyvjb1CW7t57cz%2FLGsrMDRC7ke1u945t%2Fq4NWAJpa8BTFaOUyo5CsUZkqJhTgpHVaarlsmM2%2FMJm%2FoL0GOqUB7Hat2I4yM1hUK%2BpLyJ2MdR%2FnUPO3xM%2FkFrUqKZPtN9YUanKrAMX%2F5ZQDCbYjuIJXxnPr%2F5BsT3WuEtirYHXBLx1LY3qWJHBtrel9mQpZxAajmpfxXQYlPzPtaMi7G1kejSascabbV8HoMMLWqBsJBai1KkwUfUuz6TWdtsjUKMTUuocCOxg0mqlkoJcvgqIwVrt%2Fc85tai2GNcIU9joVgDPuX0IU&X-Amz-Signature=015f4ce6402e77c392d23c27d1cce98376d3e368b47a657b8f2ca3dc484de6fb&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UHPGUR3I%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T042623Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCID1xjRy%2BUV7loPiJ354vDu5S04X07QV8HMT67sJNJPSgAiEAglcgOHF9urfvGLlc2mglITg6QRvXeOXa%2BpJFiB6YstsqiAQInf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDEV3P2XtXaxM1xA6mircA1a%2FLHASFbCuNn9Sewu4asu3lz6CwScmdeR3U%2Fd8umDpsftAS3clwE4JZSOaABPHc4WtnlaUYKXVEQ5qzrMH0K4aqWnSQ7VMCbGVzBLwy6vYDqZDYhpmJYcaDr0GKS%2BfT4ApK1pX6oYiHUGMitEmi%2BGru2mlob6ilTnczyztDWrTXBaaa3IZmhY0sRUBwPNUL8l%2B9ft%2BFxr3f%2BktHRy1urkW8V6fcloWSuxKp5OnCEKzeicFLk5TRPQF9mZk647gpEDTCmbbkYt9NwP51R%2Fm6EvWzczM3d%2FUp0fK%2BdGGImYvZVnsU9oV51CxJnnN8S58hn0M9fIDvXjxHPTC7bcOYaX9Rta9zah3ymzZ1VaHK3s%2FpGWw%2FtP3WLrtDmfXsheAowmRUm7J73Udh2q4Lnw1jETk%2BiYoUXZxZYSYffdxTELCfPA4Cd0BRvKRaYr6Gq6yQX6R%2BeruML34XE%2BZ0vbq%2BKXTohEGJ67VB%2B%2FHsTrmDy6re9WWkuUO4zxMcAT9gf2G%2FcRcrA5z%2FujvEpSNT%2BkHxTWY5snUiaNHNVLOn5m%2FVbLFvZhOC%2FKVyvjb1CW7t57cz%2FLGsrMDRC7ke1u945t%2Fq4NWAJpa8BTFaOUyo5CsUZkqJhTgpHVaarlsmM2%2FMJm%2FoL0GOqUB7Hat2I4yM1hUK%2BpLyJ2MdR%2FnUPO3xM%2FkFrUqKZPtN9YUanKrAMX%2F5ZQDCbYjuIJXxnPr%2F5BsT3WuEtirYHXBLx1LY3qWJHBtrel9mQpZxAajmpfxXQYlPzPtaMi7G1kejSascabbV8HoMMLWqBsJBai1KkwUfUuz6TWdtsjUKMTUuocCOxg0mqlkoJcvgqIwVrt%2Fc85tai2GNcIU9joVgDPuX0IU&X-Amz-Signature=9e0d2ec9802413267e4a5832003a53e9a54c711d4d5ee4909c83c2a6a59ecb67&X-Amz-SignedHeaders=host&x-id=GetObject)


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

