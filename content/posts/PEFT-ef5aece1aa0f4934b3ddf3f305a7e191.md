---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466YSAYRGW2%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250130T014346Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEJH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCICo7i3TH4vfzIZ8YkEc\
  HGB5eDq%2B%2FQhIU6ek%2BYBbqWmt4AiEA96yh97KodI41Dnm5e7Dk6qFhLkL%2Fwx4nTs8DQLr4\
  FlIqiAQImv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKmO2ZzZAU4RA\
  LNdDircA0McFbjdiPGtPaqV5oyVi8%2Fea4eevk60D89I168BFsuV31j0Rt5toadlJhYWJSxYofxP\
  9%2BsbSeeLbAoMrvfkle1ZEOofX88q6KjawVYsUWKnFHXxlZbj2HBrDyqTE7YM0w4ztKmqVvMp%2F\
  WaBFpkZjEw9q%2F6VFSVT66J0kQ%2FIqo0Y1SfYrySocSF1sTe7jIhegbPAPxMHgtyt%2FlT%2Bio\
  7%2FnTcO%2BoDJWVeUcPidCJ9aDes5yGz0weDvUt19PKcFY%2BWAM7CFirTdM2sMtAOg13bEvVRPM\
  ogte1iVEA0rZ8s97ovH%2FaeRLUx4eLdxN8B7mDHymMqjwqWyZICaoHM8LTBcZYA%2BrHw5OoPemW\
  0RRwfdIfu8gqpDCmEQVgBYS2HPZ5fcZd0Q%2BVwY%2Borhq86tGwGdpVO1bVn1Ns9ww1OF5E6lxEe\
  wiq1wXeecQ2JdfH7GZicd3pxGodxrCHmGt4J%2BPzx4X9rMQN6iKkwMy98VIWC3Dso2tvOFjxcV87\
  wy32zBFPIDTusTKGNFDyFYI8OpTtP6QDG4ovY%2Faf6ScbWot4%2B1AeSjoS51qszSBNIxwufqYHI\
  Vb1lpdRheRljOZXtLmp64JGPPRbKBSaIN05wjUSRVXxh4wm4ZdHDRPmAg8zHPMNaX67wGOqUBmFfs\
  EIlCfvy9vNEBCD1F5Cy09gRxfdTYcUocDJlPb3w9FneK6BQJ5wK9%2FAOfd5rE%2BrBJATEJKYInq\
  f%2FuIplYfKk8%2BJsHk33Wx%2B1CJ%2Bz0rjmjiqYkt%2BH%2Fr8UPfgua70gHpatM%2FXir5XPv\
  NkOL1uZc9%2BeC3GzLxq52Ip7qZX7bfdt64F5SnkSsi8hvCLDYNcryPFC0sgMBhFiyrhdknACCOoS\
  9tc5N&X-Amz-Signature=a06153bacfc4bf5abeb41902a6cb0604f4ad7dc1c13c6babd3435a6\
  7ae84ba7d&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466VPCW265K%2F20250130%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250130T014234Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEJH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIQC6uXN253ozDHotm2jc%2FT6lroq3959mTSbrHL8MZ11M%2FwIgdP79WISH%2BC3Muyar\
        hrT%2B3ZT8mlF7cUII8R59TwWV%2BUYqiAQImv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARA\
        AGgw2Mzc0MjMxODM4MDUiDDCGuguforcMUSGUsyrcA7bCnXD8xOXbBB%2BtcK04Il%2B5%2\
        BfPw5PnaA6isRJzfuKbH%2F1ObdCVgnoSwqAxCFPv2UtGi%2BmJ5IXDrvZS%2BJCMgEP%2F\
        AzuMmmxWQ9P2bWGJx1rEac4PCQ0Q3slBlucTxZa0sK8MJZQmTnWBRMMiTMKUI1nFg%2BHAw\
        Rw9x3dDHyO9I3NnF1Ep1ZaTgL1myvCYUo7ZdiaPBdRKqcgZYgoX0zLFhdbOfD5c9Ia6kPdd\
        4AK4b4kAF0h2HHMSxqVcj4t2I79WTqB39AFrGU9diRhscPW%2BUl4o%2Fp8tYaaqMmWtmHd\
        r4ZkxVc1C0KOxiyGLTPo0ZnkkLEtyyVwku9dPz5SjidcMR3RW6thNzAHso7Ry6JJK%2FHDH\
        i6QqUrZCNd1Wb6p47jdST7ETxG%2BL1%2F2ilWeAvyFetqlzHxGLPtPUsV1PPH1iFgmacbl\
        8invhLecydHra2ZVZ0hWD9wNA6gq%2FvP%2BoFylqw%2FOgu%2BGifWBvxFfTr13b1ewFk3\
        4CynVqD1wTGxnVzu24rRDBX9WExjYu54Om3I3R4sJx7c6V1Q1hBV%2B2AoJL0oU5t08Nw3R\
        jSMhCDICR3Q5p1li3qk0XrnUWgdUCSs3mlUln5ihiS%2BW%2FQkix%2BLXCzaeAk7gTTiAX\
        oYjFhczyOMOiX67wGOqUB9Rwq%2BYNJ0qFfn33y9D3EAkEUIPB%2FzBxgdGjI%2BxD9CbI9\
        6xh1iHjvZJktgaU8EoExxUKjENRTCaHTpJN9%2Bqy4MXQhB2euDNj7yyf3e4nicH%2BPJ7O\
        1JVzd5dTK51SWZW45a28pVr5ryRbQMaM8xaeIwQfihnagNeZnM5r5vHDuzuqq73gR%2BCil\
        8RvS1ab9EMqriH05k8LzK%2FUu5bJDq8gxWNBIfH32&X-Amz-Signature=b7dd6b666d36\
        79f3c6651a13965ce042f03305a7771cef64ca37ff54d4b395ce&X-Amz-SignedHeader\
        s=host&x-id=GetObject"
      expiry_time: "2025-01-30T02:42:34.388Z"
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
UPDATE_TIME: "2025-01-30T01:43:52.556Z"
EXPIRY_TIME: "2025-01-30T02:43:43.883Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UH3MP3KU%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T014344Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD2zo7pfEsdYqa%2F1tgdEfhCMakDutWCPEAr0XIn7B1qOwIgBqDsznc6SEXU2QOL8kC1gZZHH4fr5BEGqitdU5TtRJ0qiAQImv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGRcmIqOu0k3GkwZWCrcAwQQ%2BvUpRmOnnfS3Hk0xz8%2F08OBy9sz1MyqeYXxREssnqXSivNRI8DJNfx1WA0rj3mJB%2FQI31Ua%2BLqnydbewt6myG32yMwRgmCHpNyi3qPO37Y9XWjCZTnqvCpotUnVGFaKv%2BuElSHcUwfVr4scXbxJ9RJfoksU0Enpjyiv29aBYXrXO4TnpXvhVIF%2FjesX%2FQoe9yQ16y65WB9jjfFhflkAsE6ERN18%2FvvnmnqE%2FeW2vUs9rEj2LdpPg%2BX2dlZtOgjW6sXCJ4jN8LRLOcmWtEAMyzOe3EUbJ0MKWyjQVIq2m8RQDEFo8nQlkaUeOfrWRuKpsKClO0gPB22C6YiJNC6BFEb0wLKQvXyHrQloHudoTDMYiOix0K%2FzDN8gbd81fwQQS2IOmEz0Jejfb%2B%2B%2BetSWUe4TtzhzovShlOTs4ZcVFnTxE0t3JE5yeMQP4gg%2BratrR2FRJ3C72ackPsC%2FYeTeENQXJSK86V6c5R85TXT6ooG34%2F3iT%2BD99rTVgjX4%2B8j%2BDMNPRTFq53682MblrYSu0T87XEqfKmY2ILdHQD%2Fbq9LUYGAOL1vFgh3oplIyRclLRSCvRZBXtmLk5nGC3KNq%2FjhOuRRuO4z88ak8USURNFa%2Bpc2WfZ4sru6txML%2BX67wGOqUB6ZObCYTBd9MYmf1Od%2B%2FqWm7jwN2N8poINXimVqHECyQ%2FStbtmaFVmE9Pt2A2iPKzuyfbYXUK17f5mQ1MhgmLsCP%2FW43qTRlGpWHVFl7j8KKpAjML1e4CFhvezApHVQGBu%2FWF1AzRknClGGp3JahzueMgwjp3NYcc7JVVBcZRNEsWpPpcL9C5SdXxnxKLV8gX20soMMPYnZNhNBLG3Vr%2BqRZmjx7n&X-Amz-Signature=2ca5abc42b5ebb1f665512ce66d4b47cf7a1cb0f758a75a92acb0375c2f85591&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UH3MP3KU%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T014344Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD2zo7pfEsdYqa%2F1tgdEfhCMakDutWCPEAr0XIn7B1qOwIgBqDsznc6SEXU2QOL8kC1gZZHH4fr5BEGqitdU5TtRJ0qiAQImv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGRcmIqOu0k3GkwZWCrcAwQQ%2BvUpRmOnnfS3Hk0xz8%2F08OBy9sz1MyqeYXxREssnqXSivNRI8DJNfx1WA0rj3mJB%2FQI31Ua%2BLqnydbewt6myG32yMwRgmCHpNyi3qPO37Y9XWjCZTnqvCpotUnVGFaKv%2BuElSHcUwfVr4scXbxJ9RJfoksU0Enpjyiv29aBYXrXO4TnpXvhVIF%2FjesX%2FQoe9yQ16y65WB9jjfFhflkAsE6ERN18%2FvvnmnqE%2FeW2vUs9rEj2LdpPg%2BX2dlZtOgjW6sXCJ4jN8LRLOcmWtEAMyzOe3EUbJ0MKWyjQVIq2m8RQDEFo8nQlkaUeOfrWRuKpsKClO0gPB22C6YiJNC6BFEb0wLKQvXyHrQloHudoTDMYiOix0K%2FzDN8gbd81fwQQS2IOmEz0Jejfb%2B%2B%2BetSWUe4TtzhzovShlOTs4ZcVFnTxE0t3JE5yeMQP4gg%2BratrR2FRJ3C72ackPsC%2FYeTeENQXJSK86V6c5R85TXT6ooG34%2F3iT%2BD99rTVgjX4%2B8j%2BDMNPRTFq53682MblrYSu0T87XEqfKmY2ILdHQD%2Fbq9LUYGAOL1vFgh3oplIyRclLRSCvRZBXtmLk5nGC3KNq%2FjhOuRRuO4z88ak8USURNFa%2Bpc2WfZ4sru6txML%2BX67wGOqUB6ZObCYTBd9MYmf1Od%2B%2FqWm7jwN2N8poINXimVqHECyQ%2FStbtmaFVmE9Pt2A2iPKzuyfbYXUK17f5mQ1MhgmLsCP%2FW43qTRlGpWHVFl7j8KKpAjML1e4CFhvezApHVQGBu%2FWF1AzRknClGGp3JahzueMgwjp3NYcc7JVVBcZRNEsWpPpcL9C5SdXxnxKLV8gX20soMMPYnZNhNBLG3Vr%2BqRZmjx7n&X-Amz-Signature=591c48847a32437480bd8d099e49d46b587c294f038106ff50d6befac025bee1&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UH3MP3KU%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T014344Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD2zo7pfEsdYqa%2F1tgdEfhCMakDutWCPEAr0XIn7B1qOwIgBqDsznc6SEXU2QOL8kC1gZZHH4fr5BEGqitdU5TtRJ0qiAQImv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGRcmIqOu0k3GkwZWCrcAwQQ%2BvUpRmOnnfS3Hk0xz8%2F08OBy9sz1MyqeYXxREssnqXSivNRI8DJNfx1WA0rj3mJB%2FQI31Ua%2BLqnydbewt6myG32yMwRgmCHpNyi3qPO37Y9XWjCZTnqvCpotUnVGFaKv%2BuElSHcUwfVr4scXbxJ9RJfoksU0Enpjyiv29aBYXrXO4TnpXvhVIF%2FjesX%2FQoe9yQ16y65WB9jjfFhflkAsE6ERN18%2FvvnmnqE%2FeW2vUs9rEj2LdpPg%2BX2dlZtOgjW6sXCJ4jN8LRLOcmWtEAMyzOe3EUbJ0MKWyjQVIq2m8RQDEFo8nQlkaUeOfrWRuKpsKClO0gPB22C6YiJNC6BFEb0wLKQvXyHrQloHudoTDMYiOix0K%2FzDN8gbd81fwQQS2IOmEz0Jejfb%2B%2B%2BetSWUe4TtzhzovShlOTs4ZcVFnTxE0t3JE5yeMQP4gg%2BratrR2FRJ3C72ackPsC%2FYeTeENQXJSK86V6c5R85TXT6ooG34%2F3iT%2BD99rTVgjX4%2B8j%2BDMNPRTFq53682MblrYSu0T87XEqfKmY2ILdHQD%2Fbq9LUYGAOL1vFgh3oplIyRclLRSCvRZBXtmLk5nGC3KNq%2FjhOuRRuO4z88ak8USURNFa%2Bpc2WfZ4sru6txML%2BX67wGOqUB6ZObCYTBd9MYmf1Od%2B%2FqWm7jwN2N8poINXimVqHECyQ%2FStbtmaFVmE9Pt2A2iPKzuyfbYXUK17f5mQ1MhgmLsCP%2FW43qTRlGpWHVFl7j8KKpAjML1e4CFhvezApHVQGBu%2FWF1AzRknClGGp3JahzueMgwjp3NYcc7JVVBcZRNEsWpPpcL9C5SdXxnxKLV8gX20soMMPYnZNhNBLG3Vr%2BqRZmjx7n&X-Amz-Signature=522ea771a8576c60bc0d3d8082a0d56a607219b6494ebb9b577a46f8725f7f9b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UH3MP3KU%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T014344Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD2zo7pfEsdYqa%2F1tgdEfhCMakDutWCPEAr0XIn7B1qOwIgBqDsznc6SEXU2QOL8kC1gZZHH4fr5BEGqitdU5TtRJ0qiAQImv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGRcmIqOu0k3GkwZWCrcAwQQ%2BvUpRmOnnfS3Hk0xz8%2F08OBy9sz1MyqeYXxREssnqXSivNRI8DJNfx1WA0rj3mJB%2FQI31Ua%2BLqnydbewt6myG32yMwRgmCHpNyi3qPO37Y9XWjCZTnqvCpotUnVGFaKv%2BuElSHcUwfVr4scXbxJ9RJfoksU0Enpjyiv29aBYXrXO4TnpXvhVIF%2FjesX%2FQoe9yQ16y65WB9jjfFhflkAsE6ERN18%2FvvnmnqE%2FeW2vUs9rEj2LdpPg%2BX2dlZtOgjW6sXCJ4jN8LRLOcmWtEAMyzOe3EUbJ0MKWyjQVIq2m8RQDEFo8nQlkaUeOfrWRuKpsKClO0gPB22C6YiJNC6BFEb0wLKQvXyHrQloHudoTDMYiOix0K%2FzDN8gbd81fwQQS2IOmEz0Jejfb%2B%2B%2BetSWUe4TtzhzovShlOTs4ZcVFnTxE0t3JE5yeMQP4gg%2BratrR2FRJ3C72ackPsC%2FYeTeENQXJSK86V6c5R85TXT6ooG34%2F3iT%2BD99rTVgjX4%2B8j%2BDMNPRTFq53682MblrYSu0T87XEqfKmY2ILdHQD%2Fbq9LUYGAOL1vFgh3oplIyRclLRSCvRZBXtmLk5nGC3KNq%2FjhOuRRuO4z88ak8USURNFa%2Bpc2WfZ4sru6txML%2BX67wGOqUB6ZObCYTBd9MYmf1Od%2B%2FqWm7jwN2N8poINXimVqHECyQ%2FStbtmaFVmE9Pt2A2iPKzuyfbYXUK17f5mQ1MhgmLsCP%2FW43qTRlGpWHVFl7j8KKpAjML1e4CFhvezApHVQGBu%2FWF1AzRknClGGp3JahzueMgwjp3NYcc7JVVBcZRNEsWpPpcL9C5SdXxnxKLV8gX20soMMPYnZNhNBLG3Vr%2BqRZmjx7n&X-Amz-Signature=74942f023910d4547d0285745f5cc913a411e0c440ee6627b8ffec4e5a4da384&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UH3MP3KU%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T014344Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD2zo7pfEsdYqa%2F1tgdEfhCMakDutWCPEAr0XIn7B1qOwIgBqDsznc6SEXU2QOL8kC1gZZHH4fr5BEGqitdU5TtRJ0qiAQImv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGRcmIqOu0k3GkwZWCrcAwQQ%2BvUpRmOnnfS3Hk0xz8%2F08OBy9sz1MyqeYXxREssnqXSivNRI8DJNfx1WA0rj3mJB%2FQI31Ua%2BLqnydbewt6myG32yMwRgmCHpNyi3qPO37Y9XWjCZTnqvCpotUnVGFaKv%2BuElSHcUwfVr4scXbxJ9RJfoksU0Enpjyiv29aBYXrXO4TnpXvhVIF%2FjesX%2FQoe9yQ16y65WB9jjfFhflkAsE6ERN18%2FvvnmnqE%2FeW2vUs9rEj2LdpPg%2BX2dlZtOgjW6sXCJ4jN8LRLOcmWtEAMyzOe3EUbJ0MKWyjQVIq2m8RQDEFo8nQlkaUeOfrWRuKpsKClO0gPB22C6YiJNC6BFEb0wLKQvXyHrQloHudoTDMYiOix0K%2FzDN8gbd81fwQQS2IOmEz0Jejfb%2B%2B%2BetSWUe4TtzhzovShlOTs4ZcVFnTxE0t3JE5yeMQP4gg%2BratrR2FRJ3C72ackPsC%2FYeTeENQXJSK86V6c5R85TXT6ooG34%2F3iT%2BD99rTVgjX4%2B8j%2BDMNPRTFq53682MblrYSu0T87XEqfKmY2ILdHQD%2Fbq9LUYGAOL1vFgh3oplIyRclLRSCvRZBXtmLk5nGC3KNq%2FjhOuRRuO4z88ak8USURNFa%2Bpc2WfZ4sru6txML%2BX67wGOqUB6ZObCYTBd9MYmf1Od%2B%2FqWm7jwN2N8poINXimVqHECyQ%2FStbtmaFVmE9Pt2A2iPKzuyfbYXUK17f5mQ1MhgmLsCP%2FW43qTRlGpWHVFl7j8KKpAjML1e4CFhvezApHVQGBu%2FWF1AzRknClGGp3JahzueMgwjp3NYcc7JVVBcZRNEsWpPpcL9C5SdXxnxKLV8gX20soMMPYnZNhNBLG3Vr%2BqRZmjx7n&X-Amz-Signature=fe49a5e24d8126d87a521f8766d48ea8cf9b7dd10d7dd24355016ccb1feb1034&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XI4NLJLK%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T014345Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIGaYvqsuZDzlBggUSMQwBawKXDresBS6cIwbjfIstjDwAiBO3rwL0alDGxGiBGm2Z3tU74EkBVhnINy73kbPmSKVcSqIBAia%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM84rN5RlGZfm2KZYiKtwDiwFsxDZ5ecEHFFQFMxVfVIx9xtWjMtlJT1cvV4QsfcVxh3zuu3Yrd5olLduKEKSr3szDEHEeZT672xnE2TTTkuUwIne348HrH4k1kB6tFb9UBYAeniionOTntmrU4Kh8zsVqdhdw%2B%2F%2FYOxPEdEeujBkYdm4AFlJVzWS1pXb%2Fwwlebg3cNGjZonP0hZiumzGoCOK8ZZPGmDywPJUnRUJEhqatDXiP6Ngshs5%2B7WZI3fX%2FvYarJBFfrQ%2FKPMjxwXn6Mp8KM4LsCWS1zppOfz1pjL4Uv0bwtobk1zHzV4HhD4uEc4PzNPsbD5I6DHjs%2BM497QLevFhQ8KkPDLkLh04x5z9yKstEONMP1lWs36pEAAofvzaqQsp1whQAlIJX0xjFhMsxHB%2FIglEA2ExcNHP2mPPXv6jmANYmnKljvSg0oaI8xd7g%2FFkkFkauA9fUs%2F0ClT3QRWlrV9Hx793DBF3C%2FqGGbCwCGLSmplZADdjMt35XjtfQ1Fdz7uydBT3%2Bws8%2BaytocyVKi1v3hCcEJ%2F9svCAIycTdL4BuopWKjHJ0LBy8RA5uH47sWCKQy6Pqm5r%2FcC%2BQNH1HevlY4nsOwmImUN3i8%2BAhJ8naiwVTVjUzlkW9SlP0a7tq86BsjOww2JjrvAY6pgF7RZ4gS4a6zvCyDYY4dBHRNoqOsIevQ14%2BwR2yAimBPYvvAesvZ7dOjWZRsc6CBFBqRULz175ZSyEnyAiVUBhsqoh4zkAH4LCFDB6eDz0t1v8gPTOdweYDhvMdcNozxBgMX4K0LGpYm4nGSlxr7X%2FEGasTdLaFUxteGObUnJ%2BxihnOHe5PBiv4s3NikyW%2FmTd16ev1cZ90dZUgmGsqMvijzk%2F3WIha&X-Amz-Signature=55cefba03c960e9edf84f507704a14fa55bbf0ee8bfdcc56a50ad3e7dc62ad65&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z2XYLWAK%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T014345Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCWhhHoZwG6hpAFgbvaVHvLFwIezFtJrS5cdJ5SEwRGNwIhAPQIv6dE2oP8TCyLTuPixiB41sriV6inO3Xy4cJkDjMQKogECJr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyeRNQ5j4jNon%2FnlXkq3AOYHlxN8io3msHLUyFRchvIETPq74MnBPhbtbqNi5EvakKnCb7DCR2bFPIiHQFq6QLudanVZAcz58i3RcZbd4BsAiX2AIdBowWs656xE4%2FfUdSa9VLJSSNCvZR4THm9iqCNZ7nBDg5ZmoEVjm1%2Bt3d07mkDMdHxDgtC%2B1V0%2FUZyM6aqAENc7lm1yQnVDkOjaTl3Eum8UoJ74XWYMqMATyXp2NWVvZarTlOFkIGd1Q9w9uWKAAJ6suUdDD4%2Bh7Gxhsuz7Gqmuj07u4gSmXxeLRDYNTs9QewBzmwi6YacgPqLJu5ORUk0cWuN9pbRIJWulXEYew7bMSqyx4A1og11CuV6%2BGR%2B4BVo8PbegRLLfoOZIUJUgELwJ0o5rF61Wq8PJZYocEg4K6dSzyrA9pgLRBlbVEB3CI3E6RJI79aNRta7uAZAUJD0C6qOw89KXhUekwzfovMCCMa59N19MSSnuv2MIcp0E9jhPIbTyMU%2FNCst49SaTiUoa%2F8rTZs%2BPOhFm24cl8OWpUQ4Tj5bnZcOgq9wd7LIirr5nemwHFY1fe3HMGjQ97Im02m7eS9wKyvFkKBxpa4eNsWWne3rljTJJmOgocaeJfZrkUwdE4xXmvlraEHPPWNlSbuf%2BarmnzDLl%2Bu8BjqkAR%2B%2B3LQOwR9uNvbfaYpOl%2B2YYjnSAIU5Lh2eG8baN%2Fy%2FH0FtMbT4ynBM99wM15WnHt%2BuNhz9PL6XUjdWnIGRm5czo70jrE2NKEVYMtYP7TNUjV%2BvCwTGRtCYopnBmU9vY%2FivdALrdksuMXbnIwXSLDPxfOvwYZwa7Nxfy5oYpT8YypVIcaL1XZCg%2FiODJBBzGCAE4Q4DUIyhRfWL%2FENv%2BK6wmeZG&X-Amz-Signature=06872157f501fd14f3b9ea36dae854ca344df844458ae36cf12ebd6d17ce7183&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UH3MP3KU%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T014344Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD2zo7pfEsdYqa%2F1tgdEfhCMakDutWCPEAr0XIn7B1qOwIgBqDsznc6SEXU2QOL8kC1gZZHH4fr5BEGqitdU5TtRJ0qiAQImv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGRcmIqOu0k3GkwZWCrcAwQQ%2BvUpRmOnnfS3Hk0xz8%2F08OBy9sz1MyqeYXxREssnqXSivNRI8DJNfx1WA0rj3mJB%2FQI31Ua%2BLqnydbewt6myG32yMwRgmCHpNyi3qPO37Y9XWjCZTnqvCpotUnVGFaKv%2BuElSHcUwfVr4scXbxJ9RJfoksU0Enpjyiv29aBYXrXO4TnpXvhVIF%2FjesX%2FQoe9yQ16y65WB9jjfFhflkAsE6ERN18%2FvvnmnqE%2FeW2vUs9rEj2LdpPg%2BX2dlZtOgjW6sXCJ4jN8LRLOcmWtEAMyzOe3EUbJ0MKWyjQVIq2m8RQDEFo8nQlkaUeOfrWRuKpsKClO0gPB22C6YiJNC6BFEb0wLKQvXyHrQloHudoTDMYiOix0K%2FzDN8gbd81fwQQS2IOmEz0Jejfb%2B%2B%2BetSWUe4TtzhzovShlOTs4ZcVFnTxE0t3JE5yeMQP4gg%2BratrR2FRJ3C72ackPsC%2FYeTeENQXJSK86V6c5R85TXT6ooG34%2F3iT%2BD99rTVgjX4%2B8j%2BDMNPRTFq53682MblrYSu0T87XEqfKmY2ILdHQD%2Fbq9LUYGAOL1vFgh3oplIyRclLRSCvRZBXtmLk5nGC3KNq%2FjhOuRRuO4z88ak8USURNFa%2Bpc2WfZ4sru6txML%2BX67wGOqUB6ZObCYTBd9MYmf1Od%2B%2FqWm7jwN2N8poINXimVqHECyQ%2FStbtmaFVmE9Pt2A2iPKzuyfbYXUK17f5mQ1MhgmLsCP%2FW43qTRlGpWHVFl7j8KKpAjML1e4CFhvezApHVQGBu%2FWF1AzRknClGGp3JahzueMgwjp3NYcc7JVVBcZRNEsWpPpcL9C5SdXxnxKLV8gX20soMMPYnZNhNBLG3Vr%2BqRZmjx7n&X-Amz-Signature=9ff21ddbc91983a2a27d581e07fc1c64d1a80653386d93ebdc03d50084c69b0e&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UH3MP3KU%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T014344Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD2zo7pfEsdYqa%2F1tgdEfhCMakDutWCPEAr0XIn7B1qOwIgBqDsznc6SEXU2QOL8kC1gZZHH4fr5BEGqitdU5TtRJ0qiAQImv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGRcmIqOu0k3GkwZWCrcAwQQ%2BvUpRmOnnfS3Hk0xz8%2F08OBy9sz1MyqeYXxREssnqXSivNRI8DJNfx1WA0rj3mJB%2FQI31Ua%2BLqnydbewt6myG32yMwRgmCHpNyi3qPO37Y9XWjCZTnqvCpotUnVGFaKv%2BuElSHcUwfVr4scXbxJ9RJfoksU0Enpjyiv29aBYXrXO4TnpXvhVIF%2FjesX%2FQoe9yQ16y65WB9jjfFhflkAsE6ERN18%2FvvnmnqE%2FeW2vUs9rEj2LdpPg%2BX2dlZtOgjW6sXCJ4jN8LRLOcmWtEAMyzOe3EUbJ0MKWyjQVIq2m8RQDEFo8nQlkaUeOfrWRuKpsKClO0gPB22C6YiJNC6BFEb0wLKQvXyHrQloHudoTDMYiOix0K%2FzDN8gbd81fwQQS2IOmEz0Jejfb%2B%2B%2BetSWUe4TtzhzovShlOTs4ZcVFnTxE0t3JE5yeMQP4gg%2BratrR2FRJ3C72ackPsC%2FYeTeENQXJSK86V6c5R85TXT6ooG34%2F3iT%2BD99rTVgjX4%2B8j%2BDMNPRTFq53682MblrYSu0T87XEqfKmY2ILdHQD%2Fbq9LUYGAOL1vFgh3oplIyRclLRSCvRZBXtmLk5nGC3KNq%2FjhOuRRuO4z88ak8USURNFa%2Bpc2WfZ4sru6txML%2BX67wGOqUB6ZObCYTBd9MYmf1Od%2B%2FqWm7jwN2N8poINXimVqHECyQ%2FStbtmaFVmE9Pt2A2iPKzuyfbYXUK17f5mQ1MhgmLsCP%2FW43qTRlGpWHVFl7j8KKpAjML1e4CFhvezApHVQGBu%2FWF1AzRknClGGp3JahzueMgwjp3NYcc7JVVBcZRNEsWpPpcL9C5SdXxnxKLV8gX20soMMPYnZNhNBLG3Vr%2BqRZmjx7n&X-Amz-Signature=cb0389ae8a5d23a65a6341204c529cd98cea4a2f89b535132d3d47c1934bc5fa&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UH3MP3KU%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T014344Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD2zo7pfEsdYqa%2F1tgdEfhCMakDutWCPEAr0XIn7B1qOwIgBqDsznc6SEXU2QOL8kC1gZZHH4fr5BEGqitdU5TtRJ0qiAQImv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGRcmIqOu0k3GkwZWCrcAwQQ%2BvUpRmOnnfS3Hk0xz8%2F08OBy9sz1MyqeYXxREssnqXSivNRI8DJNfx1WA0rj3mJB%2FQI31Ua%2BLqnydbewt6myG32yMwRgmCHpNyi3qPO37Y9XWjCZTnqvCpotUnVGFaKv%2BuElSHcUwfVr4scXbxJ9RJfoksU0Enpjyiv29aBYXrXO4TnpXvhVIF%2FjesX%2FQoe9yQ16y65WB9jjfFhflkAsE6ERN18%2FvvnmnqE%2FeW2vUs9rEj2LdpPg%2BX2dlZtOgjW6sXCJ4jN8LRLOcmWtEAMyzOe3EUbJ0MKWyjQVIq2m8RQDEFo8nQlkaUeOfrWRuKpsKClO0gPB22C6YiJNC6BFEb0wLKQvXyHrQloHudoTDMYiOix0K%2FzDN8gbd81fwQQS2IOmEz0Jejfb%2B%2B%2BetSWUe4TtzhzovShlOTs4ZcVFnTxE0t3JE5yeMQP4gg%2BratrR2FRJ3C72ackPsC%2FYeTeENQXJSK86V6c5R85TXT6ooG34%2F3iT%2BD99rTVgjX4%2B8j%2BDMNPRTFq53682MblrYSu0T87XEqfKmY2ILdHQD%2Fbq9LUYGAOL1vFgh3oplIyRclLRSCvRZBXtmLk5nGC3KNq%2FjhOuRRuO4z88ak8USURNFa%2Bpc2WfZ4sru6txML%2BX67wGOqUB6ZObCYTBd9MYmf1Od%2B%2FqWm7jwN2N8poINXimVqHECyQ%2FStbtmaFVmE9Pt2A2iPKzuyfbYXUK17f5mQ1MhgmLsCP%2FW43qTRlGpWHVFl7j8KKpAjML1e4CFhvezApHVQGBu%2FWF1AzRknClGGp3JahzueMgwjp3NYcc7JVVBcZRNEsWpPpcL9C5SdXxnxKLV8gX20soMMPYnZNhNBLG3Vr%2BqRZmjx7n&X-Amz-Signature=05161d72a1b02ee285c253f79cdf989463beaa51a612d56c491641909f216b08&X-Amz-SignedHeaders=host&x-id=GetObject)


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

