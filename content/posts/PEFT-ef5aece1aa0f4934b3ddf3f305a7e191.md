---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466QKXFYEGG%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250209T025358Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEIP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIARt%2FZSSGFUi6giWJ\
  9HbIET%2Bpcnrez%2FBHFVT%2BGqq5qT7AiEA7rLjzo7i8VimQ2tBy1UKe79cq5twJ%2F2hSfSug0\
  hGpAUqiAQIm%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDJ2IQhwSA\
  laLjAeAhCrcA9GgRaQkpL8NG2AaNyxdI3efxB60WOTNdhpeZhLsCTzFI4zJi2fRwSFpRTX%2F07J5\
  3%2FwCqkXdgCydz9P%2FiA7fYhVCdsjguRjsRbNvmHm8a%2B8CYv1NJierOczggT4mTfU81mkpn5q\
  x9YwwPMywUyiDYbbMFCWApX%2FdguF%2Bap%2Fbmkw0aVgrY4jgDJkuNy%2F%2FBjTyQxR3gry%2F\
  0SNs3iTmEUHVE5rJa5PxUOnAHlxajRjj1vyO8UadIBXnDMuBnOH0Dv5FlGxlOg%2B%2BgfGQ8sFjq\
  eBwPSOY9k9%2F3u8wYzBne4GuyD7gOT3NaB%2FvSU6isaWs%2FNRPZjpd8fMFsie4B4bbdpVBwuIo\
  uYO7hZeZ6oHs2xyzFBTO0IXxJKF6HBu2qbKBPGnsvE1DFTUuqH%2FOVIMDK1Ibv%2FKTH9ZEUCtrg\
  6rFigF1wK889IUqVUR7pGwc4SCBvHr6LUVw%2FOoUludrpHhttXcgFZxpwvCldG6nFeEHY9w2NdNY\
  KaV9cqFPnrbPYe%2FuZQRF0a4Ub96ErXqDphJqSIP0rIKudowzV4Md1%2BT%2BqxaK%2BINBC8gV2\
  eJ8tQeUD1ZrZDdcN6yBIWAZp2JGMC4K7nshvNOYAxK89GihjFWM6lsrqRC%2BhHO6AEYyDrdE5Dgh\
  MMihoL0GOqUBoP9T7eLb%2BK3dOJvBi60aMm%2FnB827M6SulLeOnQcava%2BkzqdsIfhMzZY8qrT\
  hdckJxblagv%2B2yjyzquOuLIfiOuxngpDp2io4qpLQBmmVxyeYNKvq9C6kkvGqv1a2r9A2xO%2Fo\
  ya%2FodVkULneNK7u8PKLNce7L4klo4EuiZinX0orgpNVrzykuj2G9xrBv3d2R8309DfNfYTFWu3m\
  0kjJwzqvmH3GM&X-Amz-Signature=39e27b9cba540a86298d607520da70b1dce0ffc8e4f0003\
  a925a771975eac1a4&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466RELOCRVE%2F20250209%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250209T025254Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEIP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEY\
        CIQCkzg1UMsuuV8Ot4k0B6Gcn2W2WZGcqqXqhPk7%2FyChDmgIhANG6GcnMaphc6t3B61o8\
        L%2F0UKTDUDRMqX7s0kr8FUbmvKogECJv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMN\
        jM3NDIzMTgzODA1IgxRluHsXUp8phSE%2BmEq3AO8kaI32Vp%2FR%2BSi1P%2BhlO0aLw60\
        B7NXTYviES4Ic%2BLUID5W%2BedNJdC%2BL%2F2FJhHyd%2BrUUYs%2FI3DzfGE91CfFcu7\
        PDeoQ%2BI%2FH9W1D%2BNpnGkciVMXlZW%2B5Kyb9vgELcxrYWsViMKwTSbA%2FLokchAgd\
        mH%2FwnplhDSzVIhK%2F1YybValSCU7jwdHpsyX6uNOi6qqS6hgSmf7gFm2V%2BKdTv%2BN\
        AfpY2PxnuSwty9yrxL%2BRg1Qc%2FCawlqQOVmhQsj30IxXVcGxouqWxt4DKw7VU3S03urk\
        vla1od%2BLiKc%2Bo3U%2BCiFbfwMZDrbnaDXJPQW1uWRtjxeSX4tkXz7nBN%2BnWt3AefN\
        skuOc0G8TYVebDmVdvPkqOjhOpR%2BGvPHBSyIbuqE6Ze45xA0EkO%2BMwnKzYnjt7ytFAG\
        3%2BUevGe7x84AVhzUDdpg8Fb%2BPzDbmcThZzIjStSF5rbga76WINJK4DGprt18ObX9%2B\
        qSqEkn6MbxELyeE37O%2B%2Bsb9p%2FJxxI%2F7DGQaZAtGCzTU6UqVH17VtZtCCAqcRXIN\
        P0WgQpxNjb8PsB6IwDPePpXIQ4FMzjYdwjUBZok8rdPKqg631N5VSEH8Wo3P00dY08%2Fyv\
        bZj8hSUFkceVZtBrnFMKOwjVy4zXfUcHjC5oqC9BjqkAdWaletvcvkViLUBR%2Bnd6ey2rD\
        wglaMLz%2FvkiuB7vavhUmmYPZ%2BW2jIEHGWP0V4FWJ5qozrctCcyZlQp7%2FTUUkCHvR0\
        95UEdWORU266Ixc7HeNLaJgnObq6E2rX14ho5Aj%2BzfK9zwkEzTFPt54BM%2BIBfNSg%2B\
        JTpv6RkC46SwMK36KYZRrn9sQD%2BW1mdAFzslCZ50SANiYYjhNwI92N013Fepsmbw&X-Am\
        z-Signature=027eeaf86084fec55da411550c48fcc8f64c1a26f9597c105d6fef81d4b\
        904af&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-09T03:52:54.275Z"
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
UPDATE_TIME: "2025-02-09T02:54:08.208Z"
EXPIRY_TIME: "2025-02-09T03:53:55.443Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663H7H5YFY%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T025355Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIBciCzIkvtklHP%2BOmsSMyATdBC1YveWk3pU%2BKPw3%2ByI9AiA7BhDsx1J6Ikk74IuC8fhJC%2FSbivswiVDJF2u2VZI99iqIBAib%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMMWKSHI84ju%2FK7tZ6KtwDKrgf4ZjzhAahGHVXUzo9hhSNEpoA2m6kKWw7alAuzUFuvuxO4ahzDAHmJ0uk4enlHVID0x9XgUw5%2B1TLQBdCzWZZdTrAhs%2FmrozNwRvKXQJATiJhsGM5lHmMz96dxEc28lByUIaPq8h6ylMbVWRAog6j1ojrD7h6ftr7qWCRVhoH0K71rw6NywLLBb6Pk22nYXQ%2BAdd%2BdA7x0LFa%2FGbDNAv7S8ni3Cvfx3eG957C2XLuaBFFBhCLCYKPX1qmy9oS57qn9i7PWlkcr9sdcluxCRWE3mzRimFmCpC7p1RSXMM%2Fk1YKwBgYY1AR%2FKVm%2BXjNI4OTHUYc32eNk648HyGFWkPN86GY2K62KDIrRafr86jAgia%2F3AsGCKORb2o6oYaYF3oDTwQqcJbSqPqIA0EjV4%2F8xTyCKLk7EDase%2BaKyRTlZrnHi%2BDl9CLlD8G9MBfASHyleiZ%2FSu4k6PKiGe%2F92eZegfoRPmj8%2FjRWg4GRX5o%2FwvQmtTp3sfqzrvRtgljxNJeRVZHAhvG1qBYdkkMw%2FRPEr1%2BdpMvoUS2Stx0bu6low85kd98IDLH9s51CD3%2BmKPvYt0EgWL%2BUyEluv4wyNZ2r6R9bWdqDHpfjK%2BttfXATblsGA5auGiSSfAQwqqKgvQY6pgEJCtpBw316XSkiVQTue3JGKRirgRSp%2FXlbeMaBVA3BBlVxHqSSjRa292DUUP2M%2FLMRg4Y%2FA0d1EGNIMVGjPYeAbgFs3%2F6KXOIb%2BhmAvmCJTxlVsjWToFO0kS8mpa9fbsAjlUDsF1D2a8o7a5TSsZwVismWAqrensGx%2FbYy7f1dIb1hphnTJQ%2BI105c6GgvoBdftQtM2ZEy1unzYbAB4rw%2BnaDTPtoT&X-Amz-Signature=972e08bd7ba90aeefb546c8a7a9d3e727aa0c67586793c64854c696ecf4eeabb&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663H7H5YFY%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T025355Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIBciCzIkvtklHP%2BOmsSMyATdBC1YveWk3pU%2BKPw3%2ByI9AiA7BhDsx1J6Ikk74IuC8fhJC%2FSbivswiVDJF2u2VZI99iqIBAib%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMMWKSHI84ju%2FK7tZ6KtwDKrgf4ZjzhAahGHVXUzo9hhSNEpoA2m6kKWw7alAuzUFuvuxO4ahzDAHmJ0uk4enlHVID0x9XgUw5%2B1TLQBdCzWZZdTrAhs%2FmrozNwRvKXQJATiJhsGM5lHmMz96dxEc28lByUIaPq8h6ylMbVWRAog6j1ojrD7h6ftr7qWCRVhoH0K71rw6NywLLBb6Pk22nYXQ%2BAdd%2BdA7x0LFa%2FGbDNAv7S8ni3Cvfx3eG957C2XLuaBFFBhCLCYKPX1qmy9oS57qn9i7PWlkcr9sdcluxCRWE3mzRimFmCpC7p1RSXMM%2Fk1YKwBgYY1AR%2FKVm%2BXjNI4OTHUYc32eNk648HyGFWkPN86GY2K62KDIrRafr86jAgia%2F3AsGCKORb2o6oYaYF3oDTwQqcJbSqPqIA0EjV4%2F8xTyCKLk7EDase%2BaKyRTlZrnHi%2BDl9CLlD8G9MBfASHyleiZ%2FSu4k6PKiGe%2F92eZegfoRPmj8%2FjRWg4GRX5o%2FwvQmtTp3sfqzrvRtgljxNJeRVZHAhvG1qBYdkkMw%2FRPEr1%2BdpMvoUS2Stx0bu6low85kd98IDLH9s51CD3%2BmKPvYt0EgWL%2BUyEluv4wyNZ2r6R9bWdqDHpfjK%2BttfXATblsGA5auGiSSfAQwqqKgvQY6pgEJCtpBw316XSkiVQTue3JGKRirgRSp%2FXlbeMaBVA3BBlVxHqSSjRa292DUUP2M%2FLMRg4Y%2FA0d1EGNIMVGjPYeAbgFs3%2F6KXOIb%2BhmAvmCJTxlVsjWToFO0kS8mpa9fbsAjlUDsF1D2a8o7a5TSsZwVismWAqrensGx%2FbYy7f1dIb1hphnTJQ%2BI105c6GgvoBdftQtM2ZEy1unzYbAB4rw%2BnaDTPtoT&X-Amz-Signature=773a38d40ca25e10cefc5eb1438462dfaf67a1e7b42bee6d30f9547708d99b41&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663H7H5YFY%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T025355Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIBciCzIkvtklHP%2BOmsSMyATdBC1YveWk3pU%2BKPw3%2ByI9AiA7BhDsx1J6Ikk74IuC8fhJC%2FSbivswiVDJF2u2VZI99iqIBAib%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMMWKSHI84ju%2FK7tZ6KtwDKrgf4ZjzhAahGHVXUzo9hhSNEpoA2m6kKWw7alAuzUFuvuxO4ahzDAHmJ0uk4enlHVID0x9XgUw5%2B1TLQBdCzWZZdTrAhs%2FmrozNwRvKXQJATiJhsGM5lHmMz96dxEc28lByUIaPq8h6ylMbVWRAog6j1ojrD7h6ftr7qWCRVhoH0K71rw6NywLLBb6Pk22nYXQ%2BAdd%2BdA7x0LFa%2FGbDNAv7S8ni3Cvfx3eG957C2XLuaBFFBhCLCYKPX1qmy9oS57qn9i7PWlkcr9sdcluxCRWE3mzRimFmCpC7p1RSXMM%2Fk1YKwBgYY1AR%2FKVm%2BXjNI4OTHUYc32eNk648HyGFWkPN86GY2K62KDIrRafr86jAgia%2F3AsGCKORb2o6oYaYF3oDTwQqcJbSqPqIA0EjV4%2F8xTyCKLk7EDase%2BaKyRTlZrnHi%2BDl9CLlD8G9MBfASHyleiZ%2FSu4k6PKiGe%2F92eZegfoRPmj8%2FjRWg4GRX5o%2FwvQmtTp3sfqzrvRtgljxNJeRVZHAhvG1qBYdkkMw%2FRPEr1%2BdpMvoUS2Stx0bu6low85kd98IDLH9s51CD3%2BmKPvYt0EgWL%2BUyEluv4wyNZ2r6R9bWdqDHpfjK%2BttfXATblsGA5auGiSSfAQwqqKgvQY6pgEJCtpBw316XSkiVQTue3JGKRirgRSp%2FXlbeMaBVA3BBlVxHqSSjRa292DUUP2M%2FLMRg4Y%2FA0d1EGNIMVGjPYeAbgFs3%2F6KXOIb%2BhmAvmCJTxlVsjWToFO0kS8mpa9fbsAjlUDsF1D2a8o7a5TSsZwVismWAqrensGx%2FbYy7f1dIb1hphnTJQ%2BI105c6GgvoBdftQtM2ZEy1unzYbAB4rw%2BnaDTPtoT&X-Amz-Signature=fda97ea1b5fb72a7f15ba24a370f3257d1f0e876997a08463bb45550b6183ac8&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663H7H5YFY%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T025355Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIBciCzIkvtklHP%2BOmsSMyATdBC1YveWk3pU%2BKPw3%2ByI9AiA7BhDsx1J6Ikk74IuC8fhJC%2FSbivswiVDJF2u2VZI99iqIBAib%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMMWKSHI84ju%2FK7tZ6KtwDKrgf4ZjzhAahGHVXUzo9hhSNEpoA2m6kKWw7alAuzUFuvuxO4ahzDAHmJ0uk4enlHVID0x9XgUw5%2B1TLQBdCzWZZdTrAhs%2FmrozNwRvKXQJATiJhsGM5lHmMz96dxEc28lByUIaPq8h6ylMbVWRAog6j1ojrD7h6ftr7qWCRVhoH0K71rw6NywLLBb6Pk22nYXQ%2BAdd%2BdA7x0LFa%2FGbDNAv7S8ni3Cvfx3eG957C2XLuaBFFBhCLCYKPX1qmy9oS57qn9i7PWlkcr9sdcluxCRWE3mzRimFmCpC7p1RSXMM%2Fk1YKwBgYY1AR%2FKVm%2BXjNI4OTHUYc32eNk648HyGFWkPN86GY2K62KDIrRafr86jAgia%2F3AsGCKORb2o6oYaYF3oDTwQqcJbSqPqIA0EjV4%2F8xTyCKLk7EDase%2BaKyRTlZrnHi%2BDl9CLlD8G9MBfASHyleiZ%2FSu4k6PKiGe%2F92eZegfoRPmj8%2FjRWg4GRX5o%2FwvQmtTp3sfqzrvRtgljxNJeRVZHAhvG1qBYdkkMw%2FRPEr1%2BdpMvoUS2Stx0bu6low85kd98IDLH9s51CD3%2BmKPvYt0EgWL%2BUyEluv4wyNZ2r6R9bWdqDHpfjK%2BttfXATblsGA5auGiSSfAQwqqKgvQY6pgEJCtpBw316XSkiVQTue3JGKRirgRSp%2FXlbeMaBVA3BBlVxHqSSjRa292DUUP2M%2FLMRg4Y%2FA0d1EGNIMVGjPYeAbgFs3%2F6KXOIb%2BhmAvmCJTxlVsjWToFO0kS8mpa9fbsAjlUDsF1D2a8o7a5TSsZwVismWAqrensGx%2FbYy7f1dIb1hphnTJQ%2BI105c6GgvoBdftQtM2ZEy1unzYbAB4rw%2BnaDTPtoT&X-Amz-Signature=eaf24d7a8fa3fae49a58bcc52d2a0f8eaf477b910f0d608cfb50a8cf92040ff9&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663H7H5YFY%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T025355Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIBciCzIkvtklHP%2BOmsSMyATdBC1YveWk3pU%2BKPw3%2ByI9AiA7BhDsx1J6Ikk74IuC8fhJC%2FSbivswiVDJF2u2VZI99iqIBAib%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMMWKSHI84ju%2FK7tZ6KtwDKrgf4ZjzhAahGHVXUzo9hhSNEpoA2m6kKWw7alAuzUFuvuxO4ahzDAHmJ0uk4enlHVID0x9XgUw5%2B1TLQBdCzWZZdTrAhs%2FmrozNwRvKXQJATiJhsGM5lHmMz96dxEc28lByUIaPq8h6ylMbVWRAog6j1ojrD7h6ftr7qWCRVhoH0K71rw6NywLLBb6Pk22nYXQ%2BAdd%2BdA7x0LFa%2FGbDNAv7S8ni3Cvfx3eG957C2XLuaBFFBhCLCYKPX1qmy9oS57qn9i7PWlkcr9sdcluxCRWE3mzRimFmCpC7p1RSXMM%2Fk1YKwBgYY1AR%2FKVm%2BXjNI4OTHUYc32eNk648HyGFWkPN86GY2K62KDIrRafr86jAgia%2F3AsGCKORb2o6oYaYF3oDTwQqcJbSqPqIA0EjV4%2F8xTyCKLk7EDase%2BaKyRTlZrnHi%2BDl9CLlD8G9MBfASHyleiZ%2FSu4k6PKiGe%2F92eZegfoRPmj8%2FjRWg4GRX5o%2FwvQmtTp3sfqzrvRtgljxNJeRVZHAhvG1qBYdkkMw%2FRPEr1%2BdpMvoUS2Stx0bu6low85kd98IDLH9s51CD3%2BmKPvYt0EgWL%2BUyEluv4wyNZ2r6R9bWdqDHpfjK%2BttfXATblsGA5auGiSSfAQwqqKgvQY6pgEJCtpBw316XSkiVQTue3JGKRirgRSp%2FXlbeMaBVA3BBlVxHqSSjRa292DUUP2M%2FLMRg4Y%2FA0d1EGNIMVGjPYeAbgFs3%2F6KXOIb%2BhmAvmCJTxlVsjWToFO0kS8mpa9fbsAjlUDsF1D2a8o7a5TSsZwVismWAqrensGx%2FbYy7f1dIb1hphnTJQ%2BI105c6GgvoBdftQtM2ZEy1unzYbAB4rw%2BnaDTPtoT&X-Amz-Signature=7c73f7a217ad9e3b56a4730fcfcdad8c7599833b9e57e75b40258ba8db197330&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663CSK27AC%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T025357Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIFdJ6mtcTY4bfR2N%2F8j7GpEC9NG3MQAbKcm6WF1a0%2BdCAiEAj%2BElAsgAhrAS4bVH%2Fp%2BQxSTMVVLAfVmUuWked5CNCCAqiAQIm%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDAXalCMoL8qZzlJVPSrcA4REKGjcAgaG%2FceQWQexBzfsFA2WxGR2fqkLJshoKJZu%2BcQnpmRh3WVL42BwVxt8ijOcD0Lm7H3DF0xRXk%2Ffy6cC418QTplZ148N1nNoJ4BDcKL%2B90p%2FsbzG2R77Qd5pUNuWQ0bkzmTr1XeEEfPwh3ZZE1tOM3ugKdnGV8cy988Deq0Q5881LjdsQyZ9BxNxdy2q2jqqIUoM2GxyTrziS8cjR29im7gKjJRTcah9ygATiKNO3nlOEqO4kW5AiqNNpGpPLtmIQCDipqptxKwtOYklQy7pi5Ic%2F3u5WS%2B8qK3Y2JkjdJqyRXe0rLBzw%2FVOEs4x3db9XLiAGHmWGjlCRL5DkMiLo%2BQhPCHW7%2F1F%2B9hHroPgErOV4mUBISkx3BdCNi5NxNpZh0drFgwoyYoMhX7Sb%2FHW6DvpBNXF7n2NmPgDbqhv9Cmv4nfKfwW0tYaEqHeGy9zGikCyKxVhv8rSslmCPAHe%2B02VQzlJPNf2sTXhNSoe9jkCevdh8SlfeXiZ0ra5bYZzZS49XJGFwme9mcHO5bBXy0PQDSexE7o%2BHKa9xjEjoqDz9tHojqfk6ynOYiAAIGArIOQOxEcLpHco7d0nkGNL8O%2B7J%2Bn221IevbytoykZUTReXoOnjTajMM2ioL0GOqUBvI9HSjkTXJGvUfuScwlZJtW9BxEjdAJZFsaabD%2Fnv%2B3HtJ1wZmDII6p7i8ezKLGuFJsaRk7ZUaTvro57LfGfl3MepJJFwdt%2B8fxeWiv2OZerU155kjX%2FU69pihY5l9BwC3Ex3LC2cmXWhow4cIb8%2FIC6a6kVzv1lz0iKCxVDqVeEKqS7F4AuJU8L%2FbLP3K2AG92Ujw0ShlvFtyV%2FoHHCiUmX%2BkI%2F&X-Amz-Signature=43988504cca1a4a6d0f623f28f821b19f355248196260b5747273aac2d08b01a&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466T7MMFYH6%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T025358Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDpLzJNvhWDAqGArVKjCQ68758fn0q6NSBjNe4ITELn9AIhAPp5GHDwAwAz1H%2BjTWCLxR2QH6j4uiT2Amw3LSg1ZkcvKogECJv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxdhRg8fUb92cd3GIwq3AM%2BWGTBLBpP3nnEHggcX%2FkVMkeG%2BYZkU7jGhknaT5Mfj5PmkiNRZwECxlVqqDjTqBgd4pnEoJjM5TbzvGNt26t3nRh1fRKiQn%2F3yszIu94Q%2FPWa4%2BKW9%2F2isfdoMAoup%2F%2FG8fiD5%2B8Qj8NV1JKHOd88GpZZTElYCp1x2SD%2FdbeSrLEPpXxcC82EKaYb%2Frp15dwTdUiCyEiGtCBnfHGWpCg6adPTZI5fm0yeLTAUQjCUzZV8By858SA6tv1W82OufWAFzQbN1JmwTyUWIagRz8Sf8%2FpweFhzIYluvRM4F6UgUNWdPOVy%2BMHek7QhrPU2kMRqWQ2QliGU7%2B5pRZW40J4zApIT4MS%2Frt70y%2BwRaNLCrNI2m%2FxGwTMipwEfMT5w3LzBhOAlfqTCtmlyR%2BkisZz08ME6YSOjMse5Tkur2AddxAEOLSp2A%2Br1r%2FqmUgBlxV8zMOf3kIbU9qi0tzpxQCuBtxOJ%2BUSGsH5osHSMaALLPaJKNA8dEo2XVI9uL0%2Fs7rw20GjGB40SGPQULvmXJW4rqV3Yoh5HNpjnOvSputhoI%2FZejEdUXssYwBJ8lVckxQp7Rhsi9g6PXUbjrxfqGlxPhKxjLqL%2BtfXCg7K1%2B%2B0hk40hzz%2BkaxJUwnHrcDCFoqC9BjqkAS3Xu%2B7zCdbBsZI%2B5liuZdxKss8Kza5GPH1fOqRc3t%2B%2BunvCrTJY01mf7%2BGwQe1MugryWhpXp9BE6vqYucjkJnYE9tE%2BemwY30Vqj3MpRi6z2snILchWt8qgKYHWGEyBN8%2B%2FmgD2EE6UGHi5IDeGRwAmw00xCMaXmE2yRsvRhxS7y8DaF0Qtd%2F4WX4fHV8RRQYcZMafmXfdlG9z2cO94Twq8UBr1&X-Amz-Signature=802b59adf43727eac6fad7a5d0c2d21710267546972473abdf96ee0cd4ce671e&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663H7H5YFY%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T025355Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIBciCzIkvtklHP%2BOmsSMyATdBC1YveWk3pU%2BKPw3%2ByI9AiA7BhDsx1J6Ikk74IuC8fhJC%2FSbivswiVDJF2u2VZI99iqIBAib%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMMWKSHI84ju%2FK7tZ6KtwDKrgf4ZjzhAahGHVXUzo9hhSNEpoA2m6kKWw7alAuzUFuvuxO4ahzDAHmJ0uk4enlHVID0x9XgUw5%2B1TLQBdCzWZZdTrAhs%2FmrozNwRvKXQJATiJhsGM5lHmMz96dxEc28lByUIaPq8h6ylMbVWRAog6j1ojrD7h6ftr7qWCRVhoH0K71rw6NywLLBb6Pk22nYXQ%2BAdd%2BdA7x0LFa%2FGbDNAv7S8ni3Cvfx3eG957C2XLuaBFFBhCLCYKPX1qmy9oS57qn9i7PWlkcr9sdcluxCRWE3mzRimFmCpC7p1RSXMM%2Fk1YKwBgYY1AR%2FKVm%2BXjNI4OTHUYc32eNk648HyGFWkPN86GY2K62KDIrRafr86jAgia%2F3AsGCKORb2o6oYaYF3oDTwQqcJbSqPqIA0EjV4%2F8xTyCKLk7EDase%2BaKyRTlZrnHi%2BDl9CLlD8G9MBfASHyleiZ%2FSu4k6PKiGe%2F92eZegfoRPmj8%2FjRWg4GRX5o%2FwvQmtTp3sfqzrvRtgljxNJeRVZHAhvG1qBYdkkMw%2FRPEr1%2BdpMvoUS2Stx0bu6low85kd98IDLH9s51CD3%2BmKPvYt0EgWL%2BUyEluv4wyNZ2r6R9bWdqDHpfjK%2BttfXATblsGA5auGiSSfAQwqqKgvQY6pgEJCtpBw316XSkiVQTue3JGKRirgRSp%2FXlbeMaBVA3BBlVxHqSSjRa292DUUP2M%2FLMRg4Y%2FA0d1EGNIMVGjPYeAbgFs3%2F6KXOIb%2BhmAvmCJTxlVsjWToFO0kS8mpa9fbsAjlUDsF1D2a8o7a5TSsZwVismWAqrensGx%2FbYy7f1dIb1hphnTJQ%2BI105c6GgvoBdftQtM2ZEy1unzYbAB4rw%2BnaDTPtoT&X-Amz-Signature=b27ec88bdd4fd198db54655f32a578bd9e5d5e4d882236964f0d1168824dc3bc&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663H7H5YFY%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T025355Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIBciCzIkvtklHP%2BOmsSMyATdBC1YveWk3pU%2BKPw3%2ByI9AiA7BhDsx1J6Ikk74IuC8fhJC%2FSbivswiVDJF2u2VZI99iqIBAib%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMMWKSHI84ju%2FK7tZ6KtwDKrgf4ZjzhAahGHVXUzo9hhSNEpoA2m6kKWw7alAuzUFuvuxO4ahzDAHmJ0uk4enlHVID0x9XgUw5%2B1TLQBdCzWZZdTrAhs%2FmrozNwRvKXQJATiJhsGM5lHmMz96dxEc28lByUIaPq8h6ylMbVWRAog6j1ojrD7h6ftr7qWCRVhoH0K71rw6NywLLBb6Pk22nYXQ%2BAdd%2BdA7x0LFa%2FGbDNAv7S8ni3Cvfx3eG957C2XLuaBFFBhCLCYKPX1qmy9oS57qn9i7PWlkcr9sdcluxCRWE3mzRimFmCpC7p1RSXMM%2Fk1YKwBgYY1AR%2FKVm%2BXjNI4OTHUYc32eNk648HyGFWkPN86GY2K62KDIrRafr86jAgia%2F3AsGCKORb2o6oYaYF3oDTwQqcJbSqPqIA0EjV4%2F8xTyCKLk7EDase%2BaKyRTlZrnHi%2BDl9CLlD8G9MBfASHyleiZ%2FSu4k6PKiGe%2F92eZegfoRPmj8%2FjRWg4GRX5o%2FwvQmtTp3sfqzrvRtgljxNJeRVZHAhvG1qBYdkkMw%2FRPEr1%2BdpMvoUS2Stx0bu6low85kd98IDLH9s51CD3%2BmKPvYt0EgWL%2BUyEluv4wyNZ2r6R9bWdqDHpfjK%2BttfXATblsGA5auGiSSfAQwqqKgvQY6pgEJCtpBw316XSkiVQTue3JGKRirgRSp%2FXlbeMaBVA3BBlVxHqSSjRa292DUUP2M%2FLMRg4Y%2FA0d1EGNIMVGjPYeAbgFs3%2F6KXOIb%2BhmAvmCJTxlVsjWToFO0kS8mpa9fbsAjlUDsF1D2a8o7a5TSsZwVismWAqrensGx%2FbYy7f1dIb1hphnTJQ%2BI105c6GgvoBdftQtM2ZEy1unzYbAB4rw%2BnaDTPtoT&X-Amz-Signature=e27aad4067e9522210d3b3ec532b1ebda3ed93306ff9c12ab298cf44e8deccd4&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663H7H5YFY%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T025355Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIBciCzIkvtklHP%2BOmsSMyATdBC1YveWk3pU%2BKPw3%2ByI9AiA7BhDsx1J6Ikk74IuC8fhJC%2FSbivswiVDJF2u2VZI99iqIBAib%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMMWKSHI84ju%2FK7tZ6KtwDKrgf4ZjzhAahGHVXUzo9hhSNEpoA2m6kKWw7alAuzUFuvuxO4ahzDAHmJ0uk4enlHVID0x9XgUw5%2B1TLQBdCzWZZdTrAhs%2FmrozNwRvKXQJATiJhsGM5lHmMz96dxEc28lByUIaPq8h6ylMbVWRAog6j1ojrD7h6ftr7qWCRVhoH0K71rw6NywLLBb6Pk22nYXQ%2BAdd%2BdA7x0LFa%2FGbDNAv7S8ni3Cvfx3eG957C2XLuaBFFBhCLCYKPX1qmy9oS57qn9i7PWlkcr9sdcluxCRWE3mzRimFmCpC7p1RSXMM%2Fk1YKwBgYY1AR%2FKVm%2BXjNI4OTHUYc32eNk648HyGFWkPN86GY2K62KDIrRafr86jAgia%2F3AsGCKORb2o6oYaYF3oDTwQqcJbSqPqIA0EjV4%2F8xTyCKLk7EDase%2BaKyRTlZrnHi%2BDl9CLlD8G9MBfASHyleiZ%2FSu4k6PKiGe%2F92eZegfoRPmj8%2FjRWg4GRX5o%2FwvQmtTp3sfqzrvRtgljxNJeRVZHAhvG1qBYdkkMw%2FRPEr1%2BdpMvoUS2Stx0bu6low85kd98IDLH9s51CD3%2BmKPvYt0EgWL%2BUyEluv4wyNZ2r6R9bWdqDHpfjK%2BttfXATblsGA5auGiSSfAQwqqKgvQY6pgEJCtpBw316XSkiVQTue3JGKRirgRSp%2FXlbeMaBVA3BBlVxHqSSjRa292DUUP2M%2FLMRg4Y%2FA0d1EGNIMVGjPYeAbgFs3%2F6KXOIb%2BhmAvmCJTxlVsjWToFO0kS8mpa9fbsAjlUDsF1D2a8o7a5TSsZwVismWAqrensGx%2FbYy7f1dIb1hphnTJQ%2BI105c6GgvoBdftQtM2ZEy1unzYbAB4rw%2BnaDTPtoT&X-Amz-Signature=9e857e9b89b1164863ea8995a358231ae91b672bdc219ac2d4c5d1016afee904&X-Amz-SignedHeaders=host&x-id=GetObject)


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

