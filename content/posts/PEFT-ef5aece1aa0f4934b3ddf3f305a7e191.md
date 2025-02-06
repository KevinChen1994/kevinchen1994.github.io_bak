---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4666OJSQPHB%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250206T232413Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEE8aCXVzLXdlc3QtMiJIMEYCIQDLSRXHqcqKw0UNwjUkhPeQweDdG0%2FvPtFRFGDyjkOaUwIhA\
  Nyl08tuZgt6Dm54DwfxIwlL%2FSgsAvpVPFSPIoGR9asDKv8DCGgQABoMNjM3NDIzMTgzODA1Igy2\
  ipDxCV22b0oOmoMq3AOOemmeKTzGb8ZWB%2BOthmFGK85MgUhdPD2WXBP4d%2BsmA0Wm%2F%2BpuG\
  HPwOnljxVNVba%2FP31%2BBXc4G9xCmWpxeoV6362kpUHt5cZQGuZRL4fdsdTjkmtUGKvaqEUkfmN\
  tGWiJx%2FHVti4ZW7cbGZuLraT0wq2RqF2W5389Ne15VRwCqrMk646072cc4MDICG0uLv7gV4RUgC\
  vZHcp6lXoR9W%2Bcb%2Bx4OEM3N0ijFf9xX7qBGTAiYhC%2Fgn87m%2FOcSWun%2Bl0oxGhTI971g\
  wIfgFwimOysdToew13WTpVRO7xIUkoUOhw09ONBz3Hv0Z1N2HWrIv9Ci2bpnvmkj3ItT%2BSFp2bJ\
  ARZ4jCgPPaiGDqQ8SH1dW4Jj6Q%2FQT0IEQdHPWy4MA0x%2FsCL7C6iBdc%2Bfyh5QPTD91DnNU%2\
  BgbOOcLaqGUvxoBe14O6dAVESi2CHbODMm2KPbBkoEn3mIDoD1ojbMpo7wxrUAt0cVjAoMxdfwr%2\
  FO0ft6I3N7DoZUKcsh%2FGeTuddF5kaXPq3UXdZGFO65yAGQHGi5IMk1NDQlfWQ3ctmRYsoiK8K7E\
  bTRJyOPgCt4bx%2BnnZKQQ4XYRjMxtPLCLMkB3B5y1ZjBjybeBf%2F49CF0l97%2BR9Dgsw27%2FG\
  TB5cfUzC4%2FpS9BjqkAXFL9PzcT9vN%2Fl7f9gdXkUPdcJgi%2FhBF5V5cBLQSJ1S6%2BDOUmqAu\
  LOH7p9%2BlE%2BRAzDSASr1znjvy%2BAvqQ6y1oIEAsKT%2BNuT%2BE0SmAren9kGYiAQdEJcRU33\
  1D3EPwmOg7KTl9PD6evv%2Ft2tzNCOLqBsr3Xd3coYpTXfm3wMF4NesxR6EPjR1%2BsqHFk1sxSs%\
  2F7MUqVu2ZE42HzpR1PcrTGq2NXt4V&X-Amz-Signature=7ea31babc1f39d54ae1424926eaded\
  0550372fd50c68e1e059f7b399ffe28dbd&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466S33EGMD7%2F20250206%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250206T232253Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEE8aCXVzLXdlc3QtMiJHMEUCIQDrNlrZ0Us5SVflIaXEAGoiQw4pOBm\
        tHe1XBGek7xkUuQIgdND3qVRHNK7ZT2FHjBJCiTn0%2BybJOC2Jp%2Fx3%2FZQ2L%2BYq%2\
        FwMIaBAAGgw2Mzc0MjMxODM4MDUiDAfwZG5embAySFtA8SrcA%2F9jhvCnKjFW8ulioEDkI\
        X7VocS7SYzuwOiKwm1h7YUNq%2FM%2BzKW%2BAjYopp1YO92DxZhek%2B%2FjcDFz3cxyAG\
        ckemnTHRcEZ0%2FKDE%2B6AkyaAf3mepGUR1IHp2bbExmzjddd%2BTrfCfmU51%2B29cXFV\
        iKExtb28IwnLI34JabYex8tWnkAcrkSR3kUBiyH3k%2FDDdc2Z80vx0N9OgQHhpIH57WCFw\
        xqL2wjEVcolG5Wiq9Chugy%2Bp5TR0GD%2FhlJmdVYtABvhdbjFOd3m%2Bd2Wk0gBACkbt0\
        WMlDzm%2BIqC4%2F%2FVCKEIg2LO9wGfVMC5MX6TBPEjLUwLILpFMnZHjYHjPcGfJ118ast\
        ScAemFxKuT6NxyYK9S3wHscOPv5GOhkixCp6fN4p8gPbqr44D%2FSNuCCB7h%2BKoPkxFeK\
        91gIxW2vIVVBrLz2ImwNGJqoCGlZFrPCJ6WEAsMxtt%2BCa7tN%2FgFR2gH4SqIAU79SdWK\
        dQ2gamO%2FiUA2ZQpo83J1vWsm%2BtPmd0H%2Ff0%2Fhwk1vQ5NO5N%2BDIdYFuaKbT1y%2\
        Bn32j3IbJUYtAI%2FRMNP7KUqhlios6oXm7%2FdL4ClpCRgNc6Nrtlj3H11aUiuuZNE0uCI\
        VA3PLfgdjjn%2BR3OVQdzdlA0fZyLlrusZMIf%2FlL0GOqUBoI0aTVeEG2yDdAOV6uYCc9v\
        Jzng3KTuabCLq%2FogRxQF1j6tjZVtpgNtrJ3W8X8VYzxDlD%2BX2UJuA0wY3Tz%2BkJEvH\
        9bRJBCupfqIA%2BeKQLqrtxIyejLzrlPy7BOCc5qAQnHjHgSaohm1UwgPhdR1RiltiSSF1K\
        FhIUj1MB%2BsenTi3EiGAPEbuKxs5f%2BCHw8gtHG4OHKoRrOVY3V63LDv2sLaEE1dy&X-A\
        mz-Signature=d0f796568fce233387786a20543864033520c7f0615dea763a15858489\
        707199&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-07T00:22:53.623Z"
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
UPDATE_TIME: "2025-02-06T23:24:21.088Z"
EXPIRY_TIME: "2025-02-07T00:24:04.763Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46654OBN4QA%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T232405Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEE8aCXVzLXdlc3QtMiJIMEYCIQDTXeZ6XZQvXJGbIMqf8l9vkulsk3%2FA6a5eAUgtg4tj4QIhAOrAVB3WSgealxOlGNXDeViDRHyp8Ln8rxuFV%2FzxQV0SKv8DCGgQABoMNjM3NDIzMTgzODA1IgzUEB1RYgBau%2Ba3WRIq3ANmv1kD5ODww8nbdXUxAtzB2d0b9tEs1gYTuVIoOYkHMdpiXfDXKUbVGxDB0U6%2F27ceBpN0Uu2%2Bxwr5ysOTAFBx3qNYXzIu8%2BZi3GeauYuqZo0LTt7lARKCcf7HAR7r1YxMR0d08Ovcm3v6EkZQUaivDIWQjx2APkMjZuxNZBYUUhjcQgin1QHfHd%2F92sb%2FpqVyD9%2F%2BqUKbaOCqs7c8JTaQ943Vxo7%2B%2FqPl9xvLhiv%2BB%2BljnXvhNRICLV2uYMRxb14FBqrn3cq1x7nP6LcT7PiIW4m8FyE0EWvRICiskJHgLHoPUYdmJCtv%2FL5hIjt%2BsKCE5o8c64I1agQOTHxjM1Pp%2FZbmzJy6n35gd1lYuv%2BCqEIkfIKYA%2BEmJKy7VgZD9q0doOMXW8RcFxjLyTuluh8kN59f1MJrozGz7tMY%2B0dtdP%2FWr%2FZj285zKsorjZq6hmkrEL23XDikf8nJl38jAdU9s%2FSoStiC8ECv8kG0%2FRVNxQ1BhE%2B2pYKwou%2FfRwG7VhRqg4ZTOTa5Wyg%2BqsL8PV0kSKAVpwMdHsmkcMGnoQCptkmBIRXv510lBSD%2F5WKG38a5fI5BvMMqizCirHwq1Zn3xFs1VeQDXow%2B7s9uCQRHViKqvG0HQ%2FZ4%2BIWKOTDG%2FpS9BjqkAeP%2B%2FZu7wbdJ4o3%2BuGuBzauoCNVOkHN7CiOxTbqovIixFjH4C3TEU69yX5PixI21uHa21gq7hHETcMdHEfTDpJ%2FuU4m6ojJaSH7oxMha0qI1lmL3j6yhXhzt3jeToaOEZ6MZsie5bjtBZ4o%2BE4JtJofMr8KqYXaXBpIOYTzGAgkNw6uy%2F9N4FC%2FjDiK8DBbKK3FTOp1zlItps5hu4X2hCJHXRGpS&X-Amz-Signature=63a1998855d3a10e4c56504fff63b923a6162af3e8fba3ecd43f9a9bbc272505&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46654OBN4QA%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T232405Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEE8aCXVzLXdlc3QtMiJIMEYCIQDTXeZ6XZQvXJGbIMqf8l9vkulsk3%2FA6a5eAUgtg4tj4QIhAOrAVB3WSgealxOlGNXDeViDRHyp8Ln8rxuFV%2FzxQV0SKv8DCGgQABoMNjM3NDIzMTgzODA1IgzUEB1RYgBau%2Ba3WRIq3ANmv1kD5ODww8nbdXUxAtzB2d0b9tEs1gYTuVIoOYkHMdpiXfDXKUbVGxDB0U6%2F27ceBpN0Uu2%2Bxwr5ysOTAFBx3qNYXzIu8%2BZi3GeauYuqZo0LTt7lARKCcf7HAR7r1YxMR0d08Ovcm3v6EkZQUaivDIWQjx2APkMjZuxNZBYUUhjcQgin1QHfHd%2F92sb%2FpqVyD9%2F%2BqUKbaOCqs7c8JTaQ943Vxo7%2B%2FqPl9xvLhiv%2BB%2BljnXvhNRICLV2uYMRxb14FBqrn3cq1x7nP6LcT7PiIW4m8FyE0EWvRICiskJHgLHoPUYdmJCtv%2FL5hIjt%2BsKCE5o8c64I1agQOTHxjM1Pp%2FZbmzJy6n35gd1lYuv%2BCqEIkfIKYA%2BEmJKy7VgZD9q0doOMXW8RcFxjLyTuluh8kN59f1MJrozGz7tMY%2B0dtdP%2FWr%2FZj285zKsorjZq6hmkrEL23XDikf8nJl38jAdU9s%2FSoStiC8ECv8kG0%2FRVNxQ1BhE%2B2pYKwou%2FfRwG7VhRqg4ZTOTa5Wyg%2BqsL8PV0kSKAVpwMdHsmkcMGnoQCptkmBIRXv510lBSD%2F5WKG38a5fI5BvMMqizCirHwq1Zn3xFs1VeQDXow%2B7s9uCQRHViKqvG0HQ%2FZ4%2BIWKOTDG%2FpS9BjqkAeP%2B%2FZu7wbdJ4o3%2BuGuBzauoCNVOkHN7CiOxTbqovIixFjH4C3TEU69yX5PixI21uHa21gq7hHETcMdHEfTDpJ%2FuU4m6ojJaSH7oxMha0qI1lmL3j6yhXhzt3jeToaOEZ6MZsie5bjtBZ4o%2BE4JtJofMr8KqYXaXBpIOYTzGAgkNw6uy%2F9N4FC%2FjDiK8DBbKK3FTOp1zlItps5hu4X2hCJHXRGpS&X-Amz-Signature=519932a86709322b82e7aeec107304009727fa66ac5b2018a9f1ade51adba078&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46654OBN4QA%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T232405Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEE8aCXVzLXdlc3QtMiJIMEYCIQDTXeZ6XZQvXJGbIMqf8l9vkulsk3%2FA6a5eAUgtg4tj4QIhAOrAVB3WSgealxOlGNXDeViDRHyp8Ln8rxuFV%2FzxQV0SKv8DCGgQABoMNjM3NDIzMTgzODA1IgzUEB1RYgBau%2Ba3WRIq3ANmv1kD5ODww8nbdXUxAtzB2d0b9tEs1gYTuVIoOYkHMdpiXfDXKUbVGxDB0U6%2F27ceBpN0Uu2%2Bxwr5ysOTAFBx3qNYXzIu8%2BZi3GeauYuqZo0LTt7lARKCcf7HAR7r1YxMR0d08Ovcm3v6EkZQUaivDIWQjx2APkMjZuxNZBYUUhjcQgin1QHfHd%2F92sb%2FpqVyD9%2F%2BqUKbaOCqs7c8JTaQ943Vxo7%2B%2FqPl9xvLhiv%2BB%2BljnXvhNRICLV2uYMRxb14FBqrn3cq1x7nP6LcT7PiIW4m8FyE0EWvRICiskJHgLHoPUYdmJCtv%2FL5hIjt%2BsKCE5o8c64I1agQOTHxjM1Pp%2FZbmzJy6n35gd1lYuv%2BCqEIkfIKYA%2BEmJKy7VgZD9q0doOMXW8RcFxjLyTuluh8kN59f1MJrozGz7tMY%2B0dtdP%2FWr%2FZj285zKsorjZq6hmkrEL23XDikf8nJl38jAdU9s%2FSoStiC8ECv8kG0%2FRVNxQ1BhE%2B2pYKwou%2FfRwG7VhRqg4ZTOTa5Wyg%2BqsL8PV0kSKAVpwMdHsmkcMGnoQCptkmBIRXv510lBSD%2F5WKG38a5fI5BvMMqizCirHwq1Zn3xFs1VeQDXow%2B7s9uCQRHViKqvG0HQ%2FZ4%2BIWKOTDG%2FpS9BjqkAeP%2B%2FZu7wbdJ4o3%2BuGuBzauoCNVOkHN7CiOxTbqovIixFjH4C3TEU69yX5PixI21uHa21gq7hHETcMdHEfTDpJ%2FuU4m6ojJaSH7oxMha0qI1lmL3j6yhXhzt3jeToaOEZ6MZsie5bjtBZ4o%2BE4JtJofMr8KqYXaXBpIOYTzGAgkNw6uy%2F9N4FC%2FjDiK8DBbKK3FTOp1zlItps5hu4X2hCJHXRGpS&X-Amz-Signature=628383d4df06d0c4eb8ad7d76484542e04fbf433593847753324ace52c088748&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46654OBN4QA%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T232405Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEE8aCXVzLXdlc3QtMiJIMEYCIQDTXeZ6XZQvXJGbIMqf8l9vkulsk3%2FA6a5eAUgtg4tj4QIhAOrAVB3WSgealxOlGNXDeViDRHyp8Ln8rxuFV%2FzxQV0SKv8DCGgQABoMNjM3NDIzMTgzODA1IgzUEB1RYgBau%2Ba3WRIq3ANmv1kD5ODww8nbdXUxAtzB2d0b9tEs1gYTuVIoOYkHMdpiXfDXKUbVGxDB0U6%2F27ceBpN0Uu2%2Bxwr5ysOTAFBx3qNYXzIu8%2BZi3GeauYuqZo0LTt7lARKCcf7HAR7r1YxMR0d08Ovcm3v6EkZQUaivDIWQjx2APkMjZuxNZBYUUhjcQgin1QHfHd%2F92sb%2FpqVyD9%2F%2BqUKbaOCqs7c8JTaQ943Vxo7%2B%2FqPl9xvLhiv%2BB%2BljnXvhNRICLV2uYMRxb14FBqrn3cq1x7nP6LcT7PiIW4m8FyE0EWvRICiskJHgLHoPUYdmJCtv%2FL5hIjt%2BsKCE5o8c64I1agQOTHxjM1Pp%2FZbmzJy6n35gd1lYuv%2BCqEIkfIKYA%2BEmJKy7VgZD9q0doOMXW8RcFxjLyTuluh8kN59f1MJrozGz7tMY%2B0dtdP%2FWr%2FZj285zKsorjZq6hmkrEL23XDikf8nJl38jAdU9s%2FSoStiC8ECv8kG0%2FRVNxQ1BhE%2B2pYKwou%2FfRwG7VhRqg4ZTOTa5Wyg%2BqsL8PV0kSKAVpwMdHsmkcMGnoQCptkmBIRXv510lBSD%2F5WKG38a5fI5BvMMqizCirHwq1Zn3xFs1VeQDXow%2B7s9uCQRHViKqvG0HQ%2FZ4%2BIWKOTDG%2FpS9BjqkAeP%2B%2FZu7wbdJ4o3%2BuGuBzauoCNVOkHN7CiOxTbqovIixFjH4C3TEU69yX5PixI21uHa21gq7hHETcMdHEfTDpJ%2FuU4m6ojJaSH7oxMha0qI1lmL3j6yhXhzt3jeToaOEZ6MZsie5bjtBZ4o%2BE4JtJofMr8KqYXaXBpIOYTzGAgkNw6uy%2F9N4FC%2FjDiK8DBbKK3FTOp1zlItps5hu4X2hCJHXRGpS&X-Amz-Signature=e31d12f9716cb01bb7e91a8103d34d935e4a68cc399e7e7e8e4a6860d7b706f3&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46654OBN4QA%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T232405Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEE8aCXVzLXdlc3QtMiJIMEYCIQDTXeZ6XZQvXJGbIMqf8l9vkulsk3%2FA6a5eAUgtg4tj4QIhAOrAVB3WSgealxOlGNXDeViDRHyp8Ln8rxuFV%2FzxQV0SKv8DCGgQABoMNjM3NDIzMTgzODA1IgzUEB1RYgBau%2Ba3WRIq3ANmv1kD5ODww8nbdXUxAtzB2d0b9tEs1gYTuVIoOYkHMdpiXfDXKUbVGxDB0U6%2F27ceBpN0Uu2%2Bxwr5ysOTAFBx3qNYXzIu8%2BZi3GeauYuqZo0LTt7lARKCcf7HAR7r1YxMR0d08Ovcm3v6EkZQUaivDIWQjx2APkMjZuxNZBYUUhjcQgin1QHfHd%2F92sb%2FpqVyD9%2F%2BqUKbaOCqs7c8JTaQ943Vxo7%2B%2FqPl9xvLhiv%2BB%2BljnXvhNRICLV2uYMRxb14FBqrn3cq1x7nP6LcT7PiIW4m8FyE0EWvRICiskJHgLHoPUYdmJCtv%2FL5hIjt%2BsKCE5o8c64I1agQOTHxjM1Pp%2FZbmzJy6n35gd1lYuv%2BCqEIkfIKYA%2BEmJKy7VgZD9q0doOMXW8RcFxjLyTuluh8kN59f1MJrozGz7tMY%2B0dtdP%2FWr%2FZj285zKsorjZq6hmkrEL23XDikf8nJl38jAdU9s%2FSoStiC8ECv8kG0%2FRVNxQ1BhE%2B2pYKwou%2FfRwG7VhRqg4ZTOTa5Wyg%2BqsL8PV0kSKAVpwMdHsmkcMGnoQCptkmBIRXv510lBSD%2F5WKG38a5fI5BvMMqizCirHwq1Zn3xFs1VeQDXow%2B7s9uCQRHViKqvG0HQ%2FZ4%2BIWKOTDG%2FpS9BjqkAeP%2B%2FZu7wbdJ4o3%2BuGuBzauoCNVOkHN7CiOxTbqovIixFjH4C3TEU69yX5PixI21uHa21gq7hHETcMdHEfTDpJ%2FuU4m6ojJaSH7oxMha0qI1lmL3j6yhXhzt3jeToaOEZ6MZsie5bjtBZ4o%2BE4JtJofMr8KqYXaXBpIOYTzGAgkNw6uy%2F9N4FC%2FjDiK8DBbKK3FTOp1zlItps5hu4X2hCJHXRGpS&X-Amz-Signature=841e6bf6b032863c75c2941dec3611b3b8a645d55d2a70cd01de0463ccb317a3&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Y23HDC7L%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T232408Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEE8aCXVzLXdlc3QtMiJHMEUCIG1yHU3NQ%2BuuXVQN3x4mn9%2FI0R3PD7WM21CZRnZzqH2aAiEA%2FyWaphKBCIENEKKOcPvXpN3AZCKvndO8jj2o1LcqjzMq%2FwMIaBAAGgw2Mzc0MjMxODM4MDUiDDsuhwuNr6zXmZHBxyrcAylETM3Zoo4rreh2g90A5K7CTMB8lJnNQuKuZ1aJv3WLRkMOLStJedb3sSj9dMY4n4SbOVjIEqaRi%2Bk739u0LvXMVwXa5RmVU3vp47GrMsv4XMLSPdq%2BTAHhKbcJkrzibBQRsBmT%2BRSX9yc%2B68Q7iKKVgUcUK5mUgPXJNqMuHg2%2BvSOlLicXg2x59HIXhLYeI2XdTzQmsVSWHDjXTpZOm8uHn%2Bx6yZY73wmiKdT61p%2B4C3capnnKKF94FKlrOta015kRNdkXhP8593NuvNimeuYybMho6fbBM1T39fVI191egwaPsor2LVRXVuJoi01eGAIiae25SWkrVrj%2FvtzEQfHYMe9RmBgTOnFE%2Fq0WUejOo%2FL%2Fwz%2FFIpZbGhH9yCGz5gP%2FFNhLauWsJMQuTQY3ntkETPOM8W6NTD7RMbJhNoMlYQPuIUHglFU4WehTH1XMjAoXxnWNIwEN1j%2FEHjZ8GsYBXGvFTApzeJ5h%2FQhCNEHVHIVtrfY8pdhdh8hZTOkfU5ckHJw30IBV38TM28O0fP6duIV9VPl6b8%2Fvclu%2FfJ6D2YwCsMFKYM8sojnas5wq%2BIumaa3J0Sop44cRf41%2Btesi2qq7EVMyUE4CxQXaqkygQLCXZz7z9b6uYhIcMIf%2FlL0GOqUBQaxPtCSHHTWXWFCMdwjeHdwHPawilw%2FY7UCYB6eiGcSGbwYUQ0KQek8UyBBqalfnsMlgbAE7yC%2BvtmV1naLCGQNBiiEJHoYFRiXE7vFbXf3Ie1k3AxjKEfM%2BRKQ5dUlozTb1uDVKCJAa5Oi5QM2x%2BdeEJ1%2BRWhqgAPc6szu5ko2d2KJeF6DByHylDIaHCrP2IWyRfO6b3xjIxYbJq7zwDm8lAIVY&X-Amz-Signature=0816563c54bc18eea0223599acf55245d167e338443654f7bb0af263350cdb2c&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664DYU3CVF%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T232408Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEE8aCXVzLXdlc3QtMiJGMEQCHw8%2B4k6EIvEMW2uM4icPD10UgX%2BaVcsUhUOy777ajZMCIQC7yV7CpRnmzGVBPOGLAmSIaV9VokM4MmqCCOE%2BGMEmHSr%2FAwhoEAAaDDYzNzQyMzE4MzgwNSIMxTPVHClAx5QSiAOQKtwDZql1nfIuijU8f0sGRB8yv7txI5E3YDL%2FkEI6gWEFk38x8mMHZLM02UYUwF4Wi%2BXdrnaYX3L7kky73a82JHiPFu5LeMDX%2B0Dd8O4%2Fl%2BstA0VnRiFr0x5p03kYhdJZkXqhRWmLzr%2FmLrK7KpOdnfqkHXHkDCN5vC7aqIPIUFGNKdpbb3wPHvd3Rqkf%2FSIz6QvaiAOYNeyPpkoYXLr68cxrpNJotslllwhdjSvrPrNuNnXF3DEIjlw%2FEj5l5T7pvlz2V1DVeTgruKVjfu5oLpMR%2FRHC49ydFWFVOKAve1xRKCXSrx7sAXv4bjQd4ULJ9iBCJNVuaO6ee9rbf1M0P2TBLoj%2Bf00RqkrAQ8CQomkI3P%2B%2Fm8UaVjBFLkofXvUr5L0V1APcdBCCLRoUXMgchuwb6C4ToXSQUuYF5U1evIzC5ThYNFhMBR3r5N%2FGPuJVWT8QawlC55fWwgBev1QWwKEQ8sZVxHvSOlbmc%2BQwBW9BZ%2FyJrkx7oVAawBrb6MjrLITFkz9uE9earQvfsuSRwe6gUfLFIlqy0B0UJ8eBFEsVnVK8GGr%2FpX5CmZzVrv6fGvjWI9%2F%2Buikf0K9dfLI0TXkJ3nv%2FGnnDgsSyf8ZUkjMOQJ56SwMXX7hGPtetkLEwvv6UvQY6pgHIvMqwfdGlqjiJX5doAOyZxjDzXJPDJ93HFbEbgQrTqyJZ%2B9s9a7sRFdYL6eP17u724xQq1Ln78rD6jWQ9zJ9U5YvJNkF986YQv%2Fklcxo1WHE%2FNOEqMu9%2Fef85REZ%2BYYxC6Kj3K%2Flwh1j5k1ldj2tH5Ggnl76iiPXoIiv1DqcqVXk2%2Fa6uMMoC8qHiw9qN6%2F2qSR20kucjoIbKvHZYIOmrQFETCvly&X-Amz-Signature=f7fa153f4f5f9fab061871aff4f12c68f4096c64897b0f4797eb7eb324b40229&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46654OBN4QA%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T232405Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEE8aCXVzLXdlc3QtMiJIMEYCIQDTXeZ6XZQvXJGbIMqf8l9vkulsk3%2FA6a5eAUgtg4tj4QIhAOrAVB3WSgealxOlGNXDeViDRHyp8Ln8rxuFV%2FzxQV0SKv8DCGgQABoMNjM3NDIzMTgzODA1IgzUEB1RYgBau%2Ba3WRIq3ANmv1kD5ODww8nbdXUxAtzB2d0b9tEs1gYTuVIoOYkHMdpiXfDXKUbVGxDB0U6%2F27ceBpN0Uu2%2Bxwr5ysOTAFBx3qNYXzIu8%2BZi3GeauYuqZo0LTt7lARKCcf7HAR7r1YxMR0d08Ovcm3v6EkZQUaivDIWQjx2APkMjZuxNZBYUUhjcQgin1QHfHd%2F92sb%2FpqVyD9%2F%2BqUKbaOCqs7c8JTaQ943Vxo7%2B%2FqPl9xvLhiv%2BB%2BljnXvhNRICLV2uYMRxb14FBqrn3cq1x7nP6LcT7PiIW4m8FyE0EWvRICiskJHgLHoPUYdmJCtv%2FL5hIjt%2BsKCE5o8c64I1agQOTHxjM1Pp%2FZbmzJy6n35gd1lYuv%2BCqEIkfIKYA%2BEmJKy7VgZD9q0doOMXW8RcFxjLyTuluh8kN59f1MJrozGz7tMY%2B0dtdP%2FWr%2FZj285zKsorjZq6hmkrEL23XDikf8nJl38jAdU9s%2FSoStiC8ECv8kG0%2FRVNxQ1BhE%2B2pYKwou%2FfRwG7VhRqg4ZTOTa5Wyg%2BqsL8PV0kSKAVpwMdHsmkcMGnoQCptkmBIRXv510lBSD%2F5WKG38a5fI5BvMMqizCirHwq1Zn3xFs1VeQDXow%2B7s9uCQRHViKqvG0HQ%2FZ4%2BIWKOTDG%2FpS9BjqkAeP%2B%2FZu7wbdJ4o3%2BuGuBzauoCNVOkHN7CiOxTbqovIixFjH4C3TEU69yX5PixI21uHa21gq7hHETcMdHEfTDpJ%2FuU4m6ojJaSH7oxMha0qI1lmL3j6yhXhzt3jeToaOEZ6MZsie5bjtBZ4o%2BE4JtJofMr8KqYXaXBpIOYTzGAgkNw6uy%2F9N4FC%2FjDiK8DBbKK3FTOp1zlItps5hu4X2hCJHXRGpS&X-Amz-Signature=953c3c061c41276171ef6d5f369c21b7cb0468bd741739c34b8e836f75eee1ab&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46654OBN4QA%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T232405Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEE8aCXVzLXdlc3QtMiJIMEYCIQDTXeZ6XZQvXJGbIMqf8l9vkulsk3%2FA6a5eAUgtg4tj4QIhAOrAVB3WSgealxOlGNXDeViDRHyp8Ln8rxuFV%2FzxQV0SKv8DCGgQABoMNjM3NDIzMTgzODA1IgzUEB1RYgBau%2Ba3WRIq3ANmv1kD5ODww8nbdXUxAtzB2d0b9tEs1gYTuVIoOYkHMdpiXfDXKUbVGxDB0U6%2F27ceBpN0Uu2%2Bxwr5ysOTAFBx3qNYXzIu8%2BZi3GeauYuqZo0LTt7lARKCcf7HAR7r1YxMR0d08Ovcm3v6EkZQUaivDIWQjx2APkMjZuxNZBYUUhjcQgin1QHfHd%2F92sb%2FpqVyD9%2F%2BqUKbaOCqs7c8JTaQ943Vxo7%2B%2FqPl9xvLhiv%2BB%2BljnXvhNRICLV2uYMRxb14FBqrn3cq1x7nP6LcT7PiIW4m8FyE0EWvRICiskJHgLHoPUYdmJCtv%2FL5hIjt%2BsKCE5o8c64I1agQOTHxjM1Pp%2FZbmzJy6n35gd1lYuv%2BCqEIkfIKYA%2BEmJKy7VgZD9q0doOMXW8RcFxjLyTuluh8kN59f1MJrozGz7tMY%2B0dtdP%2FWr%2FZj285zKsorjZq6hmkrEL23XDikf8nJl38jAdU9s%2FSoStiC8ECv8kG0%2FRVNxQ1BhE%2B2pYKwou%2FfRwG7VhRqg4ZTOTa5Wyg%2BqsL8PV0kSKAVpwMdHsmkcMGnoQCptkmBIRXv510lBSD%2F5WKG38a5fI5BvMMqizCirHwq1Zn3xFs1VeQDXow%2B7s9uCQRHViKqvG0HQ%2FZ4%2BIWKOTDG%2FpS9BjqkAeP%2B%2FZu7wbdJ4o3%2BuGuBzauoCNVOkHN7CiOxTbqovIixFjH4C3TEU69yX5PixI21uHa21gq7hHETcMdHEfTDpJ%2FuU4m6ojJaSH7oxMha0qI1lmL3j6yhXhzt3jeToaOEZ6MZsie5bjtBZ4o%2BE4JtJofMr8KqYXaXBpIOYTzGAgkNw6uy%2F9N4FC%2FjDiK8DBbKK3FTOp1zlItps5hu4X2hCJHXRGpS&X-Amz-Signature=acccd25c4728a43046e8d0a06ffb273285b7580a434e2e04284f65ee8d905185&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46654OBN4QA%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T232405Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEE8aCXVzLXdlc3QtMiJIMEYCIQDTXeZ6XZQvXJGbIMqf8l9vkulsk3%2FA6a5eAUgtg4tj4QIhAOrAVB3WSgealxOlGNXDeViDRHyp8Ln8rxuFV%2FzxQV0SKv8DCGgQABoMNjM3NDIzMTgzODA1IgzUEB1RYgBau%2Ba3WRIq3ANmv1kD5ODww8nbdXUxAtzB2d0b9tEs1gYTuVIoOYkHMdpiXfDXKUbVGxDB0U6%2F27ceBpN0Uu2%2Bxwr5ysOTAFBx3qNYXzIu8%2BZi3GeauYuqZo0LTt7lARKCcf7HAR7r1YxMR0d08Ovcm3v6EkZQUaivDIWQjx2APkMjZuxNZBYUUhjcQgin1QHfHd%2F92sb%2FpqVyD9%2F%2BqUKbaOCqs7c8JTaQ943Vxo7%2B%2FqPl9xvLhiv%2BB%2BljnXvhNRICLV2uYMRxb14FBqrn3cq1x7nP6LcT7PiIW4m8FyE0EWvRICiskJHgLHoPUYdmJCtv%2FL5hIjt%2BsKCE5o8c64I1agQOTHxjM1Pp%2FZbmzJy6n35gd1lYuv%2BCqEIkfIKYA%2BEmJKy7VgZD9q0doOMXW8RcFxjLyTuluh8kN59f1MJrozGz7tMY%2B0dtdP%2FWr%2FZj285zKsorjZq6hmkrEL23XDikf8nJl38jAdU9s%2FSoStiC8ECv8kG0%2FRVNxQ1BhE%2B2pYKwou%2FfRwG7VhRqg4ZTOTa5Wyg%2BqsL8PV0kSKAVpwMdHsmkcMGnoQCptkmBIRXv510lBSD%2F5WKG38a5fI5BvMMqizCirHwq1Zn3xFs1VeQDXow%2B7s9uCQRHViKqvG0HQ%2FZ4%2BIWKOTDG%2FpS9BjqkAeP%2B%2FZu7wbdJ4o3%2BuGuBzauoCNVOkHN7CiOxTbqovIixFjH4C3TEU69yX5PixI21uHa21gq7hHETcMdHEfTDpJ%2FuU4m6ojJaSH7oxMha0qI1lmL3j6yhXhzt3jeToaOEZ6MZsie5bjtBZ4o%2BE4JtJofMr8KqYXaXBpIOYTzGAgkNw6uy%2F9N4FC%2FjDiK8DBbKK3FTOp1zlItps5hu4X2hCJHXRGpS&X-Amz-Signature=37eca42608398af743d2fb217c26645b3079254efd6b628d2e20cce5ae52244d&X-Amz-SignedHeaders=host&x-id=GetObject)


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

