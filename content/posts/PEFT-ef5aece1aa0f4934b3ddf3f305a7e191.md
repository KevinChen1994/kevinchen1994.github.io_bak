---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4667EGYU5QT%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250223T092402Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjENT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCH1F6%2FZNdw5jK1hkT5\
  gnbTIZ3EPNyjpeh8aQbh42LvKMCIQDVx0hfK%2F9Z%2BXRFgJyBd2bYrLcbYvpjN0wjlO9nj75YMi\
  qIBAj9%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMvKp%2FiBKj21iBt\
  O3FKtwDjpx0SkFZpX85bWkesP4DphORSZSKAJgqSF2ClWpPYZUUMDmHyLvYvSuoRTDrj9rS9s%2BK\
  z5FLHy9XARd3lWMerzQg6IfeW1lQpZBDcJ%2BKjzmZRqSmRlseit3cVySvVGCbFzKbPjK3zEi9on5\
  uxXbYYmoxAekVCZMkVB6qfQUIH65%2F3KoTNmwRn0sBKes15VzdY5%2FsPYasNGqMMuHO5JVjrI36\
  9duWshim5EnIHnssM0z3l90ye6sGKzju0o85UnacgxooT74AF9GpZLueFp8I6of6XcMM8d7AZpd9b\
  gkzrWCxxDowxphnApx0nhobkK9JA7UKdAEZ5W1nO2NpjA5Fn%2B7C%2F4z8t0%2BxQlTCp5lNzx5Q\
  ro%2F9Xm9spD1iK2hKbVdaOIk5HwpL0Pk%2BA%2BiZeUv5qhdpX%2Fv0vfB2MG2OmiKjy2oQaapWX\
  LPnqHb2sNhQY71uWj24AndbvC4U6wBm11lC%2B9aFxvmyUx4RbtdkdB0fotOYCid%2BKr1s0IjLGY\
  Cwwl2Qj35OOd5rss1h9De0agtzOKdWBOI8HIcqAvoNcza7H53srbKdcvwH%2F08%2FExn2qpX42Hc\
  NFbOHexGeni2KGtc3husyEzsZz8N%2BvZclsCCe1GL%2F8S4NOZBdEt7U1RgwrrrqvQY6pgF8InUf\
  6uOsuY2iOgY32FW1mf4xF2qNkSl5Fk2%2FxgFCmzJI4iT4VNP1pGrUviPrMIdFTjmbSOKPv4Smi6y\
  lzsdWkSo7ndeiezDZhZohdSnDB4mhRRHNLYk13qauQLVZgSbA9h1qs%2FS33HwUiY3T1z6Aw4pCmF\
  XGzGsNcip5%2Bsc%2BqjY22mqbSGB8acyzc1CnsxWqZ7ZfZy56ORp7zVZzT8tsOsoWNAtn&X-Amz-\
  Signature=522df917fe958704e03c101a69e20076f2fd8218acc0d4f04b6ed8102ec7a2d7&X-\
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
        redential=ASIAZI2LB466U33XPQRX%2F20250223%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250223T092225Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjENj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQ\
        CIDUO9EovgXScoFQ4neQLuUn9%2BUmZtzRp7s8kQdzdLAZ4AiAS0RyYiaJCMZTU%2Fy8%2F\
        86sUhcHWyLVJSwxDKaJN5kQJ6ir%2FAwgREAAaDDYzNzQyMzE4MzgwNSIMK0tqtlxYirAvc\
        fYUKtwDEjWNVhIVf0AWeqEPWVcQaRYkxb6VuT6rR8aI5TP5RwnqNssa0SndS2n15YXmVl9e\
        hzM%2F%2BhAbBWvcnwo9%2Bd5RBLlc%2FZ8TPuFwdskNa4KPoPFpOxdq%2BJP5iRFVpg84u\
        rOvRqlK08eoO49cQasNRP2BxWxS0Hdr%2F2ax6mDZO4%2BWsQzjQlwuaT7fiBn5XKYs1M6L\
        ItQ4sYZF70C%2FWXKsebthb1s6mmsiaNPDN5bGd8mlUm1WUCgfCtWhV%2BkP7qE5rmWT5OK\
        c2VzLS3MW%2BA3sgtuH1u5AcRWKFGg9RGw%2Bkzrw8Ii6fNuJMpT6ouKkKnYFX6NFT9giLa\
        qgg9Bw1Yer4bgaU1b3ZQFVXoZdcvYSf3uVGfZP39E%2BkKOCCKrM5G0Xl7f54684PZpEsrq\
        uugBrboi27NYKxD2jp5W1kEaW%2BQ%2FUdnRgskQJo37DQ80uLhr3I%2B9M4jquWtNUHiH7\
        osTVt%2F5peIpfVnjmpqQoCHNe8PgoiUpreXY1FP9DEjLVSKxGatUfwbLIFlrEXpCPOh9VW\
        IDJTS1QYOwFyMFZ1XWYVZvXGlN4LrTg1HE96rWGefQvjoWzF77eiNRd3RuufI1BVyNgE8nV\
        M73mz1h7thiFLfRZKqeLTWeMPW1xuFb2T2Qw1Z3rvQY6pgGKDZfF69PbZ1srXBdy2Cw9C9n\
        xO4PNgNyrc1%2BvjSCBmyRUa5jc8LH%2Bel3Ipq9EzkeRAyRR2vmMSH%2B9U5zBareF1TKx\
        pG2WBXDMWRTYRjn4vdUHScnkO8Dzip8nhxYrUMun7Rr1okGNKSTGZ%2Bo%2FcwvQ8PTwwKg\
        ytgzwqX2ArEfdUDFWe7ZCPtN1%2FCGqFOMianO5OYl0JcEkALGzeNieSq689fGKVisb&X-A\
        mz-Signature=5046ee12805e397c1d3a089fd324344c96a1968ee4167ef6ff0e1ac8d8\
        0f7bc0&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-23T10:22:25.579Z"
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
UPDATE_TIME: "2025-02-23T09:24:10.133Z"
EXPIRY_TIME: "2025-02-23T10:23:54.913Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665PBNNWGE%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T092355Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIAp3dZ%2Fs2ZypGJCwMJLUdekag8oshkaxlHmn%2F4KOE3wpAiEApVVLMcjAqinoc%2B%2FmzUpcTAFqMd8V3zoP0EviKYl%2FAP4qiAQI%2Ff%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDA5Ui44gnpHqSuwr3CrcAzGtP8nHzDdrGO%2FNIOAiXIhwCoRbBJclWrAcbTi3c4lAN3ur8V%2BBoSoLqTwEOXhiF%2F%2BSNU6%2FzdOmtpvYX5%2BsdmUKta1GWp9yteoSTF93wIximh9aQBj%2FtpY8Y%2BT2oIKcJu2ZOI%2BZajA1cf0kiLhCoSgHyIWRdDtZQH8WYQ5L0ZuuyEC3vjIgBeJ7%2BWmo4Kca2BErlGmLoQVmhfMFHznIBks5nzBXJZqso7%2B2z9kGtCJ12l%2FXhIA06BS4YBxkB2tW1Kp8BcsgrU09q%2Bsik68JNdyl7rJNibWKC7N%2BCid6ImkKZcjqkDaI1cq4THMK9m0B3E6zPuZESmHDHoV83nmVUftxPrWOqRxCQ4nRb4mZ2odMtf90H94zNSPyiYnDNE%2ByQMQTHjHlP37xJpKNYs86bfIiEXrAYx7iEZFCV5e1XZ3nPqNsHKZd4IEsJtI6Zpn4L6jdlnjZ2hO7wAjRYKTWVA2MJqYVlyFVuNl80t7EDNEDI0U4P6wcEqbOXNYEeIsU2moGOb0Is0f25cfjBp%2Boop%2BiHCPzSAdqX7WxCq1%2FqUe9DjBoIIEccolpWqloSf9Yk%2BUG17fgAMIT8xT%2Bh9RlV9XCKtWkpP2NtPmP7KB52ZYGet42jTgEdjR0B6EyMJjC6r0GOqUBW0R0obAlp3Gl9o%2FrqpaK3SqRzs1xNbJeS8WFCAi%2F9SliLauuTJEjpnNnycDcf61zp4sLQA8KP1AQS7%2Bhs8UsYsLcfQa7rQPf2bvYio2ChSFm9OssvUhl0RTpEg2wTu7bclf01EqIOo0vdHwRKS1Y05SCM%2F0JtBoLUGxVSPXKuBzZzr4VCTsu90OqQbSTxAiKUb7fFaC0jD%2F%2BEWTm2UueZMgJmrPf&X-Amz-Signature=d9226a3fd0ffe9d576c0b4492fa4bdf78ba7c1bd2c5bcfa0eb9dc08733e561f8&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665PBNNWGE%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T092355Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIAp3dZ%2Fs2ZypGJCwMJLUdekag8oshkaxlHmn%2F4KOE3wpAiEApVVLMcjAqinoc%2B%2FmzUpcTAFqMd8V3zoP0EviKYl%2FAP4qiAQI%2Ff%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDA5Ui44gnpHqSuwr3CrcAzGtP8nHzDdrGO%2FNIOAiXIhwCoRbBJclWrAcbTi3c4lAN3ur8V%2BBoSoLqTwEOXhiF%2F%2BSNU6%2FzdOmtpvYX5%2BsdmUKta1GWp9yteoSTF93wIximh9aQBj%2FtpY8Y%2BT2oIKcJu2ZOI%2BZajA1cf0kiLhCoSgHyIWRdDtZQH8WYQ5L0ZuuyEC3vjIgBeJ7%2BWmo4Kca2BErlGmLoQVmhfMFHznIBks5nzBXJZqso7%2B2z9kGtCJ12l%2FXhIA06BS4YBxkB2tW1Kp8BcsgrU09q%2Bsik68JNdyl7rJNibWKC7N%2BCid6ImkKZcjqkDaI1cq4THMK9m0B3E6zPuZESmHDHoV83nmVUftxPrWOqRxCQ4nRb4mZ2odMtf90H94zNSPyiYnDNE%2ByQMQTHjHlP37xJpKNYs86bfIiEXrAYx7iEZFCV5e1XZ3nPqNsHKZd4IEsJtI6Zpn4L6jdlnjZ2hO7wAjRYKTWVA2MJqYVlyFVuNl80t7EDNEDI0U4P6wcEqbOXNYEeIsU2moGOb0Is0f25cfjBp%2Boop%2BiHCPzSAdqX7WxCq1%2FqUe9DjBoIIEccolpWqloSf9Yk%2BUG17fgAMIT8xT%2Bh9RlV9XCKtWkpP2NtPmP7KB52ZYGet42jTgEdjR0B6EyMJjC6r0GOqUBW0R0obAlp3Gl9o%2FrqpaK3SqRzs1xNbJeS8WFCAi%2F9SliLauuTJEjpnNnycDcf61zp4sLQA8KP1AQS7%2Bhs8UsYsLcfQa7rQPf2bvYio2ChSFm9OssvUhl0RTpEg2wTu7bclf01EqIOo0vdHwRKS1Y05SCM%2F0JtBoLUGxVSPXKuBzZzr4VCTsu90OqQbSTxAiKUb7fFaC0jD%2F%2BEWTm2UueZMgJmrPf&X-Amz-Signature=d4a322e4f2ba2dcdf6291a44c39282094c69134e23830d218cda791f2604f07a&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665PBNNWGE%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T092355Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIAp3dZ%2Fs2ZypGJCwMJLUdekag8oshkaxlHmn%2F4KOE3wpAiEApVVLMcjAqinoc%2B%2FmzUpcTAFqMd8V3zoP0EviKYl%2FAP4qiAQI%2Ff%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDA5Ui44gnpHqSuwr3CrcAzGtP8nHzDdrGO%2FNIOAiXIhwCoRbBJclWrAcbTi3c4lAN3ur8V%2BBoSoLqTwEOXhiF%2F%2BSNU6%2FzdOmtpvYX5%2BsdmUKta1GWp9yteoSTF93wIximh9aQBj%2FtpY8Y%2BT2oIKcJu2ZOI%2BZajA1cf0kiLhCoSgHyIWRdDtZQH8WYQ5L0ZuuyEC3vjIgBeJ7%2BWmo4Kca2BErlGmLoQVmhfMFHznIBks5nzBXJZqso7%2B2z9kGtCJ12l%2FXhIA06BS4YBxkB2tW1Kp8BcsgrU09q%2Bsik68JNdyl7rJNibWKC7N%2BCid6ImkKZcjqkDaI1cq4THMK9m0B3E6zPuZESmHDHoV83nmVUftxPrWOqRxCQ4nRb4mZ2odMtf90H94zNSPyiYnDNE%2ByQMQTHjHlP37xJpKNYs86bfIiEXrAYx7iEZFCV5e1XZ3nPqNsHKZd4IEsJtI6Zpn4L6jdlnjZ2hO7wAjRYKTWVA2MJqYVlyFVuNl80t7EDNEDI0U4P6wcEqbOXNYEeIsU2moGOb0Is0f25cfjBp%2Boop%2BiHCPzSAdqX7WxCq1%2FqUe9DjBoIIEccolpWqloSf9Yk%2BUG17fgAMIT8xT%2Bh9RlV9XCKtWkpP2NtPmP7KB52ZYGet42jTgEdjR0B6EyMJjC6r0GOqUBW0R0obAlp3Gl9o%2FrqpaK3SqRzs1xNbJeS8WFCAi%2F9SliLauuTJEjpnNnycDcf61zp4sLQA8KP1AQS7%2Bhs8UsYsLcfQa7rQPf2bvYio2ChSFm9OssvUhl0RTpEg2wTu7bclf01EqIOo0vdHwRKS1Y05SCM%2F0JtBoLUGxVSPXKuBzZzr4VCTsu90OqQbSTxAiKUb7fFaC0jD%2F%2BEWTm2UueZMgJmrPf&X-Amz-Signature=8390c32969ca9f99e270e327c1ede1daf2066dcdf46782b9e88883a4fbac3e28&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665PBNNWGE%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T092355Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIAp3dZ%2Fs2ZypGJCwMJLUdekag8oshkaxlHmn%2F4KOE3wpAiEApVVLMcjAqinoc%2B%2FmzUpcTAFqMd8V3zoP0EviKYl%2FAP4qiAQI%2Ff%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDA5Ui44gnpHqSuwr3CrcAzGtP8nHzDdrGO%2FNIOAiXIhwCoRbBJclWrAcbTi3c4lAN3ur8V%2BBoSoLqTwEOXhiF%2F%2BSNU6%2FzdOmtpvYX5%2BsdmUKta1GWp9yteoSTF93wIximh9aQBj%2FtpY8Y%2BT2oIKcJu2ZOI%2BZajA1cf0kiLhCoSgHyIWRdDtZQH8WYQ5L0ZuuyEC3vjIgBeJ7%2BWmo4Kca2BErlGmLoQVmhfMFHznIBks5nzBXJZqso7%2B2z9kGtCJ12l%2FXhIA06BS4YBxkB2tW1Kp8BcsgrU09q%2Bsik68JNdyl7rJNibWKC7N%2BCid6ImkKZcjqkDaI1cq4THMK9m0B3E6zPuZESmHDHoV83nmVUftxPrWOqRxCQ4nRb4mZ2odMtf90H94zNSPyiYnDNE%2ByQMQTHjHlP37xJpKNYs86bfIiEXrAYx7iEZFCV5e1XZ3nPqNsHKZd4IEsJtI6Zpn4L6jdlnjZ2hO7wAjRYKTWVA2MJqYVlyFVuNl80t7EDNEDI0U4P6wcEqbOXNYEeIsU2moGOb0Is0f25cfjBp%2Boop%2BiHCPzSAdqX7WxCq1%2FqUe9DjBoIIEccolpWqloSf9Yk%2BUG17fgAMIT8xT%2Bh9RlV9XCKtWkpP2NtPmP7KB52ZYGet42jTgEdjR0B6EyMJjC6r0GOqUBW0R0obAlp3Gl9o%2FrqpaK3SqRzs1xNbJeS8WFCAi%2F9SliLauuTJEjpnNnycDcf61zp4sLQA8KP1AQS7%2Bhs8UsYsLcfQa7rQPf2bvYio2ChSFm9OssvUhl0RTpEg2wTu7bclf01EqIOo0vdHwRKS1Y05SCM%2F0JtBoLUGxVSPXKuBzZzr4VCTsu90OqQbSTxAiKUb7fFaC0jD%2F%2BEWTm2UueZMgJmrPf&X-Amz-Signature=208590862ae5a73e8cac5241eb5b4656e3f4673a9e7f9e174d04248758763884&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665PBNNWGE%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T092355Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIAp3dZ%2Fs2ZypGJCwMJLUdekag8oshkaxlHmn%2F4KOE3wpAiEApVVLMcjAqinoc%2B%2FmzUpcTAFqMd8V3zoP0EviKYl%2FAP4qiAQI%2Ff%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDA5Ui44gnpHqSuwr3CrcAzGtP8nHzDdrGO%2FNIOAiXIhwCoRbBJclWrAcbTi3c4lAN3ur8V%2BBoSoLqTwEOXhiF%2F%2BSNU6%2FzdOmtpvYX5%2BsdmUKta1GWp9yteoSTF93wIximh9aQBj%2FtpY8Y%2BT2oIKcJu2ZOI%2BZajA1cf0kiLhCoSgHyIWRdDtZQH8WYQ5L0ZuuyEC3vjIgBeJ7%2BWmo4Kca2BErlGmLoQVmhfMFHznIBks5nzBXJZqso7%2B2z9kGtCJ12l%2FXhIA06BS4YBxkB2tW1Kp8BcsgrU09q%2Bsik68JNdyl7rJNibWKC7N%2BCid6ImkKZcjqkDaI1cq4THMK9m0B3E6zPuZESmHDHoV83nmVUftxPrWOqRxCQ4nRb4mZ2odMtf90H94zNSPyiYnDNE%2ByQMQTHjHlP37xJpKNYs86bfIiEXrAYx7iEZFCV5e1XZ3nPqNsHKZd4IEsJtI6Zpn4L6jdlnjZ2hO7wAjRYKTWVA2MJqYVlyFVuNl80t7EDNEDI0U4P6wcEqbOXNYEeIsU2moGOb0Is0f25cfjBp%2Boop%2BiHCPzSAdqX7WxCq1%2FqUe9DjBoIIEccolpWqloSf9Yk%2BUG17fgAMIT8xT%2Bh9RlV9XCKtWkpP2NtPmP7KB52ZYGet42jTgEdjR0B6EyMJjC6r0GOqUBW0R0obAlp3Gl9o%2FrqpaK3SqRzs1xNbJeS8WFCAi%2F9SliLauuTJEjpnNnycDcf61zp4sLQA8KP1AQS7%2Bhs8UsYsLcfQa7rQPf2bvYio2ChSFm9OssvUhl0RTpEg2wTu7bclf01EqIOo0vdHwRKS1Y05SCM%2F0JtBoLUGxVSPXKuBzZzr4VCTsu90OqQbSTxAiKUb7fFaC0jD%2F%2BEWTm2UueZMgJmrPf&X-Amz-Signature=33b263e626f8e66a666638cb1678523bb085993abdceb8301891d0634db008a0&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UXTPATDC%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T092356Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAHDYkHs4Mvo5kCWjYNjzosNDM8ycbV7h7oHbnmk%2FStxAiBLBeyXd%2BnbUf0F7DRQDWhVCBDV9hkxwMhou6Dh9Y1%2BWCqIBAj9%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMXsm84Z4e0xC0NT58KtwDJYTNev%2FmdYuxCzVUtXXkMayoFmnhL9US1fzQuf58PaT%2FhlKB81tyYwfXm666IYiNJ9%2Bbh4LtTFfrMRE7CbpCLBAyXMdJZzxq8%2BrkdhSz8D4h%2FBMKUiJsPEt9boSMDWgpHmhrWd9vRF1tHdlPXRXypaTOSCDIOvze3TfEGAQoOBpikMVQRTR3qr8PyY2UtrSt%2BH1Ppm0OyaHXKqR%2FfsQz0mhDSvjGsqu5ZJpP%2FYQ4ZJNNo6sBeBBUfCgIgKJrc9ydUAgJpyg2NoqA9sGdazR%2BDlada%2BV4M6skO6mD3Rbcf0R%2B2Eq1w%2FPnnuBg2LOtnSQK3QjyAZjn4wLdflAGQswyTBP5bFMyYsx4JdBIM4PSHINK6t%2Br9RmUwzdj3SbmA3OhsX7iDHwYCQvfj5HAjDvavjo5PBxoLZpnYGaoMGGDkGsqxqJnqrjfvoN457CWkAiGKONSLvuRODDD9d21UL2hOjmATvS%2BJpN%2FOJM2RhIHl9ny%2BTIrsZaNN09YC%2F%2B49tk0oF5%2BjLOslqejGCsebAPxK1tYYQLb1I3a%2FfVi26ete5xoeRay0IRtfIiDrjYgw4ZBPtPbVAhVSwKFTt%2FBpJqlz0C9pWEO4uOvwchWhOyywQMa3RmtJSmVMtFpJwQw2rrqvQY6pgFjEHk1N7HMepFYMz7TgZzJ5Jq%2FhZfPyQonaWWbPFD0zwWGKk7%2FGuNFEcdMBYMrwmi0lw4RgDI2TX%2FfaLesZxXtAkjKovwF5eZdv%2B%2Fr7B4kP7wYcFj1pOYxHILoLNRfMvyL9exCrlnfzJjazOazi0BetUYbb7aFiVIZGKmtO7QGPlFJcgQmNB9x4gRZffvjD0foNLX07EG%2BMr8hB9rB%2BoFPBLHX0HGK&X-Amz-Signature=6fafa0951855abf2a2b33fe5431a5897857daa1c632e2c083e36a57b7788121d&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662W3PEEO4%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T092356Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIAynZ5b4hMVM33K1z2AedbQ8oAaCigbV%2BDj3WJKT%2Fm5oAiEAriy2YIE0iLBPCUTi9eGJjmZcLmQ0GMAefygfGnuTuLcqiAQI%2Fv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNzQQVN7kgVfao2lwircA0f58nCHSVJggUWYleDf%2F5mH3EekqDRDqXwDOBV9IZwmriDD5XR6BF1LnF6ufzHkJz21zK8xTXFqC4JtG%2B9zujIU8KwMXNhsxQNtNsXUOeTXcq2Eb2zSUmoLyvDbjot8lljIQKej9wjgonYQD2PWgoNyeeO3jCUoFpI5rZRTFUGunRcuPwywM%2B%2Bwm7rfUpfoV1iXyFSsEP%2BDDfLq58voJMYNuwN6mVtiqpWCytSm53IJDo%2Bwc0bWLAhKUZ%2BnaLjyMi%2Fg%2BXrry2HSH5zNFW4ELDIU4sTP4us0%2FZ9haB7wFFUKaPrqD7M5dIwLWoPytrDIqxqDyg%2Fmu%2FpA9vCR1sJnDojubbZxZn5WqmW4ssiPOTnT6VZ1UWuJEs0F25loD4dShfoYDbLuuZ6XJP1vfOUz7hONcMIXSkvyAgOjn1d3qm2GaHkOLNUKoX9xRXDv2eayKSHlmPH%2BWcFsJ%2BIh9EMVy5KRUkAcjtE2nYoqWCnn16v0BiwNVBSmaw%2BV%2BejvBZ95RdDZU0tHRqyn6qPJusyl1Lf4r3oeGShHieFTq%2BVZ7NBo5tDDKJ8rtQ7DDzxzVqlPjaPVk4VxgEcY%2F6FAhyP0NEZJMWaSjZbVvrf9n204UYyoV1iau6SbezVkf0AwMIHe6r0GOqUBkK1soI47YAo8Kkt9Cl6LQpAq%2BIzg5j4oX7HyFvMEf5DPR5C4AC9kcLLwm%2BV1fwXs6aI4Z%2B1IQfS2UmMpkNWEycWu4raftiA7ppm24xdni0SMVPzCGRz3rXxjOd0LTp4eFPqjOeUyIeQw28VmQtXimL%2BhozhRg35UMpxPWMm7U4nTROXi5QM25MmQpGSa4%2BM7oFEryK%2FzwhV804IldnEhfOjoAdqD&X-Amz-Signature=819d58d06100ceaa2d81ec8cc39728d04047e0dec52bba1fa0d7029833a31e87&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665PBNNWGE%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T092355Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIAp3dZ%2Fs2ZypGJCwMJLUdekag8oshkaxlHmn%2F4KOE3wpAiEApVVLMcjAqinoc%2B%2FmzUpcTAFqMd8V3zoP0EviKYl%2FAP4qiAQI%2Ff%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDA5Ui44gnpHqSuwr3CrcAzGtP8nHzDdrGO%2FNIOAiXIhwCoRbBJclWrAcbTi3c4lAN3ur8V%2BBoSoLqTwEOXhiF%2F%2BSNU6%2FzdOmtpvYX5%2BsdmUKta1GWp9yteoSTF93wIximh9aQBj%2FtpY8Y%2BT2oIKcJu2ZOI%2BZajA1cf0kiLhCoSgHyIWRdDtZQH8WYQ5L0ZuuyEC3vjIgBeJ7%2BWmo4Kca2BErlGmLoQVmhfMFHznIBks5nzBXJZqso7%2B2z9kGtCJ12l%2FXhIA06BS4YBxkB2tW1Kp8BcsgrU09q%2Bsik68JNdyl7rJNibWKC7N%2BCid6ImkKZcjqkDaI1cq4THMK9m0B3E6zPuZESmHDHoV83nmVUftxPrWOqRxCQ4nRb4mZ2odMtf90H94zNSPyiYnDNE%2ByQMQTHjHlP37xJpKNYs86bfIiEXrAYx7iEZFCV5e1XZ3nPqNsHKZd4IEsJtI6Zpn4L6jdlnjZ2hO7wAjRYKTWVA2MJqYVlyFVuNl80t7EDNEDI0U4P6wcEqbOXNYEeIsU2moGOb0Is0f25cfjBp%2Boop%2BiHCPzSAdqX7WxCq1%2FqUe9DjBoIIEccolpWqloSf9Yk%2BUG17fgAMIT8xT%2Bh9RlV9XCKtWkpP2NtPmP7KB52ZYGet42jTgEdjR0B6EyMJjC6r0GOqUBW0R0obAlp3Gl9o%2FrqpaK3SqRzs1xNbJeS8WFCAi%2F9SliLauuTJEjpnNnycDcf61zp4sLQA8KP1AQS7%2Bhs8UsYsLcfQa7rQPf2bvYio2ChSFm9OssvUhl0RTpEg2wTu7bclf01EqIOo0vdHwRKS1Y05SCM%2F0JtBoLUGxVSPXKuBzZzr4VCTsu90OqQbSTxAiKUb7fFaC0jD%2F%2BEWTm2UueZMgJmrPf&X-Amz-Signature=847dc0fb61c7edcf045c37fea99579147e300660f5156056d0b814506565ce52&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665PBNNWGE%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T092355Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIAp3dZ%2Fs2ZypGJCwMJLUdekag8oshkaxlHmn%2F4KOE3wpAiEApVVLMcjAqinoc%2B%2FmzUpcTAFqMd8V3zoP0EviKYl%2FAP4qiAQI%2Ff%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDA5Ui44gnpHqSuwr3CrcAzGtP8nHzDdrGO%2FNIOAiXIhwCoRbBJclWrAcbTi3c4lAN3ur8V%2BBoSoLqTwEOXhiF%2F%2BSNU6%2FzdOmtpvYX5%2BsdmUKta1GWp9yteoSTF93wIximh9aQBj%2FtpY8Y%2BT2oIKcJu2ZOI%2BZajA1cf0kiLhCoSgHyIWRdDtZQH8WYQ5L0ZuuyEC3vjIgBeJ7%2BWmo4Kca2BErlGmLoQVmhfMFHznIBks5nzBXJZqso7%2B2z9kGtCJ12l%2FXhIA06BS4YBxkB2tW1Kp8BcsgrU09q%2Bsik68JNdyl7rJNibWKC7N%2BCid6ImkKZcjqkDaI1cq4THMK9m0B3E6zPuZESmHDHoV83nmVUftxPrWOqRxCQ4nRb4mZ2odMtf90H94zNSPyiYnDNE%2ByQMQTHjHlP37xJpKNYs86bfIiEXrAYx7iEZFCV5e1XZ3nPqNsHKZd4IEsJtI6Zpn4L6jdlnjZ2hO7wAjRYKTWVA2MJqYVlyFVuNl80t7EDNEDI0U4P6wcEqbOXNYEeIsU2moGOb0Is0f25cfjBp%2Boop%2BiHCPzSAdqX7WxCq1%2FqUe9DjBoIIEccolpWqloSf9Yk%2BUG17fgAMIT8xT%2Bh9RlV9XCKtWkpP2NtPmP7KB52ZYGet42jTgEdjR0B6EyMJjC6r0GOqUBW0R0obAlp3Gl9o%2FrqpaK3SqRzs1xNbJeS8WFCAi%2F9SliLauuTJEjpnNnycDcf61zp4sLQA8KP1AQS7%2Bhs8UsYsLcfQa7rQPf2bvYio2ChSFm9OssvUhl0RTpEg2wTu7bclf01EqIOo0vdHwRKS1Y05SCM%2F0JtBoLUGxVSPXKuBzZzr4VCTsu90OqQbSTxAiKUb7fFaC0jD%2F%2BEWTm2UueZMgJmrPf&X-Amz-Signature=33953906d69c5230013129c176d508258d7c3d7fa8ac288dea7e63a7ac255f38&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665PBNNWGE%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T092355Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIAp3dZ%2Fs2ZypGJCwMJLUdekag8oshkaxlHmn%2F4KOE3wpAiEApVVLMcjAqinoc%2B%2FmzUpcTAFqMd8V3zoP0EviKYl%2FAP4qiAQI%2Ff%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDA5Ui44gnpHqSuwr3CrcAzGtP8nHzDdrGO%2FNIOAiXIhwCoRbBJclWrAcbTi3c4lAN3ur8V%2BBoSoLqTwEOXhiF%2F%2BSNU6%2FzdOmtpvYX5%2BsdmUKta1GWp9yteoSTF93wIximh9aQBj%2FtpY8Y%2BT2oIKcJu2ZOI%2BZajA1cf0kiLhCoSgHyIWRdDtZQH8WYQ5L0ZuuyEC3vjIgBeJ7%2BWmo4Kca2BErlGmLoQVmhfMFHznIBks5nzBXJZqso7%2B2z9kGtCJ12l%2FXhIA06BS4YBxkB2tW1Kp8BcsgrU09q%2Bsik68JNdyl7rJNibWKC7N%2BCid6ImkKZcjqkDaI1cq4THMK9m0B3E6zPuZESmHDHoV83nmVUftxPrWOqRxCQ4nRb4mZ2odMtf90H94zNSPyiYnDNE%2ByQMQTHjHlP37xJpKNYs86bfIiEXrAYx7iEZFCV5e1XZ3nPqNsHKZd4IEsJtI6Zpn4L6jdlnjZ2hO7wAjRYKTWVA2MJqYVlyFVuNl80t7EDNEDI0U4P6wcEqbOXNYEeIsU2moGOb0Is0f25cfjBp%2Boop%2BiHCPzSAdqX7WxCq1%2FqUe9DjBoIIEccolpWqloSf9Yk%2BUG17fgAMIT8xT%2Bh9RlV9XCKtWkpP2NtPmP7KB52ZYGet42jTgEdjR0B6EyMJjC6r0GOqUBW0R0obAlp3Gl9o%2FrqpaK3SqRzs1xNbJeS8WFCAi%2F9SliLauuTJEjpnNnycDcf61zp4sLQA8KP1AQS7%2Bhs8UsYsLcfQa7rQPf2bvYio2ChSFm9OssvUhl0RTpEg2wTu7bclf01EqIOo0vdHwRKS1Y05SCM%2F0JtBoLUGxVSPXKuBzZzr4VCTsu90OqQbSTxAiKUb7fFaC0jD%2F%2BEWTm2UueZMgJmrPf&X-Amz-Signature=285e2976b13059d9d4d84769761059226a0b8ecf8ceb15f16134b4ed1819e2df&X-Amz-SignedHeaders=host&x-id=GetObject)


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

