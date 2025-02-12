---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466XF33KB2L%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250212T052332Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEMr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCNc%2Fh4Aw5lFzf1P\
  7khajMD4vw3vSfvItAfOSRovGwHNQIhAP9nXk1gdaByA67%2F73cSIlVCgTc0VCQbVheymDzKebuM\
  KogECOL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyX0KVgsn8WQoZkM\
  r0q3AOZ3NSwwmWnLD6sjlg2%2BycEQLVUuJ1ZAXZCZcLEeCEvBox3c%2Bft1ogsJN7ZDczSLUQz70\
  %2FvewRR0vzZU2iZr%2FJLoiRPST6HCBvh2VzOVfHPSMb%2B0W82ZOxUMFInJ4OTihK6gcSOGFJd0\
  4UEN0YK3vkUJD9aFZnWDo2tykzZ5e1gBMOqXA%2Bwxq0FnL2J33ye8JEPfIutA0qj%2B6Mfba4hTR\
  ViftWYXhqbxscM2%2FrFBavsWUalDS5s6xCZdfzcaTKNwccTqc6lP0gi0IQNN7HIj3CAOZ4vuLeGF\
  SmOV7uG7FxLzvnkQcnsyK41jf9LbuVt2%2B8%2Bd%2Fys%2BP%2BeR4lCZJWC%2FcrN7H95BBpCT6\
  yF07gjfBT8QKFEnquBW8KZ%2FrXXStubFGHxQNgaUUQP%2FKQxJx0AjNb5E7yxvDrGt6ZTIM5NpYb\
  wZNXJqDwW9lcWsTxw9hJDtbj6tgpYDQvuhpmERCEexoLO6vN%2BFEdbSRYcqt50ZiwW2sd7pPoiEE\
  xwm2LVMegi3X2pXwBr7WeqfaO25CONDbBnqL25B%2BOlPUQSfEi4aU45VrkOd9V%2Bpw%2FZrpmKJ\
  MrQmuY%2Ffl3dqZT2FJmI0dMjyvXHubvgxI1wzSOcyTcUuTDD37J60F75TiDbzFgyzjDS7q%2B9Bj\
  qkAeW9yKD3Gb%2B1HAgxC4dCm3wntRuRRrPwsr%2FGkHD8TdQGfbjKityCdzbhda8ga9f2HrEze1Z\
  kK%2F1M7e1yGtKlgFBoMohnEJ0tlMD6TX36LO%2F5GMOwFhWRm7tZuK05z15HR1tOKqM7XnnYXpcf\
  QAaK93Ycp67ny2ib31QvI%2F4fQ8ZyYi89TNtQGZVicg%2BQOWWcVrgTB%2BHYZ%2FGSyXzILF3jk\
  0yAYtcv&X-Amz-Signature=8ea33b2a38ac67247b02dcedd480b223fcb51bfab290344587b0d\
  61fbf68a141&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4666GMM3S3R%2F20250212%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250212T052206Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEMr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CICYE05sFWdrHmFVVJly3i4oe8Koyne3azrslRnBN7cm1AiEA2rSX63BeGjrHTCuZLuZrnV\
        toesv9W4o3s6%2B5XeUeB2cqiAQI4v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc\
        0MjMxODM4MDUiDI14FOEpLZgAj2IYdSrcA6o%2FccSMVAQv%2F1mPLzfC71rYFAV%2FZv6O\
        erEcGVDPB3qlbqr6RGkJ9xEqjR0iyax5TT7r958qqaQ7LI6gb8BcSXLU1KYeqqN43HknBjy\
        8ZvlMuf8K900Sp9K2rnxaTInpUT4cLlctmkIIHe7vTpCcvH3fpBFc0jAPkEWmvDa4h2bxkT\
        qiZQ7ByxfehonM9FF3ehbKwY5R2EcUpKIQBT9vFPItj6boZ6jE89TfT9hs%2BYSZOhxFI7N\
        blc4zk%2BQ7jdDm43mFS%2B1iOro5bE5h%2Fqqywn1tzCwdSpyRPtp9fSBxO44r0seFapAe\
        9IQSz14LzgJ44sv6LT1qtuxCOjjDqZJvEWxlwYgxSlBxLEAOcF5SomjIvzdTnfOUM3u6feo\
        TDcuHt%2Ffkp1YJw3NpBi9z%2FKDEahRe1Dgi2fYYMz9XYsIRgmikopeOUpxuCtt0G6mDHD\
        mflmOX8%2F%2BTN9xyvgwshxRp6w%2B5SpuLqiJz8ZRLyi%2FR0HM%2FTnyOWfHhZO4T3k5\
        bB4V0I3zALdUoqqCYuCjzJy2VCcJQ7AEev2OSuBz1VENjTCh%2FTashyilsu1ZcXm7g4m6Q\
        o8donKatI6ZkBzmWYkV%2FABladRoYo5fn4IfC48mm4zOr4GJEw2wwX%2B5CW32UMNbur70\
        GOqUBOz4uNlu78U%2FhmVayUTw3YCCW2l2FKsOhbQAiztaLecBG4yCbQSC1TRfl3R5XfKuG\
        1D3SkTARJpSwxvX2d3H%2BJgn9QomOysAkDIIT9keLbPhrqtY7hljTpoQlX6GR3GvkqsCjb\
        lIv2T%2BjCQNerSC3ASGdUaVLv4Z3wh0osTBy0UhAJsx7SaRhumGqSgWM8q%2Bjz%2FRuqg\
        FWwJwQLw5y8cY2DyjHePGD&X-Amz-Signature=4b5bc565f9ad9b90de8c734b67345f46\
        a1551ccc95c911e042691cdc5bf9d83a&X-Amz-SignedHeaders=host&x-id=GetObjec\
        t"
      expiry_time: "2025-02-12T06:22:05.890Z"
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
UPDATE_TIME: "2025-02-12T05:23:38.879Z"
EXPIRY_TIME: "2025-02-12T06:23:30.622Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UWITHWKL%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T052330Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDHdiR2AlM4R6fncFBSxJqVJx4LmMljRP1KysM0YI5hTQIgTS4L4ODAN3hxFNvUq6YTO71s%2BQZDUNrHixQjjV6jQyEqiAQI4v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDP7xfSbnmf1hoKMMmCrcAzpAVZW2YiMFBUw25WC75wK4UXrgGgnCPNfQ3ra%2FNu07CWuGKEiUjC6evO%2FMJRGaxSB9QM3OmzKvpoCt%2F0vQz6tQKJHRlbIHDZhVAoyCYE1bvO7h3fRMozTn9Kcb47c7TOpoQ2mQNf6vT%2FmzMBufBBGKtYAhrkOsCPaLR%2FVLzFKdl9SGjMg1s13qLR9%2FbVFexC0wYqj0FE2SBnIbuQMCBZHZYPj95BZX99mQ%2BezYjSmpM7wJzUg7HzkMX4l9kUIvqUWiEUqpl7mC4nFT1maPixkiItkoiLOaBzWUwwJq0HF6ABszxuCwwcNonILZD0OmpwMIobRviMKgBD5K0iGLUdgxPEif257mJE7rnmSAvTm398SXehNjIAvRti8viYrjqHVaD3IPnaLthw8QLIG6oiXNyomQFqSSjGfMJWsVcW%2BFi51IOSaFi8%2FkyNYj%2FpB8gw69uweRpEskazy5Qu7Nx9vcvUEuD%2FE70l3reJEoIio329Q1byYuAMFTT7vLxfHiIoGBvQKs6bTp1OExNt5TChPfSvQqNwuuNgOUldwNbajl1ftgFLf9RX9Xr10VVNWPvz299c1XKPXGfuZnHuebf6IAFxviFQvBu%2FEdisDEzINLzBJVkCqKyRpn1EV4MNXnr70GOqUBtub6c4x4bfSL4X07Frd91ZsS049ldWc%2BLJs63o1u493MR7HB5o2ImVytyMuEcS5mR5BXpZxK1N%2BIv7lPUDhpqZEKhMalI3nhXbxvqQwgvQfNu2X%2Ft8qf2IKHYSJ4hfyDlMmDN3H36ifLA5rdKztkNFMGBjewi3a5j%2FbYhpBOpu2XxiSkng%2FgS7nXph56oIMDaqMExPaAgOrb9gpCRlVkL6mc7YET&X-Amz-Signature=1d683dab163ed84102ee22e671ece29e8d726493ba29539094ff2c548f74611b&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UWITHWKL%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T052331Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDHdiR2AlM4R6fncFBSxJqVJx4LmMljRP1KysM0YI5hTQIgTS4L4ODAN3hxFNvUq6YTO71s%2BQZDUNrHixQjjV6jQyEqiAQI4v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDP7xfSbnmf1hoKMMmCrcAzpAVZW2YiMFBUw25WC75wK4UXrgGgnCPNfQ3ra%2FNu07CWuGKEiUjC6evO%2FMJRGaxSB9QM3OmzKvpoCt%2F0vQz6tQKJHRlbIHDZhVAoyCYE1bvO7h3fRMozTn9Kcb47c7TOpoQ2mQNf6vT%2FmzMBufBBGKtYAhrkOsCPaLR%2FVLzFKdl9SGjMg1s13qLR9%2FbVFexC0wYqj0FE2SBnIbuQMCBZHZYPj95BZX99mQ%2BezYjSmpM7wJzUg7HzkMX4l9kUIvqUWiEUqpl7mC4nFT1maPixkiItkoiLOaBzWUwwJq0HF6ABszxuCwwcNonILZD0OmpwMIobRviMKgBD5K0iGLUdgxPEif257mJE7rnmSAvTm398SXehNjIAvRti8viYrjqHVaD3IPnaLthw8QLIG6oiXNyomQFqSSjGfMJWsVcW%2BFi51IOSaFi8%2FkyNYj%2FpB8gw69uweRpEskazy5Qu7Nx9vcvUEuD%2FE70l3reJEoIio329Q1byYuAMFTT7vLxfHiIoGBvQKs6bTp1OExNt5TChPfSvQqNwuuNgOUldwNbajl1ftgFLf9RX9Xr10VVNWPvz299c1XKPXGfuZnHuebf6IAFxviFQvBu%2FEdisDEzINLzBJVkCqKyRpn1EV4MNXnr70GOqUBtub6c4x4bfSL4X07Frd91ZsS049ldWc%2BLJs63o1u493MR7HB5o2ImVytyMuEcS5mR5BXpZxK1N%2BIv7lPUDhpqZEKhMalI3nhXbxvqQwgvQfNu2X%2Ft8qf2IKHYSJ4hfyDlMmDN3H36ifLA5rdKztkNFMGBjewi3a5j%2FbYhpBOpu2XxiSkng%2FgS7nXph56oIMDaqMExPaAgOrb9gpCRlVkL6mc7YET&X-Amz-Signature=e7aa85eb05ede39b5c70b0d236cee73864da2b38954819c29d64bac90fe8522f&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UWITHWKL%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T052331Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDHdiR2AlM4R6fncFBSxJqVJx4LmMljRP1KysM0YI5hTQIgTS4L4ODAN3hxFNvUq6YTO71s%2BQZDUNrHixQjjV6jQyEqiAQI4v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDP7xfSbnmf1hoKMMmCrcAzpAVZW2YiMFBUw25WC75wK4UXrgGgnCPNfQ3ra%2FNu07CWuGKEiUjC6evO%2FMJRGaxSB9QM3OmzKvpoCt%2F0vQz6tQKJHRlbIHDZhVAoyCYE1bvO7h3fRMozTn9Kcb47c7TOpoQ2mQNf6vT%2FmzMBufBBGKtYAhrkOsCPaLR%2FVLzFKdl9SGjMg1s13qLR9%2FbVFexC0wYqj0FE2SBnIbuQMCBZHZYPj95BZX99mQ%2BezYjSmpM7wJzUg7HzkMX4l9kUIvqUWiEUqpl7mC4nFT1maPixkiItkoiLOaBzWUwwJq0HF6ABszxuCwwcNonILZD0OmpwMIobRviMKgBD5K0iGLUdgxPEif257mJE7rnmSAvTm398SXehNjIAvRti8viYrjqHVaD3IPnaLthw8QLIG6oiXNyomQFqSSjGfMJWsVcW%2BFi51IOSaFi8%2FkyNYj%2FpB8gw69uweRpEskazy5Qu7Nx9vcvUEuD%2FE70l3reJEoIio329Q1byYuAMFTT7vLxfHiIoGBvQKs6bTp1OExNt5TChPfSvQqNwuuNgOUldwNbajl1ftgFLf9RX9Xr10VVNWPvz299c1XKPXGfuZnHuebf6IAFxviFQvBu%2FEdisDEzINLzBJVkCqKyRpn1EV4MNXnr70GOqUBtub6c4x4bfSL4X07Frd91ZsS049ldWc%2BLJs63o1u493MR7HB5o2ImVytyMuEcS5mR5BXpZxK1N%2BIv7lPUDhpqZEKhMalI3nhXbxvqQwgvQfNu2X%2Ft8qf2IKHYSJ4hfyDlMmDN3H36ifLA5rdKztkNFMGBjewi3a5j%2FbYhpBOpu2XxiSkng%2FgS7nXph56oIMDaqMExPaAgOrb9gpCRlVkL6mc7YET&X-Amz-Signature=7e62573295b7a5c314ec63a89861107d352e3386a47e0ce6c7f9058bce317712&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UWITHWKL%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T052331Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDHdiR2AlM4R6fncFBSxJqVJx4LmMljRP1KysM0YI5hTQIgTS4L4ODAN3hxFNvUq6YTO71s%2BQZDUNrHixQjjV6jQyEqiAQI4v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDP7xfSbnmf1hoKMMmCrcAzpAVZW2YiMFBUw25WC75wK4UXrgGgnCPNfQ3ra%2FNu07CWuGKEiUjC6evO%2FMJRGaxSB9QM3OmzKvpoCt%2F0vQz6tQKJHRlbIHDZhVAoyCYE1bvO7h3fRMozTn9Kcb47c7TOpoQ2mQNf6vT%2FmzMBufBBGKtYAhrkOsCPaLR%2FVLzFKdl9SGjMg1s13qLR9%2FbVFexC0wYqj0FE2SBnIbuQMCBZHZYPj95BZX99mQ%2BezYjSmpM7wJzUg7HzkMX4l9kUIvqUWiEUqpl7mC4nFT1maPixkiItkoiLOaBzWUwwJq0HF6ABszxuCwwcNonILZD0OmpwMIobRviMKgBD5K0iGLUdgxPEif257mJE7rnmSAvTm398SXehNjIAvRti8viYrjqHVaD3IPnaLthw8QLIG6oiXNyomQFqSSjGfMJWsVcW%2BFi51IOSaFi8%2FkyNYj%2FpB8gw69uweRpEskazy5Qu7Nx9vcvUEuD%2FE70l3reJEoIio329Q1byYuAMFTT7vLxfHiIoGBvQKs6bTp1OExNt5TChPfSvQqNwuuNgOUldwNbajl1ftgFLf9RX9Xr10VVNWPvz299c1XKPXGfuZnHuebf6IAFxviFQvBu%2FEdisDEzINLzBJVkCqKyRpn1EV4MNXnr70GOqUBtub6c4x4bfSL4X07Frd91ZsS049ldWc%2BLJs63o1u493MR7HB5o2ImVytyMuEcS5mR5BXpZxK1N%2BIv7lPUDhpqZEKhMalI3nhXbxvqQwgvQfNu2X%2Ft8qf2IKHYSJ4hfyDlMmDN3H36ifLA5rdKztkNFMGBjewi3a5j%2FbYhpBOpu2XxiSkng%2FgS7nXph56oIMDaqMExPaAgOrb9gpCRlVkL6mc7YET&X-Amz-Signature=248663d4c887766115e551347864d029cb84c6992eaa907d17134c7ec7394ce7&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UWITHWKL%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T052331Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDHdiR2AlM4R6fncFBSxJqVJx4LmMljRP1KysM0YI5hTQIgTS4L4ODAN3hxFNvUq6YTO71s%2BQZDUNrHixQjjV6jQyEqiAQI4v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDP7xfSbnmf1hoKMMmCrcAzpAVZW2YiMFBUw25WC75wK4UXrgGgnCPNfQ3ra%2FNu07CWuGKEiUjC6evO%2FMJRGaxSB9QM3OmzKvpoCt%2F0vQz6tQKJHRlbIHDZhVAoyCYE1bvO7h3fRMozTn9Kcb47c7TOpoQ2mQNf6vT%2FmzMBufBBGKtYAhrkOsCPaLR%2FVLzFKdl9SGjMg1s13qLR9%2FbVFexC0wYqj0FE2SBnIbuQMCBZHZYPj95BZX99mQ%2BezYjSmpM7wJzUg7HzkMX4l9kUIvqUWiEUqpl7mC4nFT1maPixkiItkoiLOaBzWUwwJq0HF6ABszxuCwwcNonILZD0OmpwMIobRviMKgBD5K0iGLUdgxPEif257mJE7rnmSAvTm398SXehNjIAvRti8viYrjqHVaD3IPnaLthw8QLIG6oiXNyomQFqSSjGfMJWsVcW%2BFi51IOSaFi8%2FkyNYj%2FpB8gw69uweRpEskazy5Qu7Nx9vcvUEuD%2FE70l3reJEoIio329Q1byYuAMFTT7vLxfHiIoGBvQKs6bTp1OExNt5TChPfSvQqNwuuNgOUldwNbajl1ftgFLf9RX9Xr10VVNWPvz299c1XKPXGfuZnHuebf6IAFxviFQvBu%2FEdisDEzINLzBJVkCqKyRpn1EV4MNXnr70GOqUBtub6c4x4bfSL4X07Frd91ZsS049ldWc%2BLJs63o1u493MR7HB5o2ImVytyMuEcS5mR5BXpZxK1N%2BIv7lPUDhpqZEKhMalI3nhXbxvqQwgvQfNu2X%2Ft8qf2IKHYSJ4hfyDlMmDN3H36ifLA5rdKztkNFMGBjewi3a5j%2FbYhpBOpu2XxiSkng%2FgS7nXph56oIMDaqMExPaAgOrb9gpCRlVkL6mc7YET&X-Amz-Signature=d55f539d53a9a9d873d21c1da53f523674bc7e712a324fd09b1d717d1a9bcb0b&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RQBFYFT4%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T052332Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCWf4dGl5cM7IPlYo%2FY1KwniQ8OcXhBXHiq0i4qekPrmwIgWJTePvfgCtdoN9R4LsJYMVnwviWWYyCLe%2FVOjgOtDI4qiAQI4f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGf%2FyCPJ0yL2gNzdRyrcA4CZGw%2BtSlkNSUyTelj2gOXgJPU5tZxOiv2xu6fVYHOhx2pjYHEJDUvZZ4eqUwqS5L1FYql2q9zXoDWTcKLpM11KH%2Fq6zUy0JA7dVstZGTPZ5esKi2gFG2z%2F9XyuDfs4HCfz%2FuKE7LVg%2BKI70mXdd5xVqeKoaskLiaN8LYxgj7DtrpQ2NqLIDc%2FwIx9J6LxqGxKd8O16ruwRnNtcQbampBoMAtQlrFkcJE9NsyJG4xtknrDTXlVco%2F5w30kpPE9MZVk8vOHBTZVkuodfvsonTUADf%2FiEmUZbxrCjU8sUqKeyMN%2BGG2c9G2%2Fw8tPexEMAaiXQS%2FyY7ghUI1D1U634N8RmNL9%2BIn4ZSJNnk2mNk7O4JEt%2BkWDlNmQ3mhlfrURIhcsUfQ8TlVMG82LlF0%2B0dPp3sIhagAoqiERFsPThd6KIUe5018W9HoUxkDcvj9mJ2iEO6pmcrykQqpSE5R7tmUxsg5VDwHG3ay5sbwMdxoDflopQj58R139s1EpUpn%2BSVG9Z838Ui7l3nugbAzfgG%2BxwriQ5z7NnZGqg4SJMPMTpwZI2zLdhIwXGVJvqiINLe68wQZCJ6SdZ4BfXrrhZrrbrqkeSfA9QwUv%2B%2FMb4l6T8x%2BjIGmugq8QkLysAMK%2FOr70GOqUBeE8XUKLgy22BPQI07GozFciaB4jS91OSPosz0SEvt7lNI1xw0E4GRF1sE5jx8ZBnHinRsh34p42I2L2AkIr2lRQCmmnS86u1ZjFr%2FpnzmGl1SKhlDnG1CjUU10b%2Fjdb%2BmombhMHVrDbAhgNr01Jv%2BiAheUhLkIPSnQjJbDPgVnPEwFkXwgMZFie0d%2Bzr%2Fymvg0kZ4dCTJQBHcpTA0Wbg2vn1za5q&X-Amz-Signature=603abd3b3ee748c5061f44be027fc847e9dbd9a0b5b334aefee9ceabbdf7b55d&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666KNH4QW2%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T052332Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDn1zdUHbn07s8lhii2B9Du%2B%2FnlZ3G7JjPQhruc%2F3Gx%2FQIgV%2BMtXkQ4VbWZoU3KqLBP3l4FLuLDCiWrNGq%2BjM%2Bvm8AqiAQI4v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPXJfKj6%2B%2BkKc2i10yrcA6TXtkzgTSY5YHvn%2B1Ox%2BpQqnRG7EEjVyR%2BXC7z6%2FTUbvI4TbYfMQL4HZbwIeTlnTSrq5kmLC9FPMOCbYHPb5faQ1yGRGrlYA7EsfMmibEeF3M4RiiH0CWnOADyqokoySkQAAio83rqbyJjwXc%2FEVT6es4ysB67hg%2FwZnd8byMwfMfCZiJdN6xSg9GFbjxaoe0ds%2BRSH2KHBPUrZ2jJ%2BFBMsUprobd%2F6QQ0%2BaNgQUE2w9sh219yO60V9Gl7EyTmiKqx8%2Fwf58fhnFb5Z2aRBXx5JGL2IvHXQhf4aX4x6DiL6ThLmkuqiyvS1iQhlXCEjHNs%2B5Zrlarq9UzwXwGShtuJOK3h013G7pUvEC6h6P1l5azHB4GM7%2FfS7JTQ%2BJwxR%2FI1C4jHbqg2cuan31go0%2Boa1tMIU7VpcQlmV1ZiaZhGxD%2BDE1VcpTPYVt3Vjyw%2BZWvbdzR3yzgvo8lvUJ94tiHZagl2vKQ1rKUKGXXfX8ITacD4uZt4Qr3b6fqrJbVtjw9YWxZN3BityLM50Ggtl4nvxSSULKuCUNA6BfCqJye%2FiMyjUGs0OoHS96yXvBnH31cdsUnHfrmPzWSctr3xwFet6ey19JEh7HfockuEgYa7d%2BtCfnB2kotvibihcMIDvr70GOqUBnGM5bWXa5QTZL%2FVosauxhFliHzCKiv%2FUkzeS6L66GZM0xPsiUkgbUYOHI%2Fp7vzElXhg9zR1h1gIU3zwqmgn1B2b3thE7NJ82a5ZjyvuRuOQIYawzey6x8avopMgThc3qRsMcAajlD8CMlo8BVeC7%2FUCzPiUGsnFa5wEYqxyRWmXSO%2BYOwomDdYvOhu1E6EhZnkKvw9TR5uG1CZj9VeGfnJGFFEg0&X-Amz-Signature=bf3113a577d011bb39ac77f28e32c969c5432c300f060147acb6b698a2dd9ac9&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UWITHWKL%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T052331Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDHdiR2AlM4R6fncFBSxJqVJx4LmMljRP1KysM0YI5hTQIgTS4L4ODAN3hxFNvUq6YTO71s%2BQZDUNrHixQjjV6jQyEqiAQI4v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDP7xfSbnmf1hoKMMmCrcAzpAVZW2YiMFBUw25WC75wK4UXrgGgnCPNfQ3ra%2FNu07CWuGKEiUjC6evO%2FMJRGaxSB9QM3OmzKvpoCt%2F0vQz6tQKJHRlbIHDZhVAoyCYE1bvO7h3fRMozTn9Kcb47c7TOpoQ2mQNf6vT%2FmzMBufBBGKtYAhrkOsCPaLR%2FVLzFKdl9SGjMg1s13qLR9%2FbVFexC0wYqj0FE2SBnIbuQMCBZHZYPj95BZX99mQ%2BezYjSmpM7wJzUg7HzkMX4l9kUIvqUWiEUqpl7mC4nFT1maPixkiItkoiLOaBzWUwwJq0HF6ABszxuCwwcNonILZD0OmpwMIobRviMKgBD5K0iGLUdgxPEif257mJE7rnmSAvTm398SXehNjIAvRti8viYrjqHVaD3IPnaLthw8QLIG6oiXNyomQFqSSjGfMJWsVcW%2BFi51IOSaFi8%2FkyNYj%2FpB8gw69uweRpEskazy5Qu7Nx9vcvUEuD%2FE70l3reJEoIio329Q1byYuAMFTT7vLxfHiIoGBvQKs6bTp1OExNt5TChPfSvQqNwuuNgOUldwNbajl1ftgFLf9RX9Xr10VVNWPvz299c1XKPXGfuZnHuebf6IAFxviFQvBu%2FEdisDEzINLzBJVkCqKyRpn1EV4MNXnr70GOqUBtub6c4x4bfSL4X07Frd91ZsS049ldWc%2BLJs63o1u493MR7HB5o2ImVytyMuEcS5mR5BXpZxK1N%2BIv7lPUDhpqZEKhMalI3nhXbxvqQwgvQfNu2X%2Ft8qf2IKHYSJ4hfyDlMmDN3H36ifLA5rdKztkNFMGBjewi3a5j%2FbYhpBOpu2XxiSkng%2FgS7nXph56oIMDaqMExPaAgOrb9gpCRlVkL6mc7YET&X-Amz-Signature=61a484c82ddcb200ee88ffbf03e3932c5f3945d8770abf9f57dc338c17b8f2ad&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UWITHWKL%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T052331Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDHdiR2AlM4R6fncFBSxJqVJx4LmMljRP1KysM0YI5hTQIgTS4L4ODAN3hxFNvUq6YTO71s%2BQZDUNrHixQjjV6jQyEqiAQI4v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDP7xfSbnmf1hoKMMmCrcAzpAVZW2YiMFBUw25WC75wK4UXrgGgnCPNfQ3ra%2FNu07CWuGKEiUjC6evO%2FMJRGaxSB9QM3OmzKvpoCt%2F0vQz6tQKJHRlbIHDZhVAoyCYE1bvO7h3fRMozTn9Kcb47c7TOpoQ2mQNf6vT%2FmzMBufBBGKtYAhrkOsCPaLR%2FVLzFKdl9SGjMg1s13qLR9%2FbVFexC0wYqj0FE2SBnIbuQMCBZHZYPj95BZX99mQ%2BezYjSmpM7wJzUg7HzkMX4l9kUIvqUWiEUqpl7mC4nFT1maPixkiItkoiLOaBzWUwwJq0HF6ABszxuCwwcNonILZD0OmpwMIobRviMKgBD5K0iGLUdgxPEif257mJE7rnmSAvTm398SXehNjIAvRti8viYrjqHVaD3IPnaLthw8QLIG6oiXNyomQFqSSjGfMJWsVcW%2BFi51IOSaFi8%2FkyNYj%2FpB8gw69uweRpEskazy5Qu7Nx9vcvUEuD%2FE70l3reJEoIio329Q1byYuAMFTT7vLxfHiIoGBvQKs6bTp1OExNt5TChPfSvQqNwuuNgOUldwNbajl1ftgFLf9RX9Xr10VVNWPvz299c1XKPXGfuZnHuebf6IAFxviFQvBu%2FEdisDEzINLzBJVkCqKyRpn1EV4MNXnr70GOqUBtub6c4x4bfSL4X07Frd91ZsS049ldWc%2BLJs63o1u493MR7HB5o2ImVytyMuEcS5mR5BXpZxK1N%2BIv7lPUDhpqZEKhMalI3nhXbxvqQwgvQfNu2X%2Ft8qf2IKHYSJ4hfyDlMmDN3H36ifLA5rdKztkNFMGBjewi3a5j%2FbYhpBOpu2XxiSkng%2FgS7nXph56oIMDaqMExPaAgOrb9gpCRlVkL6mc7YET&X-Amz-Signature=b0a0657bd83c212b1c05b7f935028b8666b4d2541f9787c4a9327d7d40f15a61&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UWITHWKL%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T052331Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDHdiR2AlM4R6fncFBSxJqVJx4LmMljRP1KysM0YI5hTQIgTS4L4ODAN3hxFNvUq6YTO71s%2BQZDUNrHixQjjV6jQyEqiAQI4v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDP7xfSbnmf1hoKMMmCrcAzpAVZW2YiMFBUw25WC75wK4UXrgGgnCPNfQ3ra%2FNu07CWuGKEiUjC6evO%2FMJRGaxSB9QM3OmzKvpoCt%2F0vQz6tQKJHRlbIHDZhVAoyCYE1bvO7h3fRMozTn9Kcb47c7TOpoQ2mQNf6vT%2FmzMBufBBGKtYAhrkOsCPaLR%2FVLzFKdl9SGjMg1s13qLR9%2FbVFexC0wYqj0FE2SBnIbuQMCBZHZYPj95BZX99mQ%2BezYjSmpM7wJzUg7HzkMX4l9kUIvqUWiEUqpl7mC4nFT1maPixkiItkoiLOaBzWUwwJq0HF6ABszxuCwwcNonILZD0OmpwMIobRviMKgBD5K0iGLUdgxPEif257mJE7rnmSAvTm398SXehNjIAvRti8viYrjqHVaD3IPnaLthw8QLIG6oiXNyomQFqSSjGfMJWsVcW%2BFi51IOSaFi8%2FkyNYj%2FpB8gw69uweRpEskazy5Qu7Nx9vcvUEuD%2FE70l3reJEoIio329Q1byYuAMFTT7vLxfHiIoGBvQKs6bTp1OExNt5TChPfSvQqNwuuNgOUldwNbajl1ftgFLf9RX9Xr10VVNWPvz299c1XKPXGfuZnHuebf6IAFxviFQvBu%2FEdisDEzINLzBJVkCqKyRpn1EV4MNXnr70GOqUBtub6c4x4bfSL4X07Frd91ZsS049ldWc%2BLJs63o1u493MR7HB5o2ImVytyMuEcS5mR5BXpZxK1N%2BIv7lPUDhpqZEKhMalI3nhXbxvqQwgvQfNu2X%2Ft8qf2IKHYSJ4hfyDlMmDN3H36ifLA5rdKztkNFMGBjewi3a5j%2FbYhpBOpu2XxiSkng%2FgS7nXph56oIMDaqMExPaAgOrb9gpCRlVkL6mc7YET&X-Amz-Signature=a4f257caed511587a7949a33b3de8835799637d03a0979cd946c975df38f7f1b&X-Amz-SignedHeaders=host&x-id=GetObject)


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

