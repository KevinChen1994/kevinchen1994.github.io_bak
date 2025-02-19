---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466XQK4G2EE%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250219T132858Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEHsaCXVzLXdlc3QtMiJHMEUCIQCWBFH65xa%2FilgdGhQ2K3n0RVgzIoFCVLZlzs8Ir8WYIAIgM\
  HIhKqZutG6AQEf91opVzLw15riFBwvLkOoIlQlYS%2FAqiAQIpP%2F%2F%2F%2F%2F%2F%2F%2F%2\
  F%2FARAAGgw2Mzc0MjMxODM4MDUiDIGCgvxtECxIOwFvYyrcA2wQP3U%2FDK2%2FbxXw9gK6dLi2R\
  sBP%2BPOD6OVzO5j95qzHbQSlFGBHoMmeJYHlTsC13abC4LUwbehd1ctgQXSjOgmL8UbW%2FPr%2B\
  RzHEe9yyACAMdKcaQWkqUpZji%2B7i8UjsnQ6hFgUAeB7jYYGAneGgJANzAEqvGcZ9IbP0cUooUrn\
  0BsgIGMsT4Hhn%2Fxdk9vxmI7GWibLEvHSqm5%2BdgAV3cFT%2Bf64qI2P1i2j54rC2LVG1KBSTYO\
  FF0KFT%2FVJgbP85VMT7w8DGxbc59sbZtFJXn6JOCaj5Xgf5T21po6bknH2%2F8SZRlr%2BB92RP8\
  YVy0GQku9CbQNvbSMSgNPVVcqAazmY7XZIwTsL%2Bw3oweOWaK%2B%2Ffab601JuU%2FEC0nsvTDe\
  5H6MXU9ng%2F7WRo2SsONYxe0%2B6a%2F%2FcZDTW9AinO3etwdVhripRLBIth6tgWL%2B2sMxPw8\
  FnS59H77pOOLGEv5vhW%2FGGUSo1MSwqwU%2F1ddxMnza49zFp1Cp6YCWA3PNKCANhC98yPmYLxjd\
  5xka5FTHA4NZSF4vyes4ZkLPCHejp0lBh8t9GOBAZSq%2FsULQtk7TecYVixZopbQYCY5ZEXw7l%2\
  BncPBNHUg%2BkVVu%2BRSZhB%2BC%2BJqEqMAX00eTjk2WFOHMNb61r0GOqUBK1GqI3QaRs4TnoRk\
  AARYwoLLungWCrLHKxLlZMGkQbx%2FlxCTV3K39uZEiVl9CwHCwQp%2BIvz1U6Z26KAxPNgAqBnxp\
  hc5IjLTM3tDC2k6rdJzFCw1dF8tvccgTT%2Fs7OCdpDO%2FWzlc0fOiNMcnCSpA9i5rq5hZnBRE6R\
  42b2tJjQ80ls68jCyKQ387lQAL4a3NL0DxvFqvyInoBVNU7sQhhV38uRpV&X-Amz-Signature=69\
  0ce29f4b5297a7d3940bd5bf7292b5afcf545cad4d1240763666bce2140ecb&X-Amz-SignedHe\
  aders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466YMSZO2NZ%2F20250219%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250219T132729Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJHMEUCIGB2VSEkeImRYKdxCJrHw%2Fim7LvCv\
        7klzz5CINVTjyOhAiEA3gke7cjALywDoS%2FWFaI0vRG9jsmVZILcPwXDdenNRLYqiAQIpP\
        %2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOHmSpW1ptmgxmGev\
        yrcA3z7uIUvAn6aFS24sWFS7GAGdY9JhCC45J3tahRB4Gh9hZ4NQF%2B1Inc5QoZjBZRiOC\
        9IksPhH9BN3po2LUStqZeEEGczYAkbCmPCHvsyja4MmhjnVnbScKRGFB2uZ8opCKh%2FXbp\
        U4tHVAOdR7nBjEB9nSBXUI%2FuRE99X%2BJS%2BAuCgeZszSghXJuSrJjM9mknDQcYt99gT\
        ZtxFcQBySn%2BFP7s7n6PbhppznDypq9XBWpCm9HeWGPSrMr2gI8LZ0oOesAM7NHLkesrpI\
        WPSTOBD1DJL0v5NcPl02ih8Z6IcPzsal8xoKIvN5gNiZ0V%2BzwbpbjmKW2TDqWrSjNsoWL\
        dW%2FxROqxRkDBRpirrnjhZe%2FzxFUrhk6KgL%2FvyxSpwHfmEFxgp7ciZVTxy85TcbkIg\
        t8WtXK%2BRsBHehtR%2FpCoOunHsfZzKOpLf7oFa5Ja4F7HNnKdASIBAI0DbZnVNxqujA%2\
        FOcouvtyvcjdWXit1LyqAV6JpN22OZfKiIvNGd4I2NPzoLWyL7N%2FjRBaz4dWk7gMI%2F9\
        61xjtV3I9P9YXcsr3B5tbvvY%2B2D8jGHmgwQ%2FvSkkduBIhAw0FG3acneC4G%2BE5bjLv\
        HsTGAuz5HDbfL874TGuT0Au4FQQ7%2BrOH4ccCMLX71r0GOqUBnZi6%2BOiEZTbGvS7DuPo\
        2cQ4HswJCOgwfxXWMIDwviWBbjkdl1Xi2WUUQHBWrEtdo7fCP97NVAs4fbTXpytqGsXsjp4\
        af58oA0DLoc2n41WSlvpgjchX7ezRpO1gvjteWnHpftBsnV1Vq3m0bFlArI7zEI%2Bdqt%2\
        B2jewLqFQ33zc1%2Bt1fSR7AtF7UgUShoUv0ErIpRfMT%2BKRfQVDaM652ZaDlTwTVR&X-A\
        mz-Signature=6c6dc35a5e2c861fe92da38ed65cab682dab0abda07775ef6d3ed1dde8\
        64b9af&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-19T14:27:29.042Z"
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
UPDATE_TIME: "2025-02-19T13:29:10.210Z"
EXPIRY_TIME: "2025-02-19T14:28:52.201Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664NWEE7DB%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T132852Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJGMEQCIAzqTU0vQk%2FPIObWo2SjPWW0d6amhUtgKHgILxgsjyIMAiAAot%2F357T0o4MMRGfPYkC65j%2B83V7I2uJZUUYT3FWmdiqIBAik%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM9J2tlJz3rWcdZBCIKtwDS92drMDH8Xo05Km0wrsb4DGkAK1TDnyH9mT%2Fn8iky3wAsrmBfPEZFk0LJm%2BWQS4zQUTo1VIfH5nEpkmfsQLy8Vw4%2F4tKKPYcH%2FS1s1pcsFwbxD%2F5BQFVjy1HkBQSiZjd0nXi%2FwP1gXzk3bXn7VRTo1%2BMXbUyEVD%2B0zwONPDjoBTAXIN04rar6CtTRPRXPk0KLP%2BfzVywCQ6TYcleDmh%2BLthEnvvtlcy3qckaTa%2FpKZy0JnfL2h922djPGa%2FSx52ZTQFFetRL%2FqUYhh6xjXguaKRU62HcuLS7yioLvlzNK1mjvm3cOVfjG0ZYPZHgC7tjKoLJBmRbvA8FWCnXvKcFUnaStSP7HsfVv9lAihsbbCfpbw3%2FD0dt%2BZbebF2%2BjHsSPJg%2FZNflyPZXqyiSETSIoSXrpezU2ykjJBc8ndQohuVHbt9yrzBl41ulxaQin1DDnB4KNrTAhCqGGq089aDTkBvC6hx8Uh9w7cpHbtG6G3%2BjAOienWYdgRpEWlEYg22U6sVA4PZr%2FECztvfSVQ6OyPNVll67nlefNHselYOwyu6Ty0x28iSphBxfBudcbJRCx%2FVSUy4aHhPwDTWWLW%2FIMzpmIkczaWn3wBQkqnNpAb6x2Y0y2sy5YeE0JbIwnfvWvQY6pgHxs9HnznHArJHh9Zzs7sxzLwlXk9Q5tlexfZSpdQoTS47ep6T2g8cMLlSDbLkDjdU7m%2B4bhgPsMsl8KbgCD1HFYhmVxe175RiaGs6mza3ugzRf1WydiNefZFKVA6rxnx6hKmfxms5WH87KPmjU5iTOlJYdEgR4Ij95WwN9HF%2BRNnHUzyFsRxLPw6FSsfnV7cvl76FZKl%2BseiVm0Vi1i4XJ%2FrRJGm2X&X-Amz-Signature=7812746ebd9d52ad99fa1f19818f7184a1ac63b626cfb3b1ac5e81917364ef53&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664NWEE7DB%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T132852Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJGMEQCIAzqTU0vQk%2FPIObWo2SjPWW0d6amhUtgKHgILxgsjyIMAiAAot%2F357T0o4MMRGfPYkC65j%2B83V7I2uJZUUYT3FWmdiqIBAik%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM9J2tlJz3rWcdZBCIKtwDS92drMDH8Xo05Km0wrsb4DGkAK1TDnyH9mT%2Fn8iky3wAsrmBfPEZFk0LJm%2BWQS4zQUTo1VIfH5nEpkmfsQLy8Vw4%2F4tKKPYcH%2FS1s1pcsFwbxD%2F5BQFVjy1HkBQSiZjd0nXi%2FwP1gXzk3bXn7VRTo1%2BMXbUyEVD%2B0zwONPDjoBTAXIN04rar6CtTRPRXPk0KLP%2BfzVywCQ6TYcleDmh%2BLthEnvvtlcy3qckaTa%2FpKZy0JnfL2h922djPGa%2FSx52ZTQFFetRL%2FqUYhh6xjXguaKRU62HcuLS7yioLvlzNK1mjvm3cOVfjG0ZYPZHgC7tjKoLJBmRbvA8FWCnXvKcFUnaStSP7HsfVv9lAihsbbCfpbw3%2FD0dt%2BZbebF2%2BjHsSPJg%2FZNflyPZXqyiSETSIoSXrpezU2ykjJBc8ndQohuVHbt9yrzBl41ulxaQin1DDnB4KNrTAhCqGGq089aDTkBvC6hx8Uh9w7cpHbtG6G3%2BjAOienWYdgRpEWlEYg22U6sVA4PZr%2FECztvfSVQ6OyPNVll67nlefNHselYOwyu6Ty0x28iSphBxfBudcbJRCx%2FVSUy4aHhPwDTWWLW%2FIMzpmIkczaWn3wBQkqnNpAb6x2Y0y2sy5YeE0JbIwnfvWvQY6pgHxs9HnznHArJHh9Zzs7sxzLwlXk9Q5tlexfZSpdQoTS47ep6T2g8cMLlSDbLkDjdU7m%2B4bhgPsMsl8KbgCD1HFYhmVxe175RiaGs6mza3ugzRf1WydiNefZFKVA6rxnx6hKmfxms5WH87KPmjU5iTOlJYdEgR4Ij95WwN9HF%2BRNnHUzyFsRxLPw6FSsfnV7cvl76FZKl%2BseiVm0Vi1i4XJ%2FrRJGm2X&X-Amz-Signature=88d66d5aa944c041cca9487410593db240010e8895b25e3d58c52cb7930c671a&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664NWEE7DB%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T132852Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJGMEQCIAzqTU0vQk%2FPIObWo2SjPWW0d6amhUtgKHgILxgsjyIMAiAAot%2F357T0o4MMRGfPYkC65j%2B83V7I2uJZUUYT3FWmdiqIBAik%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM9J2tlJz3rWcdZBCIKtwDS92drMDH8Xo05Km0wrsb4DGkAK1TDnyH9mT%2Fn8iky3wAsrmBfPEZFk0LJm%2BWQS4zQUTo1VIfH5nEpkmfsQLy8Vw4%2F4tKKPYcH%2FS1s1pcsFwbxD%2F5BQFVjy1HkBQSiZjd0nXi%2FwP1gXzk3bXn7VRTo1%2BMXbUyEVD%2B0zwONPDjoBTAXIN04rar6CtTRPRXPk0KLP%2BfzVywCQ6TYcleDmh%2BLthEnvvtlcy3qckaTa%2FpKZy0JnfL2h922djPGa%2FSx52ZTQFFetRL%2FqUYhh6xjXguaKRU62HcuLS7yioLvlzNK1mjvm3cOVfjG0ZYPZHgC7tjKoLJBmRbvA8FWCnXvKcFUnaStSP7HsfVv9lAihsbbCfpbw3%2FD0dt%2BZbebF2%2BjHsSPJg%2FZNflyPZXqyiSETSIoSXrpezU2ykjJBc8ndQohuVHbt9yrzBl41ulxaQin1DDnB4KNrTAhCqGGq089aDTkBvC6hx8Uh9w7cpHbtG6G3%2BjAOienWYdgRpEWlEYg22U6sVA4PZr%2FECztvfSVQ6OyPNVll67nlefNHselYOwyu6Ty0x28iSphBxfBudcbJRCx%2FVSUy4aHhPwDTWWLW%2FIMzpmIkczaWn3wBQkqnNpAb6x2Y0y2sy5YeE0JbIwnfvWvQY6pgHxs9HnznHArJHh9Zzs7sxzLwlXk9Q5tlexfZSpdQoTS47ep6T2g8cMLlSDbLkDjdU7m%2B4bhgPsMsl8KbgCD1HFYhmVxe175RiaGs6mza3ugzRf1WydiNefZFKVA6rxnx6hKmfxms5WH87KPmjU5iTOlJYdEgR4Ij95WwN9HF%2BRNnHUzyFsRxLPw6FSsfnV7cvl76FZKl%2BseiVm0Vi1i4XJ%2FrRJGm2X&X-Amz-Signature=0a08e267be82b70edf1e48d87e6aecc923531f71c3b6cea7b7e8d576675f2e89&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664NWEE7DB%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T132852Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJGMEQCIAzqTU0vQk%2FPIObWo2SjPWW0d6amhUtgKHgILxgsjyIMAiAAot%2F357T0o4MMRGfPYkC65j%2B83V7I2uJZUUYT3FWmdiqIBAik%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM9J2tlJz3rWcdZBCIKtwDS92drMDH8Xo05Km0wrsb4DGkAK1TDnyH9mT%2Fn8iky3wAsrmBfPEZFk0LJm%2BWQS4zQUTo1VIfH5nEpkmfsQLy8Vw4%2F4tKKPYcH%2FS1s1pcsFwbxD%2F5BQFVjy1HkBQSiZjd0nXi%2FwP1gXzk3bXn7VRTo1%2BMXbUyEVD%2B0zwONPDjoBTAXIN04rar6CtTRPRXPk0KLP%2BfzVywCQ6TYcleDmh%2BLthEnvvtlcy3qckaTa%2FpKZy0JnfL2h922djPGa%2FSx52ZTQFFetRL%2FqUYhh6xjXguaKRU62HcuLS7yioLvlzNK1mjvm3cOVfjG0ZYPZHgC7tjKoLJBmRbvA8FWCnXvKcFUnaStSP7HsfVv9lAihsbbCfpbw3%2FD0dt%2BZbebF2%2BjHsSPJg%2FZNflyPZXqyiSETSIoSXrpezU2ykjJBc8ndQohuVHbt9yrzBl41ulxaQin1DDnB4KNrTAhCqGGq089aDTkBvC6hx8Uh9w7cpHbtG6G3%2BjAOienWYdgRpEWlEYg22U6sVA4PZr%2FECztvfSVQ6OyPNVll67nlefNHselYOwyu6Ty0x28iSphBxfBudcbJRCx%2FVSUy4aHhPwDTWWLW%2FIMzpmIkczaWn3wBQkqnNpAb6x2Y0y2sy5YeE0JbIwnfvWvQY6pgHxs9HnznHArJHh9Zzs7sxzLwlXk9Q5tlexfZSpdQoTS47ep6T2g8cMLlSDbLkDjdU7m%2B4bhgPsMsl8KbgCD1HFYhmVxe175RiaGs6mza3ugzRf1WydiNefZFKVA6rxnx6hKmfxms5WH87KPmjU5iTOlJYdEgR4Ij95WwN9HF%2BRNnHUzyFsRxLPw6FSsfnV7cvl76FZKl%2BseiVm0Vi1i4XJ%2FrRJGm2X&X-Amz-Signature=ebbb981725fb8f87a98d5cbf8ff206fcc416444674552f268801853917ab33b1&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664NWEE7DB%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T132852Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJGMEQCIAzqTU0vQk%2FPIObWo2SjPWW0d6amhUtgKHgILxgsjyIMAiAAot%2F357T0o4MMRGfPYkC65j%2B83V7I2uJZUUYT3FWmdiqIBAik%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM9J2tlJz3rWcdZBCIKtwDS92drMDH8Xo05Km0wrsb4DGkAK1TDnyH9mT%2Fn8iky3wAsrmBfPEZFk0LJm%2BWQS4zQUTo1VIfH5nEpkmfsQLy8Vw4%2F4tKKPYcH%2FS1s1pcsFwbxD%2F5BQFVjy1HkBQSiZjd0nXi%2FwP1gXzk3bXn7VRTo1%2BMXbUyEVD%2B0zwONPDjoBTAXIN04rar6CtTRPRXPk0KLP%2BfzVywCQ6TYcleDmh%2BLthEnvvtlcy3qckaTa%2FpKZy0JnfL2h922djPGa%2FSx52ZTQFFetRL%2FqUYhh6xjXguaKRU62HcuLS7yioLvlzNK1mjvm3cOVfjG0ZYPZHgC7tjKoLJBmRbvA8FWCnXvKcFUnaStSP7HsfVv9lAihsbbCfpbw3%2FD0dt%2BZbebF2%2BjHsSPJg%2FZNflyPZXqyiSETSIoSXrpezU2ykjJBc8ndQohuVHbt9yrzBl41ulxaQin1DDnB4KNrTAhCqGGq089aDTkBvC6hx8Uh9w7cpHbtG6G3%2BjAOienWYdgRpEWlEYg22U6sVA4PZr%2FECztvfSVQ6OyPNVll67nlefNHselYOwyu6Ty0x28iSphBxfBudcbJRCx%2FVSUy4aHhPwDTWWLW%2FIMzpmIkczaWn3wBQkqnNpAb6x2Y0y2sy5YeE0JbIwnfvWvQY6pgHxs9HnznHArJHh9Zzs7sxzLwlXk9Q5tlexfZSpdQoTS47ep6T2g8cMLlSDbLkDjdU7m%2B4bhgPsMsl8KbgCD1HFYhmVxe175RiaGs6mza3ugzRf1WydiNefZFKVA6rxnx6hKmfxms5WH87KPmjU5iTOlJYdEgR4Ij95WwN9HF%2BRNnHUzyFsRxLPw6FSsfnV7cvl76FZKl%2BseiVm0Vi1i4XJ%2FrRJGm2X&X-Amz-Signature=829beb290e8aca6873b8cf7ad28d0ec80582cc19afd55acd893af66c67e8f6d5&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZFV7LX3V%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T132855Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJHMEUCIDZROJXjCXSaTXBc4llE7IuRBVc%2BNK%2F9%2B5eBaTp5CqXsAiEAvSbKSqRE%2B0id4rbJmnVkvEN60SKc2HXhd9EIG7hf4xgqiAQIpP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCZBTkbl5tU%2F89yayyrcA46xusIBcJpqegDLtrPxNyWgi6jtPujznUIxHcs%2F11%2Fey%2ByyATSFEUtwv8sm9N5%2FhQQYAKoMIh9ui368737SgJkYPCsFXhyDuOcyQcu%2F%2Bbc8OQSBD2wTIVA5BekPipa2yVJtWvQ%2FrBJNxytEXStpufeL7l%2B7W9wulSpUOWMpQq6eqz8YZe0Ki0b1L%2FQUjUo%2B0Efp8LANyHOCmH1klE4D0b5yi2j7a%2BBpXIuRAUJnhqcBtiTGri%2Fb6%2FtlWzLSVNDGXVM02pxAQ42fCfMB5q8haNrD9fVohv9JVQ8lg5q6DeHpF1GLy8nxqbZ1UxTMjm2n4SlcLfOPyasH3jPn9MVmgFAUMxDaFNk0XsT%2FQU%2FZQxwJrG%2BPzvP9WY25fcshtWi%2FylrZzk0EtTLvUVhfldh4HSMHvzGVDOrqKsB4TR9kIymlOkiPes8FEsaJuki93f5UskQacM1moLQKOej2vkX7FOCfB3u6eCgdQQbFBfaDJZcbaPr8uk9ORGTjOoNNMBNm5G1r8%2BNyDukSuuWnXgYPvtk61bTE1g2J5A35nhXsv01m9HSbSJ2Lf4WHSRud9gqnr%2BkGQzD5xDkzokaIhDL%2BmYbsh9%2FD5Vur7xA66d7WHPKdRfQKmP6DdkNtxGb2MP361r0GOqUBrZ1PjRm9bpx6njGaokCNB8%2FeQwplNCL2H7T1cR1waZ%2BvfMwtRbSrSzfoeBa88h0shXR3gcAojL23RPjbybVIRMOBRODDlbjQ9xG8Ut6nhMQIcyUcV6Iobb3lxZeZSoytpMNmE0L0eGTTIK%2FQpwcrljGMcrT1VadqmyCnPK343DJBph6LSofBlywvikMDBJhRo00FH91tyIg4IqBjhJWhQgSBrrc9&X-Amz-Signature=b40cad9d6b8bdfdc0f12b30caedab072ec39247a49d48f5c27bff767649101e1&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QMWWTQNA%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T132855Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJIMEYCIQDqfG6GlKxVqs6VCcB0rwNhPTvBUaomFRsE7l7r9qROzQIhALnHc1deJkq4FefGY6ZphNLZGJ4ztxKBYh%2FIVr8GoTwfKogECKT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgytJjmAbv5l6I%2Bi2aQq3AOWVRSXSQ13sAhVb6AF4y41m%2BuDJS9%2Fv6hzprB%2B9gIXLeNyhHRLX9u12j%2BqoXT3svNtR7fvbkTTNm98KDxArsa5bzwJkfgQg2HnBPIqj4YI6aZdmVoRW2fOx%2BbU0hUFLUvemNqSZwO7CSeT3e21PzkgbgV6%2Bu7dP0HL%2FPIWoegJ1fLq%2FQP1e0k0lk%2BCmgEYMpA8Qb2rAbWJi%2BT46kFwm8%2BTeSBIJ1MnSkN1h%2F%2FdFdFjABUgIpNxQAKAoEttMh2nNtj8fb9lXtcn3s6ccDEKfG7bShqgY9tGkloz1GEh3mz08CX3pSlLoeuU7sPd9uEBNJx4Ftc7SlkmSUnrOU7uclIJE36WDo2sY1PbEErBVQeS0cX9%2BCx7mM2Gj%2BSCLFVfy82kGzGEKCHutbCS00zR7hmf9OChmWWMtcuMpDvU66Hfqy%2BnCghy%2FMWgxbqrn7d7uClzuoFPsLvA9DtVYIR%2FPpdADmVNlnr2jBC0D8sCbRsBOy%2BD33clLJpp63AFGIr5Vdc0IUIo5ICj7WSRrkzmOMAT5NMTUccKNVylSQF23hc2DFpgMeyBh9%2BqTL4JljdjutKKiw9c6Km5GAhF%2FxJ6mYU39SydGzVkKnn1spG9Kh1Qvs%2BGGpcf3gUoYm9yBzDV%2Bta9BjqkAXyQwmS8TL%2FFwOZibwc5Qr%2BWWum%2BEoLURoC4FfDX7%2FVFmtQ9kO9R0QYW4BcQcCRJj2D2b3ZSzUsvtr1bC5VLVrregS7ys2DM4kfXmGSx%2BSKlxKFHmftBHFFD6Q3BDgXH9llBxpGgqfkd%2Bq3oT%2BG26LzG5EFyYgM%2B9mFaNats6z86SIbuF21pRGUWCmHHnsjsV81WGuqDNDXY2QMLZ0mGGWUFHduV&X-Amz-Signature=f67b2e0e0d2b50a1dd6b8ff3c639bcf225bb11cff86bb16ff158e442aaf1da51&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664NWEE7DB%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T132852Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJGMEQCIAzqTU0vQk%2FPIObWo2SjPWW0d6amhUtgKHgILxgsjyIMAiAAot%2F357T0o4MMRGfPYkC65j%2B83V7I2uJZUUYT3FWmdiqIBAik%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM9J2tlJz3rWcdZBCIKtwDS92drMDH8Xo05Km0wrsb4DGkAK1TDnyH9mT%2Fn8iky3wAsrmBfPEZFk0LJm%2BWQS4zQUTo1VIfH5nEpkmfsQLy8Vw4%2F4tKKPYcH%2FS1s1pcsFwbxD%2F5BQFVjy1HkBQSiZjd0nXi%2FwP1gXzk3bXn7VRTo1%2BMXbUyEVD%2B0zwONPDjoBTAXIN04rar6CtTRPRXPk0KLP%2BfzVywCQ6TYcleDmh%2BLthEnvvtlcy3qckaTa%2FpKZy0JnfL2h922djPGa%2FSx52ZTQFFetRL%2FqUYhh6xjXguaKRU62HcuLS7yioLvlzNK1mjvm3cOVfjG0ZYPZHgC7tjKoLJBmRbvA8FWCnXvKcFUnaStSP7HsfVv9lAihsbbCfpbw3%2FD0dt%2BZbebF2%2BjHsSPJg%2FZNflyPZXqyiSETSIoSXrpezU2ykjJBc8ndQohuVHbt9yrzBl41ulxaQin1DDnB4KNrTAhCqGGq089aDTkBvC6hx8Uh9w7cpHbtG6G3%2BjAOienWYdgRpEWlEYg22U6sVA4PZr%2FECztvfSVQ6OyPNVll67nlefNHselYOwyu6Ty0x28iSphBxfBudcbJRCx%2FVSUy4aHhPwDTWWLW%2FIMzpmIkczaWn3wBQkqnNpAb6x2Y0y2sy5YeE0JbIwnfvWvQY6pgHxs9HnznHArJHh9Zzs7sxzLwlXk9Q5tlexfZSpdQoTS47ep6T2g8cMLlSDbLkDjdU7m%2B4bhgPsMsl8KbgCD1HFYhmVxe175RiaGs6mza3ugzRf1WydiNefZFKVA6rxnx6hKmfxms5WH87KPmjU5iTOlJYdEgR4Ij95WwN9HF%2BRNnHUzyFsRxLPw6FSsfnV7cvl76FZKl%2BseiVm0Vi1i4XJ%2FrRJGm2X&X-Amz-Signature=6c719c4d299724e82116b5c863061b2485243812ed4d83dcc34494bda287eda4&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664NWEE7DB%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T132852Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJGMEQCIAzqTU0vQk%2FPIObWo2SjPWW0d6amhUtgKHgILxgsjyIMAiAAot%2F357T0o4MMRGfPYkC65j%2B83V7I2uJZUUYT3FWmdiqIBAik%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM9J2tlJz3rWcdZBCIKtwDS92drMDH8Xo05Km0wrsb4DGkAK1TDnyH9mT%2Fn8iky3wAsrmBfPEZFk0LJm%2BWQS4zQUTo1VIfH5nEpkmfsQLy8Vw4%2F4tKKPYcH%2FS1s1pcsFwbxD%2F5BQFVjy1HkBQSiZjd0nXi%2FwP1gXzk3bXn7VRTo1%2BMXbUyEVD%2B0zwONPDjoBTAXIN04rar6CtTRPRXPk0KLP%2BfzVywCQ6TYcleDmh%2BLthEnvvtlcy3qckaTa%2FpKZy0JnfL2h922djPGa%2FSx52ZTQFFetRL%2FqUYhh6xjXguaKRU62HcuLS7yioLvlzNK1mjvm3cOVfjG0ZYPZHgC7tjKoLJBmRbvA8FWCnXvKcFUnaStSP7HsfVv9lAihsbbCfpbw3%2FD0dt%2BZbebF2%2BjHsSPJg%2FZNflyPZXqyiSETSIoSXrpezU2ykjJBc8ndQohuVHbt9yrzBl41ulxaQin1DDnB4KNrTAhCqGGq089aDTkBvC6hx8Uh9w7cpHbtG6G3%2BjAOienWYdgRpEWlEYg22U6sVA4PZr%2FECztvfSVQ6OyPNVll67nlefNHselYOwyu6Ty0x28iSphBxfBudcbJRCx%2FVSUy4aHhPwDTWWLW%2FIMzpmIkczaWn3wBQkqnNpAb6x2Y0y2sy5YeE0JbIwnfvWvQY6pgHxs9HnznHArJHh9Zzs7sxzLwlXk9Q5tlexfZSpdQoTS47ep6T2g8cMLlSDbLkDjdU7m%2B4bhgPsMsl8KbgCD1HFYhmVxe175RiaGs6mza3ugzRf1WydiNefZFKVA6rxnx6hKmfxms5WH87KPmjU5iTOlJYdEgR4Ij95WwN9HF%2BRNnHUzyFsRxLPw6FSsfnV7cvl76FZKl%2BseiVm0Vi1i4XJ%2FrRJGm2X&X-Amz-Signature=8cdaf965a504e8f93f8ff8282e7ff6f3e64e433bba95432a1d2d72531e04e12b&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664NWEE7DB%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T132852Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJGMEQCIAzqTU0vQk%2FPIObWo2SjPWW0d6amhUtgKHgILxgsjyIMAiAAot%2F357T0o4MMRGfPYkC65j%2B83V7I2uJZUUYT3FWmdiqIBAik%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM9J2tlJz3rWcdZBCIKtwDS92drMDH8Xo05Km0wrsb4DGkAK1TDnyH9mT%2Fn8iky3wAsrmBfPEZFk0LJm%2BWQS4zQUTo1VIfH5nEpkmfsQLy8Vw4%2F4tKKPYcH%2FS1s1pcsFwbxD%2F5BQFVjy1HkBQSiZjd0nXi%2FwP1gXzk3bXn7VRTo1%2BMXbUyEVD%2B0zwONPDjoBTAXIN04rar6CtTRPRXPk0KLP%2BfzVywCQ6TYcleDmh%2BLthEnvvtlcy3qckaTa%2FpKZy0JnfL2h922djPGa%2FSx52ZTQFFetRL%2FqUYhh6xjXguaKRU62HcuLS7yioLvlzNK1mjvm3cOVfjG0ZYPZHgC7tjKoLJBmRbvA8FWCnXvKcFUnaStSP7HsfVv9lAihsbbCfpbw3%2FD0dt%2BZbebF2%2BjHsSPJg%2FZNflyPZXqyiSETSIoSXrpezU2ykjJBc8ndQohuVHbt9yrzBl41ulxaQin1DDnB4KNrTAhCqGGq089aDTkBvC6hx8Uh9w7cpHbtG6G3%2BjAOienWYdgRpEWlEYg22U6sVA4PZr%2FECztvfSVQ6OyPNVll67nlefNHselYOwyu6Ty0x28iSphBxfBudcbJRCx%2FVSUy4aHhPwDTWWLW%2FIMzpmIkczaWn3wBQkqnNpAb6x2Y0y2sy5YeE0JbIwnfvWvQY6pgHxs9HnznHArJHh9Zzs7sxzLwlXk9Q5tlexfZSpdQoTS47ep6T2g8cMLlSDbLkDjdU7m%2B4bhgPsMsl8KbgCD1HFYhmVxe175RiaGs6mza3ugzRf1WydiNefZFKVA6rxnx6hKmfxms5WH87KPmjU5iTOlJYdEgR4Ij95WwN9HF%2BRNnHUzyFsRxLPw6FSsfnV7cvl76FZKl%2BseiVm0Vi1i4XJ%2FrRJGm2X&X-Amz-Signature=43a58430b91c03a977c2fceba18f842438eeb19a0fe8589c4842d18c2fed4d3f&X-Amz-SignedHeaders=host&x-id=GetObject)


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

