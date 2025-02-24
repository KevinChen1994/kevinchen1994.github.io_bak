---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466QZFESARY%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250224T042808Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEOz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCID4lTcezJF6C%2F5Ndv\
  2hZ9caBtn5bTk9qGgzzdmPWoQcXAiBZZwUonWR1cxuBtMaL1HKpSvKhN%2BTFtNvIT91JuHQ3Fyr%\
  2FAwglEAAaDDYzNzQyMzE4MzgwNSIM8lRBTkW%2B0qznrPVUKtwDrbq2okv7GNWJz%2Bt1jvPb45Q\
  FFFuZalUtKwmqi5YJu6QsBtnpdP6dX1vMAIizrVtVM6%2BHwuyGmR02vsV1D7fsnaEQQFu4SnDrxO\
  zyn5uk2bKvtEzTP4JBzqytyBEMAPY1AI6Rmuy7sBNKsqfgdC%2FWPUXT%2BFnkYCSudGu7LfE2DCw\
  1QLa0NO06KeavXD6qV22EpS6%2BpkiUE9F4Rkm8Ng1kQt41mEleRdomM9vFcycusohF0jXJB1IBBZ\
  cu%2B5W0luvbERoB9HFBT8W3Uqj6keZ92WrAD19PRs3olcqjBxC6AAXClnFLw6q7L8Na4iJ2dztdF\
  1dx3gNCvJ9Gy%2BdR4RFv0wX2mOGjHPqfGRcOWuMmWeMjWt6yRqz7ahD0AUNiGAqtr6P0QLdYsDZQ\
  eWqsdaYfSel2cQcriGVDY5PPz6D9V3YbPU62%2BNvZzdZf2fgdpuFZiyVme0dFlvtN6Us9COm3a44\
  0SBnrCDXbsgFyTAfGSvJW%2FfAfF%2BrOm8M3s09Dafthd4p%2BdTwclnZqEJYh2l5K77vFlBrJ9s\
  zb%2FFGfRXIsf%2FBtOyd10YCPCCojS9vBf9VJvv213gKtS59LY%2BpH5tNUq2JzbbWYC8ZhSO2jW\
  KZo%2BRmvAO9oY99b3fgAVpYwh%2BLvvQY6pgFLTHiTvQev4ZKVFx7DFVYAtW9mxvuN2ewxT7KRPr\
  tQ9klWgNHoqrJ1rImnezDDzby72Xjj2oGwcc1BF1kkvkzkGDRmR5O8GCq6T0coRzsbDrGtlzuWh%2\
  BSx88rkrOnOQuQepp5S%2B5YQGhHQTG5Chsm%2F%2Fg4zrd0VXdY33OsKvVNbFtiIEfdQQOb2MQBX\
  zBIdpLTL0qzBtyw8CTBzDkkWD3%2BcoLAidTYs&X-Amz-Signature=00a82a14ca721b16b12a14\
  db077f8decdba62304bc1ec5425ef2faa4281a6759&X-Amz-SignedHeaders=host&x-id=GetO\
  bject"
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
        redential=ASIAZI2LB466T5HGJIV3%2F20250224%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250224T042654Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEOz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQ\
        CIGathPAfRQofsSyUcczr3LVCJUfDGhEEyOYKGuQcbC4HAiB75tcZcBFwZpuLk0YGwpzQhm\
        EPIuN1KvC96BtgonPtqCr%2FAwglEAAaDDYzNzQyMzE4MzgwNSIML%2FKwsfA8hHC0FnFjK\
        twDJbSgYDdEhvlgautq5KaI4b40JRMj2%2F%2Bs7sN02ad5QOwudslMXQmG%2FsLapRBdX3\
        3YF1xcNFB1HNATyE6%2BMK0f%2B0AF%2Bl96JXxyOjEgXfpVPGdx3ioWLojKdXZam84dEs%\
        2BMblmjLFBkLi%2FHjeFEC09RMIQi3rAwxCbVzOjh4%2FvVNEovnW6ihybVHCFowCzmUBei\
        kxeBNSFGWevoUK6UnWeCvRJ5G0tQmTvIdIEIIvd4aVD2Yq7%2Bn1LOYazZQJIa4aDHv77PX\
        bOAGzlbAdIfeCqqRnHfQPxYtM%2FUeusO314akt1aFM%2B4EUY5%2BSQGTI34A3eShY6gnK\
        yaS7p7QX0O83wQZ%2BAAoaxXbY0l92yOD9%2F0eaV%2BydM4U1OQ4nP9oIZWd9H6FcrEko3\
        EkBbW6w2XGV4LLpJ7d03daS9%2FzrdwYbvVdR5LPTt1uERdx6mjnRVQtYVL4TvPgMpRGVJ7\
        Ml5vth3MY8rFbZco9hHMl6SpxJ%2B2irpbSTTnvGCKSB%2BBp%2Bkl7PZxgDyDBXKdZS2%2\
        FwwujvVb28tp%2BRhVy06JUDgee0TG6TFsEO6%2BcNx0A%2B659pGYCt6GZpNDroQhRlEB%\
        2Br8s4v7TfAD%2BDz8A5qdjqYt1CUwEKavimAxm%2Bk%2B%2BUW8DDTqMwweHvvQY6pgGE3\
        2TjGzja395xrvF6%2BKbWcaGM0qDcXa9MzwiT56tjMHJnH045%2B%2FgRXOnNqRcV3US4wP\
        7s2D0RQ2mZy5j6QCKe36Jg%2B7PfnZXeb5E5x67JgGVtDGSKe3%2FLTnWlm%2Bsk%2F8uAq\
        Ko7jaanxIlvLeRVwzDDTEoY%2BJXCmBkCYXkAIzw8PqKzxjJ0G81ONQZedsd2D67ljct%2F\
        bldKfy7GQdIf%2BKc3ddgV35Nh&X-Amz-Signature=377bf6195647d12cf7cda7a29d3f\
        1cf942d7b9a6456abcbb183659c59aef3a3c&X-Amz-SignedHeaders=host&x-id=GetO\
        bject"
      expiry_time: "2025-02-24T05:26:54.385Z"
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
UPDATE_TIME: "2025-02-24T04:28:13.428Z"
EXPIRY_TIME: "2025-02-24T05:28:05.744Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UFSQC3DB%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T042806Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCpMsWnpEw0iAeqRS60OebxGzegDykVN4RBQfzHsKDF1wIhALK9FekNzuQS47rhHA3jTZd2OR%2Bl0kHysC9glMtu7NXhKv8DCCUQABoMNjM3NDIzMTgzODA1IgyIDomfzIn5JST5bgMq3AM2wfImc7DFHTb668aKbmnGnsBw%2FmAz9TXL8bZ7jrdr%2FzC5RagGQHyLncmCrR%2FEVYC%2FWdMEV3ALt5kWk4%2BsY1x8KeULUGLiCDm5xIVP8U3La%2Fsjn4NcjEgedbeL2lA16%2FdS%2B6qV85YNAgHkWWvgHcU7wN3jr9UrgUSKf5Jmxo0n8aw44A3Bi96OJOMu%2BVGPuEnquR5O0ckn1YMqdb%2FavakbMHqKDKa5nG3nN7d8FF6W%2FO4Swb5qa0Hbr%2B7APp1majbkUZeFFVQpgvKIllBWSkWo2x4KAgBzX169OXql%2FNHEIOIH9a08VgOYhZYQjBfJOqxJ%2BHD1l%2By24rn93MjHLRiKjTkKl9o4cdjoZs01gJdTUI0xJBeo%2BooiX1ugo3PNdNx%2BzxvC%2FGJHDbzosLS%2BptZfpX4Nck02TkF0ZGjg2dtUbvWXbWyWDGDhlTcuk8171ZUStnzgVcpAkxwAXYFsjXDWgxehu3FSGvety1tGtoc71xhsJ%2FeZ5W2nsKuRI5pDlI3vmm34EOKd2S2f9i0YX0TlGhtwfsg9cMf7VGWhXkL0prg%2B7pv2LLWrd%2Bg1kkf%2FYEuCkhxtiU%2B04i9WJBoAfCaJBIgWdIHnJPguNqN6s1%2BcEp52Na2E%2BT2D1K4lmjCa4u%2B9BjqkAdTphe5xdJIbaPHwh9626E%2B0EgpK59zocbMcIRjoFI7pVZyGAGC4EmWzxpUGkNOfu34S1sTqok8fOm5QNvKGAeB48I6vLsrwutvnIkamOLW10L3S63USwJqbcvDzYkVOtBVABSF3%2Fqb6PuXSPzBFFldegk%2FuiCIvY8uVRV9pAD7Vz6OQ920kv9Ob2dOWw2pnJnqg8pDH0%2BG%2BdEcg875tazjjg6MB&X-Amz-Signature=8811c33094c389f82df61df03db6981cddd10439e6497e860c5568f146c9057d&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UFSQC3DB%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T042806Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCpMsWnpEw0iAeqRS60OebxGzegDykVN4RBQfzHsKDF1wIhALK9FekNzuQS47rhHA3jTZd2OR%2Bl0kHysC9glMtu7NXhKv8DCCUQABoMNjM3NDIzMTgzODA1IgyIDomfzIn5JST5bgMq3AM2wfImc7DFHTb668aKbmnGnsBw%2FmAz9TXL8bZ7jrdr%2FzC5RagGQHyLncmCrR%2FEVYC%2FWdMEV3ALt5kWk4%2BsY1x8KeULUGLiCDm5xIVP8U3La%2Fsjn4NcjEgedbeL2lA16%2FdS%2B6qV85YNAgHkWWvgHcU7wN3jr9UrgUSKf5Jmxo0n8aw44A3Bi96OJOMu%2BVGPuEnquR5O0ckn1YMqdb%2FavakbMHqKDKa5nG3nN7d8FF6W%2FO4Swb5qa0Hbr%2B7APp1majbkUZeFFVQpgvKIllBWSkWo2x4KAgBzX169OXql%2FNHEIOIH9a08VgOYhZYQjBfJOqxJ%2BHD1l%2By24rn93MjHLRiKjTkKl9o4cdjoZs01gJdTUI0xJBeo%2BooiX1ugo3PNdNx%2BzxvC%2FGJHDbzosLS%2BptZfpX4Nck02TkF0ZGjg2dtUbvWXbWyWDGDhlTcuk8171ZUStnzgVcpAkxwAXYFsjXDWgxehu3FSGvety1tGtoc71xhsJ%2FeZ5W2nsKuRI5pDlI3vmm34EOKd2S2f9i0YX0TlGhtwfsg9cMf7VGWhXkL0prg%2B7pv2LLWrd%2Bg1kkf%2FYEuCkhxtiU%2B04i9WJBoAfCaJBIgWdIHnJPguNqN6s1%2BcEp52Na2E%2BT2D1K4lmjCa4u%2B9BjqkAdTphe5xdJIbaPHwh9626E%2B0EgpK59zocbMcIRjoFI7pVZyGAGC4EmWzxpUGkNOfu34S1sTqok8fOm5QNvKGAeB48I6vLsrwutvnIkamOLW10L3S63USwJqbcvDzYkVOtBVABSF3%2Fqb6PuXSPzBFFldegk%2FuiCIvY8uVRV9pAD7Vz6OQ920kv9Ob2dOWw2pnJnqg8pDH0%2BG%2BdEcg875tazjjg6MB&X-Amz-Signature=ccb5b562b3ba96ae102d0d9e55c45df4b254fd2cc78b852a2015c6e0d208dbb1&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UFSQC3DB%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T042806Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCpMsWnpEw0iAeqRS60OebxGzegDykVN4RBQfzHsKDF1wIhALK9FekNzuQS47rhHA3jTZd2OR%2Bl0kHysC9glMtu7NXhKv8DCCUQABoMNjM3NDIzMTgzODA1IgyIDomfzIn5JST5bgMq3AM2wfImc7DFHTb668aKbmnGnsBw%2FmAz9TXL8bZ7jrdr%2FzC5RagGQHyLncmCrR%2FEVYC%2FWdMEV3ALt5kWk4%2BsY1x8KeULUGLiCDm5xIVP8U3La%2Fsjn4NcjEgedbeL2lA16%2FdS%2B6qV85YNAgHkWWvgHcU7wN3jr9UrgUSKf5Jmxo0n8aw44A3Bi96OJOMu%2BVGPuEnquR5O0ckn1YMqdb%2FavakbMHqKDKa5nG3nN7d8FF6W%2FO4Swb5qa0Hbr%2B7APp1majbkUZeFFVQpgvKIllBWSkWo2x4KAgBzX169OXql%2FNHEIOIH9a08VgOYhZYQjBfJOqxJ%2BHD1l%2By24rn93MjHLRiKjTkKl9o4cdjoZs01gJdTUI0xJBeo%2BooiX1ugo3PNdNx%2BzxvC%2FGJHDbzosLS%2BptZfpX4Nck02TkF0ZGjg2dtUbvWXbWyWDGDhlTcuk8171ZUStnzgVcpAkxwAXYFsjXDWgxehu3FSGvety1tGtoc71xhsJ%2FeZ5W2nsKuRI5pDlI3vmm34EOKd2S2f9i0YX0TlGhtwfsg9cMf7VGWhXkL0prg%2B7pv2LLWrd%2Bg1kkf%2FYEuCkhxtiU%2B04i9WJBoAfCaJBIgWdIHnJPguNqN6s1%2BcEp52Na2E%2BT2D1K4lmjCa4u%2B9BjqkAdTphe5xdJIbaPHwh9626E%2B0EgpK59zocbMcIRjoFI7pVZyGAGC4EmWzxpUGkNOfu34S1sTqok8fOm5QNvKGAeB48I6vLsrwutvnIkamOLW10L3S63USwJqbcvDzYkVOtBVABSF3%2Fqb6PuXSPzBFFldegk%2FuiCIvY8uVRV9pAD7Vz6OQ920kv9Ob2dOWw2pnJnqg8pDH0%2BG%2BdEcg875tazjjg6MB&X-Amz-Signature=fe5e12ce75fcde34b57900db1288312d6237baae718e3fdf6ec4b5da11e62268&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UFSQC3DB%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T042806Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCpMsWnpEw0iAeqRS60OebxGzegDykVN4RBQfzHsKDF1wIhALK9FekNzuQS47rhHA3jTZd2OR%2Bl0kHysC9glMtu7NXhKv8DCCUQABoMNjM3NDIzMTgzODA1IgyIDomfzIn5JST5bgMq3AM2wfImc7DFHTb668aKbmnGnsBw%2FmAz9TXL8bZ7jrdr%2FzC5RagGQHyLncmCrR%2FEVYC%2FWdMEV3ALt5kWk4%2BsY1x8KeULUGLiCDm5xIVP8U3La%2Fsjn4NcjEgedbeL2lA16%2FdS%2B6qV85YNAgHkWWvgHcU7wN3jr9UrgUSKf5Jmxo0n8aw44A3Bi96OJOMu%2BVGPuEnquR5O0ckn1YMqdb%2FavakbMHqKDKa5nG3nN7d8FF6W%2FO4Swb5qa0Hbr%2B7APp1majbkUZeFFVQpgvKIllBWSkWo2x4KAgBzX169OXql%2FNHEIOIH9a08VgOYhZYQjBfJOqxJ%2BHD1l%2By24rn93MjHLRiKjTkKl9o4cdjoZs01gJdTUI0xJBeo%2BooiX1ugo3PNdNx%2BzxvC%2FGJHDbzosLS%2BptZfpX4Nck02TkF0ZGjg2dtUbvWXbWyWDGDhlTcuk8171ZUStnzgVcpAkxwAXYFsjXDWgxehu3FSGvety1tGtoc71xhsJ%2FeZ5W2nsKuRI5pDlI3vmm34EOKd2S2f9i0YX0TlGhtwfsg9cMf7VGWhXkL0prg%2B7pv2LLWrd%2Bg1kkf%2FYEuCkhxtiU%2B04i9WJBoAfCaJBIgWdIHnJPguNqN6s1%2BcEp52Na2E%2BT2D1K4lmjCa4u%2B9BjqkAdTphe5xdJIbaPHwh9626E%2B0EgpK59zocbMcIRjoFI7pVZyGAGC4EmWzxpUGkNOfu34S1sTqok8fOm5QNvKGAeB48I6vLsrwutvnIkamOLW10L3S63USwJqbcvDzYkVOtBVABSF3%2Fqb6PuXSPzBFFldegk%2FuiCIvY8uVRV9pAD7Vz6OQ920kv9Ob2dOWw2pnJnqg8pDH0%2BG%2BdEcg875tazjjg6MB&X-Amz-Signature=c72c2ac7c8117ff71cf2fb30b0975cbc2c0d2153ee39c859773e6e2f357e681e&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UFSQC3DB%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T042806Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCpMsWnpEw0iAeqRS60OebxGzegDykVN4RBQfzHsKDF1wIhALK9FekNzuQS47rhHA3jTZd2OR%2Bl0kHysC9glMtu7NXhKv8DCCUQABoMNjM3NDIzMTgzODA1IgyIDomfzIn5JST5bgMq3AM2wfImc7DFHTb668aKbmnGnsBw%2FmAz9TXL8bZ7jrdr%2FzC5RagGQHyLncmCrR%2FEVYC%2FWdMEV3ALt5kWk4%2BsY1x8KeULUGLiCDm5xIVP8U3La%2Fsjn4NcjEgedbeL2lA16%2FdS%2B6qV85YNAgHkWWvgHcU7wN3jr9UrgUSKf5Jmxo0n8aw44A3Bi96OJOMu%2BVGPuEnquR5O0ckn1YMqdb%2FavakbMHqKDKa5nG3nN7d8FF6W%2FO4Swb5qa0Hbr%2B7APp1majbkUZeFFVQpgvKIllBWSkWo2x4KAgBzX169OXql%2FNHEIOIH9a08VgOYhZYQjBfJOqxJ%2BHD1l%2By24rn93MjHLRiKjTkKl9o4cdjoZs01gJdTUI0xJBeo%2BooiX1ugo3PNdNx%2BzxvC%2FGJHDbzosLS%2BptZfpX4Nck02TkF0ZGjg2dtUbvWXbWyWDGDhlTcuk8171ZUStnzgVcpAkxwAXYFsjXDWgxehu3FSGvety1tGtoc71xhsJ%2FeZ5W2nsKuRI5pDlI3vmm34EOKd2S2f9i0YX0TlGhtwfsg9cMf7VGWhXkL0prg%2B7pv2LLWrd%2Bg1kkf%2FYEuCkhxtiU%2B04i9WJBoAfCaJBIgWdIHnJPguNqN6s1%2BcEp52Na2E%2BT2D1K4lmjCa4u%2B9BjqkAdTphe5xdJIbaPHwh9626E%2B0EgpK59zocbMcIRjoFI7pVZyGAGC4EmWzxpUGkNOfu34S1sTqok8fOm5QNvKGAeB48I6vLsrwutvnIkamOLW10L3S63USwJqbcvDzYkVOtBVABSF3%2Fqb6PuXSPzBFFldegk%2FuiCIvY8uVRV9pAD7Vz6OQ920kv9Ob2dOWw2pnJnqg8pDH0%2BG%2BdEcg875tazjjg6MB&X-Amz-Signature=c9fc0503cf5c021159fde0517e57684939c6c864e26fe3f8837134b94a332a3b&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QWVD3PLS%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T042807Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCICDsWknFgjQJ8EADa4ArcjId2sr3rk4upz0ub9sfZBdiAiEAw9bUGTHe6JGp%2BFzbywamnoJdYsf8hWU%2F4GkoHLZTt%2FIq%2FwMIJRAAGgw2Mzc0MjMxODM4MDUiDFfnnhTASLEb88izuircA4PyTTvP6U80LZhJsuJPjbfenPC%2BjEszT8ekCq1Rsgra9m5V3FJEC%2B3elulm1yE4%2Ba19KzQKDipx1WIBLtU6u81zcE7qDddExVTj1hJH%2FCFkdygsAkFcOS4L2w4Ef2I9xDAp7cUKNGKo8ep80X9BnH8Y5WFM3CPuctlvoEZEosn8uktqVpSabY%2FJRqCDAQDQD1YorojixEnGvXgK%2BucFqPvf%2F3McVrnH0T5i5z%2FIK1f%2FtvqCLgO7SBDhFJNYPYktMsJs9fDk6ar%2FcW3XTJaZwqZ%2FajqQkYahixBrM0Bf6QP%2BeTRFavEuYHC%2BVAYXWMUKEenCHEem8djfMgNT18VAnq9AwY7Nbgvk89GLgujqzm6wCXmZP%2Fv02Gy5K1gQF1Og2EcCV6QX6S9FeZQqTzMlPQVvUtH1GH9OUbM6rSkuIwMFJrbUgtNNqMbc5eIOOeaujDZiZyRk6%2B%2B9Tz8PvMeAJ%2Bu8nM%2FVUBgojf4YVJn3yXlSYyyRxxxU%2FE2ratKQP5ZirmfwzbFx%2FC%2FS0JgXbJICYFFo2A0VntoE26zmnw7fUhsDxH0Lil%2BB2smybJMzZ51t0k%2FtVJMIHjq28vbhoCxLmXnZ0cSDNaVIhSJ8iZ5y%2FyXZcpVBTvWs0tXp6b%2BVMMjh770GOqUBs8zHL8uDHtdX%2FfQVPzSvD65Jmay8DnPe8tBywG9pfzdZkvIEQybuWSe3tEldRZT1%2FosCs6xe%2BH2HwxZHTY9LHkXpCbfkImD1%2FVvR6zFfTfzYTXW6JEb3MwSl9T171J2Q4KZpLopExF%2F2s0GdDtLMYB4R1U6H%2FF4eE%2FN5EhtVdlcGA%2BN%2FjWhzDrRdsM38AHpDU%2Fjtht0QImom1X%2Fb0oRaQUPKknLV&X-Amz-Signature=cb4fd204236e0bfb8a5079ad26d618813a8c8ad49af54348673b02065096ac25&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TSWNHCT7%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T042808Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICafsWP70d%2BL3LG23Ndht5By4QQPrUCz9d%2BgfJi5djPkAiBx1%2F9WWRIbFZir%2BE8Xo%2BQefpy2baO%2FtCxYdWnWNWN4VCr%2FAwglEAAaDDYzNzQyMzE4MzgwNSIMTjD6P9LQoyknp%2BgAKtwDIpzTR%2B0bPltVU6HroMDddufif%2FIcERVp0eZ%2Fv3DxuFbuDibxLQabtSq4tAJfCISnZU10etwJ8wos%2F3u43NaclQfrZruC4D51Z34BW1nkkLkF1ExODmHANPO7XLW9Rui6XmYqY%2ByG90p3LuaOIVK23CbUwEBNzh9k%2FwOwNiZAy3JMI9E%2FdARIznEQTbs%2FkvTWQF9kd0uHHu2zKAgYjGgckA8AsFTVgDez6aDUhLL3grKnFDeUnU9O3Rqu5s8fwuNtDm55IqRzRO%2FhBrZ04SyBvk3x%2FO71BVW9Jr9nr9RDcdo4%2F4xv6lnRamE6D8XJA%2FC3CdwPt%2B03q5hKFw1hG3lPW%2B3%2BBfB5keQZUcKkE86jkkRaFsqHLXRhx%2FN7MP8BAzUspI7BjWZ2uPoGbR0Bud6F%2BVw7wHXrI39ZPsvpMlEl9%2F4iNV7v8SwukZr%2Becbmx7oeHMnmCe%2BkgZEzcQFunv4e3BDOsGQlw0mJnUh2pl4z133kL3kLRUpHTz1gcXT7mARn4itpl3donIttSzOXRwQE%2FRjH6suMRjgI35XrXKqNSnDdbvul%2F%2B2DsulIHW5Wh5NINPwXhWC%2Bk78YiD1X7%2BYC%2F%2B%2BIRXmawE9RUA9OtN%2FzfmkmXZn0RsoslF%2Fb9vMw1eHvvQY6pgEk%2FPTTD4b5dcCbkaMsZ74rxqR22wUfA0tdm9WRBhxBjF5azyYGqRSlv4%2FqxYg8RfLDDbH6iFNFgLsVTFnk2E9wIS1rrNv6lIQPxZ%2FQeLHqdxS7r3P0lc78SAsRRI%2F2YrjalVfXx2KVEknjoZiVFFlNZla5osR0vvUALHPteeWvmZfyG3QkE3EbeES7lhuf1nI%2BpBvh2CrsUbogkFSH2jR%2BOu4YLBWj&X-Amz-Signature=124b7d3d4e5cfe9c356b64b3e2ec2026175c8254dc7bd46a4ca10a532d3e7a28&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UFSQC3DB%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T042806Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCpMsWnpEw0iAeqRS60OebxGzegDykVN4RBQfzHsKDF1wIhALK9FekNzuQS47rhHA3jTZd2OR%2Bl0kHysC9glMtu7NXhKv8DCCUQABoMNjM3NDIzMTgzODA1IgyIDomfzIn5JST5bgMq3AM2wfImc7DFHTb668aKbmnGnsBw%2FmAz9TXL8bZ7jrdr%2FzC5RagGQHyLncmCrR%2FEVYC%2FWdMEV3ALt5kWk4%2BsY1x8KeULUGLiCDm5xIVP8U3La%2Fsjn4NcjEgedbeL2lA16%2FdS%2B6qV85YNAgHkWWvgHcU7wN3jr9UrgUSKf5Jmxo0n8aw44A3Bi96OJOMu%2BVGPuEnquR5O0ckn1YMqdb%2FavakbMHqKDKa5nG3nN7d8FF6W%2FO4Swb5qa0Hbr%2B7APp1majbkUZeFFVQpgvKIllBWSkWo2x4KAgBzX169OXql%2FNHEIOIH9a08VgOYhZYQjBfJOqxJ%2BHD1l%2By24rn93MjHLRiKjTkKl9o4cdjoZs01gJdTUI0xJBeo%2BooiX1ugo3PNdNx%2BzxvC%2FGJHDbzosLS%2BptZfpX4Nck02TkF0ZGjg2dtUbvWXbWyWDGDhlTcuk8171ZUStnzgVcpAkxwAXYFsjXDWgxehu3FSGvety1tGtoc71xhsJ%2FeZ5W2nsKuRI5pDlI3vmm34EOKd2S2f9i0YX0TlGhtwfsg9cMf7VGWhXkL0prg%2B7pv2LLWrd%2Bg1kkf%2FYEuCkhxtiU%2B04i9WJBoAfCaJBIgWdIHnJPguNqN6s1%2BcEp52Na2E%2BT2D1K4lmjCa4u%2B9BjqkAdTphe5xdJIbaPHwh9626E%2B0EgpK59zocbMcIRjoFI7pVZyGAGC4EmWzxpUGkNOfu34S1sTqok8fOm5QNvKGAeB48I6vLsrwutvnIkamOLW10L3S63USwJqbcvDzYkVOtBVABSF3%2Fqb6PuXSPzBFFldegk%2FuiCIvY8uVRV9pAD7Vz6OQ920kv9Ob2dOWw2pnJnqg8pDH0%2BG%2BdEcg875tazjjg6MB&X-Amz-Signature=8279b7b49c2460eb84d9a039c8cd0564e53ef5f11919844045e3f8856a663eff&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UFSQC3DB%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T042806Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCpMsWnpEw0iAeqRS60OebxGzegDykVN4RBQfzHsKDF1wIhALK9FekNzuQS47rhHA3jTZd2OR%2Bl0kHysC9glMtu7NXhKv8DCCUQABoMNjM3NDIzMTgzODA1IgyIDomfzIn5JST5bgMq3AM2wfImc7DFHTb668aKbmnGnsBw%2FmAz9TXL8bZ7jrdr%2FzC5RagGQHyLncmCrR%2FEVYC%2FWdMEV3ALt5kWk4%2BsY1x8KeULUGLiCDm5xIVP8U3La%2Fsjn4NcjEgedbeL2lA16%2FdS%2B6qV85YNAgHkWWvgHcU7wN3jr9UrgUSKf5Jmxo0n8aw44A3Bi96OJOMu%2BVGPuEnquR5O0ckn1YMqdb%2FavakbMHqKDKa5nG3nN7d8FF6W%2FO4Swb5qa0Hbr%2B7APp1majbkUZeFFVQpgvKIllBWSkWo2x4KAgBzX169OXql%2FNHEIOIH9a08VgOYhZYQjBfJOqxJ%2BHD1l%2By24rn93MjHLRiKjTkKl9o4cdjoZs01gJdTUI0xJBeo%2BooiX1ugo3PNdNx%2BzxvC%2FGJHDbzosLS%2BptZfpX4Nck02TkF0ZGjg2dtUbvWXbWyWDGDhlTcuk8171ZUStnzgVcpAkxwAXYFsjXDWgxehu3FSGvety1tGtoc71xhsJ%2FeZ5W2nsKuRI5pDlI3vmm34EOKd2S2f9i0YX0TlGhtwfsg9cMf7VGWhXkL0prg%2B7pv2LLWrd%2Bg1kkf%2FYEuCkhxtiU%2B04i9WJBoAfCaJBIgWdIHnJPguNqN6s1%2BcEp52Na2E%2BT2D1K4lmjCa4u%2B9BjqkAdTphe5xdJIbaPHwh9626E%2B0EgpK59zocbMcIRjoFI7pVZyGAGC4EmWzxpUGkNOfu34S1sTqok8fOm5QNvKGAeB48I6vLsrwutvnIkamOLW10L3S63USwJqbcvDzYkVOtBVABSF3%2Fqb6PuXSPzBFFldegk%2FuiCIvY8uVRV9pAD7Vz6OQ920kv9Ob2dOWw2pnJnqg8pDH0%2BG%2BdEcg875tazjjg6MB&X-Amz-Signature=82ea2a42de2e2875aa0774e455d7a6ff8f11d10a88d6ec67390c370b3afd5dfb&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UFSQC3DB%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T042806Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCpMsWnpEw0iAeqRS60OebxGzegDykVN4RBQfzHsKDF1wIhALK9FekNzuQS47rhHA3jTZd2OR%2Bl0kHysC9glMtu7NXhKv8DCCUQABoMNjM3NDIzMTgzODA1IgyIDomfzIn5JST5bgMq3AM2wfImc7DFHTb668aKbmnGnsBw%2FmAz9TXL8bZ7jrdr%2FzC5RagGQHyLncmCrR%2FEVYC%2FWdMEV3ALt5kWk4%2BsY1x8KeULUGLiCDm5xIVP8U3La%2Fsjn4NcjEgedbeL2lA16%2FdS%2B6qV85YNAgHkWWvgHcU7wN3jr9UrgUSKf5Jmxo0n8aw44A3Bi96OJOMu%2BVGPuEnquR5O0ckn1YMqdb%2FavakbMHqKDKa5nG3nN7d8FF6W%2FO4Swb5qa0Hbr%2B7APp1majbkUZeFFVQpgvKIllBWSkWo2x4KAgBzX169OXql%2FNHEIOIH9a08VgOYhZYQjBfJOqxJ%2BHD1l%2By24rn93MjHLRiKjTkKl9o4cdjoZs01gJdTUI0xJBeo%2BooiX1ugo3PNdNx%2BzxvC%2FGJHDbzosLS%2BptZfpX4Nck02TkF0ZGjg2dtUbvWXbWyWDGDhlTcuk8171ZUStnzgVcpAkxwAXYFsjXDWgxehu3FSGvety1tGtoc71xhsJ%2FeZ5W2nsKuRI5pDlI3vmm34EOKd2S2f9i0YX0TlGhtwfsg9cMf7VGWhXkL0prg%2B7pv2LLWrd%2Bg1kkf%2FYEuCkhxtiU%2B04i9WJBoAfCaJBIgWdIHnJPguNqN6s1%2BcEp52Na2E%2BT2D1K4lmjCa4u%2B9BjqkAdTphe5xdJIbaPHwh9626E%2B0EgpK59zocbMcIRjoFI7pVZyGAGC4EmWzxpUGkNOfu34S1sTqok8fOm5QNvKGAeB48I6vLsrwutvnIkamOLW10L3S63USwJqbcvDzYkVOtBVABSF3%2Fqb6PuXSPzBFFldegk%2FuiCIvY8uVRV9pAD7Vz6OQ920kv9Ob2dOWw2pnJnqg8pDH0%2BG%2BdEcg875tazjjg6MB&X-Amz-Signature=33844ad273f7ced441ade65a558c88060bdf3de3cec60d4371a1630489a2ca36&X-Amz-SignedHeaders=host&x-id=GetObject)


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

