---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4666DWUX7H3%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250213T052255Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEOL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIEfWm81X1vFVb%2B%2F\
  A7b%2Bz6%2FoZZ8DdPsPa861cO6DeIBuSAiEAzUl9JRG4lLKnLFV9xeDML8x9befrbRlkK8J%2BZ8\
  rQ188qiAQI%2B%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPJwAhs\
  BLX3LowYswircA7h%2FhltoHlYoD4WwLRwTHO7fIebiMsii4%2B0nWtnfHWzbPJmCSy49lPhMIC4K\
  ZjjtBvyDzK42z4ZGjE14BBgwpfeGqFVuxpIpldro9NB9his70lWhu75Akl%2BF1Vuw3p2Pw1tq7XU\
  5Nj9B75cW7X8zgd9WenorqjMsWeS2n4LddmxFWogy6AyZab6kiOeIJQP9Uvptqm0vZysCBA5bQZaY\
  u%2BB93Cn%2FH8crfkZG9pcdBDBijb%2BVaZZlVhZlr6mxXKcIORPCGgwYnCq8ztHxCtynW1XNpJM\
  RR8SNnHsTab6aKQ%2B4w0qMOvECU%2FtDLAaEFJuo113ajSQEAUlcV1%2B8szhUqGjX0gh%2BeNS1\
  9UNbC5W05ZMawi3ydDC60cpSKqqh%2Buaf10e84A1lEL5jv6YqYO5klSiNbRzBjAu5BA2wLXtHdpg\
  eMU6qwF2dpNso126MFKMpQpeucX8ykoSnR0JT9A4jI%2BIs%2BPf4waF57Mnsf9bthrqsUTRKgx4k\
  UAozTsiDIqCP7uZHsJOqx%2FLjYhA3laMryLlbqy8et6qbZ2kAJuR1p1xs8gR0Xe6QmefVJdrghFT\
  ci%2BGu%2FgX4VRJV9%2FRtxT5Pwfa8aBhWd3%2F0jsRsv1HeceDgxc8weYrp2Ky6LVDYMICZtb0G\
  OqUBvdmi0SGvPlyK5zS0ykfjwLew0TzYcyXzVHEAUBQdmsQM5YoIAC3f8qgGu4xwwECmLLV830Iu5\
  d0GlcHPFQbdwUoEjBzIpB%2BJzO6SM2XjqjXPC%2BMBJQhYZgac4g2MdhH50FaTSv57lj7cX%2BPw\
  LV7SCt0ov0IpGsy5sa5ShyzGqfL2qXUtO%2FUkY5cWBCHZsN2heUNa7tLhxnIqVRcQJhTkp6LkHiv\
  X&X-Amz-Signature=bb3c82b443c77ffcbcf1d5587d51933b2d810a1cb81655929ff262c00e4\
  99963&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4666JJISNCO%2F20250213%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250213T052141Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEOL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIQD4bcUwYkUrfwzbXGMAFgtptsVv93Aga6GyFlmoJTXgPgIgMmiRHYwiMXmtRTdmrfvOnb\
        p94vFfhSrmn02RS5LleSIqiAQI%2B%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2M\
        zc0MjMxODM4MDUiDOBjV6RlbOOJlOpNZyrcA5Uv7KG0MbFNrScV6WMx144XOWeYwy4CQzHz\
        A%2FMmmI2eSr6nH6lV8sE25Czm%2F3VaiC6lT%2BL%2Bi0B7D3rKxK%2F8Eple7nArQ6Wnt\
        3o8yFXUnQ%2B%2BSnrl6Ac3S6tglzT%2FUoUThNNpu0U%2FqoxClvj9srSbLC8TmlnqlgWl\
        V9tm3aIV3Tidzf8rK4h5KWeq7ZLTygtgHxqdltC3RMU8A%2FC0tDN2o3volWCO2x%2FKzJR\
        eVM1iawpZxoEfc7hCIFVSAnk7WKX6csj5ft%2BLB3S0x1NyjWKn1ZXA%2BoeMFhqxuCfNYN\
        PQhCs3VaFBwvS9JfP%2BzvME5UEhMo54a7zxUAqJvUUe4w9UPSDTiFr7LI43adYKsnSgTTk\
        dywJmABG0b23S80Uj92A6RB1KYPMv3hLblAY%2BB80GEMxMEUcu9ZAdwdDYeM2bYe5Co9gA\
        6IenYvGnyRT%2BzoSlDfIaZeMk8I8dnUJ2uFIxx4gAqV5WjJ6Fl1hSkSHGbnMD9oI8h6%2F\
        qcOwXhSbHLKa6le5nie4QuVR%2BOcaX%2BZEWVy3TN%2Fur30s0QFGrnDzyXl7QRQ4v9twc\
        juIj7hT1Zju5RkHxNAIISCKljWK2dM%2BggXX4YsmPDW9Jq83Q177Hsl3x6JgniFuN9t4lo\
        nGxMKGZtb0GOqUBS2NdF4DVoC95QN4%2BUfL2xKl5W10QGstHXqRFvbG4xNWCIHkN5%2BUL\
        1K6Cdbf1vwiRuDEmTgtXDRV3CxGT%2FGKr5a2LihUJWD4ft3EVWrC%2Bf3X%2Fs%2FEY7VG\
        W22OQEuaB8%2F9ixew1pQGw%2BWbJtne6FqM8t6JDIRpyomPMGDsbDPBZwOXQBfuv1SPz7z\
        FWrNIQ0H1b%2F8nRz1XcEdFiJdFS2g5QJ5B0NuaX&X-Amz-Signature=853e2ec34314a3\
        573fa83475da44fed6c074aa8e3ea2b388bee68d33043ae0f9&X-Amz-SignedHeaders=\
        host&x-id=GetObject"
      expiry_time: "2025-02-13T06:21:41.606Z"
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
UPDATE_TIME: "2025-02-13T05:22:59.347Z"
EXPIRY_TIME: "2025-02-13T06:22:53.359Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SKA5UDCH%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T052253Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC7Whs0l0HwM8eI2ojNPBkjYu3BfecGflqPWyhsKt3EmwIhAKJm2HpQQ4Ic3Ste7dgDXxb8P3jv1AyusZ4ZNjRhKKegKogECPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwfZXMj7v%2B0jQdVKNwq3ANoRBWZHiHPHkymJzarxBWXY1oA7BhRMqor%2BicBM9fBp1XiQSSOdIGeO0vabY%2BnHJM19bBxoDOM%2B1KEKLwZsvodGt71pEeEbV43XHi07a3%2BMWBZov2N%2Fihv3YKMwjurtc0A0mTIwcD3yNdCITb0QNNi42%2Frv8psgSd1Li2IpODGQhUNqW6RTJQSwubacYb9NGlCRKkNKq6ffxfMorSZsokKpkPDofCI%2F%2B227zym9hi%2FW5Wi26YCElfEeAaO4xtvdNHLgpW3%2BkOiQefTurR1rYv11ywfsCQi%2Bs5uLfppN3yOatAqPQHSgP60opZICU40qbnGD2El8DzZkoXYEE8vF3rVOL1S7ZX0MhVilSgDmcAiQbAHIe%2BCrkXmTdkj7nA7HHADGmLNXU2Nklq9GVQw%2F2l%2BY2S9iDm890FpRsDAamoWZP0xZ8XrA%2BlajQb3jWd%2BLdPEgO196F02ggr6VurxL2zgqMdFFPJmb9vKpAyxTNuo878an6ejcGR6uwW0WUNJMWJyRaYvAEO2FfUSIqMUsZ6dbfULdCBSuLYJznQ29v4Ly%2B%2BEo4n6qzb9lbfVEVzJopegEya3Taf1i7k4BkMsS4HUJwree6wwt43CI0NRsLbdtV1RXqiiOypabfbiiTC5mLW9BjqkASb6Fz%2BzQ7uLk7bRSgfVPDl5iPqLXTTkwc4biGRO%2FVBLAsFGrCCN6BT%2FZ8axXLiXy0SxGiFIK378BUXSq405VxSL2tGBMS8ilfiBRfI8WWUuWZJLG9N01SoSYsBTp8Iqy4G8zjFXwOd%2FlvRdng349FFPE%2Fhw81Y%2FrKuF9FTHRcOqYSE6ruPvXRtjiQFlgQtyDhR2xYWEPrqEHtps84%2Fv9QTMd16g&X-Amz-Signature=3432dc2205737d2cfdc450eb0fac246cb8f8e3f3910e6f65ee2a06508303bcd6&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SKA5UDCH%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T052253Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC7Whs0l0HwM8eI2ojNPBkjYu3BfecGflqPWyhsKt3EmwIhAKJm2HpQQ4Ic3Ste7dgDXxb8P3jv1AyusZ4ZNjRhKKegKogECPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwfZXMj7v%2B0jQdVKNwq3ANoRBWZHiHPHkymJzarxBWXY1oA7BhRMqor%2BicBM9fBp1XiQSSOdIGeO0vabY%2BnHJM19bBxoDOM%2B1KEKLwZsvodGt71pEeEbV43XHi07a3%2BMWBZov2N%2Fihv3YKMwjurtc0A0mTIwcD3yNdCITb0QNNi42%2Frv8psgSd1Li2IpODGQhUNqW6RTJQSwubacYb9NGlCRKkNKq6ffxfMorSZsokKpkPDofCI%2F%2B227zym9hi%2FW5Wi26YCElfEeAaO4xtvdNHLgpW3%2BkOiQefTurR1rYv11ywfsCQi%2Bs5uLfppN3yOatAqPQHSgP60opZICU40qbnGD2El8DzZkoXYEE8vF3rVOL1S7ZX0MhVilSgDmcAiQbAHIe%2BCrkXmTdkj7nA7HHADGmLNXU2Nklq9GVQw%2F2l%2BY2S9iDm890FpRsDAamoWZP0xZ8XrA%2BlajQb3jWd%2BLdPEgO196F02ggr6VurxL2zgqMdFFPJmb9vKpAyxTNuo878an6ejcGR6uwW0WUNJMWJyRaYvAEO2FfUSIqMUsZ6dbfULdCBSuLYJznQ29v4Ly%2B%2BEo4n6qzb9lbfVEVzJopegEya3Taf1i7k4BkMsS4HUJwree6wwt43CI0NRsLbdtV1RXqiiOypabfbiiTC5mLW9BjqkASb6Fz%2BzQ7uLk7bRSgfVPDl5iPqLXTTkwc4biGRO%2FVBLAsFGrCCN6BT%2FZ8axXLiXy0SxGiFIK378BUXSq405VxSL2tGBMS8ilfiBRfI8WWUuWZJLG9N01SoSYsBTp8Iqy4G8zjFXwOd%2FlvRdng349FFPE%2Fhw81Y%2FrKuF9FTHRcOqYSE6ruPvXRtjiQFlgQtyDhR2xYWEPrqEHtps84%2Fv9QTMd16g&X-Amz-Signature=aeb9729bd55ea19434883766014ab78b34250bc710b71be4e58c13de576f0947&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SKA5UDCH%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T052253Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC7Whs0l0HwM8eI2ojNPBkjYu3BfecGflqPWyhsKt3EmwIhAKJm2HpQQ4Ic3Ste7dgDXxb8P3jv1AyusZ4ZNjRhKKegKogECPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwfZXMj7v%2B0jQdVKNwq3ANoRBWZHiHPHkymJzarxBWXY1oA7BhRMqor%2BicBM9fBp1XiQSSOdIGeO0vabY%2BnHJM19bBxoDOM%2B1KEKLwZsvodGt71pEeEbV43XHi07a3%2BMWBZov2N%2Fihv3YKMwjurtc0A0mTIwcD3yNdCITb0QNNi42%2Frv8psgSd1Li2IpODGQhUNqW6RTJQSwubacYb9NGlCRKkNKq6ffxfMorSZsokKpkPDofCI%2F%2B227zym9hi%2FW5Wi26YCElfEeAaO4xtvdNHLgpW3%2BkOiQefTurR1rYv11ywfsCQi%2Bs5uLfppN3yOatAqPQHSgP60opZICU40qbnGD2El8DzZkoXYEE8vF3rVOL1S7ZX0MhVilSgDmcAiQbAHIe%2BCrkXmTdkj7nA7HHADGmLNXU2Nklq9GVQw%2F2l%2BY2S9iDm890FpRsDAamoWZP0xZ8XrA%2BlajQb3jWd%2BLdPEgO196F02ggr6VurxL2zgqMdFFPJmb9vKpAyxTNuo878an6ejcGR6uwW0WUNJMWJyRaYvAEO2FfUSIqMUsZ6dbfULdCBSuLYJznQ29v4Ly%2B%2BEo4n6qzb9lbfVEVzJopegEya3Taf1i7k4BkMsS4HUJwree6wwt43CI0NRsLbdtV1RXqiiOypabfbiiTC5mLW9BjqkASb6Fz%2BzQ7uLk7bRSgfVPDl5iPqLXTTkwc4biGRO%2FVBLAsFGrCCN6BT%2FZ8axXLiXy0SxGiFIK378BUXSq405VxSL2tGBMS8ilfiBRfI8WWUuWZJLG9N01SoSYsBTp8Iqy4G8zjFXwOd%2FlvRdng349FFPE%2Fhw81Y%2FrKuF9FTHRcOqYSE6ruPvXRtjiQFlgQtyDhR2xYWEPrqEHtps84%2Fv9QTMd16g&X-Amz-Signature=74e8b8f716de0e8626625fcf04bfaa1ff49d5bfd667fb56818e5cfe79f7bff6b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SKA5UDCH%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T052253Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC7Whs0l0HwM8eI2ojNPBkjYu3BfecGflqPWyhsKt3EmwIhAKJm2HpQQ4Ic3Ste7dgDXxb8P3jv1AyusZ4ZNjRhKKegKogECPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwfZXMj7v%2B0jQdVKNwq3ANoRBWZHiHPHkymJzarxBWXY1oA7BhRMqor%2BicBM9fBp1XiQSSOdIGeO0vabY%2BnHJM19bBxoDOM%2B1KEKLwZsvodGt71pEeEbV43XHi07a3%2BMWBZov2N%2Fihv3YKMwjurtc0A0mTIwcD3yNdCITb0QNNi42%2Frv8psgSd1Li2IpODGQhUNqW6RTJQSwubacYb9NGlCRKkNKq6ffxfMorSZsokKpkPDofCI%2F%2B227zym9hi%2FW5Wi26YCElfEeAaO4xtvdNHLgpW3%2BkOiQefTurR1rYv11ywfsCQi%2Bs5uLfppN3yOatAqPQHSgP60opZICU40qbnGD2El8DzZkoXYEE8vF3rVOL1S7ZX0MhVilSgDmcAiQbAHIe%2BCrkXmTdkj7nA7HHADGmLNXU2Nklq9GVQw%2F2l%2BY2S9iDm890FpRsDAamoWZP0xZ8XrA%2BlajQb3jWd%2BLdPEgO196F02ggr6VurxL2zgqMdFFPJmb9vKpAyxTNuo878an6ejcGR6uwW0WUNJMWJyRaYvAEO2FfUSIqMUsZ6dbfULdCBSuLYJznQ29v4Ly%2B%2BEo4n6qzb9lbfVEVzJopegEya3Taf1i7k4BkMsS4HUJwree6wwt43CI0NRsLbdtV1RXqiiOypabfbiiTC5mLW9BjqkASb6Fz%2BzQ7uLk7bRSgfVPDl5iPqLXTTkwc4biGRO%2FVBLAsFGrCCN6BT%2FZ8axXLiXy0SxGiFIK378BUXSq405VxSL2tGBMS8ilfiBRfI8WWUuWZJLG9N01SoSYsBTp8Iqy4G8zjFXwOd%2FlvRdng349FFPE%2Fhw81Y%2FrKuF9FTHRcOqYSE6ruPvXRtjiQFlgQtyDhR2xYWEPrqEHtps84%2Fv9QTMd16g&X-Amz-Signature=3384725800a34c69422f8be9eef1e57cf8fafbe168c97ac6bb1f26b8becaf740&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SKA5UDCH%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T052253Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC7Whs0l0HwM8eI2ojNPBkjYu3BfecGflqPWyhsKt3EmwIhAKJm2HpQQ4Ic3Ste7dgDXxb8P3jv1AyusZ4ZNjRhKKegKogECPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwfZXMj7v%2B0jQdVKNwq3ANoRBWZHiHPHkymJzarxBWXY1oA7BhRMqor%2BicBM9fBp1XiQSSOdIGeO0vabY%2BnHJM19bBxoDOM%2B1KEKLwZsvodGt71pEeEbV43XHi07a3%2BMWBZov2N%2Fihv3YKMwjurtc0A0mTIwcD3yNdCITb0QNNi42%2Frv8psgSd1Li2IpODGQhUNqW6RTJQSwubacYb9NGlCRKkNKq6ffxfMorSZsokKpkPDofCI%2F%2B227zym9hi%2FW5Wi26YCElfEeAaO4xtvdNHLgpW3%2BkOiQefTurR1rYv11ywfsCQi%2Bs5uLfppN3yOatAqPQHSgP60opZICU40qbnGD2El8DzZkoXYEE8vF3rVOL1S7ZX0MhVilSgDmcAiQbAHIe%2BCrkXmTdkj7nA7HHADGmLNXU2Nklq9GVQw%2F2l%2BY2S9iDm890FpRsDAamoWZP0xZ8XrA%2BlajQb3jWd%2BLdPEgO196F02ggr6VurxL2zgqMdFFPJmb9vKpAyxTNuo878an6ejcGR6uwW0WUNJMWJyRaYvAEO2FfUSIqMUsZ6dbfULdCBSuLYJznQ29v4Ly%2B%2BEo4n6qzb9lbfVEVzJopegEya3Taf1i7k4BkMsS4HUJwree6wwt43CI0NRsLbdtV1RXqiiOypabfbiiTC5mLW9BjqkASb6Fz%2BzQ7uLk7bRSgfVPDl5iPqLXTTkwc4biGRO%2FVBLAsFGrCCN6BT%2FZ8axXLiXy0SxGiFIK378BUXSq405VxSL2tGBMS8ilfiBRfI8WWUuWZJLG9N01SoSYsBTp8Iqy4G8zjFXwOd%2FlvRdng349FFPE%2Fhw81Y%2FrKuF9FTHRcOqYSE6ruPvXRtjiQFlgQtyDhR2xYWEPrqEHtps84%2Fv9QTMd16g&X-Amz-Signature=e14435b1610db42e01dfb8bfbbaf688d22a3736c2cebe446ccf1122db06fb5f5&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XARQBSDK%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T052254Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD4nRqpJRTMBowttCOGWBZQVdIZaFxXiUIeTAqDTaPZTwIgXLR%2BZmzETdm08PEsnEoUoizSnvQE76cDyC9TqUjUA%2BUqiAQI%2B%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPg%2B070GZUNyAASTFCrcAyQXQqJ1rz8%2FsIHUtv76buYZsq87SSawsi%2BX6Q8ZreEaJT5c%2FNSpfyg7xOJ6were7G03Rtpoqw6P4ZycXg4cSpmEBAL5Jl10UKoRwXxmp8ysrpNzryrEegw3twXHJ6%2BKCmsKFMGjX4C0SOwibMCOC9NcJo7RYZXajIycfc%2Frmi9L4EMJ6bmBHLAh3BfRyLMxdjQsBV%2BSN%2F8xWg9V16HYkzuSYOTRXtgaMAfKk0JuWxIPS9%2FNtLd4EzTne0VfIohU6yIFPW6FZdX0l3MtcRJLA3EQ4Tqa1ifhGNEymJOQpJkMonYkYd75A1AKPxXPkj4tdcVeYlyNLnavIMTuVismbfjBbFSvyoPKq%2B5c00k%2FAm9UrmdN68WwldYZPQPldcPwpIJT3Q91wwY%2BaVt0eDmv8RvYA%2BIQylhO5jkKb4xyWvv2TWOkxBLmzirOT93T85hgIqnQLBm48%2Fsa%2Bzvpkx9N30GqQxIcRGjfrSFHE1eYIXc5kenrLdLYR90J9fZtTby93iplIuoq7z9ldaSR9QjOjmKpnLOSf%2FI%2FKtlkEl7ECfvs6fg3MUpkFjqpQa0uSYHxEjLRKSDs1%2BPrK5z5AdLIafo6j5rtriyW%2Bfd5hIPY%2Bszqn%2BK%2BIx37b9TeCckSMJ2Ytb0GOqUBL67JRJ7HkXl0Pg4jo%2B%2Fg%2FYLKJhYsxiTDt55RJKjlXu7Uw5OTTIdDCpt4dTzk29i3qcaMNEwtjQ4MW1vKNcp0To8bk%2BbtaJOVMBwivywctzzpaYy6jI36x%2FRbzrzWNXFeNhsJ9CtvU9NBKztbRS9DGFIdLuzEZcpKer%2F5%2FYGHzg3eoa0T6pgMALhDKTjpketuVMJ%2Fvv1u0d8DGL%2Fi3iziFuyRn7eR&X-Amz-Signature=87edbe495c1b73010937c374fadf04cb58a02d08436148dc76e08d461c1f1d97&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UIFRBR6F%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T052255Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD02C61I3RsHH4lf25kVZhwHo85XDwKZ31bMiXkzqFPTQIhAJ7E2ydY5vwMZMMv3k1M0xq1wpvquSIa2AaJA3EG9g3sKogECPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igz4ruwYYjmKCJIPXecq3AOMuskUun0eCaroOd8GKM77TLwXJVjb0X8%2Ft0hWgvupmN7qbj00Zb39Z3gCafOb7kfmi2aFPUiAz5xuqpNRZI1Ev5z0QX9tPc5XNfVD2GLc8heYcCGoUcSZirDWVhxDkGP0MpHchkGOT9nOJ0Y9bcnE1gkQ4g8GcycUrpT4B2kSnMxQS4Iqt1M6ht6nd7ggBfT20AsPMsr%2BB3%2BcablISy8vqvxICl9nMe%2FEd0BKj%2Fs5HolAbdOfYlpAUoQerGhaEvj1lMk4ZcJzwchLauAFu9x4LYqjMY6oXHnME7QG9%2BoN4T2QaOTvRTWEqI3V%2BBx0uO1giabNo4uvIPZ6%2F%2BAzNEa6W7GJUolzVuVPRqlk0%2B1O4Aq2Y0wVi9ORwRQc2yCwrb861kqNYqJS8Dackt0P5FzlNznlCRoygMyxdeQrBXcs7JRU%2Fk0ojS6yy5o9nPfr6%2FD35eWZKAO3wXksFiPjlvx9HSKO%2BTP0JW7RZDJ1K8zpas7CVofTHC6qgnjtm6%2Bf0KzOibYUOH9XyxeWZbU4xfGNWzgPFgqe0ZBsJAwwJnWTVtVCNa97Jbp%2B4lo%2FrvtWKETXArFAgim8tW6s8i81VAH7s3IHwkrk%2FEtgqfnqOy%2FxKvNz5qChooZry5SzuDC8mLW9BjqkAXSGs1u6XQOUNZXLC71vwPDLWMG4rAdyUq7tOtllL9zn6obCl7rx1a%2BwGSA%2FuTw5u0OVLlK2K72zZmyyxHYaOJVKovEXXe6dExgSmDY3Pp6u69AXoaPfYtLolA3EcByyXx3wspQX20JQ9%2F7AsEp3VBM1mnulQIx30HJzOVnFE6PxiNdNstfqEI5r46fPB7tJ2rtSCSlUJShwcGwqyA4t5iht%2F07l&X-Amz-Signature=475ee7c08242c12816d14ad7936a8bfc86cd4576d9dd29e6bec88728563b2f5d&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SKA5UDCH%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T052253Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC7Whs0l0HwM8eI2ojNPBkjYu3BfecGflqPWyhsKt3EmwIhAKJm2HpQQ4Ic3Ste7dgDXxb8P3jv1AyusZ4ZNjRhKKegKogECPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwfZXMj7v%2B0jQdVKNwq3ANoRBWZHiHPHkymJzarxBWXY1oA7BhRMqor%2BicBM9fBp1XiQSSOdIGeO0vabY%2BnHJM19bBxoDOM%2B1KEKLwZsvodGt71pEeEbV43XHi07a3%2BMWBZov2N%2Fihv3YKMwjurtc0A0mTIwcD3yNdCITb0QNNi42%2Frv8psgSd1Li2IpODGQhUNqW6RTJQSwubacYb9NGlCRKkNKq6ffxfMorSZsokKpkPDofCI%2F%2B227zym9hi%2FW5Wi26YCElfEeAaO4xtvdNHLgpW3%2BkOiQefTurR1rYv11ywfsCQi%2Bs5uLfppN3yOatAqPQHSgP60opZICU40qbnGD2El8DzZkoXYEE8vF3rVOL1S7ZX0MhVilSgDmcAiQbAHIe%2BCrkXmTdkj7nA7HHADGmLNXU2Nklq9GVQw%2F2l%2BY2S9iDm890FpRsDAamoWZP0xZ8XrA%2BlajQb3jWd%2BLdPEgO196F02ggr6VurxL2zgqMdFFPJmb9vKpAyxTNuo878an6ejcGR6uwW0WUNJMWJyRaYvAEO2FfUSIqMUsZ6dbfULdCBSuLYJznQ29v4Ly%2B%2BEo4n6qzb9lbfVEVzJopegEya3Taf1i7k4BkMsS4HUJwree6wwt43CI0NRsLbdtV1RXqiiOypabfbiiTC5mLW9BjqkASb6Fz%2BzQ7uLk7bRSgfVPDl5iPqLXTTkwc4biGRO%2FVBLAsFGrCCN6BT%2FZ8axXLiXy0SxGiFIK378BUXSq405VxSL2tGBMS8ilfiBRfI8WWUuWZJLG9N01SoSYsBTp8Iqy4G8zjFXwOd%2FlvRdng349FFPE%2Fhw81Y%2FrKuF9FTHRcOqYSE6ruPvXRtjiQFlgQtyDhR2xYWEPrqEHtps84%2Fv9QTMd16g&X-Amz-Signature=89b59557e26f72c75ddcce0ffecccd1e2abe2689eced5f4d76df66aebf6e21f4&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SKA5UDCH%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T052253Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC7Whs0l0HwM8eI2ojNPBkjYu3BfecGflqPWyhsKt3EmwIhAKJm2HpQQ4Ic3Ste7dgDXxb8P3jv1AyusZ4ZNjRhKKegKogECPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwfZXMj7v%2B0jQdVKNwq3ANoRBWZHiHPHkymJzarxBWXY1oA7BhRMqor%2BicBM9fBp1XiQSSOdIGeO0vabY%2BnHJM19bBxoDOM%2B1KEKLwZsvodGt71pEeEbV43XHi07a3%2BMWBZov2N%2Fihv3YKMwjurtc0A0mTIwcD3yNdCITb0QNNi42%2Frv8psgSd1Li2IpODGQhUNqW6RTJQSwubacYb9NGlCRKkNKq6ffxfMorSZsokKpkPDofCI%2F%2B227zym9hi%2FW5Wi26YCElfEeAaO4xtvdNHLgpW3%2BkOiQefTurR1rYv11ywfsCQi%2Bs5uLfppN3yOatAqPQHSgP60opZICU40qbnGD2El8DzZkoXYEE8vF3rVOL1S7ZX0MhVilSgDmcAiQbAHIe%2BCrkXmTdkj7nA7HHADGmLNXU2Nklq9GVQw%2F2l%2BY2S9iDm890FpRsDAamoWZP0xZ8XrA%2BlajQb3jWd%2BLdPEgO196F02ggr6VurxL2zgqMdFFPJmb9vKpAyxTNuo878an6ejcGR6uwW0WUNJMWJyRaYvAEO2FfUSIqMUsZ6dbfULdCBSuLYJznQ29v4Ly%2B%2BEo4n6qzb9lbfVEVzJopegEya3Taf1i7k4BkMsS4HUJwree6wwt43CI0NRsLbdtV1RXqiiOypabfbiiTC5mLW9BjqkASb6Fz%2BzQ7uLk7bRSgfVPDl5iPqLXTTkwc4biGRO%2FVBLAsFGrCCN6BT%2FZ8axXLiXy0SxGiFIK378BUXSq405VxSL2tGBMS8ilfiBRfI8WWUuWZJLG9N01SoSYsBTp8Iqy4G8zjFXwOd%2FlvRdng349FFPE%2Fhw81Y%2FrKuF9FTHRcOqYSE6ruPvXRtjiQFlgQtyDhR2xYWEPrqEHtps84%2Fv9QTMd16g&X-Amz-Signature=e062dd446e82d3231d08b70664a552df8c1e6a9d7bedc03e6ba916cef99b441f&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SKA5UDCH%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T052253Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC7Whs0l0HwM8eI2ojNPBkjYu3BfecGflqPWyhsKt3EmwIhAKJm2HpQQ4Ic3Ste7dgDXxb8P3jv1AyusZ4ZNjRhKKegKogECPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwfZXMj7v%2B0jQdVKNwq3ANoRBWZHiHPHkymJzarxBWXY1oA7BhRMqor%2BicBM9fBp1XiQSSOdIGeO0vabY%2BnHJM19bBxoDOM%2B1KEKLwZsvodGt71pEeEbV43XHi07a3%2BMWBZov2N%2Fihv3YKMwjurtc0A0mTIwcD3yNdCITb0QNNi42%2Frv8psgSd1Li2IpODGQhUNqW6RTJQSwubacYb9NGlCRKkNKq6ffxfMorSZsokKpkPDofCI%2F%2B227zym9hi%2FW5Wi26YCElfEeAaO4xtvdNHLgpW3%2BkOiQefTurR1rYv11ywfsCQi%2Bs5uLfppN3yOatAqPQHSgP60opZICU40qbnGD2El8DzZkoXYEE8vF3rVOL1S7ZX0MhVilSgDmcAiQbAHIe%2BCrkXmTdkj7nA7HHADGmLNXU2Nklq9GVQw%2F2l%2BY2S9iDm890FpRsDAamoWZP0xZ8XrA%2BlajQb3jWd%2BLdPEgO196F02ggr6VurxL2zgqMdFFPJmb9vKpAyxTNuo878an6ejcGR6uwW0WUNJMWJyRaYvAEO2FfUSIqMUsZ6dbfULdCBSuLYJznQ29v4Ly%2B%2BEo4n6qzb9lbfVEVzJopegEya3Taf1i7k4BkMsS4HUJwree6wwt43CI0NRsLbdtV1RXqiiOypabfbiiTC5mLW9BjqkASb6Fz%2BzQ7uLk7bRSgfVPDl5iPqLXTTkwc4biGRO%2FVBLAsFGrCCN6BT%2FZ8axXLiXy0SxGiFIK378BUXSq405VxSL2tGBMS8ilfiBRfI8WWUuWZJLG9N01SoSYsBTp8Iqy4G8zjFXwOd%2FlvRdng349FFPE%2Fhw81Y%2FrKuF9FTHRcOqYSE6ruPvXRtjiQFlgQtyDhR2xYWEPrqEHtps84%2Fv9QTMd16g&X-Amz-Signature=a5981d9c22e8d8407b89f45b7223a7be8536fb501e978d355850100a4a2e8607&X-Amz-SignedHeaders=host&x-id=GetObject)


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

