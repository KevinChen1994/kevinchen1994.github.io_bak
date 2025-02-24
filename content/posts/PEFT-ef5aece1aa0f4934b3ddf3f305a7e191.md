---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466SLPBLBBG%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250224T222345Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEP7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDEDp2Jor37fCD7BSm\
  JES7bpkuojyZurmFeWHbfCtjyaAIgIkrRy5Hh9E%2BJ669tpEvzwQHWz7%2FL%2FAoMINBYhk3%2F\
  3MYq%2FwMINxAAGgw2Mzc0MjMxODM4MDUiDJ5eUCaqj4jKwOg0HircAyYr8q8IcmbZO4TsEv8MVdy\
  43pSFyW7jYo1TanI1mj3wQD6oDoOPfRB37EruBSwIWJ7rDRdbBPK7F%2FfiFKREclxQVj8b9lp%2F\
  MIrOb2ezD%2BTMbnjGuJ13dFEsz21u9tY7ckkSCCzrSrwo9EUOIgrFwEnIUgPIoWoFA8sdC94bSeY\
  1tZVFQNwY3%2BCpjQBM9dPoeIew2q7nqSMxyRSjyH3B%2B0aldAilEIFY9ZPlLmgs%2BcmiGVCvqA\
  %2BMyEaAWTmfbH2ROeQRoPaHIvJFyzSwD7pT7XnTIhOgi7e8onCm7fvqH3BD4qv5HW8zR%2FPm1nJ\
  jnEwd%2FcvpQlmlDsq4PSyY%2BoS0SnWYpsrKHIPBmyvgplfq88NjKZGueikEWHNZatA61pzGzsZw\
  nfE83CMtsTPGC3ROStLeVpblEGxb64nt%2BXMghF3DXYSOZ051opr2giUKj4Ypv4jEGRsXs0Wdo6U\
  akVC6yHxZzpA%2Br4ugoivuDqDLFjQhS8FKo1wkk9xWCnDhTqbZBF6Xyimcdv5038ADUS5FwQ2%2B\
  DUx4y9R%2FWaiZcM7P6mqyDb6Fpcw25zP6royosXsy9gEAsKVp89AhsL8lRotRxr%2Fm7vAXD%2Fj\
  QvWT%2BIPbC%2BRpZbGgbRgmVMHDkPDhSMLvV870GOqUBt8LZ488YEdW5KuU6KG5HZB5JB19DtuOZ\
  i0Y0JjSV6xSyfreeDSaUiqnKuJvjTk4VLsgTpblYcd1yK4%2Bv52wSY%2FjcpMRAiAt2yGTZ1nhVl\
  NlerB3pAIOyNbF7%2BNllSCB1JlHfy%2Bfg%2BIkkIQbOudXiVfMU4FujF6zTjSVnD%2BzLh%2Bet\
  7U4f1XCoiN%2F4WjO2jg6omuS%2BS2hAjvZR0Hu3YnNEr9K8XRlE&X-Amz-Signature=a90c9b3c\
  8db8ebc2e8959a82352bd3f067f4529425b6811aa191e445e24517fc&X-Amz-SignedHeaders=\
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
        redential=ASIAZI2LB4663XAIKKAY%2F20250224%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250224T222207Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEP7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIHWa%2FtgNHsswscMHPc53IClnML6k9jLtqTwzIpcbCVZOAiEAyQZ2p2Fd5GEycb7kei%2\
        FQ98Qitcu6zG%2BWzohHba0Lr4Uq%2FwMINxAAGgw2Mzc0MjMxODM4MDUiDPfSGLZP3LcsA\
        %2FgRyCrcA1qqCPWYMHdxmaJmpc9uM9GCLh5QxT0yv4r7h0h19UtFXZDnrXX%2F%2FHhNwM\
        TPdIy4Ld5JkSYu5B12kL1kexlw14FgTiOQjQ2AVVxd9iw7MU%2FJaOHKbgxirg0e%2FGlB%\
        2F%2FpIDZtWwlcWtVQmihLbiNtNx%2FVTtGqcJbzoyYNzpKLQrJCWoHhICG9IQl56t7IHfe\
        QT3Ra95qSWvVV83YmKf15SCzYwEz25kPOoHK%2BIJ1PFCwIcTlq5kX7J8qrlJw%2BiKdNVn\
        FpBiJrxvEzUBNA696bZSr4FMRIc1wGewTkMrZ%2F2j8ET7U9gCe%2BpKjhJWDPcxht6J6hw\
        XIWkfbiCbPsY9b%2FOaj%2BqqmcMbo1yC3oWvnvr2WG6WG9V3aK%2Bw4uI5a4gpNJovRdEr\
        XIKMCUraH3IGgAchpSUIS6peIYvFzQ1TZr8a4O%2FyM%2FXMVG8eqSaVEMULQfh67Oae9nV\
        mGeM8lkA0wDjniw9AjcbBVSvhGt38kOvXE3zH6Mo2qK2OiNgUWrS0XtueQNA4YzzImapeCO\
        tlqjqtOG8wfyObX2u7pTHqwq%2Fx%2BPnkTYnmE9Yw%2BI1LYR6mU33T4Kdr%2ByupqNA2T\
        g2VxwCRrb927LGda9maF88qd%2FqN2m41%2F3XMBfxRkv%2BqREAMKXW870GOqUBNoQwHce\
        %2Fy%2FDNT5FcIE5GIBXwCHtVAQPlztrE0C4XwuIy5T1W4s%2FpbrkpMPq1xSfV%2F%2FJS\
        8Q6GKkkyckXrSHn%2BwSjJWabHz624SMCYEjmNN8HK3v2e7WnfE9c6Zw8m5apWxz2Zr2w7U\
        XP%2FV3iI%2BUir%2FcSUCNk4Kb0nRf6a8ytuTKmzTkOEwzt%2BsJ%2FwFdRg1S3Tw7SJF%\
        2FI8ak1UPkL7%2BaXPENIRBs1X&X-Amz-Signature=cc0fa3e8336986556c2631d537b1\
        1761088734e9f2d1b25c8099c7c17f27c504&X-Amz-SignedHeaders=host&x-id=GetO\
        bject"
      expiry_time: "2025-02-24T23:22:07.563Z"
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
UPDATE_TIME: "2025-02-24T22:23:53.187Z"
EXPIRY_TIME: "2025-02-24T23:23:40.730Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466333Y3XTF%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T222341Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCID0h2immnrxAV0XbhUYyCFHes7Ly2FacOMyD1puYiLU8AiEA1QHlgfvka7XmACvOFYVjiEjvV8ik7bBYB8SBiiPhoMMq%2FwMINxAAGgw2Mzc0MjMxODM4MDUiDJmfjEgxmmNxx5yTQCrcA9xunUNU8XG0DjNQ3A58nXhu6ngKBwT2a%2B2d9Puv7gcWqCHQ%2BUWHZeyUiiJnLw6UF8J2fVMgDXQNlyPdp2naNIesk9J4%2BORucw5sPwQ7eSnT%2BwxaTFYcvk5%2FOV9lNN6NGdgE15SpYIk8MD19Lav04sduF5NkbX%2FunOKiJkdGJ7Um8rBVE%2FEA9aRTvH5NtWTunyhJk6c1%2F59jeMXDNOWwTlunPkTJ4%2FkVqkBDE%2FKd47YxHbFgDNV%2BN3H97c%2BnkjsabMO2UU%2Fd9XsvhrzJDRvyqDz5kPPJ7rLnUB2zoY%2Fin9Lw6dPNMeRQ14A2%2Bvyai9BZlbzGLsHYHuS8fyR7wn6y%2Bt4RjTXg2FqvL7hVBNjpyquJHbIpxhQ%2FL%2Fy4hYZegMdqpKlLPPmESHjq2ER5xBlWWF%2FZRjZ4sgP2sBihusYrmp3JQyABsvQNHdKcQrF%2B02snjptSj6zSXQ7Lk5sCZYWPZ8NaZyc85MBhaKHkd9qZ%2BoPuwTzD7sK31tqaXMaCAY9gQn9AHPIeE7zUCtX%2BqtSjClwSTSP%2BO5dGf9tPDku%2FPsCFzzWztJH%2FSN67McjKAKt2tHFrrzHVvxHzspxgVtbmsRQ9%2FhB8MHA1MKZ8baa4XY2Zj6CeZD7bbVXAdK9gMKjW870GOqUBm0Td7bSQGLjOo6XNzKf%2FaXcCnHklztWhiL%2Bc5101yoDjF96643bXCCpdrzdyrF94VTs2dy2ESfTLVHfBj0e%2FEnreYBtj8lC22%2BZWHEHiza%2BjszsKEN2oqqKDxE8eXve3cEvK%2FvM4gkIR2%2BiFX4qBa1sKu%2FZu0x%2F8uTQT8yVx%2F%2FoT7eo2igWRMDLtaPur4Szafg4%2Bzjay4%2BTXeZe4dbHos%2Frz2BMM&X-Amz-Signature=6ab5dc22ad7f55f2259cde60f7f84d2abfd88e46d21a3ffa97d2ef573820c014&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466333Y3XTF%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T222341Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCID0h2immnrxAV0XbhUYyCFHes7Ly2FacOMyD1puYiLU8AiEA1QHlgfvka7XmACvOFYVjiEjvV8ik7bBYB8SBiiPhoMMq%2FwMINxAAGgw2Mzc0MjMxODM4MDUiDJmfjEgxmmNxx5yTQCrcA9xunUNU8XG0DjNQ3A58nXhu6ngKBwT2a%2B2d9Puv7gcWqCHQ%2BUWHZeyUiiJnLw6UF8J2fVMgDXQNlyPdp2naNIesk9J4%2BORucw5sPwQ7eSnT%2BwxaTFYcvk5%2FOV9lNN6NGdgE15SpYIk8MD19Lav04sduF5NkbX%2FunOKiJkdGJ7Um8rBVE%2FEA9aRTvH5NtWTunyhJk6c1%2F59jeMXDNOWwTlunPkTJ4%2FkVqkBDE%2FKd47YxHbFgDNV%2BN3H97c%2BnkjsabMO2UU%2Fd9XsvhrzJDRvyqDz5kPPJ7rLnUB2zoY%2Fin9Lw6dPNMeRQ14A2%2Bvyai9BZlbzGLsHYHuS8fyR7wn6y%2Bt4RjTXg2FqvL7hVBNjpyquJHbIpxhQ%2FL%2Fy4hYZegMdqpKlLPPmESHjq2ER5xBlWWF%2FZRjZ4sgP2sBihusYrmp3JQyABsvQNHdKcQrF%2B02snjptSj6zSXQ7Lk5sCZYWPZ8NaZyc85MBhaKHkd9qZ%2BoPuwTzD7sK31tqaXMaCAY9gQn9AHPIeE7zUCtX%2BqtSjClwSTSP%2BO5dGf9tPDku%2FPsCFzzWztJH%2FSN67McjKAKt2tHFrrzHVvxHzspxgVtbmsRQ9%2FhB8MHA1MKZ8baa4XY2Zj6CeZD7bbVXAdK9gMKjW870GOqUBm0Td7bSQGLjOo6XNzKf%2FaXcCnHklztWhiL%2Bc5101yoDjF96643bXCCpdrzdyrF94VTs2dy2ESfTLVHfBj0e%2FEnreYBtj8lC22%2BZWHEHiza%2BjszsKEN2oqqKDxE8eXve3cEvK%2FvM4gkIR2%2BiFX4qBa1sKu%2FZu0x%2F8uTQT8yVx%2F%2FoT7eo2igWRMDLtaPur4Szafg4%2Bzjay4%2BTXeZe4dbHos%2Frz2BMM&X-Amz-Signature=55603a2b109f4088e3e643c2e7343f46c2eb01a19827752fa9ca81234e041151&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466333Y3XTF%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T222341Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCID0h2immnrxAV0XbhUYyCFHes7Ly2FacOMyD1puYiLU8AiEA1QHlgfvka7XmACvOFYVjiEjvV8ik7bBYB8SBiiPhoMMq%2FwMINxAAGgw2Mzc0MjMxODM4MDUiDJmfjEgxmmNxx5yTQCrcA9xunUNU8XG0DjNQ3A58nXhu6ngKBwT2a%2B2d9Puv7gcWqCHQ%2BUWHZeyUiiJnLw6UF8J2fVMgDXQNlyPdp2naNIesk9J4%2BORucw5sPwQ7eSnT%2BwxaTFYcvk5%2FOV9lNN6NGdgE15SpYIk8MD19Lav04sduF5NkbX%2FunOKiJkdGJ7Um8rBVE%2FEA9aRTvH5NtWTunyhJk6c1%2F59jeMXDNOWwTlunPkTJ4%2FkVqkBDE%2FKd47YxHbFgDNV%2BN3H97c%2BnkjsabMO2UU%2Fd9XsvhrzJDRvyqDz5kPPJ7rLnUB2zoY%2Fin9Lw6dPNMeRQ14A2%2Bvyai9BZlbzGLsHYHuS8fyR7wn6y%2Bt4RjTXg2FqvL7hVBNjpyquJHbIpxhQ%2FL%2Fy4hYZegMdqpKlLPPmESHjq2ER5xBlWWF%2FZRjZ4sgP2sBihusYrmp3JQyABsvQNHdKcQrF%2B02snjptSj6zSXQ7Lk5sCZYWPZ8NaZyc85MBhaKHkd9qZ%2BoPuwTzD7sK31tqaXMaCAY9gQn9AHPIeE7zUCtX%2BqtSjClwSTSP%2BO5dGf9tPDku%2FPsCFzzWztJH%2FSN67McjKAKt2tHFrrzHVvxHzspxgVtbmsRQ9%2FhB8MHA1MKZ8baa4XY2Zj6CeZD7bbVXAdK9gMKjW870GOqUBm0Td7bSQGLjOo6XNzKf%2FaXcCnHklztWhiL%2Bc5101yoDjF96643bXCCpdrzdyrF94VTs2dy2ESfTLVHfBj0e%2FEnreYBtj8lC22%2BZWHEHiza%2BjszsKEN2oqqKDxE8eXve3cEvK%2FvM4gkIR2%2BiFX4qBa1sKu%2FZu0x%2F8uTQT8yVx%2F%2FoT7eo2igWRMDLtaPur4Szafg4%2Bzjay4%2BTXeZe4dbHos%2Frz2BMM&X-Amz-Signature=2eeab1a92a88c69e59d429119988ec9c5c61a1fb08a6fbf45d72e9a4d9f37e7f&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466333Y3XTF%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T222341Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCID0h2immnrxAV0XbhUYyCFHes7Ly2FacOMyD1puYiLU8AiEA1QHlgfvka7XmACvOFYVjiEjvV8ik7bBYB8SBiiPhoMMq%2FwMINxAAGgw2Mzc0MjMxODM4MDUiDJmfjEgxmmNxx5yTQCrcA9xunUNU8XG0DjNQ3A58nXhu6ngKBwT2a%2B2d9Puv7gcWqCHQ%2BUWHZeyUiiJnLw6UF8J2fVMgDXQNlyPdp2naNIesk9J4%2BORucw5sPwQ7eSnT%2BwxaTFYcvk5%2FOV9lNN6NGdgE15SpYIk8MD19Lav04sduF5NkbX%2FunOKiJkdGJ7Um8rBVE%2FEA9aRTvH5NtWTunyhJk6c1%2F59jeMXDNOWwTlunPkTJ4%2FkVqkBDE%2FKd47YxHbFgDNV%2BN3H97c%2BnkjsabMO2UU%2Fd9XsvhrzJDRvyqDz5kPPJ7rLnUB2zoY%2Fin9Lw6dPNMeRQ14A2%2Bvyai9BZlbzGLsHYHuS8fyR7wn6y%2Bt4RjTXg2FqvL7hVBNjpyquJHbIpxhQ%2FL%2Fy4hYZegMdqpKlLPPmESHjq2ER5xBlWWF%2FZRjZ4sgP2sBihusYrmp3JQyABsvQNHdKcQrF%2B02snjptSj6zSXQ7Lk5sCZYWPZ8NaZyc85MBhaKHkd9qZ%2BoPuwTzD7sK31tqaXMaCAY9gQn9AHPIeE7zUCtX%2BqtSjClwSTSP%2BO5dGf9tPDku%2FPsCFzzWztJH%2FSN67McjKAKt2tHFrrzHVvxHzspxgVtbmsRQ9%2FhB8MHA1MKZ8baa4XY2Zj6CeZD7bbVXAdK9gMKjW870GOqUBm0Td7bSQGLjOo6XNzKf%2FaXcCnHklztWhiL%2Bc5101yoDjF96643bXCCpdrzdyrF94VTs2dy2ESfTLVHfBj0e%2FEnreYBtj8lC22%2BZWHEHiza%2BjszsKEN2oqqKDxE8eXve3cEvK%2FvM4gkIR2%2BiFX4qBa1sKu%2FZu0x%2F8uTQT8yVx%2F%2FoT7eo2igWRMDLtaPur4Szafg4%2Bzjay4%2BTXeZe4dbHos%2Frz2BMM&X-Amz-Signature=4055249a3b0cf8013b584637dbaeedf21b21a37b5a8173e58766a80420093d46&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466333Y3XTF%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T222341Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCID0h2immnrxAV0XbhUYyCFHes7Ly2FacOMyD1puYiLU8AiEA1QHlgfvka7XmACvOFYVjiEjvV8ik7bBYB8SBiiPhoMMq%2FwMINxAAGgw2Mzc0MjMxODM4MDUiDJmfjEgxmmNxx5yTQCrcA9xunUNU8XG0DjNQ3A58nXhu6ngKBwT2a%2B2d9Puv7gcWqCHQ%2BUWHZeyUiiJnLw6UF8J2fVMgDXQNlyPdp2naNIesk9J4%2BORucw5sPwQ7eSnT%2BwxaTFYcvk5%2FOV9lNN6NGdgE15SpYIk8MD19Lav04sduF5NkbX%2FunOKiJkdGJ7Um8rBVE%2FEA9aRTvH5NtWTunyhJk6c1%2F59jeMXDNOWwTlunPkTJ4%2FkVqkBDE%2FKd47YxHbFgDNV%2BN3H97c%2BnkjsabMO2UU%2Fd9XsvhrzJDRvyqDz5kPPJ7rLnUB2zoY%2Fin9Lw6dPNMeRQ14A2%2Bvyai9BZlbzGLsHYHuS8fyR7wn6y%2Bt4RjTXg2FqvL7hVBNjpyquJHbIpxhQ%2FL%2Fy4hYZegMdqpKlLPPmESHjq2ER5xBlWWF%2FZRjZ4sgP2sBihusYrmp3JQyABsvQNHdKcQrF%2B02snjptSj6zSXQ7Lk5sCZYWPZ8NaZyc85MBhaKHkd9qZ%2BoPuwTzD7sK31tqaXMaCAY9gQn9AHPIeE7zUCtX%2BqtSjClwSTSP%2BO5dGf9tPDku%2FPsCFzzWztJH%2FSN67McjKAKt2tHFrrzHVvxHzspxgVtbmsRQ9%2FhB8MHA1MKZ8baa4XY2Zj6CeZD7bbVXAdK9gMKjW870GOqUBm0Td7bSQGLjOo6XNzKf%2FaXcCnHklztWhiL%2Bc5101yoDjF96643bXCCpdrzdyrF94VTs2dy2ESfTLVHfBj0e%2FEnreYBtj8lC22%2BZWHEHiza%2BjszsKEN2oqqKDxE8eXve3cEvK%2FvM4gkIR2%2BiFX4qBa1sKu%2FZu0x%2F8uTQT8yVx%2F%2FoT7eo2igWRMDLtaPur4Szafg4%2Bzjay4%2BTXeZe4dbHos%2Frz2BMM&X-Amz-Signature=127c4c339e240533fdcd24d4de58517d1e2118990e80b08f0639b64bb777f003&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663BJHLJOP%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T222341Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDEn7Mpd%2F5DD8TywrtCi7RqRqO3kY%2FlvuZM43ekviBXgAIgGJ%2BxvMsk1%2FGlWd2TDJsEw2t3kdjfyucJyMJ75sur5Ooq%2FwMINxAAGgw2Mzc0MjMxODM4MDUiDJnUKOG18%2FVcp9JpNyrcAz6%2FDYBlSqov6dAyj7ucVlArXCxE41w14qaJiul2b%2BiZdgNlX6J85Iuo4T3e8kpnj1JmBQiAPaKtLM1Tv%2FSzFbNrlD7XPxcqsN%2FsuXFuW8YJevK4pbdz1Q588GhRY%2FAlqBs%2BSA%2FvKS2qkl2%2BJi%2Fxd2SiPBTX%2FNvRKtixL%2FfQXnZnlIYQ%2BPXT7Y0WBSwwFES53z1FKeGPuTNQTGUtHw%2BTrRIY71XdDTdSYHxDNlDeuYVrgksDfEtKVITYh6hI6b0isroqysw%2F2rJfwOxGwOkBaN%2BfxLfauGTpPffOJ6sRHVH4q0diRsREva2L4O%2BmUfBxbZBcI6DOKg0teN2x8iVwL3JttRh0u0PzU7g2JwVtGLkeDG1CfR71N4LzvckIXLvhYdwEZ3wg7T15wqsjwuwtATSdHLGGI%2FuhS5sKifPpKRBgMtkhZikmNAYi0bfiwCF8aKTbB%2BFO31Iw3t0Qizbe86aSuVegJ9wvKDKYXhKO4EspNpg8RTZdaKXXgRupskoql7bpNkXUS4Df0d66yjiXRJD6Sbo6dOrUlzXgVxiIqyN14zmq6mfoVRxTM3FIzmbY44nps3ya1rIyGj4HE%2FU1j510BIXa%2BC3L28PAxhiwqNnzUvUOC8mMVN0ebtqfMOXW870GOqUBQ%2BAXmEXM6I8iPTzVWyyJWGrGy9S3OI%2FfHmXb3HjzXuNjaWXmohzQhlLKkwoXOx%2FyM7sm0BKtXgwsQlGKOLvaoxlIjmZN6SfEVr6exRUMzWnWFk%2BahX7hbrVK8J0MvkNtVKD0GcBVD723ZwLcL2BCXJ6zRS%2Fhw%2FvyCr5LpBuF78vravrbm1AbcdPicAxAVnmQixzvyLWDnJrtkgJy%2BrzoacoUd5Nf&X-Amz-Signature=14f2973a297e61327ce5e09cf66d7a5aac28bfa6418fb5046a295994dbc08848&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46647XZRVB7%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T222344Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD811jn22mlhQTuzw5HqHiqISndGK3BTabi6yEgf%2F97ZQIhANCpEagQNiGTS0dBX%2BuaE0SV9xv%2B1M407z8uy41hd%2FEHKv8DCDcQABoMNjM3NDIzMTgzODA1IgzMBhyTxUyNOV7HBcIq3AO8ZOjfYUkS4rbJkLba2uAHLQONYA5eaeoxLzi2uVG2WhU8PtIbw%2FyapF5qvt3aBZtI%2F%2FS%2B3G1ZFL%2BP%2FiCh5Py9n1H68AQ9e7ZxX2VjeF82HDN6dfNY8iisj9l0FphBoFMPIghc93QphkLWReVthMOiR9HQzd5CdaHanKA5Ld3ENDRK5D7Cs9AbBO8EMjac6vxiHBDqpEbIprJ07gtuftf8nuFbt%2BEs3rciJrzx%2BoqA4vh4cHApLdl5kH6a6U5mN9r%2F9OtB2AY91GSbA1ZVhFj76Y5nSOa6eMOmzlNg6oBk8%2F2N3TKU8adUfdBeXOP77heGcYSPyqUpExvipi93OSmtvtOlbiQW6tnnck88UI%2FpurBO7s9cqEolumUTInty%2F5rYa5MIBCaoYP9VoDwZsiLMxoR0eDbVt4K2RbfRxaR%2BsPgwFZ0i6y5e%2B0NoyRJjV7lhyuU9qeT2VCkR7waQolQyjzqq%2BFDxlRW9I6u7ikiKRPetaS1wy3xNQ6JqnsG1ZkgkiMkHk6s%2BIsoimNo4uBqu8rtrgugd26mT%2FTow6BsKOoIgKfnzZLDQPTMFRYM4MvUwgXs2KnTIKO2ivckKRhyXcajQ048hbs%2Fz2e6L6gcUxIW1O88kTt95C80t8DDj1vO9BjqkAeadF9xDs69laHsgswRKedhixUADiDPJ4Bx4W2HAUT9CmrIRkCrEyzvZo3nlseFMzrsYWIv9rkjuufgb305Re%2B9tNm9AleWOYjZSWd0ebYpF4R6Y8Zww%2BM6jzDeoTmNlivs%2Bmr0UvTyYCg%2Bbg9NF0WAh3%2BbKzH02h3AjmHHcpFSV2V9%2FBRoTKfv41%2F4eQaQymIb5jIKcPae4q8Bvt2cttfWvfEfK&X-Amz-Signature=738b49cc72fcd602e0fbacf8deffa20324168dec61384e4c2784410dfbcf30be&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466333Y3XTF%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T222341Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCID0h2immnrxAV0XbhUYyCFHes7Ly2FacOMyD1puYiLU8AiEA1QHlgfvka7XmACvOFYVjiEjvV8ik7bBYB8SBiiPhoMMq%2FwMINxAAGgw2Mzc0MjMxODM4MDUiDJmfjEgxmmNxx5yTQCrcA9xunUNU8XG0DjNQ3A58nXhu6ngKBwT2a%2B2d9Puv7gcWqCHQ%2BUWHZeyUiiJnLw6UF8J2fVMgDXQNlyPdp2naNIesk9J4%2BORucw5sPwQ7eSnT%2BwxaTFYcvk5%2FOV9lNN6NGdgE15SpYIk8MD19Lav04sduF5NkbX%2FunOKiJkdGJ7Um8rBVE%2FEA9aRTvH5NtWTunyhJk6c1%2F59jeMXDNOWwTlunPkTJ4%2FkVqkBDE%2FKd47YxHbFgDNV%2BN3H97c%2BnkjsabMO2UU%2Fd9XsvhrzJDRvyqDz5kPPJ7rLnUB2zoY%2Fin9Lw6dPNMeRQ14A2%2Bvyai9BZlbzGLsHYHuS8fyR7wn6y%2Bt4RjTXg2FqvL7hVBNjpyquJHbIpxhQ%2FL%2Fy4hYZegMdqpKlLPPmESHjq2ER5xBlWWF%2FZRjZ4sgP2sBihusYrmp3JQyABsvQNHdKcQrF%2B02snjptSj6zSXQ7Lk5sCZYWPZ8NaZyc85MBhaKHkd9qZ%2BoPuwTzD7sK31tqaXMaCAY9gQn9AHPIeE7zUCtX%2BqtSjClwSTSP%2BO5dGf9tPDku%2FPsCFzzWztJH%2FSN67McjKAKt2tHFrrzHVvxHzspxgVtbmsRQ9%2FhB8MHA1MKZ8baa4XY2Zj6CeZD7bbVXAdK9gMKjW870GOqUBm0Td7bSQGLjOo6XNzKf%2FaXcCnHklztWhiL%2Bc5101yoDjF96643bXCCpdrzdyrF94VTs2dy2ESfTLVHfBj0e%2FEnreYBtj8lC22%2BZWHEHiza%2BjszsKEN2oqqKDxE8eXve3cEvK%2FvM4gkIR2%2BiFX4qBa1sKu%2FZu0x%2F8uTQT8yVx%2F%2FoT7eo2igWRMDLtaPur4Szafg4%2Bzjay4%2BTXeZe4dbHos%2Frz2BMM&X-Amz-Signature=c96ac351621059d9b3b217af632678ab563b0665270a388438b01d70dac2739e&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466333Y3XTF%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T222341Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCID0h2immnrxAV0XbhUYyCFHes7Ly2FacOMyD1puYiLU8AiEA1QHlgfvka7XmACvOFYVjiEjvV8ik7bBYB8SBiiPhoMMq%2FwMINxAAGgw2Mzc0MjMxODM4MDUiDJmfjEgxmmNxx5yTQCrcA9xunUNU8XG0DjNQ3A58nXhu6ngKBwT2a%2B2d9Puv7gcWqCHQ%2BUWHZeyUiiJnLw6UF8J2fVMgDXQNlyPdp2naNIesk9J4%2BORucw5sPwQ7eSnT%2BwxaTFYcvk5%2FOV9lNN6NGdgE15SpYIk8MD19Lav04sduF5NkbX%2FunOKiJkdGJ7Um8rBVE%2FEA9aRTvH5NtWTunyhJk6c1%2F59jeMXDNOWwTlunPkTJ4%2FkVqkBDE%2FKd47YxHbFgDNV%2BN3H97c%2BnkjsabMO2UU%2Fd9XsvhrzJDRvyqDz5kPPJ7rLnUB2zoY%2Fin9Lw6dPNMeRQ14A2%2Bvyai9BZlbzGLsHYHuS8fyR7wn6y%2Bt4RjTXg2FqvL7hVBNjpyquJHbIpxhQ%2FL%2Fy4hYZegMdqpKlLPPmESHjq2ER5xBlWWF%2FZRjZ4sgP2sBihusYrmp3JQyABsvQNHdKcQrF%2B02snjptSj6zSXQ7Lk5sCZYWPZ8NaZyc85MBhaKHkd9qZ%2BoPuwTzD7sK31tqaXMaCAY9gQn9AHPIeE7zUCtX%2BqtSjClwSTSP%2BO5dGf9tPDku%2FPsCFzzWztJH%2FSN67McjKAKt2tHFrrzHVvxHzspxgVtbmsRQ9%2FhB8MHA1MKZ8baa4XY2Zj6CeZD7bbVXAdK9gMKjW870GOqUBm0Td7bSQGLjOo6XNzKf%2FaXcCnHklztWhiL%2Bc5101yoDjF96643bXCCpdrzdyrF94VTs2dy2ESfTLVHfBj0e%2FEnreYBtj8lC22%2BZWHEHiza%2BjszsKEN2oqqKDxE8eXve3cEvK%2FvM4gkIR2%2BiFX4qBa1sKu%2FZu0x%2F8uTQT8yVx%2F%2FoT7eo2igWRMDLtaPur4Szafg4%2Bzjay4%2BTXeZe4dbHos%2Frz2BMM&X-Amz-Signature=f31a417c45be49c02eb1e53075f02435790ba8d11411877548715cd7d3e4d217&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466333Y3XTF%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T222341Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCID0h2immnrxAV0XbhUYyCFHes7Ly2FacOMyD1puYiLU8AiEA1QHlgfvka7XmACvOFYVjiEjvV8ik7bBYB8SBiiPhoMMq%2FwMINxAAGgw2Mzc0MjMxODM4MDUiDJmfjEgxmmNxx5yTQCrcA9xunUNU8XG0DjNQ3A58nXhu6ngKBwT2a%2B2d9Puv7gcWqCHQ%2BUWHZeyUiiJnLw6UF8J2fVMgDXQNlyPdp2naNIesk9J4%2BORucw5sPwQ7eSnT%2BwxaTFYcvk5%2FOV9lNN6NGdgE15SpYIk8MD19Lav04sduF5NkbX%2FunOKiJkdGJ7Um8rBVE%2FEA9aRTvH5NtWTunyhJk6c1%2F59jeMXDNOWwTlunPkTJ4%2FkVqkBDE%2FKd47YxHbFgDNV%2BN3H97c%2BnkjsabMO2UU%2Fd9XsvhrzJDRvyqDz5kPPJ7rLnUB2zoY%2Fin9Lw6dPNMeRQ14A2%2Bvyai9BZlbzGLsHYHuS8fyR7wn6y%2Bt4RjTXg2FqvL7hVBNjpyquJHbIpxhQ%2FL%2Fy4hYZegMdqpKlLPPmESHjq2ER5xBlWWF%2FZRjZ4sgP2sBihusYrmp3JQyABsvQNHdKcQrF%2B02snjptSj6zSXQ7Lk5sCZYWPZ8NaZyc85MBhaKHkd9qZ%2BoPuwTzD7sK31tqaXMaCAY9gQn9AHPIeE7zUCtX%2BqtSjClwSTSP%2BO5dGf9tPDku%2FPsCFzzWztJH%2FSN67McjKAKt2tHFrrzHVvxHzspxgVtbmsRQ9%2FhB8MHA1MKZ8baa4XY2Zj6CeZD7bbVXAdK9gMKjW870GOqUBm0Td7bSQGLjOo6XNzKf%2FaXcCnHklztWhiL%2Bc5101yoDjF96643bXCCpdrzdyrF94VTs2dy2ESfTLVHfBj0e%2FEnreYBtj8lC22%2BZWHEHiza%2BjszsKEN2oqqKDxE8eXve3cEvK%2FvM4gkIR2%2BiFX4qBa1sKu%2FZu0x%2F8uTQT8yVx%2F%2FoT7eo2igWRMDLtaPur4Szafg4%2Bzjay4%2BTXeZe4dbHos%2Frz2BMM&X-Amz-Signature=7704db4fbdb392a5cbb7bd3ca4c48f97745b4c3f398f62cf9eee554c1aa92f79&X-Amz-SignedHeaders=host&x-id=GetObject)


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

