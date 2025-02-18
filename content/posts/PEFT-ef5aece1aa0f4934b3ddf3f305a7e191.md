---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466UF5ZZ5JS%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250218T111957Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEGMaCXVzLXdlc3QtMiJHMEUCIQCm6LpP0vOVaOGf9A5DLhfVS3JRdKmr9PMRDfKDfKFuuwIgUpC\
  hhPE0Gy3OFYGW47%2FSQXrMCn8JGKvzLNv%2Br%2BTsOa0qiAQIjP%2F%2F%2F%2F%2F%2F%2F%2F\
  %2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPJpmjywM9CBrKGfpSrcA8foa9cpPXNP2Y7nHXArcXDwut2\
  pdS7pnsIIc%2BdT8OP2pLYm9fTx2AfQikHZq%2FFrsfKC8P2MlA3Z9hIyI7uXPGTNKQ0n5zoTsu6I\
  3mMdvIuUoLpnt%2BlqU1h7pdYAyTQmWy1M5Z0SlnhTAotPzxiQP9T7ZmhVqsibFMcHnQ6ppng35AK\
  aFZJ0NlmmUA5VNnEBFG7E43KE6LcP7L7JktW5jNcfUi6z9jROtlcGufShvb0adnHlaXNW%2BptQsh\
  c1gS6PlDjjbIomlFSFvnxuTxyxwfcH1abQo%2FxbbAFiQJ5SgZacBrDB3zz2sZ1D%2FXLP9DrC14I\
  DS%2FiF1RPw%2FbREjlru35gzXvByII%2BEVb45J%2F9K6swtkSJ0pyoeuq2YSIDQLbqamHtOxmWG\
  WfMpqmVn%2FZuu%2FZIu6Sa0CfmUZeCesqCGXfQvW8K%2BUTnOgcIg1hOy%2BisYmuZ4yP0n94OFw\
  SbiNQcAaS9XsLRDPzQkaLZ73NyCobRpeFbxOKRCEfTUW0ncLw76%2Bt9GJOyOjyNZ%2BIwDkVvSly\
  TsGmHppEp9sibQfCCdGncdGJu09GlvTvE%2B5WwCECvdiv%2Fc%2BGyMRpJBjpwUzzXlZUqpONM%2\
  BMiGyE1yI5TqNWDKqFI%2FVkozu4KbdVI8iMOzV0b0GOqUBzUEcVCH3w2Yct0q0gcmnjouGiJ7LvC\
  fFhoPD2ZzNvV6vKz9IrmjVs1LAU1HFONiwtj9fLs8xHTEAsS%2BJKDHA%2Brivvdw5JDFkpkL%2F3\
  4RckRYxuGtsFmWcaGqoQ%2BNtiBj7FzT0d2CfLG7%2FOHoSglNRScAt2P2JSLxo2u%2FiCq4Ofs91\
  IQFsfb2LyTGydyLOCM0W6UnOpU3M1jAgxxbbjQxpNmJpspRh&X-Amz-Signature=a3108c0c14de\
  d4e6ca1d035d91f943483ec64136614d6b9ec0ab453c449ec293&X-Amz-SignedHeaders=host\
  &x-id=GetObject"
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
        redential=ASIAZI2LB4666D562SPV%2F20250218%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250218T111832Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEGMaCXVzLXdlc3QtMiJIMEYCIQDrx6DReHFbXxkNOBfsCHruwUuKnTx\
        ipB%2F0bDU1hrsjcAIhALdf5mN%2BXl8r9DYn5NynsHYAKsJ%2F7%2B%2BAsNBnIyX1%2Bj\
        bLKogECIv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzR7FyHN\
        LjTaKoyybcq3ANE%2FEzyY4VEEbdWOMTMSBBlRGI%2BUkpo0ZB11tJzv89sr2jGMKoIi0xM\
        TkqrUwbNRKzBVYD%2B9yO5inHHPxgVTfZn3PqtLwkETCOQQZ9SJhUlVPw4HSPJexlPvwdcd\
        PP4rtiHRTrm%2B202rZPnbDTLzFPd11Ua57KhsOhx5Ejoov9mwHa12qVhMH51TUR%2FKzQZ\
        bSarq1vB%2BRmYkslTrdoa2gtmvwle%2F%2FgEOTzkExVmdyHhO%2FqPF6vkvo81VgWur2w\
        9pUYmxBkK7X2ByG7sT%2F0IMK4H1cubE1HlzAYQIEEmpnLDdxvIGdpyw40NMWJxW%2FXV99\
        RObasPgWeDBgWUBErMRUDxOl7Ck4PDhcsGW5nAmNWHQcbo9H8mSgY0LJ9FavnuH4shAKKps\
        p4g7xA4V39pbXu08HB3Blx%2FpVjTVxJc4ymuCVEgTG%2F5rZ6d0X6YdIuHa0%2BRBkYA2M\
        R9%2FhhuBNEF5R1RumHna4Pcy%2BSeHB1qEqa%2BPH0HhhXd%2BEUSBChPcWOvkvYpwTwGv\
        xNXkAP5bB5mAUtDpyiz5z7QLSO3xyEaeRkxZZGRmmuJVuUNuqVPdmDPbFgSSjt5jeOqIq%2\
        B283eHF034BLXnZjV%2FeNoV5dRo8eqsUlibsCHVmaVBm9fzfDDav9G9BjqkAYBikCy9Wdc\
        nwsEKUiFN9xgqyJ18vSe%2BDlJAMkhrE4QZft%2BKXALD7e747sqE2a2vqYsfkSG6brgPxA\
        j7tdDOKhkenhJJl1%2FwLI1xLTem%2BnhvsVmjqR3drKjX2RsowD083bkt%2FsblwHiJzRL\
        KWgvBYjYgSCpeUGwUEL0Nq3IIapTGg0rWt%2BchpTvBIRa1OPVrglHbzbIynzKPQ6cqOSZJ\
        wDQVzSj%2B&X-Amz-Signature=7136e7a6dc090c5947ff9815bc963c93b61ba15985db\
        f9b69be504ffe89cf416&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-18T12:18:32.607Z"
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
UPDATE_TIME: "2025-02-18T11:20:03.132Z"
EXPIRY_TIME: "2025-02-18T12:19:53.373Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666TMCBBTE%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T111953Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGMaCXVzLXdlc3QtMiJGMEQCIAE8Amw6nG5%2FZLRYTVbXnCHbyGR0bTNrCrGY2hHyNtcwAiAzR3hjj8raa5vrRjiKpPQV4mwEOM8RCGDknIT0cv6cpiqIBAiM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMIQgfQ8UTekgnMCBiKtwDgztwMhmdyI7Ziqo6nemXrXoCIc5S1xhleAmIg7F6y26Stju253kC3QtfoaIfPWigHai%2FlDlWqst5TY1rx6BI4uNb%2F16AHoScuLefJwAMqid16RIL824O02OZY3zfez%2BQ3Mox0L5e3QHG3ULfn27tLirEj%2BteDI295XklXIstwStDbOidSqUWF9mXJ4Fbk9WQOh0aZNHc%2BDkE87zIywreVoVhlm1azIfpZdAQ%2FAxbGx8pMWG2IhSjyp0ui7LzGVvxlKK1fpRPg6Yb5P16XMHQ4U1UY9zyDRie0lkCtho3WNqPfdvPKxtiSsvhr3CBOINft%2B12wLqceuEOY9wKJ2AH9TUf8zwyAB9%2B4LAM9r8OyQguqbc9RUotWKWEkYP8hDUoBPNZ6pqSa7mYFCTptqmR52gPxwoemFrtwnA5DRPm%2FQ42iD96SSr%2BJGv8NCxe4syKSM90i%2BMqYYw%2BBZqq9vOGw%2FjVlpp0U2R5F%2B%2FYSQIIBXJTIqvIthrLYp0qaHNCpYmlF%2Bdmh8dyDTDunjN2F4TT3ajkETNcoklYqvT22LMcaaiugHGIFGnlt3kDYDHPfpcgLEf2X5VXwQ%2Bm9Gyl6nDmS3QxA4dUX2qkKtymPFHe1T%2BUJr9lHgwiKJo6Dj4wr7%2FRvQY6pgFjx32Nc295%2BO4MXBgP3fXan%2FyYt6BmcteMuzpv%2FqCEQeRB2fbUHFVO%2BKsZhOb7aWvLsDubeEq63yC3Xl0i1O6iHzKMinH5VSh3HVgWoJ2u%2FEevVoTeXLpZSKaZ47eGx5dzl%2F9D9Mf3nqZftRbh%2F7gVzb%2FQGpg2yFGA0S%2Bw8xYnNpPDasFahDtC8EEnPbWVSHTukFQDfkoE6DznhrY4c6lVZZBoAIi1&X-Amz-Signature=6b7a36b80a5cb5afe48400f94370c28dca60991cc811b68d49723cf178905308&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666TMCBBTE%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T111953Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGMaCXVzLXdlc3QtMiJGMEQCIAE8Amw6nG5%2FZLRYTVbXnCHbyGR0bTNrCrGY2hHyNtcwAiAzR3hjj8raa5vrRjiKpPQV4mwEOM8RCGDknIT0cv6cpiqIBAiM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMIQgfQ8UTekgnMCBiKtwDgztwMhmdyI7Ziqo6nemXrXoCIc5S1xhleAmIg7F6y26Stju253kC3QtfoaIfPWigHai%2FlDlWqst5TY1rx6BI4uNb%2F16AHoScuLefJwAMqid16RIL824O02OZY3zfez%2BQ3Mox0L5e3QHG3ULfn27tLirEj%2BteDI295XklXIstwStDbOidSqUWF9mXJ4Fbk9WQOh0aZNHc%2BDkE87zIywreVoVhlm1azIfpZdAQ%2FAxbGx8pMWG2IhSjyp0ui7LzGVvxlKK1fpRPg6Yb5P16XMHQ4U1UY9zyDRie0lkCtho3WNqPfdvPKxtiSsvhr3CBOINft%2B12wLqceuEOY9wKJ2AH9TUf8zwyAB9%2B4LAM9r8OyQguqbc9RUotWKWEkYP8hDUoBPNZ6pqSa7mYFCTptqmR52gPxwoemFrtwnA5DRPm%2FQ42iD96SSr%2BJGv8NCxe4syKSM90i%2BMqYYw%2BBZqq9vOGw%2FjVlpp0U2R5F%2B%2FYSQIIBXJTIqvIthrLYp0qaHNCpYmlF%2Bdmh8dyDTDunjN2F4TT3ajkETNcoklYqvT22LMcaaiugHGIFGnlt3kDYDHPfpcgLEf2X5VXwQ%2Bm9Gyl6nDmS3QxA4dUX2qkKtymPFHe1T%2BUJr9lHgwiKJo6Dj4wr7%2FRvQY6pgFjx32Nc295%2BO4MXBgP3fXan%2FyYt6BmcteMuzpv%2FqCEQeRB2fbUHFVO%2BKsZhOb7aWvLsDubeEq63yC3Xl0i1O6iHzKMinH5VSh3HVgWoJ2u%2FEevVoTeXLpZSKaZ47eGx5dzl%2F9D9Mf3nqZftRbh%2F7gVzb%2FQGpg2yFGA0S%2Bw8xYnNpPDasFahDtC8EEnPbWVSHTukFQDfkoE6DznhrY4c6lVZZBoAIi1&X-Amz-Signature=eb76b454f831ca920bbd3f80e502a920b9f187471c0f1662215e501f61c28724&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666TMCBBTE%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T111953Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGMaCXVzLXdlc3QtMiJGMEQCIAE8Amw6nG5%2FZLRYTVbXnCHbyGR0bTNrCrGY2hHyNtcwAiAzR3hjj8raa5vrRjiKpPQV4mwEOM8RCGDknIT0cv6cpiqIBAiM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMIQgfQ8UTekgnMCBiKtwDgztwMhmdyI7Ziqo6nemXrXoCIc5S1xhleAmIg7F6y26Stju253kC3QtfoaIfPWigHai%2FlDlWqst5TY1rx6BI4uNb%2F16AHoScuLefJwAMqid16RIL824O02OZY3zfez%2BQ3Mox0L5e3QHG3ULfn27tLirEj%2BteDI295XklXIstwStDbOidSqUWF9mXJ4Fbk9WQOh0aZNHc%2BDkE87zIywreVoVhlm1azIfpZdAQ%2FAxbGx8pMWG2IhSjyp0ui7LzGVvxlKK1fpRPg6Yb5P16XMHQ4U1UY9zyDRie0lkCtho3WNqPfdvPKxtiSsvhr3CBOINft%2B12wLqceuEOY9wKJ2AH9TUf8zwyAB9%2B4LAM9r8OyQguqbc9RUotWKWEkYP8hDUoBPNZ6pqSa7mYFCTptqmR52gPxwoemFrtwnA5DRPm%2FQ42iD96SSr%2BJGv8NCxe4syKSM90i%2BMqYYw%2BBZqq9vOGw%2FjVlpp0U2R5F%2B%2FYSQIIBXJTIqvIthrLYp0qaHNCpYmlF%2Bdmh8dyDTDunjN2F4TT3ajkETNcoklYqvT22LMcaaiugHGIFGnlt3kDYDHPfpcgLEf2X5VXwQ%2Bm9Gyl6nDmS3QxA4dUX2qkKtymPFHe1T%2BUJr9lHgwiKJo6Dj4wr7%2FRvQY6pgFjx32Nc295%2BO4MXBgP3fXan%2FyYt6BmcteMuzpv%2FqCEQeRB2fbUHFVO%2BKsZhOb7aWvLsDubeEq63yC3Xl0i1O6iHzKMinH5VSh3HVgWoJ2u%2FEevVoTeXLpZSKaZ47eGx5dzl%2F9D9Mf3nqZftRbh%2F7gVzb%2FQGpg2yFGA0S%2Bw8xYnNpPDasFahDtC8EEnPbWVSHTukFQDfkoE6DznhrY4c6lVZZBoAIi1&X-Amz-Signature=f46682790ce07bf6d6d1e29dcc814bb4ebd89e85ef2b27872e73adbc202b3d8c&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666TMCBBTE%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T111953Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGMaCXVzLXdlc3QtMiJGMEQCIAE8Amw6nG5%2FZLRYTVbXnCHbyGR0bTNrCrGY2hHyNtcwAiAzR3hjj8raa5vrRjiKpPQV4mwEOM8RCGDknIT0cv6cpiqIBAiM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMIQgfQ8UTekgnMCBiKtwDgztwMhmdyI7Ziqo6nemXrXoCIc5S1xhleAmIg7F6y26Stju253kC3QtfoaIfPWigHai%2FlDlWqst5TY1rx6BI4uNb%2F16AHoScuLefJwAMqid16RIL824O02OZY3zfez%2BQ3Mox0L5e3QHG3ULfn27tLirEj%2BteDI295XklXIstwStDbOidSqUWF9mXJ4Fbk9WQOh0aZNHc%2BDkE87zIywreVoVhlm1azIfpZdAQ%2FAxbGx8pMWG2IhSjyp0ui7LzGVvxlKK1fpRPg6Yb5P16XMHQ4U1UY9zyDRie0lkCtho3WNqPfdvPKxtiSsvhr3CBOINft%2B12wLqceuEOY9wKJ2AH9TUf8zwyAB9%2B4LAM9r8OyQguqbc9RUotWKWEkYP8hDUoBPNZ6pqSa7mYFCTptqmR52gPxwoemFrtwnA5DRPm%2FQ42iD96SSr%2BJGv8NCxe4syKSM90i%2BMqYYw%2BBZqq9vOGw%2FjVlpp0U2R5F%2B%2FYSQIIBXJTIqvIthrLYp0qaHNCpYmlF%2Bdmh8dyDTDunjN2F4TT3ajkETNcoklYqvT22LMcaaiugHGIFGnlt3kDYDHPfpcgLEf2X5VXwQ%2Bm9Gyl6nDmS3QxA4dUX2qkKtymPFHe1T%2BUJr9lHgwiKJo6Dj4wr7%2FRvQY6pgFjx32Nc295%2BO4MXBgP3fXan%2FyYt6BmcteMuzpv%2FqCEQeRB2fbUHFVO%2BKsZhOb7aWvLsDubeEq63yC3Xl0i1O6iHzKMinH5VSh3HVgWoJ2u%2FEevVoTeXLpZSKaZ47eGx5dzl%2F9D9Mf3nqZftRbh%2F7gVzb%2FQGpg2yFGA0S%2Bw8xYnNpPDasFahDtC8EEnPbWVSHTukFQDfkoE6DznhrY4c6lVZZBoAIi1&X-Amz-Signature=fb90b70c0b8f3c6651efe07ae5ea35f1877d2667aa21c74c960153ba250ea05b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666TMCBBTE%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T111953Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGMaCXVzLXdlc3QtMiJGMEQCIAE8Amw6nG5%2FZLRYTVbXnCHbyGR0bTNrCrGY2hHyNtcwAiAzR3hjj8raa5vrRjiKpPQV4mwEOM8RCGDknIT0cv6cpiqIBAiM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMIQgfQ8UTekgnMCBiKtwDgztwMhmdyI7Ziqo6nemXrXoCIc5S1xhleAmIg7F6y26Stju253kC3QtfoaIfPWigHai%2FlDlWqst5TY1rx6BI4uNb%2F16AHoScuLefJwAMqid16RIL824O02OZY3zfez%2BQ3Mox0L5e3QHG3ULfn27tLirEj%2BteDI295XklXIstwStDbOidSqUWF9mXJ4Fbk9WQOh0aZNHc%2BDkE87zIywreVoVhlm1azIfpZdAQ%2FAxbGx8pMWG2IhSjyp0ui7LzGVvxlKK1fpRPg6Yb5P16XMHQ4U1UY9zyDRie0lkCtho3WNqPfdvPKxtiSsvhr3CBOINft%2B12wLqceuEOY9wKJ2AH9TUf8zwyAB9%2B4LAM9r8OyQguqbc9RUotWKWEkYP8hDUoBPNZ6pqSa7mYFCTptqmR52gPxwoemFrtwnA5DRPm%2FQ42iD96SSr%2BJGv8NCxe4syKSM90i%2BMqYYw%2BBZqq9vOGw%2FjVlpp0U2R5F%2B%2FYSQIIBXJTIqvIthrLYp0qaHNCpYmlF%2Bdmh8dyDTDunjN2F4TT3ajkETNcoklYqvT22LMcaaiugHGIFGnlt3kDYDHPfpcgLEf2X5VXwQ%2Bm9Gyl6nDmS3QxA4dUX2qkKtymPFHe1T%2BUJr9lHgwiKJo6Dj4wr7%2FRvQY6pgFjx32Nc295%2BO4MXBgP3fXan%2FyYt6BmcteMuzpv%2FqCEQeRB2fbUHFVO%2BKsZhOb7aWvLsDubeEq63yC3Xl0i1O6iHzKMinH5VSh3HVgWoJ2u%2FEevVoTeXLpZSKaZ47eGx5dzl%2F9D9Mf3nqZftRbh%2F7gVzb%2FQGpg2yFGA0S%2Bw8xYnNpPDasFahDtC8EEnPbWVSHTukFQDfkoE6DznhrY4c6lVZZBoAIi1&X-Amz-Signature=4018c11168c5f180c61abb2e13433e85f9e861016f86ee294cd2e0a12d185685&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Y2LLWFLB%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T111955Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGMaCXVzLXdlc3QtMiJGMEQCIDndXN3prYaTZTG3yG8rfitW6JJEzsO%2FAB07%2FCcczT97AiAIF819ilvUlTY2gtAkwupBsrlsx6yZs%2F7D38wegMO22iqIBAiM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMcrww7fnmNzeVumTgKtwDKkV7gxEBk6FWGDeJ2yVjK0xjn8kRAagMLrZATnPG8MUivflGyU%2FA6Dbe3ba8fTQELQfTsN4EAtadNhi50FC1njmD8ipBZXL4C5fQd%2FZlUob3QJNKWJP8Y8tpR5UQL6ifmmhZRgctgXTO2klOFbHMwdP2Z2%2FMw%2FljZ1WPQK1L6Uk2lGajj0G4VtoqZaX5%2Fm%2FXJizpwWziz4f36p4O8%2F3LGaR4f7V%2FAuLJRnvERoYyqKfRoUqvff%2FINmWSLtb2ozUNogdZZJfhIBpSC%2FOyjrDx5Za7xkCA%2BUftfNb6suTpa8mp%2FS48yVBzv%2Frr5wXLMhbneLoJGmX6Bsk3nAleOT1XGXX5FMMcvPgjUK30zoQ0GInUvAhdnK5p2Po8soHxN3a1l1Y3QLNQ%2F4ma9C3iim7S1Y0UyZB6ojF%2F6L7riRz4oCUx9iF0tjsmnkqY3fA7LbuGrT15kuHRqbKEjK1WLSz2EuIllFjANcUM5YJw6HXvKbLIq3ZxXcGVItxJeswiy065m6%2FyLUCbj99wsbHIiFoIjlCJCnJf9%2BrDTBBVxDB3aFjCo57GrwI97zRNqbptb%2FNw6AHcQ4nAYvnvsdNsHPCm03ihiugfhkQt4aHqBXY8fZAu7Hce91%2FP3elulhwwr7%2FRvQY6pgFDhrA3FvUinE7RfTYjdUXvz89Oryv1oSIcelvZ8ZI%2BoaqDh2U%2FmIgREPL3KT960CFnxLbkOrfVHVGDRRLFaMFGjQ4lQWJy%2B5aS01CU1bYqgqL9QHoNw2cmtnuhZa7SANMbCmubBQmzly7lOwIVFE2z%2FRGyr%2BmoV%2FGK71GCoQIx1%2BU9fIi4ZDVUZmTtAMjuXbDmcqZj8QtdTVSMesqzhu5FlToBD1Au&X-Amz-Signature=879cfde92066f0b94cbd5f26de121a6f023b1598674372a743ca6628a9dc0300&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665IWNYMZP%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T111956Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGMaCXVzLXdlc3QtMiJGMEQCIHEmlJt2CYT6u2uSBXHeHalr4SJGBLZmOtVzbvY2491cAiAoprtDXn6okvv8BgBCJKHhKnI7UW08HKa9ODkNcwu%2BeSqIBAiL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM8DMlYrQBJ1UOFRIwKtwDFyvu5h0V%2B0ArP6qeNDkBuVqIYYwh8MyUgIfjqenhBejvIBptvgbo0Q4pOn0uR54hGUBPxrn0pwIixMwrkoHy9GVytGN8Q7%2F5HmISySBwN20SP6shabLrgAo5axZkyfPy9VHH8LIE2m6o0NTHnEAQ%2BXBjimWMy44vPTMxsdKCXvZ2VIb7%2B4MyQU6gdbse1xKyJ2zqNx6rOcE61j1WSfsEvAek803IyK4vXlnIpr0iDN2SmcDt475YNu%2BWfohU1kdJ52BefT%2FULK7HkT34LtDQ%2Bqx%2FAIkulhfE2rle%2Fpv5JMIWjp%2BFawaCmNpseiCr1hthBacz2bErRXs89H8bnhimgEHU8n%2Fvzakqb2p3tneHMBXTzXfcWwc9uW%2BeRhcGrUjNqDCt%2BcaGurSEn8Xw7pLstayGEMZ07PNgExAXxUbyZijPMSYkqY2YJCmY0j4Zd7pHQNUP8LvG5Wk0jZTUY2m0xoVqcgxXgtfgk0QwD08mIEBu84JiSmencMAd44i2PM4GEty%2Bk2cbSTfAUFT0G9o0jsSywnCesvoAuEY0eBq45RKKlwG8xi160RZ4SnCUkA%2FN2s83lxO%2FJw2rVmFxArCEDZ16yBN%2FoVi7nJlLPTKEBLX%2FIe1TijJvW32ITZ0w%2B77RvQY6pgFg7Gk2YElT7IS1O03%2B59E8928e8PNUacWUoC2epCnqvmgL9yxKsT2YB%2FJC%2FOoWSK1%2Bif%2FVEhQng5cUvrsiKiJ50Q74VCvVL%2BgftFq%2F1Q%2FzdrpGZWJfDGY4BhAsikMx52NWBjnXYurTQr0o4MBVaay%2BQX%2B4f%2FqsZnbeURk1TEnSiDRxdflRsRXlLXq%2FEofuOyqV%2BS%2FcElXI3%2BzUAE3j971yxJ%2FUzCqg&X-Amz-Signature=b4fca78763c52b74842be8e5caf0574c27551444e3fae3a1106e2a10bb7278ad&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666TMCBBTE%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T111953Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGMaCXVzLXdlc3QtMiJGMEQCIAE8Amw6nG5%2FZLRYTVbXnCHbyGR0bTNrCrGY2hHyNtcwAiAzR3hjj8raa5vrRjiKpPQV4mwEOM8RCGDknIT0cv6cpiqIBAiM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMIQgfQ8UTekgnMCBiKtwDgztwMhmdyI7Ziqo6nemXrXoCIc5S1xhleAmIg7F6y26Stju253kC3QtfoaIfPWigHai%2FlDlWqst5TY1rx6BI4uNb%2F16AHoScuLefJwAMqid16RIL824O02OZY3zfez%2BQ3Mox0L5e3QHG3ULfn27tLirEj%2BteDI295XklXIstwStDbOidSqUWF9mXJ4Fbk9WQOh0aZNHc%2BDkE87zIywreVoVhlm1azIfpZdAQ%2FAxbGx8pMWG2IhSjyp0ui7LzGVvxlKK1fpRPg6Yb5P16XMHQ4U1UY9zyDRie0lkCtho3WNqPfdvPKxtiSsvhr3CBOINft%2B12wLqceuEOY9wKJ2AH9TUf8zwyAB9%2B4LAM9r8OyQguqbc9RUotWKWEkYP8hDUoBPNZ6pqSa7mYFCTptqmR52gPxwoemFrtwnA5DRPm%2FQ42iD96SSr%2BJGv8NCxe4syKSM90i%2BMqYYw%2BBZqq9vOGw%2FjVlpp0U2R5F%2B%2FYSQIIBXJTIqvIthrLYp0qaHNCpYmlF%2Bdmh8dyDTDunjN2F4TT3ajkETNcoklYqvT22LMcaaiugHGIFGnlt3kDYDHPfpcgLEf2X5VXwQ%2Bm9Gyl6nDmS3QxA4dUX2qkKtymPFHe1T%2BUJr9lHgwiKJo6Dj4wr7%2FRvQY6pgFjx32Nc295%2BO4MXBgP3fXan%2FyYt6BmcteMuzpv%2FqCEQeRB2fbUHFVO%2BKsZhOb7aWvLsDubeEq63yC3Xl0i1O6iHzKMinH5VSh3HVgWoJ2u%2FEevVoTeXLpZSKaZ47eGx5dzl%2F9D9Mf3nqZftRbh%2F7gVzb%2FQGpg2yFGA0S%2Bw8xYnNpPDasFahDtC8EEnPbWVSHTukFQDfkoE6DznhrY4c6lVZZBoAIi1&X-Amz-Signature=36aa7d5a3e7745165f269dbc8fc90f60c339371ca67affedc9d6257ecfe4338d&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666TMCBBTE%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T111953Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGMaCXVzLXdlc3QtMiJGMEQCIAE8Amw6nG5%2FZLRYTVbXnCHbyGR0bTNrCrGY2hHyNtcwAiAzR3hjj8raa5vrRjiKpPQV4mwEOM8RCGDknIT0cv6cpiqIBAiM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMIQgfQ8UTekgnMCBiKtwDgztwMhmdyI7Ziqo6nemXrXoCIc5S1xhleAmIg7F6y26Stju253kC3QtfoaIfPWigHai%2FlDlWqst5TY1rx6BI4uNb%2F16AHoScuLefJwAMqid16RIL824O02OZY3zfez%2BQ3Mox0L5e3QHG3ULfn27tLirEj%2BteDI295XklXIstwStDbOidSqUWF9mXJ4Fbk9WQOh0aZNHc%2BDkE87zIywreVoVhlm1azIfpZdAQ%2FAxbGx8pMWG2IhSjyp0ui7LzGVvxlKK1fpRPg6Yb5P16XMHQ4U1UY9zyDRie0lkCtho3WNqPfdvPKxtiSsvhr3CBOINft%2B12wLqceuEOY9wKJ2AH9TUf8zwyAB9%2B4LAM9r8OyQguqbc9RUotWKWEkYP8hDUoBPNZ6pqSa7mYFCTptqmR52gPxwoemFrtwnA5DRPm%2FQ42iD96SSr%2BJGv8NCxe4syKSM90i%2BMqYYw%2BBZqq9vOGw%2FjVlpp0U2R5F%2B%2FYSQIIBXJTIqvIthrLYp0qaHNCpYmlF%2Bdmh8dyDTDunjN2F4TT3ajkETNcoklYqvT22LMcaaiugHGIFGnlt3kDYDHPfpcgLEf2X5VXwQ%2Bm9Gyl6nDmS3QxA4dUX2qkKtymPFHe1T%2BUJr9lHgwiKJo6Dj4wr7%2FRvQY6pgFjx32Nc295%2BO4MXBgP3fXan%2FyYt6BmcteMuzpv%2FqCEQeRB2fbUHFVO%2BKsZhOb7aWvLsDubeEq63yC3Xl0i1O6iHzKMinH5VSh3HVgWoJ2u%2FEevVoTeXLpZSKaZ47eGx5dzl%2F9D9Mf3nqZftRbh%2F7gVzb%2FQGpg2yFGA0S%2Bw8xYnNpPDasFahDtC8EEnPbWVSHTukFQDfkoE6DznhrY4c6lVZZBoAIi1&X-Amz-Signature=5e998db696567616f7566fd711fb0843805d4c7858f1e8833b9d8cd02bb57ef0&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666TMCBBTE%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T111953Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGMaCXVzLXdlc3QtMiJGMEQCIAE8Amw6nG5%2FZLRYTVbXnCHbyGR0bTNrCrGY2hHyNtcwAiAzR3hjj8raa5vrRjiKpPQV4mwEOM8RCGDknIT0cv6cpiqIBAiM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMIQgfQ8UTekgnMCBiKtwDgztwMhmdyI7Ziqo6nemXrXoCIc5S1xhleAmIg7F6y26Stju253kC3QtfoaIfPWigHai%2FlDlWqst5TY1rx6BI4uNb%2F16AHoScuLefJwAMqid16RIL824O02OZY3zfez%2BQ3Mox0L5e3QHG3ULfn27tLirEj%2BteDI295XklXIstwStDbOidSqUWF9mXJ4Fbk9WQOh0aZNHc%2BDkE87zIywreVoVhlm1azIfpZdAQ%2FAxbGx8pMWG2IhSjyp0ui7LzGVvxlKK1fpRPg6Yb5P16XMHQ4U1UY9zyDRie0lkCtho3WNqPfdvPKxtiSsvhr3CBOINft%2B12wLqceuEOY9wKJ2AH9TUf8zwyAB9%2B4LAM9r8OyQguqbc9RUotWKWEkYP8hDUoBPNZ6pqSa7mYFCTptqmR52gPxwoemFrtwnA5DRPm%2FQ42iD96SSr%2BJGv8NCxe4syKSM90i%2BMqYYw%2BBZqq9vOGw%2FjVlpp0U2R5F%2B%2FYSQIIBXJTIqvIthrLYp0qaHNCpYmlF%2Bdmh8dyDTDunjN2F4TT3ajkETNcoklYqvT22LMcaaiugHGIFGnlt3kDYDHPfpcgLEf2X5VXwQ%2Bm9Gyl6nDmS3QxA4dUX2qkKtymPFHe1T%2BUJr9lHgwiKJo6Dj4wr7%2FRvQY6pgFjx32Nc295%2BO4MXBgP3fXan%2FyYt6BmcteMuzpv%2FqCEQeRB2fbUHFVO%2BKsZhOb7aWvLsDubeEq63yC3Xl0i1O6iHzKMinH5VSh3HVgWoJ2u%2FEevVoTeXLpZSKaZ47eGx5dzl%2F9D9Mf3nqZftRbh%2F7gVzb%2FQGpg2yFGA0S%2Bw8xYnNpPDasFahDtC8EEnPbWVSHTukFQDfkoE6DznhrY4c6lVZZBoAIi1&X-Amz-Signature=c6778a7b7be943e72ac8bac6cc82f86065fe857c6d88dc7d68de86146de07a2e&X-Amz-SignedHeaders=host&x-id=GetObject)


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

