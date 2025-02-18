---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4663TNVEZDQ%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250218T232215Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEG8aCXVzLXdlc3QtMiJHMEUCIQCZFksjeR9RpN%2BN95jBA%2BP%2BqaON%2BS0W3fsPG0LsZ1k\
  7cgIgW6vt7whkR00FNc4aG97PKHcyp%2BoKqwhubzops5SOb0kqiAQImP%2F%2F%2F%2F%2F%2F%2\
  F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKDnT5CSfpQu6fsePyrcA%2B2X3EaJD8PI8%2FAmFjU\
  o6NAULp%2BJfwRubcKpDq4V%2BKkjnTT9K02XrlrdYIs%2BucezPu1QlApHxFGa85rd%2Fe2cO4dE\
  vC3UJTkYjCglpbuKz%2FzEp6c9%2BDKIPdtvE219r9YI12GhPjDfo2%2BaInh%2BVfQnh1mDu9dR5\
  emKX4hdYNrOla%2BERcO%2BLQTIuXCy3rJQCF3cNEmmON%2BYCOoNAZWjtHHoNQFwGMHI3pDRZoN2\
  9NSPciH%2BDxDAUwa1BBNyp%2FpW%2Bb0%2F1hRqGowjMaeyvMCVr8cXnGRt2TdtBwiq7hq%2Ba0Y\
  %2BTEGnWY6HKsAKKPQVqvQRb0Fyt6qUQXEGgbRSstOv8c%2FLzZa7WDXEfquxYglinyGesnLhLhnb\
  %2BKbaAq8wFVYptgcGdUs3ZEbT4hnn16CPtHnh9Iduw2xdvSvGKXVrU36LHHe%2BzIpGSwS8BG7Ni\
  ENKQ8D1i%2FLdh4Pw8Z3tsHyZV7LeZc3496g26eAcJGLHsx1vCsSB4%2Bl8uJIls%2FfarEGQZOGw\
  YXYpRlk%2Frk5o2WoO3MEWgSANjBhL5xq8VH9nEQkeanPDX15BsfNsqSy8iFx4wxV6MuxG3q5xfvb\
  cHD0JR6xoYSkz30b1b7jUCAzpCNMhOkRiOzh7UphdaBFrIHHoMJ6S1L0GOqUB6Mt2ZpG8m%2FkaHd\
  FJLFFF8wJVP75YTysXNxghUF9MdOv7G3b4awyH9sE49BopdNXp0uqfb9PgDhT6ZlDmxc6zh5QeElk\
  O4CCWQBzpXrpzVEkGRgPkK%2F%2BIniNiCwf8HjV%2FoWgVhE98fh%2B8D89JCB5J80u9enzgr%2B\
  Y%2FLEhbtkC2LOTshbk0VRX8dfke4fMkeY896wJle3BpSDZO55WmfV7vpfnHh5Cn&X-Amz-Signat\
  ure=cc0fd3c339ac7378d24297844c68fd8aebf41822411fc36406680db90da3e513&X-Amz-Si\
  gnedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4667AO73XJ6%2F20250218%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250218T232047Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEG8aCXVzLXdlc3QtMiJHMEUCIHEO1vMwl8me6rABa%2B1j0BqVyvfUM\
        %2FsUzF27XHfhw5NKAiEAvv%2FGmtnz%2FZHQffdBf6cpWdciMcKS0V4zf6Xr6MIosUwqiA\
        QIl%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDEhlpE5GbcJ\
        DSXJNByrcA38ynNBqWllwU89ZkJBoi7wHFTW358aKeAJDclbE4Tr5x4Pp5qp%2FWv4hu5eX\
        Vyc180YTgSMAas7TMQukyPmgnSY%2FRm%2FbiuJtVtZv7BQIgynHWrZocgfPzz37G%2F16x\
        SjgzxK6VymYzKD0IJgMqEDWmnSHRu1HOpmzlHCr52wU%2Fld%2FNCQv5NGDzHDZfDpz5sAq\
        wQ%2B6KYd04a8pBDmvYOkbkFxsspqj2497wyKf3I64eDZSwaVsKoPepH%2Bc%2F6gH5xMyz\
        rNjIY4O0hK4xJMPXT6zDun331Z9jXffx2M%2Bqaok796M5uloay3oBOWGTKjj09eWmTGnJE\
        muRpcyBKdVii7QJ6v%2B27m%2FtoOucjHQqYlXNeZy5Y1gisMQozeQcpaSZVPCwdETTK0rY\
        XgYMQXEoWEwMfLifaWJJKabBAcnu7%2FglYmFJJ2MX0bB7xAOXMrRArmmw9yJrxCSzbWbvl\
        iChfEZdA4iNhzOA%2FK20teB8dRT26mwj64ZB4I0pD825QaAUzAwOrnAzoWM65eHRpgPz3o\
        jYsvtSz%2F0SHai4nCaQPaBlNEDLDC7ycb3v9KX6nzWHPZ8qI6yL7QYwia5b7lLIgGp%2Bf\
        fk%2BaT%2FN2%2BbVxjX9Am6t%2Bl3fqITO7JR%2FT7L9NZqMLOT1L0GOqUBPbDNUBk5DWo\
        7s3d6Jiw8Qio1l%2FiWezLCCSO0w8C0EZ%2FBx%2BNQE1pcJQFcjjYsFWt4MP1o6R3%2BpC\
        %2F0EF7AqIdRXFEmuAAASF5Zx383pKuif9iombMaTin782KkddLYGgLYXmM1N9lkjHiDU7u\
        1iNrerczzQYdja9H5cei1O9EGT%2BO7NTI9REWUxcQdYMvIgi0sKi9M1V2y3XAfjsiTRZqC\
        CK9XHAty&X-Amz-Signature=3588e5db82e1769f5dd9e7b5d0787daf7650e2b90e8972\
        4436ce47565abf725e&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-19T00:20:47.135Z"
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
UPDATE_TIME: "2025-02-18T23:22:26.728Z"
EXPIRY_TIME: "2025-02-19T00:22:12.207Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664DXTFGYN%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T232212Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG8aCXVzLXdlc3QtMiJIMEYCIQClmGTiB5hf2Y2j4gvuR6JqDTZrOG4jmQAGql2hBUgBiQIhAJ6SD1%2BAuLQkJc%2FWfelHdartZiio0g5TgR0nkHbworE%2BKogECJj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igz8ksTk2bWUclX%2BRKIq3AOKekOqvVE0Q7E5IT6nYOicr8%2F8gR6E4tLIfvJaNWnvHD8XTd6f7jOXs6gxHPoIi9kqilEs%2BUDCvHw%2FLjTekMRyqosgxozbUXjwLaIFztnLtw96Vc%2BalYOtkjmEuu%2BliCiW0xbJ9DuWWQPmcvvdOmzYI5s61kwxnTQu5u%2BeV24w6jz6qw1eMH69%2BF6c1z5aY4RCDG3A1h9JgHlUEHXz8flMEF4N9DCRpxkWmmSfsgV1RyE0HQXs5tsHcuRZ3fWjF9P69o%2B%2BQ5stI6PqJvFvRwJneWAKfFT9jjr4bLR71GWcdWauiU%2B6E12EXv0iHlmM9oEm2rCyAUQ7nYWT4p3%2FPXIbrJsMc1H%2BJVpHTeg5%2FlW%2B7XZRq2rWB05pvHYc6o0qZ4YE6YRgfcFcEImsG5TnLZADZHSEnlDeU0vpdhv2FfZoaFavNorOYZeAllV5IvYQBmdm5FokgyDlmpQI67jYmnxnzFIirvIOYM0tZ2p896vlKsyBW0Dk7scCvAVJ7gZIl%2BxAgQvrqjWBZubjjDt%2BR66m5WTKlhAMM9aJOKZPMg7CUYBs9wOlqelqsJTEa7SZoYQx9e02xSktBQjIvapjzGQIEsELQjNViSubXuuifsvo2TFXE6W7U95%2FPunkWDD1ktS9BjqkAcGVigYiMWqy83kqOD4cRASGAdyvsCSoPINXtpyPqpLGRVYLj8vTwbZtNh%2BJI8yr6%2FZKOEPiMUcb13ICrO0YaJ171QxL42epV9hGMVey87f1xkCLGykq89vWxx%2BE88S29K2%2BY29d73U7z1KHOybT3RKPbyY9apNYMgmoFLhdZcVjKXI%2B7KOslswj50IDC%2FzTmY%2BqoAfBuH%2F8OxViJMnFq5do%2BQlp&X-Amz-Signature=018bf295805b93c9e0a9b3125dcdb74bc9bc5ec909e0a43202bc174af9d68f0d&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664DXTFGYN%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T232212Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG8aCXVzLXdlc3QtMiJIMEYCIQClmGTiB5hf2Y2j4gvuR6JqDTZrOG4jmQAGql2hBUgBiQIhAJ6SD1%2BAuLQkJc%2FWfelHdartZiio0g5TgR0nkHbworE%2BKogECJj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igz8ksTk2bWUclX%2BRKIq3AOKekOqvVE0Q7E5IT6nYOicr8%2F8gR6E4tLIfvJaNWnvHD8XTd6f7jOXs6gxHPoIi9kqilEs%2BUDCvHw%2FLjTekMRyqosgxozbUXjwLaIFztnLtw96Vc%2BalYOtkjmEuu%2BliCiW0xbJ9DuWWQPmcvvdOmzYI5s61kwxnTQu5u%2BeV24w6jz6qw1eMH69%2BF6c1z5aY4RCDG3A1h9JgHlUEHXz8flMEF4N9DCRpxkWmmSfsgV1RyE0HQXs5tsHcuRZ3fWjF9P69o%2B%2BQ5stI6PqJvFvRwJneWAKfFT9jjr4bLR71GWcdWauiU%2B6E12EXv0iHlmM9oEm2rCyAUQ7nYWT4p3%2FPXIbrJsMc1H%2BJVpHTeg5%2FlW%2B7XZRq2rWB05pvHYc6o0qZ4YE6YRgfcFcEImsG5TnLZADZHSEnlDeU0vpdhv2FfZoaFavNorOYZeAllV5IvYQBmdm5FokgyDlmpQI67jYmnxnzFIirvIOYM0tZ2p896vlKsyBW0Dk7scCvAVJ7gZIl%2BxAgQvrqjWBZubjjDt%2BR66m5WTKlhAMM9aJOKZPMg7CUYBs9wOlqelqsJTEa7SZoYQx9e02xSktBQjIvapjzGQIEsELQjNViSubXuuifsvo2TFXE6W7U95%2FPunkWDD1ktS9BjqkAcGVigYiMWqy83kqOD4cRASGAdyvsCSoPINXtpyPqpLGRVYLj8vTwbZtNh%2BJI8yr6%2FZKOEPiMUcb13ICrO0YaJ171QxL42epV9hGMVey87f1xkCLGykq89vWxx%2BE88S29K2%2BY29d73U7z1KHOybT3RKPbyY9apNYMgmoFLhdZcVjKXI%2B7KOslswj50IDC%2FzTmY%2BqoAfBuH%2F8OxViJMnFq5do%2BQlp&X-Amz-Signature=b057d9cdab6475a5f693d88745b62b5a661952177d7af329dc319752675d9034&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664DXTFGYN%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T232212Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG8aCXVzLXdlc3QtMiJIMEYCIQClmGTiB5hf2Y2j4gvuR6JqDTZrOG4jmQAGql2hBUgBiQIhAJ6SD1%2BAuLQkJc%2FWfelHdartZiio0g5TgR0nkHbworE%2BKogECJj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igz8ksTk2bWUclX%2BRKIq3AOKekOqvVE0Q7E5IT6nYOicr8%2F8gR6E4tLIfvJaNWnvHD8XTd6f7jOXs6gxHPoIi9kqilEs%2BUDCvHw%2FLjTekMRyqosgxozbUXjwLaIFztnLtw96Vc%2BalYOtkjmEuu%2BliCiW0xbJ9DuWWQPmcvvdOmzYI5s61kwxnTQu5u%2BeV24w6jz6qw1eMH69%2BF6c1z5aY4RCDG3A1h9JgHlUEHXz8flMEF4N9DCRpxkWmmSfsgV1RyE0HQXs5tsHcuRZ3fWjF9P69o%2B%2BQ5stI6PqJvFvRwJneWAKfFT9jjr4bLR71GWcdWauiU%2B6E12EXv0iHlmM9oEm2rCyAUQ7nYWT4p3%2FPXIbrJsMc1H%2BJVpHTeg5%2FlW%2B7XZRq2rWB05pvHYc6o0qZ4YE6YRgfcFcEImsG5TnLZADZHSEnlDeU0vpdhv2FfZoaFavNorOYZeAllV5IvYQBmdm5FokgyDlmpQI67jYmnxnzFIirvIOYM0tZ2p896vlKsyBW0Dk7scCvAVJ7gZIl%2BxAgQvrqjWBZubjjDt%2BR66m5WTKlhAMM9aJOKZPMg7CUYBs9wOlqelqsJTEa7SZoYQx9e02xSktBQjIvapjzGQIEsELQjNViSubXuuifsvo2TFXE6W7U95%2FPunkWDD1ktS9BjqkAcGVigYiMWqy83kqOD4cRASGAdyvsCSoPINXtpyPqpLGRVYLj8vTwbZtNh%2BJI8yr6%2FZKOEPiMUcb13ICrO0YaJ171QxL42epV9hGMVey87f1xkCLGykq89vWxx%2BE88S29K2%2BY29d73U7z1KHOybT3RKPbyY9apNYMgmoFLhdZcVjKXI%2B7KOslswj50IDC%2FzTmY%2BqoAfBuH%2F8OxViJMnFq5do%2BQlp&X-Amz-Signature=5750cff307beb056098e38374885eb3b08e4454775082a50830ac3740b442417&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664DXTFGYN%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T232212Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG8aCXVzLXdlc3QtMiJIMEYCIQClmGTiB5hf2Y2j4gvuR6JqDTZrOG4jmQAGql2hBUgBiQIhAJ6SD1%2BAuLQkJc%2FWfelHdartZiio0g5TgR0nkHbworE%2BKogECJj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igz8ksTk2bWUclX%2BRKIq3AOKekOqvVE0Q7E5IT6nYOicr8%2F8gR6E4tLIfvJaNWnvHD8XTd6f7jOXs6gxHPoIi9kqilEs%2BUDCvHw%2FLjTekMRyqosgxozbUXjwLaIFztnLtw96Vc%2BalYOtkjmEuu%2BliCiW0xbJ9DuWWQPmcvvdOmzYI5s61kwxnTQu5u%2BeV24w6jz6qw1eMH69%2BF6c1z5aY4RCDG3A1h9JgHlUEHXz8flMEF4N9DCRpxkWmmSfsgV1RyE0HQXs5tsHcuRZ3fWjF9P69o%2B%2BQ5stI6PqJvFvRwJneWAKfFT9jjr4bLR71GWcdWauiU%2B6E12EXv0iHlmM9oEm2rCyAUQ7nYWT4p3%2FPXIbrJsMc1H%2BJVpHTeg5%2FlW%2B7XZRq2rWB05pvHYc6o0qZ4YE6YRgfcFcEImsG5TnLZADZHSEnlDeU0vpdhv2FfZoaFavNorOYZeAllV5IvYQBmdm5FokgyDlmpQI67jYmnxnzFIirvIOYM0tZ2p896vlKsyBW0Dk7scCvAVJ7gZIl%2BxAgQvrqjWBZubjjDt%2BR66m5WTKlhAMM9aJOKZPMg7CUYBs9wOlqelqsJTEa7SZoYQx9e02xSktBQjIvapjzGQIEsELQjNViSubXuuifsvo2TFXE6W7U95%2FPunkWDD1ktS9BjqkAcGVigYiMWqy83kqOD4cRASGAdyvsCSoPINXtpyPqpLGRVYLj8vTwbZtNh%2BJI8yr6%2FZKOEPiMUcb13ICrO0YaJ171QxL42epV9hGMVey87f1xkCLGykq89vWxx%2BE88S29K2%2BY29d73U7z1KHOybT3RKPbyY9apNYMgmoFLhdZcVjKXI%2B7KOslswj50IDC%2FzTmY%2BqoAfBuH%2F8OxViJMnFq5do%2BQlp&X-Amz-Signature=9c77cd3d92925a5e6862eff270f0d12903518494235b64066fcfe0a318583e66&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664DXTFGYN%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T232212Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG8aCXVzLXdlc3QtMiJIMEYCIQClmGTiB5hf2Y2j4gvuR6JqDTZrOG4jmQAGql2hBUgBiQIhAJ6SD1%2BAuLQkJc%2FWfelHdartZiio0g5TgR0nkHbworE%2BKogECJj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igz8ksTk2bWUclX%2BRKIq3AOKekOqvVE0Q7E5IT6nYOicr8%2F8gR6E4tLIfvJaNWnvHD8XTd6f7jOXs6gxHPoIi9kqilEs%2BUDCvHw%2FLjTekMRyqosgxozbUXjwLaIFztnLtw96Vc%2BalYOtkjmEuu%2BliCiW0xbJ9DuWWQPmcvvdOmzYI5s61kwxnTQu5u%2BeV24w6jz6qw1eMH69%2BF6c1z5aY4RCDG3A1h9JgHlUEHXz8flMEF4N9DCRpxkWmmSfsgV1RyE0HQXs5tsHcuRZ3fWjF9P69o%2B%2BQ5stI6PqJvFvRwJneWAKfFT9jjr4bLR71GWcdWauiU%2B6E12EXv0iHlmM9oEm2rCyAUQ7nYWT4p3%2FPXIbrJsMc1H%2BJVpHTeg5%2FlW%2B7XZRq2rWB05pvHYc6o0qZ4YE6YRgfcFcEImsG5TnLZADZHSEnlDeU0vpdhv2FfZoaFavNorOYZeAllV5IvYQBmdm5FokgyDlmpQI67jYmnxnzFIirvIOYM0tZ2p896vlKsyBW0Dk7scCvAVJ7gZIl%2BxAgQvrqjWBZubjjDt%2BR66m5WTKlhAMM9aJOKZPMg7CUYBs9wOlqelqsJTEa7SZoYQx9e02xSktBQjIvapjzGQIEsELQjNViSubXuuifsvo2TFXE6W7U95%2FPunkWDD1ktS9BjqkAcGVigYiMWqy83kqOD4cRASGAdyvsCSoPINXtpyPqpLGRVYLj8vTwbZtNh%2BJI8yr6%2FZKOEPiMUcb13ICrO0YaJ171QxL42epV9hGMVey87f1xkCLGykq89vWxx%2BE88S29K2%2BY29d73U7z1KHOybT3RKPbyY9apNYMgmoFLhdZcVjKXI%2B7KOslswj50IDC%2FzTmY%2BqoAfBuH%2F8OxViJMnFq5do%2BQlp&X-Amz-Signature=3b496f3f28b3b653745beba96bf96ab143ac44121973dff3afb2a3637c023a71&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664LPQZXFG%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T232213Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG8aCXVzLXdlc3QtMiJGMEQCIEkZOgUifgK8WYWF8XE1ShaQklZHFV4p0PzM9VCozq6NAiBd6goRpfCw4MtjUp5uULy50FTmliieKP47F7ym9CSpuyqIBAiX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMFFZkiXoMOhWM0H5QKtwDK79lNYnmUswbGtdS5ZvZSUGxp4AcbkxniMY7OljyMjMZLADLGRc7YJJkg1k8Je0Mu17ux%2F2fphN0JdiIMu3jqk0Jq1u5vKR6x9up%2BmF68uRlugNjuhCAwEUq3BY7svuhNTHMIiTzwORvG9OPoq6fM210pS13x9BYQP%2FyDTSflu%2BnX9QjPMIGZl0Rhfga4xIP8Z30NDNDh8PXprG1FBahaoH4DPKIdkq8eZU3Tb%2B84bEfNJm3GZ7nJUpw9wXTzB8BsEo1uvr%2BdnfnuXHevhc7p5agvoZ8TmCqB54qR4p0Nt3CrIB3VAP2O2%2Fmp0YiFM59XRF%2Bbt8Xym560uEdABU7og6%2F3aAYhIPdxBXvmNVo6QBt2GhMNhkcp7zajToJZ1KRxzPbM1MpZ1Ov9g9VDr2xKUDBGfyinGvoDlzsT1TBFGHXViJwMIrQynHZfy8GNebxY9FRo1hbYnDQ7bt3wpoSBl6x%2FFtvgcQN3%2Fqmg736J4OMtC5NO4VQMsZC%2BB5dUE6rSUfd0YXnYLhm%2FZl4RfeIm5vam3Bke%2BtArCXmTKVh0TJTPPn1kzsXAUqRSJYaFRMHULkAAiYY6bZCV7vy5kYNrBQ1crUCPa1l2Idy2UVMTVUteIfkM6C%2FiD8%2B3%2FcwoZPUvQY6pgEPUItcF7TJ0yS%2BEvt%2BBicGzg5MnB5N%2Fp7RG4t%2Fj4zatg1dVrUElcEjSqcyKncMIPW%2F%2BBlVangv0ineMhBCDJZaZxY9pVBRmd7gmxuQXzjRSQDUsKEBoZJ4XBx32VjBGnFpvKse813%2BD56UCvtKFGCYw1eEkkPl4T0JWGmRYxdRA7aMZ4N8RySu2lRr%2BgiWEUYSmvX55Mm8EK1LbJGYUG%2FDM%2BxS43ep&X-Amz-Signature=f7170eeaf5ddbc4ee6788f4504b6fd261e77e63bdf29ba8e2c2fd2bbb0ac604f&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ULHKP25T%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T232215Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG8aCXVzLXdlc3QtMiJHMEUCIQCODe0jA5xgyOLhVBAU6fJgohGBY4IoiOPxJ6ChFd4%2F%2BgIgHPBHanKTOlMAo%2FKaPL1Kr5WEM7xiHuEMa805UVl5w4sqiAQImP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOj68mFpPHmL%2BKDQuSrcA9MCcOxZwJjf%2BbKi9KkdFHlnWJQiY%2FKR%2F1iMeQqwF9DUSb3ppxxbTWN3CXujg5LabUARSCu87X94k0Tp1g4J89ZT0EHG1GII%2FrUqMQ9HzuOaJlubpuPtJNeCgphIMTaG2d8VUwO7MRepaYIUx2t1cVmD02yEw4ieMhlA51rN%2Bw2Nq7I6iQRf9yXJD0oXgibUP3DL%2Bfd1Yqqq%2Bht2cfqlRpbdvn4SgNN0dCXbwCRF0NI0sEp%2B%2Bn6DaUxkshKoYBAPtNJP2%2Bv566ZwH72Nch4deNkSx0ZpXx6T13rolwHYYJp9kMyMMu0OLQOUzVxhcmyerOxqggv3RTvbL7vcwLwtqFIm8perPeOH00DE8KDAckCbmmKOcp6fHWixd5hjQ%2Fvm%2F35Fz8wMPVR6tyxYjKbOKHALKCT04V5Gt8K6G1PXnFVNeT8lpLz5zkL5GuRxgKS1xjdxfWV%2FVVERqPwf7esGMSkD5RVo%2Bcg8xhMbH%2BG8ougUoQEOTlj%2FQtgqFHob5mNI8Q5NJKcnJGtcJtATPGjNRfIesfynu%2BHrXQ0AgR6W1ZZ962nIO%2BwhXuvAytJkDEfRC4tuLltwPsTiLKLvB%2B0nTO7yM7Q9kQv44KXwlitZago%2F0dNxeNwa%2BKAiBIUCMPGS1L0GOqUBJEevrQJHOsLOqaZlS5ZY6an%2BklhBuMl1TMeD%2BdYXr74stY1w4V0bpeh2yRGY0s6wsg9LxGl%2F2OgmAk2CoKFFaHLTZ2go1KUdC9hly9mGifwK%2BYf1aW5iYHPibR%2BsAVHdMB6N7yb7ScSoInlphF6LID38AtJnptK88y8N9Q3gLPiPOKm4qrnOTYcI03rKM9CXsI5PkM4FowP3u89rgPQ%2BrgCzlJ2g&X-Amz-Signature=40492a36f4958f84b3e461a2b106ac188cebce549104b146e66e91825ffcf3c9&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664DXTFGYN%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T232212Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG8aCXVzLXdlc3QtMiJIMEYCIQClmGTiB5hf2Y2j4gvuR6JqDTZrOG4jmQAGql2hBUgBiQIhAJ6SD1%2BAuLQkJc%2FWfelHdartZiio0g5TgR0nkHbworE%2BKogECJj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igz8ksTk2bWUclX%2BRKIq3AOKekOqvVE0Q7E5IT6nYOicr8%2F8gR6E4tLIfvJaNWnvHD8XTd6f7jOXs6gxHPoIi9kqilEs%2BUDCvHw%2FLjTekMRyqosgxozbUXjwLaIFztnLtw96Vc%2BalYOtkjmEuu%2BliCiW0xbJ9DuWWQPmcvvdOmzYI5s61kwxnTQu5u%2BeV24w6jz6qw1eMH69%2BF6c1z5aY4RCDG3A1h9JgHlUEHXz8flMEF4N9DCRpxkWmmSfsgV1RyE0HQXs5tsHcuRZ3fWjF9P69o%2B%2BQ5stI6PqJvFvRwJneWAKfFT9jjr4bLR71GWcdWauiU%2B6E12EXv0iHlmM9oEm2rCyAUQ7nYWT4p3%2FPXIbrJsMc1H%2BJVpHTeg5%2FlW%2B7XZRq2rWB05pvHYc6o0qZ4YE6YRgfcFcEImsG5TnLZADZHSEnlDeU0vpdhv2FfZoaFavNorOYZeAllV5IvYQBmdm5FokgyDlmpQI67jYmnxnzFIirvIOYM0tZ2p896vlKsyBW0Dk7scCvAVJ7gZIl%2BxAgQvrqjWBZubjjDt%2BR66m5WTKlhAMM9aJOKZPMg7CUYBs9wOlqelqsJTEa7SZoYQx9e02xSktBQjIvapjzGQIEsELQjNViSubXuuifsvo2TFXE6W7U95%2FPunkWDD1ktS9BjqkAcGVigYiMWqy83kqOD4cRASGAdyvsCSoPINXtpyPqpLGRVYLj8vTwbZtNh%2BJI8yr6%2FZKOEPiMUcb13ICrO0YaJ171QxL42epV9hGMVey87f1xkCLGykq89vWxx%2BE88S29K2%2BY29d73U7z1KHOybT3RKPbyY9apNYMgmoFLhdZcVjKXI%2B7KOslswj50IDC%2FzTmY%2BqoAfBuH%2F8OxViJMnFq5do%2BQlp&X-Amz-Signature=bf612d389740ccee39afa7b2a80f4b40a946e9f7a20d351e0bbd209cd3e4124f&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664DXTFGYN%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T232212Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG8aCXVzLXdlc3QtMiJIMEYCIQClmGTiB5hf2Y2j4gvuR6JqDTZrOG4jmQAGql2hBUgBiQIhAJ6SD1%2BAuLQkJc%2FWfelHdartZiio0g5TgR0nkHbworE%2BKogECJj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igz8ksTk2bWUclX%2BRKIq3AOKekOqvVE0Q7E5IT6nYOicr8%2F8gR6E4tLIfvJaNWnvHD8XTd6f7jOXs6gxHPoIi9kqilEs%2BUDCvHw%2FLjTekMRyqosgxozbUXjwLaIFztnLtw96Vc%2BalYOtkjmEuu%2BliCiW0xbJ9DuWWQPmcvvdOmzYI5s61kwxnTQu5u%2BeV24w6jz6qw1eMH69%2BF6c1z5aY4RCDG3A1h9JgHlUEHXz8flMEF4N9DCRpxkWmmSfsgV1RyE0HQXs5tsHcuRZ3fWjF9P69o%2B%2BQ5stI6PqJvFvRwJneWAKfFT9jjr4bLR71GWcdWauiU%2B6E12EXv0iHlmM9oEm2rCyAUQ7nYWT4p3%2FPXIbrJsMc1H%2BJVpHTeg5%2FlW%2B7XZRq2rWB05pvHYc6o0qZ4YE6YRgfcFcEImsG5TnLZADZHSEnlDeU0vpdhv2FfZoaFavNorOYZeAllV5IvYQBmdm5FokgyDlmpQI67jYmnxnzFIirvIOYM0tZ2p896vlKsyBW0Dk7scCvAVJ7gZIl%2BxAgQvrqjWBZubjjDt%2BR66m5WTKlhAMM9aJOKZPMg7CUYBs9wOlqelqsJTEa7SZoYQx9e02xSktBQjIvapjzGQIEsELQjNViSubXuuifsvo2TFXE6W7U95%2FPunkWDD1ktS9BjqkAcGVigYiMWqy83kqOD4cRASGAdyvsCSoPINXtpyPqpLGRVYLj8vTwbZtNh%2BJI8yr6%2FZKOEPiMUcb13ICrO0YaJ171QxL42epV9hGMVey87f1xkCLGykq89vWxx%2BE88S29K2%2BY29d73U7z1KHOybT3RKPbyY9apNYMgmoFLhdZcVjKXI%2B7KOslswj50IDC%2FzTmY%2BqoAfBuH%2F8OxViJMnFq5do%2BQlp&X-Amz-Signature=3afd1f8c940c5a2a22b2c5981fc63bcc1006af4aa9399db216b26944de28b9b2&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664DXTFGYN%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T232212Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG8aCXVzLXdlc3QtMiJIMEYCIQClmGTiB5hf2Y2j4gvuR6JqDTZrOG4jmQAGql2hBUgBiQIhAJ6SD1%2BAuLQkJc%2FWfelHdartZiio0g5TgR0nkHbworE%2BKogECJj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igz8ksTk2bWUclX%2BRKIq3AOKekOqvVE0Q7E5IT6nYOicr8%2F8gR6E4tLIfvJaNWnvHD8XTd6f7jOXs6gxHPoIi9kqilEs%2BUDCvHw%2FLjTekMRyqosgxozbUXjwLaIFztnLtw96Vc%2BalYOtkjmEuu%2BliCiW0xbJ9DuWWQPmcvvdOmzYI5s61kwxnTQu5u%2BeV24w6jz6qw1eMH69%2BF6c1z5aY4RCDG3A1h9JgHlUEHXz8flMEF4N9DCRpxkWmmSfsgV1RyE0HQXs5tsHcuRZ3fWjF9P69o%2B%2BQ5stI6PqJvFvRwJneWAKfFT9jjr4bLR71GWcdWauiU%2B6E12EXv0iHlmM9oEm2rCyAUQ7nYWT4p3%2FPXIbrJsMc1H%2BJVpHTeg5%2FlW%2B7XZRq2rWB05pvHYc6o0qZ4YE6YRgfcFcEImsG5TnLZADZHSEnlDeU0vpdhv2FfZoaFavNorOYZeAllV5IvYQBmdm5FokgyDlmpQI67jYmnxnzFIirvIOYM0tZ2p896vlKsyBW0Dk7scCvAVJ7gZIl%2BxAgQvrqjWBZubjjDt%2BR66m5WTKlhAMM9aJOKZPMg7CUYBs9wOlqelqsJTEa7SZoYQx9e02xSktBQjIvapjzGQIEsELQjNViSubXuuifsvo2TFXE6W7U95%2FPunkWDD1ktS9BjqkAcGVigYiMWqy83kqOD4cRASGAdyvsCSoPINXtpyPqpLGRVYLj8vTwbZtNh%2BJI8yr6%2FZKOEPiMUcb13ICrO0YaJ171QxL42epV9hGMVey87f1xkCLGykq89vWxx%2BE88S29K2%2BY29d73U7z1KHOybT3RKPbyY9apNYMgmoFLhdZcVjKXI%2B7KOslswj50IDC%2FzTmY%2BqoAfBuH%2F8OxViJMnFq5do%2BQlp&X-Amz-Signature=110b0e1db58251a032c1605cea37541cdbcc25140a717a1825a3aa8685a41470&X-Amz-SignedHeaders=host&x-id=GetObject)


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

