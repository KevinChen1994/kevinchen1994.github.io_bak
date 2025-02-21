---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4662Q67ATNZ%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250221T052345Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEKX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCICBQYU1RqO1Sbotzzql\
  n9ibGY2LKXZIiZogttg%2B3ZObxAiEAjgMn%2FlBqx3OGiAajY%2Bm15s4ZhioIW4eldbUHGv9%2F\
  hg0qiAQIzv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLntN5rYyqcHD\
  mTzJircA%2FvaDCCqbQ0qyfSpfrJunF2nuKMVoGlsq%2F%2FjBqzG1FH6VGxY%2Foaxs3TaUXyz2X\
  WrVjfvzNGVuKuUHtVZNvorPSPXLqhG866iPHFwBaxvXUSSMU1OA7B9%2B00A8GqruMxHyf9s6oRgf\
  2mYmV8AKOJvezR1tJd4lPrNiGzeH%2BPl4WFB%2BkM9zNW5z7iQe8kGzqwj9xd93ktej3i5DQUQIb\
  vPX%2F%2BNKkLDOjBuPKf1c2bDWi76jyQPrXAUXxHnRBKlaJTNdMYfMYtDWxT7sbAJ2SsorfRFbc2\
  Jg415NMCvQcWkUEMz8NpZxdtVA1MXEy5a4A6lEf9IdyWMb3pdl8%2BzWnL1mwuy7nJhsK6de8eU6I\
  PrDoHYoaLDMRnLF%2FohpP2j24HO2HFWi9tQL7Yz0exuh38z7i8nbiINrHrJnHmFaSqmwMzuZ0jvE\
  aDBnUhAPq7w%2B1MHAsQraPvYFANWZ3242%2FsqFdj2uoVlgL5kAFv65TI9ijaViFtsXCw4yCEAcE\
  4LThX0cCl1vgK%2FVpIscMiUfL%2BpSQVutkdPm5rNglryg1kU8NJhcp9Esr0b5dxrGinmsFtK%2B\
  mhq%2BorAM0LjePxRW6OYG5lTljR8fJ2cyW5fWrayWz0kPwLOUJkW%2FxreuhBJMJGG4L0GOqUBMj\
  x%2BcV9%2FwLWVQPsUxxRlJ2W5kJPRT63vuZB4mUHTVxZNow3ULJvQROqNH9seY4DWES0LvQDh7yO\
  gqUQ5WztIFJnlovU4dqvwefg7tVI5Px0lmJNMlZi0mc7JUnFE%2F8OUM4pvD2JdKKqmkyskHnkDyN\
  Ae1dfzCvywm6uyaxgyiD2Vi8XYZkLXJW15RYkI%2BBTdNU2INihL2I4ccIK2Z5We6z8yZ4xc&X-Am\
  z-Signature=f5ef6b8bd619d27afac9bf5bd4e2505d6cb94bc8113ee7c1197b5625878fb036&\
  X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466W3KZEAOO%2F20250221%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250221T052139Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEKX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEY\
        CIQC1Zp02lNYSwIZ8hMvdj50mxMDjl%2FdMwvmibBSaua3pVgIhAJHurmXqU52HNhVbaxsO\
        DPUgFeNpXmWqhVJolQpcQXanKogECM7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM\
        3NDIzMTgzODA1IgyhZCSKFVjHzpKE3JAq3AOwwQgnVvzdjcwdYhUurjnEfySw9yRtA3Lj%2\
        BimZdff8yz8UIQ7nrPGL6XiGiMc6YlIQBML%2FnBXMHBOxionydSeIGTXBy%2B0AEzQ2klq\
        16baLcRnob8l0AweU5gSn7rnWtfreqAWfb4CyrMG1lj%2BCJ8%2F5XKKRyfojaVQXqAK5ys\
        cnM244KPiSniyy6FI2bVOf7iPip165kSTElXHQDR15CYStQQ9JojwWmJcboafYvHy44Px4j\
        cej0HFmE2CsvpdSm0107T3Psj7%2BwcquxvIhNQbIt7lRwjTrGn4YDJM5GgKDB5ZxQnwiZs\
        imEXV459GdN4SDFs2RClJbE%2FNZJfS65zc2f42O4tHuvTnjuOHynmcL%2FMy55I2yonMVA\
        1YUe80D0Um5kmcaNkz1Y3ltfGyjroYja%2FtDs4kqtZGwv%2F4ZsuaSDgbFJR16q5lz2FbL\
        GJZsTBV3eCVzAu%2BTDaiR1r8Cix7doNo6NdWsTPk9Ftu4f8IFInaT5Gz%2B6gCeAw%2B5W\
        Kk7sPDvyHx5wtazs9yiraQYfNLd5acPBNE9W6BTervTIOwUSx0S9etF8eIIUhDmuokbkRHG\
        15B7cbF5MLm6Z63d3hJgpxzXx4DnggdqYnu%2B6Ok91QTcOF%2F3ySSF6iaTZjChh%2BC9B\
        jqkARgU%2BoE1GmjolBdkv1vaQCz%2FdozsAa2xivjIY5ekQ%2FmQmEtMQDip03UadVZ55z\
        DU2qIWy9AKThl65tUc020ob%2B4jeVZwVYOIZG85%2FybBnHHNdOFTjrTNqIONbvjU8BLpp\
        %2BmX9g6OVOhSyYOO8QQz0Wllvi2mAUmVsZ9AkSpuxIhBFxsDT1zC3mPQ9Orwkf%2BEnkOo\
        Sn4GPA%2FT%2FO%2FAXbkUZCDh%2B08w&X-Amz-Signature=6f5a4a8946e7cf02749c29\
        702809d9f8bcbc02c8db21cfaa29c7ad8e54fbcac3&X-Amz-SignedHeaders=host&x-i\
        d=GetObject"
      expiry_time: "2025-02-21T06:21:39.770Z"
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
UPDATE_TIME: "2025-02-21T05:23:50.173Z"
EXPIRY_TIME: "2025-02-21T06:23:43.226Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666WLZH5YS%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T052343Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIApx%2FWMnMbFb3SONaSRR7z9laXsPCMsKZ52dEACA6cIaAiEA8W81IjWYoERxeE%2Brp94LOubyxXpGexaPnrk3oyou%2FeQqiAQIzv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOHZjybT4bgBn5KGNSrcA5POVqzeOQxHDf%2FmY9Tb%2BPQe%2FPcqhitUft8yzvEUwTCv%2BG%2BX3yUURS%2F1qrqyMNobLSqkef97qoTViOP2J9oAKZ%2BA4ZCxDfyhtX64%2B5oLakse0dV4ReVeF%2FS%2FhqatRHCMTNx%2BeZtj2U75vm2JAnLqoEzD1%2Fq2Zc9tyP6JKjZOUZfmSZX11DJSO1jeR%2FB4oeViL9ANJ%2Bip2GYcAfJ9I2r4INIeVflKNzcPYFlzdLaonmXqt%2Bwr2DqizGwKiBfBHdXScr1WrqZI1fH7zdO7w32Aqe1ntN9L8TFQ8lylvPqVgnuN3QKiVF5sS6gq%2B7ygAHfWFECROr6adZAn%2FUa0vXi8ToAerGNwdSH3%2BKW4NSJF2bKaiGhD0LVzijLGJk9Vn7%2BNOCcF4Ab2Ydo%2FVb%2Bv3Xqy8uExzdGYY4Q%2F0GoXBMNalQCqKg3Q5ElU5bVaVxSN%2B0umYuV1YqNoRcuKXKU7aDfC18CaqyUUcl3FxMiBmos9Qo4Q7TJyUsPWvdTnPHjWJf2ZXAQDwiGcP2OqsDNSSs5%2BKF2bHSrlX09UJjkA7dFf%2BLH7%2BxFAvFtnE7FBtWI6YOIcgiLoYwcyFXE4IUsxJzp8RXAn6gvz3catWuJfEkVqryQwg0AnzbXVePtleIjBMPKF4L0GOqUBULz8%2BsTBz8%2BHUGpNF0h6IBXHC%2FS6S%2BtkwaJXhbIwjBZR%2F7n8u1htRLHOueC%2BEwLQAsLqaVTW1XbznoLj6%2B5Kq7TLV0WkDaHvIvXeJvG6LlaDyLdwF4zb0qR11qrLY%2By1802T0ePr5KvxgNMmtAOGvDwFYr48VdC5MKo1dD7hjtC4Z7NQ36pSgnaP4Lu4pm4J5KMSB1dRfqmtZ%2BbL4rJF9lyCdxDu&X-Amz-Signature=f7c1a7f7f7618865d8e60352ffaceee4b0ee2f1016af44a6a362c4bfdc6507b3&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666WLZH5YS%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T052343Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIApx%2FWMnMbFb3SONaSRR7z9laXsPCMsKZ52dEACA6cIaAiEA8W81IjWYoERxeE%2Brp94LOubyxXpGexaPnrk3oyou%2FeQqiAQIzv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOHZjybT4bgBn5KGNSrcA5POVqzeOQxHDf%2FmY9Tb%2BPQe%2FPcqhitUft8yzvEUwTCv%2BG%2BX3yUURS%2F1qrqyMNobLSqkef97qoTViOP2J9oAKZ%2BA4ZCxDfyhtX64%2B5oLakse0dV4ReVeF%2FS%2FhqatRHCMTNx%2BeZtj2U75vm2JAnLqoEzD1%2Fq2Zc9tyP6JKjZOUZfmSZX11DJSO1jeR%2FB4oeViL9ANJ%2Bip2GYcAfJ9I2r4INIeVflKNzcPYFlzdLaonmXqt%2Bwr2DqizGwKiBfBHdXScr1WrqZI1fH7zdO7w32Aqe1ntN9L8TFQ8lylvPqVgnuN3QKiVF5sS6gq%2B7ygAHfWFECROr6adZAn%2FUa0vXi8ToAerGNwdSH3%2BKW4NSJF2bKaiGhD0LVzijLGJk9Vn7%2BNOCcF4Ab2Ydo%2FVb%2Bv3Xqy8uExzdGYY4Q%2F0GoXBMNalQCqKg3Q5ElU5bVaVxSN%2B0umYuV1YqNoRcuKXKU7aDfC18CaqyUUcl3FxMiBmos9Qo4Q7TJyUsPWvdTnPHjWJf2ZXAQDwiGcP2OqsDNSSs5%2BKF2bHSrlX09UJjkA7dFf%2BLH7%2BxFAvFtnE7FBtWI6YOIcgiLoYwcyFXE4IUsxJzp8RXAn6gvz3catWuJfEkVqryQwg0AnzbXVePtleIjBMPKF4L0GOqUBULz8%2BsTBz8%2BHUGpNF0h6IBXHC%2FS6S%2BtkwaJXhbIwjBZR%2F7n8u1htRLHOueC%2BEwLQAsLqaVTW1XbznoLj6%2B5Kq7TLV0WkDaHvIvXeJvG6LlaDyLdwF4zb0qR11qrLY%2By1802T0ePr5KvxgNMmtAOGvDwFYr48VdC5MKo1dD7hjtC4Z7NQ36pSgnaP4Lu4pm4J5KMSB1dRfqmtZ%2BbL4rJF9lyCdxDu&X-Amz-Signature=c2f81ace01e72087171b1c12db77ca0ab8e3d69129425a475c572d67167b3ffa&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666WLZH5YS%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T052343Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIApx%2FWMnMbFb3SONaSRR7z9laXsPCMsKZ52dEACA6cIaAiEA8W81IjWYoERxeE%2Brp94LOubyxXpGexaPnrk3oyou%2FeQqiAQIzv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOHZjybT4bgBn5KGNSrcA5POVqzeOQxHDf%2FmY9Tb%2BPQe%2FPcqhitUft8yzvEUwTCv%2BG%2BX3yUURS%2F1qrqyMNobLSqkef97qoTViOP2J9oAKZ%2BA4ZCxDfyhtX64%2B5oLakse0dV4ReVeF%2FS%2FhqatRHCMTNx%2BeZtj2U75vm2JAnLqoEzD1%2Fq2Zc9tyP6JKjZOUZfmSZX11DJSO1jeR%2FB4oeViL9ANJ%2Bip2GYcAfJ9I2r4INIeVflKNzcPYFlzdLaonmXqt%2Bwr2DqizGwKiBfBHdXScr1WrqZI1fH7zdO7w32Aqe1ntN9L8TFQ8lylvPqVgnuN3QKiVF5sS6gq%2B7ygAHfWFECROr6adZAn%2FUa0vXi8ToAerGNwdSH3%2BKW4NSJF2bKaiGhD0LVzijLGJk9Vn7%2BNOCcF4Ab2Ydo%2FVb%2Bv3Xqy8uExzdGYY4Q%2F0GoXBMNalQCqKg3Q5ElU5bVaVxSN%2B0umYuV1YqNoRcuKXKU7aDfC18CaqyUUcl3FxMiBmos9Qo4Q7TJyUsPWvdTnPHjWJf2ZXAQDwiGcP2OqsDNSSs5%2BKF2bHSrlX09UJjkA7dFf%2BLH7%2BxFAvFtnE7FBtWI6YOIcgiLoYwcyFXE4IUsxJzp8RXAn6gvz3catWuJfEkVqryQwg0AnzbXVePtleIjBMPKF4L0GOqUBULz8%2BsTBz8%2BHUGpNF0h6IBXHC%2FS6S%2BtkwaJXhbIwjBZR%2F7n8u1htRLHOueC%2BEwLQAsLqaVTW1XbznoLj6%2B5Kq7TLV0WkDaHvIvXeJvG6LlaDyLdwF4zb0qR11qrLY%2By1802T0ePr5KvxgNMmtAOGvDwFYr48VdC5MKo1dD7hjtC4Z7NQ36pSgnaP4Lu4pm4J5KMSB1dRfqmtZ%2BbL4rJF9lyCdxDu&X-Amz-Signature=98b07100d3dfaa78e86b6e372bdda7de49f537cc8cfc62555403331f3d584f42&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666WLZH5YS%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T052343Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIApx%2FWMnMbFb3SONaSRR7z9laXsPCMsKZ52dEACA6cIaAiEA8W81IjWYoERxeE%2Brp94LOubyxXpGexaPnrk3oyou%2FeQqiAQIzv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOHZjybT4bgBn5KGNSrcA5POVqzeOQxHDf%2FmY9Tb%2BPQe%2FPcqhitUft8yzvEUwTCv%2BG%2BX3yUURS%2F1qrqyMNobLSqkef97qoTViOP2J9oAKZ%2BA4ZCxDfyhtX64%2B5oLakse0dV4ReVeF%2FS%2FhqatRHCMTNx%2BeZtj2U75vm2JAnLqoEzD1%2Fq2Zc9tyP6JKjZOUZfmSZX11DJSO1jeR%2FB4oeViL9ANJ%2Bip2GYcAfJ9I2r4INIeVflKNzcPYFlzdLaonmXqt%2Bwr2DqizGwKiBfBHdXScr1WrqZI1fH7zdO7w32Aqe1ntN9L8TFQ8lylvPqVgnuN3QKiVF5sS6gq%2B7ygAHfWFECROr6adZAn%2FUa0vXi8ToAerGNwdSH3%2BKW4NSJF2bKaiGhD0LVzijLGJk9Vn7%2BNOCcF4Ab2Ydo%2FVb%2Bv3Xqy8uExzdGYY4Q%2F0GoXBMNalQCqKg3Q5ElU5bVaVxSN%2B0umYuV1YqNoRcuKXKU7aDfC18CaqyUUcl3FxMiBmos9Qo4Q7TJyUsPWvdTnPHjWJf2ZXAQDwiGcP2OqsDNSSs5%2BKF2bHSrlX09UJjkA7dFf%2BLH7%2BxFAvFtnE7FBtWI6YOIcgiLoYwcyFXE4IUsxJzp8RXAn6gvz3catWuJfEkVqryQwg0AnzbXVePtleIjBMPKF4L0GOqUBULz8%2BsTBz8%2BHUGpNF0h6IBXHC%2FS6S%2BtkwaJXhbIwjBZR%2F7n8u1htRLHOueC%2BEwLQAsLqaVTW1XbznoLj6%2B5Kq7TLV0WkDaHvIvXeJvG6LlaDyLdwF4zb0qR11qrLY%2By1802T0ePr5KvxgNMmtAOGvDwFYr48VdC5MKo1dD7hjtC4Z7NQ36pSgnaP4Lu4pm4J5KMSB1dRfqmtZ%2BbL4rJF9lyCdxDu&X-Amz-Signature=e2c2a5e5ff1cdb2f345eb210d68cc25cb2cb724db45ec0a5e5f121b9a978172b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666WLZH5YS%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T052343Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIApx%2FWMnMbFb3SONaSRR7z9laXsPCMsKZ52dEACA6cIaAiEA8W81IjWYoERxeE%2Brp94LOubyxXpGexaPnrk3oyou%2FeQqiAQIzv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOHZjybT4bgBn5KGNSrcA5POVqzeOQxHDf%2FmY9Tb%2BPQe%2FPcqhitUft8yzvEUwTCv%2BG%2BX3yUURS%2F1qrqyMNobLSqkef97qoTViOP2J9oAKZ%2BA4ZCxDfyhtX64%2B5oLakse0dV4ReVeF%2FS%2FhqatRHCMTNx%2BeZtj2U75vm2JAnLqoEzD1%2Fq2Zc9tyP6JKjZOUZfmSZX11DJSO1jeR%2FB4oeViL9ANJ%2Bip2GYcAfJ9I2r4INIeVflKNzcPYFlzdLaonmXqt%2Bwr2DqizGwKiBfBHdXScr1WrqZI1fH7zdO7w32Aqe1ntN9L8TFQ8lylvPqVgnuN3QKiVF5sS6gq%2B7ygAHfWFECROr6adZAn%2FUa0vXi8ToAerGNwdSH3%2BKW4NSJF2bKaiGhD0LVzijLGJk9Vn7%2BNOCcF4Ab2Ydo%2FVb%2Bv3Xqy8uExzdGYY4Q%2F0GoXBMNalQCqKg3Q5ElU5bVaVxSN%2B0umYuV1YqNoRcuKXKU7aDfC18CaqyUUcl3FxMiBmos9Qo4Q7TJyUsPWvdTnPHjWJf2ZXAQDwiGcP2OqsDNSSs5%2BKF2bHSrlX09UJjkA7dFf%2BLH7%2BxFAvFtnE7FBtWI6YOIcgiLoYwcyFXE4IUsxJzp8RXAn6gvz3catWuJfEkVqryQwg0AnzbXVePtleIjBMPKF4L0GOqUBULz8%2BsTBz8%2BHUGpNF0h6IBXHC%2FS6S%2BtkwaJXhbIwjBZR%2F7n8u1htRLHOueC%2BEwLQAsLqaVTW1XbznoLj6%2B5Kq7TLV0WkDaHvIvXeJvG6LlaDyLdwF4zb0qR11qrLY%2By1802T0ePr5KvxgNMmtAOGvDwFYr48VdC5MKo1dD7hjtC4Z7NQ36pSgnaP4Lu4pm4J5KMSB1dRfqmtZ%2BbL4rJF9lyCdxDu&X-Amz-Signature=c69ff04752f94816834d4f14dfe019c0ea088e73104ebcd7a2818369e9081d30&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UJACH32V%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T052344Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCqYztQQQelweDzs5UkcbOEnx7GRiDQMvZ8L%2BLEvVWdPAIhAO1NQIgPvsFQ%2Fd3ha9MByh5JleIex3aJktEwKGo0id85KogECM7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgySmPh6fcssOW5jWyYq3ANEvzYj5mlHNJXEgZmcydgizaWGWHsTt%2BhoPOx6Dh5rsOBjWObhTW%2FKJ1HJ3gp8uqZO8cY%2B16yFpOXwarkt4rlUpUuN2ZRRFO4v0C%2BjkpJ18o%2BEAzjQLTOTEYwtEMZTlikLwHSDljxml3KYQr43C2MtjtHiKBqq7Agifj%2BTgxxHzuNtMtPyd5DyGEKM2ttGBh4XAqtu5VDjymGaeBIRCXRSRwsiqG%2BNj4dPw9VspdLds%2Fv7tdJ92%2FGQF6RMfJ7BoLHmozWNhb1N0%2BPimlMTiU%2B9edKTCHRmFHt5iFkH1zw1B6EatZa%2BNB8upCDfl9PCRYYwhkoyEUqWO7hr1zcuRZwAWLQKcJ3q7WgcOlmFo%2Bqd%2FJ7MVe4%2FpJ1O79xtSGiyPqU0kQy9rQgLA6s777ZA9mF8l27TzpfB%2BdyErYL5KAGXo5lYoSynK7Ix4sr8WaqS37%2FDQoBX9hdW5%2Fd%2FDtCf0XL6SdurJ3atMQbIhOmy6i3aW28l1CV1FdRu48CxC6vr5M6iarsIN7B0FIBlEAva52u5dkCzFW1ZfTQjfnsobKrmQ5B20G01L8MjkOyyXtms4QRMNQPiae7ip7yOBl7ABHZkGKFHw7DT4DOwkEH7c5vieMNWk6wbINEDicqiZjDrhuC9BjqkAT04fGo%2FGU3AkshV6cOs7uJGJ%2BOtTmBDs4WF9G9hj8MxxIZ6yGhPkQ%2BNmfhr%2B5Uj7e%2Br4RkYlTHtmI8DCsAJCIAYW%2FG7xQUD0anXFkcZNv4WZWBC1DtxIVSoWUDO4qwjCqd0TUp4JgxDVhC3LQzAgXU1Clnv%2FSRf00whS9jOvBoJ%2BbGds9M2rNaPUdF5665YukcsrIw0AFg7ohsyJfsl86V8aj5C&X-Amz-Signature=7f40ea97c21c9808bb8ddcb81c571fb780e0e8a2a200286ef504d50b994e7656&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UQLVTPOU%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T052344Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDDImk4TiKLPyUYrCX%2FfndJpP9Qfpfd88DpFP3UaXsYVAIgPJo8y6lLz3FldnS57UCqeWGhqGXoZ9HOGxP1Sh6jDV8qiAQIzv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDFAtkrlbnfQ6xszNJSrcA32HIIabrbwpAY58sRLs8wkw03FQij4%2BVYBZnmB75X7HxPkoGWJLESYg2rGZ0p%2Bq0Eqake2fI19QWUzb6jr0eItuLkIwtZKRgLS3JgesNK4slEcfoBx0VS5ZMEnWTHG%2BYzkfuipx521vpCPpt3B9NRcjgI4zzOWo2MDbLwBPO%2F0YLaxDu1riHx5d864wRX3YgRiBrq8%2BDO%2FEaUUBkZ7m%2B%2FVOOLixSs2UXHdDtOeggM6hiCsN1YYDKwuwb5mE5KhyoT0JCvRDveAKbamhXWy4b3HvCLNdfPNz9DajmIUeq%2FkRCMrZkWWtwUHTdAVCBx2oCRqFORJFRouVPDAufxOEHZSBatoRpyf%2Fywna00uzz8tIXwCK8lC1cUwXMGQR4gb14MBjdQiiDSSPIHuiM7t3HIMP%2BbXbFaXhurIqxLA16%2BZIpdx6r%2F%2FamCoNyZTZL8VyA0T9IOiEAKLzaj2E0rUFUdijtglkmgCXdz%2F2ETfLlENsvPgRb%2FFh%2F9AkWFvWM8%2F8%2BbAG4v%2BkMS%2FU6SUVG4xAHXPHsYUGDn3P3Jd7lLIVlxwTJGhchsEwfS9Mkby3HWgzDu4QWA89Z%2BPQrBKHt9socEYOOBmt4K66f9duKuRMQ8FQ2Z8UBLLggKQxR2BWMO6G4L0GOqUBFikhMUGz6k1eqfBMnWY6flvT2ORwVqpQ%2F5wOxwLaLXU85OmX%2BTUrlkMNE8gYGWPgEWJ2Xw97%2FzHj6e3kpnErBUnzD61L%2Bi5LKCjohsgqDYPgvL9r1BAlJSgaoUzIAxDQbz3A0wFSRLKV2ZyIKH%2BXnlko0mWY%2FbQJeeZqNCCswtFk2PW9crimCqhKKdlNLwMfmi7CXhSkPuNY%2B0ewAuM8nmnsToby&X-Amz-Signature=86c9c39a5babddf5fb7e7c8c17995cb850522fac49935d871efc2c392ac0294b&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666WLZH5YS%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T052343Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIApx%2FWMnMbFb3SONaSRR7z9laXsPCMsKZ52dEACA6cIaAiEA8W81IjWYoERxeE%2Brp94LOubyxXpGexaPnrk3oyou%2FeQqiAQIzv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOHZjybT4bgBn5KGNSrcA5POVqzeOQxHDf%2FmY9Tb%2BPQe%2FPcqhitUft8yzvEUwTCv%2BG%2BX3yUURS%2F1qrqyMNobLSqkef97qoTViOP2J9oAKZ%2BA4ZCxDfyhtX64%2B5oLakse0dV4ReVeF%2FS%2FhqatRHCMTNx%2BeZtj2U75vm2JAnLqoEzD1%2Fq2Zc9tyP6JKjZOUZfmSZX11DJSO1jeR%2FB4oeViL9ANJ%2Bip2GYcAfJ9I2r4INIeVflKNzcPYFlzdLaonmXqt%2Bwr2DqizGwKiBfBHdXScr1WrqZI1fH7zdO7w32Aqe1ntN9L8TFQ8lylvPqVgnuN3QKiVF5sS6gq%2B7ygAHfWFECROr6adZAn%2FUa0vXi8ToAerGNwdSH3%2BKW4NSJF2bKaiGhD0LVzijLGJk9Vn7%2BNOCcF4Ab2Ydo%2FVb%2Bv3Xqy8uExzdGYY4Q%2F0GoXBMNalQCqKg3Q5ElU5bVaVxSN%2B0umYuV1YqNoRcuKXKU7aDfC18CaqyUUcl3FxMiBmos9Qo4Q7TJyUsPWvdTnPHjWJf2ZXAQDwiGcP2OqsDNSSs5%2BKF2bHSrlX09UJjkA7dFf%2BLH7%2BxFAvFtnE7FBtWI6YOIcgiLoYwcyFXE4IUsxJzp8RXAn6gvz3catWuJfEkVqryQwg0AnzbXVePtleIjBMPKF4L0GOqUBULz8%2BsTBz8%2BHUGpNF0h6IBXHC%2FS6S%2BtkwaJXhbIwjBZR%2F7n8u1htRLHOueC%2BEwLQAsLqaVTW1XbznoLj6%2B5Kq7TLV0WkDaHvIvXeJvG6LlaDyLdwF4zb0qR11qrLY%2By1802T0ePr5KvxgNMmtAOGvDwFYr48VdC5MKo1dD7hjtC4Z7NQ36pSgnaP4Lu4pm4J5KMSB1dRfqmtZ%2BbL4rJF9lyCdxDu&X-Amz-Signature=c401b6c6582e30f7d9a513298b24962759806b03bb80fd6ac61b218841300d7a&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666WLZH5YS%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T052343Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIApx%2FWMnMbFb3SONaSRR7z9laXsPCMsKZ52dEACA6cIaAiEA8W81IjWYoERxeE%2Brp94LOubyxXpGexaPnrk3oyou%2FeQqiAQIzv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOHZjybT4bgBn5KGNSrcA5POVqzeOQxHDf%2FmY9Tb%2BPQe%2FPcqhitUft8yzvEUwTCv%2BG%2BX3yUURS%2F1qrqyMNobLSqkef97qoTViOP2J9oAKZ%2BA4ZCxDfyhtX64%2B5oLakse0dV4ReVeF%2FS%2FhqatRHCMTNx%2BeZtj2U75vm2JAnLqoEzD1%2Fq2Zc9tyP6JKjZOUZfmSZX11DJSO1jeR%2FB4oeViL9ANJ%2Bip2GYcAfJ9I2r4INIeVflKNzcPYFlzdLaonmXqt%2Bwr2DqizGwKiBfBHdXScr1WrqZI1fH7zdO7w32Aqe1ntN9L8TFQ8lylvPqVgnuN3QKiVF5sS6gq%2B7ygAHfWFECROr6adZAn%2FUa0vXi8ToAerGNwdSH3%2BKW4NSJF2bKaiGhD0LVzijLGJk9Vn7%2BNOCcF4Ab2Ydo%2FVb%2Bv3Xqy8uExzdGYY4Q%2F0GoXBMNalQCqKg3Q5ElU5bVaVxSN%2B0umYuV1YqNoRcuKXKU7aDfC18CaqyUUcl3FxMiBmos9Qo4Q7TJyUsPWvdTnPHjWJf2ZXAQDwiGcP2OqsDNSSs5%2BKF2bHSrlX09UJjkA7dFf%2BLH7%2BxFAvFtnE7FBtWI6YOIcgiLoYwcyFXE4IUsxJzp8RXAn6gvz3catWuJfEkVqryQwg0AnzbXVePtleIjBMPKF4L0GOqUBULz8%2BsTBz8%2BHUGpNF0h6IBXHC%2FS6S%2BtkwaJXhbIwjBZR%2F7n8u1htRLHOueC%2BEwLQAsLqaVTW1XbznoLj6%2B5Kq7TLV0WkDaHvIvXeJvG6LlaDyLdwF4zb0qR11qrLY%2By1802T0ePr5KvxgNMmtAOGvDwFYr48VdC5MKo1dD7hjtC4Z7NQ36pSgnaP4Lu4pm4J5KMSB1dRfqmtZ%2BbL4rJF9lyCdxDu&X-Amz-Signature=ffc1ceef1385d9161ae9f9a41d412379bac78146340677779cc949610b100206&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666WLZH5YS%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T052343Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIApx%2FWMnMbFb3SONaSRR7z9laXsPCMsKZ52dEACA6cIaAiEA8W81IjWYoERxeE%2Brp94LOubyxXpGexaPnrk3oyou%2FeQqiAQIzv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOHZjybT4bgBn5KGNSrcA5POVqzeOQxHDf%2FmY9Tb%2BPQe%2FPcqhitUft8yzvEUwTCv%2BG%2BX3yUURS%2F1qrqyMNobLSqkef97qoTViOP2J9oAKZ%2BA4ZCxDfyhtX64%2B5oLakse0dV4ReVeF%2FS%2FhqatRHCMTNx%2BeZtj2U75vm2JAnLqoEzD1%2Fq2Zc9tyP6JKjZOUZfmSZX11DJSO1jeR%2FB4oeViL9ANJ%2Bip2GYcAfJ9I2r4INIeVflKNzcPYFlzdLaonmXqt%2Bwr2DqizGwKiBfBHdXScr1WrqZI1fH7zdO7w32Aqe1ntN9L8TFQ8lylvPqVgnuN3QKiVF5sS6gq%2B7ygAHfWFECROr6adZAn%2FUa0vXi8ToAerGNwdSH3%2BKW4NSJF2bKaiGhD0LVzijLGJk9Vn7%2BNOCcF4Ab2Ydo%2FVb%2Bv3Xqy8uExzdGYY4Q%2F0GoXBMNalQCqKg3Q5ElU5bVaVxSN%2B0umYuV1YqNoRcuKXKU7aDfC18CaqyUUcl3FxMiBmos9Qo4Q7TJyUsPWvdTnPHjWJf2ZXAQDwiGcP2OqsDNSSs5%2BKF2bHSrlX09UJjkA7dFf%2BLH7%2BxFAvFtnE7FBtWI6YOIcgiLoYwcyFXE4IUsxJzp8RXAn6gvz3catWuJfEkVqryQwg0AnzbXVePtleIjBMPKF4L0GOqUBULz8%2BsTBz8%2BHUGpNF0h6IBXHC%2FS6S%2BtkwaJXhbIwjBZR%2F7n8u1htRLHOueC%2BEwLQAsLqaVTW1XbznoLj6%2B5Kq7TLV0WkDaHvIvXeJvG6LlaDyLdwF4zb0qR11qrLY%2By1802T0ePr5KvxgNMmtAOGvDwFYr48VdC5MKo1dD7hjtC4Z7NQ36pSgnaP4Lu4pm4J5KMSB1dRfqmtZ%2BbL4rJF9lyCdxDu&X-Amz-Signature=13d5ea34919861669d9f4e2c4f2c157b6e5bfdcf38984bba30cae233364a3316&X-Amz-SignedHeaders=host&x-id=GetObject)


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

