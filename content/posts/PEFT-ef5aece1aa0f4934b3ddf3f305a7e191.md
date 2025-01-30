---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466V3ZDJ67S%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250130T102411Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEJr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIEq7hCg1lmBLAPUKXtC\
  Oswk1liIkKuAtJKxO%2FwSYMaUJAiEA2I3frpnv5xNe5xWG1d3GJi7Dst2ku0w4nM4w2C%2FqZWAq\
  iAQIo%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDF%2FYgZ9UsxTCD\
  FfKxSrcAyQfXiFAj1r486OBnzoOY8x79%2BEatjPKl%2BqXKcZLiQdYQ13KtHvFFCuCu4dcE6XprD\
  PVxU02uuP5f8F5JhGYjNX%2Bz613CdUOAjwAzMwk7YqxCo4mowIyf9RNbiH0K1HIvdZYZDXx9gmWB\
  7x0EiyEh7YEcni%2B1WiJguAWXVZPAr15pjTa2dYUjUsI7yiJAvNjs9lA7c%2FENWbdcbLbjI9U9a\
  MqImsQGC4igguA0e4aCGdJCy3HL48zzLfY8xrSpIDc%2BPiVk9uPxVllu1VSTN57zLX0DMaussuoJ\
  tNmr7uFo4figJPOeYsOljJis3LPJS8pwbHCdPyynbu4D0KFxIoE7RM9oiqTSkCo3xIWTm09d%2BMH\
  pmWqxdJTNuslTa0q2GjuoH8PWuJjJZEvyrYd0nss6fw87ynCSqh2h2tI1IrCzrOzmhRCQCaSw85zG\
  vUVEkEf2uPmV7A%2BoYI6%2FR1fPCALug%2BDjsVKHdAr3YWpo6BbcaoiYhPfDCPVHB82KJ2hkJQo\
  YJRIj1icg8CwAhN%2BsJ4nsg0p8xCOZHDnOU2AMpOz%2FPFpYTuEG%2B2lkaPxqFnQDW8d1G0SoNk\
  XDblNxIhuY%2Bv0PB5TyNo1tUETuFexpQd0MSQucJN9OI%2Bj8TBbiNDnMOqM7bwGOqUBzHVJe5Y0\
  SUK1Ydbwgs5HmkLZTl7v9MTHdrn1rfhEMoVxI4vB%2BtQeEMih5bNHQodmiHGyBX9ZBEsMHDqLP%2\
  BQ4sFGngTR%2BLIuS6a%2BJM%2FRbo7BkBg9ZqYv190loNtXqKxyKMCx%2FLgZ%2BopRaLm73XMk4\
  odJjL9g2fJdPXnf9uWY%2BM%2B%2B0kLB3PqiCWdXZE8o0yFy8ctt9tcOPhaPFcJMJj9BFdCtbltr\
  X&X-Amz-Signature=ba9038ccceeb6572ec2495b6d0430f2c357fcccd97014a8a0482976e969\
  d7511&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4667UMK7JRL%2F20250130%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250130T102301Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEJr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIBFMyEs7ure0%2FoKgLg2fSMQWNljIASD9NyYNHxiVt7SmAiEAyDdrFpgUQnx4%2B9NwOM\
        dESP55cDNLEdCeNP6wHDVw3%2FkqiAQIo%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAG\
        gw2Mzc0MjMxODM4MDUiDBNfny0b4gYnumsFmircA%2FCOZ%2FcYVD%2FtnEegz5PaLUGwbp\
        sUS7yuKBUzc1tDmqA6tQHX4zDKi7eTt4HI7z2nIKWHBF%2F6ull3w4NHwxaTtDz75wDTHk0\
        aKh3ky1HzK7yaF3%2B3MXvYgo2HFiugxRJ5PS6lNtRWiLMFqhlkW7hQf%2FeH1twIjqFeV5\
        R25mBSw6POXafeqnRsx2c%2B3Qr4IJdwSfFCBzNz2s0ZDnN9ZxOtVTKolkV6yiOr8d6xy9Y\
        vK8D3tFT2UF%2B1HXmiucP%2FeZMr9HH0YLBZfYv1CdjX%2BTFJ91KGVpf%2BwG9Y7YS0Ym\
        tDyjncJD%2FOZ3a5aG2GFelMbQJ3quZ1uI4qhvAOgTVoISeCSbNUu2ibq6%2FJkaqGGG9yT\
        eYhoPci9%2FHciSGrvvOy933TH7ynw6aL5O9xoYWiRdh3QIY6bcH9xgOJ%2BRyo2TeRi1AF\
        Cg7NhLKiv6pEjXZdCC1F%2FdXJCqVtuyXw6XiRbFApHsy%2BYQvHoCcATCAEA1C2uNCGRt3\
        DcjmqRUtYzpdB%2BNRBRmMip%2BG7OYq3qk2wVY9hV72UWXp0yxNbYN%2BrChu2ouG3WZ6M\
        %2B05RguXEgxzsvhuNaMN6amdjKE3mgATTwoaxjZkcZ96%2F2xnXkZULt4LxximFVULlK3c\
        OOdpAhA3zMOOM7bwGOqUBB3ni0lVMjxs1tTOMoBLJQ9xTALOC%2FVKMTxF0NWXY68oiB95g\
        ryHBpAdorljuhC1MKwake2EYOheMz6FHhXeStb%2FyHxxzvNY7rIjyOSI73Tf1OJvI%2BgQ\
        TDGUpHseI8fz1szYB9sYdTjJqaDvegzyUDWcMJCI4zcuyGbwX3er4OwglWfYGuwwsc7Ap6S\
        9dfKXdtQmFrcCXD%2FFyQb%2BCQHXXoD42DU%2BW&X-Amz-Signature=c068861fd31eb3\
        6bccc67d2bfd2f89507533fea2af7704a9b9a9b8713aee2a2a&X-Amz-SignedHeaders=\
        host&x-id=GetObject"
      expiry_time: "2025-01-30T11:23:01.036Z"
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
UPDATE_TIME: "2025-01-30T10:24:17.932Z"
EXPIRY_TIME: "2025-01-30T11:24:10.116Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SDNLOI4B%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T102410Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD%2Bty%2FdS1wY%2F32a%2FJwcGWzjRXENBne23YYAvzEpQnH5SAIgTdhJ0u%2BAHxVwyYqosn3ZelqbCSaQxNVJj%2BUg3ioVsqcqiAQIo%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHvbHRaeoE64UZoIeCrcA6nglevqFK3R0KcwUjPEMGx%2ByCfE7qK5bTtIJQit8ijiX0nTWVZE6zhx0GYhdjGYX5HAWjA0QkElZtkZRSGsiSw9vHUVW3ui1di2zPPRZ9Rs56EYpAkZV9x6a8XMOg0RYaeBdqtSI%2FbFTKXWhdWp6iDIko2SrgBhy5ILYb8Uts23%2F%2F9JZ2mkxaLUOOno9f6xApEfvNe25LQi3i29IyHsfv8Nm8eglCZg04mIDVeDfolP1A0m04w%2FSBYqZ15alA8quvyFV0J84qsD5Gaw6hzkXaXiE1BlsSWZyUJJpdyLF%2B%2FQsNseVdNOmu3Um8VYl%2B0WEfuaBluVdtWkoRKBNKL8tQpSdyULj0VWy9m5I%2BpZu3vbzHPCEP%2FKqlSMeXtc4PiqBe045x0ZiiZ9jbCMUzhduV3j5DzoJlDTi8wcwRY%2BiGeCRujJ17YZVWBCfTuIR8cymC%2BnyEqPAA%2FamhODl4UJl7z4qLqZF8umzeZoMJWtNUaLwY8aLLngvRvY2tj9dG4k9uE1ByIb32jC1rM0eD60AY11v7KYBsWGRwu3K9rbWN0jjajGmZpRslBerjtCAsTKyni1v8DBCaHDz3LR%2F6L80GMjXRbkQZu%2BIdYwiEegkDqPI06KWKal5QGA9t6CMP2M7bwGOqUBYd5DsAfY44nNdyeEBl9YXJ0zrMaW3e8eMUfm2Gil0ARYoopNhG61%2BPMj30zmPrOj0j%2BVkztUFbq1X7gBYdoM0wIdulMoKi6O6D9a0LJukr1SNX8fD0bjHVFFvZGu4HJhgPlQ0TKuc3Guz5DbuqgeRA%2FSo6GZ0%2FKArWMNQkvlKsPe4TnY3IOGLI1CEHv62IQUmTJzsjvkQewv7layZk2AxZ%2FlIzGW&X-Amz-Signature=e2f19cc48449eca8bd0f9d2b736daea28ddb523564e3550b24077db2a82a72bb&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SDNLOI4B%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T102410Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD%2Bty%2FdS1wY%2F32a%2FJwcGWzjRXENBne23YYAvzEpQnH5SAIgTdhJ0u%2BAHxVwyYqosn3ZelqbCSaQxNVJj%2BUg3ioVsqcqiAQIo%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHvbHRaeoE64UZoIeCrcA6nglevqFK3R0KcwUjPEMGx%2ByCfE7qK5bTtIJQit8ijiX0nTWVZE6zhx0GYhdjGYX5HAWjA0QkElZtkZRSGsiSw9vHUVW3ui1di2zPPRZ9Rs56EYpAkZV9x6a8XMOg0RYaeBdqtSI%2FbFTKXWhdWp6iDIko2SrgBhy5ILYb8Uts23%2F%2F9JZ2mkxaLUOOno9f6xApEfvNe25LQi3i29IyHsfv8Nm8eglCZg04mIDVeDfolP1A0m04w%2FSBYqZ15alA8quvyFV0J84qsD5Gaw6hzkXaXiE1BlsSWZyUJJpdyLF%2B%2FQsNseVdNOmu3Um8VYl%2B0WEfuaBluVdtWkoRKBNKL8tQpSdyULj0VWy9m5I%2BpZu3vbzHPCEP%2FKqlSMeXtc4PiqBe045x0ZiiZ9jbCMUzhduV3j5DzoJlDTi8wcwRY%2BiGeCRujJ17YZVWBCfTuIR8cymC%2BnyEqPAA%2FamhODl4UJl7z4qLqZF8umzeZoMJWtNUaLwY8aLLngvRvY2tj9dG4k9uE1ByIb32jC1rM0eD60AY11v7KYBsWGRwu3K9rbWN0jjajGmZpRslBerjtCAsTKyni1v8DBCaHDz3LR%2F6L80GMjXRbkQZu%2BIdYwiEegkDqPI06KWKal5QGA9t6CMP2M7bwGOqUBYd5DsAfY44nNdyeEBl9YXJ0zrMaW3e8eMUfm2Gil0ARYoopNhG61%2BPMj30zmPrOj0j%2BVkztUFbq1X7gBYdoM0wIdulMoKi6O6D9a0LJukr1SNX8fD0bjHVFFvZGu4HJhgPlQ0TKuc3Guz5DbuqgeRA%2FSo6GZ0%2FKArWMNQkvlKsPe4TnY3IOGLI1CEHv62IQUmTJzsjvkQewv7layZk2AxZ%2FlIzGW&X-Amz-Signature=ee2f98b61bab77d9796ea7404c4b80a6fafdfbdd91901573e749cdbedd843e1e&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SDNLOI4B%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T102410Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD%2Bty%2FdS1wY%2F32a%2FJwcGWzjRXENBne23YYAvzEpQnH5SAIgTdhJ0u%2BAHxVwyYqosn3ZelqbCSaQxNVJj%2BUg3ioVsqcqiAQIo%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHvbHRaeoE64UZoIeCrcA6nglevqFK3R0KcwUjPEMGx%2ByCfE7qK5bTtIJQit8ijiX0nTWVZE6zhx0GYhdjGYX5HAWjA0QkElZtkZRSGsiSw9vHUVW3ui1di2zPPRZ9Rs56EYpAkZV9x6a8XMOg0RYaeBdqtSI%2FbFTKXWhdWp6iDIko2SrgBhy5ILYb8Uts23%2F%2F9JZ2mkxaLUOOno9f6xApEfvNe25LQi3i29IyHsfv8Nm8eglCZg04mIDVeDfolP1A0m04w%2FSBYqZ15alA8quvyFV0J84qsD5Gaw6hzkXaXiE1BlsSWZyUJJpdyLF%2B%2FQsNseVdNOmu3Um8VYl%2B0WEfuaBluVdtWkoRKBNKL8tQpSdyULj0VWy9m5I%2BpZu3vbzHPCEP%2FKqlSMeXtc4PiqBe045x0ZiiZ9jbCMUzhduV3j5DzoJlDTi8wcwRY%2BiGeCRujJ17YZVWBCfTuIR8cymC%2BnyEqPAA%2FamhODl4UJl7z4qLqZF8umzeZoMJWtNUaLwY8aLLngvRvY2tj9dG4k9uE1ByIb32jC1rM0eD60AY11v7KYBsWGRwu3K9rbWN0jjajGmZpRslBerjtCAsTKyni1v8DBCaHDz3LR%2F6L80GMjXRbkQZu%2BIdYwiEegkDqPI06KWKal5QGA9t6CMP2M7bwGOqUBYd5DsAfY44nNdyeEBl9YXJ0zrMaW3e8eMUfm2Gil0ARYoopNhG61%2BPMj30zmPrOj0j%2BVkztUFbq1X7gBYdoM0wIdulMoKi6O6D9a0LJukr1SNX8fD0bjHVFFvZGu4HJhgPlQ0TKuc3Guz5DbuqgeRA%2FSo6GZ0%2FKArWMNQkvlKsPe4TnY3IOGLI1CEHv62IQUmTJzsjvkQewv7layZk2AxZ%2FlIzGW&X-Amz-Signature=8a8cce0e1e1fe3f6b542c8da8fc09167a85d64240b0067533d6ea114ec2117de&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SDNLOI4B%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T102410Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD%2Bty%2FdS1wY%2F32a%2FJwcGWzjRXENBne23YYAvzEpQnH5SAIgTdhJ0u%2BAHxVwyYqosn3ZelqbCSaQxNVJj%2BUg3ioVsqcqiAQIo%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHvbHRaeoE64UZoIeCrcA6nglevqFK3R0KcwUjPEMGx%2ByCfE7qK5bTtIJQit8ijiX0nTWVZE6zhx0GYhdjGYX5HAWjA0QkElZtkZRSGsiSw9vHUVW3ui1di2zPPRZ9Rs56EYpAkZV9x6a8XMOg0RYaeBdqtSI%2FbFTKXWhdWp6iDIko2SrgBhy5ILYb8Uts23%2F%2F9JZ2mkxaLUOOno9f6xApEfvNe25LQi3i29IyHsfv8Nm8eglCZg04mIDVeDfolP1A0m04w%2FSBYqZ15alA8quvyFV0J84qsD5Gaw6hzkXaXiE1BlsSWZyUJJpdyLF%2B%2FQsNseVdNOmu3Um8VYl%2B0WEfuaBluVdtWkoRKBNKL8tQpSdyULj0VWy9m5I%2BpZu3vbzHPCEP%2FKqlSMeXtc4PiqBe045x0ZiiZ9jbCMUzhduV3j5DzoJlDTi8wcwRY%2BiGeCRujJ17YZVWBCfTuIR8cymC%2BnyEqPAA%2FamhODl4UJl7z4qLqZF8umzeZoMJWtNUaLwY8aLLngvRvY2tj9dG4k9uE1ByIb32jC1rM0eD60AY11v7KYBsWGRwu3K9rbWN0jjajGmZpRslBerjtCAsTKyni1v8DBCaHDz3LR%2F6L80GMjXRbkQZu%2BIdYwiEegkDqPI06KWKal5QGA9t6CMP2M7bwGOqUBYd5DsAfY44nNdyeEBl9YXJ0zrMaW3e8eMUfm2Gil0ARYoopNhG61%2BPMj30zmPrOj0j%2BVkztUFbq1X7gBYdoM0wIdulMoKi6O6D9a0LJukr1SNX8fD0bjHVFFvZGu4HJhgPlQ0TKuc3Guz5DbuqgeRA%2FSo6GZ0%2FKArWMNQkvlKsPe4TnY3IOGLI1CEHv62IQUmTJzsjvkQewv7layZk2AxZ%2FlIzGW&X-Amz-Signature=3a14c4efb5a2731dd9877518db25f7eba7a6e5a74d89b92b7a15523fcca346a7&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SDNLOI4B%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T102410Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD%2Bty%2FdS1wY%2F32a%2FJwcGWzjRXENBne23YYAvzEpQnH5SAIgTdhJ0u%2BAHxVwyYqosn3ZelqbCSaQxNVJj%2BUg3ioVsqcqiAQIo%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHvbHRaeoE64UZoIeCrcA6nglevqFK3R0KcwUjPEMGx%2ByCfE7qK5bTtIJQit8ijiX0nTWVZE6zhx0GYhdjGYX5HAWjA0QkElZtkZRSGsiSw9vHUVW3ui1di2zPPRZ9Rs56EYpAkZV9x6a8XMOg0RYaeBdqtSI%2FbFTKXWhdWp6iDIko2SrgBhy5ILYb8Uts23%2F%2F9JZ2mkxaLUOOno9f6xApEfvNe25LQi3i29IyHsfv8Nm8eglCZg04mIDVeDfolP1A0m04w%2FSBYqZ15alA8quvyFV0J84qsD5Gaw6hzkXaXiE1BlsSWZyUJJpdyLF%2B%2FQsNseVdNOmu3Um8VYl%2B0WEfuaBluVdtWkoRKBNKL8tQpSdyULj0VWy9m5I%2BpZu3vbzHPCEP%2FKqlSMeXtc4PiqBe045x0ZiiZ9jbCMUzhduV3j5DzoJlDTi8wcwRY%2BiGeCRujJ17YZVWBCfTuIR8cymC%2BnyEqPAA%2FamhODl4UJl7z4qLqZF8umzeZoMJWtNUaLwY8aLLngvRvY2tj9dG4k9uE1ByIb32jC1rM0eD60AY11v7KYBsWGRwu3K9rbWN0jjajGmZpRslBerjtCAsTKyni1v8DBCaHDz3LR%2F6L80GMjXRbkQZu%2BIdYwiEegkDqPI06KWKal5QGA9t6CMP2M7bwGOqUBYd5DsAfY44nNdyeEBl9YXJ0zrMaW3e8eMUfm2Gil0ARYoopNhG61%2BPMj30zmPrOj0j%2BVkztUFbq1X7gBYdoM0wIdulMoKi6O6D9a0LJukr1SNX8fD0bjHVFFvZGu4HJhgPlQ0TKuc3Guz5DbuqgeRA%2FSo6GZ0%2FKArWMNQkvlKsPe4TnY3IOGLI1CEHv62IQUmTJzsjvkQewv7layZk2AxZ%2FlIzGW&X-Amz-Signature=f7870d5bf77fdee54f474ae9e66e11818eaf74bccadec4914165dba8fe14620e&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QDSQAYIS%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T102410Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCXGBzvQjnev%2FgqfWay1eNeOrEgjsFFatnteC%2F9dvSM4wIhAMaInx3o05ALZrMk9RAuvH8vleOmbwDR%2BKd3WPQYo%2FRVKogECKP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzPmTPt6tzdrqzUHZoq3ANOKWz6rsBc%2F7G8Z615vRfLW3VBsZ%2F21Kt2Mdk%2FFibqtNS1jpW6FutdJJq14jnEZLHFjge%2BQw8E2IFd1vpTnT5JIbOdd9i8NrJ0ww%2FGZFIYzFmwuCVdXaxdkVwRF3SnEd7yXK4MHriVDCyA0RHD12BzzaulFNPXSrd9jA8xqdNgC8Oc5DgLP9XBHSa8mAi5re9B%2FDmZQAboEquPtJpxyCyBlsF4ph%2F5I%2BLPWdjbSHelrW07YUqwgzgUA6ZQdSz4MU3sC8bIf1JdGsjfCjQUSo5nxA3sydWF35TTjjr0N309u6V34GnjMBaTVdfxGYivhGCs1CmBpJmi%2FLxnw9FhTjT5sPHIj1YRbnTtlpvURqCAEINdC5oxV%2BZiQ2sXYM4%2BPjWEK3rofRs2YdMciWsLPIAe9ECe5oIwpg2NTWk2E5WvFwo4XBFMW7ohN7cw3Ja9y7U82InAXZH4wMqwlbeaerTUBKS%2B05v79u9oY4lj7pU5ypGv46JYm%2Fw3FUbT24JH1%2BeUR3rQjs3KVM1qjIFhJ5Vs9KwWyrgI1PB8TO7p0m110VDG4w1rIu8gSNB%2F1fULh5eZAnrOTjTxrWitByX49OwTJ0j5QCFy%2BRTHFXqnLg93KfYFTSUzkjPTlLkFnjDXjO28BjqkAc6b38sk%2BGEPKwrDcpcuodxrEH4AZAPSa5FqogshrUri3dl6z%2By6gy8myRRKStiW5C3537C5Pf0jss0IySuGN4DggVZ28Uf%2FXNEPg6PsmJlfD7k%2B%2BvBLHXifTm3kNvM76ukWGJ2%2FC7d5122iJcjGTuGHI0C%2F9UrvpFoH%2FYZzjRP0haew%2FTZXCpErLszo65m4j7msEgMqwVAq8iZYGYHyd3Wi8xXb&X-Amz-Signature=b9a2022f6ac617058a97d24bbb5ccedfb8399872d0b560bf6be264d6463029aa&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466X4KSBCHG%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T102411Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIFI4F9os3EtIlLwO1avLKEuCCGtp4WMdbqXljrNWgxlnAiBbeLV%2FTI5MXe9Oa1CB018dOjsnWxPzxZSk5fdB4%2BX6JCqIBAij%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM0DkHDE6zyzsCF6iBKtwDLT2PGpsdkjRglUSm%2F531eqby%2F4mo93SLsxhvorWDDlG96QOG4RZ5uN2KpdoykW9%2FL4HqQd4kj7cfuiZqJACN7jnjq7v03OVaDGETNEqXyPSm41wxUH%2F3UzJV3gYR1Ra3HLdvdQF6zuhnOh%2FMQShp6hiNaB8JQsiFdLMGOYya3odg9R9FUq5ar39FW2ufn%2BGBN0X7lWjQePaDiD0k4L8%2BAYifttzm2nZ5TdpbyoaD84%2FTgWFqmF%2FxZty1EGr6rHoqta%2Bq71%2FUZqJRR58aM4owrJhj%2B9oOl6GYQLDm2JdhCkdGb3jE%2Bpct1kMYFi%2BWH43Q%2B0XOY1hWuFmCOcaGmSandG%2FJDollzQa9i4VL7gu8wWeENgwxF5tvYp0vCnhP6SH81xK%2FWKbaLdvkMng2aWqCPIniRBLD%2BoudQmEHFpymhZKZu1N5828F15JTzS%2BKJoOPc3uxFDajzEmjAM3uwgHpo5Vc2KtgQczPVQluwZOiVOy8ZBI7TS%2Bfh4xqbuyZ6OIM7snRz6KklER00PBx7EZ%2BiuA5Hb77%2FpbMKzPIgFemXlF8J3%2BMkXMvR1lPtUwRXGxNGchwljADYO5T7S7HZTi0XNkvwRqGgTucdyDWU0DxMrvFTFYk80fV9rBzWz8ws4ztvAY6pgFfY1Y5XDqPk58waKctTqGp5XXixiBJkDNKqjbTQ%2FHaf1Yk%2FIBlx%2FW3jZaRrMudPlb6HrKUuMsjJXIPCF3QKGV26QP5bixqskkS7KiIHQgqScUqMVpDXHGQ9tRwPvH%2Ff%2FHwHl1MoH3CofuMjYhnlbsQNZ0p6SMfaTM5z9Wajnurzzmn0em9rN2116G2%2B8HXEh%2BukBk0sYt462zIVVMJnH5AMAyApw9Q&X-Amz-Signature=e451030f448604e6a8d5fdc891bcfd3d628d524beb91b393850955f38e657ce5&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SDNLOI4B%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T102410Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD%2Bty%2FdS1wY%2F32a%2FJwcGWzjRXENBne23YYAvzEpQnH5SAIgTdhJ0u%2BAHxVwyYqosn3ZelqbCSaQxNVJj%2BUg3ioVsqcqiAQIo%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHvbHRaeoE64UZoIeCrcA6nglevqFK3R0KcwUjPEMGx%2ByCfE7qK5bTtIJQit8ijiX0nTWVZE6zhx0GYhdjGYX5HAWjA0QkElZtkZRSGsiSw9vHUVW3ui1di2zPPRZ9Rs56EYpAkZV9x6a8XMOg0RYaeBdqtSI%2FbFTKXWhdWp6iDIko2SrgBhy5ILYb8Uts23%2F%2F9JZ2mkxaLUOOno9f6xApEfvNe25LQi3i29IyHsfv8Nm8eglCZg04mIDVeDfolP1A0m04w%2FSBYqZ15alA8quvyFV0J84qsD5Gaw6hzkXaXiE1BlsSWZyUJJpdyLF%2B%2FQsNseVdNOmu3Um8VYl%2B0WEfuaBluVdtWkoRKBNKL8tQpSdyULj0VWy9m5I%2BpZu3vbzHPCEP%2FKqlSMeXtc4PiqBe045x0ZiiZ9jbCMUzhduV3j5DzoJlDTi8wcwRY%2BiGeCRujJ17YZVWBCfTuIR8cymC%2BnyEqPAA%2FamhODl4UJl7z4qLqZF8umzeZoMJWtNUaLwY8aLLngvRvY2tj9dG4k9uE1ByIb32jC1rM0eD60AY11v7KYBsWGRwu3K9rbWN0jjajGmZpRslBerjtCAsTKyni1v8DBCaHDz3LR%2F6L80GMjXRbkQZu%2BIdYwiEegkDqPI06KWKal5QGA9t6CMP2M7bwGOqUBYd5DsAfY44nNdyeEBl9YXJ0zrMaW3e8eMUfm2Gil0ARYoopNhG61%2BPMj30zmPrOj0j%2BVkztUFbq1X7gBYdoM0wIdulMoKi6O6D9a0LJukr1SNX8fD0bjHVFFvZGu4HJhgPlQ0TKuc3Guz5DbuqgeRA%2FSo6GZ0%2FKArWMNQkvlKsPe4TnY3IOGLI1CEHv62IQUmTJzsjvkQewv7layZk2AxZ%2FlIzGW&X-Amz-Signature=26adaa8332032bddb8a6b34d8cb68ae68169b8b069ab68e26f77b2db9a9bc79f&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SDNLOI4B%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T102410Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD%2Bty%2FdS1wY%2F32a%2FJwcGWzjRXENBne23YYAvzEpQnH5SAIgTdhJ0u%2BAHxVwyYqosn3ZelqbCSaQxNVJj%2BUg3ioVsqcqiAQIo%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHvbHRaeoE64UZoIeCrcA6nglevqFK3R0KcwUjPEMGx%2ByCfE7qK5bTtIJQit8ijiX0nTWVZE6zhx0GYhdjGYX5HAWjA0QkElZtkZRSGsiSw9vHUVW3ui1di2zPPRZ9Rs56EYpAkZV9x6a8XMOg0RYaeBdqtSI%2FbFTKXWhdWp6iDIko2SrgBhy5ILYb8Uts23%2F%2F9JZ2mkxaLUOOno9f6xApEfvNe25LQi3i29IyHsfv8Nm8eglCZg04mIDVeDfolP1A0m04w%2FSBYqZ15alA8quvyFV0J84qsD5Gaw6hzkXaXiE1BlsSWZyUJJpdyLF%2B%2FQsNseVdNOmu3Um8VYl%2B0WEfuaBluVdtWkoRKBNKL8tQpSdyULj0VWy9m5I%2BpZu3vbzHPCEP%2FKqlSMeXtc4PiqBe045x0ZiiZ9jbCMUzhduV3j5DzoJlDTi8wcwRY%2BiGeCRujJ17YZVWBCfTuIR8cymC%2BnyEqPAA%2FamhODl4UJl7z4qLqZF8umzeZoMJWtNUaLwY8aLLngvRvY2tj9dG4k9uE1ByIb32jC1rM0eD60AY11v7KYBsWGRwu3K9rbWN0jjajGmZpRslBerjtCAsTKyni1v8DBCaHDz3LR%2F6L80GMjXRbkQZu%2BIdYwiEegkDqPI06KWKal5QGA9t6CMP2M7bwGOqUBYd5DsAfY44nNdyeEBl9YXJ0zrMaW3e8eMUfm2Gil0ARYoopNhG61%2BPMj30zmPrOj0j%2BVkztUFbq1X7gBYdoM0wIdulMoKi6O6D9a0LJukr1SNX8fD0bjHVFFvZGu4HJhgPlQ0TKuc3Guz5DbuqgeRA%2FSo6GZ0%2FKArWMNQkvlKsPe4TnY3IOGLI1CEHv62IQUmTJzsjvkQewv7layZk2AxZ%2FlIzGW&X-Amz-Signature=88f17bdba6d4b765e4f3ce1ac14c37dc6432cb41670c05c3346a7492206531f4&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SDNLOI4B%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T102410Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD%2Bty%2FdS1wY%2F32a%2FJwcGWzjRXENBne23YYAvzEpQnH5SAIgTdhJ0u%2BAHxVwyYqosn3ZelqbCSaQxNVJj%2BUg3ioVsqcqiAQIo%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHvbHRaeoE64UZoIeCrcA6nglevqFK3R0KcwUjPEMGx%2ByCfE7qK5bTtIJQit8ijiX0nTWVZE6zhx0GYhdjGYX5HAWjA0QkElZtkZRSGsiSw9vHUVW3ui1di2zPPRZ9Rs56EYpAkZV9x6a8XMOg0RYaeBdqtSI%2FbFTKXWhdWp6iDIko2SrgBhy5ILYb8Uts23%2F%2F9JZ2mkxaLUOOno9f6xApEfvNe25LQi3i29IyHsfv8Nm8eglCZg04mIDVeDfolP1A0m04w%2FSBYqZ15alA8quvyFV0J84qsD5Gaw6hzkXaXiE1BlsSWZyUJJpdyLF%2B%2FQsNseVdNOmu3Um8VYl%2B0WEfuaBluVdtWkoRKBNKL8tQpSdyULj0VWy9m5I%2BpZu3vbzHPCEP%2FKqlSMeXtc4PiqBe045x0ZiiZ9jbCMUzhduV3j5DzoJlDTi8wcwRY%2BiGeCRujJ17YZVWBCfTuIR8cymC%2BnyEqPAA%2FamhODl4UJl7z4qLqZF8umzeZoMJWtNUaLwY8aLLngvRvY2tj9dG4k9uE1ByIb32jC1rM0eD60AY11v7KYBsWGRwu3K9rbWN0jjajGmZpRslBerjtCAsTKyni1v8DBCaHDz3LR%2F6L80GMjXRbkQZu%2BIdYwiEegkDqPI06KWKal5QGA9t6CMP2M7bwGOqUBYd5DsAfY44nNdyeEBl9YXJ0zrMaW3e8eMUfm2Gil0ARYoopNhG61%2BPMj30zmPrOj0j%2BVkztUFbq1X7gBYdoM0wIdulMoKi6O6D9a0LJukr1SNX8fD0bjHVFFvZGu4HJhgPlQ0TKuc3Guz5DbuqgeRA%2FSo6GZ0%2FKArWMNQkvlKsPe4TnY3IOGLI1CEHv62IQUmTJzsjvkQewv7layZk2AxZ%2FlIzGW&X-Amz-Signature=bc365ef8378809e14f710a228621d56cc689d46460644bda2f1b158e2792bc33&X-Amz-SignedHeaders=host&x-id=GetObject)


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

