---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466WU3BMUBR%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250129T072107Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEH8aCXVzLXdlc3QtMiJHMEUCIQCyGew7xAUBxO8BBms9q4cSj%2Bo2JgXs2%2F%2Bbz5XwxBuLx\
  wIgGazhFawK6EGlWTSefEvuxo6unrn%2Fc2XISlvuCsi1K3sqiAQIiP%2F%2F%2F%2F%2F%2F%2F%\
  2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMULN%2BHLFgrIQaJPtSrcA2qpban0CWd3vQ0DN4OZ1zH\
  rk6WdX%2BjUzFwtZT9bOGBVc1nR%2BmN%2FjXvyXy8ERG%2FYj9r8vzboVXLgjm1VCFhvinn8Zzvr\
  1YmOCSvmnJb%2BKcHF%2F0tt3ldGMvXVJp52bRt9tKPBVeiFb3AZSBKtOM4z1q3EBcAKlPdD%2F9M\
  QeRmeV2itjUJ9MY%2BDcCJxztqrTYDH29KlIVrCcAyZM%2BRH8EoXtmMfwMwfhnyVvEzg3RVVPPHL\
  tsoYt4kc2aTxr0Pe9o0DQY91TSi0%2FF85ngw2t7muqP%2BZ4r%2FOuFW6sIDjObnMcDBGgJQJdx5\
  ymH43ZotNYNMAdQi0qYKnZHLGgeW1ZdQ9MGfzIGxymG1I1wxMhuRzZy8ukN2fDh0FgUt4lM2Qgb%2\
  BRZk1se2Y1c8w5CsjmKNxHY%2BePsklBQJ4o5z9NF6IuUILJc7c0BpuSWqb9rYPwkZrbveDHQqV1i\
  pksqwooGnlvE6MHNUpmCcD0OYF3fZqNoT9Qc1MJ8msugtHJGsEtyenBCokHcE%2BY%2FjMzLNFFko\
  vnEnqbLcxm2F6dAph7b32e%2Fl3oQ3whP%2FNMdh1Jozg%2FE0LLBcg7%2B8WP0d%2Frq%2Fr7CCS\
  %2FaH4KSmsl5K1WB8mYfmxxv2rXEoCAwwO23sq0HDhlMNCS57wGOqUB%2FVgZN%2FdXyHP%2FQeVf\
  AyyWuQiMBtSjp4oZX%2FJ9MVCXiKY%2F138zMjXv5F1qOzdSTQFanrep6FLi0uaOLRdppYqpNnfTG\
  MMFBwpXc2lo3Vmh3b8oHd72fMqTgOAfz2vsYy%2BjEIfNzZMPpi9SwOYCrUJqvinI4dByamMd3tAw\
  z68fQ2NU57EaV5fiCKj26cEru8kvIwP911io7rAF0Zf7v%2BNlJnnaVHpZ&X-Amz-Signature=0c\
  eec5b9cb2d766bb7a19e5851c3715e51e431f0c6eab86f98ab73c6bbde8bf0&X-Amz-SignedHe\
  aders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4665WPDUSXG%2F20250129%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250129T071955Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEH8aCXVzLXdlc3QtMiJHMEUCIQCnTO9xVBRb35%2FphpMSmXI%2B8Uc\
        QlbeL7lMA0AEqPTONbwIgAZS5fTZ222BRxL1b89Wqv5WJvkBGHG4h1G8cXzZTJcYqiAQIh%\
        2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKjy7cX3BcEBJtq\
        C9CrcA4m8o7dNgNd%2FsKIFI1PwsS%2Fe2BP7Z2iVGwQ8gdAolmZv7NVYMRzUiOPNUiNkcT\
        JOSDJCir%2BJ7JqMwhbpf%2FA1Dqrae44RH2urLBACJ5ogFtz1tiXdLVtDsBntHmcBrOUb4\
        LRiUYtrMmcFJlYpmaN%2BhTF089WlkjD1EKXAW7dzIJn2v01nU2YsLNhS%2F3RY8LHdISa%\
        2FUsuYrv7GhgRGYSUcJ8adPpbCw%2Bip2h886jPN3g%2B2xRyCB0wtnc2qQAuTWVV4H7nok\
        1LU5cKH5dBgBtSHWJqXtpO0RnwoXJzEe3yn2IE8tTiGopte8jOmJTm0Jmqogw7YE5UnjF8l\
        fPXIsblyTgRLAGdSHThlKY7n8EdhQmgEp3zv9Bv8%2B3zuALntcyoDZSc00BBt2gFvS78Qx\
        Lq3yDqZLNm4DyzhpGlZOl2jV0Arspo%2BaZcHYjox83hn3aMOMM2r1iV9GCMupfncjef8Bb\
        xFq7RDBPQ2TTW6cv8axZI5RBmuxC0BZmVN%2FFEWe55LJ%2Fxf8CHUaKx8UfnsDx6c4bs%2\
        FMAG%2FATqiSza02OqNeYh3%2BGieWdSaye7%2BKl%2Fyn3Tjq9fGokPigaB%2B47BrycSu\
        WJWVQAlnXxKTFiIAo99Xr6cXT%2Bh62MHYbkGBJdZMMPuR57wGOqUB4IFjMQjMMga8ws5HQ\
        KW%2FQnOik8uT2%2BlNwaRiuQV1FidXfz8jBiGR%2FSysWPDwwi0ipiusG6TIYdNrZubC6v\
        DteNa%2FSUklOPQqO3QdihWK%2FHFs3BWfb%2B65GBOtZb83xJQ0DxpxVVZrrXa35TatQnj\
        wRg57NbY4EqvsKYYegVwCfzU91ji3yLpp2FWkul%2FJ0LTWDFf4VTEUa4OAhIE4m2R83n0v\
        yUUy&X-Amz-Signature=38d9d5041ba5ee2bedc8db167ec4b35761f67b537aa828e07a\
        8e69a482ad2e3f&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-01-29T08:19:55.203Z"
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
UPDATE_TIME: "2025-01-29T07:21:13.068Z"
EXPIRY_TIME: "2025-01-29T08:21:03.027Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664UXVM6A7%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T072103Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEH8aCXVzLXdlc3QtMiJIMEYCIQCXkCJVjOQseZ406L5YAOSx8p4jPSkHkSTdLme%2BvXtPdAIhAOPsnVIA72e7e3cYAnZwh9caut7W9YP1LtPGeJk1IZUqKogECIf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxPA2le6flY8edzTvwq3AN%2BCavuZkgEJfgeRjDD0QF32ICF5yIXwznsRUJV3uca%2FnHHYcHK8YpsVwyk4DFAti8eC0NTO3QthqSjLZnecdEvVhF7YaClL%2BRfRjSs4SkOwvYTqshASpcrekBl6qbiazwdK2q6uH4nE2arjlNNabOcTMJySERp4lI5CRxiw7wUlUVntJH8lDRiMhvHaQujk2FtyOIXf1oHRb1i44n%2FQUFTEelGaux1bE2Cr2NsQb%2Bc%2BYmvXJH62PwwhX2afED59CwKRlArRTCj4bFzn%2BrgBii5b6lzIwxCVqGvm%2FFCZi1pIld%2B4HLU1764r0Opout1OnTvYYj1bYhXHNRpMjmE7IVvrG%2B0t0c1SumXpUzOz5%2Bi9r8wiVeywzIbjOHugFoVRI%2FolRqMYvx%2BAxNpWLqOhbWHKduiNw%2FK7DlnjOuXlMlguJztqvPqazowkFbWrHG%2BhjIzs0YbYoBdj7k8wLNUGTjT5fNUzxsFfqJ8Y1LILCqfhce2CHPElzd%2Bs%2FQpN7aGfEDWGGrP3WE6Nz33bBI5PKYwmktwSCpwOAov%2BTGjhXDYYAmyVbl06rXrcIom55n9JQBH9Npuk960s5Zc5cD942fYs54xATiTDicR1oQeGKqTSRixSM3OQp1JmmsBiDD9kee8BjqkAYnpS%2BPIL6%2BZ9BKY4f9li3%2FxQAT7chOtrnsUoB9oQofXSf9L2IO86XJih83eViWWs3hBYWxbQ0IyqgGr35VRBvGLtv5Jo8byEFowVJedopHt2sX1YqtRKLVmGNQ2oplOPcRTF8pXo%2ByOBReMg7rAY2Thet%2B9%2BgA%2BOqOYi%2FYverNEaQvegAizNrzZvUc%2FaHRCB%2BR9OHYfjMFlw50fw%2B0egie5c3tC&X-Amz-Signature=e0baca770e5d299b2a02cea5481b0669543917f0739c729d4de22235d5cc4df8&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664UXVM6A7%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T072103Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEH8aCXVzLXdlc3QtMiJIMEYCIQCXkCJVjOQseZ406L5YAOSx8p4jPSkHkSTdLme%2BvXtPdAIhAOPsnVIA72e7e3cYAnZwh9caut7W9YP1LtPGeJk1IZUqKogECIf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxPA2le6flY8edzTvwq3AN%2BCavuZkgEJfgeRjDD0QF32ICF5yIXwznsRUJV3uca%2FnHHYcHK8YpsVwyk4DFAti8eC0NTO3QthqSjLZnecdEvVhF7YaClL%2BRfRjSs4SkOwvYTqshASpcrekBl6qbiazwdK2q6uH4nE2arjlNNabOcTMJySERp4lI5CRxiw7wUlUVntJH8lDRiMhvHaQujk2FtyOIXf1oHRb1i44n%2FQUFTEelGaux1bE2Cr2NsQb%2Bc%2BYmvXJH62PwwhX2afED59CwKRlArRTCj4bFzn%2BrgBii5b6lzIwxCVqGvm%2FFCZi1pIld%2B4HLU1764r0Opout1OnTvYYj1bYhXHNRpMjmE7IVvrG%2B0t0c1SumXpUzOz5%2Bi9r8wiVeywzIbjOHugFoVRI%2FolRqMYvx%2BAxNpWLqOhbWHKduiNw%2FK7DlnjOuXlMlguJztqvPqazowkFbWrHG%2BhjIzs0YbYoBdj7k8wLNUGTjT5fNUzxsFfqJ8Y1LILCqfhce2CHPElzd%2Bs%2FQpN7aGfEDWGGrP3WE6Nz33bBI5PKYwmktwSCpwOAov%2BTGjhXDYYAmyVbl06rXrcIom55n9JQBH9Npuk960s5Zc5cD942fYs54xATiTDicR1oQeGKqTSRixSM3OQp1JmmsBiDD9kee8BjqkAYnpS%2BPIL6%2BZ9BKY4f9li3%2FxQAT7chOtrnsUoB9oQofXSf9L2IO86XJih83eViWWs3hBYWxbQ0IyqgGr35VRBvGLtv5Jo8byEFowVJedopHt2sX1YqtRKLVmGNQ2oplOPcRTF8pXo%2ByOBReMg7rAY2Thet%2B9%2BgA%2BOqOYi%2FYverNEaQvegAizNrzZvUc%2FaHRCB%2BR9OHYfjMFlw50fw%2B0egie5c3tC&X-Amz-Signature=c4dc68f6676434d6375c4d66b3e3c1dfc6c5866506fc3242b7a06ef315ae2d35&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664UXVM6A7%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T072103Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEH8aCXVzLXdlc3QtMiJIMEYCIQCXkCJVjOQseZ406L5YAOSx8p4jPSkHkSTdLme%2BvXtPdAIhAOPsnVIA72e7e3cYAnZwh9caut7W9YP1LtPGeJk1IZUqKogECIf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxPA2le6flY8edzTvwq3AN%2BCavuZkgEJfgeRjDD0QF32ICF5yIXwznsRUJV3uca%2FnHHYcHK8YpsVwyk4DFAti8eC0NTO3QthqSjLZnecdEvVhF7YaClL%2BRfRjSs4SkOwvYTqshASpcrekBl6qbiazwdK2q6uH4nE2arjlNNabOcTMJySERp4lI5CRxiw7wUlUVntJH8lDRiMhvHaQujk2FtyOIXf1oHRb1i44n%2FQUFTEelGaux1bE2Cr2NsQb%2Bc%2BYmvXJH62PwwhX2afED59CwKRlArRTCj4bFzn%2BrgBii5b6lzIwxCVqGvm%2FFCZi1pIld%2B4HLU1764r0Opout1OnTvYYj1bYhXHNRpMjmE7IVvrG%2B0t0c1SumXpUzOz5%2Bi9r8wiVeywzIbjOHugFoVRI%2FolRqMYvx%2BAxNpWLqOhbWHKduiNw%2FK7DlnjOuXlMlguJztqvPqazowkFbWrHG%2BhjIzs0YbYoBdj7k8wLNUGTjT5fNUzxsFfqJ8Y1LILCqfhce2CHPElzd%2Bs%2FQpN7aGfEDWGGrP3WE6Nz33bBI5PKYwmktwSCpwOAov%2BTGjhXDYYAmyVbl06rXrcIom55n9JQBH9Npuk960s5Zc5cD942fYs54xATiTDicR1oQeGKqTSRixSM3OQp1JmmsBiDD9kee8BjqkAYnpS%2BPIL6%2BZ9BKY4f9li3%2FxQAT7chOtrnsUoB9oQofXSf9L2IO86XJih83eViWWs3hBYWxbQ0IyqgGr35VRBvGLtv5Jo8byEFowVJedopHt2sX1YqtRKLVmGNQ2oplOPcRTF8pXo%2ByOBReMg7rAY2Thet%2B9%2BgA%2BOqOYi%2FYverNEaQvegAizNrzZvUc%2FaHRCB%2BR9OHYfjMFlw50fw%2B0egie5c3tC&X-Amz-Signature=dce8b0468db53a4c4ccd6ac1eb4be1e7dc3beefda66d10c338abd85f35ed8d2c&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664UXVM6A7%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T072103Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEH8aCXVzLXdlc3QtMiJIMEYCIQCXkCJVjOQseZ406L5YAOSx8p4jPSkHkSTdLme%2BvXtPdAIhAOPsnVIA72e7e3cYAnZwh9caut7W9YP1LtPGeJk1IZUqKogECIf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxPA2le6flY8edzTvwq3AN%2BCavuZkgEJfgeRjDD0QF32ICF5yIXwznsRUJV3uca%2FnHHYcHK8YpsVwyk4DFAti8eC0NTO3QthqSjLZnecdEvVhF7YaClL%2BRfRjSs4SkOwvYTqshASpcrekBl6qbiazwdK2q6uH4nE2arjlNNabOcTMJySERp4lI5CRxiw7wUlUVntJH8lDRiMhvHaQujk2FtyOIXf1oHRb1i44n%2FQUFTEelGaux1bE2Cr2NsQb%2Bc%2BYmvXJH62PwwhX2afED59CwKRlArRTCj4bFzn%2BrgBii5b6lzIwxCVqGvm%2FFCZi1pIld%2B4HLU1764r0Opout1OnTvYYj1bYhXHNRpMjmE7IVvrG%2B0t0c1SumXpUzOz5%2Bi9r8wiVeywzIbjOHugFoVRI%2FolRqMYvx%2BAxNpWLqOhbWHKduiNw%2FK7DlnjOuXlMlguJztqvPqazowkFbWrHG%2BhjIzs0YbYoBdj7k8wLNUGTjT5fNUzxsFfqJ8Y1LILCqfhce2CHPElzd%2Bs%2FQpN7aGfEDWGGrP3WE6Nz33bBI5PKYwmktwSCpwOAov%2BTGjhXDYYAmyVbl06rXrcIom55n9JQBH9Npuk960s5Zc5cD942fYs54xATiTDicR1oQeGKqTSRixSM3OQp1JmmsBiDD9kee8BjqkAYnpS%2BPIL6%2BZ9BKY4f9li3%2FxQAT7chOtrnsUoB9oQofXSf9L2IO86XJih83eViWWs3hBYWxbQ0IyqgGr35VRBvGLtv5Jo8byEFowVJedopHt2sX1YqtRKLVmGNQ2oplOPcRTF8pXo%2ByOBReMg7rAY2Thet%2B9%2BgA%2BOqOYi%2FYverNEaQvegAizNrzZvUc%2FaHRCB%2BR9OHYfjMFlw50fw%2B0egie5c3tC&X-Amz-Signature=3ffcda7fdc16fa3a8e7bdc5c2cbf24224e465da7c313a9ee545b21367c607a00&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664UXVM6A7%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T072103Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEH8aCXVzLXdlc3QtMiJIMEYCIQCXkCJVjOQseZ406L5YAOSx8p4jPSkHkSTdLme%2BvXtPdAIhAOPsnVIA72e7e3cYAnZwh9caut7W9YP1LtPGeJk1IZUqKogECIf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxPA2le6flY8edzTvwq3AN%2BCavuZkgEJfgeRjDD0QF32ICF5yIXwznsRUJV3uca%2FnHHYcHK8YpsVwyk4DFAti8eC0NTO3QthqSjLZnecdEvVhF7YaClL%2BRfRjSs4SkOwvYTqshASpcrekBl6qbiazwdK2q6uH4nE2arjlNNabOcTMJySERp4lI5CRxiw7wUlUVntJH8lDRiMhvHaQujk2FtyOIXf1oHRb1i44n%2FQUFTEelGaux1bE2Cr2NsQb%2Bc%2BYmvXJH62PwwhX2afED59CwKRlArRTCj4bFzn%2BrgBii5b6lzIwxCVqGvm%2FFCZi1pIld%2B4HLU1764r0Opout1OnTvYYj1bYhXHNRpMjmE7IVvrG%2B0t0c1SumXpUzOz5%2Bi9r8wiVeywzIbjOHugFoVRI%2FolRqMYvx%2BAxNpWLqOhbWHKduiNw%2FK7DlnjOuXlMlguJztqvPqazowkFbWrHG%2BhjIzs0YbYoBdj7k8wLNUGTjT5fNUzxsFfqJ8Y1LILCqfhce2CHPElzd%2Bs%2FQpN7aGfEDWGGrP3WE6Nz33bBI5PKYwmktwSCpwOAov%2BTGjhXDYYAmyVbl06rXrcIom55n9JQBH9Npuk960s5Zc5cD942fYs54xATiTDicR1oQeGKqTSRixSM3OQp1JmmsBiDD9kee8BjqkAYnpS%2BPIL6%2BZ9BKY4f9li3%2FxQAT7chOtrnsUoB9oQofXSf9L2IO86XJih83eViWWs3hBYWxbQ0IyqgGr35VRBvGLtv5Jo8byEFowVJedopHt2sX1YqtRKLVmGNQ2oplOPcRTF8pXo%2ByOBReMg7rAY2Thet%2B9%2BgA%2BOqOYi%2FYverNEaQvegAizNrzZvUc%2FaHRCB%2BR9OHYfjMFlw50fw%2B0egie5c3tC&X-Amz-Signature=fe0a981e0e3b55e7603a75c88bafc1fc6e8cbec4609129a5a056074e05b7863f&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663AA6NRB2%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T072103Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEH8aCXVzLXdlc3QtMiJHMEUCIGAhZcArdzvW3gvxcbD%2FxbKIgMdJ2r4h1YtWy180cX8RAiEA9clzZpFoBcBtqnDtw63GdcgN56i%2F7ihsqoHq7IyTd6kqiAQIh%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDBC2p0jOXMptpwRR3CrcA0xbTSlt%2BNjjPkiGTey%2FPdU8a9u2Wl2OLFy6cNhnl2XD9t%2Fz%2BFZ%2BgKKl%2BszkP1xW%2FnwiBS0MvWmn24QzghR1CPi3%2BaLKX2d3g2L%2F5IBwJMf4bGIx%2FqvylmVo2dZQ6Td%2FxOHO7aSSEHtJVMg5%2F5d0bIfexGQgcgzGq6cTgIEIpipYnVWG54rSD%2B7N4EIO%2FP8kRYnrsnFRgGnGe95hqFW8QBYA1hYMcrTqE9JqD23zzxbgrz5sRcrlc%2FcBhm%2FiSNScHkX6QBd0NTFIjnF%2BTmfsZnZN%2FMma2izFNWuXx76dDrbRUnWIJE7mtuoFoXwMlWPT8w8aVxr8It4dF3WM8tiTr%2BADFixAajrMA0IzjtLfkmEv2%2FeAyCQayVHhBwhgJvqIYbiwxVuclSBKTQbp4%2BDdvVfHJHdns8IcsCPQO4A%2BGzMjZejJqq8rBWdes6SdpFu6ltccmDJhBVJs0sOpn78QI43KPWPv3gvgpsQQ36jQyFfTExCuuZ3XD4qfpaTLRQckOqd55XbKcJ2AY2ZTeP7U0WOMS%2B9zmZ5%2FlhEWl62dPn5b3TI%2FSkjLPN%2B%2BQEWY5gLfMo6l1jAmLIfYe0qlKhMOi4YhDehtmQLfJWvwFr8XsoKoR2K6PdYNGfv42Qv1MIuS57wGOqUBjUnXOT2zn4CIukmMyfyb7jVeCUNMxYuY%2B4wbmsaSuZqQlKSEYJgQ427k31Yy9fEYBOBKc6xNwYV8CBtv1bglwyL9x4WiNSCI9BTmC%2FtDMiuGhHwsIQ01Xm1xbE9ci1g2SyGB6coMRqhqxEa88UNoJGO8y7LNfUKet1dyvfVLb2oCp2Rdao2uk2F1vmJHznY6GJx354S12AYluZ60FZc%2F8S3hrXUp&X-Amz-Signature=06f2de9d4a8cf19c7b98b9f333c5ae8fbc91c9f71e4874af615d5c89a0555687&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466USYCU525%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T072107Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEH8aCXVzLXdlc3QtMiJGMEQCICRr3AmTdClRvlVR0ObKkUB9QXSZs8CV%2F%2Bn6baKrv99UAiBQLLp5gnP6LVkGJ4g7x4zTBwzNiPKpYHTUdiM8y76BZCqIBAiH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMyYQKXMTkIeuQuv3ZKtwDWFwSiSm6%2FYXCPKKWf3fk5AHabxWbr2FgzeZ0Tqlbl72MwUJlz7VHPbxDm0pC7Xv8bmlMwdEo8L8Q%2FzzORD2dx1scJFLqbGdZgX0rxg9LNrUWdkOMLKPMaCBJN%2FKefrQ%2BwAt1I4e0UPATNJMczy0dJ%2FLOC%2Bgn%2FdmeLESBIclebWQ0GQQM7IZ93muIhosVubZrwysU00UyE6doeq4xmvCRXRNifOButpy8%2F2BBultyOHjzbaLxL8i8g8DTQ6qXYTAoMssODeUKs%2FuxSUbHqz90d%2F8YT8yHF6gWZvpLzYCGT1%2F2LzSBV9ZiSVJ1yToCzphuED8LPg%2F3P0K77Ja5rEQhchK6q0VoS2fv2JrfSPlABlFfPDjqPteD7CR9OXDuxzG2YkfYCV%2BZklLFwmOC0D2y7l3afYeDrnNhZc1Jtu9FiPY9AwrqBJTyZROI60X0p4B1XLaMZNTtH8olpnFhPGIwNMbBBg%2FC6ShUtF1mH57yY6oSLhntWWDWnkLaTq7WBFxur%2F9Hvz6MtajPq6CGlnuNRp%2BSzDtWVz7ihegKtB926um3u6gopxn5k524xcNyvHMzyY9DppZ8NZxRKJaGdQkbATe3WehUmTJPqg3imEBGA44dIFjE1kskcTqx1wEwp5HnvAY6pgEpCWNkVWqiceEFeL08OqOsV0%2Fc8Hm1g%2BS%2FzsLzOdjTvNvceLG9Nw9nZg%2B3S85A60H9eCNfo9VO%2Bm1RomBlWvGMeZalf%2F88n7N%2B0uuZVkRBggv%2BHtwoeq5pLeDmnEK5eUKZGriHM9PhixbZP7TIHJeS6NBgEjnLcSBqE9%2FFQ2PmmIRboIu3sXt2vyUh0eohgbEst%2FKIooPYyOBnNWpD1Wl6iGwzFjt2&X-Amz-Signature=9d9f03f98cbe8b21ad1adf6c646bfdfe960aee9aa04b277b55b4fb32c04063c4&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664UXVM6A7%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T072103Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEH8aCXVzLXdlc3QtMiJIMEYCIQCXkCJVjOQseZ406L5YAOSx8p4jPSkHkSTdLme%2BvXtPdAIhAOPsnVIA72e7e3cYAnZwh9caut7W9YP1LtPGeJk1IZUqKogECIf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxPA2le6flY8edzTvwq3AN%2BCavuZkgEJfgeRjDD0QF32ICF5yIXwznsRUJV3uca%2FnHHYcHK8YpsVwyk4DFAti8eC0NTO3QthqSjLZnecdEvVhF7YaClL%2BRfRjSs4SkOwvYTqshASpcrekBl6qbiazwdK2q6uH4nE2arjlNNabOcTMJySERp4lI5CRxiw7wUlUVntJH8lDRiMhvHaQujk2FtyOIXf1oHRb1i44n%2FQUFTEelGaux1bE2Cr2NsQb%2Bc%2BYmvXJH62PwwhX2afED59CwKRlArRTCj4bFzn%2BrgBii5b6lzIwxCVqGvm%2FFCZi1pIld%2B4HLU1764r0Opout1OnTvYYj1bYhXHNRpMjmE7IVvrG%2B0t0c1SumXpUzOz5%2Bi9r8wiVeywzIbjOHugFoVRI%2FolRqMYvx%2BAxNpWLqOhbWHKduiNw%2FK7DlnjOuXlMlguJztqvPqazowkFbWrHG%2BhjIzs0YbYoBdj7k8wLNUGTjT5fNUzxsFfqJ8Y1LILCqfhce2CHPElzd%2Bs%2FQpN7aGfEDWGGrP3WE6Nz33bBI5PKYwmktwSCpwOAov%2BTGjhXDYYAmyVbl06rXrcIom55n9JQBH9Npuk960s5Zc5cD942fYs54xATiTDicR1oQeGKqTSRixSM3OQp1JmmsBiDD9kee8BjqkAYnpS%2BPIL6%2BZ9BKY4f9li3%2FxQAT7chOtrnsUoB9oQofXSf9L2IO86XJih83eViWWs3hBYWxbQ0IyqgGr35VRBvGLtv5Jo8byEFowVJedopHt2sX1YqtRKLVmGNQ2oplOPcRTF8pXo%2ByOBReMg7rAY2Thet%2B9%2BgA%2BOqOYi%2FYverNEaQvegAizNrzZvUc%2FaHRCB%2BR9OHYfjMFlw50fw%2B0egie5c3tC&X-Amz-Signature=47046a50d85fc85f69653462a0d6754ba19f3e44237a123896d9c4a8c981f3c8&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664UXVM6A7%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T072103Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEH8aCXVzLXdlc3QtMiJIMEYCIQCXkCJVjOQseZ406L5YAOSx8p4jPSkHkSTdLme%2BvXtPdAIhAOPsnVIA72e7e3cYAnZwh9caut7W9YP1LtPGeJk1IZUqKogECIf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxPA2le6flY8edzTvwq3AN%2BCavuZkgEJfgeRjDD0QF32ICF5yIXwznsRUJV3uca%2FnHHYcHK8YpsVwyk4DFAti8eC0NTO3QthqSjLZnecdEvVhF7YaClL%2BRfRjSs4SkOwvYTqshASpcrekBl6qbiazwdK2q6uH4nE2arjlNNabOcTMJySERp4lI5CRxiw7wUlUVntJH8lDRiMhvHaQujk2FtyOIXf1oHRb1i44n%2FQUFTEelGaux1bE2Cr2NsQb%2Bc%2BYmvXJH62PwwhX2afED59CwKRlArRTCj4bFzn%2BrgBii5b6lzIwxCVqGvm%2FFCZi1pIld%2B4HLU1764r0Opout1OnTvYYj1bYhXHNRpMjmE7IVvrG%2B0t0c1SumXpUzOz5%2Bi9r8wiVeywzIbjOHugFoVRI%2FolRqMYvx%2BAxNpWLqOhbWHKduiNw%2FK7DlnjOuXlMlguJztqvPqazowkFbWrHG%2BhjIzs0YbYoBdj7k8wLNUGTjT5fNUzxsFfqJ8Y1LILCqfhce2CHPElzd%2Bs%2FQpN7aGfEDWGGrP3WE6Nz33bBI5PKYwmktwSCpwOAov%2BTGjhXDYYAmyVbl06rXrcIom55n9JQBH9Npuk960s5Zc5cD942fYs54xATiTDicR1oQeGKqTSRixSM3OQp1JmmsBiDD9kee8BjqkAYnpS%2BPIL6%2BZ9BKY4f9li3%2FxQAT7chOtrnsUoB9oQofXSf9L2IO86XJih83eViWWs3hBYWxbQ0IyqgGr35VRBvGLtv5Jo8byEFowVJedopHt2sX1YqtRKLVmGNQ2oplOPcRTF8pXo%2ByOBReMg7rAY2Thet%2B9%2BgA%2BOqOYi%2FYverNEaQvegAizNrzZvUc%2FaHRCB%2BR9OHYfjMFlw50fw%2B0egie5c3tC&X-Amz-Signature=03c4075018e19dc791321d9d97a06071ecc160f21dd748800caf37a2fdeb8190&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664UXVM6A7%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T072103Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEH8aCXVzLXdlc3QtMiJIMEYCIQCXkCJVjOQseZ406L5YAOSx8p4jPSkHkSTdLme%2BvXtPdAIhAOPsnVIA72e7e3cYAnZwh9caut7W9YP1LtPGeJk1IZUqKogECIf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxPA2le6flY8edzTvwq3AN%2BCavuZkgEJfgeRjDD0QF32ICF5yIXwznsRUJV3uca%2FnHHYcHK8YpsVwyk4DFAti8eC0NTO3QthqSjLZnecdEvVhF7YaClL%2BRfRjSs4SkOwvYTqshASpcrekBl6qbiazwdK2q6uH4nE2arjlNNabOcTMJySERp4lI5CRxiw7wUlUVntJH8lDRiMhvHaQujk2FtyOIXf1oHRb1i44n%2FQUFTEelGaux1bE2Cr2NsQb%2Bc%2BYmvXJH62PwwhX2afED59CwKRlArRTCj4bFzn%2BrgBii5b6lzIwxCVqGvm%2FFCZi1pIld%2B4HLU1764r0Opout1OnTvYYj1bYhXHNRpMjmE7IVvrG%2B0t0c1SumXpUzOz5%2Bi9r8wiVeywzIbjOHugFoVRI%2FolRqMYvx%2BAxNpWLqOhbWHKduiNw%2FK7DlnjOuXlMlguJztqvPqazowkFbWrHG%2BhjIzs0YbYoBdj7k8wLNUGTjT5fNUzxsFfqJ8Y1LILCqfhce2CHPElzd%2Bs%2FQpN7aGfEDWGGrP3WE6Nz33bBI5PKYwmktwSCpwOAov%2BTGjhXDYYAmyVbl06rXrcIom55n9JQBH9Npuk960s5Zc5cD942fYs54xATiTDicR1oQeGKqTSRixSM3OQp1JmmsBiDD9kee8BjqkAYnpS%2BPIL6%2BZ9BKY4f9li3%2FxQAT7chOtrnsUoB9oQofXSf9L2IO86XJih83eViWWs3hBYWxbQ0IyqgGr35VRBvGLtv5Jo8byEFowVJedopHt2sX1YqtRKLVmGNQ2oplOPcRTF8pXo%2ByOBReMg7rAY2Thet%2B9%2BgA%2BOqOYi%2FYverNEaQvegAizNrzZvUc%2FaHRCB%2BR9OHYfjMFlw50fw%2B0egie5c3tC&X-Amz-Signature=25375d70b0960e575ca85fbcc625b68e785259d2fdb20bb0b40e2516d8dba603&X-Amz-SignedHeaders=host&x-id=GetObject)


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

