---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4662N225FDP%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250211T142320Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDla34wBizuyTLi%2F\
  NAowcfdt3L64hSnj76WutLwPqAoIgIhAPFG69%2BUg%2BQOob1C8%2F8%2BeqxdkBFZj%2B6XedeA\
  PAcNPADmKogECNf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igx1LcxZP\
  2FX%2BbxKDF4q3AMywe7g0sw6xZ9ll3FT9LNNv0iwGNm6SACFhUUthAyE%2FX%2BvmGo6A7GL8ZA5\
  UL11BBFv1UlZfmy3aFt7%2FyjrO%2FtGiukx3MyRk5ArHyLX%2FuNRz1pwrqCVheUu%2BMHVfUtAR\
  sGgafddFRsRTGyrPZReh%2FYVK8Jw9Pdkx95WhjegjwvyAkSAxUnOK%2BW5hitFvgwXlO0br6saqm\
  xLaf8rLQ0B3SgUNnWXmftxtZqnpShvl5veZOMD9wHPWqU%2FDxdA8spyDIw77XGpJlRzwXG2zWOhi\
  RRW55%2BQmoNT5r9RRit9it8SeHOMpW4firuqcWVVo22Dg3ZB685lamRBuzGp%2Bc2FV210q%2B2G\
  QxNOFheZWRimKued4SGwXhj26b5KfDvLc4htmHHZ%2F9kLDFS%2FT%2FBHfXKaFyeU0bzOqN3Yotx\
  wygUnowNK8t5u5FoLjxIYTBbMJ%2BSTJZdrAc9Ectap9pJjvRhUZWD%2FmyUJDkQzcBKuxIqEW7Od\
  LChz6p2V0s0w2j4oHdmizWgrdu3lYS62XWfDnRUGeqttExmnNlPETZpOACFV8zOY%2FHHuMOMv6ni\
  wk8tQUYdgnTuNi7T1EKR0VJ%2BeGcFBDxdSD%2BLRxtrKApeUGp5vqSSd%2FaUm%2BOxojdPL7lFR\
  kzC7pa29BjqkAaEXZMXZ0qRjGlkA%2Fd5mlQZSbgewpq6mRvu1MnQjO0kk8J3FkX%2F8h67H2lCnZ\
  FSb2XBioCyJIrggmDwYVOBgwfRMm91ebJzkr1Z53UbogjuDA%2BGL2ka7JoCDMNM0PCKGAre6eQYc\
  0V6mZG5LR1S6%2BddUl7pk5m45qqNHQ9aFso8H4Q6auLzaCZXX49AWkr9XWTASgp0ftKwbN8sQfoB\
  3GIBupFeI&X-Amz-Signature=0405b8befab4109b0b7a2d3e5b13846cda282e9e4e2947adeee\
  c3026c92e5041&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4664YKH55QM%2F20250211%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250211T142157Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIQCcmbgu%2BuDPR3Oq5fOp2XGvGqq9KGTG4DC0z9E0waaICQIgQili%2BS453B9vwEOpP5\
        Zl4xDSUIW7EcPTxNUK4V3SUEQqiAQI1%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw\
        2Mzc0MjMxODM4MDUiDLGthoG%2FmLv4g2NjkSrcA1d753TvfmaBjEcUZ%2FYQ5l0GAG0D1m\
        5HCDydGMSrw7Q81FOhHP9MdIyx%2Ff7aOdLszJeRioLCFaD4Ct3882SprQ4ZL15AMVvZdh%\
        2FFgcevDUt4NQ4QCGcP6OnJ6Zilry0%2BPE3DmQZr%2F5ol9zXi29QUdkjGpyVNwH%2BPUZ\
        BOrwUiZsWW15ymDLhSfyGwbXL9LVKiF9wBdZIpLE8InB2Z8JBk1s2NFWrIj7SuGZxb%2Bs6\
        zm7uHHYcJK7Fj6Fcx7v7BhNiTIO0cKc0JDekmgFqjjI8Kq3rumd7PGFb0lejIzl7rnGsuvX\
        CQYb5%2B9S4DOQ7HoU8a7Rl%2FzFu%2F6RFf14b%2FIlPdrSGvjv3ReTdiCVDQJu%2F0zLQ\
        u1xk2JZJDdoRBfxBIgoljEAlgE3ZdBnrzvmoRMbA7MtDMSURwReLhxWN6ymmagR2mANB6P8\
        xATExPkUUXNwekDUyFugElHzDbAaKOx218L3PnnXBObUxSEvA9Z%2BhVw%2B7Bt7jjpx2fH\
        A4AVDWYCl20IrdHO%2Fe1zPS%2Fj%2B%2FrcL2VkVvmsIX0%2B94HMvy1vvBD2gBPH9B5Yp\
        kkf3rCJk%2FNsvzCfQGaDvD1pElaVALjDnC3AJ9dh%2Fog1RYQ7mbv2X%2BUJatPim5FpKn\
        dfZFGg%2BF5MKamrb0GOqUB%2FiO1PlRqSFGyLBKLrOnpLc%2FDAmVpP7waCp3ejjZxWUCh\
        LQK2AS4YVyVlI5LiQJ%2B5SXT27kXNgHVj9MZP07ryypzgYQyCj3YMEL%2F3eXyAsvEFAkM\
        qvwrT%2FyLZ5NnMaz5zB9Bw3Lle6wSktBmRH3WuLILKVkYqdqXyqjmt%2FqB7NtUcpsD5mW\
        0HdTaNsCKjbGv%2FY49TIpKw60k8x6Wl0smiLLBJfajQ&X-Amz-Signature=4a9d860d29\
        c1ab90c1113092cd7cc76a9b5bb0cbf29a14eeba8da4594c5776b4&X-Amz-SignedHead\
        ers=host&x-id=GetObject"
      expiry_time: "2025-02-11T15:21:57.694Z"
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
UPDATE_TIME: "2025-02-11T14:23:28.390Z"
EXPIRY_TIME: "2025-02-11T15:23:18.270Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SVZXZCOX%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T142318Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDXLFqp4htAJuG8Riwdn%2FisESgis7yEB7hD9X6DGGD6IgIhAI4z6gflyST3LOxXacnokkF4ns1v2kqOPqYjicPcleOxKogECNf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyjrnFFoJLJUk1tUhEq3ANeOxtlTkkBmSOGLA7JEnNugX%2BTBHADcr95%2BlLs1F6vXUWFufV21voR8cICU%2BIc2R0%2BsrT8S4tiU5lX%2Bz9o9CFZdkbkKm8pTLpTcucYVWObw5OGZRQeLtyUCbQs07B7n8SFQtiF30M0iLRG7P1n6V5Ms7WrFbKELwDRyJjvlam8apMZCTJSOOfZ98%2Fas7YXiLpiZhVaMMzrmTKfrNeI05P0lYinaChgD3pO3gdQt7Kbf3MUBR6Ixk9dW4bwwR%2Fvlmy496Z4Faj35tfu%2FUldD1Sgw%2BNtybQhXCWmJ0ZGR3R1gZdD3RIx9JDGJXAPcPvEhOELQd65akW%2Bji3bWQosYWQjV2H9An75seAk48rCo1MXovAoCH%2FMzzwLNKqo8a%2FvmaeSJ2gCx%2BZNzkxV3s8P0hZHtwGOzmxKRr%2BNFTtyF38TEM9RJYi6Sk8bopQECGUYOClxRiSZOVBGNhE%2FbqeKCwREfcghoKo%2Fth16KgBC%2FZVNL7yhiBi8V5XQGT5tHZQbgc3Ihx2BDUYgWLcz%2B2OJUOYJLnxsf3y%2Fa247JNG%2F084YIiY8Z3gtMvS7Fh9SjpoHpL9f9qZPVg%2BQay2U9c%2BOZ5%2FqZWFUVbaM%2BxSNkHF9mC0cNSG%2FbJ7PzhVy2N4qJjDkpa29BjqkAcTlnP%2BXvb1KVYQbRoF4MZgb1Hv43vZlNXXHD7KOBPsMSi8CuUVeuRLI%2B9eLX28bhuHo6ZvecljZvMVJ2sK8dbzStL6VxPjAwoWkcWqivlydiCNr2g%2FNK7Xfde%2BcTv%2FtuqJuj7jlEcwf79pexJG2VWNNm0UDBvgfvRop8OqchgHKPfrMiJRNJ%2Boo6D31xGO9PjAQlt64mFSnd9zRX2Lq1ng87ll8&X-Amz-Signature=d47b5d6c9aa14dd168040a0da50e90db4b0da37a4d715d55909173caf7abe4eb&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SVZXZCOX%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T142318Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDXLFqp4htAJuG8Riwdn%2FisESgis7yEB7hD9X6DGGD6IgIhAI4z6gflyST3LOxXacnokkF4ns1v2kqOPqYjicPcleOxKogECNf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyjrnFFoJLJUk1tUhEq3ANeOxtlTkkBmSOGLA7JEnNugX%2BTBHADcr95%2BlLs1F6vXUWFufV21voR8cICU%2BIc2R0%2BsrT8S4tiU5lX%2Bz9o9CFZdkbkKm8pTLpTcucYVWObw5OGZRQeLtyUCbQs07B7n8SFQtiF30M0iLRG7P1n6V5Ms7WrFbKELwDRyJjvlam8apMZCTJSOOfZ98%2Fas7YXiLpiZhVaMMzrmTKfrNeI05P0lYinaChgD3pO3gdQt7Kbf3MUBR6Ixk9dW4bwwR%2Fvlmy496Z4Faj35tfu%2FUldD1Sgw%2BNtybQhXCWmJ0ZGR3R1gZdD3RIx9JDGJXAPcPvEhOELQd65akW%2Bji3bWQosYWQjV2H9An75seAk48rCo1MXovAoCH%2FMzzwLNKqo8a%2FvmaeSJ2gCx%2BZNzkxV3s8P0hZHtwGOzmxKRr%2BNFTtyF38TEM9RJYi6Sk8bopQECGUYOClxRiSZOVBGNhE%2FbqeKCwREfcghoKo%2Fth16KgBC%2FZVNL7yhiBi8V5XQGT5tHZQbgc3Ihx2BDUYgWLcz%2B2OJUOYJLnxsf3y%2Fa247JNG%2F084YIiY8Z3gtMvS7Fh9SjpoHpL9f9qZPVg%2BQay2U9c%2BOZ5%2FqZWFUVbaM%2BxSNkHF9mC0cNSG%2FbJ7PzhVy2N4qJjDkpa29BjqkAcTlnP%2BXvb1KVYQbRoF4MZgb1Hv43vZlNXXHD7KOBPsMSi8CuUVeuRLI%2B9eLX28bhuHo6ZvecljZvMVJ2sK8dbzStL6VxPjAwoWkcWqivlydiCNr2g%2FNK7Xfde%2BcTv%2FtuqJuj7jlEcwf79pexJG2VWNNm0UDBvgfvRop8OqchgHKPfrMiJRNJ%2Boo6D31xGO9PjAQlt64mFSnd9zRX2Lq1ng87ll8&X-Amz-Signature=102db751ff65f8d270ee9ce3dc68160d0c3eedf279a4a50acac2bfc6890eb613&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SVZXZCOX%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T142318Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDXLFqp4htAJuG8Riwdn%2FisESgis7yEB7hD9X6DGGD6IgIhAI4z6gflyST3LOxXacnokkF4ns1v2kqOPqYjicPcleOxKogECNf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyjrnFFoJLJUk1tUhEq3ANeOxtlTkkBmSOGLA7JEnNugX%2BTBHADcr95%2BlLs1F6vXUWFufV21voR8cICU%2BIc2R0%2BsrT8S4tiU5lX%2Bz9o9CFZdkbkKm8pTLpTcucYVWObw5OGZRQeLtyUCbQs07B7n8SFQtiF30M0iLRG7P1n6V5Ms7WrFbKELwDRyJjvlam8apMZCTJSOOfZ98%2Fas7YXiLpiZhVaMMzrmTKfrNeI05P0lYinaChgD3pO3gdQt7Kbf3MUBR6Ixk9dW4bwwR%2Fvlmy496Z4Faj35tfu%2FUldD1Sgw%2BNtybQhXCWmJ0ZGR3R1gZdD3RIx9JDGJXAPcPvEhOELQd65akW%2Bji3bWQosYWQjV2H9An75seAk48rCo1MXovAoCH%2FMzzwLNKqo8a%2FvmaeSJ2gCx%2BZNzkxV3s8P0hZHtwGOzmxKRr%2BNFTtyF38TEM9RJYi6Sk8bopQECGUYOClxRiSZOVBGNhE%2FbqeKCwREfcghoKo%2Fth16KgBC%2FZVNL7yhiBi8V5XQGT5tHZQbgc3Ihx2BDUYgWLcz%2B2OJUOYJLnxsf3y%2Fa247JNG%2F084YIiY8Z3gtMvS7Fh9SjpoHpL9f9qZPVg%2BQay2U9c%2BOZ5%2FqZWFUVbaM%2BxSNkHF9mC0cNSG%2FbJ7PzhVy2N4qJjDkpa29BjqkAcTlnP%2BXvb1KVYQbRoF4MZgb1Hv43vZlNXXHD7KOBPsMSi8CuUVeuRLI%2B9eLX28bhuHo6ZvecljZvMVJ2sK8dbzStL6VxPjAwoWkcWqivlydiCNr2g%2FNK7Xfde%2BcTv%2FtuqJuj7jlEcwf79pexJG2VWNNm0UDBvgfvRop8OqchgHKPfrMiJRNJ%2Boo6D31xGO9PjAQlt64mFSnd9zRX2Lq1ng87ll8&X-Amz-Signature=cbb3588d57f794a2814c020ffa19bc26cab5cc5563053a966cd3591267b336d9&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SVZXZCOX%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T142318Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDXLFqp4htAJuG8Riwdn%2FisESgis7yEB7hD9X6DGGD6IgIhAI4z6gflyST3LOxXacnokkF4ns1v2kqOPqYjicPcleOxKogECNf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyjrnFFoJLJUk1tUhEq3ANeOxtlTkkBmSOGLA7JEnNugX%2BTBHADcr95%2BlLs1F6vXUWFufV21voR8cICU%2BIc2R0%2BsrT8S4tiU5lX%2Bz9o9CFZdkbkKm8pTLpTcucYVWObw5OGZRQeLtyUCbQs07B7n8SFQtiF30M0iLRG7P1n6V5Ms7WrFbKELwDRyJjvlam8apMZCTJSOOfZ98%2Fas7YXiLpiZhVaMMzrmTKfrNeI05P0lYinaChgD3pO3gdQt7Kbf3MUBR6Ixk9dW4bwwR%2Fvlmy496Z4Faj35tfu%2FUldD1Sgw%2BNtybQhXCWmJ0ZGR3R1gZdD3RIx9JDGJXAPcPvEhOELQd65akW%2Bji3bWQosYWQjV2H9An75seAk48rCo1MXovAoCH%2FMzzwLNKqo8a%2FvmaeSJ2gCx%2BZNzkxV3s8P0hZHtwGOzmxKRr%2BNFTtyF38TEM9RJYi6Sk8bopQECGUYOClxRiSZOVBGNhE%2FbqeKCwREfcghoKo%2Fth16KgBC%2FZVNL7yhiBi8V5XQGT5tHZQbgc3Ihx2BDUYgWLcz%2B2OJUOYJLnxsf3y%2Fa247JNG%2F084YIiY8Z3gtMvS7Fh9SjpoHpL9f9qZPVg%2BQay2U9c%2BOZ5%2FqZWFUVbaM%2BxSNkHF9mC0cNSG%2FbJ7PzhVy2N4qJjDkpa29BjqkAcTlnP%2BXvb1KVYQbRoF4MZgb1Hv43vZlNXXHD7KOBPsMSi8CuUVeuRLI%2B9eLX28bhuHo6ZvecljZvMVJ2sK8dbzStL6VxPjAwoWkcWqivlydiCNr2g%2FNK7Xfde%2BcTv%2FtuqJuj7jlEcwf79pexJG2VWNNm0UDBvgfvRop8OqchgHKPfrMiJRNJ%2Boo6D31xGO9PjAQlt64mFSnd9zRX2Lq1ng87ll8&X-Amz-Signature=cfd9fe14dab23412d16a4f3bb83b60a9ad8768aa3b0181044e3cfab2b030de41&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SVZXZCOX%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T142318Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDXLFqp4htAJuG8Riwdn%2FisESgis7yEB7hD9X6DGGD6IgIhAI4z6gflyST3LOxXacnokkF4ns1v2kqOPqYjicPcleOxKogECNf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyjrnFFoJLJUk1tUhEq3ANeOxtlTkkBmSOGLA7JEnNugX%2BTBHADcr95%2BlLs1F6vXUWFufV21voR8cICU%2BIc2R0%2BsrT8S4tiU5lX%2Bz9o9CFZdkbkKm8pTLpTcucYVWObw5OGZRQeLtyUCbQs07B7n8SFQtiF30M0iLRG7P1n6V5Ms7WrFbKELwDRyJjvlam8apMZCTJSOOfZ98%2Fas7YXiLpiZhVaMMzrmTKfrNeI05P0lYinaChgD3pO3gdQt7Kbf3MUBR6Ixk9dW4bwwR%2Fvlmy496Z4Faj35tfu%2FUldD1Sgw%2BNtybQhXCWmJ0ZGR3R1gZdD3RIx9JDGJXAPcPvEhOELQd65akW%2Bji3bWQosYWQjV2H9An75seAk48rCo1MXovAoCH%2FMzzwLNKqo8a%2FvmaeSJ2gCx%2BZNzkxV3s8P0hZHtwGOzmxKRr%2BNFTtyF38TEM9RJYi6Sk8bopQECGUYOClxRiSZOVBGNhE%2FbqeKCwREfcghoKo%2Fth16KgBC%2FZVNL7yhiBi8V5XQGT5tHZQbgc3Ihx2BDUYgWLcz%2B2OJUOYJLnxsf3y%2Fa247JNG%2F084YIiY8Z3gtMvS7Fh9SjpoHpL9f9qZPVg%2BQay2U9c%2BOZ5%2FqZWFUVbaM%2BxSNkHF9mC0cNSG%2FbJ7PzhVy2N4qJjDkpa29BjqkAcTlnP%2BXvb1KVYQbRoF4MZgb1Hv43vZlNXXHD7KOBPsMSi8CuUVeuRLI%2B9eLX28bhuHo6ZvecljZvMVJ2sK8dbzStL6VxPjAwoWkcWqivlydiCNr2g%2FNK7Xfde%2BcTv%2FtuqJuj7jlEcwf79pexJG2VWNNm0UDBvgfvRop8OqchgHKPfrMiJRNJ%2Boo6D31xGO9PjAQlt64mFSnd9zRX2Lq1ng87ll8&X-Amz-Signature=7da920293895b8cef403c2dc0b39c96c7a6ae3ec49f88c67702473c949048a8c&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665GPQ54WW%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T142319Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIFeDjWRaTRnDKwyTEEgx%2Fx4JIq7Y9M7ElE4lLRXz%2FwgJAiEAzGE4Pu0z4hkyz6gT2pUeNFSmqlv1dGqsdCoYUDF4nmQqiAQI1%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDJVntIN1a3qJM%2BgwQCrcA0QSaiWDeJrdD2L5zT%2BcGvOG9B5f2ZjDwNfM4dKCMpUff0zEKziju%2FaIGdyU1O%2FuUm8Gn1UrJivDxei6I2J9sUThuDcuy6lLtHxv6JZM7qJ%2FVTZGNHTWvv3S%2BhzwACFD5RYT72tEpudUnheVeBuUaIXZ4UJSWCwcty2I6NUUr9cuOhGkqQEzmsfCGiWwfWbM5lk7%2Bm6jjhcd%2FKb9GbTLPi5GQRM1qcsOyYraMMOjOySFWEdpBeYFKU5vnaJ5eiTf0nQ7hxgXumA%2FnInvGXqrsSFqC3zEO7edrpZ8I97GF85n6iv08rq55PPiN1X5bVAbGzvDfaObaaJs3mUGX0%2FOm2BOv%2BEhMYqkP9Bqe9Y%2FmvG2c4x9gxKoRrTRO%2F0Bwctlr7PKtgPcwwLFbW4bhh9j4YlOeuFB8PrLeR52%2BdG0gcLFY8wJRTYZ6jvJbKoQZSE1x1rZDUhNRQwTfXskPYfXgBJXCUJWBZxP%2FXm1dWBmvw5j9YSzxVELDm0EvX7QzUNNdi0KRJP7HfHP%2BETTEx2rWB%2FeK8PdmJ%2FU3k1LiKspb5kmgNyv8XjfYvmFHFD9zHRMTEg53MtwbOKoCjDoUM4zWr6a%2BTu5IqMn6Zp4gjjTJNzJDI91KCpCMX8qwd%2FvMK6mrb0GOqUBukUahquYxNr6N5TSuyxhELHdH2P5K2DdG%2BVxdXgubKP51ZZLxR9oP%2BX1tzJohQqIpG%2BUN01Wb2%2BsE4XZBXD9U5CLxIXyJIFjKsHqKIbun9jeL9vxZ9cy2B9e0ZT4sDchbATG5GAIHEG%2FkENKzAVnkAKxD7kAsr2SbObHzI%2FpMrujZptaj%2FeC2b1yfA48dMHf7yVBU8nsgKMAAE%2FVK4YpqSUrV8AL&X-Amz-Signature=cd011b5d64b6cb8c65f0b485f135655c1f88ffcba492103efd27e72f89abd586&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UOWNAOA6%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T142320Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICzkyBxkByzMiszvNfCRvnidha3x6hCuoaWY%2FQNw3KVIAiAHbq%2FDFc%2FWBOhg7aplUjnMxToR%2FrN%2FB4SczzW6rCneOyqIBAjX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMBRJ6egXDUMTNSzI2KtwDXLw7D2kLPsxBZcxCAN3bKjPL7lXjCLidBaYYjfo3Cq28fhnAXJG06O4nU5CYfN97fWxYxHX8OfC3o5sdFPi8rw48Y9okaCI%2Baucwyo%2FiUQm7JVp3qWny4na10RYcjAKOlH2OsMjK2uY7Mpp07ioNjYCCw6Dn2GguLspWm6MIUr3tbQzBiVVKRsQfvDztwn5oRHycdEjkUkufiaGp81LbJxdgxVxiQ5UVhig%2FRDLHE%2BIhRsv0Smwadm5A7sYtpoMadEpJDDy7rSsH8XgWfX8bD3OqDu%2BRszPJZ%2B1duG%2BruC5iyEDxKDOyIPfHKLYCf%2B%2BU5CQ12K%2BeUJ7ijxkljOxJCKtjOp2aSB%2BK50%2BWD5ACNxos4i8QTvg%2BTHVcyNbvAzQH0gEwDAo2UsqMv7S%2BLWZQOU6G43TmCG9fowoQE0127RBgnv%2FqBcWz0Nec9FffAFAcaby4LUkWBGIhiL75LWTpo9xfPY16XQjKxipCsG3PETcZfdJQG%2F%2Bxfi3RYckJz62Wy4Qa6YaEGZSp%2BXQGKBu7%2BbPW%2FLDP3fBAPP6XUigJO6YVrCMJoBeNOXQXq%2FzTK7wwtv8EndsRA9UQlF1M%2F4whgsLlxn%2FKWCDej9i7h0VftdgufhPKPEdv1ndYxwMwzaWtvQY6pgEe%2BOwsRrjUJyCyhniNYFEQnnFWeUkW0c325MMf85b70rrRprtc9vPVgrcDYqPSZ04x3KujJTvz%2F%2FmESQ7V5UM0M33R8WipS%2BS0P%2FGqssDDKtg7Vm6oEgEWY0yqEOJ5SxV%2Bh53nA%2B0fBBmYyjdt7K3J9UBnOdwUo5Emb%2FRfTXm0fXAuRiDYIxY84ENTbnEe7b9wtjDWDoMogLFX3C15OuEYJg%2FUHtNm&X-Amz-Signature=f6cef6c5fcdf1a2020b14dc57e395cc5612e946b3def1e44d01b045ba2d87ad1&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SVZXZCOX%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T142318Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDXLFqp4htAJuG8Riwdn%2FisESgis7yEB7hD9X6DGGD6IgIhAI4z6gflyST3LOxXacnokkF4ns1v2kqOPqYjicPcleOxKogECNf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyjrnFFoJLJUk1tUhEq3ANeOxtlTkkBmSOGLA7JEnNugX%2BTBHADcr95%2BlLs1F6vXUWFufV21voR8cICU%2BIc2R0%2BsrT8S4tiU5lX%2Bz9o9CFZdkbkKm8pTLpTcucYVWObw5OGZRQeLtyUCbQs07B7n8SFQtiF30M0iLRG7P1n6V5Ms7WrFbKELwDRyJjvlam8apMZCTJSOOfZ98%2Fas7YXiLpiZhVaMMzrmTKfrNeI05P0lYinaChgD3pO3gdQt7Kbf3MUBR6Ixk9dW4bwwR%2Fvlmy496Z4Faj35tfu%2FUldD1Sgw%2BNtybQhXCWmJ0ZGR3R1gZdD3RIx9JDGJXAPcPvEhOELQd65akW%2Bji3bWQosYWQjV2H9An75seAk48rCo1MXovAoCH%2FMzzwLNKqo8a%2FvmaeSJ2gCx%2BZNzkxV3s8P0hZHtwGOzmxKRr%2BNFTtyF38TEM9RJYi6Sk8bopQECGUYOClxRiSZOVBGNhE%2FbqeKCwREfcghoKo%2Fth16KgBC%2FZVNL7yhiBi8V5XQGT5tHZQbgc3Ihx2BDUYgWLcz%2B2OJUOYJLnxsf3y%2Fa247JNG%2F084YIiY8Z3gtMvS7Fh9SjpoHpL9f9qZPVg%2BQay2U9c%2BOZ5%2FqZWFUVbaM%2BxSNkHF9mC0cNSG%2FbJ7PzhVy2N4qJjDkpa29BjqkAcTlnP%2BXvb1KVYQbRoF4MZgb1Hv43vZlNXXHD7KOBPsMSi8CuUVeuRLI%2B9eLX28bhuHo6ZvecljZvMVJ2sK8dbzStL6VxPjAwoWkcWqivlydiCNr2g%2FNK7Xfde%2BcTv%2FtuqJuj7jlEcwf79pexJG2VWNNm0UDBvgfvRop8OqchgHKPfrMiJRNJ%2Boo6D31xGO9PjAQlt64mFSnd9zRX2Lq1ng87ll8&X-Amz-Signature=5f4726c998627e1cbf29876182fc48786b4fc751a91d58b5c786582f07a5422e&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SVZXZCOX%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T142318Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDXLFqp4htAJuG8Riwdn%2FisESgis7yEB7hD9X6DGGD6IgIhAI4z6gflyST3LOxXacnokkF4ns1v2kqOPqYjicPcleOxKogECNf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyjrnFFoJLJUk1tUhEq3ANeOxtlTkkBmSOGLA7JEnNugX%2BTBHADcr95%2BlLs1F6vXUWFufV21voR8cICU%2BIc2R0%2BsrT8S4tiU5lX%2Bz9o9CFZdkbkKm8pTLpTcucYVWObw5OGZRQeLtyUCbQs07B7n8SFQtiF30M0iLRG7P1n6V5Ms7WrFbKELwDRyJjvlam8apMZCTJSOOfZ98%2Fas7YXiLpiZhVaMMzrmTKfrNeI05P0lYinaChgD3pO3gdQt7Kbf3MUBR6Ixk9dW4bwwR%2Fvlmy496Z4Faj35tfu%2FUldD1Sgw%2BNtybQhXCWmJ0ZGR3R1gZdD3RIx9JDGJXAPcPvEhOELQd65akW%2Bji3bWQosYWQjV2H9An75seAk48rCo1MXovAoCH%2FMzzwLNKqo8a%2FvmaeSJ2gCx%2BZNzkxV3s8P0hZHtwGOzmxKRr%2BNFTtyF38TEM9RJYi6Sk8bopQECGUYOClxRiSZOVBGNhE%2FbqeKCwREfcghoKo%2Fth16KgBC%2FZVNL7yhiBi8V5XQGT5tHZQbgc3Ihx2BDUYgWLcz%2B2OJUOYJLnxsf3y%2Fa247JNG%2F084YIiY8Z3gtMvS7Fh9SjpoHpL9f9qZPVg%2BQay2U9c%2BOZ5%2FqZWFUVbaM%2BxSNkHF9mC0cNSG%2FbJ7PzhVy2N4qJjDkpa29BjqkAcTlnP%2BXvb1KVYQbRoF4MZgb1Hv43vZlNXXHD7KOBPsMSi8CuUVeuRLI%2B9eLX28bhuHo6ZvecljZvMVJ2sK8dbzStL6VxPjAwoWkcWqivlydiCNr2g%2FNK7Xfde%2BcTv%2FtuqJuj7jlEcwf79pexJG2VWNNm0UDBvgfvRop8OqchgHKPfrMiJRNJ%2Boo6D31xGO9PjAQlt64mFSnd9zRX2Lq1ng87ll8&X-Amz-Signature=886fe2b22cb4a6d777e344233939bf58836cdbb0cb6b573dd422d6c36e86b3ba&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SVZXZCOX%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T142318Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDXLFqp4htAJuG8Riwdn%2FisESgis7yEB7hD9X6DGGD6IgIhAI4z6gflyST3LOxXacnokkF4ns1v2kqOPqYjicPcleOxKogECNf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyjrnFFoJLJUk1tUhEq3ANeOxtlTkkBmSOGLA7JEnNugX%2BTBHADcr95%2BlLs1F6vXUWFufV21voR8cICU%2BIc2R0%2BsrT8S4tiU5lX%2Bz9o9CFZdkbkKm8pTLpTcucYVWObw5OGZRQeLtyUCbQs07B7n8SFQtiF30M0iLRG7P1n6V5Ms7WrFbKELwDRyJjvlam8apMZCTJSOOfZ98%2Fas7YXiLpiZhVaMMzrmTKfrNeI05P0lYinaChgD3pO3gdQt7Kbf3MUBR6Ixk9dW4bwwR%2Fvlmy496Z4Faj35tfu%2FUldD1Sgw%2BNtybQhXCWmJ0ZGR3R1gZdD3RIx9JDGJXAPcPvEhOELQd65akW%2Bji3bWQosYWQjV2H9An75seAk48rCo1MXovAoCH%2FMzzwLNKqo8a%2FvmaeSJ2gCx%2BZNzkxV3s8P0hZHtwGOzmxKRr%2BNFTtyF38TEM9RJYi6Sk8bopQECGUYOClxRiSZOVBGNhE%2FbqeKCwREfcghoKo%2Fth16KgBC%2FZVNL7yhiBi8V5XQGT5tHZQbgc3Ihx2BDUYgWLcz%2B2OJUOYJLnxsf3y%2Fa247JNG%2F084YIiY8Z3gtMvS7Fh9SjpoHpL9f9qZPVg%2BQay2U9c%2BOZ5%2FqZWFUVbaM%2BxSNkHF9mC0cNSG%2FbJ7PzhVy2N4qJjDkpa29BjqkAcTlnP%2BXvb1KVYQbRoF4MZgb1Hv43vZlNXXHD7KOBPsMSi8CuUVeuRLI%2B9eLX28bhuHo6ZvecljZvMVJ2sK8dbzStL6VxPjAwoWkcWqivlydiCNr2g%2FNK7Xfde%2BcTv%2FtuqJuj7jlEcwf79pexJG2VWNNm0UDBvgfvRop8OqchgHKPfrMiJRNJ%2Boo6D31xGO9PjAQlt64mFSnd9zRX2Lq1ng87ll8&X-Amz-Signature=8fd4b608607f9c205a0509ee774073d9e412c3e70dfd992783dc657c2d0841a8&X-Amz-SignedHeaders=host&x-id=GetObject)


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

