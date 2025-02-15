---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466TYGJXTXM%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250215T182840Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjECIaCXVzLXdlc3QtMiJIMEYCIQC7WtJuhtE2fOK3rzTuQLSW9hNmcrSUwNHvl85vwZrrHgIhAPf\
  sEv1n%2FUFmhcjdc%2Fb6LRbAe1iOSrI70dNT%2F2%2Bh%2FUH%2FKv8DCEoQABoMNjM3NDIzMTgz\
  ODA1Igxh%2FZGGTYUz1vrgweoq3ANx4%2BFtXqiwYYAha828VcX9hQTy2j4NEQ1gKiZ1Dwq7MZpPF\
  KcGkbKfVZWc5PDU7ckeuAYK7KWjmdAa2KNgz3yQcC7%2Bm8vxXkU5tZ%2FNeP7AXaRvke9WUBPclU\
  KzaAFFskPXsXB9oQHdV7RyOTOtA3E3dVIifaEBa94PXKjdVV8ZZHDuiE71ncamrTAE%2BElJty39B\
  ktVG3Xj0yT8jIOTpSeLx1GBrPucdeL%2BP3izW1Eq1EoAbbTN6Xk806vCA2%2Ba%2F0WSZ2LchVYl\
  Cl7DhAvA6dZ%2Fws7nhmsQSji7Zp8Z6CY%2F9cLWtlDxH2gPwhDEVlWd1cTmQJSlJi9xUhfnAybND\
  uAf5uRJISE9WRplV0ia4OJ4MQvrEro5RYyfLy27FaGuSGeBQ1Urwmv8QV9hkeDVfdM682%2Bm2zr1\
  yQe0t15pdbJSIn%2Bw6mSkaEWjv2I1EzheLWKsLF9QxADrGueB1d646wMPXCyIL1agvK2LW0%2B21\
  IYo1hZ1UuSSmivSTgiImdi60r7a8xe6LNUvl8AITZbcKR2xmS5IwS0jZi02QbSjD8xdCyTGAQmU5R\
  VLAk%2F%2F6ZyxlSRpQvBoI7LJQjs0BQqm3DAjDniMBOtpoAIcbnV%2FIrUwPChyMdXNBjFzzCkvF\
  zDsm8O9BjqkAQLpk89FB%2Bq5Cw1QkXUgo2Wc5%2F12oHiKeKfjwPmrzvo1IIP6bSXsmAza%2BqXF\
  XeKqv5e%2F9iYu2M0he88BYqbL6h4kR8YOvQTTsh0%2F8FfPRsdXNEVvLi1nzlSrdYCRP8rNsM2rk\
  6KL8vx0wjp7ilrPr6BVxb5J1dJXbQhJ3BbtP9KpRg0kLJ1ruB8%2BltNMyTvqwKVpKxHfDIPJy7EH\
  GwGj1gzaMsmB&X-Amz-Signature=b1bd11d6cb086f0c4bd9b47fc2a3af2b2909a90edef6efa6\
  3cb3e811dd6f985c&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4664SRQPE6I%2F20250215%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250215T182721Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjECIaCXVzLXdlc3QtMiJHMEUCIAsv0QkZ669IRUEKYwcCPhhtq%2BNVB\
        FeIDiQuiQ3GvFckAiEAh7Gqvf2VoTmmb3mgGI%2BJ5fAE%2B2jSzp8nN1KZDc9nXTAq%2Fw\
        MIShAAGgw2Mzc0MjMxODM4MDUiDOi5UCuGi%2FHd%2FMBXGSrcA0JsjGSAQirTjLWz%2Fk%\
        2FBrqYxLY%2FZdDo3%2Flsyq%2F0uWQG%2FuGIVGCsYesn8zEfnPy0iTWLBio4J4T4psTrB\
        aW%2B5SLOPTBdTfY4hpxfwgoKISPgKOcaJOuqtjnVXH%2FPN5%2F%2F3vWWchC8DYLGDXLR\
        irbQ8YJdzggHHLrcEgM2Fuq8%2FAvlh6WKj1jhUTwikjn966S2VZA%2BQyzi5kiMvlZU%2F\
        V0PstccfPjHJwB7%2F4sZPo%2FPhS3eBgByKUEfqZWCMJQmv5z%2FoM0E5J%2FanKewXMzu\
        DkKwVcOLZUk0RaynfkqknWnQ62pe8gbcUoZA7ZYzaC1Hl7y%2FpJPWYJXgirHzXvUVqCOje\
        ccXhK2M4MR4SZnQAJTMnOKU4%2FO%2FNb5lofZoAw%2BwMoe5b41I0kfdWrJpzq1CRHauYK\
        rl%2FWz7pOkTEAF4fpfX%2BVL9uVaOxv2OumuyqAowrXO8LB1558fqkz0MN9mtdMoOnOT5E\
        TfwSLrsOiqmtvKMGqEOBoMYabbnC9l9vectKkYwnHDwRBpVzv8iGJp2lQR%2Bx6A5jn5q8f\
        88FwJARJPPn40tpe7NXg%2F6Mhgsymf%2FhY2KqucyXLvGhoWAc%2F4%2BSIdtDaa7AkyIJ\
        n19u0ptj%2BEIumNJxoC6ApBU8MhkOIpWfMOmbw70GOqUBtQ%2B4ssy2p5GCQp7wKCYEYJe\
        s%2F5r4jx7CM7cXR%2Bxt8z1kmkIhQnGbo6YEM9mNubuWTq%2BDw35ciOv4KytEcsWHmYbA\
        %2B1lMX6RVwaaeUom7%2F3dYW%2BajUV4TwiDlGISjQH3MoXOZ0vFwqC%2FHTSCW8g2lOnr\
        VFVb2%2BYOh40Dt5uT%2BAKg3roPxcBI94teSgn3zkk1Dy6G7jx13UuoUIgl7scOpTftvN%\
        2Foe&X-Amz-Signature=86099121f018729d19aa6e0292bf0b9f6eba22c8605f8b0004\
        4e7f2fcc14b927&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-15T19:27:21.198Z"
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
UPDATE_TIME: "2025-02-15T18:28:47.816Z"
EXPIRY_TIME: "2025-02-15T19:28:37.406Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SYUFHVYB%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T182838Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECIaCXVzLXdlc3QtMiJHMEUCICvbLLvQG4z6pOjc94NSCT6gwWvx2qiRYUgop2694hyuAiEA1iGX5bERgJ5RpgWgDrV01h%2Fo4SaLoh%2F32r6WzQcgGP4q%2FwMIShAAGgw2Mzc0MjMxODM4MDUiDE8Wj%2FQUBjrAOmJO%2FircA5ATFLmmGRKJdTwBQfFS88EfvBmNTS5z9rUwcLVV2RTNzzSc4xYEQpvCHaKdT5ZeDKPkajSqt1yuHVTljDFXqs0X%2F88%2BpDd9%2FMyXfH9SRPV%2BNxcu7XGYDKY3ShRZghUFUzjJoYeY7moptV6RG18GoLFagfWw%2Bquj9ktqpvk%2BLQihjAyQrEVWhhcXFpCit1Kh2xLN6gv%2B0waGObAyagZfJW8xhhkiq52XlrpgfSoj0tj38YQqUcjQ8cMAb%2FVueBDBWGvnB98IGdS6kWgqrMCVuX4WA2ZoauukLGU%2FxyPewvP0JF6D9BtuivWURUP3V%2BGQysvTL0%2BTcOOQFO9aqUJpP2MfXZNSiwH8%2BfWhlxPSbV3ippwRVZZzTM4uKPNzYCJWPs2H2ZzYDFqFaker93YYHRnxXKghXEmczhmeiArmhc6j1qS1NTvQaDXMExAi99cC%2FJG42%2Fkwi1Eh7zBgsWD9PNMGgLpanaCZTexyF8Lnc1fnMo9srxX05LNJLw%2BeHy%2BA9JxXo3f5LNPHjPEFB5aRDUunHd%2B2yxvLSogeA6VvrCR77eyJuN783y6qCLuVgLYA5bg8BXQGw7iuRxJBeARJ0wCl%2FqDKxqjdQKgsNg07V9CGsrwRTII41H7PV5iFMLWbw70GOqUBlFygrRggXZo62QeyriremyKajwfo%2FY3GURMyouBrR5N43r6Hx7eFrx5cODzF2jF1VctdybCLeLy1uc0m49l1hrYEwyjp6dCx5TZie6iaXSt23I%2BpcYTaYLU0ugTiCr644ds0TIUqpoG6AnpFpecL8VEwCuugfPrxSEpEZxXWlv1xm7An0QtUCPXPJLEjuwDxQgFuy3ZhWBK0JmrEIdtM6i0VLpoj&X-Amz-Signature=e5549da2c2c3a3e7d65c3633b6d8ed6b80903ea07b60cc176dc991b9665b12f3&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SYUFHVYB%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T182838Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECIaCXVzLXdlc3QtMiJHMEUCICvbLLvQG4z6pOjc94NSCT6gwWvx2qiRYUgop2694hyuAiEA1iGX5bERgJ5RpgWgDrV01h%2Fo4SaLoh%2F32r6WzQcgGP4q%2FwMIShAAGgw2Mzc0MjMxODM4MDUiDE8Wj%2FQUBjrAOmJO%2FircA5ATFLmmGRKJdTwBQfFS88EfvBmNTS5z9rUwcLVV2RTNzzSc4xYEQpvCHaKdT5ZeDKPkajSqt1yuHVTljDFXqs0X%2F88%2BpDd9%2FMyXfH9SRPV%2BNxcu7XGYDKY3ShRZghUFUzjJoYeY7moptV6RG18GoLFagfWw%2Bquj9ktqpvk%2BLQihjAyQrEVWhhcXFpCit1Kh2xLN6gv%2B0waGObAyagZfJW8xhhkiq52XlrpgfSoj0tj38YQqUcjQ8cMAb%2FVueBDBWGvnB98IGdS6kWgqrMCVuX4WA2ZoauukLGU%2FxyPewvP0JF6D9BtuivWURUP3V%2BGQysvTL0%2BTcOOQFO9aqUJpP2MfXZNSiwH8%2BfWhlxPSbV3ippwRVZZzTM4uKPNzYCJWPs2H2ZzYDFqFaker93YYHRnxXKghXEmczhmeiArmhc6j1qS1NTvQaDXMExAi99cC%2FJG42%2Fkwi1Eh7zBgsWD9PNMGgLpanaCZTexyF8Lnc1fnMo9srxX05LNJLw%2BeHy%2BA9JxXo3f5LNPHjPEFB5aRDUunHd%2B2yxvLSogeA6VvrCR77eyJuN783y6qCLuVgLYA5bg8BXQGw7iuRxJBeARJ0wCl%2FqDKxqjdQKgsNg07V9CGsrwRTII41H7PV5iFMLWbw70GOqUBlFygrRggXZo62QeyriremyKajwfo%2FY3GURMyouBrR5N43r6Hx7eFrx5cODzF2jF1VctdybCLeLy1uc0m49l1hrYEwyjp6dCx5TZie6iaXSt23I%2BpcYTaYLU0ugTiCr644ds0TIUqpoG6AnpFpecL8VEwCuugfPrxSEpEZxXWlv1xm7An0QtUCPXPJLEjuwDxQgFuy3ZhWBK0JmrEIdtM6i0VLpoj&X-Amz-Signature=ce68b6b055f9ebe5d9c46ccfd5d8dfc8d6e76681ac2548b8ccef17ee47a57233&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SYUFHVYB%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T182838Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECIaCXVzLXdlc3QtMiJHMEUCICvbLLvQG4z6pOjc94NSCT6gwWvx2qiRYUgop2694hyuAiEA1iGX5bERgJ5RpgWgDrV01h%2Fo4SaLoh%2F32r6WzQcgGP4q%2FwMIShAAGgw2Mzc0MjMxODM4MDUiDE8Wj%2FQUBjrAOmJO%2FircA5ATFLmmGRKJdTwBQfFS88EfvBmNTS5z9rUwcLVV2RTNzzSc4xYEQpvCHaKdT5ZeDKPkajSqt1yuHVTljDFXqs0X%2F88%2BpDd9%2FMyXfH9SRPV%2BNxcu7XGYDKY3ShRZghUFUzjJoYeY7moptV6RG18GoLFagfWw%2Bquj9ktqpvk%2BLQihjAyQrEVWhhcXFpCit1Kh2xLN6gv%2B0waGObAyagZfJW8xhhkiq52XlrpgfSoj0tj38YQqUcjQ8cMAb%2FVueBDBWGvnB98IGdS6kWgqrMCVuX4WA2ZoauukLGU%2FxyPewvP0JF6D9BtuivWURUP3V%2BGQysvTL0%2BTcOOQFO9aqUJpP2MfXZNSiwH8%2BfWhlxPSbV3ippwRVZZzTM4uKPNzYCJWPs2H2ZzYDFqFaker93YYHRnxXKghXEmczhmeiArmhc6j1qS1NTvQaDXMExAi99cC%2FJG42%2Fkwi1Eh7zBgsWD9PNMGgLpanaCZTexyF8Lnc1fnMo9srxX05LNJLw%2BeHy%2BA9JxXo3f5LNPHjPEFB5aRDUunHd%2B2yxvLSogeA6VvrCR77eyJuN783y6qCLuVgLYA5bg8BXQGw7iuRxJBeARJ0wCl%2FqDKxqjdQKgsNg07V9CGsrwRTII41H7PV5iFMLWbw70GOqUBlFygrRggXZo62QeyriremyKajwfo%2FY3GURMyouBrR5N43r6Hx7eFrx5cODzF2jF1VctdybCLeLy1uc0m49l1hrYEwyjp6dCx5TZie6iaXSt23I%2BpcYTaYLU0ugTiCr644ds0TIUqpoG6AnpFpecL8VEwCuugfPrxSEpEZxXWlv1xm7An0QtUCPXPJLEjuwDxQgFuy3ZhWBK0JmrEIdtM6i0VLpoj&X-Amz-Signature=943873b043b3324b508220d8fbba8cc2489d53b3bb4528cbe18580fb96d330fe&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SYUFHVYB%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T182838Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECIaCXVzLXdlc3QtMiJHMEUCICvbLLvQG4z6pOjc94NSCT6gwWvx2qiRYUgop2694hyuAiEA1iGX5bERgJ5RpgWgDrV01h%2Fo4SaLoh%2F32r6WzQcgGP4q%2FwMIShAAGgw2Mzc0MjMxODM4MDUiDE8Wj%2FQUBjrAOmJO%2FircA5ATFLmmGRKJdTwBQfFS88EfvBmNTS5z9rUwcLVV2RTNzzSc4xYEQpvCHaKdT5ZeDKPkajSqt1yuHVTljDFXqs0X%2F88%2BpDd9%2FMyXfH9SRPV%2BNxcu7XGYDKY3ShRZghUFUzjJoYeY7moptV6RG18GoLFagfWw%2Bquj9ktqpvk%2BLQihjAyQrEVWhhcXFpCit1Kh2xLN6gv%2B0waGObAyagZfJW8xhhkiq52XlrpgfSoj0tj38YQqUcjQ8cMAb%2FVueBDBWGvnB98IGdS6kWgqrMCVuX4WA2ZoauukLGU%2FxyPewvP0JF6D9BtuivWURUP3V%2BGQysvTL0%2BTcOOQFO9aqUJpP2MfXZNSiwH8%2BfWhlxPSbV3ippwRVZZzTM4uKPNzYCJWPs2H2ZzYDFqFaker93YYHRnxXKghXEmczhmeiArmhc6j1qS1NTvQaDXMExAi99cC%2FJG42%2Fkwi1Eh7zBgsWD9PNMGgLpanaCZTexyF8Lnc1fnMo9srxX05LNJLw%2BeHy%2BA9JxXo3f5LNPHjPEFB5aRDUunHd%2B2yxvLSogeA6VvrCR77eyJuN783y6qCLuVgLYA5bg8BXQGw7iuRxJBeARJ0wCl%2FqDKxqjdQKgsNg07V9CGsrwRTII41H7PV5iFMLWbw70GOqUBlFygrRggXZo62QeyriremyKajwfo%2FY3GURMyouBrR5N43r6Hx7eFrx5cODzF2jF1VctdybCLeLy1uc0m49l1hrYEwyjp6dCx5TZie6iaXSt23I%2BpcYTaYLU0ugTiCr644ds0TIUqpoG6AnpFpecL8VEwCuugfPrxSEpEZxXWlv1xm7An0QtUCPXPJLEjuwDxQgFuy3ZhWBK0JmrEIdtM6i0VLpoj&X-Amz-Signature=9f1d2843f28ded90c2b95bf160223aee18490250f370f77c77512b3a47d88148&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SYUFHVYB%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T182838Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECIaCXVzLXdlc3QtMiJHMEUCICvbLLvQG4z6pOjc94NSCT6gwWvx2qiRYUgop2694hyuAiEA1iGX5bERgJ5RpgWgDrV01h%2Fo4SaLoh%2F32r6WzQcgGP4q%2FwMIShAAGgw2Mzc0MjMxODM4MDUiDE8Wj%2FQUBjrAOmJO%2FircA5ATFLmmGRKJdTwBQfFS88EfvBmNTS5z9rUwcLVV2RTNzzSc4xYEQpvCHaKdT5ZeDKPkajSqt1yuHVTljDFXqs0X%2F88%2BpDd9%2FMyXfH9SRPV%2BNxcu7XGYDKY3ShRZghUFUzjJoYeY7moptV6RG18GoLFagfWw%2Bquj9ktqpvk%2BLQihjAyQrEVWhhcXFpCit1Kh2xLN6gv%2B0waGObAyagZfJW8xhhkiq52XlrpgfSoj0tj38YQqUcjQ8cMAb%2FVueBDBWGvnB98IGdS6kWgqrMCVuX4WA2ZoauukLGU%2FxyPewvP0JF6D9BtuivWURUP3V%2BGQysvTL0%2BTcOOQFO9aqUJpP2MfXZNSiwH8%2BfWhlxPSbV3ippwRVZZzTM4uKPNzYCJWPs2H2ZzYDFqFaker93YYHRnxXKghXEmczhmeiArmhc6j1qS1NTvQaDXMExAi99cC%2FJG42%2Fkwi1Eh7zBgsWD9PNMGgLpanaCZTexyF8Lnc1fnMo9srxX05LNJLw%2BeHy%2BA9JxXo3f5LNPHjPEFB5aRDUunHd%2B2yxvLSogeA6VvrCR77eyJuN783y6qCLuVgLYA5bg8BXQGw7iuRxJBeARJ0wCl%2FqDKxqjdQKgsNg07V9CGsrwRTII41H7PV5iFMLWbw70GOqUBlFygrRggXZo62QeyriremyKajwfo%2FY3GURMyouBrR5N43r6Hx7eFrx5cODzF2jF1VctdybCLeLy1uc0m49l1hrYEwyjp6dCx5TZie6iaXSt23I%2BpcYTaYLU0ugTiCr644ds0TIUqpoG6AnpFpecL8VEwCuugfPrxSEpEZxXWlv1xm7An0QtUCPXPJLEjuwDxQgFuy3ZhWBK0JmrEIdtM6i0VLpoj&X-Amz-Signature=a6b0f6a2996ffd69b278e59ca561439b10625e7e277036d9943d153a07a3832d&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466W4Z3G6M3%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T182838Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECIaCXVzLXdlc3QtMiJIMEYCIQDvMIhwPAOX8N%2BqS%2BhVW0ekPcLyV680I4JRs8C4VskrhgIhALJKsN5o%2BVB%2FnvOXVMx1gycNQydNN0gSPJfGmOwyClvBKv8DCEoQABoMNjM3NDIzMTgzODA1IgzUXpM0mE9YNc2AnRwq3AOkXEVD27JiS%2BCKaY%2FRBW5XW8U0hgJohDC%2FdQoKU%2BDzo8HuNrOTu4U0tMHqcObSjIeGJmgt2PapgOTxuWuhTvVPI%2FAOxRKA%2Bx46JkY0l6YnT9UUfCqwdzwqjhrhag2bg%2FUUcAC5Xk%2F2NJ9DfEbki07Zmi00VB4hS3qkxFUEDKh6gv9wJ8T8JZ%2Few%2FcUAqDTrv9b80mbSQWJkRWwNPcTWxEIZ9z7ogfBqu%2BvPIdqbm4B0lC7Mc8iNXcPibnccQAKbhyfYgw%2B8wgfoZmdGfoaAkw3QPBJrLHWLkTLoiPiQzdewnkn4cgsqqvSWqwSVq6VERWasfSo4I3sRcxNMFOWoWlyVFWt8TWNmy%2BzCMAiMWKaEOdk%2Fj9iG%2FLItQy93sbjyIvWFsvNn5wJ9qeydrWphn9X%2FI1Ow%2FnMk0%2BKxa38eHiHLIYfWJONZhZoQK0XDhpXkwntMA%2BkYiWYjO6uzFP7MJkk0hHZSrdJgW%2BjQTDE8zI2rQ2KhIPJHieXWxb%2FKf9J9STn2cGLt59DpXLnGMZkJpifcv3d8lfKUxfeBvz%2FzX2znjbT1Qk48yywXbhb5hZakDjmSD0oICBQeM0HPLZDQeb4QBKJdZbMr5y8ojYueN5eQJOg7OvhGtGfZEFLRzDJm8O9BjqkAR0QRJbSQFNjEk%2B11q702kd4M1WF2Ooj8CC4s6odNdGoU8PNbM6WGfSWUKPPv%2FTIzn1xMsSgMcQX128Iw4liPg6KEKvC8KPUaZokAt4Rr5P1%2Fn8NhodU4JK1ZBtXTR3JqYioxNDy8lHSQyknz1Qc96yiCFM9otEMdN17BQmsV6Vur1P9ChuWlLVQTn4Vo7CjYV4mz8nNzyGXggXeVbULKeXCvId%2F&X-Amz-Signature=c043d1c14d4e1c542a6a5aacd56b5d8665b655538e9f96ce4cf5952dc35c3ea8&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZQ5XXNXE%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T182839Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECIaCXVzLXdlc3QtMiJHMEUCIQC18qgKwoWc8xOuSpEwDvWADmGpmAJM3AeouSysGPE0YgIgT%2FLQe7y3s6DrnrCe7DQdHzuoRELy7zzwjm%2BpFTTjVZwq%2FwMISxAAGgw2Mzc0MjMxODM4MDUiDBcRSfhpIVZavpe%2BCSrcAwcuYFAxorm1n31OE%2Bhv1ToB22FsbvCzVriwfrcU2Luz597eKYFnmUGJvFwvdbbBYK39nX%2BGKmuOkra%2FeeZTXFHXQ4xZyZWvNzLBWOi%2BvE9kTL3qBI79HEqibu5aVtzQBgGY9tvMIz8TLwVmF4R5iREf6cV5Tin%2FlZE1yWWSKR%2BJxW7odT6PBbQHvJcgzfDidKBP6mVfii7esdjoHBCOcBmSkUb80bdWFi%2Bssl%2BpnJG16lsJp%2FkAXwqk72a0oIlwDLcoMjrdS4xGgsguOq99IwHjKITDBViSY7goXBhc7DT2j053ayTBUpS%2BnsKKKh4%2BVBpyilxtqlDCfyP04HF%2FZKL%2BMGYHjeWiibsLaXZWIuzQEMx%2BEvXgu%2FB1X5BOqmUZfmwkXAO%2B5Ur7lI9Cm5TGO52VtBKQkGzFYW0eE4awx3tXzRhp2nB7J2V7SMaLAWPWIFV8I5AqpqnT9iyPw6pjSEFy0nzPssR%2Fn0vJxxrFjX807XmSHRwj7Axd7s1CwFTFaq5iydQsINfA5%2BVwocvsI0c0HEIP6X%2BQQJXVMXBk20n1KYNMUGlY%2F54MdgJyyWtFrDZGXEa7XhpsdxOh6AgeHoZOFUBo4UZZ2LI8GpNXl652jnjzmw0%2BXxGnWZAZMLSbw70GOqUBHvpy4HufwLv0D677252oliT7VzzRqdUyOxmSkAfIAjE1GjTTMm2fizrkfh7mriFkH88%2F0cUd%2BU2rGAu8otfyHgY0MYuzdxch4lzF%2BOVqWvmn7DSD6BLpzzCxOtINPBOVWIHIDjBc3ntjOWFwMLZ2o4FALM1RVRvfiDcJpThRB%2BB4R7qK%2BpWfYa%2FoYFWW7qAbv%2BJI8lGn8nZULEDgUmln5KmKUOkq&X-Amz-Signature=fc18207028da8c259501444529f87627bdd1a61e2ad92b1e0bcd3c85c1e671c3&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SYUFHVYB%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T182838Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECIaCXVzLXdlc3QtMiJHMEUCICvbLLvQG4z6pOjc94NSCT6gwWvx2qiRYUgop2694hyuAiEA1iGX5bERgJ5RpgWgDrV01h%2Fo4SaLoh%2F32r6WzQcgGP4q%2FwMIShAAGgw2Mzc0MjMxODM4MDUiDE8Wj%2FQUBjrAOmJO%2FircA5ATFLmmGRKJdTwBQfFS88EfvBmNTS5z9rUwcLVV2RTNzzSc4xYEQpvCHaKdT5ZeDKPkajSqt1yuHVTljDFXqs0X%2F88%2BpDd9%2FMyXfH9SRPV%2BNxcu7XGYDKY3ShRZghUFUzjJoYeY7moptV6RG18GoLFagfWw%2Bquj9ktqpvk%2BLQihjAyQrEVWhhcXFpCit1Kh2xLN6gv%2B0waGObAyagZfJW8xhhkiq52XlrpgfSoj0tj38YQqUcjQ8cMAb%2FVueBDBWGvnB98IGdS6kWgqrMCVuX4WA2ZoauukLGU%2FxyPewvP0JF6D9BtuivWURUP3V%2BGQysvTL0%2BTcOOQFO9aqUJpP2MfXZNSiwH8%2BfWhlxPSbV3ippwRVZZzTM4uKPNzYCJWPs2H2ZzYDFqFaker93YYHRnxXKghXEmczhmeiArmhc6j1qS1NTvQaDXMExAi99cC%2FJG42%2Fkwi1Eh7zBgsWD9PNMGgLpanaCZTexyF8Lnc1fnMo9srxX05LNJLw%2BeHy%2BA9JxXo3f5LNPHjPEFB5aRDUunHd%2B2yxvLSogeA6VvrCR77eyJuN783y6qCLuVgLYA5bg8BXQGw7iuRxJBeARJ0wCl%2FqDKxqjdQKgsNg07V9CGsrwRTII41H7PV5iFMLWbw70GOqUBlFygrRggXZo62QeyriremyKajwfo%2FY3GURMyouBrR5N43r6Hx7eFrx5cODzF2jF1VctdybCLeLy1uc0m49l1hrYEwyjp6dCx5TZie6iaXSt23I%2BpcYTaYLU0ugTiCr644ds0TIUqpoG6AnpFpecL8VEwCuugfPrxSEpEZxXWlv1xm7An0QtUCPXPJLEjuwDxQgFuy3ZhWBK0JmrEIdtM6i0VLpoj&X-Amz-Signature=a788624d4f2d68b6a8b91f4af3cca69a053306f7ff0a57a785f3863628eb30b0&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SYUFHVYB%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T182838Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECIaCXVzLXdlc3QtMiJHMEUCICvbLLvQG4z6pOjc94NSCT6gwWvx2qiRYUgop2694hyuAiEA1iGX5bERgJ5RpgWgDrV01h%2Fo4SaLoh%2F32r6WzQcgGP4q%2FwMIShAAGgw2Mzc0MjMxODM4MDUiDE8Wj%2FQUBjrAOmJO%2FircA5ATFLmmGRKJdTwBQfFS88EfvBmNTS5z9rUwcLVV2RTNzzSc4xYEQpvCHaKdT5ZeDKPkajSqt1yuHVTljDFXqs0X%2F88%2BpDd9%2FMyXfH9SRPV%2BNxcu7XGYDKY3ShRZghUFUzjJoYeY7moptV6RG18GoLFagfWw%2Bquj9ktqpvk%2BLQihjAyQrEVWhhcXFpCit1Kh2xLN6gv%2B0waGObAyagZfJW8xhhkiq52XlrpgfSoj0tj38YQqUcjQ8cMAb%2FVueBDBWGvnB98IGdS6kWgqrMCVuX4WA2ZoauukLGU%2FxyPewvP0JF6D9BtuivWURUP3V%2BGQysvTL0%2BTcOOQFO9aqUJpP2MfXZNSiwH8%2BfWhlxPSbV3ippwRVZZzTM4uKPNzYCJWPs2H2ZzYDFqFaker93YYHRnxXKghXEmczhmeiArmhc6j1qS1NTvQaDXMExAi99cC%2FJG42%2Fkwi1Eh7zBgsWD9PNMGgLpanaCZTexyF8Lnc1fnMo9srxX05LNJLw%2BeHy%2BA9JxXo3f5LNPHjPEFB5aRDUunHd%2B2yxvLSogeA6VvrCR77eyJuN783y6qCLuVgLYA5bg8BXQGw7iuRxJBeARJ0wCl%2FqDKxqjdQKgsNg07V9CGsrwRTII41H7PV5iFMLWbw70GOqUBlFygrRggXZo62QeyriremyKajwfo%2FY3GURMyouBrR5N43r6Hx7eFrx5cODzF2jF1VctdybCLeLy1uc0m49l1hrYEwyjp6dCx5TZie6iaXSt23I%2BpcYTaYLU0ugTiCr644ds0TIUqpoG6AnpFpecL8VEwCuugfPrxSEpEZxXWlv1xm7An0QtUCPXPJLEjuwDxQgFuy3ZhWBK0JmrEIdtM6i0VLpoj&X-Amz-Signature=218aafa03075a8a1681ddd9e8563277a8253f6627c443872cf5780f4d91c1003&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SYUFHVYB%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T182838Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECIaCXVzLXdlc3QtMiJHMEUCICvbLLvQG4z6pOjc94NSCT6gwWvx2qiRYUgop2694hyuAiEA1iGX5bERgJ5RpgWgDrV01h%2Fo4SaLoh%2F32r6WzQcgGP4q%2FwMIShAAGgw2Mzc0MjMxODM4MDUiDE8Wj%2FQUBjrAOmJO%2FircA5ATFLmmGRKJdTwBQfFS88EfvBmNTS5z9rUwcLVV2RTNzzSc4xYEQpvCHaKdT5ZeDKPkajSqt1yuHVTljDFXqs0X%2F88%2BpDd9%2FMyXfH9SRPV%2BNxcu7XGYDKY3ShRZghUFUzjJoYeY7moptV6RG18GoLFagfWw%2Bquj9ktqpvk%2BLQihjAyQrEVWhhcXFpCit1Kh2xLN6gv%2B0waGObAyagZfJW8xhhkiq52XlrpgfSoj0tj38YQqUcjQ8cMAb%2FVueBDBWGvnB98IGdS6kWgqrMCVuX4WA2ZoauukLGU%2FxyPewvP0JF6D9BtuivWURUP3V%2BGQysvTL0%2BTcOOQFO9aqUJpP2MfXZNSiwH8%2BfWhlxPSbV3ippwRVZZzTM4uKPNzYCJWPs2H2ZzYDFqFaker93YYHRnxXKghXEmczhmeiArmhc6j1qS1NTvQaDXMExAi99cC%2FJG42%2Fkwi1Eh7zBgsWD9PNMGgLpanaCZTexyF8Lnc1fnMo9srxX05LNJLw%2BeHy%2BA9JxXo3f5LNPHjPEFB5aRDUunHd%2B2yxvLSogeA6VvrCR77eyJuN783y6qCLuVgLYA5bg8BXQGw7iuRxJBeARJ0wCl%2FqDKxqjdQKgsNg07V9CGsrwRTII41H7PV5iFMLWbw70GOqUBlFygrRggXZo62QeyriremyKajwfo%2FY3GURMyouBrR5N43r6Hx7eFrx5cODzF2jF1VctdybCLeLy1uc0m49l1hrYEwyjp6dCx5TZie6iaXSt23I%2BpcYTaYLU0ugTiCr644ds0TIUqpoG6AnpFpecL8VEwCuugfPrxSEpEZxXWlv1xm7An0QtUCPXPJLEjuwDxQgFuy3ZhWBK0JmrEIdtM6i0VLpoj&X-Amz-Signature=58e6b5bc1f1ffd8d1118e6b9c294fdc457c1dee1bad28e1d544a526d67b09753&X-Amz-SignedHeaders=host&x-id=GetObject)


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

