---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4665ALTNPYK%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250221T112046Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEKr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDpjtBgfgkpZU8o1ZO\
  hW3WyUfq9%2BeLRJOEVPThzuT4fMwIhAOF%2FmsIs7qht2E%2BAh6LtAKhiG8gWx8mhZ4eQHxBNug\
  G1KogECNP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzCWjImjiU7Twp\
  xJnQq3AP%2FDjK88u2USZbDq5gxfe0gFiv4KdYyRi1C%2FqcnDZGxWdGf4IcCyk34jdusaNfoqC1Z\
  ZDUpLT6KhcetaBStS2%2BT1ZynRHT%2FVoU1wKHAlvQ%2BvJH0V3NPrX2rGzdNXLuFUEvkk1HhRIt\
  jk1jBLi1rPs0cydvlshJanPNvUF5TU4IKE3cvM2BGt9dCh8uj0HmC0RcaqRA0kmBmoThsDwgdCjtQ\
  jn%2BO%2B%2F39lqADU38XmMYWy0TMCFK%2FhCG%2F%2FTQbhZeRQm1pKyTyO8EnM%2BCVfxMKKCV\
  6%2BG6QkC7oTayCx3SaRfqy9G1dClmtzmR1E6nS7fyHOu6lVFtUrVMpL60kjtuF78KNR05jxbLBdw\
  RI8iyHUvY6HK48LZwksDlb12ngpueuec4lTAJVRsddDa5a78Z%2B55k%2B%2FV%2FTSf6zF5D%2Ff\
  z4Gn09BUrnwc0PFyppz6yi%2BHqw9vb3gypCDO%2FS7H7SNWG9XVPX3zTEZr4c4P0hVgx%2FpfguV\
  loowFGD%2Ff5QLe9Q%2BRi4zQuVieAHOnqPIbj9xbCD8Xx9cuJ4MXKpoMXzn0Kw7d%2BwMw2Qzx0v\
  vvX5y%2FeozYQP7OeksWHxWPxAxcTfo3LpCSuFlkjhcIjDoeyKjeF2lH1Zd%2BK8SxrNuYSREHeq3\
  4DDimOG9BjqkATP2d6zCRwY90lpIq4QqFLDfSgg8ylXaAuzuaPvL0sAkf3yzfRNYIFEZEDHTv%2Bb\
  jKkDpd28OKwAlzUJgLeHFogpxH6R5jH6VWFUAnyGUVOQd6QBq77TqSOQklIwdKZRekqapiK%2BVN%\
  2FFFlCx8Bidb1bQDlD7Fagkw4OgF2sYazKPtlRqjC5bw%2FvPWPkSEpTW%2Fq6OFSkSFPYjKQhCHi\
  bkBTsSeEKPN&X-Amz-Signature=212fe1416453c8f2f0127241d46db4049ad05075b92517545\
  4cbe6b6a5da0be4&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466RWSSR7Z7%2F20250221%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250221T111932Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEKr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIQCgHfYcO13dmyhmTWZSMkdbigxp4oAMzeIySTHgK%2FXceQIgBkemhnKBsDCE3f649ZMT\
        ogRcBGCgihcuMLu1tIJwrLwqiAQI0%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2M\
        zc0MjMxODM4MDUiDNKUpQl%2FTl4ai%2FunnCrcA7NkEpRoosuddNhPoOh4EMzr2P%2BuJ4\
        7hwbUcsnprVqpuYultQHqi%2BESW0cE7BgMIjCFpVSmJFYqCfRnLsVUeE7AHVfLGuNaopJp\
        giEeodgTvcgM4GyuKro4NpWAQ40xe88Ex5PLp9soLj1O0ItXsirNSUIPK4F4I9iccFCfY1x\
        wjHNuspuHC%2BzjMxjzTncG9UREg2eNa8OTuEhZ%2FpDMZXObYkdmsDiDQUDrzX%2BykMzg\
        FEnWqko%2FzSC90qAlO7qpG%2B2ThLR5tPcE2O0%2FUncQE7qusC9VXe9pn1H4EpmUDXE2p\
        v1m6VHq6eb0hDQjWGSlOoAm%2BUceh2Ovb%2BXk%2FUdjLrVtb1p7x5VMgVcryog2NnYrRJ\
        TWrP7w2BnDidzf%2Fw87ITRtpjcpqSecgfgPKy92sNP6BfGhEk4TBFOxzWTITESFFUTXyJL\
        RiyPC2sDyOKOR7rJRmQq8Qtf5LmcugUlEaMcGr9NpZ30OTXNKeVgIE1yYyS%2B%2Bn6ATNa\
        u%2By74nuaU8bx8eagR%2FvtxKQ5GRLXtBuZ3flk0YoIoCNZJXDSX0SeafcN4Cc3CSfckyj\
        e7PJfL08Rfx7iSvb9viwNHq4Vh5OH85n6JdyfHRdn8z3IGZC7tbjESqVNlj4hU9Zs8mLMJG\
        Z4b0GOqUBciNQ%2BQkJyEXgPT1ax1JV7L1sbI8tBzo8evahr8MkgT62saOomIncZEGBEWdz\
        sGmVuKKvAPCpoxhk9F7O0BX8W%2Fv26mYAaMC10KUxR%2BB1dguociKJOSOcLyRr1HcFUQL\
        J7%2FLkhmWhZp3MP6AsDrbLYcmk0Suf79wqChY8gvV%2BMgy6zHiouuIRddGaQQGieKoZH%\
        2BdqX%2BsVsMkkCVIMcHPyx%2BmR6lFY&X-Amz-Signature=e2f4d1773a557bb12a7236\
        dcd930b7cd8353596ecc55d7e0486c781ff7561a3c&X-Amz-SignedHeaders=host&x-i\
        d=GetObject"
      expiry_time: "2025-02-21T12:19:31.989Z"
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
UPDATE_TIME: "2025-02-21T11:20:51.687Z"
EXPIRY_TIME: "2025-02-21T12:20:42.705Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666WIRTZTT%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T112043Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCw1HUvE%2FUsov21r37Y0Sa3L54Q5s%2BVkBG6IFlGMa9rNQIgJTTq6AcniVzVwV8SHVeXdoLUHhqZP9vCP32TjzrVIwUqiAQI0%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDq5o7xYeFZE930LpircA7PIuITQZMK%2FKB%2B9ZjqGwcOKdh8mf7X0N0tipHKVYZSIiStaZFlv%2B%2BilgR3TYF42lPRalUNsjzMwusI86x880EWsWc3GQl2vPjCbIukoSxV99m2klZo9fKIX19AlvzE8%2BsQDnacogiVJsf627ttY3bm7ZWEWkP5t7sGQJULmWY%2Boy9zFj%2FKixMERH%2Be9q90I9hC4K1%2Bv5liBW51jbmUMd%2B0MV8GoEwaKA0a%2BOSH0IZW6Y8POSRaHRMvSHdFnKT%2BvJcLTcJxcaUbY8y3EM9WV6sc7qUm6KsXq%2Bx4DClgFgrwuTj4KfPo7mABzfOsly%2FzG19dsYSD1WOSYskTZyGFaA8hc8bn3L2rN8SA0wnZkPRZd9Wy3Z8immzpYFJ%2FwgcDqN9Dnu3utxxkpGdc8jiyqUTmc5IlGqaw6QTB2p%2FTLcIXPQs1mGnE1OkVH0Xs7RcNQkxaUGONuk3whT3WavoN%2BYVHT4PPqCniMvmeYyg00btqZG6GD7DABrQ1nlYbIVW6eZRyz%2FGf85%2B%2FFkuJbhR7WD2b0ta6FFkuPMFZTuMg1ch%2BtMFVwIx21UeheuG9mMbhr%2FIq%2BvhX7F%2BuHheAXDYYtSUvH9jSHtOkohTU2aSFojEj2pdY1TR2qphVTjWwNMOGY4b0GOqUBlFATHK8COv8KU7jl1ju%2FWoU6IZmjgDLLkxWllWo6CVH6IuDjIAU6mrpfSeO4D3rIfP0KU3vEgd3JSi%2BYBtLvj9himz72t6H1OZPeknODJbn98HO14cxf0WShzQa6U3lyWIlhQtX60Ve7U5RRB1VStZt9HG7PHN0vHGJWQQZvRVm5fXx1SxvIsM6dUEPEDCx4iKa1sf4M%2F9h2q2aVN%2BbtK%2FmmgDiA&X-Amz-Signature=02ac9d39e78729f02fdd41a59ed043ffe407e73838888131420f71492614f06d&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666WIRTZTT%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T112043Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCw1HUvE%2FUsov21r37Y0Sa3L54Q5s%2BVkBG6IFlGMa9rNQIgJTTq6AcniVzVwV8SHVeXdoLUHhqZP9vCP32TjzrVIwUqiAQI0%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDq5o7xYeFZE930LpircA7PIuITQZMK%2FKB%2B9ZjqGwcOKdh8mf7X0N0tipHKVYZSIiStaZFlv%2B%2BilgR3TYF42lPRalUNsjzMwusI86x880EWsWc3GQl2vPjCbIukoSxV99m2klZo9fKIX19AlvzE8%2BsQDnacogiVJsf627ttY3bm7ZWEWkP5t7sGQJULmWY%2Boy9zFj%2FKixMERH%2Be9q90I9hC4K1%2Bv5liBW51jbmUMd%2B0MV8GoEwaKA0a%2BOSH0IZW6Y8POSRaHRMvSHdFnKT%2BvJcLTcJxcaUbY8y3EM9WV6sc7qUm6KsXq%2Bx4DClgFgrwuTj4KfPo7mABzfOsly%2FzG19dsYSD1WOSYskTZyGFaA8hc8bn3L2rN8SA0wnZkPRZd9Wy3Z8immzpYFJ%2FwgcDqN9Dnu3utxxkpGdc8jiyqUTmc5IlGqaw6QTB2p%2FTLcIXPQs1mGnE1OkVH0Xs7RcNQkxaUGONuk3whT3WavoN%2BYVHT4PPqCniMvmeYyg00btqZG6GD7DABrQ1nlYbIVW6eZRyz%2FGf85%2B%2FFkuJbhR7WD2b0ta6FFkuPMFZTuMg1ch%2BtMFVwIx21UeheuG9mMbhr%2FIq%2BvhX7F%2BuHheAXDYYtSUvH9jSHtOkohTU2aSFojEj2pdY1TR2qphVTjWwNMOGY4b0GOqUBlFATHK8COv8KU7jl1ju%2FWoU6IZmjgDLLkxWllWo6CVH6IuDjIAU6mrpfSeO4D3rIfP0KU3vEgd3JSi%2BYBtLvj9himz72t6H1OZPeknODJbn98HO14cxf0WShzQa6U3lyWIlhQtX60Ve7U5RRB1VStZt9HG7PHN0vHGJWQQZvRVm5fXx1SxvIsM6dUEPEDCx4iKa1sf4M%2F9h2q2aVN%2BbtK%2FmmgDiA&X-Amz-Signature=c95b1bb115a92d0d209a2b81946365a14096e4303df5d14f06c30f30ef5c79b2&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666WIRTZTT%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T112043Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCw1HUvE%2FUsov21r37Y0Sa3L54Q5s%2BVkBG6IFlGMa9rNQIgJTTq6AcniVzVwV8SHVeXdoLUHhqZP9vCP32TjzrVIwUqiAQI0%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDq5o7xYeFZE930LpircA7PIuITQZMK%2FKB%2B9ZjqGwcOKdh8mf7X0N0tipHKVYZSIiStaZFlv%2B%2BilgR3TYF42lPRalUNsjzMwusI86x880EWsWc3GQl2vPjCbIukoSxV99m2klZo9fKIX19AlvzE8%2BsQDnacogiVJsf627ttY3bm7ZWEWkP5t7sGQJULmWY%2Boy9zFj%2FKixMERH%2Be9q90I9hC4K1%2Bv5liBW51jbmUMd%2B0MV8GoEwaKA0a%2BOSH0IZW6Y8POSRaHRMvSHdFnKT%2BvJcLTcJxcaUbY8y3EM9WV6sc7qUm6KsXq%2Bx4DClgFgrwuTj4KfPo7mABzfOsly%2FzG19dsYSD1WOSYskTZyGFaA8hc8bn3L2rN8SA0wnZkPRZd9Wy3Z8immzpYFJ%2FwgcDqN9Dnu3utxxkpGdc8jiyqUTmc5IlGqaw6QTB2p%2FTLcIXPQs1mGnE1OkVH0Xs7RcNQkxaUGONuk3whT3WavoN%2BYVHT4PPqCniMvmeYyg00btqZG6GD7DABrQ1nlYbIVW6eZRyz%2FGf85%2B%2FFkuJbhR7WD2b0ta6FFkuPMFZTuMg1ch%2BtMFVwIx21UeheuG9mMbhr%2FIq%2BvhX7F%2BuHheAXDYYtSUvH9jSHtOkohTU2aSFojEj2pdY1TR2qphVTjWwNMOGY4b0GOqUBlFATHK8COv8KU7jl1ju%2FWoU6IZmjgDLLkxWllWo6CVH6IuDjIAU6mrpfSeO4D3rIfP0KU3vEgd3JSi%2BYBtLvj9himz72t6H1OZPeknODJbn98HO14cxf0WShzQa6U3lyWIlhQtX60Ve7U5RRB1VStZt9HG7PHN0vHGJWQQZvRVm5fXx1SxvIsM6dUEPEDCx4iKa1sf4M%2F9h2q2aVN%2BbtK%2FmmgDiA&X-Amz-Signature=b31992f76817f64c9a639e180d355f470fce2449c687cf2bb0974dd1ea6480d4&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666WIRTZTT%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T112043Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCw1HUvE%2FUsov21r37Y0Sa3L54Q5s%2BVkBG6IFlGMa9rNQIgJTTq6AcniVzVwV8SHVeXdoLUHhqZP9vCP32TjzrVIwUqiAQI0%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDq5o7xYeFZE930LpircA7PIuITQZMK%2FKB%2B9ZjqGwcOKdh8mf7X0N0tipHKVYZSIiStaZFlv%2B%2BilgR3TYF42lPRalUNsjzMwusI86x880EWsWc3GQl2vPjCbIukoSxV99m2klZo9fKIX19AlvzE8%2BsQDnacogiVJsf627ttY3bm7ZWEWkP5t7sGQJULmWY%2Boy9zFj%2FKixMERH%2Be9q90I9hC4K1%2Bv5liBW51jbmUMd%2B0MV8GoEwaKA0a%2BOSH0IZW6Y8POSRaHRMvSHdFnKT%2BvJcLTcJxcaUbY8y3EM9WV6sc7qUm6KsXq%2Bx4DClgFgrwuTj4KfPo7mABzfOsly%2FzG19dsYSD1WOSYskTZyGFaA8hc8bn3L2rN8SA0wnZkPRZd9Wy3Z8immzpYFJ%2FwgcDqN9Dnu3utxxkpGdc8jiyqUTmc5IlGqaw6QTB2p%2FTLcIXPQs1mGnE1OkVH0Xs7RcNQkxaUGONuk3whT3WavoN%2BYVHT4PPqCniMvmeYyg00btqZG6GD7DABrQ1nlYbIVW6eZRyz%2FGf85%2B%2FFkuJbhR7WD2b0ta6FFkuPMFZTuMg1ch%2BtMFVwIx21UeheuG9mMbhr%2FIq%2BvhX7F%2BuHheAXDYYtSUvH9jSHtOkohTU2aSFojEj2pdY1TR2qphVTjWwNMOGY4b0GOqUBlFATHK8COv8KU7jl1ju%2FWoU6IZmjgDLLkxWllWo6CVH6IuDjIAU6mrpfSeO4D3rIfP0KU3vEgd3JSi%2BYBtLvj9himz72t6H1OZPeknODJbn98HO14cxf0WShzQa6U3lyWIlhQtX60Ve7U5RRB1VStZt9HG7PHN0vHGJWQQZvRVm5fXx1SxvIsM6dUEPEDCx4iKa1sf4M%2F9h2q2aVN%2BbtK%2FmmgDiA&X-Amz-Signature=3ad19fce1866443df84868f2eceba500b4a174e8b16a76032689f3bc70541286&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666WIRTZTT%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T112043Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCw1HUvE%2FUsov21r37Y0Sa3L54Q5s%2BVkBG6IFlGMa9rNQIgJTTq6AcniVzVwV8SHVeXdoLUHhqZP9vCP32TjzrVIwUqiAQI0%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDq5o7xYeFZE930LpircA7PIuITQZMK%2FKB%2B9ZjqGwcOKdh8mf7X0N0tipHKVYZSIiStaZFlv%2B%2BilgR3TYF42lPRalUNsjzMwusI86x880EWsWc3GQl2vPjCbIukoSxV99m2klZo9fKIX19AlvzE8%2BsQDnacogiVJsf627ttY3bm7ZWEWkP5t7sGQJULmWY%2Boy9zFj%2FKixMERH%2Be9q90I9hC4K1%2Bv5liBW51jbmUMd%2B0MV8GoEwaKA0a%2BOSH0IZW6Y8POSRaHRMvSHdFnKT%2BvJcLTcJxcaUbY8y3EM9WV6sc7qUm6KsXq%2Bx4DClgFgrwuTj4KfPo7mABzfOsly%2FzG19dsYSD1WOSYskTZyGFaA8hc8bn3L2rN8SA0wnZkPRZd9Wy3Z8immzpYFJ%2FwgcDqN9Dnu3utxxkpGdc8jiyqUTmc5IlGqaw6QTB2p%2FTLcIXPQs1mGnE1OkVH0Xs7RcNQkxaUGONuk3whT3WavoN%2BYVHT4PPqCniMvmeYyg00btqZG6GD7DABrQ1nlYbIVW6eZRyz%2FGf85%2B%2FFkuJbhR7WD2b0ta6FFkuPMFZTuMg1ch%2BtMFVwIx21UeheuG9mMbhr%2FIq%2BvhX7F%2BuHheAXDYYtSUvH9jSHtOkohTU2aSFojEj2pdY1TR2qphVTjWwNMOGY4b0GOqUBlFATHK8COv8KU7jl1ju%2FWoU6IZmjgDLLkxWllWo6CVH6IuDjIAU6mrpfSeO4D3rIfP0KU3vEgd3JSi%2BYBtLvj9himz72t6H1OZPeknODJbn98HO14cxf0WShzQa6U3lyWIlhQtX60Ve7U5RRB1VStZt9HG7PHN0vHGJWQQZvRVm5fXx1SxvIsM6dUEPEDCx4iKa1sf4M%2F9h2q2aVN%2BbtK%2FmmgDiA&X-Amz-Signature=068fcdd1b9bf9e29d14ce96ee5cf7f665ed39b8c43b890dcd68327867b0b9d7b&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TWOL7J4D%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T112045Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIHJPiok6hF2Akj%2B22v4Tth6sfIrpfprhtUUL2nBEvEghAiA36vd4kzbsZ9rFMAyNN5aWkDJfHnQoXpTabbzh7sv2ECqIBAjT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMqNjAm5vhZs3hn0fvKtwDlX5h%2FqiGFcm9IDaPi%2Bz0OXe%2Fj9iNMSyrq9IT3%2BjOM56MeZDh0dYydJliJRmcnp35WdSNWByMRVHXfcAYRuiS9%2F5UiGnEYVUy3rVAUF11GXivpPHZPL2MpoqPFOTqE9KVZo4oVkLobhLHPkbgiH8TrTVjNxTq7gjoPHrqb%2F855jrdvW5jlHsDVvJhsm9xMzDCbZ4F1nZzrFc8MQKxpDe7V7aMIgEXWrXzttO2lVkk%2BAsG%2BSWShkvrXC%2FyggP0mQ6EWHTQouOpTkdo1wNe66Xn6EMHn8tp2%2B%2FDjDWn3a%2FE5Z5FuUnQGVt%2BqbaSj1VDYkHgXtTKg2gJ6hs7Byb8kYJV3qYakiOxxrVR97HluJm9hTEkLQE6aTSaRxzTbtUpz37OL%2FqQ31sJMMdPwJzezv2AWXQopwDDI0tA3yDIfamEGFJiz7dJGFIz89aclfhOUeV0Q80GUXdid6J4wZAtxK1at04sPHVkt8nAoypQU0hfLOJuBSPTGGmqem7Thg9m2%2Fkdgi%2BD5tMtQMA%2F4S9IrsktgINSMkoTWSNGHqoXpvyvU3uASnL7IQrL4wzTbGblfBn9MLPjIHjPk8B8GtgHf1Ce35I4MBULUm7B3o7fzyphKgc08%2BcVcLH68n0qP64w%2FJjhvQY6pgGKnA%2BDmX0k3Z09X1Lj2GB1kgpQPqZIo2xVBv88orwN4b8NamQOfWlT0ciwtywnlgUvHCNlwARGieC057SEPtrBwB%2BoQRQa55ukZ27eZtZQKpoBPtZ2i9hMNX9AbfWCq9GPIN9pDUuWeNIQRyjV186x%2B%2F8hNT1h1ztvALf80KkqQwufW3BLJPE%2FrugGvl4t41CqT%2BHotcTfXbKXP5N5qivwAn61yfN6&X-Amz-Signature=4f2b1a61e7e85497bbcf97138c6ba5f0aec3d049bf6ff15ba3874ee9c9765f21&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SGR2IC3H%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T112046Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIEvBr3r6yymQ7LiKveBUMEZ5GlK8J6NlEgiOklPW4OvgAiEAkKnaWXc%2FgOhinRZzcUtTGu7xPOauTef3pQBaJ8uEwYMqiAQI0%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDAkR%2FXonuurIFp94JSrcA7gFcrOmpnXjAuTU8lkr%2Blu6l7jkPKkgDCxxvu4YDx1SjpdD2VxosrM2FjGSm9IZqhcEl8B%2FDg4mXX5XS7NxVmhCEnyiWsrio%2Bx1tdt8JrKSnmQvSnS8eGGR9fugCI903HY3Br55lD7aO%2FMJhZmYJVyZiHYtbnSJ2Fyt6HNmQKWDBLRZEYcfD9sLlhyjtLVeoWXW4c6KYppKzfpd4qDibksIkNucH4GW8yT%2BCv664V0ACDYRZTFm%2BY%2Bie18J25ZgZn%2Fwo8BGEsolf%2FnHA2j3RZslUmNPUT2KUNgPA3wxD%2BPG23kseOHL4q8v1Ep8KvCWzKKvK1ViX3LGTdWuEK29ipUJGr8OKbpjcLdMzONAJAcfa9RguJzxR0JR0xOx2l6OLLAwhNUVF5qEmSHNjdhu1vO4rYTxRK7qLVyuO8PKszFt9BwFZ%2B3rLBoE2YIZ7tFGB5v6x7A0YnL%2BBGQUMVUArSFTxOJSbceapJyyyvxIFVepgxC4exqVT%2BAhFnvRWm6J9a4dIStDyTdRV6lHmhB6cItNZnhDqY3GdkD%2B5kHhhIqBsVSRje4ycACOmzNtfJpILxu2Yx2FYaKVsnQSZnwbKsQnLYCGfa4cWh1GrSan9pXDmy3AkpPkbmYDyAL2MJeZ4b0GOqUB1mZ%2B9MfOUb62X9wkY0CFLOWkvSTuKvA55HUW8UgmjILWZHDLzBbdk6f5N4NpwYEmc%2FFvPumAgVDuReARoABcKSNxpQ7qe3We5hjKV1vE0bhEIl%2FMIMcW62hZhtj0PgmtkFs5IV1F%2FMZqOVU3R2gwAHcEywjYs3BRgVOfV7JdfecyaF0QACcHuYEccUpRr6AC1wTPl5crcLj%2BKD074whLwvbarnnb&X-Amz-Signature=576a39416328ee5f6824672b99f693de7afd3d06c11ef78c299f0c5412beb5f3&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666WIRTZTT%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T112043Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCw1HUvE%2FUsov21r37Y0Sa3L54Q5s%2BVkBG6IFlGMa9rNQIgJTTq6AcniVzVwV8SHVeXdoLUHhqZP9vCP32TjzrVIwUqiAQI0%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDq5o7xYeFZE930LpircA7PIuITQZMK%2FKB%2B9ZjqGwcOKdh8mf7X0N0tipHKVYZSIiStaZFlv%2B%2BilgR3TYF42lPRalUNsjzMwusI86x880EWsWc3GQl2vPjCbIukoSxV99m2klZo9fKIX19AlvzE8%2BsQDnacogiVJsf627ttY3bm7ZWEWkP5t7sGQJULmWY%2Boy9zFj%2FKixMERH%2Be9q90I9hC4K1%2Bv5liBW51jbmUMd%2B0MV8GoEwaKA0a%2BOSH0IZW6Y8POSRaHRMvSHdFnKT%2BvJcLTcJxcaUbY8y3EM9WV6sc7qUm6KsXq%2Bx4DClgFgrwuTj4KfPo7mABzfOsly%2FzG19dsYSD1WOSYskTZyGFaA8hc8bn3L2rN8SA0wnZkPRZd9Wy3Z8immzpYFJ%2FwgcDqN9Dnu3utxxkpGdc8jiyqUTmc5IlGqaw6QTB2p%2FTLcIXPQs1mGnE1OkVH0Xs7RcNQkxaUGONuk3whT3WavoN%2BYVHT4PPqCniMvmeYyg00btqZG6GD7DABrQ1nlYbIVW6eZRyz%2FGf85%2B%2FFkuJbhR7WD2b0ta6FFkuPMFZTuMg1ch%2BtMFVwIx21UeheuG9mMbhr%2FIq%2BvhX7F%2BuHheAXDYYtSUvH9jSHtOkohTU2aSFojEj2pdY1TR2qphVTjWwNMOGY4b0GOqUBlFATHK8COv8KU7jl1ju%2FWoU6IZmjgDLLkxWllWo6CVH6IuDjIAU6mrpfSeO4D3rIfP0KU3vEgd3JSi%2BYBtLvj9himz72t6H1OZPeknODJbn98HO14cxf0WShzQa6U3lyWIlhQtX60Ve7U5RRB1VStZt9HG7PHN0vHGJWQQZvRVm5fXx1SxvIsM6dUEPEDCx4iKa1sf4M%2F9h2q2aVN%2BbtK%2FmmgDiA&X-Amz-Signature=f9c19e0d80a4ff681e865d512930d3a1f36c050d8cdc7d52eee8eeb4bdaf314e&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666WIRTZTT%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T112043Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCw1HUvE%2FUsov21r37Y0Sa3L54Q5s%2BVkBG6IFlGMa9rNQIgJTTq6AcniVzVwV8SHVeXdoLUHhqZP9vCP32TjzrVIwUqiAQI0%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDq5o7xYeFZE930LpircA7PIuITQZMK%2FKB%2B9ZjqGwcOKdh8mf7X0N0tipHKVYZSIiStaZFlv%2B%2BilgR3TYF42lPRalUNsjzMwusI86x880EWsWc3GQl2vPjCbIukoSxV99m2klZo9fKIX19AlvzE8%2BsQDnacogiVJsf627ttY3bm7ZWEWkP5t7sGQJULmWY%2Boy9zFj%2FKixMERH%2Be9q90I9hC4K1%2Bv5liBW51jbmUMd%2B0MV8GoEwaKA0a%2BOSH0IZW6Y8POSRaHRMvSHdFnKT%2BvJcLTcJxcaUbY8y3EM9WV6sc7qUm6KsXq%2Bx4DClgFgrwuTj4KfPo7mABzfOsly%2FzG19dsYSD1WOSYskTZyGFaA8hc8bn3L2rN8SA0wnZkPRZd9Wy3Z8immzpYFJ%2FwgcDqN9Dnu3utxxkpGdc8jiyqUTmc5IlGqaw6QTB2p%2FTLcIXPQs1mGnE1OkVH0Xs7RcNQkxaUGONuk3whT3WavoN%2BYVHT4PPqCniMvmeYyg00btqZG6GD7DABrQ1nlYbIVW6eZRyz%2FGf85%2B%2FFkuJbhR7WD2b0ta6FFkuPMFZTuMg1ch%2BtMFVwIx21UeheuG9mMbhr%2FIq%2BvhX7F%2BuHheAXDYYtSUvH9jSHtOkohTU2aSFojEj2pdY1TR2qphVTjWwNMOGY4b0GOqUBlFATHK8COv8KU7jl1ju%2FWoU6IZmjgDLLkxWllWo6CVH6IuDjIAU6mrpfSeO4D3rIfP0KU3vEgd3JSi%2BYBtLvj9himz72t6H1OZPeknODJbn98HO14cxf0WShzQa6U3lyWIlhQtX60Ve7U5RRB1VStZt9HG7PHN0vHGJWQQZvRVm5fXx1SxvIsM6dUEPEDCx4iKa1sf4M%2F9h2q2aVN%2BbtK%2FmmgDiA&X-Amz-Signature=a69416e7b29dfa29aba8ccc5e7788df600893b4944870e7569ad7582ea4fa7c0&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666WIRTZTT%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T112043Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCw1HUvE%2FUsov21r37Y0Sa3L54Q5s%2BVkBG6IFlGMa9rNQIgJTTq6AcniVzVwV8SHVeXdoLUHhqZP9vCP32TjzrVIwUqiAQI0%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDq5o7xYeFZE930LpircA7PIuITQZMK%2FKB%2B9ZjqGwcOKdh8mf7X0N0tipHKVYZSIiStaZFlv%2B%2BilgR3TYF42lPRalUNsjzMwusI86x880EWsWc3GQl2vPjCbIukoSxV99m2klZo9fKIX19AlvzE8%2BsQDnacogiVJsf627ttY3bm7ZWEWkP5t7sGQJULmWY%2Boy9zFj%2FKixMERH%2Be9q90I9hC4K1%2Bv5liBW51jbmUMd%2B0MV8GoEwaKA0a%2BOSH0IZW6Y8POSRaHRMvSHdFnKT%2BvJcLTcJxcaUbY8y3EM9WV6sc7qUm6KsXq%2Bx4DClgFgrwuTj4KfPo7mABzfOsly%2FzG19dsYSD1WOSYskTZyGFaA8hc8bn3L2rN8SA0wnZkPRZd9Wy3Z8immzpYFJ%2FwgcDqN9Dnu3utxxkpGdc8jiyqUTmc5IlGqaw6QTB2p%2FTLcIXPQs1mGnE1OkVH0Xs7RcNQkxaUGONuk3whT3WavoN%2BYVHT4PPqCniMvmeYyg00btqZG6GD7DABrQ1nlYbIVW6eZRyz%2FGf85%2B%2FFkuJbhR7WD2b0ta6FFkuPMFZTuMg1ch%2BtMFVwIx21UeheuG9mMbhr%2FIq%2BvhX7F%2BuHheAXDYYtSUvH9jSHtOkohTU2aSFojEj2pdY1TR2qphVTjWwNMOGY4b0GOqUBlFATHK8COv8KU7jl1ju%2FWoU6IZmjgDLLkxWllWo6CVH6IuDjIAU6mrpfSeO4D3rIfP0KU3vEgd3JSi%2BYBtLvj9himz72t6H1OZPeknODJbn98HO14cxf0WShzQa6U3lyWIlhQtX60Ve7U5RRB1VStZt9HG7PHN0vHGJWQQZvRVm5fXx1SxvIsM6dUEPEDCx4iKa1sf4M%2F9h2q2aVN%2BbtK%2FmmgDiA&X-Amz-Signature=219da3d677a44c3db70ea5e6b3926d6331118724c7b9d0686700f5d8609a1de2&X-Amz-SignedHeaders=host&x-id=GetObject)


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

