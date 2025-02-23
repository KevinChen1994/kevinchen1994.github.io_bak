---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4665DXEPZQ5%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250223T191755Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEOD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDz4VsyZYVhFGK9ypG\
  w7FBYRHSwxusiC7R%2BBHREmOOsZwIgRA33Z0PzbJrq2C%2BHIf%2FWD6i3VHW4K1XcS5B5iLvMqT\
  4q%2FwMIGRAAGgw2Mzc0MjMxODM4MDUiDIJE375OXG2sbckdNyrcA5wkXt1iYkVVDKaVn8mV5l1Zt\
  NfcUj3KXKy2vFTZcKZsLtwdd97cNGhySKYG5m9SZCXd0rNdPsXkFN6o6VZiAoNESucoGEcqLeOalp\
  cQvUbze5DcpNUWioWLlp85x0SH1%2BBSPLUD3md7%2FVfCHE8JrWQPr6X3F%2BxuSNiTz1Phjtflq\
  SjL7HxUN14JxFTjey1wIDrTkj4pk0TxL7WkimABhXcZ5u%2Fb8puCPQw73PeeoGc%2Fe%2BiUiTE1\
  tVakVvZyJ2poju7cJrmw3uIbFu0ZA%2F4YU200hZCD%2BRkYmvix3HrXmwZ9dR%2Bncrx24G5I7k%\
  2B1uLyYd3Obi6iuRzLRrkEwqiTQUcV8DkGjEB8olGkv2zTktSXiL%2BGI2wiR2%2F%2BFKhw1jSkp\
  l9WOJSwBTcMlpElad4WynidsFNW57%2BtXMzrrsVk3eus7%2BSYdC9FdDzEts4LkB49rmxNLvOeam\
  68PCJF6SeizTqnehyYqkw2nyGKn9D5KFjOiG0wd9z81rQEqlW4b2nKf7z4BNW4QqIUPEIbvUfWqM7\
  fPVx1Mju%2BboLq8tVUWa5HExbpPGUOFmhFWHgu6WlXbGL87TP%2FXa4r5iTXcgrsEcxlrQJyTwbM\
  LcNkHUDDB3%2FDi1QHhia%2FfQ%2B4lG%2B6ZMMaL7b0GOqUByUHZMgGAqQj1SKnPND7ApoD9RffE\
  mIV17QE2BHw2lz48cidjHwGAK1EOuCG%2FXP4jQVR2QqmTl27Ir2fe%2FMby2rLM2Xl8sHtcHaOQQ\
  AsNkl2ykoUQ9LHeO6F09RgPWIsuFo95cNuPLP58Q00vsPrNyyELWQi6bGgTwQ%2B5QoW0Eods7YoX\
  lqB5kLv4YPFtQHfL8JRRlKRYRhI1UrNy7VcA%2B1fiUtI4&X-Amz-Signature=8d1026fa8dfa9e\
  9795c06a00e26c30150bf3e40d358e78b2918da85232f77f25&X-Amz-SignedHeaders=host&x\
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
        redential=ASIAZI2LB46625OH7DDD%2F20250223%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250223T191647Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEOD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CICBxe%2Bpc3TK80P9QDzGpwWxfy6VIuFoZ0iPhDZL0DcKNAiEAjN1Bcm2YqSdxnKcIIyYo\
        McqsveQqEnz4yYEGsJx7STUq%2FwMIGRAAGgw2Mzc0MjMxODM4MDUiDM8tud%2Fv3Cyo2VJ\
        RnircA5jVKXiTeuFfsAJ%2Ba5AUuKGmPizJ86t%2Bi%2B8Vn9vNUwe1UgHbYkQZXATor73X\
        4N%2BBs5w3z3KJWw06DLE91gnDVdhqlquxk%2FllmnOPcuaupdh0KtHw62Mi4vhW%2FbSiO\
        nnxd6zjEzVfAJyFaRIXzD43Sh%2BLEF%2FeYQyp9hHr9E7C6WPEJODjPRdM5dMEdzDu6d7Y\
        GPMMjxnRk2quONHumug5H9r%2Beh0i4OnHzAV1ep6%2BO0XU3hnop4F9VR6id2MAtUYFowY\
        %2FVk1o%2BNchsadgtjoX8dvAv0C%2FcbwxhKPcAm%2FX9sdyUYtnwXgW%2FB3IxlOA2Cg9\
        Zd70FuSZ8Y9V%2B52sDXpkXRn0GUHeAROewfv3OjBxS%2BbVSDEV4LHsWZubrW%2F2W%2Ff\
        sQhP1tbefkv5tFv8ABAKds7vNCqcm4%2FUxQlfLJLmhsunC8KFcvNgy4WG%2BNHWlv0YkZS\
        8Znee9SHDC4Y5y6NPXr8MyHFPHjdrrCNwRjQSIoW%2FJBaeVdD9jGNN1mfouCA55t4dBB59\
        cKL%2BVpKRsJBpcQrf8sXGHIsNln%2FjuCStOu3kN9S3FDYN2zcFoCUF3MJ0xwKmEPPKKRZ\
        E15RMwQ7kG5jQ117PaeZHP6gUUj3UAb79t7ZEzt8OvA1VDS7fBMJiL7b0GOqUBCwm%2FCYE\
        %2FnI3UTTDdsN9an56WKFsFiRTZ4aA4LuLUt0QNb5RwKw%2FIh2Aq7qO349WvS%2B7%2Bo3\
        TmwEJ5tS3hwkjHyVzdDxVS6ORDcVJgIJP49hJnA3eumwd31Gk6HMnsMSsXkC3Uaae%2Bhxh\
        M%2BHGiv3m7xYpHBc3h6rhvXuTfeGoFAK%2Fq8RltwRtEpuY6L7qkujL%2FBkhZzWXO6iye\
        LeXlU56pzQKUsMZr&X-Amz-Signature=ac38b73b6379e1b019ca4453899f199925d0e2\
        f4f2645741ab664337c4979884&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-23T20:16:47.885Z"
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
UPDATE_TIME: "2025-02-23T19:18:00.548Z"
EXPIRY_TIME: "2025-02-23T20:17:54.034Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U5TEU6DB%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T191754Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD3GATcPBUVEDsAFi2Lg1CscHg%2FqgFLjgf%2F2Qx1eIKSMAIhAL1cQWStTzmpcytRy9ke11qncuAaIm37d09tg6uSvqXsKv8DCBkQABoMNjM3NDIzMTgzODA1IgyqFxPLnaqniMBfnuQq3ANJMJ34yBFyLkcUtkPUiYaAzRxozHwouk8d%2B5ZpBzrmagjDP6tfrCXpyvdU2pFvTUe%2Fmw5n9uOWt71%2BSA%2FZFEoDEOYD9jgNBDELdNIak0pblf%2FdWUiACzVOl2XvOyCPPW4ecSpexNUC0hzD%2BsBVOW3s1apD5Ub0Qok4tpftWzhGTeNtr8J%2BTnbUZ24eGd4zyw5meeTOzfnH8tWettxTXSOexyl9WA6mYawxPUitIDSWZ%2FJ89ykg%2Fzz4u5hYfJpQ38FciH%2Fi9VnftxF791xPbzzaQJnwR%2F4p3HxfaNnm%2F7GsNj5dbkk3c7ofD2LNXK9jKcXVC3Y7VnGR82UuAIaapcOcm9DzZrT1j9xfDVeBe%2Br634cc%2BiSPEcgADmGOLSoIPGqE6Fm1fIgAtxoxvC7Ir2rkQNYGyVygAQKzj8U1vteBo%2B%2BAFoQLAWtbAlK4x2dtbiwVelQhh91lzXimYH8qLBoxLQD1r9bhvTFAH9UnoDPvrJB9nq9jWGnweRRHK%2Bwqj8ADq1r9ial5yS0G60tjsK6U3Zm5cPsVI8z%2BR1Mx%2FEQZToIGFXdH8qKR4sYqU%2Fw4yeCmDqm7kKlMrCIWbyX8Rdb67AN5us0Tv8GOTUuBDAPzEaAbJGKL%2B%2B12eJVM2TDagO29BjqkAYPPdAAKsv3lEhI2ngzeinax2snFQa1lL0fo%2BSJJSW94q33KG7NgI9cy0Ms5F%2FMO8xVztMAShJJI1qJXKKNXy0zJo8IuEIBWybUkL6HpTTUOisnPnVj83P4UhC0180zLmD1hHujjxK7M56n2XpkG2VqO3Fc4eAb17wq%2FdEYo0T5%2Fy8k8aXnw87SKsO%2FAIqKS9h0XYcVScmSoJRFL8bn3CPGjh1op&X-Amz-Signature=e5a5fc245c9dbc7a777634b923591274892f3a2f98d82ad67fde7585e8f5ba09&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U5TEU6DB%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T191754Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD3GATcPBUVEDsAFi2Lg1CscHg%2FqgFLjgf%2F2Qx1eIKSMAIhAL1cQWStTzmpcytRy9ke11qncuAaIm37d09tg6uSvqXsKv8DCBkQABoMNjM3NDIzMTgzODA1IgyqFxPLnaqniMBfnuQq3ANJMJ34yBFyLkcUtkPUiYaAzRxozHwouk8d%2B5ZpBzrmagjDP6tfrCXpyvdU2pFvTUe%2Fmw5n9uOWt71%2BSA%2FZFEoDEOYD9jgNBDELdNIak0pblf%2FdWUiACzVOl2XvOyCPPW4ecSpexNUC0hzD%2BsBVOW3s1apD5Ub0Qok4tpftWzhGTeNtr8J%2BTnbUZ24eGd4zyw5meeTOzfnH8tWettxTXSOexyl9WA6mYawxPUitIDSWZ%2FJ89ykg%2Fzz4u5hYfJpQ38FciH%2Fi9VnftxF791xPbzzaQJnwR%2F4p3HxfaNnm%2F7GsNj5dbkk3c7ofD2LNXK9jKcXVC3Y7VnGR82UuAIaapcOcm9DzZrT1j9xfDVeBe%2Br634cc%2BiSPEcgADmGOLSoIPGqE6Fm1fIgAtxoxvC7Ir2rkQNYGyVygAQKzj8U1vteBo%2B%2BAFoQLAWtbAlK4x2dtbiwVelQhh91lzXimYH8qLBoxLQD1r9bhvTFAH9UnoDPvrJB9nq9jWGnweRRHK%2Bwqj8ADq1r9ial5yS0G60tjsK6U3Zm5cPsVI8z%2BR1Mx%2FEQZToIGFXdH8qKR4sYqU%2Fw4yeCmDqm7kKlMrCIWbyX8Rdb67AN5us0Tv8GOTUuBDAPzEaAbJGKL%2B%2B12eJVM2TDagO29BjqkAYPPdAAKsv3lEhI2ngzeinax2snFQa1lL0fo%2BSJJSW94q33KG7NgI9cy0Ms5F%2FMO8xVztMAShJJI1qJXKKNXy0zJo8IuEIBWybUkL6HpTTUOisnPnVj83P4UhC0180zLmD1hHujjxK7M56n2XpkG2VqO3Fc4eAb17wq%2FdEYo0T5%2Fy8k8aXnw87SKsO%2FAIqKS9h0XYcVScmSoJRFL8bn3CPGjh1op&X-Amz-Signature=423facb6c79a627e2e560c6479a770ef52f8bdc93d08bb3e8434b63df592347d&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U5TEU6DB%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T191754Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD3GATcPBUVEDsAFi2Lg1CscHg%2FqgFLjgf%2F2Qx1eIKSMAIhAL1cQWStTzmpcytRy9ke11qncuAaIm37d09tg6uSvqXsKv8DCBkQABoMNjM3NDIzMTgzODA1IgyqFxPLnaqniMBfnuQq3ANJMJ34yBFyLkcUtkPUiYaAzRxozHwouk8d%2B5ZpBzrmagjDP6tfrCXpyvdU2pFvTUe%2Fmw5n9uOWt71%2BSA%2FZFEoDEOYD9jgNBDELdNIak0pblf%2FdWUiACzVOl2XvOyCPPW4ecSpexNUC0hzD%2BsBVOW3s1apD5Ub0Qok4tpftWzhGTeNtr8J%2BTnbUZ24eGd4zyw5meeTOzfnH8tWettxTXSOexyl9WA6mYawxPUitIDSWZ%2FJ89ykg%2Fzz4u5hYfJpQ38FciH%2Fi9VnftxF791xPbzzaQJnwR%2F4p3HxfaNnm%2F7GsNj5dbkk3c7ofD2LNXK9jKcXVC3Y7VnGR82UuAIaapcOcm9DzZrT1j9xfDVeBe%2Br634cc%2BiSPEcgADmGOLSoIPGqE6Fm1fIgAtxoxvC7Ir2rkQNYGyVygAQKzj8U1vteBo%2B%2BAFoQLAWtbAlK4x2dtbiwVelQhh91lzXimYH8qLBoxLQD1r9bhvTFAH9UnoDPvrJB9nq9jWGnweRRHK%2Bwqj8ADq1r9ial5yS0G60tjsK6U3Zm5cPsVI8z%2BR1Mx%2FEQZToIGFXdH8qKR4sYqU%2Fw4yeCmDqm7kKlMrCIWbyX8Rdb67AN5us0Tv8GOTUuBDAPzEaAbJGKL%2B%2B12eJVM2TDagO29BjqkAYPPdAAKsv3lEhI2ngzeinax2snFQa1lL0fo%2BSJJSW94q33KG7NgI9cy0Ms5F%2FMO8xVztMAShJJI1qJXKKNXy0zJo8IuEIBWybUkL6HpTTUOisnPnVj83P4UhC0180zLmD1hHujjxK7M56n2XpkG2VqO3Fc4eAb17wq%2FdEYo0T5%2Fy8k8aXnw87SKsO%2FAIqKS9h0XYcVScmSoJRFL8bn3CPGjh1op&X-Amz-Signature=c953157e1a8108bbce0c5387d9ee85b3a33584e9599b7ae6fd2affc1074d54d2&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U5TEU6DB%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T191754Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD3GATcPBUVEDsAFi2Lg1CscHg%2FqgFLjgf%2F2Qx1eIKSMAIhAL1cQWStTzmpcytRy9ke11qncuAaIm37d09tg6uSvqXsKv8DCBkQABoMNjM3NDIzMTgzODA1IgyqFxPLnaqniMBfnuQq3ANJMJ34yBFyLkcUtkPUiYaAzRxozHwouk8d%2B5ZpBzrmagjDP6tfrCXpyvdU2pFvTUe%2Fmw5n9uOWt71%2BSA%2FZFEoDEOYD9jgNBDELdNIak0pblf%2FdWUiACzVOl2XvOyCPPW4ecSpexNUC0hzD%2BsBVOW3s1apD5Ub0Qok4tpftWzhGTeNtr8J%2BTnbUZ24eGd4zyw5meeTOzfnH8tWettxTXSOexyl9WA6mYawxPUitIDSWZ%2FJ89ykg%2Fzz4u5hYfJpQ38FciH%2Fi9VnftxF791xPbzzaQJnwR%2F4p3HxfaNnm%2F7GsNj5dbkk3c7ofD2LNXK9jKcXVC3Y7VnGR82UuAIaapcOcm9DzZrT1j9xfDVeBe%2Br634cc%2BiSPEcgADmGOLSoIPGqE6Fm1fIgAtxoxvC7Ir2rkQNYGyVygAQKzj8U1vteBo%2B%2BAFoQLAWtbAlK4x2dtbiwVelQhh91lzXimYH8qLBoxLQD1r9bhvTFAH9UnoDPvrJB9nq9jWGnweRRHK%2Bwqj8ADq1r9ial5yS0G60tjsK6U3Zm5cPsVI8z%2BR1Mx%2FEQZToIGFXdH8qKR4sYqU%2Fw4yeCmDqm7kKlMrCIWbyX8Rdb67AN5us0Tv8GOTUuBDAPzEaAbJGKL%2B%2B12eJVM2TDagO29BjqkAYPPdAAKsv3lEhI2ngzeinax2snFQa1lL0fo%2BSJJSW94q33KG7NgI9cy0Ms5F%2FMO8xVztMAShJJI1qJXKKNXy0zJo8IuEIBWybUkL6HpTTUOisnPnVj83P4UhC0180zLmD1hHujjxK7M56n2XpkG2VqO3Fc4eAb17wq%2FdEYo0T5%2Fy8k8aXnw87SKsO%2FAIqKS9h0XYcVScmSoJRFL8bn3CPGjh1op&X-Amz-Signature=17e3b0e459da7c2fc28377962d2e17638db20f599eb26e041d52526093bd7be8&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U5TEU6DB%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T191754Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD3GATcPBUVEDsAFi2Lg1CscHg%2FqgFLjgf%2F2Qx1eIKSMAIhAL1cQWStTzmpcytRy9ke11qncuAaIm37d09tg6uSvqXsKv8DCBkQABoMNjM3NDIzMTgzODA1IgyqFxPLnaqniMBfnuQq3ANJMJ34yBFyLkcUtkPUiYaAzRxozHwouk8d%2B5ZpBzrmagjDP6tfrCXpyvdU2pFvTUe%2Fmw5n9uOWt71%2BSA%2FZFEoDEOYD9jgNBDELdNIak0pblf%2FdWUiACzVOl2XvOyCPPW4ecSpexNUC0hzD%2BsBVOW3s1apD5Ub0Qok4tpftWzhGTeNtr8J%2BTnbUZ24eGd4zyw5meeTOzfnH8tWettxTXSOexyl9WA6mYawxPUitIDSWZ%2FJ89ykg%2Fzz4u5hYfJpQ38FciH%2Fi9VnftxF791xPbzzaQJnwR%2F4p3HxfaNnm%2F7GsNj5dbkk3c7ofD2LNXK9jKcXVC3Y7VnGR82UuAIaapcOcm9DzZrT1j9xfDVeBe%2Br634cc%2BiSPEcgADmGOLSoIPGqE6Fm1fIgAtxoxvC7Ir2rkQNYGyVygAQKzj8U1vteBo%2B%2BAFoQLAWtbAlK4x2dtbiwVelQhh91lzXimYH8qLBoxLQD1r9bhvTFAH9UnoDPvrJB9nq9jWGnweRRHK%2Bwqj8ADq1r9ial5yS0G60tjsK6U3Zm5cPsVI8z%2BR1Mx%2FEQZToIGFXdH8qKR4sYqU%2Fw4yeCmDqm7kKlMrCIWbyX8Rdb67AN5us0Tv8GOTUuBDAPzEaAbJGKL%2B%2B12eJVM2TDagO29BjqkAYPPdAAKsv3lEhI2ngzeinax2snFQa1lL0fo%2BSJJSW94q33KG7NgI9cy0Ms5F%2FMO8xVztMAShJJI1qJXKKNXy0zJo8IuEIBWybUkL6HpTTUOisnPnVj83P4UhC0180zLmD1hHujjxK7M56n2XpkG2VqO3Fc4eAb17wq%2FdEYo0T5%2Fy8k8aXnw87SKsO%2FAIqKS9h0XYcVScmSoJRFL8bn3CPGjh1op&X-Amz-Signature=68c21735f328940325837dd08e514a37f59c09ade1759189b333b50b3294f351&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VVMI5KLI%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T191754Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQC27sDyhJJiWcHtX3210emP15N8hozpkY6P9oyQH1DzzQIgHapBE3nZzCgEuRDcnbO1NIlNACkjDY4va53aBJVHi%2B0q%2FwMIGRAAGgw2Mzc0MjMxODM4MDUiDDGgD51vb0LWHh7rwyrcA4HfAreH%2F8yEkYCnuIGyAmA0G7yBocvKWGT91c12e54qbZtjHo1v1blFP4gic3Jb1vc3qUS5SwomW6UTSkoiYDLtg1ErtUjoFXqZX0uTiN%2BGg8MZ%2BLg1LYuacQF%2BKEeiaTuqov2d%2BiCBYOyTjLeY3Csfq3s6286E8tIUh1FToz4wbDZLQn91FxJReq3uTutl8zkKwP%2FtvdOj4UepAPQvsTF%2Fcw3w8Ife9VhlxZUXN1mleQmdnw8%2FWuaNIihmnFuUr52jHSPyfBuPprErEScmuv3p4JW6bwemamW9lOtqsBPmxqUbrt7TkfWlBIL5F9aumWTehopY4H4WRR0h3hMfA5G9FHXLBjepdMSotWQNg49gdu%2Bgmj3xyFi1bPncPbrf6yNJWnY8cbGlCajgZhcgl1lOTF2HA2pMYD5e2nuVjCsaZTBGc3dS%2B%2BhZvmB%2BB5vIu46ZWg%2FreHpzYyVuzL%2BN2jJ06aXUAOZK%2F61ZL1mJLdtIDj8DwEo7gn%2BO9WJFrrz7hztjYz9%2FGevQglkWNQDDFNxvbg9z3GzBm8ByAUs02PTcKwLXwWSK%2B79NIaffV5CPxhBY64Wa2VHPSf9atAnRSa%2FwHkd0v8Iy9PtGqqWAgDNs2TJyNUCeOADZq2CqMNqA7b0GOqUBvjCEu0xlAxUAtNd0WC3P1sSMgMni2hzAhYGk6uwF43roBCzdyZCasIOyk34MTuSBClt0zzohvcbXZeLHeheE8FduV5S%2BWWP0gt4dCF0rKDvdbLfMHPLE0M8Cx6wldcunGF4HxqQzz%2BjTNRNHPkdS9pz0VOPCrrw3zDKqRiBCNRU3kkQWkkisKAAw2I8muHuV3nrBEdn8tfxdi0HbUMnd7v6h1qR0&X-Amz-Signature=6ce4c6800b2c15452f9fa03ef610e655321dd27cefcb6b02a96d8e7c6fe0a4b1&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XF4Y7JW7%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T191755Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDTcuyN6qqiiJHC7n0H71czhElYut71KiRslaSCrdtuAAIgHPFuxXFYbL0%2FePU6YxXMAioEQ0JVmd9%2BSBivxRHxzWYq%2FwMIGRAAGgw2Mzc0MjMxODM4MDUiDDNy0d%2B%2FAUmWbGn6qyrcA%2B3%2BnEYbmdQLHGqbrKVaMjGA3yiGv6WqRYFNkudYnVxnm%2BScqUyVyXKYR3eWxZmtnCfLpoTrr5JpfT8FJIZbiGJtvurusr42s22pKHbDzCpt0mzFcI94THH3maXyqL2NZJWNudUxPWMhU2AjEOc1cYPpPOFFWqJiOHtbRRyxCYbtkB%2FYEEz0WXQJOfaPKBzb2snA9DHKop83K48QWNt1y8W3tS5YDjREGXUTqpVw2qvxdoHByB1pd0LTweJVTv9KBPcvuCKDUyc1s%2F%2BHaotmoEtjYiJPCNmFE7AkWJLhMjugFSia30htgbWOEZVF6RQ7hXM33RZ2RbcPajrAH7s3ndoIOQgpS8Q4FQTfZjqbd12sL9etE3cxTxANt2bG%2FSIid7MSFx1XWQtpgsF4DatRrtJFYmk2WQSZA9ewQJ%2FpbRMsFQ735b1kMdLjheURqzV61IjCQHskS3x%2BinqWebVa2k%2FDIppL0yDzmMLy%2FCiJILTdmnQ0reF3ITlkjIsZFGxx30ScogqMKG20GZcuIQjPhqSpoXmB8Wb%2Ffkj6Pf3OFl89BTEKeJ3gE%2Fy3%2FfQMMLDZc5qnXDSlIoHdhmV6DPdOzyNOeZnr4dl%2Fo0QyNdpgPLgB9yls97kiiQ8DTxDLMJSM7b0GOqUBVpGiXIO6boB17Qr%2FbKHcvQsKcdEBaC9AsVw9k0s%2F2V0IQ414WBiyR3Ozqr5PJiAWWDCOKeMX5qJb7sPYx%2FRrh9pkcBpLDigB%2B%2B%2BzGnhb2qV0JivNLemMaS4bW%2FcsFMr1Aj4RUUn%2FVrGFjROz3v0JBJf%2FG1cKA3Y8ddNyZ7Pek%2F15Mut%2FklnqJCYJkcuTJNx0TAfMY1FIl%2BkEaAhsEVQWvf9N%2Flwt&X-Amz-Signature=169f26b2c4063d5f84bd4a6d71fe8052e7865c778ff0fa2d404b64ade232f51e&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U5TEU6DB%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T191754Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD3GATcPBUVEDsAFi2Lg1CscHg%2FqgFLjgf%2F2Qx1eIKSMAIhAL1cQWStTzmpcytRy9ke11qncuAaIm37d09tg6uSvqXsKv8DCBkQABoMNjM3NDIzMTgzODA1IgyqFxPLnaqniMBfnuQq3ANJMJ34yBFyLkcUtkPUiYaAzRxozHwouk8d%2B5ZpBzrmagjDP6tfrCXpyvdU2pFvTUe%2Fmw5n9uOWt71%2BSA%2FZFEoDEOYD9jgNBDELdNIak0pblf%2FdWUiACzVOl2XvOyCPPW4ecSpexNUC0hzD%2BsBVOW3s1apD5Ub0Qok4tpftWzhGTeNtr8J%2BTnbUZ24eGd4zyw5meeTOzfnH8tWettxTXSOexyl9WA6mYawxPUitIDSWZ%2FJ89ykg%2Fzz4u5hYfJpQ38FciH%2Fi9VnftxF791xPbzzaQJnwR%2F4p3HxfaNnm%2F7GsNj5dbkk3c7ofD2LNXK9jKcXVC3Y7VnGR82UuAIaapcOcm9DzZrT1j9xfDVeBe%2Br634cc%2BiSPEcgADmGOLSoIPGqE6Fm1fIgAtxoxvC7Ir2rkQNYGyVygAQKzj8U1vteBo%2B%2BAFoQLAWtbAlK4x2dtbiwVelQhh91lzXimYH8qLBoxLQD1r9bhvTFAH9UnoDPvrJB9nq9jWGnweRRHK%2Bwqj8ADq1r9ial5yS0G60tjsK6U3Zm5cPsVI8z%2BR1Mx%2FEQZToIGFXdH8qKR4sYqU%2Fw4yeCmDqm7kKlMrCIWbyX8Rdb67AN5us0Tv8GOTUuBDAPzEaAbJGKL%2B%2B12eJVM2TDagO29BjqkAYPPdAAKsv3lEhI2ngzeinax2snFQa1lL0fo%2BSJJSW94q33KG7NgI9cy0Ms5F%2FMO8xVztMAShJJI1qJXKKNXy0zJo8IuEIBWybUkL6HpTTUOisnPnVj83P4UhC0180zLmD1hHujjxK7M56n2XpkG2VqO3Fc4eAb17wq%2FdEYo0T5%2Fy8k8aXnw87SKsO%2FAIqKS9h0XYcVScmSoJRFL8bn3CPGjh1op&X-Amz-Signature=b565bc643f8bb8803efebf4ac17d11a501ce1b992088fe9980f84d635197c92a&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U5TEU6DB%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T191754Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD3GATcPBUVEDsAFi2Lg1CscHg%2FqgFLjgf%2F2Qx1eIKSMAIhAL1cQWStTzmpcytRy9ke11qncuAaIm37d09tg6uSvqXsKv8DCBkQABoMNjM3NDIzMTgzODA1IgyqFxPLnaqniMBfnuQq3ANJMJ34yBFyLkcUtkPUiYaAzRxozHwouk8d%2B5ZpBzrmagjDP6tfrCXpyvdU2pFvTUe%2Fmw5n9uOWt71%2BSA%2FZFEoDEOYD9jgNBDELdNIak0pblf%2FdWUiACzVOl2XvOyCPPW4ecSpexNUC0hzD%2BsBVOW3s1apD5Ub0Qok4tpftWzhGTeNtr8J%2BTnbUZ24eGd4zyw5meeTOzfnH8tWettxTXSOexyl9WA6mYawxPUitIDSWZ%2FJ89ykg%2Fzz4u5hYfJpQ38FciH%2Fi9VnftxF791xPbzzaQJnwR%2F4p3HxfaNnm%2F7GsNj5dbkk3c7ofD2LNXK9jKcXVC3Y7VnGR82UuAIaapcOcm9DzZrT1j9xfDVeBe%2Br634cc%2BiSPEcgADmGOLSoIPGqE6Fm1fIgAtxoxvC7Ir2rkQNYGyVygAQKzj8U1vteBo%2B%2BAFoQLAWtbAlK4x2dtbiwVelQhh91lzXimYH8qLBoxLQD1r9bhvTFAH9UnoDPvrJB9nq9jWGnweRRHK%2Bwqj8ADq1r9ial5yS0G60tjsK6U3Zm5cPsVI8z%2BR1Mx%2FEQZToIGFXdH8qKR4sYqU%2Fw4yeCmDqm7kKlMrCIWbyX8Rdb67AN5us0Tv8GOTUuBDAPzEaAbJGKL%2B%2B12eJVM2TDagO29BjqkAYPPdAAKsv3lEhI2ngzeinax2snFQa1lL0fo%2BSJJSW94q33KG7NgI9cy0Ms5F%2FMO8xVztMAShJJI1qJXKKNXy0zJo8IuEIBWybUkL6HpTTUOisnPnVj83P4UhC0180zLmD1hHujjxK7M56n2XpkG2VqO3Fc4eAb17wq%2FdEYo0T5%2Fy8k8aXnw87SKsO%2FAIqKS9h0XYcVScmSoJRFL8bn3CPGjh1op&X-Amz-Signature=85b159215b427121796944e11ca6fee28c001ff6c070e24eb92054ce0602a21f&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U5TEU6DB%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T191754Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD3GATcPBUVEDsAFi2Lg1CscHg%2FqgFLjgf%2F2Qx1eIKSMAIhAL1cQWStTzmpcytRy9ke11qncuAaIm37d09tg6uSvqXsKv8DCBkQABoMNjM3NDIzMTgzODA1IgyqFxPLnaqniMBfnuQq3ANJMJ34yBFyLkcUtkPUiYaAzRxozHwouk8d%2B5ZpBzrmagjDP6tfrCXpyvdU2pFvTUe%2Fmw5n9uOWt71%2BSA%2FZFEoDEOYD9jgNBDELdNIak0pblf%2FdWUiACzVOl2XvOyCPPW4ecSpexNUC0hzD%2BsBVOW3s1apD5Ub0Qok4tpftWzhGTeNtr8J%2BTnbUZ24eGd4zyw5meeTOzfnH8tWettxTXSOexyl9WA6mYawxPUitIDSWZ%2FJ89ykg%2Fzz4u5hYfJpQ38FciH%2Fi9VnftxF791xPbzzaQJnwR%2F4p3HxfaNnm%2F7GsNj5dbkk3c7ofD2LNXK9jKcXVC3Y7VnGR82UuAIaapcOcm9DzZrT1j9xfDVeBe%2Br634cc%2BiSPEcgADmGOLSoIPGqE6Fm1fIgAtxoxvC7Ir2rkQNYGyVygAQKzj8U1vteBo%2B%2BAFoQLAWtbAlK4x2dtbiwVelQhh91lzXimYH8qLBoxLQD1r9bhvTFAH9UnoDPvrJB9nq9jWGnweRRHK%2Bwqj8ADq1r9ial5yS0G60tjsK6U3Zm5cPsVI8z%2BR1Mx%2FEQZToIGFXdH8qKR4sYqU%2Fw4yeCmDqm7kKlMrCIWbyX8Rdb67AN5us0Tv8GOTUuBDAPzEaAbJGKL%2B%2B12eJVM2TDagO29BjqkAYPPdAAKsv3lEhI2ngzeinax2snFQa1lL0fo%2BSJJSW94q33KG7NgI9cy0Ms5F%2FMO8xVztMAShJJI1qJXKKNXy0zJo8IuEIBWybUkL6HpTTUOisnPnVj83P4UhC0180zLmD1hHujjxK7M56n2XpkG2VqO3Fc4eAb17wq%2FdEYo0T5%2Fy8k8aXnw87SKsO%2FAIqKS9h0XYcVScmSoJRFL8bn3CPGjh1op&X-Amz-Signature=bee225d095e6548ac02e97b22ac01414a7cfe07bb1bd8f76354ba66375423273&X-Amz-SignedHeaders=host&x-id=GetObject)


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

