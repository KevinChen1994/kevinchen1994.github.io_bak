---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466667MMS6C%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250218T212229Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEG0aCXVzLXdlc3QtMiJGMEQCIE1Xo7dioF01esBY6Tbgp5tN0pG2UbVE%2FSfYhZqoZCdiAiBp7\
  rafA2w0gUsznJwKt%2BsvZ8bTREp0hCzhJzsHi3UvGyqIBAiW%2F%2F%2F%2F%2F%2F%2F%2F%2F%\
  2F8BEAAaDDYzNzQyMzE4MzgwNSIMjVQWxuhtQk%2B9Uye%2FKtwDJcnXqR3e8eylezx%2FzMLxrty\
  DzIQZKvoFCGUkw9nXwRgndiDqZaD9p10eP%2Ff%2BMeS%2BLaO9h6yWIJEMc0u7udqi6nokRg%2BM\
  cAFhf5odKocGImCt8Qu8aH1roryxXVHmMbIHcRJAlJajoVcqofEvskqedhTwSrLudwn6SyWk2w8G3\
  7eVH0YCZk9r6hjyIEmL0XNJxCasOeAVN9uljXrFO2ulMT5yLgZ9ibKeaqlTDksTneCAM2PVtsIozf\
  SBz4M3g2rkKZ1Wmvo90WF%2FOKlQ1tJGqkzuXEbVT1ti8L4GaMfasmNFK7d0%2BrkO%2Bs2fF1kEZ\
  RMdn6kja09LoyNGwjYogPDQvp1oZUhAHBhfBo8YxUGEylpIGQe9Rt9q0%2BZBCmfAZnRsn05xiWPx\
  EA2mBolnYoAMfRCYHvujOUJaaTv%2FCcKO76P9SSZXDWrtw0CfNfxG3yXiOvv83A0HNxJpnbnlkZi\
  CNSpv8QcpShtmIJq0f97qXkSkG5meUMOS4bttpkNqtMj7E%2Bbv7fFWZzNCNJvw7a6L5j83jEcDOb\
  RipPZFKM6BcUTY8W%2FSTv0CHI4mstISFPO2nZSRw%2BR76IA%2FUNHsYkrsuWgW%2FPRNn4m23be\
  E%2BuuJoD2Oj4SuPVT30jHOve0wxtrTvQY6pgF31jzhFKqm6mgBoYzZSMvKGMhO%2Bm1fU1htma8Z\
  01uaVlRrsw8AKDkcQmAy0m3XvnDeRlXFCNfjIpheUst8rheHkGpEiK0ThLNrccKOtxHCYdkbQ1GJP\
  7KOBi0PYSgAYWc5X0DNxlI9P4WXv5fsWMi%2B1FBp2djjE4xE9PpO%2F4J76SLBJz6Iy01mziD97t\
  FtLWo%2BPjVdY2TF89e2BLaHMBVE9skrNls9&X-Amz-Signature=cd1135351b73df7a3ff67e58\
  751fefee946f9ee87919cd68608dcd5c5bf880c6&X-Amz-SignedHeaders=host&x-id=GetObj\
  ect"
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
        redential=ASIAZI2LB46636NIPDK5%2F20250218%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250218T212058Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEG0aCXVzLXdlc3QtMiJHMEUCID52yS26zkX0skIKbcaMDkcmJOrtew0\
        i0fG3eU2eqOeaAiEAhUPf43ZXySFHv%2BoPWd7WQjeqcK51aajNeOYwXycAcKkqiAQIlf%2\
        F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCPKrrNTjbNhPweFsir\
        cAwaaK23pwJcXh%2BLBBQa%2F41WdZUy5AAa8TOhp2YJacXOJiMc4yjd77H5ML8Tl7%2BzC\
        Awk081k6wN9eTFcb1KTlBM5VeA1siEQzUH3fFA2Tutipm0ijBmpO1vxvD9dyef6JUxJ2vie\
        JVeyeA%2B7QwXdzUwfWWF3RFcI5C%2BLd5XjTTm1tdYSRuoH4HSsFp5d9OkwimEngq8JQW%\
        2B9r6mbivpWvHDKiPpSb1U2wdJI7s1qh6CJAqSaEcMJ7%2FpQFQn7bPvS0gJWh%2BLknYqH\
        DYahKuaTi93HQKrnEyNz3vxVtK6cxaVdv%2B8pTfhVL8FojmAanMd1kU%2FrbWlwW%2FWVD\
        oH9uBumYPlxvJ7My4vlWYS2cqm3aJS8xTGiHfiINs8dftFXIFbLuLO7TgaMatfpjG8jAZcC\
        OyrLSBZiuW4T2%2Bpw0o1KouUK910dZsPPEJFIGeSYAXMQbhdqzIkiK%2FOa%2BaApoTrh0\
        78uCJ%2BMm%2BrOsdTYFkYnxt4RbN7jVXDfuKRQQF3CsvJuGbv%2FBQ0zGX3sHQTd7BYnf6\
        XfVHJVASrRgP00cZz8Q0dqqUIJrIgyOTrYyVdbiP3xyLOo65dCSxBk0MmRpHD73F7zLeS8s\
        F3Ktc37rPqHJtrp5i7cAHUHwXG5nqLwFMLva070GOqUBerZIPXle3qHqfAP65RMAk1uxtl2\
        nwHDNIhZCgFKJ5CbrIuCgUOeHCXa%2Bd71jtepU5B0RA1IG2LKfmZJs6%2FOzdTAM3aLhpw\
        HHFSerFM8jOvKT4BVDnuBObe51BM3Lt8RxinHdmRQ0o1cIZGBxJ4m1xA%2Be%2FZYVlsOe6\
        %2FXuk82eIfRmYbj%2BI49SVS63QfOawc%2FTvUM9Wx4%2F9kzCFZeRlBfbwbE%2BZMJD&X\
        -Amz-Signature=b8e49c4255fad10830dc36bbc1c1a977e74bc91318fb826784374ed4\
        21d02eb3&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-18T22:20:58.556Z"
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
UPDATE_TIME: "2025-02-18T21:22:34.296Z"
EXPIRY_TIME: "2025-02-18T22:22:26.270Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZB3O7FQS%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T212226Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG0aCXVzLXdlc3QtMiJHMEUCIQCRLxhg7jXaHqxj8rRx5%2FiV9lpDriYGROqciP%2BwavCQewIgQr3pIZfmgIQj2spCphpIkSy%2F729%2FpamvNFXcWMACPvwqiAQIlv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDIsVEzj33b6udJDfGSrcA9GCVbjnb%2B582xBc9ORwPkQzyq07c0fej0mWLU%2FKQ4SJ%2Bf4ZeUfYZHmY6Ee4KzWNu%2FC6ZJZOH16Av3R97jEIxNTxBNoRfWvYeLDkHodUtkn3MN9O5UqMUyTgzVJm9jxGRgqhOlEn6g1GlrGKr%2FlG1bI1lU3F9fbye8tVGdwIVWkz2NFn%2BhtEtUuiqYLp8%2BKfrApsE3dkCPu4jrk5GUK3Z%2Fo4VOIzzCRq5sMCOOxL5wZV9hznH%2FQoDPa2B17THg%2FfTDnCQndeRi8mY5J50RTxGTBZNKiDGygolIlwDRg9TA6NeKH%2FWpdY1B8hfqqgxKE3%2F07mSx64%2FTvY4WWdC1KMKUE1xAK6TpN7ZNoTO5Jm0m4kc9OgZIEaqWn36AVAeqBo4VkZNfz%2B8ilIS01ZALAs2uIzG%2FHXVMq84zok%2FllwRhpBu8P8BQo0ZeWg7MGQI5ezmzH%2Fxyq%2F0LC0ydPg5nD078gB4PuzYRBNCg50OV97CU%2Fx4YjPWRDYqkqtBGxQ8ZXAUSApC7tYil4Lp7MXGdORSNSxgAiW%2FX8Ou49ccQxjdSoaoptDAYNCigF0T3iSSOoLpzdvSVdNXwzSQDjdsryg0g%2BCeo4DDVPzGJEXxbRr6NuEkwrHS008eH1no8acMLHb070GOqUBcqMBzmPelcV%2FV3Yag3hfLpsXsIDyX9ueE5ocp8FUbQZD4Ho7bTa207V3Jdud0Bwmu%2BdNCpqWqZ9NclBjJGKHkhKXqwrFeuIG6nPuCoaL%2BkMI%2FB3Duy2tecqQDxDhti%2Ba0%2B3YCpBIru1WeUl8hFbwcm2Z64%2BfaEr%2BmFhgP8Dpsj6GrOLTaRgUclOYlf7DT09D0VW26FlOC5B%2FQz85eVhW%2FlayWTBw&X-Amz-Signature=8647feb87be90a592aa69f28de3e707242f415ab8155f1b8e0c00d65570633b7&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZB3O7FQS%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T212226Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG0aCXVzLXdlc3QtMiJHMEUCIQCRLxhg7jXaHqxj8rRx5%2FiV9lpDriYGROqciP%2BwavCQewIgQr3pIZfmgIQj2spCphpIkSy%2F729%2FpamvNFXcWMACPvwqiAQIlv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDIsVEzj33b6udJDfGSrcA9GCVbjnb%2B582xBc9ORwPkQzyq07c0fej0mWLU%2FKQ4SJ%2Bf4ZeUfYZHmY6Ee4KzWNu%2FC6ZJZOH16Av3R97jEIxNTxBNoRfWvYeLDkHodUtkn3MN9O5UqMUyTgzVJm9jxGRgqhOlEn6g1GlrGKr%2FlG1bI1lU3F9fbye8tVGdwIVWkz2NFn%2BhtEtUuiqYLp8%2BKfrApsE3dkCPu4jrk5GUK3Z%2Fo4VOIzzCRq5sMCOOxL5wZV9hznH%2FQoDPa2B17THg%2FfTDnCQndeRi8mY5J50RTxGTBZNKiDGygolIlwDRg9TA6NeKH%2FWpdY1B8hfqqgxKE3%2F07mSx64%2FTvY4WWdC1KMKUE1xAK6TpN7ZNoTO5Jm0m4kc9OgZIEaqWn36AVAeqBo4VkZNfz%2B8ilIS01ZALAs2uIzG%2FHXVMq84zok%2FllwRhpBu8P8BQo0ZeWg7MGQI5ezmzH%2Fxyq%2F0LC0ydPg5nD078gB4PuzYRBNCg50OV97CU%2Fx4YjPWRDYqkqtBGxQ8ZXAUSApC7tYil4Lp7MXGdORSNSxgAiW%2FX8Ou49ccQxjdSoaoptDAYNCigF0T3iSSOoLpzdvSVdNXwzSQDjdsryg0g%2BCeo4DDVPzGJEXxbRr6NuEkwrHS008eH1no8acMLHb070GOqUBcqMBzmPelcV%2FV3Yag3hfLpsXsIDyX9ueE5ocp8FUbQZD4Ho7bTa207V3Jdud0Bwmu%2BdNCpqWqZ9NclBjJGKHkhKXqwrFeuIG6nPuCoaL%2BkMI%2FB3Duy2tecqQDxDhti%2Ba0%2B3YCpBIru1WeUl8hFbwcm2Z64%2BfaEr%2BmFhgP8Dpsj6GrOLTaRgUclOYlf7DT09D0VW26FlOC5B%2FQz85eVhW%2FlayWTBw&X-Amz-Signature=7077b132a2bc949f79a748d3aec600e17cb246b57ed5b9bbb5fbe3f8eae68921&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZB3O7FQS%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T212226Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG0aCXVzLXdlc3QtMiJHMEUCIQCRLxhg7jXaHqxj8rRx5%2FiV9lpDriYGROqciP%2BwavCQewIgQr3pIZfmgIQj2spCphpIkSy%2F729%2FpamvNFXcWMACPvwqiAQIlv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDIsVEzj33b6udJDfGSrcA9GCVbjnb%2B582xBc9ORwPkQzyq07c0fej0mWLU%2FKQ4SJ%2Bf4ZeUfYZHmY6Ee4KzWNu%2FC6ZJZOH16Av3R97jEIxNTxBNoRfWvYeLDkHodUtkn3MN9O5UqMUyTgzVJm9jxGRgqhOlEn6g1GlrGKr%2FlG1bI1lU3F9fbye8tVGdwIVWkz2NFn%2BhtEtUuiqYLp8%2BKfrApsE3dkCPu4jrk5GUK3Z%2Fo4VOIzzCRq5sMCOOxL5wZV9hznH%2FQoDPa2B17THg%2FfTDnCQndeRi8mY5J50RTxGTBZNKiDGygolIlwDRg9TA6NeKH%2FWpdY1B8hfqqgxKE3%2F07mSx64%2FTvY4WWdC1KMKUE1xAK6TpN7ZNoTO5Jm0m4kc9OgZIEaqWn36AVAeqBo4VkZNfz%2B8ilIS01ZALAs2uIzG%2FHXVMq84zok%2FllwRhpBu8P8BQo0ZeWg7MGQI5ezmzH%2Fxyq%2F0LC0ydPg5nD078gB4PuzYRBNCg50OV97CU%2Fx4YjPWRDYqkqtBGxQ8ZXAUSApC7tYil4Lp7MXGdORSNSxgAiW%2FX8Ou49ccQxjdSoaoptDAYNCigF0T3iSSOoLpzdvSVdNXwzSQDjdsryg0g%2BCeo4DDVPzGJEXxbRr6NuEkwrHS008eH1no8acMLHb070GOqUBcqMBzmPelcV%2FV3Yag3hfLpsXsIDyX9ueE5ocp8FUbQZD4Ho7bTa207V3Jdud0Bwmu%2BdNCpqWqZ9NclBjJGKHkhKXqwrFeuIG6nPuCoaL%2BkMI%2FB3Duy2tecqQDxDhti%2Ba0%2B3YCpBIru1WeUl8hFbwcm2Z64%2BfaEr%2BmFhgP8Dpsj6GrOLTaRgUclOYlf7DT09D0VW26FlOC5B%2FQz85eVhW%2FlayWTBw&X-Amz-Signature=4747bc1a02c5badeb9a65b39b2e1dbbdd0f9834ccaa8caa6bc5aa9cf6c654df5&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZB3O7FQS%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T212226Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG0aCXVzLXdlc3QtMiJHMEUCIQCRLxhg7jXaHqxj8rRx5%2FiV9lpDriYGROqciP%2BwavCQewIgQr3pIZfmgIQj2spCphpIkSy%2F729%2FpamvNFXcWMACPvwqiAQIlv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDIsVEzj33b6udJDfGSrcA9GCVbjnb%2B582xBc9ORwPkQzyq07c0fej0mWLU%2FKQ4SJ%2Bf4ZeUfYZHmY6Ee4KzWNu%2FC6ZJZOH16Av3R97jEIxNTxBNoRfWvYeLDkHodUtkn3MN9O5UqMUyTgzVJm9jxGRgqhOlEn6g1GlrGKr%2FlG1bI1lU3F9fbye8tVGdwIVWkz2NFn%2BhtEtUuiqYLp8%2BKfrApsE3dkCPu4jrk5GUK3Z%2Fo4VOIzzCRq5sMCOOxL5wZV9hznH%2FQoDPa2B17THg%2FfTDnCQndeRi8mY5J50RTxGTBZNKiDGygolIlwDRg9TA6NeKH%2FWpdY1B8hfqqgxKE3%2F07mSx64%2FTvY4WWdC1KMKUE1xAK6TpN7ZNoTO5Jm0m4kc9OgZIEaqWn36AVAeqBo4VkZNfz%2B8ilIS01ZALAs2uIzG%2FHXVMq84zok%2FllwRhpBu8P8BQo0ZeWg7MGQI5ezmzH%2Fxyq%2F0LC0ydPg5nD078gB4PuzYRBNCg50OV97CU%2Fx4YjPWRDYqkqtBGxQ8ZXAUSApC7tYil4Lp7MXGdORSNSxgAiW%2FX8Ou49ccQxjdSoaoptDAYNCigF0T3iSSOoLpzdvSVdNXwzSQDjdsryg0g%2BCeo4DDVPzGJEXxbRr6NuEkwrHS008eH1no8acMLHb070GOqUBcqMBzmPelcV%2FV3Yag3hfLpsXsIDyX9ueE5ocp8FUbQZD4Ho7bTa207V3Jdud0Bwmu%2BdNCpqWqZ9NclBjJGKHkhKXqwrFeuIG6nPuCoaL%2BkMI%2FB3Duy2tecqQDxDhti%2Ba0%2B3YCpBIru1WeUl8hFbwcm2Z64%2BfaEr%2BmFhgP8Dpsj6GrOLTaRgUclOYlf7DT09D0VW26FlOC5B%2FQz85eVhW%2FlayWTBw&X-Amz-Signature=f9a2baba704055db52504deea660eb727a6d4d3fee96b2545e3135d6bbe556b7&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZB3O7FQS%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T212226Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG0aCXVzLXdlc3QtMiJHMEUCIQCRLxhg7jXaHqxj8rRx5%2FiV9lpDriYGROqciP%2BwavCQewIgQr3pIZfmgIQj2spCphpIkSy%2F729%2FpamvNFXcWMACPvwqiAQIlv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDIsVEzj33b6udJDfGSrcA9GCVbjnb%2B582xBc9ORwPkQzyq07c0fej0mWLU%2FKQ4SJ%2Bf4ZeUfYZHmY6Ee4KzWNu%2FC6ZJZOH16Av3R97jEIxNTxBNoRfWvYeLDkHodUtkn3MN9O5UqMUyTgzVJm9jxGRgqhOlEn6g1GlrGKr%2FlG1bI1lU3F9fbye8tVGdwIVWkz2NFn%2BhtEtUuiqYLp8%2BKfrApsE3dkCPu4jrk5GUK3Z%2Fo4VOIzzCRq5sMCOOxL5wZV9hznH%2FQoDPa2B17THg%2FfTDnCQndeRi8mY5J50RTxGTBZNKiDGygolIlwDRg9TA6NeKH%2FWpdY1B8hfqqgxKE3%2F07mSx64%2FTvY4WWdC1KMKUE1xAK6TpN7ZNoTO5Jm0m4kc9OgZIEaqWn36AVAeqBo4VkZNfz%2B8ilIS01ZALAs2uIzG%2FHXVMq84zok%2FllwRhpBu8P8BQo0ZeWg7MGQI5ezmzH%2Fxyq%2F0LC0ydPg5nD078gB4PuzYRBNCg50OV97CU%2Fx4YjPWRDYqkqtBGxQ8ZXAUSApC7tYil4Lp7MXGdORSNSxgAiW%2FX8Ou49ccQxjdSoaoptDAYNCigF0T3iSSOoLpzdvSVdNXwzSQDjdsryg0g%2BCeo4DDVPzGJEXxbRr6NuEkwrHS008eH1no8acMLHb070GOqUBcqMBzmPelcV%2FV3Yag3hfLpsXsIDyX9ueE5ocp8FUbQZD4Ho7bTa207V3Jdud0Bwmu%2BdNCpqWqZ9NclBjJGKHkhKXqwrFeuIG6nPuCoaL%2BkMI%2FB3Duy2tecqQDxDhti%2Ba0%2B3YCpBIru1WeUl8hFbwcm2Z64%2BfaEr%2BmFhgP8Dpsj6GrOLTaRgUclOYlf7DT09D0VW26FlOC5B%2FQz85eVhW%2FlayWTBw&X-Amz-Signature=4ccddbb547fabc347fce7ab1cd97f80de4576aa724ec2f070d263884a99698fa&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WLJH3VWV%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T212227Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG0aCXVzLXdlc3QtMiJHMEUCIQCyTEBWrc2q%2FK3RPu%2BxaQpCiGe5iHjXKKW55o19r95q9wIgJKRp0NFzOX%2BM056QmmKF7oBv0EPPN1uk5I9BypphoOEqiAQIlv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNvihbW1iKMxxqbi4yrcA6xX0Qp2n2UC54TNxSv4yt399pyjCBNNn6T28GRPlBAeX%2BO5HN8NWAzLWXdYyDGfK6Q%2BZ0n0WofyPllLYpuzYS4UiInGiaFiF%2FI9GztigX4L2BZmdQr8lnuMAtXwapWIuBvIYaW6L42rZDtmrtL2U%2BHHN8dQjfp1W1beDFNVg7aeQFCh5m41KDgzBrA5LAqfCKt3kqbxs%2BEdzNLN13Gr2QtwN3yoixl0zJhIE4V646q5Zm1etDfrRT1rOvtFK94WJO4fL%2BAPPNeRMLGvt2kS%2BunhcG4xqfRAjOHHVeBb9l%2F2yV3CMn9vq%2FQmqZRLl5Mq6Q%2B%2BP8TRK2RYFcyPnNDgv4pCeHD1kAdkmvGL1mCtsGbeRCADhB80Lfia0VC0wQhPB69XwHVS9BvNwK8Xmr7CLuFR5pcN7smrjA%2BK%2FSVO6iuRhrsN4yFVcS0mb%2F2rFJym%2BUu20QMMePBXmyBzgkkQ6YaVxLV7EQTJE6l985j9TLpJ%2FJ%2FTFiNRmajQfw2hkU88xDa6XgkwcsypZ2x%2BuYu%2B29280JiKcKP%2F%2Bhsd5XbVB513Rj9EssLoFcHI2L0qAjajYeAGORrA3Ij5SzyMTlB7Qj5ZSr6iTBoQp5I%2Bh3fdqynAHb9jNQ8OKitRXVByMPfZ070GOqUBuJOYb%2FhGO8ZflLzvm5EBaOkQVsSQd174qw%2B14nkSx9sSqWwbeHN2jkZ%2F3UZJnqCIfWmAyUEq4JzlSpXJOlGPc5aJn7yJFUIo6OmzyUk9nVtOgPZmFdZcMx6o%2BcLk63Cg6kvQJqexZTbLM8KhgeuprhLoxHvc6j5roCod3zJ44rJKdArguNy2S2yy4fQboTau9rJ4hulMyRxczl%2FgJU%2BBm73bqrM%2B&X-Amz-Signature=b1ddf423e6bb901409cccf156aaf82b53706f0fa87c39df429732df126992e81&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XYOMBNRZ%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T212229Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG0aCXVzLXdlc3QtMiJIMEYCIQD4XyA1wH6iUYJF8Lj8%2Fx36Ein4VDeJDdIW1kicuXnVBgIhANurInrZZng8K8kNfGEpOsWkM6j0wijyBhjx6HzUHKsmKogECJb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxE8EYeoZjc12I8uIkq3APKS9WWjkInl%2FzY7h10XyiSWYJhkYls%2F7WXo1l9BhdNX5q51RjvxQ0Xbn6t4Lq6vpNSJvmA1BEMhZcOfmvCV7DXrtTyg9M5wfldpc2%2FRRixqSwxqQa9wKX%2FpaIWc6Vit9o3g9o38mdglosTyI4%2F8h4D7cezPBiG%2Bwg%2FU977U6UPKV56Gag0FqyOIdTyx%2Fi8X9izN5bmfJLvZrF%2FzWRzsRdSkOUvFlqdFhewbPdBvutCMyawYDPd8B1u2o9LDXepQoyu2h8fj15%2BGaxALHn8WXnMD5tMQBObWXsVdAtZK2fWYLsEfh9ucX08k6iC3zmAy5JYPE4nk5wJn33RSCt0zaMGZNnIcv3Bm0xETnXeMqySf5etVu7vMsiYFe%2FbMOy044ANzZRl90AfSV5KNeblpW8%2FiSKQyxB4QyDZZxwx1oeE%2Fq4VcUYLIq6fLMtC6p%2FxvP63mLTXNTtQxbnPZLKcBlzt%2BVQUfDt6pysXbHXBePXco1Rs3g%2BGpua9eXrGikXnraA3GbcTTIIYQ6xIh%2B8l8rVLNCsdysmoVL9wiZbZCYUIc5%2Bk5DjIchrczb6WRz5qNWAfF21SnX23uAU4SbxopzsdZpcW2%2BZhGRfIl4uSeD6sDM0eRBuulcSCSw1BeDD42dO9BjqkAY0RxDH2Nyf3PCIGm4m8S2YGDg7EOlL6REWGftnqJhZC3pU6ziRYmXmOOc3KKY0Bbeb34g9SSKLbtPTFdnsO39fjEb8gbJptYe7438FAGaaPSgQXsDB2Xt%2Ftf5g%2FVVbIH91PCojWiu70N%2BEGKSzH1h1WLG6dVco%2B0qMXZ1F%2B8KkxVSAdomvgiT19EzWpd2%2FyDrf4si335dcdjuua8oHdOokxiNJp&X-Amz-Signature=fa78f07a4052484cbef4ce503eb62d5e7dcd96f65e52c880d2eda0667cbeaba5&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZB3O7FQS%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T212226Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG0aCXVzLXdlc3QtMiJHMEUCIQCRLxhg7jXaHqxj8rRx5%2FiV9lpDriYGROqciP%2BwavCQewIgQr3pIZfmgIQj2spCphpIkSy%2F729%2FpamvNFXcWMACPvwqiAQIlv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDIsVEzj33b6udJDfGSrcA9GCVbjnb%2B582xBc9ORwPkQzyq07c0fej0mWLU%2FKQ4SJ%2Bf4ZeUfYZHmY6Ee4KzWNu%2FC6ZJZOH16Av3R97jEIxNTxBNoRfWvYeLDkHodUtkn3MN9O5UqMUyTgzVJm9jxGRgqhOlEn6g1GlrGKr%2FlG1bI1lU3F9fbye8tVGdwIVWkz2NFn%2BhtEtUuiqYLp8%2BKfrApsE3dkCPu4jrk5GUK3Z%2Fo4VOIzzCRq5sMCOOxL5wZV9hznH%2FQoDPa2B17THg%2FfTDnCQndeRi8mY5J50RTxGTBZNKiDGygolIlwDRg9TA6NeKH%2FWpdY1B8hfqqgxKE3%2F07mSx64%2FTvY4WWdC1KMKUE1xAK6TpN7ZNoTO5Jm0m4kc9OgZIEaqWn36AVAeqBo4VkZNfz%2B8ilIS01ZALAs2uIzG%2FHXVMq84zok%2FllwRhpBu8P8BQo0ZeWg7MGQI5ezmzH%2Fxyq%2F0LC0ydPg5nD078gB4PuzYRBNCg50OV97CU%2Fx4YjPWRDYqkqtBGxQ8ZXAUSApC7tYil4Lp7MXGdORSNSxgAiW%2FX8Ou49ccQxjdSoaoptDAYNCigF0T3iSSOoLpzdvSVdNXwzSQDjdsryg0g%2BCeo4DDVPzGJEXxbRr6NuEkwrHS008eH1no8acMLHb070GOqUBcqMBzmPelcV%2FV3Yag3hfLpsXsIDyX9ueE5ocp8FUbQZD4Ho7bTa207V3Jdud0Bwmu%2BdNCpqWqZ9NclBjJGKHkhKXqwrFeuIG6nPuCoaL%2BkMI%2FB3Duy2tecqQDxDhti%2Ba0%2B3YCpBIru1WeUl8hFbwcm2Z64%2BfaEr%2BmFhgP8Dpsj6GrOLTaRgUclOYlf7DT09D0VW26FlOC5B%2FQz85eVhW%2FlayWTBw&X-Amz-Signature=62cb25365e0c2956303fc93d770801a9725eb2d5ba1006870897614dc2002e36&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZB3O7FQS%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T212226Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG0aCXVzLXdlc3QtMiJHMEUCIQCRLxhg7jXaHqxj8rRx5%2FiV9lpDriYGROqciP%2BwavCQewIgQr3pIZfmgIQj2spCphpIkSy%2F729%2FpamvNFXcWMACPvwqiAQIlv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDIsVEzj33b6udJDfGSrcA9GCVbjnb%2B582xBc9ORwPkQzyq07c0fej0mWLU%2FKQ4SJ%2Bf4ZeUfYZHmY6Ee4KzWNu%2FC6ZJZOH16Av3R97jEIxNTxBNoRfWvYeLDkHodUtkn3MN9O5UqMUyTgzVJm9jxGRgqhOlEn6g1GlrGKr%2FlG1bI1lU3F9fbye8tVGdwIVWkz2NFn%2BhtEtUuiqYLp8%2BKfrApsE3dkCPu4jrk5GUK3Z%2Fo4VOIzzCRq5sMCOOxL5wZV9hznH%2FQoDPa2B17THg%2FfTDnCQndeRi8mY5J50RTxGTBZNKiDGygolIlwDRg9TA6NeKH%2FWpdY1B8hfqqgxKE3%2F07mSx64%2FTvY4WWdC1KMKUE1xAK6TpN7ZNoTO5Jm0m4kc9OgZIEaqWn36AVAeqBo4VkZNfz%2B8ilIS01ZALAs2uIzG%2FHXVMq84zok%2FllwRhpBu8P8BQo0ZeWg7MGQI5ezmzH%2Fxyq%2F0LC0ydPg5nD078gB4PuzYRBNCg50OV97CU%2Fx4YjPWRDYqkqtBGxQ8ZXAUSApC7tYil4Lp7MXGdORSNSxgAiW%2FX8Ou49ccQxjdSoaoptDAYNCigF0T3iSSOoLpzdvSVdNXwzSQDjdsryg0g%2BCeo4DDVPzGJEXxbRr6NuEkwrHS008eH1no8acMLHb070GOqUBcqMBzmPelcV%2FV3Yag3hfLpsXsIDyX9ueE5ocp8FUbQZD4Ho7bTa207V3Jdud0Bwmu%2BdNCpqWqZ9NclBjJGKHkhKXqwrFeuIG6nPuCoaL%2BkMI%2FB3Duy2tecqQDxDhti%2Ba0%2B3YCpBIru1WeUl8hFbwcm2Z64%2BfaEr%2BmFhgP8Dpsj6GrOLTaRgUclOYlf7DT09D0VW26FlOC5B%2FQz85eVhW%2FlayWTBw&X-Amz-Signature=56d735fd2bbe7e272d2db4117ea747bab2c62ffc30151135d437b86ae5bcb9ea&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZB3O7FQS%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T212226Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG0aCXVzLXdlc3QtMiJHMEUCIQCRLxhg7jXaHqxj8rRx5%2FiV9lpDriYGROqciP%2BwavCQewIgQr3pIZfmgIQj2spCphpIkSy%2F729%2FpamvNFXcWMACPvwqiAQIlv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDIsVEzj33b6udJDfGSrcA9GCVbjnb%2B582xBc9ORwPkQzyq07c0fej0mWLU%2FKQ4SJ%2Bf4ZeUfYZHmY6Ee4KzWNu%2FC6ZJZOH16Av3R97jEIxNTxBNoRfWvYeLDkHodUtkn3MN9O5UqMUyTgzVJm9jxGRgqhOlEn6g1GlrGKr%2FlG1bI1lU3F9fbye8tVGdwIVWkz2NFn%2BhtEtUuiqYLp8%2BKfrApsE3dkCPu4jrk5GUK3Z%2Fo4VOIzzCRq5sMCOOxL5wZV9hznH%2FQoDPa2B17THg%2FfTDnCQndeRi8mY5J50RTxGTBZNKiDGygolIlwDRg9TA6NeKH%2FWpdY1B8hfqqgxKE3%2F07mSx64%2FTvY4WWdC1KMKUE1xAK6TpN7ZNoTO5Jm0m4kc9OgZIEaqWn36AVAeqBo4VkZNfz%2B8ilIS01ZALAs2uIzG%2FHXVMq84zok%2FllwRhpBu8P8BQo0ZeWg7MGQI5ezmzH%2Fxyq%2F0LC0ydPg5nD078gB4PuzYRBNCg50OV97CU%2Fx4YjPWRDYqkqtBGxQ8ZXAUSApC7tYil4Lp7MXGdORSNSxgAiW%2FX8Ou49ccQxjdSoaoptDAYNCigF0T3iSSOoLpzdvSVdNXwzSQDjdsryg0g%2BCeo4DDVPzGJEXxbRr6NuEkwrHS008eH1no8acMLHb070GOqUBcqMBzmPelcV%2FV3Yag3hfLpsXsIDyX9ueE5ocp8FUbQZD4Ho7bTa207V3Jdud0Bwmu%2BdNCpqWqZ9NclBjJGKHkhKXqwrFeuIG6nPuCoaL%2BkMI%2FB3Duy2tecqQDxDhti%2Ba0%2B3YCpBIru1WeUl8hFbwcm2Z64%2BfaEr%2BmFhgP8Dpsj6GrOLTaRgUclOYlf7DT09D0VW26FlOC5B%2FQz85eVhW%2FlayWTBw&X-Amz-Signature=f0a53eea90f1cd2442fba1263fa47f4e37f887ba5a2f71810898f3f0df324895&X-Amz-SignedHeaders=host&x-id=GetObject)


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

