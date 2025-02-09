---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4663J4Q67VG%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250209T111826Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIAalmS6qO5%2B3an1C6\
  bm1setXstO1d2q5G4FIQtXvWBHuAiEA4nDJWNtcSXpq%2BNuK9HArgweimwvnUe0KcXJJNZksjlsq\
  iAQIov%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMg96gmOLtzT2ifd1\
  CrcAzrDowCL%2BlMAk7W109IcYO8G4BEobIbkR7gQFidaaBQbWjt7xrNVq3m9GfzSLfDtIRw8ZM%2\
  BiH%2Fev56F46yeFxRS2j6R4BUszRs%2BGrcJN3L%2FcLa1HWDVVqjbUGUyrVYVC65KiT4gGQiom0\
  dvRyJKJ2VyeUYoT9KqA8aTE1eIB42s1SCVpMJoUSO5ZsiOrrPA4sadW1BuYn7DcW9%2B2GdJof0Sv\
  c5cLREvVkiWE0eGlKGQVZERziCD2swEdHL9CBW3zsg43w5i6u9DWdTi0VEboT1cqWHH8b2Xx7j3M6\
  f7Qq77gxsmpT%2FMcJnPC1kMuLhdezu5fdy17tmklX5%2Boj4kWgD2i6yKYJLROgnm3VVMJjLN%2F\
  thiJXKCaYKnA2a46joIsJGYYts0AKJ4CHi%2BIJYcO7t1pDRZ%2BJLhJJh5rtQbqRothXas30TbiP\
  DdrQTbGScK5nW9%2B1hBSK0XgCcIj9EuOtHiTcwkG9fDPJjGV4pbESwRfFlsOR3dXB7wXt35JBMpX\
  NTkyBEaeoYpm%2Bpz1zObkLZhtrpMSnU%2BgIQzjwFIlRsfSSJGmlWbpE76oxLbN%2FEtBJoh8M1A\
  Moh1ScFsj8yo3989NIPS7xyZmFoJXp1z32aUOVI%2FsHNnDtujGl%2BarMM%2Fjob0GOqUBbZ7OUO\
  rVa7S09cEZ1%2BZ2X%2FJWN3orrL6w1U2Hyefm3FBh362cvcaCjDBh45HL9JqSZWu4xdJkghJq9%2\
  FmJvlLanMNhoNEgasBG2%2BeKeD%2BBAXK0ZAEcX26WSZhj1im7SlNPTwBU7Q06xl32p7NuNfDSC%\
  2B%2BQPNGzAYfMJDEXhw8xVM9l1cDuKEFDgWQqPoJV3wY%2BsSTDIEO4Dq8UXxiv2Be6S3HbXd5Q&\
  X-Amz-Signature=a4ca199d338a2c2894af29466dd2ffcd2f384e75cd6818259f5593a9a1c40\
  62f&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466Y2KJVOXG%2F20250209%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250209T111721Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIF6Whc507FXFZA7g%2BkanNi6dUcFPST%2FicNbtMzxPrFWlAiEAgU5DBfwsqJyqmDF2vl\
        lj%2F6dMlzATvMKrMwnvEJ9KpJwqiAQIov%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw\
        2Mzc0MjMxODM4MDUiDDB9igNQe42QQicuiSrcA5W5FasoJgWEIhGUQcKTguI1UMD186or3S\
        fLIO2oOGrNXxJpoMMddvYDfGjNkXjMMa6JgW4bm3p7IwyUxLTHcXYUI7poDYVovCdt7E04V\
        t07%2BkGWVemQF%2BcegnTJ4B841LHfB0usaC5Q1sxZPiVgSw4JAO8sLgZgzTLgvUlQZo4D\
        QhvShUfd3eWfSxMIYRaPu7f26SoewIGFXWwWze1HPuhq2BNznHiClnu8w3iz0OvImm7USgC\
        z7muzM%2B%2B0fxIYCqGKh4VTdc1MNzjduaZGmCztVZR9H5IIeiVFPeAOdLVy0O9%2Fb9hN\
        v6Eu7ixxcZP%2FdkaM4tsx1xZVIt5SPTrHjtlJCs9kJEBCfpN8gDs3mfQxANS2WD7QfvLai\
        7DHlpBAgdNMJDvF0ZM8gaDaE1DGAMw4xn5qtSb68pq6wyqx%2FSp%2BCpLWTr8STqGcB6Et\
        C1R6PIbJjClC5Q8lcHEpluQljk7Gu1mG6be0QgtMnpOcg0X3CAzjjX%2FKjUP%2FupRuqLF\
        QrGmTBWn5ZeW5PHumtOGnRCEhzxnHDt0N4WlFHmpFpZVJYO%2Bs6RanjsNTMbcAiKhUrTFv\
        XFI8aWhE7Xb7xNKstXGdeVxz8GhmlqZ9wRHeXNAJwuA13cEar04eR9MhMOvkob0GOqUBoyf\
        Ja38a56Dk65Uev8S%2BOAj4C1%2BUeCmWvSeU0ABXnXNwihfT5KiAquI%2BvXu9tFeYD5T%\
        2BXsWbBXvyFeIAHc8D4OV3gpDd%2BrFN7vCeGHO%2F91jzcE8ANyCwUDsx9uESrY%2BwWXS\
        Phl97333UPlCWC2O%2B8OYKbl%2F7BF%2BtO%2BTt32bh%2BEr%2F34qMURJv72Ri%2FDpj\
        D6AakAc8tP7iB%2FEsFlWda%2FqDS5Z8bfsE&X-Amz-Signature=7093d59d520c0a2cc5\
        635695e005cc4f0c2f0b802c8a5ecc36f8753e4f4a9294&X-Amz-SignedHeaders=host\
        &x-id=GetObject"
      expiry_time: "2025-02-09T12:17:21.701Z"
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
UPDATE_TIME: "2025-02-09T11:18:29.986Z"
EXPIRY_TIME: "2025-02-09T12:18:22.521Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YQGCQ7GV%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T111822Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCeIGi8yuwgC1dE8Ch90Sf63%2BzSzbV7e%2FQAzd5bPJTrgAIhANQMIstt8Fuc7iiteOwzjQMoak2rnn0w3Lj9UbLbrXWrKogECKL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzVuur9z7Ar0V9TiEMq3APkiL6VwfLUNYU190La9HYyH6KhRuRwv21jhLwRk7JkepPjqtL8Gr0hABiXWy0DrR0IrJyYmkTRlJB%2BrKJlvSLIiDS6RB57R213VQt%2BHDxlOjwDP3HHKxgYvADH%2BsRWiXdK5kiAAoELPGIIGhuXRCpKT1cU1pTsWiJNyNN9Vf2WSiXqMxTe%2BUunOJTgvFvPpcfzZZcw10izkn2OWZa5%2FzNR8qo5d0Mzw9ICDofFpOsGu8TkXaWjpIkV%2BBiWDC4hBglNAXj068f8M8eQO8HBapagzlN%2F%2BfLrIUTrzaCjf%2Fnda%2FQ6r6FlBntH8rZ2aaAK7toxNgd4NxDf1eBCA6vwBAj4yx4ZN%2Fp9XTt9JKWbyY5xqMev4MqvLvsjN68OtfLZchxNHG2LvgFnCkmJKtoOaP0%2FKtgq7%2FzaseBj0m0N%2BXwHqKoozIzZ0Bj9xf5fIO8G0mx8Wd01v%2Bk5eOCzr5YWEEV5Rv4%2FeH5OxxllVHKRoc7v%2BnEhbwetJ7tkCAaShosmgjiFuh3eBCnjKg9j4qtjyvw8jnyohHbVrDDaWwVGl4Uw7%2FrG5VwLJ%2BxA7HvibZ%2BUCkDM9cSeBf%2BG6saXxNW0NMyVbPabqUhBAYuOKzZDVyP8hJyY46lqZkppzLyIFTD246G9BjqkAZ6eXVdJmD5L2UN02cfJCsbt%2B%2F57rh2I6quyPe65Wr8mAxLMDdUzXUHNf9cdj4jHGAsmn2Vr0QAuwF3CgjsU05Ygq6O2aX6IiOq0blY%2FPyb5FYcHd49diwC3HuRQs7XhH0%2FruAPkciWTcafxa73y4THaxxAx87vquhkDsELk1BhdlIopGUDK1GxrhXl8cqxJ2MahRknZna1LZtfaranTnaEHUTAz&X-Amz-Signature=f26c2e0887ab551c00619e36abe914fd81682d05d1f999854efd5928e81d71ea&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YQGCQ7GV%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T111822Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCeIGi8yuwgC1dE8Ch90Sf63%2BzSzbV7e%2FQAzd5bPJTrgAIhANQMIstt8Fuc7iiteOwzjQMoak2rnn0w3Lj9UbLbrXWrKogECKL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzVuur9z7Ar0V9TiEMq3APkiL6VwfLUNYU190La9HYyH6KhRuRwv21jhLwRk7JkepPjqtL8Gr0hABiXWy0DrR0IrJyYmkTRlJB%2BrKJlvSLIiDS6RB57R213VQt%2BHDxlOjwDP3HHKxgYvADH%2BsRWiXdK5kiAAoELPGIIGhuXRCpKT1cU1pTsWiJNyNN9Vf2WSiXqMxTe%2BUunOJTgvFvPpcfzZZcw10izkn2OWZa5%2FzNR8qo5d0Mzw9ICDofFpOsGu8TkXaWjpIkV%2BBiWDC4hBglNAXj068f8M8eQO8HBapagzlN%2F%2BfLrIUTrzaCjf%2Fnda%2FQ6r6FlBntH8rZ2aaAK7toxNgd4NxDf1eBCA6vwBAj4yx4ZN%2Fp9XTt9JKWbyY5xqMev4MqvLvsjN68OtfLZchxNHG2LvgFnCkmJKtoOaP0%2FKtgq7%2FzaseBj0m0N%2BXwHqKoozIzZ0Bj9xf5fIO8G0mx8Wd01v%2Bk5eOCzr5YWEEV5Rv4%2FeH5OxxllVHKRoc7v%2BnEhbwetJ7tkCAaShosmgjiFuh3eBCnjKg9j4qtjyvw8jnyohHbVrDDaWwVGl4Uw7%2FrG5VwLJ%2BxA7HvibZ%2BUCkDM9cSeBf%2BG6saXxNW0NMyVbPabqUhBAYuOKzZDVyP8hJyY46lqZkppzLyIFTD246G9BjqkAZ6eXVdJmD5L2UN02cfJCsbt%2B%2F57rh2I6quyPe65Wr8mAxLMDdUzXUHNf9cdj4jHGAsmn2Vr0QAuwF3CgjsU05Ygq6O2aX6IiOq0blY%2FPyb5FYcHd49diwC3HuRQs7XhH0%2FruAPkciWTcafxa73y4THaxxAx87vquhkDsELk1BhdlIopGUDK1GxrhXl8cqxJ2MahRknZna1LZtfaranTnaEHUTAz&X-Amz-Signature=f88df76a66cf023b24b48c898221978577df7ce428d0f12e27267a527b198cc3&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YQGCQ7GV%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T111822Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCeIGi8yuwgC1dE8Ch90Sf63%2BzSzbV7e%2FQAzd5bPJTrgAIhANQMIstt8Fuc7iiteOwzjQMoak2rnn0w3Lj9UbLbrXWrKogECKL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzVuur9z7Ar0V9TiEMq3APkiL6VwfLUNYU190La9HYyH6KhRuRwv21jhLwRk7JkepPjqtL8Gr0hABiXWy0DrR0IrJyYmkTRlJB%2BrKJlvSLIiDS6RB57R213VQt%2BHDxlOjwDP3HHKxgYvADH%2BsRWiXdK5kiAAoELPGIIGhuXRCpKT1cU1pTsWiJNyNN9Vf2WSiXqMxTe%2BUunOJTgvFvPpcfzZZcw10izkn2OWZa5%2FzNR8qo5d0Mzw9ICDofFpOsGu8TkXaWjpIkV%2BBiWDC4hBglNAXj068f8M8eQO8HBapagzlN%2F%2BfLrIUTrzaCjf%2Fnda%2FQ6r6FlBntH8rZ2aaAK7toxNgd4NxDf1eBCA6vwBAj4yx4ZN%2Fp9XTt9JKWbyY5xqMev4MqvLvsjN68OtfLZchxNHG2LvgFnCkmJKtoOaP0%2FKtgq7%2FzaseBj0m0N%2BXwHqKoozIzZ0Bj9xf5fIO8G0mx8Wd01v%2Bk5eOCzr5YWEEV5Rv4%2FeH5OxxllVHKRoc7v%2BnEhbwetJ7tkCAaShosmgjiFuh3eBCnjKg9j4qtjyvw8jnyohHbVrDDaWwVGl4Uw7%2FrG5VwLJ%2BxA7HvibZ%2BUCkDM9cSeBf%2BG6saXxNW0NMyVbPabqUhBAYuOKzZDVyP8hJyY46lqZkppzLyIFTD246G9BjqkAZ6eXVdJmD5L2UN02cfJCsbt%2B%2F57rh2I6quyPe65Wr8mAxLMDdUzXUHNf9cdj4jHGAsmn2Vr0QAuwF3CgjsU05Ygq6O2aX6IiOq0blY%2FPyb5FYcHd49diwC3HuRQs7XhH0%2FruAPkciWTcafxa73y4THaxxAx87vquhkDsELk1BhdlIopGUDK1GxrhXl8cqxJ2MahRknZna1LZtfaranTnaEHUTAz&X-Amz-Signature=d2817f374ab43cc2d3d7d60551a7c76112b22c2e51a662b6d36a8107b24ebb91&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YQGCQ7GV%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T111822Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCeIGi8yuwgC1dE8Ch90Sf63%2BzSzbV7e%2FQAzd5bPJTrgAIhANQMIstt8Fuc7iiteOwzjQMoak2rnn0w3Lj9UbLbrXWrKogECKL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzVuur9z7Ar0V9TiEMq3APkiL6VwfLUNYU190La9HYyH6KhRuRwv21jhLwRk7JkepPjqtL8Gr0hABiXWy0DrR0IrJyYmkTRlJB%2BrKJlvSLIiDS6RB57R213VQt%2BHDxlOjwDP3HHKxgYvADH%2BsRWiXdK5kiAAoELPGIIGhuXRCpKT1cU1pTsWiJNyNN9Vf2WSiXqMxTe%2BUunOJTgvFvPpcfzZZcw10izkn2OWZa5%2FzNR8qo5d0Mzw9ICDofFpOsGu8TkXaWjpIkV%2BBiWDC4hBglNAXj068f8M8eQO8HBapagzlN%2F%2BfLrIUTrzaCjf%2Fnda%2FQ6r6FlBntH8rZ2aaAK7toxNgd4NxDf1eBCA6vwBAj4yx4ZN%2Fp9XTt9JKWbyY5xqMev4MqvLvsjN68OtfLZchxNHG2LvgFnCkmJKtoOaP0%2FKtgq7%2FzaseBj0m0N%2BXwHqKoozIzZ0Bj9xf5fIO8G0mx8Wd01v%2Bk5eOCzr5YWEEV5Rv4%2FeH5OxxllVHKRoc7v%2BnEhbwetJ7tkCAaShosmgjiFuh3eBCnjKg9j4qtjyvw8jnyohHbVrDDaWwVGl4Uw7%2FrG5VwLJ%2BxA7HvibZ%2BUCkDM9cSeBf%2BG6saXxNW0NMyVbPabqUhBAYuOKzZDVyP8hJyY46lqZkppzLyIFTD246G9BjqkAZ6eXVdJmD5L2UN02cfJCsbt%2B%2F57rh2I6quyPe65Wr8mAxLMDdUzXUHNf9cdj4jHGAsmn2Vr0QAuwF3CgjsU05Ygq6O2aX6IiOq0blY%2FPyb5FYcHd49diwC3HuRQs7XhH0%2FruAPkciWTcafxa73y4THaxxAx87vquhkDsELk1BhdlIopGUDK1GxrhXl8cqxJ2MahRknZna1LZtfaranTnaEHUTAz&X-Amz-Signature=a68c3143d286bc3a2644700a0c1aa5307c6615e33cb784c562c2660453c2323c&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YQGCQ7GV%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T111822Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCeIGi8yuwgC1dE8Ch90Sf63%2BzSzbV7e%2FQAzd5bPJTrgAIhANQMIstt8Fuc7iiteOwzjQMoak2rnn0w3Lj9UbLbrXWrKogECKL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzVuur9z7Ar0V9TiEMq3APkiL6VwfLUNYU190La9HYyH6KhRuRwv21jhLwRk7JkepPjqtL8Gr0hABiXWy0DrR0IrJyYmkTRlJB%2BrKJlvSLIiDS6RB57R213VQt%2BHDxlOjwDP3HHKxgYvADH%2BsRWiXdK5kiAAoELPGIIGhuXRCpKT1cU1pTsWiJNyNN9Vf2WSiXqMxTe%2BUunOJTgvFvPpcfzZZcw10izkn2OWZa5%2FzNR8qo5d0Mzw9ICDofFpOsGu8TkXaWjpIkV%2BBiWDC4hBglNAXj068f8M8eQO8HBapagzlN%2F%2BfLrIUTrzaCjf%2Fnda%2FQ6r6FlBntH8rZ2aaAK7toxNgd4NxDf1eBCA6vwBAj4yx4ZN%2Fp9XTt9JKWbyY5xqMev4MqvLvsjN68OtfLZchxNHG2LvgFnCkmJKtoOaP0%2FKtgq7%2FzaseBj0m0N%2BXwHqKoozIzZ0Bj9xf5fIO8G0mx8Wd01v%2Bk5eOCzr5YWEEV5Rv4%2FeH5OxxllVHKRoc7v%2BnEhbwetJ7tkCAaShosmgjiFuh3eBCnjKg9j4qtjyvw8jnyohHbVrDDaWwVGl4Uw7%2FrG5VwLJ%2BxA7HvibZ%2BUCkDM9cSeBf%2BG6saXxNW0NMyVbPabqUhBAYuOKzZDVyP8hJyY46lqZkppzLyIFTD246G9BjqkAZ6eXVdJmD5L2UN02cfJCsbt%2B%2F57rh2I6quyPe65Wr8mAxLMDdUzXUHNf9cdj4jHGAsmn2Vr0QAuwF3CgjsU05Ygq6O2aX6IiOq0blY%2FPyb5FYcHd49diwC3HuRQs7XhH0%2FruAPkciWTcafxa73y4THaxxAx87vquhkDsELk1BhdlIopGUDK1GxrhXl8cqxJ2MahRknZna1LZtfaranTnaEHUTAz&X-Amz-Signature=e34e893ea8e4d4da0b9edc5435cc1019e61ee72a582197fa786138c704a98be0&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662L7AKEFC%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T111823Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC9GFJPXzwcDynEEid4rUup45WeW%2FEMnOCuyaNMeYkqHgIhAIrxgKM9agyGeyyUHO89N5uHN%2FcLy1AXfBq3WX7ptRE3KogECKL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyIQwddXJSbwSZtgdoq3APyGfa9zxX%2F33FNLOHRUXzOqABhWMM5%2FGXinVI62mIyxj%2FF34aubi09UDp0T3l8u%2Ff3TswXKAIfjrCpqOPe4grQskozoTl%2FzhsFWD30%2FeuDjPql6Du4p3IuMKWTYHr3nsveqPVISozvoj%2FIqLyJwr2eOvuoNuiJ28fQOobr3slSUtDxg7nBvi%2B94v870A0P12HVr20%2Bz0bicu5w5YVEfhsmoRe4y2oP1IMHZsO0JSl%2FL2AcJzVYdsS%2B5yXkBZVx73306xLPygLssEn4yVF6b2OuwGy0gQhtNrDraeG9HpNZjtRF8twPqGLhjLMvzcNY14tHVbsf6p%2FPNcSTtS0EBj2J%2FnrqQucPyKcd0195XhR2xTw0BVVTQB%2BUbrl3cumXuVJ6KYadUXxtR6wn2OGOhzsfgZO%2FQXJlLtdrjM7O6PETKHUg2A05c4JcPDLXqd85R%2FdU9Qy7Cts%2Fou%2BLY0nx8EnBvP8m%2FqmbjawNe0wu2YXZ78ZgDb1t5lg5Sjpk3nWPREVHZsIowUTZ0br04I%2BeqQLcFWirgGntlvJLGAymbyrnUSOUkoBtNqzGBpOD4Mitki3BaDbw%2FYirBjm%2F18TuzCcEXKVxkAbjSLnkHhZ1Vveorz56nOvRr99vnQ3%2F1jD546G9BjqkAXSsfb3jSZ1Xcim0I6cpzUGwc2VAbhKZpynroGh063b6bSopkLcAyAQbw0XmsQRiny0j%2BDRBXlKQiPwGPGRgN56wq1SzoKTyDQfct01OmAlG9NRu1aov5kx6797X8%2Bkes9NKhizQN1%2FwPPITnyslACd5RFZs0Tst4jLL%2Fzr3e6LXrE1scro8%2ByWjHXlgr3ArV%2F5M3JS0WEGTPlLWV5lWCS96UsWJ&X-Amz-Signature=518e1a2b0c08b2c9d2e89b73bc668c9b9a958298091ec2a18a79b7c6f69dd2be&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TAR6BU4C%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T111824Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCrBJOxq1PxATL1qn1ToVzBh6Zt1o7Lvy4UHDPFAF%2BdWwIhANrhSxLyspuNQixmlAvFfXpx7gpjFnMpI44JLgehulYdKogECKL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyR7eyjNTAT12JmD6Iq3AMdJbuveJS2GggBjUlhACn7C6p984YyskEyaFksnfJfRULatJ3VTne1VRJU0q8Llz7JOWFxcHRcVldcgGc73G0csDtxBj%2BvJ9wKw9Th%2FbsqTrFLm2EYobU6uS0s%2F2%2B8%2BipHaZ7EZAP2WmLIAxkqSSvdMGPu%2BqeTB8wKB7OGHzuwAQE8aNE66uHFAMPaooZf%2BkHTWo1REPkoCSveIBUD9efMkYEE%2BqiQz%2BFpkaGoCna0dYDo2DMNHIx1vbHEDSpN7kGAWQHtwGhR6BSELnROjE%2BAOtyZAszQ6Wdp5ZfQ2fU4eQiA9hJ4%2FCyg72Y6oUpFyo79vhHD6cvgGJpFZcnmldKbrORVtrQ5biQRmq7waxcG96y7gn2XXgnxtOXvExv0Tu6NfsXXC17tAV4WfRp4YBzlnzGLaL2lC7ymWUaqR2wR6RRuLpMfJKEK3WQbaS%2FqWEXWdnaef2fIMZGGDvPAzSzYWbf3Bccrnc5Sjdk7Pn49o5Obtagm0dP0%2FwRbZjpkhIOHhPyy50WF6O0Yk%2B%2FGm4tI4M9CGomZ8R6KRt827fxpNC1%2FLrQxS7MW2YsOwOHfdTzX0DlOWn56GEV7xVo9Rd4GN0RlXcmyfpABu7LzJAhAk5Zs7NJYZzCDqAvpKDDH46G9BjqkAWuLcG%2BHwlU4AU5EszQg3RQ2Ay%2BpvqLO7ojSrNtWttvnymJTMqlesZzUkoy1UBqzfMqyfA448nnOaax%2B1gV4%2FVu98GePYtoRRLediGQET7GzhbDGXwnqfTV%2F9WJ2hj%2BExI0LHp169tA3fqJ%2F7eNydUo03kL8qPJ6FSUI52CgEwFk6yAGBTorvIKTKJo6%2Fhhxk6VjiTM1l1UFL%2BwLOEeHSNaa7u3v&X-Amz-Signature=8617fc013404d915df0551c069a86046755c07a7ccf28a0464eb5e6bdb5be4a1&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YQGCQ7GV%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T111823Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCeIGi8yuwgC1dE8Ch90Sf63%2BzSzbV7e%2FQAzd5bPJTrgAIhANQMIstt8Fuc7iiteOwzjQMoak2rnn0w3Lj9UbLbrXWrKogECKL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzVuur9z7Ar0V9TiEMq3APkiL6VwfLUNYU190La9HYyH6KhRuRwv21jhLwRk7JkepPjqtL8Gr0hABiXWy0DrR0IrJyYmkTRlJB%2BrKJlvSLIiDS6RB57R213VQt%2BHDxlOjwDP3HHKxgYvADH%2BsRWiXdK5kiAAoELPGIIGhuXRCpKT1cU1pTsWiJNyNN9Vf2WSiXqMxTe%2BUunOJTgvFvPpcfzZZcw10izkn2OWZa5%2FzNR8qo5d0Mzw9ICDofFpOsGu8TkXaWjpIkV%2BBiWDC4hBglNAXj068f8M8eQO8HBapagzlN%2F%2BfLrIUTrzaCjf%2Fnda%2FQ6r6FlBntH8rZ2aaAK7toxNgd4NxDf1eBCA6vwBAj4yx4ZN%2Fp9XTt9JKWbyY5xqMev4MqvLvsjN68OtfLZchxNHG2LvgFnCkmJKtoOaP0%2FKtgq7%2FzaseBj0m0N%2BXwHqKoozIzZ0Bj9xf5fIO8G0mx8Wd01v%2Bk5eOCzr5YWEEV5Rv4%2FeH5OxxllVHKRoc7v%2BnEhbwetJ7tkCAaShosmgjiFuh3eBCnjKg9j4qtjyvw8jnyohHbVrDDaWwVGl4Uw7%2FrG5VwLJ%2BxA7HvibZ%2BUCkDM9cSeBf%2BG6saXxNW0NMyVbPabqUhBAYuOKzZDVyP8hJyY46lqZkppzLyIFTD246G9BjqkAZ6eXVdJmD5L2UN02cfJCsbt%2B%2F57rh2I6quyPe65Wr8mAxLMDdUzXUHNf9cdj4jHGAsmn2Vr0QAuwF3CgjsU05Ygq6O2aX6IiOq0blY%2FPyb5FYcHd49diwC3HuRQs7XhH0%2FruAPkciWTcafxa73y4THaxxAx87vquhkDsELk1BhdlIopGUDK1GxrhXl8cqxJ2MahRknZna1LZtfaranTnaEHUTAz&X-Amz-Signature=f7a06d66ef86b605b5730fec60274381c869db6ff5d2dcdca99ce1b29e887514&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YQGCQ7GV%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T111823Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCeIGi8yuwgC1dE8Ch90Sf63%2BzSzbV7e%2FQAzd5bPJTrgAIhANQMIstt8Fuc7iiteOwzjQMoak2rnn0w3Lj9UbLbrXWrKogECKL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzVuur9z7Ar0V9TiEMq3APkiL6VwfLUNYU190La9HYyH6KhRuRwv21jhLwRk7JkepPjqtL8Gr0hABiXWy0DrR0IrJyYmkTRlJB%2BrKJlvSLIiDS6RB57R213VQt%2BHDxlOjwDP3HHKxgYvADH%2BsRWiXdK5kiAAoELPGIIGhuXRCpKT1cU1pTsWiJNyNN9Vf2WSiXqMxTe%2BUunOJTgvFvPpcfzZZcw10izkn2OWZa5%2FzNR8qo5d0Mzw9ICDofFpOsGu8TkXaWjpIkV%2BBiWDC4hBglNAXj068f8M8eQO8HBapagzlN%2F%2BfLrIUTrzaCjf%2Fnda%2FQ6r6FlBntH8rZ2aaAK7toxNgd4NxDf1eBCA6vwBAj4yx4ZN%2Fp9XTt9JKWbyY5xqMev4MqvLvsjN68OtfLZchxNHG2LvgFnCkmJKtoOaP0%2FKtgq7%2FzaseBj0m0N%2BXwHqKoozIzZ0Bj9xf5fIO8G0mx8Wd01v%2Bk5eOCzr5YWEEV5Rv4%2FeH5OxxllVHKRoc7v%2BnEhbwetJ7tkCAaShosmgjiFuh3eBCnjKg9j4qtjyvw8jnyohHbVrDDaWwVGl4Uw7%2FrG5VwLJ%2BxA7HvibZ%2BUCkDM9cSeBf%2BG6saXxNW0NMyVbPabqUhBAYuOKzZDVyP8hJyY46lqZkppzLyIFTD246G9BjqkAZ6eXVdJmD5L2UN02cfJCsbt%2B%2F57rh2I6quyPe65Wr8mAxLMDdUzXUHNf9cdj4jHGAsmn2Vr0QAuwF3CgjsU05Ygq6O2aX6IiOq0blY%2FPyb5FYcHd49diwC3HuRQs7XhH0%2FruAPkciWTcafxa73y4THaxxAx87vquhkDsELk1BhdlIopGUDK1GxrhXl8cqxJ2MahRknZna1LZtfaranTnaEHUTAz&X-Amz-Signature=91117c350f5a33389ae904027de9ca6387eef8d28e330ea0a2e90093beb99ead&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YQGCQ7GV%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T111823Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCeIGi8yuwgC1dE8Ch90Sf63%2BzSzbV7e%2FQAzd5bPJTrgAIhANQMIstt8Fuc7iiteOwzjQMoak2rnn0w3Lj9UbLbrXWrKogECKL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzVuur9z7Ar0V9TiEMq3APkiL6VwfLUNYU190La9HYyH6KhRuRwv21jhLwRk7JkepPjqtL8Gr0hABiXWy0DrR0IrJyYmkTRlJB%2BrKJlvSLIiDS6RB57R213VQt%2BHDxlOjwDP3HHKxgYvADH%2BsRWiXdK5kiAAoELPGIIGhuXRCpKT1cU1pTsWiJNyNN9Vf2WSiXqMxTe%2BUunOJTgvFvPpcfzZZcw10izkn2OWZa5%2FzNR8qo5d0Mzw9ICDofFpOsGu8TkXaWjpIkV%2BBiWDC4hBglNAXj068f8M8eQO8HBapagzlN%2F%2BfLrIUTrzaCjf%2Fnda%2FQ6r6FlBntH8rZ2aaAK7toxNgd4NxDf1eBCA6vwBAj4yx4ZN%2Fp9XTt9JKWbyY5xqMev4MqvLvsjN68OtfLZchxNHG2LvgFnCkmJKtoOaP0%2FKtgq7%2FzaseBj0m0N%2BXwHqKoozIzZ0Bj9xf5fIO8G0mx8Wd01v%2Bk5eOCzr5YWEEV5Rv4%2FeH5OxxllVHKRoc7v%2BnEhbwetJ7tkCAaShosmgjiFuh3eBCnjKg9j4qtjyvw8jnyohHbVrDDaWwVGl4Uw7%2FrG5VwLJ%2BxA7HvibZ%2BUCkDM9cSeBf%2BG6saXxNW0NMyVbPabqUhBAYuOKzZDVyP8hJyY46lqZkppzLyIFTD246G9BjqkAZ6eXVdJmD5L2UN02cfJCsbt%2B%2F57rh2I6quyPe65Wr8mAxLMDdUzXUHNf9cdj4jHGAsmn2Vr0QAuwF3CgjsU05Ygq6O2aX6IiOq0blY%2FPyb5FYcHd49diwC3HuRQs7XhH0%2FruAPkciWTcafxa73y4THaxxAx87vquhkDsELk1BhdlIopGUDK1GxrhXl8cqxJ2MahRknZna1LZtfaranTnaEHUTAz&X-Amz-Signature=df1d9ad1a86015e252c9de7ae18612c526abfc4c988c8456673da4ec7f88198c&X-Amz-SignedHeaders=host&x-id=GetObject)


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

