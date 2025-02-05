---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4662C7G5JKB%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250205T021318Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjECAaCXVzLXdlc3QtMiJIMEYCIQCo80%2BTj2f1OSWAY8oEShtlkMDMsNrZh8P1jy3os0dcKAIhA\
  PAMH7O2pPkEOPg7jSCmww30i%2BVCPviXXcATYJJ1EhYQKv8DCDkQABoMNjM3NDIzMTgzODA1IgwU\
  G3ZMnEZhuT5MCvQq3APmJb2wApEnJnE6wdTlz37bdkuxkTcRcAbhfBoLXv5DakGwgIiaBlZ2AV3iB\
  kvNwyBj6lX6IYYyq6HpEFsznK40YMguTWIhmsmLg762maYiECkbN8gxPB8bxnMOlp8qBUbDnMTUqH\
  Lahnsy7Az1QhXNlPHlX2fIAli9U12SU8l%2F5knmM3ekU%2Bxaum35CFHBzkzQiT1Zp9rP8Sqr22d\
  0YTikD7PFAdN8VDpBQMK9igAEaJxUIfIo2ALPnFGklV2r2uOX%2Fz9jBMV9Kww2VMCTmfe1LQ86Ty\
  OunfZfT6CToqVokM4uZvPQz0xNXIGzdq9BCfbyeMymNFrhXJ%2Ff4TW4Q9z6HPiiD6zrDE2SSGIkF\
  ljRXSsh6L2aSYCoOvvQJ1uADoo6Gkd%2FT6sJ9S8DmqlEgv89YXSU3jYMWQnhjyGAxNmUj6pT7aoO\
  2KDXoyEFI33RxL834%2FQTlgAwcGlv8KnA0Vpf2BQIkpi%2FzFSsME8D1bcPilmJYbKQ4WBZlgaA2\
  wDP%2F8KTz3S3TdUu%2F7VQewxtw9pWePfDNFu0Gp%2FbvpeOlzWxiaE19bVP1JxpcZxp4NIirUpI\
  VEOdznrcc76nFgZtWg7YZ7IQYj9QR2XBatwwtuRGOt%2FmWhQmGCD3XUTYhTCfz4q9BjqkAWKsJnR\
  e5tr5EmFVxkO98I3alyLVh67Wo%2BbakBykEKBrS%2Fga72gva3C%2BPbuZpUd9FAZNqTJTv%2Bfa\
  zSZZUxkURILf5XMS%2FVw%2BC5qwo27nPRczBKtf5XOS7gLA3k%2FzPkkQezLYi4A%2F0ygmBWm3V\
  tgbSRx%2Fdb8VqV6%2FWo8DPa10jk%2BBcr1xbzgFKdsRDUBd7StWK4K9RUNXnI5KhIpohQXQiNto\
  oxr6&X-Amz-Signature=3235abb5393880bf16bcb5a46535c738a95683759868eb33bae399e6\
  e76ea65e&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466W2R2NQ64%2F20250205%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250205T021150Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJGMEQCIDX8Lk52qc8EWp3A5yoAfLxnEyaDffd\
        dmOMeQ8NENE5oAiA4vb5oA9%2BVudNSalZ8e2KGC%2FWzAPlPmhzsAn5SyVLfvCr%2FAwg5\
        EAAaDDYzNzQyMzE4MzgwNSIM8LcCWY%2F0Un83mOIJKtwDYV0qdZDVlITrZGqD%2BJcWkaR\
        m378JG86nce8OHqsYBSENlh0zdKSLP4JLgf5o97Ky9iDQl8xGwqGgi3Ycn0QuECuMnzQ76T\
        Fv3ReiZ1SjlWQt2cAgYLhmybWS7u9dnc40LovDG562Zxjlkmx637GB8lZAnb0nrwXIHHXWp\
        ZOFabYMlKKUEdECOOCFEXfeWcYTd2CoTOh8H4Xvqzd2E7XX73M%2BkYg8IbdxziEPC2FCuQ\
        cjquNmtUjxwq3XxYEdxpIS%2F7UVkdAW7YF6U6i1PzyTZtVEcDI4a6Ur0zXb48RyOpk3RtH\
        OMbrf%2FsLDoawbLyrzNBCBi42xCut%2F5eSn%2F0QJnoIsFFdPWJ6iqEq%2BZ5wvn8yhP2\
        8tyJCjf484LRjG3%2FfXnZWKfYcgD4p4Kh3d5fS%2Bw3JFuMgEyee4cSJOKFcZ1VWOsrd4C\
        A9Y0J%2FlTmojQX8Xf8nGo9NP1S9HZprUWPIdnTf2np23A34EKp0IxhXrYyrD6H8hmAuFiB\
        0BYTr2m2R587Np0ujLlgZZkX3kufESQ7rMyAodQ8AgehynDQ8Cfb5Fb8M3NxDUSApjqZa6B\
        Srp4kYDA%2BPIyDJExQ%2F3sr73dXa6Jf0cS1ONLb%2FTFGn9ZMhIB9WcUtFeZGh6hD8ws8\
        %2BKvQY6pgGn%2B%2FcLGkQV159QbT76h21OU%2BQaIoAYxiysqxQRrQD4iBUfzzuQZqGnJ\
        NMzx%2BsXOKr97s8nD0hiOG3FFI9JTFTsJAkfRPEBVQxc%2BB0XiYXgsraIPtRn8urZ%2Bd\
        qQbCMcLG%2FA1Cg3qcX5mk63B0iMjRW%2Bh7xc%2B71tH4P6pk3JwlDu01X5EenCEyKzF1d\
        zReW%2FNI9CWVt0NBYhDBC0vJVhBhCxgL3CODyG&X-Amz-Signature=3b915436503c4c5\
        5863c3651689c31052a4477a4d287af06d7cf3082ccac103a&X-Amz-SignedHeaders=h\
        ost&x-id=GetObject"
      expiry_time: "2025-02-05T03:11:50.293Z"
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
UPDATE_TIME: "2025-02-05T02:13:24.227Z"
EXPIRY_TIME: "2025-02-05T03:13:15.451Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TQ2CQKEJ%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T021316Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJIMEYCIQDr3C9n4gH8PxArLMFMSOuoQFJ8%2BrdnoS%2F2pEjnjQG7KQIhAPOcl7qE9U%2F2jNA85eQfFjpfvFCCG5Eaq2hNEWlLxMhcKv8DCDkQABoMNjM3NDIzMTgzODA1Igwsx8r7yNwq94e5NYEq3APPhevMqrOJojHfWbRflRWnI33fkGFJAhgtiqAzcE7pr7rIxvP5Dd7LT36eVRsBWGTY4V5raUGrAjfcLr6NaMyunNcWWx6E0zICVBSDNZ7oyDLa6aZ0MIB3h3jy1OBePVRZ6TLj4XJvhZfFKWLMb9iH1jCgzv2eS9qekqancT%2F%2FsgZZMXyag3C0Vs25nUmsQydFk54KBQC9wYFOMvPQODpKj95tBQ3%2FQkt%2FQQWnlyTKXOl3WDUv2HMMgJmlpHx8vyZVVdKODWriAcL74ZmM06NLfAuMAFN1hgVe2hkUWqgDwfAt7ln%2BUa%2BNgWIyahOm9qqp7WHrzqHGq7FzbYnN2y4mnvcV3d8pE3HblghFglmNCwvxbg0ffxovIFSFzQCGOR6R26Pas%2F4PEoPl2QRVZLOxAV95bUC%2FjEd5R99FB92qXbGCtcQm6fT1%2FXplr2q2VNDggbX%2FhxKCM9RCJXp%2BnIJ%2BsV0MDOQxMeooXPDFkB%2F0JVHWcTkhC0ZYGZlipcTG4Bc4%2F48EmqQxzNFZwRvbJ9t%2FK%2BOgUrQ0y99RN%2FCqAkSDBM23LTteo6G3wW68qPEmnKXeGhllEq60fYz1kTheo8k6zqvqhH%2FHg35jVB1AVt91ynM8D3eXHrnqceFFQDDUz4q9BjqkAZUQeQa%2FQADYhfwQg3RYVmNVbKFTUMZo5HKcQzXLt09f1yaVP8TwlhB%2B%2B%2FZfaWshOZD9HlmXmYTJL8YncsuZ3PX0hNqiur3orbzJ2Tl4b0GIkFnBU5rx34C92XwoGBOjf0URRjr1k%2FCwI8eSheNOIPOraFPEhTqe%2BUndH8890mp%2FoDG%2B%2FBNRU8UM%2FOy4MaBe65EMwbjSzcLGsY5KggThRKpOx7bp&X-Amz-Signature=280707ce1109aec04e7209fee388972fd50aa6ea630c65904b769da606573251&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TQ2CQKEJ%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T021316Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJIMEYCIQDr3C9n4gH8PxArLMFMSOuoQFJ8%2BrdnoS%2F2pEjnjQG7KQIhAPOcl7qE9U%2F2jNA85eQfFjpfvFCCG5Eaq2hNEWlLxMhcKv8DCDkQABoMNjM3NDIzMTgzODA1Igwsx8r7yNwq94e5NYEq3APPhevMqrOJojHfWbRflRWnI33fkGFJAhgtiqAzcE7pr7rIxvP5Dd7LT36eVRsBWGTY4V5raUGrAjfcLr6NaMyunNcWWx6E0zICVBSDNZ7oyDLa6aZ0MIB3h3jy1OBePVRZ6TLj4XJvhZfFKWLMb9iH1jCgzv2eS9qekqancT%2F%2FsgZZMXyag3C0Vs25nUmsQydFk54KBQC9wYFOMvPQODpKj95tBQ3%2FQkt%2FQQWnlyTKXOl3WDUv2HMMgJmlpHx8vyZVVdKODWriAcL74ZmM06NLfAuMAFN1hgVe2hkUWqgDwfAt7ln%2BUa%2BNgWIyahOm9qqp7WHrzqHGq7FzbYnN2y4mnvcV3d8pE3HblghFglmNCwvxbg0ffxovIFSFzQCGOR6R26Pas%2F4PEoPl2QRVZLOxAV95bUC%2FjEd5R99FB92qXbGCtcQm6fT1%2FXplr2q2VNDggbX%2FhxKCM9RCJXp%2BnIJ%2BsV0MDOQxMeooXPDFkB%2F0JVHWcTkhC0ZYGZlipcTG4Bc4%2F48EmqQxzNFZwRvbJ9t%2FK%2BOgUrQ0y99RN%2FCqAkSDBM23LTteo6G3wW68qPEmnKXeGhllEq60fYz1kTheo8k6zqvqhH%2FHg35jVB1AVt91ynM8D3eXHrnqceFFQDDUz4q9BjqkAZUQeQa%2FQADYhfwQg3RYVmNVbKFTUMZo5HKcQzXLt09f1yaVP8TwlhB%2B%2B%2FZfaWshOZD9HlmXmYTJL8YncsuZ3PX0hNqiur3orbzJ2Tl4b0GIkFnBU5rx34C92XwoGBOjf0URRjr1k%2FCwI8eSheNOIPOraFPEhTqe%2BUndH8890mp%2FoDG%2B%2FBNRU8UM%2FOy4MaBe65EMwbjSzcLGsY5KggThRKpOx7bp&X-Amz-Signature=de72c030c06bbcb505530e39d6d715874b1fd56662bf08da723f9f17cd87ab4d&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TQ2CQKEJ%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T021316Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJIMEYCIQDr3C9n4gH8PxArLMFMSOuoQFJ8%2BrdnoS%2F2pEjnjQG7KQIhAPOcl7qE9U%2F2jNA85eQfFjpfvFCCG5Eaq2hNEWlLxMhcKv8DCDkQABoMNjM3NDIzMTgzODA1Igwsx8r7yNwq94e5NYEq3APPhevMqrOJojHfWbRflRWnI33fkGFJAhgtiqAzcE7pr7rIxvP5Dd7LT36eVRsBWGTY4V5raUGrAjfcLr6NaMyunNcWWx6E0zICVBSDNZ7oyDLa6aZ0MIB3h3jy1OBePVRZ6TLj4XJvhZfFKWLMb9iH1jCgzv2eS9qekqancT%2F%2FsgZZMXyag3C0Vs25nUmsQydFk54KBQC9wYFOMvPQODpKj95tBQ3%2FQkt%2FQQWnlyTKXOl3WDUv2HMMgJmlpHx8vyZVVdKODWriAcL74ZmM06NLfAuMAFN1hgVe2hkUWqgDwfAt7ln%2BUa%2BNgWIyahOm9qqp7WHrzqHGq7FzbYnN2y4mnvcV3d8pE3HblghFglmNCwvxbg0ffxovIFSFzQCGOR6R26Pas%2F4PEoPl2QRVZLOxAV95bUC%2FjEd5R99FB92qXbGCtcQm6fT1%2FXplr2q2VNDggbX%2FhxKCM9RCJXp%2BnIJ%2BsV0MDOQxMeooXPDFkB%2F0JVHWcTkhC0ZYGZlipcTG4Bc4%2F48EmqQxzNFZwRvbJ9t%2FK%2BOgUrQ0y99RN%2FCqAkSDBM23LTteo6G3wW68qPEmnKXeGhllEq60fYz1kTheo8k6zqvqhH%2FHg35jVB1AVt91ynM8D3eXHrnqceFFQDDUz4q9BjqkAZUQeQa%2FQADYhfwQg3RYVmNVbKFTUMZo5HKcQzXLt09f1yaVP8TwlhB%2B%2B%2FZfaWshOZD9HlmXmYTJL8YncsuZ3PX0hNqiur3orbzJ2Tl4b0GIkFnBU5rx34C92XwoGBOjf0URRjr1k%2FCwI8eSheNOIPOraFPEhTqe%2BUndH8890mp%2FoDG%2B%2FBNRU8UM%2FOy4MaBe65EMwbjSzcLGsY5KggThRKpOx7bp&X-Amz-Signature=a79fac874145a6536bff60bbcdba2b900abd306e05194f243225f45f2f13b7ca&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TQ2CQKEJ%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T021316Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJIMEYCIQDr3C9n4gH8PxArLMFMSOuoQFJ8%2BrdnoS%2F2pEjnjQG7KQIhAPOcl7qE9U%2F2jNA85eQfFjpfvFCCG5Eaq2hNEWlLxMhcKv8DCDkQABoMNjM3NDIzMTgzODA1Igwsx8r7yNwq94e5NYEq3APPhevMqrOJojHfWbRflRWnI33fkGFJAhgtiqAzcE7pr7rIxvP5Dd7LT36eVRsBWGTY4V5raUGrAjfcLr6NaMyunNcWWx6E0zICVBSDNZ7oyDLa6aZ0MIB3h3jy1OBePVRZ6TLj4XJvhZfFKWLMb9iH1jCgzv2eS9qekqancT%2F%2FsgZZMXyag3C0Vs25nUmsQydFk54KBQC9wYFOMvPQODpKj95tBQ3%2FQkt%2FQQWnlyTKXOl3WDUv2HMMgJmlpHx8vyZVVdKODWriAcL74ZmM06NLfAuMAFN1hgVe2hkUWqgDwfAt7ln%2BUa%2BNgWIyahOm9qqp7WHrzqHGq7FzbYnN2y4mnvcV3d8pE3HblghFglmNCwvxbg0ffxovIFSFzQCGOR6R26Pas%2F4PEoPl2QRVZLOxAV95bUC%2FjEd5R99FB92qXbGCtcQm6fT1%2FXplr2q2VNDggbX%2FhxKCM9RCJXp%2BnIJ%2BsV0MDOQxMeooXPDFkB%2F0JVHWcTkhC0ZYGZlipcTG4Bc4%2F48EmqQxzNFZwRvbJ9t%2FK%2BOgUrQ0y99RN%2FCqAkSDBM23LTteo6G3wW68qPEmnKXeGhllEq60fYz1kTheo8k6zqvqhH%2FHg35jVB1AVt91ynM8D3eXHrnqceFFQDDUz4q9BjqkAZUQeQa%2FQADYhfwQg3RYVmNVbKFTUMZo5HKcQzXLt09f1yaVP8TwlhB%2B%2B%2FZfaWshOZD9HlmXmYTJL8YncsuZ3PX0hNqiur3orbzJ2Tl4b0GIkFnBU5rx34C92XwoGBOjf0URRjr1k%2FCwI8eSheNOIPOraFPEhTqe%2BUndH8890mp%2FoDG%2B%2FBNRU8UM%2FOy4MaBe65EMwbjSzcLGsY5KggThRKpOx7bp&X-Amz-Signature=64899219712b2d86aa3cf94076db36a5f81338a5aedb6b84c3d37adb4383fd70&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TQ2CQKEJ%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T021316Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJIMEYCIQDr3C9n4gH8PxArLMFMSOuoQFJ8%2BrdnoS%2F2pEjnjQG7KQIhAPOcl7qE9U%2F2jNA85eQfFjpfvFCCG5Eaq2hNEWlLxMhcKv8DCDkQABoMNjM3NDIzMTgzODA1Igwsx8r7yNwq94e5NYEq3APPhevMqrOJojHfWbRflRWnI33fkGFJAhgtiqAzcE7pr7rIxvP5Dd7LT36eVRsBWGTY4V5raUGrAjfcLr6NaMyunNcWWx6E0zICVBSDNZ7oyDLa6aZ0MIB3h3jy1OBePVRZ6TLj4XJvhZfFKWLMb9iH1jCgzv2eS9qekqancT%2F%2FsgZZMXyag3C0Vs25nUmsQydFk54KBQC9wYFOMvPQODpKj95tBQ3%2FQkt%2FQQWnlyTKXOl3WDUv2HMMgJmlpHx8vyZVVdKODWriAcL74ZmM06NLfAuMAFN1hgVe2hkUWqgDwfAt7ln%2BUa%2BNgWIyahOm9qqp7WHrzqHGq7FzbYnN2y4mnvcV3d8pE3HblghFglmNCwvxbg0ffxovIFSFzQCGOR6R26Pas%2F4PEoPl2QRVZLOxAV95bUC%2FjEd5R99FB92qXbGCtcQm6fT1%2FXplr2q2VNDggbX%2FhxKCM9RCJXp%2BnIJ%2BsV0MDOQxMeooXPDFkB%2F0JVHWcTkhC0ZYGZlipcTG4Bc4%2F48EmqQxzNFZwRvbJ9t%2FK%2BOgUrQ0y99RN%2FCqAkSDBM23LTteo6G3wW68qPEmnKXeGhllEq60fYz1kTheo8k6zqvqhH%2FHg35jVB1AVt91ynM8D3eXHrnqceFFQDDUz4q9BjqkAZUQeQa%2FQADYhfwQg3RYVmNVbKFTUMZo5HKcQzXLt09f1yaVP8TwlhB%2B%2B%2FZfaWshOZD9HlmXmYTJL8YncsuZ3PX0hNqiur3orbzJ2Tl4b0GIkFnBU5rx34C92XwoGBOjf0URRjr1k%2FCwI8eSheNOIPOraFPEhTqe%2BUndH8890mp%2FoDG%2B%2FBNRU8UM%2FOy4MaBe65EMwbjSzcLGsY5KggThRKpOx7bp&X-Amz-Signature=7628383bb0e4fae06a7f9fcaad7467f80a78651e605ae73e692bfa1416f0bc95&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZOABWLSY%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T021317Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJGMEQCIAmDO9Y5iJU03jXeEx0f9X40Ukl7wS0Wlmu6r2UOnn8FAiBAjV8QqO1E3axCgjThnE%2BOpZn7YHsW4us5dlCMTuBfOCr%2FAwg5EAAaDDYzNzQyMzE4MzgwNSIM99rlI92R02fOGx9SKtwDsxwaKYR%2FNK7oHDtaNhxsE8bnZaZLCifGWcfVlZN4x31FFilvA1D%2FLfxDAwzhdEMSDpzYA7jk9PPV4bJLfLPv1fOWwKNDamp6hVrIOeSSMCRxRCQwfbebxvUj6RehTwr%2BSnmhDrMQ0VHPc1sRRgE8LhRaUx4nexsfbai3EgZdf6rbbXZOuWepMZ5bUcDar5sFhf6Q0W3d%2FH%2B7icgRyqWd8zWaVb372u8I%2Fw9Jn1Uy22mfCAGwIHlEWOu12jIkbTyEqWcI29EmbGg9IkCFx015f%2FtrfJZ5lhEw1VBnfgo%2BDpE9ZXhRda1ox%2F57cWmHk5XRC%2FSQ0sN%2BGyVnzvF%2Bnfopn1ZA2iRMlVbYfMN5%2FGbOBxSwje7KbAppxIZgB%2BofJEJSwjryi9DJKzVa45SIZLsnjY29GshpgatAvzt6T9BcPrGNbOhbG4lK%2FbIYPwOn0FvnAv9K%2B6jYSgGMHl7diLIchd%2B6oxUxoF5RJP0ux%2BUHaC4WrTIXDbSEVQz%2FsAhZdVqwcF7ELdPiyLDZWMGeztUUst7j7pyQNPn3enl51hvcr%2FuDqu70St5gP4B13wcDJX835BaDfXQA7g5jcYR4WO%2B0xZ8tVJmdhOEz7R2gMQxAubdcFaMt%2F6f3qdek8vswmM%2BKvQY6pgE%2Flj4F2G4HzUC3zORFWfccTCkOdWacLedPjVuswDE4RaokeprbIaTy9CMyIj0cRMbbD0%2BhHyeERc7NBhq21D0QAQA1n9C8mgvYpLvPbF1wdRm1XEGXDEKDQzc8Mdqf5y84NFcC4LedqEFdb%2FWXFvhGVkbEX8iureEpMI7%2FevcKlN9T4AmV2aeXxiOw6SBTXj63CjwcklL4inLsU2JrfwJoG7L43L8%2F&X-Amz-Signature=ef8c742cce081688711e2ed7ca4f68727790b16b7bfe9e00bed14273848bf4fa&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WBGS5E6N%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T021318Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJHMEUCIQCm8DxdzoUoRVgFRrvPQ3qAxA7XWdVYq%2FRVKcQefmK%2FVQIgJ06p2woSivVvIHp6e1odbezk5JDKrixFHpgMGmdjgFwq%2FwMIORAAGgw2Mzc0MjMxODM4MDUiDEqrRIY6cpxV3XaV%2BSrcA8jhepjiF%2BR8JuxtpwFyXZnnjAXS53BoqRpSLL77s4ZEUELAv%2F5nI5%2BpDlfOWJFGzy4TbTxpgXHHtQ0IFI2%2B4ci6cCMksFKOX%2Bo%2FgpSDwXFgV1RsPDbFMq2vZlQpXJf%2BEkX%2B5i%2F51XMExgMFBsP25BhVW5ZAEtrY4tdRbcTs2XDeIqbY8OZQh898akBV8BE1gzaIqfeCTGf5IU9atyZhdtgJ6UNaEZHJPh1spdHkE5x%2FN4650Ig2U48F8SPL4%2FnaUnIMJFk7JGC1Per7Tcs5DuR2Hyyi0dWLtUnrUZaceCs%2BJLznf88AwL0p6hkG4zZ1fLqkVL7f6KpjlXrkDyKQHExJNB5C4eppx11QGRQdSe9iXffLN0byaHl8NzaYSUd5ngxI8Bt2%2Fkd4uyh3DwSrT%2FDNMQoDjx0yesrS9RogZnrVsPf7nysTrgPYNyroCWtNAtUdwmc3zkBxY1ZSoXGFC2V4LkPHsoTeA6%2B1b03erGFGTUY%2BKLox%2F17OdeRGKyKFWeLjGVlrZ0K9%2BWB7NHXhZL7MYCSTSgA%2B577ENRy%2FSCJ4ZTX6xX7B1%2FKxPgMSD5nFM6sqdXVe4NQBi7RN4pqbCzEtf05LG17uP4%2FOGNnQ%2F9ygepnm81sxJDkBYOf6MPfPir0GOqUBwxKcUW5tA%2FTEvxshGv%2FGPNa86efBGZZSK92pKQ5tJUE4zfHlDT79swA8w2e4M2%2BydqmTZZMYOcGi3svHdNsL6w6OT5uxM2tvjQIrA39AhVjKM%2FLcvVH4F5tUJz0SxZ2tAQ40uiI6Cs4AebyAfcTg2J%2Ffy34eI2VxYPmIVOzC0IZzkxfByPBISzU2POZ8iHFI0OwYAtl%2Fsu6Ou03GHfWLB0Ec0f9Y&X-Amz-Signature=121a2a30c33733baad159850c49b4f57436dd17274fc3c2f9dc5ac00edabcf09&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TQ2CQKEJ%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T021316Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJIMEYCIQDr3C9n4gH8PxArLMFMSOuoQFJ8%2BrdnoS%2F2pEjnjQG7KQIhAPOcl7qE9U%2F2jNA85eQfFjpfvFCCG5Eaq2hNEWlLxMhcKv8DCDkQABoMNjM3NDIzMTgzODA1Igwsx8r7yNwq94e5NYEq3APPhevMqrOJojHfWbRflRWnI33fkGFJAhgtiqAzcE7pr7rIxvP5Dd7LT36eVRsBWGTY4V5raUGrAjfcLr6NaMyunNcWWx6E0zICVBSDNZ7oyDLa6aZ0MIB3h3jy1OBePVRZ6TLj4XJvhZfFKWLMb9iH1jCgzv2eS9qekqancT%2F%2FsgZZMXyag3C0Vs25nUmsQydFk54KBQC9wYFOMvPQODpKj95tBQ3%2FQkt%2FQQWnlyTKXOl3WDUv2HMMgJmlpHx8vyZVVdKODWriAcL74ZmM06NLfAuMAFN1hgVe2hkUWqgDwfAt7ln%2BUa%2BNgWIyahOm9qqp7WHrzqHGq7FzbYnN2y4mnvcV3d8pE3HblghFglmNCwvxbg0ffxovIFSFzQCGOR6R26Pas%2F4PEoPl2QRVZLOxAV95bUC%2FjEd5R99FB92qXbGCtcQm6fT1%2FXplr2q2VNDggbX%2FhxKCM9RCJXp%2BnIJ%2BsV0MDOQxMeooXPDFkB%2F0JVHWcTkhC0ZYGZlipcTG4Bc4%2F48EmqQxzNFZwRvbJ9t%2FK%2BOgUrQ0y99RN%2FCqAkSDBM23LTteo6G3wW68qPEmnKXeGhllEq60fYz1kTheo8k6zqvqhH%2FHg35jVB1AVt91ynM8D3eXHrnqceFFQDDUz4q9BjqkAZUQeQa%2FQADYhfwQg3RYVmNVbKFTUMZo5HKcQzXLt09f1yaVP8TwlhB%2B%2B%2FZfaWshOZD9HlmXmYTJL8YncsuZ3PX0hNqiur3orbzJ2Tl4b0GIkFnBU5rx34C92XwoGBOjf0URRjr1k%2FCwI8eSheNOIPOraFPEhTqe%2BUndH8890mp%2FoDG%2B%2FBNRU8UM%2FOy4MaBe65EMwbjSzcLGsY5KggThRKpOx7bp&X-Amz-Signature=fea76b3d6d126b723571b4b67052bf6f9c17ca005b85c52179a905bed5088ff7&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TQ2CQKEJ%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T021316Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJIMEYCIQDr3C9n4gH8PxArLMFMSOuoQFJ8%2BrdnoS%2F2pEjnjQG7KQIhAPOcl7qE9U%2F2jNA85eQfFjpfvFCCG5Eaq2hNEWlLxMhcKv8DCDkQABoMNjM3NDIzMTgzODA1Igwsx8r7yNwq94e5NYEq3APPhevMqrOJojHfWbRflRWnI33fkGFJAhgtiqAzcE7pr7rIxvP5Dd7LT36eVRsBWGTY4V5raUGrAjfcLr6NaMyunNcWWx6E0zICVBSDNZ7oyDLa6aZ0MIB3h3jy1OBePVRZ6TLj4XJvhZfFKWLMb9iH1jCgzv2eS9qekqancT%2F%2FsgZZMXyag3C0Vs25nUmsQydFk54KBQC9wYFOMvPQODpKj95tBQ3%2FQkt%2FQQWnlyTKXOl3WDUv2HMMgJmlpHx8vyZVVdKODWriAcL74ZmM06NLfAuMAFN1hgVe2hkUWqgDwfAt7ln%2BUa%2BNgWIyahOm9qqp7WHrzqHGq7FzbYnN2y4mnvcV3d8pE3HblghFglmNCwvxbg0ffxovIFSFzQCGOR6R26Pas%2F4PEoPl2QRVZLOxAV95bUC%2FjEd5R99FB92qXbGCtcQm6fT1%2FXplr2q2VNDggbX%2FhxKCM9RCJXp%2BnIJ%2BsV0MDOQxMeooXPDFkB%2F0JVHWcTkhC0ZYGZlipcTG4Bc4%2F48EmqQxzNFZwRvbJ9t%2FK%2BOgUrQ0y99RN%2FCqAkSDBM23LTteo6G3wW68qPEmnKXeGhllEq60fYz1kTheo8k6zqvqhH%2FHg35jVB1AVt91ynM8D3eXHrnqceFFQDDUz4q9BjqkAZUQeQa%2FQADYhfwQg3RYVmNVbKFTUMZo5HKcQzXLt09f1yaVP8TwlhB%2B%2B%2FZfaWshOZD9HlmXmYTJL8YncsuZ3PX0hNqiur3orbzJ2Tl4b0GIkFnBU5rx34C92XwoGBOjf0URRjr1k%2FCwI8eSheNOIPOraFPEhTqe%2BUndH8890mp%2FoDG%2B%2FBNRU8UM%2FOy4MaBe65EMwbjSzcLGsY5KggThRKpOx7bp&X-Amz-Signature=238e29b5a4f56249554129311f48543be9763faaf3def0edc432eb8cd9767bba&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TQ2CQKEJ%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T021316Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJIMEYCIQDr3C9n4gH8PxArLMFMSOuoQFJ8%2BrdnoS%2F2pEjnjQG7KQIhAPOcl7qE9U%2F2jNA85eQfFjpfvFCCG5Eaq2hNEWlLxMhcKv8DCDkQABoMNjM3NDIzMTgzODA1Igwsx8r7yNwq94e5NYEq3APPhevMqrOJojHfWbRflRWnI33fkGFJAhgtiqAzcE7pr7rIxvP5Dd7LT36eVRsBWGTY4V5raUGrAjfcLr6NaMyunNcWWx6E0zICVBSDNZ7oyDLa6aZ0MIB3h3jy1OBePVRZ6TLj4XJvhZfFKWLMb9iH1jCgzv2eS9qekqancT%2F%2FsgZZMXyag3C0Vs25nUmsQydFk54KBQC9wYFOMvPQODpKj95tBQ3%2FQkt%2FQQWnlyTKXOl3WDUv2HMMgJmlpHx8vyZVVdKODWriAcL74ZmM06NLfAuMAFN1hgVe2hkUWqgDwfAt7ln%2BUa%2BNgWIyahOm9qqp7WHrzqHGq7FzbYnN2y4mnvcV3d8pE3HblghFglmNCwvxbg0ffxovIFSFzQCGOR6R26Pas%2F4PEoPl2QRVZLOxAV95bUC%2FjEd5R99FB92qXbGCtcQm6fT1%2FXplr2q2VNDggbX%2FhxKCM9RCJXp%2BnIJ%2BsV0MDOQxMeooXPDFkB%2F0JVHWcTkhC0ZYGZlipcTG4Bc4%2F48EmqQxzNFZwRvbJ9t%2FK%2BOgUrQ0y99RN%2FCqAkSDBM23LTteo6G3wW68qPEmnKXeGhllEq60fYz1kTheo8k6zqvqhH%2FHg35jVB1AVt91ynM8D3eXHrnqceFFQDDUz4q9BjqkAZUQeQa%2FQADYhfwQg3RYVmNVbKFTUMZo5HKcQzXLt09f1yaVP8TwlhB%2B%2B%2FZfaWshOZD9HlmXmYTJL8YncsuZ3PX0hNqiur3orbzJ2Tl4b0GIkFnBU5rx34C92XwoGBOjf0URRjr1k%2FCwI8eSheNOIPOraFPEhTqe%2BUndH8890mp%2FoDG%2B%2FBNRU8UM%2FOy4MaBe65EMwbjSzcLGsY5KggThRKpOx7bp&X-Amz-Signature=5419e54ac118a2e60baa619518245926da5dc8f45980d7175a88271bbc545d72&X-Amz-SignedHeaders=host&x-id=GetObject)


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

