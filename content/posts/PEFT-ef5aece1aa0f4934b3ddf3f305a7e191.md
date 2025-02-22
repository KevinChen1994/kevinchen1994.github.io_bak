---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466T7PO4KBX%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250222T182943Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEMj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDrp6ETWc6kI2xLnIq\
  tOtjPvGIf%2FlLqiTKPhf8yDCbY%2BwIhAKSChI91GG686uKHgu1X2FdudpnoEjq0GDJNCOABAIYc\
  KogECPD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwYUY8dd2d%2BO8G\
  kKWsq3AOyZ19UcufFvMubk088Wp2v2yikYW3s1umBt2cqyflXsGnj4XThYYy59VwPq7Qv4%2FA1XV\
  aqxflWMv%2Bt0F8dI%2BY%2FF8%2FoIjkkj%2F%2Fw%2F9DXZol7cn5Zzeud1y%2FRc0jowik%2Bd\
  KRUevoalZ%2FfKSoQblKPQTAHrDehsr7yqQAmjWMAoizbVato1cV9%2FSu9yJqzSKdufPFsHALtjV\
  d3aBqI5qUcDBniXRVrXs0ik%2FZQHPk48k0Lp0zw9ZvToewaIt5MDHxZSrAogywxxA5Gn0yAXK5i7\
  olxigFSYp5Ls9qUqOfqI7wg2B%2FxG3umuC4S5CCgfUQ4oy3ssdmLnUN8Ob4jZpuRzbBZ9iuev6H%\
  2F0iVdB8Lml%2FEHnT4Q14NcnNDf3g9L0bXhmjuRBOdu1545q4MQeFfjZZJY%2BWAxZ0XgLTExGSv\
  I5ZdkQzIPik57ZCqWpzKalqfdHmNWc8yFzBoQ0PqFLXCf3uUaU%2FtsXwU7dIGTyk0iAlfTD7uKtx\
  ot8YWOYtEAolSnA3ZmF0m3eupOtQToAspKexFeJlz8ApDyCW3koiJU2kCtP2ZO6Fd8TakECe681JZ\
  9CFx3GaLM5ZuchYHEkes13C7jo4kHyDLhSSSGHBAp82s6bBToH99gGZmAjOrSDjC32Oe9BjqkAQmK\
  PSevrnNJOS%2F1mYYwDQXFegQwfnWjrGo6NPRYu0KDYnr%2FJ7uhbhGPgKi1yq%2Bq5YhaYrTdk13\
  EXegxLDGC%2B93DxojXExykmwSzP11XEg0cXXLqjSRkxxZrAMRym33T6jFQKxP%2BIz5P35VB4e8R\
  86ntifehCCgck8Q%2FZutHEEoPwpq8o5Odg1TY%2FjkaWTV%2FgOBnz%2FMGOFozQnBF3eNIRHbSr\
  4JV&X-Amz-Signature=00a3355624a2fcaca5acbb12d58a13809f763cfd555707adf5a362c39\
  17d584d&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466TVNBYDD4%2F20250222%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250222T182827Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEY\
        CIQCDwQ4sFko%2F5kmqPVX5yTAv1YjVe30hqJSdFmnZPl1yzAIhALl2OhCVv4Qoj4vFWXC8\
        96fFlM3vbjKS66XODTL6YY%2FdKogECPL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMN\
        jM3NDIzMTgzODA1Igy4%2BiMqWfqC4Kfqrzsq3AMtSZYa7Bqkd7oi2B%2BgzuvkTFghRlVf\
        yAcS4NLan23tR31Oo%2FuK2R8DhZo4F4CnA3bjk2odH621eoyXxWa6FyBcOxhbY8DH2tAcb\
        v%2B3%2Bmszd2UUR9%2FsiiALGXJiqto4bFKvZNN4w4WkRMNGTYAZYzWwxXWnXvP1gcqt%2\
        Bl9iXU3JbyCNweOBAdGJbijLsZSdg75FDwn3yI7E5YttdK%2B%2BFH0qLZ%2Bg5sKF13EHJ\
        6se31DsQVwgWEoOEd7JY0YZK23cTv1wXtx5nB9hRIV1zPKhLtx1TiaVIL0r1iZgnIlsAGmz\
        61y3tCG6jLb9DK32ToHJP5%2F0XieWZC9UEyLQH6NEbn9PrMUoDVWd9H9%2FcS9Pu%2BZTG\
        M8wosBBhab8VApZNCPkhlUWILugYIeyZ1VXGhcurZ%2BZ%2Bq3OX%2FNCPf0ZIKtRWsMxYz\
        An0nA%2FTx3szX73Uu2Za6%2FQxLpAxhs7z7MSmAAmUW9ABTgJm6hrVupPLlUTDpLp4GrgR\
        zIIegnqUnNnTGk9BaRrXZ%2BOqBLsyFqjR%2F1i3GX1BS0IJbsz5IvQD5bHxKulURnYxoRQ\
        u3gJRG4PDcxx65ZsUL%2F%2FFoLNiF07uvQpv6qgyqTnr5oLCgoV5hKrKzNfBkAgnCn7ZCh\
        BOsGcvDDEhui9BjqkAURhGZD7yC2XV1psPQSKAolgqQBJMTE%2FBhd7qWF9jdsplnAKMF0h\
        aTWOQFlAyvaOdoP9BUz%2FzFQLPE7wSXo0HYOLz3NDAt7cOB7pW15o9foE%2FAo7JdXkaib\
        UNq%2FRcpprqSYenWFkpuhXcKij6z9n4vp2rRaSCmWaAEJdp5Asu%2FarkTKLUmMgcheKGp\
        SRPOfh45AaviAs5mhnjqz9oOvFknEI7LYI&X-Amz-Signature=e637291b94301db6fa5a\
        8e767ed810d29ce6ca935125635ee10d48ed752825c2&X-Amz-SignedHeaders=host&x\
        -id=GetObject"
      expiry_time: "2025-02-22T19:28:27.678Z"
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
UPDATE_TIME: "2025-02-22T18:29:49.375Z"
EXPIRY_TIME: "2025-02-22T19:29:40.852Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YKZN67MY%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T182941Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEbirBmE5aCqCcCJ%2Bd7JZsqLrOWefLxf%2BofgcYtva3pPAiBaeFHvryx6rxmXDJEM48zFPmKXaJ2WT7WI7OgCKIthiSqIBAjy%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMdv2MB%2BM5m1b3N8xQKtwDFU9VWHXmnrCi9%2Ba0Mdnv%2BJuRtCDQI3nJ2KPlpzO7tqnES0MmRbt0%2FO6AcEpAo%2FcgXZ%2BkqqdQcgLt7kxpoMfDdASBhX2%2BY%2BP26WgSQ8pur8fNulhXeE87dU%2FotylRlaPLzohEp2Dwze5F%2BOXAvtA04J4ORUmENs8pu1u5eNbNaCvjY2H6Bl7copqKtdP19NN5zXdNYWQGohq757vV%2Fz3EMoxZ0F7J4Xb2lXkbTEK9Kf9g3h0CqNCCwOpdlcPo4uAjzCunYf%2BlQCB2u6wkyVFYflgsH%2Bwn7mDLlfJfJNYjZg%2BlM8iwyxHXaMVYISa%2F84bkDmQ%2BGaiV67ofHrmd8d4CB%2FpJ2Ju%2BpHMao0z%2FEUhEm7lIhPPVjUXXxvAcGwVrqrJIA3LgYRmhO%2BSb9LsKT%2FuRe4PJqxkFhf1LOK75Wkx5gES2TORvRwSCjLq9ieujS%2F7osp5pwUE6e52cpc680CnEjmdQY9AvOqUxnPSaX%2FUVME0CeDcJWheOErE9bRh4e%2Fw3K6Bw6N0hlq%2FOiTzwah2S7odUqfJ%2FECZdDWarXQw5A6tZuTPxy0cv88G%2FVkSNDEhyD6kPEuMBxtm5ulz64ozYEsHMU8UR51gYda6RQSxx1rUpFqF%2FRwFl7cHU13kwkIrovQY6pgFft2yG2b5mLHLRvwB533tB8t%2F4UsPcJm9F70rik%2BA23pP94BZP69gUI1eFRltk18C581D7kQ%2BsXOrNRwRoaNjEa27jvYaHe%2Fg%2F%2FfMuj3LJVDQ4PB3dLakwLPzHxNl5gzXjjsBc5VLEkahhnlWcagqNripN7KEHDibrR%2BfyZYHPNBA3cbXJy7zzntzflzhnmu9vW2%2B4Zv9IVfNszMlg6JRN0YWAkVwT&X-Amz-Signature=23fa4eedc65e15d889da867c22795123abc7ef48fef9e2d00e726193b1a84651&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YKZN67MY%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T182941Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEbirBmE5aCqCcCJ%2Bd7JZsqLrOWefLxf%2BofgcYtva3pPAiBaeFHvryx6rxmXDJEM48zFPmKXaJ2WT7WI7OgCKIthiSqIBAjy%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMdv2MB%2BM5m1b3N8xQKtwDFU9VWHXmnrCi9%2Ba0Mdnv%2BJuRtCDQI3nJ2KPlpzO7tqnES0MmRbt0%2FO6AcEpAo%2FcgXZ%2BkqqdQcgLt7kxpoMfDdASBhX2%2BY%2BP26WgSQ8pur8fNulhXeE87dU%2FotylRlaPLzohEp2Dwze5F%2BOXAvtA04J4ORUmENs8pu1u5eNbNaCvjY2H6Bl7copqKtdP19NN5zXdNYWQGohq757vV%2Fz3EMoxZ0F7J4Xb2lXkbTEK9Kf9g3h0CqNCCwOpdlcPo4uAjzCunYf%2BlQCB2u6wkyVFYflgsH%2Bwn7mDLlfJfJNYjZg%2BlM8iwyxHXaMVYISa%2F84bkDmQ%2BGaiV67ofHrmd8d4CB%2FpJ2Ju%2BpHMao0z%2FEUhEm7lIhPPVjUXXxvAcGwVrqrJIA3LgYRmhO%2BSb9LsKT%2FuRe4PJqxkFhf1LOK75Wkx5gES2TORvRwSCjLq9ieujS%2F7osp5pwUE6e52cpc680CnEjmdQY9AvOqUxnPSaX%2FUVME0CeDcJWheOErE9bRh4e%2Fw3K6Bw6N0hlq%2FOiTzwah2S7odUqfJ%2FECZdDWarXQw5A6tZuTPxy0cv88G%2FVkSNDEhyD6kPEuMBxtm5ulz64ozYEsHMU8UR51gYda6RQSxx1rUpFqF%2FRwFl7cHU13kwkIrovQY6pgFft2yG2b5mLHLRvwB533tB8t%2F4UsPcJm9F70rik%2BA23pP94BZP69gUI1eFRltk18C581D7kQ%2BsXOrNRwRoaNjEa27jvYaHe%2Fg%2F%2FfMuj3LJVDQ4PB3dLakwLPzHxNl5gzXjjsBc5VLEkahhnlWcagqNripN7KEHDibrR%2BfyZYHPNBA3cbXJy7zzntzflzhnmu9vW2%2B4Zv9IVfNszMlg6JRN0YWAkVwT&X-Amz-Signature=e7990674b8403cecc7b97e3f12d9c86e9ec825b9ecae161ce3eeeb59e97461b3&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YKZN67MY%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T182941Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEbirBmE5aCqCcCJ%2Bd7JZsqLrOWefLxf%2BofgcYtva3pPAiBaeFHvryx6rxmXDJEM48zFPmKXaJ2WT7WI7OgCKIthiSqIBAjy%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMdv2MB%2BM5m1b3N8xQKtwDFU9VWHXmnrCi9%2Ba0Mdnv%2BJuRtCDQI3nJ2KPlpzO7tqnES0MmRbt0%2FO6AcEpAo%2FcgXZ%2BkqqdQcgLt7kxpoMfDdASBhX2%2BY%2BP26WgSQ8pur8fNulhXeE87dU%2FotylRlaPLzohEp2Dwze5F%2BOXAvtA04J4ORUmENs8pu1u5eNbNaCvjY2H6Bl7copqKtdP19NN5zXdNYWQGohq757vV%2Fz3EMoxZ0F7J4Xb2lXkbTEK9Kf9g3h0CqNCCwOpdlcPo4uAjzCunYf%2BlQCB2u6wkyVFYflgsH%2Bwn7mDLlfJfJNYjZg%2BlM8iwyxHXaMVYISa%2F84bkDmQ%2BGaiV67ofHrmd8d4CB%2FpJ2Ju%2BpHMao0z%2FEUhEm7lIhPPVjUXXxvAcGwVrqrJIA3LgYRmhO%2BSb9LsKT%2FuRe4PJqxkFhf1LOK75Wkx5gES2TORvRwSCjLq9ieujS%2F7osp5pwUE6e52cpc680CnEjmdQY9AvOqUxnPSaX%2FUVME0CeDcJWheOErE9bRh4e%2Fw3K6Bw6N0hlq%2FOiTzwah2S7odUqfJ%2FECZdDWarXQw5A6tZuTPxy0cv88G%2FVkSNDEhyD6kPEuMBxtm5ulz64ozYEsHMU8UR51gYda6RQSxx1rUpFqF%2FRwFl7cHU13kwkIrovQY6pgFft2yG2b5mLHLRvwB533tB8t%2F4UsPcJm9F70rik%2BA23pP94BZP69gUI1eFRltk18C581D7kQ%2BsXOrNRwRoaNjEa27jvYaHe%2Fg%2F%2FfMuj3LJVDQ4PB3dLakwLPzHxNl5gzXjjsBc5VLEkahhnlWcagqNripN7KEHDibrR%2BfyZYHPNBA3cbXJy7zzntzflzhnmu9vW2%2B4Zv9IVfNszMlg6JRN0YWAkVwT&X-Amz-Signature=081d9d5aff0d402f426c79bf4d40ab10055379632962b075b221dc6abd551091&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YKZN67MY%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T182941Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEbirBmE5aCqCcCJ%2Bd7JZsqLrOWefLxf%2BofgcYtva3pPAiBaeFHvryx6rxmXDJEM48zFPmKXaJ2WT7WI7OgCKIthiSqIBAjy%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMdv2MB%2BM5m1b3N8xQKtwDFU9VWHXmnrCi9%2Ba0Mdnv%2BJuRtCDQI3nJ2KPlpzO7tqnES0MmRbt0%2FO6AcEpAo%2FcgXZ%2BkqqdQcgLt7kxpoMfDdASBhX2%2BY%2BP26WgSQ8pur8fNulhXeE87dU%2FotylRlaPLzohEp2Dwze5F%2BOXAvtA04J4ORUmENs8pu1u5eNbNaCvjY2H6Bl7copqKtdP19NN5zXdNYWQGohq757vV%2Fz3EMoxZ0F7J4Xb2lXkbTEK9Kf9g3h0CqNCCwOpdlcPo4uAjzCunYf%2BlQCB2u6wkyVFYflgsH%2Bwn7mDLlfJfJNYjZg%2BlM8iwyxHXaMVYISa%2F84bkDmQ%2BGaiV67ofHrmd8d4CB%2FpJ2Ju%2BpHMao0z%2FEUhEm7lIhPPVjUXXxvAcGwVrqrJIA3LgYRmhO%2BSb9LsKT%2FuRe4PJqxkFhf1LOK75Wkx5gES2TORvRwSCjLq9ieujS%2F7osp5pwUE6e52cpc680CnEjmdQY9AvOqUxnPSaX%2FUVME0CeDcJWheOErE9bRh4e%2Fw3K6Bw6N0hlq%2FOiTzwah2S7odUqfJ%2FECZdDWarXQw5A6tZuTPxy0cv88G%2FVkSNDEhyD6kPEuMBxtm5ulz64ozYEsHMU8UR51gYda6RQSxx1rUpFqF%2FRwFl7cHU13kwkIrovQY6pgFft2yG2b5mLHLRvwB533tB8t%2F4UsPcJm9F70rik%2BA23pP94BZP69gUI1eFRltk18C581D7kQ%2BsXOrNRwRoaNjEa27jvYaHe%2Fg%2F%2FfMuj3LJVDQ4PB3dLakwLPzHxNl5gzXjjsBc5VLEkahhnlWcagqNripN7KEHDibrR%2BfyZYHPNBA3cbXJy7zzntzflzhnmu9vW2%2B4Zv9IVfNszMlg6JRN0YWAkVwT&X-Amz-Signature=0585ee19433d258b2fd2c6d97cb348791c287097a1791c5a7b1e7a6de9d10bae&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YKZN67MY%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T182941Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEbirBmE5aCqCcCJ%2Bd7JZsqLrOWefLxf%2BofgcYtva3pPAiBaeFHvryx6rxmXDJEM48zFPmKXaJ2WT7WI7OgCKIthiSqIBAjy%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMdv2MB%2BM5m1b3N8xQKtwDFU9VWHXmnrCi9%2Ba0Mdnv%2BJuRtCDQI3nJ2KPlpzO7tqnES0MmRbt0%2FO6AcEpAo%2FcgXZ%2BkqqdQcgLt7kxpoMfDdASBhX2%2BY%2BP26WgSQ8pur8fNulhXeE87dU%2FotylRlaPLzohEp2Dwze5F%2BOXAvtA04J4ORUmENs8pu1u5eNbNaCvjY2H6Bl7copqKtdP19NN5zXdNYWQGohq757vV%2Fz3EMoxZ0F7J4Xb2lXkbTEK9Kf9g3h0CqNCCwOpdlcPo4uAjzCunYf%2BlQCB2u6wkyVFYflgsH%2Bwn7mDLlfJfJNYjZg%2BlM8iwyxHXaMVYISa%2F84bkDmQ%2BGaiV67ofHrmd8d4CB%2FpJ2Ju%2BpHMao0z%2FEUhEm7lIhPPVjUXXxvAcGwVrqrJIA3LgYRmhO%2BSb9LsKT%2FuRe4PJqxkFhf1LOK75Wkx5gES2TORvRwSCjLq9ieujS%2F7osp5pwUE6e52cpc680CnEjmdQY9AvOqUxnPSaX%2FUVME0CeDcJWheOErE9bRh4e%2Fw3K6Bw6N0hlq%2FOiTzwah2S7odUqfJ%2FECZdDWarXQw5A6tZuTPxy0cv88G%2FVkSNDEhyD6kPEuMBxtm5ulz64ozYEsHMU8UR51gYda6RQSxx1rUpFqF%2FRwFl7cHU13kwkIrovQY6pgFft2yG2b5mLHLRvwB533tB8t%2F4UsPcJm9F70rik%2BA23pP94BZP69gUI1eFRltk18C581D7kQ%2BsXOrNRwRoaNjEa27jvYaHe%2Fg%2F%2FfMuj3LJVDQ4PB3dLakwLPzHxNl5gzXjjsBc5VLEkahhnlWcagqNripN7KEHDibrR%2BfyZYHPNBA3cbXJy7zzntzflzhnmu9vW2%2B4Zv9IVfNszMlg6JRN0YWAkVwT&X-Amz-Signature=315c5f455842e1306ab074eaa7efc2b322def31c8ae4aa442c0215d6f0fc4b40&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RDDO6TGL%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T182941Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQClFKBeYGExdCtl4bxuhIB%2BoqN9a9zznAdV6j7X3%2BjISAIgC2l5sV8of70UC0yEnHcocpSYRnKliVaumjIWPiYFjy0qiAQI8f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKOAujIV0N6RaFgNUSrcAyMt1NIrbWyqa1wDauiN%2FsXLYgwclDRQhT8hSknU5NuJm%2FQ0xVaJRdCwc%2FlmAPkkHbQmVhdOSIJp0XLbklM%2BrrMRvOv8WaZWNgvda87QvvglWwkIsSkJqTzWNBOCR2A%2BjJxnJi%2F5Kv%2BIH0xFQeUKrXLhbWCngbqPgPTADl0KqHFtAyaadVD1Hf93kBIsDFZRyAZpYKrumgAw3ZmjfyfcvNOhnZNbsObuPn%2FsdeKGXvzHVXhXlTG1yLUE6JuHVo8LRe7xEp8y0QfTGz0KaGuT4O5pdKcvykRSl7lo8M7eauOA%2F%2Fn9b3EAWfjODntu3vqR5haXsti%2FMYF2q7vcUX8AeEmyl%2FWdguNG1SBLvyTUx54u0gM0Xv2lUT5PlTQkBp3X2o2jLfbPMPnW263xaZrAnfr%2FXVKi9eGeLFgoayg3i1%2F0tPYZuF8vd845ILAZcriP1oxJoylBH5Ps3a8IaCKPEAoMOcRJIWLuZeeb5yXInOPgR9aUWjXKwcRlwTnzQBww995%2BZS%2BFIJkWiY53ypp51fhF5My21n6Th1VV4P2JHAJCum5P5%2BMRRtJnAtV%2B9HNb0WA0TKMBgWG58223csyXRqzYeOZ6lran2BtoLQF%2B29U%2FO4m8pQH%2FsLTJ2OZbMPfa570GOqUBvwMQfF3%2FdY9Y7%2Fno3aXcUyX5xrKPfpq5wt0Ec%2BfcgA2rHUKWJCXUkX3Lq1KJv2P5KhKT750WIzt5jFQPW7voaySMOW7qV%2Bhn5p9rFX1NrpATpzIHPHt%2Fg4LiH309KGMc3MxpZNj0VZfU17tTWz4Kju%2Bjwj4ey90lfMUIDNvho1JAkYMteDZnZ5xDkgBa4ukJ5oH4LJ4vNoEusnW6mgfHKisXGv5K&X-Amz-Signature=41a846af5a69eb624d1faa90a8b1dc62bf44df2b40220e7a2e7ff5da112e9d3e&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Q3CYZYDZ%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T182942Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIFZfxe1x5T5E7bov28atFLGwPn2Qeb5HZrRAhJSOka7nAiAx9CSrS20cqd6K%2B%2BUYjwkv0tweBENoeDJVfiIu5YDvfiqIBAjy%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMjayaexXUbRJICsWBKtwDMHZT4BV14a%2FMTHDC9BoBA4Zt%2FxP1d1NhU0%2Bu1SCx7bppjAZQZ323HfLB81%2BBqiX6%2BUFg7mE8yBlsqHzcqE1V4iJKkHxVOr2ZSzEobcb8P87o5QaFXhqN2lKbDJC4hogoSIcEdFnyiM9Zr%2BipJ%2F%2B8tBBbPDhu84jnv9vHo%2ByTVc1t7TqTpL5sovVG0ZsLKFwKM5th9pL758E39%2BSIVWXkwVeHIC1iUOhMaluxtkSp01SG8%2Bz%2B%2FTVsmpYBxRr5RJY9YRU8v8l%2BSAHCJhkmxb0Y0LJ%2FzuiV2LZht7S%2FYikTLWBpIzo%2F1Dwgq%2FITJ2ZouyRcXXEa80IfginiZtsDU%2Fcd9xESlXDuVSVZjSFFc%2BpkM%2B3o3Lh7aQkK4F2p0wkl8IiIQhMXd5h%2Bv0c09Qk0qTdGZVTwgJLzM7zcGOisnqPSIDZJmS5GG86dQrmqbVkl%2BOueXSImwJojAD3dX6qforQwiylarKya7P38gnHspuiE74HGfRqjinkpushHawbmbZirSCTKWKWp9h8JDThYsRP7eFHMHXCzr53PqLqZ9ndNVeALIaCNrMgpWMw6LzwMqAaxJZ2%2FRQV8wFJtZMm%2B4t6kfpMrgmuOhF02ziQqZSzHgU78MSjUrbPhZIlGFJAwgIvovQY6pgHYxG8qXiVoDfr%2FdDashcuXJNBBKeXuJ4Cxzkmv7kNSZ6hHqbnChMwWayv0N0a5lPigY9YAjFAqtyX2hbRtpnaomaVjPN0aUyJxO27mOH3Z1mPCQf8LYFKbiejourdl4QpxWZ%2BOMgcAOZXPEqCcZUkNHn7vNC7PA0OixjNXHZryisPJTvJIMpD7zcci5%2Bf4FbpaqlXrYQ9Xzyn%2F6sHV1vtCp55AvyW8&X-Amz-Signature=8c33c4a5c64e806b74fe724b2bf388e8a66c5116be9d90e2aabac4aecc270e59&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YKZN67MY%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T182941Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEbirBmE5aCqCcCJ%2Bd7JZsqLrOWefLxf%2BofgcYtva3pPAiBaeFHvryx6rxmXDJEM48zFPmKXaJ2WT7WI7OgCKIthiSqIBAjy%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMdv2MB%2BM5m1b3N8xQKtwDFU9VWHXmnrCi9%2Ba0Mdnv%2BJuRtCDQI3nJ2KPlpzO7tqnES0MmRbt0%2FO6AcEpAo%2FcgXZ%2BkqqdQcgLt7kxpoMfDdASBhX2%2BY%2BP26WgSQ8pur8fNulhXeE87dU%2FotylRlaPLzohEp2Dwze5F%2BOXAvtA04J4ORUmENs8pu1u5eNbNaCvjY2H6Bl7copqKtdP19NN5zXdNYWQGohq757vV%2Fz3EMoxZ0F7J4Xb2lXkbTEK9Kf9g3h0CqNCCwOpdlcPo4uAjzCunYf%2BlQCB2u6wkyVFYflgsH%2Bwn7mDLlfJfJNYjZg%2BlM8iwyxHXaMVYISa%2F84bkDmQ%2BGaiV67ofHrmd8d4CB%2FpJ2Ju%2BpHMao0z%2FEUhEm7lIhPPVjUXXxvAcGwVrqrJIA3LgYRmhO%2BSb9LsKT%2FuRe4PJqxkFhf1LOK75Wkx5gES2TORvRwSCjLq9ieujS%2F7osp5pwUE6e52cpc680CnEjmdQY9AvOqUxnPSaX%2FUVME0CeDcJWheOErE9bRh4e%2Fw3K6Bw6N0hlq%2FOiTzwah2S7odUqfJ%2FECZdDWarXQw5A6tZuTPxy0cv88G%2FVkSNDEhyD6kPEuMBxtm5ulz64ozYEsHMU8UR51gYda6RQSxx1rUpFqF%2FRwFl7cHU13kwkIrovQY6pgFft2yG2b5mLHLRvwB533tB8t%2F4UsPcJm9F70rik%2BA23pP94BZP69gUI1eFRltk18C581D7kQ%2BsXOrNRwRoaNjEa27jvYaHe%2Fg%2F%2FfMuj3LJVDQ4PB3dLakwLPzHxNl5gzXjjsBc5VLEkahhnlWcagqNripN7KEHDibrR%2BfyZYHPNBA3cbXJy7zzntzflzhnmu9vW2%2B4Zv9IVfNszMlg6JRN0YWAkVwT&X-Amz-Signature=a525fa5862471f0e266e82e7bfff1d23c4fa3e331ebb86fd48259ae97f703e06&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YKZN67MY%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T182941Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEbirBmE5aCqCcCJ%2Bd7JZsqLrOWefLxf%2BofgcYtva3pPAiBaeFHvryx6rxmXDJEM48zFPmKXaJ2WT7WI7OgCKIthiSqIBAjy%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMdv2MB%2BM5m1b3N8xQKtwDFU9VWHXmnrCi9%2Ba0Mdnv%2BJuRtCDQI3nJ2KPlpzO7tqnES0MmRbt0%2FO6AcEpAo%2FcgXZ%2BkqqdQcgLt7kxpoMfDdASBhX2%2BY%2BP26WgSQ8pur8fNulhXeE87dU%2FotylRlaPLzohEp2Dwze5F%2BOXAvtA04J4ORUmENs8pu1u5eNbNaCvjY2H6Bl7copqKtdP19NN5zXdNYWQGohq757vV%2Fz3EMoxZ0F7J4Xb2lXkbTEK9Kf9g3h0CqNCCwOpdlcPo4uAjzCunYf%2BlQCB2u6wkyVFYflgsH%2Bwn7mDLlfJfJNYjZg%2BlM8iwyxHXaMVYISa%2F84bkDmQ%2BGaiV67ofHrmd8d4CB%2FpJ2Ju%2BpHMao0z%2FEUhEm7lIhPPVjUXXxvAcGwVrqrJIA3LgYRmhO%2BSb9LsKT%2FuRe4PJqxkFhf1LOK75Wkx5gES2TORvRwSCjLq9ieujS%2F7osp5pwUE6e52cpc680CnEjmdQY9AvOqUxnPSaX%2FUVME0CeDcJWheOErE9bRh4e%2Fw3K6Bw6N0hlq%2FOiTzwah2S7odUqfJ%2FECZdDWarXQw5A6tZuTPxy0cv88G%2FVkSNDEhyD6kPEuMBxtm5ulz64ozYEsHMU8UR51gYda6RQSxx1rUpFqF%2FRwFl7cHU13kwkIrovQY6pgFft2yG2b5mLHLRvwB533tB8t%2F4UsPcJm9F70rik%2BA23pP94BZP69gUI1eFRltk18C581D7kQ%2BsXOrNRwRoaNjEa27jvYaHe%2Fg%2F%2FfMuj3LJVDQ4PB3dLakwLPzHxNl5gzXjjsBc5VLEkahhnlWcagqNripN7KEHDibrR%2BfyZYHPNBA3cbXJy7zzntzflzhnmu9vW2%2B4Zv9IVfNszMlg6JRN0YWAkVwT&X-Amz-Signature=a7bc49b8f6f19f8c93268be096db50d90df9956ed1fd49d9158e0d71b0b031a4&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YKZN67MY%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T182941Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEbirBmE5aCqCcCJ%2Bd7JZsqLrOWefLxf%2BofgcYtva3pPAiBaeFHvryx6rxmXDJEM48zFPmKXaJ2WT7WI7OgCKIthiSqIBAjy%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMdv2MB%2BM5m1b3N8xQKtwDFU9VWHXmnrCi9%2Ba0Mdnv%2BJuRtCDQI3nJ2KPlpzO7tqnES0MmRbt0%2FO6AcEpAo%2FcgXZ%2BkqqdQcgLt7kxpoMfDdASBhX2%2BY%2BP26WgSQ8pur8fNulhXeE87dU%2FotylRlaPLzohEp2Dwze5F%2BOXAvtA04J4ORUmENs8pu1u5eNbNaCvjY2H6Bl7copqKtdP19NN5zXdNYWQGohq757vV%2Fz3EMoxZ0F7J4Xb2lXkbTEK9Kf9g3h0CqNCCwOpdlcPo4uAjzCunYf%2BlQCB2u6wkyVFYflgsH%2Bwn7mDLlfJfJNYjZg%2BlM8iwyxHXaMVYISa%2F84bkDmQ%2BGaiV67ofHrmd8d4CB%2FpJ2Ju%2BpHMao0z%2FEUhEm7lIhPPVjUXXxvAcGwVrqrJIA3LgYRmhO%2BSb9LsKT%2FuRe4PJqxkFhf1LOK75Wkx5gES2TORvRwSCjLq9ieujS%2F7osp5pwUE6e52cpc680CnEjmdQY9AvOqUxnPSaX%2FUVME0CeDcJWheOErE9bRh4e%2Fw3K6Bw6N0hlq%2FOiTzwah2S7odUqfJ%2FECZdDWarXQw5A6tZuTPxy0cv88G%2FVkSNDEhyD6kPEuMBxtm5ulz64ozYEsHMU8UR51gYda6RQSxx1rUpFqF%2FRwFl7cHU13kwkIrovQY6pgFft2yG2b5mLHLRvwB533tB8t%2F4UsPcJm9F70rik%2BA23pP94BZP69gUI1eFRltk18C581D7kQ%2BsXOrNRwRoaNjEa27jvYaHe%2Fg%2F%2FfMuj3LJVDQ4PB3dLakwLPzHxNl5gzXjjsBc5VLEkahhnlWcagqNripN7KEHDibrR%2BfyZYHPNBA3cbXJy7zzntzflzhnmu9vW2%2B4Zv9IVfNszMlg6JRN0YWAkVwT&X-Amz-Signature=8e2063ce3e63b5a6c78f282158b3b7b9062a38a076a985d5204e61eaf725937a&X-Amz-SignedHeaders=host&x-id=GetObject)


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

