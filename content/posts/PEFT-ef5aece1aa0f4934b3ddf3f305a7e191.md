---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4667SJOMSHS%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250205T172030Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEDEaCXVzLXdlc3QtMiJHMEUCIEmJIg63ukLdtvyB3q49Lsui0Hu%2FIopQc1aKWBT9a06NAiEAx\
  ugyBfPhB2fmE7IuIbdBG5%2FzngZm4aNawIzg3JT%2B1U0q%2FwMISRAAGgw2Mzc0MjMxODM4MDUi\
  DBzz1N5MT%2FixQcKOhSrcAzgimRWpfFAz4%2FZCA5nB2DYWxgyDIOFWgEyUKZ9FpK2Rw0mtovjai\
  JQvKegF2FzVEsF2tVtKd06aPG7Phq%2FL1hGRuXBQgQkMebaG%2BsTKK4WwQilEulSLJ0qKhRu%2F\
  KBBqfmX%2BtKRVIrokV90qnuYP%2BZukkJbWBO1CV9fzyVSb%2BMr9%2F2sJ6CEVkG%2BaL3BmT%2\
  BEhXHPKu9t9PEIH4vEMX8WZx%2BkqA%2BbYwLd54zD%2BBxsjTys10G3vMnQ7aRI%2B%2FfKgkxQA\
  lrpUY9gPIuMGGHkW6o42xVlXjJ00ZpsF1Y1xE3dBOcKfkAvnlqCcMjHpjRKc6UDihvN85RsoIU3%2\
  BSgNcSX8W0rl%2FFEbWSGoQT9F%2FPStNj9R%2F1j44ItWZxsg%2Fr2n5rkkle3h0CBrwRXHrHQY%\
  2Bz2Qs1%2B%2BqU9SlGB9drSTIeaw2tfWGxhR%2FwjmziDmFV6WGy6p4DMKa%2FZs4e4RbcSpVPx5\
  QHJeWIF%2FBldnWDuNbuB9km8r7emR310QpJWC%2BCKuX8Rj2QO%2B%2B18g1j%2BLOrKkUVp3Yd7\
  rN5tZO4okP%2BsAcTx80qVZwnFrMmBExXP%2F7%2BPVhg6P3w7G2ODx78ae%2BYdWdvhWSi7Jk26d\
  N3fluq3LMLf8mZSkMn4geV2CBenuPrpHOMKyfjr0GOqUBZzXUUXwkX1lQCj7FnWNzQ9goOT4%2Fs7\
  HJL9uPBYrfII%2BXGUefKq%2BW9hKBLJhbw6PiaM1s7KU0bjvXyIZNg6Imjxf7yVExsY1tOmHR%2F\
  qKoQTGYpX5f4efR8PVgnxrig3njCOX3i8KNJ7m7E9PfSuzBrmRpI0sGxDyZ8Ebeg%2BXVCETrEjf7\
  GswvxJKH9EDuecilzz8UGh9P56CJsmNKhuhU37aedXsf&X-Amz-Signature=47440fe5e68db31d\
  5bb8f649a302981803c5e6fbe4133eb55d914dc0129248bf&X-Amz-SignedHeaders=host&x-i\
  d=GetObject"
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
        redential=ASIAZI2LB4666XUWPDAS%2F20250205%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250205T171911Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEDEaCXVzLXdlc3QtMiJGMEQCIELS%2F8we0tgQy%2B%2FwnilM7dcGZ\
        wNWmYpmESDolDY%2FGkN3AiAufv99v2Afv%2FPvbHRoqwTjSDb4zvnvUGzh8clpQOoA9ir%\
        2FAwhJEAAaDDYzNzQyMzE4MzgwNSIMN95u8gQ6NQ8HdJzMKtwDpH3ail%2Brq8FKAR7RrcV\
        RhNijQKpnxhfKb%2FSOEJBY8EoklCIlbrom7WnT6KcvBHzBdp%2BqbagY1DbPyD6XOLWbD3\
        lTK6AyAp0LTsRotoiUECe33EytrsF2zNHSTURDOg6m%2BalnjCpCYAlpV%2FVvd4%2B8HCl\
        QI9Gng40ggC%2Fs2DUAR6ZF5hWRfpCaWe45kd%2F8TN6XzMfiPvVFOD5s9zWt43N7f15K9j\
        VnMKszYC3csVDQKuBd%2B97vikplvHpMUcFMVKhpDsPR7il1WWNdEtbtiYfFJJBZPB%2FKe\
        QcW9FwiGnyQAzS4C8qd7U%2FAcIMS7viOsjaRGr%2FHsXc4ELDubnlg11tURhjJeDjsoNWv\
        IySCsD4ks90r1DSredhDqQWRv8jYuWvWZZx51oBfnPRRXAvC1u7T0leGJ4XaefCLs9Xkm3w\
        3AWg%2FOvPuZDuxUxpJP3uZDO1sqrbse6EBgCdX%2FDGX8we4%2BGXiNJ3kgeePnOGBZlw%\
        2FDo8qWkEH0hh8Q5y1UEtN3OJFmcDWA4yod%2FLBwokJ9WbEQvnqhLcnuVejtgBhyRzuTBA\
        XNhQD7ycLQVi5UG6tyeOV0wD1bs7iSMXFM4GsqVCiIdP%2BbF3KYi8dau3ZFc3B%2FDUb82\
        LVNdTFQD%2FP26ow2Z6OvQY6pgEjlu9ot2WmxG3zMs3zHrCkr5a9RRsKIwmSW11Ktcvn5op\
        rirztHYBv1RRAbpjvzIdmlRrTRTpWoJzIhPMm%2Bvwjzj7APBeP2mMBoz1PbMu7FR4dhFMn\
        nEK%2FJBOSdeCfA94i%2Fm2viS%2B2aPywp73e9gzxmETGRLvYWyu3ZBKR6G%2FiL%2BIAy\
        nLlIevkWiUPNQK0TzCRld9gEezLwO2iiP9j3p9rpEAqWQRd&X-Amz-Signature=b31748a\
        a08edccbb1b1454998e78e6fb1b7bed4b5f579d91d073fbf151014878&X-Amz-SignedH\
        eaders=host&x-id=GetObject"
      expiry_time: "2025-02-05T18:19:11.878Z"
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
UPDATE_TIME: "2025-02-05T17:20:38.750Z"
EXPIRY_TIME: "2025-02-05T18:20:28.599Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46657SAVSQS%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T172029Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDEaCXVzLXdlc3QtMiJHMEUCICb%2BZFZ3vvbHPrHiv6q7rbNFtzqZF0L5OdiSKJkcU9O1AiEAlWueUhJnGbZvuxAE54UZIxExdQyAcCsb52%2BAizTCSQQq%2FwMISRAAGgw2Mzc0MjMxODM4MDUiDNMwXYEwN5A8gOobFCrcA0cN4Bwep0uhkOEENfva3RZk0yAgAHF50planJcA8UypVS9ozu4WhVIFqkaqKrinkBzreYDSFb9yMdpk7zotOjYcLS2uhMCbljy4IBWfpmYWrbwDOLraMfPgPnzzCep0Zoa6DacwfHT91Npjwye%2Fx3n9adz7aTK4AA8TLu3jQCbWD%2Bh%2BLpegiy%2FQL9ud5xFbpsVSpD4wwtzN%2FKvJYY0r4zLQ7yWR6QwMcRm433xt4kBee%2FgcGv2vJKQQyh5%2BJLPJ0nwSNiM2flkZBXXlGaBUFvc6Alu3K4lzBjB7bvWchMiJtoTvPvyQyyFUYLQcD5eUzWaaZ3mKcUL59%2BTIsD8fLo5j7o9sRq8KcmKkpQEl09Nr0uKTKFX0Zuxed%2FdjGH1y7eadcDi%2B48qELN%2Bax1IHkAYO7PQbdaab8E42zaYlKxsmwXTDOLifknMCUVUX%2BxgwrYIONJpw6JbMSu8IV9VtmfP%2Byb6Lc%2BcTxyax09kJqWRdRv0nXsTYkqhB8v%2BsBEMMO0PxhroMV7X%2FpgFW7hPFDR%2Fq1BUGdBg2%2Fmm7GW65Kf8e%2FIp%2Fu6gRdmt%2FaLioV7lQHxpnvDMMzsBFOiM6P2ajmqO1CG4uikSmEYPo4uAMAgTRYOM9gys4LnNzb73PMPiejr0GOqUB7%2BoU9tXRsqjds3PkMdKlDHMzel8xJN389Va%2BRg6IVHAgnHgN5gSi0bxa%2FX7eUNpWv2r%2BTVoeOAe%2B9Xmf5FFXdCQ5%2Bes4uJPj87knHR8GdWxcjakq4yZVo8IihRPxv7fg%2BhHrcbR0qJIvA83yD4xiuLW4vHXwTGMOOES7TuxoLwH7XgmZxJGeg01NUy6oedEAOF4YPzhnZYF659OPDfQtGDHL0zwy&X-Amz-Signature=18ebf4e589d49760e1deee82f7fcbfa139359f96151583385515dda3a4083174&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46657SAVSQS%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T172029Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDEaCXVzLXdlc3QtMiJHMEUCICb%2BZFZ3vvbHPrHiv6q7rbNFtzqZF0L5OdiSKJkcU9O1AiEAlWueUhJnGbZvuxAE54UZIxExdQyAcCsb52%2BAizTCSQQq%2FwMISRAAGgw2Mzc0MjMxODM4MDUiDNMwXYEwN5A8gOobFCrcA0cN4Bwep0uhkOEENfva3RZk0yAgAHF50planJcA8UypVS9ozu4WhVIFqkaqKrinkBzreYDSFb9yMdpk7zotOjYcLS2uhMCbljy4IBWfpmYWrbwDOLraMfPgPnzzCep0Zoa6DacwfHT91Npjwye%2Fx3n9adz7aTK4AA8TLu3jQCbWD%2Bh%2BLpegiy%2FQL9ud5xFbpsVSpD4wwtzN%2FKvJYY0r4zLQ7yWR6QwMcRm433xt4kBee%2FgcGv2vJKQQyh5%2BJLPJ0nwSNiM2flkZBXXlGaBUFvc6Alu3K4lzBjB7bvWchMiJtoTvPvyQyyFUYLQcD5eUzWaaZ3mKcUL59%2BTIsD8fLo5j7o9sRq8KcmKkpQEl09Nr0uKTKFX0Zuxed%2FdjGH1y7eadcDi%2B48qELN%2Bax1IHkAYO7PQbdaab8E42zaYlKxsmwXTDOLifknMCUVUX%2BxgwrYIONJpw6JbMSu8IV9VtmfP%2Byb6Lc%2BcTxyax09kJqWRdRv0nXsTYkqhB8v%2BsBEMMO0PxhroMV7X%2FpgFW7hPFDR%2Fq1BUGdBg2%2Fmm7GW65Kf8e%2FIp%2Fu6gRdmt%2FaLioV7lQHxpnvDMMzsBFOiM6P2ajmqO1CG4uikSmEYPo4uAMAgTRYOM9gys4LnNzb73PMPiejr0GOqUB7%2BoU9tXRsqjds3PkMdKlDHMzel8xJN389Va%2BRg6IVHAgnHgN5gSi0bxa%2FX7eUNpWv2r%2BTVoeOAe%2B9Xmf5FFXdCQ5%2Bes4uJPj87knHR8GdWxcjakq4yZVo8IihRPxv7fg%2BhHrcbR0qJIvA83yD4xiuLW4vHXwTGMOOES7TuxoLwH7XgmZxJGeg01NUy6oedEAOF4YPzhnZYF659OPDfQtGDHL0zwy&X-Amz-Signature=68a114bf36c438200ae93202c545aad84763792cf15ce03398213901e7b39d5b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46657SAVSQS%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T172029Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDEaCXVzLXdlc3QtMiJHMEUCICb%2BZFZ3vvbHPrHiv6q7rbNFtzqZF0L5OdiSKJkcU9O1AiEAlWueUhJnGbZvuxAE54UZIxExdQyAcCsb52%2BAizTCSQQq%2FwMISRAAGgw2Mzc0MjMxODM4MDUiDNMwXYEwN5A8gOobFCrcA0cN4Bwep0uhkOEENfva3RZk0yAgAHF50planJcA8UypVS9ozu4WhVIFqkaqKrinkBzreYDSFb9yMdpk7zotOjYcLS2uhMCbljy4IBWfpmYWrbwDOLraMfPgPnzzCep0Zoa6DacwfHT91Npjwye%2Fx3n9adz7aTK4AA8TLu3jQCbWD%2Bh%2BLpegiy%2FQL9ud5xFbpsVSpD4wwtzN%2FKvJYY0r4zLQ7yWR6QwMcRm433xt4kBee%2FgcGv2vJKQQyh5%2BJLPJ0nwSNiM2flkZBXXlGaBUFvc6Alu3K4lzBjB7bvWchMiJtoTvPvyQyyFUYLQcD5eUzWaaZ3mKcUL59%2BTIsD8fLo5j7o9sRq8KcmKkpQEl09Nr0uKTKFX0Zuxed%2FdjGH1y7eadcDi%2B48qELN%2Bax1IHkAYO7PQbdaab8E42zaYlKxsmwXTDOLifknMCUVUX%2BxgwrYIONJpw6JbMSu8IV9VtmfP%2Byb6Lc%2BcTxyax09kJqWRdRv0nXsTYkqhB8v%2BsBEMMO0PxhroMV7X%2FpgFW7hPFDR%2Fq1BUGdBg2%2Fmm7GW65Kf8e%2FIp%2Fu6gRdmt%2FaLioV7lQHxpnvDMMzsBFOiM6P2ajmqO1CG4uikSmEYPo4uAMAgTRYOM9gys4LnNzb73PMPiejr0GOqUB7%2BoU9tXRsqjds3PkMdKlDHMzel8xJN389Va%2BRg6IVHAgnHgN5gSi0bxa%2FX7eUNpWv2r%2BTVoeOAe%2B9Xmf5FFXdCQ5%2Bes4uJPj87knHR8GdWxcjakq4yZVo8IihRPxv7fg%2BhHrcbR0qJIvA83yD4xiuLW4vHXwTGMOOES7TuxoLwH7XgmZxJGeg01NUy6oedEAOF4YPzhnZYF659OPDfQtGDHL0zwy&X-Amz-Signature=c15701962345ee9d895dbe823a1e9c58a1b2100b5126090dcd14e4958c4dc1be&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46657SAVSQS%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T172029Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDEaCXVzLXdlc3QtMiJHMEUCICb%2BZFZ3vvbHPrHiv6q7rbNFtzqZF0L5OdiSKJkcU9O1AiEAlWueUhJnGbZvuxAE54UZIxExdQyAcCsb52%2BAizTCSQQq%2FwMISRAAGgw2Mzc0MjMxODM4MDUiDNMwXYEwN5A8gOobFCrcA0cN4Bwep0uhkOEENfva3RZk0yAgAHF50planJcA8UypVS9ozu4WhVIFqkaqKrinkBzreYDSFb9yMdpk7zotOjYcLS2uhMCbljy4IBWfpmYWrbwDOLraMfPgPnzzCep0Zoa6DacwfHT91Npjwye%2Fx3n9adz7aTK4AA8TLu3jQCbWD%2Bh%2BLpegiy%2FQL9ud5xFbpsVSpD4wwtzN%2FKvJYY0r4zLQ7yWR6QwMcRm433xt4kBee%2FgcGv2vJKQQyh5%2BJLPJ0nwSNiM2flkZBXXlGaBUFvc6Alu3K4lzBjB7bvWchMiJtoTvPvyQyyFUYLQcD5eUzWaaZ3mKcUL59%2BTIsD8fLo5j7o9sRq8KcmKkpQEl09Nr0uKTKFX0Zuxed%2FdjGH1y7eadcDi%2B48qELN%2Bax1IHkAYO7PQbdaab8E42zaYlKxsmwXTDOLifknMCUVUX%2BxgwrYIONJpw6JbMSu8IV9VtmfP%2Byb6Lc%2BcTxyax09kJqWRdRv0nXsTYkqhB8v%2BsBEMMO0PxhroMV7X%2FpgFW7hPFDR%2Fq1BUGdBg2%2Fmm7GW65Kf8e%2FIp%2Fu6gRdmt%2FaLioV7lQHxpnvDMMzsBFOiM6P2ajmqO1CG4uikSmEYPo4uAMAgTRYOM9gys4LnNzb73PMPiejr0GOqUB7%2BoU9tXRsqjds3PkMdKlDHMzel8xJN389Va%2BRg6IVHAgnHgN5gSi0bxa%2FX7eUNpWv2r%2BTVoeOAe%2B9Xmf5FFXdCQ5%2Bes4uJPj87knHR8GdWxcjakq4yZVo8IihRPxv7fg%2BhHrcbR0qJIvA83yD4xiuLW4vHXwTGMOOES7TuxoLwH7XgmZxJGeg01NUy6oedEAOF4YPzhnZYF659OPDfQtGDHL0zwy&X-Amz-Signature=727536e44577933f3b1d7b10bced941bd8580fb90171746f8b71ba391f201eb1&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46657SAVSQS%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T172029Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDEaCXVzLXdlc3QtMiJHMEUCICb%2BZFZ3vvbHPrHiv6q7rbNFtzqZF0L5OdiSKJkcU9O1AiEAlWueUhJnGbZvuxAE54UZIxExdQyAcCsb52%2BAizTCSQQq%2FwMISRAAGgw2Mzc0MjMxODM4MDUiDNMwXYEwN5A8gOobFCrcA0cN4Bwep0uhkOEENfva3RZk0yAgAHF50planJcA8UypVS9ozu4WhVIFqkaqKrinkBzreYDSFb9yMdpk7zotOjYcLS2uhMCbljy4IBWfpmYWrbwDOLraMfPgPnzzCep0Zoa6DacwfHT91Npjwye%2Fx3n9adz7aTK4AA8TLu3jQCbWD%2Bh%2BLpegiy%2FQL9ud5xFbpsVSpD4wwtzN%2FKvJYY0r4zLQ7yWR6QwMcRm433xt4kBee%2FgcGv2vJKQQyh5%2BJLPJ0nwSNiM2flkZBXXlGaBUFvc6Alu3K4lzBjB7bvWchMiJtoTvPvyQyyFUYLQcD5eUzWaaZ3mKcUL59%2BTIsD8fLo5j7o9sRq8KcmKkpQEl09Nr0uKTKFX0Zuxed%2FdjGH1y7eadcDi%2B48qELN%2Bax1IHkAYO7PQbdaab8E42zaYlKxsmwXTDOLifknMCUVUX%2BxgwrYIONJpw6JbMSu8IV9VtmfP%2Byb6Lc%2BcTxyax09kJqWRdRv0nXsTYkqhB8v%2BsBEMMO0PxhroMV7X%2FpgFW7hPFDR%2Fq1BUGdBg2%2Fmm7GW65Kf8e%2FIp%2Fu6gRdmt%2FaLioV7lQHxpnvDMMzsBFOiM6P2ajmqO1CG4uikSmEYPo4uAMAgTRYOM9gys4LnNzb73PMPiejr0GOqUB7%2BoU9tXRsqjds3PkMdKlDHMzel8xJN389Va%2BRg6IVHAgnHgN5gSi0bxa%2FX7eUNpWv2r%2BTVoeOAe%2B9Xmf5FFXdCQ5%2Bes4uJPj87knHR8GdWxcjakq4yZVo8IihRPxv7fg%2BhHrcbR0qJIvA83yD4xiuLW4vHXwTGMOOES7TuxoLwH7XgmZxJGeg01NUy6oedEAOF4YPzhnZYF659OPDfQtGDHL0zwy&X-Amz-Signature=f510d9d8b0793f7c0178d3236d724921f93dadcef13cff5902f0b6ed57a86154&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WIQU3B6E%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T172029Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDEaCXVzLXdlc3QtMiJHMEUCIGnntM0o7%2FCHfWOEoUJryPdWXO%2BlRWmQZNN4S75a1CbWAiEArHImebWfOEu0pFFXGO4JUr5eGPOAa5mL3nDyampPFLMq%2FwMISRAAGgw2Mzc0MjMxODM4MDUiDJoZJ1kbJ1%2BZ24PfjCrcA2baO5ScgbTFua9M4mZmQx%2FGXc3RsLrk0MAE63PufODkoKfWoiw466Potc37%2FWFccyHsI9Zh%2BZuiYNqRy98PonZ4WIe1W3FsKN39FjeHi9PQ%2FuZpvnb%2F%2FYFnO%2FqCmgn9BV5MUL9p4zvfw4jQJPNIMNZgItrhUT7dHibsqGMvp%2BINZqpxmoLfcYveEHZej%2BEngS%2BQ15nNDp%2FaKYsCYg0qCQvjQEut8CpY6RvL26sN7VBt%2BbILELEXRUBJCZQ10dtV3HrwrFfFPB%2FLSSEUXbaXCdpeEN16QlpbBS9YokH6Zseugz%2FpCvczcK3BHksSRvL0z0Bz12mCrgYPpgI5aDH%2F4HlopLxEC1OVAMbXdZEaw2iWDlKrM5vI6huH0Ulygs0kdpZXK%2FtsC8OnxuSQEjCOj5qaCqt0ADsTYKJyWqkBYtJkypBKx1nS8b1H5eeiPozzHb%2BY3jgJq6PZyo03EqybCdp8Qy0r8E55ueUygHlX6IKixPSCVGYenbvzuPmUoMclpVjlPWvGWsvV3EqqI7VIX4yWSeKizK32yPkTcmEBYoniFpH0MnLqm8%2B7B2x5tnWooSdak56ZXt6GyJKcr%2FM6%2FJutQLLqloGO223SYDpjUKG7sbx6SUu94xvx7uQkMLGfjr0GOqUB5Cc0KdyBa51%2BhltnvwZ53nFWsgUVkdVl7ng83g%2BWg%2FTUHzscp5BqONjiEAQTDy59HnxY7EXtkQMDxil93jBIQYmC%2Fwb2dxPZ%2Bi23eXidJ9siYWLyi6yeINNFcqHbtpghpTCZaFxD8oOlfMC0IYXyu8HK9sPUTlYEJA1FtBkrQ9vJa%2FJhrprgsMK8dDS8l%2BgogO0dfF9SLLpAgAMbM4pxaM9zQBCm&X-Amz-Signature=c4993fa1f4e930e9f59a4616c6d39cb3302ef01f10b4ebcfa9f7124e910a8e1d&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667RSO2MGJ%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T172030Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDEaCXVzLXdlc3QtMiJIMEYCIQD1RTkNFzD10gQcWzkXpwfrvgq%2BcirqwFtmujhTjUTALwIhAKNcWlz%2FC9ZscbFw0W%2F6wFm7R4NI4ZgHlaw69tpobLj9Kv8DCEkQABoMNjM3NDIzMTgzODA1IgyOPZalxnUVfH6q8RQq3AMaLo%2BObvKbGWGkCSrxoxzowP%2Fz7HwjLTwANADGXHG0YQSrKuJo7tYO2cMnHyBjjDuEYEDzvktlvdl9PB9dJrGTYOIx4NPYeFST%2BTT1ElYN5YSfza46C%2B0OyTL6zNGIzSEjjs6jqv5d65L6iEqb9D%2F0fV1sVOp9tQmp%2BRnfOU3N6acAipD6h8nIy60x%2FfwKW2aC2lUIBPBcEpI1xa5Ubd5wH3tLj8UeqFf7l3Us2W%2BwoKePT0UmRHv7QLIKfwv%2FsudIPesG%2BCnjDWwL3Hczo28wn5BG5gg4SsY3AoY768mZ8nAA0u7az3dqYmLJ8xnW3UUTmYuG5QSKTkNfVNOcmzv4ttZ7PvmFKcLAntH351UGEIW25Y76nmmhhoNOlKmpEPamxKtbUkH%2BZg9MeUaK8jdlQczTL04kxRXIIy9DEiT4hscssNj0f5%2FshAfF7bQfINMn2zFwTbsFjUj1GsgaORShYs5ft257eURtAm3fz43DLptJ9aBK%2F4ToBSdH9nQuKpDLyYjOLhArOzoB3s1lAtOdp3p4tpB4jAqoq8ElvcgjMgsqFs5MY0x%2FFKaUJHr9W5PXUIvLyG5TgWCTrnSC9zZk4RtDZFD91w%2BlWEaEWh%2FtTL8qKnyFAoLu6c1%2BSzDmno69BjqkASJHbtvvPReLiivAC0kKttBHfysleC45Y90vZPSBYaWl0jgM9POz78Qfq98GYi2blbKGSzPporLKRvEhgDwm0aHMGmF1xeb2558%2FdbMoHpUwKNJbRfgeKK2D2JpcNdJMay%2B7aXE3GE6R8jsjgYzk7rvMPb9Em2d2Kao1%2FaQ0UjTALpJb%2FQezFSB6yjQ9R%2F%2FTheMDtlocVdzT6TgAwXuOuKILfka0&X-Amz-Signature=1a2166432bc1290b56dd1948d5546a0e1f904848e7b80f7152ad68ab31c1c3b8&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46657SAVSQS%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T172029Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDEaCXVzLXdlc3QtMiJHMEUCICb%2BZFZ3vvbHPrHiv6q7rbNFtzqZF0L5OdiSKJkcU9O1AiEAlWueUhJnGbZvuxAE54UZIxExdQyAcCsb52%2BAizTCSQQq%2FwMISRAAGgw2Mzc0MjMxODM4MDUiDNMwXYEwN5A8gOobFCrcA0cN4Bwep0uhkOEENfva3RZk0yAgAHF50planJcA8UypVS9ozu4WhVIFqkaqKrinkBzreYDSFb9yMdpk7zotOjYcLS2uhMCbljy4IBWfpmYWrbwDOLraMfPgPnzzCep0Zoa6DacwfHT91Npjwye%2Fx3n9adz7aTK4AA8TLu3jQCbWD%2Bh%2BLpegiy%2FQL9ud5xFbpsVSpD4wwtzN%2FKvJYY0r4zLQ7yWR6QwMcRm433xt4kBee%2FgcGv2vJKQQyh5%2BJLPJ0nwSNiM2flkZBXXlGaBUFvc6Alu3K4lzBjB7bvWchMiJtoTvPvyQyyFUYLQcD5eUzWaaZ3mKcUL59%2BTIsD8fLo5j7o9sRq8KcmKkpQEl09Nr0uKTKFX0Zuxed%2FdjGH1y7eadcDi%2B48qELN%2Bax1IHkAYO7PQbdaab8E42zaYlKxsmwXTDOLifknMCUVUX%2BxgwrYIONJpw6JbMSu8IV9VtmfP%2Byb6Lc%2BcTxyax09kJqWRdRv0nXsTYkqhB8v%2BsBEMMO0PxhroMV7X%2FpgFW7hPFDR%2Fq1BUGdBg2%2Fmm7GW65Kf8e%2FIp%2Fu6gRdmt%2FaLioV7lQHxpnvDMMzsBFOiM6P2ajmqO1CG4uikSmEYPo4uAMAgTRYOM9gys4LnNzb73PMPiejr0GOqUB7%2BoU9tXRsqjds3PkMdKlDHMzel8xJN389Va%2BRg6IVHAgnHgN5gSi0bxa%2FX7eUNpWv2r%2BTVoeOAe%2B9Xmf5FFXdCQ5%2Bes4uJPj87knHR8GdWxcjakq4yZVo8IihRPxv7fg%2BhHrcbR0qJIvA83yD4xiuLW4vHXwTGMOOES7TuxoLwH7XgmZxJGeg01NUy6oedEAOF4YPzhnZYF659OPDfQtGDHL0zwy&X-Amz-Signature=e0ed99e3781ec8df8798b8f035e0cb51e566644a64e42a82cedd8060862f90a7&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46657SAVSQS%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T172029Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDEaCXVzLXdlc3QtMiJHMEUCICb%2BZFZ3vvbHPrHiv6q7rbNFtzqZF0L5OdiSKJkcU9O1AiEAlWueUhJnGbZvuxAE54UZIxExdQyAcCsb52%2BAizTCSQQq%2FwMISRAAGgw2Mzc0MjMxODM4MDUiDNMwXYEwN5A8gOobFCrcA0cN4Bwep0uhkOEENfva3RZk0yAgAHF50planJcA8UypVS9ozu4WhVIFqkaqKrinkBzreYDSFb9yMdpk7zotOjYcLS2uhMCbljy4IBWfpmYWrbwDOLraMfPgPnzzCep0Zoa6DacwfHT91Npjwye%2Fx3n9adz7aTK4AA8TLu3jQCbWD%2Bh%2BLpegiy%2FQL9ud5xFbpsVSpD4wwtzN%2FKvJYY0r4zLQ7yWR6QwMcRm433xt4kBee%2FgcGv2vJKQQyh5%2BJLPJ0nwSNiM2flkZBXXlGaBUFvc6Alu3K4lzBjB7bvWchMiJtoTvPvyQyyFUYLQcD5eUzWaaZ3mKcUL59%2BTIsD8fLo5j7o9sRq8KcmKkpQEl09Nr0uKTKFX0Zuxed%2FdjGH1y7eadcDi%2B48qELN%2Bax1IHkAYO7PQbdaab8E42zaYlKxsmwXTDOLifknMCUVUX%2BxgwrYIONJpw6JbMSu8IV9VtmfP%2Byb6Lc%2BcTxyax09kJqWRdRv0nXsTYkqhB8v%2BsBEMMO0PxhroMV7X%2FpgFW7hPFDR%2Fq1BUGdBg2%2Fmm7GW65Kf8e%2FIp%2Fu6gRdmt%2FaLioV7lQHxpnvDMMzsBFOiM6P2ajmqO1CG4uikSmEYPo4uAMAgTRYOM9gys4LnNzb73PMPiejr0GOqUB7%2BoU9tXRsqjds3PkMdKlDHMzel8xJN389Va%2BRg6IVHAgnHgN5gSi0bxa%2FX7eUNpWv2r%2BTVoeOAe%2B9Xmf5FFXdCQ5%2Bes4uJPj87knHR8GdWxcjakq4yZVo8IihRPxv7fg%2BhHrcbR0qJIvA83yD4xiuLW4vHXwTGMOOES7TuxoLwH7XgmZxJGeg01NUy6oedEAOF4YPzhnZYF659OPDfQtGDHL0zwy&X-Amz-Signature=b326823a0c5c4e57696acea3fba0986188d81f4ee835b25f0c61445ca118f492&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46657SAVSQS%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T172029Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDEaCXVzLXdlc3QtMiJHMEUCICb%2BZFZ3vvbHPrHiv6q7rbNFtzqZF0L5OdiSKJkcU9O1AiEAlWueUhJnGbZvuxAE54UZIxExdQyAcCsb52%2BAizTCSQQq%2FwMISRAAGgw2Mzc0MjMxODM4MDUiDNMwXYEwN5A8gOobFCrcA0cN4Bwep0uhkOEENfva3RZk0yAgAHF50planJcA8UypVS9ozu4WhVIFqkaqKrinkBzreYDSFb9yMdpk7zotOjYcLS2uhMCbljy4IBWfpmYWrbwDOLraMfPgPnzzCep0Zoa6DacwfHT91Npjwye%2Fx3n9adz7aTK4AA8TLu3jQCbWD%2Bh%2BLpegiy%2FQL9ud5xFbpsVSpD4wwtzN%2FKvJYY0r4zLQ7yWR6QwMcRm433xt4kBee%2FgcGv2vJKQQyh5%2BJLPJ0nwSNiM2flkZBXXlGaBUFvc6Alu3K4lzBjB7bvWchMiJtoTvPvyQyyFUYLQcD5eUzWaaZ3mKcUL59%2BTIsD8fLo5j7o9sRq8KcmKkpQEl09Nr0uKTKFX0Zuxed%2FdjGH1y7eadcDi%2B48qELN%2Bax1IHkAYO7PQbdaab8E42zaYlKxsmwXTDOLifknMCUVUX%2BxgwrYIONJpw6JbMSu8IV9VtmfP%2Byb6Lc%2BcTxyax09kJqWRdRv0nXsTYkqhB8v%2BsBEMMO0PxhroMV7X%2FpgFW7hPFDR%2Fq1BUGdBg2%2Fmm7GW65Kf8e%2FIp%2Fu6gRdmt%2FaLioV7lQHxpnvDMMzsBFOiM6P2ajmqO1CG4uikSmEYPo4uAMAgTRYOM9gys4LnNzb73PMPiejr0GOqUB7%2BoU9tXRsqjds3PkMdKlDHMzel8xJN389Va%2BRg6IVHAgnHgN5gSi0bxa%2FX7eUNpWv2r%2BTVoeOAe%2B9Xmf5FFXdCQ5%2Bes4uJPj87knHR8GdWxcjakq4yZVo8IihRPxv7fg%2BhHrcbR0qJIvA83yD4xiuLW4vHXwTGMOOES7TuxoLwH7XgmZxJGeg01NUy6oedEAOF4YPzhnZYF659OPDfQtGDHL0zwy&X-Amz-Signature=a645ba053a16fcbf14aa9da0355dd9d5904ec310a359a64f786fb2757b503cd7&X-Amz-SignedHeaders=host&x-id=GetObject)


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

