---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466363JGWUB%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250222T032616Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjELv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDvYg0jW188G%2Frlq\
  BX%2BS6m6Ws8PXf2SLwiFbDIq2nYU7wIhAM2wNXMbmQLt4DwscVe4n8y%2Ff7NDg1Dk1%2F1rUxk0\
  %2BzQHKogECOP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwqZeJ2jyF\
  KNTk02Ccq3AOCQdGr8qzbQTp0QKyKhU9bVsXnAvxpceQnvZAu0sbB2LbQzr9VIjARMFT%2BInXNTt\
  qnyH0zH60yeeGWOHMez%2BUGWbaT6dbFdUYgLpDTDmmq8yRJ4iWEN9YYNpH8Mc4m%2BR7xgkDbCG8\
  5lU0ws0AFiLtyd15Yvt%2BO1LoxLCogVUZSXHgiIfHhfbZ9ExSqT5kA897jwvidKQYiv6kBAKMt7U\
  0fc3K%2FSJ6r94yCnK581ww%2BpR6la4mkAcct%2FTLAdNOMm4Ut%2FAQLzlqe%2FTY5OglqTDq48\
  O%2F%2BkehTN3gLPIoES2smb%2B1T6BFo3j%2BD2LnpBNYczlhaAkwUg8EQZGRjhHcP1QoltjZP2B\
  8aRywSFpmRBgHNRC82526ZHKKMApMGITkiUls%2FoyWMowFIaoaj0U1kkMZZgM8ZMg4NzGCM0gsMZ\
  a6GHbbg6BvqbuzcqKj2Z4fkwydMcgYUKbUvDGZKEMC2OK%2B9sfHX1NhK7Y946B7oQir5GjopmtGV\
  ItjstDRAjcJ220h%2FAG4RZ4IFL86htjjz64G2zXxADlQQcmeDDmgKy9FTC%2BIihdubzS1DtVMco\
  ijmRjzf%2BQjIKUec9T50zLEut4OBaR7yD3rMsfIu1QRDZEjLhgwt%2BEvwd6pdsF2FIzDp7OS9Bj\
  qkAXprPRUb5pYPtR8J9NSnByFhFTLfiQcME7aSTIV9x5DH1vKletuIRcbqvwYcemacl4CFfASXhAH\
  oyid2n8Ntvnsur35TT0%2BD31jCQfxH2RNjId%2BbvKds9JExr0t79p7Fw3jHtwJXYsuh7jTvfC4M\
  %2FwOQ%2Ft0qKF8HDaru5a0HHvoTjxUDQEomkuXH3XRbgJ5HiwJIBlOnNZOrakT05REqfksa2w3o&\
  X-Amz-Signature=b9b0f6cbe076840ab151d970494623016beb1fed702d4b81266d2a98b7f5e\
  49f&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4667YMTH3RV%2F20250222%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250222T032506Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjELv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIQCVkEhTVuss1Nv%2FlGBd7%2FDVf8l9Hpn8hJ7z9qws4qwKTAIgEiJu2c6l0CMUwgh4lH\
        r2dx0y9JbISvIbHOtoAyZuwUgqiAQI5P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2M\
        zc0MjMxODM4MDUiDLxAhXDuLk3I%2BiDWZyrcA%2BAJgP5ztuVIh05YEVQUxEt3RI9RBVOe\
        wrSjjxVyYh%2Fs0qvgGykJjy6fjQLT4FB8kkZtCV3%2BxnWjUsTA4kmbuMU6TIHWeSv4Umc\
        6tH67ZlVoqVkfKZm4rbCdokabEL4X0HBOl5bgSOMETKJCGXAk4RL21ahX%2F7Xt%2FPdWyR\
        P7SKtm4pnYe1gtDvY1RDxOK91zG3KiZd77Y0jYAND8ExWb2L4cGVprXiyh5dtuV82MAscM1\
        %2B6ikCl4KD%2BeSGT7vh8%2B5iXEOKvUSOs4D4xuRH4y1GnyWZRFYrzkOHQ2QHFSYwdnGm\
        FAxkPZqh90Oy66VnXCEC9wKm9HB4KP%2B%2BbL%2BeClI3l2y%2Bg4dZZfV0AAkRUjRx4%2\
        BAGkH%2FyyVBkO5Ls838tEdFscJREDcpEMWLUOOoH2HoYoskLUdBnx%2FGiayXQiuaIk3hJ\
        XMAvoACnD6UvrSw6Z8Zldag3OOszBw3GN%2B8Lz18lAn1onPcMU%2BSMiHOl%2B%2Bc%2Fy\
        4cLMBsnzpQsxgjrpMBCiurpNZPHxEKhgTVD9E1QR8s7VcI3tTW1po6nEWFDwHN7DLxSMUGx\
        z4U6eFOVrVduOodWGGCikp6QKjGJ7h7gm5fdfNlX8aYq77XWnlHAtovoTPR3l1DLzk29wfL\
        c7yMOrs5L0GOqUBvXwQhJ6m1GjS9TYmD97P3z3208632g9JfMHJS6fvBkcz28Uq4s55VBuC\
        A3yRoqsASq7%2FaLnz8B8TVFQPrjiSGdj%2F7spxZH2B%2FQQ140n7qGc6OzrL3SFezJGi1\
        KePegzyw0C5e%2F0w6OWUTEMtLgSlNKKcLGRuC4a9PN8n%2BPb9tcOFsHQYx0eDzbeK%2Bw\
        de%2FM6eGITJSKoVPw6MdsFGTN7JiEvhV98L&X-Amz-Signature=3d2d548d9c7064c8d8\
        48f62eaee493aa2dec7fb30c03fe9cabb126c1a4a831c9&X-Amz-SignedHeaders=host\
        &x-id=GetObject"
      expiry_time: "2025-02-22T04:25:06.590Z"
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
UPDATE_TIME: "2025-02-22T03:26:22.217Z"
EXPIRY_TIME: "2025-02-22T04:26:14.564Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XGI4QSIR%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T032615Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDixxtYAlVgWEPokziPgvzcpVSSE5UaXlbB1P9Vq01rPQIgOZoDN70LAVxnFhf4pyPPEkHSZwtsIANwSLYMSouU3xEqiAQI5P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOBsYhgBgG1av4mAYircA2YYOb2XrxMBD9X9Iz98eYEdJIHp27DhwybwQ1kiZMa12X2dhwDZA9F7W223wDiWHsPpNsRYwznyCYFh3iLBPAlxpsFBHKVBwyKbrPQr7Xelotpwea59OwmlxMZvsTOsjEVy9s9FZUfqRJV0A%2FN7KKzANATYCagnG8oza%2FqOelkAn%2FhY3C0eyPjJJfzEvgoOvZ3PMNBlTEue1gPKLIwwsPvT1wuxQ3OiNGTsYxaTicOhHfocjeloXvEr65PTS4aNVUEViQ0lzhtIovA7QACbIPbaeJuyHqD4rfOIHNK3Ntdbb9a6irWF8ontTYOJ4lnUC%2FkeE9qcclnuk201PO%2FcSOGYThhTKX4QMj7hqdh8v3AEKua8tjnHrIYQqoZb7fc1x1tKylXChYPPdWXZO9CpWKvPSbP%2Fs1nRjiwB05juu319G1MzV4SaNWggC17d6lKdfmBJPhkAUdM2qQGWwj%2Faur9t4xqnRIIC34tRfnG2zxYMOKk%2FfL%2BmJn7wvrTusWg5RB%2BTCzEdBnVzrKvJh%2BoXzdIVguTIw%2FU4nZC8heIKfrQVDG3YZAfVt%2Baw%2FZssLoldjz4gO7%2BU5CP09jw2etcOpJri1qQGclyuXlFP5FaTKGz%2Bgi5HFP4qq%2BU7j46MMIXs5L0GOqUB40%2BSDRBgIfdlomsYdZqkXxYzzvhcirX%2FS8lLVutUqC4ttEMuPwpci0JbWqMrltuLIVCIdhXkiBkowUFoma6Sb%2BYs8duIpiWFiM7PfzGb60bpZC%2FXGVKmQT%2F5KBWkcCiBFws3UWLXyNSh1oWWO6QiA9HKa0AQMX3WRGhRzrcyYZs95z6iwLpWqsx9ghWKUBiWbrazkAhZqkzMzs0FYoiuW%2BcrhxT3&X-Amz-Signature=4c871c234df7549e432b5429c7ea43e5aee18b8d4f35a1ed45ca3c0439dd7ff1&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XGI4QSIR%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T032615Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDixxtYAlVgWEPokziPgvzcpVSSE5UaXlbB1P9Vq01rPQIgOZoDN70LAVxnFhf4pyPPEkHSZwtsIANwSLYMSouU3xEqiAQI5P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOBsYhgBgG1av4mAYircA2YYOb2XrxMBD9X9Iz98eYEdJIHp27DhwybwQ1kiZMa12X2dhwDZA9F7W223wDiWHsPpNsRYwznyCYFh3iLBPAlxpsFBHKVBwyKbrPQr7Xelotpwea59OwmlxMZvsTOsjEVy9s9FZUfqRJV0A%2FN7KKzANATYCagnG8oza%2FqOelkAn%2FhY3C0eyPjJJfzEvgoOvZ3PMNBlTEue1gPKLIwwsPvT1wuxQ3OiNGTsYxaTicOhHfocjeloXvEr65PTS4aNVUEViQ0lzhtIovA7QACbIPbaeJuyHqD4rfOIHNK3Ntdbb9a6irWF8ontTYOJ4lnUC%2FkeE9qcclnuk201PO%2FcSOGYThhTKX4QMj7hqdh8v3AEKua8tjnHrIYQqoZb7fc1x1tKylXChYPPdWXZO9CpWKvPSbP%2Fs1nRjiwB05juu319G1MzV4SaNWggC17d6lKdfmBJPhkAUdM2qQGWwj%2Faur9t4xqnRIIC34tRfnG2zxYMOKk%2FfL%2BmJn7wvrTusWg5RB%2BTCzEdBnVzrKvJh%2BoXzdIVguTIw%2FU4nZC8heIKfrQVDG3YZAfVt%2Baw%2FZssLoldjz4gO7%2BU5CP09jw2etcOpJri1qQGclyuXlFP5FaTKGz%2Bgi5HFP4qq%2BU7j46MMIXs5L0GOqUB40%2BSDRBgIfdlomsYdZqkXxYzzvhcirX%2FS8lLVutUqC4ttEMuPwpci0JbWqMrltuLIVCIdhXkiBkowUFoma6Sb%2BYs8duIpiWFiM7PfzGb60bpZC%2FXGVKmQT%2F5KBWkcCiBFws3UWLXyNSh1oWWO6QiA9HKa0AQMX3WRGhRzrcyYZs95z6iwLpWqsx9ghWKUBiWbrazkAhZqkzMzs0FYoiuW%2BcrhxT3&X-Amz-Signature=953368d70c0c738cb39a93dc412653dc9ffe4cbb66cc75cfaf0c3916552b30dd&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XGI4QSIR%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T032615Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDixxtYAlVgWEPokziPgvzcpVSSE5UaXlbB1P9Vq01rPQIgOZoDN70LAVxnFhf4pyPPEkHSZwtsIANwSLYMSouU3xEqiAQI5P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOBsYhgBgG1av4mAYircA2YYOb2XrxMBD9X9Iz98eYEdJIHp27DhwybwQ1kiZMa12X2dhwDZA9F7W223wDiWHsPpNsRYwznyCYFh3iLBPAlxpsFBHKVBwyKbrPQr7Xelotpwea59OwmlxMZvsTOsjEVy9s9FZUfqRJV0A%2FN7KKzANATYCagnG8oza%2FqOelkAn%2FhY3C0eyPjJJfzEvgoOvZ3PMNBlTEue1gPKLIwwsPvT1wuxQ3OiNGTsYxaTicOhHfocjeloXvEr65PTS4aNVUEViQ0lzhtIovA7QACbIPbaeJuyHqD4rfOIHNK3Ntdbb9a6irWF8ontTYOJ4lnUC%2FkeE9qcclnuk201PO%2FcSOGYThhTKX4QMj7hqdh8v3AEKua8tjnHrIYQqoZb7fc1x1tKylXChYPPdWXZO9CpWKvPSbP%2Fs1nRjiwB05juu319G1MzV4SaNWggC17d6lKdfmBJPhkAUdM2qQGWwj%2Faur9t4xqnRIIC34tRfnG2zxYMOKk%2FfL%2BmJn7wvrTusWg5RB%2BTCzEdBnVzrKvJh%2BoXzdIVguTIw%2FU4nZC8heIKfrQVDG3YZAfVt%2Baw%2FZssLoldjz4gO7%2BU5CP09jw2etcOpJri1qQGclyuXlFP5FaTKGz%2Bgi5HFP4qq%2BU7j46MMIXs5L0GOqUB40%2BSDRBgIfdlomsYdZqkXxYzzvhcirX%2FS8lLVutUqC4ttEMuPwpci0JbWqMrltuLIVCIdhXkiBkowUFoma6Sb%2BYs8duIpiWFiM7PfzGb60bpZC%2FXGVKmQT%2F5KBWkcCiBFws3UWLXyNSh1oWWO6QiA9HKa0AQMX3WRGhRzrcyYZs95z6iwLpWqsx9ghWKUBiWbrazkAhZqkzMzs0FYoiuW%2BcrhxT3&X-Amz-Signature=a8a37a2fb98edcffbd9c93b35cb05d52c3be912f796b4a289dd1ba3f64b91a65&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XGI4QSIR%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T032615Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDixxtYAlVgWEPokziPgvzcpVSSE5UaXlbB1P9Vq01rPQIgOZoDN70LAVxnFhf4pyPPEkHSZwtsIANwSLYMSouU3xEqiAQI5P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOBsYhgBgG1av4mAYircA2YYOb2XrxMBD9X9Iz98eYEdJIHp27DhwybwQ1kiZMa12X2dhwDZA9F7W223wDiWHsPpNsRYwznyCYFh3iLBPAlxpsFBHKVBwyKbrPQr7Xelotpwea59OwmlxMZvsTOsjEVy9s9FZUfqRJV0A%2FN7KKzANATYCagnG8oza%2FqOelkAn%2FhY3C0eyPjJJfzEvgoOvZ3PMNBlTEue1gPKLIwwsPvT1wuxQ3OiNGTsYxaTicOhHfocjeloXvEr65PTS4aNVUEViQ0lzhtIovA7QACbIPbaeJuyHqD4rfOIHNK3Ntdbb9a6irWF8ontTYOJ4lnUC%2FkeE9qcclnuk201PO%2FcSOGYThhTKX4QMj7hqdh8v3AEKua8tjnHrIYQqoZb7fc1x1tKylXChYPPdWXZO9CpWKvPSbP%2Fs1nRjiwB05juu319G1MzV4SaNWggC17d6lKdfmBJPhkAUdM2qQGWwj%2Faur9t4xqnRIIC34tRfnG2zxYMOKk%2FfL%2BmJn7wvrTusWg5RB%2BTCzEdBnVzrKvJh%2BoXzdIVguTIw%2FU4nZC8heIKfrQVDG3YZAfVt%2Baw%2FZssLoldjz4gO7%2BU5CP09jw2etcOpJri1qQGclyuXlFP5FaTKGz%2Bgi5HFP4qq%2BU7j46MMIXs5L0GOqUB40%2BSDRBgIfdlomsYdZqkXxYzzvhcirX%2FS8lLVutUqC4ttEMuPwpci0JbWqMrltuLIVCIdhXkiBkowUFoma6Sb%2BYs8duIpiWFiM7PfzGb60bpZC%2FXGVKmQT%2F5KBWkcCiBFws3UWLXyNSh1oWWO6QiA9HKa0AQMX3WRGhRzrcyYZs95z6iwLpWqsx9ghWKUBiWbrazkAhZqkzMzs0FYoiuW%2BcrhxT3&X-Amz-Signature=bb00d45510c21d0e3ac44141a5fbd8a7444da53ce2a3ae2d9d1d19d8605a09f1&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XGI4QSIR%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T032615Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDixxtYAlVgWEPokziPgvzcpVSSE5UaXlbB1P9Vq01rPQIgOZoDN70LAVxnFhf4pyPPEkHSZwtsIANwSLYMSouU3xEqiAQI5P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOBsYhgBgG1av4mAYircA2YYOb2XrxMBD9X9Iz98eYEdJIHp27DhwybwQ1kiZMa12X2dhwDZA9F7W223wDiWHsPpNsRYwznyCYFh3iLBPAlxpsFBHKVBwyKbrPQr7Xelotpwea59OwmlxMZvsTOsjEVy9s9FZUfqRJV0A%2FN7KKzANATYCagnG8oza%2FqOelkAn%2FhY3C0eyPjJJfzEvgoOvZ3PMNBlTEue1gPKLIwwsPvT1wuxQ3OiNGTsYxaTicOhHfocjeloXvEr65PTS4aNVUEViQ0lzhtIovA7QACbIPbaeJuyHqD4rfOIHNK3Ntdbb9a6irWF8ontTYOJ4lnUC%2FkeE9qcclnuk201PO%2FcSOGYThhTKX4QMj7hqdh8v3AEKua8tjnHrIYQqoZb7fc1x1tKylXChYPPdWXZO9CpWKvPSbP%2Fs1nRjiwB05juu319G1MzV4SaNWggC17d6lKdfmBJPhkAUdM2qQGWwj%2Faur9t4xqnRIIC34tRfnG2zxYMOKk%2FfL%2BmJn7wvrTusWg5RB%2BTCzEdBnVzrKvJh%2BoXzdIVguTIw%2FU4nZC8heIKfrQVDG3YZAfVt%2Baw%2FZssLoldjz4gO7%2BU5CP09jw2etcOpJri1qQGclyuXlFP5FaTKGz%2Bgi5HFP4qq%2BU7j46MMIXs5L0GOqUB40%2BSDRBgIfdlomsYdZqkXxYzzvhcirX%2FS8lLVutUqC4ttEMuPwpci0JbWqMrltuLIVCIdhXkiBkowUFoma6Sb%2BYs8duIpiWFiM7PfzGb60bpZC%2FXGVKmQT%2F5KBWkcCiBFws3UWLXyNSh1oWWO6QiA9HKa0AQMX3WRGhRzrcyYZs95z6iwLpWqsx9ghWKUBiWbrazkAhZqkzMzs0FYoiuW%2BcrhxT3&X-Amz-Signature=6ef9ed1a933de9a4d61c785871e9eb6e39ec46e59ced939af3fbc03bd9d139d6&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YRF5RTWF%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T032615Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCICnZUcFYAMeNR69SW8Ci8sj22GPxeKUFfaMO1ad3raMKAiEAkxjdQiHplCD8ROsmbBZ5tFlVBKpB%2BX%2BhB%2BoOOlZ0VaMqiAQI5P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDN7FMo0KYrbGIdohFSrcA83RewqSZA72Bu9yaAgPNSrxKwU63CEe879JW9hHM7u56OmN1idHSX3UKUR3EhTNYcPhkkEgYIH4VTUnofwoI9BcvoB9OQvJSSi0AeLsaSyFsrTK9mEZ4ko0H%2BCBb7WeBWQ8KY4YHZ0sm%2BEB%2FmgntCvHmM48NbhcLsmJsRrVNHeILB2ewB8gm5UC%2F1TC8B3%2Bp4f8ii4vE1ih1D59IQMAFTf1WQG6n7kHqx7gWcF%2BVeTdtFVD7SHmVM%2Bgb8vPqUX1%2BBNi6Pd%2FshYjplHirnBHNn2wnglxkCCdES39DZTgYEsqjtxD9HC2or2yYvy8nU85Bf1I%2Fh5rFQ91xBWvZquEPbSwI4nosWrbErBabwRMg4HbeLOE%2BCBb%2BSBZ2ISPN8lCpdaquESHxH%2FhKgY26jAGQ26VGb0vioffnFSm4zQ%2FSbWXFLifli1GQs0qEiF3CO5LSeZ2KDftrGVQT9WwCcGKDIWaq1DkgMLwMMMoH7JxK5p6NGN3hQDDZHkvFTXW63BKxdj2%2Beo1WihGiCcakJ0EalOVsrVbJ5ZmuZwURBUApU4RRUwBUq4ej%2FgfEdQHt0CjusSoGrdQWT8HFUp5oYNZCxaNDA1r88yvfc%2BZ3LCOatAUktHjInvFSIP1tOJVMJfs5L0GOqUBHId5WFBh%2Fn4ss67ilnURR2RYYfIt5IeeIht84m%2BgHgoe%2Bwe97svdY2M%2By%2BKb4uvbNShvckqT0rNlWvATx948%2BpELq1RBmcwjw1CR8aZJMyJ%2BR%2BPRXaE%2FT5Xo1nyW9mWZvOXhOErKLvyLJGUCI008OYY49x2Q9sVO4abJv3I7XcnzuDTrg2CImBXvonFLgxHmBaf3PJhJrXGz4t%2B%2BUzn0c3KTrW%2BL&X-Amz-Signature=6b587fe1d1d17e6052d430e8e918973c86bb44a3e5086025e2827bad8bbf5375&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U6VBL4E3%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T032616Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDRypiXjU8x6R%2FXqvFJOb3VKeGvYxe5%2FPHc5RWfMvmxNgIgZgCleZYM4Vz2MDmxLVz1FPZH6IQjpL7PuDBSl6LHXVEqiAQI5P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOYPlQRhUky5JoXO5ircA0QGZRSM3XrSdWEJ3hcGcL4AclFdKlB6qpE9W6Zt6eyb4UMqnxN3whBVmi0QZLVs%2FTdb4mc8G7XI370uSSEcyorTdeaAJeoVqrRV77GOmIM%2BRAe2Legv8QyI82SOTjL%2FWgO390s4BiuTZ0idt0ObaNpio6ja4ZPCrdPamSrZHT%2FiaX%2BvrpILmHlNIRjS8%2FnshlXVvHLGZdda6BHXKDY2ma2fdEcw2AlnUKFwo501UxsG0S4kqF2HWM%2BNBHgdP11VBDjgF7e5pFLKd3eylWoAQItdrqiRQ7bq6G8AmJ6O%2F3CvJRm6HaW1B3LHUfFybqsjMuVLejPXfp%2BQggTJXRupeKaFYI4DrsA6yY8xmajOMzo6rnh8fMf%2FivQVPpLyQOHKNapws80Ya2rIBszXs1F4ijpRnGl3qxZzK%2BAYjcyanDIZ1DRnsUrWbKadSdNxjk7CQUJVSbIZ6Ynerkf3OlEqkMkMAfDgEmWPdEOZ%2FOOXPDkPP5NL4%2FzxFPMr%2B43w%2BEp8WBCk0%2FXFE%2FYEmSHSsyJOL6EKSid3r3EhtNxZleroiK2UOnOALxvoTQRpKO7qeu9KRBuSxdWc6GdahWA5F%2FDHH5eiwxZRKyvNAb4MagTrYE5CwMZJ0pZKSCc1Fp7nMIjt5L0GOqUBEjoOSDvE5SA5W49PZI%2Bz%2FJQtffIqUyO%2FfgLXlDDspvPZ%2BSEk7ByAb3n2EVKbdOxvisBGerXcK%2F%2BzUFnAq%2BRlT4dV8p6awnywvVEZKaXDvugAwwVOHxru0yv5XyeGF9hsAFLVzk9ylz9AsQ69gdYC2MXglALK4MI2FuZVxNDpjAx5vDsLiVp9mPh%2F5TnBw4PC2kKLCeOlau%2BOQOqN7Xu1dAHCOfwL&X-Amz-Signature=f1c08558a1e18ce9e7ab71a5ecb3b23c69a40dcc75b7251fb0b840a3e4847fb0&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XGI4QSIR%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T032615Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDixxtYAlVgWEPokziPgvzcpVSSE5UaXlbB1P9Vq01rPQIgOZoDN70LAVxnFhf4pyPPEkHSZwtsIANwSLYMSouU3xEqiAQI5P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOBsYhgBgG1av4mAYircA2YYOb2XrxMBD9X9Iz98eYEdJIHp27DhwybwQ1kiZMa12X2dhwDZA9F7W223wDiWHsPpNsRYwznyCYFh3iLBPAlxpsFBHKVBwyKbrPQr7Xelotpwea59OwmlxMZvsTOsjEVy9s9FZUfqRJV0A%2FN7KKzANATYCagnG8oza%2FqOelkAn%2FhY3C0eyPjJJfzEvgoOvZ3PMNBlTEue1gPKLIwwsPvT1wuxQ3OiNGTsYxaTicOhHfocjeloXvEr65PTS4aNVUEViQ0lzhtIovA7QACbIPbaeJuyHqD4rfOIHNK3Ntdbb9a6irWF8ontTYOJ4lnUC%2FkeE9qcclnuk201PO%2FcSOGYThhTKX4QMj7hqdh8v3AEKua8tjnHrIYQqoZb7fc1x1tKylXChYPPdWXZO9CpWKvPSbP%2Fs1nRjiwB05juu319G1MzV4SaNWggC17d6lKdfmBJPhkAUdM2qQGWwj%2Faur9t4xqnRIIC34tRfnG2zxYMOKk%2FfL%2BmJn7wvrTusWg5RB%2BTCzEdBnVzrKvJh%2BoXzdIVguTIw%2FU4nZC8heIKfrQVDG3YZAfVt%2Baw%2FZssLoldjz4gO7%2BU5CP09jw2etcOpJri1qQGclyuXlFP5FaTKGz%2Bgi5HFP4qq%2BU7j46MMIXs5L0GOqUB40%2BSDRBgIfdlomsYdZqkXxYzzvhcirX%2FS8lLVutUqC4ttEMuPwpci0JbWqMrltuLIVCIdhXkiBkowUFoma6Sb%2BYs8duIpiWFiM7PfzGb60bpZC%2FXGVKmQT%2F5KBWkcCiBFws3UWLXyNSh1oWWO6QiA9HKa0AQMX3WRGhRzrcyYZs95z6iwLpWqsx9ghWKUBiWbrazkAhZqkzMzs0FYoiuW%2BcrhxT3&X-Amz-Signature=56530a0b2718de9cb48c2dd1aaed673f0c04465b86e4de3224f0a67f6f42ea97&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XGI4QSIR%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T032615Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDixxtYAlVgWEPokziPgvzcpVSSE5UaXlbB1P9Vq01rPQIgOZoDN70LAVxnFhf4pyPPEkHSZwtsIANwSLYMSouU3xEqiAQI5P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOBsYhgBgG1av4mAYircA2YYOb2XrxMBD9X9Iz98eYEdJIHp27DhwybwQ1kiZMa12X2dhwDZA9F7W223wDiWHsPpNsRYwznyCYFh3iLBPAlxpsFBHKVBwyKbrPQr7Xelotpwea59OwmlxMZvsTOsjEVy9s9FZUfqRJV0A%2FN7KKzANATYCagnG8oza%2FqOelkAn%2FhY3C0eyPjJJfzEvgoOvZ3PMNBlTEue1gPKLIwwsPvT1wuxQ3OiNGTsYxaTicOhHfocjeloXvEr65PTS4aNVUEViQ0lzhtIovA7QACbIPbaeJuyHqD4rfOIHNK3Ntdbb9a6irWF8ontTYOJ4lnUC%2FkeE9qcclnuk201PO%2FcSOGYThhTKX4QMj7hqdh8v3AEKua8tjnHrIYQqoZb7fc1x1tKylXChYPPdWXZO9CpWKvPSbP%2Fs1nRjiwB05juu319G1MzV4SaNWggC17d6lKdfmBJPhkAUdM2qQGWwj%2Faur9t4xqnRIIC34tRfnG2zxYMOKk%2FfL%2BmJn7wvrTusWg5RB%2BTCzEdBnVzrKvJh%2BoXzdIVguTIw%2FU4nZC8heIKfrQVDG3YZAfVt%2Baw%2FZssLoldjz4gO7%2BU5CP09jw2etcOpJri1qQGclyuXlFP5FaTKGz%2Bgi5HFP4qq%2BU7j46MMIXs5L0GOqUB40%2BSDRBgIfdlomsYdZqkXxYzzvhcirX%2FS8lLVutUqC4ttEMuPwpci0JbWqMrltuLIVCIdhXkiBkowUFoma6Sb%2BYs8duIpiWFiM7PfzGb60bpZC%2FXGVKmQT%2F5KBWkcCiBFws3UWLXyNSh1oWWO6QiA9HKa0AQMX3WRGhRzrcyYZs95z6iwLpWqsx9ghWKUBiWbrazkAhZqkzMzs0FYoiuW%2BcrhxT3&X-Amz-Signature=0bcc112dc3475b82e783327cf79e0c56a67cae010070e26be2c0240f7c4973e5&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XGI4QSIR%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T032615Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDixxtYAlVgWEPokziPgvzcpVSSE5UaXlbB1P9Vq01rPQIgOZoDN70LAVxnFhf4pyPPEkHSZwtsIANwSLYMSouU3xEqiAQI5P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOBsYhgBgG1av4mAYircA2YYOb2XrxMBD9X9Iz98eYEdJIHp27DhwybwQ1kiZMa12X2dhwDZA9F7W223wDiWHsPpNsRYwznyCYFh3iLBPAlxpsFBHKVBwyKbrPQr7Xelotpwea59OwmlxMZvsTOsjEVy9s9FZUfqRJV0A%2FN7KKzANATYCagnG8oza%2FqOelkAn%2FhY3C0eyPjJJfzEvgoOvZ3PMNBlTEue1gPKLIwwsPvT1wuxQ3OiNGTsYxaTicOhHfocjeloXvEr65PTS4aNVUEViQ0lzhtIovA7QACbIPbaeJuyHqD4rfOIHNK3Ntdbb9a6irWF8ontTYOJ4lnUC%2FkeE9qcclnuk201PO%2FcSOGYThhTKX4QMj7hqdh8v3AEKua8tjnHrIYQqoZb7fc1x1tKylXChYPPdWXZO9CpWKvPSbP%2Fs1nRjiwB05juu319G1MzV4SaNWggC17d6lKdfmBJPhkAUdM2qQGWwj%2Faur9t4xqnRIIC34tRfnG2zxYMOKk%2FfL%2BmJn7wvrTusWg5RB%2BTCzEdBnVzrKvJh%2BoXzdIVguTIw%2FU4nZC8heIKfrQVDG3YZAfVt%2Baw%2FZssLoldjz4gO7%2BU5CP09jw2etcOpJri1qQGclyuXlFP5FaTKGz%2Bgi5HFP4qq%2BU7j46MMIXs5L0GOqUB40%2BSDRBgIfdlomsYdZqkXxYzzvhcirX%2FS8lLVutUqC4ttEMuPwpci0JbWqMrltuLIVCIdhXkiBkowUFoma6Sb%2BYs8duIpiWFiM7PfzGb60bpZC%2FXGVKmQT%2F5KBWkcCiBFws3UWLXyNSh1oWWO6QiA9HKa0AQMX3WRGhRzrcyYZs95z6iwLpWqsx9ghWKUBiWbrazkAhZqkzMzs0FYoiuW%2BcrhxT3&X-Amz-Signature=66a099145e5b2e4d4f7b5efa92ba94aeb521e1f16c0c2809c331ef430c265e13&X-Amz-SignedHeaders=host&x-id=GetObject)


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

