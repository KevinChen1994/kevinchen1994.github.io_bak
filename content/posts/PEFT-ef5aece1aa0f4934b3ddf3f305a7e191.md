---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4664MBTOWIO%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250214T142229Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEAUaCXVzLXdlc3QtMiJGMEQCIE1%2FMcHDtMwZq%2BkqSQsJdRtwGoYmC18AVYCLDAoFyZgGAiA\
  gL%2BoxNv5Ggo65eF%2FA3c4y7vlKMyct7e8pnVRoZd7GeCr%2FAwgtEAAaDDYzNzQyMzE4MzgwNS\
  IMzT4hcXhzwRO4dxNpKtwDQuoaB5xloYpwG3z3v1wEXyIv7b2SzYunZayZLSzWsNxP5M1m5YgfvBy\
  S8zwJOIfz7qt1uLWGGa0%2FKTI00311r06da%2F3uVwO%2FIs7vabML5xqBH1RkEtFKq%2FKvX4xx\
  Pv06rCRt2GXCLmGBqMUWe0zM31iTugCM0ehpPvaWQMTj25u0774xSYTnPGo34hgELSbVq6Ua1hC0e\
  nvdhBYhYf5fXgdxWopNv4Mbf1GwwUgs98DJgL6vPxUg95LMNpWelI031ojFVzZ64oZ3SXfPNlBXkF\
  wg%2FkJ%2FKwMAY5zIncfVt754VX9qOgDwrdL%2FE6WqSBztzw%2F%2BohZKs6eZ15ZNK%2Fdpfhy\
  Kfqpc1Jz85gM1TyScJt8PyigP0m8SnURRAov8VMqDfL6pcZXqwqbVgAOTYOCv0q7Tr9mx47KZNoVP\
  dXVxsTKRHC%2FTamzQHDNEvCeRapZMkF86Bw%2BA0ILIxs7PHwK6cXRPD0qihA8bGs%2BKpbR%2BG\
  Uc3V6f3jW2p9%2F8Or2qizdIK7DQal%2FSZWhoxq4w5OddmdrM8RoNTrZ3c%2ByGj%2BUAfOhZCgZ\
  VLgyqQ0JmHwpJhxIuVhDtaN4QQ2ucas%2BPmkhvHPEi3wdQUL7GL4GnV0B7zIfY2JV3Mn4azkFeh7\
  9sw1uq8vQY6pgEmwwWr76iSvUSt6Ye2phJpsHmSzmmFmTr0ZYkUCFyZmr0Ens0%2Bpv%2BoE4kNgR\
  EbvjxhcnHNrjfDrJzbFehpV0%2F0rdMv8QzsRDjkcISjgNTJ3UDrFgJ981fScE12rEuS%2FrPd0zw\
  DuIVIXxrY%2BEF82uTQn6DXT4OvMfPwk4i4qlydkflZCkhYUTIneqtnwYLJjtLBe2YbKPoLnaRE5i\
  illaWCAMMXJMBO&X-Amz-Signature=ae38a3f2c44b25c5e490a03667bb2dcb90763e96eeedbe\
  3671ced2ea0b91e62f&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466SQUE3YIP%2F20250214%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250214T142054Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEAUaCXVzLXdlc3QtMiJGMEQCIBBXs31TV%2BvdRvpiVR1tqQeEdnGbb\
        UNrmUXsvlp%2BSnPuAiBB4JsE8kzldwINU2Mp4vA45s55b1OmyO5WPcmKX0o9cir%2FAwgt\
        EAAaDDYzNzQyMzE4MzgwNSIMejtGi3qt7ISTXaFCKtwDTeoqSIKZvqyUAce1IfxBjzpUjrD\
        FggfrkItNUZhTtJnBIqXcTPbGOyI%2F22bj1v1bL8Hwj5UDWPVMa3Tn6iWP4wJE3DGS5gYL\
        cFoTas3uWDoQ8JhuxmQOS83oZcGLTmfyAEVEr%2Bv50dtU0HCcQayJlaW9OzNKCv3kbcokd\
        Jg8HYXB4y7sVOv5ECChPAPTZUIv8VslgYSSX5dgPZDET3E1uf0Q61Sv7lrYlTcx7XHqT3bB\
        EzChPkLdMwgsWhvRJBgvUIQI06op6NLtivWVF84Q%2BIo8OrUGR4eIwTVRPHDszPKn0C33m\
        g1fTU9pBG8%2F5X%2FdT4l4fStEATOTShGWZYwyXtAetqf7D4FAKQTHs1r2l6blS%2FpjTk\
        vvDsp077YVZPnxf%2Fvc%2BpRsraIYcBoF5VpJxoq1GBjXN4EfrHCJmcfmWStIGX2vJ4jMg\
        ksaq4SCvJ%2B42MKr%2FnngvC9ZmQwOwMzRYgagdk5WdPI6wOXrRvDsOVoKK49Omc9635tB\
        3zmNZgXRpjbTr5OxtmVUIfZI1i5ioiMugOrDOvi%2FQkMZEo%2BZO%2BCAJEg2ltzHvoOqo\
        cgTrPpAqRcvch9%2FOQ2oDSkpvCMWL%2BzR9f4lpyJ7LCQCvRFtvuNPTsfUx7m5%2FsWi%2\
        BkUwieq8vQY6pgEKUiRHdmi3MOHMZ17wCPPwJzGt4zd7L%2BNtR2QtTZQtz6UX60CZwxg%2\
        FCYUvS5jbzgZjV2fsw6dY5WleUB8IOpXf54LvRJX66XinBc6RX9bT9Ygc5RCHijs9YVeKDg\
        IBQrP4gOpVOr%2FGXBTXFZghPAkJDQJSaAWq47AQDRXFqBSTUe10w1L6vkMW7E%2BI77SeK\
        EiYXDMP8wyuLPSF5obqyEhk2%2Bnd%2BDwY&X-Amz-Signature=9611492e1714297d9ba\
        86c084b3fe168bfe90ff79d56eab0d0360ff4a831315d&X-Amz-SignedHeaders=host&\
        x-id=GetObject"
      expiry_time: "2025-02-14T15:20:54.830Z"
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
UPDATE_TIME: "2025-02-14T14:22:37.189Z"
EXPIRY_TIME: "2025-02-14T15:22:24.749Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663HIRVW2H%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T142225Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAUaCXVzLXdlc3QtMiJIMEYCIQCMcC2FQminRpoPs78%2Fu3joO9mk4nh%2FqSMFYL%2F%2B%2BBaIXQIhANLDk9ymjGTUlSMU37KaCKZNtE04t%2B8OOmE2Zm%2FmJpTYKv8DCC0QABoMNjM3NDIzMTgzODA1IgwzJm5SVmmpLHVKSE4q3AO8ZlT%2FXxMHdPcRx1v8qs%2FC59lJYzMt%2FHowdMMNRDm1O6tANtS1f56o%2FNE9LpHJERjEdUKorSc2Qrp73mG6oxW9w%2BVvAuTXBXz4YNheUD5Pt7ArXPELG24VkRuUNOhm9PV549YZysSbRcPK84yDSfGg0fYHKNmok9cjvMwWEcew1%2BGJ%2FN%2FYljzpzw16e9aBy3%2B4hOUvhHEv55bQ97otHIWGTrM839da0GwNcWnk%2BmWSQcLGwbna2Gc7zGyVh8odeAG9xDhX96Rz%2FrXdVNZzZLuctHHpQHFpqPMe5%2FA184X7PIuOrBFi3U7zuqe3lC3fvGyFQ%2FGCxmUGXfdS8cZTC3WkaFg6YppU%2B9hrhhd59SHVvD%2FqaroH4Ad%2BuSM14HecBFCuyj3BH2gV6RgFtplWn0nuHuiGLmAD2ly7Ger3YT9jeg3iLAPDg7HRv9jyf5XQ8ow6KDk2kWdTCE8FctNDpS9HG%2FfCV9931byCjvbgMsHGJ7otqOZ6e6IuI5afsBtC75rgnNtYZqO04we4YY5w%2BpSc9GZyJD%2FKiRUeA9stph8o0e%2Be4ldZQyfR3NpnSPkRajkaYPjf6jDGpHlHSLiB3CkUoO5q1RU07UJ3n%2FEJ7gGB9pOw4p%2FN6mJybzRe1DDq6ry9BjqkATgiZ4WQQT5ve2cWhznVzWivMS36Kp2Pt1JgAoNAHchg0bFeYiAnO%2FPTZCKtPiXu3owdEVKdnpA2IojTHO%2B1kzUZsJNqyysxwipZStT8p1BHxj5n0owvZVWt%2FLJGVkEgviaSIXXNvuXcQ8Zlgf6QLtcjVxGcMertPYnT4V99ZlrrmgPchPvWPo73rflvykupk9xF2XEPOmCR%2Bneh%2B2j2Gr1LkQl8&X-Amz-Signature=5aec6eab675ebcfa31c6602e0c6bb5b2e43df46e728de4dee54c3fe84db05e9d&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663HIRVW2H%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T142225Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAUaCXVzLXdlc3QtMiJIMEYCIQCMcC2FQminRpoPs78%2Fu3joO9mk4nh%2FqSMFYL%2F%2B%2BBaIXQIhANLDk9ymjGTUlSMU37KaCKZNtE04t%2B8OOmE2Zm%2FmJpTYKv8DCC0QABoMNjM3NDIzMTgzODA1IgwzJm5SVmmpLHVKSE4q3AO8ZlT%2FXxMHdPcRx1v8qs%2FC59lJYzMt%2FHowdMMNRDm1O6tANtS1f56o%2FNE9LpHJERjEdUKorSc2Qrp73mG6oxW9w%2BVvAuTXBXz4YNheUD5Pt7ArXPELG24VkRuUNOhm9PV549YZysSbRcPK84yDSfGg0fYHKNmok9cjvMwWEcew1%2BGJ%2FN%2FYljzpzw16e9aBy3%2B4hOUvhHEv55bQ97otHIWGTrM839da0GwNcWnk%2BmWSQcLGwbna2Gc7zGyVh8odeAG9xDhX96Rz%2FrXdVNZzZLuctHHpQHFpqPMe5%2FA184X7PIuOrBFi3U7zuqe3lC3fvGyFQ%2FGCxmUGXfdS8cZTC3WkaFg6YppU%2B9hrhhd59SHVvD%2FqaroH4Ad%2BuSM14HecBFCuyj3BH2gV6RgFtplWn0nuHuiGLmAD2ly7Ger3YT9jeg3iLAPDg7HRv9jyf5XQ8ow6KDk2kWdTCE8FctNDpS9HG%2FfCV9931byCjvbgMsHGJ7otqOZ6e6IuI5afsBtC75rgnNtYZqO04we4YY5w%2BpSc9GZyJD%2FKiRUeA9stph8o0e%2Be4ldZQyfR3NpnSPkRajkaYPjf6jDGpHlHSLiB3CkUoO5q1RU07UJ3n%2FEJ7gGB9pOw4p%2FN6mJybzRe1DDq6ry9BjqkATgiZ4WQQT5ve2cWhznVzWivMS36Kp2Pt1JgAoNAHchg0bFeYiAnO%2FPTZCKtPiXu3owdEVKdnpA2IojTHO%2B1kzUZsJNqyysxwipZStT8p1BHxj5n0owvZVWt%2FLJGVkEgviaSIXXNvuXcQ8Zlgf6QLtcjVxGcMertPYnT4V99ZlrrmgPchPvWPo73rflvykupk9xF2XEPOmCR%2Bneh%2B2j2Gr1LkQl8&X-Amz-Signature=838cb612f2721950fd7687df2831093f6ccb80e48bb05223621fddf3241ef2d7&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663HIRVW2H%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T142225Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAUaCXVzLXdlc3QtMiJIMEYCIQCMcC2FQminRpoPs78%2Fu3joO9mk4nh%2FqSMFYL%2F%2B%2BBaIXQIhANLDk9ymjGTUlSMU37KaCKZNtE04t%2B8OOmE2Zm%2FmJpTYKv8DCC0QABoMNjM3NDIzMTgzODA1IgwzJm5SVmmpLHVKSE4q3AO8ZlT%2FXxMHdPcRx1v8qs%2FC59lJYzMt%2FHowdMMNRDm1O6tANtS1f56o%2FNE9LpHJERjEdUKorSc2Qrp73mG6oxW9w%2BVvAuTXBXz4YNheUD5Pt7ArXPELG24VkRuUNOhm9PV549YZysSbRcPK84yDSfGg0fYHKNmok9cjvMwWEcew1%2BGJ%2FN%2FYljzpzw16e9aBy3%2B4hOUvhHEv55bQ97otHIWGTrM839da0GwNcWnk%2BmWSQcLGwbna2Gc7zGyVh8odeAG9xDhX96Rz%2FrXdVNZzZLuctHHpQHFpqPMe5%2FA184X7PIuOrBFi3U7zuqe3lC3fvGyFQ%2FGCxmUGXfdS8cZTC3WkaFg6YppU%2B9hrhhd59SHVvD%2FqaroH4Ad%2BuSM14HecBFCuyj3BH2gV6RgFtplWn0nuHuiGLmAD2ly7Ger3YT9jeg3iLAPDg7HRv9jyf5XQ8ow6KDk2kWdTCE8FctNDpS9HG%2FfCV9931byCjvbgMsHGJ7otqOZ6e6IuI5afsBtC75rgnNtYZqO04we4YY5w%2BpSc9GZyJD%2FKiRUeA9stph8o0e%2Be4ldZQyfR3NpnSPkRajkaYPjf6jDGpHlHSLiB3CkUoO5q1RU07UJ3n%2FEJ7gGB9pOw4p%2FN6mJybzRe1DDq6ry9BjqkATgiZ4WQQT5ve2cWhznVzWivMS36Kp2Pt1JgAoNAHchg0bFeYiAnO%2FPTZCKtPiXu3owdEVKdnpA2IojTHO%2B1kzUZsJNqyysxwipZStT8p1BHxj5n0owvZVWt%2FLJGVkEgviaSIXXNvuXcQ8Zlgf6QLtcjVxGcMertPYnT4V99ZlrrmgPchPvWPo73rflvykupk9xF2XEPOmCR%2Bneh%2B2j2Gr1LkQl8&X-Amz-Signature=5953218d2aaffc96f11949746e6abfb71ace14523ebd9194795fdd297af73cfc&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663HIRVW2H%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T142225Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAUaCXVzLXdlc3QtMiJIMEYCIQCMcC2FQminRpoPs78%2Fu3joO9mk4nh%2FqSMFYL%2F%2B%2BBaIXQIhANLDk9ymjGTUlSMU37KaCKZNtE04t%2B8OOmE2Zm%2FmJpTYKv8DCC0QABoMNjM3NDIzMTgzODA1IgwzJm5SVmmpLHVKSE4q3AO8ZlT%2FXxMHdPcRx1v8qs%2FC59lJYzMt%2FHowdMMNRDm1O6tANtS1f56o%2FNE9LpHJERjEdUKorSc2Qrp73mG6oxW9w%2BVvAuTXBXz4YNheUD5Pt7ArXPELG24VkRuUNOhm9PV549YZysSbRcPK84yDSfGg0fYHKNmok9cjvMwWEcew1%2BGJ%2FN%2FYljzpzw16e9aBy3%2B4hOUvhHEv55bQ97otHIWGTrM839da0GwNcWnk%2BmWSQcLGwbna2Gc7zGyVh8odeAG9xDhX96Rz%2FrXdVNZzZLuctHHpQHFpqPMe5%2FA184X7PIuOrBFi3U7zuqe3lC3fvGyFQ%2FGCxmUGXfdS8cZTC3WkaFg6YppU%2B9hrhhd59SHVvD%2FqaroH4Ad%2BuSM14HecBFCuyj3BH2gV6RgFtplWn0nuHuiGLmAD2ly7Ger3YT9jeg3iLAPDg7HRv9jyf5XQ8ow6KDk2kWdTCE8FctNDpS9HG%2FfCV9931byCjvbgMsHGJ7otqOZ6e6IuI5afsBtC75rgnNtYZqO04we4YY5w%2BpSc9GZyJD%2FKiRUeA9stph8o0e%2Be4ldZQyfR3NpnSPkRajkaYPjf6jDGpHlHSLiB3CkUoO5q1RU07UJ3n%2FEJ7gGB9pOw4p%2FN6mJybzRe1DDq6ry9BjqkATgiZ4WQQT5ve2cWhznVzWivMS36Kp2Pt1JgAoNAHchg0bFeYiAnO%2FPTZCKtPiXu3owdEVKdnpA2IojTHO%2B1kzUZsJNqyysxwipZStT8p1BHxj5n0owvZVWt%2FLJGVkEgviaSIXXNvuXcQ8Zlgf6QLtcjVxGcMertPYnT4V99ZlrrmgPchPvWPo73rflvykupk9xF2XEPOmCR%2Bneh%2B2j2Gr1LkQl8&X-Amz-Signature=c0f08188d77770b77dde770a912dfb7c251b9aec3d9a6ff576bf2da8b32f0891&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663HIRVW2H%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T142225Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAUaCXVzLXdlc3QtMiJIMEYCIQCMcC2FQminRpoPs78%2Fu3joO9mk4nh%2FqSMFYL%2F%2B%2BBaIXQIhANLDk9ymjGTUlSMU37KaCKZNtE04t%2B8OOmE2Zm%2FmJpTYKv8DCC0QABoMNjM3NDIzMTgzODA1IgwzJm5SVmmpLHVKSE4q3AO8ZlT%2FXxMHdPcRx1v8qs%2FC59lJYzMt%2FHowdMMNRDm1O6tANtS1f56o%2FNE9LpHJERjEdUKorSc2Qrp73mG6oxW9w%2BVvAuTXBXz4YNheUD5Pt7ArXPELG24VkRuUNOhm9PV549YZysSbRcPK84yDSfGg0fYHKNmok9cjvMwWEcew1%2BGJ%2FN%2FYljzpzw16e9aBy3%2B4hOUvhHEv55bQ97otHIWGTrM839da0GwNcWnk%2BmWSQcLGwbna2Gc7zGyVh8odeAG9xDhX96Rz%2FrXdVNZzZLuctHHpQHFpqPMe5%2FA184X7PIuOrBFi3U7zuqe3lC3fvGyFQ%2FGCxmUGXfdS8cZTC3WkaFg6YppU%2B9hrhhd59SHVvD%2FqaroH4Ad%2BuSM14HecBFCuyj3BH2gV6RgFtplWn0nuHuiGLmAD2ly7Ger3YT9jeg3iLAPDg7HRv9jyf5XQ8ow6KDk2kWdTCE8FctNDpS9HG%2FfCV9931byCjvbgMsHGJ7otqOZ6e6IuI5afsBtC75rgnNtYZqO04we4YY5w%2BpSc9GZyJD%2FKiRUeA9stph8o0e%2Be4ldZQyfR3NpnSPkRajkaYPjf6jDGpHlHSLiB3CkUoO5q1RU07UJ3n%2FEJ7gGB9pOw4p%2FN6mJybzRe1DDq6ry9BjqkATgiZ4WQQT5ve2cWhznVzWivMS36Kp2Pt1JgAoNAHchg0bFeYiAnO%2FPTZCKtPiXu3owdEVKdnpA2IojTHO%2B1kzUZsJNqyysxwipZStT8p1BHxj5n0owvZVWt%2FLJGVkEgviaSIXXNvuXcQ8Zlgf6QLtcjVxGcMertPYnT4V99ZlrrmgPchPvWPo73rflvykupk9xF2XEPOmCR%2Bneh%2B2j2Gr1LkQl8&X-Amz-Signature=e7813caca4c950e83954b7bc10262429213767b7317677f1931efe94868ea756&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663U7HSTA6%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T142227Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAUaCXVzLXdlc3QtMiJIMEYCIQCcAYd7VxnqJTMpUSrUyz%2BHoEx2K8el7Rl%2BEUfVk8A0WgIhAPR1MOzpBFSEFtf6%2FM%2BPgiPMbsAYOCP7zgFttkt8aWjNKv8DCC0QABoMNjM3NDIzMTgzODA1IgzErcZpWoT%2F5wxJasQq3ANJXE3aY7tKLJVJlDJkysHUw9RckqUzcdg7iYTXHXW0QL4YjIy9xTR3NunE0a65MR3r3slHMtoW%2FHL6lePiSnQ3hmfsGRv45vGGE9jSFlz6ttVepKm3byloEmB02kJDL%2F7E5fUNypDR%2Bucm7EW%2FQUgZtYCxL4PjkNgh27Ctprz78eLZO%2B1GMy7MPZtgawTb9vuteAGjguI3t%2BBnXVI0ya%2FkEA6MQdotmTiHYhSlDN7dNY0bP8tapU00zArOGw516llp8JxnUB%2BkPS13NstaJ42a5UWG1Ft3WxttwOCfTGSpLLeMarektkucWWpVVh80GqhrslhbHLRRUVO0mOddvq1IzUVcRXmdmRUeUhqkSryyxmtJiqfZ09eUIpM1MwWEU7MmwmcoWMySw2%2FthckzBQCJtaovbUnhHT1I3sbg7crR6tFFeXPfIA%2F5WiF%2F24OArS2k0oT31mx%2F6x%2FMGBfRPRZPIxp35VhMkFYlRLK8N%2Fh%2B8Uwgytwj0ebTObUqun%2FmfQjNxNa%2FsMTH83v0mp6uuzTbY91lY9DofyvoxFATBrwjs3nbAB2sK5yw7xJ7Mhtw08DI%2BxPqC6sbYF2c%2BclEdu%2FY1odEUn%2B8afbNh%2FHZfYQZrls09wtt7j5KiC%2FukzDW6ry9BjqkAX1h4CcINvb9RuWM52ktGmli%2BUkaA3DT6ezKe6lp7%2FyCpS%2By8DbY%2FX4HRLnOsVcPcw1z6W93HtyQdVZxUbAUQQ1zWl40tubrmr47vDzFhrCr8cFkFQD9pQle4k7JcRpxrsZVlPjdGr2tU1tKsldLDu1FzJaT768YSyyxCcdP0AxsD%2BiuZ7UC6PcOd0xu3asuTaFR7jRgsdvp8eOZl0jM%2BZivZImy&X-Amz-Signature=10a1df1ec28559b7fb4728dc9639c76f5dd8b6cc09471d399a6425f7b04ecdc6&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YNRX3GO4%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T142229Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAUaCXVzLXdlc3QtMiJGMEQCIDpSBWgMvtH%2BprLMKfutMwsNx%2FiEoCdThVG%2Febf3ZeAeAiAJFYc4WJ4sPpF1gO6P7Een5JyWd%2FEfLrvXtkyKJ9Y%2Bnyr%2FAwgtEAAaDDYzNzQyMzE4MzgwNSIMFl1BP%2Bn3n90Kn5o4KtwDsZcwG4RGfyUA31gauixhCwhxvx9Emt2ZaY0g1313zkOrGSoSz0cZwh6Mm%2F4%2BCHCGy37RayRIjUTVokvyLmXwd9VJtJm%2BtLL6f%2FFGPHsyAjiHAafvcGZzmI%2BrPFmONY%2Bp8xayZqgL%2BG80GUQCpboYMPvUg1TqyogyJmJoy%2FqiIGtJmo%2FO0RmE2tib%2FZJQ2s7wmIxcug1wVUWymEi7tJHlBzYvTeFTKgD%2FbbWiPB%2Fp0R9ORiMvUKgqqBjswbwPknaJYpu12norFDy2SZZUikREOU4Nb2CC%2FsYYhMp0r%2Fgl8yMl8Rhf65allTWnnfvDjw9ghPGZrW6dbvooZlFjcpVi21Nv%2BgOqWylgJ0nDnhjfeWYhkeB9ZsXWggcvwijMUgiuLjOm98QYQgZu3wA5ew%2BfUdtqbDboQsmHfp%2FjWs9kn0%2BLqf6nZ1qCMQHPcrCCxq%2FU58p%2FiVqRiQIG4rhA4lhrvbNPHtxjFXXqSnnD%2F%2BXwDnUFClO8fPOjZhdYMjlvosCK4WWdra0RibN2bHLO8pF9dV%2FwaOn11fm9qzTvxLb4PESCyBEV3wAkeAhcU2Xtm29qd67LDPAVqKkIrwyYhO3w6WIIH9yNrAXe49b%2Fe84d%2FJ4xxxjB7Qk2GM8x4BIwjeq8vQY6pgGwPhHxQXzfbD9UE3rECsbIB%2B2tTXMdy2uoDjRwdoHNywmkt4GJ70CORsbTPNaUn1yrDs9RxrUaW6ileAw%2FCBHLv6PVu64D0d%2BaOrdFPZ6P5ZtLnGiWRg9%2BnGQhnc%2FO5AIKGwQJO5z7pCjxpJm5m9xy107CyZ3jdMQRvHVVxkTJC6yqRDYp7YQBGFvfgpUVpcThAdlX%2FYA7J7e5dEx%2B48UeI47aa1D%2B&X-Amz-Signature=9f1f12d3cd10096c3680bc1236093b02070fbb81fb4360bbd1ecfb1de125fb6c&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663HIRVW2H%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T142225Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAUaCXVzLXdlc3QtMiJIMEYCIQCMcC2FQminRpoPs78%2Fu3joO9mk4nh%2FqSMFYL%2F%2B%2BBaIXQIhANLDk9ymjGTUlSMU37KaCKZNtE04t%2B8OOmE2Zm%2FmJpTYKv8DCC0QABoMNjM3NDIzMTgzODA1IgwzJm5SVmmpLHVKSE4q3AO8ZlT%2FXxMHdPcRx1v8qs%2FC59lJYzMt%2FHowdMMNRDm1O6tANtS1f56o%2FNE9LpHJERjEdUKorSc2Qrp73mG6oxW9w%2BVvAuTXBXz4YNheUD5Pt7ArXPELG24VkRuUNOhm9PV549YZysSbRcPK84yDSfGg0fYHKNmok9cjvMwWEcew1%2BGJ%2FN%2FYljzpzw16e9aBy3%2B4hOUvhHEv55bQ97otHIWGTrM839da0GwNcWnk%2BmWSQcLGwbna2Gc7zGyVh8odeAG9xDhX96Rz%2FrXdVNZzZLuctHHpQHFpqPMe5%2FA184X7PIuOrBFi3U7zuqe3lC3fvGyFQ%2FGCxmUGXfdS8cZTC3WkaFg6YppU%2B9hrhhd59SHVvD%2FqaroH4Ad%2BuSM14HecBFCuyj3BH2gV6RgFtplWn0nuHuiGLmAD2ly7Ger3YT9jeg3iLAPDg7HRv9jyf5XQ8ow6KDk2kWdTCE8FctNDpS9HG%2FfCV9931byCjvbgMsHGJ7otqOZ6e6IuI5afsBtC75rgnNtYZqO04we4YY5w%2BpSc9GZyJD%2FKiRUeA9stph8o0e%2Be4ldZQyfR3NpnSPkRajkaYPjf6jDGpHlHSLiB3CkUoO5q1RU07UJ3n%2FEJ7gGB9pOw4p%2FN6mJybzRe1DDq6ry9BjqkATgiZ4WQQT5ve2cWhznVzWivMS36Kp2Pt1JgAoNAHchg0bFeYiAnO%2FPTZCKtPiXu3owdEVKdnpA2IojTHO%2B1kzUZsJNqyysxwipZStT8p1BHxj5n0owvZVWt%2FLJGVkEgviaSIXXNvuXcQ8Zlgf6QLtcjVxGcMertPYnT4V99ZlrrmgPchPvWPo73rflvykupk9xF2XEPOmCR%2Bneh%2B2j2Gr1LkQl8&X-Amz-Signature=bc3ffe7b64ff0108ae6ba02336f88c8c28cc2206d3f71e5f221e4d2a5bd403cc&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663HIRVW2H%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T142225Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAUaCXVzLXdlc3QtMiJIMEYCIQCMcC2FQminRpoPs78%2Fu3joO9mk4nh%2FqSMFYL%2F%2B%2BBaIXQIhANLDk9ymjGTUlSMU37KaCKZNtE04t%2B8OOmE2Zm%2FmJpTYKv8DCC0QABoMNjM3NDIzMTgzODA1IgwzJm5SVmmpLHVKSE4q3AO8ZlT%2FXxMHdPcRx1v8qs%2FC59lJYzMt%2FHowdMMNRDm1O6tANtS1f56o%2FNE9LpHJERjEdUKorSc2Qrp73mG6oxW9w%2BVvAuTXBXz4YNheUD5Pt7ArXPELG24VkRuUNOhm9PV549YZysSbRcPK84yDSfGg0fYHKNmok9cjvMwWEcew1%2BGJ%2FN%2FYljzpzw16e9aBy3%2B4hOUvhHEv55bQ97otHIWGTrM839da0GwNcWnk%2BmWSQcLGwbna2Gc7zGyVh8odeAG9xDhX96Rz%2FrXdVNZzZLuctHHpQHFpqPMe5%2FA184X7PIuOrBFi3U7zuqe3lC3fvGyFQ%2FGCxmUGXfdS8cZTC3WkaFg6YppU%2B9hrhhd59SHVvD%2FqaroH4Ad%2BuSM14HecBFCuyj3BH2gV6RgFtplWn0nuHuiGLmAD2ly7Ger3YT9jeg3iLAPDg7HRv9jyf5XQ8ow6KDk2kWdTCE8FctNDpS9HG%2FfCV9931byCjvbgMsHGJ7otqOZ6e6IuI5afsBtC75rgnNtYZqO04we4YY5w%2BpSc9GZyJD%2FKiRUeA9stph8o0e%2Be4ldZQyfR3NpnSPkRajkaYPjf6jDGpHlHSLiB3CkUoO5q1RU07UJ3n%2FEJ7gGB9pOw4p%2FN6mJybzRe1DDq6ry9BjqkATgiZ4WQQT5ve2cWhznVzWivMS36Kp2Pt1JgAoNAHchg0bFeYiAnO%2FPTZCKtPiXu3owdEVKdnpA2IojTHO%2B1kzUZsJNqyysxwipZStT8p1BHxj5n0owvZVWt%2FLJGVkEgviaSIXXNvuXcQ8Zlgf6QLtcjVxGcMertPYnT4V99ZlrrmgPchPvWPo73rflvykupk9xF2XEPOmCR%2Bneh%2B2j2Gr1LkQl8&X-Amz-Signature=02e88771c7466675561a6ab186ab9ed8274f6d7405c4f9eca6fd557448a5fd9f&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663HIRVW2H%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T142225Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAUaCXVzLXdlc3QtMiJIMEYCIQCMcC2FQminRpoPs78%2Fu3joO9mk4nh%2FqSMFYL%2F%2B%2BBaIXQIhANLDk9ymjGTUlSMU37KaCKZNtE04t%2B8OOmE2Zm%2FmJpTYKv8DCC0QABoMNjM3NDIzMTgzODA1IgwzJm5SVmmpLHVKSE4q3AO8ZlT%2FXxMHdPcRx1v8qs%2FC59lJYzMt%2FHowdMMNRDm1O6tANtS1f56o%2FNE9LpHJERjEdUKorSc2Qrp73mG6oxW9w%2BVvAuTXBXz4YNheUD5Pt7ArXPELG24VkRuUNOhm9PV549YZysSbRcPK84yDSfGg0fYHKNmok9cjvMwWEcew1%2BGJ%2FN%2FYljzpzw16e9aBy3%2B4hOUvhHEv55bQ97otHIWGTrM839da0GwNcWnk%2BmWSQcLGwbna2Gc7zGyVh8odeAG9xDhX96Rz%2FrXdVNZzZLuctHHpQHFpqPMe5%2FA184X7PIuOrBFi3U7zuqe3lC3fvGyFQ%2FGCxmUGXfdS8cZTC3WkaFg6YppU%2B9hrhhd59SHVvD%2FqaroH4Ad%2BuSM14HecBFCuyj3BH2gV6RgFtplWn0nuHuiGLmAD2ly7Ger3YT9jeg3iLAPDg7HRv9jyf5XQ8ow6KDk2kWdTCE8FctNDpS9HG%2FfCV9931byCjvbgMsHGJ7otqOZ6e6IuI5afsBtC75rgnNtYZqO04we4YY5w%2BpSc9GZyJD%2FKiRUeA9stph8o0e%2Be4ldZQyfR3NpnSPkRajkaYPjf6jDGpHlHSLiB3CkUoO5q1RU07UJ3n%2FEJ7gGB9pOw4p%2FN6mJybzRe1DDq6ry9BjqkATgiZ4WQQT5ve2cWhznVzWivMS36Kp2Pt1JgAoNAHchg0bFeYiAnO%2FPTZCKtPiXu3owdEVKdnpA2IojTHO%2B1kzUZsJNqyysxwipZStT8p1BHxj5n0owvZVWt%2FLJGVkEgviaSIXXNvuXcQ8Zlgf6QLtcjVxGcMertPYnT4V99ZlrrmgPchPvWPo73rflvykupk9xF2XEPOmCR%2Bneh%2B2j2Gr1LkQl8&X-Amz-Signature=bd67f382741bb3d7e9519cab7ba9fe9a65c408a18137c1288d1012745ff8622d&X-Amz-SignedHeaders=host&x-id=GetObject)


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

