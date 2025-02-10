---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466WNIT5EOP%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250210T042945Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIGkYiUFTz3tnqAoIayt\
  b9n2VVQLETolyc4Y0tybuWXQ%2BAiEApK2SxfNqqDjSyuba%2Ft0bonr1o%2FW13YOARXqfzrzSNQ\
  sqiAQItf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOX9rGf5eu5dA2t\
  xeCrcA8RCEIoJap4WmcaT9JJpvnFSq%2BYa%2B7A39sauuspxEaL%2BKQQvTWJtX3FoSOLKH5rNP7\
  Q8WyKy4%2BwQMPl%2BbzA25%2B7cAG%2FcarsY2gonPdzDCog7BEyUA%2F8aHzGswTIMJyj%2BPmu\
  %2FWNmqHQCdSkyQHERS8X1kf%2Br4l0k6ERLwxfpAZ6E0H%2BhskDBuUvHq2PEKOe18LwsYRJu0Ku\
  hWKIqTW4UHcU87mpt18vlcvmZvJcXZzmHegnGX%2FdxQNz%2BnfpbCEfy7e3sFmT6sx3uaKXk8VCD\
  Lvknb1mScPc%2F8j0PDydUdPuKWvuSfvkGcuIBOuKygzBaIR%2F%2BsRTGM9o2SqJYwzWNs4rJx67\
  VQIv7p%2B6IJSUFbA47zFnRTwwVfHjVKwH1jvPOuJhavuKFc2OjMZBv4RzZlYTc7iJhe38RqkdTMq\
  BxJi2yFvbsbBHwBQdv0Ba%2BGdjqeOVZwzDkseXhBmiuCZD%2F9hnwQhj2OBHxXULkW2ea930w5V8\
  SM4Ks5IuBrJGNDoSSz1N6UQK11hey68iWqoKYgwexnh1agF0TV4O4AQD0A6%2FajJ7FP8ljaG7YF8\
  HRpWhNUcDeWUFNM2PMT5LjAQ5TihQ3LQimx8YFZQEe2XhtKWJFyYc3kcE8jQPJnJ%2B8RMKT6pb0G\
  OqUBqGS0LPfNrpDrb4Gs4UkltRRWvANVVS57mOvnRPulyEOOJkxttwIHhYcfX5MFZxHixEMG2USja\
  R0p16t9P%2ByVpoaviUr7FUXoaqyXgKEM9HelMBBQlzBT0JqC96KYLVt3ZPUQjTjSPgDmh6GKEjdI\
  xAT7de4cL6rOR3G2%2Figpza5QWED3AU3OlhQ0UYL4kdDWZPPo5m%2F3DoDcSvUDTzcpCNdOuw1D&\
  X-Amz-Signature=f6631e4e684cd0749fa15fd89f07b3d322ef3f8f2a5c39ba450eeff3f12e4\
  e35&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4662F43UQFC%2F20250210%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250210T042824Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEY\
        CIQDRJEDsh3rdkvjN%2BDxqGAV3MA9pQQJkHr2oMHGjlYijXgIhAIkyOcQ3zpumwzeV7B9t\
        ClaTFcqdZOG9FLabX27GUdJjKogECLX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM\
        3NDIzMTgzODA1IgzfGHXmfwr0HMN2p%2B0q3AOp7B8vbLdH2JvMkH3QtbTdujN1J3DtPKG6\
        M5XgEqC5iQT7tVYckTAVx1FtgYH808cBedMPJz4NjygmHJ%2BvB6a8cn1hpOK2xjwaVYrH5\
        1sE2ekTb6yUK4y%2B5Isjd5m6rkV4tCxh0xJPR0eqTTct9YJmFadh%2FJMPwO0AS9uf5A9C\
        z%2BVCMt78Q8rtm2Ms4VwwGWmG8a%2BhNUtQws%2B1DsEBHwYTo8d%2Bc%2FeNSK20rlZbr\
        0wyZ328fpVEPgwDtNYZFswea5D78J92XwuNNjwjMRmEd31SgQtpvmLRRHOGPeGf0EStoXrp\
        MIRs6rnlXFTGqA%2FLmCwemkFU5W4eVTuhPnYmUu7wI4AOHWOv1Or6lKDvrx4Yc1S1cmLVG\
        0E9yf%2BfpIdz7vJj1HDX9UAD26j7MqzSBfDJKFAYEIziwC3ChL%2FOxXV%2BHHHstOt69O\
        rWBTRmsfSRRRHG5gyWZGaYiHos89q6VfByv%2Fbi38VcykFssdgXswVcXKRiLIcumoG3nEL\
        iF2eG8dgtUnCnj7FZd4towYhocqIxpkUjYIb8OOPaGZbAUJZuVRu0%2FfEAV90Hsm3rkWs0\
        5WygaEDHTBb12xm7EcqD5%2BAlJt29PP9m%2FJ9ZjX8KJcyvKvZBfa2%2BSsOZ2aVsszCJ%\
        2BqW9BjqkAUa3mVJj%2FRi%2FcaR6dcvtcN0yMghgqkf6tdhbcdC69PyPWtSAuV0Ezu5jiJ\
        0Q3tnYkjEqceQdHPqyzqzJfKUlPiBLf%2FO5TYfq7V9yCvGiYg7h0n6Vox6dgAw2m0oKpjH\
        l1BFeFNHsh0zWpDIEsHm2pPJtgdREM%2B1lSZ9mAOpDVajeXmf1js5wMLNJOzGIXh3lRekY\
        QTwfrABNyeelqtu3geLuca1g&X-Amz-Signature=aad978bdfed50272523cf1e2f2bf46\
        e493ff5e8d463b9c015721e47fe99e0740&X-Amz-SignedHeaders=host&x-id=GetObj\
        ect"
      expiry_time: "2025-02-10T05:28:24.537Z"
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
UPDATE_TIME: "2025-02-10T04:29:53.597Z"
EXPIRY_TIME: "2025-02-10T05:29:43.103Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z5FQI5GB%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T042944Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDU7Gt6kVLOOy4xY8tS35XF%2FDdaU8kgJZ8q7c05tjOaCAIgMKbqV6eD2%2B%2BMCFMtRqmoEQQ1ikOwDQuD%2FX0jJQrwJDQqiAQItf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKE7A1jucwbvUAEI6SrcA0HMwcu3H1J%2FzmgP2UEk%2FL%2F7pMYEA8fHNF0yPeKR%2BQmClGN5Dvq03zpcmMdnAYUTK5AV4IxhHWXwhvT3x2PA3%2FK%2BlqmHwyDCuKg4wKwZpi6UuSD5YSTzGNDGVR5qaq5keDnd33TsRtNvYbQ2iSCqVPbM7%2BjGX6%2BboeN%2BEEZUUJvp6x4x%2Ft6nbQj%2BuSfuTfRo2KDCNiIa16jTfrWnG7Rkt4Cxruttj0Vgig%2FyeZ6Omhb1RhbT9F1lr%2F68Tpjd3kYDWnnQDyVbH0%2F8R4Y8oiLdgONfx%2B3yDFzPEplLKyzT0z0wzmypOeqAEQs%2B5LiVMpan8nPTxpdcLajWfFWvw7JQa%2Fp5TALofnOH2WsZDXQWWLpx2E890F4lzD1UWWx67TFlRpI0f8sSV4JDcVoYb55oqLFMTWgWEmS8wrbLR7Noqj4hENJRWyDOhoN2uG44aOq4iUL6WSP2l9ThzpwWYvefbd9uHmtcpZME0LvX1uU0is%2F12BTxASnlP6uowMCCESRhhVVFlQ52gmo5EHOw3%2BufT5jdJX5QltgjoXJHrcyXwqk%2FApUmtgqoxgIa%2BD294jZy6r1PGktIfgJrJRmV4ELNqrQAhkdLxuXtbXXH9aLAdhVMfrIy5%2F6IS4BMLbt1MJL6pb0GOqUBInuZotx3LKDl%2FYVJKMZeSsDRPfFUv7Pa8u256Gn%2BSWlgV7nqSjoDTgtugM5MBiNdW3DgdFbFBT05oDm7LLbGPx9maWIaYRMMLvboZVZH3I%2FQmELdLBiUWd7qdwzrSwVFH28Pd5e8fitTXU%2FZwcJECrOPzOqvxq7BUNHSGLEpsfmHhrGLBZKxkWhX%2B%2BgpHTtpjauP35TOOT3V5XnTmnhllzLtyR8b&X-Amz-Signature=a9ec29d150fbaf0835e58faf55417f42801087336423d9bf929248d45a418bf3&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z5FQI5GB%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T042944Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDU7Gt6kVLOOy4xY8tS35XF%2FDdaU8kgJZ8q7c05tjOaCAIgMKbqV6eD2%2B%2BMCFMtRqmoEQQ1ikOwDQuD%2FX0jJQrwJDQqiAQItf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKE7A1jucwbvUAEI6SrcA0HMwcu3H1J%2FzmgP2UEk%2FL%2F7pMYEA8fHNF0yPeKR%2BQmClGN5Dvq03zpcmMdnAYUTK5AV4IxhHWXwhvT3x2PA3%2FK%2BlqmHwyDCuKg4wKwZpi6UuSD5YSTzGNDGVR5qaq5keDnd33TsRtNvYbQ2iSCqVPbM7%2BjGX6%2BboeN%2BEEZUUJvp6x4x%2Ft6nbQj%2BuSfuTfRo2KDCNiIa16jTfrWnG7Rkt4Cxruttj0Vgig%2FyeZ6Omhb1RhbT9F1lr%2F68Tpjd3kYDWnnQDyVbH0%2F8R4Y8oiLdgONfx%2B3yDFzPEplLKyzT0z0wzmypOeqAEQs%2B5LiVMpan8nPTxpdcLajWfFWvw7JQa%2Fp5TALofnOH2WsZDXQWWLpx2E890F4lzD1UWWx67TFlRpI0f8sSV4JDcVoYb55oqLFMTWgWEmS8wrbLR7Noqj4hENJRWyDOhoN2uG44aOq4iUL6WSP2l9ThzpwWYvefbd9uHmtcpZME0LvX1uU0is%2F12BTxASnlP6uowMCCESRhhVVFlQ52gmo5EHOw3%2BufT5jdJX5QltgjoXJHrcyXwqk%2FApUmtgqoxgIa%2BD294jZy6r1PGktIfgJrJRmV4ELNqrQAhkdLxuXtbXXH9aLAdhVMfrIy5%2F6IS4BMLbt1MJL6pb0GOqUBInuZotx3LKDl%2FYVJKMZeSsDRPfFUv7Pa8u256Gn%2BSWlgV7nqSjoDTgtugM5MBiNdW3DgdFbFBT05oDm7LLbGPx9maWIaYRMMLvboZVZH3I%2FQmELdLBiUWd7qdwzrSwVFH28Pd5e8fitTXU%2FZwcJECrOPzOqvxq7BUNHSGLEpsfmHhrGLBZKxkWhX%2B%2BgpHTtpjauP35TOOT3V5XnTmnhllzLtyR8b&X-Amz-Signature=842f6dac6abb896554b2c75f50968c6f486bd3bfacb5d5696f5a4360d4710a44&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z5FQI5GB%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T042944Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDU7Gt6kVLOOy4xY8tS35XF%2FDdaU8kgJZ8q7c05tjOaCAIgMKbqV6eD2%2B%2BMCFMtRqmoEQQ1ikOwDQuD%2FX0jJQrwJDQqiAQItf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKE7A1jucwbvUAEI6SrcA0HMwcu3H1J%2FzmgP2UEk%2FL%2F7pMYEA8fHNF0yPeKR%2BQmClGN5Dvq03zpcmMdnAYUTK5AV4IxhHWXwhvT3x2PA3%2FK%2BlqmHwyDCuKg4wKwZpi6UuSD5YSTzGNDGVR5qaq5keDnd33TsRtNvYbQ2iSCqVPbM7%2BjGX6%2BboeN%2BEEZUUJvp6x4x%2Ft6nbQj%2BuSfuTfRo2KDCNiIa16jTfrWnG7Rkt4Cxruttj0Vgig%2FyeZ6Omhb1RhbT9F1lr%2F68Tpjd3kYDWnnQDyVbH0%2F8R4Y8oiLdgONfx%2B3yDFzPEplLKyzT0z0wzmypOeqAEQs%2B5LiVMpan8nPTxpdcLajWfFWvw7JQa%2Fp5TALofnOH2WsZDXQWWLpx2E890F4lzD1UWWx67TFlRpI0f8sSV4JDcVoYb55oqLFMTWgWEmS8wrbLR7Noqj4hENJRWyDOhoN2uG44aOq4iUL6WSP2l9ThzpwWYvefbd9uHmtcpZME0LvX1uU0is%2F12BTxASnlP6uowMCCESRhhVVFlQ52gmo5EHOw3%2BufT5jdJX5QltgjoXJHrcyXwqk%2FApUmtgqoxgIa%2BD294jZy6r1PGktIfgJrJRmV4ELNqrQAhkdLxuXtbXXH9aLAdhVMfrIy5%2F6IS4BMLbt1MJL6pb0GOqUBInuZotx3LKDl%2FYVJKMZeSsDRPfFUv7Pa8u256Gn%2BSWlgV7nqSjoDTgtugM5MBiNdW3DgdFbFBT05oDm7LLbGPx9maWIaYRMMLvboZVZH3I%2FQmELdLBiUWd7qdwzrSwVFH28Pd5e8fitTXU%2FZwcJECrOPzOqvxq7BUNHSGLEpsfmHhrGLBZKxkWhX%2B%2BgpHTtpjauP35TOOT3V5XnTmnhllzLtyR8b&X-Amz-Signature=f688bfeb12f78884d42d3d731994f50f75a33782ba5680e7f92f61199375cfe4&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z5FQI5GB%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T042944Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDU7Gt6kVLOOy4xY8tS35XF%2FDdaU8kgJZ8q7c05tjOaCAIgMKbqV6eD2%2B%2BMCFMtRqmoEQQ1ikOwDQuD%2FX0jJQrwJDQqiAQItf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKE7A1jucwbvUAEI6SrcA0HMwcu3H1J%2FzmgP2UEk%2FL%2F7pMYEA8fHNF0yPeKR%2BQmClGN5Dvq03zpcmMdnAYUTK5AV4IxhHWXwhvT3x2PA3%2FK%2BlqmHwyDCuKg4wKwZpi6UuSD5YSTzGNDGVR5qaq5keDnd33TsRtNvYbQ2iSCqVPbM7%2BjGX6%2BboeN%2BEEZUUJvp6x4x%2Ft6nbQj%2BuSfuTfRo2KDCNiIa16jTfrWnG7Rkt4Cxruttj0Vgig%2FyeZ6Omhb1RhbT9F1lr%2F68Tpjd3kYDWnnQDyVbH0%2F8R4Y8oiLdgONfx%2B3yDFzPEplLKyzT0z0wzmypOeqAEQs%2B5LiVMpan8nPTxpdcLajWfFWvw7JQa%2Fp5TALofnOH2WsZDXQWWLpx2E890F4lzD1UWWx67TFlRpI0f8sSV4JDcVoYb55oqLFMTWgWEmS8wrbLR7Noqj4hENJRWyDOhoN2uG44aOq4iUL6WSP2l9ThzpwWYvefbd9uHmtcpZME0LvX1uU0is%2F12BTxASnlP6uowMCCESRhhVVFlQ52gmo5EHOw3%2BufT5jdJX5QltgjoXJHrcyXwqk%2FApUmtgqoxgIa%2BD294jZy6r1PGktIfgJrJRmV4ELNqrQAhkdLxuXtbXXH9aLAdhVMfrIy5%2F6IS4BMLbt1MJL6pb0GOqUBInuZotx3LKDl%2FYVJKMZeSsDRPfFUv7Pa8u256Gn%2BSWlgV7nqSjoDTgtugM5MBiNdW3DgdFbFBT05oDm7LLbGPx9maWIaYRMMLvboZVZH3I%2FQmELdLBiUWd7qdwzrSwVFH28Pd5e8fitTXU%2FZwcJECrOPzOqvxq7BUNHSGLEpsfmHhrGLBZKxkWhX%2B%2BgpHTtpjauP35TOOT3V5XnTmnhllzLtyR8b&X-Amz-Signature=b42ba0baa592851c7f44baa91fd6cd359f004a54d13bdce2c0e4ff3e899c7134&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z5FQI5GB%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T042944Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDU7Gt6kVLOOy4xY8tS35XF%2FDdaU8kgJZ8q7c05tjOaCAIgMKbqV6eD2%2B%2BMCFMtRqmoEQQ1ikOwDQuD%2FX0jJQrwJDQqiAQItf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKE7A1jucwbvUAEI6SrcA0HMwcu3H1J%2FzmgP2UEk%2FL%2F7pMYEA8fHNF0yPeKR%2BQmClGN5Dvq03zpcmMdnAYUTK5AV4IxhHWXwhvT3x2PA3%2FK%2BlqmHwyDCuKg4wKwZpi6UuSD5YSTzGNDGVR5qaq5keDnd33TsRtNvYbQ2iSCqVPbM7%2BjGX6%2BboeN%2BEEZUUJvp6x4x%2Ft6nbQj%2BuSfuTfRo2KDCNiIa16jTfrWnG7Rkt4Cxruttj0Vgig%2FyeZ6Omhb1RhbT9F1lr%2F68Tpjd3kYDWnnQDyVbH0%2F8R4Y8oiLdgONfx%2B3yDFzPEplLKyzT0z0wzmypOeqAEQs%2B5LiVMpan8nPTxpdcLajWfFWvw7JQa%2Fp5TALofnOH2WsZDXQWWLpx2E890F4lzD1UWWx67TFlRpI0f8sSV4JDcVoYb55oqLFMTWgWEmS8wrbLR7Noqj4hENJRWyDOhoN2uG44aOq4iUL6WSP2l9ThzpwWYvefbd9uHmtcpZME0LvX1uU0is%2F12BTxASnlP6uowMCCESRhhVVFlQ52gmo5EHOw3%2BufT5jdJX5QltgjoXJHrcyXwqk%2FApUmtgqoxgIa%2BD294jZy6r1PGktIfgJrJRmV4ELNqrQAhkdLxuXtbXXH9aLAdhVMfrIy5%2F6IS4BMLbt1MJL6pb0GOqUBInuZotx3LKDl%2FYVJKMZeSsDRPfFUv7Pa8u256Gn%2BSWlgV7nqSjoDTgtugM5MBiNdW3DgdFbFBT05oDm7LLbGPx9maWIaYRMMLvboZVZH3I%2FQmELdLBiUWd7qdwzrSwVFH28Pd5e8fitTXU%2FZwcJECrOPzOqvxq7BUNHSGLEpsfmHhrGLBZKxkWhX%2B%2BgpHTtpjauP35TOOT3V5XnTmnhllzLtyR8b&X-Amz-Signature=7b8a3a81ea052c9e7befb8a043cee90f6e39e90c7effce6df184df7e47e4ef11&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QF5PPNTT%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T042944Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEtwvXVtPCZebMThQ5TwrC8MFk%2FhG94Nb24%2BhOMsbS1FAiBuNgeQq2gpdxFGX4%2BhXsLwOIX2KJpvt9w7p157%2B4YWPSqIBAi1%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM3yuIMH44gzG8R%2FRIKtwD3GWep%2FBI0PaK5zKE%2Bz1980HC82j3O478FHk1xbeUMt9%2Fi%2BOPN%2FGKXh6APnpeJ9MqU6CNRoZumm%2B3z0Hqm%2FLmz7bmWonSXao4a938AzkSlVHHr4AUcP0q9M4mXHvxi2JVqPyu5oqo5S19g7sYvqQ8rt9GkaMa2S5h4px8vfwEz8wxBp%2FZzlRH0SCv89Lk7gctnu8pVa95C%2BDABURBKo%2FWRNEhQP8RG4Yf3rWsixWFFxiL%2Ba9mAmj8%2BC7cfBCOJsaH5H51tQmTrPcHl0S%2F6uq42kV5ATpMCNDlax60%2BfUx9iQ833K51asoUsnsj9I7h%2BnVktKpRMD%2Bg6iHd%2FUSYyUWkkY74Cezn5pU0Hitz1ky62UXHEKZRKsIsK%2BD5F7Z%2FncJqwjACnEtcIpqpQqomzbVGjWDdIPqjocqQr70Mmu2SX4KZ6eMFBT4%2F2ggI3%2FLC2P87djeEt5Clfb3jLe9AEf%2BfIT%2FPh55E87uBVP1ZtLKYM7qFpGyteMYV9Mk%2BnQGSFJYaOB7c78uSp%2FvkMrSrrcOoBOJTEPzyL8YTHD1pGnHiPeOdgDVkemGwWpKtKRQPCPcBdT6SD0pbAPrnstKLyEe3AXiCwgnI8CPW%2FNDdK9ph1kIsZxUdOSSvdnL%2B7cws%2FqlvQY6pgGTvGV2imL7Hxy4GwjEidhz4Ik09vX4v99mE9jhvKNyJ1cA5%2Bpv0YadI0j%2BCRQ7E2MJsbYbdynbryAe54hzzAAfWCfde%2FNZlunO3rK1XZafR63DxwptsvXgXOhUHiYrjxa1HoHC1R9WUyrcHh1CYpknOvrxsAAeAlZZ%2F%2FO8iUw6UYQRjcd3C%2Bchxj8kvNWSkUUHXyQDmNWtr9CnUBuxDNyqsy91C0De&X-Amz-Signature=240472fffd1c8456556dc4688c1260fa7e57d40db7634aa5b8a1ea4db54d08ba&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QXLF56IZ%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T042945Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIGkDEyeVdRuHB804bzPoD1X8sax6zCS2Axt%2FabAFTgukAiAs6DejG39DN8bWeui4QJRUoQFwKPh1MwsdFYYRwekfXiqIBAi1%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM%2FEVz0P9x5b87hlgAKtwDF3NmiYgqlaOht6nEG8pJR7AyQ%2F0LyWRR9w0HhsM6lX%2B3NzdToqn81ztxxqYPHYGVNINTQ2ycE5wdhLtnI1OadDgNI0QKVp8t9MtMopyKrGR02lofN%2FEAxj08ZWG5OemtH6ipiMZd62H5vpj4K6JFIfCtuCUiI8FiE7U7G8W1ob7dvDoaccmgRM4fdoCEyM9Ky4zbFlDJQGEP%2BG6JlDoeBN0ajt928DFVkj%2F%2B10eN6QNjpTMr7VrTsFcwXozwS30oILuQ0EEyn3KvxWnhjqCIbRGsBnDz2ZS6ZnW2TJ8kUokOTL7nqwa3h75IpUO7SwtvcwnUwOLcmcVaTERltY2muRJ9OG7kz3HcMGabDmkniqnjARoWxVRZi69%2FBsfJT8D7Qw0moBUYB24WNtbmnk0z6i5ojoE7%2FfhNa5k%2F4SgU%2F1vxwTUb7Co0Ja4HsSzJQeV5pw5zGkCo9OHGmEogzT0pyP3G7eIeh5rYeeVu3LPwlPoEdBAeXO0MhLlccKjQRmMibWXfdU0jtrFaK5i1Qp5bDqfSJd%2Bw83k4uhZw5Q%2FfHs%2BTL4u3wqSRZ87MEUtiwlzb8GaUMgc7TVM%2F0%2BDOp990Ktz1VbI8HUi2B91f5xXK27MYg0Rv2plCU1Cmc60w1%2FmlvQY6pgGaA5sgJ1B8yL5C3VLy4S8vYaHv1QaaXw%2Bqd8x39QLeUdu%2BTFIm8A%2B7AkdVhRUJm5pkpIil13tz4E43WovHXjCBQDDX6XE1lsZ4JzUo0Udr3x%2BATM1wDoXP7TPflpF6AKooc6Zjoy4Hp71R0DhZNTCws2RTtCa9rcbY1osV2FetiY1nEtd4WmNejFGTEZ00SDyYsuQqrD%2B1tDskwjjwdWF01694qf4f&X-Amz-Signature=e2e384473d61bf218a8dbe85a858c3d50f054545978c50f1b97916b2a32c688a&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z5FQI5GB%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T042944Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDU7Gt6kVLOOy4xY8tS35XF%2FDdaU8kgJZ8q7c05tjOaCAIgMKbqV6eD2%2B%2BMCFMtRqmoEQQ1ikOwDQuD%2FX0jJQrwJDQqiAQItf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKE7A1jucwbvUAEI6SrcA0HMwcu3H1J%2FzmgP2UEk%2FL%2F7pMYEA8fHNF0yPeKR%2BQmClGN5Dvq03zpcmMdnAYUTK5AV4IxhHWXwhvT3x2PA3%2FK%2BlqmHwyDCuKg4wKwZpi6UuSD5YSTzGNDGVR5qaq5keDnd33TsRtNvYbQ2iSCqVPbM7%2BjGX6%2BboeN%2BEEZUUJvp6x4x%2Ft6nbQj%2BuSfuTfRo2KDCNiIa16jTfrWnG7Rkt4Cxruttj0Vgig%2FyeZ6Omhb1RhbT9F1lr%2F68Tpjd3kYDWnnQDyVbH0%2F8R4Y8oiLdgONfx%2B3yDFzPEplLKyzT0z0wzmypOeqAEQs%2B5LiVMpan8nPTxpdcLajWfFWvw7JQa%2Fp5TALofnOH2WsZDXQWWLpx2E890F4lzD1UWWx67TFlRpI0f8sSV4JDcVoYb55oqLFMTWgWEmS8wrbLR7Noqj4hENJRWyDOhoN2uG44aOq4iUL6WSP2l9ThzpwWYvefbd9uHmtcpZME0LvX1uU0is%2F12BTxASnlP6uowMCCESRhhVVFlQ52gmo5EHOw3%2BufT5jdJX5QltgjoXJHrcyXwqk%2FApUmtgqoxgIa%2BD294jZy6r1PGktIfgJrJRmV4ELNqrQAhkdLxuXtbXXH9aLAdhVMfrIy5%2F6IS4BMLbt1MJL6pb0GOqUBInuZotx3LKDl%2FYVJKMZeSsDRPfFUv7Pa8u256Gn%2BSWlgV7nqSjoDTgtugM5MBiNdW3DgdFbFBT05oDm7LLbGPx9maWIaYRMMLvboZVZH3I%2FQmELdLBiUWd7qdwzrSwVFH28Pd5e8fitTXU%2FZwcJECrOPzOqvxq7BUNHSGLEpsfmHhrGLBZKxkWhX%2B%2BgpHTtpjauP35TOOT3V5XnTmnhllzLtyR8b&X-Amz-Signature=149365b8119a74166910e3bce18e096bf1e7613db8659080d75190dcd70bf965&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z5FQI5GB%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T042944Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDU7Gt6kVLOOy4xY8tS35XF%2FDdaU8kgJZ8q7c05tjOaCAIgMKbqV6eD2%2B%2BMCFMtRqmoEQQ1ikOwDQuD%2FX0jJQrwJDQqiAQItf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKE7A1jucwbvUAEI6SrcA0HMwcu3H1J%2FzmgP2UEk%2FL%2F7pMYEA8fHNF0yPeKR%2BQmClGN5Dvq03zpcmMdnAYUTK5AV4IxhHWXwhvT3x2PA3%2FK%2BlqmHwyDCuKg4wKwZpi6UuSD5YSTzGNDGVR5qaq5keDnd33TsRtNvYbQ2iSCqVPbM7%2BjGX6%2BboeN%2BEEZUUJvp6x4x%2Ft6nbQj%2BuSfuTfRo2KDCNiIa16jTfrWnG7Rkt4Cxruttj0Vgig%2FyeZ6Omhb1RhbT9F1lr%2F68Tpjd3kYDWnnQDyVbH0%2F8R4Y8oiLdgONfx%2B3yDFzPEplLKyzT0z0wzmypOeqAEQs%2B5LiVMpan8nPTxpdcLajWfFWvw7JQa%2Fp5TALofnOH2WsZDXQWWLpx2E890F4lzD1UWWx67TFlRpI0f8sSV4JDcVoYb55oqLFMTWgWEmS8wrbLR7Noqj4hENJRWyDOhoN2uG44aOq4iUL6WSP2l9ThzpwWYvefbd9uHmtcpZME0LvX1uU0is%2F12BTxASnlP6uowMCCESRhhVVFlQ52gmo5EHOw3%2BufT5jdJX5QltgjoXJHrcyXwqk%2FApUmtgqoxgIa%2BD294jZy6r1PGktIfgJrJRmV4ELNqrQAhkdLxuXtbXXH9aLAdhVMfrIy5%2F6IS4BMLbt1MJL6pb0GOqUBInuZotx3LKDl%2FYVJKMZeSsDRPfFUv7Pa8u256Gn%2BSWlgV7nqSjoDTgtugM5MBiNdW3DgdFbFBT05oDm7LLbGPx9maWIaYRMMLvboZVZH3I%2FQmELdLBiUWd7qdwzrSwVFH28Pd5e8fitTXU%2FZwcJECrOPzOqvxq7BUNHSGLEpsfmHhrGLBZKxkWhX%2B%2BgpHTtpjauP35TOOT3V5XnTmnhllzLtyR8b&X-Amz-Signature=354563fab37eceec360b866393fea53c76fe9470ba778a413cd1bd12c45012c8&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z5FQI5GB%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T042944Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDU7Gt6kVLOOy4xY8tS35XF%2FDdaU8kgJZ8q7c05tjOaCAIgMKbqV6eD2%2B%2BMCFMtRqmoEQQ1ikOwDQuD%2FX0jJQrwJDQqiAQItf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKE7A1jucwbvUAEI6SrcA0HMwcu3H1J%2FzmgP2UEk%2FL%2F7pMYEA8fHNF0yPeKR%2BQmClGN5Dvq03zpcmMdnAYUTK5AV4IxhHWXwhvT3x2PA3%2FK%2BlqmHwyDCuKg4wKwZpi6UuSD5YSTzGNDGVR5qaq5keDnd33TsRtNvYbQ2iSCqVPbM7%2BjGX6%2BboeN%2BEEZUUJvp6x4x%2Ft6nbQj%2BuSfuTfRo2KDCNiIa16jTfrWnG7Rkt4Cxruttj0Vgig%2FyeZ6Omhb1RhbT9F1lr%2F68Tpjd3kYDWnnQDyVbH0%2F8R4Y8oiLdgONfx%2B3yDFzPEplLKyzT0z0wzmypOeqAEQs%2B5LiVMpan8nPTxpdcLajWfFWvw7JQa%2Fp5TALofnOH2WsZDXQWWLpx2E890F4lzD1UWWx67TFlRpI0f8sSV4JDcVoYb55oqLFMTWgWEmS8wrbLR7Noqj4hENJRWyDOhoN2uG44aOq4iUL6WSP2l9ThzpwWYvefbd9uHmtcpZME0LvX1uU0is%2F12BTxASnlP6uowMCCESRhhVVFlQ52gmo5EHOw3%2BufT5jdJX5QltgjoXJHrcyXwqk%2FApUmtgqoxgIa%2BD294jZy6r1PGktIfgJrJRmV4ELNqrQAhkdLxuXtbXXH9aLAdhVMfrIy5%2F6IS4BMLbt1MJL6pb0GOqUBInuZotx3LKDl%2FYVJKMZeSsDRPfFUv7Pa8u256Gn%2BSWlgV7nqSjoDTgtugM5MBiNdW3DgdFbFBT05oDm7LLbGPx9maWIaYRMMLvboZVZH3I%2FQmELdLBiUWd7qdwzrSwVFH28Pd5e8fitTXU%2FZwcJECrOPzOqvxq7BUNHSGLEpsfmHhrGLBZKxkWhX%2B%2BgpHTtpjauP35TOOT3V5XnTmnhllzLtyR8b&X-Amz-Signature=c0a1dddf5f6757a829bb0778f78926a20074779a96a31486b12a8ccda38c2ca9&X-Amz-SignedHeaders=host&x-id=GetObject)


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

