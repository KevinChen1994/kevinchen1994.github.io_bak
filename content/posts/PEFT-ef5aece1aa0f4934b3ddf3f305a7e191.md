---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4667Y562T7Q%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250223T063122Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjENX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIGuNyDcafhYBttDFWxH\
  %2B%2BiYZ0Gn%2FDqXfJ5AafSvl309FAiEA9f8eVu03xT45TXAf%2FkX6aiGYohGlPyDVHZMjgD0z\
  m8EqiAQI%2Fv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDE3tpft7nnL\
  lrc48oSrcA6ziRhfRQu%2BqKZkL%2FiGaAJ6Gk3L5AmmEi5vomMN8b%2FDIIb%2B63oZf2I5yorD8\
  sfPLYz2HL3L4smg0Nm1I%2BkGM9o%2BI%2BprP0JIoAFRgh8WJJcUl92mv0tvEpPJxoDvde%2BNA5\
  fGXOJvkpsu8wBkD4fmHNUvpw2nYdIgE8zPQB3eODxjWep1bV5bSCx%2FYqS5iDqzBMO%2F8Ggm77S\
  %2FYh95ptHA8Om74GMfVxamiHyxyvnRkajDrQ8MuGIEst43sNwrvLcJGoSSMy%2FkKGPYmOas7Kg8\
  9ISK%2BnA%2BMlBk0ks5O0jAYQANOV1O4XLLGUV2IDNbKneU7mxOZV5Z8eaxTeqBcmAzPMxqQv10h\
  LVwTXLE%2FgOAnxaute0uCWn2G186E7SPJhYb2JphdXv8fvWwcRz1QLsSWNin%2F9hy0w2HM0TA2g\
  2i9yvuuNmYNEs7xa64BLhu1M0sZ%2Bvg78zS7iHWTPoBXpOeXv1Y7h1F6ajcuBbB0Q6o5WNUdMhbs\
  xj9Wpu5tMCzMSrmBonwSdAv9lnVm99oGdArjsSr0ZkYR9IAFA17PxKmNoARjlcEfH1Z3bcFDav4xo\
  WI69Z8dsOCSFQV6%2BbZEkwshGwM9suycVU9NEZ%2FfbrP8C0xnd6vszs7Xyx3YSVBdMNjI6r0GOq\
  UBCNkWmVen%2BYmlUkOsgbT4uLptrAZ1Zv8vGWxDiFjmqzvrjqWc0FpIjlOhJ%2Bk%2BmFUnfA36C\
  IqRILwXfEvHgKh99BDEWTxLvupkcpzg2Ax5RN7Og00u6so8lFInT5w99wJpQ3nMraGGC%2Fa3ABa9\
  W9xeIUVnty8lbtLRADXu59jnX3Kwpn8CWeEXSN%2BYwZxPSzAN1h1zgB236tTIQOtnv8eTBCVgyiQ\
  B&X-Amz-Signature=0bf5327f49449f1def83a900dfea3ebe8c97185c5e942af7f62126159d0\
  e0698&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466XIJXLICK%2F20250223%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250223T062931Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjENX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQ\
        CIFO7EQooooQ%2BQ%2BJcr%2F62jxmUqDcreWNYpCjlvvAp6QDlAiAgDpbCVjTnxXygE%2B\
        1QvOLQ1qFEpAEeSXU4F%2FsvIcTAGyqIBAj%2B%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BE\
        AAaDDYzNzQyMzE4MzgwNSIMq%2FtUaFBo6zqYnx0OKtwDY6FExpbN4mH0CKeJ%2BaWB0UEo\
        %2BulPbLeDBg0eNx%2BbWoW41bD6VTfzwcHpkGivZK4d068q8mEtb%2BoQBKS%2FTSxw4Ca\
        kc0UotUZFHgXQ3zXOvK5SOUfqrLP4VFAhazM3MZF13YxbX1zAWXnCtEPL0NbKgxsKh21wfi\
        k6pVenUcExQ%2FeP201nr2GsmVBsKXI8VoqRMspPT84JgpiHXqDRPZ0zXh51tMMh5Aj%2BS\
        IQoM47r9xd045qv5VclPtaclq6u47ReSgzcZ1%2BU7QhhDZ7StfwxQlnHf9atZhO6lT2TZL\
        9ZZDsf%2FBAqCgIUpcu3r3DPtUZtLl2bqG%2Btkq5dDmM7Mofe919dpxxO2juazxS80h%2B\
        8zXOdEDs6VZmlxGdnY6xS0NvufkfWNRw%2BnOLYgospyNSxXrSFGrjObUesfTB63b9%2FU2\
        xgrA%2FvlcAdE%2BtaXdQJjKoHO4WoNMVUZ2LF9lQqmkr1VIlQUFOQP8429vgtVg%2Flr3r\
        AsNnHG1zf7A4xdYMidTgt4lNhTZvj02GpDxRtifSo4LMS5aqLTwTA6h2my%2FTFazUmairI\
        ZajuuOQMyT3FyMcnv5qGnguPYUGXXfghShKqSgzZDqg9W3M79YxJwfoTTd%2B7fFnAeVAdg\
        %2BwWwM0wyMnqvQY6pgGuur5tPa5CvCzK7JMUXlEZ%2FazKhcpdWMrpe5iL7IbVJ%2B7loS\
        QHhm%2F7ZIxMp3oWyeDyhgkx6UwYFTWm6kz9a210wN6pkh9DXqRWXiOgcz6lVFoRdG5z0aE\
        kybZagLcF0R2iOZ%2FQDySLQGQryL6oQrR1oYND03fDKMzkuyeIGg5ZecdXyLwq6tl9%2BG\
        czIHx0COSbgzRcVgem282T6B6WfjflLC1tILN0&X-Amz-Signature=13346e4a7e3bc5a7\
        f99756056d5b90045e901d771fb3fedb737cf337b0e050ee&X-Amz-SignedHeaders=ho\
        st&x-id=GetObject"
      expiry_time: "2025-02-23T07:29:31.364Z"
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
UPDATE_TIME: "2025-02-23T06:31:31.375Z"
EXPIRY_TIME: "2025-02-23T07:31:19.591Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TX6ZKI3H%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T063120Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBrEdGufHTbKEhqB%2BUB35IGYaY2VNWIVKG7r64uM4YOYAiEA8uSOx%2B3oexhJ1pJ9Ztg75QNPgT39ckgAJDqb770%2BQOgqiAQI%2Fv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDBA%2FCfAvfZA%2B1M2HfircAzs5O6fE9yN%2Bv0%2FdC6qUL36O0FcI7zuv9kLAT8JvWiBDGaTBOL2QBADyXMXwJLJieK8YkKDk5byX%2B6DUdm%2BsOQkz06aIpvbTv%2FCp%2FALJbKva5zl5TLcd7sS0GxeXX4VEFr%2FuYlUbYYww2DMbHWaWQ9Ov13XRtE%2F2Wht5EzPjj3Ga10zuizWKRpV3S2ipzqlrnOEQAoy9CViQ2aQ%2FcrQeec4F5a%2Fcw%2BYHVPT2k5yoVL0njgKYpoRJh5J6rvk%2F2AIfbmn%2F9MGApG1O96YntTyzJJkCxUjINsd5ujcsury2YCj0gp%2FZr%2FgcqTp%2FbOw7xFKQXNzljy8qlqzsalixBDzqEG9FhZQLOrXhkMS8%2B%2Bh7KPgWYbgfedDh%2BOL7mVvvj65Mg3RuIZ1tURFQXX5B1ISQ7pp2Iq8ZlXd3vhTL8fG%2BMAQnYeTwY4nkrbATcQKjVDKlf9fG%2FPSM%2B6JExtpPMk0fDASAKgcPgYc%2B2Y1fbn8Y3c1rd%2FG4FQ0fNv7NYHTh65P7QhhgapG1QIInnSkwvzqekLKi40BgS6WrXRKVu40GJiVvpZzU5nfgb7Eq76iwgy77wq%2FLoK7b0Eu8xnsCV3bYTRcr7o%2Fp6V67a5kqY3o%2Bjqf0JuFSPU7S2KYya4y5MLPT6r0GOqUBR9hNXd4eHtYKnQ8NcxVCrAb%2BphObPbqafw6CYLaTycDLzPB%2FtLuIjBwNuxdB4DBGG3KRKpnHw2HSKpP4wVfR5urstPVOLMcgqc2ceTyhsxbURfe8nppWFlTKlE3OPPQYOqbjvoYHcKEMo2JfN%2F46Uuld9FRBDLjfNBaMJitsiESW80re1HonTDTJ%2F4XdbKwTduJ0RVEYcl%2Fq7QuE5hwyYYKjVL%2Fm&X-Amz-Signature=2d5c9a28bdeaee7ce282bcd55730394a4b306822ab1677c3c1f46a5e5764e7db&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TX6ZKI3H%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T063120Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBrEdGufHTbKEhqB%2BUB35IGYaY2VNWIVKG7r64uM4YOYAiEA8uSOx%2B3oexhJ1pJ9Ztg75QNPgT39ckgAJDqb770%2BQOgqiAQI%2Fv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDBA%2FCfAvfZA%2B1M2HfircAzs5O6fE9yN%2Bv0%2FdC6qUL36O0FcI7zuv9kLAT8JvWiBDGaTBOL2QBADyXMXwJLJieK8YkKDk5byX%2B6DUdm%2BsOQkz06aIpvbTv%2FCp%2FALJbKva5zl5TLcd7sS0GxeXX4VEFr%2FuYlUbYYww2DMbHWaWQ9Ov13XRtE%2F2Wht5EzPjj3Ga10zuizWKRpV3S2ipzqlrnOEQAoy9CViQ2aQ%2FcrQeec4F5a%2Fcw%2BYHVPT2k5yoVL0njgKYpoRJh5J6rvk%2F2AIfbmn%2F9MGApG1O96YntTyzJJkCxUjINsd5ujcsury2YCj0gp%2FZr%2FgcqTp%2FbOw7xFKQXNzljy8qlqzsalixBDzqEG9FhZQLOrXhkMS8%2B%2Bh7KPgWYbgfedDh%2BOL7mVvvj65Mg3RuIZ1tURFQXX5B1ISQ7pp2Iq8ZlXd3vhTL8fG%2BMAQnYeTwY4nkrbATcQKjVDKlf9fG%2FPSM%2B6JExtpPMk0fDASAKgcPgYc%2B2Y1fbn8Y3c1rd%2FG4FQ0fNv7NYHTh65P7QhhgapG1QIInnSkwvzqekLKi40BgS6WrXRKVu40GJiVvpZzU5nfgb7Eq76iwgy77wq%2FLoK7b0Eu8xnsCV3bYTRcr7o%2Fp6V67a5kqY3o%2Bjqf0JuFSPU7S2KYya4y5MLPT6r0GOqUBR9hNXd4eHtYKnQ8NcxVCrAb%2BphObPbqafw6CYLaTycDLzPB%2FtLuIjBwNuxdB4DBGG3KRKpnHw2HSKpP4wVfR5urstPVOLMcgqc2ceTyhsxbURfe8nppWFlTKlE3OPPQYOqbjvoYHcKEMo2JfN%2F46Uuld9FRBDLjfNBaMJitsiESW80re1HonTDTJ%2F4XdbKwTduJ0RVEYcl%2Fq7QuE5hwyYYKjVL%2Fm&X-Amz-Signature=6ef28e36ef637cc8b18d9d6f3a886b674d0931a41f15babe281495a7862206c7&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TX6ZKI3H%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T063120Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBrEdGufHTbKEhqB%2BUB35IGYaY2VNWIVKG7r64uM4YOYAiEA8uSOx%2B3oexhJ1pJ9Ztg75QNPgT39ckgAJDqb770%2BQOgqiAQI%2Fv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDBA%2FCfAvfZA%2B1M2HfircAzs5O6fE9yN%2Bv0%2FdC6qUL36O0FcI7zuv9kLAT8JvWiBDGaTBOL2QBADyXMXwJLJieK8YkKDk5byX%2B6DUdm%2BsOQkz06aIpvbTv%2FCp%2FALJbKva5zl5TLcd7sS0GxeXX4VEFr%2FuYlUbYYww2DMbHWaWQ9Ov13XRtE%2F2Wht5EzPjj3Ga10zuizWKRpV3S2ipzqlrnOEQAoy9CViQ2aQ%2FcrQeec4F5a%2Fcw%2BYHVPT2k5yoVL0njgKYpoRJh5J6rvk%2F2AIfbmn%2F9MGApG1O96YntTyzJJkCxUjINsd5ujcsury2YCj0gp%2FZr%2FgcqTp%2FbOw7xFKQXNzljy8qlqzsalixBDzqEG9FhZQLOrXhkMS8%2B%2Bh7KPgWYbgfedDh%2BOL7mVvvj65Mg3RuIZ1tURFQXX5B1ISQ7pp2Iq8ZlXd3vhTL8fG%2BMAQnYeTwY4nkrbATcQKjVDKlf9fG%2FPSM%2B6JExtpPMk0fDASAKgcPgYc%2B2Y1fbn8Y3c1rd%2FG4FQ0fNv7NYHTh65P7QhhgapG1QIInnSkwvzqekLKi40BgS6WrXRKVu40GJiVvpZzU5nfgb7Eq76iwgy77wq%2FLoK7b0Eu8xnsCV3bYTRcr7o%2Fp6V67a5kqY3o%2Bjqf0JuFSPU7S2KYya4y5MLPT6r0GOqUBR9hNXd4eHtYKnQ8NcxVCrAb%2BphObPbqafw6CYLaTycDLzPB%2FtLuIjBwNuxdB4DBGG3KRKpnHw2HSKpP4wVfR5urstPVOLMcgqc2ceTyhsxbURfe8nppWFlTKlE3OPPQYOqbjvoYHcKEMo2JfN%2F46Uuld9FRBDLjfNBaMJitsiESW80re1HonTDTJ%2F4XdbKwTduJ0RVEYcl%2Fq7QuE5hwyYYKjVL%2Fm&X-Amz-Signature=1b4fd0f06ae47da0c2afde155807bff5ae24bdbd49844a379c2e21decd22f8e8&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TX6ZKI3H%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T063120Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBrEdGufHTbKEhqB%2BUB35IGYaY2VNWIVKG7r64uM4YOYAiEA8uSOx%2B3oexhJ1pJ9Ztg75QNPgT39ckgAJDqb770%2BQOgqiAQI%2Fv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDBA%2FCfAvfZA%2B1M2HfircAzs5O6fE9yN%2Bv0%2FdC6qUL36O0FcI7zuv9kLAT8JvWiBDGaTBOL2QBADyXMXwJLJieK8YkKDk5byX%2B6DUdm%2BsOQkz06aIpvbTv%2FCp%2FALJbKva5zl5TLcd7sS0GxeXX4VEFr%2FuYlUbYYww2DMbHWaWQ9Ov13XRtE%2F2Wht5EzPjj3Ga10zuizWKRpV3S2ipzqlrnOEQAoy9CViQ2aQ%2FcrQeec4F5a%2Fcw%2BYHVPT2k5yoVL0njgKYpoRJh5J6rvk%2F2AIfbmn%2F9MGApG1O96YntTyzJJkCxUjINsd5ujcsury2YCj0gp%2FZr%2FgcqTp%2FbOw7xFKQXNzljy8qlqzsalixBDzqEG9FhZQLOrXhkMS8%2B%2Bh7KPgWYbgfedDh%2BOL7mVvvj65Mg3RuIZ1tURFQXX5B1ISQ7pp2Iq8ZlXd3vhTL8fG%2BMAQnYeTwY4nkrbATcQKjVDKlf9fG%2FPSM%2B6JExtpPMk0fDASAKgcPgYc%2B2Y1fbn8Y3c1rd%2FG4FQ0fNv7NYHTh65P7QhhgapG1QIInnSkwvzqekLKi40BgS6WrXRKVu40GJiVvpZzU5nfgb7Eq76iwgy77wq%2FLoK7b0Eu8xnsCV3bYTRcr7o%2Fp6V67a5kqY3o%2Bjqf0JuFSPU7S2KYya4y5MLPT6r0GOqUBR9hNXd4eHtYKnQ8NcxVCrAb%2BphObPbqafw6CYLaTycDLzPB%2FtLuIjBwNuxdB4DBGG3KRKpnHw2HSKpP4wVfR5urstPVOLMcgqc2ceTyhsxbURfe8nppWFlTKlE3OPPQYOqbjvoYHcKEMo2JfN%2F46Uuld9FRBDLjfNBaMJitsiESW80re1HonTDTJ%2F4XdbKwTduJ0RVEYcl%2Fq7QuE5hwyYYKjVL%2Fm&X-Amz-Signature=121b8d8f6f5848af1f517a4433391b8a58e15dcad6887e9a0d54de2e8ed6db9c&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TX6ZKI3H%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T063120Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBrEdGufHTbKEhqB%2BUB35IGYaY2VNWIVKG7r64uM4YOYAiEA8uSOx%2B3oexhJ1pJ9Ztg75QNPgT39ckgAJDqb770%2BQOgqiAQI%2Fv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDBA%2FCfAvfZA%2B1M2HfircAzs5O6fE9yN%2Bv0%2FdC6qUL36O0FcI7zuv9kLAT8JvWiBDGaTBOL2QBADyXMXwJLJieK8YkKDk5byX%2B6DUdm%2BsOQkz06aIpvbTv%2FCp%2FALJbKva5zl5TLcd7sS0GxeXX4VEFr%2FuYlUbYYww2DMbHWaWQ9Ov13XRtE%2F2Wht5EzPjj3Ga10zuizWKRpV3S2ipzqlrnOEQAoy9CViQ2aQ%2FcrQeec4F5a%2Fcw%2BYHVPT2k5yoVL0njgKYpoRJh5J6rvk%2F2AIfbmn%2F9MGApG1O96YntTyzJJkCxUjINsd5ujcsury2YCj0gp%2FZr%2FgcqTp%2FbOw7xFKQXNzljy8qlqzsalixBDzqEG9FhZQLOrXhkMS8%2B%2Bh7KPgWYbgfedDh%2BOL7mVvvj65Mg3RuIZ1tURFQXX5B1ISQ7pp2Iq8ZlXd3vhTL8fG%2BMAQnYeTwY4nkrbATcQKjVDKlf9fG%2FPSM%2B6JExtpPMk0fDASAKgcPgYc%2B2Y1fbn8Y3c1rd%2FG4FQ0fNv7NYHTh65P7QhhgapG1QIInnSkwvzqekLKi40BgS6WrXRKVu40GJiVvpZzU5nfgb7Eq76iwgy77wq%2FLoK7b0Eu8xnsCV3bYTRcr7o%2Fp6V67a5kqY3o%2Bjqf0JuFSPU7S2KYya4y5MLPT6r0GOqUBR9hNXd4eHtYKnQ8NcxVCrAb%2BphObPbqafw6CYLaTycDLzPB%2FtLuIjBwNuxdB4DBGG3KRKpnHw2HSKpP4wVfR5urstPVOLMcgqc2ceTyhsxbURfe8nppWFlTKlE3OPPQYOqbjvoYHcKEMo2JfN%2F46Uuld9FRBDLjfNBaMJitsiESW80re1HonTDTJ%2F4XdbKwTduJ0RVEYcl%2Fq7QuE5hwyYYKjVL%2Fm&X-Amz-Signature=37fd117e7c89a53c724df90d11504009274c2de8af672d60b9d5ab92bd97f73c&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Y3ZX5PC7%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T063120Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCth5pmVvjLZoSPIKr5%2B91nlUZrsubJw8qK2xEembybQQIgLOZ1JKAugwkPmqiKl8bH0ABI2umY5z2e36z%2FuZL9B7UqiAQI%2Fv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCX4eQgPbADfIiLgbircA1IEEH6fEZ9dGWj1v9fFuATvbhLCi%2BrR%2FrPgTsUiNVgaitcVEkc6CDc8pOKd2SJoFija7ZlzehGL2zZ1%2FpokjojPAD9jPA4S79W1GOvVvnUIK3kZPjCodjdvCAzWIW66oxOPeisnlWY%2B9GtKjUpqYM1kC80cCtjxUobD2%2BQJgETnPFOKeronBXLat3Lt91Iwp8D5IkxkwDTxuMcY1nDGG4Yz7FHDY%2FUFlHy4OcfKgfLm3GpxnsuxBHkcWK2%2FHGSCDve3ZgSAG25Ji%2Fm2vwotoQV6%2BXY3trgTkvR3gNTMqqyCn0Lm5W5F94n26uD3vk4MjdpqKMyrAmqXoRqw2nCQxCqBv6op9pilrwT%2B95ij0S1veObhilN6XtFORVcKqY%2FzPaVoYGqkT8O0GdJs6qLwAvSV4tgIh88f%2BjfiHiCYSes5FlPed%2BAj7MGFKuHI31OjPgJ%2FgZfjopvsn4SvV5ed%2B2e8XoBqwQHhS7%2BOT4wRN25uL0StUXIDWWmBwgJJmGG%2FAX0B3RLbWDmr4M7WKwrjhW%2FZM0VH08q5yMfQ0QM5YR6FLyfMPViqgT%2F1CPQ6h%2FgMeDx6TQDrYrJz2qQiZO%2Bp21TOiGS8vF%2FCFd66Tb7w0VoeouF5YUOirVf4AKZuMIPQ6r0GOqUB%2FFGRR89kDCSjy9KO7ZiCcHlIWMAzaoCNcfBxDdVQ6Ly8%2BPG%2BlHfI9Av4oRGB4zFy%2BFXR8IQ%2Bf4aTUGJaE1SEc6jtBBdPmwcudCJcJXEdtZdNAA%2Bxvj23xuarF0JSNEcDeftFfUkFhlxrr1LWgFLDFt5nvhdVCyYL8CdSl9miy89CPvYwAMffv2UGZD0IT1BPUdqJh14qdpcJES0rr7MQGX5Jgitd&X-Amz-Signature=fd75dc9d4628c8bf776b10dee44c1ee0ff0374d2298ab1ab3a10126ce66ea80a&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667RYRDJ2Q%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T063121Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIEKfOb%2F0AizcqgtuSftrjPTjKjT8maLileOQMz0Q9BQ5AiEAuU5Hp6w7ExuA%2FUhbmChT4bU64gCEC%2BGTyX05hR8OqHEqiAQI%2Ff%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGIpaT529jXLgaAhOCrcA1KHbVcGITnW%2FWkxVk%2B9Oh5CwAEuLopaINNeMwzZ7C7pTM0tESGD6dh6ps6RgITAAd%2B8LV9KL6wEBWB4A01SCG48sIS33OjAWHgonaBU%2FmPhxqXzXMfEZXEqJSsIXxVy44%2Fb6G76Hk%2BF%2FGVtf8QvWtNAKynni2WXgPMChmV9Gtoffvu9POszF4wgaNNgAqVl3NyZumAWNOotPUwtJMv2uYhHuXActiRGflThdfcJKwyAQhtb2aRBB11JTI4t6ruKtcBaJG69C3IGrMy2FipE57x%2F5As6kEBurJ%2FHayiti8yiRn9UzSrLVdWpxNi7sQF3oAZN6njRJ1utI1UsKCYocZq26wqRiR6YArk8Jdi2dXLV7lR56P2KADM8rDc1G2NAlgBhjg1ZXy6WO8rUHyszCeacy99BP6CSy0oT2wPzaVFi2dO9O4LCGwya4HWr6eUGraNaQcYudBb9qFJ9DErqOv%2B5lOzx%2FZo%2FW2gxwsYiDFLaMglEagsnqS5h0dHNp0gVQEKzM65VkBu%2Fc4hI3vM2B4QTKn4Km4Smh6%2Bj%2BskyvbZlKAuh0%2BLTPXvPUqyM29VfjhXMgeZ7Y8JHBG7r5YPca4yoRyPbqgEqJdcJ37GuyOY5SvViAbrdqSxIZ99TMNq66r0GOqUBHenNVT2g8y0W9m2ZTABWdRlFni9tyzZYhxFmbeAtwApgn2G0sQzsHtmjoliibVhW9EFG92tmLNbDLDeneLFJUpaNR47HTllhepBBZuwMraYrC%2F%2FzCRiZVeT3Zo%2BNSv5OWX88gsYZh7%2B0FKHfgohTKpvZd1SjiaRn%2BWln8OF0XonMy1TQ04DVOdKix8dXbyGMVoBBNPIcgNS1ksr%2FQr2p%2FNe5%2BMBQ&X-Amz-Signature=5f285baa777658c95c539d5c7f567421abb171d64420ca2e6e809468e864f7eb&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TX6ZKI3H%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T063120Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBrEdGufHTbKEhqB%2BUB35IGYaY2VNWIVKG7r64uM4YOYAiEA8uSOx%2B3oexhJ1pJ9Ztg75QNPgT39ckgAJDqb770%2BQOgqiAQI%2Fv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDBA%2FCfAvfZA%2B1M2HfircAzs5O6fE9yN%2Bv0%2FdC6qUL36O0FcI7zuv9kLAT8JvWiBDGaTBOL2QBADyXMXwJLJieK8YkKDk5byX%2B6DUdm%2BsOQkz06aIpvbTv%2FCp%2FALJbKva5zl5TLcd7sS0GxeXX4VEFr%2FuYlUbYYww2DMbHWaWQ9Ov13XRtE%2F2Wht5EzPjj3Ga10zuizWKRpV3S2ipzqlrnOEQAoy9CViQ2aQ%2FcrQeec4F5a%2Fcw%2BYHVPT2k5yoVL0njgKYpoRJh5J6rvk%2F2AIfbmn%2F9MGApG1O96YntTyzJJkCxUjINsd5ujcsury2YCj0gp%2FZr%2FgcqTp%2FbOw7xFKQXNzljy8qlqzsalixBDzqEG9FhZQLOrXhkMS8%2B%2Bh7KPgWYbgfedDh%2BOL7mVvvj65Mg3RuIZ1tURFQXX5B1ISQ7pp2Iq8ZlXd3vhTL8fG%2BMAQnYeTwY4nkrbATcQKjVDKlf9fG%2FPSM%2B6JExtpPMk0fDASAKgcPgYc%2B2Y1fbn8Y3c1rd%2FG4FQ0fNv7NYHTh65P7QhhgapG1QIInnSkwvzqekLKi40BgS6WrXRKVu40GJiVvpZzU5nfgb7Eq76iwgy77wq%2FLoK7b0Eu8xnsCV3bYTRcr7o%2Fp6V67a5kqY3o%2Bjqf0JuFSPU7S2KYya4y5MLPT6r0GOqUBR9hNXd4eHtYKnQ8NcxVCrAb%2BphObPbqafw6CYLaTycDLzPB%2FtLuIjBwNuxdB4DBGG3KRKpnHw2HSKpP4wVfR5urstPVOLMcgqc2ceTyhsxbURfe8nppWFlTKlE3OPPQYOqbjvoYHcKEMo2JfN%2F46Uuld9FRBDLjfNBaMJitsiESW80re1HonTDTJ%2F4XdbKwTduJ0RVEYcl%2Fq7QuE5hwyYYKjVL%2Fm&X-Amz-Signature=da78849216a55a1560d9e78e5e21bf89a74c912fd49910f59b67e858a95eebe3&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TX6ZKI3H%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T063120Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBrEdGufHTbKEhqB%2BUB35IGYaY2VNWIVKG7r64uM4YOYAiEA8uSOx%2B3oexhJ1pJ9Ztg75QNPgT39ckgAJDqb770%2BQOgqiAQI%2Fv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDBA%2FCfAvfZA%2B1M2HfircAzs5O6fE9yN%2Bv0%2FdC6qUL36O0FcI7zuv9kLAT8JvWiBDGaTBOL2QBADyXMXwJLJieK8YkKDk5byX%2B6DUdm%2BsOQkz06aIpvbTv%2FCp%2FALJbKva5zl5TLcd7sS0GxeXX4VEFr%2FuYlUbYYww2DMbHWaWQ9Ov13XRtE%2F2Wht5EzPjj3Ga10zuizWKRpV3S2ipzqlrnOEQAoy9CViQ2aQ%2FcrQeec4F5a%2Fcw%2BYHVPT2k5yoVL0njgKYpoRJh5J6rvk%2F2AIfbmn%2F9MGApG1O96YntTyzJJkCxUjINsd5ujcsury2YCj0gp%2FZr%2FgcqTp%2FbOw7xFKQXNzljy8qlqzsalixBDzqEG9FhZQLOrXhkMS8%2B%2Bh7KPgWYbgfedDh%2BOL7mVvvj65Mg3RuIZ1tURFQXX5B1ISQ7pp2Iq8ZlXd3vhTL8fG%2BMAQnYeTwY4nkrbATcQKjVDKlf9fG%2FPSM%2B6JExtpPMk0fDASAKgcPgYc%2B2Y1fbn8Y3c1rd%2FG4FQ0fNv7NYHTh65P7QhhgapG1QIInnSkwvzqekLKi40BgS6WrXRKVu40GJiVvpZzU5nfgb7Eq76iwgy77wq%2FLoK7b0Eu8xnsCV3bYTRcr7o%2Fp6V67a5kqY3o%2Bjqf0JuFSPU7S2KYya4y5MLPT6r0GOqUBR9hNXd4eHtYKnQ8NcxVCrAb%2BphObPbqafw6CYLaTycDLzPB%2FtLuIjBwNuxdB4DBGG3KRKpnHw2HSKpP4wVfR5urstPVOLMcgqc2ceTyhsxbURfe8nppWFlTKlE3OPPQYOqbjvoYHcKEMo2JfN%2F46Uuld9FRBDLjfNBaMJitsiESW80re1HonTDTJ%2F4XdbKwTduJ0RVEYcl%2Fq7QuE5hwyYYKjVL%2Fm&X-Amz-Signature=3504afc2b88bf46b6c4da785233cd36e47d80e3d69302282304abce35ef64a95&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TX6ZKI3H%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T063120Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBrEdGufHTbKEhqB%2BUB35IGYaY2VNWIVKG7r64uM4YOYAiEA8uSOx%2B3oexhJ1pJ9Ztg75QNPgT39ckgAJDqb770%2BQOgqiAQI%2Fv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDBA%2FCfAvfZA%2B1M2HfircAzs5O6fE9yN%2Bv0%2FdC6qUL36O0FcI7zuv9kLAT8JvWiBDGaTBOL2QBADyXMXwJLJieK8YkKDk5byX%2B6DUdm%2BsOQkz06aIpvbTv%2FCp%2FALJbKva5zl5TLcd7sS0GxeXX4VEFr%2FuYlUbYYww2DMbHWaWQ9Ov13XRtE%2F2Wht5EzPjj3Ga10zuizWKRpV3S2ipzqlrnOEQAoy9CViQ2aQ%2FcrQeec4F5a%2Fcw%2BYHVPT2k5yoVL0njgKYpoRJh5J6rvk%2F2AIfbmn%2F9MGApG1O96YntTyzJJkCxUjINsd5ujcsury2YCj0gp%2FZr%2FgcqTp%2FbOw7xFKQXNzljy8qlqzsalixBDzqEG9FhZQLOrXhkMS8%2B%2Bh7KPgWYbgfedDh%2BOL7mVvvj65Mg3RuIZ1tURFQXX5B1ISQ7pp2Iq8ZlXd3vhTL8fG%2BMAQnYeTwY4nkrbATcQKjVDKlf9fG%2FPSM%2B6JExtpPMk0fDASAKgcPgYc%2B2Y1fbn8Y3c1rd%2FG4FQ0fNv7NYHTh65P7QhhgapG1QIInnSkwvzqekLKi40BgS6WrXRKVu40GJiVvpZzU5nfgb7Eq76iwgy77wq%2FLoK7b0Eu8xnsCV3bYTRcr7o%2Fp6V67a5kqY3o%2Bjqf0JuFSPU7S2KYya4y5MLPT6r0GOqUBR9hNXd4eHtYKnQ8NcxVCrAb%2BphObPbqafw6CYLaTycDLzPB%2FtLuIjBwNuxdB4DBGG3KRKpnHw2HSKpP4wVfR5urstPVOLMcgqc2ceTyhsxbURfe8nppWFlTKlE3OPPQYOqbjvoYHcKEMo2JfN%2F46Uuld9FRBDLjfNBaMJitsiESW80re1HonTDTJ%2F4XdbKwTduJ0RVEYcl%2Fq7QuE5hwyYYKjVL%2Fm&X-Amz-Signature=285074bc0f39e6f26855f59be59121bc0f152da8ce9ac7e048a84628e09c23cf&X-Amz-SignedHeaders=host&x-id=GetObject)


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

