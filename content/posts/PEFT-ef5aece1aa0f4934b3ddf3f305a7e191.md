---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB46623F24UHP%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250220T222344Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIC%2BA05oPT72rV1Tn8\
  HNar4uBPRfmu6AMvqyxMb%2B6cgtwAiEAwLIXTM6oEDsqK1ciY9ANUy0eGB%2FfUn5xCReGSplboL\
  YqiAQIxf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDJWbT%2B9Xm9HQW\
  Z6TvCrcA2HrO2ffutabjnd90Dxsycwi%2Bse4aF0Xa1%2FBKp8UMijK%2B6tXAwx5QO765PnwDV%2\
  BynJreNDred0Yq009uMqhnB%2B4GQC4jlIxe%2BNE8ecdzMV9tk7bV%2Bmhhs6FBcyikQaaD37VGm\
  UsOgdev%2B7N%2BKFyDM8gwMFVEbHHT3jih%2BwDrhK7aOO8jUuN%2BKz71CVIo8%2FiU1SoGWxQm\
  oeyRcuJCLy301SI6AGGkuIgcHszj1TTm6X5Ym96EF1o4o0fqERgSbJySM6CKNtmQ%2FUw%2Bk1Tm3\
  qJiILXvUGzeIfwf%2BWyJdvNs3pE2vlnQqVyo41QMXa69WyQ%2FbLjzAZyCThTtUgQaGkVGzyoQhA\
  6R7QyviZKiXs6zOmIL%2FVVN8ymQYb%2FCzBTxcZ69nUfRnxOFd2kNiRn62cDo%2BMZxMOGqsG75y\
  M%2B4yNEUDDMuJUBpKz1gkmuRcvcHtLKJJ7qjVmRnVH%2B7eJXU993SaVLaxLv3wzgt1V2vR8P6Ab\
  n8LTiZRCxYArdbU20bHoOuRcw2BE8GXNVjRo8ppKF%2B3gYctehN3Sn3GA7y3axIQmCCRWhT7G%2B\
  Vqkdie%2FmalLc4vVwyjpp7yKNlz6PH%2FwbGOtiGik8HolvFgtEdcqxbNT2HSYm%2Fs7batFUuQb\
  cJMK6N3r0GOqUB8H2hUichTGA%2BKd1MRywI8obgAate70bxWb7a9ja2Xme5qDh2ZSLnsOmba10I0\
  8qGtUHOrz0xrNNyoVA7JFLkCteJZjeZ6cV80pSaSnwoWlh%2BPJ2ekUbo8HKRODd%2FJxP8euu%2F\
  yuol8ZQSiwc5jyw%2BL4G7U0KguKMe%2Bm%2BrCA%2Fbj1%2BIMsbMxFd1L1ihzWoKICKKJ5S%2B4\
  UTaCo4Vhw0l%2Fl7V6gLWUoZu&X-Amz-Signature=ea30231e9db97eafc090059b780991ce65f\
  a3b7faaaef4644f2ad2c31ad3e1cc&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4664KRVLJ7Q%2F20250220%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250220T222137Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQ\
        CID11hBW6GPEhU7uM8C7cUjFvYBFYYE3o6NFifmGvC0SQAiBBB8bnEGV%2BtF4zW%2F1Rp5\
        IEWsE8xwaIdq5jkRS7VjpBgCqIBAjF%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzN\
        zQyMzE4MzgwNSIMaQZpBCogGXsC%2Fk5GKtwD62peyCcCZcgLLhKw2lZ2wQsnwljkgvsC%2\
        FcjNPrBLRozJp1jE25uv8BEt%2FSwGnn%2BwcwqHH%2FEuXVSw1UIE4lj3R0IJBm%2B04kP\
        3gCFp61B3ek9FtY3SnSlHSSMj75n7KPOmR3i96dIBMgNJag%2Bo6lvQYxPfmIHdMx11QRRL\
        3m71bzzADt7VBtTgXCyMqrDS%2F03f7dCJIICM0l1gHpGQDRoxLNIic8Dx9g90L6B9mV%2F\
        MsPVfVm7%2FbCFMjRMhcm28NRRSjflreMNilY7mWALf82E3oWIm1f9Mth2I4ih5tGwKG0Br\
        xjKue5DC17goD%2BP0VPOM1DtPAiqr%2F31mJ%2FuiY8wM70dD9sl2GVUU4Oj405GEc5N72\
        auGQuHPRKG%2F%2FqmJaOGUdp%2BFF34ku%2FCUKq3MkUROogUMjOBhAXeMJ4625fYhI0Oe\
        QPuXYz%2Fy0BH1ObMsDS1mBWC1ISYqtRqNMUdvfyI%2BUF8VHd8wVmVOx5P4SQV5VSLSh90\
        0yz3%2BRpEiAVXp6GfECqc8dcTokvEG0n4KsHVcuFqXqHPuchtcCE3Ys1N2NTo3y7YvQqJg\
        ngtoLPvGXB51ZPAqSR3aGyO2fvBd5cjLIUhRnaN8YMwZaAM4u%2BvPG8qMx7e1HpZXoFp1L\
        2Aw1I3evQY6pgFrj4151RVouIBRvk5q1gAtOYR7ZO6ANANFKIfPj8CVa3brLnH20I1tofUE\
        DcIvdUVMvi1mFFQlSepSP6QdeMFiNCIKy2Vux5EGWC1z97kJlZYylGlXa5WoKnWMYgZZ4jI\
        iXIarE9rTfi%2B9B%2FFZivDD72NaKfBqBHrlFvCLIf0EnpmVGD98hmUVSVIEAO5LgGotkn\
        dSKKDJdKVGCRHS7kCHvBRKMo80&X-Amz-Signature=1e69c0001f1000e52c69f2a6c246\
        fcf19cf430c5fd0cf472c9cab7e3015a072e&X-Amz-SignedHeaders=host&x-id=GetO\
        bject"
      expiry_time: "2025-02-20T23:21:37.881Z"
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
UPDATE_TIME: "2025-02-20T22:23:50.468Z"
EXPIRY_TIME: "2025-02-20T23:23:41.086Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QKOLX2NI%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T222341Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIGlzCH8bhIqI0d%2Fy5bLq6H7peVMEgd6iiicwhVFCEV2EAiBvrGYXQImWeQDNNH8M%2BhkDRwVHj60ic1%2FXolbaGS6ONiqIBAjF%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMseyFQ2bg1rRijZLSKtwDGeBowAdTbSTHyR7JccAVSnZNoENvx90I%2BnA90ymeHLSVBOTAQo8FKAdFp7V6BFR8ewxpB0CEzhInBW2kw5mk5hFTlXmS0zbDy%2BooYa5AckZ%2BJ%2BSyjQa1dOZMlHNolesXn3oFPglgYuvpDKFsWn9h2%2Fm2S5oezXILflSzM1RgUl1Cf7SqHSf0uTdYbAl10xJh4JkcKys8BLhjr9%2FAD9B7rExdsjH%2BW0tokceHXmMsVu9ruVKPqtYSDxCPeJXZcwQPvvdUApotsjirEERyi1HFQO%2BL2ILlcMBr70tMT%2BjqxDMYEBpbE9IrWrfAhBTz9OnAW5nWImoLotNHcNuV66b1z5w441fx4Q2hs4Jo%2FtzUVNKGizSPTEJkBE%2BYu2pHSzEylqo5qxR3aBOm1tPGhCXWMre12mMDEWpyu442%2BbaeDiko89JGYkzGyOI5%2F%2F7dMn1Aq%2Fok9xept%2F7oIpn5Hvqo8hTka%2F8%2FqBwr8M0%2BPaXZIBqVlyjVokjc2xP19cUCNyETpE%2Bp4BqnIFazLW1mtaiWFwKR9uXnF1rUHk34Yp6hg6Ivuo7vRFavAhNUsklnoQW4ufcgMr7NG1G6NvM2UCSMwQ394w3YlAq4L3basnWkHoLr5H1qcGTxis3mS1Uwr43evQY6pgENFdRx47sd9uAl0i02BZlpk4fvLeWMJoAE3QoZFumzlZ4iIV6rLGzNQNrUqQmqHRRFPSf6zmGa5qLNFdxtGRJGsF8Vfs5fguolYHBzDGs%2FH9JB%2BE6ouFEBMe81eIhw8u0mRtk4%2FbN3vqkHn80hGgP74yAZvJBh0JrsIyT8Mlhoj%2F29GyD82U1bLLTyCFbb5FVO41Bq%2B9n6aSheLwJ1X%2BK86d9xxJ%2Be&X-Amz-Signature=613f98118b97a2bf20a9a731eaf127493ff1a4c0b80be896bd1357c34d2497e1&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QKOLX2NI%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T222341Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIGlzCH8bhIqI0d%2Fy5bLq6H7peVMEgd6iiicwhVFCEV2EAiBvrGYXQImWeQDNNH8M%2BhkDRwVHj60ic1%2FXolbaGS6ONiqIBAjF%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMseyFQ2bg1rRijZLSKtwDGeBowAdTbSTHyR7JccAVSnZNoENvx90I%2BnA90ymeHLSVBOTAQo8FKAdFp7V6BFR8ewxpB0CEzhInBW2kw5mk5hFTlXmS0zbDy%2BooYa5AckZ%2BJ%2BSyjQa1dOZMlHNolesXn3oFPglgYuvpDKFsWn9h2%2Fm2S5oezXILflSzM1RgUl1Cf7SqHSf0uTdYbAl10xJh4JkcKys8BLhjr9%2FAD9B7rExdsjH%2BW0tokceHXmMsVu9ruVKPqtYSDxCPeJXZcwQPvvdUApotsjirEERyi1HFQO%2BL2ILlcMBr70tMT%2BjqxDMYEBpbE9IrWrfAhBTz9OnAW5nWImoLotNHcNuV66b1z5w441fx4Q2hs4Jo%2FtzUVNKGizSPTEJkBE%2BYu2pHSzEylqo5qxR3aBOm1tPGhCXWMre12mMDEWpyu442%2BbaeDiko89JGYkzGyOI5%2F%2F7dMn1Aq%2Fok9xept%2F7oIpn5Hvqo8hTka%2F8%2FqBwr8M0%2BPaXZIBqVlyjVokjc2xP19cUCNyETpE%2Bp4BqnIFazLW1mtaiWFwKR9uXnF1rUHk34Yp6hg6Ivuo7vRFavAhNUsklnoQW4ufcgMr7NG1G6NvM2UCSMwQ394w3YlAq4L3basnWkHoLr5H1qcGTxis3mS1Uwr43evQY6pgENFdRx47sd9uAl0i02BZlpk4fvLeWMJoAE3QoZFumzlZ4iIV6rLGzNQNrUqQmqHRRFPSf6zmGa5qLNFdxtGRJGsF8Vfs5fguolYHBzDGs%2FH9JB%2BE6ouFEBMe81eIhw8u0mRtk4%2FbN3vqkHn80hGgP74yAZvJBh0JrsIyT8Mlhoj%2F29GyD82U1bLLTyCFbb5FVO41Bq%2B9n6aSheLwJ1X%2BK86d9xxJ%2Be&X-Amz-Signature=e1e94eecc1dc1f8ada0d5eaf15664e88da23102c43fb2cc1e1c75e57e469cd50&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QKOLX2NI%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T222341Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIGlzCH8bhIqI0d%2Fy5bLq6H7peVMEgd6iiicwhVFCEV2EAiBvrGYXQImWeQDNNH8M%2BhkDRwVHj60ic1%2FXolbaGS6ONiqIBAjF%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMseyFQ2bg1rRijZLSKtwDGeBowAdTbSTHyR7JccAVSnZNoENvx90I%2BnA90ymeHLSVBOTAQo8FKAdFp7V6BFR8ewxpB0CEzhInBW2kw5mk5hFTlXmS0zbDy%2BooYa5AckZ%2BJ%2BSyjQa1dOZMlHNolesXn3oFPglgYuvpDKFsWn9h2%2Fm2S5oezXILflSzM1RgUl1Cf7SqHSf0uTdYbAl10xJh4JkcKys8BLhjr9%2FAD9B7rExdsjH%2BW0tokceHXmMsVu9ruVKPqtYSDxCPeJXZcwQPvvdUApotsjirEERyi1HFQO%2BL2ILlcMBr70tMT%2BjqxDMYEBpbE9IrWrfAhBTz9OnAW5nWImoLotNHcNuV66b1z5w441fx4Q2hs4Jo%2FtzUVNKGizSPTEJkBE%2BYu2pHSzEylqo5qxR3aBOm1tPGhCXWMre12mMDEWpyu442%2BbaeDiko89JGYkzGyOI5%2F%2F7dMn1Aq%2Fok9xept%2F7oIpn5Hvqo8hTka%2F8%2FqBwr8M0%2BPaXZIBqVlyjVokjc2xP19cUCNyETpE%2Bp4BqnIFazLW1mtaiWFwKR9uXnF1rUHk34Yp6hg6Ivuo7vRFavAhNUsklnoQW4ufcgMr7NG1G6NvM2UCSMwQ394w3YlAq4L3basnWkHoLr5H1qcGTxis3mS1Uwr43evQY6pgENFdRx47sd9uAl0i02BZlpk4fvLeWMJoAE3QoZFumzlZ4iIV6rLGzNQNrUqQmqHRRFPSf6zmGa5qLNFdxtGRJGsF8Vfs5fguolYHBzDGs%2FH9JB%2BE6ouFEBMe81eIhw8u0mRtk4%2FbN3vqkHn80hGgP74yAZvJBh0JrsIyT8Mlhoj%2F29GyD82U1bLLTyCFbb5FVO41Bq%2B9n6aSheLwJ1X%2BK86d9xxJ%2Be&X-Amz-Signature=24a5487d412502bb908c8cad21d33632db23f14651052a75b2db54f8d9da5482&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QKOLX2NI%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T222341Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIGlzCH8bhIqI0d%2Fy5bLq6H7peVMEgd6iiicwhVFCEV2EAiBvrGYXQImWeQDNNH8M%2BhkDRwVHj60ic1%2FXolbaGS6ONiqIBAjF%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMseyFQ2bg1rRijZLSKtwDGeBowAdTbSTHyR7JccAVSnZNoENvx90I%2BnA90ymeHLSVBOTAQo8FKAdFp7V6BFR8ewxpB0CEzhInBW2kw5mk5hFTlXmS0zbDy%2BooYa5AckZ%2BJ%2BSyjQa1dOZMlHNolesXn3oFPglgYuvpDKFsWn9h2%2Fm2S5oezXILflSzM1RgUl1Cf7SqHSf0uTdYbAl10xJh4JkcKys8BLhjr9%2FAD9B7rExdsjH%2BW0tokceHXmMsVu9ruVKPqtYSDxCPeJXZcwQPvvdUApotsjirEERyi1HFQO%2BL2ILlcMBr70tMT%2BjqxDMYEBpbE9IrWrfAhBTz9OnAW5nWImoLotNHcNuV66b1z5w441fx4Q2hs4Jo%2FtzUVNKGizSPTEJkBE%2BYu2pHSzEylqo5qxR3aBOm1tPGhCXWMre12mMDEWpyu442%2BbaeDiko89JGYkzGyOI5%2F%2F7dMn1Aq%2Fok9xept%2F7oIpn5Hvqo8hTka%2F8%2FqBwr8M0%2BPaXZIBqVlyjVokjc2xP19cUCNyETpE%2Bp4BqnIFazLW1mtaiWFwKR9uXnF1rUHk34Yp6hg6Ivuo7vRFavAhNUsklnoQW4ufcgMr7NG1G6NvM2UCSMwQ394w3YlAq4L3basnWkHoLr5H1qcGTxis3mS1Uwr43evQY6pgENFdRx47sd9uAl0i02BZlpk4fvLeWMJoAE3QoZFumzlZ4iIV6rLGzNQNrUqQmqHRRFPSf6zmGa5qLNFdxtGRJGsF8Vfs5fguolYHBzDGs%2FH9JB%2BE6ouFEBMe81eIhw8u0mRtk4%2FbN3vqkHn80hGgP74yAZvJBh0JrsIyT8Mlhoj%2F29GyD82U1bLLTyCFbb5FVO41Bq%2B9n6aSheLwJ1X%2BK86d9xxJ%2Be&X-Amz-Signature=ac32a4b3fd636b880cf88c597eae5c1c9d0dc39644f2e12dd6034c278300230a&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QKOLX2NI%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T222341Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIGlzCH8bhIqI0d%2Fy5bLq6H7peVMEgd6iiicwhVFCEV2EAiBvrGYXQImWeQDNNH8M%2BhkDRwVHj60ic1%2FXolbaGS6ONiqIBAjF%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMseyFQ2bg1rRijZLSKtwDGeBowAdTbSTHyR7JccAVSnZNoENvx90I%2BnA90ymeHLSVBOTAQo8FKAdFp7V6BFR8ewxpB0CEzhInBW2kw5mk5hFTlXmS0zbDy%2BooYa5AckZ%2BJ%2BSyjQa1dOZMlHNolesXn3oFPglgYuvpDKFsWn9h2%2Fm2S5oezXILflSzM1RgUl1Cf7SqHSf0uTdYbAl10xJh4JkcKys8BLhjr9%2FAD9B7rExdsjH%2BW0tokceHXmMsVu9ruVKPqtYSDxCPeJXZcwQPvvdUApotsjirEERyi1HFQO%2BL2ILlcMBr70tMT%2BjqxDMYEBpbE9IrWrfAhBTz9OnAW5nWImoLotNHcNuV66b1z5w441fx4Q2hs4Jo%2FtzUVNKGizSPTEJkBE%2BYu2pHSzEylqo5qxR3aBOm1tPGhCXWMre12mMDEWpyu442%2BbaeDiko89JGYkzGyOI5%2F%2F7dMn1Aq%2Fok9xept%2F7oIpn5Hvqo8hTka%2F8%2FqBwr8M0%2BPaXZIBqVlyjVokjc2xP19cUCNyETpE%2Bp4BqnIFazLW1mtaiWFwKR9uXnF1rUHk34Yp6hg6Ivuo7vRFavAhNUsklnoQW4ufcgMr7NG1G6NvM2UCSMwQ394w3YlAq4L3basnWkHoLr5H1qcGTxis3mS1Uwr43evQY6pgENFdRx47sd9uAl0i02BZlpk4fvLeWMJoAE3QoZFumzlZ4iIV6rLGzNQNrUqQmqHRRFPSf6zmGa5qLNFdxtGRJGsF8Vfs5fguolYHBzDGs%2FH9JB%2BE6ouFEBMe81eIhw8u0mRtk4%2FbN3vqkHn80hGgP74yAZvJBh0JrsIyT8Mlhoj%2F29GyD82U1bLLTyCFbb5FVO41Bq%2B9n6aSheLwJ1X%2BK86d9xxJ%2Be&X-Amz-Signature=693946a4a05224bac42a7f174820d4a220d9b5b143d75f8398b8216b3be00811&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YQ6MK72B%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T222341Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCcbDVU62dzjXrcr5%2BRzEEOey0k3UVaNOWyaF3s1s6IkwIhAIHqolMipddf7M7%2FkB%2FUnB%2FUlhS6UARg0yOzVkT9x9cTKogECMX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igy0kXS%2Fyld86%2Fx%2BRzcq3AMbqMC3Kdaxqi5AMJEXRTXI71LhtO4wiCgOFLcilm84fzMw7m1xRIbaSsQkBT5LTzy0RSDyVrT73HTaH%2F1a%2B2LOmHG4qlpFa6TNm8L%2FtP3uqpMRf3K0oHzYNnCq%2BdFIYQ5FdCjuetQfALUlsGmGNCKwfD8YCeaGQezi7WzR0VVvFxXwHuQzs7t1FFdigPkjMJRxgz3jmCck6p3mZU%2BppOzprcSNAYWV%2FWOst6JwQ8y08K66RFET9RrSlqizmSQqarwN48N7PC9B9bFbI2pRtNrSAgdnU7JtB8Zd%2FKSET%2B4cYzKSuYycX73rJCZaQBzn63eCpmw9ZPiX%2FcWGfoTq1%2BmCas5f9YcVPOiMMlxPIQ6CgJHuWgSFgmpEZBmIJEVtd%2BqpFTbJVUp6GKysUM%2BftNfZgsCJX3uPvV0m3ty683o86IorNIyvThbofgRU3%2F5qr%2Fz3Wo93np%2F6byvrEHP1aLTbxRG02Nw0%2FUZBa%2BxDACbNA1mv5HTViY%2FODhBgETdjqHCYqVJYrE8Zfl%2FZ%2FqYMJTedWUNF6KgPAyF9%2BAhPCTiuqH1weREP64g339lfAmlqH0xRpCaO0Spytpbhx3gt2tRZNoxch6O8hmfiGTYaVi5uaWPOFnJEsdNlA8z3djDsjd69BjqkAQyBw74tBM5ggem5%2BvgCsZJsW2TEm%2BiLZ7isS26Ka0at7a2OgJFfSB7WCyvqu50z3F12Bqj2KuV1k%2FHIVkuUnUlaakj20PD%2B4aUuTh07bDEo74yJLLZa2yPjzUMrBJia%2BzuwBbVq4mLkJYETsweUDJE2IOm9u06gpdT%2FHr%2FL2XVcrrCDZmVM0YC7ZMuR62XpEJaXERv3OLnPD0hSDt7lcw6KgkLu&X-Amz-Signature=8ae89904bd53643e52ebf026af16f13707bf19c67c0fa5b9a99eaeb1101f16b2&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RNNJCXOI%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T222343Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAzo4K0ia6VGoUTezCrcFZhg%2Bc1c5DgGxDSjmAUuvCmSAiAoaRm0lBj9crP0sno60dnCBgHC6FxQvsiZhRE%2FFevyQCqIBAjF%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM5D8m66tApfBWXpR0KtwDuO57xKrIYJ8Mu75R20jKhnzRrSA1RW900i92FCE0Q9lX45XggVpgWYONLS8FbR%2ButJz3dgzuEo8j9qGzlb9ZlI6evmi%2FNL0kCxEA58qYXo9n9smNDy7JPUU7leG8PlwrQduuizalDYIVmBF4I2AmAY2uZqR4rajy%2BhDP2YY%2F3MImh4o7OgN00pbFwc15z3bejAeAAWzv1gNFC%2BGuHtENZHY4ynXEQAvkZ0ArKdw%2BLQCtRZiP3GonljI8JcGoESWYjY7IIs%2F6wLP9W555FV3htkJvnHaTjzjXJB%2FXEqnxzGsFVIAJDkuRh9fIKcNrk0aylUML0dHhqRltDSP9aBjWX4ZM38kdJCDK1jwHRNPgZ4QWExdrqBK83l1a61FcAs0OG47oQUgsuUIDAKxP3TBtPW%2ByL2clt%2BtC6qyeli28vz2Xq6HS2VVNddPQe32QfZ3887p5Stjh9i%2FnyicBlB1wLXV0UjI%2Brl1p82lO36pNho%2Fq7NMKPIrSc46OXKrxLaFx75eTox8gCFR%2FWyzeL1qQUakmsWtubcrRijqWjyNKXX%2B4QBOr2aJ2553cGsHA62HwDb9Illeprd7UhMmXPdH%2BjOeAb9jWFCIj1px%2BHt1UgP%2FrmxYNZa8px2nU6Www843evQY6pgEA1LHrfYklA9KseB%2FS0EYT5t6Lr3JknN40%2Bp9gdV1DbtG4%2BBOh7PPYIml3%2Be76cB9uAXH%2BVCJxbvJFpYEP0vEvQnmuYrPLaOaUX%2F%2BIt72%2F7yMV6A9uzguSEMNdR%2Bko0b6QHld%2Fb9HOkxODwHvN0Z%2FziZ64WLswdLi2FVMENiC%2Bv%2B5xOl82WBBQwoEkGXyZ9vSanpUXe8IM2dfa7l7QoZI1LbOx9j%2BP&X-Amz-Signature=fcc3620ecf80bf67e593d77a54328aaa449b433ff58f02a9877450f67b2fa29e&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QKOLX2NI%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T222341Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIGlzCH8bhIqI0d%2Fy5bLq6H7peVMEgd6iiicwhVFCEV2EAiBvrGYXQImWeQDNNH8M%2BhkDRwVHj60ic1%2FXolbaGS6ONiqIBAjF%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMseyFQ2bg1rRijZLSKtwDGeBowAdTbSTHyR7JccAVSnZNoENvx90I%2BnA90ymeHLSVBOTAQo8FKAdFp7V6BFR8ewxpB0CEzhInBW2kw5mk5hFTlXmS0zbDy%2BooYa5AckZ%2BJ%2BSyjQa1dOZMlHNolesXn3oFPglgYuvpDKFsWn9h2%2Fm2S5oezXILflSzM1RgUl1Cf7SqHSf0uTdYbAl10xJh4JkcKys8BLhjr9%2FAD9B7rExdsjH%2BW0tokceHXmMsVu9ruVKPqtYSDxCPeJXZcwQPvvdUApotsjirEERyi1HFQO%2BL2ILlcMBr70tMT%2BjqxDMYEBpbE9IrWrfAhBTz9OnAW5nWImoLotNHcNuV66b1z5w441fx4Q2hs4Jo%2FtzUVNKGizSPTEJkBE%2BYu2pHSzEylqo5qxR3aBOm1tPGhCXWMre12mMDEWpyu442%2BbaeDiko89JGYkzGyOI5%2F%2F7dMn1Aq%2Fok9xept%2F7oIpn5Hvqo8hTka%2F8%2FqBwr8M0%2BPaXZIBqVlyjVokjc2xP19cUCNyETpE%2Bp4BqnIFazLW1mtaiWFwKR9uXnF1rUHk34Yp6hg6Ivuo7vRFavAhNUsklnoQW4ufcgMr7NG1G6NvM2UCSMwQ394w3YlAq4L3basnWkHoLr5H1qcGTxis3mS1Uwr43evQY6pgENFdRx47sd9uAl0i02BZlpk4fvLeWMJoAE3QoZFumzlZ4iIV6rLGzNQNrUqQmqHRRFPSf6zmGa5qLNFdxtGRJGsF8Vfs5fguolYHBzDGs%2FH9JB%2BE6ouFEBMe81eIhw8u0mRtk4%2FbN3vqkHn80hGgP74yAZvJBh0JrsIyT8Mlhoj%2F29GyD82U1bLLTyCFbb5FVO41Bq%2B9n6aSheLwJ1X%2BK86d9xxJ%2Be&X-Amz-Signature=5209c3e11c2d2b089e068192c469516e6c08a98c822b239d0d9dc0f1af6ce8ee&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QKOLX2NI%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T222341Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIGlzCH8bhIqI0d%2Fy5bLq6H7peVMEgd6iiicwhVFCEV2EAiBvrGYXQImWeQDNNH8M%2BhkDRwVHj60ic1%2FXolbaGS6ONiqIBAjF%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMseyFQ2bg1rRijZLSKtwDGeBowAdTbSTHyR7JccAVSnZNoENvx90I%2BnA90ymeHLSVBOTAQo8FKAdFp7V6BFR8ewxpB0CEzhInBW2kw5mk5hFTlXmS0zbDy%2BooYa5AckZ%2BJ%2BSyjQa1dOZMlHNolesXn3oFPglgYuvpDKFsWn9h2%2Fm2S5oezXILflSzM1RgUl1Cf7SqHSf0uTdYbAl10xJh4JkcKys8BLhjr9%2FAD9B7rExdsjH%2BW0tokceHXmMsVu9ruVKPqtYSDxCPeJXZcwQPvvdUApotsjirEERyi1HFQO%2BL2ILlcMBr70tMT%2BjqxDMYEBpbE9IrWrfAhBTz9OnAW5nWImoLotNHcNuV66b1z5w441fx4Q2hs4Jo%2FtzUVNKGizSPTEJkBE%2BYu2pHSzEylqo5qxR3aBOm1tPGhCXWMre12mMDEWpyu442%2BbaeDiko89JGYkzGyOI5%2F%2F7dMn1Aq%2Fok9xept%2F7oIpn5Hvqo8hTka%2F8%2FqBwr8M0%2BPaXZIBqVlyjVokjc2xP19cUCNyETpE%2Bp4BqnIFazLW1mtaiWFwKR9uXnF1rUHk34Yp6hg6Ivuo7vRFavAhNUsklnoQW4ufcgMr7NG1G6NvM2UCSMwQ394w3YlAq4L3basnWkHoLr5H1qcGTxis3mS1Uwr43evQY6pgENFdRx47sd9uAl0i02BZlpk4fvLeWMJoAE3QoZFumzlZ4iIV6rLGzNQNrUqQmqHRRFPSf6zmGa5qLNFdxtGRJGsF8Vfs5fguolYHBzDGs%2FH9JB%2BE6ouFEBMe81eIhw8u0mRtk4%2FbN3vqkHn80hGgP74yAZvJBh0JrsIyT8Mlhoj%2F29GyD82U1bLLTyCFbb5FVO41Bq%2B9n6aSheLwJ1X%2BK86d9xxJ%2Be&X-Amz-Signature=9afa3a580db7990a4a67bcf081d6814d0ffb0acb9b22bdf3088f5e8bf1ac7f06&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QKOLX2NI%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T222341Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIGlzCH8bhIqI0d%2Fy5bLq6H7peVMEgd6iiicwhVFCEV2EAiBvrGYXQImWeQDNNH8M%2BhkDRwVHj60ic1%2FXolbaGS6ONiqIBAjF%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMseyFQ2bg1rRijZLSKtwDGeBowAdTbSTHyR7JccAVSnZNoENvx90I%2BnA90ymeHLSVBOTAQo8FKAdFp7V6BFR8ewxpB0CEzhInBW2kw5mk5hFTlXmS0zbDy%2BooYa5AckZ%2BJ%2BSyjQa1dOZMlHNolesXn3oFPglgYuvpDKFsWn9h2%2Fm2S5oezXILflSzM1RgUl1Cf7SqHSf0uTdYbAl10xJh4JkcKys8BLhjr9%2FAD9B7rExdsjH%2BW0tokceHXmMsVu9ruVKPqtYSDxCPeJXZcwQPvvdUApotsjirEERyi1HFQO%2BL2ILlcMBr70tMT%2BjqxDMYEBpbE9IrWrfAhBTz9OnAW5nWImoLotNHcNuV66b1z5w441fx4Q2hs4Jo%2FtzUVNKGizSPTEJkBE%2BYu2pHSzEylqo5qxR3aBOm1tPGhCXWMre12mMDEWpyu442%2BbaeDiko89JGYkzGyOI5%2F%2F7dMn1Aq%2Fok9xept%2F7oIpn5Hvqo8hTka%2F8%2FqBwr8M0%2BPaXZIBqVlyjVokjc2xP19cUCNyETpE%2Bp4BqnIFazLW1mtaiWFwKR9uXnF1rUHk34Yp6hg6Ivuo7vRFavAhNUsklnoQW4ufcgMr7NG1G6NvM2UCSMwQ394w3YlAq4L3basnWkHoLr5H1qcGTxis3mS1Uwr43evQY6pgENFdRx47sd9uAl0i02BZlpk4fvLeWMJoAE3QoZFumzlZ4iIV6rLGzNQNrUqQmqHRRFPSf6zmGa5qLNFdxtGRJGsF8Vfs5fguolYHBzDGs%2FH9JB%2BE6ouFEBMe81eIhw8u0mRtk4%2FbN3vqkHn80hGgP74yAZvJBh0JrsIyT8Mlhoj%2F29GyD82U1bLLTyCFbb5FVO41Bq%2B9n6aSheLwJ1X%2BK86d9xxJ%2Be&X-Amz-Signature=ed294a4b5f249d849c092f511891d416420117b419b773a65c968581d2f37f2a&X-Amz-SignedHeaders=host&x-id=GetObject)


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

