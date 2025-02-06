---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4666C66XBWA%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250206T124552Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEEQaCXVzLXdlc3QtMiJHMEUCIEDJsZIa2QIF6kBaZJP1kX8PHKk2ejbpoNgakE9kI7aIAiEAzgV\
  vro49je0JfqrN0i2kwBDTYzORtJyT1Vt9GTGXaUkq%2FwMIXRAAGgw2Mzc0MjMxODM4MDUiDKAmKy\
  NvTuZR4ZumECrcA6wg5CFAYEShh5bUk%2BzY%2BACD0f5AbRu2j2sjRfvthNEHgv9T3im4jm4eW5m\
  YlqgSw2WzPbreR3eHL2lfeIzU8Xex26U%2BMxrjbxYWIJUnyoGX%2BSfYb0Z6sqfNC5vxjRfickbw\
  i%2Big3e7r2BU5D8ohEcneFA%2FJAZAsTBnAs%2BQjLjPsxksxki5oPdIdMW%2F7FS1WMjH42xR9V\
  cuOh6yIEkMXucHjJXEO9Tby2xEMJS4UZSlwENV0yPBoTzn1W21Ymv3UGlHkzdMyaCbJu8jeHASI8V\
  ghnwF5YgFJwTmM%2FtcuXTk7bC66s6UAKs4LGBjNucIL972dNEgDWGIVetPrkVkoD%2BE9O68KiZ9\
  6MHKBzhFOnPDVXlv46IGWXvbjbQQ5lDI53rahbjT92GIfB0wEVUz6SIMCW7uCDQKhUPcGB2z33Ci2\
  vE9dm8gOMWf05%2F20%2BnQUTzFvPpHTrJgVZfkGEBdM3SPOw0KHqp88LY9yFigFvtp5ISQJvK4b%\
  2FIURiaQP22Uo1sjKY9rrqK6A92gz0rCNm82hTtr8UbdZKOjdI6FAYUa6KmYmOyRDwfOcCSBMuHaV\
  0E4icJ7GU%2BpAXFXGEn%2BfeuLuZOWpcfsPm6%2BthMB7yCWAx44TtadBPfb290tIMO7Ekr0GOqU\
  BWXGg4ijc4r9%2BK9uxOmucLJ2Q3zTucvydsjOkWhZjtD%2F8olpBlDr3vBB0yLsLyjqH1060F3aZ\
  JOzwa%2BnooIw2QBRlqOzayqLgqfe1ZqMFi6hD23tVuWq%2B55WZaUapBJCvINtVlp8yco6bj%2FC\
  n%2BtV4IBa4%2B%2FOzhdbOrwHDkYAxGR%2BfeOuLxNKEv3qZ45jSCVBWZnqSB9avvQiArMhzqzP4\
  YWkjoRcg&X-Amz-Signature=27a5e1c0fd689c6d3dee1b5cf04418838848b8968e2a11c1a1f4\
  c9f807522f89&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466TZGJPT2O%2F20250206%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250206T124436Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEEQaCXVzLXdlc3QtMiJHMEUCIQDqPfI3dd%2FvkYNrc%2B0D5mpUdv6\
        oap9x%2FI1xUw1UFGq8fAIgVRATXdOU3UH5X2RJ5KLpeM4NzN0uSJzgl6iCnnYyFMgq%2Fw\
        MIXRAAGgw2Mzc0MjMxODM4MDUiDOuXe6TK2Xh44wVB8ircAxIWr%2FGAXfDqdg9vVjzX1T7\
        I1juojtGQ0Uv5JD9ZOlROTUcCqCzze9rkwuru69KXOKUp7MVaOKa7uihsF4tqX%2F%2Bgb7\
        v%2FTgCWxay2A68ACe1%2BISuNIVmMh%2F4ytlD7xG3IdixZOyXiTulMpXyyOClOuOMmj9A\
        %2Fz41FbsPZ1rgkIrDQSmIYu1O4wsoDsrJOsAs3RQwv1llCMgPLDxJQ0G2pOIvzwaKwGWK6\
        %2FJN4wPNFxoPpyri4rVbPl1%2FJQxV9Nb48kv1xxZmh6FRZ%2Fd7iJUQou6QwnVPxWihjk\
        Q5oX%2Fg5qj62PAJLij14xvgpjEKU2KuBsIfWL7R%2Fl727FRrJzLL9Vm8ZQQNCQ4g48iro\
        HsYJaT9fBrVNGMIcHSArEIo9zVYBhD7sj1Yo36Z2%2Flnwmi50%2BoeNPlECXPVqApfRvYb\
        AGVGrD7ilgxnrESOyc6aHb%2FNztj4Ine5McvsS6tg%2BviJrqVy%2BFBeDa%2Bbh2ecJSM\
        82m9b%2F6HJePgbs0H2qFDBciHtTngPm0%2B3sRJDLCY54NubwUS34pIW6FHBA3n%2Bde9s\
        7R6h0laWQ9kzZWCqRS2RLku7NrxLsWT%2F1v8rnBFFQ1BhcI%2FO6U89EHDk30KqxwnFWdu\
        xVqdmh0WCdtCiUAfxtML7Ekr0GOqUBiYuEazff1rKwgv7Q2IT7AaRYGqFKj7jGkly5x1L0H\
        DCLZ31S%2BoDkaQiOq8s%2BuzettkN5OmR1%2F5%2Fac3wEbP9%2BgKr7LQpPmlpVDSJDaU\
        xcI19306dQLEXtffhUam145guRl6XVuR7K7uMeiwfp4BgazW7AfRCUESoK7kPSc6j2YBQDI\
        vmrxyiRA0G81EnOzuyRjOBInCMSQiRasD4jNTB9aF1JY2Aj&X-Amz-Signature=b4f167d\
        ff3f72dfa2e46524de2bafc0122c60d3b2350b4b2415ce11d41ae6d52&X-Amz-SignedH\
        eaders=host&x-id=GetObject"
      expiry_time: "2025-02-06T13:44:36.543Z"
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
UPDATE_TIME: "2025-02-06T12:45:59.577Z"
EXPIRY_TIME: "2025-02-06T13:45:50.247Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZVBOHWAY%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T124550Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEQaCXVzLXdlc3QtMiJGMEQCIHmCrEI0Z19UaOyp%2F3m33FsOlFcrnMLuXSdT6MNWXLrmAiB0cO63q7RpCQQ1swo93WTm%2Bmjs3WrCsyb9SgZ5q%2F79Myr%2FAwhdEAAaDDYzNzQyMzE4MzgwNSIMeotf0yE1n2FOShptKtwDaB%2BXWqgwAUMo3c%2F5isk8cKs%2BhbnPEqLESr1XgWp3B8ayIc6NGsepjDnE726NoQ3KQ7CulOCrmAJaRM7JRno7GCSZshnuMio%2BFN2ce20e2MY1p9UicXa5sSJOzJRuv9SyxXhPXHQuBA0PYHgCNIftmbSS0KcowzOnjTItF%2F1CG0aiq3UDPqo2vfkYrJDoHJ0VS3Sd2o4HV621Od1h9YkbPxVrNeW9THEmT%2FfIR%2FtJP2M658cRzmCk78K%2FPrHaiqFHAjpDOdzoM4QAiGMQvIpjNxoSODmQGapczISpndhQhAU0rwaJ4XqCoNFtR3TCwIg4VMfBCa%2FMVBnVzOf2APFz4akXaCDSBuUQbpF15gqIoekHbGunoxm6xYOkDPw8WhReEci2aslnxDFWVlSXLb2BMxV35zEbqqJqPM64cTY9Y9IE3nxEu%2FodXlw8auqdxB6gu0Axg90ULr8B698BY17DFf5DfDre5sTr7AGnEp2xCWgR4VkTzgDSVeLb4ADiE6B8ZXunSXHMArOYfPj4kZDZbb2VBF9kT2x93U6Is1Z9yCtE66bybgbdCvWlFKSm7d1%2B0APWtQjsQtKImyxr%2Bi%2BJ%2BWrZTa%2FqlrUfzMiEAulI2kRhvuVS1MX%2BsV27AL0w9sWSvQY6pgFGfk9qwVM8J2O%2FaU1f2VjmsSO%2F%2FrhbIXBh6KmAMR%2BneJS71xczLXH178rfsLdJYXxLl9L2HmuN2noUYdbOpuCX5PgxaSJUxQ%2BHnhoe1OVD5RqOLH9l9ua0dRBl6uT6uxwUOIQjLMNbZD9hqy7PUDu70VRUSDv5%2B7ZAiuKFKO%2FIZX%2F6a%2FWx6%2BG7AQQMhc6YBTd8ujurb7JKduBjwI8%2Fc%2Fym4G60DnT%2B&X-Amz-Signature=908dd42f9bc4590b1be8e757cf47d913d69a1e2ca6768ef409d3963171ad884f&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZVBOHWAY%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T124550Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEQaCXVzLXdlc3QtMiJGMEQCIHmCrEI0Z19UaOyp%2F3m33FsOlFcrnMLuXSdT6MNWXLrmAiB0cO63q7RpCQQ1swo93WTm%2Bmjs3WrCsyb9SgZ5q%2F79Myr%2FAwhdEAAaDDYzNzQyMzE4MzgwNSIMeotf0yE1n2FOShptKtwDaB%2BXWqgwAUMo3c%2F5isk8cKs%2BhbnPEqLESr1XgWp3B8ayIc6NGsepjDnE726NoQ3KQ7CulOCrmAJaRM7JRno7GCSZshnuMio%2BFN2ce20e2MY1p9UicXa5sSJOzJRuv9SyxXhPXHQuBA0PYHgCNIftmbSS0KcowzOnjTItF%2F1CG0aiq3UDPqo2vfkYrJDoHJ0VS3Sd2o4HV621Od1h9YkbPxVrNeW9THEmT%2FfIR%2FtJP2M658cRzmCk78K%2FPrHaiqFHAjpDOdzoM4QAiGMQvIpjNxoSODmQGapczISpndhQhAU0rwaJ4XqCoNFtR3TCwIg4VMfBCa%2FMVBnVzOf2APFz4akXaCDSBuUQbpF15gqIoekHbGunoxm6xYOkDPw8WhReEci2aslnxDFWVlSXLb2BMxV35zEbqqJqPM64cTY9Y9IE3nxEu%2FodXlw8auqdxB6gu0Axg90ULr8B698BY17DFf5DfDre5sTr7AGnEp2xCWgR4VkTzgDSVeLb4ADiE6B8ZXunSXHMArOYfPj4kZDZbb2VBF9kT2x93U6Is1Z9yCtE66bybgbdCvWlFKSm7d1%2B0APWtQjsQtKImyxr%2Bi%2BJ%2BWrZTa%2FqlrUfzMiEAulI2kRhvuVS1MX%2BsV27AL0w9sWSvQY6pgFGfk9qwVM8J2O%2FaU1f2VjmsSO%2F%2FrhbIXBh6KmAMR%2BneJS71xczLXH178rfsLdJYXxLl9L2HmuN2noUYdbOpuCX5PgxaSJUxQ%2BHnhoe1OVD5RqOLH9l9ua0dRBl6uT6uxwUOIQjLMNbZD9hqy7PUDu70VRUSDv5%2B7ZAiuKFKO%2FIZX%2F6a%2FWx6%2BG7AQQMhc6YBTd8ujurb7JKduBjwI8%2Fc%2Fym4G60DnT%2B&X-Amz-Signature=2d2aa0cfd4718bae18657d1c98bcd9ed89defd2fe1ad28ccd94f1ae6b0555125&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZVBOHWAY%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T124550Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEQaCXVzLXdlc3QtMiJGMEQCIHmCrEI0Z19UaOyp%2F3m33FsOlFcrnMLuXSdT6MNWXLrmAiB0cO63q7RpCQQ1swo93WTm%2Bmjs3WrCsyb9SgZ5q%2F79Myr%2FAwhdEAAaDDYzNzQyMzE4MzgwNSIMeotf0yE1n2FOShptKtwDaB%2BXWqgwAUMo3c%2F5isk8cKs%2BhbnPEqLESr1XgWp3B8ayIc6NGsepjDnE726NoQ3KQ7CulOCrmAJaRM7JRno7GCSZshnuMio%2BFN2ce20e2MY1p9UicXa5sSJOzJRuv9SyxXhPXHQuBA0PYHgCNIftmbSS0KcowzOnjTItF%2F1CG0aiq3UDPqo2vfkYrJDoHJ0VS3Sd2o4HV621Od1h9YkbPxVrNeW9THEmT%2FfIR%2FtJP2M658cRzmCk78K%2FPrHaiqFHAjpDOdzoM4QAiGMQvIpjNxoSODmQGapczISpndhQhAU0rwaJ4XqCoNFtR3TCwIg4VMfBCa%2FMVBnVzOf2APFz4akXaCDSBuUQbpF15gqIoekHbGunoxm6xYOkDPw8WhReEci2aslnxDFWVlSXLb2BMxV35zEbqqJqPM64cTY9Y9IE3nxEu%2FodXlw8auqdxB6gu0Axg90ULr8B698BY17DFf5DfDre5sTr7AGnEp2xCWgR4VkTzgDSVeLb4ADiE6B8ZXunSXHMArOYfPj4kZDZbb2VBF9kT2x93U6Is1Z9yCtE66bybgbdCvWlFKSm7d1%2B0APWtQjsQtKImyxr%2Bi%2BJ%2BWrZTa%2FqlrUfzMiEAulI2kRhvuVS1MX%2BsV27AL0w9sWSvQY6pgFGfk9qwVM8J2O%2FaU1f2VjmsSO%2F%2FrhbIXBh6KmAMR%2BneJS71xczLXH178rfsLdJYXxLl9L2HmuN2noUYdbOpuCX5PgxaSJUxQ%2BHnhoe1OVD5RqOLH9l9ua0dRBl6uT6uxwUOIQjLMNbZD9hqy7PUDu70VRUSDv5%2B7ZAiuKFKO%2FIZX%2F6a%2FWx6%2BG7AQQMhc6YBTd8ujurb7JKduBjwI8%2Fc%2Fym4G60DnT%2B&X-Amz-Signature=8a7c7a35a79a3d27ebd1a86cbd4b88a5a1fd9d49b89c6b7ca40c995d23ea8972&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZVBOHWAY%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T124550Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEQaCXVzLXdlc3QtMiJGMEQCIHmCrEI0Z19UaOyp%2F3m33FsOlFcrnMLuXSdT6MNWXLrmAiB0cO63q7RpCQQ1swo93WTm%2Bmjs3WrCsyb9SgZ5q%2F79Myr%2FAwhdEAAaDDYzNzQyMzE4MzgwNSIMeotf0yE1n2FOShptKtwDaB%2BXWqgwAUMo3c%2F5isk8cKs%2BhbnPEqLESr1XgWp3B8ayIc6NGsepjDnE726NoQ3KQ7CulOCrmAJaRM7JRno7GCSZshnuMio%2BFN2ce20e2MY1p9UicXa5sSJOzJRuv9SyxXhPXHQuBA0PYHgCNIftmbSS0KcowzOnjTItF%2F1CG0aiq3UDPqo2vfkYrJDoHJ0VS3Sd2o4HV621Od1h9YkbPxVrNeW9THEmT%2FfIR%2FtJP2M658cRzmCk78K%2FPrHaiqFHAjpDOdzoM4QAiGMQvIpjNxoSODmQGapczISpndhQhAU0rwaJ4XqCoNFtR3TCwIg4VMfBCa%2FMVBnVzOf2APFz4akXaCDSBuUQbpF15gqIoekHbGunoxm6xYOkDPw8WhReEci2aslnxDFWVlSXLb2BMxV35zEbqqJqPM64cTY9Y9IE3nxEu%2FodXlw8auqdxB6gu0Axg90ULr8B698BY17DFf5DfDre5sTr7AGnEp2xCWgR4VkTzgDSVeLb4ADiE6B8ZXunSXHMArOYfPj4kZDZbb2VBF9kT2x93U6Is1Z9yCtE66bybgbdCvWlFKSm7d1%2B0APWtQjsQtKImyxr%2Bi%2BJ%2BWrZTa%2FqlrUfzMiEAulI2kRhvuVS1MX%2BsV27AL0w9sWSvQY6pgFGfk9qwVM8J2O%2FaU1f2VjmsSO%2F%2FrhbIXBh6KmAMR%2BneJS71xczLXH178rfsLdJYXxLl9L2HmuN2noUYdbOpuCX5PgxaSJUxQ%2BHnhoe1OVD5RqOLH9l9ua0dRBl6uT6uxwUOIQjLMNbZD9hqy7PUDu70VRUSDv5%2B7ZAiuKFKO%2FIZX%2F6a%2FWx6%2BG7AQQMhc6YBTd8ujurb7JKduBjwI8%2Fc%2Fym4G60DnT%2B&X-Amz-Signature=3a7552b4d6c9acb1bb81e7f9f78c40bfa2cb9470f6b6ef548161cdb109c10296&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZVBOHWAY%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T124550Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEQaCXVzLXdlc3QtMiJGMEQCIHmCrEI0Z19UaOyp%2F3m33FsOlFcrnMLuXSdT6MNWXLrmAiB0cO63q7RpCQQ1swo93WTm%2Bmjs3WrCsyb9SgZ5q%2F79Myr%2FAwhdEAAaDDYzNzQyMzE4MzgwNSIMeotf0yE1n2FOShptKtwDaB%2BXWqgwAUMo3c%2F5isk8cKs%2BhbnPEqLESr1XgWp3B8ayIc6NGsepjDnE726NoQ3KQ7CulOCrmAJaRM7JRno7GCSZshnuMio%2BFN2ce20e2MY1p9UicXa5sSJOzJRuv9SyxXhPXHQuBA0PYHgCNIftmbSS0KcowzOnjTItF%2F1CG0aiq3UDPqo2vfkYrJDoHJ0VS3Sd2o4HV621Od1h9YkbPxVrNeW9THEmT%2FfIR%2FtJP2M658cRzmCk78K%2FPrHaiqFHAjpDOdzoM4QAiGMQvIpjNxoSODmQGapczISpndhQhAU0rwaJ4XqCoNFtR3TCwIg4VMfBCa%2FMVBnVzOf2APFz4akXaCDSBuUQbpF15gqIoekHbGunoxm6xYOkDPw8WhReEci2aslnxDFWVlSXLb2BMxV35zEbqqJqPM64cTY9Y9IE3nxEu%2FodXlw8auqdxB6gu0Axg90ULr8B698BY17DFf5DfDre5sTr7AGnEp2xCWgR4VkTzgDSVeLb4ADiE6B8ZXunSXHMArOYfPj4kZDZbb2VBF9kT2x93U6Is1Z9yCtE66bybgbdCvWlFKSm7d1%2B0APWtQjsQtKImyxr%2Bi%2BJ%2BWrZTa%2FqlrUfzMiEAulI2kRhvuVS1MX%2BsV27AL0w9sWSvQY6pgFGfk9qwVM8J2O%2FaU1f2VjmsSO%2F%2FrhbIXBh6KmAMR%2BneJS71xczLXH178rfsLdJYXxLl9L2HmuN2noUYdbOpuCX5PgxaSJUxQ%2BHnhoe1OVD5RqOLH9l9ua0dRBl6uT6uxwUOIQjLMNbZD9hqy7PUDu70VRUSDv5%2B7ZAiuKFKO%2FIZX%2F6a%2FWx6%2BG7AQQMhc6YBTd8ujurb7JKduBjwI8%2Fc%2Fym4G60DnT%2B&X-Amz-Signature=e5074ca214a8a89df3e0895f14da0baa643d6975938d932cf1a432eede8eb518&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U4XYNBZA%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T124551Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEQaCXVzLXdlc3QtMiJHMEUCIQCx6T%2FySLi7yEQIRQzzW1cgRi9xhYhwTea53wxxW55JLQIgLEnON1zSrTd53dpyffYjPD%2Fn3WfpQl%2Bdqmj7DRo6P%2FAq%2FwMIXRAAGgw2Mzc0MjMxODM4MDUiDDi%2F6pEuPTd0IW8LxCrcAzxOpKq9CTPOc9rWEJnImUHZpGt%2FaFzSei11LEoCmo27jUeatEfxuRh5WTuU2tFAZrTFZhvlC0LkKZahOQ8rSXQ0o1hZ%2B1bQZLag6o6LMEaxYK%2BaaJqt5ula9%2BdipwhOSo9PMmvELNw%2BOInjtI0BZrquRqw4S0QmmhxXiZ0X%2BIyP5KSZM2%2FQOGRjRA0yC7ffB3zRLDfVNmiyo9795lfA0E6o3tzw8FI1YBalI4nhUX1WsnwhrAXsGtMhDI%2F8bDJ7XWrgw3dOD7k4VGnf%2FaU0aSj8WdZDG60TPzV1WKa6pjghpbvJ6eSxAudFtNDozDNoUP8WeTrepC9yOOr%2FdDFeoCecie8j7gXIsalv0wyBSmqOdmB9ex6GmrjJXI%2BZ6z7SxK%2FLwt3MWGJKICrLvM4Yevr7qVvjMOV8OrnTmZ5ac%2F6llYuNKhEY%2F%2BWDi0u6RvEFnU6LLXxj%2BjkimZTla%2BaboC3UdjaL6nA%2FXmaARqY50D5gqRefSPX2%2F67FnZRzwo9nrGvf6Z8T1t%2Fcog30SG84TlEpXRYW7%2F3RJKl4mJuXQXA%2BJFTCE2HWeYQYt3a5lmT%2BUhR%2FGjOOVXZ36kOJGIW4%2Bk2B5DvYWwGM4oS4Hg%2BsS8FX2%2FUGph7kSnEY50EaMJLFkr0GOqUBGuduqOpxZxzxmLx77V5GvTIVeeHvfF%2FnQO55veXFAQK%2Fh%2FSHENt6kdwGHlkDUU1jU06GDLxTS9qTVZEhS12LBu5M2zUldzgpSsQuQ4Tq2cvIa57s9TFASij%2F3d%2FHgozZbuDqayxdiIE731J81PkLmXl438oq5bpstVWi%2BvN%2BIvbrG1bFnMhOOuhoTQ5%2BOBakCGJ%2BTz16shvDlQaQkfrIYFUA5yOF&X-Amz-Signature=6c1c918d6502b1ad6dda935269ea421f643259d352587881367c8875f8eab1d4&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662WCTD4E4%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T124552Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEQaCXVzLXdlc3QtMiJHMEUCIAPugTN1S8%2B2bgN1UnKJH6dY4JLGRY9EJ60o59GCarOXAiEAsrqsBMpPrbtk%2BiBd8WvlLgcPIbhNQjEPAbz9vxL5QTIq%2FwMIXRAAGgw2Mzc0MjMxODM4MDUiDCWyXKQ%2BiqAn996Z8CrcA7B6mIu7pxDnibW8Tn8hikmfA1Ujrqg8z4pXVGZLQrNCUAJPkUOCJVaWpGz4tMrlA7PIRtJ%2Fseh1lMdI52Gq00v6Lrci0tqKcn99IdqFXXL72vkTRpR1ZKHGSU5jdq%2Fmn43JZF5FbgLnqX98%2B5wOP8PiIyMbGPMHl8SnudZCFFhQdi2Ssvtfj9w04ethHfbHx6xKM9%2BUEte6cJa5AZdvk7GUOdsKndx7PxGgWt5%2FUHZufQjKVLV5yZo1FvaUSw5x10VIKL9Mj4n7oa8Rl%2BdsBnYTVyQ7XlwHxJHb9TP2xmDUQcfsqhs6%2Bx9P6h%2B20obn%2BFqAiTgt9QnZRsP9PpFkgmZD08dnmie0ixltU0C%2FUwxcKkJtoS1zz65%2FdolHfNVjiqXDU13VMcIsWNgGEtP2poDUrBhSf1HmyQSc88ESTeDje1Mh259FPw7K2f8LKlwzDl8RuHV4z7O12oIA%2B%2BpCRRWl2eX75rmyxE%2F4jtWdQG9Kh8UrXuejfyDNVtvyUwnOsPdTbf93WZl0TI%2B2V%2FQTlirDKEWnk2PgMInI3bTHYOhv58nrXHS7WBgoODOZqWBeRoQenG7JghUnWM3xlsOBAXww1dtNs%2B7sVjPzlNP3FoVXw8gxYAkn2%2FfU99FeMODEkr0GOqUBsBpHDs3riEmXXFxrFGR1RM7E5bIg1pTdL5YsF%2FBtzZkx%2BJEteV2xeW%2FH1SoqTRR3JZy7KQpp5T4VIIDOs9vXOLyHoMsPdhoVUkr2x%2BD5uuYQllhrlJ6Yban%2FoQNLCdIHH4xRlcNM0s%2FpyptQkd1Os6cfzDytWA02mACeOA9hcgH0bC%2BRD97YgLtodjkZZIe0G1zxwzcukn4mLORmfewH1j1aBlss&X-Amz-Signature=710cef755a637868bcdb431746bac4d861edeaad6dade8edb6eec33eaec0cf33&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZVBOHWAY%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T124550Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEQaCXVzLXdlc3QtMiJGMEQCIHmCrEI0Z19UaOyp%2F3m33FsOlFcrnMLuXSdT6MNWXLrmAiB0cO63q7RpCQQ1swo93WTm%2Bmjs3WrCsyb9SgZ5q%2F79Myr%2FAwhdEAAaDDYzNzQyMzE4MzgwNSIMeotf0yE1n2FOShptKtwDaB%2BXWqgwAUMo3c%2F5isk8cKs%2BhbnPEqLESr1XgWp3B8ayIc6NGsepjDnE726NoQ3KQ7CulOCrmAJaRM7JRno7GCSZshnuMio%2BFN2ce20e2MY1p9UicXa5sSJOzJRuv9SyxXhPXHQuBA0PYHgCNIftmbSS0KcowzOnjTItF%2F1CG0aiq3UDPqo2vfkYrJDoHJ0VS3Sd2o4HV621Od1h9YkbPxVrNeW9THEmT%2FfIR%2FtJP2M658cRzmCk78K%2FPrHaiqFHAjpDOdzoM4QAiGMQvIpjNxoSODmQGapczISpndhQhAU0rwaJ4XqCoNFtR3TCwIg4VMfBCa%2FMVBnVzOf2APFz4akXaCDSBuUQbpF15gqIoekHbGunoxm6xYOkDPw8WhReEci2aslnxDFWVlSXLb2BMxV35zEbqqJqPM64cTY9Y9IE3nxEu%2FodXlw8auqdxB6gu0Axg90ULr8B698BY17DFf5DfDre5sTr7AGnEp2xCWgR4VkTzgDSVeLb4ADiE6B8ZXunSXHMArOYfPj4kZDZbb2VBF9kT2x93U6Is1Z9yCtE66bybgbdCvWlFKSm7d1%2B0APWtQjsQtKImyxr%2Bi%2BJ%2BWrZTa%2FqlrUfzMiEAulI2kRhvuVS1MX%2BsV27AL0w9sWSvQY6pgFGfk9qwVM8J2O%2FaU1f2VjmsSO%2F%2FrhbIXBh6KmAMR%2BneJS71xczLXH178rfsLdJYXxLl9L2HmuN2noUYdbOpuCX5PgxaSJUxQ%2BHnhoe1OVD5RqOLH9l9ua0dRBl6uT6uxwUOIQjLMNbZD9hqy7PUDu70VRUSDv5%2B7ZAiuKFKO%2FIZX%2F6a%2FWx6%2BG7AQQMhc6YBTd8ujurb7JKduBjwI8%2Fc%2Fym4G60DnT%2B&X-Amz-Signature=95551ce72da23338316bbcfa3c987c0e66091a3a1e3dd2e005f4d2b5b2c1ffc7&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZVBOHWAY%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T124550Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEQaCXVzLXdlc3QtMiJGMEQCIHmCrEI0Z19UaOyp%2F3m33FsOlFcrnMLuXSdT6MNWXLrmAiB0cO63q7RpCQQ1swo93WTm%2Bmjs3WrCsyb9SgZ5q%2F79Myr%2FAwhdEAAaDDYzNzQyMzE4MzgwNSIMeotf0yE1n2FOShptKtwDaB%2BXWqgwAUMo3c%2F5isk8cKs%2BhbnPEqLESr1XgWp3B8ayIc6NGsepjDnE726NoQ3KQ7CulOCrmAJaRM7JRno7GCSZshnuMio%2BFN2ce20e2MY1p9UicXa5sSJOzJRuv9SyxXhPXHQuBA0PYHgCNIftmbSS0KcowzOnjTItF%2F1CG0aiq3UDPqo2vfkYrJDoHJ0VS3Sd2o4HV621Od1h9YkbPxVrNeW9THEmT%2FfIR%2FtJP2M658cRzmCk78K%2FPrHaiqFHAjpDOdzoM4QAiGMQvIpjNxoSODmQGapczISpndhQhAU0rwaJ4XqCoNFtR3TCwIg4VMfBCa%2FMVBnVzOf2APFz4akXaCDSBuUQbpF15gqIoekHbGunoxm6xYOkDPw8WhReEci2aslnxDFWVlSXLb2BMxV35zEbqqJqPM64cTY9Y9IE3nxEu%2FodXlw8auqdxB6gu0Axg90ULr8B698BY17DFf5DfDre5sTr7AGnEp2xCWgR4VkTzgDSVeLb4ADiE6B8ZXunSXHMArOYfPj4kZDZbb2VBF9kT2x93U6Is1Z9yCtE66bybgbdCvWlFKSm7d1%2B0APWtQjsQtKImyxr%2Bi%2BJ%2BWrZTa%2FqlrUfzMiEAulI2kRhvuVS1MX%2BsV27AL0w9sWSvQY6pgFGfk9qwVM8J2O%2FaU1f2VjmsSO%2F%2FrhbIXBh6KmAMR%2BneJS71xczLXH178rfsLdJYXxLl9L2HmuN2noUYdbOpuCX5PgxaSJUxQ%2BHnhoe1OVD5RqOLH9l9ua0dRBl6uT6uxwUOIQjLMNbZD9hqy7PUDu70VRUSDv5%2B7ZAiuKFKO%2FIZX%2F6a%2FWx6%2BG7AQQMhc6YBTd8ujurb7JKduBjwI8%2Fc%2Fym4G60DnT%2B&X-Amz-Signature=5115631e0234c2211783b22b8bc306a8bc2ab676b984f7066da1b65fb7e8f669&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZVBOHWAY%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T124550Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEQaCXVzLXdlc3QtMiJGMEQCIHmCrEI0Z19UaOyp%2F3m33FsOlFcrnMLuXSdT6MNWXLrmAiB0cO63q7RpCQQ1swo93WTm%2Bmjs3WrCsyb9SgZ5q%2F79Myr%2FAwhdEAAaDDYzNzQyMzE4MzgwNSIMeotf0yE1n2FOShptKtwDaB%2BXWqgwAUMo3c%2F5isk8cKs%2BhbnPEqLESr1XgWp3B8ayIc6NGsepjDnE726NoQ3KQ7CulOCrmAJaRM7JRno7GCSZshnuMio%2BFN2ce20e2MY1p9UicXa5sSJOzJRuv9SyxXhPXHQuBA0PYHgCNIftmbSS0KcowzOnjTItF%2F1CG0aiq3UDPqo2vfkYrJDoHJ0VS3Sd2o4HV621Od1h9YkbPxVrNeW9THEmT%2FfIR%2FtJP2M658cRzmCk78K%2FPrHaiqFHAjpDOdzoM4QAiGMQvIpjNxoSODmQGapczISpndhQhAU0rwaJ4XqCoNFtR3TCwIg4VMfBCa%2FMVBnVzOf2APFz4akXaCDSBuUQbpF15gqIoekHbGunoxm6xYOkDPw8WhReEci2aslnxDFWVlSXLb2BMxV35zEbqqJqPM64cTY9Y9IE3nxEu%2FodXlw8auqdxB6gu0Axg90ULr8B698BY17DFf5DfDre5sTr7AGnEp2xCWgR4VkTzgDSVeLb4ADiE6B8ZXunSXHMArOYfPj4kZDZbb2VBF9kT2x93U6Is1Z9yCtE66bybgbdCvWlFKSm7d1%2B0APWtQjsQtKImyxr%2Bi%2BJ%2BWrZTa%2FqlrUfzMiEAulI2kRhvuVS1MX%2BsV27AL0w9sWSvQY6pgFGfk9qwVM8J2O%2FaU1f2VjmsSO%2F%2FrhbIXBh6KmAMR%2BneJS71xczLXH178rfsLdJYXxLl9L2HmuN2noUYdbOpuCX5PgxaSJUxQ%2BHnhoe1OVD5RqOLH9l9ua0dRBl6uT6uxwUOIQjLMNbZD9hqy7PUDu70VRUSDv5%2B7ZAiuKFKO%2FIZX%2F6a%2FWx6%2BG7AQQMhc6YBTd8ujurb7JKduBjwI8%2Fc%2Fym4G60DnT%2B&X-Amz-Signature=50db0b19eec923a165a0ac8b322aa096f7dc474f4482ba5c2dcea870fc062be3&X-Amz-SignedHeaders=host&x-id=GetObject)


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

