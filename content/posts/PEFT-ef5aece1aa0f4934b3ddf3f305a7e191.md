---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4665NSF5IV2%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250224T202710Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDVxSbo6kyjTEbaB6r\
  fa4nN33SCTfUVXjyjlIxf9FvdVQIgebz54sSRbKJE0%2B9lTivsyu9PMxymrPn8xEcFmgglYxgq%2\
  FwMINBAAGgw2Mzc0MjMxODM4MDUiDCcmNbikpfQ%2FVUtroCrcA7MzK5Ve67G%2FgLyLOEr6FWYrE\
  GlNAdW2S7DwH5nZoTRmk%2BKinTvU03R0AnUfQYXr7lDRqTfwrmzu48xdmhbn0BJ4fXFdNT%2BdRF\
  3xnABrqUi%2BKqsqiy0HrZchoOhYpOL4vV76FKmH7Wn5oYvQCAQ6b3ydgagr6HmTJ78YaLCTJncfN\
  wa0zvNFvZRqZ4oHkiHhSncZeKAb7tag3QZ8HEAWCx%2F3quf6D54JhA1ifiaXsNJ3iiMOGTGmQo9y\
  sZvS9y04x29cM%2FCrahI14dw2OcaZon52oBgz8ruaBsjNHyEuZRdHbpNTuEOiyun7zjjcCwIhF0z\
  2fsewz0DoeMIzX6PZZ67Nb4XNEgz%2FruwitGQPXMvvX1nnFp%2Ff2BKuEpEcEKXWPlVz3YRX5OpP\
  y4bZLmkUcWk%2BZszbc1lKPUno1DSFM%2BrJOxHwYBcAmJZCM4%2FWfZ7zpY6xToBBgfYnP0AAsK2\
  wRwbdBvFHqWRh3sNgYNsERdlmi4w5Jjlwof%2BJ3zZT1LygzxG5PkPFsxT1zaGH8%2BeXAAmMRMKu\
  vRG1o74l03gvdKFKfu5RI%2FuyvIlnIXqxN7LbD8JXkFZBWAx%2F8GDUYhy3n1UrrlnBRwUXguEhJ\
  bTRUV3WEBdG0kWG%2B9%2FTkLmZMJv98r0GOqUBHW%2FelstImOFbkdaQF4Ksh%2FEHrQED%2Ft4n\
  euQLgCKD7z4uj%2BjhJLC2HmHwl%2B339WBX2tWrEiMKMkbx6gmFeCSHGR1db5I5H3KOM5t0d5hfe\
  3ji9wTzVEAzL2kAxcV%2Fy6sz0cEGJpW6tZ8uKfzmH2ALYuygOsfs9QkuGJIBjPts3lA9qe2jbe3g\
  KEzotvDQHDg9liphu5Rri%2FqE69dA8fAjXhfCaaxG&X-Amz-Signature=370e207bf9c5cf6857\
  8c6446a1c36a602a66aaf13c5b6f6f590345bc117eef67&X-Amz-SignedHeaders=host&x-id=\
  GetObject"
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
        redential=ASIAZI2LB46622AJBEZH%2F20250224%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250224T202521Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEY\
        CIQDwaDacZo4T%2FqHO%2FRH5UYB4Cain3JTLsEUKWVlokWI0XgIhAJJRwmo94qoKxARMyt\
        ToaajbfTk00L7u9D8T8XqydS79Kv8DCDQQABoMNjM3NDIzMTgzODA1IgzYBRyO7pORtBrB%\
        2BFsq3ANi90UeDVY8F1nS1S9q1F%2FZhVY0WTwtIbD03f3H6g7Xc1KJFScSr0GG6UL3PN%2\
        FKgjoezoX0Vjg2dqm4Ktkj%2F6jzTIxT5%2FMOF8vZFu%2FTS044a6stjwzhiBoJDjTyI4J\
        baDZCxfhEBNEfc9nKOdbFdog%2BUsduhSWfpkVJtQyEMpuO4VzZxIPbZNjz8yeYF0D7f0gD\
        jHVdTxKxG5BL4eqT%2B7Z1TgdtTzPUMD6oTvbn2RsXfmxBX9lNVzc91%2FFIx4xm7HsUj%2\
        F%2FxE9TU7%2F5BFtFysGo%2B%2BsUGb8bRCzQDKIibdUPmJecsckcT9lfEkAms5jQmE0DW\
        qiRe8QzwSRNIkMOXgGp2uEFdCSD8tTUEkcaJwsAAuq4kkFQ2d2PP1tZ5afZ0XUwHqG5vGoE\
        5uHzc6PwnvJ90Xv%2Blj%2FDQgttuiSRGxnQNsL9Lk9RFekHKFetwYrXJOU0amdUQWuO7%2\
        BPFDZje2t8cMaQ3H%2Bc%2FfIbfTZ0F34wm8xb9urd1F9SR6ci8dSY6Y0%2BILIVA%2F6Yw\
        Gy858dNuk70eRSt%2FgFOQCm3eLqSWdvOhi3H660l8yScFGvH2jfPRZREPpzRYSdBImU2EE\
        yP8YkEiUjWWBkVe2QXo5vXa57dqdizrck6Cbj8liubILJjDT%2FPK9BjqkAVwvCRk2B359q\
        U59jtjbNQ9IZDU%2BrpNTJbrgUhNFB3iCNsXujjT2kB4pPYOuK%2BYgBR8whGgxXE6aGqa%\
        2FruphBjwPW7fuiJRM3z0p4gBtz2C5wM%2FoFprukdqBzcESmzhSUeOWEn%2F38%2Fb1mTc\
        4p2BGeQnqy7VoEcmQQvyz2W0GK5bXCyQ8YM98EWe9OoX%2F%2F6l1oCBMBqU20dxynt4abE\
        0LsLHBwRqS&X-Amz-Signature=bff399bbc26debaa8ca7473351d5a3ad234264f187dc\
        e4a580db769de5304daa&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-24T21:25:21.314Z"
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
UPDATE_TIME: "2025-02-24T20:27:16.787Z"
EXPIRY_TIME: "2025-02-24T21:27:07.519Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UMGEVLDX%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T202707Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIFeJ2pE9tYR%2BMMzrwVpQ3C4tUSDpcxdbTJ4%2B5TeIyTEeAiEAtIGuDwhS0r96va7NRtFw0Q2XTpfwOE7r1Wwd1j4m3j8q%2FwMINBAAGgw2Mzc0MjMxODM4MDUiDFrLnxaSrl%2FLexGm9ircAx%2F%2Bwa6tC7tjVg3C1cjyhgON6OleVGXlG48XiMyxbeAobxb50e5n7K6CpwN8hYz0KbS91rkTibdJ2j5tzK5%2FclO9R2RpivAjRpaDBhij4OMtcyOXbeU0b8M7VexcoKJrbMKzAcdSDL8lSeurfPoKQ%2FCFP2D4N1uEKxnzcNFZY4dOEdWMQPD7pKZ2evyg4kJmdEoX1m4S%2BzY95%2F%2B6KFk%2FTPIz7E4cAngWoqLqcYQNip7Q%2BTcLjob4cRrPGhICcBnPs9jdWtgxDQaDtdEvPCbxKZPfu8koZgyGSStOK8c3CrhuLIE6C4RgeBJLc4uEA%2BP8FN%2Fo0XJcEUMgcFFnJ8tOEKGWwovcKnVPM1m7AkfuIsnyk9qA2KSA7Rs0Ms8FlPOwRpyiyh7zOSRNZ9Md4VnUljrw79GyJq7bz%2BeLHTkk06HxZa5RF3eUcD45qbeMUWyE1wyv%2FMxmofMVWVqfK46RafJswTFlfTglEOt22YQD63Gud6RGrV52NMml7lmt5qY%2FiVluN61xXMoth2irxjmSbKZmiNcXR7K35%2BYRznV3sRQTg9ZOguqwFF7jPolQHA0ZKoDJNYNIPJOYsDd%2FBfq0BlpSRnF2zRo%2Bf7iXPQfnAa9aYgHuh4s5z9yJ8brCMMz88r0GOqUBHFjC%2F%2FE2Sn58Vet4qeoXnspkRNa3rSpuNWimr1fXuv8hcJCxU07ZoVV4AuxLDtKZJrkMrFf2cfGKJ0Zo8hk5wb7F4vHCxOPyYUn%2FBMbHIxcXaPdg6%2BbFfeLhOMHsnE%2BWSCMwoX8sk4gKvN4%2FYOc83Q4GPevl2QyBJI0Jbg7PQ385vumWL4hKVH3S83BhnBAUbrfnQ6XAIklfUb6NOFHS1y7xcjWC&X-Amz-Signature=07c7a21bf4e45cce054669006f1ec4a4418739436b522d9815f97e5e36dbf1e8&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UMGEVLDX%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T202707Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIFeJ2pE9tYR%2BMMzrwVpQ3C4tUSDpcxdbTJ4%2B5TeIyTEeAiEAtIGuDwhS0r96va7NRtFw0Q2XTpfwOE7r1Wwd1j4m3j8q%2FwMINBAAGgw2Mzc0MjMxODM4MDUiDFrLnxaSrl%2FLexGm9ircAx%2F%2Bwa6tC7tjVg3C1cjyhgON6OleVGXlG48XiMyxbeAobxb50e5n7K6CpwN8hYz0KbS91rkTibdJ2j5tzK5%2FclO9R2RpivAjRpaDBhij4OMtcyOXbeU0b8M7VexcoKJrbMKzAcdSDL8lSeurfPoKQ%2FCFP2D4N1uEKxnzcNFZY4dOEdWMQPD7pKZ2evyg4kJmdEoX1m4S%2BzY95%2F%2B6KFk%2FTPIz7E4cAngWoqLqcYQNip7Q%2BTcLjob4cRrPGhICcBnPs9jdWtgxDQaDtdEvPCbxKZPfu8koZgyGSStOK8c3CrhuLIE6C4RgeBJLc4uEA%2BP8FN%2Fo0XJcEUMgcFFnJ8tOEKGWwovcKnVPM1m7AkfuIsnyk9qA2KSA7Rs0Ms8FlPOwRpyiyh7zOSRNZ9Md4VnUljrw79GyJq7bz%2BeLHTkk06HxZa5RF3eUcD45qbeMUWyE1wyv%2FMxmofMVWVqfK46RafJswTFlfTglEOt22YQD63Gud6RGrV52NMml7lmt5qY%2FiVluN61xXMoth2irxjmSbKZmiNcXR7K35%2BYRznV3sRQTg9ZOguqwFF7jPolQHA0ZKoDJNYNIPJOYsDd%2FBfq0BlpSRnF2zRo%2Bf7iXPQfnAa9aYgHuh4s5z9yJ8brCMMz88r0GOqUBHFjC%2F%2FE2Sn58Vet4qeoXnspkRNa3rSpuNWimr1fXuv8hcJCxU07ZoVV4AuxLDtKZJrkMrFf2cfGKJ0Zo8hk5wb7F4vHCxOPyYUn%2FBMbHIxcXaPdg6%2BbFfeLhOMHsnE%2BWSCMwoX8sk4gKvN4%2FYOc83Q4GPevl2QyBJI0Jbg7PQ385vumWL4hKVH3S83BhnBAUbrfnQ6XAIklfUb6NOFHS1y7xcjWC&X-Amz-Signature=91bf212fb0ec6bff408707cffb01d5af2af9811811c6d7860740a365b6e46e28&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UMGEVLDX%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T202707Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIFeJ2pE9tYR%2BMMzrwVpQ3C4tUSDpcxdbTJ4%2B5TeIyTEeAiEAtIGuDwhS0r96va7NRtFw0Q2XTpfwOE7r1Wwd1j4m3j8q%2FwMINBAAGgw2Mzc0MjMxODM4MDUiDFrLnxaSrl%2FLexGm9ircAx%2F%2Bwa6tC7tjVg3C1cjyhgON6OleVGXlG48XiMyxbeAobxb50e5n7K6CpwN8hYz0KbS91rkTibdJ2j5tzK5%2FclO9R2RpivAjRpaDBhij4OMtcyOXbeU0b8M7VexcoKJrbMKzAcdSDL8lSeurfPoKQ%2FCFP2D4N1uEKxnzcNFZY4dOEdWMQPD7pKZ2evyg4kJmdEoX1m4S%2BzY95%2F%2B6KFk%2FTPIz7E4cAngWoqLqcYQNip7Q%2BTcLjob4cRrPGhICcBnPs9jdWtgxDQaDtdEvPCbxKZPfu8koZgyGSStOK8c3CrhuLIE6C4RgeBJLc4uEA%2BP8FN%2Fo0XJcEUMgcFFnJ8tOEKGWwovcKnVPM1m7AkfuIsnyk9qA2KSA7Rs0Ms8FlPOwRpyiyh7zOSRNZ9Md4VnUljrw79GyJq7bz%2BeLHTkk06HxZa5RF3eUcD45qbeMUWyE1wyv%2FMxmofMVWVqfK46RafJswTFlfTglEOt22YQD63Gud6RGrV52NMml7lmt5qY%2FiVluN61xXMoth2irxjmSbKZmiNcXR7K35%2BYRznV3sRQTg9ZOguqwFF7jPolQHA0ZKoDJNYNIPJOYsDd%2FBfq0BlpSRnF2zRo%2Bf7iXPQfnAa9aYgHuh4s5z9yJ8brCMMz88r0GOqUBHFjC%2F%2FE2Sn58Vet4qeoXnspkRNa3rSpuNWimr1fXuv8hcJCxU07ZoVV4AuxLDtKZJrkMrFf2cfGKJ0Zo8hk5wb7F4vHCxOPyYUn%2FBMbHIxcXaPdg6%2BbFfeLhOMHsnE%2BWSCMwoX8sk4gKvN4%2FYOc83Q4GPevl2QyBJI0Jbg7PQ385vumWL4hKVH3S83BhnBAUbrfnQ6XAIklfUb6NOFHS1y7xcjWC&X-Amz-Signature=bc05cbc60da908ec2a464d01caffce98ec2e2326949e244780568859e8da7631&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UMGEVLDX%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T202707Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIFeJ2pE9tYR%2BMMzrwVpQ3C4tUSDpcxdbTJ4%2B5TeIyTEeAiEAtIGuDwhS0r96va7NRtFw0Q2XTpfwOE7r1Wwd1j4m3j8q%2FwMINBAAGgw2Mzc0MjMxODM4MDUiDFrLnxaSrl%2FLexGm9ircAx%2F%2Bwa6tC7tjVg3C1cjyhgON6OleVGXlG48XiMyxbeAobxb50e5n7K6CpwN8hYz0KbS91rkTibdJ2j5tzK5%2FclO9R2RpivAjRpaDBhij4OMtcyOXbeU0b8M7VexcoKJrbMKzAcdSDL8lSeurfPoKQ%2FCFP2D4N1uEKxnzcNFZY4dOEdWMQPD7pKZ2evyg4kJmdEoX1m4S%2BzY95%2F%2B6KFk%2FTPIz7E4cAngWoqLqcYQNip7Q%2BTcLjob4cRrPGhICcBnPs9jdWtgxDQaDtdEvPCbxKZPfu8koZgyGSStOK8c3CrhuLIE6C4RgeBJLc4uEA%2BP8FN%2Fo0XJcEUMgcFFnJ8tOEKGWwovcKnVPM1m7AkfuIsnyk9qA2KSA7Rs0Ms8FlPOwRpyiyh7zOSRNZ9Md4VnUljrw79GyJq7bz%2BeLHTkk06HxZa5RF3eUcD45qbeMUWyE1wyv%2FMxmofMVWVqfK46RafJswTFlfTglEOt22YQD63Gud6RGrV52NMml7lmt5qY%2FiVluN61xXMoth2irxjmSbKZmiNcXR7K35%2BYRznV3sRQTg9ZOguqwFF7jPolQHA0ZKoDJNYNIPJOYsDd%2FBfq0BlpSRnF2zRo%2Bf7iXPQfnAa9aYgHuh4s5z9yJ8brCMMz88r0GOqUBHFjC%2F%2FE2Sn58Vet4qeoXnspkRNa3rSpuNWimr1fXuv8hcJCxU07ZoVV4AuxLDtKZJrkMrFf2cfGKJ0Zo8hk5wb7F4vHCxOPyYUn%2FBMbHIxcXaPdg6%2BbFfeLhOMHsnE%2BWSCMwoX8sk4gKvN4%2FYOc83Q4GPevl2QyBJI0Jbg7PQ385vumWL4hKVH3S83BhnBAUbrfnQ6XAIklfUb6NOFHS1y7xcjWC&X-Amz-Signature=42bbc0e54970c4adfc3fafb7a323a39eae4988a865cc6bc91f40bbdedfccd0b8&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UMGEVLDX%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T202707Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIFeJ2pE9tYR%2BMMzrwVpQ3C4tUSDpcxdbTJ4%2B5TeIyTEeAiEAtIGuDwhS0r96va7NRtFw0Q2XTpfwOE7r1Wwd1j4m3j8q%2FwMINBAAGgw2Mzc0MjMxODM4MDUiDFrLnxaSrl%2FLexGm9ircAx%2F%2Bwa6tC7tjVg3C1cjyhgON6OleVGXlG48XiMyxbeAobxb50e5n7K6CpwN8hYz0KbS91rkTibdJ2j5tzK5%2FclO9R2RpivAjRpaDBhij4OMtcyOXbeU0b8M7VexcoKJrbMKzAcdSDL8lSeurfPoKQ%2FCFP2D4N1uEKxnzcNFZY4dOEdWMQPD7pKZ2evyg4kJmdEoX1m4S%2BzY95%2F%2B6KFk%2FTPIz7E4cAngWoqLqcYQNip7Q%2BTcLjob4cRrPGhICcBnPs9jdWtgxDQaDtdEvPCbxKZPfu8koZgyGSStOK8c3CrhuLIE6C4RgeBJLc4uEA%2BP8FN%2Fo0XJcEUMgcFFnJ8tOEKGWwovcKnVPM1m7AkfuIsnyk9qA2KSA7Rs0Ms8FlPOwRpyiyh7zOSRNZ9Md4VnUljrw79GyJq7bz%2BeLHTkk06HxZa5RF3eUcD45qbeMUWyE1wyv%2FMxmofMVWVqfK46RafJswTFlfTglEOt22YQD63Gud6RGrV52NMml7lmt5qY%2FiVluN61xXMoth2irxjmSbKZmiNcXR7K35%2BYRznV3sRQTg9ZOguqwFF7jPolQHA0ZKoDJNYNIPJOYsDd%2FBfq0BlpSRnF2zRo%2Bf7iXPQfnAa9aYgHuh4s5z9yJ8brCMMz88r0GOqUBHFjC%2F%2FE2Sn58Vet4qeoXnspkRNa3rSpuNWimr1fXuv8hcJCxU07ZoVV4AuxLDtKZJrkMrFf2cfGKJ0Zo8hk5wb7F4vHCxOPyYUn%2FBMbHIxcXaPdg6%2BbFfeLhOMHsnE%2BWSCMwoX8sk4gKvN4%2FYOc83Q4GPevl2QyBJI0Jbg7PQ385vumWL4hKVH3S83BhnBAUbrfnQ6XAIklfUb6NOFHS1y7xcjWC&X-Amz-Signature=ca6ce048b2629299e833fbb4633341380a71ff0b8abe5ec8caae223be9916b70&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663KVDPB7G%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T202708Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIGfoNT9dPesHXfIkjxiHXRDF9vFArwUsC3E9gBhOGM8tAiEAmbmNtCX%2FZQzE2tYxF2LlfNh3FihDFCEX9BaIEh2BDFkq%2FwMINBAAGgw2Mzc0MjMxODM4MDUiDIewp6oWpAlAMbyHVCrcA7%2F0SRtbalfScfGoE7n23LLZMN9vVmZgIjkWnwHx2lIFu07eMAEMcryuU%2B7ypiLuVo4xkDndm7g%2BDPQ3DqrO9pz%2FF%2FUb49RAkLAXYtemE1n00NDO0t5yIyXXyyggkPGPhgyvDhjsDa7wTXn09ISRJx5z5g3L4QQJcuNy60qFYedF7ZJakNz0zp8VTWbfKvBot2Hr3aQ3kKzOJVOUhFxYk1f7XW61sV4p1WMDxCGrghrfyASE%2B7DMXbC0GwWZfHT22ZZ%2BTP6RnMaT7QfMTdrMfzddO7vwNcn60Veh2UhRBpOq6c5NWmfjm7b46k2YoEx2xQdV0uCOIZCKzj7ba0GAxwr8NHki4bD9qm0it3JV4KG86C7AIwQCRkiRag7eJuqz7a5Ep6Yj6ysPVjDctYB0WBr2vk2cQ07RENt7OgFftpIxdjqD2mWYQBcThR2GtP%2FPCNNibxD0ZBJbMEb1WO85ikhjCdyrEbZIko12eurM7VrSFJvaDfGw097z%2FFjFBTtQtWbYJS2O6cXpFG3JVgovDoNgfjV9XwODqac8rKgD722N7PcMXo6ITlRw0mUW0lsLu1xIKn4IW1VTJtRhcg17GokBQTLLI2eHCo6kxBgUytgcxjg3l7YXUW1gwlu0MOX98r0GOqUBiE7QiEk2U2cfRfkU4fWbpNt433opWoSJOLWrmPT4cuFDQghMWmM2JkFRiPZoia1kd5cW8Kp2gwG9kBG2cCaujswYgyQ4g0%2B367Y5NyQQ5%2F%2FPGr1aA5PSn5fXcf9VbGGcWtHXLiEKyBdfDowiHU%2F0Lhsk5tcmwtCrHzzJgwZ6pegFzYZgsJaCfd7iYD%2BkGSUDWYVTTkwzUgRJGtbVQA6ZJUww2PVM&X-Amz-Signature=324c6dfbd8c4fb0dec6ec9aab904342640e9a020d95c4d117204de8062f1a3df&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663QX2ECAA%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T202709Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIGhnN9sG%2BgZ3kmwGw7SPf5aiT9cXp8iHvxhdFzfDKszfAiBSKyl%2BjnpNcbct7A%2FsQLYLCR8Z54OmxwUqkP4BytBMWyr%2FAwg0EAAaDDYzNzQyMzE4MzgwNSIMuxe9AvLokPSBoahdKtwD7YeHdRj24aF3G8W88D2%2B8aQ1S5z8i2O%2FL85E6m1H67KOwv%2F3Z9FVKlZFeUS3VRazQscmdwwji1BV5dOETFp%2B1h6OQ08Pgw1jK36CQh9o4YLKtR1fy6VywBLnK9hfbZ7fDFjwPKQrS%2Brpa1WMUj3znSRiAksE3fk2bSCvlb%2BZn0DzUQMAAXPFpDcDl9FRelP0Rbc7Tsm1JmOKfVfW6rAiyu28M64A2HRHA6Dt8mQVF4dJao%2FelnGztLYSSHbfEeJG8gJ8tC%2BikNllA9MKepilzDM6FHqlpsP1LakC3oK07PukhGLSvxjp42UiV6AZJ0Wc%2FIr5fI4r378fEMv5c5aBAdzgLC5fjFrgYWxU1XRGhD77OgmGwWZq1jx0VATkpbXc9eKT51AsWkWvseu6mjPK9I8O4T3N%2BMry1bYhy2YKh7cNkUE8DPKHcAqGEF2VgusRu6ELDn5MqdqCBClgVbpJfHw6sWkImNI2lLM9Eux%2Bqx8kEPYRp5N7EiJxJeF9T0R%2Bpoyhonm%2BXbEFxZI3%2BBC%2FldKS4yZ11a8qgfFjAeKx9N7dlloFSerRusEuqY73BLdiAM3E7xcs3lOFoJFn30tcHDC9Ur9ujJGQz4hkmbC5FV5XKUqGy0LgReGcRMUw4fzyvQY6pgEs793If4RUWSP5kW9ved0U85uHJl6p2Pqt95VBfL70NzEolFZJnIyg4WvJg3ZIEQbiuKU8PSkt%2BNWXqJcgfSGYkGA0KBvKI6aogNZNpUUynjcPD%2FoJNXp3fi7o1DcpLkIN3Ewbp24UWHyfaqR9StN9YMeMO9CCddWGEO0PvVj%2B2CxxCH1hVpP3TFzHzUwc6ip8keTaWNETf7AjbNKRP2CEWXEYzjTh&X-Amz-Signature=a57a5f3ec75627d62b33b29a330437961a5a4ec928458485064ec7cdb5e560ae&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UMGEVLDX%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T202708Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIFeJ2pE9tYR%2BMMzrwVpQ3C4tUSDpcxdbTJ4%2B5TeIyTEeAiEAtIGuDwhS0r96va7NRtFw0Q2XTpfwOE7r1Wwd1j4m3j8q%2FwMINBAAGgw2Mzc0MjMxODM4MDUiDFrLnxaSrl%2FLexGm9ircAx%2F%2Bwa6tC7tjVg3C1cjyhgON6OleVGXlG48XiMyxbeAobxb50e5n7K6CpwN8hYz0KbS91rkTibdJ2j5tzK5%2FclO9R2RpivAjRpaDBhij4OMtcyOXbeU0b8M7VexcoKJrbMKzAcdSDL8lSeurfPoKQ%2FCFP2D4N1uEKxnzcNFZY4dOEdWMQPD7pKZ2evyg4kJmdEoX1m4S%2BzY95%2F%2B6KFk%2FTPIz7E4cAngWoqLqcYQNip7Q%2BTcLjob4cRrPGhICcBnPs9jdWtgxDQaDtdEvPCbxKZPfu8koZgyGSStOK8c3CrhuLIE6C4RgeBJLc4uEA%2BP8FN%2Fo0XJcEUMgcFFnJ8tOEKGWwovcKnVPM1m7AkfuIsnyk9qA2KSA7Rs0Ms8FlPOwRpyiyh7zOSRNZ9Md4VnUljrw79GyJq7bz%2BeLHTkk06HxZa5RF3eUcD45qbeMUWyE1wyv%2FMxmofMVWVqfK46RafJswTFlfTglEOt22YQD63Gud6RGrV52NMml7lmt5qY%2FiVluN61xXMoth2irxjmSbKZmiNcXR7K35%2BYRznV3sRQTg9ZOguqwFF7jPolQHA0ZKoDJNYNIPJOYsDd%2FBfq0BlpSRnF2zRo%2Bf7iXPQfnAa9aYgHuh4s5z9yJ8brCMMz88r0GOqUBHFjC%2F%2FE2Sn58Vet4qeoXnspkRNa3rSpuNWimr1fXuv8hcJCxU07ZoVV4AuxLDtKZJrkMrFf2cfGKJ0Zo8hk5wb7F4vHCxOPyYUn%2FBMbHIxcXaPdg6%2BbFfeLhOMHsnE%2BWSCMwoX8sk4gKvN4%2FYOc83Q4GPevl2QyBJI0Jbg7PQ385vumWL4hKVH3S83BhnBAUbrfnQ6XAIklfUb6NOFHS1y7xcjWC&X-Amz-Signature=6b1c9101936f2f761f0b9a8f3fbff5dfb54014df273fea6f5b8522fd140900bc&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UMGEVLDX%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T202707Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIFeJ2pE9tYR%2BMMzrwVpQ3C4tUSDpcxdbTJ4%2B5TeIyTEeAiEAtIGuDwhS0r96va7NRtFw0Q2XTpfwOE7r1Wwd1j4m3j8q%2FwMINBAAGgw2Mzc0MjMxODM4MDUiDFrLnxaSrl%2FLexGm9ircAx%2F%2Bwa6tC7tjVg3C1cjyhgON6OleVGXlG48XiMyxbeAobxb50e5n7K6CpwN8hYz0KbS91rkTibdJ2j5tzK5%2FclO9R2RpivAjRpaDBhij4OMtcyOXbeU0b8M7VexcoKJrbMKzAcdSDL8lSeurfPoKQ%2FCFP2D4N1uEKxnzcNFZY4dOEdWMQPD7pKZ2evyg4kJmdEoX1m4S%2BzY95%2F%2B6KFk%2FTPIz7E4cAngWoqLqcYQNip7Q%2BTcLjob4cRrPGhICcBnPs9jdWtgxDQaDtdEvPCbxKZPfu8koZgyGSStOK8c3CrhuLIE6C4RgeBJLc4uEA%2BP8FN%2Fo0XJcEUMgcFFnJ8tOEKGWwovcKnVPM1m7AkfuIsnyk9qA2KSA7Rs0Ms8FlPOwRpyiyh7zOSRNZ9Md4VnUljrw79GyJq7bz%2BeLHTkk06HxZa5RF3eUcD45qbeMUWyE1wyv%2FMxmofMVWVqfK46RafJswTFlfTglEOt22YQD63Gud6RGrV52NMml7lmt5qY%2FiVluN61xXMoth2irxjmSbKZmiNcXR7K35%2BYRznV3sRQTg9ZOguqwFF7jPolQHA0ZKoDJNYNIPJOYsDd%2FBfq0BlpSRnF2zRo%2Bf7iXPQfnAa9aYgHuh4s5z9yJ8brCMMz88r0GOqUBHFjC%2F%2FE2Sn58Vet4qeoXnspkRNa3rSpuNWimr1fXuv8hcJCxU07ZoVV4AuxLDtKZJrkMrFf2cfGKJ0Zo8hk5wb7F4vHCxOPyYUn%2FBMbHIxcXaPdg6%2BbFfeLhOMHsnE%2BWSCMwoX8sk4gKvN4%2FYOc83Q4GPevl2QyBJI0Jbg7PQ385vumWL4hKVH3S83BhnBAUbrfnQ6XAIklfUb6NOFHS1y7xcjWC&X-Amz-Signature=a59b1e9a5df8e3c4177687bba112970f7a1e7902aa58f50a6208b282653dc23d&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UMGEVLDX%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T202708Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIFeJ2pE9tYR%2BMMzrwVpQ3C4tUSDpcxdbTJ4%2B5TeIyTEeAiEAtIGuDwhS0r96va7NRtFw0Q2XTpfwOE7r1Wwd1j4m3j8q%2FwMINBAAGgw2Mzc0MjMxODM4MDUiDFrLnxaSrl%2FLexGm9ircAx%2F%2Bwa6tC7tjVg3C1cjyhgON6OleVGXlG48XiMyxbeAobxb50e5n7K6CpwN8hYz0KbS91rkTibdJ2j5tzK5%2FclO9R2RpivAjRpaDBhij4OMtcyOXbeU0b8M7VexcoKJrbMKzAcdSDL8lSeurfPoKQ%2FCFP2D4N1uEKxnzcNFZY4dOEdWMQPD7pKZ2evyg4kJmdEoX1m4S%2BzY95%2F%2B6KFk%2FTPIz7E4cAngWoqLqcYQNip7Q%2BTcLjob4cRrPGhICcBnPs9jdWtgxDQaDtdEvPCbxKZPfu8koZgyGSStOK8c3CrhuLIE6C4RgeBJLc4uEA%2BP8FN%2Fo0XJcEUMgcFFnJ8tOEKGWwovcKnVPM1m7AkfuIsnyk9qA2KSA7Rs0Ms8FlPOwRpyiyh7zOSRNZ9Md4VnUljrw79GyJq7bz%2BeLHTkk06HxZa5RF3eUcD45qbeMUWyE1wyv%2FMxmofMVWVqfK46RafJswTFlfTglEOt22YQD63Gud6RGrV52NMml7lmt5qY%2FiVluN61xXMoth2irxjmSbKZmiNcXR7K35%2BYRznV3sRQTg9ZOguqwFF7jPolQHA0ZKoDJNYNIPJOYsDd%2FBfq0BlpSRnF2zRo%2Bf7iXPQfnAa9aYgHuh4s5z9yJ8brCMMz88r0GOqUBHFjC%2F%2FE2Sn58Vet4qeoXnspkRNa3rSpuNWimr1fXuv8hcJCxU07ZoVV4AuxLDtKZJrkMrFf2cfGKJ0Zo8hk5wb7F4vHCxOPyYUn%2FBMbHIxcXaPdg6%2BbFfeLhOMHsnE%2BWSCMwoX8sk4gKvN4%2FYOc83Q4GPevl2QyBJI0Jbg7PQ385vumWL4hKVH3S83BhnBAUbrfnQ6XAIklfUb6NOFHS1y7xcjWC&X-Amz-Signature=8cdc4dddf5a243cd723053a06d0496427048898dd51aec5655c7e00c0f5f2542&X-Amz-SignedHeaders=host&x-id=GetObject)


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

