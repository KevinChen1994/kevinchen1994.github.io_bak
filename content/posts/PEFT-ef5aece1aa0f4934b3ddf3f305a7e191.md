---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466SNY6FL6Y%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250221T172124Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjELH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIEIS1tKHN2MSY8dkkpH\
  zanY4amZA7s8B0t5AW%2BxiMjuIAiEA2%2FjPnzM5mP5XCL4hzrWilDl1Py%2BlM%2FtD4Sz7RIdV\
  lLkqiAQI2v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKC0dNBdkCmVK\
  ZuF7CrcA%2BbJpwM3ABMuA7QIJiDSyDd6RSW50OsqmMal7iEtbTpEBxdLfQ8sXN6k5LpwqGeoXqtz\
  qr26sdoe53fdD7ziremgMuk3ih6H4%2Bda98ro1Z9%2FGJIpQt3rhv2WmFoHqtw2EXj9Xt17LGsWV\
  peYeEjof1XBhYmkIm%2BkI7wEgKX3dS9j3612wQfK3jU5kMy3ePx6Ysr7j5ZtMHMmqWZEFy2e2BHW\
  kxGzqbnYaB26GGl0N5UVnyVMV0%2F11NaE1MxbkKFDyXdwSXnvkBmMppAJfqnfZ2Mqi5Ong6rNWcj\
  Fs5VWePT6r%2B37sW%2FoUTPFTEMlMbaqQ5SSa7G2ltfRbngDR%2BpqIyaYP5KdQ%2FJqhmuZlvXW\
  7lteLa9MR4zWqpJsj2u9b4jVcpGPlOcAyv8%2Fz%2FddQPeAjFjtLD72pUuN3Pq%2Fq0BSCghZHiJ\
  6qnZIuJtUN8TXK8g%2F%2Bf%2F2xCHsn%2BaZJsBhSk%2FwezoZIfJ7XjStK08CLzFeL2fRdZrhce\
  u1mkPcQAE6AInZZGVORpiBE6RMey5TdzbHvAAWhruTbo%2BDiIA%2BVFFnaJPJkjv2oQMc%2BgFjr\
  GKCUn3alkYnlh9h5YlCUeBYQR%2Fz1sH2OcYBBQ%2BvW9T%2FSx%2BE9FFWMUBT4z%2BpeljDxfdw\
  MLjj4r0GOqUBIyn1ttLULFHVoGTGlUg9WVo9eam58sBOKBdoFr2Z1z2jMZ4dEHTalMe2DAU8%2F5D\
  wU1kPitZexk4GoJJwVEhS%2FAT1cDVb22APGJhOnMG1hpKT%2BEsU%2BBIkfZd92tW9GIEsv87agG\
  r3pJFWGm7rSz%2F7Pn1T5CHaDeXg%2Bj95BgI0PNbP%2F4S95inZvw3boLYB0R1%2BKgFjw3%2FQY\
  WGfDheSt4dqwHiA1H%2Fz&X-Amz-Signature=31985e0f1abb612ececd28bd6b7db2969df35fa\
  49e39cce2848d5545e8a00e9e&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466UBACU7KI%2F20250221%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250221T171914Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjELH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIQDpHJ8QPjY9pKgHV9U%2F1UaHmfbJYMCjodjeW7%2B5attZ7QIgLj9bnJixX34NFzj5fp\
        Y1iHpTPGcqi%2B2qoFM6YTHCGy0qiAQI2v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw\
        2Mzc0MjMxODM4MDUiDJbSQlY6CxFyn5I03CrcAwgC8r1fk1rU282b%2BtfEjoyaFIXUhHFm\
        dw9MPK2HU870j%2FVeoEjeybQBnXdNycN9xahJ0NUq86Bfn%2BUsHmBCHMzGMSsiYf%2Bmn\
        pK0jY5i4qNyMLSlncRIFcWePZWIFBoyVEPS3YvVcV5wog2O6K7726yVR01MGhNt91pedsC0\
        dJFyWvrDdB%2FYuEQ5mkvl3alEmKuldIqbwi8bZqUe92r4MAJzEW9fcLtEy7bo0hzoOGVsF\
        oVHLU57PAG%2BbJNhVNq%2Fz0i7fJGh11Mc8HDKiKT4tWBWB7VVp3Hhj774d7tSwcqzxUIE\
        p0fkN8LBDLH2k7%2FspdL1GK4jc9LKkocU6TI1Cp95Qm72lRiXxi7EoW6ahbc8Z74GuQN%2\
        F%2Bd6Is0R3xIq85YkQgJRXF2C7kjzJC3rXt5q8d%2FghyA0Rgp6UJKgJNyLJvQAAGzcSXd\
        uxgtPPx3Y1CaV7Wiymg4Jv3R7cs11vCCO1hQ7WnuQOamHGHW3KW%2FCtOqgVXfe8XM8E8tj\
        lMJBBvpNYY%2BWhNVEJETdQqqCVnGdt0KNA9%2FX6it0tZJY4f9efwbU6zRb11raJcd02KH\
        5csfk3Esx%2FZGc54ALcnQezhweALe8HHGu5yOQJLgIxQ7m1nXY%2FXRFA%2FzgwE8lzMOv\
        k4r0GOqUBE5jiqZqLMXyULWPhsCir9C3Cbvxfvpx%2FN%2FFTS4hf0uAt%2BlStI%2FEo7r\
        6ehKk0KFysZjWb5wTb5kXB6sNvqjeUL0%2BgN1mYbAxofNJvK37jVgfjMMUho1uJLspNcz1\
        PR2lgI73Ts5K4%2BcdU98mqX9nqS4UGCSYGJuG9PiENDFxnTbihuIZhd9YNt6zw92ytil8v\
        AaY35tNwXA8bfrQkRvhcs89%2FzhEQ&X-Amz-Signature=baeba75862a60675f2d6ee0e\
        56dc64fa02595ea764ccb66b17697675247fce89&X-Amz-SignedHeaders=host&x-id=\
        GetObject"
      expiry_time: "2025-02-21T18:19:14.657Z"
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
UPDATE_TIME: "2025-02-21T17:21:29.570Z"
EXPIRY_TIME: "2025-02-21T18:21:17.459Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TTPY5662%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T172118Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCrgP9N3hGLpWLWRoqFF1s591%2FM44hRbeDetWid7xs9qAIgeeXpP%2FejoSi2BxNP2giGv4TLXXlRGmyU2ysheFHkcyQqiAQI2v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNm5L3TpdWG0RC7A%2FyrcA8XYzvnrsvzLYY2ENaXI8Ew%2BSnyrV2W5Q5h%2FgVteQzfBdaTlqaw3NVX0GWO74VK6fkZwzuVrjyrtmCpwKjt%2FCVv7kPszDxrVyj9LDGg3s0ReCNBmN13j4aQgYJjTf1mm4S7IwWOKGZ819nCieYWSpvV5n%2Bwn5DZUCDp4le3sw%2BLjnvsFhS%2B2JI17heDES0xMLOmm5VvQWJWYiXT4ZTgh0%2FLRuKOnt7Qa3TSyqlsV7i8I%2FROlB6Z%2BoWjZ0xSt3fz2McCiB1ZqkUsCB7KaHuwapeW3FQv4tn%2Bin8PQ29WTqC9GjSa%2FRNeCfvhpF%2FM03Y4SI%2BacskSC2dheE70Zkvr6D5TYrLDJIBrnGP4P7l5LmNULDSiZyB5s0MqfTRJ2CP8YJAKJRJh7MJM%2BvEXKoH7Gw5ACK3OnITHZE0ue4sTXfvAD67pTAWY6wzUUIZ8jo%2FADortH5XEwPS7MhL37T9ANA%2FmHIvr4bV3ahd2oAhLJnx7T8%2BJNL5huv0lmWDkXEn3JBA1Fvvcy3GIKHYzY0sSY10eSrELJmq9kfRX3uz4nMKyZOjlHmc3E%2Fdr%2BulIn%2B69dQq%2Fm%2B%2BHC5ar%2FFUmR09oC5r5Sy3MHX2hny6ZO40K%2FF6Yl0oMGlMAgNdK0942WMLHk4r0GOqUBFPnm6%2F5khAMEmRsQ03OYRwfKD8buSalTMU%2FDBH%2BS9OTfh4qaa9ZPaEdtWYx9npc%2B1wnNZ6RTTWWYM6YhC56iBF82krvvMsKXZJ6OUpiXZjZcGZ%2FxNLGBE%2Bej8r%2FVPY1HGJ6IhaVGEbBUffoZLvYcuSnoaOJgz5P6XlfC7myKlHV%2Bk4qSen%2FxCIgc%2F0HGjicE0wW%2Bl1llz2T1iMSbW375O3Eh93Ov&X-Amz-Signature=78a3329403455354dc64b0285ebb66788dff796887425b7126951715090330ff&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TTPY5662%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T172118Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCrgP9N3hGLpWLWRoqFF1s591%2FM44hRbeDetWid7xs9qAIgeeXpP%2FejoSi2BxNP2giGv4TLXXlRGmyU2ysheFHkcyQqiAQI2v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNm5L3TpdWG0RC7A%2FyrcA8XYzvnrsvzLYY2ENaXI8Ew%2BSnyrV2W5Q5h%2FgVteQzfBdaTlqaw3NVX0GWO74VK6fkZwzuVrjyrtmCpwKjt%2FCVv7kPszDxrVyj9LDGg3s0ReCNBmN13j4aQgYJjTf1mm4S7IwWOKGZ819nCieYWSpvV5n%2Bwn5DZUCDp4le3sw%2BLjnvsFhS%2B2JI17heDES0xMLOmm5VvQWJWYiXT4ZTgh0%2FLRuKOnt7Qa3TSyqlsV7i8I%2FROlB6Z%2BoWjZ0xSt3fz2McCiB1ZqkUsCB7KaHuwapeW3FQv4tn%2Bin8PQ29WTqC9GjSa%2FRNeCfvhpF%2FM03Y4SI%2BacskSC2dheE70Zkvr6D5TYrLDJIBrnGP4P7l5LmNULDSiZyB5s0MqfTRJ2CP8YJAKJRJh7MJM%2BvEXKoH7Gw5ACK3OnITHZE0ue4sTXfvAD67pTAWY6wzUUIZ8jo%2FADortH5XEwPS7MhL37T9ANA%2FmHIvr4bV3ahd2oAhLJnx7T8%2BJNL5huv0lmWDkXEn3JBA1Fvvcy3GIKHYzY0sSY10eSrELJmq9kfRX3uz4nMKyZOjlHmc3E%2Fdr%2BulIn%2B69dQq%2Fm%2B%2BHC5ar%2FFUmR09oC5r5Sy3MHX2hny6ZO40K%2FF6Yl0oMGlMAgNdK0942WMLHk4r0GOqUBFPnm6%2F5khAMEmRsQ03OYRwfKD8buSalTMU%2FDBH%2BS9OTfh4qaa9ZPaEdtWYx9npc%2B1wnNZ6RTTWWYM6YhC56iBF82krvvMsKXZJ6OUpiXZjZcGZ%2FxNLGBE%2Bej8r%2FVPY1HGJ6IhaVGEbBUffoZLvYcuSnoaOJgz5P6XlfC7myKlHV%2Bk4qSen%2FxCIgc%2F0HGjicE0wW%2Bl1llz2T1iMSbW375O3Eh93Ov&X-Amz-Signature=f451c36d66b51ff67baef8c5f03bc2fa4da40f11d025510b239c4e12e36d2944&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TTPY5662%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T172118Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCrgP9N3hGLpWLWRoqFF1s591%2FM44hRbeDetWid7xs9qAIgeeXpP%2FejoSi2BxNP2giGv4TLXXlRGmyU2ysheFHkcyQqiAQI2v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNm5L3TpdWG0RC7A%2FyrcA8XYzvnrsvzLYY2ENaXI8Ew%2BSnyrV2W5Q5h%2FgVteQzfBdaTlqaw3NVX0GWO74VK6fkZwzuVrjyrtmCpwKjt%2FCVv7kPszDxrVyj9LDGg3s0ReCNBmN13j4aQgYJjTf1mm4S7IwWOKGZ819nCieYWSpvV5n%2Bwn5DZUCDp4le3sw%2BLjnvsFhS%2B2JI17heDES0xMLOmm5VvQWJWYiXT4ZTgh0%2FLRuKOnt7Qa3TSyqlsV7i8I%2FROlB6Z%2BoWjZ0xSt3fz2McCiB1ZqkUsCB7KaHuwapeW3FQv4tn%2Bin8PQ29WTqC9GjSa%2FRNeCfvhpF%2FM03Y4SI%2BacskSC2dheE70Zkvr6D5TYrLDJIBrnGP4P7l5LmNULDSiZyB5s0MqfTRJ2CP8YJAKJRJh7MJM%2BvEXKoH7Gw5ACK3OnITHZE0ue4sTXfvAD67pTAWY6wzUUIZ8jo%2FADortH5XEwPS7MhL37T9ANA%2FmHIvr4bV3ahd2oAhLJnx7T8%2BJNL5huv0lmWDkXEn3JBA1Fvvcy3GIKHYzY0sSY10eSrELJmq9kfRX3uz4nMKyZOjlHmc3E%2Fdr%2BulIn%2B69dQq%2Fm%2B%2BHC5ar%2FFUmR09oC5r5Sy3MHX2hny6ZO40K%2FF6Yl0oMGlMAgNdK0942WMLHk4r0GOqUBFPnm6%2F5khAMEmRsQ03OYRwfKD8buSalTMU%2FDBH%2BS9OTfh4qaa9ZPaEdtWYx9npc%2B1wnNZ6RTTWWYM6YhC56iBF82krvvMsKXZJ6OUpiXZjZcGZ%2FxNLGBE%2Bej8r%2FVPY1HGJ6IhaVGEbBUffoZLvYcuSnoaOJgz5P6XlfC7myKlHV%2Bk4qSen%2FxCIgc%2F0HGjicE0wW%2Bl1llz2T1iMSbW375O3Eh93Ov&X-Amz-Signature=89034f10bb0cfe1519c92f8390fa6d32a835d4e574db1ebfc4ce816bfb803962&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TTPY5662%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T172118Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCrgP9N3hGLpWLWRoqFF1s591%2FM44hRbeDetWid7xs9qAIgeeXpP%2FejoSi2BxNP2giGv4TLXXlRGmyU2ysheFHkcyQqiAQI2v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNm5L3TpdWG0RC7A%2FyrcA8XYzvnrsvzLYY2ENaXI8Ew%2BSnyrV2W5Q5h%2FgVteQzfBdaTlqaw3NVX0GWO74VK6fkZwzuVrjyrtmCpwKjt%2FCVv7kPszDxrVyj9LDGg3s0ReCNBmN13j4aQgYJjTf1mm4S7IwWOKGZ819nCieYWSpvV5n%2Bwn5DZUCDp4le3sw%2BLjnvsFhS%2B2JI17heDES0xMLOmm5VvQWJWYiXT4ZTgh0%2FLRuKOnt7Qa3TSyqlsV7i8I%2FROlB6Z%2BoWjZ0xSt3fz2McCiB1ZqkUsCB7KaHuwapeW3FQv4tn%2Bin8PQ29WTqC9GjSa%2FRNeCfvhpF%2FM03Y4SI%2BacskSC2dheE70Zkvr6D5TYrLDJIBrnGP4P7l5LmNULDSiZyB5s0MqfTRJ2CP8YJAKJRJh7MJM%2BvEXKoH7Gw5ACK3OnITHZE0ue4sTXfvAD67pTAWY6wzUUIZ8jo%2FADortH5XEwPS7MhL37T9ANA%2FmHIvr4bV3ahd2oAhLJnx7T8%2BJNL5huv0lmWDkXEn3JBA1Fvvcy3GIKHYzY0sSY10eSrELJmq9kfRX3uz4nMKyZOjlHmc3E%2Fdr%2BulIn%2B69dQq%2Fm%2B%2BHC5ar%2FFUmR09oC5r5Sy3MHX2hny6ZO40K%2FF6Yl0oMGlMAgNdK0942WMLHk4r0GOqUBFPnm6%2F5khAMEmRsQ03OYRwfKD8buSalTMU%2FDBH%2BS9OTfh4qaa9ZPaEdtWYx9npc%2B1wnNZ6RTTWWYM6YhC56iBF82krvvMsKXZJ6OUpiXZjZcGZ%2FxNLGBE%2Bej8r%2FVPY1HGJ6IhaVGEbBUffoZLvYcuSnoaOJgz5P6XlfC7myKlHV%2Bk4qSen%2FxCIgc%2F0HGjicE0wW%2Bl1llz2T1iMSbW375O3Eh93Ov&X-Amz-Signature=a8e4c4972e8245fd8ae7b2917178b2986ae1e9ddd97830aa0b66f1f524f51d59&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TTPY5662%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T172118Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCrgP9N3hGLpWLWRoqFF1s591%2FM44hRbeDetWid7xs9qAIgeeXpP%2FejoSi2BxNP2giGv4TLXXlRGmyU2ysheFHkcyQqiAQI2v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNm5L3TpdWG0RC7A%2FyrcA8XYzvnrsvzLYY2ENaXI8Ew%2BSnyrV2W5Q5h%2FgVteQzfBdaTlqaw3NVX0GWO74VK6fkZwzuVrjyrtmCpwKjt%2FCVv7kPszDxrVyj9LDGg3s0ReCNBmN13j4aQgYJjTf1mm4S7IwWOKGZ819nCieYWSpvV5n%2Bwn5DZUCDp4le3sw%2BLjnvsFhS%2B2JI17heDES0xMLOmm5VvQWJWYiXT4ZTgh0%2FLRuKOnt7Qa3TSyqlsV7i8I%2FROlB6Z%2BoWjZ0xSt3fz2McCiB1ZqkUsCB7KaHuwapeW3FQv4tn%2Bin8PQ29WTqC9GjSa%2FRNeCfvhpF%2FM03Y4SI%2BacskSC2dheE70Zkvr6D5TYrLDJIBrnGP4P7l5LmNULDSiZyB5s0MqfTRJ2CP8YJAKJRJh7MJM%2BvEXKoH7Gw5ACK3OnITHZE0ue4sTXfvAD67pTAWY6wzUUIZ8jo%2FADortH5XEwPS7MhL37T9ANA%2FmHIvr4bV3ahd2oAhLJnx7T8%2BJNL5huv0lmWDkXEn3JBA1Fvvcy3GIKHYzY0sSY10eSrELJmq9kfRX3uz4nMKyZOjlHmc3E%2Fdr%2BulIn%2B69dQq%2Fm%2B%2BHC5ar%2FFUmR09oC5r5Sy3MHX2hny6ZO40K%2FF6Yl0oMGlMAgNdK0942WMLHk4r0GOqUBFPnm6%2F5khAMEmRsQ03OYRwfKD8buSalTMU%2FDBH%2BS9OTfh4qaa9ZPaEdtWYx9npc%2B1wnNZ6RTTWWYM6YhC56iBF82krvvMsKXZJ6OUpiXZjZcGZ%2FxNLGBE%2Bej8r%2FVPY1HGJ6IhaVGEbBUffoZLvYcuSnoaOJgz5P6XlfC7myKlHV%2Bk4qSen%2FxCIgc%2F0HGjicE0wW%2Bl1llz2T1iMSbW375O3Eh93Ov&X-Amz-Signature=ea89d192c673d46114c327fe3a55636f93f3dd540cecc9e112f9bf32d7dab89a&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YXTY3BQ6%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T172119Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCliUSfpeXv8%2BQFdxvC0XZES%2BjJKFT8lwT0opJZUaLXSwIgNX9ycB%2BbAvJ1mLPmDwJTfQWhM%2FfAZhdodT98Sz0C%2BTAqiAQI2v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDWT4YRlCfaWND%2BTVyrcAytNbcPkxUNcU0B9Ta5WfCZQd7O5kA96HNzMzSfm776QSadU5JeW18JyS%2BpmV0mz5btESKnAjpXyPUpDK1J09qIfvidOMqm75ivAYcrsb0RucBtgvzZaFwwaB0MBRURarFjxTENtukbg5aysWLBumAXDx5YUJb1079sHpxd%2B8gRGWw8oQtaZxfEolqAlwi6lhn6AlCcI1jgpHY37G3e73jfjVBevVeUmiW53P3Y3ZyFBXNcXR9pm6UC1%2FcJywN%2FZQ067Nca%2B%2BEZDli3MWKiw%2ByO9umAKsVcmgtl79JOIxQlRTVNdSLACenU0zCzs9jvV7a4JibgZ2nWZsHrKXQC5NlGgx5jY9d%2FQo%2ByONBpPiMZVg9YT2taZd2B%2B1JzWjRGri0zIy9ns3yaJA%2FVaa1ptJl18aTZdd%2FNTIJ67owaqMz1zqScKuYCm4vV7O05%2Fu4nHfDGXcTBLd266PapvTo6ib9wg0Y2K8OWD6vPT2l9qNXGEp215HLKSMmFRXIvLQoOvZX53CHC3rXQrEIggfa9jIvx9uIxjjZ83UNJO5%2BSNvxy479ezItEC95wWdvwXAV5vIiPzOlk5thvSDx2Z1fvepTD8Wh5gE2i41%2FCZqdEUvp9y8oKMod8MmaK%2BzZlvMMPj4r0GOqUBaa5rV7%2FBXwPFIFOb9jZvyQTvhG8zVqGRGFzVaUm3uJz49dLwAVx50QFq%2FGhUlk3LXTgTT8CJEzfTKmG4kDPq1KqSqqr3gUXL3f2xb%2FTIUMZnRFH117mQ65kXb5JAjb0duHejx9bkaPEACBLvMri%2Fn2UWJRlnbqCgqKr6kkJdLFXwiyuKHqYFfg4%2FRAwk8lryUXQ4DUfBZz6wgIHACDsww4D0Ifpb&X-Amz-Signature=68ad6a34df2faf78079ff4b984084c4cbe7416e3395b29f2b09632b04aaecbe4&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VO6ZZHFR%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T172123Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIF12V47Q4Tg4VslhOMhPnuer91XUP%2F4dauoQhXRc2DchAiAgyzxQ9z7%2FfCKENFmWLONDMW5qvjej5NOA7xEsesJ3IiqIBAja%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMm88e%2FU40xud3ST%2FzKtwDdzvVEWKKTj2acDMnORXroW847dBpwsVVefivJdgwx0R5zNugDn9wz49jYiboyXB6WOtgEDBHSB6t%2FDnTIvrh1nirF%2B%2B5VB31%2F5y%2BsQxwZfmF4MiNP9LmmVVA6%2BfCaR2%2FrRUtkM9Xl5eFoxE8U9Oi11flb0IgfQQyxQw5FyRYB6fFffOw3BlD%2FWXnvKLd3YwGAPqVKZieSAbPhX%2FqvnzecyrDdcJdb3xOpjzLZ565KYb0IXu9pSvj4RgGKotc7kBNA%2FpWS0zP8M7R4%2BsX7m%2BUnLBOU4VSgSfBblK2wghIl1%2FCjceF42HkemFmxrTYmm5cvc78OwXNmRTmfZEbXh%2FYp6vWwr1nGq9smziGrsRMQmcXtgcxP68h84UOGy98UouvdvWYcL18OfYgCNBIlbPK%2FnqjzC6C5u9jUGQl0Rs%2BXtS2%2BOQBB5RsEZ480GbmKQBK1uyjfJWNZvGtzQ9KCYzFzPPlRVu3JOujNb7nVijalAISKpMMbPwF9WcCzVL8fedqRZsFuCMN5UHbrJAXARlb4vygidAEPGnqzkaMLfiYEeDpyD7wHoIThmdLdo%2BEYteVU%2FC1ibQP5ffVj6PguI5CphVUIDnWNrD358wlvR29Du0FNEH8WSxYN9o4yngw0%2BTivQY6pgEyo1ynDYAD3FokLrn1EMm0JaoHEUEbAD3dGU0AzCHylV3ySjgIDSF5zPY95N%2Bx%2B5Jp6%2FwQPp7IbnDihDiqB5j2oa2M6uA2%2FbRXipBMmKpdBTmNr9%2BceKylboToeWw8tEmAMa5L%2FpzFfg9RjTqeLPPj1NKvSr9S7dLS2noG5jJQSQ4NoNV6q9mYLItfXmkxe2TtUeKkw8a0D49rZYspN3c9x37L%2Begf&X-Amz-Signature=4f09cc2f04b7dc182b2e97e5cc56e9f7fb0962ab8c55b5eeb4ba9e05703efe15&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TTPY5662%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T172118Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCrgP9N3hGLpWLWRoqFF1s591%2FM44hRbeDetWid7xs9qAIgeeXpP%2FejoSi2BxNP2giGv4TLXXlRGmyU2ysheFHkcyQqiAQI2v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNm5L3TpdWG0RC7A%2FyrcA8XYzvnrsvzLYY2ENaXI8Ew%2BSnyrV2W5Q5h%2FgVteQzfBdaTlqaw3NVX0GWO74VK6fkZwzuVrjyrtmCpwKjt%2FCVv7kPszDxrVyj9LDGg3s0ReCNBmN13j4aQgYJjTf1mm4S7IwWOKGZ819nCieYWSpvV5n%2Bwn5DZUCDp4le3sw%2BLjnvsFhS%2B2JI17heDES0xMLOmm5VvQWJWYiXT4ZTgh0%2FLRuKOnt7Qa3TSyqlsV7i8I%2FROlB6Z%2BoWjZ0xSt3fz2McCiB1ZqkUsCB7KaHuwapeW3FQv4tn%2Bin8PQ29WTqC9GjSa%2FRNeCfvhpF%2FM03Y4SI%2BacskSC2dheE70Zkvr6D5TYrLDJIBrnGP4P7l5LmNULDSiZyB5s0MqfTRJ2CP8YJAKJRJh7MJM%2BvEXKoH7Gw5ACK3OnITHZE0ue4sTXfvAD67pTAWY6wzUUIZ8jo%2FADortH5XEwPS7MhL37T9ANA%2FmHIvr4bV3ahd2oAhLJnx7T8%2BJNL5huv0lmWDkXEn3JBA1Fvvcy3GIKHYzY0sSY10eSrELJmq9kfRX3uz4nMKyZOjlHmc3E%2Fdr%2BulIn%2B69dQq%2Fm%2B%2BHC5ar%2FFUmR09oC5r5Sy3MHX2hny6ZO40K%2FF6Yl0oMGlMAgNdK0942WMLHk4r0GOqUBFPnm6%2F5khAMEmRsQ03OYRwfKD8buSalTMU%2FDBH%2BS9OTfh4qaa9ZPaEdtWYx9npc%2B1wnNZ6RTTWWYM6YhC56iBF82krvvMsKXZJ6OUpiXZjZcGZ%2FxNLGBE%2Bej8r%2FVPY1HGJ6IhaVGEbBUffoZLvYcuSnoaOJgz5P6XlfC7myKlHV%2Bk4qSen%2FxCIgc%2F0HGjicE0wW%2Bl1llz2T1iMSbW375O3Eh93Ov&X-Amz-Signature=0ce3cd7e925db544f41a793a9ffad655460afbb0f1182b4aac3719c48a8677de&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TTPY5662%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T172118Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCrgP9N3hGLpWLWRoqFF1s591%2FM44hRbeDetWid7xs9qAIgeeXpP%2FejoSi2BxNP2giGv4TLXXlRGmyU2ysheFHkcyQqiAQI2v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNm5L3TpdWG0RC7A%2FyrcA8XYzvnrsvzLYY2ENaXI8Ew%2BSnyrV2W5Q5h%2FgVteQzfBdaTlqaw3NVX0GWO74VK6fkZwzuVrjyrtmCpwKjt%2FCVv7kPszDxrVyj9LDGg3s0ReCNBmN13j4aQgYJjTf1mm4S7IwWOKGZ819nCieYWSpvV5n%2Bwn5DZUCDp4le3sw%2BLjnvsFhS%2B2JI17heDES0xMLOmm5VvQWJWYiXT4ZTgh0%2FLRuKOnt7Qa3TSyqlsV7i8I%2FROlB6Z%2BoWjZ0xSt3fz2McCiB1ZqkUsCB7KaHuwapeW3FQv4tn%2Bin8PQ29WTqC9GjSa%2FRNeCfvhpF%2FM03Y4SI%2BacskSC2dheE70Zkvr6D5TYrLDJIBrnGP4P7l5LmNULDSiZyB5s0MqfTRJ2CP8YJAKJRJh7MJM%2BvEXKoH7Gw5ACK3OnITHZE0ue4sTXfvAD67pTAWY6wzUUIZ8jo%2FADortH5XEwPS7MhL37T9ANA%2FmHIvr4bV3ahd2oAhLJnx7T8%2BJNL5huv0lmWDkXEn3JBA1Fvvcy3GIKHYzY0sSY10eSrELJmq9kfRX3uz4nMKyZOjlHmc3E%2Fdr%2BulIn%2B69dQq%2Fm%2B%2BHC5ar%2FFUmR09oC5r5Sy3MHX2hny6ZO40K%2FF6Yl0oMGlMAgNdK0942WMLHk4r0GOqUBFPnm6%2F5khAMEmRsQ03OYRwfKD8buSalTMU%2FDBH%2BS9OTfh4qaa9ZPaEdtWYx9npc%2B1wnNZ6RTTWWYM6YhC56iBF82krvvMsKXZJ6OUpiXZjZcGZ%2FxNLGBE%2Bej8r%2FVPY1HGJ6IhaVGEbBUffoZLvYcuSnoaOJgz5P6XlfC7myKlHV%2Bk4qSen%2FxCIgc%2F0HGjicE0wW%2Bl1llz2T1iMSbW375O3Eh93Ov&X-Amz-Signature=a0045ab7ef3f32707901f9060e40bd7349fd9cd7f4bc437d4d63984b41afe53d&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TTPY5662%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T172118Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCrgP9N3hGLpWLWRoqFF1s591%2FM44hRbeDetWid7xs9qAIgeeXpP%2FejoSi2BxNP2giGv4TLXXlRGmyU2ysheFHkcyQqiAQI2v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNm5L3TpdWG0RC7A%2FyrcA8XYzvnrsvzLYY2ENaXI8Ew%2BSnyrV2W5Q5h%2FgVteQzfBdaTlqaw3NVX0GWO74VK6fkZwzuVrjyrtmCpwKjt%2FCVv7kPszDxrVyj9LDGg3s0ReCNBmN13j4aQgYJjTf1mm4S7IwWOKGZ819nCieYWSpvV5n%2Bwn5DZUCDp4le3sw%2BLjnvsFhS%2B2JI17heDES0xMLOmm5VvQWJWYiXT4ZTgh0%2FLRuKOnt7Qa3TSyqlsV7i8I%2FROlB6Z%2BoWjZ0xSt3fz2McCiB1ZqkUsCB7KaHuwapeW3FQv4tn%2Bin8PQ29WTqC9GjSa%2FRNeCfvhpF%2FM03Y4SI%2BacskSC2dheE70Zkvr6D5TYrLDJIBrnGP4P7l5LmNULDSiZyB5s0MqfTRJ2CP8YJAKJRJh7MJM%2BvEXKoH7Gw5ACK3OnITHZE0ue4sTXfvAD67pTAWY6wzUUIZ8jo%2FADortH5XEwPS7MhL37T9ANA%2FmHIvr4bV3ahd2oAhLJnx7T8%2BJNL5huv0lmWDkXEn3JBA1Fvvcy3GIKHYzY0sSY10eSrELJmq9kfRX3uz4nMKyZOjlHmc3E%2Fdr%2BulIn%2B69dQq%2Fm%2B%2BHC5ar%2FFUmR09oC5r5Sy3MHX2hny6ZO40K%2FF6Yl0oMGlMAgNdK0942WMLHk4r0GOqUBFPnm6%2F5khAMEmRsQ03OYRwfKD8buSalTMU%2FDBH%2BS9OTfh4qaa9ZPaEdtWYx9npc%2B1wnNZ6RTTWWYM6YhC56iBF82krvvMsKXZJ6OUpiXZjZcGZ%2FxNLGBE%2Bej8r%2FVPY1HGJ6IhaVGEbBUffoZLvYcuSnoaOJgz5P6XlfC7myKlHV%2Bk4qSen%2FxCIgc%2F0HGjicE0wW%2Bl1llz2T1iMSbW375O3Eh93Ov&X-Amz-Signature=07c3158ba864414d57a833614fd1479e9d7993c6db4cbd27133019d778166b16&X-Amz-SignedHeaders=host&x-id=GetObject)


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

