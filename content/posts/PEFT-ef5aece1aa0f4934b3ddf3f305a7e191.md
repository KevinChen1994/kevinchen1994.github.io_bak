---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4664DWIZ3MO%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250220T191913Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEJv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDIWAEi854AR6W4m%2\
  FaNvdZcmfaJbUHC60EnUdHhDpsetQIhALX5Q3K8vX2r4a4SfzIyvJQc5AYfvFLXRDD4L6hjFl1fKo\
  gECMT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwYItfLZQKOFY53bCY\
  q3APj8son0SjUVUPl1cVLPPF4TwCWya3WumEQG5soBWqOQh1HTZLx5V%2BF8twZ5P5Kl9bPLRW0eT\
  QrztmCYJYd%2FFjoG9S%2FmWd6jztfOi2BHclMCYdU%2BpAQsVhQQ%2BIIjMFDoP2gFIi4Pp1x7pl\
  nEHgRklB0N2FxR4jXdDvHShSoIyveky3bJTMvAOlUd20Y%2BEDFrzoJNqad%2BlZpgLdXnVN2kmoO\
  M6qgm12Ix4cLuD%2BIHAL6qAxT3ZqXv6BZyzBSdZvzH%2BA%2FnPz638AFObnvBaQqQw5pDssYbdq\
  mPUAbc7Uwo9x3VGHOy30%2F2kk8AYu8W%2FYicAl%2F0g%2FZzLfPLm5hbagWY0UnrAddBTZLqYmG\
  coq9YJvqXWG7oOX3cX9sV1HC7gY%2Bf%2FRJDBZ4y2LMcZwHEpMapGjji0mpmVOmkUh7MkfkpUP4w\
  MI03Mn0S2HGvV2nwKX%2F%2F8EIEdb8CNws%2BuUNcyqxvTOUVvH4T0QejlhVVQs7o49y%2FKW8bH\
  b%2BiIycwKRtJfv6DKrcyr9w3uJJ8uIIxPb%2Bx5NQt3vxq1crLlRW1FGB4DgLQkfyzIMpEZnfDbY\
  D9TcjDKoJ1meJGSNwDdeKcMmP8MEzMohG2k7SDTyNXJB35Uqy3alhhLnM9%2Betm39k%2FjCn8N29\
  BjqkAa2OX96eLlyqXnmH%2BKDfXgPDV5G98jP4c%2FdBFInHqQ7c7q1tvSW5JW%2BKF3qWjbayLXr\
  xTJFyB6OdrwPrOLi%2By2Ulu9zrZUsLWRDfqe01WZQFGVWZy8DkG8YYPT0LK54oxMKH7S1ZZTSPCh\
  iyVsMSGZL7nj7pyoBRC%2FiD2b%2BU8JCHbKJte9xAx9pMcBNaUmEhyke74j1JxI4mjN8e0HPwuLX\
  WVK9c&X-Amz-Signature=741bf5fd5502f15ffd30331efa0841296aa5ce95019ea9d9f534bce\
  cbbbee6fe&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466RNIKNTUS%2F20250220%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250220T191757Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEJv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIFqguRaOa%2FWbcesPO3MtntRroe25ifnuf%2Fb%2BH0nutBgTAiEAq9TmOIOkFDONB8NC\
        ZOJrRqDonZDaTB1j8oCNCAt9JW8qiAQIxP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw\
        2Mzc0MjMxODM4MDUiDFYVnTi3b1bphXfywCrcA8DFqIF9NnhyXnW%2BIkOKhpwOxOj3xeYE\
        LCMOqTAvfN0%2FVg6RVCSp8z9OaI0vm5hpEgPEc8KU97YQ1bma7k0tktt%2BanO5I%2BBIa\
        bgjL91Ypy05OfsLxiHN3gV7bqqRVYVYIReYHDu3RG4%2B6EvLZ5Hd4%2Ftv35QoW9n7CobJ\
        d%2B5HVJPx9f%2BwBZeR1QG38QTRKUgLff0duLENEu%2Bm0v0N3s2TCFAC5QrokyTGp12uD\
        Kgl%2FuZI59HdluwPXch%2FojyyuVTlSLAKcapO9ytSkejaapDkltGDq3sv7qx5j%2FpjiD\
        zR67sr3mATPwvUogUrVsbkXGYsuEbtnO3f7gwAL6Z6lYFNpyRWo%2B%2BhNtb0WR4YGxito\
        IEbMEKvvqAEzKJQwq%2FYOVoziKWOp9qSNcIkr8wLAkT1YeV5e2xk8reSjL%2BzK%2Fu%2F\
        cIClrirW%2FHk3NkiC4kwgL%2BJDpi5OACr80YkdYFC%2FjJSbx5aWPLGdNL8kWSJjc3ebu\
        rwNTlV3DqN55bIqeYArgmo%2FVqvL8Vc86zKPVHtoNCzclBtF5iOLknFw0UxKhNALMpyRAH\
        0QbVqRr7dRs1ySeIdD9kfIyPTZpQ0SwDJMq48ZooCa6V1UGNz2BzqWINu0TJpb7f%2FpJ81\
        V2koo1A7vMJnw3b0GOqUBTtMxEPRY3G5VtSeLqGPG3705weCHEVbQwtpNGcHJzElUDauRNp\
        lz%2BmpnonZKuGPks470sW9EaMZSOotrgns7tnl26xfMMGEMPXyYFmctvm5fP1gBuYwVFhi\
        46tS89rNtEc7IMyEwHxN4BALUANGJPR4u23zyA2hEW68p7XGxSJ4%2BzUKaAWMoy40BwoIU\
        1nB5VFAYVSRMvG3ReM%2BIjqx20Nbk%2BXS1&X-Amz-Signature=e14335e32b229c5da3\
        a6b35c32a472d882d606f9f5460fb5776c1d8b21d464ec&X-Amz-SignedHeaders=host\
        &x-id=GetObject"
      expiry_time: "2025-02-20T20:17:57.136Z"
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
UPDATE_TIME: "2025-02-20T19:19:21.741Z"
EXPIRY_TIME: "2025-02-20T20:19:10.687Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SOCI73TU%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T191911Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDZNR0%2Bi6vhoPiQQvdJS7fNFwHmDcVmHbPWH4VexPe6KQIhAPdaQ%2FBWEQeuXI117v7SmVlJ%2BxQj60IlOakuEoxq1sxqKogECMT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyiEZmT7CsOKXiNIRAq3AO7kYQtlLWF2zvcXt5BVTIW6%2BLG2LEcM7O1hv1c193OfUF3YYJTAEs%2BeCETGZkJWFHtVCwqNdyis%2Fs9U1Ym5quCYOxH6hOGDvhi7GF3Bjg4u9oeZV5G2y6ABa2wq9MR5hn906FUawn%2FOMDGAF1hqpP1LQVnUjQgaxHDnhQRh7lF5dxqeM64h5Vr09b00D%2Fae5IzLw%2FPo7TIvHi9PN%2BR8Xz3paefDNltbx8fV4%2BYWZZACBqx9kcaxDDOYR2TCv1BnUjl6ZPIzuNOkaJsBRdc2gFU0xzIiajoA4gomQTvKart7aaUKCxnloxL5e1IH6yZJMWf0lN8G%2BBMZSjwWm06owzx5pEIY14lFwxAzyCCpQSgqSCaaEuqhytnZW%2B4Rh1jA9l6cBEXE2O59qqTDU%2B0oN86OkssKaEPxQ5HohFqE43hGREKb3v6OFvWX25T1QN9blKVhS9VFn36xAHyo5dQg21xQ9SBtX%2BEv7MQznRqdwiwg%2FutIaYbTC8sC3vyGCmjEW2YkkZTlJrYuBcwSSeTfb0M6qE68y%2F0uf%2FPsxELGqYGB2HM8eRRKet1WIIFzyXseGAWu1W9wX1s0MyCaPirKg6qiGGdc6IPZ03NVYK8gDDLUJERJYb%2F8D1dp%2F1bzjDA8d29BjqkATeg7abCwAfXdrTf%2Bdgnqb1ee6ycD8XIvMWMX5RvgWx8p0rNGxTLxFpngzyz%2FYmO3%2Bu4xbf1KGuVuKkaVQehk4kFfKWJ82zDL%2Bm2jWQU1XTfbikAiLUTmv1gsHkHwpFSXyCbPnWwFa%2B1ZDQkk9WFuyaIC3DfQJ%2ForcM8NRJ4pvOWQI1kbr%2BUpYP5QXxb%2Blap2Uzz5xmUQXYTxyJ2qAxxmYk88G22&X-Amz-Signature=0b13fd4c4b41f53603fad7983f0e1dac3221b898dc0e807fb033164d8e3132c2&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SOCI73TU%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T191911Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDZNR0%2Bi6vhoPiQQvdJS7fNFwHmDcVmHbPWH4VexPe6KQIhAPdaQ%2FBWEQeuXI117v7SmVlJ%2BxQj60IlOakuEoxq1sxqKogECMT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyiEZmT7CsOKXiNIRAq3AO7kYQtlLWF2zvcXt5BVTIW6%2BLG2LEcM7O1hv1c193OfUF3YYJTAEs%2BeCETGZkJWFHtVCwqNdyis%2Fs9U1Ym5quCYOxH6hOGDvhi7GF3Bjg4u9oeZV5G2y6ABa2wq9MR5hn906FUawn%2FOMDGAF1hqpP1LQVnUjQgaxHDnhQRh7lF5dxqeM64h5Vr09b00D%2Fae5IzLw%2FPo7TIvHi9PN%2BR8Xz3paefDNltbx8fV4%2BYWZZACBqx9kcaxDDOYR2TCv1BnUjl6ZPIzuNOkaJsBRdc2gFU0xzIiajoA4gomQTvKart7aaUKCxnloxL5e1IH6yZJMWf0lN8G%2BBMZSjwWm06owzx5pEIY14lFwxAzyCCpQSgqSCaaEuqhytnZW%2B4Rh1jA9l6cBEXE2O59qqTDU%2B0oN86OkssKaEPxQ5HohFqE43hGREKb3v6OFvWX25T1QN9blKVhS9VFn36xAHyo5dQg21xQ9SBtX%2BEv7MQznRqdwiwg%2FutIaYbTC8sC3vyGCmjEW2YkkZTlJrYuBcwSSeTfb0M6qE68y%2F0uf%2FPsxELGqYGB2HM8eRRKet1WIIFzyXseGAWu1W9wX1s0MyCaPirKg6qiGGdc6IPZ03NVYK8gDDLUJERJYb%2F8D1dp%2F1bzjDA8d29BjqkATeg7abCwAfXdrTf%2Bdgnqb1ee6ycD8XIvMWMX5RvgWx8p0rNGxTLxFpngzyz%2FYmO3%2Bu4xbf1KGuVuKkaVQehk4kFfKWJ82zDL%2Bm2jWQU1XTfbikAiLUTmv1gsHkHwpFSXyCbPnWwFa%2B1ZDQkk9WFuyaIC3DfQJ%2ForcM8NRJ4pvOWQI1kbr%2BUpYP5QXxb%2Blap2Uzz5xmUQXYTxyJ2qAxxmYk88G22&X-Amz-Signature=005df219ae2e8cf3dd08a60d41e9d5302f86fa7cbd1d067cd3a08f0ca8d6501d&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SOCI73TU%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T191911Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDZNR0%2Bi6vhoPiQQvdJS7fNFwHmDcVmHbPWH4VexPe6KQIhAPdaQ%2FBWEQeuXI117v7SmVlJ%2BxQj60IlOakuEoxq1sxqKogECMT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyiEZmT7CsOKXiNIRAq3AO7kYQtlLWF2zvcXt5BVTIW6%2BLG2LEcM7O1hv1c193OfUF3YYJTAEs%2BeCETGZkJWFHtVCwqNdyis%2Fs9U1Ym5quCYOxH6hOGDvhi7GF3Bjg4u9oeZV5G2y6ABa2wq9MR5hn906FUawn%2FOMDGAF1hqpP1LQVnUjQgaxHDnhQRh7lF5dxqeM64h5Vr09b00D%2Fae5IzLw%2FPo7TIvHi9PN%2BR8Xz3paefDNltbx8fV4%2BYWZZACBqx9kcaxDDOYR2TCv1BnUjl6ZPIzuNOkaJsBRdc2gFU0xzIiajoA4gomQTvKart7aaUKCxnloxL5e1IH6yZJMWf0lN8G%2BBMZSjwWm06owzx5pEIY14lFwxAzyCCpQSgqSCaaEuqhytnZW%2B4Rh1jA9l6cBEXE2O59qqTDU%2B0oN86OkssKaEPxQ5HohFqE43hGREKb3v6OFvWX25T1QN9blKVhS9VFn36xAHyo5dQg21xQ9SBtX%2BEv7MQznRqdwiwg%2FutIaYbTC8sC3vyGCmjEW2YkkZTlJrYuBcwSSeTfb0M6qE68y%2F0uf%2FPsxELGqYGB2HM8eRRKet1WIIFzyXseGAWu1W9wX1s0MyCaPirKg6qiGGdc6IPZ03NVYK8gDDLUJERJYb%2F8D1dp%2F1bzjDA8d29BjqkATeg7abCwAfXdrTf%2Bdgnqb1ee6ycD8XIvMWMX5RvgWx8p0rNGxTLxFpngzyz%2FYmO3%2Bu4xbf1KGuVuKkaVQehk4kFfKWJ82zDL%2Bm2jWQU1XTfbikAiLUTmv1gsHkHwpFSXyCbPnWwFa%2B1ZDQkk9WFuyaIC3DfQJ%2ForcM8NRJ4pvOWQI1kbr%2BUpYP5QXxb%2Blap2Uzz5xmUQXYTxyJ2qAxxmYk88G22&X-Amz-Signature=e21ef9a0791f8665562e87bb173c83d85a2b90926468f4c82a1f7abf262d2d9a&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SOCI73TU%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T191911Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDZNR0%2Bi6vhoPiQQvdJS7fNFwHmDcVmHbPWH4VexPe6KQIhAPdaQ%2FBWEQeuXI117v7SmVlJ%2BxQj60IlOakuEoxq1sxqKogECMT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyiEZmT7CsOKXiNIRAq3AO7kYQtlLWF2zvcXt5BVTIW6%2BLG2LEcM7O1hv1c193OfUF3YYJTAEs%2BeCETGZkJWFHtVCwqNdyis%2Fs9U1Ym5quCYOxH6hOGDvhi7GF3Bjg4u9oeZV5G2y6ABa2wq9MR5hn906FUawn%2FOMDGAF1hqpP1LQVnUjQgaxHDnhQRh7lF5dxqeM64h5Vr09b00D%2Fae5IzLw%2FPo7TIvHi9PN%2BR8Xz3paefDNltbx8fV4%2BYWZZACBqx9kcaxDDOYR2TCv1BnUjl6ZPIzuNOkaJsBRdc2gFU0xzIiajoA4gomQTvKart7aaUKCxnloxL5e1IH6yZJMWf0lN8G%2BBMZSjwWm06owzx5pEIY14lFwxAzyCCpQSgqSCaaEuqhytnZW%2B4Rh1jA9l6cBEXE2O59qqTDU%2B0oN86OkssKaEPxQ5HohFqE43hGREKb3v6OFvWX25T1QN9blKVhS9VFn36xAHyo5dQg21xQ9SBtX%2BEv7MQznRqdwiwg%2FutIaYbTC8sC3vyGCmjEW2YkkZTlJrYuBcwSSeTfb0M6qE68y%2F0uf%2FPsxELGqYGB2HM8eRRKet1WIIFzyXseGAWu1W9wX1s0MyCaPirKg6qiGGdc6IPZ03NVYK8gDDLUJERJYb%2F8D1dp%2F1bzjDA8d29BjqkATeg7abCwAfXdrTf%2Bdgnqb1ee6ycD8XIvMWMX5RvgWx8p0rNGxTLxFpngzyz%2FYmO3%2Bu4xbf1KGuVuKkaVQehk4kFfKWJ82zDL%2Bm2jWQU1XTfbikAiLUTmv1gsHkHwpFSXyCbPnWwFa%2B1ZDQkk9WFuyaIC3DfQJ%2ForcM8NRJ4pvOWQI1kbr%2BUpYP5QXxb%2Blap2Uzz5xmUQXYTxyJ2qAxxmYk88G22&X-Amz-Signature=93734e1c76ad47cd8419958c456e573f758d2c8dfa3d9b613cd06d5ffd4b1b1b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SOCI73TU%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T191911Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDZNR0%2Bi6vhoPiQQvdJS7fNFwHmDcVmHbPWH4VexPe6KQIhAPdaQ%2FBWEQeuXI117v7SmVlJ%2BxQj60IlOakuEoxq1sxqKogECMT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyiEZmT7CsOKXiNIRAq3AO7kYQtlLWF2zvcXt5BVTIW6%2BLG2LEcM7O1hv1c193OfUF3YYJTAEs%2BeCETGZkJWFHtVCwqNdyis%2Fs9U1Ym5quCYOxH6hOGDvhi7GF3Bjg4u9oeZV5G2y6ABa2wq9MR5hn906FUawn%2FOMDGAF1hqpP1LQVnUjQgaxHDnhQRh7lF5dxqeM64h5Vr09b00D%2Fae5IzLw%2FPo7TIvHi9PN%2BR8Xz3paefDNltbx8fV4%2BYWZZACBqx9kcaxDDOYR2TCv1BnUjl6ZPIzuNOkaJsBRdc2gFU0xzIiajoA4gomQTvKart7aaUKCxnloxL5e1IH6yZJMWf0lN8G%2BBMZSjwWm06owzx5pEIY14lFwxAzyCCpQSgqSCaaEuqhytnZW%2B4Rh1jA9l6cBEXE2O59qqTDU%2B0oN86OkssKaEPxQ5HohFqE43hGREKb3v6OFvWX25T1QN9blKVhS9VFn36xAHyo5dQg21xQ9SBtX%2BEv7MQznRqdwiwg%2FutIaYbTC8sC3vyGCmjEW2YkkZTlJrYuBcwSSeTfb0M6qE68y%2F0uf%2FPsxELGqYGB2HM8eRRKet1WIIFzyXseGAWu1W9wX1s0MyCaPirKg6qiGGdc6IPZ03NVYK8gDDLUJERJYb%2F8D1dp%2F1bzjDA8d29BjqkATeg7abCwAfXdrTf%2Bdgnqb1ee6ycD8XIvMWMX5RvgWx8p0rNGxTLxFpngzyz%2FYmO3%2Bu4xbf1KGuVuKkaVQehk4kFfKWJ82zDL%2Bm2jWQU1XTfbikAiLUTmv1gsHkHwpFSXyCbPnWwFa%2B1ZDQkk9WFuyaIC3DfQJ%2ForcM8NRJ4pvOWQI1kbr%2BUpYP5QXxb%2Blap2Uzz5xmUQXYTxyJ2qAxxmYk88G22&X-Amz-Signature=630d0eb9a4f4fc05a3e9348e2686ae01cafecfcc97591752d48c3336a2e4c53d&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XP7IPB46%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T191912Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIFjyJUQjnIRPWMZtzgGAyvqPjKNxA98lN88QokH4hNbWAiBrg9AdTJL0Su02xPRDqeknvBPnyZCmqy3kzaVTuOjVdCqIBAjE%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMtTnphg%2BDk4yKfQzzKtwDk41zlT82EvRpvgjy8JrSCZHl9AEsbiwqfOs16GuFybQFZNLQobU4Zt57U8uFTw%2BO7RiYXeSjsef8jZSG%2FqEKRtPeIUNY5f75IFnRObseW1GCYt0zxR0o%2BQqgpZnVzxS5rCgfvYRznMtIxapar5jWKb%2FShitQjn2ziCu%2B0ATRb8NgSAyO7BnWjRB5ekKIgCUZGVV4j2H%2FZTxnUT%2F243E5cuIoS1ZRHzZ0zxydbFEZx00L92i38sf%2By6fBiC75ywBPbMfongJnEgnu3MzcCtP2NJY7Rq5oObqWAu61yKGsgkp2nKpyjFPLcAf%2B63Seapia4audn2aV75n7AeNnZakiY6ihti3P3A2jW0VuWyKahrQnQFEaOtAzvdkDGQyW6mbzcycvyDBvMjRVKyFerLL3kiTEush8QcyiI1ibJv17gZnO%2BrNKhU6PbF5R5c%2FdIH48YIdHx4IMOVnGV4UaICuEjMIrm2CpZiJMNZxQR3x5umpe7p7SFFut31kWUpPWUPKs1%2BWBSknn5GjNxCJACa6a%2Bm%2B2hrXWKmnZ%2BDvFgve%2BxpzNLTOnOg7Zs%2FDvIiJBDwp4Dj7oUY3KtN1YTL97lzR9v%2Bud3JBZYXCmpAso17iLNpf1KNuWjn3w7hKA9jkwxfHdvQY6pgGSiURixznMJfgpxE34RAWNvO9AAWls67LpzQg9hNLWtgfP7wDr%2FFFpEBef8ejv3l82W6o4GMb%2F%2BbIzf0K7Q0pS5OY3azBb7UDAHHd4C1%2Fv5HywEPlYmjkup%2BqJFmIdl4d7Qmogo3br8q%2BavUPMSpdq8tSkeBvUEtQenqDlj1YSBDQ44ExAAc%2BaFCU4MuOfAwZiNKijQuusREhKZNEd129dtINPe8SE&X-Amz-Signature=0aca9cb6a751c72f334d0348d6221fc388b66223f75131f2c2dbb3272b09121b&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Y5CYFVIG%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T191913Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIHH%2FdhJSGZMPs%2B6yGdYxcMWA7NcGAJoGrp0k3XbDQrXvAiEAj7410TGSdIjpf0NNl1SoS6g0511AUD1UstIyGPilqnoqiAQIxP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDoo8dmt2bhhTWnvyCrcA1I1HPt%2B025AhHMv60XtOvpNARATIs4CkBGThUOPNkhxATfAMt3rJKjS3k1W46BKZoMJMOjiRKZo9gwkXl%2F1MLQM2nQQVZuyxFQAY2aQe4N1%2BwkUOmddi8FYnP84luj9z1yKj1w7r4ILEmy63xfZGjx8s4786%2FMkmFgwKMF69rAMKyLq6nwSaMUe%2BpWE2a5Vu7oNmZY31jW3qXt8tOsDFpNmby57VhnniKSPu04W1C3aOn8Aq9AgIjnpaNZwCkRtTE%2FBwfbmvmWiytGCK8LCfsDDR%2BzdGIF%2BCRocSiZnijzJMCqshZ64piCRnBTV%2FfUMRPkKsnWMl3JH3%2F%2FsZlmBARADjo7Ap7%2B7VZiBMUiPrBbscXatyZbLXIiyZgunV2AL%2B7PuhK%2BGpE0q9FFyPXxyor3P0ikg%2FtO0sgn6BUNmqxu9zu1W7S5S%2FAYQRQQ1wdYm%2F4OJ83tPbW%2BkmU3fcyvyIEkJjbgeJQjo%2FIDJvbib5bv0L4HD29HBKXJ7%2Bxj8mC3jN4WWsbPixHLw0GV1F8k2D%2Bo6JgOrtetdrF3Aqw%2FO1FPD0UbTJvIddn%2BqGwOm0bd%2Fe4GBrZ4kqTcIO%2F3%2FWeprQDwQMiMre3MHKLJ8phPJdJ%2F3QcCVJIA87ocj2BlyMMTx3b0GOqUBi3l9x%2FmQ%2BzkgVd4uvFRbBp8L%2FH6d7gAO1dDqju58fbCguX1jOUhayyhPCoaVRF8jq5AAlymyVYlcF%2Bwx1SgZgAQOeygLjYSYiC%2FIFf3WZL9z21Tbt8c1xc5hrrtTLN7vdrbbn9iNaSHmexuqTBNwSHYndedVNxQrkCcBDaprPIkrnQQcqYRTsIA3PDFhKsVwsgBtmfox9XvEjnAk5ozCkMFR7JFI&X-Amz-Signature=c6fae783a6545da5d9d873c7fa63e69b03ae009a5a0726e417a659236b0b9f6c&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SOCI73TU%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T191911Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDZNR0%2Bi6vhoPiQQvdJS7fNFwHmDcVmHbPWH4VexPe6KQIhAPdaQ%2FBWEQeuXI117v7SmVlJ%2BxQj60IlOakuEoxq1sxqKogECMT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyiEZmT7CsOKXiNIRAq3AO7kYQtlLWF2zvcXt5BVTIW6%2BLG2LEcM7O1hv1c193OfUF3YYJTAEs%2BeCETGZkJWFHtVCwqNdyis%2Fs9U1Ym5quCYOxH6hOGDvhi7GF3Bjg4u9oeZV5G2y6ABa2wq9MR5hn906FUawn%2FOMDGAF1hqpP1LQVnUjQgaxHDnhQRh7lF5dxqeM64h5Vr09b00D%2Fae5IzLw%2FPo7TIvHi9PN%2BR8Xz3paefDNltbx8fV4%2BYWZZACBqx9kcaxDDOYR2TCv1BnUjl6ZPIzuNOkaJsBRdc2gFU0xzIiajoA4gomQTvKart7aaUKCxnloxL5e1IH6yZJMWf0lN8G%2BBMZSjwWm06owzx5pEIY14lFwxAzyCCpQSgqSCaaEuqhytnZW%2B4Rh1jA9l6cBEXE2O59qqTDU%2B0oN86OkssKaEPxQ5HohFqE43hGREKb3v6OFvWX25T1QN9blKVhS9VFn36xAHyo5dQg21xQ9SBtX%2BEv7MQznRqdwiwg%2FutIaYbTC8sC3vyGCmjEW2YkkZTlJrYuBcwSSeTfb0M6qE68y%2F0uf%2FPsxELGqYGB2HM8eRRKet1WIIFzyXseGAWu1W9wX1s0MyCaPirKg6qiGGdc6IPZ03NVYK8gDDLUJERJYb%2F8D1dp%2F1bzjDA8d29BjqkATeg7abCwAfXdrTf%2Bdgnqb1ee6ycD8XIvMWMX5RvgWx8p0rNGxTLxFpngzyz%2FYmO3%2Bu4xbf1KGuVuKkaVQehk4kFfKWJ82zDL%2Bm2jWQU1XTfbikAiLUTmv1gsHkHwpFSXyCbPnWwFa%2B1ZDQkk9WFuyaIC3DfQJ%2ForcM8NRJ4pvOWQI1kbr%2BUpYP5QXxb%2Blap2Uzz5xmUQXYTxyJ2qAxxmYk88G22&X-Amz-Signature=ec667f4d457fc90beca3955db208ce87618f9faa2b48af7317e5775f7c6f781a&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SOCI73TU%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T191911Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDZNR0%2Bi6vhoPiQQvdJS7fNFwHmDcVmHbPWH4VexPe6KQIhAPdaQ%2FBWEQeuXI117v7SmVlJ%2BxQj60IlOakuEoxq1sxqKogECMT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyiEZmT7CsOKXiNIRAq3AO7kYQtlLWF2zvcXt5BVTIW6%2BLG2LEcM7O1hv1c193OfUF3YYJTAEs%2BeCETGZkJWFHtVCwqNdyis%2Fs9U1Ym5quCYOxH6hOGDvhi7GF3Bjg4u9oeZV5G2y6ABa2wq9MR5hn906FUawn%2FOMDGAF1hqpP1LQVnUjQgaxHDnhQRh7lF5dxqeM64h5Vr09b00D%2Fae5IzLw%2FPo7TIvHi9PN%2BR8Xz3paefDNltbx8fV4%2BYWZZACBqx9kcaxDDOYR2TCv1BnUjl6ZPIzuNOkaJsBRdc2gFU0xzIiajoA4gomQTvKart7aaUKCxnloxL5e1IH6yZJMWf0lN8G%2BBMZSjwWm06owzx5pEIY14lFwxAzyCCpQSgqSCaaEuqhytnZW%2B4Rh1jA9l6cBEXE2O59qqTDU%2B0oN86OkssKaEPxQ5HohFqE43hGREKb3v6OFvWX25T1QN9blKVhS9VFn36xAHyo5dQg21xQ9SBtX%2BEv7MQznRqdwiwg%2FutIaYbTC8sC3vyGCmjEW2YkkZTlJrYuBcwSSeTfb0M6qE68y%2F0uf%2FPsxELGqYGB2HM8eRRKet1WIIFzyXseGAWu1W9wX1s0MyCaPirKg6qiGGdc6IPZ03NVYK8gDDLUJERJYb%2F8D1dp%2F1bzjDA8d29BjqkATeg7abCwAfXdrTf%2Bdgnqb1ee6ycD8XIvMWMX5RvgWx8p0rNGxTLxFpngzyz%2FYmO3%2Bu4xbf1KGuVuKkaVQehk4kFfKWJ82zDL%2Bm2jWQU1XTfbikAiLUTmv1gsHkHwpFSXyCbPnWwFa%2B1ZDQkk9WFuyaIC3DfQJ%2ForcM8NRJ4pvOWQI1kbr%2BUpYP5QXxb%2Blap2Uzz5xmUQXYTxyJ2qAxxmYk88G22&X-Amz-Signature=69b40dbd6ee68ea0969c7bdd1d5dd793e7f5fd1b236358adf64f71a6e1c51079&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SOCI73TU%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T191911Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDZNR0%2Bi6vhoPiQQvdJS7fNFwHmDcVmHbPWH4VexPe6KQIhAPdaQ%2FBWEQeuXI117v7SmVlJ%2BxQj60IlOakuEoxq1sxqKogECMT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyiEZmT7CsOKXiNIRAq3AO7kYQtlLWF2zvcXt5BVTIW6%2BLG2LEcM7O1hv1c193OfUF3YYJTAEs%2BeCETGZkJWFHtVCwqNdyis%2Fs9U1Ym5quCYOxH6hOGDvhi7GF3Bjg4u9oeZV5G2y6ABa2wq9MR5hn906FUawn%2FOMDGAF1hqpP1LQVnUjQgaxHDnhQRh7lF5dxqeM64h5Vr09b00D%2Fae5IzLw%2FPo7TIvHi9PN%2BR8Xz3paefDNltbx8fV4%2BYWZZACBqx9kcaxDDOYR2TCv1BnUjl6ZPIzuNOkaJsBRdc2gFU0xzIiajoA4gomQTvKart7aaUKCxnloxL5e1IH6yZJMWf0lN8G%2BBMZSjwWm06owzx5pEIY14lFwxAzyCCpQSgqSCaaEuqhytnZW%2B4Rh1jA9l6cBEXE2O59qqTDU%2B0oN86OkssKaEPxQ5HohFqE43hGREKb3v6OFvWX25T1QN9blKVhS9VFn36xAHyo5dQg21xQ9SBtX%2BEv7MQznRqdwiwg%2FutIaYbTC8sC3vyGCmjEW2YkkZTlJrYuBcwSSeTfb0M6qE68y%2F0uf%2FPsxELGqYGB2HM8eRRKet1WIIFzyXseGAWu1W9wX1s0MyCaPirKg6qiGGdc6IPZ03NVYK8gDDLUJERJYb%2F8D1dp%2F1bzjDA8d29BjqkATeg7abCwAfXdrTf%2Bdgnqb1ee6ycD8XIvMWMX5RvgWx8p0rNGxTLxFpngzyz%2FYmO3%2Bu4xbf1KGuVuKkaVQehk4kFfKWJ82zDL%2Bm2jWQU1XTfbikAiLUTmv1gsHkHwpFSXyCbPnWwFa%2B1ZDQkk9WFuyaIC3DfQJ%2ForcM8NRJ4pvOWQI1kbr%2BUpYP5QXxb%2Blap2Uzz5xmUQXYTxyJ2qAxxmYk88G22&X-Amz-Signature=880083a133f4d4246840ac4e85267ef1199e062206b9fe447df5c8ac0fc39b22&X-Amz-SignedHeaders=host&x-id=GetObject)


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

