---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466WEJPO3K3%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250209T032723Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCYVTmIBuxiA%2FOR9\
  6s5Q2GOC7OIp6MUVdjW8hbEvwyQewIgJcZAVFWIG%2B91fnH03hUYN9n8t5zupsLnzDzaDTUO77Eq\
  iAQInf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPYpqzb4GXbabYJYC\
  CrcA2lnsOkRNVe2ucLOh2PCneOM%2FC%2BgQkD%2FTIxofE9U21XCmS4mlvf9kTywHqoiJgep0oeD\
  GU1NN%2Fpi6EqOglMgyO%2F9UMnW9dyhC50vGSiMi3BZ4eu7GJUnKStvlUomKfmhmRe2rfQJBC0a0\
  gEJL5uQWfjxC92mUFAT24OdN26wJoUkO4i3B4ibJL5Hgutw2g4fYtWh4HhPQmoXLUb5WYycM6kdST\
  Xm4d654bzA%2BGIoBvjQ8rMvplarITa%2FCZr8S5B03Nmt%2BosYiBJYxqVhIT3Dinq5CvRTAgCzx\
  UjUAbBplK%2Fv8MdQDCOsKykHLoNdorcLKjjsEvBM6AJE0dEABAgcTRJ8uL%2FzB%2FdzVfJi4Vax\
  LGpDXTWlopjBX%2BAny%2BukWYJjfraOwakmua7w17QAUSj0D%2FceXrXtvEIKL%2FfR4t3pNO8ID\
  AZ4WqSvq0kzle%2BSRYThYnubsQYek5snVGf64PqEcItkhbK1Ytxv9mIRbVMDEFeiZ4YNqErhL9jJ\
  78hZZVvRIsmnV6KGZRCgZWS48O6CiQtuP0CAuluQyE3RDVECUjWiJSMfJRxC%2BTXIQC%2Fdnc8vi\
  Dl6qPRZBI8vtt69XtFuATBWs%2Fh8cwdbQivvrgN70g%2FsQzYC2Sj2VR60gFbBMMK%2FoL0GOqUB\
  6r8UHWtuBEpIQhL86m3w6l%2BVxCEsm1FQOmt4geJ%2F4KMHRr%2BTgs3s9u4%2FZqG5Nq63Y%2B2\
  R6V36XakUvKDIcz7ORlCVabqunRIqn5b4xHg8Qu4MlhoJ4Ugx1BIBt4HxskNQu3HTmA%2BHnyxzM6\
  p%2FX3EcjtlKkA2Z6Y8tnzWk4BrOnSpGWfKcNkubm3SqwmYFBxGdLkos43GwXT6VTNkauy2tRf9Zv\
  wDW&X-Amz-Signature=c36a65844104d9edf45cc0c592e7d329f187632c6ddf34fa22c4840c4\
  bb556c7&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4664ECIZDYT%2F20250209%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250209T032608Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEY\
        CIQCo34fBANHjSXyecHYN9%2FuLsUuzjSLvACkpzht06z%2BeOwIhAMzl%2B79GAKL8BWCh\
        xC5mUOa0T6Rw3EVmLvuwhBPMlNWmKogECJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABo\
        MNjM3NDIzMTgzODA1IgyB2wjRMLKKla7Xp4Qq3AO9gESekQdBIw4SlW775huf8BVaCgJZFK\
        xuUJ1tttUVq6cZX1OYapPidchnBmJkdxdcolIhl4l3sp%2Bt%2FfK0%2Fbi3iQ5MtL%2Bz7\
        4Jke%2F%2FBi7saMsPtCBVALvQd3fcHcH6wLkVlokhIbDaP5c7bRWmUji3ihXbz4rX6HebC\
        bNdNyuEdVg7xuEnmCLlTducE9vusi0pPkE7GaDQZYuupVkJllXaHdIarXW0J671n6B9okdS\
        fu0EtVLiLt1vtSNcu7yV18rbYd4JyxvrdCr%2Fqx6XeKbulVc9CDDzfbAfK66pfyOs7YCB3\
        adRxZepEjcCDeyzdqV%2BdKC8bMEIS74kivK0DRT8Knyc1GHTK4%2FXr%2BcAiUdhqAcnq2\
        RsWA5SY%2Bcl9Jy5f2obW7mZYJfjDi%2BMxT7Dp0XXhQfzMyqI3RRjSxfb2iTGf01nUrxhQ\
        oVudgli3HCgF4TyiUJB16fT4QqWeWgO4rSPG0W2SZV0PfmkNqoBkpi1SvnvGhtrmh%2FIxB\
        C5Y%2F4eUWS8ykQC0GzW0yFNvbCfQQegvLWDq3me0Z3AbtytzBt9yiLcZPGhGEcKS9HURpO\
        brmT0SCVPbuJRIpwBwyEsvb%2BX%2Fz%2FlcMnnCbRoNzarbg3OMUvT3wBHJCwAETY19JTD\
        qvqC9BjqkAf%2BYijZImvMFg8vIWcp06b3y8bwaPt0M4gjeHONWeNDkwZ%2Bpi81PQbFBQs\
        nU91qBfe9nPetkKDn2Ku4831RDkNV3%2B16P6i00Rsh5bWV8LZC%2BuN%2FEVeeQXgiKDfG\
        Dxmy4%2FiBLf3mxJd6xQUVv%2F0N8fzm3IXoR0sHXD5FE1jAJD8NJeVlpDz2J9rVEVRJo%2\
        BjVDm%2BSkC1wPIuMoU3qqxH24TfiWPkL4&X-Amz-Signature=ddda3c319fcc08e33080\
        c7f519a6b8776828e9224fead3d9dcb5ea2f8f6c2356&X-Amz-SignedHeaders=host&x\
        -id=GetObject"
      expiry_time: "2025-02-09T04:26:08.156Z"
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
UPDATE_TIME: "2025-02-09T03:27:34.504Z"
EXPIRY_TIME: "2025-02-09T04:27:20.506Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666QEKXMNB%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T032721Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCyb87aVaMFdj3%2BCPonWySWvrXeXO7yWQUnxahixdJK3QIhAIsKTaTcKElDxc89JT8DoaShK9ZJIpUs1uMLbb%2FXIwNlKogECJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igxz17sc9JoBgsY4h14q3ANe%2BhcABNQmVQeMCwkEm2vcrJRQk25pUwOQDfjw83d84oG52hpqspfQZlM82TUyriESoUE7O%2BFnZgsI4WVf0z0QV3ppyg6ZzbqZXcJas%2B7eQ9czQfQSGxO6w3IznLCJbhAYVvayWpVeD90rUq6MBcRUao6rfPJLr9kdiFGmxwhCTtDVsl5jk2FSF1ldAA91RfFNl4%2FSPvm7Be6TnmiaS50tgLnnro515lHbw6M8%2FKp2s%2FSJW%2F84nxvVVzKDEW98%2Bc7RjVPFNu9M8Vuo0gGpX6gimNrqUMeVulqWm8WXoYLjxBWlqbpl5thRJjhlEttZ4W4I96WDfk78ccjk5KIa%2FrxmikqI76kay3T7H%2B0GMxKxvwtJxmbSXKQuzP5YBan54PWgqyKa4JyqvDsFYmSWQA0rCkjPOUh3X0%2FcGWdwLyDzpn0ATJB3nQcifXX6DO3bR%2BIq5Srxgggz0tGaJN%2FJrqRKiggncosa%2FPItwVgQ5%2BmdVvhWATSH%2FUJP4uMrms5x%2Bwwigo8%2BTVm7Wl4suCwWiayb%2Fw3dTeKPXewtII0H5s2mXcjjw3yCUF2829ans7vQS6BBZMhW%2F0%2FrO0CDW6XCeSqLCS%2BMNSgBJDqCxDuBoRtTbQ6WIxKzd3C37uUmhTDhvqC9BjqkAfF2A5StHhC2nzYDp50f7CjOJee1rG%2FRCZ%2BOOAcSP0KnfjOxkssEiEoQ6CnGJH%2FRn59Fw3zfWDa8EmUgsT0O7xsUEV6Z4bGRDVIStYEUJgOQT0hUPswMYt2kl3l2%2BvFDHo9aPrszCSx00p8IaofJ62mhiL8Iep4brn8OnS6NSKEzkwF8poh%2F7N%2F2d5cGm%2Fu%2FAmTnOGvbc5FmmPbvTyi7X86Nz3x4&X-Amz-Signature=b9f8b3a6015e394ed53a5eed51e5e164c1bb332434dff06d8571ffd1d4eaf041&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666QEKXMNB%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T032721Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCyb87aVaMFdj3%2BCPonWySWvrXeXO7yWQUnxahixdJK3QIhAIsKTaTcKElDxc89JT8DoaShK9ZJIpUs1uMLbb%2FXIwNlKogECJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igxz17sc9JoBgsY4h14q3ANe%2BhcABNQmVQeMCwkEm2vcrJRQk25pUwOQDfjw83d84oG52hpqspfQZlM82TUyriESoUE7O%2BFnZgsI4WVf0z0QV3ppyg6ZzbqZXcJas%2B7eQ9czQfQSGxO6w3IznLCJbhAYVvayWpVeD90rUq6MBcRUao6rfPJLr9kdiFGmxwhCTtDVsl5jk2FSF1ldAA91RfFNl4%2FSPvm7Be6TnmiaS50tgLnnro515lHbw6M8%2FKp2s%2FSJW%2F84nxvVVzKDEW98%2Bc7RjVPFNu9M8Vuo0gGpX6gimNrqUMeVulqWm8WXoYLjxBWlqbpl5thRJjhlEttZ4W4I96WDfk78ccjk5KIa%2FrxmikqI76kay3T7H%2B0GMxKxvwtJxmbSXKQuzP5YBan54PWgqyKa4JyqvDsFYmSWQA0rCkjPOUh3X0%2FcGWdwLyDzpn0ATJB3nQcifXX6DO3bR%2BIq5Srxgggz0tGaJN%2FJrqRKiggncosa%2FPItwVgQ5%2BmdVvhWATSH%2FUJP4uMrms5x%2Bwwigo8%2BTVm7Wl4suCwWiayb%2Fw3dTeKPXewtII0H5s2mXcjjw3yCUF2829ans7vQS6BBZMhW%2F0%2FrO0CDW6XCeSqLCS%2BMNSgBJDqCxDuBoRtTbQ6WIxKzd3C37uUmhTDhvqC9BjqkAfF2A5StHhC2nzYDp50f7CjOJee1rG%2FRCZ%2BOOAcSP0KnfjOxkssEiEoQ6CnGJH%2FRn59Fw3zfWDa8EmUgsT0O7xsUEV6Z4bGRDVIStYEUJgOQT0hUPswMYt2kl3l2%2BvFDHo9aPrszCSx00p8IaofJ62mhiL8Iep4brn8OnS6NSKEzkwF8poh%2F7N%2F2d5cGm%2Fu%2FAmTnOGvbc5FmmPbvTyi7X86Nz3x4&X-Amz-Signature=56ac095fd00f2e4c68f28b65a4187eca9f21dbd7de8cd4f1be443dcac7f6bea8&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666QEKXMNB%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T032721Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCyb87aVaMFdj3%2BCPonWySWvrXeXO7yWQUnxahixdJK3QIhAIsKTaTcKElDxc89JT8DoaShK9ZJIpUs1uMLbb%2FXIwNlKogECJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igxz17sc9JoBgsY4h14q3ANe%2BhcABNQmVQeMCwkEm2vcrJRQk25pUwOQDfjw83d84oG52hpqspfQZlM82TUyriESoUE7O%2BFnZgsI4WVf0z0QV3ppyg6ZzbqZXcJas%2B7eQ9czQfQSGxO6w3IznLCJbhAYVvayWpVeD90rUq6MBcRUao6rfPJLr9kdiFGmxwhCTtDVsl5jk2FSF1ldAA91RfFNl4%2FSPvm7Be6TnmiaS50tgLnnro515lHbw6M8%2FKp2s%2FSJW%2F84nxvVVzKDEW98%2Bc7RjVPFNu9M8Vuo0gGpX6gimNrqUMeVulqWm8WXoYLjxBWlqbpl5thRJjhlEttZ4W4I96WDfk78ccjk5KIa%2FrxmikqI76kay3T7H%2B0GMxKxvwtJxmbSXKQuzP5YBan54PWgqyKa4JyqvDsFYmSWQA0rCkjPOUh3X0%2FcGWdwLyDzpn0ATJB3nQcifXX6DO3bR%2BIq5Srxgggz0tGaJN%2FJrqRKiggncosa%2FPItwVgQ5%2BmdVvhWATSH%2FUJP4uMrms5x%2Bwwigo8%2BTVm7Wl4suCwWiayb%2Fw3dTeKPXewtII0H5s2mXcjjw3yCUF2829ans7vQS6BBZMhW%2F0%2FrO0CDW6XCeSqLCS%2BMNSgBJDqCxDuBoRtTbQ6WIxKzd3C37uUmhTDhvqC9BjqkAfF2A5StHhC2nzYDp50f7CjOJee1rG%2FRCZ%2BOOAcSP0KnfjOxkssEiEoQ6CnGJH%2FRn59Fw3zfWDa8EmUgsT0O7xsUEV6Z4bGRDVIStYEUJgOQT0hUPswMYt2kl3l2%2BvFDHo9aPrszCSx00p8IaofJ62mhiL8Iep4brn8OnS6NSKEzkwF8poh%2F7N%2F2d5cGm%2Fu%2FAmTnOGvbc5FmmPbvTyi7X86Nz3x4&X-Amz-Signature=72dca16dc1909041c51f58402e20963ebcc186f18348958a162c81122925658c&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666QEKXMNB%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T032721Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCyb87aVaMFdj3%2BCPonWySWvrXeXO7yWQUnxahixdJK3QIhAIsKTaTcKElDxc89JT8DoaShK9ZJIpUs1uMLbb%2FXIwNlKogECJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igxz17sc9JoBgsY4h14q3ANe%2BhcABNQmVQeMCwkEm2vcrJRQk25pUwOQDfjw83d84oG52hpqspfQZlM82TUyriESoUE7O%2BFnZgsI4WVf0z0QV3ppyg6ZzbqZXcJas%2B7eQ9czQfQSGxO6w3IznLCJbhAYVvayWpVeD90rUq6MBcRUao6rfPJLr9kdiFGmxwhCTtDVsl5jk2FSF1ldAA91RfFNl4%2FSPvm7Be6TnmiaS50tgLnnro515lHbw6M8%2FKp2s%2FSJW%2F84nxvVVzKDEW98%2Bc7RjVPFNu9M8Vuo0gGpX6gimNrqUMeVulqWm8WXoYLjxBWlqbpl5thRJjhlEttZ4W4I96WDfk78ccjk5KIa%2FrxmikqI76kay3T7H%2B0GMxKxvwtJxmbSXKQuzP5YBan54PWgqyKa4JyqvDsFYmSWQA0rCkjPOUh3X0%2FcGWdwLyDzpn0ATJB3nQcifXX6DO3bR%2BIq5Srxgggz0tGaJN%2FJrqRKiggncosa%2FPItwVgQ5%2BmdVvhWATSH%2FUJP4uMrms5x%2Bwwigo8%2BTVm7Wl4suCwWiayb%2Fw3dTeKPXewtII0H5s2mXcjjw3yCUF2829ans7vQS6BBZMhW%2F0%2FrO0CDW6XCeSqLCS%2BMNSgBJDqCxDuBoRtTbQ6WIxKzd3C37uUmhTDhvqC9BjqkAfF2A5StHhC2nzYDp50f7CjOJee1rG%2FRCZ%2BOOAcSP0KnfjOxkssEiEoQ6CnGJH%2FRn59Fw3zfWDa8EmUgsT0O7xsUEV6Z4bGRDVIStYEUJgOQT0hUPswMYt2kl3l2%2BvFDHo9aPrszCSx00p8IaofJ62mhiL8Iep4brn8OnS6NSKEzkwF8poh%2F7N%2F2d5cGm%2Fu%2FAmTnOGvbc5FmmPbvTyi7X86Nz3x4&X-Amz-Signature=c04ad55554784efd9ae65d73d40bf26bd1f2929557ffb271b9a9581c3370656b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666QEKXMNB%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T032721Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCyb87aVaMFdj3%2BCPonWySWvrXeXO7yWQUnxahixdJK3QIhAIsKTaTcKElDxc89JT8DoaShK9ZJIpUs1uMLbb%2FXIwNlKogECJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igxz17sc9JoBgsY4h14q3ANe%2BhcABNQmVQeMCwkEm2vcrJRQk25pUwOQDfjw83d84oG52hpqspfQZlM82TUyriESoUE7O%2BFnZgsI4WVf0z0QV3ppyg6ZzbqZXcJas%2B7eQ9czQfQSGxO6w3IznLCJbhAYVvayWpVeD90rUq6MBcRUao6rfPJLr9kdiFGmxwhCTtDVsl5jk2FSF1ldAA91RfFNl4%2FSPvm7Be6TnmiaS50tgLnnro515lHbw6M8%2FKp2s%2FSJW%2F84nxvVVzKDEW98%2Bc7RjVPFNu9M8Vuo0gGpX6gimNrqUMeVulqWm8WXoYLjxBWlqbpl5thRJjhlEttZ4W4I96WDfk78ccjk5KIa%2FrxmikqI76kay3T7H%2B0GMxKxvwtJxmbSXKQuzP5YBan54PWgqyKa4JyqvDsFYmSWQA0rCkjPOUh3X0%2FcGWdwLyDzpn0ATJB3nQcifXX6DO3bR%2BIq5Srxgggz0tGaJN%2FJrqRKiggncosa%2FPItwVgQ5%2BmdVvhWATSH%2FUJP4uMrms5x%2Bwwigo8%2BTVm7Wl4suCwWiayb%2Fw3dTeKPXewtII0H5s2mXcjjw3yCUF2829ans7vQS6BBZMhW%2F0%2FrO0CDW6XCeSqLCS%2BMNSgBJDqCxDuBoRtTbQ6WIxKzd3C37uUmhTDhvqC9BjqkAfF2A5StHhC2nzYDp50f7CjOJee1rG%2FRCZ%2BOOAcSP0KnfjOxkssEiEoQ6CnGJH%2FRn59Fw3zfWDa8EmUgsT0O7xsUEV6Z4bGRDVIStYEUJgOQT0hUPswMYt2kl3l2%2BvFDHo9aPrszCSx00p8IaofJ62mhiL8Iep4brn8OnS6NSKEzkwF8poh%2F7N%2F2d5cGm%2Fu%2FAmTnOGvbc5FmmPbvTyi7X86Nz3x4&X-Amz-Signature=2c4259056877c533d826910aa4282cbd2a0f37e2abdde1c9d17f1785af762925&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SWMUWCH2%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T032722Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIGEIeEuKzMgQeEofHDtjC92Ly1imwxx2gtXKWjWVSwhtAiB6rlVajCp8HeTdm%2BahfKV7TeTYZ530FQCKtqTompDoMCqIBAic%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMzvdg5qhOXR5V9YkoKtwDuy6PsqbND4Z2i5i6JYHU9wyujc3MLgLXUo3npCf58Hm1lJFNChZ%2BCHE%2BGd8Dc2kH9NT%2FOG7i5dIGEFEwLqW3%2Bnu2eJpeiqa3U284gR8xUslQdh7Pxb3xFNnG3P09a11DlFWEUu47fq%2Fbp8nI2xXjx6CsVS%2BOIq6n4SOGL%2BBYNDH7iYiRhRNEVeXzOFBjTwHstHK0neZYcuUz9Eo%2BmBfnvLrxoIYc8DcaqZ%2BkYdOazcviTDeBkv0v78i17alAt7PvlFJ9QzCXBYc1KX61Fz9jF3DZTrw2IRXH%2Bn%2FrSI6NhAmD9T1Du9ODgIuCT3nrGmA3llzCPwHbs9zgeftnonjIGFL54PeTgBbOsMT6JnZvwo8KHnvFiI6kw0Y%2BHts1MJMav%2FR1rOkjoDAK%2BlvrueECKIxg79qHuSIfmKJeooIa6IS4MrPxy4QRXvrwBbHZGAxB7%2FYSQK%2BJ%2FkNRp5KXRWGBLi6JI%2FaFjNQsWzkuy3VqkWzTVSG7UjlRhl7RfMGI8l3oUwfikpK8l5DFz4xYx%2FOyF%2BFJliHAx7XG47PtHtLDEIYvpBVy6eTs6Dv0gy1sjFMz4NmDpCK6XMtpZE85uBzfSOot5i9cRVqgnIBulOURAtwGm4LTOCbYnBIsc9Uw6r6gvQY6pgGWPGPJYId%2FXyXlmxkZtR%2FdsdukD6nua7JMikmfrl9AlT8A%2Bn1a2DJRMA7LcZvnrtX6RuMFfkJwTFYKJqjbgK1KkhPyalHHMcjFORUQm5jWTZzsH2NMixwgoQ7icyaPz0nqvsMkcaRymBPmB7R3mTcnBWddvbu5WHt9LSVNud%2Bn6mKYNHgoPCi8TUdcLDDN1l6Sme4Gc765LACvEcp5LsXh6V6nmP6s&X-Amz-Signature=44b0f9ae67564a6dec5cafa1b9b2376418b62361ec28a283aeebfed42b38e234&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665MZPPJGM%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T032723Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBZLerbkgwMdnY8CGDix%2BQbfG2ExyDxHPPdQDfcyl0%2BiAiEAoqSHE75cGCdn4kB%2FpKMwyCrIgSGDgjY9aHFbBgkkHvgqiAQInf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDEEth9GtGR7sstunrircA96bDEZ9HhB3Hj4cxpdD3w89xGyLkeRy9x0TjUNe9PTOHiIYHPxABjobJsuO0UB%2B1l6LzHQNtaj4EOi%2BnV%2F8gc7EyNAwpYnQ%2Fm%2FsuwadhwNVewdi6XxTCCLBH%2FXXOXtq3F8LUeCambpH06J59hIvDi3LWmfvBZVVKKABKDJsAjawhqu%2F%2FM7bB3TdLXr8Eq0lJITOId6qKVx5wLFZGzN0VxH%2FxbKkM38RXg4XWr9tpylQ44nHiGJh2EJTDnzvv4G5HStKGE%2F%2F7kUmL7BQrYT1Ss2TZFz65RINac9nbW6QYv1nqKE6v3el3bHBQyIofSwmwjmeMIJZ5Ht2qcjZin59g5%2BFkbvTfPkX0OqhpxEynKE784IRZAM1uqS17ZwBxPsRsDRSXzpkgSJ5aekbHHQvww3KAY8BK4UTqbzn1shu3MDPabJ3x2gpc1EmBbvg4pwzONW57F%2BED1B0pJFr0%2FVwNSxt1yj5aN9F363pY%2FxbEJ9ZuHnDtn3tJTpSvX%2FLdc9rzOeKnAcy8m3UoFFqWzPSOU8tpA6dkgm617%2FyJxkVOtlUpA2b3gowGUrPdve3QTG2goDnL2FoEa382elmBMmnZdjb39UuFyNpjq9R2wiUM7ptsvCvYQEnnQZso6JbMLO%2FoL0GOqUBho72CxXE6uLR7%2BBNsOH30ZL4m4DqbdZxMdPebAcVhAzIfv4wdxQFZKXiK%2BtXAUa7JJ2%2BopmWrtG%2BK%2FRipSFENhA%2FRAlxAd4FItU23HSMSRuQH7qoBDVJu5%2BXwflAcgYrT2NsCq5eGz%2FYYHHuvrU2%2BMd1tXGByhL%2B3ADUBxWG0s1IEBv%2BomhOhxwNs3GYF0s9RSyuaxAvrwEOvboCeEXrrFXxU1Hh&X-Amz-Signature=2bce502ca87e40730212c4fe79a5a189aacd02e4397a71732f8250d216c70b71&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666QEKXMNB%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T032721Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCyb87aVaMFdj3%2BCPonWySWvrXeXO7yWQUnxahixdJK3QIhAIsKTaTcKElDxc89JT8DoaShK9ZJIpUs1uMLbb%2FXIwNlKogECJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igxz17sc9JoBgsY4h14q3ANe%2BhcABNQmVQeMCwkEm2vcrJRQk25pUwOQDfjw83d84oG52hpqspfQZlM82TUyriESoUE7O%2BFnZgsI4WVf0z0QV3ppyg6ZzbqZXcJas%2B7eQ9czQfQSGxO6w3IznLCJbhAYVvayWpVeD90rUq6MBcRUao6rfPJLr9kdiFGmxwhCTtDVsl5jk2FSF1ldAA91RfFNl4%2FSPvm7Be6TnmiaS50tgLnnro515lHbw6M8%2FKp2s%2FSJW%2F84nxvVVzKDEW98%2Bc7RjVPFNu9M8Vuo0gGpX6gimNrqUMeVulqWm8WXoYLjxBWlqbpl5thRJjhlEttZ4W4I96WDfk78ccjk5KIa%2FrxmikqI76kay3T7H%2B0GMxKxvwtJxmbSXKQuzP5YBan54PWgqyKa4JyqvDsFYmSWQA0rCkjPOUh3X0%2FcGWdwLyDzpn0ATJB3nQcifXX6DO3bR%2BIq5Srxgggz0tGaJN%2FJrqRKiggncosa%2FPItwVgQ5%2BmdVvhWATSH%2FUJP4uMrms5x%2Bwwigo8%2BTVm7Wl4suCwWiayb%2Fw3dTeKPXewtII0H5s2mXcjjw3yCUF2829ans7vQS6BBZMhW%2F0%2FrO0CDW6XCeSqLCS%2BMNSgBJDqCxDuBoRtTbQ6WIxKzd3C37uUmhTDhvqC9BjqkAfF2A5StHhC2nzYDp50f7CjOJee1rG%2FRCZ%2BOOAcSP0KnfjOxkssEiEoQ6CnGJH%2FRn59Fw3zfWDa8EmUgsT0O7xsUEV6Z4bGRDVIStYEUJgOQT0hUPswMYt2kl3l2%2BvFDHo9aPrszCSx00p8IaofJ62mhiL8Iep4brn8OnS6NSKEzkwF8poh%2F7N%2F2d5cGm%2Fu%2FAmTnOGvbc5FmmPbvTyi7X86Nz3x4&X-Amz-Signature=98bfc1b0eb32f5c9f3c8b958e7a86f4ccb908e20d2d5beb79391086813ab624c&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666QEKXMNB%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T032721Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCyb87aVaMFdj3%2BCPonWySWvrXeXO7yWQUnxahixdJK3QIhAIsKTaTcKElDxc89JT8DoaShK9ZJIpUs1uMLbb%2FXIwNlKogECJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igxz17sc9JoBgsY4h14q3ANe%2BhcABNQmVQeMCwkEm2vcrJRQk25pUwOQDfjw83d84oG52hpqspfQZlM82TUyriESoUE7O%2BFnZgsI4WVf0z0QV3ppyg6ZzbqZXcJas%2B7eQ9czQfQSGxO6w3IznLCJbhAYVvayWpVeD90rUq6MBcRUao6rfPJLr9kdiFGmxwhCTtDVsl5jk2FSF1ldAA91RfFNl4%2FSPvm7Be6TnmiaS50tgLnnro515lHbw6M8%2FKp2s%2FSJW%2F84nxvVVzKDEW98%2Bc7RjVPFNu9M8Vuo0gGpX6gimNrqUMeVulqWm8WXoYLjxBWlqbpl5thRJjhlEttZ4W4I96WDfk78ccjk5KIa%2FrxmikqI76kay3T7H%2B0GMxKxvwtJxmbSXKQuzP5YBan54PWgqyKa4JyqvDsFYmSWQA0rCkjPOUh3X0%2FcGWdwLyDzpn0ATJB3nQcifXX6DO3bR%2BIq5Srxgggz0tGaJN%2FJrqRKiggncosa%2FPItwVgQ5%2BmdVvhWATSH%2FUJP4uMrms5x%2Bwwigo8%2BTVm7Wl4suCwWiayb%2Fw3dTeKPXewtII0H5s2mXcjjw3yCUF2829ans7vQS6BBZMhW%2F0%2FrO0CDW6XCeSqLCS%2BMNSgBJDqCxDuBoRtTbQ6WIxKzd3C37uUmhTDhvqC9BjqkAfF2A5StHhC2nzYDp50f7CjOJee1rG%2FRCZ%2BOOAcSP0KnfjOxkssEiEoQ6CnGJH%2FRn59Fw3zfWDa8EmUgsT0O7xsUEV6Z4bGRDVIStYEUJgOQT0hUPswMYt2kl3l2%2BvFDHo9aPrszCSx00p8IaofJ62mhiL8Iep4brn8OnS6NSKEzkwF8poh%2F7N%2F2d5cGm%2Fu%2FAmTnOGvbc5FmmPbvTyi7X86Nz3x4&X-Amz-Signature=358abf1a5b908ab62ea868139cbbd8706e7e84d18236501ae8254c574f22a79a&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666QEKXMNB%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T032721Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCyb87aVaMFdj3%2BCPonWySWvrXeXO7yWQUnxahixdJK3QIhAIsKTaTcKElDxc89JT8DoaShK9ZJIpUs1uMLbb%2FXIwNlKogECJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igxz17sc9JoBgsY4h14q3ANe%2BhcABNQmVQeMCwkEm2vcrJRQk25pUwOQDfjw83d84oG52hpqspfQZlM82TUyriESoUE7O%2BFnZgsI4WVf0z0QV3ppyg6ZzbqZXcJas%2B7eQ9czQfQSGxO6w3IznLCJbhAYVvayWpVeD90rUq6MBcRUao6rfPJLr9kdiFGmxwhCTtDVsl5jk2FSF1ldAA91RfFNl4%2FSPvm7Be6TnmiaS50tgLnnro515lHbw6M8%2FKp2s%2FSJW%2F84nxvVVzKDEW98%2Bc7RjVPFNu9M8Vuo0gGpX6gimNrqUMeVulqWm8WXoYLjxBWlqbpl5thRJjhlEttZ4W4I96WDfk78ccjk5KIa%2FrxmikqI76kay3T7H%2B0GMxKxvwtJxmbSXKQuzP5YBan54PWgqyKa4JyqvDsFYmSWQA0rCkjPOUh3X0%2FcGWdwLyDzpn0ATJB3nQcifXX6DO3bR%2BIq5Srxgggz0tGaJN%2FJrqRKiggncosa%2FPItwVgQ5%2BmdVvhWATSH%2FUJP4uMrms5x%2Bwwigo8%2BTVm7Wl4suCwWiayb%2Fw3dTeKPXewtII0H5s2mXcjjw3yCUF2829ans7vQS6BBZMhW%2F0%2FrO0CDW6XCeSqLCS%2BMNSgBJDqCxDuBoRtTbQ6WIxKzd3C37uUmhTDhvqC9BjqkAfF2A5StHhC2nzYDp50f7CjOJee1rG%2FRCZ%2BOOAcSP0KnfjOxkssEiEoQ6CnGJH%2FRn59Fw3zfWDa8EmUgsT0O7xsUEV6Z4bGRDVIStYEUJgOQT0hUPswMYt2kl3l2%2BvFDHo9aPrszCSx00p8IaofJ62mhiL8Iep4brn8OnS6NSKEzkwF8poh%2F7N%2F2d5cGm%2Fu%2FAmTnOGvbc5FmmPbvTyi7X86Nz3x4&X-Amz-Signature=b65a8cab2bebe7bd5c7c6b29637880d530bdcc6909dc90dc2efcef43191e77d5&X-Amz-SignedHeaders=host&x-id=GetObject)


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

