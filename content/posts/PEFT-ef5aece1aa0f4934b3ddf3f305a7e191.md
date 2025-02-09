---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466737SIDIB%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250209T191805Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEI%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDfmwoxUvwK2CsEl\
  ImHhmzh6uRReJMHZPIWX96TZcz4UwIgNSyYEI4Z13p9b0O%2FDpNF7Onw3ajbNqy%2FqfmtA5AZYh\
  EqiAQIqP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDBVeK7veNMFl8Rx\
  p8yrcA8lijt5k65bY1KlESMU82vaR0QNnLxEzZ428AFG6KCWnejrsfs97IpgCEU7sKjP8o4VQ4MZl\
  d30b0EvV48ziJp5274cJ1zm5l1VvbyL%2FN%2Ble4BIArPgq4qXp8y90POkN7Yszc2hxvTXuSprh4\
  ELF7YoF2ehuwMphKi7n0vkgsUGOYpp8os3%2F%2FCY4mOnGMFNBz9o7iKUTOhp1Z6px4RTIqLPS5Z\
  gmgh%2FdlCBxAmFWd%2FGXBgsev28ELdy1p5zra%2FkugUhGRXfoQc5o0%2BJSJUJyIJ%2BRB9RSd\
  uxaSvLioIqByC5Www9a9SRboher0yL4EaM3%2FKMyBNXbEHd6zCRARQG%2FBfsV%2FhtVeZ0LBaxa\
  46%2BoEOb24r6M1PgPlhm69SwLUumFVpgy5XfzoC8c%2Bcx8kLu6GjKkA8Qri4aoekKYLrUJiogH8\
  j8lG4ymvfRcc6SqtwoxPBgkR9TptvAbLV3pM07qBim8WROemVfp0OoWLM2%2F4sDnTLpcexCiSgnq\
  M4mc85FtmBSfCqceaVwnmPp%2BQPzDS%2BOo9khAfqCZ9mTNMWZ93cUnD170RgUHiB8F%2FdZ3IFg\
  FQrH8a16Dz6pEKe9gWGf1HFmvHxDhP6%2FZ5EExTQsC8ZVrgUHBCH3LqrJYV0ziMP6Bo70GOqUBcg\
  wwEFjw0UGojyrDWihjhvoeKIz6jE%2BTaoPKdytnOW8C8%2B0u3iIV8TdXcqApR3Bx78W5HMmTdY7\
  B%2FhzqkWZPxuopwU19T14f%2BOaSHNcdCazw5WZcZghcbE%2FZQoHX%2BL495is1htzWWqZzT0Ll\
  zj68wVDyDQxLCslZq88QXAqpSIwI8b99q0c6w1MhuYqFQg9cqrjYYI2bB%2BLatVRSfUmb0sjvrFK\
  C&X-Amz-Signature=e12c10e684fb31bee71b44dc6a03eed7c661449fdabb426b63cc427c9d3\
  7d596&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466YOMNVFXU%2F20250209%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250209T191645Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEI%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGM\
        EQCIE9Qm2t6j4EO1qRy1mjUScsJe6bNUSO5UN%2F7QJENd17FAiAReZkdocVyJtX8LiakvS\
        l57QPtnoKxoVW6NS8rttRbgCqIBAio%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzN\
        zQyMzE4MzgwNSIM5Y5Vst7ZTVq3LGp3KtwD0FEWIUQHFcfTfS84l%2FtIPKYJ7NY5WsNeLP\
        %2FANs1EpsqaZScBPEF7imW3fmUWhzOQmm6EpEemCj%2BcjsQsYgNfRXrTM0iFGzP8p6a8D\
        wTrJtQRfPTLmHMJ8TlfZdmIcdshqfbAyq%2FlGgWKBSPiRbkt7TN1QKYsOAJ4eeURbN%2Bp\
        Wd1zgYRW4zVPUsgBmSLi8sNlsdH32JFgaTmh9DOek6h8ZtddC25AmxJWdVI2Vbprwt%2FhS\
        vMy5GfizuE%2BhQpg9o%2FyTvGIfKHwnu6wA8oEv6I1%2FqmPTucbSJ21vS34moal6qsXgj\
        3rC8wmfObUJQ9OjWYbZFOoVbr5zXSV0cGjfIEVaixh7yDgB%2BH%2BL0sWzNl9SAldkaofC\
        rxoPWTeweVQO2uInuszpjeeMc%2Fz%2BJnHi%2FZyRDmP9F9PsJq8%2FSid7E95nTLl210z\
        Asr2EMV8CvxYPlOwWk5p8PYEKe1u3XUyHUdn22MJBFypvKLSErXl1BYpaII1iokGG8naDOy\
        wHBbhR5%2Bi4nbaEg4WmWwo1gXqZU%2BkaVRLEBROJq0%2Fvywv7ttuzIuAs8XMIRDRxxSK\
        LVf2Gxw%2F3qZA3TVG%2FF3UoavlbV7AEQnC6KAQkG8%2FWKNGt5hc1bVue1zraXZM9salE\
        WEwrf%2BivQY6pgFKveG5ULDYKAsM8VR5NIIaDmQpN%2F5QQvS2fT10MuWaI1anz4xrzp2z\
        0KuTwdfTVoqoEBBZfxmQE23ILtrQB0gieOwsbUpz4%2BbS80AzIxEsElxq%2FSlniX0TyZH\
        3HzScW%2BFn%2F3z2rl2%2Bt1klY0ddty6Gh8iKTq%2F0%2BLs%2FMAv%2BfaY9CTSAcMM6\
        mazbb3YFly9%2FCnDy2wNjWNy8wKn8JyKFJdhgJSNsikD4&X-Amz-Signature=b153e93d\
        fd1d7989a9ccf7b600d1372dabded3bca0b6e24756d2c8c8a12bbab0&X-Amz-SignedHe\
        aders=host&x-id=GetObject"
      expiry_time: "2025-02-09T20:16:45.001Z"
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
UPDATE_TIME: "2025-02-09T19:18:13.417Z"
EXPIRY_TIME: "2025-02-09T20:18:03.737Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZKUI6OR2%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T191804Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEI%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDSrtinh3kEKDA4DnbnAtLqHfhMKYYRWUsjw8jyN7ekfgIgRxTRk%2BVAzN4huPvBz2BtdbTTdP4RFuSCO2jowns1CgsqiAQIqP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNo%2F5sPOKEizsryLnircA6vxv%2BmXD3Q1bu%2F6sIGsfovZ4t4RRzSPBZfdCqRtDW9vYVxQN9iYGNTktCSFOjF3r%2Bezdj9KC0ZcjK6pJQt1Scs3mTiKeXsuP0a1H3fLrPXj%2BJcRRBRl6Otxnf49Xk7bCHxu%2FECfrkVklmTPyynNqki4L4ShuU%2BRganPoJknSoB1Ow1lkitdYX1RkN%2Bb0mg%2FOaRRcxpeL44vkk%2BOzh4rX8ua0MhvoIIuGHSYIPtcpJuuYZTE7ZtEAuNlSFslC%2FYr9j8KjuTR7ZYmVWYGN1qon6vlCX0%2FZtth0mBCVo04H7HMYuai3%2BfXMY32G3NCTtNyLIar8cu2OiSAAyPveOEyD2zNatGtLKQCZ5QF0Mk0HyLIaZhhw%2B0VE6Nj6j6PPEEg%2BtJUXMGHSPb1VT1pEOfOjUQKj86GIkgCcMHQXVPIPBSB%2FB4mz0zwF5ghvXSMQoCw3cluEjswzn%2FhM2LPL%2FJkUAlHN0u4FmI7Gn7DvplXA9lRjUCC%2F%2FXwRsYrJ44zpS1iZqeEqMqvDuBBAMRvrB9yrm5ZYSbdy0QgeyqzLxQCI4sdd4esasLfXvm%2BXv5I4XNF%2FPHe2wAIm0GO8JO0D2reuvdkiU94CsxoaEupcD%2Bdz12ALd8jy82dYx7kYim%2BMJWJo70GOqUBYSWRWNNOAi6lMrScAbARCfCQFZgBwTqfGPO%2FEsFLCUiL1wMKKo79RXLYuOr9eupaowzDGTi%2Bz50NH0xIOqpmMJTSmo%2BZ%2BLZkmSdIpxHPcLaGGFb5VzX6%2B91f0y0ptC%2FxioF%2Fl6zxYihEyz%2FBM14Xe%2BPrjaaJh84ZvSP3%2BJtksD3FowunEFsNWMdIG1Df7Wrqxqz00MLl9wR9PfqRfhPzEWYyQJtH&X-Amz-Signature=2e01ee6f0554a3d875c15b0a442092d0c5410ebbf0f253b3c1957940e9f54e64&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZKUI6OR2%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T191804Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEI%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDSrtinh3kEKDA4DnbnAtLqHfhMKYYRWUsjw8jyN7ekfgIgRxTRk%2BVAzN4huPvBz2BtdbTTdP4RFuSCO2jowns1CgsqiAQIqP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNo%2F5sPOKEizsryLnircA6vxv%2BmXD3Q1bu%2F6sIGsfovZ4t4RRzSPBZfdCqRtDW9vYVxQN9iYGNTktCSFOjF3r%2Bezdj9KC0ZcjK6pJQt1Scs3mTiKeXsuP0a1H3fLrPXj%2BJcRRBRl6Otxnf49Xk7bCHxu%2FECfrkVklmTPyynNqki4L4ShuU%2BRganPoJknSoB1Ow1lkitdYX1RkN%2Bb0mg%2FOaRRcxpeL44vkk%2BOzh4rX8ua0MhvoIIuGHSYIPtcpJuuYZTE7ZtEAuNlSFslC%2FYr9j8KjuTR7ZYmVWYGN1qon6vlCX0%2FZtth0mBCVo04H7HMYuai3%2BfXMY32G3NCTtNyLIar8cu2OiSAAyPveOEyD2zNatGtLKQCZ5QF0Mk0HyLIaZhhw%2B0VE6Nj6j6PPEEg%2BtJUXMGHSPb1VT1pEOfOjUQKj86GIkgCcMHQXVPIPBSB%2FB4mz0zwF5ghvXSMQoCw3cluEjswzn%2FhM2LPL%2FJkUAlHN0u4FmI7Gn7DvplXA9lRjUCC%2F%2FXwRsYrJ44zpS1iZqeEqMqvDuBBAMRvrB9yrm5ZYSbdy0QgeyqzLxQCI4sdd4esasLfXvm%2BXv5I4XNF%2FPHe2wAIm0GO8JO0D2reuvdkiU94CsxoaEupcD%2Bdz12ALd8jy82dYx7kYim%2BMJWJo70GOqUBYSWRWNNOAi6lMrScAbARCfCQFZgBwTqfGPO%2FEsFLCUiL1wMKKo79RXLYuOr9eupaowzDGTi%2Bz50NH0xIOqpmMJTSmo%2BZ%2BLZkmSdIpxHPcLaGGFb5VzX6%2B91f0y0ptC%2FxioF%2Fl6zxYihEyz%2FBM14Xe%2BPrjaaJh84ZvSP3%2BJtksD3FowunEFsNWMdIG1Df7Wrqxqz00MLl9wR9PfqRfhPzEWYyQJtH&X-Amz-Signature=6e788060caa70c8480d50e5a9ccf9fe714cc276891f771d861c23271207dc577&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZKUI6OR2%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T191804Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEI%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDSrtinh3kEKDA4DnbnAtLqHfhMKYYRWUsjw8jyN7ekfgIgRxTRk%2BVAzN4huPvBz2BtdbTTdP4RFuSCO2jowns1CgsqiAQIqP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNo%2F5sPOKEizsryLnircA6vxv%2BmXD3Q1bu%2F6sIGsfovZ4t4RRzSPBZfdCqRtDW9vYVxQN9iYGNTktCSFOjF3r%2Bezdj9KC0ZcjK6pJQt1Scs3mTiKeXsuP0a1H3fLrPXj%2BJcRRBRl6Otxnf49Xk7bCHxu%2FECfrkVklmTPyynNqki4L4ShuU%2BRganPoJknSoB1Ow1lkitdYX1RkN%2Bb0mg%2FOaRRcxpeL44vkk%2BOzh4rX8ua0MhvoIIuGHSYIPtcpJuuYZTE7ZtEAuNlSFslC%2FYr9j8KjuTR7ZYmVWYGN1qon6vlCX0%2FZtth0mBCVo04H7HMYuai3%2BfXMY32G3NCTtNyLIar8cu2OiSAAyPveOEyD2zNatGtLKQCZ5QF0Mk0HyLIaZhhw%2B0VE6Nj6j6PPEEg%2BtJUXMGHSPb1VT1pEOfOjUQKj86GIkgCcMHQXVPIPBSB%2FB4mz0zwF5ghvXSMQoCw3cluEjswzn%2FhM2LPL%2FJkUAlHN0u4FmI7Gn7DvplXA9lRjUCC%2F%2FXwRsYrJ44zpS1iZqeEqMqvDuBBAMRvrB9yrm5ZYSbdy0QgeyqzLxQCI4sdd4esasLfXvm%2BXv5I4XNF%2FPHe2wAIm0GO8JO0D2reuvdkiU94CsxoaEupcD%2Bdz12ALd8jy82dYx7kYim%2BMJWJo70GOqUBYSWRWNNOAi6lMrScAbARCfCQFZgBwTqfGPO%2FEsFLCUiL1wMKKo79RXLYuOr9eupaowzDGTi%2Bz50NH0xIOqpmMJTSmo%2BZ%2BLZkmSdIpxHPcLaGGFb5VzX6%2B91f0y0ptC%2FxioF%2Fl6zxYihEyz%2FBM14Xe%2BPrjaaJh84ZvSP3%2BJtksD3FowunEFsNWMdIG1Df7Wrqxqz00MLl9wR9PfqRfhPzEWYyQJtH&X-Amz-Signature=be33362f0b72d2634cf2e5ed3cdfd589cc2f59797343bc61a6434f1e6e437dbd&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZKUI6OR2%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T191804Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEI%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDSrtinh3kEKDA4DnbnAtLqHfhMKYYRWUsjw8jyN7ekfgIgRxTRk%2BVAzN4huPvBz2BtdbTTdP4RFuSCO2jowns1CgsqiAQIqP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNo%2F5sPOKEizsryLnircA6vxv%2BmXD3Q1bu%2F6sIGsfovZ4t4RRzSPBZfdCqRtDW9vYVxQN9iYGNTktCSFOjF3r%2Bezdj9KC0ZcjK6pJQt1Scs3mTiKeXsuP0a1H3fLrPXj%2BJcRRBRl6Otxnf49Xk7bCHxu%2FECfrkVklmTPyynNqki4L4ShuU%2BRganPoJknSoB1Ow1lkitdYX1RkN%2Bb0mg%2FOaRRcxpeL44vkk%2BOzh4rX8ua0MhvoIIuGHSYIPtcpJuuYZTE7ZtEAuNlSFslC%2FYr9j8KjuTR7ZYmVWYGN1qon6vlCX0%2FZtth0mBCVo04H7HMYuai3%2BfXMY32G3NCTtNyLIar8cu2OiSAAyPveOEyD2zNatGtLKQCZ5QF0Mk0HyLIaZhhw%2B0VE6Nj6j6PPEEg%2BtJUXMGHSPb1VT1pEOfOjUQKj86GIkgCcMHQXVPIPBSB%2FB4mz0zwF5ghvXSMQoCw3cluEjswzn%2FhM2LPL%2FJkUAlHN0u4FmI7Gn7DvplXA9lRjUCC%2F%2FXwRsYrJ44zpS1iZqeEqMqvDuBBAMRvrB9yrm5ZYSbdy0QgeyqzLxQCI4sdd4esasLfXvm%2BXv5I4XNF%2FPHe2wAIm0GO8JO0D2reuvdkiU94CsxoaEupcD%2Bdz12ALd8jy82dYx7kYim%2BMJWJo70GOqUBYSWRWNNOAi6lMrScAbARCfCQFZgBwTqfGPO%2FEsFLCUiL1wMKKo79RXLYuOr9eupaowzDGTi%2Bz50NH0xIOqpmMJTSmo%2BZ%2BLZkmSdIpxHPcLaGGFb5VzX6%2B91f0y0ptC%2FxioF%2Fl6zxYihEyz%2FBM14Xe%2BPrjaaJh84ZvSP3%2BJtksD3FowunEFsNWMdIG1Df7Wrqxqz00MLl9wR9PfqRfhPzEWYyQJtH&X-Amz-Signature=5ba2ab4c81f1f56c614828459fec2283403a6defa04697a48fd8212bd34fb1bc&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZKUI6OR2%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T191804Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEI%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDSrtinh3kEKDA4DnbnAtLqHfhMKYYRWUsjw8jyN7ekfgIgRxTRk%2BVAzN4huPvBz2BtdbTTdP4RFuSCO2jowns1CgsqiAQIqP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNo%2F5sPOKEizsryLnircA6vxv%2BmXD3Q1bu%2F6sIGsfovZ4t4RRzSPBZfdCqRtDW9vYVxQN9iYGNTktCSFOjF3r%2Bezdj9KC0ZcjK6pJQt1Scs3mTiKeXsuP0a1H3fLrPXj%2BJcRRBRl6Otxnf49Xk7bCHxu%2FECfrkVklmTPyynNqki4L4ShuU%2BRganPoJknSoB1Ow1lkitdYX1RkN%2Bb0mg%2FOaRRcxpeL44vkk%2BOzh4rX8ua0MhvoIIuGHSYIPtcpJuuYZTE7ZtEAuNlSFslC%2FYr9j8KjuTR7ZYmVWYGN1qon6vlCX0%2FZtth0mBCVo04H7HMYuai3%2BfXMY32G3NCTtNyLIar8cu2OiSAAyPveOEyD2zNatGtLKQCZ5QF0Mk0HyLIaZhhw%2B0VE6Nj6j6PPEEg%2BtJUXMGHSPb1VT1pEOfOjUQKj86GIkgCcMHQXVPIPBSB%2FB4mz0zwF5ghvXSMQoCw3cluEjswzn%2FhM2LPL%2FJkUAlHN0u4FmI7Gn7DvplXA9lRjUCC%2F%2FXwRsYrJ44zpS1iZqeEqMqvDuBBAMRvrB9yrm5ZYSbdy0QgeyqzLxQCI4sdd4esasLfXvm%2BXv5I4XNF%2FPHe2wAIm0GO8JO0D2reuvdkiU94CsxoaEupcD%2Bdz12ALd8jy82dYx7kYim%2BMJWJo70GOqUBYSWRWNNOAi6lMrScAbARCfCQFZgBwTqfGPO%2FEsFLCUiL1wMKKo79RXLYuOr9eupaowzDGTi%2Bz50NH0xIOqpmMJTSmo%2BZ%2BLZkmSdIpxHPcLaGGFb5VzX6%2B91f0y0ptC%2FxioF%2Fl6zxYihEyz%2FBM14Xe%2BPrjaaJh84ZvSP3%2BJtksD3FowunEFsNWMdIG1Df7Wrqxqz00MLl9wR9PfqRfhPzEWYyQJtH&X-Amz-Signature=d24f9695d67cf4d7cc48970aaf8fd6e877d05cce4c5352221b8ec20818a64b94&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WTAVLK7M%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T191804Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEI%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIGApwXezSIfyjcV2xttilo%2Fxu3aYcRTX25XrIvaM6RBgAiEAjFGn%2FiOon95uCng2iHIUVNd3IX3tkx5h47nQ40Buh9YqiAQIqP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOpmdju2cl5MLXv1GSrcA0D2sAW1PyzI6tIULhyMVn8fWVZ%2FRQakFe%2BvXGSEkd365ubV1j0B2edKds6Y5XDmlZ6cZm8HfCaI1ZJn7tLrZJTgvs8TzNLE%2F8Kl5Kxw2uu1I7HtL46sna0s0QRyeAviM5WAsn0oQZErWOi0IkgVJ9BRmIrz5TTbhb7hXUsDr0djX1vKaTSFRDqARQ%2BxFNBmWkuCd%2BuPF8LQ%2BLYVSQMCdJ5ys22H5BXn5y75%2BSmIfq1fAkBFNGRUDZDQP%2BJPEhAmhYPJtXcjT6lzKBP%2BDk2t8oYad3JllcSj0EidaBTK5VCVPuJq8GU85Mf%2FoOrs4PM9dYU1brKEscT7uzAPGpwxmng3D7S4rd8i%2Bg%2FxwH%2BQGbM3X464P1UJ0l%2Fw08XO%2BlAsYKryNLOp2BeOuBMF3rf8GCJXpiD9jn3UDUUwlXfA5yxYySKIGb9bqRtB%2FGCULHUnoCkA4e%2BTAZrcy%2F8HuuAyffG470qQPLhYaS0gXdSNNBpnQ4Wf3ldMkVqOGlC%2F%2BcjBq2um4xsXJ8GUjnmXRyewVlEL%2B2DKjO4QtTtk6B13cqCTQpHgQYyRcVW9o3SEbn5%2F4K1C36X7Utnuf0jvvaKXxnR2gVN8qDrHtqiFm6Iyv4NlADH2TIwHX76mfDksMPGGo70GOqUBTw3%2FGClD1%2BFX0jOhP6uiI%2FQoQDR%2Bw1o%2FuadAbSwXIGzbnaluArLB6RCcaGvo5Khz6gbppePyA8qKP%2B2aoF7vVOhei2KiWyTMbPnAnNsIdcbeQbbW6KObJi0bua5vd8oj7a%2FzDVMhsUkiFX22a5OEGsRFGNfEP2UeHJcbwwqBbt0kQ5SK08VKml0W9BYRy9ZZ%2Fw2fjD0wQIzy%2BoLaYjBYnmrgsnvS&X-Amz-Signature=fa507d3c299c86c28bec17e7a6e40072a932c63cf8a48fbfdcc1b56fdaa9a415&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46642PB4YUT%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T191805Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEI%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCSD093wKbWuES314UWuu68BwalGuy6ZSyobbpBUOwKygIgGVd4FWMvNGNFP0b%2BrlU8QI5Hpxw6UpvGU2n%2B6xfqvZkqiAQIqP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLHRKrIjfKUv9F1%2FXCrcAwHaVvCq7pXeg6UnBW0d21h%2BG5XhGwoQJAF2CtBI18ST0rq7oMC5P%2BO6PRvBNmDpqqkzcuMo6mitqH7vMKo%2FF7%2FRCU9Db0MNH8qapphExljB4HSyuL2eJGG%2BCwBAv3MQYpqsQLNwC9T5UgWDZZYxkZMDqCdgur%2BvbGWufrbFXFT682I9YCyVfjP0d668FZz39NMXURTjEV3IUTuOzxPn%2B%2B07xPcgoZuqnT1Lw1BsGuiONB0kts3oE6%2FrMjZx5e%2B6BaUnOYL2zld1rqTw%2BdtWkO7nTZSIh3Vh9Y7g3uRmnlE8ln1qaGk1%2B6n%2BcjvEoHOQthUs48AQQ%2BPcZ2h%2BEU91aCm7G6tuc0FuANegYAL4Ku0p7T6HK0vg8TAheZ0QK5hr87VxokgcrpYvOJCS%2FNetcit%2Ftd55rOOrz2aOIXhPoz7yFi5YJDUm3y3hmNL3pChDP2o0F9By%2FNpDlw2%2FlIGEKlwlky%2FTmKnKloWW1xxTbDhUHWn7b5DAISpVcxJZy%2BZI2KDBoN8Jrd5UiVPgzkBJ7NAwZQVKUevQ%2F3QOSubgZ0x2O6Y%2B6B5VbPY2hL5EWSiQhUxNYFA685WbhqxuWPkUF4BS9lBi0xcnRxQl3HuF%2BNv3duqPpi1DdOUAaBekMP2Bo70GOqUB1Xf5sIZ%2FWQAAc5OIZbxrMMPv6LjEpz78rL%2BG5kf4ypTobxd%2BpnOhYJjCpW89hOifvyhy%2F1xILnBppk0fQsxeweoGIAKhiCTdPypZzHVZzM5ZCxhoi%2F18F9h6R42L2KaKXfGU%2BEbOshLEs7b6UhS8mhmxGZOpSno9%2FH0MEoiPkmFvdT3Ut2qsAdrPufMt3xlXEDPohEljuvyLmCRTzCrfAAqVIPgr&X-Amz-Signature=6fde27130d0dc2e3f5e539fea92a37d5476f59df789d603bbf1c6584780c069a&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZKUI6OR2%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T191804Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEI%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDSrtinh3kEKDA4DnbnAtLqHfhMKYYRWUsjw8jyN7ekfgIgRxTRk%2BVAzN4huPvBz2BtdbTTdP4RFuSCO2jowns1CgsqiAQIqP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNo%2F5sPOKEizsryLnircA6vxv%2BmXD3Q1bu%2F6sIGsfovZ4t4RRzSPBZfdCqRtDW9vYVxQN9iYGNTktCSFOjF3r%2Bezdj9KC0ZcjK6pJQt1Scs3mTiKeXsuP0a1H3fLrPXj%2BJcRRBRl6Otxnf49Xk7bCHxu%2FECfrkVklmTPyynNqki4L4ShuU%2BRganPoJknSoB1Ow1lkitdYX1RkN%2Bb0mg%2FOaRRcxpeL44vkk%2BOzh4rX8ua0MhvoIIuGHSYIPtcpJuuYZTE7ZtEAuNlSFslC%2FYr9j8KjuTR7ZYmVWYGN1qon6vlCX0%2FZtth0mBCVo04H7HMYuai3%2BfXMY32G3NCTtNyLIar8cu2OiSAAyPveOEyD2zNatGtLKQCZ5QF0Mk0HyLIaZhhw%2B0VE6Nj6j6PPEEg%2BtJUXMGHSPb1VT1pEOfOjUQKj86GIkgCcMHQXVPIPBSB%2FB4mz0zwF5ghvXSMQoCw3cluEjswzn%2FhM2LPL%2FJkUAlHN0u4FmI7Gn7DvplXA9lRjUCC%2F%2FXwRsYrJ44zpS1iZqeEqMqvDuBBAMRvrB9yrm5ZYSbdy0QgeyqzLxQCI4sdd4esasLfXvm%2BXv5I4XNF%2FPHe2wAIm0GO8JO0D2reuvdkiU94CsxoaEupcD%2Bdz12ALd8jy82dYx7kYim%2BMJWJo70GOqUBYSWRWNNOAi6lMrScAbARCfCQFZgBwTqfGPO%2FEsFLCUiL1wMKKo79RXLYuOr9eupaowzDGTi%2Bz50NH0xIOqpmMJTSmo%2BZ%2BLZkmSdIpxHPcLaGGFb5VzX6%2B91f0y0ptC%2FxioF%2Fl6zxYihEyz%2FBM14Xe%2BPrjaaJh84ZvSP3%2BJtksD3FowunEFsNWMdIG1Df7Wrqxqz00MLl9wR9PfqRfhPzEWYyQJtH&X-Amz-Signature=7b2c6c7c07db34010cd74cb4751606aea57acb506275dcb067c589f47db7b12b&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZKUI6OR2%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T191804Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEI%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDSrtinh3kEKDA4DnbnAtLqHfhMKYYRWUsjw8jyN7ekfgIgRxTRk%2BVAzN4huPvBz2BtdbTTdP4RFuSCO2jowns1CgsqiAQIqP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNo%2F5sPOKEizsryLnircA6vxv%2BmXD3Q1bu%2F6sIGsfovZ4t4RRzSPBZfdCqRtDW9vYVxQN9iYGNTktCSFOjF3r%2Bezdj9KC0ZcjK6pJQt1Scs3mTiKeXsuP0a1H3fLrPXj%2BJcRRBRl6Otxnf49Xk7bCHxu%2FECfrkVklmTPyynNqki4L4ShuU%2BRganPoJknSoB1Ow1lkitdYX1RkN%2Bb0mg%2FOaRRcxpeL44vkk%2BOzh4rX8ua0MhvoIIuGHSYIPtcpJuuYZTE7ZtEAuNlSFslC%2FYr9j8KjuTR7ZYmVWYGN1qon6vlCX0%2FZtth0mBCVo04H7HMYuai3%2BfXMY32G3NCTtNyLIar8cu2OiSAAyPveOEyD2zNatGtLKQCZ5QF0Mk0HyLIaZhhw%2B0VE6Nj6j6PPEEg%2BtJUXMGHSPb1VT1pEOfOjUQKj86GIkgCcMHQXVPIPBSB%2FB4mz0zwF5ghvXSMQoCw3cluEjswzn%2FhM2LPL%2FJkUAlHN0u4FmI7Gn7DvplXA9lRjUCC%2F%2FXwRsYrJ44zpS1iZqeEqMqvDuBBAMRvrB9yrm5ZYSbdy0QgeyqzLxQCI4sdd4esasLfXvm%2BXv5I4XNF%2FPHe2wAIm0GO8JO0D2reuvdkiU94CsxoaEupcD%2Bdz12ALd8jy82dYx7kYim%2BMJWJo70GOqUBYSWRWNNOAi6lMrScAbARCfCQFZgBwTqfGPO%2FEsFLCUiL1wMKKo79RXLYuOr9eupaowzDGTi%2Bz50NH0xIOqpmMJTSmo%2BZ%2BLZkmSdIpxHPcLaGGFb5VzX6%2B91f0y0ptC%2FxioF%2Fl6zxYihEyz%2FBM14Xe%2BPrjaaJh84ZvSP3%2BJtksD3FowunEFsNWMdIG1Df7Wrqxqz00MLl9wR9PfqRfhPzEWYyQJtH&X-Amz-Signature=d5e82e109347658ecc75b09e718a16caeb3451be7c05aeb8423bc9d4f963f426&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZKUI6OR2%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T191804Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEI%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDSrtinh3kEKDA4DnbnAtLqHfhMKYYRWUsjw8jyN7ekfgIgRxTRk%2BVAzN4huPvBz2BtdbTTdP4RFuSCO2jowns1CgsqiAQIqP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNo%2F5sPOKEizsryLnircA6vxv%2BmXD3Q1bu%2F6sIGsfovZ4t4RRzSPBZfdCqRtDW9vYVxQN9iYGNTktCSFOjF3r%2Bezdj9KC0ZcjK6pJQt1Scs3mTiKeXsuP0a1H3fLrPXj%2BJcRRBRl6Otxnf49Xk7bCHxu%2FECfrkVklmTPyynNqki4L4ShuU%2BRganPoJknSoB1Ow1lkitdYX1RkN%2Bb0mg%2FOaRRcxpeL44vkk%2BOzh4rX8ua0MhvoIIuGHSYIPtcpJuuYZTE7ZtEAuNlSFslC%2FYr9j8KjuTR7ZYmVWYGN1qon6vlCX0%2FZtth0mBCVo04H7HMYuai3%2BfXMY32G3NCTtNyLIar8cu2OiSAAyPveOEyD2zNatGtLKQCZ5QF0Mk0HyLIaZhhw%2B0VE6Nj6j6PPEEg%2BtJUXMGHSPb1VT1pEOfOjUQKj86GIkgCcMHQXVPIPBSB%2FB4mz0zwF5ghvXSMQoCw3cluEjswzn%2FhM2LPL%2FJkUAlHN0u4FmI7Gn7DvplXA9lRjUCC%2F%2FXwRsYrJ44zpS1iZqeEqMqvDuBBAMRvrB9yrm5ZYSbdy0QgeyqzLxQCI4sdd4esasLfXvm%2BXv5I4XNF%2FPHe2wAIm0GO8JO0D2reuvdkiU94CsxoaEupcD%2Bdz12ALd8jy82dYx7kYim%2BMJWJo70GOqUBYSWRWNNOAi6lMrScAbARCfCQFZgBwTqfGPO%2FEsFLCUiL1wMKKo79RXLYuOr9eupaowzDGTi%2Bz50NH0xIOqpmMJTSmo%2BZ%2BLZkmSdIpxHPcLaGGFb5VzX6%2B91f0y0ptC%2FxioF%2Fl6zxYihEyz%2FBM14Xe%2BPrjaaJh84ZvSP3%2BJtksD3FowunEFsNWMdIG1Df7Wrqxqz00MLl9wR9PfqRfhPzEWYyQJtH&X-Amz-Signature=b7916eefac048c8bb7c8d71a11fa1fe892b06ed11d0ba5e9d481ad21360c2fde&X-Amz-SignedHeaders=host&x-id=GetObject)


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

