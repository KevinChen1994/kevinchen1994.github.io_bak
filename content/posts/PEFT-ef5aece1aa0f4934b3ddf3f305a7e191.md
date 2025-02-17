---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466Z7G4A2ET%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250217T015125Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEEEaCXVzLXdlc3QtMiJHMEUCIB4e8ZcSWhDAUGKNnENoEgDXa1F7z2MMvRaLEQrK04UIAiEAqiO\
  RbyBfVeYqLvSAyz4ongbDkZ5hoCaEn8ZCvnI2fMAq%2FwMIahAAGgw2Mzc0MjMxODM4MDUiDIFM4V\
  ZbPwAJ2U99PCrcA7WHHULy2xGmgmZmi4k5PnR1MqLWUaiScD9MSTBf4sDvCOXs9lkGvceHUHg62GA\
  TMW9Xcgz4GmhVcZSyON3zkgfWNEI6utwj3LCTZEC6NsCK8EinUC0Erksav97mD6G%2FN6CVqbFRFu\
  tSJ5jJFV1jCdCdW6gjegOkJHiETpxWTTDKZGInZBEO0aLOZCuS%2FcwkSx%2FRWtdKhwf7ZS5glKt\
  r%2B9dRcREfjV1z2Nx8wfP7aG4%2BGVE%2B6Qpda0HIZhq9CN%2FhnqBECYEDOsOuwao%2FG9esE1\
  ug3S7cEOWBBcvW1QFuzbIcS6WKWCJY0bcb4Z27I0bkhCiks7%2FXfwsNdriqcc4WSY%2F8qLOEgx%\
  2FzWA5zKFT9wgwsx4vbq8tpAm48IeKBgcK%2Fv6LpQg5%2BBWO8SXEG%2B0udZTNOS4aoZX2dta1s\
  FTAgVXdTqhIr%2ByMgDNwPU%2B%2FiKn0hN%2BMWhrSn4BJOu4EF9BYKn6qtVPwO3kUjWYyMUuwo5\
  7pY1HlOVBAPfTESF7me8fUcXmjtXhuo%2F%2BEKTeVaYp1DD9%2Bc%2BQxaWHJIU2UMaNV6lTZSSf\
  W5HSM5mC6L4UIo4m0cXtBgP3MsLN%2Bt9%2B2b94R%2B86gWaZqbiFd7xxXB7IwP26Z1onjX4Ac4z\
  J6kFQbHMNabyr0GOqUByxfINl%2F1mm5aDUx0Vxfynvd1oRlYB0lCYt1DG0rG7zoZdUELYwfSBACQ\
  2TuDhp81Np0rmTuhFtKGN8WmLfT8TcfDZ%2FIsfp2J2kU%2FcNTK0MPzR3Qimbm3KLpDGOgr6VJao\
  f0Q1mHsUdT%2Bk%2FU56%2F%2BCikepj%2F8mnXamnTuitZ4HzfU6%2F5Q4pg%2BpspVwQTyT0oS3\
  jjwGH9PZGLrapNtQ%2B9zLq3F9CJDr&X-Amz-Signature=3e6d463ea7e9d56fbdc1d3e83a6f8c\
  36bdb6f7ba056c3ae8eaffecb6fc67086f&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466USMZHB4G%2F20250217%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250217T014959Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJGMEQCIDNSK3jehjHBkj%2BT3f7QgEvGG6rXj\
        LtOG4kidlqKsgyHAiA1UlMYe8dn%2Bt%2FUyI2FGj1mONXQoYHrxzxSGEbbK75%2BEir%2F\
        AwhqEAAaDDYzNzQyMzE4MzgwNSIMLfhVjdbJTWGG218yKtwDBBSA4W7HYThjt3%2FX4%2Fw\
        KZa0TrzIYL8nuOd76Oixw0WTA9QiibFJM4DYjAexZAO6U%2FLZWb6uvHu%2B0w%2F9JZY8F\
        hWrO8jY61S9uYKyvOQZo25P0ffaxAlO7pGFhvVgBKKg7rr8lqjBJ1iAhUmc3ljjgva6%2F0\
        T5smHApVBwRMappFQ1KSr0OMKLJckZ0NchC82JGqorg7Nq32FWRGFIOVRP0IS7UsvG5wLwk\
        hPbcjCuthLjY0I%2F8X3RVR1kh6Rmb%2FtHedw7%2BD08TDSXVDgb7v6m5Zkks3dtl2LQHA\
        IlMvMcxBSa5DneUaQO7vDcSJMrdsr6pQo5YOdWTToFWOp%2BGfgAzl%2BbPcTxzUP5HH8%2\
        FHsonSHAzWJd2NqyAtB72KkjmvBlHZ6sjNJu8SjyWaII%2FRrA5pVmpxSbwzX3z3lAq%2Be\
        JMSD%2F2cpmeEhb68miTs%2FDDpyZR%2BOUq5HABCjEXa3WpTymDgfRBUB3vwo9d94ttT4N\
        yDyIkhYl5mVL1L3J5C6sLZssf%2FIeHNXMu%2F%2FeXFL0AYhWPhOMJ%2BWupzAjq%2FsTk\
        D3tTAXHPJAqCMboyhJLDhrkAUOrukAsZ%2FuqOxl1Ytm5iRO25uytwzmMtEQ7dZbpU1moqM\
        INa%2FSoQ%2BMjdXlf70HSQw5ZvKvQY6pgEM5AboUJ8saS1%2BJxKgpnVG7veIPnPyiWo99\
        j2O5vJRnjqewKTYSijnUZ7kb696AtX9HNYmgoaMemShXgPX%2BjhSRxuw41BuRJKG3sUV4b\
        8Chf7It0sZblvOVhAT6qaPKJfWG%2Bg8736HiCZsR22Mdw7RUNb7vVv0i7InEHZdDghhMzn\
        lnCPMqqlYM1KUEl3atyklagLMPNq%2Bt7scaokIquo3E7x9b8Oo&X-Amz-Signature=030\
        afc9e1ccd240ef2b9bfdfe9b3e0e2fd02135b4701a30158456e25aff0109b&X-Amz-Sig\
        nedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-17T02:49:59.076Z"
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
UPDATE_TIME: "2025-02-17T01:51:31.398Z"
EXPIRY_TIME: "2025-02-17T02:51:23.413Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664QH4KSW6%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T015123Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJIMEYCIQCAotkL4Rxnsd8Z8FZhadVpkwZxIGL4eKac88uRfbpsfQIhAM3vrPremsnl1%2BIl7%2BdbTNkygof0SvnKx6MIomawac%2BiKv8DCGoQABoMNjM3NDIzMTgzODA1Igy7sc0se%2BkfYMoG4jsq3AP82kF0IrsG2GaVo6brCox0ADVbffRG3XU533mK4pXmqCuTftkTakqMuu2YoTHtFyAQ0%2FZkOd%2FWX17Kd0ldJzcja62yNB2%2B0YrkDk2Unw%2BddJysIsdKlQm2dYM2zEQW9dw5NhBE40Cz6375guNvPdgyulros26Tol6aSa8jmgHItmYTyYDj295GiXBNty9sl6%2F7jXzkxastBt9rN%2Fw5TPFpp%2B97WKuKAiJF5KgUuBDyu%2FlCGowYEOSHquMXoZkHos0T1S7uXp%2BcqMIYoC3Yyz7XEYJz5Jr3ffi6ZrH5zunnWGEBpjpxKat3kJx0Sp%2Bxq%2FDBI%2BcFdfgXRNlspc0b5rP0N5ev0hs1DHiN9ERYBZxmsZ%2BR7aaW3%2FMSYyxtoCZVQkj64WLnDYJ7LyVL1d7c2YqkpgcOGT8xNv1avXTlP732YajctbOMYCCOepb8aQeQHst6p9ApUX1J8QwTz3sh2Vu3LK0R9EKlOgsvcGF%2Fe3mfzp66bzDMi1mndP%2BQjz3y4qfvHF9rxqFO2hD4RQi59aLlBITe2Dvoz2SfIM76jCvZCeLfroxFQqvyF%2B8ZXECuVTuJ%2FgVZRmfz0VChvRee%2BjWBc5zrlAkiVgcZJ9Tp5IzraU2pSj2%2FyUa1HR7zHTCfm8q9BjqkAdWi4G51k1akeb7TWNp%2BPHlkcqMKHBXGecK5utBIp4kNsu9iJ0YvlnzvjLvoSUwojq7bm3ouqXexZyZE3yegMWP3LElSbhznNyOXMMuJSKGgJzYV0AMhSqDjKamtEqoQ3pQ6REhak%2Fu9n197JwaRvyNn5Vl6JJgw0%2FT4XBonHqzYDtQkzCC6Y7omlzKuyEs5g7lFUSlKY8Ikdygncw4Kww%2F2WT%2BX&X-Amz-Signature=a74ef08da271903a4f90df1a6cf2d2ae6d5012bdf6b5490665dcf59cc678e63c&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664QH4KSW6%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T015123Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJIMEYCIQCAotkL4Rxnsd8Z8FZhadVpkwZxIGL4eKac88uRfbpsfQIhAM3vrPremsnl1%2BIl7%2BdbTNkygof0SvnKx6MIomawac%2BiKv8DCGoQABoMNjM3NDIzMTgzODA1Igy7sc0se%2BkfYMoG4jsq3AP82kF0IrsG2GaVo6brCox0ADVbffRG3XU533mK4pXmqCuTftkTakqMuu2YoTHtFyAQ0%2FZkOd%2FWX17Kd0ldJzcja62yNB2%2B0YrkDk2Unw%2BddJysIsdKlQm2dYM2zEQW9dw5NhBE40Cz6375guNvPdgyulros26Tol6aSa8jmgHItmYTyYDj295GiXBNty9sl6%2F7jXzkxastBt9rN%2Fw5TPFpp%2B97WKuKAiJF5KgUuBDyu%2FlCGowYEOSHquMXoZkHos0T1S7uXp%2BcqMIYoC3Yyz7XEYJz5Jr3ffi6ZrH5zunnWGEBpjpxKat3kJx0Sp%2Bxq%2FDBI%2BcFdfgXRNlspc0b5rP0N5ev0hs1DHiN9ERYBZxmsZ%2BR7aaW3%2FMSYyxtoCZVQkj64WLnDYJ7LyVL1d7c2YqkpgcOGT8xNv1avXTlP732YajctbOMYCCOepb8aQeQHst6p9ApUX1J8QwTz3sh2Vu3LK0R9EKlOgsvcGF%2Fe3mfzp66bzDMi1mndP%2BQjz3y4qfvHF9rxqFO2hD4RQi59aLlBITe2Dvoz2SfIM76jCvZCeLfroxFQqvyF%2B8ZXECuVTuJ%2FgVZRmfz0VChvRee%2BjWBc5zrlAkiVgcZJ9Tp5IzraU2pSj2%2FyUa1HR7zHTCfm8q9BjqkAdWi4G51k1akeb7TWNp%2BPHlkcqMKHBXGecK5utBIp4kNsu9iJ0YvlnzvjLvoSUwojq7bm3ouqXexZyZE3yegMWP3LElSbhznNyOXMMuJSKGgJzYV0AMhSqDjKamtEqoQ3pQ6REhak%2Fu9n197JwaRvyNn5Vl6JJgw0%2FT4XBonHqzYDtQkzCC6Y7omlzKuyEs5g7lFUSlKY8Ikdygncw4Kww%2F2WT%2BX&X-Amz-Signature=3052aa3042670a7b1bb624a0e3cca31a819fc722bad20b1f318d6d076880ece1&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664QH4KSW6%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T015123Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJIMEYCIQCAotkL4Rxnsd8Z8FZhadVpkwZxIGL4eKac88uRfbpsfQIhAM3vrPremsnl1%2BIl7%2BdbTNkygof0SvnKx6MIomawac%2BiKv8DCGoQABoMNjM3NDIzMTgzODA1Igy7sc0se%2BkfYMoG4jsq3AP82kF0IrsG2GaVo6brCox0ADVbffRG3XU533mK4pXmqCuTftkTakqMuu2YoTHtFyAQ0%2FZkOd%2FWX17Kd0ldJzcja62yNB2%2B0YrkDk2Unw%2BddJysIsdKlQm2dYM2zEQW9dw5NhBE40Cz6375guNvPdgyulros26Tol6aSa8jmgHItmYTyYDj295GiXBNty9sl6%2F7jXzkxastBt9rN%2Fw5TPFpp%2B97WKuKAiJF5KgUuBDyu%2FlCGowYEOSHquMXoZkHos0T1S7uXp%2BcqMIYoC3Yyz7XEYJz5Jr3ffi6ZrH5zunnWGEBpjpxKat3kJx0Sp%2Bxq%2FDBI%2BcFdfgXRNlspc0b5rP0N5ev0hs1DHiN9ERYBZxmsZ%2BR7aaW3%2FMSYyxtoCZVQkj64WLnDYJ7LyVL1d7c2YqkpgcOGT8xNv1avXTlP732YajctbOMYCCOepb8aQeQHst6p9ApUX1J8QwTz3sh2Vu3LK0R9EKlOgsvcGF%2Fe3mfzp66bzDMi1mndP%2BQjz3y4qfvHF9rxqFO2hD4RQi59aLlBITe2Dvoz2SfIM76jCvZCeLfroxFQqvyF%2B8ZXECuVTuJ%2FgVZRmfz0VChvRee%2BjWBc5zrlAkiVgcZJ9Tp5IzraU2pSj2%2FyUa1HR7zHTCfm8q9BjqkAdWi4G51k1akeb7TWNp%2BPHlkcqMKHBXGecK5utBIp4kNsu9iJ0YvlnzvjLvoSUwojq7bm3ouqXexZyZE3yegMWP3LElSbhznNyOXMMuJSKGgJzYV0AMhSqDjKamtEqoQ3pQ6REhak%2Fu9n197JwaRvyNn5Vl6JJgw0%2FT4XBonHqzYDtQkzCC6Y7omlzKuyEs5g7lFUSlKY8Ikdygncw4Kww%2F2WT%2BX&X-Amz-Signature=8c8c22f7c5786754ff5a214cefaf4a5f5b623bd46379df290ad0ab54085e669e&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664QH4KSW6%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T015123Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJIMEYCIQCAotkL4Rxnsd8Z8FZhadVpkwZxIGL4eKac88uRfbpsfQIhAM3vrPremsnl1%2BIl7%2BdbTNkygof0SvnKx6MIomawac%2BiKv8DCGoQABoMNjM3NDIzMTgzODA1Igy7sc0se%2BkfYMoG4jsq3AP82kF0IrsG2GaVo6brCox0ADVbffRG3XU533mK4pXmqCuTftkTakqMuu2YoTHtFyAQ0%2FZkOd%2FWX17Kd0ldJzcja62yNB2%2B0YrkDk2Unw%2BddJysIsdKlQm2dYM2zEQW9dw5NhBE40Cz6375guNvPdgyulros26Tol6aSa8jmgHItmYTyYDj295GiXBNty9sl6%2F7jXzkxastBt9rN%2Fw5TPFpp%2B97WKuKAiJF5KgUuBDyu%2FlCGowYEOSHquMXoZkHos0T1S7uXp%2BcqMIYoC3Yyz7XEYJz5Jr3ffi6ZrH5zunnWGEBpjpxKat3kJx0Sp%2Bxq%2FDBI%2BcFdfgXRNlspc0b5rP0N5ev0hs1DHiN9ERYBZxmsZ%2BR7aaW3%2FMSYyxtoCZVQkj64WLnDYJ7LyVL1d7c2YqkpgcOGT8xNv1avXTlP732YajctbOMYCCOepb8aQeQHst6p9ApUX1J8QwTz3sh2Vu3LK0R9EKlOgsvcGF%2Fe3mfzp66bzDMi1mndP%2BQjz3y4qfvHF9rxqFO2hD4RQi59aLlBITe2Dvoz2SfIM76jCvZCeLfroxFQqvyF%2B8ZXECuVTuJ%2FgVZRmfz0VChvRee%2BjWBc5zrlAkiVgcZJ9Tp5IzraU2pSj2%2FyUa1HR7zHTCfm8q9BjqkAdWi4G51k1akeb7TWNp%2BPHlkcqMKHBXGecK5utBIp4kNsu9iJ0YvlnzvjLvoSUwojq7bm3ouqXexZyZE3yegMWP3LElSbhznNyOXMMuJSKGgJzYV0AMhSqDjKamtEqoQ3pQ6REhak%2Fu9n197JwaRvyNn5Vl6JJgw0%2FT4XBonHqzYDtQkzCC6Y7omlzKuyEs5g7lFUSlKY8Ikdygncw4Kww%2F2WT%2BX&X-Amz-Signature=b72708c28b311a522566f67aca5a105e64d667ae7affad76e71dc42c2b3912fb&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664QH4KSW6%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T015123Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJIMEYCIQCAotkL4Rxnsd8Z8FZhadVpkwZxIGL4eKac88uRfbpsfQIhAM3vrPremsnl1%2BIl7%2BdbTNkygof0SvnKx6MIomawac%2BiKv8DCGoQABoMNjM3NDIzMTgzODA1Igy7sc0se%2BkfYMoG4jsq3AP82kF0IrsG2GaVo6brCox0ADVbffRG3XU533mK4pXmqCuTftkTakqMuu2YoTHtFyAQ0%2FZkOd%2FWX17Kd0ldJzcja62yNB2%2B0YrkDk2Unw%2BddJysIsdKlQm2dYM2zEQW9dw5NhBE40Cz6375guNvPdgyulros26Tol6aSa8jmgHItmYTyYDj295GiXBNty9sl6%2F7jXzkxastBt9rN%2Fw5TPFpp%2B97WKuKAiJF5KgUuBDyu%2FlCGowYEOSHquMXoZkHos0T1S7uXp%2BcqMIYoC3Yyz7XEYJz5Jr3ffi6ZrH5zunnWGEBpjpxKat3kJx0Sp%2Bxq%2FDBI%2BcFdfgXRNlspc0b5rP0N5ev0hs1DHiN9ERYBZxmsZ%2BR7aaW3%2FMSYyxtoCZVQkj64WLnDYJ7LyVL1d7c2YqkpgcOGT8xNv1avXTlP732YajctbOMYCCOepb8aQeQHst6p9ApUX1J8QwTz3sh2Vu3LK0R9EKlOgsvcGF%2Fe3mfzp66bzDMi1mndP%2BQjz3y4qfvHF9rxqFO2hD4RQi59aLlBITe2Dvoz2SfIM76jCvZCeLfroxFQqvyF%2B8ZXECuVTuJ%2FgVZRmfz0VChvRee%2BjWBc5zrlAkiVgcZJ9Tp5IzraU2pSj2%2FyUa1HR7zHTCfm8q9BjqkAdWi4G51k1akeb7TWNp%2BPHlkcqMKHBXGecK5utBIp4kNsu9iJ0YvlnzvjLvoSUwojq7bm3ouqXexZyZE3yegMWP3LElSbhznNyOXMMuJSKGgJzYV0AMhSqDjKamtEqoQ3pQ6REhak%2Fu9n197JwaRvyNn5Vl6JJgw0%2FT4XBonHqzYDtQkzCC6Y7omlzKuyEs5g7lFUSlKY8Ikdygncw4Kww%2F2WT%2BX&X-Amz-Signature=6361a02a7baae04bb51d7a3f3f21f31ca568a07fa5c51b85a9380246da5818a7&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466227KVLAY%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T015124Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJHMEUCIHC%2BNUUZiGRxYzx32bwWyMVf43CO0j8wg8k1FY3gms0dAiEA8k%2BKcXmGcGke2L1qA6LN4WoQdK9AG2XzFmq6j82oYb0q%2FwMIahAAGgw2Mzc0MjMxODM4MDUiDLDJu22Avk6%2B49949yrcAzDCodJRpNWpZc0gPU1KOXLSqHOb%2BT0NomjRxBWM7cKop3jHU8l%2FgtEd1wv%2BXm4Tslmr%2Foad2dUyBQL%2B84U7%2BPSbdIE60T6sdEveH7oICbSlB76Z%2Bb%2FijSEkTPXOn6u0Lcm2SlRivW16zGBnoE1wVl0NWOeyGaWohYZUHlZQfx5ZqHqKLKv69mwJBCRs9d3KMQhLxor1Z8xvSNoLLhVsJUddXIRG8eWsRaqqwXUldHozYjZ02k0uYurdc9QPB2BWtsCL4eYj9W5kO6xXGRvRCGgoE1S%2FCcpf6aBwall65nojZJ7d%2FT1znvwB6e1cHM2mT3h8PsqqlwbExDEXyWDStXjVA%2By0bAKyV5gp07A9vhPfUdNadc8AIO8mQiXMFJ7TVBgtKbetJdvRALi8vt1nHxTHT8uJGdtUboBb%2B02ARKbM5oC3IOxrU09sR420Fzv3Rw1dRie6aaL5v2ddzCZ0u2BelYf0TX1threNDQzaWs76nUmN54QwOed3EEJVfTavbi%2FdI7wR4zTPT7mtAYVhlOP%2B8xqLXrYsRwJSCIl3rcpoOCYTs0vqEYzo4exHKtFBYHWfzuAorSHKwA%2Fhn224kM6GMQza27SfVbWg3nSsWIaV3mMHH9OD%2BiL%2FEpvrMO%2Bbyr0GOqUBH4KQftrzLpUG8DEjKJVh%2B%2BRSNGLqY3ec5yQp9hcQQt8mGK8JknTZPDBaNCIrzqBNURsytLzqy%2B2AWwijRvgiwTnqMnC%2FHb2UOnMd%2F197mH2lcNzu5n7EwGDUff1wfJRB9Fy6aA7VNflOt5WXuKcqPS5YxDjGTekoPp1VHaONL3qC2dU9faRdrmhrBlz2GM2RgUAUG%2FsRCbX9pzJVLhgWuAq938f4&X-Amz-Signature=03430e6296726e2f6e0c923100ee84c17b960d4ca27fa714ce57c251a259b04a&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TYLJ476K%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T015124Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJIMEYCIQCcWwI9KbiViaJFte6oCL08L2hFSjwqZb1pJlpS5mlApwIhANy4AlYc1oZkxPoX2s4nlYRc7Bysfa0rS3Bfe%2FO3ZcWaKv8DCGoQABoMNjM3NDIzMTgzODA1IgwlHtq3cY0gF72mFmcq3APCcWOGMP7fR5c77Ei0tpIDNWvzujQWWGVJoFd7OxTbiryYllCEy0h6iBXg2GFNODPv0891QDn0R0zJMvDIU4yHr6drvi%2Fbk6mr8%2Fs96c25ro93Qu8E3IgWJ9UpOQHzIr24PO%2BeXVtFATA9SX%2BCeBP6hfSd4PoyHj8JfY2vZIJbjcHcophXtoj6KfmKGO3ibIj%2B2mE%2BjMRtNu7111z%2BJY2YuUGicIh3N4kjgl%2FqutSTas2wymL9IY6CpyTv8HC75AxFRR%2BEWOSb%2FoS%2FQMMcKtlGZn7%2BcrlVx9iwZMW91RSD4%2Fr7xxMApND2OtHLXt3jW8zx26dEbHomKSoIG9KlF8AHpkK8lp0TkPTIn6TRVuHwORPljc4IF4B6eEZajOCpULLtRJPbhwQlfFQtQt0CHIwChs8hl2DbcwY82VjI8RJ2oYJn39AfzExNlEaVb62N42zr70Iid3LsBVav7R5frqo4h82It0RmPkXhhgKizVgE5G1xpCazusdybMAP0aVhfe%2F%2BV1DtMbQRu8dj0LHvI4FHKn9cxLNQIhB80cHeldj%2FdUPyp8You9yT7PGSauB9a2iZAnb9tAdqNfHlUHjt9buH0Z6nahhcbTvE1s4LmxhJuNjrkaF%2BU4R%2B8ZzC3zDSm8q9BjqkAezK08p4yKSiaDsN3PsQR2YPtyXCihQawX6qXWeYw6%2Flk7m%2Bbae4tytMQyPmykUQuDftbW2anAyKWeHzjXd%2BKqCJMyE5GbbFZh5jOBqXPI4xzrcWfTjkUEdzZ2pXu2atAcG30jXs69zEJHtQpRnDQlV8oAXMb6%2FgH8jFWQJ00%2BqcpVX5oKko26r9HrSJagqfzJ73dv61PZ0Z3CMApq5y9cNjrzk9&X-Amz-Signature=bac2cfebffa77015c80ae4ef726b71c83f74f90fb0718527fce45f42f50fd3a5&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664QH4KSW6%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T015123Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJIMEYCIQCAotkL4Rxnsd8Z8FZhadVpkwZxIGL4eKac88uRfbpsfQIhAM3vrPremsnl1%2BIl7%2BdbTNkygof0SvnKx6MIomawac%2BiKv8DCGoQABoMNjM3NDIzMTgzODA1Igy7sc0se%2BkfYMoG4jsq3AP82kF0IrsG2GaVo6brCox0ADVbffRG3XU533mK4pXmqCuTftkTakqMuu2YoTHtFyAQ0%2FZkOd%2FWX17Kd0ldJzcja62yNB2%2B0YrkDk2Unw%2BddJysIsdKlQm2dYM2zEQW9dw5NhBE40Cz6375guNvPdgyulros26Tol6aSa8jmgHItmYTyYDj295GiXBNty9sl6%2F7jXzkxastBt9rN%2Fw5TPFpp%2B97WKuKAiJF5KgUuBDyu%2FlCGowYEOSHquMXoZkHos0T1S7uXp%2BcqMIYoC3Yyz7XEYJz5Jr3ffi6ZrH5zunnWGEBpjpxKat3kJx0Sp%2Bxq%2FDBI%2BcFdfgXRNlspc0b5rP0N5ev0hs1DHiN9ERYBZxmsZ%2BR7aaW3%2FMSYyxtoCZVQkj64WLnDYJ7LyVL1d7c2YqkpgcOGT8xNv1avXTlP732YajctbOMYCCOepb8aQeQHst6p9ApUX1J8QwTz3sh2Vu3LK0R9EKlOgsvcGF%2Fe3mfzp66bzDMi1mndP%2BQjz3y4qfvHF9rxqFO2hD4RQi59aLlBITe2Dvoz2SfIM76jCvZCeLfroxFQqvyF%2B8ZXECuVTuJ%2FgVZRmfz0VChvRee%2BjWBc5zrlAkiVgcZJ9Tp5IzraU2pSj2%2FyUa1HR7zHTCfm8q9BjqkAdWi4G51k1akeb7TWNp%2BPHlkcqMKHBXGecK5utBIp4kNsu9iJ0YvlnzvjLvoSUwojq7bm3ouqXexZyZE3yegMWP3LElSbhznNyOXMMuJSKGgJzYV0AMhSqDjKamtEqoQ3pQ6REhak%2Fu9n197JwaRvyNn5Vl6JJgw0%2FT4XBonHqzYDtQkzCC6Y7omlzKuyEs5g7lFUSlKY8Ikdygncw4Kww%2F2WT%2BX&X-Amz-Signature=b5c115e876804246ad6f10d6dbc54f709a637e7e8958ee312d1abadaf4a5eef4&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664QH4KSW6%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T015123Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJIMEYCIQCAotkL4Rxnsd8Z8FZhadVpkwZxIGL4eKac88uRfbpsfQIhAM3vrPremsnl1%2BIl7%2BdbTNkygof0SvnKx6MIomawac%2BiKv8DCGoQABoMNjM3NDIzMTgzODA1Igy7sc0se%2BkfYMoG4jsq3AP82kF0IrsG2GaVo6brCox0ADVbffRG3XU533mK4pXmqCuTftkTakqMuu2YoTHtFyAQ0%2FZkOd%2FWX17Kd0ldJzcja62yNB2%2B0YrkDk2Unw%2BddJysIsdKlQm2dYM2zEQW9dw5NhBE40Cz6375guNvPdgyulros26Tol6aSa8jmgHItmYTyYDj295GiXBNty9sl6%2F7jXzkxastBt9rN%2Fw5TPFpp%2B97WKuKAiJF5KgUuBDyu%2FlCGowYEOSHquMXoZkHos0T1S7uXp%2BcqMIYoC3Yyz7XEYJz5Jr3ffi6ZrH5zunnWGEBpjpxKat3kJx0Sp%2Bxq%2FDBI%2BcFdfgXRNlspc0b5rP0N5ev0hs1DHiN9ERYBZxmsZ%2BR7aaW3%2FMSYyxtoCZVQkj64WLnDYJ7LyVL1d7c2YqkpgcOGT8xNv1avXTlP732YajctbOMYCCOepb8aQeQHst6p9ApUX1J8QwTz3sh2Vu3LK0R9EKlOgsvcGF%2Fe3mfzp66bzDMi1mndP%2BQjz3y4qfvHF9rxqFO2hD4RQi59aLlBITe2Dvoz2SfIM76jCvZCeLfroxFQqvyF%2B8ZXECuVTuJ%2FgVZRmfz0VChvRee%2BjWBc5zrlAkiVgcZJ9Tp5IzraU2pSj2%2FyUa1HR7zHTCfm8q9BjqkAdWi4G51k1akeb7TWNp%2BPHlkcqMKHBXGecK5utBIp4kNsu9iJ0YvlnzvjLvoSUwojq7bm3ouqXexZyZE3yegMWP3LElSbhznNyOXMMuJSKGgJzYV0AMhSqDjKamtEqoQ3pQ6REhak%2Fu9n197JwaRvyNn5Vl6JJgw0%2FT4XBonHqzYDtQkzCC6Y7omlzKuyEs5g7lFUSlKY8Ikdygncw4Kww%2F2WT%2BX&X-Amz-Signature=b115b7c8cf2b7f2e39c0571990ed8d3e228023e55398e74f7ca26a24897ff7d4&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664QH4KSW6%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T015123Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJIMEYCIQCAotkL4Rxnsd8Z8FZhadVpkwZxIGL4eKac88uRfbpsfQIhAM3vrPremsnl1%2BIl7%2BdbTNkygof0SvnKx6MIomawac%2BiKv8DCGoQABoMNjM3NDIzMTgzODA1Igy7sc0se%2BkfYMoG4jsq3AP82kF0IrsG2GaVo6brCox0ADVbffRG3XU533mK4pXmqCuTftkTakqMuu2YoTHtFyAQ0%2FZkOd%2FWX17Kd0ldJzcja62yNB2%2B0YrkDk2Unw%2BddJysIsdKlQm2dYM2zEQW9dw5NhBE40Cz6375guNvPdgyulros26Tol6aSa8jmgHItmYTyYDj295GiXBNty9sl6%2F7jXzkxastBt9rN%2Fw5TPFpp%2B97WKuKAiJF5KgUuBDyu%2FlCGowYEOSHquMXoZkHos0T1S7uXp%2BcqMIYoC3Yyz7XEYJz5Jr3ffi6ZrH5zunnWGEBpjpxKat3kJx0Sp%2Bxq%2FDBI%2BcFdfgXRNlspc0b5rP0N5ev0hs1DHiN9ERYBZxmsZ%2BR7aaW3%2FMSYyxtoCZVQkj64WLnDYJ7LyVL1d7c2YqkpgcOGT8xNv1avXTlP732YajctbOMYCCOepb8aQeQHst6p9ApUX1J8QwTz3sh2Vu3LK0R9EKlOgsvcGF%2Fe3mfzp66bzDMi1mndP%2BQjz3y4qfvHF9rxqFO2hD4RQi59aLlBITe2Dvoz2SfIM76jCvZCeLfroxFQqvyF%2B8ZXECuVTuJ%2FgVZRmfz0VChvRee%2BjWBc5zrlAkiVgcZJ9Tp5IzraU2pSj2%2FyUa1HR7zHTCfm8q9BjqkAdWi4G51k1akeb7TWNp%2BPHlkcqMKHBXGecK5utBIp4kNsu9iJ0YvlnzvjLvoSUwojq7bm3ouqXexZyZE3yegMWP3LElSbhznNyOXMMuJSKGgJzYV0AMhSqDjKamtEqoQ3pQ6REhak%2Fu9n197JwaRvyNn5Vl6JJgw0%2FT4XBonHqzYDtQkzCC6Y7omlzKuyEs5g7lFUSlKY8Ikdygncw4Kww%2F2WT%2BX&X-Amz-Signature=2e1bb3da667f05652cf856851f2756808b800545bdaec05e87540793a9acc3fa&X-Amz-SignedHeaders=host&x-id=GetObject)


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

