---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466SZEC27YU%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250216T033007Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjECsaCXVzLXdlc3QtMiJIMEYCIQDJU1Y%2F0sKrXuu6BI5OgiRn1L%2BFdliZ1RURVIuyKjpiVwI\
  hAP7%2BpJU42OCVsP5PCh7d%2B%2F9A6%2BTRLZtVMe1bfik4vFoGKv8DCFQQABoMNjM3NDIzMTgz\
  ODA1Igw98SyyiN8mEsvQvHwq3ANTo5aSAhHCFaRUHJVAp5DwE9IV2nTY%2FXY8JzPvwkzOLKnHtMx\
  JASYTYmC4k%2F0NxsckuSHTbr0uNSdjnrQpGwAXszdGMTwqhc1ZmFgMiTBbbA6Rm%2B87UdeDD1tE\
  dcwPh5%2BT51ppciLoSg2rRPVUtfjWvhVpC6arb%2F7cw%2Bzmqxccg7fkJXPrYHUmH9NiP%2Fusu\
  QFLbBRxfZE5Mx7qGoLvYRbAwKjAJAtXJbK3NqOF279QeyklzTEAjl%2Btec7KZuCVrE3ipWP00y39\
  Wwtw1qjWy23WsLV5Z43tgqnw9Y1ICoS%2Fqm9GvoXCoMPbDlOmcHW6DkyHpVnse%2BKD2wN7moYYQ\
  BhHQ%2BHD3m74NF8jhhutj1DFuqF0t20wTvYShnMIJumVBJm%2BD7NlGzdFrGwrDndQydDsur5goR\
  yW3x%2FoqbTDIcsuNd7%2BHRttrDM00K%2FhYmr%2FfZM%2BImwRQ952dszcXCibtc57vQHUmvgp9\
  FhwerF6WQz17328NZx1jpu8WQoXjiK7GsVdhOGZiMSioRFnQT5R5oMJrD0IuiV3FopHH%2B0pCgKE\
  vqEKqJmflXBhsanv6iPCb6novv3NpW0vyShOQ%2FkTTLu8jgPH5KBRd4VAxQ15syoIO9Az6wYosH3\
  gEi9NKzDiqcW9BjqkAWT%2Bb%2FYvuv2F%2BnjPuuALIDZ%2FxIFCBa9Z%2BkEcxBDu2J6cGTBe6b\
  IBbO9ypw3g911CN1E4HijCo%2FxwV42KhZmeH2gq%2FUpPih97UOLHT%2BU0YgfnFystb4bY%2FS6\
  %2F9WG7IEPbRu72sLOWtjIFWQZOGpUvp1RIFW2vzrpKxiDU4Tw19kVEhgmQonJWqzF3adway7HcN1\
  sy%2BUa%2BKFgKcZjmjyoneuGnvhtN&X-Amz-Signature=1c501e32140e65b74b9970623a3b14\
  4293b9cb8d8fa73b42c1ebb29a24df4ed3&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466SD5PCBAM%2F20250216%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250216T032847Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjECsaCXVzLXdlc3QtMiJIMEYCIQDFpWZKJ5CuS6snIf1mISPdZdxuh4L\
        BcDMkcjQu5nDmRAIhAPH%2FJD%2BKXm8V7GeqPYxqoG6zkU9d2Dg7NoJAnoxONgZ0Kv8DCF\
        QQABoMNjM3NDIzMTgzODA1IgxtE1AA%2BjaCRXQrqaMq3AN9HIR9qcJn%2FU9jUBWnMYCY6\
        SsIwoaa6k2m1dVNOXNaDkuf0DAPO34rWkt9p59q3jecQpDTwhWuaaxzeHZ%2Fu8hj%2F7RQ\
        E1zmJMm2yt7rpYhDtPREL9271oAkg25nGH%2FVIOuqaViknD%2FpzXIKK4bTEIye0JIXpGv\
        SSTnktXHVdVfSkrM8MI4dJyeQumzGv272sp0jEAHoKhGEYW7YXGqAIfWVynn8Q3DP%2F0CD\
        t9jqYNKvhlcGCsoUvP7AzFBzPtOmy%2FoA1egkGm55cxEJMYrF4r%2FABNnCiY%2Fe7u5pg\
        6unKeKojZ3o2yeoMeu%2FBHIx117d2rimCHBue3cD64y2WQDdfFDhMMQ2O1uyb%2BRbuH9X\
        yrM3aKxB8%2BWkyjouIbsEvdGFGdvcEXPkjf75FyDw9rblBv40VpSwl5VrzXJ7K%2FS5HhV\
        s9qq%2FCLDWNuuLJSRxXW46O1%2BxspsqaEmAxgX2UEy3lUcM40OauFHmul7oqyoA6g%2F8\
        1juoKmod0bFQqUOM66cedhVdPIam4nAQL4BY3dmrEdgEWcFE2alG1VHLFEjvhi7lBFKZ8Af\
        o5dRB72mvtBOVEzoi2FZRB172O6SZljieQtjUAVmDmHbCJCWK2AsMViXsPkgMisHUSaTPuT\
        PsFDDiqcW9BjqkAR%2BpNNd7Wzmg4tOH2m5Y2OTXXazSE6HVKC7CLoD3eUqz2tG7kqWxJlf\
        de%2FZsNgms23u9qo2GD1J9hDlkS4CorInuDaT0K%2BS%2B7NOa1DeCSFY5bc9wnsKcBggX\
        vEHXSMjaZ2sHWjcMuAU2UfJLi92L2Ys9o8lwA62OLZAxMU3io%2BXSZgBlfe2Imb9IvUAHT\
        2y1cnWRnwibss%2BHodStvz62SJg1oVfy&X-Amz-Signature=8a192115817099262d22c\
        8aa278283dea9b471ad14d6019580afd2461f53ac6a&X-Amz-SignedHeaders=host&x-\
        id=GetObject"
      expiry_time: "2025-02-16T04:28:46.961Z"
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
UPDATE_TIME: "2025-02-16T03:30:12.030Z"
EXPIRY_TIME: "2025-02-16T04:30:04.345Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XAXEDPPR%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T033004Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECsaCXVzLXdlc3QtMiJIMEYCIQDdVPOf%2B14hc8GZ2W8%2BJPDIjAXfkfiqHmrIwrHuKqJ3dwIhAO8Dn9jZ8mMHgjTKL%2B%2FQwhV8IrQjIVu13GD4H83qRGs6Kv8DCFQQABoMNjM3NDIzMTgzODA1IgxfQydauVFodM3OJJsq3ANpp5ulMU7J9dybj5MEf0yZiml8vI89NLOLgHjjXYwZpA9xTOc8mAAxf2br0EhmgyrfVVQt5z9aNqFh7it%2F9lPMrt4TFsiPGoKITeK6xWUkR2Z3zN4Zj%2FNwIzO86w3hL3mmbFDx%2Bw5IHrm58Y%2B%2FcdBMMlPCkZAPC8r0US6K4UVCRv939dBUQYbGeDrkBmg3gZUMFTQJ95psSP4AONvONlAIk0wRwYsuTqbZ9jle05wYSQKiYD1K8kZrtXTqN4XwJiBDA%2BmpWU6vb0a8VGZDGMvOjZWwQsezuHFG2gHpyuV83csDuCyj7%2BLPbb%2FDjNOSAo%2FUngC8SVbqiTfwSY4%2Fl06KO%2BDLPMgRf9%2B%2BB6n21ldWey2dH6tAW7pXBWswO3F2owHrhBuYo2iAjYnYIE4R%2Bpmdl9f7jHlCKT4nPzR3B4Rj5%2FAp8NnaXFEZVZ3hyIX25OdReNNzzry3Tt97HBA5nDXPUt6K8cAfnOEhgdYRc4s7n2Y2fbN8cvIF%2Fn0cY7cvbV4OGLlWHChCsx%2Bh8nVwL%2B8WJENupGNJ2bYSFCcNR%2FelsaFLpdUH6uTE8Vso6ByaiTE1BCiP28XhU0AnzYfJNVSCjlw64hevp1GG2MWqDV6zSR1qFoOvzaySKtcKPjC4qsW9BjqkAckTTqsbp96Mgr4GtJph8%2FM3A4vHjHwTGxLiJS%2FDyJffnmy%2FXVJKiM6qr9NMXdplLwlecSkRnsP2VQC8lGImjsYX2zxvhID1ePVHjUBWDMFC8QKvNfM4wU6iLBU8uagEGpO1qGpxCXdZ7Qzinouf2UxmyEFisnNZwB%2BF%2Fj9oTRLY2zYNtO45JeW1QkRHLiiFfUj9voJ9b9aeGg0%2BW%2FoRGzmC7SYI&X-Amz-Signature=c990311c8b6dac1f0f5cf3e8b743aea8f92fb5d3744f47b16bbf6dbc9a3d47a6&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XAXEDPPR%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T033004Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECsaCXVzLXdlc3QtMiJIMEYCIQDdVPOf%2B14hc8GZ2W8%2BJPDIjAXfkfiqHmrIwrHuKqJ3dwIhAO8Dn9jZ8mMHgjTKL%2B%2FQwhV8IrQjIVu13GD4H83qRGs6Kv8DCFQQABoMNjM3NDIzMTgzODA1IgxfQydauVFodM3OJJsq3ANpp5ulMU7J9dybj5MEf0yZiml8vI89NLOLgHjjXYwZpA9xTOc8mAAxf2br0EhmgyrfVVQt5z9aNqFh7it%2F9lPMrt4TFsiPGoKITeK6xWUkR2Z3zN4Zj%2FNwIzO86w3hL3mmbFDx%2Bw5IHrm58Y%2B%2FcdBMMlPCkZAPC8r0US6K4UVCRv939dBUQYbGeDrkBmg3gZUMFTQJ95psSP4AONvONlAIk0wRwYsuTqbZ9jle05wYSQKiYD1K8kZrtXTqN4XwJiBDA%2BmpWU6vb0a8VGZDGMvOjZWwQsezuHFG2gHpyuV83csDuCyj7%2BLPbb%2FDjNOSAo%2FUngC8SVbqiTfwSY4%2Fl06KO%2BDLPMgRf9%2B%2BB6n21ldWey2dH6tAW7pXBWswO3F2owHrhBuYo2iAjYnYIE4R%2Bpmdl9f7jHlCKT4nPzR3B4Rj5%2FAp8NnaXFEZVZ3hyIX25OdReNNzzry3Tt97HBA5nDXPUt6K8cAfnOEhgdYRc4s7n2Y2fbN8cvIF%2Fn0cY7cvbV4OGLlWHChCsx%2Bh8nVwL%2B8WJENupGNJ2bYSFCcNR%2FelsaFLpdUH6uTE8Vso6ByaiTE1BCiP28XhU0AnzYfJNVSCjlw64hevp1GG2MWqDV6zSR1qFoOvzaySKtcKPjC4qsW9BjqkAckTTqsbp96Mgr4GtJph8%2FM3A4vHjHwTGxLiJS%2FDyJffnmy%2FXVJKiM6qr9NMXdplLwlecSkRnsP2VQC8lGImjsYX2zxvhID1ePVHjUBWDMFC8QKvNfM4wU6iLBU8uagEGpO1qGpxCXdZ7Qzinouf2UxmyEFisnNZwB%2BF%2Fj9oTRLY2zYNtO45JeW1QkRHLiiFfUj9voJ9b9aeGg0%2BW%2FoRGzmC7SYI&X-Amz-Signature=c9b2f12e111254e56d6dd0bc8a3b9a1f80063e5007c617d6d7c0ab8230050afb&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XAXEDPPR%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T033005Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECsaCXVzLXdlc3QtMiJIMEYCIQDdVPOf%2B14hc8GZ2W8%2BJPDIjAXfkfiqHmrIwrHuKqJ3dwIhAO8Dn9jZ8mMHgjTKL%2B%2FQwhV8IrQjIVu13GD4H83qRGs6Kv8DCFQQABoMNjM3NDIzMTgzODA1IgxfQydauVFodM3OJJsq3ANpp5ulMU7J9dybj5MEf0yZiml8vI89NLOLgHjjXYwZpA9xTOc8mAAxf2br0EhmgyrfVVQt5z9aNqFh7it%2F9lPMrt4TFsiPGoKITeK6xWUkR2Z3zN4Zj%2FNwIzO86w3hL3mmbFDx%2Bw5IHrm58Y%2B%2FcdBMMlPCkZAPC8r0US6K4UVCRv939dBUQYbGeDrkBmg3gZUMFTQJ95psSP4AONvONlAIk0wRwYsuTqbZ9jle05wYSQKiYD1K8kZrtXTqN4XwJiBDA%2BmpWU6vb0a8VGZDGMvOjZWwQsezuHFG2gHpyuV83csDuCyj7%2BLPbb%2FDjNOSAo%2FUngC8SVbqiTfwSY4%2Fl06KO%2BDLPMgRf9%2B%2BB6n21ldWey2dH6tAW7pXBWswO3F2owHrhBuYo2iAjYnYIE4R%2Bpmdl9f7jHlCKT4nPzR3B4Rj5%2FAp8NnaXFEZVZ3hyIX25OdReNNzzry3Tt97HBA5nDXPUt6K8cAfnOEhgdYRc4s7n2Y2fbN8cvIF%2Fn0cY7cvbV4OGLlWHChCsx%2Bh8nVwL%2B8WJENupGNJ2bYSFCcNR%2FelsaFLpdUH6uTE8Vso6ByaiTE1BCiP28XhU0AnzYfJNVSCjlw64hevp1GG2MWqDV6zSR1qFoOvzaySKtcKPjC4qsW9BjqkAckTTqsbp96Mgr4GtJph8%2FM3A4vHjHwTGxLiJS%2FDyJffnmy%2FXVJKiM6qr9NMXdplLwlecSkRnsP2VQC8lGImjsYX2zxvhID1ePVHjUBWDMFC8QKvNfM4wU6iLBU8uagEGpO1qGpxCXdZ7Qzinouf2UxmyEFisnNZwB%2BF%2Fj9oTRLY2zYNtO45JeW1QkRHLiiFfUj9voJ9b9aeGg0%2BW%2FoRGzmC7SYI&X-Amz-Signature=d07d569c9e25722d5f9aeff31dd49819d44d70fa2dd191fd69748a952da5719d&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XAXEDPPR%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T033005Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECsaCXVzLXdlc3QtMiJIMEYCIQDdVPOf%2B14hc8GZ2W8%2BJPDIjAXfkfiqHmrIwrHuKqJ3dwIhAO8Dn9jZ8mMHgjTKL%2B%2FQwhV8IrQjIVu13GD4H83qRGs6Kv8DCFQQABoMNjM3NDIzMTgzODA1IgxfQydauVFodM3OJJsq3ANpp5ulMU7J9dybj5MEf0yZiml8vI89NLOLgHjjXYwZpA9xTOc8mAAxf2br0EhmgyrfVVQt5z9aNqFh7it%2F9lPMrt4TFsiPGoKITeK6xWUkR2Z3zN4Zj%2FNwIzO86w3hL3mmbFDx%2Bw5IHrm58Y%2B%2FcdBMMlPCkZAPC8r0US6K4UVCRv939dBUQYbGeDrkBmg3gZUMFTQJ95psSP4AONvONlAIk0wRwYsuTqbZ9jle05wYSQKiYD1K8kZrtXTqN4XwJiBDA%2BmpWU6vb0a8VGZDGMvOjZWwQsezuHFG2gHpyuV83csDuCyj7%2BLPbb%2FDjNOSAo%2FUngC8SVbqiTfwSY4%2Fl06KO%2BDLPMgRf9%2B%2BB6n21ldWey2dH6tAW7pXBWswO3F2owHrhBuYo2iAjYnYIE4R%2Bpmdl9f7jHlCKT4nPzR3B4Rj5%2FAp8NnaXFEZVZ3hyIX25OdReNNzzry3Tt97HBA5nDXPUt6K8cAfnOEhgdYRc4s7n2Y2fbN8cvIF%2Fn0cY7cvbV4OGLlWHChCsx%2Bh8nVwL%2B8WJENupGNJ2bYSFCcNR%2FelsaFLpdUH6uTE8Vso6ByaiTE1BCiP28XhU0AnzYfJNVSCjlw64hevp1GG2MWqDV6zSR1qFoOvzaySKtcKPjC4qsW9BjqkAckTTqsbp96Mgr4GtJph8%2FM3A4vHjHwTGxLiJS%2FDyJffnmy%2FXVJKiM6qr9NMXdplLwlecSkRnsP2VQC8lGImjsYX2zxvhID1ePVHjUBWDMFC8QKvNfM4wU6iLBU8uagEGpO1qGpxCXdZ7Qzinouf2UxmyEFisnNZwB%2BF%2Fj9oTRLY2zYNtO45JeW1QkRHLiiFfUj9voJ9b9aeGg0%2BW%2FoRGzmC7SYI&X-Amz-Signature=70ad70d5dd4b76011ce5699599d8c94201d67dd4fca6dc33f77e58ca52ef9b2b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XAXEDPPR%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T033005Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECsaCXVzLXdlc3QtMiJIMEYCIQDdVPOf%2B14hc8GZ2W8%2BJPDIjAXfkfiqHmrIwrHuKqJ3dwIhAO8Dn9jZ8mMHgjTKL%2B%2FQwhV8IrQjIVu13GD4H83qRGs6Kv8DCFQQABoMNjM3NDIzMTgzODA1IgxfQydauVFodM3OJJsq3ANpp5ulMU7J9dybj5MEf0yZiml8vI89NLOLgHjjXYwZpA9xTOc8mAAxf2br0EhmgyrfVVQt5z9aNqFh7it%2F9lPMrt4TFsiPGoKITeK6xWUkR2Z3zN4Zj%2FNwIzO86w3hL3mmbFDx%2Bw5IHrm58Y%2B%2FcdBMMlPCkZAPC8r0US6K4UVCRv939dBUQYbGeDrkBmg3gZUMFTQJ95psSP4AONvONlAIk0wRwYsuTqbZ9jle05wYSQKiYD1K8kZrtXTqN4XwJiBDA%2BmpWU6vb0a8VGZDGMvOjZWwQsezuHFG2gHpyuV83csDuCyj7%2BLPbb%2FDjNOSAo%2FUngC8SVbqiTfwSY4%2Fl06KO%2BDLPMgRf9%2B%2BB6n21ldWey2dH6tAW7pXBWswO3F2owHrhBuYo2iAjYnYIE4R%2Bpmdl9f7jHlCKT4nPzR3B4Rj5%2FAp8NnaXFEZVZ3hyIX25OdReNNzzry3Tt97HBA5nDXPUt6K8cAfnOEhgdYRc4s7n2Y2fbN8cvIF%2Fn0cY7cvbV4OGLlWHChCsx%2Bh8nVwL%2B8WJENupGNJ2bYSFCcNR%2FelsaFLpdUH6uTE8Vso6ByaiTE1BCiP28XhU0AnzYfJNVSCjlw64hevp1GG2MWqDV6zSR1qFoOvzaySKtcKPjC4qsW9BjqkAckTTqsbp96Mgr4GtJph8%2FM3A4vHjHwTGxLiJS%2FDyJffnmy%2FXVJKiM6qr9NMXdplLwlecSkRnsP2VQC8lGImjsYX2zxvhID1ePVHjUBWDMFC8QKvNfM4wU6iLBU8uagEGpO1qGpxCXdZ7Qzinouf2UxmyEFisnNZwB%2BF%2Fj9oTRLY2zYNtO45JeW1QkRHLiiFfUj9voJ9b9aeGg0%2BW%2FoRGzmC7SYI&X-Amz-Signature=4164a7897f6508814d6f9665cd93895166fa5ae97470c6b481e3d95fe464845f&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662XESRNEB%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T033006Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECsaCXVzLXdlc3QtMiJIMEYCIQCXSqWyAw3unVJ6%2BLdlziCwv3lfehox8uFrFYPgzzpvtQIhAIQPUrw%2FLawsP9Babo5LrXk2o05Q6PxZEjMU1NlUJcSHKv8DCFQQABoMNjM3NDIzMTgzODA1IgzCYPReQJ9nPDDUcp4q3AO6sQvk1E4%2BWCtqfxl0EpxZU2zLEjtdrA%2B2RK8p%2FJ2%2FJYmjhwTinDw3wAte5504ZncItVr0TXghy7YSL7D6MwYpdvkj6tZd6Wu7sBvFlA80AJUpVV%2FgfKQqeAyp9BcTySKB0Bn0jxJFVjGHGFxAcJSe3lHz2666XAJ7j1RmyxAFs%2FaBKKhL0pBLpOuOEk2oRfLEl%2FuSGD7ksBtJkKfRCHMTs5fon%2Fg2S8%2FwQ3D%2Fe0zRpNvr3n%2BmoPyjBCm%2B4a48Wk13OvQvobGuZSX8aE3eIt6iEbaNVrzFNrpWgunM5pq%2FVxdzDF1VQ0J%2FBZxl4sHLpf4HvrqMwhhV4M9jMHlEVY8dYEt9FeKfIoNvWa7blSJQ%2BFOajZD5GXP2bhSI4HBpIgDCCBEHrY4otdeSJwdrLEuQfZT3r5bt7B1cwmP7Oz%2FrruTGM1k6UbQSG1mOsAfidqCdTPwwCrGOfaVRP7bFH0vgqw7%2FuyiGUb7lMTfTdl01jIj7jDN6AWKz29aaAwWih%2Fbso2nRPhvHhk2ucBHgsGz9oXwsgg9qSTwn2iwrv9y2CwI37PyO4AyIMj0Zn7U%2FJJOH9AutbVBAP9iOi3ywHbNLSyF2ts4MsguIgm%2BGUv4jg2h2tRD1gQ537hh31jCuqsW9BjqkAZ8naEuvej3YPn8x619PEUjws5TnZTP8yTzFgiw6hgoMc2VNlu4EySHVcthR6re1Sz92KqzDuHXtOYshmFqxgHY9Rw3Ap3D0snwpugUt5QRT0YgCiwXfSheB5cLhy%2BevaHJ9h6tIoWgcXOfLVkMc45jWRTfPzZiaMBlRm0W%2FZg5YTINYTRX6uRZtBeCzCrgofuQyvG9ZQAY1c%2FWj7VsP7zVA%2BgcT&X-Amz-Signature=f71c177f54e28a4b41e973f2507666a62480abe2cd454eb4290460dfa9f629f0&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46663EP74QD%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T033006Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECsaCXVzLXdlc3QtMiJHMEUCIBJqpZXyGvZH4mTY2vqbnNOQg5mAQlCSTvATlztj02TnAiEAkLJVORK%2FCZX2XfBpPuTWqwbxSE3%2FhY1pccqbX9uwxYUq%2FwMIVBAAGgw2Mzc0MjMxODM4MDUiDIU%2B7PXiuYFoOFBJ%2FyrcAwShn3HRliZWJ%2FPvjScRZF0g4q1iX7fTc97GFx8Xh3bntgXgPNBYzVHdnFVHxR50n8T7Xsy9rcgiQnKLKikFq7%2FdI%2F6we3SppLwGhBJXX3px%2FBKWKIl13pX6k85O27h0Ll120dTK4H84tEAs49KeMvpZJEX1A%2Bke%2BFlMCUhEUA0OULjdeP0TLXDZplGhGpBbFHqJZziRjmLY7lNBZ9NgaL79PaB6wumf9fQa6PHQuhcTapBcjJI4zVwF8%2BlnhbbIfFVb0D0DvetQ2edpStTNpifHcRwmunWwJSCRk5oHD1USZQm5wcSlZRznFA3sYCyZSpxBBrcMjfzFF0k%2Fs3N%2B3z8wGtYV%2BxbRDcJaEfBe9JiOOpo5UlzRGGlg2jD8OAofH%2FRxeT1vmVynTLnAafOf0QMtNOn%2B%2BNV3QdK46i0K3OffMb7gCmIYHsK4Mt3DN7YssZ0eBUNu6VKFfU1%2FOZNadtPUaNiTD8lW03ItG0Yqs2OC5GnHXvkik6JWQ4ReLcOLJKa%2FvmNaxhYh9j34Mp%2FKdrVeqfFfD1rHTwM8lZCRDwMwiil0DS8dLqE%2BJopJGrhzGQDDIugJMGpiVHuLBdbfizO6a9MnFH62NL7qYRlKadoJSOtAorIJI%2B2CWfHCMOCpxb0GOqUB2EuqdmytEJOszr2VjikkvfCYyBXgee8Yi5DFautImMWDRpF6FM%2BB914Fx2CeTwUwBQx1%2F4QwviLrFkdcDUrPygz6fEy75qqW%2F0ZrU7Zyb0OeZ5K06jIEfudX%2BEpaJWg0B9YDqRbE2zeIUQ5ibALC3CN86KhF0XbE%2FgLPSTDpBQK85KkzhYsUB%2BgLwRADnX02RKG%2BaBW4QzcFbREct8xhc0oEjIuE&X-Amz-Signature=13a5b5588326fb3513f67a6150372d6bf1e713a56199a2d3e282d6387f9cf228&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XAXEDPPR%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T033005Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECsaCXVzLXdlc3QtMiJIMEYCIQDdVPOf%2B14hc8GZ2W8%2BJPDIjAXfkfiqHmrIwrHuKqJ3dwIhAO8Dn9jZ8mMHgjTKL%2B%2FQwhV8IrQjIVu13GD4H83qRGs6Kv8DCFQQABoMNjM3NDIzMTgzODA1IgxfQydauVFodM3OJJsq3ANpp5ulMU7J9dybj5MEf0yZiml8vI89NLOLgHjjXYwZpA9xTOc8mAAxf2br0EhmgyrfVVQt5z9aNqFh7it%2F9lPMrt4TFsiPGoKITeK6xWUkR2Z3zN4Zj%2FNwIzO86w3hL3mmbFDx%2Bw5IHrm58Y%2B%2FcdBMMlPCkZAPC8r0US6K4UVCRv939dBUQYbGeDrkBmg3gZUMFTQJ95psSP4AONvONlAIk0wRwYsuTqbZ9jle05wYSQKiYD1K8kZrtXTqN4XwJiBDA%2BmpWU6vb0a8VGZDGMvOjZWwQsezuHFG2gHpyuV83csDuCyj7%2BLPbb%2FDjNOSAo%2FUngC8SVbqiTfwSY4%2Fl06KO%2BDLPMgRf9%2B%2BB6n21ldWey2dH6tAW7pXBWswO3F2owHrhBuYo2iAjYnYIE4R%2Bpmdl9f7jHlCKT4nPzR3B4Rj5%2FAp8NnaXFEZVZ3hyIX25OdReNNzzry3Tt97HBA5nDXPUt6K8cAfnOEhgdYRc4s7n2Y2fbN8cvIF%2Fn0cY7cvbV4OGLlWHChCsx%2Bh8nVwL%2B8WJENupGNJ2bYSFCcNR%2FelsaFLpdUH6uTE8Vso6ByaiTE1BCiP28XhU0AnzYfJNVSCjlw64hevp1GG2MWqDV6zSR1qFoOvzaySKtcKPjC4qsW9BjqkAckTTqsbp96Mgr4GtJph8%2FM3A4vHjHwTGxLiJS%2FDyJffnmy%2FXVJKiM6qr9NMXdplLwlecSkRnsP2VQC8lGImjsYX2zxvhID1ePVHjUBWDMFC8QKvNfM4wU6iLBU8uagEGpO1qGpxCXdZ7Qzinouf2UxmyEFisnNZwB%2BF%2Fj9oTRLY2zYNtO45JeW1QkRHLiiFfUj9voJ9b9aeGg0%2BW%2FoRGzmC7SYI&X-Amz-Signature=0666ec21aa0207954cd8c4353a8f09416471286adee0440d0537dae786538aba&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XAXEDPPR%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T033005Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECsaCXVzLXdlc3QtMiJIMEYCIQDdVPOf%2B14hc8GZ2W8%2BJPDIjAXfkfiqHmrIwrHuKqJ3dwIhAO8Dn9jZ8mMHgjTKL%2B%2FQwhV8IrQjIVu13GD4H83qRGs6Kv8DCFQQABoMNjM3NDIzMTgzODA1IgxfQydauVFodM3OJJsq3ANpp5ulMU7J9dybj5MEf0yZiml8vI89NLOLgHjjXYwZpA9xTOc8mAAxf2br0EhmgyrfVVQt5z9aNqFh7it%2F9lPMrt4TFsiPGoKITeK6xWUkR2Z3zN4Zj%2FNwIzO86w3hL3mmbFDx%2Bw5IHrm58Y%2B%2FcdBMMlPCkZAPC8r0US6K4UVCRv939dBUQYbGeDrkBmg3gZUMFTQJ95psSP4AONvONlAIk0wRwYsuTqbZ9jle05wYSQKiYD1K8kZrtXTqN4XwJiBDA%2BmpWU6vb0a8VGZDGMvOjZWwQsezuHFG2gHpyuV83csDuCyj7%2BLPbb%2FDjNOSAo%2FUngC8SVbqiTfwSY4%2Fl06KO%2BDLPMgRf9%2B%2BB6n21ldWey2dH6tAW7pXBWswO3F2owHrhBuYo2iAjYnYIE4R%2Bpmdl9f7jHlCKT4nPzR3B4Rj5%2FAp8NnaXFEZVZ3hyIX25OdReNNzzry3Tt97HBA5nDXPUt6K8cAfnOEhgdYRc4s7n2Y2fbN8cvIF%2Fn0cY7cvbV4OGLlWHChCsx%2Bh8nVwL%2B8WJENupGNJ2bYSFCcNR%2FelsaFLpdUH6uTE8Vso6ByaiTE1BCiP28XhU0AnzYfJNVSCjlw64hevp1GG2MWqDV6zSR1qFoOvzaySKtcKPjC4qsW9BjqkAckTTqsbp96Mgr4GtJph8%2FM3A4vHjHwTGxLiJS%2FDyJffnmy%2FXVJKiM6qr9NMXdplLwlecSkRnsP2VQC8lGImjsYX2zxvhID1ePVHjUBWDMFC8QKvNfM4wU6iLBU8uagEGpO1qGpxCXdZ7Qzinouf2UxmyEFisnNZwB%2BF%2Fj9oTRLY2zYNtO45JeW1QkRHLiiFfUj9voJ9b9aeGg0%2BW%2FoRGzmC7SYI&X-Amz-Signature=d3df998dbc13695a130f4da3f085852d0eb8d3f442027f9cf0b518c7797d84d9&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XAXEDPPR%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T033005Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECsaCXVzLXdlc3QtMiJIMEYCIQDdVPOf%2B14hc8GZ2W8%2BJPDIjAXfkfiqHmrIwrHuKqJ3dwIhAO8Dn9jZ8mMHgjTKL%2B%2FQwhV8IrQjIVu13GD4H83qRGs6Kv8DCFQQABoMNjM3NDIzMTgzODA1IgxfQydauVFodM3OJJsq3ANpp5ulMU7J9dybj5MEf0yZiml8vI89NLOLgHjjXYwZpA9xTOc8mAAxf2br0EhmgyrfVVQt5z9aNqFh7it%2F9lPMrt4TFsiPGoKITeK6xWUkR2Z3zN4Zj%2FNwIzO86w3hL3mmbFDx%2Bw5IHrm58Y%2B%2FcdBMMlPCkZAPC8r0US6K4UVCRv939dBUQYbGeDrkBmg3gZUMFTQJ95psSP4AONvONlAIk0wRwYsuTqbZ9jle05wYSQKiYD1K8kZrtXTqN4XwJiBDA%2BmpWU6vb0a8VGZDGMvOjZWwQsezuHFG2gHpyuV83csDuCyj7%2BLPbb%2FDjNOSAo%2FUngC8SVbqiTfwSY4%2Fl06KO%2BDLPMgRf9%2B%2BB6n21ldWey2dH6tAW7pXBWswO3F2owHrhBuYo2iAjYnYIE4R%2Bpmdl9f7jHlCKT4nPzR3B4Rj5%2FAp8NnaXFEZVZ3hyIX25OdReNNzzry3Tt97HBA5nDXPUt6K8cAfnOEhgdYRc4s7n2Y2fbN8cvIF%2Fn0cY7cvbV4OGLlWHChCsx%2Bh8nVwL%2B8WJENupGNJ2bYSFCcNR%2FelsaFLpdUH6uTE8Vso6ByaiTE1BCiP28XhU0AnzYfJNVSCjlw64hevp1GG2MWqDV6zSR1qFoOvzaySKtcKPjC4qsW9BjqkAckTTqsbp96Mgr4GtJph8%2FM3A4vHjHwTGxLiJS%2FDyJffnmy%2FXVJKiM6qr9NMXdplLwlecSkRnsP2VQC8lGImjsYX2zxvhID1ePVHjUBWDMFC8QKvNfM4wU6iLBU8uagEGpO1qGpxCXdZ7Qzinouf2UxmyEFisnNZwB%2BF%2Fj9oTRLY2zYNtO45JeW1QkRHLiiFfUj9voJ9b9aeGg0%2BW%2FoRGzmC7SYI&X-Amz-Signature=f110950f22b3c77c8973eff33a10d013a4ae1247d2504e73a0842b04e5e57510&X-Amz-SignedHeaders=host&x-id=GetObject)


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

