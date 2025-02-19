---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466WYAVJ5CL%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250219T102620Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEHoaCXVzLXdlc3QtMiJHMEUCIQDImoAKnRu6Enc2UVqcEWpFuR%2FBrmXtNiqJMAUx74onAgIgd\
  NiZOeynXnF4s0mXsQudr%2BIyavffL372u9VQDCMlrhcqiAQIo%2F%2F%2F%2F%2F%2F%2F%2F%2F\
  %2F%2FARAAGgw2Mzc0MjMxODM4MDUiDFlDPJ4OpAji%2BffZlSrcA%2BOFJc%2BNFD4DKYoOUeJUo\
  hFhZYLrlSf1tDfchmDg8kme7YHUhfAoaHbYWL69GnUDSAKcLtplNd4btlNk0y5ayy%2BQRKxLFP4%\
  2FbXxUA6UPIeElMafl4vH3359qA6KtUq5hU81I7Cka2OAu5iJ1c2tTiZmIHkm5EViUIO2EO%2Fabt\
  TAz8ZMxHhfq4BKBSaDJdJ9NZYOdJ0efzivGrPY%2BPzT7vyStGp95U%2FITe90HSWOliBmB4mQaWA\
  QGsdco0oOSJmu3%2FhDlUjqxAhqRvzJH%2BOnm6zr85pEJQvY8yZx0vdu1B%2FFJOgu3d1OQcjr3%\
  2BKisVgtHmQjD4xUVJ1AoITpHSZXkecEk2kO%2B%2FifADlcqNDmzHq8aZx0CaM5We%2FLBZ%2BXW\
  Qh8i1xR%2FhXIWQkdqGRy047GfOzfUrJnlfRVZR8pTlFkI0d1yh2EaaTqwnReUZ7lF6Gdk980d0Op\
  B45izstSfDABjt3JHas0q50Qj4MfjQQk5SpKSVOcuEZS9tXiPUBwyEINqnprZjnZb5w%2FpDI%2Fb\
  uOHtXPdCWNVX01EwP1UCxuD%2F2eOrYvziC%2FAyHR5UJ%2F%2BfJ%2FgMFWuebrx9855jMN5VXAA\
  lFVzKpKRe0QgHI8emzmZTQopsd%2BV3HjVBFIOzRQ03MPTb1r0GOqUBFhUyvYrhS1Xw3qO%2F1ktd\
  WVmk8C8MyBHwSPf0GP1tQLKiLf%2BwIx3SnJBFCGue3DZnjKIcXHQAYy9FIeJfHR4j8RoHzCYfret\
  mw439E3CieMZXpwjhXcp6SQF7s9edrwlLiNXA9JGe0Gcd%2BUohOOO4egpcp2YuExhRnaAiCjuDRy\
  iLDbheYJr%2BmdEK8Kg7hHyuN8v3hFu00hfKwN5xRTfkK6VZm5bm&X-Amz-Signature=f88c325f\
  0d69793e784bfbaf7f3e6368a2c054c0f790a3f2597377ae14fb76f2&X-Amz-SignedHeaders=\
  host&x-id=GetObject"
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
        redential=ASIAZI2LB4667FIJDE2I%2F20250219%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250219T102447Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEHoaCXVzLXdlc3QtMiJHMEUCIB65jS6MOsvdMVo5QZBD0Jx4XURLZiF\
        ng7Cp7RN8QV0VAiEAtJKTP716nCFsBIk%2FVGmEd1HQSOSlA7rRy2WMb4flVdcqiAQIo%2F\
        %2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDEJsnDfO2L1rXRVMv\
        CrcA0DwD5lFkJ%2FqcoYFVTiWuQIV%2B04eiKFXxL1n%2FgaHrGQfP4%2BcbhJ%2BG6b8xz\
        n%2FRGTK62vdg0MF4bdsE0M%2F19%2BMhv%2FFXhxBMr1mLHFvsZzalUXvYZCIUVBgI0oWa\
        SjHowkeZdvDYn4VS2UtAzN2Z0modfMrqj2iPnVdVea5GZk%2F%2BNnWe8wgd9YS4qT2sKVT\
        HGEY1ACgZoj%2FbwlYlFfwpTNfNYhdAc7geCR8tVRjuMl8L6uinvLN0Nxl2PhCCMWhSJ9Ur\
        T6fbk64cN2H7%2FiUfdHZjYVPH633sRXVmmI5s48Vmk78WM5WLWzIEBSrMX7SstCtAQSO9t\
        zi%2Bg49Ov7xirdcCqXiCtuazj8AMXLsLhR3cvEIVPMK79UADc6VeYvd12JIDh6Ty3PTea8\
        VQfn79DUqTBfqok1cOq79XrzBlhi%2Fp%2FsLSj4Y1heAbh9mGanYMqwp9gpduZ6ymGomnU\
        7EBeSHryOMdoZPxhh0SwgMW5qES%2B8YE678Vk0NH99GOMUUFohNp002czhuJorpJBtV0pQ\
        vgRV0pS79w4CJ%2BnVGmoV2ezM40wFc5qYxARBdewZd%2FaxxQXFg8Ri%2FYE1%2B3iaPyL\
        %2B8R6%2BtpUsFHr%2BHGMRHVjJHH1dUZZHrgEscgAZ6o9HFMITc1r0GOqUBY9v1sxK90GP\
        fluAuwlQA2Q61FFvfe80yrZ6rfXYSU7lQ5hntASBu2gl73IHawlUBeWIw5Y9zIUTbfi89x6\
        YLUGX804JpBlXQr%2FVUL5bmhSdim%2BHeKRTuH6s01WQ6O0c8uLuTtp%2FDQPrRVl5SkE0\
        cXZ7EKsyDablwV42qrQNsyVrprfXCX6sa7qZcel3MXU%2BeGfJe0QwzrpG7%2Fd6q6tE%2B\
        tNpm1C3Q&X-Amz-Signature=743a1ff141a27e86f93c36a9f7c3010b6f62b3421f9ea3\
        1e0e60c2b5b489bef2&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-19T11:24:47.140Z"
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
UPDATE_TIME: "2025-02-19T10:26:25.236Z"
EXPIRY_TIME: "2025-02-19T11:26:17.355Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SMNNCNEZ%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T102617Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHoaCXVzLXdlc3QtMiJGMEQCIAhZsE0UbW8kjovw%2B%2FSLCEO%2FyZ%2BuJwzVXndDe6lJ6sSXAiBG%2B3Ncp55Pov5xpvnJFX0jtfokTSfZPfQCVQiBNhmk3CqIBAij%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMy2XUpSEgVMmFxhaTKtwDBAEaAH2j1eC%2F1AxFldMAbmYD6FuT6sykKylcD8AchlFk51IOse52cW5FwQhI5ZKS%2F5tk9SHzeM5Klq7wDBMMe2TKWlS6sm9e1%2BijreuWgpE5vfdcQV8jlMYKkQCJEf92jMA%2BzfLXCaqxkafaxh2ypcoSv5J5o7B82r2aOdN%2BjV6HMQJ99YhwAwK2UNxDXUpb50Bmm5FBVorHkwV3sU58OyFFOd2lQRQR3QeKWTbSa13fgsN6avCw%2Bg0TFVMs14kkq2tbH4zFP6Qt83CXmT7M3hsXqyIpTMiId1FlYI7Y0ffQDRrV3rC2suyNpktO3%2FF1i9l43SCEesF5Z%2BQqIJNleuVj%2B6hdoFP5PZqhUwsyYCLNRqv04q5f7x%2B7bm2w3ERIyeuAycQVd6FcLJ3wHm9qOfyVQVVnmHlQbNE5DkGzr5fAE8kT5Kn%2FwcSZ4wqs%2BiaDx1vDDIH31IvHfXmgkppyf%2BW9njhHgxwhwz15hAG%2FWziCtZ0zErjnXMHUe9pYbgSwZXat9Lll13U4iH79S3JSFByvKVQ9rKRSEufCJYiKmcSvbBD%2B8%2BxZBJz0q7tKSuWd6zp88y0nIxX3cUS6NeBRU5n0lnl741OawLCzrmu7LFGTNO1iya2Xi7%2F%2BJRUwstzWvQY6pgHtBkritwoRX1Y2ApifPm4V1M6UqKG0k4eur0srkc5hF0y0uSrshd%2BWGjdP7xtH5fFfe7uW6RL67pwBY1EHeJQ7Wqp2TDwrn4Lqe3kj1WrOpPwxjCxs70Y3r1BVk2Li4ZnWwf4vJyqeXOz07y7vhRptNyMldB9ZXIvpGV7s9GDGDLOWjSz7SqXw%2FRH8YqxwozNIgZzZY5dOoYTEBKGXnweOx%2FJhZDZ0&X-Amz-Signature=b484c488e5c0eff38529eeead3ef96b913563c0d44957a4288e99b19b02da6b2&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SMNNCNEZ%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T102617Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHoaCXVzLXdlc3QtMiJGMEQCIAhZsE0UbW8kjovw%2B%2FSLCEO%2FyZ%2BuJwzVXndDe6lJ6sSXAiBG%2B3Ncp55Pov5xpvnJFX0jtfokTSfZPfQCVQiBNhmk3CqIBAij%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMy2XUpSEgVMmFxhaTKtwDBAEaAH2j1eC%2F1AxFldMAbmYD6FuT6sykKylcD8AchlFk51IOse52cW5FwQhI5ZKS%2F5tk9SHzeM5Klq7wDBMMe2TKWlS6sm9e1%2BijreuWgpE5vfdcQV8jlMYKkQCJEf92jMA%2BzfLXCaqxkafaxh2ypcoSv5J5o7B82r2aOdN%2BjV6HMQJ99YhwAwK2UNxDXUpb50Bmm5FBVorHkwV3sU58OyFFOd2lQRQR3QeKWTbSa13fgsN6avCw%2Bg0TFVMs14kkq2tbH4zFP6Qt83CXmT7M3hsXqyIpTMiId1FlYI7Y0ffQDRrV3rC2suyNpktO3%2FF1i9l43SCEesF5Z%2BQqIJNleuVj%2B6hdoFP5PZqhUwsyYCLNRqv04q5f7x%2B7bm2w3ERIyeuAycQVd6FcLJ3wHm9qOfyVQVVnmHlQbNE5DkGzr5fAE8kT5Kn%2FwcSZ4wqs%2BiaDx1vDDIH31IvHfXmgkppyf%2BW9njhHgxwhwz15hAG%2FWziCtZ0zErjnXMHUe9pYbgSwZXat9Lll13U4iH79S3JSFByvKVQ9rKRSEufCJYiKmcSvbBD%2B8%2BxZBJz0q7tKSuWd6zp88y0nIxX3cUS6NeBRU5n0lnl741OawLCzrmu7LFGTNO1iya2Xi7%2F%2BJRUwstzWvQY6pgHtBkritwoRX1Y2ApifPm4V1M6UqKG0k4eur0srkc5hF0y0uSrshd%2BWGjdP7xtH5fFfe7uW6RL67pwBY1EHeJQ7Wqp2TDwrn4Lqe3kj1WrOpPwxjCxs70Y3r1BVk2Li4ZnWwf4vJyqeXOz07y7vhRptNyMldB9ZXIvpGV7s9GDGDLOWjSz7SqXw%2FRH8YqxwozNIgZzZY5dOoYTEBKGXnweOx%2FJhZDZ0&X-Amz-Signature=9319f68ac0689ec7aaea99a601b9c1ddf8eb36b4a88cdb63f888c24ecd0dd163&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SMNNCNEZ%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T102617Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHoaCXVzLXdlc3QtMiJGMEQCIAhZsE0UbW8kjovw%2B%2FSLCEO%2FyZ%2BuJwzVXndDe6lJ6sSXAiBG%2B3Ncp55Pov5xpvnJFX0jtfokTSfZPfQCVQiBNhmk3CqIBAij%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMy2XUpSEgVMmFxhaTKtwDBAEaAH2j1eC%2F1AxFldMAbmYD6FuT6sykKylcD8AchlFk51IOse52cW5FwQhI5ZKS%2F5tk9SHzeM5Klq7wDBMMe2TKWlS6sm9e1%2BijreuWgpE5vfdcQV8jlMYKkQCJEf92jMA%2BzfLXCaqxkafaxh2ypcoSv5J5o7B82r2aOdN%2BjV6HMQJ99YhwAwK2UNxDXUpb50Bmm5FBVorHkwV3sU58OyFFOd2lQRQR3QeKWTbSa13fgsN6avCw%2Bg0TFVMs14kkq2tbH4zFP6Qt83CXmT7M3hsXqyIpTMiId1FlYI7Y0ffQDRrV3rC2suyNpktO3%2FF1i9l43SCEesF5Z%2BQqIJNleuVj%2B6hdoFP5PZqhUwsyYCLNRqv04q5f7x%2B7bm2w3ERIyeuAycQVd6FcLJ3wHm9qOfyVQVVnmHlQbNE5DkGzr5fAE8kT5Kn%2FwcSZ4wqs%2BiaDx1vDDIH31IvHfXmgkppyf%2BW9njhHgxwhwz15hAG%2FWziCtZ0zErjnXMHUe9pYbgSwZXat9Lll13U4iH79S3JSFByvKVQ9rKRSEufCJYiKmcSvbBD%2B8%2BxZBJz0q7tKSuWd6zp88y0nIxX3cUS6NeBRU5n0lnl741OawLCzrmu7LFGTNO1iya2Xi7%2F%2BJRUwstzWvQY6pgHtBkritwoRX1Y2ApifPm4V1M6UqKG0k4eur0srkc5hF0y0uSrshd%2BWGjdP7xtH5fFfe7uW6RL67pwBY1EHeJQ7Wqp2TDwrn4Lqe3kj1WrOpPwxjCxs70Y3r1BVk2Li4ZnWwf4vJyqeXOz07y7vhRptNyMldB9ZXIvpGV7s9GDGDLOWjSz7SqXw%2FRH8YqxwozNIgZzZY5dOoYTEBKGXnweOx%2FJhZDZ0&X-Amz-Signature=f3189c4770d6fd45450ca7df5779bc9ea35605e167642ecf6863934272bfadd8&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SMNNCNEZ%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T102617Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHoaCXVzLXdlc3QtMiJGMEQCIAhZsE0UbW8kjovw%2B%2FSLCEO%2FyZ%2BuJwzVXndDe6lJ6sSXAiBG%2B3Ncp55Pov5xpvnJFX0jtfokTSfZPfQCVQiBNhmk3CqIBAij%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMy2XUpSEgVMmFxhaTKtwDBAEaAH2j1eC%2F1AxFldMAbmYD6FuT6sykKylcD8AchlFk51IOse52cW5FwQhI5ZKS%2F5tk9SHzeM5Klq7wDBMMe2TKWlS6sm9e1%2BijreuWgpE5vfdcQV8jlMYKkQCJEf92jMA%2BzfLXCaqxkafaxh2ypcoSv5J5o7B82r2aOdN%2BjV6HMQJ99YhwAwK2UNxDXUpb50Bmm5FBVorHkwV3sU58OyFFOd2lQRQR3QeKWTbSa13fgsN6avCw%2Bg0TFVMs14kkq2tbH4zFP6Qt83CXmT7M3hsXqyIpTMiId1FlYI7Y0ffQDRrV3rC2suyNpktO3%2FF1i9l43SCEesF5Z%2BQqIJNleuVj%2B6hdoFP5PZqhUwsyYCLNRqv04q5f7x%2B7bm2w3ERIyeuAycQVd6FcLJ3wHm9qOfyVQVVnmHlQbNE5DkGzr5fAE8kT5Kn%2FwcSZ4wqs%2BiaDx1vDDIH31IvHfXmgkppyf%2BW9njhHgxwhwz15hAG%2FWziCtZ0zErjnXMHUe9pYbgSwZXat9Lll13U4iH79S3JSFByvKVQ9rKRSEufCJYiKmcSvbBD%2B8%2BxZBJz0q7tKSuWd6zp88y0nIxX3cUS6NeBRU5n0lnl741OawLCzrmu7LFGTNO1iya2Xi7%2F%2BJRUwstzWvQY6pgHtBkritwoRX1Y2ApifPm4V1M6UqKG0k4eur0srkc5hF0y0uSrshd%2BWGjdP7xtH5fFfe7uW6RL67pwBY1EHeJQ7Wqp2TDwrn4Lqe3kj1WrOpPwxjCxs70Y3r1BVk2Li4ZnWwf4vJyqeXOz07y7vhRptNyMldB9ZXIvpGV7s9GDGDLOWjSz7SqXw%2FRH8YqxwozNIgZzZY5dOoYTEBKGXnweOx%2FJhZDZ0&X-Amz-Signature=1cf2ce94309e6fd3f01d5a7349d4a76d76fe56a1fb2f1f9574aab15d8a2f9c55&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SMNNCNEZ%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T102617Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHoaCXVzLXdlc3QtMiJGMEQCIAhZsE0UbW8kjovw%2B%2FSLCEO%2FyZ%2BuJwzVXndDe6lJ6sSXAiBG%2B3Ncp55Pov5xpvnJFX0jtfokTSfZPfQCVQiBNhmk3CqIBAij%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMy2XUpSEgVMmFxhaTKtwDBAEaAH2j1eC%2F1AxFldMAbmYD6FuT6sykKylcD8AchlFk51IOse52cW5FwQhI5ZKS%2F5tk9SHzeM5Klq7wDBMMe2TKWlS6sm9e1%2BijreuWgpE5vfdcQV8jlMYKkQCJEf92jMA%2BzfLXCaqxkafaxh2ypcoSv5J5o7B82r2aOdN%2BjV6HMQJ99YhwAwK2UNxDXUpb50Bmm5FBVorHkwV3sU58OyFFOd2lQRQR3QeKWTbSa13fgsN6avCw%2Bg0TFVMs14kkq2tbH4zFP6Qt83CXmT7M3hsXqyIpTMiId1FlYI7Y0ffQDRrV3rC2suyNpktO3%2FF1i9l43SCEesF5Z%2BQqIJNleuVj%2B6hdoFP5PZqhUwsyYCLNRqv04q5f7x%2B7bm2w3ERIyeuAycQVd6FcLJ3wHm9qOfyVQVVnmHlQbNE5DkGzr5fAE8kT5Kn%2FwcSZ4wqs%2BiaDx1vDDIH31IvHfXmgkppyf%2BW9njhHgxwhwz15hAG%2FWziCtZ0zErjnXMHUe9pYbgSwZXat9Lll13U4iH79S3JSFByvKVQ9rKRSEufCJYiKmcSvbBD%2B8%2BxZBJz0q7tKSuWd6zp88y0nIxX3cUS6NeBRU5n0lnl741OawLCzrmu7LFGTNO1iya2Xi7%2F%2BJRUwstzWvQY6pgHtBkritwoRX1Y2ApifPm4V1M6UqKG0k4eur0srkc5hF0y0uSrshd%2BWGjdP7xtH5fFfe7uW6RL67pwBY1EHeJQ7Wqp2TDwrn4Lqe3kj1WrOpPwxjCxs70Y3r1BVk2Li4ZnWwf4vJyqeXOz07y7vhRptNyMldB9ZXIvpGV7s9GDGDLOWjSz7SqXw%2FRH8YqxwozNIgZzZY5dOoYTEBKGXnweOx%2FJhZDZ0&X-Amz-Signature=4236b2e8055e84af01fa804be184b5e9a16e12f80411b1c86707ef51bf0cf885&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RTSKTDMP%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T102618Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHoaCXVzLXdlc3QtMiJHMEUCICjJdWPJnIUCStY%2FMcv1N5aVLjMYcIvvAaBnYul22kE0AiEAwQ9UHvSmMLt4j66ujQCrJ8eRbMbZ3prq%2Bl%2B8mC%2FOBHcqiAQIo%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOSLRoB%2F4kd6e%2BvJbCrcA6Tf3ogJMLdG4gRGsPDc5Zw2z48LobPEnT78WqlU31yy9qE3GQkcDX7DSJOnMg1%2FcEqzxKkqelu6XAzJAfRdwRnRU9YLSfwS8p71B2dcsfjdAQrtgu%2FZYecLheF35d%2BR%2FvPA5jGeRc8vW5wbkXbieip8V8LyveQzRMyGZmbmOY5NcWRvWkVg1Io5eBl7XyrL3%2FiLv5NnWfygKFu4fqgvhswLIO8pGxD6yigFer0cLxm4sqEWuErc2jRdRw3xMLo6YXoBOURjO7uBpbWj1RkZ8zf%2BBmpyr88fcR78ffASyN2I7BXzi1hsPphZuId1%2BYsx%2F%2BQjEr4%2B0qmTCY35A0B3xNSwpA5Nq5IzidPGtEg6j6VTJJtBvG7r41H%2FUrTnak26Uj2A%2Fh3BsfVO3WZnaHSzbIohIDjkxhxuad%2FV%2B%2Fw09zyQCLdaHPyslecS1XTCF4zjlUuQ%2FbezwzeXpyKRbSnoBEBM7C9WV5njbkdQh0u4CzivO6OUWbtcDzfYNhXvxOp4anlMCdYNgzBo54Uego9HMXbwXc2%2FHRhunfn0snQnnBtYvKiFgJYMDp%2B9yg82USeTEm0JUmvWR4QZasGuFq%2Fy3V4qr0DVTpVANMp%2FnsouRBniqUSNXOCKtTnDMXKVMPTb1r0GOqUBlgx2qu44Dcp41wCZ8nAzc6PJszl%2FsrIPzCGWuoS7veyceyt6A0d6w9vRf3kpLEzFW0diFdrUbFQbSG4PIkQDjLxdioZ0sieC2nCU1g0K0qbU26o%2FN6wg7I7dcuDOYVVXNGH9z9HTaud28gJpHHMKEv7WSjiog2VYyi0CEq29I151lCUt0C0bZ3ex9uNxdi4d%2F2DxbnICmyPS7sGG2gCzwohXuAPl&X-Amz-Signature=840349237cc38f61f84b74f21135038ae1d42afb7daa73d5f3654f60fb9ab8ad&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UAGF4YHA%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T102619Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHoaCXVzLXdlc3QtMiJGMEQCIFFUSy9%2FrnhdpJ0Twun%2FSih5wbBdQxtphKZRFtLGf1arAiB5zQraC80WECnRtkFhYoqXHmTj20JN%2Ff%2B9avdYn%2BNPTiqIBAij%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMH%2Brt2okgOehhyuM2KtwDwPS1R2fZAAZIKXDR5oZVFYuslahXg%2FulLwbrm7A6l%2BM4PMcd5lJKaJPz0IRDhn9r4UaTCumHNxJMMB86pi4l%2B32aAqDIEHtQHYYKkyc8B59jo2HwrZXyZVMukmgKj3YGu6CJ%2Foyt26jHjIsWXnokRbRofQSrDqlVI9bxKaqaM3mD7GhnESlfR69Jusz4jpn2FuBy3jdFYLe2A0CsOXGgB8e4qSlLYsZaScUVmLtV2CYR7KZ%2BL1p43p7nxfk%2BWggSO8J9hYCT%2BG%2BnysqT4%2BOcCU6YTw5AvTT%2B0%2BBx%2FEqMAOvuKByXzXd922dLka4Gp1iklOhdc0XCNRoisuZL9NTwXEKodJCb%2FKIrbOouZgc4gidv5mctq3hL7Lnr8Zo%2BXakVEOUa9NdYBqRkeqftx16kzo4nw2WcgTgTr678xoB%2FkWg6KnWVo3xBznUZ%2B6ChnQpZz2wyAiyq9HA%2FBN%2FvHPuyA4HhBDThIPH4dI566HE35GygdXreyAslO5kjG4kxWi6WvaoVP3px0tqF5HAjv6j6dkAAcpfhdfsH%2FRkPASoQfu7M2u8%2B9YUe6gzwAZvAVgpB5aor3LuBJdC5I9zW%2F7ExI2zKj0OU368fkuvqnQXQ7Ct9pj03FIJKdPDLbvAwmtzWvQY6pgFx1DXMgLhATFfyG5QMg3zSSh7LeTt%2BfuR%2Bx51EgeOX2voijKv3Lzml1EQBa4gQMlhF3Acfe08osoDLui9TZ%2BTwWTX1BAxnAmM1RrBD083OcRbX9HeNvIjt1l9BFTX9LCQLPZXH8epxX0KLa%2B2469%2FXIL9HeZt%2FnYmcFkkXgVZ3fO8Ute4wknfDtVvtFHJQbwjYaTC9NA6wp1WbZ3T%2FvB%2Ferk1vX4tp&X-Amz-Signature=6d9f4868f93598d559f2a5e124eaa31faf8415303f567cadb97e1db5dab971c1&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SMNNCNEZ%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T102617Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHoaCXVzLXdlc3QtMiJGMEQCIAhZsE0UbW8kjovw%2B%2FSLCEO%2FyZ%2BuJwzVXndDe6lJ6sSXAiBG%2B3Ncp55Pov5xpvnJFX0jtfokTSfZPfQCVQiBNhmk3CqIBAij%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMy2XUpSEgVMmFxhaTKtwDBAEaAH2j1eC%2F1AxFldMAbmYD6FuT6sykKylcD8AchlFk51IOse52cW5FwQhI5ZKS%2F5tk9SHzeM5Klq7wDBMMe2TKWlS6sm9e1%2BijreuWgpE5vfdcQV8jlMYKkQCJEf92jMA%2BzfLXCaqxkafaxh2ypcoSv5J5o7B82r2aOdN%2BjV6HMQJ99YhwAwK2UNxDXUpb50Bmm5FBVorHkwV3sU58OyFFOd2lQRQR3QeKWTbSa13fgsN6avCw%2Bg0TFVMs14kkq2tbH4zFP6Qt83CXmT7M3hsXqyIpTMiId1FlYI7Y0ffQDRrV3rC2suyNpktO3%2FF1i9l43SCEesF5Z%2BQqIJNleuVj%2B6hdoFP5PZqhUwsyYCLNRqv04q5f7x%2B7bm2w3ERIyeuAycQVd6FcLJ3wHm9qOfyVQVVnmHlQbNE5DkGzr5fAE8kT5Kn%2FwcSZ4wqs%2BiaDx1vDDIH31IvHfXmgkppyf%2BW9njhHgxwhwz15hAG%2FWziCtZ0zErjnXMHUe9pYbgSwZXat9Lll13U4iH79S3JSFByvKVQ9rKRSEufCJYiKmcSvbBD%2B8%2BxZBJz0q7tKSuWd6zp88y0nIxX3cUS6NeBRU5n0lnl741OawLCzrmu7LFGTNO1iya2Xi7%2F%2BJRUwstzWvQY6pgHtBkritwoRX1Y2ApifPm4V1M6UqKG0k4eur0srkc5hF0y0uSrshd%2BWGjdP7xtH5fFfe7uW6RL67pwBY1EHeJQ7Wqp2TDwrn4Lqe3kj1WrOpPwxjCxs70Y3r1BVk2Li4ZnWwf4vJyqeXOz07y7vhRptNyMldB9ZXIvpGV7s9GDGDLOWjSz7SqXw%2FRH8YqxwozNIgZzZY5dOoYTEBKGXnweOx%2FJhZDZ0&X-Amz-Signature=03dddee98f9a71f7e4ba8e5eddcfa12ee380d1763d7f891fc66f6748ba15ae42&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SMNNCNEZ%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T102617Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHoaCXVzLXdlc3QtMiJGMEQCIAhZsE0UbW8kjovw%2B%2FSLCEO%2FyZ%2BuJwzVXndDe6lJ6sSXAiBG%2B3Ncp55Pov5xpvnJFX0jtfokTSfZPfQCVQiBNhmk3CqIBAij%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMy2XUpSEgVMmFxhaTKtwDBAEaAH2j1eC%2F1AxFldMAbmYD6FuT6sykKylcD8AchlFk51IOse52cW5FwQhI5ZKS%2F5tk9SHzeM5Klq7wDBMMe2TKWlS6sm9e1%2BijreuWgpE5vfdcQV8jlMYKkQCJEf92jMA%2BzfLXCaqxkafaxh2ypcoSv5J5o7B82r2aOdN%2BjV6HMQJ99YhwAwK2UNxDXUpb50Bmm5FBVorHkwV3sU58OyFFOd2lQRQR3QeKWTbSa13fgsN6avCw%2Bg0TFVMs14kkq2tbH4zFP6Qt83CXmT7M3hsXqyIpTMiId1FlYI7Y0ffQDRrV3rC2suyNpktO3%2FF1i9l43SCEesF5Z%2BQqIJNleuVj%2B6hdoFP5PZqhUwsyYCLNRqv04q5f7x%2B7bm2w3ERIyeuAycQVd6FcLJ3wHm9qOfyVQVVnmHlQbNE5DkGzr5fAE8kT5Kn%2FwcSZ4wqs%2BiaDx1vDDIH31IvHfXmgkppyf%2BW9njhHgxwhwz15hAG%2FWziCtZ0zErjnXMHUe9pYbgSwZXat9Lll13U4iH79S3JSFByvKVQ9rKRSEufCJYiKmcSvbBD%2B8%2BxZBJz0q7tKSuWd6zp88y0nIxX3cUS6NeBRU5n0lnl741OawLCzrmu7LFGTNO1iya2Xi7%2F%2BJRUwstzWvQY6pgHtBkritwoRX1Y2ApifPm4V1M6UqKG0k4eur0srkc5hF0y0uSrshd%2BWGjdP7xtH5fFfe7uW6RL67pwBY1EHeJQ7Wqp2TDwrn4Lqe3kj1WrOpPwxjCxs70Y3r1BVk2Li4ZnWwf4vJyqeXOz07y7vhRptNyMldB9ZXIvpGV7s9GDGDLOWjSz7SqXw%2FRH8YqxwozNIgZzZY5dOoYTEBKGXnweOx%2FJhZDZ0&X-Amz-Signature=3b5aadf89e09043baa7c441e054942e14a4e677e86c28e31acd5f94a9bcff306&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SMNNCNEZ%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T102617Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHoaCXVzLXdlc3QtMiJGMEQCIAhZsE0UbW8kjovw%2B%2FSLCEO%2FyZ%2BuJwzVXndDe6lJ6sSXAiBG%2B3Ncp55Pov5xpvnJFX0jtfokTSfZPfQCVQiBNhmk3CqIBAij%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMy2XUpSEgVMmFxhaTKtwDBAEaAH2j1eC%2F1AxFldMAbmYD6FuT6sykKylcD8AchlFk51IOse52cW5FwQhI5ZKS%2F5tk9SHzeM5Klq7wDBMMe2TKWlS6sm9e1%2BijreuWgpE5vfdcQV8jlMYKkQCJEf92jMA%2BzfLXCaqxkafaxh2ypcoSv5J5o7B82r2aOdN%2BjV6HMQJ99YhwAwK2UNxDXUpb50Bmm5FBVorHkwV3sU58OyFFOd2lQRQR3QeKWTbSa13fgsN6avCw%2Bg0TFVMs14kkq2tbH4zFP6Qt83CXmT7M3hsXqyIpTMiId1FlYI7Y0ffQDRrV3rC2suyNpktO3%2FF1i9l43SCEesF5Z%2BQqIJNleuVj%2B6hdoFP5PZqhUwsyYCLNRqv04q5f7x%2B7bm2w3ERIyeuAycQVd6FcLJ3wHm9qOfyVQVVnmHlQbNE5DkGzr5fAE8kT5Kn%2FwcSZ4wqs%2BiaDx1vDDIH31IvHfXmgkppyf%2BW9njhHgxwhwz15hAG%2FWziCtZ0zErjnXMHUe9pYbgSwZXat9Lll13U4iH79S3JSFByvKVQ9rKRSEufCJYiKmcSvbBD%2B8%2BxZBJz0q7tKSuWd6zp88y0nIxX3cUS6NeBRU5n0lnl741OawLCzrmu7LFGTNO1iya2Xi7%2F%2BJRUwstzWvQY6pgHtBkritwoRX1Y2ApifPm4V1M6UqKG0k4eur0srkc5hF0y0uSrshd%2BWGjdP7xtH5fFfe7uW6RL67pwBY1EHeJQ7Wqp2TDwrn4Lqe3kj1WrOpPwxjCxs70Y3r1BVk2Li4ZnWwf4vJyqeXOz07y7vhRptNyMldB9ZXIvpGV7s9GDGDLOWjSz7SqXw%2FRH8YqxwozNIgZzZY5dOoYTEBKGXnweOx%2FJhZDZ0&X-Amz-Signature=bdc885da1a58201e52341d3b3e1598227180882b1d115b977f682f2b3fc0af06&X-Amz-SignedHeaders=host&x-id=GetObject)


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

