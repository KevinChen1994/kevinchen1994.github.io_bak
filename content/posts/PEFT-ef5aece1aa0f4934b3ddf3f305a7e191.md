---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB46637FXZKLG%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250211T124601Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEL3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDwfUQY6pze11h5dEY\
  nj16uvkauihQrF0mgo6I5k3ByYwIhAK%2BhhQ3LDQKGq6v9NMhRccz0oR1hIxxPswsp0X%2FHmEM0\
  KogECNb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igytu5N%2FzMEGibJ\
  NTm4q3ANo7gpATGvsa5Cur3LsBWvbj22NoXPEDwPNsHVGYomdUERyLNOEiXKTnGU%2Buwpk5pl%2B\
  kZoN%2Feq1mNpLfvyC778%2F7vMccl%2BTw8oVWYwPPOIQjuklNq2uKwW6umy0wusjwcusWzal09z\
  kK4fZ1IwdfWjBq9kEfTv%2F2u%2Fu6DixKzQUBbP9m3ZcRzl4sl2Fl%2FGqYQsE3i5i57tCwEVqUd\
  quN%2BbJ%2FETa30tlM%2FQiuf665Uubil7ldY1Eo%2B931g%2FOlSf5F3rPqNGmG%2BYJnsA5DYw\
  UTuT2nz34UBQarT529A0SZ3c3DABzRpVdxMJnsVDjjRa9BMBKu9l509%2Fm%2BtaogMqQovR9fFWs\
  lFpI%2B%2BjZ%2FEUwYdHTzqkHqKU7em%2BTpTESJ%2FTDXasEx3ie4urCl3d5ORPDXPT7fsU%2Fu\
  wVCbiQgkPvC%2F9%2BBS8YsYYxi1LbpIbejxJWesGyuN1SoYNtFOQFpDpamplm2sPTMPWaiWxy65Z\
  F8MALrOctcE73fRuspdDLG5uKVaBm%2BaRgQPsZosQBF1lcLv64%2Flhur9vnycgNEGTa%2B4eWw0\
  ddG3C47d%2BcwKkdiF%2FrXuR3HOcCnvDxxYdzONN6bL908GTaclUN978MrY6DOnXjrlMnUpMKexD\
  febnTWDTDXiq29BjqkAd%2B%2BNTUwz5oEsGkLmP6KfHhGEzbp2ucHO2PSIP0Fk3RXoT2OpC1oMjm\
  kqLUyB8FHouJ1Ua1vHQxqHV5QWKSjXjulAW%2Bd1oD15xiGrh3WVhkw%2BwcU2paywCGBnbG1oP6z\
  eTVDdCeoYhpt4Ws6U7AbxuW26jiFPob3LruvCfz1MWULFO2i3fjjAoo6q32tY6tLK1Q9IYGh5OhwM\
  rd%2FhxFuDEv8inwf&X-Amz-Signature=9ec3d9b5e53952ddac3e363cab0a34c235641105036\
  2dbe7e4b747513df76d8f&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466SNMN46UY%2F20250211%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250211T124447Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEL3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQ\
        CICl0SYhflWe6A%2BTIz8i2O1OyOOpzg7HxGFD2F8c501fmAiAd%2F9XaMHuCCZBQx2FBHr\
        1MBPrbe5ScN7EGdITh0RHM6SqIBAjW%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzN\
        zQyMzE4MzgwNSIMUIVHmiaFqKySspxoKtwDgaU1pYqXk63d6LX%2B2TpR0%2BkVOqNlfV5o\
        SMbQKau796P6H7hYLFR3Yvn7oH3Cr%2FSb0hWQ7LdatfTV676a1s5li9Z3BEDnNcGYC4Afv\
        kA4OEIQSjfLE1AlpuZe10Rr%2FGfZN1g35uqvmUteDww%2BkzGqDScxVCpXL9UG74z7NJNe\
        NxX%2BW9dsiigku3SZ%2BVoONcLm0rwhhF9RUcIsfvnc8TSTamsStxg4YljOTJoyuuVJrT4\
        xVUVTHtWN0A4fM5pA41ebndtrvG58PbU%2BiXv1X0FAx%2F5Ey0tIZoR9MLzSZ1cpKyYGbb\
        YyTg2f6PmCbtU8ZKL0zNPaVGKcNVXdhfrR1FWC%2BUpizcuNeuxOTRYh5rf6QuH7EEjc8ft\
        fFTXz2CV9j%2BqDw3unhIkvDR9NPGA1PvnPxpyuJZFwMiCQLVuYbbHwsSlan7s3UwG25rvO\
        ResQsluuCGHSI%2BMhLhm%2FXWDbx%2BzCDBo0DHWFW4WaZnxWmiFczrlQ7DEtI182nnWsb\
        6WAAguZAHv%2Fdj33ghAqh%2FHFEq3ZidWWWd26CJW7y6oxGNqsla%2BK69F8HihTOn92Ls\
        yZJ1Ug8V5B%2FRHoGv6qSdCfU%2Beib7WCwDUPxb6e9EIIlQST5BQY127w6QsmHSJhr1Qw%\
        2FIqtvQY6pgFQeaMnlPeWmh5htpVb1nAYHk77ARnTlKYEv6BHGBJuZFsaknqwl4XNz2%2Fe\
        3FWWiOvjPTFYN5UBTsCcUeGnkvszN1ANj26sYS9OKILNZX7VB7%2FbeqB87jgiDcym0DRGY\
        hYFIwCrnI9jA1Mmwto9CVARqhAwGAhuU1rYDXf2MQIEEWlkeWNS9mh9ucrX84l7m2LIKToe\
        %2FbDl%2FVXkrTwNi8SONAabo7Iy&X-Amz-Signature=b92501c375475c5d6c258dfc31\
        dea8427f9d97cf99b7f983e6a696a425ee768c&X-Amz-SignedHeaders=host&x-id=Ge\
        tObject"
      expiry_time: "2025-02-11T13:44:47.686Z"
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
UPDATE_TIME: "2025-02-11T12:46:08.821Z"
EXPIRY_TIME: "2025-02-11T13:45:59.578Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UQKOIMUY%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T124559Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIB3%2Bqu5fbwAep4FrQyK9pu86KvUNuCcD4RK7AddAY3UIAiEAvIpOdZhNlHXen3Qkm5s%2FW6qcLAYTmuBcsMEoczGvkMUqiAQI1v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDEvN1xIaAL5h9XwuPSrcA2b9ChQjc5hJtC2UnQ1CPtH734jDQwrouPqmu9HPjtViTXCXNYF8EHfSFKNQNYkFKr1ZJYuunUp1Nh0%2FeCj17AOgqF7RZOM%2Bsiw5h5vQJCmLvWUFOBbk0wW3Kj5tB0vL777wsBtKA%2Fepk%2BAvCxIFgATEwLywkhOuxUq8VIO9kbouT1lBqK6T8%2Bi0TE6%2BlzaXEAUuMtkzxxHH5duQq%2FiEZwpE0LlXQnESlUjCZYowFSSc4MvCD%2F%2FPxZmVhNSwPdBvSAIWVl9acqmyGH893FNZqth1lc1TlEVT25%2FWtgJjxyttGD6H09V7%2BIxZwhwMithpQ9TLTVV4fgsOtXCkOHJSjuNMNhdmsCePXlcIeeAlMbawCtZApf6FUiFxQ2qEAEhM2GfUu2BdHgdFtyHZIevwJMs8yL19aPakwk5B69fxeXgSGuqSZCrccIdq%2Fd%2FZlxN1RWR82CMqltOoP4%2FwhoFfLCP6zHcnxxnSnqT4WACNpchbjy4adB7UFwoNDyAwOPTb4hIGFuYns2pNLQmrt84bw2wXZfu8X64gxRZb9rYwGvoSySz66k3JyMgZHq5Ezf2W139WKVY5Xklcdndf8HEX5D0POxy0BvhxuwTZEqsHDBbwQ%2FFewcMQ%2BkSwAm%2FzMNqKrb0GOqUBy4EIgTKoOWVEQs%2FqLvOuZLJRYk0AaGv7ELFUw5SSmbQUx0tdwn8Exl2yVLSTFwMtW%2F6WSnrC8StjNwrJb2TRJrTkB1zq3VDcF9zkk%2FNUhK8QnmX2jsrTJogN1sbCRPff3pVE06T9jsn5AV%2BT6kKnN7xS%2FNpaYKb%2Fk6U9%2F0%2FyM3m2XoiEuUm4obWIMpwqdAr7hL4GkHlfxhUEz9mBvme4q%2FUbzb2X&X-Amz-Signature=46d1ed80a927c56853d0eb9b659d890500c043f4876a3559d92961d22fd658c9&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UQKOIMUY%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T124600Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIB3%2Bqu5fbwAep4FrQyK9pu86KvUNuCcD4RK7AddAY3UIAiEAvIpOdZhNlHXen3Qkm5s%2FW6qcLAYTmuBcsMEoczGvkMUqiAQI1v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDEvN1xIaAL5h9XwuPSrcA2b9ChQjc5hJtC2UnQ1CPtH734jDQwrouPqmu9HPjtViTXCXNYF8EHfSFKNQNYkFKr1ZJYuunUp1Nh0%2FeCj17AOgqF7RZOM%2Bsiw5h5vQJCmLvWUFOBbk0wW3Kj5tB0vL777wsBtKA%2Fepk%2BAvCxIFgATEwLywkhOuxUq8VIO9kbouT1lBqK6T8%2Bi0TE6%2BlzaXEAUuMtkzxxHH5duQq%2FiEZwpE0LlXQnESlUjCZYowFSSc4MvCD%2F%2FPxZmVhNSwPdBvSAIWVl9acqmyGH893FNZqth1lc1TlEVT25%2FWtgJjxyttGD6H09V7%2BIxZwhwMithpQ9TLTVV4fgsOtXCkOHJSjuNMNhdmsCePXlcIeeAlMbawCtZApf6FUiFxQ2qEAEhM2GfUu2BdHgdFtyHZIevwJMs8yL19aPakwk5B69fxeXgSGuqSZCrccIdq%2Fd%2FZlxN1RWR82CMqltOoP4%2FwhoFfLCP6zHcnxxnSnqT4WACNpchbjy4adB7UFwoNDyAwOPTb4hIGFuYns2pNLQmrt84bw2wXZfu8X64gxRZb9rYwGvoSySz66k3JyMgZHq5Ezf2W139WKVY5Xklcdndf8HEX5D0POxy0BvhxuwTZEqsHDBbwQ%2FFewcMQ%2BkSwAm%2FzMNqKrb0GOqUBy4EIgTKoOWVEQs%2FqLvOuZLJRYk0AaGv7ELFUw5SSmbQUx0tdwn8Exl2yVLSTFwMtW%2F6WSnrC8StjNwrJb2TRJrTkB1zq3VDcF9zkk%2FNUhK8QnmX2jsrTJogN1sbCRPff3pVE06T9jsn5AV%2BT6kKnN7xS%2FNpaYKb%2Fk6U9%2F0%2FyM3m2XoiEuUm4obWIMpwqdAr7hL4GkHlfxhUEz9mBvme4q%2FUbzb2X&X-Amz-Signature=444782de4ffd33ab5ffd61045f2e95eeea46da107dcaa2b3ed05192a6d05f439&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UQKOIMUY%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T124600Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIB3%2Bqu5fbwAep4FrQyK9pu86KvUNuCcD4RK7AddAY3UIAiEAvIpOdZhNlHXen3Qkm5s%2FW6qcLAYTmuBcsMEoczGvkMUqiAQI1v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDEvN1xIaAL5h9XwuPSrcA2b9ChQjc5hJtC2UnQ1CPtH734jDQwrouPqmu9HPjtViTXCXNYF8EHfSFKNQNYkFKr1ZJYuunUp1Nh0%2FeCj17AOgqF7RZOM%2Bsiw5h5vQJCmLvWUFOBbk0wW3Kj5tB0vL777wsBtKA%2Fepk%2BAvCxIFgATEwLywkhOuxUq8VIO9kbouT1lBqK6T8%2Bi0TE6%2BlzaXEAUuMtkzxxHH5duQq%2FiEZwpE0LlXQnESlUjCZYowFSSc4MvCD%2F%2FPxZmVhNSwPdBvSAIWVl9acqmyGH893FNZqth1lc1TlEVT25%2FWtgJjxyttGD6H09V7%2BIxZwhwMithpQ9TLTVV4fgsOtXCkOHJSjuNMNhdmsCePXlcIeeAlMbawCtZApf6FUiFxQ2qEAEhM2GfUu2BdHgdFtyHZIevwJMs8yL19aPakwk5B69fxeXgSGuqSZCrccIdq%2Fd%2FZlxN1RWR82CMqltOoP4%2FwhoFfLCP6zHcnxxnSnqT4WACNpchbjy4adB7UFwoNDyAwOPTb4hIGFuYns2pNLQmrt84bw2wXZfu8X64gxRZb9rYwGvoSySz66k3JyMgZHq5Ezf2W139WKVY5Xklcdndf8HEX5D0POxy0BvhxuwTZEqsHDBbwQ%2FFewcMQ%2BkSwAm%2FzMNqKrb0GOqUBy4EIgTKoOWVEQs%2FqLvOuZLJRYk0AaGv7ELFUw5SSmbQUx0tdwn8Exl2yVLSTFwMtW%2F6WSnrC8StjNwrJb2TRJrTkB1zq3VDcF9zkk%2FNUhK8QnmX2jsrTJogN1sbCRPff3pVE06T9jsn5AV%2BT6kKnN7xS%2FNpaYKb%2Fk6U9%2F0%2FyM3m2XoiEuUm4obWIMpwqdAr7hL4GkHlfxhUEz9mBvme4q%2FUbzb2X&X-Amz-Signature=04b31a6490e41e50ce22267497e1050c3334dcbae4c9a68e6247b3949ae01867&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UQKOIMUY%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T124600Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIB3%2Bqu5fbwAep4FrQyK9pu86KvUNuCcD4RK7AddAY3UIAiEAvIpOdZhNlHXen3Qkm5s%2FW6qcLAYTmuBcsMEoczGvkMUqiAQI1v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDEvN1xIaAL5h9XwuPSrcA2b9ChQjc5hJtC2UnQ1CPtH734jDQwrouPqmu9HPjtViTXCXNYF8EHfSFKNQNYkFKr1ZJYuunUp1Nh0%2FeCj17AOgqF7RZOM%2Bsiw5h5vQJCmLvWUFOBbk0wW3Kj5tB0vL777wsBtKA%2Fepk%2BAvCxIFgATEwLywkhOuxUq8VIO9kbouT1lBqK6T8%2Bi0TE6%2BlzaXEAUuMtkzxxHH5duQq%2FiEZwpE0LlXQnESlUjCZYowFSSc4MvCD%2F%2FPxZmVhNSwPdBvSAIWVl9acqmyGH893FNZqth1lc1TlEVT25%2FWtgJjxyttGD6H09V7%2BIxZwhwMithpQ9TLTVV4fgsOtXCkOHJSjuNMNhdmsCePXlcIeeAlMbawCtZApf6FUiFxQ2qEAEhM2GfUu2BdHgdFtyHZIevwJMs8yL19aPakwk5B69fxeXgSGuqSZCrccIdq%2Fd%2FZlxN1RWR82CMqltOoP4%2FwhoFfLCP6zHcnxxnSnqT4WACNpchbjy4adB7UFwoNDyAwOPTb4hIGFuYns2pNLQmrt84bw2wXZfu8X64gxRZb9rYwGvoSySz66k3JyMgZHq5Ezf2W139WKVY5Xklcdndf8HEX5D0POxy0BvhxuwTZEqsHDBbwQ%2FFewcMQ%2BkSwAm%2FzMNqKrb0GOqUBy4EIgTKoOWVEQs%2FqLvOuZLJRYk0AaGv7ELFUw5SSmbQUx0tdwn8Exl2yVLSTFwMtW%2F6WSnrC8StjNwrJb2TRJrTkB1zq3VDcF9zkk%2FNUhK8QnmX2jsrTJogN1sbCRPff3pVE06T9jsn5AV%2BT6kKnN7xS%2FNpaYKb%2Fk6U9%2F0%2FyM3m2XoiEuUm4obWIMpwqdAr7hL4GkHlfxhUEz9mBvme4q%2FUbzb2X&X-Amz-Signature=0942a125547d4ec487a91279f5a0dda6942b8ca8ed6677b02e53684f0fcbf456&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UQKOIMUY%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T124600Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIB3%2Bqu5fbwAep4FrQyK9pu86KvUNuCcD4RK7AddAY3UIAiEAvIpOdZhNlHXen3Qkm5s%2FW6qcLAYTmuBcsMEoczGvkMUqiAQI1v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDEvN1xIaAL5h9XwuPSrcA2b9ChQjc5hJtC2UnQ1CPtH734jDQwrouPqmu9HPjtViTXCXNYF8EHfSFKNQNYkFKr1ZJYuunUp1Nh0%2FeCj17AOgqF7RZOM%2Bsiw5h5vQJCmLvWUFOBbk0wW3Kj5tB0vL777wsBtKA%2Fepk%2BAvCxIFgATEwLywkhOuxUq8VIO9kbouT1lBqK6T8%2Bi0TE6%2BlzaXEAUuMtkzxxHH5duQq%2FiEZwpE0LlXQnESlUjCZYowFSSc4MvCD%2F%2FPxZmVhNSwPdBvSAIWVl9acqmyGH893FNZqth1lc1TlEVT25%2FWtgJjxyttGD6H09V7%2BIxZwhwMithpQ9TLTVV4fgsOtXCkOHJSjuNMNhdmsCePXlcIeeAlMbawCtZApf6FUiFxQ2qEAEhM2GfUu2BdHgdFtyHZIevwJMs8yL19aPakwk5B69fxeXgSGuqSZCrccIdq%2Fd%2FZlxN1RWR82CMqltOoP4%2FwhoFfLCP6zHcnxxnSnqT4WACNpchbjy4adB7UFwoNDyAwOPTb4hIGFuYns2pNLQmrt84bw2wXZfu8X64gxRZb9rYwGvoSySz66k3JyMgZHq5Ezf2W139WKVY5Xklcdndf8HEX5D0POxy0BvhxuwTZEqsHDBbwQ%2FFewcMQ%2BkSwAm%2FzMNqKrb0GOqUBy4EIgTKoOWVEQs%2FqLvOuZLJRYk0AaGv7ELFUw5SSmbQUx0tdwn8Exl2yVLSTFwMtW%2F6WSnrC8StjNwrJb2TRJrTkB1zq3VDcF9zkk%2FNUhK8QnmX2jsrTJogN1sbCRPff3pVE06T9jsn5AV%2BT6kKnN7xS%2FNpaYKb%2Fk6U9%2F0%2FyM3m2XoiEuUm4obWIMpwqdAr7hL4GkHlfxhUEz9mBvme4q%2FUbzb2X&X-Amz-Signature=897a23b69114f8f2bd25438174989bd78fbf7e195a269aa71a0cbd8868b5d463&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664PF2GTX3%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T124600Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD0fAzEd0EWuouL%2B8PkBcQP3%2BL3KFBUFkn9kkqf1pttoQIgKMONRKq8YztA8MLiCOG7ViJoK%2Fih6qHA03ARUniqmrkqiAQI1v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDEf%2B%2BSx%2BNmP8QA8rZyrcAyefHuMg1h%2FX%2B0qvhY%2FNvBp4jnEvsCPDWytJaIl%2FfBDBp%2BrnW4CF4v1FTIksks4DxZtB0%2FZFubqY8j2y9tiJdpPmbPPc0Z4tKEXVoUUJwQWRDz1nZYxlxb7NI3o4Cd1Kvt6VLN42q47ttkXywNXNFG6eT1WcL92B7D7upi9%2Bjoeq3LiZpalN9kh7XokftI%2FCw7ilaTop2H1ZTBMpb6o4Y9BBUBpQ2XaD09bgg6E65HGTiDH4Sz15%2F%2F6thHOvOwkfcI%2BYPLjMjZWjtmxl%2Fwwyn%2BKAKPIsJ3vgSpHReyvpPsbtzeYYxauLPEza8Z8%2B%2Bk503dCbhGIsCU%2B8%2B8ik6TJ3fomCIg6ypHqJ%2Bd4Y9Eq57gGIpGe2jMWOuF4lPjrexG2v%2Bk%2Fv9rPiMRx%2FFfcVhEEQz9x21orXbr9gohwR59R89avbs%2FwHucq%2Ft6G9n%2FMISIjIz%2BF0m4RKz3FFxfbWRBProQsV0WoeWw2fb77ZiHna9h1UptaO0fQFNFpyBcOVdCl%2F6wWdogi8HSjBqzqFC433R0WGUF1tJ%2BgA3ZgatCIYkKJQS8%2BYeP9tI5P1uPCIZzHCi1sJQIqonI0RNa68C6LPmJrYLxbuo0ppOiINFzesuE5r%2BZG3Tt64ReTIZndcMLqKrb0GOqUBM4sRjLs4hFJ98YuTYxkfg41X8OVH6DlNKCavsxs78LvU3x7A4weTIg6VLUygTdM0rj7rSB%2F3vtAZtwzkPYRxvoxTvwA3iyZWw0GY2yHiP3dtalR5tdFOwHo%2BhAy9GEcerMpda6a3%2F6lmy7csom71yWdam%2FkBftnXfGP2rXWMImAxVx9onjsZsEVn4SVcJZ8g%2FfYbGUqRoZJzAruUO0Go38DfweI%2B&X-Amz-Signature=61977ea0c6d2e828b9d93814e07cfb1a3dfd5dcb5839694335894264dd3d3683&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VZZ2GMNI%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T124601Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCMBAekx9Qej7KoQiJGctxTvk2BN2Df4qCMAWR7SLCa8QIhANnTBr2RxFg42%2B0uGuOdQA6c1ZPOdfDzp7viag%2F8FiSyKogECNb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxwCHhOAL6xO9jeifoq3AM1%2Bgaue59jlMAYHwKUit8IZ1UeDGQQXb%2BweK5bIfaENtZVSg9kmU%2B21S5KYNbehWq%2BK3PNIGFCiwFrxbNKmKpb7an44%2FLblOtL6jtNUFmeHjc6VF2f9RTDRdPOVzcx3lbuERl%2FxYOYEAGAeBv9CNTD2sWRjUQnwi%2FcHEQcH9zCyEXwxd%2FLvkWJJgC4QKXB1cegLwgSgBdamaSuN4gPM91ukciptBjde9ZwURTX%2FFTr20MYTjmBQgNXyNbJOCpD8ZBxrADMTGvlADU3nQdp7E0O6LdyTtbnaIKQN67Pw3B4zAW1H%2Bb5xcAZxa39kI9tcixvOmPI5ktFUAfnEun5cI51DXhefDt%2BEPKZr3qj%2BTgzZdo8sjop66Nde6v7ksfHtv%2FWXJWIEDmXsLl%2FDsyqE5L%2Bovjnio679sAgYme8rKEC2Tp4MOr3yMQw34E89gsRDXPemCYIHm90SbYulrNx2vJfS1RXGRSIQmEt0qqCexVSvlk1jTFWpAw2HzdnU4j6SQDKVgAMtH7fuIU6R4PeBoZxokyjMEZzVbCAdk5gYfKFIHqWJQ3I11Yh9ddvFijbUz7jqguABLzM9r7Mzmo1WA3jucRHLDedGGpLmr9g3Gtdi%2B1huA6yILz6qbbrKzD%2Fiq29BjqkAVDTL9ccIcftUSqt1jRYAR%2FhelSyEKTD9JmdoCo66z%2Bvs9zB8LcMB%2BETUG6jn9eDz1gbnzBCM0NFKmmJGLB9X8%2BfBrqC10P8YB7BadE%2FdqKj%2FmiECOKI1Xtrw5BVcaHT1RAVikcZf%2BnFQoNpFcsI9KAzscCT5yw06HLa3t3q%2Fp0A1IttE%2BJ5cFM0Gkpe22rW22rkAQn3LNNfTvsvkY9Wx0fA7yt3&X-Amz-Signature=a748b447e544a484ff4e72f029bd757abdc5c52101835a35052ce53ffd0ed93e&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UQKOIMUY%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T124600Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIB3%2Bqu5fbwAep4FrQyK9pu86KvUNuCcD4RK7AddAY3UIAiEAvIpOdZhNlHXen3Qkm5s%2FW6qcLAYTmuBcsMEoczGvkMUqiAQI1v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDEvN1xIaAL5h9XwuPSrcA2b9ChQjc5hJtC2UnQ1CPtH734jDQwrouPqmu9HPjtViTXCXNYF8EHfSFKNQNYkFKr1ZJYuunUp1Nh0%2FeCj17AOgqF7RZOM%2Bsiw5h5vQJCmLvWUFOBbk0wW3Kj5tB0vL777wsBtKA%2Fepk%2BAvCxIFgATEwLywkhOuxUq8VIO9kbouT1lBqK6T8%2Bi0TE6%2BlzaXEAUuMtkzxxHH5duQq%2FiEZwpE0LlXQnESlUjCZYowFSSc4MvCD%2F%2FPxZmVhNSwPdBvSAIWVl9acqmyGH893FNZqth1lc1TlEVT25%2FWtgJjxyttGD6H09V7%2BIxZwhwMithpQ9TLTVV4fgsOtXCkOHJSjuNMNhdmsCePXlcIeeAlMbawCtZApf6FUiFxQ2qEAEhM2GfUu2BdHgdFtyHZIevwJMs8yL19aPakwk5B69fxeXgSGuqSZCrccIdq%2Fd%2FZlxN1RWR82CMqltOoP4%2FwhoFfLCP6zHcnxxnSnqT4WACNpchbjy4adB7UFwoNDyAwOPTb4hIGFuYns2pNLQmrt84bw2wXZfu8X64gxRZb9rYwGvoSySz66k3JyMgZHq5Ezf2W139WKVY5Xklcdndf8HEX5D0POxy0BvhxuwTZEqsHDBbwQ%2FFewcMQ%2BkSwAm%2FzMNqKrb0GOqUBy4EIgTKoOWVEQs%2FqLvOuZLJRYk0AaGv7ELFUw5SSmbQUx0tdwn8Exl2yVLSTFwMtW%2F6WSnrC8StjNwrJb2TRJrTkB1zq3VDcF9zkk%2FNUhK8QnmX2jsrTJogN1sbCRPff3pVE06T9jsn5AV%2BT6kKnN7xS%2FNpaYKb%2Fk6U9%2F0%2FyM3m2XoiEuUm4obWIMpwqdAr7hL4GkHlfxhUEz9mBvme4q%2FUbzb2X&X-Amz-Signature=3bad4e13052946c79c0493d3e096e31ac999d9e91ca79465835bad533ffd388b&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UQKOIMUY%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T124600Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIB3%2Bqu5fbwAep4FrQyK9pu86KvUNuCcD4RK7AddAY3UIAiEAvIpOdZhNlHXen3Qkm5s%2FW6qcLAYTmuBcsMEoczGvkMUqiAQI1v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDEvN1xIaAL5h9XwuPSrcA2b9ChQjc5hJtC2UnQ1CPtH734jDQwrouPqmu9HPjtViTXCXNYF8EHfSFKNQNYkFKr1ZJYuunUp1Nh0%2FeCj17AOgqF7RZOM%2Bsiw5h5vQJCmLvWUFOBbk0wW3Kj5tB0vL777wsBtKA%2Fepk%2BAvCxIFgATEwLywkhOuxUq8VIO9kbouT1lBqK6T8%2Bi0TE6%2BlzaXEAUuMtkzxxHH5duQq%2FiEZwpE0LlXQnESlUjCZYowFSSc4MvCD%2F%2FPxZmVhNSwPdBvSAIWVl9acqmyGH893FNZqth1lc1TlEVT25%2FWtgJjxyttGD6H09V7%2BIxZwhwMithpQ9TLTVV4fgsOtXCkOHJSjuNMNhdmsCePXlcIeeAlMbawCtZApf6FUiFxQ2qEAEhM2GfUu2BdHgdFtyHZIevwJMs8yL19aPakwk5B69fxeXgSGuqSZCrccIdq%2Fd%2FZlxN1RWR82CMqltOoP4%2FwhoFfLCP6zHcnxxnSnqT4WACNpchbjy4adB7UFwoNDyAwOPTb4hIGFuYns2pNLQmrt84bw2wXZfu8X64gxRZb9rYwGvoSySz66k3JyMgZHq5Ezf2W139WKVY5Xklcdndf8HEX5D0POxy0BvhxuwTZEqsHDBbwQ%2FFewcMQ%2BkSwAm%2FzMNqKrb0GOqUBy4EIgTKoOWVEQs%2FqLvOuZLJRYk0AaGv7ELFUw5SSmbQUx0tdwn8Exl2yVLSTFwMtW%2F6WSnrC8StjNwrJb2TRJrTkB1zq3VDcF9zkk%2FNUhK8QnmX2jsrTJogN1sbCRPff3pVE06T9jsn5AV%2BT6kKnN7xS%2FNpaYKb%2Fk6U9%2F0%2FyM3m2XoiEuUm4obWIMpwqdAr7hL4GkHlfxhUEz9mBvme4q%2FUbzb2X&X-Amz-Signature=76d61f8b4cf755e7bdb6a02fcd610413fa2ba2cbad051453a913261d299e0bc2&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UQKOIMUY%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T124600Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIB3%2Bqu5fbwAep4FrQyK9pu86KvUNuCcD4RK7AddAY3UIAiEAvIpOdZhNlHXen3Qkm5s%2FW6qcLAYTmuBcsMEoczGvkMUqiAQI1v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDEvN1xIaAL5h9XwuPSrcA2b9ChQjc5hJtC2UnQ1CPtH734jDQwrouPqmu9HPjtViTXCXNYF8EHfSFKNQNYkFKr1ZJYuunUp1Nh0%2FeCj17AOgqF7RZOM%2Bsiw5h5vQJCmLvWUFOBbk0wW3Kj5tB0vL777wsBtKA%2Fepk%2BAvCxIFgATEwLywkhOuxUq8VIO9kbouT1lBqK6T8%2Bi0TE6%2BlzaXEAUuMtkzxxHH5duQq%2FiEZwpE0LlXQnESlUjCZYowFSSc4MvCD%2F%2FPxZmVhNSwPdBvSAIWVl9acqmyGH893FNZqth1lc1TlEVT25%2FWtgJjxyttGD6H09V7%2BIxZwhwMithpQ9TLTVV4fgsOtXCkOHJSjuNMNhdmsCePXlcIeeAlMbawCtZApf6FUiFxQ2qEAEhM2GfUu2BdHgdFtyHZIevwJMs8yL19aPakwk5B69fxeXgSGuqSZCrccIdq%2Fd%2FZlxN1RWR82CMqltOoP4%2FwhoFfLCP6zHcnxxnSnqT4WACNpchbjy4adB7UFwoNDyAwOPTb4hIGFuYns2pNLQmrt84bw2wXZfu8X64gxRZb9rYwGvoSySz66k3JyMgZHq5Ezf2W139WKVY5Xklcdndf8HEX5D0POxy0BvhxuwTZEqsHDBbwQ%2FFewcMQ%2BkSwAm%2FzMNqKrb0GOqUBy4EIgTKoOWVEQs%2FqLvOuZLJRYk0AaGv7ELFUw5SSmbQUx0tdwn8Exl2yVLSTFwMtW%2F6WSnrC8StjNwrJb2TRJrTkB1zq3VDcF9zkk%2FNUhK8QnmX2jsrTJogN1sbCRPff3pVE06T9jsn5AV%2BT6kKnN7xS%2FNpaYKb%2Fk6U9%2F0%2FyM3m2XoiEuUm4obWIMpwqdAr7hL4GkHlfxhUEz9mBvme4q%2FUbzb2X&X-Amz-Signature=8b6fc3190e9555e0d1afd8bf6c816bdea01ee05a7dd33f6849f9613e7b041cad&X-Amz-SignedHeaders=host&x-id=GetObject)


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

