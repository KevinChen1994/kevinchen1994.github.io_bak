---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB46632PZWIWY%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250220T042759Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEIz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQC77tWODrVdxE9GtDA\
  SEuOCKbBi4hUUNUHZhATsZJKwwwIgTzm8gPNnLVisNxztbqpNbAB9nNsPLN9SrmdE34%2BQQhAqiA\
  QItf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDIWeNeKtRa%2Bi3aEog\
  CrcA%2FMdKzDnd9MW%2FYcHtL82AsT80jO86e%2BLlHxdrK2UFz9A%2BQrHpwP71XJ5QHZaBeWf66\
  4DADhr3z6Frx7D5ojjzxiqY6NPCMLiW0R%2Fp2gm1HxNa%2BLpqNUjhLqf%2BEuSzT7ANmCN6qpDM\
  BCuz9EoWPGBcGhAl%2BpPeI9G06iMjhyNWH9pptrg23W2rE34gbqEuIkD4E9Nzi4IFekZylLT4M1J\
  oHpMdABohE01Z4oGLNdbBsyvNBrFq7lmfb5bnXZWu5dW2Z1kgug7WLRqqyNiN%2BEFXgRmFDnHunK\
  8ZVX17iC4q9kwc9KN2kzUS%2B4lz26AUlJC22jmHZBgO7yJE9jCXh8UiIOdcEVTf17ohTEtfuqiLX\
  DDIZjUdND9ImvBgFwY1sKKxBeEzVX8I2F%2FIi2ASpc%2FUjiIlrTrKVE9ZTh%2FOG9IRxBabkkMK\
  07RC8zSrFZTLKURGdc3NL6YecwtlHO8GJTsXQYKDS0awRUFQ8gM2ul99njGwdir3wdwMO1zYdoep8\
  Y7yX3TDDc0GSvwRupwutZstyzLqwzr5sQDogliBk2Ila8XUdT5Zvo8zRY0UQAWVu5wR0krZx0dpNN\
  IIV%2FNEhi5tl%2F383d3BLAQN7px4bSScNlnk5lm57jhrN0%2F9jDcMLnD2r0GOqUBOcTe2%2FhO\
  Wf5Wl3QLySEFOUrwOpAsfAEk8X4KPBIN%2BXWGMXW3atQXaAFrUPrjR5GKQgxp%2FCvgK0hQAdSNt\
  4LZG7VK5BD9qt7AnPQuBHKKaGPAGqbCr9US%2FNzc0Z2EbBZXsd3zC%2BbepelHrrCddsf%2FhlXC\
  EVb7oWImrI8RIg%2BfV0%2BejopEgFTiwO%2BkHs36qwtLuLhjNxRoQdgff%2BuNgvITN0hQEtzj&\
  X-Amz-Signature=7133fcce99a7e91d48862a8b0e2e34e47f9b29942c3b4995c2d4fa0a35f26\
  c6a&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466ZK76QXPQ%2F20250220%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250220T042632Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEIz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQ\
        CID2Ty7u8EOlotLEGLxclSBNGSFFAYWejHrpfFsc0RNsjAiBrQVTbmnSrsPpoGxa0OMJ75L\
        g3DK4NII1FTM5ulhUBvSqIBAi1%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyM\
        zE4MzgwNSIMSYhB3nCJ47JxrS4bKtwD3oTn6dNOl9xUUe6%2B1Z%2F61H44gq%2FuWmpUZq\
        K1jUhzGEuix00cOe7d7rAMze8ekvuzA2cudheF8YjtEdnz4LMlZMaLZ3zf0yj%2BlMWouOZ\
        rLOeO1PKQa7wrF4BZ7uo9kIvt3m3hSFU0uslIEuLwb233y1LHU%2BwMJOPD9c9CY2Jws1d1\
        cmucJUBpSeIPhUwVcQa4fxWkOiCIKzZQtF3Lau6NGOUBTUj7qE%2BE%2BDIwHyr3U9M26gD\
        NGe5YA2nEEKlNAH2h3lIQRMPjbtyx%2FH0QrHuBoWtlTAGwNs%2BvyKkTvJBzddhKJ%2Fns\
        05%2FckV6JfxIwEsv7iMGB9CFmj5k3lO47KgiKOmA6nJRgaAYDahLuXvb7FBhz337J52e9n\
        Iib1usKYjqGVPovKjEqejk38zkMkQY%2FwezPoyouw29u4%2BZi8gAkUIgl4KeRaUwoNILU\
        2Gpdak6oQtLbax%2FWx5J1Hpn4tfjhBn6SyOoML765g%2FegnPTxHUWZjrl7To7HV0%2BSc\
        OO%2B8WGpBua3ciy4V3m1uxs5sVnvsWEuft8NtvvEwtA8%2Fh5hPz264KHfdpZXtkeQulww\
        %2F3sFj5N%2BwhdVVsdbnJnedHkYSddVzyTdvgYjTDLIpUon5QmqbTgoIRBc0zWRvf8wlsT\
        avQY6pgGsVURUw4tymqxNp91LO6DqIS3O3tp2bx%2FJ5khksoM3lUbl%2FflbYCbEKQ0G2O\
        AWPyD5Mt7SlDAo%2FdXIZJeD%2FbGRnXDEXK7S3Zi%2FEAZibjOvMlGhhU%2F9Oxw4Nwdhb\
        onzSl4UUM573ETnoeVCZeMrcmtWmVH6WUwDTEdAGRA4pcrqqenmThkleB64gcEqUuluZdDB\
        2OK4f2hasBq6JZq7CZISDXqCt1Xk&X-Amz-Signature=fc5d972112b24bff64b73b3a87\
        9c16db486f8da011a59d4f738bc20abd1e48e7&X-Amz-SignedHeaders=host&x-id=Ge\
        tObject"
      expiry_time: "2025-02-20T05:26:32.297Z"
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
UPDATE_TIME: "2025-02-20T04:28:05.754Z"
EXPIRY_TIME: "2025-02-20T05:27:57.640Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46655Y4NXTX%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T042758Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDZN54VrjvZV%2BfBax3bw3d%2Fcs4A%2Ba1b8DRxAJu621IlHwIhAJnOwjRWTtR0Ytq9HyVmGH4CxjCwYc50VOS8z83IaAHXKogECLX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyJWxKQqHBh6xw%2B90Aq3AOcS8fAQAvzfb3Ea25gSL7U7ocugp52%2BimVNPjTLdMGUx5ZbgusN%2F4CTEws8hsLUv6ZpHRUQb1LwLoSNAj9eb8FssW%2BU9ymZ5cy8mbwIYK58AqywdXFpXeKPVwHOQ6ZLuk6Sc2Qx1XaOHkezEMTXnYnELWJF7zU0UdRgqNH4EM7dOZWJqCJurOkTtGUfQLnswkJJngc7bWryDabprqoK2WvQIw90XJmt8J1BI10XhzgLfs5RUsgIKLdsCvgaVSznqUZn4pdG30Rf5pZH9G4aI9sps9lUL%2FlRdDy2vhq%2Fkn9EeYKSRwBZSnbTy7lW77pOHmNjC13vwZkQ6wkrcP%2FGfN1rJAq255EX5q32Hnip6ibM0m5alTjHXmdiTnd40yKXJeR%2FnHEYzU5wNNnhDe6sNu3OivvROr40CAJksIS6WCrZMY22oQwWheBlrmKFmOczBm9gC2XCY4gl0szouKv%2FjnO5wzJyyp3nbUNe%2BKn%2F8XOKyg7yQtHV%2Bhl83b4Wy2JW65ONGEZSj1vyTBG2asTpuEcOdvKVj%2B%2BL1sFafN13zatoBvrGm5UagCqZf4jVWTqk6PCBDEG3ZOHFhTGKK1RVt4P4VWeWcjGvawpwyBJjGjmlAed99%2BlrO%2FIdW0DxTCiw9q9BjqkARWgKqHGmYMhANSPC21l8x9TZ%2B2FxTQni1EXgDpWWMTVBopNBIgIbtgn7PkmzDEs4KL2NKLtddXngDZ8atVeLmoalTipmix76BZIonldteTEMtqp8RBpVPEpjaPh9BICvart66vJAsuQyYKuFctqM2Jxvu6fZNgbtnprJn7CS7Mf6fTA911IvpXlKwd%2FVL%2BQx7AxZPINRPGgOV%2FjBrxdB4yxfFx4&X-Amz-Signature=eca8a55f44202506ebf7ef2688933cddd643a9b98c2b94174376feab182a308c&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46655Y4NXTX%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T042758Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDZN54VrjvZV%2BfBax3bw3d%2Fcs4A%2Ba1b8DRxAJu621IlHwIhAJnOwjRWTtR0Ytq9HyVmGH4CxjCwYc50VOS8z83IaAHXKogECLX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyJWxKQqHBh6xw%2B90Aq3AOcS8fAQAvzfb3Ea25gSL7U7ocugp52%2BimVNPjTLdMGUx5ZbgusN%2F4CTEws8hsLUv6ZpHRUQb1LwLoSNAj9eb8FssW%2BU9ymZ5cy8mbwIYK58AqywdXFpXeKPVwHOQ6ZLuk6Sc2Qx1XaOHkezEMTXnYnELWJF7zU0UdRgqNH4EM7dOZWJqCJurOkTtGUfQLnswkJJngc7bWryDabprqoK2WvQIw90XJmt8J1BI10XhzgLfs5RUsgIKLdsCvgaVSznqUZn4pdG30Rf5pZH9G4aI9sps9lUL%2FlRdDy2vhq%2Fkn9EeYKSRwBZSnbTy7lW77pOHmNjC13vwZkQ6wkrcP%2FGfN1rJAq255EX5q32Hnip6ibM0m5alTjHXmdiTnd40yKXJeR%2FnHEYzU5wNNnhDe6sNu3OivvROr40CAJksIS6WCrZMY22oQwWheBlrmKFmOczBm9gC2XCY4gl0szouKv%2FjnO5wzJyyp3nbUNe%2BKn%2F8XOKyg7yQtHV%2Bhl83b4Wy2JW65ONGEZSj1vyTBG2asTpuEcOdvKVj%2B%2BL1sFafN13zatoBvrGm5UagCqZf4jVWTqk6PCBDEG3ZOHFhTGKK1RVt4P4VWeWcjGvawpwyBJjGjmlAed99%2BlrO%2FIdW0DxTCiw9q9BjqkARWgKqHGmYMhANSPC21l8x9TZ%2B2FxTQni1EXgDpWWMTVBopNBIgIbtgn7PkmzDEs4KL2NKLtddXngDZ8atVeLmoalTipmix76BZIonldteTEMtqp8RBpVPEpjaPh9BICvart66vJAsuQyYKuFctqM2Jxvu6fZNgbtnprJn7CS7Mf6fTA911IvpXlKwd%2FVL%2BQx7AxZPINRPGgOV%2FjBrxdB4yxfFx4&X-Amz-Signature=7796d2fd469db1266b16117436ee19b52c0a4de47f47030d37de56153f2bdbd9&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46655Y4NXTX%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T042758Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDZN54VrjvZV%2BfBax3bw3d%2Fcs4A%2Ba1b8DRxAJu621IlHwIhAJnOwjRWTtR0Ytq9HyVmGH4CxjCwYc50VOS8z83IaAHXKogECLX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyJWxKQqHBh6xw%2B90Aq3AOcS8fAQAvzfb3Ea25gSL7U7ocugp52%2BimVNPjTLdMGUx5ZbgusN%2F4CTEws8hsLUv6ZpHRUQb1LwLoSNAj9eb8FssW%2BU9ymZ5cy8mbwIYK58AqywdXFpXeKPVwHOQ6ZLuk6Sc2Qx1XaOHkezEMTXnYnELWJF7zU0UdRgqNH4EM7dOZWJqCJurOkTtGUfQLnswkJJngc7bWryDabprqoK2WvQIw90XJmt8J1BI10XhzgLfs5RUsgIKLdsCvgaVSznqUZn4pdG30Rf5pZH9G4aI9sps9lUL%2FlRdDy2vhq%2Fkn9EeYKSRwBZSnbTy7lW77pOHmNjC13vwZkQ6wkrcP%2FGfN1rJAq255EX5q32Hnip6ibM0m5alTjHXmdiTnd40yKXJeR%2FnHEYzU5wNNnhDe6sNu3OivvROr40CAJksIS6WCrZMY22oQwWheBlrmKFmOczBm9gC2XCY4gl0szouKv%2FjnO5wzJyyp3nbUNe%2BKn%2F8XOKyg7yQtHV%2Bhl83b4Wy2JW65ONGEZSj1vyTBG2asTpuEcOdvKVj%2B%2BL1sFafN13zatoBvrGm5UagCqZf4jVWTqk6PCBDEG3ZOHFhTGKK1RVt4P4VWeWcjGvawpwyBJjGjmlAed99%2BlrO%2FIdW0DxTCiw9q9BjqkARWgKqHGmYMhANSPC21l8x9TZ%2B2FxTQni1EXgDpWWMTVBopNBIgIbtgn7PkmzDEs4KL2NKLtddXngDZ8atVeLmoalTipmix76BZIonldteTEMtqp8RBpVPEpjaPh9BICvart66vJAsuQyYKuFctqM2Jxvu6fZNgbtnprJn7CS7Mf6fTA911IvpXlKwd%2FVL%2BQx7AxZPINRPGgOV%2FjBrxdB4yxfFx4&X-Amz-Signature=dffd129675be075736c63fa70f2311a6b3a3c02e0cf2982bd98621f372242c75&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46655Y4NXTX%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T042758Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDZN54VrjvZV%2BfBax3bw3d%2Fcs4A%2Ba1b8DRxAJu621IlHwIhAJnOwjRWTtR0Ytq9HyVmGH4CxjCwYc50VOS8z83IaAHXKogECLX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyJWxKQqHBh6xw%2B90Aq3AOcS8fAQAvzfb3Ea25gSL7U7ocugp52%2BimVNPjTLdMGUx5ZbgusN%2F4CTEws8hsLUv6ZpHRUQb1LwLoSNAj9eb8FssW%2BU9ymZ5cy8mbwIYK58AqywdXFpXeKPVwHOQ6ZLuk6Sc2Qx1XaOHkezEMTXnYnELWJF7zU0UdRgqNH4EM7dOZWJqCJurOkTtGUfQLnswkJJngc7bWryDabprqoK2WvQIw90XJmt8J1BI10XhzgLfs5RUsgIKLdsCvgaVSznqUZn4pdG30Rf5pZH9G4aI9sps9lUL%2FlRdDy2vhq%2Fkn9EeYKSRwBZSnbTy7lW77pOHmNjC13vwZkQ6wkrcP%2FGfN1rJAq255EX5q32Hnip6ibM0m5alTjHXmdiTnd40yKXJeR%2FnHEYzU5wNNnhDe6sNu3OivvROr40CAJksIS6WCrZMY22oQwWheBlrmKFmOczBm9gC2XCY4gl0szouKv%2FjnO5wzJyyp3nbUNe%2BKn%2F8XOKyg7yQtHV%2Bhl83b4Wy2JW65ONGEZSj1vyTBG2asTpuEcOdvKVj%2B%2BL1sFafN13zatoBvrGm5UagCqZf4jVWTqk6PCBDEG3ZOHFhTGKK1RVt4P4VWeWcjGvawpwyBJjGjmlAed99%2BlrO%2FIdW0DxTCiw9q9BjqkARWgKqHGmYMhANSPC21l8x9TZ%2B2FxTQni1EXgDpWWMTVBopNBIgIbtgn7PkmzDEs4KL2NKLtddXngDZ8atVeLmoalTipmix76BZIonldteTEMtqp8RBpVPEpjaPh9BICvart66vJAsuQyYKuFctqM2Jxvu6fZNgbtnprJn7CS7Mf6fTA911IvpXlKwd%2FVL%2BQx7AxZPINRPGgOV%2FjBrxdB4yxfFx4&X-Amz-Signature=054659045a669ca9d5f2a510ff754a7218e1b2af13914fff8f9ec60f89a3bfd6&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46655Y4NXTX%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T042758Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDZN54VrjvZV%2BfBax3bw3d%2Fcs4A%2Ba1b8DRxAJu621IlHwIhAJnOwjRWTtR0Ytq9HyVmGH4CxjCwYc50VOS8z83IaAHXKogECLX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyJWxKQqHBh6xw%2B90Aq3AOcS8fAQAvzfb3Ea25gSL7U7ocugp52%2BimVNPjTLdMGUx5ZbgusN%2F4CTEws8hsLUv6ZpHRUQb1LwLoSNAj9eb8FssW%2BU9ymZ5cy8mbwIYK58AqywdXFpXeKPVwHOQ6ZLuk6Sc2Qx1XaOHkezEMTXnYnELWJF7zU0UdRgqNH4EM7dOZWJqCJurOkTtGUfQLnswkJJngc7bWryDabprqoK2WvQIw90XJmt8J1BI10XhzgLfs5RUsgIKLdsCvgaVSznqUZn4pdG30Rf5pZH9G4aI9sps9lUL%2FlRdDy2vhq%2Fkn9EeYKSRwBZSnbTy7lW77pOHmNjC13vwZkQ6wkrcP%2FGfN1rJAq255EX5q32Hnip6ibM0m5alTjHXmdiTnd40yKXJeR%2FnHEYzU5wNNnhDe6sNu3OivvROr40CAJksIS6WCrZMY22oQwWheBlrmKFmOczBm9gC2XCY4gl0szouKv%2FjnO5wzJyyp3nbUNe%2BKn%2F8XOKyg7yQtHV%2Bhl83b4Wy2JW65ONGEZSj1vyTBG2asTpuEcOdvKVj%2B%2BL1sFafN13zatoBvrGm5UagCqZf4jVWTqk6PCBDEG3ZOHFhTGKK1RVt4P4VWeWcjGvawpwyBJjGjmlAed99%2BlrO%2FIdW0DxTCiw9q9BjqkARWgKqHGmYMhANSPC21l8x9TZ%2B2FxTQni1EXgDpWWMTVBopNBIgIbtgn7PkmzDEs4KL2NKLtddXngDZ8atVeLmoalTipmix76BZIonldteTEMtqp8RBpVPEpjaPh9BICvart66vJAsuQyYKuFctqM2Jxvu6fZNgbtnprJn7CS7Mf6fTA911IvpXlKwd%2FVL%2BQx7AxZPINRPGgOV%2FjBrxdB4yxfFx4&X-Amz-Signature=b150b092a31b137c5389474c730d24e0fc56225cd95ba8433bea7558935734dc&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VB6AG5HO%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T042758Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCOJ2qSrqbJ2Syqt%2Fzzkl15u3kM14Ac3QutvyFrySLwzwIgaK9cGT98PUU7EbwFO%2Bw0e0UtPYiOubyJgMa1sWwv%2FFkqiAQItf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPPTXdR2d5DWZe%2FFFSrcAwpEdk3O0FvmM1m%2BPyGjMi%2FLB7RvVYXUrDvkKryfeota%2BzP07%2Fz1ep8kUljhTgCHoSRIRg74oljFa3kuo%2Bsx%2BcajwGjcc1JXZnICbK%2FiYgv1HEhVVWsxHb9HWbyckmzo%2B0Z2iFwlaI2%2BiRfSpLeymBpHA02ul99C0C1tC1jeczmWD2SXejyrFL0ROqjjrgZ3YxB29M%2FVentjbdwADAHgfXACTFg8ObFLITFv%2BsQ6LTxY9aZnKqd4s64lFJIO42ymBGtZl5xslKCN9NKnbtQFG1TsTB5gC%2BdorWhdnW9XJk8xUTGI7GTy%2F4VhCJTKgtLBdoq4iF2PpECtYwWnJYyQiGSxj4DiPILF2TZMeDZavtWdN5y5MDvP1h76ZG2dXfgkrNMAznjBlbZ9qPlsGUmloQ%2FkXLwId4fga0vrFIoqL7bY39GLwBZWyh7apLHXM3X6E0k%2Fm2vvvj9wihjf6GxIEb239RXrVdfcJo6adM%2F4ER3iLHwsiKdBEAoqBd2876dd%2F9%2FvX6i0D%2FQHS%2B5CZlgpAAF%2FPImFSaL6lwSXSFpwliASyy9rt6AZooquwCrbJ0gU30hbSZp995aphzpGS%2BRvk28CKwZZmIM50xpHrRNohWv8Pho9JLIBVLas%2Ffc%2FMKXZ2r0GOqUB2XxAx7g86CeSUvsV1T%2BSHZfwX8ueXSTYlUbu5aTozI0yjQMVEzw3kJLqILwv8BzadQ7z%2FlN7JP%2Fe3p3bCusUtL7vrpf6T8vn71FS4kY7NLOBWNK1ix0A27Pn%2FXkdJ6ioM6532AWcpK%2FofWDaNpX7m3v3ORgiJU%2BLwjf%2B8791lhHvQ%2FQrEGjTH3QdEhlIsl2%2F%2Br6llb3T5%2FWvWld5pCeonoG%2FdMt1&X-Amz-Signature=1dec9f818124e621b62d624bb07532bb8c0f18eee35374f7be679f11bff18855&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XCUH36MV%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T042759Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD7G9sTwlANUb2r71oE%2BiEn0laH9ewMK25vPHKDyZF8WgIhAISQXm5LrwTobXgAEguB0XrKr5maIRFuNjlHnmMswGYkKogECLX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzA1Rka%2Fb2UMRUYQEIq3AOHTX1jQe3L8k7tM8B29TWpFwZ1JqBVIt2pFfH8EBNxANT%2BZ5rRL2dn8CRd8p379oIbBsqeh%2FtgUc2001KuLHndwH17kCIsy4aNc4rEn%2Fluvey5qec32ulS34BnPB9qKqS2VpVpzx95No4emHYefbbYLgfhX2oehvFeBX9wA9uPJS8ZdM%2BlA79zPqgRoQ9pmn1HVtg%2BinP2ruIbEu9o1BkNxU8fgVyga9vucnhqjZGZGdiQIRIaBwY8nL9%2FSilxXeP%2BVH96JdNte2x3aJEd1Jcy6ubm1tO4O3Rvhq%2FV1sBcRV8Qrf8ZtRBoBenxaBs2og2VSEN9Yt1pUpo2GMEm1znIO16tbAHmLgGHwHtSofSVe6q7xBRAHTRIGS57iO83LrWWO%2Fu5uQbGAZZtvTclPN1JuXaeGTExvfZcITUdaviT77x5bEd7HVy%2Bi0yEZcWfKcvxrNMpTtckbI%2FHQHHbUIQQpPT6mr2EknxjPCd%2BzXbZmW9ph3C2UZIeWC2xRwxFLZbZJp8WQxH75M8VxNGWPKqYH5WFrvH1%2BiRz%2Fbtol4Exs91je0MBI%2FUR035yFkcn%2BkSoDGnAQX5J3qzCFJ6mpY5A%2FpP%2Fe9oN4Hz%2F0lPrdNw66i7%2BYPwbS97mxdXCzDDMw9q9BjqkATUuysF1q5FArGCRO2f2KRYJU93HM7G0VvxUzzZbIN4UFB6FMRe51Buk6s%2BcauIZm2Bh9n2hl5VskZwYNg9Z2alK2Z7nFRSZmFoBzhObp8d3i5bc1IluxeWSG6rtNUmE4434YjbTdClTqmxDJVuBFIAlsGytLmHj%2F7EvnXI87NLkMvz4sMvwxOCop5JmRM7mLPRaaHP77QDAc9BenUfFSFhmiDom&X-Amz-Signature=160096dc934b3aa4a3cfe1111e1c34376698e8855aeb056b3c9ab469e9efd1fb&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46655Y4NXTX%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T042758Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDZN54VrjvZV%2BfBax3bw3d%2Fcs4A%2Ba1b8DRxAJu621IlHwIhAJnOwjRWTtR0Ytq9HyVmGH4CxjCwYc50VOS8z83IaAHXKogECLX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyJWxKQqHBh6xw%2B90Aq3AOcS8fAQAvzfb3Ea25gSL7U7ocugp52%2BimVNPjTLdMGUx5ZbgusN%2F4CTEws8hsLUv6ZpHRUQb1LwLoSNAj9eb8FssW%2BU9ymZ5cy8mbwIYK58AqywdXFpXeKPVwHOQ6ZLuk6Sc2Qx1XaOHkezEMTXnYnELWJF7zU0UdRgqNH4EM7dOZWJqCJurOkTtGUfQLnswkJJngc7bWryDabprqoK2WvQIw90XJmt8J1BI10XhzgLfs5RUsgIKLdsCvgaVSznqUZn4pdG30Rf5pZH9G4aI9sps9lUL%2FlRdDy2vhq%2Fkn9EeYKSRwBZSnbTy7lW77pOHmNjC13vwZkQ6wkrcP%2FGfN1rJAq255EX5q32Hnip6ibM0m5alTjHXmdiTnd40yKXJeR%2FnHEYzU5wNNnhDe6sNu3OivvROr40CAJksIS6WCrZMY22oQwWheBlrmKFmOczBm9gC2XCY4gl0szouKv%2FjnO5wzJyyp3nbUNe%2BKn%2F8XOKyg7yQtHV%2Bhl83b4Wy2JW65ONGEZSj1vyTBG2asTpuEcOdvKVj%2B%2BL1sFafN13zatoBvrGm5UagCqZf4jVWTqk6PCBDEG3ZOHFhTGKK1RVt4P4VWeWcjGvawpwyBJjGjmlAed99%2BlrO%2FIdW0DxTCiw9q9BjqkARWgKqHGmYMhANSPC21l8x9TZ%2B2FxTQni1EXgDpWWMTVBopNBIgIbtgn7PkmzDEs4KL2NKLtddXngDZ8atVeLmoalTipmix76BZIonldteTEMtqp8RBpVPEpjaPh9BICvart66vJAsuQyYKuFctqM2Jxvu6fZNgbtnprJn7CS7Mf6fTA911IvpXlKwd%2FVL%2BQx7AxZPINRPGgOV%2FjBrxdB4yxfFx4&X-Amz-Signature=f92e801f61b0d37475d6035258a43725b5855d5c120cf7b1d1fe6713f63c1747&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46655Y4NXTX%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T042758Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDZN54VrjvZV%2BfBax3bw3d%2Fcs4A%2Ba1b8DRxAJu621IlHwIhAJnOwjRWTtR0Ytq9HyVmGH4CxjCwYc50VOS8z83IaAHXKogECLX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyJWxKQqHBh6xw%2B90Aq3AOcS8fAQAvzfb3Ea25gSL7U7ocugp52%2BimVNPjTLdMGUx5ZbgusN%2F4CTEws8hsLUv6ZpHRUQb1LwLoSNAj9eb8FssW%2BU9ymZ5cy8mbwIYK58AqywdXFpXeKPVwHOQ6ZLuk6Sc2Qx1XaOHkezEMTXnYnELWJF7zU0UdRgqNH4EM7dOZWJqCJurOkTtGUfQLnswkJJngc7bWryDabprqoK2WvQIw90XJmt8J1BI10XhzgLfs5RUsgIKLdsCvgaVSznqUZn4pdG30Rf5pZH9G4aI9sps9lUL%2FlRdDy2vhq%2Fkn9EeYKSRwBZSnbTy7lW77pOHmNjC13vwZkQ6wkrcP%2FGfN1rJAq255EX5q32Hnip6ibM0m5alTjHXmdiTnd40yKXJeR%2FnHEYzU5wNNnhDe6sNu3OivvROr40CAJksIS6WCrZMY22oQwWheBlrmKFmOczBm9gC2XCY4gl0szouKv%2FjnO5wzJyyp3nbUNe%2BKn%2F8XOKyg7yQtHV%2Bhl83b4Wy2JW65ONGEZSj1vyTBG2asTpuEcOdvKVj%2B%2BL1sFafN13zatoBvrGm5UagCqZf4jVWTqk6PCBDEG3ZOHFhTGKK1RVt4P4VWeWcjGvawpwyBJjGjmlAed99%2BlrO%2FIdW0DxTCiw9q9BjqkARWgKqHGmYMhANSPC21l8x9TZ%2B2FxTQni1EXgDpWWMTVBopNBIgIbtgn7PkmzDEs4KL2NKLtddXngDZ8atVeLmoalTipmix76BZIonldteTEMtqp8RBpVPEpjaPh9BICvart66vJAsuQyYKuFctqM2Jxvu6fZNgbtnprJn7CS7Mf6fTA911IvpXlKwd%2FVL%2BQx7AxZPINRPGgOV%2FjBrxdB4yxfFx4&X-Amz-Signature=98406f8a8bd4be0fb34052aa13577473b32b9ba88d2c16df44de83a4cbe84009&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46655Y4NXTX%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T042758Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDZN54VrjvZV%2BfBax3bw3d%2Fcs4A%2Ba1b8DRxAJu621IlHwIhAJnOwjRWTtR0Ytq9HyVmGH4CxjCwYc50VOS8z83IaAHXKogECLX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyJWxKQqHBh6xw%2B90Aq3AOcS8fAQAvzfb3Ea25gSL7U7ocugp52%2BimVNPjTLdMGUx5ZbgusN%2F4CTEws8hsLUv6ZpHRUQb1LwLoSNAj9eb8FssW%2BU9ymZ5cy8mbwIYK58AqywdXFpXeKPVwHOQ6ZLuk6Sc2Qx1XaOHkezEMTXnYnELWJF7zU0UdRgqNH4EM7dOZWJqCJurOkTtGUfQLnswkJJngc7bWryDabprqoK2WvQIw90XJmt8J1BI10XhzgLfs5RUsgIKLdsCvgaVSznqUZn4pdG30Rf5pZH9G4aI9sps9lUL%2FlRdDy2vhq%2Fkn9EeYKSRwBZSnbTy7lW77pOHmNjC13vwZkQ6wkrcP%2FGfN1rJAq255EX5q32Hnip6ibM0m5alTjHXmdiTnd40yKXJeR%2FnHEYzU5wNNnhDe6sNu3OivvROr40CAJksIS6WCrZMY22oQwWheBlrmKFmOczBm9gC2XCY4gl0szouKv%2FjnO5wzJyyp3nbUNe%2BKn%2F8XOKyg7yQtHV%2Bhl83b4Wy2JW65ONGEZSj1vyTBG2asTpuEcOdvKVj%2B%2BL1sFafN13zatoBvrGm5UagCqZf4jVWTqk6PCBDEG3ZOHFhTGKK1RVt4P4VWeWcjGvawpwyBJjGjmlAed99%2BlrO%2FIdW0DxTCiw9q9BjqkARWgKqHGmYMhANSPC21l8x9TZ%2B2FxTQni1EXgDpWWMTVBopNBIgIbtgn7PkmzDEs4KL2NKLtddXngDZ8atVeLmoalTipmix76BZIonldteTEMtqp8RBpVPEpjaPh9BICvart66vJAsuQyYKuFctqM2Jxvu6fZNgbtnprJn7CS7Mf6fTA911IvpXlKwd%2FVL%2BQx7AxZPINRPGgOV%2FjBrxdB4yxfFx4&X-Amz-Signature=99d825ca79fd248fe16db8682cbfc2f3988e82370c5c886d8abd713d2753c473&X-Amz-SignedHeaders=host&x-id=GetObject)


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

