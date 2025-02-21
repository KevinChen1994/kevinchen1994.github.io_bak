---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466UTWOUAT4%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250221T183207Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjELL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBKY0qZ5w28Pq5%2FAi\
  J9PZPMq5rOmLIxlCyXLGgRteFI%2BAiEA1tMVrWUymAecIL3C26WztvMSXO3tw7tvGyUJSjtG5Twq\
  iAQI2%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDY%2F0Xn2aPjp4\
  pW99yrcA1NOwxb4zPkEZVd2c%2FAuJVtcWx6IA11MvUK%2BpVLtLxjqtvp19LAo5Bcno9daVJG17L\
  bbd13WKuimij4vPDd8EjB1UI9piXPM7cq7PepSrkBYNgl02%2FJgGNpD9gY%2FW8ItRE9%2BNOSw4\
  r%2FzQ9U7jn1SeUdHrO2dzqk1EzTEZ2tXGVP61LCnezqzeKLjQQqkh99tH22DHZM0P%2Fb%2FoAO4\
  btmr6jsRqC%2Bp3frcxl%2F5CSIr8F6lw9BOCiVKQEmOe2Do%2BCTX4V31HS7umqxQUNgN6M3FJLY\
  5r7aOscvAZgyFH%2B6UUaFWBuAS43EP%2Bs7jPVD8V4GQrSVokw9kS9w0zqhZgj6UvWus2D1Tp3bM\
  W29OJHrkBAKygnOoytsSIJQ%2FBxgv41fmYsPkjPwUUmLUrlY5EpMSXwK69A7d4%2BHUZxAIFO8av\
  lVm4lFDHcJUAQ88hu2ML5BnGwIaaMkeBGg%2FhtUQD5DhlKyEVgfwKZPOc3cV5%2Fd0iZ%2BLBhm6\
  WuRgQALgj2Z6huxovnMDIzyz2z0QO4k9Z0jLPWVKVFzZEEy1q1dRGyXXCDymJ9GVIMiPw%2BHYW%2\
  F792d07360u9bMSTPh0x9XegkJS3UcBdH%2BeScS%2FbtFyIO81QgtaKDvsUDMwFCK1TXq0ML2A47\
  0GOqUBbst6UPE8SL8IZSZcrp8gNfBqHG022TEbzFp%2FyNkCIOnvmVBUcLMTs4WYTBfmgU%2F5h1A\
  ACj0swrTBA9A87Lj%2FWXNXQoWLHsK8Qz2RkSG%2Fjgj22T4MrpUo%2BRgp7tJr%2F7n5d7I8cbnJ\
  nXc66kJfZIdqup7ODrC01jvigZqKAJc66zmcLOxTjVXkjzKEoaHwB28N6Fj8aFinhhY%2BsU%2BjJ\
  evb7DuuIsAg&X-Amz-Signature=c3fbe2283599c75923eb1fdb4886154d3d209e9921b1a39de\
  bce7e7ca3d86a55&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4664YEN6FZW%2F20250221%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250221T183036Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjELL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIG9uEZPw69HbLoOtd9UqlnkEHIG07%2F5qH%2BgYnlLl6xjVAiEA7sXhd4V8bo4ID4iU%2\
        FOhezgeNYOTG5aPv7si43NKIWyQqiAQI2%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAG\
        gw2Mzc0MjMxODM4MDUiDMwYEq%2BPCd85x%2FMKGyrcA%2BJilF84B9KOdtB0kaGFZQgBV1\
        buOLIS7lxtRRWEyPCgLOFsT0on9zjD%2FIG0rfFS%2BOBBj7xpHHl6ALViGYSp3YaihCxnm\
        TM1FsccrKGO1bT1L71iIetRrp3oyBmrJdwZdKV%2FwPJOFCPNHXZlTMdpK5u%2B3QfRVITI\
        OrxU1yGmIg1fizmWq6qLvxetgc4XgCKV2X6DYmDJhgLKRtoo6P%2FB6ZmlWOmeG5pqQgQ6v\
        phMzeav9zMExOanxNW7Cn9R9A1nNeDNm4VfkciKaBXON3OnncQebbKqmA93jTiG515FH9YS\
        bRAL1ilMCm%2FU9bZ7Kwj5836vKCGBDXxIkjIvpPFcM%2FfLK6m52s5E%2BynfQzJSmE7P%\
        2BLTucRa%2FHMe6ikjSPRAI6vhUmej%2B5EvA0ijGsFzWrVMRXFz5lcCzU%2FKpIg1Y0dWh\
        MheXXdTd%2FnFmz%2FnJ%2FG9VpYFO6b26muR8kiA0N1ZYVu6ex%2Fy22c0ggR%2BbLZxPw\
        pA79uey3L9VBMoX7E8%2F36uXL1YWtHX77QU9hjT3Waly0ej569TMWTDVRrIKcRyL7eQMzs\
        kcCgTDG4ReFvfaJeaNV%2BPrWmPHc%2BiCkGcXPpT8bqw72RQqK0IiF%2B5o8Udkq36ZMWx\
        xZbgtSVqIVznmMMCA470GOqUBSDorit6u83XhzSyGPYIJx7fUNhEeOpRYxRCa5XeN3FDnW8\
        y%2Ba3jz%2BSHSSZ9gW4GZT2lNGm5ZbJGif6DeXQn2As6DjcBEfct8opfRkUyCWWYYnFe62\
        jLDgvCjSyON7lfLSgxG9zB2EkY1Aor8FxNmLc2QNenqXgf0E7owMxBHDGxcRRPR0S%2BMlj\
        Csbjn%2BSJ5b234pM3Akcl8jEnQc8GcQUMxiGSN6&X-Amz-Signature=ad7b392e7af3b6\
        93194e2d8108b8d2495111996ba4a604ff185bc9229e88ff05&X-Amz-SignedHeaders=\
        host&x-id=GetObject"
      expiry_time: "2025-02-21T19:30:36.079Z"
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
UPDATE_TIME: "2025-02-21T18:32:18.275Z"
EXPIRY_TIME: "2025-02-21T19:32:04.141Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466343G4Z7Y%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T183205Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDIs9CQYR4IAN7rXLno2WDivpHZusAtK6697TwSQm1DywIhANt474kbwQy5TfgV5cTPslNvvRl7ueGA5FlMGsUf025nKogECNv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyUR2QAUtM2DWdG%2F%2F8q3ANQkIop2K11t8rPSTY76TyPm40F91buOjorEjC8LXFamL5OONsWFFP2Wxg3D1yvBZeFHlZpgEMHGO3mjxgLS1rCnSHuq5txdkkowDU81mVwBkltut%2FNjYSm0mcb2jsfRgBb9b8ulzpQFfD%2F4kAT7I038FyJcYtBhWtRy4OvVRMsXWtMyizVg%2FO7kaL9rIX94hsxer4yBGMQIavKRPer%2BXErAKtfwNI4MYazXfS86P7BoHUVm7biGZui08n8p9X7zr7SDucpPYoatdYsAQmkcPqyA1X58IzNB99SGuBzR4IV0GNsLNJq5JL7W%2B%2BEvg35%2FG3k6n9m2QHLR2Wq%2BHFE%2BBBeOnNsHune9WYMde7hA3KY%2F6iCsz1zZjo79v7Hnkcx76UfG0JeVfvbr4%2FcFMDrTeLqLtAV0rFq0Oj8x1L8PMzGjmedMcxFhO6IHlfdMO%2Fw5xh6Ol9mBSr4LmNO1rXQqG%2FAPvlXHOiJiND47mIekm3VYcySJV9kOs%2FMrPzv4jOOpZXtLfKYG7ZCz%2F58O7XvrWCkauGCak0Jd3ytoAHWg0GiBozLEbZMBF5UCp%2B60Pals%2BhJ6RnLBr%2FkyyR%2BbZQIRL%2FOFmIcfZaXp4Te60owl3GAxgPt3h5nEdH%2FL522KjDugOO9BjqkAZ0ofylyw6iphYYgYvx7lwpx27hZzw%2BgScnwuYwVksukvpUIX8h63WOfsNzCKGqovV0HjbM91FnwW8QgwDbA3vtRlF7tRQdU0gqn1kzhMce2lhwpuiggZm%2BGlnQIv68x1xS5V4fDBvn1Zwp7wjgmZgpw2WF3zwxmnYX9%2FjLa5mgVUXf%2BSeZF24zJzwnoxJ8O11WEQpVhqcJz%2F%2Fdyx5ySZK80nJ9B&X-Amz-Signature=df87d3205e075917739471c524b4c2a58ce945d3d4d3826a4c4b147e94fce6bf&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466343G4Z7Y%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T183205Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDIs9CQYR4IAN7rXLno2WDivpHZusAtK6697TwSQm1DywIhANt474kbwQy5TfgV5cTPslNvvRl7ueGA5FlMGsUf025nKogECNv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyUR2QAUtM2DWdG%2F%2F8q3ANQkIop2K11t8rPSTY76TyPm40F91buOjorEjC8LXFamL5OONsWFFP2Wxg3D1yvBZeFHlZpgEMHGO3mjxgLS1rCnSHuq5txdkkowDU81mVwBkltut%2FNjYSm0mcb2jsfRgBb9b8ulzpQFfD%2F4kAT7I038FyJcYtBhWtRy4OvVRMsXWtMyizVg%2FO7kaL9rIX94hsxer4yBGMQIavKRPer%2BXErAKtfwNI4MYazXfS86P7BoHUVm7biGZui08n8p9X7zr7SDucpPYoatdYsAQmkcPqyA1X58IzNB99SGuBzR4IV0GNsLNJq5JL7W%2B%2BEvg35%2FG3k6n9m2QHLR2Wq%2BHFE%2BBBeOnNsHune9WYMde7hA3KY%2F6iCsz1zZjo79v7Hnkcx76UfG0JeVfvbr4%2FcFMDrTeLqLtAV0rFq0Oj8x1L8PMzGjmedMcxFhO6IHlfdMO%2Fw5xh6Ol9mBSr4LmNO1rXQqG%2FAPvlXHOiJiND47mIekm3VYcySJV9kOs%2FMrPzv4jOOpZXtLfKYG7ZCz%2F58O7XvrWCkauGCak0Jd3ytoAHWg0GiBozLEbZMBF5UCp%2B60Pals%2BhJ6RnLBr%2FkyyR%2BbZQIRL%2FOFmIcfZaXp4Te60owl3GAxgPt3h5nEdH%2FL522KjDugOO9BjqkAZ0ofylyw6iphYYgYvx7lwpx27hZzw%2BgScnwuYwVksukvpUIX8h63WOfsNzCKGqovV0HjbM91FnwW8QgwDbA3vtRlF7tRQdU0gqn1kzhMce2lhwpuiggZm%2BGlnQIv68x1xS5V4fDBvn1Zwp7wjgmZgpw2WF3zwxmnYX9%2FjLa5mgVUXf%2BSeZF24zJzwnoxJ8O11WEQpVhqcJz%2F%2Fdyx5ySZK80nJ9B&X-Amz-Signature=4e82e557e1f11fec72ae29f0ea3eac0368dbd0aa1673d3268ffe628223d5bacb&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466343G4Z7Y%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T183205Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDIs9CQYR4IAN7rXLno2WDivpHZusAtK6697TwSQm1DywIhANt474kbwQy5TfgV5cTPslNvvRl7ueGA5FlMGsUf025nKogECNv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyUR2QAUtM2DWdG%2F%2F8q3ANQkIop2K11t8rPSTY76TyPm40F91buOjorEjC8LXFamL5OONsWFFP2Wxg3D1yvBZeFHlZpgEMHGO3mjxgLS1rCnSHuq5txdkkowDU81mVwBkltut%2FNjYSm0mcb2jsfRgBb9b8ulzpQFfD%2F4kAT7I038FyJcYtBhWtRy4OvVRMsXWtMyizVg%2FO7kaL9rIX94hsxer4yBGMQIavKRPer%2BXErAKtfwNI4MYazXfS86P7BoHUVm7biGZui08n8p9X7zr7SDucpPYoatdYsAQmkcPqyA1X58IzNB99SGuBzR4IV0GNsLNJq5JL7W%2B%2BEvg35%2FG3k6n9m2QHLR2Wq%2BHFE%2BBBeOnNsHune9WYMde7hA3KY%2F6iCsz1zZjo79v7Hnkcx76UfG0JeVfvbr4%2FcFMDrTeLqLtAV0rFq0Oj8x1L8PMzGjmedMcxFhO6IHlfdMO%2Fw5xh6Ol9mBSr4LmNO1rXQqG%2FAPvlXHOiJiND47mIekm3VYcySJV9kOs%2FMrPzv4jOOpZXtLfKYG7ZCz%2F58O7XvrWCkauGCak0Jd3ytoAHWg0GiBozLEbZMBF5UCp%2B60Pals%2BhJ6RnLBr%2FkyyR%2BbZQIRL%2FOFmIcfZaXp4Te60owl3GAxgPt3h5nEdH%2FL522KjDugOO9BjqkAZ0ofylyw6iphYYgYvx7lwpx27hZzw%2BgScnwuYwVksukvpUIX8h63WOfsNzCKGqovV0HjbM91FnwW8QgwDbA3vtRlF7tRQdU0gqn1kzhMce2lhwpuiggZm%2BGlnQIv68x1xS5V4fDBvn1Zwp7wjgmZgpw2WF3zwxmnYX9%2FjLa5mgVUXf%2BSeZF24zJzwnoxJ8O11WEQpVhqcJz%2F%2Fdyx5ySZK80nJ9B&X-Amz-Signature=87a708785cba6d89214f99aa08d5498baa0d870d62efd1646e83744abbc0bec8&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466343G4Z7Y%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T183205Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDIs9CQYR4IAN7rXLno2WDivpHZusAtK6697TwSQm1DywIhANt474kbwQy5TfgV5cTPslNvvRl7ueGA5FlMGsUf025nKogECNv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyUR2QAUtM2DWdG%2F%2F8q3ANQkIop2K11t8rPSTY76TyPm40F91buOjorEjC8LXFamL5OONsWFFP2Wxg3D1yvBZeFHlZpgEMHGO3mjxgLS1rCnSHuq5txdkkowDU81mVwBkltut%2FNjYSm0mcb2jsfRgBb9b8ulzpQFfD%2F4kAT7I038FyJcYtBhWtRy4OvVRMsXWtMyizVg%2FO7kaL9rIX94hsxer4yBGMQIavKRPer%2BXErAKtfwNI4MYazXfS86P7BoHUVm7biGZui08n8p9X7zr7SDucpPYoatdYsAQmkcPqyA1X58IzNB99SGuBzR4IV0GNsLNJq5JL7W%2B%2BEvg35%2FG3k6n9m2QHLR2Wq%2BHFE%2BBBeOnNsHune9WYMde7hA3KY%2F6iCsz1zZjo79v7Hnkcx76UfG0JeVfvbr4%2FcFMDrTeLqLtAV0rFq0Oj8x1L8PMzGjmedMcxFhO6IHlfdMO%2Fw5xh6Ol9mBSr4LmNO1rXQqG%2FAPvlXHOiJiND47mIekm3VYcySJV9kOs%2FMrPzv4jOOpZXtLfKYG7ZCz%2F58O7XvrWCkauGCak0Jd3ytoAHWg0GiBozLEbZMBF5UCp%2B60Pals%2BhJ6RnLBr%2FkyyR%2BbZQIRL%2FOFmIcfZaXp4Te60owl3GAxgPt3h5nEdH%2FL522KjDugOO9BjqkAZ0ofylyw6iphYYgYvx7lwpx27hZzw%2BgScnwuYwVksukvpUIX8h63WOfsNzCKGqovV0HjbM91FnwW8QgwDbA3vtRlF7tRQdU0gqn1kzhMce2lhwpuiggZm%2BGlnQIv68x1xS5V4fDBvn1Zwp7wjgmZgpw2WF3zwxmnYX9%2FjLa5mgVUXf%2BSeZF24zJzwnoxJ8O11WEQpVhqcJz%2F%2Fdyx5ySZK80nJ9B&X-Amz-Signature=b9f3a5965120089ce30c9b681a29ebb52dfec6c07a97c7bf2399dc624d3ce021&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466343G4Z7Y%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T183205Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDIs9CQYR4IAN7rXLno2WDivpHZusAtK6697TwSQm1DywIhANt474kbwQy5TfgV5cTPslNvvRl7ueGA5FlMGsUf025nKogECNv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyUR2QAUtM2DWdG%2F%2F8q3ANQkIop2K11t8rPSTY76TyPm40F91buOjorEjC8LXFamL5OONsWFFP2Wxg3D1yvBZeFHlZpgEMHGO3mjxgLS1rCnSHuq5txdkkowDU81mVwBkltut%2FNjYSm0mcb2jsfRgBb9b8ulzpQFfD%2F4kAT7I038FyJcYtBhWtRy4OvVRMsXWtMyizVg%2FO7kaL9rIX94hsxer4yBGMQIavKRPer%2BXErAKtfwNI4MYazXfS86P7BoHUVm7biGZui08n8p9X7zr7SDucpPYoatdYsAQmkcPqyA1X58IzNB99SGuBzR4IV0GNsLNJq5JL7W%2B%2BEvg35%2FG3k6n9m2QHLR2Wq%2BHFE%2BBBeOnNsHune9WYMde7hA3KY%2F6iCsz1zZjo79v7Hnkcx76UfG0JeVfvbr4%2FcFMDrTeLqLtAV0rFq0Oj8x1L8PMzGjmedMcxFhO6IHlfdMO%2Fw5xh6Ol9mBSr4LmNO1rXQqG%2FAPvlXHOiJiND47mIekm3VYcySJV9kOs%2FMrPzv4jOOpZXtLfKYG7ZCz%2F58O7XvrWCkauGCak0Jd3ytoAHWg0GiBozLEbZMBF5UCp%2B60Pals%2BhJ6RnLBr%2FkyyR%2BbZQIRL%2FOFmIcfZaXp4Te60owl3GAxgPt3h5nEdH%2FL522KjDugOO9BjqkAZ0ofylyw6iphYYgYvx7lwpx27hZzw%2BgScnwuYwVksukvpUIX8h63WOfsNzCKGqovV0HjbM91FnwW8QgwDbA3vtRlF7tRQdU0gqn1kzhMce2lhwpuiggZm%2BGlnQIv68x1xS5V4fDBvn1Zwp7wjgmZgpw2WF3zwxmnYX9%2FjLa5mgVUXf%2BSeZF24zJzwnoxJ8O11WEQpVhqcJz%2F%2Fdyx5ySZK80nJ9B&X-Amz-Signature=4bb1152762e8f0bf332163c98a6d322ced0aea12837f5b9668e067c65ec4f16f&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WRMRIEZN%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T183206Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIGlNKZwr3pHDdDaM7xB09UHHdEElO8b3XFPZF5G4xovpAiEA1KNM4QcIXG3d1HSfMWScw0lNXVDasHG3mvPV6OItMj8qiAQI2%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLx3RF2dRwnxxN933yrcAzXRCV43%2BrRJSKZVMiysYkuyoBsGVH8rJ0ekvl5En60k%2Fjf%2F%2FGswB8e8XxeEqAK4fTLnPGigJ79r1iYaXpD%2BxfDa4SpYAzuEwr8JZSab31e2aJk3Ky224h8eALQNdEPDFvvaCHX4wVdXZeV0gvnF84xLYY3WvGmkEj3Jn%2FeQuTr9qqU5UkQ3CQ5s497aZ0x1mEbkyz837ovtwJux0mulPcIe4j7P%2B03pFTA2AQgRM69ETEpgtXExplGEPNLdFeefIdAqgqt1WfN12uJHyAOXj7%2FpSaElHl6%2B9kwRHLLHnyhK3ynwNFJ9KU0nrLV%2BOavNrMAN59x4VVvF5QSNj2bwmH7LHj9cQwhD6FYrq7DiA6jepnf5NoSxpny3eiIIJdR2fqqOwj2QFL%2Fp7e6H5Jk%2BwQj1nairrU2tmEBPpwFJ9BDu1cPOusqB56S1WCWSnB05bruH63E8Oo%2BfcisU4ZP86MF1D%2Fl2d2xb0DpuYMunYsmWQ%2FmqFJPX%2FcEyVdpErZsh04veNLWR4sgX81Fzw8OUyb5Q%2BXkFOQk2zf1T69rYp2AoTz80TreLtG1s0Uy%2F4P8%2F75U5CD7IPtoYj3Gy0M2SmJxEXWgwQd%2BGkb52jHqgfb1BmMGWse9fC%2FEhJdqXMK%2BB470GOqUB6EbfwMAjplbg24Pf7MHLXijdQfbjo4ZXZsOFQdnlskfHHDIHNJ5Sg4zWBc%2Fh3lVL9nW3dGXvBsBoY85iqz1c1TXCCRPpz65ANkWNAceKd%2F2Vmp30NJdcgF1SIMhiWOZ8qoRaqj3nlDHBZRMAHMqq7iSv5qJttLLkN2QnZiBlhYc1XgkDTfHj3u%2FGSsRsUKijp%2B3fyChk734MEDEdcQCgdYkOkipK&X-Amz-Signature=f4aa7e0259fdaa94b6c9772a05f9aa23b1480e281b373ffb4f00581bb4e656de&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466S6ZQCEZ2%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T183206Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCrmsRdHDqQcntyQaDCVk7IuIZdLsyEAiMUYsmJr847BAIhAOOrZry4p0mDIBMVPg6Lk8Ixi0zVlKgGPMqB9hnwkIJsKogECNv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyPoGdjoo73vQzkkQIq3AOFACXlt75sI%2FMAJZ2xrYc9SfAIZxSwQP727EIfkv9jACOPLcrBfUDOBl%2BeRX%2BHzK4RxZr4h3rZKTqCrUiN4NNsiGW8GFTc%2FAhOJx90bR5HT2hrRn9XDNn29zyLHazKwYnNhTPmtVOE8tdyYQm9iSjw059tgUvHJ5nNcKM%2FGCoPGhEtO8r%2F%2FIrA%2BiwxgRs9unJh2VdCx77yVKSDIWYCTUxb8EMiILDY5xFcLwbfLHkB70IrdOM0v36g2lstNRxDaOAB49Q2um4cN4IhULMbpf5JucL0NVrX9HK74pnWqjNBG3IDujwEvH%2BsNUtY%2BSeRTzuFl5mSPKXyvKFmBUQjKQKtoT9taQErdHS4bPItjVmxSgy4IBwat4d%2Fg3YLINpW5D8cGFWDj%2BNIvfzL1B%2Bovu3YJzNX%2BnuhcUdzU8G1bZAPMLcUBpMmnHFCMilMd28db0LrCM0Lz65qsJCu8b%2BGMhIkYJSeOi%2F9xPgJFm2bQpEhwEsEAvw%2BPpdIbTLOBZ8nKRj9CqEsBvlyV38NzaGakgDWcC3i6AWlLVZfI%2BALnyhPD2HGKysTAylDZJ0UxH0b7mDZJGd%2BQk5WLoPbesFJJS6M%2FkO3h9urpDGvVxjr1dM%2F85eXUur89CjL9vKb9zDagOO9BjqkAYM0y%2BQGqmfmU%2BLHpr%2Fd0A00WuL9k%2FAYMLn%2BMjxS1irlCH77QmWZ8xoCutMCpII4S1YVlhjUDA11ldyvf0jDw7QrORJcqYTQgsqlFkQqXHtTJZpQlv68xvngL42gX0MnwwErafv1rKToC6ARBlXOzXVAzbqNtDnigle062tKKpjHGtXsWUUOi9xdcCF9PX0FrWko4v7ZhUAlrtfRFQZVLvuGtiq0&X-Amz-Signature=e8700d88e52939697fc517ccd855fd3ef9afc2e9bebd7eb214311be6bea1d0d7&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466343G4Z7Y%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T183205Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDIs9CQYR4IAN7rXLno2WDivpHZusAtK6697TwSQm1DywIhANt474kbwQy5TfgV5cTPslNvvRl7ueGA5FlMGsUf025nKogECNv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyUR2QAUtM2DWdG%2F%2F8q3ANQkIop2K11t8rPSTY76TyPm40F91buOjorEjC8LXFamL5OONsWFFP2Wxg3D1yvBZeFHlZpgEMHGO3mjxgLS1rCnSHuq5txdkkowDU81mVwBkltut%2FNjYSm0mcb2jsfRgBb9b8ulzpQFfD%2F4kAT7I038FyJcYtBhWtRy4OvVRMsXWtMyizVg%2FO7kaL9rIX94hsxer4yBGMQIavKRPer%2BXErAKtfwNI4MYazXfS86P7BoHUVm7biGZui08n8p9X7zr7SDucpPYoatdYsAQmkcPqyA1X58IzNB99SGuBzR4IV0GNsLNJq5JL7W%2B%2BEvg35%2FG3k6n9m2QHLR2Wq%2BHFE%2BBBeOnNsHune9WYMde7hA3KY%2F6iCsz1zZjo79v7Hnkcx76UfG0JeVfvbr4%2FcFMDrTeLqLtAV0rFq0Oj8x1L8PMzGjmedMcxFhO6IHlfdMO%2Fw5xh6Ol9mBSr4LmNO1rXQqG%2FAPvlXHOiJiND47mIekm3VYcySJV9kOs%2FMrPzv4jOOpZXtLfKYG7ZCz%2F58O7XvrWCkauGCak0Jd3ytoAHWg0GiBozLEbZMBF5UCp%2B60Pals%2BhJ6RnLBr%2FkyyR%2BbZQIRL%2FOFmIcfZaXp4Te60owl3GAxgPt3h5nEdH%2FL522KjDugOO9BjqkAZ0ofylyw6iphYYgYvx7lwpx27hZzw%2BgScnwuYwVksukvpUIX8h63WOfsNzCKGqovV0HjbM91FnwW8QgwDbA3vtRlF7tRQdU0gqn1kzhMce2lhwpuiggZm%2BGlnQIv68x1xS5V4fDBvn1Zwp7wjgmZgpw2WF3zwxmnYX9%2FjLa5mgVUXf%2BSeZF24zJzwnoxJ8O11WEQpVhqcJz%2F%2Fdyx5ySZK80nJ9B&X-Amz-Signature=cd5952ba508e31b37297cde3fc540e4e41d4bfae85e707b00444cc4b78fcf5db&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466343G4Z7Y%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T183205Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDIs9CQYR4IAN7rXLno2WDivpHZusAtK6697TwSQm1DywIhANt474kbwQy5TfgV5cTPslNvvRl7ueGA5FlMGsUf025nKogECNv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyUR2QAUtM2DWdG%2F%2F8q3ANQkIop2K11t8rPSTY76TyPm40F91buOjorEjC8LXFamL5OONsWFFP2Wxg3D1yvBZeFHlZpgEMHGO3mjxgLS1rCnSHuq5txdkkowDU81mVwBkltut%2FNjYSm0mcb2jsfRgBb9b8ulzpQFfD%2F4kAT7I038FyJcYtBhWtRy4OvVRMsXWtMyizVg%2FO7kaL9rIX94hsxer4yBGMQIavKRPer%2BXErAKtfwNI4MYazXfS86P7BoHUVm7biGZui08n8p9X7zr7SDucpPYoatdYsAQmkcPqyA1X58IzNB99SGuBzR4IV0GNsLNJq5JL7W%2B%2BEvg35%2FG3k6n9m2QHLR2Wq%2BHFE%2BBBeOnNsHune9WYMde7hA3KY%2F6iCsz1zZjo79v7Hnkcx76UfG0JeVfvbr4%2FcFMDrTeLqLtAV0rFq0Oj8x1L8PMzGjmedMcxFhO6IHlfdMO%2Fw5xh6Ol9mBSr4LmNO1rXQqG%2FAPvlXHOiJiND47mIekm3VYcySJV9kOs%2FMrPzv4jOOpZXtLfKYG7ZCz%2F58O7XvrWCkauGCak0Jd3ytoAHWg0GiBozLEbZMBF5UCp%2B60Pals%2BhJ6RnLBr%2FkyyR%2BbZQIRL%2FOFmIcfZaXp4Te60owl3GAxgPt3h5nEdH%2FL522KjDugOO9BjqkAZ0ofylyw6iphYYgYvx7lwpx27hZzw%2BgScnwuYwVksukvpUIX8h63WOfsNzCKGqovV0HjbM91FnwW8QgwDbA3vtRlF7tRQdU0gqn1kzhMce2lhwpuiggZm%2BGlnQIv68x1xS5V4fDBvn1Zwp7wjgmZgpw2WF3zwxmnYX9%2FjLa5mgVUXf%2BSeZF24zJzwnoxJ8O11WEQpVhqcJz%2F%2Fdyx5ySZK80nJ9B&X-Amz-Signature=b705b23318a58908b3ce44e90224ee16540f1c0ccbc5908b3b431c1668c2bf1a&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466343G4Z7Y%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T183205Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDIs9CQYR4IAN7rXLno2WDivpHZusAtK6697TwSQm1DywIhANt474kbwQy5TfgV5cTPslNvvRl7ueGA5FlMGsUf025nKogECNv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyUR2QAUtM2DWdG%2F%2F8q3ANQkIop2K11t8rPSTY76TyPm40F91buOjorEjC8LXFamL5OONsWFFP2Wxg3D1yvBZeFHlZpgEMHGO3mjxgLS1rCnSHuq5txdkkowDU81mVwBkltut%2FNjYSm0mcb2jsfRgBb9b8ulzpQFfD%2F4kAT7I038FyJcYtBhWtRy4OvVRMsXWtMyizVg%2FO7kaL9rIX94hsxer4yBGMQIavKRPer%2BXErAKtfwNI4MYazXfS86P7BoHUVm7biGZui08n8p9X7zr7SDucpPYoatdYsAQmkcPqyA1X58IzNB99SGuBzR4IV0GNsLNJq5JL7W%2B%2BEvg35%2FG3k6n9m2QHLR2Wq%2BHFE%2BBBeOnNsHune9WYMde7hA3KY%2F6iCsz1zZjo79v7Hnkcx76UfG0JeVfvbr4%2FcFMDrTeLqLtAV0rFq0Oj8x1L8PMzGjmedMcxFhO6IHlfdMO%2Fw5xh6Ol9mBSr4LmNO1rXQqG%2FAPvlXHOiJiND47mIekm3VYcySJV9kOs%2FMrPzv4jOOpZXtLfKYG7ZCz%2F58O7XvrWCkauGCak0Jd3ytoAHWg0GiBozLEbZMBF5UCp%2B60Pals%2BhJ6RnLBr%2FkyyR%2BbZQIRL%2FOFmIcfZaXp4Te60owl3GAxgPt3h5nEdH%2FL522KjDugOO9BjqkAZ0ofylyw6iphYYgYvx7lwpx27hZzw%2BgScnwuYwVksukvpUIX8h63WOfsNzCKGqovV0HjbM91FnwW8QgwDbA3vtRlF7tRQdU0gqn1kzhMce2lhwpuiggZm%2BGlnQIv68x1xS5V4fDBvn1Zwp7wjgmZgpw2WF3zwxmnYX9%2FjLa5mgVUXf%2BSeZF24zJzwnoxJ8O11WEQpVhqcJz%2F%2Fdyx5ySZK80nJ9B&X-Amz-Signature=a402366827e2925c50b33ffa78eb06182494f3f470b75fdc71c1b9cf1c92217f&X-Amz-SignedHeaders=host&x-id=GetObject)


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

