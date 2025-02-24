---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466W7PZJ75I%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250224T033215Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEOj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIFjVg9TQho967JzUWC5\
  HTc6MOxBW9FJLtTbmAgRY1Zf6AiEA4wgiu6xbdGM0lBn7koSMBsdhgXELU3XZHOMfuWb1uVAq%2Fw\
  MIIRAAGgw2Mzc0MjMxODM4MDUiDIfN4oLKFlZkVskmwCrcAwQyEmRVf0nquV%2FvYjKK1h5Lt9OXS\
  PRBjhdXrK6ykrzYOOfiOG2MT0F6rHVUcR0PHcbtueuHE8iDBaIAENoLPfZovj2MuwgaVUpuv2x%2F\
  KqpdHX64PafaMdmbt0NWIjoa6NnkAysQ%2BICa9CKC4Ilpy68FhHdVlt6oayI9nIm345qEhPc3NE%\
  2B7unT97i3j%2FJ5E%2FcrIzJMn9q7HhK%2BvYsu5xYfm1CB3sXbBk4eqiDtnUzQOLmpqmvbq2fxd\
  i5ZQk8QsVBlmuQEqsWnS3T%2ByQv6MgtVo9pymfzL0Z%2BykfNpVijboF%2F%2B%2BxWv3egi%2Fn\
  %2BQ09NWtykumqM9RpUgz9npwHPrblsjfpvDgc46wDIVBhJL%2B9jhxHxgB9Qx5SFQVH2KQPq5Z37\
  vezP7LyGBBfSnlYvIFg58Gp2Zi9Mo%2FnBWPrgQWzN3wejhj4xchau2qdWEfFhqCJFrwS2yUdpxD8\
  0HvChq%2BYziAaGFq6krZoX5w22vE5ah3Ec0T9OJVHDnaphdMCwKvk%2FSJ12ym%2Bw%2BO4%2FXA\
  nsh8JihgbG%2FwREULLIBpueYxXCzkN4rSZMnkiKbonpzJP6YeFdrPvJ6CuOV%2BASKvT1ru553p%\
  2FkeU8kvSHGNsEvNfSRI1xba7FzMOVU2EmvW3MOLx7r0GOqUBHyzCl%2FAUHiAnNVWqxArMyHRUvB\
  PMIdwocrT%2FnGLTs5uxQLoXwXCFMvyki2ZJ6gzFEI6IPMxyDZ95ksB0Gj36cgC15Y6kDaug%2BHk\
  iW2X2tY8Wo%2FryqgpJDHMBARXyRyoqpWbuniIhRfN7egNYRXhRq%2FNm68cTqtGZeZ7KLxzirKDP\
  GBAd3Yk0SQuqA%2FpAgEQnEAB9L%2BE6uJyTUTylf4H89Clyx4Ka&X-Amz-Signature=cd8993e4\
  a66857cf0971a60986da01c2d24341494109fb25aa0b3e69b9cb83e7&X-Amz-SignedHeaders=\
  host&x-id=GetObject"
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
        redential=ASIAZI2LB466RSHHINV3%2F20250224%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250224T033103Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEOj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIQDnUjs4kh1oH50ILrYjHsRo47JHdhujhdPGQqbjFuNJKAIgEQTfSSLSg4MNtfTUjC0T8w\
        2yEWvWkHslFp%2Fsi7rHR8wq%2FwMIIRAAGgw2Mzc0MjMxODM4MDUiDE92NB1wE81f5Cq5n\
        yrcA8RmV0nFBtyWcWdQ5vDGvXc6rh6Hbp%2BmhH3yeqG9y8%2F7vXeqqJv1d21PQbp8sB7r\
        AQSWMnOHSOIZx07gK%2ByC0l1fOJOwO2lW095NDSGNta4GpSttK%2FToQVLDxL5WzV3pQgB\
        d%2BiJaJn4UOMs7WH%2BVYISpuasRiFcjtEiSLxEUmrguTKqpWBBPP6kBKnwoVQ88h%2FcX\
        EJSz1ya2qpQhqxjIm913YaDnPKtZKhYQq9QRghRLfXY84KPbZJnR0w2gdzIzabY6Yu2svoe\
        qk4K52GNGmGwPL4N4QbTuI9T7Tagd1unG6D3ByZZxjbMxqAlO2v%2F2EmYMvZFCw2HEmgNZ\
        %2F0cZ%2F2ixVCw4Zbtz5y%2BqYVkY2bD%2F9NgYnHcol2pvqqy6JcQuog2ruSCMzBhm2gj\
        54TDYf0iF22uStvCO%2B9EC7ockVHmBFWdD6L2TJF6g7O%2BGp0GhxnuZFA4t14g7%2FCye\
        lJxL2FnMsUP2lwEVENSb%2FfhRNUr3CZMMGM%2B1GCIIoiGqrlND0pAK8wKZVBHAoGkyMXM\
        YDlqdkPNlZDY3PrF4bZhldaMpI%2F2NYj8vCyzJkvMYl%2BwmbHeNztmDGYbB5Nk%2BZ%2F\
        UnGD8lAuwHGDaf6xD%2Bna67OLOikLOAbyUVotBppEBCMOvx7r0GOqUBT5g35EbAq9Mw3BW\
        j2mqFd7c3IuVee4eAH6kTXI9CJ0pQ%2F5RixpNdaiu3BZJ0HXUpwAGTUTb7kPMrYGcZ5Ziv\
        HBeDQrkdwSywgwn%2B9Ut6FRK3oCd2ogWfiyszjBQ5yTPO8yWGpRuVM%2F4uAYjZXGuNBHu\
        hOzZyl5bRvUi8UQMDh17qco7QGNO4WnjbhOkzp2%2B%2BHsAY9j86RAcMFpRJAgd9JDOwwA\
        gh&X-Amz-Signature=ebe8d6ab3052e64c0eeb90da942a44ebdd24abf38027c6f9ac1d\
        dff731366e8e&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-24T04:31:03.836Z"
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
UPDATE_TIME: "2025-02-24T03:32:21.047Z"
EXPIRY_TIME: "2025-02-24T04:32:14.019Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RKGMNOLO%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T033214Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIDrBeE6bUeUyWkUGgZNZwOZGJf1HyubZCQgYPjVN7YYRAiBaiXZW6Xb0ftNahmGjaBvTqSfYekineYAp6kDbc2e6lCr%2FAwghEAAaDDYzNzQyMzE4MzgwNSIMe%2F1GwuxE3joXFps2KtwDFdzh2O14%2BVdjXcy17mLqnQKkvnO0xkErw8DqwKFwAZArBVFJm5olzqbyZ8DvHfKf%2BNn6NsQf5o2sizBuxBnqG7NlDCJeR7gGyM%2FsZc4FnvKXFSEh%2FIW%2FIDVd%2B%2BddkwZKBB6cMTS%2B%2FKxksxKIV2QtG%2BPR%2BSzsst1yqkJKaeA5zx8PKe3FE359wfGsHGT2mU7ZbKRRCQUnPtZsAT1qqdSe6MseItYcrJeX1DrVkdWd%2BPLhLQYHO9ZzhPAHA1MCFNKGxGRxMlv4nQz7f3t7f2UYM65gb5afDt0U3geLhwOmQonEbnLfBVHgyJKlP%2B%2BrS8Z2rrt99z91yh4nyoIl0PLqqdfKf846wh5sz%2FagItJUwLavQLF7ql%2BJCKZwMZMp%2FJohNOgwNVlkqPyXbwe8FvWsZtPY3%2B1rLBIZmru2udAHlKaECAdOpM6RHQyUS%2BCmIvpPACdj9XKjwwJooQYDPpUQWzLGVd4lEF%2BDOQT8UXDk48KOmvoCPUHP0VSsN5IkdvSSsBqwWxuKMP0c4DkiaeU4BIX%2BM6dVkQ7MwO2WeWFW2moFh8xQkyFxEHcIrHHBMkT2%2B2pnmGw%2FZ3CpZa%2BU4iLeyytxMVUt5xRHNfUgxJg%2FRAN78rst7cVZhrLwei0w7PDuvQY6pgHyD0U5vXcoeEsP5zh7DjHB%2FSLG43OEvwCTg2LNGtuLCCxJEp0IBapwpdnTNuoopCujWFbJOeo2%2BCx7EPUKjjc4Lj04vb9hPOoGGFAM0s5RMH00vllWlxYsJPFJg5gg9M7d8%2FLtOGvDVwuj25DkP%2BrCDnDZDlgZzBKTqqVR3EVSa63sKyK3PaYRlG%2B0B8HNj%2ByIxFQEBcrSiOwBmgx8m3JTRVvSeNIc&X-Amz-Signature=d59b29d27c7a30eb6a7d8c56565f366a58ba9f6e9918d826738465bd5b00de76&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RKGMNOLO%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T033214Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIDrBeE6bUeUyWkUGgZNZwOZGJf1HyubZCQgYPjVN7YYRAiBaiXZW6Xb0ftNahmGjaBvTqSfYekineYAp6kDbc2e6lCr%2FAwghEAAaDDYzNzQyMzE4MzgwNSIMe%2F1GwuxE3joXFps2KtwDFdzh2O14%2BVdjXcy17mLqnQKkvnO0xkErw8DqwKFwAZArBVFJm5olzqbyZ8DvHfKf%2BNn6NsQf5o2sizBuxBnqG7NlDCJeR7gGyM%2FsZc4FnvKXFSEh%2FIW%2FIDVd%2B%2BddkwZKBB6cMTS%2B%2FKxksxKIV2QtG%2BPR%2BSzsst1yqkJKaeA5zx8PKe3FE359wfGsHGT2mU7ZbKRRCQUnPtZsAT1qqdSe6MseItYcrJeX1DrVkdWd%2BPLhLQYHO9ZzhPAHA1MCFNKGxGRxMlv4nQz7f3t7f2UYM65gb5afDt0U3geLhwOmQonEbnLfBVHgyJKlP%2B%2BrS8Z2rrt99z91yh4nyoIl0PLqqdfKf846wh5sz%2FagItJUwLavQLF7ql%2BJCKZwMZMp%2FJohNOgwNVlkqPyXbwe8FvWsZtPY3%2B1rLBIZmru2udAHlKaECAdOpM6RHQyUS%2BCmIvpPACdj9XKjwwJooQYDPpUQWzLGVd4lEF%2BDOQT8UXDk48KOmvoCPUHP0VSsN5IkdvSSsBqwWxuKMP0c4DkiaeU4BIX%2BM6dVkQ7MwO2WeWFW2moFh8xQkyFxEHcIrHHBMkT2%2B2pnmGw%2FZ3CpZa%2BU4iLeyytxMVUt5xRHNfUgxJg%2FRAN78rst7cVZhrLwei0w7PDuvQY6pgHyD0U5vXcoeEsP5zh7DjHB%2FSLG43OEvwCTg2LNGtuLCCxJEp0IBapwpdnTNuoopCujWFbJOeo2%2BCx7EPUKjjc4Lj04vb9hPOoGGFAM0s5RMH00vllWlxYsJPFJg5gg9M7d8%2FLtOGvDVwuj25DkP%2BrCDnDZDlgZzBKTqqVR3EVSa63sKyK3PaYRlG%2B0B8HNj%2ByIxFQEBcrSiOwBmgx8m3JTRVvSeNIc&X-Amz-Signature=21f9aa5a2b72a474398f4fcc9a5e903625105c732d0c118467bb7cc7ac4dc8a6&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RKGMNOLO%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T033214Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIDrBeE6bUeUyWkUGgZNZwOZGJf1HyubZCQgYPjVN7YYRAiBaiXZW6Xb0ftNahmGjaBvTqSfYekineYAp6kDbc2e6lCr%2FAwghEAAaDDYzNzQyMzE4MzgwNSIMe%2F1GwuxE3joXFps2KtwDFdzh2O14%2BVdjXcy17mLqnQKkvnO0xkErw8DqwKFwAZArBVFJm5olzqbyZ8DvHfKf%2BNn6NsQf5o2sizBuxBnqG7NlDCJeR7gGyM%2FsZc4FnvKXFSEh%2FIW%2FIDVd%2B%2BddkwZKBB6cMTS%2B%2FKxksxKIV2QtG%2BPR%2BSzsst1yqkJKaeA5zx8PKe3FE359wfGsHGT2mU7ZbKRRCQUnPtZsAT1qqdSe6MseItYcrJeX1DrVkdWd%2BPLhLQYHO9ZzhPAHA1MCFNKGxGRxMlv4nQz7f3t7f2UYM65gb5afDt0U3geLhwOmQonEbnLfBVHgyJKlP%2B%2BrS8Z2rrt99z91yh4nyoIl0PLqqdfKf846wh5sz%2FagItJUwLavQLF7ql%2BJCKZwMZMp%2FJohNOgwNVlkqPyXbwe8FvWsZtPY3%2B1rLBIZmru2udAHlKaECAdOpM6RHQyUS%2BCmIvpPACdj9XKjwwJooQYDPpUQWzLGVd4lEF%2BDOQT8UXDk48KOmvoCPUHP0VSsN5IkdvSSsBqwWxuKMP0c4DkiaeU4BIX%2BM6dVkQ7MwO2WeWFW2moFh8xQkyFxEHcIrHHBMkT2%2B2pnmGw%2FZ3CpZa%2BU4iLeyytxMVUt5xRHNfUgxJg%2FRAN78rst7cVZhrLwei0w7PDuvQY6pgHyD0U5vXcoeEsP5zh7DjHB%2FSLG43OEvwCTg2LNGtuLCCxJEp0IBapwpdnTNuoopCujWFbJOeo2%2BCx7EPUKjjc4Lj04vb9hPOoGGFAM0s5RMH00vllWlxYsJPFJg5gg9M7d8%2FLtOGvDVwuj25DkP%2BrCDnDZDlgZzBKTqqVR3EVSa63sKyK3PaYRlG%2B0B8HNj%2ByIxFQEBcrSiOwBmgx8m3JTRVvSeNIc&X-Amz-Signature=0574dca1495b9da4831f58af0e9cb70f99fcca1580d95da7004428c2d4edec1b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RKGMNOLO%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T033214Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIDrBeE6bUeUyWkUGgZNZwOZGJf1HyubZCQgYPjVN7YYRAiBaiXZW6Xb0ftNahmGjaBvTqSfYekineYAp6kDbc2e6lCr%2FAwghEAAaDDYzNzQyMzE4MzgwNSIMe%2F1GwuxE3joXFps2KtwDFdzh2O14%2BVdjXcy17mLqnQKkvnO0xkErw8DqwKFwAZArBVFJm5olzqbyZ8DvHfKf%2BNn6NsQf5o2sizBuxBnqG7NlDCJeR7gGyM%2FsZc4FnvKXFSEh%2FIW%2FIDVd%2B%2BddkwZKBB6cMTS%2B%2FKxksxKIV2QtG%2BPR%2BSzsst1yqkJKaeA5zx8PKe3FE359wfGsHGT2mU7ZbKRRCQUnPtZsAT1qqdSe6MseItYcrJeX1DrVkdWd%2BPLhLQYHO9ZzhPAHA1MCFNKGxGRxMlv4nQz7f3t7f2UYM65gb5afDt0U3geLhwOmQonEbnLfBVHgyJKlP%2B%2BrS8Z2rrt99z91yh4nyoIl0PLqqdfKf846wh5sz%2FagItJUwLavQLF7ql%2BJCKZwMZMp%2FJohNOgwNVlkqPyXbwe8FvWsZtPY3%2B1rLBIZmru2udAHlKaECAdOpM6RHQyUS%2BCmIvpPACdj9XKjwwJooQYDPpUQWzLGVd4lEF%2BDOQT8UXDk48KOmvoCPUHP0VSsN5IkdvSSsBqwWxuKMP0c4DkiaeU4BIX%2BM6dVkQ7MwO2WeWFW2moFh8xQkyFxEHcIrHHBMkT2%2B2pnmGw%2FZ3CpZa%2BU4iLeyytxMVUt5xRHNfUgxJg%2FRAN78rst7cVZhrLwei0w7PDuvQY6pgHyD0U5vXcoeEsP5zh7DjHB%2FSLG43OEvwCTg2LNGtuLCCxJEp0IBapwpdnTNuoopCujWFbJOeo2%2BCx7EPUKjjc4Lj04vb9hPOoGGFAM0s5RMH00vllWlxYsJPFJg5gg9M7d8%2FLtOGvDVwuj25DkP%2BrCDnDZDlgZzBKTqqVR3EVSa63sKyK3PaYRlG%2B0B8HNj%2ByIxFQEBcrSiOwBmgx8m3JTRVvSeNIc&X-Amz-Signature=edc3fb4e475940d3a6528ba3253fdc4bc6cca2c070d1b2e916f46c043fccc6e4&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RKGMNOLO%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T033214Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIDrBeE6bUeUyWkUGgZNZwOZGJf1HyubZCQgYPjVN7YYRAiBaiXZW6Xb0ftNahmGjaBvTqSfYekineYAp6kDbc2e6lCr%2FAwghEAAaDDYzNzQyMzE4MzgwNSIMe%2F1GwuxE3joXFps2KtwDFdzh2O14%2BVdjXcy17mLqnQKkvnO0xkErw8DqwKFwAZArBVFJm5olzqbyZ8DvHfKf%2BNn6NsQf5o2sizBuxBnqG7NlDCJeR7gGyM%2FsZc4FnvKXFSEh%2FIW%2FIDVd%2B%2BddkwZKBB6cMTS%2B%2FKxksxKIV2QtG%2BPR%2BSzsst1yqkJKaeA5zx8PKe3FE359wfGsHGT2mU7ZbKRRCQUnPtZsAT1qqdSe6MseItYcrJeX1DrVkdWd%2BPLhLQYHO9ZzhPAHA1MCFNKGxGRxMlv4nQz7f3t7f2UYM65gb5afDt0U3geLhwOmQonEbnLfBVHgyJKlP%2B%2BrS8Z2rrt99z91yh4nyoIl0PLqqdfKf846wh5sz%2FagItJUwLavQLF7ql%2BJCKZwMZMp%2FJohNOgwNVlkqPyXbwe8FvWsZtPY3%2B1rLBIZmru2udAHlKaECAdOpM6RHQyUS%2BCmIvpPACdj9XKjwwJooQYDPpUQWzLGVd4lEF%2BDOQT8UXDk48KOmvoCPUHP0VSsN5IkdvSSsBqwWxuKMP0c4DkiaeU4BIX%2BM6dVkQ7MwO2WeWFW2moFh8xQkyFxEHcIrHHBMkT2%2B2pnmGw%2FZ3CpZa%2BU4iLeyytxMVUt5xRHNfUgxJg%2FRAN78rst7cVZhrLwei0w7PDuvQY6pgHyD0U5vXcoeEsP5zh7DjHB%2FSLG43OEvwCTg2LNGtuLCCxJEp0IBapwpdnTNuoopCujWFbJOeo2%2BCx7EPUKjjc4Lj04vb9hPOoGGFAM0s5RMH00vllWlxYsJPFJg5gg9M7d8%2FLtOGvDVwuj25DkP%2BrCDnDZDlgZzBKTqqVR3EVSa63sKyK3PaYRlG%2B0B8HNj%2ByIxFQEBcrSiOwBmgx8m3JTRVvSeNIc&X-Amz-Signature=e39d24fe5cbab9a1d36fff42b9e063754d2def394e3007e0754b731195b2a6e4&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XCT45JWF%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T033214Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD9OLQjo66V5rKkbAMSZZthFEmqUko9MWKFV9DPEjv6DgIhAPGEpexBuWY19oDDRwTnuNrJZFqJ%2BZS5zzYZ4pnJ5w7JKv8DCCEQABoMNjM3NDIzMTgzODA1IgxhU60gI%2Fd0sZdJuvwq3APH8gF1iefsNs%2BfHr7AfvIrubPLbGT6L%2FTCYDZwX0SbP2iq4T7g5s2ivvroJ%2BwaYs%2FXS9%2BxlIXddz8AdGPtxDk6ipdksD2JLx723iAcMoVu9EQFUARtXaqPOD7G5ts3rweGZSLfL333pofoQkGF2kbjNlVeQ28HTatu3GGpgAEkc3UmACSiEHGdDz%2B7xuug6D1kZusY3UdJTu6kCAAUD1NwUqFNnLKZixm685ySkR9V7IrMWiqVywZMWTtMDS8oHCMWmDm50KXgB%2FHkejXkkIUxkU%2BP5qxUUxEDstS3Iqt2a%2B5gDCAFuh0uFs%2Fx2WX8uVHGng5UeLf4ckz9Y2xrDbPcR7t90%2FAc1%2FhudxT4%2FWuL5CUqAf5u6GptfBczyHGar8buNVJcmakQE1UzmNlNXUL0dN7hIQth9L%2BXKHG%2Bwje%2FVLcvsNStkrWpxaGuvb37DuAVnkFoLBtddE6Z7JBSw4zmkIePiizF1SB%2BEfybnHLaD8gM%2FCbBd%2FmL8z7j0Z0i9K3JzBBxOqC8PKVxAhUiMFJhU5Lx63JK9IdlvctjQ3vBFXKryZlHcFlwqmbUTkkxQyF4lh29cn2meVbxcYTQGcY0bnGL1ryaPs001BshNanubrKRbEKHj62Rqo4gtDCv8u69BjqkARR2G8m9oi8xw4wUMrr5ChJePaqQmdC85guZBtaTkp3szQCHrdjzsnC80cAFdVMReTNvBB7WlSlezNlmNw6J8jHni%2B7OsrZsl5P0Fp%2BuTEegH9c4oRldzO6YbzEbqYOQbP4gpPpa4yK8LuE9UveNXm74hBIbxQ1d%2FSbBye8FK7rPE6e2ewxsJA%2BCGBVTCMK9Awj%2B0LvZHHkAKOlqEm27wzqGICK7&X-Amz-Signature=d4a5589926fe52889376c01811e27f27cb154ea68b80a3aa01f1b777299a1592&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666244XSGV%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T033215Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD2i%2BJvBCtO8uwgk4VEX8xSawkeLpLPeIrW4Z59%2FogQOgIhAPwgvi6cZdDqPWYm%2BXrsOMqIDS21oLPQCsx1FOL4D7fPKv8DCCEQABoMNjM3NDIzMTgzODA1IgyAbdZ7onKAqcgoLasq3ANdkbN%2BTR9JVO0HDn340NXoy3Kjk4FAzsvYrB2UV4w4hVQch6oLGuCpIkN24%2BIXmeT1IUPqGLN0ahJw6LCG7sK8E9lID66%2B4PDQFVvJ284JhlttQVPFA7BA7kbW0iuj7sCahWTK54js%2FyY2wj1Ot6xlLH%2FPhp%2FbG4gTx%2FTggb9eXiqBJOjAyx21qKccraoIzVfWUOsb37MyayhEKcpNyxwIyDBT0hfXBqFSzzyzZahSJozWLbO7idzI0Ju7am%2BcK9mac89KZ6uknkjfARfSv37nUpD10%2FFgiITXCy51Icir054ip8zKZNmEkB%2FSWpnAp5eutoK1NJ14AKEnC2AFSVNExAViuvqRcUlBm1SJL5KeRfslZGT%2BGkCIJcQANn%2FJNd01SKYuMoclsdBGyvtTwPmENDyvF8cj6cn8ez7lb2Wo4ndGwK2qPMsqAMNEOKhUQbRR3NrXeAJ%2FdCQYmyK62ktWKiQV2OXNajiboHAzZpyEbXRnPzMEDJ%2FKBzl5yZ3stjd75Ulku5DRk2Fhm%2BdgqWla%2FH7DZbkz3gUE%2F2KP8SC%2FqEorLSyy1P0L2ab9L%2Fi%2B4Dt6bcAZC7%2BfiR5C5DgYtck8W0guR7%2BKafugg7r1mn2zrkUGddYstpRloJ47UDCj8e69BjqkAXUZLz2Q1AB90wPMNLkB2oj3nC46nvBJHAQLklIqNGzxvvAe%2FdPxsK7GhRlT%2FAkKAA8LAfj%2FUoHBEzXbNTa5muKrazl3ygefwlywqn%2FcWm0RT5VOV4pYNLH2Bkoc6Q8SbGUSXqLnyY8w0AzQDp8BfiY2B35zBHC2DKYc1TrvAC0AXhAof%2FQ9baDBH0pRV8cwgDT9oJfPxUXAxnfW%2BZd%2BxWTGm3wj&X-Amz-Signature=48fbbaa0db12fbc241fb59a987fa2d88d4cbe9a4ef7bc332b68d49f95241db3c&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RKGMNOLO%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T033214Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIDrBeE6bUeUyWkUGgZNZwOZGJf1HyubZCQgYPjVN7YYRAiBaiXZW6Xb0ftNahmGjaBvTqSfYekineYAp6kDbc2e6lCr%2FAwghEAAaDDYzNzQyMzE4MzgwNSIMe%2F1GwuxE3joXFps2KtwDFdzh2O14%2BVdjXcy17mLqnQKkvnO0xkErw8DqwKFwAZArBVFJm5olzqbyZ8DvHfKf%2BNn6NsQf5o2sizBuxBnqG7NlDCJeR7gGyM%2FsZc4FnvKXFSEh%2FIW%2FIDVd%2B%2BddkwZKBB6cMTS%2B%2FKxksxKIV2QtG%2BPR%2BSzsst1yqkJKaeA5zx8PKe3FE359wfGsHGT2mU7ZbKRRCQUnPtZsAT1qqdSe6MseItYcrJeX1DrVkdWd%2BPLhLQYHO9ZzhPAHA1MCFNKGxGRxMlv4nQz7f3t7f2UYM65gb5afDt0U3geLhwOmQonEbnLfBVHgyJKlP%2B%2BrS8Z2rrt99z91yh4nyoIl0PLqqdfKf846wh5sz%2FagItJUwLavQLF7ql%2BJCKZwMZMp%2FJohNOgwNVlkqPyXbwe8FvWsZtPY3%2B1rLBIZmru2udAHlKaECAdOpM6RHQyUS%2BCmIvpPACdj9XKjwwJooQYDPpUQWzLGVd4lEF%2BDOQT8UXDk48KOmvoCPUHP0VSsN5IkdvSSsBqwWxuKMP0c4DkiaeU4BIX%2BM6dVkQ7MwO2WeWFW2moFh8xQkyFxEHcIrHHBMkT2%2B2pnmGw%2FZ3CpZa%2BU4iLeyytxMVUt5xRHNfUgxJg%2FRAN78rst7cVZhrLwei0w7PDuvQY6pgHyD0U5vXcoeEsP5zh7DjHB%2FSLG43OEvwCTg2LNGtuLCCxJEp0IBapwpdnTNuoopCujWFbJOeo2%2BCx7EPUKjjc4Lj04vb9hPOoGGFAM0s5RMH00vllWlxYsJPFJg5gg9M7d8%2FLtOGvDVwuj25DkP%2BrCDnDZDlgZzBKTqqVR3EVSa63sKyK3PaYRlG%2B0B8HNj%2ByIxFQEBcrSiOwBmgx8m3JTRVvSeNIc&X-Amz-Signature=942be4ab19297f69cd0f320469bfbcaef6c51ff8fdb684671f026565e049e58e&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RKGMNOLO%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T033214Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIDrBeE6bUeUyWkUGgZNZwOZGJf1HyubZCQgYPjVN7YYRAiBaiXZW6Xb0ftNahmGjaBvTqSfYekineYAp6kDbc2e6lCr%2FAwghEAAaDDYzNzQyMzE4MzgwNSIMe%2F1GwuxE3joXFps2KtwDFdzh2O14%2BVdjXcy17mLqnQKkvnO0xkErw8DqwKFwAZArBVFJm5olzqbyZ8DvHfKf%2BNn6NsQf5o2sizBuxBnqG7NlDCJeR7gGyM%2FsZc4FnvKXFSEh%2FIW%2FIDVd%2B%2BddkwZKBB6cMTS%2B%2FKxksxKIV2QtG%2BPR%2BSzsst1yqkJKaeA5zx8PKe3FE359wfGsHGT2mU7ZbKRRCQUnPtZsAT1qqdSe6MseItYcrJeX1DrVkdWd%2BPLhLQYHO9ZzhPAHA1MCFNKGxGRxMlv4nQz7f3t7f2UYM65gb5afDt0U3geLhwOmQonEbnLfBVHgyJKlP%2B%2BrS8Z2rrt99z91yh4nyoIl0PLqqdfKf846wh5sz%2FagItJUwLavQLF7ql%2BJCKZwMZMp%2FJohNOgwNVlkqPyXbwe8FvWsZtPY3%2B1rLBIZmru2udAHlKaECAdOpM6RHQyUS%2BCmIvpPACdj9XKjwwJooQYDPpUQWzLGVd4lEF%2BDOQT8UXDk48KOmvoCPUHP0VSsN5IkdvSSsBqwWxuKMP0c4DkiaeU4BIX%2BM6dVkQ7MwO2WeWFW2moFh8xQkyFxEHcIrHHBMkT2%2B2pnmGw%2FZ3CpZa%2BU4iLeyytxMVUt5xRHNfUgxJg%2FRAN78rst7cVZhrLwei0w7PDuvQY6pgHyD0U5vXcoeEsP5zh7DjHB%2FSLG43OEvwCTg2LNGtuLCCxJEp0IBapwpdnTNuoopCujWFbJOeo2%2BCx7EPUKjjc4Lj04vb9hPOoGGFAM0s5RMH00vllWlxYsJPFJg5gg9M7d8%2FLtOGvDVwuj25DkP%2BrCDnDZDlgZzBKTqqVR3EVSa63sKyK3PaYRlG%2B0B8HNj%2ByIxFQEBcrSiOwBmgx8m3JTRVvSeNIc&X-Amz-Signature=3240db0b80a250912b0082190fa46b258869ae17f9ccd2760f4abe94251f44ca&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RKGMNOLO%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T033214Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIDrBeE6bUeUyWkUGgZNZwOZGJf1HyubZCQgYPjVN7YYRAiBaiXZW6Xb0ftNahmGjaBvTqSfYekineYAp6kDbc2e6lCr%2FAwghEAAaDDYzNzQyMzE4MzgwNSIMe%2F1GwuxE3joXFps2KtwDFdzh2O14%2BVdjXcy17mLqnQKkvnO0xkErw8DqwKFwAZArBVFJm5olzqbyZ8DvHfKf%2BNn6NsQf5o2sizBuxBnqG7NlDCJeR7gGyM%2FsZc4FnvKXFSEh%2FIW%2FIDVd%2B%2BddkwZKBB6cMTS%2B%2FKxksxKIV2QtG%2BPR%2BSzsst1yqkJKaeA5zx8PKe3FE359wfGsHGT2mU7ZbKRRCQUnPtZsAT1qqdSe6MseItYcrJeX1DrVkdWd%2BPLhLQYHO9ZzhPAHA1MCFNKGxGRxMlv4nQz7f3t7f2UYM65gb5afDt0U3geLhwOmQonEbnLfBVHgyJKlP%2B%2BrS8Z2rrt99z91yh4nyoIl0PLqqdfKf846wh5sz%2FagItJUwLavQLF7ql%2BJCKZwMZMp%2FJohNOgwNVlkqPyXbwe8FvWsZtPY3%2B1rLBIZmru2udAHlKaECAdOpM6RHQyUS%2BCmIvpPACdj9XKjwwJooQYDPpUQWzLGVd4lEF%2BDOQT8UXDk48KOmvoCPUHP0VSsN5IkdvSSsBqwWxuKMP0c4DkiaeU4BIX%2BM6dVkQ7MwO2WeWFW2moFh8xQkyFxEHcIrHHBMkT2%2B2pnmGw%2FZ3CpZa%2BU4iLeyytxMVUt5xRHNfUgxJg%2FRAN78rst7cVZhrLwei0w7PDuvQY6pgHyD0U5vXcoeEsP5zh7DjHB%2FSLG43OEvwCTg2LNGtuLCCxJEp0IBapwpdnTNuoopCujWFbJOeo2%2BCx7EPUKjjc4Lj04vb9hPOoGGFAM0s5RMH00vllWlxYsJPFJg5gg9M7d8%2FLtOGvDVwuj25DkP%2BrCDnDZDlgZzBKTqqVR3EVSa63sKyK3PaYRlG%2B0B8HNj%2ByIxFQEBcrSiOwBmgx8m3JTRVvSeNIc&X-Amz-Signature=36ff7e32624d4044f1b0380d9db881371211063e99c9d8018c795172fefa8004&X-Amz-SignedHeaders=host&x-id=GetObject)


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

