---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466727K2RPK%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250206T202511Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEEsaCXVzLXdlc3QtMiJIMEYCIQDzx0nLf0rxUQ%2FXBHa7UfwcEmyO7M0nCYrttlw7KUtCgQIhA\
  Ol4Mv6kPIhcwsqK463dy%2F9u4hlDSb0bFfkp116kO4N0Kv8DCGQQABoMNjM3NDIzMTgzODA1IgzS\
  xbeHAzhj%2FX0QxMkq3AM8ui%2FQrlMJET17GqLcE0OfHMizUrv6q7czbQ1QTZjXaX17GvyP9FnSB\
  VBGpj9OAObWqQCMlzGlCPi69QdNBebI0gNWGEKPsGMueam2Vj3NLOlTlnsmln%2BpZ4Dnnk8N9iKu\
  4dhFMi7bLE89yVA7boQkMTHo9zsr45rmvmb6NQ%2BAC32G8wjHwwyVsixG7CRgliRkxAzEF8DQVzm\
  f9gE8abiQqb71FTAD%2BEFEZyyNOo4hJn5kIXiTK69H%2BpEZLP1TuoWlMxAOfN4Jz1u%2F0elr5q\
  sc92iDhvZ%2Bgy0qorjIWH7D2%2F9PygeLqMjaVV3K%2BOjVVoCBSLeDmEiBq5ADKeirjtCsAfbgv\
  8y3kykmZo1ZbhZGiYqe2EgUPxuTC0LfS7Oz4vDh7C6xPlVHrr60uPMNp3nMfOJtAqyKqrZrR7txtu\
  bOMRAItb5hQTdjtgSmQL5z1yw4MKhFpec6k3Yz30U%2F7ikkzDyAe44bNeu1RPP9KsVsxlgmRqjms\
  ezznG0Ve6jAPvM%2FmscIh22RzuGX9CS4%2Bb4QRs1RekS67LOZqCFw8mSZzQLy26Lv59v0LrLtgg\
  M0SXUqmB5ADCTZNSeSn6MfK%2BmljYixaUBcyRb6wNheRnr7gtUa4XCD%2F1myX5PmbzC4%2FZO9B\
  jqkARtLQecgxBXkVvdeLZiKcpmpFrTq%2BdDH09tqFm6xsyOdlugmYkOBAyxvC2tRUfX%2FZAqlSE\
  c49%2FpN2GxmnCce5x%2FOWKw%2BY%2FYeGcJXbhCc9gCz52sitNou%2BY8Olb2nombWmf4JBwfys\
  o4h5qZiZvbMgUO985sXaNca0iE6i4QtfCIdb3qGW0ypitxhmxAR7DO91OWI4iZxvi6NmE3oAe9lIb\
  XP9Spf&X-Amz-Signature=418b0e3c733281d3489701eafc04333c968bfbb9afeef2cceb3521\
  fa8ad57537&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466TIB27RFX%2F20250206%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250206T202340Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEEsaCXVzLXdlc3QtMiJHMEUCIEgphL4ECzbErVM0nuaM50zn%2B3BVW\
        %2F6l6puBq%2BQ%2FRFEnAiEArhwB2EVOuUdD6Jjor2ibTdeMepeeOa98KK0aQDFxUCYq%2\
        FwMIZBAAGgw2Mzc0MjMxODM4MDUiDOAYwZ%2FKiwQd8ODVwCrcAwqIc%2BN2g8zTeUHES4R\
        S82lRCSuTmwGrOaqFiDuPNLyCnh0cbg3IgdRKb68Cg5BraQei6N9iCZFtiFH0z8O6ou4uMI\
        z5Q%2BVnXdgBgju7qDDVhs0GWUNcrb%2Bbfb4Wyl%2B8TGuWlywbmmSPLpT3rWkQ5w0SzGg\
        ooqni7LbejRvsylsCSUy5QdOMUjMJT124Qxt%2BW1V6Jg6N1Iz5ex8MwKVHOHih59Ep9Ata\
        64tRuoadLmbjjOuKb4mn8IT6Iv9V7k1hD1rdFA5m9%2FyJMHsYVNMbYLlpIMDPwDOpLQBYK\
        Ldv790T3iJzrrGwcOVClXVoyszSZCemBG5NzQ8sSz59luKvY%2FkSKsTYDmi1pluBIkeKPO\
        dzwFHMZYFVRL3RH98jrcsr59h7ZGQlA7hUQ4DA7EZaOSSHnzfP0dP3VKqdnSUDtqXJPkMPx\
        pDss5cp9OkUBPn%2F0KBJLcR7F0YC2rY1TdXIUgdmwy8ONPPdgg7V6l%2FIak%2FVdo%2Fp\
        1mKOhGyg2exm49sBH9E3NtyfOuuFb0Sdu3ManUKikeWaOibHSbXOC3NRlq3Z0IsoJJwFgY9\
        cFQcn0AShP3YVveFgsn34Ze%2FsJKlntIkbxRSofFeK5ihzlm%2BQs3S6iQLiDfNZD85muf\
        97MJv9k70GOqUBo98hviyZHsjan58CH%2Fw6762aU5uAd19HP%2FKkdevfZ4oJYu12EFJOJ\
        BlnxKWvEJgLY7TL5vjrkhKyVXG4%2BQklToiC6BTiZZZ0NZE2%2BT5G8U2aQOi7z7yU6SY7\
        J%2B8htBBajDTh06YtEGsYDLMPr3OwbsQZ%2FW5XUuVVf0of8%2Bco%2FjJG%2BWqKPzu5V\
        0%2BTKDwXFg%2FyTEZWhKmeX0wZ7ZGjkbMY79Jq9nN%2F&X-Amz-Signature=a71f41527\
        ca27c34642c9a524f044608b9341d6500e0d2fdd072f8b0888b38f0&X-Amz-SignedHea\
        ders=host&x-id=GetObject"
      expiry_time: "2025-02-06T21:23:40.160Z"
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
UPDATE_TIME: "2025-02-06T20:25:17.284Z"
EXPIRY_TIME: "2025-02-06T21:25:09.188Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SL3ZTL4I%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T202509Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEsaCXVzLXdlc3QtMiJHMEUCIQCtNMnPslMJVha5CL6uPKFCRvl7J6JHQXDFiRJlu9Mg5gIgWiyKhibnI6UBd6IhBTU7gT3C3q7cCCUOoaatZIFNllYq%2FwMIYxAAGgw2Mzc0MjMxODM4MDUiDP%2BOfb0hu7yEG1XWnyrcA%2F5Xj3jpoj8%2BBP7r%2BntiUudIwp0OWr4eVL4%2Fp9QDPq3y6QxjK90a7Q0TWzhdxYL2T2YJsremaRPdtoXV3w70G9YAc6EM30LaAy6SiqbPtX2%2BVXbPBh7JrQJzeQvziM26xt0DsLXSEsZ8z8GmSf5Wp1qlgg4UGTHntlg4X%2BfgS8aOVMMk60l%2FmG6BLNlCOd1s6%2FNQXnGdT7PV5fz8ZFfblBR1C3wLexsX29LatavKkGCTVyvd6mswsSDsN7hseTSugrvHQPE4bOuOK2pW%2BRjAWg5mDdntX0ZrUsvY2lxvSG5QW18kuFF6SawibMzIgdb2t9lgbU6IHYGDZquoU2Jot25Bk86d%2BjS9Tru7QIcXXUNrWYRh%2Fb5AbAW05VI7fq3jXhmlEepqmsCBr8hzlftlipTbE8mY4yyLMvsPvEwJEgU0%2FDjpBnm4hBaieDsymeneSc%2FQ%2FqEMSMI6mzM2UpN465KWf9NogCCLAm9AJ96y1V4UYzI%2FAfXWDel1mOPzLAz3Qq9qnqEqzcJz4AcPdjaYrtNtWYYXwEGXOLK5WUHsk8Tz2cQpfgXC0%2BQPdB3vMtyLeiyIm66wKwCF43HQV%2F9tVCcetLw3R%2BQXJIhdmUNV2bGKzWTzW%2BU2C%2Bh%2BpQ0%2BMNr9k70GOqUBMniwQFbtg9TXrFQdCICBCsQI9j6Z8K6JZ%2B3L3QguyqxHCZF8gAA6g6SIvMCrpg%2Fbtw8anjAeTc8n7%2BW7PK5YI3Sju7ePrIIBRCllGdhtJr5U7Vl31dLe%2BncwA8%2FPodI1ivdb1T3TtvOOwJMuJpUYyk0L44t0EvyIQ3P21NQgheGYmDNzVUhAPUa%2BJ%2BBipem24kfEkjqXnHFii1Q5f7YrsnLT5xo3&X-Amz-Signature=1028e5d609ff98a8c0ed830838b90ba17e88324c6d5bd55425868ec5620ed6fd&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SL3ZTL4I%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T202509Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEsaCXVzLXdlc3QtMiJHMEUCIQCtNMnPslMJVha5CL6uPKFCRvl7J6JHQXDFiRJlu9Mg5gIgWiyKhibnI6UBd6IhBTU7gT3C3q7cCCUOoaatZIFNllYq%2FwMIYxAAGgw2Mzc0MjMxODM4MDUiDP%2BOfb0hu7yEG1XWnyrcA%2F5Xj3jpoj8%2BBP7r%2BntiUudIwp0OWr4eVL4%2Fp9QDPq3y6QxjK90a7Q0TWzhdxYL2T2YJsremaRPdtoXV3w70G9YAc6EM30LaAy6SiqbPtX2%2BVXbPBh7JrQJzeQvziM26xt0DsLXSEsZ8z8GmSf5Wp1qlgg4UGTHntlg4X%2BfgS8aOVMMk60l%2FmG6BLNlCOd1s6%2FNQXnGdT7PV5fz8ZFfblBR1C3wLexsX29LatavKkGCTVyvd6mswsSDsN7hseTSugrvHQPE4bOuOK2pW%2BRjAWg5mDdntX0ZrUsvY2lxvSG5QW18kuFF6SawibMzIgdb2t9lgbU6IHYGDZquoU2Jot25Bk86d%2BjS9Tru7QIcXXUNrWYRh%2Fb5AbAW05VI7fq3jXhmlEepqmsCBr8hzlftlipTbE8mY4yyLMvsPvEwJEgU0%2FDjpBnm4hBaieDsymeneSc%2FQ%2FqEMSMI6mzM2UpN465KWf9NogCCLAm9AJ96y1V4UYzI%2FAfXWDel1mOPzLAz3Qq9qnqEqzcJz4AcPdjaYrtNtWYYXwEGXOLK5WUHsk8Tz2cQpfgXC0%2BQPdB3vMtyLeiyIm66wKwCF43HQV%2F9tVCcetLw3R%2BQXJIhdmUNV2bGKzWTzW%2BU2C%2Bh%2BpQ0%2BMNr9k70GOqUBMniwQFbtg9TXrFQdCICBCsQI9j6Z8K6JZ%2B3L3QguyqxHCZF8gAA6g6SIvMCrpg%2Fbtw8anjAeTc8n7%2BW7PK5YI3Sju7ePrIIBRCllGdhtJr5U7Vl31dLe%2BncwA8%2FPodI1ivdb1T3TtvOOwJMuJpUYyk0L44t0EvyIQ3P21NQgheGYmDNzVUhAPUa%2BJ%2BBipem24kfEkjqXnHFii1Q5f7YrsnLT5xo3&X-Amz-Signature=6de4a51f1f8fd54ac5f775e206f33640af08a3a2dd12134094f1928e12452d90&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SL3ZTL4I%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T202509Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEsaCXVzLXdlc3QtMiJHMEUCIQCtNMnPslMJVha5CL6uPKFCRvl7J6JHQXDFiRJlu9Mg5gIgWiyKhibnI6UBd6IhBTU7gT3C3q7cCCUOoaatZIFNllYq%2FwMIYxAAGgw2Mzc0MjMxODM4MDUiDP%2BOfb0hu7yEG1XWnyrcA%2F5Xj3jpoj8%2BBP7r%2BntiUudIwp0OWr4eVL4%2Fp9QDPq3y6QxjK90a7Q0TWzhdxYL2T2YJsremaRPdtoXV3w70G9YAc6EM30LaAy6SiqbPtX2%2BVXbPBh7JrQJzeQvziM26xt0DsLXSEsZ8z8GmSf5Wp1qlgg4UGTHntlg4X%2BfgS8aOVMMk60l%2FmG6BLNlCOd1s6%2FNQXnGdT7PV5fz8ZFfblBR1C3wLexsX29LatavKkGCTVyvd6mswsSDsN7hseTSugrvHQPE4bOuOK2pW%2BRjAWg5mDdntX0ZrUsvY2lxvSG5QW18kuFF6SawibMzIgdb2t9lgbU6IHYGDZquoU2Jot25Bk86d%2BjS9Tru7QIcXXUNrWYRh%2Fb5AbAW05VI7fq3jXhmlEepqmsCBr8hzlftlipTbE8mY4yyLMvsPvEwJEgU0%2FDjpBnm4hBaieDsymeneSc%2FQ%2FqEMSMI6mzM2UpN465KWf9NogCCLAm9AJ96y1V4UYzI%2FAfXWDel1mOPzLAz3Qq9qnqEqzcJz4AcPdjaYrtNtWYYXwEGXOLK5WUHsk8Tz2cQpfgXC0%2BQPdB3vMtyLeiyIm66wKwCF43HQV%2F9tVCcetLw3R%2BQXJIhdmUNV2bGKzWTzW%2BU2C%2Bh%2BpQ0%2BMNr9k70GOqUBMniwQFbtg9TXrFQdCICBCsQI9j6Z8K6JZ%2B3L3QguyqxHCZF8gAA6g6SIvMCrpg%2Fbtw8anjAeTc8n7%2BW7PK5YI3Sju7ePrIIBRCllGdhtJr5U7Vl31dLe%2BncwA8%2FPodI1ivdb1T3TtvOOwJMuJpUYyk0L44t0EvyIQ3P21NQgheGYmDNzVUhAPUa%2BJ%2BBipem24kfEkjqXnHFii1Q5f7YrsnLT5xo3&X-Amz-Signature=455ff94f1e0acfe24fc7089fda9461fa749aca7e56febe24ab33dea2636bb427&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SL3ZTL4I%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T202509Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEsaCXVzLXdlc3QtMiJHMEUCIQCtNMnPslMJVha5CL6uPKFCRvl7J6JHQXDFiRJlu9Mg5gIgWiyKhibnI6UBd6IhBTU7gT3C3q7cCCUOoaatZIFNllYq%2FwMIYxAAGgw2Mzc0MjMxODM4MDUiDP%2BOfb0hu7yEG1XWnyrcA%2F5Xj3jpoj8%2BBP7r%2BntiUudIwp0OWr4eVL4%2Fp9QDPq3y6QxjK90a7Q0TWzhdxYL2T2YJsremaRPdtoXV3w70G9YAc6EM30LaAy6SiqbPtX2%2BVXbPBh7JrQJzeQvziM26xt0DsLXSEsZ8z8GmSf5Wp1qlgg4UGTHntlg4X%2BfgS8aOVMMk60l%2FmG6BLNlCOd1s6%2FNQXnGdT7PV5fz8ZFfblBR1C3wLexsX29LatavKkGCTVyvd6mswsSDsN7hseTSugrvHQPE4bOuOK2pW%2BRjAWg5mDdntX0ZrUsvY2lxvSG5QW18kuFF6SawibMzIgdb2t9lgbU6IHYGDZquoU2Jot25Bk86d%2BjS9Tru7QIcXXUNrWYRh%2Fb5AbAW05VI7fq3jXhmlEepqmsCBr8hzlftlipTbE8mY4yyLMvsPvEwJEgU0%2FDjpBnm4hBaieDsymeneSc%2FQ%2FqEMSMI6mzM2UpN465KWf9NogCCLAm9AJ96y1V4UYzI%2FAfXWDel1mOPzLAz3Qq9qnqEqzcJz4AcPdjaYrtNtWYYXwEGXOLK5WUHsk8Tz2cQpfgXC0%2BQPdB3vMtyLeiyIm66wKwCF43HQV%2F9tVCcetLw3R%2BQXJIhdmUNV2bGKzWTzW%2BU2C%2Bh%2BpQ0%2BMNr9k70GOqUBMniwQFbtg9TXrFQdCICBCsQI9j6Z8K6JZ%2B3L3QguyqxHCZF8gAA6g6SIvMCrpg%2Fbtw8anjAeTc8n7%2BW7PK5YI3Sju7ePrIIBRCllGdhtJr5U7Vl31dLe%2BncwA8%2FPodI1ivdb1T3TtvOOwJMuJpUYyk0L44t0EvyIQ3P21NQgheGYmDNzVUhAPUa%2BJ%2BBipem24kfEkjqXnHFii1Q5f7YrsnLT5xo3&X-Amz-Signature=ce1a853033aa15f9b51886f04bc799b101893e9c713fe5182e622bcacc2e6155&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SL3ZTL4I%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T202509Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEsaCXVzLXdlc3QtMiJHMEUCIQCtNMnPslMJVha5CL6uPKFCRvl7J6JHQXDFiRJlu9Mg5gIgWiyKhibnI6UBd6IhBTU7gT3C3q7cCCUOoaatZIFNllYq%2FwMIYxAAGgw2Mzc0MjMxODM4MDUiDP%2BOfb0hu7yEG1XWnyrcA%2F5Xj3jpoj8%2BBP7r%2BntiUudIwp0OWr4eVL4%2Fp9QDPq3y6QxjK90a7Q0TWzhdxYL2T2YJsremaRPdtoXV3w70G9YAc6EM30LaAy6SiqbPtX2%2BVXbPBh7JrQJzeQvziM26xt0DsLXSEsZ8z8GmSf5Wp1qlgg4UGTHntlg4X%2BfgS8aOVMMk60l%2FmG6BLNlCOd1s6%2FNQXnGdT7PV5fz8ZFfblBR1C3wLexsX29LatavKkGCTVyvd6mswsSDsN7hseTSugrvHQPE4bOuOK2pW%2BRjAWg5mDdntX0ZrUsvY2lxvSG5QW18kuFF6SawibMzIgdb2t9lgbU6IHYGDZquoU2Jot25Bk86d%2BjS9Tru7QIcXXUNrWYRh%2Fb5AbAW05VI7fq3jXhmlEepqmsCBr8hzlftlipTbE8mY4yyLMvsPvEwJEgU0%2FDjpBnm4hBaieDsymeneSc%2FQ%2FqEMSMI6mzM2UpN465KWf9NogCCLAm9AJ96y1V4UYzI%2FAfXWDel1mOPzLAz3Qq9qnqEqzcJz4AcPdjaYrtNtWYYXwEGXOLK5WUHsk8Tz2cQpfgXC0%2BQPdB3vMtyLeiyIm66wKwCF43HQV%2F9tVCcetLw3R%2BQXJIhdmUNV2bGKzWTzW%2BU2C%2Bh%2BpQ0%2BMNr9k70GOqUBMniwQFbtg9TXrFQdCICBCsQI9j6Z8K6JZ%2B3L3QguyqxHCZF8gAA6g6SIvMCrpg%2Fbtw8anjAeTc8n7%2BW7PK5YI3Sju7ePrIIBRCllGdhtJr5U7Vl31dLe%2BncwA8%2FPodI1ivdb1T3TtvOOwJMuJpUYyk0L44t0EvyIQ3P21NQgheGYmDNzVUhAPUa%2BJ%2BBipem24kfEkjqXnHFii1Q5f7YrsnLT5xo3&X-Amz-Signature=37d9424488121e06731f6eeae54ea07c507baefcdf28dfd68a9dff387d823295&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VOQSHEND%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T202510Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEsaCXVzLXdlc3QtMiJHMEUCIA8rwqfIBM8%2BTOH1BOp6nDaVNSa9DsSAjVkwR2dQKh%2FdAiEA1f4GwAgylVuZ%2FLY3m24EApiFAlELOzUJXbveVpJ0cskq%2FwMIZBAAGgw2Mzc0MjMxODM4MDUiDFQubCGXdLO4t9xL3yrcAysuyjbeW8FBnoMPjjiLAN%2FIYCQdM1lvao4l8FG%2BeYMP88jZZsSdOPlD1QqA86UMxaOWoGB9uH%2BkoguHFPAljrdjDA5Va%2Bspx8eHYLSgTXnM%2F%2BdlHNsE9Y4CKngO62CLfrOnJO3BdEeCIEtI%2FMtmyquMome6it8gyIxrrQXp7vhJ%2FliirLu1XNKQ03c4J72elG2B%2FIv5fGFT7p2PN48%2FgKPEUGQr8gHhcKBtyD7q5X4aORedaV%2BDfM%2B%2BPXG98hmI46znQLvDnsTWFR15Qlwvz5bA0nxdyoZiZjbSxji3xt4maxQntumfixPQodoliohXIQFXpO8Br6A2XnqryxW4FH9c6UUBIzvVDM1%2B2DbCniDgf8PsRqqdOyCGqI0gTZertclgpdH4QdHR%2FzdQxI7tA7kivOAfSmN8iKCtHEeFjVQWv3mfar0PnzkTrNkAZIKzWzN1KZt%2FjDsYRhep%2FzYnMJmqwv3mVKqks1xr04pzsnFrBkVz0e%2FY0Jo%2BeuCbLF2WfsHvgm6RyR9fNhD%2BJNCol2dKtVsRfVeMInh1tYePBPHJk%2FlDXI6j4ggQSCGaBATeCVd2BRnX04HBkQ8EDAVKlIYZvx%2BHY5i2yFAQk8qoqiTqpHmr9HqnL97ckRGiMJH9k70GOqUBENCkshFBPwCSq%2Bat3xLmtQ16mZdlzT9%2BSjvg%2FvQWqBpuDSKQJOGhfJ5CD85asZgp%2Fp8CONhjxd6ADqEfhGAQ8Ty0bvPNgY2iU6q7oP60rouesdXfWima1tcTtD2uwxr4VEVIJ1tGs5ExBoNmxK%2Fv2ouzuacIMh09NwJZIZgi5z34kQ91zmWK0i5O0%2F%2BGOJCDYthTo5AGUELG5qsMCTViIRjjQyvJ&X-Amz-Signature=111b604bade1f2d3a25af8a836a8b50d936128f4ead5f1e181dae8c21077fcc8&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666NC7WTWA%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T202511Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEsaCXVzLXdlc3QtMiJHMEUCIE%2BS%2F0Gm5b6Gpjl%2BQUZdjeh5dxYg%2BlG327VSTg5t1yNJAiEAuoP098tMr5d1NK%2FURAV7DcmDL5TIPadZUFDWvG2V0k8q%2FwMIZBAAGgw2Mzc0MjMxODM4MDUiDOXIKPIkZ1VNFgRpbircA%2FMVI9lfaDNNH1Y%2FwSfxIfN3%2FSr1AmP41xFqplbvA1JH6WsIURPnvU%2BCwHqelDj4sLZ2IQl%2FoN%2B5Y6iJP5fc40G3c10NuMGPhIeA5%2B11afrSux2D6N4gSUmXOq%2FtwTANLYYrp1f2xx6%2Byne16pkbj6KTxmHbCujqr1tFwIHn59j%2FQgn5mc3BodNZSj7isC8z450uaJi7HiQwStxgqJz%2FdND3LgmmcZllmdTnH35cMEbMBOm3hmVTc0vUZf8c%2BGUhWzIvngSlZymNK4Epg8Zz6Jz8Q2jIWeXDY44tL0FhMZlYXu%2BzlWBAk1Qh8%2B9nFrRfhgXvPJalVc%2F7QAzUMIsdxmkp0t5FsaA935eL5Gk%2Fe78gcyTXJfddzMAvMCIUGnMXVFDm79jpJkYH1pfKsx90Ny32G3cn2BWj3VSrRDTAJf%2F74t%2B3Hzj2gPpBO30iUgAqLqilDyRbOaL8MXV4ocb2QTfieH5nSubpFkefPA%2BsHAfYKk4dozLn76WyEvLO8v33I%2B%2FPuq9e3UJWYwyz3VItnrBRNNYmyR7umFe3W9mou38ckeaTj5UNyZm1xRT%2Bqg93Hkr4JhJ1fUk87Mjlj5P4RqRrzK9Nzi%2FwPv0ItW%2FSqM8kCQvsJRrndgUuuCReMMT%2Bk70GOqUBqTfnFHX2%2FXxCJ4hRs6uZnoeQxhOvqAx9smoJnYvNyPTiCry2CPORHidTutimXPIKsfCV2OVh%2Bce3fApqGOBditn2MGhRbvXNfp8FBsDK%2Bzq1HoSczvifMDW6TKQiGk%2BRgyIo%2BdSAaHLSeNpBYQJrNtmZWDZuQOA%2Fk140lKcCKcUjAk%2BowwVcOUy0dyazSsYotpNxz%2FhykwgQboldAc3KIDLa4B3M&X-Amz-Signature=fb36be3ca660ec0b32eb14b76e44c3a7f9b0013067d3a952cb091380350cef40&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SL3ZTL4I%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T202509Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEsaCXVzLXdlc3QtMiJHMEUCIQCtNMnPslMJVha5CL6uPKFCRvl7J6JHQXDFiRJlu9Mg5gIgWiyKhibnI6UBd6IhBTU7gT3C3q7cCCUOoaatZIFNllYq%2FwMIYxAAGgw2Mzc0MjMxODM4MDUiDP%2BOfb0hu7yEG1XWnyrcA%2F5Xj3jpoj8%2BBP7r%2BntiUudIwp0OWr4eVL4%2Fp9QDPq3y6QxjK90a7Q0TWzhdxYL2T2YJsremaRPdtoXV3w70G9YAc6EM30LaAy6SiqbPtX2%2BVXbPBh7JrQJzeQvziM26xt0DsLXSEsZ8z8GmSf5Wp1qlgg4UGTHntlg4X%2BfgS8aOVMMk60l%2FmG6BLNlCOd1s6%2FNQXnGdT7PV5fz8ZFfblBR1C3wLexsX29LatavKkGCTVyvd6mswsSDsN7hseTSugrvHQPE4bOuOK2pW%2BRjAWg5mDdntX0ZrUsvY2lxvSG5QW18kuFF6SawibMzIgdb2t9lgbU6IHYGDZquoU2Jot25Bk86d%2BjS9Tru7QIcXXUNrWYRh%2Fb5AbAW05VI7fq3jXhmlEepqmsCBr8hzlftlipTbE8mY4yyLMvsPvEwJEgU0%2FDjpBnm4hBaieDsymeneSc%2FQ%2FqEMSMI6mzM2UpN465KWf9NogCCLAm9AJ96y1V4UYzI%2FAfXWDel1mOPzLAz3Qq9qnqEqzcJz4AcPdjaYrtNtWYYXwEGXOLK5WUHsk8Tz2cQpfgXC0%2BQPdB3vMtyLeiyIm66wKwCF43HQV%2F9tVCcetLw3R%2BQXJIhdmUNV2bGKzWTzW%2BU2C%2Bh%2BpQ0%2BMNr9k70GOqUBMniwQFbtg9TXrFQdCICBCsQI9j6Z8K6JZ%2B3L3QguyqxHCZF8gAA6g6SIvMCrpg%2Fbtw8anjAeTc8n7%2BW7PK5YI3Sju7ePrIIBRCllGdhtJr5U7Vl31dLe%2BncwA8%2FPodI1ivdb1T3TtvOOwJMuJpUYyk0L44t0EvyIQ3P21NQgheGYmDNzVUhAPUa%2BJ%2BBipem24kfEkjqXnHFii1Q5f7YrsnLT5xo3&X-Amz-Signature=760f023de2ade41bb20bb24567e8850c6d26b0f03e8ca27d3e80d2c45eb63190&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SL3ZTL4I%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T202509Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEsaCXVzLXdlc3QtMiJHMEUCIQCtNMnPslMJVha5CL6uPKFCRvl7J6JHQXDFiRJlu9Mg5gIgWiyKhibnI6UBd6IhBTU7gT3C3q7cCCUOoaatZIFNllYq%2FwMIYxAAGgw2Mzc0MjMxODM4MDUiDP%2BOfb0hu7yEG1XWnyrcA%2F5Xj3jpoj8%2BBP7r%2BntiUudIwp0OWr4eVL4%2Fp9QDPq3y6QxjK90a7Q0TWzhdxYL2T2YJsremaRPdtoXV3w70G9YAc6EM30LaAy6SiqbPtX2%2BVXbPBh7JrQJzeQvziM26xt0DsLXSEsZ8z8GmSf5Wp1qlgg4UGTHntlg4X%2BfgS8aOVMMk60l%2FmG6BLNlCOd1s6%2FNQXnGdT7PV5fz8ZFfblBR1C3wLexsX29LatavKkGCTVyvd6mswsSDsN7hseTSugrvHQPE4bOuOK2pW%2BRjAWg5mDdntX0ZrUsvY2lxvSG5QW18kuFF6SawibMzIgdb2t9lgbU6IHYGDZquoU2Jot25Bk86d%2BjS9Tru7QIcXXUNrWYRh%2Fb5AbAW05VI7fq3jXhmlEepqmsCBr8hzlftlipTbE8mY4yyLMvsPvEwJEgU0%2FDjpBnm4hBaieDsymeneSc%2FQ%2FqEMSMI6mzM2UpN465KWf9NogCCLAm9AJ96y1V4UYzI%2FAfXWDel1mOPzLAz3Qq9qnqEqzcJz4AcPdjaYrtNtWYYXwEGXOLK5WUHsk8Tz2cQpfgXC0%2BQPdB3vMtyLeiyIm66wKwCF43HQV%2F9tVCcetLw3R%2BQXJIhdmUNV2bGKzWTzW%2BU2C%2Bh%2BpQ0%2BMNr9k70GOqUBMniwQFbtg9TXrFQdCICBCsQI9j6Z8K6JZ%2B3L3QguyqxHCZF8gAA6g6SIvMCrpg%2Fbtw8anjAeTc8n7%2BW7PK5YI3Sju7ePrIIBRCllGdhtJr5U7Vl31dLe%2BncwA8%2FPodI1ivdb1T3TtvOOwJMuJpUYyk0L44t0EvyIQ3P21NQgheGYmDNzVUhAPUa%2BJ%2BBipem24kfEkjqXnHFii1Q5f7YrsnLT5xo3&X-Amz-Signature=360a16266d7825f0bb1558b0213289acc121fe99f7bd6be2bad06d59a503a952&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SL3ZTL4I%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T202509Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEsaCXVzLXdlc3QtMiJHMEUCIQCtNMnPslMJVha5CL6uPKFCRvl7J6JHQXDFiRJlu9Mg5gIgWiyKhibnI6UBd6IhBTU7gT3C3q7cCCUOoaatZIFNllYq%2FwMIYxAAGgw2Mzc0MjMxODM4MDUiDP%2BOfb0hu7yEG1XWnyrcA%2F5Xj3jpoj8%2BBP7r%2BntiUudIwp0OWr4eVL4%2Fp9QDPq3y6QxjK90a7Q0TWzhdxYL2T2YJsremaRPdtoXV3w70G9YAc6EM30LaAy6SiqbPtX2%2BVXbPBh7JrQJzeQvziM26xt0DsLXSEsZ8z8GmSf5Wp1qlgg4UGTHntlg4X%2BfgS8aOVMMk60l%2FmG6BLNlCOd1s6%2FNQXnGdT7PV5fz8ZFfblBR1C3wLexsX29LatavKkGCTVyvd6mswsSDsN7hseTSugrvHQPE4bOuOK2pW%2BRjAWg5mDdntX0ZrUsvY2lxvSG5QW18kuFF6SawibMzIgdb2t9lgbU6IHYGDZquoU2Jot25Bk86d%2BjS9Tru7QIcXXUNrWYRh%2Fb5AbAW05VI7fq3jXhmlEepqmsCBr8hzlftlipTbE8mY4yyLMvsPvEwJEgU0%2FDjpBnm4hBaieDsymeneSc%2FQ%2FqEMSMI6mzM2UpN465KWf9NogCCLAm9AJ96y1V4UYzI%2FAfXWDel1mOPzLAz3Qq9qnqEqzcJz4AcPdjaYrtNtWYYXwEGXOLK5WUHsk8Tz2cQpfgXC0%2BQPdB3vMtyLeiyIm66wKwCF43HQV%2F9tVCcetLw3R%2BQXJIhdmUNV2bGKzWTzW%2BU2C%2Bh%2BpQ0%2BMNr9k70GOqUBMniwQFbtg9TXrFQdCICBCsQI9j6Z8K6JZ%2B3L3QguyqxHCZF8gAA6g6SIvMCrpg%2Fbtw8anjAeTc8n7%2BW7PK5YI3Sju7ePrIIBRCllGdhtJr5U7Vl31dLe%2BncwA8%2FPodI1ivdb1T3TtvOOwJMuJpUYyk0L44t0EvyIQ3P21NQgheGYmDNzVUhAPUa%2BJ%2BBipem24kfEkjqXnHFii1Q5f7YrsnLT5xo3&X-Amz-Signature=0abaa8e99bc929d9ab35eb3cbc9a0d98467e6f9532f2ea1aa79caf1a4aed8ee5&X-Amz-SignedHeaders=host&x-id=GetObject)


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

