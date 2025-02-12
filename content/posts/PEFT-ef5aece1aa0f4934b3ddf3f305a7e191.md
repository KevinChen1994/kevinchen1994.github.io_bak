---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466YWV6LOA5%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250212T191933Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjENv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCRlH9hge4%2F%2Fpx\
  xhA360qAkydaRyQ5%2F1wUGr%2FMtU2M93AIgFQZuIoti2VevKu%2BWkBAMqgmr71zDk%2Bh82tnm\
  zt%2Fdp94qiAQI8%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCjjp\
  FPhQ7KMgjOKoyrcA2uyVMqumfcvNxxiBA9JHfrwX425mW7PT9xbVsBGeO%2FS4f3M1dSgiYzykcfN\
  23gzevlIUBL1PYDfp9RmLrwQiTA83jVeEt6Q2ulfM7Hk87ZfrBuFs8FNeZM1GjjAN7egQDJcA7EHG\
  5AeP4Pt2JxnWE1YRc6GDvs1I%2B0Wsx8mA1rMzs5vD4PksDCSA8RM5tZVzeuq1SSx7kZLztkwa2Hh\
  sakx1XV%2Bl2zb67Sv3OKeUQar0R8dybVMyF2Xj%2BdZ7cREVcRly%2BqsbgLovHdxxfe0%2FGljY\
  l5Bi8N8AAH1bHYtfOk0XJ4E9LulEtdgUHqkC8mo4McGix7CboT13ui%2B3HmwAGHLL0QrkeTsu%2B\
  CeL%2BCwpVup07MgcT70mcv8fk%2FsWsHo6QeaodLAl0xBHm%2BCpCwoyGMKGajm3cj3jAHuKkbkv\
  RsSsxgDC9p4n6F%2BZCwG9KIPaWAemYYatzRKhlA3Dr6y65%2FOIgAOZwpHpNJ2nBRm9Fcuz0gQfI\
  Sq0luHxVkgt%2BvDHmGuj4D09g%2FM4BwO62Iwtpxn7YPL8O%2BxtGZy16kq%2FUU9FwfHmkM2SGo\
  xbYw2tOga%2Bh4P8sqfvQLNVhSAXmSSyOOoN6NcseCNG1N8HCnyjR4ux5xlIj8gBsPPTrOxMOPMs7\
  0GOqUBFI6NODcBNzPk4F%2Bu7%2FPvUzzZ7lSOi1OM18D1NhH2xpaAfw%2BIGyCaLW6NAvMyKgxfe\
  pmD7gk7EZ%2BADei8FmOL7av%2FcXypgNM8PhQ5RACJ3GhcNnWa1dGkcxikbTHY0azasaQOb4ivVW\
  Zm0MN2Pcb9FWUDosVNT18%2FEIAnAKc5B%2FkaoHcyYjegnbVmshj2quuU9VQqAZaS%2FESLY2eKc\
  iSfTyJYCU8h&X-Amz-Signature=3bd7870e5f055bc6afd20f3459ee7f6e85fb13d871e09f872\
  aad004c645d6974&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466WRX4IDAY%2F20250212%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250212T191801Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjENv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQ\
        CIGi0mlMyxhxIBP%2F%2FplRt6P7rYgyKlrafhvZoe83eBIQUAiARofwHdCJlP9ZGjLLuT7\
        dZY45Sj0eetAbhAo2dF72rzyqIBAj0%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzN\
        zQyMzE4MzgwNSIMMsWLJYIQaBSl%2FjX3KtwDg1ExCH4ih7%2FsEQ0fIignhJSk0aySQds9\
        yfUd2amfzluNwiWi9YKtyOYLrNxcYO14gZ%2FNVqWk8uUCMkBefdIsiRz7947%2FGS4jiXW\
        ko0PNuEKjUXtQPxanGbM2S5kXZLMLVw7ZQkiET9314Mmzj5Y1VmL%2BQC10Y91Hv1icdmqv\
        NwENFm9a%2BzrTcMKLml3YbP6sIhr2KC4y84Q%2F35Ue2fF5xj21c83itiGQ2wwu9MTZ4qn\
        6Gvnug2kUKH%2Fu2zYDWxgcFcCKVfYj771kIgBKNQ2qBnb3kT7mGi6UssxbmA5B3bOSY%2B\
        qGj%2BGsBubnIult2uGmwEmOfKbI2XwTkPsqYRrEXIAQAETp7NoGBXLxaTvSa6zO18Wj%2F\
        AORsvvO25LvV%2FSQqYqJVXWOXZ0v5Vdcdf5mk62N3gPrpaLL8HDDmBHwUat2Z47q5ySqon\
        k0Nia1FNmKjIibgGnhj2e57Rez74j71EGC6hBtXpEFALuqtKdEowv6fBuAQq0P%2FBy5dIZ\
        rLymXODe8w5f0IRVdMpK7H3844l%2FpmjJlUQaiZI8JngeLj4VTG%2ByRHhoorY0Wu%2FOw\
        C%2F4mIs%2FjPUcqV8ToAo%2FPg9cnm8DMMMAhtt5iUmsMRwuo%2FePl1fj%2FggQSq5T4O\
        pAwy9OzvQY6pgEMvrywTLCecrmySa3eC%2FNcLmi0oZLK31xfxbsyIkhOA6xVAGDXNdZXXG\
        GzEr%2BhtCRL%2FDfOlGdEnuIzZ40bPhBq3OyfVEGOMkcFsSH%2B4JKi3MbrNI%2Bhb000P\
        lM8hS2x%2BYGcJ5WI15VqpCqIXIBs948tFEDT5%2F77mZAlAUO%2BMb55FwwxlbfiZTUyBv\
        WNyRU0OEnGtVKxmWO%2BM4zMI2DOzQ3TZqVGLOpd&X-Amz-Signature=af66ca6331fd9e\
        746b9644087877328a793ad4e6ec27da5d90f85236ed7ba913&X-Amz-SignedHeaders=\
        host&x-id=GetObject"
      expiry_time: "2025-02-12T20:18:01.062Z"
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
UPDATE_TIME: "2025-02-12T19:19:40.683Z"
EXPIRY_TIME: "2025-02-12T20:19:30.937Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664D54MWD5%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T191931Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICKf2ZRNAcKtZvVDSY5zK2H8p4SjyvFzQgpcbFNxXxQ9AiACtqNI5tqtoqROOeWAGi444fquBuvEW6b9sdiM1fbeHiqIBAj0%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM7fSxfdCs%2Bm6eKG9KKtwDpG9WDbEEtvuXQJvXlnIHAcfXm3Z%2Bz6q5kr07ywr1qNIHQdiXvnVX20sVTU9afCmxw7d2nL88OjfIpWBtM7mtTdXFmh%2BqoeNn8mpHbecGhDUfFBsFViWUoju9sXFukqolI4iS%2BkVrlD7w1ZYxbpYhWkPbQN741aW7ZztvKW6gA12SrIPvptej%2F0TBoAmh9mBWBk3vkpxOo07b07qQ8LEnmQbDqh9Rbg%2B1tNB%2FScxY4axcN51zBN5hbi7DBh86yehuvkehqMW%2BTYOElp4XlfnUAOKlzoXjkTl0vQRU9z62Erpx%2F89IzyY6C%2Bqw5Ws6IJDRtd%2BXI3OMy2Y2mC7fh1mUfyTRHjDdQXB2e6UN%2BIg8ZzKS6VxEtrct6fEOgsinLdIh%2FahSVveo2MYRfgT8cdAhxDuYYV2YkIX%2ByHP1pmuZ6uD9exKLXzTUE8yGzisbR9J50qMTxiYk%2B6x2cu6ChmSJ7E3QE42L5jbtoob%2BNqmP%2Bt6oNZFaeuF2f8OdLXxvxAgo88UkOzv7WGWpmYZ%2BL2SUSoVJBfR%2FAqulms4Gi%2FZ4cYIMECEjvMRwc0fg1Z7AjruxDpEJ6kCNCvhN5VSx8R2O7FoRJzI6sH6sXFalypWAFleMbdnqGe%2Bd5IhWF4Iwz9ezvQY6pgGywH%2F7fhgokL6vsz2M2eblXelMS7dDibTyB%2FdiBvsoBKzc8krybSsiPynsx%2FYiua%2BW0bz1vg1djjB%2FHZCiuCcTkrdinon7d5bT0jFsfJQM%2BcxGEZGmr3BlkTKLicbrV%2BY%2Fb8bl7zNB%2BuSNbR5jR5iYR4JE%2B6LP7ys2SOaKhxJVRzxuYuvBpyQItSt0PHZTSOAut8Dsd%2BXRSdUr9dwy0llIKt7%2BxryV&X-Amz-Signature=5093c781e63400d6d5041c2e4ddf379573cead990c1991d7dce3cc0e783bc62a&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664D54MWD5%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T191931Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICKf2ZRNAcKtZvVDSY5zK2H8p4SjyvFzQgpcbFNxXxQ9AiACtqNI5tqtoqROOeWAGi444fquBuvEW6b9sdiM1fbeHiqIBAj0%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM7fSxfdCs%2Bm6eKG9KKtwDpG9WDbEEtvuXQJvXlnIHAcfXm3Z%2Bz6q5kr07ywr1qNIHQdiXvnVX20sVTU9afCmxw7d2nL88OjfIpWBtM7mtTdXFmh%2BqoeNn8mpHbecGhDUfFBsFViWUoju9sXFukqolI4iS%2BkVrlD7w1ZYxbpYhWkPbQN741aW7ZztvKW6gA12SrIPvptej%2F0TBoAmh9mBWBk3vkpxOo07b07qQ8LEnmQbDqh9Rbg%2B1tNB%2FScxY4axcN51zBN5hbi7DBh86yehuvkehqMW%2BTYOElp4XlfnUAOKlzoXjkTl0vQRU9z62Erpx%2F89IzyY6C%2Bqw5Ws6IJDRtd%2BXI3OMy2Y2mC7fh1mUfyTRHjDdQXB2e6UN%2BIg8ZzKS6VxEtrct6fEOgsinLdIh%2FahSVveo2MYRfgT8cdAhxDuYYV2YkIX%2ByHP1pmuZ6uD9exKLXzTUE8yGzisbR9J50qMTxiYk%2B6x2cu6ChmSJ7E3QE42L5jbtoob%2BNqmP%2Bt6oNZFaeuF2f8OdLXxvxAgo88UkOzv7WGWpmYZ%2BL2SUSoVJBfR%2FAqulms4Gi%2FZ4cYIMECEjvMRwc0fg1Z7AjruxDpEJ6kCNCvhN5VSx8R2O7FoRJzI6sH6sXFalypWAFleMbdnqGe%2Bd5IhWF4Iwz9ezvQY6pgGywH%2F7fhgokL6vsz2M2eblXelMS7dDibTyB%2FdiBvsoBKzc8krybSsiPynsx%2FYiua%2BW0bz1vg1djjB%2FHZCiuCcTkrdinon7d5bT0jFsfJQM%2BcxGEZGmr3BlkTKLicbrV%2BY%2Fb8bl7zNB%2BuSNbR5jR5iYR4JE%2B6LP7ys2SOaKhxJVRzxuYuvBpyQItSt0PHZTSOAut8Dsd%2BXRSdUr9dwy0llIKt7%2BxryV&X-Amz-Signature=9e53afbfa71351c955c0b337098e27b1d1de455b634522a4e48b74191768e4ef&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664D54MWD5%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T191931Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICKf2ZRNAcKtZvVDSY5zK2H8p4SjyvFzQgpcbFNxXxQ9AiACtqNI5tqtoqROOeWAGi444fquBuvEW6b9sdiM1fbeHiqIBAj0%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM7fSxfdCs%2Bm6eKG9KKtwDpG9WDbEEtvuXQJvXlnIHAcfXm3Z%2Bz6q5kr07ywr1qNIHQdiXvnVX20sVTU9afCmxw7d2nL88OjfIpWBtM7mtTdXFmh%2BqoeNn8mpHbecGhDUfFBsFViWUoju9sXFukqolI4iS%2BkVrlD7w1ZYxbpYhWkPbQN741aW7ZztvKW6gA12SrIPvptej%2F0TBoAmh9mBWBk3vkpxOo07b07qQ8LEnmQbDqh9Rbg%2B1tNB%2FScxY4axcN51zBN5hbi7DBh86yehuvkehqMW%2BTYOElp4XlfnUAOKlzoXjkTl0vQRU9z62Erpx%2F89IzyY6C%2Bqw5Ws6IJDRtd%2BXI3OMy2Y2mC7fh1mUfyTRHjDdQXB2e6UN%2BIg8ZzKS6VxEtrct6fEOgsinLdIh%2FahSVveo2MYRfgT8cdAhxDuYYV2YkIX%2ByHP1pmuZ6uD9exKLXzTUE8yGzisbR9J50qMTxiYk%2B6x2cu6ChmSJ7E3QE42L5jbtoob%2BNqmP%2Bt6oNZFaeuF2f8OdLXxvxAgo88UkOzv7WGWpmYZ%2BL2SUSoVJBfR%2FAqulms4Gi%2FZ4cYIMECEjvMRwc0fg1Z7AjruxDpEJ6kCNCvhN5VSx8R2O7FoRJzI6sH6sXFalypWAFleMbdnqGe%2Bd5IhWF4Iwz9ezvQY6pgGywH%2F7fhgokL6vsz2M2eblXelMS7dDibTyB%2FdiBvsoBKzc8krybSsiPynsx%2FYiua%2BW0bz1vg1djjB%2FHZCiuCcTkrdinon7d5bT0jFsfJQM%2BcxGEZGmr3BlkTKLicbrV%2BY%2Fb8bl7zNB%2BuSNbR5jR5iYR4JE%2B6LP7ys2SOaKhxJVRzxuYuvBpyQItSt0PHZTSOAut8Dsd%2BXRSdUr9dwy0llIKt7%2BxryV&X-Amz-Signature=66432389f0917bc01e64e89b8c3863bf3f9c30d15b1a06ec986dd42422ecb84e&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664D54MWD5%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T191931Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICKf2ZRNAcKtZvVDSY5zK2H8p4SjyvFzQgpcbFNxXxQ9AiACtqNI5tqtoqROOeWAGi444fquBuvEW6b9sdiM1fbeHiqIBAj0%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM7fSxfdCs%2Bm6eKG9KKtwDpG9WDbEEtvuXQJvXlnIHAcfXm3Z%2Bz6q5kr07ywr1qNIHQdiXvnVX20sVTU9afCmxw7d2nL88OjfIpWBtM7mtTdXFmh%2BqoeNn8mpHbecGhDUfFBsFViWUoju9sXFukqolI4iS%2BkVrlD7w1ZYxbpYhWkPbQN741aW7ZztvKW6gA12SrIPvptej%2F0TBoAmh9mBWBk3vkpxOo07b07qQ8LEnmQbDqh9Rbg%2B1tNB%2FScxY4axcN51zBN5hbi7DBh86yehuvkehqMW%2BTYOElp4XlfnUAOKlzoXjkTl0vQRU9z62Erpx%2F89IzyY6C%2Bqw5Ws6IJDRtd%2BXI3OMy2Y2mC7fh1mUfyTRHjDdQXB2e6UN%2BIg8ZzKS6VxEtrct6fEOgsinLdIh%2FahSVveo2MYRfgT8cdAhxDuYYV2YkIX%2ByHP1pmuZ6uD9exKLXzTUE8yGzisbR9J50qMTxiYk%2B6x2cu6ChmSJ7E3QE42L5jbtoob%2BNqmP%2Bt6oNZFaeuF2f8OdLXxvxAgo88UkOzv7WGWpmYZ%2BL2SUSoVJBfR%2FAqulms4Gi%2FZ4cYIMECEjvMRwc0fg1Z7AjruxDpEJ6kCNCvhN5VSx8R2O7FoRJzI6sH6sXFalypWAFleMbdnqGe%2Bd5IhWF4Iwz9ezvQY6pgGywH%2F7fhgokL6vsz2M2eblXelMS7dDibTyB%2FdiBvsoBKzc8krybSsiPynsx%2FYiua%2BW0bz1vg1djjB%2FHZCiuCcTkrdinon7d5bT0jFsfJQM%2BcxGEZGmr3BlkTKLicbrV%2BY%2Fb8bl7zNB%2BuSNbR5jR5iYR4JE%2B6LP7ys2SOaKhxJVRzxuYuvBpyQItSt0PHZTSOAut8Dsd%2BXRSdUr9dwy0llIKt7%2BxryV&X-Amz-Signature=4efdd5e9de46caf6785eb68f9f77ea62279a638bf060c36860aaafdc803039ea&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664D54MWD5%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T191931Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICKf2ZRNAcKtZvVDSY5zK2H8p4SjyvFzQgpcbFNxXxQ9AiACtqNI5tqtoqROOeWAGi444fquBuvEW6b9sdiM1fbeHiqIBAj0%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM7fSxfdCs%2Bm6eKG9KKtwDpG9WDbEEtvuXQJvXlnIHAcfXm3Z%2Bz6q5kr07ywr1qNIHQdiXvnVX20sVTU9afCmxw7d2nL88OjfIpWBtM7mtTdXFmh%2BqoeNn8mpHbecGhDUfFBsFViWUoju9sXFukqolI4iS%2BkVrlD7w1ZYxbpYhWkPbQN741aW7ZztvKW6gA12SrIPvptej%2F0TBoAmh9mBWBk3vkpxOo07b07qQ8LEnmQbDqh9Rbg%2B1tNB%2FScxY4axcN51zBN5hbi7DBh86yehuvkehqMW%2BTYOElp4XlfnUAOKlzoXjkTl0vQRU9z62Erpx%2F89IzyY6C%2Bqw5Ws6IJDRtd%2BXI3OMy2Y2mC7fh1mUfyTRHjDdQXB2e6UN%2BIg8ZzKS6VxEtrct6fEOgsinLdIh%2FahSVveo2MYRfgT8cdAhxDuYYV2YkIX%2ByHP1pmuZ6uD9exKLXzTUE8yGzisbR9J50qMTxiYk%2B6x2cu6ChmSJ7E3QE42L5jbtoob%2BNqmP%2Bt6oNZFaeuF2f8OdLXxvxAgo88UkOzv7WGWpmYZ%2BL2SUSoVJBfR%2FAqulms4Gi%2FZ4cYIMECEjvMRwc0fg1Z7AjruxDpEJ6kCNCvhN5VSx8R2O7FoRJzI6sH6sXFalypWAFleMbdnqGe%2Bd5IhWF4Iwz9ezvQY6pgGywH%2F7fhgokL6vsz2M2eblXelMS7dDibTyB%2FdiBvsoBKzc8krybSsiPynsx%2FYiua%2BW0bz1vg1djjB%2FHZCiuCcTkrdinon7d5bT0jFsfJQM%2BcxGEZGmr3BlkTKLicbrV%2BY%2Fb8bl7zNB%2BuSNbR5jR5iYR4JE%2B6LP7ys2SOaKhxJVRzxuYuvBpyQItSt0PHZTSOAut8Dsd%2BXRSdUr9dwy0llIKt7%2BxryV&X-Amz-Signature=23da0025c3eeb5f09fa85dfc34da8f38ca6b9c7e45280b07f41f0b8a571d5bd5&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667HF7JGB6%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T191932Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIFOPGIxbOmP97Xb8WyqD%2FI1Th3ctw%2BshTZAhxRB5naA5AiAkcKB5ZmqP6izngWzPi6LDrkd9a1zPtsxKMwfZE9aKqSqIBAj0%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMrHLUeJqw85tpCWmqKtwDLLzbcsHNa%2F6ENn1nYClIw5%2BcrpdQaMmy28XK2CfSLG%2F5fwDvqnVEZWZ0n26JweIw6d%2FP6x3WOeCOY2SBwNGPjWyQ%2FhIARD6UBbnQ2f5a2Gfn5xQpKUKWft190N06ataCkMJeYzpA0ds%2FX6n11arpKAWsFbBax5tbulyUkqrPdLjeDd8lW3fIP6Vf6HfxgBwsrjTaItmABmqO2BpcTPdyXlny3yjmlBKnfpfq7SPe4hqbvx5%2B%2FT%2Fvgsryny3tPBSTZNCloF9iyOyWdzcYdJVguxOcCrAXM3jDox%2FoTjR9xHILaMRX8SEBV50nd4M94lMK0PhGPuSmTwi40gHRZ2%2BOs8JT5f35o35XYI0PJhC%2BFsD5lPVjWkllc%2FD0M0mIh5aMapuWDmzHgMaDoGmWAKVFUg99Os3jTDnQcEVi9ITDse25S1XQOoytDuZqsxvJIHpaYYO9zUghJXGZ1jxuZhkBj%2Bsa8gebnZPiXtnnq0%2BgZmqOIxgIKK2Bqqn6inbnmfR%2BQAJ1aBObRxaLABcHpHJE5ncEW5d0Iaj8ai%2Fftut7E%2FRjsC6p65xHTPEhDHCSs7jWnKDUl9K2Cbm0xd%2FreI6Fy7FvV63Eg%2B8rFvukDuvAg7%2BvjF3FJpki15yYBkswieizvQY6pgHxHCtWAtNO2XExz6aDynOJwsEYuuJyTElLCJTJ8WlBUASkpCPdNIk3MLtDcnv8vymAljh6n03Qb37OCCxip9Pq%2FRx%2FFK9woQ%2BBWdbmkkuLl102pltRxPmFZYM4tEXZqKBGg8ntK4gHTYVJKC%2FLvXxKxLaoqM7gM0QXxuz1lVGUMn5kwfXCo3lFVV9nAWc5wLvn9yzYDDtyPXxqlBw6RdywlcehFGoy&X-Amz-Signature=7a6eba781a43de10980e2663873e7cab0606bbe4428e1fc8b16d59a98692a380&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662TAKP622%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T191932Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIGxEFh2AVlrdrHzujoyvPKg5gjgSsFHrbyCFoYJXNfu3AiEAr5d3vhy2SfchTda04g%2BdHi2xr449%2B4T5q0T9Z5JhUPcqiAQI9P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDBKOWbu83u1WEr32jyrcA43LfSaWrP%2BMEK4v1lgPR%2FCf7rn47RVnEaMkw6vi0lKSRp6EeaZeifchampmH8ELGXJsfP2yIcQtcLiEuzTN7H7KEZvp4zJX5ZR%2BCsSKZFsvnzUw0DCJCJOLK9HBevZpnmI8Z514bTu3ucPEK4NbTnVXVZfRc2s4zPZX1kxKV4ihSAbhEPCOHG21vBsZG5QDK517KqGxSigLACIAaS74aEwiOL57V%2BEK6lv%2B9dNZmvO3s%2FeuWwFNr8YYg0H4MTCpkNgfvnnmG4E8tkfz0GmLoVlx8JMoIpeSAiGnubJFsYk2QPd33ZyTYIP%2FeNYuCPtGgQ5p4b4RRkdxIyD8DQMfbjgjvmMo2RCXDXXq57Bae6AbrU3Njl%2Fs6hz2OiDE25BMl87IekEMrvkPrxm8%2FQKJZfeCvi5l3Cb5bQKnq67qJXGJz4qge5omd82nTB%2Ff02xf3CpYm%2FGpkJjSzhtgACELLxvZZeXNtWq87dmc8HxMyAMO0rBHxIWL3l%2BTpl9qar96DX7AcJdgsnmtP13%2BiMWHpwvnMw%2FoZMiYAfrMd35YeHsECXiEmBxkxiytuaO2NUVLoZcEeK%2FES8THoDfj9PLwP00w6Zz6V1%2FMXwxY1bYfg%2FKp%2FB8NL5YtuIhdvnUmMMDUs70GOqUBUQ8VkVvsMav8qEozwSevXMoS1igmXffotNJ5oRltMOr6q%2BpvmaXTi7Vz3wXON1K30O2%2BxcSttOdC%2Fo6IomoXjS8sYNwTDDeA1Vv0ndWHPaw6cFw%2ByLwsITDhhgcVFjaZeibmnCA3drJ3ya8uozIjtWDIlgYsTNNPJzOy1Idd8uU%2BTllfZlTZWlfDj6VtdBJYi7d3eeC%2BtjZBF8UH%2BAXylEoZ3kNV&X-Amz-Signature=3e2bd93fe0f81e7f89bb99f96c143d219b1bb23aa5bd3b78c5f586eb1ba271bc&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664D54MWD5%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T191931Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICKf2ZRNAcKtZvVDSY5zK2H8p4SjyvFzQgpcbFNxXxQ9AiACtqNI5tqtoqROOeWAGi444fquBuvEW6b9sdiM1fbeHiqIBAj0%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM7fSxfdCs%2Bm6eKG9KKtwDpG9WDbEEtvuXQJvXlnIHAcfXm3Z%2Bz6q5kr07ywr1qNIHQdiXvnVX20sVTU9afCmxw7d2nL88OjfIpWBtM7mtTdXFmh%2BqoeNn8mpHbecGhDUfFBsFViWUoju9sXFukqolI4iS%2BkVrlD7w1ZYxbpYhWkPbQN741aW7ZztvKW6gA12SrIPvptej%2F0TBoAmh9mBWBk3vkpxOo07b07qQ8LEnmQbDqh9Rbg%2B1tNB%2FScxY4axcN51zBN5hbi7DBh86yehuvkehqMW%2BTYOElp4XlfnUAOKlzoXjkTl0vQRU9z62Erpx%2F89IzyY6C%2Bqw5Ws6IJDRtd%2BXI3OMy2Y2mC7fh1mUfyTRHjDdQXB2e6UN%2BIg8ZzKS6VxEtrct6fEOgsinLdIh%2FahSVveo2MYRfgT8cdAhxDuYYV2YkIX%2ByHP1pmuZ6uD9exKLXzTUE8yGzisbR9J50qMTxiYk%2B6x2cu6ChmSJ7E3QE42L5jbtoob%2BNqmP%2Bt6oNZFaeuF2f8OdLXxvxAgo88UkOzv7WGWpmYZ%2BL2SUSoVJBfR%2FAqulms4Gi%2FZ4cYIMECEjvMRwc0fg1Z7AjruxDpEJ6kCNCvhN5VSx8R2O7FoRJzI6sH6sXFalypWAFleMbdnqGe%2Bd5IhWF4Iwz9ezvQY6pgGywH%2F7fhgokL6vsz2M2eblXelMS7dDibTyB%2FdiBvsoBKzc8krybSsiPynsx%2FYiua%2BW0bz1vg1djjB%2FHZCiuCcTkrdinon7d5bT0jFsfJQM%2BcxGEZGmr3BlkTKLicbrV%2BY%2Fb8bl7zNB%2BuSNbR5jR5iYR4JE%2B6LP7ys2SOaKhxJVRzxuYuvBpyQItSt0PHZTSOAut8Dsd%2BXRSdUr9dwy0llIKt7%2BxryV&X-Amz-Signature=c7a617a0cc9c0b865172c260c2200c37db7ffe44def0b47a227d4cbd40a8916a&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664D54MWD5%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T191931Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICKf2ZRNAcKtZvVDSY5zK2H8p4SjyvFzQgpcbFNxXxQ9AiACtqNI5tqtoqROOeWAGi444fquBuvEW6b9sdiM1fbeHiqIBAj0%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM7fSxfdCs%2Bm6eKG9KKtwDpG9WDbEEtvuXQJvXlnIHAcfXm3Z%2Bz6q5kr07ywr1qNIHQdiXvnVX20sVTU9afCmxw7d2nL88OjfIpWBtM7mtTdXFmh%2BqoeNn8mpHbecGhDUfFBsFViWUoju9sXFukqolI4iS%2BkVrlD7w1ZYxbpYhWkPbQN741aW7ZztvKW6gA12SrIPvptej%2F0TBoAmh9mBWBk3vkpxOo07b07qQ8LEnmQbDqh9Rbg%2B1tNB%2FScxY4axcN51zBN5hbi7DBh86yehuvkehqMW%2BTYOElp4XlfnUAOKlzoXjkTl0vQRU9z62Erpx%2F89IzyY6C%2Bqw5Ws6IJDRtd%2BXI3OMy2Y2mC7fh1mUfyTRHjDdQXB2e6UN%2BIg8ZzKS6VxEtrct6fEOgsinLdIh%2FahSVveo2MYRfgT8cdAhxDuYYV2YkIX%2ByHP1pmuZ6uD9exKLXzTUE8yGzisbR9J50qMTxiYk%2B6x2cu6ChmSJ7E3QE42L5jbtoob%2BNqmP%2Bt6oNZFaeuF2f8OdLXxvxAgo88UkOzv7WGWpmYZ%2BL2SUSoVJBfR%2FAqulms4Gi%2FZ4cYIMECEjvMRwc0fg1Z7AjruxDpEJ6kCNCvhN5VSx8R2O7FoRJzI6sH6sXFalypWAFleMbdnqGe%2Bd5IhWF4Iwz9ezvQY6pgGywH%2F7fhgokL6vsz2M2eblXelMS7dDibTyB%2FdiBvsoBKzc8krybSsiPynsx%2FYiua%2BW0bz1vg1djjB%2FHZCiuCcTkrdinon7d5bT0jFsfJQM%2BcxGEZGmr3BlkTKLicbrV%2BY%2Fb8bl7zNB%2BuSNbR5jR5iYR4JE%2B6LP7ys2SOaKhxJVRzxuYuvBpyQItSt0PHZTSOAut8Dsd%2BXRSdUr9dwy0llIKt7%2BxryV&X-Amz-Signature=96a56e9e83f387853774a3a094782f57452069d36373f58bd2ab1c98dcc171cb&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664D54MWD5%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T191931Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICKf2ZRNAcKtZvVDSY5zK2H8p4SjyvFzQgpcbFNxXxQ9AiACtqNI5tqtoqROOeWAGi444fquBuvEW6b9sdiM1fbeHiqIBAj0%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM7fSxfdCs%2Bm6eKG9KKtwDpG9WDbEEtvuXQJvXlnIHAcfXm3Z%2Bz6q5kr07ywr1qNIHQdiXvnVX20sVTU9afCmxw7d2nL88OjfIpWBtM7mtTdXFmh%2BqoeNn8mpHbecGhDUfFBsFViWUoju9sXFukqolI4iS%2BkVrlD7w1ZYxbpYhWkPbQN741aW7ZztvKW6gA12SrIPvptej%2F0TBoAmh9mBWBk3vkpxOo07b07qQ8LEnmQbDqh9Rbg%2B1tNB%2FScxY4axcN51zBN5hbi7DBh86yehuvkehqMW%2BTYOElp4XlfnUAOKlzoXjkTl0vQRU9z62Erpx%2F89IzyY6C%2Bqw5Ws6IJDRtd%2BXI3OMy2Y2mC7fh1mUfyTRHjDdQXB2e6UN%2BIg8ZzKS6VxEtrct6fEOgsinLdIh%2FahSVveo2MYRfgT8cdAhxDuYYV2YkIX%2ByHP1pmuZ6uD9exKLXzTUE8yGzisbR9J50qMTxiYk%2B6x2cu6ChmSJ7E3QE42L5jbtoob%2BNqmP%2Bt6oNZFaeuF2f8OdLXxvxAgo88UkOzv7WGWpmYZ%2BL2SUSoVJBfR%2FAqulms4Gi%2FZ4cYIMECEjvMRwc0fg1Z7AjruxDpEJ6kCNCvhN5VSx8R2O7FoRJzI6sH6sXFalypWAFleMbdnqGe%2Bd5IhWF4Iwz9ezvQY6pgGywH%2F7fhgokL6vsz2M2eblXelMS7dDibTyB%2FdiBvsoBKzc8krybSsiPynsx%2FYiua%2BW0bz1vg1djjB%2FHZCiuCcTkrdinon7d5bT0jFsfJQM%2BcxGEZGmr3BlkTKLicbrV%2BY%2Fb8bl7zNB%2BuSNbR5jR5iYR4JE%2B6LP7ys2SOaKhxJVRzxuYuvBpyQItSt0PHZTSOAut8Dsd%2BXRSdUr9dwy0llIKt7%2BxryV&X-Amz-Signature=9168ae32bb5e649eb590b8e9b24ca210b49740edb172f1b58593c7a1c1edbf9c&X-Amz-SignedHeaders=host&x-id=GetObject)


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

