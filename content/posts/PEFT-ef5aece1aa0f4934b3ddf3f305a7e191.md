---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4665K5ESCU6%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250221T202511Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjELT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCID3g7kPRA4oF4J1Yx6F\
  1ebnlVCvSlEisTn5C%2Ft%2FlsrQXAiEAv5Ca0%2FssHwQ1k7WjkIfsP69KsLhEQSL0uS6%2FkFMA\
  C5MqiAQI3f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMZfv%2BGPUMH\
  XZw5GkCrcA0UZoEvcLZguNwyuMHBocvPt87RMPJ4neNGviYllgMUeEtfeoKG2JvfZSQ%2B%2BkvIc\
  dFL17Q19OQu79RvG%2Bje42Llf2tdSNuZ709sxuTI9i7Z5e7lzmlzgycUftrap%2B0QgaxgEUkCaL\
  R0DHaOGzWwhbij8xaB4oXXFGQo9RvwI%2FdiO0cD2Q%2BDmhBOZTtRNgRC35AlP8K5kqa5dDepVt0\
  dqWJuWdA3sI271l4zva900kRAvEXevEdES1ih6y7wgqhAy3Fk9EtW0LN1sGfBAjzfKttbXt6Xm5nR\
  kTE6o14puWZT7XpanrMZTVeCr%2FKP2rCHTLvRXLd13JKbAmj9xOfC2JJRdRUebMqqUi%2FiLXBE9\
  QSdnepJSLsR2KZIPc9aXKsWgp40LR%2B5nEmyB1TTZyXU%2BHLf3z3LtUYZaXHwQ4xyncorKLJSFB\
  zbeUEBEKXuVClHRl6WLqQMmDVv3Rj6qcL%2FUSCz36AH3LGOchhnyujLnsanGDC9ks2PsyeYH3Zhk\
  Ssob1IVlzCKBrWylLkl3r%2F1ivXE5y7lazRE47xwxxTIuFgj2I5gik8FGu%2B2FyhJpCP%2By%2F\
  J55I7KzP3DIgn0XnQt5lbUW4udd4wYpRl%2FNAT5QRixDfilkgx3zOqnqzu%2FCMM%2B8470GOqUB\
  k02J8nZDzNYdXxa%2F%2F3RcrAuHiGtbO4bEeqmYaoM%2FrrInCeRnXFmC5rYS2cJg9nWU%2BrMTh\
  A2eZlgAxfz4L7eZo0RJHE9topri9PJVCrsufeOHCfhtqsdAdy7brM7Qqtrg5KkUZKQ4OSb931cMVA\
  4vFtz%2FrJ6%2F3bxEeFh6AEiiy4Jdj1MF5OeKacppuvueHXtlv%2Fas7StYxqFFKah8YWBHOk%2F\
  lqbd%2F&X-Amz-Signature=d7b7c97b23cb02a680097feb8b9e8ed7e2d8e66306c96633ec43c\
  6599c13747f&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466TKHLTJXA%2F20250221%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250221T202356Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjELT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIQD5e3TuUPaamkaAclislraXlI3gjGjM83ZDOF0A7d%2FdGwIgMPgVbtP2R%2BxrJItrck\
        eVznUCxR71wcChhxi8YIWmXPoqiAQI3f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2M\
        zc0MjMxODM4MDUiDMUSH2pWQxDNvZoSqyrcAy0usEvCF5hlxvZEse7AhtwjrsW0PTttCgap\
        8B0ySycQM8nfDYkYjAlAjOh8eeryBuli58VDguxEPVrmW7GYXDW61iUEI6Tkc2UcIQeWddp\
        Ml7LJsl5%2BkrJxykSQORFUK856PYSxb%2B6ETwAFmIgT4l6jP9KVp7SOh%2BzyRJT5dLio\
        L%2FKGv6atO7MOm%2Ft3C1nL3bpJs8tcqytsrI0GCO%2BTJEfgc%2BqFL3HsSLJ72Xcob0Z\
        y83%2FcW%2B8JObYKWZBIgdst9JlRLDXj1Rv2alh0zeDM2M5oIabZ2OLXpdfJzkeKnR%2FR\
        r3KjkRFAh2oO0k6rcDtAtVqK1kAVGdDTBxCiLlcp8pEbSDTlZYaoErfa9bfiQRb2p0RjlAC\
        8AcTwf85HBEPrr7d0kk%2FaFQPwDc1P9%2BSXHpcbT0RwuI0jWwjuevIrN%2Bhq%2F8CAAZ\
        LJlmVCpGsdIyyKs4AgdzgVEAOwtjCnebTBKB%2BwuGRpEfpZlB4NoN2IyxHc0AQhGQ8xUnO\
        jwsIyYzHUHdrFpmz%2FWsGwxqJwdM89rJHpzREf03VmeXnFoz2PFanNCxm%2F5t1S6lNJ3Z\
        4ln2nRP0FZ41PC5L4plXyaG04C%2BSI9QdUyOJM1pYa8mzs79UXGss8sLqVv2fPnkadJMNm\
        8470GOqUBDzQKANgo1Nb%2F%2Bfgp2g0hqoRt1R%2BN2cTqBej1O%2FhYSm%2FdVSqtMD7R\
        4%2BJjK5gfasAXniORYA1ae%2BOCa7i3T%2B61O8MVCrOI1TL%2BjZ7mIYNvbm2jpDWo8YW\
        hFR0VmH76v4cB8auyV2O7EqTXe5SnvdL7Qo%2B5AgAtMPWRehNh9lzTXMu%2Fr4%2Ft%2FS\
        evIdChuwJRRBd3SwdTe4cwoQXYwAmox0HObKROW9XP&X-Amz-Signature=5f604d706800\
        23434f92cb5c2283f0921263e68fc4e21a84232b7fe622fe6aa2&X-Amz-SignedHeader\
        s=host&x-id=GetObject"
      expiry_time: "2025-02-21T21:23:56.818Z"
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
UPDATE_TIME: "2025-02-21T20:25:15.821Z"
EXPIRY_TIME: "2025-02-21T21:25:09.700Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SDYXXOFC%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T202510Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBIFyxvHIm2h7DUr61BFJjkpThJhTPC5nYC6vLcu0DYTAiEAiLy%2BUPCFSyxaqrq2fpjO%2BzVD42xrB2D5gTGTJz9HVZMqiAQI3f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDW1uR1JSxDOV9qEZCrcA%2FzGBi2D%2B0TTIm6PA4CsMz33VVC15EmDKym6GOGF4nODfgQL8fiXCquRMHRdAccokLADmeIMK2uhX0F41JtUqtiPmzpxBP8AxQStpjEOuZ4zaffVaeell7OfeTSyeurPuTkapTbRO7W5zmL0mAxANoavqtWc78yfy7ARpYkFzTirBiFMFLgVL%2Bl2TVGXjBSoRy2mmYrbT7Lim0xkcm00Ny3PHW7R8oMNBvFpmWx88p0G1PQrCABCEscyqTpAA08mcFDt412zmyIeP7PNqVa6D0OIvwrNZnFhK3uK1f9ju%2B6kZ1cc%2BFmHgBQNZ42FDibKPP1fD338Yw2psBrqHkD0%2FEnUlPEghnL%2FgdwX4TANozaZAC74Ym9RfMmvqg2xAB%2FNGhsotXDN%2B%2BHVVnljKw%2BEwvG5wRCWZbCtFLZe1MDBcT6vVRysKkAtOJ0v1Tu9EYt1jLkpMIqaLAI%2B188O4l1uUB51HoT%2Ffwh5ZGcbmoOJgM3%2FzjE0AZaCme4G6rvR%2BiXlx681U%2B3Ncn2R4aDnioV1lFboF%2BaVU0B%2BSnOrE1bwClJFc7iS7QAUDiMYU1PSZ9fRARhNGiYOlJHl8slJGqPbPlsLhqdPP987c%2FVAG%2Bcv0uY4GLbJ%2Fn8QOvcLv%2BbjMP%2B7470GOqUBFZPYlixiVju3YUL87uksaAJPfBw2qvQPmknBWe5%2FiOY37A9MgSlOk8BGpQPH5WA5rrMVqQnWxyP7%2FuTKNGMUZoO3jIwEekvpe87X7Yd0Z9runKtDtMZFlcKk84KPy2DMNSR1KUloKY%2Fb354vTQ%2F%2B47bqVk1H3Wr4Hy%2FT20IoLfQkWb5E1CgIM5IRH4skmBfotgHUK4j7sfpDG%2BMNA%2BGiL0hbYEgS&X-Amz-Signature=65b3b9a21b5d28297395683349ad1667f16e899805e1168996b2a4af0f47f06d&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SDYXXOFC%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T202510Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBIFyxvHIm2h7DUr61BFJjkpThJhTPC5nYC6vLcu0DYTAiEAiLy%2BUPCFSyxaqrq2fpjO%2BzVD42xrB2D5gTGTJz9HVZMqiAQI3f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDW1uR1JSxDOV9qEZCrcA%2FzGBi2D%2B0TTIm6PA4CsMz33VVC15EmDKym6GOGF4nODfgQL8fiXCquRMHRdAccokLADmeIMK2uhX0F41JtUqtiPmzpxBP8AxQStpjEOuZ4zaffVaeell7OfeTSyeurPuTkapTbRO7W5zmL0mAxANoavqtWc78yfy7ARpYkFzTirBiFMFLgVL%2Bl2TVGXjBSoRy2mmYrbT7Lim0xkcm00Ny3PHW7R8oMNBvFpmWx88p0G1PQrCABCEscyqTpAA08mcFDt412zmyIeP7PNqVa6D0OIvwrNZnFhK3uK1f9ju%2B6kZ1cc%2BFmHgBQNZ42FDibKPP1fD338Yw2psBrqHkD0%2FEnUlPEghnL%2FgdwX4TANozaZAC74Ym9RfMmvqg2xAB%2FNGhsotXDN%2B%2BHVVnljKw%2BEwvG5wRCWZbCtFLZe1MDBcT6vVRysKkAtOJ0v1Tu9EYt1jLkpMIqaLAI%2B188O4l1uUB51HoT%2Ffwh5ZGcbmoOJgM3%2FzjE0AZaCme4G6rvR%2BiXlx681U%2B3Ncn2R4aDnioV1lFboF%2BaVU0B%2BSnOrE1bwClJFc7iS7QAUDiMYU1PSZ9fRARhNGiYOlJHl8slJGqPbPlsLhqdPP987c%2FVAG%2Bcv0uY4GLbJ%2Fn8QOvcLv%2BbjMP%2B7470GOqUBFZPYlixiVju3YUL87uksaAJPfBw2qvQPmknBWe5%2FiOY37A9MgSlOk8BGpQPH5WA5rrMVqQnWxyP7%2FuTKNGMUZoO3jIwEekvpe87X7Yd0Z9runKtDtMZFlcKk84KPy2DMNSR1KUloKY%2Fb354vTQ%2F%2B47bqVk1H3Wr4Hy%2FT20IoLfQkWb5E1CgIM5IRH4skmBfotgHUK4j7sfpDG%2BMNA%2BGiL0hbYEgS&X-Amz-Signature=f8d3adf5dc3bcc690fe1a573699fd8b63412e7b18391cf984a9176cd3de557d1&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SDYXXOFC%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T202510Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBIFyxvHIm2h7DUr61BFJjkpThJhTPC5nYC6vLcu0DYTAiEAiLy%2BUPCFSyxaqrq2fpjO%2BzVD42xrB2D5gTGTJz9HVZMqiAQI3f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDW1uR1JSxDOV9qEZCrcA%2FzGBi2D%2B0TTIm6PA4CsMz33VVC15EmDKym6GOGF4nODfgQL8fiXCquRMHRdAccokLADmeIMK2uhX0F41JtUqtiPmzpxBP8AxQStpjEOuZ4zaffVaeell7OfeTSyeurPuTkapTbRO7W5zmL0mAxANoavqtWc78yfy7ARpYkFzTirBiFMFLgVL%2Bl2TVGXjBSoRy2mmYrbT7Lim0xkcm00Ny3PHW7R8oMNBvFpmWx88p0G1PQrCABCEscyqTpAA08mcFDt412zmyIeP7PNqVa6D0OIvwrNZnFhK3uK1f9ju%2B6kZ1cc%2BFmHgBQNZ42FDibKPP1fD338Yw2psBrqHkD0%2FEnUlPEghnL%2FgdwX4TANozaZAC74Ym9RfMmvqg2xAB%2FNGhsotXDN%2B%2BHVVnljKw%2BEwvG5wRCWZbCtFLZe1MDBcT6vVRysKkAtOJ0v1Tu9EYt1jLkpMIqaLAI%2B188O4l1uUB51HoT%2Ffwh5ZGcbmoOJgM3%2FzjE0AZaCme4G6rvR%2BiXlx681U%2B3Ncn2R4aDnioV1lFboF%2BaVU0B%2BSnOrE1bwClJFc7iS7QAUDiMYU1PSZ9fRARhNGiYOlJHl8slJGqPbPlsLhqdPP987c%2FVAG%2Bcv0uY4GLbJ%2Fn8QOvcLv%2BbjMP%2B7470GOqUBFZPYlixiVju3YUL87uksaAJPfBw2qvQPmknBWe5%2FiOY37A9MgSlOk8BGpQPH5WA5rrMVqQnWxyP7%2FuTKNGMUZoO3jIwEekvpe87X7Yd0Z9runKtDtMZFlcKk84KPy2DMNSR1KUloKY%2Fb354vTQ%2F%2B47bqVk1H3Wr4Hy%2FT20IoLfQkWb5E1CgIM5IRH4skmBfotgHUK4j7sfpDG%2BMNA%2BGiL0hbYEgS&X-Amz-Signature=2aaffedb25a6decc2e2cd80f25737f61efcb57ebc96d94357ff666c9b0b0d904&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SDYXXOFC%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T202510Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBIFyxvHIm2h7DUr61BFJjkpThJhTPC5nYC6vLcu0DYTAiEAiLy%2BUPCFSyxaqrq2fpjO%2BzVD42xrB2D5gTGTJz9HVZMqiAQI3f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDW1uR1JSxDOV9qEZCrcA%2FzGBi2D%2B0TTIm6PA4CsMz33VVC15EmDKym6GOGF4nODfgQL8fiXCquRMHRdAccokLADmeIMK2uhX0F41JtUqtiPmzpxBP8AxQStpjEOuZ4zaffVaeell7OfeTSyeurPuTkapTbRO7W5zmL0mAxANoavqtWc78yfy7ARpYkFzTirBiFMFLgVL%2Bl2TVGXjBSoRy2mmYrbT7Lim0xkcm00Ny3PHW7R8oMNBvFpmWx88p0G1PQrCABCEscyqTpAA08mcFDt412zmyIeP7PNqVa6D0OIvwrNZnFhK3uK1f9ju%2B6kZ1cc%2BFmHgBQNZ42FDibKPP1fD338Yw2psBrqHkD0%2FEnUlPEghnL%2FgdwX4TANozaZAC74Ym9RfMmvqg2xAB%2FNGhsotXDN%2B%2BHVVnljKw%2BEwvG5wRCWZbCtFLZe1MDBcT6vVRysKkAtOJ0v1Tu9EYt1jLkpMIqaLAI%2B188O4l1uUB51HoT%2Ffwh5ZGcbmoOJgM3%2FzjE0AZaCme4G6rvR%2BiXlx681U%2B3Ncn2R4aDnioV1lFboF%2BaVU0B%2BSnOrE1bwClJFc7iS7QAUDiMYU1PSZ9fRARhNGiYOlJHl8slJGqPbPlsLhqdPP987c%2FVAG%2Bcv0uY4GLbJ%2Fn8QOvcLv%2BbjMP%2B7470GOqUBFZPYlixiVju3YUL87uksaAJPfBw2qvQPmknBWe5%2FiOY37A9MgSlOk8BGpQPH5WA5rrMVqQnWxyP7%2FuTKNGMUZoO3jIwEekvpe87X7Yd0Z9runKtDtMZFlcKk84KPy2DMNSR1KUloKY%2Fb354vTQ%2F%2B47bqVk1H3Wr4Hy%2FT20IoLfQkWb5E1CgIM5IRH4skmBfotgHUK4j7sfpDG%2BMNA%2BGiL0hbYEgS&X-Amz-Signature=c4ea7cf79b55aaad3abef123c99d59ec0b9d258737bab1d1fa0c867b7d6d1b18&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SDYXXOFC%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T202510Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBIFyxvHIm2h7DUr61BFJjkpThJhTPC5nYC6vLcu0DYTAiEAiLy%2BUPCFSyxaqrq2fpjO%2BzVD42xrB2D5gTGTJz9HVZMqiAQI3f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDW1uR1JSxDOV9qEZCrcA%2FzGBi2D%2B0TTIm6PA4CsMz33VVC15EmDKym6GOGF4nODfgQL8fiXCquRMHRdAccokLADmeIMK2uhX0F41JtUqtiPmzpxBP8AxQStpjEOuZ4zaffVaeell7OfeTSyeurPuTkapTbRO7W5zmL0mAxANoavqtWc78yfy7ARpYkFzTirBiFMFLgVL%2Bl2TVGXjBSoRy2mmYrbT7Lim0xkcm00Ny3PHW7R8oMNBvFpmWx88p0G1PQrCABCEscyqTpAA08mcFDt412zmyIeP7PNqVa6D0OIvwrNZnFhK3uK1f9ju%2B6kZ1cc%2BFmHgBQNZ42FDibKPP1fD338Yw2psBrqHkD0%2FEnUlPEghnL%2FgdwX4TANozaZAC74Ym9RfMmvqg2xAB%2FNGhsotXDN%2B%2BHVVnljKw%2BEwvG5wRCWZbCtFLZe1MDBcT6vVRysKkAtOJ0v1Tu9EYt1jLkpMIqaLAI%2B188O4l1uUB51HoT%2Ffwh5ZGcbmoOJgM3%2FzjE0AZaCme4G6rvR%2BiXlx681U%2B3Ncn2R4aDnioV1lFboF%2BaVU0B%2BSnOrE1bwClJFc7iS7QAUDiMYU1PSZ9fRARhNGiYOlJHl8slJGqPbPlsLhqdPP987c%2FVAG%2Bcv0uY4GLbJ%2Fn8QOvcLv%2BbjMP%2B7470GOqUBFZPYlixiVju3YUL87uksaAJPfBw2qvQPmknBWe5%2FiOY37A9MgSlOk8BGpQPH5WA5rrMVqQnWxyP7%2FuTKNGMUZoO3jIwEekvpe87X7Yd0Z9runKtDtMZFlcKk84KPy2DMNSR1KUloKY%2Fb354vTQ%2F%2B47bqVk1H3Wr4Hy%2FT20IoLfQkWb5E1CgIM5IRH4skmBfotgHUK4j7sfpDG%2BMNA%2BGiL0hbYEgS&X-Amz-Signature=927b0f7d8f6f4b1cbb4cc22161bc1ec3e803901d4810f539a38a26bc52caed20&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RSWSB24M%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T202510Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD6FfhB5RVZdiqjlHMA6Zr5Yhdmy9FBrivrsbh5ZezQbAIhAL2HlessU8k319kFtE14UDsAA2Qv1CN6DrNx2Lj3xLMGKogECN3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgziKV4ki31wxIFvvjoq3ANSH1qdeeYbYJ5%2FyQrN%2BpHEhx6eNMFve%2Be12buuaXdDq6afcb6nf3%2BCXfSNZ%2F63IKDp6EK%2BTV6EABjnl6KiKHKTXJsDk9Pr6l6iAZ8VEmctCJcslXqVZNzulCZBlJ2hFA5SzLRWtvDfQyFgLdovNADBUZg7jZF6ESsgucbOmnY7w5Irama8R0Eu41AfxTQN4UyLBjiWQfRU%2FSlG53dH5niw4wrrQsnbpiQ5cgLjF4ZqYb9wF1R1uqlBaTU5Y0CygE3ebdNvWJ5cXissluJwnaHcKbiBIaQPweL%2Flu62e%2BHXaGfkeXvEf5SV8AvXY%2BCoFQWTmnBRlPeHHvYPUlx3c6WhE7ywcJYowZIggSuvfkg%2BwSwIDNeZrVoJ4RvemzLqnqJ%2B2SzmSe4%2FO5OgkeFUUNZEnoIi4By2o%2FD1AWUYm6Cc1%2BLuFqWaSPPua3Oe8Dhxg%2BY5TGNA2qOPz%2Bbc9hPx6JVwI3qdWwql3P1t0o5P%2FYdHWqtnp4WbHKy%2FTx6CoYd4d1hA%2FLb8KE5lwVZsjfVq7w9WeCR2MTIETXaM50Nt9WAo5YCPNMrv1D9X0gobOHjCqr%2BPtR1oM5aWg7sQ9jXsGGqboLtmp6MAr7jSRtcAqnyIwoEqEImYLUrdBUzkVTDJu%2BO9BjqkAdkh6QuPAxLf58o%2Fsk9CjIxI%2FA0F9kxmOzLt5VSB0t4J3zrztIZT3ognYfQGABWGEQ6gRH%2BMiSJ1LEgh4JKpMu5kCoHpxbhqouM6DdhX91B1%2Bjj7EgWLIX7KI0DdHCxksmWCXfu%2FNB0dtaaKL7qcZ5YglpV2jdDt2FG6WBybd6rRFLus%2FeHxl87u%2FO6cEJemIp4o6wF%2Bac5JEnuLInCGCFEtIO5l&X-Amz-Signature=25b08f92ecfcf16e704b56a8d409056a3619a7b6478fcef4e96bbd416bb7cdc2&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RICWL6RW%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T202511Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDg%2FZW7b7T2MBbJIarzI1aTodclHD%2FCCw6P%2FOQHtz%2Bc%2BQIgFgyMRbwSXPeC9lutbdEj942SUFCtWIhxXTIbwPpL91oqiAQI3f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPApUlF7qzNqoZ3AyircAxrGNUyK469FuK7hOBH6F9UIVea%2BTIbuQC7L0nsjxwrBKawrNrmX1i5PM3J%2BEMnt9gmN0hbP%2BmV9Mak6s%2FKAXOt32QpVt%2Fsko2PTLfFvY2sb9Ui%2F41VUHS6B8YHBfDRc2PBIYjW%2BRkn1VIBI1AaOvwDuZhUBORJaO26UDJIURKP%2Fu46mtYb%2B1lniQ%2Bpas8Po4bABUzn0%2FG%2F0cneZ4OfJAHlh3LUha233dCsK15ILyF0H9X%2BNIeXCWZVYpVTwBvDy5PMFbwkSp5tvqI4skO3YKH606BgS7Wgs4sFDCaWh3i15tm24YdG0SRM6is2CFBcZ8lczJ0cJ9Lh3S0f8xtPGeGUucVWecCSIngw3gaFfGllP7uflidJ3CGeyqDhZ1ftckVnwOUHlyrRC6mKx2gXg%2BLTKoI%2FRfqxgZAviHI0OwA%2FM5d6Dp05iz2M2sVVLds5z9R1ENFlMDVqGwymoPTYM5UGMQypZM7j6bPzvGi59IMFwTuSGvg7%2FyClD1qm1g%2BAozTg3lSESkZxnmAqnVTerYk01rxAtcrXU3q9TDdOGMVJ7XWqRxy6kptmHZYDwintUd4zrvEo7l3Q9KTFyQzHCP3U20NXch7P0G5lRP1mN%2BSGAeGmp1l9362%2FaHomaML27470GOqUBciiaKrJOiGLnZ1g31Q2qgzGgKZKZC7U580P6QaFtfpJk%2F%2BbhqHruBBVFSx7vvt8ZwF4FiWbtS1Be1B99c%2BtBkztX%2FwbsmLgxB57jE9vHkh30h9bjkSOainjspawffRYkW5yZ60XbxXAVPR4IUkEzlXtk5y0f1C%2FoYKWb6oWoH585SXPoVJdqBGNkjWDuLXZInAXVIpy1niI03xUcLCoUfkBoGeVr&X-Amz-Signature=6b3dbf878a48ff2b3dc8804fd27729fb718e79098905a5af938a1fd8a85a1057&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SDYXXOFC%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T202510Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBIFyxvHIm2h7DUr61BFJjkpThJhTPC5nYC6vLcu0DYTAiEAiLy%2BUPCFSyxaqrq2fpjO%2BzVD42xrB2D5gTGTJz9HVZMqiAQI3f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDW1uR1JSxDOV9qEZCrcA%2FzGBi2D%2B0TTIm6PA4CsMz33VVC15EmDKym6GOGF4nODfgQL8fiXCquRMHRdAccokLADmeIMK2uhX0F41JtUqtiPmzpxBP8AxQStpjEOuZ4zaffVaeell7OfeTSyeurPuTkapTbRO7W5zmL0mAxANoavqtWc78yfy7ARpYkFzTirBiFMFLgVL%2Bl2TVGXjBSoRy2mmYrbT7Lim0xkcm00Ny3PHW7R8oMNBvFpmWx88p0G1PQrCABCEscyqTpAA08mcFDt412zmyIeP7PNqVa6D0OIvwrNZnFhK3uK1f9ju%2B6kZ1cc%2BFmHgBQNZ42FDibKPP1fD338Yw2psBrqHkD0%2FEnUlPEghnL%2FgdwX4TANozaZAC74Ym9RfMmvqg2xAB%2FNGhsotXDN%2B%2BHVVnljKw%2BEwvG5wRCWZbCtFLZe1MDBcT6vVRysKkAtOJ0v1Tu9EYt1jLkpMIqaLAI%2B188O4l1uUB51HoT%2Ffwh5ZGcbmoOJgM3%2FzjE0AZaCme4G6rvR%2BiXlx681U%2B3Ncn2R4aDnioV1lFboF%2BaVU0B%2BSnOrE1bwClJFc7iS7QAUDiMYU1PSZ9fRARhNGiYOlJHl8slJGqPbPlsLhqdPP987c%2FVAG%2Bcv0uY4GLbJ%2Fn8QOvcLv%2BbjMP%2B7470GOqUBFZPYlixiVju3YUL87uksaAJPfBw2qvQPmknBWe5%2FiOY37A9MgSlOk8BGpQPH5WA5rrMVqQnWxyP7%2FuTKNGMUZoO3jIwEekvpe87X7Yd0Z9runKtDtMZFlcKk84KPy2DMNSR1KUloKY%2Fb354vTQ%2F%2B47bqVk1H3Wr4Hy%2FT20IoLfQkWb5E1CgIM5IRH4skmBfotgHUK4j7sfpDG%2BMNA%2BGiL0hbYEgS&X-Amz-Signature=9014edc575a9d7001dfd80f54feed0676fa31870bbf1754c51a7cc005fbccafa&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SDYXXOFC%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T202510Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBIFyxvHIm2h7DUr61BFJjkpThJhTPC5nYC6vLcu0DYTAiEAiLy%2BUPCFSyxaqrq2fpjO%2BzVD42xrB2D5gTGTJz9HVZMqiAQI3f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDW1uR1JSxDOV9qEZCrcA%2FzGBi2D%2B0TTIm6PA4CsMz33VVC15EmDKym6GOGF4nODfgQL8fiXCquRMHRdAccokLADmeIMK2uhX0F41JtUqtiPmzpxBP8AxQStpjEOuZ4zaffVaeell7OfeTSyeurPuTkapTbRO7W5zmL0mAxANoavqtWc78yfy7ARpYkFzTirBiFMFLgVL%2Bl2TVGXjBSoRy2mmYrbT7Lim0xkcm00Ny3PHW7R8oMNBvFpmWx88p0G1PQrCABCEscyqTpAA08mcFDt412zmyIeP7PNqVa6D0OIvwrNZnFhK3uK1f9ju%2B6kZ1cc%2BFmHgBQNZ42FDibKPP1fD338Yw2psBrqHkD0%2FEnUlPEghnL%2FgdwX4TANozaZAC74Ym9RfMmvqg2xAB%2FNGhsotXDN%2B%2BHVVnljKw%2BEwvG5wRCWZbCtFLZe1MDBcT6vVRysKkAtOJ0v1Tu9EYt1jLkpMIqaLAI%2B188O4l1uUB51HoT%2Ffwh5ZGcbmoOJgM3%2FzjE0AZaCme4G6rvR%2BiXlx681U%2B3Ncn2R4aDnioV1lFboF%2BaVU0B%2BSnOrE1bwClJFc7iS7QAUDiMYU1PSZ9fRARhNGiYOlJHl8slJGqPbPlsLhqdPP987c%2FVAG%2Bcv0uY4GLbJ%2Fn8QOvcLv%2BbjMP%2B7470GOqUBFZPYlixiVju3YUL87uksaAJPfBw2qvQPmknBWe5%2FiOY37A9MgSlOk8BGpQPH5WA5rrMVqQnWxyP7%2FuTKNGMUZoO3jIwEekvpe87X7Yd0Z9runKtDtMZFlcKk84KPy2DMNSR1KUloKY%2Fb354vTQ%2F%2B47bqVk1H3Wr4Hy%2FT20IoLfQkWb5E1CgIM5IRH4skmBfotgHUK4j7sfpDG%2BMNA%2BGiL0hbYEgS&X-Amz-Signature=37a77d22d71da9ffcc6145a91ef8409a2b8d860ed17affd9dcc999a7d35ad27f&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SDYXXOFC%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T202510Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBIFyxvHIm2h7DUr61BFJjkpThJhTPC5nYC6vLcu0DYTAiEAiLy%2BUPCFSyxaqrq2fpjO%2BzVD42xrB2D5gTGTJz9HVZMqiAQI3f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDW1uR1JSxDOV9qEZCrcA%2FzGBi2D%2B0TTIm6PA4CsMz33VVC15EmDKym6GOGF4nODfgQL8fiXCquRMHRdAccokLADmeIMK2uhX0F41JtUqtiPmzpxBP8AxQStpjEOuZ4zaffVaeell7OfeTSyeurPuTkapTbRO7W5zmL0mAxANoavqtWc78yfy7ARpYkFzTirBiFMFLgVL%2Bl2TVGXjBSoRy2mmYrbT7Lim0xkcm00Ny3PHW7R8oMNBvFpmWx88p0G1PQrCABCEscyqTpAA08mcFDt412zmyIeP7PNqVa6D0OIvwrNZnFhK3uK1f9ju%2B6kZ1cc%2BFmHgBQNZ42FDibKPP1fD338Yw2psBrqHkD0%2FEnUlPEghnL%2FgdwX4TANozaZAC74Ym9RfMmvqg2xAB%2FNGhsotXDN%2B%2BHVVnljKw%2BEwvG5wRCWZbCtFLZe1MDBcT6vVRysKkAtOJ0v1Tu9EYt1jLkpMIqaLAI%2B188O4l1uUB51HoT%2Ffwh5ZGcbmoOJgM3%2FzjE0AZaCme4G6rvR%2BiXlx681U%2B3Ncn2R4aDnioV1lFboF%2BaVU0B%2BSnOrE1bwClJFc7iS7QAUDiMYU1PSZ9fRARhNGiYOlJHl8slJGqPbPlsLhqdPP987c%2FVAG%2Bcv0uY4GLbJ%2Fn8QOvcLv%2BbjMP%2B7470GOqUBFZPYlixiVju3YUL87uksaAJPfBw2qvQPmknBWe5%2FiOY37A9MgSlOk8BGpQPH5WA5rrMVqQnWxyP7%2FuTKNGMUZoO3jIwEekvpe87X7Yd0Z9runKtDtMZFlcKk84KPy2DMNSR1KUloKY%2Fb354vTQ%2F%2B47bqVk1H3Wr4Hy%2FT20IoLfQkWb5E1CgIM5IRH4skmBfotgHUK4j7sfpDG%2BMNA%2BGiL0hbYEgS&X-Amz-Signature=23e1e7809b626616d682b9ac1c87c8e2eef1ffe5ba580393bb98f64743ce894e&X-Amz-SignedHeaders=host&x-id=GetObject)


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

