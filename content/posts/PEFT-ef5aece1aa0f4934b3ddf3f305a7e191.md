---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466QMVA3QD6%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250129T163017Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEIf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIHAGiXGibAJhpe2ZJiP\
  rJOzFWI%2F6k8yY8fTcnX8qi5YpAiBL3DbVGI5Wy2duXiu5HaegyN9u8MoNRV%2F8lnhX6SFQxSqI\
  BAiQ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMXeb%2FTk6PG6%2Fcw\
  engKtwDsEulqc67lY40xvbJKcsYowUcpxYT81Ttri4k%2BgTTHFMQVGvgyWdW0trZju0dJJSFgtWo\
  x0AHbAxyMBjiFsxlMWiqw%2FGis62mccFumd%2FYyprcGMV3LU1ZcUaMQWezrplerOzQNFfKFy0O%\
  2F2Ojit8Ys9AlVMvcrDBTxhksBwe2FpYc75MhYJXM%2FMm8CLeFR9326dVQOLLmYb7ECfund8dkWg\
  mjrvIdDwL8kHpHt6NPRJumYhVKh%2F3diSpc03TKSPFOWJRFFgv9NrYxA%2BE8D7FzdkLcMk8Dmza\
  R3hn%2FPLfbFITb7bw0P1QhuPdyXv9jncjVuJO%2BAfzDkhd33UL4yuCEf0uxweemnRB6nSsH6MRT\
  asgBlVmr8nMtCYBXxQx2%2F6BXasTYKopgYaByCkBFc1nzz0eJAQfQbyOvYYggoLqKuYbnEa1rSW3\
  E7f3rSuiMqLL5bukFdCKgm6A4MOrkSTEEudsO5fKI6gYruDaazEg4USXiQj7oRqzp64g2PnMXYQNt\
  tsZ77Iw9FyPXMr1F4S5CBI%2FIdrCXvZZtYBhXwudYs1t1bcdOtyNM3wy3rdPhhxihkGAFNAhEGEV\
  yjxVDBY6tBOjRMeVFEJKWjgdFujZ1NOrfoPTNrmJEyiP6TKUw9oTpvAY6pgETuhmk51T2EyjtgQdD\
  oCdx9uJxIMyflqzem92gq4WfvwO9CgwOpXb239pQBkoXhe4J77cNYypnXRF%2BQSk7syG2lwtwNzj\
  Au1cDGryjaxqD%2FqWdUdT7jzHho8D0P82G71D6jdlzQKJeY%2BczxEHUcYn9ub88mxw6N8YOZ9Jp\
  UZTwgoAgI7kuRJR09EW03oM7VDS0N42ROqO%2BZdgr%2BT3G%2BT02b%2FNNTTik&X-Amz-Signat\
  ure=0d3717df517b2606673450a04f477ee49ae0ea7e03dc8013282ff89d9f969956&X-Amz-Si\
  gnedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466Z7GNBOJP%2F20250129%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250129T162823Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEIf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIQCAFTmhjiVTvSVfHWY6CbMN85oF6J8DQdW4JdwgUABq7wIgFWANFSMqCOawiWCe%2B0F7\
        K750AVI%2FyMLq%2FumC0Tk%2Bv00qiAQIkP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAG\
        gw2Mzc0MjMxODM4MDUiDMtM7KoA1BGcrHUosyrcAyrZVFd%2FzQcbf7OX3Ka1A8KKc2uI0N\
        lpms86KPcECI%2BWP7xs%2FMpzoPeG4gHGWel34vZIqPufz0EEw21wd0WV0RJgHEGiM6pQm\
        i%2FiR4cHLMgkROxGpa0flnOMc%2FmQDb%2FITTcfLi7RBHnz5x0tgKQrDoz2mA69sl%2B7\
        k4PjTr82s8TMzbv9tDQijUyMpSAJKjcthaKjiPS4QTPDE0cOo3DCRfEEl0%2BtUSirBlArc\
        fVkv1MJakmQm5tPm580HPwk2NeGUdJrKl6tD%2Fi1ryGnoUvcGxNIFPyGu09FBZo8eNIVsB\
        OzMC1B%2Fh47jBJaLVOZ7bW9%2BWIA5ydvFNvnRXtz6HGpnztbN%2FdXZHyjQ9W5gi10292\
        %2BCS%2BFcUWrjLhNowWdHeHlimrqfKgccRBiflnFjH2%2F93CQZ3V5WASPsgm%2BIrluyf\
        pSMNY9yv3yajxfLV5ceJ%2FeN2jkNxf5Xyf6zc1jPEWD%2BVya5Uu0%2FhWAj9uWrlzdzrs\
        VAwDgm7v3ayhATuXw57dRfuMQAODNP6h6%2Bd6zeILLZKE1GALiypCFNEuLNIuQHn0PbrX8\
        J6%2FUM%2BVqfNK%2B3QQWKxg1RhYefAUTU8L1jBH6auBlSHp957NLyvIeYwY9PBlF547oq\
        R%2BLKW6f7wHZMIuF6bwGOqUBz8WfeOyoAx15KTGZa5JpcXXeTrcCfQ8eCkvi%2Bld4qTm%\
        2B66btyNYeNaCCOVAZSY6smyBpZygrffQ9WOaWIXopeStSxF3dWSWtlX9mtIFX5244NPaiJ\
        %2FT0SvNKXz5jr62cVbPAvzk3ebIfNHEoYW7Gi69wiGJEde6ItbbfjRauoPPKtjVvBlLmo9\
        p%2B9BiyIQTOppoPl5JZk25w%2BLMnCh7GcckIxH4C&X-Amz-Signature=6da996da3e6e\
        c5d4bde4bf0a14f0d1919dbec307b32608554a035873ffe87b55&X-Amz-SignedHeader\
        s=host&x-id=GetObject"
      expiry_time: "2025-01-29T17:28:23.548Z"
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
UPDATE_TIME: "2025-01-29T16:30:23.128Z"
EXPIRY_TIME: "2025-01-29T17:30:11.279Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YYOPZFOD%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T163011Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIDcZC6t72JUD%2BXcoFYvr9uKs55Ru47CscRC5mghdkPnVAiEA6UCfjCXm2aGIM8kxpnmFI%2BrBL1D%2BFAUZeIYfQhptg3sqiAQIkP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLN5QzTbtGm7jls2cSrcA8qgQ1%2Fpr7oO7PdVvPPQoeidyx%2BrlSQVkYE5yJsUpPs%2F2dxvU5Drs1kxqVRA4phS%2Fbyu6jkiALGtZ01fUnRrUccw%2BMj2V47gtdPh%2BpDzk6uZWbWqLN4XA9kP5Xpmj5QGsh53sFGA3O%2BC59oQ9bYg42TifwmZ%2FCpHa7qbXosy1lynaqI7OrTzH23cV72318ld6ROBRAAAvn3WebojjEYqFE1rt20rewqH8Os1gzn74AXeK8Z2rHiH578Zztcigt4Kqd%2Bf5SY8q8OPZDCCIK9IgV3Ebf3KislaIHMh%2FgYvFZpw4xHWkbgZ63fopKj2NLfu%2Bx70w27Is6J1H6EP2emXipt4IL5t8IJfKzmqGj1Pd2aBVtfbdJFuahhqTGcuFOWBq0L41YJTpA78OjJqVOmSat7EKiUgKzStgNMLuoiL%2BZhpWWlsyrdqLB8jzO8hJiYDnwpRqxbr3HZ8W4gYnADaUAnXPZ0fIGcdtBGdE1Ff%2ByulKV3SY7TL2irbs6fH3vVGHySfrO9ik5faQFbL3RsFF8A9bHuLT%2FRjj2KBAc3FNW6DYG6usEzQrV69u6TYGl9Zt27QHxbNkPy4UleKKCGMDNLTvpTw%2Bi4eUXSJxRP9tA0A6erGlA6vJ%2FOP7qrEMPSE6bwGOqUBQbVRw7IaB0vPBR3Q139TesxPaah26DEWO7%2FXQpDKbaa8MhSNdxdr7O5wlxueUP%2By8eqMlpqyUu6ZE%2BBZGB9x8M%2FMJX6lwKBkTwoLSTtX9HreALpZq28sja%2BxxEQ1CXJC1BKxIUG1p3UZ3h0fjotRUV4VEaJ%2BB0h0V5qg93dYqscsyqq%2BEYzOQ0W9BKj5SOLToKtXSCeFe%2BfPKeRY%2BQCcukv4BQ7c&X-Amz-Signature=88fb11615c9b9bfaa4d62157a3e131dcf8e331453fdf4ae304d370c64aed6ceb&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YYOPZFOD%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T163011Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIDcZC6t72JUD%2BXcoFYvr9uKs55Ru47CscRC5mghdkPnVAiEA6UCfjCXm2aGIM8kxpnmFI%2BrBL1D%2BFAUZeIYfQhptg3sqiAQIkP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLN5QzTbtGm7jls2cSrcA8qgQ1%2Fpr7oO7PdVvPPQoeidyx%2BrlSQVkYE5yJsUpPs%2F2dxvU5Drs1kxqVRA4phS%2Fbyu6jkiALGtZ01fUnRrUccw%2BMj2V47gtdPh%2BpDzk6uZWbWqLN4XA9kP5Xpmj5QGsh53sFGA3O%2BC59oQ9bYg42TifwmZ%2FCpHa7qbXosy1lynaqI7OrTzH23cV72318ld6ROBRAAAvn3WebojjEYqFE1rt20rewqH8Os1gzn74AXeK8Z2rHiH578Zztcigt4Kqd%2Bf5SY8q8OPZDCCIK9IgV3Ebf3KislaIHMh%2FgYvFZpw4xHWkbgZ63fopKj2NLfu%2Bx70w27Is6J1H6EP2emXipt4IL5t8IJfKzmqGj1Pd2aBVtfbdJFuahhqTGcuFOWBq0L41YJTpA78OjJqVOmSat7EKiUgKzStgNMLuoiL%2BZhpWWlsyrdqLB8jzO8hJiYDnwpRqxbr3HZ8W4gYnADaUAnXPZ0fIGcdtBGdE1Ff%2ByulKV3SY7TL2irbs6fH3vVGHySfrO9ik5faQFbL3RsFF8A9bHuLT%2FRjj2KBAc3FNW6DYG6usEzQrV69u6TYGl9Zt27QHxbNkPy4UleKKCGMDNLTvpTw%2Bi4eUXSJxRP9tA0A6erGlA6vJ%2FOP7qrEMPSE6bwGOqUBQbVRw7IaB0vPBR3Q139TesxPaah26DEWO7%2FXQpDKbaa8MhSNdxdr7O5wlxueUP%2By8eqMlpqyUu6ZE%2BBZGB9x8M%2FMJX6lwKBkTwoLSTtX9HreALpZq28sja%2BxxEQ1CXJC1BKxIUG1p3UZ3h0fjotRUV4VEaJ%2BB0h0V5qg93dYqscsyqq%2BEYzOQ0W9BKj5SOLToKtXSCeFe%2BfPKeRY%2BQCcukv4BQ7c&X-Amz-Signature=1f9a53f2d88c9a73135e5e2df3289462f5019024c6298966e4824d7552b28af8&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YYOPZFOD%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T163012Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIDcZC6t72JUD%2BXcoFYvr9uKs55Ru47CscRC5mghdkPnVAiEA6UCfjCXm2aGIM8kxpnmFI%2BrBL1D%2BFAUZeIYfQhptg3sqiAQIkP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLN5QzTbtGm7jls2cSrcA8qgQ1%2Fpr7oO7PdVvPPQoeidyx%2BrlSQVkYE5yJsUpPs%2F2dxvU5Drs1kxqVRA4phS%2Fbyu6jkiALGtZ01fUnRrUccw%2BMj2V47gtdPh%2BpDzk6uZWbWqLN4XA9kP5Xpmj5QGsh53sFGA3O%2BC59oQ9bYg42TifwmZ%2FCpHa7qbXosy1lynaqI7OrTzH23cV72318ld6ROBRAAAvn3WebojjEYqFE1rt20rewqH8Os1gzn74AXeK8Z2rHiH578Zztcigt4Kqd%2Bf5SY8q8OPZDCCIK9IgV3Ebf3KislaIHMh%2FgYvFZpw4xHWkbgZ63fopKj2NLfu%2Bx70w27Is6J1H6EP2emXipt4IL5t8IJfKzmqGj1Pd2aBVtfbdJFuahhqTGcuFOWBq0L41YJTpA78OjJqVOmSat7EKiUgKzStgNMLuoiL%2BZhpWWlsyrdqLB8jzO8hJiYDnwpRqxbr3HZ8W4gYnADaUAnXPZ0fIGcdtBGdE1Ff%2ByulKV3SY7TL2irbs6fH3vVGHySfrO9ik5faQFbL3RsFF8A9bHuLT%2FRjj2KBAc3FNW6DYG6usEzQrV69u6TYGl9Zt27QHxbNkPy4UleKKCGMDNLTvpTw%2Bi4eUXSJxRP9tA0A6erGlA6vJ%2FOP7qrEMPSE6bwGOqUBQbVRw7IaB0vPBR3Q139TesxPaah26DEWO7%2FXQpDKbaa8MhSNdxdr7O5wlxueUP%2By8eqMlpqyUu6ZE%2BBZGB9x8M%2FMJX6lwKBkTwoLSTtX9HreALpZq28sja%2BxxEQ1CXJC1BKxIUG1p3UZ3h0fjotRUV4VEaJ%2BB0h0V5qg93dYqscsyqq%2BEYzOQ0W9BKj5SOLToKtXSCeFe%2BfPKeRY%2BQCcukv4BQ7c&X-Amz-Signature=b3854094fd69f201c7380a2d8b60a29ddc4c7015492fb25b252fc9fe27dce7a0&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YYOPZFOD%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T163012Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIDcZC6t72JUD%2BXcoFYvr9uKs55Ru47CscRC5mghdkPnVAiEA6UCfjCXm2aGIM8kxpnmFI%2BrBL1D%2BFAUZeIYfQhptg3sqiAQIkP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLN5QzTbtGm7jls2cSrcA8qgQ1%2Fpr7oO7PdVvPPQoeidyx%2BrlSQVkYE5yJsUpPs%2F2dxvU5Drs1kxqVRA4phS%2Fbyu6jkiALGtZ01fUnRrUccw%2BMj2V47gtdPh%2BpDzk6uZWbWqLN4XA9kP5Xpmj5QGsh53sFGA3O%2BC59oQ9bYg42TifwmZ%2FCpHa7qbXosy1lynaqI7OrTzH23cV72318ld6ROBRAAAvn3WebojjEYqFE1rt20rewqH8Os1gzn74AXeK8Z2rHiH578Zztcigt4Kqd%2Bf5SY8q8OPZDCCIK9IgV3Ebf3KislaIHMh%2FgYvFZpw4xHWkbgZ63fopKj2NLfu%2Bx70w27Is6J1H6EP2emXipt4IL5t8IJfKzmqGj1Pd2aBVtfbdJFuahhqTGcuFOWBq0L41YJTpA78OjJqVOmSat7EKiUgKzStgNMLuoiL%2BZhpWWlsyrdqLB8jzO8hJiYDnwpRqxbr3HZ8W4gYnADaUAnXPZ0fIGcdtBGdE1Ff%2ByulKV3SY7TL2irbs6fH3vVGHySfrO9ik5faQFbL3RsFF8A9bHuLT%2FRjj2KBAc3FNW6DYG6usEzQrV69u6TYGl9Zt27QHxbNkPy4UleKKCGMDNLTvpTw%2Bi4eUXSJxRP9tA0A6erGlA6vJ%2FOP7qrEMPSE6bwGOqUBQbVRw7IaB0vPBR3Q139TesxPaah26DEWO7%2FXQpDKbaa8MhSNdxdr7O5wlxueUP%2By8eqMlpqyUu6ZE%2BBZGB9x8M%2FMJX6lwKBkTwoLSTtX9HreALpZq28sja%2BxxEQ1CXJC1BKxIUG1p3UZ3h0fjotRUV4VEaJ%2BB0h0V5qg93dYqscsyqq%2BEYzOQ0W9BKj5SOLToKtXSCeFe%2BfPKeRY%2BQCcukv4BQ7c&X-Amz-Signature=d1b04f29b6f42f883cfc998b719b625195575fed5b7fe60ab9c568f3056b05bb&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YYOPZFOD%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T163012Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIDcZC6t72JUD%2BXcoFYvr9uKs55Ru47CscRC5mghdkPnVAiEA6UCfjCXm2aGIM8kxpnmFI%2BrBL1D%2BFAUZeIYfQhptg3sqiAQIkP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLN5QzTbtGm7jls2cSrcA8qgQ1%2Fpr7oO7PdVvPPQoeidyx%2BrlSQVkYE5yJsUpPs%2F2dxvU5Drs1kxqVRA4phS%2Fbyu6jkiALGtZ01fUnRrUccw%2BMj2V47gtdPh%2BpDzk6uZWbWqLN4XA9kP5Xpmj5QGsh53sFGA3O%2BC59oQ9bYg42TifwmZ%2FCpHa7qbXosy1lynaqI7OrTzH23cV72318ld6ROBRAAAvn3WebojjEYqFE1rt20rewqH8Os1gzn74AXeK8Z2rHiH578Zztcigt4Kqd%2Bf5SY8q8OPZDCCIK9IgV3Ebf3KislaIHMh%2FgYvFZpw4xHWkbgZ63fopKj2NLfu%2Bx70w27Is6J1H6EP2emXipt4IL5t8IJfKzmqGj1Pd2aBVtfbdJFuahhqTGcuFOWBq0L41YJTpA78OjJqVOmSat7EKiUgKzStgNMLuoiL%2BZhpWWlsyrdqLB8jzO8hJiYDnwpRqxbr3HZ8W4gYnADaUAnXPZ0fIGcdtBGdE1Ff%2ByulKV3SY7TL2irbs6fH3vVGHySfrO9ik5faQFbL3RsFF8A9bHuLT%2FRjj2KBAc3FNW6DYG6usEzQrV69u6TYGl9Zt27QHxbNkPy4UleKKCGMDNLTvpTw%2Bi4eUXSJxRP9tA0A6erGlA6vJ%2FOP7qrEMPSE6bwGOqUBQbVRw7IaB0vPBR3Q139TesxPaah26DEWO7%2FXQpDKbaa8MhSNdxdr7O5wlxueUP%2By8eqMlpqyUu6ZE%2BBZGB9x8M%2FMJX6lwKBkTwoLSTtX9HreALpZq28sja%2BxxEQ1CXJC1BKxIUG1p3UZ3h0fjotRUV4VEaJ%2BB0h0V5qg93dYqscsyqq%2BEYzOQ0W9BKj5SOLToKtXSCeFe%2BfPKeRY%2BQCcukv4BQ7c&X-Amz-Signature=4ab6916872da9c1ebf66c16df6229f01b11fcd5614c8b2e7ed21f36a0c79c502&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SSHPHIWW%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T163013Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD%2BuIwG4q1JXvmAvqkOfvhp85UrX0e2lSe%2FcyibSGDZ%2BAIgKWAI94iNQYIKsrWTjKF8Q4%2BuVf1C%2BAtbx2HforNg7foqiAQIkP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDAckg9da332w4gXPRircAyAr14qlk9r95Im7Kx036qPb7ERHWSQ26n0IvT4QBULu3LMkM%2BM%2FauZCoG9ErCA7HLsp4ACI8c4b%2FHwLYvN3QfXzsHRkFUWd6CMViwKwMdFlG9DK2c%2B4jbXCrj%2Bnt3J59hnZdq63MlrFd7ENJJe9PqRqmuLAdwiFWZKIwjzYuKUwJQ7wARqY9U30JzlJmuhzi4ZpnkfOzVJEM8W87So6ncoihcxDmEW5pSS7CoyUZSkX8Ui0YMxoyeR%2B26WOi9PSy25be1IVdISCYtzGxN06%2FU6iPuNlmbrsm%2F8%2Fn0%2FaEUq3AUQe2UNnOfIrxhKr9ELVjeMBhG9N8uy83sPFa9mlyoqGFb2C4x%2FWdsMH%2F%2FexDKLiF1RaxcWTX%2B1GIKmKYVCrbOwy6YoN9xUW0Y5fPPPkkWIPfVQtRj0PoLBEjITjGskKhE5g9xoE3AsDDbrdKo%2BQYak17T5pmrHbYfwaC35pDclH1U21SxZYMZfatneYwLAXanm%2B%2FSeVu2Va7hUoqO5oOv3Twww0lud4EYBxRoIWCnwx3Co2JSAgg%2FucLfPZ%2B3Tm%2B1%2FfLTFAo4dJgaLxUowMGACNe1r137ioVJGTavvPE9yJZIpMPD%2BbS%2F6RodGx%2F4tKaU%2BByN3WQD11KW7iMKyF6bwGOqUB58OBOEcc6nt1GbphNba31%2FkVIP5ub6SDqweLuOAjgTbuz%2BB9oB8AbV6onIAp%2BWn%2FpWYNiYZAJYh1onU5Pb5rz3Nvvi54FKHfO6w93A3ojEsjSI8CSlR%2FBPz7og8rOr7jg0xSKfzJlXou4ZAb9Lq4smPcKcLX7GqYOznDDGS1wpZVtK7Af8rmb9rLw5dOGwhTWWoxJlJ6ivOfwdcuIrUQkymDLavW&X-Amz-Signature=52678f07a0af0d357c583849bf4d7791d9a744da7d480517d31d7c108bfab9d8&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662JYH2EL3%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T163017Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIGfgnfjEcScxHLQnyrkqwVtZ7dL8HDZOkzKsCLbKqWeiAiEArfxRkft7vN1wHYfUB3bel5t0eR2SdHVJwIB8zMcquZEqiAQIkP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDO%2B6hLIcXMrYXG128SrcA5lU%2FQWq7gdy69DL2w7kZnTgKeY%2FSrnVLBTIL0%2Fazmzz24WD4kmgAFzxyLeO%2FSjpxNDKWZb1Z%2FoOU0FuC1cjWWTw0%2BeBSL3hZE0xzaAheZ1lF62kbkl9mtxP%2FTpGf5O98o3X61reOyKwymaUYqta6ycvPUbB69KpOFyqomIjkU0zdC0c2%2FDGKIuRfVRrPrEl%2F0PfmZ2MLxyanEnWFpc4aQmsdxo%2FeHzK53v%2FKxeQgLWIUNHjZcBoAo8lBANTJBuSgkTuj6onD1WkS8feiGAhY%2FU6wZVw0L88a3%2B%2BQ%2BaEEDifXtogh1MUoPgHui6bwX%2FhcYLULnZHI1hjgtOWSDRQPbRRGdaCY%2F%2FxDd%2FXP%2BCjCwIAHYA7TM840K6dZNEZXDRlijYyrETo5DTE5MNjtG%2BzHGGzcxVn3IYEoVkohGwPMFOp9z8xEHNHUlMMrBNfznjruAECYP35D0%2BTMzj%2F2PRQEOabnwCHoFT3DUWI2qS5dqSTAeVhORC%2FRHqbzIcQksiBKTimMf1PPar5evnxFUSkOxq%2FeBlbL3r2EQaEAHJ27fc8pATi8Z0A46mS4mgrJ4KEK3%2BQ3wN081yxpG75UhtlNoWtrQWTTy7ga5W%2Ft6Ch41oHo96AT1GD1ocmrn3dMMaF6bwGOqUB6M5IjZ2lVk5c4NjxI2Yro0eSEtBLmVQw3wDNwimR2Xp17Ndb2hd6m9Ccu9zv2PgGC%2FzCdqG7RT9LoqcKGShSfQIFjvYTTisRDCAMn3EXT5TwB1EYWfTJVgAJfGJffBVwKir6zBeG%2BXg%2FnY9amYoNKu9S1%2FOhxGLCtgxT9mGEbSN9gvQ5yriIbGxBIvOx1AcVXjUBWbiriQ3MWtC4wzaxrEjIotaw&X-Amz-Signature=faab74bf12fd3a11096cca057245045ce68936604adf342cdc1b45e3a7e679ab&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YYOPZFOD%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T163012Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIDcZC6t72JUD%2BXcoFYvr9uKs55Ru47CscRC5mghdkPnVAiEA6UCfjCXm2aGIM8kxpnmFI%2BrBL1D%2BFAUZeIYfQhptg3sqiAQIkP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLN5QzTbtGm7jls2cSrcA8qgQ1%2Fpr7oO7PdVvPPQoeidyx%2BrlSQVkYE5yJsUpPs%2F2dxvU5Drs1kxqVRA4phS%2Fbyu6jkiALGtZ01fUnRrUccw%2BMj2V47gtdPh%2BpDzk6uZWbWqLN4XA9kP5Xpmj5QGsh53sFGA3O%2BC59oQ9bYg42TifwmZ%2FCpHa7qbXosy1lynaqI7OrTzH23cV72318ld6ROBRAAAvn3WebojjEYqFE1rt20rewqH8Os1gzn74AXeK8Z2rHiH578Zztcigt4Kqd%2Bf5SY8q8OPZDCCIK9IgV3Ebf3KislaIHMh%2FgYvFZpw4xHWkbgZ63fopKj2NLfu%2Bx70w27Is6J1H6EP2emXipt4IL5t8IJfKzmqGj1Pd2aBVtfbdJFuahhqTGcuFOWBq0L41YJTpA78OjJqVOmSat7EKiUgKzStgNMLuoiL%2BZhpWWlsyrdqLB8jzO8hJiYDnwpRqxbr3HZ8W4gYnADaUAnXPZ0fIGcdtBGdE1Ff%2ByulKV3SY7TL2irbs6fH3vVGHySfrO9ik5faQFbL3RsFF8A9bHuLT%2FRjj2KBAc3FNW6DYG6usEzQrV69u6TYGl9Zt27QHxbNkPy4UleKKCGMDNLTvpTw%2Bi4eUXSJxRP9tA0A6erGlA6vJ%2FOP7qrEMPSE6bwGOqUBQbVRw7IaB0vPBR3Q139TesxPaah26DEWO7%2FXQpDKbaa8MhSNdxdr7O5wlxueUP%2By8eqMlpqyUu6ZE%2BBZGB9x8M%2FMJX6lwKBkTwoLSTtX9HreALpZq28sja%2BxxEQ1CXJC1BKxIUG1p3UZ3h0fjotRUV4VEaJ%2BB0h0V5qg93dYqscsyqq%2BEYzOQ0W9BKj5SOLToKtXSCeFe%2BfPKeRY%2BQCcukv4BQ7c&X-Amz-Signature=87e39fd97644036da29612b5870d3182375a3e777a935f8626fb78f891cb4a4e&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YYOPZFOD%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T163012Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIDcZC6t72JUD%2BXcoFYvr9uKs55Ru47CscRC5mghdkPnVAiEA6UCfjCXm2aGIM8kxpnmFI%2BrBL1D%2BFAUZeIYfQhptg3sqiAQIkP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLN5QzTbtGm7jls2cSrcA8qgQ1%2Fpr7oO7PdVvPPQoeidyx%2BrlSQVkYE5yJsUpPs%2F2dxvU5Drs1kxqVRA4phS%2Fbyu6jkiALGtZ01fUnRrUccw%2BMj2V47gtdPh%2BpDzk6uZWbWqLN4XA9kP5Xpmj5QGsh53sFGA3O%2BC59oQ9bYg42TifwmZ%2FCpHa7qbXosy1lynaqI7OrTzH23cV72318ld6ROBRAAAvn3WebojjEYqFE1rt20rewqH8Os1gzn74AXeK8Z2rHiH578Zztcigt4Kqd%2Bf5SY8q8OPZDCCIK9IgV3Ebf3KislaIHMh%2FgYvFZpw4xHWkbgZ63fopKj2NLfu%2Bx70w27Is6J1H6EP2emXipt4IL5t8IJfKzmqGj1Pd2aBVtfbdJFuahhqTGcuFOWBq0L41YJTpA78OjJqVOmSat7EKiUgKzStgNMLuoiL%2BZhpWWlsyrdqLB8jzO8hJiYDnwpRqxbr3HZ8W4gYnADaUAnXPZ0fIGcdtBGdE1Ff%2ByulKV3SY7TL2irbs6fH3vVGHySfrO9ik5faQFbL3RsFF8A9bHuLT%2FRjj2KBAc3FNW6DYG6usEzQrV69u6TYGl9Zt27QHxbNkPy4UleKKCGMDNLTvpTw%2Bi4eUXSJxRP9tA0A6erGlA6vJ%2FOP7qrEMPSE6bwGOqUBQbVRw7IaB0vPBR3Q139TesxPaah26DEWO7%2FXQpDKbaa8MhSNdxdr7O5wlxueUP%2By8eqMlpqyUu6ZE%2BBZGB9x8M%2FMJX6lwKBkTwoLSTtX9HreALpZq28sja%2BxxEQ1CXJC1BKxIUG1p3UZ3h0fjotRUV4VEaJ%2BB0h0V5qg93dYqscsyqq%2BEYzOQ0W9BKj5SOLToKtXSCeFe%2BfPKeRY%2BQCcukv4BQ7c&X-Amz-Signature=701badc60661689351b0cb971c8b6d9dfd7c55ae206f90fd7aeec63b6b20ab60&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YYOPZFOD%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T163012Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIDcZC6t72JUD%2BXcoFYvr9uKs55Ru47CscRC5mghdkPnVAiEA6UCfjCXm2aGIM8kxpnmFI%2BrBL1D%2BFAUZeIYfQhptg3sqiAQIkP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLN5QzTbtGm7jls2cSrcA8qgQ1%2Fpr7oO7PdVvPPQoeidyx%2BrlSQVkYE5yJsUpPs%2F2dxvU5Drs1kxqVRA4phS%2Fbyu6jkiALGtZ01fUnRrUccw%2BMj2V47gtdPh%2BpDzk6uZWbWqLN4XA9kP5Xpmj5QGsh53sFGA3O%2BC59oQ9bYg42TifwmZ%2FCpHa7qbXosy1lynaqI7OrTzH23cV72318ld6ROBRAAAvn3WebojjEYqFE1rt20rewqH8Os1gzn74AXeK8Z2rHiH578Zztcigt4Kqd%2Bf5SY8q8OPZDCCIK9IgV3Ebf3KislaIHMh%2FgYvFZpw4xHWkbgZ63fopKj2NLfu%2Bx70w27Is6J1H6EP2emXipt4IL5t8IJfKzmqGj1Pd2aBVtfbdJFuahhqTGcuFOWBq0L41YJTpA78OjJqVOmSat7EKiUgKzStgNMLuoiL%2BZhpWWlsyrdqLB8jzO8hJiYDnwpRqxbr3HZ8W4gYnADaUAnXPZ0fIGcdtBGdE1Ff%2ByulKV3SY7TL2irbs6fH3vVGHySfrO9ik5faQFbL3RsFF8A9bHuLT%2FRjj2KBAc3FNW6DYG6usEzQrV69u6TYGl9Zt27QHxbNkPy4UleKKCGMDNLTvpTw%2Bi4eUXSJxRP9tA0A6erGlA6vJ%2FOP7qrEMPSE6bwGOqUBQbVRw7IaB0vPBR3Q139TesxPaah26DEWO7%2FXQpDKbaa8MhSNdxdr7O5wlxueUP%2By8eqMlpqyUu6ZE%2BBZGB9x8M%2FMJX6lwKBkTwoLSTtX9HreALpZq28sja%2BxxEQ1CXJC1BKxIUG1p3UZ3h0fjotRUV4VEaJ%2BB0h0V5qg93dYqscsyqq%2BEYzOQ0W9BKj5SOLToKtXSCeFe%2BfPKeRY%2BQCcukv4BQ7c&X-Amz-Signature=6fdb8bef66a26ce5539b75712cfbf9a8f04c9cb19c96a15ef7b479bd96265587&X-Amz-SignedHeaders=host&x-id=GetObject)


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

