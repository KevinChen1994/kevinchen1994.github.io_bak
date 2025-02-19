---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466XWASFTAL%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250219T014837Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEHIaCXVzLXdlc3QtMiJIMEYCIQDtHuw1XyZc5wJ3J0MJB%2BASvb7BZT1Ds43q3Azv9ZNvFgIhA\
  Mw9EM6DWN3SupAUb4Q4cYYWKEENljBkhGDe30e4TESZKogECJv%2F%2F%2F%2F%2F%2F%2F%2F%2F\
  %2FwEQABoMNjM3NDIzMTgzODA1IgysG4NBxWfj%2B0IITYkq3AMTbJUdeXJZGqd7%2BsxfkTyliXJ\
  pD%2F5HSWl9DU46mrVxs2BBp3nOJ56qnk3Ac%2By8drPk4IoRk5en8GFKmSiRSbHOQ3kTq68QAOJD\
  0afoEYZcF5G9kIpIxXnn%2BUWwLGTxDR4h1UA3rCip2nrKwyQb%2FK8kVlu1BcqPUFhiUIy3nus8v\
  mJzMfjcR5TOAFfwoUDJmpRi4mDBwH8qpE6w2YXN2%2FcLy8K%2FLsgSA%2F%2BLDWi%2Bs2I%2FAI\
  %2FVbim8fSMxbmlG9Y9E%2FiJT4xssbFkx09xXir69muDbe6SNnlEcjsOYUQXBybFGGDi6%2BS%2B\
  tqqZN%2BhLMM%2Bmyj2jE8K3Pyj1%2BN1Tmht9XWijTWq5pMzc7eRimeR1ycWB5%2BI2Wv2hyMmOG\
  S755jzDLySv5tS5oCKee5YtulZTCq5WtHs7DBYZ0UIz1JxyCQtKbyRxfN%2FuXg1Le7KrKCMIQgJ7\
  Gg5LrJll9dYYNNm%2FM1pHWfn%2Bm%2BS6%2BG1rw7XMJTYFBrHxbGK5xOkBoHcyCtXWd30MKBqrB\
  K0zv52CR%2BtdC0GXAzpkyONvWtXgbHC9LWuNIcSKzR00PJIV1BvTWU1u46U8gLWrJBfJ3bM5szin\
  Y0sy4lIgin%2BAkfvO9I12ZS%2Fs0zdCETaPMWKhsRfyE9DDP6dS9BjqkAQuwrsCwVqo2F6Vd4pkp\
  9S%2Fzp5zMGeiiaZEWxTRw9fQw8MQJoCk2ms5Ip2NIKWup%2Bf8oK0rNoxbqu%2B7R7bJzhbG0QtA\
  %2F%2FPTfUhW2pHOONUzrlDRqVNnx2lXwxL0z%2F7%2F3swPB8Yip7Vkw9U9%2F9LaHT1wgYAdZnb\
  xQaReWtfUhta3MVC5p9GSJrLhhQIUP83ggvLYVracqhCd1ZORbEOU8KJvpa5GL&X-Amz-Signatur\
  e=0b5026429503192133bea35c70686e77b235d68928da3d85a7510b6110284507&X-Amz-Sign\
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
        redential=ASIAZI2LB466ZGUBUZYX%2F20250219%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250219T014720Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEHIaCXVzLXdlc3QtMiJHMEUCIQDe7x9bL2D4XbtzKaJLjhyUjLsMnq9\
        BMtFPqgWciEfQNQIgX1P7GnVR4UbDK6owzpVUx6G1EHO0TTr6abh%2F3%2FvZH1wqiAQIm%\
        2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNvOLUFe3YOzt40\
        uGSrcA5ydl8lFYy9ymMvdUn5k4eVkaet8PNKDBxkToAh5l4IGZ86hXD6dD7aKJiA8P8Vv1u\
        lr3QQDBcFMvDjpeXeGFo5rOydBd0V%2Bvmod9HaNBYCV1qblBsMPdzlED7kAjEKYEAalavt\
        5y22qKNeHWhf0VDP9uQ69iUIB4hDfVDOXfLwDlaX98YxlqktHwPuZobQ5PZq6NacdTBpKFK\
        pQqXI68J%2B5HTxAgrBYNK5isfn12XOCGvUE6Z1DJPoz%2BVHMSlKfBlzadN74yPBH%2FpM\
        TOo51hgGlBa8LkP%2F1loETCX1qTJ2WtfX2EorhTYJecRJi9nANxdS292RivnmuM0IhOiVe\
        pJ7EKv%2B2gZBMt5i8%2F%2FpeHVyBUOeFpCl8L5fPaus72%2Fu3rk%2FKtd6z1EeO%2FL9\
        8lM7hROkIX8smn72wIGvRqCGhShN4FPPzIHsayCJOvti2OM%2BVUS2%2FOIpKaV5fYCowaV\
        7uGlThwb0FPMqsnjeUQT9bMoxYi%2BK01OoflGtY1w8rH%2Fs2lj%2BNgQjEhTTIUcb6uAs\
        RtDIv%2B%2Ft28Onykfnip2G4tViezFCn3EaPEIuMrXECkX4Z9WaMO%2BpPWA9jnohlrUh8\
        TSL1Ju1%2FIaSesUHegCZuw%2FrJNF6c6Eix3O8nMQJQMM7o1L0GOqUB%2Bt%2BFkrsUwD%\
        2FdtFBoM0MKbQc6W8augK28%2F5Hd%2B9dTDYjJ8HbQp2yD6stYsY5fdziBz5IoZ4wCNQg6\
        wjwN%2BVVWhcH55flh84DM6%2FejF4gvYK7FkfH3KOhYSQbCnIlYma%2BbrgtoHY%2BYZGM\
        AoSz1qpnCrJ4WpJccZye6O17508RdIdLAb2KMsuDoZ3CLP1%2FKtBBvz%2BguRXDTaQnyMM\
        GYkeuNwHytlMYJ&X-Amz-Signature=13fccd17aba64fb8463930358514fd535dd39ed1\
        060494a7c3df1c40fe4b9c05&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-19T02:47:20.467Z"
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
UPDATE_TIME: "2025-02-19T01:48:42.549Z"
EXPIRY_TIME: "2025-02-19T02:48:33.944Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665K2YHGX3%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T014834Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHIaCXVzLXdlc3QtMiJHMEUCIFIhN7A7jfKITBh1zAWxstU8GL603okC6%2Fz%2Bj19IuH52AiEA9pne4K7Z8nlYnl8X6VJWy4BP7rBJrHiWkcfozby31rIqiAQIm%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDJoy8DvkOH%2FUXN%2BBbSrcA9iG%2BbKmmWheRVSZjb8O2GH9GqfhCZCe8SyXDQHmIoPSV14tqI9ipWh4%2FvUPkyrLvq2Q0GiFXbVWVf1si2NxTWkrHRlbdCCC%2FsvsjIs3u4g%2BzNOSypl%2BZvfsKMW7xIZBvfNw8T59kgHLwT0UdmPqmUd71JcLvyR%2BwL02xxOPMIjuA7CPoyZxPzgTAd2fo5F5AAyLijYoRG4KOU3Si0ntepMIBolQhYUrZz5TEQ9qvlh8HW2CAJfUc8o6pd5Ij%2FKotp8Z1%2BGg0NUTKBrjmQss9OpYSw2Upy4iHg7ZmkQZFgwYXq2nFfbCh%2B9LCcB7cRogo7sPQZ3osGuRpm9SJnISyJ9xeyd%2Bq2anFjfNx6rSSnlST9AjBxDb4bE9Sd%2FWCjYyBojf5yN98iTGLJOCtucX1ppWHw099t%2FRtDEc9cvSOjex809rLOJPBL%2BzzH2Cqi%2BFrrNB%2Bj%2B9ElhsGI9PYJpybn4zPyXhRoH9f1S6XVXi8er2llRDWPdviyLKXx%2BWsVOdCXgQT9wKzK1MGM4BCbO1ZknckTAoi973vNyYOPQ%2B6tyKlVN4t%2BMu9p8rhOFxdP9aCZKYua1x0yZDpl6%2F8K2IktpMxcOg%2BfLgNTvYebxcOv5iIjswVqcrLFA2CCKqMLro1L0GOqUBkjjJ0BnMr0%2ByIDr2TxLO7s43KMpFR%2FCOKqXo9OVgbWNQ2UUNh0Hy3fR5qLPLWM4%2Fa844eG5GfXr%2BK6bUJ%2FYn69l%2BNq3EvQEVYzVL9meZPmULUzo7Xf0MJqy6TfV3u9q6HZFkrvct2IP1GBjxNwZIt17amWTvCF6X9XpGBOOlbPXTmRSuUG15BCIH3S8gqsBmr7lAVZnCvExvC7gPJgtGBKqKT3Qx&X-Amz-Signature=c5f7b6d9a39c949abfbd7bb4f7039dbb1225ae1aa0545df7a4a6dc23cfc84c9a&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665K2YHGX3%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T014834Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHIaCXVzLXdlc3QtMiJHMEUCIFIhN7A7jfKITBh1zAWxstU8GL603okC6%2Fz%2Bj19IuH52AiEA9pne4K7Z8nlYnl8X6VJWy4BP7rBJrHiWkcfozby31rIqiAQIm%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDJoy8DvkOH%2FUXN%2BBbSrcA9iG%2BbKmmWheRVSZjb8O2GH9GqfhCZCe8SyXDQHmIoPSV14tqI9ipWh4%2FvUPkyrLvq2Q0GiFXbVWVf1si2NxTWkrHRlbdCCC%2FsvsjIs3u4g%2BzNOSypl%2BZvfsKMW7xIZBvfNw8T59kgHLwT0UdmPqmUd71JcLvyR%2BwL02xxOPMIjuA7CPoyZxPzgTAd2fo5F5AAyLijYoRG4KOU3Si0ntepMIBolQhYUrZz5TEQ9qvlh8HW2CAJfUc8o6pd5Ij%2FKotp8Z1%2BGg0NUTKBrjmQss9OpYSw2Upy4iHg7ZmkQZFgwYXq2nFfbCh%2B9LCcB7cRogo7sPQZ3osGuRpm9SJnISyJ9xeyd%2Bq2anFjfNx6rSSnlST9AjBxDb4bE9Sd%2FWCjYyBojf5yN98iTGLJOCtucX1ppWHw099t%2FRtDEc9cvSOjex809rLOJPBL%2BzzH2Cqi%2BFrrNB%2Bj%2B9ElhsGI9PYJpybn4zPyXhRoH9f1S6XVXi8er2llRDWPdviyLKXx%2BWsVOdCXgQT9wKzK1MGM4BCbO1ZknckTAoi973vNyYOPQ%2B6tyKlVN4t%2BMu9p8rhOFxdP9aCZKYua1x0yZDpl6%2F8K2IktpMxcOg%2BfLgNTvYebxcOv5iIjswVqcrLFA2CCKqMLro1L0GOqUBkjjJ0BnMr0%2ByIDr2TxLO7s43KMpFR%2FCOKqXo9OVgbWNQ2UUNh0Hy3fR5qLPLWM4%2Fa844eG5GfXr%2BK6bUJ%2FYn69l%2BNq3EvQEVYzVL9meZPmULUzo7Xf0MJqy6TfV3u9q6HZFkrvct2IP1GBjxNwZIt17amWTvCF6X9XpGBOOlbPXTmRSuUG15BCIH3S8gqsBmr7lAVZnCvExvC7gPJgtGBKqKT3Qx&X-Amz-Signature=05115f73ed3788893a75ac1771acd0dac68e5b2489b86241d7da79823515046d&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665K2YHGX3%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T014834Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHIaCXVzLXdlc3QtMiJHMEUCIFIhN7A7jfKITBh1zAWxstU8GL603okC6%2Fz%2Bj19IuH52AiEA9pne4K7Z8nlYnl8X6VJWy4BP7rBJrHiWkcfozby31rIqiAQIm%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDJoy8DvkOH%2FUXN%2BBbSrcA9iG%2BbKmmWheRVSZjb8O2GH9GqfhCZCe8SyXDQHmIoPSV14tqI9ipWh4%2FvUPkyrLvq2Q0GiFXbVWVf1si2NxTWkrHRlbdCCC%2FsvsjIs3u4g%2BzNOSypl%2BZvfsKMW7xIZBvfNw8T59kgHLwT0UdmPqmUd71JcLvyR%2BwL02xxOPMIjuA7CPoyZxPzgTAd2fo5F5AAyLijYoRG4KOU3Si0ntepMIBolQhYUrZz5TEQ9qvlh8HW2CAJfUc8o6pd5Ij%2FKotp8Z1%2BGg0NUTKBrjmQss9OpYSw2Upy4iHg7ZmkQZFgwYXq2nFfbCh%2B9LCcB7cRogo7sPQZ3osGuRpm9SJnISyJ9xeyd%2Bq2anFjfNx6rSSnlST9AjBxDb4bE9Sd%2FWCjYyBojf5yN98iTGLJOCtucX1ppWHw099t%2FRtDEc9cvSOjex809rLOJPBL%2BzzH2Cqi%2BFrrNB%2Bj%2B9ElhsGI9PYJpybn4zPyXhRoH9f1S6XVXi8er2llRDWPdviyLKXx%2BWsVOdCXgQT9wKzK1MGM4BCbO1ZknckTAoi973vNyYOPQ%2B6tyKlVN4t%2BMu9p8rhOFxdP9aCZKYua1x0yZDpl6%2F8K2IktpMxcOg%2BfLgNTvYebxcOv5iIjswVqcrLFA2CCKqMLro1L0GOqUBkjjJ0BnMr0%2ByIDr2TxLO7s43KMpFR%2FCOKqXo9OVgbWNQ2UUNh0Hy3fR5qLPLWM4%2Fa844eG5GfXr%2BK6bUJ%2FYn69l%2BNq3EvQEVYzVL9meZPmULUzo7Xf0MJqy6TfV3u9q6HZFkrvct2IP1GBjxNwZIt17amWTvCF6X9XpGBOOlbPXTmRSuUG15BCIH3S8gqsBmr7lAVZnCvExvC7gPJgtGBKqKT3Qx&X-Amz-Signature=3895acec22795b31ccf7210cdd3ec2cec804fcf0c76d9b2d26044996aa37d084&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665K2YHGX3%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T014834Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHIaCXVzLXdlc3QtMiJHMEUCIFIhN7A7jfKITBh1zAWxstU8GL603okC6%2Fz%2Bj19IuH52AiEA9pne4K7Z8nlYnl8X6VJWy4BP7rBJrHiWkcfozby31rIqiAQIm%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDJoy8DvkOH%2FUXN%2BBbSrcA9iG%2BbKmmWheRVSZjb8O2GH9GqfhCZCe8SyXDQHmIoPSV14tqI9ipWh4%2FvUPkyrLvq2Q0GiFXbVWVf1si2NxTWkrHRlbdCCC%2FsvsjIs3u4g%2BzNOSypl%2BZvfsKMW7xIZBvfNw8T59kgHLwT0UdmPqmUd71JcLvyR%2BwL02xxOPMIjuA7CPoyZxPzgTAd2fo5F5AAyLijYoRG4KOU3Si0ntepMIBolQhYUrZz5TEQ9qvlh8HW2CAJfUc8o6pd5Ij%2FKotp8Z1%2BGg0NUTKBrjmQss9OpYSw2Upy4iHg7ZmkQZFgwYXq2nFfbCh%2B9LCcB7cRogo7sPQZ3osGuRpm9SJnISyJ9xeyd%2Bq2anFjfNx6rSSnlST9AjBxDb4bE9Sd%2FWCjYyBojf5yN98iTGLJOCtucX1ppWHw099t%2FRtDEc9cvSOjex809rLOJPBL%2BzzH2Cqi%2BFrrNB%2Bj%2B9ElhsGI9PYJpybn4zPyXhRoH9f1S6XVXi8er2llRDWPdviyLKXx%2BWsVOdCXgQT9wKzK1MGM4BCbO1ZknckTAoi973vNyYOPQ%2B6tyKlVN4t%2BMu9p8rhOFxdP9aCZKYua1x0yZDpl6%2F8K2IktpMxcOg%2BfLgNTvYebxcOv5iIjswVqcrLFA2CCKqMLro1L0GOqUBkjjJ0BnMr0%2ByIDr2TxLO7s43KMpFR%2FCOKqXo9OVgbWNQ2UUNh0Hy3fR5qLPLWM4%2Fa844eG5GfXr%2BK6bUJ%2FYn69l%2BNq3EvQEVYzVL9meZPmULUzo7Xf0MJqy6TfV3u9q6HZFkrvct2IP1GBjxNwZIt17amWTvCF6X9XpGBOOlbPXTmRSuUG15BCIH3S8gqsBmr7lAVZnCvExvC7gPJgtGBKqKT3Qx&X-Amz-Signature=bc2185b58149a2e0efaef8eb3a04b4c087a61cc851ab44d9a5d38e6b5779720d&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665K2YHGX3%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T014834Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHIaCXVzLXdlc3QtMiJHMEUCIFIhN7A7jfKITBh1zAWxstU8GL603okC6%2Fz%2Bj19IuH52AiEA9pne4K7Z8nlYnl8X6VJWy4BP7rBJrHiWkcfozby31rIqiAQIm%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDJoy8DvkOH%2FUXN%2BBbSrcA9iG%2BbKmmWheRVSZjb8O2GH9GqfhCZCe8SyXDQHmIoPSV14tqI9ipWh4%2FvUPkyrLvq2Q0GiFXbVWVf1si2NxTWkrHRlbdCCC%2FsvsjIs3u4g%2BzNOSypl%2BZvfsKMW7xIZBvfNw8T59kgHLwT0UdmPqmUd71JcLvyR%2BwL02xxOPMIjuA7CPoyZxPzgTAd2fo5F5AAyLijYoRG4KOU3Si0ntepMIBolQhYUrZz5TEQ9qvlh8HW2CAJfUc8o6pd5Ij%2FKotp8Z1%2BGg0NUTKBrjmQss9OpYSw2Upy4iHg7ZmkQZFgwYXq2nFfbCh%2B9LCcB7cRogo7sPQZ3osGuRpm9SJnISyJ9xeyd%2Bq2anFjfNx6rSSnlST9AjBxDb4bE9Sd%2FWCjYyBojf5yN98iTGLJOCtucX1ppWHw099t%2FRtDEc9cvSOjex809rLOJPBL%2BzzH2Cqi%2BFrrNB%2Bj%2B9ElhsGI9PYJpybn4zPyXhRoH9f1S6XVXi8er2llRDWPdviyLKXx%2BWsVOdCXgQT9wKzK1MGM4BCbO1ZknckTAoi973vNyYOPQ%2B6tyKlVN4t%2BMu9p8rhOFxdP9aCZKYua1x0yZDpl6%2F8K2IktpMxcOg%2BfLgNTvYebxcOv5iIjswVqcrLFA2CCKqMLro1L0GOqUBkjjJ0BnMr0%2ByIDr2TxLO7s43KMpFR%2FCOKqXo9OVgbWNQ2UUNh0Hy3fR5qLPLWM4%2Fa844eG5GfXr%2BK6bUJ%2FYn69l%2BNq3EvQEVYzVL9meZPmULUzo7Xf0MJqy6TfV3u9q6HZFkrvct2IP1GBjxNwZIt17amWTvCF6X9XpGBOOlbPXTmRSuUG15BCIH3S8gqsBmr7lAVZnCvExvC7gPJgtGBKqKT3Qx&X-Amz-Signature=dba62853df6d95a34297ffc0b5e283fd3a5b5d82579c741483be534d6e3a4851&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466T3MVNMPF%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T014835Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHIaCXVzLXdlc3QtMiJHMEUCIF52ie9uxfVm8%2BpBd1Dp9NdF%2FXipAAgCa%2FeOgXn%2FyH9xAiEAjVaJ835a8Kp95pi3cucQKF%2FhkDHz%2BA%2F3oG5siMge7p8qiAQIm%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMbkGxbJnbqDmoivHSrcA5Wf85QtaiW3OhTAZGG4Yk%2BwO1ofOD4y9wgk4ZUBNOsaLclBpvTRGaJ8NgSBWO6xUDC14HdHqDnfDIMG%2FQI34WpVcJneyby5sV28PW8%2BKzK%2FmxfcGs2VUcNudWLilZtV1zU%2Fc7BWGvNNP%2BK%2F6oXlL68sdE3tYAOHT39gBM97LwKUMzqwhHEDdmxhW3tLemjhpqYZohTjWpkBBHxqeygoZCmFaSls3oR5scPa51fodqEUBidusqr3uzwbZN4tCfdBXJfHgsYRL6wKEwd4nZm5CWNs0pHycPJe%2Fsu1dCNVQftj6rLwU1uWkMFb8PCsLy%2BRlo%2Bd%2BR%2FZ25MAhHunS0Aq3fAanc5R3flDY3zGEQ1XYjbChibLEmkL1SUe6wdOe2fQYUfNxhgdnyfzcilSmJ2Grw8N2KG6RuBMho5vmzf8VbXOEvGltClqfR5LVJMxbHcxXAgef3dHRNNGU9mV3ak0uYoygbHzmVe%2Fi%2BFGoKxQFTOcMRmkVGLrtF9G4m2VYtNEShxH%2F0OGP6USoTEQl3Qiwal8u3lOcS3s3GKpChN%2FT8dO1onA82biRj7GQ2oBXEpA%2BF8sbBrx%2FejYz%2Fz%2Fq57v3h9dTMLnLKWNSZCl1Y2TisFCE9prU23mHNOwZByEMJfp1L0GOqUBGc60fr%2BP5gMtxhYVvHWB0uANVSC7kCADTQukhR5N49U808Ki4%2Bhmohxyr4plBdsU%2Bjq5ZyrHuMLdKLEuwqBewlo7T8oBKOmJWzN%2BxjSu%2BvWq2wPt%2Bv1EPI%2FlfV%2FaGE47PHI%2BBRmFtDWrryOvH43E%2F93HNliFZiJJu86wmujRQcbRR950%2BkME029dM0XXy4Vj%2F%2F5ET2sar1LjYWAWvhARc3iCumUc&X-Amz-Signature=b960f8c7a5f6873b5007c717ce45caf6819c12eafaf495021ac17c3cfd60eaf2&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664JHF7QDL%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T014837Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHIaCXVzLXdlc3QtMiJHMEUCIGABDC3StEYm%2FSd%2FcV%2B7eGjCIIthU%2Bwq0nC7wvmfROenAiEA7AW3fgwBtM1HKftM4tg1tYk1lBk5oA67R4ZbR6CHIVoqiAQIm%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDIr3XKpi3uifv%2FrtnSrcAxX%2FhLhL%2BpD3GewZuJEEjoAisNJwEyhik8MKyrWuVL8QUYwV4LpmF9bN4p5nd%2FE6p%2FWW6r6teZ4Gu%2F92tb0X7sYDwqiph%2BXC%2Fu83WTJDOBVW9FzZpYTIQuBP5q0JFSLCZkQHNCUyhDgbLymRtiSKD02RsSEApX8owhD80LiOJCamw0hRO%2FQMeDTGS6RiOpcc0OJnfWFQplRjoiezYqBiVZlCaA9Jn3Fymj13wcpDEzV%2BG1O3dRvlisRffnxiRLA3gpk8kQDKp7mP59pJtFdbqHQImjOaiEVmJD1xUVoOWxJw9jpzmVZrjnIXFTyBAIniekBAbQPTUGCqSQ0QbrTQ%2Fm1fDpkIRdJY9sed6iJQoVPwxPSWgfW0Y0Yo3Jd%2BVQNIgcZ9Ogf96IMx%2BdK7qjSs0av1hrfhgVqDJjsugc0DsXGUjUvAWjtNsOyO0%2F%2F1HeIuRRDy%2FIGQSFZshJzBru1mPDf7hA615yPFziyfwMNkCiW8hEwGtHFO3uMGvZ79qx3N4Rk06QBUijXKh1%2FD4fPlKiAyK4%2BZF7k4DN3hjsRTG%2F8Ha%2BW9fwprBVYeMGg1ElA7s0VUEoguvd9qA9LyrCDXoBK3LsUMHH68QSgfRVyouk4QSHsY0TcUE%2BiCJSKZMMXp1L0GOqUBPLvxormq0D8tY0nDCCokNw8pZUmsYWG%2FP45DDZnn7D5UWTK6pxE9EtbC0DZtJP%2B9A1jyAERTswETcTHCln%2FgyEy0MdkfbAo6N0qfkW0zgu87XQNI6iBQWlMjYqkSfBuxDe1EQ2SCyv3XarIrlDE242Bphsvl7YpuUJfmYgJinffHx65H0lhalqkI5d38hwP9%2FhZFsvjCl1VBKBLOBS2TtRw6lRwl&X-Amz-Signature=3eeddf6135fd155ade9442d53638b195a13312543eee176f972903d97c1665ed&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665K2YHGX3%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T014834Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHIaCXVzLXdlc3QtMiJHMEUCIFIhN7A7jfKITBh1zAWxstU8GL603okC6%2Fz%2Bj19IuH52AiEA9pne4K7Z8nlYnl8X6VJWy4BP7rBJrHiWkcfozby31rIqiAQIm%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDJoy8DvkOH%2FUXN%2BBbSrcA9iG%2BbKmmWheRVSZjb8O2GH9GqfhCZCe8SyXDQHmIoPSV14tqI9ipWh4%2FvUPkyrLvq2Q0GiFXbVWVf1si2NxTWkrHRlbdCCC%2FsvsjIs3u4g%2BzNOSypl%2BZvfsKMW7xIZBvfNw8T59kgHLwT0UdmPqmUd71JcLvyR%2BwL02xxOPMIjuA7CPoyZxPzgTAd2fo5F5AAyLijYoRG4KOU3Si0ntepMIBolQhYUrZz5TEQ9qvlh8HW2CAJfUc8o6pd5Ij%2FKotp8Z1%2BGg0NUTKBrjmQss9OpYSw2Upy4iHg7ZmkQZFgwYXq2nFfbCh%2B9LCcB7cRogo7sPQZ3osGuRpm9SJnISyJ9xeyd%2Bq2anFjfNx6rSSnlST9AjBxDb4bE9Sd%2FWCjYyBojf5yN98iTGLJOCtucX1ppWHw099t%2FRtDEc9cvSOjex809rLOJPBL%2BzzH2Cqi%2BFrrNB%2Bj%2B9ElhsGI9PYJpybn4zPyXhRoH9f1S6XVXi8er2llRDWPdviyLKXx%2BWsVOdCXgQT9wKzK1MGM4BCbO1ZknckTAoi973vNyYOPQ%2B6tyKlVN4t%2BMu9p8rhOFxdP9aCZKYua1x0yZDpl6%2F8K2IktpMxcOg%2BfLgNTvYebxcOv5iIjswVqcrLFA2CCKqMLro1L0GOqUBkjjJ0BnMr0%2ByIDr2TxLO7s43KMpFR%2FCOKqXo9OVgbWNQ2UUNh0Hy3fR5qLPLWM4%2Fa844eG5GfXr%2BK6bUJ%2FYn69l%2BNq3EvQEVYzVL9meZPmULUzo7Xf0MJqy6TfV3u9q6HZFkrvct2IP1GBjxNwZIt17amWTvCF6X9XpGBOOlbPXTmRSuUG15BCIH3S8gqsBmr7lAVZnCvExvC7gPJgtGBKqKT3Qx&X-Amz-Signature=adf75c816ef6d0c45fc0cd448b7453d96a437df1156730588dde4f4ea32839a2&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665K2YHGX3%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T014834Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHIaCXVzLXdlc3QtMiJHMEUCIFIhN7A7jfKITBh1zAWxstU8GL603okC6%2Fz%2Bj19IuH52AiEA9pne4K7Z8nlYnl8X6VJWy4BP7rBJrHiWkcfozby31rIqiAQIm%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDJoy8DvkOH%2FUXN%2BBbSrcA9iG%2BbKmmWheRVSZjb8O2GH9GqfhCZCe8SyXDQHmIoPSV14tqI9ipWh4%2FvUPkyrLvq2Q0GiFXbVWVf1si2NxTWkrHRlbdCCC%2FsvsjIs3u4g%2BzNOSypl%2BZvfsKMW7xIZBvfNw8T59kgHLwT0UdmPqmUd71JcLvyR%2BwL02xxOPMIjuA7CPoyZxPzgTAd2fo5F5AAyLijYoRG4KOU3Si0ntepMIBolQhYUrZz5TEQ9qvlh8HW2CAJfUc8o6pd5Ij%2FKotp8Z1%2BGg0NUTKBrjmQss9OpYSw2Upy4iHg7ZmkQZFgwYXq2nFfbCh%2B9LCcB7cRogo7sPQZ3osGuRpm9SJnISyJ9xeyd%2Bq2anFjfNx6rSSnlST9AjBxDb4bE9Sd%2FWCjYyBojf5yN98iTGLJOCtucX1ppWHw099t%2FRtDEc9cvSOjex809rLOJPBL%2BzzH2Cqi%2BFrrNB%2Bj%2B9ElhsGI9PYJpybn4zPyXhRoH9f1S6XVXi8er2llRDWPdviyLKXx%2BWsVOdCXgQT9wKzK1MGM4BCbO1ZknckTAoi973vNyYOPQ%2B6tyKlVN4t%2BMu9p8rhOFxdP9aCZKYua1x0yZDpl6%2F8K2IktpMxcOg%2BfLgNTvYebxcOv5iIjswVqcrLFA2CCKqMLro1L0GOqUBkjjJ0BnMr0%2ByIDr2TxLO7s43KMpFR%2FCOKqXo9OVgbWNQ2UUNh0Hy3fR5qLPLWM4%2Fa844eG5GfXr%2BK6bUJ%2FYn69l%2BNq3EvQEVYzVL9meZPmULUzo7Xf0MJqy6TfV3u9q6HZFkrvct2IP1GBjxNwZIt17amWTvCF6X9XpGBOOlbPXTmRSuUG15BCIH3S8gqsBmr7lAVZnCvExvC7gPJgtGBKqKT3Qx&X-Amz-Signature=42e01b3e3eee252bd8f1c43288efa0bc3a59cb287da986df3dadbecc5ee4a167&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665K2YHGX3%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T014834Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHIaCXVzLXdlc3QtMiJHMEUCIFIhN7A7jfKITBh1zAWxstU8GL603okC6%2Fz%2Bj19IuH52AiEA9pne4K7Z8nlYnl8X6VJWy4BP7rBJrHiWkcfozby31rIqiAQIm%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDJoy8DvkOH%2FUXN%2BBbSrcA9iG%2BbKmmWheRVSZjb8O2GH9GqfhCZCe8SyXDQHmIoPSV14tqI9ipWh4%2FvUPkyrLvq2Q0GiFXbVWVf1si2NxTWkrHRlbdCCC%2FsvsjIs3u4g%2BzNOSypl%2BZvfsKMW7xIZBvfNw8T59kgHLwT0UdmPqmUd71JcLvyR%2BwL02xxOPMIjuA7CPoyZxPzgTAd2fo5F5AAyLijYoRG4KOU3Si0ntepMIBolQhYUrZz5TEQ9qvlh8HW2CAJfUc8o6pd5Ij%2FKotp8Z1%2BGg0NUTKBrjmQss9OpYSw2Upy4iHg7ZmkQZFgwYXq2nFfbCh%2B9LCcB7cRogo7sPQZ3osGuRpm9SJnISyJ9xeyd%2Bq2anFjfNx6rSSnlST9AjBxDb4bE9Sd%2FWCjYyBojf5yN98iTGLJOCtucX1ppWHw099t%2FRtDEc9cvSOjex809rLOJPBL%2BzzH2Cqi%2BFrrNB%2Bj%2B9ElhsGI9PYJpybn4zPyXhRoH9f1S6XVXi8er2llRDWPdviyLKXx%2BWsVOdCXgQT9wKzK1MGM4BCbO1ZknckTAoi973vNyYOPQ%2B6tyKlVN4t%2BMu9p8rhOFxdP9aCZKYua1x0yZDpl6%2F8K2IktpMxcOg%2BfLgNTvYebxcOv5iIjswVqcrLFA2CCKqMLro1L0GOqUBkjjJ0BnMr0%2ByIDr2TxLO7s43KMpFR%2FCOKqXo9OVgbWNQ2UUNh0Hy3fR5qLPLWM4%2Fa844eG5GfXr%2BK6bUJ%2FYn69l%2BNq3EvQEVYzVL9meZPmULUzo7Xf0MJqy6TfV3u9q6HZFkrvct2IP1GBjxNwZIt17amWTvCF6X9XpGBOOlbPXTmRSuUG15BCIH3S8gqsBmr7lAVZnCvExvC7gPJgtGBKqKT3Qx&X-Amz-Signature=32314cbd85f8dfe7d17aa04da3027b7fadfed3d7e3f83dced50b4f6db4d04fde&X-Amz-SignedHeaders=host&x-id=GetObject)


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

