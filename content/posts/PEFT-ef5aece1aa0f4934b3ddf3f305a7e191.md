---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466ZRJ77AKI%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250219T172143Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEIH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIASS%2Fv8FCZt6E5mv4\
  FY2u9aL7sI1Ajt3BLZHR%2FNUd12kAiEAmQR9lj9TTdDcWznDN%2BEnNdh%2FMwA1ZLUPsEn1RteV\
  yesqiAQIqv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHYKh2lUhxlxX\
  ve%2B8ircA%2F8OsK9lVQikpVWDUFxYD2yeT%2FYFdGmpV0RYC%2B7EZqd7u3PAqA4KhifSa0Lx4z\
  mx1F1I861igxTHjZsmjW4%2BkkZX%2BjK%2BE4vW%2FtKb4Wew%2Bz%2BYg0cUH%2BXfUFrVGP%2F\
  8FqkkdwkeyBvueWV1zcdyk3sxiGUyymgeHevEVe7PlXKbbxf5m69cqFAT2Qmmh6tfMJZ1d9qejmsZ\
  8MEAIJIyWvxxzm9N4ai1rG8vturjpArVOGMpeg%2FxPQNSfqEC%2BCUjkgv%2BV%2B1hs0kEx1Uem\
  AYr%2FMJAiHqvZ7%2BjPTrGYPDPZMcHgvvTTbmaUyCkWW5NB0A9RtO3MNEkBchsV7OOJBtZY9m0QM\
  DPLk%2FckCTk9dsrhqyVZkUP5G%2BwUf6M5%2BVNc84QPClhz0DCYiW%2FlmDV3hNe5P8qyz9NT8n\
  NG8mN9GRmgOSnhma5npqXZ1W6kdSd5T1OUYm0kopU6TdgXf5BLRrLl%2FnBzynMltqrWQBOAF2cly\
  0WQKuHbdTLSRsR%2BWalToSUhxHUyXc2RqC1c27MGF6TmvNSc8A%2F5woTuTfwBuZcsDg%2BxvgvN\
  p1bgTg9FAPid%2F6LA0fEHfIk65OgQyWBPElyQH%2FEuZS65Flm1jLDfA7OGy4C1pKoXm5JQwn3Yk\
  8NaSJjMI%2Ba2L0GOqUB3BptPLPIkDv%2FEkWJYuVejXYFEd02w4TzObpBbMJuH9r%2BSOaKPWW%2\
  F%2FchEjMzaEAlp7oAzTA2wf5OUGlHNylCq6BYHmtfDmEyddrI%2F%2FAl%2BObjeiTpANX8BdAxW\
  aJ6w0oWz5W4wojNbfijNpiDNEmbKew1kW7fCVllqbGMmCCjJqtXa9auOdhpKbn%2FnpeMtHnTkRU3\
  A1Ua1VarTalrFArVeaxjfZCgW&X-Amz-Signature=f5e4279249f25657370fb552e75b64edd1f\
  85e872a295561fa9fe1f65511de02&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4666EUBMBJM%2F20250219%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250219T172018Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEIH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIQCMvG8CpQtEiY46eWOzK5E1PclAnrkDuxqVd2NL1uGgrQIgB8NGTNnETVPKuKG8c0Hubu\
        zsCMENInpFKJZ5bwIg7eUqiAQIqv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0M\
        jMxODM4MDUiDGUUnQORbbSxghYH7SrcAw94OqMSbLbhzAO7E1xP9NpmBegRf%2F1QazQKaa\
        cRV%2FfNWafu7QswWuvPzthCjGKB8El0UrXhxnmXU9GtnS5kXOu3eIu6VYpvDE5vXO86hbE\
        ArTgwx0a7N1NWYU%2Bdr%2FMkIRao%2B%2FI0pCMD9vdPsy5xzyke6%2FEirJcpjvZSFtcp\
        CZz7mhGMcmUlSqd2sRBZTzD1CrXlgQRyoYy7xkwepNv8LiOyZXWV6W6fRzRGhU7U4iRqedp\
        %2F4StXlTqtZD1KcuSCajVuJHELVAfV8c%2B0JNlaB30V%2Be8I0KkBvBRSp2M6fVNHe9M9\
        tjgGUjkYWPy3QS%2BPHmjsDBgqhHnwdLA7ASeoEtAvFU3Snd5sWMmGn6SwCZNuNt8NxihhJ\
        oRPrC1EPD5iqCFfx2NQh21MFqdy7BnfgET9U%2BN3hz4Q5u3kEOb9OXp8gIB3PlGACmRsjh\
        b%2BDvARbdzU0r8gOhVWIL9zHGy3OI%2FJKjvky1Fdq0nLcho2V%2B9TCROq0pv50Q%2BNu\
        %2FvJwj2C%2Be%2BL06Z8kuGxRDKuOD%2FCiP5jEYaLN1rjKI37of8e7RA0cqwd6TALmGK5\
        IE7ezYsDC5s9dBXyOuY3BoTDHBitq5nzcUGRTxzZu672NdP%2BTG060Wr4EjkUiHy3xuBJM\
        PuZ2L0GOqUBDSmU6MPSCPN%2FgXGDbyeTYA8foiaOo7LbX58z7LnT1NcXHbXNVNqAiEgZRW\
        JTNh0yQvQSklt0TmagHIoG%2FdH2ZL%2FCuCpsoAoMJFLNCBNkrELkyNdU1IKgGACxILyFc\
        G83nDkGZR9f7fLLvWhSH7tB9iyajZWje8VvMyTDDVS%2BK92oyhRbaqL3e%2BfP32iXxSlR\
        V%2B3Wz3sf7dGwB%2Fi0k0MXzsO8EIxU&X-Amz-Signature=ab864f1123f9527d608f8c\
        c982e064079e5f3a142638411f21467bc70adfbfe4&X-Amz-SignedHeaders=host&x-i\
        d=GetObject"
      expiry_time: "2025-02-19T18:20:18.765Z"
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
UPDATE_TIME: "2025-02-19T17:21:47.938Z"
EXPIRY_TIME: "2025-02-19T18:21:40.498Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466R37PNTMJ%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T172141Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICLmhzI08Vr7vIK20ZW1ovmxoPa53nxgSgaamoL5%2BGGXAiBujwO5Unf3o8TQSKj0ior2XG%2FgwJNOFlm%2Bshqcaak1OiqIBAiq%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMBp%2FkI66ilPKS7UcTKtwD31yqhN9zBfozZRHokWLIfSckoUzBGAsEyik8Y2AWRVsaR9nf9K7R5%2FT5k1I2dwB%2BQz8wtv4HUXzZySxOvvW1%2B%2F3KP0ehRFV%2BnT2HIm3XPXOZIDNKvqARXt0DvUPxU8iT8RlQAdnitaL1S4Gm405ypRj9UJtB4PYVkPc0db7%2FAItPy3%2F0KtvdV5IrIu7PZGldgUpzO51nQfI0Uh8YpRBzkt2x3mFBwt55yoHjMpCEPvVKsQ08rWTkloZUUIhAB4XcJ%2FfTh5TZKBgUVIHFimfh4qh6UQXOOLV7ZpCkL3aUZytxNJi5Eadw4JAsFACVUhEfUq40yriMjEr1oFHaBuz2pseIkhSoG3qzfdruPPa%2FV3yUfiLub8kkz1vt6DM7%2FdZHA3ulTZhh035gvlhGxBY9uO6SkhRzLDz34vVScu2k8U8vyLdhJhFy3YfTqlsFfPwfYOXSYAuMvYA3gvlAcUyb0ppCrNDXlMC6wUppC0xAiVzAVbjFhGR7qgledOnAO7G4cuaemUMw13bGewWlUnquIX705JAnoxSCju7BNzZ30yyPBTdeX2tTxTa5Wui7q4k6F2Dar0u9A0JdFIFfeZ5kWFqjW9IHM%2FbAN3EGjaty6sXI8fkrngSXEWSQ%2FWgwlZ7YvQY6pgGgnooLvDd5UcoB0Dwl8XcjQSFkepyF1ws8TwSPQF69TQ1C7pA6F8swzVIGJPa8ojZvj0Kzidt%2FY2SY1eiZQy7x8xbj22kIrQ0Y%2FBwlC8qzHPqZ0HTQOj%2BRj%2FtJA1VAJkKb74ke%2F1T1c1k7B0GLipcNsfpr%2FcarOGWgx5DHQYqRbdx%2BIcw7%2F3J7YFNjFrMVWyibu%2BAP%2F%2BFsalw2Otc%2BAd%2FyIgSXW%2Fsa&X-Amz-Signature=4f33ffc7767e043172a60b23e5532de8f056ca01c35211cd5603d2e7296f3ccd&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466R37PNTMJ%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T172141Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICLmhzI08Vr7vIK20ZW1ovmxoPa53nxgSgaamoL5%2BGGXAiBujwO5Unf3o8TQSKj0ior2XG%2FgwJNOFlm%2Bshqcaak1OiqIBAiq%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMBp%2FkI66ilPKS7UcTKtwD31yqhN9zBfozZRHokWLIfSckoUzBGAsEyik8Y2AWRVsaR9nf9K7R5%2FT5k1I2dwB%2BQz8wtv4HUXzZySxOvvW1%2B%2F3KP0ehRFV%2BnT2HIm3XPXOZIDNKvqARXt0DvUPxU8iT8RlQAdnitaL1S4Gm405ypRj9UJtB4PYVkPc0db7%2FAItPy3%2F0KtvdV5IrIu7PZGldgUpzO51nQfI0Uh8YpRBzkt2x3mFBwt55yoHjMpCEPvVKsQ08rWTkloZUUIhAB4XcJ%2FfTh5TZKBgUVIHFimfh4qh6UQXOOLV7ZpCkL3aUZytxNJi5Eadw4JAsFACVUhEfUq40yriMjEr1oFHaBuz2pseIkhSoG3qzfdruPPa%2FV3yUfiLub8kkz1vt6DM7%2FdZHA3ulTZhh035gvlhGxBY9uO6SkhRzLDz34vVScu2k8U8vyLdhJhFy3YfTqlsFfPwfYOXSYAuMvYA3gvlAcUyb0ppCrNDXlMC6wUppC0xAiVzAVbjFhGR7qgledOnAO7G4cuaemUMw13bGewWlUnquIX705JAnoxSCju7BNzZ30yyPBTdeX2tTxTa5Wui7q4k6F2Dar0u9A0JdFIFfeZ5kWFqjW9IHM%2FbAN3EGjaty6sXI8fkrngSXEWSQ%2FWgwlZ7YvQY6pgGgnooLvDd5UcoB0Dwl8XcjQSFkepyF1ws8TwSPQF69TQ1C7pA6F8swzVIGJPa8ojZvj0Kzidt%2FY2SY1eiZQy7x8xbj22kIrQ0Y%2FBwlC8qzHPqZ0HTQOj%2BRj%2FtJA1VAJkKb74ke%2F1T1c1k7B0GLipcNsfpr%2FcarOGWgx5DHQYqRbdx%2BIcw7%2F3J7YFNjFrMVWyibu%2BAP%2F%2BFsalw2Otc%2BAd%2FyIgSXW%2Fsa&X-Amz-Signature=a5582a608894592a1d1eaa9bc6a36dfcf996e30ddafc8251eb47864ad1e224fc&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466R37PNTMJ%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T172141Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICLmhzI08Vr7vIK20ZW1ovmxoPa53nxgSgaamoL5%2BGGXAiBujwO5Unf3o8TQSKj0ior2XG%2FgwJNOFlm%2Bshqcaak1OiqIBAiq%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMBp%2FkI66ilPKS7UcTKtwD31yqhN9zBfozZRHokWLIfSckoUzBGAsEyik8Y2AWRVsaR9nf9K7R5%2FT5k1I2dwB%2BQz8wtv4HUXzZySxOvvW1%2B%2F3KP0ehRFV%2BnT2HIm3XPXOZIDNKvqARXt0DvUPxU8iT8RlQAdnitaL1S4Gm405ypRj9UJtB4PYVkPc0db7%2FAItPy3%2F0KtvdV5IrIu7PZGldgUpzO51nQfI0Uh8YpRBzkt2x3mFBwt55yoHjMpCEPvVKsQ08rWTkloZUUIhAB4XcJ%2FfTh5TZKBgUVIHFimfh4qh6UQXOOLV7ZpCkL3aUZytxNJi5Eadw4JAsFACVUhEfUq40yriMjEr1oFHaBuz2pseIkhSoG3qzfdruPPa%2FV3yUfiLub8kkz1vt6DM7%2FdZHA3ulTZhh035gvlhGxBY9uO6SkhRzLDz34vVScu2k8U8vyLdhJhFy3YfTqlsFfPwfYOXSYAuMvYA3gvlAcUyb0ppCrNDXlMC6wUppC0xAiVzAVbjFhGR7qgledOnAO7G4cuaemUMw13bGewWlUnquIX705JAnoxSCju7BNzZ30yyPBTdeX2tTxTa5Wui7q4k6F2Dar0u9A0JdFIFfeZ5kWFqjW9IHM%2FbAN3EGjaty6sXI8fkrngSXEWSQ%2FWgwlZ7YvQY6pgGgnooLvDd5UcoB0Dwl8XcjQSFkepyF1ws8TwSPQF69TQ1C7pA6F8swzVIGJPa8ojZvj0Kzidt%2FY2SY1eiZQy7x8xbj22kIrQ0Y%2FBwlC8qzHPqZ0HTQOj%2BRj%2FtJA1VAJkKb74ke%2F1T1c1k7B0GLipcNsfpr%2FcarOGWgx5DHQYqRbdx%2BIcw7%2F3J7YFNjFrMVWyibu%2BAP%2F%2BFsalw2Otc%2BAd%2FyIgSXW%2Fsa&X-Amz-Signature=6096b5de1359b6febbf400930f19899154a93f0c85e7a1f90141637dcbf8a019&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466R37PNTMJ%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T172141Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICLmhzI08Vr7vIK20ZW1ovmxoPa53nxgSgaamoL5%2BGGXAiBujwO5Unf3o8TQSKj0ior2XG%2FgwJNOFlm%2Bshqcaak1OiqIBAiq%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMBp%2FkI66ilPKS7UcTKtwD31yqhN9zBfozZRHokWLIfSckoUzBGAsEyik8Y2AWRVsaR9nf9K7R5%2FT5k1I2dwB%2BQz8wtv4HUXzZySxOvvW1%2B%2F3KP0ehRFV%2BnT2HIm3XPXOZIDNKvqARXt0DvUPxU8iT8RlQAdnitaL1S4Gm405ypRj9UJtB4PYVkPc0db7%2FAItPy3%2F0KtvdV5IrIu7PZGldgUpzO51nQfI0Uh8YpRBzkt2x3mFBwt55yoHjMpCEPvVKsQ08rWTkloZUUIhAB4XcJ%2FfTh5TZKBgUVIHFimfh4qh6UQXOOLV7ZpCkL3aUZytxNJi5Eadw4JAsFACVUhEfUq40yriMjEr1oFHaBuz2pseIkhSoG3qzfdruPPa%2FV3yUfiLub8kkz1vt6DM7%2FdZHA3ulTZhh035gvlhGxBY9uO6SkhRzLDz34vVScu2k8U8vyLdhJhFy3YfTqlsFfPwfYOXSYAuMvYA3gvlAcUyb0ppCrNDXlMC6wUppC0xAiVzAVbjFhGR7qgledOnAO7G4cuaemUMw13bGewWlUnquIX705JAnoxSCju7BNzZ30yyPBTdeX2tTxTa5Wui7q4k6F2Dar0u9A0JdFIFfeZ5kWFqjW9IHM%2FbAN3EGjaty6sXI8fkrngSXEWSQ%2FWgwlZ7YvQY6pgGgnooLvDd5UcoB0Dwl8XcjQSFkepyF1ws8TwSPQF69TQ1C7pA6F8swzVIGJPa8ojZvj0Kzidt%2FY2SY1eiZQy7x8xbj22kIrQ0Y%2FBwlC8qzHPqZ0HTQOj%2BRj%2FtJA1VAJkKb74ke%2F1T1c1k7B0GLipcNsfpr%2FcarOGWgx5DHQYqRbdx%2BIcw7%2F3J7YFNjFrMVWyibu%2BAP%2F%2BFsalw2Otc%2BAd%2FyIgSXW%2Fsa&X-Amz-Signature=1a9f90bce5384cb37b43ad84ea9869289a9cb16962f799be6aba79bb4c13ecc5&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466R37PNTMJ%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T172141Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICLmhzI08Vr7vIK20ZW1ovmxoPa53nxgSgaamoL5%2BGGXAiBujwO5Unf3o8TQSKj0ior2XG%2FgwJNOFlm%2Bshqcaak1OiqIBAiq%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMBp%2FkI66ilPKS7UcTKtwD31yqhN9zBfozZRHokWLIfSckoUzBGAsEyik8Y2AWRVsaR9nf9K7R5%2FT5k1I2dwB%2BQz8wtv4HUXzZySxOvvW1%2B%2F3KP0ehRFV%2BnT2HIm3XPXOZIDNKvqARXt0DvUPxU8iT8RlQAdnitaL1S4Gm405ypRj9UJtB4PYVkPc0db7%2FAItPy3%2F0KtvdV5IrIu7PZGldgUpzO51nQfI0Uh8YpRBzkt2x3mFBwt55yoHjMpCEPvVKsQ08rWTkloZUUIhAB4XcJ%2FfTh5TZKBgUVIHFimfh4qh6UQXOOLV7ZpCkL3aUZytxNJi5Eadw4JAsFACVUhEfUq40yriMjEr1oFHaBuz2pseIkhSoG3qzfdruPPa%2FV3yUfiLub8kkz1vt6DM7%2FdZHA3ulTZhh035gvlhGxBY9uO6SkhRzLDz34vVScu2k8U8vyLdhJhFy3YfTqlsFfPwfYOXSYAuMvYA3gvlAcUyb0ppCrNDXlMC6wUppC0xAiVzAVbjFhGR7qgledOnAO7G4cuaemUMw13bGewWlUnquIX705JAnoxSCju7BNzZ30yyPBTdeX2tTxTa5Wui7q4k6F2Dar0u9A0JdFIFfeZ5kWFqjW9IHM%2FbAN3EGjaty6sXI8fkrngSXEWSQ%2FWgwlZ7YvQY6pgGgnooLvDd5UcoB0Dwl8XcjQSFkepyF1ws8TwSPQF69TQ1C7pA6F8swzVIGJPa8ojZvj0Kzidt%2FY2SY1eiZQy7x8xbj22kIrQ0Y%2FBwlC8qzHPqZ0HTQOj%2BRj%2FtJA1VAJkKb74ke%2F1T1c1k7B0GLipcNsfpr%2FcarOGWgx5DHQYqRbdx%2BIcw7%2F3J7YFNjFrMVWyibu%2BAP%2F%2BFsalw2Otc%2BAd%2FyIgSXW%2Fsa&X-Amz-Signature=fb13fe88e9030e6f008b68c9f6a410516c0f5ea48c4d424a7b7bd2fb6d4d176d&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UCMY42VC%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T172141Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIDrgvrKOz83axfSiMuLig5Fpyv5vBiX8TN4WonSqphUSAiEAnAWxo5FVlHlkrsHhbe8NSJRmhaFiE0OocPB5kqMKfnYqiAQIqv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNdEWKqRM%2F5psDso9yrcA5rdyWIeaxSgLJZWTRTlpnLayVizpkqLRqVLMJ0ev4sNE3nvcvOMkVBI21Y8ZVCwIclM4%2B%2BsZ9LsnE8vynCmfn4juNWGdENmunecOT%2BjawhUNHf3KPET5QTao3qm%2FNWf%2B6BQb%2Bp05HVlt3zOkYz%2BpGs1C2TAuQt4mppOivPRyt2eXKNARil0xm8IX%2FCsSR4KYzFU%2Bx670if28CPtrELOcQiwzRykb9it4yPjwcL3LujSSHSVWvMtmXDJCwiYHZTwg%2FcxeQ5Xed4pxyARih1nhj8f3tTlxwMufjID1Tkd1fqF%2FIAoDSDrPim2hjdWO7pV1smG5BBP%2FL6PzfSzxhoIaDkJ7RH4gY6O4llhySmmX1EPgKSMJxnpfWTQ8SWXel4MSB81aZq7sHSIwVCdrYT8eMfhmRR8%2BYtYJIEiXoFOh6EE6OmsXJTck83IiGk2qxcM9mmX87xGpP9npOB6I885w2w4G%2B70nckAVJ9mCGUAyB3M8FVQ%2FrIv92boRt%2BGdALAgZXfo4LmnT4qH%2BmtwCBQi0nd%2FX0JaoaCFRB3ImlwF4G5QxWAbdZEJQSPcVXoXv23LKLclKpKcCh4UKhgvmBS2zWSDzQj%2F4bH0ankgez8Ylho%2B2vMFiQsExyn4fkCMPad2L0GOqUB7lmj34%2FZES62e%2FHwsOKZURW5XDpZPmaJMlVC78clb0nBn56HJmE8rfw3jz3AsMKrITS7sl%2FCODyQZ5qUWqrkpi68YXwo%2FI2onKtZqL2PHEYrhereS9MdZcZZ%2BQXAZjXAgLW74jnIrbIMq4LZXis0h0znYY5ax9Ov5rF6oSiKjpVjxhCo0fHLmOiCLeqygeDmICDUSPTSsNpjZdQC5ewoZ4rrGPyU&X-Amz-Signature=31d7977f6c9f681803ebe5e2834df09c82b63e7444583ea0e7464f1305afd5fb&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UEEME75A%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T172142Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCxDWnlH2U5eMlLGlCY4TeOenZ%2FIZDX9dozppYhympIFAIgOauZiJ%2BdktSNhVgsvOcIcUAl9kjZVJHRzOtzITMjcYIqiAQIqv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDK75d1Ge8o6%2B8diqyrcA01m58X2b50C2vRmf1GWdqaDE72Y8LK%2Bw0FsbYJnGj8lNGuqXLOgE4dLsKu2MZFrINamC0skIKnc0026acEkCLOTSAPHlTujwHpGdLpg4%2BzYevLo1B8OjPw%2BpYQZBM3GE%2BsRB6P5hXtTsrTtOcEUoh3sqcIvDpj2tQ16Rj17U%2FvuCn5pqK1a%2Bj31YSQY0vdA4MGdqY52L28cTOI6r00snf7Nru2MHbCi%2BoXMsIfcBhuCQDpkG3a6cN8xOy4Wc99JRPkQC4LxwvSV8isfTQs5fFshufN8t3Xm5LCkRyl8w6rUkSnK1Mrh%2FAQaX%2B4%2BtV3M9DAn3OashUXCRjdHWLsKSkdMqzlWu1ZEvFV%2FCKnuIENyFbr5UijJIg66gpvx7U7yqN4cc0gbUQsv23RTpJh5%2FgUxl3ir98Aj3aZWAk4bUKy0k00TOb74V98MN8GJxLvReLeRfs48HikmuGr8XEqVzmNu2PxfGPd9Jgnx9fHjeEH3eocrNCaIbG9T5Fp9yg121Puv%2Bmm%2F6xMjqDdZwZjZZ8J3sqZ39V2cGM%2FBiu1vD%2FBEMJtB9DtLWx%2FZv0wMC41lmZw34oN59YIeUNfuTqEdSCzvLwMJtfUYpLPpsJKuR%2Ff6fQaKVk%2FDYs2%2F%2FDBgMPWe2L0GOqUBKfxSSobHPLsZ%2BpsAWqXswOT1E5hSMXXpfKq2uK9G1Hr4OeWLaIaY13hzHGqCvP7TWFMivNH5RGMII4spb6gQSReqrkwvh2qon2z8ZqKFOUnroqAesiGn5WsaZcquoObVkE8BVBc6cOaSXEe98Pq9eCwBEj3y22i8va1sCU5FGXFcgYWT2dq3PDlB3UPKhJtK4h3bJndUErPgq%2Fx54KzpH9qAJfrJ&X-Amz-Signature=5b7e9546994be7fdaaf88919e45e05ec41eae01be612edbe0f403676ccae65c2&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466R37PNTMJ%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T172141Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICLmhzI08Vr7vIK20ZW1ovmxoPa53nxgSgaamoL5%2BGGXAiBujwO5Unf3o8TQSKj0ior2XG%2FgwJNOFlm%2Bshqcaak1OiqIBAiq%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMBp%2FkI66ilPKS7UcTKtwD31yqhN9zBfozZRHokWLIfSckoUzBGAsEyik8Y2AWRVsaR9nf9K7R5%2FT5k1I2dwB%2BQz8wtv4HUXzZySxOvvW1%2B%2F3KP0ehRFV%2BnT2HIm3XPXOZIDNKvqARXt0DvUPxU8iT8RlQAdnitaL1S4Gm405ypRj9UJtB4PYVkPc0db7%2FAItPy3%2F0KtvdV5IrIu7PZGldgUpzO51nQfI0Uh8YpRBzkt2x3mFBwt55yoHjMpCEPvVKsQ08rWTkloZUUIhAB4XcJ%2FfTh5TZKBgUVIHFimfh4qh6UQXOOLV7ZpCkL3aUZytxNJi5Eadw4JAsFACVUhEfUq40yriMjEr1oFHaBuz2pseIkhSoG3qzfdruPPa%2FV3yUfiLub8kkz1vt6DM7%2FdZHA3ulTZhh035gvlhGxBY9uO6SkhRzLDz34vVScu2k8U8vyLdhJhFy3YfTqlsFfPwfYOXSYAuMvYA3gvlAcUyb0ppCrNDXlMC6wUppC0xAiVzAVbjFhGR7qgledOnAO7G4cuaemUMw13bGewWlUnquIX705JAnoxSCju7BNzZ30yyPBTdeX2tTxTa5Wui7q4k6F2Dar0u9A0JdFIFfeZ5kWFqjW9IHM%2FbAN3EGjaty6sXI8fkrngSXEWSQ%2FWgwlZ7YvQY6pgGgnooLvDd5UcoB0Dwl8XcjQSFkepyF1ws8TwSPQF69TQ1C7pA6F8swzVIGJPa8ojZvj0Kzidt%2FY2SY1eiZQy7x8xbj22kIrQ0Y%2FBwlC8qzHPqZ0HTQOj%2BRj%2FtJA1VAJkKb74ke%2F1T1c1k7B0GLipcNsfpr%2FcarOGWgx5DHQYqRbdx%2BIcw7%2F3J7YFNjFrMVWyibu%2BAP%2F%2BFsalw2Otc%2BAd%2FyIgSXW%2Fsa&X-Amz-Signature=de57462fba0b22a88893c2a9fc25485e9942a587ab6168af597b1757c4d89361&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466R37PNTMJ%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T172141Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICLmhzI08Vr7vIK20ZW1ovmxoPa53nxgSgaamoL5%2BGGXAiBujwO5Unf3o8TQSKj0ior2XG%2FgwJNOFlm%2Bshqcaak1OiqIBAiq%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMBp%2FkI66ilPKS7UcTKtwD31yqhN9zBfozZRHokWLIfSckoUzBGAsEyik8Y2AWRVsaR9nf9K7R5%2FT5k1I2dwB%2BQz8wtv4HUXzZySxOvvW1%2B%2F3KP0ehRFV%2BnT2HIm3XPXOZIDNKvqARXt0DvUPxU8iT8RlQAdnitaL1S4Gm405ypRj9UJtB4PYVkPc0db7%2FAItPy3%2F0KtvdV5IrIu7PZGldgUpzO51nQfI0Uh8YpRBzkt2x3mFBwt55yoHjMpCEPvVKsQ08rWTkloZUUIhAB4XcJ%2FfTh5TZKBgUVIHFimfh4qh6UQXOOLV7ZpCkL3aUZytxNJi5Eadw4JAsFACVUhEfUq40yriMjEr1oFHaBuz2pseIkhSoG3qzfdruPPa%2FV3yUfiLub8kkz1vt6DM7%2FdZHA3ulTZhh035gvlhGxBY9uO6SkhRzLDz34vVScu2k8U8vyLdhJhFy3YfTqlsFfPwfYOXSYAuMvYA3gvlAcUyb0ppCrNDXlMC6wUppC0xAiVzAVbjFhGR7qgledOnAO7G4cuaemUMw13bGewWlUnquIX705JAnoxSCju7BNzZ30yyPBTdeX2tTxTa5Wui7q4k6F2Dar0u9A0JdFIFfeZ5kWFqjW9IHM%2FbAN3EGjaty6sXI8fkrngSXEWSQ%2FWgwlZ7YvQY6pgGgnooLvDd5UcoB0Dwl8XcjQSFkepyF1ws8TwSPQF69TQ1C7pA6F8swzVIGJPa8ojZvj0Kzidt%2FY2SY1eiZQy7x8xbj22kIrQ0Y%2FBwlC8qzHPqZ0HTQOj%2BRj%2FtJA1VAJkKb74ke%2F1T1c1k7B0GLipcNsfpr%2FcarOGWgx5DHQYqRbdx%2BIcw7%2F3J7YFNjFrMVWyibu%2BAP%2F%2BFsalw2Otc%2BAd%2FyIgSXW%2Fsa&X-Amz-Signature=b7bb1734f56c093e4d33a305870d4d9a637fac1a905844b499aec39b90b5717e&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466R37PNTMJ%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T172141Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICLmhzI08Vr7vIK20ZW1ovmxoPa53nxgSgaamoL5%2BGGXAiBujwO5Unf3o8TQSKj0ior2XG%2FgwJNOFlm%2Bshqcaak1OiqIBAiq%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMBp%2FkI66ilPKS7UcTKtwD31yqhN9zBfozZRHokWLIfSckoUzBGAsEyik8Y2AWRVsaR9nf9K7R5%2FT5k1I2dwB%2BQz8wtv4HUXzZySxOvvW1%2B%2F3KP0ehRFV%2BnT2HIm3XPXOZIDNKvqARXt0DvUPxU8iT8RlQAdnitaL1S4Gm405ypRj9UJtB4PYVkPc0db7%2FAItPy3%2F0KtvdV5IrIu7PZGldgUpzO51nQfI0Uh8YpRBzkt2x3mFBwt55yoHjMpCEPvVKsQ08rWTkloZUUIhAB4XcJ%2FfTh5TZKBgUVIHFimfh4qh6UQXOOLV7ZpCkL3aUZytxNJi5Eadw4JAsFACVUhEfUq40yriMjEr1oFHaBuz2pseIkhSoG3qzfdruPPa%2FV3yUfiLub8kkz1vt6DM7%2FdZHA3ulTZhh035gvlhGxBY9uO6SkhRzLDz34vVScu2k8U8vyLdhJhFy3YfTqlsFfPwfYOXSYAuMvYA3gvlAcUyb0ppCrNDXlMC6wUppC0xAiVzAVbjFhGR7qgledOnAO7G4cuaemUMw13bGewWlUnquIX705JAnoxSCju7BNzZ30yyPBTdeX2tTxTa5Wui7q4k6F2Dar0u9A0JdFIFfeZ5kWFqjW9IHM%2FbAN3EGjaty6sXI8fkrngSXEWSQ%2FWgwlZ7YvQY6pgGgnooLvDd5UcoB0Dwl8XcjQSFkepyF1ws8TwSPQF69TQ1C7pA6F8swzVIGJPa8ojZvj0Kzidt%2FY2SY1eiZQy7x8xbj22kIrQ0Y%2FBwlC8qzHPqZ0HTQOj%2BRj%2FtJA1VAJkKb74ke%2F1T1c1k7B0GLipcNsfpr%2FcarOGWgx5DHQYqRbdx%2BIcw7%2F3J7YFNjFrMVWyibu%2BAP%2F%2BFsalw2Otc%2BAd%2FyIgSXW%2Fsa&X-Amz-Signature=d991a9975d1b7bdf1744212c0f6798d1add310d302da7e009f8a4db7c39f432e&X-Amz-SignedHeaders=host&x-id=GetObject)


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

