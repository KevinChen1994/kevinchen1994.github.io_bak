---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4662NV6KNRR%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250223T132422Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjENv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIDlCSLybyhYXdz5ItWr\
  BQlQ6IBYgsBCaqGsUpJnUQsc7AiBGFB7FlNqB7LM5Rw7suxRUrTAuuM6TI60bmRQR5lnkTCr%2FAw\
  gUEAAaDDYzNzQyMzE4MzgwNSIMIc%2BXy56Q45AvfjQzKtwD%2BahcVSWjJv10E%2F6ljuySCLLKl\
  ZPnBG%2F8LBc6Mi8%2B%2BYF9KHoCOXcdaTBeskV4s%2F55lhmAItmbsGKiPP9S6h9tRf1soCB3h3\
  BcJRG6irKHyWDEyhBXVkVEuyyi8dMHCal%2FK%2F9HsLQRgc1rwL4R5f9iV6xxn1CEeNV65wTbn3e\
  2TztQhesowljQD%2Fu7681VqDIzu7ebfpPRVfQcPdWEfq254mzqQMOpNR%2FTKRE9BBx5MunyCJWD\
  Pb8To61REPpaXJupH35hNYkG40e0rbmQjmYuzageKqOJP3lbFPrdvWhHjCX%2FOmkALabDMhKf2R2\
  Lq8dRZ3J5Hr%2FseXku0a%2BZYHJ9OGCw3u7gzG0rjzL4UJkVN6Fi1Ra7rakGKfrQktJ3dqyTEspf\
  bCKaSGOPNfoIHRufXReZR3gjD%2BYHWczVxl%2FF1qiHXb%2BC7WbaUkAOR9yfvuZXhX6e0WgzHp5\
  2ORvvHWvvzreqJp0g0jgd6Y23rORrXdyvOlWzaZwQpiC0Ht32Eoj1deb74YZZXW7A9mDC969xBHS9\
  CbmlYxEYn%2FapwjRLVIZAzk6G%2BflPB3kPVp14hs9mHByKuoYKiT18EUJD5phLl8bK2i6r%2FsO\
  GyseFNugj8M6jwEKoa3Ks%2FYb6ScIwzfXrvQY6pgGdq1DJHVHGHGvE2CAYR3dZUfxrBrfBXuiFaR\
  NX1mI6ed0aoJv%2B0t9h5656eqrDFrrUdLJgCWgUpTLsrj1RQsXGT2biUwgZMWFo501ZOTUT5L%2F\
  B6U%2F5SY2tpcSkrdnzoUMItEI5bdnEv5XsyGBjlYeP6MyIIWY%2BVJALYAoymjYSoJ7%2BtdbSHh\
  z%2B99lbukMXhuLgOqs7Ko%2FQ9dDEOnTHeZd0xdh5wdvL&X-Amz-Signature=43a0c1641401b6\
  b618bdd3fa52bb78b7ac30ead58a5427621863e1bfeb39b80a&X-Amz-SignedHeaders=host&x\
  -id=GetObject"
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
        redential=ASIAZI2LB466RCGASAMY%2F20250223%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250223T132252Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjENn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQ\
        CIGv%2FodbApBGPsJ33M9jqMwJQyQAy5lWyN9y%2BuTbOzQRwAiAnm%2BtWP0Huj8jm4ABf\
        P%2B0GuGxc01rnac1ZHDIjj%2FZAlir%2FAwgSEAAaDDYzNzQyMzE4MzgwNSIMNvjkjAplI\
        xFAQ4mcKtwDJn5conhE7eX7TR6WUDbnYuaQQuJzQZ9TYJy7e3%2F%2BH%2FWhSja7F5Bg59\
        ifW41ROaf6YzUsI%2BTo%2F1RI1ZQtGlW4K1n3T8uXylktmBBMN77VpDtdgljrGzizXhUAM\
        aSyXVOx5B2Vuby66gojtY7%2BX0zYnueL8hXeyK3%2FTBzXvhqf0jB29TRhvugd9uCv4qT7\
        nc3GHYb1TfhBmoFuu8bwMh0vBJw%2BDASt8kqljafPwvdP1FvDKDMD%2BrOjjcjrKEzo2Xi\
        gelyAuzLmYCrNG8FtjchjLJMgWnHvvmak7W0ACzBlxgHjyxGGcctDVkJYBCQBF%2FK1RLoj\
        CskayDZsFlmAwbzsBtbjJfL4CZBjvAfGN9FGpB0WRZqiWyd%2Fhe3MKPyTB3AyC%2FlgmT8\
        cP4v3vLzDjUYDcqhCjDSm0UfNCHeQmi4I6x4Celv9zON7KEx2cD8Ibgat75joUQf4DTkDkK\
        1JIiuX5Bb4JngYXbBLIppbCN%2BZK4HlbwQncaxkhh5bshKVnfwXO295%2FOCJRC2DYAlJ8\
        WL2FnsVVHzD1BP%2Bh30b%2FqrHWgmN%2FHvX%2BYGM6DeKxlQuzsmAsrfdyJhHJTF9u8Cg\
        u68C%2BF3WLk%2FmNgY0Nr3hxr14M4vncJ2Nfhr9KEueoBYwxrrrvQY6pgEMzsm%2BijBnO\
        x9JkAb8PM0bx5thNGHlslZRTq479QOJOS6Qj%2Bu33ytn6AtKwarJIqJh3RSkdJncOx%2Fq\
        GqYeoncI5baB9tJ%2FKiOtxa52e8QmhhV1ZnT1o0vUau5NvGjg1q%2FHLrLOPXtQQOaBPcd\
        29gpMXsrbHB5TIseAaIbMwBAI%2FUapVdHeWFIvTJdGITSu614j%2FLvF74JyvTUX7i5BCw\
        b9hm3B4vC8&X-Amz-Signature=dfe27739cd48cb0af4be45a458c741d787d1cca075eb\
        b5313682af945c8f1aff&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-23T14:22:52.827Z"
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
UPDATE_TIME: "2025-02-23T13:24:27.784Z"
EXPIRY_TIME: "2025-02-23T14:24:18.255Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VEASOB3B%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T132419Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDidRwr9f45FICyY5A6N2Wq3XWuOHr%2BTA10YdScZ0Sz0gIhALezGl9cC2jjr1xYUNWUl2k3xht8V7SmvA7nYHubROKiKv8DCBUQABoMNjM3NDIzMTgzODA1IgyliSpxD53xTqI0hWcq3ANDeEo5gq5bWxoSChFJy6Rs73aBuhXxVpGx0eFdiPqYW2%2BKmwQ%2BigKs74Loih%2F4vUWtJf2vKbarg0M77ZFP112Pij7O0kSIMhrTkrDvxhwV%2FJ8%2B3GZV6nq20uQ7xfTJwfLdg46Y7s2vQWvsr7%2BKFuoUf14fIdLIJ4R4TyhxcnRBmC%2FcBd0wUQyVlGcmOhgoSelTCo7K8gObDieISj2842ul5xHEd1DHKpkNK%2FDLXhkIQ2LA%2Bvzy4u2nbGOxkU07czAM8KvH%2FojXgOKv03UVkJUOIyiXRqA3GY%2F2sGm%2Bc54klwUc%2Ff81j1ogOU54R1M%2FLeVmvnazy2dxabBG0SO8BPX9c%2BGVVUIviPLHNqQh65ioyKji8uFfHuNaKFUzA6hDMQ2otWNTBbVax9ZwNsiMm7N8n3gBVq7BoOb7ToloEWwBhBV3%2FkQzfUUYKgiIzXNBrhvYjZsRlZWELtQemXDafNIz4%2FdxZHnzNGMDk2JWzy9xidx6uIVE6NWMg8szFhx7GpaMsaiWbXapaFHLsbRAzqeFE1W6Udz%2B2KfFBqwobzqrc4%2BvZYesGiwyV5zihbGxuIQ2yovwRHYu1Fob4SWlPy%2BfImAX%2FoEzA7tfr7TXgH0cSRT%2FAXPIJKsDQfvuazDynuy9BjqkAS8zc0pyFMhBGr%2BAdr7CIe%2BZHXryLc4gS6n6gDYu8IsjY6Pb9uDlzUGpZuF62N86ENVqEKe4k74VpRw3j4dYRkNSmBgNkpisSnYaWAV%2Fzk3%2B18uOkakrvNFToYyQV2B%2FlLFPCNhGmqq7DNJWhbtZy6IwtlBVo7cmTOs8GOMAGZiJ6sWMykmESBrvkBXw4Wbz53QxB07bYS9XTF9EVy6D%2B494TJhf&X-Amz-Signature=a91ed9e480ed1b85d604f2b52a61ab09e7a50446060410c9b16b6535609f33db&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VEASOB3B%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T132419Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDidRwr9f45FICyY5A6N2Wq3XWuOHr%2BTA10YdScZ0Sz0gIhALezGl9cC2jjr1xYUNWUl2k3xht8V7SmvA7nYHubROKiKv8DCBUQABoMNjM3NDIzMTgzODA1IgyliSpxD53xTqI0hWcq3ANDeEo5gq5bWxoSChFJy6Rs73aBuhXxVpGx0eFdiPqYW2%2BKmwQ%2BigKs74Loih%2F4vUWtJf2vKbarg0M77ZFP112Pij7O0kSIMhrTkrDvxhwV%2FJ8%2B3GZV6nq20uQ7xfTJwfLdg46Y7s2vQWvsr7%2BKFuoUf14fIdLIJ4R4TyhxcnRBmC%2FcBd0wUQyVlGcmOhgoSelTCo7K8gObDieISj2842ul5xHEd1DHKpkNK%2FDLXhkIQ2LA%2Bvzy4u2nbGOxkU07czAM8KvH%2FojXgOKv03UVkJUOIyiXRqA3GY%2F2sGm%2Bc54klwUc%2Ff81j1ogOU54R1M%2FLeVmvnazy2dxabBG0SO8BPX9c%2BGVVUIviPLHNqQh65ioyKji8uFfHuNaKFUzA6hDMQ2otWNTBbVax9ZwNsiMm7N8n3gBVq7BoOb7ToloEWwBhBV3%2FkQzfUUYKgiIzXNBrhvYjZsRlZWELtQemXDafNIz4%2FdxZHnzNGMDk2JWzy9xidx6uIVE6NWMg8szFhx7GpaMsaiWbXapaFHLsbRAzqeFE1W6Udz%2B2KfFBqwobzqrc4%2BvZYesGiwyV5zihbGxuIQ2yovwRHYu1Fob4SWlPy%2BfImAX%2FoEzA7tfr7TXgH0cSRT%2FAXPIJKsDQfvuazDynuy9BjqkAS8zc0pyFMhBGr%2BAdr7CIe%2BZHXryLc4gS6n6gDYu8IsjY6Pb9uDlzUGpZuF62N86ENVqEKe4k74VpRw3j4dYRkNSmBgNkpisSnYaWAV%2Fzk3%2B18uOkakrvNFToYyQV2B%2FlLFPCNhGmqq7DNJWhbtZy6IwtlBVo7cmTOs8GOMAGZiJ6sWMykmESBrvkBXw4Wbz53QxB07bYS9XTF9EVy6D%2B494TJhf&X-Amz-Signature=982fa0e778e28a2828dfec8a8c4749fc0732b02f3a8968b6fb3b9f3f4f77d126&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VEASOB3B%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T132419Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDidRwr9f45FICyY5A6N2Wq3XWuOHr%2BTA10YdScZ0Sz0gIhALezGl9cC2jjr1xYUNWUl2k3xht8V7SmvA7nYHubROKiKv8DCBUQABoMNjM3NDIzMTgzODA1IgyliSpxD53xTqI0hWcq3ANDeEo5gq5bWxoSChFJy6Rs73aBuhXxVpGx0eFdiPqYW2%2BKmwQ%2BigKs74Loih%2F4vUWtJf2vKbarg0M77ZFP112Pij7O0kSIMhrTkrDvxhwV%2FJ8%2B3GZV6nq20uQ7xfTJwfLdg46Y7s2vQWvsr7%2BKFuoUf14fIdLIJ4R4TyhxcnRBmC%2FcBd0wUQyVlGcmOhgoSelTCo7K8gObDieISj2842ul5xHEd1DHKpkNK%2FDLXhkIQ2LA%2Bvzy4u2nbGOxkU07czAM8KvH%2FojXgOKv03UVkJUOIyiXRqA3GY%2F2sGm%2Bc54klwUc%2Ff81j1ogOU54R1M%2FLeVmvnazy2dxabBG0SO8BPX9c%2BGVVUIviPLHNqQh65ioyKji8uFfHuNaKFUzA6hDMQ2otWNTBbVax9ZwNsiMm7N8n3gBVq7BoOb7ToloEWwBhBV3%2FkQzfUUYKgiIzXNBrhvYjZsRlZWELtQemXDafNIz4%2FdxZHnzNGMDk2JWzy9xidx6uIVE6NWMg8szFhx7GpaMsaiWbXapaFHLsbRAzqeFE1W6Udz%2B2KfFBqwobzqrc4%2BvZYesGiwyV5zihbGxuIQ2yovwRHYu1Fob4SWlPy%2BfImAX%2FoEzA7tfr7TXgH0cSRT%2FAXPIJKsDQfvuazDynuy9BjqkAS8zc0pyFMhBGr%2BAdr7CIe%2BZHXryLc4gS6n6gDYu8IsjY6Pb9uDlzUGpZuF62N86ENVqEKe4k74VpRw3j4dYRkNSmBgNkpisSnYaWAV%2Fzk3%2B18uOkakrvNFToYyQV2B%2FlLFPCNhGmqq7DNJWhbtZy6IwtlBVo7cmTOs8GOMAGZiJ6sWMykmESBrvkBXw4Wbz53QxB07bYS9XTF9EVy6D%2B494TJhf&X-Amz-Signature=094aca43ef52d606ba29e8c7bda0b6a1fbecb51dbf252940bb64ac409565e50b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VEASOB3B%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T132419Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDidRwr9f45FICyY5A6N2Wq3XWuOHr%2BTA10YdScZ0Sz0gIhALezGl9cC2jjr1xYUNWUl2k3xht8V7SmvA7nYHubROKiKv8DCBUQABoMNjM3NDIzMTgzODA1IgyliSpxD53xTqI0hWcq3ANDeEo5gq5bWxoSChFJy6Rs73aBuhXxVpGx0eFdiPqYW2%2BKmwQ%2BigKs74Loih%2F4vUWtJf2vKbarg0M77ZFP112Pij7O0kSIMhrTkrDvxhwV%2FJ8%2B3GZV6nq20uQ7xfTJwfLdg46Y7s2vQWvsr7%2BKFuoUf14fIdLIJ4R4TyhxcnRBmC%2FcBd0wUQyVlGcmOhgoSelTCo7K8gObDieISj2842ul5xHEd1DHKpkNK%2FDLXhkIQ2LA%2Bvzy4u2nbGOxkU07czAM8KvH%2FojXgOKv03UVkJUOIyiXRqA3GY%2F2sGm%2Bc54klwUc%2Ff81j1ogOU54R1M%2FLeVmvnazy2dxabBG0SO8BPX9c%2BGVVUIviPLHNqQh65ioyKji8uFfHuNaKFUzA6hDMQ2otWNTBbVax9ZwNsiMm7N8n3gBVq7BoOb7ToloEWwBhBV3%2FkQzfUUYKgiIzXNBrhvYjZsRlZWELtQemXDafNIz4%2FdxZHnzNGMDk2JWzy9xidx6uIVE6NWMg8szFhx7GpaMsaiWbXapaFHLsbRAzqeFE1W6Udz%2B2KfFBqwobzqrc4%2BvZYesGiwyV5zihbGxuIQ2yovwRHYu1Fob4SWlPy%2BfImAX%2FoEzA7tfr7TXgH0cSRT%2FAXPIJKsDQfvuazDynuy9BjqkAS8zc0pyFMhBGr%2BAdr7CIe%2BZHXryLc4gS6n6gDYu8IsjY6Pb9uDlzUGpZuF62N86ENVqEKe4k74VpRw3j4dYRkNSmBgNkpisSnYaWAV%2Fzk3%2B18uOkakrvNFToYyQV2B%2FlLFPCNhGmqq7DNJWhbtZy6IwtlBVo7cmTOs8GOMAGZiJ6sWMykmESBrvkBXw4Wbz53QxB07bYS9XTF9EVy6D%2B494TJhf&X-Amz-Signature=fc3c95ad922b9360a56ae8acc1eb2f3640a72fe4c346a4712c01c5cf3962284b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VEASOB3B%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T132419Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDidRwr9f45FICyY5A6N2Wq3XWuOHr%2BTA10YdScZ0Sz0gIhALezGl9cC2jjr1xYUNWUl2k3xht8V7SmvA7nYHubROKiKv8DCBUQABoMNjM3NDIzMTgzODA1IgyliSpxD53xTqI0hWcq3ANDeEo5gq5bWxoSChFJy6Rs73aBuhXxVpGx0eFdiPqYW2%2BKmwQ%2BigKs74Loih%2F4vUWtJf2vKbarg0M77ZFP112Pij7O0kSIMhrTkrDvxhwV%2FJ8%2B3GZV6nq20uQ7xfTJwfLdg46Y7s2vQWvsr7%2BKFuoUf14fIdLIJ4R4TyhxcnRBmC%2FcBd0wUQyVlGcmOhgoSelTCo7K8gObDieISj2842ul5xHEd1DHKpkNK%2FDLXhkIQ2LA%2Bvzy4u2nbGOxkU07czAM8KvH%2FojXgOKv03UVkJUOIyiXRqA3GY%2F2sGm%2Bc54klwUc%2Ff81j1ogOU54R1M%2FLeVmvnazy2dxabBG0SO8BPX9c%2BGVVUIviPLHNqQh65ioyKji8uFfHuNaKFUzA6hDMQ2otWNTBbVax9ZwNsiMm7N8n3gBVq7BoOb7ToloEWwBhBV3%2FkQzfUUYKgiIzXNBrhvYjZsRlZWELtQemXDafNIz4%2FdxZHnzNGMDk2JWzy9xidx6uIVE6NWMg8szFhx7GpaMsaiWbXapaFHLsbRAzqeFE1W6Udz%2B2KfFBqwobzqrc4%2BvZYesGiwyV5zihbGxuIQ2yovwRHYu1Fob4SWlPy%2BfImAX%2FoEzA7tfr7TXgH0cSRT%2FAXPIJKsDQfvuazDynuy9BjqkAS8zc0pyFMhBGr%2BAdr7CIe%2BZHXryLc4gS6n6gDYu8IsjY6Pb9uDlzUGpZuF62N86ENVqEKe4k74VpRw3j4dYRkNSmBgNkpisSnYaWAV%2Fzk3%2B18uOkakrvNFToYyQV2B%2FlLFPCNhGmqq7DNJWhbtZy6IwtlBVo7cmTOs8GOMAGZiJ6sWMykmESBrvkBXw4Wbz53QxB07bYS9XTF9EVy6D%2B494TJhf&X-Amz-Signature=e3aa1e6da1ec1a12868500aae5fc74e72ae908bad578580ad962c85e3b6959f7&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z6E2SMNB%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T132419Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDMDLy7GR6BknMmmON0wxlo%2BkJ3q1TGenxyRc4UandqPQIgTcvN5J8ZEIAPNHrLJ9Qq3J9oQPV6PVpISVWeoiKvEFUq%2FwMIExAAGgw2Mzc0MjMxODM4MDUiDJFiJYUShBQIrDAKmSrcA4zVZuSKc5sqaBQ73%2Bv8fU6oPQxhEsISpliPUe%2F35D6fTQgLGconhF5ivsAyXdD70v3iRtlwk%2BzVgJgeRa4bEtTGMi69CuHHpV4x8e7FPbzHVqYWXsi541jNUjM6C%2Bs4gKQFGOMdEt9AsTEuexZVBtuAlFNU47e%2F5BTDjdvxNT%2Fe%2F86I5WGS%2BCF3s8Dt4%2Fykp3%2FH7fNwzKK8XWiSQDp6apUqzAo1muMyDWa85PdKysu8flnQiOC5D9Vq%2F7fUg%2FoGQ46cpKrnyN6Mntfwe50i7va9lVSn3tE3YJyy8thrdz0YHsJvoLC1%2B8gUt77tHMiH8MzZYpxG5%2BNnPIYSQfTM00mRcqgPAITvqdUjIB71UTmtydiHO1NvHBYBD8B5NCcCZpbL26Oe8XNCPnj5kpVu8HT3EjjVY8vcw6TxGF%2BBEabrYy0%2B%2FyAeH0zEujDyBYOs%2B4rbz0wCOSxExS%2B5kSc41UjLRSkcv4uvc3ZHFNaw96JlrICCo64f%2FK30xshI77yngI2zuLrnfM0gODy1fiEqOAG6ZHUKHmMrKkWCERK5VPhGAzFEJV8cT4tjkGgV%2FRdfAfUvlKjnfk83nT8VxmCZ6p6mATp9q0UFhWuVBnXIS93Eei75RyU%2Fy%2BFDhvGVMLrj670GOqUBywf1wE%2BNFZO1DoekzHacxri6gl0qh0bYA7u%2BWOL6jX6LGdDSVPmlyXmTHcgNe0uUPJ3GgmLUYzBa3sI%2Bg2Ix4%2BX7z8EkcHNmrafl9FUn%2BQLV%2B%2Fn0TrLXWj6hbpYtt6Z43r3FiauUB1raH3YHTeBPJRO7xBWrgqton758L2ElU8Z56GwkaZdm6XBfaTa8W%2B1OhlQJdpqA3z5l8gu2m3Pt7cKxiUDK&X-Amz-Signature=4cd6939c113e39d714ee2e56a00730c337d039b73f309650f5248f4e84ee4e11&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665WKJNLLD%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T132421Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC%2B0GG0M0NRpZBZihPdNGssqgudlglXrtenXDKo1NOThwIhALrQymQ76Hkm5VzNg1zPRt1H7dtDZTZUgKgFPMFh8g8cKv8DCBUQABoMNjM3NDIzMTgzODA1IgxrbpNkv9zWTFjhi6Iq3APdjl%2FBRj04U15l6tN%2Fdb3VfYVK19O%2FR7F1Skg76ktnHCAgJ%2FZ3UQED83u%2B4lMO7GsGUWVaGOzh7hxu%2FrGBYYDFQmf%2FNJKpWFPndpxZfF53%2BA6IUszwdouVK4MXnuJ3ajg7Dmnx7m%2FiLY7%2F9n8a98HzleDQYFN1jpuK3edKAr1vUal4yYXS%2F0szNAOghSsryD2ykxp2sQwLat1UbX6YrgWZilueOJKnvrIWzM7h1%2FRx8kjrF9%2BamIHrGRCPt9z18fCoH5KQgYksFAxsbbBMjTm9rsggEj2NeH1TdGsaWyf4qdEJdqoL7jULj1LnRh48lYWE27ercQcPb0tnTJHm%2BnL3prrcK76Hzol7lLyGZNErDHnb5macj5zMXrVvHgFHbdGCOgbZKHKWhl%2B2ODdhzmWm8EHZszCKdnliyobJm7%2F0RcnmuxbR6tEEwQi1dWnF0YdwHT2bPDg%2FcnpyPBLo43tN1zqRx53BztJq%2BMe9HB0eRm%2F%2BiRDM79wOmBRaSeBbuBJPMSjUO%2BwDmrL2v4k6xtiHSCF4FP2hzBQE1tsQkBp9kWKINAW6B6wvER3eVB6sRojqKtN2Mn%2BH4ec0jW%2BtbmHIBd5scwaews1z4LSsmWMMb3eZ2VaDngMF7WXZbDCWo%2By9BjqkAdz0c%2B8%2FQmBr7kONBJXTvKaparR3GdKFCHPDdXP8llgmaH6e0KKrKnvX9DEATYO33Y7v4fpHBhPRNCC69huecBwVcfbjayQZ2VoLd27hGj2sSUZEXVfp%2Brk3mU%2FE4uwNwy3thD1BZO11ZtU%2BQ9o0Yltuw0WThSE%2BT3hBBh3uCYNQUmw%2FG6VUE8oqfB47zK0eedfsW8VER3amUr76ohHNH8T%2BG6pp&X-Amz-Signature=882787e432d45bce675756bef83a062a8f9ec06c7bbba910c78a87ac0eae151d&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VEASOB3B%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T132419Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDidRwr9f45FICyY5A6N2Wq3XWuOHr%2BTA10YdScZ0Sz0gIhALezGl9cC2jjr1xYUNWUl2k3xht8V7SmvA7nYHubROKiKv8DCBUQABoMNjM3NDIzMTgzODA1IgyliSpxD53xTqI0hWcq3ANDeEo5gq5bWxoSChFJy6Rs73aBuhXxVpGx0eFdiPqYW2%2BKmwQ%2BigKs74Loih%2F4vUWtJf2vKbarg0M77ZFP112Pij7O0kSIMhrTkrDvxhwV%2FJ8%2B3GZV6nq20uQ7xfTJwfLdg46Y7s2vQWvsr7%2BKFuoUf14fIdLIJ4R4TyhxcnRBmC%2FcBd0wUQyVlGcmOhgoSelTCo7K8gObDieISj2842ul5xHEd1DHKpkNK%2FDLXhkIQ2LA%2Bvzy4u2nbGOxkU07czAM8KvH%2FojXgOKv03UVkJUOIyiXRqA3GY%2F2sGm%2Bc54klwUc%2Ff81j1ogOU54R1M%2FLeVmvnazy2dxabBG0SO8BPX9c%2BGVVUIviPLHNqQh65ioyKji8uFfHuNaKFUzA6hDMQ2otWNTBbVax9ZwNsiMm7N8n3gBVq7BoOb7ToloEWwBhBV3%2FkQzfUUYKgiIzXNBrhvYjZsRlZWELtQemXDafNIz4%2FdxZHnzNGMDk2JWzy9xidx6uIVE6NWMg8szFhx7GpaMsaiWbXapaFHLsbRAzqeFE1W6Udz%2B2KfFBqwobzqrc4%2BvZYesGiwyV5zihbGxuIQ2yovwRHYu1Fob4SWlPy%2BfImAX%2FoEzA7tfr7TXgH0cSRT%2FAXPIJKsDQfvuazDynuy9BjqkAS8zc0pyFMhBGr%2BAdr7CIe%2BZHXryLc4gS6n6gDYu8IsjY6Pb9uDlzUGpZuF62N86ENVqEKe4k74VpRw3j4dYRkNSmBgNkpisSnYaWAV%2Fzk3%2B18uOkakrvNFToYyQV2B%2FlLFPCNhGmqq7DNJWhbtZy6IwtlBVo7cmTOs8GOMAGZiJ6sWMykmESBrvkBXw4Wbz53QxB07bYS9XTF9EVy6D%2B494TJhf&X-Amz-Signature=e5141e98770376315388a87013b76ff69e812acffee4b79bb20f7960aea61318&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VEASOB3B%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T132419Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDidRwr9f45FICyY5A6N2Wq3XWuOHr%2BTA10YdScZ0Sz0gIhALezGl9cC2jjr1xYUNWUl2k3xht8V7SmvA7nYHubROKiKv8DCBUQABoMNjM3NDIzMTgzODA1IgyliSpxD53xTqI0hWcq3ANDeEo5gq5bWxoSChFJy6Rs73aBuhXxVpGx0eFdiPqYW2%2BKmwQ%2BigKs74Loih%2F4vUWtJf2vKbarg0M77ZFP112Pij7O0kSIMhrTkrDvxhwV%2FJ8%2B3GZV6nq20uQ7xfTJwfLdg46Y7s2vQWvsr7%2BKFuoUf14fIdLIJ4R4TyhxcnRBmC%2FcBd0wUQyVlGcmOhgoSelTCo7K8gObDieISj2842ul5xHEd1DHKpkNK%2FDLXhkIQ2LA%2Bvzy4u2nbGOxkU07czAM8KvH%2FojXgOKv03UVkJUOIyiXRqA3GY%2F2sGm%2Bc54klwUc%2Ff81j1ogOU54R1M%2FLeVmvnazy2dxabBG0SO8BPX9c%2BGVVUIviPLHNqQh65ioyKji8uFfHuNaKFUzA6hDMQ2otWNTBbVax9ZwNsiMm7N8n3gBVq7BoOb7ToloEWwBhBV3%2FkQzfUUYKgiIzXNBrhvYjZsRlZWELtQemXDafNIz4%2FdxZHnzNGMDk2JWzy9xidx6uIVE6NWMg8szFhx7GpaMsaiWbXapaFHLsbRAzqeFE1W6Udz%2B2KfFBqwobzqrc4%2BvZYesGiwyV5zihbGxuIQ2yovwRHYu1Fob4SWlPy%2BfImAX%2FoEzA7tfr7TXgH0cSRT%2FAXPIJKsDQfvuazDynuy9BjqkAS8zc0pyFMhBGr%2BAdr7CIe%2BZHXryLc4gS6n6gDYu8IsjY6Pb9uDlzUGpZuF62N86ENVqEKe4k74VpRw3j4dYRkNSmBgNkpisSnYaWAV%2Fzk3%2B18uOkakrvNFToYyQV2B%2FlLFPCNhGmqq7DNJWhbtZy6IwtlBVo7cmTOs8GOMAGZiJ6sWMykmESBrvkBXw4Wbz53QxB07bYS9XTF9EVy6D%2B494TJhf&X-Amz-Signature=4bec2b6140a1f5854acf9384d86269b6c702d6964dc7cff1cb7f9c49afb7d4cd&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VEASOB3B%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T132419Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDidRwr9f45FICyY5A6N2Wq3XWuOHr%2BTA10YdScZ0Sz0gIhALezGl9cC2jjr1xYUNWUl2k3xht8V7SmvA7nYHubROKiKv8DCBUQABoMNjM3NDIzMTgzODA1IgyliSpxD53xTqI0hWcq3ANDeEo5gq5bWxoSChFJy6Rs73aBuhXxVpGx0eFdiPqYW2%2BKmwQ%2BigKs74Loih%2F4vUWtJf2vKbarg0M77ZFP112Pij7O0kSIMhrTkrDvxhwV%2FJ8%2B3GZV6nq20uQ7xfTJwfLdg46Y7s2vQWvsr7%2BKFuoUf14fIdLIJ4R4TyhxcnRBmC%2FcBd0wUQyVlGcmOhgoSelTCo7K8gObDieISj2842ul5xHEd1DHKpkNK%2FDLXhkIQ2LA%2Bvzy4u2nbGOxkU07czAM8KvH%2FojXgOKv03UVkJUOIyiXRqA3GY%2F2sGm%2Bc54klwUc%2Ff81j1ogOU54R1M%2FLeVmvnazy2dxabBG0SO8BPX9c%2BGVVUIviPLHNqQh65ioyKji8uFfHuNaKFUzA6hDMQ2otWNTBbVax9ZwNsiMm7N8n3gBVq7BoOb7ToloEWwBhBV3%2FkQzfUUYKgiIzXNBrhvYjZsRlZWELtQemXDafNIz4%2FdxZHnzNGMDk2JWzy9xidx6uIVE6NWMg8szFhx7GpaMsaiWbXapaFHLsbRAzqeFE1W6Udz%2B2KfFBqwobzqrc4%2BvZYesGiwyV5zihbGxuIQ2yovwRHYu1Fob4SWlPy%2BfImAX%2FoEzA7tfr7TXgH0cSRT%2FAXPIJKsDQfvuazDynuy9BjqkAS8zc0pyFMhBGr%2BAdr7CIe%2BZHXryLc4gS6n6gDYu8IsjY6Pb9uDlzUGpZuF62N86ENVqEKe4k74VpRw3j4dYRkNSmBgNkpisSnYaWAV%2Fzk3%2B18uOkakrvNFToYyQV2B%2FlLFPCNhGmqq7DNJWhbtZy6IwtlBVo7cmTOs8GOMAGZiJ6sWMykmESBrvkBXw4Wbz53QxB07bYS9XTF9EVy6D%2B494TJhf&X-Amz-Signature=4c63d82f8a8302412826fbad36e88846561d8d57c2e861bf2ab7a3fcb9fcd9dd&X-Amz-SignedHeaders=host&x-id=GetObject)


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

