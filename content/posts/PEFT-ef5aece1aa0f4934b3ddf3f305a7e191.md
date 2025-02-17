---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466SFVQ25ZD%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250217T191859Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEFIaCXVzLXdlc3QtMiJGMEQCIHdS9PXSm9D1bjP0G4J22KrwzhjA04s3woNKJJv3M2hpAiAJKmW\
  pVLd35Oixxz7CE92%2FU95t5%2BmvX3TFKlqyXn7IiSr%2FAwh7EAAaDDYzNzQyMzE4MzgwNSIMbm\
  Ti1KCk%2BAwRxqjMKtwDZEA5ttOXkc7qSUvAqpEistq4PsMRB79KBG2kVKpN6ow4UohvsKPKL7Dke\
  M5jeWC9dlgWhP2QPVUiC5Pmv1px7vxsZ0R26d9bK9gVMAfTAUTutvlHROFiWNMTmJykQ3SYfahrqX\
  oBSPryQx7DhLQGEgmZ36gGhyNjv1RpAZu%2FQM4Sqz1RJMou4jDFbsI8Zqv9F6HppKgjfUOo%2B%2\
  BC36XiELdVtmobDLn4a24XZLNZTbehvLsWpXFqJwm8qdYYolF52p%2FNsg3WBroGnEHHL3f8boRDU\
  BrlZmA333Eu2NrG6yhX62yJJjLQ%2FwDOOaHHbyWTi%2B8c7YI9NipgtRde%2FIZQPONc6J4Yrwp7\
  ZON2NxlTC4gaD6Nmtvq6w14RZfQluWaf70QuGPgPJwk6YSZBKX5tRpvgu%2BlY2sJbrssEBZKHCa3\
  0DOurK9xEMJ%2FZi2eTlrrtT6FLJG7Zun0EhiJxWY59jAG8mvgXzi%2BXUEkVM5l4ylnsSYuZ0xP%\
  2F4sK8NidhAB4VYrDMaLo9IxytDVSZrZHosdg0zBh6R6iliyi54b99yZSK7jff4yqYmZHBBQghbhH\
  SRtn5LboAyN2wvTm%2BCEoRIBBD%2BG6CVP%2F0KUuthSO2m810yPTsIxeGXeImc5Ykw%2FPXNvQY\
  6pgGA3l8%2BQu5JxSzeqYtHCD7uE6X9bEyjec8jXAqF%2BtaClMcscinDlfwtsHIOHcWE3M1cCBQJ\
  macAmf%2F8uCYCCsQuW%2FYSiGfdPl%2FdQjP3s5eADr%2BB%2F8L6bdWBrucY7Cyg5ntpkQ3RFsD\
  wkOYKMsSxngGCO1enDjOLw%2BAye9Ay%2FnmmnL26jaxVbhmrxzzZ1wd%2FGekSigTrGrWbm1RXkA\
  lNe6kC4fHXgY8i&X-Amz-Signature=7e4941697cc6bd15db8a59985d12ade2a04c98d7ece965\
  69cfe073ef2e334c98&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4666JJS2WR2%2F20250217%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250217T191802Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEFIaCXVzLXdlc3QtMiJHMEUCIH7V6SgXY%2FXZYpP37DmjLARk%2BRL\
        IBb3skWgxJ%2FjleOghAiEA0fGTbbBk3CFIwHF1AECvPAmLNuAWbXNUqhaez0l%2BzJAq%2\
        FwMIexAAGgw2Mzc0MjMxODM4MDUiDJPsgG7g7MSUzQIf5SrcA5M2LHsOMPuNXjMouxQsVdU\
        NRVJf7lk9Lmle9JS2KLzKTz0LB%2BXMFrHYhOsWrwqZ2nx0wIAsbtIa%2FnwJXki7CKh8Vq\
        XUXDIuIS3kJMoK8XG%2FOLM6vNnl%2BfiP0V7q%2BKfwTcapfYuo5q7w8Qk%2FjbQHGsiXh\
        jj0AlRn5i5OnQP8NIAmDQ8UdKab3bQg%2BgfUl6fqSwZVO2lL4C77gi69nS8Nn7zYtGTgsB\
        1PLIAjRnj35qdx0iywT4Fnu4AWe%2F832b32EtPCDA4qiq43TtOaT%2FIOkB3a0xc7gx%2B\
        Mtx0dAwUMbf034ttlam9nG%2BSPl65lHj47ffibJ%2Fc9JCmWJE82zPXh5GpwqLA1pYPM8U\
        yr7zoyVj0xq2kLi1q108HWaMdzobrKLEw7nwrioucQqw1bcOVbRKaz3wODzb2bhZ4bl0cFK\
        RPPj8P8FkhmemCEVC9toWsklxYE89lTF%2BAEYOws%2B7YYC2hgn4GgFzTANrniy0K0YILe\
        tZ7FpJAx91iuUtnKYsarexJJ%2B9jwnlpfHcBmMSRSnu6sYtAwsZf7oD%2B%2B5WWfiZM0%\
        2BcQb4Llzy97f4wCww2s6WnoKj3kwhjp5CEa3niGFcGB5xamfOzZsAhfu9JAY5p6d%2FJlp\
        t9YgOHA%2FsgU2MLL2zb0GOqUBY4QtzM79y6l8HvEQw2e5D0ZUeEQD8e9IGXRSEXYvitdLf\
        60fKsG6mRFqFcuAfDVUAWYW5vFwGHKSeti0Mn%2BOcnaYCHjObkvkKgvIqGKgwFvu0DF0MR\
        8mtwcNBL%2FD0ORN%2BxuYYHEKIkpt3nlKvncHtKg1BmEqoo9mV5eAUJbPN7s0qns6kcQLF\
        cRGC%2B2JaMspJ%2FsU%2BBiTzoHRVoUEKuB52UfEX%2FsZ&X-Amz-Signature=30c9e8e\
        f71126fb11a8aeaf015b49476025f6c6659b8f9658c2a4ea534da45ec&X-Amz-SignedH\
        eaders=host&x-id=GetObject"
      expiry_time: "2025-02-17T20:18:02.088Z"
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
UPDATE_TIME: "2025-02-17T19:19:03.838Z"
EXPIRY_TIME: "2025-02-17T20:18:57.501Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SBLOKIX7%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T191858Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFIaCXVzLXdlc3QtMiJHMEUCIHs6q7ZM3%2B%2FrF%2BFzGay2z3EwM7SUSdxCTm7DZcZKNisfAiEAvDYzvOvv74APMN18CLyIFVGHuhgmpTubVUUSGSvAg7Eq%2FwMIexAAGgw2Mzc0MjMxODM4MDUiDAcOcnW3q6ly3tGbpCrcA8fWehYy9tMqAHTXpmOYX7OFxNBl7m1dTaLqwm1KATXMdszs76TOFzTQ4nQHglp3t9aQYhfqIE2rLOK%2FZYHCiUr58M%2BU2UplYzVqgJ4b4iy5HHmq9Qg%2F9n0FpLALRB2%2FvJGWqp3VhS7ZFAHBPtoRxBMGitj3Oz9%2BZTxeEqVomc9qwCN8U0noLzotgppexANsq4WMv2FQa4LKqMDTrVepcTYkYRnDfs4jUMaUGsoa3cQGNLHP1WbWmorRxqoxUsSK43ukCUOOXevvrd%2FJKrwuu3pY7XOIGzcDRb2wZERWCl19zay2ntjuA4e9lF79d88x%2FyQjHs0eEQCHn7dEXcfSC7khVRe714kPwC62XyjZKzpzsTyvHnj5OiKtorNsMviKoQNpp0aKxfWDYnFXdpBKn26YXuWJHRi%2FU8n8v4N6%2BMFpX3Tr%2FauD0V6SFhZyjpzGY%2Fbb9JCz7%2ByeX34TdxUj%2BFNYMjpa708cRl53f3WiO5G2lTl5lGTgvIs9OyGWFyVzT9Mnl2u3ploXc81aJD%2FXY4gLWu%2FyM2lGBWnHoOBhP%2F4Bg2s4q6IITg297GDtFr3bni1yH6g5zW6OMFi6VlB8RQ%2Fx7tS8j4rmR4tM43pHnk5vRHZEgNVLgjxeXOewMKb2zb0GOqUBY6FHIkEXgM7WF15Ne6lJBl3D90TifrPt3LaUxK4mw4VKQQPQKV76YIErY1JfsM%2Bj%2F1JVimZiNw3Hp68kQc%2F%2Fs5TQAIRy%2BGyHda55YuG7KfEWsTApkjXIdXhMPHqpmXtyfGmSsp3jmZnLIDYDTW8UvkW%2Fho9FIVCFcsM%2BycmD07uTXnkBIwlLHzRI%2FdpOt5A5UwidEh30rMee5mSbTikHYWH3OWvn&X-Amz-Signature=2e6c37f282e7e739503d658f16426858743d2228e504abd84d4b14959ebb741a&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SBLOKIX7%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T191858Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFIaCXVzLXdlc3QtMiJHMEUCIHs6q7ZM3%2B%2FrF%2BFzGay2z3EwM7SUSdxCTm7DZcZKNisfAiEAvDYzvOvv74APMN18CLyIFVGHuhgmpTubVUUSGSvAg7Eq%2FwMIexAAGgw2Mzc0MjMxODM4MDUiDAcOcnW3q6ly3tGbpCrcA8fWehYy9tMqAHTXpmOYX7OFxNBl7m1dTaLqwm1KATXMdszs76TOFzTQ4nQHglp3t9aQYhfqIE2rLOK%2FZYHCiUr58M%2BU2UplYzVqgJ4b4iy5HHmq9Qg%2F9n0FpLALRB2%2FvJGWqp3VhS7ZFAHBPtoRxBMGitj3Oz9%2BZTxeEqVomc9qwCN8U0noLzotgppexANsq4WMv2FQa4LKqMDTrVepcTYkYRnDfs4jUMaUGsoa3cQGNLHP1WbWmorRxqoxUsSK43ukCUOOXevvrd%2FJKrwuu3pY7XOIGzcDRb2wZERWCl19zay2ntjuA4e9lF79d88x%2FyQjHs0eEQCHn7dEXcfSC7khVRe714kPwC62XyjZKzpzsTyvHnj5OiKtorNsMviKoQNpp0aKxfWDYnFXdpBKn26YXuWJHRi%2FU8n8v4N6%2BMFpX3Tr%2FauD0V6SFhZyjpzGY%2Fbb9JCz7%2ByeX34TdxUj%2BFNYMjpa708cRl53f3WiO5G2lTl5lGTgvIs9OyGWFyVzT9Mnl2u3ploXc81aJD%2FXY4gLWu%2FyM2lGBWnHoOBhP%2F4Bg2s4q6IITg297GDtFr3bni1yH6g5zW6OMFi6VlB8RQ%2Fx7tS8j4rmR4tM43pHnk5vRHZEgNVLgjxeXOewMKb2zb0GOqUBY6FHIkEXgM7WF15Ne6lJBl3D90TifrPt3LaUxK4mw4VKQQPQKV76YIErY1JfsM%2Bj%2F1JVimZiNw3Hp68kQc%2F%2Fs5TQAIRy%2BGyHda55YuG7KfEWsTApkjXIdXhMPHqpmXtyfGmSsp3jmZnLIDYDTW8UvkW%2Fho9FIVCFcsM%2BycmD07uTXnkBIwlLHzRI%2FdpOt5A5UwidEh30rMee5mSbTikHYWH3OWvn&X-Amz-Signature=829b22e324fd736c84ad6e8c77f08c32756f1982c0bd8b9f563f9f9a3ad0e951&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SBLOKIX7%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T191858Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFIaCXVzLXdlc3QtMiJHMEUCIHs6q7ZM3%2B%2FrF%2BFzGay2z3EwM7SUSdxCTm7DZcZKNisfAiEAvDYzvOvv74APMN18CLyIFVGHuhgmpTubVUUSGSvAg7Eq%2FwMIexAAGgw2Mzc0MjMxODM4MDUiDAcOcnW3q6ly3tGbpCrcA8fWehYy9tMqAHTXpmOYX7OFxNBl7m1dTaLqwm1KATXMdszs76TOFzTQ4nQHglp3t9aQYhfqIE2rLOK%2FZYHCiUr58M%2BU2UplYzVqgJ4b4iy5HHmq9Qg%2F9n0FpLALRB2%2FvJGWqp3VhS7ZFAHBPtoRxBMGitj3Oz9%2BZTxeEqVomc9qwCN8U0noLzotgppexANsq4WMv2FQa4LKqMDTrVepcTYkYRnDfs4jUMaUGsoa3cQGNLHP1WbWmorRxqoxUsSK43ukCUOOXevvrd%2FJKrwuu3pY7XOIGzcDRb2wZERWCl19zay2ntjuA4e9lF79d88x%2FyQjHs0eEQCHn7dEXcfSC7khVRe714kPwC62XyjZKzpzsTyvHnj5OiKtorNsMviKoQNpp0aKxfWDYnFXdpBKn26YXuWJHRi%2FU8n8v4N6%2BMFpX3Tr%2FauD0V6SFhZyjpzGY%2Fbb9JCz7%2ByeX34TdxUj%2BFNYMjpa708cRl53f3WiO5G2lTl5lGTgvIs9OyGWFyVzT9Mnl2u3ploXc81aJD%2FXY4gLWu%2FyM2lGBWnHoOBhP%2F4Bg2s4q6IITg297GDtFr3bni1yH6g5zW6OMFi6VlB8RQ%2Fx7tS8j4rmR4tM43pHnk5vRHZEgNVLgjxeXOewMKb2zb0GOqUBY6FHIkEXgM7WF15Ne6lJBl3D90TifrPt3LaUxK4mw4VKQQPQKV76YIErY1JfsM%2Bj%2F1JVimZiNw3Hp68kQc%2F%2Fs5TQAIRy%2BGyHda55YuG7KfEWsTApkjXIdXhMPHqpmXtyfGmSsp3jmZnLIDYDTW8UvkW%2Fho9FIVCFcsM%2BycmD07uTXnkBIwlLHzRI%2FdpOt5A5UwidEh30rMee5mSbTikHYWH3OWvn&X-Amz-Signature=8706d08540691709151f0be10f0454d3cc7e604afbccbde5e2592328b6024e33&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SBLOKIX7%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T191858Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFIaCXVzLXdlc3QtMiJHMEUCIHs6q7ZM3%2B%2FrF%2BFzGay2z3EwM7SUSdxCTm7DZcZKNisfAiEAvDYzvOvv74APMN18CLyIFVGHuhgmpTubVUUSGSvAg7Eq%2FwMIexAAGgw2Mzc0MjMxODM4MDUiDAcOcnW3q6ly3tGbpCrcA8fWehYy9tMqAHTXpmOYX7OFxNBl7m1dTaLqwm1KATXMdszs76TOFzTQ4nQHglp3t9aQYhfqIE2rLOK%2FZYHCiUr58M%2BU2UplYzVqgJ4b4iy5HHmq9Qg%2F9n0FpLALRB2%2FvJGWqp3VhS7ZFAHBPtoRxBMGitj3Oz9%2BZTxeEqVomc9qwCN8U0noLzotgppexANsq4WMv2FQa4LKqMDTrVepcTYkYRnDfs4jUMaUGsoa3cQGNLHP1WbWmorRxqoxUsSK43ukCUOOXevvrd%2FJKrwuu3pY7XOIGzcDRb2wZERWCl19zay2ntjuA4e9lF79d88x%2FyQjHs0eEQCHn7dEXcfSC7khVRe714kPwC62XyjZKzpzsTyvHnj5OiKtorNsMviKoQNpp0aKxfWDYnFXdpBKn26YXuWJHRi%2FU8n8v4N6%2BMFpX3Tr%2FauD0V6SFhZyjpzGY%2Fbb9JCz7%2ByeX34TdxUj%2BFNYMjpa708cRl53f3WiO5G2lTl5lGTgvIs9OyGWFyVzT9Mnl2u3ploXc81aJD%2FXY4gLWu%2FyM2lGBWnHoOBhP%2F4Bg2s4q6IITg297GDtFr3bni1yH6g5zW6OMFi6VlB8RQ%2Fx7tS8j4rmR4tM43pHnk5vRHZEgNVLgjxeXOewMKb2zb0GOqUBY6FHIkEXgM7WF15Ne6lJBl3D90TifrPt3LaUxK4mw4VKQQPQKV76YIErY1JfsM%2Bj%2F1JVimZiNw3Hp68kQc%2F%2Fs5TQAIRy%2BGyHda55YuG7KfEWsTApkjXIdXhMPHqpmXtyfGmSsp3jmZnLIDYDTW8UvkW%2Fho9FIVCFcsM%2BycmD07uTXnkBIwlLHzRI%2FdpOt5A5UwidEh30rMee5mSbTikHYWH3OWvn&X-Amz-Signature=000899b3f845d606d03187a7b1c39bfade18ee1bcc9a64a3ba8ce2478d6dade5&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SBLOKIX7%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T191858Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFIaCXVzLXdlc3QtMiJHMEUCIHs6q7ZM3%2B%2FrF%2BFzGay2z3EwM7SUSdxCTm7DZcZKNisfAiEAvDYzvOvv74APMN18CLyIFVGHuhgmpTubVUUSGSvAg7Eq%2FwMIexAAGgw2Mzc0MjMxODM4MDUiDAcOcnW3q6ly3tGbpCrcA8fWehYy9tMqAHTXpmOYX7OFxNBl7m1dTaLqwm1KATXMdszs76TOFzTQ4nQHglp3t9aQYhfqIE2rLOK%2FZYHCiUr58M%2BU2UplYzVqgJ4b4iy5HHmq9Qg%2F9n0FpLALRB2%2FvJGWqp3VhS7ZFAHBPtoRxBMGitj3Oz9%2BZTxeEqVomc9qwCN8U0noLzotgppexANsq4WMv2FQa4LKqMDTrVepcTYkYRnDfs4jUMaUGsoa3cQGNLHP1WbWmorRxqoxUsSK43ukCUOOXevvrd%2FJKrwuu3pY7XOIGzcDRb2wZERWCl19zay2ntjuA4e9lF79d88x%2FyQjHs0eEQCHn7dEXcfSC7khVRe714kPwC62XyjZKzpzsTyvHnj5OiKtorNsMviKoQNpp0aKxfWDYnFXdpBKn26YXuWJHRi%2FU8n8v4N6%2BMFpX3Tr%2FauD0V6SFhZyjpzGY%2Fbb9JCz7%2ByeX34TdxUj%2BFNYMjpa708cRl53f3WiO5G2lTl5lGTgvIs9OyGWFyVzT9Mnl2u3ploXc81aJD%2FXY4gLWu%2FyM2lGBWnHoOBhP%2F4Bg2s4q6IITg297GDtFr3bni1yH6g5zW6OMFi6VlB8RQ%2Fx7tS8j4rmR4tM43pHnk5vRHZEgNVLgjxeXOewMKb2zb0GOqUBY6FHIkEXgM7WF15Ne6lJBl3D90TifrPt3LaUxK4mw4VKQQPQKV76YIErY1JfsM%2Bj%2F1JVimZiNw3Hp68kQc%2F%2Fs5TQAIRy%2BGyHda55YuG7KfEWsTApkjXIdXhMPHqpmXtyfGmSsp3jmZnLIDYDTW8UvkW%2Fho9FIVCFcsM%2BycmD07uTXnkBIwlLHzRI%2FdpOt5A5UwidEh30rMee5mSbTikHYWH3OWvn&X-Amz-Signature=acdce65a3ba5a75121ca27108932c1a364e0b11f06faeabed558c6ef3499e159&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VBC73VGD%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T191858Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFIaCXVzLXdlc3QtMiJHMEUCIEefEylPjbJeJzdw5ScN5Db%2BEYQgqoqSAYpCFz1oXSJ6AiEA2K%2FPo%2FHSh7QRXQaKh0YlyGF3bo9b6blg6zMWNOPuuXEq%2FwMIexAAGgw2Mzc0MjMxODM4MDUiDMVNXqjrFpO5UcKp4CrcA6JYDbcG1yEesj%2FjKIa%2B4Av9r5LbpywRLbjY8FeBaQcMnZsTfoylvkzSjM5iDKJyMRYIPvwq8BkblUYT9hInW9D%2Bf0YQ2%2BggZPr%2B5hBEbnDXIq3owpvAke2Bohzkdf%2FrkSdDWwkJ7WGeO0UUhrXc%2FkcXL%2Fz%2B1H19w15lAgG02FiJL36hIANHsl%2F1jvJblzuPAZXykfbX0%2Fs7d8%2BB1b%2BgZj2e9vPAwvs8KwbI8qTiUlWjAu24kjEQJ77kCXMLRSlYgLHl4Qn2nVuerjxI1%2F0St9et%2FV3QS4n8aBLV7HH4X%2FI6%2BjT9yPPB7tswcT57OYaEEOpv428f7uyzuZw8v2MZDUJlmlD955nzjWuKdZ3UreeLHWCzkvknS6GlVJDmUO5KZBZ%2FmVuVTmn6%2FOiWxDDlmeErkqhlnksFzrIs9Pvffb0cPysVrizb40Tz2h8WNKkjCDih21hMhgcgLJ2FCnCW65WgpFg0gXs9d3MNmqcnWz00pzr8IzmFRU5%2FMC21m73hzTO0Oz2e4PhmQh5Wog8bVU1r3ewFZuXyHk%2B6xk%2FpA1rvWUwjADULxjIerQZJnM3svEitgk8wfqJn1%2Fp9toqQVvzvMFzf954ZgMzGaVLiIS3jDH8WPqbeYMVYBzszMPz1zb0GOqUB1KUvGZU%2BhCgUKxPdNAVkTsn8h8aMX6S00ZVKKTpEp5tOs7lapdS0U5BY2s36kGlAjmU1aItT30s%2FbgI%2BlaEiCBLUMNWLXQE%2BkZQ5Zq4gpuut5FNFaT4AtsE6aDtpUCcrSnEnvPCSvfIry%2Fy8dMRZptVAFAu1w1xX0Zz2NB4XLQ82evCHYHPDAvyNLtTnsa3l1j87jgntq%2BvuB6jz4sQ3%2B9h9d5jI&X-Amz-Signature=116405f2fc637dc82fcf479f7c8dcda6f204807ee8d356ab13546fc8a6a4cd27&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667QP3IBQE%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T191859Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFIaCXVzLXdlc3QtMiJHMEUCIASroXbyZMDvga0bGz0PJ58R47%2BPZ055nrSSE4qPghHZAiEAsy0d7rZfGsVoX1xAfDuKAc4gE3A6udPr0CDkoCqkSboq%2FwMIexAAGgw2Mzc0MjMxODM4MDUiDC91p7iATm5SbPhQmyrcA%2FZqgGQuKeFCvUyfjkqKLwO%2FFYd13LyTH4gTxhfLwcbKOUYSx6h0uvA7Mjyi5IDzq1HoP9XW42Y8hvXXrkYabJIl9sPU4YL%2Fwx06E4XCiUkv8F37akgY1MsE9Kg5GezQ9R15hrUtRItbwH2jK2f7TD4ucLshbAqWRuP3gUqJ0bYJ9CdYeuwRok217K0tSpT54GyfKVGqbg73KV1eU3qVIHHMXfWKTssPClXelwatoKPCxS%2F8GkYfuFYmiLwaXEMZzwybupeAgrY5Z1fC3RYGpbwNxsp2PedJuefMOjYHa2PftW4rVjAiplQdo%2FYxJ9HEpKhuaN3RcuRotOe77LxUE0l%2FIDtwKsVw6XRWat6UCOuVFvyVgEYr%2Bn0myWhow8ui14idRSBgS9frLADuDO6qlNWQb9ydgscrY41%2Fkc1C%2FifU1Wv7F1zeMwAAEx1d9GfBc7z9ZVPxWWd6trzM59%2FXg%2BvV2DZfcuaRUfzyFbLDvLZhIKmplzRDCru60Ku723u3BEYZgbUxWp275qfbTC2jaKR0CO2nC0B9E7FjEI1eA76ozDqN6XmZsvgbjpeBrel%2FwYlRAEpLAmPdtCPnRbClAwUbMdorO5%2BHgxELkV9aI%2BD%2F6WVm3TT1pTmdiPVWMJP2zb0GOqUBFxk8KLlPoz28IOakvWdq84Wltd6OmdEYjPoJjfiqmKbsftQcLFAwtwqGZLeYw1HK3JmsOk%2BjA5yJINtwEeVrKFVaJUrRWFi99kwCbO1VzhaRxUX8j%2B4wa52kOLMDRUW%2BCFAQM1k13a8YJr8IfSmnxqS6P21D3TYTHbgTIsNOtgu5EL1MZSgjhK63%2B%2F5kBA4CMG8Pzczalw3M%2BCxqC3AyvXgyzETG&X-Amz-Signature=e9907b8c5e83a344c8f443e424f6f7fe62d5620a08bd22af34b5551edecd67b5&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SBLOKIX7%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T191858Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFIaCXVzLXdlc3QtMiJHMEUCIHs6q7ZM3%2B%2FrF%2BFzGay2z3EwM7SUSdxCTm7DZcZKNisfAiEAvDYzvOvv74APMN18CLyIFVGHuhgmpTubVUUSGSvAg7Eq%2FwMIexAAGgw2Mzc0MjMxODM4MDUiDAcOcnW3q6ly3tGbpCrcA8fWehYy9tMqAHTXpmOYX7OFxNBl7m1dTaLqwm1KATXMdszs76TOFzTQ4nQHglp3t9aQYhfqIE2rLOK%2FZYHCiUr58M%2BU2UplYzVqgJ4b4iy5HHmq9Qg%2F9n0FpLALRB2%2FvJGWqp3VhS7ZFAHBPtoRxBMGitj3Oz9%2BZTxeEqVomc9qwCN8U0noLzotgppexANsq4WMv2FQa4LKqMDTrVepcTYkYRnDfs4jUMaUGsoa3cQGNLHP1WbWmorRxqoxUsSK43ukCUOOXevvrd%2FJKrwuu3pY7XOIGzcDRb2wZERWCl19zay2ntjuA4e9lF79d88x%2FyQjHs0eEQCHn7dEXcfSC7khVRe714kPwC62XyjZKzpzsTyvHnj5OiKtorNsMviKoQNpp0aKxfWDYnFXdpBKn26YXuWJHRi%2FU8n8v4N6%2BMFpX3Tr%2FauD0V6SFhZyjpzGY%2Fbb9JCz7%2ByeX34TdxUj%2BFNYMjpa708cRl53f3WiO5G2lTl5lGTgvIs9OyGWFyVzT9Mnl2u3ploXc81aJD%2FXY4gLWu%2FyM2lGBWnHoOBhP%2F4Bg2s4q6IITg297GDtFr3bni1yH6g5zW6OMFi6VlB8RQ%2Fx7tS8j4rmR4tM43pHnk5vRHZEgNVLgjxeXOewMKb2zb0GOqUBY6FHIkEXgM7WF15Ne6lJBl3D90TifrPt3LaUxK4mw4VKQQPQKV76YIErY1JfsM%2Bj%2F1JVimZiNw3Hp68kQc%2F%2Fs5TQAIRy%2BGyHda55YuG7KfEWsTApkjXIdXhMPHqpmXtyfGmSsp3jmZnLIDYDTW8UvkW%2Fho9FIVCFcsM%2BycmD07uTXnkBIwlLHzRI%2FdpOt5A5UwidEh30rMee5mSbTikHYWH3OWvn&X-Amz-Signature=5f32fad5102f88799d00e788020983106980ed09761ae98ef97ffc3ffbd5fca6&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SBLOKIX7%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T191858Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFIaCXVzLXdlc3QtMiJHMEUCIHs6q7ZM3%2B%2FrF%2BFzGay2z3EwM7SUSdxCTm7DZcZKNisfAiEAvDYzvOvv74APMN18CLyIFVGHuhgmpTubVUUSGSvAg7Eq%2FwMIexAAGgw2Mzc0MjMxODM4MDUiDAcOcnW3q6ly3tGbpCrcA8fWehYy9tMqAHTXpmOYX7OFxNBl7m1dTaLqwm1KATXMdszs76TOFzTQ4nQHglp3t9aQYhfqIE2rLOK%2FZYHCiUr58M%2BU2UplYzVqgJ4b4iy5HHmq9Qg%2F9n0FpLALRB2%2FvJGWqp3VhS7ZFAHBPtoRxBMGitj3Oz9%2BZTxeEqVomc9qwCN8U0noLzotgppexANsq4WMv2FQa4LKqMDTrVepcTYkYRnDfs4jUMaUGsoa3cQGNLHP1WbWmorRxqoxUsSK43ukCUOOXevvrd%2FJKrwuu3pY7XOIGzcDRb2wZERWCl19zay2ntjuA4e9lF79d88x%2FyQjHs0eEQCHn7dEXcfSC7khVRe714kPwC62XyjZKzpzsTyvHnj5OiKtorNsMviKoQNpp0aKxfWDYnFXdpBKn26YXuWJHRi%2FU8n8v4N6%2BMFpX3Tr%2FauD0V6SFhZyjpzGY%2Fbb9JCz7%2ByeX34TdxUj%2BFNYMjpa708cRl53f3WiO5G2lTl5lGTgvIs9OyGWFyVzT9Mnl2u3ploXc81aJD%2FXY4gLWu%2FyM2lGBWnHoOBhP%2F4Bg2s4q6IITg297GDtFr3bni1yH6g5zW6OMFi6VlB8RQ%2Fx7tS8j4rmR4tM43pHnk5vRHZEgNVLgjxeXOewMKb2zb0GOqUBY6FHIkEXgM7WF15Ne6lJBl3D90TifrPt3LaUxK4mw4VKQQPQKV76YIErY1JfsM%2Bj%2F1JVimZiNw3Hp68kQc%2F%2Fs5TQAIRy%2BGyHda55YuG7KfEWsTApkjXIdXhMPHqpmXtyfGmSsp3jmZnLIDYDTW8UvkW%2Fho9FIVCFcsM%2BycmD07uTXnkBIwlLHzRI%2FdpOt5A5UwidEh30rMee5mSbTikHYWH3OWvn&X-Amz-Signature=69c2f5dcf503e26ff5b8301c62aba42b465042f71118707a0b50d5a6617f70a5&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SBLOKIX7%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T191858Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFIaCXVzLXdlc3QtMiJHMEUCIHs6q7ZM3%2B%2FrF%2BFzGay2z3EwM7SUSdxCTm7DZcZKNisfAiEAvDYzvOvv74APMN18CLyIFVGHuhgmpTubVUUSGSvAg7Eq%2FwMIexAAGgw2Mzc0MjMxODM4MDUiDAcOcnW3q6ly3tGbpCrcA8fWehYy9tMqAHTXpmOYX7OFxNBl7m1dTaLqwm1KATXMdszs76TOFzTQ4nQHglp3t9aQYhfqIE2rLOK%2FZYHCiUr58M%2BU2UplYzVqgJ4b4iy5HHmq9Qg%2F9n0FpLALRB2%2FvJGWqp3VhS7ZFAHBPtoRxBMGitj3Oz9%2BZTxeEqVomc9qwCN8U0noLzotgppexANsq4WMv2FQa4LKqMDTrVepcTYkYRnDfs4jUMaUGsoa3cQGNLHP1WbWmorRxqoxUsSK43ukCUOOXevvrd%2FJKrwuu3pY7XOIGzcDRb2wZERWCl19zay2ntjuA4e9lF79d88x%2FyQjHs0eEQCHn7dEXcfSC7khVRe714kPwC62XyjZKzpzsTyvHnj5OiKtorNsMviKoQNpp0aKxfWDYnFXdpBKn26YXuWJHRi%2FU8n8v4N6%2BMFpX3Tr%2FauD0V6SFhZyjpzGY%2Fbb9JCz7%2ByeX34TdxUj%2BFNYMjpa708cRl53f3WiO5G2lTl5lGTgvIs9OyGWFyVzT9Mnl2u3ploXc81aJD%2FXY4gLWu%2FyM2lGBWnHoOBhP%2F4Bg2s4q6IITg297GDtFr3bni1yH6g5zW6OMFi6VlB8RQ%2Fx7tS8j4rmR4tM43pHnk5vRHZEgNVLgjxeXOewMKb2zb0GOqUBY6FHIkEXgM7WF15Ne6lJBl3D90TifrPt3LaUxK4mw4VKQQPQKV76YIErY1JfsM%2Bj%2F1JVimZiNw3Hp68kQc%2F%2Fs5TQAIRy%2BGyHda55YuG7KfEWsTApkjXIdXhMPHqpmXtyfGmSsp3jmZnLIDYDTW8UvkW%2Fho9FIVCFcsM%2BycmD07uTXnkBIwlLHzRI%2FdpOt5A5UwidEh30rMee5mSbTikHYWH3OWvn&X-Amz-Signature=d44345719b6446ca40249903acefdc817ae5bf3e3c65b210ce50b3276a1228ff&X-Amz-SignedHeaders=host&x-id=GetObject)


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

