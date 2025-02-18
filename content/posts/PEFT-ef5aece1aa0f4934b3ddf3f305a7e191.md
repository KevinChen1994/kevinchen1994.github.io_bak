---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4665BDTFD6J%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250218T172200Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEGkaCXVzLXdlc3QtMiJIMEYCIQDkLXYkfMgMFqxUZYtzBspP7IrAvXShaBNni6N6hDwsSQIhAMy\
  CV30Za5yFty0RhRN1KgmyrpICcbiSNvvhbm6flzN5KogECJL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2\
  FwEQABoMNjM3NDIzMTgzODA1IgypwkeKSusvbUd7Lcgq3APHWOpzUhH0QCu0YYO84ypTyvbg9xgKy\
  DOrsQEiL5mkF5pK%2BHMFSd8Ur%2B3Us%2BcS%2FSO0rc1lZ3Be6fid7RCHuAsFuWzMJ6WVRvCq7%\
  2FrrjLuCx5xmB%2FQDezcTxzwRXX0zNFFacIqvLPgYIMh38juSThaJFzT2D2ekB6KW8ZMiCwiReaN\
  4iw9xZbWpltDhMaFEJpVbnBP6q6N96y7HqeT8QveACMVFMtG0zTVMDq7saopSz%2FCu%2F49IDPlh\
  oP5GeOLVXHo%2BT4QKZ1kmAyXePT3xOItUDqq3T4oFh764XtekInOOOKdSEdoEWBEjRQmnglfMjQC\
  hrSdeoMomZKDRb3CDvN33kWWb2MHK1GiXosrlc9lBR4uvSFSR1NGLWF37yugQ8qlBawzIYNRZ0HLV\
  3LHOOzK4%2ByEl9UxVEvMsnFeO0MXL5iGSDkEVCiTDcMvSZqTdiRvXXGOlcNnJQ6Cd0HWuDEoH5nV\
  oaOUO09WkzD%2FiGfI6pY%2B53sfdllBs9ymxHjAOXXyoVtCvnrYdLa4tGnGyTJvVI7jD1ss%2F3b\
  gPabSfV2RTS141aUNfR2o3qlCFfKECs3G6LMnBZa1KLLWB%2BZIoXV6vJpcdQk699UtYnCOmcERdj\
  euuWN08KF9V9UxU0TDM%2FdK9BjqkAcrhUU%2BhREwvDT01N%2FbkH%2B1XHBYbbxS1czI%2F9ST%\
  2FLW1CiJmLoELziYDoQtn6TY9o9lCMjaRfdx%2B9nuZ%2BlzM73QUWk2NDiwv4VRJ%2FFGfyNCsGo\
  D3QilJwwRADToiHdqtZVcZ5Q6w%2BqvMZYNvF7liV2E803o%2BhaYdiKl8DNuBJwyMW1GIWPbwsuA\
  MsfCl0P1j%2FVhGNk1Z%2BhbmOXrd%2FaY%2BYLpyJhxYC&X-Amz-Signature=851b0bbed6f775\
  7a5d58ee910fd22fc19a9d00c663de7f2bc87d058fa8a283b9&X-Amz-SignedHeaders=host&x\
  -id=GetObject"
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
        redential=ASIAZI2LB466UQPKX6BE%2F20250218%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250218T172035Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEGkaCXVzLXdlc3QtMiJGMEQCICNZGDwnG%2F9dNjbE6OXTzvykRs%2B\
        zNmNojRCwvbrQjrDBAiAiiEMrs5F2APSGCNYCagU04d7P%2BE4qKdxyvszwOvtkqSqIBAiS\
        %2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMJiAH3KjV%2FognE\
        QILKtwDvZlnBhgSfcEqEk%2B2pS5IFwPH7ose7DDJLCXjuLUsZaojFjQj%2BqnaYyMrT2UT\
        AGbe%2FjaZPmt5afqd6hI%2BL2DyeSOstl21JbQxSBq9Xxb8zBbtx3xy%2Bx%2FS2d9PvnV\
        d%2Fu8u3UGz%2Fy34BjQwTyzz4uhPLP8Qdh1JKlacY8sJ8G9ns6Mc4wIOGOXbvkRQKJ0P8E\
        A%2B931o%2B5uXYLgdHAluoEdLgVaKjBAyRtZO%2BOezeFPCktSFK%2FpX6%2BP2VeMOe3W\
        G6d8OOKVWXXtV3lms3ql%2BuM0u1GOEmi7AqacbzKdz4vTy7dVsxpi8OS0GIR4yprPK%2Bc\
        e7RxCgHH7OFgLMdf7aaXyq8NAR66hbZt4Ut9bvVh3bteX6dyFw0p58bQpyt88FPkUhrjgsb\
        xxaQUTQjI0pRnjXCM8NFsnWmRiR0sfGpEsTpEwoDNUeV%2BWs7G0FOy1tUWk3WvTCfqoXBA\
        p5cjxdCkY5c3xFc0rjR3Szu%2B4DLeJpiZkW9YskTNXF18AQgtQapm8kQ25%2F6R0kzB0Ar\
        CldCofJfoOYaqYyAzj9uRWMU3F6IPQbBzKcXEsoRC5GVp7TloCCYwwAO6Tf%2BS9K51%2Bt\
        Wb3YumrtT%2BQRUNUl7NiMTvLnS20G6PcdQs%2F4yHoJHfIw2v3SvQY6pgFX6%2BkRDn%2F\
        Rr%2FwAwkfkQYx31FbZlzD%2F5k76bzKUsl1OWibL8KRTJzoVt81r1LFUgWZDotz%2FlDJg\
        JCUUeZlrdvRZ2CM24AyOrTeFLm%2B2NPB%2Bl9luUkyO0kAAPncxj0qKkC1Txaqyngh2CMi\
        nI8QWNLwvD1Ghnnf6ztoTdtgRHlDH1LzEus%2BlqHsdOGNmOcdY6LV3v9SFYfn7SpFgoE%2\
        BnRhlNBiXL11%2Br&X-Amz-Signature=64f50596f1ed2e8c0c1da5d3a002b200ed20c6\
        5617ad4cdf75256b9e757ee524&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-18T18:20:35.749Z"
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
UPDATE_TIME: "2025-02-18T17:22:10.424Z"
EXPIRY_TIME: "2025-02-18T18:21:58.183Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667HZ367LM%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T172158Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGkaCXVzLXdlc3QtMiJHMEUCIGSiyJY9plOwxg52TT%2FbhyU538q065xwOtb799cE%2FVTiAiEA7v3fx8K4G5HohRmfeZy9%2FHbAuO1L5bPM4x1aV%2F997wcqiAQIkv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHszAugqLPyMRru7zyrcA8JhSA9Mc7ur1Drs6YymM36tpNPqeHkK5YJMZsLavCJT%2Bh4kTrZGcCAb%2FzfxAoQlGoqWW%2BZWuRQYiKJ0yrAeORbLREKBXapUq1beM633B0ZIlE5QSyAtWl2%2BS8fADQ9fIhkJ0fAOr%2FH6jIBKLJwGtqAehOqSuehIdaDVSkrTmzrlPTmYOh1nMd%2Fc5Kc%2Bg8lobtQ%2FJPkK%2FBTUT0WS15w6WN2pcRNM3oHIFPX4iMrUCTBpnVdvtC2%2FZE6SgIAWnbqCkPd5z9uRsi85EoMdtvbrbgeqpvxhQGM9bZMdNzTXdvUr1x4pW25tthO4BZnFa4RoWmVhcE04gp2zKFxIL5Nb%2B8zTOaK%2Bz1hiG8WvQHQ9CCiBD4SPhf%2BYHAa8GvVVos6Wd8T8PR0KV2cgWp7pZmYU%2Fa%2BUci2fWyryAzhtRPE1%2FtiIxu2xE%2BRCipFOVEoHIM0IZqdo0oG3vGSXHcxOUKtrEsgZQD45m7zt45mRbK%2Fzi%2FcR%2B6FWPRGXEaM8%2FokTQHw3lUZVSHIbe5C1ExzR5%2FBkfwKEZw3NAHeAxbfMq4JsAmoAf3MX7b7951wemV3nop170NsKsWig%2FlvjkdHaKM4NDp1eRX2gjijxqSCvte1SemMcft3SQxJqlCakq8ZBMM390r0GOqUBk1wSWVDQF5ktIyIOS4qTGe8fbG30GGDC9f90%2BRnf%2FhjZhPEI1jy98X6P0bPQ8LUkZVRKJMLNB8uthKm98sG6eecFt4LaLGYetAeGQ9MPCYBvW5LgjHZVScrwK7A16mUkwsPlfxLnM8op7obu%2FlPB1fY6U%2FHmPxkRjHgzaLpxqs1RCaEv5GZDAeBmlzT7mWjyArrFAEh6dcYUj2gj3VsGD7OvGM8D&X-Amz-Signature=0678edb5f9681e94733645e9f6c0e706ff4896c5c429650b481e689bfee54f14&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667HZ367LM%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T172158Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGkaCXVzLXdlc3QtMiJHMEUCIGSiyJY9plOwxg52TT%2FbhyU538q065xwOtb799cE%2FVTiAiEA7v3fx8K4G5HohRmfeZy9%2FHbAuO1L5bPM4x1aV%2F997wcqiAQIkv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHszAugqLPyMRru7zyrcA8JhSA9Mc7ur1Drs6YymM36tpNPqeHkK5YJMZsLavCJT%2Bh4kTrZGcCAb%2FzfxAoQlGoqWW%2BZWuRQYiKJ0yrAeORbLREKBXapUq1beM633B0ZIlE5QSyAtWl2%2BS8fADQ9fIhkJ0fAOr%2FH6jIBKLJwGtqAehOqSuehIdaDVSkrTmzrlPTmYOh1nMd%2Fc5Kc%2Bg8lobtQ%2FJPkK%2FBTUT0WS15w6WN2pcRNM3oHIFPX4iMrUCTBpnVdvtC2%2FZE6SgIAWnbqCkPd5z9uRsi85EoMdtvbrbgeqpvxhQGM9bZMdNzTXdvUr1x4pW25tthO4BZnFa4RoWmVhcE04gp2zKFxIL5Nb%2B8zTOaK%2Bz1hiG8WvQHQ9CCiBD4SPhf%2BYHAa8GvVVos6Wd8T8PR0KV2cgWp7pZmYU%2Fa%2BUci2fWyryAzhtRPE1%2FtiIxu2xE%2BRCipFOVEoHIM0IZqdo0oG3vGSXHcxOUKtrEsgZQD45m7zt45mRbK%2Fzi%2FcR%2B6FWPRGXEaM8%2FokTQHw3lUZVSHIbe5C1ExzR5%2FBkfwKEZw3NAHeAxbfMq4JsAmoAf3MX7b7951wemV3nop170NsKsWig%2FlvjkdHaKM4NDp1eRX2gjijxqSCvte1SemMcft3SQxJqlCakq8ZBMM390r0GOqUBk1wSWVDQF5ktIyIOS4qTGe8fbG30GGDC9f90%2BRnf%2FhjZhPEI1jy98X6P0bPQ8LUkZVRKJMLNB8uthKm98sG6eecFt4LaLGYetAeGQ9MPCYBvW5LgjHZVScrwK7A16mUkwsPlfxLnM8op7obu%2FlPB1fY6U%2FHmPxkRjHgzaLpxqs1RCaEv5GZDAeBmlzT7mWjyArrFAEh6dcYUj2gj3VsGD7OvGM8D&X-Amz-Signature=82ce65fa866db4865bc4ff0b5de02cfc4050e432f2c4975a73a373b9a265d239&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667HZ367LM%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T172158Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGkaCXVzLXdlc3QtMiJHMEUCIGSiyJY9plOwxg52TT%2FbhyU538q065xwOtb799cE%2FVTiAiEA7v3fx8K4G5HohRmfeZy9%2FHbAuO1L5bPM4x1aV%2F997wcqiAQIkv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHszAugqLPyMRru7zyrcA8JhSA9Mc7ur1Drs6YymM36tpNPqeHkK5YJMZsLavCJT%2Bh4kTrZGcCAb%2FzfxAoQlGoqWW%2BZWuRQYiKJ0yrAeORbLREKBXapUq1beM633B0ZIlE5QSyAtWl2%2BS8fADQ9fIhkJ0fAOr%2FH6jIBKLJwGtqAehOqSuehIdaDVSkrTmzrlPTmYOh1nMd%2Fc5Kc%2Bg8lobtQ%2FJPkK%2FBTUT0WS15w6WN2pcRNM3oHIFPX4iMrUCTBpnVdvtC2%2FZE6SgIAWnbqCkPd5z9uRsi85EoMdtvbrbgeqpvxhQGM9bZMdNzTXdvUr1x4pW25tthO4BZnFa4RoWmVhcE04gp2zKFxIL5Nb%2B8zTOaK%2Bz1hiG8WvQHQ9CCiBD4SPhf%2BYHAa8GvVVos6Wd8T8PR0KV2cgWp7pZmYU%2Fa%2BUci2fWyryAzhtRPE1%2FtiIxu2xE%2BRCipFOVEoHIM0IZqdo0oG3vGSXHcxOUKtrEsgZQD45m7zt45mRbK%2Fzi%2FcR%2B6FWPRGXEaM8%2FokTQHw3lUZVSHIbe5C1ExzR5%2FBkfwKEZw3NAHeAxbfMq4JsAmoAf3MX7b7951wemV3nop170NsKsWig%2FlvjkdHaKM4NDp1eRX2gjijxqSCvte1SemMcft3SQxJqlCakq8ZBMM390r0GOqUBk1wSWVDQF5ktIyIOS4qTGe8fbG30GGDC9f90%2BRnf%2FhjZhPEI1jy98X6P0bPQ8LUkZVRKJMLNB8uthKm98sG6eecFt4LaLGYetAeGQ9MPCYBvW5LgjHZVScrwK7A16mUkwsPlfxLnM8op7obu%2FlPB1fY6U%2FHmPxkRjHgzaLpxqs1RCaEv5GZDAeBmlzT7mWjyArrFAEh6dcYUj2gj3VsGD7OvGM8D&X-Amz-Signature=61160539490611e17613bd2b0062dd0b5fda363390e054e5dd692ccd21aeabde&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667HZ367LM%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T172158Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGkaCXVzLXdlc3QtMiJHMEUCIGSiyJY9plOwxg52TT%2FbhyU538q065xwOtb799cE%2FVTiAiEA7v3fx8K4G5HohRmfeZy9%2FHbAuO1L5bPM4x1aV%2F997wcqiAQIkv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHszAugqLPyMRru7zyrcA8JhSA9Mc7ur1Drs6YymM36tpNPqeHkK5YJMZsLavCJT%2Bh4kTrZGcCAb%2FzfxAoQlGoqWW%2BZWuRQYiKJ0yrAeORbLREKBXapUq1beM633B0ZIlE5QSyAtWl2%2BS8fADQ9fIhkJ0fAOr%2FH6jIBKLJwGtqAehOqSuehIdaDVSkrTmzrlPTmYOh1nMd%2Fc5Kc%2Bg8lobtQ%2FJPkK%2FBTUT0WS15w6WN2pcRNM3oHIFPX4iMrUCTBpnVdvtC2%2FZE6SgIAWnbqCkPd5z9uRsi85EoMdtvbrbgeqpvxhQGM9bZMdNzTXdvUr1x4pW25tthO4BZnFa4RoWmVhcE04gp2zKFxIL5Nb%2B8zTOaK%2Bz1hiG8WvQHQ9CCiBD4SPhf%2BYHAa8GvVVos6Wd8T8PR0KV2cgWp7pZmYU%2Fa%2BUci2fWyryAzhtRPE1%2FtiIxu2xE%2BRCipFOVEoHIM0IZqdo0oG3vGSXHcxOUKtrEsgZQD45m7zt45mRbK%2Fzi%2FcR%2B6FWPRGXEaM8%2FokTQHw3lUZVSHIbe5C1ExzR5%2FBkfwKEZw3NAHeAxbfMq4JsAmoAf3MX7b7951wemV3nop170NsKsWig%2FlvjkdHaKM4NDp1eRX2gjijxqSCvte1SemMcft3SQxJqlCakq8ZBMM390r0GOqUBk1wSWVDQF5ktIyIOS4qTGe8fbG30GGDC9f90%2BRnf%2FhjZhPEI1jy98X6P0bPQ8LUkZVRKJMLNB8uthKm98sG6eecFt4LaLGYetAeGQ9MPCYBvW5LgjHZVScrwK7A16mUkwsPlfxLnM8op7obu%2FlPB1fY6U%2FHmPxkRjHgzaLpxqs1RCaEv5GZDAeBmlzT7mWjyArrFAEh6dcYUj2gj3VsGD7OvGM8D&X-Amz-Signature=58c26d49ffce9a8e33ce5132c315c53eab04277814ba581f36baf205bcce0ee1&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667HZ367LM%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T172158Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGkaCXVzLXdlc3QtMiJHMEUCIGSiyJY9plOwxg52TT%2FbhyU538q065xwOtb799cE%2FVTiAiEA7v3fx8K4G5HohRmfeZy9%2FHbAuO1L5bPM4x1aV%2F997wcqiAQIkv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHszAugqLPyMRru7zyrcA8JhSA9Mc7ur1Drs6YymM36tpNPqeHkK5YJMZsLavCJT%2Bh4kTrZGcCAb%2FzfxAoQlGoqWW%2BZWuRQYiKJ0yrAeORbLREKBXapUq1beM633B0ZIlE5QSyAtWl2%2BS8fADQ9fIhkJ0fAOr%2FH6jIBKLJwGtqAehOqSuehIdaDVSkrTmzrlPTmYOh1nMd%2Fc5Kc%2Bg8lobtQ%2FJPkK%2FBTUT0WS15w6WN2pcRNM3oHIFPX4iMrUCTBpnVdvtC2%2FZE6SgIAWnbqCkPd5z9uRsi85EoMdtvbrbgeqpvxhQGM9bZMdNzTXdvUr1x4pW25tthO4BZnFa4RoWmVhcE04gp2zKFxIL5Nb%2B8zTOaK%2Bz1hiG8WvQHQ9CCiBD4SPhf%2BYHAa8GvVVos6Wd8T8PR0KV2cgWp7pZmYU%2Fa%2BUci2fWyryAzhtRPE1%2FtiIxu2xE%2BRCipFOVEoHIM0IZqdo0oG3vGSXHcxOUKtrEsgZQD45m7zt45mRbK%2Fzi%2FcR%2B6FWPRGXEaM8%2FokTQHw3lUZVSHIbe5C1ExzR5%2FBkfwKEZw3NAHeAxbfMq4JsAmoAf3MX7b7951wemV3nop170NsKsWig%2FlvjkdHaKM4NDp1eRX2gjijxqSCvte1SemMcft3SQxJqlCakq8ZBMM390r0GOqUBk1wSWVDQF5ktIyIOS4qTGe8fbG30GGDC9f90%2BRnf%2FhjZhPEI1jy98X6P0bPQ8LUkZVRKJMLNB8uthKm98sG6eecFt4LaLGYetAeGQ9MPCYBvW5LgjHZVScrwK7A16mUkwsPlfxLnM8op7obu%2FlPB1fY6U%2FHmPxkRjHgzaLpxqs1RCaEv5GZDAeBmlzT7mWjyArrFAEh6dcYUj2gj3VsGD7OvGM8D&X-Amz-Signature=c68ba4bc296f891530980db3f6a9447fd378a96cb11e9a48f33cfa3a1425849a&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RDQORQ74%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T172159Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGkaCXVzLXdlc3QtMiJGMEQCIFqxzgDoJumVDzEuzyfKnAcWY%2FkIJKLbRmrNtLV5Q4TbAiBgi6hbSJbP6hRGNyQFEBJFlaxNeXwLLWbCref%2FpF25iSqIBAiS%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMDnW5s0NyqGQe6GueKtwDdE4erIfkeEurnFYf%2FPWHf3MgxpzxdO9PwAoejnjbofQ5EI4bxo8%2Fv7QwELS6iZCf%2BlXF97f0or5YwG%2F%2BqL1GRjeN0ybHh97UwXCIo6UwCR49D%2FjW02SJW%2FYBAwqtd8ekny1%2BNQFHg7ljLvYMYSkyxHnGU8nRpqzvusbZLJhXgZZhwhC%2FjAu4wfdmaPv4XrCH5yacfcYEK8eX9OkZ1fFuaPBdE0Ee6hI8qly9z5c8Htt3eZibkyxoJ4LCXizZlJrVWCoomMbLs6UF0HBxQ46w%2B%2Fqmlmese%2FzAShZvI3hSNCZyQoniYGbEr%2BR870KIIzhLa5m38iBiqYFqfYZ%2F6%2BmaeahHapSgeGJVB6Qtxb%2Bp%2BqzR3OWN4WRiTXDo4YAK4vYzAyplEmcBF3sVJWUk0hp%2BJm%2F9Sx3PTahcTZVwi6CVBXE6l87DlcGmVKkArlWdreOKM4iubYzvjIQ%2BR7IQNT11T61wYg80nKRuPO4QztSxSBDotz%2FlquD%2F8gB%2BaaLcQALMF%2FkZQwzxN0m%2FgDaWs6QZF6O5avx15QkbJ5m1qrpl%2BcrnDUI45VD6kO7HwA%2BxhPFqKcxAHz6wvhGMHwXB3yEfAllnGt18JlnjUZw7zZARnjMarWz%2F5ww2rzp9%2BiEwpv7SvQY6pgGHVnNaM0dc5j2SRVEy0lbsNOfI8ORwWJCCk%2BUFakNqnEVW8v5Nv1p0mnoHN8%2Fv5qlZ7h04jLoxdlTXsIg6mRaa2thXRw0heBAy1YFVOgqBTvua%2BBN8UE6A6WxOnBh7N%2B5fcnOFS1jKzh0EaHTUfXr2Jzb%2Fz059Z6xbrsSNHsX1iCwsyFvky6vYN4C%2Fxm6iQOs807VPnWVgAWVQQbmA3bsBRi%2BXHvF5&X-Amz-Signature=ddd9f899634eca7a47c1b3d8dc0ef31c9c07f789aad3eeae9217571f05a2191f&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TI5QM6NZ%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T172200Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGkaCXVzLXdlc3QtMiJHMEUCIDupTMJ9exr1g52pm0vlafUEVoxVeazwOIQQ1SdMrwPzAiEA%2B5RL9qZU3BuutDZdUbBiCUMqArTXJZU%2FfJIRqSIDqfoqiAQIkv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDO6zUHkNWzhWOuHpaCrcA3ZRl0hZxcsMnLzfpFlJlXuiHkBIxYXMNeK%2FfBhjFko3qe%2FJq%2Fbb%2B2Jfq6QLpdMT6AW00L71bcVQjGWCe0xvlzsSJJr%2BgoAsPHc9igaMOqgD%2B32vyaDYVY7d3dGNJHFPstZSEoTI7wDR0pAVFf8Vxq66M%2Fcb73dyzw55LeNh0mxOcDfFETdDd9019TEop3FBg8BZkf0XnkmCaF%2FEPEdLhH5cXWJ%2Fysrf3AoN6GhB90CI37fZ8I0jBVAC50bkEU44vvgib3nV8L8irVhEoj1rTDWa%2Ffv7grWCsmr7xVXEF7CA0S2H9CRKcaAWK%2F89mUt2%2FFg7LNDPaItEkXIE9lFsXmvi%2Fg7f6HGvSHlpEnbeA%2FQscILfLWsULhfQAZbwkVryRRIi24r7KLy%2BWvnXJsxA3VXC7SnfZHZiCKkY6An7OsPTcBSlzyb4y6sflTQHkK%2FiK3PbFfGcYlYI3qyZkeL1%2FP65bW%2BrRLcg%2BZeoHeU%2F%2FRcCmp9B01Wyw08wreLNW68lJ9%2Frod0q2V3eave0B63NWgt9KamMYBgpjH6OmRkkPae3MSrCfuXMcMgn0BC4Dq0Lmh%2Frh8DIuFpA6KfnSwI85HNcKwP3kRe0VnEDNNp%2BKZJSxpob05Jv3hgyA7sTMLn%2B0r0GOqUB174anwzmS4JL7xhuia7%2FnhI35z%2Bs%2B4KmLBLHZL0hbfPTv1h9LQvFa9Jh4gh2z%2BYvqJSRNAYw4Ne0iUQ4OSLFUBTDuQs3JTYqUV0xqLXyuDTNUQVkbo3dsHjyc%2BNgX%2B87Ib269B%2FWUAjwAdb4pAyG%2BsG1gxqZAWY4y%2BCeWmo%2Bcojz5LTu8somUElbnlRxTG9EBubdXlmD82p4mhZ4hg7OWeVQC%2F%2F1&X-Amz-Signature=ff2c4862175fbc32686cf36b501ee487172ee21dec9b1c5b544b839c6b253e94&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667HZ367LM%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T172158Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGkaCXVzLXdlc3QtMiJHMEUCIGSiyJY9plOwxg52TT%2FbhyU538q065xwOtb799cE%2FVTiAiEA7v3fx8K4G5HohRmfeZy9%2FHbAuO1L5bPM4x1aV%2F997wcqiAQIkv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHszAugqLPyMRru7zyrcA8JhSA9Mc7ur1Drs6YymM36tpNPqeHkK5YJMZsLavCJT%2Bh4kTrZGcCAb%2FzfxAoQlGoqWW%2BZWuRQYiKJ0yrAeORbLREKBXapUq1beM633B0ZIlE5QSyAtWl2%2BS8fADQ9fIhkJ0fAOr%2FH6jIBKLJwGtqAehOqSuehIdaDVSkrTmzrlPTmYOh1nMd%2Fc5Kc%2Bg8lobtQ%2FJPkK%2FBTUT0WS15w6WN2pcRNM3oHIFPX4iMrUCTBpnVdvtC2%2FZE6SgIAWnbqCkPd5z9uRsi85EoMdtvbrbgeqpvxhQGM9bZMdNzTXdvUr1x4pW25tthO4BZnFa4RoWmVhcE04gp2zKFxIL5Nb%2B8zTOaK%2Bz1hiG8WvQHQ9CCiBD4SPhf%2BYHAa8GvVVos6Wd8T8PR0KV2cgWp7pZmYU%2Fa%2BUci2fWyryAzhtRPE1%2FtiIxu2xE%2BRCipFOVEoHIM0IZqdo0oG3vGSXHcxOUKtrEsgZQD45m7zt45mRbK%2Fzi%2FcR%2B6FWPRGXEaM8%2FokTQHw3lUZVSHIbe5C1ExzR5%2FBkfwKEZw3NAHeAxbfMq4JsAmoAf3MX7b7951wemV3nop170NsKsWig%2FlvjkdHaKM4NDp1eRX2gjijxqSCvte1SemMcft3SQxJqlCakq8ZBMM390r0GOqUBk1wSWVDQF5ktIyIOS4qTGe8fbG30GGDC9f90%2BRnf%2FhjZhPEI1jy98X6P0bPQ8LUkZVRKJMLNB8uthKm98sG6eecFt4LaLGYetAeGQ9MPCYBvW5LgjHZVScrwK7A16mUkwsPlfxLnM8op7obu%2FlPB1fY6U%2FHmPxkRjHgzaLpxqs1RCaEv5GZDAeBmlzT7mWjyArrFAEh6dcYUj2gj3VsGD7OvGM8D&X-Amz-Signature=5bd9b72b7b6ec70031fcc7bb689a3a02c8bd4c4d73153f057d13255a7d3e2a33&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667HZ367LM%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T172158Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGkaCXVzLXdlc3QtMiJHMEUCIGSiyJY9plOwxg52TT%2FbhyU538q065xwOtb799cE%2FVTiAiEA7v3fx8K4G5HohRmfeZy9%2FHbAuO1L5bPM4x1aV%2F997wcqiAQIkv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHszAugqLPyMRru7zyrcA8JhSA9Mc7ur1Drs6YymM36tpNPqeHkK5YJMZsLavCJT%2Bh4kTrZGcCAb%2FzfxAoQlGoqWW%2BZWuRQYiKJ0yrAeORbLREKBXapUq1beM633B0ZIlE5QSyAtWl2%2BS8fADQ9fIhkJ0fAOr%2FH6jIBKLJwGtqAehOqSuehIdaDVSkrTmzrlPTmYOh1nMd%2Fc5Kc%2Bg8lobtQ%2FJPkK%2FBTUT0WS15w6WN2pcRNM3oHIFPX4iMrUCTBpnVdvtC2%2FZE6SgIAWnbqCkPd5z9uRsi85EoMdtvbrbgeqpvxhQGM9bZMdNzTXdvUr1x4pW25tthO4BZnFa4RoWmVhcE04gp2zKFxIL5Nb%2B8zTOaK%2Bz1hiG8WvQHQ9CCiBD4SPhf%2BYHAa8GvVVos6Wd8T8PR0KV2cgWp7pZmYU%2Fa%2BUci2fWyryAzhtRPE1%2FtiIxu2xE%2BRCipFOVEoHIM0IZqdo0oG3vGSXHcxOUKtrEsgZQD45m7zt45mRbK%2Fzi%2FcR%2B6FWPRGXEaM8%2FokTQHw3lUZVSHIbe5C1ExzR5%2FBkfwKEZw3NAHeAxbfMq4JsAmoAf3MX7b7951wemV3nop170NsKsWig%2FlvjkdHaKM4NDp1eRX2gjijxqSCvte1SemMcft3SQxJqlCakq8ZBMM390r0GOqUBk1wSWVDQF5ktIyIOS4qTGe8fbG30GGDC9f90%2BRnf%2FhjZhPEI1jy98X6P0bPQ8LUkZVRKJMLNB8uthKm98sG6eecFt4LaLGYetAeGQ9MPCYBvW5LgjHZVScrwK7A16mUkwsPlfxLnM8op7obu%2FlPB1fY6U%2FHmPxkRjHgzaLpxqs1RCaEv5GZDAeBmlzT7mWjyArrFAEh6dcYUj2gj3VsGD7OvGM8D&X-Amz-Signature=4a8f9d12123a75ba6cff1d93ec93cbddc1dda44df561eb6004b54b97693930aa&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667HZ367LM%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T172158Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGkaCXVzLXdlc3QtMiJHMEUCIGSiyJY9plOwxg52TT%2FbhyU538q065xwOtb799cE%2FVTiAiEA7v3fx8K4G5HohRmfeZy9%2FHbAuO1L5bPM4x1aV%2F997wcqiAQIkv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHszAugqLPyMRru7zyrcA8JhSA9Mc7ur1Drs6YymM36tpNPqeHkK5YJMZsLavCJT%2Bh4kTrZGcCAb%2FzfxAoQlGoqWW%2BZWuRQYiKJ0yrAeORbLREKBXapUq1beM633B0ZIlE5QSyAtWl2%2BS8fADQ9fIhkJ0fAOr%2FH6jIBKLJwGtqAehOqSuehIdaDVSkrTmzrlPTmYOh1nMd%2Fc5Kc%2Bg8lobtQ%2FJPkK%2FBTUT0WS15w6WN2pcRNM3oHIFPX4iMrUCTBpnVdvtC2%2FZE6SgIAWnbqCkPd5z9uRsi85EoMdtvbrbgeqpvxhQGM9bZMdNzTXdvUr1x4pW25tthO4BZnFa4RoWmVhcE04gp2zKFxIL5Nb%2B8zTOaK%2Bz1hiG8WvQHQ9CCiBD4SPhf%2BYHAa8GvVVos6Wd8T8PR0KV2cgWp7pZmYU%2Fa%2BUci2fWyryAzhtRPE1%2FtiIxu2xE%2BRCipFOVEoHIM0IZqdo0oG3vGSXHcxOUKtrEsgZQD45m7zt45mRbK%2Fzi%2FcR%2B6FWPRGXEaM8%2FokTQHw3lUZVSHIbe5C1ExzR5%2FBkfwKEZw3NAHeAxbfMq4JsAmoAf3MX7b7951wemV3nop170NsKsWig%2FlvjkdHaKM4NDp1eRX2gjijxqSCvte1SemMcft3SQxJqlCakq8ZBMM390r0GOqUBk1wSWVDQF5ktIyIOS4qTGe8fbG30GGDC9f90%2BRnf%2FhjZhPEI1jy98X6P0bPQ8LUkZVRKJMLNB8uthKm98sG6eecFt4LaLGYetAeGQ9MPCYBvW5LgjHZVScrwK7A16mUkwsPlfxLnM8op7obu%2FlPB1fY6U%2FHmPxkRjHgzaLpxqs1RCaEv5GZDAeBmlzT7mWjyArrFAEh6dcYUj2gj3VsGD7OvGM8D&X-Amz-Signature=3833f1e0ea9d387134a56f7f05c228636d01329a9278ec1e3730b08333e89978&X-Amz-SignedHeaders=host&x-id=GetObject)


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

