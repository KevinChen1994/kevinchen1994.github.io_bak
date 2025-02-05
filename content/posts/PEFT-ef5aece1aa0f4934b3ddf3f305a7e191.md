---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4662GW2NRH7%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250205T132758Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjECsaCXVzLXdlc3QtMiJHMEUCIQDgmxlYtgJM72UhKMZDSCSpWre82TDy8IJQoEJs%2BgF%2BsQI\
  gfWhNX%2Fh96HtCXP6EzZxKiM7Nyf3lppf0i16w%2Fu8i8Kwq%2FwMIRBAAGgw2Mzc0MjMxODM4MD\
  UiDIVimP%2BGQqlCGnwmBCrcA3ouph1yOit%2B0y9F6zETgAtCfWBQw0SK8Q%2FBzTEKAEPhRHSo6\
  aTY0tNa4F95xyIhj7qRy5YlZcO9JcuFjpZ0PW4gk5rdiPOTxlhc37osDRsT7vd%2BpV7c7cufhCis\
  uo2Et6jcMr%2FHqJqje3PAPWNktR6GS5ilti9JWfPQLLaUEsK7chgERV45oSvbf6gjSiFs8wR2pC6\
  DGW6YA0rW8hRd9S1kPZGQqoIB6gNdav%2BL2GilL6pn%2Fx8ax9G%2B7gIsbPpC8X7pkBN3FzlDLa\
  KcViNuL8aWokDelON309MW1l6WEu9xHQPbxWIO2UYNnDJEMNk7Z1F9%2BTeJ%2BpFhsl4aXnaSfbr\
  9pLGmaNh7WwUYmhX%2FnMItkzHI1%2FxNlbu5f%2FQSVdcAZXfvpPgfMATzMAoWs6YMVaB0NJasGh\
  BxGA6l%2BFv7FRXhG8kdwShTwMMJ75loQ5gLQ0LC%2F4Ds3luIrAGuJjQWM%2FaOiBF%2FWNpf%2B\
  bIR8KrLBKlKWipnqLLBF9ZOMQQeMu%2FK805ZUaHlURixzFjhPYr6FxU%2F6V447Wye%2BTX5TRQx\
  qzFjXGpT4h3UlbXgOKbX1GZko39K87VAezew4CSET%2FYsfYM6BeZhEQFsQSAT6lkmPtVemExtOWd\
  %2F1DjA%2BVaTMKyNjb0GOqUB0B9U9DeWakiPLNJBDZXS5c8h5gkEiBoh98ca45QQBZqq2mYWM%2F\
  ozLfJn4dhtYWpQG0Y9wEzG8LxYaIRwr%2FUj%2BTlYQvWQl0Td0J0XnBStzTf4DjIpMbbTfQ4QXvF\
  9afJcHq0uT2DAkiBkEyfdvGJK9bthsLWLjYg9EHyA5uO0yeq2Wdh4Hjbw65%2BCFLoeH4par08%2F\
  Np75gVHNUMY6Sfj0myM6OURc&X-Amz-Signature=ab6217cebd3add5c04fa54a04c6a04ab8ab8\
  2d27bd15f98f524a990ff7f914c6&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466XUDE6F35%2F20250205%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250205T132640Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjECsaCXVzLXdlc3QtMiJIMEYCIQDuT6iWql8GElgChrqq2cCdxaqMEx7\
        qpWHPvDKAgOwQ%2BwIhAPwmDBKPQ59VKsWs05y85iUkVk%2FEfNKrzsXH%2FQfcJ75ZKv8D\
        CEQQABoMNjM3NDIzMTgzODA1IgwdB1eJ7cZqphVOjG4q3AMfJVsYEftkwk5jKrQoqSwBgk9\
        cXkK%2BoZgPC%2BR%2BSXL5l8It6UZVhDtYvjpfeYtNh7XpzrVztq11%2BpQqLE2lfNIihx\
        wUVq0RHNGONpU50fGKEJam0ZW%2F6TvwwDFOiHFKoqng3CFV%2FgBAZxBSX7bFLVd%2BxkW\
        MDtci%2Bnl9zCxOwKUOnqASUPmgHdEI2NaJ7XCzpkeqwWbR1Bk0jf%2F%2BL%2BLjaI3Leh\
        4m0eJSqdcxYe0WWs8O1uodx0qQoOSus1CULNh%2BEPu3q%2FlQYdjytSiTPIRrqzhM%2FYx\
        3zYP%2FCnKEGGZ%2FIbZW5VFBD5JhYNanpR72auBa0i%2B30bCCOi7pwG09W7u19jd23blK\
        tCt2T3wiofyREmpg0RI3sUhvpikPolWQdyWQBTx4iZmGtBIn1wseQhRa8zgClceBcE3qCsV\
        VX%2F7rCfWx0fIPLwPoUW0kCKG3MoBTHqv3oqQhc7r1Kj4c1K2S5acyIhU57DziGvuzo1S0\
        6z3TgxaYwPLeuhsOPZq3KYZSkW59c12C8Oh9%2FndV5yMU3gcjc32%2FGopVIjTxiU%2FLj\
        N1jrtDTsWiHca%2BFsGa7qbhwwAG3vH%2FiX%2FJpw9YLiobNSqtHReqZXPxvdPp4XKMj51\
        CycPPIZDtSJn9D6Wq9gjDyi429BjqkAUKG1XHcDUd4uMp9oGleIy0g8qKGZlvAKO9J%2BW%\
        2FLjXghy3N5m%2FBJLDvlIEFqfk6xJm3%2Fsz6BUX6ts%2Fw4bkVpaC4QuZpQKBnXyKWu7S\
        ECJiioIJonmhP93oWQ0B9qQZYudaXEfoRZDypDOOlfBxefjT5IUZrdazSX99ytjRoBg%2F3\
        n1KjSrsEoM6M%2BEOGR7HEirvHM3%2FiStsfc%2FAJiqahxFZSrJR%2B0&X-Amz-Signatu\
        re=563d37888743a1f95af976c9c526196e10e30d24243d2bc809f7dbed77b40547&X-A\
        mz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-05T14:26:39.981Z"
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
UPDATE_TIME: "2025-02-05T13:28:06.173Z"
EXPIRY_TIME: "2025-02-05T14:27:56.185Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466X2DKTVXC%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T132756Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECsaCXVzLXdlc3QtMiJHMEUCIDtIdf7%2B6ssmzbTNP0S9%2FVr5KJe9dhJ54KYKPyC%2F1RInAiEA%2B6u0QfNGrqJT4jHCWdnc8gki0A1AmRGEWlvFGu7y1Usq%2FwMIRBAAGgw2Mzc0MjMxODM4MDUiDHEkgNxAEptRPoLWuyrcAyc6IncWy1spZnncwlWc7c4HnLmyNssxqwvbFUWF%2FAEB2v3uhc20yFqzCMUjghdM6vNm5Q5733ECXrSQoF9DLnZ%2FXrx5k%2FWPW%2FJgNQdpw8L%2BBi9xG5AXl9RYu83goPTiw%2BRlFojTn5nOIFa3E468YGVhXtXPp2C7JkPeRbTw%2BVxG%2FkEG8ci8CkRNvvd1OxMwnqWuy8XE9xbK08Bh3K1WiVh77dSRBUidBK55E0bRZ0LF1bHDnt%2BiQ7tYOXomsZKRRLb0FKdOh62sbGdrmQ20IBYNgEjFI0Dcw1oYe0vAILVflMKfgqBPWQ9lXAPZ%2FXYjLZzsR3AzraCdwUVinOmij4eYBYTZ510XiJWWs8mz26rk%2BG85gs3RJF3HEtv3TIymllqMNNMtX3GZ8XmIX2lFvLD4hJSb0ENzBHeWzLcyzdmFUaToBdK4ZilVC8iu%2FRSWvevdUc1N%2FeVwGdAUO9gSYKfOv638DyQU%2FeqHKF8siPctjX9m0h59MwhzQ2ttEGPDcHKZxHhNGgPVJz4E2ETe%2BCoSo1kE%2Fovz7DnNIf9o3cRFmIsSwYaJOM83PkoiuaiL3g9s0VzXnNhs9hXGwOLO3BaTHopicaUW80rzJTu9LPpYeBsqTzS%2BpFbtB1VtMOGLjb0GOqUBTaeiViOphrtfYN5%2FY6H4seRVei6HRSyocSVzR7DOqzvuP3%2FbaCfFNEBxJHqRcrb3WYXvb3Mc7DpcGqizlsguBxkUh7UH%2F5wrvCuG03ipWzzx46wHHPFVuzy%2FgjPL9E333Vhv2iUEhlAK8l4%2BM3lPqgNC%2Fjvt2r6Ctz2pZl5O%2FCB9xnlI9JFHRcZaTm14Vi8kZAdwL6GtrP7v9t67nc6tdCM8kZLj&X-Amz-Signature=75be815627bf9dff8a0a77512c06d7d76c7739725b29c030d4e0521d89b1c4f2&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466X2DKTVXC%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T132756Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECsaCXVzLXdlc3QtMiJHMEUCIDtIdf7%2B6ssmzbTNP0S9%2FVr5KJe9dhJ54KYKPyC%2F1RInAiEA%2B6u0QfNGrqJT4jHCWdnc8gki0A1AmRGEWlvFGu7y1Usq%2FwMIRBAAGgw2Mzc0MjMxODM4MDUiDHEkgNxAEptRPoLWuyrcAyc6IncWy1spZnncwlWc7c4HnLmyNssxqwvbFUWF%2FAEB2v3uhc20yFqzCMUjghdM6vNm5Q5733ECXrSQoF9DLnZ%2FXrx5k%2FWPW%2FJgNQdpw8L%2BBi9xG5AXl9RYu83goPTiw%2BRlFojTn5nOIFa3E468YGVhXtXPp2C7JkPeRbTw%2BVxG%2FkEG8ci8CkRNvvd1OxMwnqWuy8XE9xbK08Bh3K1WiVh77dSRBUidBK55E0bRZ0LF1bHDnt%2BiQ7tYOXomsZKRRLb0FKdOh62sbGdrmQ20IBYNgEjFI0Dcw1oYe0vAILVflMKfgqBPWQ9lXAPZ%2FXYjLZzsR3AzraCdwUVinOmij4eYBYTZ510XiJWWs8mz26rk%2BG85gs3RJF3HEtv3TIymllqMNNMtX3GZ8XmIX2lFvLD4hJSb0ENzBHeWzLcyzdmFUaToBdK4ZilVC8iu%2FRSWvevdUc1N%2FeVwGdAUO9gSYKfOv638DyQU%2FeqHKF8siPctjX9m0h59MwhzQ2ttEGPDcHKZxHhNGgPVJz4E2ETe%2BCoSo1kE%2Fovz7DnNIf9o3cRFmIsSwYaJOM83PkoiuaiL3g9s0VzXnNhs9hXGwOLO3BaTHopicaUW80rzJTu9LPpYeBsqTzS%2BpFbtB1VtMOGLjb0GOqUBTaeiViOphrtfYN5%2FY6H4seRVei6HRSyocSVzR7DOqzvuP3%2FbaCfFNEBxJHqRcrb3WYXvb3Mc7DpcGqizlsguBxkUh7UH%2F5wrvCuG03ipWzzx46wHHPFVuzy%2FgjPL9E333Vhv2iUEhlAK8l4%2BM3lPqgNC%2Fjvt2r6Ctz2pZl5O%2FCB9xnlI9JFHRcZaTm14Vi8kZAdwL6GtrP7v9t67nc6tdCM8kZLj&X-Amz-Signature=b92954d7ab155b9803eebecc9a088e8f9b04a1a2ad29a359007cba0f837914e5&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466X2DKTVXC%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T132756Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECsaCXVzLXdlc3QtMiJHMEUCIDtIdf7%2B6ssmzbTNP0S9%2FVr5KJe9dhJ54KYKPyC%2F1RInAiEA%2B6u0QfNGrqJT4jHCWdnc8gki0A1AmRGEWlvFGu7y1Usq%2FwMIRBAAGgw2Mzc0MjMxODM4MDUiDHEkgNxAEptRPoLWuyrcAyc6IncWy1spZnncwlWc7c4HnLmyNssxqwvbFUWF%2FAEB2v3uhc20yFqzCMUjghdM6vNm5Q5733ECXrSQoF9DLnZ%2FXrx5k%2FWPW%2FJgNQdpw8L%2BBi9xG5AXl9RYu83goPTiw%2BRlFojTn5nOIFa3E468YGVhXtXPp2C7JkPeRbTw%2BVxG%2FkEG8ci8CkRNvvd1OxMwnqWuy8XE9xbK08Bh3K1WiVh77dSRBUidBK55E0bRZ0LF1bHDnt%2BiQ7tYOXomsZKRRLb0FKdOh62sbGdrmQ20IBYNgEjFI0Dcw1oYe0vAILVflMKfgqBPWQ9lXAPZ%2FXYjLZzsR3AzraCdwUVinOmij4eYBYTZ510XiJWWs8mz26rk%2BG85gs3RJF3HEtv3TIymllqMNNMtX3GZ8XmIX2lFvLD4hJSb0ENzBHeWzLcyzdmFUaToBdK4ZilVC8iu%2FRSWvevdUc1N%2FeVwGdAUO9gSYKfOv638DyQU%2FeqHKF8siPctjX9m0h59MwhzQ2ttEGPDcHKZxHhNGgPVJz4E2ETe%2BCoSo1kE%2Fovz7DnNIf9o3cRFmIsSwYaJOM83PkoiuaiL3g9s0VzXnNhs9hXGwOLO3BaTHopicaUW80rzJTu9LPpYeBsqTzS%2BpFbtB1VtMOGLjb0GOqUBTaeiViOphrtfYN5%2FY6H4seRVei6HRSyocSVzR7DOqzvuP3%2FbaCfFNEBxJHqRcrb3WYXvb3Mc7DpcGqizlsguBxkUh7UH%2F5wrvCuG03ipWzzx46wHHPFVuzy%2FgjPL9E333Vhv2iUEhlAK8l4%2BM3lPqgNC%2Fjvt2r6Ctz2pZl5O%2FCB9xnlI9JFHRcZaTm14Vi8kZAdwL6GtrP7v9t67nc6tdCM8kZLj&X-Amz-Signature=ea1581af336c5474e118e2e24c349a7afa04925d1963a3636758b35697e9e81c&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466X2DKTVXC%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T132756Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECsaCXVzLXdlc3QtMiJHMEUCIDtIdf7%2B6ssmzbTNP0S9%2FVr5KJe9dhJ54KYKPyC%2F1RInAiEA%2B6u0QfNGrqJT4jHCWdnc8gki0A1AmRGEWlvFGu7y1Usq%2FwMIRBAAGgw2Mzc0MjMxODM4MDUiDHEkgNxAEptRPoLWuyrcAyc6IncWy1spZnncwlWc7c4HnLmyNssxqwvbFUWF%2FAEB2v3uhc20yFqzCMUjghdM6vNm5Q5733ECXrSQoF9DLnZ%2FXrx5k%2FWPW%2FJgNQdpw8L%2BBi9xG5AXl9RYu83goPTiw%2BRlFojTn5nOIFa3E468YGVhXtXPp2C7JkPeRbTw%2BVxG%2FkEG8ci8CkRNvvd1OxMwnqWuy8XE9xbK08Bh3K1WiVh77dSRBUidBK55E0bRZ0LF1bHDnt%2BiQ7tYOXomsZKRRLb0FKdOh62sbGdrmQ20IBYNgEjFI0Dcw1oYe0vAILVflMKfgqBPWQ9lXAPZ%2FXYjLZzsR3AzraCdwUVinOmij4eYBYTZ510XiJWWs8mz26rk%2BG85gs3RJF3HEtv3TIymllqMNNMtX3GZ8XmIX2lFvLD4hJSb0ENzBHeWzLcyzdmFUaToBdK4ZilVC8iu%2FRSWvevdUc1N%2FeVwGdAUO9gSYKfOv638DyQU%2FeqHKF8siPctjX9m0h59MwhzQ2ttEGPDcHKZxHhNGgPVJz4E2ETe%2BCoSo1kE%2Fovz7DnNIf9o3cRFmIsSwYaJOM83PkoiuaiL3g9s0VzXnNhs9hXGwOLO3BaTHopicaUW80rzJTu9LPpYeBsqTzS%2BpFbtB1VtMOGLjb0GOqUBTaeiViOphrtfYN5%2FY6H4seRVei6HRSyocSVzR7DOqzvuP3%2FbaCfFNEBxJHqRcrb3WYXvb3Mc7DpcGqizlsguBxkUh7UH%2F5wrvCuG03ipWzzx46wHHPFVuzy%2FgjPL9E333Vhv2iUEhlAK8l4%2BM3lPqgNC%2Fjvt2r6Ctz2pZl5O%2FCB9xnlI9JFHRcZaTm14Vi8kZAdwL6GtrP7v9t67nc6tdCM8kZLj&X-Amz-Signature=2f5259736b5e34be2744a4feb6019a6eb339edf008819c677d3bda64b9f82089&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466X2DKTVXC%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T132756Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECsaCXVzLXdlc3QtMiJHMEUCIDtIdf7%2B6ssmzbTNP0S9%2FVr5KJe9dhJ54KYKPyC%2F1RInAiEA%2B6u0QfNGrqJT4jHCWdnc8gki0A1AmRGEWlvFGu7y1Usq%2FwMIRBAAGgw2Mzc0MjMxODM4MDUiDHEkgNxAEptRPoLWuyrcAyc6IncWy1spZnncwlWc7c4HnLmyNssxqwvbFUWF%2FAEB2v3uhc20yFqzCMUjghdM6vNm5Q5733ECXrSQoF9DLnZ%2FXrx5k%2FWPW%2FJgNQdpw8L%2BBi9xG5AXl9RYu83goPTiw%2BRlFojTn5nOIFa3E468YGVhXtXPp2C7JkPeRbTw%2BVxG%2FkEG8ci8CkRNvvd1OxMwnqWuy8XE9xbK08Bh3K1WiVh77dSRBUidBK55E0bRZ0LF1bHDnt%2BiQ7tYOXomsZKRRLb0FKdOh62sbGdrmQ20IBYNgEjFI0Dcw1oYe0vAILVflMKfgqBPWQ9lXAPZ%2FXYjLZzsR3AzraCdwUVinOmij4eYBYTZ510XiJWWs8mz26rk%2BG85gs3RJF3HEtv3TIymllqMNNMtX3GZ8XmIX2lFvLD4hJSb0ENzBHeWzLcyzdmFUaToBdK4ZilVC8iu%2FRSWvevdUc1N%2FeVwGdAUO9gSYKfOv638DyQU%2FeqHKF8siPctjX9m0h59MwhzQ2ttEGPDcHKZxHhNGgPVJz4E2ETe%2BCoSo1kE%2Fovz7DnNIf9o3cRFmIsSwYaJOM83PkoiuaiL3g9s0VzXnNhs9hXGwOLO3BaTHopicaUW80rzJTu9LPpYeBsqTzS%2BpFbtB1VtMOGLjb0GOqUBTaeiViOphrtfYN5%2FY6H4seRVei6HRSyocSVzR7DOqzvuP3%2FbaCfFNEBxJHqRcrb3WYXvb3Mc7DpcGqizlsguBxkUh7UH%2F5wrvCuG03ipWzzx46wHHPFVuzy%2FgjPL9E333Vhv2iUEhlAK8l4%2BM3lPqgNC%2Fjvt2r6Ctz2pZl5O%2FCB9xnlI9JFHRcZaTm14Vi8kZAdwL6GtrP7v9t67nc6tdCM8kZLj&X-Amz-Signature=f816ea2944125b102db362e305e7d79183b94c415a568879290e8444ad3d541c&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466R6MJVEWS%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T132757Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECsaCXVzLXdlc3QtMiJIMEYCIQC49oz%2Fm4gmeutYJrbdKu93qxLzucpZ0OGLMOYX3noc7wIhAMVOhWvDfjO0Vh5SqLG%2F2shgA7QmWo74WVaCCyT4CEiaKv8DCEQQABoMNjM3NDIzMTgzODA1IgzzZilyclxEnbQZs7Qq3AMIfsYcGFznBETHStowfSLt1bRNLEB28%2B6e%2BZHMFY%2FhvHiABkWlkRKK626rPtYgEuHJL5Z2a3b%2FnQCZKp0hhRX9KdTdyMvmpWwObpNBgAPbPIeTOZkBFZXmG8MSsAA05uUm0o27khsBRfZ0lvHQcThYxedQHRj%2Fx3oWdqvnOTCRb76LiGu9E%2FxWDJN3RohhcGemIyRNKqlrD1LHniF6BECk2aOypLfwX0SVFcXSgGwrRi3%2FRIYMF9xI8Sc%2FutjxSk19x4ekYCtoDfZNqbFMaoazRf82bhyiq62mbsOR2Ws21Upe6m213c%2BIu5P5W5bLFbv5dOWg4F7X1LIZbONhHY%2FKH%2BJXvNx%2F%2B2pQEIFJP1UhzX7073%2BO7%2BsADT%2B1Yca2U6uEYKFC4V5NLowwyxAgAxDiaQY9PHGp2Kr32tRbzQtPhD6mYI64sSjPkNuqamzarc%2FhLhyV2gTITl7l2YoJVwtT74Uwv0%2FNq%2FCmwzzk3dU0kspZmpIl1yWmF8XOrAwRgwZNuDCbuMZHxMjI27IAz6KEnPaNFPGFoR03MYUvsejt5ArQTE2o81zpXWTCgYqPhfgvijQAp7yi546CmtHE316IYSHOjv3u5iodGGGb6nLfo3jynDlTC3bfMlSc9jDCjI29BjqkATDU6wu1K%2BB001TelCc3cJttUH7q%2B7okYZ9rjK%2FekceBXprxFPSBI0bQGSjhw8rk2TIQSiV%2FkubLfWsgawnNw5mtkGQwAU5BvgtYXg8lsYUiCojz0VsobGQH85wUnDhr8kXfgu6awzRyWtDeNY7R5f0vcVb1rklcmhpTuV4epqvzQHwcuvT2ZKOBhXh7aP6QiC67v%2B88UPL9CYSW6g3MywvTWJfG&X-Amz-Signature=3e9cc3f3582d5f1e295e9edf410e15366a69e5d60af1a9b370f10c6d54db9aec&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667WNEV2QY%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T132758Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECsaCXVzLXdlc3QtMiJGMEQCIH6fu6cDacR%2BsKPnOw2fqC2QIzDrusmii5%2BPB8wZZambAiB35oaeEmLg9fPcuPR4B6ZO32n0hqvjywM8rwSlYl3sdSr%2FAwhEEAAaDDYzNzQyMzE4MzgwNSIMkAwwQuEcPQGE1PsIKtwDpmuCpk%2FQ7tVUJhHrYdegeft47wWyURXSA%2FEl%2FHS0uyB%2B1W6KpvqwZRfUO2CgEBxyM4vXN0oSF7pqg%2FfELvJ%2FFGhRKgXiZRw4zWA3taffcQ6TLxEUrcsIe%2FhVGOVVi6XO0QDDJwqKKKcDIcUKAJ2bcuDEWwhWM5rYxPQ9HMA4N0CLDqYUJP6T1GiM%2BINakI8zYTPxh%2FcezIx%2B6%2FEyxuNHml16QREBeBsaMtaQwSEWFSExSU%2B1QBPJkr40TVYGo3JVNQqokC47AOLZ5SDs68ko22otvu9572WYzHL4oAw4cOdHwS1usgC71I%2FMPj3pSKpNW9Qr920dm6lO%2F0D1l%2B6URDJU5Xhd5BjiXhi%2FtV6e5p6AJuxQWqnKBmvp3W1oIhNCpF8yOv%2BtEepgCm2bZ388mQYE9sBRdUO7GjFyM27LIC17StvRpfrh%2Bw0DF6u5HI6Inn5akUDrzfFaKpugUWnHiPxMaC6DuQqGIr%2FmyLy08AwVk4YJDr55MQoRhPP19mKUqgh8ylwOeAy2GVqRciEug6zvuAgVkgfpAlqwxtqlClkZWy0BXnVfC3tMX0DHb8t2sBan8zQDRjhyLalxMv8IUw2B%2BH%2F9mHG1FWsXIeK5juH3D%2F6Z6qIvv3ne3SYwmIyNvQY6pgGOPychRBuDguWn3jGpz1YYG6HXUcKNvYWkqu3FsjzCDTLfsAMa3zi%2B5IIbvBjYnfwZV5wy88B10Z6fjYRvy394colGZ%2FpNQTsb9OInw16bD3oiXcIsSAUW9fA3ibyL6t0FQP7GuZ0N85WM2AmfCJjASOaXkF35Pl3yyG59o6clwEPoxlaVvFizIzJswv7%2BGJXopud9icKFOvJ2lAtMPPhujvVtXT0y&X-Amz-Signature=9daee39aa8e112d25c570f0b23e6818ff2fb420d6a3a767fa03f3bdc6e28bd72&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466X2DKTVXC%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T132756Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECsaCXVzLXdlc3QtMiJHMEUCIDtIdf7%2B6ssmzbTNP0S9%2FVr5KJe9dhJ54KYKPyC%2F1RInAiEA%2B6u0QfNGrqJT4jHCWdnc8gki0A1AmRGEWlvFGu7y1Usq%2FwMIRBAAGgw2Mzc0MjMxODM4MDUiDHEkgNxAEptRPoLWuyrcAyc6IncWy1spZnncwlWc7c4HnLmyNssxqwvbFUWF%2FAEB2v3uhc20yFqzCMUjghdM6vNm5Q5733ECXrSQoF9DLnZ%2FXrx5k%2FWPW%2FJgNQdpw8L%2BBi9xG5AXl9RYu83goPTiw%2BRlFojTn5nOIFa3E468YGVhXtXPp2C7JkPeRbTw%2BVxG%2FkEG8ci8CkRNvvd1OxMwnqWuy8XE9xbK08Bh3K1WiVh77dSRBUidBK55E0bRZ0LF1bHDnt%2BiQ7tYOXomsZKRRLb0FKdOh62sbGdrmQ20IBYNgEjFI0Dcw1oYe0vAILVflMKfgqBPWQ9lXAPZ%2FXYjLZzsR3AzraCdwUVinOmij4eYBYTZ510XiJWWs8mz26rk%2BG85gs3RJF3HEtv3TIymllqMNNMtX3GZ8XmIX2lFvLD4hJSb0ENzBHeWzLcyzdmFUaToBdK4ZilVC8iu%2FRSWvevdUc1N%2FeVwGdAUO9gSYKfOv638DyQU%2FeqHKF8siPctjX9m0h59MwhzQ2ttEGPDcHKZxHhNGgPVJz4E2ETe%2BCoSo1kE%2Fovz7DnNIf9o3cRFmIsSwYaJOM83PkoiuaiL3g9s0VzXnNhs9hXGwOLO3BaTHopicaUW80rzJTu9LPpYeBsqTzS%2BpFbtB1VtMOGLjb0GOqUBTaeiViOphrtfYN5%2FY6H4seRVei6HRSyocSVzR7DOqzvuP3%2FbaCfFNEBxJHqRcrb3WYXvb3Mc7DpcGqizlsguBxkUh7UH%2F5wrvCuG03ipWzzx46wHHPFVuzy%2FgjPL9E333Vhv2iUEhlAK8l4%2BM3lPqgNC%2Fjvt2r6Ctz2pZl5O%2FCB9xnlI9JFHRcZaTm14Vi8kZAdwL6GtrP7v9t67nc6tdCM8kZLj&X-Amz-Signature=9fd53eb39e60e69a192e1b5137934955347b2a83f58c89cba108fad9d14f36b2&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466X2DKTVXC%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T132756Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECsaCXVzLXdlc3QtMiJHMEUCIDtIdf7%2B6ssmzbTNP0S9%2FVr5KJe9dhJ54KYKPyC%2F1RInAiEA%2B6u0QfNGrqJT4jHCWdnc8gki0A1AmRGEWlvFGu7y1Usq%2FwMIRBAAGgw2Mzc0MjMxODM4MDUiDHEkgNxAEptRPoLWuyrcAyc6IncWy1spZnncwlWc7c4HnLmyNssxqwvbFUWF%2FAEB2v3uhc20yFqzCMUjghdM6vNm5Q5733ECXrSQoF9DLnZ%2FXrx5k%2FWPW%2FJgNQdpw8L%2BBi9xG5AXl9RYu83goPTiw%2BRlFojTn5nOIFa3E468YGVhXtXPp2C7JkPeRbTw%2BVxG%2FkEG8ci8CkRNvvd1OxMwnqWuy8XE9xbK08Bh3K1WiVh77dSRBUidBK55E0bRZ0LF1bHDnt%2BiQ7tYOXomsZKRRLb0FKdOh62sbGdrmQ20IBYNgEjFI0Dcw1oYe0vAILVflMKfgqBPWQ9lXAPZ%2FXYjLZzsR3AzraCdwUVinOmij4eYBYTZ510XiJWWs8mz26rk%2BG85gs3RJF3HEtv3TIymllqMNNMtX3GZ8XmIX2lFvLD4hJSb0ENzBHeWzLcyzdmFUaToBdK4ZilVC8iu%2FRSWvevdUc1N%2FeVwGdAUO9gSYKfOv638DyQU%2FeqHKF8siPctjX9m0h59MwhzQ2ttEGPDcHKZxHhNGgPVJz4E2ETe%2BCoSo1kE%2Fovz7DnNIf9o3cRFmIsSwYaJOM83PkoiuaiL3g9s0VzXnNhs9hXGwOLO3BaTHopicaUW80rzJTu9LPpYeBsqTzS%2BpFbtB1VtMOGLjb0GOqUBTaeiViOphrtfYN5%2FY6H4seRVei6HRSyocSVzR7DOqzvuP3%2FbaCfFNEBxJHqRcrb3WYXvb3Mc7DpcGqizlsguBxkUh7UH%2F5wrvCuG03ipWzzx46wHHPFVuzy%2FgjPL9E333Vhv2iUEhlAK8l4%2BM3lPqgNC%2Fjvt2r6Ctz2pZl5O%2FCB9xnlI9JFHRcZaTm14Vi8kZAdwL6GtrP7v9t67nc6tdCM8kZLj&X-Amz-Signature=20c937ea44cba575a0fbbcf8ee60eef683b5298f3bfa6e29a0c7ed64a6b4ca40&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466X2DKTVXC%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T132756Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECsaCXVzLXdlc3QtMiJHMEUCIDtIdf7%2B6ssmzbTNP0S9%2FVr5KJe9dhJ54KYKPyC%2F1RInAiEA%2B6u0QfNGrqJT4jHCWdnc8gki0A1AmRGEWlvFGu7y1Usq%2FwMIRBAAGgw2Mzc0MjMxODM4MDUiDHEkgNxAEptRPoLWuyrcAyc6IncWy1spZnncwlWc7c4HnLmyNssxqwvbFUWF%2FAEB2v3uhc20yFqzCMUjghdM6vNm5Q5733ECXrSQoF9DLnZ%2FXrx5k%2FWPW%2FJgNQdpw8L%2BBi9xG5AXl9RYu83goPTiw%2BRlFojTn5nOIFa3E468YGVhXtXPp2C7JkPeRbTw%2BVxG%2FkEG8ci8CkRNvvd1OxMwnqWuy8XE9xbK08Bh3K1WiVh77dSRBUidBK55E0bRZ0LF1bHDnt%2BiQ7tYOXomsZKRRLb0FKdOh62sbGdrmQ20IBYNgEjFI0Dcw1oYe0vAILVflMKfgqBPWQ9lXAPZ%2FXYjLZzsR3AzraCdwUVinOmij4eYBYTZ510XiJWWs8mz26rk%2BG85gs3RJF3HEtv3TIymllqMNNMtX3GZ8XmIX2lFvLD4hJSb0ENzBHeWzLcyzdmFUaToBdK4ZilVC8iu%2FRSWvevdUc1N%2FeVwGdAUO9gSYKfOv638DyQU%2FeqHKF8siPctjX9m0h59MwhzQ2ttEGPDcHKZxHhNGgPVJz4E2ETe%2BCoSo1kE%2Fovz7DnNIf9o3cRFmIsSwYaJOM83PkoiuaiL3g9s0VzXnNhs9hXGwOLO3BaTHopicaUW80rzJTu9LPpYeBsqTzS%2BpFbtB1VtMOGLjb0GOqUBTaeiViOphrtfYN5%2FY6H4seRVei6HRSyocSVzR7DOqzvuP3%2FbaCfFNEBxJHqRcrb3WYXvb3Mc7DpcGqizlsguBxkUh7UH%2F5wrvCuG03ipWzzx46wHHPFVuzy%2FgjPL9E333Vhv2iUEhlAK8l4%2BM3lPqgNC%2Fjvt2r6Ctz2pZl5O%2FCB9xnlI9JFHRcZaTm14Vi8kZAdwL6GtrP7v9t67nc6tdCM8kZLj&X-Amz-Signature=649dcb87f7d09e3ce92c4a5d6d62b350fd0e42ab0293a1329637b70c567a8324&X-Amz-SignedHeaders=host&x-id=GetObject)


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

