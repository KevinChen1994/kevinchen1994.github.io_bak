---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466RCHGOLD3%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250224T232326Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEP7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIA6PA5XX4ekviYK5HYV\
  bFasVT8xVwUEg2o7qWdCcJNdTAiBd6isG4KHCsw77cLcxhe%2BrzriNe9BFa0SChMPLxlZYfCr%2F\
  Awg3EAAaDDYzNzQyMzE4MzgwNSIMNHPW%2FOytyy5iCI1RKtwDP8JI6elyrULDZ457ucg3cMtZhLi\
  VGg1w78atVq9FkIyp1kcubYeF%2B2Ts%2FD3lKnhY%2Bhjt09dDDTZWXbQitzJVXR42%2F3q1GZFy\
  3RmMidu%2FeFqXw6zv8n3RD3rB1SvR3Q9ZaA9zTsKeIb2Tc10Ld8qVqQi5OiQIVi5A3fqKxbF3Ajf\
  vtXIWm8q7tw2tlO1wYBIiQY51pv3cHILwIeoeG5DZItMgvvAkGboCEeDQwetwAdcZf%2B%2B6tDJ%\
  2FMu%2BA1bZpTgAkn9tLotHPzZnnHsrASTuJNN2UhciAPZ%2FdcmNlJ1D9yIuF7QHIUzwH7qqvjbo\
  fj6gIXi7764wuRSUpHezqfX7XFCJ2d4Q0Cc4SKfyso1oyw7OBOjfuI5Rn2V9Z0q9HjwpoU0rJSNS5\
  Omri8ZoA2g7Pn%2BoE6gmSAZMOXrMXCecAAZkqBvQS8n3An%2B%2BNfysVfRMJ0Osh1wKRIbJFsCZ\
  XtZA5jIA1Lrn2h%2FUEjn7lYDbJ%2FLkL7I1%2BaY9kpSRmu%2FL1tQoVDzcgJASdI%2FjC7y4gj5\
  9j%2FuKVSzZJGVZHRzpEvSYA7TvYhqKPJq1FfYDhzeUZfsubavsBv2iZEEcIU2nhc3PHXwR1doMMZ\
  bOJ2i%2F%2FM1KgBy%2BZglcnKHWuDWdJ7cAwjNbzvQY6pgEKpkLtn6bxT2O5ZJq4%2BeZxRmLVu3\
  POjK0UkXAI8%2Fullc%2FqR5poQPyQSv9Bp4gej2bGD7tA3qE5pyCs%2BS%2BFtFEFqPNmzC8HMPp\
  V08fOH%2Fnwszfn4pVVXMbaeqlRtseGmnYCI5je4CpoOfoD19vNQPtGpynHfAvrsaf0knrGYk2qHh\
  oaypG4DrAdgdBvsUlNTjmENxs6YtIiwWaA6i%2FRTT0tEKrEsRmI&X-Amz-Signature=c69ddef6\
  7d75b468076434badc40fbe95e0f425f087fd55e27a4338f655c74fe&X-Amz-SignedHeaders=\
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
        redential=ASIAZI2LB466VVUB37RU%2F20250224%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250224T232210Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEP7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIQDbK6glHo4Y4co3wmFTbkOUDx7iC850FEQgrg0HTPd90QIgHo2N8V8fA5K5%2BL8SEmzE\
        HNtZIoQY5tj5o9I%2F8GPv0T8q%2FwMINxAAGgw2Mzc0MjMxODM4MDUiDPUeqONkRvcpFJc\
        BYCrcA8g3aUWAUQQCj6J44XK2OleoKsNqdntK3o%2BzALZqvC36CFg71v1LwxEXL5JmmtrH\
        JCs%2BSL1ukD3Wrfwv%2FEh%2Fvi5WB0OLG1oRyQkoHokaMD4LT7420BWf4BMIHb1AlPIRl\
        RPxV3jybykTKOVgFEHuBs6giYr%2Bpp4FxojRB0X6wu%2BNaeWHcXIiZRJVQCIH%2Bwd5EX\
        F66%2FytMJIJyCNcuglu5%2FULy8T8lNv4n2gBa1i2r59Uw%2BkYpCFcrLyJPdJFlKOj3iO\
        MGVIfhYZIYpf6ALFlojQcojhsJ2T6bYQAIK428rnAtNNqkxFPlVstbFUKA6OfKAaPLI2EuQ\
        u%2FkC7wWoXtVz1cGaNGV8TJl07OLlvnEXua9PTOs8xB7gS%2Fv0BKI4DeVYvJAjFt5t0Ig\
        IMNqgXVTpqHNjsqCz8RdOsDtdV9Vee5bL%2Fi9HbBMai3VD7FoOwq6alWSyGXSDyu%2FbGo\
        uEFp5XTs%2FEHGKhAXUvbYGIT%2Ft5RbcbeTsxdSXRC2%2FN54y4mzZ9B0wiemzvDlHta5R\
        7gMwwNMDQlHVs6sJs3S%2BSbT8RCTlNOfVaRyjsAS1mq5deQYJCylVEUBJHYExtx1F%2Fxw\
        zCeYdaAyIY2oXsOuSaQpU7Q83hHhKr83zF7mjqJjMP%2FW870GOqUBNwGFF%2Bse4T4zDHO\
        kbARkrxtJ8thnmOC0EAk5CqsfXgkhjpMa96YiHbR9X5xGZwxiF%2FHf%2BG2T85gnwQyadU\
        Ls7DVLKIK8j4%2BNtZIp1x61%2BkpURs7xhLgAIjs9xbw6MIlG6aixVyqmHqQeJ35V4mOKi\
        UFfKDIgSI1bVvEKHaJ6qML1eE9rc2w6%2F8y6buLh5x21tdEU8NiizZ6%2FSseTXFzon4aH\
        zXlz&X-Amz-Signature=28b8f8843f32c93de79ce05037fe4177349fbecac966b8ea6c\
        f3e6aadfca1397&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-25T00:22:10.331Z"
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
UPDATE_TIME: "2025-02-24T23:23:32.135Z"
EXPIRY_TIME: "2025-02-25T00:23:23.679Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46627FNFA3M%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T232324Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDqjWZREgG9kvP8rENnSGMg6BrBbEPER129mE07OeJJXAIgUMEK6%2BIMDHMyQ%2B%2F9Od7j0i%2FQVfLDd%2FbKnFFOGcge3xQq%2FwMINxAAGgw2Mzc0MjMxODM4MDUiDODIeg72EznKHYX9ACrcA%2FdNhS1DuNNci3cbZ9avFBXDH9vswE6eyXgLVQ2Dxi0hit2cxJV0d2yCU73KAZ5PeRRUzojnSeGSTSSJ4%2FpcMDcLcOCUyCL7bkDocoADCWP%2BntRm8P0QHlYpTUTVH2BoQNqSunzhiCtDW42RvhKZD6RFT8eVIoFQa%2F5t8AgqARFIJfVJ8Gy%2FElLbscB6HpMgaoANW%2FO0WkSr3CdCa0Qerh8KDR1L9Bgus7xDVIPX0PJhq3ldub85wpjoSF9RrrPzO7DHE6b5hmElCbnzLud95sJodKwhpOqI%2BpA%2FtUPVu%2FME3URGjJLEjxTggnZAazckv1CkGVeBG1AB6R8G%2FWHfczpE9arNa9bjewaaK92k7SPTYPJmDRzSN10BtSdHBUJS6D%2FzoILpyKQIQ2IOiU2Bg8av4NR%2BU%2FVa1tEoaiJI%2BGA%2FM%2FNTJMolrJG0RBqr3IWu0kTF1sLJdxC60qR17WehJrPV9%2F%2B2MgvMuwovuP4VogD17BRMb6WToxIApRZnzHkj6yUMeDpGQQCWm6phMnuDq8pUBR%2BsqbFY1PEahjs2AZqsEl3hzcc9cNrvbLNHs9xy%2Fb7k7N0CfNQQWMw2ZeLhTM9sVpfYt6VtJ%2BEm0CIvnpg%2B12zlszogNXx9RuXbMOXV870GOqUBqMi%2BNSn%2FZi9Q9QKwxKJpYuhxvYldTIoCwXCZT9H%2B3xveiDRLM7FWu3ZMPaifGvX64TvnDXNmNdPP2nZwDm6zjaZNv2tuqs9Zr5FQDqs48sAbh1FiQGnkXo3kKi%2FEohbzQHMnxmHZoAV%2BxEfB3ugjT1IktZjefyH6YyKs40TQQ6DO4gfHZed7pkzGmLVjdCvrbf96N32tmXV6RA8uccmvSyiXJL1c&X-Amz-Signature=39f3e2992a728ccf4def3b90fa1ac074b9e24b329cbadbe382b1742273abcc1a&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46627FNFA3M%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T232324Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDqjWZREgG9kvP8rENnSGMg6BrBbEPER129mE07OeJJXAIgUMEK6%2BIMDHMyQ%2B%2F9Od7j0i%2FQVfLDd%2FbKnFFOGcge3xQq%2FwMINxAAGgw2Mzc0MjMxODM4MDUiDODIeg72EznKHYX9ACrcA%2FdNhS1DuNNci3cbZ9avFBXDH9vswE6eyXgLVQ2Dxi0hit2cxJV0d2yCU73KAZ5PeRRUzojnSeGSTSSJ4%2FpcMDcLcOCUyCL7bkDocoADCWP%2BntRm8P0QHlYpTUTVH2BoQNqSunzhiCtDW42RvhKZD6RFT8eVIoFQa%2F5t8AgqARFIJfVJ8Gy%2FElLbscB6HpMgaoANW%2FO0WkSr3CdCa0Qerh8KDR1L9Bgus7xDVIPX0PJhq3ldub85wpjoSF9RrrPzO7DHE6b5hmElCbnzLud95sJodKwhpOqI%2BpA%2FtUPVu%2FME3URGjJLEjxTggnZAazckv1CkGVeBG1AB6R8G%2FWHfczpE9arNa9bjewaaK92k7SPTYPJmDRzSN10BtSdHBUJS6D%2FzoILpyKQIQ2IOiU2Bg8av4NR%2BU%2FVa1tEoaiJI%2BGA%2FM%2FNTJMolrJG0RBqr3IWu0kTF1sLJdxC60qR17WehJrPV9%2F%2B2MgvMuwovuP4VogD17BRMb6WToxIApRZnzHkj6yUMeDpGQQCWm6phMnuDq8pUBR%2BsqbFY1PEahjs2AZqsEl3hzcc9cNrvbLNHs9xy%2Fb7k7N0CfNQQWMw2ZeLhTM9sVpfYt6VtJ%2BEm0CIvnpg%2B12zlszogNXx9RuXbMOXV870GOqUBqMi%2BNSn%2FZi9Q9QKwxKJpYuhxvYldTIoCwXCZT9H%2B3xveiDRLM7FWu3ZMPaifGvX64TvnDXNmNdPP2nZwDm6zjaZNv2tuqs9Zr5FQDqs48sAbh1FiQGnkXo3kKi%2FEohbzQHMnxmHZoAV%2BxEfB3ugjT1IktZjefyH6YyKs40TQQ6DO4gfHZed7pkzGmLVjdCvrbf96N32tmXV6RA8uccmvSyiXJL1c&X-Amz-Signature=a02d398941b8d7b28b18c4bd3ff589e1c0656935e6e42cb141059c8e002e0cd2&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46627FNFA3M%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T232324Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDqjWZREgG9kvP8rENnSGMg6BrBbEPER129mE07OeJJXAIgUMEK6%2BIMDHMyQ%2B%2F9Od7j0i%2FQVfLDd%2FbKnFFOGcge3xQq%2FwMINxAAGgw2Mzc0MjMxODM4MDUiDODIeg72EznKHYX9ACrcA%2FdNhS1DuNNci3cbZ9avFBXDH9vswE6eyXgLVQ2Dxi0hit2cxJV0d2yCU73KAZ5PeRRUzojnSeGSTSSJ4%2FpcMDcLcOCUyCL7bkDocoADCWP%2BntRm8P0QHlYpTUTVH2BoQNqSunzhiCtDW42RvhKZD6RFT8eVIoFQa%2F5t8AgqARFIJfVJ8Gy%2FElLbscB6HpMgaoANW%2FO0WkSr3CdCa0Qerh8KDR1L9Bgus7xDVIPX0PJhq3ldub85wpjoSF9RrrPzO7DHE6b5hmElCbnzLud95sJodKwhpOqI%2BpA%2FtUPVu%2FME3URGjJLEjxTggnZAazckv1CkGVeBG1AB6R8G%2FWHfczpE9arNa9bjewaaK92k7SPTYPJmDRzSN10BtSdHBUJS6D%2FzoILpyKQIQ2IOiU2Bg8av4NR%2BU%2FVa1tEoaiJI%2BGA%2FM%2FNTJMolrJG0RBqr3IWu0kTF1sLJdxC60qR17WehJrPV9%2F%2B2MgvMuwovuP4VogD17BRMb6WToxIApRZnzHkj6yUMeDpGQQCWm6phMnuDq8pUBR%2BsqbFY1PEahjs2AZqsEl3hzcc9cNrvbLNHs9xy%2Fb7k7N0CfNQQWMw2ZeLhTM9sVpfYt6VtJ%2BEm0CIvnpg%2B12zlszogNXx9RuXbMOXV870GOqUBqMi%2BNSn%2FZi9Q9QKwxKJpYuhxvYldTIoCwXCZT9H%2B3xveiDRLM7FWu3ZMPaifGvX64TvnDXNmNdPP2nZwDm6zjaZNv2tuqs9Zr5FQDqs48sAbh1FiQGnkXo3kKi%2FEohbzQHMnxmHZoAV%2BxEfB3ugjT1IktZjefyH6YyKs40TQQ6DO4gfHZed7pkzGmLVjdCvrbf96N32tmXV6RA8uccmvSyiXJL1c&X-Amz-Signature=7a6c07bd8557f8a2dfc576c2d9f3c91e0dff14b7a91d81005a1a6d7726786856&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46627FNFA3M%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T232324Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDqjWZREgG9kvP8rENnSGMg6BrBbEPER129mE07OeJJXAIgUMEK6%2BIMDHMyQ%2B%2F9Od7j0i%2FQVfLDd%2FbKnFFOGcge3xQq%2FwMINxAAGgw2Mzc0MjMxODM4MDUiDODIeg72EznKHYX9ACrcA%2FdNhS1DuNNci3cbZ9avFBXDH9vswE6eyXgLVQ2Dxi0hit2cxJV0d2yCU73KAZ5PeRRUzojnSeGSTSSJ4%2FpcMDcLcOCUyCL7bkDocoADCWP%2BntRm8P0QHlYpTUTVH2BoQNqSunzhiCtDW42RvhKZD6RFT8eVIoFQa%2F5t8AgqARFIJfVJ8Gy%2FElLbscB6HpMgaoANW%2FO0WkSr3CdCa0Qerh8KDR1L9Bgus7xDVIPX0PJhq3ldub85wpjoSF9RrrPzO7DHE6b5hmElCbnzLud95sJodKwhpOqI%2BpA%2FtUPVu%2FME3URGjJLEjxTggnZAazckv1CkGVeBG1AB6R8G%2FWHfczpE9arNa9bjewaaK92k7SPTYPJmDRzSN10BtSdHBUJS6D%2FzoILpyKQIQ2IOiU2Bg8av4NR%2BU%2FVa1tEoaiJI%2BGA%2FM%2FNTJMolrJG0RBqr3IWu0kTF1sLJdxC60qR17WehJrPV9%2F%2B2MgvMuwovuP4VogD17BRMb6WToxIApRZnzHkj6yUMeDpGQQCWm6phMnuDq8pUBR%2BsqbFY1PEahjs2AZqsEl3hzcc9cNrvbLNHs9xy%2Fb7k7N0CfNQQWMw2ZeLhTM9sVpfYt6VtJ%2BEm0CIvnpg%2B12zlszogNXx9RuXbMOXV870GOqUBqMi%2BNSn%2FZi9Q9QKwxKJpYuhxvYldTIoCwXCZT9H%2B3xveiDRLM7FWu3ZMPaifGvX64TvnDXNmNdPP2nZwDm6zjaZNv2tuqs9Zr5FQDqs48sAbh1FiQGnkXo3kKi%2FEohbzQHMnxmHZoAV%2BxEfB3ugjT1IktZjefyH6YyKs40TQQ6DO4gfHZed7pkzGmLVjdCvrbf96N32tmXV6RA8uccmvSyiXJL1c&X-Amz-Signature=82af262acdb572e79c96b78a7ae34eab965ea58420751f4808ebc08a5888e86d&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46627FNFA3M%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T232324Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDqjWZREgG9kvP8rENnSGMg6BrBbEPER129mE07OeJJXAIgUMEK6%2BIMDHMyQ%2B%2F9Od7j0i%2FQVfLDd%2FbKnFFOGcge3xQq%2FwMINxAAGgw2Mzc0MjMxODM4MDUiDODIeg72EznKHYX9ACrcA%2FdNhS1DuNNci3cbZ9avFBXDH9vswE6eyXgLVQ2Dxi0hit2cxJV0d2yCU73KAZ5PeRRUzojnSeGSTSSJ4%2FpcMDcLcOCUyCL7bkDocoADCWP%2BntRm8P0QHlYpTUTVH2BoQNqSunzhiCtDW42RvhKZD6RFT8eVIoFQa%2F5t8AgqARFIJfVJ8Gy%2FElLbscB6HpMgaoANW%2FO0WkSr3CdCa0Qerh8KDR1L9Bgus7xDVIPX0PJhq3ldub85wpjoSF9RrrPzO7DHE6b5hmElCbnzLud95sJodKwhpOqI%2BpA%2FtUPVu%2FME3URGjJLEjxTggnZAazckv1CkGVeBG1AB6R8G%2FWHfczpE9arNa9bjewaaK92k7SPTYPJmDRzSN10BtSdHBUJS6D%2FzoILpyKQIQ2IOiU2Bg8av4NR%2BU%2FVa1tEoaiJI%2BGA%2FM%2FNTJMolrJG0RBqr3IWu0kTF1sLJdxC60qR17WehJrPV9%2F%2B2MgvMuwovuP4VogD17BRMb6WToxIApRZnzHkj6yUMeDpGQQCWm6phMnuDq8pUBR%2BsqbFY1PEahjs2AZqsEl3hzcc9cNrvbLNHs9xy%2Fb7k7N0CfNQQWMw2ZeLhTM9sVpfYt6VtJ%2BEm0CIvnpg%2B12zlszogNXx9RuXbMOXV870GOqUBqMi%2BNSn%2FZi9Q9QKwxKJpYuhxvYldTIoCwXCZT9H%2B3xveiDRLM7FWu3ZMPaifGvX64TvnDXNmNdPP2nZwDm6zjaZNv2tuqs9Zr5FQDqs48sAbh1FiQGnkXo3kKi%2FEohbzQHMnxmHZoAV%2BxEfB3ugjT1IktZjefyH6YyKs40TQQ6DO4gfHZed7pkzGmLVjdCvrbf96N32tmXV6RA8uccmvSyiXJL1c&X-Amz-Signature=c3dd98ecfebc1f506fa3989aa2a0814c1609a39a14ed80b1aec0baf9c757a64b&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666N2HGGPL%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T232325Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCQOb4cCeC1%2F3kS2e1SngLlkmP5E3XSD7NvNWP3mxA1jQIhALY%2BJD8BqVXHkYaUG6ckUL38Kg3zvW82vOqC5ZbT8aqfKv8DCDcQABoMNjM3NDIzMTgzODA1IgwGHdULefvZDojMUvIq3AN7hAETQqLSP%2FC2es18C0q%2FxXf6vixPhVec8M7pBRy6hbPm52ybhalBfRKKMS2p7A%2Fj6v6mxZvnqRgk8pdg00V1Mexn6Ro%2FZV%2FvcZVx%2BjxXGKtvhQzY%2FfvHFeY9w3zcogXH4YZXkN9u%2FWYwBwa4J4LklYR5jmavSqCg2D8KnO%2BVXIYPpjXzQcJIrTLuT2m%2BWwqgZNJVqqZnilU31%2BguZYP9ypjaV2DfA7UOhMJYAV00kyGZS%2FmcWlg7uh2U4moFt0C%2BExvxgdS%2BKgJ5TJsLRffvKp3yqo27u%2BdJHEyDPkWWrNXSyHn011jpmhxh17Qo86psRxdoVwpago80jA68vSHk%2Bmk%2BLZHo%2Fg2AqelcVu%2FOR4OkvjF9nPo%2BaVGmkQyug7eXsDkf9jGRguUCuhyN61yrmYm5zxvfAFdv4Rzz7fB2txLGKtHRXXXK0%2BkGKFgfkr4hp%2Fsto2Zkd5JK4r57B4wkNr2ucxQR%2BbhFzKPHF9Bl2eIt8iW4xDPcC3ML5ZJShsCP10hwg3NMfdkzxl%2F34q1fU%2FlEQUkyiGyzptm%2FsA36%2FjzMZhn6ny4bbY5w9YpfJDAaAsC03Qxx7SanHRz6tDzabNOqcdfxiPtFWjkNsjvu7ziJyRco1e97PXB%2BaTDb1fO9BjqkAeqBzvnX8RpRp8h5KtJCOlD3zGdG2iwScJEq4ACfsZ1T5E1184vhHfwwCG4I8vvt%2BPhevdXFhsaLEI65i9%2FbLhum3MchRh9XthSslm7cIcET7nJMdMAaVNg4syjDeSkMLnD7cVZ1gQDDtk%2B%2FweV1cPxNDNTC8bilxvPZlEHbgXd0YUzLpyNC0hhxt9UAsJojn9dPsK%2BLIMETVs6FaY%2BCjnHmnoFc&X-Amz-Signature=c35a04e236dedc3d590490b28f2f011e1a6ab5bdad7dcf199b0dfc293a7576d8&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667JX7KWTP%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T232325Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCICZVNn7ONKLKMh641OCeWZ279ZZ5SGM1alnYGb0eCW6VAiEA0NBY2uRRPRlkR6DVpA5PEZaKoQn6775xBcTkDF7%2FtsQq%2FwMINxAAGgw2Mzc0MjMxODM4MDUiDNhlbKQSl5fitHObTyrcA1YXYSHSlzdZ3NHhtLnwymLla1YIkVBPuBAyt%2F4DYkOJi0Ky6s04aO%2F%2FJ3wQYLXOiGJudw5pFJD7NbjPT16dHlyj8KxWJI6IjCRV0fOHR7K%2BrFpAZkYmQ5I%2FO4e7Nw3An%2BUGboIwx5uH6YfM0CovcUGPz24vGMMVScKjZmZ1CJVYcWFXLuAZmwDWNVPkLZzXHdOEeHCGX4ferfncIs%2FMRM%2F9XLrXB1Sj59w5RpTVVt%2Faa%2B8qT4qfCudJE6Clm8lPwTRoA57%2BNRGv4JMWTgU%2BUrxosYNIZ2FcVvlN7aGIg4L5LQQtKKmGoSuDmN04Y8qbsFQKvjlfJYzE9oeezqoMkKBFjcPo7rOIiDsvrdkzTPY3pCrDLT%2BDMzcGPvbtWlC18cYt2JNcG8KKx41nenzjf67WULnaW6dhLo%2FbGNiYJfT1AISz7toSUfE1Y5dPJVNS%2FqvzfSJXbJiXexdthToa8GPLYPHnEdwxnSyDgyQeKAq6s2CJga%2FpHl0XtrKcNMvjxn%2BvXYBcPfmAzqK4zrU%2BE5QBvwgIUjmiEDlUyG2xeoTY6fma7hiB%2FZXmW4qGHogOJ1AbMU0r%2BJ2uGHZgfwM08btwe1VPyZaOmS9SEYvHc2Sq9lN56kD1ME2di7%2FCMOrW870GOqUB0eqRHPdZu9oNve8FTYdJ5gqn93J1xZcH8PDd0GX%2FTxj6wZfcwU8uVffLzsK2d2tEPnxdGUzMIxMkSh51z7CvrlRfy42YPd9zDxu4w9RuikfD%2B4zGLLPcIR9mSrszj6H%2B4UETEoOrKkMT8MXyDbJ5vObb9PsqYNSBA%2BiH1KGESFQd1tz2RUvshosYtl5BHlnhGiZ3rBKBaz67sccYwkAd43%2FY%2F3Eo&X-Amz-Signature=380d038ede849175dc19aba3c4fd454efd71d7b8c0a54b104383e256ba3a727f&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46627FNFA3M%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T232324Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDqjWZREgG9kvP8rENnSGMg6BrBbEPER129mE07OeJJXAIgUMEK6%2BIMDHMyQ%2B%2F9Od7j0i%2FQVfLDd%2FbKnFFOGcge3xQq%2FwMINxAAGgw2Mzc0MjMxODM4MDUiDODIeg72EznKHYX9ACrcA%2FdNhS1DuNNci3cbZ9avFBXDH9vswE6eyXgLVQ2Dxi0hit2cxJV0d2yCU73KAZ5PeRRUzojnSeGSTSSJ4%2FpcMDcLcOCUyCL7bkDocoADCWP%2BntRm8P0QHlYpTUTVH2BoQNqSunzhiCtDW42RvhKZD6RFT8eVIoFQa%2F5t8AgqARFIJfVJ8Gy%2FElLbscB6HpMgaoANW%2FO0WkSr3CdCa0Qerh8KDR1L9Bgus7xDVIPX0PJhq3ldub85wpjoSF9RrrPzO7DHE6b5hmElCbnzLud95sJodKwhpOqI%2BpA%2FtUPVu%2FME3URGjJLEjxTggnZAazckv1CkGVeBG1AB6R8G%2FWHfczpE9arNa9bjewaaK92k7SPTYPJmDRzSN10BtSdHBUJS6D%2FzoILpyKQIQ2IOiU2Bg8av4NR%2BU%2FVa1tEoaiJI%2BGA%2FM%2FNTJMolrJG0RBqr3IWu0kTF1sLJdxC60qR17WehJrPV9%2F%2B2MgvMuwovuP4VogD17BRMb6WToxIApRZnzHkj6yUMeDpGQQCWm6phMnuDq8pUBR%2BsqbFY1PEahjs2AZqsEl3hzcc9cNrvbLNHs9xy%2Fb7k7N0CfNQQWMw2ZeLhTM9sVpfYt6VtJ%2BEm0CIvnpg%2B12zlszogNXx9RuXbMOXV870GOqUBqMi%2BNSn%2FZi9Q9QKwxKJpYuhxvYldTIoCwXCZT9H%2B3xveiDRLM7FWu3ZMPaifGvX64TvnDXNmNdPP2nZwDm6zjaZNv2tuqs9Zr5FQDqs48sAbh1FiQGnkXo3kKi%2FEohbzQHMnxmHZoAV%2BxEfB3ugjT1IktZjefyH6YyKs40TQQ6DO4gfHZed7pkzGmLVjdCvrbf96N32tmXV6RA8uccmvSyiXJL1c&X-Amz-Signature=2383c793158aefdefef180ac83d21fdc0d0b068ed0804aa7a399616de6cfa52d&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46627FNFA3M%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T232324Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDqjWZREgG9kvP8rENnSGMg6BrBbEPER129mE07OeJJXAIgUMEK6%2BIMDHMyQ%2B%2F9Od7j0i%2FQVfLDd%2FbKnFFOGcge3xQq%2FwMINxAAGgw2Mzc0MjMxODM4MDUiDODIeg72EznKHYX9ACrcA%2FdNhS1DuNNci3cbZ9avFBXDH9vswE6eyXgLVQ2Dxi0hit2cxJV0d2yCU73KAZ5PeRRUzojnSeGSTSSJ4%2FpcMDcLcOCUyCL7bkDocoADCWP%2BntRm8P0QHlYpTUTVH2BoQNqSunzhiCtDW42RvhKZD6RFT8eVIoFQa%2F5t8AgqARFIJfVJ8Gy%2FElLbscB6HpMgaoANW%2FO0WkSr3CdCa0Qerh8KDR1L9Bgus7xDVIPX0PJhq3ldub85wpjoSF9RrrPzO7DHE6b5hmElCbnzLud95sJodKwhpOqI%2BpA%2FtUPVu%2FME3URGjJLEjxTggnZAazckv1CkGVeBG1AB6R8G%2FWHfczpE9arNa9bjewaaK92k7SPTYPJmDRzSN10BtSdHBUJS6D%2FzoILpyKQIQ2IOiU2Bg8av4NR%2BU%2FVa1tEoaiJI%2BGA%2FM%2FNTJMolrJG0RBqr3IWu0kTF1sLJdxC60qR17WehJrPV9%2F%2B2MgvMuwovuP4VogD17BRMb6WToxIApRZnzHkj6yUMeDpGQQCWm6phMnuDq8pUBR%2BsqbFY1PEahjs2AZqsEl3hzcc9cNrvbLNHs9xy%2Fb7k7N0CfNQQWMw2ZeLhTM9sVpfYt6VtJ%2BEm0CIvnpg%2B12zlszogNXx9RuXbMOXV870GOqUBqMi%2BNSn%2FZi9Q9QKwxKJpYuhxvYldTIoCwXCZT9H%2B3xveiDRLM7FWu3ZMPaifGvX64TvnDXNmNdPP2nZwDm6zjaZNv2tuqs9Zr5FQDqs48sAbh1FiQGnkXo3kKi%2FEohbzQHMnxmHZoAV%2BxEfB3ugjT1IktZjefyH6YyKs40TQQ6DO4gfHZed7pkzGmLVjdCvrbf96N32tmXV6RA8uccmvSyiXJL1c&X-Amz-Signature=79b2f5b63a65596495564e9c9a12f22698caceb36b6aaf551a0bdbb8e0125872&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46627FNFA3M%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T232324Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDqjWZREgG9kvP8rENnSGMg6BrBbEPER129mE07OeJJXAIgUMEK6%2BIMDHMyQ%2B%2F9Od7j0i%2FQVfLDd%2FbKnFFOGcge3xQq%2FwMINxAAGgw2Mzc0MjMxODM4MDUiDODIeg72EznKHYX9ACrcA%2FdNhS1DuNNci3cbZ9avFBXDH9vswE6eyXgLVQ2Dxi0hit2cxJV0d2yCU73KAZ5PeRRUzojnSeGSTSSJ4%2FpcMDcLcOCUyCL7bkDocoADCWP%2BntRm8P0QHlYpTUTVH2BoQNqSunzhiCtDW42RvhKZD6RFT8eVIoFQa%2F5t8AgqARFIJfVJ8Gy%2FElLbscB6HpMgaoANW%2FO0WkSr3CdCa0Qerh8KDR1L9Bgus7xDVIPX0PJhq3ldub85wpjoSF9RrrPzO7DHE6b5hmElCbnzLud95sJodKwhpOqI%2BpA%2FtUPVu%2FME3URGjJLEjxTggnZAazckv1CkGVeBG1AB6R8G%2FWHfczpE9arNa9bjewaaK92k7SPTYPJmDRzSN10BtSdHBUJS6D%2FzoILpyKQIQ2IOiU2Bg8av4NR%2BU%2FVa1tEoaiJI%2BGA%2FM%2FNTJMolrJG0RBqr3IWu0kTF1sLJdxC60qR17WehJrPV9%2F%2B2MgvMuwovuP4VogD17BRMb6WToxIApRZnzHkj6yUMeDpGQQCWm6phMnuDq8pUBR%2BsqbFY1PEahjs2AZqsEl3hzcc9cNrvbLNHs9xy%2Fb7k7N0CfNQQWMw2ZeLhTM9sVpfYt6VtJ%2BEm0CIvnpg%2B12zlszogNXx9RuXbMOXV870GOqUBqMi%2BNSn%2FZi9Q9QKwxKJpYuhxvYldTIoCwXCZT9H%2B3xveiDRLM7FWu3ZMPaifGvX64TvnDXNmNdPP2nZwDm6zjaZNv2tuqs9Zr5FQDqs48sAbh1FiQGnkXo3kKi%2FEohbzQHMnxmHZoAV%2BxEfB3ugjT1IktZjefyH6YyKs40TQQ6DO4gfHZed7pkzGmLVjdCvrbf96N32tmXV6RA8uccmvSyiXJL1c&X-Amz-Signature=9c55abe9a74fb794e330bb0eab2d8acf18839660b4ffc192e43707e046808c9f&X-Amz-SignedHeaders=host&x-id=GetObject)


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

