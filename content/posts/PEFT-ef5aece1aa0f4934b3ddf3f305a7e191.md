---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4664BQ65PJ7%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250222T111744Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIG9UvR9R8JY80XpsTRQ\
  MTZeOm3LtKUCOmGMe5o4rIZyAAiEAoUemhf6r3669ZxxaZfPFRh%2FYAAiAoScSVPJmhPf2hj4qiA\
  QI5%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPXsDGfj8QLeTRves\
  ircA9HbZwd8sUsj9PF6eYaL9jziadij3JzPcx6r9GU63GyB7Dqv5FNEvyr7aY%2BUGz%2BRRKRlBw\
  Yod7ovbgjory5JBq%2Bt2NvGaKJSPUIk9Ie2A3d8hcpVyEvIuCnMnShDZs1ebXJ7ylwhirQnuzuin\
  wEmbDgsHxOBcqpdW4oJJoj%2FQyoOKC25PcBjGZHLUkrSVC33EqvplhPkr8sxIFN%2F0BkKC1c%2F\
  5jY4hP4HPG%2FxfTIDLhw1jzUtHcw%2BxEWmf3WxamB9A3AU4KUb3hCWL7chaSAtSr5DIRmsi9x4A\
  nU0UGYsZ48TBlVU%2FgeD0FtH53qZBmhFga2P0H0AWY%2BsQk4pKY6Pz9xwnYZ3frN41zYZcWhQ8Q\
  9X2PQ56MqzHPClhizEleVOiykIxZyDuBJHJ5hkfUUHU6JbS71nCoMEpXBB%2Bqg%2FcBZsXvYczK7\
  3l%2BOWphEP%2FX3zpDh97wCsy%2F4j%2BlgTrtohn%2B%2Fl4wlwTK%2By5O2BJAj06rpCyVFofA\
  NlU8fgRJw2oxiEkRFrpkzKAzJW50w6ODXaNqiUqJEbOnFDu619i3gclNrx%2F59RJk9GK9X59JaYH\
  f072bfhpL9l7cdw6hHZuqoHaGrQZG%2BVWzuEIX1XVSHXLkvbk3XfXsZZ2IqTX3plMJHH5b0GOqUB\
  l1G3sMVk3DBhQ54XwvERpHZPMEiJSKtfYZps%2Bd2QGEfE6UQuJ2iYme21nnKJBNhd1GvfZ44Ru6g\
  1jpeUtiTOgg1LYHnWJ0aSaBi%2FdJT%2Fvw9dqm70UlKBVHueOmIBKvFoKj%2BBTN1SniU8oM9JCu\
  CaUofO8bmObz4WCDR7s1MqmnvEi90qukliazhioq1lAR6a%2Fl9xk7BnGSNzWP7cfrbir9n2aDy2&\
  X-Amz-Signature=0263456b27a128e89a98dfa5f5ef75c497608137715c7640d1ce8ebc2b1cc\
  83c&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466QHYOIR2C%2F20250222%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250222T111632Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIEBcaDLaZvTMFBaaMfLxeMPnL3HiR0TGPatZfVII%2BRvZAiEAtVRyOZb3GEjSpp7qvpRs\
        QYVhq51FaUwy8RAifjrTH3QqiAQI5%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2M\
        zc0MjMxODM4MDUiDP%2BxmtJWscCdNLUMEircA9A0nHurwCsmyVDClPD4bXTcqIexd4r9pt\
        4fMqVpmOJNoKX6qlmXCxauTZ7htzPlLYjyDcVsxxioeSqgv9MaJrO1g%2BRmY28YgLcF6Zs\
        R6Yq1u%2BALCVB8%2FA7JIw1a0XhEmGlCM%2BapscV6QkxPslb%2FQ2iaCR7yY1uIMSiPQz\
        51C%2Fz8m5QsBdz4oEynbKEy4R5WxuoR9KUXPZ1IkyO2YnKD1tBLbRcm3qFSk2cuRlbXaRq\
        17wn6J0Hrq466lgs5ssI8wTZ996zbnUC8pBh0klbtAxKyZve0tomVSoHMdLt6mAazlXEPLd\
        WFmJkpHNPJH20r73sKXFTmRL87Old65ZpkUB4SmcNrpX52hxG2jsO7CGW%2FEa9ZKlDBGp5\
        hj43V6e94AeNkbG12JR1xMITAZ3KdyxRvtoMl4ahkh8kyfn4PF9zKXW9tI0r3kMcw9BC%2B\
        5Pgf60nhpSws8MyDRJLP%2BCSTtkSMg3pP5qi5%2BBG6Rb%2FjfEUzHNR79wfdn8XZgQvGc\
        5XKaqFjjfQsxOKEIy7gSdPWSAKdIgfMjpzVVkJI8fRYbjTQA9wqFEQZ%2F3JXXUbXEYzJMg\
        0c3dk7oO8GymIkGIsTRo4Za79BraU6pBxmtR7O9nhZEDC5XBJeK0sUrvNyMJHH5b0GOqUBw\
        bSwwGeJQj8zB%2FdOSWYW9YDL%2BWldn4ewMAtIAsKU4L8xGJxD38hKAY5Rk4%2FWXX%2Fl\
        LIO%2BRBx86iHDS2ijkmcGGfa6QjI0PzggGqk7wnFIWEjNahg54%2FJu9owiUh3JEbrUWZG\
        fGM2R4zGEnCXd6YjNjMqZwXO5%2FirZNpNYO6C8NWPyZzgMWE7rCQkbVwMAvnOuG4VQnQjs\
        iW5X9H94FRMjo6RPukQ0&X-Amz-Signature=5f133bcd46d74f0a10365fc5bf5c3cf7fd\
        bc172c64fde52bb51ee9d16949acb2&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-22T12:16:32.088Z"
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
UPDATE_TIME: "2025-02-22T11:17:48.706Z"
EXPIRY_TIME: "2025-02-22T12:17:42.009Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664CPRXCLP%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T111742Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDPO%2FTQUA0HCy%2Bb4VR5P7HH8lZzpQgORBLPhpZ5pph5zAIgGQF207eNodUBS5na36Zj0TBX372ooq43YH%2FNz94ACioqiAQI5%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDI1vBPjoDksqdT7%2FJSrcA%2BRe0g84vYJnmKxlxdROhXEAFQxgPe89gh5X5iAcefbtkHIfZFAEUEBxuWS3PCBqAu1l%2BEmhOPp%2FMVrO37xcy5SoarrbWHXU8%2FkQuJpCEGnhVrgsMBONd01pq1Yv3ZvE13RQVIqVIbgBAtRd2%2FpdxV5N43S6ZfWhU9ZEfJiPjK0IZjs1pnjMZNHnMkTzFZqvz157GxM8vn8DgQlBkj1zzJkEXuwrZ6W4GIi9NaB1WQiC0w%2BBGwCCRntZhv8YNDszdEEDVPIwFhTC6VjrNGoxEHMDthgR715HB6GBiUzbxQQnUbMRwaWgXE4k2vdP5WoCj4l7ARs26xN9RZNy1MCjGlsb%2BJ%2BpspCX6XTharA7%2BOs1O67JrZRh5ZAaZzX0bol2RJNciF001ebbJTYL48hEu0YHCRe6uJBL4Qbh3yXIRcDDNUFvqHDsAkosB58aOBdvH2LQ5FrWMocF09943RPLeWmQc9okilorC0m6SxVJdFJAMqqZ%2FkCAe90PcSuhj%2Bmbk4h3hTrhu%2BTubT%2Bi4M%2Fh5fcyG14P%2F7UGA%2Bi7ZgdhB2K1wblxEeLUdAeZ8lpohZ1%2F69t4vCjOgmIMcsM%2BbWwdq9e%2BBNtsgI0DP%2Fv6THq2%2BP3mVnMAeZfU3sz5WOL2MLDH5b0GOqUBs7DVV%2Bt1o5Qw%2FnWr7ngX2ElW0ppml347xnvz06PM3WwgxqeDXzno6bIrt1H0cErOyrI7LEUdPd7Y6%2FTNrPPX1oeuiCwjzzAZ11m11xtYME9BluJo7PUuUyV58dFvAFLaOlrwRKhJzYTAIGHpP%2BKYuuxKRTHqZ2ZV%2Btr5PakKccfQfiYZ%2B4%2F1NRpAV0KG6xsDNRykrsIVI5oYhEkfkFp%2F7w7C%2FluR&X-Amz-Signature=77b73ffe910b05a005687e4428311e6337e5b8c1c17393ce2f0ca04cf434fd15&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664CPRXCLP%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T111742Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDPO%2FTQUA0HCy%2Bb4VR5P7HH8lZzpQgORBLPhpZ5pph5zAIgGQF207eNodUBS5na36Zj0TBX372ooq43YH%2FNz94ACioqiAQI5%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDI1vBPjoDksqdT7%2FJSrcA%2BRe0g84vYJnmKxlxdROhXEAFQxgPe89gh5X5iAcefbtkHIfZFAEUEBxuWS3PCBqAu1l%2BEmhOPp%2FMVrO37xcy5SoarrbWHXU8%2FkQuJpCEGnhVrgsMBONd01pq1Yv3ZvE13RQVIqVIbgBAtRd2%2FpdxV5N43S6ZfWhU9ZEfJiPjK0IZjs1pnjMZNHnMkTzFZqvz157GxM8vn8DgQlBkj1zzJkEXuwrZ6W4GIi9NaB1WQiC0w%2BBGwCCRntZhv8YNDszdEEDVPIwFhTC6VjrNGoxEHMDthgR715HB6GBiUzbxQQnUbMRwaWgXE4k2vdP5WoCj4l7ARs26xN9RZNy1MCjGlsb%2BJ%2BpspCX6XTharA7%2BOs1O67JrZRh5ZAaZzX0bol2RJNciF001ebbJTYL48hEu0YHCRe6uJBL4Qbh3yXIRcDDNUFvqHDsAkosB58aOBdvH2LQ5FrWMocF09943RPLeWmQc9okilorC0m6SxVJdFJAMqqZ%2FkCAe90PcSuhj%2Bmbk4h3hTrhu%2BTubT%2Bi4M%2Fh5fcyG14P%2F7UGA%2Bi7ZgdhB2K1wblxEeLUdAeZ8lpohZ1%2F69t4vCjOgmIMcsM%2BbWwdq9e%2BBNtsgI0DP%2Fv6THq2%2BP3mVnMAeZfU3sz5WOL2MLDH5b0GOqUBs7DVV%2Bt1o5Qw%2FnWr7ngX2ElW0ppml347xnvz06PM3WwgxqeDXzno6bIrt1H0cErOyrI7LEUdPd7Y6%2FTNrPPX1oeuiCwjzzAZ11m11xtYME9BluJo7PUuUyV58dFvAFLaOlrwRKhJzYTAIGHpP%2BKYuuxKRTHqZ2ZV%2Btr5PakKccfQfiYZ%2B4%2F1NRpAV0KG6xsDNRykrsIVI5oYhEkfkFp%2F7w7C%2FluR&X-Amz-Signature=b9aafbd9bc759f54ea21ce0597eea997587c1eee1c86de5959d8909ed15700a4&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664CPRXCLP%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T111742Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDPO%2FTQUA0HCy%2Bb4VR5P7HH8lZzpQgORBLPhpZ5pph5zAIgGQF207eNodUBS5na36Zj0TBX372ooq43YH%2FNz94ACioqiAQI5%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDI1vBPjoDksqdT7%2FJSrcA%2BRe0g84vYJnmKxlxdROhXEAFQxgPe89gh5X5iAcefbtkHIfZFAEUEBxuWS3PCBqAu1l%2BEmhOPp%2FMVrO37xcy5SoarrbWHXU8%2FkQuJpCEGnhVrgsMBONd01pq1Yv3ZvE13RQVIqVIbgBAtRd2%2FpdxV5N43S6ZfWhU9ZEfJiPjK0IZjs1pnjMZNHnMkTzFZqvz157GxM8vn8DgQlBkj1zzJkEXuwrZ6W4GIi9NaB1WQiC0w%2BBGwCCRntZhv8YNDszdEEDVPIwFhTC6VjrNGoxEHMDthgR715HB6GBiUzbxQQnUbMRwaWgXE4k2vdP5WoCj4l7ARs26xN9RZNy1MCjGlsb%2BJ%2BpspCX6XTharA7%2BOs1O67JrZRh5ZAaZzX0bol2RJNciF001ebbJTYL48hEu0YHCRe6uJBL4Qbh3yXIRcDDNUFvqHDsAkosB58aOBdvH2LQ5FrWMocF09943RPLeWmQc9okilorC0m6SxVJdFJAMqqZ%2FkCAe90PcSuhj%2Bmbk4h3hTrhu%2BTubT%2Bi4M%2Fh5fcyG14P%2F7UGA%2Bi7ZgdhB2K1wblxEeLUdAeZ8lpohZ1%2F69t4vCjOgmIMcsM%2BbWwdq9e%2BBNtsgI0DP%2Fv6THq2%2BP3mVnMAeZfU3sz5WOL2MLDH5b0GOqUBs7DVV%2Bt1o5Qw%2FnWr7ngX2ElW0ppml347xnvz06PM3WwgxqeDXzno6bIrt1H0cErOyrI7LEUdPd7Y6%2FTNrPPX1oeuiCwjzzAZ11m11xtYME9BluJo7PUuUyV58dFvAFLaOlrwRKhJzYTAIGHpP%2BKYuuxKRTHqZ2ZV%2Btr5PakKccfQfiYZ%2B4%2F1NRpAV0KG6xsDNRykrsIVI5oYhEkfkFp%2F7w7C%2FluR&X-Amz-Signature=58412ca58279155e5e840f37763c22d303c78a5de1e1f00ff53d2c7cb5257d39&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664CPRXCLP%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T111742Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDPO%2FTQUA0HCy%2Bb4VR5P7HH8lZzpQgORBLPhpZ5pph5zAIgGQF207eNodUBS5na36Zj0TBX372ooq43YH%2FNz94ACioqiAQI5%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDI1vBPjoDksqdT7%2FJSrcA%2BRe0g84vYJnmKxlxdROhXEAFQxgPe89gh5X5iAcefbtkHIfZFAEUEBxuWS3PCBqAu1l%2BEmhOPp%2FMVrO37xcy5SoarrbWHXU8%2FkQuJpCEGnhVrgsMBONd01pq1Yv3ZvE13RQVIqVIbgBAtRd2%2FpdxV5N43S6ZfWhU9ZEfJiPjK0IZjs1pnjMZNHnMkTzFZqvz157GxM8vn8DgQlBkj1zzJkEXuwrZ6W4GIi9NaB1WQiC0w%2BBGwCCRntZhv8YNDszdEEDVPIwFhTC6VjrNGoxEHMDthgR715HB6GBiUzbxQQnUbMRwaWgXE4k2vdP5WoCj4l7ARs26xN9RZNy1MCjGlsb%2BJ%2BpspCX6XTharA7%2BOs1O67JrZRh5ZAaZzX0bol2RJNciF001ebbJTYL48hEu0YHCRe6uJBL4Qbh3yXIRcDDNUFvqHDsAkosB58aOBdvH2LQ5FrWMocF09943RPLeWmQc9okilorC0m6SxVJdFJAMqqZ%2FkCAe90PcSuhj%2Bmbk4h3hTrhu%2BTubT%2Bi4M%2Fh5fcyG14P%2F7UGA%2Bi7ZgdhB2K1wblxEeLUdAeZ8lpohZ1%2F69t4vCjOgmIMcsM%2BbWwdq9e%2BBNtsgI0DP%2Fv6THq2%2BP3mVnMAeZfU3sz5WOL2MLDH5b0GOqUBs7DVV%2Bt1o5Qw%2FnWr7ngX2ElW0ppml347xnvz06PM3WwgxqeDXzno6bIrt1H0cErOyrI7LEUdPd7Y6%2FTNrPPX1oeuiCwjzzAZ11m11xtYME9BluJo7PUuUyV58dFvAFLaOlrwRKhJzYTAIGHpP%2BKYuuxKRTHqZ2ZV%2Btr5PakKccfQfiYZ%2B4%2F1NRpAV0KG6xsDNRykrsIVI5oYhEkfkFp%2F7w7C%2FluR&X-Amz-Signature=b6eeb471696709a053b4b0dab30735f40423dd93bfc258660ba209db29b236c9&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664CPRXCLP%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T111742Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDPO%2FTQUA0HCy%2Bb4VR5P7HH8lZzpQgORBLPhpZ5pph5zAIgGQF207eNodUBS5na36Zj0TBX372ooq43YH%2FNz94ACioqiAQI5%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDI1vBPjoDksqdT7%2FJSrcA%2BRe0g84vYJnmKxlxdROhXEAFQxgPe89gh5X5iAcefbtkHIfZFAEUEBxuWS3PCBqAu1l%2BEmhOPp%2FMVrO37xcy5SoarrbWHXU8%2FkQuJpCEGnhVrgsMBONd01pq1Yv3ZvE13RQVIqVIbgBAtRd2%2FpdxV5N43S6ZfWhU9ZEfJiPjK0IZjs1pnjMZNHnMkTzFZqvz157GxM8vn8DgQlBkj1zzJkEXuwrZ6W4GIi9NaB1WQiC0w%2BBGwCCRntZhv8YNDszdEEDVPIwFhTC6VjrNGoxEHMDthgR715HB6GBiUzbxQQnUbMRwaWgXE4k2vdP5WoCj4l7ARs26xN9RZNy1MCjGlsb%2BJ%2BpspCX6XTharA7%2BOs1O67JrZRh5ZAaZzX0bol2RJNciF001ebbJTYL48hEu0YHCRe6uJBL4Qbh3yXIRcDDNUFvqHDsAkosB58aOBdvH2LQ5FrWMocF09943RPLeWmQc9okilorC0m6SxVJdFJAMqqZ%2FkCAe90PcSuhj%2Bmbk4h3hTrhu%2BTubT%2Bi4M%2Fh5fcyG14P%2F7UGA%2Bi7ZgdhB2K1wblxEeLUdAeZ8lpohZ1%2F69t4vCjOgmIMcsM%2BbWwdq9e%2BBNtsgI0DP%2Fv6THq2%2BP3mVnMAeZfU3sz5WOL2MLDH5b0GOqUBs7DVV%2Bt1o5Qw%2FnWr7ngX2ElW0ppml347xnvz06PM3WwgxqeDXzno6bIrt1H0cErOyrI7LEUdPd7Y6%2FTNrPPX1oeuiCwjzzAZ11m11xtYME9BluJo7PUuUyV58dFvAFLaOlrwRKhJzYTAIGHpP%2BKYuuxKRTHqZ2ZV%2Btr5PakKccfQfiYZ%2B4%2F1NRpAV0KG6xsDNRykrsIVI5oYhEkfkFp%2F7w7C%2FluR&X-Amz-Signature=bd81660de4cedf1c2960a228960e1199e989eb9b5ead733ccdd24e41ac42bedc&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662P2ZPKY4%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T111743Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCICoXBWzP0NRGoaONH%2FH1LRxM2nKQD5sk6Du9eANg1Mj9AiEAi943QQ2oCZU3nUHMDbZtdxgVDXUppO3y1Fu93gE72tMqiAQI5%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLH3XR1v2wkb58JnvyrcAxDeI8EMrnfsS3khffUUKYum%2BSf5QEMfln9dosoFK%2FwWuHCXeo1ipOLEPxahTDXiI1tsF2%2FeaXjS1BTtOaTJ6A%2B4ZoAnCzTqo%2FT62KdwKWvRu199ImTQLDskD19x6UJj%2F8AaWedpu2LPhQCxBmF2fuSf5%2Fj%2Bq6%2BfwoVZUvRjMLp84DfcTgRfhhgPliqh23PiuZfHtM7wIEVDHLyauAGJUzjEbYH585z%2BvUH3TU0k1uiWUrCRHlN2YaLqWB3dXgoSIR6WcM4jDYSRpxem3EtQMjPvKF%2BxA6IpmmHdz2BULIOp1vUWk7DbrgewKZ3%2Bqcueyptdvq%2FnaH8WHa626182WKYlvOs1jS8W%2FGetKfbdQTAe0Dic%2FQyeXrfXjJ1XtjPRdfTmTBAqaShZHYi5SKqQL3JZtUEtuzC%2BICyYTl0iL4WIOC4ESiUEfeFhiozG6Y4sWfs2FBhVyUKvJSHZ8dtsc9rgx0mY%2FIZ5tkEv9DwFJ11b2A%2BVzM%2FwlD8wNHvdvU99lX9%2Bs8q%2Bf6wb5o%2B837jePVWx0NplGkT%2BBxxOXxHkzntIQS013zMEwAn3lKJQY%2BeeAQtYVef7weoEjIOM78ApXf7ylztPstlDM5fyfKmNmKjmt%2B76DzwoD%2FZZNecHMNDH5b0GOqUBPXgWdlNxWB2JwR9huaLioUn1dbFS6iehnlrAbMCmMLEIYfYdyD%2BtKVVfl9UZnLIeDojUYx6MuX5GQjUy7Sxon9R253wjkDFO%2Fog%2FIhjrzr%2B7eOuNZFYmrhNuHTjjtmDsvjHA1rQhZ%2FHR20CaQdQFAUJWNvf7g14srtqTkff0DTcyTp69jkjmRvnrbIvxc7vEYhLpG5%2F8ys7P7B%2Fs4Rw%2FmNEqOnl1&X-Amz-Signature=61fa727c6c6e8d3f4c505597b0ad00327a4b19a12ad3cf09a40187bbc5e4fac3&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QVOTWPGE%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T111744Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIFAWqTybwKEia%2F4BbFslLP4Z%2B2oW4JA0sAV1UkYp12fgAiBnEoBUdsVEuEazARtNF5x6hxJYfdK2tvyHfBYcQryTLiqIBAjo%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMaRM2jU0NArrFbWYsKtwDJFMCqd5WKInZ5l1J3%2BAMzj4kSodjO2yG42DEx5kNe%2F2OrYfgr01%2BCrVZzTXdl6OmyO0h4390Fs1C9StuXKO%2FM452lpqOg2urFUInXXgBv%2F%2FJw37fe%2BIYTsmyOJfdpclV%2BiNveZco0Vq7SthbGyorFS8Eco26HWwI3yZk5sXG794IQN7xSVaxDFX1Pg4%2FxHtSTdgOHk9pEMYhu1KYiPrOoOAzVe%2BnbXEsrgEpjCxB1U7Ndl9bFcntwSG4xYiNbUTHQqNK1KiPBwGuQanCaOSayo5KNPxsx93MtMxWmSQJQqZm2new2EWvfwmjATIvM9mA7oN7DM4aS8DAQIbhFO7Nm21%2FXDDd81GfS%2B5D%2FwOFizx7n9deg16HiyDwKukOwua%2B5itY3F6IdtYR%2FkRH01mR4NrcKU7CyQ5CxX5Pc24r%2FFbtZQTRx4HBmc%2FpC7olcm5B2tJvxNAlXnj4DTwoISCpXtMyQ09jGqsx1Jqt%2B46yz%2B6U%2BgGXaDcu6%2BJK9nNc2kYZXkbQ37KVdNF1tSeKvupBjF7VABMrt69yPBfpExxqWTDZZlCQa%2F38VONie%2FEw690CQRi2hhmRYZ2zs16q1ZiJ77TMMSaZRvySo7o8WjNmrLt9uvUtpCbKVBRKXZkwkezlvQY6pgH%2Fi3Z9ogbI5bMWX%2BYx0ev2RKiGTgp7OD7ur7Gp1B8PZj14dNdkOAtdOZRBeNuIzfN7DIw1ybxu%2FR0c8RpemmpkXSD7j%2Bp1clkeiG7Wmklmqk98ZUg%2BjUKWuEMrsPv2Ts9QBKzqkLzqh3FrOK8Wv55nUo8fiS4gSjunr6I35NJyBaaGFsRWF%2BF%2BAzCAUMAb%2B%2BgWUPUz6qHNsKWcxVwnNlqXo5MiP4Ui&X-Amz-Signature=c4f638c7c9b7141da2bd9450e5a4db555ccf6a92d4aeeb63c7d7230e4d3e4260&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664CPRXCLP%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T111742Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDPO%2FTQUA0HCy%2Bb4VR5P7HH8lZzpQgORBLPhpZ5pph5zAIgGQF207eNodUBS5na36Zj0TBX372ooq43YH%2FNz94ACioqiAQI5%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDI1vBPjoDksqdT7%2FJSrcA%2BRe0g84vYJnmKxlxdROhXEAFQxgPe89gh5X5iAcefbtkHIfZFAEUEBxuWS3PCBqAu1l%2BEmhOPp%2FMVrO37xcy5SoarrbWHXU8%2FkQuJpCEGnhVrgsMBONd01pq1Yv3ZvE13RQVIqVIbgBAtRd2%2FpdxV5N43S6ZfWhU9ZEfJiPjK0IZjs1pnjMZNHnMkTzFZqvz157GxM8vn8DgQlBkj1zzJkEXuwrZ6W4GIi9NaB1WQiC0w%2BBGwCCRntZhv8YNDszdEEDVPIwFhTC6VjrNGoxEHMDthgR715HB6GBiUzbxQQnUbMRwaWgXE4k2vdP5WoCj4l7ARs26xN9RZNy1MCjGlsb%2BJ%2BpspCX6XTharA7%2BOs1O67JrZRh5ZAaZzX0bol2RJNciF001ebbJTYL48hEu0YHCRe6uJBL4Qbh3yXIRcDDNUFvqHDsAkosB58aOBdvH2LQ5FrWMocF09943RPLeWmQc9okilorC0m6SxVJdFJAMqqZ%2FkCAe90PcSuhj%2Bmbk4h3hTrhu%2BTubT%2Bi4M%2Fh5fcyG14P%2F7UGA%2Bi7ZgdhB2K1wblxEeLUdAeZ8lpohZ1%2F69t4vCjOgmIMcsM%2BbWwdq9e%2BBNtsgI0DP%2Fv6THq2%2BP3mVnMAeZfU3sz5WOL2MLDH5b0GOqUBs7DVV%2Bt1o5Qw%2FnWr7ngX2ElW0ppml347xnvz06PM3WwgxqeDXzno6bIrt1H0cErOyrI7LEUdPd7Y6%2FTNrPPX1oeuiCwjzzAZ11m11xtYME9BluJo7PUuUyV58dFvAFLaOlrwRKhJzYTAIGHpP%2BKYuuxKRTHqZ2ZV%2Btr5PakKccfQfiYZ%2B4%2F1NRpAV0KG6xsDNRykrsIVI5oYhEkfkFp%2F7w7C%2FluR&X-Amz-Signature=b1cffc7f8e57e0327eb5347d7d0537d8a18bdd59ce1a2df59cd0ce0b1e0770db&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664CPRXCLP%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T111742Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDPO%2FTQUA0HCy%2Bb4VR5P7HH8lZzpQgORBLPhpZ5pph5zAIgGQF207eNodUBS5na36Zj0TBX372ooq43YH%2FNz94ACioqiAQI5%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDI1vBPjoDksqdT7%2FJSrcA%2BRe0g84vYJnmKxlxdROhXEAFQxgPe89gh5X5iAcefbtkHIfZFAEUEBxuWS3PCBqAu1l%2BEmhOPp%2FMVrO37xcy5SoarrbWHXU8%2FkQuJpCEGnhVrgsMBONd01pq1Yv3ZvE13RQVIqVIbgBAtRd2%2FpdxV5N43S6ZfWhU9ZEfJiPjK0IZjs1pnjMZNHnMkTzFZqvz157GxM8vn8DgQlBkj1zzJkEXuwrZ6W4GIi9NaB1WQiC0w%2BBGwCCRntZhv8YNDszdEEDVPIwFhTC6VjrNGoxEHMDthgR715HB6GBiUzbxQQnUbMRwaWgXE4k2vdP5WoCj4l7ARs26xN9RZNy1MCjGlsb%2BJ%2BpspCX6XTharA7%2BOs1O67JrZRh5ZAaZzX0bol2RJNciF001ebbJTYL48hEu0YHCRe6uJBL4Qbh3yXIRcDDNUFvqHDsAkosB58aOBdvH2LQ5FrWMocF09943RPLeWmQc9okilorC0m6SxVJdFJAMqqZ%2FkCAe90PcSuhj%2Bmbk4h3hTrhu%2BTubT%2Bi4M%2Fh5fcyG14P%2F7UGA%2Bi7ZgdhB2K1wblxEeLUdAeZ8lpohZ1%2F69t4vCjOgmIMcsM%2BbWwdq9e%2BBNtsgI0DP%2Fv6THq2%2BP3mVnMAeZfU3sz5WOL2MLDH5b0GOqUBs7DVV%2Bt1o5Qw%2FnWr7ngX2ElW0ppml347xnvz06PM3WwgxqeDXzno6bIrt1H0cErOyrI7LEUdPd7Y6%2FTNrPPX1oeuiCwjzzAZ11m11xtYME9BluJo7PUuUyV58dFvAFLaOlrwRKhJzYTAIGHpP%2BKYuuxKRTHqZ2ZV%2Btr5PakKccfQfiYZ%2B4%2F1NRpAV0KG6xsDNRykrsIVI5oYhEkfkFp%2F7w7C%2FluR&X-Amz-Signature=3089bbfc43d3bb034e77892d859c80becabfe19613ca3005ba8924faeddb9487&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664CPRXCLP%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T111742Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDPO%2FTQUA0HCy%2Bb4VR5P7HH8lZzpQgORBLPhpZ5pph5zAIgGQF207eNodUBS5na36Zj0TBX372ooq43YH%2FNz94ACioqiAQI5%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDI1vBPjoDksqdT7%2FJSrcA%2BRe0g84vYJnmKxlxdROhXEAFQxgPe89gh5X5iAcefbtkHIfZFAEUEBxuWS3PCBqAu1l%2BEmhOPp%2FMVrO37xcy5SoarrbWHXU8%2FkQuJpCEGnhVrgsMBONd01pq1Yv3ZvE13RQVIqVIbgBAtRd2%2FpdxV5N43S6ZfWhU9ZEfJiPjK0IZjs1pnjMZNHnMkTzFZqvz157GxM8vn8DgQlBkj1zzJkEXuwrZ6W4GIi9NaB1WQiC0w%2BBGwCCRntZhv8YNDszdEEDVPIwFhTC6VjrNGoxEHMDthgR715HB6GBiUzbxQQnUbMRwaWgXE4k2vdP5WoCj4l7ARs26xN9RZNy1MCjGlsb%2BJ%2BpspCX6XTharA7%2BOs1O67JrZRh5ZAaZzX0bol2RJNciF001ebbJTYL48hEu0YHCRe6uJBL4Qbh3yXIRcDDNUFvqHDsAkosB58aOBdvH2LQ5FrWMocF09943RPLeWmQc9okilorC0m6SxVJdFJAMqqZ%2FkCAe90PcSuhj%2Bmbk4h3hTrhu%2BTubT%2Bi4M%2Fh5fcyG14P%2F7UGA%2Bi7ZgdhB2K1wblxEeLUdAeZ8lpohZ1%2F69t4vCjOgmIMcsM%2BbWwdq9e%2BBNtsgI0DP%2Fv6THq2%2BP3mVnMAeZfU3sz5WOL2MLDH5b0GOqUBs7DVV%2Bt1o5Qw%2FnWr7ngX2ElW0ppml347xnvz06PM3WwgxqeDXzno6bIrt1H0cErOyrI7LEUdPd7Y6%2FTNrPPX1oeuiCwjzzAZ11m11xtYME9BluJo7PUuUyV58dFvAFLaOlrwRKhJzYTAIGHpP%2BKYuuxKRTHqZ2ZV%2Btr5PakKccfQfiYZ%2B4%2F1NRpAV0KG6xsDNRykrsIVI5oYhEkfkFp%2F7w7C%2FluR&X-Amz-Signature=9522ce9a758cb5ecc09d83800848a1297a365e8231d58329dacd86c85b69cd21&X-Amz-SignedHeaders=host&x-id=GetObject)


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

