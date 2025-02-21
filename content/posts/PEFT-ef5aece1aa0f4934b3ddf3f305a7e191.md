---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB46664LWKZ7Y%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250221T142150Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEK7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDGd3ZbBr5Vgd%2FFf\
  xXPIKzmlRFjoXB%2FRjLCSOKhopYYjwIhAKjJTrP7aj0Ib0U3m9rzUn12aV4uIyOPpH%2Feendfty\
  ZDKogECNf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igxxe0YATJlxslH\
  WRdMq3AMCkPsRPeuF9YIfs5UPOKj1ZVWvKJCjeQDYkwXgmFj5RgCs7KAWRCru4RVP7Pi5N5otJ1u3\
  bs%2FCUbBuB8wGC270th3etj6BkMO8SLEZwX0n5htPpW4XOzkJsvSK0ZxgRnnVOIGHGuggt07GwWi\
  r%2F4J80RfAp0e6FU79tvYuKJbBOduVbhk95EiKjQSUFFfm%2FYlXFgjUd14%2BmXVUFsk6R%2BzJ\
  xxuAoD%2BvPmoN4hKEnAICmTNaPSxSvTj9KCtW4879xbOhr%2FB8PYVX42oulSdHgwj6iWMR%2Bvk\
  gLJIgWJELRmU8x9CCkYHL9bgwcJ%2F3rmy33ND1r%2FXh70%2FdfGOc1rhAeJxIi6mTSjliyKIiwo\
  xCRvP4CeNBFTuBlJNDfIHvdLio9UnzV5xKN%2BJGGrU1ih%2F4URoHvGq%2FfjiBEKveAXnGp4%2F\
  raRYye0ulV3AqBApgRnjeeZrDHMt33y4RLC6L4V%2F7b6cb9JIpDLoaIhFGl%2FZ6uN6%2F98yE5Q\
  MFsx2y2exS0v8U1giChOhWkuf%2BRO7Fqj%2FlINP4CMDQRfQEAQue8ysKAv8Y3Tb5xo8Mh5guBZM\
  il9hWXGSM%2Fg9yAU%2BCCDe0VxjxCzftHyXmeyccyh9CK0vCeOvoSKFD7Sd%2Fq8YcXWlhFTDcgu\
  K9BjqkAVEkT1rE7isNT7o0%2FO%2BAQC0FiDJ9y0DKG77Q9ib6tVoQds5PyenqJZdU9fZcWZwua0G\
  nTSSwf7vM5XjWUq1k3rjjC8ScRIjgKqHWfmT9c1j%2Fv7Ov69cIRfH3zA%2FBFhwj2n9%2BwhGkqA\
  92YRTvwT9q1jj%2B4GSFiSzs%2F9D%2FTmPiZFgghC48CZL%2FwihRoutFwEUxQYdiWWS663ufyV1\
  HlBbAWrh5k8BG&X-Amz-Signature=89cf1f1230248a675a5676d992504a80a34eb55fb0c2be8\
  0ce35ed5c89349f18&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466RUL3BFTQ%2F20250221%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250221T142010Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEK7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIBF4y3dh8FbKWq5H8zbzgaO%2F5O2KDSSH0z8YOkI%2B7tGiAiEAoFprzoDYat%2BBMvWw\
        RkBwcxPCh7fE7C%2B2klXUgz6hVeAqiAQI1%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARA\
        AGgw2Mzc0MjMxODM4MDUiDFXizEe81EYLUAAX7yrcA0kS00PM7V7LOvtMqI3f%2FVVJJRD3\
        SO2fzZ4SYDa9%2F3fokiNpFMUcCdaQXw6Z5iQNcZUjGicxPHuUV9e199gWQS063hzyT9I%2\
        BqF2ZtIFccoUIHW0v0iMJ7wsncY1h7%2FRVI7Tn53zn7HHospKR7NFUDNEXCF45XBO1kng1\
        L8hcdeWj7LCOT3ROD%2BtP6OWv2DJiofHSydySzZqAq%2FySNQo6TXmZCdSZnMKO9c%2FD6\
        zBj4kld8L91eSh5OFKh9aFPqlOqJLKELZA1N5FS0BU7e8eiMl3awoznJT28ZGr6P1UtZ88g\
        bg8aafnT%2F9n7B0JmZgPkle5x%2F61gz8%2FKfbJR%2BVjuwu0nFCYmTWWGvqverQCGKMo\
        HuxTPeqXQbMWKN%2BPkUCxwey%2F9PWwca1iPKmHNk71oOcOJFn%2Fk0hgvGtRHCM6XlSaq\
        rWSauQwkdFWEk%2FHghr5oGpi9hK33txoqUo%2Bvi5%2F5uk%2BbrTuTu%2FZaVKEDMMFU9\
        2z%2FRTRlQCTG6ogc0mVbmApEM1hqUtbojJAS%2FVBnIRWuKOymw4X8IlzMba3c%2Fav1fA\
        ZGJNfnCM8E4xH8AbfNcVzRDNduzuVAYC%2F9OnaUC3NZFHma7YCzrBAqLXSfHhQx1MrQm1I\
        rUs21B4f96jeHMNeC4r0GOqUB3MOxpnejVikORwuFAzGp3KH6YYal%2BRi%2BYN78miuUbS\
        vIWIerLUCeIGG%2BMEmcDkf9A6yxmVvj%2BgUqsRo8ZkO0emICNa%2Fel9kqaLE8mkh9wJr\
        LAbt%2BRWILfBJqxxbYWOBLvHZ4xsIM4LCwub23cTmkKkvd9xb2BodU4SCBJdXOQBQF86C6\
        iCwK%2FfmZM8mzk1XJ0rmzOwJsIUT0MuA485Fvaa3MugxN&X-Amz-Signature=8df6acba\
        3c3356046e2db7bd2b65ee7cbd16e1ce480f295fcae5a75ece6657d5&X-Amz-SignedHe\
        aders=host&x-id=GetObject"
      expiry_time: "2025-02-21T15:20:10.251Z"
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
UPDATE_TIME: "2025-02-21T14:21:58.098Z"
EXPIRY_TIME: "2025-02-21T15:21:46.690Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZGJ6OIYI%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T142147Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEK7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCLSW2XXTAq7yQpcNue5mVDpCRX2v6287yZB5viVtwevwIgKdrQJzT3AQpjh3A2fmIVUdovELhbfyVREHERXjOGr9cqiAQI1%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLF7BYGwx8lTpt62qircA0HQuoU9vnK2mfuQD2OzdEhhkIDnkuuhxwk1VxYn4815s5aESzzsDp8AZfnHL2zgY0i%2BjUYIDzlGaucYuuLFioxtJTq6ohmg0UNpkajxrCHhKYtgu9PKaVrRWhjyHuKo%2FOOVhZWMaymNQpG5ERMX3%2Ffvb%2FG%2FBB8Fa6t1E3hKElYkttF15FKEDFWk%2FT%2B4EUjN4cf%2B8ukHkj%2BXIc%2BBdHiKlC2z1lSaveNTk4ZHzaFPoxBFfJBYbK8oIvB9%2B44l2%2B%2BK05CFuJBtyc37V0dEL%2FKGFLHCcsa6ZioSZH15vh4%2FMkdIAl2jD81xujOS7hekO8o7lIEs7bsS7ddPPUYuw3Xsi3bJo8r9eq8oRKzsviYDcU6CL51Toi9xJcPGZiAehSM252054%2BSmGEkN3L8E%2FZEzhVEL%2FnB6bEwEOlTAZnYA6rk8oHPbQhuP3osN%2BWrgqIOm5MS59p%2FozIHDr3jaAlJKHzmB1CDl0Yxev8YbMiU0fQ9qxD2t0q%2BI6ZSvxa6RUs0ZYugb8a1SiXlMHbSzdu04btFe4Zim7%2BDEhPnjNqMiB2Axf3sIXVCdY4RPo6GYgviuCIJxDsFcD3Zg0nEhEh6YYlrKbrCo3Sc8LV2aqKvv70ngSKz07wNBP6wMrkX0MPmB4r0GOqUBTWN9B3p%2F9MAerR5nLtLrfx4YWye66hXJ%2FmsQTshlm37%2F%2Bo0FC3QuPbuD%2FxRgQPVOlboZI13H1Ld2GWubgKPsUeHBy%2BKRAEZMVwts57gfRX0BOk21ZxxSYt%2BlivA0m9wwPUxVPj8fgtedwwRo6%2Bzj%2FivMoWSnujlNgl9yXwryu5yVK5m2paRstugnXwQ5ukGjyAEWrV7FdG3kNuY0z0IVMvnui9o7&X-Amz-Signature=9954b0bad7467367ef5d598386c7b2f89299693fff99187275da19605d35c3c5&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZGJ6OIYI%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T142147Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEK7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCLSW2XXTAq7yQpcNue5mVDpCRX2v6287yZB5viVtwevwIgKdrQJzT3AQpjh3A2fmIVUdovELhbfyVREHERXjOGr9cqiAQI1%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLF7BYGwx8lTpt62qircA0HQuoU9vnK2mfuQD2OzdEhhkIDnkuuhxwk1VxYn4815s5aESzzsDp8AZfnHL2zgY0i%2BjUYIDzlGaucYuuLFioxtJTq6ohmg0UNpkajxrCHhKYtgu9PKaVrRWhjyHuKo%2FOOVhZWMaymNQpG5ERMX3%2Ffvb%2FG%2FBB8Fa6t1E3hKElYkttF15FKEDFWk%2FT%2B4EUjN4cf%2B8ukHkj%2BXIc%2BBdHiKlC2z1lSaveNTk4ZHzaFPoxBFfJBYbK8oIvB9%2B44l2%2B%2BK05CFuJBtyc37V0dEL%2FKGFLHCcsa6ZioSZH15vh4%2FMkdIAl2jD81xujOS7hekO8o7lIEs7bsS7ddPPUYuw3Xsi3bJo8r9eq8oRKzsviYDcU6CL51Toi9xJcPGZiAehSM252054%2BSmGEkN3L8E%2FZEzhVEL%2FnB6bEwEOlTAZnYA6rk8oHPbQhuP3osN%2BWrgqIOm5MS59p%2FozIHDr3jaAlJKHzmB1CDl0Yxev8YbMiU0fQ9qxD2t0q%2BI6ZSvxa6RUs0ZYugb8a1SiXlMHbSzdu04btFe4Zim7%2BDEhPnjNqMiB2Axf3sIXVCdY4RPo6GYgviuCIJxDsFcD3Zg0nEhEh6YYlrKbrCo3Sc8LV2aqKvv70ngSKz07wNBP6wMrkX0MPmB4r0GOqUBTWN9B3p%2F9MAerR5nLtLrfx4YWye66hXJ%2FmsQTshlm37%2F%2Bo0FC3QuPbuD%2FxRgQPVOlboZI13H1Ld2GWubgKPsUeHBy%2BKRAEZMVwts57gfRX0BOk21ZxxSYt%2BlivA0m9wwPUxVPj8fgtedwwRo6%2Bzj%2FivMoWSnujlNgl9yXwryu5yVK5m2paRstugnXwQ5ukGjyAEWrV7FdG3kNuY0z0IVMvnui9o7&X-Amz-Signature=ac59288e144652b6a918d95cd811927bce5a4b778138c8e37000b5e782493c8d&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZGJ6OIYI%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T142147Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEK7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCLSW2XXTAq7yQpcNue5mVDpCRX2v6287yZB5viVtwevwIgKdrQJzT3AQpjh3A2fmIVUdovELhbfyVREHERXjOGr9cqiAQI1%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLF7BYGwx8lTpt62qircA0HQuoU9vnK2mfuQD2OzdEhhkIDnkuuhxwk1VxYn4815s5aESzzsDp8AZfnHL2zgY0i%2BjUYIDzlGaucYuuLFioxtJTq6ohmg0UNpkajxrCHhKYtgu9PKaVrRWhjyHuKo%2FOOVhZWMaymNQpG5ERMX3%2Ffvb%2FG%2FBB8Fa6t1E3hKElYkttF15FKEDFWk%2FT%2B4EUjN4cf%2B8ukHkj%2BXIc%2BBdHiKlC2z1lSaveNTk4ZHzaFPoxBFfJBYbK8oIvB9%2B44l2%2B%2BK05CFuJBtyc37V0dEL%2FKGFLHCcsa6ZioSZH15vh4%2FMkdIAl2jD81xujOS7hekO8o7lIEs7bsS7ddPPUYuw3Xsi3bJo8r9eq8oRKzsviYDcU6CL51Toi9xJcPGZiAehSM252054%2BSmGEkN3L8E%2FZEzhVEL%2FnB6bEwEOlTAZnYA6rk8oHPbQhuP3osN%2BWrgqIOm5MS59p%2FozIHDr3jaAlJKHzmB1CDl0Yxev8YbMiU0fQ9qxD2t0q%2BI6ZSvxa6RUs0ZYugb8a1SiXlMHbSzdu04btFe4Zim7%2BDEhPnjNqMiB2Axf3sIXVCdY4RPo6GYgviuCIJxDsFcD3Zg0nEhEh6YYlrKbrCo3Sc8LV2aqKvv70ngSKz07wNBP6wMrkX0MPmB4r0GOqUBTWN9B3p%2F9MAerR5nLtLrfx4YWye66hXJ%2FmsQTshlm37%2F%2Bo0FC3QuPbuD%2FxRgQPVOlboZI13H1Ld2GWubgKPsUeHBy%2BKRAEZMVwts57gfRX0BOk21ZxxSYt%2BlivA0m9wwPUxVPj8fgtedwwRo6%2Bzj%2FivMoWSnujlNgl9yXwryu5yVK5m2paRstugnXwQ5ukGjyAEWrV7FdG3kNuY0z0IVMvnui9o7&X-Amz-Signature=dad3e564b1080e83bac33ea2c522a3a1b6c009e536112fb908bda613599ecbeb&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZGJ6OIYI%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T142147Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEK7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCLSW2XXTAq7yQpcNue5mVDpCRX2v6287yZB5viVtwevwIgKdrQJzT3AQpjh3A2fmIVUdovELhbfyVREHERXjOGr9cqiAQI1%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLF7BYGwx8lTpt62qircA0HQuoU9vnK2mfuQD2OzdEhhkIDnkuuhxwk1VxYn4815s5aESzzsDp8AZfnHL2zgY0i%2BjUYIDzlGaucYuuLFioxtJTq6ohmg0UNpkajxrCHhKYtgu9PKaVrRWhjyHuKo%2FOOVhZWMaymNQpG5ERMX3%2Ffvb%2FG%2FBB8Fa6t1E3hKElYkttF15FKEDFWk%2FT%2B4EUjN4cf%2B8ukHkj%2BXIc%2BBdHiKlC2z1lSaveNTk4ZHzaFPoxBFfJBYbK8oIvB9%2B44l2%2B%2BK05CFuJBtyc37V0dEL%2FKGFLHCcsa6ZioSZH15vh4%2FMkdIAl2jD81xujOS7hekO8o7lIEs7bsS7ddPPUYuw3Xsi3bJo8r9eq8oRKzsviYDcU6CL51Toi9xJcPGZiAehSM252054%2BSmGEkN3L8E%2FZEzhVEL%2FnB6bEwEOlTAZnYA6rk8oHPbQhuP3osN%2BWrgqIOm5MS59p%2FozIHDr3jaAlJKHzmB1CDl0Yxev8YbMiU0fQ9qxD2t0q%2BI6ZSvxa6RUs0ZYugb8a1SiXlMHbSzdu04btFe4Zim7%2BDEhPnjNqMiB2Axf3sIXVCdY4RPo6GYgviuCIJxDsFcD3Zg0nEhEh6YYlrKbrCo3Sc8LV2aqKvv70ngSKz07wNBP6wMrkX0MPmB4r0GOqUBTWN9B3p%2F9MAerR5nLtLrfx4YWye66hXJ%2FmsQTshlm37%2F%2Bo0FC3QuPbuD%2FxRgQPVOlboZI13H1Ld2GWubgKPsUeHBy%2BKRAEZMVwts57gfRX0BOk21ZxxSYt%2BlivA0m9wwPUxVPj8fgtedwwRo6%2Bzj%2FivMoWSnujlNgl9yXwryu5yVK5m2paRstugnXwQ5ukGjyAEWrV7FdG3kNuY0z0IVMvnui9o7&X-Amz-Signature=d8a1ad0612314d5392515f57031100e786b2f67a39289876e006fb815821c85d&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZGJ6OIYI%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T142147Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEK7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCLSW2XXTAq7yQpcNue5mVDpCRX2v6287yZB5viVtwevwIgKdrQJzT3AQpjh3A2fmIVUdovELhbfyVREHERXjOGr9cqiAQI1%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLF7BYGwx8lTpt62qircA0HQuoU9vnK2mfuQD2OzdEhhkIDnkuuhxwk1VxYn4815s5aESzzsDp8AZfnHL2zgY0i%2BjUYIDzlGaucYuuLFioxtJTq6ohmg0UNpkajxrCHhKYtgu9PKaVrRWhjyHuKo%2FOOVhZWMaymNQpG5ERMX3%2Ffvb%2FG%2FBB8Fa6t1E3hKElYkttF15FKEDFWk%2FT%2B4EUjN4cf%2B8ukHkj%2BXIc%2BBdHiKlC2z1lSaveNTk4ZHzaFPoxBFfJBYbK8oIvB9%2B44l2%2B%2BK05CFuJBtyc37V0dEL%2FKGFLHCcsa6ZioSZH15vh4%2FMkdIAl2jD81xujOS7hekO8o7lIEs7bsS7ddPPUYuw3Xsi3bJo8r9eq8oRKzsviYDcU6CL51Toi9xJcPGZiAehSM252054%2BSmGEkN3L8E%2FZEzhVEL%2FnB6bEwEOlTAZnYA6rk8oHPbQhuP3osN%2BWrgqIOm5MS59p%2FozIHDr3jaAlJKHzmB1CDl0Yxev8YbMiU0fQ9qxD2t0q%2BI6ZSvxa6RUs0ZYugb8a1SiXlMHbSzdu04btFe4Zim7%2BDEhPnjNqMiB2Axf3sIXVCdY4RPo6GYgviuCIJxDsFcD3Zg0nEhEh6YYlrKbrCo3Sc8LV2aqKvv70ngSKz07wNBP6wMrkX0MPmB4r0GOqUBTWN9B3p%2F9MAerR5nLtLrfx4YWye66hXJ%2FmsQTshlm37%2F%2Bo0FC3QuPbuD%2FxRgQPVOlboZI13H1Ld2GWubgKPsUeHBy%2BKRAEZMVwts57gfRX0BOk21ZxxSYt%2BlivA0m9wwPUxVPj8fgtedwwRo6%2Bzj%2FivMoWSnujlNgl9yXwryu5yVK5m2paRstugnXwQ5ukGjyAEWrV7FdG3kNuY0z0IVMvnui9o7&X-Amz-Signature=ab43604d8dd2c97f9eca9a9d9aadfad2b95aad11eb9dc885261bbba1566eeaa5&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TIDQSUPR%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T142148Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEK7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCSyQQAp%2Bn%2FkCUJ7wSTkyvYbOXNN4L0YTLcSjwOi15uRAIhAK8oziX8fh36Ahe3%2BUNoRGnj4XVICcQ%2B222EA2%2BIjpigKogECNf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igxlra%2F6hflzPcOjK3Yq3AMSS8eGqmUmcYcPy8k3z61e3tnaukPonANw0MOivxfbB3YUCzfQjqfEIncp5LDpLGzCNdP9%2Bx3b59mYyfXDMWXOdeJDU6hvnDOr2xBfN9XdCBkI8xzIy7ffyojgFfhxF3RIpR0s1IqpE%2BIYuhB8EkwUgAJYY244WPJWR%2FRX045CYZxixztdnLHRG5Bxy3xAnYifkPi85M7B%2BjXJL%2FF61BNJV2LFUihc%2FwtjYSDa7ikWxc%2BRzzhXCOe1S0zWhYAN67yN6fiHvnHZWrfnrv9t0RfMopZhfdKcMqOra6P4%2BjKsDiF3nDlHTiFE5CbXI0VPEQ1LfE3ynUrzU%2BqFGdXB2yfOkq7IRtHSXpFEWsneNKMIpA2TzybBq5mGDlRyJ3W0VSch62YaAu8UJfpFIEEhYar7DZzHn4Xq%2FBnWLTB5pdO6GtnpgwAXFSvrBQyyDAdgcolgvXlJuISHfHNg9cwP6yW4HwaL2GXp1PFxb5C%2BtYPi2U5UVAfvX2Hv5NszR1WW6YqEIizQctOrUY48XLfsE%2FvmwAbm88wI16lgZqWVfT5SerDc%2FkmuIu5uXh34LU4p%2Bxj%2BtH3Q13U6Z2dGKZnX7MFDegpOPKwzU%2BmwEXaPSmkibq7J0O%2BX6nzX0Hgl9zDKguK9BjqkASWYFwaQyaGYgLI4%2FokBafTjqUNVsnK0EkGtPGemXKH4PFwwC7TTTlBH4NvVx1LjIwRWbZ2vRmSA4iIF2ck8shmzGm3GOJD%2BstlqKdrrlVTU1gIKrcgDSfQWaCfzZYmpu3fNxR0zlLwI5Iput6m3vMqktsGOxtvDWUtFAnx6i4vmhUqGPIJLSoT0fHtw2USeKdIb0Ci0HtFhzpUxX2cPSK%2B%2FKxsT&X-Amz-Signature=aad08e8998f86fe063a3797ed21c4e7baa059ac5f2f97676b68d7725067e0c53&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RHLFQK24%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T142149Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEK7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDOKi4g6zDbRe9lh7vddT2%2BjdSoDFxCV0rVPK4cv4UrKAIgeNZPZdPe2PIjHb0qp41jBTV2LShz0DgSlXMh6OB8G7cqiAQI1%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPy%2BJykdtCW2AhZGsSrcA972JLiPPIaOYEIto5WHOdoqJ74JfgKhBpA9Gl7X%2FvLNIAuplmMMcjZW8Cm4IXq0btcKkrZzEuFM2jDOWaBJSvAvUG5wxIZrubXaY%2FDLGRfrWmouEOH5BDiDWAJ0M7fmapRBCryG2fR32ydt1J4YrjIF0FFhGfA2TWtgWjEuXl63ewH6w%2BN5xjCCaFU%2F87t6oY4Ri0Up1E3uDDpfzg2m%2BZDfbtzLfAHd7PwsT5kJ3tX3KBqh4tIUF1VMZ%2BnjQAgLm5T4c3V8fAOJPN1gbgvMKGNZpSYjIwP9J%2F1UwM%2BkrFxBphxjRh1dCXi6NOnUaVqMORYTbYl6DCzigPsGJlqId3r%2BKa1YIafWqYh4t%2FBrn1rw%2BcwGIswxQ5F4dzA0L6LXeEOjQwz81eHRibTbgi9HFMaFzVv0TA%2FS%2F5GjHXrHr%2B%2Fv2ipxiMprdV2UAwcrc8tVlDHDkm4V42XB%2FGQGejKcs%2BC%2FrMtzJVyiISmia4WyB9tD7CRUX5P4LThktJTpirJ%2FVoYleC4bjMe7nrtcRq0%2FDAfJm2LltSBWRQ7dT%2BPQCF8Z07ya6VfzksgWMi1qNfcGpccWRrpMZOQZqw6XC5ucUO1mP461NaW0iJB6YWrCH0qG1FgLusohNOEFRWKQMIaC4r0GOqUBEYFIRBuoDoxxFOMu8V6eYF3xLjpvfx4zilCtXE6QLxlsMWz3TOkZwYPDmnu8Mm60HBD5VusfAJvr1TBvc6pSvN5xpO%2FsPZcY3hj15JbWQ4Es1EtwsnsG23oDk6hT0XQSMkfAZIOeBCNawSZib3Y3KJxWHk%2FQ9GW1icWv6C%2Ba1DM3FJPAnErHUlvtU5Szh%2BBK5fG6mgOMvfIGYEreT3hYRzGtmg6W&X-Amz-Signature=6329a6407627a70dd6185965f46a97b28865366d652c54056c01685ced6757fa&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZGJ6OIYI%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T142147Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEK7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCLSW2XXTAq7yQpcNue5mVDpCRX2v6287yZB5viVtwevwIgKdrQJzT3AQpjh3A2fmIVUdovELhbfyVREHERXjOGr9cqiAQI1%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLF7BYGwx8lTpt62qircA0HQuoU9vnK2mfuQD2OzdEhhkIDnkuuhxwk1VxYn4815s5aESzzsDp8AZfnHL2zgY0i%2BjUYIDzlGaucYuuLFioxtJTq6ohmg0UNpkajxrCHhKYtgu9PKaVrRWhjyHuKo%2FOOVhZWMaymNQpG5ERMX3%2Ffvb%2FG%2FBB8Fa6t1E3hKElYkttF15FKEDFWk%2FT%2B4EUjN4cf%2B8ukHkj%2BXIc%2BBdHiKlC2z1lSaveNTk4ZHzaFPoxBFfJBYbK8oIvB9%2B44l2%2B%2BK05CFuJBtyc37V0dEL%2FKGFLHCcsa6ZioSZH15vh4%2FMkdIAl2jD81xujOS7hekO8o7lIEs7bsS7ddPPUYuw3Xsi3bJo8r9eq8oRKzsviYDcU6CL51Toi9xJcPGZiAehSM252054%2BSmGEkN3L8E%2FZEzhVEL%2FnB6bEwEOlTAZnYA6rk8oHPbQhuP3osN%2BWrgqIOm5MS59p%2FozIHDr3jaAlJKHzmB1CDl0Yxev8YbMiU0fQ9qxD2t0q%2BI6ZSvxa6RUs0ZYugb8a1SiXlMHbSzdu04btFe4Zim7%2BDEhPnjNqMiB2Axf3sIXVCdY4RPo6GYgviuCIJxDsFcD3Zg0nEhEh6YYlrKbrCo3Sc8LV2aqKvv70ngSKz07wNBP6wMrkX0MPmB4r0GOqUBTWN9B3p%2F9MAerR5nLtLrfx4YWye66hXJ%2FmsQTshlm37%2F%2Bo0FC3QuPbuD%2FxRgQPVOlboZI13H1Ld2GWubgKPsUeHBy%2BKRAEZMVwts57gfRX0BOk21ZxxSYt%2BlivA0m9wwPUxVPj8fgtedwwRo6%2Bzj%2FivMoWSnujlNgl9yXwryu5yVK5m2paRstugnXwQ5ukGjyAEWrV7FdG3kNuY0z0IVMvnui9o7&X-Amz-Signature=057a260b9b742552d203b83706fab60676addbdb91caa6ee0719065351e9715d&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZGJ6OIYI%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T142147Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEK7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCLSW2XXTAq7yQpcNue5mVDpCRX2v6287yZB5viVtwevwIgKdrQJzT3AQpjh3A2fmIVUdovELhbfyVREHERXjOGr9cqiAQI1%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLF7BYGwx8lTpt62qircA0HQuoU9vnK2mfuQD2OzdEhhkIDnkuuhxwk1VxYn4815s5aESzzsDp8AZfnHL2zgY0i%2BjUYIDzlGaucYuuLFioxtJTq6ohmg0UNpkajxrCHhKYtgu9PKaVrRWhjyHuKo%2FOOVhZWMaymNQpG5ERMX3%2Ffvb%2FG%2FBB8Fa6t1E3hKElYkttF15FKEDFWk%2FT%2B4EUjN4cf%2B8ukHkj%2BXIc%2BBdHiKlC2z1lSaveNTk4ZHzaFPoxBFfJBYbK8oIvB9%2B44l2%2B%2BK05CFuJBtyc37V0dEL%2FKGFLHCcsa6ZioSZH15vh4%2FMkdIAl2jD81xujOS7hekO8o7lIEs7bsS7ddPPUYuw3Xsi3bJo8r9eq8oRKzsviYDcU6CL51Toi9xJcPGZiAehSM252054%2BSmGEkN3L8E%2FZEzhVEL%2FnB6bEwEOlTAZnYA6rk8oHPbQhuP3osN%2BWrgqIOm5MS59p%2FozIHDr3jaAlJKHzmB1CDl0Yxev8YbMiU0fQ9qxD2t0q%2BI6ZSvxa6RUs0ZYugb8a1SiXlMHbSzdu04btFe4Zim7%2BDEhPnjNqMiB2Axf3sIXVCdY4RPo6GYgviuCIJxDsFcD3Zg0nEhEh6YYlrKbrCo3Sc8LV2aqKvv70ngSKz07wNBP6wMrkX0MPmB4r0GOqUBTWN9B3p%2F9MAerR5nLtLrfx4YWye66hXJ%2FmsQTshlm37%2F%2Bo0FC3QuPbuD%2FxRgQPVOlboZI13H1Ld2GWubgKPsUeHBy%2BKRAEZMVwts57gfRX0BOk21ZxxSYt%2BlivA0m9wwPUxVPj8fgtedwwRo6%2Bzj%2FivMoWSnujlNgl9yXwryu5yVK5m2paRstugnXwQ5ukGjyAEWrV7FdG3kNuY0z0IVMvnui9o7&X-Amz-Signature=576c028139addb3565c323b0d4dde7e3f15b95c949318471033574c561b29aaa&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZGJ6OIYI%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T142147Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEK7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCLSW2XXTAq7yQpcNue5mVDpCRX2v6287yZB5viVtwevwIgKdrQJzT3AQpjh3A2fmIVUdovELhbfyVREHERXjOGr9cqiAQI1%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLF7BYGwx8lTpt62qircA0HQuoU9vnK2mfuQD2OzdEhhkIDnkuuhxwk1VxYn4815s5aESzzsDp8AZfnHL2zgY0i%2BjUYIDzlGaucYuuLFioxtJTq6ohmg0UNpkajxrCHhKYtgu9PKaVrRWhjyHuKo%2FOOVhZWMaymNQpG5ERMX3%2Ffvb%2FG%2FBB8Fa6t1E3hKElYkttF15FKEDFWk%2FT%2B4EUjN4cf%2B8ukHkj%2BXIc%2BBdHiKlC2z1lSaveNTk4ZHzaFPoxBFfJBYbK8oIvB9%2B44l2%2B%2BK05CFuJBtyc37V0dEL%2FKGFLHCcsa6ZioSZH15vh4%2FMkdIAl2jD81xujOS7hekO8o7lIEs7bsS7ddPPUYuw3Xsi3bJo8r9eq8oRKzsviYDcU6CL51Toi9xJcPGZiAehSM252054%2BSmGEkN3L8E%2FZEzhVEL%2FnB6bEwEOlTAZnYA6rk8oHPbQhuP3osN%2BWrgqIOm5MS59p%2FozIHDr3jaAlJKHzmB1CDl0Yxev8YbMiU0fQ9qxD2t0q%2BI6ZSvxa6RUs0ZYugb8a1SiXlMHbSzdu04btFe4Zim7%2BDEhPnjNqMiB2Axf3sIXVCdY4RPo6GYgviuCIJxDsFcD3Zg0nEhEh6YYlrKbrCo3Sc8LV2aqKvv70ngSKz07wNBP6wMrkX0MPmB4r0GOqUBTWN9B3p%2F9MAerR5nLtLrfx4YWye66hXJ%2FmsQTshlm37%2F%2Bo0FC3QuPbuD%2FxRgQPVOlboZI13H1Ld2GWubgKPsUeHBy%2BKRAEZMVwts57gfRX0BOk21ZxxSYt%2BlivA0m9wwPUxVPj8fgtedwwRo6%2Bzj%2FivMoWSnujlNgl9yXwryu5yVK5m2paRstugnXwQ5ukGjyAEWrV7FdG3kNuY0z0IVMvnui9o7&X-Amz-Signature=fd00cbea004c161d1431d349319187def857ab9a0ad4ee12b96658181f55fc93&X-Amz-SignedHeaders=host&x-id=GetObject)


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

