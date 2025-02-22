---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4664E2SHWSK%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250222T191756Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIHb2YZSts%2Bc7j9Psa\
  PjQkp%2F1ruKr3%2FIDv%2FKUNSnmWC8DAiEA72oOVehvvyprOpK%2FqczPuKD4%2FOLDYhYrmcpQ\
  iVid9bQqiAQI8v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDF5bPTR3y\
  jm5E0Ou3yrcA%2FV%2FgXmv%2BW8YNvnkFM%2B0o4ldSLA%2Bvoy%2B7qWQdpYZZjJfZQhYeo1XAE\
  PGg6MbDDKLwLb4iR0oEkevRA2q1BiCt1uLb5mZpIew3R05QS2D9sg0OYbO7b0CR1xV%2Fatu%2Bj1\
  b%2FN2MHCu%2FhPbnHSh1qTq4ypUewt78LNeK%2BfTdTUZKLMCkGA0KKkfUAGqiWntjrusULCqcl%\
  2BnceB9O4KTybYqztm4kjlTKNUhL%2FZJv3h8W1ziAh7E11zkys9pGUNikb6IabJ8zymgaOUdrG58\
  B92DtsKudWwsrT4Lk6IxaQvYSduJmAjQ7b%2BV1GlrXG2W1QN%2BFPIgg9yj578qjcHoD7sKz0E6x\
  a5vNWPZkKR3zhKEA2lW3Yj6bEFe%2BRNq44DmMx7if5EIL5I3CbKE879M4oVcGkZaDWOtU8x6kCq%\
  2Bab%2FloMHh%2BQO5%2BRnVd6%2BZ%2FANOWlzWH9aR4CRN%2FCc2Qnx9GWsXJGlH43U5kNn6ZWS\
  EfmG%2F1w%2BTuNEIz6W%2BmkBYK%2BZpIdUBDwfZ1H14vr8MztafdJGk9MCMt5xEkUmlj7RkdLxj\
  cEx6%2BtLlKoXu%2Bh2IGWI%2ByisZ0bOyf8LAqsYydiX4E%2BJ3N%2FE1KND%2Bdf5M8NH86Dgf1\
  yDvJpjYfxBp77v0yx02VMLCF6L0GOqUBcAuU70NmydMrsAO1PbkQkQcglpWgYyhWeHh8BotBGWyA8\
  MRLQkZFnkAMtPuaNpBLREw24GGQSvnmWWdUe4zHhUEoqh5hG%2Fg%2FTCQ46t0V3R%2B4Pi06hcoO\
  xCKdZXQlbcFxGzeKjcbche43Ba7fgecZqGJM9f5LhrDfSzKvkbsB4c1oXIrAPw%2BRRhQY3b3pWjJ\
  6Uo0vVQ1q1b8aAnntMFuQBjEp5xAn&X-Amz-Signature=206462d8c6ddd728828a6a3a513dc5d\
  24a628147010d5e21dc1361c63c9519a4&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466WMOBXJ5S%2F20250222%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250222T191639Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQ\
        CIHeMPv6scw7hpZ9uG0Xcc28jGZSjwHaHePcgndmwZ41tAiBJ2Af7ZlpgvjuugFodOsVU3E\
        siK%2Fv2pGytpACjZjMeMCqIBAjy%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQ\
        yMzE4MzgwNSIMGON0R8E9AQFFfwwJKtwDWlybEWo%2FolnPfVqJIhlrqQbuuageeZqexL69\
        YnGU%2B38qlsy0L3tb2ZMVnE5fbWxqNns%2BW7CrgUZ%2FY9kYexV4co1tyfh2vTy4vc3kT\
        PjIICftCOTSNPshO76jHQc21birWkk2PTGq2r02hM8VxqyqJVAwJ5mQUzZWIoRukV%2FpC5\
        vbt4MI5szAM2Q1jXSkzC60VPgpiQGOC0u%2FBXEu8AqNMEgB5MdBbJv7lYfj%2BQQdXSu46\
        JBefSYeeO5OPQ5ZWp8CC58labHWVM0N2GO%2BArSz%2BSAf%2BcM1vUWhFrAhIpPJ%2FppY\
        eBTehmabU0fd9WnV4tFfFYte09eFHTmsX%2FrG6%2FoNCANtSBcj8mGj29NkBl%2FBnmh39\
        Ewmj%2Bu0MGlN113%2BeVpGXZKyQb%2BDIy6UyInIcVFVq5vQofjZss%2BSD1cUN5XHPLbc\
        4VE8mwogAUlC1UnzPJ5tjoNUJwLbaZ1a9qjEyg60b8xV%2BJjgJaqC8FiI6ABwCVj59whzC\
        MKkW69r6pk4SD%2Brb9JCnbY7hJlir%2BWt5ecxa%2FacOHuTyV8BkBX4uGmP2pi%2FQStD\
        PokEPE1ZxAr2Xhcph5bL25N2sw4%2BC9aQpNclCmXrwMNXsyNp21dl0ghnFLZgwU2QONzyB\
        Udcbx8w3%2FvnvQY6pgFK44Ay3%2F8LWyhLOzTna7KZ%2FZHND%2BHqxRx3fFn4jepUJ7WL\
        6Iy%2B6mBi9tBRHhG2n4fD7mgJQQg%2B7Z6LulYtIwn%2BJK82tzUIskkCBbEmc6QgGG61V\
        zoiM0wzgMwbPkLtOD4ePNOZpSkraSMSdINuLMnL8nToDYd%2Bv1gJZNNwRjc7MiDsKq%2BU\
        ijgqcbJtVAuALh%2FJcNcMIe9ADUj0HbhpEipKz8ss3h8t&X-Amz-Signature=2b160dd1\
        ea10e06dacef917af5917b975555ab8b791f732d9aac05b890314158&X-Amz-SignedHe\
        aders=host&x-id=GetObject"
      expiry_time: "2025-02-22T20:16:39.805Z"
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
UPDATE_TIME: "2025-02-22T19:18:05.473Z"
EXPIRY_TIME: "2025-02-22T20:17:52.722Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663Q2WJH7T%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T191752Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD8pS7Z5702%2FnZSLyXcb92aZDcKioTgh96fmkVMpPs5dwIhAJiX4vwqL0MMgXnOtfeT8cJ4vdC3yA6oUav9jBviYfLFKogECPD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwBNuuMBdzu4ECFGZoq3AO8uX0o8g5n1YfKiJkEChDgWuNSUkKXT6un2y3bVJxNBJt6K3tO7kwA4Sn9RU6cfSTqKa9Ka0a41eLv8JUg6%2FsFWMIeulp4v9wZ47aWlAUaFyDHNjoRKS%2BHADp03GK798kCU1jXGy%2B%2BmxjSuWEe%2FkpYe%2FV9mPNOMweUw4QOuyhqBWLntkBfaGBNyVIThUfgcH5tBEZh7UHGqbx8F29Li2huvVlnw6yFK8i%2BHVoH%2B5lWHcbUsj1G9%2BVM5ATwGM7DJyr%2BD%2B8lPLWqjhHWn4DGX8h2GLnzyHc6MrkMvcV05FH%2BR9kNOTcbEAMYFNQqBviiPHkn0LO6dWJeHamKmkI4ZnuJBCGvd%2F8tSChby90Xv90HE%2BP5Sf90b2ogkAnSgQvZxTForVUJIW5VALiwuX3kKB8GmCEcP7wyftVlaZ4Q3F9by8IdaZ94hNijVEVc%2BUjv9ACtNYlALr3c%2BsNMhz7%2BwEovUPiQ88o7xL%2B08Q9IwNguraAigQaBpTwaLc3TUTQTutmafaQPYpn78ZpNKqT2HewyyR84zk41B3fRNCj1bUxTth1BZrJVz0%2FDuP1GzSjUy8rTBXWqguAFYkzNaPh0vzvJeXI7%2FdTWWtHph2n65iMsZTJy2W%2FqER7JKWODIDDPxue9BjqkARkNX2cWeUcjTKSEBF6vwzHkrI7834fsKDqtLHq3z3GsaBGWEwSEuxZq6Kg%2B0zl5tBESImYEEe3V%2B0smYzGWovxJoZUqjVff13Q6QgtHqVujy3ZJD4p2SfUBWkco1nirCj%2Bs58B1hFNM7hUPbvvpuwgQwwfwuEpUBXL9RVf7hw5ly%2F5Zp64Nt5B0xUvw06aT3YTxgBlmyzGSO6hZGB7dGpney6wz&X-Amz-Signature=d78e51cff7db38d98da702b202eb5ff5769bb1d2b8f93256ddd1189804d1875a&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663Q2WJH7T%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T191752Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD8pS7Z5702%2FnZSLyXcb92aZDcKioTgh96fmkVMpPs5dwIhAJiX4vwqL0MMgXnOtfeT8cJ4vdC3yA6oUav9jBviYfLFKogECPD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwBNuuMBdzu4ECFGZoq3AO8uX0o8g5n1YfKiJkEChDgWuNSUkKXT6un2y3bVJxNBJt6K3tO7kwA4Sn9RU6cfSTqKa9Ka0a41eLv8JUg6%2FsFWMIeulp4v9wZ47aWlAUaFyDHNjoRKS%2BHADp03GK798kCU1jXGy%2B%2BmxjSuWEe%2FkpYe%2FV9mPNOMweUw4QOuyhqBWLntkBfaGBNyVIThUfgcH5tBEZh7UHGqbx8F29Li2huvVlnw6yFK8i%2BHVoH%2B5lWHcbUsj1G9%2BVM5ATwGM7DJyr%2BD%2B8lPLWqjhHWn4DGX8h2GLnzyHc6MrkMvcV05FH%2BR9kNOTcbEAMYFNQqBviiPHkn0LO6dWJeHamKmkI4ZnuJBCGvd%2F8tSChby90Xv90HE%2BP5Sf90b2ogkAnSgQvZxTForVUJIW5VALiwuX3kKB8GmCEcP7wyftVlaZ4Q3F9by8IdaZ94hNijVEVc%2BUjv9ACtNYlALr3c%2BsNMhz7%2BwEovUPiQ88o7xL%2B08Q9IwNguraAigQaBpTwaLc3TUTQTutmafaQPYpn78ZpNKqT2HewyyR84zk41B3fRNCj1bUxTth1BZrJVz0%2FDuP1GzSjUy8rTBXWqguAFYkzNaPh0vzvJeXI7%2FdTWWtHph2n65iMsZTJy2W%2FqER7JKWODIDDPxue9BjqkARkNX2cWeUcjTKSEBF6vwzHkrI7834fsKDqtLHq3z3GsaBGWEwSEuxZq6Kg%2B0zl5tBESImYEEe3V%2B0smYzGWovxJoZUqjVff13Q6QgtHqVujy3ZJD4p2SfUBWkco1nirCj%2Bs58B1hFNM7hUPbvvpuwgQwwfwuEpUBXL9RVf7hw5ly%2F5Zp64Nt5B0xUvw06aT3YTxgBlmyzGSO6hZGB7dGpney6wz&X-Amz-Signature=b0ad9bf5ccb9a47dd720abce3f5eff6cb9f137fe21d2fdca0929915fc7a012af&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663Q2WJH7T%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T191753Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD8pS7Z5702%2FnZSLyXcb92aZDcKioTgh96fmkVMpPs5dwIhAJiX4vwqL0MMgXnOtfeT8cJ4vdC3yA6oUav9jBviYfLFKogECPD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwBNuuMBdzu4ECFGZoq3AO8uX0o8g5n1YfKiJkEChDgWuNSUkKXT6un2y3bVJxNBJt6K3tO7kwA4Sn9RU6cfSTqKa9Ka0a41eLv8JUg6%2FsFWMIeulp4v9wZ47aWlAUaFyDHNjoRKS%2BHADp03GK798kCU1jXGy%2B%2BmxjSuWEe%2FkpYe%2FV9mPNOMweUw4QOuyhqBWLntkBfaGBNyVIThUfgcH5tBEZh7UHGqbx8F29Li2huvVlnw6yFK8i%2BHVoH%2B5lWHcbUsj1G9%2BVM5ATwGM7DJyr%2BD%2B8lPLWqjhHWn4DGX8h2GLnzyHc6MrkMvcV05FH%2BR9kNOTcbEAMYFNQqBviiPHkn0LO6dWJeHamKmkI4ZnuJBCGvd%2F8tSChby90Xv90HE%2BP5Sf90b2ogkAnSgQvZxTForVUJIW5VALiwuX3kKB8GmCEcP7wyftVlaZ4Q3F9by8IdaZ94hNijVEVc%2BUjv9ACtNYlALr3c%2BsNMhz7%2BwEovUPiQ88o7xL%2B08Q9IwNguraAigQaBpTwaLc3TUTQTutmafaQPYpn78ZpNKqT2HewyyR84zk41B3fRNCj1bUxTth1BZrJVz0%2FDuP1GzSjUy8rTBXWqguAFYkzNaPh0vzvJeXI7%2FdTWWtHph2n65iMsZTJy2W%2FqER7JKWODIDDPxue9BjqkARkNX2cWeUcjTKSEBF6vwzHkrI7834fsKDqtLHq3z3GsaBGWEwSEuxZq6Kg%2B0zl5tBESImYEEe3V%2B0smYzGWovxJoZUqjVff13Q6QgtHqVujy3ZJD4p2SfUBWkco1nirCj%2Bs58B1hFNM7hUPbvvpuwgQwwfwuEpUBXL9RVf7hw5ly%2F5Zp64Nt5B0xUvw06aT3YTxgBlmyzGSO6hZGB7dGpney6wz&X-Amz-Signature=7295d09121c37f6e88fa899f2e00e7d1af0679e8e258ad6a3c4e77bb54a91df1&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663Q2WJH7T%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T191752Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD8pS7Z5702%2FnZSLyXcb92aZDcKioTgh96fmkVMpPs5dwIhAJiX4vwqL0MMgXnOtfeT8cJ4vdC3yA6oUav9jBviYfLFKogECPD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwBNuuMBdzu4ECFGZoq3AO8uX0o8g5n1YfKiJkEChDgWuNSUkKXT6un2y3bVJxNBJt6K3tO7kwA4Sn9RU6cfSTqKa9Ka0a41eLv8JUg6%2FsFWMIeulp4v9wZ47aWlAUaFyDHNjoRKS%2BHADp03GK798kCU1jXGy%2B%2BmxjSuWEe%2FkpYe%2FV9mPNOMweUw4QOuyhqBWLntkBfaGBNyVIThUfgcH5tBEZh7UHGqbx8F29Li2huvVlnw6yFK8i%2BHVoH%2B5lWHcbUsj1G9%2BVM5ATwGM7DJyr%2BD%2B8lPLWqjhHWn4DGX8h2GLnzyHc6MrkMvcV05FH%2BR9kNOTcbEAMYFNQqBviiPHkn0LO6dWJeHamKmkI4ZnuJBCGvd%2F8tSChby90Xv90HE%2BP5Sf90b2ogkAnSgQvZxTForVUJIW5VALiwuX3kKB8GmCEcP7wyftVlaZ4Q3F9by8IdaZ94hNijVEVc%2BUjv9ACtNYlALr3c%2BsNMhz7%2BwEovUPiQ88o7xL%2B08Q9IwNguraAigQaBpTwaLc3TUTQTutmafaQPYpn78ZpNKqT2HewyyR84zk41B3fRNCj1bUxTth1BZrJVz0%2FDuP1GzSjUy8rTBXWqguAFYkzNaPh0vzvJeXI7%2FdTWWtHph2n65iMsZTJy2W%2FqER7JKWODIDDPxue9BjqkARkNX2cWeUcjTKSEBF6vwzHkrI7834fsKDqtLHq3z3GsaBGWEwSEuxZq6Kg%2B0zl5tBESImYEEe3V%2B0smYzGWovxJoZUqjVff13Q6QgtHqVujy3ZJD4p2SfUBWkco1nirCj%2Bs58B1hFNM7hUPbvvpuwgQwwfwuEpUBXL9RVf7hw5ly%2F5Zp64Nt5B0xUvw06aT3YTxgBlmyzGSO6hZGB7dGpney6wz&X-Amz-Signature=434071e332139ace72c4ac8b7f5c5afd21ddf0b38048a34f3e7d9ef60630edae&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663Q2WJH7T%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T191752Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD8pS7Z5702%2FnZSLyXcb92aZDcKioTgh96fmkVMpPs5dwIhAJiX4vwqL0MMgXnOtfeT8cJ4vdC3yA6oUav9jBviYfLFKogECPD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwBNuuMBdzu4ECFGZoq3AO8uX0o8g5n1YfKiJkEChDgWuNSUkKXT6un2y3bVJxNBJt6K3tO7kwA4Sn9RU6cfSTqKa9Ka0a41eLv8JUg6%2FsFWMIeulp4v9wZ47aWlAUaFyDHNjoRKS%2BHADp03GK798kCU1jXGy%2B%2BmxjSuWEe%2FkpYe%2FV9mPNOMweUw4QOuyhqBWLntkBfaGBNyVIThUfgcH5tBEZh7UHGqbx8F29Li2huvVlnw6yFK8i%2BHVoH%2B5lWHcbUsj1G9%2BVM5ATwGM7DJyr%2BD%2B8lPLWqjhHWn4DGX8h2GLnzyHc6MrkMvcV05FH%2BR9kNOTcbEAMYFNQqBviiPHkn0LO6dWJeHamKmkI4ZnuJBCGvd%2F8tSChby90Xv90HE%2BP5Sf90b2ogkAnSgQvZxTForVUJIW5VALiwuX3kKB8GmCEcP7wyftVlaZ4Q3F9by8IdaZ94hNijVEVc%2BUjv9ACtNYlALr3c%2BsNMhz7%2BwEovUPiQ88o7xL%2B08Q9IwNguraAigQaBpTwaLc3TUTQTutmafaQPYpn78ZpNKqT2HewyyR84zk41B3fRNCj1bUxTth1BZrJVz0%2FDuP1GzSjUy8rTBXWqguAFYkzNaPh0vzvJeXI7%2FdTWWtHph2n65iMsZTJy2W%2FqER7JKWODIDDPxue9BjqkARkNX2cWeUcjTKSEBF6vwzHkrI7834fsKDqtLHq3z3GsaBGWEwSEuxZq6Kg%2B0zl5tBESImYEEe3V%2B0smYzGWovxJoZUqjVff13Q6QgtHqVujy3ZJD4p2SfUBWkco1nirCj%2Bs58B1hFNM7hUPbvvpuwgQwwfwuEpUBXL9RVf7hw5ly%2F5Zp64Nt5B0xUvw06aT3YTxgBlmyzGSO6hZGB7dGpney6wz&X-Amz-Signature=551abdba55c4c60811c952e7a80c2709d46a73178ce5ff0fc68681a332c2c6d6&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZMJVGQWV%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T191754Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCUBAU1teyQTPeagRROaXe0clV0Uskx9S4RLS7g05XeggIgZDUyUnaqUxNiqV%2FF8Uwtq%2FAGmPSIO74%2BMv6ab2eri0wqiAQI8v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDA1GesUHzTk18U7dPyrcA9r6q8DFXaTJXOv3guGpcw5ycKI8SJOCFy%2F8Tse7DncqPNgjvI814y6kWQAhDv77QuwuFotbgFkWOlIQ5uqfsyiC4NvFfshyHWEj95%2B9b4dKeX%2B1fBxEYDl9hJXlUFCpj90Cd%2FJNnXX77KevJoKGmhgnT2Crur5wNYg5HUKn5S%2F%2BGVE2%2F6FMAs4LM1kRt8hxpe5CJvaG3C1LrUIhGXrraZBUQr6t5gxWkqdml7Is6NEfjQDefzga0BVzbXpSad4Qf7FbQRupySD%2FG0LNfwozkknG3BUpA8GeS3odgOdoVdqn5PYeQ%2F3vt6vj%2B4TuOHiqBV2zVGZbMqhpmiSLkHTLjOzMwCYgmLvy5hwO4RKUz%2FWILWFSlJPTmtQuXvCjNHAPyqqmGlmAUnoYXXKaesa99pFfnrHFqbvu51oFcWSYd5CZNiEULOWZQ19x5ROQUrz%2FFZFBgAHNZNB1ptWXjqFzRZ0%2BjGJyEgsd%2BQ3B50jouOsbY1bEShV8OH08tuGoYMZTxxS12g29e%2FREyswAQQMLyTrLAwUDrWQrj%2B6lqZB9Unb9nhHG7pZbfuKoT0LK8JlQMgqHLKVWzGu82zCyBJR%2BQXMKmJwNRfw%2FgDzWEUxUmtUHN1VYp%2BP7T2yhW0UBMLSN6L0GOqUB6pHOqnbt1eltvqY97uN3Ty8rcCVt7La5hezkbze3xZS4Js7GWl4oJ7ZlVWLDrmv2p2YJxTm0eab%2BhXO9CYBFpjr6uxMlMVKrLkymvDgJWhiaWHcDM1Pc1p%2Baxij35FhSFOWvX3BNt%2FRje6nOCPbMAND%2BlBVkCHnXvcSn7nATA6hdqr3PfUCZSz%2FUTthsAecdqABy1FkLnpOhfBDYJCro74fz%2BEkx&X-Amz-Signature=994bafeee6824d4f3f00d67d637edaefef452ebe0ba00ea259c99ff7b9c84a9c&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46635ZQFM4Q%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T191755Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBnHIPRiH6Tl15nm9GsJp%2FEB7aLcoc5A9Lx2cRn0QQjwAiEAzgZ2Xc0kdajkfS50qt%2FEgfyK4IygGMwEA3MWdy2We08qiAQI8v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGdk4iU%2FbkIF3KX9dircA4sL6zuhnD7vuV3bGX1r5FgqMx99RA6j0OueV3lmemg2nhWNvbbU3JV3h0keTJMo%2FMHo9eqD3CKQ5oaQ%2FCplqSLquf9dMJ49NBtqog6o6LtM%2BIX%2B2CNuH28QkZxwcOM5ZJdmnyhHGAkLQMRB0QZwkMh15y2tqRn2IDJgSnLM2v8hJlD81oUVBxPJSUcXolnUiUQEPaYhLVnHM13Kw1xeKJwAN7Nfoq7oMT2fNiBT2EsU9pMn4flj4wRqOW0nQ%2FZNgGXW2tJfZVgXb33xT%2BjuGp4z0kIfdTBaUrzXqNpEShmuXBwOfWiNzFjEFk9zJwDV26Ucmyqgv%2FltWIzoqwCDaxpYebipHTM7vyXyvfF2BPDh5ZEDgQs33bG6XvpVOmi7gbmjfStsNnhOqlpRQWUMYF4%2BADilYtdjXzBqULdfqYs%2FguYRvTX7uGX5%2FHQEj%2FN9%2FSFLToqO%2BCjWB2oePcqcrcV6b%2FMaCnL%2BeLJO%2FdRfv94jWd3m3H6KKw3AcAtetwSd5XgivTuINH%2B33OrRaoT4OYaPVxfA%2Fg5pIncWvxAgJPRUL2zBtDp4bi3yBfoV2%2Bc4UW9kM6R6YSxU96KczfbfHO8dMft%2BRbDIRD54Ehh0ctVP%2Fc6vPRBE007fLKy8MKCH6L0GOqUBc3kctNUptfn%2FsGYJV237Hamp1wufLcmGWvgSH1sbWLHOn3NIi8tJ6Tnm61%2FXcZYlaODNX81q6kuY7%2BJUP2wyCOPwrbFDTqJ9TL7vxj8zMmSu20nhxOtLC9l%2FMT4bk0Fat%2FF4KqdNMAATXWtXb9cTcBPM%2F16U0EJ9rhms3Grg6DlckmosN1pvO1gezajFJ5GOea98SGXkxzsEWOtKTfFHwNtS8OQx&X-Amz-Signature=b6035433817714a2730937cf13b78358d613ff2b6a4b6ad9782667d38437ffdd&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663Q2WJH7T%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T191753Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD8pS7Z5702%2FnZSLyXcb92aZDcKioTgh96fmkVMpPs5dwIhAJiX4vwqL0MMgXnOtfeT8cJ4vdC3yA6oUav9jBviYfLFKogECPD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwBNuuMBdzu4ECFGZoq3AO8uX0o8g5n1YfKiJkEChDgWuNSUkKXT6un2y3bVJxNBJt6K3tO7kwA4Sn9RU6cfSTqKa9Ka0a41eLv8JUg6%2FsFWMIeulp4v9wZ47aWlAUaFyDHNjoRKS%2BHADp03GK798kCU1jXGy%2B%2BmxjSuWEe%2FkpYe%2FV9mPNOMweUw4QOuyhqBWLntkBfaGBNyVIThUfgcH5tBEZh7UHGqbx8F29Li2huvVlnw6yFK8i%2BHVoH%2B5lWHcbUsj1G9%2BVM5ATwGM7DJyr%2BD%2B8lPLWqjhHWn4DGX8h2GLnzyHc6MrkMvcV05FH%2BR9kNOTcbEAMYFNQqBviiPHkn0LO6dWJeHamKmkI4ZnuJBCGvd%2F8tSChby90Xv90HE%2BP5Sf90b2ogkAnSgQvZxTForVUJIW5VALiwuX3kKB8GmCEcP7wyftVlaZ4Q3F9by8IdaZ94hNijVEVc%2BUjv9ACtNYlALr3c%2BsNMhz7%2BwEovUPiQ88o7xL%2B08Q9IwNguraAigQaBpTwaLc3TUTQTutmafaQPYpn78ZpNKqT2HewyyR84zk41B3fRNCj1bUxTth1BZrJVz0%2FDuP1GzSjUy8rTBXWqguAFYkzNaPh0vzvJeXI7%2FdTWWtHph2n65iMsZTJy2W%2FqER7JKWODIDDPxue9BjqkARkNX2cWeUcjTKSEBF6vwzHkrI7834fsKDqtLHq3z3GsaBGWEwSEuxZq6Kg%2B0zl5tBESImYEEe3V%2B0smYzGWovxJoZUqjVff13Q6QgtHqVujy3ZJD4p2SfUBWkco1nirCj%2Bs58B1hFNM7hUPbvvpuwgQwwfwuEpUBXL9RVf7hw5ly%2F5Zp64Nt5B0xUvw06aT3YTxgBlmyzGSO6hZGB7dGpney6wz&X-Amz-Signature=4893a7173f157a9524896ae3d57961eb683dc665b61179e142db0995e049f097&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663Q2WJH7T%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T191753Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD8pS7Z5702%2FnZSLyXcb92aZDcKioTgh96fmkVMpPs5dwIhAJiX4vwqL0MMgXnOtfeT8cJ4vdC3yA6oUav9jBviYfLFKogECPD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwBNuuMBdzu4ECFGZoq3AO8uX0o8g5n1YfKiJkEChDgWuNSUkKXT6un2y3bVJxNBJt6K3tO7kwA4Sn9RU6cfSTqKa9Ka0a41eLv8JUg6%2FsFWMIeulp4v9wZ47aWlAUaFyDHNjoRKS%2BHADp03GK798kCU1jXGy%2B%2BmxjSuWEe%2FkpYe%2FV9mPNOMweUw4QOuyhqBWLntkBfaGBNyVIThUfgcH5tBEZh7UHGqbx8F29Li2huvVlnw6yFK8i%2BHVoH%2B5lWHcbUsj1G9%2BVM5ATwGM7DJyr%2BD%2B8lPLWqjhHWn4DGX8h2GLnzyHc6MrkMvcV05FH%2BR9kNOTcbEAMYFNQqBviiPHkn0LO6dWJeHamKmkI4ZnuJBCGvd%2F8tSChby90Xv90HE%2BP5Sf90b2ogkAnSgQvZxTForVUJIW5VALiwuX3kKB8GmCEcP7wyftVlaZ4Q3F9by8IdaZ94hNijVEVc%2BUjv9ACtNYlALr3c%2BsNMhz7%2BwEovUPiQ88o7xL%2B08Q9IwNguraAigQaBpTwaLc3TUTQTutmafaQPYpn78ZpNKqT2HewyyR84zk41B3fRNCj1bUxTth1BZrJVz0%2FDuP1GzSjUy8rTBXWqguAFYkzNaPh0vzvJeXI7%2FdTWWtHph2n65iMsZTJy2W%2FqER7JKWODIDDPxue9BjqkARkNX2cWeUcjTKSEBF6vwzHkrI7834fsKDqtLHq3z3GsaBGWEwSEuxZq6Kg%2B0zl5tBESImYEEe3V%2B0smYzGWovxJoZUqjVff13Q6QgtHqVujy3ZJD4p2SfUBWkco1nirCj%2Bs58B1hFNM7hUPbvvpuwgQwwfwuEpUBXL9RVf7hw5ly%2F5Zp64Nt5B0xUvw06aT3YTxgBlmyzGSO6hZGB7dGpney6wz&X-Amz-Signature=095f8337cc2f1d199f78f9dfef9737fcdc210f0349e45ddd8a90507f986d7beb&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663Q2WJH7T%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T191753Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD8pS7Z5702%2FnZSLyXcb92aZDcKioTgh96fmkVMpPs5dwIhAJiX4vwqL0MMgXnOtfeT8cJ4vdC3yA6oUav9jBviYfLFKogECPD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwBNuuMBdzu4ECFGZoq3AO8uX0o8g5n1YfKiJkEChDgWuNSUkKXT6un2y3bVJxNBJt6K3tO7kwA4Sn9RU6cfSTqKa9Ka0a41eLv8JUg6%2FsFWMIeulp4v9wZ47aWlAUaFyDHNjoRKS%2BHADp03GK798kCU1jXGy%2B%2BmxjSuWEe%2FkpYe%2FV9mPNOMweUw4QOuyhqBWLntkBfaGBNyVIThUfgcH5tBEZh7UHGqbx8F29Li2huvVlnw6yFK8i%2BHVoH%2B5lWHcbUsj1G9%2BVM5ATwGM7DJyr%2BD%2B8lPLWqjhHWn4DGX8h2GLnzyHc6MrkMvcV05FH%2BR9kNOTcbEAMYFNQqBviiPHkn0LO6dWJeHamKmkI4ZnuJBCGvd%2F8tSChby90Xv90HE%2BP5Sf90b2ogkAnSgQvZxTForVUJIW5VALiwuX3kKB8GmCEcP7wyftVlaZ4Q3F9by8IdaZ94hNijVEVc%2BUjv9ACtNYlALr3c%2BsNMhz7%2BwEovUPiQ88o7xL%2B08Q9IwNguraAigQaBpTwaLc3TUTQTutmafaQPYpn78ZpNKqT2HewyyR84zk41B3fRNCj1bUxTth1BZrJVz0%2FDuP1GzSjUy8rTBXWqguAFYkzNaPh0vzvJeXI7%2FdTWWtHph2n65iMsZTJy2W%2FqER7JKWODIDDPxue9BjqkARkNX2cWeUcjTKSEBF6vwzHkrI7834fsKDqtLHq3z3GsaBGWEwSEuxZq6Kg%2B0zl5tBESImYEEe3V%2B0smYzGWovxJoZUqjVff13Q6QgtHqVujy3ZJD4p2SfUBWkco1nirCj%2Bs58B1hFNM7hUPbvvpuwgQwwfwuEpUBXL9RVf7hw5ly%2F5Zp64Nt5B0xUvw06aT3YTxgBlmyzGSO6hZGB7dGpney6wz&X-Amz-Signature=d3923745a048d8493d66a746fea2803493f74602ae4649a5fe72b6acf1dbcce7&X-Amz-SignedHeaders=host&x-id=GetObject)


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

