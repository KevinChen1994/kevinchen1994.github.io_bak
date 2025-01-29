---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466QHDAG5IJ%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250129T032524Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEHwaCXVzLXdlc3QtMiJGMEQCIDfKO8e%2BFECTZQBAiPdMRbq7nTBjIZ8xd%2BRw%2FKryqPkHA\
  iB4nd4dPjUwPNlESeKcxmkqd1RPvJ%2BJsB9LByAixP3wHSqIBAiE%2F%2F%2F%2F%2F%2F%2F%2F\
  %2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMLBrLPzk%2FcdmghFp1KtwDy1ddyFzBsRbL%2B4YM9sUYK\
  CLJrkSIIpud7z0%2Bn%2FHUT4NWJAdJ7%2BAmHYjCie8oVa8H1tMnvxjiN%2B7q3lfquv%2B2Yh7g\
  au94wMUmT%2BAlF%2F%2FOmhhJ2EB1A2SD9ZxK3%2FLeQ%2FHvKmJOKQc8FUH6XMBZ%2F3oJQZsD5\
  gkp4ResbzftlaT3F7iV%2BmD0uu0q3QDosLa%2FvVElX4%2FSbBgOTDmggCcDvBEl%2BeInKSKfRN\
  xRTPvgZx5OuwElyqR0JUOYwbSfmZnKYij%2B%2FI3r7yPminpQA8KfIKy1Mn1diY6ipF3dCzWylkA\
  t3sE9mAw16U6FCXjNYEkGGQAFYXNaMnUwqljW7l9A6MfcZDW3JgZ48q66X8zaOGDLASLOWJvrerAH\
  sYd8rDfZZZqNgS6EUXtXgWk5bymcw0BhYOc%2FmlYKe5S9J6WR8SjLmKC6bIRbtoHu897U3UtPeNg\
  eHbqDVEoj9IGqh%2FZorxFw7EvzQYOAQLCMMhnU0%2FH%2FZ%2FRelim%2BDBVWBgwiP3oJf585qx\
  YZDAfaUxvYtZ8n21BJr5rchzdxSafWFBWOXwpaIys2jGiekiEoaOlb17SmSLjcp1JX2pBgSfZFo3l\
  qTsV7B1bL4PIgsONHBbDGNetI7Bz48DDm0kMogh7MRJIwjbzmvAY6pgHGQ0m0uoGk9VqXJiO6byEa\
  %2FThgCih%2FwC%2BGGPEe71zDFnFimcuOOEMGOpuhq%2B6yWygbK9cCtmNqiJ5DoPxJvcShTTQrz\
  shnFa%2BKCOhI8JjWbuZ7BVAHcsUFbMfK8liwoumAvON4%2F0%2F3%2FMeiLwLObNACYaW3UQJwkA\
  LZzELvl%2B%2F%2FBWtmolrTFHUMuekla%2FGfw9JxR7epVrv9l75KPfVkj5vZ0IXHfOOm&X-Amz-\
  Signature=61fde248a7822c6082d4fa59f120d0dd617f567625977e7c7dc20205d328addf&X-\
  Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466SAJL3RD4%2F20250129%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250129T032354Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJIMEYCIQDFLRzdbx%2FzeqWf46L4siGSCOuZT\
        eyCkexILbwzeNWrKgIhAPIuzGX6OozToaKGnkLE5DxYqUcsh%2FRdM9lAEvVDggNPKogECI\
        T%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igza4m3QOzoxkxcHQ\
        Ewq3AObF%2F%2BrXGzIgBCNocqjFM4KWJ7EGwGY6oWjPUnqOqafVk46cPHa6eKjqDr7U7o4\
        fC5fudabNdTcYg1RfvudB9ZZxRz7LTozwRFVu1aV50CeU8iX%2B%2BOqpvkd4dhBhx0ELQ1\
        as2f%2BShPMZnkpnR1vqFxGlP67krGKEUGf4qfeNwbeN%2F8eHESFQ5emYNhiegAQTszd8F\
        z%2B8L2Kze4dO5nvb33LUN6cPEHNqtiUdo2tBIGBBppYdGh7LuBKZ4oT2DTaepKJ%2BVl2M\
        vbnCmBNFqmZaHaG%2BFHJbkTooojXqpSiqrU7iY%2B1P18LmNeLyqpdnm%2FKLJQnxvKt5F\
        sQkk%2BW4xNSbQZdxbE2OIs%2BnGtdzZWt17oLX9BZVPmvufPWpUO9wa%2F9YcnL070eW1b\
        3BJAq3JyaItEQDtbp5KRVZ7FSrdXk3xKgKF8J5179K7jpPWzjnZenFBDgup7iQ%2FGp2dda\
        exnu5aMgrp8c6MXWveECTjgfzTYC6pJkY1EYtTTWbGhv082qdlwSvEXnbAsL2YN%2F6lhRe\
        DeA0lk7j0bG3AHMoLvKQYg49GNax19NpHOVz%2F6cJb70PcQBMRsG%2FTDDpKpgIjL%2F2Y\
        0yo7A57ws7bXcCrJcSkzTwadXTg%2FSf%2FLNY6tw2cDDbu%2Ba8BjqkAVE7CPCNeJNgh1k\
        %2BXnYfaKorL0D%2FBT2se%2BWVt6%2FGSMX8PgkJBxjpaiQ4k7rx6dgRoHMWy5Khi3JpDX\
        JEk96ppLGCGNUc%2BMZPgPmPjpETeoYBkD%2FznLczRyISQlxDiaQil4OZni2zk9e0uFfdu\
        5YPJwR3BxysWQgtC2A8xXIjQIbEznr%2FqJnKilzkeuMejTVhZ%2FxEr34hSRoNhGd7pnxX\
        JJIh4xtA&X-Amz-Signature=98357953c8a575ab66694b3c35fdccb3ea61e762347c1e\
        11dc90134692c39d5b&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-01-29T04:23:54.856Z"
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
UPDATE_TIME: "2025-01-29T03:25:31.748Z"
EXPIRY_TIME: "2025-01-29T04:25:20.208Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TNMNZJAE%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T032520Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHwaCXVzLXdlc3QtMiJHMEUCIQDGpLk9lDaVoxdqCHDb6d7LQn%2FW0ELhcUKtsmwAPjibmgIgcT4nE0ERnzXSGAfumQhlRCwH%2FG228K%2FWX2wzWWK4h44qiAQIhP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCDh%2B%2BBte96UyM2lzCrcAz1QetlXL4On9765vAcbyx7TJUkpy5MSE7CYbxaDmv%2BXQxfBswoLXY9doqEjNYOnKk4XWEZ4WkYWIAf3Y91IA5aYl5ssGSrtMnhOzdA%2FCkcJcwBx%2F7zPw512ZPDT4RTRtKVf%2FTkm6tNGb46yDoxyg7sE10q4qYgdzkiyB30roQ0mrjzRcLTKakJjdpX4lwXlNh4586XXFl72okFnyEQqlu9Ss8eQ3zYHXfH3Xz3v7Sv6ugIa03g5D4zo%2B26bWKSFvLqH9UMG%2BjL%2BT%2FSMYpBGVwWEBEab4wuVWua1gJG0IElU9LAODAxg%2F1FTLJ6IaTE8fPv63iCO%2BP4L%2FnVAT6WvG%2BFv%2B803nJ4sJ0o8cTTxwefRz3iBDbqke6KUQeOqX9MDDkgSzpN3u2OPb2l81JEK2SK9I6aWfv6mYie6iDF1HjhDK8WMO%2Bzn1KCylrx%2FKXv%2FiO0a%2B5DY1UBorgk3zmoiZAJ9aZlvkOG7E424SCNlI1XqQEtfoe0A20aX1j1%2BDX7c%2BTn9dMV6chyTqjvxUZdvfHHct3uLeb98ig1lRjwoXUMVX7MwUhgyWwRdP6UOWp3Lj8ryD0psGZvoCrcFs8XjiRZSHvuRbcwhuLPXP5aSIzuaCsQ971%2Fz5ffZH7bSMOS75rwGOqUBWH7ccLI9Ht0YRgCw5wCTJB3n39u1g2r0KHuNkTFGTL%2FEjRoVjBaPorXaH3tkdTdEfgfeN5FFq%2FS4QukNs1IbP68ygk9qNicPse85rz9s2HK2jZdV%2FX%2BPl6us8ez9DnpibQgKs6H3j7rxUej%2BLhC5H%2B2mBTqrOOla5mcYULcwdr03AoJCYAmFSUBghPi9tKqGQ0YCLCsBIV8M2MGyHSNv2lN55knq&X-Amz-Signature=74034ca8402a42c064765e0c7bed2728a06171fb6ee1a82649018a0087b05525&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TNMNZJAE%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T032520Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHwaCXVzLXdlc3QtMiJHMEUCIQDGpLk9lDaVoxdqCHDb6d7LQn%2FW0ELhcUKtsmwAPjibmgIgcT4nE0ERnzXSGAfumQhlRCwH%2FG228K%2FWX2wzWWK4h44qiAQIhP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCDh%2B%2BBte96UyM2lzCrcAz1QetlXL4On9765vAcbyx7TJUkpy5MSE7CYbxaDmv%2BXQxfBswoLXY9doqEjNYOnKk4XWEZ4WkYWIAf3Y91IA5aYl5ssGSrtMnhOzdA%2FCkcJcwBx%2F7zPw512ZPDT4RTRtKVf%2FTkm6tNGb46yDoxyg7sE10q4qYgdzkiyB30roQ0mrjzRcLTKakJjdpX4lwXlNh4586XXFl72okFnyEQqlu9Ss8eQ3zYHXfH3Xz3v7Sv6ugIa03g5D4zo%2B26bWKSFvLqH9UMG%2BjL%2BT%2FSMYpBGVwWEBEab4wuVWua1gJG0IElU9LAODAxg%2F1FTLJ6IaTE8fPv63iCO%2BP4L%2FnVAT6WvG%2BFv%2B803nJ4sJ0o8cTTxwefRz3iBDbqke6KUQeOqX9MDDkgSzpN3u2OPb2l81JEK2SK9I6aWfv6mYie6iDF1HjhDK8WMO%2Bzn1KCylrx%2FKXv%2FiO0a%2B5DY1UBorgk3zmoiZAJ9aZlvkOG7E424SCNlI1XqQEtfoe0A20aX1j1%2BDX7c%2BTn9dMV6chyTqjvxUZdvfHHct3uLeb98ig1lRjwoXUMVX7MwUhgyWwRdP6UOWp3Lj8ryD0psGZvoCrcFs8XjiRZSHvuRbcwhuLPXP5aSIzuaCsQ971%2Fz5ffZH7bSMOS75rwGOqUBWH7ccLI9Ht0YRgCw5wCTJB3n39u1g2r0KHuNkTFGTL%2FEjRoVjBaPorXaH3tkdTdEfgfeN5FFq%2FS4QukNs1IbP68ygk9qNicPse85rz9s2HK2jZdV%2FX%2BPl6us8ez9DnpibQgKs6H3j7rxUej%2BLhC5H%2B2mBTqrOOla5mcYULcwdr03AoJCYAmFSUBghPi9tKqGQ0YCLCsBIV8M2MGyHSNv2lN55knq&X-Amz-Signature=204bb9cdab210a5dc446b67e919044c3d676bd268fd09230c0d077bcaabf1921&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TNMNZJAE%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T032520Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHwaCXVzLXdlc3QtMiJHMEUCIQDGpLk9lDaVoxdqCHDb6d7LQn%2FW0ELhcUKtsmwAPjibmgIgcT4nE0ERnzXSGAfumQhlRCwH%2FG228K%2FWX2wzWWK4h44qiAQIhP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCDh%2B%2BBte96UyM2lzCrcAz1QetlXL4On9765vAcbyx7TJUkpy5MSE7CYbxaDmv%2BXQxfBswoLXY9doqEjNYOnKk4XWEZ4WkYWIAf3Y91IA5aYl5ssGSrtMnhOzdA%2FCkcJcwBx%2F7zPw512ZPDT4RTRtKVf%2FTkm6tNGb46yDoxyg7sE10q4qYgdzkiyB30roQ0mrjzRcLTKakJjdpX4lwXlNh4586XXFl72okFnyEQqlu9Ss8eQ3zYHXfH3Xz3v7Sv6ugIa03g5D4zo%2B26bWKSFvLqH9UMG%2BjL%2BT%2FSMYpBGVwWEBEab4wuVWua1gJG0IElU9LAODAxg%2F1FTLJ6IaTE8fPv63iCO%2BP4L%2FnVAT6WvG%2BFv%2B803nJ4sJ0o8cTTxwefRz3iBDbqke6KUQeOqX9MDDkgSzpN3u2OPb2l81JEK2SK9I6aWfv6mYie6iDF1HjhDK8WMO%2Bzn1KCylrx%2FKXv%2FiO0a%2B5DY1UBorgk3zmoiZAJ9aZlvkOG7E424SCNlI1XqQEtfoe0A20aX1j1%2BDX7c%2BTn9dMV6chyTqjvxUZdvfHHct3uLeb98ig1lRjwoXUMVX7MwUhgyWwRdP6UOWp3Lj8ryD0psGZvoCrcFs8XjiRZSHvuRbcwhuLPXP5aSIzuaCsQ971%2Fz5ffZH7bSMOS75rwGOqUBWH7ccLI9Ht0YRgCw5wCTJB3n39u1g2r0KHuNkTFGTL%2FEjRoVjBaPorXaH3tkdTdEfgfeN5FFq%2FS4QukNs1IbP68ygk9qNicPse85rz9s2HK2jZdV%2FX%2BPl6us8ez9DnpibQgKs6H3j7rxUej%2BLhC5H%2B2mBTqrOOla5mcYULcwdr03AoJCYAmFSUBghPi9tKqGQ0YCLCsBIV8M2MGyHSNv2lN55knq&X-Amz-Signature=9dc7a170d701571ce578d9a2447e22d7216b6f15659883389b5a4d07ff9e6960&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TNMNZJAE%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T032520Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHwaCXVzLXdlc3QtMiJHMEUCIQDGpLk9lDaVoxdqCHDb6d7LQn%2FW0ELhcUKtsmwAPjibmgIgcT4nE0ERnzXSGAfumQhlRCwH%2FG228K%2FWX2wzWWK4h44qiAQIhP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCDh%2B%2BBte96UyM2lzCrcAz1QetlXL4On9765vAcbyx7TJUkpy5MSE7CYbxaDmv%2BXQxfBswoLXY9doqEjNYOnKk4XWEZ4WkYWIAf3Y91IA5aYl5ssGSrtMnhOzdA%2FCkcJcwBx%2F7zPw512ZPDT4RTRtKVf%2FTkm6tNGb46yDoxyg7sE10q4qYgdzkiyB30roQ0mrjzRcLTKakJjdpX4lwXlNh4586XXFl72okFnyEQqlu9Ss8eQ3zYHXfH3Xz3v7Sv6ugIa03g5D4zo%2B26bWKSFvLqH9UMG%2BjL%2BT%2FSMYpBGVwWEBEab4wuVWua1gJG0IElU9LAODAxg%2F1FTLJ6IaTE8fPv63iCO%2BP4L%2FnVAT6WvG%2BFv%2B803nJ4sJ0o8cTTxwefRz3iBDbqke6KUQeOqX9MDDkgSzpN3u2OPb2l81JEK2SK9I6aWfv6mYie6iDF1HjhDK8WMO%2Bzn1KCylrx%2FKXv%2FiO0a%2B5DY1UBorgk3zmoiZAJ9aZlvkOG7E424SCNlI1XqQEtfoe0A20aX1j1%2BDX7c%2BTn9dMV6chyTqjvxUZdvfHHct3uLeb98ig1lRjwoXUMVX7MwUhgyWwRdP6UOWp3Lj8ryD0psGZvoCrcFs8XjiRZSHvuRbcwhuLPXP5aSIzuaCsQ971%2Fz5ffZH7bSMOS75rwGOqUBWH7ccLI9Ht0YRgCw5wCTJB3n39u1g2r0KHuNkTFGTL%2FEjRoVjBaPorXaH3tkdTdEfgfeN5FFq%2FS4QukNs1IbP68ygk9qNicPse85rz9s2HK2jZdV%2FX%2BPl6us8ez9DnpibQgKs6H3j7rxUej%2BLhC5H%2B2mBTqrOOla5mcYULcwdr03AoJCYAmFSUBghPi9tKqGQ0YCLCsBIV8M2MGyHSNv2lN55knq&X-Amz-Signature=499c1e64e4e42b97483900d34feb11a2b9955c363db22e519b86430273463688&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TNMNZJAE%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T032520Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHwaCXVzLXdlc3QtMiJHMEUCIQDGpLk9lDaVoxdqCHDb6d7LQn%2FW0ELhcUKtsmwAPjibmgIgcT4nE0ERnzXSGAfumQhlRCwH%2FG228K%2FWX2wzWWK4h44qiAQIhP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCDh%2B%2BBte96UyM2lzCrcAz1QetlXL4On9765vAcbyx7TJUkpy5MSE7CYbxaDmv%2BXQxfBswoLXY9doqEjNYOnKk4XWEZ4WkYWIAf3Y91IA5aYl5ssGSrtMnhOzdA%2FCkcJcwBx%2F7zPw512ZPDT4RTRtKVf%2FTkm6tNGb46yDoxyg7sE10q4qYgdzkiyB30roQ0mrjzRcLTKakJjdpX4lwXlNh4586XXFl72okFnyEQqlu9Ss8eQ3zYHXfH3Xz3v7Sv6ugIa03g5D4zo%2B26bWKSFvLqH9UMG%2BjL%2BT%2FSMYpBGVwWEBEab4wuVWua1gJG0IElU9LAODAxg%2F1FTLJ6IaTE8fPv63iCO%2BP4L%2FnVAT6WvG%2BFv%2B803nJ4sJ0o8cTTxwefRz3iBDbqke6KUQeOqX9MDDkgSzpN3u2OPb2l81JEK2SK9I6aWfv6mYie6iDF1HjhDK8WMO%2Bzn1KCylrx%2FKXv%2FiO0a%2B5DY1UBorgk3zmoiZAJ9aZlvkOG7E424SCNlI1XqQEtfoe0A20aX1j1%2BDX7c%2BTn9dMV6chyTqjvxUZdvfHHct3uLeb98ig1lRjwoXUMVX7MwUhgyWwRdP6UOWp3Lj8ryD0psGZvoCrcFs8XjiRZSHvuRbcwhuLPXP5aSIzuaCsQ971%2Fz5ffZH7bSMOS75rwGOqUBWH7ccLI9Ht0YRgCw5wCTJB3n39u1g2r0KHuNkTFGTL%2FEjRoVjBaPorXaH3tkdTdEfgfeN5FFq%2FS4QukNs1IbP68ygk9qNicPse85rz9s2HK2jZdV%2FX%2BPl6us8ez9DnpibQgKs6H3j7rxUej%2BLhC5H%2B2mBTqrOOla5mcYULcwdr03AoJCYAmFSUBghPi9tKqGQ0YCLCsBIV8M2MGyHSNv2lN55knq&X-Amz-Signature=19ad0a3391c5f59465666a021525c7bed239c3dda4806edac19a4c6c4e59aa0f&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664TDYJIPT%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T032522Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHwaCXVzLXdlc3QtMiJHMEUCIFs9a%2BDFPDXpEZNVn8UDck1x4ioFRUAh0brL0%2FfyoOXwAiEA0A85mTsMqGXLNxTPiFQtT1Ffl3g2PaxnTySVkHuS72QqiAQIhP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKU%2FRfKtGcERFFIc3yrcA0QPvNgvViJXzE7fhBweEjClQBSXbacpZu%2BvVl4gxXVet6x3n1X%2FaNUcj6yA38S%2F8LQgTbaKuIdse9KbwRNMXlVNYYwUMVAkQREIppmSNt7T0oeNwOO1Cc0yRDUTPSReqKHcHIrdSwqkR8hYZFmthnHzdznZQAwlfpsKI0dA6qfNMA3mLvQqwJ4AB%2BGA5%2FxDFcAY8tSZAHWSe%2BslR2G7PtZ5WZ6Ubu4YA3KbScZJdG4iPVxr9QQAn23vGrmE45UN35JFUQImi2%2FRLpH%2FA2IkMuB8WHx01aF%2BMF4wFeSRuThwlzQkL1MLrkWfqN3nFf%2B%2Bitm1C2JtanVOrwJ1vKOwbyE7tLjpxTi5qvVrNoYV8n9VLUGhFUT38B9WSuNHviAoRwK8y6FDhPueT3SYldXv%2BtMM5gLCXKhdwPO3P1UeXRjJ86eYhoT%2FitegJSuIbpHX0aH%2FsCngoYP%2FT2RtGK99zXwRQw29Vx3QF4dW4aT2Xu2P5%2BXgBUJWse5eoEQlxXdfFGchBq2Yl8h%2FLQ4j1H0pFBZ%2ByDYlqZWfSoTAEOGmTN5zkjGFcnUStq8qOGCf6tzRAKCcGYXV3BXyhLGgOXaPeyllk6%2B5ntpRRP3f4kXLkBQ56KPZOBCQkQvf%2BplyMOm85rwGOqUB3l2vlwKmjV0DPu1Kw%2BdMV1ngDbgfi7RLm9DDn2ECft6aoYFLnyqqHfZ%2BpLfOXtE5BR0Ij8wWnZ1PY%2FHa0kZxSj8RZdXvJnZJ5AmMaJ3mBEnlXHimp9MpdyYmQWny5wW3dihxwlo4MgbAeRbKAEXadZ%2BngIOTUnQ1Pswvb8%2FBmbABe8JVmIWXWBTak4kvB2O6LnKGe1wDCdhV1kYbmnix9MEVWR%2Fm&X-Amz-Signature=260bd953c631c3c18349257f9f43ac34092cf1b029441913de7a997f03eb2cc7&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664L7IDLCM%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T032523Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHwaCXVzLXdlc3QtMiJGMEQCIA%2BhYPyr06IHUQQkWtQ2Yw%2FPHK7oSre2%2FnbOvKmzR%2BnEAiBoo5pmLQtIuq22KynpJnd2MF2D9QYppTHBUxdGBXEu%2FSqIBAiE%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMgQR69w4b%2FjM66OGCKtwDc5jErCl7SJNSqSg5%2B5cDfSmeXgO6JiZgiK1fHVhMkLEb4sztm%2BlgJ3j1o%2F%2Bv7VJylg00q7HiY%2F9frS%2Bcppixd2Tgq90hPIONR3IQo6HChzNqxUVbLRSnuQ5cC%2BtfH7uSKtMFFVlNAFYw3vV9QiirPh9tfypBM9%2FJYhhfTOLBMeplcnLyjVkNaLVM6A4xqrb%2BuvBCxmIfG%2FEMuqPCcy38zORu8I69xF%2Bd8i1Ae5qGYP5FXqYhqfls5kpZg4VcFm1JY54utz1Nzeyc%2BaAPpOJhuASbd%2FBYKJbIW46qhnMiJpWpklWiwLy0zdFKiPbEb6Ke81%2FD1ZL0vnhFgQMdQKN7eKWWo35kMVhxpcSt%2Fqyv%2FW8ddXjHEhJ5n8cYDGHUW2VIWiuZK2P9B5ind4wHM5eHwg1ildvvGSF%2FLYNB45yLOEGH9UQUUqHddX9tcdyNp%2BrTrmsuFv8KPtaX2FYcceUaRYCJVHW9ayf1ph9YO9RLqapdZCfSPPkMz8BxTDezr0nqbDDWzx7R76gNKAsDy77tzmoWUrm14rJfqavsoZLySPfGI90xR9paaFyBBUocz3SdA4g9e7YyHyRhKgW5FW7kcErA6OM5kie3dlDz9QW8i100YJvjpNaHq5vj1FEwgrzmvAY6pgGPTU1zXHw9IEa5PRlcYbm0XrJP4fIqDLhfXD3K5yUwZsVrVK8Lnj5FgkdVJZFvQE6Pv9ijHlchIKOEfUReKHAxztrcIcTXn8q%2FqWplWaibC7fWmlUjTJRJ0vH2g9PACwSt9SZP0%2BPIazfTwV%2F2CqfSf3Mxuu1t8HM4FSgLAc4qUnnYDVdrHp5YwAqaD5URBHvnOppIRNn1oSqQBhZYztJV7PSMS3FY&X-Amz-Signature=3a527928fa3daf2987c9d19d40e399d10d6e25ddf80ad8dcbe2ef866109e174d&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TNMNZJAE%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T032520Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHwaCXVzLXdlc3QtMiJHMEUCIQDGpLk9lDaVoxdqCHDb6d7LQn%2FW0ELhcUKtsmwAPjibmgIgcT4nE0ERnzXSGAfumQhlRCwH%2FG228K%2FWX2wzWWK4h44qiAQIhP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCDh%2B%2BBte96UyM2lzCrcAz1QetlXL4On9765vAcbyx7TJUkpy5MSE7CYbxaDmv%2BXQxfBswoLXY9doqEjNYOnKk4XWEZ4WkYWIAf3Y91IA5aYl5ssGSrtMnhOzdA%2FCkcJcwBx%2F7zPw512ZPDT4RTRtKVf%2FTkm6tNGb46yDoxyg7sE10q4qYgdzkiyB30roQ0mrjzRcLTKakJjdpX4lwXlNh4586XXFl72okFnyEQqlu9Ss8eQ3zYHXfH3Xz3v7Sv6ugIa03g5D4zo%2B26bWKSFvLqH9UMG%2BjL%2BT%2FSMYpBGVwWEBEab4wuVWua1gJG0IElU9LAODAxg%2F1FTLJ6IaTE8fPv63iCO%2BP4L%2FnVAT6WvG%2BFv%2B803nJ4sJ0o8cTTxwefRz3iBDbqke6KUQeOqX9MDDkgSzpN3u2OPb2l81JEK2SK9I6aWfv6mYie6iDF1HjhDK8WMO%2Bzn1KCylrx%2FKXv%2FiO0a%2B5DY1UBorgk3zmoiZAJ9aZlvkOG7E424SCNlI1XqQEtfoe0A20aX1j1%2BDX7c%2BTn9dMV6chyTqjvxUZdvfHHct3uLeb98ig1lRjwoXUMVX7MwUhgyWwRdP6UOWp3Lj8ryD0psGZvoCrcFs8XjiRZSHvuRbcwhuLPXP5aSIzuaCsQ971%2Fz5ffZH7bSMOS75rwGOqUBWH7ccLI9Ht0YRgCw5wCTJB3n39u1g2r0KHuNkTFGTL%2FEjRoVjBaPorXaH3tkdTdEfgfeN5FFq%2FS4QukNs1IbP68ygk9qNicPse85rz9s2HK2jZdV%2FX%2BPl6us8ez9DnpibQgKs6H3j7rxUej%2BLhC5H%2B2mBTqrOOla5mcYULcwdr03AoJCYAmFSUBghPi9tKqGQ0YCLCsBIV8M2MGyHSNv2lN55knq&X-Amz-Signature=fec9667661d410237d5ccc31dd4405719f2472144d2ca5785855518c62539fa5&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TNMNZJAE%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T032520Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHwaCXVzLXdlc3QtMiJHMEUCIQDGpLk9lDaVoxdqCHDb6d7LQn%2FW0ELhcUKtsmwAPjibmgIgcT4nE0ERnzXSGAfumQhlRCwH%2FG228K%2FWX2wzWWK4h44qiAQIhP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCDh%2B%2BBte96UyM2lzCrcAz1QetlXL4On9765vAcbyx7TJUkpy5MSE7CYbxaDmv%2BXQxfBswoLXY9doqEjNYOnKk4XWEZ4WkYWIAf3Y91IA5aYl5ssGSrtMnhOzdA%2FCkcJcwBx%2F7zPw512ZPDT4RTRtKVf%2FTkm6tNGb46yDoxyg7sE10q4qYgdzkiyB30roQ0mrjzRcLTKakJjdpX4lwXlNh4586XXFl72okFnyEQqlu9Ss8eQ3zYHXfH3Xz3v7Sv6ugIa03g5D4zo%2B26bWKSFvLqH9UMG%2BjL%2BT%2FSMYpBGVwWEBEab4wuVWua1gJG0IElU9LAODAxg%2F1FTLJ6IaTE8fPv63iCO%2BP4L%2FnVAT6WvG%2BFv%2B803nJ4sJ0o8cTTxwefRz3iBDbqke6KUQeOqX9MDDkgSzpN3u2OPb2l81JEK2SK9I6aWfv6mYie6iDF1HjhDK8WMO%2Bzn1KCylrx%2FKXv%2FiO0a%2B5DY1UBorgk3zmoiZAJ9aZlvkOG7E424SCNlI1XqQEtfoe0A20aX1j1%2BDX7c%2BTn9dMV6chyTqjvxUZdvfHHct3uLeb98ig1lRjwoXUMVX7MwUhgyWwRdP6UOWp3Lj8ryD0psGZvoCrcFs8XjiRZSHvuRbcwhuLPXP5aSIzuaCsQ971%2Fz5ffZH7bSMOS75rwGOqUBWH7ccLI9Ht0YRgCw5wCTJB3n39u1g2r0KHuNkTFGTL%2FEjRoVjBaPorXaH3tkdTdEfgfeN5FFq%2FS4QukNs1IbP68ygk9qNicPse85rz9s2HK2jZdV%2FX%2BPl6us8ez9DnpibQgKs6H3j7rxUej%2BLhC5H%2B2mBTqrOOla5mcYULcwdr03AoJCYAmFSUBghPi9tKqGQ0YCLCsBIV8M2MGyHSNv2lN55knq&X-Amz-Signature=eab578bae1973237be9a2610a67e2665add03cc3f4ea4efc0a2636a8fd9ff5f6&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TNMNZJAE%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T032520Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHwaCXVzLXdlc3QtMiJHMEUCIQDGpLk9lDaVoxdqCHDb6d7LQn%2FW0ELhcUKtsmwAPjibmgIgcT4nE0ERnzXSGAfumQhlRCwH%2FG228K%2FWX2wzWWK4h44qiAQIhP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCDh%2B%2BBte96UyM2lzCrcAz1QetlXL4On9765vAcbyx7TJUkpy5MSE7CYbxaDmv%2BXQxfBswoLXY9doqEjNYOnKk4XWEZ4WkYWIAf3Y91IA5aYl5ssGSrtMnhOzdA%2FCkcJcwBx%2F7zPw512ZPDT4RTRtKVf%2FTkm6tNGb46yDoxyg7sE10q4qYgdzkiyB30roQ0mrjzRcLTKakJjdpX4lwXlNh4586XXFl72okFnyEQqlu9Ss8eQ3zYHXfH3Xz3v7Sv6ugIa03g5D4zo%2B26bWKSFvLqH9UMG%2BjL%2BT%2FSMYpBGVwWEBEab4wuVWua1gJG0IElU9LAODAxg%2F1FTLJ6IaTE8fPv63iCO%2BP4L%2FnVAT6WvG%2BFv%2B803nJ4sJ0o8cTTxwefRz3iBDbqke6KUQeOqX9MDDkgSzpN3u2OPb2l81JEK2SK9I6aWfv6mYie6iDF1HjhDK8WMO%2Bzn1KCylrx%2FKXv%2FiO0a%2B5DY1UBorgk3zmoiZAJ9aZlvkOG7E424SCNlI1XqQEtfoe0A20aX1j1%2BDX7c%2BTn9dMV6chyTqjvxUZdvfHHct3uLeb98ig1lRjwoXUMVX7MwUhgyWwRdP6UOWp3Lj8ryD0psGZvoCrcFs8XjiRZSHvuRbcwhuLPXP5aSIzuaCsQ971%2Fz5ffZH7bSMOS75rwGOqUBWH7ccLI9Ht0YRgCw5wCTJB3n39u1g2r0KHuNkTFGTL%2FEjRoVjBaPorXaH3tkdTdEfgfeN5FFq%2FS4QukNs1IbP68ygk9qNicPse85rz9s2HK2jZdV%2FX%2BPl6us8ez9DnpibQgKs6H3j7rxUej%2BLhC5H%2B2mBTqrOOla5mcYULcwdr03AoJCYAmFSUBghPi9tKqGQ0YCLCsBIV8M2MGyHSNv2lN55knq&X-Amz-Signature=6459880352f85e5891dd912940c98108a12424ec1d5f9d8ea248487cfac09b7e&X-Amz-SignedHeaders=host&x-id=GetObject)


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

