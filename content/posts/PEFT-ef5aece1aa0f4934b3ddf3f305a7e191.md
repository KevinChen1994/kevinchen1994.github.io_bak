---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB46644ZFHCNA%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250219T124318Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEHsaCXVzLXdlc3QtMiJIMEYCIQDbtC69U7xWz%2FQLJjX4eyU04OHWfmwgGthhql1w1eCc8gIhA\
  LREyXfI56JDTXH%2B3bo0d9xQLmfk1t1Ra6If3i24LVZtKogECKT%2F%2F%2F%2F%2F%2F%2F%2F%\
  2F%2FwEQABoMNjM3NDIzMTgzODA1Igx7AKLsghV0uxg%2BwHYq3ANtwMuK25h15NzYMs0TzY5p5sH\
  h6BoB8VQQ3R9oD9xlIwRfGWOuA%2Bsr6jJCIfef9AqdIOSuASta0%2FB0B6alDIJ%2F13qa7Z83sk\
  c1ZXFRvuFwHwru71YVWsEMCQthkUyXw0%2BcZFnoltLd8LI0akMeEo%2BQvht5RdL7VplZ2W762qk\
  aDZyGAej77qscgUDUwg0KYQ%2Biunp8CZY4K75rBVoy1EMmaAoZJ%2FrVIEkjMb5l8CN5tYKwu5BV\
  uwxYl0MC%2BmSEYXR2BeQSFiPfonzzjds9vKzn%2BAsL24DpzHeUNcAaNxETM6j72FlArEPOIsPAe\
  KjAE9qxga%2F2fkKUsqRguFAoVFHCoiqHRrqpU4qMJMe%2BA7Wve8BcdoeJMWKFAbgISBPrrg2rvW\
  dL9c9w5Od%2FeSmE8Go0IsJSzJLTI1n1PYn2xwYdw21NAwK31c9FJ2tvKIKfwUejsdqs31ItafX2e\
  zPEArzY2p%2FHodVFVgSR%2Bjcs63GMgZSfX6pZZ3PuZ3vgm5NNBK2NWfoE5SgooWg1OQm2KI9Vuc\
  %2B8B9u4T5OiRqJz8y%2F5VMJVa2b%2BaBsvzoBUl9CYH8BvoqhKkWfXw2N9cPmhHB6wqKrWHk5UX\
  qp%2FGQlI8yb7MeiLFlKgvtMSQLipvDD%2F%2Bta9BjqkAS6SkAwwxihIzWHmUEiK5%2BmU6sguFM\
  pt5ujqKdDqUZOXSFEf332lR%2F%2FBBkUocYWjlQZffXfo1prAlmcc%2BktuvmO4O%2FcerTM0JzP\
  BgksH25PSYySh3sjd2gly%2F7uRb1TWG4scmxBZKhzCqyymxXWZCkAAeEz8dklue2M8INkKh%2Fd5\
  a5i5glYUl1HKD%2FA43eWkRC5InG7JKoMnhvI18PUCRfwF9hlJ&X-Amz-Signature=d5b6144b54\
  fa21fb4a8e7c41f3f9f3cf77bbf6693fe6f12be003aaf4228d8620&X-Amz-SignedHeaders=ho\
  st&x-id=GetObject"
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
        redential=ASIAZI2LB4664QT2FOM4%2F20250219%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250219T124207Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJHMEUCIQC7%2FTDgnFvFUmcPKX0nSx%2B%2Be\
        8pA6nRXsxIYe69zPzT32wIgJNUaZgPUcVfHTYK%2Bmh%2Bq30ZjyhSbmNeUCzQf1U2AB%2F\
        wqiAQIpP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMmP2Fwz4\
        YzLJEU7ZSrcA5dG5zWGMFoEvu2igB1wopdbup4WsS5tUiI9Ys%2BwiWni%2FfgFL69x3umL\
        f7u6p6EcFNNrusbGZ2RGztpQ%2F1%2F6700dvti3n3DY5uxcxktbRzhm6Xio5ky%2FnIE1M\
        PIKTBMMLpuo2J3jyDJyW9in%2Fo8t5SSihQAfS2MPjVi85e1tvaPlAAFkqI2Sfzgk%2FeZG\
        zIDuEwy6nKQRzNJ2DEzj%2BYJreyrvDsohEzpo0tmBW4qV%2B%2BkWATQTwdxtICEbiV%2B\
        CzNUXraDUFUM8sXa7IHzeQG3PD3hb0fjUUYBF6bvg7IXYfNqOwqHsmMlIZ2v9CqwxyS1aq0\
        nRDry%2BMkSu%2FnPQipsUjFBoBPZe%2FyA7MrwNUGqix2RMVdVk59jjCQGvj2vDNrfMJR5\
        HL6HL5Ym694HicZENmBcWlj3WyajOoFYmDhL0oJx75Gv9nAAihY%2BiIM6PM7FqwPRxQb%2\
        FPlC4Lh13YsnWxRIPk%2FzfVMcknydb1bZ0Ni6rHNQ8yMLxC%2FjDWiRYxfTvlfjsNC68NJ\
        o9K7gKmu5qwi5NUJngA0TvA9lET%2Bz8muYKwXNf%2BB%2Fhkl76mEpZwH1S3M3q89tp1DU\
        rFbAc8JmmaJx3HpZF3zNXiN4raxE6t%2BC4dQK2TYSGIYAV%2B2z%2BGML%2F71r0GOqUBO\
        qg04abrYvZP1V6yDhjuuJU5yGBJcmjoUbzte9qnRs9I8Z20ABnGOTlh%2BADDBQPyDXtlSm\
        Q9uZ0bW4lb%2FfAeenkNbA905AgpeHV5hYesMeGexctCIgVnQ6KxxVwiTKzv9Cze5NX4VaR\
        6crJBNsEzK1tA3daXxCy7YHyfqQ9HmOqvEptM8jm68Azk1XDf5hUzbEieLPtZ%2B8H4MsOz\
        NV5%2FkU2PHAja&X-Amz-Signature=5dbc64591d272a1e050275f91126b00cd5d689f9\
        f1a5eb344e4b8f244593ef83&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-19T13:42:07.228Z"
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
UPDATE_TIME: "2025-02-19T12:43:23.895Z"
EXPIRY_TIME: "2025-02-19T13:43:16.021Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WXSSWUEF%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T124316Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJHMEUCIGZ1mDdFosPPx%2FKsNONswFDd1mrLFg%2FyIbkLANRD8ZNBAiEAhq0PTJoz%2FjHKXgpo84Ivfqg3aV54UQn7UBIdbhvp%2F6IqiAQIpP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNcXi23vdcQ1AVtJQircAxuIxx9KW9RdBAogPIybnAos4v6efVwXqUSxjOCs3Bo4il7wqM2m3dD80h8y1kVGZ64AHwXBm4yMr09pP62Use9OfJzO3xDCmGzeLPkxR%2Bm9dU%2Bpp0buh4NMuV7Sdxnlo1XNPtyfEMp8mMgyh%2BjQYNGYiUy%2FE6McC6lMYHy3PnLcfK9WQ0bL%2BKu8H2UrTC1%2FeRU%2FvMM0hbGuG%2Fpo6K%2FBoWNbI8idIm3Uq8p%2B9h70kIHwAB1a7p3li2uHcqKFosXKfBYAsyGo%2Fi8pRii7C9BABh8BsIbMs7JGy2eMUmdygHvabbIvj5gyqbo2Kl3Z5P74GQGWua%2FsjXzSrKrD9IgBPDhnd6mgf0C7UHsb0mkeZ9ElnMELxV6hltCzSokiin%2FB6MqUHyVhNdt7GAXvUEEZ%2BQXjBaQG%2Fi7zA0XIXPa1WztNsXCnLRU%2Fu%2BVo2MO1uBjawIw%2BQSykZR8ItKYvzylxB0pmN%2F12jp95Arn5S61fC4onvUu5J7%2Folh2LM4asoGzB9yspl1GsGea4wL5X7EqM%2BC3K%2FGNzoL54v2VEmHZGoknGOxLcWCMldcq%2BfiF0x7CCTQhv5riEUVNxi4%2Bo24MSxz%2B5ix9cZCYxATtNn3CimoatfEdOm0n0MuSF7ezQMOD61r0GOqUBWuOTM%2FziDpPIs6XWAce1DeG2QKY%2F0pNPK0i7ooBJNx3kBl1fVWpCdoSNFynZnvCBR%2BMZV97vzHT%2BKjASwWW3XCEX6UBF5cX49A0%2FfgovNcetG2KFSp2VjjOIf0H8MsuvBpcI72Ukn9GU5wk2uBFIg6DLUJSnRZz6nFPqks%2FnAfmkYNxTW6J%2Bn%2FoPEqvjmavPb6fgsc7m89u8r5CNgYKfM8u9WgIS&X-Amz-Signature=4bf2233f53ee71a4ac5acd683a34dfaef9d48710ebfda5095e6e5ff78da9f154&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WXSSWUEF%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T124316Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJHMEUCIGZ1mDdFosPPx%2FKsNONswFDd1mrLFg%2FyIbkLANRD8ZNBAiEAhq0PTJoz%2FjHKXgpo84Ivfqg3aV54UQn7UBIdbhvp%2F6IqiAQIpP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNcXi23vdcQ1AVtJQircAxuIxx9KW9RdBAogPIybnAos4v6efVwXqUSxjOCs3Bo4il7wqM2m3dD80h8y1kVGZ64AHwXBm4yMr09pP62Use9OfJzO3xDCmGzeLPkxR%2Bm9dU%2Bpp0buh4NMuV7Sdxnlo1XNPtyfEMp8mMgyh%2BjQYNGYiUy%2FE6McC6lMYHy3PnLcfK9WQ0bL%2BKu8H2UrTC1%2FeRU%2FvMM0hbGuG%2Fpo6K%2FBoWNbI8idIm3Uq8p%2B9h70kIHwAB1a7p3li2uHcqKFosXKfBYAsyGo%2Fi8pRii7C9BABh8BsIbMs7JGy2eMUmdygHvabbIvj5gyqbo2Kl3Z5P74GQGWua%2FsjXzSrKrD9IgBPDhnd6mgf0C7UHsb0mkeZ9ElnMELxV6hltCzSokiin%2FB6MqUHyVhNdt7GAXvUEEZ%2BQXjBaQG%2Fi7zA0XIXPa1WztNsXCnLRU%2Fu%2BVo2MO1uBjawIw%2BQSykZR8ItKYvzylxB0pmN%2F12jp95Arn5S61fC4onvUu5J7%2Folh2LM4asoGzB9yspl1GsGea4wL5X7EqM%2BC3K%2FGNzoL54v2VEmHZGoknGOxLcWCMldcq%2BfiF0x7CCTQhv5riEUVNxi4%2Bo24MSxz%2B5ix9cZCYxATtNn3CimoatfEdOm0n0MuSF7ezQMOD61r0GOqUBWuOTM%2FziDpPIs6XWAce1DeG2QKY%2F0pNPK0i7ooBJNx3kBl1fVWpCdoSNFynZnvCBR%2BMZV97vzHT%2BKjASwWW3XCEX6UBF5cX49A0%2FfgovNcetG2KFSp2VjjOIf0H8MsuvBpcI72Ukn9GU5wk2uBFIg6DLUJSnRZz6nFPqks%2FnAfmkYNxTW6J%2Bn%2FoPEqvjmavPb6fgsc7m89u8r5CNgYKfM8u9WgIS&X-Amz-Signature=d5200a9f53636eb6a50155353806acaa2217c572135a7e48a4c6aedfbf869743&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WXSSWUEF%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T124316Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJHMEUCIGZ1mDdFosPPx%2FKsNONswFDd1mrLFg%2FyIbkLANRD8ZNBAiEAhq0PTJoz%2FjHKXgpo84Ivfqg3aV54UQn7UBIdbhvp%2F6IqiAQIpP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNcXi23vdcQ1AVtJQircAxuIxx9KW9RdBAogPIybnAos4v6efVwXqUSxjOCs3Bo4il7wqM2m3dD80h8y1kVGZ64AHwXBm4yMr09pP62Use9OfJzO3xDCmGzeLPkxR%2Bm9dU%2Bpp0buh4NMuV7Sdxnlo1XNPtyfEMp8mMgyh%2BjQYNGYiUy%2FE6McC6lMYHy3PnLcfK9WQ0bL%2BKu8H2UrTC1%2FeRU%2FvMM0hbGuG%2Fpo6K%2FBoWNbI8idIm3Uq8p%2B9h70kIHwAB1a7p3li2uHcqKFosXKfBYAsyGo%2Fi8pRii7C9BABh8BsIbMs7JGy2eMUmdygHvabbIvj5gyqbo2Kl3Z5P74GQGWua%2FsjXzSrKrD9IgBPDhnd6mgf0C7UHsb0mkeZ9ElnMELxV6hltCzSokiin%2FB6MqUHyVhNdt7GAXvUEEZ%2BQXjBaQG%2Fi7zA0XIXPa1WztNsXCnLRU%2Fu%2BVo2MO1uBjawIw%2BQSykZR8ItKYvzylxB0pmN%2F12jp95Arn5S61fC4onvUu5J7%2Folh2LM4asoGzB9yspl1GsGea4wL5X7EqM%2BC3K%2FGNzoL54v2VEmHZGoknGOxLcWCMldcq%2BfiF0x7CCTQhv5riEUVNxi4%2Bo24MSxz%2B5ix9cZCYxATtNn3CimoatfEdOm0n0MuSF7ezQMOD61r0GOqUBWuOTM%2FziDpPIs6XWAce1DeG2QKY%2F0pNPK0i7ooBJNx3kBl1fVWpCdoSNFynZnvCBR%2BMZV97vzHT%2BKjASwWW3XCEX6UBF5cX49A0%2FfgovNcetG2KFSp2VjjOIf0H8MsuvBpcI72Ukn9GU5wk2uBFIg6DLUJSnRZz6nFPqks%2FnAfmkYNxTW6J%2Bn%2FoPEqvjmavPb6fgsc7m89u8r5CNgYKfM8u9WgIS&X-Amz-Signature=c1e5ab4a3c22564317f8bc4b59b6bb0785d248cbe218af04023e426dc5ca30a7&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WXSSWUEF%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T124316Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJHMEUCIGZ1mDdFosPPx%2FKsNONswFDd1mrLFg%2FyIbkLANRD8ZNBAiEAhq0PTJoz%2FjHKXgpo84Ivfqg3aV54UQn7UBIdbhvp%2F6IqiAQIpP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNcXi23vdcQ1AVtJQircAxuIxx9KW9RdBAogPIybnAos4v6efVwXqUSxjOCs3Bo4il7wqM2m3dD80h8y1kVGZ64AHwXBm4yMr09pP62Use9OfJzO3xDCmGzeLPkxR%2Bm9dU%2Bpp0buh4NMuV7Sdxnlo1XNPtyfEMp8mMgyh%2BjQYNGYiUy%2FE6McC6lMYHy3PnLcfK9WQ0bL%2BKu8H2UrTC1%2FeRU%2FvMM0hbGuG%2Fpo6K%2FBoWNbI8idIm3Uq8p%2B9h70kIHwAB1a7p3li2uHcqKFosXKfBYAsyGo%2Fi8pRii7C9BABh8BsIbMs7JGy2eMUmdygHvabbIvj5gyqbo2Kl3Z5P74GQGWua%2FsjXzSrKrD9IgBPDhnd6mgf0C7UHsb0mkeZ9ElnMELxV6hltCzSokiin%2FB6MqUHyVhNdt7GAXvUEEZ%2BQXjBaQG%2Fi7zA0XIXPa1WztNsXCnLRU%2Fu%2BVo2MO1uBjawIw%2BQSykZR8ItKYvzylxB0pmN%2F12jp95Arn5S61fC4onvUu5J7%2Folh2LM4asoGzB9yspl1GsGea4wL5X7EqM%2BC3K%2FGNzoL54v2VEmHZGoknGOxLcWCMldcq%2BfiF0x7CCTQhv5riEUVNxi4%2Bo24MSxz%2B5ix9cZCYxATtNn3CimoatfEdOm0n0MuSF7ezQMOD61r0GOqUBWuOTM%2FziDpPIs6XWAce1DeG2QKY%2F0pNPK0i7ooBJNx3kBl1fVWpCdoSNFynZnvCBR%2BMZV97vzHT%2BKjASwWW3XCEX6UBF5cX49A0%2FfgovNcetG2KFSp2VjjOIf0H8MsuvBpcI72Ukn9GU5wk2uBFIg6DLUJSnRZz6nFPqks%2FnAfmkYNxTW6J%2Bn%2FoPEqvjmavPb6fgsc7m89u8r5CNgYKfM8u9WgIS&X-Amz-Signature=2cd0d8579723f59d34ea0c83497d117c731e4bb352136236385882d143c2a00c&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WXSSWUEF%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T124316Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJHMEUCIGZ1mDdFosPPx%2FKsNONswFDd1mrLFg%2FyIbkLANRD8ZNBAiEAhq0PTJoz%2FjHKXgpo84Ivfqg3aV54UQn7UBIdbhvp%2F6IqiAQIpP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNcXi23vdcQ1AVtJQircAxuIxx9KW9RdBAogPIybnAos4v6efVwXqUSxjOCs3Bo4il7wqM2m3dD80h8y1kVGZ64AHwXBm4yMr09pP62Use9OfJzO3xDCmGzeLPkxR%2Bm9dU%2Bpp0buh4NMuV7Sdxnlo1XNPtyfEMp8mMgyh%2BjQYNGYiUy%2FE6McC6lMYHy3PnLcfK9WQ0bL%2BKu8H2UrTC1%2FeRU%2FvMM0hbGuG%2Fpo6K%2FBoWNbI8idIm3Uq8p%2B9h70kIHwAB1a7p3li2uHcqKFosXKfBYAsyGo%2Fi8pRii7C9BABh8BsIbMs7JGy2eMUmdygHvabbIvj5gyqbo2Kl3Z5P74GQGWua%2FsjXzSrKrD9IgBPDhnd6mgf0C7UHsb0mkeZ9ElnMELxV6hltCzSokiin%2FB6MqUHyVhNdt7GAXvUEEZ%2BQXjBaQG%2Fi7zA0XIXPa1WztNsXCnLRU%2Fu%2BVo2MO1uBjawIw%2BQSykZR8ItKYvzylxB0pmN%2F12jp95Arn5S61fC4onvUu5J7%2Folh2LM4asoGzB9yspl1GsGea4wL5X7EqM%2BC3K%2FGNzoL54v2VEmHZGoknGOxLcWCMldcq%2BfiF0x7CCTQhv5riEUVNxi4%2Bo24MSxz%2B5ix9cZCYxATtNn3CimoatfEdOm0n0MuSF7ezQMOD61r0GOqUBWuOTM%2FziDpPIs6XWAce1DeG2QKY%2F0pNPK0i7ooBJNx3kBl1fVWpCdoSNFynZnvCBR%2BMZV97vzHT%2BKjASwWW3XCEX6UBF5cX49A0%2FfgovNcetG2KFSp2VjjOIf0H8MsuvBpcI72Ukn9GU5wk2uBFIg6DLUJSnRZz6nFPqks%2FnAfmkYNxTW6J%2Bn%2FoPEqvjmavPb6fgsc7m89u8r5CNgYKfM8u9WgIS&X-Amz-Signature=7299fae0d70f7af72f150805d954a8c90a3514761d94a703d005e9006541df7a&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663NER6R6S%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T124317Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJIMEYCIQCn6aDD%2BbCSyYLS%2FrigBrKnELKCXrkmW%2B%2B%2BowCEbPPFjQIhAOxX0gDiEtXcTClt6ySwLtyhRdPFbAhBIrKtCLHl98ssKogECKT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igy5kAFTetD3Skf%2F7JQq3AMXdZ8bgn1l01aPa0jj%2FTCwCDByFLeXWWwIod%2BPolo8eyaiJ%2FGAFsa8GG6WcHjViL1TKequmAY%2FdFlZreX2z0EoQSJUG5Ep7eJLhQbpVsUFjz1BAWdWhhGiwndYGKkR04iD1EEodaaW7fuNL4GGbZWdaE8sblsY8meUFWn9FK05ntnzeyBuj%2FHTq7wG5JkZxfqa8Be4h8NLGmVjbdfXByDctYFop9zMDY1%2Be48KU5PWU4OYUnSX0%2FJi%2BWprVvby8WDUjSxOT9gVw9F4p8teTbe8z2O7d2zYNroy3xD5bC9r46MPd6Vfl%2BRI44tqVRXiFsjebTc3CoGva98ciggRLLUsCXHZtMqz2QZQ3LDbk8ZWeevZpmm%2FO7emL3Zf3G4%2BahwgeMi%2FkjDkIfl6qtZKyEScVgtysYSRHHvNbT1TkbnANdO%2BbKpywcXDo%2Fr34uiKkVjkbGObzzJj3xlV7pErP2GZK%2B45qQPf0dE65%2BAJ3Rn5qCbWJxJvNHtmUFYXmoGTH%2BWE3JyQevHdQJipEVyUzXb12%2BREcNERu3cJYeyHZwpUGHCQuVZwcYOxMrqwZmBbfoQQiOc7lp6kzT4oBmmfEJREDCIxnNkF2P86MZWrpyT3YAzkLAGMok4KHd4zsDDW%2Bta9BjqkASsViOyuUgkLFPbXJjCQgMy2D3hftzlqxlHjeYCamdwBdByvLU7oZKglKdepPhMukqfJZ6TolaZrKuHS%2FWUADlm5SsS5MIhaCiEOF%2B6y9y87GrSNV4AqZfPMRSBMCxA07570oBHnRSW2lNA658rtK1dZzTsa96GiMuIRRWWjlycPfCfRTvajzFkn1fKsJrDlZbtmEFJQcxD3YEyUvIDX71GxvZ%2Fg&X-Amz-Signature=b0bfade737ba1590932c49add26a94dbb2ab1aee1515bcc765f268948c106952&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QB6AMPHI%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T124317Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJHMEUCIQDpb0liMi4vK0CUnyf%2BVx%2B8Vp9m8RpR7y7s17GPbreD7QIgY7utrgMH0fZrie6Cw5sBOQJnvEagqw0KkDNxtnhNCkAqiAQIpP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDv7d7UtqFbiCXKdqSrcA4SZEM%2BTzr36JC4L6RcdrVYVmCGqvqJeuorRyRHXLxAJTqPo3cMz2g%2BJppHg9ldmWR%2FU799yCHSriE9KVAX3ckjCCmBtfkKDjcUb6JuDB0nLq6JQmG5nB%2BsMKVdicTuOJc869OLIempk1LhsZ1hXHSxFBxHXsg4zc5MaXw%2BR7q2bwlpQzSbj3llgH9IIF20mNmoDlNrL3XqwUKwQO34I7ujpr7I1Dmw10vOz3oiBpWu3HlXJjAwypQ7v%2BRktBsxvKBX1%2Bh0RQbKFvJdZW8hkE5y%2Bf8xtWcEtwTxYXkopBhtod5%2BOcgqsPVHbhBvStOkVPcn%2Bc8vMTgqtapIIR3fa%2Fdp71doSvJJef%2Fvul%2Fn6RubeVdvlmv0IEK5QbHv0OsTJgAX0WllRBsrfWVaiUsWvtpSXeOdvlLtxttMNl1fz8F8lC8PvVqGSIgU%2Bh%2FVeHGrcagBemPF6w3Q0apHdy1CseIItQuYRe%2BlzDg0EEtXiGdrFINoVMH8gXZ8944uXIOpXyZ5CrBZQ22isba%2F3VsZyzOG2Ie7WRnGSWqGmdXqUxrfu9o25x%2FK%2BXLWq2iAgonpApn%2B%2BDdf5pg%2BFXO0lq12GfpC3YjYF6NV5bd0CoUxGBRfYy04JT%2FZ04qg1%2FLbPMIr71r0GOqUBIjxnqX3UeFmkphC67NqfnsMarF8ugpcMJ8EyHL8TISfYEjoxXq1Z7Sig9eCs0zQdDre%2BesMejZ85x3xQJpF%2B%2Bmr4KMrxOWEJV%2F7BrYJupXQ%2F4pY%2B8TeEr98wvw4S9Hyxd30qle0Jof3f8uAwPxHky9zbpQjWfN7R75PMJDcjQLbyP3MoKdog3Rzm%2F2XIJ6Fos%2F%2F530AfYeaXpFOVVcv0sNqOEgwx&X-Amz-Signature=d53adab409973f89285a940cf48aa52eb7362a81e20b476f6ea19f53c77feb03&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WXSSWUEF%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T124316Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJHMEUCIGZ1mDdFosPPx%2FKsNONswFDd1mrLFg%2FyIbkLANRD8ZNBAiEAhq0PTJoz%2FjHKXgpo84Ivfqg3aV54UQn7UBIdbhvp%2F6IqiAQIpP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNcXi23vdcQ1AVtJQircAxuIxx9KW9RdBAogPIybnAos4v6efVwXqUSxjOCs3Bo4il7wqM2m3dD80h8y1kVGZ64AHwXBm4yMr09pP62Use9OfJzO3xDCmGzeLPkxR%2Bm9dU%2Bpp0buh4NMuV7Sdxnlo1XNPtyfEMp8mMgyh%2BjQYNGYiUy%2FE6McC6lMYHy3PnLcfK9WQ0bL%2BKu8H2UrTC1%2FeRU%2FvMM0hbGuG%2Fpo6K%2FBoWNbI8idIm3Uq8p%2B9h70kIHwAB1a7p3li2uHcqKFosXKfBYAsyGo%2Fi8pRii7C9BABh8BsIbMs7JGy2eMUmdygHvabbIvj5gyqbo2Kl3Z5P74GQGWua%2FsjXzSrKrD9IgBPDhnd6mgf0C7UHsb0mkeZ9ElnMELxV6hltCzSokiin%2FB6MqUHyVhNdt7GAXvUEEZ%2BQXjBaQG%2Fi7zA0XIXPa1WztNsXCnLRU%2Fu%2BVo2MO1uBjawIw%2BQSykZR8ItKYvzylxB0pmN%2F12jp95Arn5S61fC4onvUu5J7%2Folh2LM4asoGzB9yspl1GsGea4wL5X7EqM%2BC3K%2FGNzoL54v2VEmHZGoknGOxLcWCMldcq%2BfiF0x7CCTQhv5riEUVNxi4%2Bo24MSxz%2B5ix9cZCYxATtNn3CimoatfEdOm0n0MuSF7ezQMOD61r0GOqUBWuOTM%2FziDpPIs6XWAce1DeG2QKY%2F0pNPK0i7ooBJNx3kBl1fVWpCdoSNFynZnvCBR%2BMZV97vzHT%2BKjASwWW3XCEX6UBF5cX49A0%2FfgovNcetG2KFSp2VjjOIf0H8MsuvBpcI72Ukn9GU5wk2uBFIg6DLUJSnRZz6nFPqks%2FnAfmkYNxTW6J%2Bn%2FoPEqvjmavPb6fgsc7m89u8r5CNgYKfM8u9WgIS&X-Amz-Signature=d7cf3fe1f79eda6b020ee1e997d43da98c25f88ebe9f39069081ce46596b7f52&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WXSSWUEF%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T124316Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJHMEUCIGZ1mDdFosPPx%2FKsNONswFDd1mrLFg%2FyIbkLANRD8ZNBAiEAhq0PTJoz%2FjHKXgpo84Ivfqg3aV54UQn7UBIdbhvp%2F6IqiAQIpP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNcXi23vdcQ1AVtJQircAxuIxx9KW9RdBAogPIybnAos4v6efVwXqUSxjOCs3Bo4il7wqM2m3dD80h8y1kVGZ64AHwXBm4yMr09pP62Use9OfJzO3xDCmGzeLPkxR%2Bm9dU%2Bpp0buh4NMuV7Sdxnlo1XNPtyfEMp8mMgyh%2BjQYNGYiUy%2FE6McC6lMYHy3PnLcfK9WQ0bL%2BKu8H2UrTC1%2FeRU%2FvMM0hbGuG%2Fpo6K%2FBoWNbI8idIm3Uq8p%2B9h70kIHwAB1a7p3li2uHcqKFosXKfBYAsyGo%2Fi8pRii7C9BABh8BsIbMs7JGy2eMUmdygHvabbIvj5gyqbo2Kl3Z5P74GQGWua%2FsjXzSrKrD9IgBPDhnd6mgf0C7UHsb0mkeZ9ElnMELxV6hltCzSokiin%2FB6MqUHyVhNdt7GAXvUEEZ%2BQXjBaQG%2Fi7zA0XIXPa1WztNsXCnLRU%2Fu%2BVo2MO1uBjawIw%2BQSykZR8ItKYvzylxB0pmN%2F12jp95Arn5S61fC4onvUu5J7%2Folh2LM4asoGzB9yspl1GsGea4wL5X7EqM%2BC3K%2FGNzoL54v2VEmHZGoknGOxLcWCMldcq%2BfiF0x7CCTQhv5riEUVNxi4%2Bo24MSxz%2B5ix9cZCYxATtNn3CimoatfEdOm0n0MuSF7ezQMOD61r0GOqUBWuOTM%2FziDpPIs6XWAce1DeG2QKY%2F0pNPK0i7ooBJNx3kBl1fVWpCdoSNFynZnvCBR%2BMZV97vzHT%2BKjASwWW3XCEX6UBF5cX49A0%2FfgovNcetG2KFSp2VjjOIf0H8MsuvBpcI72Ukn9GU5wk2uBFIg6DLUJSnRZz6nFPqks%2FnAfmkYNxTW6J%2Bn%2FoPEqvjmavPb6fgsc7m89u8r5CNgYKfM8u9WgIS&X-Amz-Signature=c4fcf0e068f85d47ed13175bff02ca4d983a4ab35aab8c6becd0956afcf86335&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WXSSWUEF%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T124316Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHsaCXVzLXdlc3QtMiJHMEUCIGZ1mDdFosPPx%2FKsNONswFDd1mrLFg%2FyIbkLANRD8ZNBAiEAhq0PTJoz%2FjHKXgpo84Ivfqg3aV54UQn7UBIdbhvp%2F6IqiAQIpP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNcXi23vdcQ1AVtJQircAxuIxx9KW9RdBAogPIybnAos4v6efVwXqUSxjOCs3Bo4il7wqM2m3dD80h8y1kVGZ64AHwXBm4yMr09pP62Use9OfJzO3xDCmGzeLPkxR%2Bm9dU%2Bpp0buh4NMuV7Sdxnlo1XNPtyfEMp8mMgyh%2BjQYNGYiUy%2FE6McC6lMYHy3PnLcfK9WQ0bL%2BKu8H2UrTC1%2FeRU%2FvMM0hbGuG%2Fpo6K%2FBoWNbI8idIm3Uq8p%2B9h70kIHwAB1a7p3li2uHcqKFosXKfBYAsyGo%2Fi8pRii7C9BABh8BsIbMs7JGy2eMUmdygHvabbIvj5gyqbo2Kl3Z5P74GQGWua%2FsjXzSrKrD9IgBPDhnd6mgf0C7UHsb0mkeZ9ElnMELxV6hltCzSokiin%2FB6MqUHyVhNdt7GAXvUEEZ%2BQXjBaQG%2Fi7zA0XIXPa1WztNsXCnLRU%2Fu%2BVo2MO1uBjawIw%2BQSykZR8ItKYvzylxB0pmN%2F12jp95Arn5S61fC4onvUu5J7%2Folh2LM4asoGzB9yspl1GsGea4wL5X7EqM%2BC3K%2FGNzoL54v2VEmHZGoknGOxLcWCMldcq%2BfiF0x7CCTQhv5riEUVNxi4%2Bo24MSxz%2B5ix9cZCYxATtNn3CimoatfEdOm0n0MuSF7ezQMOD61r0GOqUBWuOTM%2FziDpPIs6XWAce1DeG2QKY%2F0pNPK0i7ooBJNx3kBl1fVWpCdoSNFynZnvCBR%2BMZV97vzHT%2BKjASwWW3XCEX6UBF5cX49A0%2FfgovNcetG2KFSp2VjjOIf0H8MsuvBpcI72Ukn9GU5wk2uBFIg6DLUJSnRZz6nFPqks%2FnAfmkYNxTW6J%2Bn%2FoPEqvjmavPb6fgsc7m89u8r5CNgYKfM8u9WgIS&X-Amz-Signature=0d780134f7cc03e819c250c95a24641217ee62d666f4564642aa6c37f7936e19&X-Amz-SignedHeaders=host&x-id=GetObject)


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

