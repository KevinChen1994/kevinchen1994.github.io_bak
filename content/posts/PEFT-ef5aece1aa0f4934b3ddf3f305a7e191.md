---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB46642X2KX3X%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250221T083026Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEKj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCSeZ9K679e14n7ljA\
  1d1T2Ct83Kbs5hidPn6acUmOe%2BQIhANkbWpjGyQ%2FKqDgrsqSh90K4yaNdID%2FRJ39QYAIDPv\
  30KogECNH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwNzp3EMMPip3M\
  2eQ8q3ANK1caTVhzk6ZA4CsXTAADCtNTwkZLGvoEUJ9vaK7m41IJRy16LDLnxIpcwPJprkrD0IcXe\
  COMJPWVSX7ea9%2FnPpOEmXX9NfLGrl7gICuErpMkpDH%2BG7FykMiXQEbi%2FN6kHCdbmWUGhUhX\
  XxlxBeV669ofg%2B%2F%2BYQOf4DAmpFaU3pq%2B3GKXD5Uv3EL1V5Iq6TOX8ckWNvIkdr6f8DBmh\
  41u%2F9c%2BLda1SIj3gAr17oQDIlYCD4X3DGdBCW8wTDYbHP%2FEMqxIVEeqUi3IvXplg4zcmUH2\
  QAuk8Y9wsVqTZ%2FjYH7vxz%2BfCHXX5m61AD%2BGAVfu5nWxckhQCPUX4hBHEGWDzVsoAfJBKF8g\
  yJKcw%2BQVRO%2BrQDoQ12j49mAOLRpIyoUiURkh4M61CzvR20O2m8m63u2lSyP9hwSRDJXEr6Xe%\
  2BttMCQEaCt9yAw2dFC4te4z9O2oDzjA%2FjQd5ZUWOrsLzwXUkLXZnBb8sL6j852S60iHgOhydFg\
  cMY7U9dIMUOyYWtsAJMQkz7N1GT62vspJ5ibQflhBGguZTVbHQOpPRgZYvs6huRIIbo%2FZfnex9Y\
  GoSrJiexwEiaxdOIuKW4OZsIpK%2BrbYzdoOo0HhPgbg8vkIyrkHc0bg3gSzIUSdTDb3uC9BjqkAe\
  Tn6ROvslyR84Fo48TxjrlCHIMOapbx1h0jxQC463sdkdz0%2FdLUFtxrriFw7hcixMTG2zJFke%2F\
  eCchQozapyI9bCF8oqJtULYS2qoh3dCJkV8vwGl9oI4%2F90RP5ssa9DoG6szeq8Kvnl9zYw0fDq8\
  1pZsCxuUm8J4J0QKW2gxJrGP8%2B7q15NI3UKgY1dlnvWRueBzVm2h8ioRhHvA34j8Hy%2FpjC&X-\
  Amz-Signature=f10a55df35ba1ae1643202d2b2abd5170072c5ccaba4fcbc8b7f56018be84d0\
  7&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4665STAT5OQ%2F20250221%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250221T082833Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEKj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIBG9S5M2yESUVYoISTHWIDJ%2FyHeF7Q7JlJGCtQgbz2FxAiEAuNAJRiXAT4tGsJ2QpxWI\
        GeT9r77xy0regWdpBxg9YnsqiAQI0f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc\
        0MjMxODM4MDUiDH3pVXfBx6L6fExEYCrcAyRoqWBTE5XYGk6X4Lv9%2F0WWF1ZlJb%2Bc8f\
        W3WPYb9fAPkDJmTdlyKSntNxP265ttV%2FPgzLOvWR6VvY0zBOfu%2Ftp9LIwPfD%2FnOpO\
        AEVYoFzlEEaq0O5wFTUTdvUeJA%2Bao1GcisOtICB8ubhbI%2FSgH1ZT7LC8%2BRHkhkuL5\
        0Ux3VI%2FRT%2B%2FcOXizeXqVWM0S5NcHSn5Mk6q2lxbQPxVqcrlpikHyw6xeF5Sel4PE9\
        XL0jqGaX5nLwNpJIhIMkRLuFdJUSiWahVRDE4HGwHYMCWd8nWTkyON5UKvW2%2Fwnjq%2FF\
        EWC%2Fui5dWPmPNUtY2z7W%2BScswLoJi%2FQomGdMyYzqxFdHkGbiV3HwXl%2FjXyftM0d\
        i1GwSqk3rYGoxdsTfk1zGOkdeNUOrZOb%2BY8YAVuQC6ZrU%2FeRdmXvduH%2BwbRMtWUkK\
        z4jz5%2BBy%2FqUIH0TDBw1jIckFWJK5F%2FpIFB%2FM2WyUQDGdgf82InmEx%2FA0XGTq2\
        ywWONcbZf2uZ6lAXGG63AXWAukWG4KkkJhvEuDS4c78WSiEXUTwKQc7LnuVefahBfDehCij\
        Gl1y0YHl8u8WS6OO1FVlWoNteuIz74xlmTzwbtRGil%2FJDAuKofLBKKg3Rxtpw1vsw3CQ0\
        Lfv6rUea9JtMLDe4L0GOqUB5Ix2MoxCwnRyaumt28UqAsKJe3VWKs8ADxwVjiYBcItTKyy6\
        c0h08KXhH0RV14g%2FB39jngzmNKbSQVWVRMfXThHL9i657PDzt1J4rg25TAHy1qk%2B%2F\
        KFcAMTdHd9ppwdLfMTy4hDJv3kcFRNkqrVnYiV19UCliuSkSg4MWSjaW86lARKIV%2BbOCL\
        nG2YroFxn6ysZ63n5QXVlQh8Z%2FakSI7mSR3Ruq&X-Amz-Signature=5a3ea50af740b5\
        328aa168bdb4485925de724a600f2e0d27a48c80f5dfb24ccc&X-Amz-SignedHeaders=\
        host&x-id=GetObject"
      expiry_time: "2025-02-21T09:28:33.629Z"
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
UPDATE_TIME: "2025-02-21T08:30:38.095Z"
EXPIRY_TIME: "2025-02-21T09:30:21.623Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QEQY7TQZ%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T083021Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC3VEZLt2%2B%2B9FDbYUptA4NIIxoBieWVQmoxPBVugdfbIgIhALkQ2%2BekylJbMT470i9XpxH4TB7v%2By18up6nKotsAT9%2BKogECNH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzICPmRPdnwLuM7bYUq3AOFtgM4x%2FwpLIechSOxyenCOlupc0U%2FLlb%2FO6AZNa2yBvJZiEIp3Hc7quibzQM9815haUdxyN25DgfFGdwUhMNK8HR6goRaVlZ6pq1disIi5frB5wUz4OyFQBsx%2Fe0%2BYA4raPC6WONFN79kxSXaTVm9gdZBmjdd5eqqezkcfH3ndQaQc%2Bh1lx2VlRRL4mERkzfUARo2uHnUpZR6Gn90v%2FhInSxR0H9ZWkncCW0z0RckxGPyu2PwKpwzlBpDxvAcfgW7pE9hXVzQqSs2qIKHq%2Fb4AV8lpTQ%2BRr7qslWJf3JCpkm0r%2FJpIO8CtRWeDjT4rzMFNvutS%2BUqmXNiPvVd0G8evD6nEouTbkJkLEsT06Kimn2lIC%2BRP7X5f5quLfGkG17eqiBcLPATPKGe5IXqu%2BlGBwuYUWXDbCRB%2BVPja%2B0rCdUH2sDTUhFMXyqC7lh98jjLZReB7vi5pptn4qe3pzm%2FgQO4pXQkq409gwPJSNSCZQVf1r8%2BjD17KJyR7yaDHyNCInUkRBi%2BgZ%2FCBXdX4DMqAjTeyt5UWDPDV5q4m6jPlTt9n7TFoW8kRlhlh8dF1ODZgVWMxzsQyWBScMU10SiYl0ZFpnouOyM88nRIpgERou1n4xsBgxrbQeWFNTDP3uC9BjqkAVBYmyleKEoLGaHIzGZ1H%2FLCisjGaXLd%2F6ek4%2B%2FI3IspMxol7nbJrVhTvdktKPNkBCGHG3DtXFZ5m7R%2FKJZ6o9pMS9HfUKso2OrhJJCqpy71pT6M6N7CDetEqbstJ32dCulc31e%2BNXKYZb1onlqnupB8yq6xm3L6g4jyS4tQZE4QBfSGE0xRcQn3FJ%2B0IzH2Bm%2FqbE6kwkO4FuCdmqzDfgUZU0oC&X-Amz-Signature=7d9ab56a3a6ca1620617298c97844bcb1d5f480739ccc8ddaa2659b241602719&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QEQY7TQZ%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T083022Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC3VEZLt2%2B%2B9FDbYUptA4NIIxoBieWVQmoxPBVugdfbIgIhALkQ2%2BekylJbMT470i9XpxH4TB7v%2By18up6nKotsAT9%2BKogECNH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzICPmRPdnwLuM7bYUq3AOFtgM4x%2FwpLIechSOxyenCOlupc0U%2FLlb%2FO6AZNa2yBvJZiEIp3Hc7quibzQM9815haUdxyN25DgfFGdwUhMNK8HR6goRaVlZ6pq1disIi5frB5wUz4OyFQBsx%2Fe0%2BYA4raPC6WONFN79kxSXaTVm9gdZBmjdd5eqqezkcfH3ndQaQc%2Bh1lx2VlRRL4mERkzfUARo2uHnUpZR6Gn90v%2FhInSxR0H9ZWkncCW0z0RckxGPyu2PwKpwzlBpDxvAcfgW7pE9hXVzQqSs2qIKHq%2Fb4AV8lpTQ%2BRr7qslWJf3JCpkm0r%2FJpIO8CtRWeDjT4rzMFNvutS%2BUqmXNiPvVd0G8evD6nEouTbkJkLEsT06Kimn2lIC%2BRP7X5f5quLfGkG17eqiBcLPATPKGe5IXqu%2BlGBwuYUWXDbCRB%2BVPja%2B0rCdUH2sDTUhFMXyqC7lh98jjLZReB7vi5pptn4qe3pzm%2FgQO4pXQkq409gwPJSNSCZQVf1r8%2BjD17KJyR7yaDHyNCInUkRBi%2BgZ%2FCBXdX4DMqAjTeyt5UWDPDV5q4m6jPlTt9n7TFoW8kRlhlh8dF1ODZgVWMxzsQyWBScMU10SiYl0ZFpnouOyM88nRIpgERou1n4xsBgxrbQeWFNTDP3uC9BjqkAVBYmyleKEoLGaHIzGZ1H%2FLCisjGaXLd%2F6ek4%2B%2FI3IspMxol7nbJrVhTvdktKPNkBCGHG3DtXFZ5m7R%2FKJZ6o9pMS9HfUKso2OrhJJCqpy71pT6M6N7CDetEqbstJ32dCulc31e%2BNXKYZb1onlqnupB8yq6xm3L6g4jyS4tQZE4QBfSGE0xRcQn3FJ%2B0IzH2Bm%2FqbE6kwkO4FuCdmqzDfgUZU0oC&X-Amz-Signature=acf12a929fa8028e88cd1c27f57e9e3105a88383ceace279812b4af6f321f584&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QEQY7TQZ%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T083022Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC3VEZLt2%2B%2B9FDbYUptA4NIIxoBieWVQmoxPBVugdfbIgIhALkQ2%2BekylJbMT470i9XpxH4TB7v%2By18up6nKotsAT9%2BKogECNH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzICPmRPdnwLuM7bYUq3AOFtgM4x%2FwpLIechSOxyenCOlupc0U%2FLlb%2FO6AZNa2yBvJZiEIp3Hc7quibzQM9815haUdxyN25DgfFGdwUhMNK8HR6goRaVlZ6pq1disIi5frB5wUz4OyFQBsx%2Fe0%2BYA4raPC6WONFN79kxSXaTVm9gdZBmjdd5eqqezkcfH3ndQaQc%2Bh1lx2VlRRL4mERkzfUARo2uHnUpZR6Gn90v%2FhInSxR0H9ZWkncCW0z0RckxGPyu2PwKpwzlBpDxvAcfgW7pE9hXVzQqSs2qIKHq%2Fb4AV8lpTQ%2BRr7qslWJf3JCpkm0r%2FJpIO8CtRWeDjT4rzMFNvutS%2BUqmXNiPvVd0G8evD6nEouTbkJkLEsT06Kimn2lIC%2BRP7X5f5quLfGkG17eqiBcLPATPKGe5IXqu%2BlGBwuYUWXDbCRB%2BVPja%2B0rCdUH2sDTUhFMXyqC7lh98jjLZReB7vi5pptn4qe3pzm%2FgQO4pXQkq409gwPJSNSCZQVf1r8%2BjD17KJyR7yaDHyNCInUkRBi%2BgZ%2FCBXdX4DMqAjTeyt5UWDPDV5q4m6jPlTt9n7TFoW8kRlhlh8dF1ODZgVWMxzsQyWBScMU10SiYl0ZFpnouOyM88nRIpgERou1n4xsBgxrbQeWFNTDP3uC9BjqkAVBYmyleKEoLGaHIzGZ1H%2FLCisjGaXLd%2F6ek4%2B%2FI3IspMxol7nbJrVhTvdktKPNkBCGHG3DtXFZ5m7R%2FKJZ6o9pMS9HfUKso2OrhJJCqpy71pT6M6N7CDetEqbstJ32dCulc31e%2BNXKYZb1onlqnupB8yq6xm3L6g4jyS4tQZE4QBfSGE0xRcQn3FJ%2B0IzH2Bm%2FqbE6kwkO4FuCdmqzDfgUZU0oC&X-Amz-Signature=e5c14a0ae873ea5f8e505ba9210a9262906b389dce4607446cfd158b6a1d9e07&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QEQY7TQZ%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T083022Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC3VEZLt2%2B%2B9FDbYUptA4NIIxoBieWVQmoxPBVugdfbIgIhALkQ2%2BekylJbMT470i9XpxH4TB7v%2By18up6nKotsAT9%2BKogECNH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzICPmRPdnwLuM7bYUq3AOFtgM4x%2FwpLIechSOxyenCOlupc0U%2FLlb%2FO6AZNa2yBvJZiEIp3Hc7quibzQM9815haUdxyN25DgfFGdwUhMNK8HR6goRaVlZ6pq1disIi5frB5wUz4OyFQBsx%2Fe0%2BYA4raPC6WONFN79kxSXaTVm9gdZBmjdd5eqqezkcfH3ndQaQc%2Bh1lx2VlRRL4mERkzfUARo2uHnUpZR6Gn90v%2FhInSxR0H9ZWkncCW0z0RckxGPyu2PwKpwzlBpDxvAcfgW7pE9hXVzQqSs2qIKHq%2Fb4AV8lpTQ%2BRr7qslWJf3JCpkm0r%2FJpIO8CtRWeDjT4rzMFNvutS%2BUqmXNiPvVd0G8evD6nEouTbkJkLEsT06Kimn2lIC%2BRP7X5f5quLfGkG17eqiBcLPATPKGe5IXqu%2BlGBwuYUWXDbCRB%2BVPja%2B0rCdUH2sDTUhFMXyqC7lh98jjLZReB7vi5pptn4qe3pzm%2FgQO4pXQkq409gwPJSNSCZQVf1r8%2BjD17KJyR7yaDHyNCInUkRBi%2BgZ%2FCBXdX4DMqAjTeyt5UWDPDV5q4m6jPlTt9n7TFoW8kRlhlh8dF1ODZgVWMxzsQyWBScMU10SiYl0ZFpnouOyM88nRIpgERou1n4xsBgxrbQeWFNTDP3uC9BjqkAVBYmyleKEoLGaHIzGZ1H%2FLCisjGaXLd%2F6ek4%2B%2FI3IspMxol7nbJrVhTvdktKPNkBCGHG3DtXFZ5m7R%2FKJZ6o9pMS9HfUKso2OrhJJCqpy71pT6M6N7CDetEqbstJ32dCulc31e%2BNXKYZb1onlqnupB8yq6xm3L6g4jyS4tQZE4QBfSGE0xRcQn3FJ%2B0IzH2Bm%2FqbE6kwkO4FuCdmqzDfgUZU0oC&X-Amz-Signature=212c313c2327e11fb3a6e79410dff4343d7dcb4e001015e9cc042d95839ae788&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QEQY7TQZ%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T083022Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC3VEZLt2%2B%2B9FDbYUptA4NIIxoBieWVQmoxPBVugdfbIgIhALkQ2%2BekylJbMT470i9XpxH4TB7v%2By18up6nKotsAT9%2BKogECNH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzICPmRPdnwLuM7bYUq3AOFtgM4x%2FwpLIechSOxyenCOlupc0U%2FLlb%2FO6AZNa2yBvJZiEIp3Hc7quibzQM9815haUdxyN25DgfFGdwUhMNK8HR6goRaVlZ6pq1disIi5frB5wUz4OyFQBsx%2Fe0%2BYA4raPC6WONFN79kxSXaTVm9gdZBmjdd5eqqezkcfH3ndQaQc%2Bh1lx2VlRRL4mERkzfUARo2uHnUpZR6Gn90v%2FhInSxR0H9ZWkncCW0z0RckxGPyu2PwKpwzlBpDxvAcfgW7pE9hXVzQqSs2qIKHq%2Fb4AV8lpTQ%2BRr7qslWJf3JCpkm0r%2FJpIO8CtRWeDjT4rzMFNvutS%2BUqmXNiPvVd0G8evD6nEouTbkJkLEsT06Kimn2lIC%2BRP7X5f5quLfGkG17eqiBcLPATPKGe5IXqu%2BlGBwuYUWXDbCRB%2BVPja%2B0rCdUH2sDTUhFMXyqC7lh98jjLZReB7vi5pptn4qe3pzm%2FgQO4pXQkq409gwPJSNSCZQVf1r8%2BjD17KJyR7yaDHyNCInUkRBi%2BgZ%2FCBXdX4DMqAjTeyt5UWDPDV5q4m6jPlTt9n7TFoW8kRlhlh8dF1ODZgVWMxzsQyWBScMU10SiYl0ZFpnouOyM88nRIpgERou1n4xsBgxrbQeWFNTDP3uC9BjqkAVBYmyleKEoLGaHIzGZ1H%2FLCisjGaXLd%2F6ek4%2B%2FI3IspMxol7nbJrVhTvdktKPNkBCGHG3DtXFZ5m7R%2FKJZ6o9pMS9HfUKso2OrhJJCqpy71pT6M6N7CDetEqbstJ32dCulc31e%2BNXKYZb1onlqnupB8yq6xm3L6g4jyS4tQZE4QBfSGE0xRcQn3FJ%2B0IzH2Bm%2FqbE6kwkO4FuCdmqzDfgUZU0oC&X-Amz-Signature=bc1af179386a140bccc92e34958f00324f4af1d173165f4666fc60b123c96f50&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663E5NU4VG%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T083025Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQC6Yr1UgIZSR8HWDYPrP2TzF6WPkluqTpzirabgklbL%2BAIgFkGaI1Fmxd%2BgC1cRQ0JapDXpTgjXPcnZ2qCXvixg0dkqiAQI0f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPIGcMKPZViqt3hDqCrcAyy9Td9KLRszDPQdj3ua4L2o79b7TvjBPeDl6NcuCry3bLGnO6IbndI3plomawk1OqbyHm5NbV6U4M0oODdOnVZa7TA6jelS7M%2BtHSM%2FAJoOZ1MI%2BIA4NjlgK1aTWM9XvNInFNhX5SU21gDiLXaaf47QzPJK7vA9cddO1%2BQxE1WtvAQEWZeq6jjTs51KSHwH2R1XSrPw7rFzTgjeuyRzJzJkF2314Doa%2FX%2FFQ2cop2eW6P9hy%2FAF041tSFLuhnVJA4GuughCttTCJtgPXRrO5J6%2F%2FpJ30Ab6eRvS1voYtidf%2BSIGmOcqz6QIwok5CFWNUQOFkFa1DuD4b%2Fd3tSN6e75S22wthTBEx2nJqE7Ka68I6D2ty27paON2Q4jHXnzLyt%2B323uNEYVJuuFkas1nPphWDjopyqD3sW75A9o2wwScUo1jbumnEEJhvjEp6NNwDqTJ%2BZQbLC%2Fg%2FviJI%2BqmjsXhvJ2tRdpoZs0bwpd4tDSRViO%2FjJwXvilAM1wq0NxpWyL146uPwhV%2FQ3nBBkJz7N223PssOWt214YZVYfhFm90BB1omLg2quiOGSDpA%2Bcw8SxYYtv8BzyK5UfZnQEHozZIZpmFJDepL6189grSbW7ASYfL4tR54lcJbVYyMOHd4L0GOqUBO0XO5nGlKIX3fubXsWVdUV0Glsh%2FQcQeO5slyxoYP6Nu2qskPk%2B2CzXA1k2V9ZPGrEj4qD5aU55lsfTI8As6DqmoRwqj8svS8O0nK8yQnj5%2BPRnQCGfQFiYft7nb1JWkHDJa5XUMs2N2wO%2FDnlM%2BM8GZXFRXuc9zMrvgHgBqSv4hOW0K1XDTKdkJTuH5Rbkwv5nL2%2FbyK7DN8M3anCcZOEgxweX3&X-Amz-Signature=02c6482d80bdb582ede7fdd4ff2ed5ba8d6a763942fbaa7fba5668c41f1ae195&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662SDTUCZK%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T083026Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCkiYFWfxL19EDdWVyPHUA6FECSqz19aEs%2BurZe1OGy%2BQIgWhMbbVRFjHaE%2FQYTugs%2Bzi7W1znUsva%2BVhleR6j3Mo4qiAQI0f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDF05L2UuSaYuails5yrcA1VmriTA%2FHHBgab3qb59ZCaMcnPTF88RxSuHU78qi0It6gvQy5fujJaFnMua2okz1kHJfsOCzvi0pTfTJHwi7Uk8L4eWwsaxm96MV2evpJ33ZzCdWPU5cx5w%2BLHZGifHo4UIeOLztDNrDCHqE36wAQA%2Fr9bdWNiwq%2B%2FCTHfmk9NdMCJ0Wd%2BIg0vT96ujAHfJ8vybYMDhwgtAYPhuPeD%2BVIXUEdNX%2B%2F7XHW%2Fns6FzO700xR9kpkctnfkNlg9g793wn0NjYXx31Z8dU9kqjtlgLjNdLKzL5TG%2BMDr1GJKW2o5pMNrOFaVpqu8YM8jBHokgNk4ZdlRWsszGshAa%2FKWy4NJK2S484%2BXo92W6oCRjN%2B2BDKdS97ewGTt%2FqsqLOlNX2sZypnz6O07w7Ai%2F7bdVepx75tZvx8obAuhLSWT9gPi7SuNMuRFxB3UpHU%2FSArMOVhxyMVn1M0EmvFkgBRS3tlVeoAevAialqBiU2%2F0D3Sml0rDWU2Gyb8IITDHZLhXisDQmzhwdO26%2FuGTLGlH4hX8EIBRQfibVivaAivltx5LpjjxpJrSb8m2ntApbl6kJljLvbFYZjY0FxfGF%2FyBZ4Geo35EuoCGbqq7RbAjG%2F%2Bdv%2Fa2Z3eniqTtUUJA7MPbd4L0GOqUBjTbl%2FNJcijq0as5rAWTkBy5GQO74g4fngFRs%2F5AKi6l1i8ENwwxo%2Be0Ren8O5ky3VYiBVk7NAIHH2Io7aF7gwFbaZY2pny%2FNklrCl5r4Cg4MWJOp9JCzJS1VEXnY9MFhCwvc3TJI%2BVDLiWzSEyDnS1dJEs34s03bvIknqFzdQM85jzByQgFhARb0KGkG%2FNMM798m16V4kjW2dzgubYRW33cwqauI&X-Amz-Signature=db568cf31c0e51961ab0d2cf0aa7c73d4fb0f1ecc6143567e0dca454bd8f7b21&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QEQY7TQZ%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T083022Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC3VEZLt2%2B%2B9FDbYUptA4NIIxoBieWVQmoxPBVugdfbIgIhALkQ2%2BekylJbMT470i9XpxH4TB7v%2By18up6nKotsAT9%2BKogECNH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzICPmRPdnwLuM7bYUq3AOFtgM4x%2FwpLIechSOxyenCOlupc0U%2FLlb%2FO6AZNa2yBvJZiEIp3Hc7quibzQM9815haUdxyN25DgfFGdwUhMNK8HR6goRaVlZ6pq1disIi5frB5wUz4OyFQBsx%2Fe0%2BYA4raPC6WONFN79kxSXaTVm9gdZBmjdd5eqqezkcfH3ndQaQc%2Bh1lx2VlRRL4mERkzfUARo2uHnUpZR6Gn90v%2FhInSxR0H9ZWkncCW0z0RckxGPyu2PwKpwzlBpDxvAcfgW7pE9hXVzQqSs2qIKHq%2Fb4AV8lpTQ%2BRr7qslWJf3JCpkm0r%2FJpIO8CtRWeDjT4rzMFNvutS%2BUqmXNiPvVd0G8evD6nEouTbkJkLEsT06Kimn2lIC%2BRP7X5f5quLfGkG17eqiBcLPATPKGe5IXqu%2BlGBwuYUWXDbCRB%2BVPja%2B0rCdUH2sDTUhFMXyqC7lh98jjLZReB7vi5pptn4qe3pzm%2FgQO4pXQkq409gwPJSNSCZQVf1r8%2BjD17KJyR7yaDHyNCInUkRBi%2BgZ%2FCBXdX4DMqAjTeyt5UWDPDV5q4m6jPlTt9n7TFoW8kRlhlh8dF1ODZgVWMxzsQyWBScMU10SiYl0ZFpnouOyM88nRIpgERou1n4xsBgxrbQeWFNTDP3uC9BjqkAVBYmyleKEoLGaHIzGZ1H%2FLCisjGaXLd%2F6ek4%2B%2FI3IspMxol7nbJrVhTvdktKPNkBCGHG3DtXFZ5m7R%2FKJZ6o9pMS9HfUKso2OrhJJCqpy71pT6M6N7CDetEqbstJ32dCulc31e%2BNXKYZb1onlqnupB8yq6xm3L6g4jyS4tQZE4QBfSGE0xRcQn3FJ%2B0IzH2Bm%2FqbE6kwkO4FuCdmqzDfgUZU0oC&X-Amz-Signature=99d26c5148bf92924749fbd776e98e62b74e90a591e5f505a21b909a886b819f&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QEQY7TQZ%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T083022Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC3VEZLt2%2B%2B9FDbYUptA4NIIxoBieWVQmoxPBVugdfbIgIhALkQ2%2BekylJbMT470i9XpxH4TB7v%2By18up6nKotsAT9%2BKogECNH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzICPmRPdnwLuM7bYUq3AOFtgM4x%2FwpLIechSOxyenCOlupc0U%2FLlb%2FO6AZNa2yBvJZiEIp3Hc7quibzQM9815haUdxyN25DgfFGdwUhMNK8HR6goRaVlZ6pq1disIi5frB5wUz4OyFQBsx%2Fe0%2BYA4raPC6WONFN79kxSXaTVm9gdZBmjdd5eqqezkcfH3ndQaQc%2Bh1lx2VlRRL4mERkzfUARo2uHnUpZR6Gn90v%2FhInSxR0H9ZWkncCW0z0RckxGPyu2PwKpwzlBpDxvAcfgW7pE9hXVzQqSs2qIKHq%2Fb4AV8lpTQ%2BRr7qslWJf3JCpkm0r%2FJpIO8CtRWeDjT4rzMFNvutS%2BUqmXNiPvVd0G8evD6nEouTbkJkLEsT06Kimn2lIC%2BRP7X5f5quLfGkG17eqiBcLPATPKGe5IXqu%2BlGBwuYUWXDbCRB%2BVPja%2B0rCdUH2sDTUhFMXyqC7lh98jjLZReB7vi5pptn4qe3pzm%2FgQO4pXQkq409gwPJSNSCZQVf1r8%2BjD17KJyR7yaDHyNCInUkRBi%2BgZ%2FCBXdX4DMqAjTeyt5UWDPDV5q4m6jPlTt9n7TFoW8kRlhlh8dF1ODZgVWMxzsQyWBScMU10SiYl0ZFpnouOyM88nRIpgERou1n4xsBgxrbQeWFNTDP3uC9BjqkAVBYmyleKEoLGaHIzGZ1H%2FLCisjGaXLd%2F6ek4%2B%2FI3IspMxol7nbJrVhTvdktKPNkBCGHG3DtXFZ5m7R%2FKJZ6o9pMS9HfUKso2OrhJJCqpy71pT6M6N7CDetEqbstJ32dCulc31e%2BNXKYZb1onlqnupB8yq6xm3L6g4jyS4tQZE4QBfSGE0xRcQn3FJ%2B0IzH2Bm%2FqbE6kwkO4FuCdmqzDfgUZU0oC&X-Amz-Signature=a9fde6a31701fcd8671b67f4884d5226ff0482d2742fe4cc674a8904e8305aeb&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QEQY7TQZ%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T083022Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC3VEZLt2%2B%2B9FDbYUptA4NIIxoBieWVQmoxPBVugdfbIgIhALkQ2%2BekylJbMT470i9XpxH4TB7v%2By18up6nKotsAT9%2BKogECNH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzICPmRPdnwLuM7bYUq3AOFtgM4x%2FwpLIechSOxyenCOlupc0U%2FLlb%2FO6AZNa2yBvJZiEIp3Hc7quibzQM9815haUdxyN25DgfFGdwUhMNK8HR6goRaVlZ6pq1disIi5frB5wUz4OyFQBsx%2Fe0%2BYA4raPC6WONFN79kxSXaTVm9gdZBmjdd5eqqezkcfH3ndQaQc%2Bh1lx2VlRRL4mERkzfUARo2uHnUpZR6Gn90v%2FhInSxR0H9ZWkncCW0z0RckxGPyu2PwKpwzlBpDxvAcfgW7pE9hXVzQqSs2qIKHq%2Fb4AV8lpTQ%2BRr7qslWJf3JCpkm0r%2FJpIO8CtRWeDjT4rzMFNvutS%2BUqmXNiPvVd0G8evD6nEouTbkJkLEsT06Kimn2lIC%2BRP7X5f5quLfGkG17eqiBcLPATPKGe5IXqu%2BlGBwuYUWXDbCRB%2BVPja%2B0rCdUH2sDTUhFMXyqC7lh98jjLZReB7vi5pptn4qe3pzm%2FgQO4pXQkq409gwPJSNSCZQVf1r8%2BjD17KJyR7yaDHyNCInUkRBi%2BgZ%2FCBXdX4DMqAjTeyt5UWDPDV5q4m6jPlTt9n7TFoW8kRlhlh8dF1ODZgVWMxzsQyWBScMU10SiYl0ZFpnouOyM88nRIpgERou1n4xsBgxrbQeWFNTDP3uC9BjqkAVBYmyleKEoLGaHIzGZ1H%2FLCisjGaXLd%2F6ek4%2B%2FI3IspMxol7nbJrVhTvdktKPNkBCGHG3DtXFZ5m7R%2FKJZ6o9pMS9HfUKso2OrhJJCqpy71pT6M6N7CDetEqbstJ32dCulc31e%2BNXKYZb1onlqnupB8yq6xm3L6g4jyS4tQZE4QBfSGE0xRcQn3FJ%2B0IzH2Bm%2FqbE6kwkO4FuCdmqzDfgUZU0oC&X-Amz-Signature=76aa93eabe8ee439c90c06399cac839a2b40529234658216fd860c411d292afd&X-Amz-SignedHeaders=host&x-id=GetObject)


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

