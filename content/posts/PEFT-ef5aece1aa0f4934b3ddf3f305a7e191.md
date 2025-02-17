---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466SSBTSCUH%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250217T052536Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEEMaCXVzLXdlc3QtMiJHMEUCIQCrGWnD%2FlnXqCoM%2BMbrTQ0FaBayi5%2BZ6jUhntMjhcUxd\
  AIgPUDGupDCFwTkp53P719MX1I2egPPkfJVe8r7IDnv%2F6Eq%2FwMIbBAAGgw2Mzc0MjMxODM4MD\
  UiDJuqjWMKzHgqOGgiVCrcA7OnF29Knhk9NCgYILXve%2BdYSOYd7yFy1p2mPrdPUtHg7xA4Rdw9g\
  klkvszJM1f8xFIyo2e%2F8nG%2BMZszcL2AfxcDyfSF9vj0Qg6KqVDKDgTQt4qPXze7c4Ma4F0N9Z\
  zTstMSKjQMIZLQjf7zpLCqjVn8E%2FlSFAnkrNDB65k5qmadBZAmWGmdmXj%2BsP87fdbtmcLzJyH\
  Bh9N0oXDym1c%2FBCkv%2Bs8Io1HuiwyHDRREWRUzzm1HPlKScA0Goa%2FZW1hIadcB0XyolIKMtD\
  F%2BT%2B7cw%2B20%2F8hYcZBIDI5WbK3U4wzL6uQ1%2FEFPu%2BnDqnChj5W5LM7gymgQML50eFf\
  y5ggQ68xmZxRPyEhEP8%2FjtPuFxqKdOYu5DUX4H5XFhISZTjtlYHU%2FhWVrbc065TqEF%2By8rZ\
  p%2BizuTxmlA8%2Bzgn78XUZLUyw9AH5M0tAjZ4dM%2BjPPWmNCQ9PVxrOhl6dn83PnRz597jUBH4\
  nZObaFVmMpiL7RnISULCyakF7VvRkfdeW1wRh4Injjchx9%2FTt1z9a4%2Fo%2BGSdr0POoQ0Gjlc\
  h4CiATyeiF6%2BHHAPdoNmz%2BgJlaSGHwx%2FTcMmF58pSt7ozxt22Cy13DmwsxxZKlqGuvXBbJf\
  8TclhpyQlp%2BBH7MDPMIDKyr0GOqUBmmVSS3ra7fh2wx2xJLORxpczbgVQJU0lcT1p9PrB0uAX87\
  QTL4amEQR7nDyT2AGhV1YSTFQ0gUKrTnwPis02sBnGXacdgNzfV4xLoG2VQtXrISJRYHt4Xt7juXX\
  wAiPiN%2BQh0zjn%2BW3ntrLDp%2F0YYovnYqao4vcN5k0flaui8aOT2mNjhPTxwrcLEDUwLSdJOC\
  nMJvZ2fPEXxNnDulAqiEGMD533&X-Amz-Signature=89f6329da9f0125e0284d0f056d5369ebe\
  1e012912f857cb3b6e8f8b7227a087&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4664Q4EOFEW%2F20250217%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250217T052409Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEEQaCXVzLXdlc3QtMiJGMEQCIBfztJg06kqQWoy1Ewxzup%2FaTBm47\
        BmUvR%2BVAea0HoSfAiBEr0aVlA0nLqm7uNT8TDo29gMxw5urcyE%2F56QvFNI5Xir%2FAw\
        htEAAaDDYzNzQyMzE4MzgwNSIMmS8%2BAPu908aLCVEiKtwDqFv%2FvUjXy11Yb%2BIrp3J\
        gkBtRDlhttqgOHF9LoCXDgNQE5RAWQJaXYEl6c3yfnUM22rnvPF83LFAEHjSUT1hrsjcUb1\
        hQrOmob%2BmUvESTtTZacSoqnNj4SFolXeF0K23IdgkO1Ydj13QJSSYC%2FEKBGaZ3%2BoX\
        8uPBvU7vILiC1qWHeNzwJDro4HoJ6uf1MmaS2XoQLaTQlwlLyqVqmL%2FzBMUmhnV12ZKVL\
        unBR3vT%2BdaXph%2Bq2uZLJtaPnLkQm3aeOops7SxU4ZHl%2F6xZLCue%2FDoq8df5bhWX\
        HrpAT7q7Nj%2BWxQ%2FSu5BD4eYlM0YxZCv%2FnugYb9RK1pqDVG8e6JCODHY%2FnnhexHH\
        xrsXH3Ka5zkINIoaJ4KgAYrcJkN995T2IeNAUw%2BX9MchqdTV1My1Ftq7XMZXYmx7p%2FN\
        SCYb4jjaW7XnoK0kZO19ieBgK%2BGF4JL7%2FUmfzRbshtNMbsEoZcseCv%2BXQ5priTmjX\
        4feUxsY4%2Fr0bjkx%2FRjKcyrjxMC%2FHukrC1OaY7ZdpzQaw83MfvxlNjwYyUM40LpEjl\
        OiEsZeaDp3jyCZJ9nSqt1k2bHSDOezD4O3oItu6RoEp6BH3TjbSpccFRHpA6t6b82txY1Lz\
        ffgXIyg578umyZVX4w1%2BfKvQY6pgFFgpmxhhcAh3I6IiDx3K%2FPrQ7eIB1lOJm40Myhh\
        tLcd3sLbo3Zy4Y0lqkMMQ6%2FZEtBDpwtzDUUo0upcZTiJqB4EtB%2B%2F6m5Zs%2BTs9VE\
        eH2dGjhSsQgRMM9VFiM98cdhP6y6FQi0bw1M4xi%2B4Wl0LvJ9h5K6tUhwqKJjXHHRn%2BK\
        KNgsj3PuYE5nNqIF4UkRNV%2FQGSy%2BL4v%2FWcnQzkNAz%2FfSTIsl1m6PO&X-Amz-Sig\
        nature=8917cff212aa3f6fe26ba91c64cd0d098598b2b0230139004affd1e36b4a7e75\
        &X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-17T06:24:09.032Z"
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
UPDATE_TIME: "2025-02-17T05:25:45.760Z"
EXPIRY_TIME: "2025-02-17T06:25:33.052Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ULTG5ZKH%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T052533Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEMaCXVzLXdlc3QtMiJHMEUCIGKgX8c4QTp6B%2Be%2Fd8KrML2zU1gfX9dkIRJd75MDGiroAiEAvSgJXd0geFWbFr9pasEI%2FtNLefuDBjdLHgMn5tHihLQq%2FwMIbBAAGgw2Mzc0MjMxODM4MDUiDPns2qyhRz4nekN4kSrcAzNBMueMgb7H0VAEbzh3dKCrx19JqB7ULbX%2BTidqJ2O2AQTRaFczOjwkn8aBYHAsddfcckz%2BqvIaxwaooSaieshdIWV4P65zUtP7FOs2ow69TyGnFKmwM0r%2BCcM5DehFMicHLbBdf7PREGvBRANvf6sLkVBOcFayxAf6hfa8%2BbPdZRCsHDn5vTh6%2F6KdGX23nJqXQt4P9DM0v%2BsROrpX5PITMVQGH11k1FentRTbjybEqi60jOkH3G8VGiSrHlXgyKGwGYZLdv6ha%2BtW1YCSf6F0gmy%2B4VjZqKWaqfdno8P5PCmncUUqlCmJPw8rj%2BCSAXG8BkT99fDzG%2BonfTlXwm0GJq8pK6Ndutg1Xp7qgf6RJemNB%2FIeVm4WP5QVukvqG1spFyTx4IjFhlxmoqpP7F%2FxVuioSzu3ltB7iwgFze2tNrUqQWBJVQBr%2BX6MYHWsChjrpxTFsql0%2FH6BKh0c1eTsYY9SSmyLLZiIyCpKVhXFQwAtL5sWM6701irK%2FUp9bdcLRktM5Yhgq0ITou4OaP7eFB5TMqfMa%2F%2F8LBd6pyjhItRhafi3%2FJ3Fqv7R7oK6Z76qzuuZvQ8HGNOsKGZ4TM72zAklVMOS%2FDF8x8X8qonXKrz4oxi8fFyB09aZMJfKyr0GOqUB2cOcTu%2Fi%2B6o6g%2BYq5EPjG%2BjtGlJpz8NA4DmqehdYugsZ5H6qshJlAu%2B09r%2FDEsgp2PjDx5ptCSghANKhunzZpEUtZH6qjZLt21YcElIbo9IC3P%2BuELmeOf4abirrbHP0ntoU2xDMqkJqNcnABKSbeqKTs6jcYmoZ8q9Cy%2BWzsOIG8hfM%2BsIFf9zOZPs%2BFafxPYsqntpBJGkLHpw29vlpb9Gb%2FZb7&X-Amz-Signature=685d7c0df330180a0ebf191587d7fe292caeb2b587fe591d959634fc074a4522&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ULTG5ZKH%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T052533Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEMaCXVzLXdlc3QtMiJHMEUCIGKgX8c4QTp6B%2Be%2Fd8KrML2zU1gfX9dkIRJd75MDGiroAiEAvSgJXd0geFWbFr9pasEI%2FtNLefuDBjdLHgMn5tHihLQq%2FwMIbBAAGgw2Mzc0MjMxODM4MDUiDPns2qyhRz4nekN4kSrcAzNBMueMgb7H0VAEbzh3dKCrx19JqB7ULbX%2BTidqJ2O2AQTRaFczOjwkn8aBYHAsddfcckz%2BqvIaxwaooSaieshdIWV4P65zUtP7FOs2ow69TyGnFKmwM0r%2BCcM5DehFMicHLbBdf7PREGvBRANvf6sLkVBOcFayxAf6hfa8%2BbPdZRCsHDn5vTh6%2F6KdGX23nJqXQt4P9DM0v%2BsROrpX5PITMVQGH11k1FentRTbjybEqi60jOkH3G8VGiSrHlXgyKGwGYZLdv6ha%2BtW1YCSf6F0gmy%2B4VjZqKWaqfdno8P5PCmncUUqlCmJPw8rj%2BCSAXG8BkT99fDzG%2BonfTlXwm0GJq8pK6Ndutg1Xp7qgf6RJemNB%2FIeVm4WP5QVukvqG1spFyTx4IjFhlxmoqpP7F%2FxVuioSzu3ltB7iwgFze2tNrUqQWBJVQBr%2BX6MYHWsChjrpxTFsql0%2FH6BKh0c1eTsYY9SSmyLLZiIyCpKVhXFQwAtL5sWM6701irK%2FUp9bdcLRktM5Yhgq0ITou4OaP7eFB5TMqfMa%2F%2F8LBd6pyjhItRhafi3%2FJ3Fqv7R7oK6Z76qzuuZvQ8HGNOsKGZ4TM72zAklVMOS%2FDF8x8X8qonXKrz4oxi8fFyB09aZMJfKyr0GOqUB2cOcTu%2Fi%2B6o6g%2BYq5EPjG%2BjtGlJpz8NA4DmqehdYugsZ5H6qshJlAu%2B09r%2FDEsgp2PjDx5ptCSghANKhunzZpEUtZH6qjZLt21YcElIbo9IC3P%2BuELmeOf4abirrbHP0ntoU2xDMqkJqNcnABKSbeqKTs6jcYmoZ8q9Cy%2BWzsOIG8hfM%2BsIFf9zOZPs%2BFafxPYsqntpBJGkLHpw29vlpb9Gb%2FZb7&X-Amz-Signature=381263c7ffb1f5f2fe91c8dd9faf6d086331b91411f30e2182b5f8a7c334dd74&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ULTG5ZKH%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T052533Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEMaCXVzLXdlc3QtMiJHMEUCIGKgX8c4QTp6B%2Be%2Fd8KrML2zU1gfX9dkIRJd75MDGiroAiEAvSgJXd0geFWbFr9pasEI%2FtNLefuDBjdLHgMn5tHihLQq%2FwMIbBAAGgw2Mzc0MjMxODM4MDUiDPns2qyhRz4nekN4kSrcAzNBMueMgb7H0VAEbzh3dKCrx19JqB7ULbX%2BTidqJ2O2AQTRaFczOjwkn8aBYHAsddfcckz%2BqvIaxwaooSaieshdIWV4P65zUtP7FOs2ow69TyGnFKmwM0r%2BCcM5DehFMicHLbBdf7PREGvBRANvf6sLkVBOcFayxAf6hfa8%2BbPdZRCsHDn5vTh6%2F6KdGX23nJqXQt4P9DM0v%2BsROrpX5PITMVQGH11k1FentRTbjybEqi60jOkH3G8VGiSrHlXgyKGwGYZLdv6ha%2BtW1YCSf6F0gmy%2B4VjZqKWaqfdno8P5PCmncUUqlCmJPw8rj%2BCSAXG8BkT99fDzG%2BonfTlXwm0GJq8pK6Ndutg1Xp7qgf6RJemNB%2FIeVm4WP5QVukvqG1spFyTx4IjFhlxmoqpP7F%2FxVuioSzu3ltB7iwgFze2tNrUqQWBJVQBr%2BX6MYHWsChjrpxTFsql0%2FH6BKh0c1eTsYY9SSmyLLZiIyCpKVhXFQwAtL5sWM6701irK%2FUp9bdcLRktM5Yhgq0ITou4OaP7eFB5TMqfMa%2F%2F8LBd6pyjhItRhafi3%2FJ3Fqv7R7oK6Z76qzuuZvQ8HGNOsKGZ4TM72zAklVMOS%2FDF8x8X8qonXKrz4oxi8fFyB09aZMJfKyr0GOqUB2cOcTu%2Fi%2B6o6g%2BYq5EPjG%2BjtGlJpz8NA4DmqehdYugsZ5H6qshJlAu%2B09r%2FDEsgp2PjDx5ptCSghANKhunzZpEUtZH6qjZLt21YcElIbo9IC3P%2BuELmeOf4abirrbHP0ntoU2xDMqkJqNcnABKSbeqKTs6jcYmoZ8q9Cy%2BWzsOIG8hfM%2BsIFf9zOZPs%2BFafxPYsqntpBJGkLHpw29vlpb9Gb%2FZb7&X-Amz-Signature=ae97276a57ba89447355faadd5c6125a4b7641d06d84f4ca2b03433605b20c44&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ULTG5ZKH%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T052533Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEMaCXVzLXdlc3QtMiJHMEUCIGKgX8c4QTp6B%2Be%2Fd8KrML2zU1gfX9dkIRJd75MDGiroAiEAvSgJXd0geFWbFr9pasEI%2FtNLefuDBjdLHgMn5tHihLQq%2FwMIbBAAGgw2Mzc0MjMxODM4MDUiDPns2qyhRz4nekN4kSrcAzNBMueMgb7H0VAEbzh3dKCrx19JqB7ULbX%2BTidqJ2O2AQTRaFczOjwkn8aBYHAsddfcckz%2BqvIaxwaooSaieshdIWV4P65zUtP7FOs2ow69TyGnFKmwM0r%2BCcM5DehFMicHLbBdf7PREGvBRANvf6sLkVBOcFayxAf6hfa8%2BbPdZRCsHDn5vTh6%2F6KdGX23nJqXQt4P9DM0v%2BsROrpX5PITMVQGH11k1FentRTbjybEqi60jOkH3G8VGiSrHlXgyKGwGYZLdv6ha%2BtW1YCSf6F0gmy%2B4VjZqKWaqfdno8P5PCmncUUqlCmJPw8rj%2BCSAXG8BkT99fDzG%2BonfTlXwm0GJq8pK6Ndutg1Xp7qgf6RJemNB%2FIeVm4WP5QVukvqG1spFyTx4IjFhlxmoqpP7F%2FxVuioSzu3ltB7iwgFze2tNrUqQWBJVQBr%2BX6MYHWsChjrpxTFsql0%2FH6BKh0c1eTsYY9SSmyLLZiIyCpKVhXFQwAtL5sWM6701irK%2FUp9bdcLRktM5Yhgq0ITou4OaP7eFB5TMqfMa%2F%2F8LBd6pyjhItRhafi3%2FJ3Fqv7R7oK6Z76qzuuZvQ8HGNOsKGZ4TM72zAklVMOS%2FDF8x8X8qonXKrz4oxi8fFyB09aZMJfKyr0GOqUB2cOcTu%2Fi%2B6o6g%2BYq5EPjG%2BjtGlJpz8NA4DmqehdYugsZ5H6qshJlAu%2B09r%2FDEsgp2PjDx5ptCSghANKhunzZpEUtZH6qjZLt21YcElIbo9IC3P%2BuELmeOf4abirrbHP0ntoU2xDMqkJqNcnABKSbeqKTs6jcYmoZ8q9Cy%2BWzsOIG8hfM%2BsIFf9zOZPs%2BFafxPYsqntpBJGkLHpw29vlpb9Gb%2FZb7&X-Amz-Signature=730ac565f354bbed1c20a38bb721e1e1847e599a23734f41ccee477ac9c12fe6&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ULTG5ZKH%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T052533Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEMaCXVzLXdlc3QtMiJHMEUCIGKgX8c4QTp6B%2Be%2Fd8KrML2zU1gfX9dkIRJd75MDGiroAiEAvSgJXd0geFWbFr9pasEI%2FtNLefuDBjdLHgMn5tHihLQq%2FwMIbBAAGgw2Mzc0MjMxODM4MDUiDPns2qyhRz4nekN4kSrcAzNBMueMgb7H0VAEbzh3dKCrx19JqB7ULbX%2BTidqJ2O2AQTRaFczOjwkn8aBYHAsddfcckz%2BqvIaxwaooSaieshdIWV4P65zUtP7FOs2ow69TyGnFKmwM0r%2BCcM5DehFMicHLbBdf7PREGvBRANvf6sLkVBOcFayxAf6hfa8%2BbPdZRCsHDn5vTh6%2F6KdGX23nJqXQt4P9DM0v%2BsROrpX5PITMVQGH11k1FentRTbjybEqi60jOkH3G8VGiSrHlXgyKGwGYZLdv6ha%2BtW1YCSf6F0gmy%2B4VjZqKWaqfdno8P5PCmncUUqlCmJPw8rj%2BCSAXG8BkT99fDzG%2BonfTlXwm0GJq8pK6Ndutg1Xp7qgf6RJemNB%2FIeVm4WP5QVukvqG1spFyTx4IjFhlxmoqpP7F%2FxVuioSzu3ltB7iwgFze2tNrUqQWBJVQBr%2BX6MYHWsChjrpxTFsql0%2FH6BKh0c1eTsYY9SSmyLLZiIyCpKVhXFQwAtL5sWM6701irK%2FUp9bdcLRktM5Yhgq0ITou4OaP7eFB5TMqfMa%2F%2F8LBd6pyjhItRhafi3%2FJ3Fqv7R7oK6Z76qzuuZvQ8HGNOsKGZ4TM72zAklVMOS%2FDF8x8X8qonXKrz4oxi8fFyB09aZMJfKyr0GOqUB2cOcTu%2Fi%2B6o6g%2BYq5EPjG%2BjtGlJpz8NA4DmqehdYugsZ5H6qshJlAu%2B09r%2FDEsgp2PjDx5ptCSghANKhunzZpEUtZH6qjZLt21YcElIbo9IC3P%2BuELmeOf4abirrbHP0ntoU2xDMqkJqNcnABKSbeqKTs6jcYmoZ8q9Cy%2BWzsOIG8hfM%2BsIFf9zOZPs%2BFafxPYsqntpBJGkLHpw29vlpb9Gb%2FZb7&X-Amz-Signature=a60a3ad8c5add0c464384fe1a7d52fa6cf443a5c7a8b74319bd1ee7233443549&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UPRMB2DG%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T052533Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEMaCXVzLXdlc3QtMiJGMEQCIFKqD3lyfrTq3Ng04cj3roF5V%2BcoMn4ewYoL9elzf3fPAiAZHEonHaUX1mrIU09agHcXWEQ8d3pECzllG6IHFBEHYyr%2FAwhsEAAaDDYzNzQyMzE4MzgwNSIMAk%2BndtrOaJ95U7V6KtwDmHucbro3f3xowlFw6uQyiFZIVzEjlvwpxkXygzzdj54nkBUa0OyVLTMJSeTm%2Fvdc36IiXsyMhq7MXumbV7R8z1BlrsgTFwfT3pd87FkP8g6GDJ3Pi9QEKRjBj5w5LCmbVczlWWQqz5XIaQVjPjAVTmbqqJZBOWkjXSfEbtX540Y6FWthFvBrYgxwLrpZn7U0Zgmn%2BQ0rBXCn7frdquCCHdLnmuyptvzAybyPv9AqimqRo8uVfqiptLfuJ9HvZ%2ByqhtV7tW%2FgB76YOLGyoMGrlNDildABdCAwErbS1%2F4vQZY8nx6Ui1jYtaGfdT%2FtBfphlXhOww4Im5JH8WTxlkOP1aq7DiglM3rnFKQd6u0UQVI9ZAYlaXqGXikP2u8Q5VMywvEZlXcaheU%2F6lY89t1goScbCm1vtPEY2ybhTi%2BXV67tb2goqjD43V3T96JgmMYawXthEM72ssxQgT0CYei%2BrFk%2FsqaSr%2BZhUbVGQjOsRdgeibVa5AxBvZu34YeRPLq1RRr16TH%2BN7kslu8q%2FU5apLyXu01wFogolZMe0N32IKjOX%2Fw1JMvLndmH2E%2BXf2Fz7rgkOfGE2CPC0C24%2BgkDpMOudTCX8KS2h3BGC9Mk1T0VvW%2FEqaoA%2FEhNL0UwmcrKvQY6pgFXr4be%2BM49Pu12I0nqpecS6r2gKTnZ9rsRPgzW2wVsE6rhyowy%2BO0no1x30DIzyns1qFOugzfjBfRTQlV8z6NRju%2FPgJkm4OC5I4q5HzCcyqGg%2Bu8vP%2BJl6NuBkhRakZe9oSsBSUTErqt%2BJVRvVuZCmHef1XXV1h%2BoOOFE59eaJcqB6fMK9kI00sYmtY4sF017mF5bwxF3v3DTbm1Qxebgz5zu0OD8&X-Amz-Signature=65651fe7b931734ac741931cc4fa172dd77a5d6eaeefc3dcc5b697f2b0e2a17c&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U65DXSJI%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T052536Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEMaCXVzLXdlc3QtMiJHMEUCIH7iSOPTNyN3RBq%2F7kEmxCAxZaSqXOnVtO5mGoV3JruwAiEAl828zvdkbIj4oHcdDQ8mElfgILKzvPZ2yM3gvTfpD3gq%2FwMIbBAAGgw2Mzc0MjMxODM4MDUiDJ2Bbtk1jUTbbHgixyrcA%2BA7zZtGIN4JbtxPr3IvFAAM9HGOJ9tvP5WIve1RVGtNkKnsp%2F%2BR5GD3v3W6c0TnQPrKli4G5MoJ2uv8%2BTJuWz%2BlDD%2BOfMUtCGhYmoRIVQo8Xx0HvavDzr5jFp22U2VvpDpHlNL9rgomS7v1hNO24%2Fgu6rL3O9Wh0wW8Io8O91Swxk5RN05rD69gDwG8%2FR4l3ww2o3jco%2FcceppUwMtDQYFUpkDQ%2FrUc1GIAQB%2F7lE4wPm%2BGeM9PyF59NMmmAfQ%2F9ZfDEoXFH%2BfvESdoZ2u6VlsL0bwaqpmVjQFwB32mmkg2iMo%2BepcwZ20wRVtJEeuT9zgDR7%2FmoZJyQzcAgvkpERKc6BtJRAjaoaSa%2BPnIm1HGLGFtsgxi%2FJAvsGC7URDTMsgniBgQDpH8FLmrONGhKiEVMaCjIdstXnOGAhuaSKW2W67e1WLOUukEn70KLxsBF%2BCCnly9CGi3xPIab0qsQ7RgZNhhY06gSdACGGASZS7fh%2FlBCXX1vSYKU%2BsuwO4FsxrlcJzBe%2BYt2fD8Ov6djslYCq6u6Ufoch2v%2BtrSyFWaTVhEARDHWioEecsRI6Xo135BUJhB3yoAjY3BaRc%2FcvC7HG3tEKBSUT5g9tuS0oJLb8erzmkHcJG3E3BUMJnKyr0GOqUBg%2F92URhSpPBWeQWI7gCqCsVgZPjNNekDk8FWWazQFyhxPIBR3rMsZRri3NkJlaWfHEVn3T3LnZZ33S6LqiRzCUNR7%2Bp8JLuK1nfGhLehJVDzqFuphwOWgisf41VyYVd5VE2ALm%2F5WsrZP50gan7mK1rR3SAv6CTZyDDuWhigwcSRh1%2BA2gpJxSKjK8LoV5XlDdXsGcI6nuLFtaf%2Bd1qj20S4EGdN&X-Amz-Signature=0b67f08e5d7253d344a2089ea3515b6313d08719665e256daa46fa2c4637169b&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ULTG5ZKH%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T052533Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEMaCXVzLXdlc3QtMiJHMEUCIGKgX8c4QTp6B%2Be%2Fd8KrML2zU1gfX9dkIRJd75MDGiroAiEAvSgJXd0geFWbFr9pasEI%2FtNLefuDBjdLHgMn5tHihLQq%2FwMIbBAAGgw2Mzc0MjMxODM4MDUiDPns2qyhRz4nekN4kSrcAzNBMueMgb7H0VAEbzh3dKCrx19JqB7ULbX%2BTidqJ2O2AQTRaFczOjwkn8aBYHAsddfcckz%2BqvIaxwaooSaieshdIWV4P65zUtP7FOs2ow69TyGnFKmwM0r%2BCcM5DehFMicHLbBdf7PREGvBRANvf6sLkVBOcFayxAf6hfa8%2BbPdZRCsHDn5vTh6%2F6KdGX23nJqXQt4P9DM0v%2BsROrpX5PITMVQGH11k1FentRTbjybEqi60jOkH3G8VGiSrHlXgyKGwGYZLdv6ha%2BtW1YCSf6F0gmy%2B4VjZqKWaqfdno8P5PCmncUUqlCmJPw8rj%2BCSAXG8BkT99fDzG%2BonfTlXwm0GJq8pK6Ndutg1Xp7qgf6RJemNB%2FIeVm4WP5QVukvqG1spFyTx4IjFhlxmoqpP7F%2FxVuioSzu3ltB7iwgFze2tNrUqQWBJVQBr%2BX6MYHWsChjrpxTFsql0%2FH6BKh0c1eTsYY9SSmyLLZiIyCpKVhXFQwAtL5sWM6701irK%2FUp9bdcLRktM5Yhgq0ITou4OaP7eFB5TMqfMa%2F%2F8LBd6pyjhItRhafi3%2FJ3Fqv7R7oK6Z76qzuuZvQ8HGNOsKGZ4TM72zAklVMOS%2FDF8x8X8qonXKrz4oxi8fFyB09aZMJfKyr0GOqUB2cOcTu%2Fi%2B6o6g%2BYq5EPjG%2BjtGlJpz8NA4DmqehdYugsZ5H6qshJlAu%2B09r%2FDEsgp2PjDx5ptCSghANKhunzZpEUtZH6qjZLt21YcElIbo9IC3P%2BuELmeOf4abirrbHP0ntoU2xDMqkJqNcnABKSbeqKTs6jcYmoZ8q9Cy%2BWzsOIG8hfM%2BsIFf9zOZPs%2BFafxPYsqntpBJGkLHpw29vlpb9Gb%2FZb7&X-Amz-Signature=5843cf84b3b21b6399e955feca8ad7d043b0894e63396a46865c399f0019a2b2&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ULTG5ZKH%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T052533Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEMaCXVzLXdlc3QtMiJHMEUCIGKgX8c4QTp6B%2Be%2Fd8KrML2zU1gfX9dkIRJd75MDGiroAiEAvSgJXd0geFWbFr9pasEI%2FtNLefuDBjdLHgMn5tHihLQq%2FwMIbBAAGgw2Mzc0MjMxODM4MDUiDPns2qyhRz4nekN4kSrcAzNBMueMgb7H0VAEbzh3dKCrx19JqB7ULbX%2BTidqJ2O2AQTRaFczOjwkn8aBYHAsddfcckz%2BqvIaxwaooSaieshdIWV4P65zUtP7FOs2ow69TyGnFKmwM0r%2BCcM5DehFMicHLbBdf7PREGvBRANvf6sLkVBOcFayxAf6hfa8%2BbPdZRCsHDn5vTh6%2F6KdGX23nJqXQt4P9DM0v%2BsROrpX5PITMVQGH11k1FentRTbjybEqi60jOkH3G8VGiSrHlXgyKGwGYZLdv6ha%2BtW1YCSf6F0gmy%2B4VjZqKWaqfdno8P5PCmncUUqlCmJPw8rj%2BCSAXG8BkT99fDzG%2BonfTlXwm0GJq8pK6Ndutg1Xp7qgf6RJemNB%2FIeVm4WP5QVukvqG1spFyTx4IjFhlxmoqpP7F%2FxVuioSzu3ltB7iwgFze2tNrUqQWBJVQBr%2BX6MYHWsChjrpxTFsql0%2FH6BKh0c1eTsYY9SSmyLLZiIyCpKVhXFQwAtL5sWM6701irK%2FUp9bdcLRktM5Yhgq0ITou4OaP7eFB5TMqfMa%2F%2F8LBd6pyjhItRhafi3%2FJ3Fqv7R7oK6Z76qzuuZvQ8HGNOsKGZ4TM72zAklVMOS%2FDF8x8X8qonXKrz4oxi8fFyB09aZMJfKyr0GOqUB2cOcTu%2Fi%2B6o6g%2BYq5EPjG%2BjtGlJpz8NA4DmqehdYugsZ5H6qshJlAu%2B09r%2FDEsgp2PjDx5ptCSghANKhunzZpEUtZH6qjZLt21YcElIbo9IC3P%2BuELmeOf4abirrbHP0ntoU2xDMqkJqNcnABKSbeqKTs6jcYmoZ8q9Cy%2BWzsOIG8hfM%2BsIFf9zOZPs%2BFafxPYsqntpBJGkLHpw29vlpb9Gb%2FZb7&X-Amz-Signature=e0f580e823173bcd29d0db169a0b447540be9fa2c5848c3f490d75bfc85a408e&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ULTG5ZKH%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T052533Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEMaCXVzLXdlc3QtMiJHMEUCIGKgX8c4QTp6B%2Be%2Fd8KrML2zU1gfX9dkIRJd75MDGiroAiEAvSgJXd0geFWbFr9pasEI%2FtNLefuDBjdLHgMn5tHihLQq%2FwMIbBAAGgw2Mzc0MjMxODM4MDUiDPns2qyhRz4nekN4kSrcAzNBMueMgb7H0VAEbzh3dKCrx19JqB7ULbX%2BTidqJ2O2AQTRaFczOjwkn8aBYHAsddfcckz%2BqvIaxwaooSaieshdIWV4P65zUtP7FOs2ow69TyGnFKmwM0r%2BCcM5DehFMicHLbBdf7PREGvBRANvf6sLkVBOcFayxAf6hfa8%2BbPdZRCsHDn5vTh6%2F6KdGX23nJqXQt4P9DM0v%2BsROrpX5PITMVQGH11k1FentRTbjybEqi60jOkH3G8VGiSrHlXgyKGwGYZLdv6ha%2BtW1YCSf6F0gmy%2B4VjZqKWaqfdno8P5PCmncUUqlCmJPw8rj%2BCSAXG8BkT99fDzG%2BonfTlXwm0GJq8pK6Ndutg1Xp7qgf6RJemNB%2FIeVm4WP5QVukvqG1spFyTx4IjFhlxmoqpP7F%2FxVuioSzu3ltB7iwgFze2tNrUqQWBJVQBr%2BX6MYHWsChjrpxTFsql0%2FH6BKh0c1eTsYY9SSmyLLZiIyCpKVhXFQwAtL5sWM6701irK%2FUp9bdcLRktM5Yhgq0ITou4OaP7eFB5TMqfMa%2F%2F8LBd6pyjhItRhafi3%2FJ3Fqv7R7oK6Z76qzuuZvQ8HGNOsKGZ4TM72zAklVMOS%2FDF8x8X8qonXKrz4oxi8fFyB09aZMJfKyr0GOqUB2cOcTu%2Fi%2B6o6g%2BYq5EPjG%2BjtGlJpz8NA4DmqehdYugsZ5H6qshJlAu%2B09r%2FDEsgp2PjDx5ptCSghANKhunzZpEUtZH6qjZLt21YcElIbo9IC3P%2BuELmeOf4abirrbHP0ntoU2xDMqkJqNcnABKSbeqKTs6jcYmoZ8q9Cy%2BWzsOIG8hfM%2BsIFf9zOZPs%2BFafxPYsqntpBJGkLHpw29vlpb9Gb%2FZb7&X-Amz-Signature=4713af6819ab4de11dfc849ba73f527e392f0c04b6bb954f3fffacc1e9222c40&X-Amz-SignedHeaders=host&x-id=GetObject)


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

