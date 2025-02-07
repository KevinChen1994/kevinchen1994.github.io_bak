---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4665Q6665IO%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250207T222152Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEGYaCXVzLXdlc3QtMiJHMEUCIQDWVQ09MZzlOZQMXdaU6jhC4j18iOFRMmLCDqPH4f351AIgDIL\
  4m%2BlJoVP0cwfcRL%2FhS22iyV%2FF6Aom%2FnHUAfrxI4gq%2FwMIfxAAGgw2Mzc0MjMxODM4MD\
  UiDBJilXSroc3t6BXihSrcA9QUfE1P5aOJh8A7RAA0ksePn8iV6DXiccMWYechEqmwF9faP7%2FKB\
  r2rYi206NU5TON6E7Wn7EOM4BcUH%2FtBJ5ILZ3qRG0n1t25nPckcq%2BUW4R9vIkLS4aXD73Hzo1\
  euOAN3KPC4tud41ey%2Fps6ozyYhpw%2BlB8T4qS7urHm6nU80RWU5hi%2F1JsLIXhFpWHaoagC4H\
  phRtqSIFcXRm4955Gb2NqeS9aB58l4tjv8CWtjT2a7cF0Vyz%2Fa40KL78JFlNLUzMsd08kfh5v3d\
  4PZMJ8MrMcbC28EomXLo1Mm1rQHIsmCAPUlgvkLbD9C6UL0ZZtWMdPmT7a1UUZIyqkIxL58DsWayQ\
  LwN%2BDHUjOv9F77hMAYMZXZMUqxoLKBMy0Wk%2BZOvxqlL4jCcuP6BhXd%2BTkMydi9VzecOovnE\
  ZB6IXwNEe0Ks5jC67OeZ5I%2Bdtq%2FambsCtk%2BfYzlggd0Zwb3KyDR7YtXP4noSDprLH8%2F%2\
  Fu%2B7cFLsJbNxxOoAT%2BSE2A4mPK6GxXY7pl7H%2Fry21cJavcZSKK85pCSHA6rFzp32%2BaJVn\
  KuNaJ68%2FbuncoEi7DUwP88A2%2Ft37P5S82FyHwEZrB9hGPVVg6rnaXu8fK3YqZd4TLHph5e5D7\
  mp%2FsT%2BoMMT%2Fmb0GOqUBd97mOLHeYEiqtDAl2rKjevr67jMPG%2FPc3yLlO2ZWR2UrX220js\
  T19Wdeu5dXAqn6dNGt0eo4Gr5DIRwPWXYLScYkLxx9ejpn0EMVOuTwUHU1D%2BWaxDzyvrtM6%2B3\
  hMmXwlOOZqD2B2X6NAON%2B4d21vmOhfX85JSjIW14yxWjgwVql4jPYCSeCiMifDGV6iH8dPoux%2\
  F%2BIm3LCxWm4gVdqhgXSw6Spq&X-Amz-Signature=b54f740dc2f0a4e798b00db7959250e9fd\
  6d3b087b178d5b669540eb9d605dee&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466YBX2JYOS%2F20250207%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250207T222041Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEGYaCXVzLXdlc3QtMiJGMEQCIHZF2ARtlje49QMkJSt1e6Iu6opbnMf\
        YtdTEHC1iTTA9AiB%2BshbnYxPWCZV%2BokDjeDP5zhsVbesVDWdYXx%2BCHJBrICr%2FAw\
        h%2FEAAaDDYzNzQyMzE4MzgwNSIMOVG3goKq9ZqDg1MhKtwDIUmgz8ge2vGfmPAUOlRV0oe\
        SiLu2kRZ98Bnb%2BTyJ4VXhQPt60Q1soVjBtmxR3TO5TWElOPJ2o8xOFGui3ceue6S1hNyq\
        6NxmqptIRurEEJxD%2BicC2j7cS8Cwmwdup6YZNEYbCPFvTkyJY7hX2e%2Fkk1Jy6nr4Ra%\
        2BLipZA8Qy%2B9de7p5QfueUiC95Y%2B2h9FKHkaad5gb9hg7WH9MyQx2w5Jct%2B6IoEek\
        4kXi5%2Bga10yMEFENat9YDBcRLU97Pirg7A2Tjgal0LKpatlKM1BUJlh1gBrvuEDFpsUPC\
        efEsHGA70fVgxW1S1Zl1pYRp3HhRci2pfoIGF2pQKaWfz69vgu8IAV5oL8oiosg%2Fx3C4j\
        VhiAa2T8PT7i8iTlujMv6JSQSgH3W%2B%2BM%2BqnFyBPERZjkaVX1ouraAU64U344ypR46\
        xsM%2BfVdKzh4wRQWsLpYeQQ6L1rzZSIYjaEYmTWERSJU%2FABHxM2K4b%2BzExQ4TcNkXc\
        cXaidhGJ%2BlXBUudSyfD2VEkXZNkBJlIC9Jv0jfGdCVdsasAMHv0i%2BSxFpYw40UwBMqf\
        r%2B7iX07i05%2Barov2KdnQo3jQNFCOyKGq1CUpx3ikqoTHzkdjGrVROmyAjx006qa9KDq\
        kvfaiLxNbwUwvf%2BZvQY6pgEva%2FsqucIVDktjcmN1fKwes1%2FRNJmi5agwOKPdnZriB\
        Tor9QxDhGERvxNUCnq6HB4KMl7loDKi01bmAbRMAUSZ6BohORr9ZeBGsX221dtpmtWUSbQu\
        yug8Qe3mBvj%2FiqIheMImaxg6IZuURlPvp19o0fluUlA0i%2BE5ak884%2FpY5A24tiNfD\
        iVGK17Xx05qowbLq9L97Olm%2F7fj%2BiOdjrVbYMnIVJmx&X-Amz-Signature=7a93b62\
        9a8444e5f53342312b10cf101bfeacbcfe5710142a49964fa1836cb96&X-Amz-SignedH\
        eaders=host&x-id=GetObject"
      expiry_time: "2025-02-07T23:20:41.229Z"
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
UPDATE_TIME: "2025-02-07T22:21:59.236Z"
EXPIRY_TIME: "2025-02-07T23:21:49.921Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466W4PU6TCV%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T222150Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGYaCXVzLXdlc3QtMiJHMEUCIQDzlsVdfHX5SFcN%2BUUYK5odWcazQ650ya7uekliHJ%2Bl0AIgdSZNKmGi5KVzlhMEIBXnVaEX4RSUcmEVnoSNTllJseEq%2FwMIfxAAGgw2Mzc0MjMxODM4MDUiDKD3E2ZIMwXuUxYRHircA9SC2Zz3EM6gEUXPtk%2FCZ9CdNQPjynibcguI86o%2BQKT7fJ2VXPZSpbOTG9uVXKqwJa5RmpxJ6mN4k08D%2FhUF3vve9Wwp4pueXS3OSdLqdme9TxZoycvEchZDgSvFudTAZ%2FNY3n72ppq%2BU95loKOmIe0gr7chFehfncN0gQVgDgTCBpdtv%2FjOs6RSwcFldVvAsLiOEyoi9rKU7RHCZJkQPSVRke1g5fRK1Wek84STl5wXU2%2B7bkreUPCUNFMlo3%2BcFjCV5QQeubd1vlFCkbOK%2FCdvPtCm%2FlaYOb%2FaSVuZXaO1ELx5CZfc708psMjvCR3mgYjsZz9tgJrXNIlGuFv8HfzktFMzTwukmRxxryaF3y5lCoFjk2mUsGxF4tXN6Pya9uH%2F3Y7g%2BBgAwZ7otB6aAmJvU%2B2n6Fg4ZAxhuMHpHEYPLtPJoKHiSc%2B%2BAzdbjv7TNLtFe8HdH04PzgMsr%2FEfj6FQJrFc0MsBZv2qSp9FafcwutqKXKr0ZVA%2BguOt4IG%2BdmFpD5r3VwTgILLlQKK83%2By8xjx1E5v6%2BkVOAB8syjJfMchqE3mUieY8v9p2akkJcI0ZJUvDpbt%2BTqBWi6%2BZF%2BdMIZRJtyZrJiOh1XaXQD6dKeFIcZFrmrTw9FzPMN%2BAmr0GOqUBqLvXachnZ3s5fxdafpT%2BUjBXwpS9LKWGTIh4XbwPOTNJNpwZetK05veeTbRH7BXiTpw0OrftfH%2FSQxv0RSAYIyZ7JFL8LQy8Ee0XD9guTEl4oX93SY%2B7nAfqf6%2FTnRSu6XtIy2yrdKm50J0VzKwuSvwO%2FtvvB5R95FeyGcQb3Dr4Pz2ttEKRyesQWbS0eHcWUs1cA%2BDs3zkm7O0JUxtPM3KV2hfZ&X-Amz-Signature=445798852a5a050e2ee56c6f64b82e19c9bcd298e32880f7aeed110612dedc33&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466W4PU6TCV%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T222150Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGYaCXVzLXdlc3QtMiJHMEUCIQDzlsVdfHX5SFcN%2BUUYK5odWcazQ650ya7uekliHJ%2Bl0AIgdSZNKmGi5KVzlhMEIBXnVaEX4RSUcmEVnoSNTllJseEq%2FwMIfxAAGgw2Mzc0MjMxODM4MDUiDKD3E2ZIMwXuUxYRHircA9SC2Zz3EM6gEUXPtk%2FCZ9CdNQPjynibcguI86o%2BQKT7fJ2VXPZSpbOTG9uVXKqwJa5RmpxJ6mN4k08D%2FhUF3vve9Wwp4pueXS3OSdLqdme9TxZoycvEchZDgSvFudTAZ%2FNY3n72ppq%2BU95loKOmIe0gr7chFehfncN0gQVgDgTCBpdtv%2FjOs6RSwcFldVvAsLiOEyoi9rKU7RHCZJkQPSVRke1g5fRK1Wek84STl5wXU2%2B7bkreUPCUNFMlo3%2BcFjCV5QQeubd1vlFCkbOK%2FCdvPtCm%2FlaYOb%2FaSVuZXaO1ELx5CZfc708psMjvCR3mgYjsZz9tgJrXNIlGuFv8HfzktFMzTwukmRxxryaF3y5lCoFjk2mUsGxF4tXN6Pya9uH%2F3Y7g%2BBgAwZ7otB6aAmJvU%2B2n6Fg4ZAxhuMHpHEYPLtPJoKHiSc%2B%2BAzdbjv7TNLtFe8HdH04PzgMsr%2FEfj6FQJrFc0MsBZv2qSp9FafcwutqKXKr0ZVA%2BguOt4IG%2BdmFpD5r3VwTgILLlQKK83%2By8xjx1E5v6%2BkVOAB8syjJfMchqE3mUieY8v9p2akkJcI0ZJUvDpbt%2BTqBWi6%2BZF%2BdMIZRJtyZrJiOh1XaXQD6dKeFIcZFrmrTw9FzPMN%2BAmr0GOqUBqLvXachnZ3s5fxdafpT%2BUjBXwpS9LKWGTIh4XbwPOTNJNpwZetK05veeTbRH7BXiTpw0OrftfH%2FSQxv0RSAYIyZ7JFL8LQy8Ee0XD9guTEl4oX93SY%2B7nAfqf6%2FTnRSu6XtIy2yrdKm50J0VzKwuSvwO%2FtvvB5R95FeyGcQb3Dr4Pz2ttEKRyesQWbS0eHcWUs1cA%2BDs3zkm7O0JUxtPM3KV2hfZ&X-Amz-Signature=e851bcc9ad6eee220a263d93cf5a1635cbb9de99672f718f0baef780f877eabd&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466W4PU6TCV%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T222150Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGYaCXVzLXdlc3QtMiJHMEUCIQDzlsVdfHX5SFcN%2BUUYK5odWcazQ650ya7uekliHJ%2Bl0AIgdSZNKmGi5KVzlhMEIBXnVaEX4RSUcmEVnoSNTllJseEq%2FwMIfxAAGgw2Mzc0MjMxODM4MDUiDKD3E2ZIMwXuUxYRHircA9SC2Zz3EM6gEUXPtk%2FCZ9CdNQPjynibcguI86o%2BQKT7fJ2VXPZSpbOTG9uVXKqwJa5RmpxJ6mN4k08D%2FhUF3vve9Wwp4pueXS3OSdLqdme9TxZoycvEchZDgSvFudTAZ%2FNY3n72ppq%2BU95loKOmIe0gr7chFehfncN0gQVgDgTCBpdtv%2FjOs6RSwcFldVvAsLiOEyoi9rKU7RHCZJkQPSVRke1g5fRK1Wek84STl5wXU2%2B7bkreUPCUNFMlo3%2BcFjCV5QQeubd1vlFCkbOK%2FCdvPtCm%2FlaYOb%2FaSVuZXaO1ELx5CZfc708psMjvCR3mgYjsZz9tgJrXNIlGuFv8HfzktFMzTwukmRxxryaF3y5lCoFjk2mUsGxF4tXN6Pya9uH%2F3Y7g%2BBgAwZ7otB6aAmJvU%2B2n6Fg4ZAxhuMHpHEYPLtPJoKHiSc%2B%2BAzdbjv7TNLtFe8HdH04PzgMsr%2FEfj6FQJrFc0MsBZv2qSp9FafcwutqKXKr0ZVA%2BguOt4IG%2BdmFpD5r3VwTgILLlQKK83%2By8xjx1E5v6%2BkVOAB8syjJfMchqE3mUieY8v9p2akkJcI0ZJUvDpbt%2BTqBWi6%2BZF%2BdMIZRJtyZrJiOh1XaXQD6dKeFIcZFrmrTw9FzPMN%2BAmr0GOqUBqLvXachnZ3s5fxdafpT%2BUjBXwpS9LKWGTIh4XbwPOTNJNpwZetK05veeTbRH7BXiTpw0OrftfH%2FSQxv0RSAYIyZ7JFL8LQy8Ee0XD9guTEl4oX93SY%2B7nAfqf6%2FTnRSu6XtIy2yrdKm50J0VzKwuSvwO%2FtvvB5R95FeyGcQb3Dr4Pz2ttEKRyesQWbS0eHcWUs1cA%2BDs3zkm7O0JUxtPM3KV2hfZ&X-Amz-Signature=229626fd13f1ee91a4fb9cd10a467d1df3f43d9c898419cdde5981563cc537d0&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466W4PU6TCV%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T222150Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGYaCXVzLXdlc3QtMiJHMEUCIQDzlsVdfHX5SFcN%2BUUYK5odWcazQ650ya7uekliHJ%2Bl0AIgdSZNKmGi5KVzlhMEIBXnVaEX4RSUcmEVnoSNTllJseEq%2FwMIfxAAGgw2Mzc0MjMxODM4MDUiDKD3E2ZIMwXuUxYRHircA9SC2Zz3EM6gEUXPtk%2FCZ9CdNQPjynibcguI86o%2BQKT7fJ2VXPZSpbOTG9uVXKqwJa5RmpxJ6mN4k08D%2FhUF3vve9Wwp4pueXS3OSdLqdme9TxZoycvEchZDgSvFudTAZ%2FNY3n72ppq%2BU95loKOmIe0gr7chFehfncN0gQVgDgTCBpdtv%2FjOs6RSwcFldVvAsLiOEyoi9rKU7RHCZJkQPSVRke1g5fRK1Wek84STl5wXU2%2B7bkreUPCUNFMlo3%2BcFjCV5QQeubd1vlFCkbOK%2FCdvPtCm%2FlaYOb%2FaSVuZXaO1ELx5CZfc708psMjvCR3mgYjsZz9tgJrXNIlGuFv8HfzktFMzTwukmRxxryaF3y5lCoFjk2mUsGxF4tXN6Pya9uH%2F3Y7g%2BBgAwZ7otB6aAmJvU%2B2n6Fg4ZAxhuMHpHEYPLtPJoKHiSc%2B%2BAzdbjv7TNLtFe8HdH04PzgMsr%2FEfj6FQJrFc0MsBZv2qSp9FafcwutqKXKr0ZVA%2BguOt4IG%2BdmFpD5r3VwTgILLlQKK83%2By8xjx1E5v6%2BkVOAB8syjJfMchqE3mUieY8v9p2akkJcI0ZJUvDpbt%2BTqBWi6%2BZF%2BdMIZRJtyZrJiOh1XaXQD6dKeFIcZFrmrTw9FzPMN%2BAmr0GOqUBqLvXachnZ3s5fxdafpT%2BUjBXwpS9LKWGTIh4XbwPOTNJNpwZetK05veeTbRH7BXiTpw0OrftfH%2FSQxv0RSAYIyZ7JFL8LQy8Ee0XD9guTEl4oX93SY%2B7nAfqf6%2FTnRSu6XtIy2yrdKm50J0VzKwuSvwO%2FtvvB5R95FeyGcQb3Dr4Pz2ttEKRyesQWbS0eHcWUs1cA%2BDs3zkm7O0JUxtPM3KV2hfZ&X-Amz-Signature=6da5d97d17969dbbea5e8c41190cfc04824bb542b28f93acee7d42c3dbd7e93c&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466W4PU6TCV%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T222150Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGYaCXVzLXdlc3QtMiJHMEUCIQDzlsVdfHX5SFcN%2BUUYK5odWcazQ650ya7uekliHJ%2Bl0AIgdSZNKmGi5KVzlhMEIBXnVaEX4RSUcmEVnoSNTllJseEq%2FwMIfxAAGgw2Mzc0MjMxODM4MDUiDKD3E2ZIMwXuUxYRHircA9SC2Zz3EM6gEUXPtk%2FCZ9CdNQPjynibcguI86o%2BQKT7fJ2VXPZSpbOTG9uVXKqwJa5RmpxJ6mN4k08D%2FhUF3vve9Wwp4pueXS3OSdLqdme9TxZoycvEchZDgSvFudTAZ%2FNY3n72ppq%2BU95loKOmIe0gr7chFehfncN0gQVgDgTCBpdtv%2FjOs6RSwcFldVvAsLiOEyoi9rKU7RHCZJkQPSVRke1g5fRK1Wek84STl5wXU2%2B7bkreUPCUNFMlo3%2BcFjCV5QQeubd1vlFCkbOK%2FCdvPtCm%2FlaYOb%2FaSVuZXaO1ELx5CZfc708psMjvCR3mgYjsZz9tgJrXNIlGuFv8HfzktFMzTwukmRxxryaF3y5lCoFjk2mUsGxF4tXN6Pya9uH%2F3Y7g%2BBgAwZ7otB6aAmJvU%2B2n6Fg4ZAxhuMHpHEYPLtPJoKHiSc%2B%2BAzdbjv7TNLtFe8HdH04PzgMsr%2FEfj6FQJrFc0MsBZv2qSp9FafcwutqKXKr0ZVA%2BguOt4IG%2BdmFpD5r3VwTgILLlQKK83%2By8xjx1E5v6%2BkVOAB8syjJfMchqE3mUieY8v9p2akkJcI0ZJUvDpbt%2BTqBWi6%2BZF%2BdMIZRJtyZrJiOh1XaXQD6dKeFIcZFrmrTw9FzPMN%2BAmr0GOqUBqLvXachnZ3s5fxdafpT%2BUjBXwpS9LKWGTIh4XbwPOTNJNpwZetK05veeTbRH7BXiTpw0OrftfH%2FSQxv0RSAYIyZ7JFL8LQy8Ee0XD9guTEl4oX93SY%2B7nAfqf6%2FTnRSu6XtIy2yrdKm50J0VzKwuSvwO%2FtvvB5R95FeyGcQb3Dr4Pz2ttEKRyesQWbS0eHcWUs1cA%2BDs3zkm7O0JUxtPM3KV2hfZ&X-Amz-Signature=92f4ee1ca9d370ea2b0493ab93a0e846086572de2f97cf3349dcea9dd5329780&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XBNHF7OP%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T222150Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGYaCXVzLXdlc3QtMiJIMEYCIQCaykEgck3m0l38NY32HwY2cs3ouke45KoLcexJeB7CpwIhAK0ooOPVXL169DDrFI%2FxCXCygjFs52gjZE0xVuz6lmgqKv8DCH8QABoMNjM3NDIzMTgzODA1IgwonAZ1T%2B3Aa9wErqAq3AM5R%2BzpHOh4iMqlPfb6z6BaBDXc6qV181h0ek3s1t%2F%2F6iZcL8uAE45uQMu%2FLbrWvijIKjdXU0Gh%2FEziN16A6LN53a9HUpEDELnFK%2FZywos5zMWpXeWcgrWQQ3FxPWSc8CGd%2FZ8nJg3jwu6hOk84885plGFr0YVt%2BEHQLWsclavygJrUmf1q7DbV6pr%2BnKA0U4rWMsFUcDCnWQSl6U4rxHDq3SxZqT6rAuLMngU77ykk87hTCkmKmG1TJGCOhNpSGdf0NGBOmRsi7WwiRLRjnnYPAVTwFz%2BH%2BHeAav80fINp4hZk7dwN9QrHxYfWK%2BjhhZejziyLQ0U9PctfGPFJx8YLkWYJ245m0qo87TDSkmfWbf9ZEgLaLRfWLg5lHwvCehxAD8pJdOsYWrdNY%2F4kz8Gu9tcCf7P6%2FV0M17Lrk5Y5sGESzc0HW9zdkW9fkrZag0AOXPpQNcIjctlUg%2FkoyKydIDpWWwDRKr%2FWm3tTx8ObrxfIXFvLG0EghX%2FVL9CSf65hGWJZztp8rAi83HBCX9Ye55agK5xDjqgCaZOMzWLOzk63%2FzW7T08HYyUCarDd1cBlD5K%2BhM3nAFiXCBAaUZO3kPAG7DDzF0WwWF5WB8sWPG9GTYodjXZw13Z5mDDegJq9BjqkAYRkp51UmkzzOdw0lcsUyuH4vc75ZlDmVQ%2BJR2Mfm7gRNwJTxCc18jQd6n65KycvbyaPSC2KOlVb%2F02BbqxdOyfzshqp0I26OmDGJ5D04IFrgLBwdCy4tKoecDX5Pnx6HsIkjOtVVMxb3nEBH%2BxOSE6%2B3p0la7Rst6%2FqkQMxbizSv1E4Bp2jtKr7d%2BBtNaGBatZ%2FIOgau5UoCYI7i2cm7DfW8mYJ&X-Amz-Signature=047590ef0d8d58ed22abda14fec1a68b7f40fa1c7b7273f727af36c895c32b00&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SLNNQTDY%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T222151Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGYaCXVzLXdlc3QtMiJHMEUCIQDkdUSEpF9rKSp1%2BMYCC%2Bg0VzlnArxjACV42Bl54rlqdwIgcQ3CoOlmxQx%2F733hGQjl7tvARUobMEfw%2FbnKXl9qUxEq%2FwMIfxAAGgw2Mzc0MjMxODM4MDUiDCHr0NqUgS8a7DEbiircAwN9aNUQ4ljJSahggANfm%2FiJ8yEDev2qVM9l04aAyDdOnJGidZtth1ojXSlmamuleWxL7O7J0ExmmIQLhzgVlV5WFetM2EwTrIuzuds8EMofgpzDamE%2FmmEOeKyeoACZ86hXiSNxaa1b5zofYg5Wgs0tY0EyVrnZPh4DIAFoeqgNskijC4CNchJgLfo7dM2JNE4GCJf5bOHATS8TljkON1fr0bVIE7p7YM5oSNcl9rwMb%2FGm4qsuVdTt6NW1ojmxN2C8znBH3I5yopYnkaNUxyHqvaZuflCNYWgkau4tmdU8ZvcR9pH0DuhLzoeLEBPj2A2qye88rwS3CKVlqPDnesttsCMYRz54NxZQDDzO1QCTj%2Fh85cEddBxIk8SCG%2FBeFNzN3oUaIOCX4JaEsy2Rwevp%2FtK4eRJ5jmXdEKUnUCfMDf3Pnvi2XX0KOAYeVuBxkGhsHpP%2BMOtolNbbmRNi2dm4kyalOxfCW0IUTDT2gQoZagB%2F0BUdLKxPiXH6aTNO%2BHTfy3IMnsPujkj8LRR4vw%2B8R7gG2RYWH62vL0v6VO0zKWGqH7UGIvYiJo0fa2CEhA6%2F0eZDI0y%2Bep65Ce%2FLjojQuV5fi3Wl4R%2B0wlYOoSvBNv1sXZTAMbtG%2BwzlMN%2BAmr0GOqUBwRmPPnSKoAQOvP3LyTCH%2FUdFStiaeLM8u9Cf6kwfDbsrPErtzbGJUxK4thXsy6N0z47MZZO2l%2BmYNwfl4nqQh%2F%2FRNbVK6bggQhwlNtFiqneedypSx4BSBPZGXl91BhSTjVACoyuK%2BtvIU7F3UoMIBOMC713NLLY2QZ6lTBCTuEkjqY6xQKkAIQlfxeD%2BA5mVmt93CXMh7WqpIqqJErmpcU%2BYMP1O&X-Amz-Signature=22750891d5bac5f9de7841349e238c41266ee65a475501585a309f69f25c1179&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466W4PU6TCV%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T222150Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGYaCXVzLXdlc3QtMiJHMEUCIQDzlsVdfHX5SFcN%2BUUYK5odWcazQ650ya7uekliHJ%2Bl0AIgdSZNKmGi5KVzlhMEIBXnVaEX4RSUcmEVnoSNTllJseEq%2FwMIfxAAGgw2Mzc0MjMxODM4MDUiDKD3E2ZIMwXuUxYRHircA9SC2Zz3EM6gEUXPtk%2FCZ9CdNQPjynibcguI86o%2BQKT7fJ2VXPZSpbOTG9uVXKqwJa5RmpxJ6mN4k08D%2FhUF3vve9Wwp4pueXS3OSdLqdme9TxZoycvEchZDgSvFudTAZ%2FNY3n72ppq%2BU95loKOmIe0gr7chFehfncN0gQVgDgTCBpdtv%2FjOs6RSwcFldVvAsLiOEyoi9rKU7RHCZJkQPSVRke1g5fRK1Wek84STl5wXU2%2B7bkreUPCUNFMlo3%2BcFjCV5QQeubd1vlFCkbOK%2FCdvPtCm%2FlaYOb%2FaSVuZXaO1ELx5CZfc708psMjvCR3mgYjsZz9tgJrXNIlGuFv8HfzktFMzTwukmRxxryaF3y5lCoFjk2mUsGxF4tXN6Pya9uH%2F3Y7g%2BBgAwZ7otB6aAmJvU%2B2n6Fg4ZAxhuMHpHEYPLtPJoKHiSc%2B%2BAzdbjv7TNLtFe8HdH04PzgMsr%2FEfj6FQJrFc0MsBZv2qSp9FafcwutqKXKr0ZVA%2BguOt4IG%2BdmFpD5r3VwTgILLlQKK83%2By8xjx1E5v6%2BkVOAB8syjJfMchqE3mUieY8v9p2akkJcI0ZJUvDpbt%2BTqBWi6%2BZF%2BdMIZRJtyZrJiOh1XaXQD6dKeFIcZFrmrTw9FzPMN%2BAmr0GOqUBqLvXachnZ3s5fxdafpT%2BUjBXwpS9LKWGTIh4XbwPOTNJNpwZetK05veeTbRH7BXiTpw0OrftfH%2FSQxv0RSAYIyZ7JFL8LQy8Ee0XD9guTEl4oX93SY%2B7nAfqf6%2FTnRSu6XtIy2yrdKm50J0VzKwuSvwO%2FtvvB5R95FeyGcQb3Dr4Pz2ttEKRyesQWbS0eHcWUs1cA%2BDs3zkm7O0JUxtPM3KV2hfZ&X-Amz-Signature=60e00fcdfb0d6f9ce37f8cfc1dfb4898f99267c83d583c22536a549683b96e9d&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466W4PU6TCV%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T222150Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGYaCXVzLXdlc3QtMiJHMEUCIQDzlsVdfHX5SFcN%2BUUYK5odWcazQ650ya7uekliHJ%2Bl0AIgdSZNKmGi5KVzlhMEIBXnVaEX4RSUcmEVnoSNTllJseEq%2FwMIfxAAGgw2Mzc0MjMxODM4MDUiDKD3E2ZIMwXuUxYRHircA9SC2Zz3EM6gEUXPtk%2FCZ9CdNQPjynibcguI86o%2BQKT7fJ2VXPZSpbOTG9uVXKqwJa5RmpxJ6mN4k08D%2FhUF3vve9Wwp4pueXS3OSdLqdme9TxZoycvEchZDgSvFudTAZ%2FNY3n72ppq%2BU95loKOmIe0gr7chFehfncN0gQVgDgTCBpdtv%2FjOs6RSwcFldVvAsLiOEyoi9rKU7RHCZJkQPSVRke1g5fRK1Wek84STl5wXU2%2B7bkreUPCUNFMlo3%2BcFjCV5QQeubd1vlFCkbOK%2FCdvPtCm%2FlaYOb%2FaSVuZXaO1ELx5CZfc708psMjvCR3mgYjsZz9tgJrXNIlGuFv8HfzktFMzTwukmRxxryaF3y5lCoFjk2mUsGxF4tXN6Pya9uH%2F3Y7g%2BBgAwZ7otB6aAmJvU%2B2n6Fg4ZAxhuMHpHEYPLtPJoKHiSc%2B%2BAzdbjv7TNLtFe8HdH04PzgMsr%2FEfj6FQJrFc0MsBZv2qSp9FafcwutqKXKr0ZVA%2BguOt4IG%2BdmFpD5r3VwTgILLlQKK83%2By8xjx1E5v6%2BkVOAB8syjJfMchqE3mUieY8v9p2akkJcI0ZJUvDpbt%2BTqBWi6%2BZF%2BdMIZRJtyZrJiOh1XaXQD6dKeFIcZFrmrTw9FzPMN%2BAmr0GOqUBqLvXachnZ3s5fxdafpT%2BUjBXwpS9LKWGTIh4XbwPOTNJNpwZetK05veeTbRH7BXiTpw0OrftfH%2FSQxv0RSAYIyZ7JFL8LQy8Ee0XD9guTEl4oX93SY%2B7nAfqf6%2FTnRSu6XtIy2yrdKm50J0VzKwuSvwO%2FtvvB5R95FeyGcQb3Dr4Pz2ttEKRyesQWbS0eHcWUs1cA%2BDs3zkm7O0JUxtPM3KV2hfZ&X-Amz-Signature=683cf11387a8f187c439d59f6f455a325e4db8ebb04c9c56c62f7593142aa8b1&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466W4PU6TCV%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T222150Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGYaCXVzLXdlc3QtMiJHMEUCIQDzlsVdfHX5SFcN%2BUUYK5odWcazQ650ya7uekliHJ%2Bl0AIgdSZNKmGi5KVzlhMEIBXnVaEX4RSUcmEVnoSNTllJseEq%2FwMIfxAAGgw2Mzc0MjMxODM4MDUiDKD3E2ZIMwXuUxYRHircA9SC2Zz3EM6gEUXPtk%2FCZ9CdNQPjynibcguI86o%2BQKT7fJ2VXPZSpbOTG9uVXKqwJa5RmpxJ6mN4k08D%2FhUF3vve9Wwp4pueXS3OSdLqdme9TxZoycvEchZDgSvFudTAZ%2FNY3n72ppq%2BU95loKOmIe0gr7chFehfncN0gQVgDgTCBpdtv%2FjOs6RSwcFldVvAsLiOEyoi9rKU7RHCZJkQPSVRke1g5fRK1Wek84STl5wXU2%2B7bkreUPCUNFMlo3%2BcFjCV5QQeubd1vlFCkbOK%2FCdvPtCm%2FlaYOb%2FaSVuZXaO1ELx5CZfc708psMjvCR3mgYjsZz9tgJrXNIlGuFv8HfzktFMzTwukmRxxryaF3y5lCoFjk2mUsGxF4tXN6Pya9uH%2F3Y7g%2BBgAwZ7otB6aAmJvU%2B2n6Fg4ZAxhuMHpHEYPLtPJoKHiSc%2B%2BAzdbjv7TNLtFe8HdH04PzgMsr%2FEfj6FQJrFc0MsBZv2qSp9FafcwutqKXKr0ZVA%2BguOt4IG%2BdmFpD5r3VwTgILLlQKK83%2By8xjx1E5v6%2BkVOAB8syjJfMchqE3mUieY8v9p2akkJcI0ZJUvDpbt%2BTqBWi6%2BZF%2BdMIZRJtyZrJiOh1XaXQD6dKeFIcZFrmrTw9FzPMN%2BAmr0GOqUBqLvXachnZ3s5fxdafpT%2BUjBXwpS9LKWGTIh4XbwPOTNJNpwZetK05veeTbRH7BXiTpw0OrftfH%2FSQxv0RSAYIyZ7JFL8LQy8Ee0XD9guTEl4oX93SY%2B7nAfqf6%2FTnRSu6XtIy2yrdKm50J0VzKwuSvwO%2FtvvB5R95FeyGcQb3Dr4Pz2ttEKRyesQWbS0eHcWUs1cA%2BDs3zkm7O0JUxtPM3KV2hfZ&X-Amz-Signature=b87cc2f91af04abffb12b2fb13d185ecf241cce7bc42bbcd8fdebc987d0ee182&X-Amz-SignedHeaders=host&x-id=GetObject)


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

