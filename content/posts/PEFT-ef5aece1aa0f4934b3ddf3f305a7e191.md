---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466SF4MSQSW%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250129T082936Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEIH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIFvrH6yRpBNecMij13L\
  jUfx1Q3SU3WlWjC9ucaXccnnBAiBvGStRE5K%2B4hS9RgHcxJJp2t1IpjR3ptBggsc3pGDlLiqIBA\
  iJ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMjEJsqEJoA4%2FE759gK\
  twD6uLhX0AS%2FqqfasPLUnka7QhpFXGvpPojrGzzN8ULzKqB6p08DKHaErfw%2FVK98NrCoh1jx0\
  dW6inPD%2FoSKNdK8iKGzKkjiuVOOY6fybnosKvcmReln351x8Z2tkl6hS7ZjAB4hrvCf1uwRzpXy\
  rF8PHEQ6W%2FbEVrmI6p%2BNCTtpktTWSGkNkpEPo%2B%2B7lEaDMj2C%2FXYeinURhLGcZ2tLyDp\
  0n6OMBwI8y89Q0bwZveOqJzwwW49%2BJOmfhbkSh5DcX5WJgJdn%2BEC7VMHmCUKTcIKKb6UUH3Lw\
  nkekx%2FJQmvy0DGKQLQZi%2BpDgknNbI0mQ40grLI8J%2FPfcQUpSqP11i3Ocrw9eUYSPYJ10E4Q\
  1Ke%2BxMYBKTDs6oRF0g5WXRavUdI5aYyKJj4Urz7oqu86QDQgOCVbY1sAvS0b9vziIhOrH6FHWsx\
  pM9mlCB4MRxQSnfSkWM%2FwPIp9MjcYDVjCTtDK5OKOeS%2Bvms2C93%2FljXTOo%2FLA9Q%2FNlE\
  u2udbcSO22v3LM4cVFHxFajxooXecBzKVIONiwxWMGfpGTmbZ56Xf%2BYUTt7TW8Qa9dD4Rc9P42g\
  NdNmrWmV0lHpDC%2Bx5fL08oo%2B%2BrQHmxz2Nj6T8FcqKXqHlUMsHYC5Ke2f05WtAww6sjnvAY6\
  pgHxK31JL1ATEfgYc7HFi%2Fm3W2idS12ewAnuWZZ37oDlJ49haXYA2PmeY8AiBzN6Q%2BE1zsnSv\
  ma6EGzVqyh7Lnb8vo5AUys0nc76wWyyH7Yvko9RJcjV1wFg5JhjPz5a20Jj%2FTrDGaYxGbYGGfG7\
  NUuvGXe7ciSgBpaHaUpj%2FSjaunLGpK4H7yTfY4zBBsdFptKK7mxI1LbHOqm5T%2BVJnsCM7gffM\
  wzG&X-Amz-Signature=1aa302ad2d081cdf0d98bd913269538715d05935e8a8f16ae36f3de5a\
  9710436&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466VITFCQ2V%2F20250129%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250129T082813Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEIH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQ\
        CIF8XEKREU86JuYLncvtqTV6Z1PEiBkWl0SGAA2Pbo8WEAiA5RKAdBbnPPyNNPVz%2FOqjS\
        sbTUfx5nrKMI8jsLMKwlVyqIBAiJ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQ\
        yMzE4MzgwNSIMnXMcX7AKu%2Fftb4gYKtwDYxtdqGv%2Byu52B1jW9Ru%2FtWTyky1QT86L\
        YRSrrqB61otWh0GYmAKlXW7V2IL023gt5BkNOssYJonSgaNWAVJdTlWmFmlD3a7eWiJOhaj\
        ZH%2FHwkrVSBe9cj55jlNa8Dp73iLFcEYqZHOciM9trEwBkao4Rc7gN2%2FpsddK8pnW1Mt\
        A6D3nwux%2BEYtrRUz6FvO407DvdShmRgplB4aJzFJrENae7SyeTNL64l8t9KxvoWID86EE\
        TdDoSRyR5LFNh5YtXhs3U3vQRgY3s2M%2FY8376CdiiSYwTAeNIrc9kSK2p6IlB9rvgy209\
        xHk%2FHYNr91b4q3y%2BeclBJOm1nbnLUyrs20ZawtsV0vgGuiLkmb2vtGWs9U%2FJfaHKj\
        5Df25lbUB8%2BPZ%2B5%2FYNEUXAxIytmb8rC2VBcFisIxKxTan%2Fp%2BdSac7wYL5%2Fe\
        pU4KyGQLE9Wzg37GPlp6SfTD2ylxiCcqGrdVkuUTAGdcA7usebTTwjfNRUTOOXWBQ6578cc\
        e9rUEjH5G44OxU4CfCDcYJSYm7GxeU4q8EoykjjBg4KgOAHrc1PFZUudRBX40XU8SzVF8S6\
        %2BQECjs03fOvMzCekF2222SW5ot5%2BW0dwzuL84kn6pYiE%2Fwqwhrc4W06F8psBAwqsn\
        nvAY6pgFedLtnR3vKunBWg7wtjWzOgCnfXAW84Y%2Fyue%2BsBuQ22TDu3EEGhH2oUEGpd8\
        NOxbIBvnPj3i04JsAHr3FJd%2B5ZjnRzoH199hfZtIWN3BnsMCGnDFXJBcMLZ8TOlmXEYQs\
        YB1tnT24ye%2Fz55E2VFFILQ5XdOKtts6YnM9cU09doM7BPwrTvA3pgrk9uNBZbWMPR0tNs\
        7rekqgmh8fAjqDSTqXPvsEZt&X-Amz-Signature=7eff356b12fd1ab85af7e070aee406\
        e78db286a632c2905756ce1e4c4e81c60d&X-Amz-SignedHeaders=host&x-id=GetObj\
        ect"
      expiry_time: "2025-01-29T09:28:13.174Z"
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
UPDATE_TIME: "2025-01-29T08:29:43.062Z"
EXPIRY_TIME: "2025-01-29T09:29:34.296Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667JN5XKYJ%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T082934Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIFnXAJwjz1mr%2B%2BEnnpTB11EKANHBNuhTEE%2Fa7aX8xET4AiA1JBpx5EktugHzU64zxE7XCGE03rLCCdkZ5XAxiDdX7yqIBAiJ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMmdFvkvhqKSdnYYd7KtwD6yfkz75oMHNZtfUBDxf9tf3jQ%2BNtSulhbRJUWIRAYrLQzoP2Whxr0rqGf%2BO3P3aNFvEHHOJCzVk0QUdxdz8Whv5OPw7LsbBYKLob7i0whBZZYSFfxgLT1G2TzjAuKPLRBuCWHBnO62KpmsGdAz1xhgIIITcLClmiO0TPJFgJrxBH6kswHgZn7vFSAEpVSlkhcAptxXblXyqxDqLLS5WUP7jMhEg4ZjhsLCyRBYEB9va0A4fji0ATrBn4ZTBtmKHtP5Y3wCM%2FODL%2Bq%2BAdBa0RTW3vdiNl7w57UK8ufO5Gchw2G0eo6rZ6SqE1t6KNfy4rlvUhQp%2F8KHpKI3l%2B5m2ztNUk1PE1JN9tfMLXfwuqu1OAzfEMdIjBM4HaddviDSFmd9p%2BM2QGVlZ%2FLAVesr5p%2BbPZv5VzhBzfbrc9mU%2FgyCvN9ttRAdCgEy9PucInnFRsuvRPWgBQA%2B2UnavcOOmcDO92MrVUWz2wDt%2FF7GllP2rwN2mC%2FTjJc0SSSWV2OeDxbnTSTgDO7AiIVWOmqSGpgCHy%2F6v8FhznFyLZ6MuolasR8MhFGIG6j8qtwaWdgf%2BGctiW9v40zfhhBjjYrEBwqBoz0EdPzG6iGoYx3DDXRCf7WWeEByo%2B6Xo%2BTu0w08nnvAY6pgEt%2F1CuBDikqNXbusS5L0VGg%2Fa3R371YZrP6rt1bY5ythJarbOhRjbkGOUmhFeFDGguU95eNaLzvEWO%2FoWEWmfSnp%2FpUc7tvIEXuWdeuvE1st8EA1ldhwcdNrtA5Isa5WLYCzdy2I8Ov%2FP9yabge8QiVBGidCPL0LDlDW5HJ%2BPWTOlmkpiIVH3%2FTmlGcD%2F7gStYSmCCRHWQpYYBhVMKQKahCF5jOOUH&X-Amz-Signature=62e9e51e9386121f51675f80ee2e4055fa0a082e7ecbcda7e26f5cc04e21189e&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667JN5XKYJ%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T082934Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIFnXAJwjz1mr%2B%2BEnnpTB11EKANHBNuhTEE%2Fa7aX8xET4AiA1JBpx5EktugHzU64zxE7XCGE03rLCCdkZ5XAxiDdX7yqIBAiJ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMmdFvkvhqKSdnYYd7KtwD6yfkz75oMHNZtfUBDxf9tf3jQ%2BNtSulhbRJUWIRAYrLQzoP2Whxr0rqGf%2BO3P3aNFvEHHOJCzVk0QUdxdz8Whv5OPw7LsbBYKLob7i0whBZZYSFfxgLT1G2TzjAuKPLRBuCWHBnO62KpmsGdAz1xhgIIITcLClmiO0TPJFgJrxBH6kswHgZn7vFSAEpVSlkhcAptxXblXyqxDqLLS5WUP7jMhEg4ZjhsLCyRBYEB9va0A4fji0ATrBn4ZTBtmKHtP5Y3wCM%2FODL%2Bq%2BAdBa0RTW3vdiNl7w57UK8ufO5Gchw2G0eo6rZ6SqE1t6KNfy4rlvUhQp%2F8KHpKI3l%2B5m2ztNUk1PE1JN9tfMLXfwuqu1OAzfEMdIjBM4HaddviDSFmd9p%2BM2QGVlZ%2FLAVesr5p%2BbPZv5VzhBzfbrc9mU%2FgyCvN9ttRAdCgEy9PucInnFRsuvRPWgBQA%2B2UnavcOOmcDO92MrVUWz2wDt%2FF7GllP2rwN2mC%2FTjJc0SSSWV2OeDxbnTSTgDO7AiIVWOmqSGpgCHy%2F6v8FhznFyLZ6MuolasR8MhFGIG6j8qtwaWdgf%2BGctiW9v40zfhhBjjYrEBwqBoz0EdPzG6iGoYx3DDXRCf7WWeEByo%2B6Xo%2BTu0w08nnvAY6pgEt%2F1CuBDikqNXbusS5L0VGg%2Fa3R371YZrP6rt1bY5ythJarbOhRjbkGOUmhFeFDGguU95eNaLzvEWO%2FoWEWmfSnp%2FpUc7tvIEXuWdeuvE1st8EA1ldhwcdNrtA5Isa5WLYCzdy2I8Ov%2FP9yabge8QiVBGidCPL0LDlDW5HJ%2BPWTOlmkpiIVH3%2FTmlGcD%2F7gStYSmCCRHWQpYYBhVMKQKahCF5jOOUH&X-Amz-Signature=ed3c0814ba7ee608662a3e8c4f88f983fb6ab4b7d39b7be38e13eabf30c6d391&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667JN5XKYJ%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T082934Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIFnXAJwjz1mr%2B%2BEnnpTB11EKANHBNuhTEE%2Fa7aX8xET4AiA1JBpx5EktugHzU64zxE7XCGE03rLCCdkZ5XAxiDdX7yqIBAiJ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMmdFvkvhqKSdnYYd7KtwD6yfkz75oMHNZtfUBDxf9tf3jQ%2BNtSulhbRJUWIRAYrLQzoP2Whxr0rqGf%2BO3P3aNFvEHHOJCzVk0QUdxdz8Whv5OPw7LsbBYKLob7i0whBZZYSFfxgLT1G2TzjAuKPLRBuCWHBnO62KpmsGdAz1xhgIIITcLClmiO0TPJFgJrxBH6kswHgZn7vFSAEpVSlkhcAptxXblXyqxDqLLS5WUP7jMhEg4ZjhsLCyRBYEB9va0A4fji0ATrBn4ZTBtmKHtP5Y3wCM%2FODL%2Bq%2BAdBa0RTW3vdiNl7w57UK8ufO5Gchw2G0eo6rZ6SqE1t6KNfy4rlvUhQp%2F8KHpKI3l%2B5m2ztNUk1PE1JN9tfMLXfwuqu1OAzfEMdIjBM4HaddviDSFmd9p%2BM2QGVlZ%2FLAVesr5p%2BbPZv5VzhBzfbrc9mU%2FgyCvN9ttRAdCgEy9PucInnFRsuvRPWgBQA%2B2UnavcOOmcDO92MrVUWz2wDt%2FF7GllP2rwN2mC%2FTjJc0SSSWV2OeDxbnTSTgDO7AiIVWOmqSGpgCHy%2F6v8FhznFyLZ6MuolasR8MhFGIG6j8qtwaWdgf%2BGctiW9v40zfhhBjjYrEBwqBoz0EdPzG6iGoYx3DDXRCf7WWeEByo%2B6Xo%2BTu0w08nnvAY6pgEt%2F1CuBDikqNXbusS5L0VGg%2Fa3R371YZrP6rt1bY5ythJarbOhRjbkGOUmhFeFDGguU95eNaLzvEWO%2FoWEWmfSnp%2FpUc7tvIEXuWdeuvE1st8EA1ldhwcdNrtA5Isa5WLYCzdy2I8Ov%2FP9yabge8QiVBGidCPL0LDlDW5HJ%2BPWTOlmkpiIVH3%2FTmlGcD%2F7gStYSmCCRHWQpYYBhVMKQKahCF5jOOUH&X-Amz-Signature=b341b4a2bde82adbe5b63596835624c59e2334ac7fa45b16b5ea1dd29b9ae11b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667JN5XKYJ%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T082934Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIFnXAJwjz1mr%2B%2BEnnpTB11EKANHBNuhTEE%2Fa7aX8xET4AiA1JBpx5EktugHzU64zxE7XCGE03rLCCdkZ5XAxiDdX7yqIBAiJ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMmdFvkvhqKSdnYYd7KtwD6yfkz75oMHNZtfUBDxf9tf3jQ%2BNtSulhbRJUWIRAYrLQzoP2Whxr0rqGf%2BO3P3aNFvEHHOJCzVk0QUdxdz8Whv5OPw7LsbBYKLob7i0whBZZYSFfxgLT1G2TzjAuKPLRBuCWHBnO62KpmsGdAz1xhgIIITcLClmiO0TPJFgJrxBH6kswHgZn7vFSAEpVSlkhcAptxXblXyqxDqLLS5WUP7jMhEg4ZjhsLCyRBYEB9va0A4fji0ATrBn4ZTBtmKHtP5Y3wCM%2FODL%2Bq%2BAdBa0RTW3vdiNl7w57UK8ufO5Gchw2G0eo6rZ6SqE1t6KNfy4rlvUhQp%2F8KHpKI3l%2B5m2ztNUk1PE1JN9tfMLXfwuqu1OAzfEMdIjBM4HaddviDSFmd9p%2BM2QGVlZ%2FLAVesr5p%2BbPZv5VzhBzfbrc9mU%2FgyCvN9ttRAdCgEy9PucInnFRsuvRPWgBQA%2B2UnavcOOmcDO92MrVUWz2wDt%2FF7GllP2rwN2mC%2FTjJc0SSSWV2OeDxbnTSTgDO7AiIVWOmqSGpgCHy%2F6v8FhznFyLZ6MuolasR8MhFGIG6j8qtwaWdgf%2BGctiW9v40zfhhBjjYrEBwqBoz0EdPzG6iGoYx3DDXRCf7WWeEByo%2B6Xo%2BTu0w08nnvAY6pgEt%2F1CuBDikqNXbusS5L0VGg%2Fa3R371YZrP6rt1bY5ythJarbOhRjbkGOUmhFeFDGguU95eNaLzvEWO%2FoWEWmfSnp%2FpUc7tvIEXuWdeuvE1st8EA1ldhwcdNrtA5Isa5WLYCzdy2I8Ov%2FP9yabge8QiVBGidCPL0LDlDW5HJ%2BPWTOlmkpiIVH3%2FTmlGcD%2F7gStYSmCCRHWQpYYBhVMKQKahCF5jOOUH&X-Amz-Signature=bcb8ce0cdbb58f05bdc38df0264306681394b14da4f4bdde5128a174cbdd80bb&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667JN5XKYJ%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T082934Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIFnXAJwjz1mr%2B%2BEnnpTB11EKANHBNuhTEE%2Fa7aX8xET4AiA1JBpx5EktugHzU64zxE7XCGE03rLCCdkZ5XAxiDdX7yqIBAiJ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMmdFvkvhqKSdnYYd7KtwD6yfkz75oMHNZtfUBDxf9tf3jQ%2BNtSulhbRJUWIRAYrLQzoP2Whxr0rqGf%2BO3P3aNFvEHHOJCzVk0QUdxdz8Whv5OPw7LsbBYKLob7i0whBZZYSFfxgLT1G2TzjAuKPLRBuCWHBnO62KpmsGdAz1xhgIIITcLClmiO0TPJFgJrxBH6kswHgZn7vFSAEpVSlkhcAptxXblXyqxDqLLS5WUP7jMhEg4ZjhsLCyRBYEB9va0A4fji0ATrBn4ZTBtmKHtP5Y3wCM%2FODL%2Bq%2BAdBa0RTW3vdiNl7w57UK8ufO5Gchw2G0eo6rZ6SqE1t6KNfy4rlvUhQp%2F8KHpKI3l%2B5m2ztNUk1PE1JN9tfMLXfwuqu1OAzfEMdIjBM4HaddviDSFmd9p%2BM2QGVlZ%2FLAVesr5p%2BbPZv5VzhBzfbrc9mU%2FgyCvN9ttRAdCgEy9PucInnFRsuvRPWgBQA%2B2UnavcOOmcDO92MrVUWz2wDt%2FF7GllP2rwN2mC%2FTjJc0SSSWV2OeDxbnTSTgDO7AiIVWOmqSGpgCHy%2F6v8FhznFyLZ6MuolasR8MhFGIG6j8qtwaWdgf%2BGctiW9v40zfhhBjjYrEBwqBoz0EdPzG6iGoYx3DDXRCf7WWeEByo%2B6Xo%2BTu0w08nnvAY6pgEt%2F1CuBDikqNXbusS5L0VGg%2Fa3R371YZrP6rt1bY5ythJarbOhRjbkGOUmhFeFDGguU95eNaLzvEWO%2FoWEWmfSnp%2FpUc7tvIEXuWdeuvE1st8EA1ldhwcdNrtA5Isa5WLYCzdy2I8Ov%2FP9yabge8QiVBGidCPL0LDlDW5HJ%2BPWTOlmkpiIVH3%2FTmlGcD%2F7gStYSmCCRHWQpYYBhVMKQKahCF5jOOUH&X-Amz-Signature=793430f3a327459ad6a1420ef1f6d3c13d8a9cb204ffc5f5e44b384a23f96d89&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RUDNJ3L5%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T082935Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD4FL6Q3ALZmwkmwU%2FnxwB6pU4g6XmdL8vq42lO%2F7BW4wIhANvde0cCcGN3WJwCsb0hVQaGQ6%2Fnj%2Fp2aMi6UJLACqVoKogECIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igz4i%2FGshP5p41%2BFXeAq3ANtca7yS4tUAr2Y9T43hzfkGkq4iUY5hrsGUW56%2F3HkIM3AJ6t9sgvGSBIcKe99RInxGAVN51b0Zv2eTPxiulCGA9lc%2Fm%2Bj4kjFv5VETkicCUjcKUbFTkStyzsAh1m9kPbT3r9arGQVBjMGAc2p3Dt9NeT9z%2BoaivLUXS5b3gL4aiQsCo4Fe55bIrM1aM6EgXLAqdCNFsZU%2B%2BQqncwkjbXgYNxZa3QBFP9wVn5DJGKDcp2a7uywNoJWUbnnUKhySSHIPyCgh5dw%2FtH4SoUYgBehN%2F3L6%2BfXFzQTTlG5KXSKffEsPC2JYCUoPBAGrYkAKhzkK3HBc5Dcr9ArDxrcyYKPwTWAMGVCdTOjiPGNTnkMED5V36x4ByU84EP24nIkncE1%2FT%2FQsi5CC7a1c7o2WXvcGCDi%2FMFCEFL6GrIu8dpth9QKqSOrgX8LgJmfXLaUVrfwSqyZVn1cxND%2FzevBlsg3JdNTZUMLZ5A1fEf9dCh2iDTejLXrS5RCjaVub2eXOIn9IB2EliCxaoP6zVO%2FpjEOCvWFjY67UwMzid%2FlsEZHYUFayWj7eOTLRyOdVk2TP2M5S0lsQArnE7tK3hp2PufRpkMIhVDxGi18lhjM5hZbNGTfo9%2BBSOpfdmrYhDD0yee8BjqkAWwPYwGcTtJ1NmUIn%2Ba2BO%2BmaZbc5NxBTMWcyvCV4Rz2TMPVbAWRq65IRZQtpixzMgOdLM9YAejlF0B1CyarAdjjSxWvZD2sYyrwG1e8Jh%2FSrdDypSHzJ1G%2BgxM6OC2dmuVufRZhZGtdpX%2BRmxzr1jOaFROF%2FavjMJzPH0yDYT%2FBg79ercgg6U9SN0uJuvgAq%2FBkcccUAIW%2FvaIVs1pRJyiduY6W&X-Amz-Signature=54157d46e2fb19be63099a48bd8368908bafb469045a1834ad80636cad9e019c&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663JVPVB7D%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T082936Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEID%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCEfU7OoMBIQXquvrE41lecntucCc7PQXpez%2BakhT%2F0GwIgFXDpmoBlhFnVB2gih5h21d3gTZVmAcvSCBC8dygGrhsqiAQIif%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDIgXw0Srxc7lHmqLvyrcA0ro%2FwdHlbqptoNZjMtv3TiwhkgyF2V9ZnCwXkTEPC9LPIeOanSlvKaklfe9pbW35MywfzucDwXjZENfTC3gYzbjRK9w01WweYjxm8cX6GbcdyfqPZYmli1gqZJE0u2kwYbjvMHj8dw64Loi6H%2B%2BXiduyJzQe36PBS6tGuPqcWUMs2NOAvGgAfjjfYOoUHe8lSwOpYA%2BErvMKU5eo2P4cS6k1bdbTs6lS2%2FfsNwRMqnsEFHx%2Fb0k3EaXyrXbKfZuQQ4fU9xrEFx%2B0jD92TZnJeUsFfKjO%2Fzt6fkSk1JQJo3sUEsorq5J%2BndziQYZm9gNJ1YqN2AzCoTfDaM0%2Fea1bwEl89m%2FojzVzr7AfYSruRiEDIK6Qk5U21vKX8ZRQE9YyHM1RsP06mZhGzs7dEq7LYUjE%2FbF4hE7wFYGy%2FfCJN5luWX78YFHh2FBgCuWzTgY%2Fo83fKKOLZZfH3kA3NmANOs9m9H0VgklDisNrDIgBC0usWkLFOgLZpfhANfnWgcMRPwPFZvSww3GaPtv8Wjw%2FYqibrzt%2B%2BuVhoibgTRjNc0r8%2B7TucoJQbCQPfsJ5ArJvtcG9YdF0S%2BH%2BRw66Vg%2FukRan67LGNikhfmKknve0Zw5qEWndm4ecBNIYjW1MJ%2FI57wGOqUBbngL1tQVbN%2FotPZRd%2BBf9nZT63hfiPsMrHIhA%2FIHFQryY0nkprHPjb7piGz9H%2BWNOhmzxvgIjbfeBzIYu0KTvXlx8TgW9aWMRPiK6cp9hjcyRoCRp7VkXo4tZ0i%2Fj1mHQAGWBZS6Om6%2BxZVLHx58SGlToYy6WGiKMlKz1%2F2I7rJnuXNuCVp85GjNBLBlpxCI0RbZbrrXMss6Y3emRQCitjnI8c2j&X-Amz-Signature=688dbf8b5b70fa460047aacc8f246923e53f5accf1218b52fe75195a74c9466f&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667JN5XKYJ%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T082934Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIFnXAJwjz1mr%2B%2BEnnpTB11EKANHBNuhTEE%2Fa7aX8xET4AiA1JBpx5EktugHzU64zxE7XCGE03rLCCdkZ5XAxiDdX7yqIBAiJ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMmdFvkvhqKSdnYYd7KtwD6yfkz75oMHNZtfUBDxf9tf3jQ%2BNtSulhbRJUWIRAYrLQzoP2Whxr0rqGf%2BO3P3aNFvEHHOJCzVk0QUdxdz8Whv5OPw7LsbBYKLob7i0whBZZYSFfxgLT1G2TzjAuKPLRBuCWHBnO62KpmsGdAz1xhgIIITcLClmiO0TPJFgJrxBH6kswHgZn7vFSAEpVSlkhcAptxXblXyqxDqLLS5WUP7jMhEg4ZjhsLCyRBYEB9va0A4fji0ATrBn4ZTBtmKHtP5Y3wCM%2FODL%2Bq%2BAdBa0RTW3vdiNl7w57UK8ufO5Gchw2G0eo6rZ6SqE1t6KNfy4rlvUhQp%2F8KHpKI3l%2B5m2ztNUk1PE1JN9tfMLXfwuqu1OAzfEMdIjBM4HaddviDSFmd9p%2BM2QGVlZ%2FLAVesr5p%2BbPZv5VzhBzfbrc9mU%2FgyCvN9ttRAdCgEy9PucInnFRsuvRPWgBQA%2B2UnavcOOmcDO92MrVUWz2wDt%2FF7GllP2rwN2mC%2FTjJc0SSSWV2OeDxbnTSTgDO7AiIVWOmqSGpgCHy%2F6v8FhznFyLZ6MuolasR8MhFGIG6j8qtwaWdgf%2BGctiW9v40zfhhBjjYrEBwqBoz0EdPzG6iGoYx3DDXRCf7WWeEByo%2B6Xo%2BTu0w08nnvAY6pgEt%2F1CuBDikqNXbusS5L0VGg%2Fa3R371YZrP6rt1bY5ythJarbOhRjbkGOUmhFeFDGguU95eNaLzvEWO%2FoWEWmfSnp%2FpUc7tvIEXuWdeuvE1st8EA1ldhwcdNrtA5Isa5WLYCzdy2I8Ov%2FP9yabge8QiVBGidCPL0LDlDW5HJ%2BPWTOlmkpiIVH3%2FTmlGcD%2F7gStYSmCCRHWQpYYBhVMKQKahCF5jOOUH&X-Amz-Signature=85d3efa86c4b7bc46e4e59bd8ced93ac1fae7454fb52c32e5ca0e8f9171d72b4&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667JN5XKYJ%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T082934Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIFnXAJwjz1mr%2B%2BEnnpTB11EKANHBNuhTEE%2Fa7aX8xET4AiA1JBpx5EktugHzU64zxE7XCGE03rLCCdkZ5XAxiDdX7yqIBAiJ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMmdFvkvhqKSdnYYd7KtwD6yfkz75oMHNZtfUBDxf9tf3jQ%2BNtSulhbRJUWIRAYrLQzoP2Whxr0rqGf%2BO3P3aNFvEHHOJCzVk0QUdxdz8Whv5OPw7LsbBYKLob7i0whBZZYSFfxgLT1G2TzjAuKPLRBuCWHBnO62KpmsGdAz1xhgIIITcLClmiO0TPJFgJrxBH6kswHgZn7vFSAEpVSlkhcAptxXblXyqxDqLLS5WUP7jMhEg4ZjhsLCyRBYEB9va0A4fji0ATrBn4ZTBtmKHtP5Y3wCM%2FODL%2Bq%2BAdBa0RTW3vdiNl7w57UK8ufO5Gchw2G0eo6rZ6SqE1t6KNfy4rlvUhQp%2F8KHpKI3l%2B5m2ztNUk1PE1JN9tfMLXfwuqu1OAzfEMdIjBM4HaddviDSFmd9p%2BM2QGVlZ%2FLAVesr5p%2BbPZv5VzhBzfbrc9mU%2FgyCvN9ttRAdCgEy9PucInnFRsuvRPWgBQA%2B2UnavcOOmcDO92MrVUWz2wDt%2FF7GllP2rwN2mC%2FTjJc0SSSWV2OeDxbnTSTgDO7AiIVWOmqSGpgCHy%2F6v8FhznFyLZ6MuolasR8MhFGIG6j8qtwaWdgf%2BGctiW9v40zfhhBjjYrEBwqBoz0EdPzG6iGoYx3DDXRCf7WWeEByo%2B6Xo%2BTu0w08nnvAY6pgEt%2F1CuBDikqNXbusS5L0VGg%2Fa3R371YZrP6rt1bY5ythJarbOhRjbkGOUmhFeFDGguU95eNaLzvEWO%2FoWEWmfSnp%2FpUc7tvIEXuWdeuvE1st8EA1ldhwcdNrtA5Isa5WLYCzdy2I8Ov%2FP9yabge8QiVBGidCPL0LDlDW5HJ%2BPWTOlmkpiIVH3%2FTmlGcD%2F7gStYSmCCRHWQpYYBhVMKQKahCF5jOOUH&X-Amz-Signature=7d0e2efe2ab476eb511d073c253e6d6ecd620c5f0acd9850159cd661464bfb13&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667JN5XKYJ%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T082934Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIFnXAJwjz1mr%2B%2BEnnpTB11EKANHBNuhTEE%2Fa7aX8xET4AiA1JBpx5EktugHzU64zxE7XCGE03rLCCdkZ5XAxiDdX7yqIBAiJ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMmdFvkvhqKSdnYYd7KtwD6yfkz75oMHNZtfUBDxf9tf3jQ%2BNtSulhbRJUWIRAYrLQzoP2Whxr0rqGf%2BO3P3aNFvEHHOJCzVk0QUdxdz8Whv5OPw7LsbBYKLob7i0whBZZYSFfxgLT1G2TzjAuKPLRBuCWHBnO62KpmsGdAz1xhgIIITcLClmiO0TPJFgJrxBH6kswHgZn7vFSAEpVSlkhcAptxXblXyqxDqLLS5WUP7jMhEg4ZjhsLCyRBYEB9va0A4fji0ATrBn4ZTBtmKHtP5Y3wCM%2FODL%2Bq%2BAdBa0RTW3vdiNl7w57UK8ufO5Gchw2G0eo6rZ6SqE1t6KNfy4rlvUhQp%2F8KHpKI3l%2B5m2ztNUk1PE1JN9tfMLXfwuqu1OAzfEMdIjBM4HaddviDSFmd9p%2BM2QGVlZ%2FLAVesr5p%2BbPZv5VzhBzfbrc9mU%2FgyCvN9ttRAdCgEy9PucInnFRsuvRPWgBQA%2B2UnavcOOmcDO92MrVUWz2wDt%2FF7GllP2rwN2mC%2FTjJc0SSSWV2OeDxbnTSTgDO7AiIVWOmqSGpgCHy%2F6v8FhznFyLZ6MuolasR8MhFGIG6j8qtwaWdgf%2BGctiW9v40zfhhBjjYrEBwqBoz0EdPzG6iGoYx3DDXRCf7WWeEByo%2B6Xo%2BTu0w08nnvAY6pgEt%2F1CuBDikqNXbusS5L0VGg%2Fa3R371YZrP6rt1bY5ythJarbOhRjbkGOUmhFeFDGguU95eNaLzvEWO%2FoWEWmfSnp%2FpUc7tvIEXuWdeuvE1st8EA1ldhwcdNrtA5Isa5WLYCzdy2I8Ov%2FP9yabge8QiVBGidCPL0LDlDW5HJ%2BPWTOlmkpiIVH3%2FTmlGcD%2F7gStYSmCCRHWQpYYBhVMKQKahCF5jOOUH&X-Amz-Signature=9f468744cdb453dda19d7dbffe8f1c683eb5f71c62909d8ca22bf1b035650eee&X-Amz-SignedHeaders=host&x-id=GetObject)


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

