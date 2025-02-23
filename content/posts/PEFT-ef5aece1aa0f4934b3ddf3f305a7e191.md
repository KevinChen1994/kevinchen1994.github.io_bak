---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4662NWWL3B5%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250223T111923Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjENv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCJJukdB88bshj5ukC\
  X3DzNjl30PfCUT6MV4vEMox9cPAIhALAhF%2Bu6RnwfC%2FUFqCj6pygxRd%2BGjMeQjW72D7IrKa\
  XRKv8DCBQQABoMNjM3NDIzMTgzODA1Igw3CS4ngCWghxKzZiwq3ANtg5patnwEUZqUmQqy%2Fngy5\
  axrL1aacdZZVxxkAficc4G%2F%2F1bLqRZfcPHDxmxEhlix4EROuRLrjHRVtQpyOSI45XsLJAK3Y9\
  6%2Bkabtz2rWTTqxOl5%2FwJ1o3Nk5xekje06DKscK9FfBl49ZCq7hqhzgX%2B2JoBii5PnhfVjpi\
  %2B76G5HauyI4itDiyTUd86AollnM3Ep8k8VFdPtugAkCBMWhB5wx6Z5mJ15S9IbVWdRP2hV9jgVE\
  ZlbivCaqLzfXRprnBaGYBdh8GqttwdQ1ZY5spYzv4jB8CHS8vyWaqSDcdD9olbhvs34%2B1fljMUv\
  pxJRQnqHolDt%2BqdBn9mz%2FCQw8cu2brKDMidd60rbPK33vnibNx9gL8%2FPbpk9WAjWzmBiYBS\
  6ki%2BucHf94%2BMsXTE%2FT1CKSzRImf3BJOJTV5tRlbFL0xj%2BxXj%2Bjyk1VihSqJXHa3I6sv\
  t3d2G0iTKJeBQL7NeswVbeC9E3VtQKz5Fsz37Bws7iTNljxUN4QeGv0Ye%2FeBceMumvqF9RFTrPK\
  P5fBz8dsnTdsWI5GL74t%2FJc%2Bsxwouej5XviDumy0qGPH%2Bdo4TnH6onVVb%2BrrNFEeW2NUD\
  a254UDVQSuh7mHk%2FzxJIduz6K5oK56ykBbfGzCk%2Feu9BjqkAczebc7Z72y0PJcX2x19i7JHHy\
  QaEZbX%2Bjffp%2F3r7MEg4Ak7hoyK6%2B6ZcqFD8DokW%2Bwok5EUSCaUBnlYvdVi%2Ba1rv5DSc\
  oBzHk6Vnxof3VTzgOsnVQg%2Ft%2FEoCCdSiitHkoi%2BzXLCCd7FgfNBt0maBVkDbvPFwTl27H5A\
  %2FV6GHqA8jkMmllWuGqRmiKJ535znV6Bsg0n2qZWTVOcVWAZeV3LPWwGE&X-Amz-Signature=40\
  8ad7262c4765ab178a0c306302e65ef26ca4be9fe7a617eb38b6fdb91cfbf5&X-Amz-SignedHe\
  aders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466ZTKAP7VI%2F20250223%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250223T111753Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjENr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEY\
        CIQCopNFp89wfkIahbA6uK%2B%2FSX9dJN9Wv0XTGm3LlwzMMQAIhALRhDvVfqd6j2JEtSu\
        GGJ4PeQDJyJvnP4rwyXmSTC2EmKv8DCBMQABoMNjM3NDIzMTgzODA1IgzTpvJ7h%2FqrtX7\
        7BAIq3ANWiBEfE8geaxAftXV4Ce%2F7RzFZpI3UrAPzYqNlphcL1EJi65zsmlb7AV5JScmW\
        7o1WvBoxVpP3UzBqgKgnzRXU1QhW2j9K089QxbdMWG9cgEd%2BM5%2FA9YjNbF2Q4bK8dqO\
        HCjt%2F26dGgINf%2FK4q%2BydZcZ6ozyqVC9JbMo%2BCUtceGcAjVGliqXgfyO509gDQED\
        TSxJtOfsSP%2Fvds9JWbkVGxU%2BbbchuCQ5UDA4ogmuHGUWZq3vYWhoapD6BOZGGkZvEOi\
        %2BeY0qZjdJl9iLa7x4bpXI%2BxJzQNAUiXixbOCAjYY2oAlc4D9b%2Fid0nxPMY7Aa79vD\
        rLam%2BcclP7UbhzEBQrdhoApr%2BPzHe6u3yaKaN73xi7IkwS%2FfLTI%2FXNrR5XMzOKh\
        f6pb1ZeF75zLT%2B4XZ8GG01eCVYiiMtieHqg5CeEdxkAqPy1jJJFerJkIJ4UKcT4gtmGyw\
        IiMdbx9cjWm1Jvez9WpMQ02SIwUIYJoLCmpoRCi%2FFtoNmy7U4Uz65NZBJXINZXsBaauoa\
        7XPYixTZWU2KzXxxFHdE1C9xh9oGGhU%2FARpnQm%2BWZ4jBDLJsVvC%2BuOfW%2FoA%2FM\
        Jp%2F1zTt5sZ%2FNCKhjAmnDR%2FtizZSUWFC8waX65wBdZ1p7SQv2pDCA5%2Bu9BjqkAde\
        oJwv70ND1bCUd57vSxMMUj8lj2zQKj8zumpEiAYFn%2FFg8aQDroliswGgsp%2BVT6mwDup\
        u2%2FvnZl4jHc5ryULjUivmMgr%2BOkb1mek2RosHpbAo6nFNYLmP7OQ8d5X69SxZVqR2FB\
        bj%2Bjf0PwBUVP2C2goVas9YAwp9WeBR%2BbxfMnQ1CQ6zoav6EvaO%2F7jKcb5ddCdK0ao\
        K7%2B7kUll8l2EQX6DDz&X-Amz-Signature=017f35d29b25d37896c29a50bba460ed19\
        99972ac8661114a11b017167094d61&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-23T12:17:53.148Z"
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
UPDATE_TIME: "2025-02-23T11:19:31.521Z"
EXPIRY_TIME: "2025-02-23T12:19:20.935Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UUGGOAZZ%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T111921Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIA%2Fn3vDXS96LZIgOYV4C7v%2BN%2BhPBsdUiZ5EZq%2Bj%2FiXFkAiEA9jvzSjKyYzsATywdwiHlDbIaMCHxdsV9Ddniylfh6PEq%2FwMIERAAGgw2Mzc0MjMxODM4MDUiDLtkNwFQ%2FPX1IxQV4CrcA1M1NFBi9yt1yoDDNPbN2IATI%2B%2BHy%2Bl0GxLuNnK9moVp19kmD7%2BJi9yyovnrX3advicreATu3IBBvcyUM0FdOkr7Si6mN6yRatT3XOCJvMTKZ6%2F6BgMEgyR%2BNAi3kRkXkX8NtQXGKVo5o2yi111R9aznyxUrmja46387bHyyfB8bBq5hHVG61sac%2Bh63Wsi9P9cXt1zpM25PIkW%2F2VM%2FPb52NT%2F%2FSg1Axu35O69b7mxL3cvdEhO%2F7PgaXoD1PGwHi%2FfEVWDFQn4VjXXMOItr2A2xd41hO8zoq7dGDYhoavJsEPKaJ0yb1rHIV0xbmbV7GW4xpgQUWrmJrpsGjJ82XrTxzzLqSXwXFJDd8flUhYzuSuyFH%2BNqlYDT7JDxRy5ZQkWSKi2z%2BVTiwh9j0thuM%2B8AE9LVMMwTQU%2FD0sjPptB6p0Yol7o1EM6BozvaCb7nIi46lyY%2FOiWH9PPBpEk%2BrkmqA7TmyYiJ2q2jaxe7EXsPYphVkHRLGVobnVXWLv2JFc%2BBRc%2Bec3YZFMNwtU3ggHGTUtGWQKrSkSNaoQUxv%2B30XW%2FuY5f1NN1sS7VQ70bAKP84sOKofcYJJ0prxmFLLfi7v4ZMLYOn1S6bzFI9%2BAXmET13TMXsWx7%2BIM3YMPmc670GOqUBwAHkZZcCQBbNw7HMowRadi%2BhsJeTf%2BPqFLCwXub2vQ04GiCgyvexIyXQUbJfFtqbNOHwAmuXWP8PdiH8lPN5fWS6ttpzkk%2FqhDLuoRsn%2Bo7b5KyLpG6xV2hYyyUmGgyn4IEJzy3nmJM3R%2FLNQU%2F1BfFGWnytUKEK496xDgLiUwwClWQmEj0rQRjEp9clhL7n9tGb0vazdywFZ7GlNdsYU%2BC8U6kY&X-Amz-Signature=1cf7f7dd1ca9ca00ec5f00684f24f53aa55eba88b50d070d2f312360921fc839&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UUGGOAZZ%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T111921Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIA%2Fn3vDXS96LZIgOYV4C7v%2BN%2BhPBsdUiZ5EZq%2Bj%2FiXFkAiEA9jvzSjKyYzsATywdwiHlDbIaMCHxdsV9Ddniylfh6PEq%2FwMIERAAGgw2Mzc0MjMxODM4MDUiDLtkNwFQ%2FPX1IxQV4CrcA1M1NFBi9yt1yoDDNPbN2IATI%2B%2BHy%2Bl0GxLuNnK9moVp19kmD7%2BJi9yyovnrX3advicreATu3IBBvcyUM0FdOkr7Si6mN6yRatT3XOCJvMTKZ6%2F6BgMEgyR%2BNAi3kRkXkX8NtQXGKVo5o2yi111R9aznyxUrmja46387bHyyfB8bBq5hHVG61sac%2Bh63Wsi9P9cXt1zpM25PIkW%2F2VM%2FPb52NT%2F%2FSg1Axu35O69b7mxL3cvdEhO%2F7PgaXoD1PGwHi%2FfEVWDFQn4VjXXMOItr2A2xd41hO8zoq7dGDYhoavJsEPKaJ0yb1rHIV0xbmbV7GW4xpgQUWrmJrpsGjJ82XrTxzzLqSXwXFJDd8flUhYzuSuyFH%2BNqlYDT7JDxRy5ZQkWSKi2z%2BVTiwh9j0thuM%2B8AE9LVMMwTQU%2FD0sjPptB6p0Yol7o1EM6BozvaCb7nIi46lyY%2FOiWH9PPBpEk%2BrkmqA7TmyYiJ2q2jaxe7EXsPYphVkHRLGVobnVXWLv2JFc%2BBRc%2Bec3YZFMNwtU3ggHGTUtGWQKrSkSNaoQUxv%2B30XW%2FuY5f1NN1sS7VQ70bAKP84sOKofcYJJ0prxmFLLfi7v4ZMLYOn1S6bzFI9%2BAXmET13TMXsWx7%2BIM3YMPmc670GOqUBwAHkZZcCQBbNw7HMowRadi%2BhsJeTf%2BPqFLCwXub2vQ04GiCgyvexIyXQUbJfFtqbNOHwAmuXWP8PdiH8lPN5fWS6ttpzkk%2FqhDLuoRsn%2Bo7b5KyLpG6xV2hYyyUmGgyn4IEJzy3nmJM3R%2FLNQU%2F1BfFGWnytUKEK496xDgLiUwwClWQmEj0rQRjEp9clhL7n9tGb0vazdywFZ7GlNdsYU%2BC8U6kY&X-Amz-Signature=d53d2f7ae0a46f12c09eb5152ee609687cfeac7de4c4bd7bee20d9ada44f4624&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UUGGOAZZ%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T111921Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIA%2Fn3vDXS96LZIgOYV4C7v%2BN%2BhPBsdUiZ5EZq%2Bj%2FiXFkAiEA9jvzSjKyYzsATywdwiHlDbIaMCHxdsV9Ddniylfh6PEq%2FwMIERAAGgw2Mzc0MjMxODM4MDUiDLtkNwFQ%2FPX1IxQV4CrcA1M1NFBi9yt1yoDDNPbN2IATI%2B%2BHy%2Bl0GxLuNnK9moVp19kmD7%2BJi9yyovnrX3advicreATu3IBBvcyUM0FdOkr7Si6mN6yRatT3XOCJvMTKZ6%2F6BgMEgyR%2BNAi3kRkXkX8NtQXGKVo5o2yi111R9aznyxUrmja46387bHyyfB8bBq5hHVG61sac%2Bh63Wsi9P9cXt1zpM25PIkW%2F2VM%2FPb52NT%2F%2FSg1Axu35O69b7mxL3cvdEhO%2F7PgaXoD1PGwHi%2FfEVWDFQn4VjXXMOItr2A2xd41hO8zoq7dGDYhoavJsEPKaJ0yb1rHIV0xbmbV7GW4xpgQUWrmJrpsGjJ82XrTxzzLqSXwXFJDd8flUhYzuSuyFH%2BNqlYDT7JDxRy5ZQkWSKi2z%2BVTiwh9j0thuM%2B8AE9LVMMwTQU%2FD0sjPptB6p0Yol7o1EM6BozvaCb7nIi46lyY%2FOiWH9PPBpEk%2BrkmqA7TmyYiJ2q2jaxe7EXsPYphVkHRLGVobnVXWLv2JFc%2BBRc%2Bec3YZFMNwtU3ggHGTUtGWQKrSkSNaoQUxv%2B30XW%2FuY5f1NN1sS7VQ70bAKP84sOKofcYJJ0prxmFLLfi7v4ZMLYOn1S6bzFI9%2BAXmET13TMXsWx7%2BIM3YMPmc670GOqUBwAHkZZcCQBbNw7HMowRadi%2BhsJeTf%2BPqFLCwXub2vQ04GiCgyvexIyXQUbJfFtqbNOHwAmuXWP8PdiH8lPN5fWS6ttpzkk%2FqhDLuoRsn%2Bo7b5KyLpG6xV2hYyyUmGgyn4IEJzy3nmJM3R%2FLNQU%2F1BfFGWnytUKEK496xDgLiUwwClWQmEj0rQRjEp9clhL7n9tGb0vazdywFZ7GlNdsYU%2BC8U6kY&X-Amz-Signature=f7bf784f9a41be2acd1cf3b77fe0d0f3d2ce384dd3920b2d658f00af530f941b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UUGGOAZZ%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T111921Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIA%2Fn3vDXS96LZIgOYV4C7v%2BN%2BhPBsdUiZ5EZq%2Bj%2FiXFkAiEA9jvzSjKyYzsATywdwiHlDbIaMCHxdsV9Ddniylfh6PEq%2FwMIERAAGgw2Mzc0MjMxODM4MDUiDLtkNwFQ%2FPX1IxQV4CrcA1M1NFBi9yt1yoDDNPbN2IATI%2B%2BHy%2Bl0GxLuNnK9moVp19kmD7%2BJi9yyovnrX3advicreATu3IBBvcyUM0FdOkr7Si6mN6yRatT3XOCJvMTKZ6%2F6BgMEgyR%2BNAi3kRkXkX8NtQXGKVo5o2yi111R9aznyxUrmja46387bHyyfB8bBq5hHVG61sac%2Bh63Wsi9P9cXt1zpM25PIkW%2F2VM%2FPb52NT%2F%2FSg1Axu35O69b7mxL3cvdEhO%2F7PgaXoD1PGwHi%2FfEVWDFQn4VjXXMOItr2A2xd41hO8zoq7dGDYhoavJsEPKaJ0yb1rHIV0xbmbV7GW4xpgQUWrmJrpsGjJ82XrTxzzLqSXwXFJDd8flUhYzuSuyFH%2BNqlYDT7JDxRy5ZQkWSKi2z%2BVTiwh9j0thuM%2B8AE9LVMMwTQU%2FD0sjPptB6p0Yol7o1EM6BozvaCb7nIi46lyY%2FOiWH9PPBpEk%2BrkmqA7TmyYiJ2q2jaxe7EXsPYphVkHRLGVobnVXWLv2JFc%2BBRc%2Bec3YZFMNwtU3ggHGTUtGWQKrSkSNaoQUxv%2B30XW%2FuY5f1NN1sS7VQ70bAKP84sOKofcYJJ0prxmFLLfi7v4ZMLYOn1S6bzFI9%2BAXmET13TMXsWx7%2BIM3YMPmc670GOqUBwAHkZZcCQBbNw7HMowRadi%2BhsJeTf%2BPqFLCwXub2vQ04GiCgyvexIyXQUbJfFtqbNOHwAmuXWP8PdiH8lPN5fWS6ttpzkk%2FqhDLuoRsn%2Bo7b5KyLpG6xV2hYyyUmGgyn4IEJzy3nmJM3R%2FLNQU%2F1BfFGWnytUKEK496xDgLiUwwClWQmEj0rQRjEp9clhL7n9tGb0vazdywFZ7GlNdsYU%2BC8U6kY&X-Amz-Signature=43da7923c63f5fc5a765f2364e7c3ecb5fbfa869744dee1d66820138be61f16c&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UUGGOAZZ%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T111921Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIA%2Fn3vDXS96LZIgOYV4C7v%2BN%2BhPBsdUiZ5EZq%2Bj%2FiXFkAiEA9jvzSjKyYzsATywdwiHlDbIaMCHxdsV9Ddniylfh6PEq%2FwMIERAAGgw2Mzc0MjMxODM4MDUiDLtkNwFQ%2FPX1IxQV4CrcA1M1NFBi9yt1yoDDNPbN2IATI%2B%2BHy%2Bl0GxLuNnK9moVp19kmD7%2BJi9yyovnrX3advicreATu3IBBvcyUM0FdOkr7Si6mN6yRatT3XOCJvMTKZ6%2F6BgMEgyR%2BNAi3kRkXkX8NtQXGKVo5o2yi111R9aznyxUrmja46387bHyyfB8bBq5hHVG61sac%2Bh63Wsi9P9cXt1zpM25PIkW%2F2VM%2FPb52NT%2F%2FSg1Axu35O69b7mxL3cvdEhO%2F7PgaXoD1PGwHi%2FfEVWDFQn4VjXXMOItr2A2xd41hO8zoq7dGDYhoavJsEPKaJ0yb1rHIV0xbmbV7GW4xpgQUWrmJrpsGjJ82XrTxzzLqSXwXFJDd8flUhYzuSuyFH%2BNqlYDT7JDxRy5ZQkWSKi2z%2BVTiwh9j0thuM%2B8AE9LVMMwTQU%2FD0sjPptB6p0Yol7o1EM6BozvaCb7nIi46lyY%2FOiWH9PPBpEk%2BrkmqA7TmyYiJ2q2jaxe7EXsPYphVkHRLGVobnVXWLv2JFc%2BBRc%2Bec3YZFMNwtU3ggHGTUtGWQKrSkSNaoQUxv%2B30XW%2FuY5f1NN1sS7VQ70bAKP84sOKofcYJJ0prxmFLLfi7v4ZMLYOn1S6bzFI9%2BAXmET13TMXsWx7%2BIM3YMPmc670GOqUBwAHkZZcCQBbNw7HMowRadi%2BhsJeTf%2BPqFLCwXub2vQ04GiCgyvexIyXQUbJfFtqbNOHwAmuXWP8PdiH8lPN5fWS6ttpzkk%2FqhDLuoRsn%2Bo7b5KyLpG6xV2hYyyUmGgyn4IEJzy3nmJM3R%2FLNQU%2F1BfFGWnytUKEK496xDgLiUwwClWQmEj0rQRjEp9clhL7n9tGb0vazdywFZ7GlNdsYU%2BC8U6kY&X-Amz-Signature=038c1867228f71d51527be4cdbfedaadef4b670588cfccfbfcfec2590b693ed1&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZH3JBVLM%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T111922Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD9yeYy8h%2BvL51RLCuL8H2L2znW89x%2FhZASi9tbRUgLFwIhAI5GYgstOiwAT7tAJXKz6APoFhe3bmo49Xt9mJqDPGGxKv8DCBMQABoMNjM3NDIzMTgzODA1Igz7OiDrLaObQTXoejYq3APpHhCjvWlpRP1Mc6SV0rK6xY1GPpCjPHFT5TqgmJsf4vlWr4SSXlX6QwY2YUSmruIjk0a%2BmG20tAkDNHn4kPV%2F%2B2GY1zNe2R74VnFfc0345Nmpn3kGzKGDS4oVRtZ7tgctID3yAiNfOBFp7o73sh9OibHvjLLUIcleXsUpYrzLFnqzA2QSltfwsATGIpwYiRgubfEEr%2BgM%2F%2F6PDWhBKzKrrCX775iYGv42vzsAllGjWVZxgkWFBlezp%2BhSZPOc09C81gCj3%2Fo0vfUfVzfAPZgL0xokBDhGr6ExQbFUd0a1QeaTeDZW5x4N3z13skzULATidfaGeOPtULpgdo2Gyf8m%2FVIUS5WQjGtseXA7M%2Fh%2BuBQOWi8Vt5rl0a1KWE9ceEneNeWqD%2FHBP6CVpbA2rUnOOjUrfwgUIs10rMzuYf6KnMHuePOzW5ebsuWenTUdFXi%2BnrhU66keXLJE6ziRez4pqxVqrj7B5whBeOxrv8QVc512GJMC9GKru7mxmfaMShQ9ATzJCKguSVARjslidu8RWAaSVkxhzgJ3vgkIEF53wAQWr62ClApG9ujpfu4UDfa7QU5%2Bbg0LvyyTbgc7mDtwCEx5rd4ZGItmTzy5BHKb3GNiGCVJ4CO3Zo2hyjDx2Ou9BjqkAZZg45Qgy3anqIgykC%2FDqbSo%2B1hC3an1LmBl%2B333enrr9brI4Qd6TwMR8wIlh0kIlUuPGt7NEeCNB03d0GDLznFnmrcQQwLcEFRC2QHwx7Vqm8qxGbeX8Mltk7xpCJ8e5DhQVdS%2FgYaobrHfI2RDbXbqpuGhSoS%2Fqotpu%2BwhD8SYfFertYnQc8mTOoBsL0q72hRd0s%2FblQ00Zz6XnxI6tNeBQYij&X-Amz-Signature=ec3a10e7392ab3913d7c6dca554bb74bb987fc44d1051fd2a0ab5442de5fe31b&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662QB6YCVV%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T111922Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCyqupLcpJxHCI2ilO3az%2BhBeK%2F8HfsVM8GjwjhKnLf%2BAIgQCA7XgqyBQGHiRHBf4RxRjzKREZiG5XJIpphCiJrD8IqiAQI%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDIxqbmNlOYS6B17wSyrcA%2Fnf1VPNGygF7u3KWajEaZ1DZ4S88vQFNQpo5sM%2BHbF4oQ5s2iUDAQhtjDNWlLr6B3tsqXB4njzJ1JZV1Sx78qzn7hxCAINyeffC3UIyzRVG3HJKeUKPgKso43Quy3FTteJFyAejjgo7mZoaH5G4zhw9MtMyFDojRaR2sZNqr8gomtGCryILyPhCl9SLIROkQIb9sfJlLEOHKLuyL9azi2S9RMQDSXQppT21ZEMGoutoCaCFnROLron1HcAlwi7nDR%2Fzkt1IeU5pBLpWM9ZZdw9NcEBSKp6XNC5yOGFB%2F6zzI%2BnjU15XTixmwjLsS4jrl9kAJqfUJPNTVaUxJ3n5mQCncfKXEGXuSwPR435hMzjLz9Buk6h50gLbeIv3xEs04QO%2FXQzuk%2FbwQw5mrKu9JK1ta0xQTNIYOBk6VCU6S7NZIZBRERRs1UhwoaSQiIKO9KiK6P2j1KOHlKhwlcJ6LDFK8mOUEPenwnpM5WOrLbjoG7syABQfezFrPAuOOJn0JJyfWDJ3KNZHUvCdGnBHD02XT1Non%2B9TcAlEWo2Wm8rp71ZnJenxlqnTg%2FGPcvW1EI4rA7n1Le%2F6jexL6DsVEoZEnsc%2Fb75MiHznTM7%2BCMhzRcZSCPOeLgzHuRm9MK%2Fk6r0GOqUBS4QUHWD5ztFYoVs%2BYQcygpPfnBzlHwZKiOVNNyrh4NVkVGd5SizKjC858Zrqxdb7vUYoUIyLeHSjleAefWo%2Bhd2R%2BRgR%2Fa7Hox7v7OjEv0Wka2283z3FG06kcC9Vgesb7VxsoObeS%2BqGEE3BnAriVAi9UgQafDPgCRuyovibBaS%2BsWn4w6qP7ZtI%2BIMAwFi%2BbBlsYB%2FySTGCA95NBDAVVuX7b2ku&X-Amz-Signature=02a9aa9eeace19b0983b4c29461bee82a8df71d75e8aa3ea44b4a38d884649ad&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UUGGOAZZ%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T111921Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIA%2Fn3vDXS96LZIgOYV4C7v%2BN%2BhPBsdUiZ5EZq%2Bj%2FiXFkAiEA9jvzSjKyYzsATywdwiHlDbIaMCHxdsV9Ddniylfh6PEq%2FwMIERAAGgw2Mzc0MjMxODM4MDUiDLtkNwFQ%2FPX1IxQV4CrcA1M1NFBi9yt1yoDDNPbN2IATI%2B%2BHy%2Bl0GxLuNnK9moVp19kmD7%2BJi9yyovnrX3advicreATu3IBBvcyUM0FdOkr7Si6mN6yRatT3XOCJvMTKZ6%2F6BgMEgyR%2BNAi3kRkXkX8NtQXGKVo5o2yi111R9aznyxUrmja46387bHyyfB8bBq5hHVG61sac%2Bh63Wsi9P9cXt1zpM25PIkW%2F2VM%2FPb52NT%2F%2FSg1Axu35O69b7mxL3cvdEhO%2F7PgaXoD1PGwHi%2FfEVWDFQn4VjXXMOItr2A2xd41hO8zoq7dGDYhoavJsEPKaJ0yb1rHIV0xbmbV7GW4xpgQUWrmJrpsGjJ82XrTxzzLqSXwXFJDd8flUhYzuSuyFH%2BNqlYDT7JDxRy5ZQkWSKi2z%2BVTiwh9j0thuM%2B8AE9LVMMwTQU%2FD0sjPptB6p0Yol7o1EM6BozvaCb7nIi46lyY%2FOiWH9PPBpEk%2BrkmqA7TmyYiJ2q2jaxe7EXsPYphVkHRLGVobnVXWLv2JFc%2BBRc%2Bec3YZFMNwtU3ggHGTUtGWQKrSkSNaoQUxv%2B30XW%2FuY5f1NN1sS7VQ70bAKP84sOKofcYJJ0prxmFLLfi7v4ZMLYOn1S6bzFI9%2BAXmET13TMXsWx7%2BIM3YMPmc670GOqUBwAHkZZcCQBbNw7HMowRadi%2BhsJeTf%2BPqFLCwXub2vQ04GiCgyvexIyXQUbJfFtqbNOHwAmuXWP8PdiH8lPN5fWS6ttpzkk%2FqhDLuoRsn%2Bo7b5KyLpG6xV2hYyyUmGgyn4IEJzy3nmJM3R%2FLNQU%2F1BfFGWnytUKEK496xDgLiUwwClWQmEj0rQRjEp9clhL7n9tGb0vazdywFZ7GlNdsYU%2BC8U6kY&X-Amz-Signature=e6c026c1e22cb9740ebee16c21892d07f3c3e772ec61b4786fe703268953db7d&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UUGGOAZZ%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T111921Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIA%2Fn3vDXS96LZIgOYV4C7v%2BN%2BhPBsdUiZ5EZq%2Bj%2FiXFkAiEA9jvzSjKyYzsATywdwiHlDbIaMCHxdsV9Ddniylfh6PEq%2FwMIERAAGgw2Mzc0MjMxODM4MDUiDLtkNwFQ%2FPX1IxQV4CrcA1M1NFBi9yt1yoDDNPbN2IATI%2B%2BHy%2Bl0GxLuNnK9moVp19kmD7%2BJi9yyovnrX3advicreATu3IBBvcyUM0FdOkr7Si6mN6yRatT3XOCJvMTKZ6%2F6BgMEgyR%2BNAi3kRkXkX8NtQXGKVo5o2yi111R9aznyxUrmja46387bHyyfB8bBq5hHVG61sac%2Bh63Wsi9P9cXt1zpM25PIkW%2F2VM%2FPb52NT%2F%2FSg1Axu35O69b7mxL3cvdEhO%2F7PgaXoD1PGwHi%2FfEVWDFQn4VjXXMOItr2A2xd41hO8zoq7dGDYhoavJsEPKaJ0yb1rHIV0xbmbV7GW4xpgQUWrmJrpsGjJ82XrTxzzLqSXwXFJDd8flUhYzuSuyFH%2BNqlYDT7JDxRy5ZQkWSKi2z%2BVTiwh9j0thuM%2B8AE9LVMMwTQU%2FD0sjPptB6p0Yol7o1EM6BozvaCb7nIi46lyY%2FOiWH9PPBpEk%2BrkmqA7TmyYiJ2q2jaxe7EXsPYphVkHRLGVobnVXWLv2JFc%2BBRc%2Bec3YZFMNwtU3ggHGTUtGWQKrSkSNaoQUxv%2B30XW%2FuY5f1NN1sS7VQ70bAKP84sOKofcYJJ0prxmFLLfi7v4ZMLYOn1S6bzFI9%2BAXmET13TMXsWx7%2BIM3YMPmc670GOqUBwAHkZZcCQBbNw7HMowRadi%2BhsJeTf%2BPqFLCwXub2vQ04GiCgyvexIyXQUbJfFtqbNOHwAmuXWP8PdiH8lPN5fWS6ttpzkk%2FqhDLuoRsn%2Bo7b5KyLpG6xV2hYyyUmGgyn4IEJzy3nmJM3R%2FLNQU%2F1BfFGWnytUKEK496xDgLiUwwClWQmEj0rQRjEp9clhL7n9tGb0vazdywFZ7GlNdsYU%2BC8U6kY&X-Amz-Signature=60ff4ca7527a5bb77885e36c859b382b3efb29efd21d6f187b6d880523a3c9da&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UUGGOAZZ%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T111921Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIA%2Fn3vDXS96LZIgOYV4C7v%2BN%2BhPBsdUiZ5EZq%2Bj%2FiXFkAiEA9jvzSjKyYzsATywdwiHlDbIaMCHxdsV9Ddniylfh6PEq%2FwMIERAAGgw2Mzc0MjMxODM4MDUiDLtkNwFQ%2FPX1IxQV4CrcA1M1NFBi9yt1yoDDNPbN2IATI%2B%2BHy%2Bl0GxLuNnK9moVp19kmD7%2BJi9yyovnrX3advicreATu3IBBvcyUM0FdOkr7Si6mN6yRatT3XOCJvMTKZ6%2F6BgMEgyR%2BNAi3kRkXkX8NtQXGKVo5o2yi111R9aznyxUrmja46387bHyyfB8bBq5hHVG61sac%2Bh63Wsi9P9cXt1zpM25PIkW%2F2VM%2FPb52NT%2F%2FSg1Axu35O69b7mxL3cvdEhO%2F7PgaXoD1PGwHi%2FfEVWDFQn4VjXXMOItr2A2xd41hO8zoq7dGDYhoavJsEPKaJ0yb1rHIV0xbmbV7GW4xpgQUWrmJrpsGjJ82XrTxzzLqSXwXFJDd8flUhYzuSuyFH%2BNqlYDT7JDxRy5ZQkWSKi2z%2BVTiwh9j0thuM%2B8AE9LVMMwTQU%2FD0sjPptB6p0Yol7o1EM6BozvaCb7nIi46lyY%2FOiWH9PPBpEk%2BrkmqA7TmyYiJ2q2jaxe7EXsPYphVkHRLGVobnVXWLv2JFc%2BBRc%2Bec3YZFMNwtU3ggHGTUtGWQKrSkSNaoQUxv%2B30XW%2FuY5f1NN1sS7VQ70bAKP84sOKofcYJJ0prxmFLLfi7v4ZMLYOn1S6bzFI9%2BAXmET13TMXsWx7%2BIM3YMPmc670GOqUBwAHkZZcCQBbNw7HMowRadi%2BhsJeTf%2BPqFLCwXub2vQ04GiCgyvexIyXQUbJfFtqbNOHwAmuXWP8PdiH8lPN5fWS6ttpzkk%2FqhDLuoRsn%2Bo7b5KyLpG6xV2hYyyUmGgyn4IEJzy3nmJM3R%2FLNQU%2F1BfFGWnytUKEK496xDgLiUwwClWQmEj0rQRjEp9clhL7n9tGb0vazdywFZ7GlNdsYU%2BC8U6kY&X-Amz-Signature=1fd430b38c9087c5b507ff4ea47a4b0a324f59c9711887cd736f7fc8cb5682ef&X-Amz-SignedHeaders=host&x-id=GetObject)


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

