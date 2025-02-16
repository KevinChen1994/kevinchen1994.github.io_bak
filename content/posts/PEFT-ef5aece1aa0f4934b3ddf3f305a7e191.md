---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466XTM5M5Q6%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250216T191833Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEDoaCXVzLXdlc3QtMiJHMEUCIHtHe1HBitJm4C31La6%2F8tU92VWOuSDjgVwAL5FNODxpAiEAl\
  gvwhtA%2BcexkEak5t%2BHh0s84WxQRPMdsc7iWDNi1j5Uq%2FwMIYxAAGgw2Mzc0MjMxODM4MDUi\
  DE%2FDR536fv1fsfR12CrcAxCfC32sCY9BXVjFiApV%2Fu2mzN0rbgjFSo3YbxKC9P3HdJCtpmfeC\
  YLwfJaBW%2B86jYaUIxAu%2FGgS55XMYgQNxCD2igzBYHvWAYRkdUEZrBo0jUMurlyl37kfo0OA3H\
  NjHXyM7YyjA7y0W2Ip4lnPhyxN0e6H0yh%2BxbrqWM82RJUDIoP4WOQDv%2FY3LNsWWhkHq%2BQCC\
  mVeDMog9pV8Bz1%2Fe41WWpjEimchoJ%2FLIML0e8fKbMQqNzpz%2FKXB1OiDuuCPTIgGX%2BWDCK\
  sC4MXFAuxnhTAha0O%2FdLK%2F8c61KsYvROd6FqGa21yd1708kYJ4YFLVMoHt0kEVA2IH7JiciXP\
  zFL5uZRxH3QS16SGfBT6eKY3R4Se6QmWEnW4s%2FrNlMA%2Bk9flGbxa1ksZWekQzftgSGwoVsXCQ\
  YkPoBLQapx8Uqrcp%2FIyMMPRQp5isTzSdTEgu5CYonQhy%2FFeJimt3F47CgB8mqTWoLCUeHOcxm\
  WRmQzbF2ZTMmjAA3QwIMP2hNtI8e%2BeZ7fJX%2FzY6iWIZLnxtg1xp8eLkflEi0Evr2Fgs2MG%2B\
  ozzI9TOBIrKJmAMMIZYYeItu3uAaigewmEamNdptUW0FcKU%2BzfYHp1Q0MYAbhQH7x0wW%2BHHsP\
  IKPvUhpMKzByL0GOqUBTH7uoQOtw9zd9XVViJdBDyYGG5LlkqiA3QEDzSftbzb3PAtbjydrvZjZUF\
  FcIptGp4EQ7cmLjWczmNoqRjSr3kQh6FYmLf207Ku9ReipF7Lia4LsM6%2BP7Sy189QjHPiq8H8SD\
  zkk5IZZlDlAWNiqtPWubjrlBR8TPXcjOYzmyBZD%2BXt8nAxW8nDabenQit3VMJm64MWVFwotWAon\
  m7hfEsau3k6D&X-Amz-Signature=3909431348fa30f11c2beec6df141e05be4ad251bcc61dac\
  8037522a8b1ae6ff&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466S3AYQVGA%2F20250216%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250216T191657Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEDoaCXVzLXdlc3QtMiJGMEQCIEYKJG4ip6IsolN3vv4dSF7pY6%2BMW\
        cxRaFrI64K9A0KCAiAT67YeDbxME6CBiFalJQ3xYrf1szZAiaP2By8HuEte1Cr%2FAwhjEA\
        AaDDYzNzQyMzE4MzgwNSIMOuGIlZHbNL3zEhwTKtwDXs29bdSioEtsGyfvompCMayDog0tq\
        tkAU89yjxak%2BQw7a10KmjLvc5os%2Fwv0kcnv3BLBFQzNUsHTCxwEs3Ji1gTXVL%2BjXm\
        sL6nmBOZGFq0iAgt%2F78uWEdYPd2nKNVw%2FKNKLdXbChivbm7XFF2VVXAD6pbnN6zL3Bw\
        ADhlokExxppTMnCKx1kNSfGGbeohB%2B6pp6aZZ8A5OqU2zFEz%2Bhj5zaejpn9DJDsT6Jo\
        YbbxRKjaACI2MhHZOuu7OJRvXiYw9jWKDucAqVxOt3eIbUsgRauh8xdeNKtJfsFHtm3WGnL\
        cvJH7aIqlpCJR%2FJ4mR%2B2u0IrSyGw51p%2BNxpDe3xAiIaQcJzn0tcMGhjXF7Y1jOZbF\
        6H6uZZRCocqZY1GA%2F%2BK%2FrZIPOClGEVqWw1LQumbrWGCNy8yaSUm8i7jAi5pLeym36\
        nstM17noBAYtQ8XSC32zvjSpZk2Q7mukp%2B7ouBdFkqnuNMjbaYiMfIjibMIizHk8AfreI\
        KmfooKf5dElRXcR97fO912JIa8Ybwwej%2BFCpxAPGvYkd0k78rPQ%2F8WekHedeycsSm7f\
        OALZUiozKvb6Bqwm8nJdbh%2Fk7X6tZ7w0mcyS70ANw4tOxiZjCQWWEkaiEB5qWBxfZlmVg\
        8w5cDIvQY6pgEv%2BWq7LtUzRnDD%2BEnw%2F2nH1L9m4vYVeHm4MPTg%2Bnc9UiIYuNF1J\
        ELaFdZVXiecutCOawfIu4GCK3TJy%2F8yVIU0RulcJpyJQ0tUnhONcqzQAfqLzysilNNWlT\
        kENtg6Q5Z8krADGHyR6tvqPEn%2B5V3JN8IK%2BNVlqqGRNJF8L9HgzQIN0Y9jWlwVpvmWj\
        hOfvrgdLAqrPiNMxpQfXxwG6hwngcaxHRM3&X-Amz-Signature=d208912fd666aa0838f\
        3cfe4adbd41d5cde678eb77f6a7c3413f5394124766e1&X-Amz-SignedHeaders=host&\
        x-id=GetObject"
      expiry_time: "2025-02-16T20:16:57.070Z"
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
UPDATE_TIME: "2025-02-16T19:18:37.979Z"
EXPIRY_TIME: "2025-02-16T20:18:30.788Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WI7QKDIO%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T191831Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDsaCXVzLXdlc3QtMiJHMEUCIFwa1g5mupgOI%2B0PtO4EsldEAA8Fem1d%2F3F83HW0Ra1FAiEAuE349xmvIOgft7%2BO3cdiD2t8vICMf8uXLPoo5NhbM2wq%2FwMIZBAAGgw2Mzc0MjMxODM4MDUiDKsuEiL21mm8wIW1UircA9x2GA76i3IXxT9FsycfnLdv6nMDEX6t8I%2BX59pQo7n%2Fxb0UK5M3Pl9YTvRTTj6v7HD6CqOJzxRqCLaMva9FPC3tafHWuMogVk5mLem2ITGtn26z7hiH2dP4TyzLud0KDriJPliuUAYzzL0Y79%2FFVe9uJvGfi2juCEedqvDa8ebexuFUVyIt03B8EUq5sVsd5Uw%2BXetj8lGAMt84OQYUAg%2Bg2TwcuaursHpGyt4s2BznM2oMnAtEadgfTnlDCNfKNqvsNMGlpkBVnIxXgqNP5Sa38pltdX8OMlTd4VHKovHWpwt9C5iZaJfhsGM82qcoyW8NuOksxhFGEI5Vqr%2Foc4vFc5U2%2BZsK17DnqU7ubSF7DguM2ENcHfKFz%2F1MPDfRNVaOuasAKhjhoGVqCCEpzlvPX0%2BQVccs%2F4EKQVfVKnf4z5y3u2ZkNv52XWcSk1sr2Dthgfi8xGn9vB%2BBe%2FK0Pwolj6PCqiltsJ2YD%2FfksV4rn7AHvjWi4dN1l9T9USSpIh%2BfjlNgu9x%2FUBXkZL65Tt%2BRuJFH%2F6QFK54HuOsB%2BhHrsKQ6Q92uY6QLXdgviRoUQnqfqzLvR1%2FDOmnmLlhFBH2Yh52c%2Fjh4cb0IY5S97zqjsA8TePTR5QXbpwTiMP%2FfyL0GOqUBre8sLDjFhE7lvNW2IE%2BfJ%2FCTJVBnyZFv4yx5iEmZo3lZtQDSF2HCV5J2LbthbQvJOE4ax%2B6RbeovWfw4548uqmkTyMMZDzAwvPsWiEaFu3MLMxE2oksz%2Fh6bmvhuDUdlsIEsyeKj%2BoRNVvBHQz9em4kIrgmd5pPTVYmnn0%2BPyIaQv1FT22raUtOlYe73T7Bs4OEcnO2MhY6VOFeU1cOQbDY0HVQF&X-Amz-Signature=9eddca9f87155573ecd9ea658c703d50f0719a23002938ffc7d27210f3367633&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WI7QKDIO%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T191831Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDsaCXVzLXdlc3QtMiJHMEUCIFwa1g5mupgOI%2B0PtO4EsldEAA8Fem1d%2F3F83HW0Ra1FAiEAuE349xmvIOgft7%2BO3cdiD2t8vICMf8uXLPoo5NhbM2wq%2FwMIZBAAGgw2Mzc0MjMxODM4MDUiDKsuEiL21mm8wIW1UircA9x2GA76i3IXxT9FsycfnLdv6nMDEX6t8I%2BX59pQo7n%2Fxb0UK5M3Pl9YTvRTTj6v7HD6CqOJzxRqCLaMva9FPC3tafHWuMogVk5mLem2ITGtn26z7hiH2dP4TyzLud0KDriJPliuUAYzzL0Y79%2FFVe9uJvGfi2juCEedqvDa8ebexuFUVyIt03B8EUq5sVsd5Uw%2BXetj8lGAMt84OQYUAg%2Bg2TwcuaursHpGyt4s2BznM2oMnAtEadgfTnlDCNfKNqvsNMGlpkBVnIxXgqNP5Sa38pltdX8OMlTd4VHKovHWpwt9C5iZaJfhsGM82qcoyW8NuOksxhFGEI5Vqr%2Foc4vFc5U2%2BZsK17DnqU7ubSF7DguM2ENcHfKFz%2F1MPDfRNVaOuasAKhjhoGVqCCEpzlvPX0%2BQVccs%2F4EKQVfVKnf4z5y3u2ZkNv52XWcSk1sr2Dthgfi8xGn9vB%2BBe%2FK0Pwolj6PCqiltsJ2YD%2FfksV4rn7AHvjWi4dN1l9T9USSpIh%2BfjlNgu9x%2FUBXkZL65Tt%2BRuJFH%2F6QFK54HuOsB%2BhHrsKQ6Q92uY6QLXdgviRoUQnqfqzLvR1%2FDOmnmLlhFBH2Yh52c%2Fjh4cb0IY5S97zqjsA8TePTR5QXbpwTiMP%2FfyL0GOqUBre8sLDjFhE7lvNW2IE%2BfJ%2FCTJVBnyZFv4yx5iEmZo3lZtQDSF2HCV5J2LbthbQvJOE4ax%2B6RbeovWfw4548uqmkTyMMZDzAwvPsWiEaFu3MLMxE2oksz%2Fh6bmvhuDUdlsIEsyeKj%2BoRNVvBHQz9em4kIrgmd5pPTVYmnn0%2BPyIaQv1FT22raUtOlYe73T7Bs4OEcnO2MhY6VOFeU1cOQbDY0HVQF&X-Amz-Signature=ea8ec0154c75f18268d66d779338a21804d442e35d2ae88129d891a3102604a1&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WI7QKDIO%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T191831Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDsaCXVzLXdlc3QtMiJHMEUCIFwa1g5mupgOI%2B0PtO4EsldEAA8Fem1d%2F3F83HW0Ra1FAiEAuE349xmvIOgft7%2BO3cdiD2t8vICMf8uXLPoo5NhbM2wq%2FwMIZBAAGgw2Mzc0MjMxODM4MDUiDKsuEiL21mm8wIW1UircA9x2GA76i3IXxT9FsycfnLdv6nMDEX6t8I%2BX59pQo7n%2Fxb0UK5M3Pl9YTvRTTj6v7HD6CqOJzxRqCLaMva9FPC3tafHWuMogVk5mLem2ITGtn26z7hiH2dP4TyzLud0KDriJPliuUAYzzL0Y79%2FFVe9uJvGfi2juCEedqvDa8ebexuFUVyIt03B8EUq5sVsd5Uw%2BXetj8lGAMt84OQYUAg%2Bg2TwcuaursHpGyt4s2BznM2oMnAtEadgfTnlDCNfKNqvsNMGlpkBVnIxXgqNP5Sa38pltdX8OMlTd4VHKovHWpwt9C5iZaJfhsGM82qcoyW8NuOksxhFGEI5Vqr%2Foc4vFc5U2%2BZsK17DnqU7ubSF7DguM2ENcHfKFz%2F1MPDfRNVaOuasAKhjhoGVqCCEpzlvPX0%2BQVccs%2F4EKQVfVKnf4z5y3u2ZkNv52XWcSk1sr2Dthgfi8xGn9vB%2BBe%2FK0Pwolj6PCqiltsJ2YD%2FfksV4rn7AHvjWi4dN1l9T9USSpIh%2BfjlNgu9x%2FUBXkZL65Tt%2BRuJFH%2F6QFK54HuOsB%2BhHrsKQ6Q92uY6QLXdgviRoUQnqfqzLvR1%2FDOmnmLlhFBH2Yh52c%2Fjh4cb0IY5S97zqjsA8TePTR5QXbpwTiMP%2FfyL0GOqUBre8sLDjFhE7lvNW2IE%2BfJ%2FCTJVBnyZFv4yx5iEmZo3lZtQDSF2HCV5J2LbthbQvJOE4ax%2B6RbeovWfw4548uqmkTyMMZDzAwvPsWiEaFu3MLMxE2oksz%2Fh6bmvhuDUdlsIEsyeKj%2BoRNVvBHQz9em4kIrgmd5pPTVYmnn0%2BPyIaQv1FT22raUtOlYe73T7Bs4OEcnO2MhY6VOFeU1cOQbDY0HVQF&X-Amz-Signature=ec6d3cf1d3b63ee064f203254b0d4063d3ac609c255fcb01df28efe8d0a013ae&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WI7QKDIO%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T191831Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDsaCXVzLXdlc3QtMiJHMEUCIFwa1g5mupgOI%2B0PtO4EsldEAA8Fem1d%2F3F83HW0Ra1FAiEAuE349xmvIOgft7%2BO3cdiD2t8vICMf8uXLPoo5NhbM2wq%2FwMIZBAAGgw2Mzc0MjMxODM4MDUiDKsuEiL21mm8wIW1UircA9x2GA76i3IXxT9FsycfnLdv6nMDEX6t8I%2BX59pQo7n%2Fxb0UK5M3Pl9YTvRTTj6v7HD6CqOJzxRqCLaMva9FPC3tafHWuMogVk5mLem2ITGtn26z7hiH2dP4TyzLud0KDriJPliuUAYzzL0Y79%2FFVe9uJvGfi2juCEedqvDa8ebexuFUVyIt03B8EUq5sVsd5Uw%2BXetj8lGAMt84OQYUAg%2Bg2TwcuaursHpGyt4s2BznM2oMnAtEadgfTnlDCNfKNqvsNMGlpkBVnIxXgqNP5Sa38pltdX8OMlTd4VHKovHWpwt9C5iZaJfhsGM82qcoyW8NuOksxhFGEI5Vqr%2Foc4vFc5U2%2BZsK17DnqU7ubSF7DguM2ENcHfKFz%2F1MPDfRNVaOuasAKhjhoGVqCCEpzlvPX0%2BQVccs%2F4EKQVfVKnf4z5y3u2ZkNv52XWcSk1sr2Dthgfi8xGn9vB%2BBe%2FK0Pwolj6PCqiltsJ2YD%2FfksV4rn7AHvjWi4dN1l9T9USSpIh%2BfjlNgu9x%2FUBXkZL65Tt%2BRuJFH%2F6QFK54HuOsB%2BhHrsKQ6Q92uY6QLXdgviRoUQnqfqzLvR1%2FDOmnmLlhFBH2Yh52c%2Fjh4cb0IY5S97zqjsA8TePTR5QXbpwTiMP%2FfyL0GOqUBre8sLDjFhE7lvNW2IE%2BfJ%2FCTJVBnyZFv4yx5iEmZo3lZtQDSF2HCV5J2LbthbQvJOE4ax%2B6RbeovWfw4548uqmkTyMMZDzAwvPsWiEaFu3MLMxE2oksz%2Fh6bmvhuDUdlsIEsyeKj%2BoRNVvBHQz9em4kIrgmd5pPTVYmnn0%2BPyIaQv1FT22raUtOlYe73T7Bs4OEcnO2MhY6VOFeU1cOQbDY0HVQF&X-Amz-Signature=a3bc415d2b7b95cc324527c339cb5e7e798974d43f429be945ac8fba4c388a17&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WI7QKDIO%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T191831Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDsaCXVzLXdlc3QtMiJHMEUCIFwa1g5mupgOI%2B0PtO4EsldEAA8Fem1d%2F3F83HW0Ra1FAiEAuE349xmvIOgft7%2BO3cdiD2t8vICMf8uXLPoo5NhbM2wq%2FwMIZBAAGgw2Mzc0MjMxODM4MDUiDKsuEiL21mm8wIW1UircA9x2GA76i3IXxT9FsycfnLdv6nMDEX6t8I%2BX59pQo7n%2Fxb0UK5M3Pl9YTvRTTj6v7HD6CqOJzxRqCLaMva9FPC3tafHWuMogVk5mLem2ITGtn26z7hiH2dP4TyzLud0KDriJPliuUAYzzL0Y79%2FFVe9uJvGfi2juCEedqvDa8ebexuFUVyIt03B8EUq5sVsd5Uw%2BXetj8lGAMt84OQYUAg%2Bg2TwcuaursHpGyt4s2BznM2oMnAtEadgfTnlDCNfKNqvsNMGlpkBVnIxXgqNP5Sa38pltdX8OMlTd4VHKovHWpwt9C5iZaJfhsGM82qcoyW8NuOksxhFGEI5Vqr%2Foc4vFc5U2%2BZsK17DnqU7ubSF7DguM2ENcHfKFz%2F1MPDfRNVaOuasAKhjhoGVqCCEpzlvPX0%2BQVccs%2F4EKQVfVKnf4z5y3u2ZkNv52XWcSk1sr2Dthgfi8xGn9vB%2BBe%2FK0Pwolj6PCqiltsJ2YD%2FfksV4rn7AHvjWi4dN1l9T9USSpIh%2BfjlNgu9x%2FUBXkZL65Tt%2BRuJFH%2F6QFK54HuOsB%2BhHrsKQ6Q92uY6QLXdgviRoUQnqfqzLvR1%2FDOmnmLlhFBH2Yh52c%2Fjh4cb0IY5S97zqjsA8TePTR5QXbpwTiMP%2FfyL0GOqUBre8sLDjFhE7lvNW2IE%2BfJ%2FCTJVBnyZFv4yx5iEmZo3lZtQDSF2HCV5J2LbthbQvJOE4ax%2B6RbeovWfw4548uqmkTyMMZDzAwvPsWiEaFu3MLMxE2oksz%2Fh6bmvhuDUdlsIEsyeKj%2BoRNVvBHQz9em4kIrgmd5pPTVYmnn0%2BPyIaQv1FT22raUtOlYe73T7Bs4OEcnO2MhY6VOFeU1cOQbDY0HVQF&X-Amz-Signature=5b6a2454b5277ddd15029a68edc65b46cbab2cedfe0c502c242c5b005e69017c&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SWVFETTL%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T191832Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDoaCXVzLXdlc3QtMiJHMEUCICcmBGI1VmcXv2tsWRU0R5SSa%2BKmqdWZhmOs9c3qPbxKAiEAl1%2FnfAH3HhlNksOkAosRIelCWtBdA0cul%2BMA3%2BQSMOQq%2FwMIYxAAGgw2Mzc0MjMxODM4MDUiDH1uXgnT1TY7%2BirZjCrcA%2B6IUlV0jK0SHqwaa88YmNGjFFQqJvN2773GovKOO1XXY7xkzVY35BcsSseVAhAiLv7fPTsyoreOa2v8oNquZYjDaQIiXfIIiP%2BvqdBMBTccQJt6klppKu32VoR2qYYIk8djQMdeqsiFmOsuajoZgbjxwZTHGZDDn3Xra8%2FwQ8k3kU1PkRL3H6lrKSm9xswQCPvK5mtl%2Brlx3gKk%2FrKtOjFu931cBGuo9tI9hPNRyZ5oc2pYkqjmJz4kv6a8RSpNU5Kth3NY6ENOltDncGGVLgK8eCxH%2FGDVdh0zKwAHM3FO%2B8Y4vhCrWVkInlCJ8D1AbGgMhFjrp1ldPz9SPWGWvPPHOTuPnSo%2F6egMdh4zeeCgnugAiAGiMl%2BsyWmmfpoExvZFajrM65h7klLRZCzGKLD4wgfzF%2B9w%2BHiKRm2Kvh8ejCqTlENDCNYHnVVolerMGVsoIgJC0hst%2BJq1ctOTboAFUgBe1Ml6wv3yMPANneqYNG0LxGN94cB3nZPAtL0GKONxEfCwYrrapdAtf0UnY%2FC4G7ImrAVDqtmo9pgzan3LQAlbkhIds1LJ05Vvv8xJxLYPvSy%2BND9QXRPokyADSg6vt1xnkmIaxe%2Bp1TRsvAUXFfPcAeVgJidcwJTMMM7ByL0GOqUBQbvzmOrgqe2LXQVZbt%2F6k%2FCkQj5zDgwvBHiwdETqWqj6S6ULE4ySikjSmxYDq72j1gzaK8JhheA2Gzoz%2BGJP6cVU5G%2FwfcOwhLR4p%2FFl2%2Bm4CF3H5mIOhB04zP3aLS1De5B1rIjp3t66XKCV7ozoXJd4kyq49a%2BeR0lP3vf7sQqGLISB3olZVejBTNx%2B1HVK%2BKyeMV9Oy3ezdjhapUIrP8m%2FHuGt&X-Amz-Signature=973f15dd55346c4c0190bcc3c3f2205d5233e95c6cffa0d5cdb7fcba40aabc50&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667PBZXJ2Y%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T191833Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDoaCXVzLXdlc3QtMiJIMEYCIQCAsu3TyqvG%2BYc6V%2F1H9hzd2XHX%2FerQvnm49G%2Fla6%2BV1wIhAPJ%2FL3Zh%2FA9Sk8ieSslWTenE2vvpdXx4DkxsqOlBD0VgKv8DCGMQABoMNjM3NDIzMTgzODA1IgxXa77Gz5UklyfxLpsq3APyYRAmPXeWpP8tudO6geFDvwXp%2BnevEyZoa6Q%2BO6BhxbBF%2BTjDBq%2FRXSjynEx3dn9opWB8P43cpS7VGZ%2B2tI7kEqacBZAnREZMCzUUDie6n6iu2RrDURyPCnvWYKqY9QGg0lm37YxDlriYtehKQiF2%2Fy0fHXyubYPiUZl%2Ff%2FaumChfD2EuwUbS593NmQ60QiFICb43xmmX6cjy4NBKDCGOs1Gm%2BKWwCTMGonh6KVvLVDCuEzm498fVfNmQyrKuWIP0GIEZRuxGQJ3uFr5wnRx40yYEHHuOPpn96GGCBPe5VVw2h%2B3%2BBzhgPWoE6I6XdlbPOZceVyLCjlrLm3i%2BcBGnfWFI0rEaNCBMIl6A6nap0o0vqbL46PfluLKlgKZwnMK8v8SZ8nRZYoRY695dyvyAdRETxDcZpAT62te3Ay%2FsDJVo6aEgLHtxeVpg5569AUtd%2BtFYidOO%2BlsOSBJ00GFpIG5H2J57r3JqfIKTKpfooKYWDWB9ySSvH69h4XqgbYcnWAEoH68HRP6iB5vuIa%2F0A5WYSK1wtwIzsWIBjkr5wV%2BdYjcAen5DTuvthjE3x4Jztll%2BuzN7RVrcQ9gzmeLxeG9O5izt0QeS7tImtQBrMS7FjLPpKkGJxFroszCtwci9BjqkAVgcRNVLe4r2uTOf1TCvQPD0y9BHrVFMRmsu9b1%2FDq9mJJHS%2F8Vl2zsu0pFSwzxorx3839%2BbgHzM7Sh6XVQHdex6%2FU3%2BtbkC0qJ09%2Ba0OD59IzCgyKY5WU4y50u%2FPsYGHV9O%2B6rYp0%2B%2BpAK39WRe7z3EHFfkFqGmdIz4C1MERx7JgJrubKHLLZBHnk7aW2Bl9BPSs7uRerfa6CylGTTzoEqrVga3&X-Amz-Signature=2bbddb3e06343148b3959945b2b210b7a43639004e31cd872dbdb8890e4e916b&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WI7QKDIO%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T191831Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDsaCXVzLXdlc3QtMiJHMEUCIFwa1g5mupgOI%2B0PtO4EsldEAA8Fem1d%2F3F83HW0Ra1FAiEAuE349xmvIOgft7%2BO3cdiD2t8vICMf8uXLPoo5NhbM2wq%2FwMIZBAAGgw2Mzc0MjMxODM4MDUiDKsuEiL21mm8wIW1UircA9x2GA76i3IXxT9FsycfnLdv6nMDEX6t8I%2BX59pQo7n%2Fxb0UK5M3Pl9YTvRTTj6v7HD6CqOJzxRqCLaMva9FPC3tafHWuMogVk5mLem2ITGtn26z7hiH2dP4TyzLud0KDriJPliuUAYzzL0Y79%2FFVe9uJvGfi2juCEedqvDa8ebexuFUVyIt03B8EUq5sVsd5Uw%2BXetj8lGAMt84OQYUAg%2Bg2TwcuaursHpGyt4s2BznM2oMnAtEadgfTnlDCNfKNqvsNMGlpkBVnIxXgqNP5Sa38pltdX8OMlTd4VHKovHWpwt9C5iZaJfhsGM82qcoyW8NuOksxhFGEI5Vqr%2Foc4vFc5U2%2BZsK17DnqU7ubSF7DguM2ENcHfKFz%2F1MPDfRNVaOuasAKhjhoGVqCCEpzlvPX0%2BQVccs%2F4EKQVfVKnf4z5y3u2ZkNv52XWcSk1sr2Dthgfi8xGn9vB%2BBe%2FK0Pwolj6PCqiltsJ2YD%2FfksV4rn7AHvjWi4dN1l9T9USSpIh%2BfjlNgu9x%2FUBXkZL65Tt%2BRuJFH%2F6QFK54HuOsB%2BhHrsKQ6Q92uY6QLXdgviRoUQnqfqzLvR1%2FDOmnmLlhFBH2Yh52c%2Fjh4cb0IY5S97zqjsA8TePTR5QXbpwTiMP%2FfyL0GOqUBre8sLDjFhE7lvNW2IE%2BfJ%2FCTJVBnyZFv4yx5iEmZo3lZtQDSF2HCV5J2LbthbQvJOE4ax%2B6RbeovWfw4548uqmkTyMMZDzAwvPsWiEaFu3MLMxE2oksz%2Fh6bmvhuDUdlsIEsyeKj%2BoRNVvBHQz9em4kIrgmd5pPTVYmnn0%2BPyIaQv1FT22raUtOlYe73T7Bs4OEcnO2MhY6VOFeU1cOQbDY0HVQF&X-Amz-Signature=7e307bb936dd79bb68162f793c7c0985918323c5753ce50670adc7cdd0ce6bf3&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WI7QKDIO%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T191831Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDsaCXVzLXdlc3QtMiJHMEUCIFwa1g5mupgOI%2B0PtO4EsldEAA8Fem1d%2F3F83HW0Ra1FAiEAuE349xmvIOgft7%2BO3cdiD2t8vICMf8uXLPoo5NhbM2wq%2FwMIZBAAGgw2Mzc0MjMxODM4MDUiDKsuEiL21mm8wIW1UircA9x2GA76i3IXxT9FsycfnLdv6nMDEX6t8I%2BX59pQo7n%2Fxb0UK5M3Pl9YTvRTTj6v7HD6CqOJzxRqCLaMva9FPC3tafHWuMogVk5mLem2ITGtn26z7hiH2dP4TyzLud0KDriJPliuUAYzzL0Y79%2FFVe9uJvGfi2juCEedqvDa8ebexuFUVyIt03B8EUq5sVsd5Uw%2BXetj8lGAMt84OQYUAg%2Bg2TwcuaursHpGyt4s2BznM2oMnAtEadgfTnlDCNfKNqvsNMGlpkBVnIxXgqNP5Sa38pltdX8OMlTd4VHKovHWpwt9C5iZaJfhsGM82qcoyW8NuOksxhFGEI5Vqr%2Foc4vFc5U2%2BZsK17DnqU7ubSF7DguM2ENcHfKFz%2F1MPDfRNVaOuasAKhjhoGVqCCEpzlvPX0%2BQVccs%2F4EKQVfVKnf4z5y3u2ZkNv52XWcSk1sr2Dthgfi8xGn9vB%2BBe%2FK0Pwolj6PCqiltsJ2YD%2FfksV4rn7AHvjWi4dN1l9T9USSpIh%2BfjlNgu9x%2FUBXkZL65Tt%2BRuJFH%2F6QFK54HuOsB%2BhHrsKQ6Q92uY6QLXdgviRoUQnqfqzLvR1%2FDOmnmLlhFBH2Yh52c%2Fjh4cb0IY5S97zqjsA8TePTR5QXbpwTiMP%2FfyL0GOqUBre8sLDjFhE7lvNW2IE%2BfJ%2FCTJVBnyZFv4yx5iEmZo3lZtQDSF2HCV5J2LbthbQvJOE4ax%2B6RbeovWfw4548uqmkTyMMZDzAwvPsWiEaFu3MLMxE2oksz%2Fh6bmvhuDUdlsIEsyeKj%2BoRNVvBHQz9em4kIrgmd5pPTVYmnn0%2BPyIaQv1FT22raUtOlYe73T7Bs4OEcnO2MhY6VOFeU1cOQbDY0HVQF&X-Amz-Signature=0338d59b2ffa520cc4d19fc0beac2d38272edda25659df10e458165ba465a04d&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WI7QKDIO%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T191831Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDsaCXVzLXdlc3QtMiJHMEUCIFwa1g5mupgOI%2B0PtO4EsldEAA8Fem1d%2F3F83HW0Ra1FAiEAuE349xmvIOgft7%2BO3cdiD2t8vICMf8uXLPoo5NhbM2wq%2FwMIZBAAGgw2Mzc0MjMxODM4MDUiDKsuEiL21mm8wIW1UircA9x2GA76i3IXxT9FsycfnLdv6nMDEX6t8I%2BX59pQo7n%2Fxb0UK5M3Pl9YTvRTTj6v7HD6CqOJzxRqCLaMva9FPC3tafHWuMogVk5mLem2ITGtn26z7hiH2dP4TyzLud0KDriJPliuUAYzzL0Y79%2FFVe9uJvGfi2juCEedqvDa8ebexuFUVyIt03B8EUq5sVsd5Uw%2BXetj8lGAMt84OQYUAg%2Bg2TwcuaursHpGyt4s2BznM2oMnAtEadgfTnlDCNfKNqvsNMGlpkBVnIxXgqNP5Sa38pltdX8OMlTd4VHKovHWpwt9C5iZaJfhsGM82qcoyW8NuOksxhFGEI5Vqr%2Foc4vFc5U2%2BZsK17DnqU7ubSF7DguM2ENcHfKFz%2F1MPDfRNVaOuasAKhjhoGVqCCEpzlvPX0%2BQVccs%2F4EKQVfVKnf4z5y3u2ZkNv52XWcSk1sr2Dthgfi8xGn9vB%2BBe%2FK0Pwolj6PCqiltsJ2YD%2FfksV4rn7AHvjWi4dN1l9T9USSpIh%2BfjlNgu9x%2FUBXkZL65Tt%2BRuJFH%2F6QFK54HuOsB%2BhHrsKQ6Q92uY6QLXdgviRoUQnqfqzLvR1%2FDOmnmLlhFBH2Yh52c%2Fjh4cb0IY5S97zqjsA8TePTR5QXbpwTiMP%2FfyL0GOqUBre8sLDjFhE7lvNW2IE%2BfJ%2FCTJVBnyZFv4yx5iEmZo3lZtQDSF2HCV5J2LbthbQvJOE4ax%2B6RbeovWfw4548uqmkTyMMZDzAwvPsWiEaFu3MLMxE2oksz%2Fh6bmvhuDUdlsIEsyeKj%2BoRNVvBHQz9em4kIrgmd5pPTVYmnn0%2BPyIaQv1FT22raUtOlYe73T7Bs4OEcnO2MhY6VOFeU1cOQbDY0HVQF&X-Amz-Signature=b049671f76fe88203358a16f50c6b34a1f3d36471f6cb1351e01aa3176738169&X-Amz-SignedHeaders=host&x-id=GetObject)


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

