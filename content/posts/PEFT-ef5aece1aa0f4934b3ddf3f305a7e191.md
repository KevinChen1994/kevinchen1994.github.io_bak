---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4663Z7FM5UE%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250220T112011Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQC4xYxsggky6RyU8Ve\
  mdpMTYSE8DWm8IX7QTv7zy8lqiAIgIIrpRucgsu8QPQBxPXdY8wuEhx07d5VMeS5AK6bWsBAqiAQI\
  vP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDF4ns5lB46nP5tw6iCrcA\
  9Pje6N2hzFbEVRL70crx0TxXJKel2Zw8le9VbGLRxtwdXccglhcVmtOLK5%2FjVw1c6WKpn9YyKzz\
  WNpKLly1pAoTL6CcYy5uMnV3N7uSv1Et89qh%2FXFgutE96ffHMHhRE%2B92fkOpagS48qem7VBJX\
  q73DhfheNty8xyf4pU43ztpl6%2FuLI9jQFXVMkYdmCZJJ1eW077Hw3IFcyJF7qLaVJm0d4SXxfHf\
  NsFmKufALxZDbeXn8TejIoaUVhS0nq01ILhMFdUsgu5RYQd6LWF9R%2FStMt%2Bc0MKB2FP5e3LIL\
  K42ahSD%2BIgp6J22r6kvDmkhSiMXJHMH2AT%2BXCeogjrB2pBVkcXaauXC51JIK4vQDHiCCJtfSm\
  5Mtq0pJc9jo8o6ffqK2f1e2YHvvUWOb2sXEkjyTQDMGaLgh74oH6oCkTrzSLGTPfLivvDHlByZJBD\
  9baxTc5oFBBBSRLuw4oG0Y8pFjPaxEGQBorGNDWlf84HaoTZi5tP2bRFneMSWNP0NMO9Hkpmzq%2F\
  IBxiuMsFGEZbLAdkyEPGZegKwjqOc%2FeMKfKYT%2FS8UO6ow4HuODl%2B7uFKfP%2BbdUXAfnNUP\
  JyUIdnel9XZhqwgfp8zWScyqGstKo%2FeV7WCJC5T3o7TwzMOyQ3L0GOqUBrvYK9RgrsIbkAwiN2W\
  %2FyrBpdSvdjIGqidtfMpdZaJ%2Bwowc8WO%2FFoWCVmVtjvIlZ6omKMAs00NNy7fETgZ6RkP4f5P\
  JDKqlYQFMZu6mHSajotGpdGu5e%2FcKYXlQRXKSR2BGjpt2Y1tuoVVCjaFr2qX9BlYa%2FDlD7MDb\
  FXM7Xgzp9mbiwmx8Kqy9rKTEN7zpCefIExkMbJy3%2FbOPuLA%2B1ZVCiwEd0K&X-Amz-Signatur\
  e=f52796db3f9c1e47aafe6445bce9c7872afb65ed7c3e823e3a9185ea6900c124&X-Amz-Sign\
  edHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4664SS7VBYT%2F20250220%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250220T111833Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIADBNxC8oIEJ7vOHOrVcyDxpZkk3omlzm%2BMGrMFIgo3QAiEA5EKaIlSmq%2FlwcMVcox\
        1Ww%2B3%2BxSbRDxD%2BhZS0oge9%2By4qiAQIvP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FA\
        RAAGgw2Mzc0MjMxODM4MDUiDNtWgUVShCohdgtyYCrcAwQ9OcIPT%2BuS7oI3s3Wp%2BLL1\
        18l4cc6SbKsMyjQ08kfMHbfPpBbCGWYSTAmtnDTycaDnzZRLKBgjWhQp%2FaY2jQlgcaO7p\
        h2w%2FFLte3xpEP1FH1lIBZotJOESPUK1PEMVnEzwnC0BuHMaan2W%2BYzvsu14r3vFcZXl\
        MuZ54LEuYUUHgDAw5KS6G%2BOGBl%2B%2B5zbrYB%2FLgoR0DZxWdw65Y%2BRTeUq%2FRDs\
        hZukR%2FnuIBtm0LHSWht6FTKiZohuxtKBB2zxSNzEacynNaMi%2FK8FjCjjiXR1Gubq833\
        UxNGXrQZYrNH9o0I0wG061iTKARe000ayyGo1UQ5zf%2BN690H1PUw5xOD127esM8q60e9U\
        sDJ2KJ%2FSkI9XPp9V3XFyE9Ytz5AaNa77I7NX8DFltWPO%2BZOI3IIMSveibRSufoCDWKn\
        ZmMEpzcL3%2B9H%2FBUFdJNMEc7uI2et5TG0cVkWdietOhjPkDxBq0mcmoGoc6Dp6Yga%2F\
        DhITi%2FJ7C2%2BKic%2FTGhBzg93SVL8jdc5bGpGfnnwvtPTyvDQ0ZwR9kOtFhvtwvEV6s\
        le1o5jFe6FUfZRnz%2F7xi%2B0s6IuomedqzgQpG%2BPMFHv5cmXhP7MEYFIF7ZS6ApUllr\
        MoNsLCQQclaPleL4nGLMLaR3L0GOqUBE575YHSIrHN4dfHk2WYHB5HbrGw9uGrl3wmP1%2F\
        WD%2FhO7OqoToqRE4tp3dAKdwtGU01ZdD%2B74424i86Oj1fcoQC3s1TSlKsO3bcVUvzB6h\
        xkmr0ADYbMisVQTs5wMMGYkiuMcKIpOaC8qn95lojXHj2UCPlQfzgqIwlQi41R9Qvt3Jl2m\
        4XN1p%2BHM2HcCjpkZaixLuctgtet6HskQZtXoayVEaAwp&X-Amz-Signature=1c04b4aa\
        86b542b6d25dd31f98872c299aac62d53031943fb27e0e7902881b09&X-Amz-SignedHe\
        aders=host&x-id=GetObject"
      expiry_time: "2025-02-20T12:18:33.115Z"
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
UPDATE_TIME: "2025-02-20T11:20:25.917Z"
EXPIRY_TIME: "2025-02-20T12:20:07.909Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YQL5P2IC%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T112008Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCKzi%2FFpwKWfGMnAkHqsz%2Bj5HXrDjLJS%2Bh7aQvc1ZjfiwIhAJvRdI2z1%2BYzGiz8e3xlYcKbjSzPeiMA4cy1nDOSYovDKogECLz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwMbrmHXoXkDadjf9Eq3AOghd10d8rzY7kp9ez%2F%2FvFcnwOE5lehgR83a%2FXa5TYn6p4xeBwP1enEl%2Bhh95wm54t%2FB%2FGMwlbt5hSFpGZbKJyY3PEin7Zk7goNm1pDttIM2snUUFctfj4Fx%2BoUT2wRTy15e39xLSxJQrW5PLTkRFY4zYF8GodhyQbvuJd0oVev5KNq3FZouCi4STRg55On0sDdBmuVNOOMK2HD8Xb%2FKcuRh%2B%2BvTqovMHa%2ByMj1FaCrhBM0e3C%2Bd5r7p3bc%2FSPehDg6%2BKsG%2By2S%2FOrxk1ThvBSPbY6uafmg3%2FtGdIinbmBqvbgaI0xgOtFu8cAnXqMVHbTGgyojtxgS1zwyrgvuyYVt%2F533KbayDmd9sM1twkcUeejIKkUSc7af6dK2fGGSAMnJ2%2F6nee0fIeB8IwQ3tKbJwAKUsL8Wz2e3sEGElJEz0Ie1Jhp6GMZ8CY0cl9%2BD5HyOB3bhliN64PjyhyKyG12Fqi5V%2Fcwkypspza6AMeM%2Bdxs0wDzstFqQfxO%2FmXbh9XZ1w6pkNWgt%2BeYRzhJYaycX6QobKGLjNw0y1VvCFbftkw8K8Gx4iaqghsDy6%2FdTIeo8ybiwWiNJ6S5FNnO9qtUNptSM8je%2FB0E64IbKNrgy9e2D%2FbKuFF7pdjQWqjCtkNy9BjqkAUmSNCtZgtI14dKuPcU1zF23Xs9Yx7WMyRkY5bnVEOhS0jT0pxN5TaccbbXjy4zpjgoS4BTatGcpl%2BL7U1TfnKLwI88qFNSSqxIEWYTufyERyAgJ9aZyVJ9%2Fnh98LfgjjJxzXH8NlLVV2qJbZ%2FT6FP85v6fMTwc85X9BYdUnnFMvkHnWqdQIAK82Swjglc9RJpOEO8kJLiNYbDKmg7NRnzPnoayb&X-Amz-Signature=d350135b396babf0c3ee19355f49d264ac59a4bf89196da7d058e8ba0ef75668&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YQL5P2IC%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T112008Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCKzi%2FFpwKWfGMnAkHqsz%2Bj5HXrDjLJS%2Bh7aQvc1ZjfiwIhAJvRdI2z1%2BYzGiz8e3xlYcKbjSzPeiMA4cy1nDOSYovDKogECLz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwMbrmHXoXkDadjf9Eq3AOghd10d8rzY7kp9ez%2F%2FvFcnwOE5lehgR83a%2FXa5TYn6p4xeBwP1enEl%2Bhh95wm54t%2FB%2FGMwlbt5hSFpGZbKJyY3PEin7Zk7goNm1pDttIM2snUUFctfj4Fx%2BoUT2wRTy15e39xLSxJQrW5PLTkRFY4zYF8GodhyQbvuJd0oVev5KNq3FZouCi4STRg55On0sDdBmuVNOOMK2HD8Xb%2FKcuRh%2B%2BvTqovMHa%2ByMj1FaCrhBM0e3C%2Bd5r7p3bc%2FSPehDg6%2BKsG%2By2S%2FOrxk1ThvBSPbY6uafmg3%2FtGdIinbmBqvbgaI0xgOtFu8cAnXqMVHbTGgyojtxgS1zwyrgvuyYVt%2F533KbayDmd9sM1twkcUeejIKkUSc7af6dK2fGGSAMnJ2%2F6nee0fIeB8IwQ3tKbJwAKUsL8Wz2e3sEGElJEz0Ie1Jhp6GMZ8CY0cl9%2BD5HyOB3bhliN64PjyhyKyG12Fqi5V%2Fcwkypspza6AMeM%2Bdxs0wDzstFqQfxO%2FmXbh9XZ1w6pkNWgt%2BeYRzhJYaycX6QobKGLjNw0y1VvCFbftkw8K8Gx4iaqghsDy6%2FdTIeo8ybiwWiNJ6S5FNnO9qtUNptSM8je%2FB0E64IbKNrgy9e2D%2FbKuFF7pdjQWqjCtkNy9BjqkAUmSNCtZgtI14dKuPcU1zF23Xs9Yx7WMyRkY5bnVEOhS0jT0pxN5TaccbbXjy4zpjgoS4BTatGcpl%2BL7U1TfnKLwI88qFNSSqxIEWYTufyERyAgJ9aZyVJ9%2Fnh98LfgjjJxzXH8NlLVV2qJbZ%2FT6FP85v6fMTwc85X9BYdUnnFMvkHnWqdQIAK82Swjglc9RJpOEO8kJLiNYbDKmg7NRnzPnoayb&X-Amz-Signature=cd55a926e155f5cc7ca5498b4ab761f8e664ff6e37a541d1fc3c8ffd389ec9cd&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YQL5P2IC%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T112008Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCKzi%2FFpwKWfGMnAkHqsz%2Bj5HXrDjLJS%2Bh7aQvc1ZjfiwIhAJvRdI2z1%2BYzGiz8e3xlYcKbjSzPeiMA4cy1nDOSYovDKogECLz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwMbrmHXoXkDadjf9Eq3AOghd10d8rzY7kp9ez%2F%2FvFcnwOE5lehgR83a%2FXa5TYn6p4xeBwP1enEl%2Bhh95wm54t%2FB%2FGMwlbt5hSFpGZbKJyY3PEin7Zk7goNm1pDttIM2snUUFctfj4Fx%2BoUT2wRTy15e39xLSxJQrW5PLTkRFY4zYF8GodhyQbvuJd0oVev5KNq3FZouCi4STRg55On0sDdBmuVNOOMK2HD8Xb%2FKcuRh%2B%2BvTqovMHa%2ByMj1FaCrhBM0e3C%2Bd5r7p3bc%2FSPehDg6%2BKsG%2By2S%2FOrxk1ThvBSPbY6uafmg3%2FtGdIinbmBqvbgaI0xgOtFu8cAnXqMVHbTGgyojtxgS1zwyrgvuyYVt%2F533KbayDmd9sM1twkcUeejIKkUSc7af6dK2fGGSAMnJ2%2F6nee0fIeB8IwQ3tKbJwAKUsL8Wz2e3sEGElJEz0Ie1Jhp6GMZ8CY0cl9%2BD5HyOB3bhliN64PjyhyKyG12Fqi5V%2Fcwkypspza6AMeM%2Bdxs0wDzstFqQfxO%2FmXbh9XZ1w6pkNWgt%2BeYRzhJYaycX6QobKGLjNw0y1VvCFbftkw8K8Gx4iaqghsDy6%2FdTIeo8ybiwWiNJ6S5FNnO9qtUNptSM8je%2FB0E64IbKNrgy9e2D%2FbKuFF7pdjQWqjCtkNy9BjqkAUmSNCtZgtI14dKuPcU1zF23Xs9Yx7WMyRkY5bnVEOhS0jT0pxN5TaccbbXjy4zpjgoS4BTatGcpl%2BL7U1TfnKLwI88qFNSSqxIEWYTufyERyAgJ9aZyVJ9%2Fnh98LfgjjJxzXH8NlLVV2qJbZ%2FT6FP85v6fMTwc85X9BYdUnnFMvkHnWqdQIAK82Swjglc9RJpOEO8kJLiNYbDKmg7NRnzPnoayb&X-Amz-Signature=ae4d3aafaf0819ba3e6f3efe5e5500ceed5edbc5367e60cc8b354e94838e8234&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YQL5P2IC%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T112008Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCKzi%2FFpwKWfGMnAkHqsz%2Bj5HXrDjLJS%2Bh7aQvc1ZjfiwIhAJvRdI2z1%2BYzGiz8e3xlYcKbjSzPeiMA4cy1nDOSYovDKogECLz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwMbrmHXoXkDadjf9Eq3AOghd10d8rzY7kp9ez%2F%2FvFcnwOE5lehgR83a%2FXa5TYn6p4xeBwP1enEl%2Bhh95wm54t%2FB%2FGMwlbt5hSFpGZbKJyY3PEin7Zk7goNm1pDttIM2snUUFctfj4Fx%2BoUT2wRTy15e39xLSxJQrW5PLTkRFY4zYF8GodhyQbvuJd0oVev5KNq3FZouCi4STRg55On0sDdBmuVNOOMK2HD8Xb%2FKcuRh%2B%2BvTqovMHa%2ByMj1FaCrhBM0e3C%2Bd5r7p3bc%2FSPehDg6%2BKsG%2By2S%2FOrxk1ThvBSPbY6uafmg3%2FtGdIinbmBqvbgaI0xgOtFu8cAnXqMVHbTGgyojtxgS1zwyrgvuyYVt%2F533KbayDmd9sM1twkcUeejIKkUSc7af6dK2fGGSAMnJ2%2F6nee0fIeB8IwQ3tKbJwAKUsL8Wz2e3sEGElJEz0Ie1Jhp6GMZ8CY0cl9%2BD5HyOB3bhliN64PjyhyKyG12Fqi5V%2Fcwkypspza6AMeM%2Bdxs0wDzstFqQfxO%2FmXbh9XZ1w6pkNWgt%2BeYRzhJYaycX6QobKGLjNw0y1VvCFbftkw8K8Gx4iaqghsDy6%2FdTIeo8ybiwWiNJ6S5FNnO9qtUNptSM8je%2FB0E64IbKNrgy9e2D%2FbKuFF7pdjQWqjCtkNy9BjqkAUmSNCtZgtI14dKuPcU1zF23Xs9Yx7WMyRkY5bnVEOhS0jT0pxN5TaccbbXjy4zpjgoS4BTatGcpl%2BL7U1TfnKLwI88qFNSSqxIEWYTufyERyAgJ9aZyVJ9%2Fnh98LfgjjJxzXH8NlLVV2qJbZ%2FT6FP85v6fMTwc85X9BYdUnnFMvkHnWqdQIAK82Swjglc9RJpOEO8kJLiNYbDKmg7NRnzPnoayb&X-Amz-Signature=d0c08e653e46331905c31f830596504ae18bec5579a0204137df407cf9cdd420&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YQL5P2IC%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T112008Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCKzi%2FFpwKWfGMnAkHqsz%2Bj5HXrDjLJS%2Bh7aQvc1ZjfiwIhAJvRdI2z1%2BYzGiz8e3xlYcKbjSzPeiMA4cy1nDOSYovDKogECLz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwMbrmHXoXkDadjf9Eq3AOghd10d8rzY7kp9ez%2F%2FvFcnwOE5lehgR83a%2FXa5TYn6p4xeBwP1enEl%2Bhh95wm54t%2FB%2FGMwlbt5hSFpGZbKJyY3PEin7Zk7goNm1pDttIM2snUUFctfj4Fx%2BoUT2wRTy15e39xLSxJQrW5PLTkRFY4zYF8GodhyQbvuJd0oVev5KNq3FZouCi4STRg55On0sDdBmuVNOOMK2HD8Xb%2FKcuRh%2B%2BvTqovMHa%2ByMj1FaCrhBM0e3C%2Bd5r7p3bc%2FSPehDg6%2BKsG%2By2S%2FOrxk1ThvBSPbY6uafmg3%2FtGdIinbmBqvbgaI0xgOtFu8cAnXqMVHbTGgyojtxgS1zwyrgvuyYVt%2F533KbayDmd9sM1twkcUeejIKkUSc7af6dK2fGGSAMnJ2%2F6nee0fIeB8IwQ3tKbJwAKUsL8Wz2e3sEGElJEz0Ie1Jhp6GMZ8CY0cl9%2BD5HyOB3bhliN64PjyhyKyG12Fqi5V%2Fcwkypspza6AMeM%2Bdxs0wDzstFqQfxO%2FmXbh9XZ1w6pkNWgt%2BeYRzhJYaycX6QobKGLjNw0y1VvCFbftkw8K8Gx4iaqghsDy6%2FdTIeo8ybiwWiNJ6S5FNnO9qtUNptSM8je%2FB0E64IbKNrgy9e2D%2FbKuFF7pdjQWqjCtkNy9BjqkAUmSNCtZgtI14dKuPcU1zF23Xs9Yx7WMyRkY5bnVEOhS0jT0pxN5TaccbbXjy4zpjgoS4BTatGcpl%2BL7U1TfnKLwI88qFNSSqxIEWYTufyERyAgJ9aZyVJ9%2Fnh98LfgjjJxzXH8NlLVV2qJbZ%2FT6FP85v6fMTwc85X9BYdUnnFMvkHnWqdQIAK82Swjglc9RJpOEO8kJLiNYbDKmg7NRnzPnoayb&X-Amz-Signature=0c71e1ffcb940409a163b06d5e7b89a0be97e5e337cb3332f7ed26ad2d9894c4&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TVASJ225%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T112009Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCQpsA0CBcuOTvNlQKdpAVOawjC8kFlRX4k%2BtJVeGaBQQIhAPWxukBuD6uvrcF0ap5ZfMyl9nvSb2%2BmmovaNWBEwOPAKogECLz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxvxEYYBJTc6vjYRGUq3AOu9%2FCXsxWEGvJ1Q7i1QBYsyDFqY9HJ%2B2W2LzetRJhXvbmdGshWIvH5F1MJ2dTFK3Sc3WvKp%2F7D1I2UeOlavY1L7u8rSchvsbLRnd6v7HvZyrKrYiqJEVO2NT%2Bo2bKVfC%2F2%2FzUUXLEvKzDfYsywLk4cyTaDkXMzf2I%2BSZWArdqit2W%2ByoVrZWE0kYdFMB3PA9rZ9Adsp0vrjAexrGjO3DpJxED%2FIAOQu3AnKzvUNvppPDEQvwIFcZ7MJDYQQwNYQ1j7W7TUQgk5Ztfy2RaH4KQz1E%2BZFsaJ3ZH4TpKyBVdIx72J1okfGpo8XdZebrILOMYOGSQMEfK%2BO6oq6XaDWF45KkIEk2Tq%2B0xDr%2F6bGU0%2BH1fdTIJAlYt4VkKqD9tEf7kI37se3KVTuov80MwaGFqlCrSMyZc9CjvZxwSaFxwlyN7ynrAm8sGzjUIggIw8jw7YuL4IUyeJW4KcGIGdBzx0n3t2fZQrREQGvYcCf7IlKOkLsb%2BXFA7FAsAwG7O1huLKk%2FqzRogXHNaLjzHisaQSESUMCl6rG8mv%2Fqr9%2FJyXB3Xg2BZpOPX6WBqjeHA25X2FC2v9k7Rz6PKZFJ9N4tsx%2BlI0ifMZd5pZtACDOjzX8qg84M2T%2BjPQdwGYPjC3kdy9BjqkASVE3YJkYsAK2senxMUeS2bbZ7uCPX6dqhN46moMp6z%2FBWXtDv0rqZPRfU6VmNfUZbP43K%2FbMtdniuWMWH5mWnkQODBdYy6iN2%2FH994%2BDsz8fm63WxIIGc5aE8b04bUfRv6aKN6z%2B4H7u8DjUv2wcTATYFSyXaoIMxV1f6qkCW3sSyU2AXeaJQAUm%2BjXsRgEeZgV31bLvaoebEvUw4U8n1%2BvwbhD&X-Amz-Signature=1c5751c380e3fabf03115c7e16f26ed8b118c6ae1a6ff7005402178867185a58&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662YDG4D6Y%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T112010Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIDCoUmQkFJfW3eodAViQZmgFxFEOGxAPqE1p1h3ogxX5AiEA1geMuvm5C22ZePol9RwLQ7VGNxbFlO5VyHd6ShHGr4EqiAQIvP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHnTn2DgJG8qZwo%2BDyrcA7mavQjmWDKb2kf6tzdwWSZ%2Bb4dLF3yqBg9NY%2Fbwkgmr4fFqMMDR3Y%2BxljKqMAIMEjRoBwUffjG7CoHb7oERqRY0C74sA4IHNpueq4dedtqLw4NPAJkUdHAv%2BKGkDCqgCYCP5SICMEaLKbH%2BKnlO6jfw9GwDuLv6Qi%2BjZlj%2FYckH516BsgZ2GnW0KM4An%2BgtpGzBcXKqMnuarcToew9msH4%2B1c1jdshY3eZ0tObhPndL%2F2%2F0S9DUYOs61TDMbDVIoyABtCHm6Y2y4JMrzSkzQ0xzH%2FytWTPwaVJBqacDsFSPXIcfzDk3HtzdUzu%2BROsWm0%2FKbomyW2Ic0mHCiNnFD4SbcnPMpWiGR7GQobdTdDgz0EOwv%2BYokUNnPPH%2FQIC8sAXq%2B2NfDbCnvirxxKVht8ODB%2BeLjqvne7LbZdjQrElttMVIM88IFx3k5Nrg5HXCGR56KbnPq2cnSa1C3VobaaeFcRzZrSZVylybdbvV1GTUKQHX9wmwag9VIdgIfToT7ESFigWU0Fz%2BMJ5ulqr9Jpqr1pSSfOg9P44DI4wnPTx4bYk2rbrA1jBp6RDXzjeojhFMg5QbP%2ByA8qm3jlf2CvE8wA5TUWe2rMNroVpTMQKgoSOc4A6AVGJE5%2FjrMLaR3L0GOqUBehtOSrjzbChDqydvI7j67APg9PfHq0rKfvP2Ogye912fEFavKboYPQcsXeWTXTVojx6pIzH%2FW6WGnlG2nTMMz5YGv0NAeqL%2BXDBGppzyHIiSLHG89F39WAw2gLHWIUcOZjfq6rGfQphfSh2S4PcUNazo0p3yPQ%2FuAf7fmXVd9sNmAJByzoKDBDIiZtCnIcmE2J1Q9%2Fc%2FrDOCbrP6gDbf8euO7cbN&X-Amz-Signature=78335aa8712a3e84cbb2ceadfb40262ced77800c42d8417fd08ea9e10643fae7&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YQL5P2IC%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T112008Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCKzi%2FFpwKWfGMnAkHqsz%2Bj5HXrDjLJS%2Bh7aQvc1ZjfiwIhAJvRdI2z1%2BYzGiz8e3xlYcKbjSzPeiMA4cy1nDOSYovDKogECLz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwMbrmHXoXkDadjf9Eq3AOghd10d8rzY7kp9ez%2F%2FvFcnwOE5lehgR83a%2FXa5TYn6p4xeBwP1enEl%2Bhh95wm54t%2FB%2FGMwlbt5hSFpGZbKJyY3PEin7Zk7goNm1pDttIM2snUUFctfj4Fx%2BoUT2wRTy15e39xLSxJQrW5PLTkRFY4zYF8GodhyQbvuJd0oVev5KNq3FZouCi4STRg55On0sDdBmuVNOOMK2HD8Xb%2FKcuRh%2B%2BvTqovMHa%2ByMj1FaCrhBM0e3C%2Bd5r7p3bc%2FSPehDg6%2BKsG%2By2S%2FOrxk1ThvBSPbY6uafmg3%2FtGdIinbmBqvbgaI0xgOtFu8cAnXqMVHbTGgyojtxgS1zwyrgvuyYVt%2F533KbayDmd9sM1twkcUeejIKkUSc7af6dK2fGGSAMnJ2%2F6nee0fIeB8IwQ3tKbJwAKUsL8Wz2e3sEGElJEz0Ie1Jhp6GMZ8CY0cl9%2BD5HyOB3bhliN64PjyhyKyG12Fqi5V%2Fcwkypspza6AMeM%2Bdxs0wDzstFqQfxO%2FmXbh9XZ1w6pkNWgt%2BeYRzhJYaycX6QobKGLjNw0y1VvCFbftkw8K8Gx4iaqghsDy6%2FdTIeo8ybiwWiNJ6S5FNnO9qtUNptSM8je%2FB0E64IbKNrgy9e2D%2FbKuFF7pdjQWqjCtkNy9BjqkAUmSNCtZgtI14dKuPcU1zF23Xs9Yx7WMyRkY5bnVEOhS0jT0pxN5TaccbbXjy4zpjgoS4BTatGcpl%2BL7U1TfnKLwI88qFNSSqxIEWYTufyERyAgJ9aZyVJ9%2Fnh98LfgjjJxzXH8NlLVV2qJbZ%2FT6FP85v6fMTwc85X9BYdUnnFMvkHnWqdQIAK82Swjglc9RJpOEO8kJLiNYbDKmg7NRnzPnoayb&X-Amz-Signature=04567522b57eb278062413370d11a0b226d641ad8e399681a3c79add73fe9962&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YQL5P2IC%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T112008Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCKzi%2FFpwKWfGMnAkHqsz%2Bj5HXrDjLJS%2Bh7aQvc1ZjfiwIhAJvRdI2z1%2BYzGiz8e3xlYcKbjSzPeiMA4cy1nDOSYovDKogECLz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwMbrmHXoXkDadjf9Eq3AOghd10d8rzY7kp9ez%2F%2FvFcnwOE5lehgR83a%2FXa5TYn6p4xeBwP1enEl%2Bhh95wm54t%2FB%2FGMwlbt5hSFpGZbKJyY3PEin7Zk7goNm1pDttIM2snUUFctfj4Fx%2BoUT2wRTy15e39xLSxJQrW5PLTkRFY4zYF8GodhyQbvuJd0oVev5KNq3FZouCi4STRg55On0sDdBmuVNOOMK2HD8Xb%2FKcuRh%2B%2BvTqovMHa%2ByMj1FaCrhBM0e3C%2Bd5r7p3bc%2FSPehDg6%2BKsG%2By2S%2FOrxk1ThvBSPbY6uafmg3%2FtGdIinbmBqvbgaI0xgOtFu8cAnXqMVHbTGgyojtxgS1zwyrgvuyYVt%2F533KbayDmd9sM1twkcUeejIKkUSc7af6dK2fGGSAMnJ2%2F6nee0fIeB8IwQ3tKbJwAKUsL8Wz2e3sEGElJEz0Ie1Jhp6GMZ8CY0cl9%2BD5HyOB3bhliN64PjyhyKyG12Fqi5V%2Fcwkypspza6AMeM%2Bdxs0wDzstFqQfxO%2FmXbh9XZ1w6pkNWgt%2BeYRzhJYaycX6QobKGLjNw0y1VvCFbftkw8K8Gx4iaqghsDy6%2FdTIeo8ybiwWiNJ6S5FNnO9qtUNptSM8je%2FB0E64IbKNrgy9e2D%2FbKuFF7pdjQWqjCtkNy9BjqkAUmSNCtZgtI14dKuPcU1zF23Xs9Yx7WMyRkY5bnVEOhS0jT0pxN5TaccbbXjy4zpjgoS4BTatGcpl%2BL7U1TfnKLwI88qFNSSqxIEWYTufyERyAgJ9aZyVJ9%2Fnh98LfgjjJxzXH8NlLVV2qJbZ%2FT6FP85v6fMTwc85X9BYdUnnFMvkHnWqdQIAK82Swjglc9RJpOEO8kJLiNYbDKmg7NRnzPnoayb&X-Amz-Signature=0c3098fb5b9c284e1cdf57ab58ed55fdd4b2415b91b088e7dc9b82533b2d4d0f&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YQL5P2IC%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T112008Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCKzi%2FFpwKWfGMnAkHqsz%2Bj5HXrDjLJS%2Bh7aQvc1ZjfiwIhAJvRdI2z1%2BYzGiz8e3xlYcKbjSzPeiMA4cy1nDOSYovDKogECLz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwMbrmHXoXkDadjf9Eq3AOghd10d8rzY7kp9ez%2F%2FvFcnwOE5lehgR83a%2FXa5TYn6p4xeBwP1enEl%2Bhh95wm54t%2FB%2FGMwlbt5hSFpGZbKJyY3PEin7Zk7goNm1pDttIM2snUUFctfj4Fx%2BoUT2wRTy15e39xLSxJQrW5PLTkRFY4zYF8GodhyQbvuJd0oVev5KNq3FZouCi4STRg55On0sDdBmuVNOOMK2HD8Xb%2FKcuRh%2B%2BvTqovMHa%2ByMj1FaCrhBM0e3C%2Bd5r7p3bc%2FSPehDg6%2BKsG%2By2S%2FOrxk1ThvBSPbY6uafmg3%2FtGdIinbmBqvbgaI0xgOtFu8cAnXqMVHbTGgyojtxgS1zwyrgvuyYVt%2F533KbayDmd9sM1twkcUeejIKkUSc7af6dK2fGGSAMnJ2%2F6nee0fIeB8IwQ3tKbJwAKUsL8Wz2e3sEGElJEz0Ie1Jhp6GMZ8CY0cl9%2BD5HyOB3bhliN64PjyhyKyG12Fqi5V%2Fcwkypspza6AMeM%2Bdxs0wDzstFqQfxO%2FmXbh9XZ1w6pkNWgt%2BeYRzhJYaycX6QobKGLjNw0y1VvCFbftkw8K8Gx4iaqghsDy6%2FdTIeo8ybiwWiNJ6S5FNnO9qtUNptSM8je%2FB0E64IbKNrgy9e2D%2FbKuFF7pdjQWqjCtkNy9BjqkAUmSNCtZgtI14dKuPcU1zF23Xs9Yx7WMyRkY5bnVEOhS0jT0pxN5TaccbbXjy4zpjgoS4BTatGcpl%2BL7U1TfnKLwI88qFNSSqxIEWYTufyERyAgJ9aZyVJ9%2Fnh98LfgjjJxzXH8NlLVV2qJbZ%2FT6FP85v6fMTwc85X9BYdUnnFMvkHnWqdQIAK82Swjglc9RJpOEO8kJLiNYbDKmg7NRnzPnoayb&X-Amz-Signature=b2f46eed825429ef8862633ac8e2e16098e1a8dffc5a1d50eac40b9c996c935e&X-Amz-SignedHeaders=host&x-id=GetObject)


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

