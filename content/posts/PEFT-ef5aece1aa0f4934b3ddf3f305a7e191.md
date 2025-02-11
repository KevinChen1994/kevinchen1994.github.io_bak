---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466SSJTPX5U%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250211T072143Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjELf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIARrDRVTwzT4raFp3D2\
  WCs2IedI5tMWIoiEHbGq6MtVUAiEA%2BlTnTRVDq%2FAJhy1wa92krHQSf%2FqXk0lWppknjNfCkh\
  oqiAQI0P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHssEwYRP%2FF8L\
  k2r4ircA8Kbroq0MnI2XCcRxI5qDC0%2F2YihJssfg1iT3ubl44XMJDi1H7pdn5moE%2B%2FOOYb0\
  1tK37C4p1Vu6XImobuLQadlrY5zje9UUwFirRDQTBlx93jeIy5bE3fD1HjM6HgzLhheh0N35DImaz\
  UblgNy3FMTgtbW9OQc7f6koPyFVQvJJL85l8tqcW%2BSdExrl5bQMSpO0obedR%2BLGa25X3NJsE9\
  klxF0vOnfH1znHmrFx1bzvYMjDgg3bk7hdlf3QBGyfgI2sBhIbLPcz68hpTMtv%2B9dpa0DKlSxmk\
  GZxpJzKO7sv%2B%2B7cWR5PSsQvXsdmBxh7POzqMTnOAUGaNkWPVScj7MR%2F%2FwHAcXvIcXeBAk\
  hRTtDuVjUWqxIY5YBqgw5O0o5XkcixogQddJTev%2Btegs7bA6k11G6KO2GllVpT45hSEwtydsgJ2\
  CPFnbqR9TZWUSlQ7Zbk27JN7M93Sxo0tz5TjUKC62KbzSjZBf7AKH0Luc1hRbVE3iVhEanukP6lG3\
  kuTFeuGrCf2HkNLQNQ11RsomVi6amw%2FhXg8mg%2FXtPw7iNjIU%2Fo3bt3PjCxDa6cvpi1x0FWm\
  XheJb4zKnNyG5yc7OhQvujOCMrsJ5bOW6zf4q2%2BzdONJvxRh4qWje9lMP%2Fkq70GOqUBEZiGgt\
  Fcy4S31M5HlGIMIIZJVstySh0h3IpRc%2FfeEaPWtsluQMz5Kp%2BA5SBLOXDLUYJdYzfLi23g2Sp\
  hFKLo6834dHcoZM0gmnEOZe0ooLVwu0FjrAt1%2B4LVx0WJ4KIdxCyKYMMIkcEtOies9%2BLjXEQa\
  7gLsTZy2bP4MT%2FMc2TW81qcj2S7h4eVI4ueYLPxcHl16C%2BRaX3sFvaG1kFbKfndZgT%2Fw&X-\
  Amz-Signature=c7d8f0e0533fdaf99772e62dee644bd65f43ec7963eeb0675e308a24e579c17\
  f&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466RF4NRQUD%2F20250211%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250211T072032Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjELf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIQCtoz6ODZ11gY6aNsAbmAIxaJdqhn%2F3MHYPDjEW3jaKpwIgHMosmHKVKhxmiv5X4D1d\
        VTNBVAprrdQg4LG06LGm0SQqiAQI0P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc\
        0MjMxODM4MDUiDEpRq1wsDhzkkke6tircAwKvj9UQlG7Nhgcdslu6ercowOOhsgGIdYejg%\
        2FzoglTKWcaIJ6uoyGmaHdRvzeH46sHv0R8XRz7V8hsDYqeZQQivv46VlrktqlCOJqzULTg\
        N30Sj3roMdzgedw%2B2hR2Bcw0aYu1C2gwN8myJXuQnEw8rQRIoAxQ7y8zcLmCgsyQwnxg5\
        TODy%2FpGYe0%2FWBGGpAZKH0rZPmmGKA1uuSvL3ttN0L62PlsVbdAdxyPmLj3JIrFqdA3V\
        4WCLGF9zGAmCcWmUN9zVT2JmYurQnwqLDcmEsVr8Pkg%2FVwMK9hQ2n1xYnvI9l%2FUYoA2\
        Bj6DHMEZCwypQFzH2j%2BCJag6BJWj%2FsB44sKbKCPVOY5ksibAuG6ZzWpp%2FRs67%2Fb\
        acBNrpxvXA8rKWakXiAOTyee%2FNODqKbZ%2FsTDyz%2BcxaALmtyOtV0PA%2B67JMUv0Iw\
        q8QHeIznaL%2BKlMEl%2FWtLt72lXsMT2wGTIL3PUUhJOQF2gIlI5czxM1cz1n65Js4IJhw\
        KNiLEu2JwIff9H%2FI0N0z3CmSuv3un3zUOZ7H6QdkvmwKVJag5AUcukksGXcYdm6lLhbsU\
        HFNypBec6Z5LVFCALBdxDvGUfRf6jqPW625Cz7Yyy1V260Uq5ZBii3O99KEu8czrMLTkq70\
        GOqUBx8YkQv1FfBPI9EI56yQMuc1uVpMwP6gLfCK1txioNzAsuBWa1lJALtJim3lwkxDvvo\
        9wr1M8F7ucskthugKhl%2FEe5ou695ziUDTDy%2BeIckQIOVHniIEOdvffctcyuW8euIyZT\
        YLHEMMEoEjSRFb%2B9kJZI3lOTFbcKWLFwP06tSBDTDCpcZLna0TEYEj3bL2xEBml%2BZyc\
        tsTbl%2FRjFJS6vmkf7tPt&X-Amz-Signature=f5abcbf7894ffd8d2d92b452f6532684\
        342c940f77f98aef19fbb84dbe9c2300&X-Amz-SignedHeaders=host&x-id=GetObjec\
        t"
      expiry_time: "2025-02-11T08:20:32.349Z"
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
UPDATE_TIME: "2025-02-11T07:21:51.975Z"
EXPIRY_TIME: "2025-02-11T08:21:41.630Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663NMQALPF%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T072142Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAZYSYXCEBEQl1V6BmLr6t4tN9ss%2BZUvejPMQXy09r4KAiAhMrKRJ0ri7zDoyedSkj2XnnF%2BPuso0SX0E%2FMt41BHsCqIBAjQ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMM2Kw8nFGXYu%2BsbnHKtwDirmeNM6YiQUkPcQdB%2FvRS1wBrgP7%2B5IFgl3sANDnts7Prt05npf39r2eCVELXuXHpW353ZkP2zy9GA4FE%2BFYlKviTC1FUFlK8fliaf%2ByagTUfoE3nUlahwJKSTQAe6iJSKB8BRXvMVbrG%2FPu7xDA2bP0c1kZ1J3kSigiTJwcL91K9CcTadOdgkJsAG8fIXMiiIkLlZJxjNfghdl0vYyiiA3LvmQgq%2BC1gh2NmOokjz9S4aOnx6HGZy1w4yu%2BX4qY2ek2AfnLnga73NJiv04lYEKigyTY0b6LdOhK3RpH7lOPk4PlClqj1TK6owmIIiJWTrcpAALKhTTZJShq05AN1JYJac350EZm1OJDKPQ8asZeJwb%2FddGx5SV1k%2BwcbHnwHgJeiwEezA7H0kJMS%2FTwep0mk9VXGnQljqOOeqCMws%2ByIr82pjLtU8DJ1mPZRZg1mqPkD9oSy33q3XI2RHVAsRzZU%2F8e0dwJac5WL5biXWlKEr9WKRkWTbplbQ1s5owcNCwo6OdmKXmiD0q%2FTxu2pZhkAlLCt3AOJo84ZiY0NoC%2FfjlK4FDcHESjALfeY0kpb2RO%2BGXfBbepqI53JdIOCRrpJUrJRhbx0HSU75LTZ2vy4rCmBm6e2i8MJXow%2BOOrvQY6pgH7JGLpW1SWLq08OdVcK1afiDq%2BfSybjGTp%2FPYYHJXcTG8jCZxZiFUkcCEPFvnovt6YaXAlXiK1llaFMIE8apiep86pmUV5P3ObTEZptb6T0QdO49t0mK2wcYQZ%2BMthYUgzCl3gQ0r1DCkdODGJ24B39oYJbzHZ1gvAwJbcH70fM31QdxrDELeB0nhhA%2FTdqVRLOVYPOFVZm85SBvb%2BAWLBmvONnH7c&X-Amz-Signature=56560571eab0d3d4c986691c24d1f1db45d0caae47a27a142faa1a9e6f9f5fd2&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663NMQALPF%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T072142Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAZYSYXCEBEQl1V6BmLr6t4tN9ss%2BZUvejPMQXy09r4KAiAhMrKRJ0ri7zDoyedSkj2XnnF%2BPuso0SX0E%2FMt41BHsCqIBAjQ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMM2Kw8nFGXYu%2BsbnHKtwDirmeNM6YiQUkPcQdB%2FvRS1wBrgP7%2B5IFgl3sANDnts7Prt05npf39r2eCVELXuXHpW353ZkP2zy9GA4FE%2BFYlKviTC1FUFlK8fliaf%2ByagTUfoE3nUlahwJKSTQAe6iJSKB8BRXvMVbrG%2FPu7xDA2bP0c1kZ1J3kSigiTJwcL91K9CcTadOdgkJsAG8fIXMiiIkLlZJxjNfghdl0vYyiiA3LvmQgq%2BC1gh2NmOokjz9S4aOnx6HGZy1w4yu%2BX4qY2ek2AfnLnga73NJiv04lYEKigyTY0b6LdOhK3RpH7lOPk4PlClqj1TK6owmIIiJWTrcpAALKhTTZJShq05AN1JYJac350EZm1OJDKPQ8asZeJwb%2FddGx5SV1k%2BwcbHnwHgJeiwEezA7H0kJMS%2FTwep0mk9VXGnQljqOOeqCMws%2ByIr82pjLtU8DJ1mPZRZg1mqPkD9oSy33q3XI2RHVAsRzZU%2F8e0dwJac5WL5biXWlKEr9WKRkWTbplbQ1s5owcNCwo6OdmKXmiD0q%2FTxu2pZhkAlLCt3AOJo84ZiY0NoC%2FfjlK4FDcHESjALfeY0kpb2RO%2BGXfBbepqI53JdIOCRrpJUrJRhbx0HSU75LTZ2vy4rCmBm6e2i8MJXow%2BOOrvQY6pgH7JGLpW1SWLq08OdVcK1afiDq%2BfSybjGTp%2FPYYHJXcTG8jCZxZiFUkcCEPFvnovt6YaXAlXiK1llaFMIE8apiep86pmUV5P3ObTEZptb6T0QdO49t0mK2wcYQZ%2BMthYUgzCl3gQ0r1DCkdODGJ24B39oYJbzHZ1gvAwJbcH70fM31QdxrDELeB0nhhA%2FTdqVRLOVYPOFVZm85SBvb%2BAWLBmvONnH7c&X-Amz-Signature=3726113e0735086174a8ec41732e884dd8350eead30379fb6f118d95dc40774c&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663NMQALPF%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T072142Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAZYSYXCEBEQl1V6BmLr6t4tN9ss%2BZUvejPMQXy09r4KAiAhMrKRJ0ri7zDoyedSkj2XnnF%2BPuso0SX0E%2FMt41BHsCqIBAjQ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMM2Kw8nFGXYu%2BsbnHKtwDirmeNM6YiQUkPcQdB%2FvRS1wBrgP7%2B5IFgl3sANDnts7Prt05npf39r2eCVELXuXHpW353ZkP2zy9GA4FE%2BFYlKviTC1FUFlK8fliaf%2ByagTUfoE3nUlahwJKSTQAe6iJSKB8BRXvMVbrG%2FPu7xDA2bP0c1kZ1J3kSigiTJwcL91K9CcTadOdgkJsAG8fIXMiiIkLlZJxjNfghdl0vYyiiA3LvmQgq%2BC1gh2NmOokjz9S4aOnx6HGZy1w4yu%2BX4qY2ek2AfnLnga73NJiv04lYEKigyTY0b6LdOhK3RpH7lOPk4PlClqj1TK6owmIIiJWTrcpAALKhTTZJShq05AN1JYJac350EZm1OJDKPQ8asZeJwb%2FddGx5SV1k%2BwcbHnwHgJeiwEezA7H0kJMS%2FTwep0mk9VXGnQljqOOeqCMws%2ByIr82pjLtU8DJ1mPZRZg1mqPkD9oSy33q3XI2RHVAsRzZU%2F8e0dwJac5WL5biXWlKEr9WKRkWTbplbQ1s5owcNCwo6OdmKXmiD0q%2FTxu2pZhkAlLCt3AOJo84ZiY0NoC%2FfjlK4FDcHESjALfeY0kpb2RO%2BGXfBbepqI53JdIOCRrpJUrJRhbx0HSU75LTZ2vy4rCmBm6e2i8MJXow%2BOOrvQY6pgH7JGLpW1SWLq08OdVcK1afiDq%2BfSybjGTp%2FPYYHJXcTG8jCZxZiFUkcCEPFvnovt6YaXAlXiK1llaFMIE8apiep86pmUV5P3ObTEZptb6T0QdO49t0mK2wcYQZ%2BMthYUgzCl3gQ0r1DCkdODGJ24B39oYJbzHZ1gvAwJbcH70fM31QdxrDELeB0nhhA%2FTdqVRLOVYPOFVZm85SBvb%2BAWLBmvONnH7c&X-Amz-Signature=c5b067e7ebc1e54bf0a0ff6eef3daceb3e42de21cc67a0aa7f4d1debdec78a99&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663NMQALPF%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T072142Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAZYSYXCEBEQl1V6BmLr6t4tN9ss%2BZUvejPMQXy09r4KAiAhMrKRJ0ri7zDoyedSkj2XnnF%2BPuso0SX0E%2FMt41BHsCqIBAjQ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMM2Kw8nFGXYu%2BsbnHKtwDirmeNM6YiQUkPcQdB%2FvRS1wBrgP7%2B5IFgl3sANDnts7Prt05npf39r2eCVELXuXHpW353ZkP2zy9GA4FE%2BFYlKviTC1FUFlK8fliaf%2ByagTUfoE3nUlahwJKSTQAe6iJSKB8BRXvMVbrG%2FPu7xDA2bP0c1kZ1J3kSigiTJwcL91K9CcTadOdgkJsAG8fIXMiiIkLlZJxjNfghdl0vYyiiA3LvmQgq%2BC1gh2NmOokjz9S4aOnx6HGZy1w4yu%2BX4qY2ek2AfnLnga73NJiv04lYEKigyTY0b6LdOhK3RpH7lOPk4PlClqj1TK6owmIIiJWTrcpAALKhTTZJShq05AN1JYJac350EZm1OJDKPQ8asZeJwb%2FddGx5SV1k%2BwcbHnwHgJeiwEezA7H0kJMS%2FTwep0mk9VXGnQljqOOeqCMws%2ByIr82pjLtU8DJ1mPZRZg1mqPkD9oSy33q3XI2RHVAsRzZU%2F8e0dwJac5WL5biXWlKEr9WKRkWTbplbQ1s5owcNCwo6OdmKXmiD0q%2FTxu2pZhkAlLCt3AOJo84ZiY0NoC%2FfjlK4FDcHESjALfeY0kpb2RO%2BGXfBbepqI53JdIOCRrpJUrJRhbx0HSU75LTZ2vy4rCmBm6e2i8MJXow%2BOOrvQY6pgH7JGLpW1SWLq08OdVcK1afiDq%2BfSybjGTp%2FPYYHJXcTG8jCZxZiFUkcCEPFvnovt6YaXAlXiK1llaFMIE8apiep86pmUV5P3ObTEZptb6T0QdO49t0mK2wcYQZ%2BMthYUgzCl3gQ0r1DCkdODGJ24B39oYJbzHZ1gvAwJbcH70fM31QdxrDELeB0nhhA%2FTdqVRLOVYPOFVZm85SBvb%2BAWLBmvONnH7c&X-Amz-Signature=69ea1f93abf2b856049ba6b7193d8f7d0841c65d94334968f81b51001ccf66cf&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663NMQALPF%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T072142Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAZYSYXCEBEQl1V6BmLr6t4tN9ss%2BZUvejPMQXy09r4KAiAhMrKRJ0ri7zDoyedSkj2XnnF%2BPuso0SX0E%2FMt41BHsCqIBAjQ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMM2Kw8nFGXYu%2BsbnHKtwDirmeNM6YiQUkPcQdB%2FvRS1wBrgP7%2B5IFgl3sANDnts7Prt05npf39r2eCVELXuXHpW353ZkP2zy9GA4FE%2BFYlKviTC1FUFlK8fliaf%2ByagTUfoE3nUlahwJKSTQAe6iJSKB8BRXvMVbrG%2FPu7xDA2bP0c1kZ1J3kSigiTJwcL91K9CcTadOdgkJsAG8fIXMiiIkLlZJxjNfghdl0vYyiiA3LvmQgq%2BC1gh2NmOokjz9S4aOnx6HGZy1w4yu%2BX4qY2ek2AfnLnga73NJiv04lYEKigyTY0b6LdOhK3RpH7lOPk4PlClqj1TK6owmIIiJWTrcpAALKhTTZJShq05AN1JYJac350EZm1OJDKPQ8asZeJwb%2FddGx5SV1k%2BwcbHnwHgJeiwEezA7H0kJMS%2FTwep0mk9VXGnQljqOOeqCMws%2ByIr82pjLtU8DJ1mPZRZg1mqPkD9oSy33q3XI2RHVAsRzZU%2F8e0dwJac5WL5biXWlKEr9WKRkWTbplbQ1s5owcNCwo6OdmKXmiD0q%2FTxu2pZhkAlLCt3AOJo84ZiY0NoC%2FfjlK4FDcHESjALfeY0kpb2RO%2BGXfBbepqI53JdIOCRrpJUrJRhbx0HSU75LTZ2vy4rCmBm6e2i8MJXow%2BOOrvQY6pgH7JGLpW1SWLq08OdVcK1afiDq%2BfSybjGTp%2FPYYHJXcTG8jCZxZiFUkcCEPFvnovt6YaXAlXiK1llaFMIE8apiep86pmUV5P3ObTEZptb6T0QdO49t0mK2wcYQZ%2BMthYUgzCl3gQ0r1DCkdODGJ24B39oYJbzHZ1gvAwJbcH70fM31QdxrDELeB0nhhA%2FTdqVRLOVYPOFVZm85SBvb%2BAWLBmvONnH7c&X-Amz-Signature=8e8ccf5425431276b75c63ca0bbd56bc65b9eae567bd50f1baeeca2359370243&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UFXKJCK5%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T072142Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCCDQA5bdryypbp0zOBkIpGR3HSjW2%2Bgl1c9JWJhdqESQIhAP%2F%2B51KGd%2B0noTFr4mM%2BV8%2FLkLW1p%2F9RkvO4NVlN3ld4KogECND%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxwPgjeJBnjbArWZokq3AMaLOx8t5rC43LHR6fxIoX8QMbvjlE%2FO9%2BBoZ1Zchz4pyG6ePNHLgaQxzQUnSLcHi9GEyli4T5YxFB8OGp7zLLwyP3G2Sj3nwky6vs9durRwLjeVqe7XWDsTkGoYOw%2BNVzQMV0fwZB1lP%2FdnfccqG2QweaEcaDECqIpKQubscWcRIuI%2BqUttpZ%2FuQPHZUsLXOlsmg4hBinKad1I1wdVObNs8Pez%2B%2Byl%2BHvf3%2FCzfAmmzjGVv2HQ0ZFgZAXoBRJsEKhLEruqMuJePXM3rEr%2FmY49hiHanpGOnA%2Bd9KSxCiJLW7o4N1tsw4wGSdfqy%2BM%2FvodDoHRT4uxqpGBm9179FjswTOc4DgOgV6iOtykgju%2FFEABiW2%2Bo7zL0gmbH031knYda5K1oWVKqlSBC04FPq44OqtLF9hEs%2B%2Bz9O%2B5ZnceypfJrfPPMEdzWBgqldwaRcVzYUk2PqgJAcaRk%2F0YqVU6uBB26yefhlfvmbfGdjnVmytFdpht1rajUayXxxGIaWIDgDDsIlKfsi7Cr7sLl5zethcUbSbGFXgY9vCvtE7TzdZoA4UgLXn5CA0u2DBGBrwAqJomq0AgGkFTvPHcr%2BNz%2BFxKMg%2Frp9%2Fy%2B%2FFGzCWSK5U4ea%2FP%2BF1%2FD7gIHIjDd5Ku9BjqkAWMGASF9Q6zDB0DdO0OUpN2L35HfaW7%2F6GnYQC6rFgOtjiqhvvnGYEz%2Bzbi9F1pdCSBNWbwnFbXv2jhyV07DXMWH6reQzA6tPuYXw2VrGYwZNXEK2%2BJKzn5ICWLpq%2Fcq4171f8GwuYCiBYgGeLB2c0nHAsn6P6syTiicYLEmC6b7KRALbIEY5VDYxhiIctHQNlxKw9fes4TmUSqRz821nlyuJEK%2F&X-Amz-Signature=d33696c9169b4121932fd2350dbc25e153a2c9294f01514925cee964c0225412&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666LSKCUEA%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T072143Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIGTl%2FG5tvX8CThfBRZrMkEmAK6ibg9I41tTzWjfNku5LAiBSzvA0NdEe5RU8lbEw9Eu8bzjgQDXHoZ884gA6V7GGXSqIBAjQ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMK9ArhH0Y7iFyC8qIKtwD2Lu%2B7fRStVsbcJvfJeALzAXM%2FP9Nt87eXELjiq6bcY6iDM7GIeunZTEMUTogzZMLpFBQWdaWn2gEhpqW4bRSPNJv3cexuIiQU1Hd3l3r2KPKHBL9bYD%2F9JHKjxHHYwsaKwEkA37kYPyq6V5QfuvSR1SJYY9ZoyJHW3sEuHkApFU5SnOQ64%2BjfggVlmjWUoxT3xQZz2wPenZqaLtHEz5qzGLrmUS4RkWLO0EKh6zoIpoERyHGX2NZwQ27n1Wh8cOPUE7eN0fu4KQZJvAOJj7Cs7gt%2B2NRbHYtiCONJtb3CdfbKMzj2D7I8GVRnigo%2BVgWg9Dk2ecO7A%2Biup32BZLMy%2B38ZruFl2Ksq2KGpQi6grtEiRBBHKBaHURo5U%2F%2B2hLNB99DiPbsFk5SFC91uaAne2xXejSjTXhGWJB0Z5NrO2uVWS5dncPDFZfY%2BorSJlrQ2V3eByjPl22egmYlTzmtZ8AapAtKL6N%2FdHx%2FovdBtNDVwQ9vyu%2F3oamhMSapiKMaOcT%2FwumBjiLWko%2F%2FvE57%2BSNbdXiCkgZyghVsnQvM1URYOPwDjCURo1LXX5vFa50mlvAq3CXAnaNWCidVjSmcKOkOgOwRtolRpskltwd1qr5XgvDSq71KKGP8X3sw2eSrvQY6pgH9gRWRbPDGK1BEuYCnQWlSxx%2F2xHqEC5d1BZHE55I%2FSNMXmGQ%2BsM9Ztgi1TgABtohp3BJ66IV%2Bz4D%2FYYNsYZLfgNn3WZN20mXBtXbrWnbyGpJ1j44EYm%2BG%2FCdW367%2F4m3A3HbXfSQ84ARtvqsbkwf1OiKLHRIeh7HnyjB8l6eY6q7x5pFvjjFs3wnMtNykRWeian5g7BmeZYUIM7rt%2BjZ4fRTlVm5L&X-Amz-Signature=02b9d389e912a0297070423ec9edcd31777f1c4da8e901e22e11efeec8525bd3&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663NMQALPF%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T072142Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAZYSYXCEBEQl1V6BmLr6t4tN9ss%2BZUvejPMQXy09r4KAiAhMrKRJ0ri7zDoyedSkj2XnnF%2BPuso0SX0E%2FMt41BHsCqIBAjQ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMM2Kw8nFGXYu%2BsbnHKtwDirmeNM6YiQUkPcQdB%2FvRS1wBrgP7%2B5IFgl3sANDnts7Prt05npf39r2eCVELXuXHpW353ZkP2zy9GA4FE%2BFYlKviTC1FUFlK8fliaf%2ByagTUfoE3nUlahwJKSTQAe6iJSKB8BRXvMVbrG%2FPu7xDA2bP0c1kZ1J3kSigiTJwcL91K9CcTadOdgkJsAG8fIXMiiIkLlZJxjNfghdl0vYyiiA3LvmQgq%2BC1gh2NmOokjz9S4aOnx6HGZy1w4yu%2BX4qY2ek2AfnLnga73NJiv04lYEKigyTY0b6LdOhK3RpH7lOPk4PlClqj1TK6owmIIiJWTrcpAALKhTTZJShq05AN1JYJac350EZm1OJDKPQ8asZeJwb%2FddGx5SV1k%2BwcbHnwHgJeiwEezA7H0kJMS%2FTwep0mk9VXGnQljqOOeqCMws%2ByIr82pjLtU8DJ1mPZRZg1mqPkD9oSy33q3XI2RHVAsRzZU%2F8e0dwJac5WL5biXWlKEr9WKRkWTbplbQ1s5owcNCwo6OdmKXmiD0q%2FTxu2pZhkAlLCt3AOJo84ZiY0NoC%2FfjlK4FDcHESjALfeY0kpb2RO%2BGXfBbepqI53JdIOCRrpJUrJRhbx0HSU75LTZ2vy4rCmBm6e2i8MJXow%2BOOrvQY6pgH7JGLpW1SWLq08OdVcK1afiDq%2BfSybjGTp%2FPYYHJXcTG8jCZxZiFUkcCEPFvnovt6YaXAlXiK1llaFMIE8apiep86pmUV5P3ObTEZptb6T0QdO49t0mK2wcYQZ%2BMthYUgzCl3gQ0r1DCkdODGJ24B39oYJbzHZ1gvAwJbcH70fM31QdxrDELeB0nhhA%2FTdqVRLOVYPOFVZm85SBvb%2BAWLBmvONnH7c&X-Amz-Signature=81b06181365988ff43b8a27b3878e2a30bd2ef1ae11e20a551cd5d55b8f74ada&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663NMQALPF%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T072142Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAZYSYXCEBEQl1V6BmLr6t4tN9ss%2BZUvejPMQXy09r4KAiAhMrKRJ0ri7zDoyedSkj2XnnF%2BPuso0SX0E%2FMt41BHsCqIBAjQ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMM2Kw8nFGXYu%2BsbnHKtwDirmeNM6YiQUkPcQdB%2FvRS1wBrgP7%2B5IFgl3sANDnts7Prt05npf39r2eCVELXuXHpW353ZkP2zy9GA4FE%2BFYlKviTC1FUFlK8fliaf%2ByagTUfoE3nUlahwJKSTQAe6iJSKB8BRXvMVbrG%2FPu7xDA2bP0c1kZ1J3kSigiTJwcL91K9CcTadOdgkJsAG8fIXMiiIkLlZJxjNfghdl0vYyiiA3LvmQgq%2BC1gh2NmOokjz9S4aOnx6HGZy1w4yu%2BX4qY2ek2AfnLnga73NJiv04lYEKigyTY0b6LdOhK3RpH7lOPk4PlClqj1TK6owmIIiJWTrcpAALKhTTZJShq05AN1JYJac350EZm1OJDKPQ8asZeJwb%2FddGx5SV1k%2BwcbHnwHgJeiwEezA7H0kJMS%2FTwep0mk9VXGnQljqOOeqCMws%2ByIr82pjLtU8DJ1mPZRZg1mqPkD9oSy33q3XI2RHVAsRzZU%2F8e0dwJac5WL5biXWlKEr9WKRkWTbplbQ1s5owcNCwo6OdmKXmiD0q%2FTxu2pZhkAlLCt3AOJo84ZiY0NoC%2FfjlK4FDcHESjALfeY0kpb2RO%2BGXfBbepqI53JdIOCRrpJUrJRhbx0HSU75LTZ2vy4rCmBm6e2i8MJXow%2BOOrvQY6pgH7JGLpW1SWLq08OdVcK1afiDq%2BfSybjGTp%2FPYYHJXcTG8jCZxZiFUkcCEPFvnovt6YaXAlXiK1llaFMIE8apiep86pmUV5P3ObTEZptb6T0QdO49t0mK2wcYQZ%2BMthYUgzCl3gQ0r1DCkdODGJ24B39oYJbzHZ1gvAwJbcH70fM31QdxrDELeB0nhhA%2FTdqVRLOVYPOFVZm85SBvb%2BAWLBmvONnH7c&X-Amz-Signature=bec7d93f44c30c8347433ee00d4af6c531ce34eb0b87a1b53c6cda89009a7929&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663NMQALPF%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T072142Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAZYSYXCEBEQl1V6BmLr6t4tN9ss%2BZUvejPMQXy09r4KAiAhMrKRJ0ri7zDoyedSkj2XnnF%2BPuso0SX0E%2FMt41BHsCqIBAjQ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMM2Kw8nFGXYu%2BsbnHKtwDirmeNM6YiQUkPcQdB%2FvRS1wBrgP7%2B5IFgl3sANDnts7Prt05npf39r2eCVELXuXHpW353ZkP2zy9GA4FE%2BFYlKviTC1FUFlK8fliaf%2ByagTUfoE3nUlahwJKSTQAe6iJSKB8BRXvMVbrG%2FPu7xDA2bP0c1kZ1J3kSigiTJwcL91K9CcTadOdgkJsAG8fIXMiiIkLlZJxjNfghdl0vYyiiA3LvmQgq%2BC1gh2NmOokjz9S4aOnx6HGZy1w4yu%2BX4qY2ek2AfnLnga73NJiv04lYEKigyTY0b6LdOhK3RpH7lOPk4PlClqj1TK6owmIIiJWTrcpAALKhTTZJShq05AN1JYJac350EZm1OJDKPQ8asZeJwb%2FddGx5SV1k%2BwcbHnwHgJeiwEezA7H0kJMS%2FTwep0mk9VXGnQljqOOeqCMws%2ByIr82pjLtU8DJ1mPZRZg1mqPkD9oSy33q3XI2RHVAsRzZU%2F8e0dwJac5WL5biXWlKEr9WKRkWTbplbQ1s5owcNCwo6OdmKXmiD0q%2FTxu2pZhkAlLCt3AOJo84ZiY0NoC%2FfjlK4FDcHESjALfeY0kpb2RO%2BGXfBbepqI53JdIOCRrpJUrJRhbx0HSU75LTZ2vy4rCmBm6e2i8MJXow%2BOOrvQY6pgH7JGLpW1SWLq08OdVcK1afiDq%2BfSybjGTp%2FPYYHJXcTG8jCZxZiFUkcCEPFvnovt6YaXAlXiK1llaFMIE8apiep86pmUV5P3ObTEZptb6T0QdO49t0mK2wcYQZ%2BMthYUgzCl3gQ0r1DCkdODGJ24B39oYJbzHZ1gvAwJbcH70fM31QdxrDELeB0nhhA%2FTdqVRLOVYPOFVZm85SBvb%2BAWLBmvONnH7c&X-Amz-Signature=f814f4afdfd492e2bc610427682a972e3d6bd650117c9ce91203053593619969&X-Amz-SignedHeaders=host&x-id=GetObject)


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

