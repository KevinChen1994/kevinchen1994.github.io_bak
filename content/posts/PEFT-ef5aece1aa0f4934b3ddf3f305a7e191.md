---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466SPN7ZTWA%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250216T111845Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEC4aCXVzLXdlc3QtMiJGMEQCIQD1EWbgQdRpmedsWFf0SwZjBfZ%2BkMQzu2MIqfThAtdHTQIfc\
  l6JNXCfOV7pDrWhwZm2THs97NjMZb%2FXA%2BnolKNwqyr%2FAwhXEAAaDDYzNzQyMzE4MzgwNSIM\
  r%2BXlrUbKF%2B%2BU6iReKtwDgJKfpWHQUBtf7iP5t3ok4cymKR%2B7WkmlHg7xsKlLyBJKixL%2\
  BXjYo1sy%2BXO2CvpBM%2F5oKTBKawBGxyRDB1pDI8MyrNkcTSWtu1UF0Zd6lIQnfhWMm196ELOnp\
  Y6dYBQ%2FqwbLUdFyEn7D7wR6%2FMCHF9lJw0knRAb8U%2FZEj6NAOzXM68fICi8DcCbf%2Bzf3WR\
  3K%2F94MNddyEkR2jS%2Fs0p4Nm%2Fib1YMvADI6z6UUIsYtuXAcujjnxG%2Bw3wW6MTtCg2aPROK\
  f3nloq8isuSA6atYRyGPKyBwxp25WCN5%2BhLWIjuYQH%2BqPcTcBycm0%2BOgibgAYgF5yoqnn%2\
  F7McU97xjZNsVR%2FcHO8D09e8PyturvZrVSXbEOiNMawTNkDbTcWDb8beafG9zwd0geCfycVHT5W\
  VS7735IMex6x5WbEr0936E8FxElIn2MxwA%2FbNu31pNA4KO3fobACgpFjU3To1L%2FeRcfpIo1mA\
  OjZMUtdeu8V%2B2uMfuozTy4KpFfRYgGEtHKWVRvmSLAAZztm4dt3mJJ5qku0P2p9YuidTvPO4%2B\
  31hH3OU2r7NKlIUAVXOaY%2Bkg5hnbhwLT4yHKx3tWDaJDEkzj0Y1m0GHc3FpTfkuAzR6tpEd0JfZ\
  szMU7iZ%2BrxsIw3%2F3FvQY6pgFofWj0PFCXIiHJzNlHp%2FHeOfeMuVpro3%2BT2m4dSzKkgAei\
  ugdYu6zU9LbJs9Nkfu0e3rJYpbqf5jInkH%2B2GSD8L1gn7YGERVRcdjSAcKusojtBV%2FsfhdOC6\
  Gc0JHcugQ9LxmwxhL2GFNtSWSM6%2FyRIE7gtQedeDbKMp%2BcBtnYigfXWrBs8SiTQNHevxAF2X8\
  fBo5BHl8oo0x8haxngA4O6xoPGWsJ8&X-Amz-Signature=ba34ae33289c112af386520c63dbeb\
  649e4401135c3f7e71c1e83750465629ad&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4665UZXO43N%2F20250216%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250216T111731Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEC4aCXVzLXdlc3QtMiJHMEUCIFZBi8sAbH%2BDdMCihiCfLjmrjpfO%\
        2BGXV8J0VaEhhoXpdAiEAijgv6doEYcvjVJ7eQ%2BMr1zYDsWSZk7w1yo%2BGi0AFCWgq%2\
        FwMIVxAAGgw2Mzc0MjMxODM4MDUiDEBhOuEq7TIl%2BBQmAyrcA3IkhSrPQsggvRO4U1R5S\
        le5d04CiYCLZaS051Fg25Pkh9HkW8DWO%2BdRqsyfLEXoOvELxoYf4QJp5Dkzbyps9795Xe\
        6IpBQeyiF09N9Pmh7uBpnaZBnA5Tv7xDZKZTn1DA8LtWbBorlYfq3inbpLwnwTXEZDl8jzj\
        bn6fP5nhcyODAAjR6yv%2FTY%2Fi0GrNq5HR6CBKIfKwpxnIf4H5d0f3JVMCKPQOx6w94If\
        y3hozb0rj9fGlV5UoxdjnE18P4g5OYHiRzIYxpBJDj6ql6NRRC7RKcTruVa4z0K5sQJRT1F\
        mqZyQiRquKTFqHb8T4y3uomz%2BVGH%2BFV8iUZk8mwM0%2B6gVVJQgi1hln3MTOUpD4RmH\
        lPJ4DEjnUwEvGtmb0MEwY2tmOFm5QX0RIQ0MIT6VQUvnqCGoyjr3Mj6SjIqkIn7ws8onwnM\
        w29CZSLTvVZp08uIFLS%2FvKNrINYMugQfo4dnx4m9jsbxV9UtU6dse0%2B6sFTyJ4pwZHr\
        pmRJQHQKwG%2F3cbpuq9hNqWXDt0gML05mowwxGPTD58B5fQTdftFn5FdrmYbb2WQtb5Z1o\
        G8EHHakf0oAEhw6sF%2BLL96qsGNbykxTHS%2FArxJcndLvvIXuBCqlfTiUKakx4zIQQpMM\
        D9xb0GOqUBeFcx7OAbSe%2Bch8HP0c%2Bl429xUxiXI9Kfdm8V7ziJtz0iRzRhjc3b8jKfT\
        x2kNR36QvbXf%2B2FIwwOblSFAgS84ie6A%2FBJvn2gjc3zzl34BUF5N%2F5%2BZU%2B4by\
        HaRncLuCJ0DhwNimu%2FO9RqUcUVQkiQ%2BHWiiPRM8xUmTCM8%2BkFPVK3xYZxhi8oRR6I\
        Q6gD0O%2FkW5pSkZpfheGo%2B1oj9CzE9StqrzcLq&X-Amz-Signature=9c6f454649b0f\
        56f55d607ecb2af22196abc5d18494f748f50ed0caf41d7369b&X-Amz-SignedHeaders\
        =host&x-id=GetObject"
      expiry_time: "2025-02-16T12:17:31.535Z"
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
UPDATE_TIME: "2025-02-16T11:18:52.347Z"
EXPIRY_TIME: "2025-02-16T12:18:38.909Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466R2GJ3MXM%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T111839Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEC4aCXVzLXdlc3QtMiJIMEYCIQC3SjvGLA6mCAnFrR0fCcQToy7H%2BfhrqbvlWN9%2FVYJIiQIhAN7%2BBvFByhZtwBMpOj%2F6YxfuOwCRqRvqLbhSW%2BXyWMeJKv8DCFcQABoMNjM3NDIzMTgzODA1IgxqsyZvdUr%2Fl3I4oEkq3AP0Hzwv9Ird2sRKIZCYdSMllPTh74SQVlExTCXbt9IK6ZC4%2BYroAwWlryy0VVnJwEALn5i4%2BoflFrYNMLz175FaYTHf78bsOlfP9i92ebZwLu2TUn8vCBmbN537gE6cQ77lLzJGenMxYtg8r7IT3A2FmXgETMg0dYoW8mRD50S%2FFXd343wZAt%2BbqFwFnjh2cLAfHX7Nct4hJdRM6gEmfELwmvSrBIIdvgdPUUjYCE2NLgHne%2B1gRzql6Ok7chFIibtslJEf7X%2Fu1LwrOPtZVaAc8D9jpBrTjq%2Bk43DwUn0EjIJYniWNOxg8YRfw9S7cJRJe0dcAJvpI52Uq%2BJCOlNGCSzxTeUi4bKubhQPT47y%2BFORMJuvXe2Sfu22rKwztS1tfYvPP4l4MILT9vR9xmho7JSorqtMtv2EuK6xi28HINESGqREai5E1Hf7Bh1KHS7oeZpp3c1VsMaS9%2Fr%2FPNDvL2l2r7RFvCQkWfK%2Fhm4VgZ3KlOnwFdAphyUi%2B8zOuOF2wxqcpVt05fFNvAvemcnYID0ZcdwmKl8prdOelsFDQFEIalQi6sMr%2B5QzvrQE3lVPqLZWFqO4AmRLHsAYH%2BPe8a5oaq2PZ7%2FtdPO1sZwBP%2FeElnZ4xbMGZhSyikzCb%2FsW9BjqkAWXl9REqVxGVWajL2DAnNIWWxpF3oN6YTfH5GoYQ9i7DYGLF7EJJSKrbR%2FqPsuARJt0RkTt1zmKcUDvWv5S427sJxodpJnS7UxjL4zXk%2FFcH%2F9QGjUbBKS1fRnn2kFaQiVAOAjijhZs21RPUpCUmjHV1xfNFJdeGNH7HXkvOvkK1oXBa1cJupVN9OzljeGFfDdEwphfGGrImSYWQs8jdYOJfzlB8&X-Amz-Signature=fad6259eab06afbfc9feb58c118750b95684e61b72216e7d2da5624f94d0f910&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466R2GJ3MXM%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T111839Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEC4aCXVzLXdlc3QtMiJIMEYCIQC3SjvGLA6mCAnFrR0fCcQToy7H%2BfhrqbvlWN9%2FVYJIiQIhAN7%2BBvFByhZtwBMpOj%2F6YxfuOwCRqRvqLbhSW%2BXyWMeJKv8DCFcQABoMNjM3NDIzMTgzODA1IgxqsyZvdUr%2Fl3I4oEkq3AP0Hzwv9Ird2sRKIZCYdSMllPTh74SQVlExTCXbt9IK6ZC4%2BYroAwWlryy0VVnJwEALn5i4%2BoflFrYNMLz175FaYTHf78bsOlfP9i92ebZwLu2TUn8vCBmbN537gE6cQ77lLzJGenMxYtg8r7IT3A2FmXgETMg0dYoW8mRD50S%2FFXd343wZAt%2BbqFwFnjh2cLAfHX7Nct4hJdRM6gEmfELwmvSrBIIdvgdPUUjYCE2NLgHne%2B1gRzql6Ok7chFIibtslJEf7X%2Fu1LwrOPtZVaAc8D9jpBrTjq%2Bk43DwUn0EjIJYniWNOxg8YRfw9S7cJRJe0dcAJvpI52Uq%2BJCOlNGCSzxTeUi4bKubhQPT47y%2BFORMJuvXe2Sfu22rKwztS1tfYvPP4l4MILT9vR9xmho7JSorqtMtv2EuK6xi28HINESGqREai5E1Hf7Bh1KHS7oeZpp3c1VsMaS9%2Fr%2FPNDvL2l2r7RFvCQkWfK%2Fhm4VgZ3KlOnwFdAphyUi%2B8zOuOF2wxqcpVt05fFNvAvemcnYID0ZcdwmKl8prdOelsFDQFEIalQi6sMr%2B5QzvrQE3lVPqLZWFqO4AmRLHsAYH%2BPe8a5oaq2PZ7%2FtdPO1sZwBP%2FeElnZ4xbMGZhSyikzCb%2FsW9BjqkAWXl9REqVxGVWajL2DAnNIWWxpF3oN6YTfH5GoYQ9i7DYGLF7EJJSKrbR%2FqPsuARJt0RkTt1zmKcUDvWv5S427sJxodpJnS7UxjL4zXk%2FFcH%2F9QGjUbBKS1fRnn2kFaQiVAOAjijhZs21RPUpCUmjHV1xfNFJdeGNH7HXkvOvkK1oXBa1cJupVN9OzljeGFfDdEwphfGGrImSYWQs8jdYOJfzlB8&X-Amz-Signature=18c739ea537561548e6d202f80b19097a5a00ae4241d942bafc8018c91da3b0e&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466R2GJ3MXM%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T111839Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEC4aCXVzLXdlc3QtMiJIMEYCIQC3SjvGLA6mCAnFrR0fCcQToy7H%2BfhrqbvlWN9%2FVYJIiQIhAN7%2BBvFByhZtwBMpOj%2F6YxfuOwCRqRvqLbhSW%2BXyWMeJKv8DCFcQABoMNjM3NDIzMTgzODA1IgxqsyZvdUr%2Fl3I4oEkq3AP0Hzwv9Ird2sRKIZCYdSMllPTh74SQVlExTCXbt9IK6ZC4%2BYroAwWlryy0VVnJwEALn5i4%2BoflFrYNMLz175FaYTHf78bsOlfP9i92ebZwLu2TUn8vCBmbN537gE6cQ77lLzJGenMxYtg8r7IT3A2FmXgETMg0dYoW8mRD50S%2FFXd343wZAt%2BbqFwFnjh2cLAfHX7Nct4hJdRM6gEmfELwmvSrBIIdvgdPUUjYCE2NLgHne%2B1gRzql6Ok7chFIibtslJEf7X%2Fu1LwrOPtZVaAc8D9jpBrTjq%2Bk43DwUn0EjIJYniWNOxg8YRfw9S7cJRJe0dcAJvpI52Uq%2BJCOlNGCSzxTeUi4bKubhQPT47y%2BFORMJuvXe2Sfu22rKwztS1tfYvPP4l4MILT9vR9xmho7JSorqtMtv2EuK6xi28HINESGqREai5E1Hf7Bh1KHS7oeZpp3c1VsMaS9%2Fr%2FPNDvL2l2r7RFvCQkWfK%2Fhm4VgZ3KlOnwFdAphyUi%2B8zOuOF2wxqcpVt05fFNvAvemcnYID0ZcdwmKl8prdOelsFDQFEIalQi6sMr%2B5QzvrQE3lVPqLZWFqO4AmRLHsAYH%2BPe8a5oaq2PZ7%2FtdPO1sZwBP%2FeElnZ4xbMGZhSyikzCb%2FsW9BjqkAWXl9REqVxGVWajL2DAnNIWWxpF3oN6YTfH5GoYQ9i7DYGLF7EJJSKrbR%2FqPsuARJt0RkTt1zmKcUDvWv5S427sJxodpJnS7UxjL4zXk%2FFcH%2F9QGjUbBKS1fRnn2kFaQiVAOAjijhZs21RPUpCUmjHV1xfNFJdeGNH7HXkvOvkK1oXBa1cJupVN9OzljeGFfDdEwphfGGrImSYWQs8jdYOJfzlB8&X-Amz-Signature=7d8ddaf1c3bd0fa52cab571527a3778ccc38d7b4672f8d516c694f388d818c9e&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466R2GJ3MXM%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T111839Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEC4aCXVzLXdlc3QtMiJIMEYCIQC3SjvGLA6mCAnFrR0fCcQToy7H%2BfhrqbvlWN9%2FVYJIiQIhAN7%2BBvFByhZtwBMpOj%2F6YxfuOwCRqRvqLbhSW%2BXyWMeJKv8DCFcQABoMNjM3NDIzMTgzODA1IgxqsyZvdUr%2Fl3I4oEkq3AP0Hzwv9Ird2sRKIZCYdSMllPTh74SQVlExTCXbt9IK6ZC4%2BYroAwWlryy0VVnJwEALn5i4%2BoflFrYNMLz175FaYTHf78bsOlfP9i92ebZwLu2TUn8vCBmbN537gE6cQ77lLzJGenMxYtg8r7IT3A2FmXgETMg0dYoW8mRD50S%2FFXd343wZAt%2BbqFwFnjh2cLAfHX7Nct4hJdRM6gEmfELwmvSrBIIdvgdPUUjYCE2NLgHne%2B1gRzql6Ok7chFIibtslJEf7X%2Fu1LwrOPtZVaAc8D9jpBrTjq%2Bk43DwUn0EjIJYniWNOxg8YRfw9S7cJRJe0dcAJvpI52Uq%2BJCOlNGCSzxTeUi4bKubhQPT47y%2BFORMJuvXe2Sfu22rKwztS1tfYvPP4l4MILT9vR9xmho7JSorqtMtv2EuK6xi28HINESGqREai5E1Hf7Bh1KHS7oeZpp3c1VsMaS9%2Fr%2FPNDvL2l2r7RFvCQkWfK%2Fhm4VgZ3KlOnwFdAphyUi%2B8zOuOF2wxqcpVt05fFNvAvemcnYID0ZcdwmKl8prdOelsFDQFEIalQi6sMr%2B5QzvrQE3lVPqLZWFqO4AmRLHsAYH%2BPe8a5oaq2PZ7%2FtdPO1sZwBP%2FeElnZ4xbMGZhSyikzCb%2FsW9BjqkAWXl9REqVxGVWajL2DAnNIWWxpF3oN6YTfH5GoYQ9i7DYGLF7EJJSKrbR%2FqPsuARJt0RkTt1zmKcUDvWv5S427sJxodpJnS7UxjL4zXk%2FFcH%2F9QGjUbBKS1fRnn2kFaQiVAOAjijhZs21RPUpCUmjHV1xfNFJdeGNH7HXkvOvkK1oXBa1cJupVN9OzljeGFfDdEwphfGGrImSYWQs8jdYOJfzlB8&X-Amz-Signature=59f82d558b88cfe6e6ca31425d8f9ff23e4e8f4ce4b7e82d61bcd907aea9e0a8&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466R2GJ3MXM%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T111839Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEC4aCXVzLXdlc3QtMiJIMEYCIQC3SjvGLA6mCAnFrR0fCcQToy7H%2BfhrqbvlWN9%2FVYJIiQIhAN7%2BBvFByhZtwBMpOj%2F6YxfuOwCRqRvqLbhSW%2BXyWMeJKv8DCFcQABoMNjM3NDIzMTgzODA1IgxqsyZvdUr%2Fl3I4oEkq3AP0Hzwv9Ird2sRKIZCYdSMllPTh74SQVlExTCXbt9IK6ZC4%2BYroAwWlryy0VVnJwEALn5i4%2BoflFrYNMLz175FaYTHf78bsOlfP9i92ebZwLu2TUn8vCBmbN537gE6cQ77lLzJGenMxYtg8r7IT3A2FmXgETMg0dYoW8mRD50S%2FFXd343wZAt%2BbqFwFnjh2cLAfHX7Nct4hJdRM6gEmfELwmvSrBIIdvgdPUUjYCE2NLgHne%2B1gRzql6Ok7chFIibtslJEf7X%2Fu1LwrOPtZVaAc8D9jpBrTjq%2Bk43DwUn0EjIJYniWNOxg8YRfw9S7cJRJe0dcAJvpI52Uq%2BJCOlNGCSzxTeUi4bKubhQPT47y%2BFORMJuvXe2Sfu22rKwztS1tfYvPP4l4MILT9vR9xmho7JSorqtMtv2EuK6xi28HINESGqREai5E1Hf7Bh1KHS7oeZpp3c1VsMaS9%2Fr%2FPNDvL2l2r7RFvCQkWfK%2Fhm4VgZ3KlOnwFdAphyUi%2B8zOuOF2wxqcpVt05fFNvAvemcnYID0ZcdwmKl8prdOelsFDQFEIalQi6sMr%2B5QzvrQE3lVPqLZWFqO4AmRLHsAYH%2BPe8a5oaq2PZ7%2FtdPO1sZwBP%2FeElnZ4xbMGZhSyikzCb%2FsW9BjqkAWXl9REqVxGVWajL2DAnNIWWxpF3oN6YTfH5GoYQ9i7DYGLF7EJJSKrbR%2FqPsuARJt0RkTt1zmKcUDvWv5S427sJxodpJnS7UxjL4zXk%2FFcH%2F9QGjUbBKS1fRnn2kFaQiVAOAjijhZs21RPUpCUmjHV1xfNFJdeGNH7HXkvOvkK1oXBa1cJupVN9OzljeGFfDdEwphfGGrImSYWQs8jdYOJfzlB8&X-Amz-Signature=a889dd247d50805639b1d7237a9487d57a4ac90b020ba7a5139c68579babd7a0&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SUN662QG%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T111839Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEC4aCXVzLXdlc3QtMiJHMEUCIQCxD2Jriz4OwZeNMaxxBQvWzEFrnvuv5Gv6YFSDkJVM6QIgS%2Bl7MpQLgG2PG%2Bjd9yDKnj0ilAoDuObrnnAh0xDj3jsq%2FwMIVxAAGgw2Mzc0MjMxODM4MDUiDNf%2Bptfo%2FarCmUjhFCrcA1yyP5k22mxNWaT4VH4adZbnSu2w09g%2FAzvNXV9C47HwOhLOnrvxFTQZhV1sF5SHfO9I7d9dDzrHa1fPaO8OH%2FvIweTZh95ditcrx%2BlWmX4PwLBwVTS5j8UNixn0lv83On3iiXOJebEmAu%2FcYI5VZkkUAR4bgtogYxCKIIeyX8Aq3Q%2FQDQ3FPdjB%2BGs%2Brwe2wm5TOYvcL6k9mnyHLjkmTEwIHGd%2BvrtrEkdd2bzd223lLb5DrycpNgrikZD2UE23951pJhQMT8PsMeSDbjh3T1U7YBlyaHiHRsOmR%2BQBsr7XJ5m0QBLHWzQ6tbErpJu2KfVzO28FmniyyClYyo6L8HKxM%2BgHf9xRSHJ6zopOSSqiscgr6p99eDoCTaqDsP7rVTWUkHneeTKcD5JmIS3VMzwnxTOAAYjzSuiOszj24Z7JKR7dDJ4bDptdSeTg1qcmnE22HvNWF6ni2gb05cybnHIAx7%2F52TJNEp5vcbDT6Kxkj28NhtcaGTSmU0B5KjglRAYQzBetxCQQzH4ov%2ByKTLqPieuSrrAAZTRkbIWEY8kXDKpPEkRh2XKjpPo%2Bsqe96iyZsfxhQsgE5Iu5v2hDkDDEIVwS8DtGMTiEubnzN%2BcHbUc8UPgb0%2FiNQ7ASMKz%2Bxb0GOqUBV9poUn1EbLpcOwUSnQc%2BY5fQf%2FzrDGsnykY10RNxgZ561b55%2FR1WTNwHp7UDabwft9yHj9iYEoSR%2FDA9TpEEiE17zO0J9C6idhGR9cp714j0LPb0gjDePfutuwOb7sYYmRsF1%2FGCXth6EVyJgcnOr%2B0JsXJlbDIEnVhceG%2FZ5O%2FhSYphVhzSjdaYZUa562JoOViXdTuuMt4bmPcqgCK%2FH3LUEmsW&X-Amz-Signature=5140c17be24bf9bd9d4d53c261689ff571957db2f3a53097fc06f13da509569a&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZSYTDKE7%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T111844Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEC4aCXVzLXdlc3QtMiJGMEQCIHg2%2FQTkun6Nn9lrOb8IC0qTfSWoyiHPQK6hxgX4Syr8AiAUrddAwSa%2FfMtRRmdZyW9cna5PyiTxbtHs58VozfmVCir%2FAwhXEAAaDDYzNzQyMzE4MzgwNSIMZBDRdXCKb0prTQPzKtwDQnC5sONg2rsRN%2BkWy%2Fu%2BYybYctSYxLQIH%2BQtm8Dn7%2Fdy75Kp7UfbhOVoDEY0VUmzjjHGHp6iGjXln%2B0fX1ayKwAJLzDzKUeO3iyn%2BdtvpkGBbTG7vvCfX3Ef9ZuH03qKCYxWENwloiPtx1qSM4zyPZUJTGWg3qMg1JLarCEw3TN6efTDvtXU%2Fjj9xp%2By0uRHpG4AjdPD%2Btdc%2F4KxDi8gQodLmHVmHrMHJ4LTosil%2FOi06ZGt2Hj0Hknc0Pien3vubgx6JlLXSeYjUzDe%2BVdevWv73u1ulXivc4noM3i6CdYdSd%2Fh1Y1MJmhXzl4zT83i2hxomPpEZOo0ElLqQA%2BpV3iXpr0rUd7efCERw6mZA5nG7MZnSFJ3sZc2wTEzXjrTmz%2FXMGo%2Fq1TU%2BbIlDVI6ufyZg5%2FBJpbkXnBbflJxGZyrYZ%2BBrtUw3FgZhpdNricIHI7mVvk46sMnNqXbsVNNO%2BXcQ6c3pkdOhowrsMXsc5sy0XPtq1JwRyorT0Y0w5ekUDv8UZZ1ohN%2BoMyrmASH0tPszXDufe87GawGgA6z2ahvRq%2B1Kyr7k%2BNt85SrdlWu%2BpI9ZqKEG2MmZMjag5xnHrUX1NhWm1XYZFnVt05OHe4QUWeQFczekwedkaMwkv7FvQY6pgGJ6poSDoqbWv0sJZuZcGNol0%2BBATty1%2FHounGgImYFyG6AMe%2Faz6YEMtoLv53s%2BBQod0%2FvAF26mxzjTJs5yV7BNRdMTnbL%2B7eysKBywe%2FSf6mp2z2psvNWCKW39vUl3lUtLLZXdaiHPnJYa08OSpiFJk9tgd8cDxra9YPzZv%2BdPK%2FDcpaP4LZJwMsd5zXkYaVQfFwCfaNEweDUvXdx%2Bd2ZaxgboPA8&X-Amz-Signature=f19db587e39f28b19800addb027a87c386070461f9ce3e3b4f8fb75ff138427c&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466R2GJ3MXM%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T111839Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEC4aCXVzLXdlc3QtMiJIMEYCIQC3SjvGLA6mCAnFrR0fCcQToy7H%2BfhrqbvlWN9%2FVYJIiQIhAN7%2BBvFByhZtwBMpOj%2F6YxfuOwCRqRvqLbhSW%2BXyWMeJKv8DCFcQABoMNjM3NDIzMTgzODA1IgxqsyZvdUr%2Fl3I4oEkq3AP0Hzwv9Ird2sRKIZCYdSMllPTh74SQVlExTCXbt9IK6ZC4%2BYroAwWlryy0VVnJwEALn5i4%2BoflFrYNMLz175FaYTHf78bsOlfP9i92ebZwLu2TUn8vCBmbN537gE6cQ77lLzJGenMxYtg8r7IT3A2FmXgETMg0dYoW8mRD50S%2FFXd343wZAt%2BbqFwFnjh2cLAfHX7Nct4hJdRM6gEmfELwmvSrBIIdvgdPUUjYCE2NLgHne%2B1gRzql6Ok7chFIibtslJEf7X%2Fu1LwrOPtZVaAc8D9jpBrTjq%2Bk43DwUn0EjIJYniWNOxg8YRfw9S7cJRJe0dcAJvpI52Uq%2BJCOlNGCSzxTeUi4bKubhQPT47y%2BFORMJuvXe2Sfu22rKwztS1tfYvPP4l4MILT9vR9xmho7JSorqtMtv2EuK6xi28HINESGqREai5E1Hf7Bh1KHS7oeZpp3c1VsMaS9%2Fr%2FPNDvL2l2r7RFvCQkWfK%2Fhm4VgZ3KlOnwFdAphyUi%2B8zOuOF2wxqcpVt05fFNvAvemcnYID0ZcdwmKl8prdOelsFDQFEIalQi6sMr%2B5QzvrQE3lVPqLZWFqO4AmRLHsAYH%2BPe8a5oaq2PZ7%2FtdPO1sZwBP%2FeElnZ4xbMGZhSyikzCb%2FsW9BjqkAWXl9REqVxGVWajL2DAnNIWWxpF3oN6YTfH5GoYQ9i7DYGLF7EJJSKrbR%2FqPsuARJt0RkTt1zmKcUDvWv5S427sJxodpJnS7UxjL4zXk%2FFcH%2F9QGjUbBKS1fRnn2kFaQiVAOAjijhZs21RPUpCUmjHV1xfNFJdeGNH7HXkvOvkK1oXBa1cJupVN9OzljeGFfDdEwphfGGrImSYWQs8jdYOJfzlB8&X-Amz-Signature=ab0eaadee562844baf4564b5f0fc320e00bb5416bcc06e69bf22905022b16f0e&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466R2GJ3MXM%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T111839Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEC4aCXVzLXdlc3QtMiJIMEYCIQC3SjvGLA6mCAnFrR0fCcQToy7H%2BfhrqbvlWN9%2FVYJIiQIhAN7%2BBvFByhZtwBMpOj%2F6YxfuOwCRqRvqLbhSW%2BXyWMeJKv8DCFcQABoMNjM3NDIzMTgzODA1IgxqsyZvdUr%2Fl3I4oEkq3AP0Hzwv9Ird2sRKIZCYdSMllPTh74SQVlExTCXbt9IK6ZC4%2BYroAwWlryy0VVnJwEALn5i4%2BoflFrYNMLz175FaYTHf78bsOlfP9i92ebZwLu2TUn8vCBmbN537gE6cQ77lLzJGenMxYtg8r7IT3A2FmXgETMg0dYoW8mRD50S%2FFXd343wZAt%2BbqFwFnjh2cLAfHX7Nct4hJdRM6gEmfELwmvSrBIIdvgdPUUjYCE2NLgHne%2B1gRzql6Ok7chFIibtslJEf7X%2Fu1LwrOPtZVaAc8D9jpBrTjq%2Bk43DwUn0EjIJYniWNOxg8YRfw9S7cJRJe0dcAJvpI52Uq%2BJCOlNGCSzxTeUi4bKubhQPT47y%2BFORMJuvXe2Sfu22rKwztS1tfYvPP4l4MILT9vR9xmho7JSorqtMtv2EuK6xi28HINESGqREai5E1Hf7Bh1KHS7oeZpp3c1VsMaS9%2Fr%2FPNDvL2l2r7RFvCQkWfK%2Fhm4VgZ3KlOnwFdAphyUi%2B8zOuOF2wxqcpVt05fFNvAvemcnYID0ZcdwmKl8prdOelsFDQFEIalQi6sMr%2B5QzvrQE3lVPqLZWFqO4AmRLHsAYH%2BPe8a5oaq2PZ7%2FtdPO1sZwBP%2FeElnZ4xbMGZhSyikzCb%2FsW9BjqkAWXl9REqVxGVWajL2DAnNIWWxpF3oN6YTfH5GoYQ9i7DYGLF7EJJSKrbR%2FqPsuARJt0RkTt1zmKcUDvWv5S427sJxodpJnS7UxjL4zXk%2FFcH%2F9QGjUbBKS1fRnn2kFaQiVAOAjijhZs21RPUpCUmjHV1xfNFJdeGNH7HXkvOvkK1oXBa1cJupVN9OzljeGFfDdEwphfGGrImSYWQs8jdYOJfzlB8&X-Amz-Signature=324955790661d121310a5cafacb4f0e7d5e4bed6d486bf0fc6cff0816b4eba96&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466R2GJ3MXM%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T111839Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEC4aCXVzLXdlc3QtMiJIMEYCIQC3SjvGLA6mCAnFrR0fCcQToy7H%2BfhrqbvlWN9%2FVYJIiQIhAN7%2BBvFByhZtwBMpOj%2F6YxfuOwCRqRvqLbhSW%2BXyWMeJKv8DCFcQABoMNjM3NDIzMTgzODA1IgxqsyZvdUr%2Fl3I4oEkq3AP0Hzwv9Ird2sRKIZCYdSMllPTh74SQVlExTCXbt9IK6ZC4%2BYroAwWlryy0VVnJwEALn5i4%2BoflFrYNMLz175FaYTHf78bsOlfP9i92ebZwLu2TUn8vCBmbN537gE6cQ77lLzJGenMxYtg8r7IT3A2FmXgETMg0dYoW8mRD50S%2FFXd343wZAt%2BbqFwFnjh2cLAfHX7Nct4hJdRM6gEmfELwmvSrBIIdvgdPUUjYCE2NLgHne%2B1gRzql6Ok7chFIibtslJEf7X%2Fu1LwrOPtZVaAc8D9jpBrTjq%2Bk43DwUn0EjIJYniWNOxg8YRfw9S7cJRJe0dcAJvpI52Uq%2BJCOlNGCSzxTeUi4bKubhQPT47y%2BFORMJuvXe2Sfu22rKwztS1tfYvPP4l4MILT9vR9xmho7JSorqtMtv2EuK6xi28HINESGqREai5E1Hf7Bh1KHS7oeZpp3c1VsMaS9%2Fr%2FPNDvL2l2r7RFvCQkWfK%2Fhm4VgZ3KlOnwFdAphyUi%2B8zOuOF2wxqcpVt05fFNvAvemcnYID0ZcdwmKl8prdOelsFDQFEIalQi6sMr%2B5QzvrQE3lVPqLZWFqO4AmRLHsAYH%2BPe8a5oaq2PZ7%2FtdPO1sZwBP%2FeElnZ4xbMGZhSyikzCb%2FsW9BjqkAWXl9REqVxGVWajL2DAnNIWWxpF3oN6YTfH5GoYQ9i7DYGLF7EJJSKrbR%2FqPsuARJt0RkTt1zmKcUDvWv5S427sJxodpJnS7UxjL4zXk%2FFcH%2F9QGjUbBKS1fRnn2kFaQiVAOAjijhZs21RPUpCUmjHV1xfNFJdeGNH7HXkvOvkK1oXBa1cJupVN9OzljeGFfDdEwphfGGrImSYWQs8jdYOJfzlB8&X-Amz-Signature=d95b05efaa3cb3aaa104f1c3c529510b01446b170e86308666958e8df26698a2&X-Amz-SignedHeaders=host&x-id=GetObject)


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

