---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4663EIN53VH%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250215T102314Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEBoaCXVzLXdlc3QtMiJIMEYCIQDr3Zvm1prNQ7vKDrb9EJxJ%2BXQpbTQKlPx81o8XnWNXswIhA\
  Md%2Bn5hmOnGzm%2FeqWOPACNK%2BfRcujbc1fLURsBFitZNMKv8DCEMQABoMNjM3NDIzMTgzODA1\
  Igy%2B%2BOUQPO0htCtw3Wgq3AOTD0cm%2BK9AJDvRADbOON6Tw0yNpl9y%2BRaPJ%2FcqG7GAHzw\
  lgN7Bl0hXSfemM1qzX6rdBbQLzZuHpsV5u76J3SLEl50l4fNs4DFi1VMhbJDPjBiyJ7Z7KwgdzBcP\
  vcLU1uTJIHjxMHDaofRS2ra9onxFpCsLon2lw8tpe8KvR2cQfNskyxDInjRih4gCnax1tdmoeHhCS\
  uCOGtcri1NBMiYKIdllqxUut0BiQdJ16nVeu0IMQHSQuEh7LmfxUeTdcMmWW%2BBZuCxvCdshJXU9\
  VgaR0lo6z50hlQl2pWDws4Rd5d0tm%2BXctiAeCQBGWBUjxgtWg1g88RTme1Hi0gzEBVi0fPSgyyD\
  o8O6aO%2FwU6cA%2Fyi2N%2FY1817xxa1fJpDAUWKzCrhoNxMOXNvcCUBrGqis4er6UpS%2BGguip\
  XJit5Pnk%2BEHJKGG18yWA6yNCFOZ56eNHqX1rlVjYCbsYvWk%2FQIbxO0x9lP%2Bld6Gbx1ahS9h\
  nF6C32oHgrHUPZ6aUB2m2JR7Khyx43U1rIo8%2FgWbuqUvbB33IWZyYIOC9VG0mEzsejMGcaoCf0h\
  qTHtT7RAXdkUtnpqR5V1GbrIIUzA6tQ8TDgDsnQ2xldAznJGiadXJ%2FoBkPgJYDLoj6lhB7kDC4v\
  sG9BjqkAbG3YKtzZ3DhqTBS%2BHjsqGTfoSa133S3VtIVQ%2F7ktqeMo1J0KmVdYE0vUbHZcsqEAV\
  R20nEXa2xStzONS5fk9Zgm9sjJdZsdBzm6E%2BbcQMGUTvYP4D59uvinSHKgpcJxKCWTUpLRXkS9F\
  g8zAaVZQ8KJ7m5kFJVhyy3%2FwpOiF%2BYQlNOGiC5mtwDySaCTajqQ708l7ReoAeuVpJ9EtjkCkg\
  ya2G%2Bx&X-Amz-Signature=65f356aa38b2078dffd07cafebfc3f9a490492c2cce82cc0a331\
  9a42ceb880fd&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466SKEPL5YT%2F20250215%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250215T102200Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEBoaCXVzLXdlc3QtMiJIMEYCIQCL9UvuiWgFSNXBJMGX%2FGop8X2ns\
        Pha%2F8NlZfCkRjXcPQIhAMN0Xfjn7zPOOiHHHd9lCFKhs95aYM2Iq4IKM1tT6u7FKv8DCE\
        MQABoMNjM3NDIzMTgzODA1IgwvJwZso%2B25q8PdsZcq3AMX4W7H6ZOA3eNfj7X8WHTPkCj\
        Qmbj%2B%2FwkjXgpeatN5GUdKUew1ciy0mWvbHB63jdl1f5%2FQgmDoTXOhL%2FtcW9B6Pk\
        %2FqOcI2vRlww1Wsz6I0XmRMwsh9W69gGxCePXSNjOPsX6TEOSITsM9wqzd1fIBmXsnu4Ji\
        jZNcXj6XpsafoAN68CQwzbQpM141umGD89aAUDdoYx0gQiOQgWk4PNiCCmstUwdVrwxd0vn\
        LHb%2BtBmiFh4Mt5Nqe76O6l2GmEKNyW9CQvrftiLVtYcCrRTwUSxsx4Vu9ieSikS2syLIQ\
        At%2Bw1ooMtsvLpbsOoerUbaa7b4MZ%2BcjhTu8Ilhy%2FtfqSp1HVCXTde4%2Bv97eeUky\
        nKawhiSMLjlb8dnvyVGvFDiikef26P0GKloB76%2Bv70hO3KCcQ6nLGax3hk2ymmmx8xJ8O\
        7ZSN7McIESQCGCDObHEkBiy8AHcPNFHbyzavqJlIu2uJZUYoZ3w91x4P5oaLw10G8vTmERk\
        nna3lAIzozmym5%2BYP1pOv2%2FyYolyoSwCg%2By07OgFR6ndz0tSTiblI6LeqfSbzlbUr\
        TgWR43OyxzUZLTiPD%2BwizdaowuYac09GQj3orjGgeBMtah4skYoR63PuAjvBG2PjtW7us\
        vzDcvsG9BjqkAWuILkeEgShz60PAk6ZzG3o7%2B0ObIXqMz2A3ciJwblJwNg1Gowa1tnHH%\
        2B3KWHoL5vNUQ8rYdLaKIINrlqqyAwp5k6nmMaUZgR4zo5jUUjtpCgzUOykDgmzT4riri5v\
        jtyWHgKhlUiwUIi4uCey8oxvcmwnIiOSaFQvk7sR1L28g4f3i0o1W%2BuoDQCax3WXw52dI\
        VfHtKNSkGw10kJsDJJ0XKljJq&X-Amz-Signature=da2e44a7da650283be0d303dcbad5\
        714e4ef1274d7e063c2daf9b356c39a55df&X-Amz-SignedHeaders=host&x-id=GetOb\
        ject"
      expiry_time: "2025-02-15T11:22:00.526Z"
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
UPDATE_TIME: "2025-02-15T10:23:18.813Z"
EXPIRY_TIME: "2025-02-15T11:23:11.211Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Y5LGXXCG%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T102311Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBoaCXVzLXdlc3QtMiJHMEUCIEZnyVGE1TJNVHLGpg0D9XYYXq4AFna%2BD9YOn0%2F7DpsYAiEA%2F8RohDRoJAUvGM4Q%2BE5txTSEUFooRJT4KYAKZ2wGZyQq%2FwMIQxAAGgw2Mzc0MjMxODM4MDUiDF%2B0JOy62%2FDIcrUFASrcA49%2FRbcMBbigmSTFxC3TdvIvFR%2BS97GpCQJH4OScByLaRye7hoBhT7S%2BAtymTAdyS%2FDLolPkH8VFf4hex4jlaRX0o2Lgevwd7cn2RBXtszGWiQKTgg5q4FfAtH54%2B%2Bmqc8%2Bu1OmegSpzYSL03te6UaO7TIFJGlqkyg52Wp1zcpJ%2BJyWHrT%2BzsJy%2BsvbIJcncQ1ncQEexwpnPgy%2BC1MCDrBQtooNdfDvi3bTTNQQggsJbN68J86mbe70XbLHjSy%2B1keMKZJvY3tFbPVlUhtjNZsi0Ss3fch2IGuu4v%2B7NzMX6q30NNB9Ka3%2FIuEN%2Fa2sMiZNjRqFevGPMGjkkKVt1eA%2FCdxpuWSHzVtYZzlLilJCV%2F1JykKWEVhgREaVZwsoRTeO4xAtWmM7tysYZvFCAbkqaD3z6XNsZc0kof9Vl4grj6%2BzoDxKgMYDOLOpzBHTrG29NceDEbGkUgXhhPJntaZAWId9%2BQmxaPvKULLHwu2r52f%2BDRfGlGZx%2FL4JAkVjrVPGWu9qumcWGW7p1RaiS4So%2BHt56SDCfgo7TBcsU1t9BF69jlbTfQ5u6tToHfg5PdG%2FpAxVqSB84UjE02Y303Y4doNjzUfRqTLuvZGiAakhM1eZhErlmoMpd%2B8f0MLi%2Bwb0GOqUB3130peF6LSezD4MLm7ROGWDOw1s%2BiECE7HSzvc0qurXpuFC%2FDCm8KnBVGokKxKe1%2ByW4sybXhYG2MaOxTtz9bMklSSGOFCrX96hzuQpU7DxHKbgU0vKNwBn4MtiY0uIL%2FOy6bY9Q6yZwHr5591sBahk2pLZk02XxHMDN9kfR3LmKMqOUxoDE0Oq5MW3UREQGgnwj0BmQ9GCTdNKVUcPCiZ5C3xAj&X-Amz-Signature=e77051088cfa2fbe75387448a0ffb346b97dc4eca46f46c5a0ef31226bba32f9&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Y5LGXXCG%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T102311Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBoaCXVzLXdlc3QtMiJHMEUCIEZnyVGE1TJNVHLGpg0D9XYYXq4AFna%2BD9YOn0%2F7DpsYAiEA%2F8RohDRoJAUvGM4Q%2BE5txTSEUFooRJT4KYAKZ2wGZyQq%2FwMIQxAAGgw2Mzc0MjMxODM4MDUiDF%2B0JOy62%2FDIcrUFASrcA49%2FRbcMBbigmSTFxC3TdvIvFR%2BS97GpCQJH4OScByLaRye7hoBhT7S%2BAtymTAdyS%2FDLolPkH8VFf4hex4jlaRX0o2Lgevwd7cn2RBXtszGWiQKTgg5q4FfAtH54%2B%2Bmqc8%2Bu1OmegSpzYSL03te6UaO7TIFJGlqkyg52Wp1zcpJ%2BJyWHrT%2BzsJy%2BsvbIJcncQ1ncQEexwpnPgy%2BC1MCDrBQtooNdfDvi3bTTNQQggsJbN68J86mbe70XbLHjSy%2B1keMKZJvY3tFbPVlUhtjNZsi0Ss3fch2IGuu4v%2B7NzMX6q30NNB9Ka3%2FIuEN%2Fa2sMiZNjRqFevGPMGjkkKVt1eA%2FCdxpuWSHzVtYZzlLilJCV%2F1JykKWEVhgREaVZwsoRTeO4xAtWmM7tysYZvFCAbkqaD3z6XNsZc0kof9Vl4grj6%2BzoDxKgMYDOLOpzBHTrG29NceDEbGkUgXhhPJntaZAWId9%2BQmxaPvKULLHwu2r52f%2BDRfGlGZx%2FL4JAkVjrVPGWu9qumcWGW7p1RaiS4So%2BHt56SDCfgo7TBcsU1t9BF69jlbTfQ5u6tToHfg5PdG%2FpAxVqSB84UjE02Y303Y4doNjzUfRqTLuvZGiAakhM1eZhErlmoMpd%2B8f0MLi%2Bwb0GOqUB3130peF6LSezD4MLm7ROGWDOw1s%2BiECE7HSzvc0qurXpuFC%2FDCm8KnBVGokKxKe1%2ByW4sybXhYG2MaOxTtz9bMklSSGOFCrX96hzuQpU7DxHKbgU0vKNwBn4MtiY0uIL%2FOy6bY9Q6yZwHr5591sBahk2pLZk02XxHMDN9kfR3LmKMqOUxoDE0Oq5MW3UREQGgnwj0BmQ9GCTdNKVUcPCiZ5C3xAj&X-Amz-Signature=c8b9c879273d346b7ae1288cf7732007e7b9ba5aa700bedc1fc12b8a5c3bd0d9&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Y5LGXXCG%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T102311Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBoaCXVzLXdlc3QtMiJHMEUCIEZnyVGE1TJNVHLGpg0D9XYYXq4AFna%2BD9YOn0%2F7DpsYAiEA%2F8RohDRoJAUvGM4Q%2BE5txTSEUFooRJT4KYAKZ2wGZyQq%2FwMIQxAAGgw2Mzc0MjMxODM4MDUiDF%2B0JOy62%2FDIcrUFASrcA49%2FRbcMBbigmSTFxC3TdvIvFR%2BS97GpCQJH4OScByLaRye7hoBhT7S%2BAtymTAdyS%2FDLolPkH8VFf4hex4jlaRX0o2Lgevwd7cn2RBXtszGWiQKTgg5q4FfAtH54%2B%2Bmqc8%2Bu1OmegSpzYSL03te6UaO7TIFJGlqkyg52Wp1zcpJ%2BJyWHrT%2BzsJy%2BsvbIJcncQ1ncQEexwpnPgy%2BC1MCDrBQtooNdfDvi3bTTNQQggsJbN68J86mbe70XbLHjSy%2B1keMKZJvY3tFbPVlUhtjNZsi0Ss3fch2IGuu4v%2B7NzMX6q30NNB9Ka3%2FIuEN%2Fa2sMiZNjRqFevGPMGjkkKVt1eA%2FCdxpuWSHzVtYZzlLilJCV%2F1JykKWEVhgREaVZwsoRTeO4xAtWmM7tysYZvFCAbkqaD3z6XNsZc0kof9Vl4grj6%2BzoDxKgMYDOLOpzBHTrG29NceDEbGkUgXhhPJntaZAWId9%2BQmxaPvKULLHwu2r52f%2BDRfGlGZx%2FL4JAkVjrVPGWu9qumcWGW7p1RaiS4So%2BHt56SDCfgo7TBcsU1t9BF69jlbTfQ5u6tToHfg5PdG%2FpAxVqSB84UjE02Y303Y4doNjzUfRqTLuvZGiAakhM1eZhErlmoMpd%2B8f0MLi%2Bwb0GOqUB3130peF6LSezD4MLm7ROGWDOw1s%2BiECE7HSzvc0qurXpuFC%2FDCm8KnBVGokKxKe1%2ByW4sybXhYG2MaOxTtz9bMklSSGOFCrX96hzuQpU7DxHKbgU0vKNwBn4MtiY0uIL%2FOy6bY9Q6yZwHr5591sBahk2pLZk02XxHMDN9kfR3LmKMqOUxoDE0Oq5MW3UREQGgnwj0BmQ9GCTdNKVUcPCiZ5C3xAj&X-Amz-Signature=80117d94ab516ec9fbe5bccab0d79dd7ff474adb72fd68f6c053ec377222a0d8&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Y5LGXXCG%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T102311Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBoaCXVzLXdlc3QtMiJHMEUCIEZnyVGE1TJNVHLGpg0D9XYYXq4AFna%2BD9YOn0%2F7DpsYAiEA%2F8RohDRoJAUvGM4Q%2BE5txTSEUFooRJT4KYAKZ2wGZyQq%2FwMIQxAAGgw2Mzc0MjMxODM4MDUiDF%2B0JOy62%2FDIcrUFASrcA49%2FRbcMBbigmSTFxC3TdvIvFR%2BS97GpCQJH4OScByLaRye7hoBhT7S%2BAtymTAdyS%2FDLolPkH8VFf4hex4jlaRX0o2Lgevwd7cn2RBXtszGWiQKTgg5q4FfAtH54%2B%2Bmqc8%2Bu1OmegSpzYSL03te6UaO7TIFJGlqkyg52Wp1zcpJ%2BJyWHrT%2BzsJy%2BsvbIJcncQ1ncQEexwpnPgy%2BC1MCDrBQtooNdfDvi3bTTNQQggsJbN68J86mbe70XbLHjSy%2B1keMKZJvY3tFbPVlUhtjNZsi0Ss3fch2IGuu4v%2B7NzMX6q30NNB9Ka3%2FIuEN%2Fa2sMiZNjRqFevGPMGjkkKVt1eA%2FCdxpuWSHzVtYZzlLilJCV%2F1JykKWEVhgREaVZwsoRTeO4xAtWmM7tysYZvFCAbkqaD3z6XNsZc0kof9Vl4grj6%2BzoDxKgMYDOLOpzBHTrG29NceDEbGkUgXhhPJntaZAWId9%2BQmxaPvKULLHwu2r52f%2BDRfGlGZx%2FL4JAkVjrVPGWu9qumcWGW7p1RaiS4So%2BHt56SDCfgo7TBcsU1t9BF69jlbTfQ5u6tToHfg5PdG%2FpAxVqSB84UjE02Y303Y4doNjzUfRqTLuvZGiAakhM1eZhErlmoMpd%2B8f0MLi%2Bwb0GOqUB3130peF6LSezD4MLm7ROGWDOw1s%2BiECE7HSzvc0qurXpuFC%2FDCm8KnBVGokKxKe1%2ByW4sybXhYG2MaOxTtz9bMklSSGOFCrX96hzuQpU7DxHKbgU0vKNwBn4MtiY0uIL%2FOy6bY9Q6yZwHr5591sBahk2pLZk02XxHMDN9kfR3LmKMqOUxoDE0Oq5MW3UREQGgnwj0BmQ9GCTdNKVUcPCiZ5C3xAj&X-Amz-Signature=aaa5c9329530f99656ce7fb56541136e598e4a33592e99891b9a9818510a7268&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Y5LGXXCG%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T102311Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBoaCXVzLXdlc3QtMiJHMEUCIEZnyVGE1TJNVHLGpg0D9XYYXq4AFna%2BD9YOn0%2F7DpsYAiEA%2F8RohDRoJAUvGM4Q%2BE5txTSEUFooRJT4KYAKZ2wGZyQq%2FwMIQxAAGgw2Mzc0MjMxODM4MDUiDF%2B0JOy62%2FDIcrUFASrcA49%2FRbcMBbigmSTFxC3TdvIvFR%2BS97GpCQJH4OScByLaRye7hoBhT7S%2BAtymTAdyS%2FDLolPkH8VFf4hex4jlaRX0o2Lgevwd7cn2RBXtszGWiQKTgg5q4FfAtH54%2B%2Bmqc8%2Bu1OmegSpzYSL03te6UaO7TIFJGlqkyg52Wp1zcpJ%2BJyWHrT%2BzsJy%2BsvbIJcncQ1ncQEexwpnPgy%2BC1MCDrBQtooNdfDvi3bTTNQQggsJbN68J86mbe70XbLHjSy%2B1keMKZJvY3tFbPVlUhtjNZsi0Ss3fch2IGuu4v%2B7NzMX6q30NNB9Ka3%2FIuEN%2Fa2sMiZNjRqFevGPMGjkkKVt1eA%2FCdxpuWSHzVtYZzlLilJCV%2F1JykKWEVhgREaVZwsoRTeO4xAtWmM7tysYZvFCAbkqaD3z6XNsZc0kof9Vl4grj6%2BzoDxKgMYDOLOpzBHTrG29NceDEbGkUgXhhPJntaZAWId9%2BQmxaPvKULLHwu2r52f%2BDRfGlGZx%2FL4JAkVjrVPGWu9qumcWGW7p1RaiS4So%2BHt56SDCfgo7TBcsU1t9BF69jlbTfQ5u6tToHfg5PdG%2FpAxVqSB84UjE02Y303Y4doNjzUfRqTLuvZGiAakhM1eZhErlmoMpd%2B8f0MLi%2Bwb0GOqUB3130peF6LSezD4MLm7ROGWDOw1s%2BiECE7HSzvc0qurXpuFC%2FDCm8KnBVGokKxKe1%2ByW4sybXhYG2MaOxTtz9bMklSSGOFCrX96hzuQpU7DxHKbgU0vKNwBn4MtiY0uIL%2FOy6bY9Q6yZwHr5591sBahk2pLZk02XxHMDN9kfR3LmKMqOUxoDE0Oq5MW3UREQGgnwj0BmQ9GCTdNKVUcPCiZ5C3xAj&X-Amz-Signature=e0f50f1672fff37030e84064be58073d35a365c5022746e13c67848f2acf8e73&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WN2CTWVS%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T102312Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBoaCXVzLXdlc3QtMiJHMEUCIFPjbgHsJLYkvd%2F%2BxVUJjqHeeQAu9a%2B7TKfpizPdgQzkAiEAhlUYeKGm5qPgBJxjoArSQrMlMkfwCp5RfEYZ16NQWqMq%2FwMIQxAAGgw2Mzc0MjMxODM4MDUiDPpzWizUn7n%2FlIHzXSrcA%2FD0EULrk39MD5aL0bpBI%2BIK1xUqsqsCOhZhui0jFMtTDCiBONcVJaLx4cPdMXx7IBpRrlenrgb4DS8V1hX7vfUtt1L9LN4u8eom1JphuUhGxBr65e1BRU6wKwku0y3gTMvgqyiy5GY5phzwfI%2FGwMPOYc6Sx6dbhJs6spWv1qwbwfoOPlesZIWgziSaKBfL5VST7FVrmprIPC5g0YADfffVIRn84r4HVak9gE4PS1mqotzon1Vlm2ObC029D5Rm3IuFZSxz9nGDAY8EdSqXCM14XigxRwFuIiD1ImThkxbS0oGXbl7Mdj6X87K9Lq%2FJZBi7OfBRC1D0I5OjAx6eUjsgZ%2F4PHsXaG5WPF3mT06EJhkzgfqpt5YWVfSSeOFt7Eix8AWlwGI28DIUt1ImJn6B1yZIW1WtifqKQqYniCkfhGlw8DGoyXHTmjMn3%2BtQ9xaj%2FXH07WHod0syrD9OfpGYB%2FaRtxo6B9pBucYoe0%2B%2FgkfyH%2FBkCvijIH3ZZsu1oiQl4xhcFoJj7obSPhn5kMynKV3wneTEKlspeLhzmboOECeLnGOMG4QwPi0X95oey9G4%2FCfEt%2F6DgZ1f7Pcp5U4%2B0xN6ly5cQqykDdvVXIUfdV1n5hqwNHO2F%2BXFXMPy%2Bwb0GOqUBmu7QgSLwhO9e126Ancjpx1Vb1c2U3FIkxMm2nwi3jldOdHDywnvShpZshpH1bb7GL64T6vP05Cqf9f6vTxrNfMfFmZiiI8jQGCvDp1xpThROf2WRdVR8QDCuDc7ZpohSRcHtWMXo9UdAEeAjbXCUZv0KQY4y%2FLTKt5p5a8uCzBgv5fJnMvwdOJW2u4eKvjTg9cBLaLrEZJx9LgjKkl1ronjlll5m&X-Amz-Signature=deaa634d1fda78623597eaa0b7e38b4135bff368c07da6d556a4a6081fe12e51&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VYQTMAHL%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T102313Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBoaCXVzLXdlc3QtMiJGMEQCIH33m3Bn8TSxTpod48rp9tRCzDNh8juVFQs7mPXGtc87AiB3ZRsBviUCHr3PKLU64%2BvsEdejZhtLBpjCRJhF11T82Sr%2FAwhDEAAaDDYzNzQyMzE4MzgwNSIM9F2QLEY7nDwli5IVKtwD4uK6Ds4p3bVFw8cflVSnrWZj91q2y%2BTV4OUC5LQXhdNC%2F2xKVYVbX%2F2YqGmO2c0IWO2vKVD3XBrBGMzWnZp%2BFds0IVEA8945mJD5lR0qora8Kbrup4lg754Crv4cFvK3xmh3tCGhmKxPtgZn9V8UVLszxqZyy4FOlDG08R4ggdjoUNTmgtV9GRcIfMH21rGKSvFkmGu223CbafNluNM1L8wuy0C3Dc0zsXuMggDmGmJvAdoXrsibhguj7kG5ZPZVXDeh9bg7svLKgJBckOAJnQKcwmDbfMB8AJyXoiZG7wbYtO4TnpyuY6R9S74vxKeJCAKjOP%2Fr%2BlMyiYP%2FygMqbrTlubDUrAMIRIJyWi3ExH5j%2BS9kBuIaVJv%2B5ZvwyazX%2B4ecCiwBAkutHHw35W2%2B3xLcyNZvWIR5qf%2BUfGm2DIQcR%2BS9H5QvkSXPA%2FXDX5zcU%2BDodC0zutxZWsp%2FUVwQ%2B4Y8LWHLmCEB4wDiWWnhw3vI32WxCtQVhF80hLhIaPAunepW74V2fG9keWT3pmV9HNCvU%2F%2BMSFRzPOQStxzVaFWRIeQN0Ycoo%2FwdkDETGegplNCTHW%2Fx03RbcLqcGaM0B4UUro8lf8k2I2OK9GSr6IRYW6JNyg3uD4UcWlowjr%2FBvQY6pgExPcb%2BUoqAuiqmEvY%2FacQmhNJhIH7A3SU%2FPkkXjkZ5RJfsM8sSSxCCd8kHgihcVI9lNZjnUBLuJ9sh53BGFQpTfZbTnzl7Q%2BnFBmCeAQS%2FLysJgHRtAR9B7FVjcIY4Fj4ZajWjajmOGga4CosJr%2BuzKc12mPVTGM3PpCAzfg%2FCyEvMp35bjBKbv03Yz6UFOfiSDDljiZek8DeIIZ72hxru9SWyMyIO&X-Amz-Signature=f8654e17fdfc4887b7abd9323717b6b8739f52b9f33759173489a099611d774d&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Y5LGXXCG%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T102311Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBoaCXVzLXdlc3QtMiJHMEUCIEZnyVGE1TJNVHLGpg0D9XYYXq4AFna%2BD9YOn0%2F7DpsYAiEA%2F8RohDRoJAUvGM4Q%2BE5txTSEUFooRJT4KYAKZ2wGZyQq%2FwMIQxAAGgw2Mzc0MjMxODM4MDUiDF%2B0JOy62%2FDIcrUFASrcA49%2FRbcMBbigmSTFxC3TdvIvFR%2BS97GpCQJH4OScByLaRye7hoBhT7S%2BAtymTAdyS%2FDLolPkH8VFf4hex4jlaRX0o2Lgevwd7cn2RBXtszGWiQKTgg5q4FfAtH54%2B%2Bmqc8%2Bu1OmegSpzYSL03te6UaO7TIFJGlqkyg52Wp1zcpJ%2BJyWHrT%2BzsJy%2BsvbIJcncQ1ncQEexwpnPgy%2BC1MCDrBQtooNdfDvi3bTTNQQggsJbN68J86mbe70XbLHjSy%2B1keMKZJvY3tFbPVlUhtjNZsi0Ss3fch2IGuu4v%2B7NzMX6q30NNB9Ka3%2FIuEN%2Fa2sMiZNjRqFevGPMGjkkKVt1eA%2FCdxpuWSHzVtYZzlLilJCV%2F1JykKWEVhgREaVZwsoRTeO4xAtWmM7tysYZvFCAbkqaD3z6XNsZc0kof9Vl4grj6%2BzoDxKgMYDOLOpzBHTrG29NceDEbGkUgXhhPJntaZAWId9%2BQmxaPvKULLHwu2r52f%2BDRfGlGZx%2FL4JAkVjrVPGWu9qumcWGW7p1RaiS4So%2BHt56SDCfgo7TBcsU1t9BF69jlbTfQ5u6tToHfg5PdG%2FpAxVqSB84UjE02Y303Y4doNjzUfRqTLuvZGiAakhM1eZhErlmoMpd%2B8f0MLi%2Bwb0GOqUB3130peF6LSezD4MLm7ROGWDOw1s%2BiECE7HSzvc0qurXpuFC%2FDCm8KnBVGokKxKe1%2ByW4sybXhYG2MaOxTtz9bMklSSGOFCrX96hzuQpU7DxHKbgU0vKNwBn4MtiY0uIL%2FOy6bY9Q6yZwHr5591sBahk2pLZk02XxHMDN9kfR3LmKMqOUxoDE0Oq5MW3UREQGgnwj0BmQ9GCTdNKVUcPCiZ5C3xAj&X-Amz-Signature=3a21e96827971e615bcf00ef48931255bff2d036b3a1770fdc6e7ba336ed994b&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Y5LGXXCG%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T102311Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBoaCXVzLXdlc3QtMiJHMEUCIEZnyVGE1TJNVHLGpg0D9XYYXq4AFna%2BD9YOn0%2F7DpsYAiEA%2F8RohDRoJAUvGM4Q%2BE5txTSEUFooRJT4KYAKZ2wGZyQq%2FwMIQxAAGgw2Mzc0MjMxODM4MDUiDF%2B0JOy62%2FDIcrUFASrcA49%2FRbcMBbigmSTFxC3TdvIvFR%2BS97GpCQJH4OScByLaRye7hoBhT7S%2BAtymTAdyS%2FDLolPkH8VFf4hex4jlaRX0o2Lgevwd7cn2RBXtszGWiQKTgg5q4FfAtH54%2B%2Bmqc8%2Bu1OmegSpzYSL03te6UaO7TIFJGlqkyg52Wp1zcpJ%2BJyWHrT%2BzsJy%2BsvbIJcncQ1ncQEexwpnPgy%2BC1MCDrBQtooNdfDvi3bTTNQQggsJbN68J86mbe70XbLHjSy%2B1keMKZJvY3tFbPVlUhtjNZsi0Ss3fch2IGuu4v%2B7NzMX6q30NNB9Ka3%2FIuEN%2Fa2sMiZNjRqFevGPMGjkkKVt1eA%2FCdxpuWSHzVtYZzlLilJCV%2F1JykKWEVhgREaVZwsoRTeO4xAtWmM7tysYZvFCAbkqaD3z6XNsZc0kof9Vl4grj6%2BzoDxKgMYDOLOpzBHTrG29NceDEbGkUgXhhPJntaZAWId9%2BQmxaPvKULLHwu2r52f%2BDRfGlGZx%2FL4JAkVjrVPGWu9qumcWGW7p1RaiS4So%2BHt56SDCfgo7TBcsU1t9BF69jlbTfQ5u6tToHfg5PdG%2FpAxVqSB84UjE02Y303Y4doNjzUfRqTLuvZGiAakhM1eZhErlmoMpd%2B8f0MLi%2Bwb0GOqUB3130peF6LSezD4MLm7ROGWDOw1s%2BiECE7HSzvc0qurXpuFC%2FDCm8KnBVGokKxKe1%2ByW4sybXhYG2MaOxTtz9bMklSSGOFCrX96hzuQpU7DxHKbgU0vKNwBn4MtiY0uIL%2FOy6bY9Q6yZwHr5591sBahk2pLZk02XxHMDN9kfR3LmKMqOUxoDE0Oq5MW3UREQGgnwj0BmQ9GCTdNKVUcPCiZ5C3xAj&X-Amz-Signature=c230f2f6aeb970e07fc770988012a1468831b8beb2a4523525934e81b3681262&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Y5LGXXCG%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T102311Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBoaCXVzLXdlc3QtMiJHMEUCIEZnyVGE1TJNVHLGpg0D9XYYXq4AFna%2BD9YOn0%2F7DpsYAiEA%2F8RohDRoJAUvGM4Q%2BE5txTSEUFooRJT4KYAKZ2wGZyQq%2FwMIQxAAGgw2Mzc0MjMxODM4MDUiDF%2B0JOy62%2FDIcrUFASrcA49%2FRbcMBbigmSTFxC3TdvIvFR%2BS97GpCQJH4OScByLaRye7hoBhT7S%2BAtymTAdyS%2FDLolPkH8VFf4hex4jlaRX0o2Lgevwd7cn2RBXtszGWiQKTgg5q4FfAtH54%2B%2Bmqc8%2Bu1OmegSpzYSL03te6UaO7TIFJGlqkyg52Wp1zcpJ%2BJyWHrT%2BzsJy%2BsvbIJcncQ1ncQEexwpnPgy%2BC1MCDrBQtooNdfDvi3bTTNQQggsJbN68J86mbe70XbLHjSy%2B1keMKZJvY3tFbPVlUhtjNZsi0Ss3fch2IGuu4v%2B7NzMX6q30NNB9Ka3%2FIuEN%2Fa2sMiZNjRqFevGPMGjkkKVt1eA%2FCdxpuWSHzVtYZzlLilJCV%2F1JykKWEVhgREaVZwsoRTeO4xAtWmM7tysYZvFCAbkqaD3z6XNsZc0kof9Vl4grj6%2BzoDxKgMYDOLOpzBHTrG29NceDEbGkUgXhhPJntaZAWId9%2BQmxaPvKULLHwu2r52f%2BDRfGlGZx%2FL4JAkVjrVPGWu9qumcWGW7p1RaiS4So%2BHt56SDCfgo7TBcsU1t9BF69jlbTfQ5u6tToHfg5PdG%2FpAxVqSB84UjE02Y303Y4doNjzUfRqTLuvZGiAakhM1eZhErlmoMpd%2B8f0MLi%2Bwb0GOqUB3130peF6LSezD4MLm7ROGWDOw1s%2BiECE7HSzvc0qurXpuFC%2FDCm8KnBVGokKxKe1%2ByW4sybXhYG2MaOxTtz9bMklSSGOFCrX96hzuQpU7DxHKbgU0vKNwBn4MtiY0uIL%2FOy6bY9Q6yZwHr5591sBahk2pLZk02XxHMDN9kfR3LmKMqOUxoDE0Oq5MW3UREQGgnwj0BmQ9GCTdNKVUcPCiZ5C3xAj&X-Amz-Signature=3676865d4e6f49d1fa3453d0949f2aeae3d4931dc85cfd429238a0fa083f8456&X-Amz-SignedHeaders=host&x-id=GetObject)


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

